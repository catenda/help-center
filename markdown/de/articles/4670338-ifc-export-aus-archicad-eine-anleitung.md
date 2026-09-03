# IFC Export Archicad-Handbuch

Bedenken Sie bei der Ausfuhr einer IFC, was für Ihren IFC-Export relevant ist. Die IFC-Datei kann groß und schwierig zu handhaben sein, wenn sie viele Informationen enthält. Daher ist es wichtig, keine unnötigen Informationen zu exportieren. In diesem Bericht erhalten Sie verschiedene Tipps zum Filtern Ihres IFC-Exports in Archicad.

## 1. **1. Projektinformationen**

Stellen Sie vor dem Exportieren einer IFC aus Ihrem Projekt sicher, dass die Projektinformationen konfiguriert sind. Die Projektinformationen finden Sie hier:

`Datei -> Info -> Projektinformationen`

So können die Projektinformationen aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/01-1-project-info.png)

Standardmäßig sind die verschiedenen Felder leer. Obwohl sie leer sind, wird für jedes aufgelistete Projekt, jede Website und jedes Gebäude eine eindeutige ID erstellt.

### 1.1 **1.1 Mehrere IFCs aus demselben Archicad-Projekt**

In einigen Situationen werden mehrere IFC-Dateien aus demselben Archicad-Projekt exportiert. Beispiele hierfür sind:

**1.1.1 IFC-Dateien mit Objekten aus verschiedenen Fachbereichen** Ein MEP-Modell mit Kanälen, ein Architekturmodell mit Wänden und ein Strukturmodell mit allen Platten.

**1.1.2 Mehrere Gebäude** Manchmal werden mehrere Gebäude in derselben Archicad-Datei modelliert und für jedes wird eine separate IFC exportiert.

**1.1.3 Unterschiedliche Designentscheidungen** Wenn verschiedene Variationen eines Gebäudes in derselben Archicad-Datei modelliert werden, wird jede Variation häufig in ihre eigene IFC-Datei exportiert.

### 1.2 **1.2 Konfigurieren der Projektinformationen**

Unabhängig davon, ob mehrere IFC-Dateien exportiert werden sollen oder nicht, ist es oft eine gute Idee, Werte in den Projektinformationen einzugeben, damit diese später nicht mehr geändert werden müssen. Die Projektinformationen sind wichtig, da sie die GUIDs der Datei beeinflussen. Jeder Typ der exportierten IFC sollte eigene Projekteinstellungen haben. Die Projekteinstellungen können unten rechts importiert und exportiert werden. Auf diese Weise können mehrere Profile für die Exporte aus der Datei unterstützt werden. Für Catenda ist es wichtig, dass IFCs in verschiedenen Modellen unterschiedliche Informationen konfiguriert haben, während IFCs, die sich im selben Modell befinden, dieselben Informationen konfiguriert haben.

## 2. **2. IFC-Exporteinstellungen**

Um das gesamte Projekt zu exportieren, müssen Sie sich in der 3D-Ansicht befinden. Stellen Sie sicher, dass Sie den richtigen Translator verwenden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/02-2-ifc-export-settings.png)

Klicken Sie auf die Schaltfläche "Optionen", um eine Zusammenfassung Ihrer IFC-Exporteinstellungen anzuzeigen. Unter Modellfilter können Sie auch weitere Filter anwenden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/03-2-ifc-export-settings.png)

Das Feld "IFC-Translator" ermöglicht es Ihnen, Translator-Einstellungen anzuzeigen oder zu ändern oder neue Translator zu erstellen. Wenn Sie Ihren IFC-Export ändern möchten, wird empfohlen, einen der vorgefertigten Translator zu duplizieren, damit Sie keinen der Standard-Translator durcheinander bringen. Duplizieren Sie einen Translator hier: Klicken Sie auf "Neu" > "Duplikat von" > wählen Sie den Translator aus, den Sie duplizieren möchten. Wenn Sie die IFC zusammenführen möchten, können Sie dies unter dem gleichen Banner tun.

![image-2.png](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/04-2-ifc-export-settings.png)

## 3. **3. Unterschiedliche Einstellungen im Export**

