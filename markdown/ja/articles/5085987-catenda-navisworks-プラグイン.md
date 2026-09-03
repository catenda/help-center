# Catenda Navisworksプラグイン

> **注釈:** プラグインのインストールファイルは[この記事](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations)にあります。

Catenda Navisworksプラグインは、Nemetchek Archicadにインストールできるプラグインです。このプラグインを使用すると、3Dビューポイント、トピック、およびドキュメントについて、プロジェクトの他のメンバーと協力できます。

この記事では、以下のトピックについて説明します：

## 1. **プラグインについて**

Autodesk®Navisworks®用のCatenda Hubアドインは、Catenda Hubで協力するプロジェクトに最適なツールです。すべてのトピックはNavisworksとCatenda Hubの間でリアルタイムで同期され、トピックを作成、アクセス、共有、および通信できます。トピック形式はBCFなので、トピックはBCF対応のBIMソフトウェアまたはプラットフォーム全体で共有できます。このアドインを使用すると、Navisworks内からシームレスにトピックを視覚化、作成、および編集できます。また、Catenda Hubに保存されているIFCモデルをダウンロードしてローカルクライアントにフェデレートできます。

### 1.1 **機能は以下の通りです:**

- すべてのCatendaプロジェクトへのアクセス
- トピックリスト全体でトピックをフィルタリングして管理
- Navis Worksから直接新しいトピックを作成
- Navisworksモデル内のトピックを特定
- 各コメントに対して新しい3Dビューを作成
- Clash detectorを使用して検出されたクラッシュからBCFトピックを作成
- 他のプロジェクトメンバーにトピックを割り当て
- トピックのステータスおよび他のプロパティを変更

## 2. **クラウドベースの協力**

Catenda Hubは、建築のライフサイクル全体にわたるクラウドベースのコラボレーションプラットフォームにプロジェクト情報をもたらします。Catendaは、プロジェクト開始から引き渡しとその先まで、プロジェクト情報を管理し、すべてのプロジェクトフェーズ全体でデータと知識を保持することを保証します。

## 3. **オープン標準**

Catenda Hubは、buildingSMART標準(IFC、bSDD、BCF)すべてのサポート機能を備えたBIMコラボレーションツールです。独自のソフトウェアへの簡単な実装のために、一連のAPIが付属しています。

[YouTubeビデオ](https://www.youtube.com/embed/osHul8oKysE?rel=0)

## 4. **インストール**

Catenda Navisworksプラグインを Windows にインストールすると、インストール ファイルが次のフォルダに表示されます。

`C:\ProgramData\Autodesk\ApplicationPlugins\Catenda.BCF.bundle`

プラグインで構成された設定は、ここにあります：

`C:\Users\<Username>\AppData\Local\Autodesk_Inc\Roamer.exe_Url_<GUID>\<Version>`

### 4.1 **アンインストール**

プラグインをアンインストールするには、次のWindowsメニューに移動します：

`Windowsの設定 -> アプリ -> インストール済みアプリ`

リストでCatenda Navisworks BCFプラグインバージョン\<version>を検索し、右側のアクションメニューをクリックしてアンインストールします。

## 5. **Catendaタブ**

プラグインをインストール後、Catendaタブが表示されます。タブが表示されるためにNavisworksの再起動が必要な場合があります。Navisworksのホームページでは、タブは最初グレーアウトされます。

新しいNavisworksプロジェクトを開始するか、既存のプロジェクトを開いて開始します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/01-catenda-tab.png)

これは、選択時のCatendaタブの外観です

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/02-catenda-tab.png)

### 5.1 **Catenda**

Catendaタブの[Catendaプラグイン]メニューの[Catenda]ボタンをクリックすると、Catenda Hubのデフォルトブラウザが[サインインページ](https://support.catenda.com/en/articles/7891486-sign-in-page)で開きます。

### 5.2 **BCFプラグイン**

Catendaタブの[Catendaプラグイン]メニューの[BCFプラグイン]ボタンをクリックすると、設定メニューがアクティブな状態でCatenda Navisworksプラグインが開きます。Catenda Navisworksプラグインの設定メニューは、次のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/03-bcf-plugin.png)

