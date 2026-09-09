# Flux de Travail de Statut - Mises à jour API

> Présentation des modifications de l'API de la nouvelle fonctionnalité Flux de Travail de Statut, qui distingue le statut partagé du statut publié selon l'ISO 19650. Pour les clients et partenaires d'intégration utilisant l'API Catenda.

Nous implémentons le **Flux de Travail de Statut**, une mise à jour importante de la façon dont Catenda gère les révisions de documents et de modèles. Ce changement introduit une distinction entre les révisions de travail et officielles qui peut nécessiter des ajustements à votre intégration.

## 1. Résumé Exécutif

Catenda fera la distinction entre :

- Les révisions **"Partagées"** (versions de travail/brouillon)
- Les révisions **"Publiées"** (versions officielles/approuvées)

**Action Immédiate Requise Si :**

- Votre application s'intègre à Catenda Hub
- Vous affichez les informations de révision aux utilisateurs
- Vous créez de nouvelles révisions via l'API
- Vous utilisez des extensions d'outils CAO

## 2. Ce qui Change

### 2.1 Types de Révisions

Auparavant, toutes les révisions étaient implicitement considérées comme « officielles ». Maintenant :

- **"Partagées"** : Révisions de travail collaboratives avec visibilité restreinte
- **"Publiées"** : Révisions officielles pour une distribution plus large

### 2.2 Modifications des Réponses API

L'**API Document** inclura de nouveaux champs pour les éléments de bibliothèque :

```
{  "document": {    "revision": {      "extendedVersion": {        "major": 1,        "minor": null  // ou 1,2,3 pour Partagées      },      "version": 5  // Numérotation héritée conservée    }  }}
```

Les modifications de l'**API Modèles** sont minimales :

- Ajoute une capacité de filtrage via le paramètre scope (scope=published ou scope=all)
- N'expose PAS le statut de révision ou la numérotation étendue
- Applique les permissions héritées des documents sous-jacents

### 2.3 Comportement par Défaut

**Important** : Les API retourneront **à la fois** les révisions « Partagées » et « Publiées » par défaut là où les utilisateurs ont accès. Cela maintient la compatibilité antérieure mais change fondamentalement la nature des données retournées.

## 3. Qui est Affecté et Comment

### 3.1 Non Affecté

- ✅ Applications API autonomes sans dépendance Catenda Hub
- ✅ Applications qui n'affichent ou ne gèrent pas les révisions

### 3.2 Significativement Affecté - Extensions d'Outils CAO

⚠️ **Problèmes Critiques :**

- Impossible de déterminer si les révisions créées sont « Partagées » ou « Publiées »
- Impossible d'afficher le statut de révision exact aux utilisateurs
- Peut afficher une numérotation différente de Hub (format séquentiel vs X.Y)
- Les utilisateurs ne comprendront pas le contexte de révision sans visibilité du statut

**Actions Requises pour les Développeurs d'Extensions :**

1. Évaluez si vous affichez les informations de révision
1. Envisagez d'ajouter des conseils aux utilisateurs sur les types de révisions
1. Préparez-vous à une possible confusion de l'utilisateur concernant les écarts de numérotation

### 3.3 Également Affecté

⚠️ Applications qui :

- Affichent les listes de révisions aux utilisateurs
- Créent de nouvelles révisions via API
- Dépendent de toutes les révisions étant « officielles »
- Utilisent l'intégration Catenda Site

## 4. Guide de Mise en Œuvre Technique

### 4.1 Filtrage des Révisions

Utilisez le nouveau paramètre scope pour contrôler quelles révisions sont retournées :

```
# API DocumentsGET /documents?scope=published     # Publiées uniquementGET /documents?scope=shared        # Partagées uniquement (nécessite la permission)GET /documents                     # Toutes (par défaut)# API Modèles  GET /models/revisions?scope=published  # Publiées uniquementGET /models/revisions                  # Toutes (par défaut)
```

### 4.2 Modifications des Permissions

Les nouveaux droits ACL affectent vos opérations :

- **Affichage des révisions « Partagées »** : Nécessite une permission spécifique
- **Création de révisions « Publiées »** : Possible uniquement via l'interface Catenda Hub
- **Création de révisions via API** : Crée les révisions « Partagées » par défaut

### 4.3 Ce que Vous Ne Pouvez Pas Faire via API

- ❌ Créer des révisions « Publiées » (Hub uniquement)
- ❌ Accéder au statut de révision dans l'API Modèles
- ❌ Voir la numérotation étendue (X.Y) dans l'API Modèles
- ❌ Déterminer les relations modèle-à-document

## 5. Considérations de Migration

**Projets Existants :**

- Toutes les révisions actuelles deviendront « Publiées » lors de la migration
- Les numéros de version deviennent des numéros de révision majeure (ex : v3 → 3)
- Aucune action requise pour les données historiques

**Nouveau Comportement :**

- Les nouvelles révisions créées via API = « Partagées » par défaut
- La publication nécessite une action manuelle dans Hub

## 6. Décisions Critiques pour Votre Mise en Œuvre

**Question 1** : Avez-vous besoin de révisions officielles uniquement ?

- **Oui** → Implémentez le filtrage `scope=published`
- **Non** → Préparez-vous à gérer les types de révisions mixtes

**Question 2** : Affichez-vous les informations de révision ?

- **Oui** → Préparez-vous à un écart de numérotation (particulièrement pour les utilisateurs de l'API Modèles)
- **Non** → Impact minimal attendu

**Question 3** : Les utilisateurs créent-ils des révisions via votre application ?

- **Oui** → Informez les utilisateurs qu'ils créent des révisions « Partagées »
- **Non** → Aucune action nécessaire

## 7. Limitations Connues et Solutions de Contournement

**Pour les Utilisateurs de l'API Modèles :**

- **Limitation** : Impossible d'accéder au statut de révision ou à la numérotation étendue
- **Solution de Contournement** : Utilisez le filtrage pour obtenir uniquement les types de révisions souhaités
- **Impact Utilisateur** : Confusion potentielle concernant les écarts de numérotation des révisions

**Pour les Utilisateurs de l'API Collection :**

- Actuellement, seules les révisions « Publiées » peuvent être ajoutées aux collections
- Cela peut changer en fonction des commentaires des clients

## 8. Ressources de Support

**Mises à Jour de Documentation Disponibles :**

- [Référence API Mise à Jour] - Inclut le nouveau paramètre `scope`

## 9. Foire aux questions

**Q : Mon intégration sera-t-elle rompue ?** R : Aucun changement de rupture au niveau de l'API, mais l'expérience utilisateur peut changer considérablement, particulièrement pour les extensions CAO.

**Q : Pourquoi ne puis-je pas voir le statut de révision dans l'API Modèles ?** R : Pour maintenir la compatibilité antérieure, l'API Modèles expose minimalement les fonctionnalités du Flux de Travail de Statut. Utilisez le filtrage pour contrôler les révisions retournées.

**Q : Comment les utilisateurs savent-ils quel type de révision ils créent ?** R : Via API, toutes les nouvelles révisions sont « Partagées ». Les utilisateurs doivent utiliser Catenda Hub pour créer des révisions « Publiées ».

**Q : Et si nous avons besoin de plus de temps pour nous adapter ?** R : Contactez-nous immédiatement. Le Flux de Travail de Statut sera activé progressivement, et nous pouvons discuter des options de calendrier pour votre organisation.
