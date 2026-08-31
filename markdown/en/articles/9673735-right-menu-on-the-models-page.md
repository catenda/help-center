# Right menu on the models page

The right information menu can be found by selecting a model on the [models page](https://support.catenda.com/en/articles/4670286-models-page) or by entering the [content page](https://support.catenda.com/en/articles/4670270-model-overview-page) of a model.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/01-intro.png)

Click the "i" icon on the top right to open the right menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/02-intro.png)

The menu can look something like this for a single model:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/03-intro.png)

Or like this with multiple model rows selected.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/04-intro.png)

## 1. **Model header**

In the model header information about the latest revision of the model is displayed.

### 1.1 **Image**

Towards the top of the model header an image can be added for the model. This is what it can look like when no image is added.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/05-image.png)

Either upload a local image or add a snapshot directly from the 3D viewer without uploading anything. This is what the models page when an image is configured for a model:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/06-image.png)

_Model image in right menu_ When added, the image is displayed towards the top of the right menu of a model when a single model is selected or when the menu is open on the model content page. The added image is both displayed in the right menu of a model revision when one model is selected as well as in the thumbnail of the model in the name column of the models table.

Click [here](https://support.catenda.com/en/articles/4670257-creating-a-thumbnail-for-your-model) to read more about how to add an image for a model.

**Model thumbnail** When added, the image is displayed as a thumbnail for the model in the name column of the models table on the models page.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/07-image.png)

Click on the thumbnail to open a preview of the image. This is what the thumbnail preview can look like.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/08-image.png)

From the navigation towards the top the image can be downloaded. If the snapshot was taken from a model the preview is a 3D preview so it is possible to navigate around the model from the starting point of the model thumbnail.

### 1.2 **Document link**

The document link is the gray box below the model image. The box will show the location of the document-model in the file structure. Under it you will see the name of the document-model that is linked to this model-document. Click on this box to be taken to the document preview page of the document-model on the documents page.

### 1.3 **Status**

The status of the latest public document-model revision.

### 1.4 **Labels**

By default labels can be applied to any model. If shared revisions are activated there has to be at least one published revision in the model to be able to add labels. Lables are both saved for the model and for the document that the model is linked to. The same label can therefore be used to filter for models on the models page and documents on the documents page.

## 2. **Contributors**

The different members that have uploaded revisions and thereby contributed to the model are displayed here.

## 3. **Model transformation**

With model transformation model objects can be configured to be displayed at a diffent location and orientation within the Catenda Hub 3D viewer. This transformation only applies to models in the 3D viewer and not 3D documents that have been loaded in the 3D viewer. Click [here](https://support.catenda.com/en/articles/12498975-add-context-to-your-projects-with-freely-accessible-ign-point-clouds-hd-lidar) to read more about the transformation of 3D documents.

**Exchanging models with external tools** Models are often downloaded from Catenda and opened in a third party program. It continues therefore to be important to have the right coordinates configured in the IFC file before upload so the downloaded file contains the right information.

**When should the model be transformed?** There is often a period where a model is submitted and the geometry is already used to collborate even before the coordinates in the model are correct. This can come from different reasons for example that a common zero point is not decided on in the project of that a different export method has to be looked at in the authoring program where the IFC file was generated. It can help to transform the model (only in Catenda Hub through the browser) with model transofmation during this period so that playing 3D snapshots continues to match, even with newer revisions that have updated coordinates.

**Coordinate collaboration with shared revisions** In a project where shared revisions are activated it is not recommended to publish model revisions without having the right coordinates in the IFC file.

### 3.1 **Model transformation settings**

Load the model that is to be moved in the 3D viewer. This can either by done by clicking on the 3D button on the dashboard, on the models page, on the model content  page or in the revision selector. In the right menu on the models page the transformation settings menu will be shown towards the bottom of the menu. Dhis is what the model transformation settings can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/09-model-transformation-settings.png)

**Offset** Enter X, Y and/or Z coordinate to displace the model. Units - Meter

**Rotation** Enter a an angulation to rotate the model. The model is rotated around the midpoints of its bounding box that contains all the objects of the model. The point is often around the middle of the model seen from above. Units - Degrees

**Save** Click on save to save the transformation settings.

### 3.2 **Only in browser**

The IFC file will not be changed when the transformation settings are saved. If a new model is created with the IFC file either within the same project or in a different project, the IFC file will egain be displayed at the location that is configured in the IFC file.

It is often not a problem to move a model in catenda for short periods of time or even for the whole lifetime of the project. In the end it can save a lot of time to decide a common coordinate system so that models do not need to be adjusted after their creation and to prevent misunderstandings during the course of the project.

## 4. **Multi select**

With multiple models selected the right menu can look like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/10-multi-select.png)

Click on the red x next to a model to remove it from the selection.

### 4.1 **Update selected documents**

This is what the update selected documents menu can look like

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/11-update-selected-documents.png)

Click in the add and remove labels areas and select one or more labels.

_Adding takes priority_ A label that is entered in both the add and remove label fields is added to models that do not have the label yet and not removed from models that already have the label.

### 4.2 **Latest revision**

The entered status will be configured for all selected models when the the changes are saved.
