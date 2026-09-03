# 3D Viser-innstillinger

3D Viser-innstillingene finnes i øverste høyre hjørne av [3D Viser](https://support.catenda.com/en/articles/8227211-3d-viewer).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/01-intro.png)

> **Merk:** Sørg for at maskinvaren og programvaren som Catenda er åpnet på, er konfigurert [som anbefalt](https://support.catenda.com/en/articles/6921941-hardware-recommendation) da dette kan påvirke hvordan viseren vises.

## 1. **Aktivering av 3D Viser**

3D Viseren kan åpnes på en av følgende måter: Aktiver 3D-panelet med panelknappene øverst til høyre (Shift + 2).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/02-enabling-the-3d-viewer.png)

Aktiver en 3D-modell fra Dashbord-siden.

Aktiver en 3D-modell fra viser-kolonnen i modellene-tabellen. (Bildet ovenfor)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/03-enabling-the-3d-viewer.png)

Velg modeller på modeller-siden og bruk 3D-handlingen med valgte modeller på modeller-siden.

Aktiver et 3D-dokument fra viser-kolonnen i dokumenter-tabellen på dokumenter-siden. Klikk på tannhjulikonet for å vise **3D Viser-innstillinger.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/04-enabling-the-3d-viewer.png)

## 2. **Gjengivelse**

Slik kan gjengivelsesmenyen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/05-rendering.png)

### 2.1 **Vis rom**

