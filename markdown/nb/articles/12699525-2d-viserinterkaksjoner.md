# 2D-viserinterkaksjoner

> Interaksjon med 2D-viseren

Ulike komponenter i [2D-viseren](https://support.catenda.com/en/articles/4854537-2d-viewer) kan brukes på ulike måter. Hver del av 2D-viseren som kan klikkes på er beskrevet i denne artikkelen. Slik kan 2D-viseren se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/01-intro.png)

Denne artikkelen inneholder informasjon om følgende saker: _[2D-knapp](#h_ddfb1f5837) - [Toppbar](#h_7996dde66c) - [Lerret](#h_d564366bf9) -_ [Navigasjon](#h_b384896c43) - [Valg](#h_8916df6427) - [Innstillinger](#h_f9d34c17aa) - [Bunnbar](#h_15dafd8ad4)

## 1. **2D-knapp**

Hvis 2D-viseren ikke er åpnet, klikker du på 2D-knappen i nedre høyre hjørne av 3D-viseren for å åpne 2D-viseren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/02-2d-button.png)

## 2. **Topplinje**

### 2.1 **Endring av størrelse**

Dra disse to diagonale linjene for å endre størrelse på 2D-viseren på tvers av hvilken som helst del av 3D-viseren. Du vil vite at du kan dra dette hjørnet når du ser at markøren din endres.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/03-resizing.png)

### 2.2 **Tittel**

Tittelen på topplinja vil være navnet på etasjen. Hvis en etasje i en [storey configurator](https://support.catenda.com/en/articles/6921756-storey-configurator-page) bygning er valgt, vil tittelen inneholde navnet på bygningen og navnet på gjeldende etasje. Hvis etasjen i en ikke-konfigurert modell er valgt, vil tittelen inneholde modellens navn.

### 2.3 **Åpning og lukking av 2D-viseren**

_Lukking_ Klikk på krysset i øvre høyre hjørne av 2D-viseren for å lukke 2D-viseren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/04-opening-and-closing-the-2d-viewer.png)

## 3. **Lerret**

Lerretet på 2D-viseren er den delen av 2D-viseren hvor linjene som er koblet til etasjene i de ulike modellene der 2D-visninger er aktivert, vises.

### 3.1 **Klikk musknapp**

_Venstre klikk_ Hvis det er rom på etasjen av 2D-visningen som er aktivert for en modell, kan de velges ved å klikke på dem. Det er mulig å fortelle om det er rom i 2D-visningen ved at rommets navn er synlig i midten av rommet.

_Rulling_ Zoom inn og ut av 2D-viseren.

_Høyreklikk_ Åpne kontekstmeny

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/05-click-mouse-button.png)

- _Legg til markør_
  Legg til en ny markør. Med en sak åpen i innholdspanelet kan du tilordne den valgte markøren. Denne markøren vil ikke bli lagret og synlig for andre før den blir lagt til et problem.
- _Opprett en ny sak med markør_
  Opprett en ny sak med markør. Denne markøren vil ikke bli lagret og synlig for andre før saken sendes inn.
- _Opprett spørring_
  - Kryss rom - Opprett en [spørring](https://support.catenda.com/en/articles/4854514-queries) av alle objekter som krysser det valgte rommet
  - Kryss etasje - Opprett en [spørring](https://support.catenda.com/en/articles/4854514-queries) av alle objekter som krysser denne etasjen

### 3.2 **Hold musknapp**

_Hold venstre eller høyre klikk_ Pan 2D-viser

### 3.3 **Visningspunktindikator**

_Hold venstre klikk på visningspunktindikator_ Flytt kamera i 3D. Kameravinkel forblir.

_Hold høyre klikk på visningspunktindikator_ Flytt kamera i 3D. Kameravinkel vil følge.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/06-viewpoint-indicator.png)

## 4. **Navigeringsverktøy**

### 4.1 **Zoom til alt**

Zoom ut for å vise alle synlige objekter på en gang

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/07-zoom-to-extents.png)

### 4.2 **Rotasjon**

Med rotasjonsknappen kan du rotere 2D-viseren.

