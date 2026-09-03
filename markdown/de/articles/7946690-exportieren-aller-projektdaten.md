# Exportieren aller Projektdaten

> Überblick über Exportmethoden für Projektdaten, Dokumente, Modelle und Topics in Catenda Hub. Optionen: Desktop Connector-Synchronisierung, PDF/A-Berichte, Prüfung von Zugriffsberechtigungen und automatische Cloud-Backups zu AWS S3 oder Azure Blob.

Catenda Hub bietet flexible Exportmethoden, die auf verschiedene Projektanforderungen zugeschnitten sind, von alltäglichen Downloads bis zur automatisierten Enterprise-Archivierung. Je nach spezifischen Projektanforderungen ist es möglich, große Ordnerstrukturen mithilfe von Desktop Connector zu synchronisieren, benutzerdefinierte Dokumentlieferlisten und PDF/A-Archive über die Reports Page zu erstellen oder Projektaccessberechtigungen für Audit-Trails zu dokumentieren. Für Organisationen, die kontinuierliche Cloud-zu-Cloud-Backups benötigen, bietet Catenda Data Export automatisierte Übertragungen direkt zu AWS S3 oder Azure Blob Storage.

## 1. **Warum exportieren**

Projekteigentümer und Projektbeteiligte müssen häufig lokale Kopien der Projektdokumentation während und nach dem Lebenszyklus eines Projekts aufbewahren.

### 1.1 **Dateneingabe und Phasenwechsel**

Projektdaten können an verschiedenen Projektmeilensteinen benötigt werden:

**Phasenwechsel** Der Übergang zwischen Planung, Design und Konstruktion erfordert häufig die Extraktion von Daten-Snapshots, besonders wenn Projekte unterbrochen oder an neue Parteien übergeben werden.

**Behördliche Anfragen** Formale Eingaben an Behörden werden häufig während oder nach Abschluss eines Projekts verlangt.

**Ausschreibung** Vorbereitung von Dokumenteinreichungspaketen für Ausschreibungen.

### 1.2 **Unabhängige Datenspeicherung & Zugriffsschutz**

Das Exportieren ist nicht auf den Projektabschluss beschränkt. Projektmitglieder, die nicht die primären Projektdaten besitzen, benötigen häufig ihre eigenen Kopien, um einen kontinuierlichen Zugriff auf ihre Arbeit zu gewährleisten.

Projektmitglieder werden nicht immer im Voraus darüber informiert, wann der Projektaccessverlust endet, und der Zugriff kann manchmal früher als erwartet widerrufen werden. Da der Zugriff ohne Warnung verloren gehen kann, ist die Konfiguration von **geplanten, wiederholten Exporten**, z. B. mit **Catenda Data Export** oder dem **Catenda Desktop Connector**, entscheidend. Diese wiederkehrenden Tools stellen sicher, dass Projektmitglieder eine lokale oder Cloud-Sicherung bis zur letzten geplanten Ausführung vor Zugriffsverlust beibehalten.

### 1.3 **Datenarchivierung und Compliance**

Vorschriften und Industriestandards schreiben häufig vor, dass verantwortliche Parteien Projektunterlagen über lange Zeiträume speichern, oft über Jahre oder Jahrzehnte hinweg. Systemdokumentation, Produktunterlagen und Compliance-Dateien müssen möglicherweise auf Unternehmensservern oder designierten Repositorys gespeichert werden.

### 1.4 **Projektbeendigung**

Wenn ein aktives Projekt abgeschlossen wird oder ein Lizenzzeitraum endet, stellt Catenda sicher, dass Projektdaten sicher gespeichert bleiben. Selbst wenn der Projektaccess endet, bleiben Daten auf Catenda-Servern bis zu drei Jahre lang wiederherstellbar.

### 1.5 **Option gefrorenes Archiv**

Eine Archivierungsoption ermöglicht es Projekten, als gefrorene, schreibgeschützte Repositorys für ausgewählte Mitglieder zugänglich zu bleiben.

