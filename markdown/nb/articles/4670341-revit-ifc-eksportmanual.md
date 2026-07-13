# Revit IFC-eksportmanual

Målet med denne IFC-eksportmanualen er å gi brukeren en veiledning om hvordan du eksporterer IFC for riktig formål. En IFC-fil kan raskt bli stor og tung når du har mye informasjon som skal tas ut av modellen. Derfor må du fjerne merkingen for unødvendig informasjon når du eksporterer en IFC. Når du laster opp en modell til Catenda, er det ikke alltid nødvendig å ha mye informasjon og et høyt detaljnivå i modellen. Senere i denne manualen kommer vi tilbake til hvilke innstillinger vi anbefaler for å gjøre modellen litt mindre og litt enklere å arbeide med. Her går vi gjennom steg for steg den mest hensiktsmessige måten å eksportere en IFC fra Revit til Catenda.

Følgende emner er beskrevet i denne artikkelen:

## 1. **Prosjektinnstillinger**

Før eksport er det viktig å kontrollere at GUID-ene i Revit-prosjektet ditt er korrekte.

`Administrer -> Innstillinger -> Prosjektinformasjon -> IFC-parametere`

![Prosjektinformasjon IFC-parametere IfcSite GUID IfcBuilding GUID IfcProject GUID](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/01-project-settings.png)

Hvis GUID-en er ulik fra en tidligere eksport, vil objektene i nyere eksporter ikke være riktig koblet til GUID-ene i BCF-emner. Når du oppretter et nytt prosjekt, får det en unik ID.

## 2. **Endre IFC-eksport**

Når Revit er åpent og du er klar til å eksportere, kan du gjøre følgende.

![På toppen til venstre på skjermen trykker du på Fil](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/02-modify-ifc-export.png)

Øverst til venstre finner vi fanen "Fil".

---

> **Tips:** **Husk:** _Du kan ha en dedikert mappe for dine IFC-filer, slik at du alltid har kontroll over hvor filen din er lagret!_

IFC-eksportmenyen finner du her:

`Fil -> Eksporter -> IFC`

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/03-modify-ifc-export.png)

Slik kan eksport-menyen for IFC se ut:

![Eksporter IFC](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/04-modify-ifc-export.png)

Filnavn Angi navn og plassering som den eksporterte filen skal ha i systemet

Eksportoppsett Velg mellom følgende forhåndsdefinerte oppsett: \<In-Session Setup> IFC 2x3 Coordination View 2.0 IFC 2x3 Coordination View IFC 2x3 GSA Concept Design BIM 2010 IFC 2x3 Basic FM Handover View IFC 2x3 Coordination View IFC 2x3 COBie 2.4 Design Deliverable View IFC4 Reference View [Architecture] IFC4 Reference View [Structural] IFC4 Reference View [BuildingService] IFC4 Reference View [Unofficial] IFC4x3 IFC-SG Regulatory Requirements View

Når Catenda-plugin for Revit brukes, legges det til et ekstra forhåndsdefinert eksportoppsett for bruk med Catenda i listen over alternativer.

## 3. **Endre oppsett**

Klikk på Endre oppsett i eksportoppsettet i IFC-eksportdialogen. Her kan du endre nødvendige innstillinger for IFC-eksporter og opprette egendefinerte oppsett. Slik kan menyen for endring av oppsett se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/05-modify-setup.png)

Dette vinduet inneholder følgende faner:

---

Følgende emner er beskrevet i denne delen:

### 3.1 **Generelt**

![Generelt](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/06-general.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/07-general.png)

Vi tar deg gjennom de ulike innstillingene.

_IFC-versjon_ Valg av IFC-versjon.

_Utvekslingskrav_ Disse alternativene kan variere avhengig av IFC-versjonen som er valgt. IFC 2x3 Coordination View 2.0

- Arkitektonisk referanseutveksling
- MEP-referanseutveksling
- Strukturell referanseutveksling

_Kategoritilordning_ Før Revit 2026 var dette alternativet tilgjengelig i File -> Export -> Options -> IFC Export Options. Slik kan menyen Administrer IFC-eksportilordningsinnstillinger se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/08-general.png)

_Filtype_ IFC-typevalg.

_Fase for eksport_ Hvis du har brukt faseverktøyet i Revit, kan du her velge og bare eksportere nye eller eksisterende strukturer.

