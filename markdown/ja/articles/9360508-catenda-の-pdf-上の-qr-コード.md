# Catenda の PDF 上の QR コード

QR コードは、[ドキュメント設定](https://support.catenda.com/en/articles/7831371-document-settings)の[フォルダ構成](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90)でフォルダごとに構成できます。

この機能により、Catenda のユーザーは、PDF に印刷された QR コードをスキャンすることで、使用しているドキュメントが最新バージョンであるかどうかを確認できます。

この記事では、以下のトピックについて説明します。

## 1. **Catenda Hub に QR コードをセットアップ**

QR コード割り当ては、フォルダを介して実行されます。これは、各プロジェクト管理者が、この機能を持つフォルダの選択セットを決定できることを意味します。

プロジェクト内のフォルダに QR コード機能を割り当てるための手順を以下に示します。

1. ドキュメント —> 設定で、**「フォルダ構成」**に移動します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/01-setup-qr-code-on-catenda-hub.png)

2\. 目的のフォルダの隣にあるプラス記号をクリックしてフォルダ構成を開き、「QR コードを割り当て」の下で**「はい」**と言います。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/02-setup-qr-code-on-catenda-hub.png)

プレースホルダーのスキャンと QR コードの配置は、QR コード割り当てされたフォルダでのみ行われます。

> **注意:** 親フォルダが割り当てられると、すべてのサブフォルダにこの割り当てが付与されます。QR コードは、親フォルダがまだ割り当てられていない場合、任意のフォルダに割り当てできます。

## 2. ドキュメントにプレースホルダーを配置する

この機能を使用するには、Catenda が提供する**[QR コード プレースホルダー](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)**をドキュメントに配置して、Catenda Hub にアップロードする必要があります。_寸法要件:_ 最小サイズは 2 cm × 2 cm である必要があります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/03-placing-the-placeholder-in-your-document.png)

QR コードのダウンロード リンクは、ここで見つけることができます。

_[ダウンロード リンク](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)_

### 2.1 ファイル作成者として QR コードを配置する

ドキュメントを Catenda にアップロード後は変更できないため、プレースホルダー QR コードをドキュメントに配置してから Catenda にアップロードすることが重要です。プレースホルダーは、注釈レイヤーを除く任意のレイヤーに配置できます。Catenda が QR コードを認識するには、イメージとして追加する必要があります。公開されたドキュメント内のイメージは、プレースホルダー イメージとまったく同じである必要があります。

**PDF の最適化**多くのプログラムは、表示の向上とファイル サイズの削減のための最適化ステップを実行します。これらのステップにより、イメージ内のバイト数が変わる可能性があり、Catenda がそれを認識できなくなります。最適化に役立つプレースホルダーに関する情報をここに示します。ピクセル密度: 144 dpi イメージ圧縮: ZIP イメージは 1 つの完全なイメージである必要があります。一部のオプティマイザーは、最適化としてイメージを分割する場合があります。最適化後、イメージが完全なままであることを確認してください。

_Archicad_ QR コードを配置する場合は、以下を使用してください: インポート > 相互運用性 > ファイルからマージ > ワークシートをインポートして開く > ドラッグアンドドロップ ワークシートを開き、PNG をドラッグ アンド ドロップすると、解像度が変わり、機能しません。

### 2.2 既存のドキュメントに QR コードを配置する

作成していないドキュメントがあり、それを Catenda Hub にアップロードする前に QR プレースホルダーを追加したい場合は、ドキュメントを編集し、QR プレースホルダーをイメージとして追加してください。

### 2.3 Catenda ドキュメントに QR コードを配置する

ドキュメントが既に Catenda にある場合は、QR プレースホルダーを追加し、新しいリビジョンをアップロードする必要があります。PDF 編集プログラムにアクセスできない場合は、[イメージ スタンプ注釈ツール](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6)を使用して、QR プレースホルダーをドキュメントに追加できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/04-placing-the-qr-code-a-catenda-document.png)

QR プレースホルダーが認識されるようにドキュメントを保存するには、ドキュメント プレビューの左上に表示される[プリント ボタン](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70)でドキュメントを印刷します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/05-placing-the-qr-code-a-catenda-document.png)

これにより、ブラウザーのプリント ダイアログが開きます。Google Chrome の場合は、次のようになります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/06-placing-the-qr-code-a-catenda-document.png)

プリント ダイアログで、ドキュメントを PDF に印刷します。

> **注 1:** QR コードは、ドキュメントを印刷した場合のみコンテンツ レイヤーに終わります。 ドキュメントをダウンロードした場合、注釈レイヤーに配置されます。 **注 2:** PDF に印刷することにより、ドキュメントのコンテンツがラスタライズされます。 これは、リビジョンとして Catenda にアップロードするときに、テキストが検索可能にならないことを意味します。

印刷された PDF とプレースホルダーは、新しいリビジョンとして Catenda にアップロードできるようになりました。リビジョン履歴をクリーンに保つには、QR コードなしの以前のリビジョンを取り下げることをお勧めします。

## 3. **QR コードを使用した公開**

1. QR コード割り当てされたフォルダにプレースホルダー付きの PDF の新しいリビジョンをアップロードします。
2. 公開中に PDF がプレースホルダーについてスキャンされ、QR コード（このリビジョン用に生成）に置き換えられます。
3. 新しく生成された QR コードは PDF の一部になり、Catenda Hub で表示/スキャンおよび/またはダウンロードできます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/07-publishing-with-qr-codes.png)

QR コード プレースホルダーの配置と Catenda Hub にアップロード後の結果の例を示します。1\. 図面のタイトル ブロック内のプレースホルダー。**アップロードの準備完了。**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/08-publishing-with-qr-codes.png)

2\. タイトル ブロック内のプレースホルダーは、生成された QR コードに置き換えられます。**検証の準備完了。**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/09-publishing-with-qr-codes.png)

### 3.1 **ドキュメント履歴**

プレースホルダー QR コード付きのドキュメントをアップロードすると、[右側の情報メニュー](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision)のドキュメント履歴で正常に処理されたことを確認できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/10-document-history.png)

QR コードの生成に失敗した場合、これは QR コードが 2 cm × 2 cm より小さいか、イメージではなく注釈として配置されたために発生する可能性があります。

**注釈をフラット化する**一部のソフトウェアでは、注釈をフラット化できます。これにより、プレースホルダーを処理できます。いくつかの例を次に示します。

**PDF X-change**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/11-document-history.png)

**Adobe Acrobat**

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3d7d02c461d3.png" width="300"/> --> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3398dc9eef22.png" width="300"/>

_BlueBeam Revu_ BlueBeam Revu にプレースホルダーを配置してドキュメントを保存すると、注釈として追加されます。QR コードをフラット化してドキュメントのコンテンツ レイヤーの一部にすることは可能ですが、通常に保存した場合でも、ファイル サイズを削減するオプションを使用した場合でも、QR コードは変わり、Catenda では機能しません。QR コードが Catenda で機能するようにするには、代わりに BlueBeam ドライバーでドキュメントを印刷してください。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/12-document-history.png)

名前を付けて保存ダイアログで、ZIP グラフィックスを選択し、後処理を有効にします。これは、プレースホルダーに使用される圧縮アルゴリズムが ZIP だからです。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/13-document-history.png)

後処理メニューで、隣接するイメージを結合オプションを選択します。これは、イメージが通常 2 つに分割されるため、それを再び結合するからです。ページ サイズがデフォルト オプションとして存在しない場合は、カスタム サイズをここに追加できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/14-document-history.png)
