# Approvals page

The approvals page can be found as a sub page to the [documents page](https://support.catenda.com/en/articles/8204673-documents-page) in the left navigation menu. Here an overview of the approval requests in the project can be found.

![](images/01-intro.png)

This article contains information about the following topics: _[Enable](#h_263c9d1268) - [Actions](#h_39a97bd06a) - [Search/filter](#h_95652579ee) - [Approval list](#h_aa4dfe69f5) - [Rows](#h_76de8831a3) - [Approval request cards](#h_e99a80135a) -_ [Approval requests and Document Revisions tabs](#h_aae5976a1d)

On the approvals page the following can be done:

- Each approval request can be reviewed and validated by the team before a final validation decides if the revisions that are requested to be approved should be approved or not.
- Configuration of the course and outcome of an approval can be made.
- New approvals can be created.

## 1. **Enabling the approvals page**

The approvals page is hidden by default. Enable shared revisions in [document settings](https://support.catenda.com/en/articles/7831371-document-settings-page) to reveal the approvals page. _Access required:_ Project administrator

> **Note:** In projects where shared revisions were enabled before 2 October 2025 the [legacy approvals page](https://support.catenda.com/en/articles/8349340-approvals-page-legacy) is displayed instead.

### 1.1 **Enabling from template project**

Projects created based on a template project where shared statuses were enabled will have shared statuses enabled and the approvals page will be displayed upon creation. Workflows are not carried over from project to project so in a new project a workflow has to be created for members to be able to start submitting approval requests.

## 2. **New item actions**

The new item actions can be found on the top right of the page.

![](images/02-new-item-actions.png)

### 2.1 **New approval request**

Click [here](https://support.catenda.com/en/articles/12495005-creating-a-new-approval-request) to read more about creating a new approval request.

**Access required:** A member has to at be part of a submitter team in a configured workflow to be able to submit a new approval request.

## 3. **Search or filter options**

![](images/03-search-or-filter-options.png)

Click [here](https://support.catenda.com/en/articles/12495060-filtering-on-the-approvals-page) to read more about filtering in the approvals page.

## 4. **Approval list**

Approval cards with visual ques about the content of each approval request that a member is part of are displayed in the approvals list.

This is what an approval request with full activity can look like:

![](images/04-approval-list.png)

Activity that occurs in the approval is displayed with amounts and icons on the approval card.

**Access required:** Request visibility is role-based: project members can view only requests they personally submitted, active requests assigned to a reviewer or final reviewer team of which they are a member, or all project requests in the case of project administrators.

- For detailed operational procedures on submitting revisions, adding review markups, and processing step validations or final decisions, read more [here](https://www.google.com/search?q=).
- For administrative guidance on configuring approval templates, managing locked parameters, and resolving broken dependencies, read more [here](https://www.google.com/search?q=).

## 5. **Document revisions list**

The second tab allows you to get an overview of all documents being reviewed across all opened approvals.

![](images/05-document-revisions-list.png)

The table displays:

1. the revision name
1. the revision number
1. the current review step
1. the current step's state
1. the due date for the step's review
1. the teams that still need to review the document
1. the approval request name
1. the submitter (individual and team)
1. the submission date

### 5.1 Filtering

Also, the left filter panel allows you to filter the documents by:

1. Assignment: all teams or your team specifically
1. Document state: Pending, Under review, Completed
1. Due date: all, upcoming, overdue

### 5.2 Sorting

Finally, you are able to sort by:

1. Revision name
1. State
1. Due date
1. Submission date

### 5.3 Searching

The text search allows you to search by revision name and approval request name.

## 6. **Row content**

### 6.1 **Open or closed approval row**

Opening the content of an approval request row that is under review or closed opens the [approval page](https://support.catenda.com/en/articles/12494960-open-or-closed-approval-request-page) for that approval.

### 6.2 **Draft approval row**

For draft approvals the [draft approval request page](https://support.catenda.com/en/articles/12495175-draft-approval-request-page) will open instead.

## 7. **Approval request cards**

### 7.1 **Title**

Approval title

### 7.2 **Draft status**

When an approval request has the status draft it is only visible to the person that created the draft on the approvals page.

![](images/06-draft-status.png)

The approval request is not visible in the approvals menu of the right menu of a revision.

### 7.3 **Open approval status**

When an approval request has the status open it is visible to all members that are part of teams involved in the request. Hover over statuses of approvals that are under review by more than one team to open a popup that shows which team have yet to submit their review in the current review step.

![](images/07-open-approval-status.png)

Reviewer teams that have already given their review do not show up in this list or count towards the amount of teams the approval step currently is under review by.

To the right of the open approval status the date and time the approval step must be reviewed by is displayed. If auto-approve is configured for this step the approval will automatically go to the next step on this date and time.

### 7.4 **Closed status**

When an approval request reached its final approval step it remains open. Based on the approvals and rejections given by each of the teams in each of the approval steps a member of the final approval team will be able to give their final approval or rejection. When the approval request is finally approved or rejected by the final approval team member it will be closed.

![](images/08-closed-status.png)

### 7.5 **Workflow**

The workflow that is being followed by the approval

### 7.6 **Created by**

The member that created the aproval and the date and time of when it was created.

### 7.7 **Final approval**

The final approval team that will have the final say on the publishing of the shared documents in the approval informed by the reviews submitted by the submitter teams in each of the approval steps.

### 7.8 **Approval number**

The number of the approval

### 7.9 **Bottom icons**

The current review step of the workflow that the approval is following. The total amount of steps the approval has to complete before the approval is finalized. Only visible on open and closed approvals. The amout of documents in the approval regardless of access settings.
