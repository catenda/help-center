# Catenda の PDF 上の QR コード

QR コードは、[ドキュメント設定](https://support.catenda.com/en/articles/7831371-document-settings)の[フォルダ設定](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90)でフォルダごとに設定できます。

この機能により、Catenda のユーザーは PDF に印刷された QR コードをスキャンして、使用しているドキュメントが最新バージョンであるかどうかを確認できます。

## 1. **Catenda Hub での QR コードのセットアップ**

QR コードの割り当てはフォルダ経由で行われます。つまり、各プロジェクト管理者は、この機能を使用するフォルダのセットを選択できます。

プロジェクト内のフォルダに QR コード機能を割り当てるための手順は以下の通りです；

1. ドキュメント → 設定で、**「フォルダ設定」**に移動します

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/01-setup-qr-code-on-catenda-hub.png)

2\. 目的のフォルダの横のプラスをクリックしてフォルダ設定を開き、「QR コードを割り当て」で**「はい」**を選択します

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/02-setup-qr-code-on-catenda-hub.png)

プレースホルダーのスキャンと QR コードの配置は、QR コード割り当てのあるフォルダでのみ行われます；

> **注釈:** 親フォルダが割り当てられると、すべてのサブフォルダにこの割り当てが適用されます。QR コードは、親フォルダがまだ割り当てられていない場合にのみ、任意のフォルダに割り当てることができます。

## 2. ドキュメント内にプレースホルダーを配置する

この機能を使用するには、Catenda が提供する**[QR コード プレースホルダー](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)**をドキュメント上に配置してから、Catenda Hub にアップロードする必要があります。_寸法要件:_ 最小サイズは 2cm × 2cm である必要があります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/03-placing-the-placeholder-in-your-document.png)

QR コードのダウンロードリンクはこちらにあります：

_[ダウンロードリンク](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)_

### 2.1 ファイル作成者として QR コードを配置する

Catenda にアップロードされたドキュメントは、アップロード後に変更できないため、プレースホルダー QR コードを Catenda にアップロードする前にドキュメント上に配置することが重要です。プレースホルダーは、アノテーションレイヤーを除くすべてのレイヤーに配置できます。Catenda が QR コードを認識するには、画像として追加する必要があります。公開されたドキュメント内の画像は、プレースホルダー画像と同じ画像である必要があります。

**PDF 最適化**多くのプログラムは、表示の改善とファイル サイズの削減のための最適化ステップを実行します。これらのステップにより、画像内のバイト数が変更される可能性があり、Catenda が認識できなくなります。最適化に役立つプレースホルダーに関する情報は以下の通りです。ピクセル密度: 144 dpi 画像圧縮: ZIP 画像は 1 つの完全な画像である必要があります。一部のオプティマイザーは、最適化として画像を分割する場合があります。最適化後に画像全体であることを確認してください。

_Archicad_ QR コードを配置する際は、以下を使用してください: インポート > 相互運用性 > ファイルからマージ > ワークシートをインポートして開く > ドラッグ アンド ドロップ。ワークシートを開いて PNG をドラッグ アンド ドロップすると、解像度が変更され、機能しません。

### 2.2 既存のドキュメント上に QR コードを配置する

作成していないドキュメントがあり、Catenda Hub にアップロードする前に QR プレースホルダーを追加したい場合は、ドキュメントを編集し、QR プレースホルダーを画像として追加してください。

### 2.3 Catenda ドキュメント上に QR コードを配置する

ドキュメントが既に Catenda にある場合は、QR プレースホルダーを追加し、新しいリビジョンをアップロードする必要があります。PDF 編集プログラムへのアクセス権がない場合は、[画像スタンプアノテーション ツール](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6)を使用してドキュメントに QR プレースホルダーを追加できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/04-placing-the-qr-code-a-catenda-document.png)

ドキュメント プレビューの左上にある[プリント ボタン](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70)でドキュメントを印刷して、QR プレースホルダーが認識されるようにドキュメントを保存します。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/05-placing-the-qr-code-a-catenda-document.png)

これにより、ブラウザーの印刷ダイアログが開きます。Google Chrome の場合は以下のようになります：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/06-placing-the-qr-code-a-catenda-document.png)

印刷ダイアログで、ドキュメントを PDF に印刷します。

> **注釈 1:** QR コードがコンテンツ レイヤーに表示されるのは、ドキュメントを印刷した場合のみです。ドキュメントをダウンロードすると、アノテーション レイヤーに表示されます。**注釈 2:** PDF に印刷することで、ドキュメントのコンテンツをラスタライズします。つまり、テキストを Catenda にリビジョンとしてアップロードするときに検索できなくなります。

プレースホルダー付きの印刷された PDF を新しいリビジョンとして Catenda にアップロードできます。リビジョン履歴をクリーンに保つため、QR コードなしの前のリビジョンを取り下げることをお勧めします。

## 3. **QR コードを使用した公開**

1. プレースホルダー付きの PDF の新しいリビジョンを、QR コード割り当てのあるフォルダにアップロードします
1. 公開中に、PDF がプレースホルダーについてスキャンされ、QR コード (このリビジョンに対して生成されたもの) に置き換えられます
1. 新しく生成された QR コードは PDF の一部になり、Catenda Hub で表示/スキャンしたり、ダウンロードしたりできます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/07-publishing-with-qr-codes.png)

ここに、QR コード プレースホルダーの配置と Catenda Hub へのアップロード後の結果の例があります。1\. 図面のタイトル ブロック内のプレースホルダー。**アップロード準備完了。**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/08-publishing-with-qr-codes.png)

2\. タイトル ブロック内のプレースホルダーが生成された QR コードに置き換わります。**検証準備完了。**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/09-publishing-with-qr-codes.png)

### 3.1 **ドキュメント履歴**

プレースホルダー QR コード付きのドキュメントをアップロードした後、[右側情報メニュー](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision)のドキュメント履歴で、正常に処理されたことを確認できます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/10-document-history.png)

QR コードの生成に失敗した場合、QR コードが 2cm × 2cm より小さいか、アノテーションとしてではなく画像として配置されなかった可能性があります。

**アノテーションのフラット化**一部のソフトウェアでは、アノテーションをフラット化して、プレースホルダーを処理できるようにしています。いくつかの例を以下に示します：

**PDF X-change**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/11-document-history.png)

**Adobe Acrobat**

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3d7d02c461d3.png" width="300"/> --> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3398dc9eef22.png" width="300"/>

_BlueBeam Revu_ BlueBeam Revu にプレースホルダーを配置してドキュメントを保存すると、アノテーションとして追加されます。QR コードをフラット化してドキュメントのコンテンツ レイヤーの一部にすることは可能ですが、通常に保存する場合でも、ファイル サイズ削減オプションを使用する場合でも、QR コードは変更されて Catenda では機能しません。QR コードを Catenda で機能させるには、代わりに BlueBeam ドライバーでドキュメントを印刷してください：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/12-document-history.png)

「保存」ダイアログで、ZIP グラフィックスを選択し、後処理を有効にします。これは、プレースホルダーに使用される圧縮アルゴリズムが ZIP であるためです。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/13-document-history.png)

後処理メニューで、「隣接画像を結合」オプションを選択します。これは、画像が通常 2 つに分割されるため、それを再び組み合わせるためです。ページサイズがデフォルト オプションとして存在しない場合は、ここに独自のカスタム オプションを追加できます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/14-document-history.png)
