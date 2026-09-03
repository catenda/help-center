# Exporting all project data

> An overview of export methods for project data, documents, models, and topics in Catenda Hub. Available options include Desktop Connector sync, PDF/A report creation, access permission auditing, and automated cloud backups to AWS S3 or Azure Blob storage

Catenda Hub provides flexible export methods tailored to various project needs, ranging from day-to-day downloads to automated enterprise archiving. Depending on specific project requirements, it is possible to synchronize large folder structures using Desktop Connector, generate custom document delivery checklists and PDF/A archives via the Reports Page, or document project access permissions for audit trails. For organizations requiring continuous cloud-to-cloud backups, Catenda Data Export provides automated transfers directly to AWS S3 or Azure Blob storage.

## 1. **Why export**

Project owners and project participants often need to maintain local copies of project documentation during and after a project's lifecycle.

### 1.1 **Data submittal and phase changes**

Project data may be needed at various project milestones:

**Phase changes** Transitioning between planning, design, and construction often requires extracting data snapshots, especially if projects are put on hold or handed off to new parties.

**Government inquiries** Formal submittals to authorities are frequently required during or upon completion of a project.

**Tendering** Preparing document submittal packages for tenders.

### 1.2 **Independent data retention & access protection**

Exporting is not limited to project completion. Project members who do not own the main project data often require their own copies to ensure continuous access to their work.

Project members are not always informed in advance when project access will end, and access can sometimes be revoked earlier than expected. Because access can be lost without warning, configuring **scheduled, repeating exports**, such as with **Catenda Data Export** or the **Catenda Desktop Connector**, is critical. These recurring tools ensure project members retain a local or cloud backup up to the last scheduled run prior to losing access.

### 1.3 **Data archival and compliance**

Regulations and industry standards frequently mandate that responsible parties store project records for long periods, often spanning years or decades. System documentation, product records, and compliance files may need to be stored on company servers or designated repositories.

### 1.4 **Project termination**

When an active project finishes or a license period ends, Catenda ensures project data remains stored safely. Even if project access ends, data remains recoverable on Catenda servers for up to three years.

### 1.5 **Frozen archive option**

An archiving option allows projects to remain accessible as frozen, read-only repositories for selected members.

## 2. **Standard Export Options**

These built-in export tools are available directly within the standard interface for all authorized project participants.

### 2.1 **Exporting models**

Because every model in Catenda is linked to a document in the documents section, standard document export capabilities also apply to models. In addition, dedicated export options are available specifically for models:

