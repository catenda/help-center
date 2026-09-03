# Revit IFC Export Handbuch

Mit diesem IFC-Export-Handbuch ist das Ziel, den Benutzer bei der Anleitung zum Export der IFC für die richtigen Zwecke zu unterstützen. Eine IFC-Datei kann schnell groß und umfangreich werden, wenn Sie viele Informationen aus dem Modell exportieren müssen. Deshalb müssen Sie beim Export einer IFC unnötige Informationen deaktivieren. Beim Hochladen eines Modells auf Catenda ist es nicht immer notwendig, viele Informationen und ein hohes Detaillierungsniveau im Modell zu haben. Später in diesem Handbuch werden wir auf die Einstellungen zurückkommen, die wir empfehlen, um das Modell etwas kleiner und einfacher zu handhaben. Hier werden wir Schritt für Schritt die beste Methode zum Exportieren einer IFC von Revit zu Catenda durchgehen.

## 1. **Projekteinstellungen**

Vor dem Export ist es wichtig sicherzustellen, dass die GUIDs Ihres Revit-Projekts korrekt sind.

`Verwalten -> Einstellungen -> Projektinformationen -> IFC-Parameter`

![Projektinformationen IFC-Parameter IfcSite GUID IfcBuilding GUID IfcProject GUID](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/01-project-settings.png)

Wenn die GUID von einem vorherigen Export abweicht, werden die Objekte neuerer Exporte nicht korrekt mit den GUIDs in BCF-Themen verknüpft. Wenn Sie ein neues Projekt erstellen, erhält es eine eindeutige ID.

## 2. **IFC-Export ändern**

Wenn Revit offen ist und Sie zum Export bereit sind, können Sie folgende Schritte durchführen.

![Oben links auf dem Bildschirm auf Datei klicken](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/02-modify-ifc-export.png)

Oben links finden wir die Registerkarte "Datei".

---

> **Tipp:** **Denken Sie daran:** _Sie möchten möglicherweise einen dedizierten Ordner für Ihre IFCs haben, um immer die Kontrolle darüber zu haben, wo sich Ihre Datei befindet!_

Das IFC-Exportmenü finden Sie hier:

`Datei -> Exportieren -> IFC`

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/03-modify-ifc-export.png)

So sieht das IFC-Exportmenü aus:

![IFC exportieren](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/04-modify-ifc-export.png)

Dateiname Geben Sie den Namen und den Speicherort ein, den die exportierte Datei im System haben wird

Exportsetup Wählen Sie eines der folgenden vordefinierten Setups: \<In-Session Setup> IFC 2x3 Coordination View 2.0 IFC 2x3 Coordination View IFC 2x3 GSA Concept Design BIM 2010 IFC 2x3 Basic FM Handover View IFC 2x3 Coordination View IFC 2x3 COBie 2.4 Design Deliverable View IFC4 Reference View [Architecture] IFC4 Reference View [Structural] IFC4 Reference View [BuildingService] IFC4 Reference View [Unofficial] IFC4x3 IFC-SG Regulatory Requirements View

Wenn das Catenda-Plugin für Revit verwendet wird, wird ein zusätzliches vordefiniertes Exportsetup zur Verwendung mit Catenda zur Liste der Optionen hinzugefügt.

## 3. **Setup ändern**

Klicken Sie im Export-Setup-Teil des Export-IFC-Dialogs auf "Setup ändern". Hier können die erforderlichen Einstellungen für IFC-Exporte geändert und benutzerdefinierte Setups erstellt werden. So sieht das Menü zum Ändern des Setups aus:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/05-modify-setup.png)

Dieses Fenster enthält die folgenden Registerkarten:

---

### 3.1 **Allgemein**

![Allgemein](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/06-general.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/07-general.png)

Wir führen Sie durch die verschiedenen Einstellungen.

**IFC-Version** Auswahl der IFC-Version.

**Austauschangebot** Diese Optionen können je nach ausgewählter IFC-Version unterschiedlich sein. IFC 2x3 Coordination View 2.0

