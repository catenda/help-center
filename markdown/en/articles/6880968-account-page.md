# Account page

Your [account settings](https://bimsync.com/account/profile) can be found in two places:

1. On the left side of the **home page** of Catenda Hub.
1. In the dropdown menu that appears after clicking on your **profile picture** anywhere in Catenda Hub.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/01-intro.png)

The [account page](#account-page) has three sub pages.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/02-intro.png)

## 1. **Account**

On the [account page](https://bimsync.com/account/profile) it is possible to change your username and profile picture It is not possible to change your email address as it is bound to your account.

this is what the account page can look like:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/03-account.png)

As can be seen on the top right, if no profile photo is uploaded the initials from the username are displayed. The initials that are displayed are the first three characters after each space in the username. It is not possible to set custom initials. One way around this would be to make a profile picture with the desired initials in them.

### 1.1 **Change photo**

Click on change photo and select a profile picture from your system. The set new photo dialogue will open up which can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/04-change-photo.png)

Click on set new photo to save the profile picture. This is what the profile photo menu can look like after the profile picture has been added

![](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/05-change-photo.png)

> **Note:** that the profile picture is only visible in Catenda products and will not be visible in other products that information from Catenda may have been exchanged with.

### 1.2 **Delete photo**

Click on delete photo to delete your profile picture.

## 2. **Preferences**

In [preferences](https://bimsync.com/account/preferences) it is possible to:

![Customize various aspects in Catenda Hub](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/06-preferences.png)

### 2.1 **Language**

[Change the language](https://support.catenda.com/en/articles/4670248-changing-to-your-preferred-language) of Catenda Hub

### 2.2 **Date and time**

Choose in what format you would like to see date and time settings. By default date and time settings are shown as relative to your current time. This means that an issue that is created or a model that is uploaded will be shown as having been made 1 week or 1 month ago. If you need more specific information than that for example to see how much time has passed between to items that were uploaded close to each other it is possible to turn this option off. The date and time around Catenda Hub will now be shown with the specific date and time of the occurrence.

## 3. **Authentication**

In [authentication](https://bimsync.com/account/authentication) it is possible to:

1. Change your password

    Click [here](https://support.catenda.com/en/articles/10798891-sign-in-and-passwords) for password troubleshooting

1. [Enable and disable MFA.](https://support.catenda.com/en/articles/4969891-multi-factor-authentication)

![Control how you log in](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/07-authentication.png)

## 4. **Applications**

On [the applications page](https://bimsync.com/account/apps) applications that are configured for the account can be displayed. This is what the applications page can look like:

![Manage your applications and applications accessing your data](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/08-applications.png)

### 4.1 **Your applications**

Every API appication is connected to a Catenda account. The configuration of the application can be displayed in the your applications area. With a configured application this is where the following settings can be found:

**Application name** The name of the application. This name is configured by Catenda. To change the name of your application, please contact support.

**Client ID** The client id of the application. Every application has a unique id which cannot be changed.

**Client Secret** The password of the application Every application has a unique password which cannot be changed.

**Redirect URL** The URL that the application will redirect access codes to when a request is sent with the right client secret and client id. To correctly receive an access code, the URL in the request has to match the URL that is configured here.

### 4.2 **Applications with access to your account**

Applications that have been granted access to the account are displayed. Click [here](https://support.catenda.com/en/articles/8396532-catenda-connections) to see which applications that can be connected to.

**Revoke access** Click on revoke access to revoke the access that was granted to that application. After doing so access will have to be granted again to continue using that applicaiton with this account. Depending on the application it may ask the user to grant access again or it might give an error and not ask for new access. Loggin out and back in often resets the connection in this case.
