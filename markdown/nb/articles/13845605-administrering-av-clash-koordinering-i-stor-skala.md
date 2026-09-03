# Administrering av Clash-koordinering i stor skala

Denne artikkelen ble generert ved å be vår AI-støtteagent. Ledeteksten som er gitt nederst kan brukes til å generere din egen, oppdaterte versjon av dette bruksmønsteret når støtteartiklene som AI-en er opplært på, endres over tid.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hkk8f581/01-intro.png)

## 1. **Møt Sarah Chen, en BIM-leder hos Morrison Construction**

Sarah Chen fører tilsyn med digital koordinering for det nye Metro Transit Hub-prosjektet. Med 15 års erfaring innen konstruksjonsteknologi spesialiserer Sarah seg på å transformere externe clash-deteksjonsrapporter til strømlinjeformede koordineringsarbeidsflyter i Catenda Hub ved hjelp av saklister, merkelapper og milepælsporing. Sarahs rolle sentrerer seg om å lage BIM-gjennomføringiplanen og etablere digitale kvalitetskontrollprosesser. Hun arbeider med konstruktøringeniører som bruker Tekla, MEP-team i Revit og arkitekter i ArchiCAD – alt som krever sømløs koordinering gjennom organiserte saklister med egendefinerte statusverdier og typer.

### 1.1 **Viktige observasjoner**

Sarah administrerer tverrfaglige team gjennom strukturerte saklister, oppretter koordineringsarbeidsflyter ved hjelp av eksterne verktøy og sikrer samsvar med milepæler gjennom digitale prosesser.

### 1.2 **Hvorfor saksliste-organisering er viktig**

Metro Transit Hub-prosjektet genererte over 3 000 clash-deteksjoner da teamet kjørte clash-deteksjon i Solibri Model Checker. Uten riktig organisering ville disse problemene skape kaos og forglemt frister. Sarah trengte separate saklister for ulike disipliner, hver med egendefinerte statusverdier (Aktiv, Under vurdering, Løst, Godkjent) og typer (Clash, RFI, Advarsel) for å spore livssyklusen til hver koordineringssak. Merkelapper ble avgjørende for gruppering av saker etter etasje, prioritet eller teknisk system, noe som betydelig forbedret søkbarheten.

### 1.3 **Viktige observasjoner**

Saksliste-separasjon forhindrer informasjonsoverbelastning, egendefinerte statusverdier sporer fremdrift, og merkelapper gjør effektiv filtrering og tildeling mulig.

## 2. **Roller og ansvar**

_Strukturleder_ Marcus Rodriguez administrerer koordinering av stålramme ved hjelp av dedikerte Struktur-MEP-saklister. Han filtrerer saker etter tildelt status og løser strukturelle konflikter innen 48 timer ved hjelp av milepælssporing.

_MEP-koordineringsleder_ Lisa Park fører tilsyn med mekaniske systemer gjennom MEP-spesifikke saklister. Hun bruker merkelapper til å prioritere kritiske problemer og administrerer rutingkonflikter gjennom egendefinerte statusarbeidsflyter.

_Arkitektonisk designleder_ David Kim opprettholder designintensjon gjennom Arkitektur-MEP-integreringstavler. Han gjennomgår clash-løsninger ved hjelp av milepæler-filtre og godkjenner designendringer med riktige statusoppdateringer.

_Stedsbyggeleder_ Jennifer Walsh bruker mobil tilgang med merkelappfiltre for å fokusere på etasjebaserte problemer. Hun oppretter stedsbaserte saker og lenker dem til eksisterende koordineringsmilepæler.

_Viktige observasjoner_ Hver rolle arbeider innen spesifikke saklister, bruker merkelapper for filtrering, og sporer fremdrift gjennom milepælsintegrasjon.

### 2.1 **Virkelig bruksmønster: Metro Transit Hub**

Prosjektets nivå 3-korridor krevde tre separate saklister:

Struktur-MEP-koordinering Arkitektur-MEP-integrasjon Stedsverifisering

Sarah konfigurerte hver tavle med egendefinerte statusverdier og typer som samsvarte med prosjektets koordineringsprosess. Hun implementerte merkelapper for etasjenivå (L1, L2, L3), prioritet (Kritisk, Høy, Medium, Lav) og systemtype (HVAC, Elektrisitet, Rørleggerarbeid, Struktur). Dette gjorde det mulig for team å filtrere saker effektivt – MEP-team kunne bare se "L3 + Kritisk + HVAC"-problemer.

Milepælsintegrasjon koblet koordineringssaker til prosjektfrister, noe som gir sanntidsvisibilitet til hvilke problemer som kan blokkere fremgang. Team kunne tildele saker direkte til ansvarlige medlemmer med klare frister.

### 2.2 **Viktige observasjoner**

Flere saklister organiserer disipliner, merkelapper gjør presist filtrering mulig, og milepælssporing sikrer samsvar med frister.

## 3. **Implementeringsveiledning trinn for trinn**

### 3.1 **Oppretting av disiplinspesifikke saklister**

Sarah oppretter separate tavler for Struktur-MEP-koordinering, Arkitektur-MEP-integrasjon og Stedsverifisering. Hver tavle får egendefinert konfigurasjon for statusverdier (Aktiv, Under vurdering, Løst, Godkjent) og typer (Clash, RFI, Advarsel, Koordinering).

### 3.2 **Implementering av merkelappssystemer**

Hun etablerer merkelapper for etasjenivå, prioritet, systemtype og ansvar. Merkelapper blir den primære filtreringsmekanismen, som gjør det mulig for team å raskt finne deres tildelte problemer ved å bruke kombinasjoner som "L3 + Høy prioritet + Struktur".

