# Registerkarte "Übersicht" in einer Freigabeanfrage

Die Registerkarte "Übersicht" einer Freigabeanfrage finden Sie auf der Seite der Freigabeanfrage von [offenen oder geschlossenen](https://support.catenda.com/en/articles/12494960-open-or-closed-approval-request-page) Freigaben. In der Registerkarte "Übersicht" finden Sie eine Übersicht eines ausgewählten Freigabeprüfschritts. In dem Schritt können die Validierungen eingesehen werden, die von einem Mitglied im Namen jedes zur Prüfung des Schritts konfigurierten Sender-Teams angegeben und eingereicht werden. Eine Übersicht der Validierungseinreichungen für alle Schritte finden Sie auf der [Registerkarte "Dokumente"](https://support.catenda.com/en/articles/8349418-approval-page#h_133b2690af).

> **Hinweis:** **Look and Feel -** Dies ist eine mögliche Darstellung der Registerkarte "Übersicht" im Genehmigungsinhalt für Projekte, bei denen gemeinsame Überarbeitungen nach dem 2. Oktober 2025 aktiviert wurden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/01-intro.png)

## 1. Registerkarte Freigabeprüfschritt-Menüband

Im Schritt-Menüband kann eine Vorschau des Fortschritts der Freigabeanfrage eingesehen werden. Dies ist ein mögliches Aussehen des Schritt-Menübands:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/02-approval-request-step-ribbon.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/12495212-step-ribbon-in-an-approval-request), um mehr über das Schritt-Menüband zu erfahren

## 2. Dropdown Freigabeschritt

Dies ist ein mögliches Aussehen des Dropdown-Menüs für den Freigabeschritt, wenn eine Freigabeanfrage den endgültigen Freigabeschritt erreicht hat:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/03-approval-step-dropdown.png)

Der aktuelle und alle abgeschlossenen Freigabeschritte sind im Dropdown-Menü für den Freigabeschritt aufgelistet. Wählen Sie einen Freigabeschritt in der Liste aus, um den Status der Validierungen anzuzeigen, die von jedem der für den Schritt konfigurierten Teams gegeben wurden. Eine Übersicht der Validierungen in allen Schritten finden Sie auf der Registerkarte "Dokumente".

## 3. Tabelle unter Überprüfung

In der Tabelle "Unter Überprüfung" können Dokumente eingesehen werden, die noch nicht eingereicht wurden. Dies ist ein mögliches Aussehen der Tabelle "Unter Überprüfung":

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/04-under-review-table.png)

Mitglieder, die Teil von Teams sind, die als Prüfer-Teams für diesen Freigabeprüfschritt konfiguriert sind, sehen eine Zeile pro konfiguriertes Prüfer-Team, von dem sie Teil sind. Im aktiven Freigabeprüfschritt wird eine gelbe Leiste am oberen Rand angezeigt, wenn noch Validierungsangaben eingereicht werden müssen, für die ein Mitglied Teil eines Prüfer-Teams ist.

Wenn alle Dokumente überprüft wurden und Validierungsangaben im Namen jedes der Prüfer-Teams eingereicht wurden, wird die Leiste am oberen Rand grün und erhält ein Häkchen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/05-under-review-table.png)

> **Hinweis:** Das grüne Aussehen der Leiste bedeutet nur, dass es für die Teams, deren Mitglied Sie sind, in diesem Freigabeprüfschritt keine ausstehenden Aktionen mehr gibt. Es kann aber andere Teams geben, die ihre Validierungsangaben noch einreichen müssen, bevor die Freigabeanfrage zum nächsten Schritt übergehen kann. Diese können in der nachfolgenden Schritt-Übersichtstabelle eingesehen werden.

### 3.1 Spalten in der Tabelle unter Überprüfung

**Team** Namen der Prüfer-Teams, die für diesen Freigabeschritt im Freigabeworkflow konfiguriert sind, den der Absender der Freigabeanfrage für diese Freigabeanfrage ausgewählt hat. _Erforderliche Berechtigung:_ Mitglied des Prüfer-Teams

**Ausstehend** Die Anzahl der Dokumente, die in diesem Freigabeprüfschritt noch keine Validierungsangabe erhalten haben. _Erforderliche Berechtigung:_ Mitglied des Prüfer-Teams Überprüfung Klicken Sie auf "Überprüfung", um die Dateien-Überprüfung für die Dokumente zu öffnen, die im Namen eines Prüfer-Teams in diesem Freigabeprüfschritt noch keine Validierungsangabe oder Einreichung erhalten haben.