## 2. **Standardexportoptionen**

Diese integrierten Exporttools stehen direkt innerhalb der Standardoberfläche für alle autorisierten Projektbeteiligten zur Verfügung.

### 2.1 **Modelle exportieren**

Da jedes Modell in Catenda mit einem Dokument im Dokumentenbereich verknüpft ist, gelten die Standard-Dokumentexportfunktionen auch für Modelle. Darüber hinaus stehen dedizierte Exportoptionen speziell für Modelle zur Verfügung:

**Download ausgewählter Modelle** Wählen Sie ein oder mehrere Modelle auf der [Modellseite](https://support.catenda.com/en/articles/4670286-models-page) aus und verwenden Sie die Download-Aktion, um ihre neuesten Überarbeitungen zu extrahieren.

**Download einzelner Überarbeitungen** Wählen Sie ein Modell auf der [Modellseite](https://support.catenda.com/en/articles/4670286-models-page) aus und verwenden Sie die Download-Schaltfläche neben jeder Überarbeitung im rechten Informationsbereich. Dies bietet eine effiziente Möglichkeit, bestimmte Überarbeitungen direkt herunterzuladen, ohne die vollständige [Modellinhaltseite](https://support.catenda.com/en/articles/4670270-model-contents-page) laden zu müssen. Alternativ können einzelne Überarbeitungen auch direkt von der Inhaltsseite eines Modells heruntergeladen werden.

**Erweiterter Modellexport** Greifen Sie auf die [Modellexportseite](https://support.catenda.com/en/articles/4670280-model-export-page) zu, um ausgewählte Überarbeitungen über mehrere Modelle hinweg in einer einzigen herunterladbaren ZIP-Datei zu packen. Diese Methode beinhaltet erweiterte Optionen zur Verbesserung der exportierten Modelldateien durch Einbindung von Tags, benutzerdefinierten Eigenschaften oder Bibliotheksinformationen.

### 2.2 **Themen exportieren (3 Wege)**

Themendaten können über [Exchange Topics](https://support.catenda.com/en/articles/4670289-exchange-topics) in drei Primärformaten extrahiert werden, je nachdem wie die Informationen angezeigt, analysiert oder gespeichert werden:

**BCF (BIM Collaboration Format)** Ein offener Standard, der zur Erfassung und Übertragung von Themeninformationen entwickelt wurde und sich streng an die offizielle BCF-Spezifikation hält, einschließlich einzelner Themenerstellungs-Zeitstempel. Dieses Format garantiert eine breite plattformübergreifende Interoperabilität und eignet sich ideal für die nahtlose Wiederöffnung, Bearbeitung oder Verwendung von Themendaten mit anderer BCF-kompatibler Software. Für allgemeine langfristige Dokumentrepositories, bei denen direkte Dateivorschauen erforderlich sind, werden in der Regel PDF- oder Excel-Formate bevorzugt.

**Excel** Exportiert Themenparameter in ein Tabellenformat für Filterung, Sortierung und Datenmanipulation. Dieses Format bietet strukturierte Zeilen und Spalten, die sich ideal für die Auswahl und das Kopieren von Daten eignen, und Excel-Dateien können in den meisten Archivierungsplattformen leicht vorhergesehen werden. Für Archivierungszwecke wird der PDF-Export in der Regel dem Excel-Export vorgezogen, da er mehr Informationen enthält.

**PDF** Generiert einen sauberen, lesbaren Zusammenfassungsbericht im PDF-Standardformat (v1.4), das ohne spezialisierte Software zugänglich ist (siehe [Exporting topics to PDF](https://support.catenda.com/en/articles/9784934-exporting-topics-to-pdf)). Standard-PDF-Exporte enthalten einen konsolidierten Download-Zeitstempel für formelle Behördenmeldungen und Archivierung und bieten mehr Informationen als ein Excel-Export. Während der Basis-Export eine Standard-PDF-Datei (v1.4) erzeugt, die viele Archivierungssysteme beim Upload automatisch in PDF/A konvertieren, ist der direkte Export in native PDF/A-1-, PDF/A-2- und PDF/A-3-Formate auch über die Opt-in [Reports Page](https://support.catenda.com/en/articles/12303098-reports-page) verfügbar.

### 2.3 **Dokumente und Sammlungen exportieren**

**Batch- & Ordner-Downloads** Wählen Sie einzelne Ordner, spezifische Dokumentengruppen oder alle sichtbaren Tabellenelemente auf einmal aus, um ein herunterladbares ZIP-Archiv zu generieren. Das Herunterladen in verwaltbaren Gruppen durch Auswahl spezifischer Unterordner oder gezielter Dateigruppen wird für reibungslose Übertragungen bei großen Datensätzen empfohlen.

- **Registerkarte "Veröffentlicht"**
  Extrahiert die neueste veröffentlichte Überarbeitung für jedes ausgewählte Dokument.
- **Registerkarte "Arbeitsbereich"**
  Extrahiert die neueste gemeinsam genutzteÜberarbeitung für jedes ausgewählte Dokument (erfordert die Berechtigung "Gemeinsam genutzte Überarbeitungen anzeigen"). Beachten Sie, dass ältere Entwurfsüberarbeitungen nicht in einem ZIP-Archiv zusammengefasst heruntergeladen und einzeln heruntergeladen werden können.

**Download einzelner Überarbeitungen** Wählen Sie ein Dokument auf der [Dokumentenseite](https://support.catenda.com/en/articles/8204673-documents-page) aus und klicken Sie auf die Download-Schaltfläche neben jeder im rechten Informationsmenü aufgelisteten Überarbeitung. Dies ist eine einfachere Möglichkeit, individuelle oder historische Überarbeitungen herunterzuladen, da die Dokumentvorschauseite nicht geladen werden muss, so dass Sie ein anderes Dokument in der Tabelle auswählen und seine Überarbeitungen im rechten Menü herunterladen können, ohne eine neue Vorschauseite öffnen zu müssen.

**Öffentliche Sammlungen** Verwenden Sie [Sammlungen](https://support.catenda.com/en/articles/6344318-collections-page), um öffentliche Links für ausgewählte Dokumentuntergruppen zu erstellen, damit externe Parteien Dateien herunterladen können, ohne ein Catenda-Konto zu benötigen. Beachten Sie, dass nur veröffentlichte Überarbeitungen zu Sammlungen hinzugefügt werden können.

**Gelöschte Dateien** Suchen Sie nach "gelöscht" in der Dokumentsuchleiste, um zuvor gelöschte Dokumente zu lokalisieren und zu exportieren. Beachten Sie, dass dieser Filter sprachspezifisch ist und dem Begriff für "gelöscht" in Ihren aktuellen Spracheinstellungen entspricht.

### 2.4 **Desktop Connector (Automatisierte lokale Sicherung)**

Der [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) ermöglicht eine Hintergrundsynchronisierung, um regelmäßig neue Dokumentüberarbeitungen direkt auf ein lokales Laufwerk herunterzuladen. Im Gegensatz zu Batch-Web-Exporten werden heruntergeladene Dokumente direkt auf Ihrem System als rohe, entpackte Dateien ohne manuelle Archivextraktion angezeigt.

**Geplante & sofortige Sicherungen** Aufgaben können so geplant werden, dass sie automatisch in regelmäßigen Abständen ausgeführt werden, oder bei Bedarf ausgeführt werden, um sicherzustellen, dass Projektmitglieder eine aktuelle lokale Kopie von Dokumenten speichern, auch wenn der Projektaccess unerwartet widerrufen wird.

**Direkte API-Übertragungen** Übertragen Sie große Datensätze erheblich schneller als Web-Browser-Downloads durch Nutzung direkter API-Verbindungen ohne Browser-Einschränkungen oder Overhead.

**Hierarchieoptionen** Laden Sie ausgewählte Ordnerstrukturen mit vollständiger intakter Hierarchie herunter, oder extrahieren Sie individuell ausgewählte Dateien direkt als flache Liste in den designierten lokalen Ordner.

### 2.5 **Mitgliederzugriff und Aktivitätsprotokolle**

**Themen-Boards** Dokumenten-Board-Accessberechtigungen mit zwei verfügbaren Ansichten:

- **Pro-Benutzer-Zugriffsansicht**
  Zeigen Sie einzelne Benutzer-Accessebenen direkt aus dem rechten Informationsmenü eines Themen-Boards oder ausgewählten Themas an.
  _Access erforderlich:_ Read-Zugriff auf das Themen-Board
- **Vollständige Teamkonfiguration**
  Machen Sie Screenshots der vollständigen Berechtigungseinstellungen auf Team-Ebene in den Themen-Board-Accesseinstellungen.
  _Access erforderlich:_ Vollständiger Zugriff auf das Themen-Board oder Projektadministrator

**Dokument- & Modellzugriff** Exportieren Sie die [Accessübersicht](https://support.catenda.com/en/articles/6660820-document-access-overview-page), um Berechtigungen für Mitglieder und Teams zu dokumentieren. Access erforderlich: Projektadministrator. Da jedes Modell mit einem Dokument im Dokumentenbereich verknüpft ist, werden die Accessberechtigungen für Modelle durch die zugrunde liegenden Dokumentberechtigungen geregelt und mit denselben Dokumentaccessübersichten oder Berechtigungsmenüs dokumentiert.

**Dokument- & Modellüberarbeitungszugriff** Zeigen Sie Berechtigungen aus dem [rechten Menü einer Dokumentüberarbeitung](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision-revision-info) an und machen Sie Screenshots nach Bedarf.

**Projektweite Aktionsberechtigungen** Dokumentieren Sie projektweite Berechtigungen auf der [Projekteinstellungsseite](https://support.catenda.com/en/articles/4670273-project-settings-page) (z. B. Erstellen von Themen-Boards, Einladen neuer Mitglieder, Konfigurieren von Dokumentstatus und Erstellen oder Entfernen von Modellen) mit zwei verfügbaren Ansichten:

- **Pro-Benutzer-Zugriffsansicht**
  Projektmitglieder können jedes Menü unter Zugriffssteuerung erweitern, um zu sehen, welche einzelnen Benutzer die Berechtigung haben, jede Aktion auszuführen.
- **Vollständige Konfiguration**
  Administratoren können das Edit-Access-Dialogfeld öffnen, um Team-Level-Berechtigungskonfigurationen anzuzeigen und zu verwalten.
  _Access erforderlich:_ Projektadministrator

**Benutzerprofile & Mitgliederdetails** Informationen zu Projektmitgliedern und Teams sind zum Extrahieren oder Dokumentieren verfügbar, einschließlich:

- Benutzernamen und E-Mail-Adressen (siehe [Benutzerdefinierte Mitgliederinformation](https://www.google.com/search?q=https://support.catenda.com/en/articles/11769670-custom-member-information%23h_c15463ee3f)).
- Teamzugehörigkeiten, zugewiesene Themen, hochgeladene Modellüberarbeitungen und Berechtigungseinstellungen (erfasst über die [Mitgliedseite](https://www.google.com/search?q=https://support.catenda.com/en/articles/4670291-members-page) oder [Teamseite](https://www.google.com/search?q=https://support.catenda.com/en/articles/4670291-members-page)).

### 2.6 **Benachrichtigungen**

Erfassen Sie Benachrichtigungsseiten über Screenshots von der [Projektbenachrichtigungsseite](https://support.catenda.com/en/articles/4670295-project-notifications-page), wobei Sie den [Limit-Filter](https://support.catenda.com/en/articles/8304417-filtering-on-the-notifications-page) verwenden, um sichtbare Elemente pro Seite zu maximieren.

Konfigurieren Sie ein spezielles Administratorkonto mit [projektspezifischen Benachrichtigungseinstellungen](https://support.catenda.com/en/articles/4670262-project-specific-notification-settings), die für E-Mail-Zusammenfassungen aktiviert sind, um durchsuchbare Benachrichtigungsprotokolle zu speichern.

### 2.7 **Reports Page (Opt-In-Feature)**

**Opt-in-Aktivierung** Die Reports Page ist eine Opt-in-Funktion, die für laufende Projekte aktiviert werden kann. Obwohl die Verwendung dieses Tools keine zusätzliche Zahlung erforderlich ist, muss der Projekteigentümer zustimmen, es für das Projekt zu aktivieren, was bedeutet, dass es in vielen Projekten nicht standardmäßig aktiv ist. Beachten Sie, dass neue Projekte, die aus Vorlagenprojekten erstellt werden, in denen Reports aktiviert sind, diese Funktion nicht automatisch aktiviert haben.

**Vorlagenbasierte Verwaltung** Wenn aktiviert, können Projektadministratoren die [Berichtsvorlagenseite](https://support.catenda.com/en/articles/12380837-report-templates-page) verwenden, um benutzerdefinierte Berichtsvorlagen zu konfigurieren und formatierte Exporte für ausgewählte Dokumente oder Themen zu generieren.

**Dokumentberichte** Exportieren Sie Dokumentmetadaten und Überarbeitungsdetails für alle ausgewählten Dateien, einschließlich Dokumentname, Überarbeitungsname, neueste Überarbeitungsnummer, Status, benutzerdefinierte Felder, Ersteller, Uploader und Erstellungs-/Hochlade-Zeitstempel.

- **Wichtige Anwendungsfälle**
  Ideal zur Generierung formeller Dokumentlieferchecklisten zur Begleitung einer Sammlung oder zur Kompilierung strukturierter Dokumentlisten für die Datenanalyse.
- **Modellmetadaten & -attribute**
  Obwohl der tatsächliche Dokumentdateiinhalt nicht enthalten ist, können Modellmetadaten über Dokumentberichte exportiert werden, da Modelle Verknüpfungen zum Dokumentenbereich beibehalten. Benutzerdefinierte Skripte innerhalb von Vorlagen können auch verwendet werden, um zusätzliche Attribute abzuleiten, z. B. das Extrahieren von Dateitypen aus Dokumentnamen.

**Themenberichte** Exportieren Sie gesamte Themenkopfzeilen sowie vollständige Themenkörperdetails, einschließlich Beschreibungen, Kommentare und eingebettete Kommentarbilder.

**Verfügbare Exportformate** Berichte, die aus einer beliebigen Vorlage erstellt wurden, können je nach Ihren Arbeitsablaufanforderungen in mehrere Formate exportiert werden:

- **PDF / PDF/A**
  Generiert sauber formatierte Berichte und unterstützt direkt die native PDF/A-Compliance (PDF/A-1, PDF/A-2 und PDF/A-3) zur Erfüllung strikter langfristiger Archivierungs- und formeller Rechtsnormen.
- **Excel**
  Exportiert strukturierte Tabellendaten in Tabellenzeilen und -spalten, was sich ideal für Datenmanipulation und externe Analyse eignet.
- **Zusätzliche Formate**
  Eine breite Palette zusätzlicher Dateiformate über PDF und Excel hinaus wird auch zum Exportieren unterstützt; die vollständige Übersicht finden Sie im [Reports Page](https://support.catenda.com/en/articles/12303098-reports-page)-Artikel.

**Zentralisierte Speicherung** Generierte Berichte werden direkt in der Berichtstabelle aufgelistet und automatisch in die Hauptdokumenttabelle integriert, um eine einfache Verwaltung zu ermöglichen.

## 3. **Catenda Data Export**

Im Gegensatz zu standardmäßigen benutzergesteuerten Downloads ist Catenda Data Export eine automatisierte Self-Service-Lösung, die es ermöglicht, Projektdaten nahtlos direkt in den Cloud-Speicher einer Organisation zu übertragen. Wenn Ihre Organisation daran interessiert ist, diese Funktion zu aktivieren, können Sie den Vertrieb unter [sales@catenda.com](mailto:sales@catenda.com) erreichen. Nach Aktivierung bietet es automatisierte Backups direkt zwischen Cloud-Umgebungen ohne benutzerdefinierte Skripte, wobei Browserspeicherbeschränkungen, lokale Speicherbegrenzungen und Netzwerkunterbrechungen durch automatisierte Checksummen-Überprüfung umgangen werden.

### 3.1 **Organisationsrollen & Berechtigungen**

Das Einrichten und Verwalten von Catenda Data Export erfordert einen **Organisationsadministrator**. Im Gegensatz zu einem Organisationseigentümer, dessen Administratorrechte auf eine einzelne Organisation beschränkt sind, oder standardmäßigen Projektmitgliedern hat ein Organisationsadministrator erhöhten Zugriff auf alle Organisationen, die zu einem übergeordneten Konto gehören. Diese einzigartige Rolle gewährt die erforderliche organisationsübergreifende Sichtbarkeit und Autorität, um automatisierte Cloud-Exporte zu konfigurieren und zu verwalten.

### 3.2 **Konfigurationsschritte**

Das Einrichten automatisierter Datenexporte umfasst vier Hauptschritte:

1. **Ziel auswählen**
   Wählen Sie einen Cloud-Speicheranbieter, Amazon Web Services (AWS) S3 oder Microsoft Azure Blob-Speicher, und konfigurieren Sie die Authentifizierung.
1. **Umfang & Datenformate definieren**
   - **Datentypen**
     Exportieren Sie Dokumente, Modelle und Themen.
     Themendaten können während der Übertragung automatisch in lesbare PDF-Zusammenfassungsberichte oder Standard-BCF-Dateien konvertiert werden.
   - **Projektauswahl**
     Wählen Sie alle Projekte aus, wählen Sie spezifische Projekte per Hand aus, oder richten Sie dynamische Matching-Regeln mithilfe von Projektnamenmustern (Glob oder regulärer Ausdruck / Regex) ein, um automatisch neue Projekte einzubeziehen, während sie erstellt werden.
1. **Exportmodus wählen**
   - **Kontinuierlicher Modus**
     Versendet Daten automatisch nach einem täglichen Zeitplan.
     Diese wiederkehrende Einrichtung stellt sicher, dass Nicht-Eigentümer-Projektmitglieder eine aktualisierte Sicherung bis zur letzten täglichen Ausführung beibehalten, wenn der Projektaccess unerwartet endet.
   - **Snapshot-Modus**
     Führt eine einmalige Ausführung durch, um einen vollständigen Datensatz bei einem spezifischen Meilenstein oder einer Projektübergabe zu exportieren.
1. **Bereitstellen**
   Finalisieren und aktivieren Sie die Exportkonfiguration durch Auswahl der Erstellung.

### 3.3 **Extrahierter Inhalt & Integritätsüberprüfung**

**Metadaten & Benutzerdefinierte Felder** Benutzerdefinierte Felder, die mit Dokumenten und Themen verknüpft sind, werden zusammen mit primären Dateien als strukturierte JSON-Dateien exportiert, um eine vollständige Attributaufbewahrung ohne manuelle Berichtsgenerierung zu gewährleisten.

**Integritätsüberprüfung** Jede Exportausführung generiert eine Checksummendatei, um zu überprüfen, dass exportierte Dateien den Quelldaten in Catenda Hub entsprechen und vollständig ohne Netzwerkverlust übertragen wurden.

**Organisierte Hierarchie** Exportierte Dateien werden automatisch in Ordnern organisiert, die nach Datum, Projektname und genau der in Catenda Hub beibehaltenen Ordnerhierarchie organisiert sind.
