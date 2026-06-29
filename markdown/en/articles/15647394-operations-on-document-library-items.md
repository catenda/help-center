# Operations on document library items

In this article the different actions and operations that can be performed on items in the documents area depending on which access a user has are explained.

## 1. **1. Folder operations**

These are the different operations that can be performed on a folder according to the access levels.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><p><b>Operation</b></p></td><td style="background-color: #e3e7fa80;"><p><b>Access required</b></p></td></tr><tr><td><p>View folder contents / share a folder link</p></td><td><p>Read</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Create a document, add a subfolder, rename the folder</p></td><td style="background-color: #e8e8e880;"><p>Write</p></td></tr><tr><td><p>Move, delete, modify the access settings (ACL)</p></td><td><p>Full access</p></td></tr></tbody></table></div>

### 1.1 **1.1 Access required: Read**

**Default behavior** All members have at least write access by default. A member can have read access to a folder if it was created in a folder where read access was configured or if read access was configured specifically for the folder. The folder may later have been moved so its access does not necessarily have to be the same as the folder it is in.

**View folder contents** Members with read access can navigate to the contents of a folder. Different can access can be configured to the contents of the folder so members with read access may not have access to all elements in the folder.

**Share folder** Members with read access can share links to folders with sharelink or by linking the URL. Sharelink recipient may have different access and might not see the same contents of the folder. A public link to a collection can be made with the contents of the folder so anyone can download the content of the collection regardless of access settings.

### 1.2 **1.2 Access required: Write**

**Default behavior** All members have at least write access by default.

**Create document in folder** Members with write access to a folder can create new documents in that folder.

**Add folder in folder** Members with write access to a folder can create new folders in that folder.

**Rename folder** Members with write access to a folder can rename the folder.

### 1.3 **1.3 Access required: Full access**

**Default behavior** The folder owner (creator of the folder) and administrators have full access by default.

**Move folder** Members with full access can move folders to other folders. Folder owners (creator of the folder) often have full access and are thereby able to move their own folders. Members often have write access to documents created by other members. Members are therefore often only able to move folders they created unless they are in a folder where they have been given more access.

**Delete folder** Members with full access can delete a folder regardless of the access that is set in the folder.

**Modify folder ACL** Members with full access to a folder can change the access settings to that folder.

## 2. **2. Document operations**

These are the different operations that can be performed on a document according to the access levels.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><p><b>Operation</b></p></td><td style="background-color: #e3e7fa80;"><p><b>Access required</b></p></td></tr><tr><td><p>Share a document link</p></td><td><p>Read</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Link/unlink objects, edit labels, create, rename, create a model (IFC)</p></td><td style="background-color: #e8e8e880;"><p>Write</p></td></tr><tr><td><p>Move to another folder, delete, modify the ACL</p></td><td><p>Full access</p></td></tr></tbody></table></div>

> **Note:** Creating or removing a model from an IFC document also requires write access to "creating and removing models" in project settings.

### 2.1 **2.1 Access required: Read**

**Default behavior** All members have at least write access by default. A member can have read access to a document if it was uploaded to a folder where read access was configured or if read access was configured specifically for the document. The document may later have been moved so its access does not necessarily have to be the same as the folder it is in.

**Share document** Documents can be shared with sharelink or by linking the URL. Sharelink recipient may have different access and might not see the same document revisions. A public link to a collection can be made with a specific document revision so anyone can download the content of the collection regardless of access settings.

### 2.2 **2.2 Access required: Write**

**Default behavior** All members have at least write access by default.

**Link/Unlink objects** Members with at least write access can link and unlink objects to a document.

**Edit Labels** Members with at least write access can add and remove labels from a document.

**Create new document** Members with at least write access to the parent folder can create documents within that folder.

**Rename document** Members with at least write access can rename documents.

**Create model** Members with at least write access to a document can create a model from an ifc document making it appear on the models page. Extension required: `.ifc` or `.ifczip` _Additional access required:_ Write access to creating and removing models in project settings

**Remove model** Members with at least write access can remove the model link froma a document that is linked to a model making it disappear from the models page. _Additional access required:_ Write access to creating and removing models in project settings

### 2.3 **2.3 Access required: Full access**

**Default behavior** The document owner (creator of the document and often the uploader of the first revision) and administrators have full access by default.

**Move document to another folder** Members with full access can move documents to other folders. Document owners (creator of the document and often the uploader of the first revision) often have full access and are thereby able to move their own documents Members often have write access to documents created by other members. Members are therefore often only able to move documents they created unless they are in a folder where they have been given more access.

**Delete document** Members with full access can delete a document regardless of the access that is sset in the folder.

**Modify ACL** Members with full access to a document can change the access to that document.

## 3. **3. Published revision operations**

The table below related the operations that can be performed on a published revision to the access levels. By default all new revisions in documents are published. If shared revisions have been enabled all new revisions in documents are created as shared revisions by default.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><p><b>Operation</b></p></td><td style="background-color: #e3e7fa80;"><p><b>Access required</b></p></td></tr><tr><td><p>Preview in Catenda Hub, access in apps (mobile / Catenda Site), 2D/3D viewer, download, compare, add to collection, share</p></td><td><p>Read</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Withdraw</p></td><td style="background-color: #e8e8e880;"><p>Full access</p></td></tr></tbody></table></div>

