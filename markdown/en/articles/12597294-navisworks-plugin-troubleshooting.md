# Navisworks plugin troubleshooting

Errors that can be encountered with the Navisworks plugin and how to solve them are explaind in this article.

## 1. **AddTopic**

When the topics menu is opened without being logged in the following error appears.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/01-addtopic.png)

To solve this, please go to the settings menu and click login on the top right.

## 2. **PopulateIssueBoards**

When there are no topics in one of the projects that a member is part of the following error will appear.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/02-populateissueboards.png)

After a topic is created in the project the error will no longer appear.

## 3. **Resetting the plugin**

After updating Navisworks there could be problems with the installation of the Catenda navisworks plugin. To reset the plugin, please follow the following steps:

Please change first in the Windows folder options to show hidden files and folders

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/03-resetting-the-plugin.jpg)

Then we will find Navisworks application settings from the C:\\Users\\_username\\_AppData\\Local folder. They can be under the Autodesk\_Inc or/and Autodesk\_Ltd folders

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/04-resetting-the-plugin.jpg)

Navisworks settings are located in folders which begin with “Roamer.exe\_Url…“

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/05-resetting-the-plugin.jpg)

We can reset those settings by deleting Roamer.exe\_Url… folder including subfolders and files

To check which plugins the settings belongs to: Next level indicates the version of the Navisworks e.g. 19 is for Navisworks 2022 version, 18 for 2021 version and so on

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/06-resetting-the-plugin.jpg)

Under that folder we can find the actual configuration file _user.config_ which can be opened with text editor. Please note! It is better to delete whole path from the Roamer.exe\_Url level than try to remove individual plugins by using the text editor.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/07-resetting-the-plugin.jpg)
