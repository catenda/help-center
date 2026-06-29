# Desktop Connector Troubleshooting - Not all folders have been downloaded

In this article information about a specific error that occur when using the [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) can be found. See [here](https://app.intercom.com/a/apps/areracg3/knowledge-hub/all-content?activeContentId=11844906&activeContentType=article&editorMode=view&native_content=false) for other Desktop connector troubleshooting issues.

In the task itself the following can be seen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/01-intro.png)

`Not all folders have been downloaded, click to view errors.`

## 1. **Not-supported characters**

In this case the log file will give the following error:

`The filename, directory name, or volume label syntax is incorrect.`

Document names can be limited with a naming convention in Catenda. Folders cannot be limited. Without the use of a naming convention documents with any name can be uploaded. In this case Catenda might not have been able to register the file extension of the document. Folders with any name can be created. It can therefore be that the Desktop Connector tries to create a file or folder with a character that is not allowed to be used in a path in Windows.

Typical problems arise with the following characters: `\<` - less than `>` - greater than `:` - colon `"` - double quote `|` - vertical bar or pipe `?` - question mark `\*` - asterisk

To find an extensive list of what is reserved in Windows see here: [https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file](https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file)

## 2. **Missing folder or network path**

In this case the log file will give the following error:

`Error: The network path was not found. : '\<path>'`

In this situation the transfer fails immediately. This occurs because the program is trying to reach a folder that is no longer accessible. Because the "pathway" is completely broken, the program cannot even begin the download. There are three main reasons why your folder has become a "Dead End":

### 2.1 **1. The Missing Folder (Most Common)**

The local folder that was previously selected has been moved, renamed, or deleted. When going to the location of the folder in File Explorer, the folder is not there. The Desktop Connector reaches out to save your file, finds "nothing," and stops.

### 2.2 **2. The Broken "Symbolic Link" (The Hidden Redirect)**

A Symbolic Link looks like a normal folder but acts as a permanent "signpost" that redirects Windows to a different location (like an office server). When attempting to open it the following error is displayed in a popup:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/02-2-the-broken-symbolic-link-the-hidden-redirect.png)

`Location is not available... The network path was not found.`

**How to tell them apart:** Like .lnk files, symbolic links will have the small blue "shortcut arrow" in the bottom-left corner of the folder icon or right-click the shortcut and select Properties.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/03-2-the-broken-symbolic-link-the-hidden-redirect.png)

In the General tab the name and target fields are grayed out:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/04-2-the-broken-symbolic-link-the-hidden-redirect.png)

**Why it fails** The "signpost" is on your computer, but the destination (like a `Z:` drive or a server) is disconnected.

### 2.3 **3. The Broken Windows Shortcut (.lnk file)**

A standard Windows shortcut is a small file that "points" to a folder elsewhere. These can be links to a folder on your own hard drive or a folder on a distant office server.

**How to tell them apart:** Like symbolic links, both folder and drive shortcuts will have the small blue "shortcut arrow" in the bottom-left corner of the folder icon or right-click the shortcut and select Properties.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/05-3-the-broken-windows-shortcut-lnk-file.png)

In the General tab look at the Target field: _Local Shortcut_ The target starts with a drive letter (e.g., `C:\\Users\\...` or `D:\\Data`).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/06-3-the-broken-windows-shortcut-lnk-file.png)

_Network Shortcut_ The target starts with a server path (e.g., `\\\\ServerName\\Folder`) or a mapped network drive letter (e.g., `Z:\\ProjectData`).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/07-3-the-broken-windows-shortcut-lnk-file.png)

Different Behaviors when Double-clicked Windows handles a "broken" local shortcut much faster than a "broken" network shortcut.

**Local Shortcut (The "Deleted" Error):** If the folder on your computer was deleted, Windows knows immediately. When the shortcut is double-clicked, the following error is instantly displayed:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/08-3-the-broken-windows-shortcut-lnk-file.png)

**`The item that this shortcut refers to has been changed, moved or deleted.`**

**Network Shortcut (The "Hanging" Error):** If the shortcut points to an office server and you are offline (or off the VPN), Windows doesn't know the destination is missing right away. It will try to "find" the server on the network first. Your mouse cursor may turn into a loading circle, and the window may "hang" or freeze for 30–60 seconds before finally showing:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/09-3-the-broken-windows-shortcut-lnk-file.png)

**`The drive or network connection that the shortcut refers to is unavailable.`**

If the Desktop Connector is told to use one of these shortcuts while the target is missing or the network is down, the program will eventually "time out" waiting for Windows to find the path. Because the Desktop connector cannot find a valid destination to begin the work, it stops and reports the error.

### 2.4 **How to Fix It**

