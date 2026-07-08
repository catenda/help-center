# 3D DWG-eksportmanual

Programmer som kan eksportere 3D DWG-er til IFC er:

### **AutoCAD Architecture**

[Eksportmeny](#export-menu)

### **AutoCAD MEP**

[Eksportmeny](#export-menu)

### **AutoCAD Civil 3D**

[Eksportmeny](#export-menu)

### **AutoCAD Plant 3D:**

Hvis du bruker AutoCAD Plant 3D, kan du installere objektaktivatøren for versjonen av Plant 3D som du bruker. Med objektaktivatøren installert kan du åpne filen din i noen av programmene ovenfor for å eksportere til IFC. Hvis du ikke har tilgang til noen av programmene ovenfor, kan du prøve å bruke et tredjeparts plugin som: Codemill IFC Export for Autodesk® AutoCAD® Plant3D. Selv om dette pluginet hevder å også eksportere IFC 4, som ikke er mulig med objektaktivatøren, bør du huske at dette ikke er en offisiell eksportør og det kan være problemer ved import.

### **Revit**

Det er mulig å importere en 3D DWG til Revit. Selv om Revit har mange flere alternativer når det kommer til eksportering til IFC, er det ikke ideelt å eksportere en importert 3D DWG til IFC. Hvis du vil prøve å gjøre dette, er den beste måten å gjøre det på ved å importere DWG-en til en familie. Hvis du prøver å importere DWG-en til et prosjekt, vil du se at noen objekter forsvinner hvis du eksploderer DWG-en. Etter at du har importert DWG-en til familien, eksploderer du familien som DWG-en har opprettet. Dette er for å sikre at du kan ha separate objekter i IFC i stedet for ett stort objekt. Deretter laster du familien inn i et prosjekt og plasserer den. Du kan kanskje ikke velge familien. Dette kan være fordi du ikke har merket av for Velg underlagelemente i rullegardinmenyen under endre.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/01-revit.png)

Klikk på opprett deler i øverste bånd mens familien din er valgt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/02-revit.png)

Du vil nå se at du er i stand til å velge hver del av familien individuelt i prosjektet. Nå er du klar til å eksportere IFC-filen din ved å klikke på eksporter -> IFC i menyen øverst til venstre. I IFC-eksportdialogen klikker du på endre oppsett. I dialogen endre oppsett navigerer du til den avanserte fanen. Her må du sørge for at Eksporter deler som bygningselementer er merket av.

### **Navisworks**

For øyeblikket er det ingen offisiell måte å eksportere til IFC fra Navisworks. Det er mulig å installere plugins for å gjøre dette med varierende resultater: Codemill IFC Exporter CellBIM for Excel og IFC Exporter. Husk at dette ikke er en offisiell eksportør og det kan være problemer ved import.

## 1. **Eksportmeny**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/03-export-menu.png)

1. Prosjektnummer
2. Prosjektnavn
3. Lagret i – Skriv banen til filen eller klikk på bla gjennom for å finne mappen du vil lagre IFC-en din til
4. Velg hvilke tegningsfiler du vil eksportere til IFC
5. Alternativer
   1. Topptekst – Forfatter, organisasjon osv.
      1. Velg IFC-skjema for eksportering – IFC 2x3 og IFC 4
   2. Objekter – Alle
   3. Visning – Inkluder alle

> **Merknad:** IFC 4x1 er trukket tilbake av BuildingSMART og støttes derfor heller ikke av Catenda Hub. Se [her](https://support.catenda.com/en/articles/4670320-what-file-types-does-catenda-support) hvilke filtyper som støttes i Catenda Hub

6\. Ressurs og tilordning

1. Ressurs – Høyreklikk for å legge til ressursperson og organisasjon
2. Tilordning – Høyreklikk for å legge til tilordnet person og organisasjon
3. IfcBuilding – Velg hvilke egenskaper

Eksporter – Klikk denne knappen når du er klar til å eksportere filene dine
