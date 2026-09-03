# Panneau arborescence du modèle

Le panneau arborescence du modèle se trouve dans l'un des quatre [panneaux de projet](https://support.catenda.com/en/articles/13141464-project-panels) qui peuvent être ouverts en haut à droite de l'écran.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/01-intro.png)

## 1. **Ouverture du panneau arborescence du modèle**

Le panneau arborescence du modèle peut être ouvert côte à côte avec l'un des autres panneaux.

_Ouverture du_ panneau arborescence du modèle _:_ Cliquez sur l'icône arborescence ou appuyez sur [maj+3](https://support.catenda.com/en/articles/4670267-summary-of-most-important-shortcuts-and-basic-controls#:~:text=row%20of%20objects-,Shift%20%2B%203,-Control%20%2B%20left%20click)

_Isolation du_ panneau arborescence du modèle _:_ Ouvrez le panneau arborescence Fermez tous les autres panneaux ouverts en cliquant sur ceux-ci.

## 2. **Arborescence du modèle** **Contenu du panneau**

Dans le panneau arborescence, le contenu de l'IFC peut être visualisé dans différentes structures d'arborescence. La structure affichée provient directement du modèle IFC sélectionné en haut. Chacune des arborescences affiche des parties de l'IFC de différentes manières. Les éléments de liste pour les objets visibles dans la visionneuse 3D peuvent être visibles dans une ou plusieurs des arborescences du modèle selon qu'ils conviennent à cette manière de visualiser le contenu IFC. D'autres éléments de liste peuvent inclure un regroupement de ces objets et/ou d'autres entités de l'IFC.

### 2.1 **Nommage des éléments de liste**

Les éléments de liste peuvent être nommés de différentes manières. Les entités nommées peuvent être nommées selon le nom qui leur a été attribué dans l'IFC, mais les entités peuvent également être nommées selon le nom de l'entité elle-même tel que spécifié dans la norme BuildingSMART. Si aucune traduction n'est disponible selon la norme, le nom peut être affiché en anglais, qui est la langue de base. Pour contribuer à la traduction dans la norme ouverte, consultez [ici](https://user.buildingsmart.org/knowledge-base/ifc-translations-manual/). Pour voir si une entité a une traduction, allez à la page BuildingSMART pour cette entité et changez la langue en la langue. Le nom de l'entité sera soit traduit, soit il y aura un message en haut indiquant que cette entité manque de traduction.

**Entités de regroupement** Les entités qui peuvent contenir d'autres entités, comme un bâtiment qui contient des murs, peuvent être nommées selon le nom qui a été donné à cette entité, le cas échéant, ou selon le nom de l'entité selon la norme BuildingSmart.

**Éléments uniques** Les éléments uniques sont les éléments au niveau le plus bas lorsque la vue arborescence est complètement développée et peuvent ressembler à ceci:

`Entité.Ensemble.Numéro`

Nom Ces éléments sont répertoriés par le nom de leur entité selon la norme BuildingSMART.

Ensemble Il y a souvent de nombreux éléments similaires qui sont regroupés ensemble, donc après le nom de l'entité se trouve le numéro de l'énième ensemble de ces types d'entités auquel appartient cette entité.

Numéro Enfin, le numéro de l'énième entité de l'ensemble est listé. Par exemple, la 21ème fenêtre au niveau 2 peut ressembler à ceci:

`Fenêtre.1.21`

### 2.2 **Éléments surlignés**

Comme dans la visionneuse 3D, les objets sélectionnés sont surlignés en vert et les groupes d'objets sélectionnés sont surlignés en jaune. Contrairement à la visionneuse 3D, il est également possible de surligner les entités qui peuvent contenir des objets et de surligner les ensembles d'objets similaires. Si un objet est surligné dans la visionneuse 3D mais qu'aucun objet n'est surligné dans le panneau arborescence du modèle, il se peut que l'objet soit surligné dans un autre menu arborescence du modèle.

