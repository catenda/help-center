# 2D-Viewer-Interaktionen

> Interaktion mit dem 2D-Viewer

Verschiedene Komponenten des [2D-Viewers](https://support.catenda.com/en/articles/4854537-2d-viewer) können auf unterschiedliche Weise interaktiv verwendet werden. Jeder Teil des 2D-Viewers, der angeklickt werden kann, wird in diesem Artikel beschrieben. So kann der 2D-Viewer aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/01-intro.png)

Dieser Artikel enthält Informationen zu den folgenden Themen: _[2D-Schaltfläche](#h_ddfb1f5837) - [Obere Leiste](#h_7996dde66c) - [Canvas](#h_d564366bf9) -_ [Navigation](#h_b384896c43) - [Auswahl](#h_8916df6427) - [Einstellungen](#h_f9d34c17aa) - [Untere Leiste](#h_15dafd8ad4)

## 1. **2D-Schaltfläche**

Wenn der 2D-Viewer nicht geöffnet ist, klicken Sie auf die 2D-Schaltfläche unten rechts des 3D-Viewers, um den 2D-Viewer zu öffnen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/02-2d-button.png)

## 2. **Obere Leiste**

### 2.1 **Größe ändern**

Ziehen Sie diese beiden diagonalen Linien, um die Größe des 2D-Viewers über einen beliebigen Teil des 3D-Viewers zu ändern. Sie wissen, dass Sie diese Ecke ziehen können, wenn sich Ihr Cursor ändert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/03-resizing.png)

### 2.2 **Titel**

Der Titel der oberen Leiste ist der Name des Geschosses. Wenn ein Geschoss eines [Geschoss-Konfigurators](https://support.catenda.com/en/articles/6921756-storey-configurator-page) Gebäudes ausgewählt ist, enthält der Titel den Namen des Gebäudes und den Namen des aktuellen Geschosses. Wenn das Geschoss eines nicht konfigurierten Modells ausgewählt ist, enthält der Titel den Namen des Modells.

### 2.3 **Öffnen und Schließen des 2D-Viewers**

**Schließen** Klicken Sie auf das Kreuz oben rechts des 2D-Viewers, um den 2D-Viewer zu schließen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/04-opening-and-closing-the-2d-viewer.png)

## 3. **Canvas**

Das Canvas des 2D-Viewers ist der Teil des 2D-Viewers, in dem die Linien angezeigt werden, die mit den Geschossen der verschiedenen Modelle verbunden sind, für die 2D-Ansichten aktiviert sind.

### 3.1 **Maustaste klicken**

_Linksklick_ Wenn sich Räume im Geschoss der 2D-Ansicht befinden, die für ein Modell aktiviert ist, können diese durch Anklicken ausgewählt werden. Sie können feststellen, ob sich Räume in der 2D-Ansicht befinden, indem der Name des Raums in der Mitte des Raums sichtbar ist.

**Scroll** Zoomen Sie in den 2D-Viewer ein oder aus.

**Rechtsklick** Kontextmenü öffnen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/05-click-mouse-button.png)

- _Marker hinzufügen_
  Fügen Sie einen neuen Marker hinzu. Wenn Sie ein Thema im Inhaltsbereich öffnen, können Sie den ausgewählten Marker zuweisen. Dieser Marker wird nicht gespeichert und ist für andere nicht sichtbar, bis er zu einem Problem hinzugefügt wird.
- _Neues Thema mit Marker erstellen_
  Erstellen Sie ein neues Thema mit Marker. Dieser Marker wird nicht gespeichert und ist für andere nicht sichtbar, bis das Thema eingereicht wird.
- _Abfrage erstellen_
  - Raum schneiden - Erstellen Sie eine [Abfrage](https://support.catenda.com/en/articles/4854514-queries) aller Objekte, die den ausgewählten Raum schneiden
  - Geschoss schneiden - Erstellen Sie eine [Abfrage](https://support.catenda.com/en/articles/4854514-queries) aller Objekte, die dieses Geschoss schneiden

### 3.2 **Maustaste halten**

**Linke oder rechte Taste halten** 2D-Viewer schwenken

### 3.3 **Ansichtspunkt-Indikator**

**Linksklick auf Ansichtspunkt-Indikator halten** Bewegen Sie die Kamera in 3D. Der Kamerawinkel bleibt erhalten.

**Rechtsklick auf Ansichtspunkt-Indikator halten** Bewegen Sie die Kamera in 3D. Der Kamerawinkel wird folgen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/06-viewpoint-indicator.png)

## 4. **Navigationswerkzeuge**

### 4.1 **Auf Umfang zoomen**

Zoomen Sie aus, um alle sichtbaren Objekte auf einmal anzuzeigen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/07-zoom-to-extents.png)

### 4.2 **Rotation**

Mit der Rotationsschaltfläche können Sie den 2D-Viewer drehen.

