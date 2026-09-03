# Catenda SharePoint-Anwendung

> **Hinweis:** Die Installationsdatei für das Plugin finden Sie in [diesem Artikel](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Wenn die Catenda SharePoint-Anwendung zu einer SharePoint-Website hinzugefügt wird, können Dateien von SharePoint zu Catenda veröffentlicht werden und die Catenda-Dokumentstruktur kann in SharePoint angezeigt werden. Bei entsprechender Konfiguration kann die Anwendung wie folgt aussehen: <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/inline-628ad1424b68.png" width="300"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/inline-910393724d2c.png" width="300"/> Dieser Artikel enthält Informationen darüber, wie diese Anwendung funktioniert Weitere Informationen darüber, wie diese Anwendung nützlich sein kann, finden Sie [hier](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq). Informationen zum Hinzufügen der SharePoint-Anwendung zu einer Website finden Sie [hier](https://support.catenda.com/en/articles/9453368-adding-and-removing-the-catendasp-app).

## 1. **Veröffentlichung in Catenda mit dem List-Befehl**

Mit dem List-Befehl können Sie eine oder mehrere Dateien in Catenda veröffentlichen.

> **Hinweis:** Es ist nur möglich, Dateien zu veröffentlichen. Ordnerstrukturen können von SharePoint heruntergeladen und über [ZIP-Upload](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) oder [Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) in Catenda hochgeladen werden.

### 1.1 **Suchen des List-Befehls**

**Eine Datei** Wenn Sie eine einzelne Datei in Catenda veröffentlichen möchten, können Sie dies am einfachsten tun, indem Sie im Hamburger-Menü der Datei auf „In Catenda veröffentlichen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/01-finding-the-list-command.png)

**Mehrere Dateien** Wenn Sie mehrere Dateien in Catenda veröffentlichen möchten, müssen Sie die Dateien auswählen, die Sie veröffentlichen möchten. Nachdem Sie Ihre Dateien in SharePoint ausgewählt haben, können Benutzer einen Befehl zum Veröffentlichen in Catenda in der Liste sehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/02-finding-the-list-command.png)

Wenn im Befehlsleisten nicht genügend Platz vorhanden ist, wird möglicherweise der Befehl im Hamburger-Menü angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/03-finding-the-list-command.png)

> **Hinweis:** Dateien können nur aus der Listenansicht veröffentlicht werden, da der List-Befehl in der Rasteransicht nicht verfügbar ist.

### 1.2 **Veröffentlichung der Datei**

Nach dem Klicken auf "In Catenda veröffentlichen" wird das folgende Menü geöffnet, das ungefähr so aussehen kann:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/04-publishing-the-file.png)

Wenn Sie SharePoint keinen Zugriff auf Ihr Catenda-Konto gewährt haben, werden Sie aufgefordert, dies zu autorisieren. [Siehe unten](#h_788fe15988) für Anweisungen zum Autorisieren Ihres Kontos.

**Ordner auswählen** Wenn Sie SharePoint Zugriff auf Ihr Catenda-Konto gewährt haben, können Sie das Projekt, die Bibliothek und den Zielordner in Catenda auswählen und veröffentlichen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/05-publishing-the-file.png)

Die Ansicht der Ordnerstruktur in SharePoint ist konsistent mit der Ansicht in Catenda.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/06-publishing-the-file.png)

Wenn ein Dokument mit demselben Namen wie Ihre Datei noch nicht im Ordner vorhanden ist, in dem Sie veröffentlichen, wird es als neues Dokument in Catenda angezeigt. Wenn die Datei, die Sie veröffentlichen, denselben Namen wie ein Dokument in dem Ordner hat, in den Sie sie veröffentlichen, wird die Datei eine neue Version dieses Dokuments.

> **Hinweis:** Es ist nur möglich, Dokumente zu veröffentlichen, aber keine Entwürfe hochzuladen

Nach der Veröffentlichung einer Datei können Benutzer die Datei verschieben, umbenennen und löschen. _Catenda-Zugriff erforderlich:_ Vollzugriff, normalerweise für Benutzer wie den Verleger oder einen Administrator verfügbar. Das Ändern der Datei in Catenda ändert nichts in SharePoint. Wenn sich die Datei in SharePoint ändert, ändert sich in Catenda nichts.

## 2. **Catenda Webpart**

Mit dieser Anwendung fügen Sie [das Catenda Webpart](https://support.catenda.com/en/articles/10538168-catenda-sharepoint-application-webpart) auf einer Seite Ihrer Website hinzu. Sie können Benutzern ermöglichen, die Bereiche zu durchsuchen, auf die sie im Dokumentabschnitt eines Catenda-Projekts Lesezugriff haben. Wenn sie Schreibzugriff auf einen Teil der Dokumentstruktur haben, können sie auch Dateien dort hochladen.

So kann ein konfiguriertes Webpart aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/07-catenda-webpart.png)

## 3. **Autorisieren Sie Ihr Catenda-Konto**

Wenn Sie zu einer SharePoint-Seite navigieren, auf der das Catenda Webpart aktiviert wurde, oder wenn Sie versuchen, die Veröffentlichungsaktion zu verwenden, und Sie Ihr Konto noch nicht validiert haben, erhalten Sie das folgende Popup:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/08-authorizing-your-catenda-account.png)

_Erforderlicher Zugriff:_ API-Zugriff bei der Installation der Anwendung. Wenn eine neue Browserregisterkarte nicht automatisch geöffnet wird, kopieren Sie bitte den Link aus der offenen Kontovalidierungsregisterkarte und navigieren Sie selbst dorthin. Wenn Sie nicht bereits angemeldet sind, werden Sie aufgefordert, sich in diesem Fenster bei Catenda anzumelden. Wenn Sie noch kein Konto haben, können Sie ein Catenda-Konto [hier](https://hub.catenda.com/signup) erstellen.

> **Hinweis:** Die E-Mail-Adresse, die mit dem Catenda-Konto verbunden ist, bei dem Sie sich anmelden, muss mit der Adresse übereinstimmen, die mit dem SharePoint-Konto verbunden ist, bei dem Sie angemeldet sind.

Das Authentifizierungsfenster kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0z59v4sc/09-authorizing-your-catenda-account.png)

Durch Gewährung des App-Zugriffs auf Ihr Konto können Sie Dokumente von SharePoint zu jedem Teil Ihrer Catenda-Projekte veröffentlichen, auf den Sie Schreibzugriff im [Dokumentabschnitt](https://support.catenda.com/en/articles/8204673-documents-page) haben. Wenn ein Webpart auf einer Seite Ihrer Website hinzugefügt wurde, können Sie auch alle Dokumente sehen, auf die Sie im Catenda-Projekt Lesezugriff haben, das von der Person konfiguriert wurde, die das Webpart hinzugefügt hat. Mit dem Webpart können Sie auch Dokumente von Ihrem System zu jedem Teil des konfigurierten Catenda-Projekts veröffentlichen, auf den Sie Schreibzugriff im [Dokumentabschnitt](https://support.catenda.com/en/articles/8204673-documents-page) haben.

> **Hinweis:** Catenda hat keinen Zugriff auf Ihre SharePoint-Dokumente. Wenn Sie ein Dokument in Catenda veröffentlichen, empfängt es Catenda in einer Einrichtung Transaktion.

Wenn Sie der App keinen Zugriff mehr auf Ihr Catenda-Konto gewähren möchten, können Sie den Zugriff auf der [Anwendungsseite](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) Ihres Catenda-Kontos jederzeit widerrufen.
