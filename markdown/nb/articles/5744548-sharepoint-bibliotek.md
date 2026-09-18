# Sharepoint-bibliotek

> Denne artikkelen beskriver hvordan du setter opp en tilkobling til Sharepoint

For å opprette et SharePoint-bibliotek klikker du på [knappen for nytt bibliotek](https://support.catenda.com/en/articles/8065645-libraries-page#h_c6d56f227c) øverst til høyre på [bibliotekssiden](https://support.catenda.com/en/articles/8065645-libraries-page). Dette biblioteket kan brukes til å dele dokumenter fra en brukers SharePoint med andre medlemmer av Catenda-prosjektet. Når SharePoint-biblioteket er aktivert, kan det se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/01-intro.png)

Klikk [her](https://support.catenda.com/en/articles/9800091-sharepoint-library-short-video) for å se en kort video om hvordan du konfigurerer SharePoint-biblioteket.

Etter at du har gitt biblioteket et navn, åpnes en ny fane i nettleseren din der du blir bedt om å logge inn med SharePoint-kontoen din. Etter innlogging blir du tatt til innstillingssiden for biblioteket for SharePoint-biblioteket ditt, der du kan konfigurere SharePoint-mappen du ønsker å vise på Catenda.

## 1. **Topptekst –** Biblioteksnavn

På venstre side av toppteksten vil du se navnet på det gjeldende biblioteket. Hvis biblioteket er synkronisert, vil du se et hakesymbol ved siden av navnet. Når du synkroniserer, forblir biblioteket synkronisert i 3 måneder. Etter det kan du se et utropstegn her med et verktøytips som sier at synkroniseringen mislyktes. Når dette skjer, gå til biblioteksinnstillinger og gi tilgang en gang til.

## 2. **Topptekst** – Biblioteksinnstillinger

På høyre side av toppteksten vil du kunne se en handlingsmeny som kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/02-header-library-settings.png)

I biblioteksinnstillingene kan du konfigurere SharePoint-biblioteket ditt. _Nødvendig tilgang:_ Bibliotekslager

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/03-header-library-settings.png)

### 2.1 **Tilkobling**

Hvis du har koblet til kontoen din, kan du klikke på Tilbakekall tilgang for å tilbakekalle tilgangen du har gitt Catenda til SharePoint-kontoen din. Hvis du ikke har gitt tilgang, kan du klikke på Gi tilgang her for å gå gjennom tilgangsprosessen for å gi Catenda tilgang til kontoen din.

### 2.2 **Detaljer**

Klikk på blyantsymbolet for å endre navn på dette biblioteket.

### 2.3 **Delt mappe**

Åpne denne menyen og klikk på rediger for å velge en delt mappe fra en av SharePoint-nettstedene dine som du ønsker å vise i dette SharePoint-biblioteket.

> **Merknad:** For at en mappe skal vises i denne listen, må den være satt til offentlig i SharePoint

### 2.4 **Tilgangskontroll**

Her kan du bestemme hvem som har tillatelse til å få tilgang til dette biblioteket i prosjektet ditt.

### 2.5 **Slett**

Åpne denne menyen og klikk på slett for å fjerne dette SharePoint-biblioteket fra Catenda-prosjektet ditt

## 3. **Topptekst – Biblioteksinnstillinger –** Nytt bibliotek

Klikk på knappen Nytt bibliotek for å opprette et nytt bibliotek

## 4. **Filtermeny**

### 4.1 **Lagrede filtre**

Klikk [her](https://support.catenda.com/en/articles/8551755-saving-filters) for å lese mer om hvordan du lagrer et sett med filtre

### 4.2 **Ikke koblet –** `link=unlinked`

Med dette filteret kan du filtrere etter alle dokumenter som ikke er koblet til objekter.

### 4.3 **Koblet til valgte objekter –** `link=backlink`

Hvis du har valgt objekter i 3D-visningen som er koblet til SharePoint-dokumenter, kan du filtrere etter dem her.

## 5. **SharePoint-dokumentliste**

Her kan du navigere alle dokumentene og mappene i den delte mappen som er konfigurert for dette biblioteket.

### 5.1 **Handlinger**

Etter at du har valgt ett eller flere dokument(er) eller mappe(r), vil du se følgende handlingsmeny vises øverst på dokumentlisten. Den eksisterende menyen for varerhandlinger kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/04-actions.png)

_Koble/fjern kobling_ Hvis du velger et objekt fra en modell i 3D, kan du kople/fjerne koblingen til de valgte elementene.

_Forhåndsvisning_ Åpne en forhåndsvisning av dokumentet uten å måtte laste inn dokumentsiden. Dette kan være spesielt nyttig i en mappe med mange bilder. Bare synlig når ett enkelt dokument er valgt

_Last ned_ Klikk på last ned for å laste ned det valgte dokumentet. Bare synlig når ett enkelt dokument er valgt

### 5.2 **Navn**

Klikk på navnet på en mappe for å se innholdet. Klikk på navnet på et dokument for å se innholdet

### 5.3 **Url**

Klikk på nedlastingsknappen i denne kolonnen for å laste ned dokumentet.

### 5.4 **Lenker**

Hvis noen objekter har blitt koblet til dokumentene dine, vil du kunne se antall koblede objekter her. Hvis du klikker på dette nummeret, kan du:

_Velg objekter_

_Isoler objekter_

_Last som spørring_

## 6. **Høyre informasjonsmeny**

Når du først åpner og velger et dokument i dokumentlisten, kan høyre meny være lukket. Du kan klikke på informasjonsknappen nederst til høyre på [dokumentbanneret](https://support.catenda.com/en/articles/8461918-document-banner-actions-navigation) for å utvide denne menyen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/05-right-information-menu.png)

### 6.1 **Koblede objekter**

Her kan du koble objekter til SharePoint-dokumentene dine.

### 6.2 **Saker**

Etter at du åpner et dokument, vil du kunne se saksmenyalternativet. Her vil du kunne kople SharePoint-dokumentene dine til saker.

## 7. **Tillatelser**

Når dokumenter lastes opp fra et SharePoint-dokumentbibliotek til Catenda, brukes sharepoint rest-api (via [pnpjs](https://pnp.github.io/pnpjs/)-biblioteket). Siden disse tillatelsene er gitt til spfx-løsninger OOTB, er ingen tilleggstillatelse nødvendig. Følgende tillatelser vil være nødvendige for at appen skal få tilgang til Catenda-baksystemet. Bare delegerte tillatelser brukes med følgende område: _[User.Read](https://graphpermissions.merill.net/permission/User.Read) [offline\_access](https://graphpermissions.merill.net/permission/offline_access) [Files.Read](https://graphpermissions.merill.net/permission/Files.Read)_ _[Sites.Read.All](https://graphpermissions.merill.net/permission/Sites.Read.All)_ Tilgangen ovenfor brukes bare til å godkjenne deling av dokumenter til brukerens Catenda-prosjekt.
