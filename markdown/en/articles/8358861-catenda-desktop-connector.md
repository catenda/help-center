# Catenda Desktop Connector

> **Note:** The installation file for this application can be found [here](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)

With the Catenda desktop connector you can schedule up- and downloads of the latest versions of documents.

## 1. **Instant up/downloads**

### 1.1 **Upload**

Select a folder on a local system to upload all folder content, including files within subfolders of the selected folder, with the Desktop Connector to a specified folder on Catenda Hub.

**Successful uploads** If you drag-and-drop multiple files or use the zip-upload feature on Catenda Hub you are uploading one big set of data. The larger the upload the longer you have to wait before you can submit your files into the Catenda Hub document structure.

**One file at a time** By uploading files from a folder structure one file at a time the Desktop Connector you can pause the upload and continue it later.

**Lower the risk for upload failures** The larger the upload the higher the risk that it fails as well. Maybe your power goes out, maybe your internet connection breaks for a split second. Then you would have to start the upload all over again.

### 1.2 **Download**

Select either one or more single documents or select a folder on Catenda Hub to download the selection, including documents within subfolders of selected folders to a location on your local machine.

### 1.3 **Transfer speed**

Both up- and downloading files with the Desktop connector is faster at file transfer than the regular upload process as the files are imported via the API without requiring the overhead of a running a browser or other browser limitations. For transferring a single file a drag or drop with a browser is recommended because of its ease of use, but for transferring large amounts of data in one go or for those who wish to save time during uploads of large single files the Desktop Connector is the recommended way for transferring.

### 1.4 **Access**

Access control that is configured on Catenda Hub is maintained. Users can upload to locations in the Catenda Document structure where they have at least write access and can only download documents they have at least read access to.

## 2. **Synchronization**

Files can be scheduled to be up- or downloaded at regular intervals.

### 2.1 **Local system -> Catenda Hub**

The Desktop Connector can ensure that files in a Catenda Hub project are kept current with the latest save state of a file on the local system.

### 2.2 **Catenda Hub -> Local system**

The Desktop Connector can ensure that files on a local system are kept current with the latest revision of a document in a Catenda Hub project.

## 3. **Installation**

When the Catenda Desktop Connector is installed on Windows its installation files will appear in the following folder.

`C:\Program Files\Catenda Hub Desktop Connector`

### 3.1 **Uninstalling**

To uninstll the plugin go to the following Windows menu:

`Windows settings -> Apps -> Installed apps`

Find Desktop Connector in the list and click on the action menu on the right hand side to uninstall.

## 4. **Sign in**

When the Desktop Connector is first opened a sign in request is displayed. Click on the Sign-in button to open the default browser on the system on the Catenda Sign-in page. After logging in or if already logged in click on allow access to grant access to Catenda account that is logged in. After clicking on allow access the browser will prompt the user to open the Desktop Connector application. Giving permisison to opening the application redirects back to the Desktop Connector [home page](#home-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/01-sign-in.png)

## 5. **Home page**

This is wht the Desktop Connector can look like when it is started up with a valid login:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/02-home-page.png)

### 5.1 **Wake up PC**

Wake up the PC from sleep mode if a task is scheduled to run at that time.

### 5.2 **Run on startup**

To run the desktop connector on startup, select this option

### 5.3 **Log out**

Click on the log out button on the bottom right to log out.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/03-log-out.png)

## 6. **Project list**

An overview of the projects that the account had access to the last time the projects list was loaded in is displayed. For each project the number of up- and download tasks that are configured are shown.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/04-project-list.png)

### 6.1 **Synchronize button**

If a project was recently joined, click click this synchronize button to load in the new list of projects that the logged-in account is part of.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/05-synchronize-button.png)

### 6.2 **Name**

Click on the name of a project to see the current up- and download tasks or to schedule a new task.

### 6.3 **Upload tasks**

The amount of uplaod tasks that are active for this project

### 6.4 **Download tasks**

