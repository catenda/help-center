# 3D-snapshots

Snapshots beschrijven een plaats en moment in 3D. Ze kunnen worden gebruikt om mensen te laten zien wat u bekijkt, zodat zij dezelfde weergaven kunnen recreëren, niet alleen in Catenda Hub maar ook in hun omgeving. Snapshots kunnen worden gerecreëerd door ze af te spelen in zowel Catenda Hub als in onze plug-ins.

Dit is hoe een Snapshot eruit kan zien in het [commentaar van een topic](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_1ba7f8873f) of in een [Opgeslagen view](https://support.catenda.com/en/articles/8471481-bookmark#h_5c9944a45e). <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/inline-a76bead96c41.png" width="365.48223350253795"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/inline-5a151da0b11e.png" width="272.72727272727275"/> Het topic kan een aantekening boven de afbeelding hebben en de knoppen zien er anders uit. Hoewel Snapshots op verschillende manieren worden gebruikt in topic-opmerkingen en Opgeslagen views, is hun functionaliteit hetzelfde.

## 1. **Snapshot-afbeelding**

### 1.1 **Snapshot-afbeelding in opmerking over onderwerp**

Als u ergens op de afbeelding van een snapshot-opmerking klikt, wordt de afbeelding [uitgebreid weergegeven](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_e36d14edc8), zodat u de inhoud in een groter formaat kunt zien en deze kunt downloaden nadat deze is ingediend. Na het maken van de snapshot en voordat u deze aan het onderwerp toevoegt, kunt u er aantekeningen aan toevoegen.

### 1.2 **Snapshot-afbeelding in opgeslagen view**

Als u ergens op de afbeelding van een snapshot-opgeslagen view klikt, wordt het weergavepunt in de 3D-viewer gerecreëerd conform de manier waarop de opgeslagen view is geconfigureerd toen deze voor het laatst is bijgewerkt.

### 1.3 **Snapshot-afbeelding als bijlage**

De grootte van de afbeelding die is bijgevoegd, is afhankelijk van de grootte van de viewer en het zoomniveau van de browser.

Snapshots zijn de beste manier om afbeeldingen of renderings van hoge kwaliteit te maken vanuit de Catenda Hub-viewer om de volgende redenen:

- Snapshot-afbeeldingen kunnen worden gedownload uit de [bijlage pop-out](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_e36d14edc8) in een opmerking over een onderwerp.
- Snapshot-afbeeldingen kunnen hogere resoluties hebben dan alleen een schermafbeelding van de viewer.

De grootste afbeelding die we tot nu toe hebben zien genereren, was 6417x11113 pixels. Om een snapshot van deze grootte te maken, zijn de volgende instellingen gebruikt:

- 4K-monitorweergave.
- Inhoudspaneel en 3D-paneel zichtbaar.
- Inhoudspaneel zo klein mogelijk.
- Browser in vollscherm.
- Browserschaal 10%
- Weergaveschaal in Windows 100%

Uw pc is mogelijk niet in staat om deze instellingen te verwerken. Pas ze daarom aan uw specificaties aan.

## 2. **Weergavepuntinstellingen**

De volgende instellingen worden onthouden wanneer een snapshot wordt gemaakt. Deze instellingen worden automatisch geconfigureerd wanneer de snapshot opnieuw wordt gemaakt.

### 2.1 **Objecten**

Objecten die dezelfde ID hebben en die waren geselecteerd, verborgen of geïsoleerd, worden geselecteerd, verborgen of geïsoleerd wanneer de snapshot opnieuw wordt gemaakt.

**Nieuwe objecten in revisies** Als u een snapshot opnieuw maakt met de meest recente revisies, kunnen er objecten met nieuwe ID's zijn die nog niet deel van het model waren toen de snapshot werd gemaakt.

Geselecteerd Alleen de objecten die waren geselecteerd toen de snapshot werd gemaakt, worden geselecteerd.

Verborgen Als meer dan de helft van de objecten in een model zichtbaar zijn, worden objecten met nieuwe ID's verborgen.

> **Opmerking:** Dit betekent dat als u een nieuw model toevoegt met de modelselector in een opmerking over een onderwerp-snapshot waarbij meer dan de helft van de objecten in een model zichtbaar zijn, het toegevoegde model volledig verborgen kan zijn. Als u de objecten met nieuwe ID's wilt weergeven, kunt u alles weergeven gebruiken om het model weer te geven nadat u de snapshot opnieuw hebt gemaakt.

Als minder dan de helft van de objecten in een model zichtbaar zijn, worden objecten met nieuwe ID's weergegeven.

Geïsoleerd Alleen de objecten die waren geïsoleerd toen de snapshot werd gemaakt, worden geïsoleerd. Objecten met nieuwe ID's worden weergegeven, maar niet gemarkeerd.

**Selecties** Als [selecties](https://support.catenda.com/en/articles/8238584-information-panel#h_d713a0abb1) zijn aangebracht in het [informatievenster](https://support.catenda.com/en/articles/8238584-information-panel), worden deze onthouden wanneer het weergavepunt wordt afgespeeld. Dit maakt het gemakkelijk om verschillende sets objecten te selecteren. Dit biedt u ook de mogelijkheid om een set objecten een andere kleur te geven dan de standaardkleur van de objecten wanneer u deze normaal opent vanuit de modelsectie.

_Knop Objecten selecteren_ In een opmerking over een onderwerp ziet u een pictogram dat weergeeft hoeveel objecten zijn geconfigureerd om in een snapshot te worden geselecteerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/01-objects.png)

Klik op deze knop om de geconfigureerde objecten in de 3D-viewer te selecteren. Als u de 3D-viewer open hebt, staat deze knop in het hamburgermenu.

### 2.2 **Snijvlakken**

Snijvlakken die in de snapshot zijn geconfigureerd, zijn actief wanneer de snapshot opnieuw wordt gemaakt.

### 2.3 **Revisieselector**

Welke 2D- en 3D-weergaven zijn in- of uitgeschakeld in de [revisieselector](https://support.catenda.com/en/articles/8227211-3d-viewer#h_6c32b713c9). Instellingen voor puntenwolk worden gereproduceerd.

### 2.4 **Rasterkeuzelijst**

Rasters die zijn ingeschakeld in de [rasterkeuzelijst](https://support.catenda.com/en/articles/8227211-3d-viewer#h_b735587e69) worden weergegeven.

### 2.5 **Zichtbaarheidskeuzelijst**

Opties die zijn geconfigureerd met de [zichtbaarheidskeuzelijst](https://support.catenda.com/en/articles/8227211-3d-viewer#h_376dfb4859) worden gereproduceerd.

### 2.6 **Camera-opties**

De camera in de 3D-viewer wordt verplaatst naar de locatie en kijkhoek die in de snapshot zijn ingesteld. Het cameratype dat is ingesteld in de [camera-opties](https://support.catenda.com/en/articles/8227211-3d-viewer#h_02072804a5) wordt gereproduceerd. De schaduwopties die zijn ingesteld in de [camera-opties](https://support.catenda.com/en/articles/8227211-3d-viewer#h_02072804a5) worden gereproduceerd.

### 2.7 **3D-instellingen**

Instellingen zoals gezichtsveld of incrementeel renderen die zijn ingesteld in de [3D-instellingen](https://support.catenda.com/en/articles/5784718-3d-viewer-settings) worden gereproduceerd.

## 3. **Snapshot opnieuw maken**

In Catenda Hub verplaatst de snapshot de camera naar de juiste plaats in onze viewer. In de plug-ins wordt de viewer van de hostsoftware weergegeven.

### 3.1 **Snapshot opnieuw maken met meest recente revisies**

Opgeslagen view - Topic commentaar <p class="intercom-align-center no-margin"><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/inline-63d2b110333a.png" width="60"/> - <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/inline-a628f96ebc54.png" width="104.55445544554455"/></p> Recreëer de Snapshot met de nieuwste versies van de modellen en documenten die in de Snapshot zijn geconfigureerd. Als nieuwe versies van de modellen of bestanden die deel uitmaken van de Opgeslagen view worden geüpload, kan de resulterende weergave in de 3D-viewer iets anders uitzien dan op de afbeelding. Als de Opgeslagen view gedeelde versies heeft, wordt de laatst gepubliceerde versie weergegeven.

### 3.2 **Snapshot opnieuw maken met originele revisies**

Opgeslagen view - Topic commentaar <p class="intercom-align-center no-margin"><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/inline-127de38bdf57.png" width="60"/> - <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/inline-244412c15b6d.png" width="104.72727272727272"/></p> De Snapshot wordt recreëerd met de model- en documentversies die waren geconfigureerd toen de Snapshot werd gemaakt. Zowel gepubliceerde als gedeelde versies van modellen en documenten worden met deze optie weergegeven.

## 4. **Snapshots kopiëren en favoriet markeren**

**Opmerking over onderwerp-snapshot dupliceren** Als u een snapshot wilt kopiëren, speelt u de snapshot af en maakt u een nieuw snapshot in een opgeslagen view of 3D. Met een opgeslagen view is het beter om de + knop te gebruiken, zodat u kunt bijhouden welke opgeslagen view u hebt gedupliceerd.

**Opgeslagen view naar mijn opgeslagen views kopiëren**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/02-copying-and-favoriting-snapshots.png)

Als deze opgeslagen view door een ander lid is aangemaakt, ziet u een +. Hiermee kunt u uw eigen kopie van de opgeslagen view maken die u kunt bewerken en erop filteren. Als u deze opgeslagen view al hebt gekopieerd, wordt deze knop grijs weergegeven en kunt u uw versie [hieronder](https://support.catenda.com/en/articles/8471481-bookmark#h_5c9944a45e) openen. Door een opgeslagen view te kopiëren, kunt u bijhouden welke opgeslagen view u hebt gekopieerd.

**Opgeslagen view als favoriet markeren**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/03-copying-and-favoriting-snapshots.png)

Als u op de ster linksboven op de afbeelding klikt, wordt deze opgeslagen view aan uw dashboard toegevoegd. _Toegang vereist:_ Opgeslagen view-maker

## 5. **Camerapositie instellen**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/04-set-camera-position.png)

Deze knop stelt de camerapositie en kijkhoek in die in de snapshot zijn geconfigureerd. Nadat u de snapshot hebt afgespeeld, wilt u misschien in 3D rondkijken. U kunt deze knop vervolgens gebruiken om terug te springen naar de weergavepositie die in de snapshot is geconfigureerd.

> **Opmerking:** Opmerking: Als u de 3D-viewer geopend hebt, staat deze knop in het hamburgermenu van de opmerking over de onderwerp-snapshot.

## 6. **Snapshot bijwerken**

**Snapshot in opgeslagen view bijwerken**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/05-update-snapshot.png)

Als u wijzigingen in uw snapshot wilt aanbrengen, kunt u deze afspelen, de configuratie wijzigen en de snapshot met deze knop bijwerken.

Voorbeelden waarin dit nuttig kan zijn:

- Een model uit de opgeslagen view toevoegen of verwijderen
- De opgeslagen view gekoppeld houden aan de opgeslagen view van waaruit deze is gekopieerd.
- De koppeling naar de opgeslagen view intact houden.

_Toegang vereist:_ Snapshot-maker

**Opmerking over onderwerp-snapshot bijwerken**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/06-update-snapshot.png)

De knop Modellen geeft aan hoeveel Catenda-modellen aan de snapshot zijn gekoppeld. Hoewel het mogelijk is om de tekst in een opmerking te bewerken, is het niet mogelijk om de afbeeldingsbijlage uit een opmerking te wijzigen of te verwijderen zonder de gehele opmerking te verwijderen. U kunt echter wijzigen welke modellen worden ingeschakeld wanneer het onderwerp opnieuw wordt gemaakt. _Toegang vereist:_ Projectbeheerder

Wanneer een BCF-onderwerp wordt geïmporteerd, worden de ID's van de modellen in het project vergeleken met de ID's van de modellen die in de snapshot zijn geconfigureerd. Alleen de modellen met ID's die aanwezig zijn op het moment van import, worden in de 3D-viewer geladen wanneer de snapshot opnieuw wordt gemaakt.

Als twee modellen dezelfde ID hebben, is alleen het eerste ingeschakeld. Om er zeker van te zijn dat de juiste modellen zijn ingeschakeld, is het belangrijk dat ze elk hun eigen ID hebben. Als u verschillende bestanden uit uw auteurssoftware exporteert, kan het een goed idee zijn om voor elk ander model dat u wilt exporteren, een unieke ID te gebruiken. Hier is een artikel van BuildingSMART dat beschrijft hoe dit in Revit wordt gedaan [https://user.buildingsmart.org/knowledge-base/ifcproject/](https://user.buildingsmart.org/knowledge-base/ifcproject/) Zorg ervoor dat u bijhoudt welke ID u voor welk model hebt gebruikt, zodat toekomstige onderwerpen die worden gemaakt, dit herkennen.

In sommige gevallen wilt u misschien de modellen wijzigen die in de Catenda 3D-viewer worden geladen wanneer de snapshot opnieuw wordt gemaakt:

- Uw model kan worden geïmporteerd nadat u het onderwerp hebt geïmporteerd.
- De objecten in uw model kunnen de juiste ID's bevatten, maar het model zelf kan de verkeerde ID hebben.
- Het onderwerp is voor een specifiek model gemaakt, maar u wilt context zien

Klik op de knop Modellen om het dialoogvenster Modelselectie te openen om te wijzigen welke modellen worden geladen. Het dialoogvenster Modelselectie kan er ongeveer als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/07-update-snapshot.png)

**3D** De modellen met de actieve 3D-knop zijn de modellen die momenteel zijn ingeschakeld in de 3D-viewer. Om een set modellen eenvoudig toe te voegen of te verwijderen, kunt u een opgeslagen view maken, een snapshot opnieuw maken, naar de snapshot gaan die u opnieuw wilt configureren en op Opslaan klikken in het dialoogvenster Modelselectie.

**Selectievakje** Voeg modellen toe of verwijder modellen door ze aan of uit te vinken en klik op de knop Opslaan om een nieuwe configuratie op te slaan.

**Modellen laden** Laad de modellen uit de snapshot naast de modellen die al in de viewer bestaan.

> **Opmerking 1:** In dit menu koppelt u de snapshot alleen aan Catenda-modellen. Dit verandert niet de inhoud van de BCF. **Opmerking 2:** Afhankelijk van de instellingen voor objectzichtbaarheid van de snapshot, kunnen toegevoegde modellen volledig verborgen zijn. Zelfs als ze niet zichtbaar zijn, dient u te kunnen zien dat ze worden geladen wanneer het onderwerp wordt afgespeeld.

## 7. **Snapshoottoegang**

### 7.1 **Toegang tot snapshot in opmerking over onderwerp**

Leden met leestoegang tot het onderwerpenbord kunnen de snapshot zien. Het PDF-export van onderwerpen bevat de snapshot-afbeelding. De BCF-export van het onderwerp bevat de snapshot-afbeelding en -configuratie.

### 7.2 **Opgeslagen views delen**

De [deelconfiguratie](https://support.catenda.com/en/articles/8471481-bookmark#h_5c9944a45e) voor de opgeslagen view

### 7.3 **Privé**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/08-private.png)

_Zichtbaarheid van opgeslagen view:_ Alleen u

### 7.4 **Gedeeld**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/09-shared.png)

_Zichtbaarheid van opgeslagen view:_ Alle projectleden, kunnen met externe personen worden gedeeld via openbare koppeling

## 8. **Openbare koppeling naar opgeslagen view**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/4rm1v3b8/10-public-link-to-bookmark.png)

Als voor deze opgeslagen view een [openbare koppeling](https://support.catenda.com/en/articles/8471481-bookmark#h_b148931acf) is ingeschakeld, kunt u op deze knop klikken om de openbare koppeling op een nieuw tabblad te openen.

## 9. **Een snapshot verwijderen**

### 9.1 **Opmerking over onderwerp-snapshot verwijderen**

Een snapshot die aan een opmerking over een onderwerp is gekoppeld, kan niet uit de opmerking worden verwijderd. Als u de snapshot uit een van uw opmerkingen wilt verwijderen, moet u de gehele opmerking verwijderen. _Toegang vereist:_ Opmerking-maker

Als u de snapshot in een opmerking die door iemand anders is gemaakt, wilt verwijderen, moet het onderwerp naar een gearchiveerd onderwerpenbord worden verplaatst. _Toegang vereist:_ Projectbeheerder

Of het onderwerp kan worden verwijderd. _Toegang vereist:_ Volledige toegang tot het onderwerpenbord

### 9.2 **Snapshot van opgeslagen view verwijderen**

Een opgeslagen view moet een snapshot aan zich hebben gekoppeld en kan niet worden verwijderd. Klik op de opgeslagen view verwijderen in het actiemenu rechtsboven om de hele opgeslagen view te verwijderen. _Toegang vereist:_ Opgeslagen view-maker
