# Sharepoint Library

> This article describes how to set up a connection to Sharepoint

To create a SharePoint library, click on the [new library button](https://support.catenda.com/en/articles/8065645-libraries-page#h_c6d56f227c) on the top right of the [libraries page](https://support.catenda.com/en/articles/8065645-libraries-page). This library can be used to share documents from a users SharePoint with the other members of the Catenda project. When the SharePoint library is activated it can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/01-intro.png)

Click [here](https://support.catenda.com/en/articles/9800091-sharepoint-library-short-video) to see a short video about how to configure the SharePoint library.

After giving the library a name you a new tab will open up in your browser where you will be asked to log in with your SharePoint account. After logging in, you will be taken to the Library settings page of your SharePoint library where you can configure SharePoint folder you would like to show on Catenda.

## 1. **Header -** Library name

On the left of the header you will see the name of the current library. If the library is synchronized you will see a checkmark next to the name. When you synchronize the library will stay synchronized for 3 months. After that you might see an exclamation mark here with a tooltip that says failed to synch. When this happens, please got to library settings and grant access once more.

## 2. **Header** - Library settings

On the right of the header you will be able to see an action menu that can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/02-header-library-settings.png)

In the library settings you will be able to configure your SharePoint library. _Access required:_ Library creator

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/03-header-library-settings.png)

### 2.1 **Connection**

If you have connected your account you can click on Revoke access to revoke the access you have given Catenda to your SharePoint account. If you have not given access you will be able to click on Grant access here to go through the access process to give Catenda access to your account.

### 2.2 **Details**

Click on the pencil icon to change the name of this library.

### 2.3 **Shared folder**

Open this menu and click on edit to choose a shared folder from one of your SharePoint Sites that you wish to be displayed in this SharePoint library.

> **Note:** For a folder to show up in this list it has to be set to public in SharePoint

### 2.4 **Access control**

Here you can determine who is allowed to access this library in your project.

### 2.5 **Delete**

Open this menu and click on delete to remove this SharePoint library from your Catenda Project

## 3. **Header - Library settings -** New library

Click the New library button to create a new library

## 4. **Filter menu**

### 4.1 **Saved filters**

Click [here](https://support.catenda.com/en/articles/8551755-saving-filters) to read more about how to save a set of filters

### 4.2 **Unlinked -** `link=unlinked`

With this filter you will be able to filter for all documents that are not linked to objects.

### 4.3 **Linked to selected objects -** `link=backlink`

If you have selected any objects in the 3D viewer that are connected to SharePoint documents you will be able to filter for them here.

## 5. **SharePoint document list**

Here you will be able to navigate all the documents and folder within the shared folder that is configured for this library.

### 5.1 **Actions**

After selecting one or more document(s) or folder(s) you will be able to see the following action menu appear towards the top of the documents list. The existing item actions menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/04-actions.png)

**Link/unlink** If you select an object from a model in 3D you will be able to link/unlink it to your selected elements.

**Preview** Open up a preview of the document without having to load the documents page. This can be especially useful in a folder with many images. Only visible when a single document is selected

**Download** Click on download to download your selected document. Only visible when a single document is selected

### 5.2 **Name**

Click the name of a folder to see its contents Click the name of a document to view its contents

### 5.3 **Url**

Click on the download button in this column to download the document.

### 5.4 **Links**

If any objects have been linked to your documents you will be able to see the amount of linked objects here. Clicking on this number will let you:

**Select objects**

**Isolate objects**

**Load as query**

## 6. **Right information menu**

When you first open select a document in the document list, its right menu might be closed. You can click on the information button on the bottom right of the [document banner](https://support.catenda.com/en/articles/8461918-document-banner-actions-navigation) to expand this menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/05-right-information-menu.png)

### 6.1 **Linked objects**

Here you will be able to link objects to your SharePoint documents.

### 6.2 **Topics**

After opening up a document you will be able to see the topics menu. Here you will be able to attach your SharePoint documents to topics.

## 7. **Permissions**

When documents are uploaded from a SharePoint document-library to Catenda the sharepoint rest-api is used (via the [pnpjs](https://pnp.github.io/pnpjs/) library). Since these permissions are granted to spfx-solutions OOTB no additional grant needs to be made. The following grants will be needed for the app to access the Catenda backend. Only delegated permissions are used with the following scopes: _[User.Read](https://graphpermissions.merill.net/permission/User.Read) [offline\_access](https://graphpermissions.merill.net/permission/offline_access) [Files.Read](https://graphpermissions.merill.net/permission/Files.Read)_ _[Sites.Read.All](https://graphpermissions.merill.net/permission/Sites.Read.All)_ The access above is only used to approve the sharing of documents to the users Catenda project.
