# Filteren op de notificatiepagina

Zowel in uw [notificatie-instellingen](https://support.catenda.com/en/articles/8272435-notification-settings) als in uw [projectspecifieke notificatie-instellingen](https://support.catenda.com/en/articles/4670262-project-specific-notification-settings) kunt u configureren welke notificaties u wilt ontvangen.

In dit artikel wordt uitgelegd in welke situatie een notificatie wordt verzonden voor de verschillende instellingen. Nadat de notificatie is verzonden, kunt u deze terugvinden op de [accountnotificatiepagina](https://support.catenda.com/en/articles/7439223-account-notifications-page) en de [projectnotificatiepagina](https://support.catenda.com/en/articles/4670295-project-notifications-page) door de filterknoppen aan de linkerkant te openen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/810mbm4a/01-intro.png)

## 1. **Notificatiegeschiedenis**

Notificaties worden naar een lid verzonden zodra deze aan een project is deelgenomen. De geschiedenis van notificaties in een project gaat daarom terug tot het moment waarop het project werd bijgetreden. Leden die langer deel van het project zijn, kunnen mogelijk eerdere gebeurtenissen zien die nieuwere leden niet hebben.

## 2. **Filters**

Klik op de filterknop in de linkerbovenhoek om een paneel aan de linkerkant te openen. Wanneer een filter wordt toegepast, verandert de URL die in de browser zichtbaar is. In dit artikel worden filters als volgt weergegeven:

### 2.1 **_Filternaam in menu_ - `Filternaam in URL=Filteroptie in URL`**

**Standaardfilter** Het standaardfilter is in eerste instantie niet zichtbaar in de URL. Wanneer de pagina voor het eerst wordt geopend, wordt het volgende filter toegepast.

### 2.2 _Van een maand geleden_ - `dateFrom=last-month`

### 2.3 **Huidig filter opslaan en delen**

Ga naar de URL van een gefilterde pagina om die pagina met het toegepaste filter te laden. De toegepaste filters kunnen boven aan het filtermenu worden opgeslagen. Klik [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) voor meer informatie over het opslaan en delen van filters

### 2.4 **Lege filters verbergen**

Klik [hier](https://support.catenda.com/en/articles/8551755-saving-filters) voor meer informatie over het beperken van filterresultaten.

## 3. **Datumfilters**

Met het datumfilter kunt u een tijdsbestek selecteren voor wanneer notificaties zijn verzonden.

### 3.1 **Van een week geleden** - `dateFrom=last-week`

Notificaties van de afgelopen week.

### 3.2 **Van een maand geleden** - `dateFrom=last-month`

Als u naar de accountnotificatiepagina navigeert, wordt deze standaard gefilterd op notificaties van afgelopen maand.

### 3.3 **Van een jaar geleden** - `dateFrom=last-year`

Notificaties van het afgelopen jaar.

### 3.4 **Kies een datum** - `date-from=<Epoch Unix Timestamp>&date-to=<Epoch Unix Timestamp>`

Lees [dit](https://support.catenda.com/en/articles/6511685-date-filter) artikel om te leren hoe u eenvoudig datums op de pagina kunt selecteren.

### 3.5 **Alle notificaties**

Om alle notificaties die u ooit hebt ontvangen te zien, verwijdert u het dateFrom-filter uit de URL.

## 4. **Type**

Het typemenu bevat alle filterbare notificatietypes.

Notificaties zijn verdeeld in de volgende typen:

## 5. **Alles** - `type=all`

Alle notificaties worden standaard zowel in de browser als via e-mail verzonden. Als u naar een notificatiepagina gaat, wordt deze standaard gefilterd op notificaties van afgelopen maand. Als u het dateFrom-filter uit de URL verwijdert en het type=all-filter gebruikt, kunt u alle notificaties zien die u ooit hebt ontvangen.

## 6. **Modellen** - `type=models`

_Nieuw model -_ `type=new-model` De notificatie toont de naam van het gemaakte model.

**Notificatie-klik brengt u naar:** Modeloverzichtspagina van het project waarin het model is gemaakt.

**Notificatie-instelling:** Er is een nieuw model gemaakt

### 6.1 **Verzonden zelfs als alle selectievakjes in instellingen zijn uitgeschakeld**

_Check-in mislukt_ - `type=checkin-failed` Als de indeling van uw IFC-bestand niet door ons systeem wordt herkend

_Import mislukt_ - `type=import-failed` Kan gebeuren als uw verbinding tijdens het uploaden werd onderbroken.

_Import voltooid_ - `type=import-completed` Wanneer een model klaar is met verwerken

**Notificatie-instelling:** Een nieuwe revisie is geïmporteerd

_Export voltooid_ - `type=export-completed` Wanneer uw modelexport met succes is gecomprimeerd en klaar is voor downloaden.

**Notificatie-instelling:** Een nieuwe export is gemaakt

## 7. **Onderwerpen** - `type=issues`

### 7.1 **Nieuw topic** - `type=new-issue`

Dit is de enige notificatie die u over een topic ontvangt als u het topic niet [volgt](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e). Toegewezen personen, verzoeken en leden die in topics worden vermeld, volgen het topic automatisch en ontvangen de onderstaande notificaties.

**Notificatie-instelling:** Er is een nieuw topic gemaakt

### 7.2 **Nieuwe opmerking** - `type=new-comment`

Als u noch de toegewezen noch de verzoeker van het topic bent, maar het topic [volgt](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e), ontvangt u deze notificatie.

Dit kan gebeuren als u eerder [toegewezen](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9), [verzoeker](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [vermeld](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) of [handmatig gevolgd](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) bent. Als u geen toekomstige notificaties van dit topic wilt, kunt u het topic niet volgen in het [rechter informatievenster](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue). _Notificatie-instelling: aan mij toegewezen_ Een topic is aan u toegewezen

**Notificatie-instelling: door mij aangevraagd** Een topic is door u aangevraagd

**Notificatie-instelling: gevolgd door mij** Een topic is door u gevolgd

### 7.3 **Aan mij toegewezen** - `type=issue-assigned`

**Notificatie-instelling:** Een topic is aan mij toegewezen

### 7.4 **Team toegewezen** - `type=issue-team-assigned`

Wanneer een team aan een topic wordt toegewezen

**Notificatie-instelling:** Een topic is aan mij toegewezen

### 7.5 Vermelding van mij - `type=issue-mentioned`

**Notificatie-instellingen:** Een topic vermeldt mij of een van mijn teams

### 7.6 **Team vermeld** - `type=issue-team-mentioned `

**Notificatie-instellingen:** Een topic vermeldt mij of een van mijn teams

### 7.7 **Status bijgewerkt** - `type=status-updated`

Als u noch de toegewezen noch de verzoeker van het topic bent, maar het topic [volgt](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e), ontvangt u deze notificatie.

Dit kan gebeuren als u eerder [toegewezen](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9), [verzoeker](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [vermeld](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) of [handmatig gevolgd](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) bent. Als u geen toekomstige notificaties van dit topic wilt, kunt u het topic niet volgen in het [rechter informatievenster](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue). _Notificatie-instelling: aan mij toegewezen_ Een status is bijgewerkt in een topic dat aan u is toegewezen

**Notificatie-instelling: door mij aangevraagd** Een status is bijgewerkt in een topic dat door u is aangevraagd

**Notificatie-instelling: gevolgd door mij** Een status is bijgewerkt in een topic dat door u wordt gevolgd

### 7.8 **Type bijgewerkt** - `type=type-updated`

Als u noch de toegewezen noch de verzoeker van het topic bent, maar het topic [volgt](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e), ontvangt u deze notificatie.

Dit kan gebeuren als u eerder [toegewezen](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9), [verzoeker](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [vermeld](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) of [handmatig gevolgd](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) bent. Als u geen toekomstige notificaties van dit topic wilt, kunt u het topic niet volgen in het [rechter informatievenster](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue). _Notificatie-instellingen:_

Aan mij toegewezen - Een type is bijgewerkt in een topic dat aan u is toegewezen

Door mij aangevraagd - Een type is bijgewerkt in een topic dat door u is aangevraagd

Gevolgd door mij - Een type is bijgewerkt in een topic dat door u wordt gevolgd

### 7.9 **Verzonden zelfs als alle selectievakjes in instellingen zijn uitgeschakeld**

### 7.10 **Verplaatsing voltooid** - `type=issues-move-success`

Toont het aantal topics dat is verplaatst en naar welk topicbord ze zijn verplaatst.

### 7.11 **Verplaatsing mislukt** - `type=issues-move-failed`

Toont het aantal topics dat niet kon worden verplaatst en naar welk topicbord ze niet konden worden verplaatst.

### 7.12 **Import mislukt** - `type=issues-import-failed`

Toont wat voor soort topic-import niet kon worden geïmporteerd en naar welk topicbord het niet kon worden geïmporteerd. _Mogelijke topic-importtypes:_ BCF

### 7.13 **Import voltooid** - `type=issues-import-success`

Toont wat voor soort topic-import met succes is geïmporteerd en naar welk topicbord het is geïmporteerd. _Mogelijke topic-importtypes:_ BCF

### 7.14 **Export mislukt** - `type=issues-export-failed`

Toont wat voor soort topic-export is mislukt en van welk topicbord het niet kon worden geëxporteerd. _Mogelijke topic-exporttypes:_ BCF 2.0, BCF 2.1, BCF 2.0, PDF, Excel

### 7.15 **Export voltooid** - `type=issues-export-success`

Toont wat voor soort topic-export met succes is geïmporteerd en van welk topicbord het is geëxporteerd. _Mogelijke topic-exporttypes:_ BCF 2.0, BCF 2.1, BCF 2.0, PDF, Excel

## 8. **Documenten** - `type=documents`

### 8.1 **Document toegevoegd** - `type=document-created`

_Notificatie-instelling:_ Er is een document of map gemaakt

### 8.2 **Nieuwe documentrevisie** - `type=document-revision-uploaded`

_Notificatie-instelling:_ Een nieuwe documentrevisie is geüpload

### 8.3 **Virus gedetecteerd** - `type=document-file-infected`

Als een document wordt gedetecteerd als besmet met een virus, ontvangt u een notificatie ongeacht de instelling voor e-mailsamenvatting. Een notificatie wordt ook verzonden naar de beheerders in het project van het geïnfecteerde document. De notificatie geeft aan wie welk document waar heeft geüpload.

Als uw e-mailnotificaties volledig zijn uitgeschakeld, wordt deze notificatie niet als e-mailnotificatie verzonden. U ontvangt de notificatie nog steeds in Catenda Hub, zelfs als Catenda Hub-notificaties zijn uitgeschakeld.

> **Opmerking:** Deze notificatie wordt verzonden, zelfs als alle notificaties zijn uitgeschakeld

### 8.4 **Document verwijderd** - `type=document-deleted`

_Notificatie-instelling:_ Een document of map is verwijderd

### 8.5 **Documenten verwijderd** - `type=documents-deleted`

_Notificatie-instelling:_ Een document of map is verwijderd

### 8.6 **Documenten geüpload** - `type=documents-uploaded`

_Notificatie verzonden als:_ Een document is door een ander gebruiker geüpload

### 8.7 **Documentgoedkeuring**

**Notificatie-instellingen:** Ik ben ingesteld als uitgever in een goedkeuringsverzoek Een team waarvan ik lid ben, is ingesteld als uitgever in een goedkeuringsverzoek Ik ben ingesteld als revisor voor een goedkeuringsverzoek Nieuwe opmerking in goedkeuringsverzoek

### 8.8 **Zip-extractie voltooid**

_Notificatie verzonden als:_ Een zip-map is met succes geïmporteerd.

> **Opmerking:** Deze notificatie wordt verzonden, zelfs als alle notificaties zijn uitgeschakeld

### 8.9 **Uw zip-download is klaar**

Als u meerdere documenten tegelijk hebt gedownload, wordt een zip gemaakt. Deze zip kan op elk moment van de notificatie worden gedownload, zelfs als u de browser zou sluiten en opnieuw openen.

Klik op het gedeelte "_Klik hier om te downloaden (...MB)_" van de notificatie om het zip-bestand te downloaden.

Als u alleen op de notificatie klikt, vernieuwt de pagina alleen.

De naam van het gedownloade zip-bestand is _\<Download GUID>.zip_, in tegenstelling tot de naam van de zip die u automatisch krijgt als u wacht tot de zip klaar is met comprimeren na het klikken op downloaden, namelijk \<Projectname>-\<Documents>-\<Timestamp>.zip Notificatie verzonden naar: _De gebruiker die de documenten heeft gedownload._

> **Opmerking:** Deze notificatie wordt verzonden, zelfs als alle notificaties zijn uitgeschakeld

## 9. **Collecties** - `type=document-collections`

### 9.1 **Collectie voltooid** - `type=library-item-collection-finalized`

**Notificatie verzonden als** U of een team waarvan u deel uitmaakt, bent ingesteld als volger van een collectie en de collectie is voltooid.

**Notificatie-instelling** Collectie voltooid

### 9.2 **Een collectie gevolgd** - `type=library-item-collection-made-follower`

**Notificatie verzonden als** U of een team waarvan u deel uitmaakt, bent als volger aan een collectie toegevoegd.

**Notificatie-instelling** Een collectie gevolgd

### 9.3 **Een collectie niet meer gevolgd** - `type=library-item-collection-removed-follower`

**Notificatie verzonden als** U of een team waarvan u deel uitmaakt, bent uit een collectie verwijderd.

**Notificatie-instelling** Een collectie niet meer gevolgd

### 9.4 **Collectie bijgewerkt** - `type=library-item-collection-updated`

**Notificatie verzonden als** Een collectie is met het project gedeeld en u of een team waarvan u deel uitmaakt, bent als volger ingesteld.

**Notificatie-instelling** Collectie bijgewerkt

### 9.5 **Collectie privé gemaakt** - `type=library-item-collection-made-private`

**Notificatie verzonden als** U of een team waarvan u deel uitmaakt, bent ingesteld als volger van een collectie die met het project is gedeeld en de collectie is privé gemaakt.

**Notificatie-instelling** Collectie privé gemaakt

### 9.6 **Collectie verwijderd** - `type=library-item-collection-deleted`

**Notificatie verzonden als** U bent een beheerder en een andere beheerder verwijdert een collectie in het project.

**Notificatie-instelling** Collectie verwijderd

### 9.7 **Collectie extern gedeeld** - `type=library-item-collection-shared-externally`

**Notificatie verzonden als** U bent een beheerder en een andere beheerder deelt een collectie in het project extern.

**Notificatie-instelling** Collectie extern gedeeld

## 10. **Leden** - `type=members`

### 10.1 **Nieuwe uitnodiging** - `type=invite`

**Notificatie verzonden als:** Een ander gebruiker stuurt u een uitnodiging voor een project. De notificatie beschrijft wie u heeft uitgenodigd en voor welk project u bent uitgenodigd. Als u deze notificatie hebt ontvangen, zou u ook een e-mail met een uitnodigingslink moeten hebben ontvangen waarop u kunt klikken om de uitnodiging te accepteren. Controleer [hier](https://support.catenda.com/en/articles/8417802-why-am-i-not-receiving-emails) voor e-mailprobleemoplossing.

> **Opmerking:** De notificatie in Catenda Hub bevat ook de uitnodigingslink, dus u kunt ook op de notificatie klikken om de uitnodiging te accepteren. Als u nog geen account hebt, moet u er mogelijk een maken en opnieuw worden uitgenodigd om op de notificatie te klikken.

**Notificatie-instelling** Een persoon wordt uitgenodigd voor het project.

### 10.2 **Nieuw lid** - `type=member-accept-invitation`

**Notificatie verzonden als** Als een gebruiker een uitnodiging aanvaardt die door een ander lid is verzonden, wordt een notificatie verzonden dat een nieuw lid aan het project is deelgenomen.

**Notificatie-instelling** Een nieuwe gebruiker heeft aan het project deelgenomen

### 10.3 **Toegevoegd aan team** - `type=member-added-to-team`

**Notificatie verzonden als** U bent aan een team toegevoegd.

### 10.4 **Nieuw teamlid** - `type=project-member-added-to-team`

**Notificatie-instelling** Een lid is aan een team toegevoegd

## 11. **Project**

### 11.1 **Projectnaam** - `projects=<Project GUID>`

## 12. **Limiet**

### 12.1 **Aantal notificaties per pagina** - `limit=<Notification amount>`

_Opmerking:_ Het kan langer duren voordat de pagina met meer notificaties is geladen.

## 13. **Pagina**

### 13.1 **Huidige pagina van notificaties** - `page=<Page number>`

## 14. **Verplichte notificaties**

Er zijn enkele notificaties die worden verzonden, zelfs als u alle selectievakjes in notificatie-instellingen hebt uitgeschakeld.

### 14.1 **Verzonden zelfs als alle selectievakjes zijn uitgeschakeld**

Elk type import of export dat op de achtergrond wordt verwerkt, produceert een notificatie over het resultaat van de import, ongeacht of deze is geïmporteerd of mislukt. Als u notificaties volledig uitschakelt met de aan-/uitknop rechtsboven, worden deze notificaties ook niet verzonden.

### 14.2 **Verzonden zelfs als alle notificaties zijn uitgeschakeld**

Notificaties over koppelingen die via de [sharelink](https://support.catenda.com/en/articles/4728886-sharelink-notify-people-about-catenda-hub-content)-functie met gebruikers zijn gedeeld, maken altijd een notificatie voor de gebruiker, zelfs als de gebruiker notificaties volledig heeft uitgeschakeld met de aan-/uitknop in de rechterbovenhoek van de pagina met notificatie-instellingen.
