# Revit IFCエクスポートマニュアル

このIFCエクスポートマニュアルの目的は、ユーザーにIFCを正しい目的でエクスポートする方法についてのガイドを提供することです。モデルから多くの情報を取得する場合、IFCファイルはすぐに重く、大きくなる可能性があります。したがって、IFCをエクスポートする場合、不要な情報をチェック解除する必要があります。Catendaにモデルをアップロードする場合、常にモデルに多くの情報と高い詳細度が必要とは限りません。このマニュアルの後半で、モデルをより小さく、より操作しやすくするための推奨設定に戻ります。ここでは、RevitからCatendaへIFCをエクスポートするための最も適切な方法をステップバイステップで説明します。

このアーティクルで説明されているトピックは次のとおりです:

## 1. **プロジェクト設定**

エクスポートする前に、Revitプロジェクトの GUID が正しいことを確認することが重要です。

`管理 -> 設定 -> プロジェクト情報 -> IFCパラメータ`

![プロジェクト情報 IFC パラメータ IfcSite GUID IfcBuilding GUID IfcProject GUID](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/01-project-settings.png)

GUIDが前回のエクスポートと異なる場合、新しいエクスポートのオブジェクトは、BCFトピック内のGUIDに正しくリンクされません。新しいプロジェクトを作成すると、一意のIDが割り当てられます。

## 2. **IFCエクスポートの修正**

Revitが開いていて、エクスポートの準備ができたら、次のいずれかの操作を行うことができます。

![画面左上の「ファイル」を押します](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/02-modify-ifc-export.png)

左上に「ファイル」タブがあります。

---

> **ヒント:** **注意:** _IFC用の専用フォルダを持つことをお勧めします。これにより、ファイルの場所を常に管理できます!_

IFCエクスポートメニューはここにあります:

`ファイル -> エクスポート -> IFC`

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/03-modify-ifc-export.png)

IFCエクスポートメニューは次のようになります:

![IFCをエクスポート](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/04-modify-ifc-export.png)

ファイル名 エクスポートされたファイルがシステムに持つ名前と場所を入力します

エクスポート設定 次の事前定義されたセットアップから選択します: \<セッション内セットアップ> IFC 2x3 コーディネーションビュー 2.0 IFC 2x3 コーディネーションビュー IFC 2x3 GSAコンセプトデザイン BIM 2010 IFC 2x3 基本FM ハンドオーバービュー IFC 2x3 コーディネーションビュー IFC 2x3 COBie 2.4 デザイン納品ビュー IFC4 リファレンスビュー [アーキテクチャ] IFC4 リファレンスビュー [構造] IFC4 リファレンスビュー [BuildingService] IFC4 リファレンスビュー [非公式] IFC4x3 IFC-SG 規制要件ビュー

Catenda Plugin for Revitを使用すると、Catendaで使用するための追加の事前定義されたエクスポートセットアップがオプションのリストに追加されます。

## 3. **セットアップの修正**

エクスポートセットアップダイアログのエクスポートセットアップ部分の「セットアップを修正」をクリックします。ここでは、IFCエクスポートの必要な設定を変更でき、カスタムセットアップを作成できます。セットアップの修正メニューは次のようになります:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/05-modify-setup.png)

このウィンドウには次のタブが含まれています:

---

### 3.1 **一般**

![一般](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/06-general.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/07-general.png)

さまざまな設定についてご説明します。

**IFCバージョン** IFCバージョンの選択。

**交換要件**これらのオプションは、選択されたIFCバージョンに応じて変更できます。IFC 2x3 調整ビュー 2.0

- 建築参照交換
- MEP参照交換
- 構造参照交換

**カテゴリマッピング** Revit 2026より前のバージョンでは、このオプションは「ファイル」→「エクスポート」→「オプション」→「IFCエクスポートオプション」で利用可能でした。「IFCエクスポートマッピング設定の管理」メニューは次のようになります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/08-general.png)

**ファイルタイプ** IFCタイプの選択。

