# Revision Naming Use Cases

> Explore real-world revision naming examples. Learn how teams balance space and readability using version sequences, status mapping, and compact YYMMDD or clear YYYYMMDD prefixes optimized for chronological document sorting.

When enabling a naming convention on a folder, project teams often customize dynamic blocks to fit specific internal tracking workflows. Below are practical examples of how different teams utilize custom fields and the **Document identifier** toggle to maintain an organized workspace.

## 1. **1. Project Roles and Implementation Strategies**

The adoption of naming conventions is typically driven either by a mandate from the project owner or by a desire among project members to achieve a clearer overview of their files. A structured naming convention allows team members to search for specific components of document names more effectively. Regardless of who initiates the workflow, project members must contact a project administrator to configure and activate the naming convention, as administrative access is required to modify these settings.

The scope of the implementation generally depends on who requests it:

### 1.1 **1.1 Project Owner Mandates**

When a convention is demanded by the project owner, it is frequently implemented project-wide. In these scenarios, a separate, designated folder is often established to accommodate documents that do not match the strict convention requirements.

### 1.2 **1.2 Project Member Requests**

When a convention is requested by an individual or a specific subgroup to improve a localized workflow, it is typically enabled only on their specific working folder, while the rest of the project team continues to operate without a convention.

## 2. **2. Version Sequence Workflows**

Version sequencing is utilized to track consecutive file updates. Depending on project requirements, teams choose between expanding variable-length tracks, rigid dash-padded placeholders, or simple numeric indicators.

### 2.1 Standard Version Sequence (`v1`, `v2`, `v3`)

**2.1.1 The Team** Liam (BIM Manager) and Sophia (Structural Engineer).

**2.1.2 The Workflow** Sophia regularly uploads structural model files to the platform. Liam requires all incoming models to be explicitly labeled with standard version sequences like `v1`, `v2`, or `v3`.

**2.1.3 Behavior and Considerations** While this setup is simple in the beginning, version tracks can expand into double or triple digits (e.g., `v10` or `v123`) as the project progresses. To accommodate this growth, a text field with either an infinite (variable) length or a larger fixed length is established.

A key visual consideration with this approach is that if the block is located in the middle of the filename, adding a second or third character to the sequence will visually shift all subsequent naming blocks over by character slots. To prevent these shifting version tags from creating completely separate document containers during each upload, the Document Identifier must be disabled.

**2.1.4 The Configuration**

- **Source Field:** Text Custom Field.
- **Length:** Left blank for variable length, or set to a larger fixed number.
- **Document Identifier:** Off.

**2.1.5 The Result** When Sophia uploads files named `Structural_Model_v1.ifc` and `Structural_Model_v10.ifc`, the platform recognizes the changing version strings. The files stack neatly as sequential revisions under a single, static document container named `Structural_Model`.

### 2.2 Alphanumeric Dash-Padded Sequence (`--`, `-a`, `-b`)

**2.2.1 The Team** Sarah (Lead Architect) and Tom (BIM Coordinator).

**2.2.2 The Workflow** Sarah issues architectural drawings following a progression where the initial release starts with a double dash (`--`), followed by alphabetical tracking (`-a`, `-b`) as modifications occur. She collaborates with Tom, who manages the folder layouts.

**2.2.3 Behavior and Considerations** Unlike the standard version sequence, this dash-padded setup keeps the block length exactly the same. When a new version letter is introduced, a placeholder dash is sacrificed to maintain uniform spacing.

A primary challenge with this strategy is that once all placeholder dashes within the predefined length are exhausted, the convention breaks. Therefore, this approach is only recommended when there is a clear understanding of the maximum revision limit for the documents.

**2.2.4 The Configuration:**

- **Source Field**
Text Custom Field configured with a strict, fixed length (e.g., 2 or 3 characters) or a Dropdown Custom Field containing the exact permitted variations.
- **Document Identifier:** Off.
- **The Result**
When Sarah uploads `FloorPlan_--.pdf` followed later by `FloorPlan_-a.pdf`, the platform reads the changing sequence tags for validation but strips them out when naming the file in the workspace. Tom and the design team see a single document container named `FloorPlan` where historical variations are stacked as revisions without shifting subsequent characters.

### 2.3 Simple Numeric Tracking Sequence (`01`, `02`, `03`)

**2.3.1 The Team** David (Structural Draftsman) and Chloe (Lead Structural Engineer).

**2.3.2 The Workflow** David updates structural detail drawings frequently and marks them numerically on his local computer using sequential indicators like `01`, `02`, and `03`. Chloe reviews these details and relies on the platform to ensure David is inputting numbers rather than accidental text letters.

**2.3.3 Behavior and Considerations** An integer-focused rule block is added to the folder structure to validate entries. Note that while it ensures only numerical entries are used, the system will accept any valid integer rather than forcing a strict, step-by-step sequential count up.

**2.3.4 The Configuration**

- **Source Field:** Integer Custom Field.
- **Document Identifier:** Off.

**2.3.5 The Result** When David uploads `Steel_Detail_01.pdf`, the integer field confirms the block contains numerical data and permits the upload. If David makes an error and attempts to upload a file containing letters in that block, the system rejects the file. Chloe can monitor the files knowing that while the platform accepts any valid integer and does not force David to count up in a rigid chronological sequence, it guarantees a clean numerical timeline in the file information panel.

## 3. **3. Shorthand Status Mapping Workflows (`W`, `D`, `P`)**