- Architektur-Referenzaustausch
- MEP-Referenzaustausch
- Struktur-Referenzaustausch

**Kategoriezuordnung** Vor Revit 2026 war diese Option in Datei -> Exportieren -> Optionen -> IFC-Exportoptionen verfügbar. So sieht das Menü "IFC-Export-Zuordnungseinstellungen verwalten" aus:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/08-general.png)

**Dateityp** IFC-Typauswahl.

**Phase zum Exportieren** Wenn Sie das Phasen-Tool in Revit verwendet haben, können Sie hier neue oder vorhandene Strukturen auswählen und nur diese exportieren.

**Raumgrenzen** Diese befassen sich alle damit, wie Rauminformationen weiter verwendet werden können. a. 1. Ebene - Beispiel für Verwendung: Mengenentnahmen, Verwaltung, Betrieb und Instandhaltung (FDVU). b. 2. Ebene - Beispiel für Verwendung: Energieanalyse, Lichtanalyse.

**Facility-Typ** Diese Option ist nur für IFC 4x3 verfügbar. Wählen Sie zwischen einer der folgenden: Brücke (IfcBridge) Gebäude (IfcBuilding) Marine Facility (IfcMarineFacility) Eisenbahn (IfcRailway) Straße (IfcRoad)

**Wände, Säulen, Kanäle nach Ebene teilen** Hier können Sie z. B. Trennwände horizontal aufteilen, wenn sie über mehrere Etagen verteilt sind.

_Dateiheaderinformationen... Projektadresse..._ In diesen Feldern können Sie Informationen eingeben, wer die IFC bereitgestellt hat, Projektadresse usw.

**Projektursprung** Projektursprung, dieser wird auf Aktuelle gemeinsame Koordinaten - Vorhandene gemeinsame Koordinaten gesetzt.

> **Anmerkung:** Dies wurde ab Revit 2025 zu "Geografische Referenz" verschoben

**Stahlelemente einschließen** Schließt Stahlkomponenten ein, falls modelliert.

> **Anmerkung:** Dies wurde ab Revit 2025 zu "Zusätzlicher Inhalt" verschoben

---

### 3.2 **Zusätzlicher Inhalt**

![Zusätzlicher Inhalt](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/09-additional-content.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/10-additional-content.png)

Verknüpfte Dateien als separate IFCs exportieren Wenn Sie die verknüpften Dateien in die IFC einschließen möchten, können Sie diese Option aktivieren. Es wird empfohlen, jede Datei separat zu exportieren und jede in ihr eigenes Modell zu importieren.

Nur im IFC-Dateiformat sichtbare Objekte exportieren.

- Räume, Bereiche und Leerzeichen in 3D-Ansichten exportieren
  Diese Option kann zum Auswählen von Bereichen im 2D-Viewer nützlich sein.

Stahlelemente einschließen, _gefüllt_

Exportiert 2D-Grundriss-Ansichtselemente, _gefüllt, Regionen_ (Kratzer).

Deckenraster exportieren Deckenraster sind 2D-Elemente und werden daher nicht im Catenda 3D-Viewer angezeigt.

---

### 3.3 **Eigenschaftssätze**

![Eigenschaftssätze](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/11-property-sets.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/12-property-sets.png)

Exportiert alle Revit-Eigenschaftssätze (pset / Eigenschaften). Hier ist ein Beispiel für eine mit dieser Option exportierte Wand: Revit (_Links_) --- Catenda (_Rechts_)

<img alt="Eigenschaften" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-4f4aab46be4e.png" width="208.60495436766624"/>  ---  <img alt="Eigenschaften" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-7c05fd3c2c4a.png" width="190.21739130434784"/>

Typische Eigenschaften, die im Eigenschaftsmenü angezeigt werden, sind: Randbedingungen, Querschnittsdefinition, Abmessungen, Struktur, Identitätsdaten, Sonstiges

