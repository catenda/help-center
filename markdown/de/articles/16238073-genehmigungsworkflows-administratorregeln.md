# Genehmigungsworkflows: Administratorregeln

> Leitfaden für Administratoren mit Details zu Einrichtungsregeln, flexiblen Konfigurationsoptionen, Sperren von Parametern nach Einreichung und wie sich Projektmitteilungsänderungen auf aktive Genehmigungsanfragen auswirken.

Genehmigungsworkflows etablieren strukturierte Review- und Validierungsprozesse für freigegebene Dokumentrevisionen innerhalb eines Projekts. Die Konfiguration von Workflows erfordert ein Abwägen von Vorlagenregeln für zukünftige Reviewanfragen mit Projektteam-Setups, die aktive laufende Genehmigungen antreiben.

> **Hinweis:** Nur Projektadministratoren können auf Workflow-Konfigurationseinstellungen zugreifen, neue Genehmigungsworkflows erstellen oder vorhandene Workflow-Parameter ändern.

## 1. **1. Wie sich Projektänderungen auf Genehmigungsworkflows auswirken**

Wenn eine Workflow-Vorlage geändert oder Projektkonfigurationen angepasst werden (z. B. durch Hinzufügen oder Entfernen von Team-Mitgliedern in Projekteinstellungen), wirken sich die Änderungen auf zukünftige und laufende Genehmigungsanfragen unterschiedlich aus:

### 1.1 **1.1 Bearbeitungen von Workflow-Vorlagen**

Änderungen an einer Workflow-Vorlage (z. B. das Hinzufügen von Absender-Teams) gelten für **zukünftige** Genehmigungsanfragen, die nach der Aktualisierung erstellt werden. Sie schreiben nicht die Struktur von bereits laufenden aktiven Anfragen um.

### 1.2 **1.2 Team-Mitgliedschaftsaktualisierungen**

Das Hinzufügen oder Entfernen von Team-Mitgliedern in Projekteinstellungen wird sofort auf **aktive laufende** Genehmigungen angewendet. Wenn ein Review-Schritt steckenbleibt, weil ein Team leer ist, kann das Hinzufügen eines Benutzers zu diesem Team diesem ermöglichen, sofort einzugreifen und den Review fortzusetzen.

### 1.3 **1.3 Unterbrochene Abhängigkeiten**

Das Archivieren eines Dokumentstatus, das Entfernen eines Teams oder das Archivieren einer Genehmigungsthema-Vorlage an anderer Stelle in den Projekteinstellungen kann zu Validierungsfehlern beim Speichern von Workflow-Updates führen oder die Themenerstellung bei laufenden Genehmigungen unterbrechen.

## 2. **Setup vor Einreichung (Anfangserstellung)**

Wenn ein neuer Genehmigungsworkflow zum ersten Mal erstellt wird, müssen alle grundlegenden Parameter konfiguriert werden, bevor die Vorlage gespeichert und aktiviert werden kann.

### 2.1 **2.1 Erforderliche Felder und Warnbanner vor Einreichung**

Wenn bei dem Versuch, einen neuen Workflow zu speichern, ein erforderliches Feld unvollständig ist, zeigt das System ein Warnbanner vor der Einreichung oben auf der Seite an und blockiert die Vorlagenerstellung. Erforderliche Felder umfassen:

- **2.1.1 Workflow-Titel**
  Ein eindeutiger, beschreibender Name für den Workflow.
- **2.1.2 Absender-Teams**
  Mindestens ein Projektteam, das zum Starten von Genehmigungsanfragen zugewiesen ist.
- **2.1.3 Review-Schritte**
  Mindestens ein Review-Schritt mit einem zugeordneten Reviewer-Team und einer Dauer von mindestens **1 Arbeitstag**.
- **2.1.4 Endgültige Genehmigung**
  Ein zugeordnetes finales Review-Team zusammen mit zwei aktiven Projektdokumentstatus – einer für genehmigte Revisionen und einer für abgelehnte Revisionen zugeordnet.

