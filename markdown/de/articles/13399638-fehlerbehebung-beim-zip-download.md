# Fehlerbehebung beim Zip-Download

Wenn ein Ordner oder mehrere Elemente im Dokumentenbereich heruntergeladen werden, wird unten links auf dem Bildschirm ein Dialog angezeigt. In diesem Dialog wird der Fortschritt der Vorbereitung der herunterzuladenden Zip-Datei angezeigt.

## 1. **Reservierte Zeichen im Pfad**

Wenn ein Ordner das Zeichen `/` im Ordnernamen enthält, wird dies als Pfad in der Zip-Datei erkannt und der Ordner wird in mehrere Ordner aufgeteilt, die alle ineinander verschachtelt sind. Alle Elemente im Ordner landen am Ende in dem letzten dieser Ordner. Zum Beispiel wird der Ordner `This/is/a/folder` mit dem Dokument `This-is-a-document.pdf` in eine Zip-Datei mit der folgenden Ordnerstruktur heruntergeladen: This ist ein Ordner This-is-a-document.pdf

## 2. **Nicht herunterladbare Revisionen**

### 2.1 **Entwurfsrevisionen (Legacy)**

Entwurfsrevisionen können nur einzeln im Kontextmenü einer Revision heruntergeladen werden. Wenn nur Entwurfsrevisionen ausgewählt sind, wird eine Zip-Datei vorbereitet, aber sie ist leer. Der neue Revisionstyp, der dies ersetzt, sind freigegebene Revisionen, die wie normale veröffentlichte Revisionen über die Download-Aktion der Dokumenttabelle heruntergeladen werden können, ohne dass es Probleme gibt.

### 2.2 **Zurückgezogene Revisionen**

Wenn die neueste Revision eines der Dokumente in der Auswahl zurückgezogen wurde, kann eine Warnung angezeigt werden, die dem Benutzer mitteilt, dass einige Dateien nicht heruntergeladen werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/169yxgzv/01-withdrawn-revisions.png)

Drücken Sie Weiter, um die Vorbereitung fortzusetzen, oder Abbrechen, um den Download zu stoppen.

## 3. **Noch nicht auf Virus gescannt**

Wenn kürzlich hochgeladene Dateien heruntergeladen werden sollen, ist möglich, dass sie noch nicht auf Viren gescannt wurden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/169yxgzv/02-not-yet-scanned-for-virus.png)

Wenn seit dem Hochladen der herunterzuladenden Dateien einige Zeit vergangen ist, wenden Sie sich bitte an den Support bezüglich nicht gescannter Dateien. Drücken Sie Weiter, um die Vorbereitung fortzusetzen, oder Abbrechen, um den Download zu stoppen.

## 4. **Fehler bei der Download-Vorbereitung**

Wenn bei der Vorbereitung dieser gezippten Datei etwas schiefgeht, kann der folgende Fehler angezeigt werden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/169yxgzv/03-download-preparation-error.png)

Wenn Sie diesen Bildschirm sehen, wenden Sie sich bitte an den Support.
