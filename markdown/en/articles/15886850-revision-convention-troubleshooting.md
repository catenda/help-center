# Revision Convention Troubleshooting

> Troubleshoot file upload failures and revision stacking errors in folders with naming conventions. Fix issues caused by an incorrectly enabled Document Identifier and learn to identify allowed custom field values from the preview

When a Naming Convention is enabled on a folder, file upload failures or errors in revision stacking typically stem from two common configuration issues.

## 1. **1. Incorrect Document Identifier Toggle**

A frequent issue occurs when the **Document identifier** is incorrectly set to **On** for a block that changes with every revision. When this option is active, the changing variable field is integrated into the permanent document name rather than being isolated to the revision metadata.

Consequently, while the initial revision will upload successfully, any subsequent file with a modified variable value will fail to match the established document name. This mismatch causes the system to reject the file, stating that it does not follow the convention. To resolve this issue, the block configuration must be updated to turn the Document Identifier **Off**. _Access required:_ Administrator

## 2. **2. Mismatched Field Values**

Upload failures can also occur if the text within the dynamic block does not match the validation rules or the specific values established for the underlying custom field. For instance, inserting alphabetical characters into an integer custom field, or entering a phrase that has not been explicitly defined within a dropdown custom field, will result in a convention mismatch.

### 2.1 **2.1 How to Identify Permitted Values**

To verify the exact requirements of a naming convention block, the rule configuration can be reviewed directly from the document interface:

1. Expand the right information menu for an existing document within the affected folder.
1. Review the **Naming convention preview** section, which provides a real-time visual breakdown of what the naming rule expects.
1. Hover the mouse over the specific version or status block to view its configuration rules.
1. Identify the exact custom field powering the block to discover which specific values are allowed, enabling the local filename to be adjusted to match.
