# Project Security

## 1. **Storing data**

### 1.1 **Active vs. Inactive Account Status**

During an active relationship with a company, project information is typically maintained within platform organizations to support ongoing access. Projects that are on halt or frozen but remain part of an active account configuration may continue to be accessible for reference and maintenance activities. In these cases, data remains available as long as the platform organization maintains its active status.

### 1.2 **Retention and Recovery**

When a project is transitioned to an expired status or is manually deleted, actions signifying it is no longer associated with an active platform organization, the platform is designed with the intent to be able to maintain project data for a period of up to three years. During this intended window, projects may be recovered and re-opened at any time, provided an active relationship with the company is maintained. The retention period and the ability to restore data are strictly subject to the legal and regulatory requirements of the jurisdiction in which the project is situated. In instances where local laws regarding software data management mandate earlier removal, those jurisdictional requirements take precedence over standard platform behavior. To ensure information is preserved according to internal or jurisdictional needs, it is recommended to [utilize available export tools](https://support.catenda.com/en/articles/7946690-exporting-all-project-data) to perform a final backup prior to any project expiration or deletion.

### 1.3 **Data on home soil**

Standard platform data is hosted in secure, established regions. While current configurations are centralized, there may be possibilities to establish data residency within specific geographic locations to align with local jurisdictional requirements. Organizations with unique hosting or "home soil" needs are encouraged to contact support at [support@catenda.com](mailto:support@catenda.com) to discuss potential technical possibilities and configurations.

## 2. **Sharing data with people outside of the project**

Links can be created to share both models and documents with external parties. Anyone with access to such a link will not need an account to view the model or download the documents. Documents can be shared by making an open url of a document collection. _Access required:_ Project member

Models can be shared by making an open url of a bookmark. _Access required:_ Administrator

It is possible to request that these type of url's are turned off for all your projects.

## 3. **Downloading data**

Files can be uploaded as document revisions to the documents section.

### 3.1 **Limiting downloading with access control**

**Documents / models** Access to documents can be controlled individually. If access on the ifc document is limited, only people with access to the document will be able to see it. Members with access to the document will be able to download it.

**Topics** Access to topics can be controlled per topic board. If access to a topic baord is limited, only people with access topic board will be able to see the topics in the board. Members with access to the topic board will be able to export topics to BCF, PDF, and Excel.

### 3.2 **Limiting downloading by withdrawing a revision**

If a revision is present in a document that should not be there, an administrator can withdraw the revision. After a revision is withdrawn it can no longer be viewed or downloaded anywhere by anyone.

### 3.3 **Limiting downloading of single topics**

To keep the relations to elements like documents, topics and objects a topic can be archived. Topics can be moved to a different topic board. The topic board can then be archived. _Access required:_ Administrator

While the topic is in the archived topic board, element relations will stay intact but will not be visible on the related element. If a topic board is restored the related elements will once again display their relation to the topic.

### 3.4 Limiting the downloading of models

If the document is an ifc document it can be linked to a model.

_Within the project_ Even if the document is linked to a model, only people with access to the document will see it appear on the dashboard, models page and in the revision selector.

**External sharing** If a model is shared with a public link in a bookmark, the model preview can only be viewed and not downloaded.

Object information is not visible in externally shared bookmarks.

## 4. **Deleting data**

**Documents/models** Members can delete documents but administrators in a project will always be able to find documents by searching with the "deleted" filter. Keep in mind that this filter is language specific.

**Topics** Before deleting, topics can be exported to BCF. The topic for that ID will be deleted, but if you change the ID in the BCF the topic can be re-imported. Relations to elements like documents, objects and topics will then be lost.

**Milestones** Members can archive and restore milestones. _Access required:_ Milestone creator or administrator.
