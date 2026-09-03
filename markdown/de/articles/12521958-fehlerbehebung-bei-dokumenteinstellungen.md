# Fehlerbehebung bei Dokumenteinstellungen

In diesem Artikel finden Sie Informationen über die Fehler, die auf der [Seite Dokumenteinstellungen](https://support.catenda.com/en/articles/7831371-document-settings-page) auftreten können.

## 1. **Status-Workflow**

Dies ist ein Beispiel für die Seite Dokumenteinstellungen, wenn Sie versuchen, einen Status mit einem Namen zu erstellen, der bereits vorhanden ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/e0s024gx/01-status-workflow.png)

Aktive Dokumentstatus müssen in jeder Liste eindeutig sein. Wenn Sie beispielsweise einen veröffentlichten Status namens "Status 1" haben, erhalten Sie einen Fehler, wenn Sie versuchen, einen weiteren veröffentlichten Status namens "Status 1" zu erstellen. Es ist möglich, Status mit demselben Namen unterschiedlicher Statustypen zu haben. Es ist beispielsweise möglich, einen veröffentlichten Status namens "Status 1" und gleichzeitig einen freigegebenen Status namens "Status 1" zu haben. Schließlich können Status mit beliebigen Namen archiviert werden. Wenn beispielsweise ein veröffentlichter Status namens "Status 2" archiviert wurde und anschließend ein weiterer veröffentlichter Status namens "Status 2" erstellt und archiviert wurde, würden beide dieser Status archiviert sein. Wenn ein Status wiederhergestellt wird und ein Status mit diesem Namen bereits vorhanden ist, erhält der wiederhergestellte Status "(1) dahinter.
