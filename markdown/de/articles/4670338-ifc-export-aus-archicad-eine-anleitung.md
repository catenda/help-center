# IFC Export Archicad Handbuch

Wenn Sie eine IFC exportieren, beachten Sie, was für Ihren IFC-Export relevant ist. Die IFC-Datei kann groß und schwierig zu bearbeiten sein, wenn sie viele Informationen enthält. Daher ist es wichtig, keine unnötigen Informationen zu exportieren. In diesem Bericht erhalten Sie verschiedene Tipps zum Filtern Ihres IFC-Exports in Archicad.

## 1. Projektinformationen

Stellen Sie vor dem Exportieren einer IFC aus Ihrem Projekt sicher, dass die Projektinformationen konfiguriert sind. Die Projektinformationen finden Sie hier:

`Datei -> Info -> Projektinformationen`

So können die Projektinformationen aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/01-project-info.png)

Standardmäßig sind die verschiedenen Felder leer. Auch wenn sie leer sind, wird für jedes Projekt, jeden Standort und jedes aufgeführte Gebäude eine eindeutige ID erstellt. In einigen Situationen werden mehrere IFC-Dateien aus demselben Archicad-Projekt exportiert. Beispiele hierfür sind:

IFC-Dateien mit Objekten aus verschiedenen Fachbereichen. Ein MEP-Modell mit Kanälen, ein Architekturmodell mit Wänden und ein Tragwerksmodell mit allen Platten.

Mehrere Gebäude Manchmal sind mehrere Gebäude in derselben Archicad-Datei modelliert und für jedes wird eine separate IFC exportiert.

Unterschiedliche Designentscheidungen. Wenn verschiedene Variationen eines Gebäudes in derselben Archicad-Datei modelliert sind, wird jede Variante oft in ihre eigene IFC-Datei exportiert.

### 1.1 Konfigurieren der Projektinformationen

Unabhängig davon, ob mehrere IFC-Dateien exportiert werden sollen oder nicht, ist es oft eine gute Idee, Werte in die Projektinformationen einzugeben, damit diese später nicht geändert werden müssen. Die Projektinformationen sind wichtig zum Ausfüllen, da sie die GUIDs der Datei beeinflussen. Jeder exportierte IFC-Typ sollte seine eigenen Projekteinstellungen haben. Die Projekteinstellungen können unten rechts importiert und exportiert werden. Auf diese Weise können mehrere Profile für die Exporte aus der Datei unterstützt werden. Für Catenda ist es wichtig, dass IFCs in verschiedenen Modellen unterschiedliche Informationen konfiguriert haben, während IFCs, die sich im selben Modell befinden, die gleichen Informationen konfiguriert haben.

## 2. IFC-Exporteinstellungen

Um das gesamte Projekt zu exportieren. Sie müssen sich in der 3D-Ansicht befinden. Stellen Sie sicher, dass Sie den korrekten Translator verwenden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/02-ifc-export-settings.png)

Klicken Sie auf die Schaltfläche "Optionen", um eine Zusammenfassung Ihrer IFC-Exporteinstellungen anzuzeigen. Im Modellfilter können Sie auch weitere Filter auswählen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/03-ifc-export-settings.png)

Das Feld "IFC-Translatoren" ermöglicht es Ihnen, Translatoreinstellungen anzuzeigen oder zu ändern, oder neue Translatoren zu erstellen.

Wenn Sie Ihren IFC-Export ändern möchten, wird empfohlen, einen der vordefinierten Translatoren zu duplizieren, damit Sie keinen der Standard-Translatoren beschädigen. Duplizieren Sie einen Translator hier:

Klicken Sie auf Neu > Duplikat von > wählen Sie den gewünschten Translator aus.

Wenn Sie die IFC zusammenführen möchten, können Sie dies unter dem gleichen Banner tun.

![image-2.png](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/04-ifc-export-settings.png)

