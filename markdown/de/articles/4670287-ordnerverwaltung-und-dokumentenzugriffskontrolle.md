# Ordnerverwaltung und Dokumentenzugriffskontrolle

> Zugriffskontrollebenen für Dokumente

Wählen Sie Dokument(e) und/oder Ordner im Dokumentenbereich aus, um das Zugriffskontrollmenü im [rechten Informationsmenü](https://support.catenda.com/en/articles/8345396-right-menu-on-the-documents-page#h_cad792004b) zu finden. Hier können Sie die Projektmitglieder sehen, die Zugriff auf das Dokument haben. Befolgen Sie diese Schritte, um den Zugriff auf die ausgewählten Elemente zu bearbeiten.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/01-intro.png)

1. Wählen Sie die Dokument(e) und/oder Ordner aus, die konfiguriert werden sollen.
1. Öffnen Sie das rechte Informationsmenü
1. Klicken Sie auf **Zugriff bearbeiten**.

> **Wichtig:** **Erforderlicher Zugriff:** Vollständiger Zugriff

Der Zugriffskontrolldialog könnte etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/02-intro.png)

## 1. **1. Zugriff für Projektbeteiligte konfigurieren**

Klicken Sie auf das Dropdown-Menü "Zugriff definieren für", um Beteiligte auszuwählen, für die der Zugriff konfiguriert werden soll. Beteiligte können entweder als Mitglied oder als Mitglied eines Teams ausgewählt werden. Zugriffsrollen umfassen Administrator, individueller Benutzerzugriff, Basiszugriff, Teamzugriff und Besitzerzugriff.

### 1.1 **1.1 Empfohlener Workflow**

Legen Sie den Zugriff **pro Team statt pro Benutzer** fest. Rollen ändern sich häufig, und teambasierter Zugriff bleibt flexibel: Ein Mitglied, das zu einem Team hinzugefügt wird, erhält sofort den richtigen Zugriff, wenn es dem Projekt beitritt. Ein häufiges Muster ist, "alle Benutzer" auf keinen Zugriff zu setzen – damit neue, noch nicht zugewiesene Mitglieder vertrauliche Informationen nicht sehen können – und dann jedem Team je nach Bedarf Zugriff zu gewähren.

Klicken Sie [hier](https://support.catenda.com/en/articles/15644094-how-catenda-calculates-access-levels), um mehr darüber zu erfahren, wie sich die verschiedenen Rollen der Beteiligten gegenseitig beeinflussen.

## 2. **2. Welcher Zugriff wird angewendet? (3 Schritte)**

Der Zugriff mit dem höchsten Gewicht gewinnt immer, aber es gibt Ausnahmen. Restriktive Ebenen wie "Kein Zugriff" werden erhöht, auch wenn andere Pfade höhere Rechte gewähren.

### 2.1 **2.1 Welche der Konfigurationen gilt?**

**Administratoren** Administratoren haben immer Zugriff auf alles.

**Einzelpersonen** Die genaue konfigurierte Zugriffsstufe gilt.

**Sonstige** Überprüfen Sie den unterschiedlichen Zugriff, der für einen Benutzer konfiguriert ist, auf eine der folgenden Arten:

- Alle Benutzer
- Ein Team, zu dem der Benutzer gehört (kann zu mehreren gehören)
- Besitzerzugriff.

Der Zugriff mit dem höchsten Gewicht gilt. Kein Zugriff > Vollständiger Zugriff > Schreiben > Lesen

Klicken Sie [hier](https://support.catenda.com/en/articles/15644094-how-catenda-calculates-access-levels), um mehr darüber zu erfahren, wie Zugriffsstufen berechnet werden. Klicken Sie [hier](https://support.catenda.com/en/articles/15644249-access-control-deployment-use-cases), um mehr über typische Möglichkeiten zur Konfiguration des Zugriffs zu erfahren.

### 2.2 **2.2 Was können Beteiligte mit diesem Zugriff tun?**

Klicken Sie [hier](https://support.catenda.com/en/articles/15647394-operations-on-document-library-items), um mehr über die Operationen zu erfahren, die auf Ordnern und Dokumenten ausgeführt werden können.

## 3. **3. Überschreibungsoptionen (Umfang beim Speichern angewendet)**

Wenn der Zugriffsdialog gespeichert wird, wird der Zugriff auf die ausgewählten Elemente **unabhängig davon überschrieben, was zuvor konfiguriert wurde**. Die drei Optionen unter "Wo diese Regeln angewendet werden sollen" steuern, wie weit diese Änderung reicht.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Option</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Was wird überschrieben</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Welcher Zugriff bleibt unverändert</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Wann zu verwenden</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ordner und neuer Inhalt</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ausgewählte Elemente + alle neuen, in ihnen erstellten Elemente</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Elemente eine Ebene darunter + Elemente in Ordnerstrukturen.</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Wenn Sie den Zugriff auf vorhandene Inhalte nicht ändern dürfen</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ordner und Dateien<br/>(Standard)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Das oben Genannte + vorhandene Dokumente eine Ebene darunter</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ordner eine Ebene darunter + Elemente in Ordnerstrukturen.</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Die übliche Wahl; Pro-Unterordner-Zugriff wird beibehalten</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ordner und alle Unterordner und Dateien</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Das oben Genannte + Ordner eine Ebene darunter + Elemente in Ordnerstrukturen.</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Nur wenn es in Ordnung ist, auch den vorhandenen Unterordnerzugriff zu überschreiben</p></td></tr></tbody></table></div>

> **Hinweis:** **Vorsicht:** Die ersten beiden Optionen überschreiben nur die ausgewählten Elemente, daher kann älterer Zugriff auf Unterelemente bestehen bleiben. Mitglieder können diese möglicherweise nicht mehr navigieren, können sie aber noch durch Filterung erreichen.

## 4. **4. Status-Workflow**

Wenn gemeinsame Status nach dem 2. Oktober 2025 aktiviert wurden, erscheinen rechts neben der Spalte "Zugriff" zwei zusätzliche Spalten: **Geteilte Revisionen anzeigen** und **Veröffentlichen können**. Welche Kästchen aktiviert werden können, hängt von der Zugriffsstufe ab. So könnte es aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/03-4-status-workflow.png)

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Zugriff</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Geteilte Revisionen anzeigen</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Veröffentlichen</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Kein Zugang</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Nicht verfügbar (Element nicht in der Liste angezeigt)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Nein</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lesen</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Kann gewährt werden (optional)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Nein</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Schreiben</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Immer sichtbar</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Kann gewährt werden (optional)</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Kompletter Zugang</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Immer sichtbar</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ja</p></td></tr></tbody></table></div>
