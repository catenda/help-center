# Dépannage du connecteur Solibri BCF Live

Les erreurs qui peuvent être rencontrées lors de l'intégration des documents Solibri et comment les résoudre sont expliquées dans cet article.

## 1. **Support et dépannage**

Le connecteur BCF Live est développé, maintenu et possédé par Solibri. Comme cette intégration est un produit indépendant créé par Solibri pour se connecter à l'API Catenda, notre support est axé sur l'échange de données plutôt que sur la mécanique interne du logiciel Solibri lui-même.

### 1.1 **Pour les questions de flux de travail et de données**

Si vous avez besoin d'aide pour comprendre le fonctionnement des fonctionnalités au sein de l'intégration, ou comment les informations sont représentées dans Catenda une fois synchronisées, notre équipe est heureuse de vous aider. Nous pouvons vous aider à naviguer dans le flux de travail prévu et à assurer que les données de votre projet communiquent correctement entre les deux plateformes.

### 1.2 **Pour les problèmes techniques et fonctionnels**

Si des messages d'erreur spécifiques sont rencontrés dans l'interface Solibri, si le connecteur ne répond pas comme prévu, ou si une modification du fonctionnement du connecteur est souhaitée, veuillez contacter **[Solibri Support](https://www.solibri.com/support)** directement. En tant que développeurs et propriétaires du connecteur, ils sont les seuls à pouvoir modifier le code sous-jacent, ajuster les règles de validation internes, ou dépanner les bogues spécifiques au logiciel.

## 2. **Modèle dupliqué**

Lorsque cette erreur est rencontrée, c'est généralement parce que le connecteur Solibri a identifié deux modèles partageant le même GUID IFCProject.

### 2.1 **Noms vs. IDs**

Catenda et le connecteur Solibri identifient les modèles en fonction de leur GUID unique, et non de leur nom de fichier.

Si deux fichiers différents de votre panier de sélection Solibri ont été exportés à partir du même fichier original dans votre outil de création (par exemple, Revit, ArchiCAD), ils partageront probablement le même GUID IFCProject.

Même si ces fichiers reçoivent des noms différents dans Solibri, le connecteur les reconnaît comme la même entité et déclenche un avertissement « Dupliqué » pour éviter les conflits de synchronisation des données.

### 2.2 **Comment vérifier le GUID dans Solibri**

Pour confirmer si vos modèles partagent le même identificateur, vérifiez les métadonnées directement dans Solibri :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ym9bebpy/01-how-to-verify-the-guid-in-solibri.png)

1. Sélectionnez le **modèle** dans l'arborescence du modèle Solibri.
1. Ouvrez l'**outil Info** ou l'onglet **Identité**.
1. Localisez le champ **GUID IFCProject**.

Si deux modèles affichent la même chaîne de caractères ici, le connecteur les traitera comme le même modèle.
