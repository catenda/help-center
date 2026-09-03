# Fehlerbehebung bei der Dokumentvorschau

## 1. **1. Keine Verbindung zum Server**

Wenn ein Dokument geöffnet wird, kann die Dokumentvorschau ausgegraut sein und zeigt eine zentrierte Nachricht:

`Keine Verbindung zum Server`

Dieses Problem kann sich auch als schwere Plattformverlangsamung oder Laderäder manifestieren, die nie aufhören zu drehen, besonders auf der Seite **Sammlungen** oder beim Versuch, die **Modellliste** im 3D-Viewer zu laden.

### 1.1 **1.1 Warum dies geschieht**

Es gibt eine Einschränkung auf dem spezifischen Internetnetz oder der verwendeten VPN-Verbindung. Die Sicherheitseinstellungen im Netz ermöglichen es, dass die Hauptwebseite von Catenda geladen wird, blockieren oder lehnen aber vollständig die Hintergrundverbindungen ab, die die Plattform zum Senden und Empfangen großer Projektdaten und 3D-Modelle verwendet. Da diese Hintergrund-Datenströme unterbrochen sind, kann das System die Informationen nicht laden, was dazu führt, dass die Plattform auf unbestimmte Zeit blockiert oder eine Verbindungsfehler angezeigt wird.

### 1.2 **1.2 Troubleshooting-Schritt**

Bestätigen Sie, ob das Netzwerk die Blockade verursacht. Versuchen Sie, die Plattform oder die Dokumentvorschau zu laden, während Sie mit einem anderen Netz verbunden sind, beispielsweise einem mobilen Hotspot. Wenn die Seite und die Daten dort normal geladen werden, blockiert die primäre Netzwerkkonfiguration den Datenverkehr.

### 1.3 **1.3 Permanente Behebung für Netzwerkadministratoren**

Um dieses Problem dauerhaft zu beheben, muss die Netzwerkkonfiguration aktualisiert werden, um den Catenda-Hintergrundverkehr vollständig zu unterstützen, einschließlich aller Subdomänen und erforderlichen Ports. Klicken Sie [hier](https://support.catenda.com/en/articles/13927294-network-recommendation), um mehr über Whitelist-Anforderungen und Port-Spezifikationen (einschließlich obligatorischer Port-443-TCP/UDP-Konfigurationen) zu erfahren.

## 2. **2. Fehler beim Laden des Dokuments (Timeout beim Lesen)**

Wenn ein Dokument geöffnet wird, kann der Web-Viewer, der die Dokumentvorschau anzeigt, eine Nachricht anzeigen, die besagt: **"Timeout beim Lesen"**.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hq07qt4s/01-2-error-loading-document-read-timed-out.png)

`Timeout beim Lesen`

### 2.1 **2.1 Warum dies geschieht**

Die Sicherheitseinstellungen im verwendeten Netz erlauben nur der Hauptadresse der Catenda-Website, durchzugehen. Die Firewall des Netzes erkennt oder erlaubt keine Wildcard-Einstellung (die automatisch alle Adressen mit `.catenda.com` zulässt), daher blockiert sie die spezifische, separate Hintergrundadresse, die Dokumentvorschauen behandelt (`webviewer.catenda.com`). Anstatt die Verbindung sofort abzulehnen, ignoriert die Firewall die Anfrage, bis der Browser aufgibt, was zu einem Timeout-Fehler führt.

### 2.2 **2.2 Troubleshooting-Schritt**

Bestätigen Sie, ob die Netzwerkkonfiguration das Timeout verursacht. Versuchen Sie, die Dokumentvorschau zu laden, während Sie mit einem anderen Netz verbunden sind, beispielsweise einem mobilen Hotspot. Wenn die Vorschau dort normal geladen wird, blockiert die Firewall-Konfiguration des primären Netzes den Datenverkehr.

### 2.3 **2.3 Permanente Behebung für Netzwerkadministratoren**

Um dieses Problem dauerhaft zu beheben, muss die Firewall-Konfiguration des Netzes aktualisiert werden, um die spezifische Adresse für Dokumentvorschauen (`webviewer.catenda.com`) explizit zuzulassen. Klicken Sie [hier](https://netw), um mehr über Whitelist-Regeln und Port-Spezifikationen zu erfahren.
