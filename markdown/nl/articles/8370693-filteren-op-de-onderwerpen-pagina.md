# Filteren op de onderwerpen pagina

Het filtermenu in een onderwerp bord kan worden geopend door op de filterknop links van de zoekbalk in een [onderwerp bord](https://support.catenda.com/en/articles/4670271-issues-page) te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/01-intro.png)

## 1. **Filters**

Klik op de filterknop linksboven om een paneel aan de linkerkant te laten verschijnen. Wanneer een filter wordt toegepast, verandert de URL die in de browser zichtbaar is. In dit artikel worden filters als volgt weergegeven: _Filternaam in menu_ - `Filternaam in URL=Filteroptie in URL`

**Standaardfilter** Het standaardfilter is aanvankelijk niet zichtbaar in de URL. Wanneer de pagina voor de eerste keer wordt geopend, wordt het volgende filter toegepast. _Geen filter_ - `status-type=all`

### 1.1 **Huidige filter opslaan en delen**

Ga naar de URL van een gefilterde pagina om die pagina met het toegepaste filter te laden. De toegepaste filters kunnen naar de bovenkant van het filtermenu worden opgeslagen. Klik [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) voor meer informatie over het opslaan en delen van filters

### 1.2 **Lege filters verbergen**

Klik [hier](https://support.catenda.com/en/articles/8551755-saving-filters) voor meer informatie over het beperken van filterresultaten.

## 2. **Filteren in het filtermenu**

Hier vindt u de volgende filters:

De verschillende filters in het filtermenu worden alleen weergegeven als er onderwerpen zijn waarbij het gefilterde item is geconfigureerd.

### 2.1 **Mijn onderwerpen**

Toegewezen aan mij - `assigned-user=<User GUID>&assigned-team=<Team GUID>` _Toegewezen gebruiker_ - `assigned-user=<User GUID>` _Mijn teams_ - `assigned-team=<Team GUID>` _Aangevraagd door mij_ - `requester-user=<Your GUID>` Onderwerpen _die ik volg_ - `followed-by=me` _die mij noemen_ - `mentioned=me`

> **Opmerking:** Als u een koppeling deelt met de filters "Onderwerp dat ik volg" of "Die mij noemen" actief, zal de gebruiker die de koppeling opent het onderwerpenbord gefilterd hebben voor onderwerpen die hij volgt en onderwerpen waarin hij is genoemd, en niet voor onderwerpen die u volgt en onderwerpen waarin u bent genoemd. Gebruik [tekstzoeken](#text-search) om onderwerpen te delen waarin u bent genoemd

_Gemaakt door mij_ - `created-by=<User GUID>`

### 2.2 **Status / Type**

_Alle open status_ - `status-type=open` _Specifieke open status_ - `status-type=<Status GUID>` _Alle gesloten status_ - `status-type=closed` _Specifieke gesloten status_ - `status-type=<Status GUID>` _Type_ - `type=<Type GUID>`

### 2.3 **Einddatum**

_Verlopen_ - `due=overdue` _Alles met een einddatum_ - `due=present` _Geen einddatum_ - `due=none`

### 2.4 **Bijgewerkt**

Met het datumfilter kunt u een tijdspanne selecteren voor wanneer de onderwerpen voor het laatst zijn bijgewerkt. _Bijgewerkt_ - `updated-from=<Epoch Unix Timestamp>&updated-to=<Epoch Unix Timestamp>` Lees [dit](https://support.catenda.com/en/articles/6511685-date-filter) artikel om te leren hoe u eenvoudig datums op de pagina kunt selecteren.

### 2.5 **Toegewezen aan / Aangevraagd door**

_Niet toegewezen_ - `assigned=unassigned` _Geen team toegewezen_ - `assigned-team=unassigned` _Toegewezen aan team_ - `assigned-team=<Team GUID>` _Niet toegewezen aan gebruiker_ - `assigned-user=unassigned` _Toegewezen aan gebruiker_ - `assigned-user=<User GUID>` Operator toewijzen - `assigned-op=and` Standaard kunt u alleen zoeken naar de toegewezen gebruiker OF het toegewezen team. In Catenda Hub kunt u een toewijzing instellen als gebruiker@team Om alle onderwerpen van dit type te zoeken**,** filtert u op het team en de gebruiker, en voegt u &assigned-op=and toe aan het einde van de URL.

_Niet aangevraagd_ - `requester=unassigned` _Niet aangevraagd door team_ - `requester-team=unassigned` _Niet aangevraagd door gebruiker_ - `requester-user=unassigned` _Aangevraagd door gebruiker_ - `requester-user=<User GUID>`

### 2.6 **Gemaakt door**

_Gemaakt door gebruiker_ - `created-by=<User GUID>`

### 2.7 **Milestone**

_Milestone_ - `milestone=<Milestone GUID>`

### 2.8 **Aangepast veld**

_Aangepast veld heeft waarde_ - `custom-field-has-value-<Custom field GUID>=true` Met de optie "heeft waarde" in het filtermenu kunnen alle onderwerpen met een voor dat aangepaste veld geconfigureerde waarde worden gefilterd. Aangepaste veldtypen die kunnen worden gefilterd op heeft waarde: Datum Decimaal Vervolgkeuzelijst Geheel getal Tekst

_Aangepast veld specifieke waarde_ - `custom-field-item-<Custom field GUID>=<Value GUID>` Aangepaste veldtypen die kunnen worden gefilterd op specifieke waarde uit het filtermenu: Vervolgkeuzelijst

Sommige waarden in aangepaste velden waarvan waarden kunnen worden geconfigureerd, kunnen worden gefilterd. Filter op waarden door een zoekfrase in de zoek- of filterbalk in te voeren en het bijbehorende aangepaste veld te selecteren. Aangepaste veldtypen die kunnen worden gefilterd door in te voeren in de zoek- of filterbalk: Decimaal Vervolgkeuzelijst Geheel getal Tekst

_Aangepast veld heeft geen waarde_ - `custom-field-has-value-<Custom field GUID>=false` Filter op alle onderwerpen waarbij een aangepast veld geen waarde heeft. Aangepaste veldtypen die kunnen worden gefilterd op geen waarde: Datum Decimaal Vervolgkeuzelijst Geheel getal Tekst

> **Opmerking:** Aangepaste velden die als verplicht zijn ingesteld, hebben altijd een waarde. U kunt daarom niet zoeken naar "heeft waarde" of "heeft geen waarde" voor een aangepast veld dat als verplicht is ingesteld.

### 2.9 **Label**

_Label_ - `label=<Label GUID>` Labels in hun eigen labelgroep worden in een aparte lijst weergegeven.

### 2.10 **Koppelingen**

Gekoppeld - `associations=exists` Filter op onderwerpen gekoppeld aan modelobjecten in de 3D-viewer.

Niet gekoppeld - `associations=does-not-exist` Filter op onderwerpen die niet gekoppeld zijn aan modelobjecten in de 3D-viewer.

Gekoppeld aan geselecteerde objecten - `link=backlink` Als het niet al geopend is, wordt het 3D-paneel geopend. Selecteer objecten uit een model in de 3D-viewer om onderwerpen gekoppeld aan de geselecteerde objecten te filteren.

## 3. **Filteren in de zoek- of filterbalk**

Naast het filtermenu aan de linkerkant is er enige functionaliteit die alleen beschikbaar is via de zoek- of filterbalk. Dit is hoe de zoek- of filterbalk eruit ziet wanneer deze is gemarkeerd:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/02-filtering-in-the-search-or-filter-bar.png)

Onder de zoek- of filterbalk wordt een menu met voorgestelde filters geopend. Het eerste filter in het filtermenu wordt voorgesteld na het markeren van de zoek- of filtermenu. Druk op Enter om dit filter toe te passen of gebruik de pijltoetsen om tussen de verschillende filters te navigeren.

### 3.1 **Opgeslagen filters**

Als u opgeslagen filters in een onderwerpenbord hebt, zijn dit de eerste beschikbare filters in het filtermenu en worden deze voorgesteld zodra de zoek- of filtervak wordt gemarkeerd:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/03-saved-filters.png)

Klik op het filter om het bord op de opgeslagen set filters die een naam hebben gekregen te filteren. Klik [hier](https://support.catenda.com/en/articles/8551755-saving-filters) voor meer informatie over het opslaan van een set filters.

### 3.2 **Tekstzoeken**

_Tekstzoeken -_ `search=<Search phrase>` Na het invoeren van tekens in de zoek- of filterbalk verandert het eerste voorgestelde filter in tekstzoeken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/04-text-search.png)

**Inhoud die kan worden doorzocht** Onderwerpstitel Onderwerpsbeschrijving Onderwerpsopmerkingen

**Kapitalisatie** Tekstzoeken is niet gevoelig voor hoofd- of kleine letters.

**Aantal tekens** Enkel teken Inhoud die het gezochte teken bevat, wordt overeenkomst genoemd, tenzij het een unicode-letter met een waarde van 58 of hoger aan het begin van de inhoud is.

Twee tekens Inhoud met een enkel woord, gescheiden door een scheidingsteken zoals een spatie, dat overeenkomt met de zoekfrase, wordt in de resultaten opgenomen.

Drie of meer tekens Inhoud die overeenkomt met de zoekfrase in elk deel van de inhoud wordt in de resultaten opgenomen.

**Witruimte** Witruimtetekens aan het begin van een zoekfrase worden verwijderd.

**Zoeken naar vermelde leden of teams** Onderwerpen waarin een lid of team in een opmerking of beschrijving is genoemd, kunnen worden gevonden met behulp van tekstzoeken:

Lidnaam of teamnaam Zoek op de naam van het lid of team om alle normale tekstvoorvallen van die lidnaam of teamnaam te vinden.

Vermeld lid Zoek op het e-mailadres van een lid om alle normale tekstvoorvallen van dat e-mailadres te vinden. Dit omvat waar zij zijn genoemd. Zoek op `#[<E-mailadres van lid>]` om alleen de plaatsen te vinden waar dat lid wordt genoemd.

Vermeld team Vermelde teams kunnen worden doorzocht door de GUID van dat team te zoeken. Ga naar [de inhoudspagina van dat team](https://support.catenda.com/en/articles/7891755-team-page) door op de naam ervan op het [tabblad Teams van de pagina Leden en teams](https://support.catenda.com/en/articles/4670291-members-and-teams-page) te klikken om de GUID van een team te vinden. De URL ziet er ongeveer als volgt uit: [https://hub.catenda.com/project/\<Project](https://hub.catenda.com/project/<Project) GUID>/members/\<Member GUIID>

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/05-text-search.png)

Zoek op de team GUID om alle normale tekstvoorvallen van die team GUID te vinden. Dit omvat waar zij zijn genoemd. Zoek op `#[<team GUID>]` om alleen de plaatsen te vinden waar dat team wordt genoemd.

### 3.3 **Aangepaste velden - Tekst**

Als een zoekfrase begint met een unicode-teken met een unicode-waarde van 58 of hoger, worden de volgende filters naar de onderkant van de lijst met voorgestelde filters weergegeven.

_Aangepast tekstveld -_ `custom-field-<Custom field GUID>=<Search phrase>` Als een aangepast tekstveld is ingeschakeld in het onderwerpenbord, kan de inhoud van aangepaste tekstvelden in alle onderwerpen in het bord met dit filter worden gefilterd.

### 3.4 **Zoeken op getal**

Als een zoekfrase begint met een unicode-teken met een unicode-waarde tussen 33 en 57, worden de volgende filters naar de onderkant van de lijst met voorgestelde filters weergegeven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/06-number-search-phrase.png)

Dit omvat de volgende tekens: `!`,`"`,`#`,`$`,`%`,`&`,`'`,`(`,`)`,`*`,`+`,`,`,`-`,`.`,`/`,`0`,`1`,`2`,`3`,`4`,`5`,`6`,`7`,`8`,`9`

_Onderwerp -_ `issues=<issue number>` Wanneer een zoekfrase met een getal begint, wordt het onderwerpcijferzoeken weergegeven als een suggestie in de zoek- of filterbalk. Het voorgestelde filter kan er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/07-number-search-phrase.png)

