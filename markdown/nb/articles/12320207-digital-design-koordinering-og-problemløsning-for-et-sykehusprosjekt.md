# Digital Design Koordinering og Problemløsning for et Sykehusprosjekt

> Industri: Helsekonstruksjon / BIM (Building Information Modeling) Persona: David, en BIM-koordinator for en stor generalentreprenør.

_Scenario:_ David administrerer den digitale konstruksjonsmodellen for en ny sykehusavdeling. Dette er et svært komplekst prosjekt som involverer dusinvis av spesialiserte team. Arkitektur-, struktur- og MEP-modellene (mekanisk, elektrisk, rørleggearbeid) oppdateres konstant av forskjellige konsulentfirmaer. Davids primære ansvar er å federalisere (kombinere) disse modellene i Catenda Hub for å identifisere og løse clashes _før_ de blir dyre problemer på byggeplassen.

Under sin ukentlige koordineringskontroll må han undersøke et potensielt kritisk problem som er flagget av byggeplasslederen: støttestrukturen for en stor MRI-maskin på andre etasje stemmer kanskje ikke overens med de nyeste arkitektur- og elektriske planene.

_Løsning ved bruk av Catenda Hub:_ David bruker en presis arbeidsflyt innen Catenda Hub for å håndtere denne komplekse koordineringsoppgaven effektivt.

### **1. Sentralisering av data på siden "Modeller":**

Først navigerer David til **Modeller-siden**. Her kan han se alle de siste IFC-modellene lastet opp av de ulike teamene, hver med sitt revisjonsnummer og status. Han velger de relevante modellene for områdene som er av interesse:

- ARCH-Hospital-Wing-rev04.ifc
- STRUCT-MRI-Support-rev02.ifc
- MEP-Elec-Room204-rev05.ifc

Han åpner alle tre i den føderaliserte **3D Viser**. Plattformen kombinerer dem til en enkelt, navigerbar digital tvilling av den delen av sykehuset.

### **2. Identifisering av Clash og oppretting av et "Bokmerke":**

Ved navigering gjennom 3D-modellen oppdager David umiddelbart problemet. Stålstøttene for MRI-maskinen trenger gjennom en vegg der arkitektene nå har plassert et hovedelektrisk koblingshus. Dessuten konfronterer etasjen gjennom maskinnens kjølerør med en nylig ruta kabelbrett. For å kommunisere dette komplekse, flerdelt problemet tydelig, er et enkelt skjermbilde ikke nok. I stedet bruker David **Bokmerker**-funksjonen:

- Han isolerer kun de kolliderende elementene: stålstøttene, den spesifikke veggen, koblingshuset og kabelbrettet.
- Han bruker et seksjonskutt for å skape en klar, uobstruert visning av kollisjonspunktet.
- Han lagrer denne presise tilstanden—inkludert kameravinkel, objektsynlighet og seksjonskutt—som et bokmerke med tittelen "**Clash: MRI Support vs. Elec Room 204**".

### **3. Oppretting og tildeling av en handlingskraftig sak:**

Med bokmerket opprettet, oppretter David en **Sak** (eller "Sak" i Catenda Hub). I saksbeskrivelsen skriver han: "@Arkitekter, @Konstruktør, @MEP - Vi har en kritisk clash mellom støttestrukturen for MRI-maskinen og det reviderte elektrorommets layout. Det vedlagte bokmerket viser den eksakte plasseringen og elementene som er involvert. Konstruktør må bekrefte om støttene kan flyttes, og MEP må verifisere en ny rute for kabelkanten. Vennligst gi en løsning innen fredag klokka 17." Han lenker saken direkte til bokmerket han nettopp opprettet.

### **4. Driving Collaborative Resolution:**

Hovedarkitekten, konstruktøren og MEP-koordinatoren mottar en øyeblikkelig varsel. Når de klikker på lenken i saken, åpner Catenda Hub 3D-modellen og tar dem til **den nøyaktige visningen David lagret i bokmerket**. Det er ingen tvetydighet eller tid kastet bort på å prøve å finne problemet. De bruker sakens kommentareksjon til å diskutere løsninger. Arkitekten bekrefter at elektrisk romplass er fast. Konstruktøren kjører en rask analyse og foreslår et revidert støttedesign, vedlegger en skisse. MEP-koordinatoren bekrefter at de kan omdirigere kabelbrettet.

### **Resultat og fordeler:**

Ved å utnytte Modeller- og Bokmerker-sidene, transformerte David et potensielt kaotisk og kostbart problem til en strukturert, sporbar og raskt løst sak.

- **Absolutt klarhet:** Bokmerket ga en "enkelt kilde til sannhet" for problemet, og eliminerte enhver feiltolking som kunne oppstå fra e-poster eller telefonsamtaler.
- **Betydelige tidsbesparelser:** Prosjektdeltakerne løste saken på få timers digital samarbeid, noe som sparte dager eller til og med uker sammenlignet med tradisjonelle metoder for sending av filer frem og tilbake.
- **Kostnadsunngåelse:** Å identifisere denne clashingen digitalt forhindret de massive kostnadene for rivning på stedet, omarbeiding og prosjektforsinkelser som ville ha oppstått hvis stålet hadde blitt reist på feil sted.

### **Forbedret ansvarlighet:**

Hele oppdagelse-, kommunikasjons- og løsningsprosessen er dokumentert i en enkelt sak, noe som skaper et klart revisjonsspor for prosjektregisteret.
