# Goedkeuringswerkstromen: Beheersregels

> Handleiding voor beheerders met details over instellingsregels, flexibele configuratieopties, vergrendeling van parameters na indiening en de impact van projectconfiguratiewijzigingen op actieve goedkeuringsaanvragen.

Goedkeuringswerkstromen stellen gestructureerde controle- en validatieprocessen in voor gedeelde documentversies binnen een project. Het configureren van werkstromen vereist het balanceren van sjabloonregels voor toekomstige controleaanvragen met instellingen van het projectteam die actieve, voortdurende goedkeuringen aansturen.

> **Opmerking:** Alleen projectbeheerders kunnen werkstroominstellingen openen, nieuwe goedkeuringswerkstromen maken of bestaande werkstroomparameters wijzigen.

## 1. **1. Hoe projectwijzigingen goedkeuringswerkstromen beïnvloeden**

Wanneer een werkstroomsjabloon wordt gewijzigd of projectconfiguraties worden aangepast (zoals het toevoegen of verwijderen van teamleden in projectinstellingen), beïnvloeden de wijzigingen toekomstige en actieve goedkeuringsaanvragen op verschillende manieren:

### 1.1 **1.1 Bewerkingen van werkstroomsjabloon**

Wijzigingen in een werkstroomsjabloon (zoals het toevoegen van indienerteams) zijn van toepassing op **toekomstige** goedkeuringsaanvragen die na de update worden gemaakt. Ze herschrijven niet de structuur van actieve aanvragen die al in uitvoering zijn.

### 1.2 **1.2 Updates van teamlidmaatschap**

Het toevoegen of verwijderen van teamleden in projectinstellingen wordt onmiddellijk van kracht op **actieve, voortdurende** goedkeuringen. Als een controlestap vastloopt omdat een team leeg is, kunt u een gebruiker aan dat team toevoegen zodat hij onmiddellijk kan ingrijpen en de controle kan hervatten.

### 1.3 **1.3 Verbroken afhankelijkheden**

Het archiveren van een documentstatus, het verwijderen van een team of het archiveren van een goedkeuringsonderwerpsabloon elders in projectinstellingen kan validatiefouten veroorzaken bij het opslaan van werkstroomupdates of kan het maken van onderwerp op actieve goedkeuringen stoppen.

## 2. **Pre-indieningsinstellingen (initiële aanmaak)**

Wanneer een nieuwe goedkeuringswerkstroom voor het eerst wordt gemaakt, moeten alle fundamentele parameters worden geconfigureerd voordat de sjabloon kan worden opgeslagen en geactiveerd.

### 2.1 **2.1 Verplichte velden en pre-indiening waarschuwingsbanner**

Als een verplicht veld niet is ingevuld bij het opslaan van een nieuwe werkstroom, toont het systeem een pre-indieningswaarschuwingsbanner bovenaan de pagina en blokkeert het sjabloon aanmaken. Verplichte velden zijn onder meer:

- **2.1.1 Werkstroomtitel**
  Een unieke, beschrijvende naam voor de werkstroom.
- **2.1.2 Indienerteams**
  Minstens één projectteam dat is ingesteld voor het starten van goedkeuringsaanvragen.
- **2.1.3 Controlestappen**
  Minstens één controlestap met een toegewezen controleringsteam en een duur van minimaal **1 werkdag**.
- **2.1.4 Uiteindelijke goedkeuring**
  Een toegewezen eindbeoordelingsteam samen met twee actieve projectdocumentstatussen—één voor goedgekeurde versies en één voor afgewezen versies.

### 2.2 **2.2 Systeemlimieten en teamlidmaatschapsregels**

**2.2.1 Pipelinelimieten** Een enkele werkstroom ondersteunt tot **10 opeenvolgende controlestappen** en in totaal **20 controleringsteams** in de pijplijn.

**2.2.2 Teamkeuze versus aanwezigheid van leden** Tijdens de initiële aanmaak controleert het systeem of indiener-, controle- en eindbeoordelingsteams zijn geselecteerd. Het controleert echter **niet** of deze teams daadwerkelijke leden bevatten.

**2.2.3 Uitvoeringsvereisten en automatische goedkeuring** Om een goedkeuringsaanvraag van begin tot eind compleet te maken:

