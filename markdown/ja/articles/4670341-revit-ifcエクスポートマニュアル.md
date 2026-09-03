# Revit IFC エクスポート マニュアル

このIFCエクスポートマニュアルの目的は、ユーザーが適切な目的でIFCをエクスポートする方法についてのガイドを提供することです。IFCファイルは、モデルから多くの情報を取得する必要がある場合、すぐに重くなり、大きくなる可能性があります。そのため、IFCをエクスポートする際には、不要な情報のチェックを外す必要があります。Catendaにモデルをアップロードする場合、モデルに多くの情報と高いレベルの詳細が必ずしも必要ではありません。このマニュアルの後半で、モデルを少し小さくして、作業しやすくするために推奨する設定に戻ります。ここでは、RevitからCatendaへのIFCをエクスポートするための最も適切な方法をステップバイステップで説明します。

この記事で説明するトピックは以下のとおりです：

## 1. **プロジェクト設定**

エクスポートする前に、Revit プロジェクトの GUID が正しいことを確認することが重要です。

`管理 -> 設定 -> プロジェクト情報 -> IFC パラメーター`

![プロジェクト情報 IFCパラメータ IfcSite GUID IfcBuilding GUID IfcProject GUID](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/01-project-settings.png)

GUID が前回のエクスポートと異なる場合、新しいエクスポートのオブジェクトが BCF トピックの GUID に正しくリンクされません。新しいプロジェクトを作成すると、一意の ID が割り当てられます。

## 2. **IFC エクスポートの変更**

Revit が開いている状態で、エクスポートする準備ができたら、次の操作を実行することができます。

![画面の左上にあるファイルを押します](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/02-modify-ifc-export.png)

左上に「ファイル」タブがあります。

---

> **ヒント:** **注意:** _IFC 用の専用フォルダを用意することをお勧めします。これにより、ファイルの場所を常に把握できます!_

IFC エクスポート メニューはここにあります：

`ファイル -> エクスポート -> IFC`

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/03-modify-ifc-export.png)

IFC エクスポート メニューは次のような外観です：

![IFCをエクスポート](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/04-modify-ifc-export.png)

ファイル名 エクスポートされるファイルのシステム内での名前と場所を入力してください

エクスポート セットアップ 次の事前定義されたセットアップから選択します: \<In-Session Setup> IFC 2x3 Coordination View 2.0 IFC 2x3 Coordination View IFC 2x3 GSA Concept Design BIM 2010 IFC 2x3 Basic FM Handover View IFC 2x3 Coordination View IFC 2x3 COBie 2.4 Design Deliverable View IFC4 Reference View [Architecture] IFC4 Reference View [Structural] IFC4 Reference View [BuildingService] IFC4 Reference View [Unofficial] IFC4x3 IFC-SG Regulatory Requirements View

Catenda Plugin for Revit を使用する場合、Catenda で使用するための追加の事前定義されたエクスポート セットアップがオプションのリストに追加されます。

## 3. **セットアップの変更**

エクスポート IFC ダイアログボックスのエクスポート セットアップ部分で [セットアップの変更] をクリックします。ここは、IFC エクスポートに必要な設定を変更し、カスタム セットアップを作成できる場所です。セットアップの変更メニューは次のような外観です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/05-modify-setup.png)

このウィンドウには、次のタブが含まれています：

---

### 3.1 **一般**

![一般](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/06-general.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/07-general.png)

様々な設定について説明します。

**IFC バージョン** IFC バージョンの選択。

**交換要件**これらのオプションは、選択される IFC バージョンに応じて変更される可能性があります。IFC 2x3 Coordination View 2.0

- 建築参照交換
- MEP 参照交換
- 構造参照交換

**カテゴリ マッピング** Revit 2026 より前は、このオプションは「ファイル」-> 「エクスポート」-> 「オプション」-> 「IFC エクスポート オプション」で利用可能でした。IFC エクスポート マッピング設定の管理メニューは次のような外観です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/08-general.png)

**ファイル タイプ** IFC タイプの選択。

**エクスポートするフェーズ** Revit でフェーズ ツールを使用している場合、ここで新規または既存の構造のみをエクスポートすることを選択できます。

