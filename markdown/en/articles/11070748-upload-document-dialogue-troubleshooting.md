# Upload document dialogue troubleshooting

In this article you will find information about the errors that can occur when [uploading single documents](https://support.catenda.com/en/articles/4670278-uploading-a-document).

## 1. **Document exists in folder**

If you have write access to a folder, but read access to a document you will not be able to add revisions to that document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qn4yk3x7/01-document-exists-in-folder.png)

Please create a new document with this revision or upload the revision to a different document.

## 2. **Executable and script filetypes**

When a file has a potentially harmful filetype they will not be uploaded. This is what it can look like when you attempt to upload a harmful filetype:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qn4yk3x7/02-executable-and-script-filetypes.png)

The following filetypes which can potentially be harmful are not allowed. See which filetypes cannot be uploaded in [this](https://support.catenda.com/en/articles/4670320-previewing-file-types-on-catenda-hub) article.

## 3. **Filename cut off**

Files that are selected for upload from an external drive like a usb harddrive/usb stick or a network drive have can have a limitation of around 250 characters in the length of their path. If the path to the file is too long the end of the filename (before file extension) is cut off and replaced with ~1. This is what it looks like when a filename is cut off.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qn4yk3x7/03-filename-cut-off.png)

This is not a limitation of Catenda but rather a limitation between the browser and the operating system. To avoid running into this problem copy the files from the external location to your local machine and upload them to Catenda from there. A good place to put them is typically the dashboard where temporary files can be discovered and later removed or at the root C:// to ensure there are as many characters as possible available in the path length.
