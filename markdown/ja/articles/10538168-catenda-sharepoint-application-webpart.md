# Catenda SharePoint Application - Webpart

Catenda webpartを使用すると、SharePointページ内でCatendaプロジェクトのドキュメントセクションを参照できます。_Catendaアクセス必須:_ ドキュメント構造を参照するには読み取りアクセス、SharePointファイルをCatendaにアップロードするには書き込みアクセスが必要です。

## 1. **webpartの追加**

SharePointで既存のページを編集するか、新しいページを作成して編集します。編集モードでページにカーソルを合わせると、プラス記号`----+-----`の線が表示されるまで待ちます。[Catenda SharePointアプリケーション](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application)がサイトに追加されている場合、webpartのリスト内でCatendaドキュメントWebpartを見つけることができます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/01-adding-the-webpart.png)

その後、Catenda webpartを追加できるようになります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/02-adding-the-webpart.png)

まだCatendaアカウントを認可していない場合、webpartは次のように表示されます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/03-adding-the-webpart.png)

Catenda webpartが有効になったページを開き、まだアカウントを認可していない場合は、認可するよう求められます。アカウントの認可方法について詳しくは、[こちら](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application#h_788fe15988)を参照してください。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/04-adding-the-webpart.png)

アカウント認証情報を認可した後、「webpart設定を開く」をクリックするか、鉛筆アイコンをクリックして、SharePointページの訪問者がドキュメントセクションを表示できるようにするCatendaプロジェクトを選択します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/05-adding-the-webpart.png)

これは、設定されたwebpartを追加するときの外観です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/06-adding-the-webpart.png)

## 2. **ナビゲーション**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/07-navigation.png)

### 2.1 **表示**

Webpartの上部のパスは、このwebpart用に設定されているプロジェクトと、現在のフォルダ構造の場所を示しています。

### 2.2 **ナビゲーション**

フォルダ構造のその部分に戻るには、任意の要素をクリックします。フォルダを開くにはフォルダの名前をクリックします。ドキュメント名をクリックして、Catendaで直接開きます。

## 3. **ドキュメント表**

ドキュメント表は以下のようなものです：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/08-document-table.png)

要素を選択している場合は、ドキュメント表の上部に選択された要素の数が表示されます。

### 3.1 **ドキュメントとフォルダの選択**

行の要素の名前の外側のどこかをクリックするとその行が選択されます。Shiftキーを押したまま、最後に選択した項目と対象の項目の間のすべてのアイテムを選択します。Ctrlキーを押したまま、選択対象に要素を追加または削除します。

### 3.2 **Catendaアクセス設定**

各ユーザーはCatendaで独自のアクセス権を持っているため、プロジェクトメンバーの中には他のユーザーと異なるフォルダやドキュメントが表示される場合があります。

## 4. **webpart内のアクション**

Webpartの左上に、以下のアクションがあります：

### 4.1 **フォルダを作成**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/09-create-folder.png)

現在いるドキュメント構造の一部にフォルダを作成します。_Catendaアクセス必須:_ 書き込みアクセス

### 4.2 **ファイルをアップロード**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/10-upload-file.png)

これをクリックすると、ファイルナビゲーターが開き、アップロードするドキュメント(複数可)を選択できます。ドキュメントをアップロードすると、Catendaとwebpartでそのファイルが表示されます。このようにしてSharePointのドキュメント領域にアップロードされたファイルは表示されません。Catendaでのみです。_Catendaアクセス必須:_ 書き込みアクセス Webpart内の目的の場所にシステムからファイルをドラッグアンドドロップして、これらのファイルをCatendaにアップロードできます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/11-upload-file.png)

> **注:** フォルダをドラッグアンドドロップすると、zipファイルとして公開されます。フォルダ構造をアップロードする場合は、SharePointからダウンロードして、[zipアップロード](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure)または[Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector)経由でCatendaにアップロードする必要があります。

### 4.3 **再読み込み**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/12-reload.png)

他のユーザーがCatendaプロジェクトに変更を加えた場合、まだ変更が表示されないことがあります。その場合は、webpartを再読み込みして最新情報を取得することをお勧めします。

### 4.4 SharePointに公開

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/13-publish-to-sharepoint.png)

選択したドキュメントをCatendaからSharePointに公開します。このボタンをクリックすると、SharePointに公開ダイアログが開きます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/14-publish-to-sharepoint.png)

ダイアログの上部に、公開している要素の数が表示されます。

**新しい場所**選択したファイルをSharePoint内の新しい場所に公開する場合は、「新しい場所」を選択します。

**既存のターゲットを表示**ファイルが以前公開されており、以前公開されたファイルを更新する場合は、「既存のターゲットを表示」を選択する必要があります。

**公開**公開先の場所を設定したら、「公開」をクリックします。

## 5. **Catendaアクセス**

### 5.1 **Catendaプロジェクトへのアクセス権がない**

設定されたプロジェクトへのアクセス権がない場合は、次のエラーが表示されます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/15-no-access-to-the-catenda-project.png)

ぼかしされた部分はプロジェクトGUIDです。ない場合、またはプロジェクト内のドキュメントへのアクセス権がない場合は、「コンテンツなし - フォルダが空です」と表示されます。

### 5.2 **フォルダの作成へのアクセス権がない**

現在いるフォルダへの書き込みアクセス権がない場合に、新しいサブフォルダを作成しようとすると、次の画面が表示されます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/16-no-access-to-creating-folders.png)

### 5.3 **ファイルのアップロードへのアクセス権がない**

フォルダまたはドキュメントへの書き込みアクセス権がない場合にファイルをアップロードしようとすると、次の画面が表示されます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aq5swdfr/17-no-access-to-uploading-files.png)
