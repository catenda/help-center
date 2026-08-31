# Add revision to an approval request

Approval requests can be seen in projects where shared revisions were enabled after 2 October 2025. When shared revisions are enabled all new revisions are uploaded as shared revisions. Shared revisions can be added to an approval request by clicking on the add revision button in the [create an approval request dialogue](https://support.catenda.com/en/articles/12360159-creating-a-new-approval-request) and by clicking on the add revision button in a draft approval. This is what the add revision to aproval request dialogue that opens up can look like for projects that enabled shared revisions after

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qk34ake7/01-intro.png)

Projects where shared revisions were enabled before 2 October 2025 will see the legacy add revision to an approval request dialogue instead.

## 1. Search or filter

In the search bar any shared revision with a minor revision number (0.1, 0.2, 1.1, etc..) that has been uploaded after the latest published revision in a document can be searched.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qk34ake7/02-search-or-filter.png)

### 1.1 Filter left panel

By clicking the filter button a panel will appear on the left side. Check the boxes to narrow down the search. These filters can be saved at the top of the filter list. When any of these filters are applied the filter text will be added to your URL. If the URL of the filtered page is shared the person opening it will see the same filter in the same folder as is currently displayed as long as they have access to it. When any of the filters in the left panel are hovered over "only" can be clicked on the right of the filter to remove any other, previously applied, filters.

### 1.2 Saved filters

Click [here](https://support.catenda.com/en/articles/8551755-saving-filters) to read more about how to save a set of filters

### 1.3 Filters

**Linked** Drafts in the current folder and subfolders that are linked to objects that are currently selected in the 3D viewer The number behind the filter shows the amount of documents that are linked in the current folder and subfolders

**Unlinked** Drafts in the current folder and subfolders that are that are not linked to any 3D objects. The number behind the filter shows the amount of documents that are unlinked

Linked to selected objects Shared revisions in documents in the current folder and subfolders that are linked to 3D objects from models that are currently selected in the 3D viewer. The number behind the filter shows the amount of documents that are linked to selected objects

**Status**

Published status name Matches published revisions in the current folder and subfolders with the selected published status name. Revisions with a published status cannot be added to an approval so no results will be displayed with this filter. The number behind the filter shows the amount of documents that are linked to selected objects.

Shared Matches all shared revisions in the current folder and subfolders

Shared status name Matches all shared revisions in the current folder and subfolders with the selected shared status name

**Model** Is model Shared revisions in documents in the current folder and subfolders that are linked to models.

Is not model Shared revisions in documents in the current folder and subfolders that are not linked to models.

**Document created by** Shared revisions in documents in the current folder and subfolders created by username. The number behind the filter shows the amount of documents and folders that are created in the current folder and subfolders by each user.

**Revision created by** Shared revisions in documents in the current folder and subfolders created by \<username>. The number behind the filter shows the amount of shared revisions in documents in the current folder and subfolders by each user.

**Date filters** Click on select dates to select dates in between which you would like to search Click [here](https://support.catenda.com/en/articles/6511685-date-filter) to learn more about the date filter.

**Label group** Documents with shared revisions with labels by label name within a label group. The number behind the filter shows the amount of documents with shared revisions in documents where the label is applied in the current folder and subfolders.

**Custom field** Shared revisions with custom field values by custom field.

**Open approvals** Shared revisions that are part of other open approvals by approval request name.

**Deleted** While it is possible to filter on deleted documents and select them in the list nothing will happen when one is added to an approval. The number behind the filter shows the amount of deleted folders and documents in the current folder and subfolders. _Access required_: Administrator

## 2. Add revision table

This is what the add revision table can look like

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qk34ake7/03-add-revision-table.png)

Click [here](https://support.catenda.com/en/articles/11748020-tables-on-catenda) to read more about how to work with tables in Catenda.

### 2.1 Row content

Rows in the documents for review table are displayed based on the access to the shared revision in the document that is to be reviewed. _Access required -_ Read access to the document and the view shared revisions checkbox checked.

**Folder row** Opening the content of a folder row changes the table to display the contents of that folder in the add revision table.

**Document row** Clicking anywhere on the document revision rew selects the document so it can be added to the approval.

### 2.2 Columns

Based on the configured column order the first columns are displayed while the table might have to be scrolled sideways to show other enabled columns. The default order and visibility setting of the columns on the documents page is as follows:

Checkbox - _Default_ Select the checkbox to be able to add ths shared revision to the approval request

_Name_ - _Default_ The name of the document that the shared revision is in.

Revision - _Default_ In the revision column the revision number of the latest shared revision in the document is displayed. If there are multiple shared revisions that are uploaded after the latest published revison an arrow is displayed in the revision box. Click on a revision box with an arrow to open the revision dropdown table for this document.

> **Tip:** In the revision dropdown table the following columns are available: Name - _Default_ The name of the revsion. This is the same as the orginal filename of the file that was uploaded. # - _Default_ The number of the revision Status - _Default_ The status applied to the revision File size - _Default_ The filesize of the revision By - _Default_ The creator of the revision

It is only possible to add one revision per document at a time. If a different document revision from the selected document was previously added it will be overwriten and only the new revision selection from that document will ba added to the approval request.

Status - _Default_ The status applied to the shared revision.

Uploaded by - _Default_ The member that uploaded the shared revision.

## 3. Add

Select a document in the list and click on add

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qk34ake7/04-add.png)

As soon as a shared revision form a document is added it will show up as a row in the documents table for the person.

### 3.1 Limitations

After submitting the approval request through the create approval request dialogue or by submitting a draft approval request the list of documents can no longer be edited. While it is possible to add as many documents to the add revision to appproval request dialogue, it is only possible to submit the create approval request dialogue with up to 1000 document revisions. To add more than 1000 document revisions, first add up to 1000 documents in teh create approval request dialogue and save the approval request as a draft. Then add any amount of additional documents to the draft approval request with the add documents action on the draft approval request page before submitting the approval request.
