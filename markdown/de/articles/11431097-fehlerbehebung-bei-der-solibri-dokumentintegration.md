# Fehlerbehebung bei der Solibri-Dokumentintegration

Fehler, die bei der Solibri-Dokumentintegration auftreten können, und deren Lösungen werden in diesem Artikel erläutert.

## 1. **Kontoverbindung und Zugriff**

### 1.1 **Abmelden während Hochladen/Herunterladen nicht empfohlen**

Es ist möglich, sich im Dokumentauswahlmenü von Ihrem Konto abzumelden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/01-signing-out-during-up-download-not-recommended.png)

Wenn Sie sich hier abmelden und sich erneut anmelden, sieht die Seite folgendermaßen aus:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/02-signing-out-during-up-download-not-recommended.png)

Obwohl Sie auf diese Weise auf ein anderes Catenda-Konto zugreifen können als auf das, dem Sie Zugriff gewährt haben, wird dies nicht empfohlen. Der Zugriff wurde für dieses Konto nicht gewährt und alle Modelle oder Dokumente, zu denen Sie navigieren, werden nicht in Solibri importiert.

### 1.2 **Hochladen -** Kein Zugriff auf Dokument

Wenn Sie versuchen, Ihre SMC auf eine Revision hochzuladen, auf die Sie keinen Zugriff haben, wird die folgende Warnung angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/03-upload-no-access-to-document.png)

In dieser Situation bitten Sie bitte einen Projektadministrator, Ihnen Zugriff auf das Dokument zu gewähren.

### 1.3 **Hochladen -** Kein Zugriff auf Ordner

Wenn Sie versuchen, ein neues Dokument in einem Ordner zu erstellen, auf den Sie nur Lesezugriff haben, wird die folgende Meldung angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/04-upload-no-access-to-folder.png)

In dieser Situation bitten Sie bitte einen Projektadministrator, Ihnen mindestens Schreibzugriff auf den Ordner zu gewähren.

### 1.4 **Zugriff auf Ihr Catenda-Konto widerrufen**

Gehen Sie zur Seite "Anwendungen" Ihrer Catenda Hub-[Kontoeinstellungen](https://intercom.help/bimsync-arena/en/articles/6880968-account-settings#:~:text=your%20notification%20settings.-,Applications,-In%20applications%20you), suchen Sie die Solibri-Anwendung und klicken Sie auf "Widerrufen".

### 1.5 **Vom Catenda-Server trennen**

Wenn Sie sich nicht länger mit dem Catenda-Server verbinden möchten, klicken Sie auf "Trennen".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/05-disconnect-from-the-catenda-server.png)

Nach dem Trennen hat Solibri weiterhin Zugriff auf Ihr Konto. Wenn Sie sich später erneut verbinden möchten, müssen Sie sich nicht erneut authentifizieren.

### 1.6 **Mit neuem Konto verbinden**

In den folgenden Situationen kann es hilfreich sein, sich mit einem neuen Konto zu verbinden:

- Der Zugriff auf Ihr Konto wurde widerrufen.
- Zugriff auf ein anderes Konto gewähren.
- Setzen Sie die Verbindung zurück, wenn sie nicht mehr funktioniert

Das alte Konto kann auf folgende Weise getrennt werden:

### 1.7 **Zugriff auf Catenda widerrufen**

