# Catenda Desktop Connector

> **Merk:** Installasjonfilen for dette programmet finner du [her](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)

Med Catenda desktop connector kan du planlegge opplastinger og nedlastinger av de nyeste versjonene av Dokumenter.

## 1. **Umiddelbar opp-/nedlasting**

### 1.1 **Opplasting**

Velg en mappe på et lokalt system for å laste opp alt mappeinnhold, inkludert filer i undermapper til den valgte mappen, med Desktop Connector til en angitt mappe på Catenda Hub.

_Vellykkede opplastinger_ Hvis du drar og slipper flere filer eller bruker zip-opplastingsfunksjonen på Catenda Hub, laster du opp ett stort datasett. Jo større opplastingen er, desto lenger må du vente før du kan sende filene dine til Catenda Hub-dokumentstrukturen.

_Én fil om gangen_ Ved å laste opp filer fra en mappestruktur én fil om gangen kan Desktop Connector-en pause opplastingen og fortsette den senere.

_Reduser risikoen for opplastingsfeil_ Jo større opplastingen er, desto høyere er risikoen for at den også mislykkes. Kanskje går strømmen ut, eller internettforbindelsen din avbrytes for en kort stund. Deretter må du starte opplastingen på nytt.

### 1.2 **Nedlasting**

Velg enten ett eller flere enkeltdokumenter eller velg en mappe på Catenda Hub for å laste ned utvalget, inkludert Dokumenter i undermapper av valgte mapper, til et sted på den lokale maskinen.

### 1.3 **Overføringshastighet**

Både opplasting og nedlasting av filer med Desktop Connector er raskere ved filoverføring enn den vanlige opplastingsprosessen fordi filene importeres via API-en uten overhead fra en kjørende nettleser eller andre nettleserbegrensninger. For overføring av en enkeltfil anbefales drag eller drop med en nettleser på grunn av brukervennligheten, men for overføring av store datamengder på en gang eller for de som ønsker å spare tid under opplasting av store enkeltfiler, er Desktop Connector den anbefalte måten for overføring.

### 1.4 **Tilgang**

Tilgangskontroll som er konfigurert på Catenda Hub, blir opprettholdt. Brukere kan laste opp til steder i Catenda-dokumentstrukturen der de har minst skriverettigheter, og kan bare laste ned Dokumenter de har minst leserettigheter til.

## 2. **Synkronisering**

Filer kan planlegges til å lastes opp eller ned med jevne mellomrom.

### 2.1 **Lokalt system -> Catenda Hub**

Desktop Connector kan sikre at filer i et Catenda Hub-prosjekt holdes oppdatert med den siste lagringsstilstanden til en fil på det lokale systemet.

### 2.2 **Catenda Hub -> Lokalt system**

Desktop Connector kan sikre at filer på et lokalt system holdes oppdatert med den siste revisjonen av et Dokument i et Catenda Hub-prosjekt.

## 3. **Installasjon**

Når Catenda Desktop Connector installeres på Windows, vises installasjonsfilene i følgende mappe.

`C:\Program Files\Catenda Hub Desktop Connector`

### 3.1 **Avinstallering**

For å avinstallere programtillegget, gå til følgende Windows-meny:

`Windows-innstillinger -> Apper -> Installerte apper`

Finn Desktop Connector i listen og klikk på handlingsmenyen på høyre side for å avinstallere.

## 4. **Logg inn**

Når Desktop Connector åpnes for første gang, vises en innloggingsforespørsel. Klikk på Logg inn-knappen for å åpne standardnettleseren på systemet på Catenda-innloggingssiden. Etter at du har logget inn eller hvis du allerede er logget inn, klikk på tillat tilgang for å gi tilgang til Catenda-kontoen som er logget inn. Etter at du har klikket på tillat tilgang, vil nettleseren be brukeren om å åpne Desktop Connector-programmet. Når du gir tillatelse til å åpne programmet, omdirigeres du tilbake til Desktop Connector [startside](#home-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/01-sign-in.png)

## 5. **Startside**

Slik kan Desktop Connector se ut når den startes opp med en gyldig innlogging:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/02-home-page.png)

### 5.1 **Vekk PC**

Vekk PC-en fra hvilemodus hvis en oppgave er planlagt til å kjøre på det tidspunktet.

### 5.2 **Kjør ved oppstart**

For å kjøre desktop connectorene ved oppstart, velg dette alternativet

### 5.3 **Logg ut**

Klikk på logg ut-knappen nederst til høyre for å logge ut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/03-log-out.png)

## 6. **Prosjektliste**

En oversikt over prosjektene som kontoen hadde tilgang til sist prosjektlisten ble lastet inn, vises. For hvert prosjekt vises antallet opp- og nedlastingsoppgaver som er konfigurert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/04-project-list.png)

### 6.1 **Synkroniseringsknapp**

Hvis du nylig har blitt med i et prosjekt, klikk på denne synkroniseringsknappen for å laste inn den nye listen over prosjekter som den innloggede kontoen er en del av.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/05-synchronize-button.png)

### 6.2 **Navn**

Klikk på navnet på et prosjekt for å se gjeldende opp- og nedlastingsoppgaver eller for å planlegge en ny oppgave.

### 6.3 **Opplastingsoppgaver**

Antallet opplastingsoppgaver som er aktive for dette prosjektet

### 6.4 **Nedlastingsoppgaver**

Antallet nedlastingsoppgaver som er aktive for dette prosjektet

## 7. **Opplastingsoppgave**

Planlegg en periodisk opplasting av filer fra systemet ditt til Catenda Hub med denne oppgaven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/06-upload-task.png)

### 7.1 **Tittel - Obligatorisk**

