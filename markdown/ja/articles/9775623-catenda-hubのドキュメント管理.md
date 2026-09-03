# Catenda HUBのドキュメント管理

Common Data Environment Catenda HUBの重要な部分はドキュメント領域です。この記事では、この領域を構造化する方法と、より良い整理のための個々の機能を使用する方法について説明しています。ドキュメント領域を整理するための3つのアプローチがあります。

1\. [従来のフォルダ構造](#h_62e4c2f0f2)：ドキュメントとファイルが整理された方法で保存される 2\. [メタデータの使用](#h_90254e727f)：ドキュメントとファイルの整理、およびファイルの取得を可能にする 3\. [フォルダ構造とメタデータの組み合わせ](#h_ca9aca4218)

> **注記：** これら2つのバリアントの組み合わせは、多くの場合に有効であり、多くの利点を提供します。

これら2つのバリアントの利点と欠点の比較は次のとおりです：

### **従来のフォルダ構造:**

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e8e8e880; padding: 8px;"><p class="intercom-align-center">利点</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">欠点</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>構造化された設計</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>フォルダ構造を作成および管理する必要があります</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>ドキュメントの検索を支援します</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ドキュメントは個別のフォルダに保存する必要があり、トピック間で整理することはできません</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>フォルダ経由でアクセス設定を作成できます</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr></tbody></table></div>

### **メタデータに基づくドキュメント構造**

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e8e8e880; width: 319px; padding: 8px;"><p class="intercom-align-center">利点</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">欠点</p></td></tr><tr><td style="width: 319px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>自由な構造</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>高度な規律と明確なガイドラインが必要</p></td></tr><tr><td style="width: 319px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ドキュメントの保存と検索は動的です</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ドキュメントは仕様に従って命名され、メタデータを提供する必要があります</p></td></tr></tbody></table></div>

### **両方のバリアントの組み合わせ:**

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e8e8e880; padding: 8px;"><p class="intercom-align-center">利点</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">欠点</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>フォルダ構造に基づいた構造化された整理と、動的なアプローチのための他の可能なメタデータの組み合わせ</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>両方を事前によく調整する必要があります</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>ドキュメントはフォルダ構造と名前+メタデータを介して非常に簡単に割り当てられ、見つけることができます</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr></tbody></table></div>

## 1. **フォルダ構造の例**

フォルダ構造を作成する方法についての良い提案は、[この記事](https://support.catenda.com/en/articles/8542598-structuring-documents)に記載されています。バイエルン州建設局が使用しているフォルダ構造の例は、以下の[リンク](https://hub.catenda.com/share/collections/RK9H1539QrmllSeLAx3H7cQE5rrFvDbEZeFaiudISkqX)に記載されています。フォルダ構造は非常に異なる方法で設定できます。一方、これはプロジェクトの要件と関連するプロジェクトチームに依存し、他方、フォルダ構造は使用される計画キーに依存します。

### 1.1 **例:** フェーズ別の構造の分離

フォルダ構造は、サービスフェーズに基づいて設定されます。これにより、どのドキュメントがどの管理フェーズからどのフォルダに保存されるかが明確に分離されます。しかし、すべてのサービスフェーズに適用されるドキュメントはどうなるのでしょうか?ドキュメントがさまざまなサービスフェーズのフォルダに整理されている場合、例えばこの情報は計画キーではもう必要ないと考えるかもしれません。しかし、計画が印刷されたり、建設現場にデジタルで送信されたりするとどうなるのでしょうか?ここでも、計画名は正確なドキュメントを識別するために使用される必要があります。最良のシナリオでは、フォルダ構造と計画キーは、プロジェクト全体を通じてすべての関係者に対して機能するユニットを形成します。

## 2. **ドキュメント上のメタデータ:**

ドキュメントとファイルのいわゆるメタデータの使用は、近年ますます一般的になっています。一部のドキュメントメタデータはCatenda HUBによって直接生成され、ドキュメントに保存されます。例えば、アップロード日、ドキュメントの作成者、またはファイルサイズは直接表示されます。

自動的に表示されるメタデータに加えて、Catenda HUBでは独自のメタデータを作成することもできます。ユーザー定義属性またはラベルを使用します。

### 2.1 **例:**

ドキュメントが計画キー2-ARC-AN-02-00-second floor plan.pdfでアップロードされます。命名規則はドキュメントに関する情報を自動的に読み取るために使用されます。これは命名規則を認識することにより、バックグラウンドで自動的に行われます。2 = 予備計画 ARC = アーキテクチャ AN = ビュー 02 = 2番目の上層フロア…

> **注記：** この情報に加えて、ドキュメントのステータスを追加できるようになりました。例えば、提出前、承認済み、アーカイブ済み、却下

このドキュメントが建築確認申請またはDGNB認証に重要であるかどうかなど、情報を追加したい場合は、上記のラベルまたはユーザー定義フィールドオプションを使用して追加できます。
