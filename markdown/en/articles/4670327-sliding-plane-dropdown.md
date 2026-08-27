# Sliding plane dropdown

If there are models in the project that contain grids, the sliding plane dropdown will appear towards the top left of the [3D viewer](https://support.catenda.com/en/articles/8227211-3d-viewer#h_2eec7c411b).

![](images/01-intro.png)

After clicking on the the sliding plane dropdown grids and alignments that are available in each of the models in the project start loading in.

![](images/02-intro.png)

Click on the eye icon of a grid to preview the annotation lines of each of the axes in the 3D viewer.

![](images/03-intro.png)

This article contains information about the following topics:

**Previewing annotations - Show axes**

## 1. **1. Sliding plane types**

There are two types of sliding planes that can be displayed

### 1.1 **1.1 Grids**

Grids are a type of sliding plane that is often used in residential, commercial and industrial construction which often go hand in hand with infrastructure and civil construction projects. If any model in the project contains an IfcGrid in its latest revision it will be displayed in the sliding plane menu. The first planes that are displayed in the sliding plane dropdown are grids. Grids are separated by the different models they are from. Models can contain one or more grids that contains different axes. What grids are exported depends on the exporter of the authoring solution, but often a separate grid is exported for each storey of the model. For each grid the name of the IfcStorey that the grid is on is displayed. These same storeys can also be found in the storey menu of the 2D viewer. The name of the model the grid is from and the revision number it is in are displayed.

### 1.2 **1.2 Alignments**

Alignments are a type of sliding plane that is often used in the infrastructure and civil construction but have been seen to be used in residential, commercial and industrial construction as well. If any model in the project contains an IfcAlignment in its latest revision it will be displayed in the sliding plane menu. This is what alignments can look like in the sliding plane menu.

![](images/04-1-2-alignments.png)

For each alignment the name of the alignment is displayed along with the name of the model it is from and its revision number.

## 2. **2. Preview annotation lines**

Each sliding plane has a preview button that looks like an eye.

![Sliding plane preview button Catend Hub for grids and alignments](images/05-2-preview-annotation-lines.png)

Click on the preview icon of a sliding plane to preview the annotation lines of the sliding plane in the 3D viewer. As soon as the preview icon is highlighted green the annotation lines of the selected sliding plane are visible in the 3D viewer.

**2.1 Sliding plane annotation line** A sliding plane annotation line consists of a continuous line with a circle and a letter on each end.

Annotation line circle selection Click on the annotation line circle on either end of an axis or alignment to enable the axis or alignment. The annotation line circle for enabled axes or alignments turns is highlighted when selected. After selecting an annotation line the preview plane that is connected to that axis or alignment is displayed as a transparent surface in the 3D viewer. Notice that once selected, the plane icon for that axis or alignment is also highlighted in green in the sliding plane dropdown.

Click on the annotation line circle again to deselect the annotation line and hide the plane.

Grid annotation line bounds For grids the annotation line is a single straitch, planar line that extends slightly past the bounds of the model at the height that is displayed in the sliding plane dropdown. For alignments the annotation line consists of mutliple straight or curved segments of which start, end coordinates, elevation and direction can be seen in the alignments menu in the information panel.

### 2.1 **2.2 Finding annotation lines**

As annotation lines have a 3D representaiton, make sure that they are not covered by objects from other models or that the ground elevation of the environment is below the annotation lines so they are not obscured.

![](images/06-2-2-finding-annotation-lines.png)

## 3. **3. Show axes**

To the right of a grid in the sliding plane dropdwn a show axes menu can be expanded.

![](images/07-3-show-axes.png)

Expand the show axes menu for better control of each of the axes. Here each axis can be seen by name and with its two sliding plane buttons.

## 4. **4. Sliding plane surface button**

After being enabled, the transparent sliding plane surface extends from the annotation line to the upper bounds of the model similar to a clipping plane surface. Unlike a clipping plane surface which looks similarly transparent and can be moved this is a transparent object that cannot be moved from its annotation line. Also unlike clipping plane surfaces it is possible to measure to sliding plane surfaces. Click [here](https://support.catenda.com/en/articles/4670298-measuring-to-grids) to read more about measuring to different sliding plane surfaces.

### 4.1 **4.1 Grid axis surface**

The first button activates the grid pane surface for that axis. This is what grids can look like when their axis surfaces are activated.

![](images/08-4-1-grid-axis-surface.png)

Click on the annotation circle at the end of a grid line in the 3D viewer to enable and disable the grid axis surface.

### 4.2 **4.2 Alignment surface**

Click on the plane icon to enable the alignment plane. Select the alignment plane to see information about its different segments in the inspect menu.

## 5. **5. Clip along sliding plane button**

### 5.1 **5.1 Clip along grid axis**

The second button for a grid axis in the expand axes menu for sliding plane dropdown creates a clipping plane along the grid axis. Drag an axis clipping plane to drag the clipping plane perpendicularly along the axis.

### 5.2 **5.2 Clip along alignment**

Click on the second button with the clipping plane icon to create a clipping plane along an alignment. Alignments clipping planes work similar to Grids clipping plane apart from the click and drag behavior. Instead of being dragged perpendicular to the axis, the alignment clipping plane surface follows curvature and directions of the segments in the alignment such that the plane is always at an oblique angle to the curvature at its placement along the alignment.

<p class="intercom-align-center no-margin"><img alt="" src="images/inline-8520a612b6e1.png" width="150"/> -> <img alt="" src="images/inline-2e858207316f.png" width="150"/></p>

### 5.3 **5.3 Clipping relative to the 3D camera**

With either sliding clipping plane, but especially with alignment clipping planes the bounds of the clipping plane surface may not be visible because it might be outside of the viewport of the camera or even completely behind the camera. If objects seem to disappear after dragging on the clipping plane it could be because the clipping plane is dragged behind the camera. In this situation it can often help to either flip the clipping plane with the flip button in the menu towards the bottom of the 3D viewer or to zoom out so the bounds of the clipping plane are visible.
