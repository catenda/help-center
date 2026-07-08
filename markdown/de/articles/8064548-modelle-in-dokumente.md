# Modelle als Dokumente

Früher war es möglich, IFC-Dateien an zwei verschiedenen Orten auf Catenda Hub hochzuladen. Mit der Funktion _Modelle als Dokumente_ werden diese beiden Orte für Modelldateien in eine nahtlose Funktion zusammengeführt. Wenn Sie ein Modell im Bereich "Modelle" erstellen, wird automatisch ein entsprechendes Dokument im Bereich "Dokumente" verlinkt und erstellt. Wenn Sie ein IFC-Dokument hochladen, können Sie die Schaltfläche "Modell erstellen" verwenden, um ein Modell im Bereich "Modelle" zu verlinken und zu erstellen. Mit dieser Funktion können Modelle im Bereich "Modelle" wie Dokumente behandelt werden, während Modelle im Bereich "Dokumente" genau wie Modelle behandelt werden können.

## 1. **Vor/Nach der Migration - Hauptunterschiede**

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e8e8e880; width: 126px;"><h1 id="h_3632d3cc1b"></h1></td><td style="background-color: #e8e8e880; width: 262px;"><h2 class="intercom-align-center" id="h_2093155130"><b>Vorher</b></h2></td><td style="background-color: #e8e8e880; width: 248px;"><h2 class="intercom-align-center" id="h_d5cfcbcb2d"><b>Nachher</b></h2></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Hauptverhalten</b></p></td><td style="width: 262px;"><p>Modelle existierten nur im Bereich "Modelle". Der Benutzer musste dieselbe IFC-Datei sowohl in den Bereich "Dokumente" als auch "Modelle" hochladen.</p></td><td style="width: 248px;"><p>Modelle werden auf Anfrage des Benutzers aus IFC-Dateien erstellt, die in den Bereich "Dokumente" hochgeladen wurden. Die IFC-Datei und das zugehörige Modell werden dann verlinkt.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Benutzeroberfläche</b></p></td><td style="width: 262px;"><p><b>Anders</b> als der Bereich "Dokumente" und zeigt weniger Informationen an, im Grunde nur eine Liste von Modellen.</p></td><td style="width: 248px;"><p><b>Gleich</b> wie der Bereich "Dokumente": eine anpassbare Tabelle mit zugehörigen Metadaten.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Zugriffsrechte</b></p></td><td style="width: 262px;"><p><b>Konnte nicht angewendet werden</b> auf Modelle</p></td><td style="width: 248px;"><p><b>Kann angewendet werden</b> auf Modelle aus ihrem zugehörigen Dokument im Bereich "Dokumente"</p></td></tr></tbody></table></div>

## 2. **Bekannt, aber anders**

Jetzt, da die beiden Bereiche verlinkt wurden, ist es wichtig zu beachten, dass es immer noch einige Unterschiede zwischen den Bereichen "Modelle" und "Dokumente" gibt. Im Bereich "Modelle" können Sie alle Modell-Dokumente in einer Liste zusammengefasst sehen. Hier sehen Sie Ihre Modell-Dokumente so, wie sie im 3D-Viewer verwendet werden. Im Bereich "Dokumente" können Sie Dokument-Modelle in Ihrer Dokumentstruktur sehen. Hier sehen Sie Ihre Dokument-Modelle so, wie sie in Ihrer gemeinsamen Datenumgebung verwendet werden. Alle Modelle sind mit ihrem eigenen Dokument verlinkt, und Funktionen aus beiden Bereichen können sowohl im Bereich "Modelle" als auch im Bereich "Dokumente" verwendet werden.

## 3. **Änderungen im Bereich "Modelle"**

Mit Modelle als Dokumente hat sich das Aussehen des Bereichs "Modelle" geändert. Anstelle von Menüelementen für jedes Modell werden diese nun in einer durchsuchbaren Tabelle angezeigt.

Im Bereich "Modelle" können Sie die folgenden Änderungen finden:

### 3.1 **Modell-Tabelle**

Die neue Modell-Tabelle könnte etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/01-model-table.png)

### 3.2 **Spalten**

Die Modell-Liste hat Spalten, die die meisten Informationen anzeigen, die Sie über Ihre Modelle wissen müssen.

_Name_ Der Name des Modell-Dokuments. Der Modellname ist auch der Name, den Sie in der Revisionsauswahl in der 3D-Ansicht sehen.

**Dokumentname** Der Name des Dokument-Modells im Bereich "Dokumente"

**Revisionsname** Der Name der neuesten Revision

### 3.3 **Zugriffskontrolle**

Wenn ein Modell für Sie im Bereich "Dokumente" eingeschränkt wurde, können Sie es weder im Bereich "Dokumente" noch in der Modell-Tabelle oder in der Revisionsauswahl sehen.

### 3.4 **Tabellenelemente auswählen**

Mit der Modell-Tabelle können Sie jetzt eine Reihe von Modellen auswählen, indem Sie die Umschalttaste gedrückt halten. Sie können Modelle auch aus Ihrer Auswahl hinzufügen oder entfernen, indem Sie die Strg-Taste gedrückt halten.

