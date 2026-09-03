# Topic Board aus einem vorhandenen Topic Board

Ein neues Topic Board kann erstellt werden, indem Sie auf die Aktion für das neue Topic Board auf der [Boards-Seite](https://support.catenda.com/en/articles/9413644-boards-page) klicken. Die Aktion finden Sie mit der grünen Schaltfläche oben rechts oder im benachbarten Aktionsmenü. Erforderlicher Zugriff: Schreibzugriff zum Erstellen neuer Topic Boards im Zugriffsmenü auf der [Projekteinstellungsseite](https://support.catenda.com/en/articles/4670273-project-settings-page).

Dies ist ein Beispiel für die Seite "Neues Topic Board":

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/01-intro.png)

## 1. **Name**

Geben Sie dem Topic Board einen Namen als Mindestanforderung zum Hinzufügen des Topic Boards. Die Topic Board-Liste wird nach dem Namen des Topic Boards gemäß der typischen [Sortierreihenfolge von Listen](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) auf Catenda sortiert. Es ist daher oft eine gute Idee, eine Namenskonvention zu verwenden, wenn Sie Topic Boards benennen. Hier ist ein Beispiel dafür, wie Topic Boards genannt werden könnten:

![Topic board list introduction document review approved approved with comments rejected documents breeam socre coordination cost projects](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/02-name.png)

## 2. **Beschreibung**

Die Topic Board-Beschreibung ist optional und kann später nur in den Topic Board-Einstellungen von Personen mit vollständigem Zugriff auf das Topic Board angesehen werden. Die Topic Board-Beschreibung folgt den allgemeinen Regeln für die [Formatierung von Beiträgen](https://support.catenda.com/en/articles/8430847-formatting-of-posts) auf Catenda.

## 3. **Einstellungen aus einem vorhandenen Topic Board kopieren**

Um Einstellungen von einem Topic Board bei der Erstellung eines Topic Boards zu kopieren, klicken Sie auf das Menü "Einstellungen aus einem vorhandenen Topic Board kopieren", um ein vorhandenes Topic Board im Projekt auszuwählen, aus dem die Einstellungen kopiert werden sollen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/03-copy-settings-from-an-existing-topic-board.png)

Nach Auswahl des Topic Boards können Sie auswählen, welche Einstellungen kopiert werden sollen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/04-copy-settings-from-an-existing-topic-board.png)

### 3.1 **Status und Typen kopieren**

Aktivieren Sie das Optionsfeld zum Kopieren von Status und Typen, um dieselben Status mit ihrem Statusnamen, ihrer Farbe und ihrem Meta-Status-Typ im zu erstellenden Topic Board zu erhalten.

### 3.2 **Berechtigungseinstellungen kopieren**

Aktivieren Sie das Optionsfeld zum Kopieren von Berechtigungseinstellungen, um dieselben Status mit ihrer Farbe im zu erstellenden Topic Board zu erhalten.

## 4. **BCF 1.0-Kompatibilität**

Topic Boards, die zum Exportieren von Topics in andere Topic-Management-Tools verwendet werden, die nur BCF bis Version 1.0 unterstützen, sollten zur Kompatibilität gesperrt werden, um sicherzustellen, dass die in Catenda generierten Topics auf der anderen Seite fehlerfrei ankommen. BCF 1.0-Topics, die anderswo generiert werden, können in jedes Topic Board importiert werden, unabhängig davon, ob das Board zur Kompatibilität gesperrt ist oder nicht.

### 4.1 **Bearbeitung von Status und Typen nicht möglich**

Durch das Sperren eines Topic Boards zur Kompatibilität ist es nicht möglich, die in dem Topic Board verfügbaren Status und Typen zu bearbeiten. Solange das Topic Board zur Kompatibilität gesperrt ist, werden die in BCF 1.0 angegebenen vordefinierten Status und Typen verfügbar gemacht und können nicht bearbeitet werden. _Status:_ "Open" und "Closed" _Typen:_ "Error", "Warning", "Info" und "Unknown"

### 4.2 **BCF 1.0-Kompatibilität nach der Erstellung sperren und entsperren**

Das Kontrollkästchen für die BCF 1.0-Kompatibilität kann in den Topic Board-Einstellungen jederzeit deaktiviert werden, um die Anzahl der möglichen Status im Board zu erhöhen. Wenn die Status in einem Topic Board nicht mit BCF 1.0 kompatibel sind, ist es auch möglich, alle inkompatiblen Status zu entfernen und das Board jederzeit nach der Erstellung erneut zur BCF 1.0-Kompatibilität zu sperren.

### 4.3 **Einstellungen aus gesperrtem Board kopieren**

Wenn ein Topic Board im Menü "Einstellungen aus einem anderen Topic Board kopieren" ausgewählt wird, ist das Kontrollkästchen für die BCF 1.0-Kompatibilität gesperrt und wird je nachdem aktiviert oder nicht, ob das ausgewählte Topic Board, aus dem Einstellungen kopiert werden sollen, zur BCF 1.0-Kompatibilität gesperrt ist oder nicht.

## 5. **Hinzufügen**

Klicken Sie auf "Hinzufügen", um das neue Themen-Board hinzuzufügen.

> **Hinweis:** Das Topic Board muss mindestens einen Namen haben, um hinzugefügt zu werden

Es gibt keine Benachrichtigung bei der Erstellung des Topic Boards.

## 6. **Topic Board-Erstellung bei Projekterstellung**

Bei der Erstellung eines neuen Projekts beginnt das Projekt mit einem Standard-Topic Board namens "Issues". Wenn das Kontrollkästchen für Topic Boards aus einem Template-Projekt bei der Projekterstellung aktiviert ist, beginnt das Projekt mit den Topic Boards und Topic Board-Einstellungen aus dem ausgewählten Template-Projekt.

> **Hinweis:** Während die Einstellungen dieser neuen Topic Boards mit denen im Topic Board in den Templates identisch sind, sind die GUIDs der Topic Boards, Status und Typen für das Projekt eindeutig, in dem sie sich befinden.
