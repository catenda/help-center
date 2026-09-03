# Sharepoint bibliotheek

> Dit artikel beschrijft hoe u een verbinding met Sharepoint instelt

Om een SharePoint-bibliotheek te maken, klikt u op de knop [nieuwe bibliotheek](https://support.catenda.com/en/articles/8065645-libraries-page#h_c6d56f227c) in de rechterbovenhoek van de [pagina Bibliotheek](https://support.catenda.com/en/articles/8065645-libraries-page). Deze bibliotheek kan worden gebruikt om documenten van een gebruiker SharePoint met de andere leden van het Catenda-project te delen. Wanneer de SharePoint-bibliotheek is geactiveerd, kan deze er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/01-intro.png)

Klik [hier](https://support.catenda.com/en/articles/9800091-sharepoint-library-short-video) om een korte video te bekijken over hoe u de SharePoint-bibliotheek configureert.

Nadat u de bibliotheek een naam hebt gegeven, wordt een nieuw tabblad in uw browser geopend waar u wordt gevraagd u aan te melden met uw SharePoint-account. Na aanmelding gaat u naar de pagina Bibliotheek instellingen van uw SharePoint-bibliotheek, waar u de SharePoint-map kunt configureren die u in Catenda wilt weergeven.

## 1. **Header -** Bibliotheek naam

Aan de linkerkant van de header ziet u de naam van de huidige bibliotheek. Als de bibliotheek is gesynchroniseerd, ziet u een vinkje naast de naam. Als u de bibliotheek synchroniseert, blijft deze 3 maanden gesynchroniseerd. Daarna ziet u mogelijk een uitroepteken met een tooltip dat zegt dat synchronisatie is mislukt. Als dit gebeurt, gaat u naar de bibliotheek instellingen en verleent u opnieuw toegang.

## 2. **Header** - Bibliotheek instellingen

Aan de rechterkant van de header kunt u een actiemenu zien dat er ongeveer zo uit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/02-header-library-settings.png)

In de bibliotheek instellingen kunt u uw SharePoint-bibliotheek configureren. _Vereiste toegang:_ Bibliotheek maker

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/03-header-library-settings.png)

### 2.1 **Verbinding**

Als u uw account hebt gekoppeld, kunt u op Toegang intrekken klikken om de toegang die u aan Catenda hebt gegeven tot uw SharePoint-account in te trekken. Als u geen toegang hebt gegeven, kunt u hier op Toegang verlenen klikken om het toegangsproces door te lopen en Catenda toegang tot uw account te geven.

### 2.2 **Details**

Klik op het potloodpictogram om de naam van deze bibliotheek te wijzigen.

### 2.3 **Gedeelde map**

Open dit menu en klik op bewerken om een gedeelde map van een van uw SharePoint Sites te kiezen die u in deze SharePoint-bibliotheek wilt weergeven.

> **Opmerking:** Voor een map om in deze lijst te worden weergegeven, moet deze in SharePoint op openbaar worden ingesteld

### 2.4 **Toegangscontrole**

Hier kunt u bepalen wie deze bibliotheek in uw project mag openen.

### 2.5 **Verwijderen**

Open dit menu en klik op verwijderen om deze SharePoint-bibliotheek uit uw Catenda-project te verwijderen

## 3. **Header - Bibliotheek instellingen -** Nieuwe bibliotheek

Klik op de knop Nieuwe bibliotheek om een nieuwe bibliotheek te maken

## 4. **Filtermenu**

### 4.1 **Opgeslagen filters**

Klik [hier](https://support.catenda.com/en/articles/8551755-saving-filters) voor meer informatie over hoe u een set filters opslaat

### 4.2 **Niet gekoppeld -** `link=unlinked`

Met dit filter kunt u alle documenten filteren die niet aan objecten zijn gekoppeld.

### 4.3 **Gekoppeld aan geselecteerde objecten -** `link=backlink`

Als u objecten in de 3D-viewer hebt geselecteerd die zijn verbonden met SharePoint-documenten, kunt u hier naar filteren.

## 5. **SharePoint-documentlijst**

Hier kunt u alle documenten en mappen in de gedeelde map navigeren die voor deze bibliotheek is geconfigureerd.

### 5.1 **Acties**

Nadat u één of meer document(en) of map(pen) hebt geselecteerd, ziet u het volgende actiemenu bovenaan de documentlijst verschijnen. Het bestaande actiemenu voor items kan er ongeveer zo uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/04-actions.png)

**Koppelen/ontkoppelen** Als u een object uit een 3D-model selecteert, kunt u het aan uw geselecteerde elementen koppelen/ontkoppelen.

**Voorbeeld** Open een voorbeeld van het document zonder de documentpagina te hoeven laden. Dit kan vooral handig zijn in een map met veel afbeeldingen. Alleen zichtbaar als één document is geselecteerd

**Downloaden** Klik op downloaden om uw geselecteerde document te downloaden. Alleen zichtbaar als één document is geselecteerd

### 5.2 **Naam**

Klik op de mapnaam om de inhoud ervan weer te geven Klik op de documentnaam om de inhoud ervan te bekijken

### 5.3 **URL**

Klik op de downloadknop in deze kolom om het document te downloaden.

### 5.4 **Koppelingen**

Als objecten aan uw documenten zijn gekoppeld, kunt u hier het aantal gekoppelde objecten zien. Als u op dit getal klikt, kunt u:

**Selecteer objecten**

**Isoleer objecten**

**Laden als zoekopdracht**

## 6. **Rechts informatiemenu**

Als u een document in de documentlijst selecteert, is het rechtermenu mogelijk gesloten. U kunt op de informatieknop rechtonder op de [documentbanner](https://support.catenda.com/en/articles/8461918-document-banner-actions-navigation) klikken om dit menu uit te vouwen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xt4043w9/05-right-information-menu.png)

### 6.1 **Gekoppelde objecten**

Hier kunt u objecten aan uw SharePoint-documenten koppelen.

### 6.2 **Onderwerpen**

Nadat u een document hebt geopend, ziet u het menu Onderwerpen. Hier kunt u uw SharePoint-documenten aan onderwerpen koppelen.

## 7. **Machtigingen**

Wanneer documenten van een SharePoint-documentbibliotheek naar Catenda worden geüpload, wordt de sharepoint rest-api gebruikt (via de [pnpjs](https://pnp.github.io/pnpjs/) bibliotheek). Aangezien deze machtigingen standaard aan spfx-oplossingen worden verleend, hoeft er geen aanvullende machtiging te worden verleend. De volgende machtigingen zijn nodig zodat de app toegang heeft tot de Catenda-backend. Alleen gedelegeerde machtigingen worden gebruikt met de volgende bereiken: _[User.Read](https://graphpermissions.merill.net/permission/User.Read) [offline\_access](https://graphpermissions.merill.net/permission/offline_access) [Files.Read](https://graphpermissions.merill.net/permission/Files.Read)_ _[Sites.Read.All](https://graphpermissions.merill.net/permission/Sites.Read.All)_ De bovenstaande toegang wordt alleen gebruikt om het delen van documenten met het Catenda-project van gebruikers goed te keuren.
