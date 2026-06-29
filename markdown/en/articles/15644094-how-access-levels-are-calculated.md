# How Access Levels are Calculated

An explicit individual assignment serves as the absolute final authority in Catenda Hub, giving you the power to uniquely lock or downgrade a specific user's permissions. If no individual setting is configured, the system falls back to evaluating a user's inherited paths across the global project baseline, team memberships, and owner statuses.

**The access with the highest weight always wins, meaning restrictive tiers like "No Access" will be elevated if any other pathway grants higher rights.**

## 1. **1. Understanding the Access Levels**

### 1.1 **1.1 From least to most access**

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><p><b>Access Level</b></p></td><td style="background-color: #e3e7fa80;"><p><b>What it allows</b></p></td><td style="background-color: #e3e7fa80;"><p><b>Default for</b></p></td></tr><tr><td><p>No access</p></td><td><p>Prevents visibility, interaction and navigation to subfolders.</p></td><td><p>—</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Read</p></td><td style="background-color: #e8e8e880;"><p>Minimum privilege to see and download content; no changing operations</p></td><td style="background-color: #e8e8e880;"><p>—</p></td></tr><tr><td><p>Write</p></td><td><p>Edit and modify, e.g. rename and move files you uploaded yourself</p></td><td><p>Single user / all users / team default</p></td></tr><tr><td style="background-color: #e8e8e880;"><p>Full access</p></td><td style="background-color: #e8e8e880;"><p>Control every aspect of the object including permission management. </p></td><td style="background-color: #e8e8e880;"><p>Administrator and owner default</p></td></tr></tbody></table></div>

### 1.2 **1.2 Understanding the Access Levels by Functional Weight**

While these options appear in a linear sequence within the user interface, they carry different administrative weight. **No Access** and **Full Access** act as the system's structural extremes, while **Read** serves as the vital minimum threshold for visibility.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 210px;"><p><b>Access Level</b></p></td><td style="background-color: #e3e7fa80;"><p><b>Functional weight</b></p></td></tr><tr><td style="width: 210px;"><p>No Access </p><p>(The Ultimate Restriction) </p></td><td><p>acts as an absolute block that shuts down all other permissions a user might have from teams or file ownership.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 210px;"><p>Full Access </p><p>(The Ultimate Permission) </p></td><td style="background-color: #e8e8e880;"><p>In any shared or inherited path, this tier automatically overrides and elevates all lesser privileges.</p></td></tr><tr><td style="width: 210px;"><p>Write </p><p>(Active Collaboration) </p></td><td><p>Intentionally restricts users from destructive management capabilities or deleting files they don't own.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 210px;"><p>Read </p><p>(The Visibility Threshold) </p></td><td style="background-color: #e8e8e880;"><p>Functions as the entry-point to the system; anything lower drops the user into total invisibility.</p></td></tr></tbody></table></div>

## 2. **2. How Permissions Interact (By Order of Precedence)**

### 2.1 **2.1 Project Administrators**

**Absolute Authority** Project administrators automatically receive **Full Access** to every section of a project. This system rule bypasses and overrides all matrices, team assignments, owner statuses, and individual restrictions.

### 2.2 **2.2 Individual User Settings (The Absolute Overwrite Rule)**

**Overwrites Everything** When a specific individual user is assigned a permission tier directly, that setting becomes the absolute final authority.

It completely cancels out and replaces any permissions that user would otherwise inherit from the **All Users** baseline, their **Team memberships**, or their status as an **Item Owner**. If a named individual setting is configured, that tier is applied exactly as selected—even if it downgrades their access to **No Access**.

### 2.3 **2.3 Inherited Permissions & Owner Status (Highest Access Wins)**

When a user **does not** have an explicit individual assignment configured, Catenda Hub evaluates all remaining paths they belong to and grants the maximum tier found.

**All Users Baseline** Sets the fundamental project access level for every member. A user cannot be restricted below this baseline tier unless an individual overwrite is used.

**Team Settings** If a user belongs to a team (or multiple teams) with higher access than the baseline, their access escalates to match the highest team tier.

**Owner Access** The creator or uploader of an item automatically defaults to **Full Access** to ensure data privacy. However, administrators can configure an Owner setting (e.g., restricting it to **Write** access to prevent file deletion). If an owner's team setting or the global baseline provides a higher tier than their owner setting, the highest level wins.

## 3. **3. Quick reference Matrices**

The following matrices map out final effective access levels across different user scenarios, organized in strict order of precedence starting with individual overrides to show exactly how overlapping rules resolve.

This section contains the following topics:

### 3.1 **3.1 The Absolute Individual Override Rule**

This matrix applies to any project member, including an item owner, who has an explicit individual assignment configured. Because this rule dictates absolute final access, it replaces all other variables.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 279px;"><p><b>Inherited Context </b><br/>​<b>(All Users / Team / Owner Setting)</b></p></td><td style="background-color: #e3e7fa80; width: 182px;"><p><b>Individual User Setting</b></p></td><td style="background-color: #e3e7fa80;"><p><b>Final Access Applied</b></p></td></tr><tr><td style="background-color: #00000000; width: 279px;"><p>Any Configuration Tier</p></td><td style="background-color: #00000000; width: 182px;"><p><b>No Access</b></p></td><td style="background-color: #00000000;"><p><b>No Access</b></p></td></tr><tr><td style="background-color: #e8e8e880; width: 279px;"><p>Any Configuration Tier</p></td><td style="background-color: #e8e8e880; width: 182px;"><p><b>Read</b></p></td><td style="background-color: #e8e8e880;"><p><b>Read</b></p></td></tr><tr><td style="background-color: #00000000; width: 279px;"><p>Any Configuration Tier</p></td><td style="background-color: #00000000; width: 182px;"><p><b>Write</b></p></td><td style="background-color: #00000000;"><p><b>Write</b></p></td></tr><tr><td style="background-color: #e8e8e880; width: 279px;"><p>Any Configuration Tier</p></td><td style="background-color: #e8e8e880; width: 182px;"><p><b>Full Access</b></p></td><td style="background-color: #e8e8e880;"><p><b>Full Access</b></p></td></tr></tbody></table></div>

