# Projects Page on the Archiving Portal

> Sign in to the Archiving Portal and open a project. Only projects where you are an administrator are listed.

The Archiving Portal lets you archive documents and Topics from Catenda Hub into your organization's external archive system. It is for whoever is responsible for archiving in one or more projects.

Open the portal at [archiving.catenda.com](https://archiving.catenda.com) and click **Connect to Catenda Hub**. The portal has no password of its own, so you authenticate at Catenda Hub and are returned here. For the account itself, see [Sign in page](https://support.catenda.com/en/articles/7891486-sign-in-page).

The projects page can look something like this:

![](https://catenda.github.io/help-center-ops/images/h1mfgfs5/01-intro.png)

## 1. **How archiving works**

Archiving runs in one direction, from Catenda Hub out to your organization's archive system. The portal is where you decide what goes and confirm that it arrived.

### 1.1 **What becomes archivable**

What can be archived is decided in Catenda Hub rather than in the portal. A document becomes archivable when it sits in a folder carrying the archive label, which is the label named `Arkivverdig` unless your project defines its own. Topics become archivable the same way, through their topic board.

The portal keeps its own copy of what is in Catenda Hub and refreshes it roughly every 30 minutes, so something you have just changed there takes a little while to show up here.

### 1.2 **Choosing what goes**

Everything waiting is listed on a project's own page, with documents and Topics on separate tabs. For each item you choose whether to archive it, skip it for now, or never archive it, and you can correct the metadata or add attachments before it goes.

A project number has to be set before anything can be archived, because that is the number the item is registered under in the archive. Until it is set, the portal tells you so instead of archiving.

### 1.3 **Sending, and what comes back**

Sending hands the item to the archive system, which files it and returns a reference. The portal records that reference against the item, so anything archived can be traced back to the copy in the archive.

Anything that fails is recorded with the reason it failed, and can be sent again, either one item at a time or for the whole project at once.

> **Note:** The articles describing each of these steps in detail are only available to users with access to the Archiving Portal. For which archive system the portal submits to, see [Archive Systems and Project Numbers in the Archiving Portal](https://support.catenda.com/en/articles/16968887-archive-systems-and-project-numbers-in-the-archiving-portal).

## 2. **Your projects**

After signing in you land on **Your projects**.

Only projects where you hold administrator rights are listed. If a project you expect is missing, check your rights on it in Catenda Hub rather than in the portal.

Each project is listed with its owner and a count of the documents and Topics currently waiting to be archived.

Click **Manage Archive** on a project to open it. What the project page shows you from there is described in [Project Content Page in the Archiving Portal](https://support.catenda.com/en/articles/16968871-project-content-page-in-the-archiving-portal), which only users with access to the Archiving Portal can read.

> **Note:** The portal works out which projects to show by checking your team memberships. If that check fails it tells you that some projects may not be visible, rather than quietly showing a short list.

## 3. **The controls at the top right**

Three controls sit at the top right, and this page is the first place you meet them. They stay available once you open a project.

**Language** The portal is available in English and Norwegian Bokmål, and the language picker switches between them.

**Statistics** **View Statistics** opens a summary of what has been archived across every project. The icon is only shown to organization owners, and it takes the place of the gear icon that a project page shows. That page is described in [Statistics Page in the Archiving Portal](https://support.catenda.com/en/articles/16968884-statistics-page-in-the-archiving-portal), and the per-project figures in [Project Settings Page in the Archiving Portal](https://support.catenda.com/en/articles/16968883-project-settings-page-in-the-archiving-portal). Both of those articles are only available to users with access to the Archiving Portal.

**Logout** Signs you out of the portal.

> **Note:** The language picker changes the portal's own interface. It does not change the names of the labels you set in Catenda Hub, which stay as they are written there. Even the English interface refers to the archive label by its Norwegian name, `Arkivverdig`.
