# Catenda Navisworksプラグイン

> **注：** プラグインのインストールファイルは[この記事](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations)にあります。

Catenda Navisworksプラグインは、Nemetchek Archicadにインストールできるプラグインです。このプラグインを使用すると、建設プロジェクトの他のメンバーと3Dビューポイント、トピック、ドキュメントについて協力できます。

## 1. **プラグインについて**

Autodesk® Navisworks®用のCatenda Hubアドインは、Catenda Hubで協力するプロジェクトに最適なツールです。すべてのトピックがNavisworksとCatenda Hubの間でリアルタイムに同期され、トピックの作成、アクセス、共有、コミュニケーションが可能になります。トピック形式はBCFであり、BCF対応のBIMソフトウェアまたはプラットフォーム全体でトピックを共有できます。このアドインを使用すると、Navisworks内からトピックをシームレスに表示、作成、編集できます。また、Catenda Hubに保存されているIFCモデルをダウンロードしてローカルクライアントにフェデレーションすることもできます。

### 1.1 **機能には以下が含まれます：**

- すべてのCatendaプロジェクトへのアクセス
- トピックボード全体でトピックをフィルタリングして管理
- Navis Worksから直接新しいトピックを作成
- Navisworksモデル内のトピックを検索
- 各コメントの新しい3Dビューを作成
- Clash Detectiveを使用して検出された衝突からBCFトピックを作成
- トピックを他のプロジェクトメンバーに割り当て
- トピックのステータスおよびその他のプロパティを変更

## 2. **クラウドベースのコラボレーション**

Catenda Hubは、建物のライフサイクル全体にわたるクラウドベースのコラボレーションプラットフォームで、建設データを生動化します。Catendaはプロジェクト情報を最初から引き継ぎまでおよびそれ以降まで管理し、すべてのプロジェクトフェーズ全体でデータと知識の保持を確保します。

## 3. **オープン標準**

Catenda Hubは、buildingSMART標準（IFC、bSDD、BCF）すべてをサポートするBIMコラボレーションツールです。独自のソフトウェアへの簡単な実装のための一連のAPIが付属しています。

[YouTubeビデオ](https://www.youtube.com/embed/osHul8oKysE?rel=0)

## 4. **インストール**

Catenda NavisworksプラグインがWindowsにインストールされると、インストールファイルは以下のフォルダに表示されます。

`C:\ProgramData\Autodesk\ApplicationPlugins\Catenda.BCF.bundle`

プラグインで構成されている設定はここにあります。

`C:\Users\<Username>\AppData\Local\Autodesk_Inc\Roamer.exe_Url_<GUID>\<Version>`

### 4.1 **アンインストール**

プラグインをアンインストールするには、以下のWindowsメニューに移動します。

`Windowsの設定 -> アプリ -> インストール済みアプリ`

リストからCatenda Navisworks BCFプラグインバージョン\<version>を見つけ、右側のアクションメニューをクリックしてアンインストールします。

## 5. **Catendaタブ**

プラグインをインストールすると、Catendaタブが表示されます。タブが表示されるには、Navisworksを再起動する必要がある場合があります。Navisworksのホームページでは、タブは最初はグレーアウトされます。

新しいNavisworksプロジェクトを開始するか、開きます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/01-catenda-tab.png)

選択時のCatendaタブの外観を示す

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/02-catenda-tab.png)

### 5.1 **Catenda**

CatendaタブのCatendaプラグインメニューのCatendaボタンは、Catenda Hubの[サインインページ](https://support.catenda.com/en/articles/7891486-sign-in-page)でデフォルトブラウザを開きます。

### 5.2 **BCFプラグイン**

CatendaタブのCatendaプラグインメニューのBCFプラグインボタンは、Catenda Navisworksプラグインを設定メニューが有効な状態で開きます。Catenda Navisworksプラグインの設定メニューは、このような外観になります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/03-bcf-plugin.png)

**プラグインをドッキング**ウィンドウのタイトルバーをアプリケーションの任意の側にドラッグしてドッキングします。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/04-bcf-plugin.png)

右側にドッキングされたときのアプリケーションの外観を示す

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/05-bcf-plugin.png)

## 6. **設定**

これは、左上の[ログイン]をクリックした後の設定メニューの外観です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/06-settings.png)

左側にはCatendaのサインインページが表示されます。[サインイン記事](https://support.catenda.com/en/articles/7891486-sign-in-page)に記載されているステップに従ってサインインします。

正常にログインした後の設定メニューの外観を示す

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/07-settings.png)

ログインセッションがタイムアウトした場合、更新ボタンを使用してログインセッションをリフレッシュできます。

### 6.1 **認証**

**トークン**ここにはサインイン後のCatenda認証トークンが表示されます。

### 6.2 **IFCGuid**

**カテゴリとプロパティ**カテゴリデフォルト：要素プロパティデフォルト：IfcGUID

**プロパティマッピング** Catenda Navisworksプラグインは、IFC内のIfcProjectのGUIDに基づいてオブジェクトをトピック内のビューポイントに接続します。Navisworksでは、このGUIDはオブジェクトのプロパティに表示されます。以下は、オブジェクトが選択されている例です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/08-ifcguid.png)

