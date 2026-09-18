# Modelltre-panel

Modelltre-panelet finnes som ett av fire [prosjektpaneler](https://support.catenda.com/en/articles/13141464-project-panels) som kan åpnes øverst til høyre på skjermen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/01-intro.png)

## 1. **Åpne modelltre-panelet**

Modelltre-panelet kan åpnes side ved side med noen av de andre panelene.

_Åpne_ modelltre _panel:_ Klikk på treikon eller trykk [shift+3](https://support.catenda.com/en/articles/4670267-summary-of-most-important-shortcuts-and-basic-controls#:~:text=row%20of%20objects-,Shift%20%2B%203,-Control%20%2B%20left%20click)

_Isolere_ modelltre _panel:_ Åpne treepanelet Lukk alle andre åpne paneler ved å klikke på dem.

## 2. **Modelltre** **panelinnhold**

I treepanelet kan innholdet av IFC vises i forskjellige trestrukturer. Strukturen som vises kommer direkte fra IFC-modellen som er valgt øverst. Hver av trærne viser deler av IFC på forskjellige måter. Listeelementene for objekter som er synlige i 3D-visningen kan være synlige i ett eller flere av modelltrærne avhengig av om de passer til denne måten å vise IFC-innholdet på. Andre listeelementene kan omfatte gruppering av disse objektene og/eller andre enheter fra IFC.

### 2.1 **Navngiving av listelement**

Listelementer kan navngis på forskjellige måter. Navngitte enheter kan navngis etter navnet de ble tildelt i IFC, men enheter kan også navngis etter navnet på enheten selv som spesifisert i BuildingSMART-standarden. Hvis ingen oversettelse er tilgjengelig per standard kan navnet vises på engelsk som er basisspråket. For å bidra til oversettelsen i den åpne standarden, se [her](https://user.buildingsmart.org/knowledge-base/ifc-translations-manual/). For å se om en enhet har en oversettelse, gå til BuildingSMART-siden for den enheten og endre språket til språket. Enhetens navn vil enten bli oversatt eller det vil være en melding øverst som sier at denne enheten mangler oversettelse.

_Grupperingenheter_ Enheter som kan inneholde andre enheter som en bygning som inneholder vegger kan navngis etter navnet som er gitt til den enheten hvis den er til stede eller etter navnet på enheten per BuildingSmart-standarden.

_Enkeltlementer_ Enkeltlementer er elementene på det laveste nivået når trevisningen er fullt utvidet og kan se slik ut:

`Entity.Set.Number`

Navn Disse elementene er oppført etter navnet på enheten deres i henhold til BuildingSMART-standarden.

Sett Det er ofte mange lignende elementer som er gruppert sammen, så etter enhetens navn kommer nummeret på det n-te settet av disse typene enheter som denne enheten tilhører.

Nummer Til slutt er nummeret på det n-te elementet i settet oppført. For eksempel kan det 21. vinduet på nivå 2 se slik ut:

`Window.1.21`

### 2.2 **Uthevete elementer**

Som i 3D-visningen er valgte objekter uthevet i grønt og valgte grupper av objekter er uthevet i gult. I motsetning til 3D-visningen er det også mulig å utheave enheter som kan inneholde objekter og utheave sett med objekter som er lignende. Hvis et objekt er uthevet i 3D-visningen men ingen objekt er uthevet i modelltre-panelet, kan det være at objektet er uthevet i en annen modelltre-meny.

_Zoom til listelement_ Trær kan bli ganske lange. Når et objekt er valgt i 3D-visningen rulles treemenyen til stedet i listen der det valgte objektet finnes, forutsatt at det objektet finnes i treemenyen som er åpen i modelltre-panelet.

### 2.3 **Utvalg**

Listelementer fra flere modeller som er lastet inn i 3D-visningen kan velges. Klikk på rullegardinmenyen øverst for å bytte mellom de forskjellige modellene. Utvalg kan lagres i utvalgsmenyen.

_Aktivt element_ Det aktive elementet er uthevet med en rød stiplet kontur. Bruk piltastene til å bevege deg opp og ned i listen.

_Enkeltvalg_ Etter å ha klikket på et listelement for å velge det, vil elementet bli satt til det aktive elementet og det tidligere utvalget vil bli slettet.

Klikk på et listelement eller trykk enter på det aktive elementet for å: Velge et objekt. Velg et sett med objekter og alle lignende objekter i et sett med objekter. Velg en gruppe med sett og alle underelementer i den gruppen.

_Redigering av utvalg_ Ctrl+Klikk på et listelement eller trykk Ctrl+Enter på det aktive listeelementet for å: Legg til listelementer som ikke tidligere var valgt til utvalget. Fjern listelementer som er valgt fra utvalget.

_Angi utvalg_ Shift+Klikk på et listelement eller trykk Shift+Enter på det aktive listeelementet etter å ha valgt et annet listelement for å: Velg alle listelementer mellom det tidligere valgte elementet og det valgte elementet.

_Zoom til listelement_ Dobbeltklikk på et listelement for å zoome 3D-visningen på det listeelementet.

## 3. **Inneholdelsestre**

Inneholdelsestræet gir et hierarkisk perspektiv på hvordan de forskjellige IFC-objektene forholder seg til hverandre.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/02-containment-tree.png)

Når snarveien "`p`" trykkes for å velge den overordnede noden, kan dette visuelt observeres i inneholdelsestræet.

## 4. **Komponenttre**

Komponenttræet gir et hierarkisk perspektiv på komponentene som utgjør et objekt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/03-component-tree.png)

I denne treemenyen kan komponenter som følgende finnes:

AirTerminal Annotation Beam BuildingElementPart BulidingElementproxy Coil Column Covering CurtainWall Damper Distributionport DiscreteAccessory Ductfitting DuctSilencer Door ElementAssembly EnergyConversionDevice Fan Fastener Filter FireSuppresionTernimal FlowController FlowFitting FlowMovingDevice FlowSegment FlowStoragedevice FlowTerminal Footing FurnishingElement GeographicElement Grid HeatExchanger LightFixture Member OpeningElement PipeFitting PipeSegment Pump Plate Railing Ramp Roof SanitaryTerminal Site Slab Space SpaceHeater StackTerminal Stair StairFlight TransportElement UnitaryEquipment Valve Wall WallStandardCase WasteTerminal Window

## 5. Type tre

Typetræet viser alle objektene sortert etter type.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/04-type-tree.png)

## 6. Lag tre

Lagtræet gir et hierarkisk syn på lagene i modellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/05-layer-tree.png)

## 7. System tre

Systemtræet gir en oversikt over systemene i modellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5dr5qz8m/06-system-tree.png)

> **Merk:** Objektet som er valgt i treen og i modellen er synkronisert. Hvis du klikker på et vindu i 3D-modus, velges det i treen. Og omvendt. Du kan også dobbeltklikke på et "blad" i modellen for å få 3D-kameraet til å bevege seg til det objektet.
