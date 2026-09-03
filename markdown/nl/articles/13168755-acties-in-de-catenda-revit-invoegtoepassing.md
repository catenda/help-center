# Acties in de Catenda Revit-invoegtoepassing

> **Opmerking:** Het installatiebestand voor de invoegtoepassing is te vinden in [dit artikel](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

De acties [Catenda Revit-invoegtoepassing](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin) zijn te vinden rechtsboven in het invoegtoepassing-venster in de Revit-toepassing.

Dit ziet het actiemenu er als volgt uit:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/01-intro.png)

Informatie over de volgende Topics is te vinden in dit artikel:

## 1. **1. Nieuwe Topic**

Klik op de groene knop Nieuwe Topic rechtsboven om een nieuwe Topic te maken in het project dat momenteel is geselecteerd in het vervolgkeuzemenu linksboven. De Topic wordt gemaakt in het Topic board dat is geselecteerd in het tweede vervolgkeuzemenu linksboven. _Vereiste toegang:_ Schrijftoegang tot het Topic board

Zodra de Topic is gemaakt, is deze zichtbaar in Catenda Hub via de browser en via alle Catenda-invoegtoepassingen in andere programma's. Dit ziet de nieuwe Topic-pagina er als volgt uit:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/02-1-new-topic.png)

De minimale informatie die nodig is om een Topic in te dienen is een titel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/03-1-new-topic.png)

### 1.1 **1.1 Indienen**

Zodra de Topic gereed is om met het project te delen, klikt u op Indienen om de Topic in te dienen bij het Topic board.

## 2. **2. IFC uploaden**

Klik op IFC uploaden in het actiemenu dat wordt geopend met de drie punten rechtsboven om uw huidige Revit-model rechtstreeks naar Catenda Hub als IFC-bestand te uploaden. Dit ziet de pagina IFC uploaden er als volgt uit:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/04-2-upload-ifc.png)

### 2.1 **2.1 Een model selecteren**

In dit vervolgkeuzemenu worden reeds bestaande modellen uit het geselecteerde project weergegeven. Als er geen model in het project bestaat, maakt u eerst een leeg model in Catenda via de browser. De geüploade IFC wordt een nieuwe revisie van het geselecteerde model. Elk model in Catenda is gekoppeld aan een documentcontainer, dus na het uploaden is de revisie zichtbaar in zowel het model- als het documentgedeelte van het project.

### 2.2 **2.2 Bestandsnaam**

Typ een optionele bestandsnaam die aan het upload is gekoppeld. Alleen ASCII-tekens worden in dit veld ondersteund.

### 2.3 **2.3 Een opmerking toevoegen**

Typ een verplichte opmerking die aan het upload is gekoppeld. Zodra een opmerking is toegevoegd, wordt de uploadknop gemarkeerd en kan erop worden geklikt. Alleen ASCII-tekens worden in dit veld ondersteund.

### 2.4 **2.4 Exportconfiguratie**

Selecteer een IFC-configuratie. Een nieuwe configuratie kan worden gemaakt in het IFC-exportmenu in Revit. U kunt ook de \<Catenda Setup> selecteren voor een gemakkelijk te gebruiken configuratie die goed geschikt is voor Catenda Hub.

Dit zijn de exportinstellingen van de Catenda Setup

```
selectedConfig.Name = "<Catenda Setup>"; selectedConfig.IFCVersion = IFCVersion.IFC2x3CV2; selectedConfig.SpaceBoundaries = 1; selectedConfig.ActivePhaseId = ElementId.InvalidElementId; selectedConfig.ExportBaseQuantities = true; selectedConfig.SplitWallsAndColumns = false; selectedConfig.VisibleElementsOfCurrentView = false; selectedConfig.Use2DRoomBoundaryForVolume = false; selectedConfig.UseFamilyAndTypeNameForReference = true; selectedConfig.ExportInternalRevitPropertySets = true; selectedConfig.ExportIFCCommonPropertySets = true; selectedConfig.Export2DElements = false; selectedConfig.ExportPartsAsBuildingElements = true; selectedConfig.ExportBoundingBox = false; selectedConfig.ExportSolidModelRep = false; selectedConfig.ExportSchedulesAsPsets = false; selectedConfig.ExportUserDefinedPsets = false; selectedConfig.ExportUserDefinedPsetsFileName = ""; selectedConfig.ExportLinkedFiles = false; selectedConfig.IncludeSiteElevation = true; selectedConfig.UseActiveViewGeometry = false; selectedConfig.ExportSpecificSchedules = false; selectedConfig.TessellationLevelOfDetail = 0; selectedConfig.StoreIFCGUID = true; selectedConfig.ExportRoomsInView = true;
```

