# Changelog 6 Catenda - August, 2024

Hello everyone,

I hope you have all had a great summer vacation and are ready for the second half of 2024 As Catenda changes so will the articles! As it can be hard to keep track of all the small changes over time, here you will be able to find an overview over all the latest changes. ☀️😎🏖️

## 1. **Articles**

As new features roll out and bugs are fixed articles are updated with the changes that are made. Please find the following articles that have been made and changed since the last changelog.

### 1.1 **New articles:**

**Getting started and FAQ** [Catenda SharePoint FAQ](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq) [Revisions in namingconvention](https://support.catenda.com/en/articles/9496151-revisions-in-namingconvention) [Custom fields on documents](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) [Taking over for another member](https://support.catenda.com/en/articles/9520447-taking-over-for-another-member)

**Models** [Actions on the models page](https://support.catenda.com/en/articles/9431936-actions-on-the-models-page) [Right menu on the models page](https://support.catenda.com/en/articles/9673735-right-menu-on-the-models-page) [Actions on the model overview page](https://support.catenda.com/en/articles/9674157-actions-on-the-model-overview-page)

**Topics** [Boards page](https://support.catenda.com/en/articles/9413644-boards-page) [Actions in a topic board](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board)

**Documents** [Actions in a document](https://support.catenda.com/en/articles/9323521-actions-in-a-document)

**Plugins and integrations** [Microsoft Teams notifications](https://support.catenda.com/en/articles/9167392-microsoft-teams-notifications) [Enabling the Catenda SharePoint app](https://support.catenda.com/en/articles/9419749-enabling-the-catenda-sharepoint-app) [Adding and removing the CatendaSP app](https://support.catenda.com/en/articles/9453368-adding-and-removing-the-catendasp-app) [Navisworks Changelog - 1.4.0](https://support.catenda.com/en/articles/9440035-navisworks-changelog-1-4-0)

### 1.2 **Articles that have changed:**

**Frequently asked Questions** [Previewing file types on Catenda Hub](https://support.catenda.com/en/articles/4670320-previewing-file-types-on-catenda-hub) [No access pages](https://support.catenda.com/en/articles/9172624-no-access-pages)

**Main page** [Projects page - Organization tool](https://support.catenda.com/en/articles/8505058-projects-page-organization-tool) [Users page - Organization tool ](https://support.catenda.com/en/articles/8508311-users-page-organization-tool) [Project memberships - Organization tool](https://support.catenda.com/en/articles/9003642-project-memberships-organization-tool) [Multi Factor Authentication](https://support.catenda.com/en/articles/4969891-multi-factor-authentication)

**Models** [Models page](https://support.catenda.com/en/articles/4670286-models-page) [Model overview page](https://support.catenda.com/en/articles/4670270-model-overview-page)

**Topics** [Right menu in a topic](https://support.catenda.com/en/articles/8053299-right-menu-in-a-topic) [Table view in a topic board](https://support.catenda.com/en/articles/6941099-table-view-in-an-topic-board) [List view in a topic board](https://support.catenda.com/en/articles/6941232-list-view-in-a-topic-board) [Topics page](https://support.catenda.com/en/articles/4670271-topics-page)

**Documents** [Upload a zip / file structure](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) [Actions in the document structure](https://support.catenda.com/en/articles/4670288-actions-in-the-document-structure) [Documents page](https://support.catenda.com/en/articles/8204673-documents-page) [Documents banner - Navigation](https://support.catenda.com/en/articles/8461918-document-banner-navigation) [Right menu in a document](https://support.catenda.com/en/articles/8302244-right-menu-in-a-document) [QR-Codes on PDFs in Catenda](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda) [Document settings](https://support.catenda.com/en/articles/7831371-document-settings) [Right menu on the documents page](https://support.catenda.com/en/articles/8345396-right-menu-on-the-documents-page)

**​**

**Settings** [Custom field page](https://support.catenda.com/en/articles/8445588-custom-field-page) [Custom fields page](https://support.catenda.com/en/articles/6550459-custom-fields-page)

**Plugins and integrations** [Catenda Sharepoint Application](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application) [IFC Export Archicad Manual](https://support.catenda.com/en/articles/4670338-ifc-export-archicad-manual)

**Catenda Site** [Previewing documents on Catenda Site](https://support.catenda.com/en/articles/8975421-previewing-documents-on-catenda-site)

## 2. **Bugs Resolved**

Thanks to your valuable feedback we have been able to squash many topics that you may or may not have noticed existed. Below is a list of smaller changes that have been made by the development team as a result of conversations with users.

### 2.1 **Documents**

- Measurement annotations in pdf documents that get uploaded no longer cause all other annotations to disappear.
- It is once again possible to download previous revisions from the right information menu
- If a document would fail to upload, this would cause a gap in the database causing problems for publishing approvals. It is now also possible to publish approvals with documents where a document failed to upload.
- It is once again possible to see published revisions in approvals

### 2.2 **Models**

- System tree - Groups that are related to other groups will now load faster and will no longer also show up as their own group at the root level of the systems tree.
- It is once again possible to see model revisions on the revision overview page of a model in pre- models as documents projects.
- It is once again possible to change the transformation angle of a model and see it after a reload of the page
- The initial transformation value when creating a model has been corrected
- Rotation transformation has is now xyz as it is supposed to be, instead of xyy
- A y coordinate transformation is no longer applied when adding rotation to a model.

    If you now apply a transformation with rotation, reload the page and load the model again it will appear at the right place.

- 4D functionality is working once more.

## 3. **User voices completed**

### 3.1 **Topics**

- It is now possible to add a logo to the project settings page. This logo will show up towards the top right of every topic page in the PDF export.

### 3.2 **Documents**

- It is now possible to add custom fields to folders. Custom fields can be set as default making all documents uploaded to the folder(and its subfolders) get the default value.

## 4. **New releases** - Catenda Site, Plugins and integrations

_Catenda Site v3.4.2:_ [App store](https://apps.apple.com/us/app/catenda-site/id1449579790) [Play store](https://play.google.com/store/apps/details?id=no.catenda.bimsyncmobile)

**Desktop Connector:** [Catenda Desktop Connector v1.0.5.0](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector)

Navisworks: [Navisworks plugin v1.4.0](https://support.catenda.com/en/articles/5085987-catenda-hub-navisworks-plugin)
