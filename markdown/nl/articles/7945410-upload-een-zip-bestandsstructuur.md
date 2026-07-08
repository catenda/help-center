# Een zip / bestandsstructuur uploaden

In tegenstelling tot het uploaden van een gewone zip-bestand, zal de functie zip uploaden een zip uitpakken. Op deze manier kunt u een bestandsstructuur importeren in de [Documenten-pagina](https://support.catenda.com/en/articles/8204673-documents-page#h_28610e1d21) zonder handmatig mappen te hoeven maken.

De functie Zip uploaden vindt u in het actiemenu rechts van de groene +-knop in de rechterbovenhoek van de Documenten-pagina.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/01-intro.png)

## 1. **Een zip-bestand selecteren**

Nadat u op het menu-item Zip uploaden klikt, wordt het volgende dialoogvenster geopend:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/02-selecting-a-zip-file.png)

Uw systeembestandsbrowser moet automatisch worden geopend. Als de bestandsbrowser niet opende of als deze werd gesloten zonder een zip-bestand te selecteren, kunt u deze opnieuw openen door op de knop Zip-bestand selecteren te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/03-selecting-a-zip-file.png)

Nadat u een zip-bestand op uw lokale systeem hebt geselecteerd, zou u de naam van het zip-bestand hieronder moeten zien en wordt de knop Zip uploaden gemarkeerd in diepgroen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/04-selecting-a-zip-file.png)

Als u geen map in het gedeelte Documenten hebt ingevoerd, wordt aangegeven dat de inhoud wordt uitgepakt naar de Hoofdmap. Dit betekent dat u de inhoud meteen ziet wanneer u het gedeelte Documenten opent. Het is ook mogelijk om naar een map in Catenda te navigeren en uw zip daar te uploaden als u wilt dat de bestandsstructuur daar wordt weergegeven.

## 2. **Uploadconfiguratie**

Instellingen kunnen worden geconfigureerd voor elementen met namen in het zip-bestand die al bestaan op de locatie waar de zip-extractie deze in het Catenda-project wil plaatsen.

### 2.1 **Mappen**

Nieuwe mappen worden alleen aangemaakt als er op de locatie waar het zip-bestand een map wil uitpakken nog geen map met die naam bestaat. Alle elementen in een map waarbij een map met dezelfde naam al bestaat, worden in de bestaande map met dezelfde naam in het Catenda-project geplaatst.

### 2.2 **Documenten**

Er kunnen verschillende gedragingen worden geconfigureerd voor de manier waarop de extractie van het zip-bestand gedraagt wanneer een document met dezelfde naam als het bestand in het zip-bestand al bestaat op dezelfde locatie waar het zip-bestand in het Catenda-project wil uitpakken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/05-documents.png)

**Nieuwe revisie maken - Standaard** Als een document met dezelfde naam op dezelfde locatie bestaat waar het zip-bestand een bestand wil uitpakken, wordt een nieuwe revisie in dat document aangemaakt.

**Overslaan en doorgaan** Als een document met dezelfde naam op dezelfde locatie bestaat waar het zip-bestand een bestand wil uitpakken, wordt het bestand overgeslagen en wordt er geen nieuwe revisie in het document aangemaakt.

### 2.3 **Status toepassen**

Als de statuswerkstroom in uw project is ingeschakeld, kunt u configureren wat de status van nieuwe Documenten zal zijn. Als u de optie nieuwe revisie maken kiest, wordt de status van Documenten die een nieuwe revisie ontvangen automatisch gewijzigd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/06-apply-status.png)

Het is alleen mogelijk om te kiezen tussen gedeelde revisiestatussen. Na het uploaden kunnen de gedeelde revisies worden gevonden in het tabblad werkruimte en kunnen later worden gepubliceerd.

## 3. **Uploaden**

Nadat u op zip uploaden klikt, begint uw zip te uploaden

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/07-uploading.png)

U kunt met Catenda op een ander tabblad blijven werken terwijl u wacht tot het uploaden is voltooid.

**Vereiste toegang:** Schrijftoegang tot elk van de locaties waar mappen en Documenten zullen worden aangemaakt Schrijftoegang tot Documenten waaraan revisies zullen worden toegevoegd.

## 4. **Uitpakken**

Nadat uw zip is geupload, begint Catenda uw zip uit te pakken. Tijdens het uitpakken ziet u het volgende menu linksonder:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/08-extracting.png)

U kunt dit menu open houden terwijl u in Catenda bladert, of het sluiten als u dat wilt. U kunt zelfs de browser volledig sluiten tijdens het extractieproces. Het zip-bestand blijft op de achtergrond uitpakken. Als u Catenda in een ander tabblad gebruikt terwijl het zip-bestand wordt uitgepakt, ziet u mappen, Documenten en revisies in de locatie waar u de extractie uitvoerde door de pagina te vernieuwen.

### 4.1 **Extractie voltooid**

Wanneer het zip-bestand klaar is met uitpakken, staat er voltooid in het dialoogvenster.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/09-extraction-completed.png)

Klik op details weergeven om te zien welke bestanden zijn geëxtraheerd. U kunt deze details later vinden in "Mijn zip-uploads" zoals hieronder wordt uitgelegd. Vernieuw de pagina om alle bestanden te zien die zijn geupload.

### 4.2 **Melding zip-import voltooid**

Als u het dialoogvenster, de browser hebt gesloten of de pagina hebt vernieuwd, ziet u het dialoogvenster niet meer. U ontvangt ook een melding dat uw zip-extractie is voltooid. Op deze manier weet u wanneer uw zip-upload is voltooid, zelfs als u het dialoogvenster voor extractie niet meer ziet.

## 5. **De bestandsgroottenlimiet omzeilen**

Door een zip te uploaden, kunt u bestanden uploaden die groter zijn dan 7 GB omdat het zip-bestand het bestand comprimeert.

## 6. **Mijn zip-uploads**

Met de optie onder de zip-upload in het actiemenu kunt u een overzicht van uw eerdere zip-uploads zien. Zo kunnen zip-imports met verschillende mogelijke statussen er uitzien:

### 6.1 **Uitpakken**

Terwijl het zip-bestand wordt uitgepakt, beginnen de geëxtraheerde bestanden als rijen in de Documententabel te verschijnen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/10-extracting.png)

**Voltooid** Wanneer de zip-import is voltooid, worden alle bestanden geëxtraheerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/11-extracting.png)

### 6.2 **Zip-importpagina**

Klik op een zip-import om meer informatie over het importproces te zien. Zo kan de zip-importpagina van een voltooide zip-import er uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/12-zip-import-page.png)

Zo kan het rechtermenu van de zip-importpagina van een voltooide zip-import er uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/13-zip-import-page.png)

## 7. **Desktopconnector**

Met de [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) kunt u automatisch en periodiek de nieuwste versies van Documenten van uw lokale systeem naar Catenda Hub uploaden. De Desktop Connector is sneller dan het normale uploadproces en minimaliseert het risico op fouten omdat het Documenten per bestand uploadt in plaats van één grote drag-and-drop of zip-uploadbatch.
