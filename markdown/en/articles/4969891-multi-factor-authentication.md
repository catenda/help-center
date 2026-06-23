# Multi Factor Authentication

> Describes how to set up MFA on your account

You will be able to find the **Multi Factor Authentication** (MFA) settings on the [authentication page](https://support.catenda.com/en/articles/6880968-account-page#h_e04d63351f) which is a sub page to the [account page](https://support.catenda.com/en/articles/6880968-account-page).

**Multi Factor Authentication** (MFA) requires entering a code received via your mobile device as well as your username and password, when logging on to Catenda Hub. When an organization requires MFA it's applied at a organization level. All projects belonging to that organization will then require MFA to access their projects. This will force all users to enable MFA to access projects belonging to that organization.

## 1. **Enabling MFA**

Log onto Catenda Hub and go to the **[Account](https://hub.catenda.com/account/profile)** page:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/01-enabling-mfa.png)

1. Click on the **[Authentication](https://hub.catenda.com/account/authentication)** tab:
1. Scroll down to the section for MFA:
1. Click on **Enable MFA**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/02-enabling-mfa.png)

### 1.1 **Authentication app**

To get started install an application on a mobile device that supports the TOTP (Time-based one-time password) protocol. Install a trusted authentication app on a mobile device to get started. The amount of time an authentication application has been around and the jurisdiction where the company it is owned by is based are often good to look at. Here are some examples of recommended authentication applications:

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 139px;"><h3 id="h_b56161ee38"><b>Auth app security laws</b></h3></td><td style="background-color: #e3e7fa80; width: 101px;"><h3 id="h_49bc31efe9">Company</h3></td><td style="background-color: #e3e7fa80; width: 119px;"><h3 id="h_46b679c81c">Jurisdiction</h3></td><td style="background-color: #e3e7fa80;"><h3 id="h_7699fa4ab6">Security laws that apply</h3></td></tr><tr><td style="width: 139px;"><h3 id="h_ae65255403">Aegis</h3></td><td style="width: 101px;"><p>Beem</p></td><td style="width: 119px;"><p>Netherlands<br/>(Dordrecht)</p></td><td><p>GDPR<br/>9 eyes agreement</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_42b556ff02">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Roland Moers</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Germany</p></td><td style="background-color: #e8e8e880;"><p>GDPR<br/>Bundesdatenschutzgesetz - BDSG <br/>14 eyes agreement</p></td></tr><tr><td style="width: 139px;"><h3 id="h_5e0c03d260">Authenticator</h3></td><td style="width: 101px;"><p>Google</p></td><td style="width: 119px;"><p>United States<br/>(California)</p></td><td><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_918c12706e">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Microsoft</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>United States<br/>(Washington)</p></td><td style="background-color: #e8e8e880;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="width: 139px;"><h3 id="h_b3a055f26d">Ente Auth</h3></td><td style="width: 101px;"><p>Ente</p></td><td style="width: 119px;"><p>United States (Delaware)</p></td><td><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_63d03979d2">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Internet Initiative Japan</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Japan</p></td><td style="background-color: #e8e8e880;"><p>Act on the Protection of Personal Information (APPI)</p></td></tr><tr><td style="width: 139px;"><h3 id="h_848afb2dfa">HENNGE Lock</h3></td><td style="width: 101px;"><p>HENNGE K.K.</p></td><td style="width: 119px;"><p>Japan</p></td><td><p>Act on the Protection of Personal Information (APPI)</p></td></tr></tbody></table></div>

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 138px;"><h3 id="h_5e28bb0eb3"><b>Auth app functionality</b></h3></td><td style="background-color: #e3e7fa80; width: 88px;"><h3 id="h_6ed7d3e230">Release date</h3></td><td style="background-color: #e3e7fa80; width: 180px;"><h3 id="h_f652151c66">Operating System</h3></td><td style="background-color: #e3e7fa80;"><h3 id="h_824368384e">Code extraction</h3></td></tr><tr><td style="width: 138px;"><h3 id="h_218c61c8b2">Aegis</h3></td><td style="width: 88px;"><p>2019</p></td><td style="width: 180px;"><p>Android</p></td><td><p>Export to Full Plaintext or Encrypted file. JSON / TXT / QR</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_0274ada2cb">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2020</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS</p></td><td style="background-color: #e8e8e880;"><p>Export to proprietary File / View Secret</p></td></tr><tr><td style="width: 138px;"><h3 id="h_cc8ae8a27d">Authenticator</h3></td><td style="width: 88px;"><p>2010</p></td><td style="width: 180px;"><p>iOS<br/>Android</p></td><td><p>Transfer to other Google Authenticator app with Google account</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_6d595cbd69">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS<br/>Android</p></td><td style="background-color: #e8e8e880;"><p>Transfer to other Microsoft Authenticator app with Microsoft account.</p></td></tr><tr><td style="width: 138px;"><h3 id="h_9cbe3f20d2">Ente Auth</h3></td><td style="width: 88px;"><p>2020</p></td><td style="width: 180px;"><p>iOS<br/>Android</p></td><td><p>JSON / TXT</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_425ee9cdba">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS - 8.1+<br/>Android - 4.0+</p></td><td style="background-color: #e8e8e880;"><p>QR code export per code.</p></td></tr><tr><td style="width: 138px;"><h3 id="h_10c8930b4e">HENNGE Lock</h3></td><td style="width: 88px;"><p>2020</p></td><td style="width: 180px;"><p>iOS - Latest 2 major versions <br/>Android - latest 4 codenamed versions</p></td><td><p>None</p></td></tr></tbody></table></div>

Theoretically any application that supports MFA / Two factor authentication via the TOTP protocol can be used. There are even Desktop applications out there however these are not recommended due to the fact that Desktop applications are often always connected to the same network which often has multiple devices on it increasing the risk of a bad actor getting access to the code.

**App permissions**

In order for you to be able to scan the QR code with the camera of the device. The authentication app will need camera permissions to be able to scan the code. The application may ask to receive permission to use the camera of the device. Permission options may include: "Only while using the app" - The app has permission while in use. "Ask every time" - Permission has to be granted with each use of the app. "Don't allow" - Permission is not given or revoked from the app.

**Google Authenticator**

Click on the plus on the bottom right and Scan a QR code. Here you will scan the QR code that the [authentication](https://hub.catenda.com/account/authentication) page gives you. Alternatively you can use your camera to scan the code and type in the setup key that you see in the URL that is opened.

**Microsoft Authenticator**

Make sure you are in the Authenticator menu on the bottom.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/03-authentication-app.png)

> **Note:** make sure you are not in the Verified IDs menu as you can scan a qr code here but this will not work.

Next click on the plus in the blue bar on the top right. Select Other account (Google, Facebook, etc.) If your app does not have permission to your camera you may/may not be asked to give permission to your camera.

If your app has access to your camera you can scan the QR code that the [authentication](https://hub.catenda.com/account/authentication) page gives you.

If your app does not have access to your camera you will be asked to manually create an account.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/04-authentication-app.png)

Account name: The name you give to your account Secret key: This is the key you would have gotten if you had been able to scan the qr code. You can use your camera app to scan the code. The URL that opens when you scan the code can look something like this: `otpauth://totp/\<Catenda account email address>?secret=\<Secret key>&issuer=Catenda&algorithm=SHA1&digits=6&period=30` If you type in the code after "`secret=`" in the secret key that you see in the URL that is opened, Account name can be anything.

> **Note:** If you create an account with the wrong secret key the app will generate one-time codes anyway so Catenda might not accept the code if the wrong secret key was used.

### 1.2 **Success or fail**

**Success**

After successfully enabling MFA you will see this message.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/05-success-or-fail.png)

Once enabled you will need to have your mobile device at hand every time you log onto Catenda Hub. The MFA can be disabled again by clicking on Disable MFA.

**Incorrect code**

If you did not insert the right code, you will get the message incorrrect code.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/06-success-or-fail.png)

