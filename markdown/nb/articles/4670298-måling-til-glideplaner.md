# Måling til glideplaner

Denne artikkelen beskriver hvordan måleverktøyene i 3D-viseren kan brukes til ikke bare å måle på objekter, men også til å måle på elementer fra glideplaner som rutenett eller justeringer. Dette er hvordan det kan se ut etter at måleverktøy som tøymål, punktmål og lasermål brukes til å måle mellom glideplan-annotasjonslinjer, glideplan-overflater og objekter fra modeller.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/01-intro.png)

## 1. **Komme i gang med måling til glideplaner**

Følg disse trinnene for å komme i gang med måling til glideplaner.

### 1.1 **Forhåndsvisning av glideplaner**

Glideplaner som kan måles til er definert i IFC-modellene som gjøres tilgjengelige i prosjektet. Hvis modeller med glideplaner er tilgjengelige, blir [glideplan-rullegardinmenyen](https://support.catenda.com/en/articles/4670327-sliding-plane-dropdown) synlig i øvre høyre hjørne av [3D-viseren](https://support.catenda.com/en/articles/8227211-3d-viewer) og kan se slik ut:

![Glideplan-rullegardin i 3D-viseren](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/02-previewing-sliding-planes.png)

Forbered glideplanene du skal måle til ved å åpne rullegardinmenyen og klikke på øyeikonet for å forhåndsvise annotasjonslinjer for et rutenett eller en justering.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/03-previewing-sliding-planes.png)

### 1.2 **Anbefalte innstillinger for måling**

Nøyaktige målinger er viktige for å unngå misforståelser i prosjektet. Det kan derfor være en god idé å gjøre en vurdering av innstillingene før du starter med måling.

_3D-viser-innstillinger_ Rullegardinmenyen for 3D-viser-innstillinger finnes ved girdikonet øverst til høyre i 3D-viseren:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/04-recommended-settings-for-measuring.png)

Siden glideplan-linjer inneholder tynne annotasjonslinjer og tekst som ofte er følsomme for ren gjengivelse i et 3D-miljø, anbefales følgende [3D-viser-innstillinger](https://support.catenda.com/en/articles/5784718-3d-viewer-settings#h_16d759320b) for å gjøre målingsopplevelsen så god som mulig.

_3D-viser-innstillinger - Skjermkvalitet_ Standardkvalitet anbefales fordi høy kvalitet endrer forholdet mellom piksler som vises av Catenda og piksler som er synlige på skjermen, noe som kan ha negativ effekt på nøyaktig måling.

_3D-viser-innstillinger - Kantutjevning_ Det anbefales å endre denne innstillingen fra standardinnstillingen FXAA til minst 2x MSAA eller mer. Tynne linjer i 3D er ofte en utfordring å vise fordi jo mer diagonal en tynn linje er, jo mer tannaktig blir kantene. Å endre kantutjevningsinnstillingen har ingen effekt på målenøyaktigheten, men det kan hjelpe med å se linjene bedre fordi de tannaktige kantene kan gjøre at tynne linjer blir så tynne at de blir vanskelige å visualisere.

_3D-viser-innstillinger - Grunnhøyde_ Spesielt når du prøver å måle til en annotasjonslinje under bakken, kan det være en god idé å enten velge et miljø uten bakkeplan eller flytte bakkeplanet ned under høyden på glideplanen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/05-recommended-settings-for-measuring.png)

_Anbefaling for applikasjonsprogramvare_ Uavhengig av hvilken [zoomskala](https://support.catenda.com/en/articles/13927149-application-software-recommendation?q=3d+v) som er konfigurert i nettleseren som brukes til måling i 3D-viseren, anbefales det å ikke endre nettleserens zoomskala under måling, da dette kan bidra til å redusere målenøyaktigheten. Angi nettleseren til ønsket zoomskala og vær nøye med å oppdatere siden etter hver zoomskalaendring, selv om zoomskalaendringen ble gjort i en annen fane eller hvis den ble endret tilbake til det den var opprinnelig.

## 2. **Måling til glideplan-annotasjonslinjer**

Hvert av måleverktøyene kan brukes på glideplan-annotasjonslinjer.

### 2.1 **Gripeatferd**

Når du holder musepekeren nær en annotasjonslinje med bullseye aktivert, vil bullseye gripes til en annotasjonslinje. Når du griper til slutten av en annotasjonslinje, blir senteret av bullseye grønt. Når du griper til midten av en annotasjonslinje, blir senteret av bullseye rødt.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/inline-96b1b8f9c6c8.png" width="290"/> --- <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/inline-d30d54cd3f18.png" width="290"/>

### 2.2 **Lasermål på annotasjonslinjer**

Dette er hvordan det kan se ut når du bruker lasermålverktøyet på annotasjonslinjen til et rutenett.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/06-laser-measure-on-annotation-lines.png)

_Måling vertikalt og horisontalt langs annotasjonslinjesegmentet_ Legg merke til at bullseye ser flatt ut i vertikal retning når du holder musepekeren over en annotasjonslinje. Når du måler annotasjonslinjer, er det vertikalplanet langs annotasjonslinjen som måles. Den grønne linjen er den horisontale linjen på dette planet, og den røde linjen er den vertikale linjen på dette planet og følger annotasjonslinjsegmentet

For både den vertikale måleinjen (rød) og målelinjen horisontalt langs segmentet (grønn) oppfører måleinjen seg forskjellig avhengig av objekter som påtreffes. Hvis det er objekter i en retning langs måleinjen, vises en linje som måler avstanden til nærmeste objekt. Hvis det er objekter i begge retninger langs måleinjen, vises en linje som måler avstanden mellom disse objektene.

_Måling horisontalt i skrå vinkel til annotasjonssegmentet_ Den blå linjen er linjen som kan observeres ved å gå i skrå vinkel til annotasjonssegmentet som måles horisontalt. Hvis det er objekter i en retning langs måleinjen, vises en linje som måler avstanden til nærmeste objekt. Hvis det er objekter i begge retninger, vises linjer som måler avstanden til nærmeste objekt i hver retning, ettersom denne linjen krysser annotasjonslinjen selv og måler til den.

_Manglende måling_ Hvis objekter mangler i noen av måleretningene, vises koordinater også som med punktmålet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/07-laser-measure-on-annotation-lines.png)

### 2.3 **Tøymål på annotasjonslinjer**

Tøymålverktøyet kan brukes til å måle både fra objekt til annotasjonslinje eller fra en annotasjonslinje til en annen linje. Finn for eksempel avstanden mellom to rutenettlinjer ved å måle fra et punkt på en rutenettalinje til et punkt på en annen rutenettalinje.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/08-tape-measure-on-annotation-lines.png)

### 2.4 **Punktmål på annotasjonslinjer**

Punktmålet kan brukes på annotasjonslinjer akkurat som ethvert annet måleverktøy.

## 3. **Måling til glideplan-overflater**

Aktiver glideplan-overflaten ved å trykke på den hvite sirkelen der annotasjonslinjesirkelen er. Flere glideplan-overflater kan åpnes samtidig. Lasermålinger som er gjort på objekter, kan utvides og ekspanderes til annotasjonslinjen. Bruk deretter "Lasermål" eller "Tøymål" til å måle til glideplan-overflater som er aktivert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ygqcyt9v/09-measuring-to-sliding-plane-surfaces.gif)
