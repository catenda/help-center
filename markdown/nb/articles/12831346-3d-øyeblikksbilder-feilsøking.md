# 3D-øyeblikksbilder - Feilsøking

## 1. **Viewpoint-innstillinger**

### 1.1 **Objekter**

Objekter som har samme ID og som var valgt, skjult eller isolert, vil være valgt, skjult eller isolert når øyeblikksbildet gjenskapes. Hvis to modeller deler identiske IfcProject-GUID-er (globale identifikatorer), kan konflikter resultere i synlighetsproblemer som hindrer Catenda Hub fra å bestemme hvilke modellelementer som skal vises under gjenskaping av øyeblikksbildet.

### 1.2 **Skjulte objekter**

hvis mer enn halvparten av objektene i en modell er synlige, blir objekter med nye ID-er skjult.

det betyr at hvis du legger til en ny modell med modellvelgeren i en Sak-kommentar-Øyeblikksbilde der mer enn halvparten av objektene i en modell er synlige, kan den tilføyde modellen være helt skjult. For å vise objekter med nye ID-er kan du bruke "vis alle" for å vise modellen etter gjenskaping av Øyeblikksbildet. For å feilsøke og tvinge skjulte modeller til å bli synlige, kan du bruke alternativet "vis alle" i 3D-Viseren. Høyreklikk i 3D-visningsområdet, velg "vis alle" fra kontekstmenyen, og dette bør midlertidig løse synlighetsproblemer forårsaket av konfigurasjonskonflikter.

## 2. **Gjenskap øyeblikksbilde**

Når du spiller av en saks 3D-øyeblikksbilde, kan visse modeller ikke vises. Dette problemet kan stamme fra prosjektproblemer som dupliserte IfcProject-GUID-er. For å løse dette, må du sørge for at hver modell i prosjektet bruker en unik identifikator. Du kan også bruke alternativet "Vis alle" i 3D-viseren som en midlertidig løsning.

### 2.1 **Øyeblikksbilde-modellvelger**

I denne menyen lenker du bare øyeblikksbildet til Catenda-modeller. Hvis riktige modeller ikke ble funnet automatisk, kan de lenkes manuelt her. Selv om flere modeller har samme GUID, kan du velge dem for å aktivere alle i stedet for bare den første. Det endrer ikke innholdet i BCF, så objektene kan fortsatt være skjult når de åpnes i eksterne verktøy.

avhengig av objektsynlighetsinstellingene for Øyeblikksbildet kan tilføyde modeller være helt skjult. Åpne revisjonvelgeren eller modellsiden for å se hvilke modeller som har 3D-knappen aktivert for å se hvilke modeller som er lastet inn i 3D-Viseren etter gjenskaping av Øyeblikksbildet. Selv om de kan være lastet inn, kan alle objekter fra modellen være skjult. Bruk "vis alle"-handlingen for å avsløre skjulte objekter..

## 3. **BCF-import av øyeblikksbilde**

Når en BCF-sak importeres, blir ID-ene til modellene i prosjektet sammenlignet med ID-ene til modellene som er konfigurert i Øyeblikksbildet. Bare modellene med ID-er som er tilstede på importtidspunktet, vil bli lastet inn i 3D-viseren når Øyeblikksbildet gjenopprettes.

hvis to modeller har samme ID, er bare den første aktivert. For å sikre at riktige modeller er aktivert, er det viktig at de hver har sin egen ID.

Hvis du eksporterer flere filer fra redigeringsprogramvaren din, kan det være lurt å bruke en unik ID for hver modell du ønsker å eksportere. Det anbefales at hver modell i prosjektet tildeles en unik IfcProject-GUID for å unngå konflikter under gjenskaping av øyeblikksbilde. Dette sikrer at Catenda Hub kan vise konfigurasjoner nøyaktig i 3D-viseren.

Her er en artikkel fra BuildingSMART som beskriver hvordan dette gjøres i Revit [https://user.buildingsmart.org/knowledge-base/ifcproject/](https://user.buildingsmart.org/knowledge-base/ifcproject/)

sørg for å holde styr på hvilken ID som ble brukt for hvilken modell, slik at fremtidige Saker som opprettes, gjenkjenner den.
