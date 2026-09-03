# De Catenda SharePoint-app inschakelen

> **Opmerking:** Het installatiebestand voor de invoegtoepassing vindt u in [dit artikel](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

De Catenda SharePoint-toepassing kan door een systeembeheerder voor een SharePoint-omgeving worden ingeschakeld en vervolgens door een site-eigenaar aan een site worden toegevoegd. Met deze app kunnen SharePoint-gebruikers Documenten in Catenda samen met andere Leden van het bouwproject bekijken, beheren en hieraan samenwerken.

Als u de app voor uw omgeving wilt inschakelen, kunt u deze hier vinden: [Microsoft AppSource](https://appsource.microsoft.com/en-us/marketplace/apps?search=Catenda&page=1), wat er ongeveer zo uitziet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/01-intro.png)

Nadat u op "Nu downloaden" hebt geklikt, wordt u gevraagd zich aan te melden bij uw SharePoint-account, mits u niet al bent aangemeld. U wordt dan omgeleid naar de SharePoint Store-vermelding. De SharePoint Store kunt u ook vinden door op uw profiel rechtsboven in SharePoint te klikken en vervolgens op Een app toevoegen te klikken

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/02-intro.png)

In de SharePoint Store kunt u ook naar de Catenda SharePoint-toepassing zoeken:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/03-intro.png)

**https://\<Tenant>.sharepoint.com/sites/appcatalog/\_layouts/15/appStore.aspx/sharePointStore?entry=ClassicAppCatalog&sorting=7&search=catenda**

De SharePoint Store-vermelding kan er ongeveer zo uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/04-intro.png)

**https://\<Tenant>.sharepoint.com/\_layouts/15/appStore.aspx/appDetail/WA200005981**

## 1. **Normale SharePoint-gebruikers**

Normale SharePoint-gebruikers kunnen verzoeken om de Catenda SharePoint-app in te schakelen door op de knop App aan site toevoegen te klikken. U kunt zien of uw aanvraag is goedgekeurd op de pagina Mijn aanvragen in de SharePoint Store. Als u beheerder bent, kunt u het verzoek goedkeuren vanuit de app-catalogus

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/05-regular-sharepoint-users.png)

**https://\<Tenant>.sharepoint.com/sites/appcatalog/SitePages/Home.aspx**

## 2. **SharePoint-beheerders**

Als beheerder in een SharePoint-omgeving kunt u de app inschakelen door op App aan site toevoegen te klikken. Hier wordt u gevraagd om gegevenstoegang te bevestigen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/06-sharepoint-administrators.png)

### 2.1 **Gegevenstoegang bevestigen**

De app die u gaat inschakelen, heeft toegang tot gegevens via de identiteit van de persoon die deze gebruikt. Schakel deze app alleen in als u de ontwikkelaar of uitgever vertrouwt. De app heeft deze machtiging nodig om te weten welke bestanden van gebruikers moeten worden gepubliceerd wanneer zij ervoor kiezen deze te publiceren. Het eindpunt is: [https://sharepoint.plugins.catenda.com/1.0.0.0/](https://sharepoint.plugins.catenda.com/1.0.0.0/)

### 2.2 **API-toegang**

Als API-toegang niet eerder is ingeschakeld, moet deze worden ingeschakeld om de toepassing te laten werken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/07-api-access.png)

Als u API-toegang wilt goedkeuren, gaat u naar de pagina API-toegang in uw admin center https://\<Tenant>.sharepoint.com/\_layouts/15/online/AdminHome.aspx#/webApiPermissionManagement

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/08-api-access.png)

API-toegang is nodig omdat SharePoint-beheerders hun Catenda-account moeten verbinden om publicatie van Documenten in te schakelen. Gebruikers wordt ook gevraagd zich aan te melden met hun Catenda-account wanneer zij iets naar Catenda willen publiceren, omdat elke gebruiker verschillende machtigingen in Catenda kan hebben.

Zonder API-toegang kan de Catenda SharePoint-toepassing worden ingeschakeld, waarna zowel de lijstactie als het webonderdeel zichtbaar zijn, maar niet bruikbaar zijn, omdat zonder verbinding met uw Catenda-account geen gegevens kunnen worden uitgewisseld. _Vereiste toegang:_ Rol Globale beheerder of Toepassingsbeheerder in Microsoft 365.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/09-api-access.png)

