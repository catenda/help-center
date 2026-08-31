# Zip download troubleshooting

When a folder or more than one item is downloaded in the document section a dialogue shows up towards the bottom left of the screen. In this dialogue the progress of the peparation of the zip file that is to be downloaded is displayed.

## 1. **Reserved characters in path**

If a folder has the character `/` in the folder name this is recognized as a path in the zip file and the folder will be split into multiple folders that are all inside each other. Any items within the folder will end up in the last of these folders. For example the folder `This/is/a/folder` with the document `This-is-a-document.pdf` will be downloaded to a zip with the following folder structure: This is a folder This-is-a-document.pdf

## 2. **Non-downloadable revisions**

### 2.1 **Draft revisions (Legacy)**

Draft revisions can only be downloaded individually from the right menu of a revision. If only draft revisions are selected a zip will be prepared but it will be empty. The new type of revisions to replace this is shared revisions which just like regular published revisions can be downloaded with the documents tabel downlaod action without problem.

### 2.2 **Withdrawn revisions**

If the latest revision of one of the documents in the selection has been withdrawn a warning can appears letting the user know that some files will not be downloaded.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/169yxgzv/01-withdrawn-revisions.png)

Press continue to keep preparing or cancel to stop the download.

## 3. **Not yet scanned for virus**

If files that are recently uploaded are attempted to be downloaded they may not have been scanned for a virus yet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/169yxgzv/02-not-yet-scanned-for-virus.png)

If it has been a while since the files-to-download were uploaded, please contact support about non-scanned files. Press continue to keep preparing or cancel to stop the download.

## 4. **Download preparation error**

If anything goes wrong in preparing this zipped file the following error can appear:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/169yxgzv/03-download-preparation-error.png)

If you see this screen, please contact support.
