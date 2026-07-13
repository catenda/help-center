# Catenda Revitプラグイン

> **注:** プラグインのインストールファイルは[この記事](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations)にあります。

Catenda Revitプラグインは、Autodesk Revitにインストール可能なプラグインです。このプラグインにより、3Dビューポイント、トピック、ドキュメントについて、建設プロジェクトの他のメンバーと協力することができます。

この記事では、以下のトピックについて説明します。

## 1. **インストール**

Catenda RevitプラグインがWindowsにインストールされると、インストールファイルは次のフォルダに表示されます。

`C:\ProgramData\Autodesk\ApplicationPlugins\CatendaHub.bundle`

### 1.1 **アンインストール**

プラグインをアンインストールするには、以下のWindowsメニューに移動してください。

`Windows設定 -> アプリ -> インストール済みアプリ`

リストから「Catenda for Autodesk® Revit®」を見つけ、右側のアクションメニューをクリックしてアンインストールします。

## 2. **プラグインウィンドウを開く**

インストール後、Catendaパネルはアドインリボンに表示されます。リボン設定によって、Catendaパネルは以下のようになります。

**フルリボン - デフォルト**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/01-opening-the-plugin-window.png)

**パネルボタン**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/02-opening-the-plugin-window.png)

**パネルタイトル**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/03-opening-the-plugin-window.png)

**タブに最小化**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/04-opening-the-plugin-window.png)

### 2.1 **トピック**

「トピック」をクリックすると、Catendaプラグインウィンドウがトピックページで開きます。ユーザーがサインインしていない場合は、代わりにサインインページが表示されます。

### 2.2 **IFCをアップロード**

「IFCをアップロード」をクリックすると、Catendaプラグインウィンドウが「IFCアップロード」ページで開きます。ユーザーがサインインしていない場合は、代わりにサインインページが表示されます。

### 2.3 **Catenda**

「Catenda」をクリックすると、デフォルトのシステムブラウザで[https://hub.catenda.com/](https://hub.catenda.com/)にリダイレクトされます。

## 3. **サインイン**

これは、プラグインウィンドウを右側にドックしたときの見た目です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/05-signing-in.png)

Catendaのメールアドレスとパスワードでログインします。

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-703202eeb52b.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3e163e70c122.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3b6b4eaa010e.png" width="180"/>

アカウントでMFAを有効にしている場合は、MFAコードを入力するように求められます。サインインページの詳細については、[ここ](https://support.catenda.com/en/articles/7891486-sign-in-page)をクリックしてください。

「アクセスを許可」をクリックして、Bimsync Arena用Revitプラグインに、あなたのCatenda Hubアカウントへのアクセスを許可します。

### 3.1 **アクセスを取り消す**

Catenda Hubアカウントへのアクセスは、Catenda Hubの[アプリケーションページ](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a)にアクセスして、「Bimsync Arena用Revitプラグイン」の近くにある「アクセスを取り消す」をクリックすることで、いつでも取り消すことができます。

## 4. **トピックリスト**

サインイン後、Catenda Hubプラグインのメインビューが開きます。このページには、Catenda Hubプロジェクト、トピックボード、トピックを移動するためのメインメニューが表示されます。

### 4.1 **インターフェース**

![Header.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/06-interface.png)

1. Catenda Hubプロジェクトを選択します。
2. このプロジェクト内のトピックボードを選択します。
3. 現在選択されているトピックボードで新しいトピックを作成します。
4. 現在表示されているトピックを並び替えます。
5. Catenda Hubアドインメニューを開きます。
6. 表示されているトピックを検索およびフィルタリングします。
7. トピックボード内で現在フィルタリングされているトピックのリスト。

### 4.2 **プロジェクトおよびトピックボード選択**

Catenda Hubプロジェクトを選択すると、このプロジェクト内のトピックボードのリストが表示され、1つを選択して対応するトピックを表示できます。また、Catenda HubプロジェクトとトピックボードをあなたのRevitモデルに保存し、次にこのモデルを開くときに自動的に開きます。

![ProjectInfo.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/07-project-and-topic-board-selection.png)

### 4.3 **アクション**

プラグインのアクションは右上に表示されます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/08-actions.png)