Um den Zugriff zu widerrufen, den Solibri auf ein Konto gewährt bekommen hat, melden Sie sich mit diesem Konto bei Catenda an. Nachdem Sie sich angemeldet haben, gehen Sie zur Seite "Anwendungen" [https://hub.catenda.com/account/apps](https://hub.catenda.com/account/apps). Wenn Solibri Zugriff auf dieses Konto gewährt wurde, wird Solibri in der Liste der Anwendungen mit Zugriff auf das Konto angezeigt. Klicken Sie auf "Zugriff widerrufen". Wenn Solibri mit diesem Konto verbunden war, wird der Benutzer aufgefordert, Zugriff auf ein neues Konto zu gewähren.

### 1.8 **.solibri-Ordner löschen**

Eine andere Möglichkeit, die Verbindung zu einem Catenda-Konto zu entfernen, besteht darin, die Benutzerdaten in Solibri zu löschen. Löschen Sie dazu den Ordner, der sich hier befindet:

`C:\Users\<Username>\.solibri`

> **Hinweis:** Dies ist standardmäßig ein versteckter Ordner auf Ihrem System. Geben Sie den Pfad direkt in Ihrem Datei-Explorer ein oder erfahren Sie hier, wie Sie versteckte Ordner anzeigen: [https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5](https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5)

Die Solibri-Anmeldedaten werden in diesem Ordner gespeichert, daher müssen Sie sich beim nächsten Öffnen von Solibri erneut anmelden.

## 2. **Hochladen**

### 2.1 **Angeforderte Dokument nicht gefunden**

Wenn Sie Ihre .smc von Catenda geöffnet haben, wird der Ort im Projekt, von dem aus Sie sie geöffnet haben, gespeichert. Wenn Sie die .smc später erneut in Catenda hochladen und das Dokument entweder verschoben wurde oder nicht im Projekt existiert, zu dem Sie navigiert haben, wird folgende Meldung angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/06-requested-document-not-found.png)

### 2.2 **Keine neue Revision**

Wenn Sie eine .smc von Catenda geöffnet und diese ohne Änderungen zurück in Catenda hochgeladen haben, werden Sie auch dann nicht aufgefordert, sie zuerst zu speichern, wenn Sie die smc irgendwo gespeichert haben, und es wird so aussehen, als würde sie hochgeladen. Nach dem Hochladen erhalten Sie die folgende Meldung wie erwartet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/07-no-new-revision.png)

Wenn Ihre Datei denselben Namen wie ein Dokument im Ordner hat, werden Sie sehen, dass keine neue Revision zu diesem Dokument in Catenda hinzugefügt wird. Bitte versuchen Sie, Ihre .smc erneut hochzuladen, wenn dies der Fall ist.

### 2.3 **Neues Dokument statt neuer Revision**

Wenn Ihre Datei einen anderen Namen hatte, Sie aber ein Dokument ausgewählt haben, in das die Revision hochgeladen werden soll, wird ein neues Dokument basierend auf Ihrem Dateinamen erstellt, und Ihre Datei wird keine neue Revision des Dokuments. Stellen Sie sicher, dass Ihre Datei denselben Namen wie das Dokument hat, wenn Sie möchten, dass sie eine neue Revision dieses Dokuments und kein neues Dokument wird.

### 2.4 **Schaltfläche nicht verfügbar**

Wenn Sie versuchen, Dokumente hochzuladen, kann die Meldung angezeigt werden, dass keine Dateien ausgewählt sind.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/08-button-not-available.png)

Dies kann der Fall sein, wenn Sie Solibri Zugriff auf Catenda mit einem Konto gewährt haben, aber versuchen, eine .smc-Datei mit einem anderen Konto hochzuladen. Um Zugriff auf ein anderes Konto zu gewähren, siehe [hier](#h_0ef63a37db).

## 3. **Herunterladen**

### 3.1 **Fehler**

Wenn Sie ein Dokument ausgewählt haben, wird möglicherweise im rechten Menü ein Fehler angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/09-error.png)

Dies kann der Fall sein, wenn Sie Solibri Zugriff auf Catenda mit einem Konto gewährt haben, aber versuchen, das Dokument mit einem anderen Konto herunterzuladen. Um Zugriff auf ein anderes Konto zu gewähren, siehe [hier](#h_0ef63a37db).

### 3.2 **Dateityp nicht unterstützt**

Bei der Dokumentintegration wird die folgende Meldung im rechten Informationsmenü angezeigt, nachdem Sie zu einem nicht unterstützten Dokument auf der Dokumentenseite in einem Projekt navigiert und dieses ausgewählt haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/10-filetype-not-supported.png)

Der Versuch, ein Dokument mit einer anderen Erweiterung herunterzuladen, hat keine Auswirkungen.

### 3.3 **Nichts passiert**

Das Konto, mit dem Sie angemeldet sind, unterscheidet sich von dem Konto, für das Sie Zugriff gewährt haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/11-nothing-happens.png)
