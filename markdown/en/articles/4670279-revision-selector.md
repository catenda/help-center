# Revision selector

The revision selector is a dropdown menu that can be found top left of the screen in the [3D viewer](https://support.catenda.com/en/articles/8227211-3d-viewer) panel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/01-intro.png)

Clicking on the button with the “cube” to open the revision selector.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/02-intro.png)

Information about the following topics can be found in this article:

## 1. **Models**

In the models menu you can work with 3D documents while keeping the 3D viewer panel in full focus.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/03-models.png)

The models menu can look something like this.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/04-models.png)

Enable or disable the visibility of 3D documents choose which revision should be displayed for each document.

### 1.1 **Search**

Find the 3D documents you are looking for by searching on part of their names.

A partial match of 3 roman letters or more can be matched in the list of 3D document names. Whitespace characters like space "" are not included in this amount.

**Match after separator** After a separator the three character rule is reset and only three or more characters after a separater can be matched. The three character rule is reset after each separator. Separators can be characters like underscores "`_`" or a dashes "`-`".

**Content panel** To narrow down your search further consider searching in the content panel. Here you can filter on more information than just the name of the model. In the content panel all 3D documents that have been linked to a model can be found on the [models page](https://support.catenda.com/en/articles/4670286-models-page). 3D documents that have not been linked to a document can be found on the [documents page](https://support.catenda.com/en/articles/8204673-documents-page).

### 1.2 **3D document list**

See the 10 most relevant 3D documents. The 3D document list is sorted after the [typical sorting order of lists on Catenda](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists).

_Models -_ Displayed by default See all the [Ifc documents](https://support.catenda.com/en/articles/5658031-ifc-support-in-documents) that have been linked to a model. Your list of available models is based on the access setting of the document that is linked to that model.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/05-3d-document-list.png)

_3D documents -_ Displayed when loaded in Load 3D documents from the documents page to display them towards the top of the list. See [here](https://support.catenda.com/en/articles/4670320-previewing-file-types-on-catenda-hub#h_2edd1d4e9c) which document formats can be loaded in the 3D viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/06-3d-document-list.png)

_Load more_ To load in more models click on the load more button at the bottom of the revision selector.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/07-3d-document-list.png)

### 1.3 **2D button**

When the 2D button is green, the 2D view of that model is visible in the [2D viewer](https://support.catenda.com/en/articles/4854537-2d-viewer) and loaded into memory. When the button is grey the 2D view of that model model will not be visible and is not loaded into memory.

### 1.4 **​3D button**

When the 3D button is clicked it will turn green. The 3D view of that document will then be available in the [3D viewer](https://support.catenda.com/en/articles/8227211-3d-viewer) and loaded into memory. While the 3D button is green model objects that belong to that model will be available in the 3D viewer.

> **Note:** Available does not mean visible as objects can be hidden and still be available.

After a model has been loaded into memory the 3D button can be clicked again. While the objects are not available in the 3D viewer, the document will still be loaded in memory. This makes it you can quickly turn on and off documents that you have previously loaded.

**Unloading from memory** To unload models from memory, refresh the page or go to the models page of the specific model you wish to unload. To unload documents from memory, press the x to the right of the document name.

### 1.5 **Center objects**

Click this button to center the camera position on the locaiton where most objects in this model exist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/08-center-objects.png)

Only available for models.

### 1.6 **Zoom to extents**

Click this button to see an overview of the entire contents of this 3D document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/09-zoom-to-extents.png)

Only available for 3D documents that have been loaded in the 3D viewer.

### 1.7 **Filetype icon**

The icon of each 3D document filetype. Only available for 3D documents.

### 1.8 **Name**

For models the model name is displayed. For documents, the document name is displayed. The documents list follows the general [sorting order of lists](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) in Catenda.

### 1.9 **​Model revision**

To the right of the 3D document name green underlined text can be seen. The text that is displayed reflects the number of the revision that will be loaded in when the 3D button is enabled. If a revision from the 3D document is already loaded in the number reflects the revision that is currently selected and loaded into memory.

Click on this text to change the active revision to a different revision of the 3D document.

> **Note:** It is only possible to load in one revision at a time per 3D document in the models menu.

After selecting a different revision the current revision is loaded out of memory and the selected revision is loaded into memory.

**Revision #X** If the text says `#X` or `#X.X` the latest revision of the 3D document is either available to load in or currently loaded in.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/10-model-revision.png)

If the text says `#X` the latest revision of the 3D document is a published revision. If the text says `#X.X` the latest revision of the 3D document is a shared revision.

**#76 of 77** If the selected revision is not the latest revision something like `#76 of 77` is displayed. #76 refers to the current revision numer and 77 refers to the latest published or shared revision in the 3D document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/11-model-revision.png)

If the latest revision is withdrawn or has failed processing, something like `#75 of 77` is displayed. #75 refers to the latest revision that is available to display objects in the 3D viewer.

**Struck through** If the revision text is struck through the selected revision is withdrawn and no 3D document objects are displayed.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/12-model-revision.png)

This usually only happens when a revision is loaded in and is withdrawn while it is loaded as withdrawn revisions cannot be selected.

**No text** If there is no text behind the 3D document there are no revisions and the document is empty.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/13-model-revision.png)

