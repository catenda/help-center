# Naamgeving van revisies - Use Cases

> Verken praktijkvoorbeelden van revisienamen. Leer hoe teams ruimte en leesbaarheid in balans brengen met versiereeksen, statusmapping en compacte YYMMDD- of duidelijke YYYYMMDD-voorvoegsels voor chronologische documentsortering.

Wanneer u een naamgevingsconventie in een map inschakelt, passen projectteams vaak dynamische blokken aan om specifieke interne trackingworkflows aan te passen. Hieronder vindt u praktische voorbeelden van hoe verschillende teams aangepaste velden en de **Document identifier**-schakelaar gebruiken om een georganiseerde werkruimte te behouden.

## 1. **1. Projectrollen en implementatiestrategieën**

De invoering van naamgevingsconventies wordt doorgaans voortgestuwd door een mandaat van de projecteigenaar of door de wens van projectleden om een beter overzicht van hun bestanden te krijgen. Een gestructureerde naamgevingsconventie stelt teamleden in staat om efficiënter naar specifieke onderdelen van documentnamen te zoeken. Ongeacht wie de workflow initieert, moeten projectleden contact opnemen met een projectbeheerder om de naamgevingsconventie in te stellen en te activeren, omdat administratieve toegang vereist is om deze instellingen te wijzigen.

De reikwijdte van de implementatie hangt doorgaans af van wie erom vraagt:

### 1.1 **1.1 Mandaten van de projecteigenaar**

Wanneer een conventie door de projecteigenaar wordt vereist, wordt deze vaak project-wijd geïmplementeerd. In deze scenario's wordt vaak een afzonderlijke, aangewezen map ingesteld om documenten op te vangen die niet aan de strikte conventievereisten voldoen.

### 1.2 **1.2 Verzoeken van projectleden**

Wanneer een conventie door een persoon of specifieke subgroep wordt aangevraagd om een gelokaliseerde workflow te verbeteren, wordt deze doorgaans alleen ingeschakeld in hun specifieke werkmap, terwijl de rest van het projectteam zonder een conventie blijft werken.

## 2. **2. Versiereeks-workflows**

Versiereeksen worden gebruikt om opeenvolgende bestandsupdates bij te houden. Afhankelijk van de projectvereisten kiezen teams tussen uitbreidbare tracks met variabele lengte, starre strekstreepjes met opvulling of eenvoudige numerieke indicatoren.

### 2.1 Standaardversiereeks (`v1`, `v2`, `v3`)

**2.1.1 Het team** Liam (BIM Manager) en Sophia (Structural Engineer).

**2.1.2 De workflow** Sophia uploadt regelmatig bouwmodelbestanden naar het platform. Liam vereist dat alle inkomende modellen expliciet worden gemarkeerd met standaardversiereeksen zoals `v1`, `v2` of `v3`.

**2.1.3 Gedrag en overwegingen** Hoewel deze instelling in het begin eenvoudig is, kunnen versiesporen uitbreiden naar dubbele of driedubbele cijfers (bijv. `v10` of `v123`) naarmate het project vordert. Om deze groei aan te passen, wordt een tekstveld met een oneindige (variabele) lengte of een groter vaste lengte ingesteld.

Een belangrijk visueel aspect van deze aanpak is dat als het blok in het midden van de bestandsnaam staat, het toevoegen van een tweede of derde teken aan de reeks alle volgende naamblokken visueel over tekenposities verschuift. Om te voorkomen dat deze verschuivende versieetiketten tijdens elke upload volledig afzonderlijke documentcontainers creëren, moet de Document Identifier worden uitgeschakeld.

**2.1.4 De configuratie**

- **Bronveld:** Tekstaangepast veld.
- **Lengte:** Laat leeg voor variabele lengte of stel in op een groter vast getal.
- **Document Identifier:** Uit.

