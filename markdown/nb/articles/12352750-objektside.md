# Objektside

Objektsiden finner du som en underside til modellsiden. En tabell med informasjon om prosjektmodellene vises. Sammenligningsfiltre kan kombineres for å hente ut bare den informasjonen som er forespurt. Denne siden kombinerer elementer fra QTO-menyen i informasjonspanelet og egenskapsbiblioteker på biblioteksiden og vil eventuelt erstatte begge.

![Dashbord Modeller Bokmerker Objekter Etasje Konfigurator](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/01-intro.png)

## 1. **Søk eller filtrer**

Slik kan søke- eller filtermenyen se ut på objektsiden

![Søk eller filtrer Velg Plus Modeller Valgt Tekstsøk](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/02-search-or-filter.png)

Klikk [her](https://support.catenda.com/en/articles/12353642-filtering-on-the-objects-page) for å lese mer om filtrering på objektsiden.

## 2. **Produkttabell**

Produkttabellen kan se slik ut:

![Valgt 3D handlingsmeny nedlasting innstillinger enhetskolonne GlobalId-kolonne LongName-kolonne IfcProject IfcBuildingelementProxy én rad er valgt i tabell](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/03-products-table.png)

Klikk [her](https://support.catenda.com/en/articles/11748020-tables-on-catenda) for å lese mer om hvordan du arbeider med tabeller i Catenda.

### 2.1 **Hva er et produkt?**

Navnet produkter kommer fra det faktum at hver rad er et produkt av prosessen som skjer når en IFC importeres.

### 2.2 **Vist informasjon**

Så snart den siste revisjonen av en modell har fullført behandlingen, kan en rad for hvert produkt som ble gjenkjent i IFC-filen vises i produkttabellen. Bare informasjon fra de siste revisjonene av modellene i et prosjekt vises.

### 2.3 **Valgte elementhandlinger**

Etter at du velger en elementrad, vises valgte elementhandlinger mot toppen av produkttabellen. Slik kan menyen for valgte elementhandlinger se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/04-selected-item-actions.png)

_Viser_ Klikk på 3D-ikonet eller bruk viseren-handlingen for å velge de valgte elementene i objekttabellen i 3D-visningen.

_Isoler_ Bruk isoler-handlingen for å isolere de valgte elementene i objekttabellen i 3D-visningen.

_Skjul andre_ Bruk skjul andre-handlingen for å skjule alle objekter i 3D-visningen bortsett fra de valgte objektene.

### 2.4 **Radinnhold**

_Tilgang_ Bare produktrader for de siste revisjonene av modeller som medlemmer har tilgang til vises. _Tilgang kreves -_ Les

_Produktrad_ Produktrader kan ikke åpnes som i andre tabeller. Produktrader kan bare vises i 3D-visningen via handlingsmenyen.

_Valg_ Radvalg fungerer litt annerledes enn i andre tabeller rundt Catenda. I motsetning til andre tabeller rundt Catenda blir ikke valget tilbakestilt når du går til en annen side og kommer tilbake eller endrer et filter. I produkttabellen tilbakestilles valget bare når siden oppdateres. Ettersom det ofte vil være tusenvis av objekter valgt, er det mer vanlig at valgte rader ikke er i visningen. Et annet filter kan brukes slik at de valgte radene ikke lenger vises i tabellen, men de vil forbli valgt.

### 2.5 **Eksport**

Klikk på nedlastingsknappen mot toppen av produkttabellen for å eksportere den.

![Nedlastingsknapp](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/05-export.png)

Rader Det er bare mulig å få alle rader fra de aktiverte modellene. Valg av rader begrenser ikke radene i de eksporterte filene. Det eneste filteret som kan begrense antall rader er modellefilteret. Selv om rader kan se begrenset ut i tabellen, vil den eksporterte filen inkludere alle rader for modellene som er tilgjengelige.

Kolonner En kolonne for hver kolonne som er aktivert i produkttabellen eksporteres til filen. Klikk [her](https://support.catenda.com/en/articles/11748020-tables-on-catenda) for å lese mer om hvordan du administrerer tabellkolonner.

_Eksportobjekter_ Velg å eksportere til Excel eller CSV i eksportobjekter-menyen:

![Eksporter objekter Excel CSV](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/06-export.png)

_Forberede eksport_ Etter at du klikker på eksport, kan du se en meny som sier at kalkularket klargjøres mot nedre høyre hjørne.

![Forbereder eksport Forbereder regneark](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/07-export.png)

I løpet av denne tiden er det trygt å fortsette navigering rundt Catenda så lenge siden ikke oppdateres. Når regnearket blir tilgjengelig, ser det slik ut og filen begynner å lastes ned i nettleseren:

![Eksport klar Regneark tilgjengelig](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/08-export.png)

### 2.6 **Kolonner**

Noen kolonner i produkttabellen er aktivert som standard mens andre kan skjules og må aktiveres. Slik kan kolonnenavigasjonen i produkttabellen se ut:

![Attributter Type GlobalId Navn Etikett Prosjekt Nettsted Bygning Oppfrisk](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/09-columns.png)

_Veksle_ Aktiver eller deaktiver alle kolonner med denne vekslebryter

_Filter_ Skriv inn navn på en kolonne eller kolonnekategori for å filtrere kolonnenavigasjonen for den kolonnen. Det kan være at kolonnen du søker etter befinner seg i en skjult kolonnekategori, så sørg for å utvide hver kategori for å se om resultatet kan være i den kategorien.

_Tilbakestill_ Klikk på tilbakestill-knappen for å tilbakestille kolonnene til standardkolonnene

Basert på den konfigurerte kolonneradiusen vises de første kolonnene mens tabellen må rulle sideveis for å vise andre aktiverte kolonner. Standardrekkefølge og synlighetsinnstilling for kolonnene på dokumentsiden er som følger:

- Attributter
  - Enhet
  - GlobalId
  - LongName
  - Navn
  - ObjectType

Videre kan produkttabellen ha hvilket som helst antall kolonner avhengig av mengden egenskaper og egenskapsett som er i hver modell. Hvert sett med kolonner har en hovedkategori med underkategorier. Vekslebryteren kan brukes til å veksle hele kategorien av eller på. Kategorier kan utvides og hver kolonne i kategorien kan aktiveres/deaktiveres individuelt.

_Kolonnepreferanser_ I motsetning til andre tabellkonfigurasjoner er noen typiske preferanser som kan konfigureres låst i produkttabellen.

Kolonnepreferanser lagres ikke mellom øktene. Kolonner kan ikke endres rekkefølge, bare aktiveres og deaktiveres. Det er ikke mulig å sortere tabellen etter en annen kolonne ved å klikke på cellen i overskriftsraden for kolonnen. Det er ikke mulig å endre sorteringsretningen på kolonnen tabellen sorteres etter. Det er ikke mulig å dra cellen i overskriftsraden ut av tabellen for å deaktivere raden, rader må deaktiveres via kolonnenavigasjonen.
