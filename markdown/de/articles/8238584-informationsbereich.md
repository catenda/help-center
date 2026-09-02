# Informationsbereich

Sie finden den Informationsbereich als einen der vier Hauptbereiche, die oben rechts auf Ihrem Bildschirm geöffnet werden können. Sie können entweder auf das i-Symbol klicken, um diesen Bereich zu öffnen, oder Sie können [Umschalt+4](https://support.catenda.com/en/articles/4670267-summary-of-most-important-shortcuts-and-basic-controls#:~:text=Inspect%20panel-,Shift%20%2B%204,-Show/hide%20last) drücken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/01-intro.png)

Im Informationsbereich finden Sie die folgenden Abschnitte:

## 1. **Überprüfung**

Hier können Sie die Informationen zu Ihren ausgewählten Objekten anzeigen. Klicken Sie [hier](https://support.catenda.com/en/articles/4670285-inspect-panel), um mehr über den Überprüfungsbereich zu erfahren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/02-inspect.png)

## 2. **Massenermittlung**

Damit können Sie eine Liste von Objekten erstellen und exportieren sowie die Summen von Werten berechnen, die mit den verschiedenen ausgewählten Objekten verbunden sind.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/03-quantity-take-off.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/6673929-quantity-take-off-qto), um mehr über die Massenermittlung zu erfahren

## 3. **4D**

In diesem Abschnitt können Sie den Fortschritt von Modellen mit der 4. Dimension verfolgen. Zeit. Wenn Ihre IFC-Datei einen IFCWORKPLAN enthält, können Sie einen Zeitplan für die Objekte in Ihrer Datei anzeigen.

> **Hinweis:** 4D in Catenda ist nur für IFC-Dateien verfügbar, die aus [SYNCHRO](https://www.bentley.com/software/synchro/) exportiert wurden. Diese Dateien können einen IfcWorkPlan und IfcTasks enthalten

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/04-4d.png)

Zu Beginn des Zeitrahmens werden alle Objekte ausgeblendet und je nachdem, wie viel Zeit vergangen ist, werden Objekte mit der richtigen Einstellung angezeigt. Hier ist ein Beispiel, wie der 4D-Abschnitt aussehen kann:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/05-4d.png)

### 3.1 **4D-Spalten**

## 4. - Die Aufgabennummer

_Aufgaben-ID_ - Die ID der Aufgabe

_Name_ - Der Name der Aufgabe

_Dauer_ - Die Dauer der Aufgabe

**Start** Das Startdatum der Aufgabe Dies ist der Zeitpunkt, an dem das Objekt in 3D angezeigt wird. Die Objekte werden auch zwischen dem Startdatum und dem Enddatum einer Aufgabe ausgewählt. Der Aufgabenbalken wird orange angezeigt. Klicken Sie auf das Uhrsymbol neben dem Datum, um zu diesem Zeitpunkt zu springen.

Fertig Das Enddatum der Aufgabe - Nach dem Enddatum bleiben die Objekte in 3D erhalten, werden aber abgewählt. Nach diesem Datum wird der Aufgabenbalken grün. Klicken Sie auf das Uhrsymbol neben dem Datum, um zu diesem Zeitpunkt zu springen.

**Produkte** Die mit dieser Aufgabe verbundenen Objekte Die Objekte können durch Klicken auf "Isolieren" und "Auswählen" isoliert und ausgewählt werden.

### 4.1 **4D-Lesezeichen**

Es ist möglich, ein Lesezeichen zu erstellen, bei dem der 4D-Arbeitsplan aktiviert wurde. Wenn Sie auf dieses Lesezeichen zugreifen, sehen Sie, welche Objekte bis zum aktuellen Zeitpunkt gemäß dem Plan sichtbar gemacht wurden. In Catenda Hub können Sie die Zeitskala nach Belieben anpassen. Wenn Sie das Lesezeichen extern freigeben, sieht die externe Partei, die auf das Lesezeichen zugreift, nur die Objekte, die bisher sichtbar gemacht wurden.

