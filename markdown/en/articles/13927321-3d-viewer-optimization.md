# 3D Viewer optimization

Catenda Hub is optimized to run most models smoothly in the 3D viewer. Large projects, very detailed models and point clouds can still put a heavy load on the computer. The strategies in this article keep the 3D viewer fast and responsive in those cases.

## 1. **Many objects**

Of course loading less models will mean less objects and therefore better performance Turning on [incremental rendering](https://intercom.help/bimsync-arena/en/articles/5784718-3d-viewer-settings#:~:text=Incremental%20rendering%3A) speeds up rotating around models with a lot of geometry as not all of the objects have to be loaded when rotating. As a final step you can make a [query](https://intercom.help/bimsync-arena/en/articles/4854514-queries) of the section you are working in. Usually when you section off part of the model the objects are still in memory and just hidden. With a query these objects are completely removed and it will therefore be easier to work with the model. Keep in mind that you will not be able to use property libraries with queries because not all objects are loaded.

## 2. **Heavy objects**

Every surface in a 3D model is drawn as triangles. A detailed object, such as a stair railing or a curved facade panel, can hold hundreds of thousands of them. A handful of such objects can slow down navigation in the whole model.

Two scripts for the browser console show where the triangles are. Both read the models that are loaded in the 3D viewer at that moment.

### 2.1 **Open the browser console**

1. Open the models in the 3D viewer.
2. Press **F12** (**Cmd+Option+I** on a Mac) to open the browser's developer tools, and select the **Console** tab.
3. Paste the script and press **Enter**.

> **Note:** The console may refuse a pasted script until it is unlocked. To unlock it, type `allow pasting` into the console by hand, press **Enter**, and paste the script again.

### 2.2 **Count the triangles**

This script adds up the triangles of every loaded object and prints the total in the console. It counts all loaded models together, so to compare models, load one model at a time and run the script for each.

```
triangles = 0
$('#viewer').viewer("each", function(id) {
$(this).viewer("objectInfo", id, function(info) {
  triangles += info[0].triangleCount
});
})
console.log("Total number of triangles =  "  + triangles);
```

### 2.3 **Find the heaviest objects**

This script finds the objects with more than 80,000 triangles and shows exactly which objects they are. It prints the id and triangle count of each one in the console. It also hides all other objects and moves the camera to the ones it found, so only the heavy objects are left in view. To use another limit, change the number on the first line, `big = 80000`.

```
big = 80000;
biggies = [];
$('#viewer').viewer("each", function(id) {
$(this).viewer("objectInfo", id, function(info) {
  if (info[0].triangleCount >big) {
    console.log("id " + info[0].id + " triangleCount = " + info[0].triangleCount);
    biggies.push(info[0].id);
  } 
});
})
$('#viewer').viewer('hideAll').viewer('show', biggies);
$('#viewer').viewer('lookAt', biggies);
$('#viewer').viewer('select', bimsync.selection);
```

### 2.4 **Reduce the triangle count**

An IFC model is usually an exchange model. It shows the other parties in the construction project what needs to be built. It does not need the micrometer precision of an engineering model. A model with every screw drawn down to its thread is very detailed, and that detail slows down the 3D viewer for everyone who opens it.

That level of detail can stay in the authoring tool. Many authoring tools can export an object with a lower level of detail, for example as a simple box in the IFC file. In Revit, a lower level of detail in the IFC export cuts the number of triangles drastically while the model looks almost the same. Read more about [the level of detail setting in the Revit IFC export](https://support.catenda.com/en/articles/4670341-revit-ifc-export-manual#level-of-detail).

Until a lighter revision is uploaded, the strategies under [Many objects](#many-objects) help keep the 3D viewer responsive.

## 3. **Point clouds**

If you are using [fixed point size](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-catenda-hub#:~:text=Adaptive%20(default)%2C%20or-,Fixed%20size,-.%20The%20slider%20below) you might run into low fps when a lot of points have been loaded in. You might also experience points taking longer to load when the memory budget of your system is reached. Points closest to the camera are loaded first so if you want to load points at a specific location it is better to navigate to that position and then turn on the point cloud so it starts loading points there first. To combat hitting the memory limit and getting lower fps you can lower the [point budget](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-catenda-hub#:~:text=with%20your%20PC.-,Point%20Budget%3A,-Using%20the%20viewer) so fewer points are loaded in.

## 4. **Browser zoom scale**

Make sure the zoom scale of your browser is set correctly as a large zoom scale may make some menus so large that others are hidden. While graphics defined by width and hight might scale with the browser scale, graphics that are defined by pixels may become more pixellated when the zoom scale is increased. Small zoom scale can result in graphics becoming so small that they are invisible and precisly displaying scaled down resources can be more demanding on the device.
