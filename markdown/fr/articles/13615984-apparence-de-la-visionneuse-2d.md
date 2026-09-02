# Apparence de la visionneuse 2D

Il existe plusieurs façons de configurer le contenu de la visionneuse 2D selon vos besoins.

## 1. **Objets de la visionneuse**

### 1.1 **Mise en évidence des objets sélectionnés**

Les lignes générées pour chaque étage lors du traitement du modèle restent liées à l'objet 3D qui a été traversé lors de la génération des lignes.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/01-highlighting-selected-objects.png)

Lorsqu'un objet est sélectionné dans la visionneuse 3D, si un étage de ce modèle est activé dans la visionneuse 2D qui a été générée à la hauteur où cet objet existe, l'objet sera également mis en évidence dans la visionneuse 2D. Les tranches d'objets sont générées à un mètre au-dessus de la hauteur définie pour chacun des étages du fichier IFC. Les décalages d'élévation tels que l'élévation en IFCSite ne sont pas pris en compte.

Dans l'exemple ci-dessous, l'étage "Rez-de-chaussée" est à 0 mètre. Les murs avec une hauteur de base de 0 et différentes hauteurs supérieures sont affichés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/02-highlighting-selected-objects.png)

Comme on peut le voir, seuls les murs d'une hauteur de 1 mètre et plus sont affichés dans la visionneuse 2D.

### 1.2 **Ouvertures de portes**

Les ouvertures de portes sont spécifiées dans le fichier IFC. Vous pouvez voir comment cela fonctionne dans les articles BuildingSMART suivants : [IFC 2x3](https://standards.buildingsmart.org/IFC/RELEASE/IFC2x/FINAL/HTML/ifcsharedbldgelements/lexical/ifcdoorstyle.html) [IFC 4](https://standards.buildingsmart.org/IFC/RELEASE/IFC4_1/FINAL/HTML/schema/ifcsharedbldgelements/lexical/ifcdoortypeoperationenum.htm) Si aucune ouverture de porte n'est spécifiée, la porte s'ouvrira vers la droite.

## 2. **Dessin en arrière-plan**

Il est possible de placer un PDF de la section documents en arrière-plan avec le [configurateur d'étages](https://support.catenda.com/en/articles/6921756-storey-configurator-page). Cela est particulièrement utile s'il y a des objets au-dessus ou au-dessous de la hauteur où les objets 3D sont traversés et qui n'apparaissent pas dans la visionneuse 2D. Voici des exemples : Conduits et tuyaux, Points de sortie électriques, Plans de plafond, Routes et voies ferrées

## 3. **Marqueurs dans la visionneuse 2D**

Avec [marqueurs activés](https://support.catenda.com/en/articles/4854537-2d-viewer#h_381a9d4098), les rubriques avec localisation sont affichées sous forme de cercles colorés à une coordonnée x-y. Voici à quoi peut ressembler une vue 2D avec différents marqueurs dans le navigateur :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/03-markers-in-the-2d-viewer.png)

Cliquez [ici](https://support.catenda.com/en/articles/4854523-2d-location-of-issues) pour en savoir plus sur la localisation 2D des rubriques.

### 3.1 **Rubriques avec marqueurs existants**

**Interactions avec les marqueurs -** Survolez un marqueur pour voir le numéro et le titre de la rubrique d'où provient le marqueur. Cliquez sur le marqueur pour ouvrir la rubrique dans son tableau de rubriques dans le panneau de contenu. Un marqueur appartenant à une rubrique ouverte est mis en évidence en vert.

**Affichage des marqueurs -** Filtrez et recherchez dans un tableau de rubriques. Les rubriques du résultat filtré qui ont des marqueurs sur la visionneuse 2D préparée sont affichées.

### 3.2 **Rubriques avec nouveaux marqueurs**

Avant de travailler avec des marqueurs, assurez-vous que la visionneuse 2D est configurée.

- **Étages des vues du modèle 2D -** Choisissez un étage d'une vue 2D activée comme hauteur de base. Activez d'autres vues 2D pour afficher à côté de cet étage.
- **Étages des** **bâtiments -** Choisissez un étage d'un bâtiment préconfiguré.
  La hauteur de base et les vues 2D activées des modèles configurés sont activées.

**Placement des marqueurs -** Cliquez avec le bouton droit sur le canevas et créez une nouvelle rubrique avec marqueur. Cliquez sur ajouter une localisation dans l'en-tête de la rubrique du panneau de contenu et cliquez sur l'endroit où le marqueur doit être ajouté.

## 4. **Étiquettes de pièces dans la visionneuse 2D**

Les étiquettes de pièces affichées au centre des pièces dans la visionneuse 2D sont déterminées à l'aide des données disponibles dans les objets de pièce IFC. Ces objets de pièce incluent à la fois des noms courts et longs, qui peuvent être configurés pour définir le format d'étiquette via le paramètre **Format du nom de pièce** dans Catenda. Assurez-vous que les numéros de pièces et les surfaces sont correctement inclus dans les données IFC, car les attributs manquants peuvent restreindre l'affichage des étiquettes de pièces souhaitées.

### 4.1 Dépannage des étiquettes de pièces :

- Vérifiez que le fichier de données IFC inclut les attributs nécessaires tels que les numéros de pièces et les surfaces.
- Vérifiez et ajustez les paramètres "Format du nom de pièce" pour correspondre aux configurations d'étiquettes souhaitées. Vous pouvez trouver le paramètre dans la visionneuse 2D « roue de paramètres » dans le coin droit.
