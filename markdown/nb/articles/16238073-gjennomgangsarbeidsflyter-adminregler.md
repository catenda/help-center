# Gjennomgangsarbeidsflyter: Adminregler

> Veiledning for administratorer som detaljerer oppsettsregler, fleksible konfigurasjonsalternativer, parameterlåsing etter innsending, og hvordan endringer i prosjektkonfigurering påvirker aktive gjennomganger.

Gjennomgangsarbeidsflyter etablerer strukturerte vurderings- og valideringsprosesser for delte dokumentrevisjoner innenfor et prosjekt. Konfigurering av arbeidsflyter krever balansering av malregler for fremtidige vurderingsforespørsler med prosjektteamoppsett som driver aktive, pågående gjennomganger.

> **Merknad:** Bare prosjektadministratorer kan få tilgang til konfigurasjonsinnstillinger for arbeidsflyter, opprette nye gjennomgangsarbeidsflyter eller endre eksisterende arbeidsflytparametere.

## 1. **1. Hvordan prosjektendringer påvirker gjennomgangsarbeidsflyter**

Når en arbeidsflytmal endres eller prosjektkonfigurasjoner justeres (for eksempel å legge til eller fjerne teammedlemmer i prosjektinnstillinger), påvirker endringene fremtidige og pågående gjennomgangsforespørsler på ulike måter:

### 1.1 **1.1 Redigeringer av arbeitsflytmal**

Endringer gjort i en arbeidsflytmal (for eksempel å legge til innsendingsteam) gjelder **fremtidige** gjennomgangsforespørsler som opprettes etter oppdateringen. De omskriver ikke strukturen på aktive forespørsler som allerede er i gang.

### 1.2 **1.2 Oppdateringer av teammedlemskap**

Å legge til eller fjerne teammedlemmer i prosjektinnstillinger trer i kraft umiddelbart for **aktive, pågående** gjennomganger. Hvis et vurderingstrinn er stillestilt fordi et team er tomt, lar det å legge til en bruker i det teamet dem umiddelbart gå inn og gjenoppta vurderingen.

### 1.3 **1.3 Brutte avhengigheter**

Arkivering av en dokumentstatus, fjerning av et team, eller arkivering av en gjennomgangssakmal andre steder i prosjektinnstillinger kan forårsake valideringsfeil ved lagring av arbeidsflytoppdateringer eller stanse sakopprettelse på pågående gjennomganger.

## 2. **Oppsett før innsending (Initial opprettelse)**

Når en ny gjennomgangsarbeidsflyt opprettes for første gang, må alle grunnleggende parametere konfigureres før malen kan lagres og aktiveres.

### 2.1 **2.1 Obligatoriske felt og advarselbanner før innsending**

Hvis noe obligatorisk felt er ufullstending når du prøver å lagre en ny arbeitsflyt, viser systemet et advarselbanner før innsending øverst på siden og blokkerer malopprettelse. Obligatoriske felt omfatter:

- **2.1.1 Arbeitsflyttittel**
  Et unikt, beskrivende navn for arbeitsflytene.
- **2.1.2 Innsendingsteam**
  Minst ett prosjektteam tildelt til å starte gjennomgangsforespørsler.
- **2.1.3 Vurderingstrinn**
  Minst ett vurderingstrinn som inneholder et tildelt vurderingsteam og en varighet på minst **1 arbeidsdag**.
- **2.1.4 Endelig godkjenning**
  Et tildelt sluttgjennomgangsteam sammen med to aktive prosjektdokumentstatuser—en kartlagt for godkjente revisjoner og en for avslåtte revisjoner.

### 2.2 **2.2 Systemgrenser og teammedlemskapregler**

_2.2.1 Rørledningsgrenser_ En enkelt arbeitsflyt støtter opptil **10 sekvensielle vurderingstrinn** og totalt **20 vurderingsteam** på tvers av rørledningen.

_2.2.2 Teamvalg kontra medlemstilstedeværelse_ Under initial opprettelse validerer systemet at innsendingsteam, vurderingsteam og sluttgjennomgangsteam er valgt. Imidlertid **kontrollerer det ikke** om disse teamene inneholder faktiske medlemmer.

_2.2.3 Kjøringskrav og auto-godkjenning_ For å gjøre en gjennomgangsforespørsel gjennomførbar fra start til slutt:

