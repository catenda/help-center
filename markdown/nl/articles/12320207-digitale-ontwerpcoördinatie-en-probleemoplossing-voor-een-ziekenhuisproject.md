# Digitale ontwerpcoördinatie en probleemoplossing voor een ziekenhuisproject

> Branche: Ziekenhuisbouw / BIM (Building Information Modeling) Persona: David, BIM-coördinator voor een grote aannemersbedrijf.

**Scenario:** David beheert het digitale bouwmodel voor een nieuwe ziekenhuisvleugel. Dit is een zeer complex project met tientallen gespecialiseerde teams. De architectonische, constructieve en MEP-modellen (Mechanisch, Elektrisch, Loodgieterswerk) worden constant bijgewerkt door verschillende ingenieursbureaus. Davids primaire verantwoordelijkheid is het integreren (combineren) van deze modellen in Catenda Hub om clashes te identificeren en op te lossen _voordat_ ze dure problemen op de bouwplaats worden.

Tijdens zijn wekelijkse coördinatiecontrole moet hij een potentieel kritiek probleem onderzoeken dat door de locatiemanager is gemarkeerd: de ondersteuningsstructuur voor een grote MRI-machine op de tweede verdieping komt mogelijk niet overeen met de meest recente architectonische en elektrische plannen.

**Oplossing met Catenda Hub:** David gebruikt een nauwkeurige workflow in Catenda Hub om deze complexe coördinatietaak efficiënt te beheren.

### **1. De gegevens centraliseren op de pagina 'Modellen':**

Eerst navigeert David naar de **pagina Modellen**. Hier kan hij alle meest recente IFC-modellen zien die door verschillende teams zijn geüpload, elk met hun revisienummer en status. Hij selecteert de relevante modellen voor het betrokken gebied:

- ARCH-Hospital-Wing-rev04.ifc
- STRUCT-MRI-Support-rev02.ifc
- MEP-Elec-Room204-rev05.ifc

Hij opent alle drie in de gefedereerde **3D-viewer**. Het platform combineert ze in één navigeerbaar digitaal model van dat deel van het ziekenhuis.

### **2. De clash identificeren en een 'opgeslagen view' maken:**

Terwijl David door het 3D-model navigeert, ziet hij het probleem onmiddellijk. De staalconstructies voor de MRI-machine dringen door in een muur waar de architecten nu een belangrijk elektrisch schakelbordkamer hebben geplaatst. Bovendien is de doorvoering in de vloer voor de koelbuizen van de machine in conflict met een nieuw gelegde kabelgoot. Om dit complexe, meertalige probleem duidelijk te communiceren, volstaat een eenvoudige schermafbeelding niet. In plaats daarvan gebruikt David de functie **Opgeslagen views**:

- Hij isoleert alleen de elementen die in clash zijn: de staalconstructies, de specifieke muur, het schakelboard en de kabelgoot.
- Hij gebruikt een dwarsdoorsnede om een duidelijk, ongehinderd zicht op het botsingspunt te creëren.
- Hij slaat deze precieze status op—inclusief de camerahoek, objectzichtbaarheid en dwarsdoorsnede—als een opgeslagen view met de titel "**Clash: MRI Support vs. Elec Room 204**".

### **3. Een issue maken en toewijzen:**

Met de opgeslagen view gemaakt, maakt David een **Issue** (of "Onderwerp" in Catenda Hub). In de probleembeschrijving schrijft hij: "@Architecten, @Constructie, @MEP - We hebben een kritieke clash tussen de ondersteuningsstructuur van de MRI en de herziene indeling van de elektriciteitsruimte. De bijgevoegde opgeslagen view toont de exacte locatie en betrokken elementen. Constructie moet bevestigen of de ondersteuningen kunnen worden verplaatst, en MEP moet een nieuwe route voor de kabelgoot verifiëren. Geef alstublieft voor vrijdag einde werkdag een oplossing." Hij linkt het issue rechtstreeks aan de zojuist gemaakte opgeslagen view.

### **4. Collaboratieve oplossing aansturen:**

De leidinggevende architect, constructeur en MEP-coördinator ontvangen onmiddellijk een melding. Wanneer zij op de link in het issue klikken, opent Catenda Hub het 3D-model en brengt hen naar de **exacte weergave die David in de opgeslagen view heeft vastgelegd**. Er is geen dubbelzinnigheid en geen tijd verloren aan het zoeken naar het probleem. Ze gebruiken het opmerkingsveld van het issue om oplossingen te bespreken. De architect bevestigt dat de positie van de elektriciteitsruimte vast staat. De constructeur voert snel een analyse uit en stelt een herzien ontwerp voor, voegt een schets bij. De MEP-coördinator bevestigt dat zij de kabelgoot kunnen omleiden.

### **Resultaten en voordelen:**

Door de pagina's Modellen en Opgeslagen views in te zetten, transformeerde David een potentieel chaotisch en kostbaar probleem in een gestructureerd, traceerbaar en snel opgelost issue.

- **Absolute helderheid:** De opgeslagen view bood een "single source of truth" voor het probleem, waardoor misverstanden die uit e-mails of telefoongesprekken zouden kunnen ontstaan, werden voorkomen.
- **Aanzienlijke tijdbesparing:** De projectbetrokkenen losten het probleem in enkele uren digitale samenwerking op, wat dagen of zelfs weken bespaard in vergelijking met traditionele methoden van bestandsuitwisseling heen en weer.
- **Kostenbesparing:** Het digitaal identificeren van deze clash voorkomt de massale kosten van sloopwerk ter plaatse, herwerk en projectvertragingen die zouden optreden als het staal op de verkeerde plaats zou zijn geplaatst.

### **Verbeterde verantwoording:**

Het gehele proces van ontdekking, communicatie en oplossing is gedocumenteerd in één issue, wat een duidelijk audittrail voor het projectverslag oplevert.
