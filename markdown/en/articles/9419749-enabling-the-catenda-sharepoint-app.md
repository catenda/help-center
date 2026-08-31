# Enabling the Catenda SharePoint app

> **Note:** The install file for the plugin can be found in [this article](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

The Catenda SharePoint application can be enabled for a SharePoint environment by a system administrator and then added to a site by a site owner. With this app SharePoint users will be able to view, manage and collaborate on documents in Catenda together with other members of the construction project.

To enable the app for your environment you will be able to find its entry here: [Microsoft AppSource](https://appsource.microsoft.com/en-us/marketplace/apps?search=Catenda&page=1) which can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/01-intro.png)

After clicking on "Get it now" you will be asked to log into your SharePoint account if you are not logged in already. You will then be redirected to the SharePoint Store entry The SharePoint store can also be found by clicking on your profile on the top right in SharePoint and then clicking on Add an app

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/02-intro.png)

In the SharePoint store you will also be able to search the Catenda SharePoint application:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/03-intro.png)

**https://\<Tenant>.sharepoint.com/sites/appcatalog/\_layouts/15/appStore.aspx/sharePointStore?entry=ClassicAppCatalog&sorting=7&search=catenda**

The SharePoint Store entry can look something like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/04-intro.png)

**https://\<Tenant>.sharepoint.com/\_layouts/15/appStore.aspx/appDetail/WA200005981**

## 1. **Regular SharePoint users**

Regular SharePoint users will be able to request the Catenda SharePoint app to be enabled by clicking on the Add to Apps site button. You will see if your request was approved on the My requests page in the SharePoint store. If you are an administrator you will be able to approve the request from the app catalog

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/05-regular-sharepoint-users.png)

**https://\<Tenant>.sharepoint.com/sites/appcatalog/SitePages/Home.aspx**

## 2. **SharePoint administrators**

As an administrator in a SharePoint environment you will be able to enable the app by clicking Add to Apps site. Here you will be asked to confirm data access.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/06-sharepoint-administrators.png)

### 2.1 **Confirm data access**

The app you're about to enable will have access to data by using the identity of the person using it. Enable this app only if you trust the developer or publisher. The app needs this permission to know which of the users files to publish when they choose to publish them. The endpoint is: [https://sharepoint.plugins.catenda.com/1.0.0.0/](https://sharepoint.plugins.catenda.com/1.0.0.0/)

### 2.2 **API access**

If API access had not previously been enabled it has to be enabled for the application to work.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/07-api-access.png)

To approve API access, go to the API access page in your admin center https://\<Tenant>.sharepoint.com/\_layouts/15/online/AdminHome.aspx#/webApiPermissionManagement

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/08-api-access.png)

API access is needed so that SharePoint administrators will have to connect their Catenda account to enable the publishing of documents. Users will also be asked to log in with their Catenda account when they try to publish something to Catenda as each user can have different permissions in Catenda.

Without API Access the Catenda Sharepoint Application can be enabled after which both the list action and webpart will be visible but not useable as no data can be exchanged without connecting your Catenda ccount. _Access required:_ Global Administrator role or Application Administrator role in Microsoft 365.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/09-api-access.png)

**Approve access** Select Catenda in the list of pending requests and click on approve towards the top. For the Catenda Apllication to work it needs the permission: access

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/10-api-access.png)

**Remove access** Select Catenda on the API access page and click on remove towards the top.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/11-api-access.png)

In the next menu, click on Remove

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/12-api-access.png)

While the Catenda application might be enabled, users will not be able to connect to Catenda after this access has been removed.

## 3. **App availability**

### 3.1 **Only enable this app**

This option enables the app for the SharePoint environment which lets site owners within your environment add the app to their from the My apps page. The app does nothing until it is added to a site. While this option is great, if you like to have better control over which sites users are able to publish documents to Catenda from, it can make it confusing to users if some sites have the option to publish while others do not. For even more control you can enable the [site collection app catalog](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/site-collection-app-catalog) which give site lets you choose which apps site owner can install. With this option the app will also not be on by default on new sites which means it is more work to configure a new site when it is created.

### 3.2 **Enable this app and add it to all sites**

With this option the app will automatically be added to all sites. The only visual difference the user will wee when the app is added to their site is that they will have the list command in their list and hamburger menu when selecting a document. Webparts and full pages will have to be added later. This can also be done from the manage apps page later.

### 3.3 **Add to teams**

With this option the app will also be added to Teams. This will allow users to see the teams tab. This can also be done from the manage apps page later.

## 4. **Manage apps**

After enabling the app SharePoint administrators will be able to see your app in the Manage apps area. https://\<Tenant>.sharepoint.com/sites/appcatalog/AppCatalog/Forms/AllItems.aspx

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/13-manage-apps.png)

After selecting the app it can be added to different parts of Sharepoint.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/14-manage-apps.png)

### 4.1 **Add to all sites:**

This will add the app to all sites and all new sites that are created. If the app is enabled, site owners will also be able to individually add the app to a site. If you do not wish to keep adding the app to new sites you can stop doing so by clicking on stop adding to new sites.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/15-add-to-all-sites.png)

The functionality provided by the app will continue to be available on all sites where it was added, and site owner can still add this app to their sites.

### 4.2 **Add to Teams:**

This enables the teams tab for the app.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/16-add-to-teams.png)

For the app to be added to teams it has to be added to all sites first.

## 5. **Further reading**

See [here](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application) for information about how this application works after it is installed See [here](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq) for more information about how this application can be useful.
