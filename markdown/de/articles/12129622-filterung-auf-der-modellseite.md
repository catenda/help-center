# Filterung auf der Modellseite

Die Such- oder Filteroption ist im oberen Bereich des Fensters sichtbar. Durch Eingabe des Modellnamens, des Namens einer an ein Modell angehefteten Etikett oder des Benutzernamens eines Mitglieds können die Zeilen in der Modelltabelle eingegrenzt werden. So kann das Such- oder Filtermenü auf der Modellseite aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qfd47nkw/01-intro.png)

In der Suchleiste können Sie nach jedem Modell suchen, das in der Modelltabelle verfügbar ist.

## 1. **Linkes Filterpanel**

Durch Anklicken der Filterschaltfläche wird ein Panel auf der linken Seite angezeigt. Aktivieren Sie die Kontrollkästchen, um die Suche einzugrenzen. Diese Filter können oben in der Filterliste gespeichert werden. Wenn einer dieser Filter angewendet wird, wird der Filtertext zu Ihrer URL hinzugefügt. Wenn die URL der gefilterten Seite freigegeben wird, sieht die Person, die sie öffnet, denselben Filter in demselben Ordner, wie er derzeit angezeigt wird, solange sie Zugriff darauf hat. Wenn einer der Filter im linken Panel mit der Maus über "Nur" bewegt wird, kann auf der rechten Seite des Filters geklickt werden, um alle anderen zuvor angewendeten Filter zu entfernen.

## 2. **Gespeicherte Filter**

Klicken Sie [hier](https://support.catenda.com/en/articles/8551755-saving-filters), um mehr darüber zu erfahren, wie Sie eine Reihe von Filtern speichern

## 3. **Filter**

Klicken Sie auf die Filterschaltfläche oben links, um ein Panel auf der linken Seite anzuzeigen. Wenn ein Filter angewendet wird, ändert sich die im Browser sichtbare URL entsprechend. In diesem Artikel werden Filter wie folgt angezeigt: _Filtername im Menü_ - `Filter name in URL=Filter option in URL`

**Standardfilter** Der Standardfilter ist anfangs nicht in der URL sichtbar. Wenn die Seite zum ersten Mal aufgerufen wird, wird der folgende Filter angewendet. Reiter "Arbeitsbereich" - `v=all`

### 3.1 **Aktuellen Filter speichern und freigeben**

Gehen Sie zur URL einer gefilterten Seite, um diese Seite mit angewendetem Filter zu laden. Die angewendeten Filter können oben im Filtermenü gespeichert werden. Klicken Sie [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link), um mehr darüber zu erfahren, wie Sie Filter speichern und freigeben

### 3.2 **Leere Filter ausblenden**

Klicken Sie [hier](https://support.catenda.com/en/articles/8551755-saving-filters), um mehr über die Begrenzung von Filterergebnissen zu erfahren.

### 3.3 **Reiter**

Reiter "Arbeitsbereich" - `v=all` Reiter "Veröffentlicht" - `v=published`

### 3.4 **Links**

Verknüpft - `associations=exists&subFolders=true` Nicht verknüpft - `associations=does-not-exist&subFolders=true` Mit ausgewählten Objekten verknüpft - `link=backlink&subFolders=true`

### 3.5 **Status (letzte Revision) - Nur Workflow-Status**

Veröffentlicht - `documentStatus=published&subFolders=true&documentType=file` Fehlender Status - `documentStatus=published-without-status&subFolders=true` Projektveröffentlichungsstatus - `documentStatus=<GUID>&subFolders=true` Freigegeben - `documentStatus=shared&subFolders=true&documentType=file` Freigegebene Status sind nur in der Registerkarte "Arbeitsbereich" verfügbar Freigegebener Projektrozesstatus - `documentStatus=<GUID>&subFolders=true` Keine Revision vorhanden - `documentStatus=no-stage&subFolders=true`

### 3.6 **Entwürfe - Nur Workflow-Status**

Hat neue Entwürfe - `newDrafts=exists&subFolders=true` Name des Entwurfsstatus - `newDrafts=<Draft status GUID>&subFolders=true` Wenn mehrere Entwurfsstatus vorhanden sind, kann nach jedem Entwurfsstatus gefiltert werden. Hat keine neuen Entwürfe - `newDrafts=does-not-exist&subFolders=true`

### 3.7 **Dokument erstellt von**

Name des Mitglieds - `owner=<Member GUID>&subFolders=true`

### 3.8 **Revision erstellt von**

Name des Mitglieds - `revisionCreatedBy=<GUID>&subFolders=true`

### 3.9 **Veröffentlicht von**

Name des Mitglieds - `publishedBy=<Member GUID>&subFolders=true`

### 3.10 **Datumfilter**

Veröffentlicht - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Klicken Sie auf Daten auswählen, um Daten auszuwählen, zwischen denen Sie suchen möchten Klicken Sie [hier](https://support.catenda.com/en/articles/6511685-date-filter), um mehr über den Datumfilter zu erfahren

### 3.11 **Offene Genehmigungen - Nur Workflow-Status**

Name der Genehmigung - `approval=<Approval number>&subFolders=true`

### 3.12 **Etiketten**

Alle Etiketten, die nicht Teil einer Etikettengruppe sind, werden in einem Menü namens Etiketten angezeigt. Name der Etikett - `labels=<Label GUID>6&subFolders=true`

### 3.13 **Name der Etikettengruppe**

Es gibt ein Menü pro Name der Etikettengruppe Name der Etikett - `labels=<Label GUID>6&subFolders=true`

### 3.14 **Sammlungen**

Name der Sammlung - `collections=<GUID>&subFolders=true`

## 4. **Text-Suche**

_Text-Suche_ - `search=test&subFolders=true`

### 4.1 **Inhalt, nach dem gesucht werden kann**

Name des Modells

### 4.2 **Großschreibung**

Die Text-Suche berücksichtigt keine Groß- oder Kleinbuchstaben.

### 4.3 **Zeichenanzahl**

Weniger als drei Zeichen - Die Tabelle wird nicht gefiltert. Drei oder mehr Zeichen - Titel, die ein einzelnes Wort haben, das durch ein Trennzeichen wie ein Leerzeichen getrennt ist und dem Suchbegriff entspricht, werden in die Ergebnisse aufgenommen.

### 4.4 **Dateitypen**

Wenn der Modellname eine Erweiterung enthält, kann mit der regulären Text-Suche nach der Erweiterung gesucht werden. Suchen Sie mit der Erweiterung mit dem Punkt, um nach einem bestimmten Dateityp zu suchen. Wenn Sie beispielsweise nach .ifc suchen, können alle Dokumente mit .ifc im Modellnamen gefunden werden.

## 5. **Sortieren**

Modelle können sortiert werden, indem Sie auf die Kopfzeile jeder Spalte klicken. Die Kopfzeile kann mehrmals angeklickt werden, um die Sortierung rückgängig zu machen oder zu deaktivieren.

_Name, a-z_ - Standard _Name, z-a_ - `sort=modelName-desc` _Dokumentname, a-z_ - `sort=name-asc` _Dokumentname, z-a_ -`sort=name-desc` _Veröffentlicht, neueste zuerst_ - `sort=publishedAt-desc` _Veröffentlicht, älteste zuerst_ - `sort=publishedAt-asc` _Dokument erstellt, neueste zuerst_ - `sort=createdAt-desc` _Dokument erstellt, älteste zuerst_ - `sort=createdAt-asc` Revision erstellt_, neueste zuerst_ - `sort=revisionCreatedAt-desc` Revision erstellt_, älteste zuerst_ - `sort=revisionCreatedAt-desc`
