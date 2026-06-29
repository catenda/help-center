# Topic board access control

> Access Control Levels on Topic Boards

You will be able to find the access control of a topic board by clicking on [edit access](https://support.catenda.com/en/articles/4670277-issue-board-settings#h_82063f7a79) in the [access control menu](https://support.catenda.com/en/articles/4670277-issue-board-settings#h_7a3aca4c7d) on the [topic board settings](https://support.catenda.com/en/articles/4670277-issue-board-settings) page. _Access required:_ Full access to the topic board

The edit access control dialogue can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/66bsqhfn/01-intro.png)

## 1. **Topic board information**

Here the name and the owner of the topic board are displayed

## 2. **Extensions - Close topics**

Limit who can close and reopen topics by limiting who can change the status of a topic to a status with an open meta-status and a status with a closed meta-status. When you enable this feature you will see a [close topics column](#h_3e36186c6f) appear next to the access column.

## 3. **Define access for**

Here you will be able to specify who has what access to this topic board. By clicking on the "Member or team" dropdown you will be able to define access for member(s) or team(s). Once you have selected a member or team they will appear in the list below.

## 4. **Role column**

In the role column the different roles of the projects are described

### 4.1 **Administrators**

_Default_ - Full access Members that are administrators always have full access. The project owner is an administrator.

### 4.2 **Users**

_Default_ - Write access Access given to individual members always overrides access given to teams, all users and owners.

### 4.3 **All users**

_Default_ - write access All users is the term used for members that have not gotten specific access as user, team or topic board owner.

### 4.4 **Teams**

_Default_ - Write access Access given to teams is set for all the teams members unless the member has specific access as a user or an topic board owner.

### 4.5 **Topic board Owner**

_Default_ - Full access When you create content in Catenda you become the **owner** of that content. Owner settings applies to the owner of the content.

> **Note:** Users will be granted the highest permission of what being set in **all users**, **owners** and **team**.

> **Tip:** **Example:** You may use **team**, or **owners** to grant users more permission than **all users**, but not to give them less permission.

The reason behind this is to prevent users to grant themselves more access by removing themselves from a team, or as an owner.

## 5. **Access levels**

There are four access levels defined. The access that applies is the highest access that members have received either through user access or through access configured for any of their teams.

### 5.1 **No access**

Members with no access will not be able to access the topic board.

### 5.2 **Read**

Members with read access have access to the topic board, but cannot create topics or make comments on existing topics.

### 5.3 **Write**

Members with write access will be able to do the same as members with read access. Members with write access will also be able to create new topics and comment on existing topics.

### 5.4 **Full access**

Members with full access will be able to do the same as members with read and write access. With full access members will also be able to edit the access settings of this topic board. Members with full access will be able to add and modify custom fields on this topic board. Administrators always have full access. Members with full access will not be able to edit administrator access.

## 6. **Topic**

The table below relates the operations that can be performed on a topic to the access levels for the topic board it is in.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 227px;"><h2 id="h_b8c3cd8ee9">Operation</h2></td><td style="background-color: #e3e7fa80; width: 73px;"><h2 class="intercom-align-center" id="h_eaddbaa490">Read</h2></td><td style="background-color: #e3e7fa80; width: 195px;"><h2 class="intercom-align-center" id="h_8b71241e18">Write</h2></td><td style="background-color: #e3e7fa80; width: 50px;"><h2 class="intercom-align-center" id="h_138755bddc">Full</h2></td><td style="background-color: #e3e7fa80;"><h2 class="intercom-align-center" id="h_6eae5730c8">Admin</h2></td></tr><tr><td style="width: 227px;"><p>View contents</p></td><td style="width: 73px;"><p class="intercom-align-center">x</p></td><td style="width: 195px;"><p>​</p></td><td style="width: 50px;"><p></p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px;"><p>View topic history</p></td><td style="background-color: #e8e8e880; width: 73px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; width: 195px;"><p></p></td><td style="background-color: #e8e8e880; width: 50px;"><p></p></td><td style="background-color: #e8e8e880;"><p></p></td></tr><tr><td style="width: 227px;"><p>Share topic</p></td><td style="width: 73px;"><p class="intercom-align-center">x</p></td><td style="width: 195px;"><p></p></td><td style="width: 50px;"><p></p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px;"><p>Create topic board</p></td><td style="background-color: #e8e8e880; width: 73px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; width: 50px;"><p></p></td><td style="background-color: #e8e8e880;"><p></p></td></tr><tr><td style="width: 227px;"><p>Create topic in board</p></td><td style="width: 73px;"><p></p></td><td style="width: 195px;"><p class="intercom-align-center">x</p></td><td style="width: 50px;"><p></p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px;"><p>Rename topic</p></td><td style="background-color: #e8e8e880; width: 73px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; width: 50px;"><p></p></td><td style="background-color: #e8e8e880;"><p></p></td></tr><tr><td style="width: 227px;"><p>Change topic header fields</p></td><td style="width: 73px;"><p></p></td><td style="width: 195px;"><p class="intercom-align-center">x</p></td><td style="width: 50px;"><p></p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px;"><p>Change status with open meta-status to status with closed meta-status</p></td><td style="background-color: #e8e8e880; width: 73px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px;"><p class="intercom-align-center">x and close topics extention checked if enabled</p></td><td style="background-color: #e8e8e880; width: 50px;"><p></p></td><td style="background-color: #e8e8e880;"><p></p></td></tr><tr><td style="width: 227px;"><p>Edit topic description</p></td><td style="width: 73px;"><p></p></td><td style="width: 195px;"><p class="intercom-align-center">x</p></td><td style="width: 50px;"><p></p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px;"><p>Check boxes in description</p></td><td style="background-color: #e8e8e880; width: 73px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; width: 50px;"><p></p></td><td style="background-color: #e8e8e880;"><p></p></td></tr><tr><td style="width: 227px;"><p>Create topic comment</p></td><td style="width: 73px;"><p></p></td><td style="width: 195px;"><p class="intercom-align-center">x</p></td><td style="width: 50px;"><p></p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px;"><p>Edit topic comment</p></td><td style="background-color: #e8e8e880; width: 73px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px;"><p class="intercom-align-center">x comment creator only</p></td><td style="background-color: #e8e8e880; width: 50px;"><p></p></td><td style="background-color: #e8e8e880;"><p></p></td></tr><tr><td style="width: 227px;"><p>Check boxes in comment</p></td><td style="width: 73px;"><p></p></td><td style="width: 195px;"><p class="intercom-align-center">x comment creator only</p></td><td style="width: 50px;"><p></p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px;"><p>Delete topic comment</p></td><td style="background-color: #e8e8e880; width: 73px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px;"><p class="intercom-align-center">x comment creator only</p></td><td style="background-color: #e8e8e880; width: 50px;"><p></p></td><td style="background-color: #e8e8e880;"><p></p></td></tr><tr><td style="width: 227px;"><p>Delete topic</p></td><td style="width: 73px;"><p></p></td><td style="width: 195px;"><p></p></td><td style="width: 50px;"><p class="intercom-align-center">x</p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px;"><p>Archive topic board</p></td><td style="background-color: #e8e8e880; width: 73px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px;"><p></p></td><td style="background-color: #e8e8e880; width: 50px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880;"><p></p></td></tr><tr><td style="width: 227px;"><p>Modify topic board ACL</p></td><td style="width: 73px;"><p></p></td><td style="width: 195px;"><p></p></td><td style="width: 50px;"><p class="intercom-align-center">x</p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px;"><p>Move topic</p></td><td style="background-color: #e8e8e880; width: 73px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px;"><p></p></td><td style="background-color: #e8e8e880; width: 50px;"><p></p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">x</p></td></tr></tbody></table></div>

## 7. **Close topics column**

The checkboxes in this column will decide whether these users will be allowed to close topics or not. At the bottom of the list an topic creator option will also appear. The topic creator item allows you to give extra permissions to the creator of an topic. This rule only applies when the topic creator is not listed under "Users" and has write access.

If the close topics option is unchecked for a user they will no longer be able to:

- Create closed topics
- Close existing topics
- Change the status of a topic that is closed

Let the owner close their own topic as only they know best if everything was handled or not. Let a team called "team leads" or "reviewers" close the topics as only they have the authority to close the topics.

## 8. **Save button**

> **Note:** Remember to press the save button and reload after you are done to see the changes.

## 9. **Configured example**

This is what the access control dialogue can look like after it has been configured:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/66bsqhfn/02-configured-example.png)