**スペース境界**これらはすべて、ルーム情報をさらにどのように使用できるかについてです。a. 1 段階レベル - 例: 数量の引き出し、管理、運用、保守 (FDVU)。b. 2 段階レベル - 例: エネルギー分析、光分析。

**施設タイプ**このオプションは IFC 4x3 でのみ利用可能です。次のいずれかを選択します: 橋 (IfcBridge) 建築物 (IfcBuilding) 海洋施設 (IfcMarineFacility) 鉄道 (IfcRailway) 道路 (IfcRoad)

**レベル別に壁、柱、ダクトを分割**ここでは、例えば複数のフロアにまたがってモデル化された仕切り壁を水平に分割できます。

_ファイル ヘッダー情報... プロジェクト アドレス..._ これらでは、IFC を配信したユーザー、プロジェクト アドレスなどに関する情報を入力できます。

**プロジェクト原点**プロジェクト原点、これは現在の共有座標に設定します - 共有座標を提示します。

> **注:** これは Revit 2025 以降「地理参照」に移動されました

**スチール要素を含める**モデル化された場合、スチール部品を含めます。

> **注:** これは Revit 2025 以降「追加コンテンツ」に移動されました

---

### 3.2 **追加コンテンツ**

![追加コンテンツ](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/09-additional-content.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/10-additional-content.png)

リンクされたファイルを個別の IFC としてエクスポート リンクされたファイルを IFC に含める場合は、このオプションをチェックしてそうしてください。各ファイルを個別にエクスポートし、それぞれを独自のモデルにインポートすることをお勧めします。

ビュー内に表示されている IFC ファイルのみをエクスポートします。

- 3D ビューでルーム、エリア、スペースをエクスポート
  このオプションは、2D ビューアーでエリアを選択する場合に役立つ場合があります。

スチール要素を含める、_塗りつぶし_

2D 平面ビュー要素、_塗りつぶし、領域_ (スクラッチ) をエクスポートします。

天井グリッドをエクスポート 天井グリッドは 2D 要素であるため、Catenda 3D ビューアーには表示されません。

---

### 3.3 **プロパティ セット**

![プロパティセット](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/11-property-sets.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/12-property-sets.png)

すべての Revit プロパティ セット (pset / properties) をエクスポート このオプションでエクスポートされた壁の例を次に示します: Revit (_左_) --- Catenda (_右_)

<img alt="プロパティ" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-4f4aab46be4e.png" width="208.60495436766624"/>  ---  <img alt="プロパティ" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-7c05fd3c2c4a.png" width="190.21739130434784"/>

プロパティ メニューに表示される典型的なプロパティは以下のとおりです: 制約、断面定義、寸法、構造、識別データ、その他

識別メニューに表示される典型的なプロパティは以下のとおりです：IFC パラメーター、標準 IFC プロパティをエクスポート、オブジェクトの計算された数量をエクスポート、バッチ リストをエクスポート、1 回限りのプロパティ セットをエクスポート

**分類設定** omniclass での分類設定がどのような外観であるかの例を示します。

![分類設定](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/13-property-sets.png)

**名前**分類の名前

**ソース (発行元)**分類の発行元

**版**分類版

**版の日付**分類の日付

**ドキュメント ロケーション**これは有効なドキュメント ロケーションである必要があります

**分類フィールド名**分類フィールド名は、分類値を保持するオブジェクト内のパラメーターの名前です。このパラメーターは多くの場合、ファミリー レベルで見つかります。ファミリーを編集してそのプロパティを確認してください

![ファミリーを編集](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/14-property-sets.png)

これはプロパティでパラメーターがどのように見えるかの例です

![プロパティ OmniClass番号](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/15-property-sets.png)