---

### 2.1 Verschiedene Einstellungen beim Export

1\. [Modellfilter](#model-filter) ermöglicht es Ihnen, herauszufiltern, was Sie nach verschiedenen Voreinstellungen exportieren möchten. 2\. [Typzuordnung](#type-mapping) ermöglicht es Ihnen, auszuwählen, welchen IFC-Typ jedes Element exportiert. 3\. [Geometriekonvertierung](#geometry-conversion) ermöglicht es Ihnen, zu wählen, welche Art von Geometrie Sie exportieren möchten. 4\. [Eigenschaftenzuordnung](#property-mapping) ermöglicht es Ihnen, Kriterien basierend auf Typen einzurichten. 5\. [Datenkonvertierung](#data-conversion) ermöglicht es Ihnen, zu wählen, welche Art von Daten Sie aus dem Modell exportieren möchten. 6\. [Einheitenkonvertierung](#unit-conversion) ermöglicht es Ihnen, zu wählen, welche Messenheiten Sie in Ihrer IFC exportieren möchten.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/05-different-settings-in-the-export.png)

---

## 3. Modellfilter

### 3.1 Exportieren von Gittern in der IFC

Manchmal möchten Sie auch die Gitter exportieren, um sie in Catenda Hub sehen zu können.

Gehen Sie zum Modellfilter für den IFC-Export und stellen Sie sicher, dass das Kontrollkästchen "Gittersystem und Elemente" aktiviert ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/06-exporting-grids-in-the-ifc.png)

---

## 4. Typzuordnung

Wenn eine IFC exportiert wird, wird jedem Element im Modell ein IFC-Typ zugewiesen.

Wenn Sie den gewünschten IFC-Translator auswählen, können Sie zur Typzuordnung gehen und auf "IFC-Typen für Import zuordnen" klicken, um zu verwalten, welche Art von Typzuordnung Sie in Ihrer exportierten IFC wünschen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/07-2-type-mapping.png)

Die Typzuordnung hat hauptsächlich zwei verschiedene Optionen zum Sortieren Ihrer IFC-Typen.

### 4.1 Elementtyp

Jedem Element wird automatisch ein grundlegender IFC-Typ zugewiesen. Sie können den zugewiesenen IFC-Typ jedes Elements im Projektmanager und in den Elementeinstellungen sehen.

### 4.2 Klassifikation

Diese Methode ermöglicht eine flexiblere und detailliertere IFC-Typzuordnung gemäß festgelegter Klassifikationsstandards. Zone- und Öffnungselemente werden auf einen festen IFC-Typ gesetzt. IFCSpace und IFCOpeningElements.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/08-classification.png)

---

## 5. Geometriekonvertierung

Die Geometriekonvertierung für den IFC-Export ermöglicht es Ihnen, Ihre Geometrie auf verschiedene Arten zu konvertieren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/09-3-geometry-conversion.png)

### 5.1 Konvertierungen von Archicad-Elementen

**Alle Geometrien von Modellelementen exportieren als:** _Parametrisch mit Ausnahmen_ - Standard _BREP_ - Präzise Geometrie - Wenn dies ausgewählt ist, sind die nächsten zwei Optionen auch BREP

**Elemente in Solid Element Operations:** _Extrudiert/gedreht_ - Standard _BREP_ - Präzise Geometrie

Elemente mit Übergängen Einige Elemente können sich mit anderen Elementen überschneiden, die Teile der Extrusion abschneiden können. _Extrudiert/gedreht_ - Ecken von Elementen verbinden Dies fügt Übergänge zu Ihren extrudierten Elementen hinzu. Mit dieser Option sehen Sie, dass Elemente wie Wände oder Dächer, besonders schräge, schön verbunden sind.

