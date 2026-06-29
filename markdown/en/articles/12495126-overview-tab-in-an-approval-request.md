# Overview tab in an approval request

The overview tab of an approval request can be found on the approval request page of [open or closed](https://support.catenda.com/en/articles/12494960-open-or-closed-approval-request-page) approvals. In the overview tab an overview of a selected approval review step can be found. In the step the validations that are indicated and submitted by a member on behalf of each submitter team that is configured to review the step can be seen. For an overview of validation submissions for all the steps, see the [documents tab](https://support.catenda.com/en/articles/8349418-approval-page#h_133b2690af). This is what the overview tab in the approval content can look like for projects that enabled shared revisions after 2 October 2025:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/01-intro.png)

## 1. Approval request step ribbon

In the step ribbon a preview of the progress of the approval request can be seen. This is what the step ribbon can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/02-approval-request-step-ribbon.png)

Click [here](https://support.catenda.com/en/articles/12495212-step-ribbon-in-an-approval-request) to read more about the step ribbon

## 2. Approval step dropdown

This is what the approval ste dropdown can look like when an approval request has gotten to the final approval step:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/03-approval-step-dropdown.png)

The current and all passed approval steps are listed in the approval step dropdown. Select an approval step in the list to see the status of the validations given by each of the teams that are configured for the step. An overview of the validations in all the steps can be found in the documents tab.

## 3. Under review table

In the under review table documents that are not yet submitted can be seen. This is what the under review table can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/04-under-review-table.png)

Members that are part of teams that are configured as reviewer teams for this approval request step will see one row per configured reviewer team they are part of. In the active approval request step, if there are still validation indications left to submit on behalf of any reviewer teams a member is part of, a yellow bar is displayed towards the top. When all documents are reviewed and validation indications have been submitted on behalf of each of the reviewer teams the bar towards the top will become green and get a checkmark.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/05-under-review-table.png)

> **Note:** The bar being green just means there are no teams you are part of that have any actions left in this approval request step, there might be other teams that still need to submit their validation indications before the approval request can advance to the next step. These can be seen in the step overview table below.

### 3.1 Columns in the under review table

**Team** Names of reviewer teams that are configured for this approval step in the approval workflow selected for this approval request by the approval request submitter. _Access required:_ Reviewer team member

**Pending** The amount of documents are yet to have received a validation indication in this approval request step. _Access required:_ Reviewer team member Review Click review to open the file review for the documents that have not yet received a validation indication or submission on behalf of a reviewer team in this approval request step.

**Reviewed** In the reviewed column amounts of rejected and approved validation indications are displayed. Any member of a reviewer team can have given this indication on behalf of the reviewer team. _Access required:_ Reviewer team member Submit Validation inidications that reviewer team members have given on behalf of a reviewer team can be submitted with the submit button. Click on the submit button to submit all validation indications on behalf of the reviewer team at once. Once the validation indication is submitted the document will no longer be under review and will disappear from the under review table.

## 4. Step overview table

In the step overview table an overview of the progress of all the reviewer teams for this step can be seen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/06-step-overview-table.png)

When validation indications are submitted for all documents the approval request advances to the next approval request step. Auto-approve can be configured in the workflow that the approval request submitter selected for this approval request. If auto-approve is enabled for an approval request step all documents that are still pending when the approval request step is due are approved automatically and the approval request will advance to the next approval request step.

### 4.1 Columns in the step overview table

**Team** Names of reviewer teams that are configured for this approval step in the workflow selected for this approval request.

**Pending** The amount of documents where a reviewer team member has not yet submitted a validation indication on behalf of the reviewer team in this approval request step.

**Rejected** The amount of rejection indications that have been submitted by a reviewer team member on behalf of a reviewer team in this approval request step.

**Approved** The amount of approved indications that have been submitted by a reviewer team member on behalf of a reviewer team in this approval request step.

**Progress** The progress of validation inducations that have been submitted by a reviewer team member on behalf of a reviewer team in this approval request step.

## 5. Approval request result

After the final approver team submits the final validaiton for all documents the approval request is closed the documents will start publishing:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/07-approval-request-result.png)

The result of the approval is displayed below the step overview:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/08-approval-request-result.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/09-approval-request-result.png)

Click [here](https://support.catenda.com/en/articles/12520773-approvals-troubleshooting) to read more about why the publishing of documents might fail.

### 5.1 View details

Click on view details to see the publishing results for each document.

**Status** The status of the publishing of the document The status can be one of the following: Published For documents that were given a final approval, the revision number of the shared revision is displayed with an arrow to the published revision that was created as a result of publishing this shared revision.

Publishing Failed For documents that were given a final approval that were not able to be published the reason they were not able to be published is displayed.

Set status For documents that were given a final rejection the status that the revision was updated with as a result is displayed.

**Name** The following are shown in the name column:

- Document file path
- Document icon
- Revision name of the document
