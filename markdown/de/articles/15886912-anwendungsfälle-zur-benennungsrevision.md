# Anwendungsfälle zur Benennungsrevision

> Entdecken Sie reale Beispiele für Revisionsbenennungen. Erfahren Sie, wie Teams Platz und Lesbarkeit ausbalancieren – mit Versionsfolgen, Statusabbildung und kompakten YYMMDD- oder klaren YYYYMMDD-Präfixen für die chronologische Sortierung.

Wenn Sie eine Benennungskonvention in einem Ordner aktivieren, passen Projektteams häufig dynamische Blöcke an spezifische interne Tracking-Workflows an. Unten finden Sie praktische Beispiele, wie verschiedene Teams benutzerdefinierte Felder und die Umschaltfläche **Dokumentkennung** nutzen, um einen organisierten Arbeitsbereich zu bewahren.

## 1. **1. Projektrollen und Implementierungsstrategien**

Die Einführung von Benennungskonventionen wird in der Regel entweder durch ein Mandat des Projekteigentümers oder durch den Wunsch von Projektmitgliedern angetrieben, einen besseren Überblick über ihre Dateien zu erhalten. Eine strukturierte Benennungskonvention ermöglicht es Projektmitgliedern, effektiver nach spezifischen Komponenten von Dokumentnamen zu suchen. Unabhängig davon, wer den Workflow initiiert, müssen Projektmitglieder einen Projektadministrator kontaktieren, um die Benennungskonvention zu konfigurieren und zu aktivieren, da administrativer Zugriff erforderlich ist, um diese Einstellungen zu ändern.

Der Umfang der Implementierung hängt normalerweise davon ab, wer sie anfordert:

### 1.1 **1.1 Mandate des Projekteigentümers**

Wenn eine Konvention vom Projekteigentümer verlangt wird, wird sie häufig projektweite implementiert. In diesen Szenarien wird häufig ein separater, ausgewiesener Ordner eingerichtet, um Dokumente aufzunehmen, die nicht den strikten Konventionsanforderungen entsprechen.

### 1.2 **1.2 Anfragen von Projektmitgliedern**

Wenn eine Konvention von einer Person oder einer bestimmten Untergruppe angefordert wird, um einen lokalisierten Workflow zu verbessern, wird sie normalerweise nur in ihrem spezifischen Arbeitsordner aktiviert, während der Rest des Projektteams ohne Konvention arbeitet.

## 2. **2. Versionsequenz-Workflows**

Die Versionsverfolgung wird verwendet, um nachfolgende Dateiaktualisierungen zu verfolgen. Abhängig von den Projektanforderungen wählen Teams zwischen erweiterbaren Spuren mit variabler Länge, starren Bindestrich-gepolsterten Platzhaltern oder einfachen numerischen Indikatoren.

### 2.1 Standard-Versionsequenz (`v1`, `v2`, `v3`)

**2.1.1 Das Team** Liam (BIM Manager) und Sophia (Bauingenieurin).

**2.1.2 Der Workflow** Sophia lädt regelmäßig Strukturmodell-Dateien auf die Plattform hoch. Liam verlangt, dass alle eingehenden Modelle explizit mit Standard-Versionsequenzen wie `v1`, `v2` oder `v3` gekennzeichnet werden.

**2.1.3 Verhalten und Überlegungen** Obwohl diese Einrichtung zunächst einfach ist, können Versionsspuren während des Projektverlaufs in zwei- oder dreistellige Zahlen erweitert werden (z. B. `v10` oder `v123`). Um dieses Wachstum zu ermöglichen, wird ein Textfeld mit entweder unbegrenzter (variabler) Länge oder größerer fester Länge eingerichtet.

Eine wichtige optische Überlegung bei diesem Ansatz ist, dass das Hinzufügen eines zweiten oder dritten Zeichens zur Sequenz alle nachfolgenden Benennungsblöcke optisch um Zeichenpositionen verschiebt, wenn sich der Block in der Mitte des Dateinamens befindet. Um zu verhindern, dass diese verschobenen Versions-Tags bei jedem Upload vollständig separate Dokumentcontainer erstellen, muss die Dokumentkennung deaktiviert werden.

**2.1.4 Die Konfiguration**

- **Quellfeld:** Benutzerdefiniertes Textfeld.
- **Länge:** Leer gelassen für variable Länge oder auf eine größere feste Zahl gesetzt.
- **Dokumentkennung:** Aus.

