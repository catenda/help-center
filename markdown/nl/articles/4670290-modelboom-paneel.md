# Modelboom-paneel

Het modelboom-paneel is te vinden als één van de vier [projectpanelen](https://support.catenda.com/en/articles/13141464-project-panels) die rechtsboven op het scherm kunnen worden geopend.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/01-intro.png)

## 1. **Het modelboom-paneel openen**

Het modelboom-paneel kan naast elk ander paneel worden geopend.

_Het modelboom-paneel openen:_ Klik op het boomicoon of druk op [shift+3](https://support.catenda.com/en/articles/4670267-summary-of-most-important-shortcuts-and-basic-controls#:~:text=row%20of%20objects-,Shift%20%2B%203,-Control%20%2B%20left%20click)

_Het modelboom-paneel isoleren:_ Open het boompaneel Sluit alle andere openstaande panelen door erop te klikken.

## 2. **Modelboom** **paneelinhoud**

In het boompaneel kan de inhoud van de IFC in verschillende boomstructuren worden weergegeven. De weergegeven structuur komt rechtstreeks van het IFC-model dat boven is geselecteerd. Elk van de bomen toont delen van de IFC op verschillende manieren. Lijstelementen voor objecten die zichtbaar zijn in de 3D-viewer kunnen zichtbaar zijn in één of meer van de modelbomen, afhankelijk van of ze op die manier passen om de IFC-inhoud te bekijken. Andere lijstelementen kunnen groepering van deze objecten en/of andere entiteiten uit de IFC bevatten.

### 2.1 **Naamgeving van lijstelementen**

Lijstelementen kunnen op verschillende manieren worden benoemd. Benoemde entiteiten kunnen worden benoemd met de naam die eraan is toegewezen in de IFC, maar entiteiten kunnen ook worden benoemd naar de naam van de entiteit zelf, zoals opgegeven in de BuildingSMART-standaard. Als er geen vertaling beschikbaar is volgens de standaard, kan de naam in het Engels worden weergegeven, wat de basistaal is. Zie [hier](https://user.buildingsmart.org/knowledge-base/ifc-translations-manual/) voor het bijdragen aan de vertaling in de open standaard. Om te zien of een entiteit een vertaling heeft, gaat u naar de BuildingSMART-pagina voor die entiteit en wijzigt u de taal in de taal. De naam van de entiteit wordt ofwel vertaald, ofwel er verschijnt een bericht aan de bovenkant dat deze entiteit geen vertaling heeft.

**Groepering van entiteiten** Entiteiten die andere entiteiten kunnen bevatten, zoals een gebouw dat muren bevat, kunnen worden benoemd naar de naam die aan die entiteit is gegeven, indien aanwezig, of naar de naam van de entiteit per BuildingSmart-standaard.

**Afzonderlijke elementen** Afzonderlijke elementen zijn de elementen op het laagste niveau wanneer de boomweergave volledig is uitgevouwen en kunnen er als volgt uitzien:

`Entity.Set.Number`

Naam Deze elementen worden vermeld met de naam van hun entiteit volgens de BuildingSMART-standaard.

Set Er zijn vaak veel vergelijkbare elementen die samen worden gegroepeerd. Na de entiteitsnaam staat het nummer van de nde set van deze typen entiteiten waartoe deze entiteit behoort.

Number Ten slotte wordt het nummer van de nde entiteit in de set vermeld. Bijvoorbeeld, het 21e raam op niveau 2 kan er als volgt uitzien:

`Window.1.21`

### 2.2 **Gemarkeerde elementen**

Net als in de 3D-viewer worden geselecteerde objecten groen gemarkeerd en geselecteerde groepen objecten geel gemarkeerd. In tegenstelling tot in de 3D-viewer is het ook mogelijk entiteiten te markeren die objecten kunnen bevatten en sets van vergelijkbare objecten te markeren. Als een object in de 3D-viewer is gemarkeerd, maar geen object in het modelboom-paneel is gemarkeerd, kan het zijn dat het object in een ander modelboom-menu is gemarkeerd.

**Inzoomen op lijstelement** Bomen kunnen behoorlijk lang worden. Wanneer een object in de 3D-viewer is geselecteerd, wordt het boommenu naar de locatie in de lijst gescrolld waar het geselecteerde object bestaat, op voorwaarde dat dat object in het boommenu dat in het modelboom-paneel is geopend, bestaat.

### 2.3 **Selectie**

Lijstelementen van meerdere modellen die in de 3D-viewer zijn geladen, kunnen worden geselecteerd. Klik op de vervolgkeuzelijst aan de bovenkant om tussen de verschillende modellen te schakelen. Selecties kunnen in het selectiemenu worden opgeslagen.

**Actief element** Het actieve element wordt gemarkeerd met een rode gestippelde omtrek. Gebruik de pijltoetsen om omhoog en omlaag in de lijst te bewegen.

**Eenvoudige selectie** Na het klikken op een lijstelement om het te selecteren, wordt het element ingesteld als het actieve element en wordt de vorige selectie gewist.

Klik op een lijstelement of druk op Enter op het actieve element om: Een object te selecteren. Een set objecten en alle vergelijkbare objecten in een set objecten te selecteren. Een groep sets en alle subelementen in die groep te selecteren.

**Selectie bewerken** Ctrl+Klik op een lijstelement of druk op Ctrl+Enter op het actieve lijstelement om: Lijstelementen die niet eerder waren geselecteerd, aan de selectie toevoegen. Lijstelementen die zijn geselecteerd, uit de selectie verwijderen.

**Selectie instellen** Shift+Klik op een lijstelement of druk op Shift+Enter op het actieve lijstelement nadat u een ander lijstelement hebt geselecteerd om: Alle lijstelementen tussen het eerder geselecteerde element en het geselecteerde element te selecteren.

**Inzoomen op lijstelement** Dubbelklik op een lijstelement om de 3D-viewer op dat lijstelement in te zoomen.

## 3. **Inhoudboom**

De inhoudboom biedt een hiërarchisch perspectief op hoe de verschillende IFC-objecten met elkaar samenhangen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/02-containment-tree.png)

Wanneer de sneltoets "`p`" wordt ingedrukt om het bovenliggende knooppunt te selecteren, kan dit visueel in de inhoudboom worden waargenomen.

## 4. **Componentboom**

De componentboom biedt een hiërarchisch perspectief op de onderdelen waaruit een object is samengesteld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/03-component-tree.png)

In dit boommenu kunnen componenten als volgende worden gevonden:

AirTerminal Annotation Beam BuildingElementPart BulidingElementproxy Coil Column Covering CurtainWall Damper Distributionport DiscreteAccessory Ductfitting DuctSilencer Door ElementAssembly EnergyConversionDevice Fan Fastener Filter FireSuppresionTernimal FlowController FlowFitting FlowMovingDevice FlowSegment FlowStoragedevice FlowTerminal Footing FurnishingElement GeographicElement Grid HeatExchanger LightFixture Member OpeningElement PipeFitting PipeSegment Pump Plate Railing Ramp Roof SanitaryTerminal Site Slab Space SpaceHeater StackTerminal Stair StairFlight TransportElement UnitaryEquipment Valve Wall WallStandardCase WasteTerminal Window

## 5. Typeboom

De typeboom toont alle objecten gesorteerd op hun type.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/04-type-tree.png)

## 6. Laagboom

De laagboom biedt een hiërarchische weergave van de lagen in het model.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/05-layer-tree.png)

## 7. Systeemboom

De systeemboom biedt een weergave van de systemen in het model.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/06-system-tree.png)

> **Opmerking:** Het object dat in de boom en in het model is geselecteerd, is gesynchroniseerd. Als u op een venster in de 3D-modus klikt, wordt het in de boom geselecteerd. En vice versa. U kunt ook dubbelklikken op een "blad" in het model om de 3D-camera naar dat object te verplaatsen.
