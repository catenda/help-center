# Navisworksプラグインのトラブルシューティング

Navisworksプラグインで発生する可能性のあるエラーとその解決方法については、この記事で説明されています。

この記事では、以下のトピックについて説明します。

## 1. **AddTopic**

ログインせずにトピックメニューを開くと、次のエラーが表示されます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/01-addtopic.png)

これを解決するには、設定メニューに移動して、右上のログインをクリックしてください。

## 2. **PopulateIssueBoards**

メンバーが属しているプロジェクトにトピックがない場合、次のエラーが表示されます。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/02-populateissueboards.png)

プロジェクトにトピックが作成されると、エラーは表示されなくなります。

## 3. **プラグインのリセット**

Navisworksを更新した後、Catenda Navisworksプラグインのインストールに問題が発生する可能性があります。プラグインをリセットするには、以下の手順に従ってください。

まずWindowsのフォルダオプションを変更して、隠しファイルとフォルダを表示するようにしてください。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/03-resetting-the-plugin.jpg)

次に、C:\\Users\\_username\\_AppData\\Localフォルダから、Navisworksアプリケーション設定を見つけます。これらはAutodesk\_IncまたはAutodesk\_Ltdフォルダの下にある可能性があります。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/04-resetting-the-plugin.jpg)

Navisworks設定は、"Roamer.exe\_Url…"で始まるフォルダに配置されています。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/05-resetting-the-plugin.jpg)

Roamer.exe\_Url…フォルダをサブフォルダとファイルを含めて削除することで、これらの設定をリセットできます。

プラグインの設定がどのバージョンに属しているかを確認するには：次のレベルはNavisworksのバージョンを示します。例えば、19はNavisworks 2022バージョン、18は2021バージョンなど、以降同様です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/06-resetting-the-plugin.jpg)

そのフォルダの下には、実際の設定ファイル_user.config_があり、テキストエディタで開くことができます。注意してください。Roamer.exe\_Urlレベルからパス全体を削除する方が、テキストエディタを使用して個別のプラグインを削除しようとするよりも安全です。

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/07-resetting-the-plugin.jpg)
