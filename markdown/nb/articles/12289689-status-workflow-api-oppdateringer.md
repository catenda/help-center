# Status Workflow - API-oppdateringer

> Introduksjon av API-endringer for den nye Status Workflow-funksjonen, der vi differensierer mellom delt og publisert status i samsvar med ISO 19650. Denne artikkelen er rettet mot kunder og integreringspartnere som bruker Catenda API.

Vi implementerer **Status Workflow**, en betydelig oppdatering av hvordan Catenda håndterer dokument- og modelrevisjoner. Denne endringen introduserer en distinksjonstion mellom arbeids- og offisielle revisjoner som kan kreve justeringer i integrasjonen din.

## 1. Sammendrag

Catenda vil differensiere mellom:

- **"Delt"** revisjoner (arbeids-/utkastvarsjoner)
- **"Publisert"** revisjoner (offisielle/godkjente versjoner)

_Umiddelbar handling kreves hvis:_

- Appen din er integrert med Catenda Hub
- Du viser revisjonsinformasjon til brukere
- Du oppretter nye revisjoner gjennom API
- Du bruker CAD-verktøyplugin-moduler

## 2. Hva som endres

### 2.1 Revisjonstyper

Tidligere ble alle revisjoner implicit ansett som "offisielle." Nå:

- **"Delt"**: Samarbeidende arbeidsrevisjoner med begrenset synlighet
- **"Publisert"**: Offisielle revisjoner for bredere distribusjon

### 2.2 API-responsendringer

**Dokument-API** vil inkludere nye felt for bibliotekselementer:

```
{  "document": {    "revision": {      "extendedVersion": {        "major": 1,        "minor": null  // eller 1,2,3 for Delt      },      "version": 5  // Eldre nummerering opprettholdt    }  }}
```

**Modeller-API**-endringer er minimale:

- Legger til filtreringsmulighet via omfangsparameter (scope=published eller scope=all)
- Viser IKKE revisjonsstatus eller utvidet nummerering
- Håndhever rettigheter arvet fra underliggende dokumenter

### 2.3 Standardoppførsel

**Viktig**: APIer vil returnere **både** "Delt" og "Publisert" revisjoner som standard der brukere har tilgang. Dette opprettholder bakoverkompatibilitet, men endrer fundamentalt arten av returnerte data.

## 3. Hvem som er berørt og hvordan

### 3.1 Ikke berørt

- ✅ Frittstående API-applikasjoner uten Catenda Hub-avhengighet
- ✅ Applikasjoner som ikke viser eller håndterer revisjoner

### 3.2 Betydelig berørt - CAD-verktøyplugin-moduler

⚠️ **Kritiske problemer:**

- Kan ikke fastslå om "Delt" eller "Publisert" revisjoner opprettes
- Kan ikke vise nøyaktig revisjonsstatus for brukere
- Kan vise annen nummerering enn Hub (sekvensiell vs. X.Y-format)
- Brukere forstår ikke revisjonskontekst uten statussynlighet

_Nødvendig handling for plugin-utviklere:_

1. Vurder om du viser revisjonsinformasjon
1. Vurder å legge til brukerveiledning om revisjonstyper
1. Planlegg for potensiell brukerforrvirring om nummereringsulikheter

### 3.3 Også berørt

⚠️ Applikasjoner som:

- Viser revisjonslister til brukere
- Oppretter nye revisjoner via API
- Avhenger av at alle revisjoner er "offisielle"
- Bruker Catenda Site-integrasjon

## 4. Teknisk implementeringsveiledning

### 4.1 Filtrering av revisjoner

Bruk den nye omfangsparameteren for å kontrollere hvilke revisjoner som returneres:

```
# Dokument-API GET /documents?scope=published     # Bare publisertGET /documents?scope=shared        # Bare delt (krever tillatelse)GET /documents                     # Alt (standard)# Modeller-API GET /models/revisions?scope=published  # Bare publisertGET /models/revisions                  # Alt (standard)
```

### 4.2 Rettighetetsendringer

Nye ACL-rettigheter påvirker operasjonene dine:

- **Visning av "Delt" revisjoner**: Krever spesifikk tillatelse
- **Opprettelse av "Publisert" revisjoner**: Kun mulig gjennom Catenda Hub UI
- **API-revisjonopprettelse**: Oppretter "Delt" revisjoner som standard

### 4.3 Hva du ikke kan gjøre via API

- ❌ Opprett "Publisert" revisjoner (kun Hub)
- ❌ Få tilgang til revisjonsstatus i Modeller-API
- ❌ Se utvidet nummerering (X.Y) i Modeller-API
- ❌ Fastslå modell-til-dokument-forhold

## 5. Migreringshensyn

_Eksisterende prosjekter:_

- Alle gjeldende revisjoner vil bli "Publisert" ved migrasjon
- Versionsnumre blir hovedrevisjonsnumre (f.eks. v3 → 3)
- Ingen handling nødvendig for historiske data

_Ny oppførsel:_

- Nye revisjoner opprettet via API = "Delt" som standard
- Publisering krever manuell handling i Hub

## 6. Kritiske beslutninger for implementeringen din

**Spørsmål 1**: Trenger du bare offisielle revisjoner?

- **Ja** → Implementer `scope=published`-filtrering
- **Nei** → Forbered deg på å håndtere blandede revisjonstyper

**Spørsmål 2**: Viser du revisjonsinformasjon?

- **Ja** → Planlegg for nummereringsavvik (spesielt for Modeller-API-brukere)
- **Nei** → Minimal påvirkning forventet

**Spørsmål 3**: Oppretter brukere revisjoner gjennom appen din?

- **Ja** → Informer brukere om at de oppretter "Delt" revisjoner
- **Nei** → Ingen handling nødvendig

## 7. Kjente begrensninger og løsninger

_For Modeller-API-brukere:_

- **Begrensning**: Kan ikke få tilgang til revisjonsstatus eller utvidet nummerering
- **Løsning**: Bruk filtrering for å få bare ønskede revisjonstyper
- **Brukerpåvirkning**: Potensiell forvirring om revisjonsnummereringsforskjeller

_For Collection API-brukere:_

- Bare "Publisert" revisjoner kan legges til i samlinger
- Dette kan endres basert på tilbakemelding fra kunder

## 8. Støtteressurser

_Tilgjengelige dokumentasjonsoppdateringer:_

- [Oppdatert API-referanse] - Inkluderer ny `scope`-parameter

## 9. Vanlige spørsmål

_Sp: Brytes integrasjonen min?_ Sv: Ingen API-endringer som bryter, men brukeropplevelsen kan endres betydelig, spesielt for CAD-plugin-moduler.

_Sp: Hvorfor kan jeg ikke se revisjonsstatus i Modeller-API?_ Sv: For å opprettholde bakoverkompatibilitet viser Modeller-API Status Workflow-funksjoner minimalt. Bruk filtrering for å kontrollere returnerte revisjoner.

_Sp: Hvordan vet brukere hvilken type revisjon de oppretter?_ Sv: Via API blir alle nye revisjoner "Delt." Brukere må bruke Catenda Hub for å opprette "Publisert" revisjoner.

_Sp: Hva hvis vi trenger mer tid til å tilpasse oss?_ Sv: Kontakt oss umiddelbart. Status Workflow blir aktivert gradvis, og vi kan diskutere tidsplanalternativer for organisasjonen din.
