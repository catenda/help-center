# Legg til kontekst til prosjektene dine med fritt tilgjengelige IGN-punktskyer (HD LiDAR)

Som del av [nasjonalt LiDAR HD-program](https://geoservices.ign.fr/lidarhd), produserer og distribuerer IGN 3D-kartlegging av hele bakken og overflaten av Frankrike i LiDAR-data. Dataene som distribueres er særlig rekalibrerte punktskyer, rå eller klassifisert, og 3D digitale modeller (DEM, DSM, MNH, osv.). Det er mulig med gratis og åpen kildekode-verktøy å transformere IGN-punktskyene (publisert i `.laz` og Lambert 93-formater) til .las eller .e57-format (leselig i vår 3D-viser) og til referansekoordinatsystemet (RCS) som tilsvarer prosjektet ditt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/01-intro.png)

Følg disse trinnene for å legge til en kontekstpunktskyе til prosjektet ditt!

## 1. **1. Last opp punktskyen din**

Dette er det enkleste trinnet! Last ned punktskytilen som tilsvarer konteksten til prosjektet ditt via [dette grensesnittet](https://cartes.gouv.fr/telechargement/IGNF_NUAGES-DE-POINTS-LIDAR-HD). For Sveits tilbyr Swisstopo [også](https://www.swisstopo.admin.ch/en/height-model-swisssurface3d?utm_source=chatgpt.com#The-classified-point-cloud-of-Switzerland) punktskyer som dekker hele territoriet i `.las`-format.

## 2. **2. Last ned åpen kildekode-programvaren som kreves for å transformere punktskyen din**

Det er her det blir komplisert! For å transformere punktskyen din, må du installere disse to åpen kildekode-programmene:

1. [Miniconda](https://docs.conda.io/en/latest/miniconda.html) er en lettere versjon av den gratis og åpen kildekode [Anaconda](https://fr.wikipedia.org/wiki/Anaconda_(distribution_Python))-distribusjonen av Python og R programmeringsspråk, brukt til utvikling av datavitenskaplige applikasjoner.
1. [PDAL](https://pdal.io/en/2.9.2/) er et åpen kildekode-bibliotek for behandling av punktskydata. Det er litt som en VLC-spiller for punktskyer ;)

Faktisk trenger vi Anaconda-ledeteksten for å bruke PDAL, som vil ta seg av transformasjonen. La oss gå 👇

### 2.1 **2.1. Installer Miniconda**

PDAL avhenger av andre biblioteker, så den enkleste måten er å bruke Miniconda (en lettere versjon av Anaconda).

1. Gå til den offisielle Miniconda-nedlastingssiden:
   👉 [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)
1. [Last ned](https://www.anaconda.com/download) **Miniconda-installatøren for Windows (64-bit, Python 3.x).**
1. Start installatøren:
   - Godta lisensavtalen
   - Velg "Bare for meg" (anbefalt)
   - Behold standard installasjonssted
   - Merk av "Legg til Miniconda3 til PATH" hvis alternativet tilbys
1. Når installasjonen er fullført, åpner du Anaconda-ledeteksten (dette er vinduet du skal bruke i stedet for CMD/PowerShell for PDAL).

### 2.2 **2.2. Opprett et Conda-miljø for PDAL**

Det anbefales å isolere PDAL i sitt eget miljø. I Anaconda Prompt kopierer og kjører du følgende kommando:

```
conda create -n pdal-env -c conda-forge pdal python=3.10
```

Dette gjør tre ting:

- Opprett et miljø kalt `pdal-env`
- Installer PDAL fra **[conda-forge](https://anaconda.org/conda-forge/pdal)**-depotet (siste versjon)
- Installering av Python (nyttig hvis du også vil bruke PDAL i Python-skriptene dine)

### 2.3 Aktiver PDAL-miljøet

Fortsatt i Anaconda Prompt, før du bruker PDAL, aktiverer du miljøet ved å kjøre:

```
conda activate pdal-env
```

Nå skal enhver pdal-kommando bruke dette miljøet. (Hvis du lukker terminalen, kjør conda `activate pdal-env` igjen når du åpner den på nytt.)

### 2.4 Sjekk installasjonen

Kjør:

```
pdal --version pdal --drivers
```

Hvis en versjon vises og en liste over "readers.\* / filters.\* / writers.\*" vises, er PDAL installert. ✅ Sjekk at writers.las er i listen hvis du vil eksportere til .las. Det samme gjelder for `.e57`-formatet som også støttes av Catenda Hub ;)

## 3. Transformer punktskyen din

Vi er nesten der! Bare noen få trinns til...

### 3.1 Identifiser EPSG-koden for ditt koordinatreferansesystem (CRS)

For å transformere punktskyen din til PDAL, må du vite EPSG-koden som tilsvarer koordinatsystemet til IFC-modellen din. Her er en ikke-uttømmende liste over SCR-er som dekker det kontinentale Frankrike og deres respektive EPSG-koder.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="width: 209px; padding: 8px;"><p>Navn</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; padding: 8px;"><p>EPSG</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>Merknader</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert-93</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2154</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Standarden for det kontinentale Frankrike, brukt for IGN-punktskyer. Dekker hele territoriet.</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC42</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3942</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>For sone 1 (Korsika).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC43</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3943</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>For sone 2 (sør ved 44° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC44</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3944</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>For sone 3 (43° N til 45° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC45</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3945</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>For sone 4 (44° N til 46° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC46</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3946</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>For sone 5 (45° N til 47° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC47</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3947</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>For sone 6 (46° N til 48° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC48</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3948</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>For sone 7 (47° N til 49° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC49</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3949</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>For sone 8 (48° N til 50° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC50</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3950</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>For sone 9 (nord ved 49° N).</p></td></tr></tbody></table></div>

![File:Departements LambertCC9Zones.svg - Wikimedia Commons](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/02-3-1-identify-the-epsg-code-of-your-coordinate-reference-system-crs.png)

### 3.2 Transformer punktskyen din ved hjelp av Anaconda og PDAL

Nå som vi vet den berømte EPSG-koden som tilsvarer SCR for prosjektet vårt, kan vi ENDELIG transformere punktskyen vår

Her er et eksempel på en kommando som lar deg transformere punktskyen din:

```
pdal translate ^ "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz" ^ "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.las" ^ reprojection ^ --filters.reprojection.in_srs="EPSG:2154" ^ --filters.reprojection.out_srs="EPSG:3943"
```

🤓 La oss dele opp denne kommandoen:

1. `pdal translate` er hovedkommandoen for å utføre transformasjonen.
1. `"C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz"` er stien til `.laz`-filen som er lastet ned fra IGN-databasen.
1. `"C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz`" er stien hvor den fremtidige `.las`-filen vil bli opprettet.
1. reprojektionskommandoen -`-filters.reprojection.in_srs="EPSG:2154" --filters.reprojection.out_srs="EPSG:3943"` lar deg reproyisere punktskyen fra Lambert-93 SCR (`EPSG:2154`) til CC43 SCR (`3943`)

Kopier kommandoen og erstatt ganske enkelt EPSG-stiene og kodene i inngang og utgang. Når kommandoen er utført, blir den nye .las-filen generert på stedet som er angitt av målstien.

Som standard er IGN-punktskyer ikke fargelagt, men det finnes kommandoer i PDAL for å legge til farger basert på punktelevering eller ved å bruke en georeferert .tif-ortofoto med samme CRS. Åpen kildekode-programvaren QGIS gjør det enkelt å generere georeferert ortofoto.

Her er den samme kommandoen med et fargefilter som referanserer et ortofoto:

```
pdal translate "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz" ^ "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.las" ^ reprojection ^ --filters.reprojection.in_srs="EPSG:2154" ^ --filters.reprojection.out_srs="EPSG:3943" ^ colorization ^ --filters.colorization.raster="C:\Users\USERNAME\Downloads\Orthophoto.tif" ^ --filters.colorization.dimensions="Red:1,Green:2,Blue:3"
```

### 3.3 Last opp punktskyen din til Catenda Hub-prosjektet ditt

Når transformasjonen er fullført (til prosjektets CRS og i `.las` eller `.e57`-format), er alt du trenger å gjøre å laste opp punktskyen din til Catenda Hub-prosjektet ditt! Hvis du har fulgt alle trinnene riktig, bør det være perfekt justert med prosjektet ditt :)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/03-3-3-upload-your-point-cloud-to-your-catenda-hub-project.png)
