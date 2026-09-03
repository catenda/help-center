# Modellen als Documenten

Voorheen was het mogelijk om IFC-bestanden op twee aparte locaties in Catenda Hub te uploaden. Met de functie _modellen als documenten_ worden deze twee locaties voor modelbestanden samengevoegd tot één naadloze functie. Als u een model maakt in de modelensectie, wordt automatisch een gekoppeld document aangemaakt in de documentensectie. Als u een IFC-document uploadt, kunt u de knop "model maken" gebruiken om een model in de modelensectie te koppelen en aan te maken. Met deze functie kunnen modellen in de modelensectie als documenten worden beheerd, terwijl modellen in de documentensectie zoals modellen kunnen worden beheerd.

## 1. **Voor/Na-migratie - Belangrijkste verschillen**

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e8e8e880; width: 126px; padding: 8px;"><h1 id="h_3632d3cc1b"></h1></td><td style="background-color: #e8e8e880; width: 262px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_2093155130"><b>Voor</b></h2></td><td style="background-color: #e8e8e880; width: 248px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_d5cfcbcb2d"><b>Na</b></h2></td></tr><tr><td style="background-color: #e8e8e880; width: 126px; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right"><b>Hoofdgedrag</b></p></td><td style="width: 262px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Modellen bestonden alleen in de modelensectie. De gebruiker moest hetzelfde IFC-bestand naar zowel de Document- als de modelensectie uploaden.</p></td><td style="width: 248px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Modellen worden gemaakt van IFC-bestanden die naar de documentensectie zijn geüpload, indien de gebruiker dit aanvraagt. Het IFC-bestand en het bijbehorende model zijn dan gekoppeld.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right"><b>Gebruikersinterface</b></p></td><td style="width: 262px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Anders</b> dan de documentensectie en toont minder informatie, in feite alleen een lijst met modellen.</p></td><td style="width: 248px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Hetzelfde</b> als de documentensectie: een aanpasbare tabel met gerelateerde metagegevens.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right"><b>Toegangsrechten</b></p></td><td style="width: 262px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Konden niet worden toegepast</b> op modellen</p></td><td style="width: 248px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Kunnen worden toegepast</b> op modellen via het bijbehorende document in de documentensectie</p></td></tr></tbody></table></div>

## 2. **Vertrouwd maar anders**

Nu de twee secties zijn gekoppeld, is het belangrijk op te merken dat er nog steeds belangrijke verschillen zijn tussen de modellen en documentensecties. In de modelensectie kunt u alle modeldocumenten in een lijst zien. Hier ziet u uw modeldocumenten op een manier die vergelijkbaar is met hoe zij in de 3D-viewer worden gebruikt. In de documentensectie kunt u documentmodellen in uw documentstructuur zien. Hier ziet u uw documentmodellen op een manier die vergelijkbaar is met hoe zij in uw common data environment worden gebruikt. Alle modellen zijn elk gekoppeld aan hun eigen document en functies uit beide secties kunnen in zowel de modelensectie als in de documentensectie worden gebruikt.

## 3. **Wijzigingen in de modelensectie**

Met modellen als documenten is het uiterlijk van de modelensectie veranderd. In plaats van menu-items voor elk model verschijnen deze nu in een doorzoekbare tabel.

In de modelensectie kunt u de volgende wijzigingen aantreffen:

### 3.1 **Modeltabel**

De nieuwe modeltabel kan er ongeveer als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/01-model-table.png)

### 3.2 **Kolommen**

De modellijst heeft kolommen die de meeste informatie weergeven die u over uw modellen moet weten.

_Naam_ De naam van het modeldocument. De modelnaam is ook de naam die u in de revisiekiezer in de 3D-weergave ziet.

**Documentnaam** De naam van het documentmodel in de documentensectie

**Revisienaam** De naam van de nieuwste revisie

### 3.3 **Toegangscontrole**

Als een model voor u in de documentensectie is beperkt, ziet u het niet in de documentensectie, niet in de modeltabel en ook niet in de revisiekiezer.

### 3.4 **Tabelelementen selecteren**

Met de modeltabel kunt u nu een reeks modellen selecteren door Shift ingedrukt te houden. U kunt ook modellen aan uw selectie toevoegen of uit uw selectie verwijderen door Ctrl ingedrukt te houden.