**2.1.5 Het resultaat** Wanneer Sophia bestanden uploadt met de naam `Structural_Model_v1.ifc` en `Structural_Model_v10.ifc`, herkent het platform de veranderende versiereeksen. De bestanden stapelen zich netjes als opeenvolgende revisies onder een enkele, statische documentcontainer met de naam `Structural_Model`.

### 2.2 Alfanumerieke strekstreepjereeks (`--`, `-a`, `-b`)

**2.2.1 Het team** Sarah (Lead Architect) en Tom (BIM Coördinator).

**2.2.2 De workflow** Sarah geeft architectonische tekeningen uit volgens een progressie waarbij de initiële release begint met een dubbel streepje (`--`), gevolgd door alfabetisch volgen (`-a`, `-b`) wanneer wijzigingen optreden. Ze werkt samen met Tom, die de mapindelingen beheert.

**2.2.3 Gedrag en overwegingen** In tegenstelling tot de standaardversiereeks behoudt deze instellingsstrekstreepje-opvulling exact dezelfde bloklengte. Wanneer een nieuw versieletter wordt geïntroduceerd, wordt een aanduidingsstreepje opgeofferd om uniforme tussenruimte te behouden.

Een primaire uitdaging met deze strategie is dat zodra alle aanduidingsstreepjes binnen de vooraf bepaalde lengte zijn uitgeput, de conventie wordt verbroken. Daarom wordt deze aanpak alleen aanbevolen wanneer er een duidelijk begrip is van de maximale revisielimiet voor de documenten.

**2.2.4 De configuratie:**

- **Bronveld**
  Tekstangepast veld geconfigureerd met een strikte, vaste lengte (bijv. 2 of 3 tekens) of een vervolgkeuzeangepast veld met de exact toegestane variaties.
- **Document Identifier:** Uit.
- **Het resultaat**
  Wanneer Sarah `FloorPlan_--.pdf` uploadt, gevolgd later door `FloorPlan_-a.pdf`, leest het platform de veranderende reeksetiketten voor validatie maar verwijdert ze bij het benoemen van het bestand in de werkruimte. Tom en het designteam zien een enkele documentcontainer met de naam `FloorPlan` waar historische variaties als revisies worden gestapeld zonder volgende tekens te verschuiven.

### 2.3 Eenvoudige numerieke volgreeks (`01`, `02`, `03`)

**2.3.1 Het team** David (Structural Draftsman) en Chloe (Lead Structural Engineer).

**2.3.2 De workflow** David werkt structurele detailtekeningen regelmatig bij en markeert ze numeriek op zijn lokale computer met behulp van opeenvolgende indicatoren zoals `01`, `02` en `03`. Chloe controleert deze details en vertrouwt op het platform om ervoor te zorgen dat David getallen invoert in plaats van onopzettelijke tekstletters.

**2.3.3 Gedrag en overwegingen** Er wordt een op gehele getallen gericht regelblok aan de mapstructuur toegevoegd om invoer te valideren. Opmerking: hoewel dit ervoor zorgt dat alleen numerieke invoer wordt gebruikt, accepteert het systeem elk geldig geheel getal in plaats van een strikte, stapsgewijze opeenvolgende telling.

**2.3.4 De configuratie**

- **Bronveld:** Geheel getal aangepast veld.
- **Document Identifier:** Uit.

**2.3.5 Het resultaat** Wanneer David `Steel_Detail_01.pdf` uploadt, bevestigt het integerveld dat het blok numerieke gegevens bevat en staat de upload toe. Als David een fout maakt en probeert een bestand met letters in dat blok te uploaden, weigert het systeem het bestand. Chloe kan de bestanden controleren omdat het platform elk geldig geheel getal accepteert en David niet dwingt in een strikte chronologische volgorde te tellen, wat garandeert dat de bestandsinformatiepaneel een schone numerieke tijdlijn bevat.

## 3. **3. Afkortingsstatus-mappingworkflows (`W`, `D`, `P`)**

**3.1 Het team** Elena (HVAC Engineer) en Marcus (Project Manager).

