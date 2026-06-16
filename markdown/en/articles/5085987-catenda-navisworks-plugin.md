# Catenda Navisworks plugin

> **Note:** The install file for the plugin can be found in [this article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

The Catenda Navisworks plugin is a plugin that can be installed for Nemetchek Archicad.

With this plugin you will be able to collaborate on 3D viewpoints, topics and documents with the other members of the construction project.

The following topics will be described in this article:

**[About the plugin](#h_8a72136f58) - [Cloud-based Collaboration](#h_1af0b770a7) - [Open standards](#h_2d8c53dc33) - [Installation](#h_6eca1bb38f) - [Catenda Tab](#h_1d2922dba1) - [Settings](#h_f09dd864e2) - [Topic boards](#h_f09dd864e2) - [Topic](#h_f09dd864e2) - [Clashes](#h_f09dd864e2) - [Models](#h_f09dd864e2)**

## **About the plugin**

The Catenda Hub add-in for Autodesk® Navisworks® is the perfect tool for projects collaborating in Catenda Hub. All your topics are synchronized in real-time between Navisworks and Catenda Hub, letting you create, access, share, and communicate topics. The topic format is BCF so that the topics can be shared across any BCF enabled BIM software or platform.

This add-in allows you to visualize, create, and edit topics seamlessly from within Navisworks. You can also download and federate the IFC model stored in Catenda Hub to your local client.

### **Features include:**

- Access to all your Catenda projects
- Filter and manage topics across topic boards
- Create new topics directly from Navis Works
- Locate topics in your Navisworks model
- Create a new 3D view for each comment
- Create BCF topics from clashes found using the Clash detective
- Assign topics to other project members
- Change topic status and other properties

## **Cloud-based Collaboration**

Catenda Hub brings your construction data to life in a cloud-based collaboration platform spanning the full building life cycle. Catenda manages your project information from the outset to handover and beyond, ensuring data and knowledge retention across all project phases.

## **Open standards**

Catenda Hub is a BIM collaboration tool with support for all of the buildingSMART standards (IFC, bSDD, BCF). It comes with a range of APIs for easy implementation into your own software.

[YouTube video](https://www.youtube.com/embed/osHul8oKysE?rel=0)

## **Installation**

When the Catenda Navisworks plugin is installed on Windows its installation files will appear in the following folder.

`C:\\ProgramData\\Autodesk\\ApplicationPlugins\\Catenda.BCF.bundle`

The settings configured in the plugin can be found here:

`C:\\Users\\\<Username>\\AppData\\Local\\Autodesk\_Inc\\Roamer.exe\_Url\_\<GUID>\\\<Version>`

### **Uninstalling**

To uninstll the plugin go to the following Windows menu:

`Windows settings -> Apps -> Installed apps`

Find Catenda Navisworks BCF plugin version \<version> in the list and click on the action menu on the right hand side to uninstall.

## **Catenda tab**

After having installed the plugin the Catenda tab will appear.

Navisworks might have to be restarted for the tab to appear.

On the home page of Navisworks, the tab will initially be grayed out.

Start a new or open a Navisworks project to get started.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/01-catenda-tab.png)

This is what the Catenda tab can look like when selected

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/02-catenda-tab.png)

### **Catenda**

The Catenda button in the Catenda Plugins menu of the Catenda tab will open the default browser with the [sign in page](https://support.catenda.com/en/articles/7891486-sign-in-page) of Catenda Hub.

### **BCF Plugin**

The BCF Plugin button in the Catenda Plugins menu of the Catenda tab will open the Catenda Navisworks plugin with the settings menu activated.

The settings menu of the Catenda Navisworks plugin can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/03-bcf-plugin.png)

**Docking the plugin**

Drag the title bar of the window to any of the sides of the application to dock it.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/04-bcf-plugin.png)

This is what the application can look like when docked on the right.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/05-bcf-plugin.png)

## **Settings**

This is what the settings menu can look like after clicking on Login towards the top left.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/06-settings.png)

On the left side the signin page of Catenda is displayed.

