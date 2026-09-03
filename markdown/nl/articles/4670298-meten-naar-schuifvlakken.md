# Meten naar schuifvlakken

Dit artikel beschrijft hoe de meetinstrumenten in de 3D-viewer kunnen worden gebruikt om niet alleen objecten te meten, maar ook elementen van schuifvlakken zoals roosters of uitlijningen. Dit is hoe het eruit kan zien na het gebruik van meetinstrumenten zoals de meetlint, puntmeting en lasermeting om te meten tussen annotatielijnen van schuifvlakken, oppervlakken van schuifvlakken en objecten uit modellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/01-intro.png)

## 1. **Aan de slag met meten naar schuifvlakken**

Volg deze stappen om aan de slag te gaan met meten naar schuifvlakken.

### 1.1 **Schuifvlakken bekijken**

Schuifvlakken die kunnen worden gemeten zijn gedefinieerd in de IFC-modellen die beschikbaar zijn gesteld in het project. Als modellen met schuifvlakken beschikbaar zijn, wordt de [vervolgkeuzelijst voor schuifvlakken](https://support.catenda.com/en/articles/4670327-sliding-plane-dropdown) zichtbaar in de rechterbovenhoek van de [3D-viewer](https://support.catenda.com/en/articles/8227211-3d-viewer) en kan er ongeveer zo uitzien:

![Schuifvlak-vervolgkeuzelijst in de 3D-viewer](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/02-previewing-sliding-planes.png)

Bereid de schuifvlakken voor metingen voor door de vervolgkeuzelijst te openen en op de oogknop te klikken om de annotatielijnen van een rooster of een uitlijning in voorbeeld te bekijken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/03-previewing-sliding-planes.png)

### 1.2 **Aanbevolen instellingen voor meten**

Nauwkeurige metingen maken is van cruciaal belang om miscommunicatie in het project te voorkomen. Het is daarom een goed idee om instellingen te controleren voordat u aan metingen begint.

**Instellingen voor 3D-viewer** De vervolgkeuzelijst voor instellingen van de 3D-viewer is te vinden met het tandwielpictogram in de rechterbovenhoek van de 3D-viewer:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/04-recommended-settings-for-measuring.png)

Omdat schuifvlaklijn dunne annotatielijnen en tekst bevatten die vaak gevoelig zijn voor schone weergave in een 3D-omgeving, worden de volgende [instellingen voor 3D-viewer](https://support.catenda.com/en/articles/5784718-3d-viewer-settings#h_16d759320b) aanbevolen om de meetervararing zo goed mogelijk te maken.

**Instellingen voor 3D-viewer - Weergavekwaliteit** Standaardkwaliteit wordt aanbevolen, omdat hoge kwaliteit de verhouding van pixels die door Catenda worden weergegeven ten opzichte van pixels die op het scherm zichtbaar zijn, verandert, wat een negatief effect kan hebben op nauwkeurige metingen.

**Instellingen voor 3D-viewer - Anti-aliasing** Het wordt aanbevolen deze instelling van de standaard FXAA-instelling naar minstens 2x MSAA of meer te wijzigen. Dunne lijnen in 3D zijn vaak lastig weer te geven omdat dunne lijnen des te meer gekarteld raken naarmate ze diagonaler zijn. Het wijzigen van de anti-aliasing-instelling heeft geen effect op de nauwkeurigheid van de meting, maar kan helpen bij het beter zien van de lijnen, omdat de gekartelde randen ervoor kunnen zorgen dat dunne lijnen zo dun worden dat ze moeilijk zichtbaar zijn.

**Instellingen voor 3D-viewer - Grondhoogte** Vooral wanneer u probeert te meten naar een annotatielijnen onder de grond, kan het een goed idee zijn om een omgeving zonder grondvlak te kiezen of het grondvlak onder de hoogte van het schuifvlak te verplaatsen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/05-recommended-settings-for-measuring.png)

