# Mengenermittlung (QTO)

Das QTO-Menü finden Sie als zweites Menü im [Informationsfenster](https://support.catenda.com/de/articles/8238584-informationsbereich).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/8drgvwsx/01-intro.png)

Mit dieser Funktion können Sie eine Eigenschaftenliste der Objekte anzeigen und exportieren, die im [3D-Viewer](https://support.catenda.com/de/articles/8227211-3d-viewer) oder im [Baum-Panel](https://intercom.help/bimsync-arena/de/articles/4670290-modellbaum-panel) ausgewählt sind. Mit dieser Liste können Sie einfach genaue Messungen der Mengen verschiedener Objekte in Ihrem Modell erhalten. Um zu beginnen, wählen Sie bitte ein Objekt im [3D-Viewer](https://support.catenda.com/de/articles/8227211-3d-viewer) oder im [Baum-Panel](https://intercom.help/bimsync-arena/de/articles/4670290-modellbaum-panel) aus, um seine Eigenschaften und zugehörige Informationen im Inspektionsmenü anzuzeigen. Nachdem Sie einige Objekte ausgewählt haben, kann das QTO-Menü ungefähr so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/8drgvwsx/02-intro.png)

## 1. **Filter und Export**

Mit der Filterleiste können Sie nach einem beliebigen Wert in Ihren Eigenschaften filtern.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/8drgvwsx/03-filter-and-export.png)

> **Hinweis:** Wenn Ihr Filter nicht angewendet wird, liegt dies möglicherweise daran, dass Ihr Filter nicht präzise genug war. Bitte geben Sie mehr Informationen an, damit die richtigen Zeilen gefiltert werden.

Die QTO-Liste kann durch Klicken auf die Schaltfläche "Exportieren" nach Excel oder CSV exportiert werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/8drgvwsx/04-filter-and-export.png)

## 2. **Mengenermittlungsliste**

Die Mengenermittlungsliste ist eine Liste aller Eigenschaften, Mengen und Materialien in den ausgewählten Objekten.

### 2.1 **Kopfzeile**

Die erste Zeile der Mengenermittlungsliste enthält die Gruppe, zu der jede der Eigenschaften des/der ausgewählten Objekt(e) gehört. Wenn eines der Objekte Eigenschaften enthält, die nicht Teil eines Eigenschaftssatzes (PSet) sind, werden diese in einer leeren Gruppe im ersten Feld dieser Zeile zusammengefasst. Mögliche Eigenschaftsgruppen können _Typ, Material, Eigenschaftssatz (PSet)_ sein

In der zweiten Zeile bilden die Namen von Eigenschaften innerhalb ihrer Gruppen die in der Tabelle verfügbaren Spalten. Die beiden Kopfzeilen können ungefähr so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/8drgvwsx/05-header-row.png)

Klicken Sie [hier](https://support.catenda.com/de/articles/11748020-tabellen-in-catenda), um mehr über Tabellen in Catenda zu erfahren.

## 3. **Objektanzahl**

Bis zu 10 000 Objekte können in diesem Menü angezeigt werden, aber es kann nur eine begrenzte Anzahl von Zellen angezeigt werden. Wenn alle Ihre Objekte nur eine Eigenschaft haben, können Sie möglicherweise 10 000 anzeigen, aber wenn sie viele Eigenschaften haben, werden Sie bald feststellen, dass Sie sich dem Limit nähern, was der Browser verarbeiten kann. Sie können sehen, wie viele Objekte unter der QTO-Liste ausgewählt sind.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/8drgvwsx/06-object-count.png)

## 4. **Kurzvideo**

Klicken Sie [hier](https://support.catenda.com/de/articles/6707924-mengenaufmass-qto-kurzvideo), um ein Kurzvideo zum QTO-Menü anzusehen.

## 5. **Objektseite**

Die [Objekt-Seite](https://support.catenda.com/de/articles/12352750-objektseite) führt eine ähnliche Aufgabe wie das QTO-Menü durch: Sie zeigt Zeilen mit den Informationen der Objekte in Ihren Modellen an. Die beiden funktionieren in entgegengesetzten Richtungen und unterscheiden sich darin, wie viel sie exportieren können.

### 5.1 **Objekte finden**

Das QTO-Menü ist dynamisch und wird mit den Objekten aktualisiert, die im 3D-Viewer oder im Baum-Panel ausgewählt sind. Die Objekt-Seite funktioniert umgekehrt. Suchen Sie nach beliebigen Inhalten aus Ihrer IFC mit Logik, um Objekte mit Filtern zu finden, und laden Sie dann die Objekte, die im 3D-Viewer gefunden wurden. Verwenden Sie den ausgewählten Filter auf der Objekt-Seite, um ein ähnliches Ergebnis wie das QTO-Menü zu erhalten.

### 5.2 **Exportieren**

Sowohl das QTO-Menü als auch die Objekt-Seite können nach Excel exportiert werden. Auf der Objekt-Seite werden nur die aktivierten Spalten exportiert, sodass die Spalten in der exportierten Datei durch Aktivieren und Deaktivieren von Spalten in der Produkttabelle begrenzt werden können. Die Objekt-Seite kann auch eine viel größere Anzahl von Zellen als das QTO-Menü verarbeiten, was wichtig ist, da Objekte oft viele Zellen generieren (siehe [Objektanzahl](#object-count)).