### 1.10 **Point cloud settings**

Point clouds can be configured in the revision selector by clicking the gear icon.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/14-point-cloud-settings.png)

Click [here](https://support.catenda.com/en/articles/5606625-point-clouds-in-catenda-hub) to read more about the different ways in which you can configure the 3D viewer for viewing point clouds.

### 1.11 **Unload document**

Click on the x to the right of a 3D document to unload it from the 3D viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/15-unload-document.png)

### 1.12 **Restore 3D**

It is only possible to load models in the 3D viewer from one revision selector menu at a time. If models from the models menu were loaded before a model was loaded in any of the other revision selector menus restore 3D can be clicked in the models menu to load the previously enabled set of models from the models menu back in the 3D viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/16-restore-3d.png)

## 2. **Queries**

Limit the objects you load into the 3D viewer with object queries. This lets you save memory when loading in hundreds of models at once as well as keep the object tree tidy. Click [here](https://support.catenda.com/en/articles/4854514-queries#h_b7e8a9a086) to see read more about queries.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/17-queries.png)

## 3. **Compare**

With the compare menu two model revisions can be selected to be overlayed. Click [Here](https://support.catenda.com/en/articles/4670313-revision-selector-short-video) to watch a short video about how to compare models revisions.

This is what the Compare menu can look like:

![Revision selector models queries compare is highlighted select model and revision color model](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/18-compare.png)

To start comparing click on "Select model and revision" and choose a model.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/19-compare.png)

In the list of revisions for that model, select a revision to start the comparison.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/20-compare.png)

Any models that were enabled in any of the other revision selector menus are unloaded and only the models in the compare menu are displayed as it is only possible to load models from one revision selector menu at a time.

This is what the 3D panel can look like after both model revisions are selected.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vh710sy2/21-compare.png)

The first and the second revision can be from the same or from a different 3D document that is linked to a model. All objects from the 3D document revision are highlighted in the color specified for the revision. Click on the color dropdown to change the color for all the objects in the 3D document revision.

If the 3D view from a different revision selector menu has been restored, the 3D button in the Compare menu gets disabled. Click the 3D button to enable/disable the compared revision again.

### 3.1 **Visualizing Differences**

After selection, the two model revisions will be overlayed in the 3D viewer. The revisions can now be compared visually. By seeing the overlap between the colored objects it is possible to see where one color is more prominent than the other. Colors for objects that are in the same location are added to each other. For example if red and blue were selected objects from both revisions that are in the same location are purple. This color differentiation makes it easy to identify changes between revisions.
