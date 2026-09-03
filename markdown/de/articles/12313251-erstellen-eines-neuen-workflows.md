# Erstellen eines neuen Workflows

Die neue Workflow-Seite kann durch Klicken auf die grüne Schaltfläche auf [der Workflows-Seite](https://support.catenda.com/en/articles/12309903-workflows-page-document-settings) oder durch Klicken auf die Aktion im Aktionsmenü des neuen Elements auf [der Freigabenseite](https://support.catenda.com/en/articles/8349340-approvals-page) geöffnet werden. Es ist nur möglich, neue Workflows in Projekten zu erstellen, in denen der neue Validierungs-Workflow aktiviert werden kann. Der neue Validierungs-Workflow ist eine On-Demand-Funktion, die beim Start eines neuen Projekts aktiviert werden kann. Es ist nur möglich, ein Projekt basierend auf einem Template-Projekt zu erstellen, wenn der neue Validierungs-Workflow in diesem Template-Projekt nicht aktiviert ist. So könnte der Titelteil einer neuen Freigabe aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/01-intro.png)

## 1. **Titel**

Geben Sie den Namen des Workflows ein. Dies ist der einzige Teil des Workflows, der nach dem Einreichen bearbeitet werden kann.

### 1.1 **Anforderung**

Ein Titel muss angegeben werden, um einen Workflow einreichen zu können.

### 1.2 **Freigabeinhalte**

So könnte der Inhalt einer neuen Freigabe aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/02-approval-contents.png)

## 2. **Zeiteinstellungen**

Teammitglieder haben eine begrenzte Anzahl von Arbeitstagen, um Dokumente in Prüfschritten zu überprüfen, in denen ihr Team als Prüfteam eingestellt wurde. So könnten die Zeiteinstellungen eines neuen Freigabe-Workflows aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/03-time-settings.png)

Die in den Zeiteinstellungen konfigurierte Zeit ist die Zeit, in der jeder dieser Arbeitstage beginnt und endet. Konfigurieren Sie die Zeiteinstellungen so, dass sie den Teammitgliedern entsprechen, deren Teams in diesem Workflow als Prüfteams für Prüfschritte eingestellt sind. Teammitglieder können ihre Prüfung innerhalb des angegebenen Zeitrahmens basierend auf der Anzahl der Arbeitstage und der in diesem Feld konfigurierten Zeit einreichen.

**Beispiel für die Berücksichtigung von Zeiteinstellungen:** Einreichungen können auf der Grundlage dieser Zeiten datiert werden. Eine Einreichung um 2 Uhr morgens gehört zum Vortag, wenn die Zeiteinstellung auf 6 Uhr eingestellt ist.

### 2.1 **Startzeit**

Wählen Sie einen Wert von 01 bis 24 basierend auf dem 24-Stunden-Zeitsystem, auch bekannt als Militärzeit.

### 2.2 **Ausgewählte Zeitzone**

Die Standard-Zeitzone ist die in Ihrem Betriebssystem konfigurierte Zeitzone. So könnte ein ausgewähltes Zeitzonen-Listenelement aussehen.

Der erste Teil des ausgewählten Zeitzonen-Listenelements kann anzeigen:

- Eine Zeitzonen-Abkürzung von Zeitzonen, die keine Sommer- oder Wintervariante haben. Diese Zeitzonen bleiben das ganze Jahr über gleich.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/04-selected-timezone.png)

- Ein oder mehrere geografische Orte, die denselben Zeitzonen-Regeln folgen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/05-selected-timezone.png)

### 2.3 **GMT-Offset**

Der zweite Teil des ausgewählten Zeitzonen-Listenelements zeigt den aktuellen GMT-Offset für das ausgewählte Zeitzonen-Listenelement.

Die aktuelle Zeitzone für das Zeitzonen-Listenelement wird angezeigt. Wenn sich der GMT-Offset für einen geografischen Ort beispielsweise in Sommer- oder Winterzeit ändert, ändert sich auch der für diese geografischen Orte angezeigte GMT-Offset.

### 2.4 **Auswahl eines Elements in der Zeitzone-Dropdown**

Klicken Sie auf das ausgewählte Zeitzonen-Listenelement, um die Zeitzone-Dropdown zu öffnen. So könnte die Zeitzone-Dropdown aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/06-selecting-a-list-element-in-the-timezone-dropdown.png)

Standardmäßig kann für jedes 30-Minuten-Zeitzonen-Offset-Intervall mit einer aktiven Zeitzone im Dropdown ein Listenelement angezeigt werden.

**Beschreibung des Zeitzonen-Listenelements** Der erste Teil eines Zeitzonen-Listenelements kann anzeigen:

