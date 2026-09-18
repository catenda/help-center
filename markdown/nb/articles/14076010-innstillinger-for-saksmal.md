# Innstillinger for saksmal

> Administrer innstillingene for saksmal

Siden for innstillinger for saksmal finner du ved å klikke på Konfigurer saksmal på [siden for saksinnstillinger](https://support.catenda.com/en/articles/14183429-topic-settings-page) som kan åpnes fra venstre navigasjonsmeny etter at du har åpnet siden for saker. _Tilgang kreves:_ Prosjektadministrator

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/01-intro.png)

På siden for innstillinger for saksmal kan saksmaler for hver av saklistene i prosjektet konfigureres. Etter opprettelsen gjøres saksmaler automatisk tilgjengelige for å fylle ut tekst og felt for saker ved opprettelse. Saksmaler kan konfigureres til å være tilgjengelige i følgende prosesser for saksopprettelse: [Hvordan bruke saksmaler i generelle saker](https://support.catenda.com/en/articles/14075921-apply-a-general-topic-template-upon-topic-creation) [Hvordan bruke saksmaler i merknadsaker](https://support.catenda.com/en/articles/14078352-apply-a-document-topic-template-when-creating-a-markup-from-a-document) [Hvordan bruke saksmaler med gjennomganger](https://support.catenda.com/en/articles/14078683-apply-an-approval-topic-template-to-an-approval-workflow-template)

## 1. **Handlingsmeny**

Klikk på plusknappen øverst til høyre for å åpne handlingsmenyen. Slik kan handlingsmenyen øverst til høyre på siden for innstillinger for saksmal se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/02-action-menu.png)

En rullegardinmeny gir deg muligheten til å opprette 3 forskjellige typer saksmaler. Saksmaler skilles inn i tre ulike maltyper fordi variablene som kan brukes til å automatisk fylle ut tekst og felt i saker ved opprettelse varierer avhengig av prosessen for saksopprettelse som brukes.

## 2. **Søk- eller filteralternativer**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/03-search-or-filter-options.png)

### 2.1 **Søk**

_Tekstsøk -_ `search=<Search phrase>` Etter at du har skrevet inn tegn i søk- eller filterlinjen, endres det første foreslåtte filteret til tekstsøk.

_Innhold som kan søkes på_ Navn på saksmal

_Kapitalisering_ Tekstsøket er ikke følsomt for store eller små bokstaver.

_Antall tegn_ Hvilket som helst antall eller type tegn kan søkes på.

_Mellomrom_ Mellomromstegn ved starten av en søkefrase kan søkes på, men blir fjernet fra malmalnavn, så det vil ikke være noen resultater når det søkes. Mellomromstegn på slutten av en søkefrase blir fjernet.

### 2.2 **Filtrering i filtermenyen**

Saksmaler filtreres enten etter en av de mulige statusene. Klikk på Status-menyen i filtermenyen for å skjule statusalternativet som ikke er filtrert. Det er mulig å trykke på X til høyre i søkelinjen for å fjerne filtertagger fra linjen, men dette har ingen effekt. Det er bare mulig å filtrere maler med enten Aktiv eller Arkivert filter.

_Aktiv_ - `status=active` - Standard Saksmaler som aktivt kan brukes og konfigureres til å generere saker.

_Arkivert_ - `status=archived` Saksmaler som ikke er tilgjengelige for bruk eller konfigurering i prosessen for saksopprettelse.

## 3. **Malmaltabell**

Når du navigerer til siden for innstillinger for saksmal, kan du se en oversikt over eksisterende saksmaler som tidligere er opprettet. Slik kan tabellen over saksmaler se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/04-templates-table.png)

