# Desktop Connector Fehlerbehebung – Nicht alle Ordner wurden heruntergeladen

In diesem Artikel finden Sie Informationen zu einem bestimmten Fehler, der bei der Verwendung des [Catenda Desktop Connectors](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) auftreten kann. Weitere Probleme bei der Fehlerbehebung des Desktop Connectors finden Sie [hier](https://app.intercom.com/a/apps/areracg3/knowledge-hub/all-content?activeContentId=11844906&activeContentType=article&editorMode=view&native_content=false).

In der Aufgabe selbst kann Folgendes angezeigt werden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/01-intro.png)

`Nicht alle Ordner wurden heruntergeladen. Klicken Sie, um Fehler anzuzeigen.`

## 1. **Nicht unterstützte Zeichen**

In diesem Fall wird die Protokolldatei den folgenden Fehler anzeigen:

`Die Datei-, Verzeichnis- oder Volumebezeichnung ist ungültig.`

Dokumentnamen können in Catenda durch eine Namenskonvention begrenzt werden. Ordner können nicht begrenzt werden. Ohne eine Namenskonvention können Dokumente mit jedem beliebigen Namen hochgeladen werden. In diesem Fall konnte die Dateierweiterung des Dokuments möglicherweise nicht registriert werden. Ordner können mit jedem beliebigen Namen erstellt werden. Es kann daher sein, dass der Desktop Connector versucht, eine Datei oder einen Ordner mit einem Zeichen zu erstellen, das in einem Windows-Pfad nicht verwendet werden darf.

Typische Probleme treten mit den folgenden Zeichen auf: `<` - Kleiner-als-Zeichen `>` - Größer-als-Zeichen `:` - Doppelpunkt `"` - Anführungszeichen `|` - senkrechter Strich oder Pipe `?` - Fragezeichen `*` - Sternchen

Eine umfangreiche Liste der in Windows reservierten Zeichen finden Sie hier: [https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file](https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file)

## 2. **Fehlender Ordner oder Netzwerkpfad**

In diesem Fall wird die Protokolldatei den folgenden Fehler anzeigen:

`Fehler: Der Netzwerkpfad wurde nicht gefunden. : '<path>'`

In dieser Situation schlägt die Übertragung sofort fehl. Dies geschieht, weil das Programm versucht, auf einen Ordner zuzugreifen, der nicht mehr zugänglich ist. Weil der "Pfad" vollständig unterbrochen ist, kann das Programm nicht einmal mit dem Download beginnen. Es gibt drei Hauptgründe, warum Ihr Ordner zu einer "Sackgasse" geworden ist:

### 2.1 **1. Der fehlende Ordner (am häufigsten)**

Der zuvor ausgewählte lokale Ordner wurde verschoben, umbenannt oder gelöscht. Wenn Sie in Datei-Explorer zum Speicherort des Ordners gehen, ist der Ordner nicht vorhanden. Der Desktop Connector versucht, die Datei zu speichern, findet "nichts" und wird beendet.

### 2.2 **2. Der unterbrochene "symbolische Link" (Die verborgene Umleitung)**

Ein symbolischer Link sieht wie ein normaler Ordner aus, fungiert aber als permanenter "Wegweiser", der Windows an einen anderen Speicherort weiterleitet (wie einen Büroserver). Beim Versuch, ihn zu öffnen, wird der folgende Fehler in einem Popup angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/02-2-the-broken-symbolic-link-the-hidden-redirect.png)

`Speicherort ist nicht verfügbar... Der Netzwerkpfad wurde nicht gefunden.`

**Wie man sie unterscheidet:** Wie .lnk-Dateien haben symbolische Links einen kleinen blauen "Shortcut-Pfeil" in der unteren linken Ecke des Ordnersymbols, oder klicken Sie mit der rechten Maustaste auf den Shortcut und wählen Sie Eigenschaften.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/03-2-the-broken-symbolic-link-the-hidden-redirect.png)

In der Registerkarte "Allgemein" werden die Felder Name und Ziel grau dargestellt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/04-2-the-broken-symbolic-link-the-hidden-redirect.png)

