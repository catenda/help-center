# Catenda の PDF 上の QR コード

[ドキュメント設定](https://support.catenda.com/en/articles/7831371-document-settings)の[フォルダー構成](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90)で、フォルダーごとに QR コードを設定できます。

この機能は、Catenda のユーザーに、PDF に印刷された QR コードをスキャンして、使用しているドキュメントが最新バージョンであるかどうかを確認する機能を提供します。

この記事には、次のトピックに関する情報が含まれています。

_[配置](#h_ea221d5cae)-[構成](#h_e66cc03a0e)-[公開](#h_c7f0685c1c)-_検証

## 1. **ドキュメントにプレースホルダーを配置する**

この機能を使用するには、 Catenda が提供する**[QR コード プレースホルダー](https://drive.google.com/file/d/1SbGcp8hC8l7854HOCZuI8o-WIBMWrsyF/view)**をドキュメントに配置し、Catenda Hub にアップロードする必要があります。最小サイズは 2cm x 2cm である必要があります。

![](https://downloads.intercomcdn.com/i/o/1129210747/3afe134405c9c151b8ed9936/image.png?expires=1781092800&signature=c2ea1933f269989980b29fa6c815f2115ec45196d7a904078bb197360e86fddf&req=dSElH8t%2FnYZbXvMW3nq%2BgZCIR8olrrgqRy31Ne2%2BudU3rI2Jb6gXfXlYW6X%2F%0AXNTNl9vBqIGhWJFcubOVyA7Cdis%3D%0A)

QRコード プレースホルダーのダウンロード リンクは次の場所にあります:

**[ダウンロードリンク](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)**

**ファイル作成者はQRコードを配置する**

ドキュメントは Catenda にアップロードされた後は変更できないため、ドキュメントを Catenda にアップロードする前にプレースホルダー QR コードをドキュメントに配置する必要があります。

プレースホルダーは、注釈レイヤーを除く任意のレイヤーに配置できます。

Catenda が プレースホルダーを認識するには、レースホルダーをファイルに画像として追加する必要があります。公開されたドキュメント内の画像は、プレースホルダー画像とまったく同じ画像である必要があります。

**PDFの最適化**

多くのプログラムは、表示を改善し、ファイル サイズを縮小するために最適化手順を実行します。これらの手順により、画像内のバイト数が変わる可能性があり、Catenda が画像を認識できなくなります。

最適化なプレースホルダーの仕様は次の通りです。

ピクセル密度: 144 dpi

画像圧縮: ZIP

画像は 1 つの完全な画像である必要があります。一部のオプティマイザーは最適化として画像を分割する場合があります。最適化後に画像が完全であることを確認してください。

### 1.1 **既存のドキュメントに**プレースホルダー**を配置する**

自分で作成していないドキュメントがあり、それを Catenda Hub にアップロードする前に プレースホルダーを追加する場合は、必ずドキュメントを編集し、プレースホルダーを画像として追加してください。

### 1.2 **Catendaドキュメントに**プレースホルダー**を配置する**

ドキュメントがすでに Catenda にある場合は、QR プレースホルダーを追加して新しいリビジョンをアップロードする必要があります。PDF 編集プログラムにアクセスできない場合は、[画像スタンプ注釈ツールを](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6)使用してドキュメントに QR プレースホルダーを追加できます。

![](https://downloads.intercomcdn.com/i/o/1197761140/e407aac8f89086efab976453/image.png?expires=1781092800&signature=93f547f371aaf2a67b931459774de9867e16dbd304b42df02d28762b615b70f2&req=dSEuEc54nIBbWfMW3nq%2BgT3wFjma59LIi2iWgcMB8GOKC1mffLOFVBr8k4Wd%0ApaGW5%2BMUQxjnHU0wA0d8aNKTxk4%3D%0A)

QR プレースホルダーが認識されるようにドキュメントを保存するには、ドキュメント プレビューの左上にある[印刷ボタンを使用してドキュメントを印刷します。](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70)

![](https://downloads.intercomcdn.com/i/o/1197761142/3284ae620e6aea1d0e1aeddb/image.png?expires=1781092800&signature=630614b8db499ad4f639229ddee012861f8aa7fd52e80f9d81fd9b01472e5433&req=dSEuEc54nIBbW%2FMW3nq%2Bgbr%2BMp2r0QdQ50i1PZxpD2Tq17MNM16gKK1OL7l7%0AP21d7IzgsDWpLp%2FqGqsJv9mhn9w%3D%0A)

これにより、ブラウザの印刷ダイアログが開きます。

Google Chrome の場合は次のようになります。

![](https://downloads.intercomcdn.com/i/o/1197761143/ca0008220471ff674553aade/image.png?expires=1781092800&signature=a23409288a684e9fd3a41bde12b8341fe53b56948aa2b2ccfc3b0152f0a5a0cb&req=dSEuEc54nIBbWvMW3nq%2BgWKV6EiKi9ltLcS%2FCClj%2FLrCXOIXiAUd1TfvHdg4%0A6mlGzpsFLJGOOOmmJKVG01CRu5w%3D%0A)

印刷ダイアログで、ドキュメントを PDF に印刷します。

> **Note:** **注 1:**ドキュメントを印刷した場合にのみ、QR コードはコンテンツ レイヤーに表示されます。ドキュメントをダウンロードすると、注釈レイヤー上に表示されます。注**2:** PDF に印刷すると、ドキュメントのコンテンツがラスタライズされます。つまり、Catenda にリビジョンとしてアップロードすると、テキストは検索できなくなります。

プレースホルダーを含む印刷された PDF を、Catenda に新しいリビジョンとしてアップロードできるようになりました。

リビジョン履歴をきれいに保つには、QR コードなしで以前のリビジョンを取り消すことをお勧めします。

## 2. **Catenda HubでQRコードを設定する**

QR コードの割り当てはフォルダーを介して行われるため、各プロジェクト管理者はこの機能を有効にするフォルダーのセットを選択できます。

プロジェクト内のフォルダーに QR コード機能を割り当てる手順は次のとおりです。

1. ドキュメント -> 設定で、**「フォルダ構成」に移動します**

![](https://downloads.intercomcdn.com/i/o/1197761141/6b97d62f02f42c42aaf665c0/image.png?expires=1781092800&signature=924ccc92088fc8933195458f1d1a6bc636a1ee16d537e233b9e3729fda0d5c95&req=dSEuEc54nIBbWPMW3nq%2BgaOQ1GP5AkmZ4OfZCro1mXa8MA%2FBqkTlX9vDTF6%2B%0A7ITRrlmBB4Nl0a3RhOsikgtlbpc%3D%0A)

2. 目的のフォルダの横にあるプラスをクリックしてフォルダ設定を開き、「QRコードの割り当て」で**「はい」を選択します。**

![](https://downloads.intercomcdn.com/i/o/1197761134/809fb58ba028f520f148e603/image.png?expires=1781092800&signature=eff827d87d1eacbbc51f18238b368e7414d2c63c56920d8aa77c9ed3695c2191&req=dSEuEc54nIBcXfMW3nq%2BgSNJIN5XosURXVP5hDOiDhhu8wZ2H0nxf7cR0r%2BX%0A4WY1t%2Fn2Tk%2FZ%2FgjYAItxeSdvCw8%3D%0A)

プレースホルダーのスキャンと QR コードの配置は、QR コード割り当て設定がされたフォルダーでのみ実行されます。

> **Note:** **注意:**親フォルダが割り当てられると、すべてのサブフォルダにこの割り当てが適用されます。親フォルダーがまだ割り当てられていない場合は、任意のフォルダーに QR コードを割り当てることができます。

### 2.1 **QRコードによる公開**

1. プレースホルダー付きのPDFの新しいリビジョンをQRコード割り当てのフォルダーにアップロードします。
1. 公開時にPDFがスキャンされ、プレースホルダーがQRコードに置き換えられます（このリビジョン用に生成されます）。
1. 新しく生成された QR コードは PDF の一部となり、Catenda Hub で表示/スキャンしたり、ダウンロードしたりできるようになります。

![](https://downloads.intercomcdn.com/i/o/1197761137/d4fe68cdae3e1e6912f05ebd/image.png?expires=1781092800&signature=760312f6a658a84fc74d98fa163e4efab45b0fbc92373f818bda714e59170b99&req=dSEuEc54nIBcXvMW3nq%2BgW1aty82oT4iOBD%2FUN26fKcqFj08iFzNFY6tw6%2Fa%0AYWSE7mCt2AgYp7Xg%2Fa9sfT9a%2BNk%3D%0A)

QR コード プレースホルダーの配置と Catenda Hub にアップロードした後の結果の例を次に示します。1. 図面のタイトル ブロック内のプレースホルダー。**アップロードの準備完了。**

![](https://downloads.intercomcdn.com/i/o/1197761145/720ae3e9a14be7e04ac3ee1e/image.png?expires=1781092800&signature=93a4ba0d9e3747ce678bbb34b10b89170bc76f80f8d34df832a48e34a7a8207b&req=dSEuEc54nIBbXPMW3nq%2BgbkuiC%2BoLYrY3YA5J5B6PLQYQ3cLISmhJGltcALE%0AwVVZQfK87vuf0xg87f%2FYF42645w%3D%0A)

2. タイトル ブロックのプレースホルダーが生成された QR コードに置き換えられます。**検証の準備が整いました。**

![](https://downloads.intercomcdn.com/i/o/1197761152/ab328cff3eeb80655f3a8799/image.png?expires=1781092800&signature=ca4007688886d007b5e9705202e4f443898f2c527d16bbdb55e19c8149102357&req=dSEuEc54nIBaW%2FMW3nq%2BgUMbgk%2BH%2BiP0ahWPHMr4Z%2B%2FvKPL4rmFSr5rzJ%2FhI%0Ala6EH0k22F1nvsVgXuBcMVjotkQ%3D%0A)

### 2.2 **ドキュメント履歴**

[プレースホルダー QR コード付きのドキュメントをアップロードすると、右側の情報メニュー](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision)のドキュメント履歴で、そのドキュメントが正常に処理されたことを確認できます。

![](https://downloads.intercomcdn.com/i/o/1197761150/57df9a4c5fb5ff8f4a40f26f/image.png?expires=1781092800&signature=4ccafc42c0cff3027e4014ec9b36e579702eb0f9d944f4aae94e10a10e75f2f6&req=dSEuEc54nIBaWfMW3nq%2BgW3liAzCEWMdtswnZ8b%2FdsIYDk6vs7AY0VuAISOM%0A5zL%2BB82QB3Mm7%2BXoD1a68ByVaGg%3D%0A)

QR コードの生成に失敗した場合は、QR コードが 2cm x 2cm より小さかったか、画像ではなく注釈として配置されたことが原因である可能性があります。

**注釈のフラット化**

一部のソフトウェアでは、注釈をフラット化してプレースホルダーを処理できるようになります。

以下にいくつか例を挙げます。

**PDF X-change**

![](https://downloads.intercomcdn.com/i/o/1197761149/8d566402da7012e2b6b4a4b9/image.png?expires=1781092800&signature=98be9ea0914a51ad88e615bf2fae261fef4e18333f9d971f1d4ceb6379689a06&req=dSEuEc54nIBbUPMW3nq%2BgfKKbYtvUa7p5lMBTSgJXX3hB86Ed2szTCH0Nr81%0A5VRJm%2B%2FkUS4gBZA1PuEdQr90W3k%3D%0A)

**Adobe acrobat**

_BlueBeam Revu_ BlueBeam Revu にプレースホルダーを配置してドキュメントを保存すると、注釈として追加されます。QR コードをフラット化してドキュメントのコンテンツ レイヤーの一部にすることは可能ですが、定期的に保存したり、ファイル サイズを縮小するオプションを使用したりしても、QR コードが変更され、Catenda では機能しなくなります。

QR コードを catenda で動作させるには、代わりに次の操作を行います。

BlueBeam ドライバーを使用してドキュメントを印刷します。

![](https://downloads.intercomcdn.com/i/o/1197761151/3b28ec460449386de8ca9915/image.png?expires=1781092800&signature=d666f4c0f5bf61d45d012eb85fe101f80a7d33c82d165244d3a8291da111023f&req=dSEuEc54nIBaWPMW3nq%2BgaXfV2mXghoFW3la9uKo2cVa7MFbievAqlrZIeLL%0APcLWL%2FoPNXBEPpwMfowQl6qsx08%3D%0A)

[名前を付けて保存] ダイアログで、ZIP グラフィックを選択し、後処理を有効にします。これは、プレースホルダーに使用される圧縮アルゴリズムが ZIP であるためです。

![](https://downloads.intercomcdn.com/i/o/1197761156/c4e4e324452c0fd5c312df21/image.png?expires=1781092800&signature=5daa1cb46bb56728595267423bd70589aea4d7175210d8aabc0d97711889216a&req=dSEuEc54nIBaX%2FMW3nq%2BgbRxiWqqg2m%2FDPxBVMjyCUzuRLH3wYRl4AelhdXy%0AD2kjTvtIAwGLO6KWyqgzG91MFCA%3D%0A)

後処理メニューで、「隣接する画像を結合」オプションを選択します。これは、画像が通常 2 つに分割され、再び結合されるためです。ページ サイズが既定のオプションとして存在しない場合は、ここで独自のカスタム サイズを追加できます。

![](https://downloads.intercomcdn.com/i/o/1197761158/c76df2e570d45262685756f4/image.png?expires=1781092800&signature=06d07328128bcee3e58f179546e795032b8bc5d3493ab452d6ce2e665faf8c96&req=dSEuEc54nIBaUfMW3nq%2BgSTmqRIvQWZwM7avDBHJOLbE4ZJ%2BZzIlrwe0qrbY%0A9kuVRhezfu5Yp7m0fY8FgimMJ7I%3D%0A)

## 3. **最新版の検証**

スマートフォンで QR コードをスキャンすると検証ページに移動し、PDF のバージョンに応じて次の結果が表示されます。

1. あなたのリビジョンはPDFの最新バージョンです:**ドキュメントは有効です**
1. このリビジョンは PDF の古いバージョンです:**ドキュメントが無効です**
1. プレースホルダーをスキャンしました:**プレースホルダーをスキャンしました。このドキュメントは公開されていません**

    <div class="intercom-container"><img src="https://downloads.intercomcdn.com/i/o/1128836302/b5ed664002c909cad1388c1c/image.png?expires=1781092800&amp;signature=e32a0bc159c2fe53c0580cf78540908f18b726e36d6e988f6fd07bba7b2f7069&amp;req=dSElHsF9m4JfW%2FMW3nq%2BgRAbWSa0uwekHXdmw0dniPvD%2F48H6GJmWGPMPCrC%0AngeKuBJW%2FPMavpOc%2Btwvf9PFqVY%3D%0A"/></div>