### 3.5 **Aktionsschaltflächen**

In der Vergangenheit war die einzige Aktion, die Sie mit ausgewählten Modellen durchführen konnten, das Öffnen dieser Modelle in 3D. Jetzt können Sie die 2D-Ansicht Ihrer ausgewählten Modelle herunterladen, entfernen und öffnen. Wenn Sie ein mit einem Dokument verbundenes Modell löschen, verliert das Dokument die Modellverbindung, aber das Dokument bleibt im Bereich "Dokumente".

### 3.6 **Zugriff auf Dokument-Modelle kontrollieren**

**Modell-Dokument erstellen** Wenn Sie mit der Schaltfläche "Modell erstellen" im Bereich "Modelle" ein Modell erstellen, werden Sie aufgefordert auszuwählen, wo Sie das verlinkte Dokument-Modell im Bereich "Dokumente" ablegen möchten. Im Dialogfeld "Modell erstellen" können Sie dem Modell auch einen Namen geben. Das resultierende verlinkte Dokument-Modell erhält bei der Erstellung denselben Namen wie das Modell. Catenda Hub merkt sich den zuletzt gewählten Ordner und wählt ihn beim nächsten Mal automatisch aus, wenn Sie ein Modell-Dokument erstellen.

Wenn Ihr Projekt ohne Modelle als Dokumente begonnen hat, ist ein Ordner namens "Modelle" in Ihrer Ordnerstruktur erschienen. Der Ordner "Modelle", der angezeigt wird, enthält alle Dokument-Modelle, die mit Modell-Dokumenten im Bereich "Modelle" verlinkt sind. Dokument-Modelle können aus diesem Ordner an eine beliebige Stelle im Bereich "Dokumente" verschoben werden, auf die Sie Zugriff haben. Dokument-Modelle im Ordner "Modelle" können auch gelöscht (und wiederhergestellt) werden, wenn gewünscht. Die Dokument-Modelle müssen nicht im Ordner sein, und der Ordner "Modelle" kann bei Bedarf gelöscht werden.

**Modell-Revision erstellen** Um neue Revisionen zu einem Modell hochzuladen, benötigen Sie mindestens Schreibzugriff auf das Dokument-Modell. Neue Revisionen des Modells können zum Dokument hinzugefügt werden und umgekehrt.

> **Hinweis:** Revisionskommentare wurden deaktiviert und können jetzt optional mit [benutzerdefinierten Feldern auf Revisionen](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) aktiviert werden.

**Modell-Revision herunterladen** Um das Modell herunterladen zu können, benötigen Sie mindestens Lesezugriff auf das Dokument-Modell.

### 3.7 **Informationsmenü rechts**

Ein Informationsmenü auf der rechten Seite ist verfügbar, wenn ein Modell ausgewählt ist.

**Dokumentfeld** In diesem Menü sehen Sie Ihre Modellinformationen sowie ein graues Feld, das zum Dokument-Modell im Bereich "Dokumente" verlinkt ist, das mit diesem Modell-Dokument verlinkt ist. Klicken Sie auf das Dokumentfeld, um das Dokument-Modell zu öffnen, das mit diesem Modell verlinkt ist.

**Modell-Etiketten** Sie können hier jetzt auch Etiketten zu Ihren Modellen hinzufügen.

**Modell-Status** Wenn Statuse in den Dokumenteinstellungen konfiguriert wurden, können Sie hier einen Status für Ihr Modell konfigurieren.

**Modelltransformation** Wenn Sie dieses Modell in 3D geöffnet haben, können Sie hier die Modelltransformation konfigurieren.

## 4. **Änderungen im Bereich "Dokumente"**

Obwohl die visuellen Änderungen nicht so offensichtlich sind wie im Bereich "Modelle", gibt es einige Dinge, die sich im Bereich "Dokumente" ändern werden, wenn Modelle als Dokumente aktiviert werden. So können die Dokument-Modelle im Bereich "Dokumente" aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/02-documents-section-changes.png)

Im Bereich "Dokumente" können Sie die folgenden Änderungen finden:

### 4.1 **Modell-Filter**

Sobald Sie Modelle im Bereich "Modelle" haben, wird ein Modell-Filter in Ihrem Filtermenü angezeigt. Mit diesem Filter können Sie alle erstellten Dokument-Modelle anzeigen oder verbergen.

### 4.2 **Spalten**

**Symbol** Sie können ein Dokument-Modell von einem normalen Dokument durch das Modell-Abzeichen in der unteren rechten Ecke des Dokument-Modell-Symbols unterscheiden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/03-columns.png)

**Name** Der Name des Dokuments

**Modellname** Der Name des Modells. Wenn Ihr IFC-Dokument nicht mit einem Modell verlinkt wurde, wird hier eine Schaltfläche "Modell erstellen" angezeigt.

**Revisionsname** Der Name der neuesten Revision im Modell

**Viewer** Eine Spalte mit Schaltflächen zum Öffnen jedes einzelnen Dokument-Modells im 3D-Viewer. Das Öffnen von Dokument-Modellen im 3D-Viewer ist nur möglich, wenn das Dokument mit einem Modell verlinkt wurde.

