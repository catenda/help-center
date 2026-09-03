# Neuer Status-Workflow - ISO 19650

Der neue Status-Workflow ist eine bedarfsgesteuerte Funktion, die für laufende Projekte angefordert werden kann. Neue Projekte, die auf der Basis eines Vorlagenprojekts erstellt werden, bei dem diese Funktion aktiviert ist, haben diese Funktion aktiviert. Die ISO-19650-Serie ist ein internationaler Standard für Best Practices, der Informationsmanagementsysteme im breiteren Kontext der digitalen Transformation in der Bauindustrie definiert. Viele Stakeholder in der Bauindustrie haben die ISO-19650 als Standard zur Verwaltung von Dokumentenlieferungs- und Genehmigungsprozessen in Projekten eingeführt.

## 1. **Lebenszyklus eines Dokuments**

Nach dem ISO-Standard kann ein Dokument vier verschiedene Zustände haben;

### 1.1 **🏗️ Arbeit in Bearbeitung (WiP)**

Dateien, an denen gearbeitet wird und die in der lokalen Umgebung des Benutzers ständig überschrieben werden. Diese Dateien werden in der Regel nur in Catenda hochgeladen, damit Personen den Fortschritt des Benutzers sehen können.

### 1.2 **👥 Geteilt**

Dateien, die bereit sind, mit anderen Projektmitgliedern geteilt zu werden, um Abstimmungen und abschließende Überprüfungen verschiedener Gewerke und/oder Fachleute vorzunehmen. Diese Dateien werden in Catenda hochgeladen und an die jeweiligen Parteien zur Überprüfung und Genehmigung gesendet.

### 1.3 **📰 Veröffentlicht**

Dateien, die koordiniert, finalisiert und als vertragliche Liefergegenstände akzeptiert wurden. Diese Dateien haben einen Überprüfungsprozess durchlaufen und gelten als "bereit für die nächste Phase (Konstruktion, Übergabe, Mengenaufnahme, Genehmigungserteilung, usw.)"

### 1.4 **📦 Archiviert**

Die Informationen wurden verwendet und können archiviert werden, um bei Bedarf später noch verfügbar zu sein (Audit, Erstellung der Akte der durchgeführten Arbeiten, etc.)

### 1.5 **Dokumentzustände - ISO 19650**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/01-document-states-iso-19650.png)

### 1.6 **Workflow in Catenda Hub**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/02-workflow-on-catenda-hub.png)

## 2. **Status-Workflow konfigurieren**

Die Aktivierung und Konfiguration des freigegebenen Status-Workflows sind für Projektadministratoren reserviert.

_Zugriff erforderlich_ Konfigurationszugriff für den Dokumentstatus im [Zugriffssteuerungsbereich](https://support.catenda.com/en/articles/4670273-project-settings-page#h_3b98ced32a) der [Projekteinstellungsseite](https://support.catenda.com/en/articles/4670273-project-settings-page). Mitglieder mit diesem Zugriff haben nur Zugriff auf das Status-Konfigurationsmenü in den Dokumenteinstellungen. Sie können die anderen Menüs in den Dokumenteinstellungen nicht sehen oder ändern.

Navigieren Sie unter [Dokumenteinstellungen](https://support.catenda.com/en/articles/7831371-document-settings) zu [Status-Workflow](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) und aktivieren Sie freigegebene Status

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/03-configuring-status-workflow.png)

Definieren Sie die freigegebenen und veröffentlichten Status, die im Projekt verwendet werden sollen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/04-configuring-status-workflow.png)

Legen Sie den Standard-Freigabestatus für neue Revisionen fest. Neue Revisionen werden zunächst als freigegebene Revisionen hochgeladen, die später veröffentlicht werden können. Der Standardstatus muss daher ein freigegebener Revisionsstatus sein. Dieser Status wird in der Upload-Dialogfeld für jeden Dokumentupload ausgewählt und kann während des Upload-Prozesses in einen anderen freigegebenen Status geändert werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/05-configuring-status-workflow.png)

## 3. **Vertraut, aber anders**

Nach der Aktivierung des Status-Workflows werden über den Tabellen mit Dokumenten und Modellen zwei Registerkarten angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/06-familiar-but-different.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/07-familiar-but-different.png)

