# Catenda Desktop Connector

> **Merknad:** Installasjonsfilen for dette programmet finner du [her](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)

Med Catenda-skrivebordssamkoblingen kan du planlegge opp- og nedlastinger av de siste versjonene av dokumenter.

## 1. **Øyeblikkelig opp-/nedlasting**

### 1.1 **Last opp**

Velg en mappe på et lokalt system for å laste opp alt mappeinnhold, inkludert filer i undermapper i den valgte mappen, med Desktop Connector til en angitt mappe på Catenda Hub.

_Vellykkede opplastinger_ Hvis du drar og slipper flere filer eller bruker zip-opplastingsfunksjonen på Catenda Hub, laster du opp ett stort datasett. Jo større opplastingen er, jo lenger må du vente før du kan sende filene dine inn i Catenda Hub-dokumentstrukturen.

_Én fil av gangen_ Ved å laste opp filer fra en mappestruktur én fil av gangen med Desktop Connector kan du pause opplastingen og fortsette den senere.

_Reduser risikoen for opplastingsfeil_ Jo større opplastingen er, desto høyere er risikoen for at den mislykkes. Kanskje strømmen din går ut, kanskje internettforbindelsen din brytes for et kort øyeblikk. Da må du starte opplastingen på nytt fra starten.

### 1.2 **Last ned**

Velg enten ett eller flere individuelle dokumenter, eller velg en mappe på Catenda Hub for å laste ned markeringen, inkludert dokumenter i undermapper i valgte mapper, til et sted på din lokale maskin.

### 1.3 **Overføringshastighet**

Både opp- og nedlasting av filer med Desktop Connector er raskere ved filoverføring enn den vanlige opplastingsprosessen, da filene importeres via API uten å kreve overhead for å kjøre en nettleser eller andre nettleserbegrensninger. For overføring av en enkelt fil anbefales det å dra og slippe med en nettleser på grunn av hvor enkelt det er å bruke, men for overføring av store mengder data på en gang eller for de som ønsker å spare tid under opplastinger av store enkeltfiler er Desktop Connector den anbefalte måten for overføring.

### 1.4 **Tilgang**

Tilgangskontroll som er konfigurert på Catenda Hub opprettholdes. Brukere kan laste opp til steder i Catenda-dokumentstrukturen der de har minst skriverettigheter og kan bare laste ned dokumenter som de har minst leserettigheter til.

## 2. **Synkronisering**

Filer kan planlegges til å bli opp- eller lastet ned med jevne mellomrom.

### 2.1 **Lokalt system -> Catenda Hub**

Desktop Connector kan sikre at filer i et Catenda Hub-prosjekt holdes oppdatert med den siste lagringsstaten til en fil på det lokale systemet.

### 2.2 **Catenda Hub -> Lokalt system**

Desktop Connector kan sikre at filer på et lokalt system holdes oppdatert med den siste revisjonen av et dokument i et Catenda Hub-prosjekt.

## 3. **Installasjon**

Når Catenda Desktop Connector installeres på Windows, vises installasjonsfiler i følgende mappe.

`C:\Program Files\Catenda Hub Desktop Connector`

### 3.1 **Avinstallering**

For å avinstallere plugin-modulen går du til følgende Windows-meny:

`Windows-innstillinger -> Apper -> Installerte apper`

Finn Desktop Connector i listen og klikk på handlingsmenyen på høyre side for å avinstallere.

## 4. **Logg inn**

Når Desktop Connector åpnes for første gang, vises en innloggingsforespørsel. Klikk på Logg inn-knappen for å åpne standardnettleseren på systemet på Catenda-innloggingssiden. Etter innlogging, eller hvis du allerede er innlogget, klikk på Tillat tilgang for å gi tilgang til Catenda-kontoen som er innlogget. Etter å ha klikket på Tillat tilgang vil nettleseren be brukeren om å åpne Desktop Connector-programmet. Ved å gi tillatelse til å åpne programmet omdirigeres du tilbake til Desktop Connector [startside](#h_097078145d).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/01-sign-in.png)

## 5. **Startside**

Slik kan Desktop Connector se ut når det startes med en gyldig innlogging:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/02-home-page.png)

### 5.1 **Vekk opp PC**

Vekk PC fra søvnmodus hvis en oppgave er planlagt til å kjøre på det tidspunktet.

### 5.2 **Kjør ved oppstart**

Hvis du vil kjøre skrivebordskoblingen ved oppstart, velger du dette alternativet

### 5.3 **Logg ut**

Klikk på logg ut-knappen nederst til høyre for å logge ut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/03-log-out.png)

## 6. **Prosjektliste**

En oversikt over prosjektene som kontoen hadde tilgang til sist gang prosjektlisten ble lastet inn, vises. For hvert prosjekt vises antall opp- og nedlastingsoppgaver som er konfigurert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/04-project-list.png)

### 6.1 **Synkroniser-knapp**

Hvis du nylig har sluttet seg til et prosjekt, klikk på denne synkroniser-knappen for å laste inn den nye listen over prosjekter som den innloggede kontoen er en del av.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/05-synchronize-button.png)

### 6.2 **Navn**

Klikk på navnet på et prosjekt for å se gjeldende opp- og nedlastingsoppgaver eller for å planlegge en ny oppgave.

### 6.3 **Last opp oppgaver**

Antall opplastingsoppgaver som er aktive for dette prosjektet

### 6.4 **Last ned oppgaver**

Antall nedlastingsoppgaver som er aktive for dette prosjektet

## 7. **Last opp oppgave**

Planlegg en periodisk opplasting av filer fra systemet ditt til Catenda Hub med denne oppgaven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/06-upload-task.png)

### 7.1 **Tittel - Påkrevd**