- Minstens één lid van het indienerteam moet aanwezig zijn in een toegewezen indienerteam om de aanvraag in te dienen.
- Minstens één lid van het beoordelingsteam moet aanwezig zijn in een toegewezen beoordelingsteam, tenzij automatische goedkeuring is ingeschakeld voor die stap.
- Als automatische goedkeuring is geconfigureerd, keurt een aan een leeg team toegewezen stap automatisch goed en gaat verder zodra de staptermijn is bereikt.
- Als automatische goedkeuring niet is geconfigureerd, wordt een lege beoordelingsteam de goedkeuringsaanvraag blokkeren totdat een lid aan dat team wordt toegevoegd.
- Minstens één lid van het eindbeoordelingsteam moet aanwezig zijn om het eindresultaat te bepalen.

**2.2.4 Beheerdersrechten** Projectbeheerders hebben geen automatische operationele rechten. Om acties uit te voeren tijdens een goedkeuring, moet een beheerder een expliciet lid van het relevante team zijn:

- **Indienerteam**
  Vereist om een goedkeuringsaanvraag in te dienen.
- **Beoordelingsteam**
  Vereist om een controlevalidatie aan te geven of in te dienen.
- **Eindbeoordelingsteam**
  Vereist om de uiteindelijke beslissing te bepalen en de goedkeuring af te ronden.

## 3. **3.** **Flexibele bewerkingen (pre- en na-indiening)**

Bepaalde bewerkingen blijven flexibel en kunnen worden aangepast tijdens de initiële instellingen of op elk moment nadat een werkstroom actief is. Deze flexibele bewerkingen vallen in twee verschillende categorieën: **Werkstroomsjablooninstellingen** (direct bewerkt op de werkstroomsetuppagina) **Beheer van projectteamleden** (bewerkt op de pagina Projectteams voor alle werkstroomrollen).

### 3.1 **3.1** **Wijzigingen in werkstroomsjabloon**

Deze instellingen kunnen op elk moment binnen het werkstroomconfiguratiemenu worden gewijzigd en beïnvloeden rechtstreeks toekomstige goedkeuringsaanvragen:

**3.1.1 Indienerteams** Beheerders kunnen indienerteams na indiening toevoegen of verwijderen om te controleren welke projectteams mogen starten met nieuwe goedkeuringsaanvragen onder deze werkstroom.

**3.1.2 Goedkeuringsonderwerpssjablonen** Goedkeuringsonderwerpssjablonen die aan specifieke resultaten zijn gekoppeld (_Goedgekeurd_, _Goedgekeurd met opmerkingen_ of _Afgewezen_) kunnen op elk moment worden toegevoegd, bijgewerkt of ontkoppeld om het volgen van problemen tijdens beoordelingen te controleren.

### 3.2 **3.2** **Beheer van projectteamleden (van toepassing op alle teamtypen)**

Het toevoegen of verwijderen van afzonderlijke gebruikers vindt plaats op de pagina **Projectteams** en vereist geen bewerking of opnieuw opslaan van de werkstroomsjabloon. Belangrijk is dat ledenbeheering van toepassing is op **alle drie werkstroomteamtypen** en rechtstreeks beïnvloedt wie acties kan uitvoeren:

**3.2.1 Indienerteams** Het toevoegen of verwijderen van leden bepaalt wie de werkstroom kan selecteren om nieuwe goedkeuringsaanvragen in te dienen.

**3.2.2 Beoordelingsteams** Het toevoegen of verwijderen van leden bepaalt wie toegang heeft tot actieve controlestappen, opmaak/opmerkingen kan toevoegen en stapvalidatieaanduidingen kan indienen.

**3.2.3 Eindbeoordelingsteams** Het toevoegen of verwijderen van leden bepaalt wie de uiteindelijke beslissing kan bepalen en een actieve goedkeuringsaanvraag kan afronden.

## 4. **4.** **Regels na indiening en parametervergrendeling**

Zodra een werkstroomsjabloon voor het eerst wordt opgeslagen en ingediend, worden sleutelstructurele parameters vergrendeld om consistente evaluatieregels voor goedkeuringsaanvragen te waarborgen.

### 4.1 **4.1 Vergrendelde versus bewerkbare parameters**

**4.1.1 Vergrendelde parameters** Tijdinstellingen, controlestappen, toegewezen beoordelingsteams, stapduren, automatische goedkeuringswissels, eindgoedkeuringsteams en toegewezen eindige documentstatussen kunnen niet worden gewijzigd na de eerste indiening.

**4.1.2 Bewerkbare parameters** Alleen de werkstroomtitel, toewijzingen van indienerteams en gekoppelde goedkeuringsonderwerpssjablonen blijven na indiening bewerkbaar.

### 4.2 **4.2 Verbroken externe afhankelijkheden en resoluties**