### 4.3 **Aktionsschaltflächen**

Laden Sie herunter, löschen Sie oder laden Sie die 2D-/3D-Ansichten ausgewählter Modelle im jeweiligen Viewer, indem Sie ein oder mehrere Modelle auswählen.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-9e345595c719.png" width="310"/>    <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-959af958f499.png" width="310"/>

Dies bedeutet, dass Sie mehrere Modelle auf einmal löschen können, anstatt sie wie zuvor einzeln zu löschen. Wenn Sie ein Dokument löschen, das mit einem Modell verbunden ist, müssen Sie eine Warnung bestätigen, dass auch das mit dem Dokument verbundene Modell gelöscht wird.

> **Hinweis:** Dies bedeutet, dass Sie ein Modell löschen können, ohne Daten zu verlieren. (Gelöschte Dokumente können wiederhergestellt werden)

### 4.4 **Zugriff auf Modell-Dokumente kontrollieren**

**Dokument-Modelle erstellen** Um neue Revisionen zu einem Modell hochzuladen, benötigen Sie mindestens Schreibzugriff auf das Dokument-Modell. Sie tun dies, indem Sie ein Modell im Aktionsmenü eines Dokuments erstellen. Danach werden Sie das Dokument als Modell im Bereich "Modelle" sehen. Das Modell-Dokument im Bereich "Modelle" hat den gleichen Namen wie das Dokument-Modell, obwohl diese Namen später jeweils geändert werden können, während sie verlinkt bleiben. Neue Revisionen des Modells können als Revisionen des Dokuments hinzugefügt werden und umgekehrt.

> **Hinweis:** Dies bedeutet, dass Sie Modelle aus mehreren IFC-Dateien gleichzeitig erstellen können, anstatt sie einzeln hochladen zu müssen

**Revisionen in Dokument-Modelle hochladen** Um neue Revisionen in das Modell hochzuladen, benötigen Sie mindestens Schreibzugriff auf das Dokument-Modell. Dies bedeutet, dass Sie die Mehrdatei-Upload-Funktion verwenden können, um IFC-Dateien gleichzeitig in mehrere Dokument-Modelle hochzuladen

**Dokument-Modelle herunterladen** Um das Modell herunterladen zu können, benötigen Sie mindestens Lesezugriff auf das Dokument-Modell. Dies bedeutet, dass Sie den Zugriff so konfigurieren können, dass der Download einzelner Modelle anstelle aller oder keiner Modelle zulässig ist.

### 4.5 **Auffindbarkeit**

Dokument-Modelle können jetzt wie jedes andere Dokument im Bereich "Dokumente" gefunden werden.

- Dokument-Modelle können in Ordnern strukturiert werden, um die Navigation zur richtigen Gruppe von Modellen zu vereinfachen.
- Es können Etiketten zu Dokument-Modellen hinzugefügt werden, um alle Dokument-Modelle eines bestimmten Typs zu finden.
- [Benutzerdefinierte Felder können zu Ordnern hinzugefügt werden](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents), in die Dokumente hochgeladen werden, um nach Metadatenwerten zu suchen, die mit jedem Dokument-Modell verknüpft sind
- [Benutzerdefinierte Felder können zu Ordnern hinzugefügt werden](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents), in die Dokumente hochgeladen werden, um Informationen zu jeder Revision in jedem Dokument-Modell hinzufügen zu können.

Siehe [hier](https://support.catenda.com/en/articles/8542598-structuring-documents#h_7838a63c73) für Vorschläge zur Strukturierung Ihrer Dokument-Modelle, damit sie leicht zu finden sind.

### 4.6 **Freigegebene IFC-Dateien genehmigen**

IFC-Dateien können jetzt als freigegebene Revisionen hochgeladen werden, damit sie einen Genehmigungsprozess durchlaufen können, bevor sie veröffentlicht werden.

### 4.7 **Namenskonvention mit Dokument-Modellen**

Namen im Bereich "Dokumente" enthalten häufig komprimierte Abkürzungen, um den Dokumentnamen kurz zu halten und gleichzeitig Informationen über den Inhalt des Dokuments anzuzeigen. Der Name des Dokument-Modells kann daher vom Namen des Modell-Dokuments abweichen, um ihn in Einklang mit den anderen Dokumenten im Bereich "Dokumente" zu bringen und gleichzeitig einen leicht zu lesenden Namen für die Verwendung im 3D-Viewer im Bereich "Modelle" beizubehalten. Der Dokumentname des Dokument-Modells ist der Name, der beim Hochladen von Dokumenten in den Bereich "Dokumente" erkannt wird. Wenn der Name dem Dokument ähnlich oder gleich ist, wird automatisch eine neue Revision erstellt, genau wie bei anderen Dokumenten.

Da sich Dokument-Modelle genauso wie normale Modelle verhalten, ist es jetzt möglich, die Namenskonvention mit Dokument-Modellen zu verwenden, um sicherzustellen, dass die Projektbeteiligten dem Dokument beim Hochladen den richtigen Namen geben.
