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

_Valgt modellenedlasting_ Velg en eller flere modeller på [modellersiden](https://support.catenda.com/nb/articles/4670286-modellside) og bruk nedlastingshandlingen til å trekke ut deres nyeste revisjoner.

_Individuell revisjonsnedlasting_ Velg en modell på [modellersiden](https://support.catenda.com/nb/articles/4670286-modellside) og bruk nedlastingsknappen ved siden av hver revisjon i høyre informasjonspanel. Dette gir en effektiv måte å laste ned bestemte revisjoner direkte uten å måtte laste hele [modellinnholdssiden](https://support.catenda.com/nb/articles/4670270-modellinnholdsside). Alternativt kan individuelle revisjoner også lastes ned direkte fra innholdssiden for en modell.

_Avansert modelleksport_ Få tilgang til [modeleksportsiden](https://support.catenda.com/nb/articles/4670280-modelleksportside) for å pakke valgte revisjoner på tvers av flere modeller til en enkelt nedlastbar ZIP-fil. Denne metoden inkluderer avanserte alternativer for å forbedre de eksporterte modelfilene ved å bake inn merker, brukerdefinerte egenskaper eller biblioteksinformasjon.

### 2.2 **Eksporterer saker (3 måter)**

Sakdata kan utvinnes ved hjelp av tre primære formater via [utvekslingssaker](https://support.catenda.com/nb/articles/4670289-utveksle-saker), avhengig av hvordan informasjonen blir sett, analysert eller lagret:

_BCF (BIM Collaboration Format)_ En åpen standard utformet for å fange og overføre saksinformasjon som strengt overholder den offisielle BCF-spesifikasjonen, inkludert individuelle saksopprettelsestidsstempler. Dette formatet garanterer bred plattformfellesdrift, noe som gjør det ideelt for å åpne på nytt, redigere eller utveksle saksdata smidig med annen BCF-kompatibel programvare. For generelle langsiktige dokumentoppbevaringsplasser der direkte filforhåndsvisninger trengs, er PDF- eller Excel-formater vanligvis foretrukket.

_Excel_ Eksporterer sakparametere til et regnearkformat for filtrering, sortering og datamanipulering. Dette formatet gir strukturerte rader og kolonner som er ideelle for valg og kopiering av data, og Excel-filer kan lett forhåndsvises innenfor de fleste arkiveringsplattformer. For arkiveringsformål foretrekkes PDF-eksporten generelt fremfor Excel fordi den inneholder mer informasjon.

_PDF_ Genererer en ren, lesbar sammendragsrapport i standard PDF-format (v1.4) som er tilgjengelig uten spesialisert programvare (se [eksportering av saker til PDF](https://support.catenda.com/nb/articles/9784934-eksporterer-saker-til-pdf)). Standard PDF-eksporter inkluderer et konsolidert nedlastingstidsstempel for offisiell rapportering og arkivering, noe som gir mer informasjon enn en Excel-eksport. Mens grunneksorten genererer en standard PDF-fil (v1.4), som mange arkiveringssystemer automatisk konverterer til PDF/A ved opplasting for langsiktig visning, kan prosjekter med den innbygde [rapportsidefunksjonen](https://support.catenda.com/nb/articles/12303098-rapportsside) aktivert også eksportere saker i arkiveringsformater, som beskrevet i [Eksportering av prosjektdata med rapporter](https://support.catenda.com/nb/articles/17779017-eksportere-prosjektdata-med-rapporter) _(kun rapportredigerer-kunder)_.

### 2.3 **Eksporterer dokumenter og samlinger**

_Sats- og mappenedlastinger_ Velg individuelle mapper, bestemte dokumentbatcher eller alle synlige tabeilelementer på en gang for å generere en nedlastbar ZIP-arkiv. Det anbefales å laste ned i håndterbare batcher ved å velge bestemte undermapper eller målrettede filgrupper for jevne overføringer når du arbeider med store datasett.

- **Publisert-fanen**<br>Henter den nyeste publiserte revisjonen for hvert valgt dokument.
- **Arbeidsområde-fanen**<br>Henter den nyeste delte revisjonen for hvert valgt dokument (krever "Vis delte revisjoner"-tillatelse). Merk at eldre utkastrevisjoner ikke kan lastes ned i batch til en ZIP-arkiv og lastes ned individuelt.

_Individuell revisjonsnedlasting_ Velg et dokument på [dokumentersiden](https://support.catenda.com/nb/articles/8204673-dokumenter-side) og klikk på nedlastingsknappen ved siden av hver revisjon som vises i høyre informasjonsmeny. Dette er en enklere måte å laste ned individuelle eller historiske revisjoner på fordi dokumentforhåndsvisningssiden ikke trenger å lastes inn, slik at du kan velge et annet dokument i tabellen og laste ned revisjonene i høyremeny uten å måtte åpne en ny forhåndsvisningsside.

_Offentlige samlinger_ Bruk [samlinger](https://support.catenda.com/nb/articles/6344318-samlingside) til å opprette offentlige lenker for valgte dokumentdelsett, slik at eksterne parter kan laste ned filer uten å kreve en Catenda-konto. Merk at bare publiserte revisjoner kan legges til samlinger.

_Slettede filer_ Søk etter "slettet" i dokumentsøkelinjen for å finne og eksportere tidligere slettede dokumenter. Husk at dette filteret er språkspesifikt og vil tilsvare begrepet for "slettet" i gjeldende språkinnstillinger.

### 2.4 **Desktop connector (Automatisert lokal sikkerhetskopi)**

[Catenda Desktop Connector](https://support.catenda.com/nb/articles/8358861-catenda-desktop-connector) muliggjør bakgrunnssynkronisering, slik at nye dokumentrevisjoner periodisk lastes ned direkte til en lokal stasjon. I motsetning til batchnedlastinger fra nettleseren kommer dokumentene direkte til systemet ditt som rå, upakkede filer, uten at manuell utpakking av arkiv er nødvendig.

**Planlagte og øyeblikkelige sikkerhetskopier** Oppgaver kan planlegges til å kjøre automatisk med regelmessige intervaller eller utføres on-demand, noe som sikrer at prosjektmedlemmer bevarer en oppdatert lokal kopi av dokumenter selv om prosjekttilgangen uventet tilbakekalles.

**Direkte API-overføringer** Overfører store datasett betydelig raskere enn weblesernedlastinger ved å utnytte direkte API-forbindelser uten leserbegrensninger eller overhead.

**Hierarkialternativer** Laster ned valgte mappestrukturer med komplett hierarki intakt, eller trekker ut individuelt valgte filer direkte som en flat liste til den utpekte lokale mappen.

### 2.5 **Medlemtilgang og aktivitetslogger**

_Saklister_ Dokumentelementbordtilgangstillatelser ved hjelp av to tilgjengelige visninger:

- **Per-bruker tilgangsvisning**<br>Vis individuelle brukeradgangnivåer direkte fra informasjonsmenyene til høyre på en saksliste eller valgt sak.<br>_Tilgang kreves:_ lesetilgang til sakslist
- **Fullstendig teamkonfigurasjon**<br>Ta skjermbilder av de komplette tillatelseinnstillingene på teamnivå innenfor tilganginnstillingene for sakslisten.<br>_Tilgang kreves:_ Full tilgang til sakslisten eller prosjektadministrator

_Dokument- og modelltilgang_ Eksporter [tilgangsoversikten](https://support.catenda.com/nb/articles/6660820-tilgangsoversikt-over-dokumenter) for å registrere tillatelser for medlemmer og team. Tilgang påkrevd: Prosjektadministrator. Fordi hver modell er knyttet til et dokument i dokumentdelen, styres tilgangstillatelser for modeller av de underliggende dokumenttillatelsene og registreres ved hjelp av samme dokumenttilgangsoversikt eller tillatelseamenyer.

_Dokument- og modellrevisjonens tilgang_ Vis tillatelser fra [høyre meny for en dokumentrevisjon](https://support.catenda.com/nb/articles/8302244-hoyre-meny-for-en-revisjon-revisjonsinformasjon) og fang opp skjermbildet etter behov.

_Prosjektomfattende handlingstillatelser_ Dokumenter prosjektomfattende tillatelser på [prosjektinnstillingssiden](https://support.catenda.com/nb/articles/4670273-prosjektinnstillinger) (for eksempel oppretting av saklister, invitasjon av nye medlemmer, konfigurering av dokumentstatuser og opprettelse eller fjerning av modeller) ved hjelp av to tilgjengelige visninger:

- **Visning per bruker**<br>Prosjektmedlemmer kan utvide hver meny under tilgangskontroll for å se hvilke individuelle brukere som har tillatelse til å utføre hver handling.
- **Fullstendig konfigurasjon**<br>Administratorer kan åpne dialogboksen for redigering av tilgang for å vise og administrere tillatelseinnstillinger på teamnivå.<br>_Tilgang kreves:_ Prosjektadministrator

_Brukerprofiler og medlemsdetaljer_ Informasjon om prosjektmedlemmer og team er tilgjengelig for utvinning eller dokumentasjon, inkludert:

- Brukernavn og e-postadresser (se [egendefinert medlemsinformasjon](https://www.google.com/search?q=https://support.catenda.com/nb/articles/11769670-egendefinert-medlemsinformasjon)).
- Teammedlemskap, tildelte saker, opplastede modellrevisjoner og tillatelseinnstillinger (fanget via [medlemssiden](https://www.google.com/search?q=https://support.catenda.com/nb/articles/4670291-medlemmer-og-teams-side) eller [teamsiden](https://www.google.com/search?q=https://support.catenda.com/nb/articles/4670291-medlemmer-og-teams-side)).

### 2.6 **Varslinger**

Fang opp varslingssider via skjermbildet fra [prosjektvarslinger-siden](https://support.catenda.com/nb/articles/4670295-prosjektvarselside), ved hjelp av [grensefilter](https://support.catenda.com/nb/articles/8304417-filtrering-pa-varslingssiden) for å maksimere synlige elementer per side.

Konfigurer en dedikert administratorkonto med [prosjektspesifikke varslingsinnstillinger](https://support.catenda.com/nb/articles/4670262-prosjektspesifikke-varselinnstillinger) aktivert for e-postsammendrag for å opprettholde søkbare varslingslogger.

### 2.7 **Rapportsiden (Innmeldingsfunksjon)**

[Rapportsiden](https://support.catenda.com/nb/articles/12303098-rapportsside) er en frivillig funksjon som kan forespørres for pågående prosjekter. Prosjekter som har den aktivert kan også eksportere Dokumenter- og Sak-data som formaterte rapporter, inkludert formater for langsiktig arkivering.

_Malbasert administrasjon_ Når den er aktivert, bruker prosjektadministratorer [rapportmalsiden](https://support.catenda.com/nb/articles/12380837-rapportmalsider) til å konfigurere rapportmaler etter eget valg og generere formaterte eksporter for valgte Dokumenter eller Saker.

Hva som kan eksporteres, og i hvilke filformater, er beskrevet i [Eksportering av prosjektdata med rapporter](https://support.catenda.com/nb/articles/17779017-eksportere-prosjektdata-med-rapporter) _(kun rapportredigerer-kunder)_.

## 3. **Catenda dataeksport**

Catenda Data Export selges separat fra Catenda Hub. I motsetning til nedlastingene ovenfor kopierer den prosjektdata automatisk, direkte fra Catenda Hub til en organisasjons egen skylagring i Amazon S3 eller Azure Blob storage. Den passer for organisasjoner som ønsker en sikkerhetskopi som holder tritt med prosjektene deres, eller prosjektregistreringer lagret i egen lagring. Den er ikke kun for prosjekteiere. En prosjekteier kan eksportere en fullstendig sikkerhetskopi av sine prosjekter, og en prosjektdeltaker kan eksportere det vedkommende har tilgang til i prosjektene vedkommende deltar i. Mer om dette finnes i [Om Catenda Data Export](https://support.catenda.com/nb/articles/17779020-om-catenda-data-export) _(for lesere som ikke er logget inn)_ og [Introduksjon til Catenda Data Export](https://support.catenda.com/nb/articles/17779027-introduksjon-til-catenda-data-export) _(kun for innloggede kunder)_. Kunder som har tjenesten finner oppsettet i [Catenda Data Export](https://support.catenda.com/nb/articles/17779052-catenda-datakeksport) _(kun for Data Export-kunder)_.