**Aanbeveling voor applicatiesoftware** Ongeacht welke [zoomschaal](https://support.catenda.com/en/articles/13927149-application-software-recommendation?q=3d+v) in de browser is ingesteld die voor meting in de 3D-viewer wordt gebruikt, wordt aanbevolen de zoomschaal van de browser niet te wijzigen terwijl u meet, omdat dit kan bijdragen aan het verminderen van de nauwkeurigheid van de meting. Stel de browser in op de gewenste zoomschaal en wees voorzichtig om de pagina na elke zoomschaalaanpassing te vernieuwen, zelfs als de zoomschaalaanpassing op een ander tabblad is gedaan of als deze is teruggezet naar de oorspronkelijke waarde.

## 2. **Meten naar annotatielijnen van schuifvlakken**

Elk van de meetinstrumenten kan worden gebruikt op annotatielijnen van schuifvlakken.

### 2.1 **Snapgedrag**

Wanneer u in de buurt van een annotatielijnen beweegt terwijl het vizier is geactiveerd, zal het vizier naar een annotatielijnen snappen. Wanneer u naar het einde van een annotatielijnen snapt, wordt het middelpunt van het vizier groen. Wanneer u naar het midden van een annotatielijnen snapt, wordt het middelpunt van het vizier rood.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/inline-96b1b8f9c6c8.png" width="290"/> --- <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/inline-d30d54cd3f18.png" width="290"/>

### 2.2 **Lasermeting op annotatielijnen**

Dit is hoe het eruit kan zien wanneer u het lasermeetinstrument op de annotatielijnen van een rooster gebruikt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/06-laser-measure-on-annotation-lines.png)

**Verticaal en horizontaal meten langs het annotatielijnen segment** Merk op dat het vizier plat uitziet in de verticale richting wanneer u een annotatielijnen aanwijst. Bij het meten van annotatielijnen is het het verticale vlak langs de annotatielijnen dat wordt gemeten. De groene lijn is de horizontale lijn op dit vlak en de rode lijn is de verticale lijn op dit vlak en volgt het annotatielijnen segment

Zowel voor de verticale meetlijn (rood) als voor de meetlijn horizontaal langs het segment (groen) gedraagt de meetlijn zich anders afhankelijk van objecten die worden aangetroffen. Als er objecten in één richting langs de meetlijn zijn, wordt een lijn weergegeven die de afstand tot het dichtstbijzijnde object meet. Als er objecten in beide richtingen langs de meetlijn zijn, wordt een lijn weergegeven die de afstand tussen die objecten meet.

**Horizontaal meten onder een schuine hoek naar het annotatielijnen segment** De blauwe lijn is de lijn die kan worden waargenomen onder een schuine hoek naar het annotatielijnen segment dat horizontaal wordt gemeten. Als er objecten in één richting langs de meetlijn zijn, wordt een lijn weergegeven die de afstand tot het dichtstbijzijnde object meet. Als er objecten in beide richtingen zijn, worden lijnen weergegeven die de afstanden tot het dichtstbijzijnde object in elke richting meten, omdat deze lijn zelf de annotatielijnen snijdt en ernaar meet.

**Ontbrekende meting** Als objecten in enige meetrichting ontbreken, worden coördinaten bovendien weergegeven zoals bij puntmeting.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/07-laser-measure-on-annotation-lines.png)

### 2.3 **Meetlint op annotatielijnen**

Het meetlint kan worden gebruikt om te meten van object naar annotatielijnen of van één annotatielijnen naar een ander lijnen. Zoek bijvoorbeeld de afstand tussen twee rasterlijnen door te meten van een punt op een rasterlijnen naar een punt op een ander rasterlijnen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/08-tape-measure-on-annotation-lines.png)

### 2.4 **Puntmeting op annotatielijnen**

Puntmeting kan op annotatielijnen worden gebruikt net als elk ander meetinstrument.

## 3. **Meten naar oppervlakken van schuifvlakken**

Schakel het oppervlak van het schuifvlak in door op de witte cirkel te drukken waar de annotatielijnen cirkel is. Meerdere oppervlakken van schuifvlakken kunnen tegelijk worden geopend. Lasermetingen die op objecten zijn gedaan, kunnen worden uitgebreid tot aan de annotatielijnen. Gebruik vervolgens "Lasermeting" of "Meetlint" om te meten naar ingeschakelde oppervlakken van schuifvlakken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/09-measuring-to-sliding-plane-surfaces.gif)
