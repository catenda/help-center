# Catenda Navisworks plugin

> **Opmerking:** Het installatiebestand voor de plugin is te vinden in [dit artikel](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

De Catenda Navisworks plugin is een plugin die kan worden geïnstalleerd voor Nemetchek Archicad. Met deze plugin kunt u samenwerken aan 3D-viewpoints, topics en Documenten met andere leden van het bouwproject.

De volgende topics worden in dit artikel beschreven:

## 1. **Over de plugin**

De Catenda Hub add-in voor Autodesk® Navisworks® is het perfecte gereedschap voor projecten die samenwerken in Catenda Hub. Al uw topics worden in real-time gesynchroniseerd tussen Navisworks en Catenda Hub, zodat u topics kunt maken, openen, delen en communiceren. De topic-indeling is BCF zodat de topics kunnen worden gedeeld via elke BCF-ondersteunde BIM-software of -platform. Deze add-in stelt u in staat topics naadloos vanuit Navisworks te visualiseren, maken en bewerken. U kunt ook het IFC-model dat in Catenda Hub is opgeslagen downloaden en federeren naar uw lokale client.

### 1.1 **Functies zijn onder meer:**

- Toegang tot al uw Catenda-projecten
- Topics filteren en beheren in topic boards
- Maak rechtstreeks vanuit Navis Works nieuwe topics
- Zoek topics in uw Navisworks-model
- Maak een nieuwe 3D-weergave voor elke opmerking
- Maak BCF topics vanuit clashes die met behulp van Clash Detective zijn gevonden
- Wijs topics toe aan andere projectleden
- Wijzig topic Status en andere eigenschappen

## 2. **Cloud-gebaseerde samenwerking**

Catenda Hub brengt uw bouwgegevens tot leven op een cloud-gebaseerd samenwerkingsplatform dat de volledige levenscyclus van het gebouw omvat. Catenda beheert uw projectinformatie van begin tot oplevering en daarna, wat zorgt voor behoud van gegevens en kennis over alle projectfasen heen.

## 3. **Open standaarden**

Catenda Hub is een BIM-samenwerkingshulpmiddel met ondersteuning voor alle buildingSMART-standaarden (IFC, bSDD, BCF). Het bevat een reeks API's voor eenvoudige implementatie in uw eigen software.

[YouTube-video](https://www.youtube.com/embed/osHul8oKysE?rel=0)

## 4. **Installatie**

Wanneer de Catenda Navisworks plugin op Windows wordt geïnstalleerd, verschijnen de installatiebestanden in de volgende map.

`C:\ProgramData\Autodesk\ApplicationPlugins\Catenda.BCF.bundle`

De instellingen die in de plugin zijn geconfigureerd, zijn hier te vinden:

`C:\Users\<Username>\AppData\Local\Autodesk_Inc\Roamer.exe_Url_<GUID>\<Version>`

### 4.1 **Verwijderingen**

Als u de plugin wilt verwijderen, gaat u naar het volgende Windows-menu:

`Windows-instellingen -> Apps -> Geïnstalleerde apps`

Zoek Catenda Navisworks BCF plugin versie \<version> in de lijst en klik op het actiemenu aan de rechterkant om te verwijderen.

## 5. **Catenda-tabblad**

Nadat de plugin is geïnstalleerd, verschijnt het Catenda-tabblad. Navisworks moet mogelijk opnieuw worden gestart voordat het tabblad wordt weergegeven. Op de startpagina van Navisworks wordt het tabblad in eerste instantie grijs weergegeven.

Start een nieuw project of open een Navisworks-project om aan de slag te gaan.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/01-catenda-tab.png)

Dit is wat het Catenda-tabblad er kan uitzien wanneer het is geselecteerd

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/02-catenda-tab.png)

De volgende topics worden in deze sectie beschreven:

### 5.1 **Catenda**

De Catenda-knop in het menu Catenda-plugins van het Catenda-tabblad opent de standaardbrowser met de [aanmeldingspagina](https://support.catenda.com/en/articles/7891486-sign-in-page) van Catenda Hub.

### 5.2 **BCF Plugin**

De BCF Plugin-knop in het menu Catenda-plugins van het Catenda-tabblad opent de Catenda Navisworks plugin met het instellingenmenu geactiveerd. Het instellingenmenu van de Catenda Navisworks plugin kan er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/03-bcf-plugin.png)

