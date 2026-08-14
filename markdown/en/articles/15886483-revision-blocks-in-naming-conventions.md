# Revision Blocks in Naming Conventions

> Learn to configure dynamic blocks in folder naming conventions. See how files stack as sequential revisions, where to view results, and how to use custom fields with the document identifier turned off.

When a Naming Convention is enabled on a folder, files are automatically scanned during the upload process to ensure they match specific structural patterns. If local filenames contain blocks that constantly change with every new version, the folder can be configured to dynamically recognize them.

When properly configured, uploading different local files with varying version data maps them to the exact same document container. Instead of creating separate, cluttered document entries for every minor file change, the platform automatically recognizes the shared base name and stacks them as sequential revisions under a single document.

## 1. Where to View the Document Details

Once files are successfully uploaded, the platform cleanly separates static document details from changing version data:

### 1.1 **1.1 The Right Information Menu**

Selecting a document from the file list and expanding the **File info** tab on the right side of the page displays the segmented data.

**1.1.1 Document Information** This displays data from the naming blocks that remain constant throughout the entire lifecycle of the document.

**1.1.2 Revision Information** This automatically extracts and displays the values from changing blocks directly from the uploaded filename.

**1.1.3 Revision Name** This explicitly lists the unchangeable, original local filename exactly as it was stored on the local hard drive.

### 1.2 **1.2 The Documents Table**

To view original filenames at a quick glance across the main file lists, the **"Revision name"** (Original Name) column can be toggled on. Column visibility adjustments are tied strictly to individual account profiles, meaning a workspace can be customized without altering the default view for the rest of the team.

## 2. Configuring Changing Revision Blocks

To build a naming convention that cleanly isolates changing version markers from static document names, individual block behaviors must be adjusted within the convention settings. Navigation to the naming conventions page is completed within the project settings. _Access required:_ Administrator

### 2.1 The Critical Setting: Turn Off the Document Identifier

For any block that changes per revision, the **Document identifier** must be toggled to **Off**. This setting ensures the platform validates the characters during upload to maintain consistency, but strips them out when finalizing the actual document name.

This is the exact mechanism that allows files with varying version strings to stack neatly as revisions rather than generating completely new documents.

### 2.2 Utilizing Custom Field Sources

To control exactly what characters are permitted in these dynamic blocks, custom fields are assigned as the block **Source**. Depending on tracking needs, different field types can be utilized to enforce validation constraints:

**2.2.1 Text Custom Fields** This option allows a flexible or fixed number of characters for standard alphanumeric inputs.

**2.2.2 Dropdown Custom Fields** This option restricts the block to a predefined set of specific values, up to a limit of 1,000 options. This is highly beneficial when short filename codes must be mapped to full, descriptive names inside the platform.

**3.2.3 Integer Custom Fields** This option forces the block to strictly accept numbers. Note that while it ensures only numerical entries are used, the system will accept any valid integer rather than forcing a strict, step-by-step sequential count up.
