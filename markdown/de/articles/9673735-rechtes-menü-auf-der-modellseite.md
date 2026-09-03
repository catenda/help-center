# Rechtes Menü auf der Modellseite

Das rechte Informationsmenü finden Sie, indem Sie ein Modell auf der [Modellseite](https://support.catenda.com/en/articles/4670286-models-page) auswählen oder die [Inhaltsseite](https://support.catenda.com/en/articles/4670270-model-overview-page) eines Modells aufrufen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/01-intro.png)

Klicken Sie auf das "i"-Symbol oben rechts, um das rechte Menü zu öffnen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/02-intro.png)

Das Menü kann für ein einzelnes Modell etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/03-intro.png)

Oder so mit mehreren ausgewählten Modellzeilen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/04-intro.png)

## 1. **Modellkopfzeile**

In der Modellkopfzeile werden Informationen über die neueste Revision des Modells angezeigt.

### 1.1 **Bild**

Oben in der Modellkopfzeile kann ein Bild für das Modell hinzugefügt werden. So kann es aussehen, wenn kein Bild hinzugefügt wird.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/05-image.png)

Laden Sie entweder ein lokales Bild hoch oder fügen Sie einen Schnappschuss direkt aus dem 3D-Viewer hinzu, ohne etwas hochzuladen. So sieht die Modellseite aus, wenn ein Bild für ein Modell konfiguriert ist:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/06-image.png)

_Modellbild im rechten Menü_ Wenn hinzugefügt, wird das Bild oben im rechten Menü eines Modells angezeigt, wenn ein einzelnes Modell ausgewählt ist oder wenn das Menü auf der Modellseite offen ist. Das hinzugefügte Bild wird sowohl im rechten Menü einer Modellrevision angezeigt, wenn ein Modell ausgewählt ist, als auch im Miniaturansicht des Modells in der Namensspalte der Modelltabelle.

Klicken Sie [hier](https://support.catenda.com/en/articles/4670257-creating-a-thumbnail-for-your-model), um mehr darüber zu erfahren, wie Sie ein Bild für ein Modell hinzufügen.

**Modellminiaturansicht** Wenn hinzugefügt, wird das Bild als Miniaturansicht für das Modell in der Namensspalte der Modelltabelle auf der Modellseite angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/07-image.png)

Klicken Sie auf die Miniaturansicht, um eine Vorschau des Bildes zu öffnen. So kann die Miniaturansicht aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/08-image.png)

In der Navigation oben kann das Bild heruntergeladen werden. Wenn der Schnappschuss von einem Modell gemacht wurde, ist die Vorschau eine 3D-Vorschau, sodass es möglich ist, das Modell vom Startpunkt der Modellminiaturansicht aus zu navigieren.

### 1.2 **Dokumentlink**

Der Dokumentlink ist das graue Feld unter dem Modellbild. Das Feld zeigt den Speicherort des Dokument-Modells in der Dateistruktur. Darunter sehen Sie den Namen des Dokument-Modells, das mit diesem Modell-Dokument verknüpft ist. Klicken Sie auf dieses Feld, um zur Dokumentvorschauseite des Dokument-Modells auf der Dokumentseite zu gelangen.

### 1.3 **Status**

Der Status der neuesten öffentlichen Dokument-Modell-Revision.

### 1.4 **Etiketten**

Standardmäßig können Etiketten auf beliebige Modelle angewendet werden. Wenn gemeinsame Revisionen aktiviert sind, muss mindestens eine veröffentlichte Revision im Modell vorhanden sein, um Etiketten hinzufügen zu können. Etiketten werden sowohl für das Modell als auch für das Dokument gespeichert, mit dem das Modell verknüpft ist. Das gleiche Etikett kann daher verwendet werden, um auf der Modellseite nach Modellen und auf der Dokumentseite nach Dokumenten zu filtern.

## 2. **Mitwirkende**

Die verschiedenen Mitglieder, die Revisionen hochgeladen haben und damit zum Modell beigetragen haben, werden hier angezeigt.

## 3. **Modelltransformation**

