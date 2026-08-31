# 2D viewer interactions

> Interacting with the 2D viewer

Different components of the [2D viewer](https://support.catenda.com/en/articles/4854537-2d-viewer) can be interacted with in different ways. Each of the parts of the 2D viewer that can be clicked on are described in this article. This is what the 2D viewer can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/01-intro.png)

This article contains information about the following topics: _[2D button](#h_ddfb1f5837) - [Top bar](#h_7996dde66c) - [Canvas](#h_d564366bf9) -_ [Navigation](#h_b384896c43) - [Selection](#h_8916df6427) - [Settings](#h_f9d34c17aa) - [Bottom bar](#h_15dafd8ad4)

## 1. **2D button**

If the 2D viewer is not opened, click on the 2D button on the bottom right of the 3D viewer top open the 2D viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/02-2d-button.png)

## 2. **Top bar**

### 2.1 **Resizing**

Drag these two diagonal lines to resize the 2D viewer across any part of the 3D viewer. You will know you can drag this corner when you see your cursor change.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/03-resizing.png)

### 2.2 **Title**

The title of the top bar will be the name of the storey. If a storey of a [storey configurator](https://support.catenda.com/en/articles/6921756-storey-configurator-page) building is selected title will include the name of the building and the name of the current storey. If the storey of a non-configured model is selected the title will include the name of the model.

### 2.3 **Opening and closing the 2D viewer**

**Closing** Click the cross in the top right of the 2D viewer to close the 2D viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/04-opening-and-closing-the-2d-viewer.png)

## 3. **Canvas**

The canvas of the 2D viewer is the part of the 2D viewer where the lines connected to the storeys of the differnet models of which 2D views are enabled are displayed.

### 3.1 **Click mouse button**

_Left click_ If there are spaces in the storey of the 2D view that is enabled for a model they can be select by clicking on them. It is possible to tell if there are spaces in the 2D view by the name of the space being visible in the center of the space.

**Scroll** Zoom in and out of the 2D viewer.

**Right click** Open context menu

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/05-click-mouse-button.png)

- _Add marker_
Add a new marker. With a topic open in the content panel you can assign the selected marker. This marker will not be saved and visible to others until added to an issue.
- _Create a new topic with marker_
Create a new topic with marker. This marker will not be saved and visible to others until the topic is sent in.
- _Create query_
    - Intersect space - Create a [query](https://support.catenda.com/en/articles/4854514-queries) of all objects intersecting with the selected space
    - Intersect storey - Create a [query](https://support.catenda.com/en/articles/4854514-queries) of al objects intersecting with this storey

### 3.2 **Hold mouse button**

**Hold left or right click** Pan 2D viewer

### 3.3 **Viewpoint indicator**

**Hold left click on viewpoint indicator** Move camera in 3D. Camera angle will remain.

**Hold right click on viewpoint indicator** Move camera in 3D. Camera angle will follow.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/06-viewpoint-indicator.png)

## 4. **Navigation tools**

### 4.1 **Zoom to extents**

Zoom out to show all visible objects at once

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/07-zoom-to-extents.png)

### 4.2 **Rotation**

With the rotation button you can rotate the 2D viewer.

**Rotation slider** The initial rotation can be configured by setting a location with a rotation in [project settings](https://support.catenda.com/en/articles/4670273-project-settings-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/08-rotation.png)

**Slider adjustment** Select the slider by clicking on it and use the left and right arrow keys to make 0.1 degree adjustments. This can be useful for making selections, sections and queries. Rotation is easier if you first select a space as it will snap to the edges of the space when rotating You can also write the degree of rotation in the menu below the slider.

**True North** If no initial rotation is configured in project settings True North will be the same as the reset button. If an initial rotaiton has been configured in project settings True North might be at an angle relative to the inital rotation

**Reset** Click Reset on the top right to reset the slider ot the initial rotation.

**Underlayed drawing rotation** Buildings can be configured in the [storey configurator](https://support.catenda.com/en/articles/6921756-storey-configurator-page). Each storey in a building can have a drawing as an underlay that is rotated relative to the models in the project.

### 4.3 **Lock camera**

If a model is loaded in the 3D viewer you will be able to lock the camera to the 3D viewer camera.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/09-lock-camera.png)

With this function enabled the viewpoint indicator will stay centered on the canvas even if the camera is moved in the 3D viewer. This is useful in combination with [walk mode](https://support.catenda.com/en/articles/5784718-3d-viewer-settings#h_1c05dca226).

## 5. **Selection tools and settings**

The selection tools and settings can be found towards the top right of the 2D viewer canvas.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/10-selection-tools-and-settings.png)

Click [here](https://support.catenda.com/en/articles/8035360-selecting-and-clipping-from-2d) for a detailed explanation of how to use section tools in the 2D viewer.

### 5.1 **Select**

Select spaces and zoom in and out.

### 5.2 **Section: Select objects**

Drag a rectangle over the 2D canvas to create a volume for selection of objects in 2D/3D.

### 5.3 **Section: Create clipping planes**

Create 4 to 6 clipping planes by dragging a rectangle over the 2D canvas and selecting the height.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/11-section-create-clipping-planes.png)

### 5.4 **Section: Create query**

Create a [query](https://support.catenda.com/en/articles/4854514-queries) by dragging a rectangle over the 2D canvas and selecting the height.

### 5.5 **Move button**

The rectangular selection function of the Section tools inhabits the movement of the cursor. On the bottom right of the 2D viewer you will therefore be able to use the move button. With this button you can easily reposition your canvas for Sectioning.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/12-br-move-button.png)

## 6. **2D Viewer Settings**

The settings of the 2D viewer can be found in the dropdown button with the gear icon.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/13-2d-viewer-settings.png)

**Marker coloring mode** Change the color of the markers in the 2D view to have the color of one of the following:

- Status
- Type
- Due date

**Space Name Format** Show the long name of the rooms and spaces

**Translucent** Make the 2D viewer see-through

## 7. **Bottom bar**

### 7.1 **Model view**

Click here to read more about the storey menu. The storey menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/14-model-view.png)

### 7.2 **Layer menu**

With the layer button you will be able to toggle different layers in the 2D viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/15-layer-menu.png)

**Markers** With this button, markers can be toggled on or off.

**Models** With this button, models can be toggled on or off.

**Drawings** You will see this button if a drawing has been aligned as an underlay for a building storey in the [storey configurator](https://support.catenda.com/en/articles/6921756-storey-configurator-page). With this button, the aligned drawings can be toggled on or off.

**Map** You will see this button if a location has been configured in [project settings](https://support.catenda.com/en/articles/4670273-project-settings-page) With this button, the map can be toggled on or off.
