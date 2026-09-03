# Application Webpart Catenda SharePoint

Avec le webpart Catenda, vous pouvez parcourir la section Documents d'un projet Catenda au sein d'une page SharePoint. _Accès Catenda requis :_ Lecture pour parcourir la structure des Documents et écriture pour télécharger des fichiers SharePoint vers Catenda.

## 1. **Ajout du webpart**

Modifiez une page existante ou créez une nouvelle page dans SharePoint et modifiez-la. Survolez votre page en mode édition jusqu'à ce que vous voyiez une ligne avec un plus `----+-----` Si l'[application Catenda SharePoint](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application) est ajoutée à votre site, vous pourrez trouver le webpart Catenda Document dans votre liste de webparts.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/01-adding-the-webpart.png)

Vous pourrez ensuite ajouter un webpart Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/02-adding-the-webpart.png)

Si vous n'avez pas encore autorisé votre compte Catenda, le webpart ressemblera à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/03-adding-the-webpart.png)

Si vous ouvrez une page avec le webpart Catenda activé et que vous n'avez pas encore autorisé votre compte, vous serez invité à le faire. En savoir plus sur la façon d'autoriser votre compte [ici](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application#h_788fe15988).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/04-adding-the-webpart.png)

Après avoir autorisé vos identifiants de compte, cliquez sur Ouvrir les paramètres du webpart ou cliquez sur l'icône de crayon pour sélectionner le projet Catenda dont les visiteurs de la page SharePoint pourront voir la section Documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/05-adding-the-webpart.png)

Voici à quoi peut ressembler un webpart configuré lorsqu'il est ajouté :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/06-adding-the-webpart.png)

## 2. **Navigation**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/07-navigation.png)

### 2.1 **Affichage**

Le chemin vers le haut du webpart affiche le projet qui a été configuré pour ce webpart et votre emplacement actuel dans la structure des dossiers.

### 2.2 **Navigation**

Cliquez sur l'un des éléments pour revenir à cette partie de la structure des dossiers. Cliquez sur le nom d'un dossier pour ouvrir ce dossier. Cliquez sur le nom d'un Document pour l'ouvrir directement dans Catenda.

## 3. **Tableau des Documents**

le tableau des documents peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/08-document-table.png)

Si vous avez sélectionné des éléments, vous verrez le nombre d'éléments sélectionnés vers le haut du tableau des Documents.

### 3.1 **Sélection de Documents et de dossiers**

Cliquer n'importe où en dehors du nom de l'élément dans une ligne sélectionnera cette ligne. Maintenez Maj enfoncée pour sélectionner tous les éléments entre le dernier élément sélectionné et l'élément sur lequel vous cliquez. Maintenez Ctrl enfoncée pour ajouter/supprimer des éléments de votre sélection.

### 3.2 **Paramètres d'accès Catenda**

Chaque utilisateur a son propre accès dans Catenda, donc certains de vos Membres du projet pourraient voir différents dossiers et Documents que d'autres.

## 4. **Actions dans le webpart**

En haut à gauche du webpart, vous pourrez trouver les actions suivantes :

### 4.1 **Créer un dossier**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/09-create-folder.png)

Crée un dossier dans la partie de la structure des Documents dans laquelle vous vous trouvez. _Accès Catenda requis :_ Accès en écriture

### 4.2 **Télécharger un fichier**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/10-upload-file.png)

Après avoir cliqué, un navigateur de fichiers s'ouvrira et vous pourrez sélectionner le ou les Document(s) que vous souhaitez télécharger. Après avoir téléchargé le Document, vous le verrez à la fois dans Catenda et dans le webpart. Vous ne verrez pas le fichier téléchargé dans la zone de Documents de SharePoint de cette façon. Seulement dans Catenda. _Accès Catenda requis :_ Accès en écriture Vous pouvez glisser-déposer des fichiers de votre système vers une destination dans le webpart afin de télécharger ces fichiers vers Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/11-upload-file.png)

> **Remarque :** Si vous glissez-déposez un dossier, il sera publié en tant que fichier zip. Si vous souhaitez télécharger une structure de dossiers, vous devrez la télécharger depuis SharePoint et la télécharger vers Catenda soit via l'[upload zip](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) soit via le [connecteur de bureau](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector).

### 4.3 **Recharger**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/12-reload.png)

Si quelqu'un d'autre a apporté des modifications au projet Catenda, il se peut que vous ne les voyiez pas encore. Dans ce cas, il est judicieux de recharger le webpart pour obtenir les informations les plus à jour.

### 4.4 Publier sur SharePoint

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/13-publish-to-sharepoint.png)

Publiez vos Documents sélectionnés de Catenda vers SharePoint. Cliquer sur ce bouton ouvrira la boîte de dialogue de publication sur SharePoint :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/14-publish-to-sharepoint.png)

Vers le haut de la boîte de dialogue, vous verrez combien d'éléments vous publiez.

**Nouvel emplacement** Choisissez « Nouvel emplacement » si vous souhaitez publier les fichiers sélectionnés à un nouvel emplacement dans SharePoint.

**Afficher les cibles existantes** Si les fichiers ont déjà été publiés avant et que vous souhaitez mettre à jour les fichiers précédemment publiés, vous devez choisir « Afficher les cibles existantes ».

**Publier** Après avoir configuré l'emplacement où vous souhaitez publier, cliquez sur Publier.

## 5. **Accès Catenda**

### 5.1 **Pas d'accès au projet Catenda**

Si vous n'avez pas accès au projet configuré, vous verrez l'erreur suivante.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/15-no-access-to-the-catenda-project.png)

La partie floue est le GUID du projet. S'il n'y en a pas, ou si vous n'avez accès à aucun Document du projet, il affichera « Aucun contenu - le dossier est vide ».

### 5.2 **Pas d'accès à la création de dossiers**

Si vous n'avez pas accès en écriture au dossier dans lequel vous vous trouvez et que vous essayez de créer un nouveau sous-dossier, vous verrez ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/16-no-access-to-creating-folders.png)

### 5.3 **Pas d'accès au téléchargement de fichiers**

Si vous n'avez pas accès en écriture au dossier ou Document et que vous essayez de télécharger un fichier, vous verrez ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/17-no-access-to-uploading-files.png)
