# Microsoft Teams Notifications Troubleshooting

In this article information about the errors that can occur when configuring Microsoft Teams notifications with Catenda via Microsoft Teams Workflows can be found.

This article contains information about the following topics: [No notifications](#h_42fb432d1c)

## 1. **No notifications in Microsoft Teams channel**

If a Microsoft Teams Workflow URL has been configured in Catenda and a Catenda notification for one of the notification boxes that are checked in the Microsoft Teams tab of notificaiton settings has been received but there is no message in the Microsoft Teams channel that has been configured there is likely a problem with the Microsoft Teams Workflow.

To see if something has gone wrong with the Microsoft Teams Workflow select Workflows either by hovering over the channel and clicking on the three dots or by clicking on the three dots on the top right of a channel.

<img alt="Microsoft Teams channel action menu, Workflows highlighted." src="https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/inline-f533eea19d48.png" width="290"/>  \<---> <img alt="Action menu in Microsoft Teams channel, Workflows highlighted." src="https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/inline-1a6a43fe9eec.png" width="290"/>

If Something is wrong with the workflow an error can be displayed in the Send webhook alerts to a channel workflow in the Your wokflows menu.

![Microsoft Teams A connection issue has occurred that needs you attention](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/01-no-notifications-in-microsoft-teams-channel.png)

An error can be: `A connection issue has occurred that needs you attention`

Click on the workflow to open the workflow in the preferred browser or click on details to see more information in Microsoft Teams. This is what the details of the Webhook workflow can look like in Microsoft Teams when there is an error.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/02-no-notifications-in-microsoft-teams-channel.png)

Here the time and date the error occurred can be seen. Click on the time and date of the failure to open up the workflow in Power Automate in the preferred browser. This is what the failure can look like in Power Automate:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/03-no-notifications-in-microsoft-teams-channel.png)

The alert in Power Automate gives us some more indication about what could be wrong. In this case the following error message has appeared:

`Alert: Your \<email> connection isn't working: Looks like your flow's \<email> connection needs to be signed-in again. The most common cause is a changed password or a policy set by your tenant administrator. Connections may also require reauthentication, if multi-factor authentication has been recently enabled for your account.`

To reauthenticate, click on the workflow in teams and open the workflow in Power Automate. It is also possible to go to the connectione page in Power Automate and establish a connection there.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/04-no-notifications-in-microsoft-teams-channel.png)

In the Action requried dialogue click on reauthenticate. After successfully authenticaitng the connection should show up on the Connections page.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/05-no-notifications-in-microsoft-teams-channel.png)
