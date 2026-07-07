# Folder configuration - Document settings

The folder configuration menu can be found on the [document settings page](https://support.catenda.com/en/articles/7831371-document-settings-page). By setting up a configured folder you can enhance the way documents are handled in that workflow.

## 1. **Folders table**

Folders can be configured in the folders table which can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/01-folders-table.png)

### 1.1 **Configured folders filter**

Towards the top of the table a filter can be found for configured folders.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/02-configured-folders-filter.png)

**All folders** See all folders in the project.

**Configured folders** See which folders that are configured in the project

### 1.2 **Folders column**

Here you see all the folders in the project. Clicking on the arrow or anywhere on this column will expand the folder so you see its sub folders. If you hover over the icon or name of a folder you will see a link icon which you can click to open the folder

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/03-folders-column.png)

This can help a lot with seeing the results of the configured folder after configuring it.

**Add configuration** Click the + button to the right of a folder to open the [folder configuration dialogue](#folder-configuration-dialogue). If there are configurations in sub folders you will not be able to make a configuration for the folder.

**Preview configuration** If a configuration is set for a folder you will be able to quickly see what configuration has been set by clicking on the eye icon. The configuration preview can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/04-folders-column.png)

**Edit configuration** If a configuration is set for a folder you will be able to edit it by clicking on the pencil icon.

**Configuration inheritance** If a configuration has been set in a parent folder, all its sub folders will inherit its configuration.

### 1.3 **Naming convention column**

Here you see which naming convention blocks are configured for a row

### 1.4 **Custom fields column**

Here you see which custom fields are configured for a row

## 2. **Folder configuration dialogue**

The folder configuration dialogue can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/05-folder-configuration-dialogue.png)

### 2.1 **Naming convention**

If you have naming conventions set up on the [naming convention page](https://support.catenda.com/en/articles/7832559-naming-conventions-page) in [project settings](https://support.catenda.com/en/articles/4670273-project-settings-page) you will be able to choose what folder the naming convention gets applied to here. When applying a convention all new documents in the folder and subfolders have to:

- Be named according to the naming convention
- Have a document name which cannot be edited while the convention is active
- Stay in the folder they were uploaded to and cannot be moved

To remove a naming convention press the X.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/06-naming-convention.png)

### 2.2 **Custom fields**

With custom fields you will be able to assign custom fields on all documents in this configuration. Custom fields can either be set for the whole document or for each revision. _Access required to change the field:_ Write

**Custom document fields**

- Values will be stored on the document
- Example on custom fields: "Document description", "Document note", etc...

**Custom revision fields**

- Values will be stored on each revision of the document
- Only values stored on the latest revision will be displayed together with the document.
- Examples on custom fields: "Revision comment", "Approval status", etc...

**Name** The name of the custom field

**Type** The type of the custom field. The following types of custom fields can be made available for folders: Date Decimal Dropdown Integer Text

**Is required** If a field is required it always has to have a value.

> **Note:** A default value will need to be set as the document will have to have a value upon upload.

**Default value** If a default value is set, this value will be set for the field for all documents uploaded after the configuration is confirmed unless it is changed later.

## 3. **Assign QR code**

With [QR code stamping](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda) you will be able to select if you want this function to be turned on for a folder here.
