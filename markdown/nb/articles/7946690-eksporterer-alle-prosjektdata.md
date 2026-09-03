# Eksporterer alle prosjektdata

> Oversikt over eksportmetoder for prosjektdata, dokumenter, modeller og saker i Catenda Hub. Alternativer: Desktop Connector-synkronisering, PDF/A-rapporter, revisjon av tilgangstillatelser og automatiske skysikkerhetskopier til AWS S3 eller Azure Blob.

Catenda Hub tilbyr fleksible eksportmetoder tilpasset ulike prosjektbehov, fra daglige nedlastinger til automatisert bedriftsarkivering. Avhengig av spesifikke prosjektkrav, er det mulig å synkronisere store mappestrukturer ved hjelp av Desktop Connector, generere egendefinerte dokument leveringsjekklister og PDF/A-arkiver via rapportsiden, eller dokumentere prosjekttilgangstillatelser for revisjonsspor. For organisasjoner som krever kontinuerlige sky-til-sky-sikkerhetskopier, gir Catenda Data Export automatiserte overføringer direkte til AWS S3 eller Azure Blob-lagring.

## 1. **Hvorfor eksportere**

Prosjekteiere og prosjektdeltakere må ofte vedlikeholde lokale kopier av prosjektdokumentasjon under og etter prosjektets livssyklus.

### 1.1 **Dataoverføring og faseskifter**

Prosjektdata kan være nødvendig på ulike prosjektmilepæler:

_Faseskifter_ Overganger mellom planlegging, design og konstruksjon krever ofte utvinning av dataspøkelser, spesielt hvis prosjekter settes på hold eller overføres til nye parter.

_Offentlige forespørsler_ Formelle overføringer til myndigheter kreves ofte under eller etter prosjektets slutt.

_Anbudsrunde_ Forberedelse av dokumentoverføringspakker til anbudsrunder.

### 1.2 **Uavhengig datalagring og tilgangsbeskyttelse**

Eksportering er ikke begrenset til prosjektets slutt. Prosjektmedlemmer som ikke eier hovedprosjektdataene, trenger ofte sine egne kopier for å sikre kontinuerlig tilgang til sitt arbeid.

Prosjektmedlemmer blir ikke alltid informert på forhånd om når prosjekttilgangen vil avsluttes, og tilgangen kan noen ganger tilbakekalles tidligere enn forventet. Fordi tilgangen kan gå tapt uten varsel, er det kritisk å konfigurere **planlagte, gjentakende eksporter**, slik som med **Catenda Data Export** eller **Catenda Desktop Connector**. Disse gjentakende verktøyene sikrer at prosjektmedlemmer beholder en lokal eller skysikkerhetskopi opp til den siste planlagte kjøringen før tilgangen går tapt.

### 1.3 **Dataarkivering og samsvar**

Forskrifter og industristandarder krever ofte at ansvarlige parter lagrer prosjektpostulater i lange perioder, ofte over år eller tiår. Systemdokumentasjon, produktpostulater og overholdelsesfiler kan være nødvendig å lagre på bedriftsservere eller utpekte oppbevaringsplasser.

### 1.4 **Prosjektavslutning**

Når et aktivt prosjekt avsluttes eller en lisensperiode går ut, sikrer Catenda at prosjektdata forblir lagret trygt. Selv om prosjekttilgangen avsluttes, er data fortsatt gjennomfører på Catenda-servere i opptil tre år.

### 1.5 **Froset arkivalternativ**

Et arkivalternativ gjør det mulig for prosjekter å forbli tilgjengelige som frosne, skrivebeskyttede oppbevaringsplasser for valgte medlemmer.

## 2. **Standard eksportalternativer**

Disse innebygde eksportverktøyene er tilgjengelige direkte innenfor standardgrensesnittet for alle autoriserte prosjektdeltakere.

### 2.1 **Eksporterer modeller**

Fordi hver modell i Catenda er knyttet til et dokument i dokumentdelen, gjelder standard dokumenteksportalternativer også for modeller. I tillegg er dedikerte eksportalternativer tilgjengelige spesielt for modeller:

