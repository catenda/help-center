# Fehlerbehebung beim Zip-Upload

## 1. **Upload fehlgeschlagen**

Es wird empfohlen, eine kabelgebundene Verbindung zum Hochladen der ZIP-Dateien zu Catenda zu verwenden. Viele WLAN-Router machen einen großartigen Job dabei, sicherzustellen, dass sie die richtigen Daten erhalten, aber auch die besten Router können mit einem schwachen Signal kämpfen, wenn Sie weit weg vom Router sind.

### 1.1 **Datei kann nicht verarbeitet werden**

Während des Zip-Upload-Prozesses werden Datenpakete an den Catenda-Server gesendet. Wenn es ein Problem mit einem der Pakete während des Prozesses gibt, wird die folgende Meldung angezeigt: Upload fehlgeschlagen! Datei kann nicht verarbeitet werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/01-unable-to-process-file.png)

Auch wenn Sie direkt neben einer WLAN-Antenne mit einem Gerät sind, ist es nie zu 100 % sicher, dass das Paket sicher durch die Luft ankommt. Dieser Effekt wird verstärkt, wenn Sie weiter weg von der Antenne sind oder wenn es Objekte wie Wände zwischen dem Gerät und der Antenne gibt.

**Große Dateien** Wenn große Datenmengen hochgeladen werden, werden viele Pakete gesendet. Wenn auch nur eines von ihnen nicht ordnungsgemäß durch die Luft zum Router gelangt, kann ein Netzwerkfehler auftreten. In diesem Fall wird der gesamte Upload ungültig.

### 1.2 **Netzwerkfehler**

Bestimmte Software begrenzen die Anzahl der Zeichen, die Pfade zu Dateien in einer Zip-Datei haben können. Wenn es ein Problem mit der Pfadstruktur in der Zip-Datei gibt, wird der folgende Fehler angezeigt: Upload fehlgeschlagen! Netzwerkfehler.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/02-network-error.png)

**Entzippen/Erneut zippen** Wenn diese Zip-Datei von jemand anderem empfangen wurde, kann das Entzippen und erneute Zippen helfen.

**Bekannte Limits (aktualisiert Dezember 2025)** Microsoft Windows 10/11 Das Limit unter Windows beträgt 260 Zeichen, kann aber erhöht werden. _Erforderlicher Zugriff:_ Windows-Administratorkonto

Windows Home-Benutzer: Dieses Limit kann erhöht werden, indem Sie zu Windows Start gehen und REGEDIT eingeben. Öffnen Sie den Registrierungs-Editor und navigieren Sie zu:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem`

Doppelklicken Sie auf `LongPathsEnabled` und ändern Sie den Wert auf 1. Wenn es nicht vorhanden ist, klicken Sie mit der rechten Maustaste auf den Schlüssel `FileSystem` und wählen Sie

`Neu > DWORD (32-Bit) Wert`

Benennen Sie den neuen Wert `LongPathsEnabled` mit einem Wert von 1.

Windows Pro-Benutzer Dieses Limit kann erhöht werden, indem Sie zu Windows Start gehen und gpedit.msc eingeben. Öffnen Sie Richtlinien bearbeiten und navigieren Sie zu:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem`

Doppelklicken Sie auf `Win32-Langpfade aktivieren` und aktivieren Sie es.

OneDrive und SharePoint 400 Unicode-Codeeinheiten

### 1.3 **Robuste Uploads**

**Kleinere Zips** Wenn die Zip-Datei aus mehreren Dateien besteht, kann die Zip-Datei in kleinere Zips aufgeteilt werden. Jede separate Zip-Datei kann einzeln hochgeladen werden, aber es wird immer ein Risiko für einen Netzwerk- oder Verbindungsfehler geben.

**Einzelne Dateien** Der [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) ist eine sicherere Methode zum Hochladen, da er Dokumente Datei für Datei hochlädt. Dies ist auch schneller, da die Dateien direkt zu unserem Backend hochgeladen werden, anstatt über die Browseroberfläche. Selbst wenn eine der Dateien fehlschlägt, werden die bis dahin hochgeladenen bereits in Catenda angezeigt. Die restlichen Dateien werden beim nächsten Ausführen der Upload-Aufgabe weiterhin hochgeladen.

## 2. **Zip-Uploads mit Sonderzeichen**

Catenda erkennt die Codierung der Zip-Datei, wenn sie entpackt wird, sodass Sonderzeichen in der Zip-Datei beim Entpacken ordnungsgemäß interpretiert werden. Wenn die Sonderzeichen nicht richtig codiert wurden, können sie von Catenda nicht entpackt werden und sehen verzerrt aus. Je nach dem verwendeten Service zum Erstellen Ihrer Zip-Datei können Ihre Zeichen richtig codiert sein oder nicht. Wenn Ihre Sonderzeichen verzerrt sind, schauen Sie bitte in der Zip-Datei nach, ob sie dort richtig aussehen. Wenn Sie denken, dass Ihre Zeichen richtig codiert waren und von Catenda nicht richtig extrahiert werden, überprüfen wir gerne Ihre Zip-Datei und sehen, ob wir etwas tun können. Bitte wenden Sie sich in diesem Fall an [support@catenda.com](mailto:support@catenda.com) mit Details darüber, wie Sie Ihre Zip-Datei erstellt haben.