分類を使用してIFCをエクスポートし、Catendaにモデルとしてインポートした場合、分類は[提案されたライブラリ](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca)として表示されます。[ライブラリ ページ](https://support.catenda.com/en/articles/8065645-libraries-page)で新しいライブラリを作成する場合。指定したプロパティ内の値が提供されたドキュメント内の値と一致する場合、その値が見つかり、作成した分類ライブラリを通じてこの値を持つオブジェクトを選択するために使用できます。

---

### 3.4 **詳細レベル**

![詳細度](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/16-level-of-detail.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/17-level-of-detail.png)

これは、例えばカップやハンドレール、または自転車の車輪など、どの程度詳細にするかについてです。詳細レベルには 4 つの異なるレベルがあります。

極めて低い 低い 中程度 高い

高い場合、以下の画像に示すように最も詳細になります。

![詳細度 極低と高](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/18-level-of-detail.png)

---

Catenda Hub で使用するために Revit から IFC をエクスポートする場合、詳細レベルを高に設定しないことをお勧めします。詳細レベルを上げてエクスポートされたモデルには、多くの詳細と余分なポリゴンがあり、これは常に必要であるとは限らず、モデルのナビゲーションが遅くなります。これは、超低と高の設定でエクスポートする場合の違いの例です。

![これは高の設定でエクスポートされた階段手すり。90万ポリゴン](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/19-level-of-detail.png)

![これは極低の設定でエクスポートされた同じモデル。3万3千ポリゴン。](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/20-level-of-detail.png)

モデルの外観はほぼ同じになりますが、ポリゴン数は大幅に減少し、Catenda Hub でのナビゲーションはさらに高速になります。

---

### 3.5 **詳細**

![詳細](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/21-advanced.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/22-advanced.png)

**パーツを建築要素としてエクスポート**標準 IFC 要素と同様にパーツをエクスポートします。

**混合「ソリッド モデル」表現の使用を許可**このオプションを選択して、ユニットの BRep と押し出し幾何学形状のミキシングを許可します。

**ジオメトリ作成時にアクティブ ビューを使用**ジオメトリを生成するために使用するアクティブ ビューを使用するにはこのオプションを選択します。3D 以外のビューで使用された場合、予期しない結果が生じる可能性があることに注意してください。

**参照にファミリーとタイプ名を使用**参照にファミリーとタイプ名を使用するにはこのオプションを選択します。

**ルーム ボリュームに 2D ルーム境界を使用**ルーム ボリュームを計算するための簡略化された方法 (2D スペース境界の押し出しに基づく) を使用するにはこのオプションを選択します。これは IFC 2x2 へのエクスポート時の標準でもあります。

**サイトのローカル配置の原点に IfcSite 標高を含める** IfcSite のローカル位置の Z オフセットからの高さを含めるにはこのオプションを選択します。これを除外するには、オプションを削除します。

**エクスポート後、要素パラメーターに IFC GUID を保存**エクスポート後、生成された IFC GUID をプロジェクト ファイルに保存するにはこのオプションを選択します。これにより、項目とそのタイプ、およびプロジェクト、ウェブサイト、ビルディング ガイドのプロジェクト情報に「IFC GUID」パラメーターが追加されます。

**バウンディング ボックスをエクスポート**「バウンディング ボックス」表現をエクスポートするにはこのオプションを選択します。このオプションは、GSA エクスポートで自動的に選択されたままになります。

**四面体化されたジオメトリを三角分割として保持**複雑な曲線要素またはシェルがある場合、IFC エクスポート後に正しく表示されない場合は、このオプションを選択できます。非常に重いIFCファイルを生成する可能性があることに留意してください。

**IFC タイプ名にタイプ名のみを使用**オブジェクトの BAT-ID または ID をエンティティの名前として表示する場合は、このオプションを選択します。

**IFC エンティティ名として表示可能な Revit 名を使用** Revit オブジェクト名をエンティティの名前にする場合は、このオプションを選択します

**ファセット フロアとルーフを常に単一の IFC エンティティとしてエクスポート**複数の面を持つフロアとルーフの面を単一のエンティティに結合するにはこのオプションを選択します。

**「最後に変更」ユーザーをプロジェクト情報の作成者に設定**エクスポートの変更の作成者である場合は、このオプションを選択します

**エクスポートするエンティティ** IFC エンティティ選択メニューは次のような外観です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/23-advanced.png)

---

### 3.6 **地理参照**

