# Modellbaum-Panel

Das Modellbaum-Panel befindet sich als eines von vier [Projektpaneln](https://support.catenda.com/en/articles/13141464-project-panels), die oben rechts auf dem Bildschirm geöffnet werden können.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/01-intro.png)

## 1. **Öffnen des Modellbaum-Panels**

Das Modellbaum-Panel kann neben einem der anderen Panels geöffnet werden.

_Öffnen des_ Modellbaums _Panels:_ Klicken Sie auf das Baumsymbol oder drücken Sie [Umschalt+3](https://support.catenda.com/en/articles/4670267-summary-of-most-important-shortcuts-and-basic-controls#:~:text=row%20of%20objects-,Shift%20%2B%203,-Control%20%2B%20left%20click)

_Isolieren des_ Modellbaums _Panels:_ Öffnen Sie das Panel des Baums. Schließen Sie alle anderen geöffneten Panels, indem Sie darauf klicken.

## 2. **Modellbaum** **Panel-Inhalt**

Im Baumfenster kann der Inhalt der IFC in verschiedenen Baumstrukturen angezeigt werden. Die angezeigte Struktur stammt direkt aus dem IFC-Modell, das oben ausgewählt ist. Jeder der Bäume zeigt Teile der IFC auf unterschiedliche Weise an. Listenelemente für Objekte, die im 3D-Viewer sichtbar sind, können in einem oder mehreren der Modellbäume sichtbar sein, je nachdem, ob sie dieser Viewing-Methode des IFC-Inhalts entsprechen. Andere Listenelemente können Gruppierungen dieser Objekte und/oder andere Entitäten aus der IFC enthalten.

### 2.1 **Benennungen von Listenelementen**

Listenelemente können auf verschiedene Weise benannt werden. Benannte Entitäten können nach dem Namen benannt werden, der ihnen in der IFC zugewiesen wurde, aber Entitäten können auch nach dem Namen der Entität selbst benannt werden, wie im BuildingSMART-Standard angegeben. Wenn keine Übersetzung pro Standard verfügbar ist, kann der Name auf Englisch angezeigt werden, das ist die Basissprache. Um zu den Übersetzungen im offenen Standard beizutragen, siehe [hier](https://user.buildingsmart.org/knowledge-base/ifc-translations-manual/). Um zu sehen, ob eine Entität eine Übersetzung hat, gehen Sie zur BuildingSMART-Seite für diese Entität und ändern Sie die Sprache. Der Entitätsname wird entweder übersetzt oder es gibt eine Meldung oben, dass dieser Entität die Übersetzung fehlt.

**Gruppierungsentitäten** Entitäten, die andere Entitäten enthalten können, wie ein Gebäude, das Wände enthält, können nach dem Namen benannt werden, der dieser Entität gegeben wurde, falls vorhanden, oder nach dem Namen der Entität pro BuildingSmart-Standard.

**Einzelne Elemente** Einzelne Elemente sind die Elemente auf der untersten Ebene, wenn die Baumansicht vollständig erweitert ist, und können wie folgt aussehen:

`Entity.Set.Number`

Name Diese Elemente sind nach dem Namen ihrer Entität gemäß dem BuildingSMART-Standard aufgelistet.

Set Es gibt oft viele ähnliche Elemente, die zusammengefasst sind. Nach dem Entitätsnamen folgt die Nummer des n-ten Satzes dieser Arten von Entitäten, zu dem diese Entität gehört.

Number Die Nummer der n-ten Entität in der Menge ist aufgelistet. Zum Beispiel kann das 21. Fenster auf Ebene 2 wie folgt aussehen:

`Window.1.21`

### 2.2 **Hervorgehobene Elemente**

Wie im 3D-Viewer sind ausgewählte Objekte grün und ausgewählte Objektgruppen gelb hervorgehoben. Im Gegensatz zum 3D-Viewer ist es auch möglich, Entitäten hervorzuheben, die Objekte enthalten können, und Sätze von Objekten hervorzuheben, die ähnlich sind. Wenn ein Objekt im 3D-Viewer hervorgehoben ist, aber kein Objekt im Modellbaum-Panel hervorgehoben ist, könnte es sein, dass das Objekt in einem anderen Modellbaum-Menü hervorgehoben ist.

**Zum Listenelement zoomen** Bäume können ziemlich lang werden. Wenn ein Objekt im 3D-Viewer ausgewählt ist, wird das Baummenü zu der Stelle in der Liste gescrollt, wo das ausgewählte Objekt existiert, vorausgesetzt, dass dieses Objekt in dem Baummenü existiert, das im Modellbaum-Panel offen ist.

### 2.3 **Auswahl**

Listenelemente aus mehreren Modellen, die im 3D-Viewer geladen sind, können ausgewählt werden. Klicken Sie auf das Dropdown-Menü oben, um zwischen den verschiedenen Modellen zu wechseln. Auswahlen können im Auswahlmenü gespeichert werden.

**Aktives Element** Das aktive Element ist mit einem roten gepunkteten Umriss hervorgehoben. Verwenden Sie die Pfeiltasten, um die Liste auf und ab zu verschieben.

**Einzelauswahl** Nach dem Klicken auf ein Listenelement, um es auszuwählen, wird das Element zum aktiven Element und die vorherige Auswahl wird gelöscht.

Klicken Sie auf ein Listenelement oder drücken Sie die Eingabetaste auf dem aktiven Element, um: Ein Objekt auszuwählen. Eine Reihe von Objekten und alle ähnlichen Objekte in einer Reihe von Objekten auszuwählen. Eine Gruppe von Sätzen und alle Subelemente in dieser Gruppe auszuwählen.

**Auswahl bearbeiten** Drücken Sie Strg+Klick auf ein Listenelement oder Strg+Eingabetaste auf dem aktiven Listenelement, um: Listenelemente, die nicht zuvor ausgewählt waren, zur Auswahl hinzufügen. Ausgewählte Listenelemente aus der Auswahl entfernen.

**Auswahl festlegen** Shift+Klick auf ein Listenelement oder Shift+Eingabetaste auf dem aktiven Listenelement, nachdem Sie ein anderes Listenelement ausgewählt haben, um: Alle Listenelemente zwischen dem zuvor ausgewählten Element und dem ausgewählten Element auszuwählen.

**Zum Listenelement zoomen** Doppelklick auf ein Listenelement, um im 3D-Viewer auf dieses Listenelement zu zoomen.

## 3. **Containment-Baum**

Der Containment-Baum bietet eine hierarchische Perspektive auf die Beziehungen zwischen den verschiedenen IFC-Objekten.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/02-containment-tree.png)

Wenn die Tastenkombi "`p`" gedrückt wird, um den übergeordneten Knoten auszuwählen, kann dies visuell im Containment-Baum beobachtet werden.

## 4. **Komponenten-Baum**

Der Komponenten-Baum bietet eine hierarchische Perspektive auf die Komponenten, die ein Objekt ausmachen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/03-component-tree.png)

In diesem Baummenü können Komponenten wie die folgenden gefunden werden:

AirTerminal Annotation Beam BuildingElementPart BulidingElementproxy Coil Column Covering CurtainWall Damper Distributionport DiscreteAccessory Ductfitting DuctSilencer Door ElementAssembly EnergyConversionDevice Fan Fastener Filter FireSuppresionTernimal FlowController FlowFitting FlowMovingDevice FlowSegment FlowStoragedevice FlowTerminal Footing FurnishingElement GeographicElement Grid HeatExchanger LightFixture Member OpeningElement PipeFitting PipeSegment Pump Plate Railing Ramp Roof SanitaryTerminal Site Slab Space SpaceHeater StackTerminal Stair StairFlight TransportElement UnitaryEquipment Valve Wall WallStandardCase WasteTerminal Window

## 5. Typbaum

Der Typbaum zeigt alle Objekte sortiert nach ihrem Typ.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/04-type-tree.png)

## 6. Ebenenbaum

Der Ebenenbaum bietet eine hierarchische Ansicht der Ebenen im Modell.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/05-layer-tree.png)

## 7. Systembaum

Der Systembaum bietet eine Ansicht der Systeme im Modell.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/06-system-tree.png)

> **Hinweis:** Das im Baum und im Modell ausgewählte Objekt ist synchronisiert. Wenn Sie im 3D-Modus auf ein Fenster klicken, wird es im Baum ausgewählt. Und umgekehrt. Sie können auch auf ein "Blatt" im Modell doppelklicken und die 3D-Kamera zu diesem Objekt bewegen.
