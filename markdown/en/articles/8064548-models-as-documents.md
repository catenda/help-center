# Models as Documents

Previously it has been possible to upload IFC files to two separate places on Catenda Hub. With the _models as documents_ function these two locations for model files will be merged into one seamless function. If you make a model in the models section, a document will be linked and created in the documents section. If you upload an IFC document you can use the "make model" action button to link and create a model in the models section. With this function models in the models section can be handled like documents while models in the documents section can be handled just like models.

## 1. **Before/After migration - Main differences**

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e8e8e880; width: 126px;"><h1 id="h_3632d3cc1b"></h1></td><td style="background-color: #e8e8e880; width: 262px;"><h2 class="intercom-align-center" id="h_2093155130"><b>Before</b></h2></td><td style="background-color: #e8e8e880; width: 248px;"><h2 class="intercom-align-center" id="h_d5cfcbcb2d"><b>After</b></h2></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Main behavior</b></p></td><td style="width: 262px;"><p>Models existed only in the Model section. The user had to upload the same IFC file to both the Document and Model sections.</p></td><td style="width: 248px;"><p>Models are created from IFC files uploaded to the Document section, if the user requests it. The IFC file and its related model are then linked.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>User Interface</b></p></td><td style="width: 262px;"><p><b>Different</b> from the Document section and displayed less information, basically only a list of models.</p></td><td style="width: 248px;"><p><b>The same</b> as the Document section: a customisable table with related metadata.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Access Rights</b></p></td><td style="width: 262px;"><p><b>Could not be applied</b> to models</p></td><td style="width: 248px;"><p><b>Can be applied</b> to models from their related document in the document section</p></td></tr></tbody></table></div>

## 2. **Familiar but different**

Now that the two sections have been linked it is important to note that there are still some key differences between the models and the documents sections. In the models section you will be able to see all model-documents gathered in a list. Here you will see your model-documents in a way that is similar to how they will be used in the 3D viewer. In the documents section you will be able to see document-models in your document structure. Here you will see your document-models in a way that is similar to how they will be used in your common data environment. All models are linked to each their own document and features from both sections can be used in both the models section and in the documents section.

## 3. **Models section changes**

With models as documents, the models section has changed in appearance. Instead of seeing menu items for each model they will now appear in a searchable table.

In the models section you will be able to find the following changes:

### 3.1 **Model table**

The new models table can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/01-model-table.png)

### 3.2 **Columns**

The model list has columns which display most of the information you need to know about your models.

_Name_ The name of the model-document The model name is also the name you will see in the revision selector in the 3D view.

**Document name** The name of the document-model in the documents section

**Revision name** The name of the latest revision

### 3.3 **Access control**

If a model has been restricted for you in the documents section you neither see it in the documents section, the models table nor in the revision selector.

### 3.4 **Selecting table elements**

With the model table you can now select a range of models by holding shift. You can also add or remove models from your selection by holding control.

### 3.5 **Action buttons**

In the past, the only action that you could perform on selected models was the opening of these models in 3D. Now, you are able to download, remove and open the 2D view of your selected models. If you delete a model that is connected to a document, the document will loose the model connection, but the document will remain in the document section.

### 3.6 **Control access to document-models**

**Creating a model-document** If you make a model with the create model button in the models section you will be asked to select where you want the linked document-model to end up in the documents-section. In the create model dialogue you will also be able to give the model a name. The resulting linked document-model will have the same as the model when it is created. Catenda Hub will remember the folder you chose last and will automatically select it the next time you create a model-document.

If your project began without models as documents, a folder called 'Models' will have appeared in your folder structure. The models folder that appears contains all document-models that are linked to model-documents in the model section. Document-models can be moved out of this folder to anywhere in the documents section you have access. Document-models in the Models folder can also be deleted (and restored) if desired. The document-models do not have to be in the folder and the models folder can be deleted if needed.

**Creating a model-revision** To be able to upload new revisions to a model you now need at least write access to the document model. New revisions to the model can be added to the document and vice versa.

