# Feature statuses Q4 2026

To prevent notification spam and to ensure a smooth launch, new behavior or changes to existing behavior can be rolled out gradually and without notice. Those that notice changes in behavior of a part of a page they use frequently or those that wonder what is new can consult these articles for updates on recent changes in behavior for all users.

## 1. **New features**

Each user uses the platform differently. Even if a new feature is released or changes are made to a feature it could be that users might not be using that part of the feature. For those that are curious what "that new button" or "that new page" is on the platform this article contains an introduction of what the change is about. For these features often only basic or slightly outdated support material is available as this gets updated as we go. Along with helping people out in support the articles often get updated and if questions that were asked can quickly be found explained in an article the next week.

### 1.1 **Drawings in 3D**

PDF drawings can now be shown in the [3D viewer](https://support.catenda.com/en/articles/8227211-3d-viewer), in place together with the models. A drawing is aligned once, and from then on it can be opened in 3D as often as needed.

![A PDF drawing shown under the model in the 3D viewer, with the 3D button in the viewer column of the documents table](https://raw.githubusercontent.com/catenda/help-center/main/images/0j3jpvac/01-drawings-in-3d.png)

**Aligning a drawing** Select a single PDF in the documents table on the [documents page](https://support.catenda.com/en/articles/8204673-documents-page) and choose Create drawing in the action menu at the top of the table. Give the drawing an elevation, then place the markers A and B to set its position and rotation. This works the same way as in the [storey configurator](https://support.catenda.com/en/articles/6921756-storey-configurator-page). It lines the drawing up with a storey from the storey configurator or from an IFC model.

**Opening drawings in 3D** Select one or more aligned drawings and choose 3D in the action menu at the top of the documents table. The 3D view of a single aligned drawing can also be turned on and off with the 3D button in the [viewer column](https://support.catenda.com/en/articles/8204673-documents-page#h_face62c318). If the viewer column is not visible, show it first, as described in [Columns on the documents page](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page). The drawings loaded in the 3D viewer are listed in the model dropdown at the top, in the same way as point clouds and GML files. Drawings in 3D works with PDF files. 📽️ **[Tutorial video](https://eu.guidde.com/playbooks/devAaKxijzjkFmKW8xcgLq?mode=videoAndDoc)**

### 1.2 **Accessibility**

**Keyboard and screen reader** Catenda Hub can now be used with a keyboard alone and with a screen reader. A skip to main content link and the F6 key move between the main areas of the screen, and a visible outline shows where the focus is. Topics, documents, approvals and models all work by keyboard and screen reader, including tables, forms, pop-ups, the 3D viewer and the PDF viewer. Buttons that only show an icon now have names that a screen reader reads out, in the user's [interface language](https://support.catenda.com/en/articles/4670248-changing-the-preferred-language). Error and success messages are read out as well.

**Color-blind modes** Three color-blind modes can be chosen under Color vision on the [account page](https://support.catenda.com/en/articles/6880968-account-page): protanopia, deuteranopia and tritanopia. Each mode uses a color palette that is easier to tell apart, and Standard keeps the default colors.

![The Color vision setting with the Standard, Protanopia, Deuteranopia and Tritanopia palettes](https://raw.githubusercontent.com/catenda/help-center/main/images/0j3jpvac/02-accessibility.png)

## 2. **Updated features**

### 2.1 **Approval improvements**

**Clickable approval steps** The steps in the [step ribbon](https://support.catenda.com/en/articles/12495212-step-ribbon-in-an-approval-request) at the top of an approval can now be clicked. Clicking a step shows its status, its reviewer teams and its dates. The current step keeps its green outline, so it stays clear where the review actually is.

**Closed legacy approvals after switching** Projects that switched from the legacy approvals to the new approval workflow can now see their closed legacy approvals on the [approvals page](https://support.catenda.com/en/articles/12495047-approvals-page). The documentation and the audit trail of those approvals stay intact after the switch.

### 2.2 **Shared revisions in collections**

[Collections](https://support.catenda.com/en/articles/6344318-collections-page) now support shared revisions. This was a long-standing request from users, and it widens what collections can be used for.

### 2.3 **Catenda AI Connect**

Catenda AI Connect has been updated, and the changes are listed in the [Catenda AI Connect changelog](https://support.catenda.com/en/articles/17778717-catenda-ai-connect-changelog) _(AI Connect customers only)_.

### 2.4 **3D viewer**

**Performance** A new version of the 3D viewer loads models faster and uses less memory, especially while loading. This makes it possible to open larger projects than before. The measurement tools respond faster and freeze less on large projects. Models stay sharp at any browser zoom level. The display quality settings in the [3D viewer settings](https://support.catenda.com/en/articles/5784718-3d-viewer-settings) have been renamed and work differently. The default is now Adaptive quality.

**Alignments** From the alignment table, the [clipping plane](https://support.catenda.com/en/articles/4670253-clipping-planes) can now be sent straight to a point on an [alignment](https://support.catenda.com/en/articles/4670327-sliding-plane-dropdown). There is no longer a need to create a plane and drag it into place by hand. The exact distance along the alignment where the cross section sits is shown as well. Entering a distance moves the cross section straight to it.

**Public bookmarks** The measurement tool and the [clipping plane](https://support.catenda.com/en/articles/4670253-clipping-planes) can now be used in [public bookmarks](https://support.catenda.com/en/articles/8471481-bookmark-contents-page).

### 2.5 **Document viewer languages**

The [document viewer](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations) now follows the [interface language](https://support.catenda.com/en/articles/4670248-changing-the-preferred-language) set in the user account, in every supported language.

### 2.6 **Notifications**

The [account notifications page](https://support.catenda.com/en/articles/7439223-account-notifications-page), the [project notifications page](https://support.catenda.com/en/articles/4670295-project-notifications-page) and the pop-up that opens from the bell in the top right corner have been rebuilt.

## 3. **Enabling on-demand features**

Each on-demand feature is production-grade and ready for real project use. While these features have been tested to work as they should there can be varying degrees as to how many projects have started using these features so unknown edge-cases might be found. While changes might happen as we work to make these features available to all users data that is submitted in these features will not be deleted.

### 3.1 **Requesting for on-demand features to be enabled**

Some features can be requested to be enabled for existing projects by the contact person for your Catenda license while others can be enabled with a setting in the project. When an on-demand feature is requested to be enabled, a meeting will be set up with a support representative to discuss the current status of the feature. If a project is not already available where the on-demand feature can be tested a dummy project can be created for a limited time where the on-demand feature can be tested to consider if the feature is ready to be used.

### 3.2 **Report editor**

Create report templates for topics and documents so project members can select topics or documents from the table and use the report action to generate a report. The reports page is an on-demand feature that can be requested to be enabled for ongoing projects. New projects that are created based on a template project where this feature is enabled do not have this feature enabled. Separate templates can be created for topics and documents. Reports can also be created from approvals with the [create report action](https://support.catenda.com/en/articles/13973721-create-report-action) _(report editor customers only)_. When a template is available in a project the report action can be used with selected topics and documents to generate a report based on the selected template. Support for how different values can be displayed on the page is offered by Catenda. If you would like a custom report tailored to your company we can get you in contact with a consultant that can help with this. Sample reports for topics, documents and approvals are now available in [Ready-made report templates](https://support.catenda.com/en/articles/17778911-ready-made-report-templates) _(report editor customers only)_. How the report editor works is described in [Report editor](https://support.catenda.com/en/articles/17778656-report-editor) _(report editor customers only)_.

### 3.3 **Catenda for Power BI (On Demand)**

An on-demand version of Catenda for Power BI is now available. It can be requested in the same way as the other on-demand features. What it is for is described in [Introduction to Catenda for Power BI (On Demand)](https://support.catenda.com/en/articles/17778865-introduction-to-catenda-for-power-bi-on-demand) _(signed-in customers only)_. Setting it up is described in [Catenda for Power BI (On Demand)](https://support.catenda.com/en/articles/17778868-catenda-for-power-bi-on-demand) _(on request only)_.

### 3.4 **Catenda Desktop Connector for System Images (On Demand)**

An on-demand version of the Catenda Desktop Connector for System Images is now available. It can be requested in the same way as the other on-demand features. What it is for is described in [Introduction to Catenda Desktop Connector for System Images](https://support.catenda.com/en/articles/17778688-introduction-to-catenda-desktop-connector-for-system-images) _(signed-in customers only)_. Setting it up is described in [Catenda Desktop Connector for System Images (On Demand)](https://support.catenda.com/en/articles/17778690-catenda-desktop-connector-for-system-images-on-demand) _(on request only)_.

## 4. **Co-creation program**

Some features are built together with a small group of customers while they are still in development. These customers take part in the Co-creation program: they use the feature in their own projects and their feedback shapes what it becomes.

A co-creation feature is different from an on-demand feature. An on-demand feature is production-grade and only waiting to be made available to all users, while a co-creation feature is not final yet. Pages and buttons can be moved, renamed or replaced from one version to the next, and the articles that describe them are updated as the feature changes. A co-creation feature will be a paid feature once it is released in full.

### 4.1 **Joining the Co-creation program**

The contact person for your Catenda license can ask to join the Co-creation program. A meeting will be set up with a Catenda representative to discuss the current status of the feature and what taking part in the program involves.

### 4.2 **Catenda Mobile**

[Catenda Mobile](https://support.catenda.com/en/articles/17601630-download-your-mobile-app-catenda) is a new mobile app for phones and tablets, available in early access for iPhone and iPad through TestFlight and for Android on Google Play. It covers topics, locations, forms and documents, and over time it will get all the features of [Catenda Site](https://support.catenda.com/en/articles/6530821-download-your-mobile-app-catenda-site), and more. Topics and documents work in every project the user is a member of. Forms and locations can only be used in projects where they have been turned on, and for now that is only the projects of customers in the Co-creation program.

The app is not final and may still change considerably. Catenda Site can still be used alongside it, and remains the app to use where a feature is needed that is not in Catenda Mobile yet.
