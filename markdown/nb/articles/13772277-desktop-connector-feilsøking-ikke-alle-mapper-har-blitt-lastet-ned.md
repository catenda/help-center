# Desktop Connector feilsøking - Ikke alle mapper har blitt lastet ned

I denne artikkelen finner du informasjon om en spesifikk feil som oppstår når du bruker [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector). Se [her](https://app.intercom.com/a/apps/areracg3/knowledge-hub/all-content?activeContentId=11844906&activeContentType=article&editorMode=view&native_content=false) for andre feilsøkingsproblemer med Desktop Connector.

I selve oppgaven kan du se følgende:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/01-intro.png)

`Ikke alle mapper har blitt lastet ned, klikk for å vise feil.`

## 1. **Tegn som ikke støttes**

I dette tilfellet vil loggfilen gi følgende feil:

`Syntaksen for filnavn, mappenavn eller volumetikett er feil.`

Dokumentnavn kan begrenses med en navnekonvensjon i Catenda. Mapper kan ikke begrenses. Uten bruk av en navnekonvensjon kan dokumenter med hvilket som helst navn lastes opp. I dette tilfellet har Catenda kanskje ikke kunnet registrere filtypen for dokumentet. Mapper med hvilket som helst navn kan opprettes. Det kan derfor være at Desktop Connector prøver å opprette en fil eller mappe med et tegn som ikke er tillatt i en bane i Windows.

Typiske problemer oppstår med følgende tegn: `<` - mindre enn `>` - større enn `:` - kolon `"` - anførselstegn `|` - loddrett strek eller pipe `?` - spørsmålstegn `*` - stjerne

Hvis du vil finne en omfattende liste over hva som er reservert i Windows, se her: [https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file](https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file)

## 2. **Manglende mappe eller nettverksbane**

I dette tilfellet vil loggfilen gi følgende feil:

`Feil: Nettverksbanen ble ikke funnet. : '<path>'`

I denne situasjonen mislykkes overføringen umiddelbart. Dette skjer fordi programmet prøver å nå en mappe som ikke lenger er tilgjengelig. Fordi "banen" er helt ødelagt, kan programmet ikke engang begynne nedlastingen. Det er tre hovedgrunner til at mappen din har blitt en "blindvei":

### 2.1 **1. Den manglende mappen (mest vanlig)**

Den lokale mappen som ble valgt tidligere, har blitt flyttet, omdøpt eller slettet. Når du går til plasseringen av mappen i Filutforsker, er mappen ikke der. Desktop Connector forsøker å lagre filen din, finner "ingenting" og stopper.

### 2.2 **2. Den brutte "symbolske lenken" (den skjulte omdirigeringen)**

En symbolsk lenke ser ut som en normal mappe, men fungerer som en permanent "veipost" som omdirigerer Windows til et annet sted (som en kontorserver). Når du prøver å åpne den, vises følgende feil i et popupvindu:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/02-2-the-broken-symbolic-link-the-hidden-redirect.png)

`Plasseringen er ikke tilgjengelig... Nettverksbanen ble ikke funnet.`

_Hvordan skille dem:_ Som .lnk-filer vil symbolske lenker ha den lille blå "snarveipilen" i nedre venstre hjørne av mappeikonet, eller høyreklikk på snarveien og velg Egenskaper.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/03-2-the-broken-symbolic-link-the-hidden-redirect.png)

I kategorien Generelt er feltene navn og mål nedtonet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/04-2-the-broken-symbolic-link-the-hidden-redirect.png)

_Hvorfor det mislykkes_ "Veiposter" er på datamaskinen din, men destinasjonen (som en `Z:`-stasjon eller server) er frakoblet.

### 2.3 **3. Den brutte Windows-snarveien (.lnk-fil)**

En standard Windows-snarvei er en liten fil som "peker" til en mappe andre steder. Disse kan være lenker til en mappe på din egen harddisk eller en mappe på en fjern kontorserver.

_Hvordan skille dem:_ Som symbolske lenker vil både mappe- og stasjonsnarveier ha den lille blå "snarveipilen" i nedre venstre hjørne av mappeikonet, eller høyreklikk på snarveien og velg Egenskaper.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/05-3-the-broken-windows-shortcut-lnk-file.png)

I kategorien Generelt må du se på målfeltet: _Lokal snarvei_ Målet begynner med en stasjonsbokstav (f.eks. `C:\Users\...` eller `D:\Data`).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/06-3-the-broken-windows-shortcut-lnk-file.png)

