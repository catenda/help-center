# 大きなIFCファイルがあります。Catenda Hubにファイルをアップロードする前にSolibri Optimizerを使用すべきでしょうか？

答えはいいえです。ファイルが大きくなった場合は、代わりに[アップロード前にファイルをzip形式に圧縮](https://support.bimsync.com/hc/en-us/articles/360009995879)することをお勧めします。Solibri Optimizerはいくつかのケースではファイルが破損し、Catenda Hubの様々なインポートステップを通過しなくなる可能性があります。最適化されたファイルは、インポート時のファイルの状態に関係なく、情報を最適化された形式で保存するため、Catenda Hubでの閲覧速度は向上しません。

ファイルのアップロードが失敗する場合は、ファイルヘッダーでSolibri Optimizerの最適化の痕跡を確認してください(テキストエディタなどで開き、ファイルヘッダーの最初の10行を確認してください)。失敗したファイルが最適化されている場合は、代わりに元のファイルで試してください。

![mceclip0.png](https://raw.githubusercontent.com/catenda/help-center/main/images/p8sgh6tt/01-intro.png)

(このファイルはSolibri Optimizerを通して処理されています)
