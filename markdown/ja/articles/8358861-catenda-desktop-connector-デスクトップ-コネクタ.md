# Catenda Desktop connector (デスクトップ コネクタ)

> PCとCatendaプラットフォーム間のファイル管理を簡素化し、効率的な一括アップロード、ダウンロード、スケジュール同期を可能にします。

> **注:**プラグインのインストール ファイルは、[このヘルプ記事](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations)にあります。

この記事では、次の情報について説明します。

## 1. **インスタントアップ/ダウンロード**

Desktop Connector を使用すると、ローカル システムから Catenda Hub の指定したフォルダにファイルをアップロードできます。Catenda Hub上のいくつかのフォルダを選択して、ローカルマシン上の場所にダウンロードすることもできます。

### 1.1 **アップロード速度**

Desktop Connector を使用したファイルのアップロードは、ブラウザ経由ではなく API 経由でインポートされるため、通常のアップロード プロセスよりもファイル転送が高速です。

したがって、一度に大量のデータをアップロードする場合は、ファイルをアップロードするのに最適な方法です。

### 1.2 **安定したアップロード**

複数のファイルをドラッグアンドドロップしたり、Catenda Hubのzipアップロード機能を使用したりすると、1つの大きなデータセットがアップロードされることになり、アップロードのサイズが大きいほど、Catenda Hubのドキュメント構造にファイルを送信するまでの待ち時間が長くなります。

アップロードファイルサイズが大きければ大きいほど、失敗するリスクも高くなります。インターネット接続が途中で切断される可能せもあり、アップロードを繰り返すことになりかねません。

一度に 1 つのファイル

Desktop Connector では、フォルダ構造から一度に 1 つのファイルをアップロードすることで、この障害のリスクを最小限に抑え、時間を大幅に節約できます。

## 2. **同期**

ファイルが定期的にアップロードまたはダウンロードされるタイミングをスケジュールできます。

### 2.1 **ローカルシステム - > Catenda Hub**

Desktop Connector は、ローカルシステム上のファイルがCatenda Hubプロジェクトで最新であることを確認します。

### 2.2 **Catenda Hub -> ローカルシステム**

また、Desktop Connector がローカル システム上に常に最新バージョンの Catenda Hub ドキュメントを保持するという逆の方法も機能します。

## 3. **サインイン**

Desktop Connector を初めて開くと、サインインするように求められます。

サインインボタンをクリックすると、デフォルトのブラウザが開き、Catenda Hubアカウントへのログインを求めるページが表示されます。

ログイン後、またはすでにログインしていた場合は、Catendaアカウントへのアクセスを許可するように求められます。

[アクセスを許可] をクリックすると、デスクトップ コネクタ アプリを開くように求められます。

