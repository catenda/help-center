# Design Review und Änderungsaufträge in einem Hochhausprojekt

> Branche: Gewerblicher Hochbau Persona: Maria, eine Projektarchitektin in einem großen Unternehmen.

### **Szenario:**

Maria überwacht die architektonische Gestaltung eines 30-stöckigen Geschäftsgebäudes. Das Projekt befindet sich in der Mitte der Bauphase, und mehrere Ingenieurdisziplinen (Tragwerk, MEP, Brandschutz) aktualisieren ständig ihre Zeichnungen.

Marias größte Herausforderung besteht darin, das enorme Volumen an Zeichnungsrevisionen zu verwalten, die von verschiedenen Teams eingereicht werden. Eine kleine Änderung durch den Tragwerksplaner, z. B. die Verschiebung einer Trägerposition, kann kaskadierende Auswirkungen auf die Elektrorohrleitungsverlegung und die HLK-Kanalplatzierung haben. Früher hätte ihr Team neue und alte Zeichnungen manuell auf einem Leuchtpult überlagert oder sie mühsam nebeneinander auf einem Bildschirm überprüft, ein Prozess, der langsam war, anfällig für menschliche Fehler und zu kostspieligen Nacharbeiten auf der Baustelle führte, wenn Kollisionen übersehen wurden.

### **Lösung mit Catenda Hub:**

Maria verwendet jetzt Catenda Hub, um den gesamten Design-Review-Prozess zu zentralisieren und zu rationalisieren. Hier ist ihr neuer Arbeitsablauf:

### **1. Identifikation kritischer Änderungen mit PDF-Vergleich:**

Das Tragwerksteam lädt eine neue Revision des Deckenplans der 15. Ebene als PDF hoch. Anstelle einer manuellen Überprüfung verwendet Maria die Funktion **PDF-Vergleich**. Sie wählt die neue Revision und die vorherige aus. Die Software zeigt sofort eine Überlagerung beider Dokumente an.

- **Alte Geometrie** wird in **Blau** angezeigt.
- **Neue Geometrie** wird in **Rot** angezeigt.

Mit dem Deckkraftregler kann Maria deutlich sehen, dass ein Hauptträger um 30 Zentimeter verschoben wurde, um eine neue Tragwerksanforderung zu erfüllen. Diese Änderung ist sofort offensichtlich, während sie bei einer manuellen Überprüfung übersehen werden könnte.

### **2. Kommentierung und Erstellung eines Problems zur Bearbeitung:**

Da Maria vermutet, dass dies zu einer Kollision mit dem HLK-Layout führt, verwendet sie die **Kommentierungswerkzeuge** direkt in der PDF-Vergleichsansicht:

- Sie zeichnet eine **Wolkenform** um den betroffenen Bereich.
- Sie fügt einen **Texthinweis** hinzu: "Mögliche Kollision mit Hauptlüftungskanal. Bitte Abstand überprüfen."
- Sie nutzt das **Freihand-Werkzeug**, um einen Pfeil zu zeichnen, der die Richtung der HLK-Strecke anzeigt.

Anstatt eine E-Mail zu versenden, die verloren gehen könnte, speichert Maria diese Kommentierungen direkt in einem neuen **Problem** innerhalb von Catenda Hub. Das Problem erhält automatisch den Titel "Mögliche Kollision: 15. Ebene Tragwerk & HLK" und wird sowohl dem Haupttragwerksplaner als auch dem MEP-Koordinator zugewiesen. Das Problem enthält automatisch einen Schnappschuss ihrer Kommentierung auf der verglichenen Zeichnung (zeigt Revisionen #3/#4) und stellt sicher, dass alle den vollständigen Kontext haben.

### **3. Zusammenarbeit und Behebung des Problems:**

Der MEP-Koordinator erhält eine Benachrichtigung. Er öffnet das Problem und sieht Marias präzise Kommentierung auf dem verglichenen PDF. Er muss nicht nach den Dateien suchen oder raten, auf welchen Träger sie sich bezieht. Er sieht eine Vorschau der angehängten DWG-Datei des HLK-Systems direkt im Viewer und bestätigt die Kollision. Er fügt einen Kommentar zum Problem hinzu: "Bestätigt. Wir werden die Kanalverlegung neu ausführen. Eine neue Zeichnung wird bis Geschäftsschluss hochgeladen." Er heftet eine schnelle Skizze der vorgeschlagenen neuen Strecke an, die ebenfalls mit den Kommentierungswerkzeugen erstellt wurde.

### **Ergebnis und Vorteile:**

Durch die Verwendung von Catendas Document Preview-, Kommentierungs- und PDF-Vergleichsfunktionen verwandelte Marias Team einen umständlichen und fehleranfälligen Prozess in einen effizienten, kollaborativen Arbeitsablauf.

- **Drastische Reduktion von Fehlern:** Das PDF-Vergleich-Werkzeug machte es praktisch unmöglich, kritische Designänderungen zu übersehen, und verhinderte mindestens zwei potenzielle Fälle von Nacharbeiten auf der Baustelle, die Tausende von Dollar gekostet hätten und erhebliche Verzögerungen verursacht hätten.
- **Verbesserte Kommunikation und Verantwortlichkeit:** Alle Kommunikation ist im Kontext der spezifischen Zeichnung und des Problems zentralisiert. Es gibt eine klare, überprüfbare Spur darüber, wer was und wann gesagt hat, was Verwirrung durch verstreute E-Mail-Ketten eliminiert.
- **Schnellere Review-Zyklen:** Was früher Maria und ihr Team einen ganzen Tag manuelle Überprüfung gekostet hätte, wird jetzt in weniger als einer Stunde erledigt. Dies beschleunigt den gesamten Projektzeitplan.

### **Verbesserte Klarheit:**

Kommentierungen werden direkt auf den relevanten Dokumenten vorgenommen und bieten einen präzisen visuellen Kontext, der viel klarer ist als nur Textbeschreibungen. Alle Beteiligten, vom Designbüro bis zum Feld, schauen sich dieselben Informationen an.
