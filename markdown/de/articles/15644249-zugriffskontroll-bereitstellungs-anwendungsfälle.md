# Zugriffskontroll-Bereitstellungs-Anwendungsfälle

Die Strukturierung einer Zugriffskontrollumgebung in Catenda Hub erfordert die Ausrichtung der Systemmechanik an spezifischen Projektrollen und kollaborativen Arbeitsabläufen. Um sich überlappende Regeln sauber zu lösen, wendet das System eine strikte Hierarchie an: direkte individuelle Überschreibungen bilden eine absolute endgültige Grenze, während alle nicht überschriebenen Pfade zusammenwirken, um die maximale verfügbare Berechtigungsstufe zu gewähren. Die unten beschriebenen Konfigurationsstrategien zeigen, wie Sie Teams-Grenzen, individuelle Sperren und Container-Bereiche bereitstellen, um echte Sicherheits- und Betriebsanforderungen zu erfüllen.

## 1. **1. Die allgemeine Projektcommunity**

### 1.1 **1.1 Isolierte Subunternehmer-Arbeitsbereiche**

**Wer** Ein einzelnes spezialisiertes Subunternehmer-Teams mit erforderlicher innerer Autonomie.

**Das Ziel** Das Subunternehmer-Teams muss totale Freiheit haben, Dateien in ihrem zugewiesenen Bereich hochzuladen, zu ändern, zu organisieren und zu beheben. Mitarbeiter derselben Firma müssen gegenseitig Fehler korrigieren oder Ordnerstrukturen frei umgestalten können, aber externe Parteien müssen völlig blockiert werden, um versehentliche Löschung oder nicht autorisierte Sichtbarkeit zu verhindern.

**Die Konfiguration** Die globale Baseline **Alle Benutzer** ist auf **Kein Zugriff** eingestellt, während die spezifische Subunternehmer-**Teams-Einstellung** **Vollständiger Zugriff** gewährt wird.

**Die Bereichs-Strategie** Diese Strategie wird normalerweise bereitgestellt, wenn ein Projekt neu ist. Die **Abwärtspropagation** ist auf der Ordnerstruktur der obersten Ebene aktiviert und ermöglicht es Administratoren, schnell die vollständige interne Autonomie durch den gesamten Unterverzeichnispfad zu übertragen.

### 1.2 **1.2 Interdisziplinäre Zusammenarbeit-Ordner**

**Wer** Mehrere Designdisziplinen (z. B. Architekten, Konstrukteure, MEP), die in einer gemeinsamen Umgebung arbeiten.

**Das Ziel** Ein gemeinsamer Arbeitsbereich muss bereitgestellt werden, in dem verschiedene Teams gleichzeitig Modelle hochladen, Designs koordinieren und Dateien ohne Einschränkungen kreuzenreferenzieren können.

**Die Konfiguration** Diese Umgebung kann mit einer von zwei Methoden eingerichtet werden: Entweder wird ein dediziertes, gemischtes "Interdisziplinäres Teams" erstellt und mit **Schreibzugriff** gewährt, oder jedes einzelne Disziplin-Teams (Architektur-Teams, Konstruktions-Teams usw.) wird explizit zum Container mit **Schreibzugriff** hinzugefügt.

**Die Bereichs-Strategie** Da sich die Zusammenarbeitsanforderungen häufig über verschiedene Verzweigungen eines Verzeichnisses ändern, konzentriert sich dieser Anwendungsfall auf spezifische "Blatt"-Ordner tiefer in der Hierarchie. Der Bereich ist auf **Nur sofortiger Container** beschränkt, um sicherzustellen, dass offene Zusammenarbeitsregeln nicht versehentlich in andere eingeschränkte Zonen ausweichen.

### 1.3 **1.3 Team-übergreifende Sichtbarkeit und Auditing**

**Wer** Externe Prüfer, Client-Vertreter oder sekundäre Engineering-Teams.

**Das Ziel** Ein primäres Teams muss vollständige Kontrolle oder Upload-Rechte innerhalb eines Verzeichnisses beibehalten, aber ein externes Teams oder ein Stakeholder muss den Fortschritt aktiv überwachen, Dokumente überprüfen und in Echtzeit genau sehen, was passiert, ohne die Daten zu ändern.

**Die Konfiguration** Die primäre Arbeitsgruppe wird mit **Vollständiger Zugriff** oder **Schreibzugriff** gewährt, während das Audit-Teams oder das sekundäre Teams explizit mit **Lesezugriff** zugewiesen wird.

**Die Bereichs-Strategie** Diese Konfiguration verwendet die Zuordnung **Nur sofortiger Container** auf lokalisierte Blatt-Ordner. Sie ermöglicht es Stakeholdern, gezielten Einblick in abgeschlossene Arbeitsbereiche zu erhalten, während unapproved Entwürfe in angrenzenden Ordnern völlig verborgen bleiben.

## 2. **2. Subunternehmer und externe Mitwirkende**

### 2.1 **2.1 Fluid Teams-Zuweisungen für rotierendes Personal**

**Wer** Externe Anbieter und Auftragnehmer mit hoher Personalfluktuation.

**Das Ziel** Der Zugriff muss stabil und sicher bleiben, auch wenn Personal häufig in und aus dem Projekt ausgeht oder die Unternehmensrollen ändert.

