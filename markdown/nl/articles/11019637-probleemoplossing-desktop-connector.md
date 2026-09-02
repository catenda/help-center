# Probleemoplossing Desktop Connector

## 1. **Naamconventie**

Als een naamconventie is ingeschakeld op de uploadmap of een bovenliggende map van de uploadmap, moet de lokale bestandsnaam aan de conventie voldoen om de upload door te zetten. Als de bestandsnaam niet aan de conventie voldoet, wordt het volgende foutbericht weergegeven.

**`<Bestandsnaam> komt niet overeen met naamconventie`**

Upload het bestand handmatig via de browser om te zien welke onderdelen van de bestandsnaam ontbreken.

## 2. **Serverprojectlocatie**

Er kunnen verschillende fouten optreden bij het openen van de serverprojectlocatie.

### 2.1 **Projectlocatie leeg**

Om uw lokale bestanden met een project te synchroniseren, moet u minstens één map in het Documenten-gedeelte van het project op Catenda Hub hebben.

### 2.2 **Project niet gevonden**

Wanneer de Desktop Connector voor het eerst wordt geopend, worden alle projecten waartoe de gebruiker toegang heeft, geladen. Zonder te verversen worden dezelfde projecten de volgende keer weergegeven. Als de gebruiker toegang tot het project heeft verloren, verschijnt het volgende bericht wanneer u probeert een serverlocatie in te stellen voor een upload- of downloadtaak voor het project.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/01-project-not-found.png)

Vraag een projectbeheerder om toegang tot het project. Om erachter te komen wie u moet contacteren voor projecttoegang, vraagt u ondersteuning bij Catenda.

## 3. **Documentweergave**

### 3.1 **Maplocatie**

Documentnamen kunnen in Catenda met een naamconventie beperkt worden. Mappen kunnen niet beperkt worden. Zonder het gebruik van een naamconventie kunnen documenten met een willekeurige naam worden geüpload. In dit geval kan Catenda de bestandsextensie van het document mogelijk niet registreren. Mappen met willekeurige namen kunnen worden aangemaakt. Het kan daarom voorkomen dat de Desktop Connector problemen ondervindt met tekens in namen die gereserveerd zijn voor Windows-functionaliteit.

