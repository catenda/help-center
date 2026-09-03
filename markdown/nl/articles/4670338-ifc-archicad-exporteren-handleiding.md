# IFC Export Archicad Handboek

Wanneer u een IFC exporteert, moet u bedenken wat relevant is voor uw IFC-export. Het IFC-bestand kan groot en moeilijk te hanteren zijn als het veel informatie bevat. Daarom is het belangrijk om onnodige informatie niet te exporteren. In dit rapport krijgt u verschillende tips om uw IFC-export in Archicad te filteren.

## 1. **1. Projectinfo**

Voordat u een IFC uit uw project exporteert, moet u ervoor zorgen dat de projectinfo is geconfigureerd. De projectinfo is hier te vinden:

`Bestand -> Info -> Projectinfo`

Dit is hoe de projectinfo eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/01-1-project-info.png)

Standaard zijn de verschillende velden leeg. Ook al zijn ze leeg, voor elk project, elke site en elk gebouw dat wordt vermeld, wordt een unieke id aangemaakt.

### 1.1 **1.1 Meerdere IFC's uit hetzelfde Archicad-project**

In sommige situaties worden meerdere IFC-bestanden uit hetzelfde Archicad-project geëxporteerd. Voorbeelden hiervan zijn:

**1.1.1 IFC-bestanden met objecten uit verschillende vakgebieden** Een MEP-model met kanalen, een architectuurmodel met muren en een structureel model met alle vloeren.

**1.1.2 Meerdere gebouwen** Soms worden meerdere gebouwen in hetzelfde Archicad-bestand samen gemodelleerd en wordt voor elk van hen een afzonderlijke IFC geëxporteerd.

**1.1.3 Verschillende ontwerpkeuzes** Wanneer verschillende variaties van een gebouw in hetzelfde Archicad-bestand worden gemodelleerd, wordt elke variatie vaak naar een eigen IFC-bestand geëxporteerd.

### 1.2 **1.2 De projectinfo configureren**

Of u nu van plan bent meerdere IFC-bestanden te exporteren of niet, het is vaak een goed idee om waarden in de projectinfo in te voeren, zodat deze later niet hoeven te worden gewijzigd. De projectinfo is belangrijk om in te vullen omdat deze invloed heeft op de GUID's van het bestand. Elk type IFC dat wordt geëxporteerd, moet zijn eigen projectinstellingen hebben. De projectinstellingen kunnen onderaan rechts worden geïmporteerd en geëxporteerd. Op deze manier kunnen meerdere profielen worden ondersteund voor de exports uit het bestand. Voor Catenda is het belangrijk dat IFC's in verschillende modellen verschillende informatie hebben geconfigureerd, terwijl IFC's die in hetzelfde model voorkomen dezelfde informatie hebben geconfigureerd.

## 2. **2. IFC-exportinstellingen**

Om het volledige project te exporteren, moet u zich in de 3D-weergave bevinden. Zorg ervoor dat u de juiste vertaler gebruikt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/02-2-ifc-export-settings.png)

Klik op de knop Opties om een overzicht van uw IFC-exportinstellingen weer te geven. Onder modelfilter kunt u ook kiezen om meer uit te filteren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/03-2-ifc-export-settings.png)

Met het vak IFC-vertalers kunt u vertalersinstellingen weergeven of wijzigen, of nieuwe vertalers maken. Als u uw IFC-export wilt wijzigen, wordt aanbevolen dat u een van de vooraf gemaakte vertalers dupliceert, zodat u er geen standaardvertaler mee verpest. Dupliceer hier een vertaler: Klik op Nieuw > Duplicaat van > selecteer de vertaler die u wilt dupliceren. Als u de IFC wilt samenvoegen, kunt u dat onder dezelfde banner doen.

![image-2.png](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/04-2-ifc-export-settings.png)

## 3. **3. Verschillende instellingen in de export**

