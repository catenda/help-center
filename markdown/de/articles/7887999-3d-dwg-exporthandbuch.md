# 3D-DWG-Exporthandbuch

Programme, die 3D-DWGs in IFC exportieren können, sind:

### **AutoCAD Architecture**

[Exportmenü](#export-menu)

### **AutoCAD MEP**

[Exportmenü](#export-menu)

### **AutoCAD Civil 3D**

[Exportmenü](#export-menu)

### **AutoCAD Plant 3D:**

Wenn Sie AutoCAD Plant 3D verwenden, können Sie den Object Enabler für die Version von Plant 3D installieren, die Sie verwenden. Mit dem installierten Object Enabler können Sie Ihre Datei in einem der oben genannten Programme öffnen, um sie in IFC zu exportieren. Wenn Sie keinen Zugriff auf eine der oben genannten Software haben, können Sie versuchen, ein Plugin von Drittanbietern wie Codemill IFC Export für Autodesk® AutoCAD® Plant3D zu verwenden. Obwohl dieses Plugin behauptet, auch IFC 4 zu exportieren, was mit dem Object Enabler nicht möglich ist, beachten Sie, dass dies kein offizieller Exporter ist und es möglicherweise Probleme beim Importieren gibt.

### **Revit**

Es ist möglich, eine 3D-DWG in Revit zu importieren. Obwohl Revit viele weitere Optionen beim Export zu IFC bietet, ist es nicht ideal, eine importierte 3D-DWG in IFC zu exportieren. Wenn Sie dies versuchen möchten, ist die beste Methode, die DWG in eine Familie zu importieren. Wenn Sie versuchen, die DWG in ein Projekt zu importieren, sehen Sie, dass einige Objekte verschwinden, wenn Sie die DWG explodieren. Nach dem Importieren der DWG in die Familie explodieren Sie die Familie, die die DWG erstellt hat. Dies soll sicherstellen, dass Sie in der IFC getrennte Objekte statt eines großen Objekts haben. Laden Sie anschließend die Familie in ein Projekt und platzieren Sie sie. Möglicherweise können Sie die Familie nicht auswählen. Dies kann daran liegen, dass Sie die Option "Unterlagselemente auswählen" im Dropdown-Menü unter "Ändern" nicht aktiviert haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/01-revit.png)

Klicken Sie bei ausgewählter Familie auf "Teile erstellen" im oberen Menüband.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/02-revit.png)

Jetzt können Sie alle Teile der Familie einzeln im Projekt auswählen. Nun können Sie Ihre IFC exportieren, indem Sie im oberen linken Menü auf "Exportieren -> IFC" klicken. Klicken Sie im IFC-Exportdialog auf "Einrichtung ändern". Navigieren Sie im Dialog "Einrichtung ändern" zur Registerkarte "Erweitert". Stellen Sie sicher, dass "Teile als Bauelemente exportieren" aktiviert ist.

### **Navisworks**

Es gibt derzeit keine offizielle Möglichkeit, aus Navisworks in IFC zu exportieren. Es ist möglich, Plugins mit unterschiedlichen Ergebnissen zu installieren: Codemill IFC Exporter CellBIM für Excel und IFC Exporter. Beachten Sie, dass dies kein offizieller Exporter ist und es möglicherweise Probleme beim Importieren gibt.

## 1. **Exportmenü**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/03-export-menu.png)

1. Projektnummer
2. Projektname
3. Speichern in - Geben Sie den Pfad zur Datei ein oder klicken Sie auf "Durchsuchen", um den Ordner zu finden, in dem Sie Ihre IFC speichern möchten.
4. Wählen Sie die Zeichnungsdateien aus, die Sie in IFC exportieren möchten.
5. Optionen
   1. Header - Autor, Organisation usw.
      1. Wählen Sie das IFC-Schema aus, in das exportiert werden soll - IFC 2x3 und IFC 4
   2. Objekte - Alle
   3. Ansicht - Alle einbeziehen

> **Hinweis:** IFC 4x1 wird von BuildingSMART zurückgezogen und wird daher auch nicht von Catenda Hub unterstützt. [Hier](https://support.catenda.com/en/articles/4670320-what-file-types-does-catenda-support) sehen Sie, welche Dateitypen in Catenda Hub unterstützt werden.

6\. Ressource und Zuordnung

1. Ressource - Klicken Sie mit der rechten Maustaste, um eine Ressourcenperson und Organisation hinzuzufügen
2. Zuordnung - Klicken Sie mit der rechten Maustaste, um eine zugewiesene Person und Organisation hinzuzufügen
3. IfcBuilding - Wählen Sie, welche Eigenschaften

Exportieren - Klicken Sie auf diese Schaltfläche, wenn Sie bereit sind, Ihre Dateien zu exportieren
