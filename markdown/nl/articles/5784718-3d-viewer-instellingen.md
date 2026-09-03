# 3D Viewer-instellingen

De 3D Viewer-instellingen zijn te vinden in de rechterbovenhoek van de [3D Viewer](https://support.catenda.com/en/articles/8227211-3d-viewer).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/01-intro.png)

> **Opmerking:** Zorg ervoor dat de hardware en software waarop Catenda is geopend [volgens aanbeveling](https://support.catenda.com/en/articles/6921941-hardware-recommendation) zijn geconfigureerd, omdat dit van invloed kan zijn op hoe de Viewer wordt weergegeven.

## 1. **De 3D Viewer inschakelen**

De 3D Viewer kan op een van de volgende manieren worden geopend: Schakel het 3D-paneel in met de paneelknoppen in de rechterbovenhoek (Shift + 2).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/02-enabling-the-3d-viewer.png)

Een 3D-model inschakelen vanaf de Dashboard-pagina.

Een 3D-model inschakelen vanuit de Viewer-kolom in de modelstabel. (Bovenstaande afbeelding)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/03-enabling-the-3d-viewer.png)

Selecteer modellen op de modelpagina en gebruik de 3D-actie met geselecteerde modellen op de modelpagina.

Schakel een 3D-document in vanuit de Viewer-kolom in de documenttabel op de documentenpagina. Klik op het tandwielpictogram om de **3D Viewer-instellingen** weer te geven

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/04-enabling-the-3d-viewer.png)

## 2. **Rendering**

Dit is wat het renderingmenu eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/05-rendering.png)

### 2.1 **Ruimten tonen**