### 2.2 **2.2 Systemlimits und Team-Mitgliedschaftsregeln**

**2.2.1 Pipeline-Limits** Ein einzelner Workflow unterstützt bis zu **10 sequenzielle Review-Schritte** und insgesamt **20 Reviewer-Teams** über die Pipeline.

**2.2.2 Team-Auswahl gegenüber Mitgliederpräsenz** Während der anfänglichen Erstellung validiert das System, dass Absender-, Reviewer- und Final-Reviewer-Teams ausgewählt werden. Es **überprüft jedoch nicht**, ob diese Teams tatsächliche Mitglieder enthalten.

**2.2.3 Ausführungsanforderungen und automatische Genehmigung** Um eine Genehmigungsanfrage von Anfang bis Ende durchführbar zu machen:

- Mindestens ein Absender-Team-Mitglied muss in einem zugeordneten Absender-Team vorhanden sein, um die Anfrage zu starten.
- Mindestens ein Reviewer-Team-Mitglied muss in einem zugeordneten Reviewer-Team vorhanden sein, es sei denn, die automatische Genehmigung ist für diesen Schritt aktiviert.
- Wenn die automatische Genehmigung konfiguriert ist, genehmigt ein Schritt, der einem leeren Team zugeordnet ist, automatisch und wird fortgesetzt, sobald das Schritt-Fälligkeitsdatum erreicht ist.
- Wenn die automatische Genehmigung nicht konfiguriert ist, bleibt eine leere Reviewer-Team die Genehmigungsanfrage stecken, bis ein Mitglied diesem Team hinzugefügt wird.
- Mindestens ein finales Reviewer-Team-Mitglied muss vorhanden sein, um das endgültige Ergebnis zu erteilen.

**2.2.4 Administratorrechte** Projektadministratoren haben keine automatischen Betriebsrechte. Um während einer Genehmigung Aktionen auszuführen, muss ein Administrator ein explizites Mitglied des relevanten Teams sein:

- **Absender-Team**
  Erforderlich, um eine Genehmigungsanfrage zu starten.
- **Reviewer-Team**
  Erforderlich, um eine Review-Validierung anzuzeigen oder einzureichen.
- **Finales Reviewer-Team**
  Erforderlich, um die endgültige Entscheidung zu treffen und die Genehmigung abzuschließen.

## 3. **3.** **Flexible Operationen (vor und nach Einreichung)**

Bestimmte Operationen bleiben flexibel und können während des anfänglichen Setups oder jederzeit nach der Aktivierung eines Workflows angepasst werden. Diese flexiblen Operationen fallen in zwei unterschiedliche Kategorien: **Workflow-Vorlageneinstellungen** (direkt auf der Workflow-Setup-Seite bearbeitet) **Verwaltung von Projektteam-Mitgliedern** (auf der Seite "Projektteams" über alle Workflow-Rollen bearbeitet).

### 3.1 **3.1** **Workflow-Vorlagenänderungen**

Diese Einstellungen können jederzeit im Workflow-Konfigurationsmenü geändert werden und wirken sich direkt auf zukünftige Genehmigungsanfragen aus:

**3.1.1 Absender-Teams** Administratoren können nach der Einreichung Absender-Teams hinzufügen oder entfernen, um zu steuern, welche Projektteams berechtigt sind, neue Genehmigungsanfragen unter diesem Workflow zu starten.

**3.1.2 Genehmigungsthema-Vorlagen** Genehmigungsthema-Vorlagen, die mit spezifischen Ergebnissen verknüpft sind (_Genehmigt_, _Mit Kommentaren genehmigt_ oder _Abgelehnt_), können jederzeit hinzugefügt, aktualisiert oder entfernt werden, um die Problem-Verfolgung während Reviews zu steuern.

### 3.2 **3.2** **Verwaltung von Projektteam-Mitgliedern (gilt für alle Team-Typen)**

Das Hinzufügen oder Entfernen einzelner Benutzer findet auf der Seite **Projektteams** statt und erfordert nicht die Bearbeitung oder erneutes Speichern der Workflow-Vorlage. Entscheidend ist, dass die Mitgliederverwaltung auf **alle drei Workflow-Team-Typen** angewendet wird und direkt beeinflusst, wer Aktionen ausführen kann:

