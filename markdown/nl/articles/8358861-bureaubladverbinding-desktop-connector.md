# Catenda Desktop Connector

> **Opmerking:** Het installatiebestand voor deze applicatie vindt u [hier](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)

Met de Catenda desktop connector kunt u up- en downloads van de nieuwste versies van Documenten plannen.

## 1. **Instant up/downloads**

### 1.1 **Upload**

Selecteer een map op een lokaal systeem om alle mapinhoud, inclusief bestanden in submappen van de geselecteerde map, met de Desktop Connector naar een opgegeven map op Catenda Hub te uploaden.

**Geslaagde uploads** Als u meerdere bestanden sleept en neerzet of de zip-uploadfunctie op Catenda Hub gebruikt, uploadt u één grote reeks gegevens. Hoe groter de upload, hoe langer u moet wachten voordat u uw bestanden in de Catenda Hub documentstructuur kunt indienen.

**Eén bestand tegelijk** Door bestanden van een mapstructuur één bestand tegelijk met de Desktop Connector te uploaden, kunt u de upload onderbreken en later voortzetten.

**Verkleinen van het uploadfoutrisico** Hoe groter de upload, hoe hoger het risico dat het ook mislukt. Misschien gaat uw stroom uit, misschien breekt uw internetverbinding even. Dan zou u de upload helemaal opnieuw moeten starten.

### 1.2 **Download**

Selecteer één of meer afzonderlijke Documenten of selecteer een map op Catenda Hub om de selectie, inclusief Documenten in submappen van geselecteerde mappen, naar een locatie op uw lokale computer te downloaden.

### 1.3 **Overdrachtssnelheid**

Zowel up- als downloaden van bestanden met de Desktop connector is sneller voor bestandsoverdracht dan het normale uploadproces, omdat de bestanden via de API worden geïmporteerd zonder dat de overhead van een actieve browser of andere browserbeperkingen nodig is. Voor het overdragen van één bestand wordt het slepen of neerzetten met een browser aanbevolen vanwege het gemak van gebruik, maar voor het overdragen van grote hoeveelheden gegevens tegelijk of voor degenen die tijd willen besparen bij uploads van grote enkele bestanden, is de Desktop Connector de aanbevolen manier voor overdracht.

### 1.4 **Toegang**

Toegangsbeheer dat op Catenda Hub is geconfigureerd, blijft gehandhaafd. Gebruikers kunnen uploaden naar locaties in de Catenda Documentstructuur waar zij minstens schrijftoegang hebben en kunnen alleen Documenten downloaden waar zij minstens leestoegang toe hebben.

## 2. **Synchronisatie**

Bestanden kunnen op regelmatige intervallen up- of worden gedownload.

### 2.1 **Lokaal systeem -> Catenda Hub**

De Desktop Connector kan ervoor zorgen dat bestanden in een Catenda Hub project actueel blijven met de nieuwste opslagstatus van een bestand op het lokale systeem.

### 2.2 **Catenda Hub -> Lokaal systeem**

De Desktop Connector kan ervoor zorgen dat bestanden op een lokaal systeem actueel blijven met de nieuwste versie van een Document in een Catenda Hub project.

## 3. **Installatie**

Wanneer de Catenda Desktop Connector op Windows is geïnstalleerd, verschijnen de installatiebestanden in de volgende map.

`C:\\Program Files\\Catenda Hub Desktop Connector`

### 3.1 **Verwijderen**

Ga naar het volgende Windows-menu om de plug-in te verwijderen:

`Windows-instellingen -> Apps -> Geïnstalleerde apps`

Zoek Desktop Connector in de lijst en klik op het actiemenu aan de rechterkant om te verwijderen.

## 4. **Aanmelden**