### 3.5 **Actieknoppen**

In het verleden was de enige actie die u op geselecteerde modellen kon uitvoeren het openen van deze modellen in 3D. Nu kunt u de 2D-weergave van uw geselecteerde modellen downloaden, verwijderen en openen. Als u een model verwijdert dat met een document is verbonden, verliest het document de modelkoppeling, maar het document blijft in de documentensectie.

### 3.6 **Toegang beheren tot documentmodellen**

**Een modeldocument aanmaken** Als u een model maakt met de knop "model aanmaken" in de modelensectie, wordt u gevraagd te selecteren waar u het gekoppelde documentmodel in de documentensectie wilt plaatsen. In het dialoogvenster "model aanmaken" kunt u ook een naam voor het model geven. Het resulterende gekoppelde documentmodel zal dezelfde naam hebben als het model wanneer het wordt gemaakt. Catenda Hub onthoudt de map die u het laatst hebt gekozen en selecteert deze automatisch de volgende keer dat u een modeldocument aanmaakt.

Als uw project zonder modellen als documenten is gestart, zal een map met de naam 'Modellen' in uw mapstructuur zijn verschenen. De modelmap die verschijnt, bevat alle documentmodellen die zijn gekoppeld aan modeldocumenten in de modelensectie. Documentmodellen kunnen uit deze map worden verplaatst naar elke plek in de documentensectie waartoe u toegang hebt. Documentmodellen in de map Modellen kunnen ook worden verwijderd (en hersteld) indien gewenst. De documentmodellen hoeven niet in de map te staan en de modellenmap kan indien nodig worden verwijderd.

**Een modelrevisie aanmaken** Om nieuwe revisies naar een model te kunnen uploaden, hebt u nu minimaal schrijftoegang tot het documentmodel nodig. Nieuwe revisies van het model kunnen aan het document worden toegevoegd en omgekeerd.

> **Opmerking:** Revisiecommentaar is uitgeschakeld en kan nu optioneel worden ingeschakeld met [aangepaste velden op revisies](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents).

**Een modelrevisie downloaden** U hebt minimaal leestoegang tot het documentmodel nodig om het model te kunnen downloaden.

### 3.7 **Menu met rechtsinformatie**

Er is een menu met rechtsinformatie beschikbaar als een model is geselecteerd.

**Documentveld** In dit menu ziet u uw modelinformatie en ook een grijs veld dat verwijst naar het documentmodel in de documentensectie dat aan dit modeldocument is gekoppeld. Klik op het documentveld om het documentmodel te openen dat aan dit model is gekoppeld.

**Modellabels** U kunt hier nu ook labels aan uw modellen toevoegen.

**Modelstatus** Als statussen in documentinstellingen zijn geconfigureerd, kunt u hier een status voor uw model configureren.

**Modeltransformatie** Als u dit model in 3D hebt geopend, kunt u hier de modeltransformatie configureren.

## 4. **Wijzigingen in de documentensectie**

Hoewel de visuele wijzigingen niet zo opvallend zijn als in de modelensectie, zijn er enkele zaken die in de documentensectie zullen veranderen wanneer modellen als documenten is geactiveerd. Dit is hoe de documentmodellen in de documentensectie eruit kunnen zien.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/02-documents-section-changes.png)

In de documentensectie kunt u de volgende wijzigingen aantreffen:

### 4.1 **Modelfilter**

Zodra u modellen in de modelensectie hebt, ziet u een modelfilter in uw filtermenu verschijnen. Met dit filter kunt u alle gemaakte documentmodellen weergeven/verbergen.

### 4.2 **Kolommen**

**Pictogram** U kunt een documentmodel van een normaal document onderscheiden aan de badge van het model in de rechterbenedenhoek van het documentmodelpictogram.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/03-columns.png)

**Naam** De naam van het document

**Modelnaam** De naam van het model. Als uw IFC-document niet aan een model is gekoppeld, ziet u hier een knop "model aanmaken".

**Revisienaam** De naam van de nieuwste revisie in het model

**Viewer** Een kolom met knoppen om elk afzonderlijk documentmodel in de 3D-viewer te openen. Het openen van documentmodellen in de 3D-viewer is alleen mogelijk als het document aan een model is gekoppeld.

### 4.3 **Actieknoppen**