**3.2.1 Absender-Teams** Das Hinzufügen oder Entfernen von Mitgliedern ändert, wer den Workflow auswählen kann, um neue Genehmigungsanfragen zu starten.

**3.2.2 Reviewer-Teams** Das Hinzufügen oder Entfernen von Mitgliedern ändert, wer auf aktive Review-Schritte zugreifen, Markierungen/Kommentare hinzufügen und Schritt-Validierungsanzeigen einreichen kann.

**3.2.3 Finale Reviewer-Teams** Das Hinzufügen oder Entfernen von Mitgliedern ändert, wer die endgültige Entscheidung treffen und eine aktive Genehmigungsanfrage abschließen kann.

## 4. **4.** **Regeln nach Einreichung und Parametersperren**

Sobald eine Workflow-Vorlage zum ersten Mal gespeichert und eingereicht wird, sperren Schlüsselstrukturparameter, um konsistente Evaluierungsregeln über Genehmigungsanfragen sicherzustellen.

### 4.1 **4.1 Gesperrte gegenüber bearbeitbaren Parametern**

**4.1.1 Gesperrte Parameter** Zeiteinstellungen, Review-Schritte, zugeordnete Reviewer-Teams, Schritt-Dauern, automatische Genehmigungsumschaltungen, Endgültige-Genehmigungs-Teams und zugeordnete abschließende Dokumentstatus können nach der anfänglichen Einreichung nicht mehr geändert werden.

**4.1.2 Bearbeitbare Parameter** Nur der Workflow-Titel, die Absender-Team-Zuordnungen und die verknüpften Genehmigungsthema-Vorlagen bleiben nach der Einreichung bearbeitbar.

### 4.2 **4.2 Unterbrochene externe Abhängigkeiten und Resolutionen**

Das Speichern **jeder** Bearbeitung nach der Einreichung für einen vorhandenen Workflow (z. B. das Aktualisieren des Titels) löst eine vollständige Revalidierungsprüfung auf der gesamten Vorlage aus. Wenn ein Element, das im Workflow verwendet wird, nach der Anfangserstellung in den Projekteinstellungen archiviert oder gelöscht wurde, schlägt die Revalidierung fehl, bis es behoben wird.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 130px; padding: 8px;"><h3 id="h_5956ae53a6"><b>Abhängigkeitsproblem (Blockierer)</b></h3></td><td style="background-color: #e3e7fa80; width: 244px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_9b11612daf"><b>Auswirkung &amp; Systemverhalten</b></h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_f245fc1acb"><b>Lösung</b></h3></td></tr><tr><td style="background-color: #00000000; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_aac48f326c"><b>Archivierte Dokumentstatus</b></h3></td><td style="background-color: #00000000; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Das zugeordnete Statusfeld erscheint in der Workflow-Setup leer. Veröffentlichte Dokumente erhalten den archivierten Status (angezeigt als durchgestrichen). Workflow-Updates sind blockiert.</p></td><td style="background-color: #00000000; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Status wiederherstellen (archivieren aufheben)</b> in Dokumenteinstellungen.<br/>Gesperrte Status können innerhalb des Workflows nicht bearbeitet oder ersetzt werden nach der Einreichung.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_c963d16fb5"><b>Gelöschte Projektteams</b></h3></td><td style="background-color: #e8e8e880; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ein Absender-, Reviewer- oder Endgültige-Genehmigungs-Team wurde auf der Seite "Projektteams" gelöscht.</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Absender-Teams</b><br/>Bearbeiten Sie den Workflow direkt, um ein neues aktives Team zuzuordnen.<br/>​</p><p><b>Reviewer-/Endteams</b><br/>Gesperrt. Wenn in einem Schritt keine Teams verbleiben und die automatische Genehmigung ausgeschaltet ist, stagnieren laufende Genehmigungen für immer. Archivieren Sie den Workflow, verwerfen Sie Dokumente und erstellen Sie einen neuen Workflow.</p></td></tr><tr><td style="background-color: #00000000; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_8d948d5649"><b>Archivierte Genehmigungsthema-Vorlagen</b></h3></td><td style="background-color: #00000000; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Eine Genehmigungsthema-Vorlage, die mit einem Workflow-Ergebnis verknüpft ist, wurde auf der Seite "Thema-Vorlagen" archiviert.</p><p></p></td><td style="background-color: #00000000; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Wiederherstellen (archivieren aufheben)</b> die Vorlage auf der Seite "Thema-Vorlagen" <b>ODER</b> bearbeiten Sie den Workflow direkt, um eine neue aktive Ersatzvorlage auszuwählen/hinzuzufügen.</p></td></tr></tbody></table></div>

