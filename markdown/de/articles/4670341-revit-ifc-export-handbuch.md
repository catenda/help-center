# Revit IFC Export-Anleitung

Mit dieser IFC-Export-Anleitung soll der Benutzer einen Leitfaden zum korrekten Exportieren der IFC für die richtige Verwendung erhalten. Eine IFC-Datei kann schnell schwer und groß werden, wenn Sie viele Informationen aus dem Modell exportieren müssen. Aus diesem Grund müssen Sie beim Export einer IFC unnötige Informationen deaktivieren. Beim Hochladen eines Modells auf Catenda ist es nicht immer erforderlich, viele Informationen und eine hohe Detailgenauigkeit im Modell zu haben. Später in dieser Anleitung werden wir darauf eingehen, welche Einstellungen wir empfehlen, um das Modell kleiner und einfacher zu handhaben. Hier gehen wir Schritt für Schritt durch den am besten geeigneten Weg, um eine IFC von Revit nach Catenda zu exportieren.

## 1. **Projekteinstellungen**

Vor dem Export ist es wichtig, sicherzustellen, dass die GUIDs Ihres Revit-Projekts korrekt sind.

`Verwalten -> Einstellungen -> Projektinformation -> IFC-Parameter`

![Projektinformation IFC-Parameter IfcSite-GUID IfcBuilding-GUID IfcProject-GUID](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/01-project-settings.png)

Wenn sich die GUID von einem vorherigen Export unterscheidet, werden die Objekte neuerer Exporte nicht ordnungsgemäß mit den GUIDs in BCF-Themen verknüpft. Wenn Sie ein neues Projekt erstellen, erhält es eine eindeutige ID.

## 2. **IFC-Export ändern**

Wenn Revit offen ist und Sie zum Exportieren bereit sind, können Sie das Folgende tun.

![Oben links auf dem Bildschirm auf Datei klicken](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/02-modify-ifc-export.png)

Oben links finden wir die Registerkarte "Datei".

---

> **Tipp:** **Hinweis:** _Sie möchten möglicherweise über einen eigenen Ordner für Ihre IFCs verfügen, damit Sie immer die Kontrolle darüber haben, wo sich Ihre Datei befindet!_

Das IFC-Export-Menü finden Sie hier:

`Datei -> Exportieren -> IFC`

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/03-modify-ifc-export.png)

So könnte das IFC-Export-Menü aussehen:

![IFC exportieren](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/04-modify-ifc-export.png)

Dateiname Geben Sie den Namen und den Speicherort ein, den die exportierte Datei im System haben wird

Exportsetup Wählen Sie aus den folgenden vordefinierten Setups: \<In-Session Setup> IFC 2x3 Coordination View 2.0 IFC 2x3 Coordination View IFC 2x3 GSA Concept Design BIM 2010 IFC 2x3 Basic FM Handover View IFC 2x3 Coordination View IFC 2x3 COBie 2.4 Design Deliverable View IFC4 Reference View [Architecture] IFC4 Reference View [Structural] IFC4 Reference View [BuildingService] IFC4 Reference View [Unofficial] IFC4x3 IFC-SG Regulatory Requirements View

Wenn das Catenda-Plugin für Revit verwendet wird, wird der Liste der Optionen ein zusätzliches vordefiniertes Exportsetup zur Verwendung mit Catenda hinzugefügt.

## 3. **Setup ändern**

Klicken Sie auf "Modify setup" im Abschnitt "Export setup" des IFC-Exportdialogs. Dies ist der Ort, an dem die notwendigen Einstellungen für IFC-Exporte geändert und benutzerdefinierte Setups erstellt werden können. So kann das Menü "Modify setup" aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/05-modify-setup.png)

Dieses Fenster enthält die folgenden Reiter:

---

### 3.1 **Allgemein**

![Allgemein](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/06-general.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/07-general.png)

Wir führen Sie durch die verschiedenen Einstellungen.

**IFC-Version** Auswahl der IFC-Version.

