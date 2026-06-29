# Catenda Desktop Connector FAQ

## 1. Online-only files

Many document management systems allow you to view a shadow version of your files on your system that do not take up any space. You can often tell when a document is online-only by an archived or cloud-like or badge. Here are some examples of what an online only document can look like in different services:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/swkm9e7y/01-online-only-files.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/swkm9e7y/02-online-only-files.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/swkm9e7y/03-online-only-files.png)

Dropbox Google Drive Microsoft 365/SharePoint

When the Desktop Connector attempts to upload a document like this it will attempt to access it. If you have the respective service running this will be recognized and will start downloading the document to your local system. Therefore be sure you have enough space on your machine, also when uploading! The Desktop Connector is able to tell if there have been changes to the document, even if it is online-only and will only download the file for upload to Catenda if it has been changed. After the upload task has been performed, all files that have been downloaded on your system will be taking up space. Many of these synchronization services will regularly free up space if the document has not been used after some time. If you want this to happen right away the document or the folder can be right clicked and changed back to online-only in the right-click menu.
