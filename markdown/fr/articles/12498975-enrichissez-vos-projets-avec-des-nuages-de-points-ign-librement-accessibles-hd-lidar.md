# Enrichissez vos projets avec des nuages de points IGN librement accessibles (HD LiDAR)

Dans le cadre du [programme national LiDAR HD](https://geoservices.ign.fr/lidarhd), l'IGN produit et distribue une cartographie 3D de l'ensemble du sol et de la surface de la France en données LiDAR. Les données distribuées sont notamment des nuages de points recalibrés, bruts ou classifiés, et des modèles numériques 3D (DEM, DSM, MNH, etc.). Il est possible, grâce à des outils libres et open source, de transformer les nuages de points IGN (publiés en formats `.laz` et Lambert 93) en format .las ou .e57 (lisibles dans notre Visionneuse 3D) et dans le Système de Référence de Coordonnées (SRC) correspondant à votre projet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/01-intro.png)

Suivez ces étapes pour ajouter un nuage de points contextuel à votre projet !

## 1. **1. Télécharger votre nuage de points**

C'est l'étape la plus facile ! Téléchargez la dalle de nuage de points correspondant au contexte de votre projet via [cette interface](https://cartes.gouv.fr/telechargement/IGNF_NUAGES-DE-POINTS-LIDAR-HD). Pour la Suisse, Swisstopo [propose également](https://www.swisstopo.admin.ch/en/height-model-swisssurface3d?utm_source=chatgpt.com#The-classified-point-cloud-of-Switzerland) des nuages de points couvrant tout le territoire au format `.las`.

## 2. **2. Télécharger les logiciels open source nécessaires pour transformer votre nuage de points**

C'est là que cela devient compliqué ! Pour transformer votre nuage de points, vous devrez installer ces deux programmes logiciels open source :

1. [Miniconda](https://docs.conda.io/en/latest/miniconda.html) est une version légère de la distribution libre et open source [Anaconda](https://fr.wikipedia.org/wiki/Anaconda_(distribution_Python)) des langages de programmation Python et R, appliquée au développement d'applications de science des données.
2. [PDAL](https://pdal.io/en/2.9.2/) est une Bibliothèque open source pour le traitement des données de nuages de points. C'est un peu comme un lecteur VLC pour les nuages de points ;)

En réalité, nous avons besoin de l'invite Anaconda pour utiliser PDAL, qui s'occupera de la transformation. C'est parti 👇

### 2.1 **2.1. Installer Miniconda**

PDAL dépend d'autres Bibliothèques, donc la façon la plus facile est d'utiliser Miniconda (une version légère d'Anaconda).

1. Allez sur la page officielle de téléchargement de Miniconda :
   👉 [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)
2. [Téléchargez](https://www.anaconda.com/download) l'**installateur Miniconda pour Windows (64 bits, Python 3.x).**
3. Lancez l'installateur :
   - Acceptez le contrat de licence
   - Choisissez "Juste pour moi" (recommandé)
   - Gardez l'emplacement d'installation par défaut
   - Cochez "Ajouter Miniconda3 au PATH" si l'option est proposée
4. Une fois installé, ouvrez l'invite Anaconda (c'est la fenêtre que vous utiliserez à la place de CMD/PowerShell pour PDAL).

### 2.2 **2.2. Créer un environnement Conda pour PDAL**

Il est recommandé d'isoler PDAL dans son propre environnement. Dans l'invite Anaconda, copiez et exécutez la commande suivante :

```
conda create -n pdal-env -c conda-forge pdal python=3.10
```

Cela fait trois choses :

- Créer un environnement appelé `pdal-env`
- Installer PDAL à partir du dépôt **[conda-forge](https://anaconda.org/conda-forge/pdal)** (dernière version)
- Installer Python (utile si vous souhaitez également utiliser PDAL dans vos scripts Python)

### 2.3 Activer l'environnement PDAL

Toujours dans l'invite Anaconda, avant d'utiliser PDAL, activez l'environnement en exécutant :

```
conda activate pdal-env
```

Désormais, toute commande pdal devrait utiliser cet environnement. (Si vous fermez le terminal, exécutez à nouveau `conda activate pdal-env` quand vous le rouvrez.)

### 2.4 Vérifier l'installation

Exécutez :

```
pdal --version pdal --drivers
```

Si une version s'affiche et qu'une liste de "readers.\* / Filtres.\* / writers.\*" apparaît, PDAL est installé. ✅ Vérifiez que writers.las figure dans la liste si vous souhaitez exporter en .las. Même chose pour le format `.e57` également supporté par Catenda Hub ;)

## 3. Transformer votre nuage de points

On y est presque ! Encore quelques étapes...

### 3.1 Identifier le code EPSG de votre Système de Référence de Coordonnées (SRC)

Pour transformer votre nuage de points en PDAL, vous devez connaître le code EPSG correspondant au système de coordonnées de votre model IFC. Voici une liste non exhaustive des SRC couvrant la France métropolitaine et leurs codes EPSG respectifs.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="width: 209px; padding: 8px;"><p>Nom</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; padding: 8px;"><p>EPSG</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>Remarques</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert-93</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2154</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>La norme pour la France métropolitaine, utilisée pour les nuages de points IGN. Couvre l'ensemble du territoire.</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC42</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3942</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Pour la zone 1 (Corse).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC43</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3943</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Pour la zone 2 (sud à 44° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC44</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3944</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Pour la zone 3 (43° N à 45° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC45</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3945</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Pour la zone 4 (44° N à 46° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC46</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3946</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Pour la zone 5 (45° N à 47° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC47</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3947</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Pour la zone 6 (46° N à 48° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC48</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3948</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Pour la zone 7 (47° N à 49° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC49</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3949</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Pour la zone 8 (48° N à 50° N).</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC50</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3950</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Pour la zone 9 (nord à 49° N).</p></td></tr></tbody></table></div>

![File:Departements LambertCC9Zones.svg - Wikimedia Commons](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/02-3-1-identify-the-epsg-code-of-your-coordinate-reference-system-crs.png)

### 3.2 Transformer votre nuage de points avec Anaconda et PDAL

Maintenant que nous connaissons le fameux code EPSG correspondant au SRC de notre projet, nous pouvons ENFIN transformer notre nuage de points

Voici un exemple de commande qui vous permet de transformer votre nuage de points :

```
pdal translate ^ "C:\\Users\\USERNAME\\Downloads\\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz" ^ "C:\\Users\\USERNAME\\Downloads\\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.las" ^ reprojection ^ --filters.reprojection.in_srs="EPSG:2154" ^ --filters.reprojection.out_srs="EPSG:3943"
```

🤓 Décomposons cette commande :

1. `pdal translate` est la commande principale pour effectuer la transformation.
2. `"C:\\Users\\USERNAME\\Downloads\\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz"` est le chemin d'accès au fichier `.laz` téléchargé à partir de la base de données IGN.
3. `"C:\\Users\\USERNAME\\Downloads\\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz`" est le chemin d'accès où le futur fichier `.las` sera créé.
4. la commande de reprojection -`-filters.reprojection.in_srs="EPSG:2154" --filters.reprojection.out_srs="EPSG:3943"` vous permet de reprojeter le nuage de points du SRC Lambert-93 (`EPSG:2154`) vers le SRC CC43 (`3943`)

Copiez la commande et remplacez simplement les chemins EPSG et les codes en entrée et en sortie. Une fois la commande exécutée, votre nouveau fichier .las sera généré à l'emplacement spécifié par le chemin cible.

Par défaut, les nuages de points IGN ne sont pas colorisés, mais il existe des commandes dans PDAL pour ajouter des couleurs en fonction de l'élévation des points ou en utilisant une orthophoto .tif géoréférencée ayant le même SRC. Le logiciel open source QGIS facilite la génération d'orthophotos géoréférencées.

Voici la même commande avec un Filtre de colorisation référençant une orthophoto :

```
pdal translate "C:\\Users\\USERNAME\\Downloads\\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz" ^ "C:\\Users\\USERNAME\\Downloads\\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.las" ^ reprojection ^ --filters.reprojection.in_srs="EPSG:2154" ^ --filters.reprojection.out_srs="EPSG:3943" ^ colorization ^ --filters.colorization.raster="C:\\Users\\USERNAME\\Downloads\\Orthophoto.tif" ^ --filters.colorization.dimensions="Red:1,Green:2,Blue:3"
```

### 3.3 Télécharger votre nuage de points vers votre projet Catenda Hub

Une fois la transformation effectuée (vers le SRC de votre projet, et au format `.las` ou `.e57`), il ne vous reste plus qu'à télécharger votre nuage de points vers votre projet Catenda Hub ! Si vous avez suivi toutes les étapes correctement, il devrait être parfaitement aligné avec votre projet :)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/03-3-3-upload-your-point-cloud-to-your-catenda-hub-project.png)
