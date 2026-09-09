# Solibri-modeller og dokumentintegrering

Dokumenter-API-integreringen gir en enkel måte å få tilgang til innholdet som er lagret i skyen. Du kan koble deg til et felles datamiljø (CDE) og laste ned og laste opp modeller fra/til serveren.

## 1. **Kobler til**

Dokumenter-API-en finnes på integrasjonmenyen på Fil-fanen i Solibri. For å komme i gang med API-en for dokumenter må du først gi Solibri tilgang til Catenda-kontoen din. For å gjøre det, klikker du på Koble til.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/01-connecting.png)

Listen over servere du kan koble deg til begynner nå å lastes inn.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/02-connecting.png)

Første gang du starter Solibri kan denne listen ta en stund å laste. Etter første lasting lagres listen og vil åpnes raskere. I den resulterende nedtrekksmenyen kan du velge Catenda eller Bimsync for å koble til Catenda-dokumenter-API-en.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/03-connecting.png)

## 2. **Importerer dokumenter eller modeller**

Klikk på Åpne for å importere dokumenter eller modeller som du har tilgang til i Catenda Hub.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/04-importing-documents-or-models.png)

Etter at du har klikket på åpne, åpnes standardnettleseren din.

- [Avbryt nettleserøkten din](#h_e921d649ed) hvis du ønsker å avbryte denne prosessen og fortsette å arbeide med Solibri
- Hvis du ikke allerede har gjort det, [gi tilgang til kontoen din](#h_55ca1d4d10).
- Hvis du ennå ikke har valgt et prosjekt, velger du et prosjekt på [prosjektsiden](#h_343870704c).
- Etter å ha valgt et prosjekt, eller hvis du tidligere har valgt et prosjekt, kan du velge [dokumentersiden](#h_b7ac757915) (_standard_) eller [modellsiden](#h_617a3f8bf6).

## 3. **Eksporterer Solibri-økt til Catenda**

For at knappen Last opp modell skal bli tilgjengelig må du ha [koblet til Catenda-kontoen din](#h_457cbf4e9d) og har minst én fil i Solibri-økten din. Klikk på Last opp modell for å eksportere Solibri-økten din som en del av Catenda-prosjektet du har tilgang til.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/05-exporting-solibri-session-to-catenda.png)

Hvis du ennå ikke har lagret Solibri-økten din, eller gjort noen endringer siden du sist lagret, blir du bedt om å lagre en .smc-fil slik at den kan lastes opp.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/06-exporting-solibri-session-to-catenda.png)

Den .smc-filen som har blitt lagret kan nå eksporteres som en ny revisjon til Catenda og importeres senere til Solibri igjen hvis du ønsker å fortsette økten din med den siste revisjonen. Etter at du har lagret .smc-filen klikker du på last opp modell igjen.

Etter å ha klikket på Last opp modell, åpnes standardnettleseren din.

- [Avbryt nettleserøkten din](#h_e921d649ed) hvis du ønsker å avbryte denne prosessen og fortsette å arbeide med Solibri
- Hvis du ikke allerede har gjort det, [gi tilgang til kontoen din](#h_55ca1d4d10).
- Hvis du ennå ikke har valgt et prosjekt, velger du et prosjekt på [prosjektsiden](#h_343870704c).
- Etter å ha valgt et prosjekt, eller hvis du tidligere har valgt et prosjekt, presenteres du for [dokumentersiden](#h_b7ac757915).

## 4. **Solibri-dokumentintegrasjon -** Prosjektsiden

Etter å ha klikket på åpne og logget på, hvis du nettopp ga tilgang eller tidligere har gitt tilgang, åpnes en side som ligner prosjektsiden i Catenda Hub som en ny side i standardnettleseren din. Solibri-dokumentintegrasjonsprosjektsiden kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/07-solibri-document-integration-projects-page.png)

> **Merknad:** Denne siden er opprettet av Solibri og er ikke det samme som den vanlige prosjektsiden i Catenda Hub. Bare modell- og dokumentdelsene av Catenda kan navigeres til. Catenda Hub-funksjonalitet som dokumentforhåndsvisning og tilgangskonfigurering fungerer ikke her.

## 5. **Solibri-dokumentintegrasjon -** dokumenterside

Se dokumentene du har tilgang til med Catenda-kontoen din på dokumentersiden av Solibri-dokumentintegreringen. Her kan du konfigurere hvilke dokumenter som skal synkroniseres med Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/08-solibri-document-integration-documents-page.png)

### 5.1 **Navigasjon**

Klikk på navnet på prosjektet hvis du ønsker å navigere til et annet prosjekt. Klikk på modeller på venstremeny for å importere etter modell i stedet for etter dokument.

> **Merknad:** Modellsiden er bare tilgjengelig ved nedlasting.

### 5.2 **Dokumentstruktur**

For hvert dokument vil du se:

- Filterikon for filtype
- Dokumentnavn
- Revisjonsnummer
- Dokumentstatus
- Merkelapper (klikk på de 3 prikkene for å se flere merkelapper)
- Filstørrelse
- Siste revisjons skaper
- Publiseringsdato for siste revisjon
- 3D-knapp (Forhåndsvis modell før du importerer)
- Objektlenker (Velg lenket objekter i 3D-forhåndsvisningen ved å klikke på dette tallet)

Velg et sett med dokumenter ved å merke av i boksene, eller merk av boksen øverst for å velge alle.

### 5.3 **Høyre informasjonsmeny**

Etter valg vises informasjonsmenyen øverst til høyre. Hvis den er lukket, klikker du på `i`-ikonet for å utvide det.

### 5.4 **Høyre informasjonsmeny -** Last ned

Når du importerer kan du konfigurere hvilke dokumenter som skal importeres til Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/09-right-information-menu-download.png)

Klikk på last ned mot bunnen for å importere den siste delte revisjonen av hvert valgt dokument.

### 5.5 **Høyre informasjonsmeny -** Last opp

Når du eksporterer kan du konfigurere .smc-filen som skal lastes opp.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/10-right-information-menu-upload.png)

_Oppdater dokumentnavn_ Når dette alternativet er på, oppdateres navnet på det valgte dokumentet til navnet du har gitt til filen din.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/11-right-information-menu-upload.png)

På denne måten kan du forsikre deg om at du kan fortsette å laste opp revisjoner til et dokument mens du sikrer at det alltid har samme navn som disse revisjonene.

_Velg lignende dokumenter automatisk_ Når dette alternativet er på kan du laste opp filen din til et dokument med et lignende navn, selv om det ikke er helt det samme. Merk at den opplastede revisjonen fortsatt vil ha filnavnet du har angitt.

_Filnavn_ Her vil du se navnet på filen som skal lastes opp til Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/12-right-information-menu-upload.png)

Som standard vil navnet på .smc-filen som du har lagret på systemet ditt vises. Navnet kan fortsatt endres på dette tidspunktet. Konfigurer filnavnet ved å klikke på blyanten til høyre.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/13-right-information-menu-upload.png)

_Dokument_ Her vil du se navnet på dokumentet på Catenda som skal motta filen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/14-right-information-menu-upload.png)

