# IFC Export Archicad Handleiding

Wanneer u een IFC exporteert, houd er rekening mee wat relevant is voor uw IFC-export. Het IFC-bestand kan groot en moeilijk te bewerken zijn als het veel informatie bevat. Daarom is het belangrijk om geen onnodige informatie te exporteren. In dit rapport krijgt u verschillende tips om uw IFC-export in Archicad te filteren.

## 1. Projectinfo

Voordat u een IFC van uw project exporteert, zorg ervoor dat de projectinfo is geconfigureerd. De projectinfo vindt u hier:

`Bestand -> Info -> Projectinfo`

Dit is een voorbeeld van hoe de projectinfo eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/01-project-info.png)

Standaard zijn de verschillende velden leeg. Hoewel deze leeg zijn, wordt een unieke ID gemaakt voor elk project, lokatie en gebouw dat is opgenomen. In sommige situaties worden meerdere IFC-bestanden uit hetzelfde Archicad-project geëxporteerd. Voorbeelden hiervan zijn:

IFC-bestanden met objecten uit verschillende vakgebieden. Een MEP-model met kanalen, een architectuurmodel met muren en een structureel model met alle vloeren.

Meerdere gebouwen Soms worden meerdere gebouwen samen in hetzelfde Archicad-bestand gemodelleerd en voor elk daarvan wordt een afzonderlijke IFC geëxporteerd.

Verschillende ontwerpkeuzes. Wanneer verschillende varianten van een gebouw in hetzelfde Archicad-bestand zijn gemodelleerd, wordt elke variant vaak naar zijn eigen IFC-bestand geëxporteerd.

### 1.1 De projectinfo configureren

Of er nu plannen zijn om meerdere IFC-bestanden te exporteren of niet, het is vaak een goed idee om waarden in de projectinfo in te voeren, zodat deze later niet hoeven te worden gewijzigd. De projectinfo is belangrijk om in te vullen omdat deze effect heeft op de GUID's van het bestand. Elk type IFC dat wordt geëxporteerd, moet eigen projectinstellingen hebben. De projectinstellingen kunnen rechtsonder worden geïmporteerd en geëxporteerd. Op deze manier kunnen meerdere profielen voor de exports uit het bestand worden ondersteund. Voor Catenda is het belangrijk dat IFC's in verschillende modellen verschillende informatie hebben geconfigureerd, terwijl IFC die in hetzelfde model zal zijn dezelfde informatie heeft geconfigureerd.

## 2. IFC-exportinstellingen

Het gehele project exporteren. U moet in 3D-weergave staan. Zorg ervoor dat u de juiste vertaler gebruikt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/02-ifc-export-settings.png)

Klik op de opties-knop om een samenvatting van uw IFC-exportinstellingen te zien. Onder modelfilter kunt u ook meer filteren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/03-ifc-export-settings.png)

In het vak IFC-vertalers kunt u vertalersinstellingen bekijken of wijzigen, of nieuwe vertalers maken.

Als u uw IFC-export wilt wijzigen, wordt aanbevolen om een van de vooraf gemaakte vertalers te dupliceren zodat u geen van de standaardvertalers beschadigt. Dupliceer hier een vertaler:

Klik op nieuw > Duplicaat van > selecteer de vertaler die u wilt dupliceren.

Als u de IFC wilt samenvoegen, kunt u dat onder dezelfde banner doen.

![image-2.png](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/04-ifc-export-settings.png)

---

### 2.1 Verschillende instellingen in de export

1\. [Modelfilter](#model-filter) stelt u in staat uit te filteren wat u wilt exporteren op basis van verschillende voorinstellingen. 2\. [Type-toewijzing](#type-mapping) stelt u in staat te kiezen wat voor soort IFC-type elk element wordt geëxporteerd. 3\. [Geometrieconversie](#geometry-conversion) stelt u in staat te kiezen wat voor soort geometrie u wilt exporteren. 4\. [Eigenschappentoewijzing](#property-mapping) stelt u in staat criteria op basis van typen in te stellen. 5\. [Gegevensconversie](#data-conversion) stelt u in staat te kiezen wat voor soort gegevens u uit het model wilt exporteren. 6\. [Eenhedenconversie](#unit-conversion) stelt u in staat te kiezen in welke maateenheden u uw IFC wilt exporteren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/05-different-settings-in-the-export.png)

---

## 3. Modelfilter

### 3.1 Roosters in de IFC exporteren

Soms wilt u de roosters ook geëxporteerd hebben om ze in Catenda Hub te kunnen zien.

Ga naar het modelfilter voor IFC-export en zorg ervoor dat het selectievakje "Rastersysteem en elementen" is aangevinkt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/06-exporting-grids-in-the-ifc.png)

