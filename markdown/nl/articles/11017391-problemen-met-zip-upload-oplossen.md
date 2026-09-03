# Problemen met zip-upload oplossen

## 1. **Upload mislukt**

Het wordt aanbevolen een bedrade verbinding te gebruiken voor het uploaden van zip-bestanden naar Catenda. Veel wifi-routers zorgen er goed voor dat ze de juiste gegevens ontvangen, maar zelfs de beste routers kunnen moeite hebben met een zwak signaal als je ver van de router verwijderd bent.

### 1.1 **Kan het bestand niet verwerken**

Tijdens het uploaden van zip-bestanden worden gegevenspakketten naar de Catenda-server gestuurd. Als er een probleem is met een van de pakketten tijdens het proces, wordt het volgende bericht weergegeven: Upload mislukt! Kan het bestand niet verwerken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/01-unable-to-process-file.png)

Zelfs wanneer je dicht bij een wifi-antenne bent met een apparaat, is het nooit 100% zeker dat het pakket veilig door de lucht aankomt. Dit effect wordt versterkt door verder weg van de antenne te zijn of als er objecten zoals muren tussen het apparaat en de antenne zijn.

**Grote bestanden** Wanneer grote hoeveelheden gegevens worden geüpload, worden veel pakketten verzonden. Als zelfs één ervan niet goed via de lucht naar de router aankomt, kan een netwerkfout verschijnen. Wanneer dit gebeurt, is de hele upload ongeldig.

### 1.2 **Netwerkfout**

Bepaalde software beperkt het aantal tekens dat paden naar bestanden in een zip-bestand kunnen hebben. Als er een probleem is met de padstructuur in het zip-bestand, wordt de volgende fout weergegeven: Upload mislukt! Netwerkfout.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/02-network-error.png)

**Uitpakken/opnieuw inpakken** Als deze zip van iemand anders is ontvangen, kan het helpen om deze uit te pakken en opnieuw in te pakken.

**Bekende limieten (bijgewerkt december 2025)** Microsoft Windows 10/11 De limiet in Windows is 260 tekens, maar kan worden verhoogd. _Vereiste toegang:_ Windows Administrator-account

Windows Home-gebruikers: Deze limiet kan worden verhoogd door naar Windows Start te gaan en REGEDIT in te typen. Open de Registry Editor en navigeer naar:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem`

Dubbelklik op `LongPathsEnabled` en wijzig de waarde in 1. Als deze niet aanwezig is, klik dan met de rechtermuisknop op de `FileSystem`-sleutel en kies

`Nieuw > DWORD (32-bits) Waarde`

Noem de nieuwe waarde `LongPathsEnabled` met een waarde van 1.

Windows Pro-gebruikers Deze limiet kan worden verhoogd door naar Windows Start te gaan en gpedit.msc in te typen. Open Groepsbeleid bewerken en navigeer naar:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem`

Dubbelklik op `Enable Win32 long paths` en schakel dit in.

OneDrive en SharePoint 400 Unicode-codeunits

### 1.3 **Robuuste uploads**

**Kleinere zip-bestanden** Als het zip-bestand uit meerdere bestanden bestaat, kan het zip-bestand in kleinere zip-bestanden worden gesplitst. Elk afzonderlijk zip-bestand kan afzonderlijk worden geüpload, maar er zal altijd een risico op een netwerk- of verbindingsfout zijn.

**Afzonderlijke bestanden** De [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) is een veiliger manier om te uploaden omdat documenten bestand voor bestand worden geüpload. Dit is ook sneller omdat de bestanden rechtstreeks naar onze backend worden geüpload in plaats van via de browserinterface. Zelfs als een van de bestanden mislukt, worden de bestanden die tot nu toe zijn geüpload, al weergegeven in Catenda. De resterende bestanden gaan de volgende keer uploaden wanneer de uploadtaak wordt uitgevoerd.

## 2. **Zip-uploads met speciale tekens**

Catenda detecteert de codering van het zip-bestand wanneer het wordt uitgepakt, dus als het zip-bestand speciale tekens bevat, worden deze correct geïnterpreteerd wanneer ze worden uitgepakt. Als de speciale tekens niet correct zijn gecodeerd, kunnen zij niet door Catenda worden uitgepakt en zien ze er verminkt uit. Afhankelijk van de service die u gebruikt voor het maken van uw zip-bestand, kunnen uw tekens al dan niet correct zijn gecodeerd. Als uw speciale tekens verminkt zijn, kunt u in het zip-bestand kijken of ze daar correct eruitzien. Als u denkt dat uw tekens correct zijn gecodeerd en niet correct door Catenda worden uitgepakt, kijken we graag naar uw zip-bestand en kijken of we iets kunnen doen. In dit geval kunt u contact opnemen met [support@catenda.com](mailto:support@catenda.com) met details over hoe u uw zip-bestand hebt gemaakt.

