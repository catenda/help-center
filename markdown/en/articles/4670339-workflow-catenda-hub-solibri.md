# Workflow Catenda Hub - Solibri

This is a document that will explain the optimal workflow when working with the BCF-server between Solibri and Catenda Hub.

1\. Start with connecting with your Catenda Hub project. [( see here )](https://intercom.help/bimsync-arena/en/articles/4670340-solibri-model-checker-and-bimsync-bcf-connection) 2\. When connected, start by running your clash detection in Solibri and create a presentation. There are several ways of creating a presentation in Solibri, But I will explain the best type for communicating with Catenda Hub. A. Run the check with your ruleset. B. Find a Solibri issue you want to add to your presentation. C. Instead of going to communication and adding the slide to your presentation there, right click on the issue in the checking results and press the button “Add slide”. By doing it this way, all objects in that issue will automatically be included in the issue in Catenda Hub and easier to locate. This combined with hide others, make others  translucent in Catenda Hub is a good way of never losing track of which objects are included in the issues. When creating a slide this way, you will still get the same type of issue layout as in communication where you can add a title, add a description, add extra pictures and comments. The same goes for assigning people to the issue.

![Workflow_Solibri_-_Bimsync.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/01-intro.png)

D. When you are done with your checking, go to communication and create a presentation from “checking results”. Then all the issues you created in the checking results will appear in your new presentation. If you want to add these slides to an existing presentation you can right click on that presentation and press “update presentation from results”, this way all the slides created in results will be included in that presentation.

![Workflow_Solibri_-_Bimsync__1_.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/02-intro.png)

3\. Now after you have created the presentation you can start syncing with Catenda Hub. When you press “Synchronize presentation” a pop-up menu appears. In this you can check boxes to decide which way you want to synchronize. If you go to “Value Conversion” you can set different values to match the values in your Catenda Hub project.

![Workflow_Solibri_-_Bimsync__2_.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/03-intro.png)

4\. Value Conversion. If you for example have assigned an issue to a person directly in Solibri and it doesn’t assign the issue in Catenda Hub, the reason is that the value conversion is not set correctly.

![Snag_62f59e4.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/04-intro.png)

These responsibilities set in the issue, can be set to match the users in the Catenda Hub project. This is done in value conversion here:

![Snag_62c9ad3.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/05-intro.png)

The value conversion button appears in the pop-up menu when right clicking the presentation and pressing “Synchronize presentation”. When these issues are assigned in Solibri and synchronized with the Catenda Hub project, the users assigned will receive notifications if the notifications are turned on. This way you don’t have to assign the issues manually in Catenda Hub after syncing with Solibri.
