# Oversikt-fanen i en gjennomgangsforespørsel

Oversikt-fanen for en gjennomgangsforespørsel finner du på gjennomgangsforespørselssiden for [åpne eller lukkede](https://support.catenda.com/en/articles/12494960-open-or-closed-approval-request-page) gjennomganger. I oversikt-fanen finner du en oversikt over et valgt gjennomgangsvaluering-trinn. I trinnet kan du se valideringene som er angitt og sendt inn av et medlem på vegne av hvert innsendings-team som er konfigurert til å vurdere trinnet. For en oversikt over innsendte valideringer for alle trinnene, se [dokumenter-fanen](https://support.catenda.com/en/articles/8349418-approval-page#h_133b2690af).

> **Merknad:** **Utseende og funksjonalitet –** Slik kan oversikt-fanen i gjennomgangsinnholdet se ut for prosjekter som aktiverte delte revisjoner etter 2. oktober 2025:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/01-intro.png)

## 1. Gjennomgangsforespørsel-trinn-bånd

I trinn-båndet kan du se en forhåndsvisning av fremdriften for gjennomgangsforespørselen. Slik kan trinn-båndet se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/02-approval-request-step-ribbon.png)

Klikk [her](https://support.catenda.com/en/articles/12495212-step-ribbon-in-an-approval-request) for å lese mer om trinn-båndet

## 2. Gjennomgangsforespørsel-trinn rullegardin

Slik kan rullegardin for gjennomgangsforespørsel se ut når en gjennomgangsforespørsel har kommet til det endelige gjennomgangs-trinnet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/03-approval-step-dropdown.png)

Det nåværende og alle avsluttede gjennomgangs-trinnene er oppført i rullegardin for gjennomgangsforespørsel-trinn. Velg et gjennomgangs-trinn i listen for å se statusen for valideringene gitt av hvert av de teamene som er konfigurert for trinnet. En oversikt over valideringene i alle trinnene finner du i dokumenter-fanen.

## 3. Under vurdering-tabell

I tabellen under vurdering kan du se dokumenter som ennå ikke er sendt inn. Slik kan tabellen under vurdering se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/04-under-review-table.png)

Medlemmer som er del av teams som er konfigurert som vurderings-teams for dette gjennomgangsforespørsel-trinnet, vil se en rad per konfigurert vurderings-team de er del av. I det aktive gjennomgangsforespørsel-trinnet, hvis det fortsatt er valideringsangivelser igjen å sende inn på vegne av noen av vurderings-teamene et medlem er del av, vises en gul strek øverst.

Når alle dokumenter er vurdert og valideringsangivelser er sendt inn på vegne av hvert av vurderings-teamene, blir streken øverst grønn og får en hake.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/05-under-review-table.png)

> **Merknad:** At streken er grønn betyr bare at det ikke er noen teams du er del av som har noen handlinger igjen i dette gjennomgangsforespørsel-trinnet, det kan være andre teams som fortsatt må sende inn sine valideringsangivelser før gjennomgangsforespørselen kan gå videre til neste trinn. Disse kan du se i trinn-oversikt-tabellen nedenfor.

### 3.1 Kolonner i tabellen under vurdering

_Team_ Navn på vurderings-teams som er konfigurert for dette gjennomgangs-trinnet i gjennomgangs-arbeidsflyten valgt for denne gjennomgangsforespørselen av innsenderen av gjennomgangsforespørselen. _Kreves tilgang:_ Medlem av vurderings-team

_Ventende_ Antallet dokumenter som ennå ikke har mottatt en valideringsangivelse i dette gjennomgangsforespørsel-trinnet. _Kreves tilgang:_ Medlem av vurderings-team Vurdering Klikk på vurdering for å åpne filgjennomgangen for dokumenter som ennå ikke har mottatt en valideringsangivelse eller innsendelseKlikk på innsendingsknappen for å sende inn alle valideringsangivelsene på vegne av vurderings-teamet på en gang. En gang valideringsangivelsen er sendt inn, vil dokumentet ikke lenger være under vurdering og vil forsvinne fra tabellen under vurdering.

