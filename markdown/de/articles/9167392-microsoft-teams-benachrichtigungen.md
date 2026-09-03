# Microsoft Teams-Benachrichtigungen

> Bleiben Sie auf dem Laufenden, ohne zwischen Registerkarten zu wechseln. Verbinden Sie Catenda Hub mit Microsoft Teams, um Echtzeitbenachrichtigungen direkt in Ihren bevorzugten Kanälen zu erhalten.

Erhalten Sie Echtzeitbenachrichtigungen von einem Catenda-Konto direkt in einem Microsoft Teams-Kanal, indem Sie einen Microsoft Teams-Workflow in den Catenda-Benachrichtigungseinstellungen konfigurieren. _Erforderlicher Zugriff:_ Ein **Microsoft Teams**-Konto mit Berechtigungen zur Kanalerstellung und Verwaltung von Microsoft Teams-Workflows.

Die Registerkarte Microsoft Teams-Benachrichtigung befindet sich oben auf der Seite [Kontobenachrichtigungseinstellungen](https://support.catenda.com/en/articles/8272435-account-notification-settings), die eine Unterseite der Seite [Kontobenachrichtigungen](https://support.catenda.com/en/articles/7439223-account-notifications-page) ist:

![Catenda Hub Benachrichtigungen Microsoft Teams Benachrichtigungen Projekte mit eigenen Teams-Einstellungen](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/01-intro.png)

So können Catenda-Benachrichtigungen in Microsoft Teams aussehen, nachdem ein Microsoft Teams-Workflow konfiguriert wurde.

![Microsoft Teams Kanal Beiträge Bereit zur Überprüfung neues Thema neue Revision wurde in Modell importiert](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/02-intro.png)

---

### Schritt 1: Dedizierter Kanal vorbereiten

Benutzer können ihre Projektupdates organisieren, indem sie einen speziellen Bereich für Catenda-Benachrichtigungen erstellen. 1\. Wählen Sie in **Microsoft Teams** die Registerkarte **Teams** oder **Chat** aus. 2\. Verwenden Sie ein vorhandenes Team (überspringen Sie diesen Schritt) oder **erstellen Sie ein Team**.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/03-step-1-prepare-a-dedicated-channel.png)

Geben Sie einen Namen ein und erstellen Sie das Team.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/04-step-1-prepare-a-dedicated-channel.png)

Wenn ein Team erstellt wird, wird automatisch ein Kanal namens "Allgemein" hinzugefügt. 3\. Verwenden Sie einen vorhandenen Kanal (überspringen Sie diesen Schritt) oder fügen Sie einen Kanal hinzu. Klicken Sie mit der rechten Maustaste auf ein Team und wählen Sie im Aktionsmenü "Kanal hinzufügen" aus, oder klicken Sie auf das Team und klicken Sie oben rechts auf **Kanal hinzufügen**. _Erforderlicher Zugriff:_ Eigentümer oder Mitglied des Teams.

![Microsoft Teams Catenda Integration Chat Kanäle Kanal hinzufügen Mitglieder Analytik Apps Tags Alle Kanäle ausblenden Mitglied hinzufügen Team verwalten Tags verwalten Link kopieren Team verlassen](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/05-step-1-prepare-a-dedicated-channel.png)

> **Hinweis:** Mit Gast- oder externem Zugriff können keine Kanäle erstellt werden. In diesem Fall bitten Sie einen Kanaladministrator, Ihnen eine URL zur Verfügung zu stellen, an die Benachrichtigungen gesendet werden sollen.

Nach dem Klicken auf "Kanal erstellen" wird das Dialogfeld "Kanal erstellen" angezeigt:

![Kanal erstellen Kanalname Buchstaben, Zahlen und Leerzeichen sind zulässig Beschreibung Kanaltyp wählen Standard Privat Threads Beiträge](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/06-step-1-prepare-a-dedicated-channel.png)

**4. Benennen Sie Ihren Kanal**: Verwenden Sie etwas Aussagekräftiges wie "Catenda-Benachrichtigungen" oder "Projekt-A-Benachrichtigungen".

**5. Datenschutz wählen**: Catenda-Benachrichtigungen können an Standard- und private Kanäle übermittelt werden.

- Wählen Sie **Standard**, wenn das ganze Team die Updates sehen soll.
- Wählen Sie **Privat**, wenn die Benachrichtigungen nur für Sie oder eine bestimmte Gruppe bestimmt sind.

6\. Klicken Sie auf **Erstellen**.

---

### Schritt 2: Teams-Webhook-URL generieren

In der Vergangenheit wurden Catenda Teams-Benachrichtigungen über eine Webhook-Connector-Anwendung konfiguriert, die für den Kanal konfiguriert wurde. Die Webhook-Connector-Anwendung wurde inzwischen eingestellt. Die aktuelle Methode zum Erstellen einer Webhook-URL ist die Erstellung eines Microsoft Teams-Workflows.

Führen Sie diese Schritte aus, um einen neuen Microsoft Teams-**Workflow**-Webhook zu erstellen. 1\. Öffnen Sie **Microsoft Teams** 2\. Bewegen Sie den Mauszeiger über das gewünschte Team und klicken Sie auf die drei Punkte, oder klicken Sie auf die drei Punkte oben rechts, nachdem Sie den Kanal geöffnet haben. 3\. Wählen Sie Microsoft Teams-**Workflows** im Aktionsmenü

<img alt="Microsoft Teams Kanalaktionsmenü, Workflows hervorgehoben." src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-f533eea19d48.png" width="290"/>  \<---> <img alt="Aktionsmenü in Microsoft Teams Kanal, Workflows hervorgehoben." src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-1a6a43fe9eec.png" width="290"/>

