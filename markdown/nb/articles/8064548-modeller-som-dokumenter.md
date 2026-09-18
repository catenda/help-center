# Modeller som dokumenter

Tidligere har det vært mulig å laste opp IFC-filer til to separate steder på Catenda Hub. Med funksjonen _modeller som dokumenter_ vil disse to stedene for modellfiler bli slått sammen til én sømløs funksjon. Hvis du oppretter en modell i modelldelen, blir et dokument lenket og opprettet i dokumentdelen. Hvis du laster opp et IFC-dokument, kan du bruke handlingen "lag modell" til å lenke og opprette en modell i modelldelen. Med denne funksjonen kan modeller i modelldelen håndteres som dokumenter mens modeller i dokumentdelen kan håndteres akkurat som modeller.

## 1. **Før/Etter migrering – hovedforskjeller**

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e8e8e880; width: 126px; padding: 8px;"><h1 id="h_3632d3cc1b"></h1></td><td style="background-color: #e8e8e880; width: 262px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_2093155130"><b>Før</b></h2></td><td style="background-color: #e8e8e880; width: 248px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_d5cfcbcb2d"><b>Etter</b></h2></td></tr><tr><td style="background-color: #e8e8e880; width: 126px; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right"><b>Hovedatferd</b></p></td><td style="width: 262px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Modeller fantes bare i modelldelen. Brukeren måtte laste opp samme IFC-fil til både dokumentdelen og modelldelen.</p></td><td style="width: 248px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Modeller opprettes fra IFC-filer som lastes opp til dokumentdelen, hvis brukeren ber om det. IFC-filen og dens relaterte modell blir deretter lenket.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right"><b>Brukergrensesnitt</b></p></td><td style="width: 262px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Annerledes</b> fra dokumentdelen og viste mindre informasjon, i utgangspunktet bare en liste over modeller.</p></td><td style="width: 248px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Det samme</b> som dokumentdelen: en tilpassbar tabell med relaterte metadata.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right"><b>Tilgangsrettigheter</b></p></td><td style="width: 262px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Kunne ikke brukes</b> på modeller</p></td><td style="width: 248px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Kan brukes</b> på modeller fra deres relaterte dokument i dokumentdelen</p></td></tr></tbody></table></div>

## 2. **Kjent men annerledes**

Nå som de to delene har blitt lenket, er det viktig å merke seg at det fortsatt finnes noen viktige forskjeller mellom modellene og dokumentdelene. I modelldelen vil du kunne se alle modell-dokumenter samlet i en liste. Her vil du se dine modell-dokumenter på en måte som ligner på hvordan de vil bli brukt i 3D-visningen. I dokumentdelen vil du kunne se dokument-modeller i dokumentstrukturen din. Her vil du se dine dokument-modeller på en måte som ligner på hvordan de vil bli brukt i ditt felles datamiljø. Alle modeller er lenket til hvert sitt dokument, og funksjoner fra begge delene kan brukes i både modelldelen og dokumentdelen.

## 3. **Endringer i modelldelen**

Med modeller som dokumenter har modelldelen endret utseende. I stedet for å se menyelementer for hver modell, vil de nå vises i en søkbar tabell.

I modelldelen vil du kunne finne følgende endringer:

### 3.1 **Modelltabell**

Den nye modelltabellen kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/01-model-table.png)

### 3.2 **Kolonner**

Modellisten har kolonner som viser det meste av informasjonen du trenger å vite om modellene dine.

_Navn_ Namnet på modell-dokumentet. Modellnavnet er også navnet du vil se i revisjonsvelgeren i 3D-visningen.

_Dokumentnavn_ Navnet på dokument-modellen i dokumentdelen

_Revisjonsnavnet_ Navnet på den siste revisjonen

### 3.3 **Tilgangskontroll**

Hvis en modell har blitt begrenset for deg i dokumentdelen, vil du verken se den i dokumentdelen, modelltabellen eller i revisjonsvelgeren.

### 3.4 **Velge tabellelementer**

Med modelltabellen kan du nå velge flere modeller ved å holde Shift. Du kan også legge til eller fjerne modeller fra valget ved å holde Ctrl.

