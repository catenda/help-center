# 2D viewer buildings and storeys

Information about the display which 2D cut through model objects and which drawings that are underlayed those cuts will be shown in the 2D viewer can be found toward the bottom right of the 2D viewer. The building and storey meny can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xw6p1nhs/01-intro.png)

## 1. **Storey lock**

### 1.1 **Locked**

The current storey will always be visible

### 1.2 **Unlocked**

The current storey will be the storey closest in height to the height of the camera. This is especially useful in [walk mode](https://support.catenda.com/en/articles/5784718-3d-viewer-settings) where the storey will change to the next storey if you walk up the stairs for example.

## 2. **Building menu**

If a building has been configured in the [storey configuator](https://support.catenda.com/en/articles/6921756-storey-configurator-page), you will be able to see the building menu. The building menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xw6p1nhs/02-building-menu.png)

### 2.1 **Storey configurator buildings**

First, any buildings that are created in the storey configurator will be listed. These buildings can contain storeys where multiple 2D views of models are combined and drawings can be underlayed.

### 2.2 **Model buildings**

Then the buildings that are available in each model for which the 2D view has been enabled will be listed. When the 2D view for a model is enabled, its 2D button will be active:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xw6p1nhs/03-model-buildings.png)

The name of a model building is configured in the ifc file of the current revision under the entity IfcBuildingStorey. If the model building does not have a name you will see it as unnamed building here.

## 3. **Storey menu**

In the storey menu you will see the storeys of the current building.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xw6p1nhs/04-storey-menu.png)

Click on the menu to see which storeys are available in your building. If the building has a name, you will see it in bold towards the top of the list. This menu will not be available if the current building does not have any storeys.
