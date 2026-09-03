# Puntenwolken in Catenda Hub

> Ontdek hoe je kunt profiteren van laserscans en LIDAR-technologieën in Catenda Hub.

> **Opmerking:** Download een voorbeeldbestand van [hier](https://drive.google.com/file/d/1G8U916oihDl5qHrTfQaVHxDeLsbq1ulG/view?usp=sharing).

Puntenwolkdatasets (PC) kunnen in Catenda Hub worden weergegeven. Individuele PC kunnen in het documentgebied worden weergegeven. Meerdere PC kunnen in de [3D-viewer](https://support.catenda.com/en/articles/8227211-3d-viewer) worden geladen. In de 3D-viewer kunnen PC samen met andere 3D-documentindelingen zoals IFC-modellen en GML-bestanden worden weergegeven.

Zie hieronder verschillende instellingen om uw gegevens weer te geven:

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="padding: 8px;"><p>Adaptief - Dun - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-05a450dc777f.png" style="height: auto;" width="3839"/></div></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>Adaptief - Dicht - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-196a1135014a.png" style="height: auto;" width="3839"/></div></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vast - Dicht - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-66e21551bbef.png" style="height: auto;" width="3834"/></div></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vast - Dun - Intensiteit</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-4a2046c8eaf1.png" style="height: auto;" width="3839"/></div></td></tr></tbody></table></div>

## 1. **Documentgebied voorbeeld**

PC-gegevens van de volgende twee bestandsindelingen kunnen in Catenda worden weergegeven.

- `*.e57`
- `*.las`

PC kan net als elk ander document in het documentgebied worden geüpload. Voor deze twee bestandsindelingen kunnen bestanden tot 25 GB naar het documentgebied worden geüpload. Meerdere bestanden kunnen in het documentgebied worden geladen en samen in de 3D-viewer worden weergegeven.

### 1.1 **PC-gegevens uploaden**

Het is raadzaam om de [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) te gebruiken of uw PC-bestand in een gecomprimeerde map te comprimeren en de [zip-import](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) te gebruiken om uw PC te uploaden. Deze methoden helpen u tijd besparen omdat de uploadbestandsgrootte kleiner is en het risico op een netwerkfout wordt geminimaliseerd, omdat het bestand sneller wordt geüpload

Nadat u een PC naar het documentgebied hebt geüpload, wordt de documentvoorbeeldverwerking gestart. Terwijl de voorbeeldverwerking plaatsvindt, ziet u een grijze balk aan de bovenkant van uw documentvoorbeeld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/01-uploading-pc-data.png)

De verwerkingsduur van het voorbeeld hangt af van de grootte van de PC. De verwerking duurt 1 uur per GB, maar kan meer of minder zijn, afhankelijk van de puntenwolk.

Nadat de preview is verwerkt, klikt u op het document om uw PC in het documentvoorbeeld weer te geven:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/02-uploading-pc-data.png)

### 1.2 **Gedeelde PC-revisies**

Als [revisiepublicatie](https://support.catenda.com/en/articles/9874698-revision-publishing-iso-19650) voor het project is geactiveerd, is de puntenwolk als een gedeelde revisie geüpload. Gedeelde PC-revisies kunnen alleen in het documentgebied worden weergegeven. Om uw PC in de 3D-viewer te kunnen laden, moet de revisie worden gepubliceerd. Individuele gedeelde revisies kunnen worden gepubliceerd met de publicatieactie in het rechtermenu van het documentvoorbeeld. Meerdere gedeelde revisies kunnen worden gepubliceerd met de actie geselecteerde items in de documentstructuur. Wanneer u een revisie publiceert, wordt de preview voor de gepubliceerde revisie verwerkt.

### 1.3 **Gepubliceerde PC-revisies**

Nadat het voorbeeld van een gepubliceerde PC-revisie is verwerkt, verschijnt er een 3D-knop in de viewerkolom van de documenttabel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/03-br-published-pc-revisions.png)

De 3D-knop laadt de nieuwste gepubliceerde revisie van het document in de 3D-viewer.

Als u een of meer documenten met 3D-documenten hebt geselecteerd, zoals PC-, IFC- of GML-documenten, ziet u ook de actie 3D-documenten in het menu met geselecteerde itemacties in de documenttabel. Op deze manier kunt u de nieuwste revisies van meerdere 3D-documenten tegelijk in de 3D-viewer laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/04-br-published-pc-revisions.png)

In een document met minimaal één gepubliceerde PC-revisie die is verwerkt, kunt u de 3D-actie in het actiemenu rechtsboven zien.

> **Opmerking:** De 3D-actie laadt de nieuwste gepubliceerde revisie van het document in de 3D-viewer. Zelfs als u naar een vorige revisie kijkt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/05-br-published-pc-revisions.png)

## 2. **3D-viewervoorbeeld**

Nadat u op de 3D-knop hebt geklikt, beginnen de PC-punten in de 3D-viewer te laden. De 3D-weergave van een PC kan er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/06-3d-viewer-preview.png)

