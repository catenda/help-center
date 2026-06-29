# Creating a new approval request

The new approval request action can be found for projects that enabled shared revisions after 2 October 2025. Clicking the action menu to the right of the green plus button on the [approvals page](https://support.catenda.com/en/articles/8349340-approvals-page) to create a new approval requets. Click on the new approval request button in the approvals menu of the right menu of a revision on the documents page where the latest revision is a shared revision to create a new approval request. This is what the create a new approval request dialogue can look like:

![New approval request Workflow Submitter Title Description (optional) Documents for review add documents name revision # Revision number Status Remove Cancel Save as draft Submit for review](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/01-intro.png)

Projects where shared revisions were enabled before 2 October 2025 will see the legacy create a new approval request dialogue instead.

## 1. Approval request header

This is what the header of a new approval can look like for projects that enabled shared revisions after 2 October 2025:

![New approval requst Workflow Submitter Title](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/02-approval-request-header.png)

### 1.1 **Workflow selection**

Members that are part of submitter teams configured in a project workflow can select between one of the workflows that their teams are configured for. The workflow that was previously selected is remembered. As long as the previously selected workflow is still available it will be selected once again next time an approval is created.

**Automatic selection** If only onle of the teams a member is part of is configured for a workflow, that workflow will automatically be selected. This is what it can look like when the workflow is automatically selected.

![Workflow Submitter Title](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/03-workflow-selection.png)

_Access requred:_ Members and administrators must be part of a submitter team configured for a workflow to be able to select the workflow.

### 1.2 **Submitter selection**

After a workflow is selected members who are part of multiple submitter teams configured for the workflow can select on behalf of which team they would like to submit the approval request. The submitter team that was previously selected is remembered. As long as the member is still part of the previously selected submitter team it will be selected once again next time an approval is created.

When the approval request is created members who are part of the selected submitter team will see the request while members that are part of the other possible submitter teams will only see the request if they are part of one of the reviewer teams or part of the final approval team that is configured for the workflow.

**Automatic selection** If a member is only part of one of the submitter teams that are configured for the workflow the submitter team is automatically selected when the workflow is selected.

![Workflow Submitter Title](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/04-submitter-selection.png)

_Access requred:_ Members and administrators must be part of a submitter team configured for a workflow to be able to submit on behalf of that submitter team.

### 1.3 **Title**

The title of the approval request. An approval must have a title to ​be submitted.

## 2. **Approval request body**

The new validation workflow is an on-demand feature that can be requested to be enabled when starting a new project. It is only possible to create a project based on a template project when the new validation workflow is not enabled in that template project. This is what the body of a new approval can look like for projects that enabled shared revisions after 2 October 2025:

![Approval Reqeust body Description (optional) Documents for review add documents cancel no documents added yet](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/05-approval-request-body.png)

### 2.1 **Description**

The description of the approval follows the [general formatting rules of posts](https://support.catenda.com/en/articles/8430847-formatting-of-posts).

### 2.2 **Add documents**

![Description (optional) documents for review add documents](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/06-add-documents.png)

Click [here](https://support.catenda.com/en/articles/12382093-add-revision-to-approval) to read more about adding shared revisions from documents to an approval request. While it is possible to add an infinite amount of documents here, the limit for submitting the approval request for review is 1000 documents.

### 2.3 **Documents for review table**

This is what the documents for review table can look like after shared revisions in each document that are to be validated have been added:

![Documents review table Name revision # Revision number Status Remove Cancel Save as draft Submit for review](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/07-documents-for-review-table.png)

**Columns** Based on the configured column order the first columns are displayed while the table might have to be scrolled sideways to show other enabled columns. The default order and visibility setting of the columns on the documents page is as follows:

_Name_ - _Default_ The name of the document that the shared revision is in. The document name is the same for all revisions in the document.

Revision - _Default_ The name of the document revision. This is the same as the orginal filename of the file that was uploaded.

## 3. - _Default_
The major and minor revision number of the shared revision (#0.1, #0.2, #1.1, etc...)

Status - _Default_ The name of the shared status that is applied to the shared revision.

Remove - _Default_ Click on the x in the remove column to remove the document that is to be reviewed from the documents for review list.

## 4. **Save as draft**

Edit approval request before it is submitted and locked.

### 4.1 **More than 1000 documents in drafts**

While it is possible to add as many documents to the add revision to appproval request dialogue, it is only possible to submit the dialogue with up to 1000 document revisions. To add more than 1000 document revisions with the new validation workflow, first add up to 1000 documents and save the approval request as a draft. Then add up to 1000 documents at a time to the draft approval request with the add documents actions on the draft approval request page before submitting the approval request.

### **Start review duration of step 1 when ready**

As soon as the approval request is submitted the reviewer teams configured in the first step of the selected approval workflow will be tasked with reviewing the revisions in the approval request during the duration of their approval step. The members in the reviewer teams will be able to review the revisions until the working days configured for their approval step are over. Save an approval request as a draft so it can be submitted as soon as the workflow is ready to begin.

Ensure that the teams are ready by communicating that their review step is about to begin before submitting the approval request workflow and starting the review duration of the first step for the reviewer teams configured in the selected workflow.

Ensure that the final publishing date of the worklfow ends up at the right time by making sure to align the total amount of working days in the workflow with the days of when the workflow is to be submitted by.

## 5. **Submit for review**

Click on submit for review to submit the approval and start the approval process. The following are required to submit the approval request for review:

- The workflow that the approval request will follow has to be selected.
- A submitter team to submit on behalf of has to be selected
- A title
- Documents
    - Minimum 1 document with a selected shared revision has to be added to be able to submit the approval.
    - Maximum 1000 document revisions with a selected shared revision can be added.
    - To create an approval request with more than 1000 document revisions, first create a draft with up to 1000 revisions and then add up to 1000 document revisions at a time to the draft before submitting the draft for review.

After submitting an approval request for review with the new validation workflow the only thing that can be changed is that shared revision documents can be discarded from the request.

_Start review duration of step 1 when ready_ As soon as the approval request is submitted the duration of the first review step that is configured in the approval workflow will begin.
