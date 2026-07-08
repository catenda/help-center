# Ein Zip-Archiv / eine Dateistruktur hochladen

Im Gegensatz zum Hochladen einer normalen Zip-Datei wird die Zip-Upload-Funktion ein Zip-Archiv entpacken. Auf diese Weise können Sie eine Dateistruktur in die [Seite Dokumente](https://support.catenda.com/en/articles/8204673-documents-page#h_28610e1d21) importieren, ohne Ordner manuell erstellen zu müssen.

Die Zip-Upload-Funktion finden Sie im Aktionsmenü rechts neben der grünen Schaltfläche + oben rechts auf der Seite Dokumente.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/01-intro.png)

## 1. **Zip-Datei auswählen**

Nach dem Klicken auf den Menüpunkt Upload Zip wird das folgende Dialogfeld angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/02-selecting-a-zip-file.png)

Der Datei-Browser Ihres Systems sollte automatisch geöffnet werden. Wenn der Datei-Browser nicht geöffnet wurde oder wenn er geschlossen wurde, ohne eine Zip-Datei auszuwählen, können Sie ihn erneut öffnen, indem Sie auf die Schaltfläche Zip-Datei auswählen klicken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/03-selecting-a-zip-file.png)

Nach erfolgreichem Auswählen einer Zip-Datei auf Ihrem lokalen System sollten Sie den Namen der Zip-Datei sehen und die Schaltfläche Upload Zip wird grün hervorgehoben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/04-selecting-a-zip-file.png)

Wenn Sie keinen Ordner im Dokumentbereich eingegeben haben, wird angezeigt, dass der Inhalt in den Stammordner extrahiert wird. Das bedeutet, dass Sie den Inhalt direkt sehen, wenn Sie den Dokumentbereich eingeben. Es ist auch möglich, zu einem Ordner in Catenda zu navigieren und Ihr Zip-Archiv dort hochzuladen, wenn die Dateistruktur dort angezeigt werden soll.

## 2. **Hochladekonfiguration**

Einstellungen können für Elemente mit Namen in der Zip-Datei konfiguriert werden, die bereits an dem Ort vorhanden sind, an dem die Zip-Extraktion versucht, sie im Catenda-Projekt zu platzieren.

### 2.1 **Ordner**

Neue Ordner werden nur erstellt, wenn an dem Speicherort, an dem das Zip-Archiv einen Ordner extrahieren möchte, noch kein Ordner mit diesem Namen vorhanden ist. Alle Elemente in einem Ordner, in dem bereits ein Ordner mit gleichem Namen vorhanden ist, werden in den vorhandenen Ordner mit gleichem Namen im Catenda-Projekt eingefügt.

### 2.2 **Dokumente**

Für die Extraktion der Zip-Datei können verschiedene Verhaltensweisen konfiguriert werden, wenn ein Dokument mit demselben Namen wie die Datei in der Zip-Datei bereits an dem gleichen Ort vorhanden ist, an dem die Zip-Datei versucht, es im Catenda-Projekt zu extrahieren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/05-documents.png)

**Neue Version erstellen - Standard** Wenn ein Dokument mit gleichem Namen an der gleichen Stelle wie die Zip-Extraktion existiert, wird eine neue Version in diesem Dokument erstellt.

**Überspringen und fortfahren** Wenn ein Dokument mit gleichem Namen an der gleichen Stelle wie die Zip-Extraktion existiert, wird die Datei übersprungen und keine neue Version wird in diesem Dokument erstellt.

### 2.3 **Status anwenden**

Wenn der Status-Workflow in Ihrem Projekt aktiviert wurde, können Sie konfigurieren, welcher Status die neuen Dokumente haben werden. Wenn Sie sich für die Option "Neue Version erstellen" entscheiden, wird der Status von Dokumenten, die eine neue Version erhalten, automatisch geändert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/06-apply-status.png)

