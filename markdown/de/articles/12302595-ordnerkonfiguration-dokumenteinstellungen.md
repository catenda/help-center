# Ordnerkonfiguration – Dokumenteinstellungen

Das Menü zur Ordnerkonfiguration finden Sie auf der [Seite Dokumenteinstellungen](https://support.catenda.com/en/articles/7831371-document-settings-page). Durch die Einrichtung eines konfigurierten Ordners können Sie die Art und Weise, wie Dokumente in diesem Workflow verwaltet werden, verbessern.

## 1. **Ordnertabelle**

Ordner können in der Ordnertabelle konfiguriert werden, die etwa so aussieht:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/01-folders-table.png)

### 1.1 **Filter für konfigurierte Ordner**

Oben in der Tabelle finden Sie einen Filter für konfigurierte Ordner.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/02-configured-folders-filter.png)

**Alle Ordner** Zeigen Sie alle Ordner im Projekt an.

**Konfigurierte Ordner** Zeigen Sie an, welche Ordner im Projekt konfiguriert sind

### 1.2 **Spalte Ordner**

Hier sehen Sie alle Ordner im Projekt. Wenn Sie auf den Pfeil oder an eine beliebige Stelle in dieser Spalte klicken, wird der Ordner erweitert und Sie sehen seine Unterordner. Wenn Sie den Mauszeiger über das Symbol oder den Namen eines Ordners bewegen, wird ein Linksymbol angezeigt, auf das Sie klicken können, um den Ordner zu öffnen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/03-folders-column.png)

Dies kann sehr hilfreich sein, um die Ergebnisse des konfigurierten Ordners nach der Konfiguration anzuzeigen.

**Konfiguration hinzufügen** Klicken Sie auf die Schaltfläche + rechts neben einem Ordner, um den [Ordnerkonfigurationsdialog](#h_96b6c91fe4) zu öffnen. Wenn sich in Unterordnern Konfigurationen befinden, können Sie keine Konfiguration für den Ordner erstellen.

**Konfiguration in der Vorschau anzeigen** Wenn eine Konfiguration für einen Ordner festgelegt ist, können Sie schnell anzeigen, welche Konfiguration festgelegt wurde, indem Sie auf das Augensymbol klicken. Die Konfigurationsvorschau kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/04-folders-column.png)

**Konfiguration bearbeiten** Wenn eine Konfiguration für einen Ordner festgelegt ist, können Sie diese bearbeiten, indem Sie auf das Stiftsymbol klicken.

**Konfigurationsvererbung** Wenn eine Konfiguration in einem übergeordneten Ordner festgelegt wurde, erben alle seine Unterordner diese Konfiguration.

### 1.3 **Spalte Namenskonvention**

Hier sehen Sie, welche Namenskonventionsblöcke für eine Zeile konfiguriert sind

### 1.4 **Spalte Benutzerdefinierte Felder**

Hier sehen Sie, welche benutzerdefinierten Felder für eine Zeile konfiguriert sind

## 2. **Ordnerkonfigurationsdialog**

Der Ordnerkonfigurationsdialog kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/05-folder-configuration-dialogue.png)

### 2.1 **Namenskonvention**

Wenn Sie auf der [Seite Namenskonvention](https://support.catenda.com/en/articles/7832559-naming-conventions-page) in den [Projekteinstellungen](https://support.catenda.com/en/articles/4670273-project-settings-page) Namenskonventionen eingerichtet haben, können Sie hier auswählen, auf welchen Ordner die Namenskonvention angewendet werden soll. Beim Anwenden einer Konvention müssen alle neuen Dokumente im Ordner und in den Unterordnern:

- Nach der Namenskonvention benannt werden
- Einen Dokumentnamen haben, der nicht bearbeitet werden kann, während die Konvention aktiv ist
- In dem Ordner verbleiben, in den sie hochgeladen wurden, und können nicht verschoben werden

Um eine Namenskonvention zu entfernen, drücken Sie das X.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yhj3v31h/06-naming-convention.png)

### 2.2 **Benutzerdefinierte Felder**

Mit benutzerdefinierten Feldern können Sie benutzerdefinierte Felder allen Dokumenten in dieser Konfiguration zuweisen. Benutzerdefinierte Felder können entweder für das gesamte Dokument oder für jede Revision festgelegt werden. _Erforderlicher Zugriff zum Ändern des Feldes:_ Schreiben

**Benutzerdefinierte Dokumentfelder**

- Die Werte werden auf dem Dokument gespeichert
- Beispiel für benutzerdefinierte Felder: "Dokumentbeschreibung", "Dokumentnotiz", usw...

**Benutzerdefinierte Revisionsfelder**

- Die Werte werden auf jeder Revision des Dokuments gespeichert
- Nur Werte, die auf der neuesten Revision gespeichert sind, werden zusammen mit dem Dokument angezeigt.
- Beispiele für benutzerdefinierte Felder: "Revisionsbemerkung", "Genehmigungsstatus", usw...

**Name** Der Name des benutzerdefinierten Feldes

**Typ** Der Typ des benutzerdefinierten Feldes. Die folgenden Typen von benutzerdefinierten Feldern können für Ordner zur Verfügung gestellt werden: Datum Dezimal Dropdown Ganzzahl Text

**Erforderlich** Wenn ein Feld erforderlich ist, muss es immer einen Wert haben.

> **Hinweis:** Ein Standardwert muss festgelegt werden, da das Dokument beim Hochladen einen Wert haben muss.

**Standardwert** Wenn ein Standardwert festgelegt ist, wird dieser Wert nach der Bestätigung der Konfiguration für alle hochgeladenen Dokumente für das Feld festgelegt, sofern er nicht später geändert wird.

## 3. **QR-Code zuweisen**

Mit [QR-Code-Stempelung](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda) können Sie hier auswählen, ob diese Funktion für einen Ordner aktiviert werden soll.
