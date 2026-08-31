# Information Panel

You will be able to find the Information panel as one of the four main panels that can be opened on the top right of your screen. You can either press the i-icon to open this panel or you can press [shift+4](https://support.catenda.com/en/articles/4670267-summary-of-most-important-shortcuts-and-basic-controls#:~:text=Inspect%20panel-,Shift%20%2B%204,-Show/hide%20last).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/01-intro.png)

In the information panel you will be able to find the following sections:

## 1. **Inspect**

This lets you see the information about you selected objects. Click [here](https://support.catenda.com/en/articles/4670285-inspect-panel) to read more about the inspect panel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/02-inspect.png)

## 2. **Quantity Take-Off**

This lets you make and export a list of objects and calculate the sums of values connected to the different selected objects.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/03-quantity-take-off.png)

Click [here](https://support.catenda.com/en/articles/6673929-quantity-take-off-qto) to read more about the Quantity Take-Off

## 3. **4D**

In this section you will be able to track the progress of models with the 4th dimension. Time. If your IFC file contains an IFCWORKPLAN you will be able to see a time schedule for the objects in your file.

> **Note:** 4D in Catenda is only available for ifc files exported from [SYNCHRO](https://www.bentley.com/software/synchro/). These files can include an IfcWorkPlan and IfcTasks

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/04-4d.png)

At the start of the timeframe all objects will be hidden and depending on how far time has come objects with the right setting will appear. Here is an example of what the 4D section can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/05-4d.png)

### 3.1 **4D columns**

## 4. - The task number

_Task ID_ - The ID of the task

_Name_ - The name of the task

_Duration_ - The duration of the task

**Start** The start date of the task This is when the object will appear in 3D. The objects will also appear selected Between the start date and the finish date of a task the task bar will be orange. Click on the clock icon next to the date to jump to this point in time.

Finish The finish date of the task - After the finish date the objects will stay in 3D but will be deselected. After this date the task bar will be green. Click on the clock icon next to the date to jump to this point in time.

**Products** The objects connected to this task The objects can be isolated and selected by clicking on isolate and select.

### 4.1 **4D bookmarks**

It is possible to make a bookmark where the 4D workplan has been enabled. If access this bookmark you will see what objects have been made visible to date according to the plan. In Catenda Hub you will be able to adjust the timescale to whatever time you like. If you share the bookmark externally, the external party accessing the bookmark will only see the objects that have been made visible so far.

### 4.2 **How do I know if my IFC has 4D information in it?**

If your ifc has IFCTASKs in it you will be able to see these in the 4D panel. If your ifc has IFCRELASSIGNSTOPROCESSes in it these tasks will also be connected to objects. A program you use to see if these are present is [OpenIFCViewer](https://openifcviewer.com/). Here you can check your model's statistics

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/06-how-do-i-know-if-my-ifc-has-4d-information-in-it.png)

Where you can find the entity in the statistics panel:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/07-how-do-i-know-if-my-ifc-has-4d-information-in-it.png)

## 5. **Selections**

This lets you create a set of objects which can then be styled and colorized.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/08-selections.png)

Towards the top of the Selection menu you will see how many items you currently have selected in the 3D viewer and tree panel. Selections can be saved by making a [snapshot](https://support.catenda.com/en/articles/8053352-issue-body#h_1ba7f8873f) or a [bookmark](https://support.catenda.com/en/articles/8471481-bookmark) and playing it later. Because selections are stored in the snapshot of a topic they can be imported and exported to other programs through BCF. An example of this is that topics with selections from the selection basket that are synchronized through the BCF live connector in Solibri will contain selection data when the snapshot is played.

### 5.1 **New selection**

After having selected some object you will be able click on New selection

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/09-new-selection.png)

### 5.2 **Pencil icon**

Click the pencil icon the change the name of your selection

### 5.3 **Object amount**

After the pencil icon you will see the amount of objects currently in this selection.

### 5.4 **Update**

Click the update button to set the objects in the selection to the objects you currently have selected in the 3D viewer and tree panel.

### 5.5 **Object picker**

Click on the select button to select the items in your selection

### 5.6 **Color**

With the color button you can change the color of the objects in your selection. The color picker can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/10-color.png)

Select color with the color slider, the palette or specify your desired color with a hex code. The second slider decides the transparency where 1 is 100% opaque and 0 is 100% transparent. Towards the bottom right you will see the resulting color.

### 5.7 **Delete**

Click on the delete button to delete this selection

### 5.8 **Expand/retract**

Expand the selection to see which objects are part of the selection.

## 6. **Measurements**

This lets you see what measurements have been made in the 3D viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/11-measurements.png)

Click [here](https://support.catenda.com/en/articles/4670294-measuring-features) to read more about measurements
