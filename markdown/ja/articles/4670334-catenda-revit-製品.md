# Catenda Revitプラグイン

> **注:** プラグインのインストールファイルは[このページ](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations)にあります。

Catenda Revitプラグインは、Autodesk Revitにインストールできるプラグインです。このプラグインを使用することで、建設プロジェクトの他のメンバーと3Dビューポイント、トピック、ドキュメントについて協力することができます

## 1. **インストール**

Catenda RevitプラグインがWindowsにインストールされると、そのインストールファイルは次のフォルダに表示されます。

`C:\ProgramData\Autodesk\ApplicationPlugins\CatendaHub.bundle`

### 1.1 **アンインストール**

プラグインをアンインストールするには、次のWindowsメニューに移動してください：

`Windowsの設定 -> アプリ -> インストール済みアプリ`

リスト内でAutodesk® Revit®用Catendaを探し、右側のアクション メニューをクリックしてアンインストールします。

## 2. **プラグインウィンドウを開く**

インストール後、CatendaパネルはAdd-insリボンにあります。リボン設定によっては、Catendaパネルは以下のように表示されます：

**フルリボン - デフォルト**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/01-opening-the-plugin-window.png)

**パネルボタン**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/02-opening-the-plugin-window.png)

**パネルタイトル**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/03-opening-the-plugin-window.png)

**タブに最小化**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/04-opening-the-plugin-window.png)

### 2.1 **トピック**

トピックをクリックして、Catendaプラグインウィンドウをトピックページで開きます。ユーザーがサインインしていない場合は、代わりにサインインページが表示されます。

### 2.2 **IFCをアップロード**

IFCをアップロードをクリックして、Catendaプラグインウィンドウをいったんアップロードページに開きます。ユーザーがサインインしていない場合は、代わりにサインインページが表示されます。

### 2.3 **Catenda**

Catendaをクリックして、デフォルトシステムブラウザで[https://hub.catenda.com/](https://hub.catenda.com/)にリダイレクトされます。

## 3. **サインイン**

プラグインウィンドウを右にドッキングした場合は、このように表示される可能性があります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/05-signing-in.png)

Catendaのメールアドレスとパスワードでログインしてください。

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-703202eeb52b.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3e163e70c122.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3b6b4eaa010e.png" width="180"/>

アカウントのMFAが有効な場合は、MFAコードを入力するよう求められます。[ここ](https://support.catenda.com/en/articles/7891486-sign-in-page)をクリックして、サインインページの詳細をご覧ください。

「アクセスを許可」をクリックして、Bimsync Arena用Revitプラグインに対してCatenda Hubアカウントへのアクセスを許可します。

### 3.1 **アクセスを取り消す**

Catenda Hubアカウントへのアクセスは、Catenda Hub[アプリケーションページ](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a)に移動して、「Bimsync Arena用Revitプラグイン」の近くにある「アクセスを取り消す」をクリックすることで、いつでも取り消すことができます。

## 4. **トピックリスト**

サインイン後、Catenda Hubプラグインのメインビューが開きます。このページでは、Catenda Hubプロジェクト、トピックボード、トピックをナビゲートするためのメインメニューを見つけることができます。

### 4.1 **インターフェース**

![Header.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/06-interface.png)

1. Catenda Hubプロジェクトを選択します
1. このプロジェクト内のトピックボードを選択します
1. 現在選択されているトピックボードに新しいトピックを作成します
1. 現在表示されているトピックを並び替えます
1. Catenda Hubアドイン メニューを開きます
1. 表示されているトピックを検索およびフィルターします
1. トピックボード内の現在フィルタリングされたトピックのリスト

### 4.2 **プロジェクトおよびトピックボード選択**

Catenda Hubプロジェクトを選択すると、このプロジェクト内のトピックボードのリストが表示され、1つを選択して対応するトピックを表示できます。また、Catenda HubプロジェクトとトピックボードをRevitモデルに保存し、次回このモデルを開く際に自動的に開きます。

![ProjectInfo.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/07-project-and-topic-board-selection.png)

### 4.3 **アクション**

プラグインアクションは右上の方に表示されます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/08-actions.png)