### 4.3 **4.3 Archivierung und Wiederherstellung von Workflows**

**4.3.1 Archivierung von Workflows** Verbirgt den aktiven Workflow aus Erstellungsmenüs, damit Projektmitglieder ihn nicht für neue Anfragen auswählen können.

**4.3.2 Wiederherstellung von Workflows** Reaktiviert einen archivierten Workflow in Erstellungsmenüs für zugeordnete Absender-Teams.

## 5. **5.** **Auswirkungen auf laufende Genehmigungen und Team-Lebenszyklen**

Wenn sich Projekteinstellungen oder Team-Mitgliedschaften ändern, während Genehmigungsanfragen aktiv laufen, behandelt das System Zugriff, Themenerstellung und Workflow-Fortschritt nach spezifischen Regeln.

### 5.1 **Hinzufügen und Entfernen von Team-Mitgliedern**

Projektmitglieder können jederzeit auf der Seite **Projektteams** zu oder aus Workflow-Teams hinzugefügt oder entfernt werden, ohne die Workflow-Vorlage selbst zu bearbeiten.

**5.1.1 Absender-Team-Mitglieder** Das Hinzufügen eines Benutzers zu einem Absender-Team ermöglicht es ihm, zukünftig neue Anfragen zu erstellen. Die Absender-Team-Mitgliedschaft gewährt jedoch niemals gemeinsame Sichtbarkeit für von Teamkollegen erstellte Anfragen – der Zugriff auf eine eingereichte Anfrage bleibt streng persönlich für den einzelnen Ersteller.

**5.1.2 Reviewer-Team-Mitglieder** Das Hinzufügen eines Benutzers zu einem Reviewer-Team gewährt ihm sofort Zugriff auf aktive Genehmigungsanfragen, die derzeit bei diesem Review-Schritt sind. Das Entfernen aller Mitglieder aus einem Reviewer-Team friert laufende Anfragen bei diesem Schritt ein, bis ein neues Mitglied hinzugefügt wird – es sei denn, die **automatische Genehmigung** ist für diesen Schritt aktiviert, in diesem Fall wird die Anfrage automatisch genehmigt und fortgesetzt, wenn die Schritt-Frist verstreicht.

**5.1.3 Finale Reviewer-Team-Mitglieder** Das Hinzufügen eines Benutzers zu einem finalen Reviewer-Team gewährt ihm sofort Zugriff, um endgültige Entscheidungen zu laufenden Anfragen zu treffen, die den finalen Genehmigungsschritt erreichen. Das Entfernen aller Mitglieder aus einem finalen Reviewer-Team friert laufende Anfragen beim finalen Schritt ein, bis ein Benutzer hinzugefügt wird (die automatische Genehmigung ist nicht für finalen Review-Schritte verfügbar).

### 5.2 **5.2** **Löschen von Teams aus Projekteinstellungen**

Gelöschte Projektteams können nicht wiederhergestellt werden. Wenn ein Team, das einem Workflow zugeordnet ist, aus den Projekteinstellungen gelöscht wird, hängt die operative Auswirkung von der Rolle des Teams im Workflow-Lebenszyklus ab:

**5.2.1 Gelöschte Absender-Teams** Absender-Teams bleiben nach der Einreichung bearbeitbar. Ein Administrator kann die Workflow-Konfiguration direkt bearbeiten und ein neues aktives Absender-Team zuordnen.

**5.2.2 Gelöschte Reviewer-Teams** Review-Schritte sind nach der Einreichung gesperrt.

- **Wenn andere zugeordnete Teams verbleiben**
  Der Review-Schritt funktioniert weiterhin für die verbleibenden Teams.
- **Wenn keine Teams verbleiben und die automatische Genehmigung AKTIVIERT ist**
  Der Schritt genehmigt automatisch und wird fortgesetzt, sobald die Schrift-Frist verstreicht.
- **Wenn keine Teams verbleiben und die automatische Genehmigung DEAKTIVIERT ist**
  Laufende Genehmigungsanfragen stagnieren auf unbestimmte Zeit bei diesem Review-Schritt.

**5.2.3 Gelöschte Finale Reviewer-Teams** Finale Genehmigungs-Teams sind nach der Einreichung gesperrt, und die automatische Genehmigung ist **nicht** für Finale Review-Schritte verfügbar. Wenn alle Finalen Reviewer-Teams gelöscht werden, stagnieren laufende Genehmigungsanfragen auf unbestimmte Zeit.

**5.2.4 Empfohlene Aktion für steckengebliebene oder nicht abschließbare Workflows** Wenn ein Review-Schritt mit keinen verbleibenden Teams steckenbleibt (und die automatische Genehmigung ausgeschaltet ist), oder wenn alle Finalen Reviewer-Teams gelöscht werden, wird empfohlen, den fehlerhaften Genehmigungsworkflow zu archivieren und alle Dokumente streng aus offenen Genehmigungsanfragen zu verwerfen, die diesem spezifischen Workflow folgen. Optional kann ein neuer Genehmigungsworkflow erstellt werden, wenn ein Ersatz erforderlich ist.

### 5.3 **5.3** **Genehmigungsthema-Vorlage-Archivierung und Neukonfigurationsregeln**

Genehmigungsthema-Vorlagen werden separat für jedes Entscheidungsergebnis konfiguriert (z. B. _Genehmigt_, _Mit Kommentaren genehmigt_ oder _Abgelehnt_). Das System verarbeitet Änderungen an Genehmigungsthema-Vorlagen unabhängig pro Ergebnis:

**5.3.1 Ergebnis-spezifische Isolation** Die Archivierung oder Änderung einer Genehmigungsthema-Vorlage für ein Entscheidungsergebnis wirkt sich nur auf dieses spezifische Ergebnis aus. Alle anderen Ergebnisse mit intakter Genehmigungsthema-Vorlagen erstellen weiterhin Themen wie erwartet.

**5.3.2 Archivierung einer verknüpften Genehmigungsthema-Vorlage** Wenn eine Genehmigungsthema-Vorlage, die einem Ergebnis zugeordnet ist, archiviert wird, werden laufende Genehmigungsanfragen, die diesem Workflow folgen (und neue Anfragen, die eingereicht werden, während nicht verknüpft), **nicht** Themen generieren, wenn dieses Ergebnis ausgewählt wird.

**5.3.3 Wiederherstellung einer archivierten Genehmigungsthema-Vorlage** Die Wiederherstellung (Aufhebung der Archivierung) der ursprünglichen Genehmigungsthema-Vorlage aktiviert automatisch die Themenerstellung gemäß dieser Vorlage über alle zugeordneten Genehmigungsanfragen.

**5.3.4 Konfigurieren einer anderen Genehmigungsthema-Vorlage** Wenn ein Administrator den Workflow nach der Einreichung aktualisiert, um eine _verschiedene_ aktive Genehmigungsthema-Vorlage zuzuordnen, werden laufende Genehmigungsanfragen, die vor der Bearbeitung eingeleitet wurden, **nicht** Themen mit der neuen Vorlage generieren. Nur neue Genehmigungsanfragen, die nach der Neukonfiguration eingereicht werden, generieren Themen basierend auf der neu zugeordneten Vorlage.
