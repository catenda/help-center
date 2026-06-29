# Sliding plane dropdown

If there are models in the project that contain sliding planes the grid dropdown will appear towards the top left of the [3D viewer](https://support.catenda.com/en/articles/8227211-3d-viewer#h_2eec7c411b).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/01-intro.png)

After clicking on the the sliding plane dropdown planes from all the models in the project will start loading.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/02-intro.png)

This is what the grid dropdown can look once it has loaded:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/03-intro.png)

## 1. **Grids**

Grids are a type of sliding plane that is often used in residential, commercial and industrial construction which often go hand in hand with infrastructure and civil construction projects. If any model in the project contains an IfcGrid in its latest revision it will be displayed in the sliding plane menu. The first planes that are displayed in the sliding plane dropdown are grids. Grids are separated by the different models they are from. Models can contain one or more grids that contains different axes. What grids are exported depends on the exporter of the authoring solution, but often a separate grid is exported for each storey of the model. For each grid the name of the IfcStorey that the grid is on is displayed. These same storeys can also be found in the storey menu of the 2D viewer. The name of the model the grid is from and the revision number it is in are displayed. Each grid also has an eye button.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/04-grids.png)

Click on the eye to display the grid in the 3D viewer. When the grid has loaded in the 3D viewer the eye icon will be highlighted green. To the right of the grid a show axes dropdown then becomes available.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/05-grids.png)

Expand the show axes dropdown for better control of each of the axes. Here you will see each axis by name with two buttons.

### 1.1 **Grid plane**

The first button will activate the grid pane for that grid. This is what grids can look like when their grid planes are activated.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/06-grid-plane.png)

Click on the annotation circle at the end of a grid line in the 3D viewer to enable and disable the grid plane.

### 1.2 **Clip along grid**

The second button creates a clipping plane along the grid.

### 1.3 **Measure to grids**

Click [here](https://support.catenda.com/en/articles/4670298-measuring-to-grids) to read more about measuring to different grids.

## 2. **Alignments**

Alignments are a type of sliding plane that is often used in the infrastructure and civil construction but have been seen to be used in residential, commercial and industrial construction as well. If any model in the project contains an IfcAlignment in its latest revision it will be displayed in the sliding plane menu. This is what alignments can look like in the sliding plane menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/07-alignments.png)

For each alignment the name of the alignment is displayed along with the name of the model it is from and its revision number. Click on the eye to enable the alignment in 3D.

### 2.1 **Alignment plane**

Click on the plane icon to enable the alignment plane. Select the alignment plane to see information about its different segments in the inspect menu.

### 2.2 **Clip along alignment**

Click on the clipping plane icon to create a clipping plane along the alignment Alignments clipping planes work similar to Grids clipping plane. Instead of following the line of an axis the plane follows perpendicularly along the curvature of the alignment segments so you are alway at an oblique angle to the curvature you are at. When an alignment clipping plane is activated you might be looking at its front but after dragging it along a curve you might be looking at its back.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/inline-8520a612b6e1.png" width="300"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/inline-2e858207316f.png" width="300"/>
