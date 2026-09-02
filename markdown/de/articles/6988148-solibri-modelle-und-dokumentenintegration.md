# Solibri-Modelle und Dokumentenintegration

Die Dokumenten-API-Integration bietet eine einfache Möglichkeit, auf Ihre in der Cloud gespeicherten Inhalte zuzugreifen. Sie können sich mit einer gemeinsamen Datenumgebung (CDE) verbinden und Modelle vom/zum Server herunterladen und hochladen.

## 1. **Verbindung**

Die Dokumenten-API befindet sich im Integrationsmenü der Registerkarte "Datei" in Solibri. Um mit der Dokumenten-API zu beginnen, müssen Sie Solibri zuerst Zugriff auf Ihr Catenda-Konto gewähren. Klicken Sie dazu auf "Verbinden".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/01-connecting.png)

Die Liste der Server, mit denen Sie sich verbinden können, wird nun geladen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/02-connecting.png)

Beim ersten Start von Solibri kann das Laden dieser Liste einige Zeit dauern. Nach dem ersten Laden wird die Liste gespeichert und öffnet sich schneller. Im resultierenden Dropdown-Menü können Sie Catenda oder Bimsync wählen, um sich mit der Catenda-Dokumenten-API zu verbinden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/03-connecting.png)

## 2. **Dokumente oder Modelle importieren**

Klicken Sie auf "Open", um Dokumente oder Modelle zu importieren, auf die Sie in Catenda Hub Zugriff haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/04-importing-documents-or-models.png)

Nach dem Klicken auf "Open" wird Ihr Standard-Browser geöffnet.

