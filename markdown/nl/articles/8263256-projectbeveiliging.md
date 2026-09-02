# Projectbeveiliging

## 1. **Gegevens opslaan**

### 1.1 **Actieve vs. inactieve accountstatus**

Tijdens een actieve relatie met een bedrijf wordt projectinformatie doorgaans onderhouden binnen platformorganisaties ter ondersteuning van permanente toegang. Projecten die stilstaan of bevroren zijn, maar onderdeel blijven van een actieve accountconfiguratie, kunnen toegankelijk blijven voor raadpleging en onderhoudsactiviteiten. In deze gevallen blijven gegevens beschikbaar zolang de platformorganisatie zijn actieve status behoudt.

### 1.2 **Retentie en herstel**

Wanneer een project wordt overgezet naar een verlopen status of handmatig wordt verwijderd, acties die aangeven dat het niet langer is gekoppeld aan een actieve platformorganisatie, is het platform ontworpen met de bedoeling projectgegevens tot drie jaar lang te behouden. Tijdens dit beoogde venster kunnen projecten op elk moment worden hersteld en heropend, op voorwaarde dat een actieve relatie met het bedrijf wordt gehandhaafd. De retentieperiode en de mogelijkheid om gegevens te herstellen zijn strikt onderworpen aan de wettelijke en regelgevingsvereisten van de jurisdictie waarin het project is gelokaliseerd. In gevallen waarin lokale wetten met betrekking tot softwaregegevensbeheer een eerder verwijderen vereisen, hebben die jurisdictievereisten voorrang boven standaardplatformgedrag. Om ervoor te zorgen dat informatie wordt behouden volgens interne of jurisdictionaire behoeften, wordt aanbevolen om [beschikbare exporttools](https://support.catenda.com/en/articles/7946690-exporting-all-project-data) te gebruiken om vóór projectverloping of verwijdering een definitieve back-up uit te voeren.

### 1.3 **Gegevens op binnenlands grondgebied**

Standaardplatformgegevens worden gehost in veilige, gevestigde regio's. Hoewel huidige configuraties gecentraliseerd zijn, kunnen er mogelijkheden zijn om gegevensresidentie in specifieke geografische locaties tot stand te brengen, afgestemd op lokale regelgevingsvereisten. Organisaties met unieke hosting- of "binnenlands grondgebied"-behoeften worden aangemoedigd contact op te nemen met ondersteuning op [support@catenda.com](mailto:support@catenda.com) om mogelijke technische mogelijkheden en configuraties te bespreken.

## 2. **Gegevens delen met personen buiten het project**

Koppelingen kunnen worden gemaakt om zowel modellen als documenten met externe partijen te delen. Iedereen die toegang heeft tot een dergelijke koppeling hoeft geen account te hebben om het model te bekijken of de documenten te downloaden. Documenten kunnen worden gedeeld door een open URL van een documentverzameling te maken. _Vereiste toegang:_ Projectlid

Modellen kunnen worden gedeeld door een open URL van een opgeslagen view te maken. _Vereiste toegang:_ Beheerder

Het is mogelijk om aan te vragen dat deze soort URL's voor al uw projecten worden uitgeschakeld.

## 3. **Gegevens downloaden**

Bestanden kunnen als documentversies naar de sectie documenten worden geüpload.

### 3.1 **Beperking van downloaden met toegangsbeheer**

**Documenten / modellen** Toegang tot documenten kan afzonderlijk worden beheerd. Als de toegang tot het IFC-document beperkt is, kunnen alleen personen met toegang tot het document het zien. Leden met toegang tot het document kunnen het downloaden.

**Topics** Toegang tot topics kan per topic board worden beheerd. Als toegang tot een topic board beperkt is, kunnen alleen personen met toegang tot de topic board de topics in het bord zien. Leden met toegang tot de topic board kunnen topics naar BCF, PDF en Excel exporteren.

### 3.2 **Beperking van downloaden door een versie in te trekken**

Als een versie aanwezig is in een document dat daar niet zou moeten zijn, kan een beheerder de versie intrekken. Nadat een versie is ingetrokken, kan deze nergens meer door iemand worden bekeken of gedownload.

### 3.3 **Beperking van downloaden van afzonderlijke topics**

Om de relaties met elementen zoals documenten, topics en objecten te behouden, kan een topic worden gearchiveerd. Topics kunnen naar een ander topic board worden verplaatst. Het topic board kan vervolgens worden gearchiveerd. _Vereiste toegang:_ Beheerder

Terwijl het topic zich in het gearchiveerde topic board bevindt, blijven elementrelaties intact maar zijn niet zichtbaar op het gerelateerde element. Als een topic board wordt hersteld, zullen de gerelateerde elementen hun relatie tot het topic opnieuw weergeven.

### 3.4 Beperking van het downloaden van modellen

Als het document een IFC-document is, kan het aan een model worden gekoppeld.

_Binnen het project_ Zelfs als het document aan een model is gekoppeld, kunnen alleen personen met toegang tot het document het op het dashboard, de modelenpagina en in de versieselector zien verschijnen.

**Extern delen** Als een model met een openbare koppeling in een opgeslagen view wordt gedeeld, kan de modelweergave alleen worden bekeken en niet worden gedownload.

Objectinformatie is niet zichtbaar in extern gedeelde opgeslagen views.

## 4. **Gegevens verwijderen**

**Documenten/modellen** Leden kunnen documenten verwijderen, maar beheerders in een project kunnen documenten altijd vinden door te zoeken met het filter "verwijderd". Houd er rekening mee dat dit filter taalspecifiek is.

**Topics** Vóór verwijdering kunnen topics naar BCF worden geëxporteerd. Het topic voor die ID wordt verwijderd, maar als u de ID in de BCF wijzigt, kan het topic opnieuw worden geïmporteerd. Relaties met elementen zoals documenten, objecten en topics gaan dan verloren.

**Milestones** Leden kunnen milestones archiveren en herstellen. _Vereiste toegang:_ Milestone-maker of beheerder.
