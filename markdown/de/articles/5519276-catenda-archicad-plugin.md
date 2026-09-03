# Catenda Archicad Plugin

> **Hinweis:** Die Installationsdatei für das Plugin finden Sie in [diesem Artikel](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Das Catenda Archicad Plugin ist ein Plugin, das für Nemetschek Archicad installiert werden kann. Mit diesem Plugin können Sie mit anderen Mitgliedern des Bauprojekts an 3D-Ansichtspunkten, Themen und Dokumenten zusammenarbeiten.

## 1. **Installation**

Wenn das Catenda Archicad Plugin unter Windows installiert wird, erscheinen die Installationsdateien im folgenden Ordner.

`C:\Program Files\Catenda\Catenda Archicad Connection\<Archicad Version>\Add-On`

Das Plugin wird beim nächsten Öffnen von Archicad im Add-On-Manager als aktiviert angezeigt. Beachten Sie, dass dies sich vom Standard-Add-On-Ordner unterscheidet, der sich unter

`C:\Program Files\Graphisoft\<Archicad Version>\Add-Ons`

### 1.1 **Deinstallation**

Um das Plugin zu deinstallieren, gehen Sie zu folgendem Windows-Menü:

`Windows-Einstellungen -> Apps -> Installierte Apps`

Suchen Sie Catenda Archicad Connection \<version> in der Liste und klicken Sie auf das Aktionsmenü auf der rechten Seite, um die Deinstallation durchzuführen.

## 2. **Catenda-Palette**

Nach der Installation des Plugins sehen Sie ein Catenda-Menü-Tab in der oberen Leiste. In diesem Menü finden Sie das Fenster "Catenda Hub Issue Manager", das die "Catenda Hub Issue Manager Palette" enthält. Um diese Palette zu verwenden, muss entweder ein Grundriss oder eine 3D-Ansicht geöffnet sein. In der Palette können Sie:

- Navigieren Sie zu Ihrem Catenda Hub Projekt
- Probleme anzeigen und erstellen
- Modelle und Revisionen herunterladen und hochladen

## 3. **Anmelden**

Wenn Sie die Catenda-Palette öffnen, sehen Sie zuerst die Anmeldeseite. Die Anmeldeseite kann so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/01-sign-in.png)

Wenn Sie noch kein Catenda-Konto haben, können Sie sich oben rechts kostenlos anmelden. Wenn Sie bereits ein Catenda-Konto haben, können Sie Ihre E-Mail und Ihr Passwort eingeben und auf Anmelden klicken. Nach der Anmeldung werden Sie aufgefordert, Zugriff auf Ihr Catenda-Konto zu gewähren. Nach Gewährung dieses Zugriffs wird das Archicad Plugin auf der [Seite "Anwendungen"](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) Ihres Catenda-Kontos als Anwendung angezeigt. Hier können Sie den Zugriff jederzeit widerrufen, wenn Sie ihn nicht mehr gewähren möchten.

### 3.1 **Passwort zurücksetzen**

Wenn Sie Ihr Passwort vergessen haben, können Sie auf "Ich habe mein Passwort vergessen" klicken, um es zurückzusetzen. Die Seite zum Zurücksetzen des Passworts kann so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/02-password-reset.png)

Wenn Sie Ihre E-Mail-Adresse eingeben und auf "Verifizierungs-E-Mail senden" klicken, erhalten Sie eine E-Mail, die Sie durch das Zurücksetzen Ihres Passworts führt. Stellen Sie sicher, dass Sie diese E-Mail innerhalb von 5 Minuten erhalten haben. Falls Sie sie nicht im Posteingang sehen, können Sie Ihren Spam- oder Junk-Ordner überprüfen. Wenn es länger als 5 Minuten dauert, kontaktieren Sie bitte den Support unter [support@catenda.com](mailto:support@catenda.com)

Um zur Anmeldeseite zurückzukehren, klicken Sie oben rechts auf "Anmelden".

## 4. **Projektliste**

Wenn Sie das Archicad Plugin öffnen, sehen Sie Ihre Projektliste, die so aussehen kann:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/03-project-list.png)

Sobald Sie die Einladung zu einem Projekt akzeptieren, wird Ihr Projekt in der Liste Ihrer Projekte im Plugin und auf der [Projektseite](https://support.catenda.com/en/articles/8400797-projects-page) angezeigt.

**Aktionsmenü** Klicken Sie auf die drei Punkte neben Ihrem Profilbild, um das Dropdown-Menü zu öffnen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/04-project-list.png)

**Modelle und Revisionen** So kann die Seite "Modelle und Revisionen" aussehen. Hier können Sie alle Modelle sehen, auf die Sie in Ihrem Catenda Projekt Zugriff haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/05-project-list.png)

Auf dieser Seite können Sie IFC-Dateien von Ihrem Catenda Projekt zu Ihrem Archicad Modell herunterladen und importieren. Der Zeitstempel des Modells ist relativ. Fahren Sie mit der Maus über den Zeitstempel, um genaue Informationen darüber zu erhalten, wann die Revision veröffentlicht wurde. Klicken Sie auf die Pfeiltaste neben einer der Modellrevisionen, um die IFC-Datei zu importieren, die als Revision hochgeladen wurde. Wenn Sie keinen Zugriff auf Modelle in Ihrem Catenda Projekt haben, wird Folgendes angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/06-project-list.png)

