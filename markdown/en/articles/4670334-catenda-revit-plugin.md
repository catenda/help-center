# Catenda Revit plugin

> **Note:** The install file for the plugin can be found in [this article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

The Catenda Revit plugin is a plugin that can be installed for Autodesk Revit. With this plugin you will be able to collaborate on 3D viewpoints, topics and documents with the other members of the construction project

## 1. **Installation**

When the Catenda Revit plugin is installed on Windows its installation files will appear in the following folder.

`C:\\ProgramData\\Autodesk\\ApplicationPlugins\\CatendaHub.bundle`

### 1.1 **Uninstalling**

To uninstll the plugin go to the following Windows menu:

`Windows settings -> Apps -> Installed apps`

Find Catenda for Autodesk® Revit®  in the list and click on the action menu on the right hand side to uninstall.

## 2. **Opening the plugin window**

After installing, the Catenda panel can be found in the Add-ins ribbon. Depending on your ribbon settings the Catenda panel can look somethign like this:

**Full ribbon - Default**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/01-opening-the-plugin-window.png)

**Panel buttons**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/02-opening-the-plugin-window.png)

**Panel titles**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/03-opening-the-plugin-window.png)

**Minimize to tabs**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/04-opening-the-plugin-window.png)

### 2.1 **Topics**

Click on Topics to open the Catenda Plugin Window to the topics page. If no user is signed in the sign in page is displayed instead.

### 2.2 **Upload IFC**

Click on Upload IFC to open the Catenda Plugin Window to the IFC Upload page. If no user is signed in the sign in page is displayed instead.

### 2.3 **Catenda**

Click on Catenda to be redirected to [https://hub.catenda.com/](https://hub.catenda.com/) in the default system browser.

## 3. **Signing in**

This is what the plugin window can look like when docked on the right:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/05-signing-in.png)

Log in with your Catenda email address and password.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-703202eeb52b.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3e163e70c122.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3b6b4eaa010e.png" width="180"/>

If you have MFA enabled for your account you will be asked to fill in your MFA code. Click [here](https://support.catenda.com/en/articles/7891486-sign-in-page) to read more about the sign in page.

Click on “Allow access” to allow the Revit plugin for Bimsync Arena access your Catenda Hub account.

### 3.1 **Revoke access**

Access to your Catenda Hub account can be revoked at any time by going to your Catenda Hub [application page](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) and click on “Revoke access” near “Revit plugin for Bimsync Arena”.

## 4. **Topic List**

After signing in, the main view of the Catenda Hub plugin is opened up. On this page, the main menu to navigate in your Catenda Hub project, topic boards and topics can be found.

### 4.1 **Interface**

![Header.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/06-interface.png)

1. Select your Catenda Hub project
1. Select a topic board in this project
1. Create a new topic in the currently selected topic board
1. Sort currently displayed topics
1. Open the Catenda Hub add-in menu
1. Search and filter the displayed topics
1. The list of currently filtered topics in the topic board

### 4.2 **Project and topic board selection**

Selecting a Catenda Hub project will display the list of topic board in this project, allowing you to selected one to display the corresponding topics. It will also save the Catenda Hub project and topic board in your Revit model and open them automatically the next time you open this model.

![ProjectInfo.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/07-project-and-topic-board-selection.png)

### 4.3 **Actions**

The plugin actions can be found towards the top right:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/08-actions.png)

