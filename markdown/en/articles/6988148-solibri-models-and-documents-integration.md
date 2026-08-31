# Solibri Models and Documents Integration

The Documents API integration offers an easy way to access your cloud-stored content. You can connect to a common data environment (CDE), and download and upload models from/to the server.

## 1. **Connecting**

The Documents API can be found in the integrations menu of the file tab in Solibri. To get started with the documents API you first need to give Solibri access to your Catenda account. To do so, click on Connect.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/01-connecting.png)

The list of servers you can connect to will now start loading in.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/02-connecting.png)

The first time you start up Solibri this list can take some time to load. After the first load the list is stored and will be faster to open up. In the resulting dropdown menu you can select Catenda or Bimsync to connect to the Catenda documents API.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/03-connecting.png)

## 2. **Importing documents or models**

Click on Open to import documents or models that you have access to in Catenda Hub.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/04-importing-documents-or-models.png)

After clicking on open, your default browser will open up.

- [Cancel your browser session](#h_e921d649ed) if you wish to cancel this process and keep working with Solibri
- If you have not done so already, [grant access to your account](#h_55ca1d4d10).
- If you have not yet selected a project, select a project on the [projects page](#h_343870704c).
- After selecting a project, or if you have previously selected a project, you can select the [documents page](#h_b7ac757915) (_default_) or the [models page](#h_617a3f8bf6).

## 3. **Exporting Solibri session to Catenda**

For the Upload model button to become available you have to have [connected your Catenda account](#h_457cbf4e9d) and have at least one file in your Solibri session. Click on Upload model to export your Solibri session a part of your Catenda project that you have access to.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/05-exporting-solibri-session-to-catenda.png)

If you have not yet saved your Solibri session, or made any changes since your last save, you will be asked to save an .smc file so it can be uploaded.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/06-exporting-solibri-session-to-catenda.png)

The .smc that has been saved can now be exported as a new revision to Catenda and later imported again to Solibri if you wish to continue your session with the latest revision. After having saved your .smc file click on upload model again.

After clicking on Upload Model, your default browser will open up.

- [Cancel your browser session](#h_e921d649ed) if you wish to cancel this process and keep working with Solibri
- If you have not done so already, [grant access to your account](#h_55ca1d4d10).
- If you have not yet selected a project, select a project on the [projects page](#h_343870704c).
- After selecting a project, or if you have previously selected a project, you will be presented with the [documents page](#h_b7ac757915).

## 4. **Solibri document integration -** Projects page

After clicking on open and signing in, if you just allowed access or have previously granted access, a page similar to the projects page of Catenda Hub will open up as a new page in your default browser. The Solibri document integration projects page can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/07-solibri-document-integration-projects-page.png)

> **Note:** This page is created by Solibri and is not the same as the regular projects page in Catenda Hub. Only the models and documents sections of Catenda can be navigated to. Catenda Hub functinality like document preview and access configuration does not work here.

## 5. **Solibri document integration -** documents page

See the documents you have access to with you catenda account on the documents page of the Solibri document integration. Here you can configure which documents will be synchronised with Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/08-solibri-document-integration-documents-page.png)

### 5.1 **Navigation**

Click on the name of the project if you wish to navigate to a different project. Click on models in the left menu to import by model instead of by document.

> **Note:** The models page is only available when downloading.

### 5.2 **Document structure**

For each document you will see:

- Filtype icon
- Document name
- Revision number
- Document status
- Labels (click on the 3 dots to see more labels)
- Filesize
- Latest revision creator
- Latest reivision publishing date
- 3D button (Preview model before importing)
- Object links (Select linked objects in 3D preview by clicking this number)

Select a set of documents by checking the boxes or check the box on top to select all.

### 5.3 **Right information menu**

After selecting the information menu will appear on the top right. If it is closed, click on the `i` icon to expand it.

### 5.4 ​**Right information menu -** Download

When importing you can configure which documents will be imported to Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/09-right-information-menu-download.png)

Click on download towards the bottom to import the latest shared revision of each selected document.

### 5.5 **Right information menu -** Upload

When exporting you can configure the .smc file that will be uploaded.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/10-right-information-menu-upload.png)

**Update document name** With this option on, the name of the selected document will be updated to the name you have given to your file.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/11-right-information-menu-upload.png)

This way you can make sure you can keep uploading revisions to a document while making sure it always has the same name as those revisions.

**Automatically select similar documents** With this option on you will be able to upload your file to a document with a similar name, even if it is not exactly the same. Note that the uploaded revision will still have the filename that you have specified.

**Filename** Here you will see the name of the file that will be uploaded to Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/12-right-information-menu-upload.png)

By default the name of the smc file you have saved on your system will be displayed. The name can still be changed at this moment. Configure the name of the file by clickin on the pencil to the right.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/13-right-information-menu-upload.png)

**Document** Here you will see the name of the document on Catenda that will receive the file.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/14-right-information-menu-upload.png)

By default it will have the same name as the filename. If there is no document with that name in your current folder yet this field will be green, indicating that a new document will be created. The name that your document will have can sitll be changed at this moment. If there are other .smc documents in this folder you will be able to click on the document name to select any of the other documents that you would like your .smc file to be uploaded to as a revision. If you have chosen a document or if there is a document in the current folder with the same name this field will be gray. You will then see a message warning you that a document with this name already exists and that your smc file will be uploaded as a new revision to that document.

