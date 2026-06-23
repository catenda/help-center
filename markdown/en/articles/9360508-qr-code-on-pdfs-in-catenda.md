# QR-Code on PDFs in Catenda

QR-Codes can be configured per folder in the [folder configuration](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) of [document settings](https://support.catenda.com/en/articles/7831371-document-settings).

This function provides users of Catenda a function to check, if the document they are using is the latest version, by scanning the QR-code printed on the PDF.

This article contains information about the following topics:

## 1. **Setup QR-Code on Catenda Hub**

The QR-code assignment is done via folders, which means that each project administrator can decide on a selected set of folders to have this function on.

These are the steps to assign the QR-code function to folders in your project;

1. Under the document —> settings, go to **‘folder configuration’**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/01-setup-qr-code-on-catenda-hub.png)

2. Click on the plus next to your desired folder to open the folder configuration and under ‘assign QR Code’ say **‘yes’**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/02-setup-qr-code-on-catenda-hub.png)

The scanning of placeholders and placement of QR-codes will only take place on folders with QR-code assignment;

> **Note:** Once a parent folder is assigned, all sub-folders will have this assignment QR-codes can be assigned to any folder once a parent folder hasn’t already been assigned.

## 2. Placing the Placeholder in your document

In order to use this function, you would need to place the **[QR-code placeholder](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)**, provided by Catenda, onto your document and then upload to Catenda Hub. _Dimension requirement:_ This must have a minimum size of 2cm by 2cm.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/03-placing-the-placeholder-in-your-document.png)

The download link for the QR-Code can be found here:

_[Download link](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)_

### 2.1 Placing the QR-code as file author

Since documents cannot be changed after they are uploaded to Catenda it is important that the placeholder QR-Code is placed on the document before it is uploaded to Catenda. The placeholder can be placed on any layer except the annotation layer. For Catenda to recognize the QR-Code, it has to be added as an image. The image in the published document has to be the exact same image as the placeholder image.

**PDF optimization**

Many programs perform optimization steps for better viewing and reducing file size. These steps might change the amount of bytes in the image which will make it so Catenda does not recognize it anymore. Here is some information about the placeholder that can help with optimization. Pixel density: 144 dpi Image compression: ZIP The image has to be one whole image. Some optimizers might split the image as an optimization. Please make sure the image is whole after optimizing. _Archicad_ When placing the qr code, please use: Import > interpobility > merge from file > import and open worksheet > drag en drop If you open the worksheet and drag and drop the PNG it will change the resolution and not work.

### 2.2 Placing the QR-code on an existing document

If you have a document that you did not create and you would like to add the QR-Placeholder before uploading it to Catenda Hub, please make sure you edit the document and add the QR-Placeholder as an image.

### 2.3 Placing the QR-code a Catenda document

If your document is already on Catenda you will have to add the QR-placeholder and upload a new revision. If you do not have access to a PDF editing program you can use the [image stamp annotation tool](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6) to add the QR-placeholder to your document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/04-placing-the-qr-code-a-catenda-document.png)

To save the document so the QR-placeholder will be recognized, print the document with [the pint button](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70) that can be found on the top left of your document preview.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/05-placing-the-qr-code-a-catenda-document.png)

This will open the print dialogue of your browser. Here is what that can look like for Google Chrome:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/06-placing-the-qr-code-a-catenda-document.png)

In the print dialogue, print the document to PDF.

> **Note 1:** The QR code will only end up on the content layer if you print the document. If you download the document it will be on the annotation layer. **Note 2:** By printing to PDF you rasterize the content of the document. This means that the text will not be searchable when you upload it as a revision to Catenda.

The printed PDF with the placeholder can now be uploaded as a new revision to Catenda. To keep your revision history clean you might want to withdraw the previous revision without the QR code.

## 3. **Publishing with QR Codes**

1. Upload a new revision of a PDF with the placeholder into a folder with QR-code assignment
1. While publishing the PDF will be scanned for the placeholder and replaced with a QR-code (generated for this revision)
1. The newly generated QR-code will become part of the PDF, which can be viewed/scanned on Catenda Hub and/or downloaded.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/07-publishing-with-qr-codes.png)

Here is an example on the placement of the QR-code placeholder and the results after uploading to Catenda Hub. 1. Placeholder in the title block of a drawing. **Ready for uploading.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/08-publishing-with-qr-codes.png)

2. Placeholder in title block is replaced with then generated QR code. **Ready for verification.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/09-publishing-with-qr-codes.png)

### 3.1 **Document history**

After uploading a document with a placeholder QR code you will be able to see it has successfully been processed in the document history of the [right information menu](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/10-document-history.png)

If the generation of your QR code has failed, this can be because your QR-code was smaller than 2cm x 2cm or it was placed as an annotation instead of an image.

**Flattening annotations**

Some software allow you to flatten annotations which will allow the placeholder to be processed. Here are some examples:

**PDF X-change**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/11-document-history.png)

**Adobe Acrobat**

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-9a263e31a1a0.png" width="300"/> --> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-e47c4802a00b.png" width="300"/>

_BlueBeam Revu_ When you place the placeholder in BlueBeam Revu and save the document it will be added as an annotation. It is possible to flatten the QR-code to make it part of the content layer of the document, but even when saving it regularly or by using the reduced file size option the QR-code will be changed and will not work with Catenda. To make the QR-code work with catenda, instead: Print the document with the BlueBeam driver:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/12-document-history.png)

In the Save As dialogue, select ZIP graphics and enable post processing. This is because the compression algorythm used for the placeholder is ZIP.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/13-document-history.png)

In the post processing menu, choose the Combine Adjacent Images option. This is because the image normally will be split in two so it combines it back together. If your page size does not exist as a default option, you can add your own custom one here:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/14-document-history.png)
