# Actions dans le plug-in Catenda Revit

> **Remarque :** Le fichier d'installation du plug-in se trouve dans [cet article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Les actions [Plug-in Catenda Revit](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin) se trouvent vers le coin supérieur droit de la fenêtre du plug-in dans l'application Revit.

Voici à quoi le menu d'action peut ressembler :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/01-intro.png)

Des informations sur les sujets suivants se trouvent dans cet article :

## 1. **1. Nouveau sujet**

Cliquez sur le bouton vert Nouveau sujet en haut à droite pour créer un nouveau sujet dans le projet actuellement sélectionné dans le menu déroulant en haut à gauche. Le sujet sera créé dans la liste de sujets sélectionnée dans le deuxième menu déroulant en haut à gauche. _Accès requis :_ Accès en écriture à la liste de sujets

Dès que le sujet est créé, il sera visible dans Catenda Hub via le navigateur ainsi que via n'importe quel plug-in Catenda dans d'autres programmes. Voici à quoi la page du nouveau sujet peut ressembler :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/02-1-new-topic.png)

Les informations minimales requises pour soumettre un sujet sont un titre.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/03-1-new-topic.png)

### 1.1 **1.1 Soumettre**

Une fois que le sujet est prêt à être partagé avec le projet, cliquez sur Soumettre pour soumettre le sujet à la liste de sujets.

## 2. **2. Télécharger IFC**

Cliquez sur Télécharger IFC dans le menu d'action qui s'ouvre avec les trois points en haut à droite pour télécharger votre modèle Revit actuel directement vers Catenda Hub en tant que fichier IFC. Voici à quoi la page de téléchargement d'IFC peut ressembler :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/04-2-upload-ifc.png)

### 2.1 **2.1 Sélectionner un modèle**

Ce menu déroulant affiche les modèles préexistants du projet sélectionné. Si aucun modèle n'existe dans le projet, créez d'abord un modèle vide dans Catenda via le navigateur. L'IFC téléchargé devient une nouvelle révision du modèle sélectionné. Chaque modèle dans Catenda est lié à un conteneur de documents, donc après le téléchargement, la révision sera visible à la fois dans les zones de modèle et de documents du projet.

### 2.2 **2.2 Nom de fichier**

Tapez un nom de fichier facultatif associé au téléchargement. Seuls les caractères ASCII sont pris en charge dans ce champ.

### 2.3 **2.3 Ajouter un commentaire**

Tapez un commentaire obligatoire associé au téléchargement. Dès qu'un commentaire est ajouté, le bouton Télécharger devient surlignéet cliquable. Seuls les caractères ASCII sont pris en charge dans ce champ.

### 2.4 **2.4 Configuration d'export**

Sélectionnez une configuration IFC. Une nouvelle configuration peut être créée dans le menu d'export IFC de Revit. Vous pouvez également sélectionner le <Configuration Catenda> pour une configuration facile à utiliser et bien adaptée à Catenda Hub.

Voici les paramètres d'export de la Configuration Catenda

```
selectedConfig.Name = "<Catenda Setup>"; selectedConfig.IFCVersion = IFCVersion.IFC2x3CV2; selectedConfig.SpaceBoundaries = 1; selectedConfig.ActivePhaseId = ElementId.InvalidElementId; selectedConfig.ExportBaseQuantities = true; selectedConfig.SplitWallsAndColumns = false; selectedConfig.VisibleElementsOfCurrentView = false; selectedConfig.Use2DRoomBoundaryForVolume = false; selectedConfig.UseFamilyAndTypeNameForReference = true; selectedConfig.ExportInternalRevitPropertySets = true; selectedConfig.ExportIFCCommonPropertySets = true; selectedConfig.Export2DElements = false; selectedConfig.ExportPartsAsBuildingElements = true; selectedConfig.ExportBoundingBox = false; selectedConfig.ExportSolidModelRep = false; selectedConfig.ExportSchedulesAsPsets = false; selectedConfig.ExportUserDefinedPsets = false; selectedConfig.ExportUserDefinedPsetsFileName = ""; selectedConfig.ExportLinkedFiles = false; selectedConfig.IncludeSiteElevation = true; selectedConfig.UseActiveViewGeometry = false; selectedConfig.ExportSpecificSchedules = false; selectedConfig.TessellationLevelOfDetail = 0; selectedConfig.StoreIFCGUID = true; selectedConfig.ExportRoomsInView = true;
```

### 2.5 **2.5 Télécharger**

Cliquez sur Télécharger pour télécharger un IFC. Un commentaire doit être ajouté pour pouvoir télécharger. _Accès requis :_ Accès en écriture au document lié au modèle.

## 3. **3. Paramètres**

La page des paramètres vous permet de modifier la façon dont le plug-in créera une vue 3D lors de l'utilisation de la [fonction Zoom](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin#h_36392f671a).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/05-3-settings.png)

### 3.1 **3.1 Retour aux sujets**

Cliquez sur Retour aux sujets pour revenir à la liste des sujets.

### 3.2 **3.2 Navigation**

**Conserver la vue 3D en orthographique** Cette option forcera la vue 3D de Revit à être orthographique même si le point de vue correspondant a été créé avec une vue en perspective.

**Créer une nouvelle vue pour chaque sujet** Au lieu de réutiliser la même vue 3D chaque fois que vous utilisez la fonction Zoom, cette option créera une nouvelle vue 3D pour chaque sujet chaque fois que vous utilisez la fonction Zoom.

**Suffixe du nom de la vue 3D** Ce texte sera ajouté au nom de la vue 3D créée lors de l'utilisation de la fonction Zoom.

### 3.3 **3.4 Transformation du point de vue**

Avec la transformation du point de vue, le point de vue dans Revit peut être configuré pour être décalé d'une certaine quantité. Si des valeurs ont été configurées ici, le point de vue sera décalé de cette quantité chaque fois qu'un point de vue d'un sujet est lu. Cela peut être utile lorsque les coordonnées du point de vue du sujet ne correspondent pas aux coordonnées configurées dans le projet Revit.

**3.4.1 X (E/O)** Transformation dans la direction X. Est ou Ouest selon les valeurs positives ou négatives. Unités en mètres

**3.4.2 Y (N/S)** Transformation dans la direction Y. Nord ou Sud selon les valeurs positives ou négatives. Unités en mètres

**3.4.3 Z (Élev)** Transformation dans la direction Z. Élévation selon les valeurs positives ou négatives. Unités en mètres

**3.4.4 Angle** Transformation rotationnelle. Élévation selon les valeurs positives ou négatives. Unités en degrés. La caméra restera à la même hauteur et pivotera autour d'un point du modèle.

## 4. **4. Compte**

Ouvrez votre page de compte Catenda Hub dans votre navigateur par défaut. Cliquez [ici](https://support.catenda.com/en/articles/6880968-account-page) pour en savoir plus sur la page de compte.

## 5. **5. Quitter**

Cliquez sur Quitter pour vous déconnecter de Catenda Hub dans le plug-in.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/06-5-sign-out.png)

Après la déconnexion, la page de connexion s'affiche où vous pouvez vous connecter avec le même compte ou un compte différent en utilisant votre nom d'utilisateur et votre mot de passe. Cliquez [ici](https://support.catenda.com/en/articles/7891486-sign-in-page) pour en savoir plus sur la page de connexion.

Après la reconnexion, le premier projet de la liste des projets s'affiche. Sélectionnez à nouveau un projet dans la liste des projets pour accéder à un projet différent.
