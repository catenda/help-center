# Catenda Navisworks-Plugin

> **Hinweis:** Die Installationsdatei für das Plugin finden Sie in [diesem Artikel](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Das Catenda Navisworks-Plugin ist ein Plugin, das für Nemetchek Archicad installiert werden kann. Mit diesem Plugin können Sie an 3D-Ansichtspunkten, Themen und Dokumenten mit anderen Mitgliedern des Bauprojekts zusammenarbeiten.

## 1. **Über das Plugin**

Das Catenda Hub Add-in für Autodesk® Navisworks® ist das perfekte Tool für Projekte, die in Catenda Hub zusammenarbeiten. Alle Ihre Themen werden in Echtzeit zwischen Navisworks und Catenda Hub synchronisiert, sodass Sie Themen erstellen, aufrufen, freigeben und kommunizieren können. Das Themenformat ist BCF, sodass die Themen über jede BCF-fähige BIM-Software oder -Plattform freigegeben werden können. Dieses Add-in ermöglicht es Ihnen, Themen nahtlos in Navisworks zu visualisieren, zu erstellen und zu bearbeiten. Sie können auch das in Catenda Hub gespeicherte IFC-Modell herunterladen und föderieren.

### 1.1 **Funktionen enthalten:**

- Zugriff auf alle Ihre Catenda-Projekte
- Filtern und Verwalten von Themen über Themen-Boards
- Erstellen Sie neue Themen direkt aus Navis Works
- Finden Sie Themen in Ihrem Navisworks-Modell
- Erstellen Sie für jeden Kommentar eine neue 3D-Ansicht
- Erstellen Sie BCF-Themen aus Konflikten, die mit der Clash Detective gefunden wurden
- Weisen Sie Themen anderen Projektmitgliedern zu
- Ändern Sie den Themenstatus und andere Eigenschaften

## 2. **Cloud-basierte Zusammenarbeit**

Catenda Hub bringt Ihre Konstruktionsdaten in einer Cloud-basierten Zusammenarbeitungsplattform zum Leben, die den gesamten Gebäudelebenszyklus umfasst. Catenda verwaltet Ihre Projektinformationen vom Anfang bis zur Übergabe und darüber hinaus, um die Datenspeicherung und das Wissen über alle Projektphasen hinweg zu gewährleisten.

## 3. **Offene Standards**

Catenda Hub ist ein BIM-Kollaborationstool mit Unterstützung für alle buildingSMART-Standards (IFC, bSDD, BCF). Es verfügt über eine Reihe von APIs für eine einfache Implementierung in Ihre eigene Software.

[YouTube-Video](https://www.youtube.com/embed/osHul8oKysE?rel=0)

## 4. **Installation**

Wenn das Catenda Navisworks-Plugin unter Windows installiert wird, erscheinen seine Installationsdateien im folgenden Ordner.

`C:\ProgramData\Autodesk\ApplicationPlugins\Catenda.BCF.bundle`

Die im Plugin konfigurierten Einstellungen finden Sie hier:

`C:\Users\<Username>\AppData\Local\Autodesk_Inc\Roamer.exe_Url_<GUID>\<Version>`

### 4.1 **Deinstallieren**

Um das Plugin zu deinstallieren, wechseln Sie zum folgenden Windows-Menü:

`Windows-Einstellungen -> Apps -> Installierte Apps`

Finden Sie die Catenda Navisworks BCF-Plugin-Version \<version> in der Liste und klicken Sie auf das Aktionsmenü auf der rechten Seite, um zu deinstallieren.

## 5. **Catenda-Registerkarte**

Nach der Installation des Plugins wird die Catenda-Registerkarte angezeigt. Navisworks muss möglicherweise neu gestartet werden, damit die Registerkarte angezeigt wird. Auf der Startseite von Navisworks wird die Registerkarte zunächst grau angezeigt.

Starten Sie ein neues Projekt oder öffnen Sie ein Navisworks-Projekt, um zu beginnen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/01-catenda-tab.png)

So kann die Catenda-Registerkarte bei Auswahl aussehen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/02-catenda-tab.png)

