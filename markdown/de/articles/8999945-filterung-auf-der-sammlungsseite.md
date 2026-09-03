# Filterung auf der Sammlungsseite

Die Such- und Filteroption wird oben im Fenster angezeigt. Sie können nach dem Namen der Sammlung suchen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/svz5chty/01-intro.png)

In der Suchleiste können Sie nach einer beliebigen Sammlung suchen, auf die Sie Zugriff haben.

## 1. **Linkes Filterpanel**

Durch Klicken auf die Filterschaltfläche wird ein Panel auf der linken Seite angezeigt. Durch Aktivieren der Kontrollkästchen grenzen Sie die Suche ein. Diese Filter können oben in der Filterliste gespeichert werden. Wenn Sie einen dieser Filter anwenden, wird der Filtertext zu Ihrer URL hinzugefügt. Wenn Sie diese URL teilen, sieht die Person, die sie öffnet, denselben Filter wie Sie, wenn sie darauf Zugriff hat. Wenn Sie beispielsweise eine URL mit dem aktivierten Filter "Ich folge" teilen, sehen Empfänger die Filter, denen sie folgen, wenn sie die URL öffnen. Wenn Sie den Mauszeiger über einen der Filter im linken Panel bewegen, können Sie auf der rechten Seite des Filters klicken, um andere zuvor angewendete Filter zu entfernen.

## 2. **Gespeicherte Filter**

Klicken Sie [hier](https://support.catenda.com/en/articles/8551755-saving-filters), um mehr über das Speichern eines Filtersatzes zu erfahren

## 3. **Filter**

Klicken Sie auf die Filterschaltfläche oben links, damit ein Panel auf der linken Seite angezeigt wird. Wenn ein Filter angewendet wird, ändert sich die im Browser sichtbare URL. In diesem Artikel werden Filter wie folgt angezeigt: _Filtername im Menü_ - `Filtername in URL=Filteroption in URL`

**Standardfilter** Der Standardfilter ist in der URL zunächst nicht sichtbar. Wenn die Seite zum ersten Mal besucht wird, wird der folgende Filter angewendet. _Sammlungen, denen ich und meine Teams folgen_ - `followers=my-teams,me`

### 3.1 **Aktuellen Filter speichern und freigeben**

Rufen Sie die URL einer gefilterten Seite auf, um diese Seite mit dem angewendeten Filter zu laden. Die angewendeten Filter können oben im Filtermenü gespeichert werden. Klicken Sie [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link), um mehr über das Speichern und Freigeben von Filtern zu erfahren

### 3.2 **Leere Filter ausblenden**

Klicken Sie [hier](https://support.catenda.com/en/articles/8551755-saving-filters), um mehr über die Begrenzung der Filterergebnisse zu erfahren.

### 3.3 **Sammlungen, denen ich folge**

_Ich folge_ - `followers=me` Sammlungen, denen der Benutzer folgt.

_Meine Teams folgen_ - `followers=my-teams` Sammlungen, denen Teams folgen, denen der Benutzer angehört.

_Alle Sammlungen_ - `followers=all` Alle Sammlungen mit oder ohne Follower. Dieser Filter wird automatisch angewendet, wenn die Schaltfläche „x

### 3.4 **Erstellt von mir**

Erstellt von - `createdBy=<Creator GUID>` Es gibt keine Schaltfläche in der Benutzeroberfläche für diesen Filter. Wenn Sie nach Privat oder Mit Projekt geteilt filtern, wird dies automatisch auf Ihren eigenen Benutzer gesetzt, aber Sie können ihn in die GUID eines anderen Benutzers ändern.

Privat - `visibility=private` Mit Projekt geteilt - `visibility=project-members`

### 3.5 **Abgeschlossen**

Abgeschlossen - `finalized=true` Nicht abgeschlossen - `finalized=false`

### 3.6 **Extern geteilt**

Extern geteilt - `sharedBy=email,link`

> **Hinweis:** Wenn Sie hier entweder E-Mail oder Link schreiben, können Sie Ihre Suche eingrenzen

Nicht extern geteilt - `sharedBy=not-shared`

### 3.7 **Datums-Filter**

Veröffentlicht - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Klicken Sie auf Daten auswählen, um Daten auszuwählen, zwischen denen Sie suchen möchten. Klicken Sie [hier](https://support.catenda.com/en/articles/6511685-date-filter), um mehr über den Datums-Filter zu erfahren

## 4. **Text-Suche**

Sie können nach vollständigen Übereinstimmungen von Text in Dateinamen suchen, die mindestens 3 Zeichen lang sind

### 4.1 **Text-Suche**

_Text-Suche_ - `search=test`

**Inhalte, die durchsucht werden können** Sammlungsname

**Großschreibung** Die Text-Suche berücksichtigt Groß- und Kleinschreibung nicht.

**Zeichenmenge** Beliebige Anzahl von Zeichen. Inhalte, die die gesuchte Phrase enthalten, werden gefunden.

**Leerzeichen** Leerzeichen am Anfang einer Suchphrase werden entfernt.
