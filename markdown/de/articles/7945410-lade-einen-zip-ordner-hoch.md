# Zip-Datei / Dateistruktur hochladen

Im Gegensatz zum Hochladen einer regulären Zip-Datei entpackt die Funktion "Zip hochladen" eine Zip-Datei. Auf diese Weise können Sie eine Dateistruktur in die [Seite "Dokumente"](https://support.catenda.com/en/articles/8204673-documents-page#h_28610e1d21) importieren, ohne Ordner manuell erstellen zu müssen.

Die Funktion "Zip hochladen" finden Sie im Aktionsmenü rechts neben der grünen Schaltfläche + oben rechts auf der Seite "Dokumente".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/01-intro.png)

## 1. **Zip-Datei auswählen**

Nach dem Klicken auf das Menüelement "Zip hochladen" wird das folgende Dialogfeld geöffnet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/02-selecting-a-zip-file.png)

Der Dateibrowser Ihres Systems sollte automatisch geöffnet werden. Wenn der Dateibrowser nicht geöffnet wurde oder ohne Auswahl einer Zip-Datei geschlossen wurde, können Sie ihn durch Klicken auf die Schaltfläche "Zip-Datei auswählen" erneut öffnen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/03-selecting-a-zip-file.png)

Nach erfolgreicher Auswahl einer Zip-Datei auf Ihrem lokalen System sollten Sie den Namen der Zip-Datei wie unten dargestellt sehen und die Schaltfläche "Zip hochladen" wird dunkelgrün hervorgehoben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/04-selecting-a-zip-file.png)

Wenn Sie keinen Ordner im Abschnitt "Dokumente" angegeben haben, wird angezeigt, dass der Inhalt in den Root-Ordner extrahiert wird. Dies bedeutet, dass Sie den Inhalt sehen, sobald Sie die Seite "Dokumente" öffnen. Es ist auch möglich, in Catenda zu einem Ordner zu navigieren und Ihre Zip-Datei dort hochzuladen, wenn die Dateistruktur dort angezeigt werden soll.

## 2. **Hochladen konfigurieren**

Die Einstellungen können für Elemente mit Namen in der Zip-Datei konfiguriert werden, die bereits an dem Ort vorhanden sind, an dem die Zip-Extraktion versucht, sie im Catenda-Projekt zu platzieren.

### 2.1 **Ordner**

Neue Ordner werden nur erstellt, wenn an dem Ort, an den die Zip-Datei einen Ordner extrahiert möchte, noch kein Ordner mit diesem Namen vorhanden ist. Alle Elemente in einem Ordner, für den bereits ein Ordner mit dem gleichen Namen vorhanden ist, werden in den vorhandenen Ordner mit dem gleichen Namen im Catenda-Projekt eingefügt.

### 2.2 **Dokumente**

Verschiedene Verhaltensweisen können dafür konfiguriert werden, wie die Extraktion der Zip-Datei funktioniert, wenn ein Dokument mit dem gleichen Namen wie die Datei in der Zip-Datei bereits am gleichen Ort vorhanden ist, an den die Zip-Datei versucht, es im Catenda-Projekt zu extrahieren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/05-documents.png)

**Neue Revision erstellen - Standard** Wenn ein Dokument mit dem gleichen Namen am gleichen Ort vorhanden ist, an den die Zip-Datei versucht, eine Datei zu extrahieren, wird eine neue Revision in diesem Dokument erstellt.

**Überspringen und fortfahren** Wenn ein Dokument mit dem gleichen Namen am gleichen Ort vorhanden ist, an den die Zip-Datei versucht, eine Datei zu extrahieren, wird die Datei übersprungen und es wird keine neue Revision im Dokument erstellt.

### 2.3 **Status anwenden**

Wenn der Status-Workflow in Ihrem Projekt aktiviert wurde, können Sie konfigurieren, welchen Status neue Dokumente haben werden. Wenn Sie die Option "Neue Revision erstellen" wählen, wird der Status von Dokumenten, die eine neue Revision erhalten, automatisch geändert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/06-apply-status.png)