### 5.1 **Catenda**

Die Catenda-Schaltfläche im Catenda-Plugins-Menü der Catenda-Registerkarte öffnet den Standardbrowser mit der [Anmeldeseite](https://support.catenda.com/en/articles/7891486-sign-in-page) von Catenda Hub.

### 5.2 **BCF-Plugin**

Die BCF-Plugin-Schaltfläche im Catenda-Plugins-Menü der Catenda-Registerkarte öffnet das Catenda Navisworks-Plugin mit aktiviertem Einstellungsmenü. Das Einstellungsmenü des Catenda Navisworks-Plugins kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/03-bcf-plugin.png)

**Plugin andocken** Ziehen Sie die Titelleiste des Fensters an eine beliebige Stelle der Anwendung, um es anzudocken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/04-bcf-plugin.png)

So kann die Anwendung beim Andocken auf der rechten Seite aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/05-bcf-plugin.png)

## 6. **Einstellungen**

So kann das Einstellungsmenü aussehen, nachdem Sie oben links auf "Anmelden" geklickt haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/06-settings.png)

Auf der linken Seite wird die Anmeldeseite von Catenda angezeigt. Folgen Sie den in dem [Artikel zur Anmeldung](https://support.catenda.com/en/articles/7891486-sign-in-page) beschriebenen Schritten, um sich anzumelden.

So kann das Einstellungsmenü nach erfolgreicher Anmeldung aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/07-settings.png)

Wenn die Anmeldesitzung abgelaufen ist, kann die Schaltfläche "Aktualisieren" verwendet werden, um die Anmeldesitzung zu aktualisieren.

### 6.1 **Authentifizieren**

**Token** Hier sehen Sie Ihr Catenda-Authentifizierungstoken nach der Anmeldung.

### 6.2 **IFCGuid**

**Kategorie und Eigenschaft** Kategorie Standard: Element Eigenschaft Standard: IfcGUID

**Eigenschaftszuordnung** Das Catenda Navisworks-Plugin fügt Objekte an Ansichtspunkten in Themen basierend auf der GUID des IfcProject in der IFC an. In Navisworks finden Sie diese GUID in den Eigenschaften des Objekts. Hier ist ein Beispiel mit einem ausgewählten Objekt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/08-ifcguid.png)

Abhängig vom Inhalt Ihrer IFC kann die IfcProject-GUID in einer oder mehreren anderen Eigenschaften oder Kategorien vorhanden sein. Besonders wenn Navisworks mit einer anderen Spracheinstellung als Englisch gestartet wurde, heißt die Element-Kategorie das Wort für Element in dieser Sprache, während das Standardwort noch Englisch im Catenda Navisworks-Plugin ist. Um dies zu beheben, ändern Sie die Kategorie in das Wort für Element in der Sprache, in der Navisworks gestartet wird.

2., 3., 4. Kategorie und Eigenschaft Falls es mehrere Kategorien und Eigenschaften gibt, die die IFCProject-GUID enthalten könnten, können diese auch hinzugefügt werden.

### 6.3 **Pfade**

**DownloadPath** Der Dateispeicherort, in dem Modelle und Dokumente, die über das Plugin heruntergeladen werden, landen.

### 6.4 **Schnappschüsse**

**Platzierung** Rechts - Standard Schnappschüsse werden auf der rechten Seite angezeigt

Unten Schnappschüsse werden unten angezeigt

## 7. **Themen-Boards**

Im Menü "Themen-Boards" kann ein Überblick über die Themen in den Themen-Boards verschiedener Projekte angezeigt werden. So kann das Menü "Themen-Boards" aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/09-topic-boards.png)

Klicken Sie auf die Registerkarte "Projekte", um die Liste der Themen-Boards in diesem Projekt auf der Registerkarte "Themen-Boards" zu laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/10-topic-boards.png)

