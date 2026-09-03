# Netzwerkempfehlung

Die Konfiguration des Netzwerks, mit dem das System verbunden ist, kann die Leistung beeinflussen, die Sie bei Catenda erleben.

## 1. **Netzwerkgeschwindigkeit**

Kontrollieren Sie die Qualität Ihres Netzwerks, sodass das Verhältnis zwischen Download und Upload etwa 1:10 oder höher liegt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4f22q5zf/01-network-speed.png)

(dieser Netzwerktest ist ein Beispiel, keine tatsächliche Anforderung)

## 2. **Proxies und Firewall:**

Benutzer, die auf Catenda Hub hinter einer Firewall, einem Proxy oder einem anderen Vermittler zugreifen, benötigen Zugriff auf die folgenden Domänen und Ports, damit die Anwendung ordnungsgemäß funktioniert.

### 2.1 **Domänen:**

(`*` bedeutet DNS-Wildcard und `.` ist ein Domänenebenen-Trennzeichen, behandeln Sie das Folgende nicht als Regexes).

- Catenda-Domänen:
  - `catenda.com`
  - `*.catenda.com`
    - `webviewer.catenda.com`
      Diese Unterdomäne muss in der Firewall zugelassen werden, um die Vorschau von Dokumenten auf der Dokumentvorschau-Seite anzuzeigen.
  - `*.*.catenda.com`

Wir empfehlen Ihnen, diesen neuen Domänennamen zu verwenden. Sie sollten keine Probleme mit weiteren Subdomänen wie `*.*.*.catenda.com` haben, aber falls doch, könnte es einfacher sein, alles von `catenda.com` zuzulassen

**Verwaltete Domänen** Die folgenden Domänen werden in absehbarer Zeit beibehalten, aber nicht in technischer Literatur referenziert.

- `bimsync.com`
- `*.bimsync.com`
- `*.*.bimsync.com`

**Dienste** Catenda Hub nutzt die folgenden Dienste:

- `*.google-analytics.com`
- `*.googletagmanager.com`
- `*.intercom.io`
- `*.intercomcdn.com`
- `*.sentry.io`

**Plugins** Wenn Sie beabsichtigen, Catenda Hub nur über eines unserer Plugins zu nutzen, sind dies die einzigen Domänen, die Sie durch Ihre Firewall zulassen müssen.

- Für die Authentifizierung von Plugins und Integrationen
  - `hub.catenda.com`
  - `api.catenda.com `
  - `bimsync.com`
  - `api.bimsync.com`
- Zur Verwendung von Plugins
  - Revit-Plugin
    - [`https://revit.plugins.catenda.com`](https://revit.plugins.catenda.com)
    - [`https://revit.plugins.bimsync.com`](https://revit.plugins.bimsync.com)
  - Archicad-Plugin
    - [`https://archicad.plugins.catenda.com`](https://archicad.plugins.catenda.com)
    - [`https://archicad.plugins.bimsync.com`](https://archicad.plugins.bimsync.com)
  - Navisworks-Plugin
    - [`https://navisworks.plugins.catenda.com`](https://navisworks.plugins.catenda.com)
    - [`https://navisworks.plugins.bimsync.com`](https://navisworks.plugins.bimsync.com)
  - Tekla-Plugin
    - [`https://tekla.plugins.catenda.com`](https://tekla.plugins.catenda.com)
    - [`https://tekla.plugins.bimsync.com`](https://tekla.plugins.bimsync.com)
- Zur Verwendung von Plugins und Integrationen, die Themen verwenden, die [hier](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations) aufgelistet sind
  - [`https://bcf.bimsync.com/`](https://bcf.bimsync.com/)
  - [`https://opencde.bimsync.com/`](https://opencde.bimsync.com/)

## 3. **Portkonfiguration**

### 3.1 **Port 80**

Dieser Port ist optional, wird aber für das beste Browsererlebnis empfohlen. Protokoll: TCP (nur für hub.catenda.com und [www.hub.catenda.com](http://www.hub.catenda.com)) Clients, die versuchen, eine Anfrage auf Port 80 zu stellen, werden umgeleitet, um den entsprechenden verschlüsselten Aufruf auf Port 443 zu tätigen.

### 3.2 **Port 443**

Protokoll: TCP + UDP Der gesamte Catenda Hub-Datenverkehr ist auf diesem Port TLS-verschlüsselt. UDP ist optional, wird aber für das beste Benutzererlebnis empfohlen, da es kompatiblen Browsern und anderen Clients ermöglicht, von Fortschritten im HTTP-Protokoll zu profitieren, wie z. B. HTTP/3 (ehemals QUIC), das wir auf der gesamten Plattform einführen.
