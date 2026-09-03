# Implementatie van Toegangsbeheer - Gebruiksscenario's

Het structureren van een toegangsbeheersomgeving in Catenda Hub vereist afstemming van systeemmechanismen op specifieke projectrollen en samenwerkingsworkflows. Om overlappende regels schoon op te lossen, past het systeem een strikte hiërarchie toe: directe individuele overschrijvingen stellen een absoluut eindpunt vast, terwijl alle niet-overschreven paden combineren om het maximaal beschikbare toestemmingsniveau toe te kennen. De configuratiestrategieën hieronder tonen aan hoe u teambegrenzingen, individuele vergrendelingen en containerscopes kunt inzetten om echte beveiligings- en operationele vereisten in te vullen.

De volgende onderwerpen zijn in dit artikel beschreven:

## 1. **1. De Algemene Projectgemeenschap**

De volgende onderwerpen zijn in deze sectie beschreven:

### 1.1 **1.1 Geïsoleerde Onderaannemerswerkruimten**

**Wie** Een enkel gespecialiseerd onderaannemersTeam dat autonomie van binnenuit vereist.

**De Doelstelling** Het onderaannemersTeam moet totale vrijheid hebben om bestanden binnen hun toegewezen sectie te uploaden, wijzigen, organiseren en repareren. Collega's binnen dezelfde firma moeten elkaar's fouten kunnen corrigeren of mapstructuren vrijelijk kunnen reorganiseren, maar externe partijen moeten volledig worden geblokkeerd om onbedoeld verwijderen of ongeautoriseerde zichtbaarheid te voorkomen.

**De Configuratie** De globale **Alle Gebruikers** basislijn is ingesteld op **Geen Toegang**, terwijl de specifieke onderaannemer **Team-instelling** **Volledige Toegang** krijgt.

**De Scopestrategie** Deze strategie wordt gewoonlijk geïmplementeerd wanneer een project nieuw is. **Neerwaartse verspreiding** is ingeschakeld op de mappenstructuur op het hoogste niveau, zodat beheerders snel volledige interne autonomie kunnen doordrukken via het volledige submappenpad.

### 1.2 **1.2 Interdisciplinaire Samenwerkingsmappen**

**Wie** Meerdere ontwerpdisciplines (bijv. Architecten, Constructeurs, MEP) die in een gedeelde omgeving werken.

**De Doelstelling** Er moet een gedeelde werkruimte worden geboden waar verschillende Teams gelijktijdig modellen kunnen uploaden, ontwerpen kunnen coördineren en bestanden kunnen kruisverwijzen zonder beperkingen.

**De Configuratie** Deze omgeving kan op een van twee manieren worden ingesteld: ofwel wordt een toegewijd, gemengd "Interdisciplinair Team" gemaakt en krijgt **Schrijftoegang**, ofwel wordt elk individueel disciplineTeam (Architectuur Team, Constructie Team, enz.) expliciet aan de container toegevoegd met **Schrijftoegang**.

**De Scopestrategie** Omdat samenwerkingsvereisten regelmatig wijzigen in verschillende takken van een mappestructuur, richt dit gebruiksscenario zich op specifieke "blad"-mappen dieper in de hiërarchie. De scope is beperkt tot de **Alleen Directe Container**, zodat open samenwerkingsregels niet per ongeluk in andere beperkte zones doorsijpelen.

### 1.3 **1.3 Teamoverschrijding Zichtbaarheid en Auditing**

**Wie** Externe auditors, klantvertegenwoordigers of secundaire engineeringTeams.

**De Doelstelling** Een primair Team moet volledige controle of uploadrechten binnen een map behouden, maar een buitenstaand Team of belanghebbende moet actief voortgang controleren, Documenten beoordelen en precies zien wat er in real-time gebeurt zonder enig vermogen om de gegevens te wijzigen.

**De Configuratie** De primaire werkgroep krijgt **Volledige Toegang** of **Schrijftoegang**, terwijl de auditgroep of secundaire Team expliciet **Leestoegang** krijgt.

**De Scopestrategie** Deze configuratie maakt gebruik van **Alleen Directe Container** toewijzing op gelokaliseerde bladmappen. Hiermee kunnen belanghebbenden gerichte zichtbaarheid in voltooide werksecties krijgen, terwijl niet-goedgekeurde concepten in aangrenzende mappen volledig verborgen blijven.

## 2. **2. Onderaannemers en Externe Medewerkers**

De volgende onderwerpen zijn in deze sectie beschreven:

### 2.1 **2.1 Vloeiende Teamtoewijzingen voor Roulerend Personeel**

**Wie** Externe leveranciers en aannemingsbedrijven met hoge personeelsverloop.

**De Doelstelling** Toegang moet stabiel en veilig blijven, zelfs als personeel regelmatig het project in en uit gaat of zakelijke rollen verandert.

