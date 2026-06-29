# Documents table actions

Depending on your access and your selection different actions for your documents and folders can be seen on the [documents page](https://support.catenda.com/en/articles/8204673-documents-page).

**This article contains information about the following topics:**

## 1. **New item actions**

The plus button and hamburger menu items can be found towards the top right of the page and can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/01-new-item-actions.png)

The actions you are able to find here all have to do with creating new information. [Selected item actions](#h_fb4e9ef375) that have to do with existing items on the page can also be found towards the top of the list after making a selection.

### 1.1 **Upload**

Both the plus button and the upload action will open up the upload 'upload a document menu'. Click [here](https://support.catenda.com/en/articles/4670278-uploading-a-document#h_00fa77db3e) to see how the upload dialogue works. _Access required:_ Write access to the folder you are in or to the document(s) or folder(s) in the folder you are in. Access to [uploading draft revisions with read only access](https://support.catenda.com/en/articles/4670273-project-settings-page#h_f82a1850f3) can also be given in project settings.

### 1.2 **New folder**

To make a new folder in the document location you are currently in you can use the new folder action button. The new folder dialogue that opens up can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/02-new-folder.png)

When you are creating a document structure or have to make many folders at a time it can be tedious to have to click on the new folder button many times. To make many folder at once it can help to prepare the folders externally and upload them all at once with the upload zip action. _Access required:_ Write access to the folder you are currently in

### 1.3 **Upload zip**

The upload zip action will let you extract the contents of a zip file in the document structure. It is also possible to upload a zip document with the upload action button but then you just get it as a zipped file and you do not see the contents of the zip file. Click [here](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure#h_54ace27f24) to read more about how to upload a zip to Catenda.

**Access required:** Write access to the folder you are currently in. If you use the create new draft option: Write access to the folders with the same name and structure location as folders in the zip relative to where you upload the zip Write access to the documents you might be adding revisions to.

### 1.4 **My zip uploads**

The my zip uploads action will let you see an overview of your previous zip uploads

## 2. **Selected item actions**

After selecting one or more document(s) you will be able to see the following action menu appear towards the top of the documents table. The existing item actions menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/03-selected-item-actions.png)

### 2.1 **Download**

With the download action selected items and their contents can be downloaded by clicking on the download icon on top or by opening the action menu and clicking on the download action in the dropdown menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/04-download.png)

Receive a single document with one document row selected. Receive a zip file that contains the content of the selection when a folder row or multiple rows are selected. _Access required:_ full access to your selected document(s) and/or folder(s)

**Discovering documents** Once the download button is pressed a dialogue opens up towards the bottom left of the page. First the system will start discovering the different files in the download. This is what the preparing download dialogue can look like:

![Preparing download zipping files](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/05-download.png)

At this point it is safe to move to a different page on Catenda. The files will start downloading to the local system as soon as the download is prepared. When multiple downloads are started at the same time they will be added to the same dialogue. It is even safe to completely power off your system and come back later when the download is prepared. It is always possible to download the prepared documents from the notification that is created when the download is prepared.

_Zipping files_ As soon as the total amount of files has been discovered the amount of files listed in the dialogue. Draft or withdrawn revisions are not included in this number. Catenda will then start putting the files together in a zipped file that can be downloaded once it is prepared:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/06-download.png)

_Ready for download_ Once the zip file has finished preparing the file navigator of the system will open up. The navigator asks to save the zipped file somewhere on the local machine.

![Preparing download files zipped](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/07-download.png)

When the zip has finished preparing a notification is sent that the zip download is ready. Click on the text in the notification that says "Click to download (...MB)" In order to download the document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/08-download.png)

### 2.2 **Move**

With the move action you will be able to move your documents to another location either by pressing the move icon on top or by clicking on the move action in the hamburger menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/09-move.png)

After pressing the move button you will get a window that asks you where you want to move the document(s) and/or folder(s) to. _Access required:_ full access to your selected document(s) and/or folder(s) and write access to the location you are moving to.

### 2.3 **Link and unlink**

When you select a document you will see the link and unlink icons next to the download icon or in the hamburger menu. These options might be grayed out if you do not have object of a model in the 3D panel selected.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/10-link-and-unlink.png)

After both selecting document(s) in the documents section of the content panel and an object(s) of model(s) in the 3D viewer you will be able to link and unlink your object(s) to the document(s). _Access required:_ read or write access to your selected document(s) and read access to at least one document-model

### 2.4 **Report**

The reporting tool can be requested to be activated on a per project basis. With the report action you will be able to create a report of your selected documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/11-report.png)