**エクスポートするフェーズ** Revitでフェーズツールを使用した場合、ここで新しい構造体または既存の構造体のみをエクスポートすることを選択できます。

**空間境界**これらはすべて、ルーム情報をさらにどのように使用できるかに関するものです。a. 第1レベル - 使用例：数量引き出し、管理、運用・保守（FDVU）。b. 第2レベル - 使用例：エネルギー分析、光分析。

**施設タイプ**このオプションはIFC 4x3でのみ利用可能です。以下から選択してください。橋梁（IfcBridge）建物（IfcBuilding）海洋施設（IfcMarineFacility）鉄道（IfcRailway）道路（IfcRoad）

**壁、柱、ダクトをレベルごとに分割**ここで例えば、 複数階にわたってモデル化されている場合は、壁を水平方向に分割できます。

_ファイルヘッダー情報... プロジェクトアドレス..._ これらには、IFCを配信した人、プロジェクトアドレスなどの情報を入力できます。

**プロジェクト原点**プロジェクト原点、これを現在の共有座標に置きます - 共有座標を提示します。

> **注:** Revit 2025以降、これは「地理参照」に移動されています

**鋼部材を含める**モデル化されている場合、鋼部材が含まれます。

> **注:** Revit 2025以降、これは「追加コンテンツ」に移動されています

---

### 3.2 **追加コンテンツ**

![追加コンテンツ](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/09-additional-content.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/10-additional-content.png)

リンクファイルを個別のIFCとしてエクスポート リンクファイルをIFCに含める場合は、このオプションをチェックしてそうすることができます。各ファイルを個別にエクスポートし、各ファイルを独自のモデルにインポートすることをお勧めします。

ビューに表示されているオブジェクトのみをエクスポート IFCファイル。

- 3Dビューでルーム、面積、スペースをエクスポート
  このオプションは2Dビューアで領域を選択するのに役立つ場合があります。

鋼部材を含める、_塗りつぶし_

2D平面図要素、_塗りつぶし、領域_（スクラッチ）をエクスポート。

天井グリッドをエクスポート 天井グリッドは2D要素であるため、Catenda 3Dビューアに表示されません。

---

### 3.3 **プロパティセット**

![プロパティセット](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/11-property-sets.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/12-property-sets.png)

すべてのRevitプロパティセット（pset /プロパティ）をエクスポート このオプションでエクスポートされた壁の例を次に示します。Revit（_左_）--- Catenda（_右_）

<img alt="Properties" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-4f4aab46be4e.png" width="208.60495436766624"/>  ---  <img alt="Properties" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-7c05fd3c2c4a.png" width="190.21739130434784"/>

プロパティメニューに表示される一般的なプロパティ：制約、断面定義、寸法、構造、識別データ、その他

識別メニューに表示される一般的なプロパティ：IFCパラメータ 標準IFCプロパティをエクスポート。オブジェクトの計算量をエクスポート。バッチリストをエクスポート 1回限りのプロパティセット

**分類設定** omniclassを使用した分類設定の例を次に示します。

![分類設定](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/13-property-sets.png)

**名前**分類の名前

**ソース（公開元）**分類の公開元

**版**分類版

**版日付**分類の日付

**ドキュメント場所**これは有効なドキュメント場所である必要があります

**分類フィールド名**分類フィールド名は、分類値を保持するオブジェクト内のパラメータの名前です。このパラメータはしばしばファミリレベルで見つけることができます。ファミリを編集してそのプロパティを確認します

![ファミリを編集](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/14-property-sets.png)

パラメータがプロパティに表示されるようなものです

![プロパティ OmniClassナンバー](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/15-property-sets.png)

