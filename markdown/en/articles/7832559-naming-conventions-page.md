# Naming conventions page

Administrators will be able to find the Naming conventions page as a sub page to [project settings](https://support.catenda.com/en/articles/4670273-project-settings-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/01-intro.png)

## 1. **Local file naming**

With naming conventions you can limit what files are uploaded to a folder depending on the name of the original file. This is very useful if you already have a set of rules for the naming of your local files. You should not need to rename your files so you can upload them to Catenda Hub. If you do not have rules for the naming of your local files the Naming convention is not recommended.

## 2. **Documents, revisions and original files**

Before you get started with this it is important to understand the difference between a Catenda Hub **document** and a **file**. You can think of a document (and document revisions) in Catenda Hub as a _containers for files_. You can upload a file to this container and if you are an administrator change its name. Filenames are often very different from each other even though they are the same version of the drawing or sheet you want to upload. The naming convention lets you upload similar files to the same document based on a set of rules in the name of the file.

## 3. **New naming convention**

On the top right of the page you will see the New naming convention button.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/02-new-naming-convention.png)

This is what a new naming convention looks like.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/03-new-naming-convention.png)

### 3.1 **Convention information**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/04-convention-information.png)

**Name** The convention name as it will appear when you apply in document settings

**Description** The description of the convention as it will appear in document settings

**Separator** The character separating every block except the file extension block.

### 3.2 **Previews**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/05-previews.png)

Previews show the pattern of that the conventions follow on both in your local file system and in the Catenda Hub document structure. These can be different and one can be mapped to the other as you will see

**Document name** The way the document in Catenda Hub will look when the file is uploaded

**Expected file name** The way files that are allowed to be uploaded are supposed to look

### 3.3 **Preview types**

When you hover over the different preview types you will see a detailed explanation of what each preview means. _Text - Variable length:_ {X} _Text - Fixed length:_ XXXX _Custom field:_ {Custom field name} _Separator:_ When you have three or more blocks you will see the separator you have set

### 3.4 **Blocks**

The naming convention exists of a series of blocks. Each blocks represents a part of the name of the file/document. Click on Add block to add a new block.

![Add block](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/06-blocks.png)

A convention always has at least two blocks: 1\. The name of the file/document. 2\. The name of the file/document extension.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/07-blocks.png)

**Name** The name of the block in the naming convention setup so you can tell them apart

**Description** Here you can type in a description of what you expect this block to do

**Document identifier** If you expect a part of the file name that you do not want to see in Catenda Hub you can turn off the document identifier. This part of the file name will still be used for accepting files but will not be visible in the resulting Catenda Hub Document.

**On** When the document identifier is toggled on this block identifies the name of the document

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/08-blocks.png)

**Off** When the document identifier is toggled off this block identifies the name of the local file.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/09-blocks.png)

**Disabled** The document identifier of the extension block is always off as every file has an extension.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/10-blocks.png)

**Source** What will qualify the identification of the name of the file/document? _Default:_ Text - This block can contain any character _Custom field:_ - Limit the types of characters that your block accepts with custom fields

**Length** How many characters there can be in this block. If this field is left blank the block will have a variable length.

### 3.5 **Submitting a convention**

![Cancel Submit naming convention](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/11-br-submitting-a-convention.png)

After submitting a naming convention it can be [enabled per folder](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) in [document settings](https://support.catenda.com/en/articles/7831371-document-settings).