**De Configuratie** Toestemmingen worden uitsluitend toegewezen aan een **Team-instelling** (bijv. "Externe Reviewers") ingesteld op **Lees** of **Schrijf**. Er zijn geen individuele gebruikersverwerkingen geconfigureerd voor de Teamleden.

**De Scopestrategie** Om langetermijnonderhoud te garanderen, maakt deze configuratie gebruik van **Neerwaartse Verspreiding** in de mappen op het hoogste niveau. Wanneer een nieuwe medewerker zich bij het externe bedrijf voegt, worden zij eenvoudigweg aan de bestaande Teamstructuur toegevoegd en erven onmiddellijk de juiste toestemmingen over de gehele projecttak zonder handmatige aanpassingen per map.

### 2.2 **2.2 De Veilige Individuele Vergrendeling**

**Wie:** Veiligheidsconsultants met hoge prioriteit, externe auditors of beperkte externe medewerkers.

**De Doelstelling:** Omdat veiligheid en gegevensintegriteit van het allergrootste belang zijn, moet een beheerder met 100% zekerheid garanderen dat een specifieke gebruiker een vast toegangsniveau heeft. Dit niveau moet strikt worden vergrendeld, zodat de gebruiker niet per ongeluk verhoogde toestemmingen kan erven als deze per ongeluk aan een parallel projectTeam of samenwerkingsgroep wordt toegevoegd.

**De Configuratie:** Een expliciete **Instelling Voor Individuele Gebruiker** wordt rechtstreeks op het gebruikersaccount toegepast en ingesteld op het vereiste niveau (zoals **Lees** of **Geen Toegang**).

**De Scopestrategie:** Dit wordt toegepast als een gelokaliseerde vergrendeling op specifieke bladknooppunten met behulp van de instelling **Alleen Directe Container**. Omdat een individuele toewijzing de uiteindelijke uitzonderingsbevoegdheid in de systeemhiërarchie vertegenwoordigt, heeft dit voorrang op alle globale basislijnen, Teamlidmaatschappen en eigenaarsprivileges. Zelfs als de gebruiker per ongeluk Toegewezen aan een Team met Volledige Toegang elders, zorgt de individuele vergrendeling ervoor dat de toestemmingen precies zoals beoogd beperkt blijven.

## 3. **3. Item-eigenaren en Inhoudsmakers**

Catenda Hub wijst automatisch **Volledige Toegang** toe aan de maker van een map (of deze nu handmatig is gebouwd of automatisch geëxtraheerd via een geüpload ZIP-bestand), een topic board of een zojuist opgestelde Documentcontainer. Eigenaarschap is strikt van toepassing op de Documentcontainer zelf, wat betekent dat als een gebruiker een nieuwe revisie uploadt naar een Document dat door iemand anders is gemaakt, het originele containereigenaarschap onveranderd blijft.

De volgende onderwerpen zijn in deze sectie beschreven:

### 3.1 **3.1 Creatorsoevereiniteit en Gegevensprivacy**

**Wie** Interne auteurs en standaard inhoudsmedewerkers.

**De Doelstelling** Een gedeelde mapconfiguratie is vereist waar Teamleden algemene bestanden kunnen browsen, maar elke persoon die oorspronkelijk een Documentcontainer maakt, moet absolute controle behouden om deze bij te werken, van naam te veranderen of beheer ervan, zonder dezelfde destructieve beheersrechten aan de rest van het Team toe te kennen.

**De Configuratie** De globale **Alle Gebruikers** basislijn of Teamraamwerk is beperkt tot **Lees** of **Schrijf**, terwijl individuele gebruikersinstellingen volledig ongesteld blijven voor de medewerkers.

**De Logica:** Zonder een individuele overschrijving vervalt het systeem naar het hoogst erfde niveau. Regelmatige Teamleden zijn gebonden aan de standaardmapregels, maar zodra de oorspronkelijke auteur interactie aangaat met een Documentcontainer _die zij bezitten_, verheven hun ingebouwde eigenaarStatus hen tot Volledige Toegang.

### 3.2 **3.2 Geïsoleerde Persoonlijke Werkruimten**

**Wie** Specifieke Teamleiders, projectmanagers of interne auditors.

**De Doelstelling** Een strikt vertrouwelijke map of topic board moet worden ingesteld waar een manager concepten kan uploaden, gevoelige bestanden kan organiseren of interne aantekeningen kan maken in totale isolatie van de rest van de projectgemeenschap.

**De Configuratie** De doelcontainer wordt gemaakt en de globale **Alle Gebruikers** basislijn is expliciet ingesteld op **Geen Toegang**. Geen ander algemeen Teams krijgen toegang.

**De Logica** Omdat de basislijn en Teamroutes volledig zijn gesloten, zien standaardgebruikers niets. Omdat de maker van die map of board echter automatisch **Eigenaar Volledige Toegang** houdt, behouden zij volledige zichtbaarheid en administratieve controle over de ruimte, volledig geïsoleerd van standaardprojectleden terwijl Projectbeheerders toezicht op hoog niveau behouden.