**3.2 De workflow:** Elena gebruikt een lokaal naamgevingssysteem waarin zij codes met één letter afkort toevoegt om de levenscyclusstatus van een tekening aan te geven: `W` voor Work in Progress, `D` voor Draft en `P` voor Published. Marcus, de Project Manager, moet de exacte status van haar technische werkbladen in één oogopslag weten, maar geeft de voorkeur aan volledige, beschrijvende woorden in plaats van afkortingen.

**3.3 Gedrag en overwegingen** Er wordt een vervolgkeuzeconfiguratie op de map toegepast om de kloof tussen lokale afkortingscodes en weergavetitels met platformmetagegevens te overbruggen.

**3.4 De configuratie:**

- **Bronveld:** Vervolgkeuzeangepast veld.
- **Installatieinstelling**
  De "Code" is ingesteld op overeenkomst met Elena's lokale bestandsnaammarkeringen (`W`, `D`, `P`), terwijl de "Naam" volledig is uitgeschreven als weergavewaarde (`Work in Progress`, `Draft`, `Published`).
- **Document Identifier:** Uit.

**3.5 Het resultaat** Wanneer Elena `HVAC_Layout_W.pdf` uploadt, past het systeem de code `W` aan en vult automatisch de metagegevensweergave in als `Work in Progress`. Wanneer Marcus het menu rechts informatie uitvouwt om het bestand te controleren, blijft de kerndocumentnaam een schone, statische `HVAC_Layout`, terwijl de sectie **Revisie-informatie** expliciet "Work in Progress" weergeeft.

## 4. **4. Numerieke datumTracking en chronologische sortering**

### 4.1 **4.1 Het team**

Oliver (Document Controller) en Emma (Site Manager).

### 4.2 **4.2 De workflow**

Oliver verwerkt dagelijkse locatierapporten en moet precies bijhouden wanneer elk rapport is gegenereerd. Emma, de Site Manager, heeft regelmatig toegang tot de documenttabel en vereist dat de bestanden zeer goed zijn georganiseerd. Omdat native datumblokken niet in naamgevingsconventies worden gebruikt, gebruiken Oliver en Emma numerieke aangepaste velden om datumreeksen in te voeren. Ze onderzoeken twee verschillende configuratievariaties afhankelijk van hoe ze willen dat de bestanden zich gedragen.

### 4.3 **4.3 Datum als revisiemarkering (Standaardvolgorde)**

In deze variant verandert de datum met elke nieuwe bestandsupload en vertegenwoordigt deze een nieuwe revisie van het dagelijks logboek. Oliver gebruikt twee cijfers voor de dag (`01`–`31`), twee cijfers voor de maand (`01`–`12`) en een twee-cijferig jaar (`26`, `27`) of een vier-cijferig jaar (`2026`, `2027`). Omdat een naamgevingsconventie slechts één primair scheidingsteken in alle blokken toestaat, vereist het beheren van een geïsoleerde datumindeling het kiezen tussen twee verschillende configuratiepaden:

**4.3.1 Drie afzonderlijke gehele getalblokken**

- **Structuur**
  Als een onderstrepingsteken (`_`) als primair scheidingsteken is ingesteld, kan het bestand als `Daily_Report_09_07_2026.pdf` worden opgemaakt.
  Dit maakt gebruik van drie afzonderlijke gehele getallen aangepaste velden: dag, maand en jaar.
- **Document Identifier-beperkingen**
  Als de Document Identifier voor deze drie blokken is **Ingeschakeld**, wordt de datum permanent als onderdeel van de documentnaam geïntegreerd.
  Dit creëert voor elke enkele revisie een afzonderlijke documentcontainer, en de datumwaarden blijven permanent omdat documentnamen in naamgevingsmapppen niet kunnen worden gewijzigd.
  Om de datumvelden toe te staan en bestanden als revisies onder een enkele statische documentnaam te stapelen, is het nodig om de Document Identifier **Uit** in te schakelen voor alle drie velden.

**4.3.2 Enkel tekstblok met interne scheidingstekens**

