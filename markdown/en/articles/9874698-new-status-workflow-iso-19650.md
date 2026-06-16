# New status workflow - ISO 19650

The new status workflow is an on-demand feature that can be requested to be enabled for ongoing projects.

New projects that are created based on a template project where this feature is enabled have this feature enabled.

The ISO 19650 series is an international standard of good practice which defines

information management processes within a broader context of digital transformation in the construction industry.

Many stakeholders in the construction industry have adopted the ISO-19650 as the standard to manage document delivery and approval processes in projects.

This article contains information about the following topics:

**[Lifecycle](#h_df11c20404) - [Configuration](#h_4c1abfc510) - [Document tabs](#h_bfed4daf2c) - [Approval settings](#h_058046c316) - [Approval workflow](#h_01c3894c62) - [Disabling](#h_facc7dcaf1) - [Advantages](#h_8a5dec6f25)**

## **Lifecycle of a Document**

According to the ISO standard a document can have four different states;

### **🏗️ Work in Progress (WiP)**

Files that are being worked on and constantly overwritten on the user’s local environment. These files are typically only uploaded to catenda so people can see the users progress.

### **👥 Shared**

Files that are ready to be shared with other project members in order for coordination and final reviews of various trades and/or specialists to take place. These files are uploaded onto Catenda and sent to respective parties for review and approval.

### **📰 Published**

Files that are coordinated, finalized and accepted as a contractual deliverable. These files have gone through a review process and are deemed ‘ready for the next stage (construction, handover, quantity takeoff, permit issueance, etc.)’

### **📦 Archived**

The information has been used and can be archived in order to remain available if necessary afterwards (audit, creation of the file of works carried out, etc.)

### **Document states - ISO 19650**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/01-document-states-iso-19650.png)

### **Workflow on Catenda Hub**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/02-workflow-on-catenda-hub.png)

## **Configuring Status Workflow**

Activating and configuring the shared status workflow are reserved for project administrators. _Access required_

Document status configuration access in the [access control area](https://support.catenda.com/en/articles/4670273-project-settings-page#h_3b98ced32a) of the [project settings page](https://support.catenda.com/en/articles/4670273-project-settings-page).

Members with this access will only have access to the status configuration menu in document settings.

They will not be able to see or change the other menus in document settings.

Under [document settings](https://support.catenda.com/en/articles/7831371-document-settings) navigate to [Status Workflow](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) and enable shared statuses

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/03-configuring-status-workflow.png)

Define the shared and published statuses to be used in the project.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/04-configuring-status-workflow.png)

Set default shared status for new revisions.

New revisions will initially be uploaded as shared revisions that can late be published.

The default status therefore has to be a shared revision status.

This status will be selected in the upload dialogue for every document upload and can be changed to a different shared status in the upload process.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/05-configuring-status-workflow.png)

## **Familiar but different**

After activating the status workflow you will see two tabs appear above the documents and models tables.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/06-familiar-but-different.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/07-familiar-but-different.png)

### **Workspace**

All uploads of new revisions take place here.

The latest shared revision is displayed for each document and model.

### **Published**

A mirrored version of the workspace tab.

The same folder structure as in the workspace is displayed

Only documents and models with published revisions are displayed.

> **Note:** See shared revisions in the revision overview of the document preview, even if you opened the document from the published tab. _Access required:_ Shared revisions

### **Upload new shared revisions**

A revision status will be visible for each uploaded file in the upload dialogue.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/08-upload-new-shared-revisions.png)

A revision status will be applied for each file extracted from a zipped file.​

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/09-upload-new-shared-revisions.png)

### Publish shared revisions

**Multiple documents in document structure**

A publish action will be available in the existing element action menu of one or more selected documents with shared revisions.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/10-publish-shared-revisions.png)

**Single revision in document preview or document structure**

A publish action will be available as an icon and in the action menu of the revision info of a shared revision in the right information menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/11-publish-shared-revisions.png)

**Multiple models**

A publish action will be available in the revision info of a document with a shared revision in the right information menu in the document structure and in the document preview.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/12-publish-shared-revisions.png)

_Access required:_ Shared revisions

### **Access control**

