# Catenda Archicadプラグイン

> **注意:** プラグインのインストールファイルは[この記事](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations)にあります。

Catenda ArchicadプラグインはNemetchek Archicadにインストール可能なプラグインです。このプラグインを使用すれば、建設プロジェクトの他のメンバーとともに3D viewpoint、トピック、ドキュメントについて協業できます。

## 1. **インストール**

Catenda ArchicadプラグインをWindowsにインストールすると、インストールファイルは次のフォルダに表示されます。

`C:\Program Files\Catenda\Catenda Archicad Connection\<Archicad Version>\Add-On`

プラグインは次にArchicadを開いたときに、アドオンマネージャーで有効として表示されます。これはデフォルトのアドオンフォルダとは異なることに注意してください。デフォルトのアドオンフォルダの場所は以下の通りです

`C:\Program Files\Graphisoft\<Archicad Version>\Add-Ons`

### 1.1 **アンインストール**

プラグインをアンインストールするには、次のWindowsメニューに移動してください：

`Windowsの設定 -> アプリ -> インストール済みアプリ`

リストから"Catenda Archicad Connection <version>"を見つけ、右側のアクションメニューをクリックしてアンインストールします。

## 2. **Catendaパレット**

プラグインをインストール後、トップバーにCatendaメニュータブが表示されます。このメニューでは「Catenda Hub Issue Manager」ウィンドウが表示されており、「Catenda Hub Issue Managerパレット」が含まれています。このパレットを使用開始するには、フロアプランまたは3Dビューのいずれかを開く必要があります。パレットでは以下が可能です：

- Catenda Hubプロジェクトに移動
- 問題の表示と作成
- モデルとリビジョンのダウンロードとアップロード

## 3. **サインイン**

Catendaパレットを開くと、最初に表示されるのはサインインページです。サインインページは以下のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/01-sign-in.png)

Catendaアカウントがない場合は、右上の「無料でサインアップ」をクリックしてサインアップできます。既にCatendaアカウントをお持ちの場合は、メールアドレスとパスワードを入力し、サインインをクリックしてください。サインイン後、Catendaアカウントへのアクセスを許可するよう求められます。このアクセスを許可すると、ArchicadプラグインはCatendaアカウントの[アプリケーションページ](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a)に表示されます。必要に応じていつでもこのアクセスを取り消すことができます。

### 3.1 **パスワードのリセット**

パスワードを忘れた場合は、「パスワードを忘れた」をクリックすることでリセットできます。パスワードリセットページは以下のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/02-password-reset.png)

メールアドレスを入力して「確認メールを送信」をクリックすると、パスワードのリセット方法を案内するメールが送信されます。5分以内にこのメールを受け取ったことを確認してください。受信トレイに表示されていない場合は、スパムメールまたは迷惑メールフォルダを確認してください。5分以上経過しても受け取っていない場合は、[support@catenda.com](mailto:support@catenda.com)のサポートにお問い合わせください

サインインページに戻るには、右上の「サインイン」をクリックしてください。

## 4. **プロジェクトリスト**

Archicadプラグインを開くと、プロジェクトのリストが表示されます。リストは以下のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/03-project-list.png)

プロジェクトへの招待を受け入れると、プラグイン内のプロジェクトリストと[プロジェクトページ](https://support.catenda.com/en/articles/8400797-projects-page)にプロジェクトが表示されます。

**アクションメニュー**プロフィール画像の横にある3つのドットをクリックして、アクションメニュードロップダウンを開きます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/04-project-list.png)

**モデルとリビジョン**これはモデルとリビジョンページの例です。ここでは、Catendaプロジェクトでアクセス可能なすべてのモデルを確認できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/05-project-list.png)

