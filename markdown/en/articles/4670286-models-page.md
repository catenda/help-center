# Models page

On the models page all IFC documents that are linked to a model can be seen. Typically a model for each discipline can be found here. This is what the models page can look like:

![](images/01-intro.png)

The models page as the second page in the left navigation menu of a project. This page is part of the [content panel](https://support.catenda.com/en/articles/13141464-project-panels#h_74710f7a33).

![](images/02-intro.png)

## 1. **New item actions**

The new item actions can be found on the top right of the page.

![](images/03-new-item-actions.png)

See [here](https://support.catenda.com/en/articles/9431936-actions-on-the-models-page) for what the different actions do.

## 2. **Search or filter options**

See [here](https://support.catenda.com/en/articles/12129622-filtering-on-the-models-page) to find out how best to search or filter on the models page:

![](images/04-search-or-filter-options.png)

## 3. **Right menu**

If any model rows are selected in the models table, an info button will appear to the right of the search or filter bar. The info button can look something like this:

![](images/05-right-menu.png)

In the right menu you will be able to see information about:

- _Image_
- _Document link_
- _Status_
- _Labels_
- _Contributors_
- _Model transformation_

Click [here](https://support.catenda.com/en/articles/9673735-right-menu-on-the-models-page) to read more about the right menu on the models page.

## 4. **Models table**

The models table can look something like this:

![](images/06-models-table.png)

As soon as a model is created it will show up as a row in the models table. Click [here](https://support.catenda.com/en/articles/11748020-tables-on-catenda) to read more about how to work with tables in Catenda.

### 4.1 **Selected item actions**

After selecting a model row selected item actions appear towards the top of the models table. This is what the selected item actions menu can look like:

![](images/07-selected-item-actions.png)

Click [here](https://support.catenda.com/en/articles/9431936-models-page-actions#h_9c268c45ed) to see what the different selected item actions do.

### 4.2 **Row content**

When the table is first loaded in, up to 100 rows are displayed. If more than 100 rows are in the table scroll down to the bottom to load in the next 100 rows. Each model row is linked to a document on the documents page.

**Access** Model rows are displayed based on the access to the document that is linked to the model. _Access required -_ Read Opening the content of a model row opens the [model overview page](https://support.catenda.com/en/articles/4670270-model-page) of that model.

**2D and 3D buttons** For 2D, the 3D panel opens up and the first story of the latest revision of the model is loaded into the 2D viewer. For 3D, the 3D panel opens up and the latest revision of the model is loaded into 3D.

### 4.3 **Row content with status workflow - Draft revisions**

**Access** Model rows of models with only draft revisions have no 2D and 3D buttons as draft revisions cannot be loaded in 2D or 3D.

> **Note:** Draft revisions are not displayed on the [model overview page](https://support.catenda.com/en/articles/4670270-model-page).

**2D and 3D buttons** The 2D and 3D views of the latest published revision are opened even if there are more recent draft revisions.

### 4.4 **Row content with status workflow - Workspace tab**

**Access** Model rows are displayed based on the access to the document that is linked to the model. With access to viewing shared revisions, the latest revision is displayed. _Access required_ - Access to viewing shared revisions in the document

Without access to viewing shared revisions, the latest published revision is displayed. Even if there are more recent shared revisions. _Access required -_ Read access to the document

**2D and 3D buttons** The 2D and 3D views of the latest revision a user has access to is opened.

### 4.5 **Row content with status workflow - Published tab**

**Access** Model rows are displayed based on the access to the document that is linked to the model. _Access required -_ Read

**2D and 3D buttons** The 2D and 3D views of the latest published revision are opened even if there are more recent shared revisions.

### 4.6 **Columns**

Depending on if a single panel is opened or if multiple panels are opened different information can be displayed. Some columns in the table view of the topics page are enabled by default while others can be hidden and have to be enabled. Based on the configured column order the first columns are displayed. Based on the configured column width fewer or additional columns can be dsiplayed. The table might have to be scrolled sideways to display other enabled columns. Click [here](https://support.catenda.com/en/articles/11748020-tables-on-catenda) to learn more about how to work with tables.

The default order and visibility setting of the columns on the models page is as follows:

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><h3 id="h_ec767816e6"><b>Models table columns</b></h3></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Checkbox</i> - Default</p></td></tr><tr><td><p>Selecting models</p></td></tr><tr><td><p>Click on this column to add a model to your selection.</p><p>Click <a class="intercom-content-link" href="https://support.catenda.com/en/articles/11748020-tables-on-catenda">here</a> to learn more about how to select rows in a table.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Viewer - </i>Default</p></td></tr><tr><td><p>Loading buttons</p></td></tr><tr><td><p>If this is a new model and there are no public revisions yet this column will be empty.<br/>After importing a model it will start processing. You will see a gray exclamation mark.<br/>​ </p><p class="intercom-align-center"><img alt="Processing" src="images/inline-3e6946f641f0.png" width="229.375"/> / <img alt="" src="images/inline-674792760c64.png" width="40"/></p><p><br/>If the latest model revision has failed processing you will see a red exclamation mark.</p><p></p><p class="intercom-align-center"><img alt="Failed" src="images/inline-c21b804d9253.png" width="148.57142857142858"/> / <img alt="" src="images/inline-9c4222a08d15.png" width="39.583333333333336"/></p><p></p><p>Hover over the explanation mark to see which model has failed. Clicking on 3D will load the latest valid revision instead of the latest revision.<br/>If there are any public revisions you will see a 2D, 3D and zoom to extents button here to be used together with the <a class="intercom-content-link" href="https://support.catenda.com/en/articles/4854537-2d-viewer">2D viewer</a> and <a class="intercom-content-link" href="https://support.catenda.com/en/articles/8227211-3d-viewer">3D viewer</a>.</p><p></p><div class="intercom-container intercom-align-center"><img alt="2D 3D" src="images/inline-fe323db3ad4e.png" width="131"/></div><p></p><p><i>Access required:</i> Read access to the document model</p></td></tr><tr><td style="background-color: #feedaf80;"><p><b>Note1:</b> The zoom to extents button will be gray until you load the model in 3D.</p></td></tr><tr><td style="background-color: #feedaf80;"><p><b>Note2:</b> If there is an explanation mark on the 3D button and the 2D and 3D buttons are grayed out, hover over the explanation mark to see what is wrong.</p><p>You will still be able to open previous revision by clicking on the model name.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Short name</i> - Default</p></td></tr><tr><td><p>The name of the model</p></td></tr><tr><td style="background-color: #feedaf80;"><p><b>Note1:</b> The model name of the model can be different from the name of the document that is linked to the model or name of the revision.</p></td></tr><tr><td style="background-color: #feedaf80;"><p><b>Note2:</b> If you do not have access to the document that the model is linked to, you will not see its row in the models table. You will still be able to see its model name in the revision selector.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Document name</i></p></td></tr><tr><td><p>The name of the document-model linked to the model-document.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Revision </i>- Default</p></td></tr><tr><td><p>The amount of public revisions in the document-model</p></td></tr><tr><td><p>If a model has been added from the models page it will not have any revisions yet.<br/>Instead of a revision number you will see the following icon which you can click to upload the first revision.</p><p></p><div class="intercom-container intercom-align-center"><img src="images/inline-b5a2ae50489d.png" width="47"/></div><p></p></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Revision comment</i></p></td></tr><tr><td><p>The comment the revision was uploaded with (legacy only)</p></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Revision name</i></p></td></tr><tr><td><p>The name of the latest public document-model revision. Cannot be changed after upload.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Status</i> - Default</p></td></tr><tr><td><p>The status of the latest public document-model revision. Public statuses can be turned on in <a class="intercom-content-link" href="https://support.catenda.com/en/articles/7831371-document-settings">document settings</a>.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Size</i> - Default</p></td></tr><tr><td><p>The file size of the last public document-model revision</p></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Labels</i> - Default</p></td></tr><tr><td><p>The labels connected to the model-document.</p></td></tr><tr><td><p>A label can be applied after uploading the first revision.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Document created</i></p></td></tr><tr><td><p>The person that created the document-model and the date and time it was created.</p></td></tr><tr><td style="background-color: #e8e8e880;"><p><i>Published</i> - Default</p></td></tr><tr><td><p>The person that published the last published revision in the document-model and the date and time it was published.</p></td></tr></tbody></table></div>

## 5. **Sub pages**

As sub pages to the models page you will be able to find the following pages:

- [Bookmarks](https://support.catenda.com/en/articles/4670281-bookmarks)
- [Objects](https://support.catenda.com/en/articles/12352750-objects-page)
- [Storey Configurator](https://support.catenda.com/en/articles/6921756-storey-configurator-page)
