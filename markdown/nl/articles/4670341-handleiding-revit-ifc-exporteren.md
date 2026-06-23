# Revit IFC Export Handleiding

Met deze IFC export handleiding is het doel om de gebruiker een gids te geven over het exporteren van de IFC voor de juiste doeleinden. Een IFC-bestand kan snel zwaar en groot worden wanneer u veel informatie uit het model wilt halen. Daarom moet u bij het exporteren van een IFC onnodige informatie uitvinken. Bij het uploaden van een model naar Catenda is het niet altijd nodig om veel informatie en een hoog detailniveau in het model te hebben. Later in deze handleiding gaan we terug naar welke instellingen we aanbevelen om het model iets kleiner en iets gemakkelijker te maken om mee te werken. Hier gaan we stap voor stap langs de meest geschikte manier om een IFC van Revit naar Catenda te exporteren.

## 1. **Projectinstellingen**

Voor het exporteren is het belangrijk om ervoor te zorgen dat de GUID's van uw Revit-project correct zijn.

`Beheren -> Instellingen -> Projectinformatie -> IFC Parameters`

![Project information IFC Parameters IfcSite GUID IfcBuilding GUID IfcProject GUID](https://downloads.intercomcdn.com/i/o/975614819/ee92de6f2477949e208dac45/image.png?expires=1779991200&signature=488a733e6dce35b3f9f765548a38ebcbb902309625bfa1827447b3e10ff5d1ca&req=fSciEMh6lYBWFb4V1XW4gW4DZHJ8Y%2FMyB4KsohYxe9JI9upp%2BSOrcthV9MYf%0AU5M5bUP8q8Ck5XUUcK86OtHqKw%3D%3D%0A)

Als de GUID verschilt van een vorige export, zullen de objecten van nieuwere exports niet correct worden gekoppeld aan de GUID's in BCF-onderwerpen.

Wanneer u een nieuw project maakt, krijgt het een unieke id.

## 2. **IFC exporteren wijzigen**

Wanneer Revit open is en u klaar bent om te exporteren, kunt u het volgende doen.

![Druk linksboven op het scherm op bestand](https://catenda-as.intercom-attachments-1.com/i/o/271057108/395387d7cf0cc2eb7d9928e9/image-0.png?expires=1779991200&signature=29709f4df2bf2e93a7f49e265c84ad240cb9e1ca9f0d647626ae988df2a5ce2c&req=dicmFsx5nIFXFb4V1XW4gWhxfMNYwk%2FrATxtIQ9WjWxRlpEJI1psfy%2F4XuaV%0ANtKM3bS8PgmX5bN8%2Buoj%2FLUGDQ%3D%3D%0A)

Linksboven vinden we het tabblad "Bestand".

-----------------------------------------------------------

> **Onthouden:**_ Misschien wilt u een speciale map voor uw IFC-bestanden maken, zodat u altijd weet waar uw bestand zich bevindt!_ Het IFC export menu kunt u hier vinden: `Bestand -> Exporteren -> IFC` ![](https://downloads.intercomcdn.com/i/o/areracg3/1892251735/1f06f6821d79b19642af1b81ebe6/image.png?expires=1779991200&signature=f77ab31d228b76bdf13529fee00caae4d6d42ccf86705e6e6788b4103ef18ea5&req=dSguFMt7nIZcXPMW3nq%2BgYeYtz5lfambMm12jWodCPeBvHXniyUmgGYciDwf%0AYXW5CLORtPkNnSMKCCj0IG5c3qs%3D%0A) Het IFC export menu kan er als volgt uitzien: ![IFC exporteren](https://downloads.intercomcdn.com/i/o/areracg3/1798387143/866e2fe7cec7589a87073fcc0c82/image.png?expires=1779991200&signature=4bfa202fb3004eec5587f9ccff80d9ad260c643ce24349d84a233dd0f1b00abf&req=dScuHsp2moBbWvMW3nq%2BgZPn43QJg8WVVc0ZVd8M6r96eVKW%2BS8G1RavyNB3%0A6vNrKhgPoxi%2FkGAPFMy7%2BWg0BfM%3D%0A) Bestandsnaam Voer de naam en locatie in die het geëxporteerde bestand in het systeem zal hebben Export instellingen Kies uit de volgende vooraf ingestelde instellingen: \<In-Session Setup> IFC 2x3 Coordination View 2.0 IFC 2x3 Coordination View IFC 2x3 GSA Concept Design BIM 2010 IFC 2x3 Basic FM Handover View IFC 2x3 Coordination View IFC 2x3 COBie 2.4 Design Deliverable View IFC4 Reference View [Architecture] IFC4 Reference View [Structural] IFC4 Reference View [BuildingService] IFC4 Reference View [Unofficial] IFC4x3 IFC-SG Regulatory Requirements View Wanneer de Catenda Plugin voor Revit wordt gebruikt, wordt er een extra vooraf ingestelde export instellingen voor gebruik met Catenda aan de lijst met opties toegevoegd.

## 3. **Instellingen wijzigen**

Klik op Instellingen wijzigen in het onderdeel Export instellingen van de export IFC-dialoog.

Dit is waar de noodzakelijke instellingen voor IFC-export kunnen worden gewijzigd en aangepaste instellingen kunnen worden gemaakt.

Dit kan het instellingenmenu wijzigen zien:

![](https://downloads.intercomcdn.com/i/o/areracg3/1892255169/dc9485955be8e9d289ef7b133e42/image.png?expires=1779991200&signature=fdb3c6d8b891f2db5a5d46d63d24dabdeb1eb90d7e823e58f8076ad2e015e125&req=dSguFMt7mIBZUPMW3nq%2BgU4rCzwBivDLfsHeLviWOkIR%2BVu9c41EQE6LWfpQ%0AnFh5xdUdS7zkwB57Eqs2k6s5uMw%3D%0A)

Dit venster bevat de volgende tabbladen:

[Algemeen](#h_fb41b895ea) - [Aanvullende inhoud](#h_ed48fc4387) - [Eigenschappensets](#h_04dd25ffef) - [Detailniveau](#h_11ae63fb7f) - [Geavanceerd](#h_f7b35f27cd) - [Geografische referentie](#h_de5067b34b)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 3.1 **Algemeen**

![Algemeen](https://downloads.intercomcdn.com/i/o/areracg3/1892229977/5b41cf313ce744a76d57707e7156/image.png?expires=1779991200&signature=de7a76fac9b01f590c83303ae40078c1584ff8b4876ef0b169519d39e6d9c20a&req=dSguFMt8lIhYXvMW3nq%2BgaV%2FCQixLdXaNeZ7QyQ0axWAyNp02PCsj0gdc2if%0Ad1tMevbVyEJSRIO7%2Bjxmt6fUIRM%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892261475/b091b92e7662bd96f93d12bf7f53/image.png?expires=1779991200&signature=9c06e8d7af983ce6a940f923b9ef8727f8c61d9e26ef8e352988fa36b62bd281&req=dSguFMt4nIVYXPMW3nq%2BgXBEgWjeQPHCGpBWTw2Nw1Jy05ppTRgbw1VTpLZH%0At1eqbpZDOUcMRs4z%2FBI%2Fnj41rJ0%3D%0A)

We nemen u door de verschillende instellingen.

_IFC versie_

Selectie van IFC versie.

_Uitwisselingsvereiste_

Deze opties kunnen verschillen afhankelijk van de geselecteerde IFC-versie.

IFC 2x3 Coordination View 2.0

- Bouwkundige referentie-uitwisseling
- MEP-referentie-uitwisseling
- Structurele referentie-uitwisseling
  _Categoriemapping_
  Voor Revit 2026 was deze optie beschikbaar in Bestand -> Exporteren -> Opties -> IFC Export Opties.
  Dit is hoe het menu Instellingen voor IFC Export Mapping beheren eruit kan zien:
  ![](https://downloads.intercomcdn.com/i/o/areracg3/1892362444/0291c2b037d32fe0a4808e9fe7f7/image.png?expires=1779991200&signature=528dc3b6bcb4d9399320d85087b57a2e29ed93341169cec06ce9cb8ed5c84fb7&req=dSguFMp4n4VbXfMW3nq%2BgZ7axO8%2FlFRz4FYwOCciizXyG4lDOXEisrBlsk4c%0AAoRXuiRV9UdddmK2UwD%2FBi7AM7g%3D%0A)
  _Bestandstype_
  IFC type selectie.
  _Fase om te exporteren_
  Als u het fasetool in Revit hebt gebruikt, kunt u hier kiezen en alleen
  nieuwe of bestaande structuren exporteren.
  _Ruimtegrenzen_
  Deze gaan allemaal over hoe ruimte-informatie verder kan worden gebruikt.
  a. 1e niveau - Voorbeeld: Hoeveelheidswittokkingen, beheer, bedrijf en onderhoud (FDVU).
  b. 2e niveau - Voorbeeld: Energieanalyse, lichtanalyse.
  _Faciliteit Type_
  Deze optie is alleen beschikbaar voor IFC 4x3
  Kies uit een van de volgende:
  Brug (IfcBridge)
  Gebouw (IfcBuilding)
  Maritime Faciliteit (IfcMarineFacility)
  Spoorwegen (IfcRailway)
  Weg (IfcRoad)
  _Muren, kolommen, kanalen per niveau splitsen_
  Hier kunt u bijvoorbeeld muren horizontaal verdelen als ze over meerdere verdiepingen zijn gemodelleerd. Bijv. scheidingsmuren horizontaal als deze over meerdere verdiepingen zijn gemodelleerd.
  _Bestandskoppelinginformatie..._
  Projectadres..._
  In deze kunt u informatie plaatsen over wie de IFC heeft geleverd, projectadres enz.
  _Projectoorsprong_
  Projectoorsprong, dit zetten we op Huidige gedeelde coördinaten - Aanwezige gedeelde coördinaten.

> **Opmerking:** Dit is verplaatst naar Geografische referentie vanaf Revit 2025 _Stalen elementen opnemen_ Neemt stalen componenten op als deze zijn gemodelleerd. **Opmerking:** Dit is verplaatst naar Aanvullende inhoud vanaf Revit 2025

---

### 3.2 **Aanvullende inhoud**

![Aanvullende inhoud](https://downloads.intercomcdn.com/i/o/areracg3/1892231518/1438a720e7d2d083f16e999b248d/image.png?expires=1779991200&signature=14ae8e037db758f837b33fce3426217ec13a1be4bdae21d9021a6c6e2adef1ed&req=dSguFMt9nIReUfMW3nq%2BgUrmoL4SQTHbWqp11fsyPaNkkVHU8HTI2%2F7M7%2BzB%0ABmowPSLQu3ATd2%2F2iUivb83tBuQ%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892263880/c2a3aa2c87b0e2798aa352e8e939/image.png?expires=1779991200&signature=d34f7286a508b4628d39a8280c078fb7fab54fd9c269d8f5f4b9bdb4b2f506cc&req=dSguFMt4nolXWfMW3nq%2BgZuMl2%2B0ocCSxdsSWUVwjc07TZne90pVVQ20GLrW%0AXKEA4G7s2qjM4xmQ4ob3bLJz%2Fzg%3D%0A)

Gekoppelde bestanden als afzonderlijke IFC's exporteren

Als u de gekoppelde bestanden in de IFC wilt opnemen, kunt u deze optie inschakelen.

Het wordt aanbevolen dat u elk bestand afzonderlijk exporteert en elk naar hun eigen model importeert.

Alleen zichtbare objecten zichtbaar in IFC-bestand exporteren.

- Ruimten, oppervlakken en spaties in 3D-weergaven exporteren
  Deze optie kan nuttig zijn voor het selecteren van gebieden in de 2D-viewer.
  Stalen elementen opnemen, _gevuld_
  Exporteert 2D plattegrond elementen, _gevuld, regio's_ (krassen).
  Plafondnetwerken exporteren
  Plafondnetwerken zijn 2D-elementen en worden daarom niet weergegeven in de Catenda 3D-viewer.

---

### 3.3 **Eigenschappensets**

![Eigenschappensets](https://downloads.intercomcdn.com/i/o/areracg3/1892232792/135fdbf14ece65c88f19bd1d226a/image.png?expires=1779991200&signature=08f85973ddc0828e1bce6019eed0e2ca144295420ac48e4d9b236988f3109720&req=dSguFMt9n4ZWW%2FMW3nq%2BgaY8ra%2BUm5L2ZjmJcmldhCuBAdrt45HA7HZqKLol%0AtoA76daMbGTClWLlzEA9uLIe9yA%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892275051/2ed64b1590f2714d62846de4f92f/image.png?expires=1779991200&signature=72c737d699d3e9d1d54ab3270ebf9a6416e597a6f32ba4fc860fd242e2c1abcd&req=dSguFMt5mIFaWPMW3nq%2BgZi725RhkXN5IeQuWPtKkGbxpRk%2Bl9O8njkEN8R8%0AV3y8MdRThA7Jgy%2FpcsTiX3Qr%2Bo0%3D%0A)

Exporteert alle Revit Property sets (pset / eigenschappen)

Hier is een voorbeeld van een muur geëxporteerd met deze optie:

Revit (_Links_) --- Catenda (_Rechts_) <img alt="Eigenschappen" src="https://downloads.intercomcdn.com/i/o/1143733823/5843705d0d8e18fad06a2d26/image.png?expires=1766188800&amp;signature=e683738cab58632050b7cafa92c034f12a46f70dfe3155d1cf4d911252b4d5cc&amp;req=dSEjFc59noldWvMW3nq%2Bgf%2FEabfHtQiF4KaxSmsaQLmis0sQMPMY4FRacuZa%0Az3YPfah7rm21SlIs85aLL8uLrZY%3D%0A" width="208.60495436766624"/>  ---  <img alt="Eigenschappen" src="https://downloads.intercomcdn.com/i/o/1143736276/8e2cd444c3cb4bb85a54a8eb/image.png?expires=1766188800&amp;signature=10633b362c0901da616a360cdbf654306792d62af04cc4f3501c3bda51769102&amp;req=dSEjFc59m4NYX%2FMW3nq%2BgT9zLO7Skq%2BTFld2KtbnaRMzDGwWjYF5Mm1itI8z%0AVIQLHf%2B4YSGFII1x5k%2BObZqVuGo%3D%0A" width="190.21739130434784"/>

Typische eigenschappen die in het eigendomsmenu worden weergegeven zijn:

Beperkingen, Dwarsprofielbepaling, Afmetingen, Structureel, Identiteitsgegevens, Overige

Typische eigenschappen die in het identificatiemenu worden weergegeven zijn:

IFC-parameters

Standaard IFC-eigenschappen exporteren.

Exporteert berekende hoeveelheden van objecten.

Batchlijsten exporteren

Eenmalige eigenschap set exporteren

_Classificatie-instellingen_

Hier is een voorbeeld van wat classificatie-instellingen kunnen uitzien met omniclass.

![Classificatie-instellingen](https://downloads.intercomcdn.com/i/o/1143721778/529f91196d1161bc0f7fc191/image.png?expires=1779991200&signature=f13d4621978f597e4d0c968364da4bd522527c7f374efda94be6a0be7575c6ca&req=dSEjFc58nIZYUfMW3nq%2BgTdoFEUepwZW6XnZ2V0i6WQvADjlF%2BLhRY6OJkFP%0AiNN3Uof7HbJp4u6Gl9XBlQAU8Ss%3D%0A)

_Naam_

De naam van de classificatie

_Bron (Uitgever)_

De uitgever van de classificatie

_Editie_

De classificatie-editie

_Editiedatum_

De datum van de classificatie

_Documentatielocatie_

Dit moet een geldige documentatielocatie zijn

_Classificatieveldnaam_

De classificatieveldnaam is de naam van de parameter in uw objecten die de classificatiewaarde bevat. Deze parameter kan vaak op familieniveau worden gevonden.

Een familie bewerken om de eigenschappen ervan te zien

![Familie bewerken](https://downloads.intercomcdn.com/i/o/1143724998/b22b5f6c87f49ea7c42381bf/image.png?expires=1779991200&signature=8590e78ce69a0d98961dc796b658ba4bf72cf03c45dba1890900a214bafbb117&req=dSEjFc58mYhWUfMW3nq%2BgSZUcWo6HOAqXXhYpyvCdnZ5nwKOSt5eRyx6qPHd%0AgRRUvOdjNZu11Av4vkAmqN6p0o4%3D%0A)

Hier ziet u hoe de parameter in de eigenschappen kan uitzien

![Eigenschappen OmniClass Nummer](https://downloads.intercomcdn.com/i/o/1143726246/d4edad8d1fd6912e74ac1dfd/image.png?expires=1779991200&signature=25a111f49176bbcd4a4eca8317c7d6020339ad9635734a6fdd66b808adc91213&req=dSEjFc58m4NbX%2FMW3nq%2Bge0lDZh%2F80lWgG1V9tT6cxgr0M7xLIsZrNn2i2Tj%0Ar3LmBV%2BDKYl2bfCvCkuordzTxII%3D%0A)

Als u uw IFC met een classificatie hebt geëxporteerd en deze als model naar Catenda hebt geïmporteerd, wordt de classificatie ervan voorgesteld als een [voorgestelde bibliotheek](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca) wanneer u een nieuwe bibliotheek maakt op de [bibliotheken pagina](https://support.catenda.com/en/articles/8065645-libraries-page).

Als een waarde in de eigenschap die u hebt opgegeven, overeenkomt met een waarde in de verstrekte documentatie, wordt deze gevonden en kan deze worden gebruikt om objecten met deze waarde te selecteren via de classificatie bibliotheek die u hebt gemaakt.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 3.4 **Detailniveau**

![Detailniveau](https://downloads.intercomcdn.com/i/o/areracg3/1892234477/a9bbe7f93df2e1f86dd77e0d8595/image.png?expires=1779991200&signature=51855781c86ef0d04cb75ec5abe362af236e216618b33ecddea36190c8ece55b&req=dSguFMt9mYVYXvMW3nq%2BgcGzWTbpx%2B5haiavdWYct%2BeRmFV0zbmfiG0oTuny%0ATNdlYRRUrCJXUVJUnpte5c9DwEg%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892279715/fc5d54cc402a319c1f102802fc97/image.png?expires=1779991200&signature=a04b7a621f85578fedddab7f9829e2da3a5a0d67f2226d40d826a5ff56e0f063&req=dSguFMt5lIZeXPMW3nq%2BgUWqnn%2FqIvGkfS0SdjfSGKflUy63XmjaojOfoQju%0ADW71Q%2BhgwZX1JLzynRJK3wz6z%2BQ%3D%0A)

Dit gaat erom hoe gedetailleerd we bijvoorbeeld hebben. kopjes of leuningen of misschien fietswheels. Er zijn 4 verschillende detailniveaus.

Extra laag

Laag

Middel

Hoog

Wanneer hoog, wordt het meest gedetailleerd zoals weergegeven in de onderstaande afbeelding.

![Detailniveau extra laag en hoog](https://catenda-as.intercom-attachments-1.com/i/o/271057169/c6cea2aa0003f1c409488aae/image-7.png?expires=1779991200&signature=61fe3f4006900fd1d34c251c062b3db03fc2fd91f19e16a776870e31c9aebfab&req=dicmFsx5nIdWFb4V1XW4gbUv%2FgfutyCFZjDb1AFfiWvoJKOpzILR0DxPJCm8%0AyB%2BxbX0DAGzFhIfWt2vGYTMOHg%3D%3D%0A)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Bij het exporteren van IFC's van Revit voor gebruik in Catenda Hub, raden we aan het detailniveau niet hoog in te stellen. Er zijn veel details en extra polygonen in modellen wanneer geëxporteerd met een hoger detailniveau en dit is niet altijd nodig en zal de modelnavigatie langzamer maken. Dit is een voorbeeld van het verschil tussen exporteren met de instelling Extra laag en Hoog.

![Dit is een trapuiting geëxporteerd met de instelling Hoog. 900k polygonen](https://catenda-as.intercom-attachments-1.com/i/o/271057176/4d23600fddf517fa8afa68b3/image-8.png?expires=1779991200&signature=b40c5225839df08ff3cb63abba8707242a1b1485aea1a1349b7432050ae583ee&req=dicmFsx5nIZZFb4V1XW4gXDdgIisYwJtT%2FPcu87o1zP5fAUc4VXkBDnRaDr8%0A2T6aJEaBkIYupUl7unZmH%2FzFdA%3D%3D%0A)

![Dit is dezelfde model geëxporteerd met de instelling Extra laag. 33k polygonen.](https://catenda-as.intercom-attachments-1.com/i/o/271057186/de52cec6e75ba1d44c01d9fb/image-9.png?expires=1779991200&signature=d8d2ced2202f3b52ae3b4585ea65977a74ee4709caed275abfc8d460d88a29db&req=dicmFsx5nIlZFb4V1XW4ga5Y09oq5DnlsKxhZ3TBUX7ENpGZnXWMCoB3Pz9w%0AYeiCXqLvdMUXo7BSPFFWU5lI1Q%3D%3D%0A)

De verschijning van het model zal bijna hetzelfde zijn, maar het aantal polygonen zal drastisch afnemen en de navigatie in Catenda Hub zal veel sneller zijn.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 3.5 **Geavanceerd**

![Geavanceerd](https://downloads.intercomcdn.com/i/o/areracg3/1892235835/c5a537efaad511b257aa34fd9393/image.png?expires=1779991200&signature=9ef54911a2b76d39f4e3c23df0f85f171699dd8a363ab3cf3cb37349a603544d&req=dSguFMt9mIlcXPMW3nq%2Bgej6EvTV%2BJ5RKvpYf%2BwKvvA%2BZUGNGSO9ksC63ytf%0AVqsnDeqhyykw%2B4ATqbgGWKSALMs%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892285324/5ee98db642dda09e9ef2e32f89f3/image.png?expires=1779991200&signature=a1105615a979210c8668e250b9ba318c89bc4fbd6335483a32692b3f7a71552f&req=dSguFMt2mIJdXfMW3nq%2BgeyMDiMPhq7Q85wgYm3Xh1XpOK5XvxcASYTyhduW%0AsLQ%2B1rJyZBFN%2FAQvoW31uHOg%2F7A%3D%0A)

_Delen als bouwelementen exporteren_

Exporteer delen als standaard IFC-element.

_Gebruik van gemengde "Solid Model" representatie toestaan_

Selecteer deze optie om het mengen van BRep en extrusiegeometrie voor een eenheid toe te staan.

_Actieve weergave gebruiken bij het maken van geometrie_

Selecteer deze optie om de actieve weergave te gebruiken om de geometrie te genereren. Houd er rekening mee dat dit onverwachte resultaten kan hebben als het op een niet-3D-weergave wordt gebruikt.

_Familie- en typenaam voor referentie gebruiken_

Selecteer deze optie om de familie- en typenamen voor referenties te gebruiken.

_2D ruimtegrenzen voor ruimtevolume gebruiken_

Selecteer deze optie om een vereenvoudigde benadering te gebruiken voor het berekenen van het ruimtevolume (gebaseerd op extrusie van 2D-ruimtegrenzen), wat ook standaard is bij het exporteren naar IFC 2x2.

_Verheffing van IfcSite in de lokale plaatsingoorsprong opnemen_

Selecteer deze optie om de hoogte van de Z-offset op te nemen voor lokale positie in IfcSite. Verwijder de optie om deze uit te sluiten.

_Sla de IFC GUID na het exporteren op in een elementparameter_

Selecteer deze optie om de gegenereerde IFC GUID's na het exporteren op te slaan in het projectbestand. Dit voegt "IFC GUID" parameters toe aan items en hun types en projectinformatie voor project, website en bouwgidsen.

_Begrenzingsvak exporteren_

Selecteer deze optie om "Begrenzingsvak" representaties te exporteren. Deze optie blijft automatisch geselecteerd voor GSA export.

_Tessellated Geometry als triangulatie behouden_

Als u complexe gebogen elementen of schelpen hebt en deze na de IFC export niet correct worden weergegeven, kunt u deze optie selecteren. Houd er rekening mee dat u mogelijk een zeer zwaar IFC-bestand kunt produceren.

_Alleen typenaam gebruiken voor IfcType-naam_

Selecteer deze optie als u wilt dat de BAT-ID of de ID van het object als de naam van de entiteit verschijnt.

_Zichtbare Revit-naam gebruiken als IfcEntity-naam_

Selecteer deze optie als u wilt dat de Revit-objectnaam de naam van de entiteit is

_Altijd gefacetteerde vloeren en daken als één IFC-entiteit exporteren_

Selecteer deze optie om vlakken van vloeren en daken met meerdere vlakken tot één entiteit te combineren.

_Stel "Laatst gewijzigd" gebruiker in op Auteur in Projectinformatie_

Selecteer deze optie als u de auteur van de wijzigingen in deze export bent

_Entiteiten om te exporteren_

Hier ziet u hoe het menu IFC Entity Selection dat opent er kan uitzien:

![](https://downloads.intercomcdn.com/i/o/areracg3/1892286935/be99502f0dd70ec946f55438c390/image.png?expires=1779991200&signature=799dca9446d3b00d4ca06944add4e6d6f47d8fd33c8a778c5d2557ab8437c12e&req=dSguFMt2m4hcXPMW3nq%2BgcADQUPx2PSQHDp0RWxq5dUnOJgx%2ByBdwcstuqRL%0AJLIzsYDQIIYPtAIY1dFKFpLkOAE%3D%0A)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 3.6 **Geografische referentie**

Het is belangrijk dat uw Revit-coördinaten zijn gesynchroniseerd met de andere modellen in uw project zodat ze op dezelfde plaats eindigen.

Daarom meet u de coördinaten in Catenda Hub met een puntmeting en geeft u een coördinatenbasis op in Revit op een punt dat op dezelfde plaats ligt als het gemeten punt in Catenda Hub.

![Coördinaat op punt opgeven](https://downloads.intercomcdn.com/i/o/969764101/0c12135b4cfe78982de2d2c9/image.png?expires=1779991200&signature=060be8f8a603fc0b1a1df40a9afcb314add9da447d344221a97c1a482e645427&req=fSYuEc96nIFeFb4V1XW4gXGcH65AQ%2BvBsmsiUzSJvpOZcWtpsV6NEtp3COB%2B%0AaAl33RB7R1SlFNStV1N44yOhtw%3D%3D%0A)

U kunt deze optie vinden in het tabblad Beheren -> Coördinaten -> Coördinatenbasis opgeven.

_Coördinaten op punt opgeven_

Verplaatst een model en roteert het model naar Ware Noorden door coördinaten voor Noord/Zuid, Oost/West en Verheffing op te geven.

In Revit is het vaak gemakkelijker om in 90-graden hoeken te modelleren en u wilt het hele model niet roteren.

In dit geval kunt u in plaats daarvan Ware Noorden roteren.

U vindt de optie in de vervolgkeuzelijst Positie onder Coördinaten in het tabblad Beheren.

![Geografische referentie](https://downloads.intercomcdn.com/i/o/areracg3/1892237064/dbd69633fadc1d5fe77cbbf10ad1/image.png?expires=1779991200&signature=a0fa45620598f4ea49637c071c3642c3e09a750a27b3c437d265926073e9efee&req=dSguFMt9moFZXfMW3nq%2BgWz5kavwajm2Q89QCw7rQngImO5dALYR%2F3X935bY%0ALRKgoqo1rT6VHyQCuYBc%2FWMRiDE%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892312196/3e117bb428e5bade5ced558f9bf3/image.png?expires=1779991200&signature=42aea4804b1dd4c21c0c6c4b6ed80d944086564e35b9902d1720c87903230719&req=dSguFMp%2Fn4BWX%2FMW3nq%2Bgak09I%2BhVIo7RxVv6rvgFchwhCbwffygGJDj6sXo%0AQDbWBuoUwVnnATNMwVm1SBR0YXM%3D%0A)

_Projectlocatie_

Intern

_Coördinatenbasis_

U kunt deze instelling wijzigen om ervoor te zorgen dat uw project naar het Noorden is gericht

Gedeelde coördinaten - Standaard

Opmeetpunt

Projectbasis Punt

Interne oorsprong

Projectbasis Punt gericht naar Ware Noorden

Interne oorsprong gericht naar Ware Noorden

> **Opmerking:** Als u IFC in het tabblad Invoegen koppelt, wordt uw gekoppelde bestand dicht bij uw objecten geplaatst en bevindt het zich niet op de locatie die in de IFC wordt beschreven. Als u een IFC op de juiste locatie wilt importeren, klikt u in plaats daarvan op Bestand -> Openen -> IFC. _Negeren_ Hier kunt u de geprojecteerde coördinatensysteemreferentie negeren

---

### 3.7 **Bedrijfsgegevens**

![](https://downloads.intercomcdn.com/i/o/areracg3/1892339968/a88c70cdc3d15ec1e87a1e966b46/image.png?expires=1779991200&signature=f68f221eb9ab0afd91c637e525a5d0057b3307e8e6530d5198dd90d3b144f8e5&req=dSguFMp9lIhZUfMW3nq%2BgRXRtZV646CzbhYCDTM1GZGXZIjmattZX5CDm0VJ%0ALOUcKRLlH3C9wmRrDi%2FTOy04v%2Bs%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892341695/f8aef094c7a84c8664cb6db386bc/image.png?expires=1779991200&signature=a174a5fdf3b7af5e95c5d1ed03b7d3edb1cacd026417765fdd6e0ec39c25cf03&req=dSguFMp6nIdWXPMW3nq%2BgSpJnU2%2FxbcY6345g60I7jviXU4X7ABgbjwoKuc7%0AcMRBSRyfbTm2vWp7Oys9oBkK7kw%3D%0A)

Dit menu is alleen beschikbaar wanneer de IFC2x3 COBie 2.4 Design Deliverable View Setup in het linkermenu is geselecteerd.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

### 3.8 **Projectgegevens**

![](https://downloads.intercomcdn.com/i/o/areracg3/1892356241/5a9153e5328e33ef5732be86af07/image.png?expires=1779991200&signature=24762c0ace7ebe4478d2b2713cd6017d4832352f6043104b1cc30ae373ab08f7&req=dSguFMp7m4NbWPMW3nq%2BgdDcqeJjXwra65LLEws6tCTU0wICq0oh9qpS9%2FJn%0Aqm4kmvwf4QEYAICFX8bkvDuQ7PE%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892357722/97a31374ae328eff814a977ff3ec/image.png?expires=1779991200&signature=003f4e0f69fc7180132651ec2a4ffb712c3fd3dde1440a29ae2fc4dc2a0573bb&req=dSguFMp7moZdW%2FMW3nq%2BgaYH1F4G60q4NivzbwFWQfKx5c%2BITWNaFVEP55gD%0AWJoucJnbsl2gDq1dZBIrmkyfeVs%3D%0A)

Dit menu is alleen beschikbaar wanneer de IFC2x3 COBie 2.4 Design Deliverable View Setup in het linkermenu is geselecteerd.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

## 4. **IFC Opties**

De IFC Opties van een Revit project kunt u vinden in:

`Bestand -> Exporteren -> Opties -> IFC Opties`

![Exporteren -> Opties -> IFC opties](https://catenda-as.intercom-attachments-1.com/i/o/271057200/45a1257c55b1828c71e969a4/image-11.png?expires=1779991200&signature=19ba7f1f06c737fd1570f0a06070ad9db96d0694ad820be88fb17bb60ed41856&req=dicmFsx5n4FfFb4V1XW4gakKrGXQvzEGkCAUJOtaQtRh3HZCglVgstn6e2Ch%0AaxVYb3DMOLXIpE8hXgvg%2F%2FKfNg%3D%3D%0A)

> **Opmerking:** Vanaf Revit 2026 is deze optie nu beschikbaar in: `Exporteren -> IFC -> Algemeen -> Categoriemapping -> Actiemenu rechts van vervolgkeuzelijst` Binnen de _IFC opties_ stellen we de instellingen voor het exporteren van een model naar een IFC-bestand. Hier kunt u aangepaste eigenschappen voor het exporteren van een model naar IFC. Wat aan het begin van deze handleiding werd vermeld, is dat het niet nodig is om te veel informatie uit het model te halen. Voel je vrij om onnodige informatie voor het exporteren uit te vinken. ![IFC export klassen](https://catenda-as.intercom-attachments-1.com/i/o/271057211/d475dd84fb2efef9d7bf4c1d/image-12.png?expires=1779991200&signature=ceb04d005a9687945fd4c5efc680f142fa8f71ab5daddaf6ef11c8828c6103ea&req=dicmFsx5n4BeFb4V1XW4gdpd3cvRJhUNG2sGxDwDCuCNDMBg6YsRp7MEvaGe%0Ao0oBh68YB8CtIWlb%2Bwt%2Fl%2BbXug%3D%3D%0A) Het is mogelijk om rasters in Catenda Hub weer te geven en als u deze in uw Revit model hebt, kunt u in IFC Opties instellen dat rasters in de IFC worden geëxporteerd. Deze worden standaard niet vanuit Revit geëxporteerd.

## 5. **Kleuren en materialen**

De kleuren die in Catenda worden weergegeven, worden gelezen uit het IFC-bestand dat wordt geïmporteerd.

Wanneer de materiaaleigenschap van een familie wordt toegevoegd aan de IFC-parameters, wordt de kleur van het materiaal in de materiaaleigenschap aan de IFC toegevoegd en dus weergegeven in Catenda.

In Revit kunnen materialen in de materiaalweergave worden gevonden:

`Beheer tabblad -> Instellingen sectie -> Materialen`

In de materiaalweergave kunt u de instelling voor kleur vinden in het tabblad Afbeeldingen van het materiaal:

![Beheren -> Materialen -> Materiaalweergave -> Nieuw materiaal maken](https://downloads.intercomcdn.com/i/o/areracg3/1798363404/1016d10e61dcd4bbf3969dd97a39/image.png?expires=1779991200&signature=6538f237377a045f7b7f567244f4fdefd99bc74142dc54780c79610f54b88159&req=dScuHsp4noVfXfMW3nq%2BgRHARe%2BQbSvVJU1tDswOuiSVbxNsRYJibJHNSy4a%0ADvZyAbDR4cFQbN%2FOUhLbnJ9ZKrw%3D%0A)

Het is ook mogelijk om de arcering aan de weergave-instellingen vast te zetten.

![Weergave](https://downloads.intercomcdn.com/i/o/areracg3/1798375002/9394922e0e04c7beffd701083d45/image.png?expires=1779991200&signature=d9d2670f75a1006a4b4d3d03f3e9c19bcfffcafb0d76728976f55be340ebe2c6&req=dScuHsp5mIFfW%2FMW3nq%2BgczmUc51w6Slra%2FB5MdIivv2AVzb0Puu5CECSt7u%0AvMA6oVuMcEZW9opaPvxvO6x6HrE%3D%0A)

Oppervlakken in de Catenda 3D-viewer hebben platte arcering zonder een aanwezige lichtbron.

De volgende waarden worden door Catenda geïnterpreteerd bij het weergeven van het oppervlak in de 3D-viewer:

Generiek

- Kleur
- Afbeelding vervagen
  Transparantie
- Bedrag
- Afbeelding vervagen
- Doorschijnendheid
  Tint
- Tintkleur