### 2.1 **Zip-codering in Windows**

Verschillende versies van Windows gebruiken verschillende zip-coderingen. De Engelse versie gebruikt bijvoorbeeld de coderingsstandaard IBM-437 en de pt-BR-versie gebruikt IBM-850. Als uw Windows-installatie uw zip-bestanden niet correct codeert, hebt u wellicht meer succes met een service van derden zoals [7zip](https://7-zip.org/download.html) of [WinRAR](https://www.win-rar.com/download.html?&L=0) om uw zip-bestanden met de juiste codering te maken.

## 3. **Voltooid maar niets gebeurde**

Hoewel het importeren van een zip-bestand is voltooid, kunnen er verschillende redenen zijn waarom er geen verandering zichtbaar is in de tabel met documenten. Dit is wat het kan eruitzien wanneer een zip-import is voltooid zonder dat er wijzigingen zijn aangebracht.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/03-completed-but-nothing-happened.png)

Dit is wat het rechtermenu van de zip-importpagina in deze situatie kan eruitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/04-completed-but-nothing-happened.png)

### 3.1 **Overgeslagen mappen**

Als een map met dezelfde naam als een map in het zip-bestand al bestaat op de locatie waar een map wordt geprobeerd uit te pakken, wordt het maken van de map overgeslagen en wordt er geen nieuwe map gemaakt. Alle documenten in de map met dezelfde naam als in Catenda worden geüpload naar de bestaande map in het Catenda-project.

### 3.2 **Overgeslagen bestanden**

Als in het uploadvenster voor zip-bestanden de optie Overslaan en doorgaan is gekozen en er bestaat al een document met dezelfde naam als het bestand dat uit het zip-bestand wordt geüpload, wordt het overgeslagen en gaat het volgende bestand uitpakken.

### 3.3 **Ontbrekende documenten**

Als documenten onder ontbrekende documenten worden vermeld, betekent dit dat de documenten succesvol zijn gemaakt, maar niet kunnen worden weergegeven. De documenten waarnaar de bestanden zijn geüpload, kunnen sindsdien zijn verwijderd. Het kan ook zijn dat de uploader geen toegang meer heeft tot de documenten waarnaar de bestanden zijn geüpload. _Vereiste toegang:_ Leestoegang

## 4. **Schadelijke bestandstypen**

Wanneer een bestand in het zip-bestand een mogelijk schadelijk bestandstype heeft, wordt het niet geüpload. Dit is wat de zip-importpagina kan eruitzien wanneer schadelijke bestandstypen worden geprobeerd te uploaden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/05-harmful-filetypes.png)

Dit is wat het rechtermenu op de zip-importpagina kan eruitzien wanneer een schadelijk bestand wordt geprobeerd te uploaden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/06-harmful-filetypes.png)

De volgende bestandstypen die mogelijk schadelijk zijn, zijn niet toegestaan.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa; width: 229px; padding: 8px;"><h1 id="h_711fb2a104"><b>Schadelijke indelingen</b></h1></td><td style="background-color: #e3e7fa; width: 142px; border-left: 1px solid #c6c9c0; padding: 8px;"><h1 id="h_581e5e19b4">Extensies</h1></td><td style="background-color: #e3e7fa; border-left: 1px solid #c6c9c0; padding: 8px;"><h1 id="h_766841ac5d">Opmerkingen</h1></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Scripts</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>php</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Windows-uitvoerbare bestanden</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>exe</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Windows-installatiepakketten</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>msi</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Batchscripts</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>bat</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Opdrachtscripts</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>cmd</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>DOS-uitvoerbare bestanden</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>com</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Screensaver-uitvoerbare bestanden</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>scr</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>PowerShell-scripts</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ps1</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Windows-snelkoppelingen</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>lnk</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Het klikken op een gedownloade koppeling kan naar een uitvoerbaar bestand leiden zonder dat het eruitziet als een uitvoerbaar bestand.</p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Java-uitvoerbare bestanden</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>jar</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr></tbody></table></div>

## 5. **Onvoldoende toegang**

De juiste toegang is vereist voor het uitpakken van de inhoud van het zip-bestand. _Vereiste toegang:_ Schrijftoegang

Dit is wat de zip-importpagina kan eruitzien wanneer u onvoldoende toegang hebt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/07-insufficient-access.png)

Dit is wat het rechtermenu op de zip-importpagina kan eruitzien wanneer u onvoldoende toegang hebt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/08-insufficient-access.png)
