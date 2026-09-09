# Bruk av tilgangskontroll – brukstilfeller

Å strukturere et tilgangskontrollmiljø i Catenda Hub krever tilpasning av systemmekanikk til spesifikke prosjektroller og samarbeidsarbeidsflyter. For å løse overlappende regler på en ryddig måte, bruker systemet en streng autoritetslinje: direkte individuelle overstyringer etablerer en absolutt endelig grense, mens alle ikke-overstyrt stier kombineres for å gi det maksimale tilgjengelige tillatenivået. Konfigurationsstrategiene som er skissert nedenfor, demonstrerer hvordan du distribuerer teamgrenser, individuelle låsinger og containeromfang for å oppfylle virkelige sikkerhet- og driftskrav.

## 1. **1. Det generelle prosjektfellesskapet**

### 1.1 **1.1 Isolerte underleverandørarbeidsområder**

_Hvem_ Et enkelt spesialisert underleverandørteam som krever intern autonomi.

_Målet_ Underleverandørteamet må ha total frihet til å laste opp, endre, organisere og fikse filer i det tildelte avsnittet. Kolleger innen samme firma må kunne korrigere hverandres feil eller omorganisere mappestrukturer fritt, men eksterne parter må blokkeres helt for å forhindre utilsiktet sletting eller uautorisert synlighet.

_Konfigurasjonen_ Den globale **Alle brukere**-grunnlinjen er satt til **Ingen tilgang**, mens det spesifikke underleverandør**Teamet** får **Fullstendig tilgang**.

_Omfangsstrategi_ Denne strategien distribueres vanligvis når et prosjekt er nytt. **Nedadgående propagering** er aktivert på toppnivåmappestrukturen, som lar administratorer raskt skyve fullstendig intern autonomi ned gjennom hele undermappebanen.

### 1.2 **1.2 Tverrfaglige samarbeidsmappe**

_Hvem_ Flere designdisipliner (f.eks. arkitekter, konstruktører, MEP) som arbeider i et delt miljø.

_Målet_ Det må tilbys et delt arbeidsområde der ulike team kan laste opp modeller, koordinere design og kryssreferansere filer samtidig uten restriksjoner.

_Konfigurasjonen_ Dette miljøet kan etableres ved hjelp av en av to metoder: enten blir et dedikert, blandet "Tverrfaglig team" opprettet og gitt **Skriv**tilgang, eller hvert individuelle disiplinerteam (Arkitekturteam, Konstruksjonsteam osv.) blir eksplisitt lagt til containeren med **Skriv**tilgang.

_Omfangsstrategi_ Fordi samarbeidskrav endres hyppig på tvers av ulike grener i en mappe, fokuserer dette brukstilfelle på spesifikke "blad"-mapper dypere i hierarkiet. Omfanget er begrenset til **Kun den umiddelbare containeren**, noe som sikrer at åpne samarbeidsregler ikke utilsiktet blør inn i andre begrensede soner.

### 1.3 **1.3 Tverrfaglig synlighet og revisjon**

_Hvem_ Eksterne revisorer, klientrepresentanter eller sekundære ingeniørteam.

_Målet_ Ett primær team må beholde full kontroll eller opplastingsrettigheter i en mappe, men et eksternt team eller interessent må aktivt overvåke fremgang, vurdere dokumenter og se nøyaktig hva som skjer i sanntid uten noen mulighet til å endre dataene.

_Konfigurasjonen_ Den primære arbeidsgruppen gis **Fullstendig tilgang** eller **Skriv**tilgang, mens revisjons- eller sekundærteamet eksplisitt får tildelt **Les**tilgang.

_Omfangsstrategi_ Denne konfigurasjonen bruker **Kun den umiddelbare containeren**-kartlegging på lokaliserte bladmapper. Det lar interessenter få målrettet synlighet til fullførte arbeidsavsnitt samtidig som uapproberte utkast i tilstøtende mapper holdes helt skjult.

## 2. **2. Underleverandører og eksterne bidragsytere**

### 2.1 **2.1 Flytende teamtildelinger for roterende personell**

_Hvem_ Eksterne leverandører og kontraktørfirmaer med høy personellomsetning.

_Målet_ Tilgangen må forbli stabil og sikker selv når personell hyppig kommer inn og ut av prosjektet eller endrer bedriftsroller.

_Konfigurasjonen_ Tillatelser tildeles utelukkende til et **Teamet** (f.eks. "Eksterne anmeldere") satt til **Les** eller **Skriv**. Ingen individuelle brukeroverridinger konfigureres for teammedlemmene.

