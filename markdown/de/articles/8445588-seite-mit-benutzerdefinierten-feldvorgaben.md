# Seite mit benutzerdefinierten Feldvorgaben

Sie können die Seite eines benutzerdefinierten Felds aufrufen, indem Sie auf das entsprechende Feld auf der [Seite "Benutzerdefinierte Felder"](https://support.catenda.com/en/articles/6550459-custom-fields-page) klicken, die Sie als Unterseite der [Seite "Projekteinstellungen"](https://support.catenda.com/en/articles/4670273-project-settings-page) finden.

Wenn Sie ein benutzerdefiniertes Feld erstellen, können Sie es zu einem issue board hinzufügen. Issues in diesem Board erhalten dann ein neues Feld in der Kopfzeile. Sie können auch eine Spalte in der issue board-Tabellenansicht sehen und können nach diesen Feldern filtern.

## 1. **Neues Element-Aktionsmenü**

Administratoren finden Aktionsschaltflächen oben rechts auf der Inhaltsseite eines benutzerdefinierten Felds.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/01-new-item-action-menu.png)

_Neues benutzerdefiniertes Feld_ Klicken Sie auf die grüne Plus-Schaltfläche oben rechts oder auf die Aktion "Neues benutzerdefiniertes Feld" im Aktionsmenü, um ein [neues benutzerdefiniertes Feld](https://support.catenda.com/en/articles/8445575-creating-a-custom-field) zu erstellen

**Archivieren** Öffnen Sie das Aktionsmenü mit den drei Punkten oben rechts, um die Aktion "Archivieren" oben rechts zu finden. Es ist nur möglich, ein benutzerdefiniertes Feld zu archivieren. Es ist nicht möglich, ein benutzerdefiniertes Feld zu löschen.

Statt zu löschen, können benutzerdefinierte Felder nur archiviert werden. Ein archiviertes benutzerdefiniertes Feld wird aus

## 2. **Benutzerdefiniertes Datumsfeld**

Ein Datumsfeld zeigt ein Datum im gregorianischen Kalender an. Das Datum wird in dem Format angezeigt, das auf der Kontoseite für jedes Mitglied konfiguriert ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/02-date-custom-field.png)

Dieses Feld kann verwendet werden, um das Datum der ursprünglichen Erstellung zu registrieren, wenn die Information einige Zeit vor der Einreichung bei Catenda erstellt wurde und die Metadaten bekannt, aber nicht in den Dokumentmetadaten oder im Titel widergespiegelt sind.

## 3. **Benutzerdefiniertes Feld für Dezimalzahlen**

Ein Dezimalzahlfeld zeigt bis zu 6 Stellen nach dem Komma an. Wenn mehr als 6 Stellen nach dem Komma vorhanden sind, wird die wissenschaftliche Schreibweise verwendet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/03-decimal-number-custom-field.png)

Dieses Feld wird häufig verwendet, um Beträge wie Materialkosten oder Budgetauswirkungen zu registrieren.

**Limit** Benutzerdefinierte Dezimalfelder haben ein Limit von Werten zwischen `-0.000000001` und `2147483647` pro ausgefülltem ganzzahligem benutzerdefinierten Feld. Benutzerdefinierte Dezimalfelder haben ein Limit von 17 Zahlen kombiniert vor und nach dem Dezimaltrennzeichen. Für höhere Zahlen kann die wissenschaftliche Schreibweise verwendet werden. Zum Beispiel `1.0991234567890123e+22` Die Zeichenmenge kann durch eine Namenskonvention zur Verwendung im Dokumentupload-Namen weiter begrenzt werden.

## 4. **Benutzerdefiniertes Dropdown-Feld**

Um zur Seite des benutzerdefinierten Felds eines Dropdown-Felds zu gelangen, klicken Sie auf ein Dropdown-Feld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/04-dropdown-custom-field.png)

Wenn ein benutzerdefiniertes Dropdown-Feld zum ersten Mal erstellt wird, werden Sie automatisch zu dieser Seite weitergeleitet. Eine Seite mit benutzerdefinierten Dropdown-Feldern kann ungefähr so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/05-dropdown-custom-field.png)

### 4.1 **Titel und Beschreibung**

Administratoren können Titel und Beschreibung des Felds ändern, indem sie auf den Stift klicken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/06-title-and-description.png)

### 4.2 **Aktive und deaktivierte Registerkarten**

Unter der Beschreibung ist die Registerkarte "Aktiv" standardmäßig aktiviert. Klicken Sie auf die Registerkarte "Deaktiviert", um zuvor deaktivierte Dropdown-Werte anzuzeigen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/07-active-and-disabled-tabs.png)

