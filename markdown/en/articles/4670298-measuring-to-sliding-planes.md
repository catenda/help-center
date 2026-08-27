# Measuring to sliding planes

This article describes how the measuring tools in the 3D viewer can be used to not only just measure on objects but also measure on elements from sliding planes like grids or alignments. This is what it can look like after measurement tools like after measuring tools like the tape measure, point measure and laser measure are used to measure between sliding plane annotation lines, sliding plane surfaces and objects from models.

![](images/01-intro.png)

## 1. **Getting started with measuring to sliding planes**

Follow these steps to get started with measuring to sliding planes.

### 1.1 **Previewing sliding planes**

Sliding planes that can be measured to are defined in the IFC models that are made available in the project. If models with sliding planes are available the [sliding plane dropdown](https://support.catenda.com/en/articles/4670327-sliding-plane-dropdown) becomes visible in the top right of the [3D viewer](https://support.catenda.com/en/articles/8227211-3d-viewer) and can look something like this:

![Sliding plane dropdown in the 3D viewer](images/02-previewing-sliding-planes.png)

Prepare the sliding planes to measure to by opening the dropdown and clicking on the eye button to preview the annotation lines of a grid or an alignment.

![](images/03-previewing-sliding-planes.png)

### 1.2 **Recommended settings for measuring**

Making accurate measurements is vital for avoiding miscommunication in the project. It can therefore be a good idea to do a review settings before getting started with measuring.

**3D viewer settings** The 3D viewer settings dropdown can be found with the gear icon towards the top right of the 3D viewer:

![](images/04-recommended-settings-for-measuring.png)

Since sliding plane lines include thin annotation lines and text which are often sensitive to clean rendering in a 3D environment the following [3D viewer settings](https://support.catenda.com/en/articles/5784718-3d-viewer-settings#h_16d759320b) are recommended for making the measuring experience as good as possible.

**3D viewer settings - Display quality** Standard quality is recommended as the high quality changes the ratio of pixels displayed by Catenda vs pixels visible on screen which can have a negative effect on making accurate measurements.

**3D viewer settings - Anti-aliasing** It is recommended to change this setting from the default FXAA setting to at least 2x MSAA or more. Thin lines in 3D are often a challenge to display as the more diagonal a thin line is the more jagged the edges become. Changing the anti-aliasing setting does not have an effect on the accuracy of the measurement but it can help with seeing the lines better as the jagged edges can make it so that that thin lines become so thin that they become hard to visualize.

**3D viewer settings - Ground elevation** Especially when attempting to measure to an annotation line below ground it can be a good idea to either choose an environment without a ground plane or move the ground plane to down below the elevation of the sliding plane.

![](images/05-recommended-settings-for-measuring.png)

**Application software recommendation** Regardless of which [zoom scale](https://support.catenda.com/en/articles/13927149-application-software-recommendation?q=3d+v) is configured in the browser that is used for measuring in the 3D viewer it is recommended to not change the browser zoom scale while measuring as this can contribute to reducing the accuracy of the measurement. Set the browser to the preferred zoom scale and be careful to refresh the page after every zoom scale change even if the zoom scale change was done on another tab or if it was changed back to what it was initially.

## 2. **Measuring to sliding plane annotation lines**

Each of the measuring tools can be used on sliding plane annotation lines.

### 2.1 **Snapping behavior**

When hovering near an annotation line with the bullseye activated the bullseye will snap to an annotation line. When snapping to the end of an annotation line the center of the bullseye becomes green. When snapping to the middle of an annotation line the center of the bullseye becomes red.

<img alt="" src="images/inline-96b1b8f9c6c8.png" width="290"/> --- <img alt="" src="images/inline-d30d54cd3f18.png" width="290"/>

### 2.2 **Laser measure on annotation lines**

This is what it can look like when using the laser measure tool on the annotation line of a grid.

![](images/06-laser-measure-on-annotation-lines.png)

**Measuring vertically and horizontically along the annotation line segment** Notice that the bullseye looks flat in the vertical direction when hovering an annotation line. When measuring annotation lines it is the vertical plane along the annotation line that is measured. The green line is the horizontal line on this plane and the red line is the vertical line on this plane and follows the annotation line segment

Both for the vertical measurement line (red) and for the measurement line horizontically along the segment (green) the measurement line behaves differently depending on objects that are encountered. If there are objects in one direction along the measurement line, a line measuring the distance to the nearest object is displayed. If there are objects in both directions along the measurement line a line measuring the distance between those objects is displayed.

**Measuring horizontically at the oblique angle to the annotation segment** The blue line is the line that can be observed as giubg at an oblique angle to the annotation segment that is measured horizontically. If there are objects in one direction along the measurement line, a line measuring the distance to the nearest object is displayed. If there are objects in both directions lines measuring the distances to the nearest object in each direction are displayed as this line intersects the annotation line itself and measures to it.

**Missing measurement** If objects are missing in any of the measurement directions coordinates are additionally displayed like with the point measure.

![](images/07-laser-measure-on-annotation-lines.png)

### 2.3 **Tape measure on annotation lines**

The tape measure tool can be used to measure both from object to annotation line or from one annotation line to another line. For example, find the distance between two grid lines by measuring from a point on a grid line to a point on another grid line.

![](images/08-tape-measure-on-annotation-lines.png)

### 2.4 **Point measure on annotation lines**

The point measure can be used on annotation lines just like any of the other measuring tools.

## 3. **Measuring to sliding plane surfaces**

Enable the sliding plane surface pressing the white circle where the anntoation line circle is. Multiple sliding plane surfaces can be opened at once. Laser measurements that have been made on objects can be extended expand until the annotation line. Then use the “Laser measure” or the “Tape measure” to measure to sliding plane surfaces that are enabled.

![](images/09-measuring-to-sliding-plane-surfaces.gif)