_Valgt modellenedlasting_ Velg en eller flere modeller på [modellersiden](https://support.catenda.com/en/articles/4670286-models-page) og bruk nedlastingshandlingen til å trekke ut deres nyeste revisjoner.

_Individuell revisjonsnedlasting_ Velg en modell på [modellersiden](https://support.catenda.com/en/articles/4670286-models-page) og bruk nedlastingsknappen ved siden av hver revisjon i høyre informasjonspanel. Dette gir en effektiv måte å laste ned bestemte revisjoner direkte uten å måtte laste hele [modellinnholdssiden](https://support.catenda.com/en/articles/4670270-model-contents-page). Alternativt kan individuelle revisjoner også lastes ned direkte fra innholdssiden for en modell.

_Avansert modelleksport_ Få tilgang til [modeleksportsiden](https://support.catenda.com/en/articles/4670280-model-export-page) for å pakke valgte revisjoner på tvers av flere modeller til en enkelt nedlastbar ZIP-fil. Denne metoden inkluderer avanserte alternativer for å forbedre de eksporterte modelfilene ved å bake inn merker, brukerdefinerte egenskaper eller biblioteksinformasjon.

### 2.2 **Eksporterer saker (3 måter)**

Sakdata kan utvinnes ved hjelp av tre primære formater via [utvekslingssaker](https://support.catenda.com/en/articles/4670289-exchange-topics), avhengig av hvordan informasjonen blir sett, analysert eller lagret:

_BCF (BIM Collaboration Format)_ En åpen standard utformet for å fange og overføre saksinformasjon som strengt overholder den offisielle BCF-spesifikasjonen, inkludert individuelle saksopprettelsestidsstempler. Dette formatet garanterer bred plattformfellesdrift, noe som gjør det ideelt for å åpne på nytt, redigere eller utveksle saksdata smidig med annen BCF-kompatibel programvare. For generelle langsiktige dokumentoppbevaringsplasser der direkte filforhåndsvisninger trengs, er PDF- eller Excel-formater vanligvis foretrukket.

_Excel_ Eksporterer sakparametere til et regnearkformat for filtrering, sortering og datamanipulering. Dette formatet gir strukturerte rader og kolonner som er ideelle for valg og kopiering av data, og Excel-filer kan lett forhåndsvises innenfor de fleste arkiveringsplattformer. For arkiveringsformål foretrekkes PDF-eksporten generelt fremfor Excel fordi den inneholder mer informasjon.

_PDF_ Genererer en ren, lesbar sammendragsrapport i standard PDF-format (v1.4) tilgjengelig uten spesialisert programvare (se [eksporterer saker til PDF](https://support.catenda.com/en/articles/9784934-exporting-topics-to-pdf)). Standard PDF-eksporter inkluderer et konsolidert nedlastingstidsstempel for formell myndighetrapportering og arkivering, med mer informasjon enn en Excel-eksport. Mens basiseksporten genererer en standard PDF (v1.4) fil, som mange arkiveringsystemer automatisk konverterer til PDF/A ved opplasting for langsiktig forhåndsvisning, er direkte eksport til native PDF/A-1, PDF/A-2 og PDF/A-3-formater også tilgjengelig via opt-in [Rapportsiden](https://support.catenda.com/en/articles/12303098-reports-page).

### 2.3 **Eksporterer dokumenter og samlinger**

_Sats- og mappenedlastinger_ Velg individuelle mapper, bestemte dokumentbatcher eller alle synlige tabeilelementer på en gang for å generere en nedlastbar ZIP-arkiv. Det anbefales å laste ned i håndterbare batcher ved å velge bestemte undermapper eller målrettede filgrupper for jevne overføringer når du arbeider med store datasett.

- **Publisert fane**
  Utstreker den siste publiserte revisjonen for hvert valgt dokument.
- **Arbeidsromsfane**
  Utstreker den siste delte revisjonen for hvert valgt dokument (krever "Vis delte revisjoner"-tillatelse). Merk at eldre utkastrevisjoner ikke kan lastes ned i batch til en ZIP-arkiv og lastes ned individuelt.

_Individuell revisjonsnedlasting_ Velg et dokument på [dokumentersiden](https://support.catenda.com/en/articles/8204673-documents-page) og klikk på nedlastingsknappen ved siden av hver revisjon som vises i høyre informasjonsmeny. Dette er en enklere måte å laste ned individuelle eller historiske revisjoner på fordi dokumentforhåndsvisningssiden ikke trenger å lastes inn, slik at du kan velge et annet dokument i tabellen og laste ned revisjonene i høyremeny uten å måtte åpne en ny forhåndsvisningsside.

_Offentlige samlinger_ Bruk [samlinger](https://support.catenda.com/en/articles/6344318-collections-page) til å opprette offentlige lenker for valgte dokumentdelsett, slik at eksterne parter kan laste ned filer uten å kreve en Catenda-konto. Merk at bare publiserte revisjoner kan legges til samlinger.

_Slettede filer_ Søk etter "slettet" i dokumentsøkelinjen for å finne og eksportere tidligere slettede dokumenter. Husk at dette filteret er språkspesifikt og vil tilsvare begrepet for "slettet" i gjeldende språkinnstillinger.

### 2.4 **Desktop connector (Automatisert lokal sikkerhetskopi)**

[Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) gjør det mulig å bakgrunnssynkronisere for periodisk å laste ned nye dokumentrevisjoner direkte til en lokal stasjon. I motsetning til satseksporten, ankommer nedlastede dokumenter direkte på systemet ditt som rå, ukomprimerte filer uten at det kreves manuell arkivekstraksjon.

_Planlagte og øyeblikkelige sikkerhetskopier_ Oppgaver kan planlegges til å kjøre automatisk med regelmessige intervaller eller utføres on-demand, noe som sikrer at prosjektmedlemmer bevarer en oppdatert lokal kopi av dokumenter selv om prosjekttilgangen uventet tilbakekalles.

_Direkte API-overføringer_ Overfører store datasett betydelig raskere enn weblesernedlastinger ved å utnytte direkte API-forbindelser uten leserbegrensninger eller overhead.

_Hierarkialternativer_ Laster ned valgte mappestrukturer med komplett hierarki intakt, eller trekker ut individuelt valgte filer direkte som en flat liste til den utpekte lokale mappen.

### 2.5 **Medlemtilgang og aktivitetslogger**

_Saklister_ Dokumentelementbordtilgangstillatelser ved hjelp av to tilgjengelige visninger:

- **Brukerspesifikk tilgangsvisning**
  Vis individuelle brukertilgangsnivåer direkte fra høyre informasjonsmeny for en saksliste eller valgt sak.
  ​_Tilgang påkrevd:_ lesетilgang til sakslistten
- **Fullstendig teamkonfigurasjon**
  Fang opp skjermbildet av de komplette teamnivatillatelsesinnstillingene innenfor tilgangen til sakslistten.
  ​_Tilgang påkrevd:_ Full tilgang til sakslistten eller prosjektadministrator

_Dokument- og modelltilgang_ Eksporter [tilgangsoversikten](https://support.catenda.com/en/articles/6660820-document-access-overview-page) for å registrere tillatelser for medlemmer og team. Tilgang påkrevd: Prosjektadministrator. Fordi hver modell er knyttet til et dokument i dokumentdelen, styres tilgangstillatelser for modeller av de underliggende dokumenttillatelsene og registreres ved hjelp av samme dokumenttilgangsoversikt eller tillatelseamenyer.

_Dokument- og modellrevisjonens tilgang_ Vis tillatelser fra [høyre meny for en dokumentrevisjon](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision-revision-info) og fang opp skjermbildet etter behov.

_Prosjektomfattende handlingstillatelser_ Dokumenter prosjektomfattende tillatelser på [prosjektinnstillingssiden](https://support.catenda.com/en/articles/4670273-project-settings-page) (for eksempel oppretting av saklister, invitasjon av nye medlemmer, konfigurering av dokumentstatuser og opprettelse eller fjerning av modeller) ved hjelp av to tilgjengelige visninger:

- **Brukerspesifikk tilgangsvisning**
  Prosjektmedlemmer kan utvide hver meny under tilgangskontroll for å se hvilke individuelle brukere som har tillatelse til å utføre hver handling.
- **Fullstendig konfigurasjon**
  Administratorer kan åpne redigeringsdialogen for tilgang for å vise og administrere teamnivatillatelelseskonfigurasjoner.
  ​_Tilgang påkrevd:_ Prosjektadministrator

_Brukerprofiler og medlemsdetaljer_ Informasjon om prosjektmedlemmer og team er tilgjengelig for utvinning eller dokumentasjon, inkludert:

- Brukernavn og e-postadresser (se [egendefinert medlemsinformasjon](https://www.google.com/search?q=https://support.catenda.com/en/articles/11769670-custom-member-information%23h_c15463ee3f)).
- Teammedlemskap, tildelte saker, opplastede modellrevisjoner og tillatelseinnstillinger (fanget via [medlemssiden](https://www.google.com/search?q=https://support.catenda.com/en/articles/4670291-members-page) eller [teamsiden](https://www.google.com/search?q=https://support.catenda.com/en/articles/4670291-members-page)).

### 2.6 **Varslinger**

Fang opp varslingssider via skjermbildet fra [prosjektvarslinger-siden](https://support.catenda.com/en/articles/4670295-project-notifications-page), ved hjelp av [grensefilter](https://support.catenda.com/en/articles/8304417-filtering-on-the-notifications-page) for å maksimere synlige elementer per side.

Konfigurer en dedikert administratorkonto med [prosjektspesifikke varslingsinnstillinger](https://support.catenda.com/en/articles/4670262-project-specific-notification-settings) aktivert for e-postsammendrag for å opprettholde søkbare varslingslogger.

### 2.7 **Rapportsiden (Innmeldingsfunksjon)**

_Innmeldings aktivering_ Rapportsiden er en innmeldingsfunksjon som kan forespørres som aktiv for aktuelle prosjekter. Selv om ingen ekstra betaling kreves for å bruke dette verktøyet, må prosjekteieren godta å aktivere det på prosjektet, noe som betyr at det ikke er aktivt som standard i mange prosjekter. Merk at nye prosjekter opprettet fra malprosjekter der rapporter er aktivert, aktiverer ikke automatisk denne funksjonen.

_Malbasert administrasjon_ Når den er aktivert, kan prosjektadministratorer bruke [rapportmalsiden](https://support.catenda.com/en/articles/12380837-report-templates-page) for å konfigurere egendefinerte rapportmaler og generere formaterte eksporter for valgte dokumenter eller saker.

_Dokumentrapporter_ Eksporter dokumentmetadata og revisjondetaljer for alle valgte filer, inkludert dokumentnavn, revisjonsnavn, siste revisjonsnummer, status, egendefinerte felt, oppretter, opplaster og opprettelse/opplastingstidsstempler.

- **Viktige bruksscenarier**
  Ideal for generering av formelle dokumentleveringsjekklister for å følge med en samling, eller kompilering av strukturerte dokumentlister for dataanalyse.
- **Modellmetadata og attributter**
  Selvom det faktiske dokumentfilinnholdet ikke er inkludert, kan modellmetadata eksporteres gjennom dokumentrapporter som modeller opprettholder lenker til dokumentdelen. Egendefinerte skript i maler kan også brukes til å utlede ytterligere attributter, for eksempel utvinning av filtyper fra dokumentnavn.

_Sakrapporter_ Eksporter overordnede saksoverskrifter samt komplette sakskroppdetaljer, inkludert beskrivelser, kommentarer og innebygde kommentarbilder.

_Tilgjengelige eksportformater_ Rapporter opprettet fra en mal kan eksporteres til flere formater avhengig av arbeidsflytkrav:

- **PDF / PDF/A**
  Genererer rene formaterte rapporter og støtter direkte innebygd PDF/A-samsvar (PDF/A-1, PDF/A-2 og PDF/A-3) for å oppfylle strenge langsiktige arkiverings- og formelle juridiske standarder.
- **Excel**
  Eksporterer strukturerte tabellariske data til regnearkrader og kolonner, noe som gjør det ideelt for datamanipulering og ekstern analyse.
- **Tilleggs formater**
  Et bredt spekter av ytterligere filformater utover PDF og Excel støttes også for eksport; den komplette oversikten finner du i [rapportsiden](https://support.catenda.com/en/articles/12303098-reports-page).

_Sentralisert lagring_ Genererte rapporter vises direkte i rapporttabellen og integreres automatisk i hoveddokumenttabellen for enkel administrasjon.

## 3. **Catenda dataeksport**

I motsetning til standard brukerstyrt nedlasting, er Catenda Data Export en automatisert, selvbetjent løsning utformet for å smidig overføre prosjektdata direkte til en organisasjons skylager. Hvis organisasjonen din er interessert i å aktivere denne funksjonen, kan salg nås på [sales@catenda.com](mailto:sales@catenda.com). Når den er aktivert, gir den automatiserte sikkerhetskopier direkte mellom skyomgivelser uten å trenge egendefinerte skript, som omgår minnebegrensninger for nettleser, lagringsbegrensninger for lokal stasjon og nettverksavbrudd gjennom automatisert kontrollsum-verifisering.

### 3.1 **Organisasjonsroller og tillatelser**

Oppsettet og administrasjon av Catenda Data Export krever en **organisasjonsadministrator**. I motsetning til en organisasjonseier, hvis administrative rettigheter er begrenset til en enkelt organisasjon, eller standard prosjektmedlemmer, har en organisasjonsadministrator forhøyet tilgang på tvers av alle organisasjoner som tilhører en overordnet konto. Denne unike rollen gir den nødvendige tverrorganisasjonstillitingen og myndigheten til å konfigurere og administrere automatiserte skyleksporter.

### 3.2 **Konfigureringstrinn**

Oppsettet av automatiserte dataeksporter innebærer fire hovedtrinn:

1. **Velg destinasjon**
   Velg en skylageringsleverandør, Amazon Web Services (AWS) S3 eller Microsoft Azure Blob-lagring, og konfigurer godkjenning.
1. **Definer omfang og dataformater**
   - **Datatyper**
     Eksporter dokumenter, modeller og saker.
     Sakdata kan automatisk konverteres til lesbare PDF-sammendragsrapporter eller standard BCF-filer under overføring.
   - **Prosjektvalg**
     Velg alle prosjekter, håndplukk bestemte prosjekter, eller konfigurer dynamiske samsvaringsregler ved hjelp av prosjektnavn mønstre (glob eller regulært uttrykk / regex) for automatisk å inkludere nye prosjekter når de opprettes.
1. **Velg eksportmodus**
   - **Kontinuerlig modus**
     Sender data automatisk på en daglig tidsplan.
     Denne gjentakende oppsettet sikrer at ikke-eierprosjektmedlemmer opprettholder en oppdatert sikkerhetskopi opp til den siste daglige kjøringen hvis prosjekttilgangen avsluttes uventet.
   - **Øyeblikksbildemodus**
     Utfører en engangskjøring for å eksportere et komplett datasett ved en spesifikk milepæl eller prosjektovergelse.
1. **Distribuer**
   Full legg og aktiver eksportkonfigurasjonen ved å velge Opprett.

### 3.3 **Uttrukket innhold og integritetsverifisering**

_Metadata og egendefinerte felt_ Egendefinerte felt knyttet til dokumenter og saker eksporteres ved siden av primære filer som strukturerte JSON-filer, noe som sikrer fullstendig attributtbevaring uten manuell rapportgenerering.

_Integritetverifisering_ Hver eksportkjøring genererer en kontrollsum-fil for å bekrefte at eksporterte filer samsvarer med kildedataene i Catenda Hub og ble overført fullstendig uten nettverkstap.

_Organisert hierarki_ Eksporterte filer er automatisk strukturert til mapper organisert etter dato, prosjektnavn og det nøyaktige mappearkitekturhierarkiet opprettholdt i Catenda Hub.