**2.1.5 Das Ergebnis** Wenn Sophia Dateien mit den Namen `Structural_Model_v1.ifc` und `Structural_Model_v10.ifc` hochlädt, erkennt die Plattform die sich ändernden Versionsketten. Die Dateien stapeln sich ordnungsgemäß als aufeinanderfolgende Revisionen unter einem einzigen, statischen Dokumentcontainer mit dem Namen `Structural_Model`.

### 2.2 Alphanumerische Bindestrich-gepolsterte Sequenz (`--`, `-a`, `-b`)

**2.2.1 Das Team** Sarah (Leitende Architektin) und Tom (BIM-Koordinator).

**2.2.2 Der Workflow** Sarah gibt Architekturzeichnungen aus, die einem Fortschritt folgen, bei dem die ursprüngliche Freigabe mit einem doppelten Bindestrich (`--`) beginnt, gefolgt von alphabetischer Verfolgung (`-a`, `-b`) während Änderungen auftreten. Sie arbeitet mit Tom zusammen, der die Ordnerlayouts verwaltet.

**2.2.3 Verhalten und Überlegungen** Im Gegensatz zur Standard-Versionsequenz behält diese Bindestrich-gepolsterte Einrichtung die Blocklänge genau gleich. Wenn ein neuer Versionsbuchstabe eingeführt wird, wird ein Platzhalter-Bindestrich geopfert, um einheitliche Abstände beizubehalten.

Eine primäre Herausforderung bei dieser Strategie besteht darin, dass die Konvention zusammenbricht, sobald alle Platzhalter-Bindestriche innerhalb der vordefinierten Länge erschöpft sind. Daher wird dieser Ansatz nur empfohlen, wenn ein klares Verständnis für die maximale Revisionsgrenze für die Dokumente besteht.

**2.2.4 Die Konfiguration:**

- **Quellfeld**
  Benutzerdefiniertes Textfeld, das mit einer strikten, festen Länge (z. B. 2 oder 3 Zeichen) konfiguriert ist, oder ein Dropdown-Benutzerdefiniertes Feld mit den exakt zulässigen Variationen.
- **Dokumentkennung:** Aus.
- **Das Ergebnis**
  Wenn Sarah `FloorPlan_--.pdf` hochlädt, gefolgt später von `FloorPlan_-a.pdf`, liest die Plattform die sich ändernden Sequenztags zur Validierung, entfernt sie aber beim Benennen der Datei im Arbeitsbereich. Tom und das Designteam sehen einen einzigen Dokumentcontainer mit dem Namen `FloorPlan`, wobei historische Variationen als Revisionen gestapelt sind, ohne nachfolgende Zeichen zu verschieben.

### 2.3 Einfache numerische Verfolgungssequenz (`01`, `02`, `03`)

**2.3.1 Das Team** David (Strukturzeichner) und Chloe (Leitende Bauingenieurin).

**2.3.2 Der Workflow** David aktualisiert Strukturdetail-Zeichnungen häufig und markiert sie auf seinem lokalen Computer numerisch mit sequentiellen Indikatoren wie `01`, `02` und `03`. Chloe überprüft diese Details und verlässt sich auf die Plattform, um sicherzustellen, dass David Zahlen eingibt und nicht versehentlich Textbuchstaben.

**2.3.3 Verhalten und Überlegungen** Ein ganzzahlensorientierter Regelblock wird zur Ordnerstruktur hinzugefügt, um Einträge zu validieren. Beachten Sie, dass das System zwar nur numerische Einträge akzeptiert, aber jede gültige ganze Zahl akzeptiert, anstatt eine strikte, schrittweise sequenzielle Zählung zu erzwingen.

**2.3.4 Die Konfiguration**

- **Quellfeld:** Benutzerdefiniertes Ganzzahlfeld.
- **Dokumentkennung:** Aus.

**2.3.5 Das Ergebnis** Wenn David `Steel_Detail_01.pdf` hochlädt, bestätigt das Ganzzahlfeld, dass der Block numerische Daten enthält und erlaubt den Upload. Wenn David einen Fehler macht und versucht, eine Datei mit Buchstaben in diesem Block hochzuladen, lehnt das System die Datei ab. Chloe kann die Dateien überwachen, da die Plattform zwar jede gültige ganze Zahl akzeptiert und David nicht dazu zwingt, in einer starren chronologischen Reihenfolge zu zählen, aber einen sauberen numerischen Zeitstrahl im Dateiinformationsfeld garantiert.

