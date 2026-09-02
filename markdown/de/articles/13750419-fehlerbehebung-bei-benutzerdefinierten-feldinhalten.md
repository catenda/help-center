# Fehlerbehebung bei benutzerdefinierten Feldinhalten

## 1. **Wiederherstellung archivierter Dropdown-Option nicht möglich**

Ein logischer Deadlock tritt auf, wenn versucht wird, eine archivierte Option wiederherzustellen, während der zugeordnete **Name** derzeit von einer aktiven Option verwendet wird. Da ein Name nur einer Option zugewiesen werden kann, wird die Wiederherstellung blockiert. _Erforderlicher Zugriff:_ Administratorzugriff

Um den archivierten Wert wiederherzustellen, können Sie dieser Sequenz folgen:

**Umbenennen des aktiven Werts** Die aktive Option, die derzeit den Namen verwendet, wird von einem Administrator in einen temporären Wert geändert, um den Namen im System freizugeben.

**Archivierte Option wiederherstellen** Auf die **Deaktivierte Liste** wird zugegriffen, und die Aktion **Wiederherstellen** wird für das erforderliche Element ausgewählt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/01-unable-to-restore-archived-dropdown-option.png)

**Daten korrigieren** Die Namen und Codes werden in den korrekten Zustand angepasst.

**Namen zurücksetzen** Der temporäre Name wird auf den ursprünglichen gewünschten Namen zurückgeändert.

## 2. **Eindeutigkeit von Namen und Codes**

Es ist wichtig, zwischen dem **Namen** einer Option und ihrem **Code** zu unterscheiden. Jede Dropdown-Option besteht aus beiden Elementen, und es ist nur möglich, eine Option zu speichern, wenn sowohl der Name als auch der Code innerhalb dieses bestimmten benutzerdefinierten Felds eindeutig sind.

## 3. **Fehler bei doppeltem Namen**

Es ist nur möglich, einem Namen eine Option in einer Dropdown-Liste zuzuweisen. Wenn ein Fehler bei doppeltem Namen angezeigt wird, werden die folgenden Schritte durchgeführt: _Erforderlicher Zugriff:_ Administratorzugriff

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/02-duplicate-name-error.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/03-duplicate-name-error.png)

**Überprüfung der aktiven Liste** Die Liste der aktiven Optionen wird überprüft, um zu bestätigen, ob der Name bereits verwendet wird.

**Überprüfung der deaktivierten Liste** Die deaktivierte Liste wird überprüft, da Namen, die archivierten Elementen zugeordnet sind, im System bleiben.

**Lösung** Es ist nur möglich, fortzufahren, indem entweder ein anderer eindeutiger Name verwendet oder die vorhandene Option, die den Namen enthält, umbenannt wird.

## 4. **Fehler bei doppeltem Code**

Es ist nur möglich, einen Code einer einzelnen Option innerhalb eines benutzerdefinierten Dropdown-Felds zuzuweisen. Der Code ist ein eindeutiger Wert, der zum Identifizieren von Blöcken für Benennungskonventionen verwendet wird. _Erforderlicher Zugriff:_ Administratorzugriff

Wenn ein Fehler bei doppeltem Code angezeigt wird:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/04-duplicate-code-error.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/05-duplicate-code-error.png)

**Überprüfung der aktiven Liste** Die aktive Liste wird überprüft, um zu sehen, ob der Code bereits verwendet wird.

**Überprüfung der deaktivierten Liste** Die deaktivierte Liste wird überprüft, da Codes, die archivierten Elementen zugeordnet sind, diesen eindeutigen Wert immer noch belegen.

**Lösung** Es ist nur möglich, fortzufahren, indem entweder ein anderer eindeutiger Code verwendet oder die vorhandene Option, die den Code enthält, deaktiviert wird.

## 5. Ändern von vorhandenen Codes

Es ist nur möglich, einen Code während der ursprünglichen Erstellung einer Option oder wenn eine bereits vorhandene Option noch keinen zugeordneten Code hat, zu definieren. Nach dem Hinzufügen und Speichern eines Codes wird dieser auf diesen Wert gesperrt und das Feld wird nicht bearbeitbar.

**Bearbeitungsbeschränkungen** Es ist nur möglich, den **Namen** einer Option nach dem Anwenden eines Codes zu ändern. Das Feld **Code** wird ausgegraut angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/06-modifying-existing-codes.png)

Vor Anwendung:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/07-modifying-existing-codes.png)

Nach Anwendung:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/08-modifying-existing-codes.png)

**Wiederherstellen eines Codes** Wenn ein Code bereits von einem archivierten Element verwendet wird, ist es nur möglich, diesen bestimmten Code zu verwenden, indem zuerst die archivierte Option aus der deaktivierten Liste wiederhergestellt wird. Es ist nicht möglich, eine neue Option mit einem Code einzureichen, der technisch noch von einem deaktivierten Element gehalten wird.

**Ändern eines Codes** Um einen völlig anderen Code für einen vorhandenen Namen zu verwenden, ist es nur möglich, dies zu tun, indem die aktuelle Option deaktiviert und eine neue mit dem gewünschten Code erstellt wird.

## 6. Eingabefehler für Ganzzahlfelder

Für Ganzzahlfelder gelten bestimmte Einschränkungen, die zu Dateneingabefehlern führen:

**Nur ganze Zahlen** Es ist nur möglich, ganze Zahlen in einem benutzerdefinierten Ganzzahlfeld zu speichern.

**Nicht-numerische Zeichen** Während es nur möglich ist, Zahlen direkt in das Feld einzugeben, ist es möglich, nicht-numerische Zeichen einzufügen.

**Verhalten der Speicherschaltfläche** Wenn nicht-numerische Zeichen im Feld vorhanden sind, wird die Speicherschaltfläche deaktiviert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/09-input-errors-for-integer-fields.png)

## 7. **Board-Sichtbarkeit und Filterung**

Wenn ein benutzerdefiniertes Feld auf einem issue board nicht sichtbar ist, werden die folgenden Einstellungen überprüft:

**Feldzuweisung** Durch die Erstellung eines benutzerdefinierten Felds kann es zu einem issue board hinzugefügt werden. Das Feld muss dem bestimmten Board hinzugefügt werden, um in der issue-Kopfzeile angezeigt zu werden.

**Tabellenansicht** Es ist nur möglich, benutzerdefinierte Felddaten in einem Listenformat anzuzeigen, wenn die entsprechende Spalte in der issue board-Tabellenansicht ausgewählt ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/10-board-visibility-and-filtering.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/11-board-visibility-and-filtering.png)

**Filterbeschränkungen** Es ist nur möglich, nach benutzerdefinierten Feldern zu filtern, wenn bis zu 10 Felder zugewiesen sind.
