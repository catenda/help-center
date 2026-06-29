# Custom field contents page

You will be able to find the page of a custom fields by clicking on the respective field on the [custom fields page](https://support.catenda.com/en/articles/6550459-custom-fields-page) which you can find as a sub page to the [project settings page](https://support.catenda.com/en/articles/4670273-project-settings-page).

Creating a custom field will let you add it to an issue board. Issues in this board will then get a new field in the header. You will also be able to see a column in the issue board table view and you will be able to filter for these fields.

## 1. **New item action menu**

Administrators will be able to find action buttons on the top right of the content page of a custom field.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/01-new-item-action-menu.png)

_New custom field_ Click on the green plus button towards the top right or the New custom field action in the action menu to make a [new custom field](https://support.catenda.com/en/articles/8445575-creating-a-custom-field)

**Archive** Open the action menu with the three dots towards the top right to find the Archive action towards the top right. It is only possible to archive a custom field. It is not possible to delete a custom field.

Instead of deleting custom fields can only be Archived. An archived custom field will disappear from

## 2. **Date custom field**

A date field displays a date on the georgian calendar. The date is displayed in the format that is configured on the account page for each member.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/02-date-custom-field.png)

This field can be used to register the date of original creation if the infromation was created some time before it was submitted to Catenda and the metadata is known but not reflected in the document metadata or the title.

## 3. **Decimal number custom field**

A decimal number field displays up to 6 numbers after the comma. If there are more than 6 numbers after the comma scientific notation will be used.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/03-decimal-number-custom-field.png)

This field is often used to register amounts such as material cost or budget impact.

**Limit** Decimal custom fields have a limit of values between `-0.000000001` to `2147483647` per integer custom field that is filled out. Decimal custom fields have a limit of 17 numbers combined before and after the decimal separator. For higher numbers scientific notation can be used. For example `1.0991234567890123e+22` The amount of characters is possible to limit further with a naming convention for use in document upload name.

## 4. **Dropdown custom field**

To go the the custom field page of a dropdown field, click on a dropdown field.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/04-dropdown-custom-field.png)

When a dropdown custom field is first created you will automatically be taken to this page. A dropdown custom field page can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/05-dropdown-custom-field.png)

### 4.1 **Title and description**

Administrators will be able to change the title and description of the field by clicking on the pencil.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/06-title-and-description.png)

### 4.2 **Active and disabled tabs**

Below the description, the Active tab is enabled by default. Click on the disabled tab to view dropdown values that have previously been disabled.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/07-active-and-disabled-tabs.png)

**Restore** Use the restore action to restore a previously disabled dropdown value

> **Note:** Each value in the active values list has to have a unique name so make sure the name is not already in use when restoring a value.

### 4.3 **Drop down options** - Active list

In the active list you will be able to find the dropdown options that are currently active.

_Anchor_ Administrators will be able to configure the order of the options by dragging on the anchor in the leftmost column.

**Name** Here users will see the name and of a dropdown option. If the dropdown field has been [added to a topic board](https://support.catenda.com/en/articles/6563368-custom-fields-in-a-topic-board) you will see this name as an option in the list. A name can only be assigned to one option.

**Code** Here users will see the code of a dropdown option. The code is used to [identify a block with a naming convention](https://support.catenda.com/en/articles/7869240-how-to-use-custom-fields-in-naming-convention). A code can only be assigned to one option.

**Edit and disable** Administrators will be able to edit the name of an option after it has been created. If the field does not have a code yet it is possible to add a code. After editing click save or cancel to confirm.

Administrators will be able to disable options by clicking on disable and clicking on confirm. Disabling is similar to deleting as the option will disappear everywhere on Catenda hub but can later be recovered from the disabled list.

After a code is added it is not possible to edit the code anymore. If you wish to use a different code, you can disable the option and create a new option.

### 4.4 **Drop down options -** Disabled list list

Here you will be able to find all the options that are currently disabled. Administrators will be able to click on restore to restore any of the disabled options.

### 4.5 **Adding an option**

After creation, a dropdown custom field will not have any options yet. Administrators will be able to add options by clicking on the add options button on the bottom left

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/08-adding-an-option.png)

After clicking on add options you will see the following dialogue:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/09-adding-an-option.png)

_Name_ Here you can add a name and a code for each dropdown option.

**Code** The code is used to [identify a block with a naming convention](https://support.catenda.com/en/articles/7869240-how-to-use-custom-fields-in-naming-convention). Code is a unique value that you can set on an item. This means that you can not add the same code twice.

**Name and code troubleshooting** Click [here](https://support.catenda.com/en/articles/13750419-custom-field-content-troubleshooting) to read more if there are challenges with the name and code.

### 4.6 **Adding multiple options**

In a dropdown field you often want to add more than one option. If you add a name and click on submit you have to click on "Add options" every time you want to add an option which can be tedious and time consuming. There are therefore several ways in which options can quickly be added.

**Keep open on submit** To keep adding option after option you can check the "Keep open on submit" button. If this button is checked you will be able to add the name of the next option right after submitting the previous option so you do not have to click on "Add options" all the time.

**Add multiple options** If you already have your options prepared outside of Catenda, you can paste them in a good way by clicking on the "Add multiple options" button. When you click this button, the dialogue will change, and you will be able to paste in a string. If Catenda is able to interpret the string properly the names and codes of your pasted options will be recognized and you will be able to submit them all at once.

**Creating a paste-string**

- Excel copy paste

An easy way to create a paste string is by copying rows and columns from a table editing software like Excel. If you add your names in the first row and optionally your codes in the second you can copy them and paste them into the paste dialogue. Your names and codes will then automatically be formatted right.

- Comma separated string

To create a string that will turn into a set of options, separate your options with a "comma"  `,` or a "newline" `\\n`. For example "Electrical,Architecture" will turn into the options `Electrical` and `Architecture`

- Names and codes in a string

Optionally, if you want to add it, you can add a code to your option by separating it with a  "tab" , "colon" `:`, "semi-colon" `;`, and "pipe" `|`. For example "Electrical:el,Architecture:arc" will turn into the option `Electrical` with the code `el` and the option `Architecture` with the code `arc`.

After pasting the string into the paste field you can click somewhere on the page to see if your formatting was successful.

> **Note:** If the dropdown field is added to a topic board it matters how many fields you add and if your field is mandatory. If there are up to 10 fields you can filter for each of the fields. If the field is not mandatory the field can be filtered on whether the field is set or not.

**Limit** While it is possibel to add up to 450 options at a time it is recommended to add upto 100 options at a time.

### 4.7 **Limit**

Dropdown custom fields have a limit selecting one options from up to 1000 options per dropdown custom field.

## 5. **Integer custom field**

An integer custom field displays whole numbers.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/10-integer-custom-field.png)

Only whole numbers are allowed with this field and no decimals. This is often used to register occurrences.

**Limit** Integer custom fields have a limit of values between `-2147483648` to `2147483647` per integer custom field that is filled out. The amount of characters is possible to limit further with a naming convention for use in document upload name. For higher numbers a decimal field can be used with scientific notation.

## 6. **Text custom field**

A text custom field displays a string of text.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/11-text-custom-field.png)

The text is displayed in a single line. A good example of a text field is a field called comment that can be filled out and seen from the table view. In naming conventions it is often used to limit so a certain amount of characters allowed for a filed in a document title.

**Limit** Text custom fields have a maximum limit of 200 characters per text custom field that is filled out. The amount of characters is possible to limit further with a naming convention for use in document upload name.
