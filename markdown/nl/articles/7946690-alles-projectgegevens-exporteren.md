# Alles projectgegevens exporteren

> Overzicht van exportmethoden voor projectgegevens, documenten, modellen en topics in Catenda Hub. Opties: Desktop Connector-synchronisatie, PDF/A-rapporten, controle van toegangsmachtigingen en automatische cloudback-ups naar AWS S3 of Azure Blob.

Catenda Hub biedt flexibele exportmethoden die zijn afgestemd op diverse projectbehoeften, variërend van dagelijkse downloads tot geautomatiseerde bedrijfsarchivering. Afhankelijk van specifieke projectvereisten is het mogelijk om grote mappenstructuren te synchroniseren met behulp van Desktop Connector, aangepaste documentleverings-checklists en PDF/A-archieven via de pagina Rapporten te genereren, of projecttoegangsmachtigingen voor controletrails te documenteren. Voor organisaties die continue cloud-naar-cloud back-ups nodig hebben, biedt Catenda Data Export geautomatiseerde overdrachten rechtstreeks naar AWS S3 of Azure Blob-opslag.

## 1. **Waarom exporteren**

Projecteigenaren en projectdeelnemers moeten vaak lokale kopieën van projectdocumentatie bijhouden tijdens en na de levenscyclus van een project.

### 1.1 **Gegevenstoezending en faseveranderingen**

Projectgegevens kunnen op verschillende projectmijlpalen nodig zijn:

**Faseveranderingen** Transities tussen planning, ontwerp en constructie vereisen vaak het uitpakken van gegevensmomentopnamen, vooral als projecten worden opgeheven of aan nieuwe partijen worden overgedragen.

**Overheidsonderzoeken** Formele toezendingen naar autoriteiten zijn tijdens of na voltooiing van een project vaak vereist.

**Aanbestedingen** Voorbereiding van documenttoezendingspakketten voor aanbestedingen.

### 1.2 **Onafhankelijke gegevensbehoud en toegangsbescherming**

Exporteren is niet beperkt tot projectvoltooiing. Projectleden die niet eigenaar zijn van de belangrijkste projectgegevens, hebben vaak hun eigen kopieën nodig om voortdurende toegang tot hun werk te garanderen.

Projectleden worden niet altijd vooraf geïnformeerd wanneer projecttoegang afloopt, en toegang kan soms eerder dan verwacht worden ingetrokken. Omdat toegang zonder waarschuwing kan verloren gaan, is het configureren van **geplande, herhaalde exports**, zoals met **Catenda Data Export** of de **Catenda Desktop Connector**, van cruciaal belang. Deze herhaalde hulpmiddelen zorgen ervoor dat projectleden tot en met de laatste geplande run voordat zij toegang verliezen, een lokale of cloudback-up behouden.

### 1.3 **Gegevensarchivering en compliance**

Regelgeving en industrienormen schrijven vaak voor dat verantwoordelijke partijen projectdossiers voor lange perioden bewaren, vaak meerdere jaren of decennia. Systeemdeocumentatie, productrecords en nalevingsbestanden moeten mogelijk op bedrijfsservers of aangewezen opslagruimten worden bewaard.

### 1.4 **Projectbeëindiging**

Wanneer een actief project wordt voltooid of een licentieperiode afloopt, zorgt Catenda ervoor dat projectgegevens veilig blijven opgeslagen. Zelfs als projecttoegang afloopt, blijven gegevens tot drie jaar lang herstelbaa op Catenda-servers.

### 1.5 **Bevroren archiefoptie**

Met een archiveringsoptie kunnen projecten toegankelijk blijven als bevroren, alleen-lezen opslagruimten voor geselecteerde leden.

## 2. **Standaardexportopties**

Deze ingebouwde exportgereedschappen zijn rechtstreeks beschikbaar in de standaardinterface voor alle bevoegde projectdeelnemers.

### 2.1 **Modellen exporteren**

Omdat elk model in Catenda is gekoppeld aan een document in de documentensectie, gelden de standaard documentexportmogelijkheden ook voor modellen. Daarnaast zijn speciale exportopties beschikbaar die speciaal voor modellen bedoeld zijn:

**Geselecteerde modeldownload** Selecteer een of meer modellen op de [modelenpagina](https://support.catenda.com/nl/articles/4670286-modellapagina) en gebruik de downloadactie om de nieuwste revisies uit te pakken.

**Afzonderlijke revisiedownload** Selecteer een model op de [modelenpagina](https://support.catenda.com/nl/articles/4670286-modellapagina) en klik op de downloadknop naast elke revisie in het informatiedeelvenster aan de rechterkant. Dit biedt een efficiënte manier om specifieke revisies rechtstreeks te downloaden zonder dat u de volledige [modelinhoudsenpagina](https://support.catenda.com/nl/articles/4670270-pagina-met-modelinhoud) hoeft in te laden. U kunt afzonderlijke revisies ook rechtstreeks downloaden van de inhoudspagina van een model.

**Geavanceerde modelexport** Open de [modelexportpagina](https://support.catenda.com/nl/articles/4670280-pagina-model-export) om geselecteerde revisies van meerdere modellen in één downloadbare ZIP-bestand in te pakken. Deze methode bevat geavanceerde opties om de geëxporteerde modelbestanden te verbeteren door tags, door de gebruiker gedefinieerde eigenschappen of bibliotheekgegevens in te bakken.

### 2.2 **Topics exporteren (3 manieren)**

Topicgegevens kunnen in drie primaire formaten worden geëxtraheerd via [topics uitwisselen](https://support.catenda.com/nl/articles/4670289-wissel-topics-uit), afhankelijk van hoe de informatie zal worden bekeken, geanalyseerd of opgeslagen:

**BCF (BIM Collaboration Format)** Een open standaard die is ontworpen om topicgegevens vast te leggen en over te dragen, strikt in overeenstemming met de officiële BCF-specificatie, inclusief individuele topicaanmaaktijdstempels. Dit formaat garandeert brede platformonafhankelijke interoperabiliteit, wat ideaal is voor het opnieuw openen, bewerken of naadloos uitwisselen van topicgegevens met andere BCF-compatibele software. Voor algemene langetermijn-documentopslagruimten waar directe bestandsvoorbeelden nodig zijn, hebben PDF- of Excel-formaten meestal de voorkeur.

**Excel** Exporteert topicparameters naar een spreadsheetindeling voor filteren, sorteren en gegevensmanipulatie. Dit formaat biedt gestructureerde rijen en kolommen die ideaal zijn voor het selecteren en kopiëren van gegevens. Excel-bestanden kunnen eenvoudig worden bekeken in de meeste archiveringsplatforms. Voor archiveringsdoeleinden heeft de PDF-export meestal de voorkeur boven Excel omdat deze meer informatie bevat.

**PDF** Genereert een schoon, leesbaar samenvattingsrapport in standaard PDF-indeling (v1.4) toegankelijk zonder gespecialiseerde software (zie [topics naar PDF exporteren](https://support.catenda.com/nl/articles/9784934-onderwerpen-naar-pdf-exporteren)). Standaard PDF-exports bevatten een geconsolideerde downloadtijdstempel voor officiële overheidsrapportage en archivering, met meer informatie dan een Excel-export. Terwijl de basisexport een standaard PDF-bestand (v1.4) genereert, dat veel archiveringssystemen automatisch naar PDF/A converteren bij upload voor langdurig voorbeeld, kunnen projecten met de opt-in [rapportenpagina](https://support.catenda.com/nl/articles/12303098-rapportenpagina) ingeschakeld ook topics in archiveringindelingen exporteren, zoals beschreven in [Projectgegevens exporteren met rapporten](https://support.catenda.com/nl/articles/17779017-projectgegevens-exporteren-met-rapporten) _(alleen rapporteditor-klanten)_.

### 2.3 **Documenten en bundels exporteren**

**Batch- en mapmapdownloads** Selecteer afzonderlijke mappen, specifieke documentbatches of alle zichtbare tabelitems tegelijk om een downloadbaar ZIP-archief te genereren. Het wordt aanbevolen om in beheersbare batches te downloaden door specifieke submappen of gericht bestandsgroepen te selecteren voor soepele overdrachten wanneer u met grote gegevensverzamelingen werkt.

- **Gepubliceerd tabblad**<br>Haalt de meest recente gepubliceerde revision voor elk geselecteerd document op.
- **Workspace-tabblad**<br>Haalt de meest recente gedeelde revision voor elk geselecteerd document op (vereist de machtiging "Gedeelde revisies weergeven"). Let op: legacy conceptrevisies kunnen niet in bulk naar een ZIP-archief worden gedownload en worden afzonderlijk gedownload.

**Afzonderlijke revisiedownload** Selecteer een document op de [documentenpagina](https://support.catenda.com/nl/articles/8204673-documentenpagina) en klik op de downloadknop naast elke revisie in het informatiedeelvenster aan de rechterkant. Dit is een gemakkelijkere manier om afzonderlijke of historische revisies te downloaden omdat de documentvoorbeeldpagina niet hoeft te worden geladen, zodat u een ander document in de tabel kunt selecteren en de revisies in het deelvenster aan de rechterkant kunt downloaden zonder een nieuwe voorbeeldpagina te openen.

**Openbare bundels** Gebruik [bundels](https://support.catenda.com/nl/articles/6344318-collectiespagina) om openbare koppelingen te maken voor geselecteerde documentsubsets, zodat externe partijen bestanden kunnen downloaden zonder een Catenda-account nodig te hebben. Houd er rekening mee dat alleen gepubliceerde revisies aan bundels kunnen worden toegevoegd.

**Verwijderde bestanden** Zoek naar "verwijderd" in de documentzoekbalk om eerder verwijderde documenten te zoeken en exporteren. Houd er rekening mee dat dit filter taalspecifiek is en overeenkomt met de term voor "verwijderd" in uw huidige taalinstellingen.

### 2.4 **Desktop Connector (geautomatiseerde lokale back-up)**

De [Catenda Desktop Connector](https://support.catenda.com/nl/articles/8358861-catenda-desktop-connector) maakt achtergrondynchronisatie mogelijk om periodiek nieuwe documentrevisies rechtstreeks naar een lokaal station te downloaden. In tegenstelling tot batchwebexports arriveren gedownloade documenten rechtstreeks op uw systeem als ongecomprimeerde bestanden zonder dat u handmatig archief hoeft uit te pakken.

**Geplande en instant back-ups** Taken kunnen zodanig worden gepland dat ze automatisch met regelmatige intervallen worden uitgevoerd of op aanvraag, zodat projectleden een actuele lokale kopie van documenten behouden, zelfs als projecttoegang onverwacht wordt ingetrokken.

**Directe API-overdrachten** Draagt grote gegevensverzamelingen aanzienlijk sneller over dan webbrowserdownloads door directe API-verbindingen zonder browserbeperkingen of overhead.

**Hiërarchieopties** Downloadt geselecteerde mappenstructuren met hun volledige hiërarchie intact, of extraheert afzonderlijk geselecteerde bestanden rechtstreeks als een platte lijst naar de aangewezen lokale map.

### 2.5 **Lidtoegang en activiteitenlogboeken**

**Topicborden** Documenteer boardtoegangsmachtigingen met behulp van twee beschikbare weergaven:

- **Per-gebruiker toegangsweergave**<br>Bekijk individuele toegangsniveaus van gebruikers rechtstreeks vanuit het informatief menu aan de rechterkant van een topic board of geselecteerde topic.<br>_Vereiste toegang:_ leesbevoegdheid voor de topic board
- **Volledige teamconfiguratie**<br>Maak schermafbeeldingen van de volledige teamwerkingsniveauinstellingen voor toestemmingen in de instellingen voor topic board-toegang.<br>_Vereiste toegang:_ Volledige toegang tot de topic board of projectbeheerder

**Document- en Modeltoegang** Exporteer het [toegangsoverzicht](https://support.catenda.com/nl/articles/6660820-pagina-document-toegangsoverzicht) om machtigingen voor leden en teams vast te leggen. Vereiste toegang: Projectbeheerder. Omdat elk model is gekoppeld aan een document in de documentensectie, worden toegangsmachtigingen voor modellen bepaald door de onderliggende documentmachtigingen en worden ze vastgelegd met behulp van hetzelfde documenttoegangsoverzicht of machtigingsmenu's.

**Document- en Modelrevisietoegang** Bekijk machtigingen vanuit het [deelvenster aan de rechterkant van een documentrevisie](https://support.catenda.com/nl/articles/8302244-rechtermenu-van-een-revisie-revisie-informatie) en maak indien nodig schermfoto's.

**Projectbrede actiemachtigingen** Documenteer projectbrede machtigingen op de [projectinstellingenpagina](https://support.catenda.com/nl/articles/4670273-pagina-met-projectinstellingen) (zoals het maken van topicborden, het uitnodigen van nieuwe leden, het configureren van documentstatussen en het maken of verwijderen van modellen) met behulp van twee beschikbare weergaven:

- **Weergave per gebruiker**<br>Projectleden kunnen elk menu onder toegangsbeheer uitvouwen om te zien welke individuele gebruikers toestemming hebben om elke actie uit te voeren.
- **Volledige configuratie**<br>Beheerders kunnen het dialoogvenster voor toegangbewerking openen om teamwerkingsniveaupermissieconfiguraties in te zien en te beheren.<br>_Vereiste toegang:_ Projectbeheerder

**Gebruikersprofielen en liddetails** Informatie over projectleden en teams is beschikbaar om te extraheren of te documenteren, inclusief:

- Gebruikersnamen en e-mailadressen (zie [aangepaste lidinformatie](https://www.google.com/search?q=https://support.catenda.com/nl/articles/11769670-aangepaste-lidgegevens)).
- Teamlidmaatschappen, toegewezen topics, geüploade modelrevisies en machtigingsinstellingen (vastgelegd via de [lidpagina](https://www.google.com/search?q=https://support.catenda.com/nl/articles/4670291-pagina-leden-en-teams) of [teampagina](https://www.google.com/search?q=https://support.catenda.com/nl/articles/4670291-pagina-leden-en-teams)).

### 2.6 **Meldingen**

Legfoto's van meldingspagina's vast vanuit de [projectmeldingenpagina](https://support.catenda.com/nl/articles/4670295-projectnotificatiepagina), met behulp van het [limietfilter](https://support.catenda.com/nl/articles/8304417-filteren-op-de-notificatiepagina) om het aantal zichtbare items per pagina te maximaliseren.

Configureer een speciaal beheerdersaccount met [projectspecifieke meldingsinstellingen](https://support.catenda.com/nl/articles/4670262-projectspecifieke-notificatie-instellingen) ingeschakeld voor e-mailoverzichten om doorzoekbare meldingslogboeken te onderhouden.

### 2.7 **Rapportenpagina (Opt-in-functie)**

De [rapportenpagina](https://support.catenda.com/nl/articles/12303098-rapportenpagina) is een opt-in-functie die voor lopende projecten kan worden aangevraagd. Projecten waarvoor deze functie is ingeschakeld, kunnen documentatie en Topics als geformatteerde rapporten exporteren, inclusief indelingen voor langdurige archivering.

**Op templates gebaseerd beheer** Wanneer dit is ingeschakeld, gebruiken projectbeheerders de [pagina met rapportsjablonen](https://support.catenda.com/nl/articles/12380837-pagina-met-rapportsjablonen) om hun eigen rapportsjablonen in te stellen en geformatteerde exports voor geselecteerde Documenten of Topics te genereren.

Wat kan worden geëxporteerd en in welke bestandsindelingen wordt beschreven in [Projectgegevens exporteren met rapporten](https://support.catenda.com/nl/articles/17779017-projectgegevens-exporteren-met-rapporten) _(alleen rapporteditor-klanten)_.

## 3. **Catenda Data Export**

Catenda Data Export wordt apart verkocht van Catenda Hub. In tegenstelling tot de bovenstaande downloads kopieert het automatisch projectgegevens rechtstreeks van Catenda Hub naar de eigen cloudopslag van een organisatie in Amazon S3 of Azure Blob Storage. Het is geschikt voor organisaties die een back-up willen die meegaat met hun projecten, of projectrecords die in hun eigen opslag worden bewaard. Het is niet alleen voor projecteigenaren. Een projecteigenaar kan een volledige back-up van zijn projecten exporteren, en een projectdeelnemer kan wat hij toegang tot heeft in de projecten waarin hij deelneemt exporteren. Meer informatie hierover vindt u in [Over Catenda Data Export](https://support.catenda.com/nl/articles/17779020-over-catenda-data-export) _(voor lezers die niet zijn aangemeld)_ en [Inleiding tot Catenda Data Export](https://support.catenda.com/nl/articles/17779027-inleiding-tot-catenda-data-export) _(alleen aangemelde klanten)_. Klanten die dit hebben, vinden de instelling in [Catenda Data Export](https://support.catenda.com/nl/articles/17779052-catenda-data-export) _(alleen Data Export-klanten)_.