**De plugin aan het raam vastmaken** Sleep de titelbalk van het venster naar een van de zijkanten van de toepassing om deze vast te maken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/04-bcf-plugin.png)

Dit is wat de applicatie er kan uitzien wanneer deze aan de rechterkant is vastgemaakt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/05-bcf-plugin.png)

## 6. **Instellingen**

Dit is wat het instellingenmenu er kan uitzien nadat u linksboven op Aanmelden hebt geklikt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/06-settings.png)

Aan de linkerkant wordt de aanmeldingspagina van Catenda weergegeven. Volg de stappen die in het [aanmeldartikel](https://support.catenda.com/en/articles/7891486-sign-in-page) worden beschreven om aan te melden.

Dit is wat het instellingenmenu er kan uitzien nadat u zich hebt aangemeld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/07-settings.png)

Als de aanmeldingssessie is verlopen, kan de knop Vernieuwen worden gebruikt om de aanmeldingssessie te vernieuwen.

De volgende topics worden in deze sectie beschreven:

### 6.1 **Verifiëren**

**Token** Hier ziet u uw Catenda-verificatietoken na aanmelding.

### 6.2 **IFCGuid**

**Categorie en eigenschap** Categorie standaard: Element Eigenschap standaard: IfcGUID

**Eigenschapstoewijzing** De Catenda Navisworks plugin koppelt objecten aan viewpoints in topics op basis van de GUID van het IfcProject in de IFC. In Navisworks is deze GUID te vinden in de eigenschappen van het object. Hier is een voorbeeld met een geselecteerd object:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/08-ifcguid.png)

Afhankelijk van de inhoud van uw IFC, kan de IfcProject GUID in een of meer andere eigenschappen of categorieën worden gevonden. Met name als Navisworks is gestart met een taalsetting anders dan Engels, wordt de naam van de categorie Element het woord voor Element in die taal weergegeven, terwijl het standaardwoord nog steeds Engels is in de Catenda Navisworks plugin. Als u dit wilt oplossen, wijzigt u de Categorie in het woord voor Element in de taal waarin Navisworks wordt gestart.

2e, 3e, 4e Categorie en Eigenschap Als er meerdere categorieën en eigenschappen zijn die de IFCProject GUID kunnen bevatten, kunnen deze ook worden toegevoegd.

### 6.3 **Paden**

**DownloadPath** De bestandslocatie waar modellen en Documenten die via de plugin worden gedownload, terechtkomen.

### 6.4 **Snapshot**

**Plaatsing** Rechts - standaard Snapshot worden rechts weergegeven

Onder Snapshot worden hieronder weergegeven

## 7. **Topic Boards**

In het menu Topic Boards kunt u een overzicht van topics in de topic boards van verschillende projecten zien. Dit is wat het menu Topic Boards er kan uitzien.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/09-topic-boards.png)

Klik op het tabblad Projecten om de lijst met topic boards in dat project in het tabblad Topic boards in te laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/10-topic-boards.png)

### 7.1 **Nieuw topic**

Klik op de knop Nieuw topic om een nieuw topic te maken.

## 8. **Topic**

In het topicmenu kunnen geselecteerde topics worden bewerkt en kunnen nieuwe topics worden ingediend. Dit is wat het topicmenu er kan uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/11-topic.png)

De volgende topics worden in deze sectie beschreven:

### 8.1 **Navigatiepijlen**

Gebruik de navigatiepijlen in het menu om tussen verschillende topics in het topic board te bewegen.

### 8.2 **Nieuw topic**

Maak een nieuw topic

### 8.3 **Viewpoint toevoegen**

Voeg een viewpoint van de huidige camerapositie toe aan het huidige topic.

### 8.4 **Bijwerken**

Werk het topic in Catenda bij met de gegevens die in de plugin zijn toegevoegd.

### 8.5 **Topicnummer**

Het nummer van het topic in het project.

### 8.6 **Vernieuwen**

Laad de meest recente gegevens in het topic van Catenda.

### 8.7 **Snijvlakken wissen**

Klik op de knop Snijvlakken wissen om de snijvlakken in de Viewer te wissen.

## 9. **Clashes**

