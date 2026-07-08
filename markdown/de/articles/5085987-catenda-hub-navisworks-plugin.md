# Catenda Navisworks-Plugin

> **Hinweis:** Die Installationsdatei für das Plugin finden Sie in [diesem Artikel](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Das Catenda Navisworks-Plugin ist ein Plugin, das für Nemetchek Archicad installiert werden kann. Mit diesem Plugin können Sie mit anderen Mitgliedern des Bauprojekts an 3D-Ansichten, Themen und Dokumenten zusammenarbeiten.

## 1. **Über das Plugin**

Das Catenda Hub Add-in für Autodesk® Navisworks® ist das perfekte Tool für Projekte, die in Catenda Hub zusammenarbeiten. Alle Ihre Themen werden in Echtzeit zwischen Navisworks und Catenda Hub synchronisiert, so dass Sie Themen erstellen, aufrufen, freigeben und kommunizieren können. Das Themenformat ist BCF, so dass die Themen über jede BCF-fähige BIM-Software oder Plattform hinweg freigegeben werden können. Dieses Add-in ermöglicht es Ihnen, Themen nahtlos in Navisworks zu visualisieren, zu erstellen und zu bearbeiten. Sie können auch das in Catenda Hub gespeicherte IFC-Modell auf Ihren lokalen Client herunterladen und zusammenführen.

### 1.1 **Die Funktionen umfassen:**

- Zugriff auf alle Ihre Catenda-Projekte
- Filtern und Verwalten von Themen über Topic Boards
- Erstellen Sie neue Themen direkt von Navis Works aus
- Themen in Ihrem Navisworks-Modell lokalisieren
- Erstellen Sie eine neue 3D-Ansicht für jeden Kommentar
- Erstellen Sie BCF-Themen aus Clashes, die mit dem Clash Detective gefunden wurden
- Weisen Sie Themen anderen Projektmitgliedern zu
- Ändern Sie den Themenstatus und andere Eigenschaften

## 2. **Cloud-basierte Zusammenarbeit**

Catenda Hub bringt Ihre Konstruktionsdaten in einer Cloud-basierten Zusammenarbeitssplattform zum Leben, die den gesamten Lebenszyklus des Gebäudes umfasst. Catenda verwaltet Ihre Projektinformationen vom Beginn bis zur Übergabe und darüber hinaus und stellt die Datenspeicherung und Wissenssicherung über alle Projektphasen hinweg sicher.

## 3. **Offene Standards**

Catenda Hub ist ein BIM-Kollaborationstool mit Unterstützung für alle buildingSMART-Standards (IFC, bSDD, BCF). Es wird mit einer Reihe von APIs für die einfache Implementierung in Ihre eigene Software geliefert.

[YouTube-Video](https://www.youtube.com/embed/osHul8oKysE?rel=0)

## 4. **Installation**

Wenn das Catenda Navisworks-Plugin unter Windows installiert wird, erscheinen die Installationsdateien im folgenden Ordner.

`C:\\ProgramData\\Autodesk\\ApplicationPlugins\\Catenda.BCF.bundle`

Die im Plugin konfigurierten Einstellungen finden Sie hier:

`C:\\Users\\\<Username>\\AppData\\Local\\Autodesk\_Inc\\Roamer.exe\_Url\_\<GUID>\\\<Version>`

### 4.1 **Deinstallation**

Um das Plugin zu deinstallieren, gehen Sie zum folgenden Windows-Menü:

`Windows-Einstellungen -> Apps -> Installierte Apps`

Suchen Sie die Catenda Navisworks BCF Plugin Version \<version> in der Liste und klicken Sie auf das Aktionsmenü auf der rechten Seite, um es zu deinstallieren.

## 5. **Catenda-Registerkarte**

Nach der Installation des Plugins wird die Registerkarte Catenda angezeigt. Navisworks muss möglicherweise neu gestartet werden, damit die Registerkarte angezeigt wird. Auf der Startseite von Navisworks wird die Registerkarte zunächst ausgegraut angezeigt.

Starten Sie ein neues Projekt oder öffnen Sie ein Navisworks-Projekt, um zu beginnen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/01-catenda-tab.png)

So kann die Registerkarte Catenda aussehen, wenn sie ausgewählt ist

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/02-catenda-tab.png)

### 5.1 **Catenda**

Die Catenda-Schaltfläche im Menü "Catenda Plugins" der Registerkarte Catenda öffnet den Standard-Browser mit der [Anmeldeseite](https://support.catenda.com/en/articles/7891486-sign-in-page) von Catenda Hub.

### 5.2 **BCF Plugin**

Die Schaltfläche BCF Plugin im Menü "Catenda Plugins" der Registerkarte Catenda öffnet das Catenda Navisworks-Plugin mit aktiviertem Einstellungsmenü. Das Einstellungsmenü des Catenda Navisworks-Plugins kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/03-bcf-plugin.png)