Es ist nur möglich, zwischen gemeinsamen Versionsstatus auszuwählen. Nach dem Hochladen können die gemeinsamen Versionen auf der Registerkarte Arbeitsbereich gefunden und später veröffentlicht werden.

## 3. **Hochladen**

Nach dem Klicken auf Upload Zip wird Ihr Zip-Archiv hochgeladen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/07-uploading.png)

Sie können weiterhin mit Catenda in einem anderen Browser-Tab arbeiten, während Sie auf das Ende des Hochladens warten.

**Erforderlicher Zugriff:** Schreibzugriff auf alle Speicherorte, an denen Ordner und Dokumente erstellt werden Schreibzugriff auf Dokumentversionen, die hinzugefügt werden.

## 4. **Entpacken**

Nach dem Hochladen des Zip-Archivs beginnt Catenda mit dem Entpacken. Während des Entpackens wird das folgende Menü unten links angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/08-extracting.png)

Sie können dieses Menü offen halten, während Sie in Catenda stöbern, oder es schließen, wenn Sie möchten. Sie können sogar den Browser während des Entpackens ganz schließen. Das Zip-Archiv wird im Hintergrund weiter entpackt. Wenn Sie Catenda in einem anderen Tab verwenden, während das Zip-Archiv entpackt wird, können Sie die Ordner, Dokumente und Versionen schrittweise an dem Speicherort angezeigt bekommen, an den Sie extrahiert haben, indem Sie die Seite aktualisieren.

### 4.1 **Entpacken abgeschlossen**

Wenn das Zip-Archiv fertig entpackt ist, wird in dem Dialogfeld "Abgeschlossen" angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/09-extraction-completed.png)

Klicken Sie auf "Details anzeigen", um zu sehen, welche Dateien extrahiert wurden. Sie können diese Details später in "Meine Zip-Uploads" finden, wie unten erläutert. Aktualisieren Sie die Seite, um alle hochgeladenen Dateien zu sehen.

### 4.2 **Benachrichtigung: Zip-Import abgeschlossen**

Wenn Sie das Dialogfeld, den Browser geschlossen oder die Seite aktualisiert haben, werden Sie das Dialogfeld nicht mehr sehen. Sie erhalten auch eine Benachrichtigung, dass Ihr Zip-Import abgeschlossen ist. Auf diese Weise wissen Sie, wann Ihr Zip-Upload abgeschlossen ist, auch wenn Sie das Entpackungs-Dialogfeld nicht mehr sehen.

## 5. **Größenlimit umgehen**

Mit dem Hochladen eines Zip-Archivs können Sie Dateien hochladen, die größer als 7 GB sind, da das Zip-Archiv die Datei komprimiert.

## 6. **Meine Zip-Uploads**

Die Option unter Zip-Upload im Aktionsmenü ermöglicht es Ihnen, einen Überblick über Ihre bisherigen Zip-Uploads zu sehen. So können Zip-Importe mit verschiedenen möglichen Status aussehen:

### 6.1 **Entpacken**

Während das Zip-Archiv entpackt wird, erscheinen die extrahierten Dateien nach und nach als Zeilen in der Dokumenttabelle.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/10-extracting.png)

**Abgeschlossen** Wenn der Zip-Import abgeschlossen ist, sind alle Dateien extrahiert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/11-extracting.png)

### 6.2 **Zip-Import-Seite**

Klicken Sie auf einen Zip-Import, um weitere Informationen zum Importprozess zu sehen. So kann die Zip-Import-Seite eines abgeschlossenen Zip-Imports aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/12-zip-import-page.png)

So kann das rechte Menü der Zip-Import-Seite eines abgeschlossenen Zip-Imports aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/13-zip-import-page.png)

## 7. **Desktop Connector**

Mit dem [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) können Sie automatisch und regelmäßig die neuesten Versionen von Dokumenten von Ihrem lokalen System in Catenda Hub hochladen. Der Desktop Connector ist schneller als der reguläre Hochladeprozess und minimiert das Fehlerrisiko, da er Dokumente datei-für-datei statt in einem großen Batch hochlädt.