## 3. **3. Kurzhandel-Status-Zuordnungs-Workflows (`W`, `D`, `P`)**

**3.1 Das Team** Elena (HLK-Ingenieurin) und Marcus (Projektmanager).

**3.2 Der Workflow:** Elena nutzt ein lokales Benennungssystem, bei dem sie einbuchstabige Kurzhandel-Codes anhängt, um den Lebenszyklus-Status einer Zeichnung anzugeben: `W` für Work in Progress, `D` für Draft und `P` für Published. Marcus, der Projektmanager, muss den genauen Status ihrer Konstruktionsblätter auf einen Blick kennen, bevorzugt aber vollständige, aussagekräftige Wörter statt Abkürzungen.

**3.3 Verhalten und Überlegungen** Eine Dropdown-Konfiguration wird auf den Ordner angewendet, um die Lücke zwischen lokalen Kurzhandel-Codes und Metadaten-Anzeigettiteln der Plattform zu überbrücken.

**3.4 Die Konfiguration:**

- **Quellfeld:** Dropdown-Benutzerdefiniertes Feld.
- **Zuordnungseinrichtung**
  Der "Code" ist auf Elena's lokale Dateinamensmarkierungen (`W`, `D`, `P`) abgestimmt, während der "Name" vollständig als Anzeigenwert (`Work in Progress`, `Draft`, `Published`) geschrieben ist.
- **Dokumentkennung:** Aus.

**3.5 Das Ergebnis** Wenn Elena `HVAC_Layout_W.pdf` hochlädt, gleicht das System den Code `W` ab und füllt die Metadaten-Anzeige automatisch mit `Work in Progress` aus. Wenn Marcus das rechte Informationsmenü erweitert, um die Datei zu überprüfen, bleibt der Kern-Dokumentname sauber und statisch `HVAC_Layout`, während der Abschnitt **Revisionsinformationen** explizit "Work in Progress" anzeigt.

## 4. **4. Numerische Datenverfolgung und chronologische Sortierung**

### 4.1 **4.1 Das Team**

Oliver (Dokumentenkontrolleur) und Emma (Site-Managerin).

### 4.2 **4.2 Der Workflow**

Oliver verarbeitet tägliche Standortberichte und muss genau verfolgen, wann jeder Bericht erstellt wurde. Emma, die Site-Managerin, greift häufig auf die Dokumenttabelle zu und verlangt, dass die Dateien hochgradig organisiert sind. Da native Datumblöcke nicht in Benennungskonventionen verwendet werden, verwenden Oliver und Emma numerische benutzerdefinierte Felder, um Datenketten einzugeben. Sie erkunden zwei unterschiedliche Konfigurationsvariationen, je nachdem, wie sie sich das Verhalten der Dateien vorstellen.

### 4.3 **4.3 Datum als Revisionsmarkierung (Standardreihenfolge)**

In dieser Variation ändert sich das Datum bei jedem neuen Datei-Upload und stellt eine neue Revision des täglichen Protokolls dar. Oliver verwendet zwei Ziffern für den Tag (`01`–`31`), zwei Ziffern für den Monat (`01`–`12`) und entweder ein zweistelliges Jahr (`26`, `27`) oder ein vierstelliges Jahr (`2026`, `2027`). Da eine Benennungskonvention nur ein einziges primäres Trennzeichen über ihre Blöcke hinweg erlaubt, erfordert die Verwaltung eines isolierten Datumsformats die Wahl zwischen zwei unterschiedlichen Konfigurationspfaden:

**4.3.1 Drei separate Ganzzahlblöcke**

- **Struktur**
  Wenn ein Unterstrich (`_`) als primäres Trennzeichen festgelegt ist, kann die Datei als `Daily_Report_09_07_2026.pdf` formatiert werden.
  Dies nutzt drei einzelne Ganzzahl-Benutzerdefinierte Felder: Tag, Monat und Jahr.
- **Dokumentkennung Einschränkungen**
  Wenn die Dokumentkennung für diese drei Blöcke auf **Ein** eingestellt ist, ist das Datum dauerhaft als Teil des Dokumentnamens integriert.
  Dies erstellt für jede einzelne Revision einen separaten Dokumentcontainer, und die Datumwerte bleiben permanent, da Dokumentnamen in Benennungskonventionsordnern nicht änderbar sind.
  Um den Datumfeldern zu ermöglichen, zu variieren und Dateien als Revisionen unter einem einzigen statischen Dokumentnamen zu stapeln, ist es notwendig, die Dokumentkennung für alle drei Felder auf **Aus** einzustellen.

