# Themen-Austausch

Sie finden die Aktion zum Austausch von Themen im [Menü "Neues Element"](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_8c642e051a) oben rechts in einem Themen-Board. Das Menü zum Austausch von Themen kann etwa wie folgt aussehen:

![Dateibasierter Austausch neues topic exchange topics History Import BCF Export topics mit BCF-kompatiblem Client verbinden Themen direkt mit einem BCF-kompatiblen Client synchronisieren, indem Sie die folgende URL verwenden](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/01-intro.png)

## 1. **BCF importieren**

Verwenden Sie die BCF-Importaktion, um BCF-Dateien zu importieren. So könnte der BCF-Importdialog aussehen:

![Import BCF BCF-Datei hochladen: Datei auswählen Durchsuchen Board auswählen Neue Typen und Status aus der BCF-Datei generieren](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/02-import-bcf.png)

Catenda verpflichtet sich zu 100% zu offenen Standards. Darauf basierend haben wir den Import und Export von BCF (BIM Collaboration Format) implementiert. Dies bedeutet, dass der Benutzer Themen von/zu anderer Software, die dieses Format unterstützt (z. B. Solibri, Navisworks und viele andere), importieren und exportieren kann. Sie können beispielsweise eine Datei mit Kollisionskontrolldaten für das gleiche Modell importieren, das in einer anderen Softwareanwendung erstellt wurde. So können Sie Ihren Arbeitsablauf in Catenda fortsetzen.

**Mehrere Themen pro BCF** Eine BCF-Datei kann mehrere Themen enthalten

**Maximale Dateigröße** Die maximale BCF-Dateigröße, die importiert werden kann, beträgt 500 MB.

### 1.1 **BCF-Datei hochladen**

Klicken Sie auf "Durchsuchen", um eine BCF-Datei zum Hochladen auszuwählen

### 1.2 **Board auswählen**

Wählen Sie das Themen-Board aus, in das das Thema importiert werden soll.

### 1.3 **Neue Typen und Status aus der BCF-Datei generieren**

Wenn Ihre BCF-Datei Status und Typen enthält, die nicht im Themen-Board vorhanden sind, können Sie diese automatisch erstellen, indem Sie dieses Kontrollkästchen aktivieren. _Erforderlicher Zugriff:_ Vollzugriff auf das Themen-Board

Wenn Ihre BCF-Datei Status und Typen enthält, die nicht im Themen-Board vorhanden sind, werden die nicht vorhandenen Status/Typen nicht verknüpft, wenn dieses Kontrollkästchen nicht aktiviert bleibt. Nach Abschluss des Imports können Sie die nicht verknüpften Status/Typen auf vorhandene Status/Typen abbilden.

_Mehrere Status/Typen auf einmal verknüpfen_ Wenn es nicht verknüpfte Status/Typen in einem Themen-Board gibt, wird eine orange Warnmeldung angezeigt, dass es nicht verknüpfte Felder in einem Themen-Board gibt. _Erforderlicher Zugriff:_ Projektadministrator

![Topics Es gibt nicht verknüpfte Felder in diesem topic board Klicken Sie hier zum Verknüpfen](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/03-generate-new-types-and-statuses-from-the-bcf-file.png)

Wenn Sie auf den Link klicken, werden Sie zum Bereich [Nicht verknüpfte Felder](https://support.catenda.com/en/articles/4670277-topic-board-settings#h_3bd7e3e759) der [Themen-Board-Einstellungen](https://support.catenda.com/en/articles/4670277-topic-board-settings) weitergeleitet, wo Sie alle Felder einer Art auf einmal auf einen vorhandenen Wert verknüpfen können.

## 2. **Themen exportieren**​

Sie können Themen entweder exportieren, indem Sie "Themen exportieren" im [Menü "Neues Element"](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_8c642e051a) oben rechts im Themen-Board wählen, oder indem Sie ein Thema in der Themenliste auswählen und die Exportoption im [Menü "Ausgewähltes Element"](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_b5c00c149b) über dem Themen-Board wählen. Der Exportdialog für Themen kann etwa wie folgt aussehen:

![Export topics Alle topics aus dem aktuellen topic board Aktueller Filter Ausgewählte topics BCF Excel PDF v3.0](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/04-export-topics.png)

> **Hinweis:** Themen können jeweils nur von einem Themen-Board exportiert werden.

### 2.1 **Filteroptionen**

**Alle Themen vom aktuellen Board**

**Aktueller Filter**

**Ausgewählte Themen**

### 2.2 **BCF-Export**

Je nachdem, welche BCF-Version Sie wählen, erhalten Sie verschiedene Dateitypen. BCF v3.0 und v2.1 erzeugen eine .bcf-Datei, während v2.0 eine .bcfzip erzeugt

### 2.3 **Excel-Export**

Es ist möglich, Themen in Excel zu exportieren. Es gibt eine Zeile pro Thema und eine Spalte pro Spalte in der Tabellenansicht des Themen-Boards. Die Reihenfolge der Spalten ist die gleiche wie in der Standard-Spaltenreihenfolge des Themen-Boards [Tabellenansicht](https://support.catenda.com/en/articles/6941099-table-view-in-an-topic-board#h_3102328063).

> **Hinweis:** Keine Bilder und nur der letzte Kommentar in einem Thema werden exportiert.

### 2.4 **PDF-Export**

Klicken Sie [hier](https://support.catenda.com/en/articles/9784934-exporting-topics-to-pdf), um mehr über den Export von Themen als PDF zu erfahren

## 3. **Berichtseite**

Mit der Berichtseite ist es möglich, benutzerdefinierte Berichte nicht nur über Themen, sondern auch über Dokumente zu erstellen. Die Berichtseite ist eine On-Demand-Funktion, die für laufende Projekte aktiviert werden kann. Neue Projekte, die auf einem Vorlagenprojekt basieren, bei dem diese Funktion aktiviert ist, haben diese Funktion nicht aktiviert. Diese Berichte können dann nicht nur in Excel und PDF, sondern auch in vielen weiteren Dateiformaten exportiert werden. Klicken Sie [hier](https://support.catenda.com/en/articles/12303098-reports-page), um mehr über die Berichtseite zu erfahren

## 4. **Mit einem BCF-Client verbinden**

Wenn Sie Catenda Hub als BCF-Server verwenden, können Sie sich direkt mit anderer Software verbinden. Hier können Sie Themen von dort aus zu und von Catenda senden und empfangen, ohne Themen exportieren und importieren zu müssen. Dies nutzt die standardisierte (von buildingSMART International) BCF-API. Beispiele für Software, die dies unterstützen, sind Navisworks, Revit, Archicad und Solibri. In dieser Software können Sie die allgemeine URL zu unserem Server verwenden, die [https://api.catenda.com/](https://api.catenda.com/) ist, wonach Sie alle Themen-Boards aus allen Ihren Projekten abrufen. Dies kann schnell zu einer langen Liste werden, daher stellen wir Ihnen den Link zu Ihrem aktuellen Themen-Board in diesem Menü zur Verfügung. Wenn Sie stattdessen diesen Link verwenden, können Sie die gesuchten Themen leicht finden.