### 3.1 **Arbeitsbereich**

Alle Uploads neuer Revisionen erfolgen hier. Die neueste freigegebene Revision wird für jedes Dokument und Modell angezeigt.

### 3.2 **Veröffentlicht**

Eine gespiegelte Version der Arbeitsbereich-Registerkarte. Die gleiche Ordnerstruktur wie im Arbeitsbereich wird angezeigt. Es werden nur Dokumente und Modelle mit veröffentlichten Revisionen angezeigt.

> **Hinweis:** Freigegebene Revisionen in der Revisionsübersicht der Dokumentvorschau anzeigen, auch wenn Sie das Dokument auf der Registerkarte "Veröffentlicht" geöffnet haben. _Zugriff erforderlich:_ Freigegebene Revisionen

### 3.3 **Neue freigegebene Revisionen hochladen**

Der Revisionsstatus wird für jede hochgeladene Datei in der Upload-Dialogfeld angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/08-upload-new-shared-revisions.png)

Der Revisionsstatus wird für jede aus einer gezippten Datei extrahierte Datei angewendet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/09-upload-new-shared-revisions.png)

### 3.4 Freigegebene Revisionen veröffentlichen

**Mehrere Dokumente in der Dokumentstruktur** Eine Veröffentlichungsaktion steht im vorhandenen Elementaktionsmenü eines oder mehrerer ausgewählter Dokumente mit freigegebenen Revisionen zur Verfügung.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/10-publish-shared-revisions.png)

**Einzelne Revision in Dokumentvorschau oder Dokumentstruktur** Eine Veröffentlichungsaktion ist als Symbol und im Aktionsmenü der Revisionsinformation einer freigegebenen Revision im rechten Informationsmenü verfügbar.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/11-publish-shared-revisions.png)

**Mehrere Modelle** Eine Veröffentlichungsaktion steht in den Revisionsinformationen eines Dokuments mit einer freigegebenen Revision im rechten Informationsmenü in der Dokumentstruktur und in der Dokumentvorschau zur Verfügung.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/12-publish-shared-revisions.png)

_Zugriff erforderlich:_ Freigegebene Revisionen

### 3.5 **Zugriffssteuerung**

Nach der Aktivierung des Status-Workflows werden rechts neben der Zugriffsspalte in der Zugriffssteuerdialogfeld eines Ordners oder Dokuments zwei neue Spalten angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/13-access-control.png)

Die folgende Tabelle erläutert, wie die Häkchen die Benutzererfahrung für jede Zugriffsstufe beeinflussen.

- Aktivieren Sie "Kann veröffentlichen" für ein Mitglied oder Team mit Schreibzugriff, um ihnen das Veröffentlichen von freigegebenen Revisionen und das Bearbeiten von veröffentlichten Revisionsstatus zu ermöglichen.
- Deaktivieren Sie "Freigegebene Revisionen anzeigen" für ein Mitglied oder Team mit Lesezugriff, damit sie nur offizielle, veröffentlichte Revisionen sehen.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><h3 id="h_e9579ad9ca"><b>Freigegeben Veröffentlichter Zugriff</b></h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 class="intercom-align-center" id="h_dea1580c70">Lesen</h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 class="intercom-align-center" id="h_3c6b6d7d28">Schreiben</h3></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_a33339c27e">Kann "Freigegebene Revisionen anzeigen" aktivieren</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Kann aktiviert werden. <br/>Standardmäßig deaktiviert.</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Immer aktiviert</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_e909b5dc48">Kann "Kann veröffentlichen" aktivieren</h3></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Nie aktiviert</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Kann deaktiviert werden. <br/>Standardmäßig aktiviert</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_95374b8adf">Dokumente anzeigen</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Dokumente mit nur freigegebenen Revisionen sind nur sichtbar, wenn "Freigegebene Revisionen anzeigen" aktiviert ist</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Sowohl Dokumente mit freigegebenen als auch Dokumente mit veröffentlichten Revisionen sind sichtbar</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_e401f7a37f">Freigegebene Revisionen in Dokumentinformationen anzeigen</h3></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Freigegebene Revisionen sind nur sichtbar, wenn "Freigegebene Revisionen anzeigen" aktiviert ist</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Sowohl freigegebene als auch veröffentlichte Revisionen sind sichtbar</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_13cbc969df">Freigegebene Revisionsstatus bearbeiten und anzeigen</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Angezeigt, wenn "Freigegebene Revisionen anzeigen" aktiviert ist, aber nicht bearbeitet</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_b228d7c432">Veröffentlichte Revisionsstatus bearbeiten und anzeigen</h3></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Kann nur veröffentlichten Revisionsstatus anzeigen</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Bearbeiten, wenn "Kann veröffentlichen" aktiviert ist, andernfalls nur zur Anzeige</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_13248acfd2">Dokumente veröffentlichen</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Veröffentlichen, wenn "Kann veröffentlichen" aktiviert ist</p></td></tr></tbody></table></div>