**3.1 The Team** Elena (HVAC Engineer) and Marcus (Project Manager).

**3.2 The Workflow:** Elena utilizes a local naming system where she appends single-letter shorthand codes to indicate a drawing's lifecycle status: `W` for Work in Progress, `D` for Draft, and `P` for Published. Marcus, the Project Manager, needs to know the exact status of her engineering sheets at a glance but prefers full, descriptive words rather than abbreviations.

**3.3 Behavior and Considerations** A dropdown configuration is applied to the folder to bridge the gap between local shorthand codes and platform metadata display titles.

**3.4 The Configuration:**

- **Source Field:** Dropdown Custom Field.
- **Mapping Setup**
The "Code" is set to match Elena's local filename markers (`W`, `D`, `P`), while the "Name" is written out fully as the display value (`Work in Progress`, `Draft`, `Published`).
- **Document Identifier:** Off.

**3.5 The Result** When Elena uploads `HVAC_Layout_W.pdf`, the system matches the code `W` and automatically populates the metadata display as `Work in Progress`. When Marcus expands the right information menu to review the file, the core document name remains a clean, static `HVAC_Layout`, while the **Revision Information** section explicitly displays "Work in Progress".

## 4. **4. Numerical Date Tracking & Chronological Sorting**

### 4.1 **4.1 The Team**

Oliver (Document Controller) and Emma (Site Manager).

### 4.2 **4.2 The Workflow**

Oliver processes daily site reports and needs to track exactly when each report was generated. Emma, the Site Manager, frequently accesses the documents table and requires the files to be highly organized. Because native date blocks are not utilized inside naming conventions, Oliver and Emma use numerical custom fields to input date strings. They explore two distinct configuration variations depending on how they want the files to behave.

### 4.3 **4.3 Date as a Revision Marker (Standard Order)**

In this variation, the date changes with every new file upload and represents a new revision of the daily log. Oliver uses two digits for the day (`01`–`31`), two digits for the month (`01`–`12`), and either a two-digit year (`26`, `27`) or a four-digit year (`2026`, `2027`). Because a naming convention only permits a single primary separator character across its blocks, managing an isolated date format requires choosing between two distinct configuration paths:

**4.3.1 Three Separate Integer Blocks**

- **Structure**
If an underscore (`_`) is established as the primary separator, the file can be formatted as `Daily_Report_09_07_2026.pdf`. 
This utilizes three individual integer custom fields: Day, Month, and Year.
- **Document Identifier Constraints**
If the Document Identifier is toggled **On** for these three blocks, the date is permanently integrated as part of the document name. 
This creates a separate document container for every single revision, and the date values remain permanent because document names within naming convention folders are unchangeable. 
To allow the date fields to vary and stack files as revisions under a single static document name, it is necessary to toggle the Document Identifier **Off** for all three fields.

**4.3.2 Single Text Block with Internal Separators**

- **Structure**
To avoid utilizing multiple convention blocks, an alternative character (such as a dash) can be used inside a single text field block, formatted as `Daily_Report_09-07-2026.pdf`.
- **Validation Constraints**
It is only possible to validate the overarching text string within an individual block. Consequently, ensuring the secondary internal separators are placed correctly relies entirely on manual user accuracy during file preparation.

### 4.4 Date for Sorting (Year-Month-Day Order)

In this variation, Emma wants the date to remain visible in the document name so that separate files exist for each day. Furthermore, Emma requires the documents table to sort the files in perfect chronological order automatically. Lists within the platform are sorted alphanumerically according to Unicode values. If a date is written as Day-Month-Year, the list sorts by the day number first, grouping all files from the "01" day of different months together.

To prevent this, Oliver places the year first, followed by the month, and then the day. When managing this prefix, there is a balance between conserving character space and ensuring immediate readability, which leads to two implementation options:

**4.4.1 Two-Digit Year Prefix (`YYMMDD`)** This option shortens the sorting string into a single block to eliminate extra separator characters and reduces the year to two integers (e.g., `26`, `27`, `28`). This saves character space, decreasing the risk that long document names will be cut off or truncated at the end of the line in the user interface. However, this option sacrifices immediate readability.

A date string such as `260126` can easily be misunderstood, as it is not immediately clear which numbers represent the year and which represent the day. A pattern only becomes recognizable after viewing multiple files, and the difference only becomes distinct once a day or year value exceeds 31.

**4.4.2 Four-Digit Year Prefix (`YYYYMMDD`)** This option utilizes a full four-digit year (e.g., `2026`, `2027`, `2028`) at the beginning of the name. This configuration significantly improves clarity and immediate readability, making the chronological sequence obvious to all team members. However, it consumes more character space at the beginning of the filename, increasing the likelihood that information at the end of long document names will be truncated or cut off in the interface.

**4.4.3 Configuration**

- **Source Field**
A single Integer or Text Custom Field placed at the very beginning of the naming convention, formatted in a strict `YYMMDD` or `YYYYMMDD` sequence. 
To maintain correct alignment and proper alphanumeric sorting, leading zeros must always be used for single-digit months or days (e.g., `01` for January).
- **Document Identifier:** On.

**4.4.4 Result** When Oliver uploads files like `260115_Report.pdf` and `260201_Report.pdf`, separate documents are created because the Document Identifier is active. Because the year and month come first and utilize consistent double-digit padding, the documents table automatically sorts the files in flawless chronological order.
