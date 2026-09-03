# Voeg context toe aan uw projecten met vrij toegankelijke IGN-puntenwolken (HD LiDAR)

Als onderdeel van het [nationale LiDAR HD-programma](https://geoservices.ign.fr/lidarhd) produceert en distribueert IGN 3D-kaarten van de gehele grond en oppervlakte van Frankrijk in LiDAR-gegevens. De verspreide gegevens zijn met name gekalibreerde puntenwolken, onverwerkt of geclassificeerd, en 3D-digitale modellen (DEM, DSM, MNH, enz.). Het is mogelijk met gratis en open-source tools om IGN-puntenwolken (gepubliceerd in `.laz`- en Lambert 93-formaten) om te zetten in .las- of .e57-formaat (leesbaar in onze 3D-viewer) en in het referentiecoördinatensysteem (RCS) dat overeenkomt met uw project.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/01-intro.png)

Volg deze stappen om een contextuele puntenwolk aan uw project toe te voegen!

## 1. **1. Upload uw puntenwolk**

Dit is de gemakkelijkste stap! Download de puntenwolktegel die overeenkomt met de context van uw project via [deze interface](https://cartes.gouv.fr/telechargement/IGNF_NUAGES-DE-POINTS-LIDAR-HD). Voor Zwitserland [biedt Swisstopo](https://www.swisstopo.admin.ch/en/height-model-swisssurface3d?utm_source=chatgpt.com#The-classified-point-cloud-of-Switzerland) ook puntenwolken aan die het hele grondgebied in `.las`-formaat bestrijken.

## 2. **2. Download de open-source software die nodig is om uw puntenwolk om te zetten**

Dit wordt lastig! Om uw puntenwolk om te zetten, moet u deze twee open-source softwareprogramma's installeren:

1. [Miniconda](https://docs.conda.io/en/latest/miniconda.html) is een lichtgewicht versie van de gratis en open-source [Anaconda](https://fr.wikipedia.org/wiki/Anaconda_(distribution_Python)) distributie van de Python- en R-programmeertalen, toegepast op de ontwikkeling van data science-toepassingen.
1. [PDAL](https://pdal.io/en/2.9.2/) is een open-source bibliotheek voor verwerking van puntenwolkgegevens. Het is een beetje zoals een VLC-speler voor puntenwolken ;)

Eigenlijk hebben we de Anaconda Prompt nodig om PDAL te gebruiken, wat zorg draagt voor de transformatie. Laten we gaan 👇

### 2.1 **2.1. Miniconda installeren**

PDAL is afhankelijk van andere bibliotheken, dus de gemakkelijkste manier is om Miniconda (een lichtgewicht versie van Anaconda) te gebruiken.

1. Ga naar de officiële Miniconda-downloadpagina:
   👉 [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)
1. [Download](https://www.anaconda.com/download) de **Miniconda-installatieprogramma voor Windows (64-bits, Python 3.x).**
1. Start het installatieprogramma:
   - Accepteer de licentieovereenkomst
   - Kies "Alleen voor mij" (aanbevolen)
   - Houd de standaard installatielocatie aan
   - Controleer "Miniconda3 aan PATH toevoegen" als de optie wordt aangeboden
1. Nadat u het hebt geïnstalleerd, opent u de Anaconda Prompt (dit is het venster dat u in plaats van CMD/PowerShell voor PDAL zult gebruiken).

### 2.2 **2.2. Maak een Conda-omgeving voor PDAL**

Het wordt aanbevolen om PDAL in zijn eigen omgeving te isoleren. In Anaconda Prompt kopieert en voert u de volgende opdracht uit:

```
conda create -n pdal-env -c conda-forge pdal python=3.10
```

Dit doet drie dingen:

- Maak een omgeving met de naam `pdal-env`
- Installeer PDAL vanuit de **[conda-forge](https://anaconda.org/conda-forge/pdal)**-opslagplaats (meest recente versie)
- Python installeren (nuttig als u PDAL ook in uw Python-scripts wilt gebruiken)

### 2.3 Activeer de PDAL-omgeving

Nog steeds in de Anaconda Prompt, activeer de omgeving alvorens PDAL te gebruiken door het volgende uit te voeren:

```
conda activate pdal-env
```

Nu zou elke pdal-opdracht deze omgeving moeten gebruiken. (Als u de terminal sluit, voert u conda `activate pdal-env` opnieuw uit wanneer u deze opnieuw opent.)

### 2.4 Controleer de installatie

Voer uit:

```
pdal --version pdal --drivers
```

Als een versie wordt weergegeven en een lijst met "readers.\* / filters.\* / writers.\*" verschijnt, is PDAL geïnstalleerd. ✅ Controleer of writers.las in de lijst staat als u naar .las wilt exporteren. Hetzelfde voor het `.e57`-formaat dat ook door Catenda Hub wordt ondersteund ;)

## 3. Transform uw puntenwolk

We zijn er bijna! Nog maar een paar stappen...

### 3.1 Identificeer de EPSG-code van uw coördinaatreferentiesysteem (CRS)

Om uw puntenwolk om te zetten in PDAL, moet u de EPSG-code kennen die overeenkomt met het coördinatensysteem van uw IFC-model. Hier is een niet-uitputtende lijst van SCR's die het metropolitaanse Frankrijk en hun respectieve EPSG-codes bestrijken.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="width: 209px; padding: 8px;"><p>Naam</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; padding: 8px;"><p>EPSG</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>Opmerking</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert-93</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2154</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>De standaard voor metropolitaan Frankrijk, gebruikt voor IGN-puntenwolken. Dekt het hele grondgebied.</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC42</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3942</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Voor zone 1 (Corsica).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC43</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3943</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Voor zone 2 (zuiden bij 44° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC44</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3944</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Voor zone 3 (43° N tot 45° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC45</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3945</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Voor zone 4 (44° N tot 46° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC46</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3946</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Voor zone 5 (45° N tot 47° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC47</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3947</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Voor zone 6 (46° N tot 48° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC48</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3948</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Voor zone 7 (47° N tot 49° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC49</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3949</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Voor zone 8 (48° N tot 50° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC50</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3950</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Voor zone 9 (noord bij 49° N).</p></td></tr></tbody></table></div>

![File:Departements LambertCC9Zones.svg - Wikimedia Commons](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/02-3-1-identify-the-epsg-code-of-your-coordinate-reference-system-crs.png)

### 3.2 Transform uw puntenwolk met Anaconda en PDAL

Nu we de beroemde EPSG-code kennen die overeenkomt met de SCR van ons project, kunnen we EINDELIJK onze puntenwolk transformeren

Hier is een voorbeeld van een opdracht waarmee u uw puntenwolk kunt transformeren:

```
pdal translate ^ "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz" ^ "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.las" ^ reprojection ^ --filters.reprojection.in_srs="EPSG:2154" ^ --filters.reprojection.out_srs="EPSG:3943"
```

🤓 Laten we deze opdracht analyseren:

1. `pdal translate` is de hoofdopdracht voor het uitvoeren van de transformatie.
1. `"C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz"` is het pad naar het `.laz`-bestand dat uit de IGN-database is gedownload.
1. `"C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz`" is het pad waar het toekomstige `.las`-bestand wordt gemaakt.
1. de reprojection command -`-filters.reprojection.in_srs="EPSG:2154" --filters.reprojection.out_srs="EPSG:3943"` stelt u in staat om de puntenwolk van het Lambert-93 SCR (`EPSG:2154`) naar het CC43 SCR (`3943`) om te projecteren

Kopieer de opdracht en vervang eenvoudig de EPSG-paden en codes in invoer en uitvoer. Zodra de opdracht is uitgevoerd, wordt uw nieuwe .las-bestand gegenereerd op de locatie die is opgegeven in het doelpad.

IGN-puntenwolken zijn standaard niet gekleurd, maar er zijn opdrachten in PDAL om kleuren toe te voegen op basis van puntverhoging of door gebruik te maken van een geogerefereerde .tif-orthofoto met dezelfde CRS. De open-source software QGIS maakt het gemakkelijk om geogerefereerde orthofoto's te genereren.

Hier is dezelfde opdracht met een colorization filter die verwijst naar een orthofoto:

```
pdal translate "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz" ^ "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.las" ^ reprojection ^ --filters.reprojection.in_srs="EPSG:2154" ^ --filters.reprojection.out_srs="EPSG:3943" ^ colorization ^ --filters.colorization.raster="C:\Users\USERNAME\Downloads\Orthophoto.tif" ^ --filters.colorization.dimensions="Red:1,Green:2,Blue:3"
```

### 3.3 Upload uw puntenwolk naar uw Catenda Hub-project

Zodra de transformatie is voltooid (naar de CRS van uw project en in `.las`- of `.e57`-formaat), hoeft u alleen maar uw puntenwolk naar uw Catenda Hub-project te uploaden! Als u alle stappen correct hebt gevolgd, moet deze perfect aansluiten bij uw project :)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/03-3-3-upload-your-point-cloud-to-your-catenda-hub-project.png)
