# Catenda Desktop Connector

> **Opmerking:** Het installatiebestand voor deze toepassing is [hier](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations) te vinden

Met de Catenda Desktop Connector kunt u uploads en downloads van de nieuwste versies van Documenten plannen.

## 1. **Direct uploaden/downloaden**

### 1.1 **Uploaden**

Selecteer een map op een lokaal systeem om alle mapinhoud, inclusief bestanden in submappen van de geselecteerde map, met de Desktop Connector naar een opgegeven map op Catenda Hub te uploaden.

**Geslaagde uploads** Als u meerdere bestanden sleept en neerzet of de zip-upload-functie op Catenda Hub gebruikt, uploadt u één grote reeks gegevens. Hoe groter de upload, hoe langer u moet wachten voordat u uw bestanden in de Catenda Hub-documentstructuur kunt indienen.

**Eén bestand tegelijk** Door bestanden uit een mapstructuur één bestand tegelijk met de Desktop Connector te uploaden, kunt u de upload onderbreken en later voortzetten.

**Verlaag het risico op uploadfouten** Hoe groter de upload, hoe hoger het risico dat deze mislukt. Misschien gaat uw stroom uit, misschien breekt uw internetverbinding voor een fractie van een seconde. Dan moet u de upload helemaal opnieuw starten.

### 1.2 **Downloaden**

Selecteer één of meer afzonderlijke Documenten of selecteer een map op Catenda Hub om de selectie, inclusief Documenten in submappen van geselecteerde mappen, naar een locatie op uw lokale machine te downloaden.

### 1.3 **Overdrachtssnelheid**

Zowel het uploaden als het downloaden van bestanden met de Desktop Connector is sneller dan het reguliere uploadproces, omdat de bestanden via de API worden geïmporteerd zonder de overhead van een actieve browser of andere browserbeperkingen. Voor het overdragen van een enkel bestand wordt slepen of neerzetten met een browser aanbevolen vanwege het gebruiksgemak, maar voor het overdragen van grote hoeveelheden gegevens in één keer of voor diegenen die tijd willen besparen bij uploads van grote afzonderlijke bestanden, is de Desktop Connector de aanbevolen manier voor overdracht.

### 1.4 **Toegang**

Toegangsbeheer dat is geconfigureerd op Catenda Hub wordt gehandhaafd. Gebruikers kunnen uploaden naar locaties in de Catenda-documentstructuur waar zij ten minste schrijftoegang hebben en kunnen alleen Documenten downloaden waarvoor zij ten minste leestoegang hebben.

## 2. **Synchronisatie**

Bestanden kunnen worden gepland om met regelmatige intervallen te worden geupload of gedownload.

### 2.1 **Lokaal systeem -> Catenda Hub**

De Desktop Connector kan ervoor zorgen dat bestanden in een Catenda Hub-project actueel blijven met de meest recente opslagstatus van een bestand op het lokale systeem.

### 2.2 **Catenda Hub -> Lokaal systeem**

De Desktop Connector kan ervoor zorgen dat bestanden op een lokaal systeem actueel blijven met de meest recente revision van een Document in een Catenda Hub-project.

## 3. **Installatie**

Wanneer de Catenda Desktop Connector op Windows wordt geïnstalleerd, verschijnen de installatiebestanden in de volgende map.

`C:\Program Files\Catenda Hub Desktop Connector`

### 3.1 **Verwijderen**

Ga naar het volgende Windows-menu om de invoegtoepassing te verwijderen:

`Windows-instellingen -> Apps -> Geïnstalleerde apps`

Zoek Desktop Connector in de lijst en klik op het actiemenu aan de rechterkant om het te verwijderen.

## 4. **Inloggen**