_Nettverkssnarvei_ Målet begynner med en serverstasjon (f.eks. `\\ServerName\Folder`) eller en kartlagt nettverksstasjonsbokstav (f.eks. `Z:\ProjectData`).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/07-3-the-broken-windows-shortcut-lnk-file.png)

Ulike oppførelser når du dobbeltklikker Windows håndterer en "brute" lokal snarvei mye raskere enn en "brute" nettverkssnarvei.

_Lokal snarvei (feilen "Slettet"):_ Hvis mappen på datamaskinen din ble slettet, vet Windows det umiddelbart. Når snarveien dobbeltklikkes, vises følgende feil umiddelbart:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/08-3-the-broken-windows-shortcut-lnk-file.png)

_`Elementet som denne snarveien refererer til, er endret, flyttet eller slettet.`_

_Nettverkssnarvei (feilen "Henging"):_ Hvis snarveien peker til en kontorserver og du er offline (eller uten VPN), vet ikke Windows at destinasjonen mangler med en gang. Det vil prøve å "finne" serveren på nettverket først. Musemarkøren din kan bli til en lassingkrets, og vinduet kan "henges" eller fryse i 30–60 sekunder før det endelig vises:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/09-3-the-broken-windows-shortcut-lnk-file.png)

_`Stasjonen eller nettverkstilkoblingen som snarveien refererer til, er ikke tilgjengelig.`_

Hvis Desktop Connector får beskjed om å bruke en av disse snarveiene mens målet mangler eller nettverket er nede, vil programmet til slutt "time out" mens det venter på at Windows skal finne banen. Fordi Desktop Connector ikke kan finne et gyldig mål å begynne arbeidet med, stopper det og rapporterer feilen.

### 2.4 **Hvordan fikse det**

_Identifiser frakoblingen_ Prøv å åpne målmappen i Windows Filutforsker. Hvis målmappen mangler, må enten en ny mappe opprettes på det stedet, eller en annen mappe skal velges i Desktop Connector.

_Koble til igjen eller velg på nytt_ Hvis en feil "Nettverksbane ikke funnet" eller "Stasjon utilgjengelig" vises, bekrefter du tilkoblingen til nettverksbanen eller stasjonen. Gå til "Denne PC-en" og sikre at nettverksstasjonene dine (som `Z:`) er aktive. Kontroller at eksterne USB-enheter eller harddisker er riktig tilkoblet. Hvis de har en rød X, dobbeltklikker du dem for å koble til igjen. Hvis nettverksstasjonen ikke er aktiv og du vet hvilket nettverk stasjonen er på, kobler du til nettverket igjen enten ved å koble i en kabel, knytte til via Wi-Fi, eller når du bruker et VPN, sjekker du at VPN-en er aktiv. Hvis stasjonen ikke lenger er tilgjengelig, velger du en annen målmappe i Desktop Connector som er tilgjengelig enten på den lokale datamaskinen eller på nettverket.

_Slett/gi nytt navn og opprett på nytt_ Hvis en lokal mappe eller snarvei forblir "fast" (du ser den, men kan ikke åpne den) selv etter en omstart: Gi den problematiske mappen eller snarveifilene nytt navn (f.eks. gi nytt navn til `ProjectData` til `ProjectData_OLD`) eller slett den. Opprett en helt ny, standard mappe med samme navn. Start overføringen på nytt. Desktop Connector vil oppdage den nye, sunne mappen og gjenoppta normal drift.

_Hvorfor ble ingen midlertidig mappe opprettet i stedet for den manglende mappen?_ I andre situasjoner oppretter Desktop Connector en mappe med `_restricted` lagt til navnet når noe går galt. Det er imidlertid en teknisk forskjell i hvordan Windows håndterer "manglende" plasseringer:

Mappen `_restricted` opprettes bare hvis mappen er "fysisk" der, men "låst" (som en dørterskel til et rom som er boltet igjen). I så fall kan programmet se døren og bestemmer seg for å bygge en ny (`_restricted`) ved siden av den.

I tilfelle av den manglende banen er det annerledes. Mappen er ikke lenger der, eller "veiposter" (symbolsk lenke) som ble valgt, peker på et tomt sted. For programmet er det ikke bare låst – hele "rommet" mangler fra bygningen. Fordi det ikke er noen "dørterskel" til å begynne med, kan programmet ikke opprette en `_restricted`-versjon og må stoppe.