**Status** If the status workflow has been enabled for your project you will see the status dropdown.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/15-right-information-menu-upload.png)

If you are creating a new document, or if your document does not have a status yet you will see no status. If you are adding a revision to an exisiting document you will see the status of that document and will be able to change the document status upon upload. If you wish to change the status of the document when your revision is uploaded you can select it from the list of available statuses in the project.

### 5.6 **Documents received**

When the download has started successfully you will see the following message in the browser

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/16-documents-received.png)

If you go back to Solibri you will see that the documents have started processing. Downloaded documents will be stored in a temporary folder while your Solibri session is active. Remember to save your Solibri session or upload a new revision on Catenda if you wish to save any changes made in your file. Uploaded document revisions will be stored on Catenda. The latest revision can later be opened in Solibri again.

## 6. **Solibri document integration -** Models page

See the models you have access to with you catenda account on the models page of the Solibri document integration. Here you can configure which models will be synchronised with Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/17-solibri-document-integration-models-page.png)

Click on the name of the project if you wish to navigate to a different project. For each model you will see the:

- Model name
- Revision numner
- IFC type
- Latest revision creation date
- Latest revision creator

Select a set of models by checking the boxes or check the box on top to select all. After selecting the information menu will appear on the top right. If it is closed, click on the `i` icon to expand it. Here you can edit your selection of models to be imported to Solibri. Click on download towards the bottom to import the latest shared revision of each selected model.

## 7. **Cancel browser session**

While your browser session is active you will see the following message in Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/18-cancel-browser-session.png)

Press cancel if you wish to end the import process.

## 8. **Granting access to your Catenda account**

If you are not yet logged into Catenda, you will be asked to [sign in](https://support.catenda.com/en/articles/7891486-sign-in-page). After opening for the first time, after signing in or if you were already signed in, you will be asked for permission to access your Catenda account:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/19-granting-access-to-your-catenda-account.png)

If you were already signed in, but not with the right account, you can click on your profile picture to sign out and sign into the right account. When you are sure you are signed into the right account, click Allow access to continue. If you wait to long to do this it will not work so be sure to have your password ready! After successfully granting access to your account you will see the following message:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/20-granting-access-to-your-catenda-account.png)

## 9. **Managing linked documents**

Documents that have been linked from Catenda in Solibri can look different from regular documents that have been opened from the local system. This is what documents can look like when they have been linked with documents on Catenda:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/21-managing-linked-documents.png)

### 9.1 **Name column**

The name of the model might take some time to update but will eventually change to reflect the amount of revisions in the document on Catenda. If your organization has set a preference for the download name of your document you might find a different name here. For example the document name without the revision option is possible to request. Note that this has to be requested by the organization for all downloaded files in their projects. You can see the different download name options for orgainzations [here](https://support.catenda.com/en/articles/8224886-organization-options).

### 9.2 **Version column**

The Version column will help you keep track of which revision is currently loaded. If revision publishing has been activated on your Catenda project you might see  major (1.0, 2.0, 3.0, etc...) and minor (1.1, 1.2, 2.1, etc...) revision numbers here.

### 9.3 **Link column**

After a model has been imported from Catenda Hub a chainlink icon will be displayed in the third column to show that it is linked.

### 9.4 **Model hover**

If you hover over a document that has been linked from Catenda you will see `[Documents API] Catenda` followed by the name of the document.

### 9.5 **Context menu -** Updates

Right click a document to open the context menu. Here the document update preferences can be configured.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/22-context-menu-updates.png)

**Update Models** This is what the update models dialogue can look like if you have selected multiple documents.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/23-context-menu-updates.png)

Folder - Click on the folder if you wish to choose a local file for this model instead.

Version - Here you will see the version number in Catenda along with a checkmark which shows if you are currently working with the latest revision or not. Update - Check the update box for each model or for all models by checking the box at the top and click on update models to update them.

Settings - Click on settings to open the model update settings for your selected documents.

Relink Models - Relink models only works if you have selected local models in this dialogue and not with Catenda models.

**Model update settings**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/24-context-menu-updates.png)

Automatic - When a new revision is available in Catenda Hub the model will automatically update.

Prompt - A promt will be shown when a new revision is available on Catenda. Updating to the new revision will start at your convenience.

Relink Models - Relink models only works if you have selected local models in this dialogue and not with Catenda models.

### 9.6 **Context menu -** Hyperlinks

Towards the bottom of the document context menu you will see hyperlinks.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/25-context-menu-hyperlinks.png)

For each of the selected document that has a link to Catenda, you will see "Catenda" when you open each of the hyperlinks menus.. This is what the expanded hyperlinks meny can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/26-context-menu-hyperlinks.png)

New Hyperlink - Clicking on New Hyperlink opens the Add Hyperlink meny which can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/27-context-menu-hyperlinks.png)

Show Click "Catenda" to open that linked document on Catenda.

Edit Click "Catenda" to edit the link for that selected document. The Edit Hyperlink menu will now open up and can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/28-context-menu-hyperlinks.png)

The address should look something like this: [https://hub.catenda.com/project/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx/revisions/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx](https://hub.catenda.com/project/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx/revisions/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)

The topic will be Catenda by default, but can be renamed to anything you want.

Catenda links are always Absolute meaning that they are not relative to where your .smc file is on your system.

Remove Click "Catenda" to remove the link for that selected document.
