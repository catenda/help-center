# Revit IFC Export Handleiding

Met deze IFC export handleiding is het doel om de gebruiker een gids te geven over hoe je de IFC voor de juiste doeleinden exporteert. Een IFC-bestand kan snel zwaar en groot worden als je veel informatie uit het model moet halen. Daarom moet je bij het exporteren van een IFC onnodige informatie uitvinken. Bij het uploaden van een model naar Catenda is het niet altijd nodig om veel informatie en een hoog detailniveau in het model te hebben. Later in deze handleiding komen we terug op welke instellingen we aanbevelen om het model iets kleiner en iets gemakkelijker te maken om mee te werken. Hier gaan we stap voor stap de meest geschikte manier door om een IFC van Revit naar Catenda te exporteren.

## 1. **Projectinstellingen**

Voordat u exporteert, is het belangrijk om ervoor te zorgen dat de GUID's van uw Revit-project correct zijn.

`Beheren -> Instellingen -> Projectinformatie -> IFC-parameters`

![Projectinformatie IFC-parameters IfcSite GUID IfcBuilding GUID IfcProject GUID](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/01-project-settings.png)

Als de GUID afwijkt van een vorige export, worden de objecten van nieuwere exports niet correct gekoppeld aan de GUID's in BCF-onderwerpen. Wanneer u een nieuw project maakt, krijgt het een unieke id.

## 2. **IFC export wijzigen**

Wanneer Revit open is en je klaar bent om te exporteren, wil je mogelijk het volgende doen.

![Klik op het bestand linksboven op het scherm](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/02-modify-ifc-export.png)

Linksboven vinden we het tabblad "Bestand".

---

> **Onthoud:** _U wilt mogelijk een speciale map voor uw IFC's hebben, zodat u altijd controle hebt over waar uw bestand zich bevindt!_

Het IFC-exportmenu is hier te vinden:

`Bestand -> Exporteren -> IFC`

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/03-modify-ifc-export.png)

Zo kan het menu IFC exporteren eruitzien:

![IFC exporteren](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/04-modify-ifc-export.png)

Bestandsnaam Voer de naam en locatie in die het geëxporteerde bestand in het systeem zal hebben

Exportinstelling Kies uit de volgende vooraf gedefinieerde instellingen: \<In-Session Setup> IFC 2x3 Coordination View 2.0 IFC 2x3 Coordination View IFC 2x3 GSA Concept Design BIM 2010 IFC 2x3 Basic FM Handover View IFC 2x3 Coordination View IFC 2x3 COBie 2.4 Design Deliverable View IFC4 Reference View [Architecture] IFC4 Reference View [Structural] IFC4 Reference View [BuildingService] IFC4 Reference View [Unofficial] IFC4x3 IFC-SG Regulatory Requirements View

Wanneer de Catenda Plugin voor Revit wordt gebruikt, wordt een extra vooraf gedefinieerde exportinstelling voor gebruik met Catenda aan de lijst met opties toegevoegd.

## 3. **Instellingen wijzigen**

Klik op Instellingen wijzigen in het gedeelte exportinstelling van het dialoogvenster IFC exporteren. Dit is waar de noodzakelijke instellingen voor IFC-exports kunnen worden gewijzigd en aangepaste instellingen kunnen worden gemaakt. Dit is hoe het menu instellingen wijzigen eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/05-modify-setup.png)

Dit venster bevat de volgende tabbladen:

---

### 3.1 **Algemeen**

![Algemeen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/06-general.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/07-general.png)

We gaan u door de verschillende instellingen heen.

**IFC-versie** Selectie van IFC-versie.

**Uitwisselingsvereiste** Deze opties kunnen veranderen, afhankelijk van de geselecteerde IFC-versie. IFC 2x3 Coordination View 2.0

- Architectural Reference Exchange
- MEP Reference Exchange
- Structural Reference Exchange

**Categoriemapping** Voor Revit 2026 was deze optie beschikbaar in Bestand -> Exporteren -> Opties -> IFC-exportopties. Dit is hoe het menu IFC-exportinstellingen beheren eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/08-general.png)

**Bestandstype** IFC-typeselectie.

**Fase om te exporteren** Als u het fasetool in Revit hebt gebruikt, kunt u hier kiezen en alleen nieuwe of bestaande structuren exporteren.

**Ruimtegrenzen** Dit gaat allemaal over hoe ruminformatie verder kan worden gebruikt. a. 1e niveau - Voorbeeld van gebruik: Hoeveelheidsopnames, beheer, exploitatie en onderhoud (FDVU). b. 2e niveau - Voorbeeld van gebruik: Energieanalyse, lichtanalyse.