In het menu Clashes kunnen topics als gevolg van bevindingen van Clash Detective worden ingediend. Dit is wat het menu Clashes er kan uitzien.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/12-clashes.png)

De volgende topics worden in deze sectie beschreven:

### 9.1 **Een clash-detective test uitvoeren**

Als u aan de slag wilt gaan met het menu Clashes, zoekt u de Clash Detective in het lint:

`Start tabblad -> Menu Extra's -> Clash Detective`

**Testoverzicht** Voeg een nieuwe test toe. Dit is hoe uw testoverzicht er uit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/13-running-a-clash-detective-test.png)

**Regels** Selecteer regels of maak er nieuwe.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/14-running-a-clash-detective-test.png)

**Selecteer** Selecteer modellen die u tegen elkaar wilt controleren op clashes en voer de test uit.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/15-running-a-clash-detective-test.png)

**Resultaten** Ga door de resultaten en naam uw clashes.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/16-running-a-clash-detective-test.png)

**Contextmenu** Klik met de rechtermuisknop op een clashveld om het volgende contextmenu te openen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/17-running-a-clash-detective-test.png)

Groep Groepeer clashes van soortgelijk type samen.

Viewpoint Pas de viewpoint aan met Focus op clash en open vervolgens het viewpoint-menu van het contextmenu opnieuw om de viewpoint in de clash op te slaan. Dit is de viewpoint die in het topic in Catenda zal terechtkomen.

Weergave-instellingen Klik op Weergave-instellingen aan de rechterkant om de weergave-instellingen te openen.

Markering Wijzig de kleuren van de objecten uit een van beide modellen die met elkaar botsen.

Isolatie Transparantie-instellingen

Viewpoints Stel viewpoints in op automatisch bijwerken, automatisch laden of handmatig laden.

Simulatie Simulatie tonen of niet

Weergave in context Alles, bestand of thuis.

Items Hier ziet u de objecten die betrekking hebben op de geselecteerde clash.

**Rapport** Dit is hoe het rapportmenu er uit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/18-running-a-clash-detective-test.png)

Inhoud Selecteer de inhoud van uw rapport

Clashes opnemen Selecteer welke clashes u wilt opnemen

Uitvoerinstellingen Selecteer ofwel de huidige test voor de test die is geselecteerd in het testoverzicht, ofwel alle tests voor alle tests in het testoverzicht gecombineerd of apart.

Rapportindeling Gebruik de optie Als viewpoints en controleer het selectievakje Markeringsresultaten behouden.

### 9.2 **Clashes in Catenda plugin**

Nadat een clashtest is uitgevoerd, verschijnen de viewpoints in het tabblad Clashes.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/19-clashes-in-catenda-plugin.png)

### 9.3 **Topic toevoegen**

Maak een topic door een of meer clashes te selecteren Geef het topic een titel Klik op Topic toevoegen.

**Vervolgkeuzelijst Topic toevoegen** Topics kunnen op de volgende manieren worden gemaakt:

Maak één gecombineerd topic

- Maak één topic van de geselecteerde clashes
  - Maak een topic met een viewpoint voor elke clash die is geselecteerd in Navisworks Clash Detective.
- Maak één topic van de geselecteerde clashes (Geconsolideerde viewpoint)
  - Maak een topic met een enkele viewpoint die is uitgezoomed om alle clashes op te nemen die zijn geselecteerd in Navisworks Clash Detective.

Maak meerdere topics

- Maak één topic voor elke geselecteerde clash
  - Maak een topic voor elke clash die is geselecteerd in de Catenda Navisworks plugin.
- Maak één topic voor elke clashgroep
  - Maak een topic voor elke clashgroep, die is geselecteerd in de Catenda Navisworks plugin, met een viewpoint voor elke clash in de clashgroep.
- Maak één topic voor elke clashgroep (Geconsolideerde viewpoint)
  - Maak een topic voor elke clashgroep, die is geselecteerd in de Catenda Navisworks plugin, met een enkele viewpoint die is uitgezoomed om alle geselecteerde clashes op te nemen.
- Maak één topic voor elke niet-gegroepeerde clash
  - Maak een topic voor elke niet-gegroepeerde clash die is geselecteerd in de Catenda Navisworks plugin

