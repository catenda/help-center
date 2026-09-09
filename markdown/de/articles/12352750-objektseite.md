# Objektseite

Die Objektseite befindet sich als Unterseite der Modellseite. Eine Tabelle mit Informationen über die Projektmodelle wird angezeigt. Vergleichsfilter können kombiniert werden, um nur die angeforderten Informationen zu extrahieren. Diese Seite kombiniert Elemente des QTO-Menüs im Informationsbereich und Eigenschaftswertbibliotheken auf der Bibliotheksseite und wird diese schließlich ersetzen.

![Dashboard Modelle Lesezeichen Objekte Geschoss Konfiguration](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/01-intro.png)

## 1. **Suchen oder filtern**

So könnte das Menü zum Suchen oder Filtern auf der Objektseite aussehen

![Ausgewählt Suche oder Filter Auswählen Plus Modelle Ausgewählt Textsuche](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/02-search-or-filter.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/12353642-filtering-on-the-objects-page), um mehr über das Filtern auf der Objektseite zu erfahren.

## 2. **Produkttabelle**

Die Produkttabelle könnte ungefähr so aussehen:

![Ausgewählt 3D Aktionsmenü Herunterladen Einstellungen Entität Spalte GlobalId Spalte LongName Spalte IfcProject IfcBuildingElementProxy eine Zeile ist in der Tabelle ausgewählt](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/03-products-table.png)

Klicken Sie [hier](https://support.catenda.com/en/articles/11748020-tables-on-catenda), um mehr darüber zu erfahren, wie Sie mit Tabellen in Catenda arbeiten.

### 2.1 **Was ist ein Produkt?**

Der Name Produkte kommt daher, dass jede Zeile ein Produkt des Prozesses ist, der beim Importieren einer IFC stattfindet.

### 2.2 **Angezeigte Informationen**

Sobald die neueste Revision eines Modells verarbeitet wurde, kann für jedes in der IFC-Datei erkannte Produkt eine Zeile in der Produkttabelle angezeigt werden. Nur Informationen der neuesten Revisionen der Modelle in einem Projekt werden angezeigt.

### 2.3 **Aktionen für ausgewählte Elemente**

Nach Auswahl einer Elementzeile werden Aktionen für ausgewählte Elemente oben in der Produkttabelle angezeigt. So könnte das Menü für Aktionen ausgewählter Elemente aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/04-selected-item-actions.png)

**Viewer** Klicken Sie auf das 3D-Symbol oder verwenden Sie die Viewer-Aktion, um die ausgewählten Elemente in der Objekttabelle im 3D-Viewer auszuwählen.

**Isolieren** Verwenden Sie die Isolieraktion, um die ausgewählten Elemente in der Objekttabelle im 3D-Viewer zu isolieren.

**Andere ausblenden** Verwenden Sie die Aktion "Andere ausblenden", um alle Objekte im 3D-Viewer außer den ausgewählten Objekten auszublenden.

### 2.4 **Zeileninhalt**

**Zugriff** Nur Produktzeilen für die neuesten Überarbeitungen von Modellen, auf die Mitglieder Zugriff haben, werden angezeigt. _Zugriff erforderlich -_ Lesen

**Produktzeile** Produktzeilen können nicht wie in anderen Tabellen geöffnet werden. Produktzeilen können nur im 3D-Viewer über das Aktionsmenü angezeigt werden.

**Auswahl** Die Zeilenauswahl funktioniert etwas anders als in anderen Tabellen rund um Catenda. Im Gegensatz zu anderen Tabellen rund um Catenda wird die Auswahl nicht zurückgesetzt, wenn Sie zu einer anderen Seite gehen und zurückkommen oder einen Filter ändern. In der Produkttabelle wird die Auswahl nur zurückgesetzt, wenn die Seite aktualisiert wird. Da häufig Tausende von Objekten ausgewählt werden, ist es üblicher, dass ausgewählte Zeilen nicht sichtbar sind. Es könnte ein anderer Filter angewendet werden, sodass die ausgewählten Zeilen nicht mehr in der Tabelle angezeigt werden, aber sie bleiben ausgewählt.

### 2.5 **Exportieren**

Klicken Sie auf die Download-Schaltfläche oben in der Produkttabelle, um sie zu exportieren.

![Schaltfläche zum Herunterladen](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/05-export.png)