_Romgrenser_ Dette handler om hvordan roominformasjon kan brukes videre. a. 1. nivå - Eksempel på bruk: Mengdeuttak, administrasjon, drift og vedlikehold (FDVU). b. 2. nivå - Eksempel på bruk: Energianalyse, lysanalyse.

_Anleggstype_ Dette alternativet er bare tilgjengelig for IFC 4x3 Velg mellom ett av følgende: Bru (IfcBridge) Bygning (IfcBuilding) Marineanlegg (IfcMarineFacility) Jernbane (IfcRailway) Vei (IfcRoad)

_Del vegger, søyler, kanaler etter nivå_ Her kan du f. eks. dele vegger horisontalt hvis de er modellert over flere etasjer.

_Filoverskriftsinformasjon... Prosjektadresse..._ I disse kan du legge inn informasjon om hvem som har levert IFC-en, prosjektadresse osv.

_Prosjekturspung_ Prosjekturspung, dette setter vi på Gjeldende delte koordinater - Presentere delte koordinater.

> **Merknad:** Dette ble flyttet til Geografisk referanse fra og med Revit 2025

_Inkluder stålelementer_ Inkluderer stålkomponenter hvis modellert.

> **Merknad:** Dette ble flyttet til Tilleggsinnhold fra og med Revit 2025

---

### 3.2 **Tilleggsinnhold**

![Tilleggsinnhold](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/09-additional-content.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/10-additional-content.png)

Eksporter koblede filer som separate IFC-er Hvis du vil inkludere de koblede filene i IFC-en, kan du merke av dette alternativet for å gjøre det. Det anbefales at du eksporterer hver fil separat og importerer hver til sin egen modell.

Eksporter bare synlige objekter synlige i visning IFC-fil.

- Eksporter rom, områder og mellomrom i 3D-visninger
  Dette alternativet kan være nyttig for å velge områder i 2D-viseren.

Inkluder stålelementer, _fylt_

Eksporterer 2D planvisningselementer, _fylt, regioner_ (riper).

Eksportoppillarnettet Pillarnettet er 2D-elementer og vises derfor ikke i Catenda 3D-viseren.

---

### 3.3 **Egenskapsett**

![Egenskapsett](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/11-property-sets.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/12-property-sets.png)

Eksporterer alle Revit-egenskapsett (pset / egenskaper) Her er et eksempel på en vegg eksportert med dette alternativet: Revit (_Venstre_) --- Catenda (_Høyre_)

<img alt="Egenskaper" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-4f4aab46be4e.png" width="208.60495436766624"/>  ---  <img alt="Egenskaper" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-7c05fd3c2c4a.png" width="190.21739130434784"/>

Typiske egenskaper som vises i egenskapsmenyen er: Constraints, Cross-Section Definition, Dimensions, Structural, Identity Data, Other

Typiske egenskaper som vises i Identifikasjonsmenyen er: IFC-parametere Eksporter standard IFC-egenskaper. Eksporterer beregnede mengder av objekter. Eksportbatchlister Eksporter engangseiendomsett

_Klassifikasjonsinnstillinger_ Her er et eksempel på hvordan klassifikasjonsinnstillinger kan se ut med omniclass.

![Klassifikasjonsinnstillinger](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/13-property-sets.png)

_Navn_ Navn på klassifikasjonen

_Kilde (Utgiver)_ Utgiver av klassifikasjonen

_Utgave_ Klassifikasjonsutgaven

_Utgavedato_ Datoen for klassifikasjonen

_Dokumentasjonslokasjon_ Dette må være en gyldig dokumentasjonslokasjon

_Klassifikasjonsfeltname_ Klassifikasjonsfeltnavnet er navnet på parameteren i objektene dine som skal inneholde klassifikasjonsverdien. Denne parameteren finnes ofte på familienivå. Rediger en familie for å se dens egenskaper

![Rediger familie](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/14-property-sets.png)

Slik kan parameteren se ut i egenskapene

![Properties OmniClass Number](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/15-property-sets.png)

