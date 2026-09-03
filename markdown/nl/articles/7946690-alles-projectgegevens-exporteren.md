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

**Geselecteerde modeldownload** Selecteer een of meer modellen op de [modelenpagina](https://support.catenda.com/en/articles/4670286-models-page) en gebruik de downloadactie om de nieuwste revisies uit te pakken.

**Afzonderlijke revisiedownload** Selecteer een model op de [modelenpagina](https://support.catenda.com/en/articles/4670286-models-page) en klik op de downloadknop naast elke revisie in het informatiedeelvenster aan de rechterkant. Dit biedt een efficiënte manier om specifieke revisies rechtstreeks te downloaden zonder dat u de volledige [modelinhoudsenpagina](https://support.catenda.com/en/articles/4670270-model-contents-page) hoeft in te laden. U kunt afzonderlijke revisies ook rechtstreeks downloaden van de inhoudspagina van een model.

**Geavanceerde modelexport** Open de [modelexportpagina](https://support.catenda.com/en/articles/4670280-model-export-page) om geselecteerde revisies van meerdere modellen in één downloadbare ZIP-bestand in te pakken. Deze methode bevat geavanceerde opties om de geëxporteerde modelbestanden te verbeteren door tags, door de gebruiker gedefinieerde eigenschappen of bibliotheekgegevens in te bakken.

### 2.2 **Topics exporteren (3 manieren)**

Topicgegevens kunnen in drie primaire formaten worden geëxtraheerd via [topics uitwisselen](https://support.catenda.com/en/articles/4670289-exchange-topics), afhankelijk van hoe de informatie zal worden bekeken, geanalyseerd of opgeslagen:

**BCF (BIM Collaboration Format)** Een open standaard die is ontworpen om topicgegevens vast te leggen en over te dragen, strikt in overeenstemming met de officiële BCF-specificatie, inclusief individuele topicaanmaaktijdstempels. Dit formaat garandeert brede platformonafhankelijke interoperabiliteit, wat ideaal is voor het opnieuw openen, bewerken of naadloos uitwisselen van topicgegevens met andere BCF-compatibele software. Voor algemene langetermijn-documentopslagruimten waar directe bestandsvoorbeelden nodig zijn, hebben PDF- of Excel-formaten meestal de voorkeur.

**Excel** Exporteert topicparameters naar een spreadsheetindeling voor filteren, sorteren en gegevensmanipulatie. Dit formaat biedt gestructureerde rijen en kolommen die ideaal zijn voor het selecteren en kopiëren van gegevens. Excel-bestanden kunnen eenvoudig worden bekeken in de meeste archiveringsplatforms. Voor archiveringsdoeleinden heeft de PDF-export meestal de voorkeur boven Excel omdat deze meer informatie bevat.

**PDF** Genereert een schoon, leesbaar samenvattingsrapport in standaard PDF-indeling (v1.4) die zonder speciale software toegankelijk is (zie [topics naar PDF exporteren](https://support.catenda.com/en/articles/9784934-exporting-topics-to-pdf)). Standaard PDF-exports bevatten een geconsolideerde downloadtijdstempel voor officiële overheidsrapportage en archivering, met meer informatie dan een Excel-export. Terwijl de basisexport een standaard PDF-bestand (v1.4) genereert, dat veel archiveringssystemen automatisch naar PDF/A omzetten bij upload voor langdurige voorbeelden, is directe export naar native PDF/A-1, PDF/A-2 en PDF/A-3-indeling ook beschikbaar via de opt-in [Rapportenpagina](https://support.catenda.com/en/articles/12303098-reports-page).

### 2.3 **Documenten en bundels exporteren**

**Batch- en mapmapdownloads** Selecteer afzonderlijke mappen, specifieke documentbatches of alle zichtbare tabelitems tegelijk om een downloadbaar ZIP-archief te genereren. Het wordt aanbevolen om in beheersbare batches te downloaden door specifieke submappen of gericht bestandsgroepen te selecteren voor soepele overdrachten wanneer u met grote gegevensverzamelingen werkt.

- **Tabblad Gepubliceerd**
  Extraeert de nieuwste gepubliceerde revisie voor elk geselecteerd document.
- **Tabblad Werkruimte**
  Extraeert de nieuwste gedeelde revisie voor elk geselecteerd document (vereist de machtiging "Gedeelde revisies weergeven"). Houd er rekening mee dat oudere conceptrevisies niet in een ZIP-archief kunnen worden gedownload in batch, maar afzonderlijk worden gedownload.

**Afzonderlijke revisiedownload** Selecteer een document op de [documentenpagina](https://support.catenda.com/en/articles/8204673-documents-page) en klik op de downloadknop naast elke revisie in het informatiedeelvenster aan de rechterkant. Dit is een gemakkelijkere manier om afzonderlijke of historische revisies te downloaden omdat de documentvoorbeeldpagina niet hoeft te worden geladen, zodat u een ander document in de tabel kunt selecteren en de revisies in het deelvenster aan de rechterkant kunt downloaden zonder een nieuwe voorbeeldpagina te openen.

**Openbare bundels** Gebruik [bundels](https://support.catenda.com/en/articles/6344318-collections-page) om openbare koppelingen te maken voor geselecteerde documentsubsets, zodat externe partijen bestanden kunnen downloaden zonder een Catenda-account nodig te hebben. Houd er rekening mee dat alleen gepubliceerde revisies aan bundels kunnen worden toegevoegd.

**Verwijderde bestanden** Zoek naar "verwijderd" in de documentzoekbalk om eerder verwijderde documenten te zoeken en exporteren. Houd er rekening mee dat dit filter taalspecifiek is en overeenkomt met de term voor "verwijderd" in uw huidige taalinstellingen.

### 2.4 **Desktop Connector (geautomatiseerde lokale back-up)**

De [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) maakt achtergrondynchronisatie mogelijk om periodiek nieuwe documentrevisies rechtstreeks naar een lokaal station te downloaden. In tegenstelling tot batchwebexports arriveren gedownloade documenten rechtstreeks op uw systeem als ongecomprimeerde bestanden zonder dat u handmatig archief hoeft uit te pakken.

**Geplande en instant back-ups** Taken kunnen zodanig worden gepland dat ze automatisch met regelmatige intervallen worden uitgevoerd of op aanvraag, zodat projectleden een actuele lokale kopie van documenten behouden, zelfs als projecttoegang onverwacht wordt ingetrokken.

**Directe API-overdrachten** Draagt grote gegevensverzamelingen aanzienlijk sneller over dan webbrowserdownloads door directe API-verbindingen zonder browserbeperkingen of overhead.

**Hiërarchieopties** Downloadt geselecteerde mappenstructuren met hun volledige hiërarchie intact, of extraheert afzonderlijk geselecteerde bestanden rechtstreeks als een platte lijst naar de aangewezen lokale map.

### 2.5 **Lidtoegang en activiteitenlogboeken**

**Topicborden** Documenteer boardtoegangsmachtigingen met behulp van twee beschikbare weergaven:

- **Weergave per gebruiker**
  Bekijk afzonderlijke gebruikerstoegangsniveaus rechtstreeks vanuit het informatiedeelvenster aan de rechterkant van een topicbord of geselecteerd topic.
  ​_Vereiste toegang:_ leestoegang tot het topicbord
- **Volledige teamconfiguratie**
  Legfoto's van de volledige teamniveaumachtigingsinstellingen binnen de topicboardtoegangsinstellingen vast.
  ​_Vereiste toegang:_ Volledige toegang tot het topicbord of projectbeheerder

**Document- en Modeltoegang** Exporteer het [toegangsoverzicht](https://support.catenda.com/en/articles/6660820-document-access-overview-page) om machtigingen voor leden en teams vast te leggen. Vereiste toegang: Projectbeheerder. Omdat elk model is gekoppeld aan een document in de documentensectie, worden toegangsmachtigingen voor modellen bepaald door de onderliggende documentmachtigingen en worden ze vastgelegd met behulp van hetzelfde documenttoegangsoverzicht of machtigingsmenu's.

**Document- en Modelrevisietoegang** Bekijk machtigingen vanuit het [deelvenster aan de rechterkant van een documentrevisie](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision-revision-info) en maak indien nodig schermfoto's.

**Projectbrede actiemachtigingen** Documenteer projectbrede machtigingen op de [projectinstellingenpagina](https://support.catenda.com/en/articles/4670273-project-settings-page) (zoals het maken van topicborden, het uitnodigen van nieuwe leden, het configureren van documentstatussen en het maken of verwijderen van modellen) met behulp van twee beschikbare weergaven:

- **Weergave per gebruiker**
  Projectleden kunnen elk menu onder toegangsbeheer uitvouwen om te zien welke afzonderlijke gebruikers toestemming hebben om elke actie uit te voeren.
- **Volledige configuratie**
  Beheerders kunnen het bewerkingtoegangsdialoogvenster openen om teamniveaumachtigingsconfiguraties weer te geven en te beheren.
  ​_Vereiste toegang:_ Projectbeheerder

**Gebruikersprofielen en liddetails** Informatie over projectleden en teams is beschikbaar om te extraheren of te documenteren, inclusief:

- Gebruikersnamen en e-mailadressen (zie [aangepaste lidinformatie](https://www.google.com/search?q=https://support.catenda.com/en/articles/11769670-custom-member-information%23h_c15463ee3f)).
- Teamlidmaatschappen, toegewezen topics, geüploade modelrevisies en machtigingsinstellingen (vastgelegd via de [lidpagina](https://www.google.com/search?q=https://support.catenda.com/en/articles/4670291-members-page) of [teampagina](https://www.google.com/search?q=https://support.catenda.com/en/articles/4670291-members-page)).

### 2.6 **Meldingen**

Legfoto's van meldingspagina's vast vanuit de [projectmeldingenpagina](https://support.catenda.com/en/articles/4670295-project-notifications-page), met behulp van het [limietfilter](https://support.catenda.com/en/articles/8304417-filtering-on-the-notifications-page) om het aantal zichtbare items per pagina te maximaliseren.

Configureer een speciaal beheerdersaccount met [projectspecifieke meldingsinstellingen](https://support.catenda.com/en/articles/4670262-project-specific-notification-settings) ingeschakeld voor e-mailoverzichten om doorzoekbare meldingslogboeken te onderhouden.

### 2.7 **Rapportenpagina (Opt-in-functie)**

**Opt-in-activering** De rapportenpagina is een opt-in-functie die kan worden aangevraagd om voor lopende projecten in te schakelen. Hoewel er geen extra betaling nodig is om dit hulpmiddel te gebruiken, moet de projecteigenaar ermee instemmen dat dit op het project wordt ingeschakeld. Dit betekent dat het in veel projecten niet standaard actief is. Houd er rekening mee dat nieuwe projecten die zijn gemaakt op basis van sjabloonprojecten waarop rapporten zijn ingeschakeld, deze functie niet automatisch hebben ingeschakeld.

**Op sjablonen gebaseerd beheer** Wanneer dit is ingeschakeld, kunnen projectbeheerders de [rapportsjabloonenpagina](https://support.catenda.com/en/articles/12380837-report-templates-page) gebruiken om aangepaste rapportsjablonen te configureren en geformatteerde exports voor geselecteerde documenten of topics te genereren.

**Documentrapporten** Exporteer documentmetagegevens en revisiedetails voor alle geselecteerde bestanden, inclusief documentnaam, revisienaam, meest recente revisienummer, status, aangepaste velden, maker, uploader en aanmaak-/uploadtijdstempels.

- **Belangrijkste toepassingen**
  Ideaal voor het genereren van formele documentleverings-checklists bij een bundel of het compileren van gestructureerde documentlijsten voor gegevensanalyse.
- **Modelmetagegevens en attributen**
  Hoewel de werkelijke documentbestandsinhoud niet is opgenomen, kunnen modelmetagegevens via documentrapporten worden geëxporteerd, aangezien modellen koppelingen naar de documentensectie behouden. Aangepaste scripts in sjablonen kunnen ook worden gebruikt om aanvullende attributen af te leiden, zoals het extraheren van bestandstypen uit documentnamen.

**Topicrapporten** Exporteer de algehele topicheaders en volledige topiclichaamdetails, inclusief beschrijvingen, opmerkingen en ingesloten opmerkingsafbeeldingen.

**Beschikbare exportindelingen** Rapporten die op basis van een sjabloon zijn gemaakt, kunnen afhankelijk van uw werkstroomvereisten naar meerdere indeling worden geëxporteerd:

- **PDF / PDF/A**
  Genereert schone opgemaakte rapporten en ondersteunt rechtstreeks native PDF/A-compatibiliteit (PDF/A-1, PDF/A-2 en PDF/A-3) om te voldoen aan strikte langetermijnarchiverings- en formele juridische normen.
- **Excel**
  Exporteert gestructureerde tabellarische gegevens naar spreadsheetrijen en kolommen, wat ideaal is voor gegevensmanipulatie en externe analyse.
- **Aanvullende indelingen**
  Een breed scala aan aanvullende bestandsindelingen naast PDF en Excel wordt ook ondersteund voor export. Het volledige overzicht vindt u in het [rapportenpagina](https://support.catenda.com/en/articles/12303098-reports-page)-artikel.

**Gecentraliseerde opslag** Gegenereerde rapporten staan rechtstreeks in de rapportentabel en worden automatisch geïntegreerd in de hoofddocumenttabel voor eenvoudig beheer.

## 3. **Catenda Data Export**

In tegenstelling tot standaard door gebruikers gestuurde downloads is Catenda Data Export een geautomatiseerde selfserviceoplossing die is ontworpen om projectgegevens naadloos rechtstreeks in de cloudopslag van een organisatie over te dragen. Als uw organisatie geïnteresseerd is in het inschakelen van deze functie, kunt u contact opnemen met de afdeling Verkoop op [sales@catenda.com](mailto:sales@catenda.com). Nadat dit is ingeschakeld, worden geautomatiseerde back-ups rechtstreeks tussen cloudomgevingen zonder aangepaste scripts, door browserwerkgeheugenbeperkingen, lokale stationsopslagbeperkingen en netwerkonderbrekingen te omzeilen via geautomatiseerde checksumverificatie.

### 3.1 **Organisatierollen en machtigingen**

Het instellen en beheren van Catenda Data Export vereist een **Organisatiebeheerder**. In tegenstelling tot een Organisatie-eigenaar, wiens beheersrechten beperkt zijn tot één organisatie, of standaard projectleden, heeft een Organisatiebeheerder verhoogde toegang in alle organisaties die tot een overkoepelend account behoren. Deze unieke rol biedt de vereiste zichtbaarheid en bevoegdheid op het niveau van meerdere organisaties om geautomatiseerde cloudexports in te stellen en te beheren.

### 3.2 **Configuratiestappen**

Het instellen van geautomatiseerde gegevensexports omvat vier belangrijkste stappen:

1. **Bestemming selecteren**
   Kies een cloudopslagprovider, Amazon Web Services (AWS) S3 of Microsoft Azure Blob-opslag, en configureer verificatie.
1. **Bereik en gegevensindelingen definiëren**
   - **Gegevenstypen**
     Exporteer documenten, modellen en topics.
     Topicgegevens kunnen tijdens overdracht automatisch worden geconverteerd naar leesbare PDF-samenvattingsrapporten of standaard BCF-bestanden.
   - **Projectselectie**
     Kies alle projecten, selecteer handmatig specifieke projecten, of stel dynamische overeenkomstingsregels in met projectnaampatronen (glob of reguliere expressie/regex) om automatisch nieuwe projecten op te nemen wanneer ze worden gemaakt.
1. **Exportmodus selecteren**
   - **Doorlopende modus**
     Verzendt gegevens automatisch op basis van een dagelijks schema.
     Deze herhaalde instellingen zorgen ervoor dat niet-eigenaar projectleden tot en met de laatste dagelijkse run een bijgewerkte back-up behouden als projecttoegang onverwacht afloopt.
   - **Snapshot-modus**
     Voert een eenmalige run uit om een volledige gegevensverzameling op een specifiek moment of projectoverdracht te exporteren.
1. **Implementeren**
   Voltooi en schakel de exportconfiguratie in door Maken te selecteren.

### 3.3 **Geëxtraheerde inhoud en Integriteitsverificatie**

**Metagegevens en Aangepaste velden** Aangepaste velden die aan documenten en topics zijn gekoppeld, worden naast primaire bestanden als gestructureerde JSON-bestanden geëxporteerd, zodat volledige kenmerkbehoud zonder handmatige rapportgeneratie wordt gegarandeerd.

**Integriteitsverificatie** Bij elke exportrun wordt een checksumbestand gegenereerd om te controleren of geëxporteerde bestanden overeenkomen met de brongegevens in Catenda Hub en volledig zonder netwerkuitval zijn overgedragen.

**Georganiseerde Hiërarchie** Geëxporteerde bestanden worden automatisch in mappen ingedeeld op datum, projectnaam en de exacte maphiërarchie die in Catenda Hub wordt onderhouden.
