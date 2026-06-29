# Columns on the documents page

In the [documents table](https://support.catenda.com/en/articles/8204673-documents-page#h_54e8dfcac2) on the [documents page](https://support.catenda.com/en/articles/8204673-documents-page) you will be able to see several columns in the header row which can be rearrange and turned on/off with the [column dropdown](https://support.catenda.com/en/articles/8204673-documents-page#h_9022dce579).

## 1. **Column order**

Drag the header row of the column out of the documents table to hide it. The column can be enabled again with the column dropdown. Doubleclick on the divider between two header rows to fit with of the row to the left to its content.

There is a default column order if you only have one panel open as well as a default column order if you have multiple panels open. Changing the column order in either the single panel view or the multi-panel view will change the preferred column order for you across all your different projects.

## 2. **Checkbox** - Default 1 panel

Select the checkbox on the top row to select all documents in this folder. You can also select documents one by one by selecting the checkbox on the left side. See [here](https://support.catenda.com/en/articles/8204673-documents-page#h_61be2cfecf) for more selection options.

## 3. **Icon column** - Default 1 panel, Default multipanel

The icon column is always on.

### 3.1 **Click interaction**

Click on the icon of a document to open a preview window of the document. This is especially useful for images as you will be able to flip throught he images that are currently in your list.

### 3.2 **Document icons**

For most documents the filetype icon will be displayed. For image filetypes the image will be displayed instead. Depending on the configuration of the document you might see badges appear in the corners of the icon. A configured document can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/42c02fpr/01-document-icons.png)

**Model badge** Documents that are linked to a model on the models page will show a models badge on the bottom left.

**Folder configuration** If the parent folder of the document has been configured in [document settings](https://support.catenda.com/en/articles/7831371-document-settings) you will see a gray gear badge on the bottom right of the document icon.

### 3.3 **Folder icons**

Depending on the configuration of the folder you might see badges appear in the corners of the icon. A configured folder can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/42c02fpr/02-folder-icons.png)

**Element count** If there are no elements in a folder (subfolders or documents) it will be white.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/42c02fpr/03-folder-icons.png)

If there are elements in a folder (subfolders or documents) it will be green. On the bottom right you will see the amount of elements that are in this folder.

**Folder cofiguration** If a folder has been configured in document settings you will see a green gear badge on the bottom right. If a parent folder of a folder has been configured the gear icon will be gray instead.

## 4. **Name** - Default 1 panel, Default multipanel

The name of the document as it is seen in the documents section. Click on the letters of the name to enter the latest revision of the document or see the content of the folder.

> **Note:** The document name can be different from the revision or model name.

### 4.1 **Changing the document name**

If you have selected a document or a folder, you will be able to change the name by clicking on the pencil next to the document name in the [right information menu](https://support.catenda.com/en/articles/8345396-right-menu-on-the-documents-page). _Access required:_ Full access to the document or write access to the folder

### 4.2 **Row anchor**

If you hover over the name column you will see that a grid of dots appears to the right of the document name.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/42c02fpr/04-row-anchor.png)

If you mouse over this you will see you cursor change to a hand. If you drag this grid icon you will be able to move your selected files/folders to another folder.

## 5. **Revision** - Default 1 panel

The amount of public and/or draft revisions in the document Each revisions can have their own revision name, creation date, file size, and owner.

### 5.1 **Revision name**

The name of the latest public document revision. This is the name of the file that was originally uploaded and cannot be changed. As there can be multiple revisions in a document this name can be different from the document name which is the gather name for all the revisions in the document.

> **Note:** The revision name can be different from the document or model name.

## 6. Model name

If the document is linked to a model you will see the name of the model here. This model name is meant to be an easily understandable name so people know what model they are opening.

> **Note:** The model name can be different from the document or revision name.

## 7. **Status** - Default 1 panel - Document statuses only

Document statuses can be turned on in [document settings](https://support.catenda.com/en/articles/7831371-document-settings). If the status workflow has been enabled, document revisions might have been assigned a status. Separate lists of statuses can be applied depending on if the revision is published or a draft. In this column can see the status of the latest published revision in the document.

## 8. **Size** - Default 1 panel

The file size of the latest published revision in the document

## 9. **Labels** - Default 1 panel

Any labels applied to the document or folder will be listed here. These labels can also be applied from the models section if a model is linked to the document.

## 10. **Document Created**

The member that created the document and the date and time it was created. When a model is created in the models section a document without revisions is created in the documents section and linked to it. The creation date is therefore separate from the publishing date.

## 11. **Revision created** - Default 1 panel

In this column you will see the member that created the latest document revision and the date and time it was created. When a model is created on the models page a document without revisions is created on the documents page and linked to it. At this point the revision cretation date is still blank as there are no revisions yet. As soon as a revision is uploaded to the document the revision date will be displayed. The revision creation date can therefore be separate from the document creation date.

### 11.1 **Document status workflow**

If you have activated the document status workflow the behavior of this column will be different depending on which of the tabs you are in.

**Workspace tab** In the workspace tab you will see the member that created the latest revision and the date and time it was created.

**Published tab** In the published tab you will see the member that published the latest published revision and the date and time it was published.

> **Note:** The latest published revision is not neccessarily the latest revision in the document as shared revisions may have been uploaded since the last published revision.

## 12. **Links** - Default 1 panel, Default multipanel

Shows the amount of objects that are [linked to this document](https://support.catenda.com/en/articles/4670322-how-can-i-link-a-document-to-an-object-in-catenda-hub) If you click on this you will be able to do the following:

- Select objects
- Isolate objects
- Load objects as query

## 13. **Viewer** - Default 1 panel

For IFC documents that have been linked to models, Point Clouds and GML documents you will see a 2D, 3D and zoom to extents button in this column. These buttons can be used to open the [2D view](https://support.catenda.com/en/articles/4854537-2d-viewer) or [3D view](https://support.catenda.com/en/articles/8227211-3d-viewer) of a document-model from the document structure. For 3D multiple document-models can be selected and the 3D action can be used to open them all in one go. The center button will let you center on this model if it is loaded in 3D. This is what an ifc document that is connected to a model can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/42c02fpr/05-viewer-default-1-panel.png)

## 14. **Custom fields**

One column per custom field that is added to the configured parent folder see [document settings](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90)