_Omfangsstrategi_ For å sikre langsiktig vedlikehold bruker denne konfigurasjonen **Nedadgående propagering** på toppnivåmappene. Når en ny arbeider blir med i det eksterne firmaet, blir de ganske enkelt lagt til den eksisterende teamstrukturen og arver umiddelbart de riktige tillatelsene på tvers av hele prosjektgrenen uten manuelle mappe-for-mappe-justeringer.

### 2.2 **2.2 Sikker individuell låsing**

**Hvem:** Høysikkerhetskonsulenter, tredjepartsrevisorer eller begrensede eksterne bidragsytere.

**Målet:** Fordi sikkerhet og dataintegritet er av størst betydning, må en administrator garantere med 100 % sikkerhet at en bestemt bruker har et fast tilgangsnivå. Dette nivået må forbli strengt låst, noe som sikrer at brukeren ikke kan utilsiktet arve forhøyet tillatelser hvis de ved en feiljudgement blir lagt til et parallelt prosjektteam eller samarbeidsfgruppe.

**Konfigurasjonen:** En eksplisitt **Individuell brukerinstilling** brukes direkte på brukerens konto og settes nøyaktig til det nødvendige nivået (for eksempel **Les** eller **Ingen tilgang**).

**Omfangsstrategi:** Dette brukes som en lokalisert lås på spesifikke bladnoder ved hjelp av innstillingen **Kun den umiddelbare containeren**. Fordi en individuell tildeling representerer den ultimate slutautoriteten i systemhierarkiet, overstyrer den alle globale grunnlinjer, teammedlemskap og eigarrettigheter. Selv om brukeren ved et uhell blir tildelt et team med Fullstendig tilgang andre steder, sikrer den individuelle låsingen at tillatelsene deres forblir begrenset nøyaktig som tiltenkt.

## 3. **3. Gjenstanders eiere og innholdsskapere**

Catenda Hub tildeler automatisk **Full tilgang** til oppretteren av en mappe (enten opprettet manuelt eller automatisk ekstrahert via en opplastet ZIP-struktur), en saksliste eller en nylig opprettet dokumentbeholder. Eierskap gjelder strengt tatt for dokumentbeholderen selv, noe som betyr at hvis en bruker laster opp en ny revisjon til et dokument opprettet av noen andre, forblir det opprinnelige eierskap for beholderen uendret.

### 3.1 **3.1 Opprettersuvranitet og datavern**

_Hvem_ Interne forfattere og standard innholdsbidragyere.

_Målet_ Et delt mappe-miljø må etableres der teammedlemmer kan bla gjennom generelle filer, men enhver person som opprinnelig opprettet en dokumentcontainer må beholde absolutt kontroll for å oppdatere, omdøpe eller administrere den, uten å gi de samme ødeleggende administrasjonserettighetene til resten av teamet.

_Konfigurasjonen_ Den globale **Alle brukere**-grunnlinjen eller teamrammeverktet er begrenset til **Les** eller **Skriv**, mens individuelle brukerinnstillinger helt etterlates ukonfigurert for bidragsyterne.

_Logikken:_ Uten en individuell overstyring, bruker systemet som standard det høyeste arvede nivået. Vanlige teammedlemmer er bundet av standard mapperegelen, men i det øyeblikket den opprinnelige forfatteren samhandler med en dokumentcontainer _de eier_, elevernivået deres oppgraderr dem automatisk til Fullstendig tilgang.

### 3.2 **3.2 Isolerte private arbeidsområder**

_Hvem_ Spesifikke teamledere, prosjektledere eller interne revisorer.

_Formål_ En strengt konfidensiell mappe eller saksliste må etableres der en leder kan laste opp utkast, organisere sensitive filer eller holde interne notater i total isolasjon fra resten av prosjektfellesskapet.

_Konfigurasjonen_ Målcontaineren opprettes, og den globale **Alle brukere**-grunnlinjen er eksplisitt satt til **Ingen tilgang**. Ingen andre generelle team får tilgang.

_Logikken_ Fordi grunnlinjen og teamstiene er helt lukket, ser standardbrukere ingenting. Men fordi oppretteren av den mappen eller brettet automatisk har **Eier Fullstendig tilgang**, beholder de fullstendig synlighet og administrativ kontroll over området, helt isolert fra standard prosjektmedlemmer mens prosjektadministratorer beholder høyestrangering.
