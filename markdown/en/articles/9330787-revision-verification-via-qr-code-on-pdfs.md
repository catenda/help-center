# Revision Verification via QR-Code on PDFs

Print document revisions with generated QR-Codes to physical paper so project members can verify if the piece of paper they have in their hands is still current.

Configured folders can be identified by the gear badge on the [folder icon](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page#h_6af15c36b3). This is what a revision with a generated QR-Code can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/01-intro.png)

## 1. **Folder configuration**

QR-Code stamping can be [enabled for configured folders](https://support.catenda.com/en/articles/7831371-document-settings#h_166a269870) on the documents page. _Access required:_ Administrator

In configured folders, new PDF revisions in documents are uploaded are processed. Catenda scans the the document for the QR-Code placeholder image found below. If the placeholder is succesfully identified, a QR-Code is generated for the revision. _Access required:_ Write access to the document

### 1.1 **Assign QR-Code**

To assign QR-Code stamping to a folder, go to [document settings](https://support.catenda.com/en/articles/7831371-document-settings) which can be found as a sub-page of the [documents page](https://support.catenda.com/en/articles/8204673-documents-page). In document settings, expand the [folder configuration menu](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90). This is what the folder configuration menu can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/02-assign-qr-code.png)

Towards the bottom the Assign QR-Code dropdown can be found. Click on the dropdown and select Yes to configure this folder.

**Configuration inheritance** If a configuration has been set in a parent folder, all its sub folders will inherit its configuration.

## 2. **QR-Code placeholder placement**

As mentioned in the introduction of this article, for a QR-Code to be generated on a revision uploaded to a configured folder Catenda will look for the QR-Code placeholder image. The QR-Code placeholder image can look something like this:

<p class="intercom-align-center no-margin">[<img alt="Catenda QR-Code placeholder" src="https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/inline-8c4db2f4912c.png" width="150"/>](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)</p>

Click [here](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk) to download the QR-Code placeholder

> **Warning:** Do not copy/paste this image or save as. The image might look the same on the drawing but will not be recognized.

Click [here](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda) to read more about how to place the placeholder on a PDF. This is what the placeholder can look like when placed in the title block of a drawing:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/03-qr-code-placeholder-placement.png)

## 3. **Uploading a revision with a placeholder**

Upload a new revision of a PDF with the placeholder into a folder with QR-code assignment. This only applies to published revisions!!! Drafts or shared PDFs will only get a QR code generated after they have been published.

### 3.1 **Revision QR-Code generation**

After the QR-Code placeholder is placed, the PDF can be uploaded as a new revision to the configured folder. During the upload Catenda processes the images in the document.

**Byte requirement** The correct bytes belonging to the black and white pixels in the Catenda QR-Code placeholder must be present in the right order.

**Dimension requirement** The image must have a minimum width and height of 2cm by 2cm.

**Example of generated QR-Code** This is what the title block in the example above can look like after the PDF is processed and a QR-Code has been added:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/04-revision-qr-code-generation.png)

## 4. **Status workflow -** Publish to generate QR-Code

Without the status workflow all revisions that are uploaded are instantly published. Documents are only scanned for QR-Code placeholders when they are published.

### 4.1 **Shared revisions vs published revisions**

With the status workflow enabled new revisions get uploaded as shared revisions as a step prior to publishing. When looking at the shared revision you will be able to see the original document before Catenda altered it with a generated QR-Code. With the status workflow the swapping out of the placeholder QR-Code with the generated QR-Code happens when a shared revision in a configured folder that has the placeholder QR-Code is published.
