# Innstillinger for sakstavle

For å åpne innstillingssiden for sakstavle, åpner du først [sakssiden](https://support.catenda.com/en/articles/4670271-topics-page).

Innstillingssiden for en sakstavle finner du ved å klikke på innstillinger for en sakstavle på [tavlersiden](https://support.catenda.com/en/articles/9413644-boards-page), som kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/01-intro.png)

Innstillingssiden for sakstavle for den sist besøkte sakstavlen finner du også ved å gå til [sakinnstillingssiden](https://support.catenda.com/en/articles/14183429-topic-settings-page) og klikke på innstillinger for sakstavle.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/02-intro.png)

Du kan finne innstillingssiden for sakstavle som en underside til [sakssiden](https://support.catenda.com/en/articles/4670271-topics-page) eller ved å klikke på innstillinger for den aktuelle sakstavlen på [tavlersiden](https://support.catenda.com/en/articles/9413644-boards-page#h_e0fc8beec6). _Nødvendig tilgang:_ Full tilgang til [sakstavlen](https://support.catenda.com/en/articles/4670271-topics-page)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/03-intro.png)

Slik kan innstillingssiden for sakstavle se ut med alle menyene lukket.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/04-intro.png)

Følgende saker beskrives i denne artikkelen:

## 1. **Handlingsmeny**

Slik kan handlingsmenyen i øverste høyre hjørne i en sakstavle se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/05-action-menu.png)

Følgende saker beskrives i denne delen:

### 1.1 **Ny sak**

Klikk på den grønne plusknappen eller klikk på handlingen "ny sak" i handlingsmenyen for å lage en [ny sak](https://support.catenda.com/en/articles/4670268-creating-a-new-issue) i den gjeldende sakstavlen. _Nødvendig tilgang:_ Lesestilgang til den gjeldende sakstavlen.

### 1.2 **Bytt saker**

Klikk på denne knappen for å [bytte saker](https://support.catenda.com/en/articles/4670289-exchange-issues)

### 1.3 **Ny sakstavle**

Klikk på denne knappen for å lage en [ny sakstavle](https://support.catenda.com/en/articles/6379614-topic-board-from-an-existing-topic-board).

### 1.4 **Historikk**

_Importhistorikk_ - Se importhistorikken for saker i prosjektet _Eksporthistorikk_ - Se eksporthistorikken for saker i prosjektet _Flytthistorikk_ - Se flytthistorikken for saker i prosjektet

### 1.5 **Arkiver sakstavle**

Du kan ikke slette en sakstavle i Catenda Hub. I stedet kan du "arkivere" den slik at den ikke vises lenger. Lenker til saker i arkiverte sakstavler vil ikke være synlige i dokumenter eller objekter. Arkiverte sakstavler kan gjenopprettes ved å gå til innstillinger for den arkiverte tavlen på [tavlersiden](https://support.catenda.com/en/articles/9413644-boards-page). Etter at tavlen er gjenopprettet, vil lenkene være synlige igjen.

> **Merk:** Du kan se sakene i en arkivert sakstavle ved å klikke på "sakstavler". Nederst i listen kan du velge "Vis arkivert".

## 2. **Sakstavlinformasjon**

_Navn på sakstavle_ - Endre navn på sakstavlen _Eier_ - Se hvem som opprettet sakstavlen

_Beskrivelse_ Kort beskrivelse som kun vil være synlig her, slik at du og andre som konfigurerer tavlen vet hva den brukes til.

## 3. **Statuser og typer**

Følgende saker beskrives i denne delen:

### 3.1 **Lås statuser og typer for BCF 1.0-kompatibilitet**

BCF 1.0 støtter kun 2 statuser ("Åpen" og "Lukket") og 4 typer ("Feil", "Advarsel", "Info" og "Ukjent"). Det er ikke mulig å endre statuser eller typer på sakstavler der dette alternativet er valgt.

### 3.2 **Status**

Når du oppretter en sakstavle, vil du ha følgende standardstatuser:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/06-status.png)

En status har en _Navn, Farge og Metastatus_. Som standard er det tre statuser med åpen metastatus og to med lukket metastatus.

_Legg til status_ - Klikk på teksten "legg til status" nederst i statuslisten for å legge til en ny status.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/07-status.png)

_Rediger status_ Når du redigerer en status, vil du merke at du kan tilordne en tredje metastatus kalt Kandidat.

_Farge_ - Endre fargen på statusen.

_Piler_ Endre rekkefølgen på en status ved å bruke pilene til å flytte den opp eller ned i listen. Den øverste statusen blir standardstatusen når du oppretter en ny sak. Rekkefølgen på statusene vil også være rekkefølgen som statusene vises i rullegardinlisten når du endrer statusen for en sak.

_Slett_ Du kan også slette statuser her ned til minimum 1 åpen og 1 lukket status.

### 3.3 **Metastatus**

Metastatuser gir en generell ide om hvor i arbeidsflyten statusen på en sak er. _Åpen_ - Saker med denne metastatusen vises som standard når du åpner en sakstavle. _Lukket_ - Saker med denne metastatusen er skjult som standard når du åpner en sakstavle.

> **Merk:** Du kan konfigurere hvem som har lov til å endre statusen på en sak med åpen metastatus til en status med lukket metastatus i [tilgangskontrollseksjonen](#h_82063f7a79).

_Kandidat_ Saker med en kandidat-metastatus er også skjult som standard. Denne statusen er ment for saker som verken er åpne eller lukket. Kandidat-metastatusen er ment for å la folk vite at en sak ikke helt er ferdig utkastet ennå, så den er ikke åpen ennå. I flyten er det derfor ment å komme før åpen. Imidlertid bruker folk også denne statusen for saker som har falt utenfor den vanlige flyten. Som en sak som ikke er ferdig og derfor lukket, men bare ikke lenger er relevant. Folk vil ikke se det i listen som standard og bruker derfor denne metastatusen.

Minimumsmengden av statuser er en åpen status og en lukket status.

### 3.4 **Type**

Når du oppretter en sakstavle, vil du ha følgende standardtyper:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/08-type.png)

Typer konfigureres på samme måte som statuser, bortsett fra at de ikke har metastatuser og du kan slette ned til minimum 1 type.

## 4. **Egendefinerte felt**

I denne menyen vil du kunne legge til og endre egendefinerte felt i denne sakstavlen. _Nødvendig tilgang:_ Full tilgang til sakstavlen. Egendefinerte felt kan konfigureres på [siden for egendefinerte felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup). _Nødvendig tilgang:_ Prosjektadministrator

Følgende saker beskrives i denne delen:

### 4.1 **Legg til egendefinert felt**

Du kan legge til et egendefinert felt ved å klikke på den grønne knappen "Legg til et egendefinert felt".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/09-add-custom-field.png)

Etter å ha klikket på knappen, vil du kunne velge ditt egendefinerte felt i dialogen "legg til egendefinert felt".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/10-add-custom-field.png)

_Velg et egendefinert felt_ Følgende typer egendefinerte felt kan gjøres tilgjengelig for en sakstavle: Dato Desimal Rullegardin Heltall Tekst

_Merk som obligatorisk_ Ja eller nei. Hvis det egendefinerte feltet er merket som obligatorisk, vil ikke brukerne kunne sende inn en sak uten å fylle ut dette egendefinerte feltet.

_Angi standardverdi_ Standardverdi for din egendefinerte felttype. Standardverdien er obligatorisk når det egendefinerte feltet er merket som obligatorisk.

Husk å klikke på legge til når du er ferdig.

> **Merk:** Det er mulig å legge til opptil 30 egendefinerte felt per sakstavle.

### 4.2 **Endre egendefinerte felt**

Ved å klikke på et egendefinert felt som har blitt lagt til, vil du kunne konfigurere innstillingene.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/11-modifying-custom-fields.png)

_Merk som obligatorisk_ Ja eller nei. Hvis det egendefinerte feltet er merket som obligatorisk, vil ikke brukerne kunne sende inn en sak uten å fylle ut dette egendefinerte feltet.

_Angi standardverdi_ Standardverdi for din egendefinerte felttype. Standardverdien er obligatorisk når det egendefinerte feltet er merket som obligatorisk.

_Fjern fra sakstavle_ Klikk på knappen "fjern fra sakstavle" for å fjerne dette egendefinerte feltet fra sakstavlen.

Husk å klikke på send.

## 5. **Tilgangskontroll**

Brukere vil kunne se en oversikt over hvilke lag og brukere som har hvilken tilgang til denne sakstavlen. Hvis alle brukere har tilgang til å opprette sakstavler, vil låsen være grønn. Hvis tilgang er satt for opprettelsen av sakstavler i prosjektinnstillinger, vil låsen være oransje.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/12-access-control.png)

