# Projektdatenschutz

## 1. **Daten speichern**

### 1.1 **Aktiver versus inaktiver Kontostatus**

Während einer aktiven Beziehung mit einem Unternehmen werden Projektinformationen in der Regel innerhalb von Plattformorganisationen gepflegt, um kontinuierlichen Zugriff zu unterstützen. Projekte, die angehalten oder eingefroren sind, aber Teil einer aktiven Kontokonfiguration bleiben, können weiterhin für Referenz- und Wartungsaktivitäten zugänglich sein. In diesen Fällen bleiben die Daten verfügbar, solange die Plattformorganisation ihren aktiven Status beibehält.

### 1.2 **Aufbewahrung und Wiederherstellung**

Wenn ein Projekt in einen abgelaufenen Status überführt oder manuell gelöscht wird – Aktionen, die signalisieren, dass es nicht mehr mit einer aktiven Plattformorganisation verbunden ist – ist die Plattform mit der Absicht konzipiert, Projektdaten für einen Zeitraum von bis zu drei Jahren zu speichern. Während dieses vorgesehenen Zeitfensters können Projekte jederzeit wiederhergestellt und erneut geöffnet werden, sofern eine aktive Beziehung mit dem Unternehmen erhalten bleibt. Der Aufbewahrungszeitraum und die Möglichkeit zur Datenwiederherstellung unterliegen streng den rechtlichen und behördlichen Anforderungen der Gerichtsbarkeit, in der sich das Projekt befindet. In Fällen, in denen lokale Gesetze zur Verwaltung von Softwaredaten eine frühere Löschung vorsehen, haben diese Gerichtsbarkeitsanforderungen Vorrang vor dem Standard-Plattformverhalten. Um sicherzustellen, dass Informationen gemäß internen oder behördlichen Anforderungen bewahrt bleiben, wird empfohlen, [verfügbare Exporttools zu nutzen](https://support.catenda.com/en/articles/7946690-exporting-all-project-data), um vor Ablauf oder Löschung eines Projekts ein endgültiges Backup zu erstellen.

### 1.3 **Daten im Heimatland**

Standard-Plattformdaten werden in sicheren, etablierten Regionen gehostet. Während aktuelle Konfigurationen zentralisiert sind, gibt es möglicherweise Möglichkeiten, Datenresidenz an spezifischen geografischen Standorten einzurichten, um lokale Gerichtsbarkeitsanforderungen zu erfüllen. Organisationen mit einzigartigen Hosting- oder "Heimatland"-Anforderungen werden ermutigt, den Support unter [support@catenda.com](mailto:support@catenda.com) zu kontaktieren, um potenzielle technische Möglichkeiten und Konfigurationen zu besprechen.

## 2. **Daten mit Personen außerhalb des Projekts teilen**

Es können Links erstellt werden, um Modelle und Dokumente mit externen Parteien zu teilen. Jeder mit Zugriff auf einen solchen Link benötigt kein Konto, um das Modell anzuzeigen oder die Dokumente herunterzuladen. Dokumente können durch Erstellen einer offenen URL einer Dokumentensammlung geteilt werden. _Erforderlicher Zugriff:_ Projektmitglied

Modelle können durch Erstellen einer offenen URL eines Lesezeichens geteilt werden. _Erforderlicher Zugriff:_ Administrator

Es ist möglich, anzufordern, dass diese Art von URLs für alle Ihre Projekte ausgeschaltet wird.

## 3. **Daten herunterladen**

Dateien können als Dokumentrevisionen im Bereich Dokumente hochgeladen werden.

### 3.1 **Download mit Zugriffskontrolle begrenzen**

**Dokumente / Modelle** Der Zugriff auf Dokumente kann einzeln kontrolliert werden. Wenn der Zugriff auf das IFC-Dokument eingeschränkt ist, können nur Personen mit Zugriff auf das Dokument es sehen. Mitglieder mit Zugriff auf das Dokument können es herunterladen.

**Themen** Der Zugriff auf Themen kann pro Themenbrett kontrolliert werden. Wenn der Zugriff auf ein Themenbrett eingeschränkt ist, können nur Personen mit Zugriff auf das Themenbrett die Themen in dem Brett sehen. Mitglieder mit Zugriff auf das Themenbrett können Themen in BCF-, PDF- und Excel-Format exportieren.

### 3.2 **Download durch Zurückziehen einer Revision begrenzen**

Wenn in einem Dokument eine Revision vorhanden ist, die dort nicht sein sollte, kann ein Administrator die Revision zurückziehen. Nach dem Zurückziehen einer Revision kann sie von niemandem irgendwo mehr angezeigt oder heruntergeladen werden.

### 3.3 **Download einzelner Themen begrenzen**

Um die Beziehungen zu Elementen wie Dokumenten, Themen und Objekten beizubehalten, können Themen archiviert werden. Themen können in ein anderes Themenbrett verschoben werden. Das Themenbrett kann dann archiviert werden. _Erforderlicher Zugriff:_ Administrator

Während sich das Thema im archivierten Themenbrett befindet, bleiben die Elementbeziehungen erhalten, sind aber nicht auf dem verwandten Element sichtbar. Wenn ein Themenbrett wiederhergestellt wird, zeigen die verwandten Elemente ihre Beziehung zum Thema erneut an.

### 3.4 Download von Modellen begrenzen

Wenn das Dokument ein IFC-Dokument ist, kann es mit einem Modell verknüpft werden.

_Innerhalb des Projekts_ Auch wenn das Dokument mit einem Modell verknüpft ist, können nur Personen mit Zugriff auf das Dokument es auf dem Dashboard, der Modellseite und in der Revisionsauswahl sehen.

**Externe Freigabe** Wenn ein Modell mit einem öffentlichen Link in einem Lesezeichen geteilt wird, kann die Modellvorschau nur angezeigt, aber nicht heruntergeladen werden.

Objektinformationen sind in extern freigegebenen Lesezeichen nicht sichtbar.

## 4. **Daten löschen**

**Dokumente/Modelle** Mitglieder können Dokumente löschen, aber Administratoren in einem Projekt können Dokumente immer durch Suchen mit dem Filter "gelöscht" finden. Beachten Sie, dass dieser Filter sprachspezifisch ist.

**Themen** Vor dem Löschen können Themen nach BCF exportiert werden. Das Thema mit dieser ID wird gelöscht, aber wenn Sie die ID in der BCF ändern, kann das Thema erneut importiert werden. Beziehungen zu Elementen wie Dokumenten, Objekten und Themen gehen dann verloren.

**Meilensteine** Mitglieder können Meilensteine archivieren und wiederherstellen. _Erforderlicher Zugriff:_ Meilenstein-Ersteller oder Administrator.
