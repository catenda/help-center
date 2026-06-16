# Catenda Hubでのファイル形式のプレビュー

当社のモデルビューアでは、IFC形式のみをサポートしています。その他のファイル 形式はすべて、ドキュメントセクションにアップロード可能です。

> **Note:** **注：**IFC、点群データ（e57、las）、およびGMLのプレビューは、3Dビューアで読み込むことができます。

この記事には、以下のファイル形式のプレビューに関する情報が含まれています：

**[オープン](#h_ee6b36a698) - [Open 3D](#h_2edd1d4e9c) - [Open 2D](#h_76964134d3) - [独自形式](#h_da902d0f10) - [有害](#h_f5a76051d8)**

## ベンダー中立形式

Catendaでは、所有するソフトウェアに関係なく誰もが共同作業を行えるよう、オープンスタンダードの採用を重視しています。

**一般的に、オープン規格は本質的にオープンな性質を持つため、誰でもその開発に参加することができます（[Wikipedia](https://en.wikipedia.org/wiki/Open_standard#:~:text=Typically%2C%20anybody%20can%20participate%20in%20their%20development%20due%20to%20their%20inherently%20open%20nature.)）。**

つまり、開発内容を支配しているのは単一の組織だけではないということです。

## ベンダー中立な3Dファイル形式

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><h3 id="h_93e7e652f9">ベンダー中立な3Dフォーマット</h3></td><td><h3 id="h_03a18fa1a4">拡張機能</h3></td><td><h3 id="h_d177a24399">標準タイプ、ガバナンス</h3></td><td><h3 id="h_2fa4c253b7">コメント</h3></td></tr><tr><td><h3 id="h_b6937afd78">ポイントクラウド文書</h3></td><td><p>e57、las</p></td><td><p>オープン、ASTM、ASPRS</p></td><td><p>ポイントクラウド内のカラーデータを含むポイントの3Dプレビューを表示できます。</p></td></tr><tr><td><h3 id="h_87aca485de">点群の3Dビュー</h3></td><td><p>e57, las</p></td><td><p>Open、ASTM、ASPRS</p></td><td><p>3D ビューアで、他の 3D ファイルと一緒に点群を表示できます。</p></td></tr><tr><td><h3 id="h_1ef242bb5e">GMLドキュメント</h3></td><td><p>gml (CityGML)、city.json (CityJSON)、gmlzip (CityGML zip)</p></td><td><p>Open、IGC</p></td><td><p>CityGML ファイル内のソリッドおよびサーフェスの 3D プレビューを表示できます。</p></td></tr><tr><td><h3 id="h_8ec126c704">GML3D ビュー</h3></td><td><p>gml (CityGML), city.json (CityJSON), gmlzip (CityGML zip)</p></td><td><p>Open、IGC</p></td><td><p>GML ファイルは、3D ビューアで他の 3D ファイルと一緒に表示できます。</p></td></tr><tr><td><h3 id="h_a52b9c3500">IFCドキュメント</h3></td><td><p>ifc (任意)、ifczip (任意)</p></td><td><p>Open、BuildingSMART</p></td><td><p>ドキュメントセクションにアップロードされた IFC ファイルは、IFC 3D ビューのプレビューが表示されます。ドキュメントからモデルが作成された場合、プロパティや GUID などのオブジェクトに関する情報を確認できるため、トピックにリンクさせることができます。</p></td></tr><tr><td><h2 id="h_500f6e5f3a">IFC モデル</h2></td><td><p>ifc, ifczip</p></td><td><p>Open, BuildingSMART</p></td><td><p>以下のバージョンを参照</p></td></tr></tbody></table></div>

以下の表に、当社がサポートするIFCの全バージョンを記載しています。

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p><b>バージョン</b></p></td><td><p>ドキュメント</p></td><td><p>ステータス</p></td><td><p>備考</p></td></tr><tr><td><p><b>IFC 4.3</b></p></td><td><p><a class="intercom-content-link" href="https://github.com/buildingSMART/IFC4.3-html/releases/tag/sep-13-release">IFC 4.3 TC1 (zip)</a>、<a class="intercom-content-link" href="https://standards.buildingsmart.org/IFC/RELEASE/IFC4_3/">IFC 4.3 ADD2</a></p></td><td><p>最新公式バージョン</p></td><td><p>最新の公式バージョン。</p></td></tr><tr><td><p><b>IFC 4.2</b></p></td><td><p><a class="intercom-content-link" href="https://standards.buildingsmart.org/IFC/DEV/IFC4_2/FINAL/HTML/">IFC4.2</a></p></td><td><p>廃止</p></td><td><p>IFC 4.0として処理</p></td></tr><tr><td><p><b>IFC 4.1</b></p></td><td><p><a class="intercom-content-link" href="https://standards.buildingsmart.org/IFC/RELEASE/IFC4_1/FINAL/HTML/">IFC4.1</a></p></td><td><p>取り下げ</p></td><td><p>IFC 4.0 として処理</p></td></tr><tr><td><p><b>IFC 4.0</b></p></td><td><p><a class="intercom-content-link" href="https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/">IFC4 ADD2 TC1</a></p></td><td><p>公式</p></td><td></td></tr><tr><td><p><b>IFC 2.3</b></p></td><td><p><a class="intercom-content-link" href="https://standards.buildingsmart.org/IFC/RELEASE/IFC2x3/FINAL/HTML/">IFC2x3</a>, <a class="intercom-content-link" href="https://standards.buildingsmart.org/IFC/RELEASE/IFC2x3/TC1/HTML/">IFC2x3 TC1</a></p></td><td><p>廃止</p></td><td><p>これは2005年に作成されたIFC 2の最後の公式バージョンです。現在は廃止されていますが、依然として多くの人々に使用されています。</p></td></tr><tr><td><p><b>IFC 2.2</b></p></td><td><p><a class="intercom-content-link" href="https://standards.buildingsmart.org/IFC/RELEASE/IFC2x2/FINAL/HTML/">IFC2x2</a>、<a class="intercom-content-link" href="https://standards.buildingsmart.org/IFC/RELEASE/IFC2x2/ADD1/HTML/">IFC2x2 ADD1</a></p></td><td><p>廃止</p></td><td></td></tr><tr><td><p><b>IFC 2.1</b></p></td><td><p><a class="intercom-content-link" href="https://standards.buildingsmart.org/IFC/RELEASE/IFC2x/FINAL/HTML/">IFC2x</a>、<a class="intercom-content-link" href="https://standards.buildingsmart.org/IFC/RELEASE/IFC2x/ADD1/HTML/">IFC2x ADD1</a></p></td><td><p>廃止</p></td><td></td></tr><tr><td><p><b>IFC 2.0</b></p></td><td><p>IFC2.0</p></td><td><p>廃止</p></td><td></td></tr></tbody></table></div>

### IFCのバージョン

IFCバージョンのステータスに応じて、以下の方法でサポートを提供しています：

_公式、廃止_ - 完全サポート。すべての公式および廃止されたIFCバージョンがサポートされます。

_取り下げ済み_ - 部分的なサポート。モデルは最新の公式バージョンに基づいて処理されます。

_開発中_ - サポートなし。公開前に変更される可能性があります。

公式なIFCリリースについては[、こちら](https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/)をご覧ください

公式のBuildingSMARTサンプルIFCファイル[はこちら](https://github.com/buildingSMART/Sample-Test-Files)

### 点群

点群の点は、色または強度でプレビューできます。

## ベンダー中立の2Dファイル形式

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><h3 id="h_f088d12b78">ベンダーがサポートする2D形式</h3></td><td><h3 id="h_1d9756f3b7">拡張機能</h3></td><td><h3 id="h_bdc9af8cde">標準タイプ、ガバナンス</h3></td><td><h3 id="h_d4e534e9b6">コメント</h3></td></tr><tr><td><h3 id="h_bb0f2e623a">アーカイブ用PDF：PDF/A</h3></td><td><p>.pdf <br/>(PDF/A 1,2,3)</p></td><td><p>PDF Association</p></td><td><p>ベンダー中立なのは PDF/A 形式のみです。</p></td></tr><tr><td><h3 id="h_e4f099375e">ベンダーが支援するPDF</h3></td><td></td><td></td><td></td></tr><tr><td><h3 id="h_1e81a5f6b7">BCFトピック</h3></td><td><p>bcfzip <br/>(bcf 2.0)<br/>bcf <br/>(bcf 2.1, bcf 3.0)</p></td><td><p>Open<br/>BuildingSMART</p></td><td></td></tr><tr><td><h3 id="h_58cd989eb2">画像ドキュメント</h3></td><td><p>png、<br/>gif（静止画像）</p></td><td><p>Open, W3C</p></td><td><p>360 度画像はパノラマとして表示されます。</p></td></tr><tr><td><h3 id="h_628ab890c5">トピックの説明やコメント内の画像</h3></td><td><p>png, <br/>gif (アニメーション), <br/>jpg, jpeg</p></td><td><p>Open<br/>W3C<br/>JPEG Group</p></td><td><p>トピックの<a class="intercom-content-link" href="https://support.catenda.com/ja/articles/8053352-issue-body#h_952e4743da">説明文</a>や<a class="intercom-content-link" href="https://support.catenda.com/ja/articles/8053352-issue-body#h_f76b44d3ca">コメント</a>内のテキストに、公開画像への<a class="intercom-content-link" href="https://support.catenda.com/ja/articles/8430847-formatting-of-posts#h_65e9775fd0">リンクを追加します</a>。<br/>360度画像はパノラマとして表示されます。</p></td></tr><tr><td><h3 id="h_e0eb6be055">トピックの視点にある画像</h3></td><td><p>png、<br/>gif（静止画）、<br/>jpg、jpeg</p></td><td><p>W3C<br/>JPEG<br/>グループを開く</p></td><td><p>トピックのコメントに<a class="intercom-content-link" href="https://support.catenda.com/ja/articles/8053352-issue-body#h_fb43bacd99">画像を添付できます</a>。<br/>360度画像はパノラマとして表示されます。</p></td></tr><tr><td><h3 id="h_d4cf4ca53b">画像ベンダーサポート</h3></td><td></td><td></td><td></td></tr><tr><td><h3 id="h_a03f696bba">OpenOfficeドキュメント</h3></td><td><p>odt, ods</p></td><td><p>Open<br/>OASIS</p></td><td></td></tr><tr><td><h3 id="h_9ac9be8d9f">Officeベンダー対応</h3></td><td></td><td></td><td></td></tr><tr><td><h3 id="h_d51369e720">リッチテキスト文書</h3></td><td><p>XML</p></td><td><p>Open<br/>W3C</p></td><td></td></tr><tr><td><h3 id="h_dda4050762">プレーンテキスト文書</h3></td><td><p>txt</p></td><td><p>W3C<br/>で開く</p></td><td></td></tr></tbody></table></div>

## ベンダー中立のマルチメディアファイル形式

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><h3 id="h_df4a2bf564">ベンダーが支援するマルチメディア形式</h3></td><td><h3 id="h_e8919260c8">拡張子</h3></td><td><h3 id="h_7b016eb385">標準の種類、ガバナンス</h3></td><td><h3 id="h_527bed2c0c">コメント</h3></td></tr><tr><td><h3 id="h_6ac728b57e">Xiphマルチメディアドキュメント</h3></td><td><p>ogg</p></td><td><p>Xiph.Org<br/>を開く</p></td><td><p>ビデオ、オーディオ、その他のマルチメディア</p></td></tr><tr><td><h3 id="h_265bfc961c">マルチメディアベンダーがサポートする</h3></td><td></td><td></td><td></td></tr></tbody></table></div>

## ベンダーが支援するファイル形式

多くの組織によって開発され、広く利用されているファイル形式の標準は数多く存在します。

Catendaを簡単に使えるようにすることは、私たちにとって重要です。そのため、広く使用されている一般的なファイル形式を可能な限りサポートするよう努めています。

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><h3 id="h_9d1dae63fd">ベンダーがサポートする形式</h3></td><td><h3 id="h_96ef4bad49">拡張子</h3></td><td><h3 id="h_3819a0781c">標準タイプ、ガバナンス</h3></td><td><h3 id="h_1c4db2987d">コメント</h3></td></tr><tr><td><h3 id="h_353b8d88e6">PDFベンダー中立</h3></td><td></td><td></td><td></td></tr><tr><td><h2 id="h_f99f16e4e8">PDF ドキュメント</h2></td><td><p>PDF <br/>(1.x～2.0)<br/>xfdf</p></td><td><p>Adobe<br/>を開く</p></td><td><p>PDFをアップロードすると、PDFのコメントが表示されます。PDFポートフォリオの場合は、表紙のみが表示されます。</p></td></tr><tr><td><h3 id="h_d0a7e72a6b">PDF ドキュメント</h3></td><td><p>fdf</p></td><td><p>Adobe<br/>独自の</p></td><td></td></tr><tr><td><h3 id="h_e9cbbf1a4d">画像ベンダー中立</h3></td><td></td><td></td><td></td></tr><tr><td><h3 id="h_92afc0e808">画像ドキュメント</h3></td><td><p>bmp、wmf、emf</p></td><td><p>Microsoft<br/>独自</p></td><td></td></tr><tr><td><h3 id="h_858be27ccd">画像ドキュメント</h3></td><td><p>tif, tiff</p></td><td><p>Adobe<br/>独自形式</p></td><td></td></tr><tr><td><h3 id="h_b2b5a34fd2">トピックの説明やコメント内の画像</h3></td><td><p>bmp</p></td><td><p>Microsoft<br/>独自の形式</p></td><td><p>トピックの<a class="intercom-content-link" href="https://support.catenda.com/ja/articles/8053352-issue-body#h_952e4743da">説明</a>や<a class="intercom-content-link" href="https://support.catenda.com/ja/articles/8053352-issue-body#h_f76b44d3ca">コメント</a>に画像への<a class="intercom-content-link" href="https://support.catenda.com/ja/articles/8430847-formatting-of-posts#h_65e9775fd0">リンクを追加します</a>。<br/>360 度の画像はパノラマとして表示されます。</p></td></tr><tr><td><h3 id="h_b9ef0d3ee7">マルチメディアベンダー中立</h3></td><td></td><td></td><td></td></tr><tr><td><h3 id="h_c95f29d638">Moving Picture Expert Group マルチメディア文書</h3></td><td><p>mp4</p></td><td><p>独自規格<br/>MPEGグループ</p></td><td><p>動画、音声、その他のマルチメディア</p></td></tr><tr><td><h3 id="h_be30009917">Webムービー</h3></td><td><p>webm</p></td><td><p>Google<br/>Open</p></td><td><p>動画、音声、その他のマルチメディア</p></td></tr><tr><td><h3 id="h_c34b264447">建設業界 - ベンダー中立</h3></td><td></td><td></td><td></td></tr><tr><td><h3 id="h_6ede7be0f8">Autodeskドキュメント</h3></td><td><p>dwg, dxf, dwf</p></td><td><p>オートデスク<br/>独自の形式</p></td><td><p>ベクターグラフィックスはCAD形式で表示されます</p></td></tr><tr><td><h3 id="h_d7857a1066">Bentley ドキュメント</h3></td><td><p>dgn</p></td><td><p>Bentley<br/>独自</p></td><td><p>ベクターグラフィックスは CAD 形式で表示されます</p></td></tr><tr><td><h3 id="h_9e01ed9f53">Office ドキュメントベンダー中立</h3></td><td></td><td></td><td></td></tr><tr><td><h3 id="h_537a80bfe8">Microsoft ドキュメント</h3></td><td><p>doc、xls、ppt、pub</p></td><td><p>Microsoft<br/>独自の形式</p></td><td></td></tr><tr><td><h3 id="h_1218a400a9">Microsoft Office Open XML</h3></td><td><p>docx、pptx、xlsx、xlsm</p></td><td><p>Microsoft<br/>オープン</p></td><td><p>xlsm にマクロが含まれている場合、コンテンツをプレビューすることはできません。</p></td></tr><tr><td><h3 id="h_2026341a73">レポートテンプレート</h3></td><td><p>mrt</p></td><td><p>Stimulsoft<br/>独自の</p></td><td><p>テンプレートは XML や JSON などのオープンな技術を使用して保存されていますが、特定のスキーマ、コンポーネント定義、およびスクリプトロジックは Stimulsoft エコシステムに固有のものです。</p></td></tr></tbody></table></div>

## 危険なファイル形式

以下の形式のファイルは、ダブルクリックするだけで開いた際に有害となる可能性があります。 これらのファイルタイプは、単一ドキュメントのアップロードやZIPインポート機能ではアップロードできません。

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><h1 id="h_a12d12c72d">有害な形式</h1></td><td><h1 id="h_4b07086761">拡張子</h1></td><td><h1 id="h_5ce7154479">コメント</h1></td></tr><tr><td><h3 id="h_bd332a1f35">Windows実行ファイル</h3></td><td><p>exe</p></td><td></td></tr><tr><td><h3 id="h_fad7bbd1ca">Windows インストーラーパッケージ</h3></td><td><p>msi</p></td><td></td></tr><tr><td><h3 id="h_967ead787b">バッチスクリプト</h3></td><td><p>bat</p></td><td></td></tr><tr><td><h3 id="h_2d743a6fe1">コマンドスクリプト</h3></td><td><p>cmd</p></td><td></td></tr><tr><td><h3 id="h_72ee4fd225">DOS実行ファイル</h3></td><td><p>com</p></td><td></td></tr><tr><td><h3 id="h_63c0a1e86b">スクリーンセーバー実行ファイル</h3></td><td><p>scr</p></td><td><p>プログラムとして実行すると有害となる可能性があります。</p></td></tr><tr><td><h3 id="h_7143353393">PowerShell スクリプト</h3></td><td><p>ps1</p></td><td><p>スクリプトホストで開くと有害となる可能性があります。</p></td></tr><tr><td><h3 id="h_a9a3166afc">Windows ショートカット</h3></td><td><p>lnk</p></td><td><p>実行ファイルのように見えない状態で実行ファイルにリンクすると、有害となる可能性があります。</p></td></tr><tr><td><h3 id="h_61c6aaa719">Java実行ファイル</h3></td><td><p>jar</p></td><td><p>Javaがインストールされている場合、有害となる可能性があります。</p></td></tr><tr><td><h3 id="h_59547abe10">PHPスクリプト</h3></td><td><p>php</p></td><td></td></tr></tbody></table></div>