### 5.1 **Rediger tilgang**

Klikk på "rediger tilgang" for å konfigurere tilgangen for denne sakstavlen. Du kan lese mer om redigering av tilgang [her](https://support.catenda.com/en/articles/4670296-issue-boards-acl). _Nødvendig tilgang:_ Full tilgang til sakstavlen.

## 6. **Ulenket felt**

Saker som er lagt inn i en sakstavle med felt som ikke finnes i sakstavlen, er skjult i sakstabellen som standard.

En oransje stolpe vises deretter øverst i sakstabellen som sier at det er ulenket felt i sakstavlen. _Nødvendig tilgang:_ Administrator

For at saker som inneholder felt med verdier som ikke finnes i sakstavlen, skal vises i sakstabellen, må feltene være lenket til noe som finnes i sakstavlen.

Følgende saker beskrives i denne delen:

### 6.1 **Felt med verdier som ikke finnes**

Eksempler på felt med verdier som kanskje ikke finnes i en sakstavle, er:

_Status eller type_ For at en sak skal vises i sakstabellen, må den ha en status og en type med en GUID som samsvarer med en GUID for en status og en type som er konfigurert for en sakstavle. Selv om navnene på statusene og typene er de samme i ulike sakstavler, hvis saken flyttes fra en tavle til en annen, vil status/type være ulenket fordi GUID for en status/type er unik for hver sakstavle.

_Medlemmer_ For at en sak skal vises i sakstabellen, må alle medlemmer som er en del av saken finnes i prosjektet. Følgende felt kan inneholde medlemmer i en sak: Tildelt bruker Etterspurt av bruker Kommenterer bruker

### 6.2 **Lenke felt**

Ofte importeres flere saker samtidig. For at ikke hvert enkelt felt må endres til en eksisterende verdi, er det mulig å kartlegge alle felt fra ett tidspunkt til en eksisterende verdi i sakstavlen.

_Status eller type_ For hver status og type som ikke finnes i sakstavlen, velger du en eksisterende status eller type. Den ulenket status eller type kan ha samme navn som en eksisterende status eller type, men kan fortsatt være ulenket fordi den har en annen GUID i bakgrunnen. I dette tilfellet er kartleggingen enkel, velg bare statusen eller typen med samme navn. Hvis en status eller type med samme navn ikke finnes i tavlen som saken ble importert til, må en status eller type med et annet navn som finnes i tavlen, velges. Hvis ingen av dem passer, vurder å legge til en annen status til listen over typer eller statuser i sakstavlen.

_Brukere_ Hver bruker i importerte saker som ikke finnes i prosjektet, må kartlegges til enten en bruker eller team i prosjektet. Etter kartleggingen vil sakene bli etterspurt av eller tildelt denne brukeren, og alle kommentarer vil se ut som de er laget av den kartlagte brukeren. Hvis brukeren har endret e-postadresse, er kartleggingen enkel, velg bare brukeren etter navn med kontoen de bruker med sin nye e-postadresse. Hvis det ikke er en tilsvarende bruker som kan kartlegges i prosjektet, er en god strategi å opprette et team som fungerer som denne brukeren. På denne måten er det mulig å finne alle handlinger fra importerte saker laget av denne brukeren ved å filtrere på det kartlagte teamet.