**Wiederherstellen** Verwenden Sie die Aktion "Wiederherstellen", um einen zuvor deaktivierten Dropdown-Wert wiederherzustellen

> **Hinweis:** Jeder Wert in der Liste der aktiven Werte muss einen eindeutigen Namen haben. Stellen Sie daher sicher, dass der Name nicht bereits verwendet wird, wenn Sie einen Wert wiederherstellen.

### 4.3 **Dropdown-Optionen** - Aktive Liste

In der aktiven Liste finden Sie die Dropdown-Optionen, die derzeit aktiv sind.

_Anker_ Administratoren können die Reihenfolge der Optionen konfigurieren, indem sie auf den Anker in der linken Spalte ziehen.

**Name** Hier sehen Benutzer den Namen einer Dropdown-Option. Wenn das Dropdown-Feld [zu einem Themen-Board hinzugefügt](https://support.catenda.com/en/articles/6563368-custom-fields-in-a-topic-board) wurde, sehen Sie diesen Namen als Option in der Liste. Ein Name kann nur einer Option zugewiesen werden.

**Code** Hier sehen Benutzer den Code einer Dropdown-Option. Der Code wird verwendet, um [einen Block mit einer Namenskonvention zu identifizieren](https://support.catenda.com/en/articles/7869240-how-to-use-custom-fields-in-naming-convention). Ein Code kann nur einer Option zugewiesen werden.

**Bearbeiten und Deaktivieren** Administratoren können den Namen einer Option nach ihrer Erstellung bearbeiten. Wenn das Feld noch keinen Code hat, können Sie einen Code hinzufügen. Klicken Sie nach der Bearbeitung auf "Speichern" oder "Abbrechen", um zu bestätigen.

Administratoren können Optionen deaktivieren, indem sie auf "Deaktivieren" klicken und auf "Bestätigen" klicken. Das Deaktivieren ist ähnlich wie das Löschen, da die Option überall auf Catenda Hub verschwindet, aber später aus der deaktivierten Liste wiederhergestellt werden kann.

Nach dem Hinzufügen eines Codes ist es nicht mehr möglich, den Code zu bearbeiten. Wenn Sie einen anderen Code verwenden möchten, können Sie die Option deaktivieren und eine neue Option erstellen.

### 4.4 **Dropdown-Optionen -** Deaktivierte Liste

Hier finden Sie alle Optionen, die derzeit deaktiviert sind. Administratoren können auf "Wiederherstellen" klicken, um beliebige deaktivierte Optionen wiederherzustellen.

### 4.5 **Option hinzufügen**

Nach der Erstellung hat ein benutzerdefiniertes Dropdown-Feld noch keine Optionen. Administratoren können Optionen hinzufügen, indem sie unten links auf die Schaltfläche "Optionen hinzufügen" klicken

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/08-adding-an-option.png)

Nachdem Sie auf "Optionen hinzufügen" geklickt haben, wird das folgende Dialogfeld angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/09-adding-an-option.png)

_Name_ Hier können Sie für jede Dropdown-Option einen Namen und einen Code hinzufügen.