3.1 [Modelfilter](#h_138e653078) stelt u in staat uit te filteren wat u wilt exporteren via verschillende voorinstellingen. 3.2 [Typetoewijzing](#h_a34c1332a3) stelt u in staat te kiezen welk type IFC elk element wordt geëxporteerd als. 3.3 [Geometrieconversie](#h_db084b5d6b) stelt u in staat te kiezen wat voor soort geometrie u wilt exporteren. 3.4 [Eigenschappentoewijzing](#h_d48644eb35) stelt u in staat criteria in te stellen op basis van typen. 3.5 [Gegevensconversie](#h_7f1df4ecb9) stelt u in staat te kiezen wat voor soort gegevens u uit het model wilt exporteren. 3.6 [Eenheidsconversie](#h_36caead1cd) stelt u in staat te kiezen in welke meeteenheden u uw IFC wilt exporteren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/05-3-different-settings-in-the-export.png)

## 4. **4. Modelfilter**

### 4.1 **Rasters in de IFC exporteren**

Soms wilt u ook de rasters geëxporteerd hebben zodat u ze in Catenda Hub kunt zien. Ga naar het modelfilter voor IFC-export en zorg ervoor dat het selectievakje "Rastersysteem en elementen" is ingeschakeld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/06-exporting-grids-in-the-ifc.png)

## 5. **5. Typetoewijzing**

Wanneer een IFC wordt geëxporteerd, krijgen alle elementen in het model een IFC-type toegewezen. Als u de IFC-vertaler selecteert die u wilt gebruiken, kunt u naar typetoewijzing gaan en klikken op Map IFC Types for import om te beheren wat voor soort typetoewijzing u op uw geëxporteerde IFC wilt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/07-5-type-mapping.png)

Typetoewijzing heeft vooral twee verschillende opties om uw IFC-typen op te sorteren.

### 5.1 **5.1 Elementtype**

Elk element krijgt automatisch een basis-IFC-type toegewezen. U kunt het toegewezen IFC-type van elk element zien in de projectmanager en in de elementinstellingen.

### 5.2 **5.2 Classificatie**

Deze methode staat meer flexibele en gedetailleerde IFC-typetoewijzing toe, overeenkomstig specifieke classificatienormen. Zone- en openingselementen zijn ingesteld op een vast IFC-type. IFCSpace en IFCOpeningElements.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/08-5-2-classification.png)

## 6. **6. Geometrieconversie**

Geometrieconversie voor IFC-export stelt u in staat uw geometrie op verschillende manieren te converteren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/09-6-geometry-conversion.png)

### 6.1 Conversies van Archicad-elementen

**6.1.1 Alleen geometrieën exporteren die "Deelnemen aan botsingsdetectie"** Exporteer alleen objecten die elkaar kruisen

**6.1.2 Geometrie van IFC-typeproducten exporteren** Typeproducten inbegrepen

**6.1.3 Brutogeometrie van elementen exporteren** Brutogeometrie inbegrepen

**6.1.4 Alle geometrie van modelelementen exporteren als:** _Parametrisch met uitzonderingen_ - standaard

**Parametrisch (Geëxtrudeerd/gedraaid)** _BREP_ - Precieze geometrie - Als dit is geselecteerd, zullen de volgende twee opties ook BREP zijn

**6.1.5 Elementen in vaste elementbewerkingen:** _Geëxtrudeerd/gedraaid_ - standaard _BREP_ - Precieze geometrie

**6.1.6 Elementen met verbindingen** Sommige elementen kunnen elkaar kruisen, waardoor delen van de extrude kunnen worden geknipt.

Geëxtrudeerd/gedraaid - Verbind hoeken van elementen Dit voegt verbindingen toe aan uw geëxtrudeerde elementen. Met deze optie ziet u dat elementen zoals muren of daken, vooral schuine, mooi met elkaar verbonden zijn.