Typische Eigenschaften, die im Menü "Kennung" angezeigt werden, sind: IFC-Parameter. Exportiert Standard-IFC-Eigenschaften. Exportiert berechnete Mengen von Objekten. Exportieren Sie Chargenlisten Exportieren Sie einen einzelnen Eigenschaftssatz

**Klassifizierungseinstellungen** Hier ist ein Beispiel für Klassifizierungseinstellungen mit OmniClass.

![Klassifikationseinstellungen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/13-property-sets.png)

**Name** Der Name der Klassifizierung

**Quelle (Herausgeber)** Der Herausgeber der Klassifizierung

**Edition** Die Klassifizierungsedition

**Editionsdatum** Das Datum der Klassifizierung

**Dokumentationsspeicherort** Dies muss ein gültiger Dokumentationsspeicherort sein

**Klassifizierungsfeldname** Der Name des Klassifizierungsfelds ist der Name des Parameters in Ihren Objekten, der den Klassifizierungswert enthält. Dieser Parameter kann häufig auf der Familienebene gefunden werden. Bearbeiten Sie eine Familie, um ihre Eigenschaften anzuzeigen

![Familie bearbeiten](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/14-property-sets.png)

So kann der Parameter in den Eigenschaften aussehen

![Eigenschaften OmniClass-Nummer](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/15-property-sets.png)

Wenn Sie Ihre IFC mit einer Klassifizierung exportiert und als Modell zu Catenda importiert haben, wird ihre Klassifizierung als [vorgeschlagene Bibliothek](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca) vorgeschlagen, wenn Sie eine neue Bibliothek auf der [Bibliotheksseite](https://support.catenda.com/en/articles/8065645-libraries-page) erstellen. Wenn ein Wert in der Eigenschaft, die Sie angegeben haben, mit einem Wert in der bereitgestellten Dokumentation übereinstimmt, wird dieser gefunden und kann verwendet werden, um Objekte mit diesem Wert durch die von Ihnen erstellte Klassifizierungsbibliothek auszuwählen.

---

### 3.4 **Detaillierungsstufe**

![Detaillierungsgrad](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/16-level-of-detail.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/17-level-of-detail.png)

Dies dreht sich darum, wie detailliert wir zum Beispiel Tassen oder Handläufe oder vielleicht Fahrradräder haben. Es gibt 4 verschiedene Detaillierungsstufen.

Extra niedrig Niedrig Mittel Hoch

Bei hohem Wert wird es am detailliertesten, wie in der Abbildung unten gezeigt.

![Detaillierungsgrad sehr niedrig und hoch](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/18-level-of-detail.png)

---

Beim Exportieren von IFCs von Revit für die Verwendung in Catenda Hub empfehlen wir, die Detaillierungsstufe nicht auf "Hoch" zu setzen. Es gibt viele Details und zusätzliche Polygone in Modellen, die mit höherer Detaillierungsstufe exportiert werden, und dies ist nicht immer notwendig und verlangsamt die Modellnavigation. Dies ist ein Beispiel für den Unterschied zwischen dem Exportieren mit der Einstellung "Extra niedrig" und "Hoch".

![Dies ist ein Treppengeländer, das mit der Einstellung Hoch exportiert wurde. 900K Polygone](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/19-level-of-detail.png)

![Dies ist das gleiche Modell, das mit der Einstellung "Sehr niedrig" exportiert wurde. 33K Polygone.](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/20-level-of-detail.png)

Das Aussehen des Modells wird nahezu gleich sein, aber die Anzahl der Polygone wird drastisch abnehmen und die Navigation in Catenda Hub wird viel schneller.

---

### 3.5 **Erweitert**

![Erweitert](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/21-advanced.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/22-advanced.png)

**Teile als Bauelemente exportieren** Teile als Standard-IFC-Element exportieren.

**Verwendung gemischter "Solid Model"-Darstellung zulassen** Wählen Sie diese Option, um das Mischen von BRep- und Extrusions-Geometrien für eine Einheit zu ermöglichen.

**Aktive Ansicht beim Erstellen von Geometrie verwenden** Wählen Sie diese Option, um die aktive Ansicht zum Generieren der Geometrie zu verwenden. Beachten Sie, dass dies zu unerwarteten Ergebnissen führen kann, wenn es für eine Nicht-3D-Ansicht verwendet wird.

**Familien- und Typnamen für Referenz verwenden** Wählen Sie diese Option, um die Familien- und Typnamen für Verweise zu verwenden.

**2D-Raumgrenzen für Raumvolumen verwenden** Wählen Sie diese Option, um einen vereinfachten Ansatz für die Berechnung des Raumvolumens zu verwenden (basierend auf der Extrusion von 2D-Raumgrenzen), was auch beim Exportieren zu IFC 2x2 Standard ist.

**IfcSite-Erhebung in den Ursprung der lokalen Platzierung der Website einschließen** Wählen Sie diese Option, um die Höhe des Z-Versatzes in die lokale Position in IfcSite einzubeziehen. Entfernen Sie die Option, um sie auszuschließen.

**IFC-GUID nach dem Export in einem Elementparameter speichern** Wählen Sie diese Option, um die generierten IFC-GUIDs nach dem Export in der Projektdatei zu speichern. Dies fügt "IFC-GUID"-Parameter zu Elementen und deren Typen sowie Projektinformationen für Projekt-, Website- und Gebäudeguides hinzu.

**Begrenzungsrahmen exportieren** Wählen Sie diese Option, um "Begrenzungsrahmen"-Darstellungen zu exportieren. Diese Option bleibt für GSA-Export automatisch ausgewählt.

**Tessellierte Geometrie als Triangulation behalten** Wenn Sie komplexe gekrümmte Elemente oder Schalen haben und diese nach dem IFC-Export nicht korrekt angezeigt werden, können Sie diese Option aktivieren. Beachten Sie, dass Sie möglicherweise eine sehr große IFC-Datei erzeugen.

**Nur Typnamen für IFCType-Name verwenden** Wählen Sie diese Option, wenn Sie möchten, dass die BAT-ID oder die ID des Objekts als Name der Entität angezeigt wird.

**Sichtbaren Revit-Namen als IFCEntity-Namen verwenden** Wählen Sie diese Option, wenn der Name des Revit-Objekts der Name der Entität sein soll

**Facettierte Böden und Dächer immer als einzelne IFC-Entität exportieren** Wählen Sie diese Option, um Flächen von Böden und Dächern mit mehreren Flächen zu einer einzelnen Entität zu kombinieren.

**Benutzer "Zuletzt geändert" auf den Autor in Projektinformationen setzen** Wählen Sie diese Option, wenn Sie der Autor der Änderungen in diesem Export sind

**Zu exportierende Entitäten** So sieht das IFC-Entity-Auswahlmenü, das sich öffnet, aus:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/23-advanced.png)