**Type faciliteit** Deze optie is alleen beschikbaar voor IFC 4x3 Kies uit één van de volgende: Brug (IfcBridge) Gebouw (IfcBuilding) Maritieme faciliteit (IfcMarineFacility) Spoorlijn (IfcRailway) Weg (IfcRoad)

**Wanden, kolommen, kanalen per niveau splitsen** Hier kunt u b.v. scheidingswanden horizontaal verdelen als ze over meerdere verdiepingen zijn gemodelleerd.

_Informatie in bestandskop... Projectadres..._ Hier kunt u informatie invoeren over wie de IFC heeft geleverd, projectadres enz.

**Projectoorsprong** Projectoorsprong, deze zetten we op Huidige gedeelde coördinaten- Huidige gedeelde coördinaten.

> **Opmerking:** Dit is verplaatst naar Geografische verwijzing vanaf Revit 2025

**Stalen elementen opnemen** Bevat stalen onderdelen indien gemodelleerd.

> **Opmerking:** Dit is verplaatst naar Aanvullende inhoud vanaf Revit 2025

---

### 3.2 **Aanvullende inhoud**

![Aanvullende inhoud](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/09-additional-content.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/10-additional-content.png)

Gekoppelde bestanden als afzonderlijke IFC's exporteren Als u de gekoppelde bestanden in de IFC wilt opnemen, kunt u deze optie inschakelen. Het wordt aanbevolen dat u elk bestand afzonderlijk exporteert en elk naar hun eigen model importeert.

Alleen zichtbare objecten exporteren Zichtbaar in weergave IFC-bestand.

- Kamers, gebieden en ruimten exporteren in 3D-weergaven
  Deze optie kan nuttig zijn voor het selecteren van gebieden in de 2D-viewer.

Stalen elementen opnemen, _ingevuld_

Exporteert 2D-planelementen, _ingevuld, regio's_ (krassen).

Plafondroostrs exporteren Plafondroostrs zijn 2D-elementen en worden daarom niet weergegeven in de Catenda 3D-viewer.

---

### 3.3 **Eigenschappensets**

![Eigenschappensets](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/11-property-sets.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/12-property-sets.png)

Exporteert alle Revit-eigenschappensets (pset / eigenschappen) Hier is een voorbeeld van een muur die met deze optie is geëxporteerd: Revit (_Links_) --- Catenda (_Rechts_)

<img alt="Eigenschappen" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-4f4aab46be4e.png" width="208.60495436766624"/>  ---  <img alt="Eigenschappen" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-7c05fd3c2c4a.png" width="190.21739130434784"/>

Typische eigenschappen die in het eigenschappenmenu worden weergegeven zijn: Beperkingen, Doorsnedebeschrijving, Dimensies, Structureel, Identiteitsgegevens, Overige

Typische eigenschappen die in het menu Identificatie worden weergegeven zijn: IFC-parameters Standaard IFC-eigenschappen exporteren. Exporteert berekende hoeveelheden van objecten. Exporteerlijsten batchen Exporteert eenmalige eigenschappenverzameling

**Classificatie-instellingen** Hier is een voorbeeld van hoe classificatie-instellingen er met omniclass uit kunnen zien.

![Classificatie-instellingen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/13-property-sets.png)

**Naam** De naam van de classificatie

**Bron (Uitgever)** De uitgever van de classificatie

**Editie** De classificatie-editie

**Editiedatum** De datum van de classificatie

**Documentatielocatie** Dit moet een geldige documentatielocatie zijn

**Classificatieveldnaam** De classificatieveldnaam is de naam van de parameter in uw objecten die de classificatiewaarde bevat. Deze parameter is vaak te vinden op familieniveau. Bewerk een familie om de eigenschappen ervan te zien

![Familie bewerken](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/14-property-sets.png)

Dit is hoe de parameter in de eigenschappen kan uitzien

![Eigenschappen OmniClass-nummer](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/15-property-sets.png)