### 7.1 **Neues Thema**

Klicken Sie auf die Schaltfläche "Neues Thema", um ein neues Thema zu erstellen.

## 8. **Thema**

Im Themenmenü können ausgewählte Themen bearbeitet und neue Themen eingereicht werden. So kann das Themenmenü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/11-topic.png)

### 8.1 **Navigationspfeile**

Verwenden Sie die Navigationspfeile im Menü, um sich zwischen verschiedenen Themen im Themen-Board zu bewegen.

### 8.2 **Neues Thema**

Erstellen Sie ein neues Thema

### 8.3 **Ansichtspunkt hinzufügen**

Fügen Sie einen Ansichtspunkt der aktuellen Kameraposition zum aktuellen Thema hinzu.

### 8.4 **Aktualisieren**

Aktualisieren Sie das Thema auf Catenda mit den Informationen, die im Plugin hinzugefügt wurden.

### 8.5 **Themennummer**

Die Nummer des Themas im Projekt.

### 8.6 **Aktualisieren**

Laden Sie die neuesten Informationen zum Thema von Catenda.

### 8.7 **Schnittebenen löschen**

Klicken Sie auf die Schaltfläche "Schnittebenen löschen", um die Schnittebenen im Viewer zu löschen.

## 9. **Konflikte**

Im Menü "Konflikte" können Themen als Ergebnis von Clash Detective-Erkenntnissen eingereicht werden. So kann das Menü "Konflikte" aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/12-clashes.png)

### 9.1 **Durchführung eines Clash Detective-Tests**

Um mit dem Menü "Konflikte" zu beginnen, suchen Sie die Clash Detective im Menüband:

`Registerkarte "Startseite" -> Menü "Tools" -> Clash Detective`

**Testübersicht** Fügen Sie einen neuen Test hinzu. So kann Ihre Testübersicht aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/13-running-a-clash-detective-test.png)

**Regeln** Wählen Sie Regeln aus oder erstellen Sie neue.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/14-running-a-clash-detective-test.png)

**Auswählen** Wählen Sie Modelle aus, die Sie auf Konflikte überprüfen möchten, und führen Sie den Test aus.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/15-running-a-clash-detective-test.png)

**Ergebnisse** Überprüfen Sie das Ergebnis und benennen Sie Ihre Konflikte.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/16-running-a-clash-detective-test.png)

**Kontextmenü** Klicken Sie mit der rechten Maustaste auf eine Konflikt-Zeile, um das folgende Kontextmenü zu öffnen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/17-running-a-clash-detective-test.png)

Gruppe Gruppieren Sie ähnliche Konflikte zusammen.

Ansichtspunkt Passen Sie den Ansichtspunkt mit "Auf Konflikt fokussieren" an, öffnen Sie dann das Menü "Ansichtspunkt" des Kontextmenüs erneut, um den Ansichtspunkt zum Konflikt zu speichern. Dies ist der Ansichtspunkt, der im Thema auf Catenda angezeigt wird.

Anzeigeeinstellungen Klicken Sie auf der rechten Seite auf "Anzeigeeinstellungen", um die Anzeigeeinstellungen zu öffnen.

Hervorhebung Ändern Sie die Farben der Objekte aus den Modellen, die sich gegenseitig überschneiden.

Isolierung Transparenzeinstellungen

Ansichtspunkte Legen Sie Ansichtspunkte fest, um entweder automatisch zu aktualisieren, automatisch zu laden oder manuell zu laden.

Simulation Simulation anzeigen oder nicht

Im Kontext anzeigen Alle, Datei oder Startseite.

Elemente Hier sehen Sie die Objekte, die mit dem ausgewählten Konflikt verbunden sind.

**Bericht** Dies ist, wie das Berichtsmenü aussehen kann:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/18-running-a-clash-detective-test.png)

Inhalte Wählen Sie den Inhalt Ihres Berichts