**Das Plugin andocken** Ziehen Sie die Titelleiste des Fensters an eine beliebige Seite der Anwendung, um es anzudocken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/04-bcf-plugin.png)

So kann die Anwendung aussehen, wenn sie auf der rechten Seite angedockt ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/05-bcf-plugin.png)

## 6. **Einstellungen**

So kann das Einstellungsmenü aussehen, nachdem Sie oben links auf Anmelden geklickt haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/06-settings.png)

Auf der linken Seite wird die Anmeldeseite von Catenda angezeigt. Folgen Sie den Schritten in dem [Anmeldeartikel](https://support.catenda.com/en/articles/7891486-sign-in-page), um sich anzumelden.

So kann das Einstellungsmenü nach erfolgreichem Anmelden aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/07-settings.png)

Wenn die Anmeldesitzung abgelaufen ist, kann die Schaltfläche Aktualisieren verwendet werden, um die Anmeldesitzung zu aktualisieren.

### 6.1 **Authentifizierung**

**Token** Hier sehen Sie Ihren Catenda-Authentifizierungstoken nach der Anmeldung.

### 6.2 **IFCGuid**

**Kategorie und Eigenschaft** Kategorie Standard: Element Eigenschaft Standard: IfcGUID

**Eigenschaftszuordnung** Das Catenda Navisworks-Plugin heftet Objekte an Viewpoints in Topics basierend auf der GUID des IfcProject in der IFC an. In Navisworks ist diese GUID in den Eigenschaften des Objekts zu finden. Hier ist ein Beispiel mit einem ausgewählten Objekt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/08-ifcguid.png)

Je nach Inhalt Ihrer IFC kann die GUID des IfcProject in einer oder mehreren anderen Eigenschaften oder Kategorien gefunden werden. Besonders wenn Navisworks mit einer anderen Spracheinstellung als Englisch gestartet wurde, ist der Name der Element-Kategorie das Wort für Element in dieser Sprache, während das Standardwort im Catenda Navisworks-Plugin noch Englisch ist. Um dieses Problem zu beheben, ändern Sie die Kategorie in das Wort für Element in der Sprache, in der Navisworks gestartet wird.

2., 3., 4. Kategorie und Eigenschaft Wenn es mehrere Kategorien und Eigenschaften gibt, die die IFCProject GUID enthalten könnten, können diese ebenfalls hinzugefügt werden.

### 6.3 **Pfade**

**DownloadPath** Der Dateispeicherort, in dem heruntergeladene Modelle und Dokumente über das Plugin landen.

### 6.4 **Schnappschüsse**

**Platzierung** Rechts - Standard Schnappschüsse werden auf der rechten Seite angezeigt

Unten Schnappschüsse werden unten angezeigt

## 7. **Topic Boards**

Im Menü Topic Boards können Sie eine Übersicht über die Themen in den Topic Boards verschiedener Projekte sehen. So kann das Menü Topic Boards aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/09-topic-boards.png)

Klicken Sie auf die Registerkarte Projekte, um die Liste der Topic Boards in diesem Projekt auf der Registerkarte Topic Boards zu laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/10-topic-boards.png)

### 7.1 **Neues Thema**

Klicken Sie auf die Schaltfläche Neues Thema, um ein neues Thema zu erstellen.

## 8. **Thema**

Im Themenmenü können ausgewählte Themen bearbeitet und neue Themen eingereicht werden. So kann das Themenmenü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/11-topic.png)

### 8.1 **Navigationspfeile**

Verwenden Sie die Navigationspfeile im Menü, um zwischen verschiedenen Themen im Topic Board zu navigieren.

### 8.2 **Neues Thema**

Erstellen Sie ein neues Thema

### 8.3 **Viewpoint hinzufügen**

Fügen Sie einen Viewpoint der aktuellen Kameraposition zum aktuellen Thema hinzu.

### 8.4 **Aktualisieren**

Aktualisieren Sie das Thema auf Catenda mit den Informationen, die im Plugin hinzugefügt wurden.

### 8.5 **Themennummer**

Die Nummer des Themas im Projekt.

### 8.6 **Aktualisieren**

Laden Sie die neuesten Informationen zum Thema von Catenda.

### 8.7 **Schnittebenen löschen**

Klicken Sie auf die Schaltfläche Schnittebenen löschen, um die Schnittebenen im Viewer zu löschen.

## 9. **Clashes**

Im Clashes-Menü können Themen als Ergebnis von Clash Detective-Ergebnissen eingereicht werden. So kann das Clashes-Menü aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/12-clashes.png)

### 9.1 **Durchführen eines Clash Detective-Tests**

Suchen Sie zuerst im Clash-Menü den Clash Detective im Menüband:

`Startregisterkarte -> Tools-Menü -> Clash Detective`

