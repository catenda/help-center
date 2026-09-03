# Revit IFC Export Handleiding

Met deze IFC export handleiding is het doel de gebruiker een gids te geven over hoe je de IFC voor de juiste doeleinden exporteert. Een IFC-bestand kan snel zwaar en groot worden wanneer je veel informatie uit het model wilt halen. Daarom moet je bij het exporteren van een IFC onnodige informatie uitschakelen. Bij het uploaden van een model naar Catenda is het niet altijd nodig om veel informatie en een hoog detailniveau in het model te hebben. Later in deze handleiding zullen we terugkomen op welke instellingen we aanraden om het model kleiner en gemakkelijker in het gebruik te maken. Hier zullen we stap voor stap de meest geschikte manier doorlopen om een IFC van Revit naar Catenda te exporteren.

## 1. **Projectinstellingen**

Voordat u exporteert, is het belangrijk om ervoor te zorgen dat de GUID's van uw Revit-project correct zijn.

`Beheren -> Instellingen -> Projectinformatie -> IFC-parameters`

![Projectinformatie IFC-parameters IfcSite GUID IfcBuilding GUID IfcProject GUID](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/01-project-settings.png)

Als de GUID anders is dan een vorige export, worden de objecten van nieuwere exports niet correct gekoppeld aan de GUID's in BCF-onderwerpen. Wanneer u een nieuw project maakt, krijgt het een unieke id.

## 2. **IFC export wijzigen**

Wanneer Revit open is en u klaar bent om te exporteren, kunt u het volgende doen.

![Linksboven in het scherm op Bestand drukken](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/02-modify-ifc-export.png)

Linksboven vinden we het tabblad "Bestand".

---

> **Onthoud:** _U wilt mogelijk een speciale map voor uw IFC's hebben, zodat u altijd controle hebt over waar uw bestand zich bevindt!_

Het IFC-exportmenu vindt u hier:

`Bestand -> Exporteren -> IFC`

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/03-modify-ifc-export.png)

Dit is hoe het IFC-exportmenu er uit kan zien:

![IFC exporteren](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/04-modify-ifc-export.png)

Bestandsnaam: Voer de naam en locatie in die het geëxporteerde bestand in het systeem zal hebben

Exportsetup Kies uit de volgende vooraf gedefinieerde setups: <In-Session Setup> IFC 2x3 Coördinatieweergave 2.0 IFC 2x3 Coördinatieweergave IFC 2x3 GSA Concept Design BIM 2010 IFC 2x3 Basic FM Handover View IFC 2x3 Coördinatieweergave IFC 2x3 COBie 2.4 Design Deliverable View IFC4 Reference View [Architectuur] IFC4 Reference View [Structureel] IFC4 Reference View [BuildingService] IFC4 Reference View [Informeel] IFC4x3 IFC-SG Regulatory Requirements View

Wanneer de Catenda Plugin voor Revit wordt gebruikt, wordt een extra vooraf gedefinieerde exportsetup voor gebruik met Catenda aan de lijst met opties toegevoegd.

## 3. **Setup wijzigen**

Klik op Setup wijzigen in het exportsetup-gedeelte van de dialoog IFC exporteren. Dit is waar de nodige instellingen voor IFC-exports kunnen worden gewijzigd en aangepaste setups kunnen worden gemaakt. Dit is hoe het menu Setup wijzigen er uit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/05-modify-setup.png)

Dit venster bevat de volgende tabbladen:

---

### 3.1 **Algemeen**

![Algemeen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/06-general.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/07-general.png)

We zullen u door de verschillende instellingen leiden.

**IFC-versie** Selectie van IFC-versie.

**Uitwisselingsvereiste** Deze opties kunnen veranderen, afhankelijk van de geselecteerde IFC-versie. IFC 2x3 Coördinatieweergave 2.0

- Architectuur-referentie-uitwisseling
- MEP-referentie-uitwisseling
- Structurele referentie-uitwisseling

**Categoriemapping** Vóór Revit 2026 was deze optie beschikbaar in Bestand -> Exporteren -> Opties -> IFC-exportopties. Dit is hoe het menu Instellingen voor IFC-exportmapping beheren er uit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/08-general.png)

**Bestandstype** IFC-typeselectie.

**Fase om te exporteren** Als u het fasetool in Revit hebt gebruikt, kunt u hier kiezen en alleen nieuwe of bestaande structuren exporteren.

**Ruimtegrenzen** Dit gaat allemaal over hoe ruimteinformatie verder kan worden gebruikt. a. 1e niveau - Voorbeeld van gebruik: Hoeveelheidontrekking, beheer, exploitatie en onderhoud (FDVU). b. 2e niveau - Voorbeeld van gebruik: Energieanalyse, lichtanalyse.

