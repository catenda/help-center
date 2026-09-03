# Menu droit sur la page des modèles

Le menu d'information droit peut être trouvé en sélectionnant un model sur la [page des modèles](https://support.catenda.com/en/articles/4670286-models-page) ou en accédant à la [page de contenu](https://support.catenda.com/en/articles/4670270-model-overview-page) d'un model.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/01-intro.png)

Cliquez sur l'icône "i" en haut à droite pour ouvrir le menu droit.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/02-intro.png)

Le menu peut ressembler à ceci pour un seul model :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/03-intro.png)

Ou comme ceci avec plusieurs lignes de model sélectionnées.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/04-intro.png)

## 1. **En-tête du model**

Dans l'en-tête du model, les informations sur la dernière révision du model sont affichées.

### 1.1 **Image**

En haut de l'en-tête du model, une image peut être ajoutée pour le model. Voici à quoi cela peut ressembler lorsqu'aucune image n'est ajoutée.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/05-image.png)

Téléchargez une image locale ou ajoutez une Capture directement à partir de la Visionneuse 3D sans télécharger quoi que ce soit. Voici à quoi ressemble la page des modèles lorsqu'une image est configurée pour un model :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/06-image.png)

_Image du model dans le menu droit_ Lorsqu'elle est ajoutée, l'image est affichée en haut du menu droit d'un model lorsqu'un seul model est sélectionné ou lorsque le menu est ouvert sur la page de contenu du model. L'image ajoutée est affichée à la fois dans le menu droit d'une révision du model lorsqu'un model est sélectionné et dans la miniature du model dans la colonne du nom du tableau des modèles.

Cliquez [ici](https://support.catenda.com/en/articles/4670257-creating-a-thumbnail-for-your-model) pour en savoir plus sur la façon d'ajouter une image pour un model.

**Miniature du model** Lorsqu'elle est ajoutée, l'image est affichée sous forme de miniature pour le model dans la colonne du nom du tableau des modèles sur la page des modèles.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/07-image.png)

Cliquez sur la miniature pour ouvrir un aperçu de l'image. Voici à quoi peut ressembler l'aperçu de la miniature.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/08-image.png)

À partir de la navigation en haut, l'image peut être téléchargée. Si la Capture a été prise à partir d'un model, l'aperçu est un aperçu 3D permettant de naviguer autour du model à partir du point de départ de la miniature du model.

### 1.2 **Lien vers un document**

Le lien vers le document est la boîte grise sous l'image du model. La boîte affichera l'emplacement du document-model dans la structure des fichiers. Sous celle-ci, vous verrez le nom du document-model lié à ce model-document. Cliquez sur cette boîte pour accéder à la page d'aperçu du document du document-model sur la page des Documents.

### 1.3 **Statut**

Le Statut de la dernière révision du document-model publique.

### 1.4 **Étiquettes**

Par défaut, les Étiquettes peuvent être appliquées à n'importe quel model. Si les révisions partagées sont activées, il doit y avoir au moins une révision publiée dans le model pour pouvoir ajouter des Étiquettes. Les Étiquettes sont enregistrées à la fois pour le model et pour le Document auquel le model est lié. La même Étiquette peut donc être utilisée pour filtrer les modèles sur la page des modèles et les Documents sur la page des Documents.

## 2. **Contributeurs**

Les différents Membres qui ont téléchargé des révisions et qui ont ainsi contribué au model sont affichés ici.

## 3. **Transformation du model**

Avec la transformation du model, les objets du model peuvent être configurés pour être affichés à un emplacement et une orientation différents dans la Visionneuse 3D de Catenda Hub. Cette transformation s'applique uniquement aux modèles dans la Visionneuse 3D et non aux Documents 3D qui ont été chargés dans la Visionneuse 3D. Cliquez [ici](https://support.catenda.com/en/articles/12498975-add-context-to-your-projects-with-freely-accessible-ign-point-clouds-hd-lidar) pour en savoir plus sur la transformation des Documents 3D.

**Échange de modèles avec des outils externes** Les modèles sont souvent téléchargés depuis Catenda et ouverts dans un programme tiers. Il reste donc important d'avoir les bonnes coordonnées configurées dans le fichier IFC avant le téléchargement afin que le fichier téléchargé contienne les bonnes informations.

**Quand le model doit-il être transformé ?** Il y a souvent une période où un model est soumis et la géométrie est déjà utilisée pour collaborer même avant que les coordonnées du model ne soient correctes. Cela peut provenir de différentes raisons, par exemple qu'un point zéro commun n'est pas décidé dans le projet ou qu'une méthode d'export différente doit être examinée dans le programme de création où le fichier IFC a été généré. Il peut être utile de transformer le model (uniquement dans Catenda Hub via le navigateur) avec la transformation du model pendant cette période afin que la lecture des Captures 3D continue à correspondre, même avec les révisions plus récentes qui ont mis à jour les coordonnées.

**Collaboration aux coordonnées avec révisions partagées** Dans un projet où les révisions partagées sont activées, il n'est pas recommandé de publier des révisions du model sans avoir les bonnes coordonnées dans le fichier IFC.

### 3.1 **Paramètres de transformation du model**

Chargez le model qui doit être déplacé dans la Visionneuse 3D. Cela peut être fait en cliquant sur le bouton 3D du Tableau de bord, sur la page des modèles, sur la page de contenu du model ou dans le sélecteur de révision. Dans le menu droit sur la page des modèles, le menu des paramètres de transformation sera affiché vers le bas du menu. Voici à quoi peuvent ressembler les paramètres de transformation du model :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/09-model-transformation-settings.png)

**Décalage** Entrez la coordonnée X, Y et/ou Z pour déplacer le model. Unités - Mètre

**Rotation** Entrez une angulation pour faire tourner le model. Le model est pivoté autour des points milieu de sa boîte englobante qui contient tous les objets du model. Le point se trouve souvent autour du milieu du model vu de dessus. Unités - Degrés

**Enregistrer** Cliquez sur enregistrer pour enregistrer les paramètres de transformation.

### 3.2 **Uniquement dans le navigateur**

Le fichier IFC ne sera pas modifié lors de l'enregistrement des paramètres de transformation. Si un nouveau model est créé avec le fichier IFC soit dans le même projet soit dans un projet différent, le fichier IFC sera à nouveau affiché à l'emplacement configuré dans le fichier IFC.

Il n'est souvent pas problématique de déplacer un model dans Catenda pendant de courtes périodes ou même pendant toute la durée de vie du projet. En fin de compte, cela peut faire gagner beaucoup de temps de décider d'un système de coordonnées commun afin que les modèles n'aient pas besoin d'être ajustés après leur création et pour éviter les malentendus au cours du projet.

## 4. **Sélection multiple**

Avec plusieurs modèles sélectionnés, le menu droit peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/10-multi-select.png)

Cliquez sur le x rouge à côté d'un model pour le supprimer de la sélection.

### 4.1 **Mise à jour des Documents sélectionnés**

Voici à quoi peut ressembler le menu de mise à jour des Documents sélectionnés

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/11-update-selected-documents.png)

Cliquez dans les zones d'ajout et de suppression des Étiquettes et sélectionnez une ou plusieurs Étiquettes.

_L'ajout prend la priorité_ Une Étiquette entrée à la fois dans les champs d'ajout et de suppression d'Étiquettes est ajoutée aux modèles qui n'ont pas encore l'Étiquette et n'est pas supprimée des modèles qui ont déjà l'Étiquette.

### 4.2 **Dernière révision**

Le Statut entré sera configuré pour tous les modèles sélectionnés lors de l'enregistrement des modifications.