Klikk [her](https://support.catenda.com/en/articles/11748020-tables-on-catenda) for å lese mer om hvordan du arbeider med tabeller i Catenda.

### 3.1 **Radinnhold**

Klikk på en saksrad for å åpne innholdsiden for saksmal for den malen.

### 3.2 **Kolonner**

Alle kolonner i tabellen over saksmaler er som standard aktivert. Basert på den konfigurerte kolonneordren vises de første kolonnene, mens tabellen kanskje må rulles sideveis for å vise andre aktiverte kolonner. Standardordenen og visibilitetinnstillingene for kolonnene på dokumentsiden er som følger:

Navn Maltype Opprettet av Opprettet den Status Sakliste

## 4. **Opprett en ny generell saksmal**

Kan brukes på saker opprettet fra delen Generell sak. Her er de ulike handlingene du må følge og variablene du kan skrive inn når du oppretter en ny generell saksmal:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/05-create-a-new-general-topic-template.png)

1. **Sakliste**: Saklisten som den generelle saksmalenen kan genereres innen for.
1. **Malnavn**: Malmalnavn kan velges fra rullegardinen under opprettelse, eller oppdateres i innstillingene senere hvis det er nødvendig.
1. **Sakstittel**: Den resulterende saktittelen etter opprettelse av saken fra den generelle saksmalen.<br>Hold musen over "?" ikonet som ligger på øverst til høyre på tittelfeltet for å se hvordan du kan tilpasse saksmalens tittel med den tilgjengelige variabelen: `topicCreator`.<br>

    <div class="intercom-container intercom-align-center"><img height="184" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-272165f584d2.png" style="height: auto;" width="300"/></div>

1. **Saksstatus**: Den resulterende saksstatus etter opprettelse av saken fra den generelle saksmalenen.
1. **Sakstype**: Den resulterende sakstype etter opprettelse av saken fra den generelle saksmalenen.
1. **Milepæl**: Den resulterende saksmilepæl etter opprettelse av saken fra den generelle saksmalenen.
1. **Tildelt til**: Den resulterende saksansvarlige (prosjektmedlem eller team) etter opprettelse av saken fra den generelle saksmalen. Du kan bruke `Topic Creator` variabelen her for automatisk å fylle ut dette feltet med sakens oppretteren om nødvendig.<br>

    <div class="intercom-container intercom-align-center"><img height="94" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-c7f3d7220c54.png" style="height: auto;" width="150"/></div>

1. **Etterspurt av**: Den resulterende saksklageren etter opprettelse av saken fra den generelle saksmalen. Du kan bruke `Topic Creator` variabelen her for automatisk å fylle ut dette feltet med sakens oppretteren om nødvendig.<br>

    <div class="intercom-container intercom-align-center"><img height="93" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-43e4955bfdd8.png" style="height: auto;" width="150"/></div>

1. **Merkelapper**: De resulterende saksmerkelappene etter opprettelse av saken fra den generelle saksmalenen.
1. **Beskrivelse**: Den resulterende saksbeskrivelsen etter opprettelse av saken fra den generelle saksmalen. Denne delen støtter Markdown-format og du kan bruke dens fulle potensial til å formatere teksten, opprette tilpassede overskrifter og sjekklister. <br>Hold musepekeren over "?" -ikonet som er plassert i øvre høyre hjørne av beskrivelsesfeltet for å se hvordan du kan bruke alle tilgjengelige funksjoner (nevn lagkamerater og lenk eksisterende saker) og variabler (som `topicCreator` i tilfelle av den generelle saksmalen).

    <div class="intercom-container intercom-align-center"><img height="291" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-d2735ca1aec8.png" style="height: auto;" width="300"/></div>

Når du er ferdig med å sette opp den nye generelle saksmalenen din, kan du klikke på "Lagre" knappen nederst til høyre.

## 5. **Ny dokumentsaksmal**

Kan brukes på saker opprettet fra merknader på dokumenter. Her er de ulike handlingene du må følge og variablene du kan skrive inn når du oppretter en ny dokumentsaksmal:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/06-new-document-topic-template.png)

