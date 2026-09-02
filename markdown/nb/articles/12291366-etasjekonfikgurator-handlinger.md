# Etasjekonfikgurator-handlinger

Handlingen "opprett ny bygning" finnes øverst til høyre på [etasjekonfikgurator-siden](https://support.catenda.com/en/articles/6921756-storey-configurator-page). Dette er hvor handlingene på etasjekonfikgurator-siden finnes:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/43a5z00a/01-intro.png)

## 1. **Nye elementhandlinger**

Hvis ingen bygninger har blitt konfigurert ennå, kan "legg til ny"-knappen i midten av siden klikkes. Klikk på den grønne plusknappen øverst til høyre eller åpne handlingsmenyen for å bruke handlingen "Legg til ny bygning". For å legge til en bygning er det alltid mulig å klikke på den grønne plusknappen eller klikke på handlingen i handlingsmenyen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/43a5z00a/02-new-item-actions.png)

## 2. **Legg til ny bygning**

Etter å ha brukt handlingen "legg til ny bygning" åpnes dialogboksen "Opprett en ny bygning".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/43a5z00a/03-add-new-building.png)

I dialogboksen "Opprett en ny bygning" velges en initiell modell.

> **Merknad:** For å kunne velge en modell må minst én modell være konfigurert i prosjektet.

Klikk [her](https://support.catenda.com/en/articles/9431936-models-page-actions#h_4100594482) for å lese mer om oppretting av modeller. Når en modell importeres, genereres en 2D-visning ved å skjære gjennom objektene i modellen 1,4 meter over høyden på hver etasje.

### 2.1 **Modeller uten 2D-geometri**

Hvis ingen objekter ble skåret gjennom, vil det ikke være mulig å velge modellen. Det er mulig å se at dette er tilfelle når [2D-knappen](https://support.catenda.com/en/articles/4670279-revision-selector#h_180a64490d) ikke blir aktivert når du åpner 2D-visningen av modellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/43a5z00a/04-models-with-no-2d-geometry.png)

### 2.2 **Eksempelfil**

Klikk [her](https://hub.catenda.com/share/collections/zBkFZ5yzhIUvw5a028kNt8A8oZNXVQhdtV9QhO8FuFuS) for å laste ned en eksempelmodell med én etasje og et enkelt objekt som kan brukes som eksempel.

## 3. **Bygningoppretting**

Hvis en modell med 2D-geometri velges, opprettes et utkast til en bygningskonfigurasjon. På dette stadiet er endringene som er gjort i etasjekonfigurasjonen ikke tilgjengelig for prosjektmedlemmer ennå. Dette er hvordan etasjekonfikgurator-siden kan se ut etter at en modell er valgt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/43a5z00a/05-building-creation.png)

I den opprettede bygningen opprettes en etasje for hver IfcStorey i modellen med sin respektive høyde. Med dette som utgangspunkt kan flere 2D-visninger legges til, en PDF-tegning kan legges under, og høyden kan endres for hver etasje.

### 3.1 **Etasjeforhåndsvisning**

Den gjeldende etasjen er uthevet i grønt. Konfigurasjonen av etasjen vises på høyre side. Hvis det er flere paneler og innholdspanelet med etasjekonfikgurator-siden har mindre plass, kan det hende at du ikke ser etasjeforhåndsvisningen på høyre side. Klikk på en annen etasje for å forhåndsvise konfigurasjonen for den etasjen.

### 3.2 **Lagre konfigurasjon**

For å lagre bygningen klikker du på "lagre konfigurasjon" mot bunnen av siden.
