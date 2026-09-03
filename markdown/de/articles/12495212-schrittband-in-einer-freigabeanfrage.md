# Schrittband in einer Freigabeanfrage

Das Schrittband befindet sich oben auf der Seite einer [Entwurfs-](https://support.catenda.com/en/articles/12495175-draft-approval-request-page), [offenen oder geschlossenen](https://support.catenda.com/en/articles/12494960-open-or-closed-approval-request-page) Freigabeanfrage für Projekte, die Shared Revisions nach dem 2. Oktober 2025 aktiviert haben. Im Schrittband wird eine Vorschau aller Freigabeverifikationsschritte einer Freigabe angezeigt. So kann das Freigabeanfrage-Schrittband für eine Freigabeanfrage aussehen, bei der ein Freigabe-Workflow mit der maximalen Anzahl von Freigabeanfrage-Schritten ausgewählt ist:

![Genehmigungsschrittband. Schritt 2 Fälligkeit Endgültige Genehmigung 10 Schritte](https://raw.githubusercontent.com/catenda/help-center/main/images/1bshvqk0/01-intro.png)

Projekte, bei denen Shared Revisions vor dem 2. Oktober 2025 aktiviert wurden, sehen stattdessen die Legacy-Freigabeanfrage-Seite.

## 1. **Erstellter Freigabeanfrage-Schritt**

Fahren Sie mit der Maus über den erstellten Schritt, um Informationen zur Erstellung der Freigabeanfrage anzuzeigen. Sehen Sie den Namen des Mitglieds, das die Freigabeanfrage erstellt hat. Zum Zeitpunkt der Erstellung muss das Mitglied Teil eines für diesen Freigabe-Workflow konfigurierten Einreicher-Teams gewesen sein. Sehen Sie, wann die Freigabeanfrage erstellt wurde.

![Genehmigungsanforderungsschrittband Hover erstellt von Benutzername Fälligkeit](https://raw.githubusercontent.com/catenda/help-center/main/images/1bshvqk0/02-created-approval-request-step.png)

### 1.1 **Erstellter Schritt in einer Entwurfs-Freigabeanfrage**

So kann der erstellte Schritt in einer Entwurfs-Freigabeanfrage aussehen:

![Genehmigungsschrittband erstellter Schritt rotes Überfälligkeitsdatum endgültige Genehmigungsprüfung](https://raw.githubusercontent.com/catenda/help-center/main/images/1bshvqk0/03-created-step-in-draft-approval-request.png)

Entwurfs-Freigaben erreichen ihr Erstellungsdatum, sobald sie erstellt werden. Das Erstellungsdatum sieht daher immer rot aus.

## 2. **Bestandener Freigabeanfrage-Schritt**

Fahren Sie mit der Maus über einen bestandenen Freigabeschritt, um Informationen zu diesem anzuzeigen. Sehen Sie die Fälligkeit für den bestandenen Freigabeschritt. Wenn die Fälligkeit überschritten wurde, wird sie rot angezeigt. Sehen Sie, welche Teams für diesen Freigabeschritt konfiguriert sind.

![Überfälliger Anforderungsschritt Genehmigungsschrittband Hover Fälligkeit in rot Teams zur Überprüfung erwähnt](https://raw.githubusercontent.com/catenda/help-center/main/images/1bshvqk0/04-passed-approval-request-step.png)

## 3. **Aktueller Freigabeanfrage-Schritt**

Wenn ein Freigabeanfrage-Schritt der aktuelle Schritt ist, wird die Fälligkeit für den aktuellen Freigabeschritt in der Vorschau des Freigabeanfrage-Schritts angezeigt. Wenn die Fälligkeit überschritten wurde, wird sie rot angezeigt. Fahren Sie mit der Maus über den aktuellen Freigabeanfrage-Schritt, um Informationen zu diesem anzuzeigen.

![Genehmigungsschrittband Überprüfungsschritt Hover mit 10 Reviewer-Teams alle in Popup aufgelistet](https://raw.githubusercontent.com/catenda/help-center/main/images/1bshvqk0/05-current-approval-request-step.png)

Automatisches Fortschreiten aktiviert - Die Freigabeanfrage wechselt nach der Fälligkeit automatisch zum nächsten Schritt Automatisches Fortschreiten deaktiviert - Die Freigabeanfrage bleibt im Schritt, nachdem ihre Fälligkeit überschritten wurde, und wechselt nur fort, nachdem alle Bearbeiter ihre Validierungsbewertung eingereicht haben. Sehen Sie, welche Bearbeiter-Teams für diesen Freigabeanfrage-Schritt konfiguriert sind.

## 4. **Zukünftiger Freigabeanfrage-Schritt**

Fahren Sie mit der Maus über einen zukünftigen Freigabeschritt, um Informationen zu diesem anzuzeigen.

![Genehmigungsanforderungsschrittband Überprüfungsschritt Hover mit einem Team zur Überprüfung noch nicht fällig](https://raw.githubusercontent.com/catenda/help-center/main/images/1bshvqk0/06-future-approval-request-step.png)

Sehen Sie, welche Bearbeiter-Teams für diesen Freigabeanfrage-Schritt konfiguriert sind. Zukünftige Schritte haben noch keine Fälligkeit, da die Anzahl der Arbeitstage zur Fertigstellung des Schritts beginnt, sobald der vorherige Schritt beendet ist.

## 5. Finaler Freigabeschritt

Wenn der finale Freigabeschritt der aktuelle Schritt ist, wird die Fälligkeit für den finalen Freigabeschritt in der Schritt-Vorschau angezeigt. Wenn die Fälligkeit überschritten wurde, wird sie rot angezeigt. Zukünftige finale Freigabeschritte haben noch keine Fälligkeit, da die Anzahl der Arbeitstage zur Fertigstellung des Schritts beginnt, sobald der vorherige Schritt beendet ist. Fahren Sie mit der Maus über den aktuellen Freigabeanfrage-Schritt, um Informationen zu diesem anzuzeigen.

![Genehmigungsanforderung endgültiger Genehmigungsschritt Hover mit endgültigem Überprüfungsteam in Popup aufgelistet](https://raw.githubusercontent.com/catenda/help-center/main/images/1bshvqk0/07-final-approval-step.png)

Sehen Sie, welches Genehmiger-Team für den finalen Freigabeschritt konfiguriert ist. Ein Mitglied des finalen Genehmiger-Teams kann die endgültige Validierungsentscheidung darüber treffen, die Dokumente in dieser Freigabeanfrage genehmigen oder ablehnen zu lassen, basierend auf den Validierungsentscheidungen, die von jedem der Teams in jedem der Schritte getroffen wurden. Wenn das validierende Mitglied seine Validierung als genehmigt oder abgelehnt für jedes der Dokumente eingereicht hat, wird der Freigabe-Workflow geschlossen. Eine finale Freigabe muss immer eingereicht werden, um eine Freigabeanfrage zu schließen. Es gibt kein automatisches Fortschreiten für den finalen Freigabeschritt.

Wenn alle finalen Validierungen eingereicht sind, wird die Freigabeanfrage geschlossen.

![Genehmigungsanforderungsschrittband geschlossene Genehmigung endgültiger Schritt geschlossen in grün mit Schließungsdatum](https://raw.githubusercontent.com/catenda/help-center/main/images/1bshvqk0/08-final-approval-step.png)

Der finale Freigabeanfrage-Schritt erhält dann einen grünen Hintergrund. Das Datum, an dem alle finalen Validierungen eingereicht wurden, wird angezeigt.
