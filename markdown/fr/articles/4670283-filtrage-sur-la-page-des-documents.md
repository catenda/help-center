# Filtrage sur la page des documents

L'option de recherche ou de filtrage peut être vue dans la partie supérieure de la fenêtre. En écrivant le nom du document ou le nom d'une étiquette épinglée à un document, les lignes du tableau des documents peuvent être réduites. Voici à quoi le menu de recherche ou de filtrage peut ressembler sur la page des documents :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aa862mj2/01-intro.png)

## 1. **Filtres**

Cliquez sur le bouton de filtrage en haut à gauche pour qu'un panneau apparaisse sur le côté gauche. Lorsqu'un filtre est appliqué, l'URL visible dans le navigateur change. Dans cet article, les filtres sont affichés comme suit : _Nom du filtre dans le menu_ - `Nom du filtre dans l'URL=Option de filtre dans l'URL`

**Filtre par défaut** Le filtre par défaut n'est initialement pas visible dans l'URL. Lorsque la page est accédée pour la première fois, le filtre suivant est appliqué. Onglet Espace de travail - `v=all`

### 1.1 **Enregistrer et partager le filtre actuel**

Accédez à l'URL d'une page filtrée pour charger cette page avec le filtre appliqué. Les filtres appliqués peuvent être enregistrés en haut du menu de filtrage. Cliquez [ici](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) pour en savoir plus sur la façon d'enregistrer et de partager les filtres. Notez que contrairement aux autres menus de filtrage, il n'est pas possible d'enregistrer les filtres personnels en haut du menu de filtrage sur la page des approbations.

### 1.2 **Masquer les filtres vides**

