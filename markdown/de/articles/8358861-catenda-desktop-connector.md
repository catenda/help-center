# Catenda Desktop Connector

> **Hinweis:** Die Installationsdatei für diese Anwendung finden Sie [hier](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)

Mit dem Catenda Desktop Connector können Sie Up- und Downloads der neuesten Versionen von Dokumenten planen.

## 1. **Sofortiges Up-/Download**

### 1.1 **Hochladen**

Wählen Sie einen Ordner auf einem lokalen System aus, um alle Ordnerinhalte, einschließlich Dateien in Unterordnern des ausgewählten Ordners, mit dem Desktop Connector in einen angegebenen Ordner auf Catenda Hub hochzuladen.

**Erfolgreiche Uploads** Wenn Sie mehrere Dateien per Drag & Drop durchführen oder die Zip-Upload-Funktion auf Catenda Hub verwenden, laden Sie einen großen Datensatz hoch. Je größer der Upload, desto länger müssen Sie warten, bevor Sie Ihre Dateien in die Catenda Hub-Dokumentstruktur einreichen können.

**Eine Datei nach der anderen** Durch das Hochladen von Dateien aus einer Ordnerstruktur Datei für Datei können Sie mit dem Desktop Connector den Upload unterbrechen und später fortsetzen.

**Verringern Sie das Risiko von Upload-Fehlern** Je größer der Upload, desto höher ist das Risiko, dass er fehlschlägt. Möglicherweise fällt Ihr Strom aus, möglicherweise bricht Ihre Internetverbindung für eine Sekunde ab. Dann müssten Sie den Upload ganz von vorne beginnen.

### 1.2 **Herunterladen**

Wählen Sie entweder ein oder mehrere einzelne Dokumente oder einen Ordner auf Catenda Hub aus, um die Auswahl, einschließlich Dokumente in Unterordnern ausgewählter Ordner, an einen Speicherort auf Ihrem lokalen Computer herunterzuladen.

### 1.3 **Übertragungsgeschwindigkeit**

Sowohl das Up- als auch das Herunterladen von Dateien mit dem Desktop Connector ist bei der Dateiübertragung schneller als der reguläre Upload-Prozess, da die Dateien über die API importiert werden, ohne dass der Overhead eines laufenden Browsers oder anderer Browser-Einschränkungen erforderlich ist. Für die Übertragung einer einzelnen Datei wird Drag & Drop mit einem Browser empfohlen, da es einfach zu bedienen ist. Für die Übertragung großer Datenmengen auf einmal oder für diejenigen, die beim Upload großer einzelner Dateien Zeit sparen möchten, ist der Desktop Connector die empfohlene Methode zum Übertragen.

### 1.4 **Zugriff**

Die auf Catenda Hub konfigurierte Zugriffskontrolle bleibt erhalten. Benutzer können an Speicherorte in der Catenda-Dokumentstruktur hochladen, auf die sie mindestens Schreibzugriff haben, und können nur Dokumente herunterladen, auf die sie mindestens Lesezugriff haben.

## 2. **Synchronisierung**

Dateien können zeitlich gestaffelt up- oder heruntergeladen werden.

### 2.1 **Lokales System -> Catenda Hub**

Der Desktop Connector kann sicherstellen, dass Dateien in einem Catenda Hub-Projekt mit dem neuesten Speicherzustand einer Datei auf dem lokalen System aktuell bleiben.

### 2.2 **Catenda Hub -> Lokales System**

Der Desktop Connector kann sicherstellen, dass Dateien auf einem lokalen System mit der neuesten Revision eines Dokuments in einem Catenda Hub-Projekt aktuell bleiben.

## 3. **Installation**

Wenn der Catenda Desktop Connector unter Windows installiert wird, werden seine Installationsdateien im folgenden Ordner angezeigt.

`C:\Program Files\Catenda Hub Desktop Connector`

### 3.1 **Deinstallation**

Zum Deinstallieren des Plug-ins gehen Sie zu folgendem Windows-Menü:

`Windows-Einstellungen -> Apps -> Installierte Apps`

Suchen Sie den Desktop Connector in der Liste und klicken Sie auf das Aktionsmenü auf der rechten Seite, um ihn zu deinstallieren.

## 4. **Anmelden**

