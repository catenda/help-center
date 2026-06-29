# Revit IFC Export Manual

With this IFC export manual, the goal is to give the user a guide on how to export the IFC for the right purposes. An IFC file can quickly become heavy and large when you have a lot of information to get out of the model. That is why when exporting an IFC, you need to uncheck unnecessary information. When uploading a model to Catenda, it is not always necessary to have a lot of information and a high level of detail in the model. A little later in this manual we will return to what settings we recommend to make the model a little smaller and a little easier to work with. Here we will go through step by step the most appropriate way to export an IFC from Revit to Catenda.

## 1. **Project settings**

Before exporting it is important to make sure that the GUID's of your Revit project are correct.

`Manage -> Settings -> Project Information -> IFC Parameters`

![Project information IFC Parameters IfcSite GUID IfcBuilding GUID IfcProject GUID](images/01-project-settings.png)

If the GUID is different from a previous export the objects of newer exports will not be properly linked to the GUIDs in BCF topics. When you make a new project it will have a unique id.

## 2. **Modify IFC export**

When Revit is open and you are ready to export, you may want to do the following.

![On th top left of the screen, press file](images/02-modify-ifc-export.png)

Top left we find "File" tab.

---

> **Tip:** **Remember:** _You may want to have a dedicated folder for your IFCs, so you always have control over where your file is located!_

The IFC export menu can be found here:

`File -> Export -> IFC`

![](images/03-modify-ifc-export.png)

This is what the Export IFC menu can look like:

![Export IFC](images/04-modify-ifc-export.png)

File name Enter the name and location that the exported file will have in the system

Export setup Choose between the following pre-defined setups: \<In-Session Setup> IFC 2x3 Coordination View 2.0 IFC 2x3 Coordination View IFC 2x3 GSA Concept Design BIM 2010 IFC 2x3 Basic FM Handover View IFC 2x3 Coordination View IFC 2x3 COBie 2.4 Design Deliverable View IFC4 Reference View [Architecture] IFC4 Reference View [Structural] IFC4 Reference View [BuildingService] IFC4 Reference View [Unofficial] IFC4x3 IFC-SG Regulatory Requirements View

When the Catenda Plugin for Revit is used, an extra pre-defined export setup for use with Catenda is added to the list of options.

## 3. **Modify Setup**

Click on Modify setup in the export setup part of the export ifc dialogue. This is where the necessary settings for IFC exports can be changed and custom setups can be created. This is what the modify setup menu can look like:

![](images/05-modify-setup.png)

This window contains the following tabs:

---

### 3.1 **General**

![General](images/06-general.png)

![](images/07-general.png)

We'll take you through the various settings.

**IFC version** Selection of IFC version.

**Exchange Requirement** These options can change depending on the IFC version that is selected. IFC 2x3 Coordination View 2.0

- Architectural Reference Exchange
- MEP Reference Exchange
- Structural Reference Exchange

**Category mapping** Before Revit 2026 this option was available in File -> Export -> Options -> IFC Export Options. This is what the Manage IFC Export Mapping Settings menu can look like:

![](images/08-general.png)

**File type** IFC type selection.

**Phase to export** If you have used the phase tool in Revit, here you can choose and only export new or existing structures.

**Space boundaries** These are all about how room information can be used further. a. 1st Level - Ex on use: Quantity withdrawals, management, operation and maintenance (FDVU). b. 2st Level - Ex on use: Energy analysis, light analysis.

**Facility Type** This option is only available for IFC 4x3 Choose between one of the following: Bridge (IfcBridge) Building (IfcBuilding) Marine Facility (IfcMarineFacility) Railway (IfcRailway) Road (IfcRoad)

**Split Walls, Columns, Ducts by level** Here you can f. Ex dividing walls horizontal if modeled over several floors.

_File Header information... Project Address..._ In these you can put information on who has delivered the IFC, project address etc.

**Project Origin** Project origin, this we put on Current shared coordinates- Present shared coordinates.

> **Note:** This is moved to Geographic reference as of Revit 2025

**Include Steel Elements** Includes steel components if modeled.

> **Note:** This is moved to Additional content as of Revit 2025

---

### 3.2 **Additional Content**

![Additional Content](images/09-additional-content.png)

