# Status Workflow Shared -> Published

## 1. **Availability on Projects**

The new status workflow is an on-demand feature that can be requested to be enabled for ongoing projects. New projects that are created based on a template project where the new status workflow is enabled will also have the new status workflow enabled.

**'Drafts' will be discontinued and no longer be available.**

## 2. **Enabling status workflow with 'shared' revisions**

The old status workflow (legacy) with 'drafts' will be replaced by the new Status Workflow (with shared statuses) for on-going projects that are not using the legacy status workflow. Shared statuses can be activatedin the status workflow menu of the document settings page.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/h48tax1e/01-enabling-status-workflow-with-shared-revisions.png)

The upgrade from status workflow with 'drafts' to status workflow with 'shared' documents, bring these effects;

## 3. **Catenda Hub**

**Shared status** Uploads will all begin with a shared status, once shared statuses are available in the project. After uploading, shared documents can eb published.

**Draft documents** Drafts will be discontinued, hence new drafts cannot be uploaded anymore Existing drafts can still be used in old projects (with limitations)

🖥️  _Workspace and_ ✔️ _Published tabs_ Separate tabs (workspace and a published) will be available in the document area, where the published tab will provide only published revisions.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/h48tax1e/02-catenda-hub.png)

A new revision numbering will appear (major.minor). #0.1, #0.2 and so on for **shared revisions** and #1, #2, #3 and so on for **published revisions**.

### 3.1 _Access control_

Access rights can be set on publishing of shared revisions. This allow users to publish shared revisions and change published statuses. Access control will appear on a folder/document level to grant users the right to publish document revisions with write access Access rights on viewing of shared revision will be available. Here you can prohibit users with 'read access' from seeing shared revisions.

**Approvals** Only shared revisions can be added to an approval request

**Collections** Collections can only be used for published revisions

**Document-models** The model area will display the tabs (workspace and a published) just like in the document area. Access rights will be inherited from documents.

> **Note:** Please inform your project members of these changes when activating this feature on existing projects.

## 4. **API clients**

**Latest revision** Latest revision of document (can be a shared or published) is fetched unless otherwise specified in the API call

**Upload defaults** Uploads via the API will default to a shared revision, once shared statuses are available in the project.

**Revision number changes** Revision numbers will be inconsistent with the revision numbers (major.minor) on Catenda Hub. You would need to update your app.

> **Note:** Please inform your project members of these changes when activating this feature on existing projects.

Click [here](https://support.catenda.com/en/articles/12289689-status-workflow-api-updates) to read more about API changes