**Toegang goedkeuren** Selecteer Catenda in de lijst met aanvragen in behandeling en klik bovenaan op Goedkeuren. Om de Catenda-toepassing te laten werken, is de volgende machtiging nodig: toegang

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/10-api-access.png)

**Toegang verwijderen** Selecteer Catenda op de pagina API-toegang en klik bovenaan op Verwijderen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/11-api-access.png)

Klik in het volgende menu op Verwijderen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/12-api-access.png)

Hoewel de Catenda-toepassing ingeschakeld kan zijn, kunnen gebruikers zich na verwijdering van deze toegang niet verbinden met Catenda.

## 3. **App-beschikbaarheid**

### 3.1 **Alleen deze app inschakelen**

Deze optie schakelt de app in voor de SharePoint-omgeving, waardoor site-eigenaren in uw omgeving de app van de pagina Mijn apps aan hun site kunnen toevoegen. De app doet niets totdat deze aan een site wordt toegevoegd. Hoewel deze optie uitstekend is, kunt u, als u meer controle wilt over welke sites gebruikers Documenten naar Catenda kunnen publiceren, dit verwarrend maken voor gebruikers als sommige sites de optie hebben om te publiceren en andere niet. Voor nog meer controle kunt u de [app-catalogus van siteverzameling](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/site-collection-app-catalog) inschakelen, waarmee u kunt kiezen welke apps site-eigenaren kunnen installeren. Met deze optie is de app ook standaard niet ingeschakeld op nieuwe sites, wat meer werk betekent om een nieuwe site te configureren wanneer deze wordt gemaakt.

### 3.2 **Deze app inschakelen en aan alle sites toevoegen**

Met deze optie wordt de app automatisch aan alle sites toegevoegd. Het enige visuele verschil dat de gebruiker ziet wanneer de app aan hun site wordt toegevoegd, is dat zij in hun lijst en hamburgermenu de lijstopdracht hebben wanneer zij een Document selecteren. Webonderdelen en volledige pagina's moeten later worden toegevoegd. Dit kan later ook worden gedaan via de pagina Apps beheren.

### 3.3 **Toevoegen aan teams**

Met deze optie wordt de app ook aan Teams toegevoegd. Hierdoor kunnen gebruikers het tabblad Teams zien. Dit kan later ook worden gedaan via de pagina Apps beheren.

## 4. **Apps beheren**

Nadat u de app hebt ingeschakeld, kunnen SharePoint-beheerders uw app in het gebied Apps beheren zien. https://\<Tenant>.sharepoint.com/sites/appcatalog/AppCatalog/Forms/AllItems.aspx

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/13-manage-apps.png)

Nadat u de app hebt geselecteerd, kan deze worden toegevoegd aan verschillende onderdelen van SharePoint.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/14-manage-apps.png)

### 4.1 **Toevoegen aan alle sites:**

Hierdoor wordt de app aan alle sites en alle nieuwe sites die worden gemaakt toegevoegd. Als de app is ingeschakeld, kunnen site-eigenaren de app ook afzonderlijk aan een site toevoegen. Als u niet wilt doorgaan met het toevoegen van de app aan nieuwe sites, kunt u dit stoppen door op Stoppen met toevoegen aan nieuwe sites te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/15-add-to-all-sites.png)

De functionaliteit die door de app wordt geboden, blijft beschikbaar op alle sites waaraan deze is toegevoegd, en site-eigenaren kunnen deze app nog steeds aan hun sites toevoegen.

### 4.2 **Toevoegen aan Teams:**

Dit schakelt het tabblad Teams voor de app in.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/16-add-to-teams.png)

Voordat de app aan Teams kan worden toegevoegd, moet deze eerst aan alle sites worden toegevoegd.

## 5. **Verder lezen**

Zie [hier](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application) voor informatie over hoe deze toepassing na de installatie werkt. Zie [hier](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq) voor meer informatie over hoe deze toepassing nuttig kan zijn.