このページでは、Catendaプロジェクトからarchicadモデルにifcファイルをダウンロードしてインポートできます。モデルのタイムスタンプは相対的です。タイムスタンプにマウスを合わせると、リビジョンが公開された時期に関する正確な情報が表示されます。モデルリビジョンの横の矢印ボタンをクリックするとIFCファイルをインポートできます。このファイルはリビジョンとしてアップロードされました。Catendaプロジェクト内のモデルにアクセスできない場合は、以下が表示されます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/06-project-list.png)

**IFCのアップロード**現在のArchicadプロジェクトからIFCをアップロード IFCのアップロードページは以下のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/07-project-list.png)

デフォルトでは、ファイル名はArchicadプロジェクトの名前になります。これはCatendaのリビジョン名になります。ファイルをアップロードするモデルを選択してください。「設定」をクリックしてArchicad IFCエクスポート ダイアログを開きます。ここではIFCをCatendaにエクスポートするために使用する設定を構成できます。準備ができたら、アップロードボタンをクリックしてモデルをアップロードしてください。

**座標**座標オプションにマウスを合わせて座標メニューを展開します。座標メニューは以下のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/08-project-list.png)

座標メニューでは、座標を以下に相対的に選択できます: サーベイポイント - デフォルトプロジェクト原点

**バージョン**プラグインのバージョン番号。

**ログアウト** Catendaアカウントからログアウト

## 5. **トピックリスト**

プロジェクトをクリックして開くと、プロジェクト内の最初のトピックボードが開きます。トピックボードは以下のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/09-topic-board.png)

### 5.1 **検索**

検索バーをクリックしてハイライトします。ハイライトされた検索バーは以下のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/10-search.png)

検索バーをクリックすると、提案されるフィルターのドロップダウンが開きます。いずれかのフィルターを選択して適用します。フィルターの横の「X」をクリックすると、再度削除できます。入力を開始して提案されるフィルターを絞り込むか、テキスト検索を実行してください。

### 5.2 **フィルターを表示**

「フィルターを表示」ボタンをクリックしてフィルターメニューを開きます。フィルターメニューは以下のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/11-show-filter.png)

トピックボードで構成された設定とトピックの送信に応じて、利用可能なさまざまなフィルターを指定できます：

**自分のトピック**私に割り当てられたリクエスト元 作成者

**ステータス**トピックリストに含まれる異なるステータスが一覧表示されます

**タイプ**トピックリストに含まれる異なるタイプが一覧表示されます

**期日**期限切れ 1日未満 1週間未満 2週間未満 1か月未満 期日を設定したすべての項目

**担当者** `@`で始まるエントリは、最初にリストされた割り当てられたチームです。その後、割り当てられたプロジェクトメンバーが一覧表示されます。

**依頼者** `@`で始まるエントリは、トピックを依頼するチームの最初に一覧表示されます。その後、トピックを依頼するプロジェクトメンバーが一覧表示されます。

**マイルストーン**トピックに適用されたマイルストーンが一覧表示されます。

**ラベル**トピックに適用されたラベルが一覧表示されます。

**フィルターメニューに記載されていないフィルター**テキスト検索 検索バーで入力してテキストを検索できます。

検索可能なコンテンツ トピックのタイトル トピックの説明 トピックのコメント

大文字小文字の区別 テキスト検索は大文字と小文字を区別しません。

文字数 1文字 - 結果なし。テキスト検索には2文字以上が必要です。2文字 - 検索フレーズと一致する、スペースで区切られた完全な単語が結果に含まれます。

### 5.3 **並べ替え**

「並べ替え」をクリックして並べ替えメニューを開きます。並べ替えメニューは以下のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/12-sort.png)

オプションをクリックしてトピックリストを以下でソートします: _最新_ - デフォルト 最新の作成日を持つトピック

**最も古い**最も古い作成日を持つトピック

**最近更新**最近更新されたトピック

**最近更新されていない**最近更新されていないトピック

## 6. **トピック**

トピックボード内のトピックをクリックして開きます。トピックは以下のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/13-topic.png)