### 4.2 **Wie erkenne ich, ob meine IFC 4D-Informationen enthält?**

Wenn Ihre IFC-Datei IFCTASKs enthält, können Sie diese im 4D-Bereich anzeigen. Wenn Ihre IFC-Datei IFCRELASSIGNSTOPROCESSes enthält, werden diese Aufgaben auch mit Objekten verbunden. Ein Programm, das Sie verwenden können, um zu überprüfen, ob diese vorhanden sind, ist [OpenIFCViewer](https://openifcviewer.com/). Hier können Sie die Statistiken Ihres Modells überprüfen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/06-how-do-i-know-if-my-ifc-has-4d-information-in-it.png)

Wo Sie die Entität im Statistikbereich finden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/07-how-do-i-know-if-my-ifc-has-4d-information-in-it.png)

## 5. **Auswahlmöglichkeiten**

Damit können Sie eine Reihe von Objekten erstellen, die dann gestaltet und koloriert werden können.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/08-selections.png)

Oben im Menü "Auswahlmöglichkeiten" sehen Sie, wie viele Elemente Sie derzeit im 3D-Viewer und in der Baumstruktur ausgewählt haben. Auswahlmöglichkeiten können gespeichert werden, indem Sie einen [Schnappschuss](https://support.catenda.com/en/articles/8053352-issue-body#h_1ba7f8873f) oder ein [Lesezeichen](https://support.catenda.com/en/articles/8471481-bookmark) erstellen und später wiedergeben. Da Auswahlmöglichkeiten im Schnappschuss eines Themas gespeichert werden, können sie über BCF in andere Programme importiert und exportiert werden. Ein Beispiel dafür ist, dass Themen mit Auswahlmöglichkeiten aus dem Auswahlkorb, die über den BCF-Live-Connector in Solibri synchronisiert werden, Auswahlmöglichkeiten enthalten, wenn der Schnappschuss wiedergegeben wird.

### 5.1 **Neue Auswahlmöglichkeit**

Nach Auswahl eines Objekts können Sie auf "Neue Auswahlmöglichkeit" klicken

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/09-new-selection.png)

### 5.2 **Stiftsymbol**

Klicken Sie auf das Stiftsymbol, um den Namen Ihrer Auswahlmöglichkeit zu ändern

### 5.3 **Objektmenge**

Nach dem Stiftsymbol sehen Sie die Anzahl der Objekte, die sich derzeit in dieser Auswahlmöglichkeit befinden.

### 5.4 **Aktualisieren**

Klicken Sie auf die Schaltfläche "Aktualisieren", um die Objekte in der Auswahlmöglichkeit auf die Objekte einzustellen, die Sie derzeit im 3D-Viewer und in der Baumstruktur ausgewählt haben.

### 5.5 **Objektwähler**

Klicken Sie auf die Schaltfläche "Auswählen", um die Elemente in Ihrer Auswahlmöglichkeit auszuwählen

### 5.6 **Farbe**

Mit der Schaltfläche "Farbe" können Sie die Farbe der Objekte in Ihrer Auswahlmöglichkeit ändern. Die Farbauswahl kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/10-color.png)

Wählen Sie Farbe mit dem Farbschieber, der Palette oder geben Sie Ihre gewünschte Farbe mit einem Hex-Code an. Der zweite Schieber bestimmt die Transparenz, wobei 1 100% undurchsichtig und 0 100% transparent ist. Unten rechts sehen Sie die resultierende Farbe.

### 5.7 **Löschen**

Klicken Sie auf die Schaltfläche "Löschen", um diese Auswahlmöglichkeit zu löschen

### 5.8 **Erweitern/Einklappen**

Erweitern Sie die Auswahlmöglichkeit, um zu sehen, welche Objekte Teil der Auswahlmöglichkeit sind.

## 6. **Messungen**

Damit können Sie die Messungen anzeigen, die im 3D-Viewer vorgenommen wurden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/11-measurements.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/4670294-measuring-features), um mehr über Messungen zu erfahren
