# Approval Workflows: Admin Rules

> Guide for administrators detailing setup rules, flexible configuration options, post-submission parameter locks, and how project configuration changes impact active approval requests.

Approval workflows establish structured review and validation processes for shared document revisions within a project. Configuring workflows requires balancing template rules for future review requests with project team setups that drive active, ongoing approvals.

> **Note:** Only project administrators can access workflow configuration settings, create new approval workflows, or modify existing workflow parameters.

## 1. **1. How Project Changes Affect Approval Workflows**

When a workflow template is modified or project configurations are adjusted (such as adding or removing team members in project settings), the changes affect future and ongoing approval requests differently:

### 1.1 **1.1 Workflow Template Edits**

Changes made to a workflow template (such as adding submitter teams) apply to **future** approval requests created after the update. They do not rewrite the structure of active requests already in progress.

### 1.2 **1.2 Team Membership Updates**

Adding or removing team members in Project Settings takes effect immediately on **active, ongoing** approvals. If a review step is stalled because a team is empty, adding a user to that team allows them to immediately step in and resume the review.

### 1.3 **1.3 Broken Dependencies**

Archiving a document status, removing a team, or archiving an approval topic template elsewhere in project settings can cause validation errors when saving workflow updates or halt topic creation on ongoing approvals.

## 2. **Pre-Submission Setup (Initial Creation)**

When a new approval workflow is created for the first time, all foundational parameters must be configured before the template can be saved and activated.

### 2.1 **2.1 Mandatory Fields & Pre-Submission Warning Banner**

If any required field is incomplete when attempting to save a new workflow, the system displays a pre-submission warning banner across the top of the page and blocks template creation. Mandatory fields include:

- **2.1.1 Workflow Title**<br>A unique, descriptive name for the workflow.
- **2.1.2 Submitter Teams**<br>At least one project team assigned to launch approval requests.
- **2.1.3 Review Steps**<br>At least one review step containing an assigned reviewer team and a duration of at least **1 working day**.
- **2.1.4 Final Approval**<br>An assigned final review team alongside two active project document statuses—one mapped for approved revisions and one for rejected revisions.

### 2.2 **2.2 System Limits & Team Membership Rules**

**2.2.1 Pipeline Limits** A single workflow supports up to **10 sequential review steps** and a total of **20 reviewer teams** across the pipeline.

**2.2.2 Team Selection vs. Member Presence** During initial creation, the system validates that submitter, reviewer, and final reviewer teams are selected. However, it **does not** check whether those teams contain actual members.

**2.2.3 Execution Requirements & Auto-Approve** To make an approval request completable from start to finish:

- At least one submitter team member must be present in an assigned submitter team to launch the request.
- At least one reviewer team member must be present in an assigned reviewer team, unless auto-approve is enabled for that step.
- If auto-approve is configured, a step assigned to an empty team will automatically approve and advance once the step due date is reached.
- If auto-approve is not configured, an empty reviewer team will stall the approval request until a member is added to that team.
- At least one final reviewer team member must be present to render the final outcome.

**2.2.4 Administrator Rights** Project administrators do not hold automatic operational rights. To perform actions during an approval, an administrator must be an explicit member of the relevant team:

- **Submitter Team**<br>Required to launch an approval request.
- **Reviewer Team**<br>Required to indicate or submit a review validation.
- **Final Reviewer Team**<br>Required to render the final decision and close out the approval.

## 3. **3.** **Flexible Operations (Pre & Post-Submission)**

Certain operations remain flexible and can be adjusted during initial setup or updated at any point after a workflow is active. These flexible operations fall into two distinct categories: **Workflow Template Settings** (edited directly on the workflow setup page) **Project Team Member Management** (edited on the Project Teams page across all workflow roles).

### 3.1 **3.1** **Workflow Template Modifications**

These settings can be changed within the workflow configuration menu at any time, directly affecting future approval requests:

**3.1.1 Submitter Teams** Administrators can add or remove submitter teams post-submission to control which project teams are permitted to launch new approval requests under this workflow.

**3.1.2 Approval Topic Templates** Approval topic templates linked to specific outcomes (_Approved_, _Approved with Comments_, or _Rejected_) can be added, updated, or unlinked at any time to control issue tracking during reviews.

### 3.2 **3.2** **Project Team Member Management (Applies to All Team Types)**

Adding or removing individual users takes place on the **Project Teams** page and does not require editing or re-saving the workflow template. Crucially, member management applies to **all three workflow team types**, directly impacting who can perform actions:

**3.2.1 Submitter Teams** Adding or removing members changes who can select the workflow to launch new approval requests.

**3.2.2 Reviewer Teams** Adding or removing members changes who can access active review steps, add markups/comments, and submit step validation indications.

**3.2.3 Final Reviewer Teams** Adding or removing members changes who can render the final decision and close out an active approval request.

## 4. **4.** **Post-Submission Rules & Parameter Locking**

Once a workflow template is saved and submitted for the first time, key structural parameters lock to ensure consistent evaluation rules across approval requests.

### 4.1 **4.1 Locked vs. Editable Parameters**

**4.1.1 Locked Parameters** Time settings, review steps, assigned reviewer teams, step durations, auto-approve toggles, final approval teams, and mapped final document statuses cannot be altered after initial submission.

**4.1.2 Editable Parameters** Only the workflow title, submitter team assignments, and linked approval topic templates remain editable post-submission.

### 4.2 **4.2 Broken External Dependencies & Resolutions**