Wanneer de Desktop Connector voor het eerst wordt geopend, wordt een aanmeldingsverzoek weergegeven. Klik op de knop Aanmelden om de standaardbrowser op het systeem op de Catenda-aanmeldingspagina te openen. Nadat u bent aangemeld of als u al bent aangemeld, klikt u op Toegang toestaan om toegang te verlenen tot het aangemelde Catenda-account. Nadat u op Toegang toestaan hebt geklikt, vraagt de browser u om de Desktop Connector-toepassing te openen. Door toestemming te geven voor het openen van de toepassing keert u terug naar de Desktop Connector [startpagina](#home-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/01-sign-in.png)

## 5. **Startpagina**

Dit is hoe de Desktop Connector eruit kan zien wanneer deze wordt gestart met een geldige aanmelding:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/02-home-page.png)

### 5.1 **PC uit slaapstand wekken**

Zet de PC uit de slaapstand als een taak is ingepland om op dat moment te worden uitgevoerd.

### 5.2 **Uitvoeren bij opstarten**

Als u de desktop connector bij het opstarten wilt uitvoeren, selecteert u deze optie

### 5.3 **Afmelden**

Klik op de afmeldingsknop rechtsonder om u af te melden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/03-log-out.png)

## 6. **Projectlijst**

Er wordt een overzicht weergegeven van de projecten waartoe het account de laatste keer dat de projectlijst werd geladen toegang had. Voor elk project wordt het aantal geconfigureerde up- en downloadtaken weergegeven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/04-project-list.png)

### 6.1 **Synchronisatieknop**

Als u onlangs bent lid van een project, klikt u op deze synchronisatieknop om de nieuwe lijst met projecten waarvan het aangemelde account lid is, in te laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/05-synchronize-button.png)

### 6.2 **Naam**

Klik op de naam van een project om de huidige up- en downloadtaken te zien of een nieuwe taak in te plannen.

### 6.3 **Uploadtaken**

Het aantal uploadtaken dat actief is voor dit project

### 6.4 **Downloadtaken**

Het aantal downloadtaken dat actief is voor dit project

## 7. **Uploadtaak**

Plan een periodieke upload van bestanden van uw systeem naar Catenda Hub in met deze taak.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/06-upload-task.png)

### 7.1 **Titel - Vereist**

De uploadtaak moet minstens een titel hebben om te worden opgeslagen

### 7.2 **Schema kalender - Vereist**

De taak moet minstens één dag geselecteerd hebben om te worden opgeslagen

### 7.3 **Projectlocatie**

**Server** Klik op bladeren om de bestemming op de Documentenpagina in Catenda Hub te selecteren waar bestanden gesynchroniseerd moeten worden. Klik [hier](#server-location) voor meer informatie over het selecteren van het servermapcpad

**Lokaal** Selecteer de locatie op het lokale systeem van waaruit bestanden gesynchroniseerd moeten worden.

### 7.4 **Instant**

Taken hoeven niet te worden opgeslagen om het uploadproces te starten. Klik op het vak Nu uploaden om deze taak onmiddellijk te starten. Opgeslagen taken worden periodiek op het geconfigureerde moment uitgevoerd.

## 8. **Downloadtaak**

Plan een periodieke download van bestanden van Catenda Hub naar het lokale systeem in.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/07-download-task.png)

### 8.1 **Titel - Vereist**

De uploadtaak moet minstens een titel hebben om te worden opgeslagen

### 8.2 **Schema kalender - Vereist**

De taak moet minstens één dag geselecteerd hebben om te worden opgeslagen

### 8.3 **Projectlocatie**