Wanneer de Desktop Connector voor het eerst wordt geopend, wordt een inloggingsverzoek weergegeven. Klik op de knop Inloggen om de standaardbrowser op het systeem op de inlogpagina van Catenda te openen. Nadat u zich hebt aangemeld of als u al bent aangemeld, klikt u op Toegang toestaan om toegang te verlenen tot het Catenda-account dat is aangemeld. Nadat u op Toegang toestaan hebt geklikt, vraagt de browser de gebruiker om de Desktop Connector-toepassing te openen. Het geven van toestemming voor het openen van de toepassing leidt terug naar de [startpagina](#h_097078145d) van de Desktop Connector.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/01-sign-in.png)

## 5. **Startpagina**

Dit is hoe de Desktop Connector eruit kan zien wanneer deze wordt gestart met een geldige inloggegevens:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/02-home-page.png)

### 5.1 **PC uit slaapstand halen**

Haal de pc uit de slaapstand als een taak op dat moment moet worden uitgevoerd.

### 5.2 **Uitvoeren bij opstarten**

Om de Desktop Connector bij het opstarten uit te voeren, selecteert u deze optie

### 5.3 **Uitloggen**

Klik op de knop Uitloggen rechtsonder om uit te loggen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/03-log-out.png)

## 6. **Projectlijst**

Een overzicht van de projecten waartoe het account de laatste keer had toegang toen de projectenlijst werd geladen, wordt weergegeven. Voor elk project wordt het aantal geconfigureerde upload- en downloadtaken weergegeven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/04-project-list.png)

### 6.1 **Synchroniseer-knop**

Als u onlangs aan een project bent toegevoegd, klikt u op deze synchroniseer-knop om de nieuwe lijst met projecten waarvan het ingelogde account deel uitmaakt, in te laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/05-synchronize-button.png)

### 6.2 **Naam**

Klik op de naam van een project om de huidige upload- en downloadtaken te bekijken of een nieuwe taak in te plannen.

### 6.3 **Uploadtaken**

Het aantal uploadtaken dat actief is voor dit project

### 6.4 **Downloadtaken**

Het aantal downloadtaken dat actief is voor dit project

## 7. **Uploadtaak**

Plan een periodieke upload van bestanden van uw systeem naar Catenda Hub in met deze taak.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/06-upload-task.png)

### 7.1 **Titel - Vereist**

De uploadtaak moet ten minste een titel hebben om te worden opgeslagen

### 7.2 **Planningskalender - Vereist**

De taak moet ten minste één dag geselecteerd hebben om te worden opgeslagen

### 7.3 **Projectlocatie**

**Server** Klik op bladeren om de bestemming op de pagina Documenten in Catenda Hub te selecteren waar bestanden naartoe moeten worden gesynchroniseerd. Klik [hier](#h_4446f1b663) voor meer informatie over het selecteren van het mappad op de server

**Lokaal** Selecteer de locatie op het lokale systeem van waaruit bestanden moeten worden gesynchroniseerd.

### 7.4 **Direct**

Taken hoeven niet te worden opgeslagen om het uploadproces te starten. Klik op het vak Nu uploaden om deze taak direct te starten. Opgeslagen taken worden periodiek op het ingestelde moment uitgevoerd.

## 8. **Downloadtaak**

Plan een periodieke download van bestanden van Catenda Hub naar het lokale systeem in.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/07-download-task.png)

### 8.1 **Titel - Vereist**

De uploadtaak moet ten minste een titel hebben om te worden opgeslagen

### 8.2 **Planningskalender - Vereist**

De taak moet ten minste één dag geselecteerd hebben om te worden opgeslagen

### 8.3 **Projectlocatie**