- [Brechen Sie Ihre Browsersitzung ab](#h_e921d649ed), wenn Sie diesen Vorgang abbrechen und weiterhin mit Solibri arbeiten möchten.
- Wenn Sie dies noch nicht getan haben, [gewähren Sie Zugriff auf Ihr Konto](#h_55ca1d4d10).
- Wenn Sie noch kein Projekt ausgewählt haben, wählen Sie ein Projekt auf der [Projektseite](#h_343870704c).
- Nach Auswahl eines Projekts oder wenn Sie bereits ein Projekt ausgewählt haben, können Sie die [Dokumentseite](#h_b7ac757915) (_Standard_) oder die [Modellseite](#h_617a3f8bf6) wählen.

## 3. **Solibri-Sitzung zu Catenda exportieren**

Damit die Schaltfläche "Modell hochladen" verfügbar wird, müssen Sie [Ihr Catenda-Konto verbunden](#h_457cbf4e9d) haben und mindestens eine Datei in Ihrer Solibri-Sitzung vorhanden sein. Klicken Sie auf "Modell hochladen", um Ihre Solibri-Sitzung als Teil Ihres Catenda-Projekts zu exportieren, auf das Sie Zugriff haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/05-exporting-solibri-session-to-catenda.png)

Wenn Sie Ihre Solibri-Sitzung nicht gespeichert haben oder seit dem letzten Speichern Änderungen vorgenommen haben, werden Sie aufgefordert, eine .smc-Datei zu speichern, damit diese hochgeladen werden kann.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/06-exporting-solibri-session-to-catenda.png)

Die gespeicherte .smc-Datei kann nun als neue Revision zu Catenda exportiert und später erneut zu Solibri importiert werden, wenn Sie Ihre Sitzung mit der neuesten Revision fortsetzen möchten. Nachdem Sie Ihre .smc-Datei gespeichert haben, klicken Sie erneut auf "Modell hochladen".

Nach dem Klicken auf "Modell hochladen" wird Ihr Standard-Browser geöffnet.

- [Brechen Sie Ihre Browsersitzung ab](#h_e921d649ed), wenn Sie diesen Vorgang abbrechen und weiterhin mit Solibri arbeiten möchten.
- Wenn Sie dies noch nicht getan haben, [gewähren Sie Zugriff auf Ihr Konto](#h_55ca1d4d10).
- Wenn Sie noch kein Projekt ausgewählt haben, wählen Sie ein Projekt auf der [Projektseite](#h_343870704c).
- Nach Auswahl eines Projekts oder wenn Sie bereits ein Projekt ausgewählt haben, wird Ihnen die [Dokumentseite](#h_b7ac757915) angezeigt.

## 4. **Solibri-Dokumentenintegration -** Projektseite

Nach dem Klicken auf "Open" und der Anmeldung wird, wenn Sie gerade den Zugriff gewährt haben oder vorher bereits den Zugriff gewährt haben, eine ähnliche Seite wie die Projektseite von Catenda Hub als neue Seite in Ihrem Standard-Browser geöffnet. Die Projektseite der Solibri-Dokumentenintegration kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/07-solibri-document-integration-projects-page.png)

> **Hinweis:** Diese Seite wird von Solibri erstellt und unterscheidet sich von der regulären Projektseite im Catenda Hub. Es kann nur zu den Modell- und Dokumentabschnitten von Catenda navigiert werden. Funktionen von Catenda Hub wie Dokumentvorschau und Zugriffskonfiguration funktionieren hier nicht.

## 5. **Solibri-Dokumentenintegration -** Dokumentseite

Sehen Sie die Dokumente, auf die Sie mit Ihrem Catenda-Konto auf der Dokumentseite der Solibri-Dokumentenintegration Zugriff haben. Hier können Sie konfigurieren, welche Dokumente mit Solibri synchronisiert werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/08-solibri-document-integration-documents-page.png)

### 5.1 **Navigation**

Klicken Sie auf den Namen des Projekts, wenn Sie zu einem anderen Projekt navigieren möchten. Klicken Sie auf "Modelle" im linken Menü, um nach Modell statt nach Dokument zu importieren.

> **Hinweis:** Die Modellseite ist nur beim Herunterladen verfügbar.

### 5.2 **Dokumentstruktur**

Für jedes Dokument sehen Sie:

- Dateityp-Symbol
- Dokumentname
- Revisionsnummer
- Dokumentstatus
- Etiketten (klicken Sie auf die 3 Punkte, um weitere Etiketten anzuzeigen)
- Dateigröße
- Creator der neuesten Revision
- Veröffentlichungsdatum der neuesten Revision
- 3D-Schaltfläche (Modell vor dem Importieren in der Vorschau anzeigen)
- Objektlinks (Wählen Sie verlinkte Objekte in der 3D-Vorschau aus, indem Sie auf diese Nummer klicken)

Wählen Sie einen Dokumentenbestand aus, indem Sie die Kästchen ankreuzen, oder kreuzen Sie das Kästchen oben an, um alle auszuwählen.

### 5.3 **Rechtes Informationsmenü**

Nach der Auswahl wird das Informationsmenü oben rechts angezeigt. Wenn es geschlossen ist, klicken Sie auf das Symbol `i`, um es zu erweitern.

### 5.4 ​**Rechtes Informationsmenü -** Download

Beim Importieren können Sie konfigurieren, welche Dokumente zu Solibri importiert werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/09-right-information-menu-download.png)

Klicken Sie unten auf "Download", um die neueste freigegebene Revision jedes ausgewählten Dokuments zu importieren.

### 5.5 **Rechtes Informationsmenü -** Upload

Beim Exportieren können Sie die .smc-Datei konfigurieren, die hochgeladen wird.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/10-right-information-menu-upload.png)

**Dokumentnamen aktualisieren** Wenn diese Option aktiviert ist, wird der Name des ausgewählten Dokuments auf den Namen aktualisiert, den Sie Ihrer Datei gegeben haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/11-right-information-menu-upload.png)

Auf diese Weise können Sie sicherstellen, dass Sie Revisionen weiterhin zu einem Dokument hochladen können, während Sie sicherstellen, dass es immer denselben Namen wie diese Revisionen hat.

**Ähnliche Dokumente automatisch auswählen** Wenn diese Option aktiviert ist, können Sie Ihre Datei zu einem Dokument mit einem ähnlichen Namen hochladen, auch wenn es nicht genau gleich ist. Beachten Sie, dass die hochgeladene Revision immer noch den von Ihnen angegebenen Dateinamen hat.

**Dateiname** Hier sehen Sie den Namen der Datei, die zu Catenda hochgeladen wird.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/12-right-information-menu-upload.png)

Standardmäßig wird der Name der smc-Datei angezeigt, die Sie auf Ihrem System gespeichert haben. Der Name kann immer noch ändert werden. Konfigurieren Sie den Dateinamen, indem Sie auf den Stift auf der rechten Seite klicken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/13-right-information-menu-upload.png)

**Dokument** Hier sehen Sie den Namen des Dokuments auf Catenda, das die Datei erhält.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/14-right-information-menu-upload.png)

