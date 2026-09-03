# Een zip / bestandsstructuur uploaden

In vergelijking met het uploaden van een regulier zipbestand, zal de functie een zip uploaden en uitpakken. Op deze manier kunt u een bestandsstructuur in de [Documenten pagina](https://support.catenda.com/en/articles/8204673-documents-page#h_28610e1d21) importeren zonder handmatig mappen te hoeven maken.

De functie voor het uploaden van een zip bestand is te vinden in het actiemenu aan de rechterkant van de groene + knop in de rechterbovenhoek van de Documenten pagina.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/01-intro.png)

## 1. **Een zip bestand selecteren**

Na het klikken op het menu-item Upload zip, wordt het volgende dialoogvenster geopend:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/02-selecting-a-zip-file.png)

Uw systeembestandsbrowser moet automatisch openen. Als de bestandsbrowser niet is geopend of gesloten is zonder een zip-bestand te selecteren, kunt u deze opnieuw openen door op de knop 'Selecteer zip-bestand' te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/03-selecting-a-zip-file.png)

Nadat u met succes een zip bestand op uw lokale systeem hebt geselecteerd, ziet u de naam van het zip bestand hieronder en wordt de knop Upload zip gemarkeerd in diep groen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/04-selecting-a-zip-file.png)

Als u geen map in de sectie Document hebt ingevoerd, wordt aangegeven dat de inhoud wordt geëxtraheerd naar de map Root. Dit betekent dat u de inhoud meteen ziet wanneer u de sectie Documenten opent. Het is ook mogelijk om naar een map in Catenda te navigeren en uw zip daar te uploaden als u wilt dat de bestandsstructuur daar verschijnt.

## 2. **Uploadconfiguratie**

Instellingen kunnen worden geconfigureerd voor elementen waarvan de namen in het zip bestand reeds aanwezig zijn op de locatie waar de zip-extractie probeert ze in het Catenda project te plaatsen.

### 2.1 **Mappen**

Nieuwe mappen worden alleen aangemaakt als er op de locatie waar de zip een map probeert uit te pakken nog geen map met die naam aanwezig is. Alle elementen in een map waarbij een map met dezelfde naam al aanwezig is, worden in de bestaande map met dezelfde naam in het Catenda project geplaatst.

### 2.2 **Documenten**

Verschillende gedragingen kunnen worden geconfigureerd voor hoe de extractie van het zip bestand zich gedraagt wanneer een document met dezelfde naam als het bestand in het zip bestand al op dezelfde locatie aanwezig is waar het zip bestand in het Catenda project probeert het uit te pakken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/05-documents.png)

**Nieuwe revisie maken - Standaard** Als een document met dezelfde naam op dezelfde locatie aanwezig is als waar de zip een bestand probeert uit te pakken, wordt een nieuwe revisie in dat document aangemaakt.

**Overslaan en doorgaan** Als een document met dezelfde naam op dezelfde locatie aanwezig is als waar de zip een bestand probeert uit te pakken, wordt het bestand overgeslagen en wordt geen nieuwe revisie in het document aangemaakt.

### 2.3 **Status toepassen**

Als de statusworkflow in uw project is ingeschakeld, kunt u configureren welke status nieuwe Documenten krijgen. Als u voor de optie nieuwe revisie maken kiest, wordt de status van Documenten die een nieuwe revisie ontvangen automatisch gewijzigd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/06-apply-status.png)

Het is alleen mogelijk om te kiezen tussen gedeelde revisiestatus. Na het uploaden kunnen de gedeelde revisies in het tabblad werkruimte worden gevonden en kunnen later worden gepubliceerd.

## 3. **Uploaden**

Nadat u op upload zip hebt geklikt, wordt uw zip geüpload

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/07-uploading.png)

U kunt doorgaan met werken in Catenda op een ander tabblad terwijl u wacht tot het uploaden is voltooid.

**Vereiste toegang:** Schrijftoegang tot elk van de locaties waar mappen en Documenten worden aangemaakt. Schrijftoegang tot Documenten revisies die worden toegevoegd.

## 4. **Uitpakken**

Nadat uw zip is geüpload, begint Catenda uw zip uit te pakken. Tijdens het uitpakken ziet u het volgende menu in de linkerbenedenhoek:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/08-extracting.png)

U kunt dit menu open houden terwijl u door Catenda bladert, of het sluiten als u dat wilt. U kunt de browser zelfs volledig sluiten tijdens het uitpakproces. De zip blijft op de achtergrond uitpakken. Als u Catenda in een ander tabblad hebt gebruikt terwijl de zip wordt uitgepakt, ziet u de mappen, Documenten en revisies op de locatie waar u ze hebt uitgepakt door de pagina te vernieuwen.

### 4.1 **Uitpakken voltooid**

Wanneer de zip klaar is met uitpakken, staat in het dialoogvenster voltooid.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/09-extraction-completed.png)

Klik op details weergeven om te zien welke bestanden zijn geëxtraheerd. U kunt deze details later vinden in "Mijn zip uploads" zoals hieronder uitgelegd. Vernieuw de pagina om alle geüploade bestanden te zien.

### 4.2 **Melding zip-import voltooid**

Als u het dialoogvenster hebt gesloten, de browser hebt vernieuwd of de pagina hebt vernieuwd, ziet u het dialoogvenster niet meer. U ontvangt ook een melding dat uw zip-extractie is voltooid. Op deze manier weet u wanneer uw zip-upload is voltooid, zelfs als u het extractiedialoogvenster niet meer ziet.

## 5. **De bestandsgroottelimiet omzeilen**

Met het uploaden van een zip kunt u bestanden uploaden die groter zijn dan 7 GB omdat de zip het bestand comprimeert.

## 6. **Mijn zip-uploads**

De optie onder de zip-upload in het actiemenu stelt u in staat om een overzicht van uw vorige zip-uploads te zien. Dit is hoe zip-imports met de verschillende mogelijke statussen er uit kunnen zien:

### 6.1 **Uitpakken**

Terwijl de zip wordt uitgepakt, verschijnen de geëxtraheerde bestanden als rijen in de Documenten tabel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/10-extracting.png)

**Voltooid** Wanneer de zip-import is voltooid, zijn alle bestanden geëxtraheerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/11-extracting.png)

### 6.2 **Zip-importpagina**

Klik op een zip-import om meer informatie over het importproces te zien. Dit is hoe de zip-importpagina van een voltooide zip-import er uit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/12-zip-import-page.png)

Dit is hoe het rechtermenu van de zip-importpagina van een voltooide zip-import er uit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q3fxr4yj/13-zip-import-page.png)

## 7. **Desktopconnector**

Met de [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) kunt u automatisch en periodiek de nieuwste versies van Documenten van uw lokale systeem naar Catenda Hub uploaden. De Desktop Connector is sneller dan het normale uploadproces en minimaliseert het risico op fouten doordat deze Documenten bestand-voor-bestand uploadt in plaats van in één groot drag-and-drop of zip-uploadbatch.
