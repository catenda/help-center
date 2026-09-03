# Topic board from an existing topic board

Creating a new topic board can be done by clicking the new topic board action on the [boards page](https://support.catenda.com/en/articles/9413644-boards-page). The action can be found with the green plus button on the top right or in it's neighboring action menu. Access required: Write access to create new topic boards in the access menu on the [project settings page](https://support.catenda.com/en/articles/4670273-project-settings-page).

This is what the New topic board page can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/01-intro.png)

## 1. **Name**

Give the topic board a name as a minimum requirement for adding the topic board. The topic boards list is sorted by topic board name according to the typical [sorting order of lists](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) on Catenda. It is therefore often a good idea to use a naming convention when naming topic boards. Here is an example of what topic boards could be called:

![Topic board list introduction document review approved approved with comments rejected documents breeam socre coordination cost projects](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/02-name.png)

## 2. **Description**

The topic board description is optional and can later only be seen in topic baord settings by those with full access to the topic board. The topic board description follows the general rules for [formatting of posts](https://support.catenda.com/en/articles/8430847-formatting-of-posts) on Catenda.

## 3. **Copy settings from an existing topic board**

To copy settings from one topic board upon topic board creation, click on the "copy settings from an existing topic board" menu to select an existing topic board in the project from which the settings should be copied.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/03-copy-settings-from-an-existing-topic-board.png)

After selecting the topic topic board it is possible to choose which settings to copy.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/04-copy-settings-from-an-existing-topic-board.png)

### 3.1 **Copy statuses and types**

Activate the copy statuses and types radio button to get the same statusses with their status name, color and meta-status type in the topic board that is to be created.

### 3.2 **Copy permission settings**

Activate the copy permission settings radio button to get the same statuses with their color in the topic board that is to be created.

## 4. **BCF 1.0 compatibility**

Topic boards that are used for exporting topics to other topic management tools that only support BCF up to version 1.0 should be locked for compatibility to ensure that the topics generated in Catenda arrive without error on the other side. BCF 1.0 topics generated elsewhere can be imported to any topic board regardless of wether that board is locked for compatibility or not.

### 4.1 **No editing of statuses or types**

By locking a topic board for compatibility it will not be possible to edit the statuses and types that are available in the topic board. As long as the topic board is locked for compatibility the pre-defined statuses and types as specified in BCF 1.0 are made availble and cannot be edited. _Statuses:_ "Open" and "Closed" _Types:_ "Error", "Warning", "Info" and "Unknown"

### 4.2 **Locking and unlocking BCF 1.0 compatibility after creation**

The BCF 1.0 compatibility box can be unchecked in the topic board settings at any moment to expand the amount of statuses that are possible to have in the board. If the statuses in a topic board are not compatible with BCF 1.0 it is also possible to remove any incompatible statuses and lock the board to BCF 1.0 compatibility again at any moment after creation.

### 4.3 **Copy settings from board that is locked**

If a topic board is selected in the copy settings from another topic board menu the BCF 1.0 compatibility checkbox is locked and will be checked or not depending on if the selected topic board to copy settings from is locked to BCF 1.0 compatibility or not.

## 5. **Add**

Click on add to add the new topic board.

> **Note:** The topic board has to at least have a name to be able to be added

There is no notification upon topic board creation.

## 6. **Topic board creation upon project creation**

Upon the creation of a new project the project starts out with a default topic board called "Issues". If the checkbox for topic boards from a template project is checked upon project creation the project starts with the topic boards and topic board settings from the selected template project.

> **Note:** While the settings of these new topic boards are the same as in the topic board in the templates, the GUIDs of the topic boards, statuses and types are unique to the project they are in.