1. **Sakliste**: Saklisten som dokumentsaksmalenen kan genereres innen for.
1. **Malnavn**: Malmalnavn kan velges fra rullegardinen under oppretting av merknad, eller oppdateres i innstillingene senere hvis det er nødvendig.
1. **Sakstittel**: Den resulterende saktittelen etter opprettelse av saken fra dokumentsaksmalen.<br>Hold musen over "?" ikonet som ligger på høyre side av tittelfeltet for å se hvordan du kan tilpasse dokumentsaksmalen tittel med de tilgjengelige variablene: `documentName`, `fileName`, `markupName` og `topicCreator`.<br>

    <div class="intercom-container intercom-align-center"><img height="231" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-dbe5030f1082.png" style="height: auto;" width="300"/></div>

1. **Saksstatus**: Den resulterende saksstatus etter opprettelse av saken fra dokumentsaksmalenen.
1. **Sakstype**: Den resulterende sakstype etter opprettelse av saken fra dokumentsaksmalenen.
1. **Milepæl**: Den resulterende saksmilepæl etter opprettelse av saken fra dokumentsaksmalenen.
1. **Tildelt til**: Den resulterende saksansvarlig (prosjektmedlem eller team) etter opprettelse av saken fra dokumentsaksmalenen. Ulike variabler kan brukes her, for eksempel `Dokumenteier`, `Filstringer`, `Merknadsoppretter`, `Utgiver` og `Saksoppretteren`.

    <div class="intercom-container intercom-align-center"><img height="228" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b3156a6c2724.png" style="height: auto;" width="150"/></div>

1. **Etterspurt av**: Den resulterende saksklageren etter opprettelse av saken fra dokumentsaksmalen. Ulike variabler kan brukes her, for eksempel `Document owner`, `File uploader`, `Markup creator`, `Publisher` og `Topic creator`.<br>

    <div class="intercom-container intercom-align-center"><img height="171" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-0c4680dfae06.png" style="height: auto;" width="150"/></div>

1. **Merkelapper**: De resulterende saksmerkelappene etter opprettelse av saken fra dokumentsaksmalen. Merk at du kan hente merkelappene fra dokumentet du opprettet merkingen fra ved hjelp av variabelen `Labels from documents` nedenfor:<br>

    <div class="intercom-container intercom-align-center"><img height="67" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-522016d4b8ae.png" style="height: auto;" width="500"/></div>

1. **Beskrivelse**: Den resulterende saksbeskrivelsen etter opprettelse av saken fra dokumentsaksmalen. Denne delen støtter Markdown-format og du kan bruke dens fulle potensial til å formatere teksten, opprette tilpassede overskrifter og sjekklister. <br>Hold musepekeren over "?" -ikonet som er plassert i øvre høyre hjørne av beskrivelsesfeltet for å se hvordan du kan bruke alle tilgjengelige funksjoner (nevn lagkamerater og lenk eksisterende saker) og variabler (som `documentName`, `fileName`, `markupName` og `topicCreator` i tilfelle av dokumentsaksmalen).

    <div class="intercom-container intercom-align-center"><img height="349" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b8f3e2dabde9.png" style="height: auto;" width="300"/></div>

Når du er ferdig med å sette opp den nye dokumentsaksmalenen din, kan du klikke på "Lagre" knappen nederst til høyre.

## 6. **Ny gjennomgangssaksmal**

Kan brukes på saker opprettet etter at en gjennomgangsarbeidsflyt er avsluttet. _Tilgang kreves:_ Delte statuser aktivert (Arbeidsområde- og publiserte faner synlige på dokumenter og modellsider)

> **Merknad:** Dette alternativet vises bare hvis gjeldende status- og valideringsarbeidsflyter er i bruk. Prosjekter opprettet etter 2. oktober 2025 bruker automatisk gjeldende status- og valideringsarbeidsflyter.

Her er de ulike handlingene du må følge og variablene du kan skrive inn når du oppretter en ny gjennomgangssaksmal:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/07-new-approval-topic-template.png)

