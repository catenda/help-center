# Einstellungsseite für Themenvorlagen

> Verwalten Sie Ihre Einstellungen für Themenvorlagen

Die Einstellungsseite für Themenvorlagen finden Sie, indem Sie auf der [Themeneinstellungsseite](https://support.catenda.com/en/articles/14183429-topic-settings-page) auf „Themenvorlagen konfigurieren

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/01-intro.png)

Auf der Seite mit den Themenvorlagen-Einstellungen können Themenvorlagen für jedes der Themen-Boards im Projekt konfiguriert werden. Nach ihrer Erstellung werden Themenvorlagen automatisch verfügbar gemacht, um Text und Felder von Themen bei der Erstellung auszufüllen. Themenvorlagen können so konfiguriert werden, dass sie in den folgenden Themenerstellungsprozessen verfügbar sind: [Verwendung von Themenvorlagen in allgemeinen Themen](https://support.catenda.com/en/articles/14075921-apply-a-general-topic-template-upon-topic-creation) [Verwendung von Themenvorlagen in Markup-Themen](https://support.catenda.com/en/articles/14078352-apply-a-document-topic-template-when-creating-a-markup-from-a-document) [Verwendung von Themenvorlagen mit Genehmigungen](https://support.catenda.com/en/articles/14078683-apply-an-approval-topic-template-to-an-approval-workflow-template)

## 1. **Aktionsmenü**

Klicken Sie auf die Schaltfläche mit dem Pluszeichen oben rechts, um das Aktionsmenü zu öffnen. So könnte das Aktionsmenü oben rechts auf der Seite mit den Themenvorlagen-Einstellungen aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/02-action-menu.png)

Ein Dropdown-Menü bietet die Möglichkeit, 3 unterschiedliche Arten von Themenvorlagen zu erstellen. Themenvorlagen werden in drei verschiedene Vorlagentypen unterteilt, da die Variablen, die zum automatischen Ausfüllen von Text und Feldern in den Themen bei der Erstellung verwendet werden können, je nach verwendetem Themenerstellungsprozess unterschiedlich sind.

## 2. **Such- oder Filteroptionen**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/03-search-or-filter-options.png)

### 2.1 **Suche**

_Textsuche -_ `search=<Search phrase>` Nach der Eingabe von Zeichen in der Such- oder Filterleiste ändert sich der erste vorgeschlagene Filter in die Textsuche.

**Durchsuchbarer Inhalt** Themenvorlagenname

**Groß- und Kleinschreibung** Die Textsuche berücksichtigt Groß- und Kleinschreibung nicht.

**Zeichenanzahl** Beliebige Zeichen können durchsucht werden.

**Leerzeichen** Leerzeichen am Anfang einer Suchphrase können durchsucht werden, werden aber aus den Vorlagennamen entfernt, sodass keine Ergebnisse bei der Suche angezeigt werden. Leerzeichen am Ende einer Suchphrase werden entfernt.

### 2.2 **Filterung im Filtermenü**

Themenvorlagen werden nach einem der möglichen Status gefiltert. Klicken Sie im Filtermenü auf das Status-Menü, um den Status auszublenden, der nicht gefiltert wird. Es ist möglich, das X rechts in der Suchleiste zu drücken, um die Filter-Tags aus der Leiste zu entfernen, aber dies hat keine Auswirkung. Es ist nur möglich, Vorlagen mit dem Filter "Aktiv" oder "Archiviert" zu filtern.

_Aktiv_ - `status=active` - Standard Themenvorlagen, die aktiv verwendet und so konfiguriert werden können, dass sie Themen generieren.

_Archiviert_ - `status=archived` Themenvorlagen, die nicht verfügbar sind, um in dem Themengenerierungsprozess verwendet oder konfiguriert zu werden.

## 3. **Vorlagentabelle**

Wenn Sie zu Ihrer Seite mit den Themenvorlagen-Einstellungen navigieren, können Sie einen Überblick über die zuvor erstellten Themenvorlagen sehen. So könnte die Themenvorlagentabelle aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/04-templates-table.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/11748020-tables-on-catenda), um mehr darüber zu erfahren, wie Sie mit Tabellen in Catenda arbeiten.

### 3.1 **Zeileninhalt**

Klicken Sie auf eine Themenzeile, um die Inhaltsseite der Themenvorlage für diese Vorlage zu öffnen.

### 3.2 **Spalten**

