# Inspeksjonsmeny

Inspeksjonsmenyen finner du som den første menyen i [informasjonspanelet](https://support.catenda.com/en/articles/8238584-information-panel).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/01-intro.png)

Velg et objekt i [3D-visningen](https://support.catenda.com/en/articles/8227211-3d-viewer) eller [trepanelet](https://intercom.help/bimsync-arena/en/articles/4670290-trees-panel) for å komme i gang. Egenskapene og relatert informasjon vises i inspeksjonsmenyen. Etter at du har valgt et objekt, kan inspeksjonspanelet se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/02-intro.png)

Når du velger mer enn ett objekt, vises fellessakene, egenskaper, mengder, materialer eller biblioteker. Dine preferanser for hvilken meny du har åpen i inspeksjonsmenyen vil bli husket på tvers av prosjekter og sesjoner. Det betyr at uansett om du har lukket nettleseren og åpnet den på nytt, eller hvilket prosjekt du er i, vil de samme menyene alltid være åpne når du velger et objekt.

## 1. **Identifikasjon**

I identifikasjonsmenyen vil du se all identifikasjonsdata for det valgte objektet. Identifikasjon vises bare for ett objekt om gangen.

### 1.1 **Navn**

Navnet på objektet

### 1.2 **Merkelapp**

Merkelappen på objektet

### 1.3 **Enhet**

Enhetstiden på objektet

### 1.4 **GUID**

GUID-koden for objektet. Denne koden er unik for hvert objekt og kan brukes til å identifisere objektet gjennom revisjoner av IFC-filen.

### 1.5 **Type**

Typen på objektet. Hver type har sin egen unike GUID. To objekter som ser ut til å ha samme type kan derfor faktisk ha forskjellige typer med forskjellige GUID-er knyttet til dem. Klikk på typen for å velge alle objekter av den typen. Når du gjør det, aktiveres typetræet i [trepanelet](https://intercom.help/bimsync-arena/en/articles/4670290-trees-panel) hvor du kan se typen du har valgt i listen over typer for den modellen.

### 1.6 **Forhåndsdefinert type**

Den forhåndsdefinerte typen forteller deg hva slags type du har med å gjøre

### 1.7 **Omslutning**

Hvis objektet ditt er del av et hierarki, vil du se den overordnede noden i hierarkiet her. Klikk på den overordnede noden for å velge alle objekter som er inneholdt av den overordnede noden. Når du gjør det, aktiveres omslutningstreet i [trepanelet](https://intercom.help/bimsync-arena/en/articles/4670290-trees-panel) hvor du kan se omslutningsnoden i hierarkiet for objektene i modellen din.

## 2. **Linjeføringer**

Med en linjeføring valgt i trepanelet, klikk på Vis alle segmenter for å åpne tabellen for linjeføringer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/03-alignments.png)

Slik kan tabellen for linjeføringer se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/04-alignments.png)

Klikk [her](https://support.catenda.com/en/articles/11748020-tables-on-catenda) for å lese mer om tabeller på Catenda

## 3. **Saker**

I sakesmenyen kan du se om det er noen åpne eller lukkede saker som er [knyttet til](https://support.catenda.com/en/articles/8053299-right-menu-in-a-topic#h_758f17abbc) de valgte objektene. Sakesmenyen kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/05-topics.png)

### 3.1 **Ny sak**

Klikk på + -knappen for å opprette en ny sak i den gjeldende sakslisten. Hvis du oppretter en sak på denne måten, vil de valgte objektene automatisk være knyttet til saken, så du trenger ikke å koble dem manuelt.

Hvis du klikker på åpne, lukkede, profilbildet ditt eller bildet uten tilordning, filtreres alle sakelister i henhold til det du klikket på.

### 3.2 **Åpne saker**

Antallet åpne saker som det valgte objektet er knyttet til

### 3.3 **Stengt**

Antallet lukkede saker som det valgte objektet er knyttet til

### 3.4 **Profilbilde**

Antallet åpne saker som er knyttet til de valgte objektene som du har blitt tildelt

### 3.5 **Ikke tilordnet**

Antallet åpne saker som er knyttet til det valgte objektet uten en tilordnet ansvarlig

## 4. **Egenskaper, mengder og materialer**

Her finner du egenskapene som de valgte objektene har felles. Egenskapsmenyen kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/06-properties-quantities-and-materials.png)

### 4.1 **Filtrer tomme verdier-knappen**

Klikk på filterikonen for å skjule egenskaper som ikke har noen verdier.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/07-filter-empty-values-button.png)

### 4.2 **Vis verdi fra type-knappen**

Hvis de valgte objektene har egenskaper arvet fra objekttypen, vil du se knappen Vis verdi fra type.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/08-display-type-value-button.png)

Aktiver denne knappen for å vise egenskapene som ble arvet fra typen. Når denne knappen er aktivert, vil du se typeverdien slik:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/09-display-type-value-button.png)

### 4.3 **Egenskapsverdier**

Alle vanlige egenskapsverdi-par for de valgte objektene vises. Hvis verdier bare finnes i ett av objektene, vises egenskapen bare hvis objektet med den verdien er valgt.

### 4.4 **Egenskapssett**

I egenskapslisten kan du enten finne individuelle egenskaper eller egenskapssett (PSets) som inneholder flere egenskaper hver med sin egen verdi. Som du ser på bildet ovenfor, var de første 4 egenskapene individuelle egenskaper etterfulgt av tre egenskapssett med egenskaper i dem.

_Utvide/trekke inn egenskapssett_ Egenskapssett kan utvides eller trekkes inn ved å klikke på pilen ved siden av navnet. Så lenge de valgte objektene dine har egenskapssett, vil preferansen din for utvidelse/innstramming bli husket, men så snart du velger et objekt uten egenskapssett, blir den tilbakestilt.

### 4.5 **Mengder**

Her finner du mengdene som de valgte objektene har felles

### 4.6 **Materialer**

Her finner du materialene som de valgte objektene har felles

## 5. **Bibliotek**

Hvis de valgte objektene er [koblet til noen dokumenter](https://support.catenda.com/en/articles/8302244-right-menu-in-a-document#h_d0769e55eb) eller bibliotekelementer, vil du kunne se dem her. Biblioteksmenyen kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/s5wpkh4e/10-libraries.png)

Du kan klikke på tallet til høyre for disse elementene for å få de koblede dokumentene/bibliotekselementene vist i en visning i innholdspanelet. Hvis du for eksempel har en plantegning i dokumentdelen som er koblet til et veggbjekt, vil du kunne klikke på dokumenter her for å finne dokumentet i dokumentdelen.

## 6. **Modell**

Hvis alle objektene dine tilhører en modell, vil du kunne se informasjon om modellrevisjonen her. Denne informasjonen inkluderer:

_Modellbilde_

_Modellnavn_

_Revisjonsnummer_

_Dato og klokkeslett for publisering av revisjonen_

_Modellrevisjonens utgiver_

## 7. **Eierhistorikk**

Hvis det finnes informasjon om eierhistorikken for revisjonen i IFC-filen, vil du kunne finne den vist her. Denne informasjonen kan inkludere:

_Personen som opprinnelig eksporterte modellen_

_Forfattingsverktøyet som ble brukt_ _Når modellen ble eksportert_ Du kan også muligens se om noen redigerte modellen mellom eksport fra forfattingsverktøy og import i Catenda Hub.