**Rotationsschieber** Die anfängliche Rotation kann durch Festlegen eines Standorts mit Rotation in den [Projekteinstellungen](https://support.catenda.com/en/articles/4670273-project-settings-page) konfiguriert werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/08-rotation.png)

**Schieber-Anpassung** Wählen Sie den Schieber aus, indem Sie darauf klicken, und verwenden Sie die linke und rechte Pfeiltaste, um 0,1-Grad-Anpassungen vorzunehmen. Dies kann nützlich sein, um Auswahl, Schnitte und Abfragen zu erstellen. Die Rotation ist einfacher, wenn Sie zuerst einen Raum auswählen, da dieser beim Drehen an den Kanten des Raums einrastet. Sie können den Rotationsgrad auch in das Menü unter dem Schieber schreiben.

**Magnetischer Norden** Wenn keine anfängliche Rotation in den Projekteinstellungen konfiguriert ist, ist der magnetische Norden identisch mit der Zurücksetzen-Schaltfläche. Wenn eine anfängliche Rotation in den Projekteinstellungen konfiguriert wurde, kann der magnetische Norden in einem Winkel zur anfänglichen Rotation liegen

**Zurücksetzen** Klicken Sie oben rechts auf "Zurücksetzen", um den Schieberegler auf die anfängliche Rotation zurückzusetzen.

**Unterliegende Zeichnungsrotation** Gebäude können im [Geschoss-Konfigurator](https://support.catenda.com/en/articles/6921756-storey-configurator-page) konfiguriert werden. Jedes Geschoss in einem Gebäude kann eine Zeichnung als Untergrund haben, die relativ zu den Modellen im Projekt gedreht ist.

### 4.3 **Kamera sperren**

Wenn ein Modell im 3D-Viewer geladen ist, können Sie die Kamera auf die 3D-Viewer-Kamera sperren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/09-lock-camera.png)

Wenn diese Funktion aktiviert ist, bleibt der Ansichtspunkt-Indikator auf der Leinwand zentriert, auch wenn die Kamera im 3D-Viewer bewegt wird. Dies ist nützlich in Kombination mit dem [Gehmodus](https://support.catenda.com/en/articles/5784718-3d-viewer-settings#h_1c05dca226).

## 5. **Auswahlwerkzeuge und Einstellungen**

Die Auswahlwerkzeuge und Einstellungen befinden sich oben rechts auf der Leinwand des 2D-Viewers.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/10-selection-tools-and-settings.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/8035360-selecting-and-clipping-from-2d), um eine detaillierte Erklärung zur Verwendung von Schnittwerkzeugen im 2D-Viewer zu erhalten.

### 5.1 **Auswählen**

Wählen Sie Räume aus und zoomen Sie ein und aus.

### 5.2 **Abschnitt: Objekte auswählen**

Ziehen Sie ein Rechteck über die 2D-Leinwand, um ein Volumen zum Auswählen von Objekten in 2D/3D zu erstellen.

### 5.3 **Abschnitt: Schnittebenen erstellen**

Erstellen Sie 4 bis 6 Schnittebenen, indem Sie ein Rechteck über die 2D-Leinwand ziehen und die Höhe auswählen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/11-section-create-clipping-planes.png)

### 5.4 **Abschnitt: Abfrage erstellen**

Erstellen Sie eine [Abfrage](https://support.catenda.com/en/articles/4854514-queries), indem Sie ein Rechteck über die 2D-Leinwand ziehen und die Höhe auswählen.

### 5.5 **Schaltfläche verschieben**

Die rechteckige Auswahlmöglichkeit der Schnitt-Tools behindert die Cursorbewegung. Oben rechts im 2D-Viewer können Sie daher die Verschiebungs-Schaltfläche verwenden. Mit dieser Schaltfläche können Sie Ihre Canvas für die Schnitterstellung leicht neu positionieren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/12-br-move-button.png)

## 6. **2D-Viewer-Einstellungen**

Die Einstellungen des 2D-Viewers finden Sie in der Dropdown-Schaltfläche mit dem Zahnradsymbol.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/13-2d-viewer-settings.png)

**Markierungsfarb-Modus** Ändern Sie die Farbe der Markierungen in der 2D-Ansicht auf eine der folgenden Farben:

- Status
- Typ
- Fälligkeitsdatum

**Raumname-Format** Zeigen Sie den langen Namen der Räume und Flächen an

**Durchscheinend** Machen Sie den 2D-Viewer durchsichtig

## 7. **Untere Leiste**

### 7.1 **Modellansicht**

Klicken Sie hier, um mehr über das Geschoss-Menü zu erfahren. Das Geschoss-Menü kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/14-model-view.png)

### 7.2 **Ebenenmenü**

Mit der Ebenen-Schaltfläche können Sie verschiedene Ebenen im 2D-Viewer umschalten.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/15-layer-menu.png)

**Markierungen** Mit dieser Schaltfläche können Markierungen ein- oder ausgeschaltet werden.

**Modelle** Mit dieser Schaltfläche können Modelle ein- oder ausgeschaltet werden.

**Zeichnungen** Sie sehen diese Schaltfläche, wenn eine Zeichnung als Untergrund für ein Gebäudegeschoss im [Geschoss-Konfigurator](https://support.catenda.com/en/articles/6921756-storey-configurator-page) ausgerichtet wurde. Mit dieser Schaltfläche können die ausgerichteten Zeichnungen ein- oder ausgeschaltet werden.

**Karte** Sie sehen diese Schaltfläche, wenn ein Standort in den [Projekteinstellungen](https://support.catenda.com/en/articles/4670273-project-settings-page) konfiguriert wurde. Mit dieser Schaltfläche kann die Karte ein- oder ausgeschaltet werden.