Standardmäßig hat es denselben Namen wie der Dateiname. Wenn es noch kein Dokument mit diesem Namen in Ihrem aktuellen Ordner gibt, wird dieses Feld grün angezeigt und zeigt an, dass ein neues Dokument erstellt wird. Der Name, den Ihr Dokument haben wird, kann immer noch geändert werden. Wenn sich andere .smc-Dokumente in diesem Ordner befinden, können Sie auf den Dokumentnamen klicken, um eines der anderen Dokumente auszuwählen, zu dem Sie Ihre .smc-Datei als Revision hochladen möchten. Wenn Sie ein Dokument gewählt haben oder wenn sich ein Dokument in Ihrem aktuellen Ordner mit demselben Namen befindet, wird dieses Feld grau angezeigt. Sie erhalten dann eine Nachricht, die Sie warnt, dass bereits ein Dokument mit diesem Namen vorhanden ist und dass Ihre smc-Datei als neue Revision zu diesem Dokument hochgeladen wird.

**Status** Wenn der Status-Workflow für Ihr Projekt aktiviert wurde, wird die Status-Dropdownliste angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/15-right-information-menu-upload.png)

Wenn Sie ein neues Dokument erstellen oder Ihr Dokument noch keinen Status hat, wird kein Status angezeigt. Wenn Sie eine Revision zu einem vorhandenen Dokument hinzufügen, wird der Status dieses Dokuments angezeigt und Sie können den Dokumentstatus beim Upload ändern. Wenn Sie den Status des Dokuments ändern möchten, wenn Ihre Revision hochgeladen wird, können Sie ihn aus der Liste der verfügbaren Status im Projekt auswählen.

### 5.6 **Empfangene Dokumente**

Wenn der Download erfolgreich gestartet wurde, wird folgende Nachricht im Browser angezeigt

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/16-documents-received.png)

Wenn Sie zu Solibri zurückkehren, sehen Sie, dass die Dokumente verarbeitet werden. Heruntergeladene Dokumente werden in einem temporären Ordner gespeichert, während Ihre Solibri-Sitzung aktiv ist. Denken Sie daran, Ihre Solibri-Sitzung zu speichern oder eine neue Revision auf Catenda hochzuladen, wenn Sie Änderungen an Ihrer Datei speichern möchten. Hochgeladene Dokumentrevisionen werden auf Catenda gespeichert. Die neueste Revision kann später bei Bedarf erneut in Solibri geöffnet werden.

## 6. **Solibri-Dokumentenintegration -** Modellseite

Sehen Sie die Modelle, auf die Sie mit Ihrem Catenda-Konto auf der Modellseite der Solibri-Dokumentenintegration Zugriff haben. Hier können Sie konfigurieren, welche Modelle mit Solibri synchronisiert werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/17-solibri-document-integration-models-page.png)

Klicken Sie auf den Namen des Projekts, wenn Sie zu einem anderen Projekt navigieren möchten. Für jedes Modell sehen Sie das:

- Modellname
- Revisionsnummer
- IFC-Typ
- Erstellungsdatum der neuesten Revision
- Creator der neuesten Revision

