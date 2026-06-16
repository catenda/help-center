# Systemanforderungen und -optimierung

Dieser Artikel enthält Informationen über die minimalen Systemvoraussetzungen für die Nutzung von Catenda Hub. Catenda Hub kann über den Browser aufgerufen werden und muss nicht installiert werden.

Die folgenden Themen werden in diesem Artikel beschrieben:

Optimierung - Proxies and firewall - Ports

## Hardware-Empfehlung:

Für reguläre Projekte (bis zu LOD 300):

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p class="intercom-align-center"><b>Processor</b></p></td><td><p class="intercom-align-center"><b>RAM</b></p></td><td><p class="intercom-align-center"><b>GPU</b></p></td></tr><tr><td><p class="intercom-align-center">Intel Core i5 or eq.</p></td><td><p class="intercom-align-center">8 to 16 GB</p></td><td><p class="intercom-align-center">integrated / 4GB</p></td></tr></tbody></table></div>

For Dense Geometry projects (LOD 400 and above):

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p class="intercom-align-center"><b>Processor</b></p></td><td><p class="intercom-align-center"><b>RAM</b></p></td><td><p class="intercom-align-center"><b>GPU</b></p></td></tr><tr><td><p class="intercom-align-center">Intel Core i7 or eq.</p></td><td><p class="intercom-align-center">32GB</p></td><td><p class="intercom-align-center">8GB</p></td></tr></tbody></table></div>