Saving **any** post-submission edit to an existing workflow (such as updating the title) triggers a full re-validation check across the entire template. If an element used in the workflow was archived or deleted in project settings after initial creation, re-validation fails until resolved.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 130px; padding: 8px;"><h3 id="h_5956ae53a6"><b>Dependency Issue (Blocker)</b></h3></td><td style="background-color: #e3e7fa80; width: 244px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_9b11612daf"><b>Impact &amp; System Behavior</b></h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_f245fc1acb"><b>Resolution</b></h3></td></tr><tr><td style="background-color: #00000000; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_aac48f326c"><b>Archived Document Statuses</b></h3></td><td style="background-color: #00000000; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>The mapped status field appears empty in workflow setup. Published documents receive the archived status (displayed as struck-through). Workflow updates are blocked.</p></td><td style="background-color: #00000000; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Recover (unarchive) the status</b> in Document Settings.<br/>Locked statuses cannot be edited or replaced inside the workflow post-submission.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_c963d16fb5"><b>Deleted Project Teams</b></h3></td><td style="background-color: #e8e8e880; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>A submitter, reviewer, or final approval team was deleted on the Project Teams page.</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Submitter Teams</b><br/>Edit the workflow directly to assign a new active team.<br/>​</p><p><b>Reviewer / Final Teams</b><br/>Locked. If no teams remain in a step and auto-approve is off, ongoing approvals stall forever. Archive the workflow, discard documents, and create a new workflow.</p></td></tr><tr><td style="background-color: #00000000; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_8d948d5649"><b>Archived Approval Topic Templates</b></h3></td><td style="background-color: #00000000; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>An approval topic template linked to a workflow outcome was archived on the Topic Templates page.</p><p></p></td><td style="background-color: #00000000; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Recover (unarchive)</b> the template on the Topic Templates page <b>OR</b> edit the workflow directly to select/add a new active replacement template.</p></td></tr></tbody></table></div>

### 4.3 **4.3 Archiving and Restoring Workflows**

**4.3.1 Archiving Workflows** Hides the active workflow from creation menus so project members cannot select it for new requests.

**4.3.2 Restoring Workflows** Re-enables an archived workflow in creation menus for assigned submitter teams.

## 5. **5.** **Impact on Ongoing Approvals & Team Lifecycles**

When project settings or team memberships change while approval requests are actively in progress, the system handles access, topic creation, and workflow progression according to specific rules.

### 5.1 **Adding and Removing Team Members**

Project members can be added to or removed from workflow teams on the **Project Teams** page at any time without editing the workflow template itself.

**5.1.1 Submitter Team Members** Adding a user to a submitter team lets them create new requests going forward. However, submitter team membership never grants shared visibility into requests created by teammates—access to a submitted request remains strictly personal to the individual creator.

**5.1.2 Reviewer Team Members** Adding a user to a reviewer team immediately grants them access to active approval requests currently at that review step. Removing all members from a reviewer team will freeze ongoing requests at that step until a new member is added—unless **auto-approve** is enabled for that step, in which case the request will automatically approve and advance when the step deadline passes.

**5.1.3 Final Reviewer Team Members** Adding a user to a final reviewer team immediately grants them access to render final decisions on active requests reaching the final approval step. Removing all members from a final reviewer team freezes ongoing requests at the final step until a user is added (auto-approve is not available for final review steps).

### 5.2 **5.2** **Deleting Teams from Project Settings**

Deleted project teams cannot be recovered. If a team assigned to a workflow is deleted from project settings, the operational impact depends on the team's role in the workflow lifecycle:

**5.2.1 Deleted Submitter Teams** Submitter teams remain editable post-submission. An administrator can edit the workflow configuration directly and assign a new active submitter team.

**5.2.2 Deleted Reviewer Teams** Review steps are locked post-submission.

- **If other assigned teams remain**<br>The review step continues to function for the remaining teams.
- **If no teams remain & auto-approve is ON**<br>The step automatically approves and advances once the step due date passes.
- **If no teams remain & auto-approve is OFF**<br>Ongoing approval requests stall indefinitely at that review step.

**5.2.3 Deleted Final Reviewer Teams** Final approval teams are locked post-submission, and auto-approve is **not** available for final review steps. If all final reviewer teams are deleted, ongoing approval requests are stalled indefinitely.

**5.2.4 Recommended Action for Stalled or Uncompletable Workflows** When a review step stalls with no remaining teams (and auto-approve is off), or when all final reviewer teams are deleted, the recommendation is to archive the broken approval workflow and discard all documents strictly from open approval requests that follow that specific workflow. Optionally, a new approval workflow can be created if a replacement is needed.

### 5.3 **5.3** **Approval Topic Template Archival & Reconfiguration Rules**

Approval topic templates are configured separately for each decision outcome (e.g., _Approved_, _Approved with Comments_, or _Rejected_). The system processes approval topic template changes independently per outcome:

**5.3.1 Outcome-Specific Isolation** Archiving or changing an approval topic template for one decision outcome only impacts that specific outcome. All other outcomes with intact approval topic templates continue creating topics as expected.

**5.3.2 Archiving a Linked Approval Topic Template** If an approval topic template assigned to an outcome is archived, ongoing approval requests following that workflow (and new requests submitted while unlinked) will **not** generate topics if that outcome is selected.

**5.3.3 Restoring an Archived Approval Topic Template** Recovering (unarchiving) the original approval topic template automatically re-enables topic creation according to that template across all associated approval requests.

**5.3.4 Configuring a Different Approval Topic Template** If an administrator updates the workflow post-submission to assign a _different_ active approval topic template, ongoing approval requests initiated prior to the edit will **not** generate topics using the new template. Only new approval requests submitted after the reconfiguration will generate topics based on the newly assigned template.