Wenn der Desktop Connector zum ersten Mal geöffnet wird, wird eine Anmeldeanfrage angezeigt. Klicken Sie auf die Schaltfläche "Anmelden", um den Standardbrowser des Systems auf der Catenda-Anmeldeseite zu öffnen. Melden Sie sich an oder klicken Sie, falls Sie bereits angemeldet sind, auf "Zugriff zulassen", um Zugriff auf das angemeldete Catenda-Konto zu gewähren. Nach dem Klicken auf "Zugriff zulassen" werden Sie vom Browser aufgefordert, die Desktop Connector-Anwendung zu öffnen. Wenn Sie dem Öffnen der Anwendung zustimmen, werden Sie zur [Startseite](#h_097078145d) des Desktop Connectors weitergeleitet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/01-sign-in.png)

## 5. **Startseite**

So kann der Desktop Connector aussehen, wenn er mit gültiger Anmeldung gestartet wird:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/02-home-page.png)

### 5.1 **PC aufwecken**

Wecken Sie den PC aus dem Ruhezustand auf, wenn eine Aufgabe zu diesem Zeitpunkt ausgeführt werden soll.

### 5.2 **Beim Start ausführen**

Wählen Sie diese Option, um den Desktop Connector beim Start auszuführen

### 5.3 **Abmelden**

Klicken Sie auf die Schaltfläche "Abmelden" unten rechts, um sich abzumelden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/03-log-out.png)

## 6. **Projektliste**

Es wird eine Übersicht der Projekte angezeigt, auf die das Konto beim letzten Laden der Projektliste Zugriff hatte. Für jedes Projekt wird die Anzahl der konfigurierten Up- und Download-Aufgaben angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/04-project-list.png)

### 6.1 **Schaltfläche "Synchronisieren"**

Wenn Sie kürzlich einem Projekt beigetreten sind, klicken Sie auf diese Synchronisierungsschaltfläche, um die neue Liste der Projekte zu laden, in denen das angemeldete Konto Mitglied ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/05-synchronize-button.png)

### 6.2 **Name**

Klicken Sie auf den Namen eines Projekts, um die aktuellen Up- und Download-Aufgaben anzuzeigen oder eine neue Aufgabe zu planen.

### 6.3 **Upload-Aufgaben**

Die Anzahl der Upload-Aufgaben, die für dieses Projekt aktiv sind

### 6.4 **Download-Aufgaben**

Die Anzahl der Download-Aufgaben, die für dieses Projekt aktiv sind

## 7. **Upload-Aufgabe**

Planen Sie einen periodischen Upload von Dateien von Ihrem System zu Catenda Hub mit dieser Aufgabe.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/06-upload-task.png)

### 7.1 **Titel - Erforderlich**

Die Upload-Aufgabe muss mindestens einen Titel haben, um gespeichert zu werden

### 7.2 **Kalender planen - Erforderlich**

Die Aufgabe muss mindestens einen Tag ausgewählt haben, um gespeichert zu werden

### 7.3 **Projektstandort**

**Server** Klicken Sie auf "Durchsuchen", um das Ziel auf der Seite "Dokumente" in Catenda Hub auszuwählen, wo Dateien synchronisiert werden sollen. Klicken Sie [hier](#h_4446f1b663), um mehr über die Auswahl des Serververzeichnispfads zu erfahren

**Lokal** Wählen Sie den Speicherort auf dem lokalen System aus, von dem Dateien synchronisiert werden sollen.

### 7.4 **Sofort**

Aufgaben müssen nicht gespeichert werden, um den Upload-Prozess zu starten. Klicken Sie auf das Feld "Jetzt hochladen", um diese Aufgabe sofort zu starten. Gespeicherte Aufgaben werden regelmäßig zur konfigurierten Zeit ausgeführt.

## 8. **Download-Aufgabe**

Planen Sie einen periodischen Download von Dateien von Catenda Hub auf das lokale System.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/07-download-task.png)

### 8.1 **Titel - Erforderlich**

Die Upload-Aufgabe muss mindestens einen Titel haben, um gespeichert zu werden

### 8.2 **Kalender planen - Erforderlich**

Die Aufgabe muss mindestens einen Tag ausgewählt haben, um gespeichert zu werden

### 8.3 **Projektstandort**

