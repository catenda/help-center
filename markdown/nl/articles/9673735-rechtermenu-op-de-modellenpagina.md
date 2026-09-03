# Rechtermenu op de modellenpagina

Het rechtermenu met informatie is te vinden door een model op de [modellenpagina](https://support.catenda.com/en/articles/4670286-models-page) te selecteren of door de [inhoudspagina](https://support.catenda.com/en/articles/4670270-model-overview-page) van een model te openen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/01-intro.png)

Klik op het "i"-pictogram rechtsboven om het rechtermenu te openen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/02-intro.png)

Het menu kan er voor een enkel model ongeveer zo uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/03-intro.png)

Of zo met meerdere modelsrijen geselecteerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/04-intro.png)

## 1. **Modelheader**

In de modelheader wordt informatie over de laatste revisie van het model weergegeven.

### 1.1 **Afbeelding**

Bovenaan de modelheader kan een afbeelding voor het model worden toegevoegd. Dit is hoe het eruit kan zien als geen afbeelding is toegevoegd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/05-image.png)

Upload een lokale afbeelding of voeg rechtstreeks een snapshot van de 3D-viewer toe zonder iets te uploaden. Dit is hoe de modellenpagina eruit ziet wanneer een afbeelding voor een model is geconfigureerd:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/06-image.png)

_Modelafbeelding in rechtermenu_ Wanneer toegevoegd, wordt de afbeelding bovenaan het rechtermenu van een model weergegeven wanneer een enkel model is geselecteerd of wanneer het menu open is op de modelinhoudspagina. De toegevoegde afbeelding wordt weergegeven in het rechtermenu van een modelrevisie wanneer één model is geselecteerd, evenals in de miniatuur van het model in de naamkolom van de modelstabel.

Klik [hier](https://support.catenda.com/en/articles/4670257-creating-a-thumbnail-for-your-model) voor meer informatie over het toevoegen van een afbeelding voor een model.

**Modelminiatuur** Wanneer toegevoegd, wordt de afbeelding als miniatuur voor het model weergegeven in de naamkolom van de modelstabel op de modellenpagina.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/07-image.png)

Klik op de miniatuur om een preview van de afbeelding te openen. Dit is hoe de miniatuurnvoorbeeld eruit kan zien.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/08-image.png)

Via de navigatie bovenaan kan de afbeelding worden gedownload. Als de snapshot van een model is gemaakt, is de preview een 3D-preview, zodat het mogelijk is om het model vanaf het startpunt van de modelminiatuur te navigeren.

### 1.2 **Documentkoppeling**

De documentkoppeling is het grijze vak onder de modelafbeelding. Het vak toont de locatie van het document-model in de bestandsstructuur. Eronder zie je de naam van het document-model dat aan dit model-document is gekoppeld. Klik op dit vak om naar de documentvoorbeeldpagina van het document-model op de documentenpagina te gaan.

### 1.3 **Status**

De status van de nieuwste openbare document-modelrevisie.

### 1.4 **Labels**

Standaard kunnen labels op elk model worden toegepast. Als gedeelde revisies zijn geactiveerd, moet er ten minste één gepubliceerde revisie in het model zijn om labels toe te voegen. Labels worden zowel voor het model als voor het document waaraan het model is gekoppeld, opgeslagen. Hetzelfde label kan daarom worden gebruikt om modellen op de modellenpagina en documenten op de documentenpagina te filteren.

## 2. **Bijdragers**

De verschillende teamleden die revisies hebben geupload en zodoende aan het model hebben bijgedragen, worden hier weergegeven.

## 3. **Modeltransformatie**