_Extrudiert/gedreht ohne Übergänge_ - Standard - Dies macht den Export schneller Wenn Sie 90-Grad-Elemente wie Wände oder Dächer haben, werden Sie wahrscheinlich keinen Unterschied zu dieser Option bemerken. Wenn Sie schräge Wände haben, werden Sie bemerken, dass an der Ecke, wo sich die Wände treffen, statt das Überschuss der geraden Extrusion abzuschneiden, die Wände einfach gerade aneinander vorbeigehen und nicht schön verbunden sind.

_BREP_ - Präzise Geometrie

Parametrische Elemente Archicad-Elemente können als parametrische Geometrie, oft in Form von Führungslinien, die um eine Distanz extrudiert werden, exportiert werden. Parametrische Geometrie macht es einfach, das Objekt nach seiner Erstellung zu bearbeiten. Während diese Option die Bearbeitbarkeit beibehält, kann die Geometrie oft etwas ungenau sein, da die Definition eine Näherung der Geometrie ist. Diese Option wird empfohlen, wenn Sie die IFC zurück in Archicad oder ein anderes Bearbeitungsprogramm importieren möchten, um weitere Änderungen vorzunehmen.

BREP Export Geometrie als separate BREP-Flächen. Statt die Objekte durch ihre Parameter wie Länge/Breite/Höhe mit daraus resultierenden Flächen zu beschreiben, wird jede Fläche als separate Fläche mit einem Ort im 3D-Raum beschrieben. Objekte können immer noch mehrere Flächen enthalten, aber diese sind lose Flächen. Nach dem Exportieren müssen BREP-Flächen einzeln bearbeitet werden, da keine Parameter mehr auf die Fläche angewendet werden. Mit der BREP-Option werden exakte Flächen exportiert, ohne Raum für Unterschiede in der Interpretierung von Parametern zwischen Authoring-Tools. Flächen werden einzeln gefärbt und haben die gleiche Farbe in Catenda Hub wie in Archicad. Oberflächenfarben können im folgenden Menü konfiguriert werden:

`Optionen -> Elementattribute -> Oberflächen`

Es kann hilfreich sein, alle Einstellungen für eine Fläche zu konfigurieren, da diese in die IFC geschrieben werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/10-conversions-of-archicad-elements.png)

Flächen im Catenda 3D-Viewer haben flache Schattierung ohne Lichtquelle. Das bedeutet, dass Werte wie Ambient, Attenuation, Shinyness, Emission und Specular nicht interpretiert werden, wenn die Fläche im Catenda 3D-Viewer angezeigt wird. Die folgenden Werte werden von Catenda bei der Anzeige der Fläche im 3D-Viewer interpretiert:

Oberflächenfarbe Die Farbe der Oberfläche

Durchlässigkeit Wie viel Sie durch das Objekt sehen können (Überlagert die transluzente Deckkraft-Einstellung)

Diffus Wie dunkel oder hell die Oberflächenfarbe ist

**IFC-Modellposition definieren nach:** Diese Option bestimmt den Projektort. Es ist wichtig, einen gemeinsamen Koordinatenpunkt zu vereinbaren, auf den in dem Projekt bereits am Anfang verwiesen werden soll, da eine Änderung bedeuten könnte, dass mehrere Berater ihre Objekte verschieben müssen, was am Ende eines Projekts oft nicht machbar ist.

Vermessungspunkt und Projektherkunft - Standard Mit dieser Option ist der Abstand von (0,0,0) zu Ihrem Modell in Archicad der Abstand von (0,0,0 + Koordinaten Ihres Vermessungspunkts) zu Ihrem Modell in Catenda Hub + der Wenn Sie einen Projektstandort eingestellt haben, endet Ihr Modell bei diesen Koordinaten in Catenda Hub

Nur Projektherkunft Mit dieser Option ist der Abstand von (0,0,0) zu Ihrem Modell in Archicad der Abstand von (0,0,0) zu Ihrem Modell in Catenda Hub.

