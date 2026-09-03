# Microsoft チームの通知

> タブを切り替えることなく情報を得られます。Catenda Hub を Microsoft チームに接続して、リアルタイム通知を優先チャネルで直接受け取ります。

Catenda notification 設定で Microsoft チームワークフローを設定することにより、Catenda アカウントから Microsoft チームチャネルに直接リアルタイム通知を受け取ります。_必要なアクセス権限:_ チャネル作成および Microsoft チームワークフロー管理権限を持つ **Microsoft チーム** アカウント。

Microsoft チーム通知タブは、[account notification settings ページ](https://support.catenda.com/en/articles/8272435-account-notification-settings)の上部近くに見つかります。このページは[account notifications page](https://support.catenda.com/en/articles/7439223-account-notifications-page)のサブページです。

![Catenda Hub 通知設定 Microsoft チーム通知 独自のチーム設定を持つプロジェクト](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/01-intro.png)

Microsoft チームワークフローが設定された後、Catenda通知が Microsoft チームでどのように見えるかを示します。

![Microsoft チームチャネル 投稿 レビュー待ち 新しいトピックを作成 新しいリビジョンがモデルにインポートされました](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/02-intro.png)

---

### Step 1: 専用チャネルを準備する

ユーザーは、Catenda通知用の特定のスペースを作成することで、プロジェクトの更新を整理できます。1\. **Microsoft チーム**で、**チーム**または**チャット**タブを選択します。2\. 既存のチームを使用するか(このステップをスキップ)、**チームを作成**します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/03-step-1-prepare-a-dedicated-channel.png)

名前を入力してチームを作成します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/04-step-1-prepare-a-dedicated-channel.png)

チームが作成されると、general というチャネルが自動的に追加されます。3\. 既存のチャネルを使用するか(このステップをスキップ)、チャネルを追加します。チームを右クリックしてアクション メニューで「チャネルを追加」を選択するか、チームをクリックして右上の**「チャネルを追加」**をクリックします。_必要なアクセス権限:_ チームのオーナーまたはメンバー。

![Microsoft チーム Catenda 統合 チャット チャネル チャネルを追加 メンバー 分析 アプリ タグ すべてのチャネルを非表示 メンバーを追加 チームを管理 タグを管理 リンクをコピー チームから退出](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/05-step-1-prepare-a-dedicated-channel.png)

> **注:** ゲストまたは外部アクセスでは、チャネルを作成できません。この場合、チャネル管理者に通知を送信するためのチャネルの URL を提供するよう依頼してください。

「チャネルを作成」をクリックすると、「チャネルを作成」ダイアログが表示されます。

![チャネルを作成 チャネル名 文字、数字、スペースが使用可能です 説明 チャネルタイプを選択 標準 プライベート スレッド 投稿](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/06-step-1-prepare-a-dedicated-channel.png)

**4. チャネルに名前を付ける**: "Catenda通知" または "Project-A-Notifications" のような わかりやすい名前を使用します。

**5. プライバシーを選択**: Catenda通知は標準チャネルとプライベートチャネルの両方に配信できます。

- チーム全体が更新を見たい場合は、**標準**を選択します。
- 通知が自分またはグループ内の人のみを対象としている場合は、**プライベート**を選択します。

6\. **作成**をクリックします。

---

### Step 2: チーム Webhook URL を生成する

過去に、Catenda チーム通知は、チャネル用に設定されていた Webhook Connector アプリケーションを通じて設定されていました。Webhook Connector アプリケーションは廃止されています。現在、webhook URL を作成する方法は、Microsoft チームワークフローを作成することです。

以下の手順に従って、新しい Microsoft チーム**ワークフロー** webhook を作成します。1\. **Microsoft チーム**を開きます 2\. 目的のチームにマウスを置いて3つのドットをクリックするか、チャネルを開いた後、右上の3つのドットをクリックします。3\. アクション メニューから Microsoft チーム**ワークフロー**を選択します。

<img alt="Microsoft チームチャネルアクションメニュー、ワークフローがハイライトされている。" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-f533eea19d48.png" width="290"/>  \<---> <img alt="Microsoft チームチャネルのアクションメニュー、ワークフローがハイライトされている。" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-1a6a43fe9eec.png" width="290"/>

