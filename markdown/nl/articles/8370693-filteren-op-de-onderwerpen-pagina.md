# Filteren op de onderwerppagina

Het filtermenu in een onderwerpenboard kan worden geopend door op de filterknop links van de zoekbalk in een [onderwerpenboard](https://support.catenda.com/en/articles/4670271-issues-page) te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/01-intro.png)

## 1. **Filters**

Klik op de filterknop linksboven om een paneel aan de linkerkant weer te geven. Wanneer een filter wordt toegepast, verandert de URL die zichtbaar is in de browser. In dit artikel worden filters als volgt weergegeven: _Filternaam in menu_ - `Filternaam in URL=Filteroptie in URL`

**Standaardfilter** Het standaardfilter is in eerste instantie niet zichtbaar in de URL. Wanneer de pagina voor de eerste keer wordt geopend, wordt het volgende filter toegepast. _Geen filter_ - `status-type=all`

### 1.1 **Het huidige filter opslaan en delen**

Ga naar de URL van een gefilterde pagina om die pagina met het toegepaste filter te laden. De toegepaste filters kunnen worden opgeslagen aan de bovenkant van het filtermenu. Klik [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) voor meer informatie over het opslaan en delen van filters

### 1.2 **Verberg lege filters**

Klik [hier](https://support.catenda.com/en/articles/8551755-saving-filters) voor meer informatie over het beperken van filterresultaten.

## 2. **Filteren in het filtermenu**

Hier zijn de volgende filters beschikbaar:

De verschillende filters in het filtermenu worden alleen weergegeven als er onderwerpen zijn waarvoor het gefilterde item is geconfigureerd.

### 2.1 **Mijn onderwerpen**

Toegewezen aan mij - `assigned-user=<User GUID>&assigned-team=<Team GUID>` _Toegewezen gebruiker_ - `assigned-user=<User GUID>` _Mijn teams_ - `assigned-team=<Team GUID>` _Aangevraagd door mij_ - `requester-user=<Your GUID>` Onderwerpen _die ik volg_ - `followed-by=me` _waarmee ik word vermeld_ - `mentioned=me`

> **Opmerking:** Als u een koppeling deelt met de filters "Onderwerp dat ik volg" of "waarmee ik word vermeld" actief, zal de gebruiker die de koppeling opent hun onderwerpenboard laten filteren op onderwerpen die zij volgen en onderwerpen waarin zij zijn vermeld, en niet op onderwerpen die u volgt en onderwerpen waarin u bent vermeld. Als u onderwerpen wilt delen waarin u bent vermeld, gebruikt u alstublieft [tekst zoeken](#h_7fc30a16f0)

_Gemaakt door mij_ - `created-by=<User GUID>`

### 2.2 **Status / Type**

_Alle openstaande statussen_ - `status-type=open` _Specifieke openstaande status_ - `status-type=<Status GUID>` _Alle gesloten statussen_ - `status-type=closed` _Specifieke gesloten status_ - `status-type=<Status GUID>` _Type_ - `type=<Type GUID>`

### 2.3 **Vervaldatum**

_Verlopen_ - `due=overdue` _Alles met een vervaldatum_ - `due=present` _Geen vervaldatum_ - `due=none`

### 2.4 **Bijgewerkt**

Met het datumfilter kunt u een timeframe selecteren voor wanneer de onderwerpen voor het laatst zijn bijgewerkt. _Bijgewerkt_ - `updated-from=<Epoch Unix Timestamp>&updated-to=<Epoch Unix Timestamp>` Lees [dit](https://support.catenda.com/en/articles/6511685-date-filter) artikel om te leren hoe u eenvoudig datums op de pagina kunt selecteren.

### 2.5 **Toegewezen aan / Aangevraagd door**

_Niet toegewezen aan iemand_ - `assigned=unassigned` _Geen team toegewezen_ - `assigned-team=unassigned` _Toegewezen aan team_ - `assigned-team=<Team GUID>` _Niet toegewezen aan gebruiker_ - `assigned-user=unassigned` _Toegewezen aan gebruiker_ - `assigned-user=<User GUID>` Toewijzingsoperator - `assigned-op=and` Standaard kunt u alleen zoeken naar de toegewezen gebruiker OF het toegewezen team. In Catenda Hub kunt u een ontvanger instellen als user@team Als u alle onderwerpen van dit type wilt vinden**,** filtert u op het team en de gebruiker, en voegt u &assigned-op=and toe aan het einde van de URL.

_Niet aangevraagd_ - `requester=unassigned` _Niet aangevraagd door team_ - `requester-team=unassigned` _Niet aangevraagd door gebruiker_ - `requester-user=unassigned` _Aangevraagd door gebruiker_ - `requester-user=<User GUID>`

### 2.6 **Gemaakt door**

_Gemaakt door gebruiker_ - `created-by=<User GUID>`

### 2.7 **Mijlpaal**

_Mijlpaal_ - `milestone=<Milestone GUID>`

### 2.8 **Eigen veld**

_Eigen veld heeft waarde_ - `custom-field-has-value-<Custom field GUID>=true` Met de optie "heeft waarde" in het filtermenu kunnen alle onderwerpen met een waarde die voor dat aangepaste veld is geconfigureerd, worden gefilterd. Aangepaste veldtypen die kunnen worden gefilterd op heeft waarde: Datum Decimaal Vervolgkeuzelijst Geheel getal Tekst

_Eigen veld specifieke waarde_ - `custom-field-item-<Custom field GUID>=<Value GUID>` Aangepaste veldtypen die kunnen worden gefilterd op specifieke waarde uit het filtermenu: Vervolgkeuzelijst

Sommige waarden in aangepaste velden waar waarden kunnen worden geconfigureerd, kunnen worden gefilterd. Filter op waarden door een zoekfrase in de zoek- of filterbalk in te voeren en het bijbehorende aangepaste veld te selecteren. Aangepaste veldtypen die kunnen worden gefilterd door in te typen in de zoek- of filterbalk: Decimaal Vervolgkeuzelijst Geheel getal Tekst

_Eigen veld heeft geen waarde_ - `custom-field-has-value-<Custom field GUID>=false` Filter op alle onderwerpen waarbij een aangepast veld geen waarde heeft. Aangepaste veldtypen die kunnen worden gefilterd op geen waarde: Datum Decimaal Vervolgkeuzelijst Geheel getal Tekst

> **Opmerking:** Aangepaste velden die als vereist zijn ingesteld, hebben altijd een waarde. U kunt daarom niet zoeken naar "heeft waarde" of "heeft geen waarde" kan daarom niet worden gezocht op een aangepast veld dat als vereist is ingesteld.

### 2.9 **Label**

_Label_ - `label=<Label GUID>` Labels in hun eigen labelgroep worden in een aparte lijst weergegeven.

### 2.10 **Koppelingen**

Gekoppeld - `associations=exists` Filter op onderwerpen die zijn gekoppeld aan modelobjecten in de 3D-viewer.

Niet gekoppeld - `associations=does-not-exist` Filter op onderwerpen die niet zijn gekoppeld aan modelobjecten in de 3D-viewer.

Gekoppeld aan geselecteerde objecten - `link=backlink` Als het 3D-paneel nog niet geopend is, wordt het geopend. Selecteer objecten uit een model in de 3D-viewer om op onderwerpen die zijn gekoppeld aan de geselecteerde objecten te filteren.

## 3. **Filteren in de zoek- of filterbalk**

Naast het filtermenu aan de linkerkant is er bepaalde functionaliteit die alleen beschikbaar is via de zoek- of filterbalk. Dit is wat de zoek- of filterbalk kan zijn wanneer deze is gemarkeerd:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/02-filtering-in-the-search-or-filter-bar.png)

Onder de zoek- of filterbalk wordt een menu met voorgestelde filters geopend. Het eerste filter in het filtermenu wordt voorgesteld na het markeren van het zoek- of filtermenu. Druk op Enter om dit filter toe te passen of gebruik de pijltoetsen om tussen de verschillende filters te navigeren.

### 3.1 **Opgeslagen filters**

Als u opgeslagen filters hebt in een onderwerpenboard, zullen deze de eerste beschikbare filter in het filtermenu zijn en zullen worden voorgesteld zodra de zoek- of filtervak is gemarkeerd:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/03-saved-filters.png)

Klik op het filter om het board te openen gefilterd op de opgeslagen set filters die een naam hebben gekregen. Klik [hier](https://support.catenda.com/en/articles/8551755-saving-filters) voor meer informatie over het opslaan van een set filters.

### 3.2 **Tekst zoeken**

_Tekst zoeken -_ `search=<Search phrase>` Na het invoeren van tekens in de zoek- of filterbalk, wordt het eerste voorgestelde filter gewijzigd in tekst zoeken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/04-text-search.png)

**Inhoud die kan worden gezocht** Onderwerptitel Onderwerpbeschrijving Onderwerpcommentaren

**Capitalisatie** De tekstzoekopdracht is niet gevoelig voor hoofd- of kleine letters.

**Tekenhoevelheden** Enkel teken Inhoud die het gezochte teken bevat, wordt gematcht tenzij het een unicode-letter is met een waarde van 58 of hoger aan het begin van de inhoud.

Twee tekens Inhoud die een enkel woord bevat, gescheiden door een scheidingsteken zoals een spatie, dat overeenkomt met de zoekfrase, wordt opgenomen in de resultaten.

Drie of meer tekens Inhoud die overeenkomt met de zoekfrase in enig deel van de inhoud wordt opgenomen in de resultaten.

**Witruimte** Witruimtetekens aan het begin van een zoekfrase worden verwijderd.

**Zoeken naar vermelde leden of teams** Onderwerpen waarbij een lid of team is vermeld in een opmerking of beschrijving, kunnen worden gevonden met behulp van tekst zoeken:

Naam lid of team Zoek op de naam van het lid of team om alle platte tekstvoorkomsten van die lid- of teamnaam te vinden.

Vermeld lid Zoek op het e-mailadres van een lid om alle platte tekstvoorkomsten van dat e-mailadres van het lid te vinden. Dit omvat waar zij zijn vermeld. Zoek op `#[<E-mailadres van lid>]` om alleen de voorkomsten te vinden waar dat lid wordt vermeld.

Vermeld team Vermelde teams kunnen worden gezocht door de GUID van dat team te doorzoeken. Als u de GUID van een team wilt vinden, gaat u naar de [inhoudspagina van dat team](https://support.catenda.com/en/articles/7891755-team-page) door op de naam ervan te klikken op het [tabblad Teams van de pagina Leden en teams](https://support.catenda.com/en/articles/4670291-members-and-teams-page). De URL moet er ongeveer zo uitzien: [https://hub.catenda.com/project/\<Project](https://hub.catenda.com/project/<Project) GUID>/members/\<Member GUIID>

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/05-text-search.png)

Zoek op de team-GUID om alle platte tekstvoorkomsten van die team-GUID te vinden. Dit omvat waar zij zijn vermeld. Zoek op `#[<team GUID>]` om alleen de voorkomsten te vinden waar dat team wordt vermeld.

### 3.3 **Aangepaste velden - Tekst**

Als een zoekfrase begint met een unicode-teken met een unicode-waarde van 58 of hoger, worden de volgende filters weergegeven onder aan de lijst met voorgestelde filters.

_Tekstaangepast veld -_ `custom-field-<Custom field GUID>=<Search phrase>` Als een aangepast tekstveld in het onderwerpenboard is ingeschakeld, kan de inhoud van aangepaste tekstvelden in alle onderwerpen in het board met dit filter worden gefilterd.

### 3.4 **Zoekfrase voor getallen**

Als een zoekfrase begint met een unicode-teken met een unicode-waarde tussen 33 en 57, verschijnen de volgende filters onder aan de lijst met voorgestelde filters.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/06-number-search-phrase.png)

Dit omvat de volgende tekens: `!`,`"`,`#`,`$`,`%`,`&`,`'`,`(`,`)`,`*`,`+`,`,`,`-`,`.`,`/`,`0`,`1`,`2`,`3`,`4`,`5`,`6`,`7`,`8`,`9`

_Onderwerp -_ `issues=<issue number>` Wanneer een zoekfrase met een getal begint, verschijnt het onderwerp nummerzoeken als een suggestie in de zoek- of filterbalk. Het voorgestelde filter kan er ongeveer als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/07-number-search-phrase.png)