**Warum es fehlschlägt:** Der "Wegweiser" befindet sich auf Ihrem Computer, aber das Ziel (wie ein `Z:`-Laufwerk oder ein Server) ist getrennt.

### 2.3 **3. Der unterbrochene Windows-Shortcut (.lnk-Datei)**

Ein Windows-Shortcut ist eine kleine Datei, die "auf" einen Ordner an einem anderen Ort "verweist". Diese können Links zu einem Ordner auf Ihrem eigenen Laufwerk oder zu einem Ordner auf einem entfernten Büroserver sein.

**Wie man sie unterscheidet:** Wie symbolische Links haben sowohl Ordner- als auch Laufwerk-Shortcuts einen kleinen blauen "Shortcut-Pfeil" in der unteren linken Ecke des Ordnersymbols, oder klicken Sie mit der rechten Maustaste auf den Shortcut und wählen Sie Eigenschaften.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/05-3-the-broken-windows-shortcut-lnk-file.png)

In der Registerkarte "Allgemein" schauen Sie sich das Feld Ziel an: _Lokaler Shortcut_ Das Ziel beginnt mit einem Laufwerksbuchstaben (z. B. `C:\Benutzer\...` oder `D:\Daten`).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/06-3-the-broken-windows-shortcut-lnk-file.png)

_Netzwerk-Shortcut_ Das Ziel beginnt mit einem Serverpfad (z. B. `\\ServerName\Ordner`) oder einem zugeordneten Netzlaufwerkbuchstaben (z. B. `Z:\ProjektDaten`).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/07-3-the-broken-windows-shortcut-lnk-file.png)

Unterschiedliche Verhaltensweisen beim Doppelklick Windows behandelt einen "unterbrochenen" lokalen Shortcut viel schneller als einen "unterbrochenen" Netzwerk-Shortcut.

**Lokaler Shortcut (Der "Gelöschte" Fehler):** Wenn der Ordner auf Ihrem Computer gelöscht wurde, erfährt Windows sofort davon. Wenn der Shortcut doppelgeklickt wird, wird sofort der folgende Fehler angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/08-3-the-broken-windows-shortcut-lnk-file.png)

**`Das Element, auf das dieser Shortcut verweist, wurde geändert, verschoben oder gelöscht.`**

**Netzwerk-Shortcut (Der "Hängen" Fehler):** Wenn der Shortcut auf einen Büroserver verweist und Sie offline sind (oder außerhalb des VPN), erfährt Windows nicht sofort, dass das Ziel fehlt. Es wird zunächst versuchen, den Server im Netzwerk zu "finden". Der Mauszeiger kann sich in einen Ladesymbol drehen, und das Fenster kann 30–60 Sekunden lang "hängen" oder einfrieren, bevor schließlich folgende Meldung angezeigt wird:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/09-3-the-broken-windows-shortcut-lnk-file.png)

**`Das Laufwerk oder die Netzwerkverbindung, auf das dieser Shortcut verweist, ist nicht verfügbar.`**

Wenn dem Desktop Connector mitgeteilt wird, einen dieser Shortcuts zu verwenden, während das Ziel fehlt oder das Netzwerk ausfällt, wird das Programm schließlich beim Warten auf den Windows-Pfad "zeitüberschritten". Weil der Desktop Connector kein gültiges Ziel finden kann, um mit der Arbeit zu beginnen, wird die Anwendung beendet und der Fehler wird gemeldet.

### 2.4 **So beheben Sie das Problem**

**Bestimmen Sie die Trennung** Versuchen Sie, den Zielordner in Windows Explorer zu öffnen. Wenn der Zielordner fehlt, muss entweder ein neuer Ordner an diesem Speicherort erstellt werden, oder ein anderer Ordner sollte im Desktop Connector ausgewählt werden.

