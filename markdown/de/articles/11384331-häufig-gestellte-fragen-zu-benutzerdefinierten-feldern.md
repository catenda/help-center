# Häufig gestellte Fragen zu benutzerdefinierten Feldern

Die Einschränkungen bei der Interaktion mit benutzerdefinierten Feldern werden hier erläutert.

## 1. **Projekt \<=> Projekt**

Benutzerdefinierte Felder haben eine eindeutige ID innerhalb eines Projekts und können daher nicht von einem Projekt zu einem anderen ausgetauscht werden. Auch wenn benutzerdefinierte Felder in beiden Projekten denselben Namen haben, ist die ID eindeutig und das Feld wird nicht erkannt.

## 2. **Themenbrett \<=> Themenbrett**

Wenn ein benutzerdefiniertes Feld für zwei Themenbretter innerhalb desselben Projekts aktiviert ist, können Themen zwischen den Brettern verschoben werden und das Feld wird beibehalten.

## 3. **Exportieren von benutzerdefinierten Feldern für Themen**

Benutzerdefinierte Felder für Themen können auf folgende Weise exportiert werden

### 3.1 **Thema PDF-Export**

Benutzerdefinierte Feldwerte werden im PDF-Export von Themen angezeigt

### 3.2 **Thema BCF-Export**

Benutzerdefinierte Felder sind noch nicht im exportierten BCF enthalten. Benutzerdefinierte Felder werden Teil des BCF 4-Standards sein, wenn dieser veröffentlicht wird. Nach der Veröffentlichung werden wir und andere BCF-Tools, die den Standard befolgen, daran arbeiten, das Feld für den Austausch verfügbar zu machen.

### 3.3 **Thema Excel-Export**

Für jedes benutzerdefinierte Feld im Themenbrett wird eine Spalte hinzugefügt.

### 3.4 **API**

Benutzerdefinierte Felder in Themenbrettern [können über die API konfiguriert werden](https://developers.catenda.com/topic-api/update-a-topic-board). Benutzerdefinierte Felder für Themen [können über die API konfiguriert werden](https://developers.catenda.com/topic-api/update-topic). Informationen über benutzerdefinierte Felder für Themen können über die API abgerufen werden.

### 3.5 **Berichtsaktion**

Benutzerdefinierte Felder für Themen sind nur für den Export mit PDF-, BCF- oder Excel-Exporten und über die API verfügbar.

## 4. **Exportieren von benutzerdefinierten Feldern für Dokumente**

Benutzerdefinierte Felder für Dokumente können auf folgende Weise exportiert werden

### 4.1 **Berichtsaktion**

Wenn die Funktion "On-Demand-Berichte" für ein Projekt aktiviert worden ist, wird die Berichtsaktion verfügbar gemacht. Wenn der Bericht mit dem Namen des benutzerdefinierten Feldes konfiguriert ist, können Informationen über benutzerdefinierte Felder von Dokumenten, die in der Dokumenttabelle ausgewählt sind, in einen Bericht exportiert und in jedem verfügbaren Berichtsformat gespeichert werden.

### 4.2 **API**

Benutzerdefinierte Felder für Dokumente sind nur über die Berichtsaktion für den Export verfügbar.

### 4.3 **Dokumentendownload**

Benutzerdefinierte Felder für Dokumente sind nur über die Berichtsaktion verfügbar. Wenn Dokumente mit der Download-Aktion in der Dokumenttabelle heruntergeladen werden, wird das Originaldokument heruntergeladen. Catenda ändert das Dokument in keiner Weise, daher werden benutzerdefinierte Felder auch nicht als Metadaten hinzugefügt.