3.1 [Modellfilter](#h_138e653078) ermöglicht es Ihnen, auszuwählen, was Sie durch verschiedene Voreinstellungen exportieren möchten. 3.2 [Typzuordnung](#h_a34c1332a3) ermöglicht es Ihnen, den Typ der IFC zu wählen, als der jedes Element exportiert wird. 3.3 [Geometriekonvertierung](#h_db084b5d6b) ermöglicht es Ihnen, zu wählen, welche Art von Geometrie Sie exportieren möchten. 3.4 [Eigenschaftszuordnung](#h_d48644eb35) ermöglicht es Ihnen, Kriterien basierend auf Typen festzulegen. 3.5 [Datenkonvertierung](#h_7f1df4ecb9) ermöglicht es Ihnen, zu wählen, welche Art von Daten Sie aus dem Modell exportieren möchten. 3.6 [Einheitenkonvertierung](#h_36caead1cd) ermöglicht es Ihnen, zu wählen, welche Maßeinheiten Sie in Ihrer IFC exportieren möchten.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/05-3-different-settings-in-the-export.png)

## 4. **4. Modellfilter**

### 4.1 **Exportieren von Gittern in der IFC**

Manchmal möchten Sie die Gitter auch exportieren, um sie in Catenda Hub sehen zu können. Gehen Sie zum Modellfilter für den IFC-Export und stellen Sie sicher, dass das Kontrollkästchen "Gittersystem und Elemente" aktiviert ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/06-exporting-grids-in-the-ifc.png)

## 5. **5. Typzuordnung**

Wenn eine IFC exportiert wird, wird jedem Element im Modell ein IFC-Typ zugewiesen. Wenn Sie den gewünschten IFC-Translator auswählen, können Sie zu "Typzuordnung" gehen und auf "IFC-Typen für Import zuordnen" klicken, um zu verwalten, welche Art von Typzuordnung Sie in Ihrer exportierten IFC wünschen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/07-5-type-mapping.png)

Die Typzuordnung hat hauptsächlich zwei verschiedene Optionen zum Sortieren Ihrer IFC-Typen.

### 5.1 **5.1 Elementtyp**

Jedem Element wird automatisch ein grundlegender IFC-Typ zugewiesen. Sie können den zugewiesenen IFC-Typ jedes Elements im Projekt-Manager und in den Elementeinstellungen sehen.

### 5.2 **5.2 Klassifikation**

Diese Methode ermöglicht eine flexiblere und detailliertere IFC-Typzuordnung nach festgelegten Klassifikationsstandards. Zone- und Öffnungselemente werden auf einen festen IFC-Typ eingestellt. IFCSpace und IFCOpeningElements.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/08-5-2-classification.png)

## 6. **6. Geometriekonvertierung**

Die Geometriekonvertierung für den IFC-Export ermöglicht es Ihnen, Ihre Geometrie auf verschiedene Weise zu konvertieren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/09-6-geometry-conversion.png)

### 6.1 Konvertierungen von Archicad-Elementen

**6.1.1 Nur Geometrien exportieren, die "an der Kollisionserkennung teilnehmen"** Nur Objekte exportieren, die sich mit anderen Objekten schneiden

**6.1.2 Geometrie von IFC-Typ-Produkten exportieren** Typprodukte enthalten

**6.1.3 Bruttgeometrie von Elementen exportieren** Bruttgeometrie enthalten

**6.1.4 Alle Modell-Elementgeometrien exportieren als:** _Parametrisch mit Ausnahmen_ - Standard

**Parametrisch (extrudiert/rotiert)** _BREP_ - Präzise Geometrie - Wenn dies ausgewählt ist, sind die nächsten beiden Optionen auch BREP

**6.1.5 Elemente in Solid Element Operations:** _Extrudiert/rotiert_ - Standard _BREP_ - Präzise Geometrie

**6.1.6 Elemente mit Übergängen** Einige Elemente können sich mit anderen Elementen schneiden, die Teile der Extrusion schneiden können.

Extrudiert/rotiert - Ecken der Elemente verbinden Dies fügt Ihren extrudierten Elementen Übergänge hinzu. Mit dieser Option können Sie sehen, dass sich Elemente wie Wände oder Dächer, besonders geneigte, schön verbinden.

