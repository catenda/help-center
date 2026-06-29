# Desktop Connector troubleshooting

In this article you will find information about the errors that can occur when using the [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector).

## 1. **Naming convnention**

If a naming convention is enabled on the upload folder or a parent folder to the upload folder the local filename has to conform to the convention in order for the uplaod to go thorugh. If the filename does not follow the convention the following error is displayed.

**`\<Filename> not match naming convention`**

Please upload the file manually via the browser to see which parts of the filename are missing.

## 2. **Server project location**

Several errors can happen when opening server project location.

### 2.1 **Project location empty**

In order to synchronize your local files to a project you have to have at least one folder in the documents section of the project on Catenda Hub.

### 2.2 **Project not found**

When the Desktop Connector is opened for the first time all projects the user has access to are loaded in. Without refreshing these same projects are displayed next time. If the user has lost access to the project the following message will appear when attempting to set a server location in an up- or download task for the project.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/01-project-not-found.png)

Please ask a project administrator for access to the project. To find out who to contact for project access ask Catenda support.

## 3. **Document appearance**

### 3.1 **Folder location**

Document names can be limited with a naming convention in Catenda. Folders cannot be limited. Without the use of a naming convention documents with any name can be uploaded. In this case Catenda might not have been able to register the file extension of the document. Folders with any name can be created. It can therefore be that the Desktop Connector runs into problems with characters in names that are reserved for Windows functionality.

Typical problems arise with the following characters: `/` - Forward Slash `\\` - Backward Slash These characters are used in the file path hierarchy in Windows which causes the document to end up in the wrong place.

To find an extensive list of what is reserved in Windows see here: [https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file](https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file)

### 3.2 **Incorrect document or folder name**

Document names can be limited with a naming convention in Catenda. Folders cannot be limited. Without the use of a naming convention documents with any name can be uploaded. In this case Catenda might not have been able to register the file extension of the document. Folders with any name can be created.

It can therefore be that the Desktop Connector runs into problems with characters in names that are reserved for Windows functionality.

Typical problems arise with the following characters: `.` - Period

Since folders and files ending in a period are not allowed in Windows the period at the end of the folder or file is removed in the document that is created from a download task. When uploading the period is removed in the process of finding the right folder to upload to so the downloaded document will end up in the right place when synchronizing two ways.

- Space

On Catenda it is possible to manually add a space at the end of a document or folder name while spaces at the end of document and folder names are removed in Windows. If a space is included on Catenda the name of the downloaded folder is different from the name of the folder in Catenda that can include a space. When an upload task is created on that same folder a new folder will be created as the file or folder name on Windows does not have a space at the end.

## 4. **No up- or download**

### 4.1 **Document already exists**

When the import system cannot process an item that was previously created the following error will occurr.

Desktop connector `Document already exists (code: 25)`

Log file

```
<Message number>|<Date/Time>|ERROR|1|BimRequestProviderService|Call API error status code Conflict reason: {"error":{"code":25,"message":"Document already exists"}}.url: https://api.bimsync.com/v2/projects/<ProjectGUID>/libraries/<LibraryGUID>/items? | Data: {"parentId":"<LibraryItemGUID>","name":"<Name>","document":{"type":"<Type>","filename":"<Filename>"}} 
```

Specifically this can happen when trying to upload a folder with the title "`A`" for the second time where a folder with that title already exists. It is recommended to change each local folder with the name "A" to something like "A\_". This way the task will not run into problems. After the upload task finishes change the synchronized version back to "A" on Catenda so both sides stay the same.

### 4.2 **Not all folders have been downloaded**

In the task itself the following can be seen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/02-not-all-folders-have-been-downloaded.png)

`Not all folders have been downloaded, click to view errors.`