### 9.4 **Status wijzigen**

Wijzig de Status van de clashes die zijn geselecteerd in de Catenda Navisworks plugin naar een van de volgende statusen in de Navisworks-testresultaten.

- Nieuw
- Actief
- Beoordeeld
- Goedgekeurd
- Opgelost

## 10. **Modellen**

Download, open en append modelrevisies van het in het menu Topic Boards geselecteerde Catenda-project naar het Navisworks-project. Dit is wat het menu Modellen er kan uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/20-models.png)

De volgende topics worden in deze sectie beschreven:

### 10.1 **Zoeken**

Zoek modellen in het Catenda-project

### 10.2 **Vernieuwen**

Vernieuw de modellenlijst van het Catenda-project

### 10.3 **Geselecteerde downloaden**

Download het/de geselecteerde model(len) van Catenda naar uw lokale systeem

### 10.4 **Geselecteerde openen**

Open het/de geselecteerde model(len) in een nieuw Navisworks-project

### 10.5 **Geselecteerde toevoegen**

Voeg het/de geselecteerde model(len) toe aan het huidige Navisworks-project. Als u een model aan het huidige Navisworks-project wilt toevoegen, moet dit eerst worden gedownload.

### 10.6 **Catenda-documentbibliotheek**

Open het venster van de Catenda-documentbibliotheek. Dit is wat het venster Documentbibliotheek er kan uitzien.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/21-catenda-document-library.png)

**Navigatiepijl** Ga een niveau omhoog in de mappenstructuur.

**Vernieuwen** Vernieuw de Documenten in de documentbibliotheek.

**Downloaden** Download de nieuwste revisie van het geselecteerde Catenda document naar uw lokale systeem.

**Uploaden** Upload de nieuwste revisie van het geselecteerde Catenda document naar uw lokale systeem.

**Kolommen** Navigatie Dubbelklik op de navigatiepijl of elders in de rij van een map om die map te openen.

Naam De naam van de map of document

Documentnaam De naam van het document

Afbeelding De afbeelding van het document

Revisie Het revisienummer voor het document

### 10.7 **Kolommen**

**Selectievak** Het selectievak van het model

**Modelpictogram** Het pictogram van het model

**Naam** De naam van het model

**Revisie Catenda** Het meest recente revisienummer in het Catenda-project

**Revisie Navisworks**

**Downloaden** Klik op het downloadpictogram om de nieuwste modelrevisie te downloaden. Wanneer het revisienummer in de kolom Revisie navisworks wordt weergegeven, is het model gedownload.

**Openen** Klik op het open-pictogram om het model in een nieuw Navisworks-project te openen.

**Toevoegen** Klik op het append-pictogram om het model aan het huidige Navisworks-project toe te voegen.

### 10.8 **Modellen downloaden van Catenda Hub**

U kunt eenvoudig de IFC-modellen van uw Catenda-project downloaden met behulp van deze plugin en de acties in het tabblad Modellen. Als u naar uw lokale apparaat wilt downloaden: Klik op de downloadknop voor elk model dat u wilt downloaden. De modellen worden opgeslagen in een nieuwe map met de projectnaam onder het downloadpad dat is opgegeven op het tabblad Instellingen. Bijvoorbeeld:

`C:\...\Documenten\Catenda projectnaam`

### 10.9 **Een samengevoegd .nwf-bestand maken met IFC's van Catenda Hub**

Om de BCF-viewpoints van uw Catenda-project in de Catenda-plugin te kunnen gebruiken, hebt u een samengevoegd NavisWorks-bestand nodig dat de IFC's van Catenda bevat. Download de IFC-modellen die u wilt samenvoegen volgens de bovenstaande stappen. Open een van de bestanden die u hebt gedownload in NavisWorks. Voeg meer modellen van hetzelfde project samen in het NavisWorks-model met behulp van "Toevoegen". Nadat u alle bestanden die u wilt samenvoegen hebt toegevoegd, slaat u het bestand op als .nwf-bestand. Sla het bestand op in dezelfde map als uw gedownloade IFC-bestanden. Gebruik dit samengevoegde bestand wanneer u BCF-viewpoints in Navisworks bekijkt. U kunt dit samengevoegde bestand ook gebruiken om botsingstests in NavisWorks uit te voeren.
