# Microsoft Teams notifications

> Stay updated without switching tabs. Connect Catenda Hub to Microsoft Teams to receive real-time notifications directly in your preferred channels.

Receive real-time notifications from a Catenda account directly in a Microsoft Teams channel by configuring a Microsoft Teams Workflow in the Catenda notification settings. _Access required:_ A **Microsoft Teams** account with channel creation and Microsoft Teams workflow management permissions.

The Microsoft Teams notification tab can be found towards the top of the [account notification settings page](https://support.catenda.com/en/articles/8272435-account-notification-settings) that is a sub-page to the [account notifications page](https://support.catenda.com/en/articles/7439223-account-notifications-page):

![Catenda Hub Notification settings Microsoft Teams notificaitons Projects with own Teams settings](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/01-intro.png)

This is what Catenda notifications can look like in Microsoft Teams after a Microsoft Teams workflow has been configured.

![Microsoft Teams channel Posts REady for review created a new topic a new revision was imported in model](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/02-intro.png)

---

### Step 1: Prepare a dedicated channel

Users can organize their project updates by creating a specific space for Catenda notifications. 1\. In **Microsoft Teams**, select the **Teams** or **Chat** tab. 2\. Use an existing team (skip this step) or **create a team**.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/03-step-1-prepare-a-dedicated-channel.png)

Enter a name and create the team.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/04-step-1-prepare-a-dedicated-channel.png)

When a team is created a channel called general is automatically added. 3\. Use an existing channel (skip this step) or add a channel. Richt click a team and select Add channel in the action menu or click on the team and click on **Add channel** towards the top right. _Access required:_ Owner or member of team.

![Microsoft teams Catenda Integration Chat Channels Add channel Members Analytics Apps Tags Hidae all channels Add member Manage team Manage tags Copy link Leave team](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/05-step-1-prepare-a-dedicated-channel.png)

> **Note:** With guest or external access channels cannot be created. In this case, please ask a channel administrator to provide you with a url for notifications to be sent to a channel.

After clicking on Create channel the Create a channel dialogue appears:

![Create a channel Channel name Letters, numbers and spaces are allowed Description Choose a channel type Standard Private Threads Posts](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/06-step-1-prepare-a-dedicated-channel.png)

**4. Name your channel**: Use something clear like "Catenda notifications" or "Project-A-Notifications".

**5. Choose Privacy**: Catenda notifications can be delivered to both standard and private channels.

- Select **Standard** if you want the whole team to see the updates.
- Select **Private** if the notifications are only for you or a specific group.

6\. Click **Create**.

---

### Step 2: Generate your Teams Webhook URL

In the past Catenda Teams Notifications were configured through a Webhook Connector application that was configured for the channel. The Webhook Connector application has since been discontinued. The current way to create a webhook URL is by creating a Microsoft Teams workflow.

Follow these steps to create a new Microsoft Teams **Workflow** webhook. 1\. Open **Microsoft Teams** 2\. Hover over the desired team and click on the three dots or click on the three dots on the top right after having opened the channel. 3\. Select Microsoft Teams **Workflows** from the action menu

<img alt="Microsoft Teams channel action menu, Workflows highlighted." src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-f533eea19d48.png" width="290"/>  \<---> <img alt="Action menu in Microsoft Teams channel, Workflows highlighted." src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-1a6a43fe9eec.png" width="290"/>

4\. Search for **"Send webhook alerts to a channel"** and select it.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/07-step-2-generate-your-teams-webhook-url.png)

5\. Follow the setup steps to select your Team and Channel. **6. Copy the URL**: Once the Microsoft Teams workflow is created, copy the generated webhook URL to your clipboard by clicking on Copy webhook link towards the top.

> **Note:** 💡**Tip**: Keep this URL private. Anyone with this link can send messages to your Teams channel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/08-step-2-generate-your-teams-webhook-url.png)

---

### Step 3: Connect to Catenda Hub

Follow these steps to configure the webhook link in Catenda. This way Catenda knows where to send the project notifications.

1. Log into **Catenda Hub**.
1. Navigate to your **Notifications>Settings** (Account-level or Project-level).
1. Select "Microsoft Teams" tab and scroll all the way to the bottom.
1. Paste your copied URL into the **Webhook URL** field.
1. Click **Save**.

    <div class="intercom-container intercom-align-center"><img height="320" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-a60f9c2dbac8.png" style="height: auto;" width="500"/></div>

1. **Enable Notifications**: Ensure the toggle at the top of the page is switched to **On**.
​

    <div class="intercom-container intercom-align-center"><img height="159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-a3e9aa9365d2.png" style="height: auto;" width="500"/></div>

---

### Step 4: Customize Your Alerts

Tailor the information you receive to avoid notification fatigue. 1\. In the same **Notifications Settings** menu, scroll through the list of notification types. **2. Check the boxes** for the specific updates you want to receive in your Teams channel. This is what the Microsoft Teams notifications menu can look like:

![Choose which notificaitons you would like to receive Catenda Hub Email Microsoft Teams notifications Tropics Documents Approvals Collections Models Users A new topic is created aA topic is assigned to me A topic is mentioning me or my Teams New comment in a topic assigned to me mentioned by me followed by me Status changed in a topic Type changed in a topics I am set as the publisher in an approval request A team I am member of is set as the publisher in an approval request An approval request is closed A member of the submitter team A new approval request has been submitted A document has been discarded An approval request is closed A new approval request has been submitted A new approval request has been assigned to my team A new approval request is ready for review by my team All reviews have been submitted by my team aA document has been discarded An approval request is closed As member of the review team for the final approval A new approval requesthas been submitted A new approval request has been assigned to my team A new approval reqeust is ready for review by my team All reviews have been submitted by my team All reviews have been submitted by my team A review step has been completed A document has been discarded An approval request is closed A new models is created A new revision is imported.](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/09-step-4-customize-your-alerts.png)

Grayed out notifications boxes are disabled for Microsoft teams and are only available for other notification methods. Notification boxes for approvals become available if Shared revisions are enabled in [document settings](https://support.catenda.com/en/articles/7831371-document-settings-page) of a project.

---

### Step 5: Verification

Make sure a notification is sent to your account that is also sent to Microsoft teams.

1\. Perform an action in Catenda Hub.

> **Warning:** ⚠️ **Note:** Not every notification is available to be sent to Microsoft Teams and Microsoft Teams notifications are generally not sent for actions users perform themselves. Upload a model or ask a teammate to create a topic or mention you in a description or comment to verify the link.

2\. Check your **Microsoft Teams Channel**. 3\. A message should appear instantly via the Microsoft Teams **Workflow** bot.