![](images/10-additional-content.png)

Export linked files as separate IFC's If you want to include the linked files in the IFC you can check this option to do so. It is recommended that you export each file separately and import each to their own model.

Export only visible objects visible in view IFC file.

- Export rooms, areas and spaces in 3D views 
This option can be useful for selecting areas in the 2D viewer.

Include Steel elements, _filled_

Exports 2D plan view elements, _filled, regions_ (scratches).

Export Ceiling Grids Ceiling grids are 2D elements and thus not displayed in the Catenda 3D viewer.

---

### 3.3 **Property Sets**

![Property Sets](images/11-property-sets.png)

![](images/12-property-sets.png)

Exports all Revit Property sets (pset / properties) Here is an example of a wall exported with this option: Revit (_Left_) --- Catenda (_Right_)

<img alt="Properties" src="images/inline-4f4aab46be4e.png" width="208.60495436766624"/>  ---  <img alt="Properties" src="images/inline-7c05fd3c2c4a.png" width="190.21739130434784"/>

Typical properties that show in the properties menu are: Constraints, Cross-Section Definition, Dimensions, Structural, Identity Data, Other

Typical properties that show in the Identification menu are: IFC Parameters Export standard IFC properties. Exports calculated quantities of objects. Export batch lists Export one-off Property Set

**Classification settings** Here is an example of what classification settings can look like with omniclass.

![Classification Settings](images/13-property-sets.png)

**Name** The name of the classification

**Source (Publisher)** The publisher of the classification

**Edition** The classification edition

**Edition date** The date of the classification

**Documentation location** This has to be a valid documentation location

**Classification field name** The classification field name is the name of the parameter in your objects that will hold the classification value. This parameter can often be found on the family level. Edit a family to see its properties

![Edit Family](images/14-property-sets.png)

This is what the parameter can look like in the properties

![Properties OmniClass Number](images/15-property-sets.png)

