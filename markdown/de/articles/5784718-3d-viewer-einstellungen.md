# 3D Viewer-Einstellungen

Die 3D Viewer-Einstellungen finden Sie oben rechts im [3D Viewer](https://support.catenda.com/en/articles/8227211-3d-viewer).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/01-intro.png)

> **Hinweis:** Stellen Sie sicher, dass die Hardware und Software, auf denen Catenda geöffnet ist, [wie empfohlen](https://support.catenda.com/en/articles/6921941-hardware-recommendation) konfiguriert sind, da dies Auswirkungen darauf hat, wie der Viewer angezeigt wird.

## 1. **Aktivierung des 3D Viewers**

Der 3D Viewer kann auf eine der folgenden Arten geöffnet werden: Aktivieren Sie das 3D-Panel mit den Schaltflächen oben rechts (Shift + 2).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/02-enabling-the-3d-viewer.png)

Aktivieren Sie ein 3D-Modell von der Dashboard-Seite.

Aktivieren Sie ein 3D-Modell aus der Viewer-Spalte in der Modellierungstabelle. (Abbildung oben)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/03-enabling-the-3d-viewer.png)

Wählen Sie Modelle auf der Modellseite aus und verwenden Sie die 3D-Aktion mit ausgewählten Modellen auf der Modellseite.

Aktivieren Sie ein 3D-Dokument aus der Viewer-Spalte in der Tabelle "Dokumente" auf der Dokumentenseite. Klicken Sie auf das Zahnradsymbol, um die **3D Viewer-Einstellungen** anzuzeigen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/04-enabling-the-3d-viewer.png)

## 2. **Rendering**

So kann das Rendering-Menü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/05-rendering.png)

### 2.1 **Räume anzeigen**

