# Workflows-Seite - Dokumenteinstellungen

Die Workflows-Seite finden Sie, indem Sie im Genehmigungsmenü der [Dokumenteinstellungsseite](https://support.catenda.com/en/articles/7831371-document-settings-page) auf die Schaltfläche "Workflows konfigurieren" klicken, in Projekten, in denen der neue Validierungs-Workflow aktiviert werden soll und freigegebene Status im Statusworkflow-Menü von [Dokumenteinstellungen](https://support.catenda.com/en/articles/7831371-document-settings-page) aktiviert sind. Der neue Validierungs-Workflow ist eine bedarfsgerechte Funktion, die beim Start eines neuen Projekts aktiviert werden kann. Es ist nur möglich, ein Projekt basierend auf einem Template-Projekt zu erstellen, wenn der neue Validierungs-Workflow in diesem Template-Projekt nicht aktiviert ist. Auf der Workflows-Seite können Workflows für verschiedene Genehmigungskonfigurationen konfiguriert werden. _Erforderlicher Zugriff:_ Administrator

Die Workflows-Seite kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/01-intro.png)

Die folgenden Themen werden in diesem Artikel beschrieben:

_[Neue Elementaktionen](https://support.catenda.com/en/articles/8204673-documents-page#h_d0f4a44fb7) - [Suchen oder filtern](https://support.catenda.com/en/articles/8204673-documents-page#h_bbf4dcad58) - [Rechtes Menü](https://support.catenda.com/en/articles/8204673-documents-page#h_fc89aaa1fe) - [Tabelle](https://support.catenda.com/en/articles/8204673-documents-page#h_54e8dfcac2) - [Unterseiten](https://support.catenda.com/en/articles/8204673-documents-page#h_5751ccd2b7)_

Obwohl die Workflows-Seite eine Unterseite zur Genehmigungsseite ist, wie durch die hervorgehobene Genehmigungsseite und die Breadcrumbs oben deutlich wird, ist die Seite nur über das Genehmigungsmenü in den Dokumenteinstellungen zugänglich.

## 1. **Neue Elementaktionen**

Die neuen Elementaktionen finden Sie oben rechts auf der Seite.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/02-new-item-actions.png)

Hier können Sie sehen, welche Funktionen die verschiedenen Aktionen haben.

## 2. **Such- oder Filteroptionen**

So könnte das Such- oder Filtermenü auf der Workflows-Seite aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/03-search-or-filter-options.png)

In der Suchleiste können alle auf der Workflows-Seite verfügbaren Workflows gesucht werden.

### 2.1 **Filterlinkenpanel**

Wenn Sie auf die Filterschaltfläche klicken, wird ein Panel auf der linken Seite angezeigt. Aktivieren Sie die Kontrollkästchen, um die Suche einzugrenzen. Wenn einer dieser Filter angewendet wird, wird der Filtertext zu Ihrer URL hinzugefügt. Wenn die URL der gefilterten Seite freigegeben wird, sieht die Person, die sie öffnet, die gleichen Ergebnisse wie derzeit angezeigt, solange sie Zugriff darauf hat.

### 2.2 **Filter**

> **Hinweis:** Die URL der Webseite ändert sich je nachdem, welche Filter angewendet wurden. Dies ermöglicht es, die aktuelle gefilterte Dokumente-Tabelle mit anderen Projektmitgliedern zu teilen.

Wenn mehrere derselben Filter ausgewählt sind, werden sie durch `,` oder `%2C` getrennt. Wenn mehrere Filter ausgewählt sind, werden sie durch `&` oder `%26` getrennt. Verschiedene Filter und ihre URL-Entsprechungen:

**Status** Aktiv - Standard - `status=active` Archiviert - `status=archived`

> **Hinweis:** Es ist nur möglich, entweder aktive oder archivierte Workflows anzuzeigen, nicht beide gleichzeitig

**Suche** Textsuche - `search=test` Standardmäßig entspricht die Textsuche nur aktiven Workflows. Um archivierte Status zu suchen, filtern Sie zuerst nach archiviert und verwenden Sie dann die Textsuche.

## 3. **Workflows-Tabelle**

Die Workflows-Tabelle kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/04-workflows-table.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/11748020-tables-on-catenda), um mehr über die Arbeit mit Tabellen in Catenda zu erfahren. Sobald ein Workflow erstellt wird, wird er als Zeile in der Workflows-Tabelle angezeigt.

### 3.1 **Zeileninhalt**

**Workflow-Zeile** Wenn Sie den Inhalt einer Workflow-Zeile öffnen, wird die Workflow-Seite für diesen Workflow geöffnet. So kann eine Workflow-Seite beim Öffnen aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/05-row-content.png)

Auf der Workflow-Seite eines Workflows können Sie sehen, wie der Workflow konfiguriert wurde.

Titel Der einzige Teil des Workflows, der bearbeitet werden kann, ist der Name des Workflows.

Zeitzone Wenn für den Workflow eine Zeitzone ausgewählt wird, bleibt sie das ganze Jahr über gleich. Wenn für den Workflow ein geografischer Standort ausgewählt wird, ändert sich der GMT-Offset je nachdem, welche Zeitzone gerade für diesen geografischen Standort aktiv ist.

Aktualisieren Klicken Sie auf Aktualisieren, um den Titel zu aktualisieren.

### 3.2 **Spalten**

Einige Spalten in der Workflows-Tabelle sind standardmäßig aktiviert, während andere ausgeblendet und aktiviert werden müssen. Je nach konfigurierter Spaltenreihenfolge werden die ersten Spalten angezeigt, während die Tabelle möglicherweise seitwärts gescrollt werden muss, um andere aktivierte Spalten anzuzeigen. Die Standardreihenfolge und Sichtbarkeitseinstellung der Spalten auf der Workflows-Seite ist wie folgt:

Titel - _Standard_ Der Titel des Workflows

Erstellt von - _Standard_ Das Mitglied, das den Workflow erstellt hat.

Erstellt am - _Standard_ Das Datum und die Uhrzeit, zu der der Workflow erstellt wurde

Status - _Standard_ Der Status des Workflows
