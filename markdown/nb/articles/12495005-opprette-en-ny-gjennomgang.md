# Opprette en ny gjennomgang

Den nye gjennomgangsforespørsel kan finnes for prosjekter som aktiverte delte revisjoner etter 2. oktober 2025. Klikk på handlingsmenyen til høyre for den grønne plusknappen på [gjennomgangssiden](https://support.catenda.com/en/articles/8349340-approvals-page) for å opprette en ny gjennomgangsforespørsel. Klikk på knappen for ny gjennomgangsforespørsel i gjennomgangsmenyen på høyre side av en revisjon på dokumentsiden der den nyeste revisjonen er en delt revisjon for å opprette en ny gjennomgangsforespørsel. Slik kan dialogen for å opprette en ny gjennomgangsforespørsel se ut:

![Ny godkjenningsforespørsel Arbeidsflyt Innsender Tittel Beskrivelse (valgfritt) Dokumenter til vurdering legg til dokumenter navn revisjon # Revisjonsnummer Status Fjern Avbryt Lagre som utkast Send til vurdering](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/01-intro.png)

Prosjekter der delte revisjoner ble aktivert før 2. oktober 2025, vil se dialogen for eldre gjennomgangsforespørsel i stedet.

## 1. Gjennomgangsforespørsel-topptekst

Slik kan toppteksten for en ny gjennomgang se ut for prosjekter som aktiverte delte revisjoner etter 2. oktober 2025:

![Ny godkjenningsforespørsel Arbeidsflyt Innsender Tittel](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/02-approval-request-header.png)

### 1.1 **Arbeidsflytvalg**

Medlemmer som er del av innsenderteam som er konfigurert i en projektarbeidsflyt, kan velge mellom en av arbeidsflytene som teamene er konfigurert for. Arbeidsflyten som ble valgt tidligere, blir husket. Så lenge arbeidsflyten som ble valgt tidligere fortsatt er tilgjengelig, vil den bli valgt igjen neste gang en gjennomgang opprettes.

_Automatisk valg_ Hvis bare ett av teamene som et medlem er del av, er konfigurert for en arbeidsflyt, vil arbeidsflyten bli valgt automatisk. Slik kan det se ut når arbeidsflyten velges automatisk.

![Arbeidsflyt Innsender Tittel](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/03-workflow-selection.png)

_Tilgang påkrevd:_ Medlemmer og administratorer må være del av et innsenderteam som er konfigurert for en arbeidsflyt for å kunne velge arbeidsflyten.

### 1.2 **Innsendervalg**

Etter at en arbeidsflyt er valgt, kan medlemmer som er del av flere innsenderteam som er konfigurert for arbeidsflyten, velge på vegne av hvilket team de vil sende gjennomgangsforespørselen. Innsendertemaet som ble valgt tidligere, blir husket. Så lenge medlemmet fortsatt er del av det innsenderteamet som ble valgt tidligere, vil det bli valgt igjen neste gang en gjennomgang opprettes.

Når gjennomgangsforespørselen opprettes, vil medlemmer som er del av det valgte innsenderteamet se forespørselen, mens medlemmer som er del av de andre mulige innsenderteamene bare vil se forespørselen hvis de er del av ett av vurderingsteamene eller del av det endelige gjennomgangsteamet som er konfigurert for arbeidsflyten.

_Automatisk valg_ Hvis et medlem bare er del av ett av innsenderteamene som er konfigurert for arbeidsflyten, velges innsenderteamet automatisk når arbeidsflyten velges.

![Arbeidsflyt Innsender Tittel](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/04-submitter-selection.png)

_Tilgang påkrevd:_ Medlemmer og administratorer må være del av et innsenderteam som er konfigurert for en arbeidsflyt for å kunne sende på vegne av det innsenderteamet.

### 1.3 **Tittel**

Tittelen på gjennomgangsforespørselen. En gjennomgang må ha en tittel for å kunne sendes.

## 2. **Gjennomgangsforespørsel-brødtekst**

Den nye valideringsarbeidsflyten er en on-demand-funksjon som kan forespørres aktivert når du starter et nytt prosjekt. Det er bare mulig å opprette et prosjekt basert på et malprosjekt når den nye valideringsarbeidsflyten ikke er aktivert i det malprosjektet. Slik kan brødteksten for en ny gjennomgang se ut for prosjekter som aktiverte delte revisjoner etter 2. oktober 2025:

![Godkjenningsforespørsel brødtekst Beskrivelse (valgfritt) Dokumenter til vurdering legg til dokumenter avbryt ingen dokumenter lagt til ennå](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/05-approval-request-body.png)

### 2.1 **Beskrivelse**

Beskrivelsen av gjennomgangen følger [de generelle formateringsreglene for innlegg](https://support.catenda.com/en/articles/8430847-formatting-of-posts).

### 2.2 **Legg til dokumenter**

![Beskrivelse (valgfritt) dokumenter til vurdering legg til dokumenter](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/06-add-documents.png)

Klikk [her](https://support.catenda.com/en/articles/12382093-add-revision-to-approval) for å lese mer om å legge til delte revisjoner fra dokumenter til en gjennomgangsforespørsel. Selv om det er mulig å legge til et uendelig antall dokumenter her, er grensen for sending av gjennomgangsforespørselen til vurdering 1000 dokumenter.

### 2.3 **Dokumenter for vurderingstabell**

Slik kan tabellen for dokumenter for vurdering se ut etter at delte revisjoner i hvert dokument som skal valideres har blitt lagt til:

![Dokumenter vurderingstabell Navn revisjon # Revisjonsnummer Status Fjern Avbryt Lagre som utkast Send til vurdering](https://raw.githubusercontent.com/catenda/help-center/main/images/4e7kgq0a/07-documents-for-review-table.png)

_Kolonner_ Basert på den konfigurerte kolonneordenen vises de første kolonnene, mens tabellen kanskje må rulles sidelengs for å vise andre aktiverte kolonner. Standardordenen og synlighetsinnstillingen for kolonnene på dokumentsiden er som følger:

_Navn_ - _Standard_ Navnet på dokumentet som den delte revisjonen er i. Dokumentnavnet er det samme for alle revisjoner i dokumentet.

Revisjon - _Standard_ Navnet på dokumentrevisjonen. Dette er det samme som det opprinnelige filnavnet på filen som ble lastet opp.

## 3. - _Standard_

Status - _Standard_ Navnet på den delte statusen som brukes på den delte revisjonen.

Fjern - _Standard_ Klikk på x-en i fjern-kolonnen for å fjerne dokumentet som skal vurderes fra listen for dokumenter for vurdering.

## 4. **Lagre som utkast**

Rediger gjennomgangsforespørselen før den sendes og låses.

### 4.1 **Mer enn 1000 dokumenter i utkast**

Selv om det er mulig å legge til så mange dokumenter til dialogen for å legge til revisjon til gjennomgangsforespørsel, er det bare mulig å sende dialogen med opptil 1000 dokumentrevisjoner. For å legge til mer enn 1000 dokumentrevisjoner med den nye valideringsarbeidsflyten, legger du først til opptil 1000 dokumenter og lagrer gjennomgangsforespørselen som utkast. Legg deretter til opptil 1000 dokumenter om gangen til utkast-gjennomgangsforespørselen med handlingene for å legge til dokumenter på siden for utkast-gjennomgangsforespørsel før du sender utkast-gjennomgangsforespørselen.

### 4.2 **Start vurderingsvarighet for trinn 1 når klar**

Så snart gjennomgangsforespørselen sendes, vil vurderingsteamene som er konfigurert i det første trinnet av den valgte gjennomgangsarbeidsflyten få i oppdrag å vurdere revisjonene i gjennomgangsforespørselen i løpet av varigheten av sitt gjennomgangstrinn. Medlemmene i vurderingsteamene vil kunne vurdere revisjonene til arbeidsdagene som er konfigurert for gjennomgangstrinnet deres, er over. Lagre en gjennomgangsforespørsel som utkast slik at den kan sendes så snart arbeidsflyten er klar til å begynne.

Sørg for at teamene er klar ved å kommunisere at deres vurderingstrinn er i ferd med å begynne før du sender gjennomgangsforespørselsarbeidsflyten og starter vurderingsvarhigheten for det første trinnet for vurderingsteamene som er konfigurert i den valgte arbeidsflyten.

Sørg for at den endelige publiseringsdatoen for arbeidsflyten ender på rett tid ved å sørge for at du justerer det totale antallet arbeidsdager i arbeidsflyten med dagene for når arbeidsflyten skal sendes.

## 5. **Send til vurdering**

Klikk på Send til vurdering for å sende gjennomgangen og starte gjennomgangsprosessen. Følgende er påkrevd for å sende gjennomgangsforespørselen til vurdering:

- Arbeidsflyten som gjennomgangsforespørselen skal følge, må velges.
- Et innsenderteam som skal sende på vegne av, må velges
- En tittel
- Dokumenter
  - Minst 1 dokument med en valgt delt revisjon må legges til for å kunne sende gjennomgangen.
  - Maksimalt 1000 dokumentrevisjoner med en valgt delt revisjon kan legges til.
  - For å opprette en gjennomgangsforespørsel med mer enn 1000 dokumentrevisjoner, oppretter du først et utkast med opptil 1000 revisjoner, og deretter legger du til opptil 1000 dokumentrevisjoner om gangen til utkastet før du sender utkastet til vurdering.

Etter sending av en gjennomgangsforespørsel til vurdering med den nye valideringsarbeidsflyten er det eneste som kan endres at delte revisjonsdokumenter kan kastes fra forespørselen.

_Start vurderingsvarighet for trinn 1 når klar_ Så snart gjennomgangsforespørselen sendes, vil varigheten av det første vurderingstrinnet som er konfigurert i gjennomgangsarbeidsflyten begynne.
