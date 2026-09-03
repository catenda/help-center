# Filterung auf der Objektseite

Das Filterfenster auf der Objektseite kann durch Anklicken der Filterschaltfläche links neben der Suchleiste auf der Objektseite geöffnet werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/01-intro.png)
So kann das Such- oder Filtermenü beim Öffnen aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/02-intro.png)

## 1. **Filter**

Klicken Sie oben links auf die Filterschaltfläche, um ein Fenster auf der linken Seite zu öffnen. Wenn ein Filter angewendet wird, ändert sich die im Browser sichtbare URL entsprechend. In diesem Artikel werden Filter wie folgt angezeigt: _Filtername im Menü_ - `Filtername in URL=Filteroption in URL`

**Standardfilter** Der Standardfilter ist anfangs nicht in der URL sichtbar. Wenn die Seite zum ersten Mal aufgerufen wird, wird der folgende Filter angewendet.

**Kein Filter**

### 1.1 **Aktuellen Filter speichern und freigeben**

Rufen Sie die URL einer gefilterten Seite auf, um diese Seite mit dem angewendeten Filter zu laden. Die angewendeten Filter können oben im Filtermenü gespeichert werden. Klicken Sie [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link), um mehr über das Speichern und Freigeben von Filtern zu erfahren.

### 1.2 **Leere Filter ausblenden**

Klicken Sie [hier](https://support.catenda.com/en/articles/8551755-saving-filters), um mehr über die Begrenzung von Filterergebnissen zu erfahren.

### 1.3 **Modelle**

Klicken Sie auf 3D rechts neben der Modellkategorie im Filtermenü, um alle Modelle zu filtern, die derzeit im 3D-Viewer geladen sind.

Modellname - `model=<Model GUID>` Filter für eine Reihe von Projektmodellen.

### 1.4 **Ausgewählt**

Ausgewählt - `selected=true` Filter, um nur Zeilen für Objekte anzuzeigen, die im 3D-Viewer ausgewählt sind.

## 2. **Filter, die nicht im Filterfenster aufgelistet sind**

### 2.1 **Abfrage**

Abfragesuche - `query=<Product>,<Operator>,<Value>` Klicken Sie in die Such- oder Filterleiste, um einen Filter zu konfigurieren, der zwei Werte vergleicht.

**Produkt** Die erste Auswahl kann jede Art von IFC-Produkt sein. So kann das Produktdropdown aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/03-query.png)

**Operator** Der Operator kann nur ausgewählt werden, nachdem ein Produkt ausgewählt wurde. Der Operatorteil des Abfragefilters bestimmt, wie das Produkt mit dem Wert verglichen wird. Je nachdem, ob das Produkt einen beliebigen Wert haben kann oder nur einen begrenzten Satz von Werten haben kann, können verschiedene Operatoren ausgewählt werden:

Immer verfügbare Operatoren: Gleich - `equals` Wenn das ausgewählte Produkt genau den eingegebenen Wert hat

Nicht gleich - `not-equals` Wenn das ausgewählte Produkt nicht genau den eingegebenen Wert hat

Vorhanden - `exists` Wenn "Vorhanden" ausgewählt wird, kann nur ein Produkt ausgewählt werden, kein Wert, da alle Werte Teil dieses Filters sind

Nicht vorhanden - `not-exists` Wenn "Nicht vorhanden" ausgewählt wird, kann nur ein Produkt ausgewählt werden, kein Wert, da alle Werte Teil dieses Filters sind

Operatoren mit begrenztem Wertsatz So kann das Operatordropdown aussehen, wenn die ausgewählte Eigenschaft einen begrenzten Wertsatz hat:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/04-query.png)

Enthält - `contains`

Enthält nicht - `not-contains` Um Ergebnisse über Produkte zu erhalten, die einen bestimmten Wert nicht enthalten

Hat Wert - `has-value` Wenn "Hat Wert" ausgewählt wird, kann nur ein Produkt ausgewählt werden, kein Wert, da alle Werte Teil dieses Filters sind

Operatoren für beliebige Werte So kann das Operatordropdown aussehen, wenn die ausgewählte Eigenschaft einen beliebigen Wert haben kann:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/05-query.png)

Im Bereich - `range-inclusive` Wenn der Operator "Im Bereich" ausgewählt wird, gibt es zwei Wertfelder. So kann es aussehen, wenn ein Bereichsfilter bearbeitet wird:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/06-query.png)

Der Bereich ist alles vom ersten Wert bis zum zweiten Wert.

Größer oder gleich - `greater-than-equals`

Größer als - `greater-than`

Kleiner oder gleich - `less-than-equals`

Kleiner als - `less-than`

**Wert** Das Wertfeld verhält sich je nach den möglichen Werten des ausgewählten Produkts unterschiedlich.

Zahlenwert Wenn das ausgewählte Produkt nur einen Zahlenwert haben kann, werden beim Anklicken des Wertfelds Pfeile angezeigt und es können nur Zahlen eingegeben werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/07-query.png)

Vorgeschlagene Werte Wenn ein Produkt einen Textwert haben kann, kann dieser direkt in das Wertfeld eingegeben werden. So kann das Wertmenü aussehen, wenn das Produkt "Entität" ausgewählt wurde.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/08-query.png)

Wenn Sie in das Wertfeld klicken, wird eine Liste mit vorgeschlagenen Elementen unter dem Feld angezeigt. Wenn das ausgewählte Produkt nur einen begrenzten Wertsatz haben kann, wird dieser begrenzte Wertsatz in der Liste der vorgeschlagenen Elemente angezeigt. Wenn das ausgewählte Produkt einen beliebigen Wert haben kann, zeigt die Liste der vorgeschlagenen Elemente eine Liste mit Werten, die andere Produkte dieser Art haben.