**Die Konfiguration** Berechtigungen werden ausschließlich einer **Teams-Einstellung** (z. B. "Externe Prüfer") zugewiesen, die auf **Lesezugriff** oder **Schreibzugriff** eingestellt ist. Keine individuellen Benutzerüberschreibungen sind für die Teams-Mitglieder konfiguriert.

**Die Bereichs-Strategie** Um langfristige Wartbarkeit zu gewährleisten, nutzt diese Konfiguration die **Abwärtspropagation** auf den Verzeichnissen der obersten Ebene. Wenn ein neuer Mitarbeiter dem externen Unternehmen beitritt, wird er einfach zur bestehenden Teams-Struktur hinzugefügt und erbt sofort die richtigen Berechtigungen über den gesamten Projektbranch, ohne manuelle Ordner-für-Ordner-Anpassungen.

### 2.2 **2.2 Die sichere individuelle Sperrung**

**Wer:** Hochsicherheitsberater, Drittanbieter-Prüfer oder eingeschränkte externe Mitwirkende.

**Das Ziel:** Da Sicherheit und Datenintegrität von größter Bedeutung sind, muss ein Administrator mit 100%iger Sicherheit garantieren, dass ein bestimmter Benutzer eine feste Zugriffsstufe hat. Diese Stufe muss streng gesperrt bleiben und sicherstellen, dass der Benutzer nicht versehentlich erhöhte Berechtigungen erben kann, wenn er versehentlich einem parallelen Projekt-Teams oder einer Zusammenarbeitsgruppe hinzugefügt wird.

**Die Konfiguration:** Eine explizite **Individuelle Benutzereinstellung** wird direkt auf das Benutzerkonto angewendet und genau auf die erforderliche Stufe eingestellt (z. B. **Lesezugriff** oder **Kein Zugriff**).

**Die Bereichs-Strategie:** Dies wird als lokalisierte Sperrung auf spezifischen Blatt-Knoten mit der Einstellung **Nur sofortiger Container** angewendet. Da eine individuelle Zuweisung die ultimativ endgültige Behörde in der Systemhierarchie darstellt, setzt sie alle globalen Baselines, Teams-Mitgliedschaften und Besitzerrechte außer Kraft. Auch wenn der Benutzer versehentlich an einem anderen Ort einem Teams mit Vollständiger Zugriff zugewiesen wird, stellt die individuelle Sperrung sicher, dass die Berechtigungen genau wie beabsichtigt eingeschränkt bleiben.

## 3. **3. Elementbesitzer und Inhaltersteller**

Catenda Hub weist automatisch **Vollständiger Zugriff** dem Ersteller eines Ordners (ob manuell erstellt oder automatisch extrahiert über eine hochgeladene ZIP-Struktur), einem Topic-Board oder einem neu eingerichteten Dokument-Container zu. Ownership gilt streng für den Dokument-Container selbst. Dies bedeutet, dass wenn ein Benutzer eine neue Version zu einem von jemand anderem erstellten Dokument hochlädt, die ursprüngliche Container-Ownership unverändert bleibt.

### 3.1 **3.1 Ersteller-Souveränität und Datenschutz**

**Wer** Interne Autoren und Standard-Inhaltsmitwirkende.

**Das Ziel** Eine gemeinsame Ordnerumgebung ist erforderlich, in der Teams-Mitglieder allgemeine Dateien durchsuchen können, aber jede Person, die ursprünglich einen Dokument-Container erstellt, muss die absolute Kontrolle behalten, um ihn zu aktualisieren, umzubenennen oder zu verwalten, ohne denselben destruktiven Verwaltungsrechte dem Rest des Teams zu gewähren.

**Die Konfiguration** Die globale Baseline **Alle Benutzer** oder das Teams-Framework ist auf **Lesezugriff** oder **Schreibzugriff** beschränkt, während die individuellen Benutzereinstellungen für die Mitwirkenden völlig nicht konfiguriert bleiben.

**Die Logik:** Ohne eine individuelle Überschreibung wird das System auf die höchste vererbte Stufe standardisiert. Reguläre Teams-Mitglieder sind an die Standard-Ordnerregeln gebunden, aber in dem Moment, in dem der ursprüngliche Autor mit einem Dokument-Container interagiert, _den sie besitzen_, erhöht ihr integrierter Besitzerstatus sie auf Vollständiger Zugriff.

### 3.2 **3.2 Isolierte private Arbeitsbereiche**

**Wer** Spezifische Teams-Leiter, Projektmanager oder interne Prüfer.

**Das Ziel** Ein streng vertraulicher Ordner oder Topic-Board muss eingerichtet werden, in dem ein Manager Entwürfe hochladen, vertrauliche Dateien organisieren oder interne Notizen in völliger Isolation vom Rest der Projektcommunity speichern kann.

**Die Konfiguration** Der Zielcontainer wird erstellt, und die globale Baseline **Alle Benutzer** ist explizit auf **Kein Zugriff** eingestellt. Keine anderen allgemeinen Teams werden Zugriff gewährt.

**Die Logik** Da die Baseline und Teams-Pfade völlig geschlossen sind, sehen Standard-Benutzer nichts. Jedoch, da der Ersteller dieses Ordners oder Boards automatisch **Owner Full Access** hält, behält er vollständige Sichtbarkeit und administrative Kontrolle über den Raum, völlig isoliert von Standard-Projektmitgliedern, während Projektadministratoren eine übergeordnete Überwachung behalten.