IFCの内容に応じて、IfcProject GUIDは1つ以上の他のプロパティまたはカテゴリで見つかる可能性があります。特に、Navisworksが英語以外の言語設定で起動されている場合、Element カテゴリの名前は、Catenda Navisworksプラグインではデフォルトの単語が引き続き英語である言語の要素の単語になります。これを解決するには、カテゴリをNavisworksが起動されている言語のElementの単語に変更します。

2番目、3番目、4番目のカテゴリとプロパティ IfcProject GUIDを含む可能性のある複数のカテゴリとプロパティがある場合は、それらも追加できます。

### 6.3 **パス**

**DownloadPath**プラグインを通じてダウンロードされたモデルとドキュメントが保存されるファイルの場所。

### 6.4 **スナップショット**

**配置**右 - デフォルト スナップショットは右に表示されます

下 スナップショットは下に表示されます

## 7. **トピックボード**

トピックボードメニューでは、異なるプロジェクトのトピックボード内のトピックの概要を確認できます。これはトピックボードメニューのような外観です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/09-topic-boards.png)

プロジェクトタブをクリックして、そのプロジェクトのトピックボード一覧をトピックボードタブに読み込みます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/10-topic-boards.png)

### 7.1 **新しいトピック**

[新しいトピック]ボタンをクリックして、新しいトピックを作成します。

## 8. **トピック**

トピックメニューでは、選択したトピックを編集し、新しいトピックを送信できます。これはトピックメニューのような外観です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/11-topic.png)

### 8.1 **ナビゲーション矢印**

ナビゲーション矢印を使用してメニューの異なるトピック間を移動します。

### 8.2 **新しいトピック**

新しいトピックを作成

### 8.3 **ビューポイントを追加**

現在のカメラ位置のビューポイントを現在のトピックに追加します。

### 8.4 **更新**

プラグインに追加された情報でCatendaのトピックを更新します。

### 8.5 **トピック番号**

プロジェクト内のトピック番号。

### 8.6 **更新**

Catendaからのトピック内の最新情報を読み込みます。

### 8.7 **クリッピング平面をクリア**

[クリッピング平面をクリア]ボタンをクリックして、ビューア内のクリッピング平面をクリアします。

## 9. **衝突**

衝突メニューでは、トピックをClash Detectiveの検出結果として送信できます。これは衝突メニューのような外観です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/12-clashes.png)

### 9.1 **衝突検査テストの実行**

衝突メニューを開始するには、リボンでClash Detectiveを見つけます。

`ホームタブ -> ツールメニュー -> Clash Detective`

**テスト概要**新しいテストを追加します。テスト概要の外観を示す。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/13-running-a-clash-detective-test.png)

**ルール**ルールを選択するか、新しいルールを作成します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/14-running-a-clash-detective-test.png)

**選択**相互に衝突をチェックしたいモデルを選択し、テストを実行します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/15-running-a-clash-detective-test.png)

**結果**結果を確認して衝突に名前を付けます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/16-running-a-clash-detective-test.png)

**コンテキストメニュー**衝突行を右クリックして、以下のコンテキストメニューを開きます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/17-running-a-clash-detective-test.png)

グループ 同様の種類の衝突をグループでまとめます。

ビューポイント 衝突にフォーカスしてビューポイントを調整してから、コンテキストメニューのビューポイントメニューを再度開いてビューポイントを衝突に保存します。これは、Catendaのトピックに終わるビューポイントです。

表示設定 右側の[表示設定]をクリックして、表示設定を開きます。

ハイライト 相互に衝突しているどちらかのモデルからオブジェクトの色を変更します。

分離 透明度の設定

ビューポイント ビューポイントを自動更新、自動読み込み、または手動読み込みのいずれかに設定します。

シミュレーション シミュレーションを表示するかどうか

コンテキストで表示 すべて、ファイル、またはホーム。

アイテム ここに、選択された衝突に関連するオブジェクトが表示されます。

**レポート**レポートメニューのような外観を示す。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/18-running-a-clash-detective-test.png)

コンテンツ レポートのコンテンツを選択

衝突を含める 含める衝突を選択

出力設定 テスト概要で選択されたテストの現在のテスト、またはテスト概要の全テストの全テストを個別に、または結合して選択します。

レポート形式 ビューポイントをオプションとして使用し、[結果のハイライトを保持]ボックスをチェックします。

### 9.2 **Catendaプラグインの衝突**

衝突テストが実行された後、ビューポイントが衝突タブに表示されます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/19-clashes-in-catenda-plugin.png)

### 9.3 **トピックを追加**

1つ以上の衝突を選択してトピックを作成 トピックにタイトルを付ける [トピックを追加]をクリック。

**トピックドロップダウンを追加**トピックは次の方法で作成できます。

1つの結合されたトピックを作成

- 選択した衝突から1つのトピックを作成
  - Navisworks Clash Detectiveで選択された各衝突のビューポイント付きのトピックを作成します。