Click [here](https://support.catenda.com/en/articles/13772277-desktop-connector-troubleshooting-not-all-folders-have-been-downloaded) to read more about what the problem could be with this error.

## 5. **Latest revision withdrawn**

The latest revision for one of the documents has been withdrawn. In this case there is no error message in the log file.

## 6. **Simultanious synchronisation**

In order for the Desktop Connector to be able to extract data from a document to upload or update a document with downloaded data it needs access to the document. If the document is in use by another process it cannot access the document. If the document is in use the following error can be seen:

Desktop Connector `The process cannot access the file '\<File path>' because it is being used by another process.`

Log file

```
<Message number>|<Date/Time>|ERROR|1|ExceptionHandleExtension|Some error happen --> System.IO.IOException: The process cannot access the file '<File path>' because it is being used by another process.
```

Processes that can have files in use can include: A different task from the Desktop Connector itself File synchronisation services like Dropbox, Onedrive or Google Drive Other CDE synchronization tools. Programs that have the file open for editing.

If the document is in use the task will stop and not continue if it cannot access one of the files. If multiple tasks have been scheduled it will try again at the next scheduled time.

## 7. **Activity monitoring**

### 7.1 **Task started**

Tasks, that were manually started by clicking on Upload/Download Now in the task, display a status of Uploading or Downloading as soon as the task has started. For both tasks that were manually started and tasks that were started per schedule a message that looks like so appears in the log file when a task starts:

Log file `\<Message number>|\<Date/time>|INFO|1|LoggingExtension|start logging`

### 7.2 **Task running**

Tasks, that were manually started by clicking on Upload/Download Now in the task, display a status of Uploading or Downloading as long as the task is still running. For both tasks that were manually started and tasks that were started per schedule  the state that tasks that are running are in can be seen by monitoring the network usage of the application.

**Initial startup phase** A Desktop Connector task is in its initial startup phase when it is using between 1 kilobyte per second and 1 megabyte per second. During this phase the network useage of the task is minimal.

Download task During the initial startup phase documents on in the server location are checked checked against the local files to see if there are any server files that have changed for which a new revision should be downloaded or if there are any new files on the server side that should be downloaded to the local system.

Upload task During the initial startup phase documents on in the server location are checked checked against the local files to see if there are any local files that have changed for which a new revision should be uploaded or if there are any new local files that should be uploaded to Catenda.

**Active phase** A Desktop Connector task is in its active phase when it is using more than 1 megabyte per second. During this phase the network useage of the task can have an effect on the rest of the system.

Download task During the active phase the Desktop Connector is actively downloading file by file from Catenda to the local system.

Upload task During the active phase the Desktop Connector is actively uploading file by file from the local system to Catenda.

### 7.3 **Task halted**

Tasks, that are manually ran by clicking on Upload/Download Now in the task, display a status message within the task when the task is halted if either when the task has finished or when an error has occurred.

**Task finished** The only way to see if tasks have successfully finished is by manually running the task. Click on Upload/Download Now within the task to do so. When the task has successfully finished a message that all documents have been uploaded or downloaded is displayed in the task.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/03-task-halted.png)

> **Note:** There are no messages in the log file for finished tasks. The only way to see if tasks that were started per schedule have halted is by checking the network usage of the application.

**An error occurred** A more detailed description of errors that have occurred can be seen by checking the log file for any recent errors.

**Network useage** The only way to see if tasks that were started per schedule have halted is by checking the network usage of the application. If the Desktop Connector has used less than 1 kilobyte per second for over 2 minutes any tasks that were running have likely been halted and will not start up again. For tasks that are scheduled to be reoccurring a new task will be started if the Desktop Connector is running at the next date and time that the task is scheduled to commence.

## 8. **Connection between the Connector and Catenda**

### 8.1 **Connection when starting a task**

If there is a problem with the internet connection the upload or download task will not automatically restart and will run again at the next scheduled time. It can also manually be started by going to the task and clicking on the upload or download button.

**No connection** If there is no internet connection available when starting an upload or download task the following error will appear in the upload or download task.

`No such host is known`

**Connection lost while starting task** If the connection to the internet was lost or timed out when trying to connect to the Catenda servers, the following error is displayed:

`The SSL connection could not be established`

**Used connection method depends on preferred method available at task start** When a task is started a connection is made with the preferred internet connection method. For example, if a wired connection and a WiFi connection are available when a task is ran the wired connection is often preferred. If only a WiFi connection is available when a task is started and a wired connection is connected while it is running the connector continues to use the initial connection as long as it is available and does not switch over to a preferred connection that later becomes available.

### 8.2 **Connection during task - Connection to the internet**

**Internet connection no longer available without fallback** If there was only one connection available when the task began or if there were no connection available at all (E.G. Flight mode) the following errror can appear.

`An error occurred while sending the request.`

**Internet connection no longer available with fallback** If there were multiple connections available when the task began and the connection that was in use was lost the connector will attemt to switch to one of the other available connections. During this switching the following error can appear:

`Error while copying content to a stream`

### 8.3 **Connection during task - Desktop Connector session timeout**

The Catenda Desktop Connector has a hardcoded session limit of 10 minutes. This does not mean that a task will time out after 10 minutes since the Desktop Connector often works with multiple short sessions at a time. Large files like point clouds where up to 25 GB at a time is accepted can cause a session to take longer than normal and might time out if it is not uploaded within the 10 minute limit.