Som standard vil det ha samme navn som filnavnet. Hvis det ennå ikke finnes et dokument med det navnet i den gjeldende mappen, vil dette feltet være grønt, noe som indikerer at et nytt dokument blir opprettet. Navnet som dokumentet ditt skal ha kan fortsatt endres på dette tidspunktet. Hvis det finnes andre .smc-dokumenter i denne mappen kan du klikke på dokumentnavnet for å velge noen av de andre dokumentene som du ønsker å laste opp .smc-filen til som en revisjon. Hvis du har valgt et dokument, eller hvis det er et dokument i den gjeldende mappen med samme navn, vil dette feltet være grått. Du vil da se en melding som advarer deg om at et dokument med dette navnet allerede finnes, og at .smc-filen din skal lastes opp som en ny revisjon til det dokumentet.

_Status_ Hvis statusarbeidsflyten er aktivert for prosjektet ditt vil du se statusrullemenyen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/15-right-information-menu-upload.png)

Hvis du oppretter et nytt dokument, eller hvis dokumentet ditt ennå ikke har en status, vil du ikke se status. Hvis du legger til en revisjon i et eksisterende dokument vil du se statusen for det dokumentet og kan endre dokumentstatusen ved opplasting. Hvis du ønsker å endre statusen på dokumentet når revisjonen din lastes opp, kan du velge det fra listen over tilgjengelige statuser i prosjektet.