Als u uw ifc met een classificatie hebt geëxporteerd en als model naar Catenda hebt geïmporteerd, ziet u de bijbehorende classificatie voorgesteld als een [voorgestelde bibliotheek](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca) bij het maken van een nieuwe bibliotheek op de [bibliothekenpagina](https://support.catenda.com/en/articles/8065645-libraries-page). Als een waarde in de eigenschap die u hebt opgegeven overeenkomt met een waarde in de verstrekte documentatie, wordt deze gevonden en kan deze worden gebruikt om objecten met deze waarde te selecteren via de bibliotheek voor classificatie die u hebt gemaakt.

---

### 3.4 **Detailniveau**

![Detailniveau](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/16-level-of-detail.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/17-level-of-detail.png)

Dit gaat over hoe gedetailleerd we hebben, bijvoorbeeld. kopjes of leuningen of misschien fietswiel. Er zijn 4 verschillende detailniveaus.

Extra laag Laag Gemiddeld Hoog

Als hoog ingesteld, wordt het meest gedetailleerd weergegeven zoals in de onderstaande afbeelding.

![Detailniveau extra laag en hoog](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/18-level-of-detail.png)

---

Bij het exporteren van IFC's van Revit voor gebruik in Catenda Hub, raden we aan het detailniveau niet op hoog in te stellen. Er zijn veel details en extra polygonen in modellen bij export met een hoger detailniveau en dit is niet altijd nodig en zal de modelnavigatie langzamer maken. Dit is een voorbeeld van het verschil tussen exporteren met de instelling Extra laag en Hoog.

![Dit is een trapuitzetting die is geëxporteerd met de instelling Hoog. 900k polygonen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/19-level-of-detail.png)

![Dit is hetzelfde model geëxporteerd met de instelling Extra laag. 33k polygonen.](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/20-level-of-detail.png)

Het uiterlijk van het model zal bijna hetzelfde zijn, maar het aantal polygonen zal drastisch afnemen en de navigatie in Catenda Hub zal veel sneller zijn.

---

### 3.5 **Geavanceerd**

![Geavanceerd](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/21-advanced.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/22-advanced.png)

**Onderdelen als bouwkundig elementen exporteren** Exporteer onderdelen als standaard IFC-element.

**Gebruik van gemengde "Solid Model"-weergave toestaan** Selecteer deze optie om mengselvorming van BRep- en extrusiegeometrie voor een eenheid toe te staan.

**Actieve weergave gebruiken bij het maken van geometrie** Selecteer deze optie om de actieve weergave te gebruiken voor het genereren van geometrie. Houd er rekening mee dat dit onverwachte resultaten kan opleveren als het op een niet-3D-weergave wordt gebruikt.

**Familie- en typenaam gebruiken voor verwijzing** Selecteer deze optie om de familie- en typenamen voor verwijzingen te gebruiken.

**2D-ruimtegrenzen gebruiken voor ruimtevolume** Selecteer deze optie om een vereenvoudigde benadering te gebruiken voor het berekenen van het ruimtevolume (op basis van extrusie van 2D-ruimtegrenzen), wat ook standaard is bij export naar IFC 2x2.

**IfcSite-hoogte in de lokale plaatsingsoorsprong opnemen** Selecteer deze optie om de hoogte van de Z-verschuiving voor lokale positie in IfcSite op te nemen. Verwijder de optie om het uit te sluiten.

**IFC GUID opslaan in een elementparameter na export** Selecteer deze optie om de gegenereerde IFC GUID's na export naar het projectbestand op te slaan. Dit voegt "IFC GUID"-parameters toe aan items en hun typen en projectinformatie voor project-, website- en bouwgidsen.

**Begrenzingsvak exporteren** Selecteer deze optie om "Begrenzingsvak"-weergaven te exporteren. Deze optie blijft automatisch geselecteerd voor GSA-export.

**Geteseleerde geometrie als driehoeksmeting houden** Als u complexe gekromde elementen of schelpen hebt en deze na de IFC-export niet correct worden weergegeven, kunt u deze optie selecteren. Houd er rekening mee dat u een zeer zwaar IFC-bestand kunt produceren.

**Alleen typenaam voor IFCType-naam gebruiken** Selecteer deze optie als u wilt dat de BAT-ID of ID van het object als naam van de entiteit verschijnt.

**Zichtbare Revit-naam als IFC-entiteitnaam gebruiken** Selecteer deze optie als u wilt dat de Revit-objectnaam de naam van de entiteit is

**Altijd gefacetteerde vloeren en daken als één IFC-entiteit exporteren** Selecteer deze optie om vlakken van vloeren en daken met meerdere vlakken in één entiteit te combineren.

**"Laatst gewijzigd" gebruiker instellen op Auteur in projectinformatie** Selecteer deze optie als u de auteur van de wijzigingen in deze export bent

**Te exporteren entiteiten** Dit is hoe het IFC-entiteitsselectiemenu dat opent eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/23-advanced.png)

---

### 3.6 **Geografische verwijzing**

Het is belangrijk dat uw Revit-coördinaten zijn gesynchroniseerd met de andere modellen in uw project, zodat ze op dezelfde plaats eindigen. Meet daarom de coördinaten in Catenda Hub met een puntmeting en geef een coördinaatbasis op in Revit op een punt dat op dezelfde plaats ligt als het gemeten punt in Catenda Hub.