_Rotasjonsglider_ Den innledende rotasjonen kan konfigureres ved å angi en plassering med rotasjon i [prosjektinnstillinger](https://support.catenda.com/en/articles/4670273-project-settings-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/08-rotation.png)

_Gliderajustering_ Velg glideren ved å klikke på den og bruk pil høyre og venstre tastene for å gjøre justeringer på 0,1 grad. Dette kan være nyttig for å gjøre valg, utsnitt og spørringer. Rotasjon er lettere hvis du først velger et rom fordi det vil knipse seg til kantene av rommet når du roterer. Du kan også skrive graden av rotasjon i menyen under glideren.

_True North_ Hvis ingen innledende rotasjon er konfigurert i prosjektinnstillinger, vil True North være det samme som tilbakestillingsknappen. Hvis en innledende rotasjon er konfigurert i prosjektinnstillinger, kan True North være i en vinkel i forhold til den innledende rotasjonen

_Tilbakestill_ Klikk Tilbakestill i øvre høyre hjørne for å tilbakestille glideren til den innledende rotasjonen.

_Underliggende tegningsrotasjon_ Bygninger kan konfigureres i [storey configurator](https://support.catenda.com/en/articles/6921756-storey-configurator-page). Hver etasje i en bygning kan ha en tegning som underlag som roteres i forhold til modellene i prosjektet.

### 4.3 **Lås kamera**

Hvis en modell er lastet inn i 3D-viseren, kan du låse kameraet til 3D-viserkameraet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/09-lock-camera.png)

Med denne funksjonen aktivert, vil visningspunktindikatoren forbli sentrert på lerretet selv om kameraet flyttes i 3D-viseren. Dette er nyttig i kombinasjon med [walk-modus](https://support.catenda.com/en/articles/5784718-3d-viewer-settings#h_1c05dca226).

## 5. **Valg- og innstillingsverktøy**

Valg- og innstillingsverktøyene finnes mot øvre høyre del av 2D-viserlerretet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/10-selection-tools-and-settings.png)

Klikk [her](https://support.catenda.com/en/articles/8035360-selecting-and-clipping-from-2d) for en detaljert forklaring på hvordan du bruker utsnittverktøy i 2D-viseren.

### 5.1 **Velg**

Velg rom og zoom inn og ut.

### 5.2 **Utsnitt: Velg objekter**

Dra et rektangel over 2D-lerretet for å lage et volum for valg av objekter i 2D/3D.

### 5.3 **Utsnitt: Opprett klippeplan**

Opprett 4 til 6 klippeplan ved å dra et rektangel over 2D-lerretet og velge høyden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/11-section-create-clipping-planes.png)

### 5.4 **Utsnitt: Opprett spørring**

Opprett en [spørring](https://support.catenda.com/en/articles/4854514-queries) ved å dra et rektangel over 2D-lerretet og velge høyden.

### 5.5 **Flytt-knapp**

Den rektangulære valgfunksjonen til utsnittverktøyene hindrer bevegelsen av markøren. I nedre høyre hjørne av 2D-viseren kan du derfor bruke flytt-knappen. Med denne knappen kan du enkelt omposisjonere lerretet ditt for utsnittering.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/12-br-move-button.png)

## 6. **2D-viseinnstillinger**

Innstillingene for 2D-viseren finnes i rullegarden med girikon.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/13-2d-viewer-settings.png)

_Markeringsfargemodus_ Endre fargen på markørene i 2D-visningen til å ha fargen på en av følgende:

- Status
- Type
- Frist

_Romnavnformat_ Vis det lange navnet på rommene og områdene

_Gjennomsiktig_ Gjør 2D-viseren gjennomsiktig

## 7. **Bunnlinje**

### 7.1 **Modellvisning**

Klikk her for å lese mer om etasjemenyen. Etasjemenyen kan se omtrent slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/14-model-view.png)

### 7.2 **Lagmeny**

Med lagknappen kan du veksle mellom ulike lag i 2D-viseren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/5nvzd52j/15-layer-menu.png)

_Markører_ Med denne knappen kan markører slås av eller på.

_Modeller_ Med denne knappen kan modeller slås av eller på.

_Tegninger_ Du vil se denne knappen hvis en tegning har blitt justert som et underlag for en bygningsetasje i [storey configurator](https://support.catenda.com/en/articles/6921756-storey-configurator-page). Med denne knappen kan de justerte tegningene slås av eller på.

_Kart_ Du vil se denne knappen hvis en plassering har blitt konfigurert i [prosjektinnstillinger](https://support.catenda.com/en/articles/4670273-project-settings-page). Med denne knappen kan kartet slås av eller på.