分類を使用してifcをエクスポートし、Catendaにモデルとしてインポートした場合、[ライブラリページ](https://support.catenda.com/en/articles/8065645-libraries-page)で新しいライブラリを作成する際に、その分類が[提案されたライブラリ](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca)として提案されます。指定したプロパティの値が提供されたドキュメント内の値と一致する場合、それが見つかり、作成した分類ライブラリを通じてこの値を持つオブジェクトを選択するために使用できます。

---

### 3.4 **詳細度**

![詳細度](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/16-level-of-detail.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/17-level-of-detail.png)

これは、例えばどれほど詳細であるかについてです。カップ、手すり、おそらく自転車の車輪。詳細度には4つのレベルがあります。

非常に低い 低い 中 高い

高い場合、下の画像に示すように、最も詳細になります。

![詳細度が非常に低いと高い](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/18-level-of-detail.png)

---

RevitからCatenda Hubで使用するIFCをエクスポートする場合、詳細度を高に設定しないことをお勧めします。より高い詳細度でエクスポートされたモデルには、多くの詳細と余分なポリゴンがあり、これが常に必要とは限らず、モデルナビゲーションが遅くなります。これは、非常に低い設定と高い設定でエクスポートする場合の違いの例です。

![これは、「高い」設定でエクスポートされた階段の手すりです。 900kポリゴン](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/19-level-of-detail.png)

![これは「非常に低い」設定でエクスポートされた同じモデルです。 33kポリゴン。](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/20-level-of-detail.png)

モデルの外観はほぼ同じになりますが、ポリゴンの数は大幅に減少し、Catenda Hubでのナビゲーションがはるかに高速になります。

---

### 3.5 **詳細**

![詳細](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/21-advanced.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/22-advanced.png)

**部品を建築要素としてエクスポート**部品を標準IFC要素のようにエクスポート。

**混合「ソリッドモデル」表現の使用を許可する**このオプションを選択して、ユニットのBRepと押し出しジオメトリの混合を許可します。

**ジオメトリ作成時にアクティブビューを使用する**このオプションを選択して、アクティブビューを使用してジオメトリを生成します。3D以外のビューで使用した場合、予期しない結果が発生する可能性があることに注意してください。

**参照にファミリとタイプ名を使用する**このオプションを選択して、参照にファミリとタイプ名を使用します。

**ルーム体積に2Dルーム境界を使用する**このオプションを選択して、ルーム体積を計算するための簡略化されたアプローチ（2D空間境界の押し出しに基づく）を使用します。これはIFC 2x2へのエクスポート時の標準でもあります。

**IfcSiteの高さをサイトローカル配置原点に含める**このオプションを選択して、IfcSiteのローカル位置のZ-オフセットから高さを含めます。オプションを削除して除外します。

**エクスポート後、要素パラメータにIFC GUIDを保存する**このオプションを選択して、生成されたIFC GUIDをエクスポート後にプロジェクトファイルに保存します。これにより、アイテムとそのタイプおよびプロジェクト情報にプロジェクト、ウェブサイト、および建物ガイド用の「IFC GUID」パラメータが追加されます。

**バウンディングボックスをエクスポート**このオプションを選択して、「バウンディングボックス」表現をエクスポートします。このオプションはGSAエクスポート用に自動的に選択されたままになります。

**テッセレーション化されたジオメトリを三角形分割として保持**複雑な曲線要素またはシェルがあり、IFCエクスポート後に正しく表示されない場合は、このオプションを選択できます。ただし、非常に重いIFCファイルが生成される可能性があることに注意してください。

**IFCType名にはタイプ名のみを使用**このオプションを選択すると、オブジェクトのBAT-IDまたはIDがエンティティの名前として表示されます。

**表示可能なRevit名をIFCEntity名として使用する**このオプションを選択すると、Revitオブジェクト名がエンティティの名前になります。

**ファセット付き床と屋根を常に単一のIFCエンティティとしてエクスポート**このオプションを選択して、複数のフェースを持つ床と屋根のフェースを1つのエンティティに結合します。

**「最終更新」ユーザーをプロジェクト情報の作成者に設定する**このオプションを選択すると、このエクスポートの変更の作成者であるかどうかが選択されます

**エクスポートするエンティティ**これが開くIFCエンティティ選択メニューの見え方です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/23-advanced.png)

---

### 3.6 **地理参照**

