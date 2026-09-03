# Créer un nouvel export de modèle

Cliquez sur le bouton plus vert en haut à droite de la [page d'export de modèle](https://support.catenda.com/en/articles/4670280-model-export) pour créer un nouvel export de modèle. Il y a quatre étapes pour créer un nouvel export de modèle. Voici à quoi peut ressembler la première étape du processus de création d'export de modèle :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/01-intro.png)

## 1. **Étape 1 - Sélectionner modèles et révisions**

À la première étape, la révision de chacun des modèles à inclure dans l'export peut être spécifiée. Commencez par sélectionner un modèle à inclure en cochant sa case. Une fois le modèle sélectionné, la révision à inclure dans cet export peut être sélectionnée.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/02-step-1-select-models-and-revisons.png)

À la première étape de l'export de modèle, les modèles à inclure dans l'export peuvent être sélectionnés.

> **Remarque 1 :** Si le modèle n'a pas de révisions pouvant être exportées, la case sera grisée. **Remarque 2 :** Une révision de modèle doit être traitée avec succès et ne pas être retirée pour être sélectionnable.

### 1.1 **Navigation**

Dès qu'un ou plusieurs modèles sont sélectionnés et que les révisions sont spécifiées, l'étape affichera Terminé. Passez à l'étape suivante en cliquant sur Suivant : Options de fusion en bas à droite de la page.

## 2. **Étape 2 - Options de fusion**

À la deuxième étape, les éléments liés au contenu du modèle dans le projet peuvent être fusionnés dans les fichiers ifc auxquels ils sont liés lors de l'export. Voici à quoi peut ressembler la page des options de fusion dans un nouveau projet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/03-step-2-merge-options.png)

Décochez les cases à cocher pour désélectionner les Bibliothèques de projet qui ne doivent pas être fusionnées dans les fichiers de modèle de l'export.

Dans un nouveau projet, les Bibliothèques disponibles sont :

### 2.1 **Documents**

Sélectionnez « Documents » pour insérer des liens d'URL Catenda vers tous les documents de projet qui ont été liés à des objets dans les fichiers IFC exportés.

### 2.2 **Liens**

Sélectionnez « Liens » pour insérer les Liens définis par l'utilisateur de la Bibliothèque de Liens qui ont été liés à des objets dans les fichiers ifc exportés.

### 2.3 **Bibliothèques définies par l'utilisateur**

Toute Bibliothèque créée dans le projet est affichée par le nom de la Bibliothèque ici. Voici à quoi cela peut ressembler après l'ajout de quelques Bibliothèques

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/04-user-defined-libraries.png)

Les types de Bibliothèques supportées incluent :

**Bibliothèques de Documents telles que les Bibliothèques Dropbox ou SharePoint** Connectez-vous avec Dropbox ou SharePoint et liez les éléments de votre Bibliothèque externe aux objets du modèle pour que les Liens Catenda vers ces éléments de Bibliothèque soient inclus dans l'ifc exporté.

**Bibliothèque de Liens** Incluez les Liens d'URL enregistrés de la Bibliothèque de Liens dans votre export IFC en les liant à des objets des modèles d'export sélectionnés.

**Bibliothèque de classification** Créez une Bibliothèque de classification en téléchargeant un CSV. Liez les éléments du CSV dans la Bibliothèque de classification aux objets du modèle. Les Bibliothèques de classification apparaissent par le nom de la Bibliothèque dans la liste des options de fusion. Lorsque la case à cocher d'une Bibliothèque de classification est sélectionnée, tous les éléments de la Bibliothèque de classification du CSV qui ont été liés aux objets dans les modèles d'export sélectionnés sont fusionnés dans l'IFC exporté. Les objets avec de tels Liens dans l'IFC reçoivent un Lien vers l'élément de la Bibliothèque de classification sur Catenda.

### 2.4 **Bibliothèques non supportées**

Les Bibliothèques non supportées incluent les Bibliothèques qui dépendent du contenu dynamique comme :

**Bibliothèques de recherche** Celles-ci recherchent les objets sélectionnés sur Internet

**Bibliothèques de valeur de propriété** Celles-ci classifient les objets du modèle en fonction d'une propriété sélectionnée

**Bibliothèques de classification intégrées** Celles-ci classifient les objets en fonction d'une Bibliothèque de classification externe qui est déjà spécifiée dans l'ifc.

### 2.5 **Navigation**

Après avoir configuré les Bibliothèques sélectionnées, cliquez sur « Suivant : Ajouter un nom et un commentaire » pour procéder à l'étape suivante.

## 3. **Étape 3 - Ajouter un nom et un commentaire**

À la troisième étape, l'export peut recevoir un nom et un commentaire peut être ajouté. Voici à quoi peut ressembler l'étape d'ajout d'un nom et d'un commentaire :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/05-step-3-add-name-and-comment.png)

**Nom** Le nom sera pré-rempli avec Export de modèle et la date et l'heure de l'export. Ce nom sera également le nom de fichier du zip téléchargé.

**Commentaire** Les commentaires d'export sont facultatifs et n'apparaissent que sur Catenda. Le commentaire peut donner aux participants du projet des informations sur ce que cet export concerne.

## 4. **Étape 4 - Options de partage**

À la quatrième et dernière étape, l'option de partage peut être choisie. Voici à quoi peut ressembler l'étape des options de partage :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/06-step-4-sharing-options.png)

### 4.1 **Export partagé**

Les exports partagés sont visibles pour tous les participants du projet

### 4.2 **Export privé**

Les exports privés ne sont visibles que pour le créateur de l'export.

### 4.3 **Navigation**

Cliquez sur export pour démarrer le traitement de cet export. Après la finalisation de l'export, la page d'export de modèle s'affiche où la progression du traitement de l'export peut être visible. Le traitement de l'export se fait complètement en arrière-plan et il est sûr de fermer complètement le navigateur à ce stade. Lorsqu'un export a terminé le traitement, une Notification est envoyée au créateur de l'export indiquant que son export est prêt à être téléchargé.
