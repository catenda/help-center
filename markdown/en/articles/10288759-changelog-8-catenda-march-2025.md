# Changelog 8 Catenda - March, 2025

Hello everyone, Hopefully you have all been able to survive the cold winter months. The sun has thankfully started shining more and more and we are getting ready for spring! Since the last changelog you have been using Catenda more than ever before. This has let us focus on makeing sure everything runs smoothly, even when people from all over the world are active with their projects at the same time! Many pages in Catenda are now faster to open than before. Some even 10-100 times faster! Many of you are still letting us know that you notice hiccups in some situations and we are now also monitoring this more than before to ensure you have the best experience possible. If you notice anything taking longer than expected, please let us know what page you noticed this on, and when you noticed this so we can help you. 🚅📈✈️🌍

In this article you will find updates about the following:

_[Articles](https://support.catenda.com/en/articles/9285880-changelog-6-catenda-august-2024#h_a8cc7b1921) - [Bugs resolved](https://support.catenda.com/en/articles/9285880-changelog-6-catenda-august-2024#h_58dfb1b852) - [New releases](https://support.catenda.com/en/articles/9285880-changelog-6-catenda-august-2024#h_25203946b2)_

## 1. **Articles**

As new features roll out and bugs are fixed articles are updated with the changes that are made. Please find the following articles that have been made and changed since the last changelog.

### 1.1 **New articles:**

**Getting started and FAQ** [Organization tool FAQ](https://support.catenda.com/en/articles/10475849-organization-tool-faq)

**Topics** [Topic board access control](https://support.catenda.com/en/articles/4670296-topic-board-access-control) [Topic board settings](https://support.catenda.com/en/articles/4670277-topic-board-settings)

**Plugins and integrations** [Catenda SharePoint Application - WebPart](https://support.catenda.com/en/articles/10538168-catenda-sharepoint-application-webpart) [Catenda as an application](https://support.catenda.com/en/articles/10695677-catenda-as-an-application) [Add to home screen](https://support.catenda.com/en/articles/10741601-add-to-home-screen) [Home screen system-browser support](https://Home-screen%20system-browser%20support)

### 1.2 **Articles that have changed:**

**Getting started** [Getting started on Catenda Hub](https://support.catenda.com/en/articles/9030303-getting-started-on-catenda-hub) [Snapshots](https://support.catenda.com/en/articles/10345863-snapshots) [Hardware recommendation](https://support.catenda.com/en/articles/6921941-hardware-recommendation) [Notification filtering and functionality](https://support.catenda.com/en/articles/8304417-notification-filtering-and-functionality) [Accepting an invitation to join a project](https://support.catenda.com/en/articles/4670246-accepting-an-invitation-to-join-a-project) [Creating an account](https://support.catenda.com/en/articles/8412895-creating-an-account)

**Frequently asked Questions** [Is there a size limit for IFC files?](https://support.catenda.com/en/articles/4670324-is-there-a-size-limit-for-ifc-files)

**Main page** [Users page - Organization tool](https://support.catenda.com/en/articles/8508311-users-page-organization-tool) [Support bubble location and functionality](https://Support%20button%20location%20and%20functionality)

**Topics** [List view in a topic board](https://support.catenda.com/en/articles/6941232-list-view-in-a-topic-board) [Table view in a topic board](https://support.catenda.com/en/articles/6941099-table-view-in-an-topic-board) [Topic body - The content of a topic](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic)

**Documents** [Actions in a document](https://support.catenda.com/en/articles/9323521-actions-in-a-document) [QR-Codes on PDFs in Catenda](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda)

**Plugins and integrations** [Catenda Plugins and Integrations](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations) [Catenda SharePoint Application](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application)

## 2. **Bugs Resolved**

Thanks to your valuable feedback we have been able to squash many topics that you may or may not have noticed existed. Below is a list of smaller changes that have been made by the development team as a result of conversations with users.

### 2.1 **Documents**

- Documents over 1GB can now be uploaded again without error
- Fixed a problem where document revisions that were created at exactly the same time caused no documents to be shown. Documents are now loaded in a map instead of one by one which drastically lowers loading times. This makes it so the page is both quick to load and so our servers can better handle all your requests during when many people are using Catenda at the same time.
- Point Clouds can once again be imported and will process correctly
- It is once again possible to click on objects that are linked to documents in the right information menu to select them in the 3D viewer.
- If the last viewed time on the public link of a collection has a different millisecond you will now no longer get an error.
- Special characters will no longer be garbled when a document is downloaded from Safari on Mac.
- Text annotations that contain full-width characters placed on documents that are then downloaded will no longer be scale disproportionally compared to single width characters.
- Image documents larger than 10000x5000 pixels will now properly generate a document preview.

### 2.2 **Models**

- Colors applied to mesh objects are now properly displayed. Models will have to be re-imported to see the difference.
- A complete redesign of our model management system - we now load model information only when needed, instead of loading everything upfront. This makes it so the page is both quick to load and so our servers can better handle all your requests during when many people are using Catenda at the same time.
- It is once again possible to see properties in previsous revisions of models in the inspect panel
- You will no longer see models you do not have access to in the revisions selector.
This way models used for tenders can be kept anonymous by use of access control.
- It is once again possible (and a better experience than previously) to measure between points in point clouds.

### 2.3 **Topics**

- The all topics board is no longer showing the filters of the previous board you were on and once again correctly shows the fliters belonging to the all topics board.
- Topic export improvements:
    - Topics exports that take a long time will now time out.
    - Up to 10000 images can now be included in a PDF export.

### 2.4 **Project settings**

- Members - The members page is now much faster to load.

## 3. **New releases** - Catenda Site, Plugins and integrations

_Catenda Site v3.5.2:_ [App store](https://apps.apple.com/us/app/catenda-site/id1449579790) [Play store](https://play.google.com/store/apps/details?id=no.catenda.bimsyncmobile) It is no longer possible to see the content of topics that were deleted on Catenda Hub. If you had loaded in markers in the 2D viewer, these will still be visible. Attempting to open a deleted topic via topic list or marker will no longer show the content of the topic and will unload the marker from the 2D viewer.
