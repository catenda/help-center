# Messung zu Gleitebenen

Dieser Artikel beschreibt, wie die Messwerkzeuge im 3D-Viewer nicht nur zur Messung an Objekten, sondern auch zur Messung an Elementen von Gleitebenen wie Gittern oder Ausrichtungen verwendet werden können. Dies ist ein Beispiel dafür, wie es aussehen kann, wenn Messwerkzeuge wie das Stahllineal, das Punktmessgerät und das Lasermessgerät verwendet werden, um zwischen Gleitebenen-Anmerkungslinien, Gleitebenen-Oberflächen und Objekten aus Modellen zu messen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/01-intro.png)

## 1. **Erste Schritte mit der Messung zu Gleitebenen**

Befolgen Sie diese Schritte, um mit der Messung zu Gleitebenen zu beginnen.

### 1.1 **Gleitebenen in der Vorschau anzeigen**

Gleitebenen, die gemessen werden können, werden in den IFC-Modellen definiert, die im Projekt verfügbar sind. Falls Modelle mit Gleitebenen verfügbar sind, wird die [Gleitebenen-Dropdown](https://support.catenda.com/en/articles/4670327-sliding-plane-dropdown) oben rechts des [3D-Viewers](https://support.catenda.com/en/articles/8227211-3d-viewer) angezeigt und kann etwa so aussehen:

![Dropdown für Gleitebenen im 3D-Viewer](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/02-previewing-sliding-planes.png)

Bereiten Sie die Gleitebenen für die Messung vor, indem Sie die Dropdown-Liste öffnen und auf die Augenschaltfläche klicken, um die Anmerkungslinien eines Gitters oder einer Ausrichtung in der Vorschau anzuzeigen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/03-previewing-sliding-planes.png)

### 1.2 **Empfohlene Einstellungen zum Messen**

Genaue Messungen sind wichtig, um Missverständnisse im Projekt zu vermeiden. Es kann daher eine gute Idee sein, die Einstellungen zu überprüfen, bevor Sie mit dem Messen beginnen.

**3D-Viewer-Einstellungen** Die Dropdown-Liste der 3D-Viewer-Einstellungen befindet sich oben rechts des 3D-Viewers und ist mit dem Zahnradsymbol gekennzeichnet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/04-recommended-settings-for-measuring.png)

Da Gleitebenenlinien dünne Anmerkungslinien und Text enthalten, die in einer 3D-Umgebung oft anfällig für sauberes Rendering sind, werden die folgenden [3D-Viewer-Einstellungen](https://support.catenda.com/en/articles/5784718-3d-viewer-settings#h_16d759320b) empfohlen, um die Messerfahrung bestmöglich zu gestalten.

**3D-Viewer-Einstellungen – Anzeigequalität** Standardqualität wird empfohlen, da hochwertige Qualität das Verhältnis von Pixeln, die von Catenda angezeigt werden, zu sichtbaren Pixeln auf dem Bildschirm ändert, was sich negativ auf genaue Messungen auswirken kann.

**3D-Viewer-Einstellungen – Kantenglättung** Es wird empfohlen, diese Einstellung von der Standard-FXAA-Einstellung auf mindestens 2x MSAA oder höher zu ändern. Dünne Linien in 3D sind oft eine Herausforderung, da die Kanten umso gezackter werden, je mehr eine dünne Linie diagonal ist. Die Änderung der Kantenglättungseinstellung hat keine Auswirkungen auf die Genauigkeit der Messung, kann aber beim Sehen der Linien helfen, da gezackte Kanten dazu führen können, dass dünne Linien so dünn werden, dass sie schwer zu visualisieren sind.

**3D-Viewer-Einstellungen – Bodenerhebung** Besonders beim Versuch, eine Anmerkungslinie unter der Erde zu messen, kann es eine gute Idee sein, entweder eine Umgebung ohne Bodenebene zu wählen oder die Bodenebene unterhalb der Höhe der Gleitebene zu verschieben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/05-recommended-settings-for-measuring.png)