**プラグインをドッキング**ウィンドウのタイトルバーをアプリケーションの任意の側にドラッグしてドッキングします。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/04-bcf-plugin.png)

これは、右側にドッキングされた場合のアプリケーションの外観です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/05-bcf-plugin.png)

## 6. **設定**

左上の[ログイン]をクリックした後、設定メニューの外観は次のようになります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/06-settings.png)

左側にはCatendaのサインインページが表示されます。[サインイン記事](https://support.catenda.com/en/articles/7891486-sign-in-page)の説明に従ってサインインしてください。

設定メニューは、正常にログインした後、次のように見える場合があります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/07-settings.png)

ログインセッションがタイムアウトした場合は、更新ボタンを使用してログインセッションを更新できます。

### 6.1 **認証**

**トークン**サインイン後のCatenda認証トークンがここに表示されます。

### 6.2 **IFCGuid**

**カテゴリと属性**カテゴリのデフォルト: Element 属性のデフォルト: IfcGUID

**プロパティマッピング** Catenda Navisworksプラグインは、IFC内のIfcProjectのGUIDに基づいて、オブジェクトをトピック内のビューポイントにアタッチします。Navisworksでは、このGUIDはオブジェクトのプロパティにあります。以下は、オブジェクトが選択された状態の例です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/08-ifcguid.png)

IFCの内容によっては、IfcProject GUIDが他のプロパティまたはカテゴリにある場合があります。特に、Navisworksが英語以外の言語設定で起動された場合、要素カテゴリの名前は、Catenda Navisworksプラグインでデフォルトがまだ英語のままである言語になります。これを解決するには、カテゴリをNavisworksが起動する言語の要素の単語に変更します。

2番目、3番目、4番目のカテゴリと属性 IfcProject GUIDを含める可能性のある複数のカテゴリと属性がある場合は、それらも追加できます。

### 6.3 **パス**

**ダウンロードパス**プラグインを通じてダウンロードされるモデルおよびドキュメントが最終的に保存されるファイルの場所。

### 6.4 **スナップショット**

**配置**右 - デフォルト スナップショットが右に表示されます

下 スナップショットが下に表示されます

## 7. **トピックリスト**

トピックリストメニューでは、異なるプロジェクトのトピックリスト内のトピックの概要を確認できます。これがトピックリストメニューの外観です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/09-topic-boards.png)

プロジェクトタブをクリックして、トピックリストタブでそのプロジェクト内のトピックリストのリストを読み込みます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/10-topic-boards.png)

### 7.1 **新規トピック**

[新規トピック]ボタンをクリックして、新しいトピックを作成します。

## 8. **トピック**

トピックメニューでは、選択したトピックを編集でき、新しいトピックを送信できます。これがトピックメニューの外観です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/11-topic.png)

### 8.1 **ナビゲーション矢印**

メニュー内のナビゲーション矢印を使用して、トピックボード内の異なるトピック間を移動します。

### 8.2 **新規トピック**

新しいトピックを作成

### 8.3 **ビューポイントを追加**

現在のカメラ位置のビューポイントを現在のトピックに追加します。

### 8.4 **更新**

プラグインに追加された情報をCatendaのトピックで更新します。

### 8.5 **トピック番号**

プロジェクト内のトピックの番号。

### 8.6 **更新**

Catendaからトピック内の最新情報を読み込みます。

### 8.7 **クリッピングプレーンをクリア**

[クリッピングプレーンをクリア]ボタンをクリックして、ビューアのクリッピングプレーンをクリアします。

## 9. **クラッシュ**

クラッシュメニューでは、クラッシュ検出検出の結果としてトピックを送信できます。これはクラッシュメニューの外観です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/12-clashes.png)

