# Informasjonspanel

Du vil kunne finne Informasjonspanelet som ett av de fire hovedpanelene som kan åpnes øverst til høyre på skjermen din. Du kan enten trykke på i-ikonet for å åpne dette panelet, eller du kan trykke [shift+4](https://support.catenda.com/en/articles/4670267-summary-of-most-important-shortcuts-and-basic-controls#:~:text=Inspect%20panel-,Shift%20%2B%204,-Show/hide%20last).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/01-intro.png)

I informasjonspanelet vil du kunne finne følgende seksjoner:

Følgende saker er beskrevet i denne artikkelen:

## 1. **Inspiser**

Dette lar deg se informasjonen om valgte objekter. Klikk [her](https://support.catenda.com/en/articles/4670285-inspect-panel) for å lese mer om inspiseringspanelet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/02-inspect.png)

## 2. **Mengdeberegning**

Dette lar deg lage og eksportere en liste over objekter og beregne summene av verdier som er knyttet til de ulike valgte objektene.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/03-quantity-take-off.png)

Klikk [her](https://support.catenda.com/en/articles/6673929-quantity-take-off-qto) for å lese mer om Mengdeberegning

## 3. **4D**

I denne seksjonen vil du kunne spore fremdriften til modeller med den 4. dimensjonen. Tid. Hvis IFC-filen din inneholder en IFCWORKPLAN, vil du kunne se en tidsplan for objektene i filen din.

> **Merk:** 4D i Catenda er bare tilgjengelig for ifc-filer eksportert fra [SYNCHRO](https://www.bentley.com/software/synchro/). Disse filene kan inneholde en IfcWorkPlan og IfcTasks

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/04-4d.png)

Ved starten av tidsrammen vil alle objekter være skjult, og avhengig av hvor langt tiden har kommet, vil objekter med riktig innstilling vises. Her er et eksempel på hvordan 4D-seksjonen kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/05-4d.png)

### 3.1 **4D-kolonner**

## 4. - Oppgavenummeret

_Oppgave-ID_ - Identifikatoren for oppgaven

_Navn_ - Navn på oppgaven

_Varighet_ - Varigheten av oppgaven

_Start_ Startdatoen for oppgaven Dette er når objektet vil vises i 3D. Objektene vil også vises som valgt Mellom startdatoen og sluttdatoen for en oppgave, vil oppgavelinjen være oransje. Klikk på klokke-ikonet ved siden av datoen for å hoppe til dette tidspunktet.

Slutt Sluttdatoen for oppgaven - Etter sluttdatoen vil objektene forbli i 3D, men vil være devalgt. Etter denne datoen vil oppgavelinjen være grønn. Klikk på klokke-ikonet ved siden av datoen for å hoppe til dette tidspunktet.

_Produkter_ Objektene som er knyttet til denne oppgaven Objektene kan isoleres og velges ved å klikke på isoler og velg.

### 4.1 **4D-bokmerker**

Det er mulig å lage et bokmerke der 4D-arbeidsplanen har blitt aktivert. Hvis du åpner dette bokmerket, vil du se hvilke objekter som har blitt gjort synlige til dags dato i henhold til planen. I Catenda Hub vil du kunne justere tidsskalaen til det tidspunktet du ønsker. Hvis du deler bokmerket eksternt, vil den eksterne parten som åpner bokmerket bare se objektene som har blitt gjort synlige så langt.

### 4.2 **Hvordan vet jeg om min IFC-fil har 4D-informasjon?**

Hvis ifc-filen din har IFCTASKs i seg, vil du kunne se disse i 4D-panelet. Hvis ifc-filen din har IFCRELASSIGNSTOPROCESSes i seg, vil disse oppgavene også være koblet til objekter. Et program du kan bruke for å se om disse er til stede, er [OpenIFCViewer](https://openifcviewer.com/). Her kan du kontrollere modellens statistikk

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/06-how-do-i-know-if-my-ifc-has-4d-information-in-it.png)

Hvor du finner enheten i statistikkpanelet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/07-how-do-i-know-if-my-ifc-has-4d-information-in-it.png)

## 5. **Utvalg**

Dette lar deg lage et sett med objekter som deretter kan stiliseres og farges.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/08-selections.png)

Mot toppen av Utvalgsmenyen vil du se hvor mange elementer du har valgt i 3D-viseren og treepanelet. Utvalg kan lagres ved å lage et [øyeblikksbilde](https://support.catenda.com/en/articles/8053352-issue-body#h_1ba7f8873f) eller et [bokmerke](https://support.catenda.com/en/articles/8471481-bookmark) og spille det av senere. Fordi utvalg lagres i øyeblikksbildet av en sak, kan de importeres og eksporteres til andre programmer gjennom BCF. Et eksempel på dette er at saker med utvalg fra utvalgskurven som synkroniseres gjennom BCF live connector i Solibri, vil inneholde utvalgsdata når øyeblikksbildet spilles av.

Følgende saker er beskrevet i denne seksjonen:

### 5.1 **Nytt utvalg**

Etter at du har valgt et objekt, vil du kunne klikke på Nytt utvalg

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/09-new-selection.png)

### 5.2 **Blyantikon**

Klikk på blyant-ikonet for å endre navnet på utvalget ditt

### 5.3 **Objektmengde**

Etter blyant-ikonet vil du se antallet objekter som for øyeblikket er i dette utvalget.

### 5.4 **Oppdater**

Klikk på oppdateringsknappen for å sette objektene i utvalget til objektene du for øyeblikket har valgt i 3D-viseren og treepanelet.

### 5.5 **Objektplukker**

Klikk på velg-knappen for å velge elementene i utvalget ditt

### 5.6 **Farge**

Med fargeknappen kan du endre fargen på objektene i utvalget ditt. Fargeplukker kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/10-color.png)

Velg farge med fargeglideren, paletten eller angi ønsket farge med en heksadesimals kode. Den andre glideren bestemmer transparensen der 1 er 100% ugjennomsiktig og 0 er 100% gjennomsiktig. Mot nederst til høyre vil du se den resulterende fargen.

### 5.7 **Slett**

Klikk på slettknappen for å slette dette utvalget

### 5.8 **Utvid/trekk sammen**

Utvid utvalget for å se hvilke objekter som er en del av utvalget.

## 6. **Målinger**

Dette lar deg se hvilke målinger som har blitt gjort i 3D-viseren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/11-measurements.png)

Klikk [her](https://support.catenda.com/en/articles/4670294-measuring-features) for å lese mer om målinger
