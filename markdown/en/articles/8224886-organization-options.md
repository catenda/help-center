# Organization options

It is possible to request the following options to be set for your organization. These options will apply to all projects owned by the organization.

## 1. **Profile**

Please contact support through the black chat button next to your profile picture on the top right or at [support@catenda.com](mailto:support@catenda.com) if you wish to change the name of your organization.

## 2. **Plan**

Please contact [sales@catenda.com](mailto:sales@catenda.com) for questions regarding your plan. Your plan decides how many projects you can have at any moment in an organization. Your plan also decides when new projects expire.

## 3. **Defaults for new projects**

### 3.1 Document download title option

The document download title option decides which file name a downloaded file gets. You can let the file keep its [revision name](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page#h_01e7f2d654), or you can use the name of the document in Catenda. This can be useful in combination with the naming convention, and for overwriting documents that have the same name instead of with a different revision number every time.

The option is one of the defaults for new projects. When the organization changes it, the change only applies to projects created afterwards. Existing projects keep the setting they already have.

**Example:** The name of the project is _testproject._ Two files are uploaded with two revisions each: _test01.pdf_ and _test02.pdf_ The names of the documents are then changed to: _changed01.pdf_ and _changed02.pdf_

**Options:** The options below decide what these two files are called when you download them.

**Revision file name** \<Revision name>.\<Extension> _test01.pdf_ and _test02.pdf_

**Document title** \<Document name>.\<Extension> _changed01.pdf_ and _changed02.pdf_

**Document title with revision number** \<Document name>\<Revision number>.\<Extension> _changed01.pdf #2_ and _changed02.pdf #2_

**Project title with Document title and Revision number** \<Project name>\<Document name>\<Revision number>.\<Extension> _testproject changed01.pdf #2_ and _testproject changed02.pdf #2_

### 3.2 Where the option applies

The option applies when you download a single file and when you download several files at once. It applies to documents downloaded from the documents section and to models downloaded from the models section. It also applies when you click **Download collection** on the collections page.

### 3.3 Exceptions to the option

A few downloads ignore the option.

**Public links** If you share a collection with a public link, the person who opens the link downloads from the Catenda Transfer page. The files they download always keep their revision name.

**Annotation toolbar** When you download from the action menu in the annotation toolbar of the document preview, the file always gets the revision name, whatever the option is set to. If you choose **Save As** in the same menu, you can enter the file name you want.

### 3.4 Challenges with the option

Two projects in the same organization can name the same file differently. The option is only a default for new projects, so a project created before the option was changed keeps its old setting.

The same document can also get different names depending on where you download it. The annotation toolbar and public links always use the revision name, while the other downloads follow the option.

If you choose an option that uses the document name, the file name depends on the document name in Catenda. When a new revision is uploaded and the document name is not updated, the downloaded file can be missing information that was in the revision name. This is why some organizations keep the **Revision file name** option.

With the **Revision file name** option, a file that was uploaded with an unclear name keeps that name when it is downloaded.

### 3.5 **Downloading of infected documents**

Quarantine handling for infected files in owned projects. If a document is found to be infected, by default, it can be downloaded. The user will get a warning that this document includes a virus. An option can be set per organization that makes it so no-one, not even administrators will be able to download infected documents.

**Options:** _Warn on download_ - default

**Block download**

### 3.6 **Models as documents**

If this feature is turned on all new projects that are made in the organization will have the [Models as documents](https://support.catenda.com/en/articles/8064548-models-as-documents) feature turned enabled.

> **Note:** 24 November: This feature will be enabled for all new organizations. We will support the old view for about a year before all projects are migrated.

### 3.7 **Document upload draft option**

If approval flow has been enabled and there are draft statuses in document settings the upload as draft checkbox is checked by default upon document upload. Per request this can this checkbox can be set to unchecked by default for all projects in an organization.

## 4. **Members**

Users can be added as members or owners of an organization.

### 4.1 **Owners**

Owners of organizations can see an overview of the organization in the [organization tool](http://hub.catenda.com/orgs). In this tool they will be able to: Move projects to other organizations they own (Archives are often a separate organizations) Create new projects within the organization if your plan allows that. Delete projects owned by the organization. Add organization members to projects without inviting them. Invite users to organization projects without having to be part of the project. It is recommended that this organization owners are kept few as projects do not have to be moved often.

### 4.2 **Members**

Members of organizations can easily be added to the organizations projects by organization owners.

## 5. **Project owner rules**

### 5.1 **Enforce that all users require MFA**

Enterprise customers can request the enforcement of MFA for users participating in their projects. With this option all users are required to have MFA set up to join projects that are owned by your organization.

### 5.2 **Internal SSO users do not require MFA**

Enterprise customers can request to set up [Single Sign-On](https://en.wikipedia.org/wiki/Single_sign-on). There is a fee involved as it takes our developers some time to set up the configuration.

_What does this rule do?_ By default users who log in with SSO and users who log in normally are treated the same. If MFA is enforced for an organization both regular users and SSO users therefore have to insert the MFA code to log in and access the project. If this option is checked for an organization SSO users do not have to use MFA to access the project. Regular users would still have to input the MFA code while SSO users could log in without having to use the code.

_What is SSO?_ [Single Sign-On](https://en.wikipedia.org/wiki/Single_sign-on) allows the user to log in once and access services without re-entering authentication factors. With this option you can make it so users for your organization do not have to set up MFA. Users from different organizations that are part of your organizations projects will still have to have MFA on if the option above is enabled.

_Setting up SSO:_ It is possible to set up SSO with any SSO provider as it is a standardized process please find some of the most common SSO providers below:

_Microsoft Active Directory:_ To configure SSO with Microsoft Active Directory a new Azure Enterprise Application has to be configured an the Azure AD environtment. Typically it is the system administrator of the entity that is does this configuration. In the Azure AD environment the following fields have to be filled out with SAML authentication by the system administrator: Entity ID: [https://hub.catenda.com/metadata.xml](https://hub.catenda.com/metadata.xml) This XML file is available for download but typically only the URL should be pasted in the field. Assertion Consumer Service (ACS) URL: [https://hub.catenda.com/sso/saml/v2/attribute](https://hub.catenda.com/sso/saml/v2/attribute) This link is also to be posted into the field and is not accessible by opening it in a browser. Once configured the Identity provieder will issue a POST request to this endpoint. If this endpoint is called from a normal browser (GET request) or via a POST request without the correct data the page will not load. Sign-on URL [https://hub.catenda.com/signin](https://hub.catenda.com/signin) This is the signin page that will redirect to the configured Identity provider before granting access to Catenda.

When that is done your system administrator will have to get back to us with the App Federation Metadata URL and Federation Metadata XML for the new application.

**GSuite:** Set up SSO as in [this article](https://support.google.com/a/answer/12032922?hl=en)

**Test users:** Once the SSO setup is configured, please supply a list of test users for which the SSO can be enabled first so you can see how the SSO will work for them. Once the test users have been tested the rest of the users can be enabled.

**Black and Whitelist:** It is also possible to configure a black/whitelist: For example: All users except: X, Y and etc. should be allowed to log in with SSO or, Only X, Y and etc. should be allowed to log in with SSO This information will have to be supplied in addition to the XML file as specified above.

### 5.3 **Disable public sharing feature**

This option lets you disable the public sharing feature for all projects in your organization. If this option is enabled it will no longer be possible to:

- [Enable public URLs for bookmarks](https://support.catenda.com/en/articles/6423215-public-bookmarks-short-video).
- [Enable public URLs for document collections](https://support.catenda.com/en/articles/6344318-collections-page#h_c1e1a2a402).
- [Share document collections via email](https://support.catenda.com/en/articles/6344318-collections-page#h_c1e1a2a402).

## 6. **Domains**

You can request that a domain is added to your organization. If a domain has been registered with your organization the option "add from domain" will appear on the users page of your organization in the [organization tool](http://hub.catenda.com/orgs). This will let you add users from your organization to your projects without having to invite them through [email invitations](https://support.catenda.com/en/articles/4670319-how-can-i-invite-a-member). If you do not find a user from your organization this will most likely be because they have not made a Catenda account yet and we do not have them in our system. Users from your domain that do not have accounts yet will have to be [invited](https://support.catenda.com/en/articles/4670319-how-can-i-invite-a-member) the regular way so they can join the project and make an account. Users from domains that have not been added will still have to be invited with the regular [email invitation](https://support.catenda.com/en/articles/4670319-how-can-i-invite-a-member).
