# Erstellen einer neuen Genehmigungsanforderung

Die neue Genehmigungsanforderungsaktion ist für Projekte verfügbar, bei denen geteilte Überarbeitungen nach dem 2. Oktober 2025 aktiviert wurden. Klicken Sie auf das Aktionsmenü rechts neben der grünen Schaltfläche "Plus" auf der [Genehmigungsseite](https://support.catenda.com/en/articles/8349340-approvals-page), um eine neue Genehmigungsanforderung zu erstellen. Klicken Sie auf die Schaltfläche "Neue Genehmigungsanforderung" im Genehmigungsmenü des rechten Menüs einer Überarbeitung auf der Dokumentenseite, wenn die neueste Überarbeitung eine geteilte Überarbeitung ist, um eine neue Genehmigungsanforderung zu erstellen. So könnte der Dialog "Neue Genehmigungsanforderung erstellen" aussehen:

![New approval request Workflow Submitter Title Description (optional) Documents for review add documents name revision # Revision number Status Remove Cancel Save as draft Submit for review](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/01-intro.png)

Projekte, bei denen geteilte Überarbeitungen vor dem 2. Oktober 2025 aktiviert wurden, sehen stattdessen den älteren Dialog "Neue Genehmigungsanforderung erstellen".

## 1. Genehmigungsanforderungs-Header

So könnte der Header einer neuen Genehmigung für Projekte aussehen, bei denen geteilte Überarbeitungen nach dem 2. Oktober 2025 aktiviert wurden:

![New approval requst Workflow Submitter Title](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/02-approval-request-header.png)

### 1.1 **Workflow-Auswahl**

Mitglieder, die Teil von Absender-Teams sind, die in einem Projekt-Workflow konfiguriert sind, können zwischen einem der Workflows wählen, für die ihre Teams konfiguriert sind. Der zuvor ausgewählte Workflow wird beibehalten. Solange der zuvor ausgewählte Workflow noch verfügbar ist, wird er beim nächsten Erstellen einer Genehmigung erneut ausgewählt.

**Automatische Auswahl** Wenn nur eines der Teams, zu denen ein Mitglied gehört, für einen Workflow konfiguriert ist, wird dieser Workflow automatisch ausgewählt. So kann es aussehen, wenn der Workflow automatisch ausgewählt wird.

![Workflow Submitter Title](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/03-workflow-selection.png)

_Erforderlicher Zugriff:_ Mitglieder und Administratoren müssen Teil eines Absender-Teams sein, das für einen Workflow konfiguriert ist, um den Workflow auswählen zu können.

### 1.2 **Absender-Auswahl**

Nachdem ein Workflow ausgewählt wurde, können Mitglieder, die Teil mehrerer Absender-Teams sind, die für den Workflow konfiguriert sind, auswählen, in welchem Namen welchen Team sie die Genehmigungsanforderung einreichen möchten. Das zuvor ausgewählte Absender-Team wird beibehalten. Solange das Mitglied noch Teil des zuvor ausgewählten Absender-Teams ist, wird es beim nächsten Erstellen einer Genehmigung erneut ausgewählt.

Wenn die Genehmigungsanforderung erstellt wird, sehen Mitglieder, die Teil des ausgewählten Absender-Teams sind, die Anforderung, während Mitglieder, die Teil der anderen möglichen Absender-Teams sind, die Anforderung nur sehen, wenn sie Teil eines der Prüfer-Teams oder Teil des Endgenehmigungsteams sind, das für den Workflow konfiguriert ist.

**Automatische Auswahl** Wenn ein Mitglied nur Teil eines der Absender-Teams ist, die für den Workflow konfiguriert sind, wird das Absender-Team automatisch ausgewählt, wenn der Workflow ausgewählt wird.

![Workflow Submitter Title](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/04-submitter-selection.png)

_Erforderlicher Zugriff:_ Mitglieder und Administratoren müssen Teil eines Absender-Teams sein, das für einen Workflow konfiguriert ist, um in dessen Namen eine Genehmigung einreichen zu können.

### 1.3 **Titel**

Der Titel der Genehmigungsanforderung. Eine Genehmigung muss einen Titel haben, um eingereicht zu werden.

## 2. **Genehmigungsanforderungs-Body**

Der neue Validierungs-Workflow ist eine On-Demand-Funktion, die beim Start eines neuen Projekts angefordert werden kann. Es ist nur möglich, ein Projekt basierend auf einem Template-Projekt zu erstellen, wenn der neue Validierungs-Workflow in diesem Template-Projekt nicht aktiviert ist. So könnte der Body einer neuen Genehmigung für Projekte aussehen, bei denen geteilte Überarbeitungen nach dem 2. Oktober 2025 aktiviert wurden:

![Approval Reqeust body Description (optional) Documents for review add documents cancel no documents added yet](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/05-approval-request-body.png)

### 2.1 **Beschreibung**

Die Beschreibung der Genehmigung folgt den [allgemeinen Formatierungsregeln von Beiträgen](https://support.catenda.com/en/articles/8430847-formatting-of-posts).

### 2.2 **Dokumente hinzufügen**

![Description (optional) documents for review add documents](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/06-add-documents.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/12382093-add-revision-to-approval), um mehr über das Hinzufügen von geteilten Überarbeitungen aus Dokumenten zu einer Genehmigungsanforderung zu erfahren. Obwohl es möglich ist, hier eine unbegrenzte Anzahl von Dokumenten hinzuzufügen, beträgt die Grenze für die Einreichung der Genehmigungsanforderung zur Überprüfung 1000 Dokumente.

### 2.3 **Tabelle "Dokumente zur Überprüfung"**

So könnte die Tabelle "Dokumente zur Überprüfung" aussehen, nachdem geteilte Überarbeitungen in jedem Dokument hinzugefügt wurden, die validiert werden sollen:

![Documents review table Name revision # Revision number Status Remove Cancel Save as draft Submit for review](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/07-documents-for-review-table.png)

**Spalten** Basierend auf der konfigurierten Spaltenreihenfolge werden die ersten Spalten angezeigt, während die Tabelle möglicherweise zur Seite gescrollt werden muss, um andere aktivierte Spalten anzuzeigen. Die Standardreihenfolge und Sichtbarkeitseinstellung der Spalten auf der Dokumentenseite ist wie folgt:

_Name_ - _Standard_ Der Name des Dokuments, in dem sich die geteilte Überarbeitung befindet. Der Dokumentname ist für alle Überarbeitungen im Dokument gleich.

Überarbeitung - _Standard_ Der Name der Dokumentüberarbeitung. Dies ist derselbe wie der ursprüngliche Dateiname der hochgeladenen Datei.

## 3. - _Standard_

Status - _Standard_ Der Name des gemeinsamen Status, der auf die geteilte Überarbeitung angewendet wird.

Entfernen - _Standard_ Klicken Sie auf das x in der Spalte "Entfernen", um das zu überprüfende Dokument aus der Liste "Dokumente zur Überprüfung" zu entfernen.

## 4. **Als Entwurf speichern**

Bearbeitungsanforderung bearbeiten, bevor sie eingereicht und gesperrt wird.

### 4.1 **Mehr als 1000 Dokumente in Entwürfen**

Obwohl es möglich ist, beliebig viele Dokumente zum Dialog "Revision hinzufügen zur Genehmigungsanfrage" hinzuzufügen, ist es nur möglich, den Dialog mit bis zu 1000 Dokumentrevision einzureichen. Um mehr als 1000 Dokumentrevisionen mit dem neuen Validierungs-Workflow hinzuzufügen, fügen Sie zunächst bis zu 1000 Dokumente hinzu und speichern Sie die Genehmigungsanfrage als Entwurf. Fügen Sie dann bis zu 1000 Dokumente auf einmal zum Entwurf der Genehmigungsanfrage mit den Aktionen "Dokumente hinzufügen" auf der Seite des Entwurfs der Genehmigungsanfrage hinzu, bevor Sie die Genehmigungsanfrage einreichen.

### 4.2 **Überprüfungsdauer des ersten Schritts starten, wenn bereit**

Sobald die Genehmigungsanfrage eingereicht wird, werden die im ersten Schritt des ausgewählten Genehmigungsworkflows konfigurierten Überprüfungs-Teams damit beauftragt, die Revisionen in der Genehmigungsanfrage während der Dauer ihres Genehmigungsschritts zu überprüfen. Die Mitglieder in den Überprüfungs-Teams können die Revisionen überprüfen, bis die für ihren Genehmigungsschritt konfigurierten Arbeitstage vorbei sind. Speichern Sie eine Genehmigungsanfrage als Entwurf, damit sie eingereicht werden kann, sobald der Workflow bereit ist zu beginnen.

Stellen Sie sicher, dass die Teams bereit sind, indem Sie kommunizieren, dass ihr Überprüfungsschritt kurz bevorsteht, bevor Sie den Genehmigungsanfrage-Workflow einreichen und die Überprüfungsdauer des ersten Schritts für die im ausgewählten Workflow konfigurierten Überprüfungs-Teams starten.

Stellen Sie sicher, dass das endgültige Veröffentlichungsdatum des Workflows zum richtigen Zeitpunkt endet, indem Sie die Gesamtanzahl der Arbeitstage im Workflow mit den Tagen abstimmen, an denen der Workflow eingereicht werden soll.

## 5. **Zur Überprüfung einreichen**

Klicken Sie auf "Zur Überprüfung einreichen", um die Genehmigung einzureichen und den Genehmigungsprozess zu starten. Folgende Anforderungen müssen erfüllt sein, um die Genehmigungsanfrage zur Überprüfung einzureichen:

- Der Workflow, dem die Bearbeitungsanforderung folgt, muss ausgewählt werden.
- Ein Team, das im Namen einreicht, muss ausgewählt werden
- Ein Titel
- Dokumente
  - Mindestens 1 Dokument mit einer ausgewählten freigegebenen Revision muss hinzugefügt werden, um die Bearbeitungsanforderung einreichen zu können.
  - Es können maximal 1000 Dokumentrevisionen mit einer ausgewählten freigegebenen Revision hinzugefügt werden.
  - Um eine Bearbeitungsanforderung mit mehr als 1000 Dokumentrevisionen zu erstellen, erstellen Sie zunächst einen Entwurf mit bis zu 1000 Revisionen und fügen Sie dann bis zu 1000 Dokumentrevisionen gleichzeitig zum Entwurf hinzu, bevor Sie den Entwurf zur Überprüfung einreichen.

Nach dem Einreichen einer Bearbeitungsanforderung zur Überprüfung mit dem neuen Validierungs-Workflow ist das Einzige, das geändert werden kann, dass freigegebene Revisionsdokumente aus der Anforderung verworfen werden können.

_Überprüfungsdauer von Schritt 1 starten, wenn bereit_ Sobald die Bearbeitungsanforderung eingereicht wird, beginnt die Dauer des ersten Überprüfungsschritts, der im Bearbeitungs-Workflow konfiguriert ist.