### 9.1 **クラッシュ検出テストの実行**

クラッシュメニューを開始するには、リボン内でClash Detectiveを見つけます：

`ホームタブ -> ツールメニュー -> Clash Detective`

**テスト概要**新しいテストを追加します。これはテスト概要の外観です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/13-running-a-clash-detective-test.png)

**ルール**ルールを選択するか、新しいルールを作成します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/14-running-a-clash-detective-test.png)

**選択**クラッシュについて相互にチェックするモデルを選択し、テストを実行します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/15-running-a-clash-detective-test.png)

**結果**結果を確認して、クラッシュに名前を付けます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/16-running-a-clash-detective-test.png)

**コンテキストメニュー**クラッシュ行を右クリックして、次のコンテキストメニューを開きます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/17-running-a-clash-detective-test.png)

グループ 同様のタイプのクラッシュをグループ化します。

ビューポイント [クラッシュに焦点を当てる]でビューポイントを調整してから、コンテキストメニューのビューポイントメニューを再度開いて、ビューポイントをクラッシュに保存します。これはCatendaのトピックで終了するビューポイントです。

表示設定 右側の[表示設定]をクリックして、表示設定を開きます。

ハイライト 相互にクラッシュしているいずれかのモデルからオブジェクトの色を変更します。

分離 透明度設定

ビューポイント ビューポイントを自動更新、自動読み込み、または手動読み込みに設定します。

シミュレーション シミュレーションを表示するかどうか

コンテキストで表示 すべて、ファイル、またはホーム。

アイテム ここで、選択されたクラッシュに関連するオブジェクトが表示されます。

**レポート**これはレポートメニューの外観です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/18-running-a-clash-detective-test.png)

コンテンツ レポートの内容を選択します

クラッシュを含める 含めるクラッシュを選択します

出力設定 テスト概要で選択されたテストのテスト概要の現在のテスト、またはすべてのテストについてすべてのテストを選択します。

レポート形式 ビューポイントとしてオプションを使用し、[結果の強調表示を保持]ボックスをチェックします。

### 9.2 **Catendaプラグインのクラッシュ**

クラッシュテストが実行された後、ビューポイントがクラッシュタブに表示されます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/19-clashes-in-catenda-plugin.png)

### 9.3 **トピックを追加**

1つ以上のクラッシュを選択してトピックを作成し、トピックにタイトルを付けて、トピックを追加をクリックします。

**トピックドロップダウンを追加**トピックは、次の方法で作成できます：

1つの統合トピックを作成

- 選択したクラッシュから1つのトピックを作成
  - Navisworks Clash Detectiveで選択された各クラッシュに対して、ビューポイントを持つトピックを作成します。
- 選択したクラッシュから1つのトピックを作成（統合ビューポイント）
  - Navisworks Clash Detectiveで選択されたすべてのクラッシュを含めるためにズームアウトされた単一のビューポイントを持つトピックを作成します。

複数のトピックを作成

- 選択したクラッシュごとに1つのトピックを作成
  - Catenda Navisworksプラグインで選択された各クラッシュに対して、トピックを作成します。
- クラッシュグループごとに1つのトピックを作成
  - Catenda Navisworksプラグインで選択されたクラッシュグループごとに、クラッシュグループ内の各クラッシュに対してビューポイントを持つトピックを作成します。
- クラッシュグループごとに1つのトピックを作成（統合ビューポイント）
  - Catenda Navisworksプラグインで選択されたクラッシュグループごとに、選択されたすべてのクラッシュを含めるためにズームアウトされた単一のビューポイントを持つトピックを作成します。
- グループ化されていない各クラッシュに対して1つのトピックを作成
  - Catenda Navisworksプラグインで選択されたグループ化されていない各クラッシュに対して、トピックを作成します

### 9.4 **ステータスを変更**

