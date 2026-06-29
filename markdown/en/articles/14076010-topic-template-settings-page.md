# Topic template settings page

> Manage your topic template settings

The topic template settings page can be found by clicking on Configure topic templates on the [topic settings page](https://support.catenda.com/en/articles/14183429-topic-settings-page) that can be opened from the left navigation menu after opening the topics page. _Access required:_ Project administrator

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/01-intro.png)

On the topic template settings page topic templates for each of the topic boards in the project can be configured. After their creation, topic templates are made available automatically fill out text and fields of topics upon creation. Topic templates can be configured to be made available in the following topic creation processes: [How to use topic templates in general topics](https://support.catenda.com/en/articles/14075921-apply-a-general-topic-template-upon-topic-creation) [How to use topic templates in markup topics](https://support.catenda.com/en/articles/14078352-apply-a-document-topic-template-when-creating-a-markup-from-a-document) [How to use topic templates with approvals](https://support.catenda.com/en/articles/14078683-apply-an-approval-topic-template-to-an-approval-workflow-template)

## 1. **Action menu**

Click the plus button towards the top right top open the action menu. This is what the action menu towards the top right in on the topic template settings page can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/02-action-menu.png)

A dropdown menu will give the option to create 3 distinct types of topic template. Topic templates are distinguished to three different template types as the variables that can be used to automatically fill out text and fields in the topics upon creation differ depending on the topic creation process that is used.

## 2. **Search or filter options**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/03-search-or-filter-options.png)

### 2.1 **Search**

_Text search -_ `search=\<Search phrase>` After entering characters in the search or filter bar, the first suggested filter changes to the text search.

**Content that can be searched on** Topic template name

**Capitalization** The text search is not sensitive to upper or lowercase characters.

**Character amounts** Any amount or type of character can be searched on.

**Whitespace** Whitespace characters at the beginning of a search phrase can be searched on but are removed from the template names so there will be no results when searched. Whitespace characters at the end of a search phrase are removed.

### 2.2 **Filtering in the filter menu**

Topic templates are either filtered by one of the possible statuses Click on the Status menu in the fitler menu to hide the option status that is not filtered. It is possible to press the X to the right in the search bar to remove the fitler tags from the bar but this has no effect. It is only possible to either filter templates with the Active or the Archived filter.

_Active_ - `status=active` - Default Topic templates that can actively be used and configured to generate topics.

_Archived_ - `status=archived` Topic templates that are not available to be used or configured in the topic generation process.

## 3. **Templates table**

Once you navigate to your topic template settings page, an overview on existing topic templates that have previously been created can be seen. This is what the topic templates table can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/04-templates-table.png)

Click [here](https://support.catenda.com/en/articles/11748020-tables-on-catenda) to read more about how to work with tables in Catenda.

### 3.1 **Row content**

Click on a topic row to open the topic template content page for that template.

### 3.2 **Columns**

All columns in the topic templates table are enabled by default. Based on the configured column order the first columns are displayed while the table might have to be scrolled sideways to show other enabled columns. The default order and visibility setting of the columns on the documents page is as follows:

Name Template type Created by Created at Status Topic board

## 4. **Create a new general topic template**

Can be used on topics created from the general Topic section. Here are the different actions you need to follow and variables you can input when creating a new general topic template:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/05-create-a-new-general-topic-template.png)

1. **Topic Board**: The topic board within which the general topic template can be generated.
1. **Template Name**: The template name can be selected from the dropdown menu during creation, or updated in the settings later if needed.
1. **Topic Title**: The resulting topic title after creating the topic from the general topic template.
Hover your mouse on the "?" icon located on the top right-side of the title box to see how you can customize your topic template title with the available variable: `topicCreator`.
​

    <div class="intercom-container intercom-align-center"><img height="184" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-272165f584d2.png" style="height: auto;" width="300"/></div>

1. **Topic Status**: The resulting topic status after creating the topic from the general topic template.
1. **Topic Type**: The resulting topic type after creating the topic from the general topic template.
1. **Milestone**: The resulting topic milestone after creating the topic from the general topic template.
1. **Assigned to**: The resulting topic assignee (project member or team) after creating the topic from the general topic template. You can use here the `Topic Creator` variable to automatically populate this field with the topic creator if needed.
​

    <div class="intercom-container intercom-align-center"><img height="94" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-c7f3d7220c54.png" style="height: auto;" width="150"/></div>

1. **Requested by**: The resulting topic requester after creating the topic from the general topic template. You can use here the `Topic Creator` variable to automatically populate this field with the topic creator if needed.
​

    <div class="intercom-container intercom-align-center"><img height="93" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-43e4955bfdd8.png" style="height: auto;" width="150"/></div>

1. **Labels**: The resulting topic labels after creating the topic from the general topic template.
1. **Description**: The resulting topic description after creating the topic from the general topic template. This section supports the Markdown format and you can use its full potential to format the text, create custom headers and checklists. 
Hover your mouse on the "?" icon located on the top-right corner of the description box to see how you can make use of all available features (mention teammates and link existing topics) and variables (such as `topicCreator` in the case of the general topic template).

    <div class="intercom-container intercom-align-center"><img height="291" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-d2735ca1aec8.png" style="height: auto;" width="300"/></div>

Once you are done setting up your new general topic template, you can click on the "Save" button at the bottom right.

## 5. **New document topic template**

Can be used on topics created from Markups on Documents. Here are the different actions you need to follow and variables you can input when creating a new document topic template:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/06-new-document-topic-template.png)