## 3. **Manglende monteringspunkt**

I dette tilfellet vil loggfilen gi følgende feil:

`Feil: Kunne ikke finne en del av banen '<path>'.`

Hvis mappen ikke kan åpnes, prøver Windows å følge "veiposter" til en nettverksplass, og følgende feil vises:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/10-missing-mount-point.png)

`<Path> er ikke tilgjengelig.`
`Nettverksbanen ble ikke funnet`

I denne situasjonen oppretter Desktop Connector automatisk en ny mappe med "_restricted" lagt til navnet (f.eks. `ProjectData_restricted`).

Dette skjer når en mappe på datamaskinen faktisk er et "monteringspunkt" (en dørterskel) til en annen stasjon. Eksempler på andre stasjoner kan omfatte:

- USB-pinne,
- Ekstern harddisk
- Nettverksvolum som er frakoblet for øyeblikket.

Windows "husker" at mappen eksisterer, men fordi den fysiske stasjonen mangler, blir mappen en "Spøkelses-mappe". Desktop Connector oppdager at mappen er der, men kan ikke skrive til den. For å forhindre at dataene dine går tapt, opprettes en skygge-mappe med suffiks `_restricted` slik at filene dine har et trygt sted å lande.

Her er noen typiske situasjoner der dette kan skje:

- Mappen ble kartlagt til en stasjon (som `D:`) som ble trukket ut.
- Mappen peker på en nettverksdeling (som `Z:`) som er offline eller krever et VPN.
- En skytjeneste (Dropbox, OneDrive eller andre verktøy for samarbeid synkroniseringstjenester) opprettet en "plassholder"-mappe som ikke er aktiv for øyeblikket.
- Et sikkerhetsverktøy for virksomheter "skjermer" mappen fra å bli endret av tredjepartsapper.

For å kontrollere om mappen er en "Spøkelses-mappe", høyreklikker du på mappen og velger Egenskaper.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/11-missing-mount-point.png)

Se på typfeltet i kategorien Generelt: En normal mappe sier "Filmappe", mens en spøkelses-mappe sier "Montert volum".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/12-missing-mount-point.png)

Når du dobbeltklikker på den monterte mappen, vises følgende feil umiddelbart:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/13-missing-mount-point.png)

_`Plasseringen er ikke tilgjengelig`_ eller

_`Nettverksbanen ble ikke funnet`_ `<Path> er ikke tilgjengelig som så lenken er brute`

### 3.1 **Hvordan fikse det**

Opprett mappen på nytt manuelt Hvis mappen forblir "fast" selv etter en omstart:

1. Gi den problematiske mappen nytt navn (f.eks. gi nytt navn til `ProjectData` til `ProjectData_OLD`).
1. Opprett en helt ny mappe med det opprinnelige navnet (`ProjectData`).
1. Desktop Connector vil oppdage den nye, sunne mappen og gjenoppta normal drift uten suffiks `_restricted`.

_Koble til maskinvaren eller nettverket på nytt_ Gå til "Denne PC-en" og sikre at nettverksstasjonene dine (som `Z:`) er aktive. Kontroller at eksterne USB-enheter eller harddisker er riktig tilkoblet. Hvis de har en rød X, dobbeltklikker du dem for å koble til igjen. Hvis nettverksstasjonen ikke er aktiv og du vet hvilket nettverk stasjonen er på, kobler du til nettverket igjen enten ved å koble i en kabel, knytte til via Wi-Fi, eller når du bruker et VPN, sjekker du at VPN-en er aktiv. Hvis stasjonen ikke lenger er tilgjengelig, velger du en annen målmappe i Desktop Connector som er tilgjengelig enten på den lokale datamaskinen eller på nettverket.

_Slett/gi nytt navn og opprett på nytt_ Hvis en lokal mappe eller snarvei forblir "fast" (du ser den, men kan ikke åpne den) selv etter en omstart: Gi den problematiske mappen eller snarveifilene nytt navn (f.eks. gi nytt navn til `ProjectData` til `ProjectData_OLD`) eller slett den. Opprett en helt ny mappe med det opprinnelige navnet (`ProjectData`). Start overføringen på nytt. Desktop Connector vil oppdage den nye, sunne mappen og gjenoppta normal drift uten suffiks `_restricted`.