- Eine Zeitzonen-Abkürzung

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/07-selecting-a-list-element-in-the-timezone-dropdown.png)

- Ein oder mehrere geografische Orte, die denselben Zeitzonen-Regeln folgen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/08-selecting-a-list-element-in-the-timezone-dropdown.png)

**Name des Zeitzonen-Listenelements** Der zweite Teil eines Zeitzonen-Listenelements kann anzeigen:

- Ein Zeitzonen-Name.
  Für geografische Orte, an denen die Zeitzone das ganze Jahr über gleich ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/09-selecting-a-list-element-in-the-timezone-dropdown.png)

- Ein GMT+XX:XX Zeitzonen-Offset
  Für geografische Orte, an denen sich die Zeitzone während des Jahres ändert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/10-selecting-a-list-element-in-the-timezone-dropdown.png)

**Typ des Zeitzonen-Listenelements** Der letzte Teil eines Zeitzonen-Listenelements kann anzeigen:

- Eine Zeitzonen-Abkürzung

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/11-selecting-a-list-element-in-the-timezone-dropdown.png)

- Ein GMT+XX Zeitzonen-Offset

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/12-selecting-a-list-element-in-the-timezone-dropdown.png)

**Suche in der Zeitzone-Dropdown** Suchen Sie nach einem geografischen Ort, um alle Zeitzonen-Listenelemente für diesen Ort zu finden. Falls eine Übereinstimmung vorhanden ist, wird der Ort einbezogen. Er wird nicht immer wie unten dargestellt aufgelistet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/13-selecting-a-list-element-in-the-timezone-dropdown.png)

Einige Zeitzonen können anhand ihres Kurznamens im ersten Teil des Listenelements gesucht werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/14-selecting-a-list-element-in-the-timezone-dropdown.png)

Wenn eine Zeitzone das ganze Jahr über gleich ist, kann im zweiten Teil des Listenelements danach gesucht werden. Suchen Sie nach einer Zeitzone, um alle Zeitzonen-Listenelemente für diese Zeitzone zu finden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/15-selecting-a-list-element-in-the-timezone-dropdown.png)

> **Hinweis:** Verschiedene Zeitzonen-Listenelemente für denselben Zeitzonen-Namen können je nach aktuellem Datum und Uhrzeit unterschiedlich reagieren.

Suchen Sie nach einem Zeitzonen-Typ, um alle Zeitzonen-Listenelemente für diesen Zeitzonen-Typ zu finden: Suchen Sie entweder nach dem Zeitzonen-Offset:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/16-selecting-a-list-element-in-the-timezone-dropdown.png)

Oder nach der Zeitzonen-Abkürzung:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/17-selecting-a-list-element-in-the-timezone-dropdown.png)

Da einige Zeitzonen einen GMT-Offset als Typ haben, ist es oft besser, nach dem vollständigen Zeitzonen-Namen statt nach der Zeitzonen-Abkürzung zu suchen. Nur Zeitzonen, die derzeit aktiv sind, werden angezeigt. Für Zeitzonen, die sich für geografische Orte ändern, kann nur die Zeitzone gefunden werden, die derzeit für diesen geografischen Ort aktiv ist.

## 3. **Einreicher**

Wählen Sie aus, welche Teams Mitglieder im abschließenden Freigabeteam in der Liste der Teams sehen können, aus denen sie auswählen können, wenn sie ein Einreicher-Team für eine Freigabe mit diesem Workflow auswählen. So könnte der Einreicher-Teil eines neuen Freigabe-Workflows aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/18-submitters.png)

**Auswahl eines Teams, dessen Mitglied der Workflow-Ersteller ist** Wenn der Workflow-Ersteller derjenige sein wird, der diese Art von Workflows einreicht, ist es wichtig, dass ein Team, dessen Mitglied der Workflow-Ersteller ist, als Einreicher-Team hinzugefügt wird.

**Auswahl eines leeren Teams** Ein leeres Team kann ausgewählt werden, wenn die Mitglieder, die Teil dieses Teams sein werden, noch nicht Teil des Projekts sind.

**Auswahl eines Teams mit einem Mitglied** Da es nicht möglich ist, einzelne Mitglieder hinzuzufügen, kann ein Team mit nur einem Mitglied ausgewählt werden, wenn nur ein Mitglied auf diese Weise Dokumente genehmigen wird. Nach der Erstellung des Workflows kann dieser nicht mehr bearbeitet werden. Daher ermöglicht ein Team selbst mit einem Mitglied die Flexibilität, Personen in das Team hinein- und herauszubewegen.

> **Hinweis:** Es ist nur möglich, Teams und nicht einzelne Mitglieder auszuwählen

### 3.1 **Anforderung**