### 3.5 **Handlingsknapper**

Tidligere var den eneste handlingen du kunne utføre på valgte modeller å åpne disse modellene i 3D. Nå kan du laste ned, fjerne og åpne 2D-visningen av de valgte modellene dine. Hvis du sletter en modell som er koblet til et dokument, mister dokumentet modeltilkoblingen, men dokumentet forblir i dokumentdelen.

### 3.6 **Kontroller tilgang til dokument-modeller**

_Opprette en modell-dokument_ Hvis du oppretter en modell med knappen for å opprette modell i modelldelen, blir du bedt om å velge hvor du vil at det lenket dokument-modellen skal ende opp i dokumentdelen. I dialogboksen for å opprette modell vil du også kunne gi modellen et navn. Det resulterende lenket dokument-modellen vil ha det samme som modellen når den opprettes. Catenda Hub vil huske mappen du valgte sist og velger den automatisk neste gang du oppretter en modell-dokument.

Hvis prosjektet ditt startet uten modeller som dokumenter, vil en mappe kalt "Modeller" ha dukket opp i mappestrukturen din. Modellmappen som vises inneholder alle dokument-modeller som er lenket til modell-dokumenter i modelldelen. Dokument-modeller kan flyttes ut av denne mappen til hvor som helst i dokumentdelen du har tilgang til. Dokument-modeller i modellmappen kan også slettes (og gjenopprettes) hvis ønskelig. Dokument-modellene trenger ikke å være i mappen, og modellmappen kan slettes om nødvendig.

_Opprett en modellrevisjon_ For å kunne laste opp nye revisjoner til en modell trenger du nå minst skrivetilgang til dokument-modellen. Nye revisjoner til modellen kan legges til dokumentet og omvendt.

> **Merk:** Revisjonskommentarer har blitt deaktivert og kan nå valgfritt aktiveres med [egendefinerte felt på revisjoner](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents).

_Laste ned en modellrevisjon_ Du trenger minst lesetilgang til dokument-modellen for å kunne laste ned modellen.

### 3.7 **Meny for informasjon til høyre**

En meny for informasjon til høyre vil være tilgjengelig hvis en modell er valgt.

_Dokumentfelt_ I denne menyen vil du se modellinformasjonen din samt et grått felt som lenker til dokument-modellen i dokumentdelen som er lenket til denne modell-dokumenten. Klikk på dokumentfeltet for å åpne dokument-modellen som er lenket til denne modellen.

_Modellmerkelapper_ Du kan nå også legge til merkelapper i modellene dine her.

_Modellstatus_ Hvis statusar har blitt konfigurert i dokumentinnstillinger, vil du kunne konfigurere en status for modellen din her.

_Modelltransformasjon_ Hvis du har åpnet denne modellen i 3D, vil du kunne konfigurere modelltransformasjon her.

## 4. **Endringer i dokumentdelen**

Selv om de visuelle endringene ikke er like åpenbare som i modelldelen, er det noen få ting som vil endres i dokumentdelen når modeller som dokumenter aktiveres. Slik kan dokument-modellene se ut i dokumentdelen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/02-documents-section-changes.png)

I dokumentdelen vil du kunne finne følgende endringer:

### 4.1 **Modellfilter**

Så snart du har modeller i modelldelen, vil du se et modellfilter dukke opp i filtrermenyen din. Med dette filteret kan du vise/skjule dokument-modeller som har blitt opprettet.

### 4.2 **Kolonner**

_Ikon_ Du vil kunne skille en dokument-modell fra et vanlig dokument ved modellmerket på nedre høyre side av dokument-modellikonen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/03-columns.png)

_Navn_ Navnet på dokumentet

_Modellnavn_ Navnet på modellen. Hvis IFC-dokumentet ditt ikke har blitt lenket til en modell, vil du se en knapp for å opprette modell her.

_Revisjonsnavnet_ Navnet på den siste revisjonen i modellen

