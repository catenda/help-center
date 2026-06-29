# 3D Viewer settings

The 3D viewer settings can be found in the top right of the [3D viewer](https://support.catenda.com/en/articles/8227211-3d-viewer).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/01-intro.png)

> **Note:** Be sure the hardware and sofware Catenda is opened on are configured [as recommended](https://support.catenda.com/en/articles/6921941-hardware-recommendation) as this can have an effect on how the viewer is displayed.

## 1. **Enabling the 3D viewer**

The 3D viewer can be opened in any of the following ways: Enable the 3D panel with the panel buttons on the top right (Shift + 2).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/02-enabling-the-3d-viewer.png)

Enable a 3D model from the Dashboard page.

Enable a 3D model from the viewer column in the models table. (Above image)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/03-enabling-the-3d-viewer.png)

Select models on the models page and use the 3D action with selected models on the models page.

Enable a 3D document from the viewer column in the documents table on the documents page. Click on the gear icon to show the **3D viewer settings.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/04-enabling-the-3d-viewer.png)

## 2. **Rendering**

This is what the rendering menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/05-rendering.png)

### 2.1 **Show spaces**

_Default off_ - [Enable and disable spaces](https://support.catenda.com/en/articles/4670315-how-can-i-show-spaces-in-catenda-hub). Spaces are still selectable in the 2D viewer if they are in the model.

### 2.2 **Display quality**

The ratio between the amount of pixels that the viewport says it is displaying and the amount of pixels that are physically part of your screen is often the same. In that case the display quality option does not have much of a difference. If the amount of pixels that the viewport says it has and the amount of pixels where the viewport is being displayed on a screen is different the display quality can affect the sharpness of the image. For screens of the following types the ratio between the amount of pixels that the viewport says it has and the amount of pixels the screen actually has can be different:

- Mobile devices
- Display technologies that affect pixel density like Apple Retina.
- High-DPI displays

> **Note:** Be sure the hardware and sofware Catenda is opened on are configured [as recommended](https://support.catenda.com/en/articles/6921941-hardware-recommendation) as this can have an effect on the pixellation of the viewer.

**Standard quality** With the standard display quality the pixels that the viewport says it has are the same amount of physical pixels that display the viewport on the screen. For screens that offer to display the viewport across more physical pixels than the viewport says it has, this setting can make the image appear less precise. This mode is faster and less demanding on your device.

**High quality** With the high display quality the viewport is displayed across the full amount of physical pixels that are available on the part of the screen that displays the viewport. For screens that allow for the viewport to be displayed across more pixels than it says i has this provides the best visual quality but can be more demanding on performance.

### 2.3 **Anti-aliasing**

Pixel accuracy in the smoothing of diagonal lines in order of accuracy. Note that the more accurate the harder it will be to display for the system.

- FXAA
- 2x MSAA
- 4x MSAA
- 8x MSAA

> **Note:** Be sure the hardware and sofware Catenda is opened on are configured [as recommended](https://support.catenda.com/en/articles/6921941-hardware-recommendation) as this can have an effect on the accuracy of diagonal lines.

### 2.4 **Incremental rendering**

While rotating non vital objects like glass in windows and small fittings are temporarily hidden to improve performance. This makes it possible to rotate in huge models with little lag. When many objects are loaded into the 3D viewer this option is a must.

### 2.5 **Ambient shadows**

When this option is enabled, shadows with a radius of about 5 cm are displayed between the overlap of objects. Be sure to have your objects at real-world scale for this to have a better effect. With large surfaces like where a wall meets a floor this is not that visible until the camera moves close to the intersection. With small geometry like furniture, steel beams and metal fittings this is a gamechanger. This option typically has little effect on performance.

### 2.6 **Extended view range**

With massive models that are multiple kilometers long the objects often end up outside of the default clipping distance of 2 kilometers. When the model is enabled the camera attempts to position itself far enough away to display everything and if the objects are far enough away they might get clipped and nothing will show until the camera moves closer to the objects. With this option objects up to 50 kilometers away from the camera become visible! Note that this can affect performance. In infrastructure projects this option is often a must!

### 2.7 **Translucent opacity**

_5% Default_ - How much you can see through objects that are translucent

### 2.8 **Point cloud settings**

Point budget: _1000000 Default_ - How many points of the point cloud can be displayed at once.  The default value is more than enough for most point clouds but the setting is there should more be needed.

## 3. **Navigation**

This is what the navigation menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/06-navigation.png)

### 3.1 **Walk mode**

_1.6 Meters Default_ - Binds the viewer to the ground beneath when you are walking through the model with walkthrough mode. Allows you to walk up stairs.

### 3.2 **Walk speed**

_3 m/s Default_ - How fast the viewer moves in walkthrough mode. For reference a table of general speeds is included below.

### 3.3 **Elevation speed**

_1.5 m/s Default_ - Vertical movement speed when moving up and down using X and C.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><p><b>Method of travel</b></p></td><td style="background-color: #e3e7fa80;"><p><b>Typical speed (m/s)</b></p></td><td style="background-color: #e3e7fa80;"><p><b>Typical speed (mph)</b></p></td></tr><tr><td><p>Walking</p></td><td><p>1.5</p></td><td><p>3.4</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Default</p></td><td style="background-color: #e8e8e880;"><p>3</p></td><td style="background-color: #e8e8e880;"><p>6.7</p></td></tr><tr><td><p>Running</p></td><td><p>5</p></td><td><p>11</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Cycling</p></td><td style="background-color: #e8e8e880;"><p>7</p></td><td style="background-color: #e8e8e880;"><p>15</p></td></tr><tr><td><p>Car</p></td><td><p>13 - 30</p></td><td><p>29 - 67</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Train</p></td><td style="background-color: #e8e8e880;"><p>56</p></td><td style="background-color: #e8e8e880;"><p>125</p></td></tr><tr><td><p>Plane</p></td><td><p>250</p></td><td><p>560</p></td></tr></tbody></table></div>

### 3.4 **Rotation speed**

_40°/s Default_ - How fast the viewer rotates around the camera when you drag on the screen

### 3.5 **View angle**

_60° Default_ - This setting can be good to make bigger in interior spaces like small rooms so you can see more. It can also be good to limit this setting in models with large distances 2 KM (1.2 miles) and more as it will allow you to more precisely see objects that are further away.

### 3.6 **Reset navigation settings**

Set all navigation settings back to their default position

## 4. **Environment**

This is what the environment menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/07-environment.png)

### 4.1 **Environment setting**

The chosen environment settings decides which sky is displayed when looking up and which ground is displayed when looking down. Note that the horizon is often more pronounced when the perspective view option is chosen as with the orthagonal viewpoint the horizon is infinitely far away so it is only seen when the camera faces exactly in the horizontal direction.

**Clear** With the clear setting a clear sky when looking up and a grassy ground plane when looking down are displayed in the background of the viewport.

**Partly Cloudy** With the partly cloudy setting a cloudy sky when looking up and a grassy ground plane when looking down are displayed in the background of the viewport.

**Neutral** With the neutral setting light gray sky when looking up and a dark gray ground plane when looking down are displayed in the background of the viewport. This setting is great for models that have light colors and are hard to distinguish from a light background.

**None** With the none setting a gradient that transitions from a light green sky when looking up into a white ground plane when looking down are displayed in the background of the viewport.

### 4.2 **Ground elevation**

The ground elevation options are grayed out for the None setting as this does not have a ground plane. In settings where the ground plane is displayed a surface becomes visible at a set elvation that receives shadows from objects that are loaded into the 3D viewer.

_Below model -_ Default With this option the ground plane surface is displayed at a height of 0 meters above sea level.

_At elevation_ With this option the ground plane surface can be moved up with positive values and down with negative values. This is great in situations where the surface is clipping through a basement of for objects that are otherwise below sea level.
