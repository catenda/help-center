# Modeller som dokumenter

Tidligere har det vært mulig å laste opp IFC-filer til to separate steder på Catenda Hub. Med funksjonen _modeller som dokumenter_ blir disse to plasseringene for modellfiler slått sammen til én smidig funksjon. Hvis du lager en modell i modellseksjonen, blir et dokument lenket og opprettet i dokumentseksjonen. Hvis du laster opp et IFC-dokument, kan du bruke handlingsknappen "lag modell" for å lenke og opprette en modell i modellseksjonen. Med denne funksjonen kan modeller i modellseksjonen håndteres som dokumenter, mens modeller i dokumentseksjonen kan håndteres akkurat som modeller.

## 1. **Før/Etter migrering - Hovedforskjeller**

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e8e8e880; width: 126px;"><h1 id="h_3632d3cc1b"></h1></td><td style="background-color: #e8e8e880; width: 262px;"><h2 class="intercom-align-center" id="h_2093155130"><b>Før</b></h2></td><td style="background-color: #e8e8e880; width: 248px;"><h2 class="intercom-align-center" id="h_d5cfcbcb2d"><b>Etter</b></h2></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Hovedatferd</b></p></td><td style="width: 262px;"><p>Modeller fantes kun i modellseksjonen. Brukeren måtte laste opp den samme IFC-filen til både dokumentseksjonen og modellseksjonen.</p></td><td style="width: 248px;"><p>Modeller blir opprettet fra IFC-filer lastet opp til dokumentseksjonen, hvis brukeren ber om det. IFC-filen og dens relaterte modell blir deretter lenket.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Brukergrensesnitt</b></p></td><td style="width: 262px;"><p><b>Annerledes</b> fra dokumentseksjonen og viser mindre informasjon, i hovedsak kun en liste over modeller.</p></td><td style="width: 248px;"><p><b>Det samme</b> som dokumentseksjonen: en tilpassbar tabell med relaterte metadata.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Tilgangsrettigheter</b></p></td><td style="width: 262px;"><p><b>Kunne ikke brukes</b> på modeller</p></td><td style="width: 248px;"><p><b>Kan brukes</b> på modeller fra deres tilknyttede dokument i dokumentseksjonen</p></td></tr></tbody></table></div>

## 2. **Kjent men annerledes**

Nå som de to seksjonen har blitt lenket, er det viktig å merke seg at det fortsatt er noen viktige forskjeller mellom modell- og dokumentseksjonene. I modellseksjonen kan du se alle modell-dokumenter samlet i en liste. Her vil du se dine modell-dokumenter på en måte som ligner hvordan de vil bli brukt i 3D-viseren. I dokumentseksjonen kan du se dokument-modeller i dokumentstrukturen din. Her vil du se dine dokument-modeller på en måte som ligner hvordan de vil bli brukt i ditt felles datamiljø. Alle modeller er lenket til hver sitt eget dokument, og funksjoner fra begge seksjoner kan brukes i både modell- og dokumentseksjonen.

## 3. **Endringer i modellseksjonen**

Med modeller som dokumenter har modellseksjonen endret utseende. I stedet for å se menyoppføringer for hver modell, vil de nå vises i en søkbar tabell.

I modellseksjonen kan du finne følgende endringer:

### 3.1 **Modelltabell**

Den nye modelltabellen kan se omtrent slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/01-model-table.png)

### 3.2 **Kolonner**

Modelllisten har kolonner som viser det meste av informasjonen du trenger å vite om modellene dine.

_Navn_ Navnet på modell-dokumentet Modellnavnet er også navnet du vil se i revisjonsvelgeren i 3D-visningen.

_Dokumentnavn_ Navnet på dokument-modellen i dokumentseksjonen

_Revisjonnavn_ Navnet på den siste revisjonen

### 3.3 **Tilgangskontroll**

Hvis en modell har blitt begrenset for deg i dokumentseksjonen, ser du den ikke i dokumentseksjonen, modelltabellen eller i revisjonsvelgeren.

### 3.4 **Velge tabellelementer**

Med modelltabellen kan du nå velge en rekke modeller ved å holde shift. Du kan også legge til eller fjerne modeller fra valget ditt ved å holde Ctrl.