Zeilen Es ist nur möglich, alle Zeilen der aktivierten Modelle zu erhalten. Die Auswahl von Zeilen beschränkt die Zeilen in den exportierten Dateien nicht. Der einzige Filter, der die Anzahl der Zeilen begrenzen kann, ist der Modellfilter. Obwohl Zeilen in der Tabelle begrenzt aussehen könnten, enthält die exportierte Datei alle Zeilen für die verfügbaren Modelle.

Spalten Für jede in der Produkttabelle aktivierte Spalte wird eine Spalte in die Datei exportiert. Klicken Sie [hier](https://support.catenda.com/en/articles/11748020-tables-on-catenda), um mehr darüber zu erfahren, wie Sie Tabellenspalten verwalten.

**Objekte exportieren** Wählen Sie im Menü "Objekte exportieren" die Option zum Exportieren in Excel oder CSV:

![Objekte exportieren Excel CSV](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/06-export.png)

**Export wird vorbereitet** Nachdem Sie auf "Exportieren" geklickt haben, wird oben rechts ein Menü angezeigt, das besagt "Tabellenkalkulation wird vorbereitet".

![Export wird vorbereitet Arbeitsmappe wird vorbereitet](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/07-export.png)

Während dieser Zeit können Sie sicher in Catenda navigieren, solange die Seite nicht aktualisiert wird. Wenn die Tabellenkalkulation verfügbar wird, sieht es so aus und die Datei wird im Browser heruntergeladen:

![Export bereit Arbeitsmappe verfügbar](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/08-export.png)

### 2.6 **Spalten**

Einige Spalten in der Produkttabelle sind standardmäßig aktiviert, während andere ausgeblendet und aktiviert werden müssen. So könnte die Spaltenliste in der Produkttabelle aussehen:

![Attribute Typ GlobalId Name Tag Projekt Standort Gebäude Aktualisieren](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/09-columns.png)

**Umschalten** Aktivieren oder deaktivieren Sie alle Spalten mit diesem Umschalter

**Filter** Geben Sie den Namen einer Spalte oder Spaltenkategorie ein, um die Spaltenliste für diese Spalte zu filtern. Es könnte sein, dass sich die gesuchte Spalte in einer eingeklappten Spaltenkategorie befindet. Stellen Sie daher sicher, dass Sie jede Kategorie erweitern, um zu sehen, ob sich das Ergebnis darin befinden könnte.

**Zurücksetzen** Klicken Sie auf die Schaltfläche "Zurücksetzen", um die Spalten auf die Standardspalten zurückzusetzen

Basierend auf der konfigurierten Spaltenreihenfolge werden die ersten Spalten angezeigt, während die Tabelle möglicherweise seitlich gescrollt werden muss, um andere aktivierte Spalten anzuzeigen. Die Standard-Reihenfolge und Sichtbarkeitseinstellung der Spalten auf der Seite "Dokumente" ist wie folgt:

- Attribute
  - Entität
  - GlobalId
  - LongName
  - Name
  - ObjectType

Darüber hinaus kann die Produkttabelle je nach Anzahl der Eigenschaften und Eigenschaftssätze in jedem der Modelle eine beliebige Anzahl von Spalten haben. Jeder Satz von Spalten hat eine Hauptkategorie mit Unterkategorien. Mit der Umschalttaste können Sie die ganze Kategorie aktivieren oder deaktivieren. Kategorien können erweitert werden und jede Spalte in der Kategorie kann einzeln aktiviert/deaktiviert werden.

**Spalteneinstellungen** Im Gegensatz zu anderen Tabelleneinstellungen sind einige typische Einstellungen, die in der Produkttabelle konfiguriert werden können, gesperrt.

Spalteneinstellungen werden zwischen Sitzungen nicht gespeichert. Spalten können nicht neu angeordnet werden, sondern nur aktiviert und deaktiviert. Es ist nicht möglich, die Tabelle durch Klicken auf die Zelle in der Kopfzeile der Spalte nach einer anderen Spalte zu sortieren. Es ist nicht möglich, die Sortierrichtung der Spalte zu ändern, nach der die Tabelle sortiert wird. Es ist nicht möglich, die Zelle in der Kopfzeile aus der Tabelle zu ziehen, um die Zeile zu deaktivieren. Zeilen müssen über die Spaltenliste deaktiviert werden.