**IFC hochladen** Laden Sie eine IFC aus Ihrem aktuellen Archicad Projekt hoch. So kann die Seite "IFC hochladen" aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/07-project-list.png)

Der Dateiname ist standardmäßig der Name des Archicad Projekts. Dies wird der Name der Revision in Catenda. Wählen Sie das Modell aus, in das Sie Ihre Datei hochladen möchten. Klicken Sie auf "Einstellungen", um den Archicad IFC-Exportdialog zu öffnen. Hier können Sie die Einstellungen konfigurieren, die Sie zum Exportieren Ihrer IFC zu Catenda verwenden möchten. Wenn Sie bereit sind, klicken Sie auf die Schaltfläche "Hochladen", um ein Modell hochzuladen.

**Koordinaten** Fahren Sie mit der Maus über die Koordinatenseite, um das Koordinatenmenü zu erweitern. So kann das Koordinatenmenü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/08-project-list.png)

Im Koordinatenmenü können Koordinaten relativ zu: Vermessungspunkt - Standardprojektorigin gewählt werden

**Version** Die Versionsnummer des Plugins.

**Abmelden** Melden Sie sich von Ihrem Catenda Konto ab

## 5. **Themen-Board**

Wenn Sie auf ein Projekt klicken, um es zu öffnen, wird das erste Themen-Board im Projekt geöffnet. Ein Themen-Board kann so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/09-topic-board.png)

### 5.1 **Suche**

Klicken Sie in die Suchleiste, um sie hervorzuheben. So kann die hervorgehobene Suchleiste aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/10-search.png)

Nach dem Klicken in die Suchleiste wird eine Dropdown-Liste mit vorgeschlagenen Filtern geöffnet. Wählen Sie einen der Filter aus, um ihn anzuwenden. Klicken Sie auf das X neben dem Filter, um ihn wieder zu entfernen. Beginnen Sie zu tippen, um die vorgeschlagenen Filter einzugrenzen oder führen Sie eine Textsuche durch.

### 5.2 **Filter anzeigen**

Klicken Sie auf die Schaltfläche "Filter anzeigen", um das Filtermenü zu öffnen. So kann das Filtermenü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/11-show-filter.png)

Je nach konfigurierter Einstellung im Themen-Board und den eingereichten Themen können unterschiedliche Filter verfügbar sein:

**Meine Themen** Mir zugewiesen Von mir angefordert Von mir erstellt

**Status** Die verschiedenen Status im Themen-Board werden hier aufgelistet

**Typ** Die verschiedenen Typen im Themen-Board werden hier aufgelistet

**Fälligkeit** Überfällig Weniger als einen Tag Weniger als eine Woche Weniger als zwei Wochen Weniger als einen Monat Alle mit Fälligkeitsdatum

**Zugewiesen** Die Einträge, die mit einem `@` beginnen, sind zugewiesene Teams, die zuerst aufgelistet werden. Danach werden zugewiesene Projektmitglieder aufgelistet.

**Angefordert von** Die Einträge, die mit einem `@` beginnen, sind Teams, die Themen anfordern und zuerst aufgelistet werden. Danach werden Projektmitglieder aufgelistet, die Themen anfordern.

**Meilenstein** Alle auf Themen angewendeten Meilensteine werden aufgelistet.

**Etikett** Auf Themen angewendete Etiketten werden hier aufgelistet.

**Filter, die nicht im Filtermenü erwähnt werden** Textsuche Text kann durch Eingabe in der Suchleiste gesucht werden.

Durchsuchbarer Inhalt Themata Themenbeschreibung Themenkommentar

Großschreibung Die Textsuche ist nicht zwischen Groß- und Kleinschreibung empfindlich.

Zeichenanzahl Einzelnes Zeichen - Keine Ergebnisse. Mindestens zwei Zeichen sind für eine Textsuche erforderlich Zwei Zeichen - Ganze Wörter, getrennt durch Leerzeichen, die dem Suchbegriff entsprechen, sind in den Ergebnissen enthalten.

### 5.3 **Sortieren**

Klicken Sie auf "Sortieren", um das Sortiermenü zu öffnen. So kann das Sortiermenü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/12-sort.png)

Klicken Sie auf eine beliebige Option, um die Themenliste nach folgenden Kriterien zu sortieren: _Neueste_ - Standard Themen mit dem neuesten Erstellungsdatum

**Älteste** Themen mit dem ältesten Erstellungsdatum

**Zuletzt aktualisiert** Themen, die zuletzt aktualisiert wurden

**Am längsten nicht aktualisiert** Themen, die am längsten nicht aktualisiert wurden

## 6. **Thema**

Wenn Sie auf ein Thema im Themen-Board klicken, öffnen Sie es. Ein Thema kann so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cxr3wm2a/13-topic.png)
