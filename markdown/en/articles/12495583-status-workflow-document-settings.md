# Status workflow - Document settings

This is what the status workflow menu on the [document settings page](https://support.catenda.com/en/articles/7831371-document-settings-page) can look like for projects that enabled shared revisions after 2 October 2025. In new projects, the status workflow is disabled by default. This is what the status workflow menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/01-intro.png)

Projects that are created based on a [template project](https://support.catenda.com/en/articles/4670245-creating-a-new-project#h_5db32e5398) and projects that enabled shared revisions before 2 October 2025 will see the legacy status workflow menu.

## 1. **Shared statuses**

Enable shared statuses to align with ISO 19650 and configure workflows. This is what the status workflow menu can look like after enabling shared statuses

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/02-shared-statuses.png)

### 1.1 Enabling shared statuses

By default there is one shared status by the name if shared that is configured. Typical published that are added are:

- WIP - Blue
- Work in progress - Blue
- Internal validation - Blue

**Project changes**

- Information starts out with a minor revision number: 0.1, 0.2, 1.1, etc...
- Information can be published to receive a major revision number: 1.0, 2.0, 3.0, etc..
- The access control menu on the documents page will have an extra column where access to shared revisions and publishing rights can be configured.
- Shared and published statuses - New information submitted in the shared stage.
- The default status is set to Shared.
- An approvals menu in document settings appears.
- An approvals sub-page to the documents page appears.

### 1.2 **Disabling shared statuses**

**Project changes**

- Published statuses - New information submitted in the published stage.
- The default status is set to No status.
- The approvals menu in document settings is disabled.
- The approvals sub-page to the documents page is disabled.
​

## 2. **Published statuses**

By default there is one published status by the name if published that is configured. Click on add status to add more statuses. Typical shared statuses that are added are:

- Published, with comments - Light green
- Waiting - Yellow
- Rejected - Red
​

## 3. **Add status**

You can add a status by clicking on Add status. A new status can have a color and a name. Statuses can either be added to the list of shared or the list of published statuses.

## 4. **Changing statuses**

Status can be edited by clicking on the pencil button to the right of the status.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/03-changing-statuses.png)

The color and name of a status can be changed.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/04-changing-statuses.png)

### 4.1 **Sorting order**

After editing, click on the arrows to move the status up and down in the list of statuses within its stage.

### 4.2 **Archiving statuses**

Statuses can be archived by clicking on the trashcan button to the right of the status. It is only possible to archive and recover the status within the same stage. If the now-archived status was applied to information the status will be visible but struck through.

### 4.3 **Restoring statuses**

Archived statuses can always be brought back by clicking on "Show archived statuses" Here all archived statuses are displayed and can be restored.

## 5. Default status

The status that is listed by default when the publish action is used for a shared revision. A different status can still be selected before publishing. Shared revisions can also be published via [approval requests](https://support.catenda.com/en/articles/12494960-open-or-closed-approval-request-page). Depending on which workflow the submitter selected on behalf of their submitter team, when a member makes a final validation on behalf of the final validation team the published revision the status of the document will change based on what the workflow configuration.

## 6. Upload menu

### 6.1 **Shared statuses enabled**

This is what the upload menu can look like when the published and shared workflow has been requested to be enabled on a project.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/05-shared-statuses-enabled.png)

By default the default shared status is Shared. A status from the list of shared statuses can be selected before uploading.

### 6.2 **Shared statuses disabled**

This is what the upload menu can look like when shared statuses are disabled.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/06-shared-statuses-disabled.png)

By default the default published status is no status. A status from the list of published statuses can be selected before uploading.