**Faciliteitstype** Deze optie is alleen beschikbaar voor IFC 4x3 Kies uit een van de volgende: Brug (IfcBridge) Gebouw (IfcBuilding) Mariene Faciliteit (IfcMarineFacility) Spoorweg (IfcRailway) Weg (IfcRoad)

**Muren, kolommen, kanalen per niveau splitsen** Hier kunt u bijvoorbeeld scheidingswanden horizontaal verdelen als deze over meerdere verdiepingen zijn gemodelleerd.

_Bestandskoppelinginformatie... Projectadres..._ Hierin kunt u informatie plaatsen over wie de IFC heeft geleverd, projectadres enz.

**Projectoorsprong** Projectoorsprong, dit plaatsen we op Huidige gedeelde coördinaten - Huidige gedeelde coördinaten.

> **Opmerking:** Dit is verplaatst naar Geografische referentie vanaf Revit 2025

**Stalen elementen opnemen** Omvat stalen componenten als deze zijn gemodelleerd.

> **Opmerking:** Dit is verplaatst naar Aanvullende inhoud vanaf Revit 2025

---

### 3.2 **Aanvullende inhoud**

![Aanvullende inhoud](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/09-additional-content.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/10-additional-content.png)

Gekoppelde bestanden als afzonderlijke IFC's exporteren Als u de gekoppelde bestanden in de IFC wilt opnemen, kunt u deze optie inschakelen. Het wordt aanbevolen dat u elk bestand afzonderlijk exporteert en elk naar uw eigen model importeert.

Alleen zichtbare objecten in IFC-bestand exporteren die in weergave zichtbaar zijn.

- Kamers, gebieden en ruimten in 3D-weergaven exporteren
  Deze optie kan nuttig zijn voor het selecteren van gebieden in de 2D-viewer.

Stalen elementen opnemen, _ingevuld_

2D-plattegrondweergaveelementen exporteren, _ingevuld, regio's_ (krassen).

Plafondtralie exporteren Plafondtralie zijn 2D-elementen en worden daarom niet weergegeven in de Catenda 3D-viewer.

---

### 3.3 **Eigenschappensets**

![Eigenschappensets](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/11-property-sets.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/12-property-sets.png)

Exporteert alle Revit Eigenschappensets (pset / eigenschappen) Hier is een voorbeeld van een muur die met deze optie is geëxporteerd: Revit (_Links_) --- Catenda (_Rechts_)

<img alt="Eigenschappen" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-4f4aab46be4e.png" width="208.60495436766624"/>  ---  <img alt="Eigenschappen" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-7c05fd3c2c4a.png" width="190.21739130434784"/>

Typische eigenschappen die in het eigenschappenmenu verschijnen, zijn: Beperkingen, Definitie van dwarsdoorsnede, Afmetingen, Structureel, Identiteitsgegevens, Overige

Typische eigenschappen die in het menu Identificatie verschijnen, zijn: IFC-parameters Standaard IFC-eigenschappen exporteren. Exporteert berekende hoeveelheden van objecten. Batchlijsten exporteren Eenmalige eigenschappenset exporteren

**Instellingen voor classificatie** Hier is een voorbeeld van hoe classificatie-instellingen er uit kunnen zien met omniclass.

![Classificatie-instellingen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/13-property-sets.png)

**Naam** De naam van de classificatie

**Bron (Uitgever)** De uitgever van de classificatie

**Editie** De classificatie-editie

**Uitgiftedatum** De datum van de classificatie

**Documentatielocatie** Dit moet een geldige documentatielocatie zijn

**Classificatieveldnaam** De classificatieveldnaam is de naam van de parameter in uw objecten die de classificatiewaarde bevat. Deze parameter is vaak op familieniveau te vinden. Bewerk een familie om de eigenschappen ervan te zien

![Familie bewerken](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/14-property-sets.png)

Dit is hoe de parameter er in de eigenschappen uit kan zien

![Eigenschappen OmniClass-nummer](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/15-property-sets.png)