Extrudiert/rotiert ohne Übergänge - Standard Dies beschleunigt den Export. Wenn Sie Elemente im 90-Grad-Winkel wie Wände oder Dächer haben, werden Sie wahrscheinlich keinen Unterschied bemerken. Wenn Sie geneigte Wände haben, werden Sie bemerken, dass an der Ecke, an der sich die Wände treffen, statt des Schnitts des Überhangs der geraden Extrusion die Wände einfach aneinander vorbeigehen und sich nicht schön verbinden.

BREP Präzise Geometrie

**6.1.7 Parametrische Elemente** Archicad-Elemente können als parametrische Geometrie exportiert werden, häufig in Form von Führungslinien, die auf eine Entfernung extrudiert werden. Parametrische Geometrie macht es einfach, das Objekt nach seiner Erstellung zu bearbeiten. Während diese Option die Bearbeitbarkeit behält, kann die Geometrie oft etwas ungenau sein, da die Definition eine Annäherung an die Geometrie ist. Diese Option wird empfohlen, wenn Sie beabsichtigen, die IFC zurück in Archicad oder ein anderes Bearbeitungsprogramm zu importieren, um weitere Änderungen vorzunehmen.

BREP Geometrie als separate BREP-Oberflächen exportieren. Anstatt Objekte durch ihre Parameter wie Länge/Breite/Höhe mit erzeugten Oberflächen zu beschreiben, wird jede Oberfläche als separate Oberfläche mit einem Ort in 3D beschrieben. Objekte können immer noch mehrere Oberflächen enthalten, aber diese sind lose Oberflächen. Nach dem Exportieren müssen BREP-Oberflächen einzeln bearbeitet werden, da Parameter nicht mehr auf die Oberfläche angewendet werden. Mit der BREP-Option werden exakte Oberflächen exportiert, ohne Raum für Unterschiede in der Interpretation von Parametern zwischen Authoring-Tools zu lassen. Oberflächen werden einzeln eingefärbt und haben in Catenda Hub die gleiche Farbe wie in Archicad. Oberflächenfarben können im folgenden Menü konfiguriert werden:

`Optionen -> Elementattribute -> Oberflächen`

Es kann gut sein, alle Einstellungen für eine Oberfläche zu konfigurieren, da sie in die IFC geschrieben werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/10-6-1-conversions-of-archicad-elements.png)

Oberflächen im Catenda 3D-Viewer haben flaches Shading ohne eine Lichtquelle. Dies bedeutet, dass Werte wie Ambient, Attenuation, Shinyness, Emission und Specular nicht interpretiert werden, wenn die Oberfläche im Catenda 3D-Viewer angezeigt wird. Die folgenden Werte werden von Catenda bei der Anzeige der Oberfläche im 3D-Viewer interpretiert:

Oberflächenfarbe Die Farbe der Oberfläche

Durchlässigkeit Wie viel Sie durch das Objekt sehen können (setzt die transluzente Deckkrafteinstellung außer Kraft)

Diffus Wie dunkel oder hell die Oberflächenfarbe ist

**6.1.8 IFC-Modellposition definieren durch:** Diese Option bestimmt den Projektstandort. Es ist wichtig, sich bereits zu Beginn des Projekts auf einen gemeinsamen Koordinatenpunkt einzuigen, da eine Änderung möglicherweise bedeutet, dass mehrere Berater ihre Objekte verschieben müssen, was am Ende eines Projekts oft nicht möglich ist.

Survey Point und Projektausgang - Standard Mit dieser Option ist der Abstand von (0,0,0) zu Ihrem Modell in Archicad der Abstand von (0,0,0 + Koordinaten Ihres Survey Point) zu Ihrem Modell in Catenda Hub + das Wenn Sie einen Projektstandort festgelegt haben, landet Ihr Modell bei diesen Koordinaten in Catenda Hub

Nur Projektausgang Mit dieser Option ist der Abstand von (0,0,0) zu Ihrem Modell in Archicad der Abstand von (0,0,0) zu Ihrem Modell in Catenda Hub.

Nur Survey Point Mit dieser Option ist der Abstand vom Survey Point in Archicad zu Ihren Modellen der Abstand von (0,0,0) zu Ihrem Modell in Catenda Hub

## 7. **7. Hierarchische Archicad-Elemente**

Exportieren Sie Objekte in einer flachen Hierarchie oder als verschachtelte Unterelemente.

