# 2D- en 3D-gezichtspunten

2D- en 3D-gezichtspunten kunnen worden toegevoegd als een [opmerking van een topic](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_f76b44d3ca). Snapshots zijn veelzijdige communicatiemiddelen voor 2D- en 3D-informatie omdat ze niet alleen visuele informatie bevatten maar ook kunnen worden gebruikt om een plaats en een moment in een document of model te beschrijven. De informatie die in snapshots wordt opgeslagen, stelt u in staat om samen te werken met 2D- en 3D-informatie, omdat u uw snapshot in elk van uw BCF- en IFC-compatibele services kunt afspelen.

Dit is hoe een 3D-snapshot eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/01-intro.png)

De onderstaande snapshot had de volgende instellingen toen de snapshot werd gemaakt: De snapshot werd opnieuw gemaakt met originele revisies. De 7 modeldocumenten die aan de snapshot waren gekoppeld, werden in de 3D-viewer geladen. De 5 geselecteerde objecten uit de modeldocumenten waren geselecteerd 2 Documenten die niet aan modellen waren gekoppeld, werden geladen waarvan één IFC en één puntenwolk. 2D-snapshots hebben dezelfde knoppen, maar met een afbeelding van de 2D-viewer bijgevoegd.

## 1. **Een snapshot maken**

Als u een model in 3D hebt geladen, kunt u op de plus-knop links van het opmerkingsveld voor het topic klikken om een 3D-snapshot aan uw opmerking toe te voegen. Als u de 2D-viewer hebt geopend, kunt u op de plus-knop links van het opmerkingsveld voor het topic klikken om een 2D-snapshot aan uw opmerking toe te voegen. Een snapshot wordt automatisch gemaakt als u iets in 2D of 3D hebt geladen en u een nieuw topic maakt. Klik [hier](https://support.catenda.com/en/articles/10345863-snapshots) voor meer informatie over snapshots.

## 2. **Viewer-afbeeldingen**

Snapshots zijn de beste manier om hoogwaardige afbeeldingen of renderings te maken vanuit de Catenda Hub-viewer om de volgende redenen:

- Snapshotafbeeldingen kunnen worden gedownload uit het [pop-out voor bijlagen](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_e36d14edc8).
- Snapshotafbeeldingen kunnen hogere resoluties hebben dan alleen een schermafbeelding uit de viewer.
- Snapshotafbeeldingen hebben transparante achtergronden. Bij 3D-snapshots bevat de afbeelding alleen pixels waar objecten in 3D zijn. Bij 2D-snapshots bevat de afbeelding alleen pixels waar lijnen in 2D zijn.

### 2.1 **Afbeeldingsgrootte**

De grootte van de bijgevoegde afbeelding hangt af van de grootte van de viewer en het inzoompercentage van de browser. Het aantal pixels in een snapshotafbeelding is afhankelijk van de grootte van de viewer, het inzoompercentage van de browser en uw weergaveschaal van het besturingssysteem. De grootste afbeelding die ik tot nu toe heb kunnen genereren is 6417 pixels bij 11113 pixels. Om een snapshot van deze grootte te maken, had ik de volgende instellingen:

- 4K-monitorweergave.
- Inhoudspaneel en 3D-paneel zichtbaar.
- Inhoudspaneel zo klein mogelijk.
- Browser op volledig scherm.
- Browservergroting 10%
- Weergaveschaal in Windows 100%

Deze instellingen belasten het systeem zeer zwaar en uw computer kan dit mogelijk niet verwerken. U moet deze instellingen dus mogelijk aanpassen aan uw specificaties.

## 3. **Afspeelpictogrammen**

Snapshots bevatten informatie over het moment waarop u de snapshot hebt gemaakt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/02-play-icons.png)

Als een object op het moment van creatie verborgen was, wordt het object met die ID verborgen wanneer de snapshot opnieuw wordt gemaakt. Als een object was geïsoleerd, wordt het object met die ID weergegeven terwijl objecten die niet zijn geïsoleerd, verborgen worden. Dit geldt ook voor objecten met nieuwe ID's die mogelijk worden toegevoegd aan nieuwere revisies van het model.

### 3.1 **Snapshot opnieuw maken**

Snapshots zijn geweldig voor het tonen van mensen wat u bekijkt, omdat zij dezelfde weergaven niet alleen in Catenda Hub maar ook in hun eigen omgeving opnieuw kunnen maken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/03-recreate-snapshot.png)

Snapshots kunnen opnieuw worden gemaakt door ze af te spelen in zowel Catenda Hub als in onze plugins. In Catenda Hub zal de snapshot de camera naar de juiste plaats in onze viewer verplaatsen. In de plugins wordt de viewer van de hostsoftware weergegeven.