4\. **"チャネルに webhook アラートを送信"**を検索して選択します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/07-step-2-generate-your-teams-webhook-url.png)

5\. セットアップ ステップに従ってチームとチャネルを選択します。**6. URL をコピー**: Microsoft チームワークフローが作成されたら、上部の「Webhook リンク をコピー」をクリックして、生成された webhook URL をクリップボードにコピーします。

> **注:** 💡**ヒント**: この URL をプライベートに保ちます。このリンクを持つ誰もが、チーム チャネルにメッセージを送信できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/08-step-2-generate-your-teams-webhook-url.png)

---

### Step 3: Catenda Hub に接続する

以下の手順に従って、webhook リンクを Catenda で設定します。これにより、Catenda はプロジェクト通知を送信する場所を認識します。

1. **Catenda Hub** にログインします。
1. **通知>設定**に移動します(アカウント レベルまたはプロジェクト レベル)。
1. 「Microsoft チーム」タブを選択して、一番下までスクロールします。
1. コピーした URL を **Webhook URL** フィールドに貼り付けます。
1. **保存**をクリックします。

    <div class="intercom-container intercom-align-center"><img height="320" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-a60f9c2dbac8.png" style="height: auto;" width="500"/></div>

1. **通知を有効にする**: ページの上部にあるトグルが**オン**に設定されていることを確認します。

    <div class="intercom-container intercom-align-center"><img height="159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-a3e9aa9365d2.png" style="height: auto;" width="500"/></div>

---

### Step 4: アラートをカスタマイズする

受け取る情報をカスタマイズして、通知の疲れを避けます。1\. 同じ**通知設定**メニューで、通知タイプのリストをスクロールします。**2. チェック ボックスをオン**にします チーム チャネルで受け取りたい特定の更新についてはチェックボックスをオンにします。これは Microsoft チーム通知メニューの例です。

![受け取りたい通知を選択 Catenda Hub メール Microsoft チーム通知 トピック ドキュメント 承認 コレクション モデル ユーザー 新しいトピックが作成されました トピックが自分に割り当てられました トピックが自分またはマイチームに言及されています トピックに割り当てられているコメント 自分が言及している 自分がフォローしているトピックで状態が変更されました トピックでタイプが変更されました 承認リクエストでパブリッシャーとして設定されました 自分が所属するチームが承認リクエストでパブリッシャーとして設定されました 承認リクエストが終了しました 提出チームのメンバー 新しい承認リクエストが提出されました ドキュメントが破棄されました 承認リクエストが終了しました 新しい承認リクエストが提出されました 新しい承認リクエストが自分のチームに割り当てられました 新しい承認リクエストが自分のチームによるレビューの準備ができました 自分のチームによるすべてのレビューが提出されました ドキュメントが破棄されました 承認リクエストが終了しました 最終承認のレビューチームのメンバーとして 新しい承認リクエストが提出されました 新しい承認リクエストが自分のチームに割り当てられました 新しい承認リクエストが自分のチームによるレビューの準備ができました 自分のチームによるすべてのレビューが提出されました 自分のチームによるすべてのレビューが提出されました レビューステップが完了しました ドキュメントが破棄されました 承認リクエストが終了しました 新しいモデルが作成されました 新しいリビジョンがインポートされました](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/09-step-4-customize-your-alerts.png)

グレーアウトされた通知ボックスは Microsoft チーム用に無効になっており、他の通知方法にのみ利用可能です。承認用の通知ボックスは、プロジェクトの[ドキュメント設定](https://support.catenda.com/en/articles/7831371-document-settings-page)で「共有 revision」が有効になっている場合に利用可能になります。

---

### Step 5: 確認

アカウントに送信され、Microsoft チームにも送信される通知があることを確認します。

1\. Catenda Hub でアクションを実行します。

> **警告:** ⚠️ **注:** すべての通知を Microsoft チームに送信することはできず、Microsoft チーム通知は通常、ユーザー自身が実行したアクションについて送信されません。model をアップロードするか、チームメイトに topic を作成したり、説明またはコメント内であなたをメンションしてもらい、リンク を確認します。

2\. **Microsoft チーム チャネル**を確認します。3\. メッセージは、Microsoft チーム**ワークフロー** ボットを経由してすぐに表示されます。