Aan de bovenkant van de 3D-viewer is een groene voortgangsbalk te zien. Deze voortgangsbalk geeft aan hoeveel punten in de 3D-viewer voor de huidige camerastand en -hoek zijn geladen. De voortgangsbalk kan veranderen als u rondroteren, omdat punten uit beeld kunnen verdwijnen en uit het geheugen kunnen worden verwijderd of meer punten in bereik kunnen komen en beginnen in te laden.

En na enkele aanpassingen met zoomen en positionering kan het PC-voorbeeld er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/07-3d-viewer-preview.png)

## 3. **3D-viewerinstellingen**

In deze sectie kijken we naar de instellingen in Catenda Hub waarmee u de beste ervaring met uw PC kunt krijgen.

> **Opmerking:** Zorg er vóór het configureren van de 3D-viewer voor dat de toepassing Catenda is geopend en is ingesteld [zoals aanbevolen](https://support.catenda.com/en/articles/6921941-hardware-recommendation).

Instellingen die kunnen worden gebruikt voor het configureren van puntenwolken bevinden zich op twee plaatsen.

### 3.1 **1. Puntbegroting:**

De puntbegroting kan worden ingesteld in de [3D-viewerinstellingen](https://support.catenda.com/en/articles/5784718-3d-viewer-settings) die u kunt vinden in het tandwielpictogram rechtsboven in de 3D-viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/08-1-point-budget.png)

In het menu 3D-viewerinstellingen kan de puntbegroting van 100.000 tot 10.000.000 worden aangepast. Het laden van meer punten kan meer tijd in beslag nemen en meer resources van uw systeem vereisen. Door meer punten in te laden, kan de puntenwolk met hogere getrouwheid worden weergegeven. Zie dezelfde weergave met: 100.000 punten

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/09-1-point-budget.png)

1.000.000 punten

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/10-1-point-budget.png)

10.000.000 punten

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/11-1-point-budget.png)

### 3.2 **2. Revisieselector en individuele PC-instellingen:**

Linksbovenaan de 3D-viewer vindt u de [Revisieselector](https://support.catenda.com/en/articles/4670246-accepting-an-invitation-to-join-a-project).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/12-2-revision-selector-and-individual-pc-settings.png)

In [het menu Modellen](https://support.catenda.com/en/articles/4670279-revision-selector#h_180a64490d) kunt u de individuele [3D-documenten](https://support.catenda.com/en/articles/4670279-revision-selector#h_fce60074ef) vinden die u in de 3D-viewer hebt geladen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/13-2-revision-selector-and-individual-pc-settings.png)

Puntenwolken kunnen in de revisieselector worden ingesteld door op het tandwielpictogram te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/14-2-revision-selector-and-individual-pc-settings.png)

Dit is wat het instellingenmenu kan lijken:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/15-2-revision-selector-and-individual-pc-settings.png)

_Attribuut_ _RGBA_ - Standaard PC-punten weergeven met hun kleuren

_Attribuut Intensiteit_ De intensiteitsoptie kan worden gebruikt als de punten geen kleuren bevatten. Bijvoorbeeld wanneer de puntenwolk in een tunnel of donkere ruimte is vastgelegd.

**Dekking** Wanneer modellen samen met puntenwolken worden weergegeven, kan het nodig zijn om de punten te dimmen voor een beter inzicht in het viewpoint.

_Puntgrootte_ _Adaptief_ - Standaard Hoe dichter een punt bij de camera staat, hoe groter het is. Punten die in zicht zijn, worden in het geheugen geladen. Punten die uit het zicht gaan, worden uit het geheugen verwijderd.

> **Opmerking:** Zorg ervoor dat de hardware en software waarop Catenda is geopend, zijn ingesteld [zoals aanbevolen](https://support.catenda.com/en/articles/6921941-hardware-recommendation), omdat dit van invloed kan zijn op het soort puntgrootte dat uw apparaat kan verwerken.

**Puntgrootte Vaste grootte** Punten die zijn geladen, blijven in het geheugen staan met deze optie. Met veel punten merkt u dat rotaties kunnen worden vertraagd en beweging kan worden vertraagd naarmate u dicht bij het aantal punten komt dat uw systeem aankan. U merkt mogelijk ook dat het steeds langer duurt om nieuwe punten in te laden naarmate u dichter bij de limiet van uw apparaat komt. Punten worden eerst dicht bij de camera geladen. Zorg er voordat u de puntenwolk uit het documentgebied laadt voor dat u de camera op de plaats positioneert waar u de punten wilt laden. Als dit een camerastand is die u vaker met deze puntenwolk wilt gebruiken, overweeg dan om een bladwijzer of een snapshot in een topic te maken die u kunt afspelen om naar deze positie terug te keren.

**Puntdichtheid-schuifregelaar** De dichtheidschuifregelaar helpt u de definitieve instelling te bepalen. Er is geen regel voor de juiste waarde, dit hangt af van de gegevens die u uploadt (grootte van de dataset, puntdichtheid, type scan, enz.). Ons advies: Laad de puntenwolk en wacht even tot voldoende punten worden weergegeven. Pas vervolgens indien nodig de instellingen aan.

[YouTube-video](https://www.youtube.com/embed/n9pztkRPxoc?rel=0)