### 5.6 **Dokumenter mottatt**

Når nedlastingen har startet har startet, vil du se følgende melding i nettleseren

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/16-documents-received.png)

Hvis du går tilbake til Solibri vil du se at dokumentene har begynt å behandles. Nedlastede dokumenter lagres i en midlertidig mappe mens Solibri-økten din er aktiv. Husk å lagre Solibri-økten din eller laste opp en ny revisjon på Catenda hvis du ønsker å lagre eventuelle endringer som er gjort i filen din. Opplastede dokumentrevisjoner lagres på Catenda. Den siste revisjonen kan senere åpnes i Solibri igjen.

## 6. **Solibri-dokumentintegrasjon -** Modellsiden

Se modellene du har tilgang til med Catenda-kontoen din på modellsiden av Solibri-dokumentintegreringen. Her kan du konfigurere hvilke modeller som skal synkroniseres med Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/17-solibri-document-integration-models-page.png)

Klikk på navnet på prosjektet hvis du ønsker å navigere til et annet prosjekt. For hver modell vil du se:

- Modellnavn
- Revisjonsnummer
- IFC-type
- Siste revisjon opprettelsesdato
- Siste revisjons skaper

Velg et sett med modeller ved å merke av i boksene, eller merk av boksen øverst for å velge alle. Etter valg vises informasjonsmenyen øverst til høyre. Hvis den er lukket, klikker du på `i`-ikonet for å utvide det. Her kan du redigere utvalget av modeller som skal importeres til Solibri. Klikk på last ned mot bunnen for å importere den siste delte revisjonen av hver valgt modell.

## 7. **Avbryt nettleserøkt**

Mens nettleserøkten din er aktiv vil du se følgende melding i Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/18-cancel-browser-session.png)

Klikk Avbryt hvis du ønsker å avslutte importprosessen.

## 8. **Gir tilgang til Catenda-kontoen din**

Hvis du ikke allerede er logget inn på Catenda, blir du bedt om å [logge inn](https://support.catenda.com/en/articles/7891486-sign-in-page). Etter å ha åpnet for første gang, etter innlogging, eller hvis du allerede var logget inn, blir du bedt om tillatelse for å få tilgang til Catenda-kontoen din:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/19-granting-access-to-your-catenda-account.png)

Hvis du allerede var logget på, men ikke med riktig konto, kan du klikke på profilbildet ditt for å logge av og logge på riktig konto. Når du er sikker på at du er logget inn på riktig konto, klikker du Tillat tilgang for å fortsette. Hvis du venter for lenge med å gjøre dette fungerer det ikke, så sørg for å ha passordet ditt klart! Etter at du har gitt tilgang til kontoen din, vil du se følgende melding:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/20-granting-access-to-your-catenda-account.png)

## 9. **Håndtering av lenket dokumenter**

Dokumenter som har blitt lenket fra Catenda i Solibri kan se annerledes ut fra vanlige dokumenter som har blitt åpnet fra det lokale systemet. Slik ser dokumenter ut når de har blitt lenket med dokumenter på Catenda:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/21-managing-linked-documents.png)

### 9.1 **Navnkolonne**