Konflikte einbeziehen Wählen Sie aus, welche Konflikte einzubeziehen sind

Ausgabeeinstellungen Wählen Sie entweder den aktuellen Test für den Test, der in der Testübersicht ausgewählt ist, oder alle Tests für alle Tests in der Testübersicht kombiniert oder separat.

Berichtsformat Verwenden Sie die Option "Als Ansichtspunkte" und aktivieren Sie das Kontrollkästchen "Hervorhebung des Ergebnisses beibehalten".

### 9.2 **Konflikte im Catenda-Plugin**

Nachdem ein Konflikt-Test ausgeführt wurde, erscheinen die Ansichtspunkte auf der Registerkarte "Konflikte".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/19-clashes-in-catenda-plugin.png)

### 9.3 **Thema hinzufügen**

Erstellen Sie ein Thema, indem Sie einen oder mehrere Konflikte auswählen. Geben Sie dem Thema einen Titel. Klicken Sie auf "Thema hinzufügen".

**Thema hinzufügen Dropdown** Themen können auf folgende Weise erstellt werden:

Erstellen Sie ein kombiniertes Thema

- Erstellen Sie ein Thema aus den ausgewählten Konflikten
  - Erstellen Sie ein Thema mit einem Ansichtspunkt für jeden Konflikt, der in der Navisworks Clash Detective ausgewählt ist.
- Erstellen Sie ein Thema aus den ausgewählten Konflikten (Konsolidierter Ansichtspunkt)
  - Erstellen Sie ein Thema mit einem einzelnen Ansichtspunkt, der so vergrößert wird, dass alle Konflikte einbezogen werden, die in der Navisworks Clash Detective ausgewählt sind.

Erstellen Sie mehrere Themen

- Erstellen Sie ein Thema für jeden ausgewählten Konflikt
  - Erstellen Sie ein Thema für jeden Konflikt, der im Catenda Navisworks-Plugin ausgewählt ist.
- Erstellen Sie ein Thema für jede Konfliktgruppe
  - Erstellen Sie ein Thema für jede Konfliktgruppe, das im Catenda Navisworks-Plugin ausgewählt ist, mit einem Ansichtspunkt für jeden Konflikt in der Konfliktgruppe.
- Erstellen Sie ein Thema für jede Konfliktgruppe (Konsolidierter Ansichtspunkt)
  - Erstellen Sie ein Thema für jede Konfliktgruppe, das im Catenda Navisworks-Plugin ausgewählt ist, mit einem einzelnen Ansichtspunkt, der so vergrößert wird, dass alle ausgewählten Konflikte einbezogen werden.
- Erstellen Sie ein Thema für jeden nicht gruppierten Konflikt
  - Erstellen Sie ein Thema für jeden nicht gruppierten Konflikt, der im Catenda Navisworks-Plugin ausgewählt ist

### 9.4 **Status ändern**

Ändern Sie den Status der Konflikte, die im Catenda Navisworks-Plugin ausgewählt sind, in einen der folgenden Status in den Navisworks-Testergebnissen.

- Neu
- Aktiv
- Überprüft
- Freigegeben
- Gelöst

## 10. **Modelle**

Laden Sie Modellrevisionen aus dem im Menü "Themen-Boards" ausgewählten Catenda-Projekt herunter, öffnen Sie sie und fügen Sie sie dem Navisworks-Projekt hinzu. So kann das Menü "Modelle" aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/20-models.png)

### 10.1 **Suche**

Durchsuchen Sie die Modelle im Catenda-Projekt

### 10.2 **Aktualisieren**

Aktualisieren Sie die Modelliste aus dem Catenda-Projekt

### 10.3 **Ausgewählte herunterladen**

Laden Sie die ausgewählten Modelle von Catenda auf Ihr lokales System herunter

### 10.4 **Ausgewählte öffnen**

Öffnen Sie die ausgewählten Modelle in einem neuen Navisworks-Projekt

### 10.5 **Ausgewählte anfügen**