Als u uw ifc met een classificatie hebt geëxporteerd en het als model naar Catenda hebt geïmporteerd, ziet u de classificatie als een [voorgestelde bibliotheek](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca) wanneer u een nieuwe bibliotheek op de [bibliotheekpagina](https://support.catenda.com/en/articles/8065645-libraries-page) aanmaakt. Als een waarde in de eigenschap die u hebt opgegeven, overeenkomt met een waarde in de verstrekte documentatie, wordt deze gevonden en kan deze worden gebruikt om objecten met deze waarde in de classificatiebibliotheken die u hebt gemaakt, te selecteren.

---

### 3.4 **Detailniveau**

![Detailniveau](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/16-level-of-detail.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/17-level-of-detail.png)

Dit gaat over hoe gedetailleerd we bijvoorbeeld hebben. kopjes of leuningen of misschien fietswheels. Er zijn 4 verschillende detailniveaus.

Extra laag Laag Gemiddeld Hoog

Wanneer hoog, wordt het het meest gedetailleerd zoals weergegeven in de afbeelding hieronder.

![Detailniveau extra laag en hoog](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/18-level-of-detail.png)

---

Bij het exporteren van IFC's van Revit voor gebruik in Catenda Hub, raden we aan het detailniveau niet op hoog in te stellen. Er zullen veel details en extra polygonen in modellen zijn wanneer ze met een hoger detailniveau worden geëxporteerd en dit is niet altijd nodig en maakt de modelnavigatie langzamer. Dit is een voorbeeld van het verschil tussen exporteren met de instellingen Extra laag en Hoog.

![Dit is een trapborstwering geëxporteerd met de instelling Hoog. 900k polygonen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/19-level-of-detail.png)

![Dit is hetzelfde model geëxporteerd met de instelling Extra laag. 33k polygonen.](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/20-level-of-detail.png)

Het uiterlijk van het model zal vrijwel hetzelfde zijn, maar het aantal polygonen zal drastisch afnemen en de navigatie in Catenda Hub zal veel sneller zijn.

---

### 3.5 **Geavanceerd**

![Geavanceerd](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/21-advanced.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/22-advanced.png)

**Onderdelen als buildingelementen exporteren** Onderdelen exporteren zoals standaard IFC-element.

**Gebruik van gemengde "Solid Model"-representatie toestaan** Selecteer deze optie om menging van BRep- en extrusiegerometrie voor een eenheid toe te staan.

**Actieve weergave gebruiken bij het maken van geometrie** Selecteer deze optie om de actieve weergave te gebruiken voor het genereren van de geometrie. Houd er rekening mee dat dit onverwachte resultaten kan opleveren bij gebruik van een niet-3D-weergave.

**Familie- en typenaam gebruiken voor referentie** Selecteer deze optie om de familie- en typenamen voor referenties te gebruiken.

**2D-ruimtegrenzen gebruiken voor ruimtevolume** Selecteer deze optie om een vereenvoudigde benadering voor het berekenen van het ruimtevolume te gebruiken (gebaseerd op extrusion van 2D-ruimtegrenzen), wat ook standaard is bij export naar IFC 2x2.

**IFCSite-verhoging in de lokale plaatsingsoorsprong van de locatie opnemen** Selecteer deze optie om de hoogte van de Z-offset voor lokale positie in IfcSite op te nemen. Verwijder de optie om deze uit te sluiten.

**IFC GUID in een elementparameter opslaan na export** Selecteer deze optie om de gegenereerde IFC GUID's na export in het projectbestand op te slaan. Dit voegt "IFC GUID"-parameters toe aan items en hun typen en Projectinformatie voor project, website en building guides.

**Begrenzingsvak exporteren** Selecteer deze optie om "Begrenzingsvak"-representaties te exporteren. Deze optie blijft automatisch geselecteerd voor GSA-export.

**Tesselleerde geometrie behouden als triangulatie** Als u complexe gebogen elementen of shells hebt en deze niet correct worden weergegeven na de IFC-export, kunt u deze optie selecteren. Houd er rekening mee dat u mogelijk een zeer zwaar IFC-bestand produceert.

**Alleen typenaam gebruiken voor IFCType-naam** Selecteer deze optie als u wilt dat de BAT-ID of de ID van het object als de naam van de entiteit wordt weergegeven.

**Zichtbare Revit-naam gebruiken als IFCEntity-naam** Selecteer deze optie als u wilt dat de Revit-objectnaam de naam van de entiteit is

**Altijd gefacetteerde vloeren en daken als één IFC-entiteit exporteren** Selecteer deze optie om vlakken van vloeren en daken met meerdere vlakken in één entiteit te combineren.

**"Laatst gewijzigd"-gebruiker instellen op de auteur in Projectinformatie** Selecteer deze optie als u de auteur bent van de wijzigingen in deze export

**Te exporteren entiteiten** Dit is hoe het IFC-Entity-selectiemenu dat opent er uit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/23-advanced.png)

---

### 3.6 **Geografische referentie**

Het is belangrijk dat uw Revit-coördinaten zijn gesynchroniseerd met de andere modellen in uw project, zodat ze op dezelfde plaats uitkomen. Daarom meet u de coördinaten in Catenda Hub met een puntmeting en specificeert u een coördinatenbasis in Revit op een punt dat op dezelfde plaats ligt als het gemeten punt in Catenda Hub.