Hoewel het mogelijk is om een bord op onderwerpnummers te filteren met meer dan alleen nummers, kunnen onderwerpen alleen met hun nummer met dit filter worden gevonden. Als meer dan alleen nummers worden verstrekt, verdwijnt het filter uit het menu, maar het bord wordt nog steeds gefilterd op de ingevoerde frase.

Filteren op één of meer onderwerpen op nummer Het is slechts mogelijk om tegelijk op één onderwerp vanuit de zoek- of filterbalk te zoeken. Als het onderwerp met het Catenda-onderwerpnummer 123 in het bord bestaat, bevat de URL `&issues=123` erin wanneer deze op onderwerpnummer 123 wordt gefilterd. Het is mogelijk om meer onderwerpnummers in de URL in te voeren, bijvoorbeeld: `&issues123,124,125` resulteert in alle drie onderwerpen die worden weergegeven als zij in het bord bestaan. Filteren op meerdere onderwerpen op deze manier is alleen mogelijk door de URL te bewerken.

### 3.5 **Aangepaste velden - Getal**

_Aangepast gehele getal veld -_ `custom-field-<Custom field GUID>=<Search phrase>` Als een aangepast gehele getal veld is ingeschakeld in het onderwerpenbord, kan de inhoud van aangepaste gehele getal velden in alle onderwerpen in het bord met dit filter worden gefilterd.

_Aangepast decimaal veld -_ `custom-field-<Custom field GUID>=<Search phrase>` Als een aangepast decimaal veld is ingeschakeld in het onderwerpenbord, kan de inhoud van aangepaste decimale velden in alle onderwerpen in het bord met dit filter worden gefilterd.

### 3.6 **Aangepaste velden - Vervolgkeuzelijst**

Als een zoekfrase overeenkomt met de naam van een waarde in een filter, wordt het best overeenkomende filter in het suggestiebox voorgesteld.

_Aangepast vervolgkeuzelijstveld_ _-_ `custom-field-item-<Custom field GUID>=<Dropdown value GUID>` Als de zoekfrase overeenkomt met een waarde in een aangepast vervolgkeuzelijstveld met maximaal 10 waarden, wordt voorgesteld om op die vervolgkeuzelijstwaarde te zoeken.
