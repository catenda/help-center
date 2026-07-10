# Catenda Archicadプラグイン

> テスト

> \*\*注:\*\*プラグインのインストールファイルは[この記事](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations)にあります。

Catenda Archicadプラグインは、Nemetchek Archicadにインストールできるプラグインです。このプラグインを使用すると、3Dビューポイント、トピック、ドキュメントについて、建設プロジェクトの他のメンバーと協力することができます。

## 1. **インストール**

Catenda ArchicadプラグインがWindowsにインストールされると、インストールファイルは次のフォルダに表示されます。

`C:\Program Files\Catenda\Catenda Archicad Connection\<Archicad Version>\Add-On`

プラグインは、次にArchicadを開いたときに、アドオンマネージャーで有効として表示されます。これはデフォルトのアドオンフォルダとは異なることに注意してください。デフォルトのアドオンフォルダは次の場所にあります。

`C:\Program Files\Graphisoft\<Archicad Version>\Add-Ons`

### 1.1 **アンインストール**

プラグインをアンインストールするには、次のWindowsメニューに移動します:

`Windows設定 -> アプリ -> インストール済みアプリ`

リストからCatenda Archicad Connection \<version>を見つけ、右側のアクションメニューをクリックしてアンインストールします。

## 2. **Catendaパレット**

プラグインをインストールすると、トップバーにCatendaメニュータブが表示されます。このメニューでは、"Catenda Hub Issue Manager"ウィンドウが表示され、"Catenda Hub Issue Manager パレット"が含まれます。このパレットを使用するには、フロアプランまたは3Dビューを開く必要があります。このパレットでは、以下の操作が可能です:

- Catenda Hubプロジェクトに移動
- 問題の確認と作成
- モデルとrevisionのダウンロードとアップロード

## 3. **サインイン**

Catendaパレットを開くと、最初に表示されるのはサインインページです。サインインページは以下のようになります:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/01-sign-in.png)

Catendaアカウントをお持ちでない場合は、右上の「無料でサインアップ」をクリックできます。すでにCatendaアカウントをお持ちの場合は、メールアドレスとパスワードを入力してサインインをクリックします。サインイン後、Catendaアカウントへのアクセスを許可するよう求められます。このアクセスを許可すると、Archicadプラグインはあなたのcatendaアカウントの[アプリケーションページ](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a)にアプリケーションとして表示されます。必要に応じて、いつでもここからアクセスを取り消すことができます。

### 3.1 **パスワードリセット**

パスワードを忘れた場合は、「パスワードを忘れた」をクリックしてリセットできます。パスワードリセットページは以下のようになります:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/02-password-reset.png)

メールアドレスを入力して「認証メールを送信」をクリックすると、パスワードリセットのガイダンスを含むメールが送信されます。このメールが5分以内に届いていることを確認してください。受信トレイに表示されない場合は、スパムまたは迷惑メールフォルダをご確認ください。5分以上かかった場合は、[support@catenda.com](mailto:support@catenda.com)のサポートにお問い合わせください。

サインインに戻るには、右上の「サインイン」をクリックします。

## 4. **プロジェクトリスト**

Archicadプラグインを開くと、プロジェクトのリストが表示されます:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/03-project-list.png)

プロジェクトへの招待を受け入れると、そのプロジェクトがプラグインのプロジェクトリストと[プロジェクトページ](https://support.catenda.com/en/articles/8400797-projects-page)に表示されます。

**アクションメニュー**プロフィール画像の横にある3つのドットをクリックしてアクションメニュードロップダウンを開きます:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/04-project-list.png)

**モデル&revision**これはモデル&revisionページのような見た目です。ここでは、Catendaプロジェクトでアクセス権のあるすべてのモデルを確認できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/05-project-list.png)