Catenda Revitプラグイン内のさまざまなアクションについて詳しく読むには、[ここ](https://support.catenda.com/en/articles/13168755-actions-in-the-catenda-revit-plugin)をクリックしてください。

### 4.4 **トピック選択**

トピックリストには、トピックに関するすべての主要な情報が表示されます。

![IssueInformation.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/09-topic-selection.png)

1. トピックのタイトル
2. そのステータス（オープン、クローズ、…）、そのタイプ（情報、エラー、…） およびそのラベル
3. トピックを依頼したメンバー
4. トピックが割り当てられているメンバー
5. トピックの期日
6. トピックが最後に更新された時刻。 日付の上にマウスカーソルを置いて、更新の完全な日時を表示できます。
7. トピック内のコメント数
8. トピック内の最初のコメントの画像
9. Catenda Hubトピック番号

任意のトピックをクリックして、[トピック詳細ページ](#topic-details)に移動できます。

### 4.5 **トピックの並び替え**

表示されているトピックを並び替えて、最も関連性の高いものを最初に表示できます。

![sort.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/10-sort-topics.png)

1. 最近作成されたトピックを最初に表示します。
2. 最も古いトピックを最初に表示します。
3. 最近更新されたトピックを最初に表示します。 トピックの更新には、タイトルやコメントなどのプロパティの変更が含まれます。
4. 最も最近に更新されていないトピックを最初に表示します。
5. 最も最近の期日を最初に表示します。
6. 最も古い期日を最初に表示します。

### 4.6 **トピックのフィルタリング**

フィルターバーを使用して、任意のタイプのフィルターを組み合わせて、最も関連性の高いトピックのみを表示できます。

現在のフィルターは、フィルターバーに小さなチップとして表示されます。ここでは、「オープン」ステータスのトピックのみが表示されます。フィルターバーをクリックして、すべての使用可能なフィルターを表示します（1）。

![AvailableFilters.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/11-filter-topics.png)

左側（2）はフィルターの名前で、すべてのフィルターは右側（3）に表示されるタイプに属します。

使用可能なフィルタータイプは以下を含みます。

- 依頼者：特定のユーザーが依頼したすべてのトピックを取得します。
- 担当者：特定のユーザーに割り当てられたすべてのトピックを取得します。
- 期日：期限切れのトピック、または1か月以内、2週間、1週間、または1日以内の期日を持つトピックをすべて取得します。
- ステータス：特定のステータス（オープン、クローズ、…）のすべてのトピックを取得します。
- タイプ：特定のタイプ（エラー、警告、情報、…）のすべてのトピックを取得します。
- ラベル：特定のラベルを持つすべてのトピックを取得します。
- マイトピック：自分に割り当てられたまたは依頼したすべてのトピックを取得します。

フィルターバーにテキストを入力して、これらのフィルターを検索できます（1）。これを使用して、トピックのタイトルまたは説明内の特定のテキストを検索するテキストフィルターを作成することもできます（2）。

![TextFilter.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/12-filter-topics.png)

## 5. **トピック詳細**

このビューでは、特定のトピックをレビューおよび編集できます。

### 5.1 **インターフェース**

![IssueDetailView.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/13-interface.png)

1. [トピックリスト](#topic-list)に戻ります。
2. このトピックのコンテンツを更新します。
3. トピック間をナビゲートします。
4. トピックステータスを設定します（オープン、クローズ、…）。
5. トピックタイプを設定します（エラー、警告、情報、…）。
6. トピックの期日を設定します。
7. トピックに割り当てられたメンバーを設定します。 トピックを個々のユーザーまたはチームに割り当てることができます。
8. このトピックを依頼したメンバーを設定します。 個々のユーザーまたはチームを設定できます。
9. トピックラベルを編集します。
10. トピック内のコメントのリスト。

### 5.2 **トピックプロパティ**

トピックのプロパティを編集できます：ステータス、タイプ、担当者、依頼者、期日、ラベル。すべてのメニューに、利用可能なプロパティのリストが表示されます。ただし、プラグインで直接新しいステータス、タイプ、またはラベルを作成することはできません。Catenda Hubのウェブインターフェースを使用する必要があります。

タイトルをクリックして編集できます。

![editTitle.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/14-topic-properties.gif)

ペンアイコンをクリックして、説明を編集できます。

![editDescription.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/15-topic-properties.gif)

ラベルバーにテキストを入力して、フィルターのリストをフィルターダウンすることもできます。

![editLabels.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/16-topic-properties.gif)

### 5.3 **コメント**

すべてのコメントはトピックの下に表示されます。コメントには、テキスト、画像、Revitの現在のビューからのスナップショット、またはビューポイントが含まれる可能性があります。

![CommentDetail.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/17-comments.png)

1. コメントの作成者
2. コメントが作成された時刻。 日付の上にマウスカーソルを置いて、更新の完全な日時を表示できます。
3. [ズームボタン](#zoom)（下のセクションを参照）
4. コメントに関連付けられた画像
5. コメントのテキスト

### 5.4 **ズーム**

コメントに含まれるビューポイントがある場合は、このビューポイントにズームできます。ズームインすると、同じビューポイントにフォーカスしたRevitモデルに新しい3Dビューが作成されます。

![zoom.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/18-zoom.gif)

ビューポイントが関連性を持つためには、コメントが作成されたのと同じモデルを開いておく必要があります。プラグインは、モデルをIFCにエクスポートするときに共有座標が使用されたと想定しています。

ビューポイントが透視図から作成されている場合、新しい3Dビューの投影モードは「透視」に設定されます。それ以外の場合、投影モードは「平行投影」になります。

アドインは、1つの透視図ビューと1つの平行投影ビューのみを作成します。それらを作成した後、ズーム機能を使用するたびにそれらを再利用します。設定メニューでそれを変更できます。設定メニューを使用して、これらのビューの名前を変更することもできます。

### 5.5 **関連要素**

トピックに関連要素が含まれている場合、ビューポイントにズームするとアドインはRevitでそれらを選択します。

![relatedElements.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/19-related-elements.gif)

この機能を使用するには、Revitモデルを「エクスポート後のエレメント パラメータに IFC GUID を保存」でIFCにエクスポートする必要があります。これにより、すべてのオブジェクトに IFCGuid パラメータが追加され、プラグインが関連要素を選択できるようになります。

### 5.6 **コメント追加**

テキストボックスにテキストを入力して「送信」をクリックすることで、トピックにコメントを追加できます。

「プラス」ボタンをクリックして、コンピューターから画像を追加することもできます。プレビュー画像をクリックして、この画像に注釈を付けることができます。

![createComment.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/20-add-comment.gif)

### 5.7 **3Dスナップショット追加**

現在のRevitビューをビューポイント、およびコメントに添付されたスナップショットとして追加することもできます。任意の画像と同様に、プレビュー画像をクリックしてスナップショットに注釈を付けることができます。

IFCGUID パラメータが存在する場合、Revit で選択されたエレメント はトピックに関連要素として追加されます。
