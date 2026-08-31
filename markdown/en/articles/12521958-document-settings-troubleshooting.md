# Document settings troubleshooting

In this article you will find information about the errors that can occur on the [document settings page](https://support.catenda.com/en/articles/7831371-document-settings-page).

## 1. **Status workflow**

This is what the document settings page can look like when you attempt to create a status with a name that already exists.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/e0s024gx/01-status-workflow.png)

Active document statuses have to be unique in each list. For example, if you have a published status called "Status 1" you get the error when trying to create another published status called "Status 1". It is possible to have statuses of the same name of different status types. For example, it is possible to have a published status called "Status 1" and a shared status called "Status 1" at the same time. Finally statuses of any name can be archived. For example, If a published status called "Status 2" was archived and then another published status called "Status 2" was created and archived both of these statuses would be archived. When a status gets restored where a status of that name already exists, the recovered status will get "(1) behind it.