Alle Spalten in der Themenvorlagentabelle sind standardmäßig aktiviert. Je nach konfigurierter Spaltenreihenfolge werden die ersten Spalten angezeigt, während die Tabelle möglicherweise seitwärts gescrollt werden muss, um andere aktivierte Spalten anzuzeigen. Die Standardreihenfolge und Sichtbarkeitseinstellung der Spalten auf der Dokumentseite ist wie folgt:

Name Vorlagentyp Erstellt von Erstellt am Status Themen-Board

## 4. **Erstellen einer neuen allgemeinen Themenvorlage**

Kann für Themen verwendet werden, die aus dem allgemeinen Themenbereich erstellt wurden. Hier sind die verschiedenen Maßnahmen, die Sie ergreifen müssen, und die Variablen, die Sie beim Erstellen einer neuen allgemeinen Themenvorlage eingeben können:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/05-create-a-new-general-topic-template.png)

1. **Themen-Board**: Das Themen-Board, innerhalb dessen die allgemeine Themenvorlage generiert werden kann.
1. **Vorlagenname**: Der Vorlagenname kann während der Erstellung aus dem Dropdown-Menü ausgewählt oder später in den Einstellungen aktualisiert werden, wenn erforderlich.
1. **Thementitel**: Der resultierende Thementitel nach dem Erstellen des Themas aus der allgemeinen Themenvorlage.
   Bewegen Sie die Maus über das "?"-Symbol oben rechts im Titelfeld, um zu sehen, wie Sie Ihren Themenvorlagentitel mit der verfügbaren Variablen anpassen können: `topicCreator`.

    <div class="intercom-container intercom-align-center"><img height="184" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-272165f584d2.png" style="height: auto;" width="300"/></div>

1. **Themenstatus**: Der resultierende Themenstatus nach dem Erstellen des Themas aus der allgemeinen Themenvorlage.
1. **Thementyp**: Der resultierende Thementyp nach dem Erstellen des Themas aus der allgemeinen Themenvorlage.
1. **Meilenstein**: Der resultierende Themenmeilenstein nach dem Erstellen des Themas aus der allgemeinen Themenvorlage.
1. **Zugewiesen zu**: Der resultierende Themenverantwortliche (Projektmitglied oder Team) nach dem Erstellen des Themas aus der allgemeinen Themenvorlage. Sie können hier die Variable `Topic Creator` verwenden, um dieses Feld automatisch mit dem Themenerstellungsperson zu füllen, falls erforderlich.

    <div class="intercom-container intercom-align-center"><img height="94" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-c7f3d7220c54.png" style="height: auto;" width="150"/></div>

1. **Angefordert von**: Der resultierende Themenanforderer nach dem Erstellen des Themas aus der allgemeinen Themenvorlage. Sie können hier die Variable `Topic Creator` verwenden, um dieses Feld automatisch mit dem Themenerstellungsperson zu füllen, falls erforderlich.

    <div class="intercom-container intercom-align-center"><img height="93" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-43e4955bfdd8.png" style="height: auto;" width="150"/></div>

1. **Etiketten**: Die resultierenden Themenetiketten nach dem Erstellen des Themas aus der allgemeinen Themenvorlage.
1. **Beschreibung**: Die resultierende Themenbeschreibung nach dem Erstellen des Themas aus der allgemeinen Themenvorlage. Dieser Bereich unterstützt das Markdown-Format und Sie können sein volles Potenzial nutzen, um den Text zu formatieren, benutzerdefinierte Header und Checklisten zu erstellen.
    Bewegen Sie die Maus über das "?"-Symbol oben rechts im Beschreibungsfeld, um zu sehen, wie Sie alle verfügbaren Funktionen nutzen können (Teammates erwähnen und vorhandene Themen verlinken) und Variablen (wie `topicCreator` im Fall der allgemeinen Themenvorlage).

     <div class="intercom-container intercom-align-center"><img height="291" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-d2735ca1aec8.png" style="height: auto;" width="300"/></div>

Wenn Sie Ihre neue allgemeine Themenvorlage fertig eingerichtet haben, können Sie auf die Schaltfläche "Speichern" unten rechts klicken.

## 5. **Neue Dokument-Themenvorlage**

Kann für Themen verwendet werden, die aus Markups in Dokumenten erstellt wurden. Hier sind die verschiedenen Maßnahmen, die Sie ergreifen müssen, und die Variablen, die Sie beim Erstellen einer neuen Dokument-Themenvorlage eingeben können:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/06-new-document-topic-template.png)

