# Catenda Tekla プラグイン

> Catenda Hub と Tekla を接続

> **注意:** プラグインのインストール ファイルは、[このナレッジベース記事](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations)で確認できます。

このナレッジベース記事では、以下のトピックについて説明します：

## 1. **インストール**

Windows に Catenda Revit プラグインをインストールすると、インストール ファイルは次のフォルダーに配置されます。

`C:\Program Files\Logic\Catenda for Tekla 2025`

### 1.1 **アンインストール**

プラグインをアンインストールするには、次の Windows メニューに移動します：

`Windows の設定 -> アプリ -> インストール済みアプリ`

リストから「Catenda for Catenda for Tekla \<Tekla version>」を見つけ、右側のアクション メニューをクリックしてアンインストールします。

## 2. **重要な情報:**

Tekla には Catenda Hub 専用のビューがあり、このビューを使用して Tekla から Catenda Hub へイシューを作成する必要があります。このビューを使用しないと、作成されたイシューに不一致が生じます (例: viewpoint、オブジェクト選択など)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kvtgs8k1/01-important-info.png)

## 3. **はじめに**

プラグインをインストールした後、Tekla Structures でモデルを開き、Catenda Hub タスク バーの Catenda Hub アイコンをクリックします。

メール アドレスと Catenda Hub パスワードでログインします。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kvtgs8k1/02-getting-started.png)

「アクセスを許可」をクリックして、Tekla プラグインが Catenda Hub アカウントにアクセスできるようにします。これにより、Catenda Hub アドイン の メイン ビューが開きます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kvtgs8k1/03-getting-started.png)

Catenda Hub の Web アプリケーション上の Catenda Hub [アカウント ページ](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a)に移動することで、いつでも Catenda Hub アカウントへのアクセスを取り消すことができます。

## 4. **トピック一覧**

このページでは、Catenda プロジェクト、イシュー ボード、イシューを移動するためのメイン メニューが表示されます。

### 4.1 **インターフェース**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kvtgs8k1/04-interface.png)

1. Catenda プロジェクトを選択
1. このプロジェクト内の issue board を選択
1. 現在選択されている issue board に新しいイシューを作成
1. 現在表示されているイシューをソート
1. Catenda Hub アドイン メニューを開く
1. 表示されているイシューを検索およびフィルター
1. Issue board 内で現在フィルター処理されているイシューのリスト
1. イシューを更新

### 4.2 **プロジェクトと issue board の選択**

Catenda プロジェクトを選択すると、このプロジェクト内の issue board のリストが表示され、1 つを選択して対応するイシューを表示できます。

### 4.3 **Catenda Hub アドイン メニュー**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kvtgs8k1/05-catenda-hub-add-in-menu.png)

1. モデルとリビジョンのリスト
1. Catenda Hub への IFC アップロード用のエクスポート設定
1. Catenda Hub プラグインのバージョン
1. Catenda Hub アカウントをログアウト
