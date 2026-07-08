# Puntenwolken in Catenda Hub

> Ontdek hoe u kunt profiteren van laserscanningen en LIDAR-technologieën in Catenda Hub.

> **Opmerking:** Download een voorbeeldbestand van [hier](https://drive.google.com/file/d/1G8U916oihDl5qHrTfQaVHxDeLsbq1ulG/view?usp=sharing).

Puntenwolkgegevenssets (PC) kunnen in Catenda Hub worden gevisualiseerd. Individuele PC kunnen in het documentgedeelte worden bekeken. Meerdere PC kunnen worden geladen in de [3D Viewer](https://support.catenda.com/en/articles/8227211-3d-viewer). In de 3D Viewer kunnen PC samen worden bekeken met andere 3D-documentindelingen zoals IFC-modellen en GML-bestanden.

Zie hieronder verschillende instellingen voor het weergeven van uw gegevens:

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p>Adaptief - Spars - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-05a450dc777f.png" style="height: auto;" width="3839"/></div></td><td><p>Adaptief - Dicht - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-196a1135014a.png" style="height: auto;" width="3839"/></div></td></tr><tr><td><p>Vast - Dicht - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-66e21551bbef.png" style="height: auto;" width="3834"/></div></td><td><p>Vast - Spars - Intensiteit</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-4a2046c8eaf1.png" style="height: auto;" width="3839"/></div></td></tr></tbody></table></div>

## 1. **Documentgedeelte voorbeeld**

PC-gegevens van de volgende twee bestandsindelingen kunnen in Catenda worden bekeken.

- `\*.e57`
- `\*.las`

PC kan zoals elk ander document in het documentgedeelte worden geüpload. Voor deze twee bestandsindelingen kunnen bestanden tot 25 GB naar het documentgedeelte worden geüpload. Meerdere bestanden kunnen in het documentgedeelte worden geladen en samen in de 3D Viewer worden weergegeven.

### 1.1 **PC-gegevens uploaden**

Het is aanbevolen om de [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) te gebruiken of uw PC-bestand in een gecomprimeerde map te comprimeren en de [zip-import](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) te gebruiken om uw PC te uploaden. Deze methoden helpen u tijd te besparen, omdat de bestandsgrootte voor uploaden kleiner wordt en het risico op netwerkfouten wordt geminimaliseerd, omdat het bestand sneller wordt geüpload.

Nadat u een PC naar het documentgedeelte hebt geüpload, wordt de documentvoorvertoning verwerkt. Tijdens de verwerking van de voorvertoning ziet u boven uw documentvoorvertoning een grijze balk.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/01-uploading-pc-data.png)

De verwerkingsduur van de voorvertoning hangt af van de grootte van de PC. De verwerking duurt 1 uur per GB, maar kan meer of minder zijn, afhankelijk van de puntenwolk.

Zodra de voorvertoning is verwerkt, klikt u op het document om uw PC in de documentvoorvertoning te bekijken:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/02-uploading-pc-data.png)

### 1.2 **Gedeelde PC-revisies**

Als [revision publiceren](https://support.catenda.com/en/articles/9874698-revision-publishing-iso-19650) is geactiveerd voor het project, is de puntenwolk als een gedeelde revisie geüpload. Gedeelde PC-revisies kunnen alleen in het documentgedeelte worden bekeken. Om uw PC in de 3D Viewer te kunnen laden, moet de revisie worden gepubliceerd. Individuele gedeelde revisies kunnen worden gepubliceerd met de publiceeractie in het rechtermenu van de documentvoorvertoning. Meerdere gedeelde revisies kunnen worden gepubliceerd met de actie voor geselecteerde items in de documentstructuur. Wanneer u een revisie publiceert, begint de verwerking van de voorvertoning voor de gepubliceerde revisie.

### 1.3 **Gepubliceerde PC-revisies**

Nadat de voorvertoning van een gepubliceerde PC-revisie is verwerkt, verschijnt er een 3D-knop in de Viewer-kolom van de documentenentabel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/03-br-published-pc-revisions.png)

De 3D-knop laadt de meest recente gepubliceerde revisie van het document in de 3D Viewer.

Als u een of meer Documenten met 3D-Documenten hebt geselecteerd, zoals PC-, IFC- of GML-Documenten, ziet u ook de 3D-Documenten-actie in het menu met acties voor geselecteerde items in de Documenten-tabel. Op deze manier kunt u de meest recente revisies van meerdere 3D-Documenten tegelijk in de 3D Viewer laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/04-br-published-pc-revisions.png)

In een document met ten minste één gepubliceerde PC-revisie die is verwerkt, kunt u de 3D-actie in het actiemenu rechtsboven zien.

> **Opmerking:** De 3D-actie laadt de meest recente gepubliceerde revisie van het document in de 3D Viewer. Zelfs als u naar een vorige revisie kijkt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/05-br-published-pc-revisions.png)

## 2. **3D Viewer-voorbeeld**

Nadat u op de 3D-knop hebt geklikt, beginnen de PC-punten in de 3D Viewer te laden. De 3D-weergave van een PC kan er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/06-3d-viewer-preview.png)