Het opslaan van **elke** bewerking na indiening naar een bestaande werkstroom (zoals het bijwerken van de titel) triggert een volledige hervalidatiecontrole op de gehele sjabloon. Als een element dat in de werkstroom wordt gebruikt, na de initiële aanmaak in projectinstellingen is gearchiveerd of verwijderd, mislukt hervalidatie totdat dit is opgelost.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 130px; padding: 8px;"><h3 id="h_5956ae53a6"><b>Afhankelijkheidskwestie (blokker)</b></h3></td><td style="background-color: #e3e7fa80; width: 244px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_9b11612daf"><b>Impact en systeemgedrag</b></h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_f245fc1acb"><b>Resolutie</b></h3></td></tr><tr><td style="background-color: #00000000; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_aac48f326c"><b>Gearchiveerde documentstatussen</b></h3></td><td style="background-color: #00000000; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Het toegewezen statusveld lijkt leeg in werkstroominstellingen. Gepubliceerde documenten ontvangen de gearchiveerde status (weergegeven als doorgehaald). Werkstroomupdates zijn geblokkeerd.</p></td><td style="background-color: #00000000; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>De status herstellen (uit archief halen)</b> in documentinstellingen.<br/>Vergrendelde statussen kunnen niet worden bewerkt of vervangen in de werkstroom na indiening.</p></td></tr><tr><td style="background-color: #e8e8e880; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_c963d16fb5"><b>Verwijderde projectteams</b></h3></td><td style="background-color: #e8e8e880; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Een indiener-, beoordelings- of eindgoedkeuringsteam is verwijderd op de pagina projectteams.</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Indienerteams</b><br/>Bewerk de werkstroom rechtstreeks om een nieuw actief team toe te wijzen.<br/>​</p><p><b>Beoordelings-/eindteams</b><br/>Vergrendeld. Als er geen teams in een stap achterblijven en automatische goedkeuring is uitgeschakeld, blijven actieve goedkeuringen voor altijd staan. Archiveer de werkstroom, verwijder documenten en maak een nieuwe werkstroom.</p></td></tr><tr><td style="background-color: #00000000; width: 130px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_8d948d5649"><b>Gearchiveerde goedkeuringsonderwerpssjablonen</b></h3></td><td style="background-color: #00000000; width: 244px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Een goedkeuringsonderwerpssjabloon die aan een werkstroom-uitkomst is gekoppeld, is gearchiveerd op de pagina onderwerpssjablonen.</p><p></p></td><td style="background-color: #00000000; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Herstel (uit archief halen)</b> de sjabloon op de pagina onderwerpssjablonen <b>OF</b> bewerk de werkstroom rechtstreeks om een nieuw actief vervangend sjabloon te selecteren/toevoegen.</p></td></tr></tbody></table></div>

### 4.3 **4.3 Werkstromen archiveren en herstellen**

**4.3.1 Werkstromen archiveren** Verbergt de actieve werkstroom uit creatiemenu's, zodat projectleden deze niet kunnen selecteren voor nieuwe aanvragen.

**4.3.2 Werkstromen herstellen** Herauwer een gearchiveerde werkstroom in creatiemenu's voor toegewezen indienerteams.

## 5. **5.** **Impact op actieve goedkeuringen en teamlevenscycli**

Wanneer projectinstellingen of teamlidmaatschappen veranderen terwijl goedkeuringsaanvragen actief in uitvoering zijn, worden toegang, onderwerpscreatie en werkstroomprogress door het systeem volgens specifieke regels verwerkt.

### 5.1 **Teamleden toevoegen en verwijderen**

Projectleden kunnen op elk moment op de pagina **Projectteams** aan werkstroomteams worden toegevoegd of eruit worden verwijderd zonder de werkstroomsjabloon zelf te bewerken.

**5.1.1 Leden van indienerteams** Het toevoegen van een gebruiker aan een indienerteam stelt hen in staat om voortaan nieuwe aanvragen in te dienen. Echter, lidmaatschap van het indienerteam verleent nooit gedeelde zichtbaarheid in aanvragen die door teamgenoten zijn ingediend—toegang tot een ingediende aanvraag blijft strikt persoonlijk voor de individuele maker.

**5.1.2 Leden van beoordelingsteams** Het toevoegen van een gebruiker aan een beoordelingsteam verleent hem onmiddellijk toegang tot actieve goedkeuringsaanvragen die momenteel in die controlestap zitten. Het verwijderen van alle leden uit een beoordelingsteam zal actieve aanvragen op die stap bevriezen totdat een nieuw lid wordt toegevoegd—tenzij **automatische goedkeuring** is ingeschakeld voor die stap, in welk geval de aanvraag automatisch zal goedkeuren en vooruitgaan wanneer de stapdeadline voorbij is.