Revit座標がプロジェクト内の他のモデルと同期されているため、同じ場所に配置されることが重要です。したがって、Catenda Hubでポイント測定で座標を測定し、Catenda Hubで測定したポイントと同じ場所にあるRevitの座標ベースを指定してください。

![座標をポイントで指定](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/24-geographic-reference.png)

このオプションは「管理」タブ→「座標」→「座標ベースを指定」で見つけることができます。_ポイントで座標を指定_ 北/南、東/西、高さの座標を指定して、モデルを再配置し、モデルを真北に回転します。Revitでは、90度の角度でモデル化する方が簡単であり、モデル全体を回転させたくない場合があります。この場合は、代わりに真北を回転させることができます。このオプションは、「管理」タブの「座標」の下にある「位置」ドロップダウンに表示されます。

![地理参照](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/25-geographic-reference.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/26-geographic-reference.png)

**プロジェクトサイト**内部

**座標ベース**この設定を変更して、プロジェクトが北を向くように確認できます 共有座標 - デフォルト測地点 プロジェクトベースポイント 内部原点 プロジェクトベースポイント 真北に向き合った 内部原点 真北に向き合った

> **注:** 「挿入」タブでIFCをリンクした場合、リンクされたファイルはオブジェクトの近くに配置され、IFCで説明されている場所にはなりません。 代わりに、IFCを正しい場所にインポートするには、「ファイル」→「開く」→「IFC」をクリックします。

**上書き**ここで、投影された座標系参照を上書きできます。

---

### 3.7 **企業情報**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/27-company-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/28-company-info.png)

このメニューは、左側のメニューでIFC2x3 COBie 2.4デザイン配信可能ビューセットアップが選択されている場合にのみ利用可能です。

---

### 3.8 **プロジェクト情報**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/29-project-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/30-project-info.png)

このメニューは、左側のメニューでIFC2x3 COBie 2.4デザイン配信可能ビューセットアップが選択されている場合にのみ利用可能です。

---

## 4. **IFCオプション**

RevitプロジェクトのIFCオプションは以下の場所にあります。

`ファイル→エクスポート→オプション→IFCオプション`

![エクスポート→オプション→IFCオプション](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/31-ifc-options.png)

> **注:** Revit 2026以降では、このオプションは`エクスポート→IFC→一般→カテゴリマッピング→ドロップダウンの右側のアクションメニュー`で利用可能です

ここの_IFCオプション_内で、モデルをIFCファイルにエクスポートするための設定を行います。ここでは、モデルをIFCにエクスポートするためのセットアップ自体をカスタマイズできます。このマニュアルの最初に述べられたことは、モデルから多くの情報を取り出す必要がないということです。エクスポート前に不要な情報をオフにしてください。

![IFCエクスポートクラス](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/32-ifc-options.png)

Catenda Hubでグリッドを表示することは可能であり、Revitモデルに含まれている場合は、IFCオプションでグリッドをIFCにエクスポートするように設定できます。デフォルトでは、Revitからエクスポートされません。

## 5. **色と材料**

Catendaに表示される色は、インポートされるIFCファイルから読み取られます。ファミリの材料プロパティがIFCパラメータに追加されている場合、材料プロパティの材料の色がIFCに追加され、Catendaに表示されます。Revitでは、材料はマテリアルブラウザにあります。

`管理タブ→設定セクション→マテリアル`
マテリアルブラウザでは、色の設定がマテリアルのグラフィックスタブにあります。

![管理→マテリアル→マテリアルブラウザ→新しいマテリアルの作成](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/33-colors-and-materials.png)

シェーディングをレンダリング設定にロックすることもできます。

![外観](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/34-colors-and-materials.png)

Catenda 3Dビューアの表面は、光源なしでフラットシェーディングされます。以下の値は、3Dビューアに表面を表示するときにCatendaによって解釈されます。

汎用

- 色
- 画像フェード

透明性

- 量
- 画像フェード
- 半透明性

色合い

- 色合いの色
