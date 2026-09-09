# Catenda Navisworks-plugin

> **Opmerking:** Het installatiebestand voor de plugin is te vinden in [dit artikel](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

De Catenda Navisworks-plugin is een plugin die kan worden geïnstalleerd voor Nemetchek Archicad. Met deze plugin kunt u samenwerken aan 3D-gezichtspunten, Topics en documenten met andere leden van het bouwproject.

## 1. **Over de plugin**

De Catenda Hub-invoegtoepassing voor Autodesk® Navisworks® is het perfecte gereedschap voor projecten die samenwerken in Catenda Hub. Al uw Topics worden in realtime gesynchroniseerd tussen Navisworks en Catenda Hub, zodat u Topics kunt maken, openen, delen en communiceren. De Topic-indeling is BCF, zodat de Topics kunnen worden gedeeld via alle BCF-compatibele BIM-software of platforms. Met deze invoegtoepassing kunt u Topics naadloos visualiseren, maken en bewerken vanuit Navisworks. U kunt ook het IFC-model dat in Catenda Hub is opgeslagen, downloaden en federaliseren naar uw lokale client.

### 1.1 **Functies zijn onder meer:**

- Toegang tot al uw Catenda-projecten
- Topics filteren en beheren via Topic boards
- Topics rechtstreeks vanuit Navis Works maken
- Topics in uw Navisworks-model lokaliseren
- Een nieuwe 3D-weergave voor elke opmerking maken
- BCF-Topics maken van clashes die zijn gevonden met behulp van Clash detective
- Topics toewijzen aan andere projectleden
- Topic-status en andere eigenschappen wijzigen

## 2. **Cloudgebaseerde samenwerking**

Catenda Hub brengt uw bouwgegevens tot leven op een cloudgebaseerd samenwerkingsplatform dat de volledige levenscyclus van het gebouw beslaat. Catenda beheert uw projectinformatie van het begin tot de overdracht en verder, zodat gegevens en kennis in alle projectfasen behouden blijven.

## 3. **Open standaarden**

Catenda Hub is een BIM-samenwerkingstool met ondersteuning voor alle buildingSMART-standaarden (IFC, bSDD, BCF). Het wordt geleverd met een reeks API's voor eenvoudige implementatie in uw eigen software.

[YouTube-video](https://www.youtube.com/embed/osHul8oKysE?rel=0)

## 4. **Installatie**

Wanneer de Catenda Navisworks-plugin op Windows wordt geïnstalleerd, worden de installatiebestanden in de volgende map weergegeven.

`C:\ProgramData\Autodesk\ApplicationPlugins\Catenda.BCF.bundle`

De instellingen die in de plugin zijn geconfigureerd, vindt u hier:

`C:\Users\<Username>\AppData\Local\Autodesk_Inc\Roamer.exe_Url_<GUID>\<Version>`

### 4.1 **Verwijderen**

Als u de plugin wilt verwijderen, gaat u naar het volgende Windows-menu:

`Windows-instellingen -> Apps -> Geïnstalleerde apps`

Zoek Catenda Navisworks BCF-plugin versie \<version> in de lijst en klik op het actiemenu aan de rechterkant om het te verwijderen.

## 5. **Catenda-tabblad**

Nadat u de plugin hebt geïnstalleerd, wordt het Catenda-tabblad weergegeven. Navisworks moet mogelijk opnieuw worden gestart om het tabblad weer te geven. Op de startpagina van Navisworks is het tabblad in eerste instantie grijs weergegeven.

Start een nieuw Navisworks-project of open een bestaande om aan de slag te gaan.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/01-catenda-tab.png)

Dit is hoe het Catenda-tabblad eruit kan zien wanneer het is geselecteerd

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/02-catenda-tab.png)

### 5.1 **Catenda**

De knop Catenda in het menu Catenda-plugins van het Catenda-tabblad opent de standaardbrowser met de [aanmeldingspagina](https://support.catenda.com/en/articles/7891486-sign-in-page) van Catenda Hub.

### 5.2 **BCF Plugin**

De knop BCF Plugin in het menu Catenda-plugins van het Catenda-tabblad opent de Catenda Navisworks-plugin met het instellingenmenu geactiveerd. Het instellingenmenu van de Catenda Navisworks-plugin kan er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/03-bcf-plugin.png)