### 3.5 **Handlingsknapper**

Tidligere var den eneste handlingen du kunne utføre på valgte modeller å åpne dem i 3D. Nå kan du laste ned, fjerne og åpne 2D-visningen av de valgte modellene dine. Hvis du sletter en modell som er tilkoblet et dokument, mister dokumentet modeltilkoblingen, men dokumentet forblir i dokumentseksjonen.

### 3.6 **Kontroller tilgang til dokument-modeller**

_Oppretter en modell-dokument_ Hvis du lager en modell med knappen Opprett modell i modellseksjonen, blir du bedt om å velge hvor du ønsker at det linkede dokument-modellen skal havne i dokumentseksjonen. I dialogboksen Opprett modell kan du også gi modellen et navn. Det resulterende linkede dokument-modellen vil ha det samme som modellen når den blir opprettet. Catenda Hub vil huske mappen du valgte sist og velger den automatisk neste gang du oppretter en modell-dokument.

Hvis prosjektet ditt ble påbegynt uten modeller som dokumenter, har en mappe kalt "Modeller" dukket opp i mappstrukturen din. Modelsmappen som vises inneholder alle dokument-modeller som er lenket til modell-dokumenter i modellseksjonen. Dokument-modeller kan flyttes ut av denne mappen til hvor som helst i dokumentseksjonen du har tilgang. Dokument-modeller i Modeller-mappen kan også slettes (og gjenopprettes) hvis ønsket. Dokument-modellene trenger ikke å være i mappen, og modelsmappen kan slettes hvis det er nødvendig.

_Oppretter en modell-revisjon_ For å kunne laste opp nye revisjoner til en modell trenger du nå minst skrivetilgang til dokumentmodellen. Nye revisjoner til modellen kan legges til dokumentet og omvendt.

> **Merknad:** Revisjonskommentarer har blitt deaktivert og kan nå eventuelt aktiveres med [egendefinerte felt på revisjoner](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents).

_Laster ned en modell-revisjon_ Du må ha minst lesetilgang til dokument-modellen for å kunne laste ned modellen.

### 3.7 **Informasjonsmeny til høyre**

En informasjonsmeny til høyre er tilgjengelig hvis en modell er valgt.

_Dokumentfelt_ I denne menyen vil du se modellinformasjonen din samt et grått felt som lenkes til dokument-modellen i dokumentseksjonen som er lenket til denne modell-dokumentet. Klikk på dokumentfeltet for å åpne dokument-modellen som er lenket til denne modellen.

_Modelletiketter_ Du kan nå også legge til etiketter til modellene dine her.

_Modellstatus_ Hvis statuser har blitt konfigurert i dokumentinnstillinger, kan du konfigurere en status for modellen din her.

_Modelltransformasjon_ Hvis du har åpnet denne modellen i 3D, kan du konfigurere modelltransformasjon her.

## 4. **Endringer i dokumentseksjonen**

Selv om de visuelle endringene ikke er like tydelige som i modellseksjonen, er det noen få ting som vil endres i dokumentseksjonen når modeller som dokumenter aktiveres. Slik kan dokument-modellene se ut i dokumentseksjonen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/02-documents-section-changes.png)

I dokumentseksjonen kan du finne følgende endringer:

### 4.1 **Modelfilter**

Så snart du har noen modeller i modellseksjonen, vil du se et modelfilter dukke opp i filtermenyen din. Med dette filteret kan du vise/skjule dokument-modeller som har blitt opprettet.

### 4.2 **Kolonner**

_Ikon_ Du vil kunne skille et dokument-modell fra et vanlig dokument ved modellbadgen i nederste høyre hjørne av dokument-modellikon.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/03-columns.png)

_Navn_ Navnet på dokumentet

_Modellnavn_ Navnet på modellen. Hvis IFC-dokumentet ditt ikke har blitt lenket til en modell, vil du se en opprettingsmodellknapp her.

_Revisjonnavn_ Navnet på den siste revisjonen i modellen