**4.3.2 Einzelner Textblock mit internen Trennzeichen**

- **Struktur**
  Um die Verwendung mehrerer Konventionsblöcke zu vermeiden, kann ein alternatives Zeichen (wie ein Bindestrich) innerhalb eines einzelnen Textfeldblocks verwendet werden, formatiert als `Daily_Report_09-07-2026.pdf`.
- **Validierungseinschränkungen**
  Es ist nur möglich, die übergeordnete Textkette innerhalb eines einzelnen Blocks zu validieren. Folglich hängt die Sicherstellung, dass die sekundären internen Trennzeichen korrekt platziert sind, vollständig von manueller Benutzergenauigkeit bei der Dateivorbereitung ab.

### 4.4 Datum für Sortierung (Jahr-Monat-Tag-Reihenfolge)

In dieser Variation möchte Emma, dass das Datum im Dokumentnamen sichtbar bleibt, damit für jeden Tag separate Dateien existieren. Darüber hinaus verlangt Emma, dass die Dokumenttabelle die Dateien automatisch in perfekter chronologischer Reihenfolge sortiert. Listen innerhalb der Plattform werden alphanumerisch gemäß Unicode-Werten sortiert. Wenn ein Datum als Tag-Monat-Jahr geschrieben ist, sortiert die Liste zuerst nach der Tagnummer und gruppiert alle Dateien vom "01"-Tag verschiedener Monate zusammen.

Um dies zu verhindern, platziert Oliver zuerst das Jahr, dann den Monat und dann den Tag. Bei der Verwaltung dieses Präfixes gibt es ein Gleichgewicht zwischen Zeichenraum-Ersparnis und sofortiger Lesbarkeit, was zu zwei Implementierungsoptionen führt:

**4.4.1 Zweistelliges Jahrs-Präfix (`YYMMDD`)** Diese Option verkürzt die Sortierungszeichenkette in einen einzigen Block, um zusätzliche Trennzeichen zu eliminieren, und reduziert das Jahr auf zwei ganze Zahlen (z. B. `26`, `27`, `28`). Dies spart Zeichenplatz und verringert das Risiko, dass lange Dokumentnamen am Ende der Zeile in der Benutzeroberfläche abgeschnitten oder gekürzt werden. Diese Option opfert jedoch sofortige Lesbarkeit.

Eine Datenkette wie `260126` kann leicht missverstanden werden, da nicht sofort klar ist, welche Zahlen das Jahr und welche den Tag darstellen. Ein Muster wird nur erkennbar, nachdem mehrere Dateien angezeigt wurden, und der Unterschied wird erst deutlich, wenn ein Tag- oder Jahreswert 31 überschreitet.

**4.4.2 Vierstelliges Jahrs-Präfix (`YYYYMMDD`)** Diese Option nutzt ein vollständiges vierstelliges Jahr (z. B. `2026`, `2027`, `2028`) am Anfang des Namens. Diese Konfiguration verbessert deutlich Klarheit und sofortige Lesbarkeit und macht die chronologische Reihenfolge für alle Teamitglieder offensichtlich. Allerdings beansprucht es mehr Zeichenplatz am Anfang des Dateinamens und erhöht die Wahrscheinlichkeit, dass Informationen am Ende langer Dokumentnamen in der Schnittstelle abgeschnitten oder gekürzt werden.

**4.4.3 Konfiguration**

- **Quellfeld**
  Ein einzelnes Ganzzahl- oder Text-Benutzerdefiniertes Feld, das ganz am Anfang der Benennungskonvention platziert ist, formatiert in einer strikten `YYMMDD`- oder `YYYYMMDD`-Reihenfolge.
  Um korrekte Ausrichtung und ordnungsgemäße alphanumerische Sortierung zu gewährleisten, müssen führende Nullen immer für einstellige Monate oder Tage verwendet werden (z. B. `01` für Januar).
- **Dokumentkennung:** Ein.

**4.4.4 Ergebnis** Wenn Oliver Dateien wie `260115_Report.pdf` und `260201_Report.pdf` hochlädt, werden separate Dokumente erstellt, weil die Dokumentkennung aktiv ist. Da das Jahr und der Monat zuerst kommen und durchgehende doppelstellige Polsterung verwenden, sortiert die Dokumenttabelle die Dateien automatisch in perfekter chronologischer Reihenfolge.