[ここ](https://support.catenda.com/en/articles/13168755-actions-in-the-catenda-revit-plugin)をクリックして、Catenda Revitプラグインのさまざまなアクションについて詳しく読んでください。

### 4.4 **トピック選択**

トピックリスト内で、トピックに関するすべての主な情報が表示されます：

![IssueInformation.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/09-topic-selection.png)

1. トピックのタイトル
1. そのステータス(オープン、クローズ...)、そのタイプ(情報、エラー...)、そのラベル
1. トピックを要求したメンバー
1. トピックが割り当てられているメンバー
1. トピックの期日
1. トピックが最後に更新された時刻。日付にカーソルを合わせると、更新の完全な日時が表示されます。
1. トピック内のコメント数
1. トピック内の最初のコメントの画像
1. Catenda Hubトピック番号

任意のトピックをクリックして、[トピック詳細ページ](#h_445d3efa52)に移動できます。

### 4.5 **トピック並び替え**

表示されているトピックを並び替えて、最も関連性の高いものを最初に表示できます。

![sort.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/10-sort-topics.png)

1. 最も最近作成されたトピックを最初に表示します
1. 最も古いトピックを最初に表示します
1. 最も最近更新されたトピックを最初に表示します。トピックの更新には、タイトル、コメントなどのプロパティの変更が含まれる可能性があります…
1. 最近更新されていないトピックを最初に表示します
1. 最も最近の期日を最初に表示します
1. 最も古い期日を最初に表示します

### 4.6 **トピックをフィルター**

フィルターバーを使用して、任意のタイプのフィルターを組み合わせて、最も関連性の高いトピックのみを表示できます。

現在のフィルターはフィルターバーに小さなチップとして表示されます。ここでは、「オープン」ステータスのトピックのみが表示されます。フィルターバーをクリックして、利用可能なすべてのフィルターを表示します(1)。

![AvailableFilters.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/11-filter-topics.png)

左側(2)はフィルターの名前で、すべてのフィルターは右側(3)に表示されるタイプに属します。

利用可能なフィルタータイプには以下が含まれます：

- 要求者: 特定のユーザーによって要求されたすべてのトピックを取得します
- 割り当て先: 特定のユーザーに割り当てられたすべてのトピックを取得します
- 期日：1か月以内、2週間、1週間、または1日以内に期限が切れるトピック、または期限を超過したトピックをすべて取得します
- ステータス: 特定のステータス(オープン、クローズなど)のすべてのトピックを取得します
- タイプ: 特定のタイプ(エラー、警告、情報など)のすべてのトピックを取得します
- ラベル: 特定のラベルを持つすべてのトピックを取得します
- マイトピック: 自分に割り当てられたまたは自分が要求したすべてのトピックを取得します

フィルターバーにテキストを入力してこれらのフィルターを検索できます(1)。これを使用して、トピックのタイトルまたは説明で特定のテキストを検索するためのテキストフィルターを作成することもできます(2)。

![TextFilter.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/12-filter-topics.png)

## 5. **トピック詳細**

このビューでは、特定のトピックを確認および編集できます。

### 5.1 **インターフェース**

![IssueDetailView.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/13-interface.png)

1. [トピックリスト](#h_642fa61854)に戻る
1. このトピックのコンテンツを更新します
1. トピック間を移動します
1. トピックステータスを設定します(オープン、クローズなど)
1. トピックタイプを設定します(エラー、警告、情報など)
1. トピックの期日を設定します
1. トピックに割り当てられたメンバーを設定します。トピックを個別ユーザーまたはチームに割り当てることができます。
1. このトピックを要求したメンバーを設定します。個別ユーザーまたはチームを設定できます。
1. トピックラベルを編集します
1. トピック内のコメントのリスト

### 5.2 **トピックプロパティ**

トピックのプロパティ（ステータス、タイプ、割り当て先、要求者、期日、ラベル）を編集できます。すべてのメニューには利用可能なプロパティのリストが表示されます。ただし、プラグイン内で直接新しいステータス、タイプ、またはラベルを作成することはできません。Catenda Hubのウェブインターフェースを使用する必要があります。

タイトルをクリックして編集できます：

![editTitle.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/14-topic-properties.gif)

ペンアイコンをクリックして説明を編集できます：

![editDescription.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/15-topic-properties.gif)

ラベルバーにテキストを入力して、フィルターのリストをフィルターダウンすることもできます：

![editLabels.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/16-topic-properties.gif)

### 5.3 **コメント**

すべてのコメントはトピックの下に表示されます。コメントには、テキスト、画像、Revitの現在のビューのスナップショット、またはビューポイントが含まれる場合があります。

![CommentDetail.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/17-comments.png)

1. コメントの作成者
1. コメントが作成された時刻。日付にカーソルを合わせると、更新の完全な日時が表示されます。
1. [ズームボタン](#h_d873968c27)(下のセクションを参照)
1. コメントに関連付けられた画像
1. コメントのテキスト

### 5.4 **ズーム**

コメントがビューポイントを含む場合、このビューポイントにズームできます。ズームインすると、同じビューポイントに焦点を当てたRevitモデルに新しい3Dビューが作成されます。

![zoom.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/18-zoom.gif)

ビューポイントが関連性を持つようにするには、コメントが作成されたのと同じモデルが開かれていることを確認する必要があります。プラグインは、モデルをIFCにエクスポートする際に共有座標が使用されたと想定しています。

ビューポイントが透視図ビューから作成された場合、新しい3Dビューは投影モードが「透視図」に設定されます。それ以外の場合は、投影モードが「正投影」に設定されます。

アドインは、1つの透視図ビューと1つの正投影ビューのみを作成します。作成後、ズーム機能の後続の使用のために再利用します。[設定メニュー](#h_b02502c589)でこれを変更できます。設定メニューを使用して、これらのビューの名前を変更することもできます。

### 5.5 **関連要素**

トピックが関連要素を含む場合、ビューポイントにズームするとアドインはRevitでそれらを選択します。

![relatedElements.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/19-related-elements.gif)

この機能を機能させるには、Revitモデルを「エクスポート後にIFC GUIDを要素パラメータに保存」してIFCにエクスポートしておく必要があります。これにより、すべてのオブジェクトにIFCGuidパラメータが追加され、プラグインが関連要素を選択できます。

### 5.6 **コメント追加**

テキストボックスに入力して「送信」をクリックすることで、トピックにコメントを追加できます。

また、「プラス」ボタンをクリックしてコンピューターから画像を追加することもできます。選択後、プレビュー画像をクリックして、この画像に注釈を付けることができます。

![createComment.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/20-add-comment.gif)

### 5.7 **3Dスナップショット追加**

また、現在のRevitビューをビューポイントとスナップショットとしてコメントに追加することもできます。任意の画像と同様に、プレビュー画像をクリックしてスナップショットに注釈を付けることができます。

IFCGUIDパラメータが存在する場合、Revitで選択された要素がトピックに関連要素として追加されます。
