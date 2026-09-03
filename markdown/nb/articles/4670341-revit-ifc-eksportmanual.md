# Revit IFC Eksportmanual

Med denne IFC-eksportmanualen er målet å gi brukeren en veiledning om hvordan eksportere IFC for riktige formål. En IFC-fil kan raskt bli tung og stor når du har mye informasjon som skal ut av modellen. Derfor må du når du eksporterer en IFC, fjerne avmerkingen for unødvendig informasjon. Når du laster opp en modell til Catenda, er det ikke alltid nødvendig å ha mye informasjon og høy detaljnivå i modellen. Litt senere i denne manualen skal vi gå tilbake til hvilke innstillinger vi anbefaler for å gjøre modellen litt mindre og litt enklere å arbeide med. Her skal vi gjennomgå trinn for trinn den mest passende måten å eksportere en IFC fra Revit til Catenda.

## 1. **Prosjektinnstillinger**

Før eksport er det viktig å sikre at GUID-ene i Revit-prosjektet ditt er korrekte.

`Administrer -> Innstillinger -> Prosjektinformasjon -> IFC-parametere`

![Prosjektinformasjon IFC-parametere IfcSite GUID IfcBuilding GUID IfcProject GUID](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/01-project-settings.png)

Hvis GUID-en er forskjellig fra en tidligere eksport, vil objektene fra nyere eksporter ikke være korrekt koblet til GUID-ene i BCF-saker. Når du oppretter et nytt prosjekt, får det en unik ID.

## 2. **Endre IFC-eksport**

Når Revit er åpent og du er klar for eksport, kan det være lurt å gjøre følgende.

![På øverst til venstre på skjermen, trykk på fil](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/02-modify-ifc-export.png)

Øverst til venstre finner vi fanen "Fil".

---

> **Tips:** **Husk:** _Det kan være lurt å ha en dedikert mappe for IFC-filene dine, slik at du alltid har kontroll over hvor filen befinner seg!_

IFC-eksportmenyen finner du her:

`Fil -> Eksporter -> IFC`

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/03-modify-ifc-export.png)

Slik kan IFC-eksportmenyen se ut:

![Eksporter IFC](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/04-modify-ifc-export.png)

Filnavn Skriv inn navn og plassering som den eksporterte filen skal ha i systemet

Eksportoppsett Velg mellom følgende forhåndsdefinerte oppsett: \<In-Session Setup> IFC 2x3 Coordination View IFC 2x3 Coordination View IFC 2x3 GSA Concept Design BIM 2010 IFC 2x3 Basic FM Handover View IFC 2x3 Coordination View IFC 2x3 COBie 2.4 Design Deliverable View IFC4 Reference View [Architecture] IFC4 Reference View [Structural] IFC4 Reference View [BuildingService] IFC4 Reference View [Unofficial] IFC4x3 IFC-SG Regulatory Requirements View

Når Catenda-programtillegget for Revit brukes, legges det til et ekstra forhåndsdefinert eksportoppsett for bruk med Catenda i listen over alternativer.

## 3. **Endre oppsett**

Klikk på Endre oppsett i eksportoppsettet i dialogen for IFC-eksport. Dette er der de nødvendige innstillingene for IFC-eksporter kan endres og egendefinerte oppsett kan opprettes. Slik kan menyen Endre oppsett se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/05-modify-setup.png)

Dette vinduet inneholder følgende faner:

---

### 3.1 **Generelt**

![Generelt](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/06-general.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/07-general.png)

Vi skal gå gjennom de ulike innstillingene.

_IFC-versjon_ Valg av IFC-versjon.

_Utvekslingskrav_ Disse alternativene kan endres avhengig av hvilken IFC-versjon som er valgt. IFC 2x3 Coordination View

- Arkitekturreferenceutveksling
- MEP Reference Exchange
- Strukturell referanseutveksling

_Kategorikartlegging_ Før Revit 2026 var dette alternativet tilgjengelig i Fil -> Eksporter -> Alternativer -> IFC-eksportalternativer. Slik kan menyen Administrer IFC-eksportkartleggingsinnstillinger se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/08-general.png)

_Filtype_ IFC-typevalg.

_Fase som skal eksporteres_ Hvis du har brukt faseverktøyet i Revit, kan du her velge og bare eksportere nye eller eksisterende strukturer.

