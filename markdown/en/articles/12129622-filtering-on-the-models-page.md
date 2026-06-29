# Filtering on the models page

The search or filter option can be seen in the top part of the window. By writing the name of the model, the name of a label that is pinned to a model or the username of a member, the rows in the models table can be narrowed down. This is what the search or filter menu can look like on the models page:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qfd47nkw/01-intro.png)

In the search bar you can search for any model that is available in the models table.

## 1. **Filter left panel**

By clicking the filter button a panel will appear on the left side. Check the boxes to narrow down the search. These filters can be saved at the top of the filter list. When any of these filters are applied the filter text will be added to your URL. If the URL of the filtered page is shared the person opening it will see the same filter in the same folder as is currently displayed as long as they have access to it. When any of the filters in the left panel are hovered over "only" can be clicked on the right of the filter to remove any other, previously applied, filters.

## 2. **Saved filters**

Click [here](https://support.catenda.com/en/articles/8551755-saving-filters) to read more about how to save a set of filters

## 3. **Filters**

Click the filter button on the top left for a panel to appear on the left side. When a filter is applied, the URL visible in the browser changes with it. In this article filters are displayed like so: _Filter name in menu_ - `Filter name in URL=Filter option in URL`

**Default filter** The default filter is initially not visible in the URL. When the page is navigated to for the first time the following filter is applied. Workspace tab - `v=all`

### 3.1 **Save and share the current filter**

Go to the URL of a filtered page to load that page with the filter applied. The applied filters can be saved towards the top of the filter menu. Click [here](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) to read more about how to save and share filters

### 3.2 **Hide empty filters**

Click [here](https://support.catenda.com/en/articles/8551755-saving-filters) to read more about limiting filter results.

### 3.3 **Tabs**

Workspace tab - `v=all` Published tab - `v=published`

### 3.4 **Links**

Linked - `associations=exists&subFolders=true` Unlinked - `associations=does-not-exist&subFolders=true` Linked to selected objects - `link=backlink&subFolders=true`

### 3.5 **Status (latest revision) - Status workflow only**

Published - `documentStatus=published&subFolders=true&documentType=file` Missing status - `documentStatus=published-without-status&subFolders=true` Project published status - `documentStatus=\<GUID>&subFolders=true` Shared - `documentStatus=shared&subFolders=true&documentType=file` Shared statuses are only available in the workspace tab Project shared status - `documentStatus=\<GUID>&subFolders=true` Has no revision - `documentStatus=no-stage&subFolders=true`

### 3.6 **Drafts - Status workflow only**

Has new drafts - `newDrafts=exists&subFolders=true` Draft status name - `newDrafts=\<Draft status GUID>&subFolders=true` If there are multiple draft statuses each draft status can be filtered on. Has no new drafts - `newDrafts=does-not-exist&subFolders=true`

### 3.7 **Document created by**

Member name - `owner=\<Member GUID>&subFolders=true`

### 3.8 **Revision created by**

Member name - `revisionCreatedBy=\<GUID>&subFolders=true`

### 3.9 **Published by**

Member name - `publishedBy=\<Member GUID>&subFolders=true`

### 3.10 **Date filters**

Published - `publishedAtFrom=\<UTC timestamp>&publishedAtTo=\<UTC timestamp>` Click on select dates to select dates in between which you would like to search Click [here](https://support.catenda.com/en/articles/6511685-date-filter) to learn more about the date filter

### 3.11 **Open approvals - Status workflow only**

Approval name - `approval=\<Approval number>&subFolders=true`

### 3.12 **Labels**

All labels that are not part of a label group will be displayed in a menu called labels. Label name - `labels=\<Label GUID>6&subFolders=true`

### 3.13 **Label group name**

There will be one menu per label group name Label name - `labels=\<Label GUID>6&subFolders=true`

### 3.14 **Collections**

Collection name - `collections=\<GUID>&subFolders=true`

## 4. **Text search**

_Text search_ - `search=test&subFolders=true`

### 4.1 **Content that can be searched on**

Model name

### 4.2 **Capitalization**

The text search is not sensitive to upper or lowercase characters.

### 4.3 **Character amounts**

Less than three characters - The table is not filtered. Three or more characters - Titles that have a single word,  separated by a separator character like a space, that matches the search phrase are included in the results.

### 4.4 **File types**

If the model name includes an extension, the extension can be searched on with the regular text search. Search on the file extention with the period included to search on a specific file type. For example when searching on .ifc all documents with .ifc in the model name can be found.

## 5. **Sort**

Models can be sorted by clicking the header of each column. The header can be clicked multiple times to revert or disable the sorting.

_Name, a-z_ - Default _Name, z-a_ - `sort=modelName-desc` _Document name, a-z_ - `sort=name-asc` _Document name, z-a_ -`sort=name-desc` _Published, newest first_ - `sort=publishedAt-desc` _Published, oldest first_ - `sort=publishedAt-asc` _Document created, newest first_ - `sort=createdAt-desc` _Document created, oldest first_ - `sort=createdAt-asc` Revision created_, newest first_ - `sort=revisionCreatedAt-desc` Revision created_, oldest first_ - `sort=revisionCreatedAt-desc`
