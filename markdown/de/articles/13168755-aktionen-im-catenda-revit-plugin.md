# Aktionen im Catenda Revit Plugin

> **Hinweis:** Die Installationsdatei für das Plugin finden Sie in [diesem Artikel](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Die Aktionen [Catenda Revit Plugin](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin) finden Sie oben rechts im Plugin-Fenster in der Revit-Anwendung.

So kann das Aktionsmenü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/01-intro.png)

Informationen zu folgenden Themen finden Sie in diesem Artikel:

## 1. **1. Neues Thema**

Klicken Sie auf die grüne Schaltfläche "Neues Thema" oben rechts, um ein neues Thema in dem Projekt zu erstellen, das derzeit im Dropdown-Menü oben links ausgewählt ist. Das Thema wird im Themen-Board erstellt, das im zweiten Dropdown-Menü oben links ausgewählt ist. _Erforderlicher Zugriff:_ Schreibzugriff auf das Themen-Board

Sobald das Thema erstellt ist, wird es in Catenda Hub über den Browser sowie über alle Catenda-Plugins in anderen Programmen angezeigt. So kann die neue Themenseite aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/02-1-new-topic.png)

Die minimalen Informationen, die erforderlich sind, um ein Thema einzureichen, sind ein Titel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/03-1-new-topic.png)

### 1.1 **1.1 Einreichen**

Wenn das Thema bereit ist, um mit dem Projekt geteilt zu werden, klicken Sie auf "Einreichen", um das Thema im Themen-Board einzureichen.

## 2. **2. IFC hochladen**

Klicken Sie im Aktionsmenü, das sich mit den drei Punkten oben rechts öffnet, auf "IFC hochladen", um Ihr aktuelles Revit-Modell direkt als IFC-Datei in Catenda Hub hochzuladen. So kann die Seite "IFC hochladen" aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/04-2-upload-ifc.png)

### 2.1 **2.1 Modell auswählen**

In diesem Dropdown-Menü werden bereits vorhandene Modelle aus dem ausgewählten Projekt angezeigt. Falls kein Modell im Projekt vorhanden ist, erstellen Sie zunächst ein leeres Modell in Catenda über den Browser. Das hochgeladene IFC wird eine neue Revision des ausgewählten Modells. Jedes Modell in Catenda ist mit einem Dokumentcontainer verknüpft, sodass die Revision nach dem Hochladen sowohl in den Modell- als auch in den Dokumentbereichen des Projekts sichtbar ist.

### 2.2 **2.2 Dateiname**

Geben Sie einen optionalen Dateinamen ein, der mit dem Hochladen verknüpft ist. In diesem Feld werden nur ASCII-Zeichen unterstützt.

### 2.3 **2.3 Kommentar eingeben**

Geben Sie einen erforderlichen Kommentar ein, der mit dem Hochladen verknüpft ist. Sobald ein Kommentar hinzugefügt wird, wird die Schaltfläche "Hochladen" hervorgehoben und ist anklickbar. In diesem Feld werden nur ASCII-Zeichen unterstützt.

### 2.4 **2.4 Exportkonfiguration**

Wählen Sie eine IFC-Konfiguration. Eine neue Konfiguration kann im IFC-Exportmenü in Revit erstellt werden. Sie können auch \<Catenda-Konfiguration> für eine benutzerfreundliche Konfiguration auswählen, die sich gut für Catenda Hub eignet.

Dies sind die Exporteinstellungen des Catenda Setup

```
selectedConfig.Name = "<Catenda Setup>"; selectedConfig.IFCVersion = IFCVersion.IFC2x3CV2; selectedConfig.SpaceBoundaries = 1; selectedConfig.ActivePhaseId = ElementId.InvalidElementId; selectedConfig.ExportBaseQuantities = true; selectedConfig.SplitWallsAndColumns = false; selectedConfig.VisibleElementsOfCurrentView = false; selectedConfig.Use2DRoomBoundaryForVolume = false; selectedConfig.UseFamilyAndTypeNameForReference = true; selectedConfig.ExportInternalRevitPropertySets = true; selectedConfig.ExportIFCCommonPropertySets = true; selectedConfig.Export2DElements = false; selectedConfig.ExportPartsAsBuildingElements = true; selectedConfig.ExportBoundingBox = false; selectedConfig.ExportSolidModelRep = false; selectedConfig.ExportSchedulesAsPsets = false; selectedConfig.ExportUserDefinedPsets = false; selectedConfig.ExportUserDefinedPsetsFileName = ""; selectedConfig.ExportLinkedFiles = false; selectedConfig.IncludeSiteElevation = true; selectedConfig.UseActiveViewGeometry = false; selectedConfig.ExportSpecificSchedules = false; selectedConfig.TessellationLevelOfDetail = 0; selectedConfig.StoreIFCGUID = true; selectedConfig.ExportRoomsInView = true;
```

