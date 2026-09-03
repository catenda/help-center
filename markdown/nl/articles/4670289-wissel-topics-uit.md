# Wissel topics uit

Je kunt de actie voor het uitwisselen van topics vinden in het [menu voor nieuwe item-acties](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_8c642e051a) rechtsboven in een topic board. Het menu voor het uitwisselen van topics kan er zo uitzien:

![Bestandsgebaseerde uitwisseling nieuw topic exchange topics geschiedenis import bcf export topics verbind met een bcf client synchroniseer topics rechtstreeks met elke BCF-compatibele client met behulp van de onderstaande URL](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/01-intro.png)

## 1. **BCF importeren**

Gebruik de BCF-importactie om BCF-bestanden te importeren. Dit is hoe de BCF-importdialoog eruit kan zien:

![Import BCF upload bcf file: select file browse selct board generate new types and statuses from the BCF-file](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/02-import-bcf.png)

Catenda is 100% toegewijd aan open standaarden. Op basis hiervan hebben we import en export van BCF (BIM-samenwerkingsformat) geïmplementeerd. Dit betekent dat de gebruiker topics van/naar andere software die dit formaat ondersteunt, kan importeren en exporteren (bijvoorbeeld Solibri, Navisworks en vele anderen). Je kunt bijvoorbeeld een bestand met botsingscontrolgegevens voor hetzelfde model dat in een ander softwareprogramma is gemaakt, importeren. Op deze manier kun je je workflow in Catenda voortzetten.

**Meerdere topics per bcf** Eén BCF-bestand kan meerdere topics bevatten

**Maximale bestandsgrootte** De maximale BCF-bestandsgrootte die kan worden geïmporteerd is 500 MB.

### 1.1 **BCF-bestand uploaden**

Klik op bladeren om een BCF-bestand te selecteren dat u wilt uploaden

### 1.2 **Board selecteren**

Selecteer het topic board waarnaar u het topic wilt importeren.

### 1.3 **Nieuwe typen en statussen van het BCF-bestand genereren**

Als uw BCF-bestand statussen en typen bevat die niet in het topic board bestaan, kunt u deze automatisch maken door dit selectievakje in te schakelen. _Vereiste toegang:_ Volledige toegang tot het topic board

Als uw BCF-bestand statussen en typen bevat die niet in het topic board bestaan, worden de niet-bestaande statussen/typen losgekoppeld als dit selectievakje uitgeschakeld blijft. Nadat het importeren is voltooid, kunt u de losgekoppelde statussen/typen aan bestaande statussen/typen toewijzen.

_Meerdere statussen/typen tegelijk koppelen_ Als er losgekoppelde statussen/typen in een topic board aanwezig zijn, ziet u een oranje waarschuwingsbericht dat er losgekoppelde velden in een topic board aanwezig zijn. _Vereiste toegang:_ Projectbeheerder

![Topics there are unlinked fields in this topic board click here to link](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/03-generate-new-types-and-statuses-from-the-bcf-file.png)

Door op de koppeling te klikken, gaat u naar het gebied [losgekoppelde velden](https://support.catenda.com/en/articles/4670277-topic-board-settings#h_3bd7e3e759) van de [instellingen van het topic board](https://support.catenda.com/en/articles/4670277-topic-board-settings) waar u alle velden van één soort tegelijk aan een bestaande waarde kunt koppelen.

## 2. **Topics exporteren**

U kunt topics exporteren door in het [menu voor nieuwe item-acties](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_8c642e051a) rechtsboven in een topic board de optie topics exporteren te kiezen, of door een topic in de topicslijst te selecteren en de exportoptie in het [menu voor geselecteerde item-acties](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_b5c00c149b) boven het topic board te kiezen. De dialoog voor het exporteren van topics kan er zo uitzien:

![Export topics all topics from the current topic board current filter selected topics bcf excel pdf v3.0](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/04-export-topics.png)

> **Opmerking:** Topics kunnen slechts tegelijk vanuit één topic board worden geëxporteerd.

### 2.1 **Filteropties**

**Alle topics van het huidige board**

**Huidig filter**

**Geselecteerde topics**

### 2.2 **BCF exporteren**

Afhankelijk van welke versie van BCF u kiest, kunt u verschillende bestandstypen krijgen. BCF v3.0 en v2.1 produceren een .bcf terwijl v2.0 een .bcfzip produceert

### 2.3 **Excel exporteren**

Het is mogelijk om topics naar Excel te exporteren. Er is één rij per topic en één kolom per kolom in de tabelweergave van het topic board. De volgorde van de kolommen zal hetzelfde zijn als de standaardkolomvolgorde van het topic board [tabelweergave](https://support.catenda.com/en/articles/6941099-table-view-in-an-topic-board#h_3102328063).

> **Opmerking:** Geen afbeeldingen en alleen het laatste opmerking in een topic worden geëxporteerd.

### 2.4 **PDF exporteren**

Klik [hier](https://support.catenda.com/en/articles/9784934-exporting-topics-to-pdf) om meer te lezen over het exporteren van topics naar PDF

## 3. **Rapportenpagina**

Met de rapportenpagina is het mogelijk om aangepaste rapporten te maken, niet alleen over topics maar ook over documenten. De rapportenpagina is een on-demand-functie die voor lopende projecten kan worden ingeschakeld. Nieuwe projecten die zijn gemaakt op basis van een templateproject waarvan deze functie is ingeschakeld, hebben deze functie niet ingeschakeld. Deze rapporten kunnen vervolgens niet alleen naar Excel en PDF, maar ook naar veel meer bestandsformaten worden geëxporteerd. Klik [hier](https://support.catenda.com/en/articles/12303098-reports-page) om meer te lezen over de rapportenpagina

## 4. **Verbind met een BCF-client**

Als u Catenda Hub als BCF-server gebruikt, kunt u zich rechtstreeks met andere software verbinden. Hier kunt u topics direct naar en van Catenda versturen en ontvangen zonder topics te hoeven exporteren en importeren. Dit maakt gebruik van de gestandaardiseerde (van buildingSMART International) BCF API. Voorbeelden van software die dit ondersteunt zijn Navisworks, Revit, Archicad en Solibri. In deze software kunt u de algemene URL naar onze server gebruiken, namelijk [https://api.catenda.com/](https://api.catenda.com/), waarna u alle topic boards van al uw projecten krijgt. Dit kan al snel een lange lijst worden om doorheen te scrollen, dus om u te helpen stellen we de koppeling naar uw huidige topic board in dit menu ter beschikking. Als u in plaats daarvan deze koppeling gebruikt, kunt u gemakkelijk de topics vinden die u zoekt.
