# Model tree panel

The model tree panel can be found as one of the four [project panels](https://support.catenda.com/en/articles/13141464-project-panels) that can be opened on the top right of the screen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/01-intro.png)

## 1. **Opening the model tree panel**

The model tree panel can be opened side by side to any of the other panels.

_Opening the_ model tree _panel:_ Click the tree icon or Press [shift+3](https://support.catenda.com/en/articles/4670267-summary-of-most-important-shortcuts-and-basic-controls#:~:text=row%20of%20objects-,Shift%20%2B%203,-Control%20%2B%20left%20click)

_Isolating the_ model tree _panel:_ Open the tree panel Close any other panels that are open by clicking on them.

## 2. **Model tree** **panel content**

In the trees panel the content of the IFC can be viewed in differen tree structures. The structure that is displayed comes directly from the IFC model that is selected towards the top. Each of the trees shows parts of the IFC in different ways. List elements for objects that are visible in the 3D viewer may be visible in one or more of the model trees depending on if they fit that way of viewing the IFC contents. Other list elements can include grouping of these objects and/or other entities from the IFC.

### 2.1 **List element naming**

List elements can be named in different ways. Named entities can be named by the name they were assigned in the IFC but entities can also be named after the name of the entity itself as specified in the BuildingSMART standard. If no translation is available per standard the name can be displayed in English which is the base langague. To contribute to the translation in the open standard see [here](https://user.buildingsmart.org/knowledge-base/ifc-translations-manual/). To see if an entity has a translation go to the BuildingSMART page for that entity and change the language to the language. The entity name will either be translated or there will be a message towards the top that this entity is lacking translation.

**Grouping entities** Entities that can contain other entities like a building that contains walls can be named after the name that has been given to that entity if present or after the name of the Entity per BuildingSmart standard.

**Single elements** Single elements are the elements at the lowest level when the tree view is fully expanded and can look something like so:

`Entity.Set.Number`

Name These elements are listed by the name of their enitity according to the BuildingSMART standard.

Set There are often many similar elements that are grouped together so after the entity name is the number of the nth set of these types of entities that this entity belongs to.

Number Finally number of the nth entity in the set is listed. For example the 21st window on level 2 can look something like this:

`Window.1.21`

### 2.2 **Higlighted elements**

Like in the 3D viewer, selected objects are highlighted in green and selected groups of objects are hightlighted in yellow. Unlike in the 3D viewer it is also possible to highligt entities that can contain objects and hightlight sets of objects that are similar. If an object is highlighted in the 3D viewer but no object is highlighted in the model tree panel it could be that the object is highlighted in another model tree menu.

**Zoom to list element** Trees can get quite long. When an object is selected in the 3D viewer the tree menu is scrolled to the location in the list where the selected object exists granted that that object exists in the tree menu that is open in the model tree panel.

### 2.3 **Selection**

List elements from multiple models that are loaded in the 3D viewer can be selected. Click on the dropdown towards the top to switch between the different models. Selections can be saved in the selections menu.

**Active element** The active element is highlighted with a red dotted outline. Use the arrow keys to move up and down the list.

**Single selection** After clicking on a list element to select it the element will be set to the active element and the previous selection is erased.

Click a list element or press enter on the active element to: Select an object. Select a set of objects and all similar objects in a set of objects. Select a group of sets and all subelements in that group.

**Editing selection** Ctrl+Click a list element or press Ctrl+Enter on the active list element to: Add list elements that were not previously selected to the selection. Remove list elements that are selected from the selection.

**Set selection** Shift+Click a list element or press Shift+Enter on the active list element after having selected a different list element to: Select all list elements between the previously selected element and the selected element.

**Zoom to list element** Doubleclick on a list element to zoom the 3D viewer on that list element.

## 3. **Containment tree**

The containment tree provides a hierarchical perspective on how the different IFC objects relate to each other.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/02-containment-tree.png)

When the shortcut "`p`" is pressed to select the parent node, this can visually be observed in the containment tree.

## 4. **Component tree**

The component tree provides a hierarchical perspective on the components that make up an object.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/03-component-tree.png)

In this tree menu components like the following can be found:

AirTerminal Annotation Beam BuildingElementPart BulidingElementproxy Coil Column Covering CurtainWall Damper Distributionport DiscreteAccessory Ductfitting DuctSilencer Door ElementAssembly EnergyConversionDevice Fan Fastener Filter FireSuppresionTernimal FlowController FlowFitting FlowMovingDevice FlowSegment FlowStoragedevice FlowTerminal Footing FurnishingElement GeographicElement Grid HeatExchanger LightFixture Member OpeningElement PipeFitting PipeSegment Pump Plate Railing Ramp Roof SanitaryTerminal Site Slab Space SpaceHeater StackTerminal Stair StairFlight TransportElement UnitaryEquipment Valve Wall WallStandardCase WasteTerminal Window

## 5. Type tree

The type tree shows all the objects sorted by their type.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/04-type-tree.png)

## 6. Layer tree

The layer tree provides a hierarchical view of the layers in the model.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/05-layer-tree.png)

## 7. System tree

The system tree provides a view of the systems in the model.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/06-system-tree.png)

> **Note:** The object selected in the tree and in the model are in sync. If you click on a window in the 3D mode, it is selected in the tree. And vice versa. You can also double-click on a “leaf” in the model and make the 3D camera move to that object.
