# Modelle als Dokumente

Bisher war es möglich, IFC-Dateien an zwei verschiedenen Orten in Catenda Hub hochzuladen. Mit der Funktion _Modelle als Dokumente_ werden diese beiden Orte für Modelldateien in eine nahtlose Funktion zusammengeführt. Wenn Sie ein Modell im Bereich Modelle erstellen, wird ein Dokument verknüpft und im Bereich Dokumente erstellt. Wenn Sie ein IFC-Dokument hochladen, können Sie die Schaltfläche "Modell erstellen" verwenden, um ein Modell im Bereich Modelle zu verknüpfen und zu erstellen. Mit dieser Funktion können Modelle im Bereich Modelle wie Dokumente behandelt werden, während Modelle im Bereich Dokumente wie Modelle behandelt werden können.

## 1. **Vorher/Nachher-Migration – Hauptunterschiede**

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e8e8e880; width: 126px; padding: 8px;"><h1 id="h_3632d3cc1b"></h1></td><td style="background-color: #e8e8e880; width: 262px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_2093155130"><b>Vorher</b></h2></td><td style="background-color: #e8e8e880; width: 248px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_d5cfcbcb2d"><b>Nachher</b></h2></td></tr><tr><td style="background-color: #e8e8e880; width: 126px; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right"><b>Hauptverhalten</b></p></td><td style="width: 262px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Modelle existierten nur im Bereich Modelle. Der Benutzer musste die gleiche IFC-Datei sowohl in den Bereich Dokumente als auch in den Bereich Modelle hochladen.</p></td><td style="width: 248px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Modelle werden aus IFC-Dateien erstellt, die im Bereich Dokumente hochgeladen werden, wenn der Benutzer dies anfordert. Die IFC-Datei und das zugehörige Modell werden dann verknüpft.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right"><b>Benutzeroberfläche</b></p></td><td style="width: 262px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Unterschiedlich</b> vom Bereich Dokumente und zeigte weniger Informationen, im Grunde nur eine Liste von Modellen.</p></td><td style="width: 248px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Gleich</b> wie der Bereich Dokumente: eine anpassbare Tabelle mit zugehörigen Metadaten.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right"><b>Zugriffsrechte</b></p></td><td style="width: 262px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Konnten nicht angewendet werden</b> auf Modelle</p></td><td style="width: 248px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Können angewendet werden</b> auf Modelle aus ihrem zugehörigen Dokument im Bereich Dokumente</p></td></tr></tbody></table></div>

## 2. **Vertraut, aber anders**

Jetzt, da die beiden Bereiche verknüpft sind, ist es wichtig zu beachten, dass es immer noch einige wesentliche Unterschiede zwischen dem Bereich Modelle und dem Bereich Dokumente gibt. Im Bereich Modelle können Sie alle Modell-Dokumente in einer Liste sehen. Hier sehen Sie Ihre Modell-Dokumente so, wie sie im 3D-Viewer verwendet werden. Im Bereich Dokumente können Sie Dokument-Modelle in Ihrer Dokumentstruktur sehen. Hier sehen Sie Ihre Dokument-Modelle so, wie sie in Ihrer gemeinsamen Datenumgebung verwendet werden. Alle Modelle sind mit ihrem eigenen Dokument verknüpft und Funktionen aus beiden Bereichen können sowohl im Bereich Modelle als auch im Bereich Dokumente verwendet werden.

## 3. **Änderungen im Bereich Modelle**

Mit Modelle als Dokumente hat sich die Darstellung des Bereichs Modelle geändert. Statt Menüelemente für jedes Modell anzuzeigen, werden diese jetzt in einer durchsuchbaren Tabelle angezeigt.

Im Bereich Modelle können Sie die folgenden Änderungen finden:

### 3.1 **Modelltabelle**

Die neue Modelltabelle kann ungefähr so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/01-model-table.png)

### 3.2 **Spalten**

Die Modellliste hat Spalten, die die meisten Informationen anzeigen, die Sie über Ihre Modelle wissen müssen.

_Name_ Der Name des Modell-Dokuments. Der Modellname ist auch der Name, den Sie im Revisions-Selector in der 3D-Ansicht sehen.

**Dokumentname** Der Name des Dokument-Modells im Bereich Dokumente

**Revisionsname** Der Name der neuesten Revision

### 3.3 **Zugangskontrolle**

Wenn ein Modell für Sie im Bereich Dokumente eingeschränkt wurde, sehen Sie es weder im Bereich Dokumente noch in der Modelltabelle oder im Revisions-Selector.

### 3.4 **Tabellenelemente auswählen**

Mit der Modelltabelle können Sie jetzt einen Bereich von Modellen auswählen, indem Sie die Umschalttaste gedrückt halten. Sie können Modelle auch zu Ihrer Auswahl hinzufügen oder entfernen, indem Sie die Strg-Taste gedrückt halten.

### 3.5 **Aktionsschaltflächen**

