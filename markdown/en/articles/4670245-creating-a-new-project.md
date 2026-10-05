# Creating a new project

If your current plan and access allows for it, you can create a new project by signing in and on the [project page](https://support.catenda.com/en/articles/4670260-account-buttons), click the "New Project" button or by going to the [new project page](https://hub.catenda.com/new-project).

Otherwise, to create a new project contact Catenda support at [support@catenda.com](mailto:support@catenda.com) or via the chat button. The black chat button can be found on the top right inside of Catenda Hub or to the bottom right on our help/home pages to upgrade your plan. We will guide you through creating it.

This is what the new project page can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/bwrskh2q/01-intro.png)

## 1. **Select an owner**

Users with access to enterprise organizations will be able to create the amount of projects that their plan allows.

## 2. **Name**

The name of the project. Here are some suggestions of what can be added to the project name:

### 2.1 **Numbers**

Often the project number is used in the beginning of the name. Numbers in front of the name are recommended because the projects are sorted alphabetically on the projects page.

### 2.2 **Location**

Location is often mentioned in the project name.

### 2.3 **Type of project**

For example an office building or a school.

### 2.4 **Project phase**

If there are multiple phases to this project the phase can be added to the project name.

## 3. **Document download title**

Each organization has a document download setting.

### 3.1 **Default**

The document download setting that a created project receives is based on the document download setting for new projects in the organization it is created in. New organizations have the 'Revision file name' option enabled by default. Documents downloaded in projects created in new organizations therefore get the revision name of the downloaded revision in the file title. Click [here](https://support.catenda.com/en/articles/8224886-organization-options#h_5564d6602f) to see other options that are available for organizations.

### 3.2 **New projects in configured organizations**

When the document download option for new projects in an organization is changed this setting is only applied to new projects created in the organization and not for the existing projects. It is therefore possible that there are projects in the same organization with different document download settings.

### 3.3 **Projects created from a template project**

The document download setting of a new project is based on the organization it is created in, not on the template project. It is never copied from the template project, so it is not one of the options when a template project is used.

## 4. **On-demand features**

When a new project is created opt-in features are not enabled by default. It is possible to request for the following feature to be enabled after creating a project:

[Reports page](https://support.catenda.com/en/articles/12303098-reports-page)

## 5. **Select a project to use as template**

Check the use another project as a template box to inherit settings of another project when making a new project. _Access required:_ Project member

This is what it can look like when a template project is used:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/bwrskh2q/02-select-a-project-to-use-as-template.png)

Items with a light green checkbox are always copied and cannot be unchecked. Labels, Milestones, Teams and Topic boards are always copied from the template project. Items with a dark green checkbox are optional and can be unchecked.

Some items become required when another item is checked, as the note above the list says: "Items required by your selection are included automatically and cannot be unchecked." Currently the only dependency is on Approval workflows. When Approval workflows is checked, Document status configuration and Topic templates are included automatically and are shown in light green. When Approval workflows is unchecked, Document status configuration and Topic templates become optional and are shown in dark green.

### 5.1 **Models (no revisions)**

The models of the template project are copied without their revisions, so they are empty and ready to receive new revisions. _Selection:_ Optional

### 5.2 **Labels**

The labels of the template project are copied, ready to be connected to topics, models and documents. It is useful to have the same labels in multiple projects for analysis with tools like Power BI. _Selection:_ Mandatory

### 5.3 **Milestones (no dates)**

The milestones of the template project are copied without their dates. This is useful when creating a new project upon a phase change that has the same milestones as the last one. _Selection:_ Mandatory

### 5.4 **Teams (no members)**

The teams of the template project are copied without their members, ready to accept members. Access in the document structure is also distributed through teams. _Selection:_ Mandatory

### 5.5 **Topic boards (including statuses and types, but no topics)**

The topic boards of the template project are copied with their statuses and types, but without topics, so they are set up and ready to be used for communication. Boards can lie archived until they are ready to be used. _Selection:_ Mandatory

### 5.6 **Folder structure**

The names and structure of the template project folders are copied without their documents. _Access required:_ Full access to the template project _Selection:_ Optional

### 5.7 **Document status configuration**

The document statuses of the template project are copied. Public document statuses can be used to keep track of the progress of a document. Draft document statuses can be used for approvals. _Selection:_ Mandatory when Approval workflows is checked, optional otherwise

### 5.8 **Document and topic board access control**

The access control of the folder structure and the topic boards is copied, for those of the two that are selected.

The following is included:

- Defined access for "Teams"
- Other access settings, such as "All users" and "Owners"

The following is not included:

- Defined access for "Users"

When this option is unchecked, the new project gets the default access instead. That is the default access for the root of the documents, which can be found in the documents settings, and the default access for the default topic board. _Access required:_ Administrator or owner of the template project _Selection:_ Optional

### 5.9 **Custom fields, naming conventions and QR code**

The [folder configuration](https://support.catenda.com/en/articles/12302595-folder-configuration-document-settings) of the template project is copied: its custom fields, naming conventions and QR code stamping settings. Custom fields can be shown in issues and used in naming conventions. _Selection:_ Optional

### 5.10 **Topic templates**

The topic templates of the template project are copied, so topics can be created from the same templates in the new project. _Selection:_ Mandatory when Approval workflows is checked, optional otherwise

### 5.11 **Approval workflows**

The approval workflows of the template project are copied, so members can start submitting approval requests without a workflow being created first. The teams, document statuses and topic templates that a workflow uses are copied along with it, so every reference in the workflow still works in the new project. That is why checking Approval workflows makes Document status configuration and Topic templates mandatory. _Selection:_ Optional
