# Desktop Connector Probleemoplossing - Niet alle mappen zijn gedownload

In dit artikel vindt u informatie over een specifieke fout die optreedt bij het gebruik van de [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector). Zie [hier](https://app.intercom.com/a/apps/areracg3/knowledge-hub/all-content?activeContentId=11844906&activeContentType=article&editorMode=view&native_content=false) voor andere Desktop Connector-probleemoplossingen.

In de taak zelf kunt u het volgende zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/01-intro.png)

`Niet alle mappen zijn gedownload, klik om fouten te bekijken.`

## 1. **Niet-ondersteunde tekens**

In dit geval geeft het logboekbestand de volgende fout:

`De syntaxis van bestandsnaam, mapnaam of volumelabel is onjuist.`

Documenten kunnen in Catenda worden beperkt met een naamconventie. Mappen kunnen niet worden beperkt. Zonder het gebruik van een naamconventie kunnen Documenten met elke naam worden geüpload. In dit geval kan Catenda de bestandsextensie van het document mogelijk niet hebben geregistreerd. Mappen met elke naam kunnen worden gemaakt. Het kan daarom voorkomen dat de Desktop Connector probeert een bestand of map met een teken te maken dat niet mag worden gebruikt in een pad in Windows.

Typische problemen treden op met de volgende tekens: `<` - kleiner dan `>` - groter dan `:` - dubbele punt `"` - dubbel aanhalingsteken `|` - verticale streep of pijp `?` - vraagteken `*` - asterisk

Zie hier voor een uitgebreide lijst van wat gereserveerd is in Windows: [https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file](https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file)

## 2. **Ontbrekende map of netwerkpad**

In dit geval geeft het logboekbestand de volgende fout:

`Fout: Het netwerkpad is niet gevonden. : '<path>'`

In deze situatie mislukt de overdracht onmiddellijk. Dit gebeurt omdat het programma probeert een map te bereiken die niet meer toegankelijk is. Omdat het "pad" volledig verbroken is, kan het programma de download niet eens beginnen. Er zijn drie hoofdredenen waarom uw map een "Dood spoor" is geworden:

### 2.1 **1. De ontbrekende map (meest voorkomend)**

De lokale map die eerder was geselecteerd, is verplaatst, hernoemd of verwijderd. Wanneer u naar de locatie van de map in Verkenner gaat, is de map er niet. De Desktop Connector probeert uw bestand op te slaan, vindt "niets" en stopt.

### 2.2 **2. De verbroken "symbolische koppeling" (de verborgen omleiding)**

Een symbolische koppeling ziet eruit als een normale map maar werkt als een permanent "bordje" dat Windows naar een ander locatie omleidt (zoals een bedrijfsserver). Wanneer u deze probeert te openen, wordt de volgende fout in een pop-up weergegeven:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/02-2-the-broken-symbolic-link-the-hidden-redirect.png)

`Locatie is niet beschikbaar... Het netwerkpad is niet gevonden.`

**Hoe ze uit elkaar te houden:** Net als .lnk-bestanden hebben symbolische koppelingen een klein blauw "snelkoppelingspijltje" in de linkeronderhoek van het mappictogram of klik met de rechtermuisknop op de snelkoppeling en selecteer Eigenschappen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/03-2-the-broken-symbolic-link-the-hidden-redirect.png)

In het tabblad Algemeen zijn de velden naam en doel grijs weergegeven:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/04-2-the-broken-symbolic-link-the-hidden-redirect.png)

**Waarom het mislukt** Het "bordje" staat op uw computer, maar de bestemming (zoals een `Z:` schijf of een server) is niet verbonden.

### 2.3 **3. De verbroken Windows-snelkoppeling (.lnk-bestand)**

Een standaard Windows-snelkoppeling is een klein bestand dat "wijst" naar een map ergens anders. Dit kunnen koppelingen naar een map op uw eigen harde schijf of naar een map op een verre bedrijfsserver zijn.

**Hoe ze uit elkaar te houden:** Net als symbolische koppelingen hebben zowel map- als stationsnelkoppelingen een klein blauw "snelkoppelingspijltje" in de linkeronderhoek van het mappictogram of klik met de rechtermuisknop op de snelkoppeling en selecteer Eigenschappen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/05-3-the-broken-windows-shortcut-lnk-file.png)

In het tabblad Algemeen kijkt u naar het veld Doel: _lokale snelkoppeling_ Het doel begint met een stationsletter (bijv. `C:\Users\...` of `D:\Data`).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/06-3-the-broken-windows-shortcut-lnk-file.png)