**Austauschvoraussetzung** Diese Optionen können je nach ausgewählter IFC-Version variieren. IFC 2x3 Coordination View 2.0

- Architektonischer Referenzaustausch
- MEP-Referenzaustausch
- Struktureller Referenzaustausch

**Kategorienzuordnung** Vor Revit 2026 war diese Option verfügbar in Datei -> Exportieren -> Optionen -> IFC-Exportoptionen. So kann das Menü "IFC-Exportzuordnungseinstellungen verwalten" aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/08-general.png)

**Dateityp** IFC-Typauswahl.

**Phase zum Exportieren** Wenn Sie das Phasenwerkzeug in Revit verwendet haben, können Sie hier auswählen und nur neue oder vorhandene Strukturen exportieren.

**Raumgrenzen** Dies betrifft, wie Rauminformationen weiter verwendet werden können. a. 1. Ebene - Beispiel für Verwendung: Mengenentnahmen, Verwaltung, Betrieb und Wartung (FDVU). b. 2. Ebene - Beispiel für Verwendung: Energieanalyse, Lichtanalyse.

**Anlagentyp** Diese Option ist nur für IFC 4x3 verfügbar. Wählen Sie aus einer der folgenden Optionen: Brücke (IfcBridge) Gebäude (IfcBuilding) Marine-Anlage (IfcMarineFacility) Eisenbahn (IfcRailway) Straße (IfcRoad)

**Wände, Säulen, Kanäle nach Ebene teilen** Hier können Sie z.B. Trennwände horizontal teilen, wenn sie über mehrere Geschosse modelliert sind.

_Datei-Kopfzeileninformationen... Projektadresse..._ In diesen Feldern können Sie Informationen darüber eingeben, wer die IFC bereitgestellt hat, Projektadresse usw.

**Projektursprung** Projektursprung, wir setzen diesen auf Aktuelle gemeinsame Koordinaten- Vorhanden gemeinsame Koordinaten.

> **Hinweis:** Dies wurde ab Revit 2025 zu Geografischer Referenz verschoben

**Stahlelemente einschließen** Schließt Stahlkomponenten ein, falls modelliert.

> **Hinweis:** Dies wurde ab Revit 2025 zu Zusätzlicher Inhalt verschoben

---

### 3.2 **Zusätzlicher Inhalt**

![Zusätzlicher Inhalt](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/09-additional-content.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/10-additional-content.png)

Verknüpfte Dateien als separate IFCs exportieren Wenn Sie die verknüpften Dateien in die IFC einbeziehen möchten, können Sie diese Option aktivieren. Es wird empfohlen, jede Datei separat zu exportieren und jede in ihr eigenes Modell zu importieren.

Nur sichtbare Objekte exportieren, sichtbar in Ansicht IFC-Datei.

- Räume, Bereiche und Flächen in 3D-Ansichten exportieren
  Diese Option kann nützlich sein, um Bereiche im 2D-Viewer auszuwählen.

Stahlelemente einschließen, _gefüllt_

Exportiert 2D-Planansichtselemente, _gefüllt, Regionen_ (Kratzer).

Deckenraster exportieren Deckenraster sind 2D-Elemente und werden daher nicht im Catenda 3D-Viewer angezeigt.

---

### 3.3 **Eigenschaftssätze**

![Eigenschaftssätze](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/11-property-sets.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/12-property-sets.png)

Exportiert alle Revit-Eigenschaftssätze (pset / Eigenschaften). Hier ist ein Beispiel einer mit dieser Option exportierten Wand: Revit (_Links_) --- Catenda (_Rechts_)

<img alt="Eigenschaften" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-4f4aab46be4e.png" width="208.60495436766624"/>  ---  <img alt="Eigenschaften" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-7c05fd3c2c4a.png" width="190.21739130434784"/>

Typische Eigenschaften, die im Eigenschaftsmenü angezeigt werden: Bedingungen, Querschnittsdefinition, Dimensionen, Struktur, Identitätsdaten, Sonstige

