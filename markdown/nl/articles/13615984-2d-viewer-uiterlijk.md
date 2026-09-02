# 2D-viewer uiterlijk

Er zijn verschillende manieren om de inhoud van de 2D-viewer naar uw wensen in te stellen.

## 1. **Viewer-objecten**

### 1.1 **Geselecteerde objecten markeren**

De lijnen die voor elke verdieping worden gegenereerd wanneer het model wordt verwerkt, blijven gekoppeld aan het 3D-object dat werd doorgesneden toen de lijnen werden gegenereerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/01-highlighting-selected-objects.png)

Wanneer een object in de 3D-viewer wordt geselecteerd, en een verdieping van dat model is ingeschakeld in de 2D-viewer die werd gegenereerd op de hoogte waar dit object bestaat, wordt het object ook gemarkeerd in de 2D-viewer. Objectslices worden gegenereerd op één meter boven de hoogte die voor elke verdieping in het IFC-bestand is ingesteld. Hoogteverschuivingen zoals de hoogte in IFCSite worden niet in aanmerking genomen.

In het onderstaande voorbeeld bevindt de verdieping "Begane grond" zich op 0 meter. Muren met een basishogte van 0 en verschillende bovenhoogtes worden weergegeven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/02-highlighting-selected-objects.png)

Zoals te zien is, worden alleen de muren die 1 meter en hoger zijn, weergegeven in de 2D-viewer.

### 1.2 **Draaiingen van deuren**

Draaiingen van deuren worden gespecificeerd in het IFC-bestand. U kunt zien hoe dit werkt in de volgende BuildingSMART-artikelen: [IFC 2x3](https://standards.buildingsmart.org/IFC/RELEASE/IFC2x/FINAL/HTML/ifcsharedbldgelements/lexical/ifcdoorstyle.html) [IFC 4](https://standards.buildingsmart.org/IFC/RELEASE/IFC4_1/FINAL/HTML/schema/ifcsharedbldgelements/lexical/ifcdoortypeoperationenum.htm) Als geen draaiing van deuren is gespecificeerd, zwaait de deur naar rechts open.

## 2. **Tekening als ondergrond**

Het is mogelijk om een PDF uit de documentensectie met de [verdiepingconfiguratie](https://support.catenda.com/en/articles/6921756-storey-configurator-page) als ondergrond in te voegen. Dit is met name handig als er objecten boven of onder de hoogte staan waar de 3D-objecten door worden gesneden en die niet in de 2D-viewer worden weergegeven. Voorbeelden hiervan zijn: Kanalen en buizen, Elektra-outlets, Plafondplannen, Weg- en spoorinfrastructuur

## 3. **Markers in de 2D-viewer**

Met [markers ingeschakeld](https://support.catenda.com/en/articles/4854537-2d-viewer#h_381a9d4098) worden onderwerpen met een locatie weergegeven als gekleurde cirkels op een x-y-coördinaat. Dit is wat een 2D-weergave met verschillende markers in de browser kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/03-markers-in-the-2d-viewer.png)

Klik [hier](https://support.catenda.com/en/articles/4854523-2d-location-of-issues) om meer te lezen over de 2D-locatie van onderwerpen.

### 3.1 **Onderwerpen met bestaande markers**

**Marker-interacties -** Beweeg de muis over een marker om het nummer en de titel van het onderwerp van de marker te zien. Klik op de marker om het onderwerp in het onderwerpsbord in het inhoudspaneel te openen. Een marker die tot een geopend onderwerp behoort, wordt groen gemarkeerd.

**Markers weergeven -** Filter en zoek in een onderwerpsbord. Onderwerpen uit het gefilterde resultaat met markers op de voorbereide 2D-viewer worden weergegeven.

### 3.2 **Onderwerpen met nieuwe markers**

Voordat u met markers werkt, moet u ervoor zorgen dat de 2D-viewer is geconfigureerd.

- **Verdiepingen van Model 2D-weergaven -** Kies een verdieping uit een ingeschakelde 2D-weergave als de basishogte. Schakel andere 2D-weergaven in om deze verdieping naast elkaar te bekijken.
- **Verdiepingen van** **Gebouwen -** Kies een verdieping uit een vooraf geconfigureerd gebouw.
  De basishogte en de ingeschakelde 2D-weergaven van geconfigureerde modellen zijn ingeschakeld.

**Marker plaatsen -** Klik met de rechtermuisknop op het canvas en maak een nieuw onderwerp met een marker. Klik op locatie toevoegen in de onderwerpskop in het inhoudspaneel en klik op de locatie waar de marker moet worden toegevoegd.

## 4. **Ruimtelabels in de 2D-viewer**

De ruimtelabels die in het midden van ruimten in de 2D-viewer worden weergegeven, worden bepaald op basis van de beschikbare gegevens in IFC-ruimteobjecten. Deze ruimteobjecten bevatten zowel korte als lange namen, die kunnen worden geconfigureerd om de labelindeling via de instelling **Ruimtenaamindeling** in Catenda te definiëren. Zorg ervoor dat ruimnummers en -oppervlakken nauwkeurig in de IFC-gegevens zijn opgenomen, omdat ontbrekende kenmerken de weergave van gewenste ruimtelabels kunnen beperken.

### 4.1 Problemen met ruimtelabels oplossen:

- Controleer of het IFC-gegevensbestand noodzakelijke kenmerken zoals ruimnummers en -oppervlakten bevat.
- Controleer en pas de instellingen voor "Ruimtenaamindeling" aan zodat deze aansluiten op uw voorkeurslabelconfiguraties. U kunt de instelling vinden in de 2D-viewer 'instellingswiel' in de rechterhoek.
