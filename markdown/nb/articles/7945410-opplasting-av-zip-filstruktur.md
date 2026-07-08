# Last opp en zip / filstruktur

Sammenlignet med å laste opp en vanlig zip-fil, vil funksjonen for lastning av zip pakke ut en zip. På denne måten kan du importere en filstruktur til [dokumentsiden](https://support.catenda.com/en/articles/8204673-documents-page#h_28610e1d21) uten å måtte opprette mapper manuelt.

Funksjonen for lastning av zip finner du i handlingsmenyen til høyre for den grønne + knappen øverst til høyre på dokumentsiden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/01-intro.png)

## 1. **Velge en zip-fil**

Etter å ha klikket på menyelementet Last opp zip, åpnes følgende dialog:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/02-selecting-a-zip-file.png)

Filutforskeren på systemet ditt bør åpnes automatisk. Hvis filutforskeren ikke åpnes, eller hvis den ble lukket uten å velge en zip-fil, kan du åpne den igjen ved å klikke på knappen Velg zip-fil.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/03-selecting-a-zip-file.png)

Etter å ha valgt en zip-fil på det lokale systemet ditt, bør du se navnet på zip-filen som nedenfor, og knappen for lastning av zip blir uthevet i dyp grønn.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/04-selecting-a-zip-file.png)

Hvis du ikke skrev inn en mappe i dokumentdelen, vil det si at innholdet vil bli pakket ut til rotmappen. Dette betyr at du vil se innholdet når du åpner dokumentdelen. Det er også mulig å navigere til en mappe i Catenda og laste opp zip-filen din der hvis du vil at filstrukturen skal vises der.

## 2. **Konfigurasjon av lastning**

Innstillinger kan konfigureres for elementer med navn i zip-filen som allerede finnes på stedet der zip-utpakking forsøker å plassere dem i Catenda-prosjektet.

### 2.1 **Mapper**

Nye mapper opprettes bare hvis det ikke allerede finnes en mappe med det navnet på stedet der zip-en forsøker å pakke ut en mappe til. Alle elementer i en mappe der en mappe med samme navn allerede finnes, vil bli plassert i den eksisterende mappen med samme navn i Catenda-prosjektet.

### 2.2 **Dokumenter**

Ulike behov kan konfigureres for hvordan utpakkingen av zip-filen oppfører seg når et dokument med samme navn som filen i zip-filen allerede finnes på samme sted som der zip-filen forsøker å pakke den ut til i Catenda-prosjektet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/05-documents.png)

_Opprett ny revisjon - Standard_ Hvis et dokument med samme navn finnes på samme sted som zip-en forsøker å pakke ut en fil til, vil en ny revisjon bli opprettet i det dokumentet.

_Hopp over og fortsett_ Hvis et dokument med samme navn finnes på samme sted som zip-en forsøker å pakke ut en fil til, vil filen bli hoppet over og ingen ny revisjon vil bli opprettet i dokumentet.

### 2.3 **Bruk status**

Hvis statusarbeidsflyten har blitt aktivert i prosjektet ditt, vil du kunne konfigurere hva statusen til nye dokumenter skal være. Hvis du velger alternativet opprett ny revisjon, vil statusen til dokumenter som mottar ny revisjon bli endret automatisk.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/06-apply-status.png)

Det er bare mulig å velge mellom delte revisjonsstatuser. Etter lastning kan de delte revisjonene finnes i arbeidsflaten-fanen og kan senere publiseres.

## 3. **Laster opp**

Etter å ha klikket på last opp zip, vil zip-en din begynne å laste opp

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/07-uploading.png)

Du kan fortsette å arbeide med Catenda på en annen fane mens du venter på at lastingen skal bli ferdig.

_Tilgang påkrevd:_ Skrivetilgang til hver av stedene der mapper og dokumenter vil bli opprettet Skrivetilgang til dokumentrevisjonene som vil bli lagt til.

## 4. **Pakker ut**

Etter at zip-en din er lastet opp, vil Catenda begynne å pakke ut zip-en din. Under utpakkingen vil du se følgende meny nederst til venstre:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/08-extracting.png)

Du kan holde denne menyen åpen mens du surfer i Catenda, eller lukke den hvis du vil. Du kan til og med lukke nettleseren helt under utpakkingsprosessen. Zip-en vil fortsette å pakke ut i bakgrunnen. Hvis du brukte Catenda i en annen fane mens zip-en pakker ut, vil du se mapper, dokumenter og revisjoner begynne å vises på stedet du pakket ut til ved å oppdatere siden.

### 4.1 **Utpakking fullført**

Når zip-en er ferdig pakket ut, vil det si ferdig i dialogen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/09-extraction-completed.png)

Klikk på vis detaljer for å se hvilke filer som ble pakket ut. Du vil senere være i stand til å finne disse detaljene i "Mine zip-opplastinger" som forklart nedenfor. Oppdater siden for å se alle filene som har blitt lastet opp.

### 4.2 **Melding om fullført zip-import**

Hvis du har lukket dialogen, nettleseren eller oppdatert siden, vil du ikke lenger se dialogen. Du vil også få en melding om at zip-utpakkingen din er fullført. På denne måten vil du vite når zip-lastingen din er fullført, selv om du ikke lenger ser utpakkingsdialogen.

## 5. **Omgå størrelsesbegrensningen for filer**

Å laste opp en zip lar deg laste opp filer som er større enn 7 gb fordi zip-en komprimerer filen.

## 6. **Mine zip-opplastinger**

Alternativet under zip-lastingen i handlingsmenyen lar deg se en oversikt over dine tidligere zip-opplastinger. Dette er hvordan zip-importer med de ulike mulige statusene kan se ut:

### 6.1 **Pakker ut**

Mens zip-en pakker ut, begynner de utpakkede filene å dukke opp som rader i dokumenttabellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/10-extracting.png)

_Fullført_ Når zip-importen er fullført, er alle filer pakket ut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/11-extracting.png)

### 6.2 **Zip import-side**

Klikk på en zip-import for å se mer informasjon om importprosessen. Dette er hvordan zip import-siden av en fullført zip-import kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/12-zip-import-page.png)

Dette er hvordan høyre meny på zip import-siden av en fullført zip-import kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/13-zip-import-page.png)

## 7. **Skrivebordskontakt**

Med [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) kan du automatisk, med regelmessige intervaller, laste opp de nyeste versjonene av dokumenter fra det lokale systemet ditt til Catenda Hub. Desktop Connector er både raskere enn den vanlige lastingsprosessen og minimerer risikoen for feil ved å laste opp dokumenter fil for fil i stedet for i én stor dra og slipp eller zip-lastingsbatch.