`Timeout of 600 seconds elapsing`

Please contact support in this situation. There is a Beta version available per request that can help with this. With the Beta version this limit is slightly increased, but even with the beta version it can time out but instead after 15 minutes.

`Timeout of 900 seconds elapsing`

### 8.4 **Connection during task - Connection to Catenda**

Depending on the speed of the connection on both the up/download side or on the Catenda side it can take shorter or longer to upload files. If the task takes too long the connection might time out.

**Catenda Timeout** If the transfer has taken too long it will time out and the following error will appear:

`A connection attempt failed because the connected party did not properly respond after a period of time, or established connection failed because connected host has failed to respond. (api.bimsync.com:443)`

Please contact support in this situation. There is a Beta version available per request that can help with this.

**Catenda Service unavailable** If the Catenda API is temporarily unable to receive requests in the split second the Desktop Connector is attempting to reach it the following message is displayed.

Desktop Connector `HTTP ERROR 503 Service Unavailable`

Log file

```
<Message number>|<Date/Time>|ERROR|1|BimRequestProviderService|Call API error status code ServiceUnavailable reason: <html><head><meta http-equiv="Content-Type" content="text/html;charset=ISO-8859-1"/><title>Error 503 Service Unavailable</title></head><body><h2>HTTP ERROR 503 Service Unavailable</h2><table><tr><th>URI:</th><td>/v2/projects/10005fce182e49cb91342571746cf1fc/libraries/9a90887d954a444c8ed45695707b2fbd/items</td></tr><tr><th>STATUS:</th><td>503</td></tr><tr><th>MESSAGE:</th><td>Service Unavailable</td></tr><tr><th>SERVLET:</th><td>-</td></tr></table>
```

This is often due to servers being overloaded and many users attempting to send requests at once.

**Gateway timeout** A gateway timeout often means that the Catenda API is running smoothly and that the initial request was properly received. The service that was supposed to handle this request however did not respond in time.

Desktop connector `504 Gateway Time-Out` Log file

```
<Message number>|<Date/Time>|ERROR|1|BimRequestProviderService|Call API error status code GatewayTimeout reason: <html><head><title>504 Gateway Time-out</title></head><body><center><h1>504 Gateway Time-out</h1></center></body></html>
```

This can indicate that Catenda is properly receiving requests but that the server that proccesses the requests is temporarily unavailable. This can sometimes happen when not enough machines are available after which more will automatically start up but this can take some time.

**Access token expired** Catenda access tokens have to be refreshed after an hour. When the Desktop Connector is navigated this is typically not a problem as the token gets refreshed automatically but when a task is started that takes longer than one hour the access token that was used for the task can time out while the task is ongoing. When this happens the following error is displayed in the Desktop Connector. For tasks that take longer than one hour restart the task or wait for the next scheduled task to do the remaining work.

Desktop Connector `Exception of type 'BimsyncApp.Exceptions.BimAuthenticatorException' was thrown.`

Log file

```
<Message number>|<Date/Time>|ERROR|1|BimRequestProviderService|Call API error status code Unauthorized reason: {"error":{"code":12,"message":"Access token has expired"}}.url: 
```

## 9. **This device is currently in use**

While downloading from or uplaoding to an external harddrive Windows will give an error saying that the device is currently in use if it is attempted to be disconnected.

## 10. **Folder permissions**

For folders that are on drive where Windows is installed the right folder permissions are required. Right click the folder you are trying to download to and allow the right permissions.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/04-folder-permissions.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/05-folder-permissions.png)

In this case the log file will give the following error:

`Access to the path '\<Selected local folder path> subfolder \<Path within local folder>' is denied`

### 10.1 **Permission denied**

Even though a folder on Windows can be opened, Windows can enforce a "No-Write-Up" policy. The Desktop Connector will let you select this folder but when the task is ran the following message appers:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/06-permission-denied.png)

In this case the Desktop Connector is blocked from writing, regardless of the user's "Full Control" rights.

Deleting this folder will require the user to gran administrator privileges.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/07-permission-denied.png)

In some situations the folder can still be opened while in others the following message can be seen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/08-permission-denied.png)

Even when continuing the following message can be seen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/09-permission-denied.png)

Clicking on Download Anyway will download the files but they will not be able to be downloaded to the specified folder as that folder is restricted.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/10-permission-denied.png)

Desktop connector `Status: Redirect, click to _view downloaded files_`

Log file `Access to the path '\<Path>' is denied`

Click on view downloaded files to open the location of where the files were donwloaded to.