Revit の座標を プロジェクト内の他のモデルと同期することが重要です。そうすることで、同じ場所に配置されます。したがって、Catenda Hub でポイント計測を使用して座標を計測し、Catenda Hub で計測されたポイントと同じ場所にある Revit でのポイントに座標ベースを指定します。

![ポイントで座標を指定](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/24-geographic-reference.png)

このオプションは、[管理] タブ -> [座標] -> [座標ベースを指定] で見つかります。_座標をポイントで指定_ モデルを移動し、北/南、東/西、標高の座標を指定することで、モデルを真北に回転します。Revit では、多くの場合、90 度の角度でモデル化する方が簡単であり、モデル全体を回転させたくない場合があります。この場合、代わりに真北を回転させることができます。このオプションは、[管理] タブの [座標] の下の [位置] ドロップダウンで見つかります。

![地理参照](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/25-geographic-reference.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/26-geographic-reference.png)

**プロジェクト サイト**内部

**座標ベース**この設定を変更して、プロジェクトが北に向いていることを確認できます 共有座標 - デフォルト測量ポイント プロジェクト基点 内部原点 プロジェクト基点 真北に向いた内部原点 真北に向いた

> **注:** [挿入] タブで IFC をリンクする場合、リンクされたファイルはオブジェクトの近くに配置され、IFC に記述されている場所には配置されません。IFC を正しい場所にインポートするには、[ファイル] -> [開く] -> [IFC] をクリックします。

**オーバーライド**ここで投影座標系参照をオーバーライドできます

---

### 3.7 **会社情報**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/27-company-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/28-company-info.png)

このメニューは、左側のメニューで [IFC2x3 COBie 2.4 Design Deliverable View セットアップ] が選択されている場合にのみ利用可能です。

---

### 3.8 **プロジェクト情報**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/29-project-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/30-project-info.png)

このメニューは、左側のメニューで [IFC2x3 COBie 2.4 Design Deliverable View セットアップ] が選択されている場合にのみ利用可能です。

---

## 4. **IFC オプション**

Revit プロジェクトの IFC オプションは以下で見つかります：

`ファイル -> エクスポート -> オプション -> IFC オプション`

![エクスポート -> オプション -> IFCオプション](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/31-ifc-options.png)

> **注:** Revit 2026 以降、このオプションは以下で利用可能になりました: `エクスポート -> IFC -> 一般 -> カテゴリ マッピング -> ドロップダウンの右側のアクション メニュー`

ここで、IFC オプション内で、モデルを IFC ファイルにエクスポートするための設定を行います。ここでは、モデルを IFC にエクスポートするためのセットアップ プロパティをカスタマイズできます。このマニュアルの最初に述べたことは、モデルから多くの情報を取り出す必要がないということです。エクスポート前に不必要な情報をオフにしてください。

![IFCエクスポートクラス](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/32-ifc-options.png)

Catenda Hub でグリッドを表示することは可能であり、Revit モデルにこれらがある場合、[IFC オプション] で、グリッドを IFC でエクスポートするように設定できます。デフォルトでは、これらは Revit からエクスポートされません。

## 5. **色と素材**

Catenda に表示される色は、インポートされる IFC ファイルから読み込まれます。ファミリーのマテリアル プロパティが IFC パラメーターに追加される場合、マテリアル プロパティ内のマテリアルの色が IFC に追加され、Catenda に表示されます。Revit では、マテリアルはマテリアル ブラウザーで見つかります：

`管理タブ -> 設定セクション -> マテリアル`
マテリアル ブラウザーでは、マテリアルの [グラフィックス] タブで色の設定が見つかります：

![管理 -> マテリアル -> マテリアルブラウザ -> 新しいマテリアルを作成](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/33-colors-and-materials.png)

シェーディングをレンダリング設定にロックすることも可能です。

![外観](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/34-colors-and-materials.png)

Catenda 3D ビューアーのサーフェスは、光源がない場合は平面シェーディングを使用します。Catenda が 3D ビューアーでサーフェスを表示する場合、以下の値が解釈されます：

汎用

- 色
- 画像フェード

透明度

- 量
- 画像フェード
- 透光性

色合い

- 色合い色
