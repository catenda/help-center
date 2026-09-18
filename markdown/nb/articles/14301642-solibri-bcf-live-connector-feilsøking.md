# Solibri BCF Live Connector-feilsøking

Feil som kan oppstå med Solibri-dokumentintegreringen og hvordan du løser dem, forklares i denne artikkelen.

## 1. **Støtte og feilsøking**

BCF Live Connector er utviklet, vedlikeholdt og eid av Solibri. Siden denne integreringen er et uavhengig produkt opprettet av Solibri for å koble seg til Catenda API, er vår støtte fokusert på datautveksling snarere enn den interne mekanikken i Solibri-programvaren selv.

### 1.1 **For arbeidsflyt- og dataspørsmål**

Hvis du trenger hjelp til å forstå hvordan funksjoner fungerer innen integreringen, eller hvordan informasjon representeres i Catenda når den er synkronisert, er teamet vårt glad for å assistere. Vi kan hjelpe deg med å navigere i den tiltenkte arbeidsflyten og sikre at prosjektdataene dine kommuniserer korrekt mellom de to plattformene.

### 1.2 **For tekniske og funksjonelle problemer**

Hvis du møter spesifikke feilmeldinger i Solibri-grensesnittet, hvis koblingen ikke svarer som forventet, eller hvis du ønsker en endring i hvordan koblingen fungerer, kontakt **[Solibri Support](https://www.solibri.com/support)** direkte. Som utviklere og eiere av koblingen er de de eneste som kan endre den underliggende koden, justere interne valideringsregler eller feilsøke programvarespecifikke feil.

## 2. **Dupliseringsmodell**

Når denne feilen oppstår, er det typisk fordi Solibri-koblingen har identifisert to modeller som deler samme IFCProject GUID.

### 2.1 **Navn vs. ID-er**

Catenda og Solibri-koblingen identifiserer modeller basert på deres unike GUID, ikke filnavnet deres.

Hvis to forskjellige filer i Solibri Selection Basket ble eksportert fra samme originalfil i redigeringsverktøyet ditt (f.eks. Revit, ArchiCAD), vil de sannsynligvis dele samme IFCProject GUID.

Selv om disse filene gis forskjellige navn i Solibri, gjenkjenner koblingen dem som samme enhet og utløser en "Duplisering"-advarsel for å forhindre dataksynkroniseringskonflikter.

### 2.2 **Hvordan verifisere GUID-en i Solibri**

For å bekrefte om modellene dine deler samme identifikator, sjekk metadata direkte i Solibri:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ym9bebpy/01-how-to-verify-the-guid-in-solibri.png)

1. Velg **Modell** i Solibri Model Tree.
1. Åpne **Info Tool** eller **Identity**-fanen.
1. Finn **IFCProject GUID**-feltet.

Hvis to modeller viser samme tegnserie her, vil koblingen behandle dem som samme modell.