### 3.3 **Oppsett av status- og typearbeidsflyter**

Hver saksliste blir konfigurert med minimum én åpen status og én lukket status. Typer tilpasses for hver disiplin – strukturtavler kan ha "Grunnlags-clash" og "Stålkonflikt"-typer mens MEP-tavler bruker "Rutingproblem" og "Utstyrclash".

### 3.4 **Etablering av tildeling og milepælsintegrasjon**

Saker blir tildelt direkte til teammedlemmer med forfallsdatoer knyttet til prosjektmilepæler. Plattformen sporer tildelinger etter person og team, med filtre tilgjengelig for "Mine saker," "Tildelt til meg" og milepælsspesifikke visninger.

### 3.5 **Importering av eksterne clash-deteksjonsresultater**

Ved import av BCF-rapporter fra Solibri sikrer Sarah at de lander i den aktuelle saklisten med korrekte merkelapper og tildelinger. Team kan deretter opprette saker fra clash-resultater ved hjelp av ulike alternativer – enkelt kombinerte saker eller individuelle saker for hver clash.

### 3.6 **Viktige observasjoner**

Systematisk saksliste-oppsett, omfattende merking og milepælsintegrasjon skaper ansvarlig og transparens i koordineringsprosesser.

## 4. **Videre lesing:**

- [Saksliste-innstillingerside](https://support.catenda.com/en/articles/4670277-topic-board-settings-page)
- [Catenda Archicad-plugin](https://support.catenda.com/en/articles/5519276-catenda-archicad-plugin)
- [Catenda Revit-plugin](https://support.catenda.com/en/articles/4670334-catenda-revit-plugin)
- [Catenda Navisworks-plugin](https://support.catenda.com/en/articles/5085987-catenda-navisworks-plugin)
- [Trinn 5 – Saker](https://support.catenda.com/en/articles/10576182-step-5-topics)

## 5. Ledetekst

### 5.1 **Karakter**

Du er en BIM-leder for en hovedentreprenør på et høyintensitets-infrastrukturprosjekt. Du er arkitekten for BIM-gjennomføringsplanen (BEP) og den primære autoriteten for digital kvalitetskontroll og koordineringsmilepæler.

### 5.2 **Erfaring**

Du er en meister innen digital koordinering som trives i høytrykksuker der tusenvis av tekniske og geometriske clash identifiseres. Du forstår at administrering av disse i stor skala krever å bevege seg bort fra statiske PDF-rapporter mot et sentralisert, live-koordineringsnav. Du vet hvordan du utnytter de naturlige "finn-og-fiks"-instinktene til et prosjektteam ved å gi dem et profesjonelt, strukturert arbeidsmiljø for arbeidet deres.

### 5.3 **Mål**

Ditt mål er å transformere et enormt datasett til en handlingsorientert arbeidsflyt ved å:

_Separering av saklister:_ Organisering av tusenvis av saker i kategoribaserte tavler for å forhindre datasiloer.

_Definering av livssykluser:_ Etablering av klare statusverdier og typer for hver tavle for å sikre at design følger en streng valideringsbane.

_Sikring av ansvar:_ Fordeling av arbeidsmengde på tvers av team for å sikre at milepælblokkering av problemer blir løst før formelle vurderinger.

_Tilbud av transparens:_ Oppretting av et uangripelig revisjonslogg for hver beslutning, revisjon og godkjenning.

### 5.4 **Situasjon**

Prosjektet går inn i en kritisk koordineringsfase, og clash-deteksjonsprogramvaren din har nettopp identifisert tusenvis av problemer. For å administrere dette i Catenda Hub implementerer du følgende system:

_Saksliste-separasjon:_ Du oppretter distinkte tavler basert på disiplin (f.eks. struktur, MEP, arkitektur) eller alvorlighetsgrad. Dette holder tekniske iterasjoner organiserte og søkbare.

_Konfigurering av statusverdier og typer:_ For hver tavle konfigurerer du spesifikke typer (f.eks. clash, RFI, advarsel) og statusverdier (f.eks. aktiv, pågår, løst, godkjent). Dette sikrer at livssyklusen til hvert koordineringspunkt spores i henhold til ISO 19650-standarder.

_Sporing via milepæler:_ Du lenker saker på tvers av ulike tavler til prosjektmilepæler. Dette gjør det mulig for deg å spore sanntidshelse og identifisere nøyaktig hvilke clash som vil blokkere prosjektets fortsettelse hvis de ikke blir løst innen en bestemt dato.

_Gruppering med merkelapper:_ Du bruker merkelapper til å gruppere saker etter etasje, prioritet eller teknisk system. Dette forbedrer søkbarheten betydelig, slik at fagpersoner raskt kan filtrere og finne problemene de er ansvarlige for.

_Fordeling av arbeidsmengde:_ Du deler ansvar ved å tildele saker til spesifikke medlemmer eller tverrfaglige team. Ved å lenke saker direkte til BIM-objekter og 3D-visninger sikrer du at struktur- eller MEP-lederen kan finne, diskutere og løse problemet uten noen gang å forlate sitt eget redigeringsmiljø.

### 5.5 **Insentiv**

Din suksess måles ved å nå kontraktsmessige milepæler i tide med null manuell datainmatting. Du vet at en beslutning som ikke er dokumentert i sammenheng er en beslutning som ikke skjedde. Ditt mål er å gi en "clash-fri" rapport som fungerer som en uforanderlig forsikring for prosjektets historikk.