- Minst ett innsendingsteammedlem må være tilstede i et tildelt innsendingsteam for å starte forespørselen.
- Minst ett vurderingsteammedlem må være tilstede i et tildelt vurderingsteam, med mindre auto-godkjenning er aktivert for det trinnet.
- Hvis auto-godkjenning er konfigurert, godkjenner og fremmer et trinn tildelt et tomt team automatisk når trinets forfallsdato nås.
- Hvis auto-godkjenning ikke er konfigurert, vil et tomt vurderingsteam stanse gjennomgangsforespørselen til et medlem legges til det teamet.
- Minst ett sluttgjennomgangsteammedlem må være tilstede for å presentere det endelige resultatet.

_2.2.4 Administratorrettigheter_ Prosjektadministratorer har ikke automatiske operative rettigheter. For å utføre handlinger under en gjennomgang, må en administrator være et eksplisitt medlem av det relevante teamet:

- **Innsendingsteam**
  Oppgitt til å starte en gjennomgangsforespørsel.
- **Vurderingsteam**
  Oppgitt til å angi eller sende inn en vurderingsvalidering.
- **Sluttgjennomgangsteam**
  Oppgitt til å presentere den endelige beslutningen og lukke gjennomgangen.

## 3. **3.** **Fleksible operasjoner (før og etter innsending)**

Visse operasjoner forblir fleksible og kan justeres under innledende oppsett eller oppdateres når som helst etter at en arbeitsflyt er aktiv. Disse fleksible operasjonene faller inn i to distinkte kategorier: **Arbeitsflytmalinnstillinger** (redigert direkte på siden for arbeitsflytoppsett) **Prosjektteammedlemskapshåndtering** (redigert på siden Prosjektteam på tvers av alle arbeitsflytroller).

### 3.1 **3.1** **Arbeitsflytmalendringer**

Disse innstillingene kan endres i arbeitsflytkonfigurasjonsmenyen når som helst, noe som direkte påvirker fremtidige gjennomgangsforespørsler:

_3.1.1 Innsendingsteam_ Administratorer kan legge til eller fjerne innsendingsteam etter innsending for å kontrollere hvilke prosjektteam som har tillatelse til å starte nye gjennomgangsforespørsler under denne arbeitsflyten.

_3.1.2 Gjennomgangssakmaler_ Gjennomgangssakmaler knyttet til spesifikke resultater (_Godkjent_, _Godkjent med kommentarer_, eller _Avslått_) kan legges til, oppdateres eller avkoblet når som helst for å kontrollere problemsporing under vurderinger.

### 3.2 **3.2** **Prosjektteammedlemskapshåndtering (gjelder alle teamtyper)**

Å legge til eller fjerne individuelle brukere skjer på **Prosjektteam**-siden og krever ikke redigering eller re-lagring av arbeitsflytemalen. Avgjørende er at medlemskapshåndtering gjelder **alle tre arbeitsflytteamtyper**, og påvirker direkte hvem som kan utføre handlinger:

_3.2.1 Innsendingsteam_ Å legge til eller fjerne medlemmer endrer hvem som kan velge arbeitsflyten for å starte nye gjennomgangsforespørsler.

_3.2.2 Vurderingsteam_ Å legge til eller fjerne medlemmer endrer hvem som kan få tilgang til aktive vurderingstrinn, legge til merknader/kommentarer og sende inn trinvalideringsindikasjoner.

_3.2.3 Sluttgjennomgangsteam_ Å legge til eller fjerne medlemmer endrer hvem som kan presentere den endelige beslutningen og lukke en aktiv gjennomgangsforespørsel.

## 4. **4.** **Regler etter innsending og parameterlåsing**

Når en arbeitsflytmal lagres og sendes inn for første gang, låses nøkkelstrukturparametere for å sikre konsistente vurderingsregler på tvers av gjennomgangsforespørsler.

### 4.1 **4.1 Låste kontra redigerbare parametere**

_4.1.1 Låste parametere_ Tidsinnstillinger, vurderingstrinn, tildelte vurderingsteam, trinvarigheter, auto-godkjenningsknapper, endelige godkjenningsteam og kartlagte sluttdokumentstatuser kan ikke endres etter innledende innsending.

_4.1.2 Redigerbare parametere_ Bare arbeitsflytetittelen, innsendingsteamtildelinger og koblede gjennomgangssakmaler forblir redigerbare etter innsending.