**Erneut verbinden oder neu auswählen** Wenn ein Fehler "Netzwerkpfad nicht gefunden" oder "Laufwerk nicht verfügbar" angezeigt wird, bestätigen Sie die Verbindung zum Netzwerkpfad oder zum Laufwerk. Gehen Sie zu "Dieser PC" und stellen Sie sicher, dass Ihre Netzlaufwerke (wie `Z:`) aktiv sind. Überprüfen Sie, ob externe USB-Laufwerke oder Festplatten ordnungsgemäß angeschlossen sind. Wenn sie ein rotes X haben, doppelklicken Sie darauf, um die Verbindung erneut herzustellen. Wenn das Netzlaufwerk nicht aktiv ist und Sie wissen, mit welchem Netzwerk das Laufwerk verbunden ist, stellen Sie die Verbindung zum Netzwerk erneut her, indem Sie ein Kabel einstecken, sich über WLAN verbinden oder bei Verwendung eines VPN überprüfen, ob das VPN aktiv ist. Wenn das Laufwerk nicht mehr verfügbar ist, wählen Sie im Desktop Connector einen anderen Zielordner aus, der entweder auf dem lokalen Computer oder im Netzwerk verfügbar ist.

**Löschen/umbenennen und neu erstellen** Wenn ein lokaler Ordner oder Shortcut nach einem Neustart "feststeckt" (Sie sehen ihn, können ihn aber nicht öffnen): Benennen Sie den problematischen Ordner oder die Shortcut-Datei um (z. B. umbenennen von `ProjektDaten` zu `ProjektDaten_ALT`), oder löschen Sie ihn. Erstellen Sie einen brandneuen Standard-Ordner mit demselben Namen. Starten Sie die Übertragung erneut. Der Desktop Connector erkennt den frischen, fehlerfreien Ordner und nimmt den normalen Betrieb wieder auf.

**Warum wurde kein temporärer Ordner anstelle des fehlenden Ordners erstellt?** In anderen Situationen erstellt der Desktop Connector einen Ordner mit dem Suffix `_restricted` appended to the name, wenn etwas schief geht. Es gibt jedoch einen technischen Unterschied in der Behandlung von "fehlenden" Speicherorten durch Windows:

Der `_restricted`-Ordner wird nur erstellt, wenn der Ordner "physisch" vorhanden ist, aber "gesperrt" (wie eine Tür zu einem Zimmer, das verriegelt ist). In diesem Fall kann das Programm die Tür sehen und entscheidet sich, eine neue neben sich zu bauen (`_restricted`).

Im Fall des fehlenden Pfades ist es anders. Der Ordner ist nicht mehr vorhanden, oder der "Wegweiser" (symbolischer Link), der ausgewählt wurde, verweist auf einen leeren Speicherort. Für das Programm ist es nicht nur gesperrt – der gesamte "Raum" fehlt aus dem Gebäude. Weil es keine "Tür" zum Anfang gibt, kann das Programm keine `_restricted`-Version erstellen und muss beendet werden.

## 3. **Fehlender Bereitstellungspunkt**

In diesem Fall wird die Protokolldatei den folgenden Fehler anzeigen:

`Fehler: Ein Teil des Pfades '<path>' konnte nicht gefunden werden.`

Wenn der Ordner nicht geöffnet werden kann, versucht Windows, dem "Wegweiser" zu einem Netzwerkort zu folgen, und es wird der folgende Fehler angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/10-missing-mount-point.png)

`<Path> ist nicht zugänglich.`
`Der Netzwerkpfad wurde nicht gefunden`

In dieser Situation erstellt der Desktop Connector automatisch einen neuen Ordner mit dem Suffix `_restricted` appended to the name (z. B. `ProjektDaten_restricted`).

Dies geschieht, wenn ein Ordner auf dem Computer tatsächlich ein "Bereitstellungspunkt" (eine Tür) zu einem anderen Laufwerk ist. Beispiele für andere Laufwerke können Folgendes umfassen:

- USB-Stick,
- Externe Festplatte
- Netzwerkvolume, das derzeit getrennt ist.

