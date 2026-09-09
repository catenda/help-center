# Høyremeny på modelsiden

Høyremenyen med informasjon finner du ved å velge en modell på [modellsiden](https://support.catenda.com/en/articles/4670286-models-page) eller ved å gå inn på [innholdssiden](https://support.catenda.com/en/articles/4670270-model-overview-page) til en modell.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/01-intro.png)

Klikk på "i"-ikonet øverst til høyre for å åpne høyremenyen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/02-intro.png)

Menyen kan se slik ut for en enkelt modell:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/03-intro.png)

Eller slik med flere modellrader valgt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/04-intro.png)

## 1. **Modellhovedtekst**

I modellhovedteksten vises informasjon om den nyeste revisjonen av modellen.

### 1.1 **Bilde**

Øverst i modellhovedteksten kan et bilde legges til for modellen. Slik kan det se ut når ingen bilde er lagt til.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/05-image.png)

Enten laster du opp et lokalt bilde eller legger til et øyeblikksbilde direkte fra 3D-visningen uten å laste opp noe. Slik ser modellsiden ut når et bilde er konfigurert for en modell:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/06-image.png)

_Modellbilde i høyremeny_ Når det er lagt til, vises bildet øverst i høyremenyen til en modell når en enkelt modell er valgt eller når menyen er åpen på modellinnholdssiden. Det opploadede bildet vises både i høyremenyen til en modellrevisjon når én modell er valgt, og i miniatyrbildet av modellen i navnekolonnen i modelltabellen.

Klikk [her](https://support.catenda.com/en/articles/4670257-creating-a-thumbnail-for-your-model) for å lese mer om hvordan du legger til et bilde for en modell.

_Modellminiatyr_ Når det er lagt til, vises bildet som et miniatyr for modellen i navnekolonnen i modelltabellen på modellsiden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/07-image.png)

Klikk på miniatyren for å åpne en forhåndsvisning av bildet. Slik kan miniatyrforhåndsvisningen se ut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/08-image.png)

Fra navigasjonen øverst kan bildet lastes ned. Hvis øyeblikksbildet ble tatt fra en modell, er forhåndsvisningen en 3D-forhåndsvisning, så det er mulig å navigere rundt modellen fra startpunktet for modellminiatyren.

### 1.2 **Dokumentlenke**

Dokumentlenken er den grå boksen under modellbildet. Boksen viser plasseringen av dokument-modellen i filstrukturen. Under den vil du se navnet på dokument-modellen som er koblet til denne modell-dokumenten. Klikk på denne boksen for å gå til forhåndsvisningssiden for dokument-modellen på dokumentsiden.

### 1.3 **Status**

Statusen for den nyeste offentlige dokument-modellrevisjonen.

### 1.4 **Merkelapper**

Som standard kan merkelapper brukes på hvilken som helst modell. Hvis delte revisjoner er aktivert, må det være minst én publisert revisjon i modellen for å kunne legge til merkelapper. Merkelapper lagres både for modellen og for dokumentet som modellen er koblet til. Samme merkelapp kan derfor brukes til å filtrere modeller på modellsiden og dokumenter på dokumentsiden.

## 2. **Bidragsytere**

De ulike medlemmene som har lastet opp revisjoner og dermed bidratt til modellen, vises her.

## 3. **Modelltransformasjon**

Med modelltransformasjon kan modellelementer konfigureres til å vises på en annen plassering og orientering i Catenda Hub 3D-visningen. Denne transformasjonen gjelder kun for modeller i 3D-visningen og ikke 3D-dokumenter som er lastet inn i 3D-visningen. Klikk [her](https://support.catenda.com/en/articles/12498975-add-context-to-your-projects-with-freely-accessible-ign-point-clouds-hd-lidar) for å lese mer om transformasjonen av 3D-dokumenter.

_Utbytte av modeller med eksterne verktøy_ Modeller lastes ofte ned fra Catenda og åpnes i et tredjepartsprogram. Det er derfor fortsatt viktig å ha de riktige koordinatene konfigurert i IFC-filen før opplasting, slik at den nedlastede filen inneholder riktig informasjon.

_Når bør modellen transformeres?_ Det er ofte en periode hvor en modell blir sendt inn og geometrien allerede brukes til samarbeid selv før koordinatene i modellen er korrekte. Dette kan komme fra ulike årsaker, for eksempel at et felles nullpunkt ikke er besluttet i prosjektet, eller at en annen eksportmetode må undersøkes i forfatterprogrammet hvor IFC-filen ble generert. Det kan hjelpe å transformere modellen (kun i Catenda Hub gjennom nettleseren) med modelltransformasjon i løpet av denne perioden, slik at avspilling av 3D-øyeblikksbilder fortsetter å stemme, selv med nyere revisjoner som har oppdaterte koordinater.

_Koordinatsamarbeid med delte revisjoner_ I et prosjekt hvor delte revisjoner er aktivert, anbefales det ikke å publisere modellrevisjoner uten å ha de riktige koordinatene i IFC-filen.

### 3.1 **Modelltransformasjonsinnstillinger**

Last inn modellen som skal flyttes i 3D-visningen. Dette kan gjøres ved å klikke på 3D-knappen på dashbordet, på modellsiden, på modellinnholdssiden eller i revisjonsvelgeren. I høyremenyen på modellsiden vises transformasjonsinnstillingene menyen mot bunnen av menyen. Slik kan modelltransformasjonsinnstillingene se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/09-model-transformation-settings.png)

_Offset_ Skriv inn X-, Y- og/eller Z-koordinat for å flytte modellen. Enheter - Meter

_Rotasjon_ Skriv inn en vinkel for å rotere modellen. Modellen roteres rundt midtpunktene i dens grenseboks som inneholder alle objektene i modellen. Punktet er ofte rundt midten av modellen sett fra oven. Enheter - Grader

_Lagre_ Klikk på lagre for å lagre transformasjonsinnstillingene.

### 3.2 **Kun i nettleser**

IFC-filen endres ikke når transformasjonsinnstillingene lagres. Hvis en ny modell opprettes med IFC-filen enten innenfor samme prosjekt eller i et annet prosjekt, vises IFC-filen på nytt på plasseringen som er konfigurert i IFC-filen.

Det er ofte ikke et problem å flytte en modell i Catenda for korte tidsperioder eller til og med hele levetiden til prosjektet. Til slutt kan det spare mye tid å bestemme et felles koordinatsystem slik at modeller ikke trenger å justeres etter at de er opprettet, og for å forhindre misforståelser i løpet av prosjektet.

## 4. **Flervalg**

Med flere modeller valgt kan høyremenyen se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/10-multi-select.png)

Klikk på den røde x-en ved siden av en modell for å fjerne den fra utvalget.

### 4.1 **Oppdater valgte dokumenter**

Slik kan oppdateringsmeny for valgte dokumenter se ut

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dcxbjfs1/11-update-selected-documents.png)

Klikk i områdene for å legge til og fjerne merkelapper, og velg en eller flere merkelapper.

_Tillegg har prioritet_ En merkelapp som er angitt i både feltene for å legge til og fjerne merkelapper, legges til modeller som ikke allerede har merkelappen, og fjernes ikke fra modeller som allerede har merkelappen.

### 4.2 **Siste revisjon**

Den angitte statusen blir konfigurert for alle valgte modeller når endringene lagres.