_Viser_ En kolonne med knapper for å åpne hver enkelt dokument-modell i 3D-viseren. Det er bare mulig å åpne dokument-modeller i 3D-viseren hvis dokumentet har blitt lenket til en modell.

### 4.3 **Handlingsknapper**

Last ned, slett eller last 2D/3D-visninger av valgte modeller i den respektive viseren ved å velge en eller flere modeller.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-9e345595c719.png" width="310"/>    <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-959af958f499.png" width="310"/>

Dette betyr at du kan slette flere modeller på en gang i stedet for en om gangen som før. Hvis du sletter et dokument som er tilkoblet en modell, må du godkjenne en advarsel om at modellen som er tilkoblet dokumentet også blir slettet.

> **Merknad:** Dette betyr at du kan slette en modell uten å miste dataene. (Slettede dokumenter kan gjenopprettes)

### 4.4 **Kontroller tilgang til modell-dokumenter**

_Oppretter dokument-modeller_ For å kunne laste opp nye revisjoner til en modell trenger du nå minst skrivetilgang til dokumentmodellen. Du gjør dette ved å opprette en modell i handlingsmenyen for et dokument. Etter at du gjør dette, vil du se dokumentet som en modell i modellseksjonen. Modell-dokumentet i modellseksjonen vil ha samme navn som dokument-modellen, selv om disse kan endres separat senere mens de forblir lenket. Nye revisjoner til modellen kan legges til som revisjoner til dokumentet og omvendt.

> **Merknad:** Dette betyr at du kan opprette modeller fra flere IFC-filer samtidig i stedet for å måtte laste dem opp en om gangen

_Laster opp revisjoner til dokument-modeller_ Du må ha minst skrivetilgang til dokument-modellen for å kunne laste opp nye revisjoner til modellen. Dette betyr at du kan bruke multopplastingsfunksjonen til å laste opp IFC-filer til flere dokument-modeller samtidig

_Laster ned dokument-modeller_ Du må ha minst lesetilgang til dokument-modellen for å kunne laste ned modellen. Dette betyr at du kan konfigurere tilgang for å tillate nedlasting av separate modeller i stedet for bare alle eller ingen modeller.

### 4.5 **Oppdagbarhet**

Dokument-modeller kan nå finnes i dokumentseksjonen som alle andre dokumenter.

- Dokument-modeller kan struktureres i mapper for å gjøre det enklere å navigere til riktig sett med modeller.
- Etiketter kan legges til dokument-modeller for å finne alle dokument-modeller som tilhører en type.
- [Egendefinerte felt kan legges til mapper](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) der dokumenter lastes opp for å søke på metadataverdier knyttet til hver dokument-modell
- [Egendefinerte felt kan legges til mapper](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) der dokumenter lastes opp for å kunne legge til informasjon i hver revisjon i hver dokument-modell.

Se [her](https://support.catenda.com/en/articles/8542598-structuring-documents#h_7838a63c73) for forslag på hvordan du strukturerer dokument-modellene dine slik at de er enkle å finne.

### 4.6 **Godkjenn delte IFC-filer**

IFC-filer kan nå lastes opp som delte revisjoner slik at de kan gå gjennom en godkjenningsprosess før de blir publisert.

### 4.7 **Navnekonvensjon med dokument-modeller**

Navn i dokumentseksjonen inkluderer ofte komprimerte forkortelser for å holde dokumentnavnet kort mens det vises noe informasjon om hva dokumentet handler om. Navnet på dokument-modellen kan derfor være annerledes fra navnet på modell-dokumentet for å holde det i tråd med de andre dokumentene i dokumentseksjonen, mens det samtidig opprettholder et leselig navn å bruke i 3D-viseren i modellseksjonen. Dokumentnavnet på dokument-modellen er det navnet som blir gjenkjent når du laster opp dokumenter til dokumentseksjonen. Hvis navnet er likt eller det samme som dokumentet, blir en ny revisjon automatisk opprettet akkurat som med andre dokumenter.

Fordi dokument-modeller oppfører seg på samme måte som vanlige modeller, er det nå mulig å bruke navnekonvensjonen med dokument-modeller for å sikre at deltakerne i prosjektet ditt gir dokumentet riktig navn ved opplasting.