**Selected model download** Select one or more models on the [models page](https://support.catenda.com/en/articles/4670286-models-page) and use the download action to extract their latest revisions.

**Individual revision download** Select a model on the [models page](https://support.catenda.com/en/articles/4670286-models-page) and use the download button next to each revision in the right information panel. This provides an efficient way to download specific revisions directly without needing to load the full [model contents page](https://support.catenda.com/en/articles/4670270-model-contents-page). Alternatively, individual revisions can also be downloaded directly from the content page of a model.

**Advanced model export** Access the [model export page](https://support.catenda.com/en/articles/4670280-model-export-page) to package selected revisions across multiple models into a single downloadable ZIP file. This method includes advanced options to enhance the exported model files by baking in tags, user-defined properties, or library information.

### 2.2 **Exporting topics (3 ways)**

Topic data can be extracted using three primary formats via [exchange topics](https://support.catenda.com/en/articles/4670289-exchange-topics), depending on how the information will be viewed, analyzed, or stored:

**BCF (BIM Collaboration Format)** An open standard designed to capture and transfer topic information that conforms strictly to the official BCF specification, including individual topic creation timestamps. This format guarantees broad cross-platform interoperability, making it ideal for reopening, editing, or exchanging topic data seamlessly with other BCF-compatible software. For general long-term document repositories where direct file previews are needed, PDF or Excel formats are typically preferred.

**Excel** Exports topic parameters into a spreadsheet format for filtering, sorting, and data manipulation. This format provides structured rows and columns that are ideal for selecting and copying data, and Excel files can be easily previewed within most archiving platforms. For archiving purposes, the PDF export is generally preferred over Excel because it includes more information.

**PDF** Generates a clean, readable summary report in standard PDF format (v1.4) accessible without specialized software (see [exporting topics to PDF](https://support.catenda.com/en/articles/9784934-exporting-topics-to-pdf)). Standard PDF exports include a consolidated download timestamp for formal authority reporting and archiving, providing more information than an Excel export. While the base export generates a standard PDF (v1.4) file, which many archiving systems automatically convert to PDF/A upon upload for long-term previewing, direct export to native PDF/A-1, PDF/A-2, and PDF/A-3 formats is also available via the opt-in [Reports Page](https://support.catenda.com/en/articles/12303098-reports-page).

### 2.3 **Exporting documents and collections**

**Batch & folder downloads** Select individual folders, specific document batches, or all visible table items at once to generate a downloadable ZIP archive. Downloading in manageable batches by selecting specific subfolders or targeted file groups is recommended for smooth transfers when working with large datasets.

- **Published tab**<br>Extracts the latest published revision for each selected document.
- **Workspace tab**<br>Extracts the latest shared revision for each selected document (requires the "View shared revisions" permission). Note that legacy draft revisions cannot be batch-downloaded into a ZIP archive and are downloaded individually.

**Individual revision download** Select a document on the [documents page](https://support.catenda.com/en/articles/8204673-documents-page) and click the download button next to each revision listed in the right information menu. This is an easier way to download individual or historical revisions because the document preview page does not have to be loaded, allowing you to select another document in the table and download its revisions in the right menu without needing to open a new preview page.

**Public collections** Use [collections](https://support.catenda.com/en/articles/6344318-collections-page) to create public links for selected document subsets, allowing external parties to download files without requiring a Catenda account. Note that only published revisions can be added to collections.

**Deleted files** Search for "deleted" in the documents search bar to locate and export previously deleted documents. Keep in mind that this filter is language-specific and will correspond to the term for "deleted" in your current language settings.

### 2.4 **Desktop connector (Automated local backup)**

The [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) enables background synchronization to periodically download new document revisions directly to a local drive. Unlike batch web exports, downloaded documents arrive directly on your system as raw, unzipped files without requiring manual archive extraction.

**Scheduled & instant backups** Tasks can be scheduled to run automatically at regular intervals or executed on demand, ensuring project members preserve an up-to-date local copy of documents even if project access is unexpectedly revoked.

**Direct API transfers** Transfers large datasets significantly faster than web browser downloads by leveraging direct API connections without browser limitations or overhead.

**Hierarchy options** Downloads select folder structures with their complete hierarchy intact, or extracts individually selected files directly as a flat list into the designated local folder.

### 2.5 **Member access and activity logs**

**Topic boards** Document board access permissions using two available views:

- **Per-user access view**<br>View individual user access levels directly from the right information menu of a topic board or selected topic.<br>_Access required:_ read access to the topic board
- **Full team configuration**<br>Capture screenshots of the complete team-level permission settings within the topic board access settings.<br>_Access required:_ Full access to the topic board or project administrator

**Document & Model access** Export the [access overview](https://support.catenda.com/en/articles/6660820-document-access-overview-page) to record permissions for members and teams. Access required: Project administrator. Because every model is linked to a document in the documents section, access permissions for models are governed by the underlying document permissions and are recorded using the same document access overview or permission menus.

**Document & Model revision access** View permissions from the [right menu of a document revision](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision-revision-info) and capture screenshots as needed.

**Project-wide action permissions** Document project-wide permissions on the [project settings page](https://support.catenda.com/en/articles/4670273-project-settings-page) (such as creating topic boards, inviting new members, configuring document statuses, and creating or removing models) using two available views:

- **Per-user access view**<br>Project members can expand each menu under access control to see which individual users have permission to perform each action.
- **Full configuration**<br>Administrators can open the edit access dialogue to view and manage team-level permission configurations.<br>_Access required:_ Project administrator

**User profiles & member details** Information regarding project members and teams is available to extract or document, including:

- Usernames and email addresses (see [custom member information](https://www.google.com/search?q=https://support.catenda.com/en/articles/11769670-custom-member-information%23h_c15463ee3f)).
- Team memberships, assigned topics, uploaded model revisions, and permission settings (captured via the [member page](https://www.google.com/search?q=https://support.catenda.com/en/articles/4670291-members-page) or [team page](https://www.google.com/search?q=https://support.catenda.com/en/articles/4670291-members-page)).

### 2.6 **Notifications**

Capture notification pages via screenshots from the [project notification page](https://support.catenda.com/en/articles/4670295-project-notifications-page), using the [limit filter](https://support.catenda.com/en/articles/8304417-filtering-on-the-notifications-page) to maximize visible items per page.

Configure a dedicated administrative account with [project specific notification settings](https://support.catenda.com/en/articles/4670262-project-specific-notification-settings) enabled for email summaries to maintain searchable notification logs.

### 2.7 **Reports Page (Opt-In Feature)**

**Opt-in activation** The reports page is an opt-in feature that can be requested to be enabled for ongoing projects. While no additional payment is required to use this tool, the project owner must agree to enable it on the project, meaning it is not active by default in many projects. Note that new projects created from template projects where reports are enabled do not automatically have this feature enabled.

**Template-based management** When enabled, project administrators can use the [report templates page](https://support.catenda.com/en/articles/12380837-report-templates-page) to configure custom report templates and generate formatted exports for selected documents or topics.

**Document reports** Export document metadata and revision details for all selected files, including document name, revision name, latest revision number, status, custom fields, creator, uploader, and creation/upload timestamps.

- **Key use cases**<br>Ideal for generating formal document delivery checklists to accompany a collection, or compiling structured document lists for data analysis.
- **Model metadata & attributes**<br>While actual document file contents are not included, model metadata can be exported through document reports as models maintain links to the document section. Custom scripts within templates can also be used to derive additional attributes, such as extracting filetypes from document names.

**Topic reports** Export overall topic headers as well as complete topic body details, including descriptions, comments, and embedded comment images.

**Available export formats** Reports created from any template can be exported to multiple formats depending on your workflow requirements:

- **PDF / PDF/A**<br>Generates clean formatted reports and directly supports native PDF/A compliance (PDF/A-1, PDF/A-2, and PDF/A-3) to meet strict long-term archiving and formal legal standards.
- **Excel**<br>Exports structured tabular data into spreadsheet rows and columns, making it ideal for data manipulation and external analysis.
- **Additional formats**<br>A wide range of additional file formats beyond PDF and Excel are also supported for export; the complete overview can be found in the [reports page](https://support.catenda.com/en/articles/12303098-reports-page) article.

**Centralized storage** Generated reports are listed directly within the reports table and automatically integrated into the main documents table for easy management.

## 3. **Catenda Data Export**

Unlike standard user-driven downloads, Catenda Data Export is an automated, self-service solution designed to seamlessly transfer project data directly into an organization's cloud storage. If your organization is interested in enabling this feature, sales can be reached at [sales@catenda.com](mailto:sales@catenda.com). Once enabled, it provides automated backups directly between cloud environments without needing custom scripts, bypassing browser memory constraints, local drive storage limitations, and network interruptions through automated checksum verification.

### 3.1 **Organization Roles & Permissions**

Setting up and managing Catenda Data Export requires an **Organization Administrator**. Unlike an Organization Owner, whose administrative rights are restricted to a single organization, or standard project members, an Organization Administrator holds elevated access across all organizations belonging to an overarching account. This unique role grants the required cross-organization visibility and authority to configure and manage automated cloud exports.

### 3.2 **Configuration Steps**

Setting up automated data exports involves four main steps:

1. **Select Destination**<br>Choose a cloud storage provider, Amazon Web Services (AWS) S3 or Microsoft Azure Blob storage, and configure authentication.
1. **Define Scope & Data Formats**
    - **Data Types**<br>Export documents, models, and topics. <br>Topic data can automatically be converted into readable PDF summary reports or standard BCF files during transfer.
    - **Project Selection**<br>Choose all projects, hand-pick specific projects, or set up dynamic matching rules using project name patterns (glob or regular expression / regex) to automatically include new projects as they are created.
1. **Select Export Mode**
    - **Continuous Mode**<br>Ships data automatically on a daily schedule. <br>This recurring setup ensures non-owner project members maintain an updated backup up to the last daily run if project access ends unexpectedly.
    - **Snapshot Mode**<br>Performs a one-off run to export a complete dataset at a specific milestone or project handoff.
1. **Deploy**<br>Finalize and enable the export configuration by selecting Create.

### 3.3 **Extracted Content & Integrity Verification**

**Metadata & Custom Fields** Custom fields associated with documents and topics are exported alongside primary files as structured JSON files, ensuring full attribute retention without manual report generation.

**Integrity Verification** Every export run generates a checksum file to verify that exported files match the source data in Catenda Hub and were transferred completely without network loss.

**Organized Hierarchy** Exported files are automatically structured into folders organized by date, project name, and the exact folder hierarchy maintained in Catenda Hub.
