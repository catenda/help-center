# Folders and Documents access control

> Access Control Levels for Documents

Select document(s) and/or folder(s) in the documents area to find the access control menu in the [right information menu](https://support.catenda.com/en/articles/8345396-right-menu-on-the-documents-page#h_cad792004b). Here the project members that have access to the document can be seen. Follow these steps to edit the access of the selected items.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/01-intro.png)

1. Select the document(s) and/or folder(s) that are to be configured.
1. Open the right information menu
1. Click on **edit access**.

> **Important:** **Access required:** Full access

The access control dialogue can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/02-intro.png)

## 1. **1. Configure access for project participants**

Click the "Define access for" dropdown to select participants for which access should be configured. Participants can either be selected as member or as a member of a team. Access roles include administrator, individual user access, baseline access, team access and owner access.

### 1.1 **1.1 Recommended workflow**

Set access **per team rather than per user**. Roles change often, and team-based access stays flexible: a member added to a team gets the right access as soon as they join the project. A common pattern is to set "all users" to no access — so new, not-yet-assigned members can't see sensitive information — then grant access to each team as needed.

Click [here](https://support.catenda.com/en/articles/15644094-how-catenda-calculates-access-levels) to read more about how the different participant roles stack up against eachother.

## 2. **2. What access is applied? (3 steps)**

The access with the highest weight always wins, but there are exceptions. Restrictive tiers like "No Access" are elevated even other pathways grants higher rights.

### 2.1 **2.1 Which of the configurations applies?**

**Administrators** Administrators always have access to everything.

**Individuals** The exact configured access level applies.

**Others** Check the different access configured for a user either via one of the following:

- All users
- A team the user is part of (can be part of multiple)
- Owner access.

The access with the highest weight applies. No access > Full access > Write > Read

Click [here](https://support.catenda.com/en/articles/15644094-how-catenda-calculates-access-levels) to read more about how access levels are calculated. Click [here](https://support.catenda.com/en/articles/15644249-access-control-deployment-use-cases) to read more about typical ways access is configured.

### 2.2 **2.2 What can paritcipants do with that access?**

Click [here](https://support.catenda.com/en/articles/15647394-operations-on-document-library-items) to read more about what operations can be performed on folders and documents.

## 3. **3. Overwrite options (scope applied on save)**

When the access dialogue is saved, the access on the selected elements is **overwritten regardless of what was previously configured**. The three options under "Where to apply these rules" control how far that change reaches.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><p><b>Option</b></p></td><td style="background-color: #e3e7fa80;"><p><b>What gets overwritten</b></p></td><td style="background-color: #e3e7fa80;"><p><b>What access stays as-is</b></p></td><td style="background-color: #e3e7fa80;"><p><b>When to use</b></p></td></tr><tr><td><p>Folder and new content</p></td><td><p>Selected items + any new items created in them</p></td><td><p>Items one level down + items in folder structures.</p></td><td><p>When you must not change the access of existing contents</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Folder and files<br/>(default)</p></td><td style="background-color: #e8e8e880;"><p>The above + existing documents one level down</p></td><td style="background-color: #e8e8e880;"><p>Folders one level down + items in folder structures.</p></td><td style="background-color: #e8e8e880;"><p>The usual choice; per-subfolder access is preserved</p></td></tr><tr><td><p>Folder and all subfolders and files</p></td><td><p>The above + folders one level down + items in folders structures.</p></td><td><p>-</p></td><td><p>Only when it's fine to overwrite existing subfolder access too</p></td></tr></tbody></table></div>

> **Note:** **Careful:** the first two options overwrite only the selected elements, so older access can remain on sub-elements. Members might no longer be able to navigate to them, yet still reach them through filtering.

## 4. **4. Status workflow**

If shared statuses were enabled after 2 October 2025, two extra columns appear to the right of the access column: **View shared revisions** and **Can publish**. Which boxes can be checked depends on the access level. This is what that can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/03-4-status-workflow.png)

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><p><b>Access</b></p></td><td style="background-color: #e3e7fa80;"><p><b>View shared revisions</b></p></td><td style="background-color: #e3e7fa80;"><p><b>Publish</b></p></td></tr><tr><td><p>No access</p></td><td><p>Not available (item not shown in list)</p></td><td><p>No</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Read</p></td><td style="background-color: #e8e8e880;"><p>Can be granted (optional)</p></td><td style="background-color: #e8e8e880;"><p>No</p></td></tr><tr><td><p>Write</p></td><td><p>Always able to view</p></td><td><p>Can be granted (optional)</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Full access</p></td><td style="background-color: #e8e8e880;"><p>Always able to view</p></td><td style="background-color: #e8e8e880;"><p>Yes</p></td></tr></tbody></table></div>