If you have exported your ifc with a classification and imported it as a model to Catenda you will see its classification suggested as a [suggested library](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca) when creating a new library on the [libraries page](https://support.catenda.com/en/articles/8065645-libraries-page). If a value in the property you specified matches with a value in the documentation provided it will be found and can be used to select objects with this value through the classification library you created.

---

### 3.4 **Level Of Detail**

![Level of Detail](images/16-level-of-detail.png)

![](images/17-level-of-detail.png)

This is about how detailed we have for example. cups or handrails or maybe bicycle wheels. There are 4 different levels of detail.

Extra Low Low Medium High

When high, it gets the most detailed as shown in the picture below.

![Level of detail extra low and high](images/18-level-of-detail.png)

---

When exporting IFCs from Revit to be used in Catenda Hub, we recommend not to set the level of detail to high. There will be a lot of details and extra polygons in models when exported with higher level of detail and this is not always necessary and will make the model navigation slower. This is an example of the difference between exporting with the Extra low and High setting.

![This is a stair railing exported with the setting High. 900k polygons](images/19-level-of-detail.png)

![This is the same model exported with the setting Extra Low. 33k polygons.](images/20-level-of-detail.png)

The appearance of the model will be close to the same, but the number of polygons will decrease drastically and the navigation in Catenda Hub will be a lot faster.

---

### 3.5 **Advanced**

![Advanced](images/21-advanced.png)

![](images/22-advanced.png)

**Export parts as building elements** Export parts like standard IFC element.

**Allow use of mixed "Solid Model" representation** Select this option to allow mixing of BRep and extrusion geometries for a unit.

**Use active view when creating geometry** Select this option to use the active view to generate the geometry. Note that this may have unexpected results if used on a non-3D view.

**Use family and type name for reference** Select this option to use the family and type namesfor references.

**Use 2D room boundaries for room volume** Select this option to use a simplified approach for calculating room volume (based on extrusion of 2D space boundaries) which is also standard when exporting to IFC 2x2.

**Include IFCSite elevation in the site local placement origin** Select this option to include the height from the Z-offset for local position in IfcSite. Remove the option to exclude it.

**Store the IFC GUID in an element parameter after export** Select this option to save the generated IFC GUIDs to the project file after export. This will add "IFC GUID" parameters to items and their types and Project information for project, website and building guides.

**Export bounding box** Select this option to export "Bounding box" representations. This option remains automatically selected for GSA export.

**Keep Tessellated Geometry as Triangulation** If you have complex curved elements or shells and they do not display correctly after the IFC export you can select this option. Keep in mind yo that you might produce a very heavy IFC file.

**Use Type name only for IFCType name** Select this option if you want the BAT-ID or the ID of the object to appear as the name of the entity.

**Use Visilble Revit name as the IFCEntity name** Select this option if you want the Revit object name to be the name of the entity

**Always export faceted floors and roofs as a single IFC enitity** Select this option to combine faces of floors and roofs with multiple faces to a single entity.

**Set "Last Modified" user to the Author in Project Information** Select this option if you are the author of the changes in this export

**Entities to export** This is what the IFC Entity Selection menu that opens upcan look like:

![](images/23-advanced.png)

---

### 3.6 **Geographic Reference**

It is important that your Revit coordinates are synchronized with the other models in your project so that they end up on the same place. Therefore measure the coordinates in Catenda Hub with a point measure and specify a coordinate base in Revit at a point that is on the same place as the measured point in Catenda Hub.

![Specify Coordinate at POint](images/24-geographic-reference.png)

You can find this option in the Manage tab -> Coordinates -> Specify Coordinate Base. _Specify Coordinates at Point_ Relocates a model and rotates the model to True North by specifying coordinates for North/South, East/West, and Elevation. In Revit it is often easier to model on 90 degree angles and you don't want to rotate the whole model. In this case you can rotate True North instead. You will find the option in the Position dropdown below Coordinates in the Manage tab.

![Geographic Reference](images/25-geographic-reference.png)

![](images/26-geographic-reference.png)

**Project site** Internal

**Coordinate base** You can change this setting to make sure your project is oriented towards North Shared Coordinates - Default Survey point Project Base Point Internal Origin Project Base Point Oriented in True North Internal origin Oriented in True North

> **Note:** If you Link IFC in the Insert tab your linked file will be placed close to your objects and will not be in the location described in the IFC. To import an IFC to the right location click File -> Open -> IFC instead.

**Override** Here you can override the projected Coordinate System Reference

---

### 3.7 **Company Info**

![](images/27-company-info.png)

![](images/28-company-info.png)

This menu is only available when the IFC2x3 COBie 2.4 Design Deliverable View Setup is selected in the left menu.

---

### 3.8 **Project info**

![](images/29-project-info.png)

![](images/30-project-info.png)

This menu is only available when the IFC2x3 COBie 2.4 Design Deliverable View Setup is selected in the left menu.

---

## 4. **IFC Options**

The IFC Options of a Revit project can be found in:

`File -> Export -> Options -> IFC Options`

![Export -> Options -> IFC options](images/31-ifc-options.png)

> **Note:** From Revit 2026 this option is now available in: `Export -> IFC -> General -> Category Mapping -> Action menu right of dropdown`

Here within the _IFC options_ we make the settings for exporting a model to an IFC file. Here you can customize setup properties for exporting a model to IFC. What was mentioned at the start of this manual is it is not necessary to bring too much information out of the model. Feel free to tick off unnecessarily information before export.

![IFC export classes](images/32-ifc-options.png)

It is possible to view grids in Catenda Hub, and if you have these in your Revit model it is in IFC Options you can set grids to be exported in the IFC. By default these are not exported from Revit.

## 5. **Colors and materials**

The colors that are displayed in Catenda are read from the IFC file that is imported. When the material property of a family is added to the IFC parameters, the color of the material in the material property is added to the IFC and thus displayed in Catenda. In Revit materials can be found in the material browser:

`Manage tab -> Settings section -> Materials`
In the Material browser the setting for color can be found in the graphics tab of the material:

![Manage -> Materials -> Material browser -> Create new material](images/33-colors-and-materials.png)

It is also possible to lock the shading to the render settings.

![Appearance](images/34-colors-and-materials.png)

Surfaces in the Catenda 3D viewer have flat shading without a light source present. The following values are interpreted by Catenda when displaying the surface in the 3D viewer:

Generic

- Color
- Image fade

Transparency

- Amount
- Image Fade
- Translucency

Tint

- Tint Color
