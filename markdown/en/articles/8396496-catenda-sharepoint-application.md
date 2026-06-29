# Catenda SharePoint Application

> **Note:** The install file for the plugin can be found in [this article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

If the Catenda SharePoint Application is added to a SharePoint site, files can be published from SharePoint to Catenda and the Catenda document structure can be viewed in SharePoint. When configured, the application can look as follows: <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/inline-628ad1424b68.png" width="300"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/inline-910393724d2c.png" width="300"/>
This article contains information about how this application works
See [here](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq) for more information about how this application can be useful.
See [here](https://support.catenda.com/en/articles/9453368-adding-and-removing-the-catendasp-app) for how to add the SharePoint application to a site.

## 1. **Publishing to Catenda with the list command**

With the list command it is possible to publish one or more files to Catenda.

> **Note:** It is only possible to publish files. Folder structures can be downloaded from SharePoint and uploaded to Catenda via [zip upload](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) or [Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector).

### 1.1 **Finding the list command**

**One file** If you want to publish a single file to Catenda, the easiest way to do so is by clicking on Publish to Catenda in the hamburger menu of the file.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/01-finding-the-list-command.png)

**Multiple files** If you wish to publish multiple files to Catenda you will have to select the files you wish to publish. After your files in SharePoint, users will be able to see a Publish to Catenda list command.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/02-finding-the-list-command.png)

If there is not enough space in the command bar you might see the command in the hamburger menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/03-finding-the-list-command.png)

> **Note:** Files can only be published from list view as the list command is not available in grid view.

### 1.2 **Publishing the file**

After clicking on Publish to Catenda the following menu will open that can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/04-publishing-the-file.png)

If you have not given SharePoint access to your Catenda account you will be asked to authorize it. [See below](#h_788fe15988) for how to authorize your account.

**Selecting a folder** If you have granted access to your Catenda account you can select the project, library and the destination folder on Catenda, and publish.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/05-publishing-the-file.png)

The view of the folder structure in SharePoint is consistent with the view in Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/06-publishing-the-file.png)

If a document with the same name as your file does not exist yet in the folder you are publishing, it will appear as a new document in Catenda. If the file you are publishing has the same name as a document in the folder you are publishing it to, the file will be a new revision to that document.

> **Note:** It is only possible to publish documents and not upload drafts

After a file is published, users will be able to move, rename and delete the file. _Catenda Access required:_ Full access, usually given to users like the publisher or an administrator Changing the file on Catenda does not change anything on SharePoint. Likewise, if the file changes on SharePoint, nothing changes on Catenda.

## 2. **Catenda Webpart**

With this application you add [the Catenda webpart](https://support.catenda.com/en/articles/10538168-catenda-sharepoint-application-webpart) to a page on your sit. You can let users browse the areas that they have read access to in the document section of a Catenda project. If the have write access to any part of the document structure they will also be able to upload files there.

This is what a configured webpart can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/07-catenda-webpart.png)

## 3. **Authorizing your Catenda Account**

If you navigate to a SharePoint page where the Catenda Webpart has been activated or you attempt to use the publish action and you have not yet validated your account you will get the folowing popup:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/08-authorizing-your-catenda-account.png)

_Access required:_ API access when installing application If a new browser tab does not open automatically, please copy the link from the open account validation tab and navigate there yourself. If you are not already logged in, you will be asked to log into Catenda in this window. If you do not already have one, you can create a Catenda Account [here](https://hub.catenda.com/signup).

> **Note:** The email address connected to the Catenda account you sign in with has to be the same as the address connected to the SharePoint account you are signed in with.

The authentication window can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/09-authorizing-your-catenda-account.png)

By allowing the app access to your account you will be able to publish documents from SharePoint to any part of your Catenda project(s) that you have write access to in the [document section](https://support.catenda.com/en/articles/8204673-documents-page). If a webpart has been added to a page on your site you will also be able to see all documents you have read access to in the Catenda project that was configured by the person that added the webpart. With the webpart you will also be able to publish documents from your system to any part of the configured Catenda project that you have write access to in the [document section](https://support.catenda.com/en/articles/8204673-documents-page).

> **Note:** Catenda will not have access to your SharePoint documents. If you publish a document to Catenda, Catenda receives it in a one way transaction.

If you no longer wish to give the app access to your Catenda account, you can always revoke the access on the [applications page](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) of your Catenda account.