**Code** Der Code wird verwendet, um [einen Block mit einer Namenskonvention zu identifizieren](https://support.catenda.com/en/articles/7869240-how-to-use-custom-fields-in-naming-convention). Code ist ein eindeutiger Wert, den Sie für ein Element festlegen können. Das bedeutet, dass Sie denselben Code nicht zweimal hinzufügen können.

**Fehlerbehebung für Namen und Code** Klicken Sie [hier](https://support.catenda.com/en/articles/13750419-custom-field-content-troubleshooting), um mehr zu erfahren, wenn es Probleme mit dem Namen und Code gibt.

### 4.6 **Mehrere Optionen hinzufügen**

In einem Dropdown-Feld möchten Sie häufig mehrere Optionen hinzufügen. Wenn Sie einen Namen hinzufügen und auf "Absenden" klicken, müssen Sie jedes Mal auf "Optionen hinzufügen" klicken, wenn Sie eine Option hinzufügen möchten, was zeitaufwändig sein kann. Es gibt daher mehrere Möglichkeiten, Optionen schnell hinzuzufügen.

**Beim Absenden offen lassen** Um Option für Option hinzuzufügen, können Sie das Kontrollkästchen "Beim Absenden offen lassen" aktivieren. Wenn dieses Kontrollkästchen aktiviert ist, können Sie den Namen der nächsten Option direkt nach dem Absenden der vorherigen Option hinzufügen, sodass Sie nicht immer auf "Optionen hinzufügen" klicken müssen.

**Mehrere Optionen hinzufügen** Wenn Sie Ihre Optionen bereits außerhalb von Catenda vorbereitet haben, können Sie sie auf gute Weise einfügen, indem Sie auf die Schaltfläche "Mehrere Optionen hinzufügen" klicken. Wenn Sie auf diese Schaltfläche klicken, ändert sich das Dialogfeld, und Sie können eine Zeichenkette einfügen. Wenn Catenda die Zeichenkette richtig interpretieren kann, werden die Namen und Codes Ihrer eingefügten Optionen erkannt und können sofort eingereicht werden.

**Erstellen einer Einfügekette**

- Excel-Kopie einfügen

Eine einfache Möglichkeit, eine Einfügekette zu erstellen, besteht darin, Zeilen und Spalten aus einer Tabellenbearbeitungssoftware wie Excel zu kopieren. Wenn Sie Ihre Namen in der ersten Zeile und optional Ihre Codes in der zweiten Zeile hinzufügen, können Sie sie kopieren und in das Einfügedialogs einfügen. Ihre Namen und Codes werden dann automatisch richtig formatiert.

- Kommagetrennte Zeichenkette

Um eine Zeichenkette zu erstellen, die sich in einen Satz von Optionen umwandelt, trennen Sie Ihre Optionen durch ein "Komma" `,` oder einen "Zeilenumbruch" `\n`. Zum Beispiel wird "Electrical,Architecture" in die Optionen `Electrical` und `Architecture` umgewandelt

- Namen und Codes in einer Zeichenkette

Optional können Sie einen Code zu Ihrer Option hinzufügen, indem Sie ihn durch einen "Tab", "Doppelpunkt" `:`, "Semikolon" `;` und "Pipe" `|` trennen. Zum Beispiel wird "Electrical:el,Architecture:arc" in die Option `Electrical` mit dem Code `el` und die Option `Architecture` mit dem Code `arc` umgewandelt.

Nach dem Einfügen der Zeichenkette in das Einfügefeld können Sie an eine beliebige Stelle auf der Seite klicken, um zu prüfen, ob Ihre Formatierung erfolgreich war.

> **Hinweis:** Wenn das Dropdown-Feld zu einem Themen-Board hinzugefügt wird, spielt es eine Rolle, wie viele Felder Sie hinzufügen und ob Ihr Feld erforderlich ist. Wenn es bis zu 10 Felder gibt, können Sie nach jedem einzelnen Feld filtern. Wenn das Feld nicht erforderlich ist, kann das Feld danach gefiltert werden, ob das Feld gesetzt ist oder nicht.

**Limit** Während es möglich ist, bis zu 450 Optionen auf einmal hinzuzufügen, wird empfohlen, bis zu 100 Optionen auf einmal hinzuzufügen.

### 4.7 **Limit**

Benutzerdefinierte Dropdown-Felder haben ein Limit zur Auswahl einer Option von bis zu 1000 Optionen pro benutzerdefinierten Dropdown-Feld.

## 5. **Ganzzahliges benutzerdefiniertes Feld**

Ein ganzzahliges benutzerdefiniertes Feld zeigt ganze Zahlen an.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/10-integer-custom-field.png)

Bei diesem Feld sind nur ganze Zahlen zulässig, keine Dezimalzahlen. Dies wird häufig verwendet, um Vorkommen zu registrieren.

**Limit** Ganzzahlige benutzerdefinierte Felder haben ein Limit von Werten zwischen `-2147483648` und `2147483647` pro ausgefülltem ganzzahligem benutzerdefinierten Feld. Die Zeichenmenge kann durch eine Namenskonvention zur Verwendung im Dokumentupload-Namen weiter begrenzt werden. Für höhere Zahlen kann ein Dezimalfeld mit wissenschaftlicher Schreibweise verwendet werden.

## 6. **Benutzerdefiniertes Textfeld**

Ein benutzerdefiniertes Textfeld zeigt eine Textzeichenkette an.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/11-text-custom-field.png)

Der Text wird in einer Zeile angezeigt. Ein gutes Beispiel für ein Textfeld ist ein Feld namens "Kommentar", das ausgefüllt und aus der Tabellenansicht angezeigt werden kann. In Namenskonventionen wird es häufig verwendet, um eine bestimmte Anzahl von Zeichen zu begrenzen, die für ein Feld in einem Dokumenttitel zulässig sind.

**Limit** Benutzerdefinierte Textfelder haben ein maximales Limit von 200 Zeichen pro ausgefülltem benutzerdefinierten Textfeld. Die Zeichenmenge kann durch eine Namenskonvention zur Verwendung im Dokumentupload-Namen weiter begrenzt werden.
