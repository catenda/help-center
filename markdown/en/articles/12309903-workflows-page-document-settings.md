# Workflows page - Document settings

The workflows page can be found by clicking on the configure workflows button in the approvals menu of the [documents settings page](https://support.catenda.com/en/articles/7831371-document-settings-page) in projects where the new validation workflow has been requested to be enabled and shared statuses are enabled in the status workflow menu of [document settings](https://support.catenda.com/en/articles/7831371-document-settings-page). The new validation workflow is an on-demand feature that can be requested to be enabled when starting a new project. It is only possible to create a project based on a template project when the new validation workflow is not enabled in that template project. On the workflows page workflows for different approval configurations can be configured. _Access required:_ Administrator

The workflows page can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/01-intro.png)

The following topics will be described in this article:

_[New item actions](https://support.catenda.com/en/articles/8204673-documents-page#h_d0f4a44fb7) - [Search or filter](https://support.catenda.com/en/articles/8204673-documents-page#h_bbf4dcad58) - [Right menu](https://support.catenda.com/en/articles/8204673-documents-page#h_fc89aaa1fe) - [Table](https://support.catenda.com/en/articles/8204673-documents-page#h_54e8dfcac2) - [Sub-pages](https://support.catenda.com/en/articles/8204673-documents-page#h_5751ccd2b7)_

While the workflows page is a sub-page to the approvals page as is apparent by the approvals page being higlighted and the breadcrumbs towards the top, the page is only accessible from the approvals menu in document settings.

## 1. **New item actions**

The new item actions can be found on the top right of the page.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/02-new-item-actions.png)

See here for what the different actions do.

## 2. **Search or filter options**

This is what the search or filter menu can look like on the workflows page.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/03-search-or-filter-options.png)

In the search bar any workflow that is available on the workflows page can be searched.

### 2.1 **Filter left panel**

By clicking the filter button a panel will appear on the left side. Check the boxes to narrow down the search. When any of these filters are applied the filter text will be added to your URL. If the URL of the filtered page is shared the person opening it will see the same resultes as are currently displayed as long as they have access to them.

### 2.2 **Filters**

> **Note:** The URL of the webpage changes depending on what filters have been applied. This makes it so the current filtered documents table can be shared with other members that are part of the project.

If multiple of the same filters selected they are separated by a `,` or `%2C` If multiple filters are selected they are separated by `&` or `%26` Different filters and their URL equivalents:

**Status** Active - Default - `status=active` Archived - `status=archived `

> **Note:** It is only possible to either show active or archived workflows, not both at the same time

**Search** Text search - `search=test` By default the text search only matches active workflows. To search on archived statuses, first filter on archived and then use the text search.

## 3. **Workflows table**

The workflows table can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/04-workflows-table.png)

Click [here](https://support.catenda.com/en/articles/11748020-tables-on-catenda) to read more about how to work with tables in Catenda. As soon as a workflow is created it will show up as a row in the workflows table.

### 3.1 **Row content**

**Workflow row** Opening the content of a workflow row opens the workflow page for that workflow. This is what a workflow page can look like when opened.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/05-row-content.png)

On the workflow page of a workflow it is possible to see how the workflowhas been configured.

Title The only part of the workflow that can be edited is the name of the workflow.

Timezone If a timezone is selected for the workflow it will stay the same all year around. If a geographical location is selected for the workflow the GMT offset will change depending on which timezone is currently active for that geographical location.

Update Click on update to update the title.

### 3.2 **Columns**

Some columns in the workflows table are enabled by default while others can be hidden and have to be enabled. Based on the configured column order the first columns are displayed while the table might have to be scrolled sideways to show other enabled columns. The default order and visibility setting of the columns on the workflows page is as follows:

Title - _Default_ The title of the workflow

Created by - _Default_ The member that created the workflow.

Created at - _Default_ The date and time the workflow was created

Status - _Default_ The status of the workflow