Click [here](https://support.catenda.com/en/articles/13973721-create-report-action) to read more about the report action. _Access required:_ Read access to the document

### 2.5 **Publish**

With [revision publishing](https://support.catenda.com/en/articles/9874698-revision-publishing-iso-19650) enabled the workspace and published tabs can be seen towards the top of the models page.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/12-publish.png)

In the workspace tab shared revisions can be seen. You will be able to tell shared revisions apart from published revisions by the icon in the revision column and the fact that they have a minor revision number (0.1, 0.2, 1.1, etc...) _Access required:_ View shared revisions in document-model access settings After enabling the status workflow every new revision in a document will start out as a shared revision which can be published. Select one ore more documents where the latest revision is a shared revision to see the publish action in the action menu. _Access required:_ Can publish in document access settings With the publish action you will be able to publish the latest shared revision. If you wish to publish a previous shared revision, you can publish it from the [revision preview](https://support.catenda.com/en/articles/9323521-document-revision-actions).

### 2.6 **Preview**

To preview your selected document(s) you can can either click on the preview action button in the hamburger menu or click on the icon of the document in the documents list. You will then get a preview dialogue which you can use to easily preview the different documents without having to open the page of each document. This is especially nice if you are trying to preview many images but can also be useful if you need to see two documents next to each other as you can pin the preview so it stays open. _Access required:_ Read access

> **Note:** Folders and draft documents cannot be previewed in the preview dialogue. Draft documents can still be previewed on their [document page](https://support.catenda.com/en/articles/8461918-document-banner-navigation).

### 2.7 **3D Models**

If your document can be loaded in the 3D viewer you will be able to click on the 3D action button to load the selected document-models and/or point clouds in the 3D viewer. This action is only available if you have selected IFC(s) (IFC and IFCZip) that are linked to models in the models section, point cloud(s) (Las and e57) and/or Gml documents It is also possible to load the preview of ifc documents that are not linked to models in the 3D viewer but those will have to be loaded from the revision dropdown inside the document. _Access required:_ Read access to the ifc, ifczip, las, e57 or gml document

### 2.8 **New revision**

If you have selected one document you will be able to upload a new revision by clicking on the new revision action in the hamburger menu. This will open the file explorer and there you can choose the file you want to upload. Uploading a file like this will create a new revision and not a new document. It is one possible to upload new revisions to one document at a time with the action button. If you wish to upload multiple revisions to multiple documents in the folder you can do so with the upload action button. _Access required:_ Write access to the selected document

### 2.9 **Create and remove model**

**Create model** A selected document with the `.ifc` or `.ifczip` extention can be linked a model in the models section with the create model action. The first time a model-link is created for a document, the model that appears on the models page will have the same name as the document it was created from. Both the name of the model on the models page and the name of the document can later be changed. A document that has previously had a model-link will remember what name that model had and apply the previous name that the removed model had when a new model-link is created, even if the current document name is different. _Access required:_ Write access to [create and remove models](https://support.catenda.com/en/articles/4670273-project-settings-page#h_f82a1850f3) in project settings

**Remove model** The link of a document that is linked to a model can be removed with the remove model action.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/13-create-and-remove-model.png)

When the model-link is removed, the model will disappear from the models section while the document remains in the document section. A model-link can later be created from the same document again. _Access required:_ Write access to [create and remove models](https://support.catenda.com/en/articles/4670273-project-settings-page#h_f82a1850f3) in project settings

### 2.10 **Copy link**

With the copy link action a link that displayes only the selected table rows can be copied. Click [here](https://support.catenda.com/en/articles/14323982-copy-link-action) to learn more about copying links.

### 2.11 **Deleting and restoring**

Use the delete action on a selected element to delete it. A window will appear asking for confirmation to delete the element(s). _Access required:_ Full access to the selected document(s) Full access to the selected folder(s) and their contents Deleted elements can be recovered. Filter on deleted, select the element and use the restore action. _Access required:_ Administrator

**Topic relation** A deleted document that was linked to a topic is seen as a question mark in the related documents area of a topic. A restored document will once again be revealed in the topic.

_Model link_ A deleted document that was linked to a model is unlinked upon deletion. A restored document will therfore no longer be linked to a model. Use the create models action once more to connect it to a model again. The previous model settings like the model name and processing is stored so they do not have to be re-configured.

**Storey configurator** A deleted document that is configured as an underlay for a storey in the storey configurator will disappear from the 2D view for project members. A restored document that was configured as an underlay for a storey in the storey configurator will once again be revealed in the 2D view for that storey.

_Object relations_ A deleted document that was linked to an object is unlinked upon deletion. A restored document will therefore not be linked to any objects.

## 3. **Current folder actions**

If you have opened a folder, but not selected anything the [right information menu](https://support.catenda.com/en/articles/8302244-right-menu-in-a-document) will show actions for the folder you are in. The right information menu might be closed and you may have to click on the arrow on the right side to open it. These actions can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yvm5kp30/14-current-folder-actions.png)

Because you have not selected anything the selected item actions will not show towards the top of the documents table. Instead you will be able to perform actions on the folder you are in with the icons and hamburger menu in the [right information menu](https://support.catenda.com/en/articles/8302244-right-menu-in-a-document).

**Access required:** Download: Read access to the current folder Move: Full access to the current folder and write access to the location you are moving the folder to. Delete: Full access to the current folder and its contents.
