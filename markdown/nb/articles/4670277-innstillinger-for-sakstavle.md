# Innstillinger for saksliste

For å åpne siden for innstillinger for saksliste, må du først åpne [saker-siden](https://support.catenda.com/en/articles/4670271-topics-page).

Innstillingssiden for en saksliste kan finnes ved å klikke på innstillinger for en saksliste på [tavler-siden](https://support.catenda.com/en/articles/9413644-boards-page), som kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/01-intro.png)

Innstillingssiden for saksliste for den sist besøkte sakslisten kan også finnes ved å gå til [sak-innstillingssiden](https://support.catenda.com/en/articles/14183429-topic-settings-page) og klikke på innstillinger for saksliste.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/02-intro.png)

Du kan finne innstillingssiden for saksliste som en underside til [saker-siden](https://support.catenda.com/en/articles/4670271-topics-page) eller ved å klikke på innstillinger for den aktuelle sakslisten på [tavler-siden](https://support.catenda.com/en/articles/9413644-boards-page#h_e0fc8beec6). _Påkrevd tilgang:_ Full tilgang til [sakslisten](https://support.catenda.com/en/articles/4670271-topics-page)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/03-intro.png)

Dette er hvordan innstillingssiden for saksliste kan se ut med alle menyene lukket.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/04-intro.png)

## 1. **Handlingsmeny**

Dette er hvordan handlingsmenyen mot øvre høyre hjørne i en saksliste kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/05-action-menu.png)

### 1.1 **Ny sak**

Klikk på den grønne plusknappen eller klikk på handlingen for ny sak i handlingsmenyen for å opprette en [ny sak](https://support.catenda.com/en/articles/4670268-creating-a-new-issue) i den gjeldende sakslisten. _Påkrevd tilgang:_ Lesetilgang til den gjeldende sakslisten.

### 1.2 **Utveksle saker**

Klikk denne knappen for å [utveksle saker](https://support.catenda.com/en/articles/4670289-exchange-issues)

### 1.3 **Ny saksliste**

Klikk denne knappen for å lage en [ny saksliste](https://support.catenda.com/en/articles/6379614-topic-board-from-an-existing-topic-board).

### 1.4 **Historikk**

_Importhistorikk_ - Se importhistorikken for saker i prosjektet _Eksporthistorikk_ - Se eksporthistorikken for saker i prosjektet _Flytthistorikk_ - Se flytthistorikken for saker i prosjektet

### 1.5 **Arkiver saksliste**

Du kan ikke slette en saksliste i Catenda Hub. I stedet kan du "arkivere" den slik at den ikke vises lenger. Lenker til saker i arkiverte sakslister vil ikke være synlige i dokumenter eller objekter. Arkiverte sakslister kan gjenopprettes ved å gå til innstillingene for den arkiverte tavlen på [tavler-siden](https://support.catenda.com/en/articles/9413644-boards-page). Etter gjenoppretting av en tavle vil lenkene være synlige igjen.

> **Merk:** Du kan se sakene i en arkivert saksliste ved å klikke på "sakslister". Nederst på denne listen kan du velge "Vis arkivert".

## 2. **Informasjon om saksliste**

_Navn på saksliste_ - Endre navn på sakslisten _Eier_ - Se hvem som opprettet sakslisten

_Beskrivelse_ Kort beskrivelse som bare vil bli sett her, slik at du og andre som konfigurerer tavlen vet hva den brukes til.

## 3. **Statuser og typer**

### 3.1 **Lås statuser og typer for BCF 1.0-kompatibilitet**

BCF 1.0 støtter kun 2 statuser ("Åpen" og "Lukket") og 4 typer ("Feil", "Advarsel", "Info" og "Ukjent"). Det er ikke mulig å endre statuser eller typer på sakslister der dette valget er valgt.

### 3.2 **Status**

Når du opprettet en saksliste, vil du ha følgende standardstatuser:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/06-status.png)

En status har _Navn, Farge og Meta-status._ Som standard er det tre statuser som har en åpen og to som har en lukket meta-status.

_Legg til status_ - Klikk på teksten for å legge til status nederst i statuslisten for å legge til en ny status.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/07-status.png)

_Rediger status_ Når du redigerer en status, vil du legge merke til at du kan tilordne en tredje meta-status kalt Kandidat.

_Farge_ - Endre fargen på statusen.

_Piler_ Endre rekkefølgen på en status ved å bruke pilene for å flytte den opp eller ned i listen. Topp-statusen vil være standardstatusen når du oppretter en ny sak. Rekkefølgen på statusene vil også være rekkefølgen som statusene vil vises i rullegardinlisten når du endrer statusen på en sak.

_Slett_ Du kan også slette statuser her ned til et minimum på 1 åpen og 1 lukket status.

### 3.3 **Meta-status**

Meta-statuser gir en generell ide om hvor i arbeidsflyten statusen på en sak er. _Åpen_ - Saker med denne meta-statusen vises som standard når du åpner en saksliste. _Lukket -_ Saker med denne meta-statusen er skjult som standard når du åpner en saksliste.

> **Merk:** Du kan konfigurere hvem som har tillatelse til å endre statusen på en sak med en åpen meta-status til en status med en lukket meta-status i [tilgangsstyringsdelen](#h_82063f7a79).

_Kandidat_ Saker med en kandidat meta-status er også skjult som standard. Denne statusen er ment for saker som verken er åpne eller lukket. Kandidat meta-statusen er ment for å la folk vite at en sak ikke er helt ferdig utdannet ennå, så den er ikke åpen ennå. I arbeidsflyten er den derfor ment å komme før åpen. Imidlertid bruker noen mennesker også denne statusen for saker som har falt utenfor den vanlige arbeidsflyten. Som en sak som ikke er ferdig og derfor lukket, men bare ikke lenger relevant. Folk vil ikke se det i listen som standard og bruker derfor denne meta-statusen.

Minimumsantallet statuser er en åpen status og en lukket status.

### 3.4 **Type**

Når du opprettet en saksliste, vil du ha følgende standardtyper:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/08-type.png)

Typer er konfigurert på samme måte som statuser bortsett fra at de ikke har meta-statuser, og du kan slette ned til et minimum på 1 type.

## 4. **Egendefinerte felt**

I denne menyen kan du legge til og endre egendefinerte felt i denne sakslisten. _Påkrevd tilgang:_ Full tilgang til sakslisten Egendefinerte felt kan konfigureres på [siden for egendefinerte felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup). _Påkrevd tilgang:_ Prosjektadministrator

### 4.1 **Legg til egendefinert felt**

Du kan legge til et egendefinert felt ved å klikke på den grønne knappen Legg til et egendefinert felt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/09-add-custom-field.png)

Etter å ha klikket på knappen, kan du velge ditt egendefinerte felt i dialogboksen for å legge til et egendefinert felt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/10-add-custom-field.png)

_Velg et egendefinert felt_ Følgende typer egendefinerte felt kan gjøres tilgjengelige for en saksliste: Dato Desimal Rullegardin Heltall Tekst

_Merk som påkrevd_ Ja eller nei Hvis det egendefinerte feltet er satt som påkrevd, vil ikke brukerne kunne sende inn en sak uten å fylle ut dette egendefinerte feltet.

_Angi standardverdi_ Standardverdi for din egendefinerte felttype. Standardverdien er obligatorisk når det egendefinerte feltet er merket som påkrevd.

Husk å klikke legg til når du er ferdig.

> **Merk:** Det er mulig å legge til opptil 30 egendefinerte felt per saksliste.

### 4.2 **Endre egendefinerte felt**

Ved å klikke på et egendefinert felt som er lagt til, kan du konfigurere innstillingene.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/11-modifying-custom-fields.png)

_Merk som påkrevd_ Ja eller nei Hvis det egendefinerte feltet er satt som påkrevd, vil ikke brukerne kunne sende inn en sak uten å fylle ut dette egendefinerte feltet.

_Angi standardverdi_ Standardverdi for din egendefinerte felttype. Standardverdien er obligatorisk når det egendefinerte feltet er merket som påkrevd.

_Fjern fra saksliste_ Klikk knappen Fjern fra saksliste for å fjerne dette egendefinerte feltet fra sakslisten.

Husk å klikke send.

## 5. **Tilgangsstyring**

Brukerne vil kunne se en oversikt over hvilke teams og brukere som har hvilken tilgang til denne sakslisten. Hvis alle brukere har tilgang til å opprette sakslister, vil låsen være grønn. Hvis tilgang har blitt angitt for opprettelsen av sakslister i prosjektinnstillinger, vil låsen være oransje.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s0bzqka3/12-access-control.png)