_Viser_ En kolonne med knapper for å åpne hver enkelt dokument-modell i 3D-visningen. Det er bare mulig å åpne dokument-modeller i 3D-visningen hvis dokumentet har blitt lenket til en modell.

### 4.3 **Handlingsknapper**

Last ned, slett eller åpne 2D/3D-visningene av valgte modeller i den respektive visningen ved å velge en eller flere modeller.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-9e345595c719.png" width="310"/>    <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-959af958f499.png" width="310"/>

Dette betyr at du kan slette flere modeller på en gang i stedet for en-og-en som før. Hvis du sletter et dokument som er koblet til en modell, må du godkjenne en advarsel om at modellen som er koblet til dokumentet også vil bli slettet.

> **Merk:** Dette betyr at du kan slette en modell uten å miste dataene. (Slettede dokumenter kan gjenopprettes)

### 4.4 **Kontroller tilgang til modell-dokumenter**

_Opprette dokument-modeller_ For å kunne laste opp nye revisjoner til en modell trenger du nå minst skrivetilgang til dokument-modellen. Du gjør dette ved å opprette en modell i handlingsmenyen til et dokument. Etter at du gjør dette, vil du se dokumentet som en modell i modelldelen. Modell-dokumentet i modelldelen vil ha det samme navnet som dokument-modellen, selv om disse kan endres senere mens de forblir lenket. Nye revisjoner til modellen kan legges til som revisjoner til dokumentet og omvendt.

> **Merk:** Dette betyr at du kan opprette modeller fra flere IFC-filer samtidig i stedet for å måtte laste dem opp en etter en

_Opplasting av revisjoner til dokument-modeller_ Du trenger minst skrivetilgang til dokument-modellen for å kunne laste opp nye revisjoner til modellen. Dette betyr at du kan bruke multi-upload-funksjonen til å laste opp IFC-filer til flere dokument-modeller samtidig

_Laste ned dokument-modeller_ Du trenger minst lesetilgang til dokument-modellen for å kunne laste ned modellen. Dette betyr at du kan konfigurere tilgang for å tillate nedlasting av separate modeller i stedet for bare alt eller ingenting.

### 4.5 **Synlighet**

Dokument-modeller kan nå finnes i dokumentdelen som ethvert annet dokument.

- Dokument-modeller kan organiseres i mapper for å gjøre det lettere å navigere til riktig sett med modeller.
- Merkelapper kan legges til dokument-modeller for å finne alle dokument-modeller som tilhører én type.
- [Egendefinerte felt kan legges til i mapper](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) der dokumenter lastes opp for å søke på metadataverdier knyttet til hver dokument-modell
- [Egendefinerte felt kan legges til i mapper](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) der dokumenter lastes opp for å kunne legge til informasjon til hver revisjon i hver dokument-modell.

Se [her](https://support.catenda.com/en/articles/8542598-structuring-documents#h_7838a63c73) for forslag på hvordan du kan organisere dokument-modellene dine slik at de er lette å finne.

### 4.6 **Godkjenn delte IFC-filer**

IFC-filer kan nå lastes opp som delte revisjoner slik at de kan gjennomgå en godkjenningsprosess før de publiseres.

### 4.7 **Navnekonvensjon med dokument-modeller**

Namen i dokumentdelen inkluderer ofte komprimerte forkortelser for å holde dokumentnavnet kort og samtidig vise litt informasjon om hva dokumentet handler om. Navnet på dokument-modellen kan derfor være annerledes enn navnet på modell-dokumentet for å holde det i tråd med de andre dokumentene i dokumentdelen, samtidig som du opprettholder et lett leselig navn til bruk i 3D-visningen i modelldelen. Dokumentnavnet på dokument-modellen vil være navnet som gjenkjennes når dokumenter lastes opp til dokumentdelen. Hvis navnet er likt eller identisk med dokumentet, opprettes det automatisk en ny revisjon akkurat som med andre dokumenter.

Fordi dokument-modeller oppfører seg på samme måte som vanlige modeller, er det nå mulig å bruke navnekonvensjonen med dokument-modeller for å sikre at deltakerne i prosjektet ditt gir det riktige navnet på dokumentet når de laster det opp.
