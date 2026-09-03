# Catenda Desktop Connector FAQ

## 1. オンラインのみのファイル

多くのドキュメント管理システムでは、システム上にファイルのシャドウバージョンを表示でき、スペースを消費しません。ドキュメントがオンラインのみであることは、アーカイブまたはクラウドのようなバッジでわかることが多くあります。以下は、異なるサービスでオンラインのみのドキュメントがどのように見えるかの例です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/swkm9e7y/01-online-only-files.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/swkm9e7y/02-online-only-files.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/swkm9e7y/03-online-only-files.png)

Dropbox Google Drive Microsoft 365/SharePoint

Desktop Connectorがこのようなドキュメントのアップロードを試みると、それにアクセスしようとします。それぞれのサービスが実行されている場合、これが認識され、ドキュメントをローカルシステムにダウンロードし始めます。したがって、マシン上に十分なスペースがあることを確認してください。アップロード時も同様です。Desktop Connectorは、ドキュメントに変更があったかどうかを判断でき、オンラインのみであっても、変更された場合にのみCatendaへのアップロード用ファイルをダウンロードします。アップロードタスクが実行された後、システムにダウンロードされたすべてのファイルはスペースを消費します。これらの同期サービスの多くは、しばらくの間ドキュメントが使用されていない場合、定期的にスペースを解放します。これをすぐに発生させたい場合は、ドキュメントまたはフォルダを右クリックして、右クリックメニューでオンラインのみに変更できます。
