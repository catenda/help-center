# IFC Archicad exporteren handleiding

Houd bij het exporteren van een IFC rekening met wat relevant is voor je IFC-export. Het IFC-bestand kan groot zijn en moeilijk om mee te werken als er veel informatie in staat. Daarom is het belangrijk om geen onnodige informatie te exporteren. In dit rapport krijg je verschillende tips om je IFC-export in Archicad te filteren.

Dit artikel bevat informatie over de volgende onderwerpen

## 1. Projectinformatie

Voordat je een IFC van je project exporteert, moet je ervoor zorgen dat de projectinfo is geconfigureerd.

De project info kan hier gevonden worden:

`Bestand -> Info -> Project info`

Zo kan de project info eruit zien:

![](https://downloads.intercomcdn.com/i/o/areracg3/1836931119/c925f37fc292cccb9d4107147316/image.png?expires=1781092800&signature=0b33e6636409e0c7af0a87efe5da4bdbf512ce90156238fc021ccff08d8d7d99&req=dSgkEMB9nIBeUPMW3nq%2BgS%2FUIeMwWK1stokhyX7eRpqqUQMufFYF2Q7QdZpr%0AUjpkCYOiPTEqla620Ilf2CiWFhU%3D%0A)

Standaard zijn de verschillende velden leeg.

Ook al zijn ze leeg, er wordt een unieke id aangemaakt voor elk project, site en gebouw dat in de lijst staat.

In sommige situaties worden meerdere IFC-bestanden geëxporteerd vanuit hetzelfde Archicad-project.

Voorbeelden hiervan zijn:

IFC-bestanden met objecten uit verschillende vakgebieden.

Een MEP-model met leidingen, een architectuurmodel met wanden en een constructiemodel met alle platen.

Meerdere gebouwen

Soms worden meerdere gebouwen samen gemodelleerd binnen hetzelfde Archicad-bestand en wordt voor elk gebouw een aparte IFC geëxporteerd.

Verschillende ontwerpkeuzes.

Wanneer verschillende varianten van een gebouw worden gemodelleerd in hetzelfde Archicad-bestand, wordt elke variant vaak geëxporteerd naar een eigen IFC-bestand.

### 1.1 De projectinformatie configureren

Of er nu plannen zijn om meerdere IFC-bestanden te exporteren of niet, het is vaak een goed idee om waarden in te voeren in de projectinfo zodat deze later niet hoeven te worden gewijzigd.

De projectinfo is belangrijk om in te vullen omdat het effect heeft op de GUID's van het bestand.

Elk type IFC dat wordt geëxporteerd moet zijn eigen projectinstellingen hebben.

De projectinstellingen kunnen rechtsonder worden geïmporteerd en geëxporteerd.

Op deze manier kunnen meerdere profielen worden ondersteund voor de export van het bestand.

Voor Catenda is het belangrijk dat de IFC's in verschillende modellen verschillende informatie hebben terwijl IFC's die in hetzelfde model komen dezelfde informatie hebben.

## 2. IFC-export instellingen

Om het hele project te exporteren. U moet in 3D-weergave staan. Zorg ervoor dat u de juiste vertaler gebruikt.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056907/3ed1a2d39b9276705eca2953/image-0.png?expires=1781092800&signature=727a3898f989f68df24662a23ff14957bf59781f3bc27d84f57a5035967a4361&req=dicmFsx4lIFYFb4V1XW4gSsqFAIns%2BLVOCRTS1jsXxQqqssEUzUY2qHudMas%0AwiXzkKrZCxh05B46OxMksUBk8A%3D%3D%0A)

Klik op de knop Opties voor een overzicht van uw IFC-exportinstellingen. Onder model filter kunt u ook kiezen om meer uit te filteren.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056913/07e3a491c52e1af168324efe/image-1.png?expires=1781092800&signature=5003112051c8e8137b5bd8a0b7928b9d95227b2fe1f992494c057307472e3fe0&req=dicmFsx4lIBcFb4V1XW4gbS3lr63ymIv%2Bs4YYj8FOwEC8e03LRJ%2F1CBZuT%2F3%0A3q1TIGFHJXIvB8QkpSEHWMf08w%3D%3D%0A)

