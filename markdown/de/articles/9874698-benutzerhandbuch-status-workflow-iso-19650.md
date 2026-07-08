# Neuer Status-Workflow - ISO 19650

Der neue Status-Workflow ist eine Funktion auf Anfrage, die für laufende Projekte aktiviert werden kann. Neue Projekte, die auf der Grundlage eines Vorlagenprojekts erstellt werden, in dem diese Funktion aktiviert ist, haben diese Funktion ebenfalls aktiviert. Die ISO-19650-Serie ist ein internationaler Standard für bewährte Praktiken, der Informationsverwaltungsprozesse im breiteren Kontext der digitalen Transformation in der Bauindustrie definiert. Viele Akteure in der Bauindustrie haben die ISO-19650 als Standard zur Verwaltung von Dokumentlieferungs- und Genehmigungsprozessen in Projekten übernommen.

## 1. **Lebenszyklus eines Dokuments**

Nach dem ISO-Standard kann ein Dokument vier verschiedene Status haben;

### 1.1 **🏗️ Laufende Arbeit (WiP)**

Dateien, an denen gearbeitet wird und die ständig in der lokalen Umgebung des Benutzers überschrieben werden. Diese Dateien werden typischerweise nur in Catenda hochgeladen, damit Personen die Fortschritte des Benutzers sehen können.

### 1.2 **👥 Gemeinsam genutzt**

Dateien, die zum Austausch mit anderen Projektmitgliedern zur Koordination und endgültigen Überprüfung durch verschiedene Gewerke und/oder Spezialisten bereit sind. Diese Dateien werden in Catenda hochgeladen und an die jeweiligen Parteien zur Überprüfung und Genehmigung gesendet.

### 1.3 **📰 Veröffentlicht**

Dateien, die koordiniert, finalisiert und als vertragliches Liefererzeugnis akzeptiert wurden. Diese Dateien haben einen Überprüfungsprozess durchlaufen und gelten als "bereit für die nächste Phase (Konstruktion, Übergabe, Mengenermittlung, Genehmigungserstellung usw.)"

### 1.4 **📦 Archiviert**

Die Informationen wurden verwendet und können archiviert werden, um bei Bedarf später verfügbar zu bleiben (Audit, Erstellung der durchgeführten Arbeiten usw.)

### 1.5 **Dokumentstatus - ISO 19650**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/01-document-states-iso-19650.png)

### 1.6 **Workflow in Catenda Hub**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/02-workflow-on-catenda-hub.png)

## 2. **Status-Workflow konfigurieren**

Die Aktivierung und Konfiguration des gemeinsamen Status-Workflows ist Projektadministratoren vorbehalten.

_Erforderlicher Zugriff_ Zugriff auf die Dokumentstatuskonfiguration im [Zugriffskontrollbereich](https://support.catenda.com/en/articles/4670273-project-settings-page#h_3b98ced32a) der [Projekteinstellungsseite](https://support.catenda.com/en/articles/4670273-project-settings-page). Mitglieder mit diesem Zugriff haben nur Zugriff auf das Statuskonfigurationsmenü in den Dokumenteinstellungen. Sie können die anderen Menüs in den Dokumenteinstellungen nicht sehen oder ändern.

Gehen Sie unter [Dokumenteinstellungen](https://support.catenda.com/en/articles/7831371-document-settings) zu [Status-Workflow](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) und aktivieren Sie gemeinsame Status

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/03-configuring-status-workflow.png)

Definieren Sie die gemeinsamen und veröffentlichten Status, die im Projekt verwendet werden sollen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/04-configuring-status-workflow.png)

Legen Sie den Standard-Gemeinsamstatus für neue Revisionen fest. Neue Revisionen werden anfänglich als gemeinsame Revisionen hochgeladen und können später veröffentlicht werden. Der Standardstatus muss daher ein gemeinsamer Revisionsstatus sein. Dieser Status wird im Upload-Dialog für jeden Dokumentupload ausgewählt und kann während des Upload-Prozesses in einen anderen gemeinsamen Status geändert werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/05-configuring-status-workflow.png)

## 3. **Vertraut, aber anders**

Nach der Aktivierung des Status-Workflows sehen Sie zwei Registerkarten über den Dokumenten- und Modelltabellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/06-familiar-but-different.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/07-familiar-but-different.png)

