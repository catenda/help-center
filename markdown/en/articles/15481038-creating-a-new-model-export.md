# Creating a New Model Export

Click on the green plus button on the top right of the [model export page](https://support.catenda.com/en/articles/4670280-model-export) to create a new model export. There are four steps to creating a new model export. This is what the first step in the model export creation process can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/01-intro.png)

## **Step 1 - Select models and revisons**

In the first step the revision from each of the models that should be included in the export can be specified. Start by selecting a model that should be included by checking its checkbox. Once the model is selected the revision that is to be included in this export can be selected.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/02-step-1-select-models-and-revisons.png)

In the first step of the model export the models that should be included in the export can be selected.

> **Note 1:** If the model does not have revisions that can be exported the checkbox will be grayed out. **Note 2:** A model revision has to successfully be processed and not be withdrawn to be selectable.

### **Navigation**

As soon as one or more models are selected and revisions are specified the step will say Done. Go to the next step by clicking Next: Merge options towards the bottom right of the page.

## **Step 2 - Merge options**

In the second step items that are linked to model content in the project can be merged into the ifc files they are linked to when exported. This is what the merge options page can look like in a new project.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/03-step-2-merge-options.png)

Uncheck the checkboxes to deselect any project libraries that should not be merged into the model files of the export.

In a new project the available libraries are:

### **Documents**

Select "Documents" to insert Catenda url links to any project documents that have been linked to objects into the exported ifc files.

### **Links**

Select "Links" to insert user defined links from the links library that have been linked to objects into the exported ifc files.

### **User defined libraries**

Any libraries that have been created in the project are displayed by the library name here. This i what it can look like after adding a few libraries

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/04-user-defined-libraries.png)

Supported library types include:

**Document libraries such as Dropbox or SharePoint libraries** Sign in with Dropbox or SharePoint and link the items from your external library to model objects to have Catenda links to these library items included in the exported ifc.

**Links library** Include saved URL links from the Links library in your IFC export by linking them to objects from selected export models.

**Classification library** Create a classification library by uploading a CSV. Link items from the CSV in the classification library to model objects. Classification libraries appear by the name of the library in the merge options list. When the checkbox for a classification library is selected any classification library items from the CSV that have been linked to objects in selected export models are merged into the exported IFC. Objects with such links in the IFC receive a link to the classification library item on Catenda.

### **Libraries that are not supported**

Libraries that are not supported include libraries that rely on dynamic content like:

**Lookup libraries** These look up selected objects on the internt

**Property value libraries** These classify model objects based on a selected property

**Embedded classification libraries** These classify objects based on an external classification library that is already specified in the ifc.

### **Navigation**

After configuring the selected libraries click "Next: Add name and comment" to proceed to the next step.

## **Step 3 - Add name and comment**

In the third step items the export can be given a name and a comment can be added. This is what the add name and comment step can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/05-step-3-add-name-and-comment.png)

**Name** The name will be pre-filled with Model export and the date and time of the export. This name will also be the filename of the downloaded zip.

**Comment** Export comments are optional and only appear on Catenda. The comment can give the project participants some information about what this export is about.

## **Step 4 - Sharing options**

In the fourth and last step the shareing option can be chosen. This is what the sharing options step can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/06-step-4-sharing-options.png)

### **Shared export**

Shared exports are visible to all project participants

### **Private export**

Private exports only visible to the export creator.

### **Navigation**

Click on export to start the processing of this export. After finalizing the export the model export page is displayed where progress on the processing of the export can be seen. The processing of the export happens completely in the background and it is safe to completely close the browser at this point. When an export has finished processing a notification is sent out to the export creator that their export is ready to be downloaded.
