# Catenda Desktop connector

> **Note:** The installation file for this application can be found [here](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)

With the Catenda desktop connector you can schedule up- and downloads of the latest versions of documents.

This article contains information about the following:

## 1. **Instant up/downloads**

The Desktop Connector lets you upload files from your local system to a specified folder on Catenda Hub. You can also select a number of folders on Catenda Hub to download to a location on your local machine.

**Uploading speed**

Uploading files with the Desktop connector is faster at file transfer than the regular upload process as the files are imported via the API instead of via the browser. It is therefore the best way to upload your files if you are uploading a large amount of data at once.

### 1.1 **Successful uploads**

If you drag-and-drop multiple files or use the zip-upload feature on Catenda Hub you are uploading one big set of data. The larger the upload the longer you have to wait before you can submit your files into the Catenda Hub document structure.

**One file at a time**

By uploading files from a folder structure one file at a time the Desktop Connector you can pause the upload jon and continue it later.

**Lower the risk for upload failures**

The larger the upload the higher the risk that it fails as well. Maybe your power goes out, maybe your internet connection breaks for a split second. Then you would have to start the upload all over again.

## 2. **Synchronization**

You can schedule when your files are uploaded or downloaded at regular intervals.

### 2.1 **Local system -> Catenda Hub**

The desktop connector will make sure that either the file on your local system are up-to-date with your Catenda Hub project.

### 2.2 **Catenda Hub -> Local system**

It can also work the other way where the connector ensures you always have the latest version of your Catenda Hub documents on your local system.

## 3. **Installation**

When the Catenda Desktop Connector is installed on Windows its installation files will appear in the following folder.

`C:\\Program Files\\Catenda Hub Desktop Connector`

### 3.1 **Uninstalling**

To uninstll the plugin go to the following Windows menu:

`Windows settings -> Apps -> Installed apps`

Find Desktop Connector in the list and click on the action menu on the right hand side to uninstall.

## 4. **Sign in**

When you first open the Desktop connector you will be asked to sign in. If you click on the sign in button your default browser will open with a page that asks you to log in to your Catenda Hub account. After logging in or if you were already logged in you will be asked to grant access to your Catenda account. After clicking on allow access you will be asked to open the desktop connector app. You will then be redirected back to the Desktop Connector [home page](#h_097078145d).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/01-sign-in.png)

## 5. **Home page**

When you start up the Desktop connector it will look like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/02-home-page.png)

### 5.1 **Wake up PC**

Wake up the PC from sleep mode if a task is scheduled to run at that time.

### 5.2 **Run on startup**

To run the desktop connector on startup, select this option

### 5.3 **Log out**

Click on the log out button on the bottom right to log out.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/03-log-out.png)

## 6. **Project list**

Here you see an overview of your projects and the number of up- and download tasks you have set for each project.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/04-project-list.png)

### 6.1 **Synchronize button**

If you have recently joined a new project you can click this synchronize button to load in the new list of projects you are part of.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/05-synchronize-button.png)

### 6.2 **Name**

Click on the name of a project to see your current up- and download tasks or to schedule a new task.

### 6.3 **Upload tasks**

The amount of uplaod tasks that are active for this project

### 6.4 **Download tasks**

The amount of download tasks that are active for this project

## 7. **Upload task**

With this task you can schedule a periodic upload of files from your system to Catenda Hub

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/06-upload-task.png)

### 7.1 **Title - Required**

The upload task has to at least have a title to be saved

### 7.2 **Schedule calendar - Required**

The task has to at least have one day selected to be saved

### 7.3 **Project location**

**Server**

Select the location on Catenda Hub you want to synchronize your files to.

**Local**

Select the location on your system you want to sychronize the files from.

### 7.4 **Instant**

Click on the upload now square to start this task immediately. You do not have to save the task to start uploading. If you save the task it will run periodically at the configured time.

## 8. **Download task**

With this task you can schedule a periodic download of files from Catenda Hub to your system.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/07-download-task.png)

### 8.1 **Title - Required**

The upload task has to at least have a title to be saved

### 8.2 **Schedule calendar - Required**

The task has to at least have one day selected to be saved​

### 8.3 **Project location**

**Server**

Select the location on Catenda Hub you want to download your files from.

**Local**

Select the location on your system you want to download the files to.

### 8.4 **Instant**

Click on the upload now square to start this task immediately. You do not have to save the task to start uploading. If you save the task it will run periodically at the configured time. The downloaded documents will end up on your system unzipped.

### 8.5 Back button

Click this button to go back to the [home page](#h_097078145d)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 9. **Task List**

Here you can see your current up- and download tasks

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/09-task-list.png)

### 9.1 **Name**

The name of the task.

### 9.2 **Task**

The scheduled time of that the task will run.

### 9.3 **Project**

The name of the project where this task will run.

### 9.4 **Status**

The status of this task.

### 9.5 **Back button**

Click this button to go back to the [home page](#h_097078145d)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 10. **Log Folder**

This button opens the folder location of the Desktop Connector logs on your system. The default location of these logs is: C:\\Users\\\<Windows account name>\\AppData\\Local\\User Name\\2b92d867-496c-47d1-ac42-fbf8fa355177\\Cache\\BimsyncApp