_Standardmäßig aus_ - [Räume aktivieren und deaktivieren](https://support.catenda.com/en/articles/4670315-how-can-i-show-spaces-in-catenda-hub). Räume sind im 2D Viewer weiterhin auswählbar, wenn sie sich im Modell befinden.

### 2.2 **Anzeigequalität**

Das Verhältnis zwischen der Anzahl der Pixel, die der Viewport anzeigt, und der Anzahl der physischen Pixel auf Ihrem Bildschirm ist oft gleich. In diesem Fall hat die Anzeigequalitätsoption nicht viel Unterschied. Wenn die Anzahl der Pixel, die der Viewport hat, und die Anzahl der Pixel, auf denen der Viewport auf einem Bildschirm angezeigt wird, unterschiedlich sind, kann die Anzeigequalität die Schärfe des Bildes beeinflussen. Bei Bildschirmen der folgenden Typen kann das Verhältnis zwischen der Anzahl der Pixel, die der Viewport hat, und der Anzahl der Pixel, die der Bildschirm tatsächlich hat, unterschiedlich sein:

- Mobilgeräte
- Anzeigetechnologien, die die Pixeldichte beeinflussen, wie Apple Retina.
- High-DPI-Anzeigen

> **Hinweis:** Stellen Sie sicher, dass die Hardware und Software, auf denen Catenda geöffnet ist, [wie empfohlen](https://support.catenda.com/en/articles/6921941-hardware-recommendation) konfiguriert sind, da dies Auswirkungen auf die Pixelation des Viewers hat.

**Standardqualität** Bei der Standard-Anzeigequalität entspricht die Anzahl der Pixel, die der Viewport hat, der gleichen Anzahl physischer Pixel, die den Viewport auf dem Bildschirm anzeigen. Für Bildschirme, die den Viewport über mehr physische Pixel anzeigen können als der Viewport angibt, kann diese Einstellung das Bild weniger präzise erscheinen lassen. Dieser Modus ist schneller und weniger anspruchsvoll für Ihr Gerät.

**Hohe Qualität** Bei hoher Anzeigequalität wird der Viewport über die volle Anzahl der physischen Pixel angezeigt, die auf dem Teil des Bildschirms verfügbar sind, der den Viewport anzeigt. Für Bildschirme, auf denen der Viewport über mehr Pixel angezeigt werden kann, als er angibt, bietet dies die beste visuelle Qualität, kann aber leistungsintensiver sein.

### 2.3 **Antialiasing**

Pixelgenauigkeit beim Glätten von Diagonallinien in der Reihenfolge der Genauigkeit. Beachten Sie, dass je genauer, desto schwieriger es für das System wird anzuzeigen.

- FXAA
- 2x MSAA
- 4x MSAA
- 8x MSAA

> **Hinweis:** Stellen Sie sicher, dass die Hardware und Software, auf denen Catenda geöffnet ist, [wie empfohlen](https://support.catenda.com/en/articles/6921941-hardware-recommendation) konfiguriert sind, da dies Auswirkungen auf die Genauigkeit von Diagonallinien haben kann.

### 2.4 **Inkrementelles Rendering**

Während der Rotation werden nicht lebensnotwendige Objekte wie Glas in Fenstern und kleine Armaturen vorübergehend ausgeblendet, um die Leistung zu verbessern. Dies macht es möglich, in großen Modellen mit wenig Verzögerung zu rotieren. Wenn viele Objekte in den 3D Viewer geladen werden, ist diese Option ein Muss.

### 2.5 **Umgebungsschatten**

Wenn diese Option aktiviert ist, werden Schatten mit einem Radius von etwa 5 cm in der Überlappung von Objekten angezeigt. Stellen Sie sicher, dass sich Ihre Objekte in echter Weltgröße befinden, damit dies eine bessere Wirkung hat. Bei großen Oberflächen wie dort, wo eine Wand auf einen Boden trifft, ist dies nicht so sichtbar, bis die Kamera sich der Schnittlinie nähert. Bei kleiner Geometrie wie Möbeln, Stahlträgern und Metallbeschlägen ist dies ein Game-Changer. Diese Option hat normalerweise wenig Auswirkungen auf die Leistung.

### 2.6 **Erweiterter Sichtbereich**

Bei massiven Modellen, die mehrere Kilometer lang sind, enden die Objekte oft außerhalb der Standard-Clipping-Distanz von 2 Kilometern. Wenn das Modell aktiviert ist, versucht die Kamera, sich weit genug zu positionieren, um alles anzuzeigen. Wenn die Objekte weit genug entfernt sind, können sie abgeschnitten werden und es wird nichts angezeigt, bis sich die Kamera den Objekten nähert. Mit dieser Option werden Objekte bis zu 50 Kilometer von der Kamera entfernt sichtbar! Beachten Sie, dass dies die Leistung beeinflussen kann. Bei Infrastrukturprojekten ist diese Option oft ein Muss!

### 2.7 **Lichtdurchlässige Opazität**

_5% Standard_ - Wie viel Sie durch durchscheinende Objekte sehen können

### 2.8 **Punktwolken-Einstellungen**

Punktbudget: _1000000 Standard_ - Wie viele Punkte der Punktwolke auf einmal angezeigt werden können. Der Standardwert ist für die meisten Punktwolken mehr als ausreichend, aber die Einstellung ist vorhanden, falls mehr benötigt wird.

## 3. **Navigation**

So kann das Navigationsmenü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/06-navigation.png)

### 3.1 **Walk-Modus**

_1,6 Meter Standard_ - Bindet den Viewer an den darunter liegenden Boden, wenn Sie mit dem Walk-Through-Modus durch das Modell gehen. Ermöglicht es Ihnen, Treppen hinaufzugehen.

### 3.2 **Schrittgeschwindigkeit**

_3 m/s Standard_ - Wie schnell sich der Viewer im Walk-Through-Modus bewegt. Zu Referenzzwecken ist unten eine Tabelle mit allgemeinen Geschwindigkeiten enthalten.

### 3.3 **Elevationsgeschwindigkeit**

_1,5 m/s Standard_ - Vertikale Bewegungsgeschwindigkeit beim Hochfahren und Herunterfahren mit X und C.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Fortbewegungsart</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Typische Geschwindigkeit (m/s)</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Typische Geschwindigkeit (mph)</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Gehen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>1,5</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3,4</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Standard</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>6,7</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Laufen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>5</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>11</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Radfahren</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>7</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>15</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Auto</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>13 - 30</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>29 - 67</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Zug</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>56</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>125</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Flugzeug</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>250</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>560</p></td></tr></tbody></table></div>

### 3.4 **Drehgeschwindigkeit**

_40°/s Standard_ - Wie schnell sich der Viewer um die Kamera dreht, wenn Sie auf dem Bildschirm ziehen

### 3.5 **Blickwinkel**

_60° Standard_ - Diese Einstellung kann gut sein, um sie in Innenräumen wie kleinen Räumen zu vergrößern, damit Sie mehr sehen können. Es kann auch gut sein, diese Einstellung in Modellen mit großen Entfernungen von 2 KM (1,2 Meilen) und mehr zu begrenzen, da Sie Objekte, die weiter entfernt sind, präziser sehen können.

### 3.6 **Navigationseinstellungen zurücksetzen**

Setzen Sie alle Navigationseinstellungen auf ihre Standardposition zurück

## 4. **Umwelt**

So kann das Umgebungsmenü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/07-environment.png)

### 4.1 **Umgebungseinstellung**

Die gewählte Umgebungseinstellung bestimmt, welcher Himmel beim Aufblick und welcher Untergrund beim Abblick angezeigt wird. Beachten Sie, dass der Horizont oft ausgeprägter ist, wenn die Perspektivansicht-Option gewählt wird, da bei der orthogonalen Ansicht der Horizont unendlich weit entfernt ist und nur dann sichtbar ist, wenn die Kamera genau in die horizontale Richtung zeigt.

**Klar** Bei der Einstellung "Klar" werden ein klarer Himmel beim Aufblick und eine grüne Bodenebene beim Abblick im Hintergrund des Viewports angezeigt.

**Teilweise bewölkt** Bei der Einstellung "Teilweise bewölkt" werden ein bewölkter Himmel beim Aufblick und eine grüne Bodenebene beim Abblick im Hintergrund des Viewports angezeigt.

**Neutral** Bei der Einstellung "Neutral" werden ein hellgrauer Himmel beim Aufblick und eine dunkelgraue Bodenebene beim Abblick im Hintergrund des Viewports angezeigt. Diese Einstellung ist großartig für Modelle, die helle Farben haben und schwer von einem hellen Hintergrund zu unterscheiden sind.

**Keine** Bei der Einstellung "Keine" wird ein Farbverlauf angezeigt, der von einem hellgrünen Himmel beim Aufblick zu einer weißen Bodenebene beim Abblick im Hintergrund des Viewports übergeht.

### 4.2 **Bodenhöhe**

Die Bodenhöhenoptionen sind für die Einstellung "Keine" ausgegraut, da diese keine Bodenebene hat. In Einstellungen, in denen die Bodenebene angezeigt wird, wird eine Oberfläche in einer festgelegten Höhe sichtbar, die Schatten von Objekten empfängt, die in den 3D Viewer geladen werden.

_Unter Modell -_ Standard Mit dieser Option wird die Bodenflächenoberfläche in einer Höhe von 0 Metern über dem Meeresspiegel angezeigt.

_Bei Höhe_ Mit dieser Option kann die Bodenflächenoberfläche mit positiven Werten nach oben und mit negativen Werten nach unten verschoben werden. Dies ist großartig in Situationen, wo die Oberfläche durch einen Keller schneidet oder für Objekte, die sonst unter dem Meeresspiegel liegen.
