# Schiebeflächen-Dropdown

Wenn das Projekt Modelle mit Gittern enthält, wird das Schiebeflächen-Dropdown oben links im [3D-Viewer](https://support.catenda.com/en/articles/8227211-3d-viewer#h_2eec7c411b) angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/01-intro.png)

Nach dem Klicken auf das Schiebeflächen-Dropdown beginnen Gitter und Ausrichtungen zu laden, die in den einzelnen Modellen des Projekts verfügbar sind.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/02-intro.png)

Klicken Sie auf das Augensymbol eines Gitters, um die Anmerkungslinien der einzelnen Achsen im 3D-Viewer in der Vorschau anzuzeigen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/03-intro.png)

Dieser Artikel enthält Informationen zu folgenden Themen:

**Anmerkungslinien in der Vorschau anzeigen – Achsen anzeigen**

## 1. **1. Schiebeflächen-Typen**

Es gibt zwei Arten von Schiebeflächen, die angezeigt werden können

### 1.1 **1.1 Gitter**

Gitter sind eine Art von Schiebefläche, die häufig im Wohn-, Geschäfts- und Industriebau verwendet wird und oft Hand in Hand mit Infrastruktur- und Tiefbauprojekten einhergeht. Wenn ein Modell in dem Projekt ein IfcGrid in seiner neuesten Revision enthält, wird es im Schiebeflächen-Menü angezeigt. Die ersten Flächen, die im Schiebeflächen-Dropdown angezeigt werden, sind Gitter. Gitter werden nach den verschiedenen Modellen, aus denen sie stammen, getrennt. Modelle können ein oder mehrere Gitter enthalten, die verschiedene Achsen enthalten. Welche Gitter exportiert werden, hängt vom Exporter der Autorenlösung ab, häufig wird jedoch für jede Geschoßebene des Modells ein separates Gitter exportiert. Für jedes Gitter wird der Name des IfcStorey angezeigt, auf dem sich das Gitter befindet. Diese gleichen Geschosse finden sich auch im Geschoß-Menü des 2D-Viewers. Der Name des Modells, aus dem das Gitter stammt, und die Revisionsnummer werden angezeigt.

### 1.2 **1.2 Ausrichtungen**

Ausrichtungen sind eine Art von Schiebefläche, die häufig im Infrastruktur- und Tiefbau verwendet wird, sich aber auch im Wohn-, Geschäfts- und Industriebau bewährt hat. Wenn ein Modell in dem Projekt ein IfcAlignment in seiner neuesten Revision enthält, wird es im Schiebeflächen-Menü angezeigt. So können Ausrichtungen im Schiebeflächen-Menü aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/04-1-2-alignments.png)

Für jede Ausrichtung werden der Name der Ausrichtung, der Name des Modells, aus dem sie stammt, und die Revisionsnummer angezeigt.

## 2. **2. Anmerkungslinien in der Vorschau anzeigen**

Jede Schiebefläche hat eine Schaltfläche für die Vorschau, die wie ein Auge aussieht.

![Schiebeflächen-Vorschau-Schaltfläche Catenda Hub für Gitter und Ausrichtungen](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/05-2-preview-annotation-lines.png)

Klicken Sie auf das Vorschausymbol einer Schiebefläche, um die Anmerkungslinien der Schiebefläche im 3D-Viewer in der Vorschau anzuzeigen. Sobald das Vorschausymbol grün hervorgehoben wird, sind die Anmerkungslinien der ausgewählten Schiebefläche im 3D-Viewer sichtbar.

**2.1 Schiebeflächen-Anmerkungslinie** Eine Schiebeflächen-Anmerkungslinie besteht aus einer durchgehenden Linie mit einem Kreis und einem Buchstaben an jedem Ende.

Anmerkungslinie Kreisauswahl Klicken Sie auf den Anmerkungslinienkreis an jedem Ende einer Achse oder Ausrichtung, um die Achse oder Ausrichtung zu aktivieren. Der Anmerkungslinie-Kreis für aktivierte Achsen oder Ausrichtungen wird hervorgehoben, wenn er ausgewählt ist. Nach Auswahl einer Anmerkungslinie wird die Vorschau-Fläche, die mit dieser Achse oder Ausrichtung verbunden ist, als transparente Fläche im 3D-Viewer angezeigt. Beachten Sie, dass das Flächensymbol für diese Achse oder Ausrichtung nach der Auswahl auch im Schiebeflächen-Dropdown grün hervorgehoben wird.

Klicken Sie erneut auf den Anmerkungslinie-Kreis, um die Anmerkungslinie abzuwählen und die Fläche auszublenden.