- 選択した衝突から1つのトピック（統合ビューポイント）を作成
  - Navisworks Clash Detectiveで選択されたすべての衝突を含むように拡大された単一のビューポイント付きのトピックを作成します。

複数のトピックを作成

- 選択した各衝突に対して1つのトピックを作成
  - Catenda Navisworksプラグインで選択された各衝突に対してトピックを作成します。
- 衝突グループごとに1つのトピックを作成
  - Catenda Navisworksプラグインで選択された各衝突グループに対して、衝突グループ内の各衝突のビューポイント付きのトピックを作成します。
- 衝突グループごとに1つのトピック（統合ビューポイント）を作成
  - Catenda Navisworksプラグインで選択された各衝突グループに対して、選択されたすべての衝突を含むように拡大された単一のビューポイント付きのトピックを作成します。
- グループ化されていない各衝突に対して1つのトピックを作成
  - Catenda Navisworksプラグインで選択されたグループ化されていない各衝突に対してトピックを作成

### 9.4 **ステータスを変更**

Catenda Navisworksプラグインで選択されている衝突のステータスを、Navisworksテスト結果で以下のステータスの1つに変更します。

- 新規
- アクティブ
- 確認済み
- 承認済み
- 解決済み

## 10. **モデル**

トピックボードメニューで選択されたCatendaプロジェクトからモデルリビジョンをダウンロード、開き、Navisworksプロジェクトに追加します。これはモデルメニューのような外観です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/20-models.png)

### 10.1 **検索**

Catendaプロジェクト内のモデルを検索

### 10.2 **更新**

Catendaプロジェクトからモデル一覧をリフレッシュ

### 10.3 **選択した項目をダウンロード**

選択したモデルをCatendaからローカルシステムにダウンロード

### 10.4 **選択した項目を開く**

選択したモデルを新しいNavisworksプロジェクトで開く

### 10.5 **選択した項目を追加**

選択したモデルを現在のNavisworksプロジェクトに追加します。モデルを現在のNavisworksプロジェクトに追加できるようにするには、最初にダウンロードする必要があります。

### 10.6 **Catendaドキュメントライブラリ**

Catendaドキュメントライブラリウィンドウを開きます。ドキュメントライブラリウィンドウの外観を示す。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/21-catenda-document-library.png)

**ナビゲーション矢印**フォルダ構造のレベルを上げます。

**更新**ドキュメントライブラリ内のドキュメントをリフレッシュします。

**ダウンロード**選択されたCatendaドキュメントの最新リビジョンをローカルシステムにダウンロード。

**アップロード**選択されたCatendaドキュメントの最新リビジョンをローカルシステムにアップロード。

**列**ナビゲーション ナビゲーション矢印をダブルクリックするか、フォルダの行の他の場所をクリックしてそのフォルダを開きます。

名前 フォルダまたはドキュメントの名前

ドキュメント名 ドキュメントの名前

画像 ドキュメントの画像

リビジョン ドキュメントのリビジョン番号

### 10.7 **列**

**選択ボックス**モデルの選択ボックス

**モデルアイコン**モデルのアイコン

**名前**モデルの名前

**リビジョンCatenda** Catendaプロジェクトの最新リビジョン番号

**リビジョンNavisworks**

**ダウンロード**ダウンロードアイコンをクリックして、最新のモデルリビジョンをダウンロード。リビジョン番号がリビジョンNavisworks列に表示されると、モデルはダウンロードされます。

**開く**開くアイコンをクリックして、新しいNavisworksプロジェクトでモデルを開きます。

**追加**追加アイコンをクリックして、モデルを現在のNavisworksプロジェクトに追加します。

### 10.8 **Catenda Hubからモデルをダウンロード**

このプラグインと[モデル]タブのアクションを使用して、Catendaプロジェクトから簡単にIFCモデルをダウンロードできます。ローカルデバイスにダウンロードするには、ダウンロードするモデルごとに[ダウンロード]ボタンをクリックします。モデルは、[設定]タブの下に指定されたダウンロードパスの下にあるプロジェクト名の新しいフォルダに保存されます。例えば：

`C:\...\Documents\Catendaプロジェクト名`

### 10.9 **Catenda Hubからのフォルダを使用してマージされた.nwfファイルを作成**

Catendaプロジェクトの CatendaプラグインからBCFビューポイントを使用できるようにするには、Catendaからの IFCを含むマージされたNavisWorksファイルが必要です。上記の手順に従ってマージしたいIFCモデルをダウンロード。ダウンロードしたファイルの1つをNavisWorksで開きます。"追加"を使用して、同じプロジェクトからより多くのモデルをNavisWorksモデルにマージ。マージしたいファイルすべてをマージしたら、ファイルを.nwfファイルとして保存。ダウンロードしたIFCファイルと同じフォルダにファイルを保存。NavisworksでBCFビューポイントを表示する場合は、このマージされたファイルを使用。このマージされたファイルをNavisWorksで衝突テストを実行するためにも使用できます。
