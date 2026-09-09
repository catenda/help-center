# Page Objets

La page des objets se trouve comme une sous-page de la page des modèles. Un tableau contenant des informations sur les modèles du projet s'affiche. Les filtres de comparaison peuvent être combinés pour extraire uniquement les informations demandées. Cette page combine des éléments du menu QTO dans le panneau d'information et des bibliothèques de valeurs de propriété sur la page des bibliothèques et remplacera éventuellement les deux.

![Tableau de bord Modèles Signets Objets Étage Configurateur](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/01-intro.png)

## 1. **Rechercher ou filtrer**

Voici à quoi peut ressembler le menu de recherche ou de filtrage sur la page des objets

![Rechercher ou filtrer Sélectionner Plus Modèles Sélectionné Recherche textuelle](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/02-search-or-filter.png)

Cliquez [ici](https://support.catenda.com/en/articles/12353642-filtering-on-the-objects-page) pour en savoir plus sur le filtrage sur la page des objets.

## 2. **Tableau des produits**

Le tableau des produits peut ressembler à ceci :

![Sélectionné Menu d'action 3D télécharger paramètres colonne entité colonne GlobalId colonne LongName IfcProject IfcBuildingelementProxy une ligne est sélectionnée dans le tableau](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/03-products-table.png)

Cliquez [ici](https://support.catenda.com/en/articles/11748020-tables-on-catenda) pour en savoir plus sur la façon de travailler avec les tableaux dans Catenda.

### 2.1 **Qu'est-ce qu'un produit ?**

Le nom produits vient du fait que chaque ligne est un produit du processus qui se produit lors de l'importation d'un IFC.

### 2.2 **Informations affichées**

Dès que la dernière révision d'un modèle a fini de traiter, une ligne pour chaque produit qui a été reconnu dans le fichier ifc peut être affichée dans le tableau des produits. Seules les informations des dernières révisions des modèles du projet s'affichent.

### 2.3 **Actions sur les éléments sélectionnés**

Après avoir sélectionné une ligne d'élément, les actions sur les éléments sélectionnés apparaissent vers le haut du tableau des produits. Voici à quoi peut ressembler le menu des actions sur les éléments sélectionnés :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/04-selected-item-actions.png)

**Visionneuse** Cliquez sur l'icône 3D ou utilisez l'action de visionneuse pour sélectionner les éléments sélectionnés du tableau des objets dans la visionneuse 3D.

**Isoler** Utilisez l'action isoler pour isoler les éléments sélectionnés du tableau des objets dans la visionneuse 3D.

**Masquer les autres** Utilisez l'action Masquer les autres pour masquer tous les objets de la visionneuse 3D sauf les objets sélectionnés.

### 2.4 **Contenu de la ligne**

**Accès** Seules les lignes de produits des dernières révisions des modèles auxquels les membres ont accès sont affichées. _Accès requis -_ Lecture

**Ligne de produit** Les lignes de produit ne peuvent pas être ouvertes comme dans les autres tableaux. Les lignes de produit ne peuvent être affichées que dans la visionneuse 3D via le menu d'actions.

**Sélection** La sélection de lignes fonctionne légèrement différemment que dans les autres tableaux de Catenda. Contrairement aux autres tableaux de Catenda, la sélection ne se réinitialise pas lorsque vous accédez à une autre page et que vous revenez ou que vous modifiez un filtre. Dans le tableau des produits, la sélection n'est réinitialisée que lorsque la page est actualisée. Comme il y aura souvent des milliers d'objets sélectionnés, il est plus courant que les lignes sélectionnées ne soient pas visibles. Un filtre différent peut être appliqué de sorte que les lignes sélectionnées ne soient plus affichées dans le tableau, mais elles resteront sélectionnées.

### 2.5 **Exporter**

Cliquez sur le bouton de téléchargement en haut du tableau des produits pour l'exporter.

![Bouton de téléchargement](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/05-export.png)

Lignes Il n'est possible d'obtenir que toutes les lignes des modèles activés. La sélection de lignes ne limite pas les lignes dans les fichiers exportés. Le seul filtre qui peut limiter le nombre de lignes est le filtre des modèles. Bien que les lignes puissent sembler limitées dans le tableau, le fichier exporté comprendra toutes les lignes des modèles disponibles.

Colonnes Une colonne pour chaque colonne activée dans le tableau des produits est exportée vers le fichier. Cliquez [ici](https://support.catenda.com/en/articles/11748020-tables-on-catenda) pour en savoir plus sur la façon de gérer les colonnes du tableau.

**Exporter les objets** Choisissez d'exporter vers Excel ou CSV dans le menu d'exportation des objets :

![Exporter les objets Excel CSV](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/06-export.png)

**Préparation de l'export** Après avoir cliqué sur exporter, un menu s'affiche indiquant « Préparation du tableur » en bas à droite.

![Préparation de l'export Feuille de calcul en cours de préparation](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/07-export.png)

Pendant ce temps, il est sûr de continuer à naviguer dans Catenda tant que la page n'est pas actualisée. Lorsque le tableur devient disponible, il ressemble à ceci et le fichier commence à se télécharger dans le navigateur :

![Export prêt Feuille de calcul disponible](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/08-export.png)

### 2.6 **Colonnes**

Certaines colonnes du tableau des produits sont activées par défaut tandis que d'autres peuvent être masquées et doivent être activées. Voici à quoi peut ressembler la liste déroulante des colonnes du tableau des produits :

![Attributs Type GlobalId Nom Balise Projet Site Bâtiment Actualiser](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/09-columns.png)

**Activer/Désactiver** Activez ou désactivez toutes les colonnes avec ce bouton bascule

**Filtre** Tapez le nom d'une colonne ou d'une catégorie de colonne pour filtrer la liste déroulante des colonnes pour cette colonne. Il est possible que la colonne recherchée se trouve dans une catégorie de colonne rétractée, assurez-vous donc de développer chaque catégorie pour voir si le résultat s'y trouve.

**Réinitialiser** Cliquez sur le bouton Réinitialiser pour réinitialiser les colonnes par rapport aux colonnes par défaut

En fonction de l'ordre des colonnes configuré, les premières colonnes sont affichées tandis que le tableau peut devoir être fait défiler latéralement pour afficher les autres colonnes activées. Le paramètre d'ordre par défaut et de visibilité des colonnes sur la page des documents est le suivant :

- Attributs
  - Entité
  - GlobalId
  - LongName
  - Nom
  - ObjectType

De plus, le tableau des produits peut avoir un nombre quelconque de colonnes en fonction de la quantité de propriétés et d'ensembles de propriétés dans chacun des modèles. Chaque ensemble de colonnes a une catégorie principale avec des sous-catégories. Le bouton bascule peut être utilisé pour activer ou désactiver toute la catégorie. Les catégories peuvent être développées et chaque colonne de la catégorie peut être activée/désactivée individuellement.

**Préférences des colonnes** Contrairement à d'autres configurations de tableau, certaines préférences typiques qui peuvent être configurées sont verrouillées dans le tableau des produits.

Les préférences des colonnes ne sont pas enregistrées entre les sessions. Les colonnes ne peuvent pas être réorganisées, seules activées et désactivées. Il n'est pas possible de trier le tableau par une colonne différente en cliquant sur la cellule de la ligne d'en-tête de la colonne. Il n'est pas possible de modifier la direction de tri de la colonne par laquelle le tableau est trié. Il n'est pas possible de faire glisser la cellule de la ligne d'en-tête hors du tableau pour désactiver la ligne, les lignes doivent être désactivées via la liste déroulante des colonnes.