Gittera-Anmerkungsliniengrenzen Für Gitter ist die Anmerkungslinie eine einzelne gerade, planare Linie, die sich leicht über die Grenzen des Modells in der Höhe hinaus erstreckt, die im Schiebeflächen-Dropdown angezeigt wird. Bei Ausrichtungen besteht die Anmerkungslinie aus mehreren geraden oder gekrümmten Segmenten, deren Start- und Endkoordinaten, Höhe und Richtung im Ausrichtungsmenü in der Informationstafel angezeigt werden können.

### 2.1 **2.2 Anmerkungslinien finden**

Da Anmerkungslinien eine 3D-Darstellung haben, stellen Sie sicher, dass sie nicht von Objekten aus anderen Modellen überdeckt werden oder dass die Grundhöhe der Umgebung unter den Anmerkungslinien liegt, sodass diese nicht verdeckt werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/06-2-2-finding-annotation-lines.png)

## 3. **3. Achsen anzeigen**

Rechts neben einem Gitter im Schiebeflächen-Dropdown kann ein Menü zum Anzeigen von Achsen erweitert werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/07-3-show-axes.png)

Erweitern Sie das Menü zum Anzeigen von Achsen, um jede Achse besser zu steuern. Hier kann jede Achse unter ihrem Namen und mit ihren zwei Schiebeflächen-Schaltflächen angezeigt werden.

## 4. **4. Schiebeflächenbutton**

Nach der Aktivierung erstreckt sich die transparente Schiebeflächenoberfläche von der Anmerkungslinie bis zu den oberen Grenzen des Modells ähnlich einer Schnittflächenoberfläche. Im Gegensatz zu einer Schnittflächenoberfläche, die ähnlich transparent aussieht und bewegt werden kann, ist dies ein transparentes Objekt, das nicht von seiner Anmerkungslinie verschoben werden kann. Anders als Schnittflächenoberflächen ist es auch möglich, bis zu Schiebeflächenoberflächen zu messen. Klicken Sie [hier](https://support.catenda.com/en/articles/4670298-measuring-to-grids), um mehr über das Messen zu verschiedenen Schiebeflächenoberflächen zu erfahren.

### 4.1 **4.1 Gitterachsen-Oberfläche**

Die erste Schaltfläche aktiviert die Gitterflächenoberfläche für diese Achse. So können Gitter aussehen, wenn ihre Achsenoberflächen aktiviert sind.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/08-4-1-grid-axis-surface.png)

Klicken Sie auf den Anmerkungskreis am Ende einer Gitterlinie im 3D-Viewer, um die Gitterachsen-Oberfläche zu aktivieren oder zu deaktivieren.

### 4.2 **4.2 Ausrichtungsflächenoberfläche**

Klicken Sie auf das Flächensymbol, um die Ausrichtungsfläche zu aktivieren. Wählen Sie die Ausrichtungsfläche aus, um Informationen zu ihren verschiedenen Segmenten im Inspektionsmenü anzuzeigen.

## 5. **5. Entlang Schiebeflächenbutton schneiden**

### 5.1 **5.1 Entlang Gitterachse schneiden**

Die zweite Schaltfläche für eine Gitterachse im Menü zum Erweitern von Achsen für das Schiebeflächen-Dropdown erstellt eine Schnittfläche entlang der Gitterachse. Ziehen Sie eine Achsen-Schnittfläche, um die Schnittfläche senkrecht entlang der Achse zu verschieben.

### 5.2 **5.2 Entlang Ausrichtung schneiden**

Klicken Sie auf die zweite Schaltfläche mit dem Schnittflächensymbol, um eine Schnittfläche entlang einer Ausrichtung zu erstellen. Ausrichtungs-Schnittflächen funktionieren ähnlich wie Gitter-Schnittflächen, abgesehen vom Klick- und Ziehverhalten. Anstatt senkrecht zur Achse gezogen zu werden, folgt die Ausrichtungs-Schnittflächenoberfläche der Krümmung und Richtung der Segmente in der Ausrichtung, sodass die Fläche immer in einem schiefen Winkel zur Krümmung an ihrer Platzierung entlang der Ausrichtung liegt.

<p class="intercom-align-center no-margin"><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/inline-8520a612b6e1.png" width="150"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/inline-2e858207316f.png" width="150"/></p>

### 5.3 **5.3 Schneiden relativ zur 3D-Kamera**

Bei jeder Schnittfläche, besonders aber bei Ausrichtungs-Schnittflächen können die Grenzen der Schnittflächenoberfläche möglicherweise nicht sichtbar sein, da sie sich außerhalb des Viewport der Kamera befinden könnten oder sogar vollständig hinter der Kamera liegen könnten. Wenn Objekte nach dem Ziehen auf der Schnittfläche zu verschwinden scheinen, könnte dies daran liegen, dass die Schnittfläche hinter der Kamera gezogen wird. In dieser Situation kann es oft hilfreich sein, die Schnittfläche mit der Flip-Schaltfläche im Menü am unteren Rand des 3D-Viewers umzukehren oder herauszuzoomen, damit die Grenzen der Schnittfläche sichtbar sind.