Modellnavnet kan ta litt tid å oppdatere, men vil til slutt endres for å reflektere antallet revisjoner i dokumentet på Catenda. Hvis organisasjonen din har angitt en innstilling for nedlastingsnavnet på dokumentet ditt, kan du finne et annet navn her. For eksempel er det mulig å be om dokumentnavnet uten revisjonsalternativet. Merk at dette må be om av organisasjonen for alle nedlastede filer i prosjektene deres. Du kan se de forskjellige nedlastingsnavnalternativene for organisasjoner [her](https://support.catenda.com/en/articles/8224886-organization-options).

### 9.2 **Versjonskolonne**

Versjonskolonnen hjelper deg med å holde styr på hvilken revisjon som er lastet inn. Hvis revisjonspublisering er aktivert på Catenda-prosjektet ditt, kan du se større (1.0, 2.0, 3.0, osv...) og mindre (1.1, 1.2, 2.1, osv...) revisjonsnumre her.

### 9.3 **Lenkekolonne**

Etter at en modell har blitt importert fra Catenda Hub, vil et kjedelenkikon vises i den tredje kolonnen for å vise at den er lenket.

### 9.4 **Modellsvev**

Hvis du holder musepekeren over et dokument som har blitt lenket fra Catenda, vil du se `[Documents API] Catenda` etterfulgt av navnet på dokumentet.

### 9.5 **Kontekstmeny -** Oppdateringer

Høyreklikk et dokument for å åpne kontekstmenyen. Her kan du konfigurere innstillingene for dokumentoppdatering.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/22-context-menu-updates.png)

_Oppdater modeller_ Slik kan oppdateringsmodeller-dialogen se ut hvis du har valgt flere dokumenter.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/23-context-menu-updates.png)

Mappe - Klikk på mappen hvis du ønsker å velge en lokal fil for denne modellen i stedet.

Versjon - Her vil du se versjonsnummeret i Catenda sammen med en avmerking som viser om du for øyeblikket arbeider med den siste revisjonen eller ikke. Oppdater - Merk av oppdateringsfeltet for hver modell eller for alle modeller ved å merke av boksen øverst, og klikk på oppdater modeller for å oppdatere dem.

Innstillinger - Klikk på innstillinger for å åpne oppdateringsinnstillingene for modellen for de valgte dokumentene.

Lenk modeller på nytt - Lenk modeller på nytt fungerer bare hvis du har valgt lokale modeller i denne dialogen og ikke med Catenda-modeller.

_Oppdateringsinnstillinger for modell_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/24-context-menu-updates.png)

Automatisk - Når en ny revisjon er tilgjengelig i Catenda Hub, oppdateres modellen automatisk.

Spørsmål - En melding vises når en ny revisjon er tilgjengelig på Catenda. Oppdatering til den nye revisjonen starter når det passer deg.

Lenk modeller på nytt - Lenk modeller på nytt fungerer bare hvis du har valgt lokale modeller i denne dialogen og ikke med Catenda-modeller.

### 9.6 **Kontekstmeny -** Hyperkoblinger

Mot bunnen av dokumentkontekstmenyen vil du se hyperkoblinger.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/25-context-menu-hyperlinks.png)

For hvert valgt dokument som har en lenke til Catenda, vil du se "Catenda" når du åpner hver av hyperkoblingslenyene. Slik kan den utvidede hyperkobjlingsmenylen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/26-context-menu-hyperlinks.png)

Ny hyperkobling - Ved å klikke på Ny hyperkobling åpner du menyen Legg til hyperkobling som kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/27-context-menu-hyperlinks.png)

Vis Klikk "Catenda" for å åpne det lenket dokumentet på Catenda.

Rediger Klikk "Catenda" for å redigere lenken for det valgte dokumentet. Menyen Rediger hyperkobling åpnes nå og kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/28-context-menu-hyperlinks.png)

Adressen skal se slik ut: [https://hub.catenda.com/project/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx/revisions/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx](https://hub.catenda.com/project/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx/revisions/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)

Saken vil være Catenda som standard, men kan gi nytt navn til hva som helst.

Catenda-lenker er alltid Absolutt, noe som betyr at de ikke er relative til hvor .smc-filen din er på systemet ditt.

Fjern Klikk "Catenda" for å fjerne lenken for det valgte dokumentet.
