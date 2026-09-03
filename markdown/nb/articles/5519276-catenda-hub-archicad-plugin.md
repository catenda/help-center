# Catenda Archicad-plugin

> **Merk:** Installasjonfilen for programtillegget finner du i [denne artikkelen](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Catenda Archicad-plugin er et programtillegg som kan installeres for Nemetschek Archicad. Med dette programtillegget kan du samarbeide om 3D-synspunkter, saker og dokumenter med andre medlemmer av byggeprosjektet.

De følgende sakene er beskrevet i denne artikkelen:

## 1. **Installasjon**

Når Catenda Archicad-plugin installeres på Windows, vil installasjonsfilene vises i følgende mappe.

`C:\Program Files\Catenda\Catenda Archicad Connection\<Archicad Version>\Add-On`

Programtillegget vises som aktivert i Legg til programtillegg-behandleren neste gang Archicad åpnes. Merk at dette er forskjellig fra standard programtillegg-mappen som befinner seg på

`C:\Program Files\Graphisoft\<Archicad Version>\Add-Ons`

### 1.1 **Avinstallasjon**

Hvis du vil avinstallere programtillegget, går du til følgende Windows-meny:

`Windows-innstillinger -> Apper -> Installerte apper`

Finn Catenda Archicad Connection \<version> i listen og klikk på handlingsmenyen på høyre side for å avinstallere.

## 2. **Catenda Palette**

Etter at du har installert programtillegget, kan du se en Catenda-menyfane på topplisten. I denne menyen finner du vinduet "Catenda Hub Issue Manager" som inneholder "Catenda Hub Issue Manager Palette". For å begynne å bruke denne paletten, må enten et planleggingskart eller en 3D-visning være åpnet. I paletten kan du:

- Gå til Catenda Hub-prosjektet ditt
- Se og opprett problemer
- Laste ned og laste opp modeller og revisjoner

## 3. **Logg inn**

Når du åpner Catenda-paletten, er det første du ser, innloggingssiden. Innloggingssiden kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/01-sign-in.png)

Hvis du ikke har en Catenda-konto, kan du registrere deg gratis øverst til høyre. Hvis du allerede har en Catenda-konto, kan du skrive inn e-postadressen og passordet ditt og klikke på Logg inn. Etter innlogging blir du bedt om å gi tilgang til Catenda-kontoen din. Etter at du har gitt denne tilgangen, vises Archicad-programtillegget som en applikasjon på [applikasjoner-siden](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) for Catenda-kontoen din. Her kan du alltid tilbakekalle tilgangen hvis du ikke lenger ønsker å gi den.

### 3.1 **Tilbakestill passord**

Hvis du har glemt passordet ditt, kan du klikke på Jeg har glemt passordet mitt for å tilbakestille det. Siden for tilbakestilling av passord kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/02-password-reset.png)

Hvis du skriver inn e-postadressen din og klikker på "send en verifiserings-e-post", får du en e-post som vil veilede deg gjennom tilbakestilling av passordet ditt. Kontroller at du har mottatt denne e-posten innen 5 minutter. Hvis du ikke ser den i innboksen din, kan du prøve mappen for spam eller søppelpost. Hvis det tar lengre enn 5 minutter, kontakter du brukerstøtten på [support@catenda.com](mailto:support@catenda.com)

Hvis du vil gå tilbake til innlogging, klikker du på Logg inn øverst til høyre.

## 4. **Prosjektliste**

Når du åpner Archicad-programtillegget, ser du listen over prosjektene dine, som kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/03-project-list.png)

Så snart du har godtatt invitasjonen til et prosjekt, vises prosjektet ditt i listen over prosjektene dine i programtillegget og på [prosjektsiden](https://support.catenda.com/en/articles/8400797-projects-page).

_Handlingsmeny_ Klikk på de tre prikkene ved siden av profilbildet ditt for å åpne rullegardinmenyen for handlinger:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/04-project-list.png)

_Modeller og revisjoner_ Dette er hvordan siden for modeller og revisjoner kan se ut. Her kan du se alle modellene du har tilgang til i Catenda-prosjektet ditt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/05-project-list.png)

