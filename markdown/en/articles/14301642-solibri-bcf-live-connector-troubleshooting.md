# Solibri BCF Live Connector troubleshooting

Errors that can be encountered with the Solibri documents integration and how to solve them are explaind in this article.

## 1. **Support and Troubleshooting**

The BCF Live Connector is developed, maintained, and owned by Solibri. Because this integration is an independent product created by Solibri to connect with the Catenda API, our support is focused on the data exchange rather than the internal mechanics of the Solibri software itself.

### 1.1 **For Workflow & Data Questions**

If you need help understanding how features work within the integration, or how information is represented within Catenda once it has been synced, our team is happy to assist. We can help you navigate the intended workflow and ensure your project data is communicating correctly between the two platforms.

### 1.2 **For Technical & Functional Issues**

If specific error message within the Solibri interface are encountered, if the connector is not responding as expected, or if a change to how the connector functions is wished for please contact **[Solibri Support](https://www.solibri.com/support)** directly. As the developers and owners of the connector, they are the only ones who can modify the underlying code, adjust internal validation rules, or troubleshoot software-specific bugs.

## 2. **Duplicate model**

When this is encountered error, it is typically because the Solibri connector has identified two models sharing the same IFCProject GUID.

### 2.1 **Names vs. IDs**

Catenda and the Solibri connector identify models based on their unique GUID, not their filename.

If two different files in your Solibri Selection Basket were exported from the same original file in your authoring tool (e.g., Revit, ArchiCAD), they will likely share the same IFCProject GUID.

Even these files are given different names in Solibri, the connector recognizes them as the same entity and triggers a "Duplicate" warning to prevent data synchronization conflicts.

### 2.2 **How to Verify the GUID in Solibri**

To confirm if your models share the same identifier, check the metadata directly within Solibri:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ym9bebpy/01-how-to-verify-the-guid-in-solibri.png)

1. Select the **Model** in the Solibri Model Tree.
1. Open the **Info Tool** or the **Identity** tab.
1. Locate the **IFCProject GUID** field.

If two models show the same string of characters here, the connector will treat them as the same model.