Hvis du har eksportert ifc-en din med en klassifikasjon og importert den som en modell til Catenda, vil du se klassifikasjonen foreslått som et [foreslått bibliotek](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca) når du oppretter et nytt bibliotek på [biblioteksiden](https://support.catenda.com/en/articles/8065645-libraries-page). Hvis en verdi i egenskapen du spesifiserte stemmer overens med en verdi i dokumentasjonen som er gitt, vil den bli funnet og kan brukes til å velge objekter med denne verdien gjennom klassifikasjonsbiblioteket du opprettet.

---

### 3.4 **Detaljnivå**

![Detaljnivå](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/16-level-of-detail.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/17-level-of-detail.png)

Dette handler om hvor detaljert vi har for eksempel. kopper eller rekkverk eller kanskje sykkelhjul. Det er 4 forskjellige detaljnivåer.

Ekstra lavt Lavt Medium Høyt

Når høy, får det mest detaljert som vist på bildet nedenfor.

![Detaljnivå ekstra lavt og høyt](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/18-level-of-detail.png)

---

Når du eksporterer IFC-er fra Revit for bruk i Catenda Hub, anbefaler vi ikke å sette detaljnivået til høyt. Det vil være mange detaljer og ekstra polygoner i modeller når de eksporteres med høyere detaljnivå, og dette er ikke alltid nødvendig og vil gjøre modellnavigasjonen langsommere. Dette er et eksempel på forskjellen mellom eksportering med innstillingen Ekstra lavt og Høyt.

![Dette er en trapperekkverk eksportert med innstillingen Høy. 900k polygoner](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/19-level-of-detail.png)

![Dette er den samme modellen eksportert med innstillingen Ekstra lavt. 33k polygoner.](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/20-level-of-detail.png)

Utseendet på modellen vil være nesten det samme, men antallet polygoner vil reduseres drastisk og navigasjonen i Catenda Hub vil være mye raskere.

---

### 3.5 **Avansert**

![Avansert](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/21-advanced.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/22-advanced.png)

_Eksporter deler som bygningselementer_ Eksporter deler som standard IFC-element.

_Tillat bruk av blandet "Solid Model"-representasjon_ Velg dette alternativet for å tillate blanding av BRep og ekstrumeringsgeometrier for en enhet.

_Bruk aktiv visning ved oppretting av geometri_ Velg dette alternativet for å bruke den aktive visuingen til å generere geometrien. Merk at dette kan ha uventede resultater hvis det brukes på en ikke-3D-visning.

_Bruk familie- og typnavn for referanse_ Velg dette alternativet for å bruke familie- og typenavnene for referanser.

_Bruk 2D-romgrenser for romvolum_ Velg dette alternativet for å bruke en forenklet tilnærming til beregning av romvolum (basert på ekstrudering av 2D-romgrenser) som også er standard ved eksportering til IFC 2x2.

_Inkluder IFCSite-høyde i plasseringsopprinnelsen på stedet_ Velg dette alternativet for å inkludere høyden fra Z-offset for lokal posisjon i IfcSite. Fjern alternativet for å utelukke det.

_Lagre IFC GUID i en elementparameter etter eksport_ Velg dette alternativet for å lagre de genererte IFC GUID-ene til prosjektfilen etter eksport. Dette vil legge til "IFC GUID"-parametere til elementer og deres typer og prosjektinformasjon for prosjekt-, nettsted- og bygningsveiledninger.

_Eksporterer avgrensningsboks_ Velg dette alternativet for å eksportere "Bounding box"-representasjoner. Dette alternativet forblir automatisk valgt for GSA-eksport.

_Behold tesselert geometri som triangulering_ Hvis du har komplekse buede elementer eller skall og de ikke vises riktig etter IFC-eksporten, kan du velge dette alternativet. Husk at du kanskje produserer en veldig tung IFC-fil.

_Bruk bare typnavn for IFCType-navn_ Velg dette alternativet hvis du vil at BAT-ID-en eller ID-en til objektet skal vises som navnet på enheten.

_Bruk synlig Revit-navn som IFCEntity-navn_ Velg dette alternativet hvis du vil at Revit-objektets navn skal være navnet på enheten

_Eksporter alltid fasetterte gulv og tak som en enkelt IFC-enhet_ Velg dette alternativet for å kombinere flater av gulv og tak med flere flater til en enkelt enhet.

_Angi "Sist endret" bruker til forfatteren i prosjektinformasjon_ Velg dette alternativet hvis du er forfatteren av endringene i denne eksporten

_Enheter for eksport_ Slik kan menyen IFC Entity Selection som åpnes se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/23-advanced.png)

---