### 2.5 **2.5 Hochladen**

Klicken Sie auf "Hochladen", um ein IFC hochzuladen. Ein Kommentar muss hinzugefügt werden, um hochzuladen. _Erforderlicher Zugriff:_ Schreibzugriff auf das Dokument, das mit dem Modell verknüpft ist.

## 3. **3. Einstellungen**

Die Einstellungsseite ermöglicht es Ihnen, zu ändern, wie das Plugin eine 3D-Ansicht erstellt, wenn Sie die [Zoom-Funktion](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin#h_36392f671a) verwenden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/05-3-settings.png)

### 3.1 **3.1 Zurück zu den Themen**

Klicken Sie auf "Zurück zu den Themen", um zur Themenliste zurückzukehren.

### 3.2 **3.2 Navigation**

**3D-Ansicht orthografisch halten** Diese Option erzwingt, dass die Revit 3D-Ansicht orthografisch ist, selbst wenn der entsprechende Viewpoint mit einer perspektivischen Ansicht erstellt wurde.

**Neue Ansicht für jedes Thema erstellen** Anstatt dieselbe 3D-Ansicht jedes Mal wiederzuverwenden, wenn Sie die Zoom-Funktion verwenden, erstellt diese Option jedes Mal eine neue 3D-Ansicht für jedes Thema, wenn Sie die Zoom-Funktion verwenden.

**3D-Ansicht-Namenssuffix** Dieser Text wird dem Namen der 3D-Ansicht hinzugefügt, die bei Verwendung der Zoom-Funktion erstellt wird.

### 3.3 **3.4 Viewpoint-Transformation**

Mit der Viewpoint-Transformation kann der Viewpoint in Revit so konfiguriert werden, dass er um einen bestimmten Betrag versetzt ist. Wenn hier Werte konfiguriert wurden, wird der Viewpoint jedes Mal um diesen Betrag versetzt, wenn ein Viewpoint aus einem Thema wiedergegeben wird. Dies kann nützlich sein, wenn die Koordinaten im Thema-Viewpoint nicht mit den in dem Revit-Projekt konfigurierten Koordinaten übereinstimmen.

**3.4.1 X (E/W)** Transformation in X-Richtung. Ost oder West abhängig von positiven oder negativen Werten. Einheiten in Metern

**3.4.2 Y (N/S)** Transformation in Y-Richtung. Nord oder Süd abhängig von positiven oder negativen Werten. Einheiten in Metern

**3.4.3 Z (Elev)** Transformation in Z-Richtung. Höhe abhängig von positiven oder negativen Werten. Einheiten in Metern

**3.4.4 Winkel** Rotationstransformation. Höhe abhängig von positiven oder negativen Werten. Einheiten in Grad. Die Kamera bleibt in der gleichen Höhe und dreht die Kamera um einen Punkt im Modell.

## 4. **4. Konto**

Öffnen Sie Ihre Catenda Hub-Kontoseite in Ihrem Standardbrowser. Klicken Sie [hier](https://support.catenda.com/en/articles/6880968-account-page), um mehr über die Kontoseite zu erfahren.

## 5. **5. Abmelden**

Klicken Sie auf "Abmelden", um sich aus Catenda Hub im Plugin abzumelden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/06-5-sign-out.png)

Nach dem Abmelden wird die Anmeldungsseite angezeigt, auf der sich das gleiche Konto oder ein anderes Konto mit Benutzername und Passwort anmelden kann. Klicken Sie [hier](https://support.catenda.com/en/articles/7891486-sign-in-page), um mehr über die Anmeldungsseite zu erfahren.

Nach erneuter Anmeldung wird das erste Projekt in der Projektliste angezeigt. Wählen Sie erneut ein Projekt in der Projektliste aus, um ein anderes Projekt anzuzeigen.