In het vak IFC translators kunt u de instellingen van Translators bekijken of wijzigen, of nieuwe Translators maken.

Als u uw IFC-export wilt aanpassen, is het aan te raden om een van de vooraf gemaakte vertalers te dupliceren, zodat u niet een van de standaardvertalers verknoeit. Dupliceer hier een vertaler:

Klik op nieuw > Dupliceren van > selecteer de vertaler die je wilt dupliceren.

Als je de IFC wilt samenvoegen kun je dat onder dezelfde banner doen.

![image-2.png](https://catenda-as.intercom-attachments-1.com/i/o/271056923/31605f86d13eb419fbb6b898/image-2.png?expires=1781092800&signature=a48f835dcf19dd3d20fafae1efca1ed8b731d7bbda7652f171b36ce73a05c3bb&req=dicmFsx4lINcFb4V1XW4gQA38htLLYIQOAE6xdxWgLSyC37l6Z8dKATf2fdr%0Ae0nMCShTSpN%2BRiDkcmZGbegXzQ%3D%3D%0A)

---

### 2.1 Verschillende instellingen in de export

1. Met [model filter](#h_138e653078) kun je filteren op wat je wilt exporteren aan de hand van verschillende voorinstellingen.

2. Met [Type mapping](#h_a34c1332a3) kun je kiezen als welk IFC-type elk element wordt geëxporteerd.

3. [Geometrieconversie](#h_db084b5d6b) laat u kiezen wat voor soort geometrie u wilt exporteren.

4. Met [Property mapping](#h_d48644eb35) kunt u criteria instellen op basis van types.

5. Met [gegevensconversie](#h_7f1df4ecb9) kunt u kiezen welke gegevens u wilt exporteren uit het model.

6. Met [eenheidsconversie](#h_36caead1cd) kunt u kiezen welke maateenheden u wilt exporteren in uw IFC.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056934/9c3eded88c73ec7e25ba4f4c/image-3.png?expires=1781092800&signature=4254158355f2ae65d52a4d2bf021496d0121849c85ee0ea279f94b6244161f56&req=dicmFsx4lIJbFb4V1XW4gfe0uzqiQldsKSXT2h%2FU0X1wYWMro6zFlyz8PDvw%0AQqWqqhwtmS%2BuEGqYeUXFypF0ZA%3D%3D%0A)

---

## 3. Model filter

### 3.1 Roosters exporteren in de IFC

Soms wil je de rasters ook geëxporteerd hebben om ze in Catenda Hub te kunnen zien.

Ga naar het model filter voor IFC Export en zorg ervoor dat het selectievakje "Grid system and Elements" is aangevinkt.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056967/a5906d5103e06c85f450f730/image-9.png?expires=1781092800&signature=3a57123c1e36ed368dda2ace93eedada56dfdcdf15dc0758d05956a4b252e149&req=dicmFsx4lIdYFb4V1XW4gdOixTR1uP%2BLnKVfHKCnuIne5TpHJDkHqYAkaNdU%0ASCC8qRvvbFCiGISg7JnUXeSwcw%3D%3D%0A)

---

## 4. Type mapping

Wanneer een IFC wordt geëxporteerd krijgen alle elementen in het model een IFC-type toegewezen.

Als u de IFC-vertaler selecteert die u wilt gebruiken, kunt u vervolgens naar Type mapping gaan en op Map IFC Types for import klikken om te beheren wat voor type mapping u wilt voor uw geëxporteerde IFC.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056940/57204561a8ccd3176e04d381/image-4.png?expires=1781092800&signature=8b2550d1949b9bcf2166050a67b0157d580cbf7308ffb90554f3424dd1d003dd&req=dicmFsx4lIVfFb4V1XW4gRT3Fi9%2FTyVfVfmhSH8DRamqc%2FFvbJuyRfAk7nhc%0AqQSucfuCAs4ih7jWnNIOcahFzg%3D%3D%0A)

Type mapping heeft voornamelijk verschillende opties om uw IFC-typen op te sorteren.

### 4.1 Type element

Aan elk element wordt automatisch een IFC-basistype toegewezen. U kunt het toegewezen IFC-type van elk element bekijken in de projectmanager en in de elementinstellingen.

### 4.2 Classificatie

Deze methode maakt een flexibelere en meer gedetailleerde toewijzing van IFC-typen mogelijk volgens specifieke classificatienormen. Zone- en openingselementen worden ingesteld op een vast IFC-type. IFCSpace en IFCOpeningElements.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056943/3731267714f7fa4930235354/image-5.png?expires=1781092800&signature=4ac137b61b9aaca454a4d031b64b1b3aaa697ae7457151121487d7eb18d4a218&req=dicmFsx4lIVcFb4V1XW4gaWRyW4wYZJh5THfO3CBEboYzzFw%2Fd1eDlkOJ%2FYT%0AeiJvrhqWfZiO2GWM0q56Mt8alg%3D%3D%0A)

---

## 5. Geometrieconversie

Met Geometry Conversion for IFC Export kunt u uw geometrie op verschillende manieren converteren.

![](https://downloads.intercomcdn.com/i/o/852256533/6acaa196d2acf7499d9aaafa/image.png?expires=1781092800&signature=477ab462c03abaca08a3a1bb95231c979a16c909f98d569a6e25e90855732436&req=fCUlFMx4mIJcFb4V1XW4gbFA7WWR17Jl6uaRn16tGKO80nJZcAqI0Q8myZSQ%0AUi30%2BZpM7YkT%2Bi5%2FWjhulkJmiA%3D%3D%0A)

### 5.1 Conversie van Archicad-elementen

**Exporteer de geometrie van alle modelelementen als:**

_Parametrisch met uitzonderingen_ - standaard

_BREP_ - Precieze geometrie - als deze optie is geselecteerd, zijn de volgende twee opties ook BREP

**Elementen in Solid Element Operations:**

_Extruded/revolved_ - standaard

_BREP_ - precieze geometrie

Elementen met kruisingen

Sommige elementen kunnen snijden met andere elementen die delen van de extrusie kunnen afsnijden.

_Extruded/revolved_ - Hoeken van elementen verbinden Dit voegt knooppunten toe aan je geëxtrudeerde elementen.

Met deze optie zul je zien dat elementen zoals muren of daken, vooral schuine, mooi zullen aansluiten.

_Extruded/revolved zonder verbindingen_ - standaard - Hierdoor verloopt het exporteren sneller

Als je elementen hebt met een hoek van 90 graden, zoals muren of daken, zul je waarschijnlijk geen verschil merken met deze optie. Als u schuine wanden hebt, zult u merken dat in de hoek waar de wanden op elkaar aansluiten, in plaats van het overschot van de rechte extrusie weg te snijden, de wanden gewoon recht langs elkaar gaan en niet mooi op elkaar aansluiten.

_BREP_ - Precieze geometrie

Parametrische elementen

Archicad elementen kunnen worden geëxporteerd als parametrische geometrie, vaak in de vorm van hulplijnen die op afstand worden geëxtrudeerd. Parametrische geometrie maakt het eenvoudig om het object te bewerken nadat het gemaakt is. Hoewel deze optie de bewerkbaarheid behoudt, kan de geometrie vaak wat onnauwkeurig zijn omdat de definitie een benadering is van de geometrie.

Deze optie wordt aanbevolen als u van plan bent de IFC terug te importeren in Archicad of een ander bewerkingsprogramma om verdere bewerkingen uit te voeren.

BREP Exporteer geometrie als afzonderlijke BREP-vlakken. In plaats van de objecten te beschrijven aan de hand van parameters zoals lengte/diepte/hoogte met surfaces als resultaat, wordt elk surface beschreven als een afzonderlijk surface met een locatie in 3D. Objecten kunnen nog steeds meerdere surfaces bevatten, maar dit zullen losse surfaces zijn. Na het exporteren van BREP moeten surfaces individueel worden bewerkt omdat parameters niet langer worden toegepast op de surface.

Met de BREP-optie worden exacte surfaces geëxporteerd, zodat er geen ruimte is voor verschillen in interpretatie van parameters tussen authoring tools.

Oppervlakken worden individueel gekleurd en zullen in Catenda Hub dezelfde kleur hebben als in Archicad.

Oppervlaktekleuren kunnen worden geconfigureerd in het volgende menu:

`Opties -> Element attributen -> Oppervlakken`

Het kan goed zijn om alle instellingen voor een surface te configureren omdat ze in de IFC worden geschreven.

![](https://downloads.intercomcdn.com/i/o/areracg3/1656700908/3bd28cde47ebdf76d515377ffdac/image.png?expires=1781092800&signature=a79042b2f4388244568ed5fc0b5591c6af0739ee814d8864881215920abc97d5&req=dSYiEM5%2BnYhfUfMW3nq%2BgUVMy2t5vk1CGatFRCfRSjmO%2FC38srSbEn9T1AdV%0AXvQXaA2M4J78l%2FW%2BbOgOVoSJo5s%3D%0A)

Oppervlakken in de Catenda 3D viewer hebben een vlakke arcering zonder dat er een lichtbron aanwezig is. Dit betekent dat waarden als Ambient, Attenuation, Shinyness, Emission en Specular niet worden geïnterpreteerd wanneer het oppervlak in de Catenda 3D viewer wordt bekeken. De volgende waarden worden door Catenda geïnterpreteerd wanneer het oppervlak in de 3D viewer wordt weergegeven:

Kleur oppervlak

De kleur van het oppervlak

Overbrenging

Hoeveel je door het object kunt zien (Overruled de doorschijnende opaciteit instelling)

Diffuus

Hoe donker of helder de kleur van het oppervlak is

**IFC-modelpositie definiëren door:**

Deze optie bepaalt de projectlocatie.

Het is belangrijk om al in het begin een gemeenschappelijk coördinaatpunt overeen te komen als referentiepunt voor het project, omdat dit kan betekenen dat meerdere consultants hun objecten moeten verplaatsen, wat tegen het einde van een project vaak niet haalbaar is.

Meetpunt en project oorsprong - standaard

Met deze optie is de afstand van (0,0,0) tot uw model in Archicad gelijk aan de afstand van (0,0,0 + coördinaten van uw meetpunt) tot uw model in Catenda Hub + de afstand van (0,0,0 + coördinaten van uw meetpunt) tot uw model in Catenda Hub

Als je een projectlocatie hebt ingesteld zal je model op die coördinaten in Catenda Hub terechtkomen

Alleen project oorsprong

Met deze optie wordt de afstand van (0,0,0) tot uw model in Archicad de afstand van (0,0,0) tot uw model in Catenda Hub.

Alleen landmeetpunt

Met deze optie wordt de afstand van het landmeetpunt in Archicad tot uw model gelijk aan de afstand van (0,0,0) tot uw model in Catenda Hub

### 5.2 IFC Schema gerelateerde opties

**Modus materiaalbehoud (alleen IFC2x3)**

- Explodeer nooit elementen, behoud is niet gegarandeerd

Met deze optie exporteer je het hele object als één object

- Explodeer alleen als het nodig is om materialen te behouden - Standaard

Met deze optie exporteert u alleen aparte objecten voor elk samengesteld materiaal indien nodig

- Explodeer alle elementen in delen, behoud materialen

Met deze optie worden alle objecten geëxporteerd als afzonderlijke objecten voor elk materiaal

Als je een samengesteld wandmateriaal hebt, betekent dit dat er voor elk materiaal een apart object wordt geëxporteerd.

Vaak heb je een dampscherm van 1-5 mm, wat resulteert in een zeer dun object.

Wanneer objecten zo dun zijn, kan de geometrie onnauwkeurig zijn.

Problematische wandmaterialen kunnen er ongeveer zo uitzien:

![](https://downloads.intercomcdn.com/i/o/1081851011/f299a5efe75792604e232f1e/image.png?expires=1781092800&signature=4e5bd2fc5b5a425217c5a10336a579578dbeb66300d566bb3a1904e44fbe7fd0&req=dSAvF8F7nIFeWPMW3nq%2BgQHJk%2FcTXuZhurrDgjjRlo8WQINdlX%2Fot4EpHXfb%0AHq%2B946vaAfTcPCXm3FcsVCYgn0E%3D%0A)

Dit kan het voor software moeilijk maken om gaten door het oppervlak te snijden, omdat de onnauwkeurigheid het moeilijk maakt om precies vast te stellen waar het gat moet komen.

Als je daarom merkt dat je openingen niet worden doorgesneden, kan het helpen om deze optie aan te zetten.

Als je deze optie inschakelt, wordt de wand geëxporteerd als één enkel object in plaats van vele dunne samengestelde objecten.

### 5.3 Samengestelde constructies en complexe profielen

**Complexe bouwelementen opsplitsen in delen**

Hier kun je kiezen voor welke type elementen je wilt dat het samengestelde element wordt opgesplitst en voor welke niet.

Als je deze optie kiest, kun je geen keuze maken voor de modus voor materiaalbehoud.

---

## 6. Eigenschappen toewijzen

Binnen property mapping (File > IFC > Interoperability > Property Mapping) kun je kiezen wat voor soort versie van IFC je wilt exporteren. je hebt de standaard IFC2x3 en de standaard IFC4. Je kunt ook psets toevoegen om te exporteren met je IFC. Als u dit doet, moet u een duplicaat maken van het IFC-schema dat u kiest.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056948/23de75ed67ebb8120f9ef63d/image-6.png?expires=1781092800&signature=2314c41343dba2f942862c4fb165cc070dcfa98658050e223df6a2fe8cecd606&req=dicmFsx4lIVXFb4V1XW4gX0eUSHQutujQy5PjUI1pttrN6jFy0gn5Wmw5l2r%0AvnVe595gd%2F5OcH05ksfM1MFdjA%3D%3D%0A)

Nadat je een duplicaat hebt gemaakt van je standaard IFC kun je de gewenste eigenschappen toevoegen aan die nieuwe preset door het IFC schema te selecteren en te klikken op _Map IFC Properties for Export_.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056955/8fd00cf142ae8d45a0fb7df1/image-7.png?expires=1781092800&signature=e66c9d5f53bbfae153da829dffb45bc582bc112cc3198628772d8798ecf6aabf&req=dicmFsx4lIRaFb4V1XW4gct4hmNJw3Cxmyiu4iXSGkjI8COu4X1sCPk6Gl1D%0AoF5KclTEvV0MOwQ%2BOYYH9OHrDw%3D%3D%0A)

---

## 7. Gegevensconversie

Onder gegevensconversie selecteert u wat voor soort gegevens naast geometrie u uit uw IFC-export wilt halen. vink de vakjes aan van wat u wilt exporteren.

Element parameters leest de Archicad elementparameter en converteert deze naar IFC grootheden of IFC eigenschappen. Afhankelijk van hun type. Door deze optie te kiezen neemt de bestandsgrootte aanzienlijk toe.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056963/bf0e775372c6fc6418e2727a/image-8.png?expires=1781092800&signature=7ae773823614711d50cdd4f7780fab8d8cc35ab2e7acad5a5c0474d4a31c0b92&req=dicmFsx4lIdcFb4V1XW4geoCNQZckbiMZP52Jc8%2BroBx3DCAZ7qhaLrtGOkQ%0AFPsbhSQya9mPEkHsU%2FfnXUXAaA%3D%3D%0A)

IFC Base Quantities leest de parameters van grootte, oppervlakte en volume. Als je dit vakje niet aanvinkt kan het zijn dat je problemen krijgt met het importeren van je IFC in Catenda Hub.

## 8. Eenheid Conversie

Stel de eenheden Lengte, Hoek, Oppervlakte, Volume, Valuta en Tijd in voor je export.
