# Filterung auf der Dokumentseite

Die Such- oder Filteroption ist oben im Fenster zu sehen. Durch Eingabe des Dokumentnamens oder des Namens einer Etikett, die an ein Dokument angeheftet ist, können die Zeilen in der Dokumenttabelle eingegrenzt werden. So kann das Such- oder Filtermenü auf der Dokumentseite aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aa862mj2/01-intro.png)

## 1. **Filter**

Klicken Sie auf die Filterschaltfläche oben links, um ein Panel auf der linken Seite anzuzeigen. Wenn ein Filter angewendet wird, ändert sich die im Browser sichtbare URL entsprechend. In diesem Artikel werden Filter wie folgt angezeigt: _Filtername im Menü_ - `Filtername in URL=Filteroption in URL`

**Standardfilter** Der Standardfilter ist anfangs nicht in der URL sichtbar. Wenn die Seite zum ersten Mal aufgerufen wird, wird der folgende Filter angewendet. Registerkarte Arbeitsbereich - `v=all`

### 1.1 **Aktuellen Filter speichern und teilen**

Gehen Sie zur URL einer gefilterten Seite, um diese Seite mit angewendetem Filter zu laden. Die angewendeten Filter können oben im Filtermenü gespeichert werden. Klicken Sie [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link), um mehr über das Speichern und Teilen von Filtern zu erfahren. Beachten Sie, dass es im Gegensatz zu anderen Filtermenüs nicht möglich ist, persönliche Filter oben im Filtermenü auf der Genehmigungsseite zu speichern.

### 1.2 **Leere Filter ausblenden**