**Server** Wählen Sie den Speicherort auf Catenda Hub aus, von dem Dokumente heruntergeladen werden sollen. Klicken Sie [hier](#h_4446f1b663), um mehr über die Auswahl des Serververzeichnispfads zu erfahren

**Lokal** Wählen Sie das Ziel auf dem lokalen System aus, auf das Dateien heruntergeladen werden sollen.

### 8.4 **Sofort**

Eine Aufgabe muss nicht gespeichert werden, um mit dem Herunterladen zu beginnen. Klicken Sie auf das Feld "Jetzt herunterladen", um diese Aufgabe sofort zu starten. Speichern Sie die Aufgabe, um den Download regelmäßig zur konfigurierten Zeit durchzuführen. Die heruntergeladenen Dokumente werden auf Ihrem System entpackt.

### 8.5 Zurück-Schaltfläche

Klicken Sie auf die Pfeiltaste, um zur [Startseite](#h_097078145d) zurückzukehren

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 9. **Serverspeicherort**

Klicken Sie im Bereich "Projektstandort" einer Upload- oder Download-Aufgabe auf "Durchsuchen", um mit dem Durchsuchen des Verzeichnispfads des Catenda-Projekts zu beginnen. Das Dialogfeld "Verzeichnispfad auswählen" wird geöffnet. Nach dem Öffnen werden alle Ordnernamen im Projekt und ihre Hierarchie heruntergeladen. Bei Download-Aufgaben werden auch Dokumentnamen heruntergeladen. Während des Herunterladens kann das Dialogfeld so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/09-server-location.png)

Besonders bei Download-Aufgaben, wenn viele Ordner und Dokumente vorhanden sind, kann dieser Vorgang einige Minuten dauern. Stellen Sie bitte sicher, dass auf dem lokalen System genügend Speicher für diesen Schritt verfügbar ist.

**Dialoggröße** Klicken Sie oben rechts auf "Min" oder "Max", um das Dialogfeld "Verzeichnispfad auswählen" zu minimieren oder zu maximieren.

**Verzeichnisaktionen** Nach dem Laden der Ordner kann das Dialogfeld etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/10-server-location.png)

Klicken Sie auf den Pfeil neben einem Ordner, um ihn zu erweitern. Dokumente sind in dieser Ansicht nur für Download-Aufgaben verfügbar.

**Ordner auswählen** Klicken Sie auf einen Ordner, um ihn auszuwählen. Bei Download-Aufgaben können mehrere Ordner ausgewählt werden, während bei Upload-Aufgaben jeweils nur ein Ordner ausgewählt werden kann.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/11-server-location.png)

Nach der Auswahl eines Ordners wird dieser mit einem Häkchen weiß angezeigt. Alle Unterordner des ausgewählten Ordners werden durchgestrichen, da nur Ordner auf derselben Ebene ausgewählt werden können. Oben wird die Anzahl der ausgewählten Elemente angezeigt.

**Download-Aufgabe** Wenn sich Dokumente im ausgewählten Ordner oder seinen Unterordnern befinden, werden alle Ordner im Pfad zwischen dem ausgewählten Ordner und dem Dokument erstellt. Das Dokument wird dann in diesen Ordner heruntergeladen. Wenn ein Unterordner keine Dokumente enthält, wird der Unterordner nicht erstellt, auch wenn er in diesem Dialogfeld aktiviert sein kann. Es ist nicht möglich, die Auswahl eines Unterordners aufzuheben, um nicht einen Teil einer Ordnerstruktur herunterzuladen. Wählen Sie einzelne Ordner aus, wie im Bild unten, um nur einige Ordner herunterzuladen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/12-server-location.png)

Dokument auswählen Klicken Sie auf ein Dokument, um es auszuwählen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/13-server-location.png)

Wenn einzelne Dokumente ausgewählt werden, werden die Dokumente als flache Liste direkt zum ausgewählten lokalen Pfad heruntergeladen, ohne die Hierarchie der Ordner, in denen sich diese Dokumente befinden.

**Upload-Aufgabe** Dokumente werden in den ausgewählten Ordner hochgeladen. Wenn der Ordnername übereinstimmt, werden Dokumente in Unterordner des ausgewählten Ordners hochgeladen.

## 10. **Aufgabenliste**

Hier können die Up- und Download-Aufgaben angezeigt werden, die in dieser Installation für den angemeldeten Benutzer konfiguriert sind.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/14-task-list.png)

### 10.1 **Name**

Der Name der Aufgabe.

### 10.2 **Aufgabe**

Die geplante Zeit für die Ausführung der Aufgabe.

### 10.3 **Projekt**

Der Name des Projekts, in dem diese Aufgabe ausgeführt wird.

### 10.4 **Status**

Der Status dieser Aufgabe.

### 10.5 **Zurück-Schaltfläche**

Klicken Sie auf diese Schaltfläche, um zur [Startseite](#h_097078145d) zurückzukehren

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 11. **Protokollordner**

Diese Schaltfläche öffnet den Ordnerspeicherort der Desktop Connector-Protokolle auf dem lokalen System. Der Standardspeicherort dieser Protokolle ist:

`C:\Users\<Windows account name>\AppData\Local\User Name\2b92d867-496c-47d1-ac42-fbf8fa355177\Cache\BimsyncApp`
