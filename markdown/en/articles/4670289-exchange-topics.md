# Exchange topics

You will be able to find the exchange topics action in the [new item action menu](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_8c642e051a) to the top right in a topic board. The exchange topics menu can look something like this:

![File based exchange new topic exchange topics history import bcf export topics connect to a bcf client synchronize topics directly with any BCF-compatible client by using the URL below](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/01-intro.png)

## 1. **Import BCF**

Use the BCF import action to import BCF files. This is what the BCF import dialogue can look like:

![Import BCF upload bcf file: select file browse selct board generate new types and statuses from the BCF-file](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/02-import-bcf.png)

Catenda is 100% committed to open standards. Based on this we have implemented import and export of BCF (BIM collaboration format). This means that the user can import and export topics from/to other software that supports this format (for instance Solibri, Navisworks and many others). You can for instance import a file with collision control data for the same model created in another software application. This way you can continue your workflow inside Catenda.

**Multiple topics per bcf** One BCF file can contain multiple topics

**Maximum filesize** The maximum BCF filesize that can be imported is 500 mb.

### 1.1 **Upload BCF file**

Click on browse to select a BCF file you would like to upload

### 1.2 **Select board**

Select the topic board where you would like the topic to be imported to.

### 1.3 **Generate new types and statuses from the BCF-file**

If your BCF file has statuses and types that do not exist in the topic board, you will be able to create these automatically by checking this box. _Access required:_ Full access to the topic board

If your BCF file has statuses and types that do not exist in the topic board, the non-existing statuses/types will be unlinked if this box remains unchecked. After the import is finished you can map the unlinked statuses/types to existing statuses/types.

_Linking multiple statuses/types at once_ If there are unlinked statuses/types in a topic board you will see an orange warning message that there are unlinked fields in a topic board. _Access required:_ Project administrator

![Topics there are unlinked fields in this topic board click here to link](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/03-generate-new-types-and-statuses-from-the-bcf-file.png)

Clicking on the link will take you to the [unlinked fields](https://support.catenda.com/en/articles/4670277-topic-board-settings#h_3bd7e3e759) area of the [topic board settings](https://support.catenda.com/en/articles/4670277-topic-board-settings) where you can link all fields of one kind to an existing value in one go.

## 2. **Export topics**​

You will either be able to export topics by choosing export topics in the [new item action menu](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_8c642e051a) to the top right in a topic board or by selecting a topic in the topics list and choosing the export option in the [selected item action menu](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_b5c00c149b) above the topic board. The export topics dialogue can look something like this:

![Export topics all topics from the current topic board current filter selected topics bcf excel pdf v3.0](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/04-export-topics.png)

> **Note:** Topics can only be exported from one topic board at a time.

### 2.1 **Filter options**

**All topics from the current board**

**Current filter**

**Selected topics**

### 2.2 **BCF export**

Depending on which version of BCF you choose you can get different file types. BCF v3.0 and v2.1 will produce a .bcf while v2.0 will produce a .bcfzip

### 2.3 **Excel export**

It is possible to export topics to excel. There will one row per topic and one column per column int he topic board table view. The order of the columns will be the same as the default topic board [table view](https://support.catenda.com/en/articles/6941099-table-view-in-an-topic-board#h_3102328063) column order.

> **Note:** No images and only the last comment in an topic will be exported.

### 2.4 **PDF export**

Click [here](https://support.catenda.com/en/articles/9784934-exporting-topics-to-pdf) to read more about exporting topics to PDF

## 3. **Reports page**

With the reports page it is possible to make custom reports about not only topics but also documents. The reports page is an on-demand feature that can be requested to be enabled for ongoing projects. New projects that are created based on a template project where this feature is enabled do not have this feature enabled. These reports can then be exported not only to Excel and PDF, but also many more file formats. Click [here](https://support.catenda.com/en/articles/12303098-reports-page) to read more about the reports page

## 4. **Connect to a BCF client**

If you use Catenda Hub as a BCF-server you can connect directly to other software. Here you can and send and receive topics from there to and from Catenda without having to export and import topics. This uses the standardized (from buildingSMART International) BCF API. Examples of software supporting this are Navisworks, Revit, Archicad and Solibri. In these software you can use the general URL to our server which is [https://api.catenda.com/](https://api.catenda.com/) after which you will get all topic boards from all your projects. This can quickly become a long list to scroll through so to help you out we provide the link to your current topic board in this menu. If you use this link instead you will easily be able to find the topics you are looking for.
