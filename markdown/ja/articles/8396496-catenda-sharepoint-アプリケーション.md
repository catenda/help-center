# Catenda SharePoint アプリケーション

> **注:** プラグインのインストール ファイルは[この記事](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations)にあります。

Catenda SharePoint アプリケーションが SharePoint サイトに追加されると、SharePoint から Catenda にファイルを公開でき、Catenda ドキュメント構造を SharePoint で表示できます。設定すると、アプリケーションは次のようになります: <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/inline-628ad1424b68.png" width="300"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/inline-910393724d2c.png" width="300"/>この記事には、このアプリケーションがどのように機能するかについての情報が含まれていますこのアプリケーションが有用な方法の詳細については、[こちら](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq)を参照してください。SharePoint アプリケーションをサイトに追加する方法については、[こちら](https://support.catenda.com/en/articles/9453368-adding-and-removing-the-catendasp-app)を参照してください。

## 1. **リストコマンドを使用したCatendaへの公開**

リストコマンドを使用すると、1つ以上のファイルをCatendaに公開できます。

> **注:** ファイルのみ公開可能です。フォルダ構造はSharePointからダウンロードして、[zip アップロード](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure)または[Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector)経由でCatendaにアップロードできます。

### 1.1 **リストコマンドの検索**

**1つのファイル**単一のファイルをCatendaに公開したい場合、最も簡単な方法は、ファイルのハンバーガー メニューで「Catendaに公開」をクリックすることです。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/01-finding-the-list-command.png)

**複数のファイル**複数のファイルをCatendaに公開したい場合は、公開したいファイルを選択する必要があります。SharePointでファイルを選択すると、ユーザーは「Catendaに公開」リストコマンドを表示できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/02-finding-the-list-command.png)

コマンド バーにスペースが足りない場合は、ハンバーガー メニューにコマンドが表示される可能性があります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/03-finding-the-list-command.png)

> **注:** ファイルはリスト ビューからのみ公開でき、リストコマンドはグリッド ビューでは使用できません。

### 1.2 **ファイルの公開**

「Catendaに公開」をクリックすると、以下のようなメニューが開きます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/04-publishing-the-file.png)

SharePointにCatendaアカウントへのアクセスを許可していない場合、認可するよう求められます。アカウントの認可方法については、[以下](#h_788fe15988)を参照してください。

**フォルダの選択** Catendaアカウントへのアクセスを許可している場合は、Catendaでプロジェクト、ライブラリ、および宛先フォルダを選択して、公開できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/05-publishing-the-file.png)

SharePointのフォルダ構造のビューはCatendaのビューと一致しています。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/06-publishing-the-file.png)

公開するフォルダに同じ名前のドキュメントがまだ存在しない場合、Catendaに新しいドキュメントとして表示されます。公開するファイルが公開先のフォルダ内のドキュメントと同じ名前を持つ場合、ファイルはそのドキュメントの新しいrevisionになります。

> **注:** ドキュメントの公開のみが可能であり、ドラフトのアップロードはできません

ファイルが公開された後、ユーザーはファイルを移動、名前変更、削除できるようになります。_Catendaアクセス必須:_ フルアクセス（通常、公開者または管理者などのユーザーに与えられます）。Catendaでファイルを変更してもSharePointには何も変わりません。同様に、SharePointでファイルが変更されても、Catendaには何も変わりません。

## 2. **Catenda Webpart**

このアプリケーションでは、[Catenda webpart](https://support.catenda.com/en/articles/10538168-catenda-sharepoint-application-webpart)をサイトのページに追加します。ユーザーが読み取りアクセス権を持つ領域をCatendaプロジェクトのドキュメント セクションで閲覧できるようにすることができます。ドキュメント構造の任意の部分に対して書き込みアクセス権を持つ場合、ユーザーはそこにファイルをアップロードできます。

構成されたWebpartの例を次に示します：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/07-catenda-webpart.png)

## 3. **Catendaアカウントの認可**

Catenda Webpartが有効になっているSharePointページに移動するか、公開アクションを使用しようとして、アカウントをまだ検証していない場合、以下のようなポップアップが表示されます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/08-authorizing-your-catenda-account.png)

_アクセス必須:_ アプリケーションをインストールするときのAPIアクセス 新しいブラウザ タブが自動的に開かない場合は、開いているアカウント検証タブからリンクをコピーして、そこに移動してください。まだログインしていない場合は、このウィンドウでCatendaにログインするよう求められます。まだ持っていない場合は、[ここ](https://hub.catenda.com/signup)でCatendaアカウントを作成できます。

> **注:** サインインするCatendaアカウントに接続されているメール アドレスは、サインインするSharePointアカウントに接続されているアドレスと同じである必要があります。

認証ウィンドウは以下のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/09-authorizing-your-catenda-account.png)

アプリケーションにアカウントへのアクセスを許可することで、[ドキュメント セクション](https://support.catenda.com/en/articles/8204673-documents-page)で書き込みアクセス権を持つCatendaプロジェクト（複数の場合もあります）の任意の部分にSharePointからドキュメントを公開できるようになります。Webpartがサイトのページに追加されている場合は、Webpartを追加した人によって構成されたCatendaプロジェクトで読み取りアクセス権を持つすべてのドキュメントを表示できます。Webpartを使用すると、[ドキュメント セクション](https://support.catenda.com/en/articles/8204673-documents-page)で書き込みアクセス権を持つ構成されたCatendaプロジェクトの任意の部分にシステムからドキュメントを公開できます。

> **注:** CatendaはSharePointドキュメントにアクセスできません。ドキュメントをCatendaに公開する場合、Catendaはそれを一方通行のトランザクションで受け取ります。

アプリケーションにCatendaアカウントへのアクセスを許可したくない場合は、Catendaアカウントの[アプリケーション ページ](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a)でいつでもアクセスを取り消すことができます。
