# Filtering on the documents page

The search or filter option can be seen in the top part of the window. By writing the name of the document or writing the name of a label that is pinned to a document the rows in the documents table can be narrowed down. This is what the search or filter menu can look like on the documents page:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aa862mj2/01-intro.png)

## 1. **Filters**

Click the filter button on the top left for a panel to appear on the left side. When a filter is applied, the URL visible in the browser changes with it. In this article filters are displayed like so: _Filter name in menu_ - `Filter name in URL=Filter option in URL`

**Default filter** The default filter is initially not visible in the URL. When the page is navigated to for the first time the following filter is applied. Workspace tab - `v=all`

### 1.1 **Save and share the current filter**

Go to the URL of a filtered page to load that page with the filter applied. The applied filters can be saved towards the top of the filter menu. Click [here](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) to read more about how to save and share filters. Note that unlike in other filter menus it is not possible to save personal filters towards the top of the filter menu on the approvals page​.

### 1.2 **Hide empty filters**

Click [here](https://support.catenda.com/en/articles/8551755-saving-filters) to read more about limiting filter results.

### 1.3 **Tabs**

Workspace tab - `v=all` Published tab - `v=published`

### 1.4 **Links**

Linked - `associations=exists&subFolders=true` Filter on documents linked to model objects in the 3D viewer.

Unlinked - `associations=does-not-exist&subFolders=true` Filter on documents that are not linked to model objects in the 3D viewer.

Linked to selected objects - `link=backlink&subFolders=true` If it is not already open, the 3D panel will open up. Select objects from a model in the 3D viewer to filter on topics linked to the selected objects.

### 1.5 **Status (latest revision) - Status workflow only**

Published - `documentStatus=published&subFolders=true&documentType=file` Missing status - `documentStatus=published-without-status&subFolders=true` Project published status - `documentStatus=<GUID>&subFolders=true` Shared - `documentStatus=shared&subFolders=true&documentType=file` Shared statuses are only available in the workspace tab Project shared status - `documentStatus=<GUID>&subFolders=true` Has no revision - `documentStatus=no-stage&subFolders=true`

### 1.6 **Drafts - Status workflow only**

Has new drafts - `newDrafts=exists&subFolders=true` Draft status name - `newDrafts=<Draft status GUID>&subFolders=true` If there are multiple draft statuses each draft status can be filtered on. Has no new drafts - `newDrafts=does-not-exist&subFolders=true`

### 1.7 **Models**

Is model - `model=is-model&subFolders=true` Is not model - `model=is-not-model&subFolders=true`

### 1.8 **Document created by**

Member name - `owner=<Member GUID>&subFolders=true`

### 1.9 **Revision created by**

Member name - `revisionCreatedBy=<GUID>&subFolders=true`

### 1.10 **Published by**

Member name - `publishedBy=<Member GUID>&subFolders=true`

### 1.11 **Date filters**

Published - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Click on select dates to select dates in between which you would like to search Click [here](https://support.catenda.com/en/articles/6511685-date-filter) to learn more about the date filter

### 1.12 **Open approvals - Status workflow only**

Approval name - `approval=<Approval number>&subFolders=true`

### 1.13 **Documents - Labels**

All labels that are not part of a label group will be displayed in a menu called documents. Label name - `labels=<Label GUID>6&subFolders=true`

### 1.14 **Label group name**

There will be one menu per label group name Label name - `labels=<Label GUID>6&subFolders=true`

The contents of custom fields where values can be configured can be filtered by writing a search pharse in the search or filter bar and selecting the corresponding filter in the suggested filter.

### 1.15 **Custom field**

_Custom field has value_ - `custom-field-has-value-<Custom field GUID>=true` With the "has value" option in the filter menu all topics with that have a value configured for that custom field can be filtered. Custom field types that can be filtered on has value: Date Decimal Dropdown Integer Text

_Custom field specific value_ - `custom-field-item-<Custom field GUID>=<Value GUID>` Specific values in fields for fields with up to 10 values can be filtered for. Custom field types that can be filtered on specific value from the filter menu: Dropdown

Some values in custom fields where values can be configured can be filtered. Filter for values by writing a search phrase in the search or filter bar and select the corresponding custom field. Custom field types that can be filtered by typing in the search or filter bar: Decimal Dropdown Integer Text

_Custom field has no value_ - `custom-field-has-value-<Custom field GUID>=false` Filter on all topics where a custom fields does not have any value. Custom field types that can be filtered on no value: Date Decimal Dropdown Integer Text

> **Note:** Custom fields that are set as required will always have a value. You will therefore not be able to search for "has value" or "has no value" can therefore not be searched for a custom field that is set as required.

### 1.16 **Collections**

Collection name - `collections=<GUID>&subFolders=true`

### 1.17 **Deleted**

Deleted - `deleted=deleted&subFolders=true` See [here](https://support.catenda.com/en/articles/4670249-undeleting-restoring-documents-or-folders) how to search for deleted documents

## 2. **Text search**

_Text search_ - `search=test&subFolders=true`

### 2.1 **Content that can be searched on**

Document title Folder title

### 2.2 **Capitalization**

The text search is not sensitive to upper or lowercase characters.

### 2.3 **Character amounts**

Single character - Titles that include the searched character are matched. Two characters - No results. Three or more characters - Titles that have a single word,  separated by a separator character like a space, that matches the search phrase are included in the results.

### 2.4 **File types**

If the title includes an extension, the extension can be searched on with the regular text search. Search on the file extention with the period included to search on a specific file type. For example when searching on .ifc all documents with .ifc in the title can be found.

## 3. **Sort**

Documents can be sorted by clicking the header of each column. The header can be clicked multiple times to revert or disable the sorting.

_Title, a-z_ - Default _Name, z-a_ - `sort=name-desc` _Published, newest first_ - `sort=publishedAt-desc` _Published, oldest first_ - `sort=publishedAt-asc` _Created, newest first_ - `sort=createdAt-desc` _Created, oldest first_ - `sort=createdAt-asc`