The amount of download tasks that are active for this project

## 7. **Upload task**

Schedule a periodic uplaod of files from your system to Catenda Hub with this task.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/06-upload-task.png)

### 7.1 **Title - Required**

The upload task has to at least have a title to be saved

### 7.2 **Schedule calendar - Required**

The task has to at least have one day selected to be saved

### 7.3 **Project location**

**Server** Click on browse to select the destination on the Documents page in Catenda Hub  where files should be synchronized to. Click [here](#server-location) to read more about selecting the server directory path

**Local** Select the location on the local system from where files should be sychronizes.

### 7.4 **Instant**

Tasks do not have to be saved to start the upload process. Click on the upload now square to start this task immediately. Saved taks run periodically at the configured time.

## 8. **Download task**

Schedule a periodic download of files from Catenda Hub to the local system.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/07-download-task.png)

### 8.1 **Title - Required**

The upload task has to at least have a title to be saved

### 8.2 **Schedule calendar - Required**

The task has to at least have one day selected to be saved

### 8.3 **Project location**

**Server** Select the location on Catenda Hub from where documents should be downloaded. Click [here](#server-location) to read more about selecting the server directory path

**Local** Select the destination on the local system where files should be downloaded to.

### 8.4 **Instant**

A task does nto have to be saved to start downloading. Click on the Download now square to start this task immediately. Save the task to periodically run the download at the configured time. The downloaded documents will end up on your system unzipped.

### 8.5 Back button

Click on the arrow button to go back to the [home page](#home-page)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 9. **Server location**

Click on browse in the project location are of an upload or download task to start browsing the directory path of the Catenda project. The Choose directory path dialogue will open up. Once opened it will start downloading all folder names in the project and their heirarchy. For download tasks document names are downloaded as well. While the downloading is onging the dialogue can look like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/09-server-location.png)

Especially for download tasks, if there are many folders and documents it can take a couple of minutes for this process to finish. Please make sure enough memory is available on the local system for this step.

**Dialogue size** Click on Min or Max towards the top right to minimize or maximize the Choose directory path dialogue.

**Directory actions** After the folders have loaded in the dialogue can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/10-server-location.png)

Click on the arrow next to a folder to expand it. Documents are only available in this view for download tasks.

**Folder select** Click on a folder to select it. For download tasks multiple folders can be selected while for upload tasks only one folder can be selected at a time.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/11-server-location.png)

After a folder is selected it appears as whilte with a checkmark. Any subfolders to the selected folder will appear struck through as it is only possible to select folders at the same level. Towards the top the amount of selected items are displayed.

**Download task** If there are documents in the selected folder or its subfolders all folders in the path between the selected folder and the document will be created. The document is then downloaded to that folder. If a subfolder does not contain and documents the subfolder will not be created even though it may be checked in this dialogue. It is not possible to uncheck a subfolder to not download part of a folder structure. To only download some folders, select them individually like in the image below:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/12-server-location.png)

Document select Click on a document to select it

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/13-server-location.png)

When individual documents are selected the documents will be downloaded as a flat list directly to the selected local path without the hierarchy of the folders those documents are in.

**Upload task** Documents are uploaded to the selected folder. If the folder name matches documents are uploaded to subfolders of the selected folder.

## 10. **Task List**

Here the up- and download tasks that are configured in this installation for the logged-in user can be seen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/14-task-list.png)

### 10.1 **Name**

The name of the task.

### 10.2 **Task**

The scheduled time of that the task will run.

### 10.3 **Project**

The name of the project where this task will run.

### 10.4 **Status**

The status of this task.

### 10.5 **Back button**

Click this button to go back to the [home page](#home-page)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 11. **Log Folder**

This button opens the folder location of the Desktop Connector logs on the local system. The default location of these logs is:

`C:\Users\<Windows account name>\AppData\Local\User Name\2b92d867-496c-47d1-ac42-fbf8fa355177\Cache\BimsyncApp`
