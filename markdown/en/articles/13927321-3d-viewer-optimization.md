# 3D Viewer optimization

Although Catenda Hub is well optimized and can run most models some users might want to set themselves up for success as best as possible.

This article includes information abot the following topics:

Here are some strategies that can be used to optimize your workflow in Catenda Hub

## 1. **Many objects**

Of course loading less models will mean less objects and therefore better performance Turning on [incremental rendering](https://intercom.help/bimsync-arena/en/articles/5784718-3d-viewer-settings#:~:text=Incremental%20rendering%3A) speeds up rotating around models with a lot of geometry as not all of the objects have to be loaded when rotating. As a final step you can make a [query](https://intercom.help/bimsync-arena/en/articles/4854514-queries) of the section you are working in. Usually when you section off part of the model the objects are still in memory and just hidden. With a query these objects are completely removed and it will therefore be easier to work with the model. Keep in mind that you will not be able to use property libraries with queries because not all objects are loaded.

## 2. **Point clouds**

If you are using [fixed point size](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=Adaptive%20(default)%2C%20or-,Fixed%20size,-.%20The%20slider%20below) you might run into low fps when a lot of points have been loaded in. You might also experience points taking longer to load when the memory budget of your system is reached. Points closest to the camera are loaded first so if you want to load points at a specific location it is better to navigate to that position and then turn on the point cloud so it starts loading points there first. To combat hitting the memory limit and getting lower fps you can lower the [point budget](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=with%20your%20PC.-,Point%20Budget%3A,-Using%20the%20viewer) so fewer points are loaded in.

## 3. **Browser zoom scale**

Make sure the zoom scale of your browser is set correctly as a large zoom scale may make some menus so large that others are hidden. While graphics defined by width and hight might scale with the browser scale, graphics that are defined by pixels may become more pixellated when the zoom scale is increased. Small zoom scale can result in graphics becoming so small that they are invisible and precisly displaying scaled down resources can be more demanding on the device.
