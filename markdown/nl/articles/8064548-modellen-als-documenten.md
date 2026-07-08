# Modellen als Documenten

Eerder was het mogelijk om IFC-bestanden op twee aparte locaties in Catenda Hub te uploaden. Met de functie _modellen als documenten_ worden deze twee locaties voor modelbestanden samengevoegd tot één naadloze functie. Als u een model in de modellensectie maakt, wordt automatisch een document gekoppeld en gemaakt in de sectie Documenten. Als u een IFC-document uploadt, kunt u de actieknop "model maken" gebruiken om een model in de modellensectie te koppelen en te maken. Met deze functie kunnen modellen in de modellensectie als documenten worden verwerkt, terwijl modellen in de sectie Documenten net als modellen kunnen worden verwerkt.

## 1. **Vóór/Na migratie - Belangrijkste verschillen**

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e8e8e880; width: 126px;"><h1 id="h_3632d3cc1b"></h1></td><td style="background-color: #e8e8e880; width: 262px;"><h2 class="intercom-align-center" id="h_2093155130"><b>Vóór</b></h2></td><td style="background-color: #e8e8e880; width: 248px;"><h2 class="intercom-align-center" id="h_d5cfcbcb2d"><b>Na</b></h2></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Hoofdgedrag</b></p></td><td style="width: 262px;"><p>Modellen bestonden alleen in de modelsectie. De gebruiker moest hetzelfde IFC-bestand naar zowel de sectie Document als Model uploaden.</p></td><td style="width: 248px;"><p>Modellen worden gemaakt op basis van IFC-bestanden die naar de sectie Document zijn geüpload, als de gebruiker dit aanvraagt. Het IFC-bestand en het bijbehorende model zijn dan gekoppeld.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Gebruikersinterface</b></p></td><td style="width: 262px;"><p><b>Anders</b> dan de sectie Document en minder informatie weergegeven, eigenlijk alleen een lijst met modellen.</p></td><td style="width: 248px;"><p><b>Hetzelfde</b> als de sectie Document: een aanpasbare tabel met gerelateerde metadata.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 126px;"><p class="intercom-align-right"><b>Toegangsrechten</b></p></td><td style="width: 262px;"><p><b>Kon niet worden toegepast</b> op modellen</p></td><td style="width: 248px;"><p><b>Kan worden toegepast</b> op modellen vanuit het gerelateerde document in de sectie Document</p></td></tr></tbody></table></div>

## 2. **Vertrouwd maar anders**

Nu de twee secties zijn gekoppeld, is het belangrijk op te merken dat er nog steeds enkele belangrijke verschillen tussen de modellen- en documentensecties zijn. In de modellensectie kunt u alle modeldocumenten in een lijst verzameld zien. Hier ziet u uw modeldocumenten op een manier die vergelijkbaar is met hoe ze in de 3D-viewer zullen worden gebruikt. In de sectie Documenten kunt u documentmodellen in uw documentstructuur zien. Hier ziet u uw documentmodellen op een manier die vergelijkbaar is met hoe ze in uw gemeenschappelijke gegevensomgeving zullen worden gebruikt. Alle modellen zijn gekoppeld aan hun eigen document en functies uit beide secties kunnen in zowel de modellensectie als in de sectie Documenten worden gebruikt.

## 3. **Wijzigingen in de modellensectie**

Met modellen als documenten is het uiterlijk van de modellensectie veranderd. In plaats van menu-items voor elk model worden deze nu weergegeven in een doorzoekbare tabel.

In de modellensectie vindt u de volgende wijzigingen:

### 3.1 **Modeltabel**

De nieuwe modeltabel kan er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/01-model-table.png)

### 3.2 **Kolommen**

De modellijst bevat kolommen met de meeste informatie die u over uw modellen moet weten.

_Naam_ De naam van het modeldocument. De modelnaam is ook de naam die u in de revisieselector in de 3D-weergave ziet.

**Documentnaam** De naam van het documentmodel in de sectie Documenten

**Revisienaam** De naam van de nieuwste revisie

### 3.3 **Toegangsbeheer**

Als een model voor u in de sectie Documenten is beperkt, ziet u het niet in de sectie Documenten, de modeltabel of in de revisieselector.

### 3.4 **Tabelelementen selecteren**