Typische Eigenschaften, die im Menü "Kennung" angezeigt werden: IFC-Parameter Standardmäßig IFC-Eigenschaften exportieren. Exportiert berechnete Objektmengen. Chargenlisten exportieren Einmaligen Eigenschaftssatz exportieren

**Klassifikationseinstellungen** Hier ist ein Beispiel, wie Klassifikationseinstellungen mit OmniClass aussehen können.

![Klassifikationseinstellungen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/13-property-sets.png)

**Name** Der Name der Klassifikation

**Quelle (Verleger)** Der Herausgeber der Klassifikation

**Ausgabe** Die Klassifikationsausgabe

**Ausgabedatum** Das Datum der Klassifikation

**Dokumentationsort** Dies muss ein gültiger Dokumentationsort sein

**Klassifikationsfeldname** Der Klassifikationsfeldname ist der Name des Parameters in Ihren Objekten, der den Klassifikationswert enthält. Dieser Parameter befindet sich häufig auf der Familienebene. Bearbeiten Sie eine Familie, um ihre Eigenschaften anzuzeigen

![Familie bearbeiten](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/14-property-sets.png)

So kann der Parameter in den Eigenschaften aussehen

![Eigenschaften OmniClass-Nummer](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/15-property-sets.png)

Wenn Sie Ihre IFC mit einer Klassifikation exportiert und als Modell zu Catenda importiert haben, wird ihre Klassifikation als [empfohlene Bibliothek](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca) vorgeschlagen, wenn Sie eine neue Bibliothek auf der [Bibliotheksseite](https://support.catenda.com/en/articles/8065645-libraries-page) erstellen. Wenn ein Wert in der angegebenen Eigenschaft mit einem Wert in der bereitgestellten Dokumentation übereinstimmt, wird er gefunden und kann verwendet werden, um Objekte mit diesem Wert durch die erstellte Klassifikationsbibliothek auszuwählen.

---

### 3.4 **Detailstufe**

![Detailstufe](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/16-level-of-detail.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/17-level-of-detail.png)

Es geht darum, wie detailliert wir z.B. haben. Tassen, Handläufe oder vielleicht Fahrradräder. Es gibt 4 verschiedene Detailstufen.

Sehr niedrig Niedrig Mittel Hoch

Wenn hoch, wird es am detailliertesten angezeigt, wie in der folgenden Abbildung dargestellt.

![Detailstufe sehr niedrig und hoch](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/18-level-of-detail.png)

---

Beim Exportieren von IFCs aus Revit zur Verwendung in Catenda Hub empfehlen wir, die Detailstufe nicht auf hoch einzustellen. Es gibt viele Details und zusätzliche Polygone in Modellen, wenn sie mit höherer Detailstufe exportiert werden. Dies ist nicht immer notwendig und verlangsamt die Modellnavigation. Dies ist ein Beispiel für den Unterschied zwischen dem Exportieren mit der Einstellung Sehr niedrig und Hoch.

![Dies ist ein Treppengeländer, das mit der Einstellung Hoch exportiert wurde. 900k Polygone](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/19-level-of-detail.png)

![Dasselbe Modell, exportiert mit der Einstellung Sehr niedrig. 33k Polygone.](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/20-level-of-detail.png)

Das Aussehen des Modells ist sehr ähnlich, aber die Anzahl der Polygone wird drastisch reduziert und die Navigation in Catenda Hub wird viel schneller.

---

### 3.5 **Erweiterte Einstellungen**

![Erweitert](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/21-advanced.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/22-advanced.png)

**Teile als Bauelemente exportieren** Teile wie standardmäßiges IFC-Element exportieren.

**Verwendung gemischter "Solid Model"-Darstellung zulassen** Wählen Sie diese Option, um das Mischen von BRep- und Extrusionsgeometrien für eine Einheit zu ermöglichen.

**Aktive Ansicht bei der Geometrieerstellung verwenden** Wählen Sie diese Option, um die aktive Ansicht zur Generierung der Geometrie zu verwenden. Beachten Sie, dass dies zu unerwarteten Ergebnissen führen kann, wenn es in einer nicht-3D-Ansicht verwendet wird.

**Familie und Typnamen für Referenz verwenden** Wählen Sie diese Option, um die Familie und Typnamen für Referenzen zu verwenden.

**2D-Raumgrenzen für Raumvolumen verwenden** Wählen Sie diese Option, um einen vereinfachten Ansatz zur Berechnung des Raumvolumens zu verwenden (basierend auf Extrusion von 2D-Raumgrenzen), der auch standard beim Exportieren zu IFC 2x2 ist.

**IFCSite-Erhebung in den Ursprung der lokalen Platzierung der Website einbeziehen** Wählen Sie diese Option, um die Höhe des Z-Versatzes für die lokale Position in IfcSite einzubeziehen. Entfernen Sie die Option, um sie auszuschließen.

**IFC GUID in einem Elementparameter nach dem Export speichern** Wählen Sie diese Option, um die generierten IFC-GUIDs nach dem Export in der Projektdatei zu speichern. Dies fügt "IFC GUID"-Parameter zu Elementen und deren Typen sowie Projektinformationen für Projekt-, Website- und Gebäudeführer hinzu.

**Begrenzungsrahmen exportieren** Wählen Sie diese Option, um "Begrenzungsrahmen"-Darstellungen zu exportieren. Diese Option bleibt für den GSA-Export automatisch ausgewählt.

**Tesselierte Geometrie als Triangulation beibehalten** Wenn Sie komplexe gekrümmte Elemente oder Schalen haben und diese nach dem IFC-Export nicht korrekt angezeigt werden, können Sie diese Option auswählen. Beachten Sie, dass Sie möglicherweise eine sehr große IFC-Datei erstellen.

**Nur Typname für IFCTyp-Namen verwenden** Wählen Sie diese Option, wenn Sie möchten, dass die BAT-ID oder die ID des Objekts als Name der Entität angezeigt wird.

**Sichtbaren Revit-Namen als IFCEntity-Namen verwenden** Wählen Sie diese Option, wenn Sie möchten, dass der Revit-Objektname der Name der Entität ist

**Facettierte Böden und Dächer immer als einzelne IFC-Entität exportieren** Wählen Sie diese Option, um Flächen von Böden und Dächern mit mehreren Flächen zu einer einzelnen Entität zu kombinieren.

**"Zuletzt geändert"-Benutzer als Autor in Projektinformationen festlegen** Wählen Sie diese Option, wenn Sie der Autor der Änderungen in diesem Export sind

**Entitäten zum Exportieren** So kann das IFC-Entitätsauswahlmenü aussehen, das sich öffnet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/23-advanced.png)

