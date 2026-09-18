# Fehlerbehebung bei Solibri BCF Live Connector

Fehler, die bei der Integration von Solibri-Dokumenten auftreten können, und ihre Lösungen werden in diesem Artikel erläutert.

## 1. **Support und Fehlerbehebung**

Der BCF Live Connector wird von Solibri entwickelt, gewartet und betrieben. Da diese Integration ein unabhängiges Produkt von Solibri ist, das zur Verbindung mit der Catenda API entwickelt wurde, konzentriert sich unser Support auf den Datenaustausch und nicht auf die internen Mechanismen der Solibri-Software selbst.

### 1.1 **Für Workflow- und Datenfragen**

Wenn Sie Hilfe beim Verständnis der Funktionsweise von Funktionen in der Integration benötigen oder wie Informationen in Catenda dargestellt werden, nachdem sie synchronisiert wurden, hilft Ihnen unser Team gerne weiter. Wir können Ihnen dabei helfen, den beabsichtigten Workflow zu navigieren und sicherzustellen, dass Ihre Projektdaten zwischen den beiden Plattformen korrekt kommunizieren.

### 1.2 **Für technische und funktionale Probleme**

Wenn bestimmte Fehlermeldungen in der Solibri-Oberfläche auftreten, der Connector nicht wie erwartet reagiert oder eine Änderung der Connector-Funktionalität gewünscht wird, kontaktieren Sie bitte direkt **[Solibri Support](https://www.solibri.com/support)**. Als Entwickler und Eigentümer des Connectors können nur sie den zugrunde liegenden Code ändern, interne Validierungsregeln anpassen oder softwarespezifische Fehler beheben.

## 2. **Dupliziertes Modell**

Wenn dieser Fehler auftritt, liegt dies normalerweise daran, dass der Solibri Connector zwei Modelle identifiziert hat, die die gleiche IFCProject GUID aufweisen.

### 2.1 **Namen vs. IDs**

Catenda und der Solibri Connector identifizieren Modelle basierend auf ihrer eindeutigen GUID, nicht auf ihrem Dateinamen.

Wenn zwei verschiedene Dateien in Ihrem Solibri Selection Basket aus derselben Originaldatei in Ihrem Authoring-Tool (z. B. Revit, ArchiCAD) exportiert wurden, ist es wahrscheinlich, dass sie die gleiche IFCProject GUID aufweisen.

Auch wenn diesen Dateien unterschiedliche Namen in Solibri gegeben sind, erkennt der Connector sie als die gleiche Entität und löst eine "Duplikat"-Warnung aus, um Datensynchronisierungskonflikte zu verhindern.

### 2.2 **So verifizieren Sie die GUID in Solibri**

Um zu bestätigen, dass Ihre Modelle die gleiche Kennung aufweisen, überprüfen Sie die Metadaten direkt in Solibri:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ym9bebpy/01-how-to-verify-the-guid-in-solibri.png)

1. Wählen Sie das **Modell** im Solibri-Modellbaum aus.
1. Öffnen Sie das **Info-Tool** oder die Registerkarte **Identität**.
1. Suchen Sie das Feld **IFCProject GUID**.

Wenn zwei Modelle hier die gleiche Zeichenfolge anzeigen, behandelt der Connector sie als das gleiche Modell.
