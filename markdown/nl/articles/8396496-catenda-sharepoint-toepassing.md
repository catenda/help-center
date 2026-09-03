# Catenda SharePoint-toepassing

> **Opmerking:** Het installatiebestand voor de plugin is te vinden in [dit artikel](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Als de Catenda SharePoint-toepassing aan een SharePoint-site is toegevoegd, kunnen bestanden van SharePoint naar Catenda worden gepubliceerd en kan de Catenda-documentstructuur in SharePoint worden weergegeven. Wanneer geconfigureerd, kan de toepassing er als volgt uitzien: <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/inline-628ad1424b68.png" width="300"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/inline-910393724d2c.png" width="300"/> Dit artikel bevat informatie over hoe deze toepassing werkt Zie [hier](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq) voor meer informatie over hoe deze toepassing nuttig kan zijn. Zie [hier](https://support.catenda.com/en/articles/9453368-adding-and-removing-the-catendasp-app) voor het toevoegen van de SharePoint-toepassing aan een site.

De volgende topics zijn beschreven in dit artikel:

## 1. **Publiceren naar Catenda met het lijstcommando**

Met het lijstcommando is het mogelijk om een of meer bestanden naar Catenda te publiceren.

> **Opmerking:** Het is alleen mogelijk om bestanden te publiceren. Mapstructuren kunnen worden gedownload van SharePoint en naar Catenda worden geüpload via [zip-upload](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) of [Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector).

De volgende topics zijn beschreven in deze sectie:

### 1.1 **Het lijstcommando zoeken**

**Eén bestand** Als u een enkel bestand naar Catenda wilt publiceren, kunt u dit het gemakkelijkst doen door op Publiceren naar Catenda in het hamburgermenu van het bestand te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/01-finding-the-list-command.png)

**Meerdere bestanden** Als u meerdere bestanden naar Catenda wilt publiceren, moet u de bestanden selecteren die u wilt publiceren. Nadat u uw bestanden in SharePoint hebt geplaatst, kunnen gebruikers het lijstcommando Publiceren naar Catenda zien.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/02-finding-the-list-command.png)

Als er niet genoeg ruimte is in de opdrachtbalk, ziet u de opdracht mogelijk in het hamburgermenu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/03-finding-the-list-command.png)

> **Opmerking:** Bestanden kunnen alleen uit de lijstweergave worden gepubliceerd, omdat het lijstcommando niet beschikbaar is in de rasterweergave.

### 1.2 **Het bestand publiceren**

Na het klikken op Publiceren naar Catenda wordt het volgende menu geopend dat er ongeveer als volgt uit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/04-publishing-the-file.png)

Als u SharePoint nog geen toegang tot uw Catenda-account hebt gegeven, wordt u gevraagd dit te autoriseren. [Zie hieronder](#h_788fe15988) voor hoe u uw account kunt autoriseren.

**Een map selecteren** Als u toegang tot uw Catenda-account hebt verleend, kunt u het project, de bibliotheek en de doelmap op Catenda selecteren en publiceren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/05-publishing-the-file.png)

De weergave van de mapstructuur in SharePoint is consistent met de weergave in Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/06-publishing-the-file.png)

Als een document met dezelfde naam als uw bestand nog niet in de map bestaat waarnaar u publiceert, verschijnt dit als een nieuw document in Catenda. Als het bestand dat u publiceert dezelfde naam heeft als een document in de map waarnaar u het publiceert, is het bestand een nieuwe versie van dat document.

> **Opmerking:** Het is alleen mogelijk om documenten te publiceren en geen concepten te uploaden

Nadat een bestand is gepubliceerd, kunnen gebruikers het bestand verplaatsen, hernoemen en verwijderen. _Catenda-toegang vereist:_ Volledige toegang, meestal gegeven aan gebruikers zoals de uitgever of een beheerder. Het wijzigen van het bestand op Catenda verandert niets op SharePoint. Evenzo, als het bestand op SharePoint verandert, verandert er niets op Catenda.

## 2. **Catenda Webpart**

Met deze toepassing voegt u [de Catenda-webpart](https://support.catenda.com/en/articles/10538168-catenda-sharepoint-application-webpart) toe aan een pagina op uw site. U kunt gebruikers de gebieden laten bladeren waartoe zij leestoegang hebben in de documentsectie van een Catenda-project. Als zij schrijftoegang hebben tot enig deel van de documentstructuur, kunnen zij daar ook bestanden uploaden.

Dit is hoe een geconfigureerde webpart eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/07-catenda-webpart.png)

## 3. **Uw Catenda-account autoriseren**

Als u naar een SharePoint-pagina navigeert waar de Catenda Webpart is geactiveerd of u probeert de publiceeractie te gebruiken en u hebt uw account nog niet gevalideerd, krijgt u het volgende pop-upvenster:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/08-authorizing-your-catenda-account.png)

_Vereiste toegang:_ API-toegang bij het installeren van de toepassing. Als er niet automatisch een nieuw browsertabblad wordt geopend, kopieert u de link van het geopende tabblad voor accountvalidatie en navigeert u daar zelf heen. Als u nog niet bent aangemeld, wordt u gevraagd om u in dit venster aan te melden bij Catenda. Als u er nog geen hebt, kunt u [hier](https://hub.catenda.com/signup) een Catenda-account maken.

> **Opmerking:** Het e-mailadres dat is gekoppeld aan het Catenda-account waarmee u zich aanmeldt, moet hetzelfde zijn als het adres dat is gekoppeld aan het SharePoint-account waarmee u bent aangemeld.

Het verificatievenster kan er ongeveer als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/09-authorizing-your-catenda-account.png)

Door de app toegang tot uw account te geven, kunt u documenten van SharePoint naar elk deel van uw Catenda-project(en) publiceren waartoe u schrijftoegang hebt in de [documentsectie](https://support.catenda.com/en/articles/8204673-documents-page). Als een webpart aan een pagina op uw site is toegevoegd, kunt u ook alle documenten zien waartoe u leestoegang hebt in het Catenda-project dat is geconfigureerd door de persoon die de webpart heeft toegevoegd. Met de webpart kunt u ook documenten van uw systeem naar elk deel van het geconfigureerde Catenda-project publiceren waartoe u schrijftoegang hebt in de [documentsectie](https://support.catenda.com/en/articles/8204673-documents-page).

> **Opmerking:** Catenda heeft geen toegang tot uw SharePoint-documenten. Als u een document naar Catenda publiceert, ontvangt Catenda het in een eenrichtingstransactie.

Als u de app niet langer toegang tot uw Catenda-account wilt geven, kunt u de toegang altijd intrekken op de [toepassingenpagina](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) van uw Catenda-account.
