# 2D viewer appearance

There are several ways to configure the content of the 2D viewer to suit your needs.

## 1. **Viewer objects**

### 1.1 **Highlighting selected objects**

The lines that are generated for each storey when the model is processed stay linked to the 3D object that was sliced through when the lines were generated.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/01-highlighting-selected-objects.png)

When an object is selected in the 3D viewer, if a storey of that model is enabled in the 2D viewer that was generated on the height where this object exists, the object will also be highlighted in the 2D viewer. Object slices are generated at one meters above the height that is set for each of the storeys in the ifc file are generated. Elevation offsets like the elevation in IFCSite are not taken into account.

In the example below the storey "Ground Floor" is at 0 meters. Walls with a base height of 0 and different top heights are displayed.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/02-highlighting-selected-objects.png)

As can be seen only the walls that are 1 meter and above are displayed in the 2D viewer.

### 1.2 **Door swings**

Door swings are specified in the IFC file. You can see how this works in the following BuildingSMART articles: [IFC 2x3](https://standards.buildingsmart.org/IFC/RELEASE/IFC2x/FINAL/HTML/ifcsharedbldgelements/lexical/ifcdoorstyle.html) [IFC 4](https://standards.buildingsmart.org/IFC/RELEASE/IFC4_1/FINAL/HTML/schema/ifcsharedbldgelements/lexical/ifcdoortypeoperationenum.htm) If no door swing is specified the door will swing open to the right.

## 2. **Drawing as underlay**

It is possible to underlay a PDF from the documents section with the [storey configurator](https://support.catenda.com/en/articles/6921756-storey-configurator-page). This is especially helpful if there are objects above or below the height where the 3D objects are sliced through that do not show up in the 2D viewer. Examples of these are: Ducts and pipes, Electrical outlets, Ceiling plans, Road and rail

## 3. **Markers in the 2D viewer**

With [markers enabled](https://support.catenda.com/en/articles/4854537-2d-viewer#h_381a9d4098) any topics that have a specified location on the story of a an IFC or a configured building are displayed. This is what a 2D view with different markers can look like in the browser.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/03-markers-in-the-2d-viewer.png)

Hovering over the marker will show you the topic number and title. Clicking on the marker will let you open up the topic in the topic board. Click [here](https://support.catenda.com/en/articles/4854523-2d-location-of-issues) to read more about the 2D location of topics.

## 4. **Room Labels in the 2D Viewer**

The room labels displayed in the center of rooms within the 2D viewer are determined using the data available in IFC room objects. These room objects include both short and long names, which can be configured to define the label format via the **Room name format** setting in Catenda. Ensure that both room numbers and areas are accurately included in the IFC data, as missing attributes may restrict the display of desired room labels.

### 4.1 Troubleshooting Room Labels:

- Verify that the IFC data file includes necessary attributes like room numbers and areas.
- Check and adjust the "Room name format" settings to align with your preferred label configurations. You can find the setting in the 2D viewer 'setting-wheel' in the right corner.