1. **Themen-Board**: Das Themen-Board, innerhalb dessen die Dokument-Themenvorlage generiert werden kann.
1. **Vorlagenname**: Der Vorlagenname kann während der Markup-Erstellung aus dem Dropdown-Menü ausgewählt oder später in den Einstellungen aktualisiert werden, wenn erforderlich.
1. **Thementitel**: Der resultierende Thementitel nach dem Erstellen des Themas aus der Dokument-Themenvorlage.
   Bewegen Sie die Maus über das "?"-Symbol auf der rechten Seite des Titelfelds, um zu sehen, wie Sie Ihren Dokument-Themenvorlagentitel mit den verfügbaren Variablen anpassen können: `documentName`, `fileName`, `markupName` und `topicCreator`.

    <div class="intercom-container intercom-align-center"><img height="231" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-dbe5030f1082.png" style="height: auto;" width="300"/></div>

1. **Themenstatus**: Der resultierende Themenstatus nach dem Erstellen des Themas aus der Dokument-Themenvorlage.
1. **Thementyp**: Der resultierende Thementyp nach dem Erstellen des Themas aus der Dokument-Themenvorlage.
1. **Meilenstein**: Der resultierende Themenmeilenstein nach dem Erstellen des Themas aus der Dokument-Themenvorlage.
1. **Zugewiesen zu**: Der resultierende Themenverantwortliche (Projektmitglied oder Team) nach dem Erstellen des Themas aus der Dokument-Themenvorlage. Hier können verschiedene Variablen verwendet werden, wie `Document owner`, `File uploader`, `Markup creator`, `Publisher` und `Topic creator`.

    <div class="intercom-container intercom-align-center"><img height="228" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b3156a6c2724.png" style="height: auto;" width="150"/></div>

1. **Angefordert von**: Der resultierende Themenanforderer nach dem Erstellen des Themas aus der Dokument-Themenvorlage. Hier können verschiedene Variablen verwendet werden, wie `Document owner`, `File uploader`, `Markup creator`, `Publisher` und `Topic creator`.

    <div class="intercom-container intercom-align-center"><img height="171" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-0c4680dfae06.png" style="height: auto;" width="150"/></div>

1. **Etiketten**: Die resultierenden Themenetiketten nach dem Erstellen des Themas aus der Dokument-Themenvorlage. Beachten Sie, dass Sie die Etiketten aus dem Dokument, aus dem Sie das Markup erstellt haben, mit der Variablen `Labels from documents` abrufen können:

    <div class="intercom-container intercom-align-center"><img height="67" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-522016d4b8ae.png" style="height: auto;" width="500"/></div>

1. **Beschreibung**: Die resultierende Themenbeschreibung nach dem Erstellen des Themas aus der Dokument-Themenvorlage. Dieser Bereich unterstützt das Markdown-Format und Sie können sein volles Potenzial nutzen, um den Text zu formatieren, benutzerdefinierte Header und Checklisten zu erstellen.
    Bewegen Sie die Maus über das "?"-Symbol oben rechts im Beschreibungsfeld, um zu sehen, wie Sie alle verfügbaren Funktionen nutzen können (Teammates erwähnen und vorhandene Themen verlinken) und Variablen (wie `documentName`, `fileName`, `markupName` und `topicCreator` im Fall der Dokument-Themenvorlage).

     <div class="intercom-container intercom-align-center"><img height="349" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b8f3e2dabde9.png" style="height: auto;" width="300"/></div>

Wenn Sie Ihre neue Dokument-Themenvorlage fertig eingerichtet haben, können Sie auf die Schaltfläche "Speichern" unten rechts klicken.

## 6. **Neue Genehmigungsthemenvorlage**

Kann für Themen verwendet werden, die nach dem Schließen eines Genehmigungsworkflows generiert werden. _Erforderlicher Zugriff:_ Freigegebene Status aktiviert (Registerkarten "Arbeitsbereich" und "Veröffentlicht" sind in Dokumenten- und Modellseiten sichtbar)

> **Hinweis:** Diese Option wird nur angezeigt, wenn die aktuellen Status- und Validierungs-Workflows verwendet werden. Projekte, die nach dem 2. Oktober 2025 erstellt wurden, verwenden automatisch die aktuellen Status- und Validierungs-Workflows.