### 3.6 **Haupt- und Nebenversionsnummern**

Freigegebene Revisionen haben eine Nebenversionsnummer (z. B. #0.1, #2.3, #4.1) Veröffentlichte Revisionen haben eine Hauptversionsnummer (#1, #2, #3 und so weiter)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/14-major-and-minor-revision-numbers.png)

### 3.7 Dokumentvorschau öffnen

In der Dokumentstruktur wird die neueste Revision angezeigt, auf die Sie Zugriff haben. Klicken Sie auf den Namen eines Dokuments, um die Dokumentvorschau der angezeigten Revision zu öffnen.

**Arbeitsbereich-Registerkarte** Die neueste Revision in der Arbeitsbereich-Registerkarte kann sein: Freigegebene Revision - _Zugriff erforderlich:_ Freigegebene Revisionen Veröffentlichte Revision - _Zugriff erforderlich:_ Lesen

**Registerkarte "Veröffentlicht"** Die neueste Revision auf der Registerkarte "Veröffentlicht" kann sein: Veröffentlichte Revision - _Zugriff erforderlich:_ Lesen

> **Hinweis:** Freigegebene Revisionen können in der Revisionsübersicht der Dokumentvorschau sichtbar sein, auch wenn Sie das Dokument auf der Registerkarte "Veröffentlicht" geöffnet haben. _Zugriff erforderlich:_ Freigegebene Revisionen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/15-opening-the-document-preview.png)

### 3.8 **Revisionsinformationen**

Wählen Sie ein einzelnes Dokument aus oder öffnen Sie die Dokumentvorschau, indem Sie auf das Dokument klicken. Informationen zur aktuellen Revision werden im [rechten Informationsmenü](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision) angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/16-revision-information.png)

- Veröffentlichen Sie die aktuelle Revision mit der Veröffentlichungsaktion.
  _Zugriff erforderlich:_ Freigegebene Revisionen

- Ändern Sie einen Freigabe-Revisionsstatus in einen anderen Freigabe-Revisionsstatus.
  _Zugriff erforderlich:_ Lesezugriff und freigegebene Revisionen

- Ändern Sie einen veröffentlichten Revisionsstatus in einen anderen veröffentlichten Revisionsstatus.
  _Zugriff erforderlich:_ Schreibzugriff und veröffentlichte Revisionen

