# Fehlerbehebung für Desktop Connector

## 1. **Benennungskonvention**

Wenn eine Benennungskonvention für den Upload-Ordner oder einen übergeordneten Ordner des Upload-Ordners aktiviert ist, muss der lokale Dateiname der Konvention entsprechen, damit der Upload durchgeführt werden kann. Wenn der Dateiname der Konvention nicht entspricht, wird die folgende Fehlermeldung angezeigt.

**`<Dateiname> stimmt nicht mit Benennungskonvention überein`**

Bitte laden Sie die Datei manuell über den Browser hoch, um zu sehen, welche Teile des Dateinamens fehlen.

## 2. **Serverproektstandort**

Beim Öffnen des Serverproektstandorts können mehrere Fehler auftreten.

### 2.1 **Proektstandort leer**

Um Ihre lokalen Dateien mit einem Projekt zu synchronisieren, benötigen Sie mindestens einen Ordner im Dokumentbereich des Projekts in Catenda Hub.

### 2.2 **Projekt nicht gefunden**

Wenn der Desktop Connector zum ersten Mal geöffnet wird, werden alle Projekte, auf die der Benutzer Zugriff hat, geladen. Ohne Aktualisierung werden dieselben Projekte beim nächsten Mal angezeigt. Wenn der Benutzer den Zugriff auf das Projekt verloren hat, wird die folgende Meldung angezeigt, wenn versucht wird, einen Serverstandort für eine Hoch- oder Herunterladetask für das Projekt festzulegen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/01-project-not-found.png)

Bitte wenden Sie sich an einen Projektadministrator, um Zugriff auf das Projekt zu erhalten. Um herauszufinden, wen Sie für den Proektzugriff kontaktieren können, wenden Sie sich bitte an Catenda Support.

## 3. **Dokumentanzeige**

### 3.1 **Ordnerstandort**

Dokumentnamen können durch eine Benennungskonvention in Catenda begrenzt werden. Ordner können nicht begrenzt werden. Ohne Verwendung einer Benennungskonvention können Dokumente mit beliebigen Namen hochgeladen werden. In diesem Fall war Catenda möglicherweise nicht in der Lage, die Dateierweiterung des Dokuments zu registrieren. Ordner mit beliebigen Namen können erstellt werden. Es kann daher vorkommen, dass der Desktop Connector auf Probleme mit Zeichen in Namen stößt, die für die Windows-Funktionalität reserviert sind.

