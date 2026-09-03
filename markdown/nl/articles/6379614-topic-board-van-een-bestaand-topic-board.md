# Topic board van een bestaand topic board

Een nieuw topic board kan worden gemaakt door op de actie voor een nieuw topic board op de [boards pagina](https://support.catenda.com/en/articles/9413644-boards-page) te klikken. De actie is te vinden met de groene plus-knop rechtsboven of in het bijbehorende actiemenu. Vereiste toegang: Schrijftoegang om nieuwe topic boards te maken in het toegangsmenu op de [projectinstellingenpagina](https://support.catenda.com/en/articles/4670273-project-settings-page).

Dit is hoe de pagina Nieuw topic board eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/01-intro.png)

## 1. **Naam**

Geef het topic board minimaal een naam om het topic board toe te voegen. De topic board-lijst is gesorteerd op topic board-naam volgens de typische [sorteeringsvolgorde van lijsten](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) op Catenda. Het is daarom vaak een goed idee om een naamconventie te gebruiken bij het benoemen van topic boards. Hier volgt een voorbeeld van hoe topic boards kunnen heten:

![Topicbordlijst introductie documentbeoordeling goedgekeurd goedgekeurd met opmerkingen afgewezen documenten breeam socre coördinatie kosten projecten](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/02-name.png)

## 2. **Omschrijving**

De omschrijving van het topic board is optioneel en kan later alleen worden weergegeven in de instellingen van het topic board voor degenen met volledige toegang tot het topic board. De omschrijving van het topic board volgt de algemene regels voor [opmaak van berichten](https://support.catenda.com/en/articles/8430847-formatting-of-posts) op Catenda.

## 3. **Kopieer instellingen van een bestaand topic board**

Om instellingen van het ene topic board naar het andere te kopiëren bij het aanmaken van een topic board, klikt u op het menu "instellingen kopiëren van een bestaand topic board" om een bestaand topic board in het project te selecteren waarvan de instellingen moeten worden gekopieerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/03-copy-settings-from-an-existing-topic-board.png)

Na het selecteren van het topic board kunt u kiezen welke instellingen u wilt kopiëren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/04-copy-settings-from-an-existing-topic-board.png)

### 3.1 **Kopieer statussen en types**

Activeer de radio-knop Statussen en types kopiëren om dezelfde statussen met hun statusnaam, kleur en metatype-status in het topic board te krijgen dat moet worden gemaakt.

### 3.2 **Instellingen voor kopieerrechten**

Activeer de radio-knop Toestemmingsinstellingen kopiëren om dezelfde statussen met hun kleur in het topic board te krijgen dat moet worden gemaakt.

## 4. **BCF 1.0 compatibiliteit**

Topic boards die worden gebruikt voor het exporteren van onderwerpen naar andere topic-beheerprogramma's die alleen BCF tot versie 1.0 ondersteunen, moeten voor compatibiliteit worden vergrendeld om ervoor te zorgen dat de onderwerpen die in Catenda zijn gegenereerd, foutloos aan de andere kant aankomen. BCF 1.0 onderwerpen die elders zijn gegenereerd, kunnen in elk topic board worden geïmporteerd, ongeacht of dat board voor compatibiliteit is vergrendeld of niet.

### 4.1 **Geen bewerking van statussen of types**

Door een topic board voor compatibiliteit te vergrendelen, is het niet mogelijk om de statussen en types die beschikbaar zijn in het topic board, te bewerken. Zolang het topic board voor compatibiliteit is vergrendeld, worden de vooraf gedefinieerde statussen en types zoals opgegeven in BCF 1.0 beschikbaar gemaakt en kunnen deze niet worden bewerkt. _Statussen:_ "Open" en "Gesloten" _Types:_ "Error", "Warning", "Info" en "Unknown"

### 4.2 **Vergrendelen en ontgrendelen van BCF 1.0 compatibiliteit na aanmaak**

Het selectievakje BCF 1.0 compatibiliteit kan op elk moment in de instellingen van het topic board worden uitgeschakeld om het aantal mogelijke statussen in het board uit te breiden. Als de statussen in een topic board niet compatibel zijn met BCF 1.0, is het ook mogelijk om statussen die niet compatibel zijn te verwijderen en het board op elk moment na aanmaak opnieuw voor BCF 1.0 compatibiliteit te vergrendelen.

### 4.3 **Instellingen kopiëren van board dat is vergrendeld**

Als een topic board wordt geselecteerd in het menu Instellingen kopiëren van een ander topic board, is het selectievakje BCF 1.0 compatibiliteit vergrendeld en wordt dit al dan niet ingeschakeld afhankelijk van of het geselecteerde topic board waarvan instellingen moeten worden gekopieerd, is vergrendeld voor BCF 1.0 compatibiliteit of niet.

## 5. **Toevoegen**

Klik op Toevoegen om het nieuwe topic board toe te voegen.

> **Opmerking:** Het topic board moet minstens een naam hebben om toe te voegen

Er is geen melding bij het aanmaken van een topic board.

## 6. **Topic board-aanmaak bij projectcreatie**

Bij het aanmaken van een nieuw project begint het project met een standaard topic board met de naam "Issues". Als het selectievakje voor topic boards uit een templateproject is ingeschakeld bij projectcreatie, begint het project met de topic boards en instellingen van het topic board uit het geselecteerde templateproject.

> **Opmerking:** Hoewel de instellingen van deze nieuwe topic boards gelijk zijn aan die van het topic board in de templates, zijn de GUID's van de topic boards, statussen en types uniek voor het project waarin ze zich bevinden.