Follow the stepd described in the [sign in article](https://support.catenda.com/en/articles/7891486-sign-in-page) to sign in.

This is what the setting menu can look like after succesfully having logged in.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/07-settings.png)

If the login session has timed out the refresh button can be used to refresh the login session.

### **Authenticate**

**Token**

Here you will see your Catenda authentication token after signing in.

### **IFCGuid**

**Category and property**

Cateogory default: Element

Property default: IfcGUID

**Property mapping**

The Catenda Navisworks plugin attaches objects to viewpoints in topics based on the GUID of the IfcProject in the IFC.

In Navisworks this GUID can be found in the properties of the object.

Here is an example with an object selected:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/08-ifcguid.png)

Depending on the content of your IFC, the IfcProject GUID might be found in one or more other properties or categories.

Especially if Navisworks has been launched with a language setting other than English name of the Element category will the word for Element in that language while the default word is still English in the Catenda Navisworks plugin.

To resolve this, change the Category to to the word for Element in the language Navisworks is launched in.

2nd, 3rd, 4th Category and Property

If there are mulgiple categories and properites that could include the IFCProject GUID they can also be added.

### **Paths**

**DownloadPath**

The file location that models and documents downloaded through the plugin end up at.

### **Snapshots**

**Placement**

Right - default

Snapshots are displayed to the right

Below

Snapshots are displayed below

## **Topic Boards**

In the Topic Boards menu an overview topics in the topic boards of different projects can be seen.

Thisis what the Topic Boards menu can look like.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/09-topic-boards.png)

Click on the projects tab to load the list of topic boards in that project in the topic boards tab.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/10-topic-boards.png)

### **New topic**

Click on the New Topic button to create a new topic.

## **Topic**

In the topic menu selected topics can be edited and new topics can be submitted.

This is what the topic menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/11-topic.png)

### **Navigation arrows**

Use the navigation arros in the menu to move between different topics in the topic board.

### **New Topic**

Create a new topic

### **Add Viewpoint**

Add a viewpoint of the current camera position to the current topic.

### **Update**

Update the topic on Catenda with the information that has been added in the plugin.

### **Topic number**

The number of the topic in the project.

### **Refresh**

Load the latest information in the topic from Catenda.

### **Clear clipping planes**

Click the clear clipping planes button to clear the clipping planes in the viewer.

## **Clashes**

In the clashes menu topics can be submitted as a result of clash detective findings.

This is what the clashes menu can look like.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/12-clashes.png)

### **Running a clash detective test**

To get started with the clashes menu find the Clash detective in the ribbon:

`Home tab -> Tools menu -> Clash Detective`

**Test overview**

Add a new test.

This is what your test overview can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/13-running-a-clash-detective-test.png)

**Rules**

Select rules or create new ones.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/14-running-a-clash-detective-test.png)

**Select**

Select models that you want to check against each other for clashes and run the test.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/15-running-a-clash-detective-test.png)

**Results**

Go through the result and name your clashes.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/16-running-a-clash-detective-test.png)

**Context menu**

Right click on a clash row to open the following context menu:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/17-running-a-clash-detective-test.png)

Group

Group together clahses of similar type.

Viewpoint

Adjust the viewpoint with Focus on clash and then open the viewpoint menu of the context menu again to save the viewpoint to the clash.

This is the viewpoint that will end up in the topic on Catenda.

Display settings

Click on display settings on the right to open the display settings.

Highlighting

Change the colors of the the objects from either model that are clashing with each other.

Isolation

Transparency settings

Viewpoints

Set viewpoints to either auto-update, auto-load or manually load.

Simulation

Show simulation or not

View in context

All, file or home.

Items

Here you see the objects that are related to the selected clash.

**Report**

this is what the report menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/18-running-a-clash-detective-test.png)

Contents

Select the contents of your report

Include clahses

Select which clashes to include

Output settings

Select either the current test for the test that is selected in the test overview or all tests for all tests in the test overview combined or separate.

Report format

Use the as viewpoints option and check the Preserve result highlighting box.