Typische Probleme treten bei den folgenden Zeichen auf: `/` - Schrägstrich `\` - Rückwärtsschrägstrich Diese Zeichen werden in der Dateipfad-Hierarchie in Windows verwendet, wodurch das Dokument am falschen Ort landet.

Eine umfangreiche Liste der in Windows reservierten Elemente finden Sie hier: [https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file](https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file)

### 3.2 **Falscher Dokument- oder Ordnername**

Dokumentnamen können durch eine Benennungskonvention in Catenda begrenzt werden. Ordner können nicht begrenzt werden. Ohne Verwendung einer Benennungskonvention können Dokumente mit beliebigen Namen hochgeladen werden. In diesem Fall war Catenda möglicherweise nicht in der Lage, die Dateierweiterung des Dokuments zu registrieren. Ordner mit beliebigen Namen können erstellt werden.

Es kann daher vorkommen, dass der Desktop Connector auf Probleme mit Zeichen in Namen stößt, die für die Windows-Funktionalität reserviert sind.

Typische Probleme treten bei den folgenden Zeichen auf: `.` - Punkt

Da Ordner und Dateien, die mit einem Punkt enden, in Windows nicht zulässig sind, wird der Punkt am Ende des Ordners oder der Datei in dem Dokument entfernt, das aus einer Herunterladetask erstellt wird. Beim Hochladen wird der Punkt beim Suchen nach dem richtigen Ordner zum Hochladen entfernt, damit das heruntergeladene Dokument beim bidirektionalen Synchronisieren am richtigen Ort landet.

- Leerzeichen

In Catenda ist es möglich, manuell ein Leerzeichen am Ende eines Dokument- oder Ordnernamens hinzuzufügen, während Leerzeichen am Ende von Dokument- und Ordnernamen in Windows entfernt werden. Wenn in Catenda ein Leerzeichen enthalten ist, unterscheidet sich der Name des heruntergeladenen Ordners vom Namen des Ordners in Catenda, der ein Leerzeichen enthalten kann. Wenn eine Upload-Task für denselben Ordner erstellt wird, wird ein neuer Ordner erstellt, da der Datei- oder Ordnername in Windows kein Leerzeichen am Ende hat.

## 4. **Kein Hoch- oder Herunterladen**

### 4.1 **Dokument existiert bereits**

Wenn das Importsystem ein zuvor erstelltes Element nicht verarbeiten kann, tritt der folgende Fehler auf.

Desktop-Connector `Dokument existiert bereits (Code: 25)`

Protokolldatei

```
<Nachrichtennummer>|<Datum/Uhrzeit>|ERROR|1|BimRequestProviderService|API-Fehler Status Code Konflikt Grund: {"error":{"code":25,"message":"Dokument existiert bereits"}}.url: https://api.bimsync.com/v2/projects/<ProjectGUID>/libraries/<LibraryGUID>/items? | Daten: {"parentId":"<LibraryItemGUID>","name":"<Name>","document":{"type":"<Type>","filename":"<Filename>"}} 
```

Speziell kann dies passieren, wenn versucht wird, einen Ordner mit dem Titel "`A`" ein zweites Mal hochzuladen, wenn bereits ein Ordner mit diesem Titel existiert. Es wird empfohlen, jeden lokalen Ordner mit dem Namen "A" in etwas wie "A\_" zu ändern. Auf diese Weise wird die Task nicht auf Probleme stoßen. Nachdem die Upload-Task abgeschlossen ist, ändern Sie die synchronisierte Version in Catenda zurück zu "A", damit beide Seiten gleich bleiben.

### 4.2 **Nicht alle Ordner wurden heruntergeladen**

In der Task selbst kann Folgendes angezeigt werden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/02-not-all-folders-have-been-downloaded.png)

`Nicht alle Ordner wurden heruntergeladen, klicken Sie hier, um Fehler anzuzeigen.`

Klicken Sie [hier](https://support.catenda.com/en/articles/13772277-desktop-connector-troubleshooting-not-all-folders-have-been-downloaded), um mehr über mögliche Probleme mit diesem Fehler zu erfahren.

## 5. **Neueste Revision zurückgezogen**

Die neueste Version eines der Dokumente wurde zurückgezogen. In diesem Fall gibt es keine Fehlermeldung in der Protokolldatei.

## 6. **Gleichzeitige Synchronisierung**

Damit der Desktop Connector Daten aus einem Dokument extrahieren oder ein Dokument mit heruntergeladenen Daten aktualisieren kann, benötigt er Zugriff auf das Dokument. Wenn das Dokument von einem anderen Prozess verwendet wird, kann darauf nicht zugegriffen werden. Wenn das Dokument verwendet wird, kann der folgende Fehler angezeigt werden:

Desktop-Connector `Der Prozess kann nicht auf die Datei '<Dateipfad>' zugreifen, da sie von einem anderen Prozess verwendet wird.`

Protokolldatei

```
<Nachrichtennummer>|<Datum/Uhrzeit>|ERROR|1|ExceptionHandleExtension|Ein Fehler ist aufgetreten --> System.IO.IOException: Der Prozess kann nicht auf die Datei '<Dateipfad>' zugreifen, da sie von einem anderen Prozess verwendet wird.
```

Prozesse, die Dateien verwenden können, sind: Eine andere Task des Desktop Connector selbst Dateisynchronisierungsdienste wie Dropbox, OneDrive oder Google Drive Andere CDE-Synchronisierungstools. Programme, die die Datei zum Bearbeiten offen haben.

Wenn das Dokument verwendet wird, wird die Task gestoppt und nicht fortgesetzt, wenn auf eine der Dateien nicht zugegriffen werden kann. Wenn mehrere Tasks geplant wurden, wird die Task zur nächsten geplanten Zeit erneut versucht.

## 7. **Aktivitätsüberwachung**

### 7.1 **Task gestartet**

Tasks, die manuell durch Klicken auf "Jetzt hochladen/herunterladen" in der Task gestartet wurden, zeigen sofort nach dem Start der Task den Status "Hochladen" oder "Herunterladen" an. Für Tasks, die manuell gestartet wurden, sowie für Tasks, die per Zeitplan gestartet wurden, wird eine Meldung wie folgt in der Protokolldatei angezeigt, wenn eine Task gestartet wird:

Protokolldatei `<Nachrichtennummer>|<Datum/Uhrzeit>|INFO|1|LoggingExtension|Protokollierung beginnen`

### 7.2 **Task läuft**

Tasks, die manuell durch Klicken auf "Jetzt hochladen/herunterladen" in der Task gestartet wurden, zeigen den Status "Hochladen" oder "Herunterladen" an, solange die Task noch läuft. Für Tasks, die manuell gestartet wurden, sowie für Tasks, die per Zeitplan gestartet wurden, kann der Status laufender Tasks durch Überwachung der Netzwerknutzung der Anwendung angezeigt werden.

**Anfängliche Startphase** Eine Desktop Connector Task befindet sich in ihrer anfänglichen Startphase, wenn sie zwischen 1 Kilobyte pro Sekunde und 1 Megabyte pro Sekunde verwendet wird. Während dieser Phase ist die Netzwerknutzung der Task minimal.

Herunterlade-Task Während der anfänglichen Startphase werden Dokumente am Serverstandort mit lokalen Dateien abgeglichen, um zu prüfen, ob es Serverdateien gibt, die sich geändert haben und für die eine neue Version heruntergeladen werden sollte, oder ob es neue Dateien auf der Serverseite gibt, die in das lokale System heruntergeladen werden sollten.

Upload-Task Während der anfänglichen Startphase werden Dokumente am Serverstandort mit lokalen Dateien abgeglichen, um zu prüfen, ob es lokale Dateien gibt, die sich geändert haben und für die eine neue Version hochgeladen werden sollte, oder ob es neue lokale Dateien gibt, die in Catenda hochgeladen werden sollten.

**Aktive Phase** Eine Desktop Connector Task befindet sich in ihrer aktiven Phase, wenn sie mehr als 1 Megabyte pro Sekunde verwendet. Während dieser Phase kann die Netzwerknutzung der Task Auswirkungen auf den Rest des Systems haben.

Herunterlade-Task Während der aktiven Phase lädt der Desktop Connector aktiv Datei für Datei von Catenda in das lokale System herunter.

Upload-Task Während der aktiven Phase lädt der Desktop Connector aktiv Datei für Datei vom lokalen System in Catenda hoch.

### 7.3 **Task gestoppt**

Tasks, die manuell durch Klicken auf "Jetzt hochladen/herunterladen" in der Task ausgeführt werden, zeigen eine Statusmeldung in der Task an, wenn die Task gestoppt wird, entweder wenn die Task beendet ist oder wenn ein Fehler aufgetreten ist.

**Task beendet** Die einzige Möglichkeit zu sehen, ob Tasks erfolgreich beendet wurden, ist die manuelle Ausführung der Task. Klicken Sie auf "Jetzt hochladen/herunterladen" in der Task. Wenn die Task erfolgreich beendet wurde, wird eine Meldung angezeigt, dass alle Dokumente hochgeladen oder heruntergeladen wurden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/03-task-halted.png)

> **Hinweis:** Es gibt keine Meldungen in der Protokolldatei für beendete Tasks. Die einzige Möglichkeit zu sehen, ob Tasks, die per Zeitplan gestartet wurden, gestoppt wurden, besteht darin, die Netzwerknutzung der Anwendung zu prüfen.

**Ein Fehler ist aufgetreten** Eine detailliertere Beschreibung der aufgetretenen Fehler finden Sie in der Protokolldatei mit letzten Fehlern.

**Netzwerknutzung** Die einzige Möglichkeit zu sehen, ob Tasks, die per Zeitplan gestartet wurden, gestoppt wurden, besteht darin, die Netzwerknutzung der Anwendung zu prüfen. Wenn der Desktop Connector weniger als 1 Kilobyte pro Sekunde für mehr als 2 Minuten verwendet hat, wurden alle laufenden Tasks wahrscheinlich gestoppt und starten nicht wieder. Für Tasks, die wiederkehrend geplant sind, wird eine neue Task gestartet, wenn der Desktop Connector am nächsten Termin und zur nächsten Uhrzeit ausgeführt wird, zu der die Task geplant ist.

## 8. **Verbindung zwischen dem Connector und Catenda**

### 8.1 **Verbindung beim Starten einer Task**

Wenn ein Problem mit der Internetverbindung besteht, wird die Upload- oder Herunterlade-Task nicht automatisch neu gestartet und wird zum nächsten geplanten Zeitpunkt erneut ausgeführt. Sie können auch manuell gestartet werden, indem Sie zur Task gehen und auf die Schaltfläche "Hochladen" oder "Herunterladen" klicken.

**Keine Verbindung** Wenn beim Starten einer Upload- oder Herunterlade-Task keine Internetverbindung verfügbar ist, wird der folgende Fehler in der Upload- oder Herunterlade-Task angezeigt.

`Solcher Host ist nicht bekannt`

**Verbindung beim Starten der Task unterbrochen** Wenn die Internetverbindung unterbrochen wurde oder beim Verbindungsversuch mit den Catenda-Servern abgelaufen ist, wird der folgende Fehler angezeigt:

`Die SSL-Verbindung konnte nicht hergestellt werden`

**Verwendete Verbindungsmethode hängt von der verfügbaren Vorzugsmethode bei Task-Start ab** Wenn eine Task gestartet wird, wird eine Verbindung mit der bevorzugten Internetverbindungsmethode hergestellt. Wenn beispielsweise beim Start einer Task eine kabelgebundene Verbindung und eine WiFi-Verbindung verfügbar sind, wird die kabelgebundene Verbindung oft bevorzugt. Wenn beim Start einer Task nur eine WiFi-Verbindung verfügbar ist und während der Ausführung eine kabelgebundene Verbindung hergestellt wird, nutzt der Connector weiterhin die anfängliche Verbindung, solange sie verfügbar ist, und schaltet nicht auf eine bevorzugte Verbindung um, die später verfügbar wird.

### 8.2 **Verbindung während Task - Verbindung mit dem Internet**

**Internetverbindung nicht mehr verfügbar ohne Fallback** Wenn beim Start der Task nur eine Verbindung verfügbar war oder überhaupt keine Verbindung verfügbar war (z. B. Flugmodus), kann der folgende Fehler auftreten.

`Beim Senden der Anforderung ist ein Fehler aufgetreten.`

**Internetverbindung nicht mehr verfügbar mit Fallback** Wenn beim Start der Task mehrere Verbindungen verfügbar waren und die verwendete Verbindung verloren geht, versucht der Connector, zu einer der anderen verfügbaren Verbindungen zu wechseln. Während dieses Wechsels kann der folgende Fehler auftreten:

`Fehler beim Kopieren von Inhalten in einen Stream`

### 8.3 **Verbindung während Task - Desktop Connector Session-Timeout**

Der Catenda Desktop Connector hat ein fest eingestelltes Sitzungslimit von 10 Minuten. Dies bedeutet nicht, dass eine Task nach 10 Minuten abläuft, da der Desktop Connector oft mit mehreren kurzen Sitzungen gleichzeitig arbeitet. Große Dateien wie Point Clouds mit bis zu 25 GB können dazu führen, dass eine Sitzung länger als normal dauert und abläuft, wenn sie nicht innerhalb des 10-Minuten-Limits hochgeladen wird.

`Timeout von 600 Sekunden verstreicht`

Bitte kontaktieren Sie in dieser Situation den Support. Es ist eine Beta-Version auf Anfrage verfügbar, die dabei helfen kann. Mit der Beta-Version ist dieses Limit leicht erhöht, aber auch mit der Beta-Version kann es abgelaufen sein, aber stattdessen nach 15 Minuten.

`Timeout von 900 Sekunden verstreicht`

### 8.4 **Verbindung während Task - Verbindung mit Catenda**

Je nach Geschwindigkeit der Verbindung auf der Hoch-/Herunterlade-Seite oder auf der Catenda-Seite kann das Hochladen von Dateien kürzer oder länger dauern. Wenn die Task zu lange dauert, kann die Verbindung abgelaufen sein.

**Catenda Timeout** Wenn die Übertragung zu lange gedauert hat, läuft sie ab und der folgende Fehler wird angezeigt:

`Ein Verbindungsversuch ist fehlgeschlagen, da die verbundene Partei nicht ordnungsgemäß geantwortet hat oder die hergestellte Verbindung fehlgeschlagen ist, da der verbundene Host nicht antwortet. (api.bimsync.com:443)`

Bitte kontaktieren Sie in dieser Situation den Support. Es ist eine Beta-Version auf Anfrage verfügbar, die dabei helfen kann.

**Catenda Service nicht verfügbar** Wenn die Catenda API in der Sekunde, in der der Desktop Connector versucht, darauf zuzugreifen, vorübergehend keine Anforderungen empfangen kann, wird die folgende Meldung angezeigt.

Desktop-Connector `HTTP ERROR 503 Service Unavailable`

Protokolldatei

```
<Nachrichtennummer>|<Datum/Uhrzeit>|ERROR|1|BimRequestProviderService|API-Fehler Status Code ServiceUnavailable Grund: <html><head><meta http-equiv="Content-Type" content="text/html;charset=ISO-8859-1"/><title>Error 503 Service Unavailable</title></head><body><h2>HTTP ERROR 503 Service Unavailable</h2><table><tr><th>URI:</th><td>/v2/projects/10005fce182e49cb91342571746cf1fc/libraries/9a90887d954a444c8ed45695707b2fbd/items</td></tr><tr><th>STATUS:</th><td>503</td></tr><tr><th>MESSAGE:</th><td>Service Unavailable</td></tr><tr><th>SERVLET:</th><td>-</td></tr></table>
```

Dies ist oft darauf zurückzuführen, dass Server überlastet sind und viele Benutzer versuchen, gleichzeitig Anforderungen zu senden.

**Gateway-Timeout** Ein Gateway-Timeout bedeutet oft, dass die Catenda API reibungslos läuft und die ursprüngliche Anforderung ordnungsgemäß empfangen wurde. Der Dienst, der diese Anforderung verarbeiten sollte, hat jedoch nicht rechtzeitig geantwortet.

Desktop-Connector `504 Gateway Time-Out` Protokolldatei

```
<Nachrichtennummer>|<Datum/Uhrzeit>|ERROR|1|BimRequestProviderService|API-Fehler Status Code GatewayTimeout Grund: <html><head><title>504 Gateway Time-out</title></head><body><center><h1>504 Gateway Time-out</h1></center></body></html>
```

Dies kann darauf hindeuten, dass Catenda Anforderungen ordnungsgemäß empfängt, der Server, der die Anforderungen verarbeitet, jedoch vorübergehend nicht verfügbar ist. Dies kann manchmal vorkommen, wenn nicht genügend Maschinen verfügbar sind, danach werden automatisch mehr gestartet, dies kann jedoch einige Zeit dauern.

**Access Token abgelaufen** Catenda-Zugriffstokens müssen nach einer Stunde aktualisiert werden. Wenn der Desktop Connector navigiert wird, ist dies normalerweise kein Problem, da das Token automatisch aktualisiert wird. Wenn jedoch eine Task gestartet wird, die länger als eine Stunde dauert, kann das Zugriffstoken, das für die Task verwendet wurde, abgelaufen sein, während die Task noch läuft. In diesem Fall wird der folgende Fehler im Desktop Connector angezeigt. Für Tasks, die länger als eine Stunde dauern, starten Sie die Task neu oder warten Sie auf die nächste geplante Task, um die restliche Arbeit auszuführen.

Desktop-Connector `Exception des Typs 'BimsyncApp.Exceptions.BimAuthenticatorException' wurde ausgelöst.`

Protokolldatei

```
<Nachrichtennummer>|<Datum/Uhrzeit>|ERROR|1|BimRequestProviderService|API-Fehler Status Code Unauthorized Grund: {"error":{"code":12,"message":"Access Token ist abgelaufen"}}.url: 
```

## 9. **Dieses Gerät wird derzeit verwendet**

Beim Herunterladen oder Hochladen auf eine externe Festplatte zeigt Windows einen Fehler an, dass das Gerät derzeit verwendet wird, wenn versucht wird, es zu trennen.

## 10. **Ordnerberechtigungen**

Für Ordner auf dem Laufwerk, auf dem Windows installiert ist, sind die richtigen Ordnerberechtigungen erforderlich. Klicken Sie mit der rechten Maustaste auf den Ordner, in den Sie herunterladen möchten, und aktivieren Sie die richtigen Berechtigungen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/04-folder-permissions.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/05-folder-permissions.png)

In diesem Fall wird die Protokolldatei den folgenden Fehler ausgeben:

`Zugriff auf den Pfad '<Ausgewählter lokaler Ordnerpfad> Unterordner <Pfad im lokalen Ordner>' verweigert`

### 10.1 **Berechtigung verweigert**

Obwohl ein Ordner in Windows geöffnet werden kann, kann Windows eine "No-Write-Up" Richtlinie durchsetzen. Der Desktop Connector lässt Sie diesen Ordner auswählen, aber wenn die Task ausgeführt wird, wird die folgende Meldung angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/06-permission-denied.png)

In diesem Fall wird der Desktop Connector beim Schreiben blockiert, unabhängig von den "Vollständig steuern" Rechten des Benutzers.

Das Löschen dieses Ordners erfordert, dass der Benutzer Administratorrechte gewährt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/07-permission-denied.png)

In manchen Situationen kann der Ordner noch geöffnet werden, in anderen ist die folgende Meldung sichtbar:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/08-permission-denied.png)

Auch wenn Sie fortfahren, kann die folgende Meldung angezeigt werden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/09-permission-denied.png)

Das Klicken auf "Trotzdem herunterladen" lädt die Dateien herunter, aber sie können nicht in den angegebenen Ordner heruntergeladen werden, da dieser Ordner beschränkt ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/10-permission-denied.png)

Desktop-Connector `Status: Umleitung, klicken Sie hier, um heruntergeladene Dateien anzuzeigen`

Protokolldatei `Zugriff auf den Pfad '<Pfad>' verweigert`

Klicken Sie auf "Heruntergeladene Dateien anzeigen", um den Speicherort der heruntergeladenen Dateien zu öffnen.