**Zoom sur l'élément de liste** Les arborescences peuvent devenir assez longues. Lorsqu'un objet est sélectionné dans la visionneuse 3D, le menu arborescence fait défiler jusqu'à l'emplacement de la liste où l'objet sélectionné existe, à condition que cet objet existe dans le menu arborescence ouvert dans le panneau arborescence du modèle.

### 2.3 **Sélection**

Les éléments de liste de plusieurs modèles chargés dans la visionneuse 3D peuvent être sélectionnés. Cliquez sur la liste déroulante en haut pour basculer entre les différents modèles. Les sélections peuvent être enregistrées dans le menu des sélections.

**Élément actif** L'élément actif est surligné d'un contour pointillé rouge. Utilisez les touches fléchées pour vous déplacer vers le haut et le bas de la liste.

**Sélection unique** Après avoir cliqué sur un élément de liste pour le sélectionner, l'élément sera défini comme l'élément actif et la sélection précédente sera effacée.

Cliquez sur un élément de liste ou appuyez sur Entrée sur l'élément actif pour: Sélectionner un objet. Sélectionner un ensemble d'objets et tous les objets similaires d'un ensemble d'objets. Sélectionner un groupe d'ensembles et tous les sous-éléments de ce groupe.

**Modification de la sélection** Ctrl+Clic sur un élément de liste ou appuyez sur Ctrl+Entrée sur l'élément de liste actif pour: Ajouter les éléments de liste qui n'ont pas été précédemment sélectionnés à la sélection. Supprimer de la sélection les éléments de liste qui sont sélectionnés.

**Sélection d'ensemble** Maj+Clic sur un élément de liste ou appuyez sur Maj+Entrée sur l'élément de liste actif après avoir sélectionné un élément de liste différent pour: Sélectionner tous les éléments de liste entre l'élément précédemment sélectionné et l'élément sélectionné.

**Zoom sur l'élément de liste** Double-cliquez sur un élément de liste pour faire un zoom sur cet élément de liste dans la visionneuse 3D.

## 3. **Arborescence de contenance**

L'arborescence de contenance fournit une perspective hiérarchique sur la façon dont les différents objets IFC se rapportent les uns aux autres.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/02-containment-tree.png)

Lorsque le raccourci "`p`" est enfoncé pour sélectionner le nœud parent, cela peut être observé visuellement dans l'arborescence de contenance.

## 4. **Arborescence des composants**

L'arborescence des composants fournit une perspective hiérarchique sur les composants qui constituent un objet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/03-component-tree.png)

Dans ce menu arborescence, les composants suivants peuvent être trouvés:

AirTerminal Annotation Beam BuildingElementPart BulidingElementproxy Coil Column Covering CurtainWall Damper Distributionport DiscreteAccessory Ductfitting DuctSilencer Door ElementAssembly EnergyConversionDevice Fan Fastener Filtres FireSuppresionTernimal FlowController FlowFitting FlowMovingDevice FlowSegment FlowStoragedevice FlowTerminal Footing FurnishingElement GeographicElement Grid HeatExchanger LightFixture Membres OpeningElement PipeFitting PipeSegment Pump Plate Railing Ramp Roof SanitaryTerminal Site Slab Space SpaceHeater StackTerminal Stair StairFlight TransportElement UnitaryEquipment Valve Wall WallStandardCase WasteTerminal Window

## 5. Arborescence des types

L'arborescence des types affiche tous les objets triés par type.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/04-type-tree.png)

## 6. Arborescence des calques

L'arborescence des calques fournit une vue hiérarchique des calques du modèle.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/05-layer-tree.png)

## 7. Arborescence des systèmes

L'arborescence des systèmes fournit une vue des systèmes du modèle.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/06-system-tree.png)

> **Remarque:** L'objet sélectionné dans l'arborescence et dans le modèle sont synchronisés. Si vous cliquez sur une fenêtre en mode 3D, elle est sélectionnée dans l'arborescence. Et vice versa. Vous pouvez également double-cliquer sur une "feuille" du modèle et faire déplacer la caméra 3D vers cet objet.
