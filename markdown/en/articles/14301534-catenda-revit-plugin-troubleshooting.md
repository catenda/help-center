# Catenda Revit Plugin Troubleshooting

Errors that can be encountered with the Catenda evit plugin and how to solve them are explaind in this article..

## 1. **Manage Links window**

After installing the Catenda Revit plugin in a Revit 2025 that was updated after March 2026 Revit will crash when attempting to open the Manage Links window. This is due to a change from Autodesk. Click [here](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Program-crash-on-certain-machines-when-opening-the-Manage-Links-dialog-in-Revit.html) for a workaround. Please note that only Revit 2025 is affected. This problem does not exist in Revit 2026.

## 2. **Supported Revit Editions**

The Catenda add-in is compatible with Revit editions that support the Revit API (Application Programming Interface). Integration is possible within the following environments:

**Standard Revit** Full support is provided for the multidisciplinary version of the software, encompassing the **Architecture**, **Structure**, and **MEP** (Mechanical, Electrical, and Plumbing) toolsets.

**Educational Version** Licenses issued for students and educators support the installation of third-party add-ins, provided the installation is the full version of the software and not the LT version.

### 2.1 **Unsupported Edition: Revit LT**

It is important to note that [Revit LT does not support third-party add-ins or plugins](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Revit-LT-Is-it-possible-to-use-plugin-or-addins-in-Revit-LT.html), including the Catenda Revit add-in. This is a limitation of the LT platform's software architecture, as it lacks the required API framework. Consequently, it is not possible to install the add-in or utilize Dynamo-based automation within the Revit LT environment.

### 2.2 **Version Compatibility**

To ensure alignment with the latest software updates and performance enhancements, the integrations are updated regularly. For a comprehensive list of currently supported year-versions for both the Revit add-in and the Dynamo package, **r**eference should be made to the [Plugins and Integrations](https://support.catenda.com/en/articles/8396532-catenda-plugins-integrations) article.

## 3. Catenda Hub Dynamo Package

For workflows requiring custom automation, a specialized package is available for base Dynamo. This is not a separate application but a collection of nodes for use within the standard Dynamo environment.

**Licensing** No additional Autodesk license is required to use Dynamo, as it is included as a core capability within the standard Revit license.

**API Access** Use of this package requires Catenda API access. While this is not included for every client by default, access may be requested through the Catenda support portal. Once granted, API access allows for interactions across all projects within an organization.

**Installation** Deployment of the package requires manual installation by specifying the file location within the Dynamo interface.

### 3.1 **Operational Warning for Dynamo Users**

Before the use of this package begins, a warning is issued that these tools enable actions within a project as if the actor were an application rather than an individual user. With significant capabilities comes significant responsibility. Actions performed at the application level, such as deletions, are processed differently than standard user actions. Elements or data deleted by an application cannot be restored. Extreme caution is urged when utilizing these tools within a project environment. To request API access or the Dynamo package please contact [support@catenda.com](mailto:support@catenda.com) or via the black chat bubble towards the top right of the platform.