![Coördinaten op punt opgeven](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/24-geographic-reference.png)

U kunt deze optie vinden in het tabblad Beheren -> Coördinaten -> Coördinatenbasis opgeven. _Coördinaten op punt opgeven_ Verplaatst een model en roteert het model naar Ware Noorden door coördinaten voor Noord/Zuid, Oost/West en Verhoging op te geven. In Revit is het vaak gemakkelijker om op 90 gradenhoeken te modelleren en wil je het hele model niet roteren. In dit geval kunt u in plaats daarvan Ware Noorden roteren. U vindt de optie in de dropdown Positie onder Coördinaten in het tabblad Beheren.

![Geografische referentie](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/25-geographic-reference.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/26-geographic-reference.png)

**Projectlocatie** Intern

**Coördinatenbasis** U kunt deze instelling wijzigen om ervoor te zorgen dat uw project naar het Noorden is gericht Gedeelde coördinaten - Standaard onderzoekspunt Projectbasispoint Interne oorsprong Projectbasispoint gericht naar ware Noorden Interne oorsprong gericht naar ware Noorden

> **Opmerking:** Als u IFC in het tabblad Invoegen koppelt, wordt uw gekoppelde bestand dicht bij uw objecten geplaatst en bevindt het zich niet op de locatie die in de IFC is beschreven. Als u een IFC naar de juiste locatie wilt importeren, klikt u op Bestand -> Openen -> IFC.

**Negeer** Hier kunt u het geprojecteerde Coordinate System Reference negeren

---

### 3.7 **Bedrijfsgegevens**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/27-company-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/28-company-info.png)

Dit menu is alleen beschikbaar wanneer de exportsetup IFC2x3 COBie 2.4 Design Deliverable View in het linkermenu is geselecteerd.

---

### 3.8 **Projectinfo**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/29-project-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/30-project-info.png)

Dit menu is alleen beschikbaar wanneer de exportsetup IFC2x3 COBie 2.4 Design Deliverable View in het linkermenu is geselecteerd.

---

## 4. **IFC-opties**

De IFC-opties van een Revit-project vindt u in:

`Bestand -> Exporteren -> Opties -> IFC-opties`

![Exporteren -> Opties -> IFC-opties](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/31-ifc-options.png)

> **Opmerking:** Vanaf Revit 2026 is deze optie nu beschikbaar in: `Exporteren -> IFC -> Algemeen -> Categoriemapping -> Actiemenu rechts van dropdown`

Hier in de _IFC-opties_ maken we de instellingen voor het exporteren van een model naar een IFC-bestand. Hier kunt u setup-eigenschappen aanpassen voor het exporteren van een model naar IFC. Wat aan het begin van deze handleiding werd genoemd, is dat het niet nodig is om te veel informatie uit het model te halen. Voel je vrij om onnodige informatie voor export uit te schakelen.

![IFC-exportklassen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/32-ifc-options.png)

Het is mogelijk om rasters in Catenda Hub weer te geven, en als u deze in uw Revit-model hebt, kunt u in IFC-opties rasters instellen om te worden geëxporteerd in de IFC. Deze worden standaard niet uit Revit geëxporteerd.

## 5. **Kleuren en materialen**

De kleuren die in Catenda worden weergegeven, worden uit het IFC-bestand gelezen dat wordt geïmporteerd. Wanneer de materiaaleigenschap van een familie wordt toegevoegd aan de IFC-parameters, wordt de kleur van het materiaal in de materiaaleigenschap aan de IFC toegevoegd en dus in Catenda weergegeven. In Revit zijn materialen te vinden in de materialenbrowser:

`Tabblad Beheren -> Sectie Instellingen -> Materialen`
In de Materialenbrowser vindt u de instelling voor kleur in het tabblad Grafische afbeelding van het materiaal:

![Beheren -> Materialen -> Materialenbrowser -> Nieuw materiaal maken](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/33-colors-and-materials.png)

Het is ook mogelijk om de arcering aan de renderinginstellingen vast te zetten.

![Uiterlijk](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/34-colors-and-materials.png)

Oppervlakken in de Catenda 3D-viewer hebben vlakke arcering zonder een aanwezige lichtbron. De volgende waarden worden door Catenda geïnterpreteerd bij het weergeven van het oppervlak in de 3D-viewer:

Algemeen

- Kleur
- Afbeelding vervagen

Transparantie

- Hoeveelheid
- Afbeelding vervagen
- Doorzichtigheid

Tint kleur

- Tintkleur