Fügen Sie die ausgewählten Modelle zum aktuellen Navisworks-Projekt hinzu. Um ein Modell zum aktuellen Navisworks-Projekt hinzufügen zu können, muss es zunächst heruntergeladen werden.

### 10.6 **Catenda-Dokumentbibliothek**

Öffnen Sie das Fenster "Catenda-Dokumentbibliothek". So kann das Fenster "Dokumentbibliothek" aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/21-catenda-document-library.png)

**Navigationspfeil** Verschieben Sie eine Ebene in der Ordnerstruktur nach oben.

**Aktualisieren** Aktualisieren Sie die Dokumente in der Dokumentbibliothek.

**Herunterladen** Laden Sie die neueste Revision des ausgewählten Catenda-Dokuments auf Ihr lokales System herunter.

**Hochladen** Laden Sie die neueste Revision des ausgewählten Catenda-Dokuments auf Ihr lokales System hoch.

**Spalten** Navigation Doppelklicken Sie auf den Navigationspfeil oder auf eine andere Stelle in der Zeile eines Ordners, um diesen Ordner zu öffnen.

Name Der Name des Ordners oder Dokuments

Dokumentname Der Name des Dokuments

Bild Das Bild des Dokuments

Revision Die Revisionsnummer für das Dokument

### 10.7 **Spalten**

**Auswahlfeld** Das Auswahlfeld des Modells

**Modellsymbol** Das Symbol des Modells

**Name** Der Name des Modells

**Revision Catenda** Die neueste Revisionsnummer im Catenda-Projekt

**Revision Navisworks**

**Herunterladen** Klicken Sie auf das Download-Symbol, um die neueste Modellrevision herunterzuladen. Wenn die Revisionsnummer in der Spalte "Revision Navisworks" angezeigt wird, wird das Modell heruntergeladen.

**Öffnen** Klicken Sie auf das Symbol "Öffnen", um das Modell in einem neuen Navisworks-Projekt zu öffnen.

**Anfügen** Klicken Sie auf das Symbol "Anfügen", um das Modell zum aktuellen Navisworks-Projekt anzufügen.

### 10.8 **Modelle von Catenda Hub herunterladen**

Sie können ganz einfach die IFC-Modelle aus Ihrem Catenda-Projekt mit diesem Plugin und den Aktionen auf der Registerkarte "Modelle" herunterladen. Zum Herunterladen auf Ihr lokales Gerät: Klicken Sie auf die Download-Schaltfläche für jedes Modell, das Sie herunterladen möchten. Die Modelle werden in einem neuen Ordner mit dem Projektnamen unter dem in der Registerkarte "Einstellungen" angegebenen Download-Pfad gespeichert. Beispiel:

`C:\...\Dokumente\Catenda Projektname`

### 10.9 **Erstellen Sie eine zusammengeführte .nwf-Datei mit IFCs aus Catenda Hub**

Um die BCF-Ansichtspunkte aus Ihrem Catenda-Projekt im Catenda-Plugin verwenden zu können, benötigen Sie eine zusammengeführte NavisWorks-Datei mit den IFCs aus Catenda. Laden Sie die IFC-Modelle herunter, die Sie zusammenführen möchten, indem Sie die obigen Schritte befolgen. Öffnen Sie eine der heruntergeladenen Dateien in NavisWorks. Führen Sie weitere Modelle aus demselben Projekt mit "Anfügen" in das NavisWorks-Modell zusammen. Nachdem Sie alle Dateien, die Sie zusammenführen möchten, angefügt haben, speichern Sie die Datei als .nwf-Datei. Speichern Sie die Datei im selben Ordner wie die heruntergeladenen IFC-Dateien. Verwenden Sie diese zusammengeführte Datei, wenn Sie BCF-Ansichtspunkte in Navisworks anzeigen. Sie können diese zusammengeführte Datei auch für die Durchführung von Kollisionstests in NavisWorks verwenden.
