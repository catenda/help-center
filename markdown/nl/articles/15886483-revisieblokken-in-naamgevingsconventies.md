# Revisieblokken in naamgevingsconventies

> Leer dynamische blokken in naamgevingsconventies voor mappen configureren. Zie hoe bestanden als opeenvolgende revisies worden gestapeld, waar u de resultaten bekijkt en hoe u aangepaste velden gebruikt met de documentidentificatie uit.

Wanneer een naamgevingsconventie is ingeschakeld in een map, worden bestanden automatisch gescand tijdens het uploadproces om ervoor te zorgen dat ze voldoen aan specifieke structurele patronen. Als lokale bestandsnamen blokken bevatten die constant veranderen met elke nieuwe versie, kan de map worden geconfigureerd om deze dynamisch te herkennen.

Wanneer correct geconfigureerd, worden verschillende lokale bestanden met verschillende versiegegevens geüpload naar dezelfde documentcontainer. In plaats van voor elke kleine bestandswijziging afzonderlijke, rommelige documentvermeldingen te maken, herkent het platform automatisch de gedeelde basisnaam en stapelt deze als opeenvolgende revisies onder één document.

## 1. Waar u de documentgegevens kunt bekijken

Nadat bestanden zijn geüpload, scheidt het platform schoon statische documentgegevens van wijzigende versiegegevens:

### 1.1 **1.1 Het informatieMenu aan de rechterkant**

Als u een document in de bestandslijst selecteert en het tabblad **Bestandsinfo** aan de rechterkant van de pagina uitvouwt, worden de gesegmenteerde gegevens weergegeven.

**1.1.1 Documentinformatie** Dit geeft gegevens weer van de naamgevingsblokken die gedurende de hele levensduur van het document constant blijven.

**1.1.2 Revisie-informatie** Dit extraheert en geeft automatisch de waarden van wijzigende blokken rechtstreeks uit de geüploade bestandsnaam weer.

**1.1.3 Revisienaam** Dit geeft expliciet de onveranderbare, originele lokale bestandsnaam weer, precies zoals deze op de lokale vaste schijf was opgeslagen.

### 1.2 **1.2 De Documenttabel**

Als u originele bestandsnamen in één oogopslag in de belangrijkste bestandslijsten wilt weergeven, kan de kolom **"Revisienaam"** (Originele naam) worden ingeschakeld. Aanpassingen van kolombreedte zijn strikt gekoppeld aan individuele accountprofielen, wat betekent dat een werkruimte kan worden aangepast zonder de standaardweergave voor de rest van het team te wijzigen.

## 2. Wisselende revisieblokken configureren

Om een naamgevingsconventie te bouwen die wijzigende versiemarkeringen schoon isoleren van statische documentnamen, moeten individuele blokgedragingen worden aangepast in de conventie-instellingen. Navigatie naar de naamgevingsconventiespagina wordt voltooid in de projectinstellingen. _Vereiste toegang:_ Beheerder

### 2.1 De kritische instelling: documentidentificatie uitschakelen

Voor elk blok dat per revisie wijzigt, moet de **documentidentificatie** worden ingesteld op **Uit**. Deze instelling zorgt ervoor dat het platform de tekens tijdens het uploaden valideert om consistentie te behouden, maar verwijdert deze wanneer de daadwerkelijke documentnaam wordt voltooid.

Dit is het exacte mechanisme dat ervoor zorgt dat bestanden met verschillende versietekenreeksen netjes kunnen worden gestapeld als revisies in plaats van volledig nieuwe documenten te genereren.

### 2.2 Aangepaste veldbroninnen gebruiken

Om nauwkeurig te bepalen welke tekens in deze dynamische blokken zijn toegestaan, worden aangepaste velden toegewezen als de **bron** van het blok. Afhankelijk van de volgniveaubehoeften kunnen verschillende veldtypen worden gebruikt om validatiebeperkingen af te dwingen:

**2.2.1 Aangepaste tekstvelden** Deze optie staat een flexibel of vast aantal tekens toe voor standaard alfanumerieke invoer.

**2.2.2 Vervolgkeuzelijst Aangepaste velden** Deze optie beperkt het blok tot een vooraf gedefinieerde set specifieke waarden, tot maximaal 1.000 opties. Dit is erg voordelig wanneer korte bestandsnaamcodes moeten worden toegewezen aan volledige, beschrijvende namen in het platform.

**3.2.3 Aangepaste getalvelden** Deze optie forceert het blok om strikt getallen te accepteren. Let op dat hoewel dit alleen numerieke invoer garandeert, het systeem elk geldig getal accepteert in plaats van een strikte, stap-voor-stapvolgvolgorde af te dwingen.