### **Clashes in Catenda plugin**

After a clash test has ran the viewpoints appear in the clashes tab.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/19-clashes-in-catenda-plugin.png)

### **Add topic**

Create topic by selecting one or more clash

Give topic a title

Click add topic.

**Add topic dropdown**

Topics can be made in the following ways:

Create one combined topic

- Create one topic from the selected clashes
    - Create a topic with a viewpoint for each clash that is selected in the Navisworks Clash Detective.
- Create one topic from the selected clashes (Consolidated viewpoint)
    - Create a topic with a single viewpoint that is zoomed out to include all clashes that are selected in the Navisworks Clash Detective.

Create multiple topics

- Create one topic for each selected clash
    - Create a topic for each clash that is selected in the Catenda Navisworks plugin.
- Create one topic for each clash group
    - Create a topic for each clash group, that is selected in the Catenda Navisworks plugin, with a viewpoint for each clash in the clash group.
- Create one topic for each clash group (Consolidated viewpoint)
    - Create a topic for each clash group, that is selected in the Catenda Navisworks plugin, with a single viewpoint that is zoomed out to include all selected clashes.
- Create one topic for each ungrouped clash
    - Create a topic for each ungrouped clash that is selected in the Catenda Navisworks plugin

### **Change status**

Change the status of the clashes that are selected in the Catenda Navisworks plugin to one of the following statuses in the Navisworks test results.

- New
- Active
- Reviewed
- Approved
- Resolved

## **Models**

Download, open and append model revisions from the Catenda project selected in the Topic Boards menu to the Navisworks project.

This is what the models menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/20-models.png)

### **Search**

Search thorugh the models in the Catenda project

### **Refresh**

Refresh the models list from the Catenda project

### **Download selected**

Download the selected model(s) from Catenda to your local system

### **Open selected**

Open the selected model(s) in a new Navisworks project

### **Append selected**

Append the selected model(s) to the current Navisworks project.

To be able to append a model to the current Navisworks project it has to be downloaded first.

### **Catenda document library**

Open the Catenda Document library window.

This is what the Document library window can look like.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/21-catenda-document-library.png)

**Navigation arrow**

Move up a level in the folder structure.

**Refresh**

Refresh the documents in the document library.

**Download**

Download the latest revision of the selcted Catenda document to your local system.

**Upload**

Upload the latest revision of the selcted Catenda document to your local system.

**Columns**

Navigation

Doubleclick on the navigation arrow or anywhere else on the row of a folder to open that folder.

Name

The name of the folder or document

Document name

The name of the document

Image

The image of the document

Revision

The revision number for the document

### **Columns**

**Selection box**

The selection box of the model

**Model icon**

The ifon of the model

**Name**

The name of the model

**Revision Catenda**

The latest revision number in the Catenda project

**Revision Navisworks**

**Download**

Click on the download icon to download the latest model revision.

When the revision number appears in the Revision navisworks column the model is Downloaded.

**Open**

Click on the open icon to open the model in a new Navisworks project.

**Append**

Click on the append icon to append the model to the current Navisworks project.

### **Downloading models from Catenda Hub**

You can easily download the IFC models from your Catenda project using this plugin and the actions in the Models tab.

To download to your local device:

Click the download button for each model you want to download.

The models will be saved in a new folder with the project name under the download path specified under the settings tab.

For example:

`C:\\...\\Documents\\Catenda project name`

### **Create a merged .nwf file using IFCs from Catenda Hub**

In order to be able to use the BCF viewpoints from your Catenda project in the Catenda plugin, you need a merged NavisWorks file containing the IFCs from Catenda.

Download the IFC models you want to merge following the steps above.

Open one of the files you have downloaded in NavisWorks.

Merge more models from the same project into the NavisWorks model using “Append”.

Once you have all the files you want to merge appended, save the file as a .nwf file.

Save the file in the same folder as your downloaded IFC files.

Use this merged file when viewing BCF viewpoints in Navisworks.

You can also use this merged file for running collision tests in NavisWorks.
