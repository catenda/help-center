# Fehlerbehebung auf der Seite "Genehmigungen"

## 1. **Neue Genehmigungsanfrage einreichen**

Wenn eine neue Genehmigungsanfrage zur Überprüfung eingereicht wird, wobei mehr als 1000 Dokumente über die Schaltfläche "Dokumente hinzufügen" hinzugefügt werden, wird der folgende Fehler angezeigt:

![New approval request error Workflow default workflow Submitter Title](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/01-submitting-a-new-approval-request.png)

Es ist nur möglich, den Dialog für neue Genehmigungsanfragen mit bis zu 1000 Dokumenten auf einmal einzureichen. Um eine Genehmigungsanfrage mit mehr als 1000 Dokumenten einzureichen, fügen Sie zunächst bis zu 1000 Dokumente zum Dialog für neue Genehmigungsanfragen hinzu und speichern Sie diese als Entwurf. Gehen Sie zur Entwurfsgenehmigungsseite des Dokuments und fügen Sie so viele Dokumente hinzu, wie gewünscht, bevor Sie die Genehmigungsanfrage einreichen.

## 2. **Registerkarte "Übersicht" - Schließen einer Genehmigungsanfrage**

Beim Schließen einer Genehmigung kann die Veröffentlichung fehlschlagen. In der [Registerkarte "Übersicht"](https://support.catenda.com/en/articles/12495126-overview-tab-in-an-approval-request) der Genehmigung kann dann folgendes angezeigt werden:

![Publishing failed Published 1 document. Failed to update 1 document view details](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/02-overview-tab-closing-an-approval-request.png)

### 2.1 **Eine veröffentlichte Revision existiert bereits**

Es ist nur möglich, freigegebene Revisionen in Dokumenten zu veröffentlichen, bei denen die neueste Revision eine freigegebene Revision ist. Wenn die Revision in der Genehmigung oder eine andere freigegebene Revision nach der zuvor veröffentlichten Revision veröffentlicht wurde und eine neue Hauptrevisionsnummer erstellt wurde, kann diese Revision nicht diese nächste Hauptrevisionsnummer erhalten, da diese bereits existiert und fehlschlagen wird. Eine freigegebene Revision könnte als Ergebnis des Schließens einer anderen Genehmigungsanfrage oder durch Verwendung der Veröffentlichungsaktion in der Dokumenttabelle oder in den Revisionsinformationen im rechten Menü einer Revision veröffentlicht worden sein.

## 3. **Registerkarte "Dokumente"**

### 3.1 **Dokument nicht gefunden**

Wenn ein Dokument, das Teil einer Genehmigung ist, gelöscht wird, kann es nicht mehr gefunden werden und der Inhalt des Dokuments wird nicht mehr auf der Dateiüberprüfungsseite angezeigt. So kann die Registerkarte "Dokumente" aussehen, wenn ein Dokument, das Teil einer Genehmigung ist, gelöscht wurde:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/03-document-not-found.png)

Dokumente, die zu einer Genehmigungsanfrage hinzugefügt und später gelöscht wurden, können entweder von einem Administrator wiederhergestellt oder aus der Genehmigungsanfrage verworfen werden.

### 3.2 **Zurückgezogene Revision**​

Wenn eine Dokumentrevision, die Teil einer Genehmigung ist, zurückgezogen wird, wird die Revisionsnummer durchgestrichen und der Inhalt des Dokuments wird nicht mehr auf der Dateiüberprüfungsseite angezeigt. So kann die Registerkarte "Dokumente" aussehen, wenn ein Dokument, das Teil einer Genehmigung ist, gelöscht wurde:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/04-withdrawn-revision.png)

Dokumentrevisionen, die zu einer Genehmigungsanfrage hinzugefügt und später zurückgezogen wurden, können aus der Genehmigungsanfrage verworfen werden.
