# Bruk av revisjonsnavn

> Utforsk praktiske eksempler på revisjonsnavn. Lær hvordan team balanserer plass og lesbarhet ved hjelp av versjonsekvenser, statuskartlegging og kompakte YYMMDD eller klare YYYYMMDD-prefikser optimalisert for kronologisk dokumentsortering.

Når du aktiverer en navnekonvensjon i en mappe, tilpasser prosjektteam ofte dynamiske blokker for å passe til spesifikke interne sporingsarbeidsflyten. Nedenfor er praktiske eksempler på hvordan ulike team bruker egendefinerte felt og **Dokumentidentifikator**-bryteren for å opprettholde et organisert arbeidsområde.

## 1. **1. Prosjektroller og implementeringsstrategier**

Bruken av navnekonvensjoner drives vanligvis enten av et mandat fra prosjekteieren eller av et ønske blant prosjektmedlemmer om å få et klarere overblikk over filene sine. En strukturert navnekonvensjon lar teammedlemmer søke etter spesifikke komponenter i dokumentnavn mer effektivt. Uansett hvem som initierer arbeidsflyten, må prosjektmedlemmer kontakte en prosjektadministrator for å konfigurere og aktivere navnekonvensjonen, da administratortilgang kreves for å endre disse innstillingene.

Omfanget av implementeringen avhenger generelt av hvem som ber om det:

### 1.1 **1.1 Prosjekteiers mandater**

Når en konvensjon kreves av prosjekteieren, implementeres den ofte på hele prosjektet. I disse scenariene opprettes ofte en separat, utpekt mappe for å romme dokumenter som ikke oppfyller de strenge konvenjonskravene.

### 1.2 **1.2 Forespørsler fra prosjektmedlemmer**

Når en konvensjon bes om av en enkeltperson eller en bestemt undergruppe for å forbedre en lokalisert arbeidsflyt, aktiveres den vanligvis bare i deres spesifikke arbeidsmapper, mens resten av prosjektteamet fortsetter å fungere uten konvensjon.

## 2. **2. Versjonsekvens-arbeidsflyter**

Versjonsekvensering brukes til å spore påfølgende fileoppdateringer. Avhengig av prosjektkrav velger team mellom utvidbare variable-lengde-spor, rigide bindestrek-polstrede plassholdere eller enkle numeriske indikatorer.

### 2.1 Standard versjonsekvens (`v1`, `v2`, `v3`)

_2.1.1 Teamet_ Liam (BIM-leder) og Sophia (Konstruktøringeniør).

_2.1.2 Arbeidsflyten_ Sophia laster jevnlig opp strukturelle modellfiler til plattformen. Liam krever at alle innkommende modeller skal være eksplisitt merket med standard versjonsekvenser som `v1`, `v2` eller `v3`.

_2.1.3 Atferd og hensyn_ Selv om dette oppsettet er enkelt i begynnelsen, kan versjonsspor utvides til doble eller trippeltall (f.eks. `v10` eller `v123`) etter hvert som prosjektet fremskriter. For å imøtekomme denne veksten etableres et tekstfelt med enten uendelig (variabel) lengde eller større fast lengde.

En viktig visuell vurdering med denne tilnærmingen er at hvis blokken befinner seg i midten av filnavnet, vil tillegg av et annet eller tredje tegn til sekvensen visuelt forskyve alle påfølgende navneblokker over tegn-plasser. For å forhindre at disse skiftende versjonsetikett­ene oppretter helt separate dokumentbeholdere under hver opplasting, må dokumentidentifikatoren deaktiveres.

_2.1.4 Konfigurasjonen_

- **Kildekilde:** Egendefinert tekstfelt.
- **Lengde:** Stå tom for variabel lengde, eller angi en større fast tall.
- **Dokumentidentifikator:** Av.

_2.1.5 Resultatet_ Når Sophia laster opp filer med navn som `Structural_Model_v1.ifc` og `Structural_Model_v10.ifc`, gjenkjenner plattformen de endrede versjonsstengene. Filene stabiles pent som sekvensielle revisjoner under en enkelt, statisk dokumentbeholder med navn `Structural_Model`.

### 2.2 Alfanumerisk bindestrek-polstret sekvens (`--`, `-a`, `-b`)

_2.2.1 Teamet_ Sarah (Lederarkitekt) og Tom (BIM-koordinator).

_2.2.2 Arbeidsflyten_ Sarah utsteder arkitektoniske tegninger som følger en progresjon der den første utgivelsen starter med et dobbelt bindestrek (`--`), fulgt av alfabetisk sporing (`-a`, `-b`) når endringer oppstår. Hun samarbeider med Tom, som administrerer mappeoppsettet.

_2.2.3 Atferd og hensyn_ I motsetning til standard versjonsekvens holder dette bindestrek-polstrete oppsettet blokkens lengde nøyaktig den samme. Når en ny versjonsbokstav introduseres, ofres en plassholder-bindestrek for å opprettholde jevn avstand.

