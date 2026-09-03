# Filtrage sur la page des modèles

L'option de recherche ou de filtre est visible en haut de la fenêtre. En écrivant le nom du modèle, le nom d'une étiquette épinglée à un modèle ou le nom d'utilisateur d'un membre, les lignes du tableau des modèles peuvent être réduites. Voici à quoi le menu de recherche ou de filtre peut ressembler sur la page des modèles :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qfd47nkw/01-intro.png)

Dans la barre de recherche, vous pouvez rechercher n'importe quel modèle disponible dans le tableau des modèles.

## 1. **Panneau de filtre gauche**

En cliquant sur le bouton de filtre, un panneau s'affiche sur le côté gauche. Cochez les cases pour affiner la recherche. Ces filtres peuvent être enregistrés en haut de la liste de filtres. Lorsque l'un de ces filtres est appliqué, le texte du filtre est ajouté à votre URL. Si l'URL de la page filtrée est partagée, la personne qui l'ouvre verra le même filtre dans le même dossier que celui actuellement affiché, à condition qu'elle y ait accès. Lorsque vous survolez l'un des filtres du panneau de gauche, vous pouvez cliquer sur « seulement » à droite du filtre pour supprimer tous les autres filtres précédemment appliqués.

## 2. **Filtres enregistrés**

Cliquez [ici](https://support.catenda.com/en/articles/8551755-saving-filters) pour en savoir plus sur la façon d'enregistrer un ensemble de filtres

## 3. **Filtres**

Cliquez sur le bouton de filtre en haut à gauche pour qu'un panneau s'affiche sur le côté gauche. Lorsqu'un filtre est appliqué, l'URL visible dans le navigateur change. Dans cet article, les filtres sont affichés comme suit : _Nom du filtre dans le menu_ - `Nom du filtre dans l'URL=Option de filtre dans l'URL`

**Filtre par défaut** Le filtre par défaut n'est initialement pas visible dans l'URL. Lorsque la page est visitée pour la première fois, le filtre suivant est appliqué. Onglet Espace de travail - `v=all`

### 3.1 **Enregistrer et partager le filtre actuel**

Accédez à l'URL d'une page filtrée pour charger cette page avec le filtre appliqué. Les filtres appliqués peuvent être enregistrés en haut du menu de filtre. Cliquez [ici](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) pour en savoir plus sur la façon d'enregistrer et de partager des filtres

### 3.2 **Masquer les filtres vides**

Cliquez [ici](https://support.catenda.com/en/articles/8551755-saving-filters) pour en savoir plus sur la limitation des résultats de filtre.

### 3.3 **Onglets**

Onglet Espace de travail - `v=all` Onglet Publié - `v=published`

### 3.4 **Liens**

Lié - `associations=exists&subFolders=true` Non lié - `associations=does-not-exist&subFolders=true` Lié aux objets sélectionnés - `link=backlink&subFolders=true`

### 3.5 **Statut (dernière révision) - Statut flux de travail uniquement**

Publié - `documentStatus=published&subFolders=true&documentType=file` Statut manquant - `documentStatus=published-without-status&subFolders=true` Statut publié du projet - `documentStatus=<GUID>&subFolders=true` Partagé - `documentStatus=shared&subFolders=true&documentType=file` Les statuts partagés ne sont disponibles que dans l'onglet Espace de travail Statut partagé du projet - `documentStatus=<GUID>&subFolders=true` Aucune révision - `documentStatus=no-stage&subFolders=true`

### 3.6 **Brouillons - Statut flux de travail uniquement**

Contient de nouveaux brouillons - `newDrafts=exists&subFolders=true` Nom du statut du brouillon - `newDrafts=<Draft status GUID>&subFolders=true` S'il y a plusieurs statuts de brouillon, chaque statut de brouillon peut être filtré. Aucun nouveau brouillon - `newDrafts=does-not-exist&subFolders=true`

### 3.7 **Document créé par**

Nom du membre - `owner=<Member GUID>&subFolders=true`

### 3.8 **Révision créée par**

Nom du membre - `revisionCreatedBy=<GUID>&subFolders=true`

### 3.9 **Publié par**

Nom du membre - `publishedBy=<Member GUID>&subFolders=true`

### 3.10 **Filtres de date**

Publié - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Cliquez sur Sélectionner les dates pour sélectionner les dates entre lesquelles vous souhaitez effectuer une recherche. Cliquez [ici](https://support.catenda.com/en/articles/6511685-date-filter) pour en savoir plus sur le filtre de date

### 3.11 **Approbations ouvertes - Statut flux de travail uniquement**

Nom de l'approbation - `approval=<Approval number>&subFolders=true`

### 3.12 **Étiquettes**

Toutes les étiquettes qui ne font pas partie d'un groupe d'étiquettes s'affichent dans un menu appelé étiquettes. Nom de l'étiquette - `labels=<Label GUID>6&subFolders=true`

### 3.13 **Nom du groupe d'étiquettes**

Il y aura un menu par nom de groupe d'étiquettes Nom de l'étiquette - `labels=<Label GUID>6&subFolders=true`

### 3.14 **Collections**

Nom de la collection - `collections=<GUID>&subFolders=true`

## 4. **Recherche textuelle**

_Recherche textuelle_ - `search=test&subFolders=true`

### 4.1 **Contenu pouvant être recherché**

Nom du modèle

### 4.2 **Capitalisation**

La recherche textuelle n'est pas sensible aux caractères majuscules ou minuscules.

### 4.3 **Nombre de caractères**

Moins de trois caractères - Le tableau n'est pas filtré. Trois caractères ou plus - Les titres qui ont un seul mot, séparé par un caractère de séparation comme un espace, qui correspond à la phrase de recherche sont inclus dans les résultats.

### 4.4 **Types de fichiers**

Si le nom du modèle inclut une extension, l'extension peut être recherchée avec la recherche textuelle régulière. Recherchez l'extension de fichier en incluant le point pour rechercher un type de fichier spécifique. Par exemple, lors de la recherche sur .ifc, tous les documents contenant .ifc dans le nom du modèle peuvent être trouvés.

## 5. **Tri**

Les modèles peuvent être triés en cliquant sur l'en-tête de chaque colonne. L'en-tête peut être cliqué plusieurs fois pour inverser ou désactiver le tri.

_Nom, a-z_ - Par défaut _Nom, z-a_ - `sort=modelName-desc` _Nom du document, a-z_ - `sort=name-asc` _Nom du document, z-a_ -`sort=name-desc` _Publié, plus récent d'abord_ - `sort=publishedAt-desc` _Publié, plus ancien d'abord_ - `sort=publishedAt-asc` _Document créé, plus récent d'abord_ - `sort=createdAt-desc` _Document créé, plus ancien d'abord_ - `sort=createdAt-asc` Révision créée_, plus récente d'abord_ - `sort=revisionCreatedAt-desc` Révision créée_, plus ancienne d'abord_ - `sort=revisionCreatedAt-desc`
