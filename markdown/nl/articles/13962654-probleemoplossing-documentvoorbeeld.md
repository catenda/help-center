# Probleemoplossing documentvoorbeeld

## 1. **1. Kan geen verbinding met server maken**

Wanneer een document wordt geopend, kan het documentvoorbeeld grijs worden weergegeven met een gecentreerd bericht dat zegt:

`Kan geen verbinding met server maken`

Dit probleem kan ook lijken op ernstige platformvertraging of laadwielen die nooit stoppen met draaien, vooral op de pagina **Collecties** of wanneer u de **Modelslijst** in de 3D Viewer probeert te laden.

### 1.1 **1.1 Waarom dit gebeurt**

Er is een beperking op het specifieke internetnetwerk of de VPN-verbinding die wordt gebruikt. De beveiligingsinstellingen op het netwerk staan toe dat de hoofdwebsite van Catenda wordt geladen, maar blokkeren of weigeren volledig de achtergrondverbindingen die het platform gebruikt om zware projectgegevens en 3D-modellen te verzenden en ontvangen. Omdat deze achtergrondgegevensstromen worden onderbroken, kan het systeem de informatie niet laden, waardoor het platform onbepaald ophangt of een verbindingsfout weergeeft.

### 1.2 **1.2 Stap voor probleemoplossing**

Bevestig of het netwerk de blokkade veroorzaakt, probeer het platform of documentvoorbeeld te laden terwijl u met een ander netwerk bent verbonden, zoals een mobiel hotspot-netwerk. Als de pagina en gegevens daar normaal worden geladen, blokkeert de primaire netwerkconfiguratie het verkeer.

### 1.3 **1.3 Permanente oplossing voor netwerkbeheerders**

Om dit probleem permanent op te lossen, moet de netwerkconfiguratie worden bijgewerkt om het achtergrondverkeer van Catenda volledig te ondersteunen, inclusief alle subdomeinen en vereiste poorten. Klik [hier](https://support.catenda.com/en/articles/13927294-network-recommendation) voor meer informatie over whitelisting-vereisten en portspecificaties (inclusief verplichte Port 443 TCP/UDP-configuraties).

## 2. **2. Fout bij het laden van document (Time-out gelezen)**

Wanneer een document wordt geopend, kan de webviewer die het documentvoorbeeld weergeeft een bericht weergeven dat zegt: **"Time-out gelezen"**.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hq07qt4s/01-2-error-loading-document-read-timed-out.png)

`Time-out gelezen`

### 2.1 **2.1 Waarom dit gebeurt**

De beveiligingsinstellingen op het gebruikte netwerk staan alleen het adres van de hoofdwebsite van Catenda toe. De firewall van het netwerk herkent of staat geen wildcard-instelling toe (die automatisch alle adressen toestaat die eindigen op `.catenda.com`), dus het blokkeert het specifieke, afzonderlijke achtergrondadres dat documentvoorbeelden verwerkt (`webviewer.catenda.com`). In plaats van de verbinding onmiddellijk af te wijzen, negeert de firewall de aanvraag totdat de browser stopt met wachten, wat resulteert in een time-outfout.

### 2.2 **2.2 Stap voor probleemoplossing**

Bevestig of de netwerkconfiguratie de time-out veroorzaakt, probeer het documentvoorbeeld te laden terwijl u met een ander netwerk bent verbonden, zoals een mobiel hotspot-netwerk. Als het voorbeeld daar normaal wordt geladen, blokkeert de firewallconfiguratie van het primaire netwerk het verkeer.

### 2.3 **2.3 Permanente oplossing voor netwerkbeheerders**

Om dit probleem permanent op te lossen, moet de firewallconfiguratie van het netwerk worden bijgewerkt om het specifieke adres dat voor documentvoorbeelden wordt gebruikt, expliciet toe te staan (`webviewer.catenda.com`). Klik [hier](https://netw) voor meer informatie over whitelisting-regels en portspecificaties.