_Roombegrensninger_ Alt dette handler om hvordan roominformasjon kan brukes videre. a. 1. nivå - Eksempel på bruk: Mengdeuttrekk, administrasjon, drift og vedlikehold (FDVU). b. 2. nivå - Eksempel på bruk: Energianalyse, lysanalyse.

_Anleggstype_ Dette alternativet er bare tilgjengelig for IFC 4x3 Velg mellom et av følgende: Bru (IfcBridge) Bygning (IfcBuilding) Marineanlegg (IfcMarineFacility) Jernbane (IfcRailway) Vei (IfcRoad)

_Del vegger, søyler, kanaler etter nivå_ Her kan du f. eks. dele vegger horisontalt hvis de er modellert over flere etasjer.

_Filhodetinformasjon... Prosjektadresse..._ I disse kan du legge inn informasjon om hvem som har levert IFC-en, prosjektadresse osv.

_Prosjektopprinnelse_ Prosjektopprinnelse, dette setter vi på Gjeldende delte koordinater- Presentere delte koordinater.

> **Merknad:** Dette er flyttet til Geografisk referanse fra Revit 2025

_Inkluder stålkomponenter_ Inkluderer stålkomponenter hvis modellert.

> **Merknad:** Dette er flyttet til Tilleggsinnhold fra Revit 2025

---

### 3.2 **Tilleggsinnhold**

![Tillegginnhold](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/09-additional-content.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/10-additional-content.png)

Eksporter koblede filer som separate IFC-filer Hvis du vil ta med de koblede filene i IFC-en, kan du merke av dette alternativet. Det anbefales at du eksporterer hver fil separat og importerer hver til sin egen modell.

Eksporter bare synlige objekter synlige i visning IFC-fil.

- Eksporter rom, områder og mellomrom i 3D-visninger
  Dette alternativet kan være nyttig for å velge områder i 2D-visningen.

Inkluder stålkomponenter, _fyllt_

Eksporterer 2D-planvisningselementer, _fyllt, områder_ (riper).

Eksporter takgitter Takgitter er 2D-elementer og vises derfor ikke i Catenda 3D-visningen.

---

### 3.3 **Egenskapssett**

![Egenskapsett](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/11-property-sets.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/12-property-sets.png)

Eksporterer alle Revit-egenskapssett (pset / egenskaper) Her er et eksempel på en vegg eksportert med dette alternativet: Revit (_Venstre_) --- Catenda (_Høyre_)

<img alt="Egenskaper" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-4f4aab46be4e.png" width="208.60495436766624"/>  ---  <img alt="Egenskaper" src="https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/inline-7c05fd3c2c4a.png" width="190.21739130434784"/>

Typiske egenskaper som vises i egenskapsmenyen er: Begrensninger, Tverrsnittsdefinisjon, Dimensjoner, Strukturell, Identitetsdata, Annet

Typiske egenskaper som vises i Identifikasjonsmenyen er: IFC-parametere Eksporter standard IFC-egenskaper. Eksporterer beregnede mengder av objekter. Eksportbatchlister Eksporter engangseiendomssett

_Klassifikasjonsinnstillinger_ Her er et eksempel på hvordan klassifikasjonsinnstillinger kan se ut med omniclass.

![Klassifikasjonsinnstillinger](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/13-property-sets.png)

_Navn_ Navnet på klassifikasjonen

_Kilde (utgiver)_ Utgiver av klassifikasjonen

_Utgave_ Klassifikasjonsutgaven

_Utgavedato_ Datoen for klassifikasjonen

_Dokumentasjonsplassering_ Dette må være en gyldig dokumentasjonsplassering

_Klassifikasjonfeltname_ Klassifikasjonfeltnavnet er navnet på parameteren i objektene dine som skal inneholde klassifikasjonsverdien. Denne parameteren finnes ofte på familienivå. Rediger en familie for å se egenskapene

![Rediger familie](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/14-property-sets.png)

Slik kan parameteren se ut i egenskapene

![Egenskaper OmniClass-nummer](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/15-property-sets.png)