### 3.1 **3.1 Access required: Read**

**Preview in Catenda Hub** Members with at least read access to a document can preview published revisions in Catenda Hub.

**Access in applications** Members with at least read access to a document can access published revisions from applications that access the API like, our mobile application, Catenda Site.

**2D/3D viewer buttons** Members with at least read access to a document with published 3D document revisions can use the 2D and 3D buttons in the viewer column to load the 3D document into the respective viewer. One of the following required:

- Document linked to model and latest revision is a succesfully processed `.ifc` or `.ifczip`
- Latest revision is a pointcloud
- Latest revision is a CityGML

**Share published revision** Members with at least read access to a document with published revisions can share links to revisions via sharelink or by linking the URL. The sharelink recipient may have different access and might not be able to view the document. A public link to a collection can be made with a specific published revision so anyone can download the content of the collection regardless of access settings.

**Compare** Members with at least read access to a document with at least two pdf revisions present can use the compare feature. Additional access required: Second published PDF revision present in document

**Download** Members with at least read access to a document with published revisions can download the published revisions in the document.

**Add to collection** Members with at least read access to a document with published revisions can add a published revision from a document to a collection.

### 3.2 **3.2 Access required: Full access**

**Withdraw** Members with full access to a document can withdraw published revisions in the document.

## 4. **4. Draft revision operations - Legacy**

The table below related the operations that can be performed on a draft revision to the access levels. Draft revisions are only available in projects created before October 2 2025.

### 4.1 **4.1 Access required: No access**

**Access in applications** Only published revisions can be accessed from applications that access our API like, our mobile application, Catenda Site.

**Add to collection** Only published revisions can be added to collections.

### 4.2 **4.2 Access required: Read**

**Preview in Catenda Hub** Members with at least read access to a document and read access to drafts in project settings can preview draft revisions in Catenda Hub. _Additional access required:_ Read access to document drafts in project settings.

**Share draft revision** Members with at least read access to a document with draft revisions and read access to drafts in project settings can share links to draft revisions via sharelink or by linking the URL. The sharelink recipient may have different access and might not be able to view the document.

**Download** Members with at least read access to a document with draft revisions and read access to drafts in project settings can download draft revisions. Draft revisions can be downloaded one by one by clicking on the download button in the revisions area of the right menu of the revision on the document preview page. _Additional access required:_ Read access to document drafts in project settings

### 4.3 **4.3 Access required: Write**

**Preview in Catenda Hub** _Additional access required:_ Document owner

**Publish** In projects where the status workflow was activated before October 2 2025 the draft revision checkbox is enabled by default in the upload menu but can be unchecked to uplaod a published revision instead.

## 5. **5. Shared Revision**

The table below related the operations that can be performed on a shared revision to the access levels. If shared revisions have been enabled all new revisions in documents are created as shared revisions by default.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><p><b>Operation</b></p></td><td style="background-color: #e3e7fa80;"><p><b>Access required (+ extra condition)</b></p></td></tr><tr><td><p>Preview, share, download</p></td><td><p>Read (+ "View shared revisions" checked)</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Publish</p></td><td style="background-color: #e8e8e880;"><p>Write (+ "Can publish" checked)</p></td></tr><tr><td><p>Withdraw</p></td><td><p>"View shared revisions" checked</p></td></tr></tbody></table></div>

> **Note:** Note: Only published revisions can be accessed from apps or added to collections.

### 5.1 **5.1 Access required: No access**

**Access in applications** Only published revisions can be accessed from applications that access our API like, our mobile application, Catenda Site.

**Add to collection** Only published revisions can be added to collections.

### 5.2 **5.2 Access required: Read**

**Preview in Catenda Hub** Members with at least read access to a document with shared revisions and access to viewing the shared revisions of a document can preview shared revisions in Catenda Hub. _Additional access required:_ "View shared revisions" checked in document access menu

**Share shared revision** Members with at least read access to a document with shared revisions and access to viewing the shared revisions of a document can share links to shared revisions via sharelink or by linking the URL. The sharelink recipient may have different access and might not be able to view the document.

**Download** Members with at least read access to a document with shared revisions and access to viewing the shared revisions of a document can download shared revisions. The latest shared revisions of documents that are selected in the workspace tab of the documents table can be downloaded with the download action. Previous shared revisions can be downloaded one by one by clicking on the download button in the revisions area of the right menu of the revision on the document preview page. _Additional access required:_ "View shared revisions" is checked in document access menu

### 5.3 **5.3 Access required: Write**

**Publish** Members with at least write access to a document with shared revisions, access to viewing the shared revisions of a document and access to publishing revisions in the document can publish one of the shared revisions that have been uploaded since the latest published revision in the document. _Additional access required:_ "Can publish" is checked in document access menu

### 5.4 **5.4 Access required: Full access**

**Withdraw** Members with at least read access to a document with shared revisions and access to viewing the shared revisions of a document can withdraw shared revisions in the document. _Additional access required:_ "View shared revisions" is checked in document access menu
