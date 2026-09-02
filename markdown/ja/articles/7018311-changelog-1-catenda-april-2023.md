# Changelog 1 Catenda - April, 2023

このアーティクルでは、以下のトピックについて説明します。

## 1. アーティクル

**新しい記事:**

[システム要件と最適化](https://intercom.help/bimsync-arena/en/articles/6921941-system-requirements-and-optimization)

[Solibri モデルとドキュメント統合](https://intercom.help/bimsync-arena/en/articles/6988148-solibri-models-and-documents-integration)

[2D オーバーレイ](https://intercom.help/bimsync-arena/en/articles/6921756-2d-overlay)

[アカウント設定](https://intercom.help/bimsync-arena/en/articles/6880968-account-settings)

[列のサイズ変更](https://intercom.help/bimsync-arena/en/articles/6887350-resizing-of-columns) [ドキュメントの IFC サポート](https://intercom.help/bimsync-arena/en/articles/5658031-ifc-support-in-documents) [Catenda Hub の新機能](https://intercom.help/bimsync-arena/en/articles/7150907-what-s-new-in-catenda-hub) [Catenda Site の新機能](https://intercom.help/bimsync-arena/en/articles/7161448-what-s-new-in-catenda-site)

<a class="intercom-content-link" href="" target="_blank">プロジェクト設定</a>
[Issue board のテーブルビュー](https://support.catenda.com/en/articles/6941099-table-view-in-an-issue-board)

[Issue board のリストビュー](https://support.catenda.com/en/articles/6941232-list-view-in-an-issue-board)

**変更された記事:**

[3D ビューア設定](https://intercom.help/bimsync-arena/en/articles/5784718-3d-viewer-settings)

[ドキュメント承認](https://support.catenda.com/en/articles/5784717-document-approval)

[多要素認証](https://support.catenda.com/en/articles/4969891-multi-factor-authentication)

## 2. 解決された問題

**インポートに関する問題:**

- MagiCAD からエクスポートされた欠落エンティティを持つ IFC ファイルをインポートしやすくなりました。
- IfcPerson と IfcOrganization に非 Unicode 文字が含まれている IFC ファイルは、グリッドに失敗を起こさなくなります。

**ビューアに関する問題:**

- モデルは問題なく再度回転できるようになりました。(回転フィールドは短時間の間空白でした)
- オブジェクトを再度削除できるようになりました (モデルは短時間の間に 2 回ロードされていました)
- 公式 IFC4 エクスポーターで Revit からエクスポートされたグリッドが表示されるようになりました
  インスペクト パネルと 3D ビューアを同時に表示するスペースがない画面でインスペクトに移動して、最初に測定された測定値がすぐに表示されるようになりました。
- オブジェクトを再度透明にできるようになりました。(透明化すると、短時間の間、他のオブジェクトが非表示になっていました)
- プロパティなどのパネルは、空の場所をクリックして同じオブジェクトに戻った場合でも、開いたままになります。

**その他の問題:**

- ファイルの移動時にルート フォルダーから再度ナビゲートできるようになりました (ルート フォルダーは短時間の間コンテンツを表示していませんでした)
- ストーリー コンフィギュレーターが、ブランド変更前のプレースメントを持つ図面を再度配置できるようになりました。