Met modeltransformatie kunnen modelobjecten op een ander locatie en oriëntatie binnen de Catenda Hub 3D-viewer worden weergegeven. Deze transformatie is alleen van toepassing op modellen in de 3D-viewer en niet op 3D-documenten die in de 3D-viewer zijn geladen. Klik [hier](https://support.catenda.com/en/articles/12498975-add-context-to-your-projects-with-freely-accessible-ign-point-clouds-hd-lidar) voor meer informatie over de transformatie van 3D-documenten.

**Modellen uitwisselen met externe tools** Modellen worden vaak van Catenda gedownload en in een third-party programma geopend. Het blijft daarom belangrijk om de juiste coördinaten in het IFC-bestand te configureren voordat u uploadt, zodat het gedownloade bestand de juiste informatie bevat.

**Wanneer moet het model worden getransformeerd?** Vaak is er een periode waarin een model wordt ingediend en de geometrie al wordt gebruikt voor samenwerking, nog voordat de coördinaten in het model correct zijn. Dit kan verschillende redenen hebben, bijvoorbeeld dat geen gemeenschappelijk nulpunt in het project is besloten of dat een andere exportmethode in het ontwerprogramma waarmee het IFC-bestand is gegenereerd moet worden onderzocht. Het kan helpen om het model (alleen in Catenda Hub via de browser) met modeltransformatie in deze periode te transformeren zodat het afspelen van 3D-snapshots blijft overeenkomen, zelfs met nieuwere revisies met bijgewerkte coördinaten.

**Coördinatenamenwerking met gedeelde revisies** In een project waarin gedeelde revisies zijn geactiveerd, wordt het niet aanbevolen om modelrevisies te publiceren zonder de juiste coördinaten in het IFC-bestand te hebben.

### 3.1 **Modeltransformatie-instellingen**

Laad het model dat in de 3D-viewer moet worden verplaatst. Dit kan gedaan worden door op de 3D-knop op het dashboard, op de modellenpagina, op de modelinhoudspagina of in de revisieselector te klikken. In het rechtermenu op de modellenpagina wordt het menu met transformatie-instellingen onderaan het menu weergegeven. Dit is hoe de modeltransformatie-instellingen eruit kunnen zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/09-model-transformation-settings.png)

**Offset** Voer X-, Y- en/of Z-coördinaten in om het model te verplaatsen. Eenheden - Meter

**Rotatie** Voer een hoek in om het model te roteren. Het model wordt geroteerd rond de middelpunten van de begrenzingsvak die alle objecten van het model bevat. Het punt bevindt zich vaak rond het midden van het model van bovenaf gezien. Eenheden - Graden

**Opslaan** Klik op Opslaan om de transformatie-instellingen op te slaan.

### 3.2 **Alleen in browser**

Het IFC-bestand wordt niet gewijzigd wanneer de transformatie-instellingen worden opgeslagen. Als een nieuw model met het IFC-bestand wordt gemaakt, hetzij binnen hetzelfde project hetzij in een ander project, wordt het IFC-bestand opnieuw weergegeven op de locatie die in het IFC-bestand is geconfigureerd.

Het is vaak geen probleem om een model in Catenda voor korte perioden of zelfs voor de hele levensduur van het project te verplaatsen. Uiteindelijk kan het veel tijd besparen om een gemeenschappelijk coördinatenstelsel vast te stellen zodat modellen na het aanmaken niet hoeven te worden aangepast en om misverstanden gedurende het project te voorkomen.

## 4. **Meervoudige selectie**

Met meerdere geselecteerde modellen kan het rechtermenu er zo uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/10-multi-select.png)

Klik op de rode x naast een model om het uit de selectie te verwijderen.

### 4.1 **Geselecteerde documenten bijwerken**

Dit is hoe het menu Geselecteerde documenten bijwerken eruit kan zien

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/11-update-selected-documents.png)

Klik in de gebieden voor labels toevoegen en verwijderen en selecteer één of meer labels.

_Toevoegen heeft prioriteit_ Een label dat in zowel het veld Label toevoegen als Label verwijderen wordt ingevoerd, wordt toegevoegd aan modellen die het label nog niet hebben en wordt niet verwijderd uit modellen die het label al hebben.

### 4.2 **Laatste revisie**

De ingevoerde status wordt voor alle geselecteerde modellen geconfigureerd wanneer de wijzigingen worden opgeslagen.
