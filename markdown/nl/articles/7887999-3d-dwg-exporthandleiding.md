# 3D DWG exporthandleiding

Programma's die 3D DWG's naar IFC kunnen exporteren zijn:

### **AutoCAD Architectuur**

[Exportmenu](#h_9ac38304dd)

### **AutoCAD MEP**

[Exportmenu](#h_9ac38304dd)

### **AutoCAD Civil 3D**

[Exportmenu](#h_9ac38304dd)

### **AutoCAD Plant 3D:**

Als u AutoCAD Plant 3D gebruikt, kunt u de objectenabeler installeren voor de versie van Plant 3D die u gebruikt. Met de objectenabeler geïnstalleerd kunt u uw bestand openen in een van de bovenstaande programma's om naar IFC te exporteren. Als u geen toegang hebt tot een van de bovenstaande software, kunt u proberen een externe plugin te gebruiken zoals: Codemill IFC Export voor Autodesk® AutoCAD® Plant3D Hoewel deze plugin ook IFC 4 claimt te exporteren, wat niet mogelijk is met de objectenabeler, onthoud dat dit geen officiële exporter is en er kunnen problemen optreden bij het importeren.

### **Revit**

Het is mogelijk om een 3D DWG naar Revit te importeren. Hoewel Revit veel meer opties heeft voor het exporteren naar IFC, is het niet ideaal om een geïmporteerde 3D DWG naar IFC te exporteren. Als u dit toch wilt proberen, is de beste manier om de DWG naar een familie te importeren. Als u de DWG naar een project probeert te importeren, zult u zien dat sommige objecten verdwijnen als u de DWG ontleedt. Na het importeren van de DWG naar de familie, ontleedt u de familie die de DWG heeft gemaakt. Dit is om ervoor te zorgen dat u gescheiden objecten in de IFC kunt hebben in plaats van één groot object. Laad vervolgens de familie in een project en plaats deze. U kunt de familie mogelijk niet selecteren. Dit kan zijn omdat u in het vervolgkeuzemenu onder wijzigen geen vinkje hebt gezet bij Het selecteren van onderlays.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/01-revit.png)

Klik met uw geplaatste familie geselecteerd op onderdelen maken in het bovenste lint.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/02-revit.png)

U ziet nu dat u elk onderdeel van de familie afzonderlijk in het project kunt selecteren. Nu bent u klaar om uw ifc te exporteren door in het menu linksboven op exporteren -> IFC te klikken. Klik in het dialoogvenster IFC-export op installatiewijziging. Navigeer in het dialoogvenster voor installatiewijziging naar het tabblad Geavanceerd. Zorg hier dat u het vakje Onderdelen exporteren als bouwelementen inschakelt.

### **Navisworks**

Op dit moment is er geen officiële manier om vanuit Navisworks naar IFC te exporteren. Het is mogelijk om plugins te installeren om dit te doen met uiteenlopende resultaten: Codemill IFC Exporter CellBIM for Excel en IFC Exporter Onthoud dat dit geen officiële exporter is en er kunnen problemen optreden bij het importeren.

## 1. **Exportmenu**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/03-export-menu.png)

1. Projectnummer
1. Projectnaam
1. Opgeslagen in - Typ het pad naar het bestand of klik op bladeren om de map te zoeken waar u uw IFC wilt opslaan
1. Selecteer welke tekenbestanden u naar IFC wilt exporteren
1. Opties
   1. Koptekst - Auteur, organisatie enz.
      1. Selecteer IFC-schema om naar te exporteren - IFC 2x3 en IFC 4
   1. Objecten - Alles
   1. Weergave - Alles opnemen

> **Opmerking:** Ifc 4x1 is ingetrokken door BuildingSMART en wordt daarom ook niet ondersteund door Catenda Hub. Zie [hier](https://support.catenda.com/en/articles/4670320-what-file-types-does-catenda-support) welke bestandstypen worden ondersteund in Catenda Hub

6\. Bron en toewijzing

1. Bron - Klik met de rechtermuisknop om een bronperson en organisatie toe te voegen
1. Toewijzing - Klik met de rechtermuisknop om een toegewezen persoon en organisatie toe te voegen
1. IfcBuilding - Kies welke eigenschappen

Exporteren - Klik op deze knop wanneer u klaar bent om uw bestanden te exporteren