### 3.6 **Geografisk referanse**

Det er viktig at Revit-koordinatene dine er synkronisert med de andre modellene i prosjektet ditt slik at de ender opp på samme sted. Mål derfor koordinatene i Catenda Hub med en punktmåling og spesifiser en koordinatbase i Revit på et punkt som er på samme sted som det målte punktet i Catenda Hub.

![Spesifiser koordinat på punkt](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/24-geographic-reference.png)

Du finner dette alternativet i Administrer-fanen -> Koordinater -> Spesifiser koordinatbase. _Spesifiser koordinater på punkt_ Omflytter en modell og roterer modellen til ekte nord ved å spesifisere koordinater for nord/sør, øst/vest og høyde. I Revit er det ofte lettere å modellere i 90-graders vinkler og du ønsker ikke å rotere hele modellen. I dette tilfellet kan du rotere True North i stedet. Du finner alternativet i rullegardinmenyen Posisjon under Koordinater i Administrer-fanen.

![Geografisk referanse](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/25-geographic-reference.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/26-geographic-reference.png)

_Prosjektsted_ Internt

_Koordinatbase_ Du kan endre denne innstillingen for å sikre at prosjektet ditt er orientert mot nord Delte koordinater - Standardundersøkelsespunkt Prosjektbasispunkt Internt opphav Prosjektbasispunkt orientert mot ekte nord Internt opphav orientert mot ekte nord

> **Merknad:** Hvis du kobler IFC i Sett inn-fanen, vil den koblede filen bli plassert nær objektene dine og vil ikke være på stedet som er beskrevet i IFC-en. For å importere en IFC til riktig sted, klikker du File -> Open -> IFC i stedet.

_Overstyring_ Her kan du overstyre den projiserte koordinatsystemreferansen

---

### 3.7 **Selskapsinformasjon**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/27-company-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/28-company-info.png)

Denne menyen er bare tilgjengelig når IFC2x3 COBie 2.4 Design Deliverable View Setup er valgt i menyen til venstre.

---

### 3.8 **Prosjektinfo**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/29-project-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/30-project-info.png)

Denne menyen er bare tilgjengelig når IFC2x3 COBie 2.4 Design Deliverable View Setup er valgt i menyen til venstre.

---

## 4. **IFC-alternativer**

IFC-alternativene for et Revit-prosjekt finnes i:

`File -> Export -> Options -> IFC Options`

![Export -> Options -> IFC options](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/31-ifc-options.png)

> **Merknad:** Fra Revit 2026 er dette alternativet nå tilgjengelig i: `Export -> IFC -> General -> Category Mapping -> Action menu right of dropdown`

Her i _IFC-alternativene_ gjør vi innstillingene for eksportering av en modell til en IFC-fil. Her kan du tilpasse oppsettegenskaper for eksportering av en modell til IFC. Det som ble nevnt i starten av denne manualen, er at det ikke er nødvendig å få ut for mye informasjon fra modellen. Vær gjerne med på å merke av for unødvendig informasjon før eksport.

![IFC-eksportklasser](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/32-ifc-options.png)

Det er mulig å vise rutenett i Catenda Hub, og hvis du har disse i Revit-modellen din, kan du i IFC-alternativene angi at rutenett skal eksporteres i IFC-en. Som standard eksporteres disse ikke fra Revit.

## 5. **Farger og materialer**

Fargene som vises i Catenda blir lest fra IFC-filen som importeres. Når materialegenskapen til en familie legges til IFC-parameterne, legges fargen på materialet i materialegenskapen til IFC-en og vises således i Catenda. I Revit finnes materialer i materialleseren:

`Administrer-fanen -> Innstillinger-seksjon -> Materialer`
I materialleseren finnes innstillingen for farge i grafikkfanen til materialet:

![Administrer -> Materialer -> Materialleser -> Opprett nytt material](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/33-colors-and-materials.png)

Det er også mulig å låse skyggingen til renderingsinnstillingene.

![Utseende](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/34-colors-and-materials.png)

Flater i Catenda 3D-viseren har flat skygging uten en lyskilde til stede. Følgende verdier tolkes av Catenda når overflaten vises i 3D-viseren:

Generisk

- Farge
- Bildeavfading

Gjennomsiktighet

- Beløp
- Bildeavfading
- Lysgjennomtrengelighet

Tint

- Tintfarge