Bovenaan de 3D Viewer is een groene laadbalken te zien. Deze laadbalken geeft aan hoeveel punten voor de huidige cameraweergave en hoek in de 3D Viewer zijn geladen. De laadbalken kan veranderen wanneer u rondopdraait, omdat punten uit beeld kunnen verdwijnen en worden verwijderd, of meer punten in bereik komen en gaan laden.

En na enkele aanpassingen met in- en uitzoomen en positionering kan de PC-voorvertoning er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/07-3d-viewer-preview.png)

## 3. **3D Viewer-instellingen**

In dit gedeelte bekijken we de instellingen in Catenda Hub waarmee u de beste ervaring met uw PC kunt krijgen.

> **Opmerking:** Voordat u de 3D Viewer configureert, moet u ervoor zorgen dat de toepassing Catenda is geconfigureerd [zoals aanbevolen](https://support.catenda.com/en/articles/6921941-hardware-recommendation).

Instellingen die kunnen worden gebruikt om puntenwolken te configureren, bevinden zich op twee locaties.

### 3.1 **1. Puntenbegroting:**

De puntenbegroting kan worden geconfigureerd in de [3D Viewer-instellingen](https://support.catenda.com/en/articles/5784718-3d-viewer-settings), die u kunt vinden in het tandwielpictogram rechtsboven in de 3D Viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/08-1-point-budget.png)

In het menu 3D Viewer-instellingen kan de puntenbegroting worden aangepast van 100.000 tot 10.000.000. Meer punten laden kan meer tijd in beslag nemen en meer middelen van uw systeem eisen. Door meer punten te laden, kan de puntenwolk met hogere getrouwheid worden weergegeven. Bekijk dezelfde weergave met: 100.000 punten

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/09-1-point-budget.png)

1.000.000 punten

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/10-1-point-budget.png)

10.000.000 punten

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/11-1-point-budget.png)

### 3.2 **2. Revisiekiezer en afzonderlijke PC-instellingen:**

Linksboven in de 3D Viewer vindt u de [Revisiekiezer](https://support.catenda.com/en/articles/4670246-accepting-an-invitation-to-join-a-project).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/12-2-revision-selector-and-individual-pc-settings.png)

In [het menu Modellen](https://support.catenda.com/en/articles/4670279-revision-selector#h_180a64490d) kunt u de afzonderlijke [3D-Documenten](https://support.catenda.com/en/articles/4670279-revision-selector#h_fce60074ef) vinden die u in de 3D Viewer hebt geladen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/13-2-revision-selector-and-individual-pc-settings.png)

Puntenwolken kunnen in de revisiekiezer worden geconfigureerd door op het tandwielpictogram te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/14-2-revision-selector-and-individual-pc-settings.png)

Dit is wat het instellingenmenu eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/15-2-revision-selector-and-individual-pc-settings.png)

_Kenmerk_ _RGBA_ - Standaard PC-punten weergeven met hun kleuren

_Intensiteit van kenmerk_ De intensiteitsoptie kan worden gebruikt als de punten geen kleuren bevatten. Bijvoorbeeld wanneer de puntenwolk in een tunnel of een donkere ruimte is vastgelegd.

**Dekking** Wanneer modellen samen met puntenwolken worden weergegeven, kan het nodig zijn om de punten te dimmen voor een beter begrip van het gezichtspunt.

_Puntgrootte_ _Adaptief_ - Standaard Hoe dichter een punt bij de camera is, hoe groter het is. Punten die in beeld zijn, worden in het geheugen geladen. Punten die uit beeld verdwijnen, worden uit het geheugen verwijderd.

> **Opmerking:** Zorg ervoor dat de hardware en software waarop Catenda is geopend, [naar aanbeveling](https://support.catenda.com/en/articles/6921941-hardware-recommendation) is geconfigureerd, omdat dit van invloed kan zijn op het soort puntgroottlading dat uw apparaat aankan.

**Puntgrootte Vaste grootte** Punten die zijn geladen, blijven met deze optie in het geheugen. Met veel punten merkt u dat het draaien kan worden vertraagd en de beweging kan worden vertraagd naarmate u dichterbij het aantal punten komt dat uw systeem aankan. U merkt misschien ook dat het steeds langer duurt om nieuwe punten te laden naarmate u de limiet van uw apparaat nadert. Punten worden eerst het dichtst bij de camera geladen. Voordat u de puntenwolk uit het documentgedeelte laadt, moet u daarom de camera positioneren naar waar u wilt dat de punten worden geladen. Als dit een cameraweergave is die u vaker met deze puntenwolk wilt gebruiken, kunt u overwegen om een Opgeslagen view of een Snapshot in een onderwerp te maken die u kunt afspelen om terug te keren naar deze weergave.

**Dichtheidschuifregeling** De dichtheidschuifregeling helpt u de uiteindelijke instelling te maken. Er is geen regel voor de juiste waarde, dit hangt af van de gegevens die u uploadt (grootte van de gegevensset, puntdichtheid, type scan, enz...). Ons advies: Laad de puntenwolk en wacht even tot voldoende punten worden weergegeven, pas de instellingen daarna zo nodig aan.

[YouTube-video](https://www.youtube.com/embed/n9pztkRPxoc?rel=0)