その後、Desktop Connector [のホーム ページ](#h_097078145d)にリダイレクトされます。

![](https://downloads.intercomcdn.com/i/o/950031540/36cd0ebbd558689393707668/image.png?expires=1781092800&signature=0e4b881b5ad87ef25b75105e7a7e8ecd494477dfaa34d1d4278e9b4fa5b20dff&req=fSUnFsp%2FmIVfFb4V1XW4gfDY9EEgr1R66lyc8%2Fis2Xr%2FzXcao8SXlcGPq7zG%0ADZpSrheuhiUYwCibiwZ1deljSg%3D%3D%0A)

## 4. **ホームページ**

デスクトップコネクタを起動すると、次のようになります。

![](https://downloads.intercomcdn.com/i/o/949987194/4ea79b327a432d2fbe6ddd0c/image.png?expires=1781092800&signature=4d94f80aa64fef1e3c1a73bf2deff039ac0475207a39783a19617c3e92a8ae5d&req=fSQuH8F5nIhbFb4V1XW4gTcWjiViXzLHPjg0U6HS3fsJi7aRbTkCAMiMYSfa%0ASUgK3XjJ8oymzuQQNs7TggJgJg%3D%3D%0A)

### 4.1 **起動時に実行（スタートアップアプリ）**

起動時にデスクトップコネクタを実行するには、このオプションを選択します

### 4.2 **ログアウト**

右下のログアウトボタンをクリックしてログアウトします。

![](https://downloads.intercomcdn.com/i/o/950021316/0053ee8a768a5188e6313c57/image.png?expires=1781092800&signature=43a10ad461d99e318a20b35ee132a99b1abed0e726ac4e1fdb3c57928b439578&req=fSUnFst%2FnoBZFb4V1XW4gThqJOWIUgCvL1w4D%2FD00hZl%2BjSWkhBzu0AfrfCB%0At7yYs0Cvm2OWN4cYaarP2Iu8jw%3D%3D%0A)

## 5. **プロジェクト一覧**

ここには、プロジェクトの概要と、各プロジェクトに設定したアップロードタスクとダウンロードタスクの数が表示されます。

プロジェクトの名前をクリックすると、現在のアップタスクとダウンロードタスクを表示したり、新しいタスクをスケジュールしたりできます。

### 5.1 **「同期」ボタン**

新しいプロジェクトに最近参加した場合は、この同期ボタンをクリックして、参加しているプロジェクトの新しいリストにロードできます。

![](https://downloads.intercomcdn.com/i/o/950025424/2f27581570051bde063c7246/image.png?expires=1781092800&signature=ef6298b070111ca73c8e594595b72887bd2b9b9cac65cea8e800e7af69f4ec2d&req=fSUnFst7mYNbFb4V1XW4geobuS5sg5oKpjFhFVSCA3gu2MlbQTC4KuaGF1EC%0A3NuFgqd7xXl8O8cJztQFnUVDow%3D%3D%0A)

### 5.2 **アップロードタスク**

このタスクを使用すると、システムから Catenda Hub へのファイルの定期的なアップロードをスケジュールできます。

### 5.3 **ダウンロードタスク**

このタスクを使用すると、Catenda Hubからシステムへのファイルの定期的なダウンロードをスケジュールできます。

ダウンロードしたドキュメントは、解凍された状態でシステムに保存されます。

### 5.4 **戻るボタン**

このボタンをクリックすると、[ホームページ](#h_097078145d)に戻ります

![](https://downloads.intercomcdn.com/i/o/950023253/d65643c0a2f97d7bc7d2319e/image.png?expires=1781092800&signature=a5c07c2bae2a7ad2cb375cfc7b58e84de093d43a89c6106dadabc2204c59e04e&req=fSUnFst9n4RcFb4V1XW4ga0YsQM1%2FTQcJiZjnQF4y8vosAgaXDzX%2Bu%2BJTnPP%0ArEpZpux7zmL2kXm%2Fj27ea4%2FJnQ%3D%3D%0A)

## 6. **タスク一覧**

ここでは、現在のアップタスクとダウンロードタスクを確認できます

### 6.1 **戻るボタン**

このボタンをクリックすると、[ホームページ](#h_097078145d)に戻ります

![](https://downloads.intercomcdn.com/i/o/950023253/d65643c0a2f97d7bc7d2319e/image.png?expires=1781092800&signature=a5c07c2bae2a7ad2cb375cfc7b58e84de093d43a89c6106dadabc2204c59e04e&req=fSUnFst9n4RcFb4V1XW4ga0YsQM1%2FTQcJiZjnQF4y8vosAgaXDzX%2Bu%2BJTnPP%0ArEpZpux7zmL2kXm%2Fj27ea4%2FJnQ%3D%3D%0A)

## 7. **ログフォルダ**

このボタンは、システム上のDesktop Connectorログのフォルダの場所を開きます。

## 8. **トラブルシューティング**

### 8.1 **ドキュメント名**

ドキュメント名にその文字が含まれていないことを確認してください。`\\`

この文字は、Windowsのファイルパス階層の一部であり、ドキュメントが間違った場所に配置される原因となります。

### 8.2 **サーバー プロジェクトの場所が空です**

ローカルファイルをプロジェクトに同期するには、Catenda Hubのプロジェクトのドキュメントセクションに少なくとも1つのフォルダが必要です。

### 8.3 **フォルダの権限**

フォルダに対する適切な権限がない場合、エラーが発生する可能性があります。ダウンロードしようとしているフォルダを右クリックして、適切な権限を許可します。

![](https://downloads.intercomcdn.com/i/o/areracg3/1373014007/de25ee387219641a228498f4ac53/image.png?expires=1781092800&signature=64b8cd24d56f3e0580e09bdb9d645763cedbc428796cb07f17a8c6323dc2ea1a&req=dSMgFcl%2FmYFfXvMW3nq%2BgZc5Y84qY4uRCZuDVwfwRgy6b70NOUqyyzImBAK8%0AJqsdNUQZzAnuahXe74VbjSVe6wc%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1373023427/6ecce5bcacc82597271780eb25d3/image.png?expires=1781092800&signature=7dc5b8845aa0ed55bee837454bbe4721b0227fa331cbac7e0260fcb130e55a8d&req=dSMgFcl8noVdXvMW3nq%2BgavEOFqOQk9RKx%2Flkpajr98q6QPJnXWqde%2BO1fgd%0A%2BprOu4vps6w6%2F%2FETQaYJC7sUjaY%3D%0A)