Click [here](https://support.catenda.com/en/articles/13168755-actions-in-the-catenda-revit-plugin) to read more about the different actions in the Catenda Revit Plugin.

### 4.4 **Topic selection**

In the topic list, you will find all the main information about an topic:

![IssueInformation.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/09-topic-selection.png)

1. The title of the topic
1. Its status (Open, Closed, …), its type (Info, Error, …) and its labels
1. The member requesting the topic
1. The member the topic is assigned to
1. The due date of the topic
1. When the topic was last updated. You can hover over the date to display the full date and time of update.
1. The number of comments in the topic
1. The image of the first comment in the topic
1. Catenda Hub topic number

You can click on any topic to go to the [topic detail page](#topic-details).

### 4.5 **Sort topics**

You can sort the displayed topics to bring he most relevant to you first.

![sort.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/10-sort-topics.png)

1. Bring the most recently created topic first
1. Bring the oldest topic first
1. Bring the most recently updated topic first. Updating an topic can involve changing any of this properties, title, comments, …
1. Bring the least recently updated topic first
1. Bring the most recent due date first
1. Bring the oldest due date first

### 4.6 **Filter topics**

Using the filter bar, you can combine any type of filter to display only the most relevant topics.

Current filters are displayed as small chips in the filter bar. Here, only topics with the “Open” status are displayed. Click in the filter bar to display all available filters (1).

![AvailableFilters.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/11-filter-topics.png)

On the left (2) is the name of the filter, every filter belong to a type displayed on the right (3).

Available filters types includes:

- Requested By: Get all topics requested by a given user
- Assigned To: Get all topics assigned to a given user
- Due Date: Get all overdue topics or topic due in less than a month, two week, a week or a day
- Status: Get all topics of a given status (Open, Closed, …)
- Type: Get all topics of a given type (Error, Warning, Info, …)
- Label: Get all topics with a given label
- My topics: Get all topics assigned or requested by yourself

You can search for these filters by typing text in the filter bar (1). You can also use this to create a text filter to search for a specific text in the topic title or description (2).

![TextFilter.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/12-filter-topics.png)

## 5. **Topic Details**

In this view, you can review and edit a specific topic.

### 5.1 **Interface**

![IssueDetailView.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/13-interface.png)

1. Go back to the [Topic List](#topic-list)
1. Refresh the content of this topic
1. Navigate between topics
1. Set the topic status (Open, Closed, …)
1. Set the topic type (Error, Warning, Info, …)
1. Set the due date of the topic
1. Set the member assigned to the topic. You can assign a topic to an individual user or a team.
1. Set the member requesting this topic. You can set an individual user or a team.
1. Edit the topic labels
1. The list of comments in the topic

### 5.2 **Topic properties**

You can edit any property of the topic: Status, type, assignee, requester, due date, labels. Every menu will display a list of available properties. However, you cannot create a new status, type or label directly in the plugin, you will have to use the web interface of Catenda Hub to do that.

You can click on the title to edit it:

![editTitle.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/14-topic-properties.gif)

You can click on the pen icon to edit the description:

![editDescription.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/15-topic-properties.gif)

You can also type text in the label bar to filter down the list of filters:

![editLabels.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/16-topic-properties.gif)

### 5.3 **Comments**

All comments are displayed below the topic. A comment can contains text, a picture, a snapshot from your Revit current view or a viewpoint.

![CommentDetail.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/17-comments.png)

1. The author of the comment
1. When the comment was created. You can hover over the date to display the full date and time of update.
1. The [zoom button](#zoom) (see chapter below)
1. The image associated with the comment
1. The text of the comment

### 5.4 **Zoom**

If the comment contains a viewpoint, you can zoom to this viewpoint. Zoom in will create a new 3D view in your Revit model focused on the same viewpoint.

![zoom.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/18-zoom.gif)

For the viewpoint to be relevant, you must have opened the same model than the one where the comment was created. The plugin assumed that Shared Coordinates where used while exporting the model to IFC.

If the viewpoint has been created from a perspective view, the new 3D view will have its projection mode set to “Perspective”. Otherwise, the projection mode will be “Orthographic”.

The add-in will create only one perspective view and one orthographic view. After having created them, it will reuse them for any subsequent use of the zoom function. You can change that in the settings menu. You can also use the settings menu to change the name of these view.

### 5.5 **Related elements**

If the topic contains related elements, the add-in will select them in Revit when you zoom to a viewpoint.

![relatedElements.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/19-related-elements.gif)

For this function to work, you Revit model must have been exported to IFC with the “Store the IFC GUID in an element parameter after export”. This add the IFCGuid parameter on every object, allowing the plugin to select the related elements.

### 5.6 **Add comment**

You can add comments to an topic by writing in the text box and clicking on Submit.

You can also add a picture from your computer by clicking on the “Plus” button. You can annotate this picture by clicking on the preview image after selecting it.

![createComment.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/20-add-comment.gif)

### 5.7 **Add 3D snapshot**

You can also add your current Revit view as a viewpoint and a snapshot attached to your comment. Just like any picture, you can annotate the snapshot by clicking on the preview image.

If the IFCGUID parameter is present, selected elements in Revit will be added to your topic as related elements.
