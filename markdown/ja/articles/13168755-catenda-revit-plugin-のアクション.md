# Catenda Revit Plugin のアクション

> **注意:** プラグインのインストールファイルは [この記事](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations) で確認できます。

[Catenda Revit Plugin](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin) のアクションは、Revit アプリケーション内のプラグイン ウィンドウの右上に表示されます。

このアクション メニューは以下のように表示されます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/01-intro.png)

以下のトピックに関する情報は、この記事に記載されています：

以下のトピックはこの記事で説明されています：

## 1. **1. 新規トピック**

右上の緑色の「新規トピック」ボタンをクリックして、左上のドロップダウンメニューで現在選択されているプロジェクトに新しいトピックを作成します。トピックは、左上の2番目のドロップダウンメニューで選択されているトピックリストに作成されます。_アクセス権限が必要：_ トピックリストへの書き込みアクセス権

トピックが作成されるとすぐに、Catenda Hub がブラウザ経由で、また他のプログラムの Catenda プラグインを通じて表示されます。新しいトピック ページは以下のように表示されます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/02-1-new-topic.png)

トピックを送信するために必要な最小限の情報はタイトルです。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/03-1-new-topic.png)

### 1.1 **1.1 送信**

トピックがプロジェクトと共有する準備ができたら、「送信」をクリックしてトピックをトピックリストに送信します。

## 2. **2. IFC をアップロード**

右上の3つの点で開くアクション メニューで「IFC をアップロード」をクリックして、現在の Revit モデルを IFC ファイルとして Catenda Hub に直接アップロードします。IFC のアップロード ページは以下のように表示されます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/04-2-upload-ifc.png)

### 2.1 **2.1 モデルを選択**

このドロップダウン メニューには、選択したプロジェクトから既存のモデルが表示されます。プロジェクトにモデルが存在しない場合は、まずブラウザ経由で Catenda に空のモデルを作成してください。アップロードされた IFC は、選択したモデルの新しいリビジョンになります。Catenda の各モデルは document コンテナーにリンクされているため、アップロード後、リビジョンはプロジェクトのモデルおよびドキュメント領域の両方に表示されます。

### 2.2 **2.2 ファイル名**

アップロードに関連付けるオプションのファイル名を入力します。このフィールドでは ASCII 文字のみがサポートされています。

### 2.3 **2.3 コメントを入力**

アップロードに関連付けるコメント（必須）を入力します。コメントを追加すると、アップロード ボタンがハイライト表示され、クリック可能になります。このフィールドでは ASCII 文字のみがサポートされています。

### 2.4 **2.4 エクスポート設定**

IFC 設定を選択します。新しい設定は Revit の IFC エクスポート メニューで作成できます。Catenda Hub に適したセットアップの \<Catenda setup> を選択することもできます。

これらは Catenda セットアップのエクスポート設定です

```
selectedConfig.Name = "<Catenda Setup>"; selectedConfig.IFCVersion = IFCVersion.IFC2x3CV2; selectedConfig.SpaceBoundaries = 1; selectedConfig.ActivePhaseId = ElementId.InvalidElementId; selectedConfig.ExportBaseQuantities = true; selectedConfig.SplitWallsAndColumns = false; selectedConfig.VisibleElementsOfCurrentView = false; selectedConfig.Use2DRoomBoundaryForVolume = false; selectedConfig.UseFamilyAndTypeNameForReference = true; selectedConfig.ExportInternalRevitPropertySets = true; selectedConfig.ExportIFCCommonPropertySets = true; selectedConfig.Export2DElements = false; selectedConfig.ExportPartsAsBuildingElements = true; selectedConfig.ExportBoundingBox = false; selectedConfig.ExportSolidModelRep = false; selectedConfig.ExportSchedulesAsPsets = false; selectedConfig.ExportUserDefinedPsets = false; selectedConfig.ExportUserDefinedPsetsFileName = ""; selectedConfig.ExportLinkedFiles = false; selectedConfig.IncludeSiteElevation = true; selectedConfig.UseActiveViewGeometry = false; selectedConfig.ExportSpecificSchedules = false; selectedConfig.TessellationLevelOfDetail = 0; selectedConfig.StoreIFCGUID = true; selectedConfig.ExportRoomsInView = true；
```

### 2.5 **2.5 アップロード**

「アップロード」をクリックして IFC をアップロードします。アップロードするにはコメントを追加する必要があります。_アクセス権限が必要：_ モデルにリンクされているドキュメントへの書き込みアクセス権。

## 3. **3. 設定**

設定ページでは、[ズーム機能](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin#h_36392f671a) を使用する際に、プラグインが 3D ビューをどのように作成するかを変更できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/05-3-settings.png)

### 3.1 **3.1 トピックに戻る**

「トピックに戻る」をクリックしてトピック リストに戻ります。

### 3.2 **3.2 ナビゲーション**

**3D ビューを正投影で保つ**このオプションは、対応するビューポイントが透視図で作成されている場合でも、Revit 3D ビューを正投影に強制します。

**トピックごとに新しいビューを作成**ズーム機能を使用するたびに同じ 3D ビューを再利用する代わりに、このオプションはズーム機能を使用するたびにトピックごとに新しい 3D ビューを作成します。

**3D ビュー名サフィックス**このテキストは、ズーム機能を使用して作成された 3D ビューの名前に追加されます。

### 3.3 **3.4 ビューポイント変換**

ビューポイント変換を使用すると、Revit のビューポイントをオフセット量で設定できます。ここで値が設定されている場合、トピックからのビューポイントが再生されるたびに、ビューポイントはその量だけオフセットされます。これは、トピックのビューポイント内の座標が Revit プロジェクトで設定された座標と一致しない場合に便利です。

**3.4.1 X (E/W)** X 方向の変換。正の値または負の値に応じた東または西。単位: メートル

**3.4.2 Y (N/S)** Y 方向の変換。正の値または負の値に応じた北または南。単位: メートル

**3.4.3 Z (Elev)** Z 方向の変換。正の値または負の値に応じた標高。単位: メートル

**3.4.4 角度**回転変換。正の値または負の値に応じた標高。単位: 度。カメラは同じ高さに留まり、モデル内のポイント周辺でカメラが回転します。

## 4. **4. アカウント**

デフォルト ブラウザーで Catenda Hub アカウント ページを開きます。[ここ](https://support.catenda.com/en/articles/6880968-account-page) をクリックして、アカウント ページの詳細をご覧ください。

## 5. **5. サインアウト**

「サインアウト」をクリックして、プラグイン内から Catenda Hub からサインアウトします。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/06-5-sign-out.png)

サインアウト後、サインイン ページが表示され、ユーザー名とパスワードを使用して同じアカウントまたは別のアカウントにサインインできます。[ここ](https://support.catenda.com/en/articles/7891486-sign-in-page) をクリックして、サインイン ページの詳細をご覧ください。

再度サインインすると、プロジェクト リストの最初のプロジェクトが表示されます。異なるプロジェクトに移動するには、プロジェクト リストでプロジェクトを再度選択します。
