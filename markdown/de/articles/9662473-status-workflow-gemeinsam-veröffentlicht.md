# Status Workflow gemeinsam → veröffentlicht

## 1. **Verfügbarkeit in Projekten**

Der neue Status-Workflow ist eine On-Demand-Funktion, die für laufende Projekte aktiviert werden kann. Neue Projekte, die auf der Grundlage eines Template-Projekts erstellt werden, bei dem der neue Status-Workflow aktiviert ist, haben ebenfalls den neuen Status-Workflow aktiviert.

**"Entwürfe" werden eingestellt und sind nicht mehr verfügbar.**

## 2. **Aktivierung des Status-Workflows mit "gemeinsamen" Revisionen**

Der alte Status-Workflow (Legacy) mit "Entwürfen" wird durch den neuen Status-Workflow (mit gemeinsamen Status) für laufende Projekte ersetzt, die den Legacy-Status-Workflow nicht verwenden. Gemeinsame Status können im Status-Workflow-Menü der Dokumenteinstellungsseite aktiviert werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/h48tax1e/01-enabling-status-workflow-with-shared-revisions.png)

Das Upgrade vom Status-Workflow mit "Entwürfen" zum Status-Workflow mit "gemeinsamen" Dokumente hat diese Auswirkungen;

## 3. **Catenda Hub**

**Gemeinsamer Status** Uploads beginnen mit einem gemeinsamen Status, sobald gemeinsame Status im Projekt verfügbar sind. Nach dem Hochladen können gemeinsame Dokumente veröffentlicht werden.

**Entwurfsdokumente** Entwürfe werden eingestellt, daher können neue Entwürfe nicht mehr hochgeladen werden. Vorhandene Entwürfe können weiterhin in alten Projekten verwendet werden (mit Einschränkungen)

🖥️  _Workspace und_ ✔️ _Registerkarten "Veröffentlicht"_ Separate Registerkarten (Workspace und Veröffentlicht) sind im Dokumentbereich verfügbar, wobei die Registerkarte "Veröffentlicht" nur veröffentlichte Revisionen bereitstellt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/h48tax1e/02-catenda-hub.png)

Eine neue Revisionsnummerierung wird angezeigt (Major.Minor). #0.1, #0.2 usw. für **gemeinsame Revisionen** und #1, #2, #3 usw. für **veröffentlichte Revisionen**.

### 3.1 _Zugriffskontrolle_

Zugriffsrechte können für die Veröffentlichung gemeinsamer Revisionen festgelegt werden. Dies ermöglicht Benutzern, gemeinsame Revisionen zu veröffentlichen und veröffentlichte Status zu ändern. Die Zugriffskontrolle wird auf Ordner-/Dokumentebene angezeigt, um Benutzern das Recht zum Veröffentlichen von Dokumentrevisionen mit Schreibzugriff zu gewähren. Zugriffsrechte zum Anzeigen gemeinsamer Revisionen sind verfügbar. Hier können Sie Benutzer mit "Lesezugriff" davon abhalten, gemeinsame Revisionen anzuzeigen.

**Genehmigungen** Nur gemeinsame Revisionen können einer Genehmigungsanfrage hinzugefügt werden

**Sammlungen** Sammlungen können nur für veröffentlichte Revisionen verwendet werden

**Dokumentmodelle** Der Modellbereich zeigt die Registerkarten (Workspace und Veröffentlicht) wie im Dokumentbereich an. Zugriffsrechte werden von Dokumenten geerbt.

> **Hinweis:** Bitte informieren Sie Ihre Projektmitglieder über diese Änderungen, wenn Sie diese Funktion in vorhandenen Projekten aktivieren.

## 4. **API-Clients**

**Neueste Revision** Die neueste Revision eines Dokuments (kann gemeinsam oder veröffentlicht sein) wird abgerufen, sofern nicht anders im API-Aufruf angegeben

**Upload-Standards** Uploads über die API werden standardmäßig auf eine gemeinsame Revision gesetzt, sobald gemeinsame Status im Projekt verfügbar sind.

**Änderungen der Revisionsnummer** Revisionsnummern sind nicht mit den Revisionsnummern (Major.Minor) in Catenda Hub konsistent. Sie müssen Ihre App aktualisieren.

> **Hinweis:** Bitte informieren Sie Ihre Projektmitglieder über diese Änderungen, wenn Sie diese Funktion in vorhandenen Projekten aktivieren.

Klicken Sie [hier](https://support.catenda.com/en/articles/12289689-status-workflow-api-updates), um mehr über API-Änderungen zu erfahren