### 3.2 **3.2 Standard Users and Team Members**

This matrix determines final access for regular project members who do not own the item and **do not** have an explicit individual assignment configured.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 145px;"><p><b>All Users Setting</b></p></td><td style="background-color: #e3e7fa80; width: 119px;"><p><b>Team Setting</b></p></td><td style="background-color: #e3e7fa80; width: 182px;"><p><b>Regular User Access</b></p></td><td style="background-color: #e3e7fa80;"><p><b>Team Member Access</b></p></td></tr><tr><td style="background-color: #00000000; width: 145px;"><p>No Access</p></td><td style="background-color: #00000000; width: 119px;"><p>No Access</p></td><td style="background-color: #00000000; width: 182px;"><p><b>No Access</b></p></td><td style="background-color: #00000000;"><p><b>No Access</b></p></td></tr><tr><td style="background-color: #e8e8e880; width: 145px;"><p>No Access</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Read</p></td><td style="background-color: #e8e8e880; width: 182px;"><p><b>No Access</b></p></td><td style="background-color: #e8e8e880;"><p><b>Read</b></p></td></tr><tr><td style="background-color: #00000000; width: 145px;"><p>Read</p></td><td style="background-color: #00000000; width: 119px;"><p>No Access</p></td><td style="background-color: #00000000; width: 182px;"><p><b>Read</b></p></td><td style="background-color: #00000000;"><p><b>Read</b></p></td></tr><tr><td style="background-color: #e8e8e880; width: 145px;"><p>Read</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Write</p></td><td style="background-color: #e8e8e880; width: 182px;"><p><b>Read</b></p></td><td style="background-color: #e8e8e880;"><p><b>Write</b></p></td></tr><tr><td style="background-color: #00000000; width: 145px;"><p>Write</p></td><td style="background-color: #00000000; width: 119px;"><p>Read</p></td><td style="background-color: #00000000; width: 182px;"><p><b>Write</b></p></td><td style="background-color: #00000000;"><p><b>Write</b></p></td></tr><tr><td style="background-color: #e8e8e880; width: 145px;"><p>Full Access</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>No Access</p></td><td style="background-color: #e8e8e880; width: 182px;"><p><b>Full Access</b></p></td><td style="background-color: #e8e8e880;"><p><b>Full Access</b></p></td></tr></tbody></table></div>

### 3.3 **3.3 Item Owners**

This matrix determines access for the creator or uploader of an item when **no** explicit individual assignment is present. It highlights how the global baseline or team settings elevate an owner's access via the highest-access-wins principle.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 103px;"><p><b>All Users Setting</b></p></td><td style="background-color: #e3e7fa80; width: 104px;"><p><b>Team Setting</b></p></td><td style="background-color: #e3e7fa80; width: 105px;"><p><b>Owner Setting</b></p></td><td style="background-color: #e3e7fa80;"><p><b>Final Item Owner Access</b></p></td></tr><tr><td style="background-color: #00000000; width: 103px;"><p>No Access</p></td><td style="background-color: #00000000; width: 104px;"><p>No Access</p></td><td style="background-color: #00000000; width: 105px;"><p>Full Access</p></td><td style="background-color: #00000000;"><p><b>Full Access</b> (Owner default applies)</p></td></tr><tr><td style="background-color: #e8e8e880; width: 103px;"><p>Write</p></td><td style="background-color: #e8e8e880; width: 104px;"><p>No Access</p></td><td style="background-color: #e8e8e880; width: 105px;"><p>Read</p></td><td style="background-color: #e8e8e880;"><p><b>Write</b> (Global baseline elevates owner)</p></td></tr><tr><td style="background-color: #00000000; width: 103px;"><p>No Access</p></td><td style="background-color: #00000000; width: 104px;"><p>No Access</p></td><td style="background-color: #00000000; width: 105px;"><p>Write</p></td><td style="background-color: #00000000;"><p><b>Write</b> (Owner restriction holds)</p></td></tr><tr><td style="background-color: #e8e8e880; width: 103px;"><p>No Access</p></td><td style="background-color: #e8e8e880; width: 104px;"><p>Full Access</p></td><td style="background-color: #e8e8e880; width: 105px;"><p>Write</p></td><td style="background-color: #e8e8e880;"><p><b>Full Access</b> (Team assignment elevates owner)</p></td></tr><tr><td style="background-color: #00000000; width: 103px;"><p>Full Access</p></td><td style="background-color: #00000000; width: 104px;"><p>No Access</p></td><td style="background-color: #00000000; width: 105px;"><p>Write</p></td><td style="background-color: #00000000;"><p><b>Full Access</b> (Global baseline elevates owner)</p></td></tr></tbody></table></div>
