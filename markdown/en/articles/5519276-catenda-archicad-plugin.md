# Catenda Archicad plugin

> test

> **Note:** The install file for the plugin can be found in [this article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

The Catenda Archicad plugin is a plugin that can be installed for Nemetchek Archicad. With this plugin you will be able to collaborate on 3D viewpoints, topics and documents with the other members of the construction project.

This article contains information about the following:

## 1. **Installation**

When the Catenda Archicad plugin is installed on Windows its installation files will appear in the following folder.

`C:\\Program Files\\Catenda\\Catenda Archicad Connection\\\<Archicad Version>\\Add-On`

Plugin will appear as enabled in the add on manager the next time Archicad is opened up. Note that this is different from the default add-on folder which is located at

`C:\\Program Files\\Graphisoft\\\<Archicad Version>\\Add-Ons`

### 1.1 **Uninstalling**

To uninstll the plugin go to the following Windows menu:

`Windows settings -> Apps -> Installed apps`

Find Catenda Archicad Connection \<version> in the list and click on the action menu on the right hand side to uninstall.

## 2. **Catenda Palette**

After installing the plugin you will be able to see a Catenda menu tab on the top bar. In this menu you will find the window "Catenda Hub Issue Manager" which contains the "Catenda Hub Issue Manager Palette". In order to start using this palette either a floor plan or a 3D view will have to be opened. In the palette you will be able to:

- Navigate to your Catenda Hub project
- See and make issues
- Download and upload models and revisions

## 3. **Sign in**

When you open up the Catenda palette, the first thing you will see is the sign in page. The sign in page can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/01-sign-in.png)

If you do not have a Catenda account you can Sign up for free on the top right. If you already have a Catenda account you can input your email and password and click on sign in. After signing in you will be asked to grant access to your Catenda account. After granting this access the Archicad plugin will show up as an application on the [applications page](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) of your Catenda account. Here you can always revoke the access should you no longer wish to grant it.

### 3.1 **Password reset**

If you forgot your password you can click on I forgot my password to reset it. The password reset page can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/02-password-reset.png)

If you enter your email address and click on "send a verification email" you will be sent an email that will guide you through resetting your password. Please make sure you have received this email within 5 minutes. If you do not see it in your inbox you could try your spam or junk inbox. If it takes longer 5 minutes please contact support at [support@catenda.com](mailto:support@catenda.com)

To go back to sign in click on sign in on the top right.

## 4. **Project list**

When you open up the Archicad plugin you will see your list of projects which can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/03-project-list.png)

As soon as you have accepted the invitation to a project you will see your project appear in the list of your projects in the plugin and on the [projects page](https://support.catenda.com/en/articles/8400797-projects-page). **Action menu** Click on the three dots next to your profile picture to open the action menu dropdown:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/04-project-list.png)

**Models & revisions** This is what the models & revisions page can look like. Here you will be able to see all the models you have access to in your Catenda Project.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/05-project-list.png)

On this page you will be able to download and import ifc files from your Catenda Project to you Archicad model. The timestamp of the model will be relative. Hover over the timestamp to get accurate information about when the revision was published. Click on the arrow button next to one of the model revisions to import the IFC file that was uploaded as a revision. If you do not have access to any models in your Catenda project you will see the following:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/06-project-list.png)

**Upload IFC** Upload an IFC from your current Archicad project This is what the upload IFC page can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/07-project-list.png)

By default the file name will be the name of the Archicad project. This will become the name of the revision in Catenda Select to which model you would like to upload your file. Click on settings to open the Archicad IFC export dialogue. Here you can configure what settings you would like to use to export your IFC to Catenda. When you are ready, click the upload button to upload a model.

**Coordinates** Hover over the coordinates option to expand the coordinates menu. This is what the coordinates menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/08-project-list.png)

In the coordinates menu coordinates can be chosen to be relative to: Survey Point - Default Project origin

**Version** The version number of the plugin.

**Logout** Log out of your Catenda account

## 5. **Topic board**

When you click on a project to open it up the first topic board in the project will open. A topic board can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/09-topic-board.png)

### 5.1 **Search**

Click in the search bar to highlight it. This is what the hightlighted searchbar can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/10-search.png)

After clicking in the searchbar a dropdown with suggested filters opens up. Select any of the filters to apply them. Click on the x next to the filer to remove it again. Start typing to narrow down the suggested filters or perform a text search.

### 5.2 **Show filter**

Click on the Show filter button to open the filter menu. This is what the filter menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/11-show-filter.png)

Depending on the configured settings in the topic board and the topics that are submitted different filters can be  available:

**My topics** Assigned to me Requested by me Created by me

**Status** The different statuses in the topic board are listed here

**Type** The different types in the topic board are listed here

**Due date** Overdue Less than a day Less than a week Less than two weeks Less than a month All with a due date

**Assigned to** The entries starting with an `@` are assigned teams that are listed first. After that assigned project members are listed.

**Requested by** The entries starting with an `@` are teams requesting topics that are listed first. After that project members requesting topics are listed.

**Milestone** Any milestones applied to topics are listed.

**Label** Lables applied to topics are listed here.

**Filters that are not mentioned in the filter menu** Text search Text can be searched on by typing in the serach bar.

Content that can be searched on Topic title Topic description Topic comment

Capitalization The text search is not sensitive to upper or lowercase characters.

Character amounts Single character - No results. At least two characters are required for a text serach Two characters - Full words, separated by spaces, that matches the search phrase are included in the results.

### 5.3 **Sort**

Click on Sort to open the sort menu. This is what the sort menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/12-sort.png)

Click on any of the options to sort the topics list by: _Newest_ - Default Topics with the newest creation date

**Oldest** Topics with the oldest creation date

**Recently updated** Topics that are most recently updated

**Least recently updated** Topics that are least recently updated

## 6. **Topic**

When you click on a topic in the topic board you open it up. A topic can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/13-topic.png)
