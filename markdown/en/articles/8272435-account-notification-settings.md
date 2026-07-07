# Account notification settings

The notification settings page can be found as a sub page to the [notifications page](https://hub.catenda.com/notifications). In [notification settings](https://bimsync.com/notifications/settings) it is possible to configure what notifications you receive.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/01-intro.png)

Each tab corresponds to a different method of sending notifications.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/02-intro.png)

The tab you are currently on will be underlined with a green bar.

## 1. **Notification switch**

For each notification method you can completely turn on or off notifications. By default Catenda Hub and email notifications will be on while Slack and Teams notifications will be off. To enable or disable notifications completely for a tab press this switch.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/03-notification-switch.png)

When a notification method has been disabled, the circle next to the tab goes gray.

> **Note:** If you disable email notifications you can receive project invite emails and sharelink emails.

Click the switch again to turn the notifications back on.

## 2. **Notification checkboxes**

For each notification method you can choose which notification types you would like to receive for that method. Click [here](https://support.catenda.com/en/articles/8304417-untitled-article) to see when each type of notification get sent.

## 3. **In-browser notifications**

The Catenda Hub tab will allow you to configure what notifications you receive in the browser. These are the notifications that you see on the [notifications page](https://hub.catenda.com/notifications). When you receive a notification you will see a red number of unread notifications on the notification icon on the top right. When you click on this button the unread notifications badge will disappear.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/04-in-browser-notifications.png)

## 4. **Email notifications**

The email tab will allow you to configure what notifications you receive via email. By default you get sent one email per notification on Catenda Hub. If you change your email notifications you will still get all the notifications on Catenda Hub as you configured [above](#email-notifications)

### 4.1 **Email summary**

With email notifications you can choose to get a daily summary instead.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/05-br-email-summary.png)

Each time a summary gets sent it will contain all notifications that have happened since the last summary.

## 5. **Slack notifications**

The Slack tab will allow you to receive the notifications that have been sent to your account in a slack channel. This notification method is off by default and has to be configured and turned on if you want to use it. You will be able to find the webhook URL setting on the bottom of the tabs page.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/06-slack-notifications.png)

Setting up 'Slack webhook URL' will post Catenda Hub notifications to Slack. To set up, go to ([https://api.slack.com/incoming-webhooks](https://api.slack.com/incoming-webhooks)) and click the link \`incoming webhook integration\`. Choose the channel you want the messages to go to and copy the field \`webhook URL\` into Catenda.

## 6. **Microsoft teams notifications**

The Microsoft Teams tab will allow you to receive the notifications that have been sent to your account in a Microsoft Teams channel. This notification method is off by default and has to be configured and turned on if you want to use it. You will be able to find the webhook URL setting on the bottom of the tabs page.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/07-microsoft-teams-notifications.png)

In your Teams channel, select **"Connectors"** from the main menu. Search for **"Incoming Webhook"** and select **"Configure"**. Set name to Catenda, use **"[https://hub.catenda.com/img/logo-192x192.png](https://hub.catenda.com/img/logo-192x192.png)"** as image and then press **"Create"**.

Copy the URL into the **"Webhook URL"** above. Make sure the notifications are enabled at the top and then check the notification types you want to be sent into the Teams channel

## 7. **Per project notifications**

If you have set any project specific notifications you will be able to see these in the left navigation menu of a project. You can click on the name of the project to get taken to the [project notification settings](https://support.catenda.com/en/articles/4670262-project-notification-settings) for that project. These settings will be specific to you and are not settings for the whole project.
