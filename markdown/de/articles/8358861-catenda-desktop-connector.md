# Catenda Desktop Connector

> **Hinweis:** Die Installationsdatei für diese Anwendung finden Sie [hier](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)

Mit dem Catenda Desktop Connector können Sie Hoch- und Herunterladungen der neuesten Versionen von Dokumente planen.

## 1. **Sofortige Hoch-/Herunterladungen**

### 1.1 **Hochladen**

Wählen Sie einen Ordner auf einem lokalen System aus, um alle Ordnerinhalte, einschließlich Dateien in Unterordnern des ausgewählten Ordners, mit dem Desktop Connector in einen angegebenen Ordner auf Catenda Hub hochzuladen.

**Erfolgreiche Uploads** Wenn Sie mehrere Dateien per Drag-and-Drop verschieben oder die ZIP-Upload-Funktion auf Catenda Hub verwenden, laden Sie einen großen Datensatz hoch. Je größer der Upload, desto länger müssen Sie warten, bevor Sie Ihre Dateien in die Catenda Hub-Dokumentstruktur übermitteln können.

**Jeweils eine Datei** Durch das Hochladen von Dateien aus einer Ordnerstruktur nacheinander können Sie mit dem Desktop Connector das Hochladen unterbrechen und später fortsetzen.

**Reduzieren Sie das Risiko von Upload-Ausfällen** Je größer der Upload, desto höher ist das Risiko, dass er auch fehlschlägt. Vielleicht fällt der Strom aus, vielleicht bricht Ihre Internetverbindung für einen Moment ab. Dann müssten Sie den Upload von vorne beginnen.

### 1.2 **Herunterladen**

Wählen Sie ein oder mehrere einzelne Dokumente oder wählen Sie einen Ordner auf Catenda Hub aus, um die Auswahl, einschließlich Dokumente in Unterordnern ausgewählter Ordner, an einen Speicherort auf Ihrem lokalen Computer herunterzuladen.

### 1.3 **Übertragungsgeschwindigkeit**

Das Hoch- und Herunterladen von Dateien mit dem Desktop Connector ist schneller bei der Dateiübertragung als der reguläre Upload-Prozess, da die Dateien über die API importiert werden, ohne den Overhead eines laufenden Browsers oder andere Browser-Einschränkungen zu erfordern. Für die Übertragung einer einzelnen Datei wird Drag-and-Drop mit einem Browser empfohlen, da es einfach zu bedienen ist. Für die Übertragung großer Datenmengen auf einmal oder für diejenigen, die beim Hochladen großer einzelner Dateien Zeit sparen möchten, ist der Desktop Connector jedoch die empfohlene Methode zur Übertragung.

### 1.4 **Zugriff**

Die Zugriffssteuerung, die auf Catenda Hub konfiguriert ist, wird beibehalten. Benutzer können an Speicherorte in der Catenda-Dokumentstruktur hochladen, an denen sie mindestens Schreibzugriff haben, und können nur Dokumente herunterladen, auf die sie mindestens Lesezugriff haben.

## 2. **Synchronisierung**

Dateien können so geplant werden, dass sie in regelmäßigen Abständen hoch- oder heruntergeladen werden.

### 2.1 **Lokales System -> Catenda Hub**

Der Desktop Connector kann sicherstellen, dass Dateien in einem Catenda Hub-Projekt mit dem neuesten Speicherzustand einer Datei auf dem lokalen System aktuell bleiben.

### 2.2 **Catenda Hub -> Lokales System**

Der Desktop Connector kann sicherstellen, dass Dateien auf einem lokalen System mit der neuesten Version eines Dokuments in einem Catenda Hub-Projekt aktuell bleiben.

## 3. **Installation**

Wenn der Catenda Desktop Connector auf Windows installiert wird, erscheinen die Installationsdateien im folgenden Ordner.

`C:\\Program Files\\Catenda Hub Desktop Connector`

### 3.1 **Deinstallation**

Um das Plugin zu deinstallieren, gehen Sie zum folgenden Windows-Menü:

`Windows-Einstellungen -> Apps -> Installierte Apps`

Finden Sie Desktop Connector in der Liste und klicken Sie auf das Menü "Aktionen" auf der rechten Seite, um es zu deinstallieren.

## 4. **Anmelden**