### 2.5 **2.5 Uploaden**

Klik op Uploaden om een IFC te uploaden. Er moet een opmerking worden toegevoegd om te kunnen uploaden. _Vereiste toegang:_ Schrijftoegang tot het document dat aan het model is gekoppeld.

## 3. **3. Instellingen**

Op de pagina Instellingen kunt u wijzigen hoe de invoegtoepassing een 3D-weergave maakt wanneer u de [Zoomfunctie](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin#h_36392f671a) gebruikt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/05-3-settings.png)

### 3.1 **3.1 Terug naar Topics**

Klik op Terug naar Topics om terug te gaan naar de Topics-lijst.

### 3.2 **3.2 Navigatie**

**Houd de 3D-weergave orthogonaal** Met deze optie wordt de 3D-weergave in Revit orthogonaal gehouden, zelfs als het corresponderende viewpoint met een perspectiefweergave is gemaakt.

**Maak een nieuwe weergave voor elke Topic** In plaats van telkens dezelfde 3D-weergave opnieuw te gebruiken wanneer u de Zoomfunctie gebruikt, maakt deze optie telkens een nieuwe 3D-weergave voor elke Topic wanneer u de zoomfunctie gebruikt.

**Achtervoegsel van 3D-weergavenaam** Deze tekst wordt toegevoegd aan de naam van de 3D-weergave die wordt gemaakt wanneer u de Zoomfunctie gebruikt.

### 3.3 **3.4 Viewpoint-transformatie**

Met de viewpoint-transformatie kan het viewpoint in Revit worden geconfigureerd met een bepaalde verschuiving. Als hier waarden zijn geconfigureerd, wordt het viewpoint telkens verschoven met die hoeveelheid wanneer een viewpoint uit een Topic wordt afgespeeld. Dit kan handig zijn wanneer de coördinaten in het Topic-viewpoint niet overeenkomen met de coördinaten die in het Revit-project zijn geconfigureerd.

**3.4.1 X (E/W)** Transformatie in de X-richting. Oost of west, afhankelijk van positieve of negatieve waarden. Eenheden in meters

**3.4.2 Y (N/S)** Transformatie in de Y-richting. Noord of zuid, afhankelijk van positieve of negatieve waarden. Eenheden in meters

**3.4.3 Z (Elev)** Transformatie in de Z-richting. Hoogte, afhankelijk van positieve of negatieve waarden. Eenheden in meters

**3.4.4 Hoek** Rotatietransformatie. Hoogte, afhankelijk van positieve of negatieve waarden. Eenheden in graden. De camera blijft op dezelfde hoogte en roteert rond een punt in het model.

## 4. **4. Mijn account**

Open uw Catenda Hub-accountpagina in uw standaardbrowser. Klik [hier](https://support.catenda.com/en/articles/6880968-account-page) voor meer informatie over de accountpagina.

## 5. **5. Uitloggen**

Klik op Uitloggen om u af te melden bij Catenda Hub in de invoegtoepassing.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/06-5-sign-out.png)

Na het afmelden wordt de pagina Aanmelden weergegeven, waar u zich met dezelfde account of een ander account kunt aanmelden met gebruikersnaam en wachtwoord. Klik [hier](https://support.catenda.com/en/articles/7891486-sign-in-page) voor meer informatie over de aanmeldingspagina.

Na het opnieuw aanmelden wordt het eerste project in de projectlijst weergegeven. Selecteer opnieuw een project in de projectlijst om naar een ander project te navigeren.
