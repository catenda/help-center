# Catenda SharePoint Application - Webpart

With the Catenda webpart you can browse the document section of a Catenda project within a SharePoint page. _Catenda Access required:_ Read to browse the document structure and write to upload SharePoint files to Catenda.

## 1. **Adding the webpart**

Edit an existing or create a new page in SharePoint and edit it. Hover over your page in edit mode until you see a line with a plus `----+-----` If the [Catenda SharePoint application](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application) is added to your site you will be able to find the the Catenda Document Webpart in your list of webparts.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/01-adding-the-webpart.png)

You will then be able to and add a Catenda webpart.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/02-adding-the-webpart.png)

If you have not already authorized your Catenda account the webpart will look like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/03-adding-the-webpart.png)

If you open a page with the Catenda webpart enabled and you have not yet authorized your account you will be asked to do so. Read more about how to authorize your account [here](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application#h_788fe15988).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/04-adding-the-webpart.png)

After authorizing your account credentials, click on Open webpart settings or click on the pencil icon to select the Catenda project for which the SharePoint page visitors will be able to see the documents section.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/05-adding-the-webpart.png)

This is what a configured webpart can look like when it is added:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/06-adding-the-webpart.png)

## 2. **Navigation**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/07-navigation.png)

### 2.1 **Viewing**

The path towards the top of the webpart shows the project that has been configured for this webpart and your current folder structure location.

### 2.2 **Navigating**

Click on any of the elements to go back to that part of the folder structure. Clicking on the name of a folder to open that folder. Clicking on the name of a document to open it directly in Catenda.

## 3. **Document table**

the document table can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/08-document-table.png)

If you have selected any elements you will see the amount of selected elements towards the top of the documents table.

### 3.1 **Selecting documents and folders**

Clicking anywhere outside of the name of the element in a row will select that row. Hold shift to select all items between the last selected item and the item you click on. Hold control to add/remove elements to your selection.

### 3.2 **Catenda access settings**

Each user has their own access in Catenda so some of your project members might see different folders and documents than others.

## 4. **Actions in the webpart**

On the top left of the webpart you will be able to find the following actions:

### 4.1 **Create folder**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/09-create-folder.png)

Creates a folder in the part of the document structure you are in. _Catenda access required:_ Write access

### 4.2 **Upload file**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/10-upload-file.png)

After clicking this a file navigator will open up, and you can select which document(s) you want to upload. After uploading the document you will see it both in Catenda and in the webpart. You will not see the uploaded file in the SharePoint document area this way. Only in Catenda. _Catenda access required:_ Write access You can drag and drop files from your system onto a destination in the Webpart in order to upload these files to Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/11-upload-file.png)

> **Note:** If you drag and drop a folder it will be published as a zip file. If you wish to upload a folder structure you will have to download it from SharePoint and upload it to Catenda either via the [zip upload](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) or [Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector).

### 4.3 **Reload**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/12-reload.png)

If someone else has made changes in the Catenda project, it could be that you do not see them yet. In that case it can be a good idea to reload the webpart to get the most up-to-date information.

### 4.4 Publish to SharePoint

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/13-publish-to-sharepoint.png)

Publish your selected documents from Catenda to SharePoint Clicking this button will open the publish to SharePoint dialogue:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/14-publish-to-sharepoint.png)

Towards the top of the dialogue you will see how many elements you are publishing.

**New location** Choose 'New location' if you wish to publish the selected files to a new location within SharePoint.

**Show existing targets** If the files were already published before and you want to update previously published files, you should choose 'Show existing targets'.

**Publish** After configuring the location you want to publish to, click publish.

## 5. **Catenda access**

### 5.1 **No access to the Catenda project**

If you do not have access to the configured project you will see the following error.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/15-no-access-to-the-catenda-project.png)

The blurred part is the project GUID. If there are none, or you do not have access to any documents in the project it will say "No Content - folder is empty".

### 5.2 **No access to creating folders**

If you do not have write access to the folder you are in and try to create a new subfolder you will see this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/16-no-access-to-creating-folders.png)

### 5.3 **No access to uploading files**

If you do not have write access to the folder or document and try to upload a file you will see this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/17-no-access-to-uploading-files.png)