**Empfehlung für Anwendungssoftware** Unabhängig davon, welche [Zoomstufe](https://support.catenda.com/en/articles/13927149-application-software-recommendation?q=3d+v) im Browser für die Messung im 3D-Viewer konfiguriert ist, wird empfohlen, die Zoomstufe des Browsers während der Messung nicht zu ändern, da dies die Genauigkeit der Messung beeinträchtigen kann. Stellen Sie den Browser auf die bevorzugte Zoomstufe ein und achten Sie darauf, die Seite nach jeder Zoomstufen-Änderung zu aktualisieren, auch wenn die Zoomstufen-Änderung auf einem anderen Tab durchgeführt wurde oder auf den ursprünglichen Wert zurückgeändert wurde.

## 2. **Messung zu Gleitebenen-Anmerkungslinien**

Jedes der Messwerkzeuge kann auf Gleitebenen-Anmerkungslinien verwendet werden.

### 2.1 **Einrastverhalten**

Wenn Sie mit aktiviertem Fadenkreuz in der Nähe einer Anmerkungslinie schweben, wird das Fadenkreuz an eine Anmerkungslinie eingerastet. Beim Einrasten am Ende einer Anmerkungslinie wird die Mitte des Fadenkreuzes grün. Beim Einrasten in der Mitte einer Anmerkungslinie wird die Mitte des Fadenkreuzes rot.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/inline-96b1b8f9c6c8.png" width="290"/> --- <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/inline-d30d54cd3f18.png" width="290"/>

### 2.2 **Lasermessung an Anmerkungslinien**

Dies ist ein Beispiel dafür, wie es aussehen kann, wenn das Lasermessgerät auf einer Anmerkungslinie eines Gitters verwendet wird.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/06-laser-measure-on-annotation-lines.png)

**Vertikale und horizontale Messung entlang des Anmerkungsliniensegments** Beachten Sie, dass das Fadenkreuz beim Schweben über einer Anmerkungslinie in vertikaler Richtung flach aussieht. Bei der Messung von Anmerkungslinien wird die vertikale Ebene entlang der Anmerkungslinie gemessen. Die grüne Linie ist die horizontale Linie auf dieser Ebene und die rote Linie ist die vertikale Linie auf dieser Ebene, die dem Anmerkungsliniensegment folgt.

Sowohl bei der vertikalen Messlinie (rot) als auch bei der Messlinie horizontal entlang des Segments (grün) verhält sich die Messlinie unterschiedlich je nach den auftretenden Objekten. Wenn in eine Richtung entlang der Messlinie Objekte vorhanden sind, wird eine Linie angezeigt, die den Abstand zum nächsten Objekt misst. Wenn in beide Richtungen entlang der Messlinie Objekte vorhanden sind, wird eine Linie angezeigt, die den Abstand zwischen diesen Objekten misst.

**Messung horizontal in schräger Richtung zum Anmerkungssegment** Die blaue Linie ist die Linie, die in schräger Richtung zum Anmerkungssegment beobachtet wird und horizontal gemessen wird. Wenn in eine Richtung entlang der Messlinie Objekte vorhanden sind, wird eine Linie angezeigt, die den Abstand zum nächsten Objekt misst. Wenn in beide Richtungen Objekte vorhanden sind, werden Linien angezeigt, die die Abstände zum nächsten Objekt in jeder Richtung messen, da diese Linie die Anmerkungslinie selbst schneidet und dazu misst.

**Fehlende Messung** Wenn Objekte in Messy-Richtungen fehlen, werden zusätzlich Koordinaten angezeigt, wie beim Punktmessgerät.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/07-laser-measure-on-annotation-lines.png)

### 2.3 **Stahllineal an Anmerkungslinien**

Das Stahllineal-Werkzeug kann verwendet werden, um sowohl von einem Objekt zu einer Anmerkungslinie als auch von einer Anmerkungslinie zu einer anderen Linie zu messen. Suchen Sie beispielsweise den Abstand zwischen zwei Gitterlinien, indem Sie von einem Punkt auf einer Gitterlinie zu einem Punkt auf einer anderen Gitterlinie messen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/08-tape-measure-on-annotation-lines.png)

### 2.4 **Punktmessung an Anmerkungslinien**

Das Punktmessgerät kann auf Anmerkungslinien genau wie jedes andere Messwerkzeug verwendet werden.

## 3. **Messung zu Gleitebenen-Oberflächen**

Aktivieren Sie die Gleitebenen-Oberfläche, indem Sie auf den weißen Kreis dort drücken, wo sich der Anmerkungslinien-Kreis befindet. Es können mehrere Gleitebenen-Oberflächen gleichzeitig geöffnet werden. Lasermessungen, die an Objekten durchgeführt wurden, können erweitert werden, bis zur Anmerkungslinie. Verwenden Sie dann das "Lasermessgerät" oder das "Stahllineal", um zu aktivierten Gleitebenen-Oberflächen zu messen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/09-measuring-to-sliding-plane-surfaces.gif)