### 3.1 **Arbeitsbereich**

Alle Uploads neuer Revisionen finden hier statt. Die neueste gemeinsame Revision wird für jedes Dokument und Modell angezeigt.

### 3.2 **Veröffentlicht**

Eine gespiegelte Version der Arbeitsbereichsregisterkarte. Die gleiche Ordnerstruktur wie im Arbeitsbereich wird angezeigt. Nur Dokumente und Modelle mit veröffentlichten Revisionen werden angezeigt.

> **Hinweis:** Sehen Sie gemeinsame Revisionen in der Revisionsübersicht der Dokumentvorschau, auch wenn Sie das Dokument von der veröffentlichten Registerkarte geöffnet haben. _Erforderlicher Zugriff:_ Gemeinsame Revisionen

### 3.3 **Neue gemeinsame Revisionen hochladen**

Ein Revisionsstatus wird für jede hochgeladene Datei im Upload-Dialog angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/08-upload-new-shared-revisions.png)

Ein Revisionsstatus wird für jede Datei angewendet, die aus einer gezippten Datei extrahiert wird.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/09-upload-new-shared-revisions.png)

### 3.4 Gemeinsame Revisionen veröffentlichen

**Mehrere Dokumente in Dokumentstruktur** Eine Veröffentlichungsaktion ist im vorhandenen Element-Aktionsmenü eines oder mehrerer ausgewählter Dokumente mit gemeinsamen Revisionen verfügbar.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/10-publish-shared-revisions.png)

**Einzelne Revision in Dokumentvorschau oder Dokumentstruktur** Eine Veröffentlichungsaktion ist als Symbol und im Aktionsmenü der Revisionsinformationen einer gemeinsamen Revision im rechten Informationsmenü verfügbar.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/11-publish-shared-revisions.png)

**Mehrere Modelle** Eine Veröffentlichungsaktion ist in den Revisionsinformationen eines Dokuments mit einer gemeinsamen Revision im rechten Informationsmenü in der Dokumentstruktur und in der Dokumentvorschau verfügbar.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/12-publish-shared-revisions.png)

_Erforderlicher Zugriff:_ Gemeinsame Revisionen

### 3.5 **Zugriffskontrolle**

Nach der Aktivierung des Status-Workflows sehen Sie zwei neue Spalten rechts neben der Zugriffsspalte im Zugriffskontrolldialog eines Ordners oder Dokuments.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/13-access-control.png)

Die folgende Tabelle erläutert, wie die Kontrollkästchen die Benutzererfahrung für jede Zugriffsstufe beeinflussen.

- Aktivieren Sie "Veröffentlichung möglich" für ein Mitglied oder Team mit Schreibzugriff, um ihnen die Veröffentlichung gemeinsamer Revisionen und die Bearbeitung veröffentlichter Revisionsstatus zu ermöglichen.
- Deaktivieren Sie "Gemeinsame Revisionen anzeigen" für ein Mitglied oder Team mit Lesezugriff, damit diese nur offizielle, veröffentlichte Revisionen sehen.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><h3 id="h_e9579ad9ca"><b>Gemeinsam veröffentlichter Zugriff</b></h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_dea1580c70">Lesen</h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_3c6b6d7d28">Schreiben</h3></td></tr><tr><td><h3 id="h_a33339c27e">Kann "Gemeinsame Revisionen anzeigen" aktivieren</h3></td><td><p class="intercom-align-center">Kann aktivieren. <br/>Standardmäßig deaktiviert.</p></td><td><p class="intercom-align-center">Immer aktiviert</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_e909b5dc48">Kann "Veröffentlichung möglich" aktivieren</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Nie aktiviert</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Kann deaktivieren. <br/>Standardmäßig aktiviert</p></td></tr><tr><td><h3 id="h_95374b8adf">Dokumente anzeigen</h3></td><td><p class="intercom-align-center">Dokumente, die nur gemeinsame Revisionen enthalten, sind nur sichtbar, wenn "Gemeinsame Revisionen anzeigen" aktiviert ist</p></td><td><p class="intercom-align-center">Sowohl Dokumente mit gemeinsamen als auch Dokumente mit veröffentlichten Revisionen sind sichtbar</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_e401f7a37f">Gemeinsame Revisionen in Dokumentinfo anzeigen</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Gemeinsame Revisionen sind nur sichtbar, wenn "Gemeinsame Revisionen anzeigen" aktiviert ist</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Sowohl gemeinsame als auch veröffentlichte Revisionen sind sichtbar</p></td></tr><tr><td><h3 id="h_13cbc969df">Gemeinsame Revisionsstatus bearbeiten und anzeigen</h3></td><td><p class="intercom-align-center">Wird angezeigt, wenn "Gemeinsame Revisionen anzeigen" aktiviert ist, wird aber nicht bearbeitet</p></td><td><p class="intercom-align-center">x</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_b228d7c432">Veröffentlichte Revisionsstatus bearbeiten und anzeigen</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Kann nur veröffentlichte Revisionsstatus anzeigen</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Bearbeiten, wenn "Veröffentlichung möglich" aktiviert ist, sonst nur Ansicht</p></td></tr><tr><td><h3 id="h_13248acfd2">Dokumente veröffentlichen</h3></td><td><p class="intercom-align-center">-</p></td><td><p class="intercom-align-center">Veröffentlichen, wenn "Veröffentlichung möglich" aktiviert ist</p></td></tr></tbody></table></div>