このページでは、CatendaプロジェクトからifcファイルをダウンロードしてArchicadモデルにインポートできます。モデルのタイムスタンプは相対的です。タイムスタンプの上にカーソルを置くと、revisionが公開された正確な時刻を確認できます。モデルrevisionの横の矢印ボタンをクリックして、revisionとしてアップロードされたIFCファイルをインポートします。Catendaプロジェクトのモデルにアクセス権がない場合は、以下のように表示されます:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/06-project-list.png)

**IFCのアップロード**現在のArchicadプロジェクトからIFCをアップロードします。これはIFCアップロードページのような見た目です:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/07-project-list.png)

デフォルトでは、ファイル名はArchicadプロジェクトの名前になります。これはCatendaのrevisionの名前になります。ファイルをアップロードするモデルを選択します。「設定」をクリックしてArchicad IFCエクスポートダイアログを開きます。ここで、IFCをCatendaにエクスポートするために使用する設定を構成できます。準備ができたら、アップロードボタンをクリックしてモデルをアップロードします。

**座標**座標オプションの上にカーソルを置いて座標メニューを展開します。座標メニューは以下のようになります:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/08-project-list.png)

座標メニューでは、座標を以下に相対的に選択できます: 測量ポイント - デフォルトプロジェクト原点

**バージョン**プラグインのバージョン番号。

**ログアウト** Catendaアカウントからログアウト

## 5. **トピックボード**

プロジェクトをクリックして開くと、プロジェクトの最初のトピックボードが開きます。トピックボードは以下のようになります:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/09-topic-board.png)

### 5.1 **検索**

検索バーをクリックしてハイライトします。ハイライトされた検索バーは以下のようなものになります:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/10-search.png)

検索バーをクリックすると、推奨フィルター付きのドロップダウンが開きます。フィルターのいずれかを選択して適用します。フィルターの横のxをクリックして削除します。入力を開始して推奨フィルターを絞り込むか、テキスト検索を実行します。

### 5.2 **フィルター表示**

「フィルター表示」ボタンをクリックしてフィルターメニューを開きます。フィルターメニューは以下のようなものになります:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/11-show-filter.png)

トピックボードとサブミットされたトピックの設定によっては、様々なフィルターが利用できます:

**マイトピック**自分に担当されている 自分がリクエストした 自分が作成した

**ステータス**トピックボードの異なるステータスがここにリストされています

**タイプ**トピックボードの異なるタイプがここにリストされています

**期日**期限切れ 1日未満 1週間未満 2週間未満 1ヶ月未満 期日のあるすべてのもの

**担当者** `@`で始まるエントリは、最初にリストされた担当チームです。その後、割り当てられたプロジェクトメンバーがリストされます。

**依頼者** `@`で始まるエントリは、最初にリストされたトピックをリクエストするチームです。その後、トピックをリクエストするプロジェクトメンバーがリストされます。

**マイルストーン**トピックに適用されたマイルストーンがリストされます。

**ラベル**トピックに適用されたラベルがここにリストされます。

**フィルターメニューに記載されていないフィルター**テキスト検索 テキスト検索バーに入力して検索できます。

検索できるコンテンツ トピックタイトル トピック説明 トピックコメント

大文字と小文字の区別 テキスト検索は大文字と小文字の区別に敏感ではありません。

文字数 1文字 - 結果なし。テキスト検索には少なくとも2文字が必要です。2文字 - スペースで区切られた検索フレーズに一致する完全な単語が結果に含まれます。

### 5.3 **並べ替え**

「並べ替え」をクリックしてソートメニューを開きます。ソートメニューは以下のようなものになります:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/12-sort.png)

オプションのいずれかをクリックしてトピックリストを以下の順に並べ替えます: _最新_ - デフォルト 最新の作成日のトピック

**最古**最古の作成日のトピック

**最近更新**最近更新されたトピック

**最も更新が古い**最も更新が古いトピック

## 6. **トピック**

トピックボードのトピックをクリックして開きます。トピックは以下のようなものになります:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/13-topic.png)
