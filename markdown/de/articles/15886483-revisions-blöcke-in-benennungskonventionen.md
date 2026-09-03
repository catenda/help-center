# Revisions-Blöcke in Benennungskonventionen

> Erfahren Sie, wie Sie dynamische Blöcke in Ordner-Benennungskonventionen konfigurieren. Sehen Sie, wie Dateien als sequenzielle Revisionen gestapelt werden, wo Sie Ergebnisse sehen und wie Sie benutzerdefinierte Felder ohne Dokumentbezeichner nutzen.

Wenn eine Benennungskonvention in einem Ordner aktiviert ist, werden Dateien während des Upload-Prozesses automatisch gescannt, um sicherzustellen, dass sie bestimmten strukturellen Mustern entsprechen. Wenn lokale Dateinamen Blöcke enthalten, die sich mit jeder neuen Version ständig ändern, kann der Ordner so konfiguriert werden, dass sie dynamisch erkannt werden.

Bei ordnungsgemäßer Konfiguration werden verschiedene lokale Dateien mit unterschiedlichen Versionsdaten beim Upload demselben Dokumenten-Container zugeordnet. Anstatt für jede kleinere Dateiänderung separate, unübersichtliche Dokumenteinträge zu erstellen, erkennt die Plattform automatisch den gemeinsamen Basisnamen und stapelt sie als sequenzielle Revisionen unter einem einzelnen Dokument.

## 1. Wo Sie die Dokumentdetails anzeigen

Nachdem Dateien erfolgreich hochgeladen wurden, trennt die Plattform statische Dokumentdetails sauber von sich ändernden Versionsdaten:

### 1.1 **1.1 Das Informationsmenü rechts**

Wenn Sie ein Dokument aus der Dateiliste auswählen und die Registerkarte **Dateiinfo** auf der rechten Seite der Seite erweitern, werden die segmentierten Daten angezeigt.

**1.1.1 Dokumentinformationen** Dies zeigt Daten aus den Benennungsblöcken an, die während des gesamten Lebenszyklus des Dokuments konstant bleiben.

**1.1.2 Revisionsinformationen** Dies extrahiert und zeigt automatisch die Werte aus sich ändernden Blöcken direkt aus dem hochgeladenen Dateinamen an.

**1.1.3 Revisionsname** Dies listet explizit den unveränderlichen, ursprünglichen lokalen Dateinamen genau so auf, wie er auf der lokalen Festplatte gespeichert war.

### 1.2 **1.2 Die Dokumente-Tabelle**

Um ursprüngliche Dateinamen schnell auf einen Blick in den Haupt-Dateilisten anzuzeigen, kann die Spalte **"Revisionsname"** (Originalname) umgeschaltet werden. Anpassungen der Spaltensichtbarkeit sind streng an einzelne Kontenprofile gebunden, was bedeutet, dass ein Arbeitsbereich angepasst werden kann, ohne die Standardansicht für den Rest des Teams zu ändern.

## 2. Konfigurieren von sich ändernden Revisions-Blöcken

Um eine Benennungskonvention zu erstellen, die sich ändernde Versionsmarkierungen sauber von statischen Dokumentnamen isoliert, müssen einzelne Blockverhalten innerhalb der Konventionseinstellungen angepasst werden. Die Navigation zur Seite der Benennungskonventionen erfolgt in den Projekteinstellungen. _Erforderlicher Zugriff:_ Administrator

### 2.1 Die kritische Einstellung: Dokumentenidentifikator ausschalten

Für jeden Block, der sich pro Revision ändert, muss der **Dokumentenidentifikator** auf **Aus** gestellt werden. Diese Einstellung stellt sicher, dass die Plattform die Zeichen während des Uploads überprüft, um die Konsistenz zu gewährleisten, entfernt sie aber bei der Finalisierung des eigentlichen Dokumentnamens.

Dies ist der genaue Mechanismus, der Dateien mit unterschiedlichen Versionskennzeichnungen ermöglicht, sich ordnungsgemäß als Revisionen zu stapeln, anstatt völlig neue Dokumente zu erstellen.

### 2.2 Benutzerdefinierte Feldquellen nutzen

Um genau zu steuern, welche Zeichen in diesen dynamischen Blöcken zulässig sind, werden benutzerdefinierte Felder als Block-**Quelle** zugewiesen. Je nach Tracking-Anforderungen können verschiedene Feldtypen verwendet werden, um Validierungsbeschränkungen durchzusetzen:

**2.2.1 Text-Benutzerdefinierte Felder** Diese Option ermöglicht eine flexible oder feste Anzahl von Zeichen für standardmäßige alphanumerische Eingaben.

**2.2.2 Dropdown-Benutzerdefinierte Felder** Diese Option beschränkt den Block auf einen vordefinierten Satz spezifischer Werte, bis zu einem Limit von 1.000 Optionen. Dies ist äußerst vorteilhaft, wenn kurze Dateinamencodes auf vollständige, beschreibende Namen innerhalb der Plattform abgebildet werden müssen.

**3.2.3 Integer-Benutzerdefinierte Felder** Diese Option zwingt den Block, nur Zahlen zu akzeptieren. Beachten Sie, dass das System zwar nur numerische Einträge akzeptiert, jedoch jede gültige ganze Zahl akzeptiert, anstatt einen strikten, schrittweisen sequenziellen Aufzählungszwang durchzusetzen.
