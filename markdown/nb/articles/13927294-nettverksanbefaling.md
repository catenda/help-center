# Nettverksanbefaling

Konfigurasjonen av nettverket som systemet er koblet til, kan påvirke ytelsen du opplever på Catenda.

## 1. **Nettverkshastighet**

Kontroller kvaliteten på nettverket ditt, slik at forholdet mellom nedlasting og opplasting er omkring 1:10 eller høyere.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4f22q5zf/01-network-speed.png)

(denne nettverkstesten er et eksempel, ikke faktisk krav)

## 2. **Mellommenn og brannmur:**

Brukere som får tilgang til Catenda Hub bak en brannmur, mellomtjeneste eller annen formidler, må ha tilgang til følgende domener og porter for at applikasjonen skal fungere som den skal.

### 2.1 **Domener:**

(`*` betyr DNS-jokertegn og `.` er en domenenivåskiller, ikke behandle det nedenfor som regexer).

- Catenda-domener:
  - `catenda.com`
  - `*.catenda.com`
    - `webviewer.catenda.com`
      Dette underdomenet må være tillatt i brannmuren for å vise forhåndsvisningen av dokumenter på dokumentforhåndsvisningssiden.
  - `*.*.catenda.com`

Vi oppfordrer deg til å bruke dette nye domenenavnet. Du burde ikke få problemer med flere underdomener som `*.*.*.catenda.com`, men hvis du gjør det, kan det være lettere å tillate alt fra `catenda.com`

_Vedlikeholdte domener_ Følgende domener vil bli vedlikeholdt i overskuelig framtid, men ikke referert i teknisk litteratur.

- `bimsync.com`
- `*.bimsync.com`
- `*.*.bimsync.com`

_Tjenester_ Catenda Hub bruker følgende tjenester:

- `*.google-analytics.com`
- `*.googletagmanager.com`
- `*.intercom.io`
- `*.intercomcdn.com`
- `*.sentry.io`

_Plugins_ Hvis du bare har til hensikt å bruke Catenda Hub gjennom ett av våre plugins, er disse de eneste domenene du trenger å tillate gjennom brannmuren din.

- For autentisering av plugins og integrasjoner
  - `hub.catenda.com`
  - `api.catenda.com`
  - `bimsync.com`
  - `api.bimsync.com`
- For bruk av plugin
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
- For bruk av plugins og integrasjoner som bruker saker som er oppført [her](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)
  - [`https://bcf.bimsync.com/`](https://bcf.bimsync.com/)
  - [`https://opencde.bimsync.com/`](https://opencde.bimsync.com/)

## 3. **Portkonfigurasjon**

### 3.1 **Port 80**

Denne porten er valgfri, men anbefalt for best brukeropplevelse i nettleseren. Protokoll: TCP (kun for hub.catenda.com og [www.hub.catenda.com](http://www.hub.catenda.com)) Klienter som forsøker å foreta en forespørsel på 80, blir omdirigert til å gjøre den tilsvarende krypterte anropet på port 443.

### 3.2 **Port 443**

Protokoll: TCP + UDP All Catenda Hub-trafikk er TLS-kryptert på denne porten. UDP er valgfritt, men anbefalt for best brukeropplevelse, da det tillater kompatible nettlesere og andre klienter å dra fordel av fremskritt i HTTP-protokollen, som HTTP/3 (tidligere QUIC) som vi utrulles på tvers av plattformen.