**Server** Selecteer de locatie op Catenda Hub van waaruit Documenten moeten worden gedownload. Klik [hier](#server-location) voor meer informatie over het selecteren van het servermapcpad

**Lokaal** Selecteer de bestemming op het lokale systeem waar bestanden naar moeten worden gedownload.

### 8.4 **Instant**

Een taak hoeft niet te worden opgeslagen om te beginnen met downloaden. Klik op het vak Nu downloaden om deze taak onmiddellijk te starten. Sla de taak op om de download periodiek op het geconfigureerde moment uit te voeren. De gedownloade Documenten verschijnen gedecomprimeerd op uw systeem.

### 8.5 Terug knop

Klik op de pijlknop om terug te gaan naar de [startpagina](#home-page)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 9. **Serverlocatie**

Klik op bladeren in het projectlocatiegebied van een upload- of downloadtaak om het mapcpad van het Catenda-project te gaan bladeren. Het dialoogvenster Map kiezen wordt geopend. Zodra geopend, begint het alle mapnamen in het project en hun hiërarchie te downloaden. Voor downloadtaken worden ook documentnamen gedownload. Terwijl het downloaden aan de gang is, kan het dialoogvenster er zo uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/09-server-location.png)

Vooral voor downloadtaken kan het enige minuten duren als er veel mappen en Documenten zijn. Zorg ervoor dat er voldoende geheugen op het lokale systeem beschikbaar is voor deze stap.

**Dialooggrootte** Klik op Min of Max rechtsboven om het dialoogvenster Map kiezen te minimaliseren of te maximaliseren.

**Mapacties** Nadat de mappen zijn geladen, kan het dialoogvenster er ongeveer zo uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/10-server-location.png)

Klik op de pijl naast een map om deze uit te vouwen. Documenten zijn alleen beschikbaar in deze weergave voor downloadtaken.

**Mapselectie** Klik op een map om deze te selecteren. Voor downloadtaken kunnen meerdere mappen worden geselecteerd, terwijl voor uploadtaken slechts één map tegelijk kan worden geselecteerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/11-server-location.png)

Nadat een map is geselecteerd, verschijnt deze wit met een vinkje. Alle submappen van de geselecteerde map verschijnen doorgestreept, omdat het alleen mogelijk is mappen op hetzelfde niveau te selecteren. Bovenaan wordt het aantal geselecteerde items weergegeven.

**Downloadtaak** Als er Documenten in de geselecteerde map of bijbehorende submappen aanwezig zijn, worden alle mappen in het pad tussen de geselecteerde map en het document gemaakt. Het Document wordt vervolgens naar die map gedownload. Als een submap geen Documenten bevat, wordt de submap niet gemaakt, ook al kan deze in dit dialoogvenster zijn ingeschakeld. Het is niet mogelijk een submap uit te schakelen om geen deel van een mapstructuur te downloaden. Als u alleen bepaalde mappen wilt downloaden, selecteert u ze afzonderlijk zoals in de afbeelding hieronder:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/12-server-location.png)

Documentselectie Klik op een Document om dit te selecteren

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/13-server-location.png)

Wanneer afzonderlijke Documenten worden geselecteerd, worden de Documenten gedownload als een vlakke lijst rechtstreeks naar het geselecteerde lokale pad, zonder de hiërarchie van de mappen waarin die Documenten zich bevinden.

**Uploadtaak** Documenten worden naar de geselecteerde map geupload. Als de mapnaam overeenkomt, worden Documenten naar submappen van de geselecteerde map geupload.

## 10. **Takenlijst**

Hier kunnen de up- en downloadtaken worden gezien die in deze installatie voor de aangemelde gebruiker zijn geconfigureerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/14-task-list.png)

### 10.1 **Naam**

De naam van de taak.

### 10.2 **Taak**

Het geplande moment waarop de taak wordt uitgevoerd.

### 10.3 **Project**

De naam van het project waarin deze taak wordt uitgevoerd.

### 10.4 **Status**

De Status van deze taak.

### 10.5 **Terug knop**

Klik op deze knop om terug te gaan naar de [startpagina](#home-page)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tfqdkst1/08-back-button.png)

## 11. **Logmap**

Met deze knop opent u de maplocatie van de Desktop Connector-logboeken op het lokale systeem. De standaardlocatie van deze logboeken is:

`C:\\Users\\\<Windows account name>\\AppData\\Local\\User Name\\2b92d867-496c-47d1-ac42-fbf8fa355177\\Cache\\BimsyncApp`
