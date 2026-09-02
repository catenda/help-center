# Veelgestelde vragen over aangepaste velden

Hier worden de beperkingen van hoe aangepaste velden kunnen worden gebruikt, uitgelegd.

## 1. **Project \<=> Project**

Aangepaste velden hebben een unieke id binnen een project en kunnen daarom niet van het ene project naar het andere worden uitgewisseld. Zelfs als aangepaste velden in beide projecten dezelfde naam hebben, zal de id uniek zijn en wordt het veld niet herkend.

## 2. **Onderwerpenbord \<=> Onderwerpenbord**

Wanneer een aangepast veld is ingeschakeld voor twee onderwerpenborden binnen hetzelfde project, kunnen onderwerpen tussen de borden worden verplaatst en het veld blijft behouden.

## 3. **Aangepaste velden op onderwerpen exporteren**

Aangepaste velden op onderwerpen kunnen op de volgende manieren worden geëxporteerd

### 3.1 **Onderwerp PDF-export**

Waarden van aangepaste velden worden weergegeven in de PDF-export van onderwerpen

### 3.2 **Onderwerp BCF-export**

Aangepaste velden zijn nog niet opgenomen in de geëxporteerde BCF. Aangepaste velden zullen deel uitmaken van de BCF 4-standaard wanneer deze wordt vrijgegeven. Na de release zullen wij en andere BCF-tools die de standaard volgen, eraan werken het veld beschikbaar te stellen voor uitwisseling.

### 3.3 **​Onderwerp Excel-export**

Voor elk aangepast veld in het onderwerpenbord wordt een kolom toegevoegd.

### 3.4 **API**

Aangepaste velden in onderwerpenborden [kunnen worden geconfigureerd](https://developers.catenda.com/topic-api/update-a-topic-board) via de API. Aangepaste velden op onderwerpen [kunnen worden geconfigureerd](https://developers.catenda.com/topic-api/update-topic) via de API. Informatie over aangepaste velden op onderwerpen kan via de API worden opgehaald.

### 3.5 **Rapportactie**

Aangepaste velden op onderwerpen zijn alleen beschikbaar voor export via PDF-, BCF- of Excel-export en via de API.

## 4. **Aangepaste velden op Documenten exporteren**

Aangepaste velden op Documenten kunnen op de volgende manieren worden geëxporteerd

### 4.1 **Rapportactie**

Wanneer de on demand reports-functie is aangevraagd om voor een project in te schakelen, wordt de rapportactie beschikbaar gesteld. Als het rapport is geconfigureerd met de naam van het aangepaste veld, kunnen informatie over aangepaste velden van Documenten die in de Documenten-tabel zijn geselecteerd, naar een rapport worden geëxporteerd en in een van de beschikbare rapportformaten worden opgeslagen.

### 4.2 **API**

Aangepaste velden op Documenten zijn alleen beschikbaar voor export via de rapportactie.

### 4.3 **Document downloaden**

Aangepaste velden op Documenten zijn alleen beschikbaar via de rapportactie. Wanneer Documenten worden gedownload via de downloadactie in de Documenten-tabel, wordt het originele document gedownload. Catenda wijzigt het document op geen enkele manier, dus aangepaste velden worden ook niet als metagegevens toegevoegd.