Opplastingsoppgaven må ha minst en tittel for å bli lagret

### 7.2 **Planlegg kalender - Påkrevd**

Oppgaven må ha minst en dag valgt for å bli lagret

### 7.3 **Prosjektplassering**

_Server_ Klikk på Bla gjennom for å velge destinasjonen på Dokumenter-siden i Catenda Hub hvor filer skal synkroniseres til. Klikk [her](#h_4446f1b663) for å lese mer om valg av serverkatalogsti

_Lokal_ Velg plasseringen på det lokale systemet der filene skal synkroniseres fra.

### 7.4 **Øyeblikkelig**

Oppgaver trenger ikke å bli lagret for å starte opplastingsprosessen. Klikk på Last opp nå-kvadratet for å starte denne oppgaven umiddelbart. Lagrede oppgaver kjøres periodisk på det konfigurerte tidspunktet.

## 8. **Last ned oppgave**

Planlegg en periodisk nedlasting av filer fra Catenda Hub til det lokale systemet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/07-download-task.png)

### 8.1 **Tittel - Påkrevd**

Opplastingsoppgaven må ha minst en tittel for å bli lagret

### 8.2 **Planlegg kalender - Påkrevd**

Oppgaven må ha minst en dag valgt for å bli lagret

### 8.3 **Prosjektplassering**

_Server_ Velg plasseringen på Catenda Hub der dokumenter skal lastes ned fra. Klikk [her](#h_4446f1b663) for å lese mer om valg av serverkatalogsti

_Lokal_ Velg destinasjonen på det lokale systemet der filer skal lastes ned til.

### 8.4 **Øyeblikkelig**

En oppgave trenger ikke å bli lagret for å starte nedlastingen. Klikk på Last ned nå-kvadratet for å starte denne oppgaven umiddelbart. Lagre oppgaven for å kjøre nedlastingen periodisk på det konfigurerte tidspunktet. De nedlastede dokumentene vil ende opp på systemet ditt upakket.

### 8.5 Tilbake-knapp

Klikk på pil-knappen for å gå tilbake til [startside](#h_097078145d)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 9. **Serverplassering**

Klikk på Bla gjennom i prosjektplasseringsområdet for en opp- eller nedlastingsoppgave for å begynne å bla gjennom katalogstigenen til Catenda-prosjektet. Dialogen Velg katalogsti åpnes. Når den åpnes, begynner den å laste ned alle mappenavn i prosjektet og deres hierarki. For nedlastingsoppgaver lastes dokumentnavn ned også. Mens nedlastingen pågår, kan dialogen se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/09-server-location.png)

Spesielt for nedlastingsoppgaver, hvis det er mange mapper og dokumenter, kan det ta et par minutter før denne prosessen er ferdig. Kontroller at du har nok minne tilgjengelig på det lokale systemet for dette trinnet.

_Dialogstørrelse_ Klikk på Min eller Maks mot øvre høyre hjørne for å minimere eller maksimere dialogen Velg katalogsti.

_Kataloghandlinger_ Etter at mappene har lastet inn, kan dialogen se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/10-server-location.png)

Klikk på pilen ved siden av en mappe for å utvide den. Dokumenter er bare tilgjengelige i denne visningen for nedlastingsoppgaver.

_Mappevalg_ Klikk på en mappe for å velge den. For nedlastingsoppgaver kan flere mapper velges, mens for opplastingsoppgaver kan bare en mappe velges av gangen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/11-server-location.png)

Etter at en mappe er valgt, vises den som hvit med en hake. Alle undermapper i den valgte mappen vises gjennomstreket, da det bare er mulig å velge mapper på samme nivå. Mot toppen vises antallet av valgte elementer.

_Last ned oppgave_ Hvis det finnes dokumenter i den valgte mappen eller dens undermapper, vil alle mapper i banen mellom den valgte mappen og dokumentet bli opprettet. Dokumentet lastes deretter ned til den mappen. Hvis en undermappe ikke inneholder noen dokumenter, vil undermappen ikke bli opprettet selv om den kan være merket av i denne dialogen. Det er ikke mulig å fjerne merking av en undermappe for ikke å laste ned en del av en mappestruktur. Hvis du bare vil laste ned noen mapper, velger du dem enkeltvis som i bildet nedenfor:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/12-server-location.png)

Dokumentvalg Klikk på et dokument for å velge det

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/13-server-location.png)

Når enkelte dokumenter er valgt, lastes dokumentene ned som en flat liste direkte til den valgte lokale banen uten hierarkiet til mappene som disse dokumentene befinner seg i.

_Last opp oppgave_ Dokumenter lastes opp til den valgte mappen. Hvis mappenavnet samsvarer, lastes dokumenter opp til undermapper i den valgte mappen.

## 10. **Oppgaveliste**

Her kan de opp- og nedlastingsoppgavene som er konfigurert i denne installasjonen for den innloggede brukeren ses.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/14-task-list.png)

### 10.1 **Navn**

Navn på oppgaven.

### 10.2 **Oppgave**

Det planlagte tidspunktet for når oppgaven kjøres.

### 10.3 **Prosjekt**

Navnet på prosjektet der denne oppgaven kjøres.

### 10.4 **Status**

Status for denne oppgaven.

### 10.5 **Tilbake-knapp**

Klikk denne knappen for å gå tilbake til [startside](#h_097078145d)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 11. **Loggmappe**

Denne knappen åpner mappeplasseringen for Desktop Connector-loggene på det lokale systemet. Standardplasseringen for disse loggene er:

`C:\Users\<Windows account name>\AppData\Local\User Name\2b92d867-496c-47d1-ac42-fbf8fa355177\Cache\BimsyncApp`
