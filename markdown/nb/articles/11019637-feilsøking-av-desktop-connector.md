# Feilsøking av Desktop Connector

## 1. **Navnekonvensjon**

Hvis en navnekonvensjon er aktivert på opplastingsmappen eller en overordnet mappe til opplastingsmappen, må det lokale filnavnet følge konvensjonen for at opplastingen skal gjennomføres. Hvis filnavnet ikke følger konvensjonen, vises følgende feil.

_`<Filename> samsvarer ikke med navnekonvensjon`_

Vennligst last opp filen manuelt via nettleseren for å se hvilke deler av filnavnet som mangler.

## 2. **Serverprosjektplassering**

Flere feil kan oppstå når du åpner serverprosjektplasseringen.

### 2.1 **Prosjektplassering tom**

For å synkronisere dine lokale filer til et prosjekt må du ha minst én mappe i dokumentseksjonen av prosjektet på Catenda Hub.

### 2.2 **Prosjekt ikke funnet**

Når Desktop Connector åpnes for første gang, lastes alle prosjekter som brukeren har tilgang til. Uten å oppdatere vises de samme prosjektene neste gang. Hvis brukeren har mistet tilgang til prosjektet, vises følgende melding når du forsøker å angi serverplassering i en opplastings- eller nedlastingsoppgave for prosjektet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/01-project-not-found.png)

Vennligst spør en prosjektadministrator om tilgang til prosjektet. For å finne ut hvem du skal kontakte for prosjekttilgang, kan du kontakte Catenda-support.

## 3. **Dokumentutseende**

### 3.1 **Mappeplassering**

Dokumentnavn kan være begrenset med en navnekonvensjon i Catenda. Mapper kan ikke være begrenset. Uten bruk av en navnekonvensjon kan dokumenter med ethvert navn lastes opp. I dette tilfellet kan det hende at Catenda ikke kunne registrere filtypen til dokumentet. Mapper med ethvert navn kan opprettes. Det kan derfor være at Desktop Connector støter på problemer med tegn i navn som er reservert for Windows-funksjoner.

