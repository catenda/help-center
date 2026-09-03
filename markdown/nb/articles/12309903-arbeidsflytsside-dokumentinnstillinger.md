# Arbeidsflytsside - Dokumentinnstillinger

Arbeidsflytsiden finnes ved å klikke på knappen Konfigurer arbeidsflyter i menyen Gjennomganger på [siden for dokumentinnstillinger](https://support.catenda.com/en/articles/7831371-document-settings-page) i prosjekter der den nye valideringsarbeidsflyten er bedt aktivert og delte statuser er aktivert i statusarbeidsflytsmenyen for [dokumentinnstillinger](https://support.catenda.com/en/articles/7831371-document-settings-page). Den nye valideringsarbeidsflyten er en funksjon etter forespørsel som kan aktiveres når du starter et nytt prosjekt. Det er bare mulig å opprette et prosjekt basert på et malprosjekt når den nye valideringsarbeidsflyten ikke er aktivert i det malprosjektet. På arbeidsflytsiden kan arbeidsflyter for ulike gjennomgangskonfigurasjoner konfigureres. _Tilgang kreves:_ Administrator

Arbeidsflytsiden kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/01-intro.png)

Følgende saker vil bli beskrevet i denne artikkelen:

_[Nye elementhandlinger](https://support.catenda.com/en/articles/8204673-documents-page#h_d0f4a44fb7) - [Søk eller filtrer](https://support.catenda.com/en/articles/8204673-documents-page#h_bbf4dcad58) - [Høyre meny](https://support.catenda.com/en/articles/8204673-documents-page#h_fc89aaa1fe) - [Tabell](https://support.catenda.com/en/articles/8204673-documents-page#h_54e8dfcac2) - [Undersider](https://support.catenda.com/en/articles/8204673-documents-page#h_5751ccd2b7)_

Selv om arbeidsflytsiden er en underside til gjennomgangssiden som framgår av at gjennomgangssiden er uthevet og brødsmulen øverst, er siden bare tilgjengelig fra gjennomgangsmenyen i dokumentinnstillinger.

## 1. **Nye elementhandlinger**

De nye elementhandlingene finner du øverst til høyre på siden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/02-new-item-actions.png)

Se her for hva de ulike handlingene gjør.

## 2. **Søk- eller filteralternativer**

Slik kan søk- eller filtermenyen se ut på arbeidsflytsiden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/03-search-or-filter-options.png)

I søkebaren kan alle arbeidsflyter som er tilgjengelige på arbeidsflytsiden søkes.

### 2.1 **Filtrer venstra panel**

Ved å klikke på filterknappen vises et panel på venstre side. Merk av i boksene for å begrense søket. Når noen av disse filtrene brukes, legges filterteksten til i nettadressen din. Hvis nettadressen til den filtrerte siden deles, vil personen som åpner den, se de samme resultatene som vises for øyeblikket, så lenge de har tilgang til dem.

### 2.2 **Filtre**

> **Merk:** Nettadressen til nettsiden endres avhengig av hvilke filtre som er brukt. Dette gjør at den gjeldende filtrerte dokumenttabellen kan deles med andre medlemmer som er del av prosjektet.

Hvis flere av de samme filtrene er valgt, skilles de med `,` eller `%2C` Hvis flere filtre er valgt, skilles de med `&` eller `%26` Ulike filtre og deres URL-ekvivalenter:

_Status_ Aktiv - Standard - `status=active` Arkivert - `status=archived `

> **Merk:** Det er bare mulig å vise enten aktive eller arkiverte arbeidsflyter, ikke begge samtidig

_Søk_ Tekstsøk - `search=test` Som standard samsvarer tekstsøket bare med aktive arbeidsflyter. For å søke i arkiverte statuser, filter først på arkivert og bruk deretter tekstsøket.

## 3. **Arbeidsflytstabel**

Arbeidsflytstabellen kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/04-workflows-table.png)

Klikk [her](https://support.catenda.com/en/articles/11748020-tables-on-catenda) for å lese mer om hvordan du arbeider med tabeller i Catenda. Så snart en arbeidsflyt opprettes, vises den som en rad i arbeidsflytstabellen.

### 3.1 **Radinnhold**

_Arbeidsflytrad_ Når du åpner innholdet i en arbeitsflytrad, åpnes arbeidsflytsiden for denne arbeidsflyten. Slik kan en arbeitsflytside se ut når den er åpnet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/05-row-content.png)

På arbeidsflytsiden for en arbeitsflyt er det mulig å se hvordan arbeidsflyten er blitt konfigurert.

Tittel Den eneste delen av arbeidsflyten som kan redigeres, er navnet på arbeidsflyten.

Tidssone Hvis en tidssone er valgt for arbeidsflyten, forblir den den samme hele året. Hvis en geografisk plassering er valgt for arbeidsflyten, endres GMT-offsetten avhengig av hvilken tidssone som er aktiv for den geografiske plasseringen.

Oppdater Klikk på oppdater for å oppdatere tittelen.

### 3.2 **Kolonner**

Noen kolonner i arbeidsflytstabellen er aktivert som standard mens andre kan skjules og må aktiveres. Basert på den konfigurerte kolonneordenen vises de første kolonnene mens tabellen kanskje må rulles sideveis for å vise andre aktiverte kolonner. Standardrekkefølgen og synlighetsinnstillingen for kolonnene på arbeidsflytsiden er som følger:

Tittel - _Standard_ Tittelen på arbeidsflyten

Opprettet av - _Standard_ Medlemmet som opprettet arbeidsflyten.

Opprettet den - _Standard_ Dato og tid da arbeidsflyten ble opprettet

Status - _Standard_ Status for arbeidsflyten