After the status workflow is enabled you will see two new columns appear to the right of the access column in the acces control dialogue of a folder or document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/13-access-control.png)

The table below explains how the checkmarks affect the users experience for each access level.

- Check "can publish" for a member or team with write access to allow them to publish shared revisions and edit published revision statuses.
- Uncheck"view shared revisions" for a member or team with read access to so they only see official, published, revisions.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><h3 id="h_e9579ad9ca"><b>Shared Published Access</b></h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_dea1580c70">Read</h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_3c6b6d7d28">Write</h3></td></tr><tr><td><h3 id="h_a33339c27e">Can check "View shared revisions"</h3></td><td><p class="intercom-align-center">Can check. <br/>Unchecked by default.</p></td><td><p class="intercom-align-center">Always checked</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_e909b5dc48">Can check "Can publish"</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Never checked</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Can uncheck. <br/>Checked by default</p></td></tr><tr><td><h3 id="h_95374b8adf">View documents</h3></td><td><p class="intercom-align-center">Documents with only shared revisions are only visible if "view shared revisions" is checked</p></td><td><p class="intercom-align-center">Both documents with shared and documents with published revisions are visible</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_e401f7a37f">View shared revisions in document info</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Shared revisions are only visible if "view shared revisions" is checked</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Both shared and published reivisions are visible</p></td></tr><tr><td><h3 id="h_13cbc969df">Edit and view shared revision statuses</h3></td><td><p class="intercom-align-center">Viewed if "view shared revisions" is checked but not edited</p></td><td><p class="intercom-align-center">x</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_b228d7c432">Edit and view published revision statuses</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Can only view published revision status</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Edit if "Can publish" is checked, else only viewable</p></td></tr><tr><td><h3 id="h_13248acfd2">Publish documents</h3></td><td><p class="intercom-align-center">-</p></td><td><p class="intercom-align-center">Publish if "Can pubish" is checked</p></td></tr></tbody></table></div>

### **Major and minor revision numbers**