**5.1.3 Leden van eindbeoordelingsteams** Het toevoegen van een gebruiker aan een eindbeoordelingsteam verleent hem onmiddellijk toegang om uiteindelijke beslissingen te bepalen op actieve aanvragen die de uiteindelijke goedkeuringsstap bereiken. Het verwijderen van alle leden uit een eindbeoordelingsteam zal actieve aanvragen op de uiteindelijke stap bevriezen totdat een gebruiker wordt toegevoegd (automatische goedkeuring is niet beschikbaar voor definitieve beoordelingsstappen).

### 5.2 **5.2** **Teams verwijderen uit projectinstellingen**

Verwijderde projectteams kunnen niet worden hersteld. Als een team dat aan een werkstroom is toegewezen, uit projectinstellingen wordt verwijderd, hangt de operationele impact af van de rol van het team in de werkstroom-levenscyclus:

**5.2.1 Verwijderde indienerteams** Indienerteams blijven na indiening bewerkbaar. Een beheerder kan de werkstromconfiguratie rechtstreeks bewerken en een nieuw actief indienerteam toewijzen.

**5.2.2 Verwijderde beoordelingsteams** Controlestappen zijn na indiening vergrendeld.

- **Als andere toegewezen teams overblijven**
  De controlestap blijft voor de resterende teams functioneren.
- **Als geen teams overblijven en automatische goedkeuring is AAN**
  De stap keurt automatisch goed en gaat verder zodra de stapdatum is bereikt.
- **Als geen teams overblijven en automatische goedkeuring is UIT**
  Actieve goedkeuringsaanvragen blijven onbepaald op die controlestap staan.

**5.2.3 Verwijderde eindbeoordelingsteams** Eindgoedkeuringsteams zijn na indiening vergrendeld, en automatische goedkeuring is **niet** beschikbaar voor definitieve beoordelingsstappen. Als alle eindbeoordelingsteams worden verwijderd, worden actieve goedkeuringsaanvragen voor onbepaalde tijd stilgezet.

**5.2.4 Aanbevolen actie voor vastgelopen of onvoltooibare werkstromen** Wanneer een controlestap met geen resterende teams vastloopt (en automatische goedkeuring is uitgeschakeld), of wanneer alle eindbeoordelingsteams worden verwijderd, is de aanbeveling om de verbroken goedkeuringswerkstroom te archiveren en alle documenten strikt te verwijderen uit open goedkeuringsaanvragen die die specifieke werkstroom volgen. Optioneel kan een nieuwe goedkeuringswerkstroom worden gemaakt als een vervanging nodig is.

### 5.3 **5.3** **Archivering en herconfiguratie van goedkeuringsonderwerpssjablonen**

Goedkeuringsonderwerpssjablonen worden apart voor elke besluituitkomst geconfigureerd (bijv. _Goedgekeurd_, _Goedgekeurd met opmerkingen_ of _Afgewezen_). Het systeem verwerkt wijzigingen in goedkeuringsonderwerpssjablonen onafhankelijk per uitkomst:

**5.3.1 Uitkomstspecifieke isolatie** Het archiveren of wijzigen van een goedkeuringsonderwerpssjabloon voor één besluituitkomst beïnvloedt alleen die specifieke uitkomst. Alle andere uitkomsten met intacte goedkeuringsonderwerpssjablonen blijven onderwerpen naar verwachting maken.

**5.3.2 Een gekoppelde goedkeuringsonderwerpssjabloon archiveren** Als een aan een uitkomst toegewezen goedkeuringsonderwerpssjabloon wordt gearchiveerd, zullen actieve goedkeuringsaanvragen die die werkstroom volgen (en nieuwe aanvragen die worden ingediend terwijl deze niet zijn gekoppeld) **geen** onderwerpen genereren als die uitkomst wordt geselecteerd.

**5.3.3 Een gearchiveerde goedkeuringsonderwerpssjabloon herstellen** Het herstellen (uit archief halen) van de oorspronkelijke goedkeuringsonderwerpssjabloon schakelt automatisch het maken van onderwerpen volgens die sjabloon in over alle bijbehorende goedkeuringsaanvragen.

**5.3.4 Een ander goedkeuringsonderwerpssjabloon configureren** Als een beheerder de werkstroom na indiening bijwerkt om een _ander_ actief goedkeuringsonderwerpssjabloon toe te wijzen, zullen actieve goedkeuringsaanvragen die vóór de bewerking zijn ingediend, **geen** onderwerpen genereren met behulp van het nieuwe sjabloon. Alleen nieuwe goedkeuringsaanvragen die na herconfiguratie worden ingediend, genereren onderwerpen op basis van het nieuw toegewezen sjabloon.
