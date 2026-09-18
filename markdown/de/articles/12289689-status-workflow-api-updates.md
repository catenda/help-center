# Status Workflow - API-Updates

> Einführung der API-Änderungen der neuen Status Workflow-Funktion, die gemäß ISO 19650 zwischen geteiltem und veröffentlichtem Status unterscheidet. Für Kunden und Integrationspartner, die die Catenda API nutzen.

Wir implementieren **Status Workflow**, ein bedeutendes Update der Art und Weise, wie Catenda Dokument- und Model-Revisionen verwaltet. Diese Änderung führt eine Unterscheidung zwischen Arbeits- und offiziellen Revisionen ein, die möglicherweise Anpassungen an Ihrer Integration erfordert.

## 1. Zusammenfassung

Catenda wird zwischen folgenden Punkten unterscheiden:

- **"Gemeinsam genutzte"** Revisionen (Arbeits-/Entwurfsversionen)
- **"Veröffentlichte"** Revisionen (offizielle/genehmigte Versionen)

**Sofortige Maßnahme erforderlich, wenn:**

- Ihre Anwendung ist in Catenda Hub integriert
- Sie Revisionsinformationen für Benutzer anzeigen
- Sie erstellen neue Revisionen über die API
- Sie verwenden CAD-Tool-Plugins

## 2. Was sich ändert

### 2.1 Revisionstypen

Zuvor wurden alle Revisionen implizit als "offiziell" betrachtet. Nun:

- **"Gemeinsam genutzt"**: Kollaborative Arbeitsrevisionen mit eingeschränkter Sichtbarkeit
- **"Veröffentlicht"**: Offizielle Revisionen für breitere Verteilung

### 2.2 API-Antwortänderungen

**Dokument-API** enthält neue Felder für Bibliothekselemente:

```
{  "document": {    "revision": {      "extendedVersion": {        "major": 1,        "minor": null  // oder 1,2,3 für gemeinsam genutzt      },      "version": 5  // Legacy-Nummerierung beibehalten    }  }}
```

**Models API** Änderungen sind minimal:

- Fügt Filterfunktion über den Bereichsparameter hinzu (scope=published oder scope=all)
- Macht den Revisionsstatus oder die erweiterte Nummerierung NICHT verfügbar
- Erzwingt Berechtigungen, die von den zugrunde liegenden Dokumenten geerbt werden

### 2.3 Standardverhalten

**Wichtig**: APIs geben standardmäßig **sowohl** "gemeinsam genutzte" als auch "veröffentlichte" Revisionen zurück, wo Benutzer Zugriff haben. Dies behält Abwärtskompatibilität bei, ändert aber grundlegend die Art der zurückgegebenen Daten.

## 3. Wer ist betroffen und wie

### 3.1 Nicht betroffen

- ✅ Eigenständige API-Anwendungen ohne Catenda Hub-Abhängigkeit
- ✅ Anwendungen, die Revisionen nicht anzeigen oder verwalten

### 3.2 Erheblich betroffen - CAD-Tool-Plugins

⚠️ **Kritische Probleme:**

- Kann nicht bestimmen, ob "gemeinsam genutzte" oder "veröffentlichte" Revisionen erstellt werden
- Kann den genauen Revisionsstatus für Benutzer nicht anzeigen
- Kann unterschiedliche Nummerierung als Hub anzeigen (sequenziell vs. X.Y-Format)
- Benutzer verstehen den Revisionskontext ohne Statusverfügbarkeit nicht

**Erforderliche Maßnahmen für Plugin-Entwickler:**

1. Bewerten Sie, ob Sie Revisionsinformationen anzeigen
1. Erwägen Sie, Benutzerleitfäden zu Revisionstypen hinzuzufügen
1. Planen Sie mögliche Benutzerverwirung über Numerierungsabweichungen

### 3.3 Auch betroffen

⚠️ Anwendungen, die:

- Revisionslisten für Benutzer anzeigen
- Erstellen Sie neue Revisionen über die API
- Verlassen Sie sich darauf, dass alle Revisionen "offiziell" sind
- Catenda Site-Integration verwenden

## 4. Technisches Implementierungsleitfaden

### 4.1 Filterung von Revisionen

Verwenden Sie den neuen Bereichsparameter, um zu steuern, welche Revisionen zurückgegeben werden:

