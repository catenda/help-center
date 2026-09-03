# 3D Snapshots - Probleemoplossing

## 1. **Viewpoint-instellingen**

### 1.1 **Objecten**

Objecten met dezelfde ID die waren geselecteerd, verborgen of geïsoleerd, worden geselecteerd, verborgen of geïsoleerd wanneer de snapshot opnieuw wordt gemaakt. Als twee modellen identieke IfcProject-GUID's (Global Identifiers) delen, kunnen conflicten leiden tot zichtbaarheidsproblemen, waardoor Catenda Hub niet kan bepalen welke modelelementen tijdens het opnieuw maken van de snapshot moeten verschijnen.

### 1.2 **Verborgen objecten**

Als meer dan de helft van de objecten in een model zichtbaar is, worden objecten met nieuwe id's verborgen.

Dit betekent dat als u een nieuw model met de modelpicker in een topic-opmerking snapshot toevoegt waar meer dan de helft van de objecten in een model zichtbaar is, het toegevoegde model volledig verborgen kan zijn. Om de objecten met nieuwe id's weer te geven, kunt u alles weergeven gebruiken om het model weer te geven na het opnieuw maken van de snapshot. Om problemen op te lossen en verborgen modellen zichtbaar te maken, kunt u de optie "alles weergeven" in de 3D Viewer gebruiken. Klik met de rechtermuisknop in het 3D-weergavegebied, selecteer "alles weergeven" in het contextmenu. Dit zou zichtbaarheidsproblemen die door configuratieconflicten worden veroorzaakt, tijdelijk moeten oplossen.

## 2. **Snapshot opnieuw maken**

Bij het afspelen van een 3D-snapshot van een Topic kunnen bepaalde modellen niet verschijnen. Dit probleem kan voortvloeien uit projectproblemen zoals dubbele IfcProject-GUID's. Los dit op door ervoor te zorgen dat elk model in het project een unieke identificatie gebruikt. Gebruik bovendien de optie "Alles weergeven" in de 3D Viewer als een tijdelijke oplossing.

### 2.1 **Snapshot-modelpicker**

In dit menu kunt u de snapshot alleen aan Catenda-modellen koppelen. Als de juiste modellen niet automatisch zijn gevonden, kunnen ze hier handmatig worden gekoppeld. Zelfs als meerdere modellen dezelfde GUID hebben, kunt u selecteren om ze allemaal in te schakelen in plaats van alleen de eerste. Dit verandert niets aan de inhoud van de BCF, dus de objecten kunnen nog steeds verborgen zijn wanneer ze in externe tools worden geopend.

Afhankelijk van de zichtbaarheidsinstellingen van de Snapshot kunnen toegevoegde modellen volledig verborgen zijn. Open de revisieselector of modellenpagina om te zien welke modellen de 3D-knop ingeschakeld hebben om te zien welke modellen na het opnieuw maken van de Snapshot in de Viewer zijn geladen. Ook al zijn ze geladen, alle objecten van het model kunnen verborgen zijn. Gebruik de actie alles weergeven om verborgen objecten zichtbaar te maken..

## 3. **BCF-import van snapshot**

Wanneer een BCF-topic wordt geïmporteerd, worden de id's van de modellen in het project vergeleken met de id's van de modellen die in de snapshot zijn geconfigureerd. Alleen de modellen met id's die op het moment van import aanwezig zijn, worden in de 3D-viewer geladen wanneer de snapshot opnieuw wordt gemaakt.

Als twee modellen dezelfde id hebben, is alleen de eerste ingeschakeld. Om ervoor te zorgen dat de juiste modellen zijn ingeschakeld, is het belangrijk dat elk model zijn eigen id heeft.

Als u verschillende meerdere bestanden van uw ontwerpsoftware exporteert, kan het een goed idee zijn om een unieke id voor elk afzonderlijk model dat u wilt exporteren te gebruiken. Het is aanbevolen dat elk model in het project een unieke IfcProject-GUID krijgt toegewezen om conflicten tijdens het opnieuw maken van snapshots te voorkomen. Dit zorgt ervoor dat Catenda Hub de configuraties in de 3D-viewer nauwkeurig kan weergeven.

Hier is een artikel van BuildingSMART dat beschrijft hoe dit in Revit wordt gedaan [https://user.buildingsmart.org/knowledge-base/ifcproject/](https://user.buildingsmart.org/knowledge-base/ifcproject/)

Zorg ervoor dat u bijhoudt welke id voor welk model is gebruikt, zodat toekomstige topics die worden gemaakt, deze herkennen.
