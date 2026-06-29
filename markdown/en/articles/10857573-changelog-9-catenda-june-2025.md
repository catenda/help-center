# Changelog 9 Catenda - June, 2025

Hello everyone,

As always we have been hard at work, but especially in the months leading up to the summer this is a busy time for us as this is when our developers are getting the product ready for the changes that lie in wait for you after the summer vacation!

Something new that not everyone may have noticed is that we have made our first step into the GIS world. Ask an administrator to re-configure your project locaiton and see a a map with the buildings surrounding your project appear in the 2D viewer!

After it was discovered that the new status workflow could not be released unless some other features were in place many of you have been waiting for the official release of the ISO 19650 workflow. Many of you have been testing the new workspace and published tabs with shared revisions already but keep an eye on changes in your test projects as you soon will be able to try out the complete approval system as we are getting closer to release. For those that do not have access to a test project, please ask and we will set one up for you.

With that I wish you all a happy holidays and would like to remind you to apply plenty of sunscreen when going to the beach! 🏖️⛱️🩴🍦🍧🍨☀️😎🌞

## 1. **Articles**

As new features roll out and bugs are fixed articles are updated with the changes that are made. Please find the following articles that have been made and changed since the last changelog.

### 1.1 **New articles:**

**Product Features** [Document preview tools](https://support.catenda.com/en/articles/11384618-document-preview-tools) [Milestone page](https://support.catenda.com/en/articles/11376858-milestone-page)

**Troubleshooting** [Sign-in and Passwords](https://support.catenda.com/en/articles/10798891-sign-in-and-passwords) [Desktop Connector Troubleshooting](https://support.catenda.com/en/articles/11019637-desktop-connector-troubleshooting) [Zip upload troubleshooting](https://support.catenda.com/en/articles/11017391-zip-upload-troubleshooting) [2D viewer buildings and storeys](https://support.catenda.com/en/articles/10901703-2d-viewer-buildings-and-storeys) [Upload document dialogue troubleshooting](https://support.catenda.com/en/articles/11070748-upload-document-dialogue-troubleshooting) [Solibri Documents Integration Troubleshooting](https://support.catenda.com/en/articles/11431097-solibri-documents-integration-troubleshooting)

**Tutorials and guides** [Guidde videos](https://support.catenda.com/en/articles/11055278-guidde-videos)

**Frequently Asked Questions** [Saving a filter link](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) [Catenda Desktop Connector FAQ](https://support.catenda.com/en/articles/11582835-catenda-desktop-connector-faq)

### 1.2 **Articles that have changed:**

**Product Features**

- Models
    - [Models page actions](https://support.catenda.com/en/articles/9431936-models-page-actions)
    - [Model overview page actions](https://support.catenda.com/en/articles/9674157-model-overview-page-actions)
    - [Quanitity Take Off (QTO)](https://support.catenda.com/en/articles/6673929-quantity-take-off-qto)
- Topics
    - [Milestones page](https://support.catenda.com/en/articles/4670266-milestones-page)
- Documents
    - [Right menu of a revision - Revision info](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision-revision-info)
    - [Document structure actions](https://support.catenda.com/en/articles/4670288-document-structure-actions)
    - [Document revision actions](https://support.catenda.com/en/articles/9323521-document-revision-actions)
    - [Document preview and annotations](https://app.intercom.com/a/apps/areracg3/knowledge-hub/all-content?activeContentId=4496538&activeContentType=article&editorMode=view&search=document%20preview)
    - [Columns on the documents page](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page)
    - [Revision publishing - ISO 19650](https://support.catenda.com/en/articles/9874698-revision-publishing-iso-19650)
    - [Upload a zip/file structure](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure)
    - [Collections page](https://support.catenda.com/en/articles/6344318-collections-page)
- Project setings
    - [Project settings page](https://support.catenda.com/en/articles/4670273-project-settings-page)
    - [Custom fields page](https://support.catenda.com/en/articles/6550459-custom-fields-page)
    - [Members page](https://support.catenda.com/en/articles/4670291-members-page)
- 2D & 3D Viewers
    - [3D viewer tool menu](https://support.catenda.com/en/articles/4670294-3d-viewer-tool-menu)
    - [3D viewer](https://support.catenda.com/en/articles/8227211-3d-viewer)
    - [Revision Selector](https://support.catenda.com/en/articles/4670279-revision-selector)
    - [Point Clouds in Catenda Hub](https://support.catenda.com/en/articles/5606625-point-clouds-in-catenda-hub)
- Catenda Plugins and integrations
    - [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector)
    - [Topics menu - Catenda Site](https://support.catenda.com/en/articles/7734073-topics-menu-catenda-site)
    - [Solibri Models and Documents integration](https://support.catenda.com/en/articles/6988148-solibri-models-and-documents-integration)

**Troubleshooting** [Hardware recommendation](https://support.catenda.com/en/articles/6921941-hardware-recommendation) [Why am I not receiving emails?](https://support.catenda.com/en/articles/8417802-why-am-i-not-receiving-emails) [Support button location and functionality](https://support.catenda.com/en/articles/8894066-support-button-location-and-functionality)

**Frequently Asked Questions** [Project security](https://support.catenda.com/en/articles/8263256-project-security)

Recent updates [Models as documents](https://support.catenda.com/en/articles/8064548-models-as-documents)

## 2. **Bugs Resolved**

Thanks to your valuable feedback we have been able to squash many topics that you may or may not have noticed existed. Below is a list of smaller changes that have been made by the development team as a result of conversations with users.

### 2.1 **Performance**

Performance degradation was noticed during 17-28 April. This, after we had just worked on speeding up the platform the month before. Investigation resulted in a problem discovery which implacted all incoming request to Catenda Hub. Resolving this problem made Catenda Hub faster to work with, especially when many people attempt to perform many tasks at once:

- 5x faster during lesser activity
    - When: Half of the time during 09:00-17:00 CET and nights.
    - Percieved speed: Slower than when there is no activity at all but it should feel a tiny little bit faster than it used to as the lesser activity is still making things slower.
- 250x faster during regular activity
    - When: Half of the time during 09:00-17:00 CET
    - Percieved speed: Slower than when there is lesser activity but noticably faster than it used to be during regular activity.
- 5000x faster during high activity
    - When: In the case where there is the most amount of useage.
    - Percieved speed: Slower than when there is regular activity but night and day compared to when there used to be high activity.

### 2.2 **Documents**

- The right person that deleted a document is once again displayed in email notifications
- It is once again possible to add selected shared revisions to approvals from the right information menu.
- With the latest version of the document preview in Catenda it is now possible to follow links in excel documents that get uploaded to Catenda to the right hyperlink location.
- When you create a label, the list of labels you have access to is now refreshed.
This means that you will no longer have to reload the page to apply a newly created label other places and can do it without refreshing the page.
- Annotations on some pages of uploaded documents are once again visible.
This allows you to properly download the document with all its annotations.
New annotations will also not be see through as this will not happen anymore.
- The link buttons now now no longer infinitely spin when you have the content and 3D panels open and have only a folder selected.
- It is now possible to filter on dates with the date filter of documents in sub-folders as well as the folder you are currently in
- Screenshots included when saving markups as new topics or to comments can now have larger file sizes. This makes it so you can submit your markups, even when you have created annotations when zoomed in on highly detailed drawings.
- When printing documents from the documents viewer, the documents are once again in high resolution instead of a rasterised pixelated version.
- It is once again possible to add documents to collections with the add documents button without the page going white.

### 2.3 **Models**

- When the latest model has failed importing you open the last successfully imported revision in 3D when clicking on the 3D button on the models page. 
That revision will now properly be displayed in the revision selector instead of the latest failed revision.
- When enabling a grid some models that were previously enabled in the 3D viewer will now no longer turn on.
- Some grids are now no longer offset verticaly.
- Table elements in the second selection of the objects function are now properly highlighted.
- It is once again possible to scroll in the Trees, and Information panels.

### 2.4 **Plugins and integrations**

- The Revit plugin login window is no longer cropped in some situations

## 3. **New videos in playlists**

- Getting started
    - [Video - User onboarding & support](https://eu.guidde.com/share/playlists/gL4N5E4aGEYqk3nojjPpq7?track_link_name=Intercom&track_link_id=vrc3txAqpnzG21ahEDofSs&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Connect to Catenda Hub](https://eu.guidde.com/share/playbooks/sAJ9zHv65kinzKseJPmNQm?track_link_name=Changelog&track_link_id=nQAaRkkuJwtN2my3y8ZNSK&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Account Settings and Notifications](https://eu.guidde.com/share/playbooks/6cAvR5y6ugZsAShAwPLL6f?track_link_name=Changelog&track_link_id=4PcBgdUq2XeCAyaHp4Surf&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Add members and create teams in Catenda Hub](https://eu.guidde.com/share/playbooks/32n43rhyPM5WkmCNZZ3Smf?track_link_name=Changelog&track_link_id=4nEH9C2PJeTvYuuoXRtEYe&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Contact Support and Access documentation](https://eu.guidde.com/share/playbooks/bQFS6LFyFckyhNwY3LnXGJ?track_link_name=Changelog&track_link_id=feEe6eFALATtc4tHkuhKYR&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
    - [Video - Project navigation](https://eu.guidde.com/share/playlists/raHoQ3qwoDbNx18S5YZtDv?track_link_name=Intercom&track_link_id=rHg8xpibRQegGuksgmT5nA&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Hub dashboard](https://eu.guidde.com/share/playbooks/jTzRJEtpD8KZ7BjpKcd1Zw?track_link_name=Changelog&track_link_id=fVJrXGLsuTBxE43RZ3MBs2&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Navigate the project folders](https://eu.guidde.com/share/playbooks/tzd39Q3NFqKTTVHodFQpJr?track_link_name=Changelog&track_link_id=vssrsCNc1tQz49b4J7RqnQ&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Opening 3D documents](https://Opening%203D%20documents)
    - [Video - Content management](https://eu.guidde.com/share/playlists/v2QNmY2iHDMVZd96ePzVQ7?track_link_name=Intercom&track_link_id=khM8GzpkYf6nta8Y46UGED&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Upload content and create models from IFC](https://eu.guidde.com/share/playbooks/9fgGi4DqpchSDqcy1WEY8n?track_link_name=Changelog&track_link_id=wBvEL6SVQmQgVLAwF1DgAF&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Create, assign and manage topics](https://eu.guidde.com/share/playbooks/vRYbidpKvH49HzfhbKh8z6?track_link_name=Changelog&track_link_id=sBPtoFQcnCkfMn8Kd7i4zy&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Export Topics](https://eu.guidde.com/share/playbooks/tjNgrqvUfKreqJqXrWKUQw?track_link_name=Changelog&track_link_id=qEVCnwTYQNETuKNF4YF45Q&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
    - [Video - Project setup](https://eu.guidde.com/share/playlists/9EG9WZEd2UiGMPZVVQfHuR?track_link_name=Intercom&track_link_id=ouZFRWrWkT82un7JZcNcZD&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Add folders and subfolders](https://eu.guidde.com/share/playbooks/o7pDsqiQCKPyTGBLifxKgE?track_link_name=Changelog&track_link_id=cV899DSepqVheMCwSroRSt&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Create and share a collection](https://eu.guidde.com/share/playbooks/rcTnM584AAZPy6APbGyQS9?track_link_name=Changelog&track_link_id=eBp853v7gRvCsu9L2h5Ht2&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Create and add labels](https://eu.guidde.com/share/playbooks/ibD5KfuW1XNvGYuDPUFeiT?track_link_name=Changelog&track_link_id=asuMNTs82hbfQhwZCinqZi&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
- Product features
    - [Link sharing](https://eu.guidde.com/share/playbooks/1Z3cf5Rjbvgkv5Lfq2mLex?track_link_name=Changelog&track_link_id=gpwRmqmraYWC9J4maVZZPz&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
    - [Move content](https://eu.guidde.com/share/playbooks/czZ43xf7ncVH7M18yUZoCC?track_link_name=Changelog&track_link_id=qZUkeSsyHcj98hWGM2Wwd1&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
    - [Download content](https://eu.guidde.com/share/playbooks/naxhWxhmKhkt5cYbY6iMMj?track_link_name=Changelog&track_link_id=5WE2WuHetNNcjKdaqciDAi&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
    - Topics
        - [Showing topic history](https://eu.guidde.com/share/playbooks/vc9qXCxWe47hbvtGjtn8rJ?track_link_name=Changelog&track_link_id=n1Bfij4G5CNWTXGzaLNMcY&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
    - Documents
        - [Annotate a document with the markup function](https://eu.guidde.com/share/playbooks/oHGeYhjqug4yKLUywvSTMP?track_link_name=Changelog&track_link_id=3GDPP7qo2TJ3hsNM4xi4QP&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Compare two revisions of a PDF file](https://eu.guidde.com/share/playbooks/oHGeYhjqug4yKLUywvSTMP?track_link_name=Changelog&track_link_id=3GDPP7qo2TJ3hsNM4xi4QP&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [How to set up a naming convention](https://eu.guidde.com/share/playbooks/gvmH5vCYdrmxz7gHhosVEr?track_link_name=Guidde%20videos%20article&track_link_id=cmU3oSHd7meH6G99TjUYGm&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Visualizing a document](https://eu.guidde.com/share/playbooks/g7G5vfKW7K29MhYUzkXdZX?track_link_name=Changelog&track_link_id=wHtAfxXfoVEjWZePMqTfcA&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Validation workflow (draft mode)](https://eu.guidde.com/share/playbooks/kDbhPXwcvGtRRjhdLjUDV1?track_link_name=Changelog&track_link_id=8F4Coqk2VZpzy56xCUZKHa&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
    - Libraries
        - [Library: Import CSV classification](https://eu.guidde.com/share/playbooks/kDbhPXwcvGtRRjhdLjUDV1?track_link_name=Changelog&track_link_id=8F4Coqk2VZpzy56xCUZKHa&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
        - [Catenda Hub - Classification Library, Planning example](https://eu.guidde.com/share/playbooks/kDbhPXwcvGtRRjhdLjUDV1?track_link_name=Changelog&track_link_id=8F4Coqk2VZpzy56xCUZKHa&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)
    - Catenda Plugins and integrations
        - [Catenda Sharepoint App (Webpart)](https://eu.guidde.com/share/playbooks/4yFopCgQCynxpKw9fGYqJ5?track_link_name=Guidde%20videos%20article&track_link_id=qPkRg1v5PVS2jwdonBoreg&origin=7PqdD6oPp9QLchKHNkCwDH3opRS2)

## 4. **User voices completed**

### 4.1 **Documents**

Showing shared revisions through the API I.E Catenda Site, Solibri With the new status workflow it is now possible to show major and minor revisions in external applications.

## 5. **New releases** - Plugins and integrations

_Catenda Desktop Connector - v1.0.6.0_ Files that are in use by another program or synchronisation serivce will now properly be uploaded. (This means that the Desktop Connector now works together with online-only files from other synchronization services!) Files bigger than 2GB can now be downloaded.

_Revit plugin - v1.0.1.13 Beta_ When you type @ in a comment or description you now get a list of members you can choose from so you can select which one you want to mention. Support for Revit 2026 The beta version is only available per request.

**Navisworks plugin - v1.6.0** Support NW 2026