Windows "erinnert" sich, dass der Ordner vorhanden ist, aber weil das physische Laufwerk fehlt, wird der Ordner zu einem "Geist". Der Desktop Connector erkennt, dass der Ordner vorhanden ist, kann aber nicht darin schreiben. Um zu verhindern, dass Ihre Daten verloren gehen, wird ein Schattenordner mit dem Suffix `_restricted` erstellt, damit Ihre Dateien einen sicheren Platz haben.

Hier sind einige typische Situationen, in denen dies vorkommen kann:

- Der Ordner wurde einem Laufwerk (wie `D:`) zugeordnet, das abgesteckt wurde.
- Der Ordner verweist auf eine Netzwerkfreigabe (wie `Z:`), die offline ist oder ein VPN erfordert.
- Ein Cloud-Service (Dropbox, OneDrive oder andere Synchronisationsdienste von Collaboration-Tools) hat einen "Platzhalter"-Ordner erstellt, der derzeit nicht aktiv ist.
- Ein Enterprise-Sicherheitstool "schützt" den Ordner, damit dieser nicht von Drittanwendungen geändert werden kann.

Um zu überprüfen, ob Ihr Ordner ein "Geist" ist, klicken Sie mit der rechten Maustaste auf den Ordner und wählen Sie Eigenschaften.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/11-missing-mount-point.png)

Schauen Sie sich das Feld "Typ" in der Registerkarte "Allgemein" an: Ein normaler Ordner wird "Dateiordner" anzeigen, während ein Schattenordner "Bereitgestelltes Volume" anzeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/12-missing-mount-point.png)

Wenn der bereitgestellte Ordner doppelgeklickt wird, wird sofort der folgende Fehler angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/13-missing-mount-point.png)

**`Speicherort ist nicht verfügbar`** oder

**`Der Netzwerkpfad wurde nicht gefunden`** `<Path> ist nicht verfügbar, daher ist der Link unterbrochen`

### 3.1 **So beheben Sie das Problem**

Ordner manuell neu erstellen Wenn der Ordner nach einem Neustart "feststeckt" bleibt:

1. Benennen Sie den problematischen Ordner um (z. B. umbenennen von `ProjektDaten` zu `ProjektDaten_ALT`).
1. Erstellen Sie einen brandneuen Ordner mit dem ursprünglichen Namen (`ProjektDaten`).
1. Der Desktop Connector erkennt den frischen, fehlerfreien Ordner und nimmt den normalen Betrieb ohne das Suffix `_restricted` wieder auf.

**Verbinden Sie Hardware oder Netzwerk erneut** Gehen Sie zu "Dieser PC" und stellen Sie sicher, dass Ihre Netzlaufwerke (wie `Z:`) aktiv sind. Überprüfen Sie, ob externe USB-Laufwerke oder Festplatten ordnungsgemäß angeschlossen sind. Wenn sie ein rotes X haben, doppelklicken Sie darauf, um die Verbindung erneut herzustellen. Wenn das Netzlaufwerk nicht aktiv ist und Sie wissen, mit welchem Netzwerk das Laufwerk verbunden ist, stellen Sie die Verbindung zum Netzwerk erneut her, indem Sie ein Kabel einstecken, sich über WLAN verbinden oder bei Verwendung eines VPN überprüfen, ob das VPN aktiv ist. Wenn das Laufwerk nicht mehr verfügbar ist, wählen Sie im Desktop Connector einen anderen Zielordner aus, der entweder auf dem lokalen Computer oder im Netzwerk verfügbar ist.

**Löschen/umbenennen und neu erstellen** Wenn ein lokaler Ordner oder Shortcut nach einem Neustart "feststeckt" (Sie sehen ihn, können ihn aber nicht öffnen): Benennen Sie den problematischen Ordner oder die Shortcut-Datei um (z. B. umbenennen von `ProjektDaten` zu `ProjektDaten_ALT`), oder löschen Sie ihn. Erstellen Sie einen brandneuen Ordner mit dem ursprünglichen Namen (`ProjektDaten`). Starten Sie die Übertragung erneut. Der Desktop Connector erkennt den frischen, fehlerfreien Ordner und nimmt den normalen Betrieb ohne das Suffix `_restricted` wieder auf.
