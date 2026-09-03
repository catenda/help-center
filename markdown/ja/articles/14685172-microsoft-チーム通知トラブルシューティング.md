# Microsoft チーム通知トラブルシューティング

この記事では、Microsoft チーム ワークフロー経由で Catenda と Microsoft チーム通知を構成するときに発生する可能性のあるエラーについての情報が記載されています。

この記事には、次のトピックに関する情報が含まれています: [通知なし](#h_42fb432d1c)

## 1. **Microsoft チーム チャネルに通知がない**

Microsoft チーム ワークフロー URL が Catenda で構成されており、通知設定の Microsoft チーム タブでチェックされている通知ボックスのいずれかについて Catenda 通知を受け取ったが、そこで構成されている Microsoft チーム チャネルにメッセージがない場合は、Microsoft チーム ワークフローに問題がある可能性があります。

Microsoft チーム ワークフローで何か問題が発生したかどうかを確認するには、チャネルの上にマウスを置いてメニューをクリックするか、チャネルの右上にあるメニューをクリックして、ワークフローを選択します。

<img alt="Microsoft Teamsチャネルアクションメニュー、ワークフローがハイライトされています。" src="https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/inline-f533eea19d48.png" width="290"/>  \<---> <img alt="Microsoft Teamsチャネルのアクションメニュー、ワークフローがハイライトされています。" src="https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/inline-1a6a43fe9eec.png" width="290"/>

ワークフローに問題がある場合、[ワークフロー] メニューの [チャネルへの webhook アラートを送信] ワークフローでエラーが表示される可能性があります。

![Microsoft Teams 接続エラーが発生しました、ご対応をお願いします](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/01-no-notifications-in-microsoft-teams-channel.png)

エラーは次のようになります: `接続の問題が発生しました。対応が必要です`

ワークフローをクリックして、ワークフローをお好みのブラウザーで開くか、[詳細] をクリックして Microsoft チームで詳細情報を確認してください。これは、エラーが発生した場合の Microsoft チームの Webhook ワークフロー詳細の外観です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/02-no-notifications-in-microsoft-teams-channel.png)

ここで、エラーが発生した時刻と日付を確認できます。失敗の時刻と日付をクリックして、ワークフローをお好みのブラウザーで Power Automate で開きます。これが Power Automate での失敗の外観です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/03-no-notifications-in-microsoft-teams-channel.png)

Power Automate のアラートから、何が問題である可能性があるかについてさらに詳しく知ることができます。この場合、次のエラー メッセージが表示されました：

`アラート: お客様の <email> 接続が機能していません: お客様のフローの <email> 接続を再度サインインする必要があります。最も一般的な原因は、パスワードが変更されたか、テナント管理者が設定したポリシーです。多要素認証が最近お客様のアカウントで有効になっている場合、接続も再認証が必要になることがあります。`

再認証するには、チームでワークフローをクリックして、Power Automate でワークフローを開きます。Power Automate の接続ページに移動して、そこで接続を確立することも可能です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/04-no-notifications-in-microsoft-teams-channel.png)

[アクション必須] ダイアログで [再認証] をクリックします。正常に認証された後、接続は [接続] ページに表示されます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/05-no-notifications-in-microsoft-teams-channel.png)
