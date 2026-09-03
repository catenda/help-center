# Catenda Desktop Connector FAQ

## 1. Dateien, die nur online verfügbar sind

Viele Dokumentenverwaltungssysteme ermöglichen es Ihnen, eine Schattenversion Ihrer Dateien auf Ihrem System anzuzeigen, die keinen Platz beansprucht. Sie können oft erkennen, dass ein Dokument nur online verfügbar ist, anhand eines Archiv- oder Cloud-ähnlichen Symbols oder Badges. Hier sind einige Beispiele, wie ein Dokument, das nur online verfügbar ist, in verschiedenen Diensten aussehen kann:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/swkm9e7y/01-online-only-files.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/swkm9e7y/02-online-only-files.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/swkm9e7y/03-online-only-files.png)

Dropbox Google Drive Microsoft 365/SharePoint

Wenn der Desktop Connector versucht, ein solches Dokument hochzuladen, versucht er, darauf zuzugreifen. Wenn Sie den jeweiligen Dienst ausführen, wird dies erkannt und das Dokument wird auf Ihr lokales System heruntergeladen. Stellen Sie daher sicher, dass Sie genügend Speicherplatz auf Ihrem Computer haben, auch beim Hochladen! Der Desktop Connector kann erkennen, ob das Dokument geändert wurde, auch wenn es nur online verfügbar ist, und lädt die Datei nur zum Hochladen zu Catenda herunter, wenn sie geändert wurde. Nach Abschluss der Upload-Aufgabe beanspruchen alle auf Ihr System heruntergeladenen Dateien Speicherplatz. Viele dieser Synchronisierungsdienste geben den Speicherplatz regelmäßig frei, wenn das Dokument einige Zeit lang nicht verwendet wurde. Wenn Sie dies sofort geschehen lassen möchten, können Sie das Dokument oder den Ordner mit Rechtsklick anklicken und über das Kontextmenü wieder in den Status "Nur online verfügbar" ändern.