### 5.1 **Rediger tilgang**

Klikk på "rediger tilgang" for å konfigurere tilgangen for denne sakslisten. Du kan lese mer om redigering av tilgang [her](https://support.catenda.com/en/articles/4670296-issue-boards-acl). _Påkrevd tilgang:_ Full tilgang til sakslisten.

## 6. **Ukoblede felter**

Saker som legges inn i en saksliste med felt som ikke finnes i sakslisten, er skjult i sakstabellen som standard.

En oransje stolpe vises deretter mot toppen av sakstabellen som sier at det finnes ukoblede felt i sakslisten. _Påkrevd tilgang:_ Administrator

For at saker som inneholder felt med verdier som ikke finnes i sakslisten, skal vises i sakstabellen, må feltene kobles til noe som finnes i sakslisten.

### 6.1 **Felt med verdier som ikke finnes**

Eksempler på felt med verdier som kanskje ikke finnes i en saksliste er:

_Status eller type_ For at en sak skal vises i sakstabellen, må den ha en status og type med en GUID som samsvarer med en GUID for en status og type som er konfigurert for en saksliste. Selv om navnene på statuser og typer er de samme i forskjellige sakslister, hvis saken flyttes fra en tavle til en annen, vil statusen/typen være ukoblet fordi GUID for en status/type er unik for hver saksliste.

_Medlemmer_ For at en sak skal vises i sakstabellen, må alle medlemmer som er del av saken, finnes i prosjektet. Følgende felt kan inneholde medlemmer i en sak: Tildelt bruker Bruker som ber om det Bruker som kommenterer

### 6.2 **Koble felter**

Ofte importeres flere saker samtidig. For å gjøre det slik at ikke hvert enkelt felt må endres til en eksisterende verdi, er det mulig å kartlegge alle felt av en gang til en eksisterende verdi i sakslisten.

_Status eller type_ For hver status og type som ikke finnes i sakslisten, velger du en eksisterende status eller type. Den ukoblede statusen eller typen kan ha samme navn som en eksisterende status eller type, men kan fortsatt være ukoblet fordi den har en annen GUID i bakgrunnen. I dette tilfellet er kartleggingen enkel – velg bare statusen eller typen med samme navn. Hvis det ikke finnes en status eller type med samme navn på tavlen som saken ble importert til, må du velge en status eller type med et annet navn som finnes på tavlen. Hvis ingen av dem passer, bør du vurdere å legge til en annen status i listen over typer eller statuser i sakslisten.

_Brukere_ Hver bruker i importerte saker som ikke finnes i prosjektet, må kartlegges til enten en bruker eller et team i prosjektet. Etter kartlegging vil sakene bli etterspurt av eller tildelt denne brukeren, og alle kommentarer vil se ut til å være gjort av den kartlagte brukeren. Hvis brukeren har endret e-postadresse, er kartleggingen enkel – velg bare brukeren etter navn med kontoen som de bruker med sin nye e-postadresse. Hvis det ikke finnes en lignende bruker som kan kartlegges i prosjektet, er en god strategi å opprette et team som fungerer som denne brukeren. På denne måten er det mulig å finne alle handlinger fra importerte saker gjort av denne brukeren ved å filtrere på det kartlagte teamet.
