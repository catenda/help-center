# Feilsøking på gjennomgangssiden

## 1. **Innsending av en ny gjennomgangsforespørsel**

Når en ny gjennomgangsforespørsel sendes inn for vurdering der mer enn 1000 dokumenter legges til med knappen for å legge til dokumenter, vises følgende feil:

![Feil ved ny gjennomgang Workflow standardarbeidsflyt Innsender Tittel](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/01-submitting-a-new-approval-request.png)

Det er bare mulig å sende inn dialogen for ny gjennomgangsforespørsel med opptil 1000 dokumenter om gangen. For å sende inn en gjennomgangsforespørsel med mer enn 1000 dokumenter, legger du først til opptil 1000 dokumenter i dialogen for ny gjennomgangsforespørsel og lagrer som utkast. Gå til utkastsiden for gjennomgang av dokumentet og legg til så mange dokumenter som ønsket før du sender inn gjennomgangsforespørselen.

## 2. **Oversiktsfanen – Lukking av en gjennomgangsforespørsel**

Når en gjennomgang lukkes, kan publiseringen mislykkes. I [oversiktsfanen](https://support.catenda.com/en/articles/12495126-overview-tab-in-an-approval-request) for gjennomgangen kan følgende ses:

![Publisering mislyktes Publiserte 1 dokument. Kunne ikke oppdatere 1 dokument vis detaljer](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/02-overview-tab-closing-an-approval-request.png)

### 2.1 **Det finnes allerede en publisert revisjon**

Det er bare mulig å publisere delte revisjoner i dokumenter der den nyeste revisjonen er en delt revisjon. Hvis revisjonen i gjennomgangen, eller en annen delt revisjon etter den tidligere publiserte revisjonen ble publisert og et nytt hovedrevisjonsnummer ble opprettet, kan denne revisjonen ikke bli det neste hovedrevisjonsnummeret fordi det allerede finnes og vil mislykkes. En delt revisjon kan ha blitt publisert som et resultat av lukkingen av en annen gjennomgangsforespørsel eller ved å bruke publiser-handlingen i dokumenttabellen eller i revisjonsinformasjonen i høyre meny for en revisjon.

## 3. **Dokumenter-fanen**

### 3.1 **Dokument ikke funnet**

Hvis et dokument som er en del av en gjennomgang slettes, kan det ikke lenger finnes og innholdet i dokumentet vises ikke lenger på siden for filgjennomgang. Slik kan dokumentfanen se ut når et dokument som er en del av en gjennomgang har blitt slettet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/03-document-not-found.png)

Dokumenter som ble lagt til en gjennomgangsforespørsel og senere slettet, kan enten gjenopprettes av en administrator eller forkastes fra gjennomgangsforespørselen.

### 3.2 **Trukket tilbake revisjon**

Hvis en dokumentrevisjon som er en del av en gjennomgang trekkes tilbake, er revisjonsnummeret gjennomstreket og innholdet i dokumentet vises ikke lenger på siden for filgjennomgang. Slik kan dokumentfanen se ut når et dokument som er en del av en gjennomgang har blitt slettet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/04-withdrawn-revision.png)

Dokumentrevisjoner som ble lagt til en gjennomgangsforespørsel og senere trukket tilbake, kan forkastes fra gjennomgangsforespørselen.
