# Labels page

The label page can be found as a sub page to [project settings](https://support.catenda.com/en/articles/4670273-project-settings-page) in the left navigation menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/exzgaw41/01-intro.png)

This is what the labels page can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/exzgaw41/02-intro.png)

## 1. **Top buttons**

The green top right button on the labels page either lets you make a new label or a new group depending on which tab is active

### 1.1 New label

With the label tab active, If you click on the "New label" button the Add labels menu will appear.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/exzgaw41/03-new-label.png)

**Color** Choose the color of the new label

**Group** Choose the group of the new label (optional) If your group does not exist yet you can write your desired group in the set label group dropdown and click on create \<group name> You can also make and edit groups in the groups tab.

**Label** Choose a label name

**Import multiple** Copy a table with up to three columns from Excel. Each row corresponds to a labels name, group, and color.

Example:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/exzgaw41/04-new-label.png)

Pasting in the following from excel will result in:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/exzgaw41/05-new-label.png)

> **Note:** If you do not specify a color to the labels they will get the color specified in the color dropdown.

Labels will be separated on "comma" or "newline". Group names per label will be split on "tab", "colon", "semi-colon" or "pipe". The labels are written as name:groupname:color. Labels will be separated on **"comma"** or **"newline"**.

`Electrical,Architecture`

will become

![](https://raw.githubusercontent.com/catenda/help-center/main/images/exzgaw41/06-new-label.png)

---

Group names per label will be split on **"tab"**, **"colon"**, **"semi-colon"** or **"pipe"**.

`Electrical:Trade,Architecture:Trade`

will become

![](https://raw.githubusercontent.com/catenda/help-center/main/images/exzgaw41/07-new-label.png)

---

A third argument may specify a hex color.

`Electrical:Trade,Architecture::#00ff00`

will become

![](https://raw.githubusercontent.com/catenda/help-center/main/images/exzgaw41/08-new-label.png)

Groups and colors are optional. Set a default to overwrite blank spaces.

Error If there is an error with a label it will show up as red.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/exzgaw41/09-new-label.png)

Hover over the label to see what is causing the error.

This could be: The label already exists in the project.

Label names have to be unique. If a label already exists in the project or if you are trying to add a label twice you will have to rename it.

Creating new groups If the groups do not exist in the project yet you will be asked if you want to create the appropriate new groups or if you would like to discard them.

**Keep open on submit** If you check this checkbox a new add labels menu will be opened right after submitting a label. If you would like to create more than three labels manually through this menu this option will save you time since you will not have to click on the new label button every time. If you are making one or two labels it is just as fast to click the new label button.

### 1.2 **New group**

With the group tab active, If you click on the "New group" button the Add label group menu will appear.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/exzgaw41/10-new-group.png)

**Label group** Choose a label group name

**Keep open on submit** If you check this checkbox a new add label group menu will be opened right after submitting a label group. If you would like to create more than three label groups manually through this menu this option will save you time since you will not have to click on the new label button every time. If you are making one or two label groups it is just as fast to click the new group button.

## 2. **Changing a label**

Select one or more labels to overwrite their settings.

## 3. **Deleting a label**

If a label is not connected to aa topic or a document you can click on delete in the rightmost column.
