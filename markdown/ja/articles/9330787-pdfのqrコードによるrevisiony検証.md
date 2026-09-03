# PDFのQRコードによるrevisiony検証

生成されたQRコードを含むドキュメント revisionを物理的な紙に印刷して、プロジェクトメンバーが手に持っている紙がまだ最新版であるかどうかを確認できるようにします。

設定されたフォルダは、[フォルダアイコン](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page#h_6af15c36b3)の歯車バッジで識別できます。これは、生成されたQRコードを含むrevisionがどのように見えるかの例です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/01-intro.png)

## 1. **フォルダ設定**

QRコードスタンプは、ドキュメントページで[設定されたフォルダに対して有効にできます](https://support.catenda.com/en/articles/7831371-document-settings#h_166a269870)。_必要なアクセス権:_ 管理者

設定されたフォルダでは、アップロードされたドキュメント内の新しいPDF revisionが処理されます。Catendaはドキュメントをスキャンして、以下に記載されているQRコードプレースホルダ画像を探します。プレースホルダが正常に識別されると、revisionのQRコードが生成されます。_必要なアクセス権:_ ドキュメントへの書き込みアクセス

### 1.1 **QRコードを割り当てる**

フォルダにQRコードスタンプを割り当てるには、[ドキュメントページ](https://support.catenda.com/en/articles/8204673-documents-page)のサブページとして見つけることができる[ドキュメント設定](https://support.catenda.com/en/articles/7831371-document-settings)に移動します。ドキュメント設定で、[フォルダ設定メニュー](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90)を展開します。これはフォルダ設定メニューがどのように見えるかの例です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/02-assign-qr-code.png)

一番下にQRコード割り当てドロップダウンがあります。ドロップダウンをクリックして、「はい」を選択してこのフォルダを設定します。

**設定の継承**親フォルダに設定が設定されている場合、すべてのサブフォルダがその設定を継承します。

## 2. **QRコードプレースホルダの配置**

このアーティクルの冒頭で述べたように、設定されたフォルダにアップロードされたrevisionに対してQRコードを生成するために、Catendaはプレースホルダ画像を探します。QRコードプレースホルダ画像は次のようなものになります：

<p class="intercom-align-center no-margin">[<img alt="Catenda QR-Code placeholder" src="https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/inline-8c4db2f4912c.png" width="150"/>](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)</p>

QRコードプレースホルダをダウンロードするには、[ここをクリック](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)してください

> **警告:** この画像をコピー/ペーストしたり、名前を付けて保存したりしないでください。画像は図面上では同じに見えるかもしれませんが、認識されません。

プレースホルダをPDFに配置する方法について詳しく知るには、[ここをクリック](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda)してください。これはプレースホルダが図面のタイトルブロックに配置されたときにどのように見えるかの例です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/03-qr-code-placeholder-placement.png)

## 3. **プレースホルダ付きrevisionのアップロード**

プレースホルダ付きPDFの新しいrevisionをQRコード割り当てのあるフォルダにアップロードします。これは公開revisionにのみ適用されます! ドラフトまたは共有PDFは、公開された後にのみQRコードが生成されます。

### 3.1 **Revision QRコード生成**

QRコードプレースホルダを配置した後、PDFを設定されたフォルダへの新しいrevisionとしてアップロードできます。アップロード中にCatendaはドキュメント内の画像を処理します。

**バイト要件** Catenda QRコードプレースホルダ内の黒と白のピクセルに属する正しいバイトが正しい順序で存在する必要があります。

**サイズ要件**画像は最小幅および高さ2cm × 2cmである必要があります。

**生成されたQRコードの例**これは、PDFが処理され、QRコードが追加された後、上記の例のタイトルブロックがどのように見えるかの例です：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/04-revision-qr-code-generation.png)

## 4. **ステータスワークフロー -** QRコード生成を公開

ステータスワークフローなしでは、アップロードされたすべてのrevisionは即座に公開されます。ドキュメントがQRコードプレースホルダについてスキャンされるのは、公開される場合のみです。

### 4.1 **共有revisionと公開revision**

ステータスワークフローが有効な場合、新しいrevisionは公開に先立つステップとして共有revisionとしてアップロードされます。共有revisionを見ると、Catendaが生成したQRコードで変更される前の元のドキュメントを表示できます。ステータスワークフローにより、プレースホルダQRコードが生成されたQRコードと入れ替わるのは、プレースホルダQRコードを持つ設定されたフォルダ内の共有revisionが公開されたときです。