Shared revisions have a minor revision number (e.g. #0.1, #2.3, #4.1)

Published revisions have a major revision number ( #1, #2, #3 and so on)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/14-major-and-minor-revision-numbers.png)

### Opening the document preview

In the document structure you will see the latest revision you have access to.

Click on the name of a document to open the document preview of the displayed revision.

**Workspace tab**

The latest revision in the workspace tab can be:

Shared revision - _Access required:_ Shared revisions Published revision - ​_Access required:_ Read

**Published tab**

The latest revision in the published tab can be:

Published revision - _Access required:_ Read

> **Note:** Shared revisions can be visible in the revision overview of the document preview, even if you opened the document from the published tab. _Access required:_ Shared revisions

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/15-opening-the-document-preview.png)

### **Revision information**

Select a single document or open the document preview by clicking the document.

Information about the current revision will be visible in the [right information menu](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/16-revision-information.png)

- Publish the current revision with the publish action.

_Access required:_ Shared revisions

- Change a shared revision status to a different shared revision status.

_Access required:_ Read access and shared revisions

- Change a published revision status to a different published revision status.

_Access required:_ Write access and published revisions

**Revision information dialogue**

Click on the revision box to see an overview of all the revisions in the document in the [revision information dialogue](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision#h_6838c6ad71).

A green link between a published and a shared revision indicates which shared revision was published.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/17-revision-information.png)

### Shared and published revisions in Catenda Site

Only published revisions are visible in Catenda Site.

## Status configuration access

1. Edit access to the document status configuration can be configured from the [project settings page](https://support.catenda.com/en/articles/4670273-project-settings-page):

    <div class="intercom-container intercom-align-center"><img src="https://downloads.intercomcdn.com/i/o/areracg3/1211347568/082eb05dc3b18bf896b0aa148431/image.png?expires=1781092800&amp;signature=d7f11d11f4522d76f1afc39c4fa3c1abcf07d65ea6866337afc4f9aec43ea4a9&amp;req=dSImF8p6moRZUfMW3nq%2BgWPlnxx3jrC6fMrF99grkWaNrp00TWDQdpt0O4gd%0AVlMGdQrCecjFzy0uRBOfB7Z9eqY%3D%0A" width="500"/></div>

1. Documents status can be then [configured](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) from the settings in the documents section:

    <div class="intercom-container intercom-align-center"><img src="https://downloads.intercomcdn.com/i/o/areracg3/1211364420/5d6103d8c487ef0b43f8275be5e3/image.png?expires=1781092800&amp;signature=284c9ac52ff4057d8c2333ea2f752321f7ac99e4db9fe32cf5b00a50a2ab7aa1&amp;req=dSImF8p4mYVdWfMW3nq%2BgSPBqKtQx3mDN2RUxAGHVK4Zm%2BCeuCGeKk2Kpqj6%0Ao7QTpegJSCq1qQ64o2dJOULG6GY%3D%0A" width="500"/></div>

1. Finally, these document status can be assigned to file review status accessible from the top-right three dots button in the [Approvals section](https://support.catenda.com/en/articles/8349340-approvals-page). It is also possible to configure here a Topic template.

    <div class="intercom-container intercom-align-center"><img src="https://downloads.intercomcdn.com/i/o/areracg3/1211362235/ff7ea475a572749cba4247518058/image.png?expires=1781092800&amp;signature=ed641b32ce2b29ed26475385e36b8015832ce0fcc27dc7dd50942cd3942ef84f&amp;req=dSImF8p4n4NcXPMW3nq%2Bgcv5xnTzfFrfmLPu%2Fh%2FbaP0DptD%2Bm8oeC8vRpvPF%0AzFKQmL79JK7RcPLygqoKQ0CoqM4%3D%0A" width="500"/></div>

    <div class="intercom-container intercom-align-center"><img src="https://downloads.intercomcdn.com/i/o/areracg3/1211362345/59c0a70c13879eacc2b08c0db623/image.png?expires=1781092800&amp;signature=9c4b2b7d82aee40c7c1baccfdf0c17735a34889d51b5680e5824f7502d8f4289&amp;req=dSImF8p4n4JbXPMW3nq%2BgQL5wc3pBXVaAiE%2FNNg7wwK7Y9rNWq0G7M1E0M6c%0AgGNJ2NG26plHpZW4oC7Y%2F2YpO2M%3D%0A" width="300"/></div>

## **Approval workflow**

1. An approval workflow is created by an administrator.
    1. Submitter team
    1. Reviewer team (at least one approval step is required)
    1. Final reviewer team
1. A member of a submitter team submits an approval request with a set of shared revisons on the approvals page.
1. Members of the submitter teams assigned to the step review the documents submitted in the approval and give either an approved or rejected validation.
1. Once all the steps have been completed a member of the final reviewer team reviews the validations that have been submitted on behalf of the different teams in each step and gives their final validation of approved, approved with comment or rejected.
    1. The final approver is able to make a final, informed, decision on whether this document should be published (approved) or rejected (stay as shared)

### **Legacy approval workflow**

1. An Approval request nominates a Publisher (person in charge of making the final decision over the publication), and one or several Reviewers, in charge of validating (or not), the set of documents
1. Each reviewer will decide whether the shared document is Approved, Approved with comment, or Rejected
1. At the end of the review, the Publisher will choose the outcome of the approval, by picking the documents to be published.
1. From the approval settings, topics related to the documents may be created in order to keep track of the process later on

A detailed demonstration of those steps are shown in the following tutorial:

[YouTube video](https://www.youtube.com/embed/lDWKXWTtegU?rel=0)

## **Disabling status workflow**

If you want to turn status workflow flow off you can do so by clicking on the radio button in [document settings](https://support.catenda.com/en/articles/7831371-document-settings). The published and shared tabs in the document section will then disappear.

Documents uploaded while the status workflow is not enabled will be uploaded as published and will show in the published tab when the status workflow gets enabled.

## **Advantages of using the status workflow**

- The published tab serves as a designated area for contractual documents. Project members can easily find verified documents.
- Documents are validated before being published
- You can configure your delivery process based on the ISO 19650 much easier
- Coordination/collaboration documents are separated from contractual documents
- Multiple shared revisions can be selected and downloaded, where in the previous version drafts could only be downloaded one by one
- Limit what people can see in the mobile app Catenda Site