Wählen Sie eine Reihe von Modellen aus, indem Sie die Kästchen ankreuzen, oder kreuzen Sie das Kästchen oben an, um alle auszuwählen. Nach der Auswahl wird das Informationsmenü oben rechts angezeigt. Wenn es geschlossen ist, klicken Sie auf das Symbol `i`, um es zu erweitern. Hier können Sie Ihre Auswahl der zu Solibri zu importierenden Modelle bearbeiten. Klicken Sie unten auf "Download", um die neueste freigegebene Revision jedes ausgewählten Modells zu importieren.

## 7. **Browsersitzung abbrechen**

Während Ihre Browsersitzung aktiv ist, wird die folgende Nachricht in Solibri angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/18-cancel-browser-session.png)

Klicken Sie auf "Abbrechen", wenn Sie den Importvorgang beenden möchten.

## 8. **Zugriff auf Ihr Catenda-Konto gewähren**

Wenn Sie nicht bereits bei Catenda angemeldet sind, werden Sie aufgefordert, sich [anzumelden](https://support.catenda.com/en/articles/7891486-sign-in-page). Nach dem ersten Öffnen, nach der Anmeldung oder wenn Sie bereits angemeldet waren, werden Sie aufgefordert, die Berechtigung für den Zugriff auf Ihr Catenda-Konto zu erteilen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/19-granting-access-to-your-catenda-account.png)

Wenn Sie bereits angemeldet waren, aber nicht mit dem richtigen Konto, können Sie auf Ihr Profilbild klicken, um sich abzumelden und sich mit dem richtigen Konto anzumelden. Wenn Sie sicher sind, dass Sie mit dem richtigen Konto angemeldet sind, klicken Sie auf "Zugriff erlauben", um fortzufahren. Wenn Sie zu lange warten, funktioniert dies nicht, also stellen Sie sicher, dass Sie Ihr Passwort bereit haben! Nach erfolgreichem Gewähren des Zugriffs auf Ihr Konto wird die folgende Nachricht angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/20-granting-access-to-your-catenda-account.png)

## 9. **Verlinkte Dokumente verwalten**

Dokumente, die von Catenda in Solibri verlinkt wurden, können sich von regulären Dokumenten unterscheiden, die vom lokalen System geöffnet wurden. Dies ist das Aussehen von Dokumenten, wenn sie mit Dokumenten auf Catenda verlinkt wurden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/21-managing-linked-documents.png)

### 9.1 **Namensspalte**

Der Name des Modells kann einige Zeit zum Aktualisieren benötigen, ändert sich aber schließlich, um die Anzahl der Revisionen im Dokument auf Catenda widerzuspiegeln. Wenn Ihre Organisation eine Voreinstellung für den Download-Namen Ihres Dokuments festgelegt hat, könnten Sie hier einen anderen Namen finden. Zum Beispiel ist es möglich, den Dokumentnamen ohne die Revisionsoption anzufordern. Beachten Sie, dass dies von der Organisation für alle heruntergeladenen Dateien in ihren Projekten angefordert werden muss. Sie können die verschiedenen Download-Namenoptionen für Organisationen [hier](https://support.catenda.com/en/articles/8224886-organization-options) sehen.

### 9.2 **Versionsspalte**

Die Versionsspalte hilft Ihnen, den Überblick darüber zu behalten, welche Revision derzeit geladen ist. Wenn die Versionierung von Revisionen in Ihrem Catenda-Projekt aktiviert wurde, werden hier möglicherweise Groß- (1.0, 2.0, 3.0, usw.) und Nebenversionsnummern (1.1, 1.2, 2.1, usw.) angezeigt.

### 9.3 **Link-Spalte**

Nach dem Importieren eines Modells aus Catenda Hub wird ein Kettenglieder-Symbol in der dritten Spalte angezeigt, um anzuzeigen, dass es verlinkt ist.

### 9.4 **Modell-Hover**

Wenn Sie über ein Dokument fahren, das von Catenda verlinkt wurde, wird `[Dokumenten-API] Catenda` gefolgt vom Namen des Dokuments angezeigt.

### 9.5 **Kontextmenü -** Updates

Klicken Sie mit der rechten Maustaste auf ein Dokument, um das Kontextmenü zu öffnen. Hier können die Dokumentaktualisierungsvoreinstellungen konfiguriert werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/22-context-menu-updates.png)

