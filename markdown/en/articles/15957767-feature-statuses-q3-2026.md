# Feature statuses Q3 2026

To prevent against notification spam and to ensure a smooth launch new behavior or changes to existing behavior can be rolled out gruadually and without notice. Those that notice changes in behavior of a part of a page they use frequently or those that wonder what is new can consult these articles for updates on recent changes in behavior for all users.

## 1. **New features**

Each user uses the platform diffrently. Even if a new feature is released or changes are made to a feature it could be that users might not be using that part of the feature. For those that are curious what "that new button" or "that new page" is on the platform this article contains an introduction of what the change is about. For these features often only basic or slightly outdated support material is available as this gets updated as we go. Along with helping people out in support the articles often get updated and if questions that were asked can quickly be found explained in an article the next week.

### 1.1 **Figma URL Link unfurling in topics**

Raw url links and markdown formatted url links to figma boards now unfurl and display the figma board in topic descriptions and comments.

### 1.2 **Account language setting**

Romanian is now available as a user interface language.

### 1.3 **Kanban view for topics**

A new kanban view is made available on the topics page. Find it towards the top right of the topic board next to the list and table views. Organize, filter, and update topics directly on a Kanban board, improving issue management, task management and team collaboration in Catenda Hub.

### 1.4 **Catenda AI Connect**

The Catenda AI Connect is now live, bringing advanced intelligence seamlessly into your existing workflows. This capability can be unlocked as a feature extension for existing project licenses, or requested directly by external project members. Contact our support team to request enablement for your workspace.

### 1.5 **Catenda Data Export**

Catenda Data Export is now available, providing flexible recurring or one-time extractions tailored to your total export size. Existing clients can integrate this capability across their current projects, while external project members can request standalone access. Get in touch with our support team to configure and enable this feature. Export to Amazon S3 or Azure Blob storage

### 1.6 **QR codes on PDF drawings**

A QR code tool is now available in the document preview toolbar on shared revisions. The placeholder can be placed directly on the PDF in Catenda Hub. Previously the placeholder image had to be downloaded from the Help Center and added to the file in a PDF editor before uploading. That is no longer necessary.

**Two conditions apply:** The tool only appears on shared revisions, so the project needs the status workflow enabled. Projects where every upload is published immediately do not have a shared revision step to place it on. The document must be in a folder with Assign QR code set to yes. Only then is the placeholder recognised on publishing and replaced with a scannable Catenda QR code for that revision.