Hvis du har eksportert IFC-en din med en klassifikasjon og importert den som en modell til Catenda, vil du se klassifikasjonen foreslått som et [foreslått bibliotek](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca) når du oppretter et nytt bibliotek på [biblioteksiden](https://support.catenda.com/en/articles/8065645-libraries-page). Hvis en verdi i egenskapen du har angitt stemmer overens med en verdi i dokumentasjonen som er gitt, blir den funnet og kan brukes til å velge objekter med denne verdien gjennom klassifikasjonsbiblioteket du opprettet.

---

### 3.4 **Detaljnivå**

![Detaljnivå](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/16-level-of-detail.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/17-level-of-detail.png)

Dette handler om hvor detaljert vi har for eksempel. kopper eller håndløpere eller kanskje sykkelhjul. Det er 4 ulike detaljnivåer.

Ekstra lavt lavt Medium høyt

Når høyt, blir det mest detaljert som vist på bildet nedenfor.

![Detaljnivå ekstra lavt og høyt](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/18-level-of-detail.png)

---

Når du eksporterer IFC-filer fra Revit som skal brukes i Catenda Hub, anbefaler vi ikke å sette detaljnivået til høyt. Det blir mye detaljer og ekstra polygoner i modeller når eksportert med høyere detaljnivå og dette er ikke alltid nødvendig og vil gjøre modelnavigasjonen saktere. Dette er et eksempel på forskjellen mellom eksportering med innstillingen Ekstra lavt og høyt.

![Dette er et trapperekkverkeksportert med innstillingen Høyt. 900k polygoner](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/19-level-of-detail.png)

![Dette er den samme modellen eksportert med innstillingen Ekstra lavt. 33k polygoner.](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/20-level-of-detail.png)

Utseendet på modellen vil være nesten det samme, men antallet polygoner vil reduseres drastisk og navigasjonen i Catenda Hub vil være mye raskere.

---

### 3.5 **Avansert**

![Avansert](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/21-advanced.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/22-advanced.png)

_Eksporter deler som byggelementer_ Eksporter deler som standard IFC-element.

_Tillat bruk av blandet "Solid Model"-representasjon_ Velg dette alternativet for å tillate blanding av BRep- og ekstrusjonsgeometrier for en enhet.

_Bruk aktiv visning når du lager geometri_ Velg dette alternativet for å bruke den aktive visningen til å generere geometrien. Vær oppmerksom på at dette kan gi uventede resultater hvis det brukes på en ikke-3D-visning.

_Bruk familie- og typenavn for referanse_ Velg dette alternativet for å bruke familie- og typenavnene for referanser.

_Bruk 2D-roombegrensninger for romvolum_ Velg dette alternativet for å bruke en forenklet tilnærming for beregning av romvolum (basert på ekstruksjon av 2D-roombegrensninger) som også er standard ved eksportering til IFC 2x2.

_Inkluder IfcSite-høyde i stedens lokale plassering av opprinnelse_ Velg dette alternativet for å inkludere høyden fra Z-forskyvningen for lokal posisjon i IfcSite. Fjern alternativet for å utelukke det.

_Lagre IFC GUID i en elementparameter etter eksport_ Velg dette alternativet for å lagre de genererte IFC GUID-ene i prosjektfilen etter eksport. Dette legger til "IFC GUID"-parametere til elementer og deres typer samt prosjektinformasjon for prosjekt-, nettsted- og bygningsveiledninger.

_Eksporter grenseboks_ Velg dette alternativet for å eksportere "Grenseboks"-representasjoner. Dette alternativet blir automatisk valgt for GSA-eksport.

_Behold tessellert geometri som triangulering_ Hvis du har komplekse buede elementer eller skall og de ikke vises korrekt etter IFC-eksporten, kan du velge dette alternativet. Vær oppmerksom på at du kan produsere en veldig tung IFC-fil.

_Bruk bare typenavn for IfcType-navn_ Velg dette alternativet hvis du vil at BAT-ID-en eller ID-en til objektet skal vises som navnet på enheten.

_Bruk synlig Revit-navn som IfcEntity-navn_ Velg dette alternativet hvis du vil at Revit-objektnavnet skal være navnet på enheten

_Eksporter alltid fasetterte gulv og tak som en enkelt IFC-enhet_ Velg dette alternativet for å kombinere flater av gulv og tak med flere flater til en enkelt enhet.

_Sett "Sist endret"-bruker til forfatteren i prosjektinformasjon_ Velg dette alternativet hvis du er forfatteren av endringene i denne eksporten

_Enheter som skal eksporteres_ Slik kan IFC-enhetsvalgsmenyen som åpnes se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/23-advanced.png)

---

### 3.6 **Geografisk referanse**

