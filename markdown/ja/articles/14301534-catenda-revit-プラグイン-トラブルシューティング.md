# Catenda Revit プラグイン トラブルシューティング

Catenda Revit プラグインで発生する可能性のあるエラーと解決方法をこの記事で説明します。

## 1. **IFC のアップロード**

アップロード モデル ダイアログのファイル名とコメント フィールドでは、アップロード時に ASCII 文字のみがサポートされています。ASCII セットに含まれている文字については、[こちらの Wikipedia の記事](https://en.wikipedia.org/wiki/ASCII)を参照してください。

非 ASCII 文字は、次のようにファイルとコメント フィールドに追加できます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0bx8b1nt/01-upload-ifc.png)

[アップロード] をクリックすると、次のエラー メッセージが表示されます：

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0bx8b1nt/02-upload-ifc.png)

```
アプリケーション内のコンポーネントで予期しない例外が発生しました。[続行] をクリックするとアプリケーションはこのエラーを無視して続行しようとします。リクエスト ヘッダーには ASCII 文字のみを含める必要があります。
```

このエラーが発生した後、アップロードを続行するには Revit を再起動してください。

## 2. **リンク管理ウィンドウ**

Revit 2025 に Catenda Revit プラグインをインストールした後、2026 年 3 月以降に更新された場合、[リンク管理] ウィンドウを開こうとすると Revit がクラッシュします。これは Autodesk の変更が原因です。回避策については、[こちら](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Program-crash-on-certain-machines-when-opening-the-Manage-Links-dialog-in-Revit.html)をクリックしてください。Revit 2025 のみが影響を受けることに注意してください。この問題は Revit 2026 には存在しません。

## 3. **サポート対象の Revit エディション**

Catenda アドインは、Revit API (Application Programming Interface) をサポートする Revit エディションと互換性があります。統合は、次の環境内で可能です：

**標準 Revit**ソフトウェアの多分野対応バージョンを完全にサポートしており、**建築**、**構造**、および **MEP**(機械、電気、配管) ツールセットが含まれています。

**教育版**学生および教育者向けに発行されたライセンスは、サードパーティ アドインのインストールをサポートしており、インストールはソフトウェアのフル バージョンであり、LT バージョンではない場合に限ります。

### 3.1 **非対応エディション: Revit LT**

Revit LT が[サードパーティ アドインまたはプラグイン](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Revit-LT-Is-it-possible-to-use-plugin-or-addins-in-Revit-LT.html)(Catenda Revit アドインを含む) をサポートしていないことに注意することが重要です。これは LT プラットフォームのソフトウェア アーキテクチャの制限であり、必要な API フレームワークが不足しているためです。その結果、Revit LT 環境内でアドインをインストールするか、Dynamo ベースの自動化を使用することはできません。

### 3.2 **バージョン互換性**

最新のソフトウェア アップデートとパフォーマンス向上に合わせるために、統合は定期的に更新されます。Revit アドインと Dynamo パッケージの両方について、現在サポートされている年度版の包括的なリストについては、[プラグインと統合](https://support.catenda.com/en/articles/8396532-catenda-plugins-integrations)の記事を参照してください。

## 4. Catenda Hub Dynamo パッケージ

カスタム自動化が必要なワークフロー向けに、ベース Dynamo 用の特別なパッケージが利用可能です。これは個別のアプリケーションではなく、標準 Dynamo 環境内で使用するノードのコレクションです。

**ライセンス** Dynamo を使用するために追加の Autodesk ライセンスは必要ありません。これは標準 Revit ライセンス内のコア機能として含まれているためです。

**API アクセス**このパッケージを使用するには、Catenda API アクセスが必要です。これはすべてのクライアントに既定で含まれているわけではありませんが、Catenda サポート ポータルを通じてアクセスをリクエストできます。アクセスが付与されると、API アクセスにより組織内のすべてのプロジェクト間でのやり取りが可能になります。

**インストール**パッケージの配置には、Dynamo インターフェース内でファイルの場所を指定することによる手動インストールが必要です。

### 4.1 **Dynamo ユーザー向けの運用上の警告**

このパッケージの使用を開始する前に、これらのツールが個々のユーザーではなく、アプリケーションであるかのようにプロジェクト内でアクションを有効にするという警告が発行されます。大きな機能には大きな責任が伴います。削除などのアプリケーション レベルで実行されるアクションは、標準ユーザー アクションとは異なる方法で処理されます。アプリケーションによって削除された要素またはデータは復元できません。これらのツールをプロジェクト環境内で使用する場合は、細心の注意が必要です。API アクセスまたは Dynamo パッケージをリクエストするには、[support@catenda.com](mailto:support@catenda.com) またはプラットフォームの右上の黒いチャット バブル経由でお問い合わせください。
