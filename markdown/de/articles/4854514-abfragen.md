# Abfragen

> Eine Erklärung der Abfragefunktion in der 2D-Symbolleiste

Eine Abfrage ist eine Möglichkeit, Objekte aus Teilen von Modellen in Catenda Hub zu laden, ohne das gesamte Modell zu laden.

IFC-Dateien sind in der Regel leichtgewichtige Versionen des Modells aus dem Autorenprogram, aus dem es exportiert wurde, und sind oft leicht genug, um sie im Browser anzuzeigen, wenn sie keine Objekte mit viel Geometrie enthalten.

## 1. **Wann sollte ich eine Abfrage erstellen?**

Es kann jedoch vorkommen, dass Sie eine begrenzte Leistung feststellen. Dies kann durch eine Reihe von Faktoren verursacht werden, z. B. durch große Geometrie wie zuvor erwähnt, aber auch durch den Versuch, viele Modelle gleichzeitig (100+) zu laden und die Grenzen dessen zu erreichen, was Ihr Gerät verarbeiten kann. Beim Laden von Modellen ist oft Speicher erforderlich. Besonders auf mobilen Geräten mit begrenztem Speicher kann dies der Fall sein, aber auch durchschnittliche Systeme mit 16 GB RAM können bei Laden vieler Modelle aus dem Speicher laufen.

## 2. **Eine Abfrage erstellen**

Abfragen können entweder vom [2D-Viewer](https://support.catenda.com/en/articles/4854537-2d-viewer) oder aus einer Eigenschaftsbibliothek erstellt werden. Mit dem [2D-Viewer](https://support.catenda.com/en/articles/4854537-2d-viewer) können Sie leicht einen Bereich im Projekt auswählen, den Sie laden möchten. Mit einer Eigenschaftsbibliothek können Sie leicht Objekte mit einer bestimmten Eigenschaft auswählen, die Sie laden möchten.

## 3. **2D-Viewer-Abfrage**

Um eine Abfrage vom [2D-Viewer](https://support.catenda.com/en/articles/4854537-2d-viewer) zu erstellen, öffnen Sie die 2D-Ansicht eines Modells:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/01-2d-viewer-query.png)

Dies hilft Ihnen zu verstehen, von welcher Position im Projekt Ihre Objekte ausgewählt werden. Es gibt drei verschiedene Möglichkeiten, Abfragen im 2D-Viewer zu erstellen. Wenn Sie im 2D-Viewer mit der rechten Maustaste klicken, wird das [Menü 2D-Viewer-Interaktionen](https://support.catenda.com/en/articles/4854537-2d-viewer#h_bfa30db456) geöffnet. Hier können Sie die folgenden Abfragen auswählen: [Überschneidender Raum](#h_bade07829c) [Überschneidendes Geschoss](#h_6127f099ac) Die dritte Abfrage kann mit dem [Dropdown-Menü 2D-Viewer-Auswahl](https://support.catenda.com/en/articles/4854537-2d-viewer#h_042dc145fa) erstellt werden. Hier können Sie auswählen: Rechteckige Auswahl, mit der Sie die folgende Abfrage erstellen können: [Rechteckige Auswahl](#h_33afc95ee3)

### 3.1 **Überschneidender Raumabfrage**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/02-intersecting-space-query.png)

1. Klicken Sie mit der rechten Maustaste auf einen Raum
1. Wählen Sie _Überschneidender Raum_

Dies lädt alle Geometrie, die die achsenausgerichtete Begrenzungsbox des Raums schneidet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/03-intersecting-space-query.png)

### 3.2 **Überschneidendes Geschossabfrage**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/04-intersecting-storey-query.png)

1. Klicken Sie mit der rechten Maustaste im Viewer
1. Wählen Sie _Überschneidendes Geschoss_

Dies lädt alle Geometrie innerhalb der oberen und unteren Ebenen des Geschosses.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/05-intersecting-storey-query.png)

### 3.3 **Rechteckige Auswahl**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/06-rectangle-selection.png)

1. Klicken Sie auf die Schaltfläche Abfrage-Rechteck.
1. Klicken Sie, ziehen Sie und lassen Sie los, um ein Rechteck zu zeichnen.
1. Geben Sie die Modelle an, die Sie in der Abfrage-Popover laden möchten.

**Abfrage-Popover**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/07-rectangle-selection.png)

1. Wählen Sie aktuelles Geschoss oder Vollhöhe.
1. Wählen Sie Beliebig, Außen oder Innen.
1. Schalten Sie alle Modelle ein oder aus.
1. Wählen Sie die Modelle aus, die Sie in die Abfrage einbeziehen möchten.
1. Abfrage erstellen.

## 4. **Eigenschaftsbibliotheks-Abfrage**

Wenn Sie Ihre [Eigenschaftswert-Bibliothek](https://support.catenda.com/en/articles/4670252-property-value-library) synchronisiert haben, können Sie auf die Objektanzahl neben dem Eigenschaftswert klicken und auswählen, aus welchem/welchen Modell(en) Sie eine Abfrage von Objekten mit diesem Eigenschaftswert durchführen möchten.

## 5. **Eine Abfrage bearbeiten**

Abfragen können bearbeitet werden, indem Sie das Abfragemenü in der [Revisions-Auswahl](https://support.catenda.com/en/articles/4670279-revision-selector#h_fcf1c5a080) auswählen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/08-editing-a-query.png)

Hier sehen Sie die verschiedenen Abfragen, die Sie in dieser Sitzung geladen haben. Um eine Abfrage zu bearbeiten, klicken Sie auf die Schaltfläche Bearbeiten rechts neben Ihrer Abfrage. Da Abfragen nur einen begrenzten Satz von Objekten laden, ist es nicht möglich, gleichzeitig mit Modellen aus der Registerkarte Modelle und Abfragen zu arbeiten. Wenn Sie mit Modellen aus der Registerkarte Modelle arbeiten möchten, klicken Sie auf 3D wiederherstellen. Dies entlädt die Abfrage und lädt stattdessen das gesamte Modell.

## 6. **Abfragen speichern**

Um Ihre Abfrage zu speichern und später damit zu arbeiten, erstellen Sie einen 3D-Schnappschuss im Kommentarbereich eines Themas oder erstellen Sie ein Lesezeichen. Wenn Sie in Ihrer nächsten Catenda-Sitzung mit Ihrer Abfrage fortfahren möchten, können Sie das Lesezeichen oder den Schnappschuss abspielen.