Mindestens ein Einreicher muss ausgewählt werden, um einen Workflow einreichen zu können.

## 4. **Prüfschritte**

Erstellen Sie einen mehrstufigen Prüfprozess. So könnte der Prüfschritt-Teil eines neuen Freigabe-Workflows aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/19-review-steps.png)

### 4.1 **Schrittanzahl**

**Keine Schritte** Es ist zwar möglich, einen Workflow ohne Schritte zu erstellen, indem man alle Schritte löscht, aber es wird nicht möglich sein, eine Freigabe mit diesem Workflow zu erstellen, da es mindestens einen Schritt geben muss, um eine Freigabe einreichen zu können.

**Maximale Anzahl von Schritten** Die maximale Schrittanzahl, die ein Workflow haben kann, ist 10.

### 4.2 **Teams**

Wählen Sie Prüfteams aus, die an dem Prüfschritt teilnehmen können. Die maximale Anzahl von Teams, die ein Workflow haben kann, ist 20. Jedes Team muss seine Prüfung einreichen, bevor der Workflow zum nächsten Schritt übergehen kann. Wenn die automatische Freigabe aktiviert ist, wird der Workflow nach der konfigurierten Anzahl von Arbeitstagen automatisch zum nächsten Schritt übergehen.

**Auswahl eines Teams, dessen Mitglied der Workflow-Ersteller ist** Wenn der Workflow-Ersteller derjenige sein wird, der einen Schritt prüft, ist es wichtig, dass ein Team, dessen Mitglied der Workflow-Ersteller ist, als Prüfteam hinzugefügt wird.

**Auswahl eines leeren Teams** Ein leeres Team kann ausgewählt werden, wenn die Mitglieder, die Teil dieses Teams sein werden, noch nicht Teil des Projekts sind.

**Auswahl eines Teams mit einem Mitglied** Da es nicht möglich ist, einzelne Mitglieder hinzuzufügen, kann ein Team mit nur einem Mitglied ausgewählt werden, wenn nur ein Mitglied auf diese Weise Dokumente genehmigen wird. Nach der Erstellung des Workflows kann dieser nicht mehr bearbeitet werden. Daher ermöglicht ein Team selbst mit einem Mitglied die Flexibilität, Personen in das Team hinein- und herauszubewegen.

### 4.3 **Arbeitstage für die Prüfung**

Arbeitstage sind definiert als Montag bis Freitag. Öffentliche Feiertage sind in den Arbeitstagen für die Prüfung enthalten. _Mindestens erforderliche Arbeitstage:_ 1 Arbeitstag

Beispiel: Wenn es der erste Schritt ist, beginnt er, sobald die Freigabeanforderung eingereicht wird. Andernfalls beginnt er, sobald Validierungen für jede der Revisionen im vorherigen Schritt eingereicht werden, oder er wird automatisch vorangetrieben und diese werden validiert.

Die Arbeitstage für die Prüfung für einen Freigabeanforderungsschritt sind auf 2 Tage eingestellt.

Wenn das Startdatum für den Freigabeschritt auf einen Freitag fällt, wird das Fälligkeitsdatum wie folgt festgelegt:

- Die Startzeit, die im Zeiteinstellungsbereich des Workflows konfiguriert ist
- Am Dienstag der nächsten Woche, unabhängig davon, ob dieser Dienstag ein öffentlicher Feiertag ist oder nicht.

### 4.4 **Automatische Freigabe**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/20-auto-approve.png)

Aktivieren Sie die automatische Freigabe, um Engpässe zu vermeiden – Dokumente erhalten automatisch freigegebene Prüfungen im Namen von Teams, die bis zur Fälligkeitsdatum nicht geantwortet haben.

### 4.5 Prüfung durch alle Teammitglieder erforderlich

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/21-br-require-review-from-all-team-members.png)

Aktivieren Sie "Prüfung durch alle Teammitglieder erforderlich", um zu verlangen, dass jedes einzelne Mitglied jedes Prüfteams in diesem Schritt seine eigene Validierungsangabe einreicht, bevor die Prüfung des Teams eingereicht werden kann.

- **Wenn diese Option deaktiviert ist** (das aktuelle, einzige Verhalten, das an anderer Stelle in diesem Hilfecenter beschrieben wird), kann ein beliebiges Mitglied des Prüfteams eine Validierungsangabe im Namen des gesamten Teams einreichen, und der Schritt kann sofort fortgesetzt werden.

- **Wenn diese Option aktiviert ist,** ist der Schritt des Teams nicht abgeschlossen, bis jedes einzelne Mitglied seine eigene Angabe gemacht hat. Weitere Informationen dazu, wie dies während der Prüfung angezeigt wird, finden Sie in den Artikeln zur Übersichtsregisterkarte, dem Dateiprüfungsmenü auf der rechten Seite und dem Dokumentenregisterkarten-Menü auf der rechten Seite.
  ​

