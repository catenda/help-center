# Interactions de la Visionneuse 2D

> Interaction avec la Visionneuse 2D

Différents composants de la [Visionneuse 2D](https://support.catenda.com/en/articles/4854537-2d-viewer) peuvent être utilisés de différentes manières. Chaque partie de la Visionneuse 2D sur laquelle vous pouvez cliquer est décrite dans cet article. Voici à quoi peut ressembler la Visionneuse 2D :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/01-intro.png)

Cet article contient des informations sur les sujets suivants : _[Bouton 2D](#h_ddfb1f5837) - [Barre supérieure](#h_7996dde66c) - [Canevas](#h_d564366bf9) -_ [Navigation](#h_b384896c43) - [Sélection](#h_8916df6427) - [Paramètres](#h_f9d34c17aa) - [Barre inférieure](#h_15dafd8ad4)

## 1. **Bouton 2D**

Si la Visionneuse 2D n'est pas ouverte, cliquez sur le bouton 2D en bas à droite de la Visionneuse 3D pour ouvrir la Visionneuse 2D.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/02-2d-button.png)

## 2. **Barre supérieure**

### 2.1 **Redimensionnement**

Faites glisser ces deux lignes diagonales pour redimensionner la Visionneuse 2D sur n'importe quelle partie de la Visionneuse 3D. Vous saurez que vous pouvez faire glisser ce coin lorsque votre curseur change.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/03-resizing.png)

### 2.2 **Titre**

Le titre de la barre supérieure sera le nom de l'étage. Si un étage d'un bâtiment du [configurateur d'étage](https://support.catenda.com/en/articles/6921756-storey-configurator-page) est sélectionné, le titre inclura le nom du bâtiment et le nom de l'étage actuel. Si l'étage d'un modèle non configuré est sélectionné, le titre inclura le nom du modèle.

### 2.3 **Ouverture et fermeture de la Visionneuse 2D**

**Fermeture** Cliquez sur la croix en haut à droite de la Visionneuse 2D pour fermer la Visionneuse 2D.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/04-opening-and-closing-the-2d-viewer.png)

## 3. **Canevas**

Le canevas de la Visionneuse 2D est la partie de la Visionneuse 2D où sont affichées les lignes connectées aux étages des différents modèles pour lesquels les vues 2D sont activées.

### 3.1 **Clic souris**

_Clic gauche_ S'il y a des espaces dans l'étage de la vue 2D qui est activée pour un modèle, ils peuvent être sélectionnés en cliquant dessus. Il est possible de savoir s'il y a des espaces dans la vue 2D par le nom de l'espace visible au centre de l'espace.

**Défilement** Zoomez avant et arrière de la Visionneuse 2D.

**Clic droit** Ouvrir le menu contextuel

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/05-click-mouse-button.png)

- _Ajouter un marqueur_
  Ajouter un nouveau marqueur. Avec un sujet ouvert dans le panneau de contenu, vous pouvez assigner le marqueur sélectionné. Ce marqueur ne sera pas enregistré et visible pour les autres tant qu'il n'aura pas été ajouté à un problème.
- _Créer un nouveau sujet avec marqueur_
  Créer un nouveau sujet avec marqueur. Ce marqueur ne sera pas enregistré et visible pour les autres jusqu'à ce que le sujet soit envoyé.
- _Créer une requête_
  - Intersecter espace - Créer une [requête](https://support.catenda.com/en/articles/4854514-queries) de tous les objets intersectant avec l'espace sélectionné
  - Intersecter étage - Créer une [requête](https://support.catenda.com/en/articles/4854514-queries) de tous les objets intersectant avec cet étage

### 3.2 **Maintenir le bouton souris**

**Maintenir le clic gauche ou droit** Faire défiler la Visionneuse 2D

### 3.3 **Indicateur de point de vue**

**Maintenir le clic gauche sur l'indicateur de point de vue** Déplacer la caméra en 3D. L'angle de la caméra restera le même.

**Maintenir le clic droit sur l'indicateur de point de vue** Déplacer la caméra en 3D. L'angle de la caméra suivra.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/06-viewpoint-indicator.png)

## 4. **Outils de navigation**

### 4.1 **Zoom sur l'ensemble**

Effectuer un zoom arrière pour afficher tous les objets visibles à la fois

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/07-zoom-to-extents.png)

### 4.2 **Rotation**

Avec le bouton de rotation, vous pouvez faire pivoter la Visionneuse 2D.

**Curseur de rotation** La rotation initiale peut être configurée en définissant un emplacement avec une rotation dans [les paramètres du projet](https://support.catenda.com/en/articles/4670273-project-settings-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/08-rotation.png)

**Ajustement du curseur** Sélectionnez le curseur en cliquant dessus et utilisez les touches fléchées gauche et droite pour effectuer des ajustements de 0,1 degré. Cela peut être utile pour effectuer des sélections, des sections et des requêtes. La rotation est plus facile si vous sélectionnez d'abord un espace car il s'alignera sur les bords de l'espace lors de la rotation. Vous pouvez également écrire le degré de rotation dans le menu sous le curseur.

**Nord vrai** Si aucune rotation initiale n'est configurée dans les paramètres du projet, le Nord vrai sera le même que le bouton de réinitialisation. Si une rotation initiale a été configurée dans les paramètres du projet, le Nord vrai peut être à un angle par rapport à la rotation initiale

**Réinitialiser** Cliquez sur Réinitialiser en haut à droite pour réinitialiser le curseur à la rotation initiale.

**Rotation du dessin superposé** Les bâtiments peuvent être configurés dans le [configurateur d'étage](https://support.catenda.com/en/articles/6921756-storey-configurator-page). Chaque étage d'un bâtiment peut avoir un dessin comme superposition qui est pivoté par rapport aux modèles du projet.

### 4.3 **Verrouiller la caméra**

Si un modèle est chargé dans la Visionneuse 3D, vous pourrez verrouiller la caméra sur la caméra de la Visionneuse 3D.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/09-lock-camera.png)

Lorsque cette fonction est activée, l'indicateur de point de vue reste centré sur le canevas même si la caméra est déplacée dans la Visionneuse 3D. Cela est utile en combinaison avec le [mode de marche](https://support.catenda.com/en/articles/5784718-3d-viewer-settings#h_1c05dca226).

## 5. **Outils de sélection et paramètres**

Les outils de sélection et les paramètres se trouvent vers le haut à droite du canevas de la Visionneuse 2D.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/10-selection-tools-and-settings.png)

Cliquez [ici](https://support.catenda.com/en/articles/8035360-selecting-and-clipping-from-2d) pour une explication détaillée de comment utiliser les outils de section dans la Visionneuse 2D.

### 5.1 **Sélectionner**

Sélectionnez des espaces et zoomez avant et arrière.

### 5.2 **Section : Sélectionner des objets**

Faites glisser un rectangle sur le canevas 2D pour créer un volume de sélection d'objets en 2D/3D.

### 5.3 **Section : Créer des plans de découpe**

Créer de 4 à 6 plans de découpe en faisant glisser un rectangle sur le canevas 2D et en sélectionnant la hauteur.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/11-section-create-clipping-planes.png)

### 5.4 **Section : Créer une requête**

Créer une [requête](https://support.catenda.com/en/articles/4854514-queries) en faisant glisser un rectangle sur le canevas 2D et en sélectionnant la hauteur.

### 5.5 **Bouton Déplacer**

La fonction de sélection rectangulaire des outils de section entrave le mouvement du curseur. En bas à droite de la Visionneuse 2D, vous pourrez donc utiliser le bouton Déplacer. Avec ce bouton, vous pouvez facilement repositionner votre canevas pour la section.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/12-br-move-button.png)

## 6. **Paramètres de la Visionneuse 2D**

Les paramètres de la Visionneuse 2D se trouvent dans le bouton déroulant avec l'icône d'engrenage.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/13-2d-viewer-settings.png)

