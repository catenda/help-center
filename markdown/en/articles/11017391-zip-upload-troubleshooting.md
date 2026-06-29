# Zip upload troubleshooting

In this article you will find information about the errors that can occur when [uploading a zip / file structure](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure).

## 1. **Upload failed**

It is recommended to use a wired connection for uploading the zips to Catenda. Many wifi routers do a great job at making sure they receive the right data, but even the best routers can struggle with a weak signal if you are far away from the router.

### 1.1 **Unable to process file**

During the zip upload process packets of data are being sent to the Catenda server. If there is a problem with any of the packets during the process the following message is displayed: Failed to upload! Unable to process file.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/01-unable-to-process-file.png)

Even when right next to a WiFi antenna with a device it is never 100% sure the packet will arrive safely through the air. This effect is amplified by being further away from the antenna or if there are objects like walls between the device and the antenna.

**Large files** When large amounts of data are being uploaded many packets are being sent. If even one of them does not arrive to the router through the air properly a network error can appear. When this happens the entire upload will be invalid.

### 1.2 **Network error**

Certain software limit the amount of characters that paths to files in a zip file can have. If there is a problem with the path structure in the zip file the following error will appear: Failed to upload! Network error.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/02-network-error.png)

**Unzip/Rezip** If this zip was received from someone else it can help unzipping it and rezipping it.

**Known limits (updated December 2025)** Microsoft Windows 10/11 The limit in Windows is 260 characters but can be increased. _Access required:_ Windows Administrator account

Windows Home users: This limit can be increased by going to Windows Start and typing REGEDIT Open the Registry Editor and navigato to:

`HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\FileSystem`

Doubleclick `LongPathsEnabled` and change the value to 1. If it is not there, rightclick the `FileSystem` key and choose

`New > DWORD (32-bit) Value`

Name the new value `LongPathsEnabled` with a value of 1.

Windows Pro users This limit can be increased by going to Windows Start and typing gpedit.msc Open Edit Group Policy and navigato to:

`HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\FileSystem`

Double click on `Enable Win32 long paths` and enable it.

OneDrive and SharePoint 400 Unicode code units

### 1.3 **Robust uploads**

**Smaller zips** If the zip consists of multiple files, the zip can be split into smaller zips. Each separated zip can be uploaded individually but there will always be a risk of a network or connection error.

**Individual files** The [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) is a safer way to upload as it uploads documents file for file. This is also faster as the files are uploaded directly to our backend rather than through the browser interface. Even if one of the files fails, the ones uploaded until then will already appear on Catenda. The rest of the files will continue uploading the next time the upload task runs.

## 2. **Zip uploads with special characters**

Catenda detects the encoding of the zip file when it gets extracted so if the zip has special characters in it they will be interpreted properly when extracted. If the special characters were not encoded properly they will not be extractable by Catenda and will end up looking garbled. Depending on the service you use for creating your zip file your characters may or may not be encoded correctly. If your special characters are garbled please look in the zip to see if they look right there. If you think your characters were encoded properly and are not properly being extracted by Catenda we are happy to have a look at your zip file and see if there is anything we can do. In this case please contact [support@catenda.com](mailto:support@catenda.com) with the details of how you created your zip file.

### 2.1 **Zip encoding on Windows**

Different versions of Windows use different zip encodings. For example the English version uses the encoding standard IBM-437 and the pt-BR version uses IBM-850. If your Windows installation does not encode your zip files properly you might have more luck using a third party service like [7zip](https://7-zip.org/download.html) or [WinRAR](https://www.win-rar.com/download.html?&L=0) to create your zip files with the right encoding.

## 3. **Completed but nothing happened**

Even though a zip import completes it there can be several reasons for no change to be visible in the documents table. This is what it can look like when a zip import has completed without changes being made.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/03-completed-but-nothing-happened.png)

This is what the right menu of the zip import page can look like in this situation:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/04-completed-but-nothing-happened.png)

### 3.1 **Skipped folders**

If a folder with the same name as a folder in the zip already exists in the location that the where a folder is attempted to be extracted the creation of the folder will be skipped and no new folder will be created. Any documents within the folder with the same name as on Catenda will be uploaded to the existing folder in the Catenda project.

### 3.2 **Skipped files**

If the skip and continue option was chosen in the zip upload dialogue and a document with the same name as the file that is attempted to be uploaded from the zip file already exists it will be skipped and the next file will start extracting.

### 3.3 **Missing documents**

If documents are listed under missing documents this means that the documents were successfully created but cannot be viewed. The documents that the files were uploaded to can since have been removed. It could also be that the uploader no longer has access to the documents that the files were uploaded to. _Access required:_ Read access

## 4. **Harmful filetypes**

When a file in the zip file has a potentially harmful filetype they will not be uploaded. This is what the zip import page can look like when harmful filetypes are attempted to be uploaded:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/05-harmful-filetypes.png)

This is what the right menu on the zip import page can look like when a harmfull file is attempted to beuploaded:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/06-harmful-filetypes.png)

The following filtypes which can potentially be harmful are not allowed.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa; width: 229px;"><h1 id="h_711fb2a104"><b>Harmful formats</b></h1></td><td style="background-color: #e3e7fa; width: 142px;"><h1 id="h_581e5e19b4">Extensions</h1></td><td style="background-color: #e3e7fa;"><h1 id="h_766841ac5d">Comments</h1></td></tr><tr><td style="width: 229px;"><p>Scripts</p></td><td style="width: 142px;"><p>php</p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px;"><p>Windows executables</p></td><td style="background-color: #e8e8e8; width: 142px;"><p>exe</p></td><td style="background-color: #e8e8e8;"><p></p></td></tr><tr><td style="width: 229px;"><p>Windows installer packages</p></td><td style="width: 142px;"><p>msi</p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px;"><p>Batch scripts</p></td><td style="background-color: #e8e8e8; width: 142px;"><p>bat</p></td><td style="background-color: #e8e8e8;"><p></p></td></tr><tr><td style="width: 229px;"><p>Command scripts</p></td><td style="width: 142px;"><p>cmd</p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px;"><p>DOS executables</p></td><td style="background-color: #e8e8e8; width: 142px;"><p>com</p></td><td style="background-color: #e8e8e8;"><p></p></td></tr><tr><td style="width: 229px;"><p>Screensaver executables</p></td><td style="width: 142px;"><p>scr</p></td><td><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px;"><p>PowerShell scripts</p></td><td style="background-color: #e8e8e8; width: 142px;"><p>ps1</p></td><td style="background-color: #e8e8e8;"><p></p></td></tr><tr><td style="width: 229px;"><p>Windows shortcuts</p></td><td style="width: 142px;"><p>lnk</p></td><td><p>Clicking a downloaded link could link to an executable without looking like an executable.</p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px;"><p>Java executable files</p></td><td style="background-color: #e8e8e8; width: 142px;"><p>jar</p></td><td style="background-color: #e8e8e8;"><p></p></td></tr></tbody></table></div>

## 5. **Insufficient access**

The right access is required for the zip contents to be extracted. _Access required:_ Write access

This is what the zip import page can look like when there is not enough access:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/07-insufficient-access.png)

This is what the right menu on the zip import page can look like when there is not enough access:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/08-insufficient-access.png)