Nur Vermessungspunkt Mit dieser Option ist der Abstand vom Vermessungspunkt in Archicad zu Ihren Modellen der Abstand von (0,0,0) zu Ihrem Modell in Catenda Hub

### 5.2 IFC-Schema verwandte Optionen

**Materialerhaltungsmodus (nur IFC2x3)** - Elemente nie explodieren, Erhaltung nicht garantiert Mit dieser Option exportieren Sie das gesamte Objekt als ein Objekt

- Nur bei Bedarf explodieren, um Materialien zu erhalten - Standard
  Mit dieser Option exportieren Sie nur separate Objekte für jedes Verbundmaterial, wenn erforderlich

- Alle Elemente in Teile explodieren, Materialien erhalten
  Mit dieser Option werden alle Objekte als separate Objekte für jedes Material exportiert

Wenn Sie ein Verbundwandmaterial haben, bedeutet dies, dass für jedes Material ein separates Objekt exportiert wird. Oft haben Sie eine Dampfbremse, die 1-5 mm beträgt, was zu einem sehr dünnen Objekt führt. Wenn Objekte so dünn sind, kann die Geometrie ungenau sein. Problematische Wandmaterialien können so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/11-ifc-schema-related-options.png)

Dies kann es für die Software schwierig machen, Löcher durch die Oberfläche zu schneiden, da die Ungenauigkeit es schwierig macht, genau zu bestimmen, wo das Loch sein soll. Wenn Sie also bemerken, dass Ihre Öffnungen nicht durchgeschnitten werden, kann es hilfreich sein, diese Option einzuschalten. Wenn Sie diese Option einschalten, wird die Wand als ein einzelnes Objekt anstatt vieler dünner Verbundobjekte exportiert.

### 5.3 Zusammensetzungen und komplexe Profile

**Komplexe Bauelemente in Teile aufteilen** Hier können Sie wählen, für welche Art von Elementen Sie das Verbundelement aufteilen möchten und für welche nicht. Wenn Sie diese Option wählen, können Sie keine Wahl für den Materialerhaltungsmodus treffen.

---

## 6. Eigenschaftenzuordnung

Innerhalb der Eigenschaftenzuordnung (Datei > IFC > Interoperabilität > Eigenschaftenzuordnung) können Sie wählen, welche Version von IFC Sie exportieren möchten. Sie haben den Standard IFC2x3 und den Standard IFC4. Sie können auch psets exportieren mit Ihrer IFC hinzufügen. Wenn Sie dies tun, sollten Sie ein Duplikat des IFC-Schemas erstellen, das Sie wählen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/12-4-property-mapping.png)

Nachdem Sie ein Duplikat Ihres Standard-IFC erstellt haben, können Sie die gewünschten Eigenschaften zu dieser neuen Voreinstellung hinzufügen, indem Sie das IFC-Schema auswählen und auf _IFC-Eigenschaften für Export zuordnen_ klicken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/13-4-property-mapping.png)

---

## 7. Datenkonvertierung

Bei der Datenkonvertierung wählen Sie aus, welche Art von Daten Sie neben der Geometrie aus Ihrem IFC-Export erhalten möchten. Aktivieren Sie die Kontrollkästchen für die Elemente, die Sie exportieren möchten.

Elementparameter liest den Archicad-Elementparameter und konvertiert ihn in IFC-Mengen oder IFC-Eigenschaften. Je nach Typ. Durch die Wahl dieser Option vergrößern Sie die Dateigröße erheblich.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/14-5-data-conversion.png)

IFC-Basismengen liest die Parameter Größe, Fläche und Volumen. Wenn Sie dieses Kontrollkästchen nicht aktivieren, können Sie Ihre IFC möglicherweise nicht in Catenda Hub importieren.

## 8. Einheitenkonvertierung

Legen Sie die Einheiten für Länge, Winkel, Fläche, Volumen, Währung und Zeit für Ihren Export fest.
