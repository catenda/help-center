# ハードウェア推奨 - Catenda Site

> Catenda Site モバイルアプリでスマートフォンとタブレット上の3D modelを表示するためのデバイス推奨事項とヒントを確認してください。

[Catenda Site](https://support.catenda.com/ja/articles/6530821-モバイルアプリ-catenda-site-をダウンロード)はスマートフォンとタブレット向けのCatendaモバイルアプリです。その3Dビューアで表示できる内容はデバイスに左右され、この記事ではその詳細を説明しています。

タブレットを含むブラウザでのCatenda Hubの推奨事項については、[ハードウェア推奨](https://support.catenda.com/ja/articles/6921941-ハードウェア推奨仕様)を参照してください。

## 1. **オペレーティングシステム**

Catenda SiteはiPhone、Androidスマートフォンとタブレット、iPad、iPod touch、Apple Visionで利用できます。最新バージョンのオペレーティングシステムを実行している最新のスマートフォンまたはタブレットの使用をお勧めします。オペレーティングシステムとCatenda Siteの両方を最新の状態に保つことをお勧めします。更新によってデバイスが3Dグラフィックスを処理する方法が改善されることが多いためです。

### 1.1 **iOS: iPhoneとiPod touch**

iPhone または iPod touch には、[App Store](https://apps.apple.com/us/app/catenda-site/id1449579790)から Catenda Site をインストールします。Catenda Site には iOS 13.4 以降が必要です。下記の iPad における 3Dビューアの iPadOS 16 および 17 の問題は、iPhone には影響しません。

### 1.2 **Android:スマートフォンとタブレット**

Android のスマートフォンまたはタブレットには、[Google Play](https://play.google.com/store/apps/details?id=no.catenda.bimsyncmobile)から Catenda Site をインストールします。Catenda Site には Android 7.0 以降が必要です。Google Play でお使いのデバイスに Catenda Site が利用できないと表示される場合でも、これはデバイスの制限ではありません。その場合のアプリのインストール方法は、[Catenda Site - トラブルシューティング](https://support.catenda.com/ja/articles/11926914-catenda-site-トラブルシューティング#not-available-for-your-device-in-google-play)に記載されています。

### 1.3 **iPadOS: iPad**

iPad には、[App Store](https://apps.apple.com/us/app/catenda-site/id1449579790)から Catenda Site をインストールします。Catenda Site には iPadOS 13.4 以降が必要です。3Dビューアは iPadOS 15 以前および iPadOS 18 以降で動作します。iPadOS 16 および 17 では、iPadOS の不具合によりアプリで 3D model が表示されないため、これらのバージョンの iPad は、アップデートが利用可能な場合は iPadOS 18 にアップデートしてください。以下の iPad は iPadOS 16 または 17 を超えてアップデートすることができないため、これらのバージョンで動作している場合、Catenda Site の3Dビューアは動作しません：

- iPad(第5および第6世代)
- iPad Pro 9.7インチ
- iPad Pro 10.5インチ
- iPad Pro 12.9インチ(第1および第2世代)

これらのiPadでは、modelをCatenda HubのSafariで引き続き表示できます。iPadがどのmodelであるかを確認するには、Appleウェブサイトの[iPadを特定する](https://support.apple.com/en-us/108043)を参照してください。

### 1.4 **visionOS: Apple Vision**

Apple Vision には、[App Store](https://apps.apple.com/us/app/catenda-site/id1449579790)から Catenda Site をインストールします。Catenda Site には visionOS 1.0 以降が必要です。

## 2. **3Dビューアを最大限に活用する**

スマートフォンまたはタブレットでは、タスクに必要なものだけを表示することが役立ちます:

- プロジェクト内のすべてのmodelではなく、[modelセレクタ](https://support.catenda.com/ja/articles/7744403-3d-ビューア-catenda-site)で必要なmodelのみを有効にします。
- ビューアのパフォーマンス設定で品質より速度を優先します。
- 大きなmodelを開く前に、大量のメモリを使用する他のアプリを閉じます。

大きなmodelで作業するためのさらに多くのヒントについては、[3Dビューアの最適化](https://support.catenda.com/ja/articles/13927321-3dビューア最適化)を参照してください。

## 3. **モバイルデバイス上の3D model**

### 3.1 **グラフィックスメモリ、ストレージではない**

3Dビューアに表示されるmodelはグラフィックスプロセッサのメモリに保持されます。スマートフォンとタブレットではグラフィックスプロセッサがそのメモリをデバイスの残りの部分と共有し、専用グラフィックスカードを搭載したコンピュータよりも少なくなっています。したがって、デバイスが同時に表示できるジオメトリの量は、ストレージ容量ではなく、チップとメモリに依存します。ストレージが多いデバイスでも、より多くのmodelを読み込みません。

### 3.2 **推奨デバイス**

高密度ジオメトリプロジェクト（LOD 400以上）の場合、または多くのmodelを一緒に表示する必要がある場合は、iPad ProまたはiPad AirのようなM系チップを搭載した高性能タブレットを推奨します。
