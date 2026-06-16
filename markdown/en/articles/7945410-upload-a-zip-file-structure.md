# Upload a zip / file structure

Compared to uploading a regular zip file, the upload a zip function will unpack a zip. This way you can import a file structure into the [documents page](https://support.catenda.com/en/articles/8204673-documents-page#h_28610e1d21) without having to manually make folders.

The following topics will be described in this article:

**[Selecting file](#h_1b8fb565da) - [Configuration](#h_95dd1ed2a4) - [Uploading](#h_054e595cce) - [Extracting](#h_eacf59e68f) - [Size limit](#h_e43a342de9) - [My uploads](#h_90dab69441)**

The Upload zip function can be found in the action menu to the right of the green + button on the top right of the documents page.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/01-intro.png)

### 

## **Selecting a zip file**

After clicking the Upload zip menu item, the following dialogue will open up:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/02-selecting-a-zip-file.png)

your system file browser of your system should open automatically.

If the file browser did not open up or if it was closed without selecting a zip file, you can open it back up by clicking on the Select zip file button.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/03-selecting-a-zip-file.png)

After successfully selecting a zip file on your local system you should see the name of the zip file as below and the upload zip button will be highlighted in deep green.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/04-selecting-a-zip-file.png)

If you did not enter a folder in the document section, it will say that the contents will be extracted to the Root folder. This means that you will see the contents right when you enter the documents section. It is also possible to navigate to a folder in Catenda and upload your zip there if you want the file structure to appear there.

## **Upload configuration**

Settings can be configured for elements with names in the zip file already exist at the location the zip extraction attempts to place them in the Catenda project.

### **Folders**

New folders will only be created if a folder with that name does not exist at the location that the zip is trying to extract a folder to yet.

Any elements within folder where a folder with that same name already exists will be placed in the existing folder with that same name in the Catenda project.

### **Documents**

Different behaviors can be configured for how the extraction of the zip file behaves when a document with the same name as the file in the zip file already exists at the same location as where the zip file is trying to extact it to in the Catenda project.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/05-documents.png)

**Create new revision - Default**

If a document with the same name exists in the same location as the zip attempts to extract a file to, a new revision will be created in that document.

**Skip and continue**

If a document with the same name exists in the same location as the zip attempts to extract a file to, the file will be skipped and no new revision will be created in the document.

### **Apply status**

If the status workflow has been enabled in your project, you will be able to configure what the status of new documents will be.

If you chose the create new revision option, the status of documents that receive new revision will automatically be changed.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/06-apply-status.png)

It is only possible to choose between shared revision statuses.

After upload the shared revisions can be found in the workspace tab and can later be published.

## **Uploading**

After clicking on upload zip your zip will start uploading

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/07-uploading.png)

You can continue working with Catenda on another tab while you wait for the upload to finish.

**Access required:**

Write access to each of the locations where folders and documents will be created

Write access to documents revisions will be added to.

## **Extracting**

After your zip has uploaded Catenda will start extracting your zip.

During the extraction, you will see the following menu on the bottom left:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/08-extracting.png)

You can keep this menu open while browsing Catenda, or close it if you want.

You could even close the browser completely during the extaction process.

The zip will continue extracting in the background.

If you used Catenda in a different tab while the zip is extracting, you will see the folders, documents and revisions start to appear in the location you extracted to by refreshing the page.

### **Extraction completed**

When the zip is done extracting it will say completed in the dialogue.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/09-extraction-completed.png)

Click on view details to see which files were extracted.

You will later be able to find these details in "My zip uploads" as explained below.

Refresh the page to see all the files that have been uploaded.

### **Zip import completed notification**

If you have closed the dialogue, the browser or refreshed the page, you will no longer see the dialogue.

You will also get a notification that you zip extraction has completed.

This way you will know when your zip upload is completed, even if you no longer see the extraction dialogue.

## **Bypassing the file size limit**

Uploading a zip will let you upload files that are larger than 7gb as the zip compresses the file.

## **My zip uploads**

The option under the zip upload in the action menu will let you see an overview of your previous zip uploads.

This is what zip imports with the different possible statuses can look like:

### **Extracting**

While the zip is extracting the extracted files start to appear as rows in the documents table.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/10-extracting.png)

**Completed**

When the zip import has completed all files are extracted.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/11-extracting.png)

### **Zip import page**

Click on a zip import to see more information about the import process.

This is what the zip import page of a completed zip import can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/12-zip-import-page.png)

This is what right menu of the zip import page of a completed zip import can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/13-zip-import-page.png)

## **Desktop connector**

With the [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) you can automatically, periodically, upload the latest versions of documents from your local system to Catenda Hub.

The Desktop Connector is both faster at doing so than the regular upload process and minimizes the risk of failure as it uploads documents file-by-file instead of in one big drag and drop or zip upload batch.
