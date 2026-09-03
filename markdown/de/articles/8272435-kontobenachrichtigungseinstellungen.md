# Kontobenachrichtigungseinstellungen

Die Benachrichtigungseinstellungsseite finden Sie als Unterseite der [Benachrichtigungsseite](https://hub.catenda.com/notifications). In den [Benachrichtigungseinstellungen](https://bimsync.com/notifications/settings) können Sie konfigurieren, welche Benachrichtigungen Sie erhalten.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/01-intro.png)

Jede Registerkarte entspricht einer anderen Methode zum Versenden von Benachrichtigungen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/02-intro.png)

Die Registerkarte, auf der Sie sich gerade befinden, wird durch einen grünen Balken unterstrichen.

## 1. **Benachrichtigungsschalter**

Für jede Benachrichtigungsmethode können Sie Benachrichtigungen vollständig ein- oder ausschalten. Standardmäßig sind Catenda Hub- und E-Mail-Benachrichtigungen aktiviert, während Slack- und Teams-Benachrichtigungen ausgeschaltet sind. Um Benachrichtigungen für eine Registerkarte vollständig zu aktivieren oder zu deaktivieren, drücken Sie diesen Schalter.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/03-notification-switch.png)

Wenn eine Benachrichtigungsmethode deaktiviert wurde, wird der Kreis neben der Registerkarte grau.

> **Hinweis:** Wenn Sie E-Mail-Benachrichtigungen deaktivieren, können Sie trotzdem Projekteinladungs-E-Mails und Freigabelink-E-Mails erhalten.

Klicken Sie erneut auf den Schalter, um die Benachrichtigungen wieder einzuschalten.

## 2. **Benachrichtigungskontrollkästchen**

Für jede Benachrichtigungsmethode können Sie auswählen, welche Benachrichtigungstypen Sie für diese Methode erhalten möchten. Klicken Sie [hier](https://support.catenda.com/en/articles/8304417-untitled-article), um zu sehen, wann jeder Benachrichtigungstyp gesendet wird.

## 3. **In-Browser-Benachrichtigungen**

Die Registerkarte "Catenda Hub" ermöglicht es Ihnen, zu konfigurieren, welche Benachrichtigungen Sie im Browser erhalten. Dies sind die Benachrichtigungen, die Sie auf der [Benachrichtigungsseite](https://hub.catenda.com/notifications) sehen. Wenn Sie eine Benachrichtigung erhalten, wird oben rechts eine rote Anzahl von ungelesenen Benachrichtigungen auf dem Benachrichtigungssymbol angezeigt. Wenn Sie auf diese Schaltfläche klicken, verschwindet das Ungelesen-Abzeichen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/04-in-browser-notifications.png)

## 4. **E-Mail-Benachrichtigungen**

Die E-Mail-Registerkarte ermöglicht es Ihnen, zu konfigurieren, welche Benachrichtigungen Sie per E-Mail erhalten. Standardmäßig erhalten Sie eine E-Mail pro Benachrichtigung auf Catenda Hub. Wenn Sie Ihre E-Mail-Benachrichtigungen ändern, erhalten Sie alle Benachrichtigungen auf Catenda Hub wie [oben](#h_e4a9ba5c0c) konfiguriert

### 4.1 **E-Mail-Zusammenfassung**

Bei E-Mail-Benachrichtigungen können Sie stattdessen eine tägliche Zusammenfassung erhalten.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/05-br-email-summary.png)

Jedes Mal, wenn eine Zusammenfassung gesendet wird, enthält sie alle Benachrichtigungen, die seit der letzten Zusammenfassung eingegangen sind.

## 5. **Slack-Benachrichtigungen**

Die Slack-Registerkarte ermöglicht es Ihnen, die Benachrichtigungen zu erhalten, die an Ihr Konto in einem Slack-Kanal gesendet wurden. Diese Benachrichtigungsmethode ist standardmäßig ausgeschaltet und muss konfiguriert und aktiviert werden, wenn Sie sie verwenden möchten. Sie finden die Webhook-URL-Einstellung unten auf der Registerkartenseite.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/06-slack-notifications.png)

Das Einrichten von "Slack webhook URL" sendet Catenda Hub-Benachrichtigungen an Slack. Zum Einrichten gehen Sie zu ([https://api.slack.com/incoming-webhooks](https://api.slack.com/incoming-webhooks)) und klicken Sie auf den Link `incoming webhook integration`. Wählen Sie den Kanal, zu dem die Nachrichten gehen sollen, und kopieren Sie das Feld `webhook URL` in Catenda.

## 6. **Microsoft Teams-Benachrichtigungen**

Die Registerkarte "Microsoft Teams" ermöglicht es Ihnen, die Benachrichtigungen zu erhalten, die an Ihr Konto in einem Microsoft Teams-Kanal gesendet wurden. Diese Benachrichtigungsmethode ist standardmäßig ausgeschaltet und muss konfiguriert und aktiviert werden, wenn Sie sie verwenden möchten. Sie finden die Webhook-URL-Einstellung unten auf der Registerkartenseite.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/07-microsoft-teams-notifications.png)

Wählen Sie in Ihrem Teams-Kanal **"Connectors"** aus dem Hauptmenü. Suchen Sie nach **"Incoming Webhook"** und wählen Sie **"Configure"**. Legen Sie den Namen auf Catenda fest, verwenden Sie **"[https://hub.catenda.com/img/logo-192x192.png](https://hub.catenda.com/img/logo-192x192.png)"** als Bild und drücken Sie dann **"Create"**.

Kopieren Sie die URL in die **"Webhook URL"** oben. Stellen Sie sicher, dass die Benachrichtigungen oben aktiviert sind, und aktivieren Sie dann die Benachrichtigungstypen, die Sie in den Teams-Kanal senden möchten

## 7. **Pro-Projekt-Benachrichtigungen**

Wenn Sie projektspezifische Benachrichtigungen eingerichtet haben, können Sie diese im linken Navigationsmenü eines Projekts sehen. Sie können auf den Namen des Projekts klicken, um zu den [Projektbenachrichtigungseinstellungen](https://support.catenda.com/en/articles/4670262-project-notification-settings) für dieses Projekt zu gelangen. Diese Einstellungen sind für Sie spezifisch und nicht für das gesamte Projekt.