4\. Suchen Sie nach **"Webhook-Benachrichtigungen an einen Kanal senden"** und wählen Sie diese aus.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/07-step-2-generate-your-teams-webhook-url.png)

5\. Führen Sie die Einrichtungsschritte aus, um Ihr Team und Ihren Kanal auszuwählen. **6. Kopieren Sie die URL**: Nachdem der Microsoft Teams-Workflow erstellt wurde, kopieren Sie die generierte Webhook-URL in Ihre Zwischenablage, indem Sie oben auf "Webhook-Link kopieren" klicken.

> **Hinweis:** 💡**Tipp**: Halten Sie diese URL privat. Jeder mit diesem Link kann Nachrichten an Ihren Teams-Kanal senden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/08-step-2-generate-your-teams-webhook-url.png)

---

### Schritt 3: Mit Catenda Hub verbinden

Führen Sie diese Schritte aus, um den Webhook-Link in Catenda zu konfigurieren. Auf diese Weise weiß Catenda, wohin die Projektbenachrichtigungen gesendet werden sollen.

1. Melden Sie sich bei **Catenda Hub** an.
1. Navigieren Sie zu **Benachrichtigungen > Einstellungen** (Kontoebene oder Projektebene).
1. Wählen Sie die Registerkarte "Microsoft Teams" und scrollen Sie bis ganz nach unten.
1. Fügen Sie Ihre kopierte URL in das Feld **Webhook-URL** ein.
1. Klicken Sie auf **Speichern**.

    <div class="intercom-container intercom-align-center"><img height="320" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-a60f9c2dbac8.png" style="height: auto;" width="500"/></div>

1. **Benachrichtigungen aktivieren**: Stellen Sie sicher, dass der Schalter oben auf der Seite auf **Ein** gestellt ist.

    <div class="intercom-container intercom-align-center"><img height="159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-a3e9aa9365d2.png" style="height: auto;" width="500"/></div>

---

### Schritt 4: Warnungen anpassen

Passen Sie die Informationen, die Sie erhalten, an, um Benachrichtigungsmüdigkeit zu vermeiden. 1\. Scrollen Sie im selben Menü **Benachrichtigungseinstellungen** durch die Liste der Benachrichtigungstypen. **2. Aktivieren Sie die Kontrollkästchen** für die spezifischen Updates, die Sie in Ihrem Teams-Kanal erhalten möchten. So kann das Menü "Microsoft Teams-Benachrichtigungen" aussehen:

![Wählen Sie aus, welche Benachrichtigungen Sie erhalten möchten Catenda Hub E-Mail Microsoft Teams Benachrichtigungen Themen Dokumente Genehmigungen Sammlungen Modelle Benutzer Ein neues Thema wird erstellt Ein Thema wird mir zugewiesen Ein Thema erwähnt mich oder mein Team Neuer Kommentar in einem mir zugewiesenen Thema von mir erwähnt mir gefolgt Thema Thema Status wurde in einem Thema geändert Typ wurde in Themen geändert Ich bin als Herausgeber in einer Genehmigungsanforderung festgelegt Ein Team, dessen Mitglied ich bin, ist als Herausgeber in einer Genehmigungsanforderung festgelegt Eine Genehmigungsanforderung wurde geschlossen Ein Mitglied des Absendeteams Eine neue Genehmigungsanforderung wurde eingereicht Ein Dokument wurde verworfen Eine Genehmigungsanforderung wurde geschlossen Eine neue Genehmigungsanforderung wurde eingereicht Eine neue Genehmigungsanforderung wurde meinem Team zugewiesen Eine neue Genehmigungsanforderung ist bereit zur Überprüfung durch mein Team Alle Überprüfungen wurden von meinem Team eingereicht Ein Dokument wurde verworfen Eine Genehmigungsanforderung wurde geschlossen Als Mitglied des Überprüfungsteams für die abschließende Genehmigung Eine neue Genehmigungsanforderung wurde eingereicht Eine neue Genehmigungsanforderung wurde meinem Team zugewiesen Eine neue Genehmigungsanforderung ist bereit zur Überprüfung durch mein Team Alle Überprüfungen wurden von meinem Team eingereicht Alle Überprüfungen wurden von meinem Team eingereicht Ein Überprüfungsschritt wurde abgeschlossen Ein Dokument wurde verworfen Eine Genehmigungsanforderung wurde geschlossen Ein neues Modell wird erstellt Eine neue Revision wurde importiert](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/09-step-4-customize-your-alerts.png)

Ausgegraute Benachrichtigungsfelder sind für Microsoft Teams deaktiviert und stehen nur für andere Benachrichtigungsmethoden zur Verfügung. Benachrichtigungsfelder für Genehmigungen sind verfügbar, wenn "Gemeinsame Revisionen" in [Dokumenteinstellungen](https://support.catenda.com/en/articles/7831371-document-settings-page) eines Projekts aktiviert sind.

---

### Schritt 5: Überprüfung

Stellen Sie sicher, dass eine Benachrichtigung an Ihr Konto gesendet wird, die auch an Microsoft Teams gesendet wird.

1\. Führen Sie eine Aktion in Catenda Hub durch.

> **Warnung:** ⚠️ **Hinweis:** Nicht jede Benachrichtigung kann an Microsoft Teams gesendet werden, und Microsoft Teams-Benachrichtigungen werden normalerweise nicht für Aktionen gesendet, die Benutzer selbst ausführen. Laden Sie ein Modell hoch oder bitten Sie einen Teamkollegen, ein Thema zu erstellen oder Sie in einer Beschreibung oder einem Kommentar zu erwähnen, um den Link zu überprüfen.

2\. Überprüfen Sie Ihren **Microsoft Teams-Kanal**. 3\. Eine Nachricht sollte sofort über den Microsoft Teams-**Workflow**-Bot angezeigt werden.