![Coördinaat op punt opgeven](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/24-geographic-reference.png)

U kunt deze optie vinden in het tabblad Beheren -> Coördinaten -> Coördinaatbasis opgeven. _Coördinaten op punt opgeven_ Verplaatst een model en draait het model naar True North door coördinaten voor Noord/Zuid, Oost/West en hoogte op te geven. In Revit is het vaak gemakkelijker om te modelleren op 90 graden en wil u het hele model niet draaien. In dit geval kunt u in plaats daarvan True North draaien. U vindt de optie in de vervolgkeuzelijst Positie onder Coördinaten in het tabblad Beheren.

![Geografische verwijzing](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/25-geographic-reference.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/26-geographic-reference.png)

**Projectlocatie** Intern

**Coördinaatbasis** U kunt deze instelling wijzigen om ervoor te zorgen dat uw project naar het noorden is georiënteerd Gedeelde coördinaten - Standaardopmeetsunt Projectbasispunt Interne oorsprong Projectbasispunt georiënteerd naar True North Interne oorsprong georiënteerd naar True North

> **Opmerking:** Als u IFC in het tabblad Invoegen koppelt, wordt uw gekoppelde bestand dicht bij uw objecten geplaatst en niet op de locatie die in de IFC wordt beschreven. Als u in plaats daarvan een IFC naar de juiste locatie wilt importeren, klikt u op Bestand -> Openen -> IFC.

**Negeer** Hier kunt u de geprojecteerde coördinaatsysteemverwijzing negeren

---

### 3.7 **Bedrijfsinfo**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/27-company-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/28-company-info.png)

Dit menu is alleen beschikbaar wanneer de instelling IFC2x3 COBie 2.4 Design Deliverable View Setup in het linkermenu is geselecteerd.

---

### 3.8 **Projectinfo**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/29-project-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/30-project-info.png)

Dit menu is alleen beschikbaar wanneer de instelling IFC2x3 COBie 2.4 Design Deliverable View Setup in het linkermenu is geselecteerd.

---

## 4. **IFC-opties**

De IFC-opties van een Revit-project kunt u vinden in:

`Bestand -> Exporteren -> Opties -> IFC-opties`

![Exporteren -> Opties -> IFC-opties](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/31-ifc-options.png)

> **Opmerking:** Vanaf Revit 2026 is deze optie nu beschikbaar in: `Exporteren -> IFC -> Algemeen -> Categoriemapping -> Actiemenu rechts van vervolgkeuzelijst`

Hier in de _IFC-opties_ stellen we de instellingen in voor het exporteren van een model naar een IFC-bestand. Hier kunt u de setup-eigenschappen aanpassen voor het exporteren van een model naar IFC. Wat aan het begin van deze handleiding werd vermeld, is dat het niet nodig is om te veel informatie uit het model te halen. Voel je vrij om onnodige informatie vóór de export uit te schakelen.

![IFC-exportklassen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/32-ifc-options.png)

Het is mogelijk om rasters in Catenda Hub weer te geven, en als u deze in uw Revit-model hebt, kunt u in IFC-opties instellen dat rasters in de IFC worden geëxporteerd. Standaard worden deze niet uit Revit geëxporteerd.

## 5. **Kleuren en materialen**

De kleuren die in Catenda worden weergegeven, worden gelezen uit het IFC-bestand dat wordt geïmporteerd. Wanneer de materiële eigenschap van een familie aan de IFC-parameters wordt toegevoegd, wordt de kleur van het materiaal in de materiaaleigenschap aan de IFC toegevoegd en dus weergegeven in Catenda. In Revit kunnen materialen worden gevonden in de materiaalenbrowser:

`Tabblad Beheren -> Sectie Instellingen -> Materialen`
In de Materiaalenbrowser vindt u de instelling voor kleur in het tabblad Afbeelding van het materiaal:

![Beheren -> Materialen -> Materiaalenbrowser -> Nieuw materiaal maken](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/33-colors-and-materials.png)

Het is ook mogelijk om de schaduwing op de render-instellingen in te sluiten.

![Voorkomen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/34-colors-and-materials.png)

Oppervlakken in de Catenda 3D-viewer hebben platte schaduwing zonder lichtkracht. De volgende waarden worden door Catenda geïnterpreteerd bij het weergeven van het oppervlak in de 3D-viewer:

Algemeen

- Kleur
- Afbeelding vervagen

Transparantie

- Bedrag
- Afbeelding vervagen
- Doorschijnendheid

Tint

- Tintkleur