[LOD Definition](https://www.gsa.gov/real-estate/design-and-construction/3d4d-building-information-modeling/bim-software-guidelines/document-guides/level-of-detail)

### Dedizierter Grafikprozessor vs. integrierter Grafikprozessor

Vergewissern Sie sich, dass Sie den dedizierten Grafikprozessor Ihres Systems und nicht den integrierten Grafikprozessor verwenden. Unter Windows 10 können Sie sicherstellen, dass Sie den dedizierten Grafikprozessor verwenden, indem Sie [diese](https://superuser.com/questions/1439471/how-can-i-force-my-dedicated-gpu-to-handle-all-applications-or-disable-my-integr#:~:text=use%20these%20steps%3A-,Open%20Settings.,-Click%20on%20System) Schritte ausführen.

## Optimierung des 3D-Viewers:

Obwohl Catenda Hub gut optimiert ist und die meisten Modelle ausführen kann, möchten sich einige Benutzer so gut wie möglich auf den Erfolg vorbereiten. Im Folgenden finden Sie daher einige Strategien, mit denen Sie Ihren Arbeitsablauf in Catenda Hub optimieren können:

### Viele Objekte:

Wenn weniger Modelle geladen werden, bedeutet dies natürlich auch weniger Objekte und damit eine bessere Leistung.

Die Aktivierung des inkrementellen Renderings beschleunigt das Drehen um Modelle mit viel Geometrie, da beim Drehen nicht alle Objekte geladen werden müssen.

Als letzten Schritt können Sie eine Abfrage des Bereichs machen, in dem Sie arbeiten. Wenn Sie einen Teil des Modells abtrennen, befinden sich die Objekte normalerweise noch im Speicher und sind nur ausgeblendet; mit einer Abfrage werden diese Objekte vollständig entfernt, was die Arbeit mit dem Modell erleichtert. Beachten Sie, dass Sie bei Abfragen keine Eigenschaftsbibliotheken verwenden können, da nicht alle Objekte geladen werden.

### Punktwolken

Wenn Sie eine feste Punktgröße verwenden, kann es sein, dass Sie eine niedrige Bildwiederholrate haben, wenn viele Punkte geladen wurden. Es kann auch vorkommen, dass das Laden von Punkten länger dauert, wenn das Speicherbudget Ihres Systems erreicht ist. Die Punkte, die sich am nächsten zur Kamera befinden, werden zuerst geladen. Wenn Sie also Punkte an einer bestimmten Stelle laden möchten, ist es besser, zu dieser Position zu navigieren und dann die Punktwolke zu aktivieren, damit die Punkte dort zuerst geladen werden.

Um zu verhindern, dass das Speicherlimit erreicht wird und die Bildwiederholrate sinkt, können Sie das Punktbudget verringern, damit weniger Punkte geladen werden.

## Browser-Einstellungen

### Systemanforderungen:

Catenda Hub ist in verschiedenen Browsern verfügbar.

Anforderungen an die Browser, die für den Zugriff auf Catenda Hub verwendet werden können:

_Chrome: _[https://support.google.com/chrome/answer/95346?hl=en&co=GENIE.Platform%3DDesktop&sjid=15879972061287151057-EU](https://support.google.com/chrome/answer/95346?hl=en&co=GENIE.Platform%3DDesktop&sjid=15879972061287151057-EU) _Firefox:_ [https://www.mozilla.org/en-US/firefox/114.0.2/system-requirements/](https://www.mozilla.org/en-US/firefox/114.0.2/system-requirements/) _Microsoft Edge:_ Windows 11 system requirements: [https://www.microsoft.com/en-in/windows/windows-11-specifications](https://www.microsoft.com/en-in/windows/windows-11-specifications)

Safari:

[https://support.apple.com/en-us/112653](https://support.apple.com/en-us/112653)

_Opera:_ [https://www.opera.com/download/requirements](https://www.opera.com/download/requirements) _Vivaldi:_ [https://help.vivaldi.com/desktop/install-update/install-the-vivaldi-browser/](https://help.vivaldi.com/desktop/install-update/install-the-vivaldi-browser/)

### Hardware-Beschleunigung

Vergewissern Sie sich, dass Sie die Hardware-Beschleunigung für die verschiedenen Browser verwenden, die Sie hier finden:

**Chrome:**

[chrome://settings/?search=hardware+acceleration](chrome://settings/?search=hardware+acceleration) _Firefox:_ [https://support.mozilla.org/en-US/kb/performance-settings?as=u&utm\_source=inproduct](https://support.mozilla.org/en-US/kb/performance-settings?as=u&utm_source=inproduct) _Microsoft Edge:_ [edge://settings/?search=hardware%20acceleration](edge://settings/?search=hardware%20acceleration) _Safari:_

[https://support.apple.com/en-us/102894](https://support.apple.com/en-us/102894)

_Opera:_ [https://blogs.opera.com/news/2015/07/advanced-settings-in-opera/](https://blogs.opera.com/news/2015/07/advanced-settings-in-opera/)

_Vivaldi:_ [https://forum.vivaldi.net/topic/1207/hardware-acceleration](https://forum.vivaldi.net/topic/1207/hardware-acceleration)

### Externe Faktoren

Bitte prüfen Sie, ob Sie Browser-Erweiterungen oder andere Programme verwenden, die Ihre Catenda Hub-Erfahrung verlangsamen könnten.

Bester Browser nach Speicherverbrauch unter Windows:

1. Firefox
1. Chrome
1. Microsoft Edge

### **Cookies**

Anhand der in den Cookies gespeicherten Daten kann Ihr Browser erkennen, ob Sie angemeldet sind und welche Präferenzen Sie in den Catenda-Projekten haben. Einige Einstellungen können sich von Projekt zu Projekt unterscheiden, während andere für alle Projekte gleich sind. Wenn Sie z.B. das Filtermenü in einem Tab schließen und dann dieselbe Seite in einem anderen Tab aktualisieren, wird das Filtermenü auch in diesem Tab geschlossen.

Angenommen, Sie melden sich in einer Registerkarte ab, um sich bei einem anderen Konto anzumelden, und aktualisieren dann die Seite in einer anderen Registerkarte, dann sind Sie mit dem anderen Konto angemeldet, das möglicherweise keinen Zugriff auf das Projekt hat, in dem Sie sich befunden haben.

In Chrome können Sie Ihre Cookies wie folgt verwalten:Klicken Sie auf Cookies und Standortdaten

![](https://downloads.intercomcdn.com/i/o/areracg3/1385208428/41d738ac77adb12dfb213288a3ef/image.png?expires=1781092800&signature=2dcb38d6ef6bc67c6288c0c52208d926c46c22939fb280c5e2439d8c674e7348&req=dSMvE8t%2BlYVdUfMW3nq%2BgaHQRpCY0DDg4am2VqCgtd5aHqgQSEVyYa63Etcf%0AIYTh4ag1x6%2BEBYELpmPs63uWpbk%3D%0A)

Klicken Sie auf On-Device-Site-Daten verwalten

![](https://downloads.intercomcdn.com/i/o/areracg3/1385208427/1240f9ce5e3bca59db6965f91c1f/image.png?expires=1781092800&signature=e62261125a92d2a971d3cb060de1fc3245840ae390996a8a5c9fae8f54ccd4c3&req=dSMvE8t%2BlYVdXvMW3nq%2BgXQzVzQL4Kv%2B%2BEyoRaBDmKwAZsMuS54MMiM8bokV%0AUOEl2pkb5OgdyQmHVUYGOGzNEgE%3D%0A)

So können Ihre Standortdateneinstellungen aussehen:

![](https://downloads.intercomcdn.com/i/o/areracg3/1385208430/7e63d3007bb9802315f33cf4c92f/image.png?expires=1781092800&signature=9b253dcd15cc3db785e940a18c354145a08e379980c71a900d2cf7aaf0477c86&req=dSMvE8t%2BlYVcWfMW3nq%2BgVLmKejEvgE%2F1qIyGjoVTpVZE8DqzdpAw0C0AupP%0AWnifyOlHyHVyRqy00xPEZMr22Zg%3D%0A)

Um Catenda Hub zu nutzen, müssen Sie zumindest die Speicherung von Daten für hub.catenda.com während Ihrer Sitzung zulassen. Wenn Sie sich dafür entscheiden, Daten beim Schließen aller Fenster zu löschen, werden Ihre Daten bei jeder Nutzung von Catenda zurückgesetzt. Wenn Sie Ihre Daten bei jedem Schließen aller Fenster löschen, werden Ihre Einstellungen jedes Mal nach dem Schließen aller Fenster Ihres Browsers zurückgesetzt.

## Geschwindigkeit des Netzes

Kontrollieren Sie die Qualität Ihres Netzwerks, so dass das Verhältnis zwischen Download und Upload

etwa 1:10 oder mehr beträgt.

![](https://downloads.intercomcdn.com/i/o/areracg3/1385208426/e7d5bd69853c947000e83a8f6343/5e52d40f-4227-418f-b23b-20fa30a307e2?expires=1781092800&signature=c484fe4b96b33864fbe2916366f4bda8f6e2a55c26518932b36a7d0ff8625fb7&req=dSMvE8t%2BlYVdX%2FMW3nq%2BgW%2FIiSEwMcuWTEtt71X8FCEOMaRFiZC9BYZIxV%2FD%0ANPguDFRXdXUZI2249%2BwUN02I71I%3D%0A)

(dies ist ein Beispiel, keine tatsächliche Anforderung)

## Proxies und Firewall:

Benutzer, die auf Catenda Hub hinter einer Firewall, einem Proxy oder einem anderen Vermittler zugreifen, benötigen Zugang zu den folgenden Domänen und Ports, damit die Anwendung ordnungsgemäß funktioniert.

### Domains:

(`\*` means DNS wildcard and `.` is a domain level separator, don't treat the below as regexes).

- Catenda domains:
    - `catenda.com`
    - `\*.catenda.com`
        - `webviewer.catenda.com`
    - `\*.\*.catenda.com`

Wir empfehlen Ihnen, diesen neuen Domänennamen zu verwenden. Sie sollten keine Probleme mit weiteren Subdomains wie \*.\*.\*.catenda.com haben, aber falls doch, ist es vielleicht einfacher, alles von catenda.com aus zuzulassen

Gepflegte Domänen

Die folgenden Bereiche werden in absehbarer Zeit beibehalten, aber nicht in der Fachliteratur erwähnt.

- `bimsync.com`
- `\*.bimsync.com`
- `\*.\*.bimsync.com`

Dienstleistungen

Catenda Hub nutzt die folgenden Dienste:

- `\*.google-analytics.com`
- `\*.googletagmanager.com`
- `\*.intercom.io`
- `\*.intercomcdn.com`
- `\*.sentry.io`

**Plugins**

Wenn Sie Catenda Hub nur über eines unserer Plugins nutzen wollen, sind dies die einzigen Domains, die Sie durch Ihre Firewall lassen müssen.

- Für die Authentifizierung von Plugins und Integrationen
    - `hub.catenda.com`
    - `api.catenda.com `
    - `bimsync.com`
    - `api.bimsync.com`
- Zur Verwendung des Plugins
    - Revit plugin
        - `https://revit.plugins.catenda.com`
        - `https://revit.plugins.bimsync.com`
    - Archicad plugin
        - `https://archicad.plugins.catenda.com`
        - `https://archicad.plugins.bimsync.com`
    - Navisworks plugin
        - `https://navisworks.plugins.catenda.com`
        - `https://navisworks.plugins.bimsync.com`
    - Tekla plugin
        - `https://tekla.plugins.catenda.com`
        - `https://tekla.plugins.bimsync.com`
- For use of integration
    - Solibri BCF Live connector
        - `https://bcf.bimsync.com/`
        - `https://opencde.bimsync.com/`

## **Ports:**

**80:** Dieser Port ist optional, wird aber für eine optimale Benutzerfreundlichkeit im Browser empfohlen. Protokoll: TCP (nur für hub.catenda.com und www.hub.catenda.com)

Clients, die versuchen, eine Anfrage über 80 zu stellen, werden umgeleitet, um den entsprechenden verschlüsselten Anruf über Port 443 zu tätigen.

**443:**

Protokoll: TCP + UDPDer gesamte Catenda Hub-Datenverkehr wird auf diesem Port TLS-verschlüsselt.

UDP ist optional, wird aber für ein optimales Benutzererlebnis empfohlen, da es kompatiblen Browsern und anderen Clients ermöglicht, die Fortschritte im HTTP-Protokoll zu nutzen, wie z. B. HTTP/3 (früher QUIC), das wir plattformübergreifend einführen.
