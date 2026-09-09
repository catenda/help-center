# Mappekonfigurasjon - Dokumentinnstillinger

Menyen for mappekonfigurasjon finner du på siden [dokumentinnstillinger](https://support.catenda.com/en/articles/7831371-document-settings-page). Ved å konfigurere en mappe kan du forbedre hvordan dokumenter håndteres i den arbeidsflytingen.

## 1. **Mappetabell**

Mapper kan konfigureres i mappetabellen som kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/01-folders-table.png)

### 1.1 **Filter for konfigurerte mapper**

Øverst i tabellen finner du et filter for konfigurerte mapper.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/02-configured-folders-filter.png)

_Alle mapper_ Se alle mapper i prosjektet.

_Konfigurerte mapper_ Se hvilke mapper som er konfigurert i prosjektet

### 1.2 **Mappekolonne**

Her ser du alle mapper i prosjektet. Hvis du klikker på pilen eller et annet sted i denne kolonnen, ekspanderes mappen slik at du ser undermappene. Hvis du holder musepekeren over ikonet eller navnet på en mappe, vil du se et lenkeikon som du kan klikke for å åpne mappen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/03-folders-column.png)

Dette kan hjelpe mye når du skal se resultatene av den konfigurerte mappen etter at du har konfigurert den.

_Legg til konfigurasjon_ Klikk på +-knappen til høyre for en mappe for å åpne [mappekonfigureringsdialogen](#h_96b6c91fe4). Hvis det er konfigurasjoner i undermapper, kan du ikke lage en konfigurasjon for mappen.

_Forhåndsvis konfigurasjon_ Hvis en konfigurasjon er angitt for en mappe, kan du raskt se hvilken konfigurasjon som er angitt ved å klikke på øyeikonet. Forhåndsvisningen av konfigurasjonen kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/04-folders-column.png)

_Rediger konfigurasjon_ Hvis en konfigurasjon er angitt for en mappe, kan du redigere den ved å klikke på blyant-ikonet.

_Konfigurasjonsarv_ Hvis en konfigurasjon er angitt i en overordnet mappe, arver alle undermappene konfigurasjonen.

### 1.3 **Navnekonvensjonskolonne**

Her ser du hvilke navnekonvensjonsblokker som er konfigurert for en rad

### 1.4 **Kolonne for egendefinerte felt**

Her ser du hvilke egendefinerte felt som er konfigurert for en rad

## 2. **Mappekonfigureringsdialog**

Mappekonfigureringsdialogen kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/05-folder-configuration-dialogue.png)

### 2.1 **Navnekonvensjon**

Hvis du har angitt navnekonvensjoner på siden [navnekonvensjon](https://support.catenda.com/en/articles/7832559-naming-conventions-page) i [prosjektinnstillinger](https://support.catenda.com/en/articles/4670273-project-settings-page), kan du velge hvilken mappe navnekonvensjonen skal brukes på her. Når du bruker en konvensjon, må alle nye dokumenter i mappen og undermappene:

- Være navngitt i henhold til navnekonvensjonen
- Ha et dokumentnavn som ikke kan redigeres mens konvensjonen er aktiv
- Forbli i mappen de ble lastet opp til og kan ikke flyttes

Hvis du vil fjerne en navnekonvensjon, trykker du på X.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/06-naming-convention.png)

### 2.2 **Egendefinerte felt**

Med egendefinerte felt kan du tilordne egendefinerte felt til alle dokumenter i denne konfigurasjonen. Egendefinerte felt kan enten angis for hele dokumentet eller for hver revisjon. _Tilgang som kreves for å endre feltet:_ Skriv

_Egendefinerte dokument-felt_

- Verdier vil bli lagret på dokumentet
- Eksempel på egendefinerte felt: "Dokumentbeskrivelse", "Dokumentnotat" osv...

_Egendefinerte revisjons-felt_

- Verdier vil bli lagret på hver revisjon av dokumentet
- Bare verdier lagret på den nyeste revisjonen vil bli vist sammen med dokumentet.
- Eksempler på egendefinerte felt: "Revisjonskommentar", "Godkjenningsstatus" osv...

_Navn_ Navnet på det egendefinerte feltet

_Type_ Typen egendefinert felt. Følgende typer egendefinerte felt kan gjøres tilgjengelige for mapper: Dato Desimal Rullegardin Heltall Tekst

_Er obligatorisk_ Hvis et felt er obligatorisk, må det alltid ha en verdi.

> **Merk:** En standardverdi må angis fordi dokumentet må ha en verdi ved opplasting.

_Standardverdi_ Hvis en standardverdi er angitt, blir denne verdien satt for feltet for alle dokumenter lastet opp etter at konfigurasjonen er bekreftet, med mindre den endres senere.

## 3. **Tilordne QR-kode**

Med [QR-kodestamping](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda) kan du velge om du vil aktivere denne funksjonen for en mappe her.
