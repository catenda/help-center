# Erscheinungsbild des 2D-Viewers

Es gibt mehrere Möglichkeiten, den Inhalt des 2D-Viewers an Ihre Anforderungen anzupassen.

## 1. **Viewer-Objekte**

### 1.1 **Hervorhebung ausgewählter Objekte**

Die Linien, die für jedes Geschoss beim Verarbeiten des Modells erstellt werden, bleiben mit dem 3D-Objekt verbunden, das beim Erstellen der Linien durchschnitten wurde.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/01-highlighting-selected-objects.png)

Wenn ein Objekt im 3D-Viewer ausgewählt wird und ein Geschoss dieses Modells im 2D-Viewer aktiviert ist, das in der Höhe erstellt wurde, in der sich dieses Objekt befindet, wird das Objekt auch im 2D-Viewer hervorgehoben. Objektschnitte werden in einer Höhe von einem Meter über der Höhe erstellt, die für jedes Geschoss in der IFC-Datei festgelegt ist. Höhenversätze wie die Höhe in IFCSite werden nicht berücksichtigt.

Im folgenden Beispiel befindet sich das Geschoss "Erdgeschoss" auf 0 Metern. Wände mit einer Basishöhe von 0 und unterschiedlichen Oberkanten werden angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/02-highlighting-selected-objects.png)

Wie zu sehen ist, werden im 2D-Viewer nur Wände angezeigt, die 1 Meter und darüber sind.

### 1.2 **Türöffnungen**

Türöffnungen werden in der IFC-Datei angegeben. Sie können sehen, wie dies in den folgenden BuildingSMART-Artikeln funktioniert: [IFC 2x3](https://standards.buildingsmart.org/IFC/RELEASE/IFC2x/FINAL/HTML/ifcsharedbldgelements/lexical/ifcdoorstyle.html) [IFC 4](https://standards.buildingsmart.org/IFC/RELEASE/IFC4_1/FINAL/HTML/schema/ifcsharedbldgelements/lexical/ifcdoortypeoperationenum.htm) Wenn keine Türöffnung angegeben ist, öffnet sich die Tür nach rechts.

## 2. **Zeichnung als Untergrund**

Es ist möglich, ein PDF aus dem Dokumentenbereich mit dem [Geschosskonfigurator](https://support.catenda.com/en/articles/6921756-storey-configurator-page) zu unterlegen. Dies ist besonders hilfreich, wenn sich Objekte über oder unter der Höhe befinden, in der die 3D-Objekte geschnitten werden und im 2D-Viewer nicht angezeigt werden. Beispiele hierfür sind: Kanäle und Rohre, Elektrische Steckdosen, Deckenzeichnungen, Straßen und Schienen

## 3. **Marker im 2D-Viewer**

Mit [aktivierten Markern](https://support.catenda.com/en/articles/4854537-2d-viewer#h_381a9d4098) werden Themen mit Ort als farbige Kreise bei einer x-y-Koordinate angezeigt. So könnte eine 2D-Ansicht mit verschiedenen Markern im Browser aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/03-markers-in-the-2d-viewer.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/4854523-2d-location-of-issues), um mehr über den 2D-Ort von Themen zu erfahren.

### 3.1 **Themen mit vorhandenen Markern**

**Markerinteraktionen -** Fahren Sie mit der Maus über einen Marker, um die Nummer und den Titel des Themas anzuzeigen, aus dem der Marker stammt. Klicken Sie auf den Marker, um das Thema im Themenbrett im Inhaltsbereich zu öffnen. Ein Marker, der zu einem geöffneten Thema gehört, wird grün hervorgehoben.

**Anzeige von Markern -** Filtern und suchen Sie in einem Themenbrett. Themen aus dem gefilterten Ergebnis, die Marker im vorbereiteten 2D-Viewer haben, werden angezeigt.

### 3.2 **Themen mit neuen Markern**

Stellen Sie vor der Arbeit mit Markern sicher, dass der 2D-Viewer konfiguriert ist.

- **Geschosse aus Modell 2D-Ansichten -** Wählen Sie ein Geschoss aus einer aktivierten 2D-Ansicht als Basishöhe. Aktivieren Sie andere 2D-Ansichten, um sie neben diesem Geschoss anzuzeigen.
- **Geschosse aus Gebäuden -** Wählen Sie ein Geschoss aus einem vorkonfigurierten Gebäude.
  Die Basishöhe und die aktivierten 2D-Ansichten aus konfigurierten Modellen sind aktiviert.

**Markerplatzierung -** Klicken Sie mit der rechten Maustaste auf die Leinwand und erstellen Sie ein neues Thema mit Marker. Klicken Sie auf Ort hinzufügen in der Themenkopfzeile im Inhaltsbereich und klicken Sie auf den Ort, an dem der Marker hinzugefügt werden soll.

## 4. **Raumetiketten im 2D-Viewer**

Die im Zentrum von Räumen im 2D-Viewer angezeigten Raumetiketten werden anhand der in IFC-Raum-Objekten verfügbaren Daten bestimmt. Diese Raum-Objekte enthalten sowohl Kurz- als auch Langnamen, die konfiguriert werden können, um das Etikettenformat über die Einstellung **Raumnamensformat** in Catenda zu definieren. Stellen Sie sicher, dass sowohl Raumnummern als auch Flächen genau in den IFC-Daten enthalten sind, da fehlende Attribute die Anzeige der gewünschten Raumetiketten möglicherweise einschränken.

### 4.1 Fehlerbehebung für Raumetiketten:

- Stellen Sie sicher, dass die IFC-Datendatei erforderliche Attribute wie Raumnummern und Flächen enthält.
- Überprüfen und passen Sie die Einstellung "Raumnamensformat" an, um sie an Ihre bevorzugten Etikett-Konfigurationen anzupassen. Sie finden die Einstellung im 2D-Viewer "Einstellungsrad" in der rechten Ecke.
