# Creating a new workflow

The new workflow page can be opened by clicking on the green plus button on [the workflows page](https://support.catenda.com/en/articles/12309903-workflows-page-document-settings) or clicking on the action in the new element action menu on [the approvals page](https://support.catenda.com/en/articles/8349340-approvals-page). It is only possible to create new workflows in projects where the new validation workflow has been requested to be enabled. The new validation workflow is an on-demand feature that can be requested to be enabled when starting a new project. It is only possible to create a project based on a template project when the new validation workflow is not enabled in that template project. This is what the title part of a new approval can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/01-intro.png)

## 1. **Title**

Enter the name of the workflow. This is the only part of the workflow that can be edited after it has been submitted.

### 1.1 **Requirement**

A title must be provided to be able to sumit a workflow.

### 1.2 **Approval contents**

This is what the contents of a new approval can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/02-approval-contents.png)

## 2. **Time settings**

Team members will have a limited amount of working days to review documents in review steps where their team has been set as a reviewer team. This is what the time settings of a new approval workflow can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/03-time-settings.png)

The time that is configured in time settings is the time for the working day to begin and end for each of these working days. Configure the time settings to match the team members whose teams are set as reviewer teams for review steps in this workflow. Team members will be able to submit their review within the given timeframe based on the amount of working days and the time configured in this field.

**Example of how time settings can be considered:** Submissions can be dated based on these times. A submission at 2 AM belongs to the previous day if time setting is set to 6 AM.

### 2.1 **Start time**

Chose between a value from 01 to 24 based on the 24 hour clock system otherwise known as military time.

### 2.2 **Selected timezone**

The default timezone is the timezone configured in your operating system. This is what a selected timezone list element can look like.

The first part of the selected timezone list element shows can display:

- A timezone abbreviation of timezones that do not have a summer or winter counterpart. These timezones stay the same all year around.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/04-selected-timezone.png)

- One or more geographical locations that follow the same timezone rules.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/05-selected-timezone.png)

### 2.3 **GMT offset**

The second part of the selected timezone list element displays the current GMT offset for the selected timzone list element.

The current timezone for the timezone list element is displayed. If the GMT offset for a geographical location changes to for example summer or winter time the GMT offset displayed for these geographical locations also changes.

### 2.4 **Selecting a list element in the timezone dropdown**

Click on the selected timezone list element to open the timezone dropdown. This is what the timezone dropdown can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/06-selecting-a-list-element-in-the-timezone-dropdown.png)

By default a list element can be seen for each thirty minute timezone offset interval that has an active timezone in the timezone dropdown.

**Timezone list element description** The first part for a timezone list elements can display:

- A timezone abbreviation

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/07-selecting-a-list-element-in-the-timezone-dropdown.png)

- One or more geographical locations that follow the same timezone rules.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/08-selecting-a-list-element-in-the-timezone-dropdown.png)

**Timezone list element name** The second part of a timezone list element can display:

- A timezone name.
For geographical locations where the timezone is the same all year around.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/09-selecting-a-list-element-in-the-timezone-dropdown.png)

- A GMT+XX:XX timezone offset
For geographical locations where the timezone changes during the year.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/10-selecting-a-list-element-in-the-timezone-dropdown.png)

**Timezone list element type** The last part for a timezone list elements can display:

- A timezone abbreviation

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/11-selecting-a-list-element-in-the-timezone-dropdown.png)

- A GMT+XX timezone offset

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/12-selecting-a-list-element-in-the-timezone-dropdown.png)

**Searching in the timezone dropdown** Search for a geographical location to find all timezone list elements for that location. If there is a match the location is included. It is not always listed as seen below.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/13-selecting-a-list-element-in-the-timezone-dropdown.png)

Some timezones can be searched by their short name in the first part of the list element.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/14-selecting-a-list-element-in-the-timezone-dropdown.png)

If a timezone is the same during the whole year it can be searched on in the second part of the list element. Search for a timezone to find all timezone list elements for that timezone.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/15-selecting-a-list-element-in-the-timezone-dropdown.png)

> **Note:** Different timezone list elements for the same timezone name can behave differently depending on the current time and date.

Search for a timezone type to find all timezone list elements for that timezone type: Either search for the timezone offset:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/16-selecting-a-list-element-in-the-timezone-dropdown.png)

Or the timezone abbreviation:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/17-selecting-a-list-element-in-the-timezone-dropdown.png)

Since some timezones have a GMT offesset as type it is often better to search for the full timezone name rather than the timezone abbreviation. Only timezones that are currently active are displayed so for timezones that change for geographical locations only the timezone that is currently active for that geographical location can be found.

## 3. **Submitters**