Hier sind die verschiedenen Maßnahmen, die Sie ergreifen müssen, und die Variablen, die Sie beim Erstellen einer neuen Genehmigungsthemenvorlage eingeben können:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/07-new-approval-topic-template.png)

1. **Themen-Board**: Das Themen-Board, innerhalb dessen die Genehmigungsthemenvorlage nach dem Schließen eines Genehmigungsworkflows generiert wird.
1. **Vorlagenname**: Der Vorlagenname einer Genehmigungsthemenvorlage kann aus dem Dropdown-Menü in einer Genehmigungsworkflow-Vorlage ausgewählt oder später in den Einstellungen aktualisiert werden, wenn erforderlich.
1. **Thementitel**: Der resultierende Thementitel nach dem Schließen des zugehörigen Genehmigungsworkflows.
   Bewegen Sie die Maus über das "?"-Symbol auf der rechten Seite des Titelfelds, um zu sehen, wie Sie Ihren Genehmigungsthemenvorlagentitel mit den verfügbaren Variablen anpassen können: `approvalRequestName`, `approvalRequestNumber`, `documentName`, `fileName`, `markupName` und `topicCreator`.

    <div class="intercom-container intercom-align-center"><img height="272" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-6038b1d41fed.png" style="height: auto;" width="300"/></div>

1. **Themenstatus**: Der resultierende Themenstatus nach dem Schließen des zugehörigen Genehmigungsworkflows.
1. **Thementyp**: Der resultierende Thementyp nach dem Schließen des zugehörigen Genehmigungsworkflows.
1. **Meilenstein**: Der resultierende Themenmeilenstein nach dem Schließen des zugehörigen Genehmigungsworkflows.
1. **Zugewiesen zu**: Der resultierende Themenverantwortliche (Projektmitglied oder Team), der den zugehörigen Genehmigungsworkflow schließt. Hier können verschiedene Variablen verwendet werden, wie `Approval request approver`, `Approval requested approver team`, `Approval request submitter`, `Approval request submitter team`, `Document owner`, `File uploader`, `Markup creator`, `Markup creator team`, `Publisher`.

    <div class="intercom-container intercom-align-center"><img height="182" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b012d92ee132.png" style="height: auto;" width="150"/></div>

1. **Angefordert von**: Der resultierende Themenanforderer nach dem Schließen des zugehörigen Genehmigungsworkflows. Hier können verschiedene Variablen verwendet werden, wie `Approval request approver`, `Approval requested approver team`, `Approval request submitter`, `Approval request submitter team`, `Document owner`, `File uploader`, `Markup creator`, `Markup creator team`, `Publisher`.

    <div class="intercom-container intercom-align-center"><img height="181" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-d7986adac70c.png" style="height: auto;" width="150"/></div>

1. **Etiketten**: Die resultierenden Themenetiketten nach dem Schließen des zugehörigen Genehmigungsworkflows. Beachten Sie, dass Sie die Etiketten aus dem Dokument, aus dem Sie das Markup erstellt haben, mit der Variablen `Labels from documents` abrufen können:

    <div class="intercom-container intercom-align-center"><img height="67" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-522016d4b8ae.png" style="height: auto;" width="500"/></div>

1. **Beschreibung**: Die resultierende Themenbeschreibung nach dem Schließen des zugehörigen Genehmigungsworkflows. Dieser Bereich unterstützt das Markdown-Format und Sie können sein volles Potenzial nutzen, um den Text zu formatieren, benutzerdefinierte Header und Checklisten zu erstellen.
    Bewegen Sie die Maus über das "?"-Symbol oben rechts im Beschreibungsfeld, um zu sehen, wie Sie alle verfügbaren Funktionen nutzen können (Teammates erwähnen und vorhandene Themen verlinken) und Variablen (wie `approvalRequestDueDate`, `approvalRequestFileLink`, `approvalRequestLink`, `approvalRequestName`, `approvalRequestNumber`, `documentName`, `fileName`, `markupName`, `topicCreator`) im Fall der Genehmigungsthemenvorlage).

     <div class="intercom-container intercom-align-center"><img height="449" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-f3f078b5d2af.png" style="height: auto;" width="300"/></div>

Wenn Sie Ihre neue Genehmigungsthemenvorlage fertig eingerichtet haben, können Sie auf die Schaltfläche "Speichern" unten rechts klicken.
