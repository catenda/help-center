# 3D DWG Export-Handbuch

Programme, die 3D DWGs zu IFC exportieren können:

### **AutoCAD Architektur**

[Export-Menü](#h_9ac38304dd)

### **AutoCAD MEP**

[Export-Menü](#h_9ac38304dd)

### **AutoCAD Civil 3D**

[Export-Menü](#h_9ac38304dd)

### **AutoCAD Plant 3D:**

Wenn Sie AutoCAD Plant 3D verwenden, können Sie den Object Enabler für die Version von Plant 3D installieren, die Sie verwenden. Mit dem installierten Object Enabler können Sie Ihre Datei in einem der oben genannten Programme öffnen, um zu IFC zu exportieren. Falls Sie keinen Zugriff auf eine der oben genannten Software haben, können Sie versuchen, ein Plugin eines Drittanbieters wie Codemill IFC Export für Autodesk® AutoCAD® Plant3D zu verwenden. Obwohl dieses Plugin behauptet, auch IFC 4 zu exportieren, was mit dem Object Enabler nicht möglich ist, beachten Sie, dass dies kein offizieller Exporter ist und beim Import möglicherweise Probleme auftreten.

### **Revit**

Es ist möglich, eine 3D DWG in Revit zu importieren. Obwohl Revit beim Export zu IFC viele weitere Optionen bietet, ist es nicht ideal, eine importierte 3D DWG zu IFC zu exportieren. Wenn Sie dies versuchen möchten, besteht die beste Methode darin, die DWG in eine Familie zu importieren. Wenn Sie versuchen, die DWG in ein Projekt zu importieren, werden Sie sehen, dass einige Objekte verschwinden, wenn Sie die DWG explodieren. Nachdem Sie die DWG in die Familie importiert haben, explodieren Sie die Familie, die die DWG erstellt hat. Dies soll sicherstellen, dass Sie separate Objekte in der IFC statt eines großen Objekts haben. Laden Sie anschließend die Familie in ein Projekt und platzieren Sie sie. Möglicherweise können Sie die Familie nicht auswählen. Dies kann daran liegen, dass Sie im Dropdown-Menü unter Ändern nicht das Feld "Unterlagerungselemente auswählen" aktiviert haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/01-revit.png)

Klicken Sie mit der ausgewählten Familie auf "Teile erstellen" im oberen Menüband.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/02-revit.png)

Sie sehen nun, dass Sie jeden Teil der Familie einzeln im Projekt auswählen können. Jetzt können Sie Ihre IFC exportieren, indem Sie im oberen linken Menü auf "Exportieren -> IFC" klicken. Klicken Sie im IFC-Exportdialog auf "Setup ändern". Navigieren Sie im Dialog "Setup ändern" zur Registerkarte "Erweitert". Stellen Sie hier sicher, dass "Teile als Gebäudeelemente exportieren" aktiviert ist.

### **Navisworks**

Derzeit gibt es keine offizielle Möglichkeit, aus Navisworks zu IFC zu exportieren. Es ist möglich, Plugins zu installieren, um dies mit unterschiedlichen Ergebnissen zu tun: Codemill IFC Exporter CellBIM für Excel und IFC Exporter. Beachten Sie, dass dies kein offizieller Exporter ist und beim Import möglicherweise Probleme auftreten.

## 1. **Export-Menü**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/03-export-menu.png)

1. Projektnummer
1. Projektname
1. Speichern unter - Geben Sie den Pfad zur Datei ein oder klicken Sie auf "Durchsuchen", um den Ordner zu suchen, in dem Sie Ihre IFC speichern möchten
1. Wählen Sie aus, welche Zeichnungsdateien Sie zu IFC exportieren möchten
1. Optionen
   1. Header – Autor, Organisation usw.
      1. IFC-Schema zum Exportieren auswählen – IFC 2x3 und IFC 4
   1. Objekte – Alle
   1. Ansicht – Alle einschließen

> **Hinweis:** IFC 4x1 wird von BuildingSMART eingestellt und wird daher auch von Catenda Hub nicht unterstützt. Siehe [hier](https://support.catenda.com/en/articles/4670320-what-file-types-does-catenda-support), welche Dateitypen in Catenda Hub unterstützt werden

1. Ressource und Zuweisung

1. Ressource – Klicken Sie mit der rechten Maustaste, um eine Ressourcenperson und Organisation hinzuzufügen
1. Zuweisung – Klicken Sie mit der rechten Maustaste, um eine zugewiesene Person und Organisation hinzuzufügen
1. IfcBuilding – Wählen Sie aus, welche Eigenschaften

Exportieren – Klicken Sie auf diese Schaltfläche, wenn Sie Ihre Dateien exportieren möchten
