# Microsoft Teams Benachrichtigungen – Fehlerbehebung

In diesem Artikel finden Sie Informationen über die Fehler, die bei der Konfiguration von Microsoft Teams Benachrichtigungen mit Catenda über Microsoft Teams Workflows auftreten können.

Dieser Artikel enthält Informationen zu den folgenden Themen: [Keine Benachrichtigungen](#h_42fb432d1c)

## 1. **Keine Benachrichtigungen im Microsoft Teams-Kanal**

Wenn eine Microsoft Teams Workflow-URL in Catenda konfiguriert wurde und eine Catenda-Benachrichtigung für eines der Benachrichtigungsfelder empfangen wurde, die auf der Registerkarte Microsoft Teams in den Benachrichtigungseinstellungen aktiviert sind, aber keine Nachricht im konfigurierten Microsoft Teams-Kanal vorhanden ist, liegt wahrscheinlich ein Problem mit dem Microsoft Teams Workflow vor.

Um zu prüfen, ob etwas mit dem Microsoft Teams Workflow nicht stimmt, wählen Sie Workflows aus, indem Sie entweder über dem Kanal auf die drei Punkte klicken oder auf die drei Punkte oben rechts in einem Kanal klicken.

<img alt="Microsoft Teams-Kanalaktionsmenü, Workflows hervorgehoben." src="https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/inline-f533eea19d48.png" width="290"/>  \<---> <img alt="Aktionsmenü im Microsoft Teams-Kanal, Workflows hervorgehoben." src="https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/inline-1a6a43fe9eec.png" width="290"/>

Wenn etwas mit dem Workflow nicht stimmt, kann ein Fehler im Workflow "Webhook-Warnungen an einen Kanal senden" im Menü "Ihre Workflows" angezeigt werden.

![Microsoft Teams Ein Verbindungsproblem ist aufgetreten, das Ihre Aufmerksamkeit erfordert](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/01-no-notifications-in-microsoft-teams-channel.png)

Ein Fehler kann lauten: `Ein Verbindungsproblem ist aufgetreten, das Ihre Aufmerksamkeit erfordert`

Klicken Sie auf den Workflow, um ihn im bevorzugten Browser zu öffnen, oder klicken Sie auf Details, um weitere Informationen in Microsoft Teams anzuzeigen. Dies ist ein Beispiel für die Details des Webhook-Workflows in Microsoft Teams bei einem Fehler.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/02-no-notifications-in-microsoft-teams-channel.png)

Hier können Sie den Zeitpunkt und das Datum des Fehlers sehen. Klicken Sie auf den Zeitpunkt und das Datum des Fehlers, um den Workflow in Power Automate im bevorzugten Browser zu öffnen. Dies ist ein Beispiel für den Fehler in Power Automate:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/03-no-notifications-in-microsoft-teams-channel.png)

Die Warnung in Power Automate gibt uns einen besseren Hinweis darauf, was schief gelaufen sein könnte. In diesem Fall ist die folgende Fehlermeldung angezeigt worden:

`Warnung: Ihre <email>-Verbindung funktioniert nicht: Es sieht so aus, als müsse Ihre <email>-Verbindung des Flows erneut angemeldet werden. Die häufigste Ursache ist ein geändertes Kennwort oder eine Richtlinie, die von Ihrem Mandantenadministrator festgelegt wurde. Verbindungen können auch eine erneute Authentifizierung erfordern, wenn die mehrstufige Authentifizierung kürzlich für Ihr Konto aktiviert wurde.`

Um sich erneut zu authentifizieren, klicken Sie auf den Workflow in Teams und öffnen Sie den Workflow in Power Automate. Es ist auch möglich, zur Verbindungsseite in Power Automate zu gehen und dort eine Verbindung herzustellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/04-no-notifications-in-microsoft-teams-channel.png)

Klicken Sie im Dialog "Aktion erforderlich" auf "Erneut authentifizieren". Nach erfolgreicher Authentifizierung sollte die Verbindung auf der Seite "Verbindungen" angezeigt werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/05-no-notifications-in-microsoft-teams-channel.png)