På denne siden kan du laste ned og importere IFC-filer fra Catenda-prosjektet ditt til Archicad-modellen din. Tidsstempelet for modellen vil være relativt. Hold musemarkøren over tidsstempelet for å få nøyaktig informasjon om når revisjonen ble publisert. Klikk på pilknappen ved siden av en av modellrevisjonene for å importere IFC-filen som ble lastet opp som en revisjon. Hvis du ikke har tilgang til noen modeller i Catenda-prosjektet ditt, ser du følgende:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/06-project-list.png)

_Last opp IFC_ Last opp en IFC fra gjeldende Archicad-prosjekt Dette er hvordan siden for opplasting av IFC kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/07-project-list.png)

Som standard vil filnavnet være navnet på Archicad-prosjektet. Dette blir navnet på revisjonen i Catenda. Velg hvilken modell du vil laste opp filen til. Klikk på innstillinger for å åpne dialogboksen for Archicad IFC-eksport. Her kan du konfigurere hvilke innstillinger du vil bruke for å eksportere IFC-en til Catenda. Når du er klar, klikker du på opplastingsknappen for å laste opp en modell.

_Koordinater_ Hold musemarkøren over alternativet Koordinater for å utvide menyen Koordinater. Dette er hvordan menyen Koordinater kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/08-project-list.png)

I menyen Koordinater kan koordinater velges til å være relative til: Grunnpunkt - Standard Prosjektopprinnelse

_Versjon_ Versjonsnummeret til programtillegget.

_Logg ut_ Logg ut av Catenda-kontoen din

## 5. **Saksliste**

Når du klikker på et prosjekt for å åpne det, åpnes den første sakslistens i prosjektet. En saksliste kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/09-topic-board.png)

De følgende sakene er beskrevet i denne delen:

### 5.1 **Søk**

Klikk i søkefeltet for å markere det. Dette er hvordan søkefeltet som er markert, kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/10-search.png)

Etter at du har klikket i søkefeltet, åpnes en rullegardin med foreslåtte filtre. Velg et av filtrene for å bruke det. Klikk på x-en ved siden av filteret for å fjerne det igjen. Begynn å skrive for å begrense de foreslåtte filtrene eller utfør et tekstsøk.

### 5.2 **Vis filter**

Klikk på knappen Vis filter for å åpne filtermenyen. Dette er hvordan filtermenyen kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/11-show-filter.png)

Avhengig av de konfigurerte innstillingene i sakslistens og sakene som sendes inn, kan det være tilgjengelig ulike filtre:

_Mine saker_ Tildelt til meg Etterspurt av meg Opprettet av meg

_Status_ De ulike statusene i sakslistens er oppført her

_Type_ De ulike typene i sakslistens er oppført her

_Frist_ Forfalt Mindre enn en dag Mindre enn en uke Mindre enn to uker Mindre enn en måned Alle med en frist

_Tildelt til_ Oppføringene som begynner med en `@` er tildelte team som er oppført først. Etter det er tildelte prosjektmedlemmer oppført.

_Etterspurt av_ Oppføringene som begynner med en `@` er team som etterspør saker som er oppført først. Etter det er prosjektmedlemmer som etterspør saker, oppført.

_Milepæl_ Eventuelle milepæler som brukes på saker, er oppført.

_Merkelapp_ Merkelapper brukt på saker er oppført her.

_Filtre som ikke er nevnt i filtermenyen_ Tekstsøk Tekst kan søkes på ved å skrive i søkefeltet.

Innhold som kan søkes på Sakstittel Saksbeskrivelse Sakskommentar

Kapitalisering Tekstsøket skiller ikke mellom små og store bokstaver.

Antall tegn Enkelt tegn - Ingen resultater. Minst to tegn kreves for et tekstsøk To tegn - Hele ord, atskilt med mellomrom, som samsvarer med søkefrasen, er inkludert i resultatene.

### 5.3 **Sortering**

Klikk på Sortering for å åpne sorteringsmenyen. Dette er hvordan sorteringsmenyen kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/12-sort.png)

Klikk på et av alternativene for å sortere sakslistens etter: _Nyeste_ - Standard Saker med den nyeste opprettelsesdatoen

_Eldste_ Saker med den eldste opprettelsesdatoen

_Nylig oppdatert_ Saker som er nylig oppdatert

_Minst nylig oppdatert_ Saker som er minst nylig oppdatert

## 6. **Sak**

Når du klikker på en sak i sakslistens, åpner du den. En sak kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/13-topic.png)