Catenda Navisworksプラグインで選択されたクラッシュのステータスを、Navisworksテスト結果で次のステータスのいずれかに変更します。

- 新規
- アクティブ
- レビュー済み
- 承認済み
- 解決済み

## 10. **モデル**

トピックボードメニューで選択したCatendaプロジェクトからモデルリビジョンをダウンロード、開き、Navisworksプロジェクトに追加します。これはモデルメニューの外観です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/20-models.png)

### 10.1 **検索**

Catendaプロジェクト内のモデルを検索します

### 10.2 **更新**

Catendaプロジェクトからモデルリストを更新します

### 10.3 **選択したダウンロード**

選択したモデルをCatendaからローカルシステムにダウンロードします

### 10.4 **選択したものを開く**

選択したモデルを新しいNavisworksプロジェクトで開きます

### 10.5 **選択したものを追加**

選択したモデルを現在のNavisworksプロジェクトに追加します。モデルを現在のNavisworksプロジェクトに追加できるようにするには、まずダウンロードする必要があります。

### 10.6 **Catendaドキュメントライブラリ**

Catendaドキュメントライブラリウィンドウを開きます。これはドキュメントライブラリウィンドウの外観です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/21-catenda-document-library.png)

**ナビゲーション矢印**フォルダ構造の上のレベルに移動します。

**更新**ドキュメントライブラリ内のドキュメントを更新します。

**ダウンロード**選択したCatendaドキュメントの最新リビジョンをローカルシステムにダウンロードします。

**アップロード**選択したCatendaドキュメントの最新リビジョンをローカルシステムにアップロードします。

**列**ナビゲーション フォルダの行のナビゲーション矢印または別の場所をダブルクリックしてそのフォルダを開きます。

名前 フォルダまたはドキュメントの名前

ドキュメント名 ドキュメントの名前

画像 ドキュメントの画像

リビジョン ドキュメントのリビジョン番号

### 10.7 **列**

**選択ボックス**モデルの選択ボックス

**モデルアイコン**モデルのアイコン

**名前**モデルの名前

**リビジョンCatenda** Catendaプロジェクト内の最新リビジョン番号

**リビジョンNavisworks**

**ダウンロード**ダウンロードアイコンをクリックして、最新のモデルリビジョンをダウンロードします。リビジョン navisworks列にリビジョン番号が表示されると、モデルがダウンロードされます。

**開く** [開く]アイコンをクリックして、モデルを新しいNavisworksプロジェクトで開きます。

**追加**追加アイコンをクリックして、モデルを現在のNavisworksプロジェクトに追加します。

### 10.8 **Catenda Hubからモデルをダウンロード**

このプラグインとモデルタブのアクションを使用して、CatendaプロジェクトからIFCモデルを簡単にダウンロードできます。ローカルデバイスにダウンロードするには：ダウンロードしたい各モデルのダウンロードボタンをクリックします。モデルは、設定タブで指定されたダウンロードパスの下にあるプロジェクト名の新しいフォルダに保存されます。例えば：

`C:\...\Documents\Catendaプロジェクト名`

### 10.9 **Catenda HubからのIFCを使用したマージ済み.nwfファイルの作成**

Catendaプロジェクトから Catenda プラグイン内のBCFビューポイントを使用できるようにするには、Catendaからの IFCを含むマージされたNavisWorksファイルが必要です。上記の手順に従って、マージしたいIFCモデルをダウンロードします。NavisWorksでダウンロードしたファイルの1つを開きます。「追加」を使用して、同じプロジェクトからのモデルをNavisWorksモデルにマージします。マージするすべてのファイルを追加したら、ファイルを.nwfファイルとして保存します。ダウンロードしたIFCファイルと同じフォルダにファイルを保存します。Navisworks内でBCFビューポイントを表示するときは、このマージされたファイルを使用します。NavisWorksでコリジョンテストを実行するときは、このマージされたファイルを使用することもできます。