In der Vergangenheit war die einzige Aktion, die Sie für ausgewählte Modelle ausführen konnten, das Öffnen dieser Modelle in 3D. Jetzt können Sie die 2D-Ansicht Ihrer ausgewählten Modelle herunterladen, entfernen und öffnen. Wenn Sie ein Modell löschen, das mit einem Dokument verbunden ist, verliert das Dokument die Modellverbindung, aber das Dokument bleibt im Bereich Dokumente.

### 3.6 **Zugriff auf Dokument-Modelle steuern**

**Ein Modell-Dokument erstellen** Wenn Sie ein Modell mit der Schaltfläche "Modell erstellen" im Bereich Modelle erstellen, werden Sie aufgefordert, auszuwählen, wo das verknüpfte Dokument-Modell im Bereich Dokumente landen soll. Im Dialogfeld "Modell erstellen" können Sie dem Modell auch einen Namen geben. Das resultierende verknüpfte Dokument-Modell hat den gleichen Namen wie das Modell bei seiner Erstellung. Catenda Hub merkt sich den Ordner, den Sie zuletzt gewählt haben, und wählt ihn automatisch aus, wenn Sie das nächste Mal ein Modell-Dokument erstellen.

Wenn Ihr Projekt ohne Modelle als Dokumente begonnen hat, ist ein Ordner namens "Modelle" in Ihrer Ordnerstruktur erschienen. Der Ordner "Modelle", der erscheint, enthält alle Dokument-Modelle, die mit Modell-Dokumenten im Bereich Modelle verknüpft sind. Dokument-Modelle können aus diesem Ordner an beliebige Stellen im Bereich Dokumente verschoben werden, auf die Sie Zugriff haben. Dokument-Modelle im Ordner "Modelle" können auch bei Bedarf gelöscht (und wiederhergestellt) werden. Die Dokument-Modelle müssen nicht im Ordner sein und der Ordner "Modelle" kann bei Bedarf gelöscht werden.

**Eine Modell-Revision erstellen** Um neue Revisionen zu einem Modell hochzuladen, benötigen Sie mindestens Schreibzugriff auf das Dokument-Modell. Neue Revisionen des Modells können zum Dokument hinzugefügt werden und umgekehrt.

> **Hinweis:** Revisionskommentare wurden deaktiviert und können jetzt optional mit [benutzerdefinierten Feldern auf Revisionen](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) aktiviert werden.

**Eine Modell-Revision herunterladen** Sie benötigen mindestens Lesezugriff auf das Dokument-Modell, um das Modell herunterladen zu können.

### 3.7 **Menü mit Informationen auf der rechten Seite**

Ein Menü mit Informationen auf der rechten Seite ist verfügbar, wenn ein Modell ausgewählt ist.

**Dokumentfeld** In diesem Menü sehen Sie Ihre Modellinformationen sowie ein grau hinterlegtes Feld, das zum Dokument-Modell im Bereich Dokumente verknüpft ist, das mit diesem Modell-Dokument verknüpft ist. Klicken Sie auf das Dokumentfeld, um das Dokument-Modell zu öffnen, das mit diesem Modell verknüpft ist.

**Modell-Etiketten** Sie können hier nun auch Etiketten zu Ihren Modellen hinzufügen.

**Modellstatus** Falls Statussymbole in den Dokumenteinstellungen konfiguriert wurden, können Sie hier einen Status für Ihr Modell konfigurieren.

**Modelltransformation** Wenn Sie dieses Modell in 3D geöffnet haben, können Sie hier die Modelltransformation konfigurieren.

## 4. **Änderungen im Bereich Dokumente**

Während die visuellen Änderungen nicht so offensichtlich sind wie im Bereich Modelle, gibt es einige Dinge, die sich im Bereich Dokumente ändern werden, wenn "Modelle als Dokumente" aktiviert ist. So können die Dokument-Modelle im Bereich Dokumente aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/02-documents-section-changes.png)

Im Bereich Dokumente können Sie die folgenden Änderungen finden:

### 4.1 **Modellfilter**

Sobald Sie Modelle im Bereich Modelle haben, wird ein Modellfilter in Ihrem Filtermenü angezeigt. Mit diesem Filter können Sie Dokument-Modelle, die erstellt wurden, anzeigen oder ausblenden.

### 4.2 **Spalten**

**Symbol** Sie können ein Dokument-Modell von einem normalen Dokument durch das Modellabzeichen in der unteren rechten Ecke des Dokument-Modell-Symbols unterscheiden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/03-columns.png)

**Name** Der Name des Dokuments

**Modellname** Der Name des Modells. Wenn Ihr IFC-Dokument nicht mit einem Modell verknüpft wurde, wird hier eine Schaltfläche "Modell erstellen" angezeigt.

**Revisionsname** Der Name der neuesten Revision im Modell

**Viewer** Eine Spalte mit Schaltflächen zum Öffnen jedes einzelnen Dokument-Modells im 3D-Viewer. Das Öffnen von Dokument-Modellen im 3D-Viewer ist nur möglich, wenn das Dokument mit einem Modell verknüpft wurde.