**Plugin koppelen** Sleep de titelbalk van het venster naar een van de zijden van de toepassing om het in te koppelen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/04-bcf-plugin.png)

Dit is hoe de toepassing eruit kan zien wanneer deze aan de rechterkant is gekoppeld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/05-bcf-plugin.png)

## 6. **Instellingen**

Dit is hoe het instellingenmenu er kan uitzien nadat u op Aanmelden in de linkerbovenhoek hebt geklikt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/06-settings.png)

Aan de linkerkant wordt de aanmeldingspagina van Catenda weergegeven. Volg de stappen in het [artikel Aanmelden](https://support.catenda.com/en/articles/7891486-sign-in-page) om u aan te melden.

Dit is hoe het instellingenmenu er kan uitzien nadat u zich succesvol hebt aangemeld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/07-settings.png)

Als de aanmeldingssessie is verlopen, kan de knop Vernieuwen worden gebruikt om de aanmeldingssessie te vernieuwen.

### 6.1 **Verifiëren**

**Token** Hier ziet u uw Catenda-verificatietoken na aanmelding.

### 6.2 **IFCGuid**

**Categorie en eigenschap** Categorie standaard: Element Eigenschap standaard: IfcGUID

**Eigenschappentoewijzing** De Catenda Navisworks-plugin koppelt objecten aan gezichtspunten in Topics op basis van de GUID van het IfcProject in de IFC. In Navisworks is deze GUID te vinden in de eigenschappen van het object. Hier is een voorbeeld met een geselecteerd object:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/08-ifcguid.png)

Afhankelijk van de inhoud van uw IFC, kan de IfcProject GUID zich in een of meer andere eigenschappen of categorieën bevinden. Met name als Navisworks met een andere taalinstelling dan Engels is gestart, zal de naam van de categorie Element het woord voor Element in die taal zijn, terwijl het standaardwoord nog steeds Engels is in de Catenda Navisworks-plugin. Wijzig de categorie in het woord voor Element in de taal waarin Navisworks is gestart om dit op te lossen.

2e, 3e, 4e categorie en eigenschap Als er meerdere categorieën en eigenschappen zijn die de IFCProject GUID kunnen bevatten, kunnen deze ook worden toegevoegd.

### 6.3 **Paden**

**DownloadPath** De bestandslocatie waar modellen en documenten die via de plugin worden gedownload eindigen.

### 6.4 **Snapshots**

**Plaatsing** Rechts - standaard Snapshots worden rechts weergegeven

Hieronder Snapshots worden hieronder weergegeven

## 7. **Onderwerpenboards**

In het menu Topic Boards kan een overzicht van Topics in de Topic boards van verschillende projecten worden gezien. Dit is hoe het menu Topic Boards eruit kan zien.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/09-topic-boards.png)

Klik op het tabblad Projecten om de lijst met Topic boards in dat project in het tabblad Topic boards in te laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/10-topic-boards.png)

### 7.1 **Nieuw Topic**

Klik op de knop Nieuw Topic om een nieuw Topic te maken.

## 8. **Topic**

In het Topic-menu kunnen geselecteerde Topics worden bewerkt en kunnen nieuwe Topics worden ingediend. Dit is hoe het Topic-menu eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/11-topic.png)

### 8.1 **Navigatiepijlen**

Gebruik de navigatiepijlen in het menu om tussen verschillende Topics in het Topic board te schakelen.

### 8.2 **Nieuw Topic**

Maak een nieuw Topic aan

### 8.3 **Gezichtspunt toevoegen**

Voeg een gezichtspunt van de huidige camerapositie toe aan het huidige Topic.

### 8.4 **Bijwerken**

Werk het Topic in Catenda bij met de informatie die in de plugin is toegevoegd.

### 8.5 **Topic-nummer**

Het nummer van het Topic in het project.

### 8.6 **Vernieuwen**

Laad de nieuwste informatie in het Topic vanuit Catenda.

### 8.7 **Snijvlakken wissen**

Klik op de knop Snijvlakken wissen om de snijvlakken in de viewer te wissen.

## 9. **Clashes**