Geëxtrudeerd/gedraaid zonder verbindingen - standaard Dit versnelt de export Als u elementen van 90 graden hebt, zoals muren of daken, zult u waarschijnlijk geen verschil opmerken met deze optie. Als u schuine muren hebt, zult u opmerken dat in de hoek waar de muren verbonden zijn, in plaats van het overtollige van de rechte extrude af te knippen, de muren gewoon recht langs elkaar heen gaan en niet mooi verbonden zijn.

BREP Precieze geometrie

**6.1.7 Parametrische elementen** Archicad-elementen kunnen worden geëxporteerd als parametrische geometrie, vaak in de vorm van leidende lijnen die over een afstand worden geëxtrudeerd. Parametrische geometrie maakt het gemakkelijk om het object na het maken te bewerken. Hoewel deze optie bewerkbaarheid behoudt, kan de geometrie vaak enigszins onnauwkeurig zijn, omdat de definitie een benadering van de geometrie is. Deze optie wordt aanbevolen als u de IFC terug in Archicad of een ander bewerkingsprogramma wilt importeren om verdere bewerkingen uit te voeren.

BREP Exporteer geometrie als afzonderlijke BREP-oppervlakken. In plaats van objecten aan de hand van hun parameters zoals lengte/breedte/hoogte te beschrijven met gegenereerde oppervlakken, wordt elk oppervlak als een afzonderlijk oppervlak met een locatie in 3D beschreven. Objecten kunnen nog steeds meerdere oppervlakken bevatten, maar deze zijn los van elkaar. Na het exporteren moeten BREP-oppervlakken afzonderlijk worden bewerkt, omdat parameters niet meer op het oppervlak van toepassing zijn. Met de BREP-optie worden exacte oppervlakken geëxporteerd, zodat er geen verschil in interpretatie van parameters tussen authoring tools. Oppervlakken worden afzonderlijk gekleurd en hebben dezelfde kleur in Catenda Hub als in Archicad. Oppervlakkleuren kunnen in het volgende menu worden geconfigureerd:

`Opties -> Elementeigenschappen -> Oppervlakken`

Het kan goed zijn om alle instellingen voor een oppervlak te configureren, omdat deze in de IFC worden geschreven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/10-6-1-conversions-of-archicad-elements.png)

Oppervlakken in de Catenda 3D-viewer hebben vlakke schaduw zonder aanwezige lichtbron. Dit betekent dat waarden zoals Ambient, Attenuation, Shinyness, Emission en Specular niet worden geïnterpreteerd wanneer het oppervlak in de Catenda 3D-viewer wordt bekeken. De volgende waarden worden door Catenda geïnterpreteerd bij het weergeven van het oppervlak in de 3D-viewer:

Oppervlakkleur De kleur van het oppervlak

Transmissie Hoeveel u door het object kunt zien (Overschrijft de semi-transparante opaciteitsinstelling)

Diffuus Hoe donker of helder de oppervlakkleur is

**6.1.8 Definieer IFC-modelposie door:** Deze optie bepaalt de projectlocatie. Het is belangrijk dat u al aan het begin van het project overeenstemming bereikt over een gemeenschappelijk referentiepunt. Het wijzigen ervan kan betekenen dat meerdere consultants hun objecten moeten verplaatsen, wat tegen het einde van een project vaak niet haalbaar is.

Onderzoekspunt en projectoorsprong - standaard Met deze optie is de afstand van (0,0,0) naar uw model in Archicad gelijk aan de afstand van (0,0,0 + coördinaten van uw onderzoekspunt) naar uw model in Catenda Hub + de. Als u een projectlocatie hebt ingesteld, bevindt uw model zich op die coördinaten in Catenda Hub

Alleen projectoorsprong Met deze optie is de afstand van (0,0,0) naar uw model in Archicad gelijk aan de afstand van (0,0,0) naar uw model in Catenda Hub.

Alleen onderzoekspunt Met deze optie is de afstand van het onderzoekspunt in Archicad naar uw modellen gelijk aan de afstand van (0,0,0) naar uw model in Catenda Hub