Es ist nur möglich, zwischen freigegebenen Revisionsstatus zu wählen. Nach dem Hochladen finden Sie die freigegebenen Revisionen auf der Registerkarte "Arbeitsbereich" und können diese später veröffentlicht werden.

## 3. **Hochladen**

Nach dem Klicken auf "Zip hochladen" wird Ihre Zip-Datei hochgeladen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/07-uploading.png)

Sie können mit Catenda auf einer anderen Registerkarte arbeiten, während Sie auf das Ende des Hochladens warten.

**Erforderlicher Zugriff:** Schreibzugriff auf jeden der Orte, an denen Ordner und Dokumente erstellt werden Schreibzugriff auf Dokumentrevisionen, die hinzugefügt werden.

## 4. **Entpacken**

Nach dem Hochladen Ihrer Zip-Datei beginnt Catenda mit dem Entpacken Ihrer Zip-Datei. Während des Entpackens wird das folgende Menü unten links angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/08-extracting.png)

Sie können dieses Menü beim Durchsuchen von Catenda offen lassen oder schließen, wenn Sie möchten. Sie könnten sogar den Browser während des Entpackungsprozesses ganz schließen. Die Zip-Datei wird im Hintergrund weiter entpackt. Wenn Sie Catenda auf einer anderen Registerkarte verwendet haben, während die Zip-Datei entpackt wird, sehen Sie, dass die Ordner, Dokumente und Revisionen an dem Ort, an dem Sie extrahiert haben, durch Aktualisieren der Seite angezeigt werden.

### 4.1 **Extraktion abgeschlossen**

Wenn das Entpacken der Zip-Datei abgeschlossen ist, wird im Dialogfeld "abgeschlossen" angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/09-extraction-completed.png)

Klicken Sie auf "Details anzeigen", um zu sehen, welche Dateien extrahiert wurden. Sie können diese Details später unter "Meine Zip-Uploads" wie unten erläutert finden. Aktualisieren Sie die Seite, um alle hochgeladenen Dateien zu sehen.

### 4.2 **Benachrichtigung: Zip-Import abgeschlossen**

Wenn Sie das Dialogfeld, den Browser geschlossen oder die Seite aktualisiert haben, wird das Dialogfeld nicht mehr angezeigt. Sie erhalten auch eine Benachrichtigung, dass das Entpacken Ihrer Zip-Datei abgeschlossen ist. Auf diese Weise wissen Sie, wann Ihr Zip-Upload abgeschlossen ist, auch wenn Sie das Entpackungsdialogfeld nicht mehr sehen.

## 5. **Das Größenlimit umgehen**

Mit dem Hochladen einer ZIP-Datei können Sie Dateien hochladen, die größer als 7 GB sind, da die ZIP-Datei die Datei komprimiert.

## 6. **Meine Zip-Uploads**

Die Option unter dem Zip-Upload im Aktionsmenü zeigt Ihnen einen Überblick über Ihre vorherigen Zip-Uploads. So können Zip-Importe mit den verschiedenen möglichen Status aussehen:

### 6.1 **Entpacken**

Während die Zip-Datei entpackt wird, erscheinen die extrahierten Dateien als Zeilen in der Dokumenttabelle.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/10-extracting.png)

**Abgeschlossen** Wenn der Zip-Import abgeschlossen ist, werden alle Dateien extrahiert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/11-extracting.png)

### 6.2 **Zip-Importseite**

Klicken Sie auf einen Zip-Import, um weitere Informationen zum Importprozess anzuzeigen. Dies ist ein Beispiel für die Zip-Importseite eines abgeschlossenen Zip-Imports:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/12-zip-import-page.png)

Dies ist ein Beispiel für das rechte Menü der Zip-Importseite eines abgeschlossenen Zip-Imports:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/13-zip-import-page.png)

## 7. **Desktop Connector**

Mit dem [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) können Sie automatisch und regelmäßig die neuesten Versionen von Dokumenten von Ihrem lokalen System zu Catenda Hub hochladen. Der Desktop Connector ist schneller als der reguläre Upload-Prozess und minimiert das Ausfallrisiko, da Dokumente dateiweise statt in einem großen Drag-and-Drop- oder Zip-Upload-Batch hochgeladen werden.