**Testübersicht** Fügen Sie einen neuen Test hinzu. So kann Ihre Testübersicht aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/13-running-a-clash-detective-test.png)

**Regeln** Wählen Sie Regeln oder erstellen Sie neue.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/14-running-a-clash-detective-test.png)

**Auswählen** Wählen Sie Modelle aus, die Sie gegenseitig auf Clashes überprüfen möchten, und führen Sie den Test aus.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/15-running-a-clash-detective-test.png)

**Ergebnisse** Gehen Sie durch die Ergebnisse und benennen Sie Ihre Clashes.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/16-running-a-clash-detective-test.png)

**Kontextmenü** Klicken Sie mit der rechten Maustaste auf eine Clash-Zeile, um das folgende Kontextmenü zu öffnen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/17-running-a-clash-detective-test.png)

Gruppe Fassen Sie ähnliche Clashes zusammen.

Viewpoint Passen Sie den Viewpoint mit "Focus on Clash" an und öffnen Sie das Viewpoint-Menü im Kontextmenü erneut, um den Viewpoint im Clash zu speichern. Dies ist der Viewpoint, der im Thema auf Catenda landet.

Anzeigeeinstellungen Klicken Sie auf der rechten Seite auf Anzeigeeinstellungen, um die Anzeigeeinstellungen zu öffnen.

Hervorhebung Ändern Sie die Farben der Objekte aus einem der Modelle, die gegenseitig kollidieren.

Isolation Transparenzeinstellungen

Viewpoints Stellen Sie Viewpoints auf automatische Aktualisierung, automatisches Laden oder manuelles Laden ein.

Simulation Simulation anzeigen oder nicht

Im Kontext anzeigen Alles, Datei oder Startseite.

Elemente Hier sehen Sie die Objekte, die mit dem ausgewählten Clash verknüpft sind.

**Bericht** so kann das Berichtsmenü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/18-running-a-clash-detective-test.png)

Inhalt Wählen Sie den Inhalt Ihres Berichts aus

Clashes einschließen Wählen Sie aus, welche Clashes einzubeziehen sind

Ausgabeeinstellungen Wählen Sie entweder den aktuellen Test für den im Testübersicht ausgewählten Test oder alle Tests für alle Tests im Testübersicht kombiniert oder separat.

Berichtformat Verwenden Sie die Option als Viewpoints und aktivieren Sie das Kontrollkästchen Ergebnishervorhebung beibehalten.

### 9.2 **Clashes im Catenda-Plugin**

Nach Durchführung eines Clash-Tests erscheinen die Viewpoints auf der Registerkarte Clashes.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/19-clashes-in-catenda-plugin.png)

### 9.3 **Thema hinzufügen**

Erstellen Sie ein Thema, indem Sie einen oder mehrere Clashes auswählen Geben Sie dem Thema einen Titel Klicken Sie auf Thema hinzufügen.

**Thema-Dropdown hinzufügen** Themen können auf folgende Weise erstellt werden:

Ein kombiniertes Thema erstellen

- Ein Thema aus den ausgewählten Clashes erstellen
  - Erstellen Sie ein Thema mit einem Viewpoint für jeden Clash, der im Navisworks Clash Detective ausgewählt ist.
- Erstellen Sie ein Thema aus den ausgewählten Clashes (Konsolidierter Viewpoint)
  - Erstellen Sie ein Thema mit einem einzelnen Viewpoint, der herausgezoomt ist, um alle im Navisworks Clash Detective ausgewählten Clashes einzubeziehen.

Mehrere Themen erstellen

- Erstellen Sie ein Thema für jeden ausgewählten Clash
  - Erstellen Sie ein Thema für jeden Clash, der im Catenda Navisworks-Plugin ausgewählt ist.
- Erstellen Sie ein Thema für jede Clash-Gruppe
  - Erstellen Sie ein Thema für jede Clash-Gruppe, das im Catenda Navisworks-Plugin ausgewählt ist, mit einem Viewpoint für jeden Clash in der Clash-Gruppe.
- Erstellen Sie ein Thema für jede Clash-Gruppe (Konsolidierter Viewpoint)
  - Erstellen Sie ein Thema für jede Clash-Gruppe, das im Catenda Navisworks-Plugin ausgewählt ist, mit einem einzelnen Viewpoint, der herausgezoomt ist, um alle ausgewählten Clashes einzubeziehen.
- Erstellen Sie ein Thema für jeden nicht gruppierten Clash
  - Erstellen Sie ein Thema für jeden nicht gruppierten Clash, das im Catenda Navisworks-Plugin ausgewählt ist

### 9.4 **Status ändern**

Ändern Sie den Status der im Catenda Navisworks-Plugin ausgewählten Clashes auf einen der folgenden Status in den Navisworks-Testergebnissen.