In het menu Clashes kunnen Topics worden ingediend als gevolg van Clash detective-bevindingen. Dit is hoe het menu Clashes eruit kan zien.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/12-clashes.png)

### 9.1 **Een Clash detective-test uitvoeren**

Om aan de slag te gaan met het menu Clashes, zoekt u de Clash detective in het lint:

`Startpagina-tabblad -> Menu Extra -> Clash Detective`

**Testoverzicht** Voeg een nieuwe test toe. Dit is hoe uw testoverzicht eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/13-running-a-clash-detective-test.png)

**Regels** Selecteer regels of maak nieuwe.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/14-running-a-clash-detective-test.png)

**Selecteer** Selecteer modellen die u tegen elkaar wilt controleren op clashes en voer de test uit.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/15-running-a-clash-detective-test.png)

**Resultaten** Ga door de resultaten en geef uw clashes een naam.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/16-running-a-clash-detective-test.png)

**Contextmenu** Klik met de rechtermuisknop op een clash-rij om het volgende contextmenu te openen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/17-running-a-clash-detective-test.png)

Groep Groepeer clashes van soortgelijk type.

Gezichtspunt Pas het gezichtspunt aan met Focus op clash en open vervolgens het gezichtspuntmenu van het contextmenu opnieuw om het gezichtspunt in de clash op te slaan. Dit is het gezichtspunt dat in het Topic in Catenda terecht komt.

Weergave-instellingen Klik op Weergave-instellingen aan de rechterkant om de weergave-instellingen te openen.

Markering Wijzig de kleuren van de objecten van beide modellen die met elkaar botsen.

Isolatie Transparantie-instellingen

Gezichtspunten Stel gezichtspunten in om automatisch bij te werken, automatisch te laden of handmatig te laden.

Simulatie Simulatie al dan niet weergeven

In context weergeven Alles, bestand of thuis.

Items Hier ziet u de objecten die gerelateerd zijn aan de geselecteerde clash.

**Rapport** dit is hoe het rapportmenu er kan uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/18-running-a-clash-detective-test.png)

Inhoud Selecteer de inhoud van uw rapport

Clashes opnemen Selecteer welke clashes u wilt opnemen

Uitvoerinstellingen Selecteer ofwel de huidige test voor de test die in het testoverzicht is geselecteerd, ofwel alle tests voor alle tests in het testoverzicht gecombineerd of afzonderlijk.

Rapportindeling Gebruik de optie als gezichtspunten en controleer het selectievakje Markering van resultaten behouden.

### 9.2 **Clashes in Catenda-plugin**

Nadat een clash-test is uitgevoerd, worden de gezichtspunten weergegeven in het tabblad Clashes.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/19-clashes-in-catenda-plugin.png)

### 9.3 **Topic toevoegen**

Maak een Topic door een of meer clashes te selecteren Geef het Topic een titel Klik op Topic toevoegen.

**Vervolgkeuzelijst Topic toevoegen** Topics kunnen op de volgende manieren worden gemaakt:

Maak één gecombineerd Topic

- Maak één Topic van de geselecteerde clashes
  - Maak een Topic met een gezichtspunt voor elke clash die in Navisworks Clash Detective is geselecteerd.
- Maak één Topic van de geselecteerde clashes (Geconsolideerd gezichtspunt)
  - Maak een Topic met één gezichtspunt dat is uitgezoomd om alle clashes op te nemen die in Navisworks Clash Detective zijn geselecteerd.

Meerdere Topics maken

- Maak voor elke geselecteerde clash één Topic
  - Maak een Topic voor elke clash die is geselecteerd in de Catenda Navisworks-plugin.
- Maak voor elke clash-groep één Topic
  - Maak een Topic voor elke clash-groep die is geselecteerd in de Catenda Navisworks-plugin, met een gezichtspunt voor elke clash in de clash-groep.
- Maak voor elke clash-groep één Topic (Geconsolideerd gezichtspunt)
  - Maak een Topic voor elke clash-groep die is geselecteerd in de Catenda Navisworks-plugin, met één gezichtspunt dat is uitgezoomd om alle geselecteerde clashes op te nemen.
- Maak voor elke niet-gegroepeerde clash één Topic
  - Maak een Topic voor elke niet-gegroepeerde clash die is geselecteerd in de Catenda Navisworks-plugin