Met de modeltabel kunt u nu een reeks modellen selecteren door Shift ingedrukt te houden. U kunt ook modellen aan uw selectie toevoegen of eruit verwijderen door Ctrl ingedrukt te houden.

### 3.5 **Actieknoppen**

In het verleden was het enige wat u kon doen met geselecteerde modellen het openen van deze modellen in 3D. Nu kunt u de 2D-weergave van uw geselecteerde modellen downloaden, verwijderen en openen. Als u een model verwijdert dat is verbonden met een document, verliest het document de modelverbinding, maar het document blijft in de sectie Document.

### 3.6 **Toegang tot documentmodellen beheren**

**Een modeldocument maken** Als u een model maakt met de knop Model maken in de modellensectie, wordt u gevraagd te selecteren waar u het gekoppelde documentmodel in de sectie Documenten wilt plaatsen. In het dialoogvenster Model maken kunt u ook een naam voor het model opgeven. Het resulterende gekoppelde documentmodel heeft dezelfde naam als het model wanneer het wordt gemaakt. Catenda Hub onthoudt de map die u het laatst hebt gekozen en selecteert deze automatisch de volgende keer dat u een modeldocument maakt.

Als uw project zonder modellen als documenten is begonnen, verschijnt een map genaamd "Modellen" in uw mapstructuur. De modellenmap bevat alle documentmodellen die zijn gekoppeld aan modeldocumenten in de modelsectie. Documentmodellen kunnen uit deze map naar elke plaats in de sectie Documenten worden verplaatst waartoe u toegang hebt. Documentmodellen in de map Modellen kunnen ook worden verwijderd (en hersteld) als gewenst. Documentmodellen hoeven niet in de map te staan en de modellenmap kan indien nodig worden verwijderd.

**Een modelrevisie maken** Om nieuwe revisies naar een model te kunnen uploaden, hebt u ten minste schrijftoegang tot het documentmodel nodig. Nieuwe revisies van het model kunnen aan het document worden toegevoegd en omgekeerd.

> **Opmerking:** Revisiecommentaren zijn uitgeschakeld en kunnen nu optioneel worden ingeschakeld met [aangepaste velden in revisies](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents).

**Een modelrevisie downloaden** U hebt ten minste leestoegang tot het documentmodel nodig om het model te kunnen downloaden.

### 3.7 **Menu met juiste informatie**

Een menu met juiste informatie is beschikbaar als een model is geselecteerd.

**Documentveld** In dit menu ziet u uw modelinformatie en een grijs veld dat verwijst naar het documentmodel in de sectie Document dat is gekoppeld aan dit modeldocument. Klik op het documentveld om het documentmodel te openen dat aan dit model is gekoppeld.

**Modellabels** U kunt nu ook labels aan uw modellen toevoegen.

**Modelstatus** Als statussen in documentinstellingen zijn geconfigureerd, kunt u hier een status voor uw model configureren.

**Modeltransformatie** Als u dit model in 3D hebt geopend, kunt u hier de modeltransformatie configureren.

## 4. **Wijzigingen in de sectie Documenten**

Hoewel de visuele veranderingen niet zo duidelijk zijn als in de modellensectie, zijn er enkele dingen die in de sectie Documenten veranderen wanneer modellen als documenten is geactiveerd. Dit is wat documentmodellen in de sectie Documenten kunnen uitzien.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/02-documents-section-changes.png)

In de sectie Documenten vindt u de volgende wijzigingen:

### 4.1 **Modelfilter**

Zodra u modellen in de modellensectie hebt, ziet u een modelfilter in uw filtermenu verschijnen. Met dit filter kunt u alle gemaakte documentmodellen weergeven of verbergen.

### 4.2 **Kolommen**

**Pictogram** U kunt een documentmodel van een normaal document onderscheiden aan het modelbadge rechtsonder op het pictogram van het documentmodel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/03-columns.png)

**Naam** De naam van het document

**Modelnaam** De naam van het model. Als uw IFC-document nog niet aan een model is gekoppeld, ziet u hier een knop Model maken.

**Revisienaam** De naam van de nieuwste revisie in het model

**Viewer** Een kolom met knoppen om elk afzonderlijk documentmodel in de 3D-viewer te openen. Het openen van documentmodellen in de 3D-viewer is alleen mogelijk als het document aan een model is gekoppeld.

### 4.3 **Actieknoppen**

