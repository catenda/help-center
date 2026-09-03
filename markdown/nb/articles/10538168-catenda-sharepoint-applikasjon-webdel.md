# Catenda SharePoint-applikasjon – Webdel

Med Catenda-webdelen kan du bla gjennom dokumentdelen av et Catenda-prosjekt på en SharePoint-side. _Catenda-tilgang påkrevd:_ Les for å bla gjennom dokumentstrukturen og skriv for å laste opp SharePoint-filer til Catenda.

## 1. **Legge til webdelen**

Rediger en eksisterende side eller opprett en ny side i SharePoint og rediger den. Hold musepekeren over siden i redigeringsmodus til du ser en linje med et plusstegn `----+-----` Hvis [Catenda SharePoint-applikasjonen](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application) er lagt til på nettstedet ditt, vil du kunne finne Catenda-dokumentwebdelen i listen over webdeler.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/01-adding-the-webpart.png)

Du vil da kunne legge til en Catenda-webdel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/02-adding-the-webpart.png)

Hvis du ikke allerede har godkjent Catenda-kontoen din, vil webdelen se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/03-adding-the-webpart.png)

Hvis du åpner en side med Catenda-webdelen aktivert og du ikke ennå har godkjent kontoen din, blir du bedt om å gjøre det. Les mer om hvordan du godkjenner kontoen din [her](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application#h_788fe15988).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/04-adding-the-webpart.png)

Etter å ha godkjent kontolegitmasjonen din, klikker du på Åpne webdelinnstillinger eller klikker på blyantikonen for å velge Catenda-prosjektet som SharePoint-sidesbesøkende skal kunne se dokumentdelen for.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/05-adding-the-webpart.png)

Slik kan en konfigurert webdel se ut når den legges til:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/06-adding-the-webpart.png)

## 2. **Navigasjon**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/07-navigation.png)

### 2.1 **Visning**

Banen øverst på webdelen viser prosjektet som er konfigurert for denne webdelen og din nåværende mappestrukturlokasjon.

### 2.2 **Navigering**

Klikk på ett av elementene for å gå tilbake til denne delen av mappestrukturen. Klikk på navnet på en mappe for å åpne den mappen. Klikk på navnet på et dokument for å åpne det direkte i Catenda.

## 3. **Dokumenttabell**

dokumenttabellen kan se omtrent slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/08-document-table.png)

Hvis du har valgt noen elementer, vil du se antallet valgte elementer øverst på dokumenttabellen.

### 3.1 **Velge Dokumenter og mapper**

Hvis du klikker hvor som helst utenfor navnet på elementet i en rad, velges denne raden. Hold Skift for å velge alle elementer mellom det sist valgte elementet og elementet du klikker på. Hold Ctrl for å legge til/fjerne elementer i markeringen din.

### 3.2 **Catenda-tilgangsinnstillinger**

Hver bruker har sin egen tilgang i Catenda, så noen av prosjektmedlemmene dine kan se andre mapper og Dokumenter enn andre.

## 4. **Handlinger i webdelen**

Øverst til venstre på webdelen finner du følgende handlinger:

### 4.1 **Opprett mappe**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/09-create-folder.png)

Oppretter en mappe i den delen av dokumentstrukturen du er i. _Catenda-tilgang påkrevd:_ Skrivetilgang

### 4.2 **Last opp fil**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/10-upload-file.png)

Etter å ha klikket på dette åpnes en filnavigator, og du kan velge hvilke dokument(er) du vil laste opp. Etter opplasting av dokumentet vil du se det både i Catenda og i webdelen. Du vil ikke se den opplastede filen i SharePoint-dokumentområdet på denne måten. Bare i Catenda. _Catenda-tilgang påkrevd:_ Skrivetilgang Du kan dra og slippe filer fra systemet ditt på en destinasjon i webdelen for å laste opp disse filene til Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/11-upload-file.png)

> **Merk:** Hvis du drar og slipper en mappe, blir den publisert som en zip-fil. Hvis du ønsker å laste opp en mappestruktur, må du laste den ned fra SharePoint og laste den opp til Catenda enten via [zip-opplastingen](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) eller [Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector).

### 4.3 **Last på nytt**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/12-reload.png)

Hvis noen andre har gjort endringer i Catenda-prosjektet, kan det hende at du ikke ser dem ennå. I så fall kan det være en god idé å laste webdelen på nytt for å få den mest oppdaterte informasjonen.

### 4.4 Publiser til SharePoint

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/13-publish-to-sharepoint.png)

Publiser valgte Dokumenter fra Catenda til SharePoint Hvis du klikker denne knappen, åpnes dialogboksen for publisering til SharePoint:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/14-publish-to-sharepoint.png)

Øverst i dialogboksen vil du se hvor mange elementer du publiserer.

_Ny lokasjon_ Velg «Ny lokasjon» hvis du ønsker å publisere de valgte filene til en ny lokasjon i SharePoint.

_Vis eksisterende mål_ Hvis filene allerede ble publisert før og du ønsker å oppdatere tidligere publiserte filer, bør du velge «Vis eksisterende mål».

_Publiser_ Etter å ha konfigurert lokasjonen du vil publisere til, klikker du publiser.

## 5. **Catenda-tilgang**

### 5.1 **Ingen tilgang til Catenda-prosjektet**

Hvis du ikke har tilgang til det konfigurerte prosjektet, vil du se følgende feil.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/15-no-access-to-the-catenda-project.png)

Den uskarpe delen er prosjekt-GUID. Hvis det ikke finnes noen, eller du ikke har tilgang til noen Dokumenter i prosjektet, vil det si «Ingen innhold – mappen er tom».

### 5.2 **Ingen tilgang til å opprette mapper**

Hvis du ikke har skrivetilgang til mappen du er i og prøver å opprette en ny undermappe, vil du se dette:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/16-no-access-to-creating-folders.png)

### 5.3 **Ingen tilgang til å laste opp filer**

Hvis du ikke har skrivetilgang til mappen eller dokumentet og prøver å laste opp en fil, vil du se dette:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/17-no-access-to-uploading-files.png)