### 9.4 **Status wijzigen**

Wijzig de status van de clashes die in de Catenda Navisworks-plugin zijn geselecteerd in een van de volgende statussen in de Navisworks-testresultaten.

- Nieuw
- Actief
- Herzien
- Goedgekeurd
- Opgelost

## 10. **Modellen**

Download, open en voeg modelversies uit het Catenda-project toe dat is geselecteerd in het menu Topic Boards naar het Navisworks-project. Dit is hoe het menu Modellen eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/20-models.png)

### 10.1 **Zoeken**

Zoek in de modellen in het Catenda-project

### 10.2 **Vernieuwen**

Vernieuw de modellenlijst vanuit het Catenda-project

### 10.3 **Geselecteerde downloaden**

Download het/de geselecteerde model(len) van Catenda naar uw lokale systeem

### 10.4 **Geselecteerde openen**

Open het/de geselecteerde model(len) in een nieuw Navisworks-project

### 10.5 **Geselecteerde toevoegen**

Voeg het/de geselecteerde model(len) toe aan het huidige Navisworks-project. Om een model aan het huidige Navisworks-project toe te voegen, moet het eerst worden gedownload.

### 10.6 **Catenda-documentenbibliotheek**

Open het Catenda-documentenbibliotheken venster. Dit is hoe het Documentenbibliotheken venster eruit kan zien.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/21-catenda-document-library.png)

**Navigatiepijl** Ga omhoog naar een hoger niveau in de mapstructuur.

**Vernieuwen** Vernieuw de documenten in de documentenbibliotheek.

**Download** Download de nieuwste versie van het geselecteerde Catenda-document naar uw lokale systeem.

**Upload** Upload de nieuwste versie van het geselecteerde Catenda-document naar uw lokale systeem.

**Kolommen** Navigatie Dubbelklik op de navigatiepijl of ergens anders op de rij van een map om die map te openen.

Naam De naam van de map of het document

Documentnaam De naam van het document

Afbeelding De afbeelding van het document

Versie Het versienummer voor het document

### 10.7 **Kolommen**

**Selectievakje** Het selectievakje van het model

**Modelpictogram** Het pictogram van het model

**Naam** De naam van het model

**Versie Catenda** Het nieuwste versienummer in het Catenda-project

**Versie Navisworks**

**Download** Klik op het downloadpictogram om de nieuwste modelversie te downloaden. Wanneer het versienummer in de kolom Versie Navisworks verschijnt, is het model gedownload.

**Openen** Klik op het openpictogram om het model in een nieuw Navisworks-project te openen.

**Toevoegen** Klik op het toevoegpictogram om het model aan het huidige Navisworks-project toe te voegen.

### 10.8 **Modellen downloaden vanuit Catenda Hub**

U kunt de IFC-modellen eenvoudig vanuit uw Catenda-project downloaden met behulp van deze plugin en de acties op het tabblad Modellen. Als u naar uw lokale apparaat wilt downloaden: Klik op de downloadknop voor elk model dat u wilt downloaden. De modellen worden opgeslagen in een nieuwe map met de projectnaam onder het downloadpad dat is opgegeven op het tabblad Instellingen. Bijvoorbeeld:

`C:\...\Documenten\Catenda projectnaam`

### 10.9 **Een samengevoegd .nwf-bestand maken met IFC's vanuit Catenda Hub**

Om de BCF-gezichtspunten van uw Catenda-project in de Catenda-plugin te kunnen gebruiken, hebt u een samengevoegd NavisWorks-bestand nodig dat de IFC's van Catenda bevat. Download de IFC-modellen die u wilt samenvoegen volgens de bovenstaande stappen. Open een van de bestanden die u in NavisWorks hebt gedownload. Voeg meer modellen uit hetzelfde project samen met het NavisWorks-model met behulp van "Toevoegen". Zodra u alle bestanden hebt die u wilt samenvoegen toegevoegd, slaat u het bestand op als een .nwf-bestand. Sla het bestand op in dezelfde map als uw gedownloade IFC-bestanden. Gebruik dit samengevoegde bestand bij het bekijken van BCF-gezichtspunten in Navisworks. U kunt dit samengevoegde bestand ook gebruiken voor het uitvoeren van botsingstests in NavisWorks.