Typiske problemer oppstår med følgende tegn: `/` - Skråstrek fremover `\` - Skråstrek bakover Disse tegnene brukes i filstigarkitekturen i Windows, noe som fører til at dokumentet havner på feil sted.

Se her for en omfattende liste over hva som er reservert i Windows: [https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file](https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file)

### 3.2 **Feil dokument- eller mappenavn**

Dokumentnavn kan være begrenset med en navnekonvensjon i Catenda. Mapper kan ikke være begrenset. Uten bruk av en navnekonvensjon kan dokumenter med ethvert navn lastes opp. I dette tilfellet kan det hende at Catenda ikke kunne registrere filtypen til dokumentet. Mapper med ethvert navn kan opprettes.

Det kan derfor være at Desktop Connector støter på problemer med tegn i navn som er reservert for Windows-funksjoner.

Typiske problemer oppstår med følgende tegn: `.` - Periode

Siden mapper og filer som ender med en periode ikke er tillatt i Windows, fjernes perioden på slutten av mappen eller filen i dokumentet som opprettes fra en nedlastingsoppgave. Ved opplasting fjernes perioden i prosessen med å finne riktig mappe å laste opp til, slik at det nedlastede dokumentet havner på rett sted ved to-veis synkronisering.

- Mellomrom

I Catenda er det mulig å manuelt legge til mellomrom på slutten av et dokument- eller mappenavn, mens mellomrom på slutten av dokument- og mappenavn fjernes i Windows. Hvis det inkluderes mellomrom på Catenda, er navnet på den nedlastede mappen forskjellig fra navnet på mappen i Catenda som kan inneholde mellomrom. Når en opplastingsoppgave opprettes for den samme mappen, vil en ny mappe bli opprettet fordi fil- eller mappenavnet i Windows ikke har mellomrom på slutten.

## 4. **Ingen opplasting eller nedlasting**

### 4.1 **Dokumentet finnes allerede**

Når importsystemet ikke kan behandle en gjenstand som ble opprettet tidligere, oppstår følgende feil.

Desktop Connector `Dokumentet finnes allerede (kode: 25)`

Loggfil

```
<Message number>|<Date/Time>|ERROR|1|BimRequestProviderService|Call API error status code Conflict reason: {"error":{"code":25,"message":"Document already exists"}}.url: https://api.bimsync.com/v2/projects/<ProjectGUID>/libraries/<LibraryGUID>/items? | Data: {"parentId":"<LibraryItemGUID>","name":"<Name>","document":{"type":"<Type>","filename":"<Filename>"}} 
```

Spesifikt kan dette skje når du forsøker å laste opp en mappe med tittelen "`A`" for andre gang hvor en mappe med den tittelen allerede finnes. Det anbefales å endre hver lokale mappe med navnet "A" til noe som "A\_". På denne måten vil oppgaven ikke støte på problemer. Etter at opplastingsoppgaven er ferdig, endrer du den synkroniserte versjonen tilbake til "A" på Catenda slik at begge sidene forblir den samme.

### 4.2 **Ikke alle mapper er nedlastet**

I selve oppgaven kan du se følgende:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/02-not-all-folders-have-been-downloaded.png)

`Ikke alle mapper er nedlastet, klikk for å vise feil.`

Klikk [her](https://support.catenda.com/en/articles/13772277-desktop-connector-troubleshooting-not-all-folders-have-been-downloaded) for å lese mer om hva problemet kunne være med denne feilen.

## 5. **Siste revisjon trukket tilbake**

Siste revisjon for et av dokumentene har blitt trukket tilbake. I dette tilfellet er det ingen feilmelding i loggfilen.

## 6. **Samtidig synkronisering**

For at Desktop Connector skal kunne hente data fra et dokument for å laste opp eller oppdatere et dokument med nedlastede data, trenger den tilgang til dokumentet. Hvis dokumentet er i bruk av en annen prosess, kan den ikke få tilgang til dokumentet. Hvis dokumentet er i bruk, kan følgende feil vises:

Desktop Connector `Prosessen har ikke tilgang til filen '<File path>' fordi den brukes av en annen prosess.`

Loggfil

```
<Message number>|<Date/Time>|ERROR|1|ExceptionHandleExtension|Some error happen --> System.IO.IOException: The process cannot access the file '<File path>' because it is being used by another process.
```

Prosesser som kan ha filer i bruk, inkluderer: En annen oppgave fra Desktop Connector selv Filsynkroniseringstjenester som Dropbox, OneDrive eller Google Drive Andre CDE-synkroniseringsverktøy. Programmer som har filen åpen for redigering.

Hvis dokumentet er i bruk, stoppes oppgaven og vil ikke fortsette hvis den ikke kan få tilgang til en av filene. Hvis flere oppgaver er planlagt, vil den prøve igjen til neste planlagte tid.

## 7. **Aktivitetsovervåking**

### 7.1 **Oppgave startet**

Oppgaver som er manuelt startet ved å klikke på Last opp/Last ned nå i oppgaven, viser en status for Last opp eller Last ned så snart oppgaven er startet. For både oppgaver som er manuelt startet og oppgaver som er startet etter tidsplan, vises en melding som ser slik ut i loggfilen når en oppgave starter:

Loggfil `<Message number>|<Date/time>|INFO|1|LoggingExtension|start logging`

### 7.2 **Oppgave kjører**

Oppgaver som er manuelt startet ved å klikke på Last opp/Last ned nå i oppgaven, viser en status for Last opp eller Last ned så lenge oppgaven kjører. For både oppgaver som er manuelt startet og oppgaver som er startet etter tidsplan, kan tilstanden som oppgaver som kjører er i, ses ved å overvåke nettverksutnyttelsen av programmet.

_Innledende oppstartsfase_ En Desktop Connector-oppgave er i innledende oppstartsfase når den bruker mellom 1 kilobyte per sekund og 1 megabyte per sekund. I løpet av denne fasen er nettverksutnyttelsen av oppgaven minimal.

Nedlastingsoppgave Under innledende oppstartsfase sjekkes dokumenter på serverplasseringen mot de lokale filene for å se om det finnes noen serverfiler som har endret seg og som en ny revisjon skal lastes ned for, eller om det finnes nye filer på serversiden som skal lastes ned til det lokale systemet.

Opplastingsoppgave Under innledende oppstartsfase sjekkes dokumenter på serverplasseringen mot de lokale filene for å se om det finnes noen lokale filer som har endret seg og som en ny revisjon skal lastes opp for, eller om det finnes nye lokale filer som skal lastes opp til Catenda.

_Aktiv fase_ En Desktop Connector-oppgave er i aktiv fase når den bruker mer enn 1 megabyte per sekund. I løpet av denne fasen kan nettverksutnyttelsen av oppgaven ha en effekt på resten av systemet.

Nedlastingsoppgave I løpet av den aktive fasen laster Desktop Connector aktivt ned fil for fil fra Catenda til det lokale systemet.

Opplastingsoppgave I løpet av den aktive fasen laster Desktop Connector aktivt opp fil for fil fra det lokale systemet til Catenda.

### 7.3 **Oppgave stoppet**

Oppgaver som kjøres manuelt ved å klikke på Last opp/Last ned nå i oppgaven, viser en statusmelding innenfor oppgaven når oppgaven stoppes hvis enten når oppgaven er ferdig eller når en feil har oppstått.

_Oppgave ferdig_ Den eneste måten å se om oppgaver er ferdig på er å kjøre oppgaven manuelt. Klikk på Last opp/Last ned nå innenfor oppgaven for å gjøre det. Når oppgaven er ferdig, vises en melding om at alle dokumenter er lastet opp eller ned i oppgaven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/03-task-halted.png)

> **Merk:** Det er ingen meldinger i loggfilen for ferdige oppgaver. Den eneste måten å se om oppgaver som er startet etter tidsplan er stoppet på, er ved å sjekke nettverksutnyttelsen av programmet.

_En feil oppstod_ En mer detaljert beskrivelse av feil som har oppstått, kan ses ved å sjekke loggfilen for eventuelle nylige feil.

_Nettverksutnyttelse_ Den eneste måten å se om oppgaver som er startet etter tidsplan er stoppet på, er ved å sjekke nettverksutnyttelsen av programmet. Hvis Desktop Connector har brukt mindre enn 1 kilobyte per sekund i over 2 minutter, har oppgaver som kjørte sannsynligvis blitt stoppet og vil ikke starte igjen. For oppgaver som er planlagt å gjentas, startes en ny oppgave hvis Desktop Connector kjører på den neste datoen og klokkeslettet oppgaven er planlagt til å begynne.

## 8. **Tilkobling mellom koblingen og Catenda**

### 8.1 **Tilkobling ved oppgavestart**

Hvis det er et problem med internettilkoblingen, startes ikke opplastings- eller nedlastingsoppgaven automatisk på nytt og kjøres igjen til neste planlagte tid. Det kan også startes manuelt ved å gå til oppgaven og klikke på opplastings- eller nedlastingsknappen.

_Ingen tilkobling_ Hvis det ikke finnes internettilkobling når du starter en opplastings- eller nedlastingsoppgave, vises følgende feil i opplastings- eller nedlastingsoppgaven.

`Ingen slik vert er kjent`

_Tilkobling tapt under oppgavestart_ Hvis tilkoblingen til internett gikk tapt eller timet ut når du forsøkte å koble til Catenda-serverne, vises følgende feil:

`SSL-tilkoblingen kunne ikke etableres`

_Brukt tilkoblingsmetode avhenger av foretrukket metode tilgjengelig ved oppgavestart_ Når en oppgave startes, opprettes en tilkobling med den foretrukne internettilkoblingsmetoden. Hvis for eksempel en kablet tilkobling og en WiFi-tilkobling er tilgjengelig når en oppgave kjøres, foretrekkes vanligvis den kablede tilkoblingen. Hvis bare en WiFi-tilkobling er tilgjengelig når en oppgave startes og en kablet tilkobling kobles til mens den kjører, fortsetter koblingen å bruke den innledende tilkoblingen så lenge den er tilgjengelig og bytter ikke til en foretrukket tilkobling som senere blir tilgjengelig.

### 8.2 **Tilkobling under oppgave - Tilkobling til internett**

_Internettilkobling ikke lenger tilgjengelig uten reserve_ Hvis det bare var en tilkobling tilgjengelig da oppgaven begynte, eller hvis det ikke var noen tilkobling tilgjengelig i det hele tatt (f.eks. Flymodus), kan følgende feil oppstå.

`En feil oppstod under sending av forespørselen.`

_Internettilkobling ikke lenger tilgjengelig med reserve_ Hvis det var flere tilkoblinger tilgjengelig da oppgaven begynte og tilkoblingen som ble brukt gikk tapt, vil koblingen forsøke å bytte til en av de andre tilgjengelige tilkoblingene. Under denne bytting kan følgende feil oppstå:

`Feil under kopiering av innhold til en strøm`

### 8.3 **Tilkobling under oppgave - Desktop Connector sesjonstimeout**

Catenda Desktop Connector har en hardkodet sesjonsbegrensning på 10 minutter. Dette betyr ikke at en oppgave vil timeout etter 10 minutter siden Desktop Connector ofte fungerer med flere korte økter av gangen. Store filer som punktskyer der opptil 25 GB kan godtas på en gang, kan føre til at en sesjon tar lengre tid enn normalt og kan timeout hvis den ikke lastes opp innen 10 minutters grensen.

`Timeout på 600 sekunder forløper`

Kontakt støtte i denne situasjonen. Det finnes en Beta-versjon tilgjengelig etter forespørsel som kan hjelpe med dette. Med Beta-versjonen økes denne grensen litt, men selv med betaversjonen kan den timeout, men i stedet etter 15 minutter.

`Timeout på 900 sekunder forløper`

### 8.4 **Tilkobling under oppgave - Tilkobling til Catenda**

Avhengig av hastigheten på tilkoblingen både på opplastings- eller nedlastingssiden eller på Catenda-siden kan det ta kortere eller lengre tid å laste opp filer. Hvis oppgaven tar for lang tid, kan tilkoblingen timeout.

_Catenda timeout_ Hvis overføringen har tatt for lang tid, vil den timeout og følgende feil vil vises:

`En tilkoblingsforsøk mislyktes fordi den tilkoblede parten ikke svarte ordentlig etter en tid, eller etablert tilkobling mislyktes fordi tilkoblet vert kunne ikke reagere. (api.bimsync.com:443)`

Kontakt støtte i denne situasjonen. Det finnes en Beta-versjon tilgjengelig etter forespørsel som kan hjelpe med dette.

_Catenda Service utilgjengelig_ Hvis Catenda API midlertidig ikke kan motta forespørsler på brøkdelen av sekundet Desktop Connector forsøker å nå den, vises følgende melding.

Desktop Connector `HTTP FEIL 503 Service Utilgjengelig`

Loggfil

```
<Message number>|<Date/Time>|ERROR|1|BimRequestProviderService|Call API error status code ServiceUnavailable reason: <html><head><meta http-equiv="Content-Type" content="text/html;charset=ISO-8859-1"/><title>Error 503 Service Unavailable</title></head><body><h2>HTTP ERROR 503 Service Unavailable</h2><table><tr><th>URI:</th><td>/v2/projects/10005fce182e49cb91342571746cf1fc/libraries/9a90887d954a444c8ed45695707b2fbd/items</td></tr><tr><th>STATUS:</th><td>503</td></tr><tr><th>MESSAGE:</th><td>Service Unavailable</td></tr><tr><th>SERVLET:</th><td>-</td></tr></table>
```

Dette skyldes ofte at servere er overbelastet og mange brukere forsøker å sende forespørsler samtidig.

_Gateway timeout_ En gateway timeout betyr ofte at Catenda API kjører jevnt og at den innledende forespørselen ble mottatt ordentlig. Tjenesten som skulle håndtere denne forespørselen svarte imidlertid ikke i tide.

Desktop Connector `504 Gateway Time-Out` Loggfil

```
<Message number>|<Date/Time>|ERROR|1|BimRequestProviderService|Call API error status code GatewayTimeout reason: <html><head><title>504 Gateway Time-out</title></head><body><center><h1>504 Gateway Time-out</h1></center></body></html>
```

Dette kan indikere at Catenda mottar forespørsler ordentlig, men at serveren som behandler forespørslene midlertidig er utilgjengelig. Dette kan noen ganger skje når ikke nok maskiner er tilgjengelige, hvoretter flere vil starte automatisk, men dette kan ta litt tid.

_Tilgangstoken utløpt_ Catenda-tilgangstokens må oppdateres etter en time. Når Desktop Connector navigeres, er dette vanligvis ikke et problem da tokenet oppdateres automatisk, men når en oppgave startes som tar lengre tid enn en time, kan tilgangstokenet som ble brukt for oppgaven, timeout mens oppgaven pågår. Når dette skjer, vises følgende feil i Desktop Connector. For oppgaver som tar lengre tid enn en time, starter du oppgaven på nytt eller venter på neste planlagte oppgave for å gjøre det gjenstående arbeidet.

Desktop Connector `Unntak av typen 'BimsyncApp.Exceptions.BimAuthenticatorException' ble kastet.`

Loggfil

```
<Message number>|<Date/Time>|ERROR|1|BimRequestProviderService|Call API error status code Unauthorized reason: {"error":{"code":12,"message":"Access token has expired"}}.url: 
```

## 9. **Denne enheten er for øyeblikket i bruk**

Når du laster ned fra eller laster opp til en ekstern harddisk, gir Windows en feil som sier at enheten for øyeblikket er i bruk hvis den forsøkes frakoblet.

## 10. **Mapperettigheter**

For mapper som befinner seg på stasjonen der Windows er installert, kreves riktige mapperettigheter. Høyreklikk mappen du prøver å laste ned til og tillat de rette rettighetene.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/04-folder-permissions.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/05-folder-permissions.png)

I dette tilfellet gir loggfilen følgende feil:

`Tilgang til stien '<Selected local folder path> undermappe <Path within local folder>' er nektet`

### 10.1 **Tilgang nektet**

Selv om en mappe i Windows kan åpnes, kan Windows håndheve en "Ingen-skriving-opp"-policy. Desktop Connector lar deg velge denne mappen, men når oppgaven kjøres, vises følgende melding:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/06-permission-denied.png)

I dette tilfellet er Desktop Connector blokkert fra skriving, uavhengig av brukerens "Full kontroll"-rettigheter.

Sletting av denne mappen krever at brukeren gir administratorrettigheter.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/07-permission-denied.png)

I noen situasjoner kan mappen fremdeles åpnes, mens i andre kan følgende melding vises:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/08-permission-denied.png)

Selv ved fortsetting kan følgende melding vises:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/09-permission-denied.png)

Hvis du klikker på Last ned likevel, lastes filene ned, men de kan ikke lastes ned til den angitte mappen ettersom mappen er begrenset.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/10-permission-denied.png)

Desktop Connector `Status: Omdirigering, klikk for å vise nedlastede filer`

Loggfil `Tilgang til stien '<Path>' er nektet`

Klikk på Vis nedlastede filer for å åpne plasseringen der filene ble nedlastet.
