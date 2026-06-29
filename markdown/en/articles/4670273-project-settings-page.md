# Project settings page

You will be able to find the project settings page as the last page of the left navigation menu in a project. This page is part of the content panel. Here you will be able to find settings that have to do with more than one project area.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4hamkb6q/01-intro.png)

## 1. **Project owner**

This is what the project owner menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4hamkb6q/02-project-owner.png)

There can only be one project owner. For most projects the owner of the project is the organization of the client that the project belongs to. Organizations are often called by the name of the client followed by the type of organization it is. What the organization is called is up to each organization owner, but they will often be called something like "Business A - Running projects", "Business B - Archive" or "Business C - Admin and templates" Organizations can be owned by multiple people who then have an overview of all the projects in that organization. Organization owners can also move projects from the [projects page in the organization tool](https://support.catenda.com/en/articles/8505058-projects-page-organization-tool) without having to be part of the project.

### 1.1 **Change owner**

If you are the owner of this organization and also other organizations, you will see the change owner text on the right of this menu. Here you will be able to change which organization owns this project. For example you could move a project from an organization with running projects to an archive organization this way. Click change owner, select the new organization, click make owner and confirm.

## 2. **Project details**

This is what the new project menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4hamkb6q/03-project-details.png)

### 2.1 **Project details**

Here you can add a picture of the building or any picture you would like. This picture will be shown in project details and on the [project page](https://support.catenda.com/en/articles/8400797-projects-page#h_1285a6d343) if you mark the project as a favorite. _Access required:_ Project administrator

### 2.2 **Project name**

Click on the pencil next to the project name to rename the project. _Access required:_ Project administrator

### 2.3 **Description**

Here you can enter a description of the project _Access required:_ Project administrator

## 3. **Measurement units**

The measurement units menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4hamkb6q/04-measurement-units.png)

Configure what units you want to use to use in your project

- Meters (m)
- Centimeters (cm)
- Millimeters (mm)
- Feet (')
- Inches ('')
- Fractional Inches

The selected measurement unit will be used by default for project members when measuring in the 3D viewer in this project. Change the measurement unit and click save. _Access required:_ Project administrator

## 4. **Default models folder**

The default models folder menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4hamkb6q/05-default-models-folder.png)

With [models as documents](https://support.catenda.com/en/articles/8064548-models-as-documents) every model is linked to a document in the document section. When you create a model you will therefore be asked where in the document structure you want the document to end up. If you create models via the API, the documents that will be linked for each model will need a place in the document section. If no default folder is specified a folder called models will appear if a model is created via the API. By default all users will have write access to the auto-generated folder.

## 5. **Delete project**

The delete projects menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4hamkb6q/06-delete-project.png)

Click the delete project button and write in the exact name of the project to confirm that you want to delete it. Organization owners can also delete the project from the [projects page in the organization tool](https://support.catenda.com/en/articles/8505058-projects-page-organization-tool) without having to be part of the project. If you do not see this option and wish to delete your project please contact support. _Access required:_ Organization or project owner

> **Warning:** **Warning!** A deleted project cannot be restored

## 6. **Access control**

The access control menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4hamkb6q/07-access-control.png)

Here you will be able to control actions that are project wide. Click on each of the menus to open them.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4hamkb6q/08-access-control.png)

Click on edit access to change the access of each setting. _Access required:_ Administrator

After opening the menu, project members will be able to see who has access to performing each action.

### 6.1 **Create new topic boards**

_Default access:_ All users - Write [Create new topic boards](https://support.catenda.com/en/articles/4670299-issue-board-creation-acl)

### 6.2 **Invite new members**

_Default access:_ All users - No access [Invite new members](https://support.catenda.com/en/articles/4670263-invite-members-page)

### 6.3 **Document status configuration**

_Default access:_ All users - Write [Document status configuration](https://support.catenda.com/en/articles/9874698-revision-publishing-iso-19650)

### 6.4 **Create and remove models**

_Default access:_ All users - Write [Create and remove models](https://support.catenda.com/en/articles/8300623-model-configuration)

## 7. **Geolocation**

The geoloaction menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4hamkb6q/09-geolocation.png)

Here you can configure a visual representation of where the project exists in the world.

### 7.1 **Geolocation of 3D models**

Configuring this setting does not affect the 3D models in the project as their coordinates are specified in each IFC file and/or model transformation setting.

### 7.2 **Geolocation of 2D models**

Configuring this setting places the 2D views of models that are generated by cutting through objects at a height on a location in the world. After configuring this a map will show up in the 2D viewer. Configuring this setting will also let you specify your initial 2D viewer rotation.

> **Note:** If your location was set before 24 March 2025 you will have edit and save or reconfigure your location to see the map.

### 7.3 **Projects page map**

If a location has been set members will see a pin for this project on their [map on the projects page](https://support.catenda.com/en/articles/8400797-projects-page#h_5cf5358c76).

## 8. **Logo**

The logo menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4hamkb6q/10-logo.png)

If you upload a logo here, it will replace the Catenda logo on the top left of every topic PDF export page when you [export topics to PDF](https://support.catenda.com/en/articles/9784934-exporting-topics-to-pdf#h_77568077c7) from a topic board.

## 9. **Sub pages**

You will be able to find the following pages as sub pages to this page:

- [Labels](https://support.catenda.com/en/articles/4670265-labels-page)
- [Custom fields](https://support.catenda.com/en/articles/6550459-custom-fields-page)
- [Naming conventions](https://support.catenda.com/en/articles/7832559-naming-conventions-page)
- [Members](https://support.catenda.com/en/articles/4670291-members-page)