_Netwerksnelkoppeling_ Het doel begint met een serverpad (bijv. `\\ServerName\Folder`) of een toegewezen netwerkstationsletter (bijv. `Z:\ProjectData`).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/07-3-the-broken-windows-shortcut-lnk-file.png)

Ander gedrag bij dubbel klikken Windows handelt een "verbroken" lokale snelkoppeling veel sneller af dan een "verbroken" netwerksnelkoppeling.

**Lokale snelkoppeling (de "verwijderde" fout):** Als de map op uw computer is verwijderd, weet Windows dit onmiddellijk. Wanneer op de snelkoppeling wordt dubbelgeklikt, wordt de volgende fout onmiddellijk weergegeven:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/08-3-the-broken-windows-shortcut-lnk-file.png)

**`Het item waarop deze snelkoppeling verwijst, is gewijzigd, verplaatst of verwijderd.`**

**Netwerksnelkoppeling (de "vastgelopen" fout):** Als de snelkoppeling naar een bedrijfsserver verwijst en u bent offline (of uit VPN), weet Windows niet meteen dat de bestemming ontbreekt. Windows zal eerst proberen de server op het netwerk te "vinden". Uw muiscursor kan veranderen in een laadcirkel en het venster kan 30-60 seconden "hangen" of bevriezen voordat uiteindelijk het volgende wordt weergegeven:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/09-3-the-broken-windows-shortcut-lnk-file.png)

**`Het station of de netwerkverbinding waarop deze snelkoppeling verwijst, is niet beschikbaar.`**

Als de Desktop Connector wordt verteld een van deze snelkoppelingen te gebruiken terwijl het doel ontbreekt of het netwerk inactief is, zal het programma uiteindelijk "time-out" wachten totdat Windows het pad heeft gevonden. Omdat de Desktop Connector geen geldig doel kan vinden om mee te beginnen, stopt het programma en meldt de fout.

### 2.4 **Hoe op te lossen**

**Identificeer de onderbreking** Probeer de doelmap in Windows Verkenner te openen. Als de doelmap ontbreekt, moet u een nieuwe map op die locatie maken of een ander map in de Desktop Connector selecteren.

**Opnieuw verbinden of opnieuw selecteren** Als er een fout "Netwerkpad niet gevonden" of "Station niet beschikbaar" verschijnt, bevestigt u de verbinding met het netwerkpad of station. Ga naar "Deze pc" en zorg ervoor dat uw netwerkstations (zoals `Z:`) actief zijn. Controleer of externe USB-schijven of harde schijven correct zijn aangesloten. Als ze een rood X hebben, dubbelklikt u erop om opnieuw verbinding te maken. Als het netwerkstation niet actief is en u weet welk netwerk het station zich op bevindt, verbindt u opnieuw met het netwerk door een kabel aan te sluiten, via wifi in te schakelen of als u een VPN gebruikt, controleert u of de VPN actief is. Als het station niet meer beschikbaar is, selecteert u een ander doelmap in de Desktop Connector die beschikbaar is op de lokale computer of het netwerk.

**Verwijderen/hernoemen en opnieuw maken** Als een lokale map of snelkoppeling "vastgelopen" blijft (u ziet het, maar kunt het niet openen) zelfs na een herstart: Hernoem de problematische map of snelkoppelingbestand (bijv. hernoem `ProjectData` naar `ProjectData_OLD`) of verwijder het. Maak een gloednieuwe standaardmap met dezelfde naam. Start de overdracht opnieuw. De Desktop Connector detecteert de verse, gezonde map en hervaart de normale werking.

**Waarom is er geen tijdelijke map gemaakt in plaats van de ontbrekende map?** In andere situaties maakt de Desktop Connector een map met `_restricted` eraan toegevoegd wanneer er iets misgaat. Er is echter een technisch verschil in hoe Windows "ontbrekende" locaties verwerkt:

De `_restricted` map wordt alleen gemaakt als de map "fysiek" aanwezig is maar "vergrendeld" (zoals een deur naar een kamer die dicht is gegrendeld). In dat geval kan het programma de deur zien en besluit een nieuwe te bouwen (`_restricted`) ernaast.

In het geval van het ontbrekende pad is het anders. De map is niet meer daar of het "bordje" (symbolische koppeling) dat is geselecteerd wijst naar een lege locatie. Voor het programma is het niet alleen vergrendeld - de hele "kamer" ontbreekt uit het gebouw. Omdat er geen "deur" om mee te beginnen is, kan het programma geen `_restricted` versie maken en moet het stoppen.

