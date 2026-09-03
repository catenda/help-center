# Catenda Hub - Solibri ワークフロー

これは、Solibri と Catenda Hub 間の BCF サーバーを使用する場合の最適なワークフローを説明するドキュメントです。

1\. Catenda Hub プロジェクトへの接続から始めます。[( こちらを参照 )](https://intercom.help/bimsync-arena/en/articles/4670340-solibri-model-checker-and-bimsync-bcf-connection) 2\. 接続後、Solibri で clash 検出を実行し、プレゼンテーションを作成します。Solibri でプレゼンテーションを作成する方法はいくつかありますが、Catenda Hub との通信に最適な方法について説明します。A. ルールセットでチェックを実行します。B. プレゼンテーションに追加する Solibri 問題を見つけます。C. コミュニケーションに移動してスライドをプレゼンテーションに追加する代わりに、チェック結果の問題を右クリックして「スライドを追加」ボタンを押します。この方法で実行すると、その問題内のすべてのオブジェクトは Catenda Hub の問題に自動的に含まれ、位置を特定しやすくなります。これを Catenda Hub の「他を非表示」や「他を半透明」と組み合わせることで、問題に含まれるオブジェクトを常に把握できる優れた方法となります。この方法でスライドを作成する場合でも、コミュニケーションと同じ種類の問題レイアウトが表示され、タイトルの追加、説明の追加、追加の写真とコメントの追加が可能です。問題への人員割り当ても同様です。

![Workflow_Solibri_-_Bimsync.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/01-intro.png)

D. チェックが完了したら、コミュニケーションに移動して「チェック結果」からプレゼンテーションを作成します。その後、チェック結果で作成したすべての問題が新しいプレゼンテーションに表示されます。これらのスライドを既存のプレゼンテーションに追加する場合は、そのプレゼンテーションを右クリックして「結果からプレゼンテーションを更新」を押すことができます。これにより、結果で作成されたすべてのスライドがそのプレゼンテーションに含まれます。

![Workflow_Solibri_-Bimsync__1.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/02-intro.png)

3\. プレゼンテーションを作成したら、Catenda Hub との同期を開始できます。「プレゼンテーションを同期」を押すと、ポップアップメニューが表示されます。ここで、チェックボックスをオンにして同期方法を決定できます。「値の変換」に移動すると、Catenda Hub プロジェクトの値に一致するように異なる値を設定できます。

![Workflow_Solibri_-Bimsync__2.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/03-intro.png)

4\. 値の変換。例えば、Solibri で問題を直接人に割り当てたのに Catenda Hub で問題が割り当てられない場合、理由は値の変換が正しく設定されていないことです。

![Snag_62f59e4.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/04-intro.png)

問題に設定されたこれらの責任は、Catenda Hub プロジェクトのユーザーに一致するように設定できます。これは次の値の変換で実行されます：

![Snag_62c9ad3.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/05-intro.png)

値の変換ボタンは、プレゼンテーションを右クリックして「プレゼンテーションを同期」を押すときに表示されるポップアップメニューに表示されます。これらの問題が Solibri で割り当てられ、Catenda Hub プロジェクトと同期されると、通知がオンになっている場合、割り当てられたユーザーが通知を受け取ります。この方法により、Solibri と同期した後に Catenda Hub で問題を手動で割り当てる必要がありません。
