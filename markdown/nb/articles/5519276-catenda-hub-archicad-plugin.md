# Catenda Archicad plugin

> test

> **Merknad:** Installeringsfilen for plugin-en finner du i [denne artikkelen](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Catenda Archicad plugin er en plugin som kan installeres for Nemetchek Archicad. Med denne plugin-en kan du samarbeide om 3D-visninger, emner og Dokumenter med andre Medlemmer av byggprosjektet.

## 1. **Installasjon**

Når Catenda Archicad plugin installeres på Windows, vises installeringsfilene i følgende mappe.

`C:\\Program Files\\Catenda\\Catenda Archicad Connection\\\<Archicad Version>\\Add-On`

Plugin-en vises som aktivert i tilleggsprogrambehandleren neste gang Archicad åpnes. Merk at dette er annerledes enn standardmappen for tilleggsprogrammer som ligger på

`C:\\Program Files\\Graphisoft\\\<Archicad Version>\\Add-Ons`

### 1.1 **Avinstallering**

For å avinstallere plugin-en går du til følgende Windows-meny:

`Windows-innstillinger -> Apper -> Installerte apper`

Finn Catenda Archicad Connection \<version> i listen og klikk på handlingsmenyen på høyre side for å avinstallere.

## 2. **Catenda Palette**

Etter å ha installert plugin-en kan du se en Catenda-menyfane på toppraden. I denne menyen finner du vinduet "Catenda Hub Issue Manager" som inneholder "Catenda Hub Issue Manager Palette". For å begynne å bruke denne paletten må enten en plantegning eller en 3D-visning åpnes. I paletten kan du:

- Naviger til Catenda Hub-prosjektet ditt
- Se og opprett problemer
- Last ned og last opp model og revisjoner

## 3. **Logg inn**

Når du åpner Catenda-paletten er det første du ser innloggingssiden. Innloggingssiden kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/01-sign-in.png)

Hvis du ikke har en Catenda-konto kan du registrere deg gratis øverst til høyre. Hvis du allerede har en Catenda-konto kan du angi e-postadressen og passordet og klikke på Logg inn. Etter at du har logget inn, blir du bedt om å gi tilgang til Catenda-kontoen din. Etter at du har gitt denne tilgangen vil Archicad-plugin-en vises som et program på [programsiden](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) på Catenda-kontoen din. Her kan du alltid tilbakekalle tilgangen hvis du ikke lenger ønsker å gi den.

### 3.1 **Tilbakestill passord**

Hvis du glemte passordet kan du klikke på Jeg glemte passordet for å tilbakestille det. Siden for tilbakestilling av passord kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/02-password-reset.png)

Hvis du angir e-postadressen din og klikker på "send en verifikasjons-e-post" sendes det deg en e-post som veileder deg gjennom tilbakestilling av passordet. Sørg for at du mottar denne e-posten innen 5 minutter. Hvis du ikke ser den i innboksen, kan du prøve mappen for spam eller uønsket e-post. Hvis det tar lenger enn 5 minutter, kontakt oss på [support@catenda.com](mailto:support@catenda.com)

For å gå tilbake til innlogging klikker du på Logg inn øverst til høyre.

## 4. **Prosjektliste**

Når du åpner Archicad-plugin-en ser du listen over prosjektene dine som kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/03-project-list.png)

Så snart du har godtatt invitasjonen til et prosjekt vil du se prosjektet ditt vises i listen over prosjektene dine i plugin-en og på [prosjektsiden](https://support.catenda.com/en/articles/8400797-projects-page).

_Handlingsmeny_ Klikk på de tre prikkene ved siden av profilbildet ditt for å åpne rullegardinmenyen for handlinger:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/04-project-list.png)

_Model & revisjoner_ Dette er hvordan siden for model & revisjoner kan se ut. Her kan du se alle model-ene du har tilgang til i Catenda-prosjektet ditt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/05-project-list.png)

På denne siden kan du laste ned og importere ifc-filer fra Catenda-prosjektet ditt til Archicad-model-en din. Tidsstempelet på model-en vil være relativt. Hold musepekeren over tidsstempelet for å få nøyaktig informasjon om når revisjonen ble publisert. Klikk på pil-knappen ved siden av en av model-revisjonene for å importere IFC-filen som ble lastet opp som en revisjon. Hvis du ikke har tilgang til noen model-er i Catenda-prosjektet ditt vil du se følgende:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/06-project-list.png)

