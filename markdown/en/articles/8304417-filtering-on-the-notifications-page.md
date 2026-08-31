# Filtering on the notifications page

Both in your [notification settings](https://support.catenda.com/en/articles/8272435-notification-settings) and in your [project notification settings](https://support.catenda.com/en/articles/4670262-project-specific-notification-settings) you will be able to configure which notifications you would like to receive.

In which situation a notification gets sent for the different settings will be explained in this article. After the notification is sent it can be found again on the [account notifications page](https://support.catenda.com/en/articles/7439223-account-notifications-page) and the [project notifications page](https://support.catenda.com/en/articles/4670295-project-notifications-page) by opening the filter menu button on the left.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/810mbm4a/01-intro.png)

## 1. **Notification history**

Notifications start to be sent out to a member as soon as they have joined a project. History of notifications in a project therefore goes back to the time a project was joined. Members that have been part of the project for longer might therefore been able to catch past events that new members have not.

## 2. **Filters**

Click the filter button on the top left for a panel to appear on the left side. When a filter is applied, the URL visible in the browser changes with it. In this article filters are displayed like so:

### 2.1 **_Filter name in menu_ - `Filter name in URL=Filter option in URL`**

**Default filter** The default filter is initially not visible in the URL. When the page is navigated to for the first time the following filter is applied.

### 2.2 _From a month ago_ - `dateFrom=last-month`

### 2.3 **Save and share the current filter**

Go to the URL of a filtered page to load that page with the filter applied. The applied filters can be saved towards the top of the filter menu. Click [here](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) to read more about how to save and share filters

### 2.4 **Hide empty filters**

Click [here](https://support.catenda.com/en/articles/8551755-saving-filters) to read more about limiting filter results.

## 3. **Date filters**

With the date filter you can select a timeframe for when notifications were sent.

### 3.1 **From a week ago** - `dateFrom=last-week`

Notifications from the past week.

### 3.2 **From a month ago** - `dateFrom=last-month`

If you navigate to the account notifications page it will be filtered by last months notifications by default.

### 3.3 **From a year ago** - `dateFrom=last-year`

Notifications from the past year.

### 3.4 **Pick a date** - `date-from=<Epoch Unix Timestamp>&date-to=<Epoch Unix Timestamp>`

Read [this](https://support.catenda.com/en/articles/6511685-date-filter) article to learn how to easily select dates on the page.

### 3.5 **All notifications**

To see all notifications you have ever received remove the dateFrom filter from the URL.

## 4. **Type**

The type menu includes all filterable notification types.

Notifications are divided in the following types:

## 5. **All** - `type=all`

All notifications are sent both in the browser and via email by default. If you go to a notifications page, it will be filtered by last months notifications by default. If you remove the dateFrom filter from the URL and use the type=all filter you will be able to get see all notifications you have ever received.

## 6. **Models** - `type=models`

_New model -_ `type=new-model` The notification shows the name of the model that was created.

**Notification click takes you to:** Model overview page of the project the model is created in.

**Notification setting option:** A new model is created

### 6.1 **Sent even if all checkboxes are unchecked in settings**

_Checkin failed_ - `type=checkin-failed` If the formatting of your IFC file is somehow not recognized by our system

_Import failed_ - `type=import-failed` Could happen if your connection was interrupted while uploading.

_Import completed_ - `type=import-completed` When a model is finished processing

**Notification setting option:** A new revision is imported

_Export success_ - `type=export-completed` When you model export has successfully finished zipping and is ready for download.

**Notification setting option:** A new export is created

## 7. **Topics** - `type=issues`

### 7.1 **New topic** - `type=new-issue`

This is the only notification you get about a topic if you are not [following](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) the topic. Assignees, requestees and members that are mentioned in topics are automatically following the topic and will get the notifications below.

**Notification setting option:** A new topic is created

### 7.2 **New comment** - `type=new-comment`

If you are neither the assignee nor the requestee of the topic but are [following](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) the topic you will get this notification.

This can happen if you were previously [assigned](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9), [requester](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [mentioned](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) or [manually followed](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) the topic. If you would not like future notifications of this topic you can unfollow the topic in its [right information panel](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue). _Notification setting option: assigned to me_ A topic is assigned to you

**Notification setting option: requested by me** A topic is requested by you

**Notification setting option: followed by me** A topic is followed by you

### 7.3 **Assigned to me** - `type=issue-assigned`

**Notification setting option:** A topic is assigned to me

### 7.4 **Team assigned** - `type=issue-team-assigned`

When a team is assigned to a topic

**Notification setting option:** A topic is assigned to me

### 7.5 Mentioning me - `type=issue-mentioned`

**Notification setting options:** A topic is mentioning me or one of my teams

### 7.6 **Team mentioned** - `type=issue-team-mentioned `

**Notification setting options:** A topic is mentioning me or one of my teams

### 7.7 **Status updated** - `type=status-updated`

If you are neither the assignee nor the requestee of the topic but are [following](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) the topic you will get this notification.

This can happen if you were previously [assigned](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9), [requester](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [mentioned](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) or [manually followed](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) the topic. If you would not like future notifications of this topic you can unfollow the topic in its [right information panel](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue). _Notification setting option: assigned to me_ A status is updated in a topic assigned to you

**Notification setting option: requested by me** A status is updated in a topic requested by you

**Notification setting option: followed by me** A status is updated in a topic followed by you

### 7.8 **Type updated** - `type=type-updated`

If you are neither the assignee nor the requestee of the topic but are [following](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) the topic you will get this notification.

This can happen if you were previously [assigned](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9), [requester](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [mentioned](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) or [manually followed](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) the topic. If you would not like future notifications of this topic you can unfollow the topic in its [right information panel](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue). _Notification setting options:_

Assigned to me - A type is updated in a topic assigned to you

Requested by me - A type is updated in a topic requested by you

Followed by me - A type is updated in a topic followed by you

### 7.9 **Sent even if all checkboxes are unchecked in settings**

### 7.10 **Move success** - `type=issues-move-success`

Shows the amount of topics that were moved and to which topic board they were moved.

### 7.11 **Move failed** - `type=issues-move-failed`

Shows the amount of topics that failed to move and to which topic board they failed to move to.

### 7.12 **Import failed** - `type=issues-import-failed`

Shows what type of topic import failed to import and which topic board it failed to import to. _Possible topic import types:_ BCF

### 7.13 **Import completed** - `type=issues-import-success`

Shows what type of topic import was successfully imported and which topic board it was imported to. _Possible topic import types:_ BCF

### 7.14 **Export failed** - `type=issues-export-failed`

Shows what type of topic export failed and which topic board it failed to export from. _Possible topic export types:_ BCF 2.0, BCF 2.1, BCF 2.0, PDF, Excel

### 7.15 **Export success** - `type=issues-export-success`

Shows what type of topic export successfully imported and which topic board it was exported from. _Possible topic export types:_ BCF 2.0, BCF 2.1, BCF 2.0, PDF, Excel

## 8. **Documents** - `type=documents`

### 8.1 **Document added** - `type=document-created`

_Notification setting option:_ A document or a folder is created

### 8.2 **New document revision** - `type=document-revision-uploaded`

_Notification setting option:_ A new document revision is uploaded

### 8.3 **Virus detected** - `type=document-file-infected`

If a document is detected to be infected with a virus a notification will receive a notification regardless of email summary setting. A notification will also be sent to the administrators in the project of the infected document. The notification will state who uploaded what document where.

If your email notifications are completely off this notification will not be sent as an email notification. You will still get the notification in Catenda Hub even if Catenda Hub notifications are turned off.

> **Note:** This notification will be sent even if all notifications have been disabled

### 8.4 **Document removed** - `type=document-deleted`

_Notification setting option:_ A document or a folder is deleted

### 8.5 **Documents removed** - `type=documents-deleted`

_Notification setting option:_ A document or a folder is deleted

### 8.6 **Documents uploaded** - `type=documents-uploaded`

_Notification sent if:_ A document has been uploaded by another user

### 8.7 **Document approval**

**Notification setting options:** I am set as the publisher in an approval request A team I am a member of is set as the publisher in an approval request I am set as a reviewer for an approval request New comment in approval request

### 8.8 **Zip extraction complete**

_Notification sent if:_ A zip folder is successfully imported.

> **Note:** This notification will be sent even if all notifications have been disabled

### 8.9 **Your zip download is ready**

If you have downloaded multiple documents at once a zip will be prepared. This zip can be downloaded from the notification at any time even if you should close the browser and re-open it.

Click on the "_Click to download (...MB)"_ text part of the notification to download the zip file.

If you just click on the notification it will just refresh the page.

The name of the downloaded zip will be _\<Download GUID>.zip_ in contrast to the name of the zip you automatically get if you wait for the zip to finish zipping after clicking on download which is \<Projectname>-\<Documents>-\<Timestamp>.zip Notification sent to: _The user that has downloaded the documents._

> **Note:** This notification will be sent even if all notifications have been disabled

## 9. **Collections** - `type=document-collections`

### 9.1 **Collection finalized** - `type=library-item-collection-finalized`

**Notification sent if** You or a team you are part of is set as follower of a collection and the collection is finalized.

**Notification setting option** Collection finalized

### 9.2 **Followed a collection** - `type=library-item-collection-made-follower`

**Notification sent if** You or a team you are part of was added as follower to a collection.

**Notification setting option** Followed a collection

### 9.3 **Unfollowed a collection** - `type=library-item-collection-removed-follower`

**Notification sent if** You or a team you are part of was removed from a collection.

**Notification setting option** Unfollowed a collection

### 9.4 **Collection updated** - `type=library-item-collection-updated`

**Notification sent if** A collection is shared with the project and you or a team you are part of have been set as a follower.

**Notification setting option** Collection updated

### 9.5 **Collection made private** - `type=library-item-collection-made-private`

**Notification sent if** You, or a team you are part of, are set as follower of a collection that is shared with the project and the collection is made private.

**Notification setting option** Collection made private

### 9.6 **Collection deleted** - `type=library-item-collection-deleted`

**Notification sent if** You are an administrator and another administrator deletes a collection in the project.

**Notification setting option** Collection deleted

### 9.7 **Collection shared externally** - `type=library-item-collection-shared-externally`

**Notification sent if** You are an administrator and and another administrator shares a collection in the project externally.

**Notification setting option** Collection shared externally

## 10. **Members** - `type=members`

### 10.1 **New invite** - `type=invite`

**Notification sent if:** Another user sends you an invitation to a project. The notification describes who invited you and to which project you were invited. If you received this notification you should also have received an email with an invitation link that you can click on to accept the invitation. Please check [here](https://support.catenda.com/en/articles/8417802-why-am-i-not-receiving-emails) fore email troubleshooting.

> **Note:** The notification on Catenda Hub also includes the invitation link so you can also click on the notification to accept the invitation. If you do not have an account yet you might have to create one and be invited again to be able to click on the notification.

**Notification setting option** A person is invited to the project.

### 10.2 **New member** - `type=member-accept-invitation`

**Notification sent if** If a user accepts an invitation sent by another member a notification is sent that a new member has joined the project.

**Notification setting option** A new user has joined the project

### 10.3 **Added to team** - `type=member-added-to-team`

**Notification sent if** You have been added to a team.

### 10.4 **New team member** - `type=project-member-added-to-team`

**Notification setting option** A member is added to a team

## 11. **Project**

### 11.1 **Project name** - `projects=<Project GUID>`

## 12. **Limit**

### 12.1 **Amount of notifications per page** - `limit=<Notification amount>`

_Note:_ It might take longer for the page to load with more notifications.

## 13. **Page**

### 13.1 **Current page of notifications** - `page=<Page number>`

## 14. **Obligatory notifications**

There are some notifications that will be sent even if you have unchecked all the checkboxes in notification settings.

### 14.1 **Sent even if all checkboxes are unchecked**

Any type of import or export that processes in the background will produce a notification about the result of the import whether it has imported or failed. If you turn off notifications completely with the on/off button on the top right these notifications will not be sent either.

### 14.2 **Sent even if all notifications disabled**

Notifications about links shared with users via the [sharelink](https://support.catenda.com/en/articles/4728886-sharelink-notify-people-about-catenda-hub-content) function will always create notification for the user even if a user has turned off notifications completely with the on/off button on the top right of the notification settings page.