---

### 3.6 **Geografische Referenz**

Es ist wichtig, dass Ihre Revit-Koordinaten mit den anderen Modellen in Ihrem Projekt synchronisiert werden, damit sie an derselben Stelle enden. Daher messen Sie die Koordinaten in Catenda Hub mit einem Punktmaß und geben Sie einen Koordinatenbasis in Revit an einem Punkt an, der sich an derselben Stelle befindet wie der in Catenda Hub gemessene Punkt.

![Koordinaten an Punkt angeben](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/24-geographic-reference.png)

Sie finden diese Option auf der Registerkarte "Verwalten" -> "Koordinaten" -> "Koordinatenbasis angeben". _Koordinaten an einem Punkt angeben_ Verlegt ein Modell und dreht das Modell zum wahren Norden, indem Koordinaten für Nord/Süd, Ost/West und Höhe angegeben werden. In Revit ist es oft einfacher, in 90-Grad-Winkeln zu modellieren, und Sie möchten das gesamte Modell nicht drehen. In diesem Fall können Sie stattdessen den wahren Norden drehen. Sie finden diese Option in der Dropdown-Liste "Position" unter "Koordinaten" auf der Registerkarte "Verwalten".

![Geografische Referenz](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/25-geographic-reference.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/26-geographic-reference.png)