- Neu
- Aktiv
- Überprüft
- Genehmigt
- Gelöst

## 10. **Modelle**

Laden Sie Modellrevisionen aus dem im Menü Topic Boards ausgewählten Catenda-Projekt herunter, öffnen Sie diese und hängen Sie diese an das Navisworks-Projekt an. So kann das Menü Modelle aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/20-models.png)

### 10.1 **Suche**

Durchsuchen Sie die Modelle im Catenda-Projekt

### 10.2 **Aktualisieren**

Aktualisieren Sie die Modelliste aus dem Catenda-Projekt

### 10.3 **Ausgewählte herunterladen**

Laden Sie das ausgewählte Modell (die ausgewählten Modelle) von Catenda auf Ihr lokales System herunter

### 10.4 **Ausgewählte öffnen**

Öffnen Sie das ausgewählte Modell (die ausgewählten Modelle) in einem neuen Navisworks-Projekt

### 10.5 **Ausgewählte anhängen**

Hängen Sie das ausgewählte Modell (die ausgewählten Modelle) an das aktuelle Navisworks-Projekt an. Um ein Modell an das aktuelle Navisworks-Projekt anhängen zu können, muss es zuerst heruntergeladen werden.

### 10.6 **Catenda-Dokumentbibliothek**

Öffnen Sie das Fenster Catenda-Dokumentbibliothek. So kann das Fenster Dokumentbibliothek aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/21-catenda-document-library.png)

**Navigationspfeil** Gehen Sie eine Ebene in der Ordnerstruktur nach oben.

**Aktualisieren** Aktualisieren Sie die Dokumente in der Dokumentbibliothek.

**Herunterladen** Laden Sie die neueste Version des ausgewählten Catenda-Dokuments auf Ihr lokales System herunter.

**Hochladen** Laden Sie die neueste Version des ausgewählten Catenda-Dokuments auf Ihr lokales System hoch.

**Spalten** Navigation Doppelklicken Sie auf den Navigationspfeil oder an einer beliebigen Stelle in der Zeile eines Ordners, um diesen Ordner zu öffnen.

Name Der Name des Ordners oder Dokuments

Dokumentname Der Name des Dokuments

Bild Das Bild des Dokuments

Revision Die Versionsnummer für das Dokument

### 10.7 **Spalten**

**Auswahlfeld** Das Auswahlfeld des Modells

**Modellsymbol** Das Symbol des Modells

**Name** Der Name des Modells

**Revision Catenda** Die neueste Versionsnummer im Catenda-Projekt

**Revision Navisworks**

**Herunterladen** Klicken Sie auf das Download-Symbol, um die neueste Modellversion herunterzuladen. Wenn die Versionsnummer in der Spalte Revision Navisworks erscheint, wird das Modell heruntergeladen.

**Öffnen** Klicken Sie auf das Symbol Öffnen, um das Modell in einem neuen Navisworks-Projekt zu öffnen.

**Anhängen** Klicken Sie auf das Symbol Anhängen, um das Modell an das aktuelle Navisworks-Projekt anzuhängen.

### 10.8 **Modelle von Catenda Hub herunterladen**

Sie können ganz einfach IFC-Modelle aus Ihrem Catenda-Projekt mit diesem Plugin und den Aktionen auf der Registerkarte Modelle herunterladen. Um auf Ihr lokales Gerät herunterzuladen: Klicken Sie die Download-Schaltfläche für jedes Modell, das Sie herunterladen möchten. Die Modelle werden in einem neuen Ordner mit dem Projektnamen unter dem in der Registerkarte Einstellungen angegebenen Download-Pfad gespeichert. Zum Beispiel:

`C:\\...\\Dokumente\\Catenda Projektname`

### 10.9 **Erstellen Sie eine zusammengeführte .nwf-Datei mit IFCs von Catenda Hub**

Um die BCF-Viewpoints aus Ihrem Catenda-Projekt im Catenda-Plugin verwenden zu können, benötigen Sie eine zusammengeführte NavisWorks-Datei mit den IFCs von Catenda. Laden Sie die IFC-Modelle herunter, die Sie zusammenführen möchten, indem Sie die obigen Schritte ausführen. Öffnen Sie eine der heruntergeladenen Dateien in NavisWorks. Führen Sie weitere Modelle aus demselben Projekt in das NavisWorks-Modell mit "Anhängen" ein. Speichern Sie die Datei, nachdem Sie alle Dateien, die Sie zusammenführen möchten, angehängt haben, als .nwf-Datei. Speichern Sie die Datei im selben Ordner wie Ihre heruntergeladenen IFC-Dateien. Verwenden Sie diese zusammengeführte Datei, wenn Sie BCF-Viewpoints in Navisworks anzeigen. Sie können diese zusammengeführte Datei auch verwenden, um Kollisionstests in NavisWorks durchzuführen.