---

## 4. Type-toewijzing

Wanneer een IFC wordt geëxporteerd, krijgen alle elementen in het model een IFC-type toegewezen.

Als u de IFC-vertaler selecteert die u wilt gebruiken, kunt u naar type-toewijzing gaan en klikken op IFC-typen voor importeren toewijzen om te beheren wat voor soort type-toewijzing u op uw geëxporteerde IFC wilt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/07-2-type-mapping.png)

Type-toewijzing heeft hoofdzakelijk twee verschillende opties om uw IFC-typen op te sorteren.

### 4.1 Elementtype

Elk element krijgt automatisch een basis-IFC-type toegewezen. U kunt elk element\ het toegewezen IFC-type zien in projectmanager en in element-instellingen.

### 4.2 Classificatie

Deze methode maakt flexibelere en gedetailleerde IFC-type-toewijzing mogelijk, volgens specifieke classificatiestandaarden. Zone- en openingselementen krijgen een vast IFC-type. IFCSpace en IFCOpeningElements.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/08-classification.png)

---

## 5. Geometrieconversie

Geometrieconversie voor IFC-export stelt u in staat uw geometrie op verschillende manieren om te zetten.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/09-3-geometry-conversion.png)

### 5.1 Conversies van Archicad-elementen

**Alle modelelementen\ geometrie exporteren als:** _Parametrisch met uitzonderingen_ - standaard _BREP_ - Precieze geometrie - Als dit is geselecteerd, zullen de volgende twee opties ook BREP zijn

**Elementen in vaste elementbewerkingen:** _Extruded/revolved_ - standaard _BREP_ - Precieze geometrie

Elementen met juncties Sommige elementen kunnen elkaar kruisen, wat delen van de extrusie kan trimmen. _Extruded/revolved_ - Hoeken van elementen verbinden Dit voegt juncties toe aan uw extrudeerde elementen. Met deze optie zult u zien dat elementen zoals muren of daken, vooral schuin geplaatste, mooi aansluiten.

_Extruded/revolved zonder juncties_ - standaard - Dit maakt de export sneller Als u 90 graden elementen zoals muren of daken hebt, zult u waarschijnlijk geen verschil met deze opties opmerken. Als u schuin geplaatste muren hebt, zult u opmerken dat in de hoek waar de muren verbinden, in plaats van het trimmen van het overschot van de rechte extrusie, de muren rechtuit langs elkaar gaan en niet mooi verbinden.

_BREP_ - Precieze geometrie

Parametrische elementen Archicad-elementen kunnen als parametrische geometrie worden geëxporteerd, vaak in de vorm van richtlijnnen die tot een afstand worden extrudeerd. Parametrische geometrie maakt het gemakkelijk om het object na het maken ervan te bewerken. Hoewel deze optie bewerkbaarheid behoudt, kan de geometrie vaak enigszins onnauwkeurig zijn omdat de definitie een benadering van de geometrie is. Deze optie wordt aanbevolen als u van plan bent de IFC terug naar Archicad of een ander bewerkingsprogramma te importeren om verdere bewerkingen uit te voeren.

BREP Geometrie exporteren als aparte BREP-oppervlakken. In plaats van objecten op basis van hun parameters zoals lengte/breedte/hoogte met gegenereerde oppervlakken te beschrijven, wordt elk oppervlak beschreven als een afzonderlijk oppervlak met een locatie in 3D. Objecten kunnen nog steeds meerdere oppervlakken bevatten, maar deze zullen losse oppervlakken zijn. Na het exporteren moeten BREP-oppervlakken afzonderlijk worden bewerkt omdat parameters niet langer op het oppervlak worden toegepast. Met de BREP-optie worden exacte oppervlakken geëxporteerd, zonder ruimte voor verschil in interpretatie van parameters tussen authoringtools. Oppervlakken krijgen afzonderlijk een kleur en zullen dezelfde kleur hebben in Catenda Hub als in Archicad. Oppervlakkleuren kunnen in het volgende menu worden geconfigureerd:

`Opties -> Element-attributen -> Oppervlakken`

Het kan goed zijn om alle instellingen voor een oppervlak in te stellen, omdat deze in de IFC worden geschreven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/10-conversions-of-archicad-elements.png)

Oppervlakken in de Catenda 3D-viewer hebben platte arcering zonder lichtbron. Dit betekent dat waarden zoals Ambient, Attenuation, Shinyness, Emission en Specular niet worden geïnterpreteerd wanneer het oppervlak wordt bekeken in de Catenda 3D-viewer. De volgende waarden worden door Catenda geïnterpreteerd wanneer het oppervlak in de 3D-viewer wordt weergegeven:

