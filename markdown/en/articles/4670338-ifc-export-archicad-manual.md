# IFC Export Archicad Manual

When you export an IFC keep in mind what is relevant to your IFC export. The IFC file can be big and difficult to work with if it has a lot of information in it. Therefore it is important to not export unnecessary information. In this report you will get different tips to filter your IFC export in Archicad.

## 1. **1. Project info**

Before exporting an IFC from your project make sure the project info is configured. The project info can be found here:

`File -> Info -> Project info`

This is what the project info can look like:

![](images/01-1-project-info.png)

By default the different fields will be empty. Even though they are empty a unique id is created for each project, site and building that is listed.

### 1.1 **1.1 Multiple IFCs from same Archicad project**

In some situations multiple IFC files are exported from the same Archicad project. Examples of this are:

**1.1.1 IFC files with objects from different fields of study** An MEP model with ducts, an architecture model with walls and a structural model with all the slabs.

**1.1.2 Multiple buildings** Sometimes multiple buildings are modeled together within the same Archicad file and a separate IFC is exported for each of them.

**1.1.3 Different design choices** When different variations of a building are modeled in the same Archicad file each variation is often exported to its own IFC file.

### 1.2 **1.2 Configuring the project info**

Whether there are plans to export multiple IFC files or not it is often a good idea to input values in the project info so it does not have to be changed later on. The project info is important to fill out because it has effect on the GUIDs of the file. Each type of IFC that is exported should have its own project settings. The project settings can be imported and exported to the bottom right. This way multiple profiles can be supported for the exports from the file. For Catenda it is important the IFCs in different models have different information configued while IFC that will be in the same model have the same information configured.

## 2. **2. IFC export settings**

To export the entire project you must stand in 3D view. Make sure you use the correct translator.

![](images/02-2-ifc-export-settings.png)

Click the options button to see a summary of your IFC export settings. Under model filter you can also choose to filter out more.

![](images/03-2-ifc-export-settings.png)

The IFC translators box allows you to view or modify Translator settings, or to create new Translators. If you want to modify your IFC export there is recommended that you duplicate one of the premade translators so you don’t mess up one of the default translators. Duplicate a translator here: Click new > Duplicate of > select the translator you want to duplicate. If you want to merge the IFC you can do that under the same banner.

![image-2.png](images/04-2-ifc-export-settings.png)

## 3. **3. Different settings in the export**