### 3.6 **Haupt- und Nebenversionsnummern**

Gemeinsame Revisionen haben eine Nebenversionsnummer (z.B. #0,1, #2,3, #4,1). Veröffentlichte Revisionen haben eine Hauptversionsnummer (#1, #2, #3 usw.)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/14-major-and-minor-revision-numbers.png)

### 3.7 Dokumentvorschau öffnen

In der Dokumentstruktur sehen Sie die neueste Revision, auf die Sie Zugriff haben. Klicken Sie auf den Namen eines Dokuments, um die Dokumentvorschau der angezeigten Revision zu öffnen.

**Arbeitsbereichsregisterkarte** Die neueste Revision in der Arbeitsbereichsregisterkarte kann sein: Gemeinsame Revision - _Erforderlicher Zugriff:_ Gemeinsame Revisionen Veröffentlichte Revision - _Erforderlicher Zugriff:_ Lesen

**Registerkarte Veröffentlicht** Die neueste Revision in der Registerkarte "Veröffentlicht" kann sein: Veröffentlichte Revision - _Erforderlicher Zugriff:_ Lesen

> **Hinweis:** Gemeinsame Revisionen können in der Revisionsübersicht der Dokumentvorschau sichtbar sein, auch wenn Sie das Dokument von der veröffentlichten Registerkarte geöffnet haben. _Erforderlicher Zugriff:_ Gemeinsame Revisionen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/15-opening-the-document-preview.png)

### 3.8 **Revisionsinformationen**

Wählen Sie ein einzelnes Dokument aus oder öffnen Sie die Dokumentvorschau, indem Sie auf das Dokument klicken. Informationen zur aktuellen Revision werden im [rechten Informationsmenü](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision) angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/16-revision-information.png)

- Veröffentlichen Sie die aktuelle Revision mit der Veröffentlichungsaktion.
  _Erforderlicher Zugriff:_ Gemeinsame Revisionen

- Ändern Sie einen gemeinsamen Revisionsstatus in einen anderen gemeinsamen Revisionsstatus.
  _Erforderlicher Zugriff:_ Lesezugriff und gemeinsame Revisionen

- Ändern Sie einen veröffentlichten Revisionsstatus in einen anderen veröffentlichten Revisionsstatus.
  _Erforderlicher Zugriff:_ Schreibzugriff und veröffentlichte Revisionen

