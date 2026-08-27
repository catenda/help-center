# Changelog 4 Catenda - January 2024

> New information and minor changes

Hello everyone,

it has been a nice couple of months since the last changelog. Hopefully you have all had a nice winter vacation! 🎄🤶🧑‍🎄❄️ And welcome to 2024!🎇 Hopefully we will be able to make many changes and improvements this year as well! In this article you will find updates about the following: [Articles](https://support.catenda.com/en/articles/7983534-changelog-3-catenda-update-october-2023#h_5be2a02999) - [topics resolved](https://support.catenda.com/en/articles/7983534-changelog-3-catenda-update-october-2023#h_d238d9111d) - [New releases](https://support.catenda.com/en/articles/7983534-changelog-3-catenda-update-october-2023#h_d238d9111d)

## 1. **Articles**

As new features roll out and bugs are fixed articles are updated with the changes that are made. Please find the following articles that have been made and changed since the last changelog.

### 1.1 **New articles:**

**Getting started and FAQ** [Sorting order of lists](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) [Structuring documents](https://support.catenda.com/en/articles/8542598-structuring-documents)

**Main page** [Organizations page](https://support.catenda.com/en/articles/8442343-organizations-page)

**Topics** [Topic history](https://support.catenda.com/en/articles/8613038-issue-history)

**Documents** [Documents](https://support.catenda.com/en/articles/8461918-documents) [PDF Compare](https://support.catenda.com/en/articles/8461650-pdf-compare) [Filtering on the approvals page](https://support.catenda.com/en/articles/8551740-filtering-on-the-approvals-page)

**Models and 3D** [Bookmark](https://support.catenda.com/en/articles/8471481-bookmark)

**Project settings** [Creating a custom field](https://support.catenda.com/en/articles/8445575-creating-a-custom-field) [Custom field page](https://support.catenda.com/en/articles/8445588-custom-field-page)

### 1.2 **Articles that have changed:**

Getting started and FAQ [Saving filters](https://support.catenda.com/en/articles/8551755-saving-filters)

Topics [Topic boards ACL](https://support.catenda.com/en/articles/4670296-issue-boards-acl)

Documents [Documents page](https://support.catenda.com/en/articles/8204673-documents-page) [Models as documents](https://support.catenda.com/en/articles/8064548-models-as-documents) [Filtering on the documents page](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page)

Models [Bookmarks page](https://support.catenda.com/en/articles/4670281-bookmarks-page) [Creating a new bookmark](https://support.catenda.com/en/articles/4670269-creating-a-new-bookmark) [Models as documents](https://support.catenda.com/en/articles/8064548-models-as-documents)

Libraries <a class="intercom-content-link" href="" target="_blank">Links library</a>

Settings [Members page](https://support.catenda.com/en/articles/4670291-members-page)

## 2. **Bugs Resolved**

Thanks to your valuable feedback we have been able to squash many topics that you may or may not have noticed existed. Below is a list of smaller changes that have been made by the development team as a result of conversations with users.

### 2.1 **Topics**

- Dropdown custom fields with up to 10 values that are required can now also be filtered.
- PDF exports of topics now no longer show certain pictures twice.
- Custom fields filters are now displayed even if the custom field is set as required.
- Images attached to topic comments after 16. November will now show up in the same order that they are in the topic comments in the preview dialogue.
- The time of export in the PDF export now says UTC behind it so the user might know what timezone the timestamp was in.
- Models that are deleted in the timeframe between the preparation and the enabling of a models as documents migration will now properly be deleted upon migration.

### 2.2 **Documents**

- Lithuanian letters in documents imported from ZIP imports will now no longer be garbled as a result of zip poisoning.
- Text bubbles can once again be placed for users with MFA enforcement.
- Highlight annotations from pdfs files are now properly displayed in the pdf viewer after they are uploaded.
- PDFs can once again be saved as with annotations and comments.
- Documents that were not loading for users with MFA enforcement are now loading again.

### 2.3 **Models**

- The delete model button is visible once again.
- There is now no way models can be hidden anymore if models as documents was enabled without migrating the project.
- The model import completed email notification now says import completed on \<model> instead of new revision in model for clarity.
- It is now only possible to select pdf documents in the storey configurator where pdf.
- It is no longer possible to add non-pdf documents to the storey configurator. (which only accepts PDFs anyway)

## 3. **User voices completed**

### 3.1 **Topics**

- You now get a notification when a team you are part of is mentioned in a topic
- If you click on view marker on 2D in the location of a topic your 2D viewer will now center on that marker instead of just showing the marker as selected on the right floor.
- The width of the model select dialogue in the comment of a topic now scales with the width of a model name. Previously long model names were cut off and had to be moused over to be seen.
- It is now possible to see what a description looked like before it was changed by clicking on the description changed box in topic history.
- Images are no longer show up twice in pdf exports of older topics

### 3.2 **Documents**

- Document ACL is now reflected in the models section for projects that have models as documents enabled
- You can now see how many documents are in a collection.
- It is now possible to snap to mid and endpoints of lines in PDF drawings.
- It is now possible to preview .odt and .ods file formats.

### 3.3 **Models**

- It is now possible to set the ACL per model instead of for all models.

    This means that you can hide models from people in the models section.

- With models as documents you can add labels to models.
- With models as documents you can structure models in folders in the documents section.
- With models as documents you can see the file size of the model
- With models as documents you can use the naming convention feature with models
- It is once again possible to see previous revisions of models in the revision selector

### 3.4 **Project settings**

- Label groups can now be deleted.
- It is now possible to delete labels that are connected to topics/documents.
- Label groups can be edited.
You can find the edit pencil in the right information menu after having selected the label group in the groups tab.
- It now is possible to make multiple labels at a time.
Note the import multiple button in the new label menu.
- It is now possible to delete multiple labels at a time.
- Labels can be filtered and filters can be saved.
- It is now possible to add new label groups
- It is possible to add label groups without adding them to a label first.
- It is now possible to search on the labels page.
- Administrators will now be able to merge labels. The option can be found by selecting more than one label on the labels page.

### 3.5 **General**

- Making new projects from template projects has been improved. It is now possible to bring the following parts of a project to a new project:
    - Folder structure
    - Document status configuration
    - Document and topic board access control
    - Custom fields and naming conventions

## 4. **New releases** - Catenda Site, Plugins and integrations

**Catenda Hub:**

- Models as documents has now been fully released.
- Issues have been renamed to Topics.

_Catenda Site:_ [App store](https://apps.apple.com/us/app/catenda-site/id1449579790) [Play store](https://play.google.com/store/apps/details?id=no.catenda.bimsyncmobile)

**New version 3.3.1**

- Bug fixes

**New version 3.3.0**

- _Deep linking_ -  URLs from the Hub website will open content directly in the Site app.
- _Topic filtering_ - New option for filtering by milestone.
- _User mentioning_ - Quickly find and select a user for mentioning in topics from the toolbar.
- _Text markup_ - Easily apply rich text to your topics from the toolbar.
- _Center 2D Marker_ - Opening a marker from a topic will center the view on the marker location.
- Vietnamese language support. 🇻🇳

**New version 3.4.0**

- Issues have been renamed to topics
- Bug fixes

**Sharepoint Integration:**

- You can now connect to your catenda account via a browser popup instead of waiting for an email.