**Mode de coloration des marqueurs** Changez la couleur des marqueurs dans la vue 2D pour avoir la couleur de l'une des suivantes :

- Statut
- Type
- Échéance

**Format du nom d'espace** Affiche le nom long des salles et des espaces

**Translucide** Rendre la Visionneuse 2D transparente

## 7. **Barre inférieure**

### 7.1 **Vue du modèle**

Cliquez ici pour en savoir plus sur le menu des étages. Le menu des étages peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/14-model-view.png)

### 7.2 **Menu des calques**

Avec le bouton de calque, vous pourrez basculer différents calques dans la Visionneuse 2D.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/15-layer-menu.png)

**Marqueurs** Avec ce bouton, les marqueurs peuvent être activés ou désactivés.

**Modèles** Avec ce bouton, les modèles peuvent être activés ou désactivés.

**Dessins** Vous verrez ce bouton si un dessin a été aligné comme superposition pour un étage de bâtiment dans le [configurateur d'étage](https://support.catenda.com/en/articles/6921756-storey-configurator-page). Avec ce bouton, les dessins alignés peuvent être activés ou désactivés.

**Carte** Vous verrez ce bouton si un emplacement a été configuré dans les [paramètres du projet](https://support.catenda.com/en/articles/4670273-project-settings-page) Avec ce bouton, la carte peut être activée ou désactivée.