> **Note:** If you have scanned the QR-Code you can try inputting the code within the given timeframe for that code while you have this menu open. If you close this menu, you will have to remove the code that is being generated in your authenticator app and scan the QR-Code again to set up a new code pairing.

## 2. **Modifying MFA**

After connecting an MFA code you can safely edit the account name of the code. You can do so in the following ways:

**Google authenticator**

1. Long press the code
1. Click on the pencil on the top right to change the name.

**Microsoft authenticator**

1. Click on the code.
1. Click on the gear button on the top right
1. Click on the pencil the change the name

## 3. **Transferring MFA**

**Deactivating and reactivating**

It is only possible to use MFA app code pairing at a time. If you wish to switch to a different code pairing, perhaps because your current one has been compromised, you follow these steps: You should also use this method if you wish to change the app you use for MFA.

1. Disable your MFA on the [authentication page](https://hub.catenda.com/account/authentication)
1. Prepare the app you want to use to re-connect your MFA
1. Generate a new code-pair by scanning the QR code like in the [enabling section](#h_9e13fd06f5)

> **Note:** Be careful with this method as your account will temporarily be vulnerable while it is deactivated and you will not be able to access projects where MFA is required during this time.

**Transferring through backup**

If you wish to start using a new device without your code temporarily being disable you can use a different installation of the same MFA app and transfer the code from the old installation to the new installation.

**Google authenticator**

Old device:

1. Tap on the hamburger menu top right
1. Tap on Export accounts
1. Select the accounts you wish to export

New device:

1. Tap on the hamburger menu top right
1. Tap on import accounts
1. Tap on scan QR code
1. Scan the QR code that is displayed on the old device when you went through the export process.

**Microsoft authenticator**

Old device:

1. Tap the hamburger menu top right
1. Turn on backup

New device:

1. Install and open the Microsoft Authenticator app on your new device
1. Tap "Begin Recovery."

> **Note 1:** Do not set up any accounts using Microsoft Authenticator until after you have used the Recovery tool because it will overwrite matching site accounts.

> **Note 2:** This method requires you to backup your MFA codes which means they are stored in your app providers cloud service. Only use this method if you trust your app providers backup service. If not you are better off deactivating and reactivating.

## 4. **Disabling MFA**

You can disable MFA by clicking the disable button shown above, then entering your password to confirm. After disabling you no longer be able to access projects requiring MFA.

After disabling the code on Catenda Hub, the code will remain on the application that you connected with. This code will now be useless and can safely be deleted.

### 4.1 **How to delete the old code:**

**Google authenticator**

1. Long press the code
1. Click on the trashcan on the top right.

**Microsoft authenticator**

1. Click on the code.
1. Click on the gear button on the top right
1. Click on remove account

## 5. **MFA on non-mobile devices**

Authenticator apps are more secure than SMS/Email code solutions as there is no communication that can be intercepted between the two systems after the original configuration. While it is better to use an app on a mobile application, see note below, It is possible to get MFA codes on other systems than just mobile devices. The recommended desktop application for this is [Authy](https://authy.com/). Functionally, these types of applications use the same TOTP protocol as the app on your mobile device and should be just as secure.

> **Warning:** Desktop apps can be less secure as they might be easier to hack or get access to. This is because desktop systems are often, if not always, connected to the local network which might be infected. Mobile devices that are not always connected to the network can therefore be harder to get into.

## 6. **Who can enforce MFA on projects?**

Enterprise customers can request an [organization option](https://support.catenda.com/en/articles/8224886-organization-options#h_d6710faf75) to be turned on which makes it so that all users that are part of their projects have to use MFA to enter the project. To enable MFA on your organization's projects, contact Catenda support. When MFA is required on an organization's projects you will see this message when attempting to open the project.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/07-who-can-enforce-mfa-on-projects.png)
