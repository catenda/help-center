# Right menu in a topic

The right menu in a topic can be found by clicking the information button to the right in the [topic banner](https://support.catenda.com/en/articles/7986346-topic-banner-navigating-topics) towards the top of the page after having opened a topic.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/01-intro.png)

In the right menu of a topic information about the related items in a topic can be found. This is what the right menu might look like when all menus are retracted:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/02-intro.png)

## 1. **Related documents**

This is what the expanded related documents menu can look like before any documents have been added

![Documents Add No related documents](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/03-related-documents.png)

The number to the right of the related documents menu header displays the amount of library items that are currently linked to the topic. That means it is not just the amount of documents but the amount of folders (without contents), documents and url links combined. This is what the related documents menu can look like after items from all possible libraries have been added:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/04-related-documents.png)

In the expanded menu linked documents are separated by each type of library. For each library the linked library items are displayed.

### 1.1 **Add related documents**

Navigate a library and click on link to the right of the document or folder to link it to the topic. Added documents will be sorted alphabetically.

> **Note:** Documents added from other libraries than the document library are not exportable and will therefore not be visible in our plugins/integrations and BCF/Excel and PDF exports

### 1.2 **Edit related documents**

After related documents have been linked the edit button appears to the right of the header in the related documents menu. This is what the related documents menu can look like when editing the links:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/05-edit-related-documents.png)

Click on unlink next to the document, folder or link to unlink it from the topic. While edtiting it is still possible to click Link to undo the unlinking. Remember to click Done towards the top after making change to submit the changes. After clicking done documents have to be added again to be linked back to the topic.

### 1.3 Related folders and documents

For the Documents, SharePoint and Dropbox libaries folders and documents can be linked. Click on the name of a folder to open the documents tabel on that folder in the library structure. Click on the icon of a document to open a preview of that document in a preview dialogue box on top of the topic without having to go to the document page of that document. Click on the name of a document to open the document preview page of the latest published revision of that document.

> **Note:** The only way to specify which revision should be previewed is by making a markup on that revision and saving it to the comment of the topic. when a markup from a topic is played the revision that that markup is on is loaded instead of the latest published revision.

When the browser is zoomed all the way out the most information about library items can be seen in this menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/06-related-folders-and-documents.png)

For folders the name of the folder is displayed along with any labels attached to the folder. For documents the following is displayed:

- Document path in the document library.
- Document name
Hover over each name to see a preview of the whole document / path name.
- Revision number
- Revision status of the latest revision in the document
- Labels applied to the document
- Size of the latest revision
- Creator of the latest revision
- Amount of 3D objects linked to the related document
    - Click on the object amount to open the 3D object action menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/07-related-folders-and-documents.png)

**Select objects** Use the select objects action to load the models belonging to the linked objects in the 3D viewer and select the linked objects.

**Isolate objects** Use the isolate objects action to load the models belonging to the linked objects in the 3D viewer and isolate the linked objects.

**Load as query** Use the load as query action to load only the linked objects in the 3D viewer without the other objects from their models.

### 1.4 **Documents library buttons**

For the documents library there is a download all documents icon to the right of the library header.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/08-documents-library-buttons.png)

With this button all latest published revisions of documents that are set as related to the topic from the documents library are downloaded. Note that the title of the downloaded file can be different from the document name depending on the organization that the project belongs to. By default the title is set to the revision name and not the document name. Documents from other libraries are not downloaded with this button.

### 1.5 **SharePoint and Dropbox libraries buttons**

For documents in the SharePoint and Dropbox libraries a download button is displayed that lets members download the document to their machine.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/09-sharepoint-and-dropbox-libraries-buttons.png)

> **Note:** The download button is only visible when the browser zoom scale is zoomed far enough out.

### 1.6 **Links library buttons**

Folders the Links library or urls can be linked.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/10-links-library-buttons.png)

Click on the name of a link to open the link in the links library. Click on the open in new tab icon to open the link in a new tab.

> **Note:** The open in new tab button is only visible when the browser zoom scale is zoomed far enough out.

## 2. **Related objects**

If you have objects selected when making an topic they will automatically be related to the topic. Expand this menu to see the objects that are related to the topic.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/11-related-objects.png)

The number on the right will display how many objects are currently related to the topic.

### 2.1 **Green selection box**

This box shows the amount of objects currently selected in 3D Clicking Link or unlink in this box will overwrite the objects that are related to this topic with the current selection.

### 2.2 **Grey object box**

Click on the grey object box to select the object in the topic and in 3D. See what objects are selected by which ones are highlighted in grey.

### 2.3 **Linking and unlinking one object at a time**

To link/unlink one object at a time objects can either be select/deselected in 3D or the `+` or `x` next to the selected object in the list below can be clicked. The grey object field will include the following: Object name - Type name (Entity component)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/12-linking-and-unlinking-one-object-at-a-time.png)

## 3. **Related topics**

Expand this menu to see what topics are related to the topic If a topic is linked by writing `#[1234]` in a description or comment the topic will be added to the list of related topics of both the current topic and to the list of the topic that is linked. This makes it easy to navigate back and forward between topics. Often users will make a "master topic" where they link all topics belonging to a task. All topics in this task will then have the master topic as a related topic.

The number on the right will display how many topics that are currently related to the topic.

You can click anywhere on the topic to be taken to the respective topic. Click on the topic number to copy a link to that topic . Click on the three dots in the tags to see the rest of the tags.

### 3.1 **Edit**

Click on edit to add/remove related topics to the related topics list of this topic. You will not be able to click on an topic to go to the topic in edit mode.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/7pvzrk75/13-br-edit.png)

Either all topics can be selected by clicking on the box on top or the desired ones can be selected by clicking on their respective boxes. After selecting topics they can be removed from relations with the remove relations button. Remember that the topic will only be removed as a relation from the current topic. The topic that was related will most likely still have the current topic as a relation. If a relation is removed this can instantly be seen by others. As long as the page is loaded the last removal can still be undone.
