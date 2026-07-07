# Handleiding Revit IFC exporteren

Het doel van deze handleiding voor IFC-export is om de gebruiker een handleiding te geven voor het exporteren van IFC voor de juiste doeleinden. Een IFC-bestand kan snel zwaar en groot worden als je veel informatie uit het model wilt halen. Daarom moet je bij het exporteren van een IFC overbodige informatie uitvinken. Bij het uploaden van een model naar Catenda is het niet altijd nodig om veel informatie en een hoog detailniveau in het model te hebben. Iets later in deze handleiding komen we terug op de instellingen die we aanraden om het model wat kleiner te maken en wat makkelijker om mee te werken. Hier overlopen we stap voor stap de meest geschikte manier om een IFC te exporteren van Revit naar Catenda.

In dit artikel vind je informatie over:

## 1. Project instellingen

Voordat je gaat exporteren is het belangrijk om ervoor te zorgen dat de GUID's van je Revit project correct zijn.

`Beheer -> Instellingen -> Projectinformatie -> IFC-parameters`

![](https://downloads.intercomcdn.com/i/o/975614819/ee92de6f2477949e208dac45/image.png?expires=1781092800&signature=22f30bf8576125786b12846d90b997dc615c409ba5b678d6000df45a4322cbc4&req=fSciEMh6lYBWFb4V1XW4gW4DZH10avMxDYKsohYxe9KujcH1hF5joErcbHET%0A0sr%2FfaH31EQykHBEENZXfifdHA%3D%3D%0A)

Als de GUID afwijkt van een eerdere export zullen de objecten van nieuwere exports niet goed gekoppeld worden aan de GUID's in BCF topics.

Wanneer je een nieuw project maakt zal het een unieke id hebben.

## 2. IFC-export wijzigen

Wanneer Revit is geopend en je klaar bent om te exporteren, kun je het volgende doen.

![](https://catenda-as.intercom-attachments-1.com/i/o/271057108/395387d7cf0cc2eb7d9928e9/image-0.png?expires=1781092800&signature=66ced81e2e597e9b48425be1a65d934ab7235385d6e0e5a938cdafc666887585&req=dicmFsx5nIFXFb4V1XW4gWhxfMxQy0%2FoCzxtIQ9WjWzXJ2qGW1KIpav9gweN%0AonDGgBmVBIbI7vLjHWq7AItBPg%3D%3D%0A)

Linksboven vinden we de tab "File".

---

> **Onthoud:** _het kan handig zijn om een speciale map te hebben voor je IFC's, zodat je altijd controle hebt over waar je bestand zich bevindt!_

Het menu voor IFC-export vindt u hier:

`Bestand -> Exporteren -> IFC`

![](https://catenda-as.intercom-attachments-1.com/i/o/271057123/d49b5bef059523291ef5968e/image-1.png?expires=1781092800&signature=9f0b6c0d43b1d4c094640d83b73902cb6a596458e8c4e35ec64eb1a612535902&req=dicmFsx5nINcFb4V1XW4gdQLpPviLwVRilNrONBuLrAR1lQN87K%2FewpPYGIf%0ApA5oYxtykInFq55yLnltOkBdMQ%3D%3D%0A)

Zo kan het menu IFC exporteren eruit zien:

![](https://downloads.intercomcdn.com/i/o/areracg3/1798387143/866e2fe7cec7589a87073fcc0c82/image.png?expires=1781092800&signature=b00f163464f440b53eaa0479ab42d92a3fa385b5297d2b470ae6148fa367c2cc&req=dScuHsp2moBbWvMW3nq%2BgZPn43QGi8yVVscZVd8M6r%2BuczDby8hxctqQL2Pq%0AKK8uip8yArxG8Qxw7xGGhxrOXxw%3D%0A)

Bestandsnaam

Voer de naam en locatie in die het geëxporteerde bestand in het systeem krijgt

Exportinstelling

Kies uit de volgende voorgedefinieerde setups:

\<In-Sessie Setup>

IFC 2x3 Coördinatieweergave 2.0

IFC 2x3 Coördinatieweergave

IFC 2x3 GSA Concept Ontwerp BIM 2010

IFC 2x3 Basisweergave FM-overdracht

IFC 2x3 Coördinatieweergave

IFC 2x3 COBie 2.4 Ontwerp Deliverable View

IFC4 Referentieweergave [Architectuur]

IFC4 Referentieweergave [Bouwkundig]

IFC4 Referentie View [GebouwService]

IFC4-Referentiebeeld [Niet-officieel]

IFC4x3

IFC-SG Aanzicht Regelgeving

Wanneer de Catenda Plugin voor Revit wordt gebruikt, wordt een extra voorgedefinieerde exportinstelling voor gebruik met Catenda toegevoegd aan de lijst met opties.

## 3. Setup wijzigen

Klik op Modify setup in het export setup gedeelte van het export ifc dialoogvenster.

Hier kunnen de noodzakelijke instellingen voor IFC-export worden gewijzigd en aangepaste setups worden gemaakt.

Dit venster bevat de volgende tabbladen:

---

### 3.1 Algemeen

![](https://catenda-as.intercom-attachments-1.com/i/o/271057133/8051aa4e84045a36936e4477/image-3.png?expires=1781092800&signature=9f0a1f37473db0103a09176158876ad07eeab653053f2491beef7109d9351f0b&req=dicmFsx5nIJcFb4V1XW4gRAeo%2FbbqY%2Bjy4yNVm7GGROIxz%2FOuB4aiieTxEhO%0Avx2MPY9pl2MHmH7m5TgbRi5FkA%3D%3D%0A)

We nemen de verschillende instellingen met je door.

_1. IFC-versie_ - Selectie van IFC-versie.

_2. Bestandstype_ - Selectie van het IFC-type.

**3. Fase exporteren**

Als je de fasetool

in Revit hebt gebruikt, kun je hier kiezen en alleen

nieuwe of bestaande structuren exporteren.

_4. Ruimtegrenzen -_ gaan over hoe ruimte-informatie verder kan worden gebruikt.

a. 1e niveau - Ex bij gebruik: Hoeveelheid onttrekkingen, FDVU.

b. 2e niveau - Ex bij gebruik: Energieanalyse, lichtanalyse.

5. _Project oorsprong_ - Project oorsprong, dit zetten we op Huidige gedeelde coördinaten- Huidige gedeelde coördinaten.

_6. Wanden, kolommen, kanalen splitsen per niveau_ - Hier kun je bijv. wanden horizontaal splitsen als het model over meerdere verdiepingen loopt.

_7. Inclusief stalen elementen_ - Inclusief stalen componenten indien gemodelleerd.

---

### 3.2 Extra inhoud

![](https://downloads.intercomcdn.com/i/o/801770461/27837862bbe48d592f7e7022/image.png?expires=1781092800&signature=8cd2dcb34c91a4681de54484c89b80fc85c9e387c46fe0d7fe25959e6d2ad3f4&req=fCAmEc5%2BmYdeFb4V1XW4gbPpvGgDiiJxUCyzpW1EyLOn2KvzrrihU2fq0vsf%0Ar2EFRx41WWPsrmjelOaw0Eg2mA%3D%3D%0A)

1. Gelinkte bestanden exporteren als afzonderlijke IFC's

Als u de gekoppelde bestanden wilt opnemen in de IFC, kunt u deze optie aanvinken om dat te doen.

Het is aan te raden om elk bestand apart te exporteren en te importeren in hun eigen model.

2. Exporteer alleen zichtbare objecten die zichtbaar zijn in het

IFC-bestand.

3. Exporteer ruimten, gebieden en ruimtes in 3D-aanzichten

Deze optie kan handig zijn voor het selecteren van ruimtes in de 2D viewer.

4. Stalen elementen opnemen, _gevuld_

5. Exporteert 2D-planweergaven, _gevulde_

_gebieden_ (krassen).

---

### 3.3 Eigenschappenreeksen

![](https://catenda-as.intercom-attachments-1.com/i/o/271057152/2f2ad2b699248505b991d502/image-5.png?expires=1781092800&signature=1295e7fd9c9490631dcdf0bedcae41c07df94a7d985577d4401878d131085b11&req=dicmFsx5nIRdFb4V1XW4gTc5yyntzCu%2BMV4hR%2BqGrisix0tJTLs3z3DA%2BcXf%0AlS%2BsKN9VEtUFIRqaaB%2FMGP00Hw%3D%3D%0A)

1. Exporteert alle Revit eigenschappensets (pset / properties)

Hier is een voorbeeld van een muur geëxporteerd met deze optie:

Revit_(Links_) --- Catenda_(Rechts_)

![](https://downloads.intercomcdn.com/i/o/1143733823/5843705d0d8e18fad06a2d26/image.png?expires=1781092800&signature=d3c8f5f2e89496672a009244a29666882a4d5ed850a3ada5baf282996984dfeb&req=dSEjFc59noldWvMW3nq%2Bgf%2FEabfJsgmE6qaxSmsaQLnOEcrEWUDecLdGPLDS%0AX6Acg6q8YRRWmemsm%2FJmP5NeU8E%3D%0A)

---

![](https://downloads.intercomcdn.com/i/o/1143736276/8e2cd444c3cb4bb85a54a8eb/image.png?expires=1781092800&signature=34625dadd77a0f74aaec93d0b07441024225117a6f56cb9b084b88eec322f53f&req=dSEjFc59m4NYX%2FMW3nq%2BgT9zLO7cla6SHFd2KtbnaRMX5aTVuOC8ph9XiCgR%0Ap3b0qpPvprlRm3jAHMRpeWbClos%3D%0A)

Typische eigenschappen die worden weergegeven in het eigenschappenmenu zijn:

Constraints, Cross-Section Definition, Dimensions, Structural, Identity Data, Other

Typische eigenschappen die in het menu Identification verschijnen zijn:

IFC Parameters

2. Standaard IFC-eigenschappen exporteren.

3. Exporteert berekende hoeveelheden van objecten.

4. Batchlijsten exporteren

5. Eenmalige eigenschappenset exporteren

**Classificatie-instellingen**

Hier is een voorbeeld van hoe classificatie-instellingen eruit kunnen zien met omniclass.

![](https://downloads.intercomcdn.com/i/o/1143721778/529f91196d1161bc0f7fc191/image.png?expires=1781092800&signature=b3623c0892be237d82fba4fd3289cee68e07e3a84a2d2797ad7163af05252618&req=dSEjFc58nIZYUfMW3nq%2BgTdoFEURrw9W6nPZ2V0i6WSE%2Bx8YqK3Yiesvs8ip%0AuCL0zXGlHVIIGXOxdTP5mQJKNUU%3D%0A)

_Naam_ - De naam van de classificatie

_Bron (Uitgever)_ - De uitgever van de classificatie

_Editie_ - De editie van de classificatie

_Editie datum_ - De datum van de classificatie

_Documentatielocatie_ - Dit moet een geldige documentatielocatie zijn

**Rubriceringsveldnaam**

De classificatieveldnaam is de naam van de parameter in uw objecten die de classificatiewaarde zal bevatten. Deze parameter kan vaak gevonden worden op familieniveau. Bewerk een familie om de eigenschappen te zien

![](https://downloads.intercomcdn.com/i/o/1143724998/b22b5f6c87f49ea7c42381bf/image.png?expires=1781092800&signature=c388476d8a7f22081f4e436b94a5d840a0750177cf0f6ad6739e1e54253547f8&req=dSEjFc58mYhWUfMW3nq%2BgSZUcWo1FOkqXnJYpyvCdnb6akMbGZmK3rHBEWm%2F%0AkCht%2FRfgbXxIQeXGFlaUFhVNrO4%3D%0A)

Zo kan de parameter eruit zien in de eigenschappen

![](https://downloads.intercomcdn.com/i/o/1143726246/d4edad8d1fd6912e74ac1dfd/image.png?expires=1781092800&signature=da76ee8ae6aee3def558368e9e0cc64f86c4af32a5d0ba61270886a9feb49cf0&req=dSEjFc58m4NbX%2FMW3nq%2Bge0lDZhw%2B0BWg2dV9tT6cxhge33Di%2F%2BPWzHn113Y%0AQge%2Ft4ynqCOaoPdB7r8xnmbbWbw%3D%0A)

Als je een ifc met classificatie hebt geëxporteerd en als model in Catenda hebt geïmporteerd, zie je de classificatie voorgesteld als een [voorgestelde bibliotheek](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca) bij het aanmaken van een nieuwe bibliotheek op de [pagina Bibliotheken](https://support.catenda.com/en/articles/8065645-libraries-page). Als een waarde in de door jou gespecificeerde eigenschap overeenkomt met een waarde in de bijgeleverde documentatie, dan wordt deze gevonden en kan deze gebruikt worden om objecten met deze waarde te selecteren via de classificatiebibliotheek die je hebt aangemaakt.

---

### 3.4 Detailniveau

Dit gaat over hoe gedetailleerd we bijvoorbeeld kopjes of leuningen of misschien fietswielen hebben. Er zijn 4 verschillende detailniveaus.

![](https://catenda-as.intercom-attachments-1.com/i/o/271057162/4c417102be6cfa626da9dcc2/image-6.png?expires=1781092800&signature=b496ed0861b8f7c7d5e67e94fcb8dc8518af70b0d7ab947a81e68402d1ece343&req=dicmFsx5nIddFb4V1XW4gbW5GTgHoPkHYqjS0sDGHyHxPH9rVJZlXnUnKIQc%0AsBifrSVyeViMfZIhArIW%2B1zwgw%3D%3D%0A)

Extra Laag, Laag, Gemiddeld en Hoog.

Bij High wordt het het meest gedetailleerd, zoals te zien is in onderstaande afbeelding.

![](https://catenda-as.intercom-attachments-1.com/i/o/271057169/c6cea2aa0003f1c409488aae/image-7.png?expires=1781092800&signature=163ca81e8090cd8111015b87422fb1c763363cbe441a98de5e2d5addb4160e73&req=dicmFsx5nIdWFb4V1XW4gbUv%2FgjmviCGbDDb1AFfiWu1GWDJMFykpWYqnBSt%0A8wHmdEkuf9lNiFmOD%2B7116w%2BWg%3D%3D%0A)

---

Bij het exporteren van IFC's uit Revit voor gebruik in Catenda Hub raden we aan om het detailniveau niet te hoog in te stellen. Er zullen veel details en extra polygonen in modellen zitten wanneer deze met een hoger detailniveau worden geëxporteerd en dit is niet altijd nodig en zal het navigeren door het model langzamer maken. Dit is een voorbeeld van het verschil tussen exporteren met de instelling Extra laag en Hoog.

![](https://catenda-as.intercom-attachments-1.com/i/o/271057176/4d23600fddf517fa8afa68b3/image-8.png?expires=1781092800&signature=687538a2f51390d1c2496a56ac501a0047a7f2084be29544df3e1c72d2620abd&req=dicmFsx5nIZZFb4V1XW4gXDdgIekagJuRfPcu87o1zP4ve6r3oLBUX0acm25%0ApnerAD5N5Dm6YEoW8hoPiWEcHA%3D%3D%0A)

![](https://catenda-as.intercom-attachments-1.com/i/o/271057186/de52cec6e75ba1d44c01d9fb/image-9.png?expires=1781092800&signature=4ad8acf5a209d1300b89be36e46854cabc2df68ff8986d80a78a52da834391d0&req=dicmFsx5nIlZFb4V1XW4ga5Y09Ui7TnmuqxhZ3TBUX5W45nlGIxZj38QI3aA%0AEXg8VjMtFsN7DRIWWtmxivtd4w%3D%3D%0A)

Het uiterlijk van het model zal vrijwel hetzelfde zijn, maar het aantal polygonen zal drastisch afnemen en de navigatie in Catenda Hub zal een stuk sneller gaan.

---

### 3.5 Geavanceerd

![](https://downloads.intercomcdn.com/i/o/762436110/53060f6623c03636599afd65/image.png?expires=1781092800&signature=7e5d4c6fc5774a25daed486302bd750786e163677394b3c3810c18beb6217c18&req=cyYlEsp4nIBfFb4V1XW4gZKfAMjUpLLEaBScAMYPcrxl294b7UlsvqYiSVoJ%0AHIfxZOmNpNke9SGMFFIaXhgXRA%3D%3D%0A)

1. Exporteer onderdelen als een standaard IFC element.

2. Selecteer deze optie om het mengen van BRep en extrusie geometrieën voor een unit toe te staan.

3. Selecteer deze optie om de actieve view te gebruiken om de geometrie te genereren. Merk op dat dit onverwachte resultaten kan hebben als het wordt gebruikt in een niet-3D aanzicht.

4. Selecteer deze optie om de familie- en typenamen te gebruiken voor referenties.

5. Selecteer deze optie om een vereenvoudigde benadering te gebruiken voor het berekenen van het kamervolume (gebaseerd op

extrusie van 2D-ruimtedelimieten) die ook standaard is bij het exporteren naar IFC 2x2.

6. Selecteer deze optie om de hoogte vanaf de Z-offset op te nemen voor de lokale positie in IfcSite. Verwijder de optie om deze uit te sluiten.

7. Selecteer deze optie om de gegenereerde IFC GUID's op te slaan in het projectbestand na export. Dit voegt "IFC GUID" parameters toe aan items en hun types en Projectinformatie voor project, website en bouwgidsen.

8. Selecteer deze optie om "Bounding box" representaties te exporteren. Deze optie blijft automatisch geselecteerd voor GSA-export.

9. Als je complexe gebogen elementen of schalen hebt en ze worden niet correct weergegeven na de IFC-export, kun je deze optie selecteren. Houd er wel rekening mee dat het IFC-bestand dan erg zwaar kan worden.

10. Selecteer deze optie als u wilt dat de BAT-ID of de ID van het object wordt weergegeven als de naam van de entiteit.

11. Selecteer deze optie als u wilt dat de Revit objectnaam de naam van de entiteit is

---

### 3.6 Geografische referentie

Het is belangrijk dat je Revit coördinaten gesynchroniseerd zijn met de andere modellen in je project zodat ze op dezelfde plaats terecht komen.

Meet daarom de coördinaten in Catenda Hub op met een puntmaat en specificeer een coördinatenbasis in Revit op een punt dat op dezelfde plaats ligt als het opgemeten punt in Catenda Hub.

![](https://downloads.intercomcdn.com/i/o/969764101/0c12135b4cfe78982de2d2c9/image.png?expires=1781092800&signature=84d865b4e05cd94c652262461fda5186cf3f7d946257cdddba401888aea06abd&req=fSYuEc96nIFeFb4V1XW4gXGcH6FISuvCuGsiUzSJvpN%2B2gT%2BbnAigyT02RI%2F%0AlYpLb4rMYF4tiqRbu5bmBqCC2g%3D%3D%0A)

Je vindt deze optie in de Manage tab -> Coordinates -> Specify Coordinate Base. _coördinaten opgeven bij punt_

Verplaatst een model en roteert het model naar het ware noorden door coördinaten op te geven voor Noord/Zuid, Oost/West en Elevatie.

In Revit is het vaak eenvoudiger om te modelleren onder hoeken van 90 graden en wil je niet het hele model roteren. In dit geval kun je het ware noorden roteren. Je vindt de optie in het vervolgkeuzemenu Positie onder Coördinaten op het tabblad Beheren.

![](https://downloads.intercomcdn.com/i/o/817756541/b53247c4381eb5c35bb9d18b/image.png?expires=1781092800&signature=051311eba043e9a123f63ff0a14ecbb7fa67b292e6e8cb26d9edacab0e00035c&req=fCEgEcx4mIVeFb4V1XW4gZnws9NKcGTDL8o1YS3JtbOTYY7g8BEv%2FiVm1pI9%0AxRm47OnwnfXB466DOBVkk6MV1w%3D%3D%0A)

_1. Projectlocatie_ - Intern

_2. Coördinaat basis_ -

Je kunt deze instelling wijzigen om ervoor te zorgen dat je project op het noorden is georiënteerd

Gedeelde coördinaten - Standaard

Enquête punt

Project Basispunt

Interne oorsprong

Projectbasispunt Georiënteerd in het Ware Noorden

Interne oorsprong Georiënteerd in het Ware Noorden

> **Opmerking:** Als u IFC koppelt in het tabblad Invoegen, wordt uw gekoppelde bestand dicht bij uw objecten geplaatst en niet op de locatie die in de IFC wordt beschreven. Om een IFC naar de juiste locatie te importeren, klikt u in plaats daarvan op Bestand -> Openen -> IFC.

**3. Overschrijven**

Hier kunt u de referentie van het geprojecteerde coördinatensysteem overschrijven

---

## 4. IFC opties

De IFC Options van een Revit project kunnen gevonden worden in:

`Bestand -> Exporteren -> Opties -> IFC-opties`

![C:\Users\Kristian\AppData\Local\Temp\SNAGHTML4b61da.PNG](https://catenda-as.intercom-attachments-1.com/i/o/271057200/45a1257c55b1828c71e969a4/image-11.png?expires=1781092800&signature=d18decf494bb4cc9b436ce50608d52e1b2c80f133a56f17d4f9a8256a149b85b&req=dicmFsx5n4FfFb4V1XW4gakKrGrYtjEFmiAUJOtaQtSPFXcdjJtB8agolGCg%0AE4MaP533t6t4YBplk4iE%2FrXM3g%3D%3D%0A)

Hier binnen de _IFC opties_ maken we de instellingen voor het exporteren van een model naar een IFC bestand. Hier kunt u

eigenschappen aanpassen voor het exporteren van een model naar IFC. Wat aan het begin van deze handleiding is vermeld, is

het is niet nodig om te veel informatie uit het model te halen. Vink gerust onnodige

informatie voor het exporteren.

![](https://catenda-as.intercom-attachments-1.com/i/o/271057211/d475dd84fb2efef9d7bf4c1d/image-12.png?expires=1781092800&signature=7212818cd7e7225a6bee95cc202498ff6f83b0de62997b9de764a0ab64ab1a4c&req=dicmFsx5n4BeFb4V1XW4gdpd3cTZLxUOEWsGxDwDCuBU3P2AUy%2Fk33mdcExY%0AtenxeVhs5GN20o7gm4uSxYFP1g%3D%3D%0A)

Het is mogelijk om rasters te bekijken in Catenda Hub, en als je deze in je Revit model hebt is het in IFC Options mogelijk om in te stellen dat rasters worden geëxporteerd in de IFC. Standaard worden deze niet geëxporteerd vanuit Revit.

## 5. Kleuren en materialen

De kleuren die worden weergegeven in Catenda worden gelezen uit het IFC-bestand dat wordt geïmporteerd. Wanneer de materiaaleigenschap van een familie wordt toegevoegd aan de IFC-parameters, wordt de kleur van het materiaal in de materiaaleigenschap toegevoegd aan de IFC en dus weergegeven in Catenda.

In Revit kan je materialen terugvinden in de materiaalbrowser:

`Tabblad Beheer -> sectie Instellingen -> Materialen`

In de materiaalbrowser kan de instelling voor kleur gevonden worden in het grafische tabblad van het materiaal:

![](https://downloads.intercomcdn.com/i/o/areracg3/1798363404/1016d10e61dcd4bbf3969dd97a39/image.png?expires=1781092800&signature=5ee7272efd7647b8a9544e41af6747a6259a5438ad8ff39d55016bee9b50a88f&req=dScuHsp4noVfXfMW3nq%2BgRHARe%2BfZSLVJkdtDswOuiR0dOcupZAmVKkRpdhZ%0Aq028kr6QAfKB0snku2VNQsJ52sA%3D%0A)

Het is ook mogelijk om de schaduw te vergrendelen naar de renderinstellingen.

![](https://downloads.intercomcdn.com/i/o/areracg3/1798375002/9394922e0e04c7beffd701083d45/image.png?expires=1781092800&signature=afe10bc65a063a09c01aa68726995ee41147f91d3ca6e1a64bde1df90d47dbe0&req=dScuHsp5mIFfW%2FMW3nq%2BgczmUc56y62lrqXB5MdIivv23x5JUgzFoFlwBcpp%0Aq8%2FwGq0OF9ww%2Bt1vOJqBMxsgUao%3D%0A)

Oppervlakken in de Catenda 3D viewer hebben een vlakke arcering zonder dat er een lichtbron aanwezig is. De volgende waarden worden door Catenda geïnterpreteerd bij het weergeven van het oppervlak in de 3D viewer:

Algemeen

- Kleur
- Beeld vervaging

Transparantie

- Hoeveelheid
- Beeld vervagen
- Doorschijnendheid

Tint

- Kleur tint