**Revisionsinformations-Dialogfeld** Klicken Sie auf das Revisionsfeld, um eine Übersicht aller Revisionen des Dokuments in der [Revisionsinformations-Dialogfeld](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision#h_6838c6ad71) anzuzeigen. Ein grüner Link zwischen einer veröffentlichten und einer freigegebenen Revision zeigt an, welche freigegebene Revision veröffentlicht wurde.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/17-revision-information.png)

### 3.9 Freigegebene und veröffentlichte Revisionen in Catenda Site

Nur veröffentlichte Revisionen sind in Catenda Site sichtbar.

## 4. Status-Konfigurationszugriff

1. Der Bearbeitungszugriff auf die Dokumentstatus-Konfiguration kann auf der [Projekteinstellungsseite](https://support.catenda.com/en/articles/4670273-project-settings-page) konfiguriert werden:

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-868820a898ba.png" width="500"/></div>

1. Der Dokumentstatus kann dann [konfiguriert](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) von den Einstellungen im Dokumente-Abschnitt aus konfiguriert werden:

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-931418a5fab1.png" width="500"/></div>

1. Schließlich kann dieser Dokumentstatus dem Dateiüberprüfungsstatus zugewiesen werden, auf den über die Schaltfläche mit drei Punkten oben rechts im [Genehmigungsabschnitt](https://support.catenda.com/en/articles/8349340-approvals-page) zugegriffen werden kann. Es ist auch möglich, hier eine Topic-Vorlage zu konfigurieren.

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-3cdbebefca38.png" width="500"/></div>

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-f8ab7f3194ff.png" width="300"/></div>

## 5. **Genehmigungsworkflow**

1. Ein Genehmigungsworkflow wird von einem Administrator erstellt.
   1. Einreichungs-Team
   1. Überprüfungs-Team (mindestens ein Genehmigungsschritt erforderlich)
   1. Team der endgültigen Überprüfer
1. Ein Mitglied eines Einreichungsteams reicht einen Genehmigungsantrag mit einer Reihe von freigegebenen Revisionen auf der Genehmigungsseite ein.
1. Mitglieder der Einreichungsteams, die dem Schritt zugewiesen sind, überprüfen die in der Genehmigung eingereichten Dokumente und geben entweder eine genehmigte oder abgelehnte Validierung ab.
1. Nachdem alle Schritte abgeschlossen sind, überprüft ein Mitglied des Teams der endgültigen Überprüfer die Validierungen, die im Namen der verschiedenen Teams in jedem Schritt eingereicht wurden, und gibt seine endgültige Validierung von genehmigt, mit Kommentar genehmigt oder abgelehnt ab.
   1. Der endgültige Genehmiger kann eine endgültige, informierte Entscheidung treffen, ob dieses Dokument veröffentlicht (genehmigt) oder abgelehnt (als freigegeben verbleibend) werden soll

### 5.1 **Legacy-Genehmigungsworkflow**

1. Ein Genehmigungsantrag benennt einen Verleger (Person, die für die endgültige Entscheidung über die Veröffentlichung zuständig ist) und einen oder mehrere Überprüfer, die für die Validierung (oder nicht) des Dokumentensatzes zuständig sind
1. Jeder Reviewer entscheidet, ob das freigegebene Dokument genehmigt, mit Kommentar genehmigt oder abgelehnt wird
1. Am Ende der Überprüfung wählt der Publisher das Ergebnis der Genehmigung aus, indem er die zu veröffentlichenden Dokumente auswählt.
1. Aus den Genehmigungseinstellungen können Themen im Zusammenhang mit den Dokumenten erstellt werden, um den Prozess später nachverfolgen zu können

Eine detaillierte Demonstration dieser Schritte wird im folgenden Tutorial gezeigt:

[YouTube-Video](https://www.youtube.com/embed/lDWKXWTtegU?rel=0)

## 6. **Status-Workflow deaktivieren**

Wenn Sie den Status-Workflow ausschalten möchten, können Sie dies tun, indem Sie auf das Optionsfeld in den [Dokumenteinstellungen](https://support.catenda.com/en/articles/7831371-document-settings) klicken. Die veröffentlichten und freigegebenen Registerkarten im Dokumentabschnitt werden dann verschwinden. Dokumente, die hochgeladen werden, während der Status-Workflow nicht aktiviert ist, werden als veröffentlicht hochgeladen und werden auf der Registerkarte "Veröffentlicht" angezeigt, wenn der Status-Workflow aktiviert wird.

## 7. **Vorteile der Verwendung des Status-Workflows**

- Die Registerkarte "Veröffentlicht" dient als ausgewiesener Bereich für vertragliche Dokumente. Projektmitglieder können überprüfte Dokumente leicht finden.
- Dokumente werden vor der Veröffentlichung validiert
- Sie können Ihren Lieferprozess basierend auf der ISO 19650 viel leichter konfigurieren
- Koordinations-/Kollaborationsdokumente sind von vertraglichen Dokumenten getrennt
- Mehrere freigegebene Revisionen können ausgewählt und heruntergeladen werden, während in der vorherigen Version Entwürfe nur einzeln heruntergeladen werden konnten
- Begrenzen Sie, was Personen in der mobilen App Catenda Site sehen können
