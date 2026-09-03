# Last opp en zip / filstruktur

Sammenlignet med å laste opp en vanlig zip-fil, vil funksjonen for opplasting av zip pakke ut en zip. På denne måten kan du importere en filstruktur til [dokumentsiden](https://support.catenda.com/en/articles/8204673-documents-page#h_28610e1d21) uten å måtte opprette mapper manuelt.

Funksjonen Last opp zip finnes i handlingsmenyen til høyre for den grønne + knappen øverst til høyre på Dokumenter-siden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/01-intro.png)

## 1. **Velge en zip-fil**

Etter å ha klikket på menyalternativet Last opp zip, åpnes følgende dialog:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/02-selecting-a-zip-file.png)

Systemfilutforskeren din bør åpnes automatisk. Hvis filutforskeren ikke åpnet seg eller ble lukket uten at du valgte en zip-fil, kan du åpne den igjen ved å klikke på knappen Velg zip-fil.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/03-selecting-a-zip-file.png)

Etter å ha valgt en zip-fil på det lokale systemet ditt, bør du se navnet på zip-filen som nedenfor, og opplastingsknappen for zip vil være uthevet i dypgrønt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/04-selecting-a-zip-file.png)

Hvis du ikke skrev inn en mappe i dokumentdelen, vil det si at innholdet vil bli pakket ut til rotmappen. Dette betyr at du vil se innholdet rett når du åpner Dokumenter-delen. Det er også mulig å navigere til en mappe i Catenda og laste opp zip-filen din der hvis du vil at filstrukturen skal vises der.

## 2. **Opplastingskonfigurasjon**

Innstillinger kan konfigureres for elementer med navn i zip-filen som allerede finnes på plasseringen der zip-utpakningen forsøker å plassere dem i Catenda-prosjektet.

### 2.1 **Mapper**

Nye mapper opprettes bare hvis en mappe med det samme navnet ikke allerede finnes på plasseringen der zip-filen forsøker å pakke ut en mappe til. Alle elementer i en mappe der en mappe med samme navn allerede finnes, blir plassert i den eksisterende mappen med samme navn i Catenda-prosjektet.

### 2.2 **Dokumenter**

Ulike handlinger kan konfigureres for hvordan utpakningen av zip-filen oppfører seg når et dokument med samme navn som filen i zip-filen allerede finnes på samme plassering som der zip-filen forsøker å pakke det ut i Catenda-prosjektet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/05-documents.png)

_Opprett ny revisjon - Standard_ Hvis et dokument med samme navn finnes på samme plassering som zip-en forsøker å pakke ut en fil til, opprettes en ny revisjon i det dokumentet.

_Hopp over og fortsett_ Hvis et dokument med samme navn finnes på samme plassering som zip-en forsøker å pakke ut en fil til, hoppes filen over og ingen ny revisjon opprettes i dokumentet.

### 2.3 **Bruk status**

Hvis statusarbeidsflyten er aktivert i prosjektet ditt, kan du konfigurere hva statusen for nye dokumenter skal være. Hvis du valgte alternativet opprett ny revisjon, endres statusen for dokumenter som mottar ny revisjon automatisk.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/06-apply-status.png)

Det er bare mulig å velge mellom delte revisjonsstatuser. Etter opplasting finnes de delte revisjonene i arbeidsfanen og kan senere publiseres.

## 3. **Laster opp**

Etter å ha klikket på last opp zip, begynner zip-en å laste opp

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/07-uploading.png)

Du kan fortsette å arbeide med Catenda i en annen fane mens du venter på at opplastingen skal bli ferdig.

_Påkrevd tilgang:_ Skrivetilgang til hver av stedene der mapper og dokumenter skal opprettes Skrivetilgang til dokumentrevisjoner som skal legges til.

## 4. **Pakker ut**

Etter at zip-en din er lastet opp, begynner Catenda å pakke ut zip-en din. Under utpakningen vil du se følgende meny nederst til venstre:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/08-extracting.png)

Du kan holde denne menyen åpen mens du blar gjennom Catenda, eller lukke den hvis du vil. Du kan til og med lukke nettleseren helt under utpakkingsprosessen. Zip-en vil fortsette å pakke ut i bakgrunnen. Hvis du brukte Catenda i en annen fane mens zip-en pakkes ut, vil du se mapper, dokumenter og revisjoner begynne å vises på plasseringen du pakket ut til ved å oppdatere siden.

### 4.1 **Utpakking fullført**

Når zip-en er ferdig med å pakkes ut, vil den si fullført i dialogen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/09-extraction-completed.png)

Klikk på vis detaljer for å se hvilke filer som ble pakket ut. Du vil senere kunne finne disse detaljene i "Mine zip-opplastinger" som forklart nedenfor. Oppdater siden for å se alle filene som har blitt lastet opp.

### 4.2 **Zip-import fullført varsel**

Hvis du har lukket dialogen, nettleseren eller oppdatert siden, vil du ikke lenger se dialogen. Du vil også få et varsel om at zip-utpakningen din er fullført. På denne måten vil du vite når zip-opplastingen din er fullført, selv om du ikke lenger ser utpakkingsdialogen.

## 5. **Omgå størrelsesbegrensningen for filer**

Opplasting av en zip-fil lar deg laste opp filer som er større enn 7 GB, da zip komprimerer filen.

## 6. **Mine zip-opplastinger**

Alternativet under zip-opplastingen i handlingsmenyen lar deg se en oversikt over dine tidligere zip-opplastinger. Slik kan zip-importer med de ulike mulige statusene se ut:

### 6.1 **Pakker ut**

Mens zip-en pakkes ut, begynner de pakkede filene å vises som rader i Dokumenter-tabellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/10-extracting.png)

_Fullført_ Når zip-importen er fullført, pakkes alle filer ut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/11-extracting.png)

### 6.2 **Zip-importside**

Klikk på en zip-import for å se mer informasjon om importprosessen. Slik kan zip-importsiden for en fullført zip-import se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/12-zip-import-page.png)

Slik kan høyremeny for zip-importsiden for en fullført zip-import se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/13-zip-import-page.png)

## 7. **Skrivebordskontakt**

Med [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) kan du automatisk, med jevne mellomrom, laste opp de nyeste versjonene av dokumenter fra det lokale systemet ditt til Catenda Hub. Desktop Connector er både raskere enn den vanlige opplastingsprosessen og minimerer risikoen for feil ved å laste opp dokumenter fil for fil i stedet for i en stor drag-and-drop eller zip-opplastingsbatch.
