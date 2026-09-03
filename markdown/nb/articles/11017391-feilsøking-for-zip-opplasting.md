# Feilsøking for zip-opplasting

## 1. **Opplasting feilet**

Det anbefales å bruke en kabelforbindelse for opplasting av zip-filer til Catenda. Mange wifi-rutere gjør en god jobb med å sikre at de mottar riktige data, men selv de beste rutere kan slite med svak signal hvis du er langt fra routeren.

### 1.1 **Klarte ikke å prosessere filen**

Under zip-opplastingsprosessen sendes datapakker til Catenda-serveren. Hvis det er et problem med noen av pakkene under prosessen, vises følgende melding: Opplasting feilet! Klarte ikke å prosessere filen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/01-unable-to-process-file.png)

Selv når du er rett ved en WiFi-antenne med en enhet, er det aldri 100 % sikkert at pakken ankommer trygt gjennom luften. Denne effekten forsterkes ved å være lengre vekk fra antennen eller hvis det er gjenstander som vegger mellom enheten og antennen.

_Store filer_ Når store mengder data lastes opp, sendes mange pakker. Hvis selv en av dem ikke ankommer til routeren gjennom luften ordentlig, kan en nettverksfeil vises. Når dette skjer, blir hele opplastingen ugyldig.

### 1.2 **Nettverksfeil**

Viss programvare begrenser antallet tegn som stier til filer i en zip-fil kan ha. Hvis det er et problem med stiestrukturen i zip-filen, vises følgende feil: Opplasting feilet! Nettverksfeil.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/02-network-error.png)

_Pakk ut/pakk inn igjen_ Hvis denne zip-filen ble mottatt fra noen andre, kan det hjelpe å pakke den ut og pakke den inn igjen.

_Kjente grenser (oppdatert desember 2025)_ Microsoft Windows 10/11 Grensen i Windows er 260 tegn, men kan økes. _Tilgang som kreves:_ Windows Administrator-konto

Windows Home-brukere: Denne grensen kan økes ved å gå til Windows Start og skrive REGEDIT Åpne Registerredigering og naviger til:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem`

Dobbeltklikk på `LongPathsEnabled` og endre verdien til 1. Hvis det ikke er der, høyreklikk på `FileSystem`-nøkkelen og velg

`Ny > DWORD (32-bit) verdi`

Gi den nye verdien navn `LongPathsEnabled` med en verdi på 1.

Windows Pro-brukere Denne grensen kan økes ved å gå til Windows Start og skrive gpedit.msc Åpne Rediger gruppepolicy og naviger til:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem`

Dobbeltklikk på `Enable Win32 long paths` og aktiver det.

OneDrive og SharePoint 400 Unicode-kodeenheter

### 1.3 **Robust opplasting**

_Mindre zip-filer_ Hvis zip-filen består av flere filer, kan zip-filen deles inn i mindre zip-filer. Hver separate zip-fil kan lastes opp individuelt, men det vil alltid være en risiko for nettverks- eller tilkoblingsfeil.

_Individuelle filer_ [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) er en sikrere måte å laste opp på, ettersom den laster opp dokumenter fil for fil. Dette er også raskere ettersom filene lastes opp direkte til vår backend i stedet for gjennom nettlesergrensesnittet. Selv om en av filene mislykkes, vil de som ble lastet opp til da allerede vises på Catenda. Resten av filene vil fortsette å lastes opp neste gang opplastingsoppgaven kjøres.

## 2. **Zip-opplastinger med spesialtegn**

Catenda oppdager kodingen av zip-filen når den pakkes ut, så hvis zip-filen har spesialtegn, tolkes de riktig når de pakkes ut. Hvis spesialtegnene ikke ble kodet riktig, kan de ikke pakkes ut av Catenda og vil ende opp med å se skadet ut. Avhengig av hvilken tjeneste du bruker for å opprette zip-filen din, kan tegnene dine være kodet riktig eller ikke. Hvis spesialtegnene dine er skadet, se i zip-filen for å se om de ser riktige ut der. Hvis du tror tegnene dine ble kodet riktig og ikke blir pakket ut riktig av Catenda, er vi glade for å se på zip-filen din og se om det er noe vi kan gjøre. I dette tilfellet ber vi deg om å kontakte [support@catenda.com](mailto:support@catenda.com) med detaljer om hvordan du opprettet zip-filen din.