### 4.6 **Prüfschritt löschen**

Klicken Sie auf das Mülleimer-Symbol oben rechts eines Prüfschritts, um ihn zu löschen.

### 4.7 **Anforderung**

Falls es Prüfschritte gibt, muss jeder Schritt mindestens einen Einreicher haben, um den Workflow einreichen zu können.

## 5. **Finale Freigabe**

Die finale Freigabe wird manuell von einem einzelnen Team erteilt. So könnte der Teil der finalen Freigabe eines neuen Freigabe-Workflows aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/22-final-approval.png)

### 5.1 **Team**

Das finale Freigabeteam, das die finale Freigabe basierend auf den Prüfungen jedes der Prüfteams erteilt.

**Auswahl eines Teams, dessen Mitglied der Workflow-Ersteller ist** Wenn der Workflow-Ersteller derjenige sein wird, der die finale Validierung der Freigabe erteilt, ist es wichtig, dass das Publisher-Team ein Team ist, dessen Mitglied der Workflow-Ersteller ist.

**Auswahl eines leeren Teams** Ein leeres Team kann ausgewählt werden, wenn die Mitglieder, die Teil dieses Teams sein werden, noch nicht Teil des Projekts sind.

**Auswahl eines Teams mit einem Mitglied** Da es nicht möglich ist, einzelne Mitglieder hinzuzufügen, kann ein Team mit nur einem Mitglied ausgewählt werden, wenn nur ein Mitglied auf diese Weise Dokumente genehmigen wird. Nach der Erstellung des Workflows kann dieser nicht mehr bearbeitet werden. Daher ermöglicht ein Team selbst mit einem Mitglied die Flexibilität, Personen in das Team hinein- und herauszubewegen.

### 5.2 **Arbeitstage für die Freigabe**

Die Anzahl der Arbeitstage, die das finale Freigabeteam benötigt, um die finale Freigabe zu konfigurieren. _Mindestens erforderliche Arbeitstage:_ 0 Arbeitstage

### 5.3 Themenvorlage

Im Feld Themenvorlagen können Sie die Vorlage auswählen, die das System verwendet und die ein Thema erstellt, wenn der Freigabefluss beendet wird. Wenn Sie nichts auswählen, werden keine Themen erstellt!

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/23-br-topic-template.png)

Die Auswahl einer Vorlage ist aus vorhandenen Themenvorlagen möglich. [Mehr über Themenvorlagen erfahren](https://support.catenda.com/en/articles/14076010-topic-template-settings-page)

Wenn keine Vorlage vorhanden ist, können Sie direkt in der Einstellungsansicht eine erstellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/24-br-topic-template.png)

### 5.4 **Prüfzustand**

Freigegeben oder abgelehnt

### 5.5 **Finaler Status**

Wählen Sie den finalen Status für freigegebene und abgelehnte Dokumente. Freigegebene Dokumente werden veröffentlicht, abgelehnte Dokumente werden nicht veröffentlicht.

### 5.6 **Anforderung**

Ein abschließendes Freigabeteam muss ausgewählt worden sein, um den Workflow einreichen zu können. Ein finaler Status für freigegebene Workflows muss ausgewählt werden, um den Workflow einreichen zu können. Ein finaler Status für abgelehnte Workflows muss ausgewählt werden, um den Workflow einreichen zu können.

## 6. **Einreichen**

Klicken Sie auf "Einreichen", um den Workflow einzureichen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/25-submit.png)

### 6.1 **Warnung für erforderliche Felder**

Wenn dem Workflow ein erforderliches Feld fehlt, wird eine Warnung oben auf der Seite aufgefordert, die fehlenden Felder auszufüllen. So könnte die Warnung aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/m7h7atyc/26-required-field-warning.png)

Folgende Anforderungen müssen erfüllt sein, um einen neuen Workflow einzureichen:

- Ein Titel.
- Mindestens 1 Einreicher-Team muss ausgewählt werden.
- Mindestens 1 Prüfteam muss pro Workflow-Schritt ausgewählt werden.
- Mindestens 1 Arbeitstag muss pro Workflow-Schritt konfiguriert werden.
- Ein abschließendes Freigabeteam muss ausgewählt werden
- Ein finaler Status für freigegebene Workflows muss ausgewählt werden
- Ein finaler Status für abgelehnte Workflows muss ausgewählt werden

### 6.2 **Nach dem Einreichen gesperrt**

Nach dem Einreichen ist es nur möglich, den Titel des Workflows zu ändern.