Opplastingsoppgaven må ha minst en tittel for å bli lagret

### 7.2 **Planlegg kalender - Obligatorisk**

Oppgaven må ha minst én dag valgt for å bli lagret

### 7.3 **Prosjektplassering**

_Server_ Klikk på Bla gjennom for å velge destinasjonen på siden Dokumenter i Catenda Hub der filer skal synkroniseres til. Klikk [her](#server-location) for å lese mer om valg av servermappebane

_Lokalt_ Velg plasseringen på det lokale systemet der filer skal synkroniseres fra.

### 7.4 **Umiddelbar**

Oppgaver trenger ikke å bli lagret for å starte opplastingsprosessen. Klikk på opplastingsfeltet nå for å starte denne oppgaven umiddelbart. Lagrede oppgaver kjøres periodisk på det konfigurerte tidspunktet.

## 8. **Nedlastingsoppgave**

Planlegg en periodisk nedlasting av filer fra Catenda Hub til det lokale systemet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/07-download-task.png)

### 8.1 **Tittel - Obligatorisk**

Opplastingsoppgaven må ha minst en tittel for å bli lagret

### 8.2 **Planlegg kalender - Obligatorisk**

Oppgaven må ha minst én dag valgt for å bli lagret

### 8.3 **Prosjektplassering**

_Server_ Velg plasseringen på Catenda Hub der Dokumenter skal lastes ned fra. Klikk [her](#server-location) for å lese mer om valg av servermappebane

_Lokalt_ Velg destinasjonen på det lokale systemet der filer skal lastes ned til.

### 8.4 **Umiddelbar**

En oppgave trenger ikke å bli lagret for å starte nedlasting. Klikk på Nedlast nå-feltet for å starte denne oppgaven umiddelbart. Lagre oppgaven for å kjøre nedlastingen periodisk på det konfigurerte tidspunktet. De nedlastede Dokumentene blir pakket ut på systemet ditt.

### 8.5 Tilbake-knapp

Klikk på pilknappen for å gå tilbake til [startsiden](#home-page)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 9. **Serverplassering**

Klikk på Bla gjennom i prosjektplasseringsområdet for en opp- eller nedlastingsoppgave for å begynne å bla gjennom mappebanen til Catenda-prosjektet. Dialogboksen Velg mappebane åpnes. Når den åpnes, starter den nedlastingen av alle mappenavn i prosjektet og deres hierarki. For nedlastingsoppgaver lastes også Dokumentnavn ned. Mens nedlastingen pågår, kan dialogboksen se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/09-server-location.png)

Spesielt for nedlastingsoppgaver, hvis det er mange mapper og Dokumenter, kan det ta et par minutter før denne prosessen er ferdig. Kontroller at det er nok minne tilgjengelig på det lokale systemet for dette trinnet.

_Dialogboksstørrelse_ Klikk på Min eller Maks øverst til høyre for å minimere eller maksimere dialogboksen Velg mappebane.

_Mappehandlinger_ Etter at mappene er lastet inn, kan dialogboksen se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/10-server-location.png)

Klikk på pilen ved siden av en mappe for å utvide den. Dokumenter er bare tilgjengelig i denne visningen for nedlastingsoppgaver.

_Mappevalg_ Klikk på en mappe for å velge den. For nedlastingsoppgaver kan flere mapper velges mens for opplastingsoppgaver kan bare én mappe velges om gangen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/11-server-location.png)

Etter at en mappe er valgt, vises den som hvit med en hake. Alle undermapper til den valgte mappen vises gjennomstrekket fordi det bare er mulig å velge mapper på samme nivå. Øverst vises antallet valgte elementer.

_Nedlastingsoppgave_ Hvis det finnes Dokumenter i den valgte mappen eller dens undermapper, vil alle mapper i banen mellom den valgte mappen og Dokumentet bli opprettet. Dokumentet lastes deretter ned til den mappen. Hvis en undermappe ikke inneholder Dokumenter, vil undermappen ikke bli opprettet selv om den kan være merket av i denne dialogboksen. Det er ikke mulig å fjerne merking fra en undermappe for ikke å laste ned en del av en mappestruktur. For å bare laste ned noen mapper, velg dem individuelt som i bildet nedenfor:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/12-server-location.png)

Dokumentvalg Klikk på et Dokument for å velge det

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/13-server-location.png)

Når individuelle Dokumenter er valgt, blir Dokumentene lastet ned som en flat liste direkte til den valgte lokale banen uten hierarkiet til mappene som disse Dokumentene befinner seg i.

_Opplastingsoppgave_ Dokumenter lastes opp til den valgte mappen. Hvis mappenavnet stemmer, lastes Dokumenter opp til undermapper til den valgte mappen.

## 10. **Oppgaveliste**

Her kan du se opp- og nedlastingsoppgavene som er konfigurert i denne installasjonen for den innloggede brukeren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/14-task-list.png)

### 10.1 **Navn**

Navnet på oppgaven.

### 10.2 **Oppgave**

Det planlagte tidspunktet oppgaven skal kjøre.

### 10.3 **Prosjekt**

Navnet på prosjektet der denne oppgaven skal kjøres.

### 10.4 **Status**

Status for denne oppgaven.

### 10.5 **Tilbake-knapp**

Klikk på denne knappen for å gå tilbake til [startsiden](#home-page)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 11. **Loggmappe**

Denne knappen åpner mappeplasseringen til Desktop Connector-loggene på det lokale systemet. Standardplasseringen for disse loggene er:

`C:\Users\<Windows account name>\AppData\Local\User Name\2b92d867-496c-47d1-ac42-fbf8fa355177\Cache\BimsyncApp`