### 4.2 **4.2 Brutte eksterne avhengigheter og løsninger**

Lagring av **en hvilken som helst** redigeringen etter innsending av en eksisterende arbeitsflyt (for eksempel å oppdatere tittelen) utløser en full re-valideringskontroll på tvers av hele malen. Hvis et element som brukes i arbeitsflyten ble arkivert eller slettet i prosjektinnstillinger etter innledende opprettelse, mislykkes re-validering til problemet er løst.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 130px; padding: 8px;"><h3 id="h_5956ae53a6"><b>Avhengighetsproblem (blokkering)</b></h3></td><td style="background-color: #e3e7fa80; width: 244px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_9b11612daf"><b>Innvirkning og systematferd</b></h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_f245fc1acb"><b>Løsning</b></h3></td></tr><tr><td style="background-color: #00000000; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_aac48f326c"><b>Arkiverte dokumentstatuser</b></h3></td><td style="background-color: #00000000; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Det kartlagte statusfeltet vises tomt i arbeitsflytoppsettet. Publiserte dokumenter mottar den arkiverte statusen (vises gjennomstreget). Arbeitsflytoppdateringer blokkeres.</p></td><td style="background-color: #00000000; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Gjenopprett (gjør aktiv) statusen</b> i dokumentinnstillinger.<br/>Låste statuser kan ikke redigeres eller erstattes inne i arbeitsflyten etter innsending.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_c963d16fb5"><b>Slettede prosjektteam</b></h3></td><td style="background-color: #e8e8e880; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Et innsendingsteam, vurderingsteam eller endelig godkjenningsteam ble slettet på siden Prosjektteam.</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Innsendingsteam</b><br/>Rediger arbeitsflyten direkte for å tildele et nytt aktivt team.<br/>​</p><p><b>Vurderingsteam / sluttteam</b><br/>Låst. Hvis ingen team gjenstår i et trinn og auto-godkjenning er av, staller pågående gjennomganger for alltid. Arkiver arbeitsflyten, forkast dokumenter, og opprett en ny arbeitsflyt.</p></td></tr><tr><td style="background-color: #00000000; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_8d948d5649"><b>Arkiverte gjennomgangssakmaler</b></h3></td><td style="background-color: #00000000; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>En gjennomgangssakmal knyttet til et arbeitsflytresultat ble arkivert på siden sakmalene.</p><p></p></td><td style="background-color: #00000000; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Gjenopprett (gjør aktiv)</b> malen på siden sakmalene <b>ELLER</b> rediger arbeitsflyten direkte for å velge/legge til en ny aktiv erstatningsmal.</p></td></tr></tbody></table></div>

### 4.3 **4.3 Arkivering og gjenoppretting av arbeitsflyter**

_4.3.1 Arkivering av arbeitsflyter_ Skjuler den aktive arbeitsflyten fra opprettelsesmenyer slik at prosjektmedlemmer ikke kan velge den for nye forespørsler.

_4.3.2 Gjenoppretting av arbeitsflyter_ Gjør en arkivert arbeitsflyt aktiv igjen i opprettelsesmenyer for tildelte innsendingsteam.

## 5. **5.** **Innvirkning på pågående gjennomganger og team-livssykler**

Når prosjektinnstillinger eller teammedlemsskap endres mens gjennomgangsforespørsler aktivt er i gang, håndterer systemet tilgang, sakopprettelse og arbeitsflytfremskriding i henhold til spesifikke regler.

### 5.1 **Å legge til og fjerne teammedlemmer**

Prosjektmedlemmer kan legges til eller fjernes fra arbeitsflytteam på siden **Prosjektteam** når som helst uten å redigere arbeitsflytemalen selv.

_5.1.1 Innsendingsteammedlemmer_ Å legge til en bruker i et innsendingsteam lar dem opprette nye forespørsler fremover. Imidlertid gir innsendingsteammedlemskapet aldri delt synlighet for forespørsler opprettet av lagkamerater - tilgang til en sendt forespørsel forblir strengt personlig for den enkelte oppretteren.

_5.1.2 Vurderingsteammedlemmer_ Å legge til en bruker i et vurderingsteam gir dem umiddelbar tilgang til aktive gjennomgangsforespørsler som for tiden er på det vurderingstrinnet. Å fjerne alle medlemmer fra et vurderingsteam vil fryse pågående forespørsler på det trinnet til et nytt medlem legges til - med mindre **auto-godkjenning** er aktivert for det trinnet, i så fall vil forespørselen automatisk godkjenne og fremme når trinfristen passeres.