Download, verwijder of laad de 2D/3D-weergaven van geselecteerde modellen in de respectievelijke viewer door één of meer modellen te selecteren.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-9e345595c719.png" width="310"/>    <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-959af958f499.png" width="310"/>

Dit betekent dat u meerdere modellen tegelijk kunt verwijderen in plaats van één voor één zoals eerder. Als u een document verwijdert dat met een model is verbonden, moet u een waarschuwing goedkeuren dat het model dat met het document is verbonden, ook zal worden verwijderd.

> **Opmerking:** Dit betekent dat u een model kunt verwijderen zonder de gegevens kwijt te raken. (Verwijderde documenten kunnen worden hersteld)

### 4.4 **Toegang beheren tot modelmodellen**

**Documentmodellen aanmaken** Om nieuwe revisies naar een model te kunnen uploaden, hebt u nu minimaal schrijftoegang tot het documentmodel nodig. U doet dit door in het actiemenu van een document een model aan te maken. Hierna ziet u het document als een model in de modelensectie. Het modeldocument in de modelensectie zal dezelfde naam hebben als het documentmodel, hoewel deze later elk afzonderlijk kunnen worden gewijzigd terwijl ze gekoppeld blijven. Nieuwe revisies van het model kunnen als revisies aan het document worden toegevoegd en omgekeerd.

> **Opmerking:** Dit betekent dat u tegelijkertijd modellen uit meerdere IFC-bestanden kunt aanmaken in plaats van ze één voor één te moeten uploaden

**Revisies uploaden naar documentmodellen** U hebt minimaal schrijftoegang tot het documentmodel nodig om nieuwe revisies naar het model te kunnen uploaden. Dit betekent dat u de functie voor meervoudig uploaden kunt gebruiken om IFC-bestanden tegelijk naar meerdere documentmodellen te uploaden

**Documentmodellen downloaden** U hebt minimaal leestoegang tot het documentmodel nodig om het model te kunnen downloaden. Dit betekent dat u de toegang kunt configureren zodat u het downloaden van afzonderlijke modellen in plaats van alles of niets kunt toestaan.

### 4.5 **Ontdekkbaarheid**

Documentmodellen kunnen nu in de documentensectie worden gevonden zoals elk ander document.

- Documentmodellen kunnen in mappen worden georganiseerd om het gemakkelijker te maken naar de juiste set modellen te navigeren.
- Labels kunnen aan documentmodellen worden toegevoegd om alle documentmodellen te vinden die tot één type behoren.
- [Aangepaste velden kunnen aan mappen worden toegevoegd](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) waarin documenten worden geüpload om te zoeken op metagegevenswaarden die aan elk documentmodel zijn gerelateerd
- [Aangepaste velden kunnen aan mappen worden toegevoegd](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) waarin documenten worden geüpload om informatie aan elke revisie in elk documentmodel toe te kunnen voegen.

Zie [hier](https://support.catenda.com/en/articles/8542598-structuring-documents#h_7838a63c73) voor suggesties over hoe u uw documentmodellen zo kunt structureren dat ze gemakkelijk te vinden zijn.

### 4.6 **Gedeelde IFC-bestanden goedkeuren**

IFC-bestanden kunnen nu als gedeelde revisies worden geüpload, zodat ze een goedkeuringsproces kunnen doorlopen voordat ze worden gepubliceerd.

### 4.7 **Naamgeving met documentmodellen**

Namen in de documentensectie bevatten vaak gecomprimeerde afkortingen om de documentnaam kort te houden en toch enige informatie over het onderwerp van het document weer te geven. De naam van het documentmodel kan daarom afwijken van de naam van het modeldocument om het in overeenstemming te houden met de andere documenten in de documentensectie, terwijl een gemakkelijk leesbare naam voor gebruik in de 3D-viewer in de modelensectie behouden blijft. De documentnaam van het documentmodel is de naam die wordt herkend wanneer documenten naar de documentensectie worden geüpload. Als de naam gelijk is aan of lijkt op het document, wordt automatisch een nieuwe revisie aangemaakt, net zoals bij andere documenten.

Omdat documentmodellen zich op dezelfde manier gedragen als normale modellen, is het nu mogelijk om de naamgevingsconventie met documentmodellen te gebruiken om ervoor te zorgen dat deelnemers aan uw project de juiste naam aan het document geven bij het uploaden.