**Server** Selecteer de locatie op Catenda Hub van waaruit Documenten moeten worden gedownload. Klik [hier](#h_4446f1b663) voor meer informatie over het selecteren van het mappad op de server

**Lokaal** Selecteer de bestemming op het lokale systeem waar bestanden naartoe moeten worden gedownload.

### 8.4 **Direct**

Een taak hoeft niet te worden opgeslagen om te beginnen met downloaden. Klik op het vak Nu downloaden om deze taak direct te starten. Sla de taak op om de download periodiek op het ingestelde moment uit te voeren. De gedownloade Documenten worden op uw systeem gedecomprimeerd.

### 8.5 Knop Terug

Klik op de pijlknop om terug te gaan naar de [startpagina](#h_097078145d)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 9. **Serverlocatie**

Klik op bladeren in het projectlocatiegebied van een upload- of downloadtaak om het mappad van het Catenda-project te bladeren. Het dialoogvenster Mappad kiezen wordt geopend. Eenmaal geopend begint het met het downloaden van alle mapnamen in het project en hun hiërarchie. Voor downloadtaken worden ook documentnamen gedownload. Terwijl het downloaden aan de gang is, kan het dialoogvenster er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/09-server-location.png)

Met name voor downloadtaken, als er veel mappen en Documenten zijn, kan dit proces enkele minuten in beslag nemen. Zorg ervoor dat er voldoende geheugen beschikbaar is op het lokale systeem voor deze stap.

**Dialooggrootte** Klik op Min of Max in de rechterboven hoek om het dialoogvenster Mappad kiezen te minimaliseren of maximaliseren.

**Mapaacties** Nadat de mappen in het dialoogvenster zijn geladen, kan dit er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/10-server-location.png)

Klik op de pijl naast een map om deze uit te vouwen. Documenten zijn alleen beschikbaar in deze weergave voor downloadtaken.

**Map selecteren** Klik op een map om deze te selecteren. Voor downloadtaken kunnen meerdere mappen worden geselecteerd, terwijl voor uploadtaken slechts één map per keer kan worden geselecteerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/11-server-location.png)

Nadat een map is geselecteerd, verschijnt deze als wit met een vinkje. Alle submappen van de geselecteerde map worden doorgestreept omdat het alleen mogelijk is mappen op hetzelfde niveau te selecteren. Bovenaan wordt het aantal geselecteerde items weergegeven.

**Downloadtaak** Als er Documenten in de geselecteerde map of de bijbehorende submappen staan, worden alle mappen in het pad tussen de geselecteerde map en het Document gemaakt. Het Document wordt vervolgens naar die map gedownload. Als een submap geen Documenten bevat, wordt de submap niet gemaakt, ook al kan deze in dit dialoogvenster zijn aangevinkt. Het is niet mogelijk een submap uit te vinken om niet deel van een mapstructuur te downloaden. Selecteer ze afzonderlijk zoals in de onderstaande afbeelding om alleen bepaalde mappen te downloaden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/12-server-location.png)

Document selecteren Klik op een Document om het te selecteren

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/13-server-location.png)

Wanneer afzonderlijke Documenten worden geselecteerd, worden de Documenten gedownload als een platte lijst rechtstreeks naar het geselecteerde lokale pad zonder de hiërarchie van de mappen waarin deze Documenten zich bevinden.

**Uploadtaak** Documenten worden naar de geselecteerde map geupload. Als de mapnaam overeenkomt, worden Documenten naar submappen van de geselecteerde map geupload.

## 10. **Takenlijst**

Hier kunnen de upload- en downloadtaken die in deze installatie voor de ingelogde gebruiker zijn geconfigureerd, worden bekeken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/14-task-list.png)

### 10.1 **Naam**

De naam van de taak.

### 10.2 **Taak**

Het geplande moment waarop de taak zal worden uitgevoerd.

### 10.3 **Project**

De naam van het project waarin deze taak zal worden uitgevoerd.

### 10.4 **Status**

De Status van deze taak.

### 10.5 **Knop Terug**

Klik op deze knop om terug te gaan naar de [startpagina](#h_097078145d)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 11. **Logmap**

Deze knop opent de maplocatie van de Desktop Connector-logboeken op het lokale systeem. De standaardlocatie van deze logboeken is:

`C:\Users\<Windows account name>\AppData\Local\User Name\2b92d867-496c-47d1-ac42-fbf8fa355177\Cache\BimsyncApp`
