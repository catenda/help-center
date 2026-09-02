# Bereichern Sie Ihre Projekte mit frei zugänglichen IGN-Punktwolken (HD LiDAR)

Im Rahmen des [nationalen LiDAR-HD-Programms](https://geoservices.ign.fr/lidarhd) produziert und verteilt die IGN 3D-Kartierungen des gesamten Bodens und der Oberfläche Frankreichs in LiDAR-Daten. Die verteilten Daten sind insbesondere kalibrierte Punktwolken, roh oder klassifiziert, sowie 3D-Digitalmodelle (DEM, DSM, MNH usw.). Mit kostenlosen und quelloffenen Tools ist es möglich, die IGN-Punktwolken (veröffentlicht in `.laz`- und Lambert-93-Formaten) in das Format .las oder .e57 (lesbar in unserem 3D-Viewer) und in das Bezugskoordinatensystem (RCS) umzuwandeln, das Ihrem Projekt entspricht.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/01-intro.png)

Folgen Sie diesen Schritten, um eine kontextuelle Punktwolke zu Ihrem Projekt hinzuzufügen!

## 1. **1. Laden Sie Ihre Punktwolke hoch**

Das ist der einfachste Schritt! Laden Sie die Punktwolken-Kachel herunter, die dem Kontext Ihres Projekts entspricht, über [diese Schnittstelle](https://cartes.gouv.fr/telechargement/IGNF_NUAGES-DE-POINTS-LIDAR-HD). Für die Schweiz bietet Swisstopo [ebenfalls](https://www.swisstopo.admin.ch/en/height-model-swisssurface3d?utm_source=chatgpt.com#The-classified-point-cloud-of-Switzerland) Punktwolken an, die das gesamte Territorium im `.las`-Format abdecken.

## 2. **2. Laden Sie die erforderliche Open-Source-Software zum Transformieren Ihrer Punktwolke herunter**

Hier wird es knifflig! Um Ihre Punktwolke zu transformieren, müssen Sie diese zwei Open-Source-Softwareprogramme installieren:

1. [Miniconda](https://docs.conda.io/en/latest/miniconda.html) ist eine einfache Version der kostenlosen und quelloffenen [Anaconda](https://fr.wikipedia.org/wiki/Anaconda_(distribution_Python))-Distribution der Programmiersprachen Python und R, angewendet auf die Entwicklung von Data-Science-Anwendungen.
2. [PDAL](https://pdal.io/en/2.9.2/) ist eine quelloffene Bibliothek für die Verarbeitung von Punktwolken-Daten. Es ist ein bisschen wie ein VLC-Player für Punktwolken ;)

Eigentlich brauchen wir die Anaconda-Eingabeaufforderung, um PDAL zu verwenden, das sich um die Transformation kümmert. Lasst uns gehen 👇

### 2.1 **2.1. Installieren Sie Miniconda**

PDAL ist von anderen Bibliotheken abhängig, daher ist die einfachste Methode die Verwendung von Miniconda (eine einfache Version von Anaconda).

1. Gehen Sie zur offiziellen Miniconda-Download-Seite:
   👉 [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)
2. [Laden Sie das **Miniconda-Installationsprogramm für Windows (64-Bit, Python 3.x).** herunter](https://www.anaconda.com/download)
3. Starten Sie das Installationsprogramm:
   - Akzeptieren Sie die Lizenzvereinbarung
   - Wählen Sie "Nur für mich" (empfohlen)
   - Behalten Sie den standardmäßigen Installationsort bei
   - Aktivieren Sie "Miniconda3 zu PATH hinzufügen", falls diese Option angeboten wird
4. Öffnen Sie nach der Installation die Anaconda-Eingabeaufforderung (dies ist das Fenster, das Sie anstelle von CMD/PowerShell für PDAL verwenden werden).

### 2.2 **2.2. Erstellen Sie eine Conda-Umgebung für PDAL**

Es wird empfohlen, PDAL in seiner eigenen Umgebung zu isolieren. Kopieren Sie in der Anaconda-Eingabeaufforderung den folgenden Befehl und führen Sie ihn aus:

```
conda create -n pdal-env -c conda-forge pdal python=3.10
```

Dies tut drei Dinge:

- Erstellen Sie eine Umgebung namens `pdal-env`
- Installieren Sie PDAL aus dem **[conda-forge](https://anaconda.org/conda-forge/pdal)** Repository (neueste Version)
- Installieren von Python (nützlich, wenn Sie PDAL auch in Ihren Python-Skripten verwenden möchten)

### 2.3 Aktivieren Sie die PDAL-Umgebung

Führen Sie in der Anaconda-Eingabeaufforderung vor der Verwendung von PDAL die Umgebung aus, indem Sie folgende Schritte ausführen:

```
conda activate pdal-env
```

Jetzt sollte jeder pdal-Befehl diese Umgebung verwenden. (Wenn Sie das Terminal schließen, führen Sie conda `activate pdal-env` erneut aus, wenn Sie es erneut öffnen.)

### 2.4 Überprüfen Sie die Installation

Führen Sie aus:

```
pdal --version pdal --drivers
```

Wenn eine Version angezeigt wird und eine Liste der "readers.\* / filters.\* / writers.\*" erscheint, ist PDAL installiert. ✅ Überprüfen Sie, ob writers.las in der Liste enthalten ist, falls Sie in .las exportieren möchten. Dasselbe gilt für das Format `.e57`, das auch von Catenda Hub unterstützt wird ;)

## 3. Transformieren Sie Ihre Punktwolke

Wir sind fast dort! Nur noch ein paar Schritte...

### 3.1 Identifizieren Sie den EPSG-Code Ihres Koordinatenreferenzsystems (CRS)

Um Ihre Punktwolke in PDAL zu transformieren, müssen Sie den EPSG-Code kennen, der dem Koordinatensystem Ihres IFC-Modells entspricht. Hier ist eine nicht-umfassende Liste von SCRs, die das französische Kernland abdecken, und ihre jeweiligen EPSG-Codes.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="width: 209px; padding: 8px;"><p>Name</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; padding: 8px;"><p>EPSG</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>Bemerkungen</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert-93</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2154</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Der Standard für das französische Kernland, verwendet für IGN-Punktwolken. Deckt das gesamte Territorium ab.</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC42</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3942</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Für Zone 1 (Korsika).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC43</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3943</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Für Zone 2 (Süden bei 44° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC44</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3944</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Für Zone 3 (43° N bis 45° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC45</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3945</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Für Zone 4 (44° N bis 46° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC46</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3946</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Für Zone 5 (45° N bis 47° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC47</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3947</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Für Zone 6 (46° N bis 48° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC48</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3948</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Für Zone 7 (47° N bis 49° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC49</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3949</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Für Zone 8 (48° N bis 50° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC50</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3950</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Für Zone 9 (Nord bei 49° N).</p></td></tr></tbody></table></div>

![File:Departements LambertCC9Zones.svg - Wikimedia Commons](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/02-3-1-identify-the-epsg-code-of-your-coordinate-reference-system-crs.png)

### 3.2 Transformieren Sie Ihre Punktwolke mit Anaconda und PDAL

Jetzt, da wir den berühmten EPSG-Code kennen, der dem SCR unseres Projekts entspricht, können wir ENDLICH unsere Punktwolke transformieren

Hier ist ein Beispiel eines Befehls, mit dem Sie Ihre Punktwolke transformieren können:

```
pdal translate ^ "C:\\Users\\USERNAME\\Downloads\\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz" ^ "C:\\Users\\USERNAME\\Downloads\\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.las" ^ reprojection ^ --filters.reprojection.in_srs="EPSG:2154" ^ --filters.reprojection.out_srs="EPSG:3943"
```

🤓 Lassen Sie uns diesen Befehl aufschlüsseln:

1. `pdal translate` ist der Hauptbefehl zur Durchführung der Transformation.
2. `"C:\\Users\\USERNAME\\Downloads\\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz"` ist der Pfad zur `.laz`-Datei, die aus der IGN-Datenbank heruntergeladen wurde.
3. `"C:\\Users\\USERNAME\\Downloads\\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz`" ist der Pfad, in dem die zukünftige `.las`-Datei erstellt wird.
4. Der Reprojektion-Befehl `-`--filters.reprojection.in_srs="EPSG:2154" --filters.reprojection.out_srs="EPSG:3943"` ermöglicht es Ihnen, die Punktwolke vom Lambert-93-SCR (`EPSG:2154`) zum CC43-SCR (`3943\`) umzuprojizieren

Kopieren Sie den Befehl und ersetzen Sie einfach die EPSG-Pfade und -Codes in Ein- und Ausgang. Nach der Ausführung des Befehls wird Ihre neue .las-Datei im angegebenen Zielort generiert.

Standardmäßig sind IGN-Punktwolken nicht farblich gekennzeichnet, aber es gibt Befehle in PDAL, um Farben basierend auf der Punkthöhe oder durch Verwendung eines georeferenzierten .tif-Orthophotos mit demselben CRS hinzuzufügen. Die Open-Source-Software QGIS macht es einfach, georeferenzierte Orthophotos zu generieren.

Hier ist der gleiche Befehl mit einem Farbfilter, der auf ein Orthophoto verweist:

```
pdal translate "C:\\Users\\USERNAME\\Downloads\\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz" ^ "C:\\Users\\USERNAME\\Downloads\\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.las" ^ reprojection ^ --filters.reprojection.in_srs="EPSG:2154" ^ --filters.reprojection.out_srs="EPSG:3943" ^ colorization ^ --filters.colorization.raster="C:\\Users\\USERNAME\\Downloads\\Orthophoto.tif" ^ --filters.colorization.dimensions="Red:1,Green:2,Blue:3"
```

### 3.3 Laden Sie Ihre Punktwolke in Ihr Catenda-Hub-Projekt hoch

Nachdem die Transformation abgeschlossen ist (in Ihr Projekt-CRS und im `.las`- oder `.e57`-Format), müssen Sie nur noch Ihre Punktwolke in Ihr Catenda-Hub-Projekt hochladen! Wenn Sie alle Schritte korrekt befolgt haben, sollte sie perfekt mit Ihrem Projekt ausgerichtet sein :)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/03-3-3-upload-your-point-cloud-to-your-catenda-hub-project.png)