Download, verwijder of laad de 2D/3D-weergaven van geselecteerde modellen in de respectieve viewer door een of meer modellen te selecteren.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-9e345595c719.png" width="310"/>    <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/dkw8jgdd/inline-959af958f499.png" width="310"/>

Dit betekent dat u meerdere modellen tegelijk kunt verwijderen in plaats van één voor één zoals eerder. Als u een document verwijdert dat is verbonden met een model, moet u een waarschuwing goedkeuren dat het model dat aan het document is verbonden ook wordt verwijderd.

> **Opmerking:** Dit betekent dat u een model kunt verwijderen zonder gegevens kwijt te raken. (Verwijderde documenten kunnen worden hersteld)

### 4.4 **Toegang tot modelmodellen beheren**

**Documentmodellen maken** Om nieuwe revisies naar een model te kunnen uploaden, hebt u ten minste schrijftoegang tot het documentmodel nodig. U doet dit door een model te maken in het actiemenu van een document. Daarna ziet u het document als een model in de modellensectie. Het modeldocument in de modellensectie heeft dezelfde naam als het documentmodel, hoewel deze later elk afzonderlijk kunnen worden gewijzigd terwijl ze gekoppeld blijven. Nieuwe revisies van het model kunnen als revisies aan het document worden toegevoegd en omgekeerd.

> **Opmerking:** Dit betekent dat u tegelijkertijd modellen van meerdere IFC-bestanden kunt maken in plaats van ze één voor één te hoeven uploaden

**Revisies naar documentmodellen uploaden** U hebt ten minste schrijftoegang tot het documentmodel nodig om nieuwe revisies naar het model te kunnen uploaden. Dit betekent dat u de functie voor meerdere uploads kunt gebruiken om IFC-bestanden tegelijk naar meerdere documentmodellen te uploaden

**Documentmodellen downloaden** U hebt ten minste leestoegang tot het documentmodel nodig om het model te kunnen downloaden. Dit betekent dat u de toegang kunt configureren om het downloaden van afzonderlijke modellen toe te staan in plaats van alle of geen modellen.

### 4.5 **Vindbaarheid**

Documentmodellen kunnen nu in de sectie Documenten worden gevonden zoals elk ander document.

- Documentmodellen kunnen in mappen worden georganiseerd om gemakkelijker naar de juiste set modellen te navigeren.
- Labels kunnen aan documentmodellen worden toegevoegd om alle documentmodellen van één type te vinden.
- [Aangepaste velden kunnen aan mappen worden toegevoegd](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) waar documenten worden geüpload om te zoeken op metagegevenswaarden die verband houden met elk documentmodel
- [Aangepaste velden kunnen aan mappen worden toegevoegd](https://support.catenda.com/en/articles/9531080-custom-fields-on-documents) waar documenten worden geüpload om informatie aan elke revisie in elk documentmodel toe te voegen.

Zie [hier](https://support.catenda.com/en/articles/8542598-structuring-documents#h_7838a63c73) voor suggesties over hoe u uw documentmodellen structureert zodat deze gemakkelijk te vinden zijn.

### 4.6 **Gedeelde IFC-bestanden goedkeuren**

IFC-bestanden kunnen nu als gedeelde revisies worden geüpload zodat ze een goedkeuringsproces kunnen doorlopen voordat ze worden gepubliceerd.

### 4.7 **Naamgeving met documentmodellen**

Namen in de sectie Documenten bevatten vaak gecomprimeerde afkortingen om de documentnaam kort te houden terwijl u informatie over wat het document gaat weergeven. De naam van het documentmodel kan daarom verschillen van de naam van het modeldocument om deze in overeenstemming te houden met de andere documenten in de sectie Documenten, terwijl u een gemakkelijk leesbare naam behoudt voor gebruik in de 3D-viewer in de modellensectie. De documentnaam van het documentmodel is de naam die wordt herkend bij het uploaden van documenten naar de sectie Documenten. Als de naam gelijk is aan of gelijk aan het document, wordt automatisch een nieuwe revisie aangemaakt, net als bij andere documenten.

Omdat documentmodellen zich hetzelfde gedragen als normale modellen, is het nu mogelijk om de naamgevingsconventie met documentmodellen te gebruiken om ervoor te zorgen dat deelnemers aan uw project de juiste naam aan het document geven bij het uploaden.
