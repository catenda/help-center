# Nuages de points dans Catenda Hub

> Découvrez comment bénéficier des analyses laser et des technologies LIDAR dans Catenda Hub.

> **Remarque :** Téléchargez un exemple de fichier [ici](https://drive.google.com/file/d/1G8U916oihDl5qHrTfQaVHxDeLsbq1ulG/view?usp=sharing).

Les ensembles de données de nuage de points (PC) peuvent être visualisés dans Catenda Hub. Les PC individuels peuvent être prévisualisés dans la zone de documents. Plusieurs PC peuvent être chargés dans la [Visionneuse 3D](https://support.catenda.com/en/articles/8227211-3d-viewer). Dans la Visionneuse 3D, les PC peuvent être visualisés ensemble avec d'autres formats de documents 3D comme les modèles IFC et les fichiers GML.

Consultez ci-dessous les différents paramètres pour afficher vos données :

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="padding: 8px;"><p>Adaptatif - Épars - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-05a450dc777f.png" style="height: auto;" width="3839"/></div></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>Adaptatif - Dense - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-196a1135014a.png" style="height: auto;" width="3839"/></div></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Fixe - Dense - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-66e21551bbef.png" style="height: auto;" width="3834"/></div></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Fixe - Épars - Intensité</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-4a2046c8eaf1.png" style="height: auto;" width="3839"/></div></td></tr></tbody></table></div>

## 1. **Aperçu de la section des documents**

Les données PC des deux formats de fichier suivants peuvent être prévisualisées sur Catenda.

- `*.e57`
- `*.las`

Les PC peuvent être téléchargés comme tout autre document dans la section des documents. Pour ces deux formats de fichier, les fichiers jusqu'à 25 Go peuvent être téléchargés vers la section des documents. Plusieurs fichiers peuvent être chargés dans la section des documents et affichés ensemble dans la Visionneuse 3D.

### 1.1 **Téléchargement de données PC**

Il est recommandé d'utiliser le [Connecteur Catenda Desktop](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) ou de compresser votre fichier PC dans un dossier zippé et d'utiliser l'[importation zip](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) pour télécharger votre PC. Ces méthodes vous aideront à gagner du temps car la taille du fichier à télécharger sera plus petite et cela minimisera le risque d'erreur réseau puisque le fichier sera téléchargé plus rapidement

Après avoir téléchargé un PC vers la section des documents, l'aperçu du document commencera à être traité. Pendant que l'aperçu est en cours de traitement, vous verrez une barre grise en haut de votre aperçu du document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/01-uploading-pc-data.png)

La durée du traitement de l'aperçu dépend de la taille du PC. Le traitement prend 1 heure par Go, mais cela peut être plus ou moins selon le nuage de points.

Une fois le traitement de l'aperçu terminé, cliquez sur le document pour visualiser votre PC dans l'aperçu du document :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/02-uploading-pc-data.png)

### 1.2 **Révisions PC partagées**

Si la [publication de révisions](https://support.catenda.com/en/articles/9874698-revision-publishing-iso-19650) a été activée pour le projet, le nuage de points aura été téléchargé en tant que révision partagée. Les révisions PC partagées ne peuvent être prévisualisées que dans la section des documents. Pour pouvoir charger votre PC dans la Visionneuse 3D, la révision doit être publiée. Les révisions partagées individuelles peuvent être publiées avec l'action de publication dans le menu de droite de l'aperçu du document. Plusieurs révisions partagées peuvent être publiées avec l'action des éléments sélectionnés dans la structure du document. Lorsque vous publiez une révision, l'aperçu de la révision publiée commencera à être traité.

### 1.3 **Révisions PC publiées**

Une fois que l'aperçu d'une révision PC publiée a été traité, un bouton 3D apparaîtra dans la colonne de la Visionneuse du tableau des documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/03-br-published-pc-revisions.png)

Le bouton 3D chargera la dernière révision publiée du document dans la Visionneuse 3D.

Si vous avez sélectionné un ou plusieurs documents contenant des documents 3D comme PC, IFC ou GML, vous verrez également l'action des documents 3D dans le menu d'action des éléments sélectionnés du tableau des documents. De cette façon, vous pouvez charger les dernières révisions de plusieurs documents 3D dans la Visionneuse 3D à la fois.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/04-br-published-pc-revisions.png)

Dans un document contenant au moins une révision PC publiée dont le traitement est terminé, vous pourrez voir l'action 3D dans le menu d'action en haut à droite.

> **Remarque :** L'action 3D chargera la dernière révision publiée du document dans la Visionneuse 3D. Même si vous consultez une révision antérieure.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/05-br-published-pc-revisions.png)

## 2. **Aperçu de la Visionneuse 3D**

Après avoir cliqué sur le bouton 3D, les points PC commenceront à se charger dans la Visionneuse 3D. L'affichage 3D d'un PC peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/06-3d-viewer-preview.png)