Hoewel het mogelijk is een board op onderwerpnummers met meer dan alleen getallen te filteren, kunnen onderwerpen alleen met hun nummer met dit filter worden gevonden. Als meer dan alleen getallen worden opgegeven, verdwijnt het filter uit het menu, maar het board wordt nog steeds gefilterd op de ingevoerde frase.

Filteren op een of meer onderwerpen per nummer Het is alleen mogelijk om tegelijk van de zoek- of filterbalk op één onderwerp te zoeken. Als het onderwerp met het Catenda-onderwerpnummer 123 in het board bestaat, zal de url `&issues=123` bevatten wanneer het wordt gefilterd op onderwerpnummer 123. Het is mogelijk om meer onderwerpnummers in de url in te voeren, bijvoorbeeld: `&issues123,124,125` zou ertoe leiden dat alle drie onderwerpen worden weergegeven als ze in het board bestaan. Het filteren op meerdere onderwerpen op deze manier is alleen mogelijk door de URL te bewerken.

### 3.5 **Aangepaste velden - Getal**

_Aangepast geheel getal veld -_ `custom-field-<Custom field GUID>=<Search phrase>` Als een aangepast geheel getalveld in het onderwerpenboard is ingeschakeld, kan de inhoud van aangepaste geheel getalvelden in alle onderwerpen in het board met dit filter worden gefilterd.

_Aangepast decimaal veld -_ `custom-field-<Custom field GUID>=<Search phrase>` Als een aangepast decimaal veld in het onderwerpenboard is ingeschakeld, kan de inhoud van aangepaste decimale velden in alle onderwerpen in het board met dit filter worden gefilterd.

### 3.6 **Aangepaste velden - Vervolgkeuzelijst**

Als een zoekfrase overeenkomt met de naam van een waarde in een filter, wordt het filter dat het best overeenkomt, voorgesteld in het suggestievak.

_Vervolgkeuzelijst aangepast veld_ _-_ `custom-field-item-<Custom field GUID>=<Dropdown value GUID>` Als de zoekfrase overeenkomt met een waarde in een vervolgkeuzelijst aangepast veld met maximaal 10 waarden, wordt het voorgesteld om op die vervolgkeuzelijstwaarde te zoeken.
