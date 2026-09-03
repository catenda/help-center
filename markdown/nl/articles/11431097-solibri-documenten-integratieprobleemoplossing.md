# Solibri-documenten integratieprobleemoplossing

Fouten die kunnen optreden bij de Solibri-documenten integratie en hoe deze op te lossen worden in dit artikel uitgelegd.

## 1. **Accountverbinding en toegang**

### 1.1 **Afmelden tijdens uploaden/downloaden niet aanbevolen**

Het is mogelijk zich af te melden van uw account in het menu voor documentselectie.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/01-signing-out-during-up-download-not-recommended.png)

Als u zich hier afmeldt en vervolgens opnieuw aanmeldt, ziet de pagina er als volgt uit:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/02-signing-out-during-up-download-not-recommended.png)

Hoewel u op deze manier toegang kunt krijgen tot een ander Catenda-account dan dat waarvoor u toegang hebt verleend, wordt dit niet aanbevolen. Toegang zal niet zijn verleend voor dat account en eventuele modellen of documenten waarnaar u navigeert, worden niet in Solibri geïmporteerd.

### 1.2 **Uploaden -** Geen toegang tot document

Als u probeert uw smc naar een revisie te uploaden waartoe u geen toegang hebt, ziet u de volgende waarschuwing.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/03-upload-no-access-to-document.png)

In deze situatie kunt u een projectbeheerder vragen om u toegang tot het document te geven.

### 1.3 **Uploaden -** Geen toegang tot map

Als u probeert een nieuw document te maken in een map waartoe u alleen leestoegang hebt, ziet u het volgende bericht.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/04-upload-no-access-to-folder.png)

In deze situatie kunt u een projectbeheerder vragen om u minstens schrijftoegang tot de map te geven.

### 1.4 **Toegang tot uw Catenda-account intrekken**

Ga naar de toepassingenpagina van uw Catenda Hub [accountinstellingen](https://intercom.help/bimsync-arena/en/articles/6880968-account-settings#:~:text=your%20notification%20settings.-,Applications,-In%20applications%20you), zoek de Solibri-toepassing en klik op intrekken.

### 1.5 **Verbreken met de Catenda-server**

Als u niet langer verbinding wilt maken met de Catenda-server, klikt u op verbreken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/05-disconnect-from-the-catenda-server.png)

Na het verbreken heeft Solibri nog steeds toegang tot uw account. Als u later opnieuw verbinding wilt maken, hoeft u zich niet opnieuw te verifiëren.

### 1.6 **Verbinding maken met een nieuw account**

In de volgende situaties kan het helpen om verbinding te maken met een nieuw account:

- Toegang tot uw account is ingetrokken.
- Toegang geven tot een ander account.
- De verbinding opnieuw instellen als deze niet meer werkt

Het oude account kan op de volgende manieren worden verbroken:

### 1.7 **Toegang op Catenda intrekken**

Om de toegang die Solibri aan een account is verleend in te trekken, meldt u zich aan met het account op Catenda. Nadat u zich hebt aangemeld, gaat u naar de toepassingenpagina [https://hub.catenda.com/account/apps](https://hub.catenda.com/account/apps). Als Solibri toegang tot dit account is verleend, ziet u Solibri in de lijst met toepassingen met toegang tot het account. Klik op toegang intrekken. Als Solibri met dit account is verbonden, wordt de gebruiker gevraagd toegang tot een nieuw account te verlenen.

### 1.8 **Map .solibri verwijderen**

Een andere manier om de verbinding met een Catenda-account te verwijderen is door de gebruikersgegevens in Solibri te verwijderen. Verwijder hiervoor de map die hier is gevestigd:

`C:\Users\<Username>\.solibri`

> **Opmerking:** Dit is standaard een verborgen map op uw systeem. Typ het pad rechtstreeks in uw bestandsverkenner of ga hier te weten hoe u verborgen mappen kunt weergeven: [https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5](https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5)

De aanmeldingsgegevens van Solibri worden in deze map opgeslagen, dus Solibri moet de volgende keer dat het wordt geopend opnieuw worden aangemeld.

## 2. **Uploaden**

### 2.1 **Aangevraagd document niet gevonden**

Als u uw .smc van Catenda hebt geopend, wordt de locatie in het project van waaruit u deze hebt geopend, onthouden. Wanneer u de .smc later opnieuw naar Catenda uploadt en het document is verplaatst of bestaat niet in het project waarnaar u bent genavigeerd, ziet u het volgende bericht.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/06-requested-document-not-found.png)

### 2.2 **Geen nieuwe revisie**

Als u een .smc van Catenda hebt geopend en deze terug naar Catenda uploadt zonder wijzigingen aan te brengen, zelfs als u de smc ergens hebt opgeslagen, wordt u niet gevraagd deze eerst op te slaan en lijkt het alsof deze wordt geüpload. Na het uploaden krijgt u het volgende bericht zoals verwacht:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/07-no-new-revision.png)

Als uw bestand dezelfde naam had als een document in de map, ziet u dat geen nieuwe revisie aan dat document in Catenda wordt toegevoegd. Probeer uw .smc opnieuw te uploaden als dit het geval is.

### 2.3 **Nieuw document in plaats van nieuwe revisie**

Als uw bestand een andere naam had, maar u een document hebt geselecteerd waarnaar de revisie moet worden geüpload, ziet u dat een nieuw document wordt gemaakt op basis van uw bestandsnaam. Uw bestand wordt geen nieuwe revisie van het document. Zorg ervoor dat uw bestand dezelfde naam heeft als het document als u wilt dat het een nieuwe revisie van dat document wordt en geen nieuw document.

### 2.4 **Knop niet beschikbaar**

Als u probeert documenten te uploaden, ziet u mogelijk het bericht dat er geen bestanden zijn geselecteerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/08-button-not-available.png)

Dit kan het geval zijn wanneer u Solibri toegang tot Catenda hebt verleend met een account, maar probeert een .smc-bestand met een ander account te uploaden. Om toegang tot een ander account te geven, zie [hier](#h_0ef63a37db).

## 3. **Downloaden**

### 3.1 **Fout**

Als u een document hebt geselecteerd, ziet u mogelijk een fout in het rechtermenu.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/09-error.png)

Dit kan het geval zijn wanneer u Solibri toegang tot Catenda hebt verleend met een account, maar probeert het document met een ander account te downloaden. Om toegang tot een ander account te geven, zie [hier](#h_0ef63a37db).

### 3.2 **Bestandstype niet ondersteund**

Met de documenten integratie ziet u na het navigeren naar en selecteren van een niet-ondersteund document op de documentenpagina in een project het volgende bericht in het rechtermenu met informatie.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/10-filetype-not-supported.png)

Het downloaden van een document met een ander extensie heeft geen effect.

### 3.3 **Niets gebeurt**

Het account waarmee u bent aangemeld, verschilt van het account waarvoor u toegang hebt verleend.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/11-nothing-happens.png)