Cliquez [ici](https://support.catenda.com/en/articles/8551755-saving-filters) pour en savoir plus sur la limitation des résultats des filtres.

### 1.3 **Onglets**

Onglet Espace de travail - `v=all` Onglet Publié - `v=published`

### 1.4 **Liens**

Lié - `associations=exists&subFolders=true` Filtrer les documents liés aux objets de modèle dans la Visionneuse 3D.

Non lié - `associations=does-not-exist&subFolders=true` Filtrer les documents qui ne sont pas liés aux objets de modèle dans la Visionneuse 3D.

Lié aux objets sélectionnés - `link=backlink&subFolders=true` Si le panneau 3D n'est pas déjà ouvert, il s'ouvrira. Sélectionnez des objets à partir d'un modèle dans la Visionneuse 3D pour filtrer les sujets liés aux objets sélectionnés.

### 1.5 **Statut (dernière révision) - Statut flux de travail uniquement**

Publié - `documentStatus=published&subFolders=true&documentType=file` Statut manquant - `documentStatus=published-without-status&subFolders=true` Statut publié du projet - `documentStatus=<GUID>&subFolders=true` Partagé - `documentStatus=shared&subFolders=true&documentType=file` Les statuts partagés ne sont disponibles que dans l'onglet Espace de travail Statut partagé du projet - `documentStatus=<GUID>&subFolders=true` N'a pas de révision - `documentStatus=no-stage&subFolders=true`

### 1.6 **Brouillons - Statut flux de travail uniquement**

A des brouillons nouveaux - `newDrafts=exists&subFolders=true` Nom du statut de brouillon - `newDrafts=<Draft status GUID>&subFolders=true` S'il y a plusieurs statuts de brouillon, chaque statut de brouillon peut être filtré. N'a pas de brouillons nouveaux - `newDrafts=does-not-exist&subFolders=true`

### 1.7 **Modèles**

Est un modèle - `model=is-model&subFolders=true` N'est pas un modèle - `model=is-not-model&subFolders=true`

### 1.8 **Document créé par**

Nom du membre - `owner=<Member GUID>&subFolders=true`

### 1.9 **Révision créée par**

Nom du membre - `revisionCreatedBy=<GUID>&subFolders=true`

### 1.10 **Publié par**

Nom du membre - `publishedBy=<Member GUID>&subFolders=true`

### 1.11 **Filtres de date**

Publié - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Cliquez sur Sélectionner des dates pour sélectionner les dates entre lesquelles vous souhaitez effectuer une recherche Cliquez [ici](https://support.catenda.com/en/articles/6511685-date-filter) pour en savoir plus sur le filtre de date

### 1.12 **Approbations ouvertes - Statut flux de travail uniquement**

Nom de l'approbation - `approval=<Approval number>&subFolders=true`

### 1.13 **Documents - Étiquettes**

Toutes les étiquettes qui ne font pas partie d'un groupe d'étiquettes seront affichées dans un menu appelé Documents. Nom de l'étiquette - `labels=<Label GUID>6&subFolders=true`

### 1.14 **Nom du groupe d'étiquettes**

Il y aura un menu par nom de groupe d'étiquettes Nom de l'étiquette - `labels=<Label GUID>6&subFolders=true`

Le contenu des champs personnalisés où les valeurs peuvent être configurées peut être filtré en écrivant une phrase de recherche dans la barre de recherche ou de filtrage et en sélectionnant le filtre correspondant dans le filtre suggéré.

### 1.15 **Champ personnalisé**

_Le champ personnalisé a une valeur_ - `custom-field-has-value-<Custom field GUID>=true` Avec l'option "a une valeur" dans le menu de filtrage, tous les sujets qui ont une valeur configurée pour ce champ personnalisé peuvent être filtrés. Types de champs personnalisés qui peuvent être filtrés sur a une valeur : Date Décimal Liste déroulante Entier Texte

_Valeur spécifique du champ personnalisé_ - `custom-field-item-<Custom field GUID>=<Value GUID>` Les valeurs spécifiques dans les champs pour les champs avec jusqu'à 10 valeurs peuvent être filtrées. Types de champs personnalisés qui peuvent être filtrés sur une valeur spécifique à partir du menu de filtrage : Liste déroulante

Certaines valeurs dans les champs personnalisés où les valeurs peuvent être configurées peuvent être filtrées. Filtrez les valeurs en écrivant une phrase de recherche dans la barre de recherche ou de filtrage et en sélectionnant le champ personnalisé correspondant. Types de champs personnalisés qui peuvent être filtrés en tapant dans la barre de recherche ou de filtrage : Décimal Liste déroulante Entier Texte

_Le champ personnalisé n'a pas de valeur_ - `custom-field-has-value-<Custom field GUID>=false` Filtrer tous les sujets où un champ personnalisé n'a aucune valeur. Types de champs personnalisés qui peuvent être filtrés sur aucune valeur : Date Décimal Liste déroulante Entier Texte

> **Remarque :** Les champs personnalisés définis comme obligatoires auront toujours une valeur. Vous ne pourrez donc pas rechercher "a une valeur" ou "n'a pas de valeur" et ne pourront donc pas être recherchés pour un champ personnalisé défini comme obligatoire.

### 1.16 **Collections**

Nom de la collection - `collections=<GUID>&subFolders=true`

### 1.17 **Supprimé**

Supprimé - `deleted=deleted&subFolders=true` Voir [ici](https://support.catenda.com/en/articles/4670249-undeleting-restoring-documents-or-folders) comment rechercher les documents supprimés

## 2. **Recherche textuelle**

_Recherche textuelle_ - `search=test&subFolders=true`

### 2.1 **Contenu qui peut être recherché**

Titre du document Titre du dossier

### 2.2 **Casse**

La recherche textuelle ne tient pas compte de la casse des caractères.

### 2.3 **Quantités de caractères**

Un seul caractère - Les titres qui incluent le caractère recherché sont mis en correspondance. Deux caractères - Aucun résultat. Trois caractères ou plus - Les titres qui ont un seul mot, séparé par un caractère de séparation comme un espace, qui correspond à la phrase de recherche sont inclus dans les résultats.

### 2.4 **Types de fichiers**

Si le titre inclut une extension, l'extension peut être recherchée avec la recherche textuelle régulière. Recherchez l'extension du fichier avec le point inclus pour rechercher un type de fichier spécifique. Par exemple, lors de la recherche sur .ifc, tous les documents avec .ifc dans le titre peuvent être trouvés.

## 3. **Tri**

Les documents peuvent être triés en cliquant sur l'en-tête de chaque colonne. L'en-tête peut être cliqué plusieurs fois pour annuler ou désactiver le tri.

_Titre, a-z_ - Par défaut _Nom, z-a_ - `sort=name-desc` _Publié, le plus récent en premier_ - `sort=publishedAt-desc` _Publié, le plus ancien en premier_ - `sort=publishedAt-asc` _Créé, le plus récent en premier_ - `sort=createdAt-desc` _Créé, le plus ancien en premier_ - `sort=createdAt-asc`
