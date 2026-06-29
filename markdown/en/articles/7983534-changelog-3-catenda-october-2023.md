# Changelog 3 Catenda - October, 2023

> New information and minor changes

Hello everyone,

it has been a nice couple of months since the last changelog. Many of you have been on vacation and so have we! 🏖️ Although capacity may have been reduced during the summer months we have still had time to make some changes and improvements.

## 1. **Articles**

As new features roll out and bugs are fixed articles are updated with the changes that are made. Please find the following articles that have been made and changed since the last changelog.

### 1.1 **New articles:**

**Getting started and FAQ** [Project Security](https://support.catenda.com/en/articles/8263256-project-security') [Tracking information by linking](https://support.catenda.com/en/articles/8294909-tracking-information-by-linking) [Why am I not receiving emails?](https://support.catenda.com/en/articles/8417802-why-am-i-not-receiving-emails) [Formatting of posts](https://support.catenda.com/en/articles/8430847-formatting-of-posts)

**Main page** [Organization options](https://support.catenda.com/en/articles/8224886-organization-options) [Dashboard page](https://support.catenda.com/en/articles/8212646-dashboard-page) [Notification settings](https://support.catenda.com/en/articles/8272435-notification-settings) [Notification functionality](https://support.catenda.com/en/articles/8304417-notification-functionality) [Create an account](https://support.catenda.com/en/articles/8412895-creating-an-account)

**Issues** [Issue content](https://support.catenda.com/en/articles/7986346-issue-content) [Issue right panel](https://support.catenda.com/en/articles/8053299-issue-right-panel) [Issue body](https://support.catenda.com/en/articles/8053352-issue-body) [Filtering in an issue board](https://support.catenda.com/en/articles/8370693-filtering-in-an-issue-board)

**Documents** [Giving a user access to a single folder](https://support.catenda.com/en/articles/8009637-giving-a-user-access-to-a-single-folder) [Libraries page](https://support.catenda.com/en/articles/8065645-libraries-page) [Upload a zip / file structure](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) [Right panel in a document](https://support.catenda.com/en/articles/8302244-documents-right-panel) [Right panel in documents list](https://support.catenda.com/en/articles/8345396-right-panel-in-documents-list) [Approvals page](https://support.catenda.com/en/articles/8349340-approvals-page) [Approval content](https://support.catenda.com/en/articles/8349418-approval-content) [Table view in the documents section](https://support.catenda.com/en/articles/8398771-table-view-in-the-documents-section)

**Models and 3D** [Selecting and clipping from 2D](https://support.catenda.com/en/articles/8035360-selecting-and-clipping-from-2d) [3D viewer](https://support.catenda.com/en/articles/8227211-3d-viewer) [Models as documents](https://support.catenda.com/en/articles/8064548-models-as-documents) [Information panel](https://support.catenda.com/en/articles/8238584-information-panel) [3D location of models](https://support.catenda.com/en/articles/8294750-3d-location-of-models) [Model configuration](https://support.catenda.com/en/articles/8300623-model-configuration) [Measure plane](https://support.catenda.com/en/articles/8360838-measure-plane)

**Project settings** [Member page](https://support.catenda.com/en/articles/8228836-member-page)

**Plugins and integrations** [Integration Power BI](https://support.catenda.com/en/articles/5784721-integration-power-bi) [Catenda SharePoint Plugin](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-plugin) [Catenda Access from your environment](https://support.catenda.com/en/articles/8396532-catenda-access-from-your-environment)

### 1.2 **Articles that have changed:**

Getting started and FAQ [User Voice @ Catenda](https://support.catenda.com/en/articles/5925449-user-voice-catenda) [Summary of most important shortcuts and basic controls](https://support.catenda.com/en/articles/4670267-summary-of-most-important-shortcuts-and-basic-controls)

Main page [Notifications page](https://support.catenda.com/en/articles/7439223-notifications-page)

Issues [Right panel in an issue board](https://support.catenda.com/en/articles/6941224-right-panel-in-an-issue-board) [Issue boards settings](https://support.catenda.com/en/articles/4670277-issue-board-settings) [Issue board settings](https://support.catenda.com/en/articles/4670277-issue-board-settings)

Documents [Documents page](https://support.catenda.com/en/articles/8204673-documents-page) [Filtering on the documents page](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page)

Models [2D Viewer](https://support.catenda.com/en/articles/4854537-2d-viewer)

Notifications [Latest project notifications](https://support.catenda.com/en/articles/4670262-project-notification-settings)

## 2. **Issues Resolved**

Thanks to your valuable feedback we have been able to squash many issues that you may or may not have noticed existed. Below is a list of smaller changes that have been made by the development team as a result of conversations with users.

### 2.1 **Issues**

- The following columns in the excel export have gotten a new name in Japanese:
「にて作成された」→「作成者・質問者」
「作成済み」→「作成日・質問日」
- The setting for shown or hidden filters in issue boards is now remembered in your account instead of in your browser so you do not have to change it if your browser gets reset often.
- The issue board once again updates after an issue has been moved
- BCF issues that are imported with status " " will now default to get the first open status
- If you change your bcf to zip, unzip and rezip it and change it back to bcf you can now upload it to Catenda Hub
- Issue export UI is improved and remembers which option you have selected
- Approvals that were published while annotation snapshots were still being generated now properly generate the full issue with all approval comments.
- Closed issues are now properly exported with selected issue export.
- If more than 100 issues are selected the selected issues export now exports the proper amount of issues
- Issues with more than 32 767 characters in the last comment or description can now also be exported to excel.
- It is once again possible to use the sharelink feature to share only the selected issues.
- BCF files with NULL in the title now import correctly.
- It is now possible to filter on custom field values instead of just "has value" and "no value"

### 2.2 **Documents**

- Point clouds that do not have rgb will now automatically show the intensity setting. (previously the setting was not set and the Point cloud looked black)
- Regular users will once again be able to change document statuses in document settings if they get access to this through the access option in document settings
- Project owners can delete Dropbox and Sharepoint libraries now.
- If the document and revision download name option is enabled in a project, this download option will now also apply for single files and not just multiple.
- With the new documents table view it is now possible to change the status of multiple documents at a time.
- PDFs with comments will now show their comments upon import.
- PDFs with comments both from importing and the ones made in Catenda Hub can be downloaded with comments by clicking on the hamburger menu top right and clicking "save as"
- PDFs can be compared with the new PDF compare feature. You will find this feature in PDF documents with multiple revisions on the top right next the the revision dropdown.

### 2.3 **Models**

- Bookmark stars are now yellow again
- Measurements once again snap to object clipping plane intersections
- Pipes and ducts bullseyes are no longer displaced
- It is once again possible to make new bookmarks public and private
- Objects that are part of both groups and systems will now show up in both groups AND systems instead of just the most specific type of group
- It is once again possible to see selections when you play a snapshot or a bookmark.
- Viewer movement no longer gets stuck in motion if you press the windows key while moving.
- If you select objects from the object tree, change models in the tree, select objects from this model, and switch back your objects will now properly be highlighted.
- The storey configurator is once again only visible to administrators.

### 2.4 **General**

- Lithuanian language is now available.

    <div class="intercom-container"><img alt=":flag-lt:" src="https://raw.githubusercontent.com/catenda/help-center/main/images/1zszs46s/inline-ae369a463875.png" width="22"/></div>

## 3. **New releases** - Catenda Site, Plugins and integrations

_Catenda Site:_ [App store](https://apps.apple.com/us/app/catenda-site/id1449579790) [Play store](https://play.google.com/store/apps/details?id=no.catenda.bimsyncmobile) New version 3.2.0

- Issues list thumbnails: Viewpoint snapshots are displayed on the list of issues.
- Access Control List for issue closing: Permission to close issues is based on project setting.
- View linked documents and issues on models: Access linked documents and issues when inspecting objects in the 3D viewer.

New version 3.2.1

- Lithuanian language support

New version 3.2.2

- Japanese language support

_Desktop connector:_ [New version 1.0.4.0](https://hub.catenda.com/share/collections/oLhaVZ2CpCmyD87bTjNlLxmM3AQOQMrWIuZqndALKpcj)

- Now works better with naming conventions

**SharePoint plugin:** [Catenda SharePoint 1.0.0.0](https://appsource.microsoft.com/en-us/product/office/WA200005981?tab=Overview)

- New release
