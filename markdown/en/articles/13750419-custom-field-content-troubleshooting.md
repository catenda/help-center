# Custom field content troubleshooting

## 1. **Unable to restore archived dropdown option**

A logical deadlock occurs if an attempt is made to restore an archived option while the associated **Name** is currently in use by an active option. Because it is only possible for a name to be assigned to one option, the restoration is blocked. _Access required:_ Administrator access

To recover the archived value, it is possible to follow this sequence:

**Rename the active value** The active option currently using the name is edited by an administrator to a temporary value to free the name within the system.

**Restore the archived value** The **Disabled list** is accessed, and the **Restore** action is selected for the required item.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/01-unable-to-restore-archived-dropdown-option.png)

**Correct the data** The names and codes are adjusted to the correct state.

**Revert names** The temporary name is changed back to the original intended name.

## 2. **Uniqueness of Names and Codes**

It is important to distinguish between the **Name** of an option and its **Code**. Each dropdown option consists of both these elements, and it is only possible to save an option if both the name and the code are unique within that specific custom field.

## 3. **Duplicate name error**

It is only possible to assign a name to one option in a dropdown list. If a duplicate name error is displayed, the following steps are taken: _Access required:_ Administrator access

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/02-duplicate-name-error.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/03-duplicate-name-error.png)

**Active list verification** The list of active options is checked to confirm if the name is already in use.

**Disabled list verification** The disabled list is checked, as names assigned to archived items remain in the system.

**Resolution** It is only possible to proceed by either using a different unique name or by renaming the existing option that holds the name.

## 4. **Duplicate code error**

It is only possible to assign a code to a single option within a dropdown custom field. The code is a unique value used to identify blocks for naming conventions. _Access required:_ Administrator access

If a duplicate code error is displayed:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/04-duplicate-code-error.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/05-duplicate-code-error.png)

**Active list verification** The active list is checked to see if the code is already in use.

**Disabled list verification** The disabled list is checked, as codes assigned to archived items still occupy that unique value.

**Resolution** It is only possible to proceed by either using a different unique code or by disabling the existing option that holds the code.

## 5. Modifying existing codes

It is only possible to define a code during the initial creation of an option or if an already existing option does not yet have a code assigned. After a code is added and saved, it is locked to that value and the field becomes uneditable.

**Editing restrictions** It is only possible to change the **Name** of an option after a code has been applied. The **Code** field will appear grayed out.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/06-modifying-existing-codes.png)

Before application:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/07-modifying-existing-codes.png)

After application:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/08-modifying-existing-codes.png)

**Recovering a code** If a code is already in use by an archived item, it is only possible to use that specific code by first restoring the archived option from the disabled list. It is not possible to submit a new option with a code that is technically still held by a disabled item.

**Changing a code** To use a completely different code for an existing name, it is only possible to do so by disabling the current option and creating a new one with the desired code.

## 6. Input errors for integer fields

Specific constraints exist for integer fields that result in data entry errors:

**Whole numbers only** It is only possible to save whole numbers in an integer custom field.

**Non-numeric characters** While it is only possible to type numbers directly into the field, it is possible to paste non-numeric characters into it.

**Save button behavior** If there are any non-numeric characters present in the field, the save button is disabled.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/09-input-errors-for-integer-fields.png)

## 7. **Board visibility and filtering**

If a custom field is not visible on an issue board, the following settings are verified:

**Field assignment** Creating a custom field allows it to be added to an issue board. The field must be added to the specific board to appear in the issue header.

**Table view** It is only possible to view custom field data in a list format if the corresponding column is selected in the issue board table view.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/10-board-visibility-and-filtering.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/11-board-visibility-and-filtering.png)

**Filter limits** It is only possible to filter for custom fields if there are up to 10 fields assigned.
