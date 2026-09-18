# Eksporterer saker til PDF

Saker kan eksporteres til PDF ved å klikke på PDF-alternativet i [Eksporter saker-dialogen](https://support.catenda.com/en/articles/4670289-exchange-topics#h_aa0b8d7789). PDF-eksporten lar deg eksportere en rapport over sakene dine. Dette eksportalternativet er nyttig for å få en lett lesbar versjon av saker og kan brukes til arkivering eller rapportering til myndigheter.

Denne siden inneholder informasjon om følgende saker:

## 1. **Innstillinger som påvirker alle sider av PDF-en**

Disse innstillingene påvirker alle sider av PDF-en

### 1.1 **Logo**

Logoen øverst til venstre på hver side av PDF-en vil være Catenda-logoen som standard. Hvis du klikker på logoen eller på hub.catenda.com øverst til høyre, tas du til prosjektsiden. Det er mulig å laste opp en egendefinert logo på [prosjektinnstillingssiden](https://support.catenda.com/en/articles/4670273-project-settings-page) for å få din egen logo til å vises her.

### 1.2 **Språk**

PDF-eksporten vil være på det språket du har konfigurert i [kontoinformasjonen](https://support.catenda.com/en/articles/6880968-account-page#h_4aa257b72f).

### 1.3 **Saksordering**

Hvis du har sortert sakene i sakslisten din på noen måte, vil rekkefølgen sakene vises i rapporten gjenspeile rekkefølgen du har sortert sakslisten din.

## 2. **Forside**

Den nedlastede PDF-en vil inneholde en forside. Her vil du se profilbildet av prosjektet sammen med følgende eksportdetaljer: Forsiden kan se ut noe som dette:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/nx64p9qh/01-front-page.png)

### 2.1 **Prosjektnavn**

Navn på prosjektet

### 2.2 **Eksportert**

Antallet saker og fra hvilken saksliste de ble eksportert. Hvis du klikker på saklsistenavn, tas du til den sakslisten.

### 2.3 **Tidspunkt for eksport**

UTC-tidssone-tiden da PDF-eksporten ble foretatt.

### 2.4 **Oversikt over saker**

Under vil sakene som er del av denne eksporten bli opplistet. Hvis du klikker på navnet på saken, tas du til den saken på Catenda Hub.

## 3. **Sakssider**

En side for hver sak med alle detaljer for hver sak vil bli lagt til etter forsiden. En typisk saksside kan se ut som følgende:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/nx64p9qh/02-topic-pages.png)

### 3.1 **Tittel**

Tittelen på saken etterfulgt av nummeret på saken på Catenda.

### 3.2 **Inkludert metadata**

Følgende hoveder er inkludert:

_Type_ Typen av saken

_Status_ Statusen for saken

_Tildelt til_ Personen som er tildelt saken

_Opprettet av_ Opprettingen av saken

_Opprettet_ Tiden saken ble opprettet for første gang

_Lukket på_ Hvis saken er lukket, vises det siste tidspunktet for lukking av saken her.

_Frist_ Fristen

_Egendefinerte felt fra sakslisten_ Hvert egendefinert felt og verdien dersom det finnes noen er inkludert

_Merkelapper_ Merkelapper er opplistet med navn og farge.

### 3.3 **Ekskluderte sakhoveder**

_Milepæl_ Milepæler er ikke inkludert i PDF-eksporten.

_Markør_ Klikk [her](https://support.catenda.com/en/articles/4854523-2d-location-of-topics) for å lese mer om eksporteringen av 2D-plassering til PDF.

### 3.4 **Sakskoblinger**

Lenker til saksrelasjoner på Catenda er inkludert i PDF-eksporten. De relaterte elementene blir ikke eksportert automatisk, så vurder å eksportere denne informasjonen separat.

_Saker_ Hvis saker er koblet til den eksporterte saken, listes hver sak med en lenke til den saken på Catenda.

> **Merk:** Disse sakene er ikke nødvendigvis inkludert i rapporten da de kan være fra en annen saksliste med andre tilgangsinnstillinger.

_Dokumenter_ Hvis det finnes dokumenter som er koblet til saken, vil du se dem opplistet her med lenker til hvert dokument i Catenda.

### 3.5 **Beskrivelse**

Beskrivelsen av saken

### 3.6 **Kommentarer**

Hvis noen kommentarer er blitt lagt til saken, vil du se dem her. Først vil du se brukernavnet på kommentarforfatteren og datoen da han/hun postet kommentaren, etterfulgt av alle vedlagte bilder og teksten i kommentaren.

## 4. **Rapportside**

Med rapportsiden er det mulig å lage egendefinerte rapporter om ikke bare saker, men også dokumenter. Rapportsiden er en etterspørselsfunksjon som kan forespørres aktivert for pågående prosjekter. Nye prosjekter som opprettes basert på et malprosjekt der denne funksjonen er aktivert, har ikke denne funksjonen aktivert. Disse rapportene kan deretter eksporteres ikke bare til Excel og PDF, men også mange flere filformater. Disse rapportene kan også eksportere saker fra flere sakslister samtidig. Klikk [her](https://support.catenda.com/en/articles/12303098-reports-page) for å lese mer om rapportsiden
