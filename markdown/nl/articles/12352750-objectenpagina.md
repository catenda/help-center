# Objectenpagina

De objectenpagina is te vinden als een subpagina van de modellenpagina. Een tabel met informatie over de projectmodellen wordt weergegeven. Vergelijkingsfilters kunnen worden gecombineerd om alleen de gevraagde informatie te extraheren. Deze pagina combineert elementen van het QTO-menu in het informatiepaneel en Bibliotheek met eigenschapwaarden op de bibliotheken-pagina en zal uiteindelijk beide vervangen.

![Dashboard Modellen Opgeslagen views Objecten Verdieping Configurator](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/01-intro.png)

## 1. **Zoeken of filteren**

Dit is wat het zoeken of filtermenu op de objectenpagina kan lijken

![Zoeken of filteren Selecteren Plus Modellen Geselecteerd Tekstzoeken](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/02-search-or-filter.png)

Klik [hier](https://support.catenda.com/en/articles/12353642-filtering-on-the-objects-page) voor meer informatie over filteren op de objectenpagina.

## 2. **Productentabel**

De productentabel kan er ongeveer zo uitzien:

![Geselecteerd 3D actiemenu downloaden instellingen entiteit kolom GlobalId kolom LongName kolom IfcProject IfcBuildingelementProxy één rij is geselecteerd in tabel](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/03-products-table.png)

Klik [hier](https://support.catenda.com/en/articles/11748020-tables-on-catenda) voor meer informatie over hoe u met tabellen in Catenda werkt.

### 2.1 **Wat is een product?**

De naam producten komt voort uit het feit dat elke rij een product is van het proces dat plaatsvindt wanneer een IFC wordt geïmporteerd.

### 2.2 **Weergegeven informatie**

Zodra de nieuwste revisie van een model is verwerkt, kan een rij voor elk product dat in het IFC-bestand is herkend, in de productentabel worden weergegeven. Alleen informatie van de nieuwste revisies van de modellen in een project wordt weergegeven.

### 2.3 **Geselecteerde item-acties**

Na het selecteren van een elementrij worden geselecteerde item-acties boven aan de productentabel weergegeven. Dit is wat het menu met geselecteerde item-acties kan lijken:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/04-selected-item-actions.png)

**Viewer** Klik op het 3D-pictogram of gebruik de viewer-actie om de geselecteerde elementen in de objectentabel in de 3D-viewer te selecteren.

**Isoleren** Gebruik de isoleeractie om de geselecteerde elementen in de objectentabel in de 3D-viewer te isoleren.

**Anderen verbergen** Gebruik de actie anderen verbergen om alle objecten in de 3D-viewer te verbergen, behalve de geselecteerde objecten.

### 2.4 **Rijinhoud**

**Toegang** Alleen productrijen voor de nieuwste versies van modellen waartoe leden toegang hebben, worden weergegeven. _Toegang vereist -_ Lezen

**Productrij** Productrijen kunnen niet worden geopend zoals in andere tabellen. Productrijen kunnen alleen in de 3D-viewer worden weergegeven via het actiemenu.

**Selectie** Rijselectie werkt iets anders dan in andere tabellen rond Catenda. In tegenstelling tot andere tabellen rond Catenda wordt de selectie niet opnieuw ingesteld wanneer u naar een andere pagina gaat en terugkomt of een filter wijzigt. In de productentabel wordt de selectie alleen opnieuw ingesteld wanneer u de pagina vernieuwt. Omdat er vaak duizenden objecten zijn geselecteerd, is het vaker het geval dat geselecteerde rijen niet zichtbaar zijn. Er kan een ander filter worden toegepast, waardoor de geselecteerde rijen niet meer in de tabel worden weergegeven, maar ze blijven geselecteerd.

### 2.5 **Exporteren**

Klik op de downloadknop bovenaan de productentabel om deze te exporteren.

![Downloadknop](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/05-export.png)

Rijen Het is alleen mogelijk om alle rijen van de ingeschakelde modellen op te halen. Het selecteren van rijen beperkt de rijen in de geëxporteerde bestanden niet. Het enige filter dat het aantal rijen kan beperken, is het modellen-filter. Hoewel rijen in de tabel beperkt kunnen lijken, zal het geëxporteerde bestand alle rijen voor de beschikbare modellen bevatten.

Kolommen Één kolom voor elke kolom die in de productentabel is ingeschakeld, wordt naar het bestand geëxporteerd. Klik [hier](https://support.catenda.com/en/articles/11748020-tables-on-catenda) voor meer informatie over het beheren van tabelkolommen.

**Export-objecten** Kies in het menu Export-objecten of u naar Excel of CSV wilt exporteren:

![Objecten exporteren Excel CSV](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/06-export.png)

**Export voorbereiden** Na het klikken op export kan een menu worden weergegeven met de mededeling dat de spreadsheet wordt voorbereid in de rechterbenedenhoek.

![Export voorbereiden Spreadsheet voorbereiden](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/07-export.png)

Tijdens deze tijd kunt u veilig rond navigeren in Catenda zolang de pagina niet wordt vernieuwd. Wanneer de spreadsheet beschikbaar is, ziet deze er als volgt uit en begint het bestand in de browser te downloaden:

![Export gereed Spreadsheet beschikbaar](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/08-export.png)

### 2.6 **Kolommen**

Sommige kolommen in de productentabel zijn standaard ingeschakeld, terwijl andere kunnen worden verborgen en moeten worden ingeschakeld. Dit is wat het kolommenvervolgkeuzemenu in de productentabel kan lijken:

![Attributen Type GlobalId Naam Tag Project Locatie Gebouw Vernieuwen](https://raw.githubusercontent.com/catenda/help-center/main/images/ahnhn26k/09-columns.png)

**Schakelaar** Schakel alle kolommen met deze schakelaar in of uit

**Filter** Typ de naam van een kolom of kolom categorie om het kolommen vervolgkeuzemenu voor die kolom te filteren. Het kan zijn dat de kolom waarnaar u zoekt zich in een ingestelde kolom categorie bevindt. Zorg er daarom voor dat u elke categorie uitvouwt om te zien of het resultaat in die categorie kan voorkomen.

**Reset** Klik op de reset knop om de kolommen terug te zetten naar de standaard kolommen

Op basis van de geconfigureerde kolom volgorde worden de eerste kolommen weergegeven, terwijl de tabel mogelijk zijwaarts moet worden verschoven om andere ingeschakelde kolommen weer te geven. De standaard volgorde en zichtbaarheidsinstelling van de kolommen op de documentenpagina is als volgt:

- Attributen
  - Entiteit
  - GlobalId
  - LongName
  - Naam
  - ObjectType

Bovendien kan de productentabel elk aantal kolommen hebben, afhankelijk van het aantal eigenschappen en eigenschappensets in elk van de modellen. Elke reeks kolommen heeft een hoofdcategorie met subcategorieën. De schakelknop kan worden gebruikt om de hele categorie in of uit te schakelen. Categorieën kunnen worden uitgevouwen en elke kolom in de categorie kan afzonderlijk worden in- of uitgeschakeld.

**Kolom voorkeuren** In tegenstelling tot andere tabelconfiguraties zijn sommige typische voorkeuren die kunnen worden geconfigureerd, vergrendeld in de productentabel.

Kolom voorkeuren worden niet tussen sessies opgeslagen. Kolommen kunnen niet opnieuw worden geordend, alleen in- of uitgeschakeld. Het is niet mogelijk om de tabel op een ander kolom te sorteren door op de cel in de koppeprij van de kolom te klikken. Het is niet mogelijk om de sorteerrichting van de kolom waarnaar de tabel is gesorteerd, te wijzigen. Het is niet mogelijk om de cel in de koppeprij uit de tabel te verslepen om de rij uit te schakelen. Rijen moeten via het kolommen vervolgkeuzemenu worden uitgeschakeld.
