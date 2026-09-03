# Catenda SharePoint アプリを有効にする

> **注:** プラグインのインストール ファイルは[このアーティクル](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations)で見つけることができます。

Catenda SharePoint アプリケーションは、システム管理者が SharePoint 環境に対して有効にすることができ、その後、サイト所有者がサイトに追加できます。このアプリを使用すると、SharePoint ユーザーは建設プロジェクトの他のメンバーと一緒に、Catenda 内のドキュメントを表示、管理、および共同作業することができます。

アプリをお使いの環境に対して有効にするには、ここでエントリを検索できます：[Microsoft AppSource](https://appsource.microsoft.com/en-us/marketplace/apps?search=Catenda&page=1)の外観は以下のようなものです：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/01-intro.png)

「今すぐ取得」をクリックすると、既にログインしていない場合はSharePointアカウントにログインするよう求められます。その後、SharePointストアエントリにリダイレクトされます。SharePointストアは、SharePointの右上のプロフィールをクリックして、「アプリを追加」をクリックすることでも見つけることができます

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/02-intro.png)

SharePointストアでは、CatendaSharePointアプリケーションを検索することもできます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/03-intro.png)

**https://\<Tenant>.sharepoint.com/sites/appcatalog/\_layouts/15/appStore.aspx/sharePointStore?entry=ClassicAppCatalog&sorting=7&search=catenda**

SharePointストアエントリの外観は以下のようなものです：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/04-intro.png)

**https://\<Tenant>.sharepoint.com/\_layouts/15/appStore.aspx/appDetail/WA200005981**

このアーティクルで説明されているトピックは次のとおりです：

## 1. **通常の SharePoint ユーザー**

通常のSharePointユーザーは、「アプリにサイトを追加」ボタンをクリックして、CatendaSharePointアプリを有効にするようリクエストできます。SharePointストアの「マイリクエスト」ページで、リクエストが承認されたかどうかを確認できます。管理者の場合は、アプリカタログからリクエストを承認できます

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/05-regular-sharepoint-users.png)

**https://\<Tenant>.sharepoint.com/sites/appcatalog/SitePages/Home.aspx**

## 2. **SharePoint 管理者**

SharePoint 環境の管理者として、「アプリにサイトを追加」をクリックしてアプリを有効にできます。ここでは、データ アクセスを確認するよう求められます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/06-sharepoint-administrators.png)

### 2.1 **データ アクセスを確認**

有効にしようとしているアプリは、そのアプリを使用する人のIDを使用することでデータにアクセスできます。開発者またはパブリッシャーを信頼する場合にのみ、このアプリを有効にしてください。このアプリは、ユーザーがファイルを公開することを選択したときに、ユーザーのどのファイルを公開するかを知るためにこの権限が必要です。エンドポイント：[https://sharepoint.plugins.catenda.com/1.0.0.0/](https://sharepoint.plugins.catenda.com/1.0.0.0/)

### 2.2 **API アクセス**

API アクセスが以前有効にされていない場合は、アプリケーションが機能するために有効にする必要があります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/07-api-access.png)

API アクセスを承認するには、管理センターの API アクセス ページに移動します https://\<Tenant>.sharepoint.com/\_layouts/15/online/AdminHome.aspx#/webApiPermissionManagement

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/08-api-access.png)

API アクセスが必要です。これにより、SharePoint 管理者は Catenda アカウントに接続してドキュメントの公開を有効にする必要があります。ユーザーが Catenda に何かを公開しようとするときは、Catenda アカウントでログインするよう求められます。これは、各ユーザーが Catenda で異なる権限を持つ可能性があるためです。

API アクセスがない場合、Catenda SharePoint アプリケーションを有効にすることができます。その後、リスト アクションと Web パーツの両方は表示されますが、Catenda アカウントに接続しないとデータを交換できないため、使用できません。_必要なアクセス:_ Microsoft 365 の Global Administrator ロールまたは Application Administrator ロール。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/09-api-access.png)

**アクセスを承認**保留中のリクエストのリストから Catenda を選択し、上部の承認をクリックします。Catenda アプリケーションが機能するには、次の権限が必要です: アクセス

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/10-api-access.png)

**アクセスを削除** API アクセス ページで Catenda を選択し、上部の削除をクリックします。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/11-api-access.png)

次のメニューで、「削除」をクリックします

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/12-api-access.png)

Catenda アプリケーションが有効になっている可能性がありますが、このアクセスが削除されると、ユーザーは Catenda に接続できなくなります。

## 3. **アプリの可用性**

### 3.1 **このアプリのみを有効にする**

このオプションは、SharePoint 環境に対してアプリを有効にし、環境内のサイト所有者がお使いのアプリから「マイ アプリ」ページにアプリを追加できるようにします。アプリをサイトに追加するまで、アプリは何も実行しません。このオプションは優れていますが、ユーザーが Catenda にドキュメントを公開できるサイトをより細かく制御したい場合は、一部のサイトに公開オプションがあり、他のサイトにはない場合、ユーザーが混乱する可能性があります。さらに細かく制御するために、[サイト コレクション アプリ カタログ](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/site-collection-app-catalog)を有効にすることができます。これにより、サイト所有者がインストールできるアプリを選択できます。このオプションでは、新しいサイトではデフォルトではアプリもオンになりません。つまり、新しいサイトを作成する場合、構成により多くの作業が必要になります。

### 3.2 **このアプリを有効にしてすべてのサイトに追加**

このオプションでは、アプリがすべてのサイトに自動的に追加されます。ユーザーがアプリがサイトに追加されたときに見る唯一の視覚的な違いは、リストのリスト コマンドと、ドキュメントを選択するときのハンバーガー メニューが表示されることです。Web パーツとフル ページは後で追加する必要があります。これは後でアプリ管理ページから行うこともできます。

### 3.3 **チームに追加**

このオプションでは、アプリも Teams に追加されます。これにより、ユーザーは Teams タブを表示できます。これは後でアプリ管理ページから行うこともできます。

## 4. **アプリを管理**

アプリを有効にすると、SharePoint 管理者は、アプリ管理エリアでアプリを確認できます。https://\<Tenant>.sharepoint.com/sites/appcatalog/AppCatalog/Forms/AllItems.aspx

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/13-manage-apps.png)

アプリを選択すると、SharePoint のさまざまな部分に追加できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/14-manage-apps.png)

### 4.1 **すべてのサイトに追加:**

これにより、アプリがすべてのサイトと作成されたすべての新しいサイトに追加されます。アプリが有効になっている場合、サイト所有者も個別にアプリをサイトに追加できます。新しいサイトへのアプリの追加を続けたくない場合は、「新しいサイトへの追加を停止」をクリックして停止できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/15-add-to-all-sites.png)

アプリによって提供される機能は、アプリが追加されたすべてのサイトで利用可能なままであり、サイト所有者は引き続きこのアプリをサイトに追加できます。

### 4.2 **チームに追加:**

これにより、アプリの Teams タブが有効になります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/16-add-to-teams.png)

アプリをチームに追加するには、最初にすべてのサイトに追加する必要があります。

## 5. **参考資料**

インストール後のこのアプリケーションの動作方法については、[こちら](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application)を参照してください。このアプリケーションがどのように役立つかについての詳細情報は、[こちら](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq)を参照してください。
