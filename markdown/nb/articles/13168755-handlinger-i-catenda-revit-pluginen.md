# Handlinger i Catenda Revit-pluginen

> **Merk:** Installasjonfilen for pluginen finner du i [denne artikkelen](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Handlingene [Catenda Revit-plugin](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin) finnes øverst til høyre i plugin-vinduet i Revit-appen.

Slik kan handlingsmenyen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/01-intro.png)

Informasjon om følgende saker finnes i denne artikkelen:

## 1. **1. Ny sak**

Klikk på den grønne Ny sak-knappen øverst til høyre for å opprette en ny sak i prosjektet som er valgt i rullegardinmenyen øverst til venstre. Saken blir opprettet i saklisten som er valgt i den andre rullegardinmenyen øverst til venstre. _Tilgang påkrevd:_ Skrivetilgang til saklisten

Så snart saken er opprettet, vil den være synlig i Catenda Hub via nettleseren samt gjennom alle Catenda-plugins i andre programmer. Slik kan den nye sak-siden se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/02-1-new-topic.png)

Minimumsinformasjonen som kreves for å sende inn en sak, er en tittel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/03-1-new-topic.png)

### 1.1 **1.1 Send inn**

Når saken er klar til å deles med prosjektet, klikker du på Send inn for å sende inn saken til saklisten.

## 2. **2. Last opp IFC**

Klikk på Last opp IFC i handlingsmenyen som åpnes med de tre prikkene øverst til høyre for å laste opp ditt nåværende Revit-modell direkte til Catenda Hub som en IFC-fil. Slik kan siden Last opp IFC se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/04-2-upload-ifc.png)

### 2.1 **2.1 Velg modell**

I denne rullegardinmenyen vises allerede eksisterende modeller fra det valgte prosjektet. Hvis ingen modell finnes i prosjektet, opprett først en tom modell i Catenda via nettleseren. Den opplastede IFC-filen blir en ny revisjon til den valgte modellen. Hver modell i Catenda er knyttet til en dokumentbeholder, så etter opplasting vil revisjonen være synlig både i modell- og dokumentområdene i prosjektet.

### 2.2 **2.2 Filnavn**

Skriv inn et valgfritt filnavn knyttet til opplastingen. Bare ASCII-tegn støttes i dette feltet.

### 2.3 **2.3 Skriv inn en kommentar**

Skriv inn en obligatorisk kommentar knyttet til opplastingen. Så snart en kommentar legges til, blir opplastingsknappen fremhevet og klikkbar. Bare ASCII-tegn støttes i dette feltet.

### 2.4 **2.4 Eksportkonfigurasjon**

Velg en IFC-konfigurasjon. En ny konfigurasjon kan opprettes i IFC-eksportmenyen i Revit. Du kan også velge \<Catenda-oppsett> for en enkel konfigurasjon som passer godt til Catenda Hub.

Dette er eksportinnstillingene for Catenda-oppsettet

```
selectedConfig.Name = "<Catenda Setup>"; selectedConfig.IFCVersion = IFCVersion.IFC2x3CV2; selectedConfig.SpaceBoundaries = 1; selectedConfig.ActivePhaseId = ElementId.InvalidElementId; selectedConfig.ExportBaseQuantities = true; selectedConfig.SplitWallsAndColumns = false; selectedConfig.VisibleElementsOfCurrentView = false; selectedConfig.Use2DRoomBoundaryForVolume = false; selectedConfig.UseFamilyAndTypeNameForReference = true; selectedConfig.ExportInternalRevitPropertySets = true; selectedConfig.ExportIFCCommonPropertySets = true; selectedConfig.Export2DElements = false; selectedConfig.ExportPartsAsBuildingElements = true; selectedConfig.ExportBoundingBox = false; selectedConfig.ExportSolidModelRep = false; selectedConfig.ExportSchedulesAsPsets = false; selectedConfig.ExportUserDefinedPsets = false; selectedConfig.ExportUserDefinedPsetsFileName = ""; selectedConfig.ExportLinkedFiles = false; selectedConfig.IncludeSiteElevation = true; selectedConfig.UseActiveViewGeometry = false; selectedConfig.ExportSpecificSchedules = false; selectedConfig.TessellationLevelOfDetail = 0; selectedConfig.StoreIFCGUID = true; selectedConfig.ExportRoomsInView = true;
```

### 2.5 **2.5 Last opp**

Klikk på Last opp for å laste opp en IFC. En kommentar må legges til for å kunne laste opp. _Tilgang påkrevd:_ Skrivetilgang til dokumentet som er knyttet til modellen.

## 3. **3. Innstillinger**

Siden Innstillinger lar deg endre hvordan pluginen skal opprette 3D-visning når du bruker [Zoom-funksjonen](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin#h_36392f671a).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/05-3-settings.png)

### 3.1 **3.1 Tilbake til saker**

Klikk på Tilbake til saker for å gå tilbake til saklisten.

### 3.2 **3.2 Navigasjon**

_Behold 3D-visningen ortografisk_ Dette alternativet tvinger Revits 3D-visning til å være ortografisk selv om det tilsvarende viewpoint er opprettet med en perspektivvisning.

_Opprett en ny visning for hver sak_ I stedet for å gjenbruke den samme 3D-visningen hver gang du bruker Zoom-funksjonen, vil dette alternativet opprette en ny 3D-visning for hver sak hver gang du bruker zoom-funksjonen.

_Suffiksen for 3D-visningsnavn_ Denne teksten vil bli lagt til navnet på 3D-visningen som er opprettet når du bruker Zoom-funksjonen.

### 3.3 **3.4 Viewpoint-transformasjon**

Med viewpoint-transformasjonen kan viewpoint i Revit konfigureres til å bli forskjøvet med et beløp. Hvis verdier er konfigurert her, vil viewpoint bli forskjøvet med det beløpet hver gang et viewpoint fra en sak blir avspilt. Dette kan være nyttig når koordinatene i sak-viewpoint ikke samsvarer med koordinatene som er konfigurert i Revit-prosjektet.

_3.4.1 X (Ø/V)_ Transformasjon i X-retningen. Øst eller vest avhengig av positive eller negative verdier. Enheter i meter

_3.4.2 Y (N/S)_ Transformasjon i Y-retningen. Nord eller sør avhengig av positive eller negative verdier. Enheter i meter

_3.4.3 Z (Høyde)_ Transformasjon i Z-retningen. Høyde avhengig av positive eller negative verdier. Enheter i meter

_3.4.4 Vinkel_ Rotasjonstransformasjon. Høyde avhengig av positive eller negative verdier. Enheter i grader. Kameraet vil forbli i samme høyde og rotere kameraet rundt et punkt i modellen.

## 4. **4. Min konto**

Åpne siden Catenda Hub-kontoen din i standardnettleseren din. Klikk [her](https://support.catenda.com/en/articles/6880968-account-page) for å lese mer om kontosiden.

## 5. **5. Logg ut**

Klikk på Logg ut for å logge ut av Catenda Hub i pluginen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/gjfjfwqg/06-5-sign-out.png)

Etter at du har logget ut, vises påloggingssiden der du kan logge inn med samme konto eller en annen konto med brukernavn og passord. Klikk [her](https://support.catenda.com/en/articles/7891486-sign-in-page) for å lese mer om påloggingssiden.

Etter at du logger inn igjen, vises det første prosjektet i prosjektlisten. Velg et prosjekt i prosjektlisten igjen for å navigere til et annet prosjekt.