_Standaard uit_ - [Ruimten inschakelen en uitschakelen](https://support.catenda.com/en/articles/4670315-how-can-i-show-spaces-in-catenda-hub). Ruimten kunnen nog steeds worden geselecteerd in de 2D Viewer als deze in het model voorkomen.

### 2.2 **Weergavekwaliteit**

De verhouding tussen het aantal pixels dat de viewport zegt weer te geven en het aantal pixels dat fysiek deel uitmaakt van uw scherm is vaak hetzelfde. In dat geval maakt de weergavekwaliteitsoptie niet veel verschil. Als het aantal pixels dat de viewport heeft en het aantal pixels waar de viewport op een scherm wordt weergegeven verschillend is, kan de weergavekwaliteit de scherpte van de afbeelding beïnvloeden. Voor schermen van de volgende typen kan de verhouding tussen het aantal pixels dat de viewport heeft en het aantal pixels dat het scherm werkelijk heeft verschillend zijn:

- Mobiele apparaten
- Weergavetechnologieën die de pixeldichtheid beïnvloeden, zoals Apple Retina.
- Displays met hoge DPI

> **Opmerking:** Zorg ervoor dat de hardware en software waarop Catenda is geopend [volgens aanbeveling](https://support.catenda.com/en/articles/6921941-hardware-recommendation) zijn geconfigureerd, omdat dit van invloed kan zijn op de pixelafzetting van de Viewer.

**Standaardkwaliteit** Met de standaard weergavekwaliteit zijn de pixels die de viewport heeft hetzelfde aantal fysieke pixels dat de viewport op het scherm weergeeft. Voor schermen die de mogelijkheid bieden om de viewport over meer fysieke pixels weer te geven dan de viewport zegt dat het heeft, kan deze instelling ertoe leiden dat de afbeelding minder nauwkeurig lijkt. Deze modus is sneller en minder veeleisend voor uw apparaat.

**Hoge kwaliteit** Met de hoge weergavekwaliteit wordt de viewport weergegeven over de volledige hoeveelheid fysieke pixels die beschikbaar zijn op het deel van het scherm dat de viewport weergeeft. Voor schermen waarmee de viewport over meer pixels kan worden weergegeven dan het zegt, biedt dit de beste visuele kwaliteit, maar kan het meer vereisend zijn voor prestaties.

### 2.3 **Anti-aliasing**

Pixelnauwkeurigheid bij het afvlakken van diagonale lijnen in volgorde van nauwkeurigheid. Houd er rekening mee dat hoe nauwkeuriger, hoe moeilijker het voor het systeem is om weer te geven.

- FXAA
- 2x MSAA
- 4x MSAA
- 8x MSAA

> **Opmerking:** Zorg ervoor dat de hardware en software waarop Catenda is geopend [volgens aanbeveling](https://support.catenda.com/en/articles/6921941-hardware-recommendation) zijn geconfigureerd, omdat dit van invloed kan zijn op de nauwkeurigheid van diagonale lijnen.

### 2.4 **Stapsgewijze rendering**

Tijdens het roteren worden niet-essentiële objecten zoals glas in ramen en kleine onderdelen tijdelijk verborgen om de prestaties te verbeteren. Dit maakt het mogelijk om in enorme modellen met weinig vertraging te roteren. Wanneer veel objecten in de 3D Viewer zijn geladen, is deze optie een must.

### 2.5 **Modelschaduwen**

Wanneer deze optie is ingeschakeld, worden schaduwen met een straal van ongeveer 5 cm weergegeven tussen de overlapping van objecten. Zorg ervoor dat uw objecten op ware grootte zijn voor een beter effect. Bij grote oppervlakken, zoals waar een muur een vloer ontmoet, is dit niet erg zichtbaar totdat de camera dicht bij het snijpunt beweegt. Bij kleine geometrie zoals meubels, staalliggers en metalen fittingen is dit een game changer. Deze optie heeft meestal weinig effect op de prestaties.

### 2.6 **Uitgebreid zichtbereik**

Bij massieve modellen die meerdere kilometers lang zijn, eindigen objecten vaak buiten de standaard clipping-afstand van 2 kilometer. Wanneer het model is ingeschakeld, probeert de camera zichzelf ver genoeg weg te positioneren om alles weer te geven, en als de objecten ver genoeg weg zijn, kunnen ze worden geknipt en wordt er niets weergegeven totdat de camera dicht bij de objecten komt. Met deze optie worden objecten tot 50 kilometer van de camera zichtbaar! Houd er rekening mee dat dit de prestaties kan beïnvloeden. In infrastructuurprojecten is deze optie vaak een must!

### 2.7 **Doorschijnende dekking**

_5% Standaard_ - Hoeveel u door doorschijnende objecten kunt zien

### 2.8 **Puntwolk-instellingen**

Puntbudget: _1000000 Standaard_ - Hoeveel punten van de puntwolk tegelijk kunnen worden weergegeven. De standaardwaarde is meer dan voldoende voor de meeste puntenwolken, maar de instelling is daar voor het geval er meer nodig is.

## 3. **Navigatie**

Dit is wat het navigatiemenu eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/06-navigation.png)

### 3.1 **Loopmodus**

_1,6 meter standaard_ - Bindt de Viewer aan de grond eronder wanneer u door het model loopt met doorloopfunctie. Hiermee kunt u trappen op lopen.

### 3.2 **Loopsnelheid**

_3 m/s Standaard_ - Hoe snel de Viewer in doorloopfunctie beweegt. Ter referentie is hieronder een tabel met algemene snelheden opgenomen.

### 3.3 **Hoogtesnelheid**

_1,5 m/s Standaard_ - Verticale bewegingssnelheid bij omhoog en omlaag bewegen met X en C.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Vervoermethode</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Typische snelheid (m/s)</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Typische snelheid (mph)</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lopen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>1,5</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3,4</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Standaard</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>6,7</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Hardlopen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>5</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>11</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Fietsen</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>7</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>15</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Auto</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>13 - 30</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>29 - 67</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Trein</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>56</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>125</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vliegtuig</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>250</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>560</p></td></tr></tbody></table></div>

### 3.4 **Rotatiesnelheid**

_40°/s Standaard_ - Hoe snel de Viewer rond de camera draait wanneer u op het scherm sleept

### 3.5 **Kijkhoek**

_60° Standaard_ - Deze instelling kan goed zijn om groter te maken in binnenruimten zoals kleine kamers zodat u meer kunt zien. Het kan ook goed zijn om deze instelling in modellen met grote afstanden van 2 km (1,2 mijl) en meer te beperken, omdat u objecten die verder weg zijn nauwkeuriger kunt zien.

### 3.6 **Navigatie-instellingen resetten**

Stel alle navigatie-instellingen opnieuw in op hun standaardpositie

## 4. **Omgeving**

Dit is wat het omgevingsmenu eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/07-environment.png)

### 4.1 **Omgevingsinstelling**

De gekozen omgevingsinstellingen bepalen welke lucht wordt weergegeven bij het opkijken en welke grond bij het neerkijken. Merk op dat de horizon vaak meer uitgesproken is wanneer de perspectief weergaveoptie is gekozen, omdat met het orthogonale gezichtspunt de horizon oneindig ver weg is, dus deze wordt alleen gezien wanneer de camera exact in de horizontale richting kijkt.

**Helder** Met de heldere instelling worden een heldere hemel bij het opkijken en een grasachtig grondvlak bij het neerkijken in de achtergrond van de viewport weergegeven.

**Gedeeltelijk bewolkt** Met de gedeeltelijk bewolkte instelling worden een bewolkte hemel bij het opkijken en een grasachtig grondvlak bij het neerkijken in de achtergrond van de viewport weergegeven.

**Neutraal** Met de neutrale instelling worden een lichtgrijze hemel bij het opkijken en een donkergrijs grondvlak bij het neerkijken in de achtergrond van de viewport weergegeven. Deze instelling is geweldig voor modellen met lichte kleuren die moeilijk van een lichte achtergrond te onderscheiden zijn.

**Geen** Met de instelling Geen wordt een verloop weergegeven dat overgaat van een lichtgroene lucht bij het opkijken naar een wit grondvlak bij het neerkijken in de achtergrond van de viewport.

### 4.2 **Peilhoogte maaiveld**

De opties voor peilhoogte maaiveld zijn grijs voor de instelling Geen, omdat deze geen grondvlak hebben. In instellingen waar het grondvlak wordt weergegeven, wordt een oppervlak zichtbaar op een bepaalde hoogte die schaduwen ontvangt van objecten die in de 3D Viewer zijn geladen.

_Onder model -_ Standaard Met deze optie wordt het grondvlakoppervlak weergegeven op een hoogte van 0 meter boven het zeeniveau.

_Op hoogte_ Met deze optie kan het grondvlakoppervlak omhoog worden verplaatst met positieve waarden en omlaag met negatieve waarden. Dit is geweldig in situaties waarbij het oppervlak door een kelder wordt geknipt of voor objecten die anderszins onder het zeeniveau liggen.
