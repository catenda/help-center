# Catenda Archicad-Plugin

> Test

> **Hinweis:** Die Installationsdatei für das Plugin finden Sie in [diesem Artikel](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Das Catenda Archicad-Plugin ist ein Plugin, das für Nemetchek Archicad installiert werden kann. Mit diesem Plugin können Sie an 3D-Ansichtspunkten, Themen und Dokumente mit anderen Mitgliedern des Bauprojekts zusammenarbeiten.

## 1. **Installation**

Wenn das Catenda Archicad-Plugin unter Windows installiert wird, erscheinen seine Installationsdateien im folgenden Ordner.

`C:\\Program Files\\Catenda\\Catenda Archicad Connection\\\<Archicad Version>\\Add-On`

Das Plugin wird beim nächsten Öffnen von Archicad als aktiviert im Add-on-Manager angezeigt. Beachten Sie, dass dies sich vom Standard-Add-on-Ordner unterscheidet, der sich unter folgender Adresse befindet

`C:\\Program Files\\Graphisoft\\\<Archicad Version>\\Add-Ons`

### 1.1 **Deinstallation**

Gehen Sie zum Deinstallieren des Plugins zu folgendem Windows-Menü:

`Windows-Einstellungen -> Apps -> Installierte Apps`

Suchen Sie in der Liste nach Catenda Archicad Connection \<version> und klicken Sie auf das Aktionsmenü auf der rechten Seite, um es zu deinstallieren.

## 2. **Catenda Palette**

Nach der Installation des Plugins können Sie ein Catenda-Menü auf der oberen Leiste sehen. In diesem Menü finden Sie das Fenster "Catenda Hub Issue Manager", das die "Catenda Hub Issue Manager Palette" enthält. Um diese Palette nutzen zu können, muss entweder ein Grundriss oder eine 3D-Ansicht geöffnet sein. In der Palette können Sie folgende Aktionen ausführen:

- Navigieren Sie zu Ihrem Catenda Hub-Projekt
- Sehen Sie Probleme und erstellen Sie sie
- Laden Sie Modelle und Revisionen herunter und laden Sie sie hoch

## 3. **Anmelden**

Wenn Sie die Catenda-Palette öffnen, sehen Sie zunächst die Anmeldeseite. Die Anmeldeseite kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/01-sign-in.png)

Wenn Sie kein Catenda-Konto haben, können Sie sich kostenlos oben rechts anmelden. Wenn Sie bereits ein Catenda-Konto haben, können Sie Ihre E-Mail und Ihr Passwort eingeben und auf Anmelden klicken. Nach der Anmeldung werden Sie aufgefordert, Zugriff auf Ihr Catenda-Konto zu gewähren. Nach Gewährung dieses Zugriffs wird das Archicad-Plugin als Anwendung auf der [Seite "Anwendungen"](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) Ihres Catenda-Kontos angezeigt. Hier können Sie den Zugriff jederzeit widerrufen, wenn Sie ihn nicht mehr gewähren möchten.

### 3.1 **Passwort zurücksetzen**

Wenn Sie Ihr Passwort vergessen haben, können Sie auf "Ich habe mein Passwort vergessen" klicken, um es zurückzusetzen. Die Seite zum Zurücksetzen des Passworts kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/02-password-reset.png)

Wenn Sie Ihre E-Mail-Adresse eingeben und auf "Bestätigungs-E-Mail senden" klicken, erhalten Sie eine E-Mail, die Sie durch das Zurücksetzen Ihres Passworts führt. Bitte stellen Sie sicher, dass Sie diese E-Mail innerhalb von 5 Minuten erhalten. Wenn Sie diese nicht in Ihrem Posteingang sehen, können Sie in Ihrem Spam- oder Junk-Ordner nachsehen. Wenn es länger als 5 Minuten dauert, kontaktieren Sie den Support unter [support@catenda.com](mailto:support@catenda.com)

Klicken Sie oben rechts auf Anmelden, um zur Anmeldung zurückzukehren.

## 4. **Projektliste**

Wenn Sie das Archicad-Plugin öffnen, sehen Sie Ihre Projektliste, die etwa so aussehen kann:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/03-project-list.png)

Sobald Sie die Einladung zu einem Projekt angenommen haben, wird Ihr Projekt in der Liste Ihrer Projekte im Plugin und auf der [Seite "Projekte"](https://support.catenda.com/en/articles/8400797-projects-page) angezeigt.

**Aktionsmenü** Klicken Sie auf die drei Punkte neben Ihrem Profilbild, um das Dropdown-Menü "Aktion" zu öffnen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/04-project-list.png)

**Modelle & Revisionen** So kann die Seite "Modelle & Revisionen" aussehen. Hier können Sie alle Modelle einsehen, auf die Sie in Ihrem Catenda-Projekt Zugriff haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/05-project-list.png)

