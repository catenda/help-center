# Catenda Power BI コネクタ

> **注:** このアプリケーションのインストールファイルは[こちら](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)にあります

この記事では、Catenda HUBデータベースをPowerBIとリンクする方法について説明します。リンクすることで、Catenda HUB上のデータへの直接アクセスをPowerBIで取得できます。このデータは、タスク、ドキュメント、またはメンバーなどを評価するために使用できます。

## 1. **インストール**

Catenda Desktop ConnectorがWindowsにインストールされると、インストールファイルは次のフォルダに表示されます。

`C:\Users\<Username>\Documents\Power BI Desktop\Custom connectors`

### 1.1 **アンインストール**

プラグインをアンインストールするには、インストールフォルダに移動して、次のファイルを実行します：

`uninstall.exe`

フォルダが削除されてプラグインがまだアクティブな場合は、プラグインを再度インストールして、作成されたアンインストールファイルでアンインストールしてください。

## 2. **データを取得して接続**

PowerBIからCatenda HUBデータベースへの接続を作成するには、以下の手順を実行してください: PowerBIを開き、画面の中央にある"別のソースからデータを取得"をクリックするか、トップリボンのホームメニューでデータを取得アクションを使用します。アクションを表示するには、リボンを拡張する必要がある場合があります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/01-get-data-and-connect.png)

ターゲットソースを[その他] --> [Catenda]の下で選択します。"_接続_"を使用してデータベースへの接続を確立します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/02-get-data-and-connect.png)

## 3. **データを読み込む**

アクセス権のあるすべてのプロジェクトが一覧表示されるナビゲータが開きます。対応するプロジェクトとリンクするテーブルを選択します。この例では、PowerBIで[トピック](https://support.catenda.com/en/articles/4670271-topics-page)を評価したいと思います。"_読み込む_"をクリックしてデータセットを読み込みます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/03-load-data.png)

ここで、次のデータセットから選択できます: _ドキュメント_

**ドキュメントラベル**

**ラベル**

**メンバー**

**モデル**

**モデルリビジョン**

**プロダクト**

**チーム**

**チームメンバー**

**トークン**

**トピック**

**トピックリスト**

**トピックラベル**

**トピックステータス**

**トピックタイプ**

読み込みをクリックすると、PowerBIコネクタはAPIからトピックデータのフェッチを開始します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/04-load-data.png)

データは右側に表示されます。適切なデータフィールドを選択して、分析を作成します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/05-load-data.png)

> **注:** 異なるデータセットを読み込んでリンクさせます。これにより、完全な概要を提供するインタラクティブなダッシュボードを作成できます。

プロジェクトに存在するデータと読み込むデータに応じて、異なるリレーションが自動的に作成されます。

## 4. **テーブル表示**

トピックデータがテーブル表示でどのように表示されるかの例は次のとおりです：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/06-table-view.png)

## 5. **モデル表示**

プロジェクトにすべての情報が存在し、すべてのプロジェクトデータを読み込んだときに、モデル表示で接続がどのように見えるかを示すマップです：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/07-model-view.png)