**Überprüft** In der Spalte "Überprüft" werden die Anzahl der abgelehnten und genehmigten Validierungsangaben angezeigt. Jedes Mitglied eines Prüfer-Teams konnte diese Angabe im Namen des Prüfer-Teams geben. _Erforderliche Berechtigung:_ Mitglied des Prüfer-Teams Einreichen Validierungsangaben, die Mitglieder des Prüfer-Teams im Namen eines Prüfer-Teams gegeben haben, können mit der Schaltfläche "Einreichen" eingereicht werden. Klicken Sie auf die Schaltfläche "Einreichen", um alle Validierungsangaben im Namen des Prüfer-Teams auf einmal einzureichen. Sobald die Validierungsangabe eingereicht ist, ist das Dokument nicht mehr unter Überprüfung und verschwindet aus der Tabelle "Unter Überprüfung".

## 4. Schritt-Übersichtstabelle

In der Schritt-Übersichtstabelle kann eine Übersicht des Fortschritts aller Prüfer-Teams für diesen Schritt eingesehen werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/06-step-overview-table.png)

Wenn Validierungsangaben für alle Dokumente eingereicht werden, wird die Freigabeanfrage zum nächsten Freigabeprüfschritt übergeleitet. Die automatische Genehmigung kann in dem Workflow konfiguriert werden, den der Absender der Freigabeanfrage für diese Freigabeanfrage ausgewählt hat. Wenn die automatische Genehmigung für einen Freigabeprüfschritt aktiviert ist, werden alle Dokumente, die noch ausstehend sind, wenn der Freigabeprüfschritt fällig ist, automatisch genehmigt und die Freigabeanfrage wird zum nächsten Freigabeprüfschritt übergeleitet.

### 4.1 Spalten in der Schritt-Übersichtstabelle

**_Team_ —** Namen der Prüfer-Teams, die für diesen Freigabeschritt im für diese Freigabeanfrage ausgewählten Workflow konfiguriert sind.

**_Ausstehend_ —** Die Anzahl der Dokumente, für die ein Mitglied des Prüfer-Teams im Namen des Prüfer-Teams in diesem Freigabeprüfschritt noch keine Validierungsangabe eingereicht hat.

**_Unter Überprüfung –_** _Die Anzahl der Dokumente, die genehmigt oder abgelehnt, aber noch nicht eingereicht wurden. Wenn nicht eingereicht, aber zum Einreichen verfügbar, ist die Schaltfläche "Einreichen" dunkelgrün._

**_Eingereicht_ —** Die Anzahl der genehmigten Angaben, die von einem Mitglied des Prüfer-Teams im Namen eines Prüfer-Teams in diesem Freigabeprüfschritt eingereicht wurden.

**_Team-Fortschritt_ —** Der Fortschritt der Validierungsangaben, die von einem Mitglied des Prüfer-Teams im Namen eines Prüfer-Teams in diesem Freigabeprüfschritt eingereicht wurden.

## 5. Freigabeanfrage-Ergebnis

Nachdem das endgültige Prüfer-Team die abschließende Validierung für alle Dokumente eingereicht hat, wird die Freigabeanfrage geschlossen und die Dokumente werden mit der Veröffentlichung beginnen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/07-approval-request-result.png)

Das Ergebnis der Genehmigung wird unter der Schritt-Übersicht angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/08-approval-request-result.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/09-approval-request-result.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/12520773-approvals-troubleshooting), um mehr darüber zu erfahren, warum die Veröffentlichung von Dokumenten fehlschlagen kann.

### 5.1 Details anzeigen

Klicken Sie auf "Details anzeigen", um die Veröffentlichungsergebnisse für jedes Dokument einzusehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/10-view-details.png)

**Status**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/11-view-details.png)

Der Status der Veröffentlichung des Dokuments Der Status kann einer der folgenden sein:

**Veröffentlicht** Für Dokumente, die eine endgültige Genehmigung erhalten haben, wird die Revisionsnummer der gemeinsamen revision mit einem Pfeil zur veröffentlichten revision angezeigt, die als Ergebnis der Veröffentlichung dieser gemeinsamen revision erstellt wurde.

**Veröffentlichung fehlgeschlagen** Für Dokumente, die eine endgültige Genehmigung erhalten haben, aber nicht veröffentlicht werden konnten, wird der Grund angezeigt, warum sie nicht veröffentlicht werden konnten.

**Status festlegen** Für Dokumente, die eine endgültige Ablehnung erhalten haben, wird der Status angezeigt, mit dem die revision als Ergebnis aktualisiert wurde.

**_Name_** Das Folgende wird in der Spalte "Name" angezeigt:

- Dokumentdateipfad
- Dokumentsymbol
- Revisionsname des Dokuments
