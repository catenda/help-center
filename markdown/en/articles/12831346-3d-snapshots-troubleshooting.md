# 3D Snapshots - Troubleshooting

## 1. **Viewpoint settings**

### 1.1 **Objects**

Objects that have the same ID and were that were selected, hidden or isolated will be selected hidden or isolated when the snapshot is recreated. If two models share identical IfcProject GUIDs (Global Identifiers), conflicts might result in visibility issues, preventing Catenda Hub from determining which model elements should appear during the snapshot recreation.

### 1.2 **Hidden objects**

If more than half of the objects in a model are visible objects with new ids will be hidden.

That means that if you add a new model with the model picker in a topic comment snapshot where more than half of the objects in a model are visible the added model might be completely hidden. To view the objects with new ids you can use show all to display the model after recreating the snapshot. To troubleshoot and force any hidden models to become visible, you can use the "show all" option in the 3D Viewer. Right-click in the 3D view area, select "show all" from the context menu, and this should temporarily resolve visibility issues caused by configuration conflicts.

## 2. **Recreate snapshot**

When replaying a Topic’s 3D snapshot, certain models may fail to appear. This problem can stem from project issues such as duplicate IfcProject GUIDs. To resolve this, ensure each model in the project uses a unique identifier. Additionally, use the 'Show all' option in the 3D Viewer as a temporary solution.

### 2.1 **Snapshot model picker**

In this menu you only link the snapshot to Catenda models. If the right models were not automatically found they can manually be linked here. Even if multiple models have the same GUID you can select tho enable all of them instead of just the first one. It does not change the content of the BCF so the objects might still be hidden when opened in external tools.

Depending of the object visibility settings of the snapshot added models might be completely hidden. Open the revision selector or models page to see which models have the 3D buttton enabled to see which models are loaded into the 3D viewer after recreating the snapshot. Even though they might be loaded all objects from the model might be hidden. Use the show all action to reveal any hidden objects..

## 3. **BCF import of snapshot**

When a BCF topic is imported the ids of the models in the project are compared with the ids of the models that are configured in the snapshot. Only the models with ids that are present at the time of import will be loaded in the 3D viewer when the snapshot is re-created.

If two models have the same id, only the first one is enabled. To make sure that the right models are enabled it is important that they each have their own id.

If you are exporting different multiple files from your authoring software it can be a good idea to use a unique id for each different model you wish to export to. It is recommended that every model in the project is assigned a unique IfcProject GUID to avoid conflicts during snapshot recreation. This ensures that Catenda Hub can accurately display the configurations in the 3D viewer.

Here is an article from BuildingSMART that describes how this is done in Revit [https://user.buildingsmart.org/knowledge-base/ifcproject/](https://user.buildingsmart.org/knowledge-base/ifcproject/)

Be sure to keep track of which id that was used used for which model so future topics that get created recognize it.