1. **Topic Board**: The topic board within which the document topic template can be generated.
1. **Template Name**: The template name can be selected from the dropdown menu during Markup creation, or updated in the settings later if needed.
1. **Topic Title**: The resulting topic title after creating the topic from the document topic template.
Hover your mouse on the "?" icon located on the right side of the title box to see how you can customize your document topic template title with the available variables: `documentName`, `fileName`, `markupName` and `topicCreator`.
​

    <div class="intercom-container intercom-align-center"><img height="231" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-dbe5030f1082.png" style="height: auto;" width="300"/></div>

1. **Topic Status**: The resulting topic status after creating the topic from the document topic template.
1. **Topic Type**: The resulting topic type after creating the topic from the document topic template.
1. **Milestone**: The resulting topic milestone after creating the topic from the document topic template.
1. **Assigned to**: The resulting topic assignee (project member or team) after creating the topic from the document topic template. Different variables can be used here, such as `Document owner`, `File uploader`, `Markup creator`, `Publisher` and `Topic creator`.

    <div class="intercom-container intercom-align-center"><img height="228" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b3156a6c2724.png" style="height: auto;" width="150"/></div>

1. **Requested by**: The resulting topic requester after creating the topic from the document topic template. Different variables can be used here, such as `Document owner`, `File uploader`, `Markup creator`, `Publisher` and `Topic creator`.
​

    <div class="intercom-container intercom-align-center"><img height="171" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-0c4680dfae06.png" style="height: auto;" width="150"/></div>

1. **Labels**: The resulting topic labels after creating the topic from the document topic template. Note that you can fetch the labels from the document you created the Markup from using the variable `Labels from documents` below:
​

    <div class="intercom-container intercom-align-center"><img height="67" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-522016d4b8ae.png" style="height: auto;" width="500"/></div>

1. **Description**: The resulting topic description after creating the topic from the document topic template. This section supports the Markdown format and you can use its full potential to format the text, create custom headers and checklists. 
Hover your mouse on the "?" icon located on the top-right side of the description box to see how you can make use of all available features (mention teammates and link existing topics) and variables (such as `documentName`, `fileName`, `markupName` and `topicCreator` in the case of the document topic template).

    <div class="intercom-container intercom-align-center"><img height="349" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b8f3e2dabde9.png" style="height: auto;" width="300"/></div>

Once you are done setting up your new document topic template, you can click on the "Save" button at the bottom right.

## 6. **New approval topic template**

Can be used on topics generated after an approval workflow has been closed. _Access required:_ Shared statuses enabled (Workspace and published tabs visible on documents and models pages)

> **Note:** This option only appears if the current status and validation workflows are in use. Projects created after 2 October 2025 automatically use the current status and validation workflows.

Here are the different actions you need to follow and variables you can input when creating a new approval topic template:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/07-new-approval-topic-template.png)

1. **Topic Board**: The topic board within which the approval topic template will be generated after an approval workflow is closed.
1. **Template Name**: The template name of an approval topic template can be selected from the dropdown menu in an approval workflow template, or updated in the settings later if needed.
1. **Topic Title**: The resulting topic title after the associated approval workflow is closed.
Hover your mouse on the "?" icon located on the right side of the title box to see how you can customize your approval topic template title with the available variables: `approvalRequestName`, `approvalRequestNumber`, `documentName`, `fileName`, `markupName` and `topicCreator`.
​

    <div class="intercom-container intercom-align-center"><img height="272" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-6038b1d41fed.png" style="height: auto;" width="300"/></div>

1. **Topic Status**: The resulting topic status after closing the associated approval workflow.
1. **Topic Type**: The resulting topic type after closing the associated approval workflow.
1. **Milestone**: The resulting topic milestone after closing the associated approval workflow.
1. **Assigned to**: The resulting topic assignee (project member or team) closing the associated approval workflow. Different variables can be used here, such as `Approval request approver`, `Approval requested approver team`, `Approval request submitter`, `Approval request submitter team`, `Document owner`, `File uploader`, `Markup creator`, `Markup creator team`, `Publisher`.

    <div class="intercom-container intercom-align-center"><img height="182" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b012d92ee132.png" style="height: auto;" width="150"/></div>

1. **Requested by**: The resulting topic requester after closing the associated approval workflow. Different variables can be used here, such as `Approval request approver`, `Approval requested approver team`, `Approval request submitter`, `Approval request submitter team`, `Document owner`, `File uploader`, `Markup creator`, `Markup creator team`, `Publisher`.
​

    <div class="intercom-container intercom-align-center"><img height="181" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-d7986adac70c.png" style="height: auto;" width="150"/></div>

1. **Labels**: The resulting topic labels after closing the associated approval workflow. Note that you can fetch the labels from the document you created the Markup from using the variable `Labels from documents` below:
​

    <div class="intercom-container intercom-align-center"><img height="67" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-522016d4b8ae.png" style="height: auto;" width="500"/></div>

1. **Description**: The resulting topic description after closing the associated approval workflow. This section supports the Markdown format and you can use its full potential to format the text, create custom headers and checklists. 
Hover your mouse on the "?" icon located on the top-right corner of the description box to see how you can make use of all available features (mention teammates and link existing topics) and variables (such as `approvalRequestDueDate`, `approvalRequestFileLink`, `approvalRequestLink`, `approvalRequestName`, `approvalRequestNumber`, `documentName`, `fileName`, `markupName`, `topicCreator`) in the case of the approval topic template).
​

    <div class="intercom-container intercom-align-center"><img height="449" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-f3f078b5d2af.png" style="height: auto;" width="300"/></div>

Once you are done setting up your new approval topic template, you can click on the "Save" button at the bottom right.