- Door op deze knop te klikken wordt de snapshot opnieuw gemaakt met hetzelfde model en de nieuwste revisies geladen in de 3D-viewer.
- De verbonden puntenwolk- of IFC-Documenten worden geladen
- De camera in de 3D-viewer zal naar de locatie in de snapshot gaan.
- De snijvlakken uit de snapshot worden opnieuw gemaakt
- De objecten die in de snapshot waren geselecteerd, worden geselecteerd
- De kleuren die in selecties zijn ingesteld, krijgen hun opgegeven kleuren

### 3.2 **Snapshot opnieuw maken met originele revisies**

Klik op deze knop om de snapshot opnieuw te maken met het originele model.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/04-recreate-snapshot-with-original-revisions.png)

De modelrevisies die actief waren in de 3D-viewer op het moment van het maken van de snapshot worden in de 3D-viewer geladen wanneer op deze knop wordt geklikt.

## 4. **Inhoudspictogrammen**

In de rechterbenedenhoek van de snapshot vindt u pictogrammen die informatie bevatten over de inhoud van de snapshot.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/05-content-icons.png)

Als het inhoudspaneel klein wordt gemaakt, kunt u enkele van deze inhoudspictogrammen in het actiemenu vinden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/06-content-icons.png)

Het actiemenu bevindt zich rechtsboven in de snapshot waar niet genoeg ruimte is om alle inhoudspictogrammen weer te geven.

### 4.1 **Modelkiezer**

Als de 3D-viewer open is, is het modellaadinqmenu beschikbaar

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/07-model-picker.png)

- De modellen met een vinkje in dit menu worden geladen wanneer de snapshot wordt afgespeeld.

    <div class="intercom-container"><img height="24" src="https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/inline-b248400a1359.png" style="height: auto;" width="30"/></div>

- De modellen met een plus ervoor worden toegevoegd aan de set modellen met vinkje na opslaan.

    <div class="intercom-container"><img height="25" src="https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/inline-ca568d75479a.png" style="height: auto;" width="30"/></div>

- De modellen met een min ervoor worden verwijderd uit de set modellen met vinkje na opslaan.

    <div class="intercom-container"><img height="30" src="https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/inline-ff3494b6d9f8.png" style="height: auto;" width="30"/></div>

- Afhankelijk van de zichtbaarheid-instellingen van het object in de snapshot, kunnen toegevoegde modellen volledig verborgen zijn. Zelfs als deze niet zichtbaar zijn, zou u moeten zien dat ze zijn geladen wanneer het topic wordt afgespeeld.
- De modellen die aan zijn wanneer dit menu wordt geopend, weerspiegelen de modellen die momenteel in de 3D-viewer zijn geladen. Om eenvoudig een set modellen toe te voegen of te verwijderen, kunt u een bladwijzer maken, de bladwijzer afspelen, naar de snapshot gaan, op het actiemenu ervan klikken en opslaan in het modellaadinqmenu.
- Als een model in uw snapshot dezelfde IFCPROJECT GUID heeft als een model in de modelssectie, worden de modellen automatisch gekoppeld.

Hier is een artikel van BuildingSMART waarin wordt beschreven hoe dit in Revit wordt gedaan [https://user.buildingsmart.org/knowledge-base/ifcproject/](https://user.buildingsmart.org/knowledge-base/ifcproject/)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/08-model-picker.png)

### 4.2 **Geselecteerde objecten weergeven**

Selecteer de objecten die in de snapshots zijn geselecteerd in de 3D-viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/09-show-selected-objects.png)

Toont hoeveel objecten in de snapshot zijn geselecteerd

### 4.3 **Gekoppelde documenten**

Klik hier om de modellen uit de snapshot naast de modellen die al in de viewer bestaan te laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/10-linked-documents.png)

Toont hoeveel modellen in de snapshot zijn geladen.

### 4.4 **Camerapositie instellen**

Zet de camera op de positie van de snapshot in de 3D-viewer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/11-set-camera-position.png)

Als u uw 3D-weergave hebt verplaatst nadat u de snapshot hebt afgespeeld, kunt u op deze knop klikken om terug te gaan naar de positie van de snapshot.

## 5. **Afbeelding uitklappen**

Als u met uw muis over de afbeelding van een 2D- of 3D-snapshot beweegt, verschijnt er een vergrootglas. Dit kan er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/12-image-pop-out.png)

Nadat de snapshot is ingediend, kan de afbeelding die eraan is gekoppeld [worden uitgeklapt](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_e36d14edc8) om de inhoud in een groter formaat te zien en te downloaden.

## 6. **Een snapshot verwijderen**

Het is niet mogelijk om een snapshot die aan een opmerking is gekoppeld te verwijderen. Als u de snapshot uit het topic wilt verwijderen, moet u de hele opmerking verwijderen.