> **Note:** Revision comments have been disabled and can now optionally be enabled with [custom fields on revisions](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents).

**Downloading a model-revision** You need at least read access to the document-model to be able to download the model.

### 3.7 **Right information menu**

A right information menu will be available if a model is selected.

**Document field** In this menu you will see your model information as well as a gray field that links to the document-model in the document section that is linked to this model-document. Click on the document field to open the document-model that is linked to this model.

**Model labels** You can now also add labels to your models here.

**Model status** If statuses have been configured in document settings you will be able to configure a status for your model here.

**Model transformation** If you have opened this model in 3D, you will be able to configure model transformation here.

## 4. **Documents section changes**

While the visual changes are not as apparent as in the models section there are a few things that will change to the documents section when models as documents is activated. This is what the document-models can look like in the doucments section.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/02-documents-section-changes.png)

In the documents section you will be able to find the following changes:

### 4.1 **Model filter**

As soon as you have any models in the models section you will see a model filter appear in your filter menu. With this filter you can show/hide any document-models that have been created.

### 4.2 **Columns**

**Icon** You will be able to tell apart a document-model from a regular document by the model badge on the bottom right of the document-model icon.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/03-columns.png)

**Name** The name of the document

**Model name** The name of the model If your ifc document has not been linked to a model you you will see a create model button here.

**Revision name** The name of the latest revision in the model

**Viewer** A column with buttons to open each individual document-model in the 3D viewer. Opening document-models in the 3D viewer is only possible if the document has been linked to a model.

### 4.3 **Action buttons**

Download, delete or load the 2D/3D views of selected models in the respective viewer by selecting one or more models.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-9e345595c719.png" width="310"/>    <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-959af958f499.png" width="310"/>

This means that you can delete multiple models at once instead of one-by-one like before. If you delete a document that is connected to a model you will have to approve a warning that the model connected to the document will also be deleted.

> **Note:** This means you can delete a model without loosing the data. (Deleted documents can be recovered)

### 4.4 **Control access to model-documents**

**Creating document-models** To be able to upload new revisions to a model you now need at least write access to the document model. You do this by creating a model in the action menu of a document. After you do this you will see the document as a model in the models section. The model-document in the models section will have the same name as the document model although these can each be changed later while they stay linked. New revisions to the model can be added as revisions to the document and vice versa.

> **Note:** This means you can create models from multiple IFC files at the same time instead of having to upload them one by one

**Uploading revisions to document-models** You need at least write access to the document-model to be able to upload new revisions to the model. This means you can use the multi-upload feature to upload ifc files to multiple document-models at once

**Downloading document-models** You need at least read access to the document-model to be able to download the model. This means that you can configure access to allow the downloading of separate models instead of just all or no models.

### 4.5 **Discoverability**

Document-models can now be found in the documents section like any other document.

- Document-models can be structured in folders to make it easier to navigate to the right set of models.
- Labels can be added to document-models to find all document-models that belong to one type.
- [Custom fields can be added to folders](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) where documents are uploaded to search on metadata-values related to each document-model
- [Custom fields can be added to folders](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) where documents are uplaoded to be able to add information to each revision in each document model.

See [here](https://support.catenda.com/en/articles/8542598-structuring-documents#h_7838a63c73) for suggestions on how to structure your document-models so they are easy to find.

### 4.6 **Approve shared IFC files**

IFC files can now be uploaded as shared revisions so they can go through an approval process before they are published.

### 4.7 **Naming convention with document-models**

Names in the documents section often include compressed abbreviations to keep the document name short while showing some information about of what this document is about. The name of the document-model can therefore be different from the name of the model-document to keep it in line with the other documents in the documents section while maintaining an easy to read name to use in the 3D viewer in the models section. The document name of the document-model will be the name that is recognized when uploading documents to the documents section. If the name is similar to or the same as the document, a new revision will automatically be created just like with other documents.

Because document-models behave the same as regular models it is now possible to use the naming convention with document-models to ensure that the participants of your project give the right name to the document upon uploading.