Typische problemen ontstaan met de volgende tekens: `/` - Voorwaartse schuine streep `\` - Achterwaartse schuine streep Deze tekens worden gebruikt in de bestandspadhiërarchie in Windows, waardoor het document op de verkeerde plaats terecht komt.

Voor een uitgebreide lijst met wat in Windows is gereserveerd, zie: [https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file](https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file)

### 3.2 **Onjuiste document- of mapnaam**

Documentnamen kunnen in Catenda met een naamconventie beperkt worden. Mappen kunnen niet beperkt worden. Zonder het gebruik van een naamconventie kunnen documenten met een willekeurige naam worden geüpload. In dit geval kan Catenda de bestandsextensie van het document mogelijk niet registreren. Mappen met willekeurige namen kunnen worden aangemaakt.

Het kan daarom voorkomen dat de Desktop Connector problemen ondervindt met tekens in namen die gereserveerd zijn voor Windows-functionaliteit.

Typische problemen ontstaan met de volgende tekens: `.` - Punt

Omdat mappen en bestanden die eindigen met een punt niet zijn toegestaan in Windows, wordt de punt aan het einde van de map of het bestand verwijderd in het document dat wordt gemaakt na een downloadtaak. Bij het uploaden wordt de punt verwijderd in het proces van het vinden van de juiste map om naar te uploaden, zodat het gedownloade document op de juiste plaats terecht komt bij bidirectionele synchronisatie.

- Spatie

Op Catenda is het mogelijk om handmatig een spatie aan het einde van een document- of mapnaam toe te voegen, terwijl spaties aan het einde van document- en mapnamen in Windows worden verwijderd. Als een spatie op Catenda is opgenomen, is de naam van de gedownloade map anders dan de naam van de map in Catenda, die een spatie kan bevatten. Wanneer een uploadtaak op diezelfde map wordt gemaakt, wordt een nieuwe map gemaakt omdat de bestand- of mapnaam in Windows geen spatie aan het einde heeft.

## 4. **Geen uploaden of downloaden**

### 4.1 **Document bestaat al**

Wanneer het importsysteem een item dat eerder is gemaakt niet kan verwerken, treedt de volgende fout op.

Desktop Connector `Document bestaat al (code: 25)`

Logbestand

```
<Berichtnummer>|<Datum/Tijd>|ERROR|1|BimRequestProviderService|Call API-foutstatuscode Conflict reden: {"error":{"code":25,"message":"Document bestaat al"}}.url: https://api.bimsync.com/v2/projects/<ProjectGUID>/libraries/<LibraryGUID>/items? | Data: {"parentId":"<LibraryItemGUID>","name":"<Naam>","document":{"type":"<Type>","filename":"<Bestandsnaam>"}} 
```

Dit kan specifiek voorkomen wanneer u probeert een map met de titel "`A`" voor de tweede keer te uploaden, waar al een map met die titel bestaat. Het wordt aanbevolen om elke lokale map met de naam "A" te wijzigen in iets als "A\_". Op deze manier zal de taak geen problemen ondervinden. Nadat de uploadtaak is voltooid, wijzigt u de gesynchroniseerde versie terug naar "A" op Catenda, zodat beide zijden hetzelfde blijven.

### 4.2 **Niet alle mappen zijn gedownload**

In de taak zelf kan het volgende worden gezien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/02-not-all-folders-have-been-downloaded.png)

`Niet alle mappen zijn gedownload, klik om fouten weer te geven.`

Klik [hier](https://support.catenda.com/en/articles/13772277-desktop-connector-troubleshooting-not-all-folders-have-been-downloaded) om meer te lezen over wat het probleem met deze fout kan zijn.

## 5. **Nieuwste versie ingetrokken**

De nieuwste versie van één van de documenten is ingetrokken. In dit geval is er geen foutbericht in het logbestand.

## 6. **Gelijktijdige synchronisatie**

Om gegevens uit een document te extraheren voor het uploaden of een document met gedownloade gegevens bij te werken, moet de Desktop Connector toegang tot het document hebben. Als het document door een ander proces wordt gebruikt, kan het document niet worden geopend. Als het document wordt gebruikt, kan de volgende fout zichtbaar zijn:

Desktop Connector `Het proces kan niet tot het bestand '<Bestandspad>' komen omdat het door een ander proces wordt gebruikt.`

Logbestand

```
<Berichtnummer>|<Datum/Tijd>|ERROR|1|ExceptionHandleExtension|Er is een fout opgetreden --> System.IO.IOException: Het proces kan niet tot het bestand '<Bestandspad>' komen omdat het door een ander proces wordt gebruikt.
```

Processen die bestanden in gebruik kunnen hebben, kunnen het volgende omvatten: Een andere taak van de Desktop Connector zelf Bestandssynchronisatieservices zoals Dropbox, OneDrive of Google Drive Andere CDE-synchronisatietools. Programma's die het bestand geopend hebben voor bewerking.

Als het document in gebruik is, stopt de taak en gaat niet verder als het één van de bestanden niet kan openen. Als er meerdere taken zijn gepland, probeert het opnieuw op het volgende geplande moment.

## 7. **Activiteitsbewaking**

### 7.1 **Taak gestart**

Taken die handmatig worden gestart door in de taak op 'Nu uploaden/Downloaden' te klikken, geven een status van 'Uploaden' of 'Downloaden' zodra de taak is gestart. Voor zowel handmatig gestarte taken als volgens schema gestarte taken verschijnt een bericht dat er als volgt uitziet in het logbestand wanneer een taak wordt gestart:

Logbestand `<Berichtnummer>|<Datum/tijd>|INFO|1|LoggingExtension|logging starten`

### 7.2 **Taak wordt uitgevoerd**

Taken die handmatig worden gestart door in de taak op 'Nu uploaden/Downloaden' te klikken, geven een status van 'Uploaden' of 'Downloaden' zolang de taak nog wordt uitgevoerd. Voor zowel handmatig gestarte taken als volgens schema gestarte taken kan de status van taken die worden uitgevoerd worden gezien door het netwerkgebruik van de toepassing te controleren.

**Initiële opstartsase** Een Desktop Connector-taak bevindt zich in de initiële opstartfase wanneer deze tussen 1 kilobyte per seconde en 1 megabyte per seconde wordt gebruikt. Tijdens deze fase is het netwerkgebruik van de taak minimaal.

Downloadtaak Tijdens de initiële opstartfase worden documenten op de serverlocatie gecontroleerd op lokale bestanden om te zien of er serverbestanden zijn gewijzigd waarvoor een nieuwe versie moet worden gedownload, of of er nieuwe bestanden aan de serverzijde zijn die naar het lokale systeem moeten worden gedownload.

Uploadtaak Tijdens de initiële opstartfase worden documenten op de serverlocatie gecontroleerd op lokale bestanden om te zien of er lokale bestanden zijn gewijzigd waarvoor een nieuwe versie moet worden geüpload, of of er nieuwe lokale bestanden zijn die naar Catenda moeten worden geüpload.

**Actieve fase** Een Desktop Connector-taak bevindt zich in de actieve fase wanneer deze meer dan 1 megabyte per seconde gebruikt. Tijdens deze fase kan het netwerkgebruik van de taak gevolgen hebben voor de rest van het systeem.

Downloadtaak Tijdens de actieve fase downloadt de Desktop Connector actief bestand voor bestand van Catenda naar het lokale systeem.

Uploadtaak Tijdens de actieve fase uploadt de Desktop Connector actief bestand voor bestand van het lokale systeem naar Catenda.

### 7.3 **Taak onderbroken**

Taken die handmatig worden uitgevoerd door in de taak op 'Nu uploaden/Downloaden' te klikken, geven een statusbericht in de taak weer wanneer de taak is onderbroken, zowel wanneer de taak is voltooid als wanneer er een fout is opgetreden.

**Taak voltooid** De enige manier om te zien of taken succesvol zijn voltooid, is door de taak handmatig uit te voeren. Klik op 'Nu uploaden/Downloaden' in de taak om dit te doen. Wanneer de taak succesvol is voltooid, wordt in de taak een bericht weergegeven dat alle documenten zijn geüpload of gedownload.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/03-task-halted.png)

> **Opmerking:** Er zijn geen berichten in het logbestand voor voltooide taken. De enige manier om te zien of taken die volgens schema zijn gestart, zijn onderbroken, is door het netwerkgebruik van de toepassing te controleren.

**Er is een fout opgetreden** Een gedetailleerdere beschrijving van fouten die zijn opgetreden, kan worden gezien door het logbestand op eventuele recente fouten te controleren.

**Netwerkgebruik** De enige manier om te zien of taken die volgens schema zijn gestart, zijn onderbroken, is door het netwerkgebruik van de toepassing te controleren. Als de Desktop Connector meer dan 2 minuten minder dan 1 kilobyte per seconde heeft gebruikt, zijn alle taken die werden uitgevoerd waarschijnlijk onderbroken en zullen zij niet opnieuw starten. Voor taken die volgens schema terugkerend zijn, wordt een nieuwe taak gestart als de Desktop Connector wordt uitgevoerd op de volgende datum en tijd waarop de taak is gepland.

## 8. **Verbinding tussen de Connector en Catenda**

### 8.1 **Verbinding bij het starten van een taak**

Als er een probleem is met de internetverbinding, wordt de upload- of downloadtaak niet automatisch opnieuw gestart en wordt deze opnieuw uitgevoerd op het volgende geplande moment. Dit kan ook handmatig worden gestart door naar de taak te gaan en op de upload- of downloadknop te klikken.

**Geen verbinding** Als er geen internetverbinding beschikbaar is wanneer u een upload- of downloadtaak start, verschijnt de volgende fout in de upload- of downloadtaak.

`Host onbekend`

**Verbinding verbroken tijdens taakstart** Als de verbinding met internet verloren is gegaan of is verbroken wanneer u probeert verbinding te maken met de Catenda-servers, wordt de volgende fout weergegeven:

`De SSL-verbinding kon niet tot stand worden gebracht`

**Gebruikte verbindingsmethode hangt af van voorkeurmethode beschikbaar bij taakstart** Wanneer een taak wordt gestart, wordt een verbinding tot stand gebracht met de voorkeurverbindingsmethode voor internet. Bijvoorbeeld, als er een bekabelde verbinding en een WiFi-verbinding beschikbaar zijn wanneer een taak wordt uitgevoerd, heeft de bekabelde verbinding vaak de voorkeur. Als er alleen een WiFi-verbinding beschikbaar is wanneer een taak wordt gestart en een bekabelde verbinding wordt aangesloten terwijl deze wordt uitgevoerd, blijft de connector de initiële verbinding gebruiken zolang deze beschikbaar is en schakelt deze niet over naar een voorkeurverbinding die later beschikbaar wordt.

### 8.2 **Verbinding tijdens taak - Verbinding met internet**

**Internetverbinding niet langer beschikbaar zonder fallback** Als er bij het begin van de taak slechts één verbinding beschikbaar was of als er helemaal geen verbinding beschikbaar was (bijv. vliegtuigmodus), kan de volgende fout verschijnen.

`Er is een fout opgetreden bij het verzenden van de aanvraag.`

**Internetverbinding niet langer beschikbaar met fallback** Als er bij het begin van de taak meerdere verbindingen beschikbaar waren en de verbinding die werd gebruikt is verbroken, probeert de connector over te schakelen naar een van de andere beschikbare verbindingen. Tijdens deze omschakeling kan de volgende fout verschijnen:

`Fout bij kopiëren van inhoud naar stream`

### 8.3 **Verbinding tijdens taak - Desktop Connector-sessietime-out**

De Catenda Desktop Connector heeft een vastgestelde sessielimiet van 10 minuten. Dit betekent niet dat een taak na 10 minuten een time-out krijgt, omdat de Desktop Connector meestal met meerdere korte sessies tegelijk werkt. Grote bestanden, zoals puntenwolken met een maximum van 25 GB tegelijk, kunnen ervoor zorgen dat een sessie langer duurt dan normaal en kan er een time-out optreden als deze niet binnen de limiet van 10 minuten wordt geüpload.

`Time-out van 600 seconden verstrijkt`

Neem in deze situatie contact op met ondersteuning. Er is een bètaversie beschikbaar op aanvraag die hiermee kan helpen. Met de bètaversie is deze limiet iets verhoogd, maar zelfs met de bètaversie kan er een time-out optreden, maar dan na 15 minuten.

`Time-out van 900 seconden verstrijkt`

### 8.4 **Verbinding tijdens taak - Verbinding met Catenda**

Afhankelijk van de snelheid van de verbinding aan de up-/downloadzijde of aan de Catenda-zijde kan het uploaden van bestanden korter of langer duren. Als de taak te lang duurt, kan de verbinding een time-out krijgen.

**Catenda Time-out** Als de overdracht te lang duurt, treedt er een time-out op en verschijnt de volgende fout:

`Een verbindingspoging is mislukt omdat de verbonden partij niet correct heeft gereageerd na een bepaalde periode, of omdat de tot stand gebrachte verbinding is mislukt omdat de verbonden host niet heeft gereageerd. (api.bimsync.com:443)`

Neem in deze situatie contact op met ondersteuning. Er is een bètaversie beschikbaar op aanvraag die hiermee kan helpen.

**Catenda-service niet beschikbaar** Als de Catenda API temporair geen aanvragen kan ontvangen op het moment dat de Desktop Connector deze probeert te bereiken, wordt het volgende bericht weergegeven.

Desktop Connector `HTTP-FOUT 503 Service niet beschikbaar`

Logbestand

```
<Berichtnummer>|<Datum/Tijd>|ERROR|1|BimRequestProviderService|Call API-foutstatuscode ServiceUnavailable reden: <html><head><meta http-equiv="Content-Type" content="text/html;charset=ISO-8859-1"/><title>Error 503 Service Unavailable</title></head><body><h2>HTTP ERROR 503 Service Unavailable</h2><table><tr><th>URI:</th><td>/v2/projects/10005fce182e49cb91342571746cf1fc/libraries/9a90887d954a444c8ed45695707b2fbd/items</td></tr><tr><th>STATUS:</th><td>503</td></tr><tr><th>MESSAGE:</th><td>Service Unavailable</td></tr><tr><th>SERVLET:</th><td>-</td></tr></table>
```

Dit is vaak het gevolg van servers die overbelast zijn en veel gebruikers die tegelijk aanvragen proberen in te dienen.

**Gateway time-out** Een gateway time-out betekent vaak dat de Catenda API soepel werkt en dat de initiële aanvraag correct is ontvangen. De service die deze aanvraag moest afhandelen, heeft echter niet op tijd gereageerd.

Desktop Connector `504 Gateway Time-Out` Logbestand

```
<Berichtnummer>|<Datum/Tijd>|ERROR|1|BimRequestProviderService|Call API-foutstatuscode GatewayTimeout reden: <html><head><title>504 Gateway Time-out</title></head><body><center><h1>504 Gateway Time-out</h1></center></body></html>
```

Dit kan erop wijzen dat Catenda aanvragen correct ontvangt, maar dat de server die aanvragen verwerkt, temporair niet beschikbaar is. Dit kan soms gebeuren wanneer niet genoeg machines beschikbaar zijn, waarna er automatisch meer kunnen worden gestart, maar dit kan enige tijd duren.

**Toegangstoken verlopen** Catenda-toegangstokens moeten na een uur worden vernieuwd. Wanneer in de Desktop Connector wordt genavigeerd, is dit meestal niet problematisch omdat het token automatisch wordt vernieuwd, maar wanneer een taak wordt gestart die langer dan een uur duurt, kan het toegangstoken dat voor de taak werd gebruikt, een time-out krijgen terwijl de taak nog bezig is. Wanneer dit gebeurt, wordt het volgende foutbericht weergegeven in de Desktop Connector. Voor taken die langer dan een uur duren, start de taak opnieuw of wacht op de volgende geplande taak om het resterende werk uit te voeren.

Desktop Connector `Uitzondering van type 'BimsyncApp.Exceptions.BimAuthenticatorException' is gegenereerd.`

Logbestand

```
<Berichtnummer>|<Datum/Tijd>|ERROR|1|BimRequestProviderService|Call API-foutstatuscode Unauthorized reden: {"error":{"code":12,"message":"Access token has expired"}}.url: 
```

## 9. **Dit apparaat is momenteel in gebruik**

Bij het downloaden van of uploaden naar een externe schijf geeft Windows een fout wanneer u probeert deze los te koppelen, zeggende dat het apparaat momenteel in gebruik is.

## 10. **Mapmachtigingen**

Voor mappen op het station waar Windows is geïnstalleerd, zijn de juiste mapmachtigingen vereist. Klik met de rechtermuisknop op de map waarnaar u wilt downloaden en sta de juiste machtigingen toe.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/04-folder-permissions.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/05-folder-permissions.png)

In dit geval geeft het logbestand de volgende fout:

`Toegang tot het pad '<Geselecteerde lokale mappad> submap <Pad in lokale map>' is geweigerd`

### 10.1 **Toestemming geweigerd**

Hoewel een map in Windows kan worden geopend, kan Windows een "No-Write-Up"-beleid afdwingen. De Desktop Connector laat u deze map selecteren, maar wanneer de taak wordt uitgevoerd, verschijnt het volgende bericht:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/06-permission-denied.png)

In dit geval wordt de Desktop Connector geblokkeerd van schrijven, ongeacht de machtigingen "Volledig beheer" van de gebruiker.

Als u deze map wilt verwijderen, moet de gebruiker beheerdersrechten toekennen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/07-permission-denied.png)

In sommige situaties kan de map nog steeds worden geopend, terwijl in andere het volgende bericht kan worden weergegeven:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/08-permission-denied.png)

Zelfs bij doorgaan kan het volgende bericht worden weergegeven:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/09-permission-denied.png)

Als u op 'Toch downloaden' klikt, worden de bestanden gedownload, maar kunnen ze niet naar de opgegeven map worden gedownload omdat die map beperkt is.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0emrc0xc/10-permission-denied.png)

Desktop Connector `Status: Omleiding, klik om gedownloade bestanden weer te geven`

Logbestand `Toegang tot het pad '<Pad>' is geweigerd`

Klik op 'Gedownloade bestanden weergeven' om de locatie te openen waar de bestanden zijn gedownload.