## 3. **Ontbrekend aankoppelpunt**

In dit geval geeft het logboekbestand de volgende fout:

`Fout: Kon geen deel van het pad '<path>' vinden.`

Als de map niet kan worden geopend, probeert Windows het "bordje" naar een netwerklocatie te volgen en wordt de volgende fout weergegeven:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/10-missing-mount-point.png)

`<Pad> is niet toegankelijk.`
`Het netwerkpad is niet gevonden`

In deze situatie maakt de Desktop Connector automatisch een nieuwe map met "_restricted" eraan toegevoegd (bijv. `ProjectData_restricted`).

Dit gebeurt wanneer een map op de computer eigenlijk een "aankoppelpunt" (deuropening) naar een ander station is. Voorbeelden van andere stations kunnen zijn:

- USB-stick,
- Externe harde schijf
- Netwerkvolume dat momenteel niet is verbonden.

Windows "herinnert" zich dat de map bestaat, maar omdat de fysieke schijf ontbreekt, wordt de map een "Spookmap". De Desktop Connector detecteert dat de map aanwezig is maar kan er niet naar schrijven. Om te voorkomen dat uw gegevens verloren gaan, wordt een schaduwmap gemaakt met het `_restricted` achtervoegsel zodat uw bestanden een veilige plek hebben om naar toe te gaan.

Hier zijn enkele typische situaties waarin dit kan gebeuren:

- De map was toegewezen aan een station (zoals `D:`) dat is losgekoppeld.
- De map verwijst naar een netwerkshare (zoals `Z:`) die offline is of een VPN vereist.
- Een cloudservice (Dropbox, OneDrive of ander samenwerkingsgereedschap synch-services) heeft een "plaatshoudende" map gemaakt die momenteel niet actief is.
- Een beveiligingsprogramma van het bedrijf "beschermt" de map tegen wijziging door apps van derden.

Om te controleren of uw map een "Spookmap" is, klikt u met de rechtermuisknop op de map en selecteert u Eigenschappen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/11-missing-mount-point.png)

Kijk naar het veld Type in het tabblad Algemeen: Een normale map zegt "Mapmap" terwijl een spookmap zegt "Gekoppeld volume".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/12-missing-mount-point.png)

Wanneer op de gekoppelde map wordt dubbelgeklikt, wordt de volgende fout onmiddellijk weergegeven:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/13-missing-mount-point.png)

**`Locatie is niet beschikbaar`** of

**`Het netwerkpad is niet gevonden`** `<Pad> is niet beschikbaar dus de koppeling is verbroken`

### 3.1 **Hoe op te lossen**

Handmatig de map opnieuw maken Als de map "vastgelopen" blijft zelfs na een herstart:

1. Hernoem de problematische map (bijv. hernoem `ProjectData` naar `ProjectData_OLD`).
1. Maak een gloednieuwe map met de originele naam (`ProjectData`).
1. De Desktop Connector detecteert de verse, gezonde map en hervaart de normale werking zonder het `_restricted` achtervoegsel.

**Verbind de hardware of het netwerk opnieuw** Ga naar "Deze pc" en zorg ervoor dat uw netwerkstations (zoals `Z:`) actief zijn. Controleer of externe USB-schijven of harde schijven correct zijn aangesloten. Als ze een rood X hebben, dubbelklikt u erop om opnieuw verbinding te maken. Als het netwerkstation niet actief is en u weet welk netwerk het station zich op bevindt, verbindt u opnieuw met het netwerk door een kabel aan te sluiten, via wifi in te schakelen of als u een VPN gebruikt, controleert u of de VPN actief is. Als het station niet meer beschikbaar is, selecteert u een ander doelmap in de Desktop Connector die beschikbaar is op de lokale computer of het netwerk.

**Verwijderen/hernoemen en opnieuw maken** Als een lokale map of snelkoppeling "vastgelopen" blijft (u ziet het, maar kunt het niet openen) zelfs na een herstart: Hernoem de problematische map of snelkoppelingbestand (bijv. hernoem `ProjectData` naar `ProjectData_OLD`) of verwijder het. Maak een gloednieuwe map met de originele naam (`ProjectData`). Start de overdracht opnieuw. De Desktop Connector detecteert de verse, gezonde map en hervaart de normale werking zonder het `_restricted` achtervoegsel.
