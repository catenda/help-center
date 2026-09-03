# Troubleshooting von Revisions-Konventionen

> Beheben Sie Upload-Fehler und Fehler beim Revisionsstapeln in Ordnern mit Benennungskonventionen. Lösen Sie Probleme durch einen falsch aktivierten Dokumentbezeichner und erkennen Sie zulässige benutzerdefinierte Feldwerte in der Vorschau

Wenn eine Benennungskonvention für einen Ordner aktiviert ist, entstehen Fehler beim Datei-Upload oder beim Revisionsstapeln in der Regel aus zwei häufigen Konfigurationsproblemen.

## 1. **1. Fehlerhafte Dokumentbezeichner-Umschaltung**

Ein häufiges Problem tritt auf, wenn der **Dokumentbezeichner** fälschlicherweise auf **Ein** für einen Block gesetzt ist, der sich mit jeder Revision ändert. Wenn diese Option aktiv ist, wird das sich ändernde Variablenfeld in den permanenten Dokumentnamen integriert, anstatt es in den Revisions-Metadaten zu isolieren.

Infolgedessen wird zwar die erste Revision erfolgreich hochgeladen, aber jede nachfolgende Datei mit einem geänderten Variablenwert wird nicht mit dem etablierten Dokumentnamen übereinstimmen. Diese Nichtübereinstimmung führt dazu, dass das System die Datei ablehnt und besagt, dass sie nicht der Konvention entspricht. Um dieses Problem zu beheben, muss die Block-Konfiguration aktualisiert werden, um den Dokumentbezeichner auf **Aus** zu setzen. _Erforderlicher Zugriff:_ Administrator

## 2. **2. Nicht übereinstimmende Feldwerte**

Upload-Fehler können auch auftreten, wenn der Text im dynamischen Block nicht den Validierungsregeln oder den spezifischen, für das zugrunde liegende benutzerdefinierte Feld festgelegten Werten entspricht. Beispielsweise führt das Einfügen von Buchstaben in ein ganzzahliges benutzerdefiniertes Feld oder das Eingeben einer Phrase, die nicht explizit in einem Dropdown-Feld für benutzerdefinierte Felder definiert wurde, zu einer Konventionsnichtübereinstimmung.

### 2.1 **2.1 Zulässige Werte identifizieren**

Um die genauen Anforderungen eines Benennungskonventionsblocks zu überprüfen, kann die Regelkonfiguration direkt aus der Dokumentoberfläche überprüft werden:

1. Erweitern Sie das rechte Informationsmenü für ein vorhandenes Dokument im betroffenen Ordner.
1. Überprüfen Sie den Abschnitt **Vorschau der Benennungskonvention**, der eine Echtzeitaufschlüsselung dessen bietet, was die Benennungsregel erwartet.
1. Bewegen Sie die Maus über den spezifischen Versions- oder Statusblock, um die Konfigurationsregeln anzuzeigen.
1. Identifizieren Sie das genaue benutzerdefinierte Feld, das den Block antreibt, um zu ermitteln, welche spezifischen Werte zulässig sind, und passen Sie den lokalen Dateinamen entsprechend an.