Wenn der Desktop Connector zum ersten Mal geöffnet wird, wird eine Anmeldeanforderung angezeigt. Klicken Sie auf die Schaltfläche "Anmelden", um den Standard-Browser des Systems auf der Catenda-Anmeldeseite zu öffnen. Nach dem Anmelden oder wenn Sie bereits angemeldet sind, klicken Sie auf "Zugriff erlauben", um Zugriff auf das angemeldete Catenda-Konto zu gewähren. Nach dem Klicken auf "Zugriff erlauben" fordert der Browser den Benutzer auf, die Desktop Connector-Anwendung zu öffnen. Wenn Sie die Berechtigung zum Öffnen der Anwendung erteilen, werden Sie zur [Startseite](#home-page) des Desktop Connector weitergeleitet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/01-sign-in.png)

## 5. **Startseite**

So kann der Desktop Connector aussehen, wenn er mit einer gültigen Anmeldung gestartet wird:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/02-home-page.png)

### 5.1 **PC aufwecken**

Wecken Sie den PC aus dem Ruhemodus auf, wenn eine Aufgabe zu dieser Zeit ausgeführt werden soll.

### 5.2 **Beim Start ausführen**

Um den Desktop Connector beim Start auszuführen, wählen Sie diese Option

### 5.3 **Abmelden**

Klicken Sie auf die Schaltfläche "Abmelden" unten rechts, um sich abzumelden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/03-log-out.png)

## 6. **Projektliste**

Es wird eine Übersicht der Projekte angezeigt, auf die das Konto beim letzten Laden der Projektliste Zugriff hatte. Für jedes Projekt wird die Anzahl der konfigurierten Hoch- und Herunterladungsaufgaben angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/04-project-list.png)

### 6.1 **Schaltfläche "Synchronisieren"**

Wenn Sie kürzlich einem Projekt beigetreten sind, klicken Sie auf diese Synchronisierungsschaltfläche, um die neue Liste der Projekte zu laden, an denen das angemeldete Konto beteiligt ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/05-synchronize-button.png)

### 6.2 **Name**

Klicken Sie auf den Namen eines Projekts, um die aktuellen Hoch- und Herunterladungsaufgaben anzuzeigen oder um eine neue Aufgabe zu planen.

### 6.3 **Upload-Aufgaben**

Die Anzahl der aktiven Upload-Aufgaben für dieses Projekt

### 6.4 **Download-Aufgaben**

Die Anzahl der aktiven Download-Aufgaben für dieses Projekt

## 7. **Upload-Aufgabe**

Planen Sie mit dieser Aufgabe ein regelmäßiges Hochladen von Dateien von Ihrem System zu Catenda Hub.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/06-upload-task.png)

### 7.1 **Titel - Erforderlich**

Die Upload-Aufgabe muss mindestens einen Titel haben, um gespeichert zu werden

### 7.2 **Zeitplan-Kalender - Erforderlich**

Die Aufgabe muss mindestens einen ausgewählten Tag haben, um gespeichert zu werden

### 7.3 **Projektposition**

**Server** Klicken Sie auf "Durchsuchen", um das Ziel auf der Seite "Dokumente" in Catenda Hub auszuwählen, wo Dateien synchronisiert werden sollen. Klicken Sie [hier](#server-location), um mehr über die Auswahl des Server-Verzeichnispfads zu erfahren

**Lokal** Wählen Sie den Speicherort auf dem lokalen System aus, von dem Dateien synchronisiert werden sollen.

### 7.4 **Sofort**

Aufgaben müssen nicht gespeichert werden, um den Upload-Prozess zu starten. Klicken Sie auf das Feld "Jetzt hochladen", um diese Aufgabe sofort zu starten. Gespeicherte Aufgaben werden regelmäßig zu der konfigurierten Zeit ausgeführt.

## 8. **Download-Aufgabe**

Planen Sie mit dieser Aufgabe ein regelmäßiges Herunterladen von Dateien von Catenda Hub auf das lokale System.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/07-download-task.png)

### 8.1 **Titel - Erforderlich**

Die Upload-Aufgabe muss mindestens einen Titel haben, um gespeichert zu werden

### 8.2 **Zeitplan-Kalender - Erforderlich**

Die Aufgabe muss mindestens einen ausgewählten Tag haben, um gespeichert zu werden

### 8.3 **Projektposition**