En primær utfordring med denne strategien er at når alle plassholder-bindestrekene innenfor den forhåndsdefinerte lengden er oppbrukt, bryter konvensjonen. Derfor anbefales denne tilnærmingen kun når det er en klar forståelse av grensen for maksimal revisjon for dokumentene.

_2.2.4 Konfigurasjonen:_

- **Kildekilde**
  Egendefinert tekstfelt konfigurert med streng, fast lengde (f.eks. 2 eller 3 tegn) eller et rullegardin-egendefinert felt som inneholder de nøyaktige tillatte variasjonene.
- **Dokumentidentifikator:** Av.
- **Resultatet**
  Når Sarah laster opp `FloorPlan_--.pdf` etterfulgt senere av `FloorPlan_-a.pdf`, leser plattformen de endrede sekvensetikett­ene for validering, men fjerner dem når filen navngis i arbeidsrommet. Tom og designteamet ser en enkelt dokumentbeholder med navn `FloorPlan` der historiske variasjoner stapeles som revisjoner uten å forskyve påfølgende tegn.

### 2.3 Enkel numerisk sporingssekvens (`01`, `02`, `03`)

_2.3.1 Teamet_ David (Konstruksjonstegnmann) og Chloe (Leder konstruktøringeniør).

_2.3.2 Arbeidsflyten_ David oppdaterer tegninger med konstruksjonsdetaljer hyppig og merker dem numerisk på sin datamaskin ved hjelp av sekvensielle indikatorer som `01`, `02` og `03`. Chloe gjennomgår disse detalj­ene og stoler på at plattformen sikrer at David legger inn tall i stedet for tilfeldige tekstbokstaver.

_2.3.3 Atferd og hensyn_ En heltall-fokusert regelblokk legges til mappestrukturen for å validere oppføringer. Merk at selv om det sikrer at bare numeriske oppføringer brukes, godtar systemet ethvert gyldig heltall i stedet for å tvinge en streng, trinnvis sekvensiell telling.

_2.3.4 Konfigurasjonen_

- **Kildekilde:** Egendefinert heltallsfelt.
- **Dokumentidentifikator:** Av.

_2.3.5 Resultatet_ Når David laster opp `Steel_Detail_01.pdf`, bekrefter heltallsfeltet at blokken inneholder numeriske data og tillater opplastingen. Hvis David gjør en feil og prøver å laste opp en fil som inneholder bokstaver i denne blokken, avviser systemet filen. Chloe kan overvåke filene vel vitende om at selv om plattformen godtar ethvert gyldig heltall og ikke tvinger David til å telle opp i en stiv kronologisk sekvens, garanterer den en ren numerisk tidslinje i filinformasjonsruten.

## 3. **3. Arbeidsflyter for forkortelsesstatuskartlegging (`W`, `D`, `P`)**

_3.1 Teamet_ Elena (HVAC-ingeniør) og Marcus (Prosjektleder).

_3.2 Arbeidsflyten:_ Elena bruker et lokalt navnesystem der hun legger til enkeltbokstav-forkortelseskoder for å indikere en tegnings livssyklustatus: `W` for Under utarbeidelse, `D` for Utkast og `P` for Publisert. Marcus, prosjektlederen, må kjenne den nøyaktige statusen for ingeniørarkene hennes med et øyeblikk, men foretrekker fulle, beskrivende ord i stedet for forkortelser.

_3.3 Atferd og hensyn_ En rullegardinkonfigurasjon brukes på mappen for å bygge bro mellom lokale forkortelseskoder og plattformmetadata-visningstitler.

_3.4 Konfigurasjonen:_

- **Kildekilde:** Egendefinert rullegardinfelt.
- **Kartleggingsoppsett**
  "Koden" er angitt for å samsvare med Elenas lokale filnavn-merker (`W`, `D`, `P`), mens "Navn" skrives ut fullt som visningsverdien (`Under utarbeidelse`, `Utkast`, `Publisert`).
- **Dokumentidentifikator:** Av.

_3.5 Resultatet_ Når Elena laster opp `HVAC_Layout_W.pdf`, samsvarer systemet koden `W` og fyller automatisk metadatavisningen som `Under utarbeidelse`. Når Marcus utvider høyre informasjonsmeny for å gjennomgå filen, forblir dokumentnavnet et rent, statisk `HVAC_Layout`, mens delen **Revisjonsopplysninger** eksplisitt viser «Under utarbeidelse».

## 4. **4. Numerisk datosporing og kronologisk sortering**

### 4.1 **4.1 Teamet**

Oliver (Dokumentkontroller) og Emma (Stedleder).

### 4.2 **4.2 Arbeidsflyten**

Oliver behandler daglige stedrapporter og må spore nøyaktig når hver rapport ble generert. Emma, stedlederen, får hyppig tilgang til dokumenttabellen og krever at filene er svært organisert. Fordi innebygde datoblokker ikke brukes innenfor navnekonvensjoner, bruker Oliver og Emma egendefinerte numeriske felt for å legge inn datostrenger. De utforsker to distinkte konfigurasjonsvariasjoner avhengig av hvordan de vil at filene skal fungere.

### 4.3 **4.3 Dato som revisijonmarkør (standardrekkefølge)**

