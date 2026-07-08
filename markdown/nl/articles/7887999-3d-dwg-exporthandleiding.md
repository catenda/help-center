# 3D DWG-exporthandleiding

Programma's die 3D DWG's naar IFC kunnen exporteren zijn:

### **AutoCAD Architecture**

[Exportmenu](#export-menu)

### **AutoCAD MEP**

[Exportmenu](#export-menu)

### **AutoCAD Civil 3D**

[Exportmenu](#export-menu)

### **AutoCAD Plant 3D:**

Als u AutoCAD Plant 3D gebruikt, kunt u de objectenableaar installeren voor de versie van Plant 3D die u gebruikt. Met de objectenableaar geïnstalleerd, kunt u uw bestand in elk van de bovenstaande programma's openen om naar IFC te exporteren. Als u geen toegang hebt tot een van de bovenstaande software, kunt u proberen een plugin van een derde partij te gebruiken, zoals: Codemill IFC Export for Autodesk® AutoCAD® Plant3D. Hoewel deze plugin beweert ook IFC 4 te exporteren wat niet mogelijk is met de objectenableaar, houd er rekening mee dat dit geen officiële exporter is en er kunnen problemen optreden bij het importeren.

### **Revit**

Het is mogelijk om een 3D DWG naar Revit te importeren. Hoewel Revit veel meer opties biedt wanneer het gaat om exporteren naar IFC, is het niet ideaal om een geïmporteerde 3D DWG naar IFC te exporteren. Als u dit wilt proberen, is de beste manier om de DWG naar een familie te importeren. Als u de DWG naar een project probeert te importeren, zult u zien dat sommige objecten verdwijnen als u de DWG explodeert. Nadat u de DWG naar de familie hebt geïmporteerd, explodeert u de familie die de DWG heeft gemaakt. Dit is om ervoor te zorgen dat u afzonderlijke objecten in de IFC kunt hebben in plaats van één groot object. Laad vervolgens de familie in een project en plaats deze. U kunt de familie mogelijk niet selecteren. Dit kan zijn omdat u de optie "Select underlay elements" niet hebt ingeschakeld in het vervolgmenu onder modify.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/01-revit.png)

Klik met uw geselecteerde familie op "create parts" in het bovenste lint.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/02-revit.png)

Nu zult u zien dat u elk onderdeel van de familie afzonderlijk in het project kunt selecteren. Nu bent u klaar om uw IFC te exporteren door op exporteren -> IFC in het menu linksboven te klikken. Klik in het IFC-exportdialoogvenster op "modify setup". Navigeer in het dialoogvenster "modify setup" naar het tabblad "advanced". Zorg hier dat "Export parts as building elements" is ingeschakeld.

### **Navisworks**

Op dit moment is er geen officiële manier om vanuit Navisworks naar IFC te exporteren. Het is mogelijk om plugins te installeren om dit te doen met uiteenlopende resultaten: Codemill IFC Exporter CellBIM for Excel en IFC Exporter. Houd er rekening mee dat dit geen officiële exporter is en er kunnen problemen optreden bij het importeren.

## 1. **Exportmenu**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/03-export-menu.png)

1. Projectnummer
2. Projectnaam
3. Opgeslagen in - Schrijf het pad naar het bestand of klik op "browse" om de map te zoeken waar u uw IFC wilt opslaan
4. Selecteer welke tekenbestanden u naar IFC wilt exporteren
5. Opties
   1. Header - Auteur, Organisatie enz.
      1. Selecteer IFC Schema om naar te exporteren - IFC 2x3 en IFC 4
   2. Objecten - Alles
   3. Weergave - Alles opnemen

> **Opmerking:** IFC 4x1 is ingetrokken door BuildingSMART en wordt daarom ook niet ondersteund door Catenda Hub. Zie [hier](https://support.catenda.com/en/articles/4670320-what-file-types-does-catenda-support) welke bestandstypen worden ondersteund in Catenda Hub

6\. Bron en Toewijzing

1. Bron - Klik met de rechtermuisknop om een bronpersoon en organisatie toe te voegen
2. Toewijzing - Klik met de rechtermuisknop om een toegewezen persoon en organisatie toe te voegen
3. IfcBuilding - Kies welke eigenschappen

Exporteren - Klik op deze knop wanneer u klaar bent om uw bestanden te exporteren
