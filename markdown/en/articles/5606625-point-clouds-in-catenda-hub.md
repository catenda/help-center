# Point Clouds in Catenda Hub

> Discover how to benefit from laser scans and LIDAR technologies in Catenda Hub.

> **Note:** Download a sample file from [here](https://drive.google.com/file/d/1G8U916oihDl5qHrTfQaVHxDeLsbq1ulG/view?usp=sharing).

Pointcloud datasets (PC) can be visualiszed inside Catenda Hub Individual PC can be previewed inside the document area. Multiple PC can be loaded into the [3D viewer](https://support.catenda.com/en/articles/8227211-3d-viewer). In the 3D viewer, PC can be viewed together with other 3D documents formats like IFC models and GML files.

See below various settings to display your data:

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p>Adaptive - Sparse - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-05a450dc777f.png" style="height: auto;" width="3839"/></div></td><td><p>Adaptive - Dense - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-196a1135014a.png" style="height: auto;" width="3839"/></div></td></tr><tr><td><p>Fixed - Dense - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-66e21551bbef.png" style="height: auto;" width="3834"/></div></td><td><p>Fixed - Sparse - Intensity</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-4a2046c8eaf1.png" style="height: auto;" width="3839"/></div></td></tr></tbody></table></div>

## 1. **Document section preview**

PC data of the following two file formats can be previewed on Catenda.

- `*.e57`
- `*.las`

PC can be uploaded like any other document in the document section. For these two file formats files up to 25 GB files can be uploaded to the document section. Multiple files can be loaded in the document section and displayed together in the 3D viewer.

### 1.1 **Uploading PC data**

It is recommended to use the [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) or to compress your PC file to a zipped folder and use the [zip import](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) to upload your PC. These methods will help you save time as the upload file size will be smaller as well as minimise the risk of a network error as the file will be uploaded faster

After you upload a PC to the document section, the document preview will start processing. While the preview is processing you will see a gray bar towards the top of your document preview.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/01-uploading-pc-data.png)

The preview processing duration depends on the size of the PC. Processing takes 1 hour per GB but it might be more/less depending on the point cloud.

Once the preview has finished processing, click on the document to view your PC in the document preview:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/02-uploading-pc-data.png)

### 1.2 **Shared PC revisions**

If [revision publishing](https://support.catenda.com/en/articles/9874698-revision-publishing-iso-19650) has been activated for the project the point cloud will have been uploaded as a shared revision. Shared PC revisions can only be previewed in the documents section. To be able to load your PC in the 3D viewer the revision has to be published. Individual shared revisions can be published with the publish action in the right menu of the document preview. Multiple shared revisions can be published with the selected items action in the document structure. When you publish a revision, the preview for the published revision will start processing.

### 1.3 **Published PC revisions**

After the preview of a published PC revision has processed a 3D button will appear in the viewer column of the the documents table.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/03-br-published-pc-revisions.png)

The 3D button will load the latest published revision of the document in the 3D viewer.

If you have selected one or more documents with 3D documents like PC, IFC or GML documents you will also see the 3D documents action in the selected item action menu in the documents table. This way you can load the latest revisions of multiple 3D documents in the 3D viewer at once.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/04-br-published-pc-revisions.png)

In a document with at least one published PC revision that has finished processing you will be able to see the 3D action in the action menu towards the top right.

> **Note:** The 3D action will load the latest published revision of the document in the 3D viewer. Even if you are looking at a previous revision.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/05-br-published-pc-revisions.png)

## 2. **3D viewer preview**

After clicking the 3D button the PC points will start loading into the 3D viewer. The 3D view of a PC can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/06-3d-viewer-preview.png)

Towards the top of the 3D viewer a green loading bar can be seen. This loading bar indicates how many points have been loaded into the 3D viewer for the current camera position and angle. The loading bar might change if you rotate around as points might disappear from the view and get loaded out or more points come within range and start loading in.

And after some adjustments with zoom and positioning the PC preview can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/07-3d-viewer-preview.png)

## 3. **3D viewer settings**

In this section, we will look at the settings inside Catenda Hub that will allow you to get the best experience with your PC.

> **Note:** Before configuring the 3D viewer, please make sure the application Catenda is opened in is configured [as recommended](https://support.catenda.com/en/articles/6921941-hardware-recommendation).

Settings that can be used to configure point clouds are located in two places.

### 3.1 **1. Point Budget:**

The point budget can be configured in the [3D viewer settings](https://support.catenda.com/en/articles/5784718-3d-viewer-settings) which can be found in the gear icon towards the top right of the 3D Viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/08-1-point-budget.png)

The the 3D viewer settings menu, the point budget can be adjusted from 100,000 up to 10,000,000. Loading in more points can take more time and can demand more resourses from your system. By loading in more points the point cloud can be displayed in higher fidelity. See the same view with: 100,000 points

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/09-1-point-budget.png)

1,000,000 points

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/10-1-point-budget.png)

10,000,000 points

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/11-1-point-budget.png)

### 3.2 **2. Revision Selector, and individual PC settings:**

On the top left of the 3D viewer you will find the [Revision selector](https://support.catenda.com/en/articles/4670246-accepting-an-invitation-to-join-a-project).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/12-2-revision-selector-and-individual-pc-settings.png)

In [the models menu](https://support.catenda.com/en/articles/4670279-revision-selector#h_180a64490d) you will be able to find the individual [3D documents](https://support.catenda.com/en/articles/4670279-revision-selector#h_fce60074ef) that you have loaded into the 3D viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/13-2-revision-selector-and-individual-pc-settings.png)

Point clouds can be configured in the revision selector by clicking the gear icon.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/14-2-revision-selector-and-individual-pc-settings.png)

This is what the settings menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/15-2-revision-selector-and-individual-pc-settings.png)

_Attribute_ _RGBA_ - Default Display PC points with their colors

_Attribute Intensity_ The intensity option can be used when the points do not include colors. For example when the point cloud was captured in a tunnel or a dark room.

**Opacity** When models are displayed together with point clouds, it can be necessary to dim the points to have a better understanding of the viewpoint.

_Point size_ _Adaptive_ - Default The closer a point is to the camera, the larger it is. Points that are in view are loaded into memory. Points that move out of view are loaded out of memory.

> **Note:** Be sure the hardware and sofware Catenda is opened on are configured [as recommended](https://support.catenda.com/en/articles/6921941-hardware-recommendation) as this can have an effect on the type of point size loading your device is able to handle.

**Point size Fixed size** Points that have been loaded will stay in memory with this option. With many points you will notice that rotating might be delayed and movement can be slowed down as you start getting close to the amount of points that your system can handle. You might also notice that it will take longer and longer to load in new points as you get closer to the limit of your device. Points load closest to the camera first. Before loading the point cloud from the document section, be sure to therfore position the camera to where you want the points to load. If this is a camera position you plan to use more often with this point cloud consider making a bookmark or a snapshot in a topic which you can play to return to this position.

**Point density slider** The density slider helps you make the final setting. There is no rule for the correct value, it will depend on the data you upload (size of the dataset, point density, type of scan, etc...). Our advice: Load the point cloud, and after a brief moment, when enough points are displayed, adjust the settings if necessary.

[YouTube video](https://www.youtube.com/embed/n9pztkRPxoc?rel=0)
