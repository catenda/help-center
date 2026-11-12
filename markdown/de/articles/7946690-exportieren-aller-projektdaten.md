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

**Download ausgewählter Modelle** Wählen Sie ein oder mehrere Modelle auf der [Modellseite](https://support.catenda.com/de/articles/4670286-modellseite) aus und verwenden Sie die Download-Aktion, um ihre neuesten Überarbeitungen zu extrahieren.

**Download einzelner Überarbeitungen** Wählen Sie ein Modell auf der [Modellseite](https://support.catenda.com/de/articles/4670286-modellseite) aus und verwenden Sie die Download-Schaltfläche neben jeder Überarbeitung im rechten Informationsbereich. Dies bietet eine effiziente Möglichkeit, bestimmte Überarbeitungen direkt herunterzuladen, ohne die vollständige [Modellinhaltseite](https://support.catenda.com/de/articles/4670270-modellinhaltseite) laden zu müssen. Alternativ können einzelne Überarbeitungen auch direkt von der Inhaltsseite eines Modells heruntergeladen werden.

**Erweiterter Modellexport** Greifen Sie auf die [Modellexportseite](https://support.catenda.com/de/articles/4670280-modell-exportseite) zu, um ausgewählte Überarbeitungen über mehrere Modelle hinweg in einer einzigen herunterladbaren ZIP-Datei zu packen. Diese Methode beinhaltet erweiterte Optionen zur Verbesserung der exportierten Modelldateien durch Einbindung von Tags, benutzerdefinierten Eigenschaften oder Bibliotheksinformationen.

### 2.2 **Themen exportieren (3 Wege)**

Themendaten können über [Exchange Topics](https://support.catenda.com/de/articles/4670289-themen-austausch) in drei Primärformaten extrahiert werden, je nachdem wie die Informationen angezeigt, analysiert oder gespeichert werden:

**BCF (BIM Collaboration Format)** Ein offener Standard, der zur Erfassung und Übertragung von Themeninformationen entwickelt wurde und sich streng an die offizielle BCF-Spezifikation hält, einschließlich einzelner Themenerstellungs-Zeitstempel. Dieses Format garantiert eine breite plattformübergreifende Interoperabilität und eignet sich ideal für die nahtlose Wiederöffnung, Bearbeitung oder Verwendung von Themendaten mit anderer BCF-kompatibler Software. Für allgemeine langfristige Dokumentrepositories, bei denen direkte Dateivorschauen erforderlich sind, werden in der Regel PDF- oder Excel-Formate bevorzugt.

**Excel** Exportiert Themenparameter in ein Tabellenformat für Filterung, Sortierung und Datenmanipulation. Dieses Format bietet strukturierte Zeilen und Spalten, die sich ideal für die Auswahl und das Kopieren von Daten eignen, und Excel-Dateien können in den meisten Archivierungsplattformen leicht vorhergesehen werden. Für Archivierungszwecke wird der PDF-Export in der Regel dem Excel-Export vorgezogen, da er mehr Informationen enthält.

**PDF** Generiert einen sauberen, lesbaren Zusammenfassungsbericht im Standard-PDF-Format (v1.4), das ohne spezialisierte Software zugänglich ist (siehe [Themen als PDF exportieren](https://support.catenda.com/de/articles/9784934-themen-in-pdf-exportieren)). Standard-PDF-Exporte enthalten einen konsolidierten Download-Zeitstempel für die Berichterstattung an Behörden und für die Archivierung und bieten mehr Informationen als ein Excel-Export. Während der Basis-Export eine Standard-PDF-Datei (v1.4) generiert, die viele Archivsysteme beim Upload automatisch in PDF/A konvertieren, um eine langfristige Vorschau zu ermöglichen, können Projekte mit der optionalen [Berichtsseite](https://support.catenda.com/de/articles/12303098-berichterstattungsseite) auch Themen in Archivierungsformaten exportieren, wie in [Projektdaten mit Berichten exportieren](https://support.catenda.com/de/articles/17779017-projektdaten-mit-berichten-exportieren) beschrieben _(nur für Berichtereditor-Kunden)_.

### 2.3 **Dokumente und Sammlungen exportieren**

**Batch- & Ordner-Downloads** Wählen Sie einzelne Ordner, spezifische Dokumentengruppen oder alle sichtbaren Tabellenelemente auf einmal aus, um ein herunterladbares ZIP-Archiv zu generieren. Das Herunterladen in verwaltbaren Gruppen durch Auswahl spezifischer Unterordner oder gezielter Dateigruppen wird für reibungslose Übertragungen bei großen Datensätzen empfohlen.

- **Registerkarte „Veröffentlicht“**<br>Extrahiert die letzte veröffentlichte Revision für jedes ausgewählte Dokument.
- **Registerkarte "Arbeitsbereich"<br>Extrahiert die neueste gemeinsam genutzte Version für jedes ausgewählte Dokument (erfordert die Berechtigung "Gemeinsam genutzte Versionen anzeigen"). Beachten Sie, dass Legacy-Entwurfversionen nicht in einem ZIP-Archiv per Batch heruntergeladen werden können und einzeln heruntergeladen werden.

**Download einzelner Überarbeitungen** Wählen Sie ein Dokument auf der [Dokumentenseite](https://support.catenda.com/de/articles/8204673-dokumentenseite) aus und klicken Sie auf die Download-Schaltfläche neben jeder im rechten Informationsmenü aufgelisteten Überarbeitung. Dies ist eine einfachere Möglichkeit, individuelle oder historische Überarbeitungen herunterzuladen, da die Dokumentvorschauseite nicht geladen werden muss, so dass Sie ein anderes Dokument in der Tabelle auswählen und seine Überarbeitungen im rechten Menü herunterladen können, ohne eine neue Vorschauseite öffnen zu müssen.

**Öffentliche Sammlungen** Verwenden Sie [Sammlungen](https://support.catenda.com/de/articles/6344318-sammlungsseite), um öffentliche Links für ausgewählte Dokumentuntergruppen zu erstellen, damit externe Parteien Dateien herunterladen können, ohne ein Catenda-Konto zu benötigen. Beachten Sie, dass nur veröffentlichte Überarbeitungen zu Sammlungen hinzugefügt werden können.

**Gelöschte Dateien** Suchen Sie nach "gelöscht" in der Dokumentsuchleiste, um zuvor gelöschte Dokumente zu lokalisieren und zu exportieren. Beachten Sie, dass dieser Filter sprachspezifisch ist und dem Begriff für "gelöscht" in Ihren aktuellen Spracheinstellungen entspricht.

### 2.4 **Desktop Connector (Automatisierte lokale Sicherung)**

Der [Catenda Desktop Connector](https://support.catenda.com/de/articles/8358861-catenda-desktop-connector) ermöglicht eine Hintergrundsynchronisierung, um neue revisions von Dokumenten regelmäßig direkt auf ein lokales Laufwerk herunterzuladen. Anders als Batch-Exporte im Web kommen die heruntergeladenen Dokumente direkt als unkomprimierte Rohdateien auf Ihrem System an, ohne dass ein manuelles Entpacken von Archiven erforderlich ist.

**Geplante & sofortige Sicherungen** Aufgaben können so geplant werden, dass sie automatisch in regelmäßigen Abständen ausgeführt werden, oder bei Bedarf ausgeführt werden, um sicherzustellen, dass Projektmitglieder eine aktuelle lokale Kopie von Dokumenten speichern, auch wenn der Projektaccess unerwartet widerrufen wird.

**Direkte API-Übertragungen** Übertragen Sie große Datensätze erheblich schneller als Web-Browser-Downloads durch Nutzung direkter API-Verbindungen ohne Browser-Einschränkungen oder Overhead.

**Hierarchieoptionen** Laden Sie ausgewählte Ordnerstrukturen mit vollständiger intakter Hierarchie herunter, oder extrahieren Sie individuell ausgewählte Dateien direkt als flache Liste in den designierten lokalen Ordner.

### 2.5 **Mitgliederzugriff und Aktivitätsprotokolle**

**Themen-Boards** Dokumenten-Board-Accessberechtigungen mit zwei verfügbaren Ansichten:

- **Zugriff pro Benutzer**<br>Zeigen Sie die Zugriffsstufen einzelner Benutzer direkt aus dem Informationsmenü auf der rechten Seite eines Themen-Boards oder eines ausgewählten Themas an.<br>_Erforderlicher Zugriff:_ Lesezugriff auf das Themen-Board
- **Vollständige Team-Konfiguration**<br>Erstellen Sie Screenshots der kompletten Berechtigungseinstellungen auf Team-Ebene in den Zugriffseinstellungen des Themen-Boards.<br>_Erforderlicher Zugriff:_ Vollständiger Zugriff auf das Themen-Board oder Projektadministrator

**Dokument- & Modellzugriff** Exportieren Sie die [Accessübersicht](https://support.catenda.com/de/articles/6660820-seite-zugriffsubersicht-fur-dokumente), um Berechtigungen für Mitglieder und Teams zu dokumentieren. Access erforderlich: Projektadministrator. Da jedes Modell mit einem Dokument im Dokumentenbereich verknüpft ist, werden die Accessberechtigungen für Modelle durch die zugrunde liegenden Dokumentberechtigungen geregelt und mit denselben Dokumentaccessübersichten oder Berechtigungsmenüs dokumentiert.

**Dokument- & Modellüberarbeitungszugriff** Zeigen Sie Berechtigungen aus dem [rechten Menü einer Dokumentüberarbeitung](https://support.catenda.com/de/articles/8302244-rechtes-menu-einer-revision-revisionsinformationen) an und machen Sie Screenshots nach Bedarf.

**Projektweite Aktionsberechtigungen** Dokumentieren Sie projektweite Berechtigungen auf der [Projekteinstellungsseite](https://support.catenda.com/de/articles/4670273-seite-projekteinstellungen) (z. B. Erstellen von Themen-Boards, Einladen neuer Mitglieder, Konfigurieren von Dokumentstatus und Erstellen oder Entfernen von Modellen) mit zwei verfügbaren Ansichten:

- **Pro-Benutzer-Zugriffssicht<br>Projektmitglieder können jedes Menü unter der Zugriffskontrolle erweitern, um zu sehen, welche einzelnen Benutzer berechtigt sind, jede Aktion auszuführen.
- **Vollständige Konfiguration**<br>Administratoren können den Dialog zum Bearbeiten des Zugriffs öffnen, um Berechtigungskonfigurationen auf Team-Ebene anzuzeigen und zu verwalten.<br>_Erforderlicher Zugriff:_ Projektadministrator

**Benutzerprofile & Mitgliederdetails** Informationen zu Projektmitgliedern und Teams sind zum Extrahieren oder Dokumentieren verfügbar, einschließlich:

- Benutzernamen und E-Mail-Adressen (siehe [Benutzerdefinierte Mitgliederinformation](https://www.google.com/search?q=https://support.catenda.com/de/articles/11769670-benutzerdefinierte-mitgliedsinformationen)).
- Teamzugehörigkeiten, zugewiesene Themen, hochgeladene Modellüberarbeitungen und Berechtigungseinstellungen (erfasst über die [Mitgliedseite](https://www.google.com/search?q=https://support.catenda.com/de/articles/4670291-mitglieder-und-teams-seite) oder [Teamseite](https://www.google.com/search?q=https://support.catenda.com/de/articles/4670291-mitglieder-und-teams-seite)).

### 2.6 **Benachrichtigungen**

Erfassen Sie Benachrichtigungsseiten über Screenshots von der [Projektbenachrichtigungsseite](https://support.catenda.com/de/articles/4670295-projektbenachrichtigungsseite), wobei Sie den [Limit-Filter](https://support.catenda.com/de/articles/8304417-filterung-auf-der-benachrichtigungsseite) verwenden, um sichtbare Elemente pro Seite zu maximieren.

Konfigurieren Sie ein spezielles Administratorkonto mit [projektspezifischen Benachrichtigungseinstellungen](https://support.catenda.com/de/articles/4670262-projektspezifische-benachrichtigungseinstellungen), die für E-Mail-Zusammenfassungen aktiviert sind, um durchsuchbare Benachrichtigungsprotokolle zu speichern.

### 2.7 **Reports Page (Opt-In-Feature)**

Die [Berichtsseite](https://support.catenda.com/de/articles/12303098-berichterstattungsseite) ist eine optionale Funktion, die für laufende Projekte angefordert werden kann. Projekte, bei denen sie aktiviert ist, können Dokumente und Themendaten auch als formatierte Berichte exportieren, einschließlich Formate für die langfristige Archivierung.

**Vorlagenbasierte Verwaltung** Wenn diese aktiviert ist, verwenden Projektadministratoren die [Seite mit Berichtsvorlagen](https://support.catenda.com/de/articles/12380837-seite-berichtvorlagen), um ihre eigenen Berichtsvorlagen einzurichten und formatierte Exporte für ausgewählte Dokumente oder Themen zu generieren.

Was exportiert werden kann und in welchen Dateiformaten, wird in [Projektdaten mit Berichten exportieren](https://support.catenda.com/de/articles/17779017-projektdaten-mit-berichten-exportieren) beschrieben _(nur für Berichtereditor-Kunden)_.

## 3. **Catenda Data Export**

Catenda Data Export wird separat von Catenda Hub verkauft. Anders als bei den oben genannten Downloads kopiert es Projektdaten automatisch direkt von Catenda Hub in den eigenen Cloud-Speicher einer Organisation bei Amazon S3 oder Azure Blob Storage. Es eignet sich für Organisationen, die ein Backup wünschen, das mit ihren Projekten Schritt hält, oder Projektunterlagen in ihrem eigenen Speicher aufbewahren möchten. Es ist nicht nur für Projektinhaber gedacht. Ein Projektinhaber kann ein vollständiges Backup seiner Projekte exportieren, und ein Projektteilnehmer kann alles exportieren, worauf er in den Projekten, an denen er teilnimmt, Zugriff hat. Mehr dazu finden Sie unter [Über Catenda Data Export](https://support.catenda.com/de/articles/17779020-uber-catenda-data-export) _(für Leser, die nicht angemeldet sind)_ und [Einführung in Catenda Data Export](https://support.catenda.com/de/articles/17779027-einfuhrung-in-catenda-data-export) _(nur für angemeldete Kunden)_. Kunden, die es haben, finden die Einrichtung unter [Catenda Data Export](https://support.catenda.com/de/articles/17779052-catenda-datenexport) _(nur für Data-Export-Kunden)_.