The placeholder is placed on the shared revision, and the QR code is generated when that revision is published. This works both when publishing from the document section and when publishing happens as part of an approval workflow. QR Codes are placed one document at a time. 📽️ **[Tutorial video](https://eu.guidde.com/share/playbooks/cdpo9DyYmZWxWvRUrR7LWb?origin=6VMUQTF9wwUsoREWtvRVGILBqzz1&mode=videoAndDoc)**

### 1.7 Whiteboard links displayed in Hub

A link to a Figma, FigJam or Miro whiteboard can be placed in a topic description or a topic comment, and the whiteboard is then displayed underneath the text. This is the whiteboard from the external service, not the topic board the topic itself sits on. Add the link the same way as any other link in the markdown editor, either as a plain URL or as a markdown formatted link. The whiteboard appears below the description or comment once it is saved. The whiteboard is only displayed to users who are already signed in to Figma or Miro and who have access to it there. Catenda does not grant access, access is controlled entirely in Figma or Miro, so a user without access sees no whiteboard content.

## 2. **Updated features**

### 2.1 **Approval improvements**

The new validation flow that was released in Q3 2025 deserved some more love. The following features have been added as a follow-up release to the new approval workflow:

**👁 [Visibility on individual reviewer status (3:14):](https://eu.guidde.com/share/playbooks/oAoCAVdJVGQzMTBYvNPHtm?origin=7PqdD6oPp9QLchKHNkCwDH3opRS2&mode=videoAndDoc)** get a quick overview of each member's activity within a team assigned to an approval step, so you can clear blockers fast. **[Pt. 2 Video (3:26)](https://eu.guidde.com/share/playbooks/7fc2J2cZfisYp4VnUF2szF?origin=7PqdD6oPp9QLchKHNkCwDH3opRS2&mode=videoAndDoc)** **📄 [Documents across all open approvals in one view (3:41):](https://eu.guidde.com/share/playbooks/wWhdRkGbbziaHbnbD9Gj8Y?origin=6VMUQTF9wwUsoREWtvRVGILBqzz1&mode=videoAndDoc)** instantly see the documents that need your attention, without opening individual approval requests. **🖱 [One-click access to the review page (2:05):](https://eu.guidde.com/share/playbooks/6e4dQJDoPfjAY84XU282Xp?origin=6VMUQTF9wwUsoREWtvRVGILBqzz1&mode=videoAndDoc)** jump straight to the review page and start reviewing. **✅ [Require sign-off by all team members (3:20):](https://eu.guidde.com/share/playbooks/mnNWejVsSnJoH56aHpft5z?origin=6VMUQTF9wwUsoREWtvRVGILBqzz1&mode=videoAndDoc)** be certain every member of the review team has reviewed the document before it moves on.

**Editing an approval's title and description** The title and description of an approval can now be edited after it has been submitted. Previously both were fixed at creation, so a typo or a title that no longer matched the scope of the request meant living with it for the life of the approval, or cancelling and starting again. Editing is limited to the person who created the approval, and to project administrators. Being a member of a submitter team is what allows an approval to be created, but it does not carry the right to edit approvals created by other members of the same team. If a colleague created it, the edit is not available, the creator or a project administrator has to make the change.

**Long descriptions in the approval overview** Long approval descriptions are handled better in the approval overview, so a long description no longer pushes the rest of the information out of view.

**Teams column in the documents-across-approvals table** The teams column in the table of documents across all open approvals has been improved, making it easier to see which team is expected to act on each document.

### 2.2 **Document compare: compare text, not just pixels**

Document compare now has a text compare mode alongside the existing overlay mode. Text compare reads the actual text content of two revisions and highlights every wording change, so a specification or contract can be checked in seconds rather than read line by line. Overlay mode is unchanged and remains the right choice for drawings and geometry, where a pixel comparison is what is needed. Both modes sit behind the same Compare action in the document viewer, so the mode that fits the document can be chosen there. Compare requires a PDF with at least two revisions of the same document. The Compare button appears next to the revision dropdown when those conditions are met. If it is not visible, the document is either not a PDF or has only one revision. 📽️ **[Tutorial video](https://eu.guidde.com/playbooks/9hrXCk2DMw75wrspDCvJDv?origin=6VMUQTF9wwUsoREWtvRVGILBqzz1&mode=videoAndDoc)**

## 3. **Enabling on-demand features**

Each on-demand feature is production-grade and ready for real project use. While these features have been tested to work as they should there can be varying degrees as to how many projects have started using these features so unknown edge-cases might be found. While changes might happen as we work to make these features available to all users data that is submitted in these features will not be deleted.

### 3.1 **Requesting for on-demand features to be enabled**

Some features can be requested to be enabled for existing projects by the contact person for your Catenda license while others can be enabled with a setting in the project. When an on-demand feature is requested to be enabled, a meeting will be set up with a support representative to discuss the current status of the feature. If a project is not already available where the on-demand feature can be tested a dummy project can becreated for a limited time where the on-demand feature can be tested to consider if the feature is ready to be used.

### 3.2 **Report editor**

Create report templates for topics and documents so project members can select topics or documents from the table and use the report action to generate a report. The reports page is an on-demand feature that can be requested to be enabled for ongoing projects. New projects that are created based on a template project where this feature is enabled do not have this feature enabled. Separate templates can be created for topics and documents. When a template is available in a project the report action can be used with selected topics and documents to generate a report based on the selected template. Support for how different values can be displayed on the page is offered by Catenda. If you would like a custom report tailored to your company we can get you in contact with a consultant that can help with this.