1. **Sakliste**: Saklisten som gjennomgangssaksmalenen vil bli generert innen for etter at en gjennomgangsarbeidsflyt er avsluttet.
1. **Malnavn**: Malmalnavn for en gjennomgangssaksmal kan velges fra rullegardinen i en gjennomgangsarbeidsflytsmal, eller oppdateres i innstillingene senere hvis det er nødvendig.
1. **Sakstittel**: Den resulterende saktittelen etter at den tilknyttede gjennomgangsprosessen er lukket.<br>Hold musen over "?" ikonet som ligger på høyre side av tittelfeltet for å se hvordan du kan tilpasse saksmalens tittel for gjennomgang med de tilgjengelige variablene: `approvalRequestName`, `approvalRequestNumber`, `documentName`, `fileName`, `markupName` og `topicCreator`.<br>

    <div class="intercom-container intercom-align-center"><img height="272" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-6038b1d41fed.png" style="height: auto;" width="300"/></div>

1. **Saksstatus**: Den resulterende saksstatus etter avslutning av den tilknyttede gjennomgangsarbeidsflyten.
1. **Sakstype**: Den resulterende sakstype etter avslutning av den tilknyttede gjennomgangsarbeidsflyten.
1. **Milepæl**: Den resulterende saksmilepæl etter avslutning av den tilknyttede gjennomgangsarbeidsflyten.
1. **Tildelt til**: Den resulterende saksansvarlig (prosjektmedlem eller team) som avslutter den tilknyttede gjennomgangsarbeidsflyten. Ulike variabler kan brukes her, for eksempel `Gjennomgangforespørselsgodkjenner`, `Gjennomgangsforespørselsgodkjennerteam`, `Gjennomgangsforespørselsinnsender`, `Gjennomgangsforespørselsinnsenderteam`, `Dokumenteier`, `Filstringer`, `Merknadsoppretter`, `Merknadsoppretterteam`, `Utgiver`.

    <div class="intercom-container intercom-align-center"><img height="182" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b012d92ee132.png" style="height: auto;" width="150"/></div>

1. **Etterspurt av**: Den resulterende saksklageren etter lukking av den tilknyttede gjennomgangsprosessen. Ulike variabler kan brukes her, for eksempel `Approval request approver`, `Approval requested approver team`, `Approval request submitter`, `Approval request submitter team`, `Document owner`, `File uploader`, `Markup creator`, `Markup creator team`, `Publisher`.<br>

    <div class="intercom-container intercom-align-center"><img height="181" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-d7986adac70c.png" style="height: auto;" width="150"/></div>

1. **Merkelapper**: De resulterende saksmerkelappene etter lukking av den tilknyttede gjennomgangsprosessen. Merk at du kan hente merkelappene fra dokumentet du opprettet merkingen fra ved hjelp av variabelen `Labels from documents` nedenfor:<br>

    <div class="intercom-container intercom-align-center"><img height="67" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-522016d4b8ae.png" style="height: auto;" width="500"/></div>

1. **Beskrivelse**: Den resulterende saksbeskrivelsen etter lukking av den tilknyttede gjennomgangsprosessen. Denne delen støtter Markdown-formatet og du kan bruke sitt fulle potensial til å formatere teksten, opprette egne overskrifter og sjekklister. <br>Hold musen over "?" ikonet som ligger i øverst til høyre hjørnet av beskrivelsesfeltet for å se hvordan du kan utnytte alle tilgjengelige funksjoner (nevne lagkamerater og koble til eksisterende saker) og variabler (for eksempel `approvalRequestDueDate`, `approvalRequestFileLink`, `approvalRequestLink`, `approvalRequestName`, `approvalRequestNumber`, `documentName`, `fileName`, `markupName`, `topicCreator`) i tilfellet av saksmalens gjennomgang).<br>

    <div class="intercom-container intercom-align-center"><img height="449" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-f3f078b5d2af.png" style="height: auto;" width="300"/></div>

Når du er ferdig med å sette opp den nye gjennomgangssaksmalenen din, kan du klikke på "Lagre" knappen nederst til høyre.
