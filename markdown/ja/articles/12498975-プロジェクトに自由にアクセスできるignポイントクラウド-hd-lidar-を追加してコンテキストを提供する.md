# プロジェクトに自由にアクセスできるIGNポイントクラウド(HD LiDAR)を追加してコンテキストを提供する

[国家LiDAR HDプログラム](https://geoservices.ign.fr/lidarhd)の一部として、IGNはフランス全土の地面と表面の3Dマッピングを製造・配布しています。配布されるデータには、特に再キャリブレーションされたポイントクラウド(生または分類)、および3Dデジタルモデル(DEM、DSM、MNH等)が含まれます。自由でオープンソースのツールを使用して、IGNポイントクラウド(`.laz`およびLambert 93形式で公開)を.lasまたは.e57形式(当社の3D ビューアで読み取り可能)に、およびプロジェクトに対応する参照座標系(RCS)に変換することが可能です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/01-intro.png)

以下の手順に従って、プロジェクトにコンテキストポイントクラウドを追加してください。

この記事で説明されているトピックは以下の通りです。

## 1. **1. ポイントクラウドをアップロード**

これが最も簡単なステップです！プロジェクトのコンテキストに対応するポイントクラウドタイルを[このインターフェース](https://cartes.gouv.fr/telechargement/IGNF_NUAGES-DE-POINTS-LIDAR-HD)を経由してダウンロードしてください。スイスの場合、Swisstapo [も提供](https://www.swisstopo.admin.ch/en/height-model-swisssurface3d?utm_source=chatgpt.com#The-classified-point-cloud-of-Switzerland)しており、`.las`形式で全領域をカバーするポイントクラウドを提供しています。

## 2. **2. ポイントクラウドを変換するために必要なオープンソースソフトウェアをダウンロード**

ここからが本当に複雑になります！ポイントクラウドを変換するには、これら2つのオープンソースソフトウェアプログラムをインストールする必要があります。

1. [Miniconda](https://docs.conda.io/en/latest/miniconda.html)は、フリーでオープンソースの[Anaconda](https://fr.wikipedia.org/wiki/Anaconda_(distribution_Python))配布版(PythonおよびRプログラミング言語)の軽量バージョンで、データサイエンスアプリケーションの開発に適用されます。
2. [PDAL](https://pdal.io/en/2.9.2/)はポイントクラウドデータを処理するためのオープンソースライブラリです。ポイントクラウド用のVLCプレイヤーのようなものです ;)

実は、PDALを使用するにはAnacondaプロンプトが必要です。これが変換を行います。さあ、行きましょう 👇

### 2.1 **2.1. Minicondaをインストール**

PDALは他のライブラリに依存しているため、最も簡単な方法はMiniconda(Anacondaの軽量バージョン)を使用することです。

1. 公式Minicondaダウンロードページにアクセスしてください。
   👉 [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)
2. [ダウンロード](https://www.anaconda.com/download)して、**Windows用Minicondaインストーラ(64ビット、Python 3.x)。**
3. インストーラーを起動します。
   - ライセンス契約に同意します
   - 「私のみ」を選択します(推奨)
   - デフォルトのインストール場所を保持します
   - 「Miniconda3をPATHに追加」にチェックを入れます(オプションが提供されている場合)
4. インストール後、Anacondaプロンプトを開きます(これはPDALの代わりにCMD/PowerShellの代わりに使用するウィンドウです)。

### 2.2 **2.2. PDAL用のConda環境を作成**

PDALを独自の環境に分離することが推奨されます。Anacondaプロンプトで、以下のコマンドをコピーして実行してください。

```
conda create -n pdal-env -c conda-forge pdal python=3.10
```

これは3つのことを行います。

- `pdal-env`という名前の環境を作成します
- **[conda-forge](https://anaconda.org/conda-forge/pdal)**リポジトリからPDALをインストール(最新バージョン)
- Pythonをインストール(PythonスクリプトでもPDALを使用したい場合に便利です)

### 2.3 PDAL環境をアクティベート

引き続きAnacondaプロンプトで、PDALを使用する前に、以下を実行して環境をアクティベートしてください。

```
conda activate pdal-env
```

これからは、すべてのpdalコマンドはこの環境を使用する必要があります。(ターミナルを閉じた場合、再度開くときに`activate pdal-env`を実行してください。)

### 2.4 インストールを確認

実行してください。

```
pdal --version pdal --drivers
```

バージョンが表示され、「readers.\* / filters.\* / writers.\*」のリストが表示される場合、PDALはインストールされています。✅ .lasにエクスポートしたい場合はwriters.lasがリストにあることを確認してください。Catenda Hubでもサポートされている`.e57`形式についても同じです ;)

## 3. ポイントクラウドを変換

ほぼ完成しました！あと数ステップです。

### 3.1 座標参照システム(CRS)のEPSGコードを識別

ポイントクラウドをPDALに変換するには、IFCモデルの座標系に対応するEPSGコードを知る必要があります。メトロポリタンフランスをカバーするSCRの完全ではないリストと、それらの対応するEPSGコードはここにあります。

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="width: 209px; padding: 8px;"><p>名前</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; padding: 8px;"><p>EPSG</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>備考</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert-93</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2154</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>メトロポリタンフランスの標準で、IGNポイントクラウドに使用されます。全領土をカバーしています。</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC42</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3942</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ゾーン1(コルシカ)用。</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC43</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3943</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ゾーン2(44°N以南)用。</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC44</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3944</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ゾーン3(43°N～45°N)用。</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC45</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3945</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ゾーン4(44°N～46°N)用。</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC46</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3946</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ゾーン5(45°N～47°N)用。</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC47</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3947</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ゾーン6(46°N～48°N)用。</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC48</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3948</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ゾーン7(47°N～49°N)用。</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC49</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3949</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ゾーン8(48°N～50°N)用。</p></td></tr><tr><td style="width: 209px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>RGF93 / Lambert CC50</p></td><td style="width: 70px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3950</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ゾーン9(49°N北)用。</p></td></tr></tbody></table></div>

![File:Departements LambertCC9Zones.svg - Wikimedia Commons](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/02-3-1-identify-the-epsg-code-of-your-coordinate-reference-system-crs.png)

### 3.2 AnacondaとPDALを使用してポイントクラウドを変換

私たちのプロジェクトのSCRに対応する有名なEPSGコードを知ったので、ついにポイントクラウドを変換できます。

ポイントクラウドを変換できるコマンドの例を次に示します。

```
pdal translate ^ "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz" ^ "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.las" ^ reprojection ^ --filters.reprojection.in_srs="EPSG:2154" ^ --filters.reprojection.out_srs="EPSG:3943"
```

🤓 このコマンドを詳しく見てみましょう。

1. `pdal translate`は変換を実行するためのメインコマンドです。
2. `"C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz"`はIGNデータベースからダウンロードした`.laz`ファイルへのパスです。
3. `"C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz"`は、今後の`.las`ファイルが作成されるパスです。
4. 再投影コマンド-`-filters.reprojection.in_srs="EPSG:2154" --filters.reprojection.out_srs="EPSG:3943"`を使用すると、ポイントクラウドをLambert-93 SCR(`EPSG:2154`)からCC43 SCR(`3943`)に再投影できます。

コマンドをコピーして、入力と出力のEPSGパスとコードを単純に置き換えてください。コマンドが実行されると、新しい.lasファイルがターゲットパスで指定された場所に生成されます。

デフォルトでは、IGNポイントクラウドは色付けされていませんが、ポイント標高またはSameCRS地理参照.tif正射画像を使用して色を追加するPDALのコマンドがあります。オープンソースソフトウェアQGISは、地理参照正射画像を簡単に生成します。

正射画像を参照する色付けフィルターを使用した同じコマンドを次に示します。

```
pdal translate "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.laz" ^ "C:\Users\USERNAME\Downloads\LHD_FXX_0766_6282_PTS_LAMB93_IGN69.copc.las" ^ reprojection ^ --filters.reprojection.in_srs="EPSG:2154" ^ --filters.reprojection.out_srs="EPSG:3943" ^ colorization ^ --filters.colorization.raster="C:\Users\USERNAME\Downloads\Orthophoto.tif" ^ --filters.colorization.dimensions="Red:1,Green:2,Blue:3"
```

### 3.3 Catenda Hubプロジェクトにポイントクラウドをアップロード

変換が完了したら(プロジェクトのCRSと`.las`または`.e57`形式で)、あとはポイントクラウドをCatenda Hubプロジェクトにアップロードするだけです！すべてのステップを正しく実行していれば、プロジェクトと完全に調整される必要があります :)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/z22gv4e5/03-3-3-upload-your-point-cloud-to-your-catenda-hub-project.png)
