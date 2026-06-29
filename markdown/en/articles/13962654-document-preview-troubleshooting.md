# Document Preview Troubleshooting

In this article you will find information about the errors that can occur in the [document preview](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations).

## 1. **1. Cannot Connect to Server**

When a document is opened, the document preview can be grayed out with a centered message that says:

`Cannot connect to server`

This problem can also look like severe platform slowness or loading wheels that never stop spinning, especially on the **Collections** page or when trying to load the **Models list** inside the 3D Viewer.

### 1.1 **1.1 Why This Is Happening**

There is a restriction on the specific internet network or VPN connection in use. The security settings on the network allow the main Catenda website to load, but completely block or reject the background connections the platform uses to send and receive heavy project data and 3D models. Because these background data streams are cut off, the system cannot load the information, causing the platform to hang indefinitely or show a connection error.

### 1.2 **1.2 Troubleshooting Step**

Confirm if the network is causing the block, try loading the platform or document preview while connected to a different network, such as a cellular mobile network hotspot. If the page and data load normally there, the primary network configuration is blocking the traffic.

### 1.3 **1.3 Permanent Fix for Network Administrators**

To resolve this issue permanently, the network configuration must be updated to fully support Catenda's background traffic, including all subdomains and required ports. Click [here](https://support.catenda.com/en/articles/13927294-network-recommendation) to read more about whitelisting requriements and port specifications (including mandatory Port 443 TCP/UDP configurations).

## 2. **2. Error Loading Document (Read Timed Out)**

When a document is opened, the webviewer that displays the document preview can display a message that says: **"Read timed out"**.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hq07qt4s/01-2-error-loading-document-read-timed-out.png)

`Read timed out`

### 2.1 **2.1 Why This Is Happening**

The security settings on the network in use only allow the main Catenda website address to pass through. The network's firewall does not recognize or allow a wildcard setting (which automatically permits all addresses ending in `.catenda.com`), so it blocks the specific, separate background address that handles document previews (`webviewer.catenda.com`). Instead of rejecting the connection instantly, the firewall ignores the request until the browser gives up waiting, resulting in a time-out error.

### 2.2 **2.2 Troubleshooting Step**

Confirm if the network configuration is causing the timeout, try loading the document preview while connected to a different network, such as a cellular mobile network hotspot. If the preview loads normally there, the primary network's firewall configuration is blocking the traffic.

### 2.3 **2.3 Permanent Fix for Network Administrators**

To resolve this issue permanently, the network's firewall configuration must be updated to explicitly allow the specific address used for document previews (`webviewer.catenda.com`). Click [here](https://netw) to read more about whitelisting rules and port specifications.
