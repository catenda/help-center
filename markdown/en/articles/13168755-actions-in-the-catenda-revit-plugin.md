# Actions in the Catenda Revit Plugin

> **Note:** The install file for the plugin can be found in [this article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

The actions [Catenda Revit Plugin](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin) can be found towards the top right of the plugin window within the Revit application.

This is what the action menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/01-intro.png)

Information about the following topics can be found in this article:

## 1. **New topic**

Click on the green New topic button towards the top right to create a new topic in the project that is currently selected in the dropdown menu towards the top left. The topic will be created in the topic board that is selected in the second dropdown menu towards the top left. _Access required:_ Write access to the topic board

As soon as the topic is created it will be visible in Catenda Hub via the browser as well as through any Catenda plugins in other programs. This is what the new topic page can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/02-new-topic.png)

The minimum information that is required to submit a topic is a title.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/03-new-topic.png)

**Submit** Once the topic is ready to be shared with the project, click submit to submit the topic to the topic board.

## 2. **Upload IFC**

Click on upload IFC in the action menu that opens up with the three dots towards the top right to upload your current Revit model directly to Catenda Hub as an IFC file. This is what the upload IFC page can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/04-upload-ifc.png)

After opening the upload page:

1. Select the Catenda Hub model where you will be creating a new revision
1. Type in a comment associated with the upload
1. Select an IFC configuration. A new configuration can be created in the IFC export menu in Revit. You can also select the \<Catenda setup> for an easy to use configuration well suited to Catenda Hub.
1. Click on Upload

These are the export settings of the Catenda Setup

```
selectedConfig.Name = "<Catenda Setup>"; selectedConfig.IFCVersion = IFCVersion.IFC2x3CV2; selectedConfig.SpaceBoundaries = 1; selectedConfig.ActivePhaseId = ElementId.InvalidElementId; selectedConfig.ExportBaseQuantities = true; selectedConfig.SplitWallsAndColumns = false; selectedConfig.VisibleElementsOfCurrentView = false; selectedConfig.Use2DRoomBoundaryForVolume = false; selectedConfig.UseFamilyAndTypeNameForReference = true; selectedConfig.ExportInternalRevitPropertySets = true; selectedConfig.ExportIFCCommonPropertySets = true; selectedConfig.Export2DElements = false; selectedConfig.ExportPartsAsBuildingElements = true; selectedConfig.ExportBoundingBox = false; selectedConfig.ExportSolidModelRep = false; selectedConfig.ExportSchedulesAsPsets = false; selectedConfig.ExportUserDefinedPsets = false; selectedConfig.ExportUserDefinedPsetsFileName = ""; selectedConfig.ExportLinkedFiles = false; selectedConfig.IncludeSiteElevation = true; selectedConfig.UseActiveViewGeometry = false; selectedConfig.ExportSpecificSchedules = false; selectedConfig.TessellationLevelOfDetail = 0; selectedConfig.StoreIFCGUID = true; selectedConfig.ExportRoomsInView = true;
```

## 3. **Settings**

The settings page allows you to change how the plugin will create 3D view when using the [Zoom function](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin#h_36392f671a).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/05-settings.png)

### 3.1 **Back to topics**

Click on back to topics to go back to the topics list.

### 3.2 **Navigation**

**Keep the 3D view orthographic** This option will force the Revit 3D view to be orthographic even if the corresponding viewpoint has been created with a perspective view.

**Create a new view for every topic** Instead of reusing the same 3D view each time you use the Zoom function, this option will create a new 3D view for every topic each time you use the zoom function.

**3D view name suffix** This text will be added to the name of the 3D view created when using the Zoom function.

### 3.3 **Viewpoint Transform**

With the viewpoint transform the viewpoint in Revit can be configured to be offset by an amount. If values have been configured here the viewpoint will be offset by that amount each time a viewpoint from a topic is played. This can be useful when the coordinates in the topic viewpoint do not match with the coordinates configured in the Revit project.

**X (E/W)** Transform in the X direction. East or west depending on positive or negative values. Units in meters

**Y (N/S)** Transform in the Y direction. North or south depending on positive or negative values. Units in meters

**Z (Elev)** Transform in the Z direction. Elevation depending on positive or negative values. Units in meters

**Angle** Rotational transformation. Elevation depending on positive or negative values. Units in degrees. The camera will stay at the same height and rotate the camera around a point in the model.

## 4. **Account**

Open your Catenda Hub account page in your default browser. Click [here](https://support.catenda.com/en/articles/6880968-account-page) to read more about the account page.

## 5. **Sign out**

Click on Sign out to sign out of Catenda Hub within the plugin.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/06-sign-out.png)

After signing out the Sign in page is displayed where the same account or a different acount can be signed into with username and password. Click [here](https://support.catenda.com/en/articles/7891486-sign-in-page) to read more about the sign in page.

After signing in again the first project in the project list will be displayed. Select a project in the projects list again to navigate a different project.
