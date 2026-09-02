# Digitale Designkoordination und Problemlösung für ein Krankenhausprojekt

> Branche: Krankenhausbau / BIM (Building Information Modeling) Persona: David, ein BIM-Koordinator für einen großen Generalunternehmer.

**Szenario:** David verwaltet das digitale Baumodell für einen neuen Krankenhausflügel. Dies ist ein äußerst komplexes Projekt, an dem Dutzende spezialisierter Teams beteiligt sind. Die architektonischen, statischen und MEP-Modelle (Mechanik, Elektrizität, Sanitär) werden ständig von verschiedenen Beratungsunternehmen aktualisiert. Davids Hauptverantwortung besteht darin, diese Modelle in Catenda Hub zu vereinigen, um Kollisionen zu identifizieren und zu beheben, _bevor_ sie zu teuren Problemen auf der Baustelle werden.

Während seiner wöchentlichen Koordinationsprüfung muss er ein mögliches kritisches Problem untersuchen, das der Bauleiter gekennzeichnet hat: Die Stützstruktur für eine große MRT-Maschine im zweiten Stock passt möglicherweise nicht zu den neuesten architektonischen und elektrischen Plänen.

**Lösung mit Catenda Hub:** David nutzt einen präzisen Arbeitsablauf in Catenda Hub, um diese komplexe Koordinationsaufgabe effizient zu bewältigen.

### **1. Zentralisierung der Daten auf der Seite "Modelle":**

Zunächst navigiert David zur Seite **Modelle**. Hier kann er alle neuesten IFC-Modelle sehen, die von den verschiedenen Teams hochgeladen wurden, jeweils mit ihrer Revisionsnummer und ihrem Status. Er wählt die relevanten Modelle für den betroffenen Bereich aus:

- ARCH-Hospital-Wing-rev04.ifc
- STRUCT-MRI-Support-rev02.ifc
- MEP-Elec-Room204-rev05.ifc

Er öffnet alle drei im verbundenen **3D-Viewer**. Die Plattform kombiniert sie zu einem einzigen, navigierbaren digitalen Zwilling dieses Abschnitts des Krankenhauses.

### **2. Identifizierung der Kollision und Erstellung eines "Lesezeichens":**

Bei der Navigation durch das 3D-Modell entdeckt David sofort das Problem. Die Stahlstützen für die MRT-Maschine durchdringen eine Wand, in der die Architekten nun einen Hauptelektroverteilraum platziert haben. Darüber hinaus kollidiert die Bodendurchführung für die Kühlrohre der Maschine mit einem neu verlegten Kabelkanal. Um dieses komplexe, mehrteilige Problem klar zu kommunizieren, reicht ein einfacher Screenshot nicht aus. Stattdessen nutzt David die Funktion **Lesezeichen**:

- Er isoliert nur die kollidierenden Elemente: die Stahlstützen, die spezifische Wand, den Schalter und den Kabelkanal.
- Er verwendet einen Schnittschnitt, um eine klare, ungehinderte Ansicht des Kollisionspunkts zu schaffen.
- Er speichert diesen genauen Zustand – einschließlich des Kamerawinkels, der Objektsichtbarkeit und des Schnittschnitts – als Lesezeichen mit dem Titel "**Kollision: MRT-Stütze vs. Elektroraum 204**".

### **3. Erstellung und Zuweisung eines umsetzbaren Problems:**

Mit dem erstellten Lesezeichen erstellt David ein **Problem** (oder "Thema" in Catenda Hub). In der Problembeschreibung schreibt er: "@Architekten, @Statik, @MEP - Wir haben eine kritische Kollision zwischen der MRT-Stützstruktur und dem überarbeiteten Layout des Elektroraums. Das angehängte Lesezeichen zeigt die genaue Position und die beteiligten Elemente. Die Statik muss bestätigen, ob die Stützen versetzt werden können, und MEP muss eine neue Route für den Kabelkanal überprüfen. Bitte stellen Sie bis Freitag EOD eine Lösung bereit." Er verlinkt das Problem direkt mit dem gerade erstellten Lesezeichen.

### **4. Förderung der kollaborativen Lösung:**

Der Chefarchitekt, der Bauingenieur und der MEP-Koordinator erhalten eine sofortige Benachrichtigung. Wenn sie auf den Link im Problem klicken, öffnet Catenda Hub das 3D-Modell und führt sie zur **genauen Ansicht, die David im Lesezeichen gespeichert hat**. Es gibt keine Mehrdeutigkeit oder verschwendete Zeit beim Versuch, das Problem zu finden. Sie nutzen den Kommentarbereich des Problems, um Lösungen zu diskutieren. Der Architekt bestätigt, dass die Position des Elektroraums festgelegt ist. Der Bauingenieur führt eine schnelle Analyse durch und schlägt ein überarbeitetes Stützdesign vor, dem eine Skizze beigefügt ist. Der MEP-Koordinator bestätigt, dass sie den Kabelkanal neu verlegen können.

### **Ergebnis und Vorteile:**

Durch die Nutzung der Seiten Modelle und Lesezeichen wandelte David ein potenziell chaotisches und kostspieliges Problem in ein strukturiertes, verfolgbares und schnell gelöstes Problem um.

- **Absolute Klarheit:** Das Lesezeichen bot eine "einzige Informationsquelle" für das Problem und beseitigte alle Missverständnisse, die durch E-Mails oder Telefonanrufe entstehen könnten.
- **Erhebliche Zeiteinsparungen:** Die Projektbeteiligten lösten das Problem in wenigen Stunden digitaler Zusammenarbeit und sparten Tage oder sogar Wochen im Vergleich zu herkömmlichen Methoden zum Austausch von Dateien.
- **Kosteneinsparung:** Die digitale Identifizierung dieser Kollision verhinderte die massiven Kosten für Abbruch vor Ort, Überarbeitungen und Projektverzögerungen, die aufgetreten wären, wenn der Stahl an der falschen Stelle errichtet worden wäre.

### **Verbesserte Rechenschaftspflicht:**

Der gesamte Erkennungs-, Kommunikations- und Lösungsprozess ist in einem einzigen Problem dokumentiert und schafft eine klare Audit-Spur für die Projektakte.