```
# Dokumente APIGET /documents?scope=published     # Nur veröffentlichtGET /documents?scope=shared        # Nur gemeinsam genutzt (erfordert Berechtigung)GET /documents                     # Alle (Standard)# Models API  GET /models/revisions?scope=published  # Nur veröffentlichtGET /models/revisions                  # Alle (Standard)
```

### 4.2 Berechtigungsänderungen

Neue ACL-Rechte beeinflussen Ihre Operationen:

- **Anzeigen von "gemeinsam genutzten" Revisionen**: Erfordert spezifische Berechtigung
- **Erstellen von "veröffentlichten" Revisionen**: Nur über Catenda Hub UI möglich
- **API-Revisionserstellung**: Erstellt standardmäßig "gemeinsam genutzte" Revisionen

### 4.3 Was Sie nicht über die API tun können

- ❌ Erstellen Sie "veröffentlichte" Revisionen (nur Hub)
- ❌ Zugriff auf Revisionsstatus in Models API
- ❌ Erweiterte Nummerierung (X.Y) in Models API anzeigen
- ❌ Bestimmen Sie Model-zu-Dokument-Beziehungen

## 5. Migrationsüberlegungen

**Bestehende Projekte:**

- Alle aktuellen Revisionen werden bei der Migration "veröffentlicht"
- Versionsnummern werden zu Revisionshauptnummern (z. B. v3 → 3)
- Keine Maßnahmen erforderlich für historische Daten

**Neues Verhalten:**

- Neue Revisionen, die über die API erstellt wurden = standardmäßig "gemeinsam genutzt"
- Das Veröffentlichen erfordert manuelle Aktion im Hub

## 6. Kritische Entscheidungen für Ihre Implementierung

**Frage 1**: Benötigen Sie nur offizielle Revisionen?

- **Ja** → Implementieren Sie die Filterung `scope=published`
- **Nein** → Bereiten Sie sich auf die Behandlung gemischter Revisionstypen vor

**Frage 2**: Zeigen Sie Revisionsinformationen an?

- **Ja** → Planen Sie Numerierungsabweichungen (besonders für Models API-Benutzer)
- **Nein** → Minimale Auswirkungen erwartet

**Frage 3**: Erstellen Benutzer Revisionen über Ihre App?

- **Ja** → Informieren Sie Benutzer, dass sie "gemeinsam genutzte" Revisionen erstellen
- **Nein** → Keine Maßnahme erforderlich

## 7. Bekannte Einschränkungen und Lösungsansätze

**Für Models API-Benutzer:**

- **Einschränkung**: Kann nicht auf Revisionsstatus oder erweiterte Nummerierung zugreifen
- **Problemumgehung**: Verwenden Sie Filterung, um nur die gewünschten Revisionstypen zu erhalten
- **Benutzerauswirkung**: Mögliche Verwirrung über Revisionsabweichungen bei der Nummerierung

**Für Collection API-Benutzer:**

- Derzeit können nur "veröffentlichte" Revisionen zu Sammlungen hinzugefügt werden
- Dies kann sich basierend auf Kundenfeedback ändern

## 8. Supportressourcen

**Verfügbare Dokumentationsaktualisierungen:**

- [Aktualisierte API-Referenz] - Enthält neuen `scope`-Parameter

## 9. Häufig gestellte Fragen

**F: Wird meine Integration unterbrochen?** A: Keine Breaking Changes auf API-Ebene, aber das Benutzererlebnis kann sich erheblich ändern, besonders für CAD-Plugins.

**F: Warum kann ich den Revisionsstatus in Models API nicht sehen?** A: Um Abwärtskompatibilität zu gewährleisten, stellt die Models API Status Workflow-Funktionen minimal bereit. Verwenden Sie Filterung, um zurückgegebene Revisionen zu steuern.

**F: Wie wissen Benutzer, welchen Revisionstyp sie erstellen?** A: Über die API sind alle neuen Revisionen "gemeinsam genutzt". Benutzer müssen Catenda Hub verwenden, um "veröffentlichte" Revisionen zu erstellen.

**F: Was ist, wenn wir mehr Zeit zum Anpassen benötigen?** A: Kontaktieren Sie uns sofort. Status Workflow wird schrittweise aktiviert und wir können Zeitleistenoptionen für Ihre Organisation diskutieren.
