# Changelog 4 Catenda - Januar 2024

> Neue Informationen und kleinere Änderungen

Hallo zusammen,

es ist schon ein paar Monate her seit dem letzten Changelog. Hoffentlich hattet ihr alle einen schönen Winterurlaub! 🎄🤶🧑‍🎄❄️ Und willkommen zu 2024!🎇 Hoffentlich werden wir auch dieses Jahr viele Änderungen und Verbesserungen vornehmen können! In diesem Artikel findest du Updates zu folgenden Themen: [Artikel](https://support.catenda.com/en/articles/7983534-changelog-3-catenda-update-october-2023#h_5be2a02999) - [Behobene Probleme](https://support.catenda.com/en/articles/7983534-changelog-3-catenda-update-october-2023#h_d238d9111d) - [Neue Versionen](https://support.catenda.com/en/articles/7983534-changelog-3-catenda-update-october-2023#h_d238d9111d)

## 1. **Artikel**

Mit dem Rollout neuer Funktionen und dem Beheben von Fehlern werden Artikel mit den vorgenommenen Änderungen aktualisiert. Bitte finde die folgenden Artikel, die seit dem letzten Changelog erstellt und geändert wurden.

### 1.1 **Neue Artikel:**

**Erste Schritte und FAQ** [Sortierreihenfolge von Listen](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) [Strukturierung von Dokumenten](https://support.catenda.com/en/articles/8542598-structuring-documents)

**Hauptseite** [Organisationsseite](https://support.catenda.com/en/articles/8281910-organizations-page)

**Themen** [Themenverlauf](https://support.catenda.com/en/articles/8613038-issue-history)

**Dokumente** [Dokumente](https://support.catenda.com/en/articles/8461918-documents) [PDF-Vergleich](https://support.catenda.com/en/articles/8461650-pdf-compare) [Filterung auf der Genehmigungsseite](https://support.catenda.com/en/articles/8551740-filtering-on-the-approvals-page)

**Modelle und 3D** [Lesezeichen](https://support.catenda.com/en/articles/8471481-bookmark)

**Projekteinstellungen** [Erstellen eines benutzerdefinierten Felds](https://support.catenda.com/en/articles/8445575-creating-a-custom-field) [Seite "Benutzerdefiniertes Feld"](https://support.catenda.com/en/articles/8445588-custom-field-page)

### 1.2 **Artikel, die sich geändert haben:**

Erste Schritte und FAQ [Filter speichern](https://support.catenda.com/en/articles/8551755-saving-filters)

Themen [Themenboards ACL](https://support.catenda.com/en/articles/4670296-issue-boards-acl)

Dokumente [Dokumentenseite](https://support.catenda.com/en/articles/8204673-documents-page) [Modelle als Dokumente](https://support.catenda.com/en/articles/8064548-models-as-documents) [Filterung auf der Dokumentenseite](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page)

Modelle [Seite "Lesezeichen"](https://support.catenda.com/en/articles/4670281-bookmarks-page) [Erstellen eines neuen Lesezeichens](https://support.catenda.com/en/articles/4670269-creating-a-new-bookmark) [Modelle als Dokumente](https://support.catenda.com/en/articles/8064548-models-as-documents)

Bibliotheken <a class="intercom-content-link" href="" target="_blank">Links-Bibliothek</a>

Einstellungen [Mitgliedersseite](https://support.catenda.com/en/articles/4670291-members-page)

## 2. **Behobene Probleme**

Dank eures wertvollen Feedbacks konnten wir viele Probleme beheben, die du möglicherweise bemerkt hast oder auch nicht. Nachfolgend findest du eine Liste mit kleineren Änderungen, die das Entwicklungsteam als Ergebnis von Gesprächen mit Benutzern vorgenommen hat.

### 2.1 **Themen**

- Benutzerdefinierte Dropdown-Felder mit bis zu 10 erforderlichen Werten können jetzt auch gefiltert werden.
- PDF-Exporte von Themen zeigen nun nicht mehr bestimmte Bilder zweimal.
- Benutzerdefinierte Feldfilter werden jetzt auch angezeigt, wenn das benutzerdefinierte Feld als erforderlich festgelegt ist.
- Bilder, die nach dem 16. November an Themenkommentare angehängt sind, werden jetzt im Dialog "Vorschau" in derselben Reihenfolge angezeigt, in der sie sich in den Themenkommentaren befinden.
- Die Exportzeit im PDF-Export zeigt nun UTC dahinter an, damit der Benutzer wissen kann, in welcher Zeitzone der Zeitstempel war.
- Modelle, die im Zeitfenster zwischen der Vorbereitung und der Aktivierung einer Modelle-als-Dokumente-Migration gelöscht werden, werden nun ordnungsgemäß bei der Migration gelöscht.

### 2.2 **Dokumente**

- Litauische Buchstaben in Dokumenten, die aus ZIP-Importen importiert wurden, werden nicht mehr beschädigt, wenn Zip-Poisoning auftritt.
- Textblasen können jetzt wieder von Benutzern mit MFA-Erzwingung platziert werden.
- Highlight-Anmerkungen aus PDF-Dateien werden jetzt ordnungsgemäß im PDF-Viewer angezeigt, nachdem sie hochgeladen wurden.
- PDFs können jetzt wieder mit Anmerkungen und Kommentaren gespeichert werden.
- Dokumente, die für Benutzer mit MFA-Erzwingung nicht geladen wurden, werden jetzt wieder geladen.

### 2.3 **Modelle**

- Die Schaltfläche zum Löschen des Modells ist wieder sichtbar.
- Es gibt jetzt keine Möglichkeit mehr, Modelle auszublenden, wenn "Modelle als Dokumente" aktiviert wurde, ohne das Projekt zu migrieren.
- Die E-Mail-Benachrichtigung zum Import von Modellen sagt jetzt "Import abgeschlossen auf \<Modell>" anstelle von "Neue Revision in Modell" zur Verdeutlichung.
- Im Geschossplaner können jetzt nur noch PDF-Dokumente ausgewählt werden, wo PDF erforderlich ist.
- Es ist nicht mehr möglich, Nicht-PDF-Dokumente zum Geschossplaner hinzuzufügen. (der nur PDFs akzeptiert)

## 3. **Benutzeranfragen bearbeitet**

### 3.1 **Themen**

- Du erhältst jetzt eine Benachrichtigung, wenn ein Team, dem du angehörst, in einem Thema erwähnt wird
- Wenn du in 2D auf "Marker anzeigen" am Ort eines Themas klickst, zentriert dein 2D-Viewer jetzt auf diesen Marker, anstatt nur den Marker als ausgewählt auf dem rechten Geschoss anzuzeigen.
- Die Breite des Modellauswahldialoges im Kommentar eines Themas skaliert jetzt mit der Breite eines Modellnamens. Zuvor wurden lange Modellnamen abgeschnitten und mussten mit der Maus überfahren werden, um sie zu sehen.
- Es ist jetzt möglich zu sehen, wie eine Beschreibung aussah, bevor sie geändert wurde, indem du im Themenverlauf auf das Feld "Beschreibung geändert" klickst.
- Bilder werden nicht mehr doppelt in PDF-Exporten älterer Themen angezeigt

### 3.2 **Dokumente**

- Die Dokument-ACL wird jetzt im Modellabschnitt für Projekte angezeigt, bei denen "Modelle als Dokumente" aktiviert ist
- Du kannst jetzt sehen, wie viele Dokumente sich in einer Sammlung befinden.
- Es ist jetzt möglich, sich an Mittelpunkte und Endpunkte von Linien in PDF-Zeichnungen zu fangen.
- Es ist jetzt möglich, eine Vorschau von .odt- und .ods-Dateiformaten anzuzeigen.

### 3.3 **Modelle**

- Es ist jetzt möglich, die ACL pro Modell statt für alle Modelle festzulegen.

Dies bedeutet, dass du Modelle vor Personen im Modellabschnitt verbergen kannst.

- Mit Modelle als Dokumente kannst du Etiketten zu Modellen hinzufügen.
- Mit Modelle als Dokumente kannst du Modelle in Ordnern im Abschnitt "Dokumente" strukturieren.
- Mit Modelle als Dokumente kannst du die Dateigröße des Modells sehen
- Mit Modelle als Dokumente kannst du die Benennungskonvention-Funktion mit Modellen verwenden
- Es ist jetzt wieder möglich, frühere Versionen von Modellen in der Versionsauswahl anzuzeigen

### 3.4 **Projekteinstellungen**

- Etikettgruppen können jetzt gelöscht werden.
- Es ist jetzt möglich, Etiketten zu löschen, die mit Themen/Dokumenten verbunden sind.
- Etikettgruppen können bearbeitet werden.
  Du findest den Bearbeitungsstift im rechten Informationsmenü, nachdem du die Etikettgruppe auf der Registerkarte "Gruppen" ausgewählt hast.
- Es ist jetzt möglich, mehrere Etiketten auf einmal zu erstellen.
  Beachte die Schaltfläche "Mehrere importieren" im neuen Etikettmenü.
- Es ist jetzt möglich, mehrere Etiketten auf einmal zu löschen.
- Etiketten können gefiltert werden und Filter können gespeichert werden.
- Es ist jetzt möglich, neue Etikettgruppen hinzuzufügen
- Es ist möglich, Etikettgruppen hinzuzufügen, ohne sie zuerst zu einem Etikett hinzuzufügen.
- Es ist jetzt möglich, auf der Etikettseite zu suchen.
- Administratoren können jetzt Etiketten zusammenführen. Die Option kann gefunden werden, indem mehr als ein Etikett auf der Etikettenseite ausgewählt wird.

### 3.5 **Allgemeines**

- Das Erstellen neuer Projekte aus Vorlagenprojekten wurde verbessert. Es ist jetzt möglich, folgende Teile eines Projekts in ein neues Projekt zu bringen:
  - Ordnerstruktur
  - Dokumentstatuskonfiguration
  - Dokument- und Themenbrettzugriff
  - Benutzerdefinierte Felder und Benennungskonventionen

## 4. **Neue Versionen** - Catenda Site, Plugins und Integrationen

**Catenda Hub:**

- Modelle als Dokumente wurde vollständig freigegeben.
- Probleme wurden in Themen umbenannt.

_Catenda Site:_ [App Store](https://apps.apple.com/us/app/catenda-site/id1449579790) [Play Store](https://play.google.com/store/apps/details?id=no.catenda.bimsyncmobile)

**Neue Version 3.3.1**

- Fehlerbehebungen

**Neue Version 3.3.0**

- _Deep Linking_ - URLs von der Hub-Website öffnen sich direkt in der Site-App.
- _Themenfilterung_ - Neue Option zum Filtern nach Meilenstein.
- _Benutzererwähnung_ - Finde und wähle schnell einen Benutzer zur Erwähnung in Themen aus der Symbolleiste aus.
- _Textformatierung_ - Wende einfach Rich-Text auf deine Themen aus der Symbolleiste an.
- _2D-Marker zentrieren_ - Das Öffnen eines Markers aus einem Thema zentriert die Ansicht auf den Markerort.
- Unterstützung der vietnamesischen Sprache. 🇻🇳

**Neue Version 3.4.0**

- Probleme wurden in Themen umbenannt
- Fehlerbehebungen

**SharePoint-Integration:**

- Du kannst dich jetzt über ein Browser-Popup mit deinem Catenda-Konto verbinden, anstatt auf eine E-Mail zu warten.
