# Netwerkadvisering

De configuratie van het netwerk waarop het systeem is aangesloten, kan de prestaties van Catenda beïnvloeden.

## 1. **Netwerksnelheid**

Controleer de kwaliteit van uw netwerk, zodat de verhouding tussen Download en Upload ongeveer 1:10 of hoger is.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4f22q5zf/01-network-speed.png)

(deze netwerktest is een voorbeeld, geen werkelijke vereiste)

## 2. **Proxy's en firewall:**

Gebruikers die toegang hebben tot Catenda Hub achter een firewall, proxy of ander intermediair, hebben toegang nodig tot de volgende domeinen en poorten om de toepassing correct te laten functioneren.

### 2.1 **Domeinen:**

(`*` betekent DNS-wildcard en `.` is een domeinniveauscheiding, behandel het onderstaande niet als regex's).

- Catenda-domeinen:
  - `catenda.com`
  - `*.catenda.com`
    - `webviewer.catenda.com`
      Dit subdomein moet door de firewall toegestaan zijn om de voorbeeldweergave van Documenten op de pagina met documentvoorbeelden te kunnen bekijken.
  - `*.*.catenda.com`

We raden u aan deze nieuwe domeinnaam te gebruiken. U zou geen problemen moeten ondervinden met meer subdomeinen zoals `*.*.*.catenda.com`, maar als dat wel het geval is, kan het gemakkelijker zijn om alles van `catenda.com` toe te staan

**Onderhouden domeinen** De volgende domeinen zullen in de nabije toekomst onderhouden worden, maar worden niet genoemd in technische literatuur.

- `bimsync.com`
- `*.bimsync.com`
- `*.*.bimsync.com`

**Services** Catenda Hub maakt gebruik van de volgende services:

- `*.google-analytics.com`
- `*.googletagmanager.com`
- `*.intercom.io`
- `*.intercomcdn.com`
- `*.sentry.io`

**Plugins** Als u Catenda Hub alleen via een van onze plugins wilt gebruiken, zijn dit de enige domeinen die u door uw firewall hoeft toe te staan.

- Voor authenticatie van plugins en integraties
  - `hub.catenda.com`
  - `api.catenda.com `
  - `bimsync.com`
  - `api.bimsync.com`
- Voor gebruik van plugin
  - Revit-plugin
    - [`https://revit.plugins.catenda.com`](https://revit.plugins.catenda.com)
    - [`https://revit.plugins.bimsync.com`](https://revit.plugins.bimsync.com)
  - Archicad-plugin
    - [`https://archicad.plugins.catenda.com`](https://archicad.plugins.catenda.com)
    - [`https://archicad.plugins.bimsync.com`](https://archicad.plugins.bimsync.com)
  - Navisworks-plugin
    - [`https://navisworks.plugins.catenda.com`](https://navisworks.plugins.catenda.com)
    - [`https://navisworks.plugins.bimsync.com`](https://navisworks.plugins.bimsync.com)
  - Tekla-plugin
    - [`https://tekla.plugins.catenda.com`](https://tekla.plugins.catenda.com)
    - [`https://tekla.plugins.bimsync.com`](https://tekla.plugins.bimsync.com)
- Voor gebruik van plugins en integraties die topics gebruiken die [hier](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations) worden vermeld
  - [`https://bcf.bimsync.com/`](https://bcf.bimsync.com/)
  - [`https://opencde.bimsync.com/`](https://opencde.bimsync.com/)

## 3. **Poortconfiguratie**

### 3.1 **Poort 80**

Deze poort is optioneel, maar aanbevolen voor de beste gebruikerservaring in de browser. Protocol: TCP (alleen voor hub.catenda.com en [www.hub.catenda.com](http://www.hub.catenda.com)) Clients die een verzoek op poort 80 doen, worden omgeleid om het equivalente versleutelde verzoek op poort 443 in te dienen.

### 3.2 **Poort 443**

Protocol: TCP + UDP Al het Catenda Hub-verkeer is versleuteld met TLS op deze poort. UDP is optioneel, maar aanbevolen voor de beste gebruikerservaring, omdat het compatibele browsers en andere clients in staat stelt om voordeel te halen uit vooruitgang in het HTTP-protocol, zoals HTTP/3 (voorheen QUIC) dat we over het gehele platform uitrollen.