### 2.1 **Zip-Codierung unter Windows**

Verschiedene Windows-Versionen verwenden verschiedene Zip-Codierungen. Beispielsweise verwendet die englische Version den Codierungsstandard IBM-437 und die pt-BR-Version verwendet IBM-850. Wenn Ihre Windows-Installation Ihre Zip-Dateien nicht richtig codiert, haben Sie möglicherweise mehr Erfolg mit einem Drittanbieter-Service wie [7zip](https://7-zip.org/download.html) oder [WinRAR](https://www.win-rar.com/download.html?&L=0), um Ihre Zip-Dateien mit der richtigen Codierung zu erstellen.

## 3. **Abgeschlossen, aber nichts ist passiert**

Obwohl ein Zip-Import abgeschlossen wird, kann es mehrere Gründe geben, warum in der Dokumenttabelle keine Änderung sichtbar ist. So kann es aussehen, wenn ein Zip-Import abgeschlossen ist, ohne dass Änderungen vorgenommen werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/03-completed-but-nothing-happened.png)

So kann das rechte Menü der Zip-Import-Seite in dieser Situation aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/04-completed-but-nothing-happened.png)

### 3.1 **Übersprungene Ordner**

Wenn ein Ordner mit dem gleichen Namen wie ein Ordner in der Zip-Datei bereits an dem Ort vorhanden ist, an dem ein Ordner entpackt werden soll, wird die Erstellung des Ordners übersprungen und es wird kein neuer Ordner erstellt. Alle Dokumente im Ordner mit dem gleichen Namen wie in Catenda werden in den vorhandenen Ordner im Catenda-Projekt hochgeladen.

### 3.2 **Übersprungene Dateien**

Wenn die Option zum Überspringen und Fortfahren im Zip-Upload-Dialog ausgewählt wurde und ein Dokument mit dem gleichen Namen wie die Datei, die aus der Zip-Datei hochgeladen werden soll, bereits vorhanden ist, wird es übersprungen und die nächste Datei wird mit dem Extrahieren beginnen.

### 3.3 **Fehlende Dokumente**

Wenn Dokumente unter fehlenden Dokumenten aufgelistet sind, bedeutet dies, dass die Dokumente erfolgreich erstellt wurden, aber nicht angezeigt werden können. Die Dokumente, in die die Dateien hochgeladen wurden, können inzwischen entfernt worden sein. Es könnte auch sein, dass der Uploader keinen Zugriff mehr auf die Dokumente hat, in die die Dateien hochgeladen wurden. _Erforderlicher Zugriff:_ Lesezugriff

## 4. **Schädliche Dateitypen**

Wenn eine Datei in der Zip-Datei einen potenziell schädlichen Dateityp hat, wird sie nicht hochgeladen. So kann die Zip-Import-Seite aussehen, wenn versucht wird, schädliche Dateitypen hochzuladen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/05-harmful-filetypes.png)

So kann das rechte Menü der Zip-Import-Seite aussehen, wenn versucht wird, eine schädliche Datei hochzuladen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/06-harmful-filetypes.png)

Die folgenden Dateitypen, die möglicherweise schädlich sind, sind nicht zulässig.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa; width: 229px; padding: 8px;"><h1 id="h_711fb2a104"><b>Schädliche Formate</b></h1></td><td style="background-color: #e3e7fa; width: 142px; border-left: 1px solid #c6c9c0; padding: 8px;"><h1 id="h_581e5e19b4">Erweiterungen</h1></td><td style="background-color: #e3e7fa; border-left: 1px solid #c6c9c0; padding: 8px;"><h1 id="h_766841ac5d">Bemerkungen</h1></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Skripte</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>php</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Windows-Dateien</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>exe</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Windows-Installationspakete</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>msi</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Batch-Skripte</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>bat</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Befehlsskripte</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>cmd</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>DOS-Dateien</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>com</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Bildschirmschoner-Dateien</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>scr</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>PowerShell-Skripte</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ps1</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Windows-Verknüpfungen</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>lnk</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Das Klicken auf einen heruntergeladenen Link könnte auf eine ausführbare Datei verlinken, ohne wie eine ausführbare Datei auszusehen.</p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Java-Dateien</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>jar</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr></tbody></table></div>

## 5. **Unzureichender Zugriff**

Der richtige Zugriff ist erforderlich, damit der Zip-Inhalt extrahiert werden kann. _Erforderlicher Zugriff:_ Schreibzugriff

So kann die Zip-Import-Seite aussehen, wenn nicht genug Zugriff vorhanden ist:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/07-insufficient-access.png)

So kann das rechte Menü der Zip-Import-Seite aussehen, wenn nicht genug Zugriff vorhanden ist:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/08-insufficient-access.png)