**Server** Wählen Sie den Speicherort auf Catenda Hub aus, von dem Dokumente heruntergeladen werden sollen. Klicken Sie [hier](#server-location), um mehr über die Auswahl des Server-Verzeichnispfads zu erfahren

**Lokal** Wählen Sie den Zielort auf dem lokalen System aus, zu dem Dateien heruntergeladen werden sollen.

### 8.4 **Sofort**

Eine Aufgabe muss nicht gespeichert werden, um mit dem Herunterladen zu beginnen. Klicken Sie auf das Feld "Jetzt herunterladen", um diese Aufgabe sofort zu starten. Speichern Sie die Aufgabe, um den Download regelmäßig zu der konfigurierten Zeit auszuführen. Die heruntergeladenen Dokumente werden auf Ihrem System entpackt.

### 8.5 Schaltfläche Zurück

Klicken Sie auf die Pfeiltaste, um zur [Startseite](#home-page) zurückzukehren

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 9. **Serverspeicherort**

Klicken Sie im Projektposition-Bereich einer Upload- oder Download-Aufgabe auf "Durchsuchen", um den Verzeichnispfad des Catenda-Projekts zu durchsuchen. Das Dialogfeld "Verzeichnispfad wählen" wird geöffnet. Nach dem Öffnen werden alle Ordnernamen im Projekt und deren Hierarchie heruntergeladen. Für Download-Aufgaben werden auch Dokumentnamen heruntergeladen. Während der Download läuft, kann das Dialogfeld wie folgt aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/09-server-location.png)

Besonders bei Download-Aufgaben kann dieser Prozess mehrere Minuten dauern, wenn es viele Ordner und Dokumente gibt. Bitte stellen Sie sicher, dass für diesen Schritt genügend Speicher auf dem lokalen System verfügbar ist.

**Dialoggröße** Klicken Sie oben rechts auf "Min" oder "Max", um das Dialogfeld "Verzeichnispfad wählen" zu minimieren oder zu maximieren.

**Verzeichnisaktionen** Nach dem Laden der Ordner kann das Dialogfeld etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/10-server-location.png)

Klicken Sie auf den Pfeil neben einem Ordner, um ihn zu erweitern. Dokumente sind nur in dieser Ansicht für Download-Aufgaben verfügbar.

**Ordnerauswahl** Klicken Sie auf einen Ordner, um ihn auszuwählen. Bei Download-Aufgaben können mehrere Ordner ausgewählt werden, während bei Upload-Aufgaben jeweils nur ein Ordner ausgewählt werden kann.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/11-server-location.png)

Nach Auswahl eines Ordners wird dieser mit einem Häkchen weiß angezeigt. Alle Unterordner des ausgewählten Ordners werden durchgestrichen angezeigt, da es nur möglich ist, Ordner auf der gleichen Ebene auszuwählen. Oben wird die Anzahl der ausgewählten Elemente angezeigt.

**Download-Aufgabe** Wenn sich Dokumente im ausgewählten Ordner oder seinen Unterordnern befinden, werden alle Ordner im Pfad zwischen dem ausgewählten Ordner und dem Dokument erstellt. Das Dokument wird dann in diesen Ordner heruntergeladen. Wenn ein Unterordner keine Dokumente enthält, wird der Unterordner nicht erstellt, auch wenn er möglicherweise in diesem Dialogfeld aktiviert ist. Es ist nicht möglich, die Aktivierung eines Unterordners aufzuheben, um nicht einen Teil einer Ordnerstruktur herunterzuladen. Um nur einige Ordner herunterzuladen, wählen Sie sie einzeln wie im Bild unten aus:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/12-server-location.png)

Dokumentauswahl Klicken Sie auf ein Dokument, um es auszuwählen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/13-server-location.png)

Wenn einzelne Dokumente ausgewählt werden, werden die Dokumente als flache Liste direkt zum ausgewählten lokalen Pfad heruntergeladen, ohne die Hierarchie der Ordner, in denen sich diese Dokumente befinden.

**Upload-Aufgabe** Dokumente werden in den ausgewählten Ordner hochgeladen. Wenn der Ordnername übereinstimmt, werden Dokumente in Unterordner des ausgewählten Ordners hochgeladen.

## 10. **Aufgabenliste**

Hier können die Hoch- und Download-Aufgaben angezeigt werden, die in dieser Installation für den angemeldeten Benutzer konfiguriert sind.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/14-task-list.png)

### 10.1 **Name**

Der Name der Aufgabe.

### 10.2 **Aufgabe**

Die geplante Zeit, zu der die Aufgabe ausgeführt wird.

### 10.3 **Projekt**

Der Name des Projekts, in dem diese Aufgabe ausgeführt wird.

### 10.4 **Status**

Der Status dieser Aufgabe.

### 10.5 **Schaltfläche Zurück**

Klicken Sie auf diese Schaltfläche, um zur [Startseite](#home-page) zurückzukehren

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 11. **Protokollordner**

Diese Schaltfläche öffnet den Ordnerspeicherort der Desktop Connector-Protokolle auf dem lokalen System. Der Standardspeicherort dieser Protokolle ist:

`C:\\Users\\\<Windows account name>\\AppData\\Local\\User Name\\2b92d867-496c-47d1-ac42-fbf8fa355177\\Cache\\BimsyncApp`
