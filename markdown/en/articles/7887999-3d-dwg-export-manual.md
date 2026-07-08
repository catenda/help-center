# 3D DWG export manual

Programs that are able to export 3D DWGs to IFC are:

### **AutoCAD Architecture**

[Export menu](#export-menu)

### **AutoCAD MEP**

[Export menu](#export-menu)

### **AutoCAD Civil 3D**

[Export menu](#export-menu)

### **AutoCAD Plant 3D:**

If you are using AutoCAD Plant 3D you can install the object enabler for the version of Plant 3D that you are using. With the object enabler installed you can open your file in any of the above programs to export to IFC. If you do not have access to any of the software above you can try to use a third party plugin like: Codemill IFC Export for Autodesk® AutoCAD® Plant3D Although this plugin claims to also export IFC 4 which is not possible with the object enabler keep in mind that this is not an official exporter and there might be problems importing.

### **Revit**

It is possible to import a 3D DWG to Revit. Although Revit has a lot more options when it comes to exporting to IFC it is not ideal to export an imported 3D DWG to IFC. If you want to try to do this, the best way to do it is by importing the DWG to a family. If you try to import the DWG to a project you will see that some objects disappear if you explode the DWG. After importing the DWG to the family explode the family that the DWG has created. This is to make sure you can have separated objects in the IFC instead of one big object. Next load the family in a project and place it. You might not be able to select the family. This can be because you do not have the Select underlay elements checked in the dropdown menu under modify.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/01-revit.png)

With your placed family selected click on create parts in the top ribbon.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/02-revit.png)

You will now see that you are able to to select each part of the family individually in the project. Now you are ready to export your ifc by clicking on the export -> IFC in the top left menu. In the IFC export dialogue click on modify setup. In the modify setup dialogue navigate to the advanced tab. Here be sure to have Export parts as building elements checked.

### **Navisworks**

At the moment there is no official way to export to IFC from Navisworks. It is possible to install plugins to do this with varied results: Codemill IFC Exporter CellBIM for Excel and IFC Exporter Keep in mind that this is not an official exporter and there might be problems importing.

## 1. **Export menu**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/03-export-menu.png)

1. Project Number
1. Project Name
1. Saved in - Write the path to the file or click on browse to find the folder you want to save your IFC to
1. Select which drawing files you want to export to IFC
1. Options
    1. Header - Author, Organization etc.
        1. Select IFC Schema to export to - IFC 2x3 and IFC 4
    1. Objects - All
    1. View - Include all

> **Note:** Ifc 4x1 is with drawn by BuildingSMART and therefore also not supported by Catenda Hub. See [here](https://support.catenda.com/en/articles/4670320-what-file-types-does-catenda-support) what file types are supported in Catenda Hub

6\. Resource and Assignment

1. Resource - Right click to add resource person and organization
1. Assignment - Right click to add assigned person and organization
1. IfcBuilding - Choose what properties

Export - Click this button when you are ready to export your files
