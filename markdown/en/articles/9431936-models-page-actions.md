# Models page actions

Depending on your access and your selection actions for your models and their latest revisions can be seen on the [models page](https://support.catenda.com/en/articles/4670286-models-page).

## 1. **New item actions**

The plus button and hamburger menu items can be found towards the top right of the page and can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/09fxhve6/01-new-item-actions.png)

_Access required:_ Creating or downloading models or access to a document-model in the documents section

### 1.1 **New model**

Both the plus button and the new model action will open up the new model dialogue. The new model dialogue can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/09fxhve6/02-new-model.png)

With the new model button on the models page you will be asked to select a folder where you want the document-model to end up.

**Name** The model has to be given a name before you can create it.

**Folder** When you create the model a document with no revisions will be created in the folder that you choose in this dialogue. If you choose Root folder the document-model will end up in the top level of the document section. After creating your first model in a project the model folder preference for your account will be saved so you do not have to choose it each time. You can click on the folder later if you want the model to end up somewhere else.

**Keep open on submit** If you are creating a couple of models you can select the keep open on submit option. This way you do not have to click on new model each time as the menu will stay open. If you are creating many models at once it is recommended to upload them to the documents section and use the create model selected item action instead.

**Create** After clicking on create you will be taken to the [model overview page](https://support.catenda.com/en/articles/4670270-model-overview-page) of the newly created model.

_Access required:_ Creating and deleting models in project settings and write access to a location in the documents section.

**Creating models in the document section** If you already have the file you want to create a model with in the documents section, you can select it there and use the create model selected item action to create the model. The system might be able to import large files (700mb+) better this way as it does not have to deal with imports. You can create multiple models at a time in the document section as you can upload them, select them and then click create model. When creating models in the document section the name of the model in the models section will be the same as the name of the document linked to the model.

### 1.2 **Exports**

This action will take you to the [model export page](https://support.catenda.com/en/articles/4670280-model-export) where you will be able to create a zip file with a chosen revision for each of the models you have access to. _Access required:_ Access to at least one document-model in the models section.

## 2. **Selected item actions**

After selecting one or more model(s) you will be able to see the following action menu appear towards the top of the documents table. The existing item actions menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/09fxhve6/03-selected-item-actions.png)

### 2.1 **2D viewer**

With the 2D viewer action you will be able to open your selected model(s) either by clicking on the 2D icon on top or by opening the hamburger menu and clicking on the 2D viewer action. _Access required:_ Access to at least one document-model in the models section.

### 2.2 **3D viewer**

With the 3D viewer action you will be able to open your selected model(s) either by clicking on the 3D icon on top or by opening the hamburger menu and clicking on the 3D viewer action. _Access required:_ Access to at least one document-model in the models section.

### 2.3 **Publish**

If shared revisions are enabled in the [status workflow menu](https://support.catenda.com/en/articles/12495583-status-workflow-document-settings) of document settings in the project, any new revision that is created starts out as a shared revision that can later be published.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/09fxhve6/04-publish.png)

In the workspace tab row elements show the latest shared revision for each model. In the published tab row elements show the latest published revision for each model. Shared revisions can be differentieated from published revisions by the icon in the revision column and the fact that they have a minor revision number (0.1, 0.2, 1.1, etc...) _Access required:_ View shared revisions in document-model access settings Select one ore more models where the latest revision is a shared revision to see the publish action in the action menu. _Access required:_ Can publish in document-model access settings

With the publish action the latest shared revision can be published. Previous shared revisions that were uploaded after the latest published revision can be published from the [model overview page](https://support.catenda.com/en/articles/4670270-model-overview-page). After publishing a new published revision with a major number (1.0, 2.0, 3.0 etc...) is added. This published revision will be visible both in the workspace and published tabs.

### 2.4 **Download latest revision**

If you have access to downloading models you can click on the download button. This will let you download the latest revision of a model as an ifc file. If you are looking for a previous revision of this model please to the its [model page](https://support.catenda.com/en/articles/4670270-model-page) _Access required:_ Access to at least one document-model in the models section.

### 2.5 **New revision**

Select a single model and use the new revision action or drag and drop a file on a revision to upload a new revision to that model. _Access required:_ Creating and deleting models in [project settings](https://support.catenda.com/en/articles/4670273-project-settings-page#h_f82a1850f3) and write access the document-model.

Revisions can only be uploaded to one model at a time on the models page. Use the "is model" filter in the documents area and upload from there to upload up to up to 100 documents at once. Use the Catenda Desktop Connector to schedule regular uploads if the local file has changed.

**What can be uploaded?** When uploading a new revision with the new revision action choose a .ifc or a .ifczip file from your local harddrive. Both the model and the document that is linked to the model will have the same revisions. Although other 3D filetypes from the documents section can be loaded together with the models from the models page in the 3D viewer, only IFC files are accepted in the models section. Click [here](https://support.catenda.com/en/articles/4670320-previewing-file-types-on-catenda-hub) to see what filetypes can be previewed on Catenda.

**Plugin and integration upload** Many of Catenda's plugins and integrations as well as custom-built tools by clients with API credentials allow for the creation of new revisions as well. Click [here](https://support.catenda.com/en/articles/8396532-catenda-plugins-integrations) to see which plugins and integrations are currently available.

**Revision comment and other metadata** The best way to add a revision comment when using Catenda Hub via the browser is to place document that is linked to the model in a configured folder. Configure a text field called comment for the folder so a comment can be added as metadata to the document after the revision is uploaded. A comment field that can be submitted via the API exists and is available in some of the plugins and integrations. When submitted, comments from plugins and integrations can be seen with the view comments button on the [model contents page](https://support.catenda.com/en/articles/4670270-model-contents-page).

_IFC checkin processing_ When the upload process is complete, Catenda Hub analyzes the IFC file and generates the geometry in the background. For large models it can take some time before the file is ready to be worked on in the viewer. During this processing Catenda Hub can be exited as geometry generation happens uninterrupted whether Catenda Hub is opened or not. When importing is complete a notification will pop up in Catenda Hub and additionally a notification email can be sent stating that a new version is uploaded to a model for which you have access.

### 2.6 **Copy link**

With the copy link action a link that displayes only the selected table rows can be copied. Click [here](https://support.catenda.com/en/articles/14323982-copy-link-action) to learn more about copying links.

### 2.7 **Remove**

With this action you will be asked to confirm before removing the model from the models page.

> **Note:** Removing the model only removes it from the models page. The document-model will remain in the documents section and will have to be deleted with the selected document delete action if you want that deleted too. The model can always be made again from the same document in the models section.

_Access required:_ Creating and deleting models in project settings and write access to model(s) you are attempting to remove.