### 7.1 **7.1 Vorhangfassade**

In einzelnes Element konvertieren Hierarchie beibehalten - Standard

### 7.2 **7.2 Treppe**

In einzelnes Element konvertieren Hierarchie beibehalten - Standard

### 7.3 **7.3 Geländer**

In einzelnes Element konvertieren - Standard Hierarchie beibehalten

## 8. **8. IFC-Schemaoptionen**

### 8.1 **8.1 Materialbeibehaltungsmodus (nur IFC2x3)**

**8.1.1 Elemente niemals explodieren, Beibehaltung wird nicht garantiert** Mit dieser Option werden Sie das ganze Objekt als ein Objekt exportieren

**8.1.2 Nur bei Bedarf explodieren, um Materialien zu erhalten - Standard** Mit dieser Option exportieren Sie nur separate Objekte für jedes zusammengesetzte Material, falls erforderlich

**8.1.3 Alle Elemente in Teile explodieren, Materialien erhalten** Mit dieser Option werden alle Objekte als separate Objekte für jedes Material exportiert. Wenn Sie ein zusammengesetztes Wandmaterial haben, bedeutet dies, dass ein separates Objekt für jedes Material exportiert wird. Sie haben oft eine Dampfsperre mit 1-5 mm, was zu einem sehr dünnen Objekt führt. Wenn Objekte so dünn sind, kann die Geometrie ungenau sein. Problematische Wandmaterialien können so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/11-8-1-material-preservation-mode-ifc2x3-only.png)

Dies kann es für Software schwierig machen, Löcher durch die Oberfläche zu schneiden, da die Ungenauigkeit es schwierig macht, genau zu bestimmen, wo sich das Loch befinden soll. Wenn Sie daher bemerken, dass Ihre Öffnungen nicht durchgeschnitten werden, kann es helfen, diese Option zu aktivieren. Diese Option zu aktivieren, exportiert die Wand als ein einzelnes Objekt anstatt vieler dünner zusammengesetzter Objekte.

## 9. **9. Zusammengesetzte Strukturen und komplexe Profile**

**9.1 Komplexe Baugelemente in Teile aufteilen** Hier können Sie wählen, für welche Elementtypen Sie das zusammengesetzte Element aufteilen möchten und für welche nicht. Wenn Sie diese Option wählen, können Sie keine Wahl für den Materialbeibehaltungsmodus treffen.

## 10. **10. Eigenschaftszuordnung**

In der Eigenschaftszuordnung (Datei > IFC > Interoperabilität > Eigenschaftszuordnung) können Sie wählen, welche Version der IFC Sie exportieren möchten. Sie haben den Standard IFC2x3 und den Standard IFC4. Sie können auch psets hinzufügen, um mit Ihrer IFC zu exportieren. Wenn Sie dies tun, sollten Sie ein Duplikat des von Ihnen gewählten IFC-Schemas erstellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/12-10-property-mapping.png)

Nachdem Sie ein Duplikat Ihres Standard-IFC erstellt haben, können Sie die Eigenschaften, die Sie hinzufügen möchten, zu diesem neuen Voreinstellung hinzufügen, indem Sie das IFC-Schema auswählen und auf _IFC-Eigenschaften für Export zuordnen_ klicken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/13-10-property-mapping.png)

## 11. **11. Datenkonvertierung**

Unter Datenkonvertierung wählen Sie aus, welche Art von Daten Sie zusätzlich zur Geometrie aus Ihrem IFC-Export erhalten möchten. Aktivieren Sie die Kontrollkästchen für das, was Sie exportieren möchten. Elementparameter liest den Archicad-Elementparameter und konvertiert ihn in IFC-Größen oder IFC-Eigenschaften. Je nach Typ. Durch Auswahl dieser Option erhöhen Sie die Dateigröße erheblich.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/14-11-data-conversion.png)

IFC-Basisgrößen liest die Parameter von Größe, Fläche und Volumen. Wenn Sie dieses Kontrollkästchen nicht aktivieren, können beim Importieren Ihrer IFC in Catenda Hub Probleme auftreten.

## 12. **12. Einheitenkonvertierung**

Legen Sie die Einheiten für Länge, Winkel, Fläche, Volumen, Währung und Zeit für Ihren Export fest.