Select which teams members in the final approval team will see in the list of teams they can choose from when selecting a submitter team for an approval with this workflow. This is what the submitters part of a new approval workflow can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/18-submitters.png)

**Selecting a team the workflow creator is part of** If the workflow creator will be the one submitting these kinds of workflows it is important that a team the workflow creator is part of is added as a submitter team.

**Selecting an empty team** An empty team can be selected if the members that will be part of this team are not part of the project yet.

**Selecting a team with one member** Since it is not possible to add individual members, if only one member will work with this way of approving documents a team with only one member can be selected. After creating the workflow it will not be possible to edit it so even with one member a team allows for the flexibility of moving people in-and-out of that team.

> **Note:** It is only possible to select teams and not individual members

### 3.1 **Requirement**

At least one submitter must be selected to sumit the workflow.

## 4. **Review steps**

Build a multi-stage review process This is what the review steps part of a new approval workflow can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/19-review-steps.png)

### 4.1 **Step amount**

**No steps** While it is possible to create a workflow with no steps by deleting all steps it will not be possible to create an approval with this workflow as there has to be at least one step to be eable to submit an approval.

**Maximum amount of steps** The maximum step amount that a workflow can have is 10.

### 4.2 **Teams**

Select reviewer teams who will be able to participate in the review step. The maximum amount of teams a workflow can have is 20. Each team must submit their review before proceeding the wokflow advances to the next step. If auto approve is checked the workflow will automatically go to the next step after the configured amount of working days.

**Selecting a team the workflow creator is part of** If the workflow creator will be the one reviewing a step it is important that a team the workflow creator is part of is added as a reviewer team.

**Selecting an empty team** An empty team can be selected if the members that will be part of this team are not part of the project yet.

**Selecting a team with one member** Since it is not possible to add individual members, if only one member will work with this way of approving documents a team with only one member can be selected. After creating the workflow it will not be possible to edit it so even with one member a team allows for the flexibility of moving people in-and-out of that team.

### 4.3 **Working days to review**

Working days are defined as Monday through Friday. Public holdidays are included in the working days to review. _Minimum working days requried:_ 1 working day

Example: If it is the first step it will start as soon as the approval request is submitted. Otherwise it will start as soon as validations are submitted for each of the revisions in the previous step or it auto advanced and validated them.

The working days to review for an approval request step is set to 2 days.

If the start date for the approval step is on a Friday the due date will be set to:

- The start time that is configured in the time setting area of the wofklow
- On Tuesday the next week regardlses of whether that Tuesday is a public holdiday or not.

### 4.4 **Auto-approve**

Enable auto-approve to prevent bottlenecks - documents will automatically receive approved reviews on behalf of teams that haven't responded by the due date.

### 4.5 **Delete review step**

Click on the trashcan icon on the top right of a review step to delete it.

### 4.6 **Requirement**

If there are review steps each step must have at least one submitter to be able to sumit the workflow.

## 5. **Final approval**

Final approval will be given manually by a single team. This is what the final approval part of a new approval workflow can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/20-final-approval.png)

### 5.1 **Team**

The final appproval team that will give the final approval based on the reviews of each of the reviewer teams.

**Selecting a team the workflow creator is part of** If the workflow creator will be the one giving the final validation of the approval it is important that the publisher team is a team the workflow creator is part of.

**Selecting an empty team** An empty team can be selected if the members that will be part of this team are not part of the project yet.

**Selecting a team with one member** Since it is not possible to add individual members, if only one member will work with this way of approving documents a team with only one member can be selected. After creating the workflow it will not be possible to edit it so even with one member a team allows for the flexibility of moving people in-and-out of that team.

### 5.2 **Working days to approve**

The amount of working days the final aproval team has to configure the final approval. _Minimum working days requried:_ 0 working days

### 5.3 **Review state**

Approved or rejected

### 5.4 **Final status**

Select the final status for approved and rejected documents. Approved documents will be published, Rejected documents will not be published.

### 5.5 **Requirement**

A final approval team must have been selected to be able to sumit the workflow. A final status for approved workflows must be selected to be able to sumit the workflow. A final status for rejected workflows must be selected to be able to sumit the workflow.

## 6. **Submit**

Click on submit to submit the workflow.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/21-submit.png)

### 6.1 **Required field warning**

If the workflow is missing a required field a warning towards the top of the page will ask for the missing fields to be filled out. This is what the warning can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/22-required-field-warning.png)

The following are required to submit a new workflow:

- A title.
- At least 1 submitter team has to be selected.
- At least 1 reviewer team has to be selected per workflow step.
- At least 1 working day has to be configured per workflow step.
- A final approval team has to be selected
- A final status for approved workflows has to be selected
- A final status for rejected workflows has to be selected

### 6.2 **Locked after submitting**

After submitting it will only be possible to change the title of the workflow.