_Vurdert_ I vurdert-kolonnen vises beløp for avviste og godkjente valideringsangivelser. Ethvert medlem av et vurderings-team kan ha gitt denne angivelsen på vegne av vurderings-teamet. _Kreves tilgang:_ Medlem av vurderings-team Send inn Valideringsangivelser som medlemmer av vurderings-team har gitt på vegne av et vurderings-team kan sendes inn med innsendingsknappen. Klikk på innsendingsknappen for å sende inn alle valideringsangivelsene på vegne av vurderings-teamet på en gang. En gang valideringsangivelsen er sendt inn, vil dokumentet ikke lenger være under vurdering og vil forsvinne fra tabellen under vurdering.

## 4. Trinn-oversikt-tabell

I trinn-oversikt-tabellen kan du se en oversikt over fremdriften for alle vurderings-teamene for dette trinnet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/06-step-overview-table.png)

Når valideringsangivelser er sendt inn for alle dokumenter, går gjennomgangsforespørselen videre til neste gjennomgangsforespørsel-trinn. Automatisk godkjenning kan konfigureres i arbeidsflyten som innsenderen av gjennomgangsforespørselen valgte for denne gjennomgangsforespørselen. Hvis automatisk godkjenning er aktivert for et gjennomgangsforespørsel-trinn, godkjennes alle dokumenter som fortsatt venter når gjennomgangsforespørsel-trinnet forfaller automatisk, og gjennomgangsforespørselen går videre til neste gjennomgangsforespørsel-trinn.

### 4.1 Kolonner i trinn-oversikt-tabellen

**_Team_ —** Navn på vurderings-teams som er konfigurert for dette gjennomgangs-trinnet i arbeidsflyten valgt for denne gjennomgangsforespørselen.

**_Ventende_ —** Antallet dokumenter der et medlem av vurderings-teamet ennå ikke har sendt inn en valideringsangivelse på vegne av vurderings-teamet i dette gjennomgangsforespørsel-trinnet.

**_Under vurdering –_** _Antallet dokumenter som er godkjent eller avvist, men ikke ennå sendt inn. Når ikke sendt inn, men tilgjengelig for innsendelseknappen, er knappen "Send inn" mørkegrønn._

**_Sendt inn_ —** Antallet godkjente angivelser som er sendt inn av et medlem av vurderings-teamet på vegne av et vurderings-team i dette gjennomgangsforespørsel-trinnet.

**_Team Progress_ —** Fremdriften for valideringsangivelser som er sendt inn av et medlem av vurderings-teamet på vegne av et vurderings-team i dette gjennomgangsforespørsel-trinnet.

## 5. Gjennomgangsforespørsel-resultat

Etter at det endelige vurderings-teamet sender inn den endelige valideringen for alle dokumenter, lukkes gjennomgangsforespørselen og dokumentene begynner publisering:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/07-approval-request-result.png)

Resultatet av gjennomgangen vises under trinn-oversikten:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/08-approval-request-result.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/09-approval-request-result.png)

Klikk [her](https://support.catenda.com/en/articles/12520773-approvals-troubleshooting) for å lese mer om hvorfor publisering av dokumenter kan mislykkes.

### 5.1 Se detaljer

Klikk på Se detaljer for å se publiseringsresultatene for hvert dokument.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/10-view-details.png)

_Status_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0se83h1m/11-view-details.png)

Statusen for publisering av dokumentet. Statusen kan være en av følgende:

_Publisert_ For dokumenter som fikk endelig godkjenning, vises revisjons-nummeret for den delte revisjonen med en pil til den publiserte revisjonen som ble opprettet som resultat av publisering av denne delte revisjonen.

_Publisering mislyktes_ For dokumenter som fikk endelig godkjenning, men som ikke kunne publiseres, vises grunnen til at de ikke kunne publiseres.

_Angi status_ For dokumenter som fikk endelig avvisning, vises statusen som revisjonen ble oppdatert med som resultat.

**_Navn_** Følgende vises i navn-kolonnen:

- Dokumentfilsti
- Dokument-ikon
- Revisjons-navn for dokumentet