**Revisionsinformationsdialog** Klicken Sie auf das Revisionsfeld, um einen Überblick über alle Revisionen im Dokument im [Revisionsinformationsdialog](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision#h_6838c6ad71) zu sehen. Ein grüner Link zwischen einer veröffentlichten und einer gemeinsamen Revision zeigt an, welche gemeinsame Revision veröffentlicht wurde.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/17-revision-information.png)

### 3.9 Gemeinsame und veröffentlichte Revisionen in Catenda Site

In Catenda Site sind nur veröffentlichte Revisionen sichtbar.

## 4. Zugriff auf Statuskonfiguration

1. Der Bearbeitungszugriff auf die Dokumentstatuskonfiguration kann auf der [Projekteinstellungsseite](https://support.catenda.com/en/articles/4670273-project-settings-page) konfiguriert werden:

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-868820a898ba.png" width="500"/></div>

2. Der Dokumentstatus kann dann von den Einstellungen im Dokumentbereich [konfiguriert](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) werden:

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-931418a5fab1.png" width="500"/></div>

3. Schließlich können diese Dokumentstatus dem DateiBewertungsstatus zugeordnet werden, auf den über die Schaltfläche mit den drei Punkten oben rechts im [Abschnitt "Genehmigungen"](https://support.catenda.com/en/articles/8349340-approvals-page) zugegriffen werden kann. Es ist auch möglich, hier eine Themenvorlage zu konfigurieren.

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-3cdbebefca38.png" width="500"/></div>

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-f8ab7f3194ff.png" width="300"/></div>

## 5. **Genehmigungsworkflow**

1. Ein Genehmigungsworkflow wird von einem Administrator erstellt.
   1. Einreicher-Team
   2. Überprüfer-Team (mindestens ein Genehmigungsschritt ist erforderlich)
   3. Endgültiges Überprüfer-Team
2. Ein Mitglied eines Einreicher-Teams reicht eine Genehmigungsanfrage mit einem Satz gemeinsamer Revisionen auf der Seite "Genehmigungen" ein.
3. Mitglieder der dem Schritt zugeordneten Einreicher-Teams überprüfen die bei der Genehmigung eingereichten Dokumente und geben entweder eine genehmigte oder abgelehnte Validierung ab.
4. Nach Abschluss aller Schritte überprüft ein Mitglied des endgültigen Überprüfer-Teams die Validierungen, die im Namen der verschiedenen Teams in jedem Schritt eingereicht wurden, und gibt ihre endgültige Validierung genehmigt, genehmigt mit Kommentar oder abgelehnt ab.
   1. Der endgültige Genehmiger kann eine endgültige, fundierte Entscheidung treffen, ob dieses Dokument veröffentlicht (genehmigt) oder abgelehnt werden sollte (gemeinsam bleiben)

### 5.1 **Legacy-Genehmigungsworkflow**

1. Eine Genehmigungsanfrage benennt einen Herausgeber (Person, die für die endgültige Entscheidung über die Veröffentlichung verantwortlich ist) und einen oder mehrere Prüfer, die für die Validierung (oder nicht) des Dokument-Sets verantwortlich sind
2. Jeder Prüfer entscheidet, ob das gemeinsame Dokument genehmigt, genehmigt mit Kommentar oder abgelehnt wird
3. Am Ende der Überprüfung wählt der Herausgeber das Ergebnis der Genehmigung, indem er die zu veröffentlichenden Dokumente auswählt.
4. In den Genehmigungseinstellungen können mit den Dokumenten verbundene Themen erstellt werden, um den Prozess später nachzuverfolgen

Eine detaillierte Demonstration dieser Schritte wird im folgenden Tutorial gezeigt:

[YouTube-Video](https://www.youtube.com/embed/lDWKXWTtegU?rel=0)

## 6. **Status-Workflow deaktivieren**

Wenn Sie den Status-Workflow deaktivieren möchten, können Sie dies tun, indem Sie das Optionsfeld in den [Dokumenteinstellungen](https://support.catenda.com/en/articles/7831371-document-settings) aktivieren. Die veröffentlichten und gemeinsamen Registerkarten im Dokumentbereich werden dann ausgeblendet. Dokumente, die während der Deaktivierung des Status-Workflows hochgeladen werden, werden als veröffentlicht hochgeladen und werden in der veröffentlichten Registerkarte angezeigt, wenn der Status-Workflow erneut aktiviert wird.

## 7. **Vorteile der Verwendung des Status-Workflows**

- Die veröffentlichte Registerkarte dient als designated Bereich für Vertragsdokumente. Projektmitglieder können überprüfte Dokumente leicht finden.
- Dokumente werden vor der Veröffentlichung validiert
- Sie können Ihren Lieferprozess basierend auf ISO 19650 viel einfacher konfigurieren
- Koordinations-/Zusammenarbeitsdokumente sind von Vertragsdokumenten getrennt
- Mehrere gemeinsame Revisionen können ausgewählt und heruntergeladen werden, wobei in der vorherigen Version Entwürfe nur einzeln heruntergeladen werden konnten
- Beschränken Sie, was Personen in der mobilen App Catenda Site sehen können