Klicken Sie [hier](https://support.catenda.com/en/articles/8551755-saving-filters), um mehr über die Begrenzung von Filterergebnissen zu erfahren.

### 1.3 **Registerkarten**

Registerkarte Arbeitsbereich - `v=all` Registerkarte Veröffentlicht - `v=published`

### 1.4 **Links**

Verlinkt - `associations=exists&subFolders=true` Filter für Dokumente, die mit Modelobjekten im 3D-Viewer verlinkt sind.

Nicht verlinkt - `associations=does-not-exist&subFolders=true` Filter für Dokumente, die nicht mit Modelobjekten im 3D-Viewer verlinkt sind.

Mit ausgewählten Objekten verlinkt - `link=backlink&subFolders=true` Wenn das 3D-Panel nicht bereits offen ist, wird es geöffnet. Wählen Sie Objekte aus einem Modell im 3D-Viewer aus, um nach Themen zu filtern, die mit den ausgewählten Objekten verlinkt sind.

### 1.5 **Status (letzte Überarbeitete) - Status nur Workflow**

Veröffentlicht - `documentStatus=published&subFolders=true&documentType=file` Status fehlt - `documentStatus=published-without-status&subFolders=true` Projektveröffentlichungsstatus - `documentStatus=<GUID>&subFolders=true` Freigegeben - `documentStatus=shared&subFolders=true&documentType=file` Freigegebene Status sind nur in der Registerkarte Arbeitsbereich verfügbar Projektfreigabestatus - `documentStatus=<GUID>&subFolders=true` Keine Überarbeitete - `documentStatus=no-stage&subFolders=true`

### 1.6 **Entwürfe - Status nur Workflow**

Neue Entwürfe vorhanden - `newDrafts=exists&subFolders=true` Name des Entwurfsstatus - `newDrafts=<Draft status GUID>&subFolders=true` Wenn mehrere Entwurfsstatus vorhanden sind, kann auf jeden Entwurfsstatus einzeln gefiltert werden. Keine neuen Entwürfe - `newDrafts=does-not-exist&subFolders=true`

### 1.7 **Modelle**

Ist Modell - `model=is-model&subFolders=true` Ist kein Modell - `model=is-not-model&subFolders=true`

### 1.8 **Dokument erstellt von**

Mitgliedername - `owner=<Member GUID>&subFolders=true`

### 1.9 **Überarbeitete erstellt von**

Mitgliedername - `revisionCreatedBy=<GUID>&subFolders=true`

### 1.10 **Veröffentlicht von**

Mitgliedername - `publishedBy=<Member GUID>&subFolders=true`

### 1.11 **Datumsfilter**

Veröffentlicht - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Klicken Sie auf Daten auswählen, um die Daten auszuwählen, in deren Bereich Sie suchen möchten. Klicken Sie [hier](https://support.catenda.com/en/articles/6511685-date-filter), um mehr über den Datumsfilter zu erfahren.

### 1.12 **Genehmigungen offen - Status nur Workflow**

Name der Genehmigung - `approval=<Approval number>&subFolders=true`

### 1.13 **Dokumente - Etiketten**

Alle Etiketten, die nicht Teil einer Etikettgruppe sind, werden in einem Menü namens Dokumente angezeigt. Name der Etikett - `labels=<Label GUID>6&subFolders=true`

### 1.14 **Name der Etikettgruppe**

Pro Etikettgruppenname wird ein Menü angezeigt Name der Etikett - `labels=<Label GUID>6&subFolders=true`

Der Inhalt von benutzerdefinierten Feldern, deren Werte konfiguriert werden können, kann gefiltert werden, indem in der Such- oder Filterleiste eine Suchphrase eingegeben und der entsprechende Filter in dem empfohlenen Filter ausgewählt wird.

### 1.15 **Benutzerdefiniertes Feld**

_Benutzerdefiniertes Feld hat Wert_ - `custom-field-has-value-<Custom field GUID>=true` Mit der Option "Hat Wert" im Filtermenü können alle Themen gefiltert werden, die einen für dieses benutzerdefinierte Feld konfigurierten Wert haben. Benutzerdefinierte Feldtypen, die auf "Hat Wert" gefiltert werden können: Datum Dezimal Dropdown Ganzzahl Text

_Benutzerdefinierter Feldspezifischer Wert_ - `custom-field-item-<Custom field GUID>=<Value GUID>` Spezifische Werte in Feldern für Felder mit bis zu 10 Werten können gefiltert werden. Benutzerdefinierte Feldtypen, die aus dem Filtermenü auf spezifische Werte gefiltert werden können: Dropdown

Einige Werte in benutzerdefinierten Feldern, deren Werte konfiguriert werden können, können gefiltert werden. Filtern Sie nach Werten, indem Sie in der Such- oder Filterleiste eine Suchphrase eingeben und das entsprechende benutzerdefinierte Feld auswählen. Benutzerdefinierte Feldtypen, die in der Such- oder Filterleiste gefiltert werden können: Dezimal Dropdown Ganzzahl Text

_Benutzerdefiniertes Feld hat keinen Wert_ - `custom-field-has-value-<Custom field GUID>=false` Filtern Sie alle Themen, in denen ein benutzerdefiniertes Feld keinen Wert hat. Benutzerdefinierte Feldtypen, die auf keinen Wert gefiltert werden können: Datum Dezimal Dropdown Ganzzahl Text

> **Hinweis:** Benutzerdefinierte Felder, die als erforderlich festgelegt sind, haben immer einen Wert. Sie können daher nicht nach "Hat Wert" oder "Hat keinen Wert" suchen und können daher nicht für ein benutzerdefiniertes Feld gesucht werden, das als erforderlich festgelegt ist.

### 1.16 **Sammlungen**

Name der Sammlung - `collections=<GUID>&subFolders=true`

### 1.17 **Gelöscht**

Gelöscht - `deleted=deleted&subFolders=true` Siehe [hier](https://support.catenda.com/en/articles/4670249-undeleting-restoring-documents-or-folders), wie Sie nach gelöschten Dokumenten suchen

## 2. **Textsuche**

_Textsuche_ - `search=test&subFolders=true`

### 2.1 **Inhalte, auf die gesucht werden kann**

Dokumenttitel Ordnertitel

### 2.2 **Großschreibung**

Die Textsuche berücksichtigt keine Unterschiede zwischen Groß- und Kleinschreibung.

### 2.3 **Zeichenmengen**

Ein einzelnes Zeichen - Titel, die das gesuchte Zeichen enthalten, werden gefunden. Zwei Zeichen - Keine Ergebnisse. Drei oder mehr Zeichen - Titel, die ein einzelnes Wort haben, getrennt durch ein Trennzeichen wie ein Leerzeichen, das mit der Suchphrase übereinstimmt, werden in die Ergebnisse aufgenommen.

### 2.4 **Dateitypen**

Wenn der Titel eine Erweiterung enthält, kann die Erweiterung mit der normalen Textsuche gesucht werden. Suchen Sie die Dateierweiterung mit dem Punkt ein, um nach einem bestimmten Dateityp zu suchen. Wenn Sie beispielsweise nach .ifc suchen, können alle Dokumente mit .ifc im Titel gefunden werden.

## 3. **Sortieren**

Dokumente können durch Klicken auf die Kopfzeile jeder Spalte sortiert werden. Die Kopfzeile kann mehrmals angeklickt werden, um die Sortierung zu ändern oder zu deaktivieren.

_Titel, A-Z_ - Standard _Name, Z-A_ - `sort=name-desc` _Veröffentlicht, neueste zuerst_ - `sort=publishedAt-desc` _Veröffentlicht, älteste zuerst_ - `sort=publishedAt-asc` _Erstellt, neueste zuerst_ - `sort=createdAt-desc` _Erstellt, älteste zuerst_ - `sort=createdAt-asc`