En haut de la Visionneuse 3D, vous pouvez voir une barre de chargement verte. Cette barre de chargement indique le nombre de points chargés dans la Visionneuse 3D pour la position et l'angle de caméra actuels. La barre de chargement peut changer si vous vous déplacez car certains points peuvent disparaître de la vue et être déchargés, ou d'autres points peuvent entrer dans la plage et commencer à se charger.

Et après quelques ajustements avec le zoom et le positionnement, l'aperçu du PC peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/07-3d-viewer-preview.png)

## 3. **Paramètres de la Visionneuse 3D**

Dans cette section, nous examinerons les paramètres de Catenda Hub qui vous permettront d'obtenir la meilleure expérience avec votre PC.

> **Remarque :** Avant de configurer la Visionneuse 3D, assurez-vous que l'application Catenda sur laquelle vous travaillez est configurée [comme recommandé](https://support.catenda.com/en/articles/6921941-hardware-recommendation).

Les paramètres qui peuvent être utilisés pour configurer les nuages de points sont situés dans deux endroits.

### 3.1 **1. Budget des points :**

Le budget des points peut être configuré dans les [paramètres de la Visionneuse 3D](https://support.catenda.com/en/articles/5784718-3d-viewer-settings) qui se trouvent dans l'icône d'engrenage en haut à droite de la Visionneuse 3D.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/08-1-point-budget.png)

Dans le menu des paramètres de la Visionneuse 3D, le budget des points peut être ajusté de 100 000 à 10 000 000. Le chargement de plus de points peut prendre plus de temps et exiger plus de ressources de votre système. En chargeant plus de points, le nuage de points peut être affiché avec une fidélité plus élevée. Consultez la même vue avec : 100 000 points

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/09-1-point-budget.png)

1 000 000 de points

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/10-1-point-budget.png)

10 000 000 de points

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/11-1-point-budget.png)

### 3.2 **2. Sélecteur de révision et paramètres PC individuels :**

En haut à gauche de la Visionneuse 3D, vous trouverez le [sélecteur de révision](https://support.catenda.com/en/articles/4670246-accepting-an-invitation-to-join-a-project).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/12-2-revision-selector-and-individual-pc-settings.png)

Dans [le menu des modèles](https://support.catenda.com/en/articles/4670279-revision-selector#h_180a64490d), vous pourrez trouver les [documents 3D](https://support.catenda.com/en/articles/4670279-revision-selector#h_fce60074ef) individuels que vous avez chargés dans la Visionneuse 3D.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/13-2-revision-selector-and-individual-pc-settings.png)

Les nuages de points peuvent être configurés dans le sélecteur de révision en cliquant sur l'icône d'engrenage.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/14-2-revision-selector-and-individual-pc-settings.png)

Voici à quoi peut ressembler le menu des paramètres :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/15-2-revision-selector-and-individual-pc-settings.png)

_Attribut_ _RGBA_ - Par défaut Afficher les points PC avec leurs couleurs

_Attribut Intensité_ L'option d'intensité peut être utilisée lorsque les points n'incluent pas les couleurs. Par exemple, lorsque le nuage de points a été capturé dans un tunnel ou une pièce sombre.

**Opacité** Lorsque les modèles sont affichés avec des nuages de points, il peut être nécessaire de réduire l'intensité des points pour mieux comprendre le point de vue.

_Taille du point_ _Adaptatif_ - Par défaut Plus un point est proche de la caméra, plus il est grand. Les points qui sont en vue sont chargés en mémoire. Les points qui sortent de la vue sont déchargés de la mémoire.

> **Remarque :** Assurez-vous que le matériel et le logiciel sur lesquels Catenda est ouvert sont configurés [comme recommandé](https://support.catenda.com/en/articles/6921941-hardware-recommendation) car cela peut affecter le type de chargement de taille de point que votre appareil peut gérer.

**Taille du point Taille fixe** Les points qui ont été chargés resteront en mémoire avec cette option. Avec de nombreux points, vous remarquerez que la rotation peut être retardée et le mouvement peut être ralenti à mesure que vous vous rapprochez de la quantité de points que votre système peut gérer. Vous remarquerez également qu'il faudra de plus en plus de temps pour charger les nouveaux points à mesure que vous vous rapprochez de la limite de votre appareil. Les points se chargent d'abord au plus proche de la caméra. Avant de charger le nuage de points de la section des documents, assurez-vous donc de positionner la caméra où vous souhaitez que les points se chargent. Si cela est une position de caméra que vous envisagez d'utiliser plus souvent avec ce nuage de points, pensez à créer un signet ou une capture dans une rubrique que vous pouvez lancer pour revenir à cette position.

**Curseur de densité des points** Le curseur de densité vous aide à effectuer le réglage final. Il n'y a pas de règle pour la bonne valeur, cela dépendra des données que vous téléchargez (taille de l'ensemble de données, densité des points, type de scan, etc.). Notre conseil : Chargez le nuage de points, et après un court instant, lorsque suffisamment de points sont affichés, ajustez les paramètres si nécessaire.

[Vidéo YouTube](https://www.youtube.com/embed/n9pztkRPxoc?rel=0)