---

### 3.6 **Geografische Referenz**

Es ist wichtig, dass Ihre Revit-Koordinaten mit den anderen Modellen in Ihrem Projekt synchronisiert sind, damit sie an derselben Stelle landen. Messen Sie daher die Koordinaten in Catenda Hub mit einer Punktmessung und geben Sie eine Koordinatenbasis in Revit an einem Punkt an, der sich an derselben Stelle befindet wie der gemessene Punkt in Catenda Hub.

![Koordinate an Punkt angeben](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/24-geographic-reference.png)

Diese Option finden Sie auf der Registerkarte "Verwalten" -> "Koordinaten" -> "Koordinatenbasis angeben". _Koordinaten an Punkt angeben_ Versetzt ein Modell und rotiert das Modell nach True North, indem Koordinaten für Nord/Süd, Ost/West und Höhe angegeben werden. In Revit ist es oft einfacher, mit 90-Grad-Winkeln zu modellieren und man möchte das ganze Modell nicht drehen. In diesem Fall können Sie stattdessen True North drehen. Sie finden die Option im Dropdown-Menü "Position" unter "Koordinaten" auf der Registerkarte "Verwalten".

![Geografische Referenz](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/25-geographic-reference.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/26-geographic-reference.png)

**Projektwebsite** Intern