### 2.1 **Zip-koding på Windows**

Ulike versjoner av Windows bruker ulike zip-kodinger. For eksempel bruker den engelske versjonen kodingsstandarden IBM-437, og pt-BR-versjonen bruker IBM-850. Hvis Windows-installasjonen din ikke koder zip-filene dine riktig, kan du ha bedre hell med å bruke en tredjepartstjeneste som [7zip](https://7-zip.org/download.html) eller [WinRAR](https://www.win-rar.com/download.html?&L=0) for å opprette zip-filene dine med riktig koding.

## 3. **Fullført, men ingenting skjedde**

Selv om en zip-import er fullført, kan det være flere grunner til at ingen endring er synlig i dokumenttabellen. Slik kan det se ut når en zip-import er fullført uten at det er gjort endringer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/03-completed-but-nothing-happened.png)

Slik kan høyremenyen på zip-importsiden se ut i denne situasjonen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/04-completed-but-nothing-happened.png)

### 3.1 **Mapper hoppet over**

Hvis det allerede finnes en mappe med samme navn som en mappe i zip-filen på stedet hvor en mappe skal pakkes ut, hoppes opprettelsen av mappen over og ingen ny mappe opprettes. Alle dokumenter i mappen med samme navn som på Catenda blir lastet opp til den eksisterende mappen i Catenda-prosjektet.

### 3.2 **Filer hoppet over**

Hvis alternativet hopp over og fortsett ble valgt i zip-opplastingsdialogen, og et dokument med samme navn som filen som skal lastes opp fra zip-filen allerede finnes, hoppes det over og neste fil starter utpakkingen.

### 3.3 **Manglende dokumenter**

Hvis dokumenter er oppført under manglende dokumenter, betyr det at dokumentene ble opprettet, men kan ikke vises. Dokumentene som filene ble lastet opp til, kan siden ha blitt fjernet. Det kan også være at opplasteren ikke lenger har tilgang til dokumentene som filene ble lastet opp til. _Tilgang som kreves:_ Lesetilgang

## 4. **Skadelige filtyper**

Når en fil i zip-filen har en potensielt skadelig filtype, vil de ikke bli lastet opp. Slik kan zip-importsiden se ut når skadelige filtyper forsøkes lastet opp:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/05-harmful-filetypes.png)

Slik kan høyremenyen på zip-importsiden se ut når en skadelig fil forsøkes lastet opp:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/06-harmful-filetypes.png)

Følgende filtyper som kan være potensielt skadelige er ikke tillatt.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa; width: 229px; padding: 8px;"><h1 id="h_711fb2a104"><b>Skadelige formater</b></h1></td><td style="background-color: #e3e7fa; width: 142px; border-left: 1px solid #c6c9c0; padding: 8px;"><h1 id="h_581e5e19b4">Filtyper</h1></td><td style="background-color: #e3e7fa; border-left: 1px solid #c6c9c0; padding: 8px;"><h1 id="h_766841ac5d">Kommentarer</h1></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Skript</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>php</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Windows kjørbare filer</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>exe</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Windows-installasjonspakker</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>msi</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Batch-skript</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>bat</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Kommandoskript</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>cmd</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>DOS kjørbare filer</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>com</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Skjermsparer kjørbare filer</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>scr</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>PowerShell-skript</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>ps1</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Windows-snarveier</p></td><td style="width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>lnk</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Hvis du klikker på en nedlastet lenke, kan den koble til en kjørbar fil uten å se ut som en kjørbar fil.</p></td></tr><tr><td style="background-color: #e8e8e8; width: 229px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Java kjørbare filer</p></td><td style="background-color: #e8e8e8; width: 142px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>jar</p></td><td style="background-color: #e8e8e8; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr></tbody></table></div>

## 5. **Utilstrekkelig tilgang**

Riktig tilgang er nødvendig for at zip-innholdet skal pakkes ut. _Tilgang som kreves:_ Skrivetilgang

Slik kan zip-importsiden se ut når det ikke er tilstrekkelig tilgang:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/07-insufficient-access.png)

Slik kan høyremenyen på zip-importsiden se ut når det ikke er tilstrekkelig tilgang:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qsefpf4z/08-insufficient-access.png)