Oppervlakkleur De kleur van het oppervlak

Doorlaatbaarheid Hoeveel u door het object kunt zien (overschrijft de translucente opaciteitsinstelling)

Diffuse Hoe donker of helder de oppervlakkleur is

**IFC-modelposition bepalen door:** Deze optie bepaalt projectlocatie. Het is belangrijk om al aan het begin afstand te spreken over een gemeenschappelijk coördinaatpunt waarnaar in het project moet worden verwezen, omdat wijziging ervan kan betekenen dat meerdere raadplegers hun objecten moeten verplaatsen, wat tegen het einde van een project vaak niet haalbaar is.

Surveypoint en projectoorsprong - standaard Met deze optie is de afstand van (0,0,0) tot uw model in Archicad gelijk aan de afstand van (0,0,0 + coördinaten van uw surveypoint) tot uw model in Catenda Hub + het als u een projectlocatie hebt ingesteld, komt uw model op die coördinaten in Catenda Hub terecht

Alleen projectoorsprong Met deze optie is de afstand van (0,0,0) tot uw model in Archicad gelijk aan de afstand van (0,0,0) tot uw model in Catenda Hub.

Alleen surveypoint Met deze optie is de afstand van het surveypoint in Archicad tot uw modellen gelijk aan de afstand van (0,0,0) tot uw model in Catenda Hub

### 5.2 IFC-schemaopties

**Materiaalbehoudsmode (alleen IFC2x3)** - Elementen nooit exploderen, behoud is niet gegarandeerd Met deze optie exporteert u het gehele object als één object

- Alleen exploderen indien nodig om materialen te behouden - Standaard
  Met deze optie exporteert u alleen afzonderlijke objecten voor elk composietmateriaal indien nodig

- Alle elementen in onderdelen exploderen, materialen behouden
  Met deze optie worden alle objecten als afzonderlijke objecten voor elk materiaal geëxporteerd

Als u een composiet wandmateriaal hebt, betekent dit dat voor elk materiaal een afzonderlijk object wordt geëxporteerd. U hebt vaak een dampdoorlatende laag van 1-5 mm, wat resulteert in een zeer dun object. Wanneer objecten zo dun zijn, kan de geometrie onnauwkeurig zijn. Problematische wandmaterialen kunnen er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/11-ifc-schema-related-options.png)

Dit kan het moeilijk maken voor software om gaten in het oppervlak te snijden, omdat de onnauwkeurigheid het lastig maakt om precies te bepalen waar het gat zou moeten zijn. Als u merkt dat uw openingen niet worden doorsneden, kan het helpen deze optie in te schakelen. Het inschakelen van deze optie exporteert de muur als één enkel object in plaats van veel dunne samengestelde objecten.

### 5.3 Samengestelde constructies en complexe profielen

**Complexe bouwonderdelen in onderdelen splitsen** Hier kunt u kiezen voor welk type elementen u het samengestelde element wilt splitsen en voor welke niet. Als u deze optie kiest, kunt u geen keuze maken voor de materiaalbehoudsmode.

---

## 6. Eigenschappentoewijzing

In eigenschappentoewijzing (Bestand > IFC > Interoperabiliteit > Eigenschappentoewijzing) kunt u kiezen welke versie van IFC u wilt exporteren. u hebt de standaard IFC2x3 en de standaard IFC4. U kunt ook psets toevoegen om met uw IFC te exporteren. Als u dit doet, moet u een duplicaat van het IFC-schema maken dat u kiest.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/12-4-property-mapping.png)

Nadat u een duplicaat van uw standaard-IFC hebt gemaakt, kunt u de eigenschappen die u wilt toevoegen aan deze nieuwe voorinstelling door het IFC-schema te selecteren en op _IFC-eigenschappen voor export toewijzen_ te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/13-4-property-mapping.png)

---

## 7. Gegevensconversie

Onder gegevensconversie selecteert u wat voor soort gegevens u naast geometrie uit uw IFC-export wilt. vink de selectievakjes aan van wat u wilt exporteren.

Elementparameters leest de Archicad-elementparameter en zet deze om naar IFC-hoeveelheden of IFC-eigenschappen. Afhankelijk van hun type. Door deze optie te kiezen, vergroot u aanzienlijk de bestandsgrootte.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/14-5-data-conversion.png)

IFC-basisgrootheden leest de parameters van grootte, oppervlakte en volume. Als u dit selectievakje niet aanvinkt, kan het lastig zijn uw IFC naar Catenda Hub te importeren.

## 8. Eenhedenconversie

Stel de lengte-, hoek-, oppervlakte-, volume-, valuta- en tijdeenheden in voor uw export.