**Koordinatenbasis** Sie können diese Einstellung ändern, um sicherzustellen, dass Ihr Projekt nach Norden ausgerichtet ist. Gemeinsame Koordinaten - Standard-Messpunkt Projektbasispunkt Interner Ursprung Projektbasispunkt in True North ausgerichtet Interner Ursprung in True North ausgerichtet

> **Hinweis:** Wenn Sie IFC auf der Registerkarte "Einfügen" verknüpfen, wird Ihre verknüpfte Datei in der Nähe Ihrer Objekte platziert und befindet sich nicht am Speicherort, der in der IFC beschrieben ist. Um eine IFC an den richtigen Ort zu importieren, klicken Sie stattdessen auf Datei -> Öffnen -> IFC.

**Überschreiben** Hier können Sie die projizierte Koordinatensystemreferenz überschreiben

---

### 3.7 **Unternehmensinfo**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/27-company-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/28-company-info.png)

Dieses Menü ist nur verfügbar, wenn in dem linken Menü die Einrichtung "IFC2x3 COBie 2.4 Design Deliverable View" ausgewählt ist.

---

### 3.8 **Projektinfo**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/29-project-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/30-project-info.png)

Dieses Menü ist nur verfügbar, wenn in dem linken Menü die Einrichtung "IFC2x3 COBie 2.4 Design Deliverable View" ausgewählt ist.

---

## 4. **IFC-Optionen**

Die IFC-Optionen eines Revit-Projekts finden Sie unter:

`Datei -> Exportieren -> Optionen -> IFC-Optionen`

![Exportieren -> Optionen -> IFC-Optionen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/31-ifc-options.png)

> **Hinweis:** Ab Revit 2026 ist diese Option nun verfügbar unter: `Exportieren -> IFC -> Allgemein -> Kategorienzuordnung -> Aktionsmenü rechts neben der Dropdown`

Hier innerhalb der _IFC-Optionen_ treffen wir die Einstellungen zum Exportieren eines Modells in eine IFC-Datei. Hier können Sie die Einrichtungseigenschaften zum Exportieren eines Modells in IFC anpassen. Was zu Beginn dieses Handbuchs erwähnt wurde, ist, dass es nicht notwendig ist, zu viele Informationen aus dem Modell zu bringen. Deaktivieren Sie gerne unnötige Informationen vor dem Export.

![IFC-Exportklassen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/32-ifc-options.png)

Es ist möglich, Raster in Catenda Hub anzuzeigen. Wenn Sie diese in Ihrem Revit-Modell haben, können Sie in den IFC-Optionen festlegen, dass Raster in die IFC exportiert werden. Standardmäßig werden diese nicht aus Revit exportiert.

## 5. **Farben und Materialien**

Die Farben, die in Catenda angezeigt werden, werden aus der importierten IFC-Datei gelesen. Wenn die Materialeigenschaft einer Familie zu den IFC-Parametern hinzugefügt wird, wird die Farbe des Materials in der Materialeigenschaft zur IFC hinzugefügt und damit in Catenda angezeigt. In Revit können Materialien im Materialbrowser gefunden werden:

`Registerkarte Verwalten -> Abschnitt Einstellungen -> Materialien`
Im Materialbrowser finden Sie die Einstellung für die Farbe auf der Registerkarte "Grafik" des Materials:

![Verwalten -> Materialien -> Materialbrowser -> Neues Material erstellen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/33-colors-and-materials.png)

Es ist auch möglich, die Schattierung an die Render-Einstellungen zu sperren.

![Erscheinungsbild](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/34-colors-and-materials.png)

Oberflächen im Catenda 3D-Viewer haben flache Schattierung ohne eine vorhandene Lichtquelle. Die folgenden Werte werden von Catenda beim Anzeigen der Oberfläche im 3D-Viewer interpretiert:

Allgemein

- Farbe
- Bild ausblenden

Transparenz

- Menge
- Bild ausblenden
- Transluzenz

Farbton

- Farbton-Farbe
