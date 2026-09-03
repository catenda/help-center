# Erstellen eines neuen Modellexports

Klicken Sie auf die grüne Schaltfläche mit dem Pluszeichen oben rechts auf der [Modellexport-Seite](https://support.catenda.com/en/articles/4670280-model-export), um einen neuen Modellexport zu erstellen. Es gibt vier Schritte zum Erstellen eines neuen Modellexports. So kann der erste Schritt im Modellexporterstellungsprozess aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/01-intro.png)

## 1. **Schritt 1 – Modelle und Revisionen auswählen**

Im ersten Schritt kann die Revision jedes Modells angegeben werden, das in den Export einbezogen werden soll. Beginnen Sie, indem Sie ein Modell auswählen, das einbezogen werden soll, indem Sie das Kontrollkästchen aktivieren. Sobald das Modell ausgewählt ist, kann die Revision ausgewählt werden, die in diesen Export einbezogen werden soll.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/02-step-1-select-models-and-revisons.png)

Im ersten Schritt des Modellexports können die Modelle ausgewählt werden, die in den Export einbezogen werden sollen.

> **Hinweis 1:** Wenn das Modell keine Revisionen hat, die exportiert werden können, wird das Kontrollkästchen ausgegraut. **Hinweis 2:** Eine Modellrevision muss erfolgreich verarbeitet und nicht widerrufen worden sein, um ausgewählt zu werden.

### 1.1 **Navigation**

Sobald ein oder mehrere Modelle ausgewählt und Revisionen angegeben sind, wird der Schritt als Fertig angezeigt. Gehen Sie zum nächsten Schritt, indem Sie unten rechts auf der Seite auf Weiter: Zusammenführungsoptionen klicken.

## 2. **Schritt 2 – Zusammenführungsoptionen**

Im zweiten Schritt können Elemente, die mit Modellinhalten im Projekt verknüpft sind, beim Export in die IFC-Dateien zusammengeführt werden, mit denen sie verknüpft sind. So kann die Seite mit Zusammenführungsoptionen in einem neuen Projekt aussehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/03-step-2-merge-options.png)

Deaktivieren Sie die Kontrollkästchen, um die Projektbibliotheken abzuwählen, die nicht in die Modelldateien des Exports zusammengeführt werden sollen.

In einem neuen Projekt sind die verfügbaren Bibliotheken:

### 2.1 **Dokumente**

Wählen Sie "Dokumente", um Catenda-URL-Links zu Projektdokumenten einzufügen, die mit Objekten verknüpft wurden, in die exportierten IFC-Dateien.

### 2.2 **Links**

Wählen Sie "Links", um benutzerdefinierte Links aus der Links-Bibliothek einzufügen, die mit Objekten verknüpft wurden, in die exportierten IFC-Dateien.

### 2.3 **Benutzerdefinierte Bibliotheken**

Alle in dem Projekt erstellten Bibliotheken werden hier nach ihrem Namen angezeigt. Dies ist der Anblick nach dem Hinzufügen einiger Bibliotheken

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/04-user-defined-libraries.png)

Zu den unterstützten Bibliothekstypen gehören:

**Dokumentbibliotheken wie Dropbox- oder SharePoint-Bibliotheken** Melden Sie sich mit Dropbox oder SharePoint an und verknüpfen Sie die Elemente aus Ihrer externen Bibliothek mit Modellobjekten, um Catenda-Links zu diesen Bibliothekselementen in die exportierte IFC aufzunehmen.

**Links-Bibliothek** Beziehen Sie gespeicherte URL-Links aus der Links-Bibliothek in Ihren IFC-Export ein, indem Sie sie mit Objekten aus ausgewählten Exportmodellen verknüpfen.

**Klassifizierungsbibliothek** Erstellen Sie eine Klassifizierungsbibliothek durch das Hochladen einer CSV-Datei. Verknüpfen Sie Elemente aus der CSV-Datei in der Klassifizierungsbibliothek mit Modellobjekten. Klassifizierungsbibliotheken werden nach dem Namen der Bibliothek in der Liste der Zusammenführungsoptionen angezeigt. Wenn das Kontrollkästchen für eine Klassifizierungsbibliothek aktiviert ist, werden alle Klassifizierungsbibliotheks-Elemente aus der CSV-Datei, die mit Objekten in ausgewählten Exportmodellen verknüpft wurden, in die exportierte IFC zusammengeführt. Objekte mit solchen Links in der IFC erhalten einen Link zum Klassifizierungsbibliotheks-Element in Catenda.

### 2.4 **Bibliotheken, die nicht unterstützt werden**

Nicht unterstützte Bibliotheken umfassen Bibliotheken, die auf dynamische Inhalte angewiesen sind, wie z. B.:

**Lookup-Bibliotheken** Diese schlagen ausgewählte Objekte im Internet nach

**Eigenschaftswert-Bibliotheken** Diese klassifizieren Modellobjekte basierend auf einer ausgewählten Eigenschaft

**Eingebettete Klassifizierungsbibliotheken** Diese klassifizieren Objekte basierend auf einer externen Klassifizierungsbibliothek, die bereits in der IFC angegeben ist.

### 2.5 **Navigation**

Nach der Konfiguration der ausgewählten Bibliotheken klicken Sie auf "Weiter: Namen und Kommentar hinzufügen", um zum nächsten Schritt zu gehen.

## 3. **Schritt 3 – Namen und Kommentar hinzufügen**

Im dritten Schritt kann dem Export ein Name gegeben und ein Kommentar hinzugefügt werden. So kann der Schritt zum Hinzufügen von Namen und Kommentar aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/05-step-3-add-name-and-comment.png)

**Name** Der Name wird mit Modellexport und Datum und Uhrzeit des Exports vorausgefüllt. Dieser Name wird auch der Dateiname der heruntergeladenen ZIP-Datei sein.

**Kommentar** Exportkommentare sind optional und erscheinen nur in Catenda. Der Kommentar kann den Projektbeteiligten Informationen darüber geben, worum es bei diesem Export geht.

## 4. **Schritt 4 – Freigabeoptionen**

Im vierten und letzten Schritt kann die Freigabeoption gewählt werden. So kann der Schritt mit den Freigabeoptionen aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/06-step-4-sharing-options.png)

### 4.1 **Geteilter Export**

Geteilte Exporte sind für alle Projektbeteiligten sichtbar

### 4.2 **Privatexport**

Private Exporte sind nur für den Export-Ersteller sichtbar.

### 4.3 **Navigation**

Klicken Sie auf Export, um die Verarbeitung dieses Exports zu starten. Nach Abschluss des Exports wird die Seite des Modellexports angezeigt, auf der der Fortschritt der Exportverarbeitung zu sehen ist. Die Verarbeitung des Exports erfolgt vollständig im Hintergrund und es ist sicher, den Browser an dieser Stelle vollständig zu schließen. Nach Abschluss der Exportverarbeitung wird eine Benachrichtigung an den Export-Ersteller gesendet, dass sein Export zum Download bereit ist.
