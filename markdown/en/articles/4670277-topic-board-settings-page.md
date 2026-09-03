# Topic board settings page

To open the topic board settings page, first open the [topics page](https://support.catenda.com/en/articles/4670271-topics-page).

The settings page of a topic board can be found by clicking on settings of a topic board on the [boards page](https://support.catenda.com/en/articles/9413644-boards-page) which can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/01-intro.png)

The topic board settings page of the last visited topic board can also be found by going to the [topic settings page](https://support.catenda.com/en/articles/14183429-topic-settings-page) and clicking on topic board settings.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/02-intro.png)

You can find the topic board settings page as a sub page to the [topics page](https://support.catenda.com/en/articles/4670271-topics-page) or by clicking on settings for the respective topic board on the [boards page](https://support.catenda.com/en/articles/9413644-boards-page#h_e0fc8beec6). _Access required:_ Full access to the [topic board](https://support.catenda.com/en/articles/4670271-topics-page)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/03-intro.png)

This is what the topic board settings page could look like with all its menus closed.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/04-intro.png)

## 1. **Action menu**

This is what the action menu towards the top righ in a topic board can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/05-action-menu.png)

### 1.1 **New topic**

Click on the green plus button or click on the new topic action in the action menu to createa a [new topic](https://support.catenda.com/en/articles/4670268-creating-a-new-issue) in the current topic board. _Access required:_ Read access to the current topic board.

### 1.2 **Exchange topics**

Click this button to [exchange topics](https://support.catenda.com/en/articles/4670289-exchange-issues)

### 1.3 **New topic board**

Click this button to make a [new topic board](https://support.catenda.com/en/articles/6379614-topic-board-from-an-existing-topic-board).

### 1.4 **History**

_Import history_ - See the topic import history of the project _Export history_ - See the topic export history of the project _Move history_ - See the topic move history of the project

### 1.5 **Archive topic board**

You can not delete an topic board in Catenda Hub Instead you can “archive” it so that it does not show anymore. Links to topics in archived topic boards will not be visible in documents or objects. Archived topic boards can be restored by going to the settings of the archived board on the [boards page](https://support.catenda.com/en/articles/9413644-boards-page). After restoring a board the links will be visible again.

> **Note:** You can see the topics in an archived topic board by clicking on “topic boards”. At the bottom of that list you can select “View archived”.

## 2. **Topic board information**

_Topic board name_ - Change the name of the topic board _Owner_ - See who made the topic board

**Description** Short description that will only be seen here so you and others that are configuring the board know what it is used for.

## 3. **Statuses and types**

### 3.1 **Lock statuses and types for BCF 1.0 compatibility**

BCF 1.0 only supports 2 statuses ("Open" and "Closed") and 4 types ("Error", "Warning", "Info" and "Unknown"). It is not possible to modify statuses or types on topic boards where this option is selected.

### 3.2 **Status**

When you create a topic board you will have the following default statuses:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/06-status.png)

A status has a _Name, Color, and Meta-status._ By default there are three statuses that have an open and two that have a closed meta-status.

_Add status_ - Click the add status text at the bottom of the status list to add a new status.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/07-status.png)

**Edit status** Upon editing a status you will notice that you can assign a third meta-status called Candidate.

_Color_ - Change the color of the status.

**Arrows** Change the order of a status by using the arrows to move it up or down the list. The top status will be the default status when you make a new topic. The order of the statuses will also be the order the statuses will appear in the dropdown list when changing the status of an topic.

**Delete** You can also delete statuses here down to a minimum of 1 open and 1 closed status.

### 3.3 **Meta-status**

Meta-statuses give a general idea of where in the workflow the status of a topic is. _Open_ - Topics with this meta-status are shown by default when you open an topic board. _Closed -_ Topics with this meta-status are hidden by default when you open an topic board.

> **Note:** You can configure who is allowed to change the status of a topic with an open meta-status to a status with a closed meta-status in the [access control section](#h_82063f7a79).

**Candidate** Topics with a candidate meta-status are also hidden by default This status is supposed to be for Topics that are neither open nor closed. The candidate meta-status is meant to be for letting people know an topic is not completely finished drafting yet so it is not open yet. In the flow it is therefore meant to come before open. However, people also use this status for topics that have fallen outside of the regular flow. Like an topic that is not finished and therefore closed but just no longer relevant. People do not want to see it in the list by default and therefore use this meta status.

The minimum amount of statuses is one open status and one closed status.

### 3.4 **Type**

When you create a topic board you will have the following default types:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/08-type.png)

Types are configured similarly to statuses except they do not have meta-statuses and you can delete up to a minimum of 1 type.

## 4. **Custom Fields**

In this menu you will be able to add and modify custom fields in this topic board. _Access required:_ Full access to the topic board Custom fields can be configured on the [custom fields page](https://support.catenda.com/en/articles/6550459-custom-fields-setup). _Access required:_ Project administrator

### 4.1 **Add custom field**

You can add a custom field by clicking on the green Add a custom field button.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/09-add-custom-field.png)

After clicking on the button you will be able to select your custom field in the add a custom field dialogue.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/10-add-custom-field.png)

**Select a custom field** The following types of custom fields can be made available for a topic board: Date Decimal Dropdown Integer Text

**Mark as required** Yes or no If the custom field is set as required users will not be able to submit an topic without filling out this custom field.

**Set default value** Default value for your custom field type The default value is mandatory when the custom field is marked as required.

Remember to click add when you are done.

> **Note:** It is possible to add up to 30 custom fields per topic board.

### 4.2 **Modifying custom fields**

By clicking on a custom field that has been added you will be able to configure its settings.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/11-modifying-custom-fields.png)

**Mark as required** Yes or no If the custom field is set as required users will not be able to submit an topic without filling out this custom field.

**Set default value** Default value for your custom field type The default value is mandatory when the custom field is marked as required.

**Remove from topic board** Click the remove from topic board button to remove this custom field from the topic board.

Remember to click submit.

## 5. **Access control**

Users will be able to see an overview of what teams and users have which access to this topic  board. If all users have access to creating topic boards the lock will be green. If access has been set for the creation of topic boards in project settings the lock will be orange.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/12-access-control.png)

### 5.1 **Edit access**

Click on "edit access" to configure access the access for this topic board. You can read more about editing access [here](https://support.catenda.com/en/articles/4670296-issue-boards-acl). _Access required:_ Full access to the topic board.

## 6. **Unlinked fields**

Topics that are entered into a topic board with fields that do not exist in the topic board are hidden in the topics table by default.

An orange bar is then displayed towards the top of the topics table that says that there are unliked fields in the topic board. _Access required:_ administrator

For the topics containing fields with values that do not exist in the topic board to be displayed in the topics table, the fields need to be linked to something that does exist in the topic board.

### 6.1 **Fields with non-existing values**

Examples of fields with values that might not exist in a topic board are:

**Status or type** For a topic to be displayed in the topics table it has to have a status and type with a GUID that matches with a GUID of a status and type that is configured for a topic board. Even if the names of the statuses and types are the same in different topic boards, if the topic is moved from one board to another, the status/type will be unlinked as the GUID of a status/type is unique to each topic board.

**Members** For a topic to be displayed in the topics table all members that are part of the topic have to exist in the project. The following fields can contain members in a topic: Assigned user Requesting user Commenting user

### 6.2 **Linking fields**

Often multiple topics are imported at a time. To make it so not each individual field has to be changed to an existing value it is possible to mapp all fields of one time to an existing value in the topic board.

**Status or type** For each status and type that does not exist in the topic board, select an existing status or type. The unlinked status or type can have the same name as an existing status or type but might still be unlinked as it has a different GUID in the background. In this case the mapping is simple, just select the status or type with the same name. If a status or type with the same name does not exist in the board the topic was imported to, a status or type with a different name that does exist in the board will have to be selected. If none of them fit, consider adding another status to the list of types or statuses in the topic board.

**Users** Each user in imported topics that does not exist in the project has to be mapped to either a user or team in the project. After mapping, the topics will be be requested by or assigned to this user and any comments will look like they have been made by the mapped user. If the user has changed email addresses the mapping is simple, just select the user by their name with the account that they are using with their new email address. If there is no similar user that can be mapped in the project a good stategy is to create a team that will act as this user. That way it is possible to find all actions from imported topics made by this user by filtering on the mapped team.
