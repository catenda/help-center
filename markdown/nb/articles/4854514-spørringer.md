# Spørringer

> En forklaring på spørringsfunksjonen i 2D-verktøylinjen

En spørring er en måte å laste objekter fra deler av modeller i Catenda Hub uten å laste hele modellen.

IFC-filer har en tendens til å være lettere versjoner av modellen i redigeringsprogrammet den ble eksportert fra, og er ofte lett nok til å vises i nettleseren hvis de ikke inneholder objekter med mye geometri.

## 1. **Når skal jeg opprette en spørring?**

Likevel kan det oppstå en situasjon der du opplever at ytelsen er begrenset. Dette kan skyldes en rekke faktorer, for eksempel stor geometri som nevnt før, men også å prøve å laste mange modeller samtidig (100+) og nå grensen for hva enheten din kan håndtere. Når det gjelder innlasting av modeller, er det ofte minne som kreves. Spesielt på mobile enheter med begrenset minne kan dette være tilfelle, men selv gjennomsnittlige systemer med 16 GB RAM kan gå tom for minne når mange modeller lastes.

## 2. **Opprette en spørring**

Spørringer kan enten opprettes fra [2D-viseren](https://support.catenda.com/en/articles/4854537-2d-viewer) eller fra et egenskapsbibliotek. Med [2D-viseren](https://support.catenda.com/en/articles/4854537-2d-viewer) kan du enkelt velge et område i prosjektet som du vil laste. Med et egenskapsbibliotek kan du enkelt velge objekter med en bestemt egenskap som du vil laste.

## 3. **2D-viser-spørring**

For å opprette en spørring fra [2D-viseren](https://support.catenda.com/en/articles/4854537-2d-viewer), åpner du 2D-visningen av en modell:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/01-2d-viewer-query.png)

Dette vil hjelpe deg med å forstå fra hvilken plassering i prosjektet objektene dine vil bli valgt. Det er tre forskjellige måter å lage spørringer i 2D-viseren på. Hvis du høyreklikker i 2D-viseren, åpnes [menyen 2D-viser-interaksjoner](https://support.catenda.com/en/articles/4854537-2d-viewer#h_bfa30db456). Her kan du velge fra følgende spørringer: [Kryssende rom](#h_bade07829c) [Kryssende etasje](#h_6127f099ac) Den tredje spørringen kan opprettes med [rullegardinmenyen for 2D-viservalg](https://support.catenda.com/en/articles/4854537-2d-viewer#h_042dc145fa) Her kan du velge: rektangelvalg som lar deg opprette følgende spørring: [Rektangelvalg](#h_33afc95ee3)

### 3.1 **Kryssende rom-spørring**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/02-intersecting-space-query.png)

1. Høyreklikk på et rom
1. Velg _Kryssende rom_

Dette vil laste all geometri som krysser den aksealjusterte avgrensningsboksen til rommet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/03-intersecting-space-query.png)

### 3.2 **Kryssende etasje-spørring**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/04-intersecting-storey-query.png)

1. Høyreklikk i viseren
1. Velg _Kryssende etasje_

Dette vil laste all geometri inne i topp- og bunnplanene til etasjen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/05-intersecting-storey-query.png)

### 3.3 **Rektangelvalg**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/06-rectangle-selection.png)

1. Klikk på knappen for spørring-rektangel.
1. Klikk, dra og slipp for å tegne et rektangel.
1. Angi modellene du vil laste i spørringspopover.

_Spørringspopover_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/07-rectangle-selection.png)

1. Velg gjeldende Etasje eller Full høyde.
1. Velg Hvilken som helst, Ekstern eller Intern.
1. Slå alle modeller på eller av.
1. Velg hvilke modeller du vil inkludere i spørringen.
1. Opprett spørring.

## 4. **Egenskapsbibliotek-spørring**

Når du har synkronisert ditt [egenskapsverdibibliotek](https://support.catenda.com/en/articles/4670252-property-value-library), kan du klikke på objektantallet ved siden av egenskapsverdien og velge fra hvilken(e) modell(er) du ønsker å lage en spørring om objekter med denne egenskapsverdien.

## 5. **Redigere en spørring**

Spørringer kan redigeres ved å velge spøringsmenyen i [revisjonsvalgeren](https://support.catenda.com/en/articles/4670279-revision-selector#h_fcf1c5a080).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/58rq5x2c/08-editing-a-query.png)

Her vil du se de forskjellige spørringene du har lastet i denne økten. For å redigere en spørring, klikker du på redigeringsknappen til høyre for spørringen din. Siden spørringer bare laster et begrenset sett med objekter, er det ikke mulig å arbeide med modeller fra modell-fanen og spørringer samtidig. Hvis du vil arbeide med modeller fra modell-fanen, klikker du på Gjenopprett 3D. Dette vil fjerne spørringen og laste hele modellen i stedet.

## 6. **Lagre spørringer**

For å lagre spørringen din for å fortsette arbeidet med den senere, opprett et 3D-øyeblikksbilde i kommentarinndelingen for en sak eller opprett et bokmerke. Hvis du vil fortsette arbeidet med spørringen din i neste Catenda-økt, kan du spille av bokmerket eller øyeblikksbildet.
