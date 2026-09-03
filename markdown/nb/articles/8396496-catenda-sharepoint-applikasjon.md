# Catenda SharePoint-applikasjon

> **Merknad:** Installeringsfilen for programtillegget finnes i [denne artikkelen](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Hvis Catenda SharePoint Application legges til på et SharePoint-nettsted, kan filer publiseres fra SharePoint til Catenda og Catenda-dokumentstrukturen kan vises i SharePoint. Når den er konfigurert, kan applikasjonen se slik ut: <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/inline-628ad1424b68.png" width="300"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/inline-910393724d2c.png" width="300"/> Denne artikkelen inneholder informasjon om hvordan denne applikasjonen fungerer Se [her](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq) for mer informasjon om hvordan denne applikasjonen kan være nyttig. Se [her](https://support.catenda.com/en/articles/9453368-adding-and-removing-the-catendasp-app) for hvordan du legger til SharePoint-applikasjonen på et nettsted.

## 1. **Publisering til Catenda med listkommandoen**

Med listkommandoen er det mulig å publisere én eller flere filer til Catenda.

> **Merknad:** Det er bare mulig å publisere filer. Mappestrukturer kan lastes ned fra SharePoint og lastes opp til Catenda via [zip-opplasting](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) eller [Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector).

### 1.1 **Finne listkommandoen**

_Én fil_ Hvis du vil publisere én fil til Catenda, er den enkleste måten å klikke på Publiser til Catenda i hamburgermenylinjen for filen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/01-finding-the-list-command.png)

_Flere filer_ Hvis du vil publisere flere filer til Catenda, må du velge filene du vil publisere. Etter filene dine i SharePoint vil brukerne kunne se en Publiser til Catenda-listkommando.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/02-finding-the-list-command.png)

Hvis det ikke er nok plass i kommandolinjen, kan du se kommandoen i hamburgermenylinjen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/03-finding-the-list-command.png)

> **Merknad:** Filer kan bare publiseres fra listevisning da listkommandoen ikke er tilgjengelig i rutenettvisning.

### 1.2 **Publisering av filen**

Etter at du klikker på Publiser til Catenda, åpnes følgende meny som kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/04-publishing-the-file.png)

Hvis du ikke har gitt SharePoint tilgang til Catenda-kontoen din, blir du bedt om å autorisere den. [Se nedenfor](#h_788fe15988) for hvordan du autoriserer kontoen din.

_Velge en mappe_ Hvis du har gitt tilgang til Catenda-kontoen din, kan du velge prosjektet, biblioteket og destinasjonsmappen på Catenda, og publisere.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/05-publishing-the-file.png)

Visningen av mappestrukturen i SharePoint er konsistent med visningen i Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/06-publishing-the-file.png)

Hvis et dokument med samme navn som filen din ikke allerede finnes i mappen du publiserer til, vises det som et nytt dokument i Catenda. Hvis filen du publiserer har samme navn som et dokument i mappen du publiserer til, vil filen være en ny revisjon av det dokumentet.

> **Merknad:** Det er bare mulig å publisere dokumenter og ikke laste opp kladder

Etter at en fil er publisert, kan brukere flytte, gi nytt navn og slette filen. _Catenda-tilgang påkrevd:_ Full tilgang, vanligvis gitt til brukere som utgiver eller administrator. Endring av filen på Catenda endrer ingenting på SharePoint. På samme måte, hvis filen endres på SharePoint, endres ingenting på Catenda.

## 2. **Catenda Webpart**

Med denne applikasjonen legger du til [Catenda webpart](https://support.catenda.com/en/articles/10538168-catenda-sharepoint-application-webpart) på en side på nettstedet ditt. Du kan la brukere bla gjennom områdene som de har lesebeskyttelse til i dokumentdelen av et Catenda-prosjekt. Hvis de har skrivetilgang til noen del av dokumentstrukturen, kan de også laste opp filer der.

Slik kan en konfigurert webpart se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/07-catenda-webpart.png)

## 3. **Autorisering av Catenda-kontoen din**

Hvis du navigerer til en SharePoint-side der Catenda Webpart er aktivert, eller du prøver å bruke publiseringshandlingen og du ikke har validert kontoen din ennå, får du følgende popupp:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/08-authorizing-your-catenda-account.png)

_Tilgang påkrevd:_ API-tilgang ved installering av applikasjon Hvis en ny nettleserfane ikke åpnes automatisk, kopierer du lenken fra fanen for kontovalidering som er åpen, og navigerer dit selv. Hvis du ikke allerede er logget på, blir du bedt om å logge på Catenda i dette vinduet. Hvis du ikke allerede har en, kan du opprette en Catenda-konto [her](https://hub.catenda.com/signup).

> **Merknad:** E-postadressen som er knyttet til Catenda-kontoen du logger inn med, må være den samme som adressen som er knyttet til SharePoint-kontoen du er logget på med.

Autentiseringsvinduet kan se ut som dette:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/09-authorizing-your-catenda-account.png)

Ved å tillate appen tilgang til kontoen din kan du publisere dokumenter fra SharePoint til hvilken som helst del av Catenda-prosjektet(ene) ditt som du har skrivetilgang til i [dokumentdelen](https://support.catenda.com/en/articles/8204673-documents-page). Hvis en webpart er lagt til på en side på nettstedet ditt, kan du også se alle dokumenter som du har lesebeskyttelse til i Catenda-prosjektet som ble konfigurert av personen som la til webparten. Med webparten kan du også publisere dokumenter fra systemet ditt til hvilken som helst del av det konfigurerte Catenda-prosjektet som du har skrivetilgang til i [dokumentdelen](https://support.catenda.com/en/articles/8204673-documents-page).

> **Merknad:** Catenda vil ikke ha tilgang til SharePoint-dokumentene dine. Hvis du publiserer et dokument til Catenda, mottar Catenda det i en enveistransaksjon.

Hvis du ikke lenger ønsker å gi appen tilgang til Catenda-kontoen din, kan du alltid tilbakekalle tilgangen på [applikasjonssiden](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) på Catenda-kontoen din.