- **Structuur**
  Om het gebruik van meerdere conventieblokken te voorkomen, kan een alternatief teken (zoals een streepje) in een enkel tekstveldbock worden gebruikt, opgemaakt als `Daily_Report_09-07-2026.pdf`.
- **Validatiebeperkingen**
  Het is alleen mogelijk om de overkoepelende tekstreeks in een afzonderlijk blok te valideren. Daarom is het waarborgen dat de secundaire interne scheidingstekens correct worden geplaatst, volledig afhankelijk van handmatige gebruikersnauwkeurigheid tijdens de voorbereiding van het bestand.

### 4.4 Datum voor sortering (Jaar-maand-dagvolgorde)

In deze variant wil Emma dat de datum in de documentnaam zichtbaar blijft, zodat voor elke dag afzonderlijke bestanden bestaan. Bovendien vereist Emma dat de documenttabel de bestanden automatisch in perfecte chronologische volgorde sorteert. Lijsten op het platform worden alfanumeriek gesorteerd volgens Unicode-waarden. Als een datum als Dag-Maand-Jaar is geschreven, sorteert de lijst eerst op het dagnummer, waarbij alle bestanden van de "01"-dag van verschillende maanden samen worden gegroepeerd.

Om dit te voorkomen, plaatst Oliver eerst het jaar, gevolgd door de maand en vervolgens de dag. Wanneer u dit voorvoegsel beheert, moet u een evenwicht vinden tussen het sparen van karakterruimte en het waarborgen van onmiddellijke leesbaarheid, wat leidt tot twee implementatieopties:

**4.4.1 Voorvoegsel met twee-cijferig jaar (`YYMMDD`)** Deze optie verkort de sorteertekenreeks in een enkel blok om extra scheidingstekens te elimineren en reduceert het jaar tot twee gehele getallen (bijv. `26`, `27`, `28`). Dit bespaart karakterruimte en vermindert het risico dat lange documentnamen worden afgekapt of afgebroken aan het einde van de regel in de gebruikersinterface. Deze optie offert echter onmiddellijke leesbaarheid op.

Een datumreeks zoals `260126` kan gemakkelijk worden verkeerd begrepen, omdat niet onmiddellijk duidelijk is welke nummers het jaar vertegenwoordigen en welke de dag vertegenwoordigen. Een patroon wordt alleen herkenbaar na het bekijken van meerdere bestanden en het verschil wordt alleen duidelijk zodra een dag- of jaarwaarde meer dan 31 bedraagt.

**4.4.2 Voorvoegsel met vier-cijferig jaar (`YYYYMMDD`)** Deze optie gebruikt een volledig jaar met vier cijfers (bijv. `2026`, `2027`, `2028`) aan het begin van de naam. Deze configuratie verbetert de helderheid en onmiddellijke leesbaarheid aanzienlijk, waardoor de chronologische volgorde voor alle teamleden duidelijk wordt. Dit verbruikt echter meer karakterruimte aan het begin van de bestandsnaam, waardoor de waarschijnlijkheid toeneemt dat informatie aan het einde van lange documentnamen in de interface wordt afgekapt of afgebroken.

**4.4.3 Configuratie**

- **Bronveld**
  Een enkel geheel getal of tekstangepast veld aan het zeer begin van de naamgevingsconventie, opgemaakt in een strikte `YYMMDD`- of `YYYYMMDD`-reeks.
  Om de juiste uitlijning en goede alfanumerieke sortering te behouden, moeten voorloopnullen altijd worden gebruikt voor maanden of dagen met één cijfer (bijv. `01` voor januari).
- **Document Identifier:** Aan.

**4.4.4 Resultaat** Wanneer Oliver bestanden als `260115_Report.pdf` en `260201_Report.pdf` uploadt, worden afzonderlijke documenten gemaakt omdat de Document Identifier actief is. Omdat het jaar en de maand eerst komen en consistent dubbel-cijferige opvulling gebruiken, sorteert de documenttabel automatisch de bestanden in perfecte chronologische volgorde.
