# Documents page

The documents page can be found as the fourth item in the left navigation menu in a project. This page is part of the content panel. In the document management system you will be able to upload files and configure who has access to them.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/nzhpbg4s/01-intro.png)

## 1. **New item actions**

The new item actions can be found on the top right of the page. See [here](https://support.catenda.com/en/articles/4670288-actions-in-the-document-structure) for what the different actions do.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/nzhpbg4s/02-new-item-actions.png)

## 2. **Search or filter options**

See [here](https://support.catenda.com/en/articles/4670283-search-and-filter-option) to find out how best to search or filter in the documents section

![](https://raw.githubusercontent.com/catenda/help-center/main/images/nzhpbg4s/03-search-or-filter-options.png)

## 3. **Right menu**

If any document rows are selected in the documents table, an info button will appear to the right of the search or filter bar. The info button can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/nzhpbg4s/04-right-menu.png)

In the right menu you will be able to see information about:

- Document information
- Revision information
- Access control
- Open approvals
- Revisions
- History
- Collections
- Linked objects
- Topics

Click [here](https://support.catenda.com/en/articles/8345396-right-panel-on-the-documents-page) to read more about the right menu.

## 4. **Documents table**

The documents table can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/nzhpbg4s/05-documents-table.png)

Click [here](https://support.catenda.com/en/articles/11748020-tables-on-catenda) to read more about how to work with tables in Catenda. As soon as a document or folder is created it will show up as a row in the documents table for the person.

### 4.1 **Selected item actions**

After selecting an element row selected item actions appear towards the top of the documetns table. This is what the selected item actions menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/nzhpbg4s/06-selected-item-actions.png)

Click [here](https://support.catenda.com/en/articles/4670288-document-structure-actions) to read more about the selected item actions on the documents page.

### 4.2 **Row content**

When the table is first loaded in, up to 100 rows are displayed. If more than 100 rows are in the table scroll down to the bottom to load in the next 100 rows.

**Access** Rows on the documents page are displayed based on the access to the element. _Access required -_ Read

**Folder row** Opening the content of a folder row changes the table to display the contents of that folder on the documents page.

**Document row** Opening the content of a document row opens the [document preview](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations) of the latest revision of that document.

**Image or 3D document icons** Opening the content of an image or 3D document icon will open a popup preview dialogue. In the preview dialogue images that are currently in the table can be flipped through.

**2D and 3D buttons** For 2D, the 3D panel opens up and the first story of the latest revision of the document is loaded into the 2D viewer. For 3D, the 3D panel opens up and the latest revision of the document is loaded into 3D.

### 4.3 **Row content with status workflow -** Draft revisions

Opening the content of a document row with only draft revisions opens the [document preview](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations) of the latest draft revision of the document. Only published revisions can be loaded in 3D so until a revision gets published, there will not be 2D and 3D buttons in the viewer column.

Opening the content of a document row with draft and published revisions opens the the latest published revision of the document, even if there are newer draft revisions. The 2D and 3D views of the latest published revision are opened even if there are more recent draft revisions.

### 4.4 **Row content with status workflow - Workspace tab**

**Access** Rows on the documents page are displayed based on the access to the element. With access to viewing shared revisions, the latest revision is displayed. _Access required_ - Access to viewing shared revisions in the document

Without access to viewing shared revisions, the latest published revision is displayed. Even if there are more recent shared revisions. _Access required -_ Read access to the document

**Document content** Opening the content of a document row in the workspace tab opens the [document preview](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations) of the latest shared revision, even if revisions in the document were previously published.

**2D and 3D buttons for model documents** The 2D and 3D views of the latest revision a user has access to are opened.

### 4.5 **Row content with status workflow -** Published tab

**Access** Rows on the documents page are displayed based on the access to the element. Document rows with at least one published revision are displayed. _Access required -_ Read

**Document content** Opening the content of a document row in the published tab opens the [document preview](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations) of the latest published revision of the document, even if there are newer shared revisions.

**2D and 3D buttons for model documents** The 2D and 3D views of the latest published revision are opened even if there are more recent shared revisions.

### 4.6 **Columns**

Some columns in the documents table are enabled by default while others can be hidden and have to be enabled. Based on the configured column order the first columns are displayed while the table might have to be scrolled sideways to show other enabled columns. The default order and visibility setting of the columns on the documents page is as follows:

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><h3 id="h_face62c318"><b>Documents table columns</b></h3></td></tr><tr><td style="background-color: #e8e8e880;"><p>Checkbox - <i>Default</i></p></td></tr><tr><td><p>Click on the checkbox in this column to add a document to your selection.</p><p>See <a class="intercom-content-link" href="https://support.catenda.com/en/articles/6941099-table-view-in-a-topic-board#h_e2ba9177de">selection options</a>.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Name </i>- <i>Default</i></p></td></tr><tr><td><p>The name of the document or folder.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Revision - <i>Default</i></p></td></tr><tr><td><p>The revision number of the latest revision that is displayed in the table.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Revision name</p></td></tr><tr><td><p>The file name of the latest revision that was uploaded to the document.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Short name</p></td></tr><tr><td><p>The name of the linked model on the models page and in the revision selector of the 3D viewer. Can only be configured on documents.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Status - <i>Default</i></p></td></tr><tr><td><p>The status of the document. Empty by default. Can only be configured on documents.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Size - <i>Default</i></p></td></tr><tr><td><p>The filesize of the document. Empty for folders.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Labels - <i>Default</i></p></td></tr><tr><td><p>The labels applied to the element</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Created</p></td></tr><tr><td><p>The member that created the document and when they created it. </p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Published - <i>Default</i></p></td></tr><tr><td><p>The member that published document and when they published it. </p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Links - <i>Default</i></p></td></tr><tr><td><p>If objects are linked to a document or folder a button is displaye with the number of linked objects. Click the button to select the objects in 3D.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Viewer - <i>Default</i></p></td></tr><tr><td><p>2D, 3D and zoom to extents buttons are available for 3D documents in this column.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Custom field columns</p></td></tr><tr><td><p>One column per custom field that is configured for the current folder.</p></td></tr></tbody></table></div>

Click [here](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page) to read more about the different columns in the documents table.

## 5. **Sub pages**

The following pages can be found as sub-pages to the documents page:

- [collections](https://support.catenda.com/en/articles/6344318-collections-page)
- [approvals](https://support.catenda.com/en/articles/8349340-approvals-page)
- [settings](https://support.catenda.com/en/articles/7831371-document-settings)
