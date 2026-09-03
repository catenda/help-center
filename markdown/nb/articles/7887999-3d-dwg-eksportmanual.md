# 3D DWG eksportmanual

Programmer som kan eksportere 3D DWG-er til IFC er:

### **AutoCAD Architecture**

[Eksportmeny](#h_9ac38304dd)

### **AutoCAD MEP**

[Eksportmeny](#h_9ac38304dd)

### **AutoCAD Civil 3D**

[Eksportmeny](#h_9ac38304dd)

### **AutoCAD Plant 3D:**

Hvis du bruker AutoCAD Plant 3D, kan du installere objektaktivatøren for versjonen av Plant 3D som du bruker. Med objektaktivatøren installert kan du åpne filen din i et av programmene ovenfor for å eksportere til IFC. Hvis du ikke har tilgang til noen av programvarene ovenfor, kan du prøve å bruke et plugin fra tredjepartsleverandør som: Codemill IFC Export for Autodesk® AutoCAD® Plant3D. Selv om dette programtillegget hevder å også eksportere IFC 4 som ikke er mulig med objektaktivatøren, må du huske på at dette ikke er en offisiell eksportør og det kan oppstå problemer ved import.

### **Revit**

Det er mulig å importere en 3D DWG til Revit. Selv om Revit har mange flere alternativer når det gjelder eksport til IFC, er det ikke ideelt å eksportere en importert 3D DWG til IFC. Hvis du vil prøve å gjøre dette, er den beste måten å importere DWG-en til en familie. Hvis du prøver å importere DWG-en til et prosjekt, vil du se at noen objekter forsvinner hvis du eksploderer DWG-en. Etter at du har importert DWG-en til familien, eksploderer du familien som DWG-en har opprettet. Dette er for å sikre at du kan ha separate objekter i IFC i stedet for ett stort objekt. Last deretter familien inn i et prosjekt og plasser den. Du kan ikke være i stand til å velge familien. Dette kan skyldes at du ikke har merket av for "Velg underlagelemmenter" i rullegardinmenyen under Endre.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/01-revit.png)

Med familien du har plassert valgt, klikker du på opprett deler i toppbåndet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/02-revit.png)

Du vil nå se at du er i stand til å velge hver del av familien individuelt i prosjektet. Nå er du klar til å eksportere ifc-en ved å klikke på eksporter -> IFC i menyen øverst til venstre. I IFC-eksportdialogen klikker du på endre oppsett. I dialogboksen for endring av oppsett navigerer du til fanen Avansert. Her må du kontrollere at "Eksporter deler som bygningselementer" er merket av.

### **Navisworks**

For øyeblikket finnes det ingen offisiell måte å eksportere til IFC fra Navisworks. Det er mulig å installere programtillegg for å gjøre dette med varierende resultater: Codemill IFC Exporter CellBIM for Excel og IFC Exporter. Husk at dette ikke er en offisiell eksportør og det kan oppstå problemer ved import.

## 1. **Eksportmeny**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3baydpf4/03-export-menu.png)

1. Prosjektnummer
1. Prosjektnavn
1. Lagret i - Skriv stien til filen eller klikk på Bla gjennom for å finne mappen der du vil lagre IFC-en
1. Velg hvilke tegningsfiler du vil eksportere til IFC
1. Valg
   1. Topptekst - Forfatter, Organisasjon osv.
      1. Velg IFC-skjema du vil eksportere til - IFC 2x3 og IFC 4
   1. Objekter - Alle
   1. Visning - Inkluder alle

> **Merk:** IFC 4x1 er trukket tilbake av BuildingSMART og støttes derfor heller ikke av Catenda Hub. Se [her](https://support.catenda.com/en/articles/4670320-what-file-types-does-catenda-support) hvilke filtyper som støttes i Catenda Hub

1\. Ressurs og Tildeling

1. Ressurs - Høyreklikk for å legge til ressursperson og organisasjon
1. Tildeling - Høyreklikk for å legge til tildelt person og organisasjon
1. IfcBuilding - Velg hvilke egenskaper

Eksporter - Klikk denne knappen når du er klar til å eksportere filene dine