**Identify the Disconnect** Try to open the destination folder in Windows Explorer. If the destination folder is missing, either a new folder needs to be created at that location or a different folder should be selected in the Desktop Connector.

**Reconnect or Re-select** If a "Network path not found" or "Drive unavailable" error pops up confirm the connection to the network path or drive. Go to "This PC" and ensure your network drives (like `Z:`) are active. Check if any external USB drives or hard drives are properly connected. If they have a red X, double-click them to to reconnect. If the network drive is not active and you know what network the drive is on, reconnect to the network either by plugging in a cable, joining via wifi or when using a VPN, check to see if the VPN is active. If the drive is no longer available, select a different destination folder in the Desktop Connector that is available either on the local computer or on the network..

**Delete/rename and Recreate** If a local folder or shortcut remains "stuck" (you see it, but can't open it) even after a reboot: Rename the problematic folder or shortcut file (e.g., rename `ProjectData` to `ProjectData\_OLD`) or delete it. Create a brand-new, standard folder with the same name. Restart the transfer. The Desktop Connector will detect the fresh, healthy folder and resume normal operation.

**Why was no temporary folder created in place of the missing folder?** In other situations the desktop connector creates a folder with `\_restricted` appended to the name when things go wrong. However, there is a technical difference in how Windows handles "missing" locations:

The `\_restricted` Folder is only created if the folder is "physically" there but "locked" (like a doorway to a room that is bolted shut). In that case, the program can see the door and decides to build a new one (`\_restricted`) next to it.

In the case of the missing pathway it is different. The folder is no longer there or the "signpost"(symbolic link) that was selected is pointing to an empty location. To the program, it’s not just locked—the entire "room" is missing from the building. Because there is no "doorway" to start with, the program cannot create a `\_restricted` version and must stop.

## 3. **Missing mount point**

In this case the log file will give the following error:

`Error: Could not find a part of the path '\<path>'.`

If the folder cannot be opened Windows tries to follow the "signpost" to a network location and the following error is displayed:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/10-missing-mount-point.png)

`\<Path> is not accessible.`
`The network path was not found`

In this situation the Desktop Connector automatically creates a new folder with "\_restricted" appended to the name (e.g., `ProjectData\_restricted`).

This happens when a folder on the computer is actually a "Mount Point" (a doorway) to another drive. Examples of other drives can include:

- USB stick,
- External hard drive
- Network volume that is currently disconnected.

Windows "remembers" the folder exists, but because the physical drive is missing, the folder becomes a "Ghost." The Desktop Connector detects that the folder is there but cannot write to it. To prevent your data from being lost, a Shadow Folder is created with the `\_restricted` suffix so your files have a safe place to land.

Here are some typical situations in which this can happen:

- The folder was mapped to a drive (like `D:`) that has been unplugged.
- The folder points to a network share (like `Z:`) that is offline or requires a VPN.
- A cloud service (Dropbox, OneDrive or other collaboration tool synch services) created a "placeholder" folder that is not currently active.
- An enterprise security tool is "shielding" the folder from being modified by third-party apps.

To check if your folder is a "Ghost" right-click the folder and select Properties.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/11-missing-mount-point.png)

Look at the Type field in the General tab: A Normal Folde**r** will say "File folder." while a ghost folder will say "Mounted Volume."

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/12-missing-mount-point.png)

When the mounted folder is double-clicked, the following error is instantly displayed:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/13-missing-mount-point.png)

**`Location is not avialable`** or

**`The network path was not found`** `\<Path> is unavailable like so the link is broken`

### 3.1 **How to Fix It**

Manually Recreate the Folder If the folder remains "stuck" even after a reboot:

1. Rename the problematic folder (e.g., rename `ProjectData` to `ProjectData\_OLD`).
1. Create a brand-new folder with the original name (`ProjectData`).
1. The Desktop Connector will detect the fresh, healthy folder and resume normal operation without the `\_restricted` suffix.

**Reconnect the Hardware or Network** Go to "This PC" and ensure your network drives (like `Z:`) are active. Check if any external USB drives or hard drives are properly connected. If they have a red X, double-click them to to reconnect. If the network drive is not active and you know what network the drive is on, reconnect to the network either by plugging in a cable, joining via wifi or when using a VPN, check to see if the VPN is active. If the drive is no longer available, select a different destination folder in the Desktop Connector that is available either on the local computer or on the network.

**Delete/rename and Recreate** If a local folder or shortcut remains "stuck" (you see it, but can't open it) even after a reboot: Rename the problematic folder or shortcut file (e.g., rename `ProjectData` to `ProjectData\_OLD`) or delete it. Create a brand-new folder with the original name (`ProjectData`). Restart the transfer. The Desktop Connector will detect the fresh, healthy folder and resume normal operation without the `\_restricted` suffix.