**Projektstandort** Intern

**Koordinatenbasis** Sie können diese Einstellung ändern, um sicherzustellen, dass Ihr Projekt nach Norden ausgerichtet ist. Gemeinsame Koordinaten - Standardvermessungspunkt Projektbasissunkt Interner Ursprung Projektbasissunkt nach True North ausgerichtet Interner Ursprung nach True North ausgerichtet

> **Anmerkung:** Wenn Sie IFC auf der Registerkarte "Einfügen" verknüpfen, wird Ihre verknüpfte Datei in der Nähe Ihrer Objekte platziert und befindet sich nicht am Speicherort, der in der IFC beschrieben wird. Um eine IFC an die richtige Position zu importieren, klicken Sie auf "Datei" -> "Öffnen" -> "IFC".

**Überschreiben** Hier können Sie die projizierte KoordinatenSystemreferenz überschreiben

---

### 3.7 **Unternehmensinfo**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/27-company-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/28-company-info.png)

Dieses Menü ist nur verfügbar, wenn das Setup "IFC2x3 COBie 2.4 Design Deliverable View" im linken Menü ausgewählt ist.

---

### 3.8 **Projektinfo**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/29-project-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/30-project-info.png)

Dieses Menü ist nur verfügbar, wenn das Setup "IFC2x3 COBie 2.4 Design Deliverable View" im linken Menü ausgewählt ist.

---

## 4. **IFC-Optionen**

Die IFC-Optionen eines Revit-Projekts finden Sie unter:

`Datei -> Exportieren -> Optionen -> IFC-Optionen`

![Exportieren -> Optionen -> IFC-Optionen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/31-ifc-options.png)

> **Anmerkung:** Ab Revit 2026 ist diese Option jetzt verfügbar in: `Exportieren -> IFC -> Allgemein -> Kategoriezuordnung -> Aktionsmenü rechts neben der Dropdown-Liste`

Hier in den _IFC-Optionen_ nehmen wir die Einstellungen für den Export eines Modells in eine IFC-Datei vor. Hier können Sie Setupeigenschaften zum Exportieren eines Modells zu IFC anpassen. Was am Anfang dieses Handbuchs erwähnt wurde, ist, dass es nicht notwendig ist, zu viele Informationen aus dem Modell zu exportieren. Sie können vor dem Export gerne unnötige Informationen deaktivieren.

![IFC-Exportklassen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/32-ifc-options.png)

Es ist möglich, Raster in Catenda Hub anzuzeigen. Wenn Sie diese in Ihrem Revit-Modell haben, können Sie in "IFC-Optionen" festlegen, dass Raster in der IFC exportiert werden. Standardmäßig werden diese nicht aus Revit exportiert.

## 5. **Farben und Materialien**

Die in Catenda angezeigten Farben werden aus der importierten IFC-Datei gelesen. Wenn die Materialeigenschaft einer Familie zu den IFC-Parametern hinzugefügt wird, wird die Farbe des Materials in der Materialeigenschaft zu der IFC hinzugefügt und somit in Catenda angezeigt. In Revit können Materialien im Materialbrowser gefunden werden:

`Registerkarte "Verwalten" -> Bereich "Einstellungen" -> Materialien`
Im Materialbrowser kann die Einstellung für Farbe auf der Registerkarte "Grafiken" des Materials gefunden werden:

![Verwalten -> Materialien -> Materialbrowser -> Neues Material erstellen](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/33-colors-and-materials.png)

Es ist auch möglich, die Schattierung auf die Rendereinstellungen zu sperren.

![Erscheinungsbild](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/34-colors-and-materials.png)

Oberflächen im Catenda 3D-Viewer haben flache Schattierung ohne eine vorhandene Lichtquelle. Die folgenden Werte werden von Catenda beim Anzeigen der Oberfläche im 3D-Viewer interpretiert:

Generisch

- Farbe
- Bildüberblendung

Transparenz

- Betrag
- Bildüberblendung
- Transluzenz

Tönung

- Tönungsfarbe