I denne variasjonen endres datoen med hver ny filopplasting og representerer en ny revisjon av dagloggen. Oliver bruker to siffer for dagen (`01`–`31`), to siffer for måneden (`01`–`12`) og enten et tosifret år (`26`, `27`) eller et firesifret år (`2026`, `2027`). Fordi en navnekonvensjon bare tillater ett primært separatortegn på tvers av blokkene, krever håndtering av et isolert datoformat valg mellom to distinkte konfigurasjonsveier:

_4.3.1 Tre separate heltallsblokker_

- **Struktur**
  Hvis en understrek (`_`) er etablert som primærseparatoren, kan filen formateres som `Daily_Report_09_07_2026.pdf`.
  Dette bruker tre individuelle egendefinerte heltallsfelt: Dag, Måned og År.
- **Dokumentidentifikator-begrensninger**
  Hvis dokumentidentifikatoren er angitt **På** for disse tre blokkene, er datoen permanent integrert som del av dokumentnavnet.
  Dette oppretter en separat dokumentbeholder for hver enkelt revisjon, og datoverdiene forblir permanente fordi dokumentnavn innenfor navnekonvensjons-mapper ikke kan endres.
  For å tillate at datofeltet varierer og stapler filer som revisjoner under et enkelt statisk dokumentnavn, må det være nødvendig å angi dokumentidentifikatoren **Av** for alle tre felt.

_4.3.2 Enkelt tekstblokk med interne separatorer_

- **Struktur**
  For å unngå å bruke flere konvensjonsblokker, kan et alternativt tegn (for eksempel en bindestrek) brukes innenfor en enkelt tekstfeltblokk, formatert som `Daily_Report_09-07-2026.pdf`.
- **Valideringsbegrensninger**
  Det er bare mulig å validere den overordnede tekststrengen innenfor en individuell blokk. Følgelig avhenger sikring av at de sekundære interne separatorene er plassert korrekt helt av manuell brukerakkurathitet under fileforberedelsen.

### 4.4 Dato for sortering (år-måned-dag-rekkefølge)

I denne variasjonen vil Emma at datoen skal være synlig i dokumentnavnet slik at separate filer finnes for hver dag. Videre krever Emma at dokumenttabellen sorterer filene i perfekt kronologisk rekkefølge automatisk. Lister innenfor plattformen sorteres alfanumerisk i henhold til Unicode-verdier. Hvis en dato er skrevet som dag-måned-år, sorterer listen først etter dagsnummeret, og grupperer alle filer fra "01"-dagen fra ulike måneder sammen.

For å forhindre dette, plasserer Oliver året først, etterfulgt av måneden og deretter dagen. Ved administrering av dette prefikset er det en balanse mellom å bevare tegenplass og sikre umiddelbar lesbarhet, noe som fører til to implementeringsalternativer:

_4.4.1 To-sifret årprefikser (`YYMMDD`)_ Dette alternativet forkorter sorteringsstrengen til en enkelt blokk for å eliminere ekstra separatortegn og reduserer året til to heltall (f.eks. `26`, `27`, `28`). Dette sparer tegenplass, noe som reduserer risikoen for at lange dokumentnavn blir avskåret eller trunkert på slutten av linjen i brukergrensesnittet. Imidlertid oppgir dette alternativet umiddelbar lesbarhet.

En datostreng som `260126` kan lett bli misforstått, da det ikke er umiddelbar klart hvilke tall som representerer året og hvilke som representerer dagen. Et mønster blir først gjenkjennbart etter visning av flere filer, og forskjellen blir bare tydelig når en dag eller årverdi overstiger 31.

_4.4.2 Fire-sifret årprefikser (`YYYYMMDD`)_ Dette alternativet bruker et fullstendig firesifret år (f.eks. `2026`, `2027`, `2028`) på begynnelsen av navnet. Denne konfigurasjonen forbedrer klarhet og umiddelbar lesbarhet betydelig, noe som gjør den kronologiske sekvensen åpenbar for alle teammedlemmer. Imidlertid bruker det mer tegenplass på begynnelsen av filnavnet, noe som øker sannsynligheten for at informasjon på slutten av lange dokumentnavn blir trunkert eller skåret av i grensesnittet.

_4.4.3 Konfigurasjon_

- **Kildekilde**
  Et enkelt heltalls- eller tekstegendefinert felt plassert helt på begynnelsen av navnekonvensjonen, formatert i en streng `YYMMDD` eller `YYYYMMDD`-sekvens.
  For å opprettholde riktig justering og riktig alfanumerisk sortering, må ledende nuller alltid brukes for ensifrete måneder eller dager (f.eks. `01` for januar).
- **Dokumentidentifikator:** På.

_4.4.4 Resultat_ Når Oliver laster opp filer som `260115_Report.pdf` og `260201_Report.pdf`, opprettes separate dokumenter fordi dokumentidentifikatoren er aktiv. Fordi året og måneden kommer først og bruker konsistent tosifret polstring, sorterer dokumenttabellen filene i upåklagelig kronologisk rekkefølge.
