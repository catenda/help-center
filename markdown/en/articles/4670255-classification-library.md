# Classification Library

Classification libraries are a simple and practical way of getting existing data into the BIM. They can be used to tag objects with information.

One example can be \<example with status of objects, ref table below>

User defined libraries can be uploaded as simple spreadsheets (csv). As long as the “code” is maintained, the linking between one or more library item(s) and the object(s) is maintained. If the string in the “sort” column is hierarchical, an item - subitem relation is created (so 1.1 will be a sub-item of 1).

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p>Sort (unique)</p></td><td><p>Code (unique)</p></td><td><p>Name (mandatory)</p></td><td><p>Description (optional)</p></td></tr><tr><td><p>1</p></td><td><p>S0</p></td><td><p>Not considered</p></td><td><p>desc</p></td></tr><tr><td><p>1.1</p></td><td><p>S01</p></td><td><p>Not considered sub 1</p></td><td><p><br/>​</p><p></p></td></tr><tr><td><p>1.1.1</p></td><td><p>S02</p></td><td><p>Not considered sub 1 sub</p></td><td><p><br/>​</p><p></p></td></tr><tr><td><p>1.2</p></td><td><p>S03</p></td><td><p>Not considered sub 2</p></td><td><p><br/>​</p><p></p></td></tr><tr><td><p>2</p></td><td><p>S5</p></td><td><p>Under programming</p></td><td><p>desc</p></td></tr><tr><td><p>3</p></td><td><p>S1</p></td><td><p>Under construction</p></td><td><p>desc</p></td></tr><tr><td><p>4</p></td><td><p>S3</p></td><td><p>Approved</p></td><td><p>desc</p></td></tr><tr><td><p>5</p></td><td><p>S4</p></td><td><p>Changes needed</p></td><td><p>desc</p></td></tr></tbody></table></div>

Start with creating a new classification library and save it. Then go to the library and upload a CSV by pressing the + button and choosing what CSV to upload.

In the example below a library containing several statuses has been used to mark/tag an object with how far in the production process the window currently is.

To assign a library item from a user definable library to all the selected objects, click the checkbox to the left of the content item. This works the same way as with tagging documents to objects. The content that has been assigned to an object is shown on the inspect tab.

All library content and attributes added in Catenda Hub can be merged into the IFC-files if you choose to export the project.

![mceclip0.png](https://raw.githubusercontent.com/catenda/help-center/main/images/b6bxj0dm/01-intro.png)
