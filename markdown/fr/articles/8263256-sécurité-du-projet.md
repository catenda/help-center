# Sécurité du projet

## 1. **Stockage des données**

### 1.1 **Compte actif ou inactif - Statut**

Lors d'une relation active avec une entreprise, les informations du projet sont généralement maintenues au sein des organisations de plateforme pour soutenir l'accès continu. Les projets qui sont en attente ou figés mais restent partie d'une configuration de compte active peuvent continuer à être accessibles pour les activités de référence et de maintenance. Dans ces cas, les données restent disponibles tant que l'organisation de plateforme maintient son Statut actif.

### 1.2 **Rétention et Récupération**

Lorsqu'un projet est transitionné vers un Statut expiré ou supprimé manuellement, actions signifiant qu'il n'est plus associé à une organisation de plateforme active, la plateforme est conçue avec l'intention de pouvoir maintenir les données du projet pendant une période allant jusqu'à trois ans. Au cours de cette fenêtre prévue, les projets peuvent être récupérés et rouverts à tout moment, à condition qu'une relation active avec l'entreprise soit maintenue. La période de rétention et la capacité à restaurer les données sont strictement soumises aux exigences légales et réglementaires de la juridiction dans laquelle le projet est situé. Dans les cas où les lois locales concernant la gestion des données logicielles imposent une suppression antérieure, ces exigences juridictionnelles prennent préséance sur le comportement standard de la plateforme. Pour assurer que les informations sont préservées selon les besoins internes ou juridictionnels, il est recommandé d'[utiliser les outils d'exportation disponibles](https://support.catenda.com/en/articles/7946690-exporting-all-project-data) pour effectuer une sauvegarde finale avant toute expiration ou suppression de projet.

### 1.3 **Données sur le territoire national**

Les données standard de la plateforme sont hébergées dans des régions sécurisées et établies. Bien que les configurations actuelles soient centralisées, il peut y avoir des possibilités d'établir une résidence des données dans des emplacements géographiques spécifiques pour s'aligner sur les exigences juridictionnelles locales. Les organisations ayant des besoins d'hébergement uniques ou "sur le territoire national" sont encouragées à contacter le support à [support@catenda.com](mailto:support@catenda.com) pour discuter des possibilités techniques potentielles et des configurations.

## 2. **Partage des données avec des personnes en dehors du projet**

Des Liens peuvent être créés pour partager à la fois des modèles et des Documents avec des parties externes. Toute personne ayant accès à un tel Lien n'aura pas besoin de compte pour afficher le modèle ou télécharger les Documents. Les Documents peuvent être partagés en créant une URL ouverte d'une collection de Documents. _Accès requis :_ Membre du projet

Les modèles peuvent être partagés en créant une URL ouverte d'un Signet. _Accès requis :_ Administrateur

Il est possible de demander que ces types d'URL soient désactivés pour tous vos projets.

## 3. **Téléchargement de données**

Les fichiers peuvent être téléchargés en tant que révisions de document dans la section Documents.

### 3.1 **Limitation du téléchargement avec contrôle d'accès**

**Documents / modèles** L'accès aux Documents peut être contrôlé individuellement. Si l'accès au Document IFC est limité, seules les personnes ayant accès au Document pourront le voir. Les Membres ayant accès au Document pourront le télécharger.

**Topics** L'accès aux topics peut être contrôlé par topic board. Si l'accès à un topic board est limité, seules les personnes ayant accès au topic board pourront voir les topics du tableau. Les Membres ayant accès au topic board pourront exporter les topics au format BCF, PDF et Excel.

### 3.2 **Limitation du téléchargement en retirant une révision**

Si une révision est présente dans un Document qui ne devrait pas y être, un administrateur peut retirer la révision. Après le retrait d'une révision, elle ne peut plus être visualisée ou téléchargée nulle part par personne.

### 3.3 **Limitation du téléchargement de topics individuels**

Pour conserver les relations aux éléments comme les Documents, les topics et les objets, un topic peut être archivé. Les topics peuvent être déplacés vers un autre topic board. Le topic board peut ensuite être archivé. _Accès requis :_ Administrateur

Tant que le topic est dans le topic board archivé, les relations d'éléments resteront intactes mais ne seront pas visibles sur l'élément associé. Si un topic board est restauré, les éléments associés afficheront à nouveau leur relation au topic.

### 3.4 Limitation du téléchargement de modèles

Si le Document est un Document IFC, il peut être Lié à un modèle.

_Au sein du projet_ Même si le Document est Lié à un modèle, seules les personnes ayant accès au Document le verront apparaître sur le Tableau de bord, la page des modèles et dans le sélecteur de révision.

**Partage externe** Si un modèle est partagé avec un Lien public dans un Signet, l'aperçu du modèle peut uniquement être visualisé et non téléchargé.

Les informations sur les objets ne sont pas visibles dans les Signets partagés en externe.

## 4. **Suppression de données**

**Documents/modèles** Les Membres peuvent supprimer des Documents mais les administrateurs d'un projet pourront toujours trouver des Documents en effectuant une recherche avec le Filtre "supprimé". Gardez à l'esprit que ce Filtre est spécifique à la langue.

**Topics** Avant la suppression, les topics peuvent être exportés au format BCF. Le topic portant cet ID sera supprimé, mais si vous modifiez l'ID dans le BCF, le topic peut être réimporté. Les relations aux éléments comme les Documents, les objets et les topics seront alors perdues.

**Milestones** Les Membres peuvent archiver et restaurer les milestones. _Accès requis :_ Créateur de milestone ou administrateur.