Mit der Modelltransformation können Modellobjekte so konfiguriert werden, dass sie an einem anderen Ort und einer anderen Ausrichtung im Catenda Hub 3D-Viewer angezeigt werden. Diese Transformation gilt nur für Modelle im 3D-Viewer und nicht für 3D-Dokumente, die in den 3D-Viewer geladen wurden. Klicken Sie [hier](https://support.catenda.com/en/articles/12498975-add-context-to-your-projects-with-freely-accessible-ign-point-clouds-hd-lidar), um mehr über die Transformation von 3D-Dokumenten zu erfahren.

**Modelle mit externen Tools austauschen** Modelle werden häufig aus Catenda heruntergeladen und in einem Drittanbieter-Programm geöffnet. Es ist daher wichtig, vor dem Hochladen die richtigen Koordinaten in der IFC-Datei konfiguriert zu haben, damit die heruntergeladene Datei die richtigen Informationen enthält.

**Wann sollte das Modell transformiert werden?** Es gibt oft einen Zeitraum, in dem ein Modell eingereicht wird und die Geometrie bereits verwendet wird, um zusammenzuarbeiten, bevor die Koordinaten im Modell korrekt sind. Dies kann verschiedene Gründe haben, zum Beispiel, dass in dem Projekt kein gemeinsamer Nullpunkt festgelegt ist, oder dass in dem Programm, in dem die IFC-Datei generiert wurde, eine andere Exportmethode verwendet werden muss. Es kann hilfreich sein, das Modell während dieses Zeitraums (nur in Catenda Hub über den Browser) mit der Modelltransformation zu transformieren, damit die 3D-Schnappschüsse weiterhin passen, auch bei neueren Revisionen mit aktualisierten Koordinaten.

**Koordinatenzusammenarbeit mit gemeinsamen Revisionen** In einem Projekt, in dem gemeinsame Revisionen aktiviert sind, wird nicht empfohlen, Modellrevisionen zu veröffentlichen, ohne die richtigen Koordinaten in der IFC-Datei zu haben.

### 3.1 **Modelltransformationseinstellungen**

Laden Sie das Modell, das im 3D-Viewer verschoben werden soll. Dies kann durch Klicken auf die 3D-Schaltfläche im Dashboard, auf der Modellseite, auf der Modellseite oder im Revisions-Selector erfolgen. Im rechten Menü auf der Modellseite wird das Transformationseinstellungsmenü am unteren Ende des Menüs angezeigt. Das ist, wie die Modelltransformationseinstellungen aussehen können:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/09-model-transformation-settings.png)

**Versatz** Geben Sie X-, Y- und/oder Z-Koordinate ein, um das Modell zu verschieben. Einheiten - Meter

**Rotation** Geben Sie einen Winkel ein, um das Modell zu drehen. Das Modell wird um die Mittelpunkte seines Begrenzungsrahmens gedreht, die alle Objekte des Modells enthalten. Der Punkt liegt oft um die Mitte des Modells von oben gesehen. Einheiten - Grad

**Speichern** Klicken Sie auf Speichern, um die Transformationseinstellungen zu speichern.

### 3.2 **Nur im Browser**

Die IFC-Datei wird nicht geändert, wenn die Transformationseinstellungen gespeichert werden. Wenn ein neues Modell mit der IFC-Datei entweder innerhalb desselben Projekts oder in einem anderen Projekt erstellt wird, wird die IFC-Datei an dem Speicherort angezeigt, der in der IFC-Datei konfiguriert ist.

Es ist oft kein Problem, ein Modell in Catenda für kurze Zeit oder sogar für die gesamte Lebensdauer des Projekts zu verschieben. Am Ende kann es viel Zeit sparen, sich auf ein gemeinsames Koordinatensystem zu einigen, damit Modelle nach ihrer Erstellung nicht angepasst werden müssen und Missverständnisse im Verlauf des Projekts vermieden werden.

## 4. **Mehrfachauswahl**

Bei mehreren ausgewählten Modellen kann das rechte Menü so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/10-multi-select.png)

Klicken Sie auf das rote x neben einem Modell, um es aus der Auswahl zu entfernen.

### 4.1 **Ausgewählte Dokumente aktualisieren**

So kann das Menü „Ausgewählte Dokumente aktualisieren

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/11-update-selected-documents.png)

Klicken Sie in die Bereiche „Etiketten hinzufügen

_Das Hinzufügen hat Vorrang_ Ein Etikett, das in beiden Feldern „Etiketten hinzufügen

### 4.2 **Letzte Revision**

Der eingegebene Status wird für alle ausgewählten Modelle konfiguriert, wenn die Änderungen gespeichert werden.
