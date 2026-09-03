# Filteren op de objectenpagina

Het filterpaneel op de objectenpagina kan worden geopend door op de filterknop links van de zoekbalk op de objectenpagina te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/01-intro.png)
Dit is hoe het zoekmenu of filtermenu eruit kan zien wanneer het is geopend:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/02-intro.png)

## 1. **Filters**

Klik op de filterknop linksboven om een paneel aan de linkerkant te laten verschijnen. Wanneer een filter wordt toegepast, verandert de URL die zichtbaar is in de browser ermee. In dit artikel worden filters als volgt weergegeven: _Filternaam in menu_ - `Filternaam in URL=Filteroptie in URL`

**Standaardfilter** Het standaardfilter is in eerste instantie niet zichtbaar in de URL. Wanneer de pagina voor het eerst wordt bezocht, wordt het volgende filter toegepast.

**Geen filter**

### 1.1 **Huidige filter opslaan en delen**

Ga naar de URL van een gefilterde pagina om die pagina met het toegepaste filter te laden. De toegepaste filters kunnen bovenaan het filtermenu worden opgeslagen. Klik [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) voor meer informatie over het opslaan en delen van filters

### 1.2 **Lege filters verbergen**

Klik [hier](https://support.catenda.com/en/articles/8551755-saving-filters) voor meer informatie over het beperken van filterresultaten.

### 1.3 **Modellen**

Klik op 3D rechts van de modelcategorie in het filtermenu om op alle modellen te filteren die momenteel in de 3D-viewer zijn geladen.

Modelnaam - `model=<Model GUID>` Filteren op een set projectmodellen.

### 1.4 **Geselecteerd**

Geselecteerd - `selected=true` Filteren om alleen rijen voor objecten weer te geven die in de 3D-viewer zijn geselecteerd.

## 2. **Filters die niet in het filterpaneel worden weergegeven**

### 2.1 **Query**

Queryzoeking - `query=<Product>,<Operator>,<Value>` Klik in de zoek- of filterbalk om een filter te configureren dat twee waarden vergelijkt.

**Product** De eerste selectie kan elk soort IFC-product zijn. Dit is hoe de productdropdown eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/03-query.png)

**Operator** De operator kan alleen worden geselecteerd nadat een product is geselecteerd. Het operatordeel van het queryfilter bepaalt hoe het product tegen de waarde wordt vergeleken. Afhankelijk van of het product elke waarde kan hebben of alleen een beperkte set waarden kan hebben, kunnen verschillende operators worden gekozen uit:

Altijd beschikbare operators: Gelijk aan - `equals` Wanneer het geselecteerde product exact de ingevoerde waarde heeft

Niet gelijk aan - `not-equals` Wanneer het geselecteerde product niet exact de ingevoerde waarde heeft

Bestaat - `exists` Wanneer bestaat is geselecteerd, kan alleen een product worden geselecteerd en geen waarde, omdat alle waarden deel van dit filter zijn

Bestaat niet - `not-exists` Wanneer bestaat niet is geselecteerd, kan alleen een product worden geselecteerd en geen waarde, omdat alle waarden deel van dit filter zijn

Operators voor beperkte reeks waarden Dit is hoe de operatordropdown eruit kan zien wanneer de geselecteerde eigenschap een beperkte set waarden heeft:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/04-query.png)

Bevat - `contains`

Bevat niet - `not-contains` Om resultaten te krijgen over producten die een bepaalde waarde niet bevatten

Heeft waarde - `has-value` Wanneer heeft waarde is geselecteerd, kan alleen een product worden geselecteerd en geen waarde, omdat alle waarden deel van dit filter zijn

Operators voor elke waarde Dit is hoe de operatordropdown eruit kan zien wanneer de geselecteerde eigenschap elke waarde kan hebben:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/05-query.png)

In bereik - `range-inclusive` Wanneer de operator in bereik is geselecteerd, zijn er twee waardevelden. Dit is hoe het eruit kan zien wanneer een bereikfilter wordt bewerkt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/06-query.png)

Het bereik kan alles zijn van de eerste waarde tot de tweede waarde.

Groter dan of gelijk aan - `greater-than-equals`

Groter dan - `greater-than`

Kleiner dan of gelijk aan - `less-than-equals`

Kleiner dan - `less-than`

**Waarde** Het waardeveld gedraagt zich anders afhankelijk van de mogelijke waarden die het geselecteerde product kan hebben.

Nummerieke waarde Wanneer het geselecteerde product alleen een nummerieke waarde kan hebben, worden pijlen weergegeven wanneer op het waardeveld wordt geklikt en kunnen alleen nummers worden ingevoerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/07-query.png)

Aanbevolen waarden Wanneer een product een tekstwaarde kan hebben, kan deze rechtstreeks in het waardeveld worden geschreven. Dit is hoe het waardenmenu eruit kan zien wanneer het product Entity is geselecteerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/08-query.png)

Wanneer u in het waardeveld klikt, wordt een lijst met voorgestelde elementen onder het veld weergegeven. Als het geselecteerde product alleen een beperkte set waarden kan hebben, wordt deze beperkte set waarden weergegeven in de lijst met voorgestelde elementen. Als het geselecteerde product elke waarde kan hebben, toont de lijst met voorgestelde elementen een lijst met waarden die andere producten van dit soort hebben.
