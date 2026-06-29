# Inspect menu

The inspect menu can be found as the first menu in the [information panel](https://support.catenda.com/en/articles/8238584-information-panel).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/01-intro.png)

Select an object in the [3D viewer](https://support.catenda.com/en/articles/8227211-3d-viewer) or [tree panel](https://intercom.help/bimsync-arena/en/articles/4670290-trees-panel) to get started. The properties and related information are displayed in the inspect menu. After selecting an object, the inspect panel can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/02-intro.png)

Selecting more than one object shows common topics, properties, quantities, materials or libraries. Your preference for which menu you have opened in the inspect menu will be remembered across projects and sessions. That means that, no matter if you have closed the browser and re-opened or which project you are in, the same menus will always be open when you select an object.

## 1. **Identification**

In the identification menu you will see all the identification data for the selected object. Identification will only be displayed for one object at a time.

### 1.1 **Name**

The name of the object

### 1.2 **Tag**

The tag of the object

### 1.3 **Entity**

The entity type of the object

### 1.4 **GUID**

The GUID of the object. This code is unique for each object and can be used to identify the object throughout revisions of the IFC file.

### 1.5 **Type**

The type of the object. Each type has its own unique GUID. Two objects that look like they have the same type might therefore actually have different types with different GUIDs connected to them. Click the type to select all objects of that type. Doing so will activate the type tree in the [trees panel](https://intercom.help/bimsync-arena/en/articles/4670290-trees-panel) where you can see the type you have selected in the list of types for that model.

### 1.6 **Predefined type**

The predefined type tells you about what kind of type you are dealing with

### 1.7 **Containment**

If your object is part of a hierarchy you will see the parent node in the hierarchy here. Click on the parent node to select all objects contained by that parent node. Doing so will activate the containment tree in the [trees panel](https://intercom.help/bimsync-arena/en/articles/4670290-trees-panel) where you can see the containment node in the hierarchy of the objects in your model.

## 2. **Alignments**

With an alignment selected in the trees panel, click on Display all segments to open the alignments table.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/03-alignments.png)

This is what the alignments table can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/04-alignments.png)

Click [here](https://support.catenda.com/en/articles/11748020-tables-on-catenda) to read more about tables on Catenda

## 3. **Topics**

In the topics menu you will be able to see if there are any open or closed topics that are [related to](https://support.catenda.com/en/articles/8053299-right-menu-in-a-topic#h_758f17abbc) your selected object(s). The topics menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/05-topics.png)

### 3.1 **New topic**

Click the + button to create a new topic in the current topic board. If you create a topic like this, your selected objects will automatically be related to the topic so you will not have to manually link them.

Clicking on open, closed, your profile picture or the unassigned picture will filter the all topic boards according to what you clicked on.

### 3.2 **Open topics**

The amount of open topics that your selected object is related to

### 3.3 **Closed**

The amount of closed topics that your selected object is related to

### 3.4 **Profile picture**

The amount of open topics that are related to your selected objects that you have been assigned to

### 3.5 **Unassigned**

The amount of open topics that are related to your selected objects without an assignee

## 4. **Properties, Quantities and Materials**

Here you can find the properties the selected objects have in common. The properties menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/06-properties-quantities-and-materials.png)

### 4.1 **Filter empty values button**

Click the filter icon to hide properties that do not have any values.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/07-filter-empty-values-button.png)

### 4.2 **Display type value button**

If your selected object(s) have any properties inherited from the object type you will see the display type value button.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/08-display-type-value-button.png)

Activate this button to show the properties that were inherited from the type. When this button is activated you will see the type value like so:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/09-display-type-value-button.png)

### 4.3 **Property values**

All common property-value pairs of the selected objects will be displayed. If values are only present in one of the objects, that property will only be displayed if the object with that value is selected.

### 4.4 **Property sets**

In the property list you can either find separate properties or property sets (PSets) that contain several properties each with its own value. As you see in the image above, the first 4 properties were separate properties followed by three property sets with properties in them.

**Expanding/retracting property sets** Property sets can be expanded or retracted by clicking on the arrow next to its name. As long as your selected objects have property set your expand/retract preference will be remembered, but as soon as you select an object without the property set it will be reset.

### 4.5 **Quantities**

Here you can find the quantities the selected objects have in common

### 4.6 **Materials**

Here you can find the materials the selected objects have in common

## 5. **Libraries**

If your selected object(s) are [linked to any documents](https://support.catenda.com/en/articles/8302244-right-menu-in-a-document#h_d0769e55eb) or library items you will be able to see them here. The libraries menu can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/10-libraries.png)

You can click on the number to the right of these items to get the linked documents/library items shown in a view in the content panel. If you for example have a floor plan in the documents section linked to a wall object you will be able to click on documents here to find the document in the document section.

## 6. **Model**

If all your objects belong to one model you will be able to see information about the model revision here. This information includes:

**Model image**

**Model name**

**Revision number**

**Date and time of publishing of the revision**

**Model revision publisher**

## 7. **Owner History**

If there is information about the owner history of the revision in its IFC file, you will be able to find it displayed here. This information can include:

**The person that originally exported the model**

**The authoring tool that was used** _When the model was exported _You might also be able to see if someone edited the model between export from authoring tool and import in Catenda Hub.
