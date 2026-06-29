# 3D location of models

## 1. **Exporting with the same coordinates**

In authoring platforms you can export with different coordinates. All coordinates work fine with Catenda Hub. It is recommended that everyone in the project uses the same coordinate system to ensure that objects do not end up far away from each other and users do not wonder why they see some objects while the others are hidden while really they are just very, very far away.

## 2. **Objects far away from origin**

Compared to other authoring platforms Catenda hub does not have problems with precision when objects are far away from 0. The model location specified in the IFC file is used to decide where in 3D the model exists. The scene (size of what area is loaded in the 3D viewer) is only as big as the objects that are in it and does not have to include the origin point (0,0,0) This makes it so you can easily zoom in on objects without having to calculate how far away they are in relation to the origin.

## 3. **Objects far away from other objects**

If you have objects that are more than 10000 KM away from each other you can run into trouble because the scene gets very large. If you make a horizontal clipping plane it will clip the entire scene and will become sensitive when moved. If a model is therefore accidentally imported with the wrong coordinates and ends up very far away you might want to transform it. The models will still work fine by itself but together with other models that are very far away you can run into trouble.

## 4. **Transforming the location of a model**

It is possible to transform the 3D location of a model on the model overview page if you have it loaded in 3D. This lets you move the model in 3D after it is imported to Catenda Hub. This movement is only visual in Catenda Hub. If the IFC is downloaded it will be back on its original location. This method is only recommended to temporarily transform the model while you wait on an ifc file that has the correct location. This is because the some functions will not work properly with transformed models like 2D viewer sections, queries and issue snapshots. Measurements are not affected and will be accurate if the model is moved to the right place. You can find more information about how to do this [here](https://support.catenda.com/en/articles/4670270-model-overview-page#h_c10dbce6c8)