_Last opp IFC_ Last opp en IFC fra gjeldende Archicad-prosjekt. Dette er hvordan siden for opplasting av IFC kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/07-project-list.png)

Som standard vil filnavnet være navnet på Archicad-prosjektet. Dette blir navnet på revisjonen i Catenda. Velg hvilken model du vil laste opp filen til. Klikk på Innstillinger for å åpne eksportdialogen for Archicad IFC. Her kan du konfigurere hvilke innstillinger du vil bruke til å eksportere IFC-filen din til Catenda. Når du er klar, klikker du på Opplast-knappen for å laste opp en model.

_Koordinater_ Hold musepekeren over koordinatalternativet for å utvide koordinatmenyen. Dette er hvordan koordinatmenyen kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/08-project-list.png)

I koordinatmenyen kan koordinater velges til å være relative til: Surveypunkt - Standard Prosjektopprinnelse

_Versjon_ Versjonsnummeret for plugin-en.

_Logg ut_ Logg ut av Catenda-kontoen din

## 5. **Emnekartotek**

Når du klikker på et prosjekt for å åpne det åpnes det første emnekartoteket i prosjektet. Et emnekartotek kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/09-topic-board.png)

### 5.1 **Søk**

Klikk i søkefeltet for å fremheve det. Dette er hvordan det fremhevede søkefeltet kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/10-search.png)

Etter at du har klikket i søkefeltet åpnes det en rullegardin med foreslåtte Filtre. Velg et hvilket som helst av Filtrene for å bruke dem. Klikk på x ved siden av filteret for å fjerne det igjen. Begynn å skrive for å begrense de foreslåtte Filtrene eller utfør et tekstsøk.

### 5.2 **Vis Filtre**

Klikk på knappen Vis Filtre for å åpne filtreringsmenyen. Dette er hvordan filtreringsmenyen kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/11-show-filter.png)

Avhengig av de konfigurerte innstillingene i emnekartoteket og emnene som sendes inn kan ulike Filtre være tilgjengelige:

_Mine emner_ Tildelt til meg Etterspurt av meg Opprettet av meg

_Status_ De ulike statusene i emnekartoteket er listet opp her

_Type_ De ulike typene i emnekartoteket er listet opp her

_Frist_ Forfalt Mindre enn en dag Mindre enn en uke Mindre enn to uker Mindre enn en måned Alle med en frist

_Tildelt til_ Oppføringene som begynner med `@` er tildelte teams som er listet opp først. Etter det er tildelte prosjektMedlemmer listet opp.

_Etterspurt av_ Oppføringene som begynner med `@` er teams som etterspør emner som er listet opp først. Etter det er prosjektMedlemmer som etterspør emner listet opp.

_Milepæl_ Alle milepæler brukt på emner er listet opp.

_Merkelapp_ Merkelapper brukt på emner er listet her.

_Filtre som ikke er nevnt i filtreringsmenyen_ Tekstsøk Tekst kan søkes etter ved å skrive i søkefeltet.

Innhold som kan søkes Emnets tittel Emnebeskrivelse Emnekommentar

Kapitalisering Tekstsøket er ikke følsomt for store og små bokstaver.

Antall tegn Ett tegn - Ingen resultater. Minst to tegn kreves for et tekstsøk To tegn - Hele ord separert med mellomrom som passer til søkefrasen er inkludert i resultatene.

### 5.3 **Sorter**

Klikk på Sorter for å åpne sorteringsmenyen. Dette er hvordan sorteringsmenyen kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/12-sort.png)

Klikk på et hvilket som helst alternativ for å sortere emnelisten etter: _Nyeste_ - Standard Emner med den nyeste opprettingsdatoen

_Eldste_ Emner med den eldste opprettingsdatoen

_Nylig oppdatert_ Emner som er nylig oppdatert

_Minst nylig oppdatert_ Emner som er minst nylig oppdatert

## 6. **Emne**

Når du klikker på et emne i emnekartoteket åpner du det. Et emne kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/13-topic.png)