3.1 [Model filter](#h_138e653078) lets you filter out what you want to export by different pre-sets. 3.2 [Type mapping](#h_a34c1332a3) lets you choose what kind of IFC type each element is exported as. 3.3 [Geometry conversion](#h_db084b5d6b) lets you choose what kind of geometry you want to export. 3.4 [Property mapping](#h_d48644eb35) lets you set up criteria based on types. 3.5 [Data conversion](#h_7f1df4ecb9) lets you choose what kind of data you want to export from the model. 3.6 [Unit conversion](#h_36caead1cd) lets you choose what measuring units you want to export in your IFC.

![](images/05-3-different-settings-in-the-export.png)

## 4. **4. Model filter**

### 4.1 **Exporting grids in the IFC**

Sometimes you want the grids exported as well to be able to see them in Catenda Hub. Go to the model filter for IFC Export and make sure the checkbox “Grid system and Elements” are checked.

![](images/06-exporting-grids-in-the-ifc.png)

## 5. **5. Type Mapping**

When an IFC is exported all the elements in the model gets assigned an IFC type. If you select the IFC translator you want to use you can then go to type mapping and click on the Map IFC Types for import to manage what kind of type mapping you want on your exported IFC.

![](images/07-5-type-mapping.png)

Type mapping mainly have to different options to sort your IFC types by.

### 5.1 **5.1 Element type**

Each element is automatically assigned a basic IFC type. You can se each element\`s assigned IFC type in project manager and in element settings.

### 5.2 **5.2 Classification**

This method allows more flexible and detailed IFC type mapping, according to specify classification standards. Zone and opening elements are set to a fixed IFC type. IFCSpace and IFCOpeningElements.

![](images/08-5-2-classification.png)

## 6. **6. Geometry conversion**

Geometry Conversion for IFC Export will let you convert your geometry in different ways.

![](images/09-6-geometry-conversion.png)

### 6.1 Conversions of Archicad elements

**6.1.1 Export only geometries which "Participate in Collision Detection"** Only export objects that intersect with other objects

**6.1.2 Export geometry of IFC Type Products** Type products included

**6.1.3 Export gross geometry of elements** Gross geometry included

**6.1.4 Export all model elements' geometry as:** _Parametric with exceptions_ - default

**Parametric (Extruded/revolved)** _BREP_ - Precise geometry - If this is selected the next two options will also be BREP

**6.1.5 Elements in Solid Element Operations:** _Extruded/revolved_ - default _BREP_ - Precise geometry

**6.1.6 Elements with Junctions** Some elements can intersect with other elements which can trim parts of the extrusion.

Extruded/revolved - Connect corners of elements This adds junctions to your extruded elements. With this option you will see that elements like walls or roofs, especially slanted ones will connect nicely.

Extruded/revolved without junctions - default This makes the export faster If you have 90 degree elements like walls or roofs you will probably not notice a difference with this options. If you have slanted walls you will notice that in the corner where the walls connect, instead of trimming the excess of the straight extrusion, the walls just go straight past each other and do not connect nicely.

BREP Precise geometry

**6.1.7 Parametric elements** Archicad elements can be exported as parametric geometry often in the form of guiding lines that are extruded to a distance. Parametric geometry makes it easy to edit the object after it has been created. While this option retains editability the geometry can often be somewhat imprecise as the definition is an approximation of the geometry. This option is recommended if you intend to import the IFC back into Archicad or another editing program to make further edits.

BREP Export geometry as separate BREP surfaces. Instead of describing the objects by its parameters such as length/witdth/height with surfaces generated as a result, each surface is described as a separate surface with a location in 3D. Objects can still contain multiple surfaces, but these will be loose surfaces. After exporting BREP surfaces have to individually be edited as parameters are no longer applied to the surface. With the BREP option exact surfaces are exported leaving no room for difference in interpretation of parameters between authoring tools. Surfaces are colored individually and will have the same color in Catenda Hub as they do in Archicad. Surface colors can be configured in the following menu:

`Options -> Element attributes -> Surfaces`

It can be good to configure all settings for a surface as they will be written into the IFC.

![](images/10-6-1-conversions-of-archicad-elements.png)

Surfaces in the Catenda 3D viewer have flat shading without a light source present. This means that values like Ambient, Attenuation, Shinyness, Emission and Specular are not interpreted when the surface is viewed in the Catenda 3D viewer. The following values are interpreted by Catenda when displaying the surface in the 3D viewer:

Surface color The color of the surface

Transmittance How much you can see through the object (Overrides the translucent opacity setting)

Diffuse How dark or bright the surface color is

**6.1.8 Define IFC model position by:** This option decides project location. It is important to agree on a common coordinate point to reference in the project already in the beginning changing it might mean that multiple consultants have to move their objects which is often not feasible towards the end of a project.

Survey Point and Project Origin - default With this option the distance from (0,0,0) to your model in Archicad will be the distance from (0,0,0 + coordinates of your survey point) to your model in Catenda Hub + the If you have set a project location your model will end up at those coordinates in Catenda Hub

Project Origin only With this option the distance from (0,0,0) to your model in Archicad will be the distance from (0,0,0) to your model in Catenda Hub.

Survey Point only With this option the distance from the survey point in Archicad to your models will be the distance from (0,0,0) to your model in Catenda Hub

## 7. **7. Hierarchical Archicad elements**

Export objects in a flat hierarchi or as nested subelements.

### 7.1 **7.1 Curtain Wall**

Convert to Single element Keep hierarchy - Default

### 7.2 **7.2 Stair**

Convert to Single element Keep hierarchy - Default

### 7.3 **7.3 Railing**

Convert to Single element - Default Keep hierarchy

## 8. **8. IFC Schema related options**

### 8.1 **8.1 Material preservation mode (IFC2x3 only)**

**8.1.1 Never explode elements, preservation is not guaranteed** With this option you will export the whole object as one object

**8.1.2 Explode only when necessary to preserve materials - Default** With this option you only export separate objects for each composite material if necessary

**8.1.3 Explode all elements into parts, preserver materials** With this option all objects are exported as separate objects for each material If you have a composite wall material this means that a separate object will be exported for each material. You often have a vapor barrier that is 1-5mm which will result in a very thin object. When objects are that thin geometry can be inaccurate. Problematic wall materials can look something like this:

![](images/11-8-1-material-preservation-mode-ifc2x3-only.png)

This can make it hard for software to cut holes through the surface as the inaccuracy makes it hard to pin down exactly where the hole is supposed to be. If you therefore notice that your openings are not being cut through it can help to turn this option on. Turning this option on will export the wall as one single object instead of many thin composite objects.

## 9. **9. Composite structures and Complex Profiles**

**9.1 Split complex Building Elements into parts** Here you can chose for what type of elements you want the composite element to be split and for which you do not want them to be split. If you choose this option you will not be able to make a choice for the material preservation mode.

## 10. **10. Property mapping**

Inside property mapping (File > IFC > Interoperability > Property Mapping) you can choose what kind of version of IFC you want to export. you have the standard IFC2x3 and the standard IFC4. You can also add psets to export with your IFC. If you do this you should make a duplicate of the IFC schema you choose.

![](images/12-10-property-mapping.png)

After you’ve made a duplicate of your standard IFC you can add the properties you want to that new preset by selecting the IFC schema and clicking on _Map IFC Properties for Export_.

![](images/13-10-property-mapping.png)

## 11. **11. Data conversion**

Under data conversion you select what kind of data in addition to geometry you want to get out of your IFC export. check the boxes of what you want to export. Element parameters reads the Archicad element parameter and converts it to IFC quantities or IFC properties. Depending on their type. By choosing this option you significantly increase the file size.

![](images/14-11-data-conversion.png)

IFC Base Quantities reads the parameters of size, area and volume. If you don’t check this box off you may have trouble importing your IFC to Catenda Hub.

## 12. **12. Unit Conversion**

Set the Length, Angle, Area, Volume, Currency and Time units for your export.