Det er viktig at Revit-koordinatene dine er synkronisert med de andre modellene i prosjektet ditt slik at de ender opp på samme sted. Mål derfor koordinatene i Catenda Hub med en punktmål og angi en koordinatbase i Revit på et punkt som er på samme sted som det målte punktet i Catenda Hub.

![Spesifiser koordinat på punkt](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/24-geographic-reference.png)

Du finner dette alternativet i kategorien Administrer -> Koordinater -> Angi koordinatbase. _Angi koordinater på punkt_ Omplacerer en modell og roterer modellen til sann nord ved å spesifisere koordinater for nord/syd, øst/vest og høyde. I Revit er det ofte lettere å modellere med 90-graders vinkler og du vil kanskje ikke rotere hele modellen. I dette tilfellet kan du rotere sann nord i stedet. Du finner alternativet i rullegardinmenyen Posisjon under Koordinater i kategorien Administrer.

![Geografisk referanse](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/25-geographic-reference.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/26-geographic-reference.png)

_Prosjektsted_ Internt

_Koordinatbase_ Du kan endre denne innstillingen for å sørge for at prosjektet ditt er orientert mot nord Delte koordinater - standard referansepunkt Prosjektbasispunkt Internt opprinnelse Prosjektbasispunkt orientert mot sann nord Internt opprinnelse orientert mot sann nord

> **Merknad:** Hvis du kobler IFC i Sett inn-fanen, plasseres den koblede filen nær objektene dine og vil ikke være på plasseringen beskrevet i IFC-en. For å importere en IFC til riktig plassering klikker du Fil -> Åpne -> IFC i stedet.

_Overstyring_ Her kan du overstyre det projiserte koordinatsystemreferansen

---

### 3.7 **Bedriftsinformasjon**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/27-company-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/28-company-info.png)

Denne menyen er bare tilgjengelig når oppsettet IFC2x3 COBie 2.4 Design Deliverable View er valgt i menyen til venstre.

---

### 3.8 **Prosjektinformasjon**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/29-project-info.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/30-project-info.png)

Denne menyen er bare tilgjengelig når oppsettet IFC2x3 COBie 2.4 Design Deliverable View er valgt i menyen til venstre.

---

## 4. **IFC-alternativer**

IFC-alternativene for et Revit-prosjekt finner du i:

`Fil -> Eksporter -> Alternativer -> IFC-alternativer`

![Eksporter -> Alternativer -> IFC-alternativer](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/31-ifc-options.png)

> **Merknad:** Fra Revit 2026 er dette alternativet nå tilgjengelig i: `Eksporter -> IFC -> Generelt -> Kategorikartlegging -> Handlingsmeny til høyre for rullegardin`

Her i _IFC-alternativene_ gjør vi innstillingene for eksportering av en modell til en IFC-fil. Her kan du tilpasse oppsettsegenskaper for eksportering av en modell til IFC. Det som ble nevnt i begynnelsen av denne manualen er at det ikke er nødvendig å ta for mye informasjon ut av modellen. Fjern gjerne avmerkingen for unødvendig informasjon før eksport.

![IFC-eksportklasser](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/32-ifc-options.png)

Det er mulig å vise rutenett i Catenda Hub, og hvis du har disse i Revit-modellen din, er det i IFC-alternativer du kan sette rutenett til å eksporteres i IFC-en. Som standard eksporteres disse ikke fra Revit.

## 5. **Farger og materialer**

Fargene som vises i Catenda, leses fra IFC-filen som importeres. Når materialegenskapen til en familie legges til IFC-parametrene, legges fargen på materialet i materialegenskapen til IFC-en og vises dermed i Catenda. I Revit finner du materialer i materialleseren:

`Administrer-fane -> Innstillinger-seksjon -> Materialer`
I materialleseren finner du innstillingen for farge i grafikkfanen til materialet:

![Behandle -> Materialer -> Materialleser -> Opprett nytt materiale](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/33-colors-and-materials.png)

Det er også mulig å låse skyggingen til gjengivelsesinnstillingene.

![Utseende](https://raw.githubusercontent.com/catenda/help-center/main/images/k2nekg1n/34-colors-and-materials.png)

Flater i Catenda 3D-visningen har flat skygging uten en lyskildestat. Følgende verdier tolkes av Catenda når flaten vises i 3D-visningen:

Generisk

- Farge
- Bildeutfading

Transparens

- Beløp
- Bildeutfading
- Gjennomsiktighet

Fargetone

- Tintfarge
