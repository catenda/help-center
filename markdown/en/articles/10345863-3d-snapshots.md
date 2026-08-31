# 3D Snapshots

Snapshots describe a place and time in 3D. They can be used for showing people what you are looking at as they will be able to recreate the same views not only within Catenda Hub but also within their environment. Snapshots can be recreated by playing them both in Catenda Hub and in our plugins.

This is what a snapshot can look like in the [comment of a topic](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_1ba7f8873f) or in a [bookmark](https://support.catenda.com/en/articles/8471481-bookmark#h_5c9944a45e). <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/inline-a76bead96c41.png" width="365.48223350253795"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/inline-5a151da0b11e.png" width="272.72727272727275"/>
The topic might have an annotation on top of the image and the buttons look different.
While snapshots are used in different ways in topic comments and bookmarks, their functionality is the same.

## 1. **Snapshot image**

### 1.1 **Topic comment snapshot image**

Clicking anywhere on the image of a comment snapshot will [pop-out](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_e36d14edc8) the image allowing you to see a its contents in a larger format and download it after it has been submitted. After creating the snapshot and before adding it to the topic you will be able to add annotations to it.

### 1.2 **Bookmark snapshot image**

Clicking anywhere on the image of a bookmark snapshot will recreate the viewpoint in the 3D viewer according to how the bookmarks was configured when it was last updated.

### 1.3 **Snapshot image attachment**

The size of the image that is attached is dependent on the size of the viewer and the browser zoom percentage.

Snapshots are the best way to create high quality images or renderings from the Catenda Hub viewer for the following reasons:

- Snapshot images can be downloaded from the [attachment pop-out](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_e36d14edc8) in a topic comment.
- Snapshot images can have higher resolutions than just taking a screenshot from the viewer.

The largest image we have seen being generated so far has been 6417x11113 pixels. To make a snapshot this big the following settings were used:

- 4K monitor display.
- Content panel and 3D panel visible.
- Content panel as small as possible.
- Browser in Fullscreen.
- Browser scale 10%
- Display scale in Windows 100%

Your pc might not be able to handle these settings so please tweak them to fit your specifications.

## 2. **Viewpoint settings**

The following settings will be remembered when a snapshot is created. These settings will automatically be configured when the snapshot is re-created.

### 2.1 **Objects**

Objects that have the same ID and were that were selected, hidden or isolated will be selected hidden or isolated when the snapshot is recreated.

**New objects in revisions** If you recreate a snapshot with the latest revisions there might be objects with new ids that were not part of the model yet when the snapshot was created.

Selected Only the objects that were slected when the snapshot was created will be selected.

Hidden If more than half of the objects in a model are visible objects with new ids will be hidden.

> **Note:** That means that if you add a new model with the model picker in a topic comment snapshot where more than half of the objects in a model are visible the added model might be completely hidden. To view the objects with new ids you can use show all to display the model after recreating the snapshot.

If less than half of the objects in a model are visible objects with new ids will be shown.

Isolated Only the objects that were isolated when the snapshot was created will be isolated. Objects with new ids will be show, but not highlighted.

**Selections** If [selections](https://support.catenda.com/en/articles/8238584-information-panel#h_d713a0abb1) have been made in the [information panel](https://support.catenda.com/en/articles/8238584-information-panel) these will be remembered when the viewpoint is played. This makes it easy to select different sets of objects. This also allows you to give a set of objects a color that is different from the default color of the objects when you normally open them from the models section.

_Select objects button_ In a topic comment you will see an icon that displays how many objects are configured to be selected in a snapshot.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/01-objects.png)

Click this button to select the configured objects in the 3D viewer. If you have the 3D viewer open, this button will be in the hamburger menu.

### 2.2 **Clipping planes**

Clipping planes configured in the snapshot will be active when the snapshot is re-created.

### 2.3 **Revision selector**

Which 2D and 3D views have been turned on or off in the [revision selector](https://support.catenda.com/en/articles/8227211-3d-viewer#h_6c32b713c9). Point cloud settings will be reproduced.

### 2.4 **Grid dropdown**

Grids that have been turned on in the [grid dropdown](https://support.catenda.com/en/articles/8227211-3d-viewer#h_b735587e69) will be displayed.

### 2.5 **Visibility dropdown**

Options configured with the [visibility dropdown](https://support.catenda.com/en/articles/8227211-3d-viewer#h_376dfb4859) will be reproduced.

### 2.6 **Camera options**

The camera in the 3D viewer will move to the location and viewing angle set in the snapshot. The camera type set in the [camera options](https://support.catenda.com/en/articles/8227211-3d-viewer#h_02072804a5) will be reproduced. The shading options set in the [camera options](https://support.catenda.com/en/articles/8227211-3d-viewer#h_02072804a5) will be reproduced.

### 2.7 **3D settings**

Settings like field of view or incremental rendering set in the [3D settings](https://support.catenda.com/en/articles/5784718-3d-viewer-settings) will be reproduced.

## 3. **Recreate snapshot**

In Catenda Hub the snapshot will move the camera to the right place in our viewer. In the plugins the viewer of the host software will display.

### 3.1 **Recreate snapshot with latest revisions**

Bookmark - Topic comment <p class="intercom-align-center no-margin"><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/inline-63d2b110333a.png" width="60"/> - <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/inline-a628f96ebc54.png" width="104.55445544554455"/></p>
Recreate the snapshot with the latest revisions of the models and documents that are configured in the snapshot.
If new revisions of the models or files that are part of the bookmark are uploaded, the resulting view in the 3D viewer might look slightly different than on the picture.
If the bookmark has any shared revisions, the latest published revision will be displayed.

### 3.2 **Recreate snapshot with original revisions**

Bookmark - Topic comment <p class="intercom-align-center no-margin"><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/inline-127de38bdf57.png" width="60"/> - <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/inline-244412c15b6d.png" width="104.72727272727272"/></p>
The snapshot will be recreated with the model and document revisions that were configured when the snapshot was created.
Both published and shared revisions of models and documents will be displayed with this option.

## 4. **Copying and favoriting snapshots**

**Duplicate topic comment snapshot** To copy a snapshot simply play the snapshot and create a new bookmark or 3D snapshot in a comment. With a bookmark it is better to use the + button so you can keep track of which bookmark you duplicated.

**Copy bookmark to my bookmarks**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/02-copying-and-favoriting-snapshots.png)

If this bookmark was created by another member you will see a +. This allows you to create your own copy of the bookmark that you can edit and filter on. If you have already copied this bookmark this button will be grayed out and you will be able to open your version [below](https://support.catenda.com/en/articles/8471481-bookmark#h_5c9944a45e). By copying a bookmark you can keep track of which bookmark you copied.

**Favorite bookmark**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/03-copying-and-favoriting-snapshots.png)

Starring the image by clicking the star on the top left of the image will add this bookmark to your dashboard. _Access required:_ Bookmark creator

## 5. **Set camera position**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/04-set-camera-position.png)

This button sets the camera position and viewing angle that is configured in the snapshot. After playing the snapshot you might want to move around in 3D. You can then use this button to snap back to the viewing position configured in the snapshot.

> **Note:** Note: If you have the 3D viewer open, this button will be in the hamburger menu of the topic comment snapshot.

## 6. **Update snapshot**

**Updating bookmark snapshot**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/05-update-snapshot.png)

If you want to make changes to your snapshot you can play it, change the configuration, and update the snapshot with this button.

Examples where this can be useful:

- Add or remove a model from the bookmark
- Keep the bookmark linked to the bookmark it was copied from.
- Keep the link to the bookmark intact.

_Access required:_ Snapshot creator

**Updating a topic comment snapshot**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/06-update-snapshot.png)

The models button shows how many Catenda models are linked to the snapshot. While it is possible to edit the text in a comment it is not possible to change or remove the image attachment from a comment without deleting the whole comment. What you can do is change which models will be enabled when the topic is re-created. _Access required:_ Project administrator

When a BCF topic is imported the ids of the models in the project is compared with the ids of the models that are configured in the snapshot. Only the models with ids that are present at the time of import will be loaded in the 3D viewer when the snapshot is re-created.

If two models have the same id, only the first one is enabled. To make sure that the right models are enabled it is important that they each have their own id. If you are exporting different multiple files from your authoring software it can be a good idea to use a unique id for each different model you wish to export to. Here is an article from BuildingSMART that describes how this is done in Revit [https://user.buildingsmart.org/knowledge-base/ifcproject/](https://user.buildingsmart.org/knowledge-base/ifcproject/) Be sure to keep track of which id you used for which model so future topics that get created recognize it.

In some cases you might want to change the models that are loaded in the Catenda 3D viewer when the snapshot is recreated:

- Your model might be imported after you import the topic.
- Your the objects in your model might contain the right ids, but the model itself might have the wrong id.
- The topic was created for a specific model, but you want to see context

To change which models get loaded click the models button to open the model select dialogue. The model select dialogue can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/07-update-snapshot.png)

**3D** The models with the active 3D button are the models that are currently enabled in the 3D viewer. In order to easily add/remove a set of models you can make a bookmark, recreate a snapshot, go to the snapshot you want to reconfigure and click on save in the model select dialogue.

**Checkbox** Add or remove models by checking/unchecking them and click the save button to save a new configuration.

**Load models** Load the models from the snapshot in addition to the models that already exist in the viewer.

> **Note 1:** In this menu you only link the snapshot to Catenda models. It does not change the content of the BCF. **Note 2:** Depending of the object visibility settings of the snapshot added models might be completely hidden. Even if they are not visible you should see that they are loaded when the topic is played.

## 7. **Snapshot access**

### 7.1 **Topic comment snapshot access**

Members with read access to the topic board will be able to see the snapshot. Topic PDF export will include the snapshot image. Topic BCF export will include the snapshot image and configuration.

### 7.2 **Bookmarks sharing**

The [sharing](https://support.catenda.com/en/articles/8471481-bookmark#h_5c9944a45e) configuration for the bookmark

### 7.3 **Private**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/08-private.png)

_Bookmark visibility:_ Only you

### 7.4 **Shared**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/09-shared.png)

_Bookmark visibility:_ All project members, can be shared with external people via public link

## 8. **Public link to bookmark**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/10-public-link-to-bookmark.png)

If a [public link](https://support.catenda.com/en/articles/8471481-bookmark#h_b148931acf) has been enabled for this bookmark you can click this button to open the public link in a new tab.

## 9. **Deleting a snapshot**

### 9.1 **Deleting a topic comment snapshot**

A snapshot that is attached to a topic comment cannot be deleted from the comment. To remove the snapshot from one of your comments you will have to delete the whole comment. _Access required:_ Comment creator

To remove the snapshot in a comment created by someone else the topic will have to be moved to an archived topic board. _Access required:_ Project administrator

Or the topic could be deleted. _Access required:_ Full access to the topic board

### 9.2 **Deleting a bookmark snapshot**

A bookmark has to have a snapshot connected to it and cannot be deleted. To delete the whole bookmark, click the delete bookmark in the action menu on the top right. _Access required:_ Bookmark creator