## 7. **7. Hiërarchische Archicad-elementen**

Exporteer objecten in een vlakke hiërarchie of als geneste subelementen.

### 7.1 **7.1 Gevelraam**

Converteren naar Enkel element Hierarchie behouden - Standaard

### 7.2 **7.2 Trap**

Converteren naar Enkel element Hierarchie behouden - Standaard

### 7.3 **7.3 Leuning**

Converteren naar Enkel element - Standaard Hierarchie behouden

## 8. **8. Opties met betrekking tot IFC-schema**

### 8.1 **8.1 Modus voor materiaalconservering (alleen IFC2x3)**

**8.1.1 Elementen nooit uit elkaar halen, conservering niet gegarandeerd** Met deze optie exporteert u het hele object als één object

**8.1.2 Alleen uit elkaar halen indien nodig om materialen te conserveren - Standaard** Met deze optie exporteert u alleen afzonderlijke objecten voor elk composietmateriaal indien nodig

**8.1.3 Alle elementen in onderdelen uit elkaar halen, materialen conserveren** Met deze optie worden alle objecten geëxporteerd als afzonderlijke objecten voor elk materiaal. Als u een composiet wandmateriaal hebt, betekent dit dat voor elk materiaal een afzonderlijk object wordt geëxporteerd. U hebt vaak een dampscherm dat 1-5 mm is, wat resulteert in een erg dun object. Wanneer objecten zo dun zijn, kan de geometrie onnauwkeurig zijn. Problematische wandmaterialen kunnen er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/11-8-1-material-preservation-mode-ifc2x3-only.png)

Dit kan het voor software moeilijk maken om gaten door het oppervlak te snijden, omdat de onnauwkeurigheid het moeilijk maakt om precies uit te zoeken waar het gat zich moet bevinden. Als u daarom opmerkt dat uw openingen niet worden doorsneden, kan het helpen om deze optie in te schakelen. Het inschakelen van deze optie exporteert de muur als één enkel object in plaats van veel dunne samengestelde objecten.

## 9. **9. Samengestelde structuren en complexe profielen**

**9.1 Splitsing van complexe bouwelementen in onderdelen** Hier kunt u kiezen voor welk type elementen u het samengestelde element wilt splitsen en voor welke elementen u dit niet wilt doen. Als u deze optie kiest, kunt u geen keuze maken voor de modus voor materiaalconservering.

## 10. **10. Eigenschappentoewijzing**

In eigenschappentoewijzing (Bestand > IFC > Interoperabiliteit > Eigenschappentoewijzing) kunt u kiezen welke versie van IFC u wilt exporteren. U hebt de standaard IFC2x3 en de standaard IFC4. U kunt ook psets toevoegen om met uw IFC te exporteren. Als u dit doet, moet u een duplicaat van het IFC-schema dat u kiest maken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/12-10-property-mapping.png)

Nadat u een duplicaat van uw standaard IFC hebt gemaakt, kunt u de gewenste eigenschappen aan die nieuwe voorinstelling toevoegen door het IFC-schema te selecteren en op _Map IFC Properties for Export_ te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/13-10-property-mapping.png)

## 11. **11. Gegevensconversie**

Onder gegevensconversie selecteert u wat voor soort gegevens u naast geometrie uit uw IFC-export wilt halen. Controleer de selectievakjes van wat u wilt exporteren. Elementparameters leest de Archicad-elementparameter en converteert deze naar IFC-hoeveelheden of IFC-eigenschappen. Afhankelijk van hun type. Door deze optie te kiezen, vergroten u de bestandsgrootte aanzienlijk.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/14-11-data-conversion.png)

IFC Base Quantities leest de parameters van grootte, oppervlakte en volume. Als u dit selectievakje niet uitschakelt, kan het importeren van uw IFC naar Catenda Hub problemen opleveren.

## 12. **12. Eenheidsconversie**

Stel de eenheden voor lengte, hoek, oppervlakte, volume, valuta en tijd voor uw export in.
