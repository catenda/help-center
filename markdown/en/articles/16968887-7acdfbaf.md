# Archive Systems and Project Numbers in the Archiving Portal

> Which external archive system the portal submits to, and which project-numbering scheme it records.

The other Archiving Portal articles describe the archive system and the project number in general terms, because what sits behind them depends on the organization. This article names what the portal currently supports.

## 1. **The archive system: WebSak+**

The portal submits to **WebSak+**, the archive system supplied by **Acos**.

A submission does not go directly into WebSak+. The portal assembles the item's metadata as XML and hands it to Acos's submission service, which performs the archiving. The reference that service returns is what the **Archived** tab shows under **ACOS Ref**, so quote it when you need to ask about one specific archived item.

This is also why the failure reasons on the **Archived** tab are phrased as limits of the receiving archive: at most 50 files and at most 2300 MB per submission.

## 2. **Project numbering: Agresso**

The **Project number** in **Settings** is an **Agresso project number**, 8 characters long.

> **Important:** The number is entered in the portal because it is the number registered against the project in WebSak+. There is no connection between the Archiving Portal and Agresso itself. Nothing is read from or written to Agresso, and no validation is performed against it, so enter the number carefully. The portal cannot tell you it is wrong.

## 3. **Everything else**

The portal is built for openBIM project data in Catenda Hub, so the documents and Topics it offers come from Catenda Hub and nowhere else.

For getting project data out of Catenda Hub in other ways, including exports, long-term formats and the frozen archive option, see [Exporting all project data](https://support.catenda.com/en/articles/7946690-exporting-all-project-data).
