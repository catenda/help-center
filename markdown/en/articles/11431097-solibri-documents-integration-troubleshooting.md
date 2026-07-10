# Solibri documents integration troubleshooting

Errors that can be encountered with the Solibri documents integration and how to solve them are explaind in this article.

## 1. **Account connection and access**

### 1.1 **Signing out during up-download not recommended**

It is possible to sign out of your account in the document selection menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/01-signing-out-during-up-download-not-recommended.png)

If you sign out here and sign back in the page will look like this instead:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/02-signing-out-during-up-download-not-recommended.png)

While you can access a different Catenda account from the one you have granted access to this way, it is not recommended. Access will not have been granted for that account and any models or documents that are navigated to will not be imported to Solibri.

### 1.2 **Upload -** No access to document

If you try to upload your smc to a revision that you do not have access to you will see the following warning.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/03-upload-no-access-to-document.png)

In this situation please ask a project administrator if they can give you access to the document.

### 1.3 **Upload -** No access to folder

If you try to create a new document in a folder where you only have read access you will see the following message.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/04-upload-no-access-to-folder.png)

In this situation please ask a project administrator if they can give you at least write access to the folder.

### 1.4 **Revoke access to your Catenda account**

Go to the applications page of our your Catenda Hub [account settings](https://intercom.help/bimsync-arena/en/articles/6880968-account-settings#:~:text=your%20notification%20settings.-,Applications,-In%20applications%20you), find the Solibri application and click on revoke.

### 1.5 **Disconnect from the Catenda Server**

If you not longer wish to connect to the Catenda server, click disconnect.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/05-disconnect-from-the-catenda-server.png)

After disconnecting solibri will still have access to your account. If you wish to connect again later on you will not have to authenticate again.

### 1.6 **Connect with a new account**

In the following situations it can help to connect with a new account:

- Access to your account has been revoked.
- Giving access to a different account.
- Resetting the connection if it has stopped working

The old account can be disconnected in the following ways:

### 1.7 **Revoke access on Catenda**

To revoke the access that Solibri was granted to an account, log in with the account on Catenda. After having logged in, go to the applications page [https://hub.catenda.com/account/apps](https://hub.catenda.com/account/apps) If Solibri was granted access to this account you will see Solibri in the list of applications with access to the account. Click on revoke access. If Solibri was connected with this account it will ask the user to grant access to a new account.

### 1.8 **Delete .solibri folder**

Another way to remove the connection to a Catenda account is by deleting the userdata in Solibri. To do so delete the folder that is located here:

`C:\Users\<Username>\.solibri`

> **Note:** By default this is a hidden folder on your system. Type the path directly in your file explorer or find out how to unhide hidden folders here: [https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5](https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5)

The Solibri login data is stored in this folder so Solibri will have to be logged into again next time it is opened.

## 2. **Upload**

### 2.1 **Requested document not found**

If you have opened your .smc from Catenda, the location in the project you opened it from will be remembered. When you later re-upload the .smc to Catenda and either the document has been moved or does not exist in the project you have navigated to, you will see the following message.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/06-requested-document-not-found.png)

### 2.2 **No new revision**

If you have opened a .smc from Catenda and upload it back to Catenda without making any changes, even if you have saved the smc somewhere, you will not be asked to save it first and it will seem like it gets uploaded. After uploading you will get the following message as expected:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/07-no-new-revision.png)

If your file had the same name as a document in the folder you will see that no new revision is added to that document in Catenda. Please try uploading your .smc again if this is the case.

### 2.3 **New document instead of new revision**

If your file had a different name, but you selected a document for the revision to be uploaded to, you will see that a new document will be created based on your file name your file will not be a new revision of the document. Please make sure your file has the same name as the document if you want it to become a new revision to that document and not a new document.

### 2.4 **Button not available**

If you are trying to upload documents you could see the message that no files are selected.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/08-button-not-available.png)

This can be the case when you have granted Solibri access to Catenda with one account, but are attempting to upload a .smc file with another account. To give access to a different account see [here](#connect-with-a-new-account).

## 3. **Download**

### 3.1 **Error**

If you have selected a document, you could see an error in the right menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/09-error.png)

This can be the case when you have granted Solibri access to Catenda with one account, but are attempting to download the document with another account. To give access to a different account see [here](#connect-with-a-new-account).

### 3.2 **Filetype not supported**

With the documents integration, after navigating to and selecting an unsupported document on the documents page in a project you will see the following message in the right information menu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/10-filetype-not-supported.png)

Attempting to download a document with a different extension will not have an effect.

### 3.3 **Nothing happens**

The account you are logged in with is different thant the acocunt you have granted access for.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/11-nothing-happens.png)