**Modelle aktualisieren** Dies ist das Aussehen des Dialogfelds "Modelle aktualisieren", wenn Sie mehrere Dokumente ausgewählt haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/23-context-menu-updates.png)

Ordner - Klicken Sie auf den Ordner, wenn Sie stattdessen eine lokale Datei für dieses Modell wählen möchten.

Version - Hier sehen Sie die Versionsnummer in Catenda zusammen mit einem Häkchen, das zeigt, ob Sie derzeit mit der neuesten Revision arbeiten oder nicht. Update - Aktivieren Sie das Kontrollkästchen "Aktualisieren" für jedes Modell oder für alle Modelle, indem Sie das Kontrollkästchen oben aktivieren, und klicken Sie auf "Modelle aktualisieren", um sie zu aktualisieren.

Einstellungen - Klicken Sie auf "Einstellungen", um die Modellaktualisierungseinstellungen für Ihre ausgewählten Dokumente zu öffnen.

Modelle erneut verknüpfen - "Modelle erneut verknüpfen" funktioniert nur, wenn Sie in diesem Dialogfeld lokale Modelle ausgewählt haben und nicht mit Catenda-Modellen.

**Modellaktualisierungseinstellungen**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/24-context-menu-updates.png)

Automatisch - Wenn eine neue Revision in Catenda Hub verfügbar ist, wird das Modell automatisch aktualisiert.

Eingabeaufforderung - Eine Eingabeaufforderung wird angezeigt, wenn eine neue Revision auf Catenda verfügbar ist. Die Aktualisierung auf die neue Revision beginnt bei Ihrem Ermessen.

Modelle erneut verknüpfen - "Modelle erneut verknüpfen" funktioniert nur, wenn Sie in diesem Dialogfeld lokale Modelle ausgewählt haben und nicht mit Catenda-Modellen.

### 9.6 **Kontextmenü -** Hyperlinks

Unten im Dokumentkontextmenü sehen Sie Hyperlinks.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/25-context-menu-hyperlinks.png)

Für jedes ausgewählte Dokument, das einen Link zu Catenda hat, wird beim Öffnen jedes Hyperlinks-Menüs "Catenda" angezeigt. Dies ist das Aussehen des erweiterten Hyperlinks-Menüs:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/26-context-menu-hyperlinks.png)

Neuer Hyperlink - Wenn Sie auf "Neuer Hyperlink" klicken, wird das Menü "Hyperlink hinzufügen" geöffnet, das etwa folgendermaßen aussehen kann:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/27-context-menu-hyperlinks.png)

Anzeigen Klicken Sie auf "Catenda", um das verlinkte Dokument auf Catenda zu öffnen.

Bearbeiten Klicken Sie auf "Catenda", um den Link für das ausgewählte Dokument zu bearbeiten. Das Menü "Hyperlink bearbeiten" wird nun geöffnet und kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/28-context-menu-hyperlinks.png)

Die Adresse sollte etwa so aussehen: [https://hub.catenda.com/project/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx/revisions/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx](https://hub.catenda.com/project/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx/revisions/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)

Das Thema ist standardmäßig "Catenda", kann aber in jeden beliebigen Namen umbenannt werden.

Catenda-Links sind immer absolut, was bedeutet, dass sie nicht relativ zu dem Ort sind, an dem sich Ihre .smc-Datei auf Ihrem System befindet.

Entfernen Klicken Sie auf "Catenda", um den Link für das ausgewählte Dokument zu entfernen.