_5.1.3 Sluttgjennomgangsteammedlemmer_ Å legge til en bruker i et sluttgjennomgangsteam gir dem umiddelbar tilgang til å presentere endelige beslutninger om aktive forespørsler som når det endelige godkjenningstrinnet. Å fjerne alle medlemmer fra et sluttgjennomgangsteam fryser pågående forespørsler på det endelige trinnet til en bruker legges til (auto-godkjenning er ikke tilgjengelig for sluttgjennomgangstrinn).

### 5.2 **5.2** **Sletting av team fra prosjektinnstillinger**

Slettede prosjektteam kan ikke gjenopprettes. Hvis et team tildelt en arbeitsflyt slettes fra prosjektinnstillinger, avhenger den operative virkningen av teamets rolle i arbeitsflytlivssyklusen:

_5.2.1 Slettede innsendingsteam_ Innsendingsteam forblir redigerbare etter innsending. En administrator kan redigere arbeitsflytekonfigurasjonen direkte og tildele et nytt aktivt innsendingsteam.

_5.2.2 Slettede vurderingsteam_ Vurderingstrinn er låst etter innsending.

- **Hvis andre tildelte team gjenstår**
  Vurderingstrinnet fortsetter å fungere for de gjenværende teamene.
- **Hvis ingen team gjenstår og auto-godkjenning er PÅ**
  Trinnet godkjenner og fremmer automatisk når trinfristen passeres.
- **Hvis ingen team gjenstår og auto-godkjenning er AV**
  Pågående gjennomgangsforespørsler staller ubestemt på det vurderingstrinnet.

_5.2.3 Slettede sluttgjennomgangsteam_ Endelige godkjenningsteam er låst etter innsending, og auto-godkjenning er **ikke** tilgjengelig for sluttgjennomgangstrinn. Hvis alle sluttgjennomgangsteam slettes, staller pågående gjennomgangsforespørsler ubestemt.

_5.2.4 Anbefalt handling for stillestilte eller ufullstendige arbeitsflyter_ Når et vurderingstrinn staller med ingen gjenværende team (og auto-godkjenning er av), eller når alle sluttgjennomgangsteam slettes, er anbefalingen å arkivere den brutte gjennomgangsarbeitsflyten og forkaste alle dokumenter strengt fra åpne gjennomgangsforespørsler som følger denne spesifikke arbeitsflyten. Eventuelt kan en ny gjennomgangsarbeitsflyt opprettes hvis en erstatning er nødvendig.

### 5.3 **5.3** **Arkivering og omkonfigurering av gjennomgangssakmaler**

Gjennomgangssakmaler konfigureres separat for hvert beslutningsresultat (f.eks. _Godkjent_, _Godkjent med kommentarer_, eller _Avslått_). Systemet behandler endringer i gjennomgangssakmaler uavhengig per resultat:

_5.3.1 Resultatspesifikk isolasjon_ Arkivering eller endring av en gjennomgangssakmal for ett beslutningsresultat påvirker bare det spesifikke resultatet. Alle andre resultater med intakte gjennomgangssakmaler fortsetter å opprette saker som forventet.

_5.3.2 Arkivering av en koblet gjennomgangssakmal_ Hvis en gjennomgangssakmal tildelt et resultat arkiveres, vil pågående gjennomgangsforespørsler som følger den arbeitsflyten (og nye forespørsler sendt mens den er uavhengig) **ikke** generere saker hvis det resultatet velges.

_5.3.3 Gjenoppretting av en arkivert gjennomgangssakmal_ Gjenoppretting (gjøring av aktiv) av den opprinnelige gjennomgangssakmalen gjør automatisk sakopprettelse aktiv igjen i henhold til den malen på tvers av alle tilhørende gjennomgangsforespørsler.

_5.3.4 Konfigurering av en annen gjennomgangssakmal_ Hvis en administrator oppdaterer arbeitsflyten etter innsending for å tildele en _annen_ aktiv gjennomgangssakmal, vil pågående gjennomgangsforespørsler initiert før redigeringen **ikke** generere saker ved hjelp av den nye malen. Bare nye gjennomgangsforespørsler sendt etter omkonfigureringen genererer saker basert på den nylig tildelte malen.