### 4.3 **Aktionsschaltflächen**

Laden Sie die 2D/3D-Ansichten ausgewählter Modelle im jeweiligen Viewer herunter, löschen Sie sie oder laden Sie sie, indem Sie ein oder mehrere Modelle auswählen.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-9e345595c719.png" width="310"/>    <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-959af958f499.png" width="310"/>

Das bedeutet, dass Sie mehrere Modelle auf einmal löschen können, anstatt eins nach dem anderen wie zuvor. Wenn Sie ein Dokument löschen, das mit einem Modell verbunden ist, müssen Sie eine Warnung genehmigen, dass das mit dem Dokument verbundene Modell auch gelöscht wird.

> **Hinweis:** Das bedeutet, dass Sie ein Modell löschen können, ohne die Daten zu verlieren. (Gelöschte Dokumente können wiederhergestellt werden)

### 4.4 **Zugriff auf Modell-Dokumente steuern**

**Dokument-Modelle erstellen** Um neue Revisionen zu einem Modell hochzuladen, benötigen Sie mindestens Schreibzugriff auf das Dokument-Modell. Dies tun Sie, indem Sie ein Modell im Aktionsmenü eines Dokuments erstellen. Danach sehen Sie das Dokument als Modell im Bereich Modelle. Das Modell-Dokument im Bereich Modelle hat den gleichen Namen wie das Dokument-Modell, obwohl diese später jeweils geändert werden können, während sie verknüpft bleiben. Neue Revisionen des Modells können als Revisionen zum Dokument hinzugefügt werden und umgekehrt.

> **Hinweis:** Das bedeutet, dass Sie Modelle aus mehreren IFC-Dateien gleichzeitig erstellen können, anstatt sie nacheinander hochzuladen

**Revisionen zu Dokument-Modellen hochladen** Sie benötigen mindestens Schreibzugriff auf das Dokument-Modell, um neue Revisionen zum Modell hochladen zu können. Dies bedeutet, dass Sie die Multi-Upload-Funktion verwenden können, um IFC-Dateien gleichzeitig auf mehrere Dokument-Modelle hochzuladen.

**Dokument-Modelle herunterladen** Sie benötigen mindestens Lesezugriff auf das Dokument-Modell, um das Modell herunterladen zu können. Dies bedeutet, dass Sie den Zugriff konfigurieren können, um das Herunterladen einzelner Modelle zu ermöglichen, anstatt nur alle oder keine Modelle.

### 4.5 **Auffindbarkeit**

Dokument-Modelle können nun wie jedes andere Dokument im Bereich Dokumente gefunden werden.

- Dokument-Modelle können in Ordnern strukturiert werden, um das Navigieren zu einem bestimmten Satz von Modellen zu erleichtern.
- Etiketten können zu Dokument-Modellen hinzugefügt werden, um alle Dokument-Modelle zu finden, die zu einem bestimmten Typ gehören.
- [Benutzerdefinierte Felder können zu Ordnern hinzugefügt werden](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents), in denen Dokumente hochgeladen werden, um nach Metadatenwerten zu suchen, die mit jedem Dokument-Modell verknüpft sind
- [Benutzerdefinierte Felder können zu Ordnern hinzugefügt werden](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents), in denen Dokumente hochgeladen werden, um Informationen zu jeder Revision in jedem Dokument-Modell hinzufügen zu können.

Siehe [hier](https://support.catenda.com/en/articles/8542598-structuring-documents#h_7838a63c73) für Vorschläge, wie Sie Ihre Dokument-Modelle strukturieren können, damit sie leicht zu finden sind.

### 4.6 **Freigegebene IFC-Dateien genehmigen**

IFC-Dateien können jetzt als gemeinsame Revisionen hochgeladen werden, damit sie einen Genehmigungsprozess durchlaufen können, bevor sie veröffentlicht werden.

### 4.7 **Benennungskonvention mit Dokument-Modellen**

Namen im Bereich Dokumente enthalten häufig komprimierte Abkürzungen, um den Dokumentnamen kurz zu halten und gleichzeitig einige Informationen darüber zu zeigen, worum es in diesem Dokument geht. Der Name des Dokument-Modells kann sich daher vom Namen des Modell-Dokuments unterscheiden, um ihn in Einklang mit den anderen Dokumenten im Bereich Dokumente zu halten und gleichzeitig einen leicht zu lesenden Namen zur Verwendung im 3D-Viewer im Bereich Modelle zu bewahren. Der Dokumentname des Dokument-Modells ist der Name, der beim Hochladen von Dokumenten in den Bereich Dokumente erkannt wird. Wenn der Name dem Dokument ähnelt oder gleich ist, wird automatisch eine neue Revision erstellt, genau wie bei anderen Dokumenten.

Da sich Dokument-Modelle genauso wie reguläre Modelle verhalten, ist es jetzt möglich, die Benennungskonvention mit Dokument-Modellen zu verwenden, um sicherzustellen, dass die Projektbeteiligten dem Dokument beim Hochladen den richtigen Namen geben.
