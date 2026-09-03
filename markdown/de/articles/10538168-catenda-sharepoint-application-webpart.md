# Catenda SharePoint Application - Webpart

Mit dem Catenda-Webpart können Sie den Dokumentbereich eines Catenda-Projekts innerhalb einer SharePoint-Seite durchsuchen. _Catenda-Zugriff erforderlich:_ Lesezugriff zum Durchsuchen der Dokumentstruktur und Schreibzugriff zum Hochladen von SharePoint-Dateien in Catenda.

## 1. **Webpart hinzufügen**

Bearbeiten Sie eine vorhandene Seite oder erstellen Sie eine neue Seite in SharePoint und bearbeiten Sie diese. Bewegen Sie den Mauszeiger über Ihre Seite im Bearbeitungsmodus, bis Sie eine Linie mit einem Plus `----+-----` sehen. Wenn die [Catenda SharePoint-Anwendung](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application) zu Ihrer Website hinzugefügt wurde, können Sie das Catenda Document Webpart in Ihrer Liste der Webparts finden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/01-adding-the-webpart.png)

Sie können dann ein Catenda-Webpart hinzufügen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/02-adding-the-webpart.png)

Wenn Sie Ihr Catenda-Konto noch nicht autorisiert haben, sieht das Webpart so aus:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/03-adding-the-webpart.png)

Wenn Sie eine Seite mit aktiviertem Catenda-Webpart öffnen und Ihr Konto noch nicht autorisiert haben, werden Sie aufgefordert, dies zu tun. Weitere Informationen zum Autorisieren Ihres Kontos finden Sie [hier](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application#h_788fe15988).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/04-adding-the-webpart.png)

Nach der Autorisierung Ihrer Kontoanmeldedaten klicken Sie auf "Webpart-Einstellungen öffnen" oder klicken Sie auf das Stiftsymbol, um das Catenda-Projekt auszuwählen, für das die Besucher der SharePoint-Seite den Dokumentbereich sehen können.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/05-adding-the-webpart.png)

So kann ein konfiguriertes Webpart aussehen, wenn es hinzugefügt wird:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/06-adding-the-webpart.png)

## 2. **Navigation**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/07-navigation.png)

### 2.1 **Anzeigen**

Der Pfad oben im Webpart zeigt das Projekt, das für dieses Webpart konfiguriert wurde, und Ihren aktuellen Speicherort in der Ordnerstruktur an.

### 2.2 **Navigation**

Klicken Sie auf eines der Elemente, um zu diesem Teil der Ordnerstruktur zurückzukehren. Klicken Sie auf den Namen eines Ordners, um diesen Ordner zu öffnen. Klicken Sie auf den Namen eines Dokuments, um es direkt in Catenda zu öffnen.

## 3. **Dokumenttabelle**

Die Dokumenttabelle kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/08-document-table.png)

Wenn Sie Elemente ausgewählt haben, werden Ihnen oben in der Dokumenttabelle die Anzahl der ausgewählten Elemente angezeigt.

### 3.1 **Dokumente und Ordner auswählen**

Wenn Sie außerhalb des Namens des Elements in einer Zeile klicken, wird diese Zeile ausgewählt. Halten Sie die Umschalttaste gedrückt, um alle Elemente zwischen dem zuletzt ausgewählten Element und dem Element, auf das Sie klicken, auszuwählen. Halten Sie die Strg-Taste gedrückt, um Elemente zu Ihrer Auswahl hinzuzufügen oder zu entfernen.

### 3.2 **Catenda-Zugriffseinstellungen**

Jeder Benutzer hat seinen eigenen Zugriff in Catenda, daher können einige Ihrer Projektmitglieder unterschiedliche Ordner und Dokumente sehen als andere.

## 4. **Aktionen im Webpart**

Oben links im Webpart können Sie die folgenden Aktionen ausführen:

### 4.1 **Ordner erstellen**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/09-create-folder.png)

Erstellt einen Ordner in dem Teil der Dokumentstruktur, in dem Sie sich befinden. _Catenda-Zugriff erforderlich:_ Schreibzugriff

### 4.2 **Datei hochladen**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/10-upload-file.png)

Nach dem Klicken wird ein Dateinavigator geöffnet, und Sie können auswählen, welche Dokument(e) Sie hochladen möchten. Nach dem Hochladen des Dokuments sehen Sie es sowohl in Catenda als auch im Webpart. Sie werden die hochgeladene Datei auf diese Weise nicht im SharePoint-Dokumentbereich sehen. Nur in Catenda. _Catenda-Zugriff erforderlich:_ Schreibzugriff Sie können Dateien von Ihrem System auf ein Ziel im Webpart ziehen und ablegen, um diese Dateien in Catenda hochzuladen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/11-upload-file.png)

> **Hinweis:** Wenn Sie einen Ordner ziehen und ablegen, wird dieser als ZIP-Datei veröffentlicht. Wenn Sie eine Ordnerstruktur hochladen möchten, müssen Sie diese von SharePoint herunterladen und über den [ZIP-Upload](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) oder den [Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) in Catenda hochladen.

### 4.3 **Neu laden**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/12-reload.png)

Wenn jemand anderes Änderungen im Catenda-Projekt vorgenommen hat, kann es sein, dass Sie diese noch nicht sehen. In diesem Fall kann es eine gute Idee sein, das Webpart neu zu laden, um die aktuellsten Informationen zu erhalten.

### 4.4 In SharePoint veröffentlichen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/13-publish-to-sharepoint.png)

Veröffentlichen Sie Ihre ausgewählten Dokumente von Catenda in SharePoint. Durch Klicken auf diese Schaltfläche wird der Dialog "In SharePoint veröffentlichen" geöffnet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/14-publish-to-sharepoint.png)

Oben im Dialog sehen Sie, wie viele Elemente Sie veröffentlichen.

**Neuer Speicherort** Wählen Sie "Neuer Speicherort", wenn Sie die ausgewählten Dateien an einem neuen Speicherort in SharePoint veröffentlichen möchten.

**Vorhandene Ziele anzeigen** Wenn die Dateien bereits vorher veröffentlicht wurden und Sie bereits veröffentlichte Dateien aktualisieren möchten, sollten Sie "Vorhandene Ziele anzeigen" wählen.

**Veröffentlichen** Nach dem Konfigurieren des Speicherorts, an dem Sie veröffentlichen möchten, klicken Sie auf "Veröffentlichen".

## 5. **Catenda-Zugriff**

### 5.1 **Kein Zugriff auf das Catenda-Projekt**

Wenn Sie keinen Zugriff auf das konfigurierte Projekt haben, wird die folgende Fehlermeldung angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/15-no-access-to-the-catenda-project.png)

Der unscharfe Teil ist die Projekt-GUID. Wenn es keine gibt oder Sie keinen Zugriff auf Dokumente im Projekt haben, wird "Kein Inhalt - Ordner ist leer" angezeigt.

### 5.2 **Kein Zugriff auf das Erstellen von Ordnern**

Wenn Sie keinen Schreibzugriff auf den Ordner haben, in dem Sie sich befinden, und versuchen, einen neuen Unterordner zu erstellen, wird Ihnen dies angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/16-no-access-to-creating-folders.png)

### 5.3 **Kein Zugriff auf das Hochladen von Dateien**

Wenn Sie keinen Schreibzugriff auf den Ordner oder das Dokument haben und versuchen, eine Datei hochzuladen, wird Ihnen dies angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/17-no-access-to-uploading-files.png)
