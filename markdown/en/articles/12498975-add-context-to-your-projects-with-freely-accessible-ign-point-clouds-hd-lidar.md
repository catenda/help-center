# Add context to your projects with freely accessible IGN point clouds (HD LiDAR)

As part of the [national LiDAR HD program](https://geoservices.ign.fr/lidarhd), the IGN produces and distributes 3D mapping of the entire ground and surface of France in LiDAR data. The data distributed are in particular recalibrated point clouds, raw or classified, and 3D digital models (DEM, DSM, MNH, etc.). It is possible with free and open source tools to transform the IGN point clouds (published in `.laz` and Lambert 93 formats) into .las or .e57 format (readable in our 3D viewer) and into the Reference Coordinate System (RCS) corresponding to your project.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/01-intro.png)

Follow these steps to add a contextual point cloud to your project!

## 1. **1. Upload your point cloud**

This is the easiest step! Download the point cloud tile corresponding to the context of your project via [this interface](https://cartes.gouv.fr/telechargement/IGNF_NUAGES-DE-POINTS-LIDAR-HD). For Switzerland, Swisstopo [also provides](https://www.swisstopo.admin.ch/en/height-model-swisssurface3d?utm_source=chatgpt.com#The-classified-point-cloud-of-Switzerland) point clouds covering the entire territory in `.las` format.

## 2. **2. Download the open source software required for transforming your point cloud**

This is where it gets tricky! To transform your point cloud, you'll need to install these two open-source software programs:

1. [Miniconda](https://docs.conda.io/en/latest/miniconda.html) is a lightweight version of the free and open-source [Anaconda](https://fr.wikipedia.org/wiki/Anaconda_(distribution_Python)) distribution of the Python and R programming languages, applied to the development of data science applications.
1. [PDAL](https://pdal.io/en/2.9.2/) is an open-source library for processing point cloud data. It's a bit like a VLC player for point clouds ;)

Actually, we need the Anaconda Prompt to use PDAL, which will take care of the transformation. Let's go 👇

### 2.1 **2.1. Install Miniconda**

PDAL depends on other libraries, so the easiest way is to use Miniconda (a lightweight version of Anaconda).

1. Go to the official Miniconda download page: 
👉 [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)
1. [Download](https://www.anaconda.com/download) the **Miniconda installer for Windows (64-bit, Python 3.x).**
1. Launch the installer:
    - Accept the license agreement
    - Choose "Just for me" (recommended)
    - Keep the default installation location
    - Check "Add Miniconda3 to PATH" if the option is offered
1. Once installed, open the Anaconda Prompt (this is the window you will use instead of CMD/PowerShell for PDAL).

### 2.2 **2.2. Create a Conda environment for PDAL**

It is recommended to isolate PDAL in its own environment. In Anaconda Prompt, copy and run the following command:

```
conda create -n pdal-env -c conda-forge pdal python=3.10
```

This does three things:

- Create an environment called `pdal-env`
- Install PDAL from the **[conda-forge](https://anaconda.org/conda-forge/pdal)** repository (latest version)
- Installing Python (useful if you also want to use PDAL in your Python scripts)

### 2.3 Activate the PDAL environment

Still in the Anaconda Prompt, before using PDAL, activate the environment by running:

```
conda activate pdal-env
```

Now, any pdal command should use this environment. (If you close the terminal, run conda `activate pdal-env` again when you reopen it.)

### 2.4 Check the installation

Run:

```
pdal --version pdal --drivers
```

If a version is displayed and a list of “readers.\* / filters.\* / writers.\*” appears, PDAL is installed. ✅ Check that writers.las is in the list if you want to export to .las. Same for the `.e57` format also supported by Catenda Hub ;)

## 3. Transform your point cloud

We're almost there! Just a few more steps...

### 3.1 Identify the EPSG code of your Coordinate Reference System (CRS)

To transform your point cloud into PDAL, you need to know the EPSG code corresponding to the coordinate system of your IFC model. Here is a non-exhaustive list of SCRs covering metropolitan France and their respective EPSG codes.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="width: 209px;"><p>Name</p></td><td style="width: 70px;"><p>EPSG</p></td><td><p>Remarks</p></td></tr><tr><td style="width: 209px;"><p>RGF93 / Lambert-93</p></td><td style="width: 70px;"><p>2154</p></td><td><p>The standard for metropolitan France, used for IGN point clouds. Covers the entire territory.</p></td></tr><tr><td style="width: 209px;"><p>RGF93 / Lambert CC42</p></td><td style="width: 70px;"><p>3942</p></td><td><p>For the zone 1 (Corse).</p></td></tr><tr><td style="width: 209px;"><p>RGF93 / Lambert CC43</p></td><td style="width: 70px;"><p>3943</p></td><td><p>For the zone 2 (south at 44° N).</p></td></tr><tr><td style="width: 209px;"><p>RGF93 / Lambert CC44</p></td><td style="width: 70px;"><p>3944</p></td><td><p>For the zone 3 (43° N by 45° N).</p></td></tr><tr><td style="width: 209px;"><p>RGF93 / Lambert CC45</p></td><td style="width: 70px;"><p>3945</p></td><td><p>For the zone 4 (44° N by 46° N).</p></td></tr><tr><td style="width: 209px;"><p>RGF93 / Lambert CC46</p></td><td style="width: 70px;"><p>3946</p></td><td><p>For the zone 5 (45° N by 47° N).</p></td></tr><tr><td style="width: 209px;"><p>RGF93 / Lambert CC47</p></td><td style="width: 70px;"><p>3947</p></td><td><p>For the zone 6 (46° N by 48° N).</p></td></tr><tr><td style="width: 209px;"><p>RGF93 / Lambert CC48</p></td><td style="width: 70px;"><p>3948</p></td><td><p>For the zone 7 (47° N by 49° N).</p></td></tr><tr><td style="width: 209px;"><p>RGF93 / Lambert CC49</p></td><td style="width: 70px;"><p>3949</p></td><td><p>For the zone 8 (48° N by 50° N).</p></td></tr><tr><td style="width: 209px;"><p>RGF93 / Lambert CC50</p></td><td style="width: 70px;"><p>3950</p></td><td><p>For the zone 9 (nord at 49° N).</p></td></tr></tbody></table></div>

![File:Departements LambertCC9Zones.svg - Wikimedia Commons](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/02-3-1-identify-the-epsg-code-of-your-coordinate-reference-system-crs.png)

### 3.2 Transform your point cloud using Anaconda and PDAL

Now that we know the famous EPSG code corresponding to the SCR of our project, we can FINALLY transform our point clou

Here is an example of a command that allows you to transform your point cloud:

```
pdal translate ^ "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz" ^ "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.las" ^ reprojection ^ --filters.reprojection.in_srs="EPSG:2154" ^ --filters.reprojection.out_srs="EPSG:3943"
```

🤓 Let's break this command down:

1. `pdal translate` is the main command for performing the transformation.
1. `"C:\\Users\\USERNAME\\Downloads\\LHD\_FXX\_0766\_6282\_PTS\_LAMB93\_IGN69.copc.laz"` is the path to the `.laz` file downloaded from the IGN database.
1. `"C:\\Users\\USERNAME\\Downloads\\LHD\_FXX\_0766\_6282\_PTS\_LAMB93\_IGN69.copc.laz`" is the path where the future `.las` file will be created.
1. the reprojection command -`-filters.reprojection.in\_srs="EPSG:2154" --filters.reprojection.out\_srs="EPSG:3943"` allows you to reproject the point cloud from the Lambert-93 SCR (`EPSG:2154`) to the CC43 SCR (`3943`)

Copy the command and simply replace the EPSG paths and codes in input and output. Once the command is executed, your new .las file will be generated in the location specified by the target path.

By default, IGN point clouds are not colorized, but there are commands in PDAL to add colors based on point elevation or by using a georeferenced .tif orthophoto with the same CRS. The open source software QGIS makes it easy to generate georeferenced orthophotos.

Here is the same command with a colorization filter referencing an orthophoto:

```
pdal translate "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz" ^ "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.las" ^ reprojection ^ --filters.reprojection.in_srs="EPSG:2154" ^ --filters.reprojection.out_srs="EPSG:3943" ^ colorization ^ --filters.colorization.raster="C:\Users\USERNAME\Downloads\Orthophoto.tif" ^ --filters.colorization.dimensions="Red:1,Green:2,Blue:3"
```

### 3.3 Upload your point cloud to your Catenda Hub project

Once the transformation is done (to your project's CRS, and in `.las` or `.e57` format), all you have to do is upload your point cloud to your Catenda Hub project! If you've followed all the steps correctly, it should be perfectly aligned with your project :)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/03-3-3-upload-your-point-cloud-to-your-catenda-hub-project.png)