_Av som standard_ - [Aktiver og deaktiver rom](https://support.catenda.com/en/articles/4670315-how-can-i-show-spaces-in-catenda-hub). Rom er fortsatt valgbare i 2D-viseren hvis de er i modellen.

### 2.2 **Visningskvalitet**

Forholdet mellom antall piksler som visningsvinduet sier at det viser, og antall piksler som fysisk er del av skjermen din, er ofte det samme. I så fall har ikke visningskvalitetsalternativet mye forskjell. Hvis antall piksler som visningsvinduet sier det har, og antall piksler der visningsvinduet vises på en skjerm, er forskjellig, kan visningskvaliteten påvirke billedskarpigheten. For skjermer av følgende typer kan forholdet mellom antall piksler som visningsvinduet sier det har, og antall piksler som skjermen faktisk har, være annerledes:

- Mobilenheter
- Visteknologier som påvirker pikseltetthet som Apple Retina.
- Høy DPI-skjermer

> **Merk:** Sørg for at maskinvaren og programvaren som Catenda er åpnet på, er konfigurert [som anbefalt](https://support.catenda.com/en/articles/6921941-hardware-recommendation) da dette kan påvirke nøyaktigheten av diagonale linjer i viseren.

_Standardkvalitet_ Med standardvisningskvaliteten er piksler som visningsvinduet sier det har, det samme antallet fysiske piksler som viser visningsvinduet på skjermen. For skjermer som tilbyr å vise visningsvinduet over flere fysiske piksler enn visningsvinduet sier det har, kan denne innstillingen få bildet til å virke mindre presist. Denne modusen er raskere og mindre krevende for enheten din.

_Høy kvalitet_ Med høy visningskvalitet vises visningsvinduet over hele mengden fysiske piksler som er tilgjengelige på delen av skjermen som viser visningsvinduet. For skjermer som tillater at visningsvinduet vises over flere piksler enn det sier, gir dette den beste visuelle kvaliteten, men kan være mer krevende for ytelsen.

### 2.3 **Anti-aliasing**

Pikselnøyaktighet i utglattingen av diagonale linjer i rekkefølge etter nøyaktighet. Merk at jo mer nøyaktig, desto vanskeligere blir det å vise for systemet.

- FXAA
- 2x MSAA
- 4x MSAA
- 8x MSAA

> **Merk:** Sørg for at maskinvaren og programvaren som Catenda er åpnet på, er konfigurert [som anbefalt](https://support.catenda.com/en/articles/6921941-hardware-recommendation) da dette kan påvirke nøyaktigheten av diagonale linjer.

### 2.4 **Inkrementell tegning**

Under rotasjon blir ikke-vitale objekter som glass i vinduer og små monteringer midlertidig skjult for å forbedre ytelsen. Dette gjør det mulig å rotere i enorme modeller med lite forsinkelse. Når mange objekter er lastet inn i 3D-viseren, er dette alternativet et must.

### 2.5 **Dybdeskygger**

Når dette alternativet er aktivert, vises skygger med en radius på ca. 5 cm mellom overlappingen av objekter. Sørg for å ha objektene dine i virkelig verden skalert for å få bedre effekt. Med store overflater som der en vegg møter et gulv, er dette ikke så synlig før kameraet beveger seg nær krysset. Med små geometrier som møbler, stålbjelker og metallmonteringer er dette en gamechanger. Dette alternativet har typisk liten effekt på ytelsen.

### 2.6 **Utvided synsvidde**

Med massive modeller som er flere kilometer lange, ender objektene ofte opp utenfor standardkuttstanden på 2 kilometer. Når modellen er aktivert, forsøker kameraet å posisjonere seg langt nok unna til å vise alt, og hvis objektene er langt nok unna, kan de bli kuttet av og ingenting vises før kameraet beveger seg nærmere objektene. Med dette alternativet blir objekter opptil 50 kilometer unna kameraet synlige! Merk at dette kan påvirke ytelsen. I infrastrukturprosjekter er dette alternativet ofte et must!

### 2.7 **Ugjennomsiktighetsgrad**

_5% Standard_ - Hvor mye du kan se gjennom objekter som er halvgjennomskinnelige

### 2.8 **Punktsky**

Punktbudsjett: _1000000 Standard_ - Hvor mange punkter fra punktskyen kan vises samtidig. Standardverdien er mer enn nok for de fleste punktskyer, men innstillingen er der hvis det trengs mer.

## 3. **Navigasjon**

Slik kan navigasjonsmenyen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/06-navigation.png)

### 3.1 **Gåmodus**

_1,6 meter standard_ - Binder viseren til bakken under deg når du går gjennom modellen med gjennomgangsmodus. Lar deg gå opp trapper.

### 3.2 **Gåhastighet**

_3 m/s standard_ - Hvor raskt viseren beveger seg i gjennomgangsmodus. Som referanse er en tabell med generelle hastigheter inkludert nedenfor.

### 3.3 **Vertikalfart**

_1,5 m/s standard_ - Vertikal bevegelseshastighet når du beveger deg opp og ned ved hjelp av X og C.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Fremgangsmåte</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Typisk hastighet (m/s)</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Typisk hastighet (mph)</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Gange</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>1,5</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3,4</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Standard</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>3</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>6,7</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Løping</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>5</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>11</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Sykling</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>7</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>15</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Bil</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>13 - 30</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>29 - 67</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Tog</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>56</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>125</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Fly</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>250</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>560</p></td></tr></tbody></table></div>

### 3.4 **Rotasjonshastighet**

_40°/s standard_ - Hvor raskt viseren roterer rundt kameraet når du drar på skjermen

### 3.5 **Synsvinkel**

_60° standard_ - Denne innstillingen kan være god å gjøre større i innvendige områder som små rom slik at du kan se mer. Det kan også være godt å begrense denne innstillingen i modeller med store avstander 2 KM (1,2 mil) og mer siden det vil tillate deg å se objekter som er lenger unna mer presist.

### 3.6 **Tilbakestill navigasjonsinnstillinger**

Sett alle navigasjonsinnstillinger tilbake til standardposisjonen

## 4. **Miljø**

Slik kan miljømenyen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/32hqb8n2/07-environment.png)

### 4.1 **Miljøinnstilling**

De valgte miljøinnstillingene bestemmer hvilken himmel som vises når du ser opp, og hvilken bakke som vises når du ser ned. Merk at horisonten ofte er mer uttalt når perspektivvisningsalternativet er valgt, da horisonten med ortogonal visningsvinkel er uendelig langt borte, så det ses bare når kameraet vender nøyaktig i horisontal retning.

_Klart_ Med den klare innstillingen vises en klar himmel når du ser opp og en gressig bakkeplan når du ser ned i bakgrunnen av visningsvinduet.

_Delvis skyet_ Med den delvis skyet innstillingen vises en skyet himmel når du ser opp og en gressig bakkeplan når du ser ned i bakgrunnen av visningsvinduet.

_Nøytral_ Med den nøytrale innstillingen vises lysegrå himmel når du ser opp og en mørk grå bakkeplan når du ser ned i bakgrunnen av visningsvinduet. Denne innstillingen er flott for modeller som har lyse farger og er vanskelig å skille fra en lys bakgrunn.

_Ingen_ Med ingen-innstillingen vises en gradient som går fra en lettgrønn himmel når du ser opp til en hvit bakkeplan når du ser ned i bakgrunnen av visningsvinduet.

### 4.2 **Bakkeplan**

Bakkeplan-alternativene er utgrådd for Ingen-innstillingen fordi denne ikke har et bakkeplan. I innstillinger der bakkeplanet vises, blir en overflate synlig på et bestemt høydepunkt som mottar skygger fra objekter som er lastet inn i 3D-viseren.

_Under modell -_ Standard Med dette alternativet vises bakkeplanoverflaten på en høyde på 0 meter over havnivå.

_På høyde_ Med dette alternativet kan bakkeplanoverflaten flyttes opp med positive verdier og ned med negative verdier. Dette er flott i situasjoner der overflaten klipper gjennom en kjeller eller for objekter som på annen måte er under havnivå.
