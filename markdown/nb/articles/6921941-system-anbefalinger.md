# System anbefalinger

Denne artikkelen inneholder information om anbefalte system krav for bruk av Catenda Hub. Catenda Hub er tilgjengelig gjennom nettleseren og det er ingen behov for installasjon.

Denne artikkelen inneholder informasjon om følgende temaer:

**[System anbefalinger](#h_635eb6138d) - [Optimalisering](#h_d5aa0a3232) - [Nettleser](#h_36e3ce3a14) - [Nettverk](#h_46ad0a2b18) - [Proxyer og brannmur](#h_6cbd0fccb9) - [Porter](#h_bb33c61f6f)**

## **System anbefalinger:**

**(Juni 2024)**

For vanlige prosjekt (opp til LOD 300):

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p class="intercom-align-center"><b>Prosessor</b></p></td><td><p class="intercom-align-center"><b>RAM</b></p></td><td><p class="intercom-align-center"><b>GPU</b></p></td></tr><tr><td><p class="intercom-align-center">Intel Core i5 eller liknende</p></td><td><p class="intercom-align-center">8 til 16 GB</p></td><td><p class="intercom-align-center">integrert / 4GB</p></td></tr></tbody></table></div>

For tette geometri prosjekter (LOD 400 og over):

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p class="intercom-align-center"><b>Processor</b></p></td><td><p class="intercom-align-center"><b>RAM</b></p></td><td><p class="intercom-align-center"><b>GPU</b></p></td></tr><tr><td><p class="intercom-align-center">Intel Core i7 eller liknende</p></td><td><p class="intercom-align-center">32GB</p></td><td><p class="intercom-align-center">8GB</p></td></tr></tbody></table></div>

[LOD Definisjon](https://www.gsa.gov/real-estate/design-and-construction/3d4d-building-information-modeling/bim-software-guidelines/document-guides/level-of-detail)

### **Dedikert GPU vs integrert GPU**

Pass på at du bruker den dedikerte GPUen til ditt system og ikke den integrerte GPUen.

På Windows 10 kan du forsikre at du bruker den dedikerte GPUen ved å følge [disse](https://superuser.com/questions/1439471/how-can-i-force-my-dedicated-gpu-to-handle-all-applications-or-disable-my-integr#:~:text=use%20these%20steps%3A-,Open%20Settings.,-Click%20on%20System) steg.

## **3D viser optimalisering:**

Selv om Catenda Hub kan fremvise de fleste modeller på en optimert måte kan det hende at noen brukere ønsker å komme så langt de kan med det de har. Her er derfor noen strategier som kan brukes til å optimalisere dine arbeidsflyt i Catenda Hub:

### **Mange objekter:**

Å bruke færre modeller og dermed færre objekter kan være en løsning for å få bedre ytelse. Andre måter du kan øke ytelsen for å fremvise mange objekter av gangen er:

**Skru på inkrementell tegning**

[Inkrementell tegning](https://support.catenda.com/nb/articles/5784718-3d-viser-innstillinger#h_3d1b7c0b7f) innstillingen øker hastigheten du kan rotere rundt modeller med mye geometri med siden ikke alle objekter må fremvises mens du roterer.

**Lag Spørringer**

Som et siste steg kan du lage en [spørring](https://intercom.help/bimsync-arena/en/articles/4854514-queries) av utsnittet du jobber med. Vanligvis når tar ut en del av modellen ved å begrense den med klippeplan er objektene fortsatt lastet i minnet og bare skjult.

Med en spørring vil disse objekte være helt lastet ut og det vil dermed være lettere å jobbe med modellen. Husk at du ikk vil kunne bruke egenskapsbibliotek med spørringer for ikke alle objekter er lastet inn.

### **Punktsky**

Bruker du [fast punktstørrelse](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=Adaptive%20(default)%2C%20or-,Fixed%20size,-.%20The%20slider%20below) kan det hende at du ender opp med lav bildefrekvens  når mange punkt er lastet inn. Du kan også erfare at punkt tar lenger å laste inn når du når minnebuddsjettet til ditt system. Punkt nærmest kameraet er lastet inn først så hvis du ønsker å laste punkt på et spesifikt sted er det bedre å først navigere til det stedet for å så skru på punksky så det starter å laste punkt som er der først.

For å unngå å nå minnebegrensningen og få lavere bildefrekvens kan du senke [punktbudsjettet](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=with%20your%20PC.-,Point%20Budget%3A,-Using%20the%20viewer) så færre punkt lastes inn.

## **Nettleserinnstillinger**

### **Systemkrav:**

Catenda Hub er tilgjengelig gjennom forskjellige nettlesere.

Krav for nettlesere som kan brukes til å nå Catenda Hub:

_Chrome: _[https://support.google.com/chrome/answer/95346?hl=en&co=GENIE.Platform%3DDesktop&sjid=15879972061287151057-EU](https://support.google.com/chrome/answer/95346?hl=en&co=GENIE.Platform%3DDesktop&sjid=15879972061287151057-EU) _Firefox:_ [https://www.mozilla.org/en-US/firefox/114.0.2/system-requirements/](https://www.mozilla.org/en-US/firefox/114.0.2/system-requirements/) _Microsoft Edge:_ Windows 11 systemkrav: [https://www.microsoft.com/en-in/windows/windows-11-specifications](https://www.microsoft.com/en-in/windows/windows-11-specifications)

Safari:

[https://support.apple.com/en-us/112653](https://support.apple.com/en-us/112653)

_Opera:_ [https://www.opera.com/download/requirements](https://www.opera.com/download/requirements) _Vivaldi:_ [https://help.vivaldi.com/desktop/install-update/install-the-vivaldi-browser/](https://help.vivaldi.com/desktop/install-update/install-the-vivaldi-browser/)

### **Maskinvareakselerasjon**

Pass på at du bruker maskinvareaksellerasjon.

Maskinvareaksellerasjonsvalg for de forskjellige nettlesere kan bli funnet her:

**Chrome:**

[chrome://settings/?search=hardware+acceleration](chrome://settings/?search=hardware+acceleration) _Firefox:_ [https://support.mozilla.org/en-US/kb/performance-settings?as=u&utm\_source=inproduct](https://support.mozilla.org/en-US/kb/performance-settings?as=u&utm_source=inproduct) _Microsoft Edge:_ [edge://settings/?search=hardware%20acceleration](edge://settings/?search=hardware%20acceleration)

**Safari:**

[https://support.apple.com/en-us/102894](https://support.apple.com/en-us/102894)

_Opera:_ [https://blogs.opera.com/news/2015/07/advanced-settings-in-opera/](https://blogs.opera.com/news/2015/07/advanced-settings-in-opera/)

_Vivaldi:_ [https://forum.vivaldi.net/topic/1207/hardware-acceleration](https://forum.vivaldi.net/topic/1207/hardware-acceleration)

### ​**Ytre faktorer**

Sjekk om du nar noen nettleser utvidelser eller andre program på ditt system som kan gjøre din Catenda Hub erfaring tregere.

**De beste nettlesere etter minnebruk:**

1. Firefox
1. Chrome
1. Microsoft Edge

### **Informasjonskapsler**

Med dataen lagret i informasjonskapsler i din nettleser vil den kunne vite om du er logget inn og noen av dine preferanser i Catenda prosjekter. Noen preferanser kan være forskjellige fra prosjekt til prosjekt mens andre kan være like for alle prosjekt. Hvis du ender dinne innstillinger gjennom å for eksempel lukke en meny vil dette være husket i alle nettleservindu og faner.

Hvis du for eksempel lukker filtermenyen i en fane og laster inn den samme siden i en annen fane vil filter menyen også være lukket i den fanen.

På denne måten husker også nettleseren om du er logget inn eller ikke.

Si at du har logget ut i en fane og har logget inn med en annen konto, hvis du da laster inn siden til en annen fane på nytt vil du finne deg selv logget inn med en andre kontoen som ikke nødvendigivis har tilgang til prosjektet du var del av.

På chrome vil du kunne koble på og redigere dine informasjonskapsler som under:

Klikk på Cookies and site data

![](https://downloads.intercomcdn.com/i/o/1143829455/e1b8867e01930b24ef529e47/image.png?expires=1781092800&signature=e2930701f16f0bb3a0bf73c281e38f6f67c644391db6ed32ee93ea59a6d53707&req=dSEjFcF8lIVaXPMW3nq%2BgUEUCAtZlI0OymkGwvXwPbIdriySEnhYe5MnX9rH%0AEYoxZWV%2FwN%2FD9WGf%2BN6T8rLpu6U%3D%0A)

Klikk på Manage on-device site data

![](https://downloads.intercomcdn.com/i/o/1143829543/42d74782920e4a35a660e546/image.png?expires=1781092800&signature=772bcce3cf9b467dbc597b9d51e83558d486f87ddb35ea6b96af416fc21e8b5a&req=dSEjFcF8lIRbWvMW3nq%2BgURf0KbK%2BNuvBfcmFwNBFGl1BsOYkzIeKVHfYp9q%0Ax43X05BUHahlsi1ikzCV75TMgJk%3D%0A)

Dette er hva dine nettleser datainnstillinger ser ut som:

![](https://downloads.intercomcdn.com/i/o/1143829607/ca12dcb2003b5cb363d40567/image.png?expires=1781092800&signature=f3a187e05e4ba985f1ae0ec66d8fb2a99a1057a2881e8a657ddac3758f562e70&req=dSEjFcF8lIdfXvMW3nq%2BgckeVuXJSA5nST8uRqQYtlpUuNArxqJhicAjHiaF%0APs4KS9lyB2p5JX1IIKTovtvmSMA%3D%0A)

For å bruke Catenda Hub måt du minst tillate lagringen av data for hub.catenda.com under din sesjon.

Hvis du velger å slette data når alle nettleservindu lukkes vil din data være tilbakestilt hver gang du bruker Catenda.

## **Nettverkshastighet**

Kontroller kvaliteten til ditt nettverk å forholdet mellom Ned- og opplasting er rundt 1:10 eller over.

![](https://downloads.intercomcdn.com/i/o/748569163/86b6c411513b1d918f971664/5e52d40f-4227-418f-b23b-20fa30a307e2?expires=1781092800&signature=1ba0773f7dc7c9af736408f4089c2adccac66a67a0b7737730ea980132976063&req=cyQvE893nIdcFb4V1XW4gbNVrM1pna2WNERr2HdEoh49FtF8K3i%2F%2BKq6uCKu%0AYfEqJDh3SgD2pd%2FhWLATN81jAg%3D%3D%0A)

(dette er et eksempel, ikke et krav)

## **Proxyer og brannmur:**

Brukere som kobler på Catenda Hub gjennom en brannmur, proxy eller annen mellom tjeneste nå gi tilgang til følgende domener og porter for at applikasjonen skal fungere ordentlig.

### **Domener:**

(`\*` betyr DNS wildcard og `.` er domenenivåseparator, disse må ikke behandles som regexer)

- Catenda domener:
    - `catenda.com`
    - `\*.catenda.com`
        - `webviewer.catenda.com`
    - `\*.\*.catenda.com`

Vi anbvefaker at dy vryjer dette nye domene navnet.

Du burde ikke komme bort i problemer me flere under-domener som `\*.\*.\*.catenda.com` men hvis du gjør det kan det være letter å tillate alt fra `catenda.com`

**Vedlikeholdte domener**

De følgende domenene vil vedlikeholdes i nær framtid men vil ikke referes til i teknisk literatur.

- `bimsync.com`
- `\*.bimsync.com`
- `\*.\*.bimsync.com`

**Tjenester**

Catenda Hub bruker følgende tjenester:

- `\*.google-analytics.com`
- `\*.googletagmanager.com`
- `\*.intercom.io`
- `\*.intercomcdn.com`
- `\*.sentry.io`

**Pluginner**

Hvis du ønsker å bruke Catenda Hub gjennom en av våre pluginner er disse de eneste domenene du trenger å tillate gjennom brannmuren.

- For autentisering av pluginner og integrasjoner
    - `hub.catenda.com`
    - `api.catenda.com `
    - `bimsync.com`
    - `api.bimsync.com`
- For bruk av plugin
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
- For bruk av integration
    - Solibri BCF Live connector
        - `https://bcf.bimsync.com/`
        - `https://opencde.bimsync.com/`

## **Porter:**

**80:** Denne porten er valgfri men anbvefalt for best i-nettleser brukeropplevelse.

Protokoll: TCP (Bare for hub.catenda.com og [www.hub.catenda.com](http://www.hub.catenda.com))

Tjenester som forsøker å gjøre et forespørsel på 80 blir henvist til å gjøre det samme krypterete forespørselet på port 443.

**443:**

Protokoll: TCP + UDP All Catenda Hub trafikk er TLS-kryptert på denne porten.

UDP er valgfri men anbefalt for best brukeropplevelse etter som det tillater støttede nettlesere og andre tjenester til å ta i bruke fremskritt i HTTP-protokollen som HTTP/3 (tidligere QUIC) som vi ruller ut over hele platformen.
