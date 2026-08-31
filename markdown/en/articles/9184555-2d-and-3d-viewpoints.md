# 2D and 3D Viewpoints

2D and 3D viewpoints can be added as a [comment of a topic](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_f76b44d3ca). Snapshots are versatile ways of communicating about 2D and 3D information as they not only contain visual information but can be used to describe a place and time in a document or model. The information that is saved in snapshots allows you to collaborate with 2D and 3D information as you will be able to play your snapshot in any of your BCF and IFC enabled services.

This is what a 3D snapshot can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/01-intro.png)

The snapshot below had the following setup when the snapshot was taken: The snapshot was recreated with original revisions. The 7 model-documents connected to the snapshot were loaded in the 3D viewer. The 5 selected objects from the model-documents were selected 2 documents that are not connected to models were loaded of which one ifc and one point cloud. 2D snapshots will have the same buttons but with an image of the 2D viewer attached.

## 1. **Creating a snapshot**

If you have a model loaded in 3D you can click the plus bottom to the left of the topic comment field to attach a 3D snapshot to your comment. If you have the 2D viewer opened up you can click the plus bottom to the left of the topic comment field to attach a 2D snapshot to your comment. A snapshot is automatically created if you have loaded something in 2D or 3D and you make a new topic. Click [here](https://support.catenda.com/en/articles/10345863-snapshots) to read more about snapshots.

## 2. **Viewer images**

Snapshots are the best way to create high quality images or renderings from the Catenda Hub viewer for the following reasons:

- Snapshot images can be downloaded from the [attachment pop-out](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_e36d14edc8).
- Snapshot images can have higher resolutions than just taking a screenshot from the viewer.
- Snapshot images have transparent backgrounds. With 3D snapshots the image only contains pixels where there are objects in 3D. With 2D snapshots the image only contains pixels where there are lines in 2D.

### 2.1 **Image size**

The size of the image that is attached is dependent on the size of the viewer and the browser zoom percentage. The amount of pixels in a snapshot image depends on the size of the viewer, the browser zoom percentage and your operating system display scale. The largest image I have been able to generate so far has been 6417 pixels by 11113 pixels. To make a snapshot this big I had the following settings:

- 4K monitor display.
- Content panel and 3D panel visible.
- Content panel as small as possible.
- Browser in Fullscreen.
- Browser scale 10%
- Display scale in Windows 100%

These settings are very heavy on the system and your pc might not be able to handle this so you might have to tweak the these settings to fit your specifications.

## 3. **Play icons**

Snapshots contain information about the time when you created the snapshot.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/02-play-icons.png)

If an object was hidden at the time of creation, the object with that ID will be hidden when the snapshot is recreated. If an object was isolated, the object with that ID will be shown while objects that are not isolated will be hidden. This also reflects to any objects with new ids that might be added to newer revisions of the model.

### 3.1 **Recreate snapshot**

Snapshots are great for showing people what you are looking at as they will be able to recreate the same views not only within Catenda Hub but also within their environment.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/03-recreate-snapshot.png)

Snapshots can be recreated by playing them both in Catenda Hub and in our plugins. In Catenda Hub the snapshot will move the camera to the right place in our viewer. In the plugins the viewer of the host software will display.

- By clicking this button the snapshot will be recreated with the same model and latest revisions loaded in the 3D viewer.
- The connected point cloud or ifc documents will be loaded
- The camera in the 3D viewer will move to the location set in the snapshot.
- The clipping planes from the snapshot will be re-created
- The objects that were selected in the snapshot will be selected
- The colors that were set in selections will receive their specified colors

### 3.2 **Recreate snapshot with original revisions**

Click this button to recreate the snapshot with the original model.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/04-recreate-snapshot-with-original-revisions.png)

The model revisions that were active in the 3D viewer at the time of the creation of the snapshot are loaded into the 3D viewer when this buttin is clicked.

## 4. **Content icons**

On the bottom right of the snapshot you will find icons that contain information about the contents of the snapshot.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/05-content-icons.png)

If the content panel is made small you might find some of these content icons in the action menu:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/06-content-icons.png)

The action menu can be found towards the bottom right of the snapshot where there is not enough space to displaye all content icons.

### 4.1 **Model picker**

If the 3D viewer is open the model load menu will be available

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/07-model-picker.png)

- The models that with a checkmark in this menu will be loaded when the snapshot is played.

    <div class="intercom-container"><img height="24" src="https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/inline-b248400a1359.png" style="height: auto;" width="30"/></div>

- The models with a plus in front of them will be added to the set of models with checkmark after hitting save.

    <div class="intercom-container"><img height="25" src="https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/inline-ca568d75479a.png" style="height: auto;" width="30"/></div>

- The models with a minus in front of them will be removed from the set of models with checkmark after hitting save.

    <div class="intercom-container"><img height="30" src="https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/inline-ff3494b6d9f8.png" style="height: auto;" width="30"/></div>

- Depending of the object visibility settings of the snapshot added models might be completely hidden. Even if they are not visible you should see that they are loaded when the topic is played.
- The models that are on when this menu is opened reflect the models that are currently loaded in the 3D viewer. In order to easily add/remove a set of models you can make a bookmark, play the bookmark, go to the snapshot, click on its action menu and hit save in the model load menu.
- If a model in your snapshot has the same IFCPROJECT GUID as a model in the models section the models will automatically be linked.

    Here is an article from BuildingSMART that describes how this is done in Revit [https://user.buildingsmart.org/knowledge-base/ifcproject/](https://user.buildingsmart.org/knowledge-base/ifcproject/)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/08-model-picker.png)

### 4.2 **Show selected objects**

Select the objects, that are selected in the snapshots, in the 3D viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/09-show-selected-objects.png)

Shows how many objects are selected in the snapshot

### 4.3 **Linked documents**

Click here to load the models from the snapshot in addition to the models that already exist in the viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/10-linked-documents.png)

Shows how many models are loaded in the snapshot.

### 4.4 **Set camera position**

Move the camera to the position of the snapshot in the 3D viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/11-set-camera-position.png)

If you have moved your 3D view after playing the snapshot you can click this button to get back to the position of the snapshot.

## 5. **Image pop-out**

If you hover over the image of a 2D or 3D snapshot a looking glass will appear. This can look like the snapshot below:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/12-image-pop-out.png)

After the snapshot is submitted, the image that is connected to it can be [popped-out](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_e36d14edc8) to see its contents in a larger format and download it.

## 6. **Deleting a snapshot**

It is not possible to delete a snapshot that is attached to a comment. If you want to remove the snapshot from the topic you will have to delete the whole comment.
