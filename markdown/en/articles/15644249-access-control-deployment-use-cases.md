# Access Control Deployment Use-Cases

Structuring an access control environment in Catenda Hub requires aligning system mechanics with specific project roles and collaborative workflows. To resolve overlapping rules cleanly, the system applies a strict line of authority: direct individual overrides establish an absolute final boundary, while all unoverridden pathways combine to grant the maximum available permission tier. The configuration strategies outlined below demonstrate how to deploy team boundaries, individual lockouts, and container scopes to satisfy real-world security and operational requirements.

## 1. **1. The General Project Community**

### 1.1 **1.1 Isolated Subcontractor Workspaces**

**The Who** A single specialized subcontractor team requiring internal autonomy.

**The Objective** The subcontractor team must have total freedom to upload, modify, organize, and fix files within their assigned section. Coworkers within the same firm need to correct each other's mistakes or rearrange folder structures freely, but external parties must be entirely blocked to prevent accidental deletion or unauthorized visibility.

**The Configuration** The global **All Users** baseline is set to **No Access**, while the specific subcontractor **Team Setting** is granted **Full Access**.

**The Scope Strategy** This strategy is typically deployed when a project is new. **Downward propagation** is enabled on the top-level folder structure, allowing administrators to rapidly push full internal autonomy down through the entire sub-directory path.

### 1.2 **1.2 Interdisciplinary Collaboration Folders**

**The Who** Multiple design disciplines (e.g., Architects, Structural Engineers, MEP) working in a shared environment.

**The Objective** A shared workspace must be provided where various distinct teams can upload models, coordinate designs, and cross-reference files simultaneously without restrictions.

**The Configuration** This environment can be established using one of two methods: either a dedicated, blended "Interdisciplinary Team" is created and granted **Write** access, or each individual discipline team (Architecture Team, Structural Team, etc.) is explicitly added to the container with **Write** access.

**The Scope Strategy** Because collaboration requirements change frequently across different branches of a directory, this use-case is focused on specific "leaf" folders deeper in the hierarchy. The scope is restricted to the **Immediate Container Only**, ensuring that open collaboration rules do not accidentally bleed into other restricted zones.

### 1.3 **1.3 Cross-Team Visibility and Auditing**

**The Who** External auditors, client representatives, or secondary engineering teams.

**The Objective** One primary team must maintain full control or upload rights within a directory, but an outside team or stakeholder needs to actively monitor progress, review documents, and see exactly what is happening in real time without any ability to alter the data.

**The Configuration** The primary working group is granted **Full Access** or **Write** access, while the auditing group or secondary team is explicitly assigned **Read** access.

**The Scope Strategy** This configuration utilizes **Immediate Container Only** mapping on localized leaf folders. It allows stakeholders to be granted targeted visibility into completed work sections while keeping unapproved drafts in adjacent folders completely hidden.

## 2. **2. Subcontractors and External Contributors**

### 2.1 **2.1 Fluid Team Assignments for Rotating Staff**

**The Who** External vendors and contracting firms with high staff turnover.

**The Objective** Access must remain stable and secure even as personnel frequently move in and out of the project or change corporate roles.

**The Configuration** Permissions are assigned exclusively to a **Team Setting** (e.g., "External Reviewers") set to **Read** or **Write**. No individual user overrides are configured for the team members.

**The Scope Strategy** To ensure long-term maintainability, this configuration utilizes **Downward Propagation** at the top-level directories. When a new worker joins the external firm, they are simply added to the existing team structure, instantly inheriting the correct permissions across the entire project branch without manual folder-by-folder adjustments.

### 2.2 **2.2 The Secure Individual Lockdown**

**The Who:** High-security consultants, third-party auditors, or restricted external contributors.

**The Objective:** Because security and data integrity are paramount, an administrator must guarantee with 100% certainty that a specific user has a fixed level of access. This tier must remain strictly locked, ensuring the user cannot accidentally inherit elevated permissions if they are mistakenly added to a parallel project team or collaborative group.

**The Configuration:** An explicit **Individual User Setting** is applied directly to the user's account and set precisely to the required tier (such as **Read** or **No Access**).

**The Scope Strategy:** This is applied as a localized lock on specific leaf nodes using the **Immediate Container Only** setting. Because an individual assignment represents the ultimate final authority in the system hierarchy, it overrides all global baselines, team memberships, and owner privileges. Even if the user is accidentally assigned to a team with Full Access elsewhere, the individual lockdown ensures their permissions remain restricted exactly as intended.

## 3. **3. Item Owners and Content Creators**

Catenda Hub automatically assigns **Full Access** to the creator of a folder (whether built manually or auto-extracted via a uploaded ZIP structure), a topic board, or a newly established document container. Ownership applies strictly to the document container itself, meaning that if a user uploads a new revision to a document created by someone else, the original container ownership remains unchanged.

### 3.1 **3.1 Creator Sovereignty and Data Privacy**

**The Who** Internal authors and standard content contributors.

**The Objective** A shared folder environment is required where team members can browse general files, but any individual who originally creates a document container must retain absolute control to update, rename, or manage it, without granting those same destructive management rights to the rest of the team.

**The Configuration** The global **All Users** baseline or team framework is restricted to **Read** or **Write**, while leaving individual user settings completely unconfigured for the contributors.

**The Logic:** Without an individual override, the system defaults to the highest inherited tier. Regular team members are bound by the standard folder rules, but the moment the original author interacts with a document container _they own_, their built-in owner status elevates them to Full Access.

### 3.2 **3.2 Isolated Private Workspaces**

**The Who** Specific team leads, project managers, or internal auditors.

**The Objective** A strictly confidential folder or topic board must be established where a manager can upload drafts, organize sensitive files, or keep internal notes in total isolation from the rest of the project community.

**The Configuration** The target container is created, and the global **All Users** baseline is explicitly set to **No Access**. No other general teams are granted access.

**The Logic** Because the baseline and team paths are entirely closed, standard users see nothing. However, because the creator of that folder or board automatically holds **Owner Full Access**, they retain complete visibility and administrative control over the space, completely isolated from standard project members while Project Administrators retain high-level oversight.