Auf dieser Seite können Sie IFC-Dateien aus Ihrem Catenda-Projekt herunterladen und in Ihr Archicad-Modell importieren. Der Zeitstempel des Modells wird relativ sein. Bewegen Sie den Mauszeiger über den Zeitstempel, um genaue Informationen darüber zu erhalten, wann die Revision veröffentlicht wurde. Klicken Sie auf die Pfeiltaste neben einer der Modellrevisionen, um die IFC-Datei zu importieren, die als Revision hochgeladen wurde. Wenn Sie keinen Zugriff auf Modelle in Ihrem Catenda-Projekt haben, wird Ihnen Folgendes angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/06-project-list.png)

**IFC hochladen** Laden Sie eine IFC aus Ihrem aktuellen Archicad-Projekt hoch. So kann die Seite "IFC hochladen" aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/07-project-list.png)

Standardmäßig ist der Dateiname der Name des Archicad-Projekts. Dies wird der Name der Revision in Catenda. Wählen Sie aus, zu welchem Modell Sie Ihre Datei hochladen möchten. Klicken Sie auf Einstellungen, um das Archicad-IFC-Exportdialogfeld zu öffnen. Hier können Sie konfigurieren, welche Einstellungen Sie zum Exportieren Ihrer IFC nach Catenda verwenden möchten. Wenn Sie bereit sind, klicken Sie auf die Schaltfläche Hochladen, um ein Modell hochzuladen.

**Koordinaten** Bewegen Sie den Mauszeiger über die Option "Koordinaten", um das Menü "Koordinaten" zu erweitern. So kann das Koordinatenmenü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/08-project-list.png)

Im Koordinatenmenü können Koordinaten relativ zu: Vermessungspunkt - Standard Projektursprung gewählt werden

**Version** Die Versionsnummer des Plugins.

**Abmelden** Melden Sie sich von Ihrem Catenda-Konto ab

## 5. **Topic board**

Wenn Sie auf ein Projekt klicken, um es zu öffnen, wird das erste Topic board im Projekt geöffnet. Ein Topic board kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/09-topic-board.png)

### 5.1 **Suche**

Klicken Sie in die Suchleiste, um sie hervorzuheben. So kann die hervorgehobene Suchleiste aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/10-search.png)

Nach dem Klicken in die Suchleiste wird ein Dropdown-Menü mit vorgeschlagenen Filtern geöffnet. Wählen Sie einen der Filter aus, um sie anzuwenden. Klicken Sie auf das X neben dem Filter, um ihn erneut zu entfernen. Beginnen Sie zu tippen, um die vorgeschlagenen Filter einzugrenzen oder führen Sie eine Textsuche durch.

### 5.2 **Filter anzeigen**

Klicken Sie auf die Schaltfläche "Filter anzeigen", um das Filtermenü zu öffnen. So kann das Filtermenü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/11-show-filter.png)

Je nach den konfigurierten Einstellungen im Topic board und den eingereichten Topics können unterschiedliche Filter verfügbar sein:

**Meine Topics** Mir zugewiesen Angefordert von mir Erstellt von mir

**Status** Die verschiedenen Status im Topic board werden hier aufgelistet

**Typ** Die verschiedenen Typen im Topic board werden hier aufgelistet

**Fälligkeit** Überfällig Weniger als ein Tag Weniger als eine Woche Weniger als zwei Wochen Weniger als ein Monat Alles mit einem Fälligkeitsdatum

**Zugewiesen** Die Einträge, die mit einem `@` beginnen, sind zugewiesene Teams, die zuerst aufgelistet werden. Danach werden zugewiesene Projektmitglieder aufgelistet.

**Angefordert von** Die Einträge, die mit einem `@` beginnen, sind Teams, die Topics anfordern, und werden zuerst aufgelistet. Danach werden Projektmitglieder aufgelistet, die Topics anfordern.

**Meilenstein** Alle auf Topics angewendeten Meilensteine werden aufgelistet.

**Etikett** Auf Topics angewendete Etiketten werden hier aufgelistet.

**Filter, die nicht im Filtermenü erwähnt werden** Textsuche Die Textsuche kann durch Eingabe in der Suchleiste erfolgen.

Inhalte, nach denen gesucht werden kann Topic-Titel Topic-Beschreibung Topic-Kommentar

Großschreibung Die Textsuche ist nicht zwischen Groß- und Kleinbuchstaben empfindlich.

Zeichenmenge Einzelnes Zeichen - Keine Ergebnisse. Für eine Textsuche sind mindestens zwei Zeichen erforderlich. Zwei Zeichen - Ganze Wörter, getrennt durch Leerzeichen, die dem Suchbegriff entsprechen, sind in den Ergebnissen enthalten.

### 5.3 **Sortieren**

Klicken Sie auf Sortieren, um das Sortierkonsole zu öffnen. So kann das Sortierkonsole aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/12-sort.png)

Klicken Sie auf eine beliebige Option, um die Topic-Liste zu sortieren nach: _Neueste_ - Standard Topics mit dem neuesten Erstellungsdatum

**Älteste** Topics mit dem ältesten Erstellungsdatum

**Zuletzt aktualisiert** Topics, die zuletzt aktualisiert wurden

**Am längsten nicht aktualisiert** Topics, die am längsten nicht aktualisiert wurden

## 6. **Topic**

Wenn Sie auf ein Topic im Topic board klicken, öffnen Sie es. Ein Topic kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/13-topic.png)
