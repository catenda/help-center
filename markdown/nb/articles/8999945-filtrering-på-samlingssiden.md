# Filtrering på samlingssiden

Søk- og filteralternativet vises i den øvre delen av vinduet. Du kan søke ved å skrive navnet på samlingen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/svz5chty/01-intro.png)

I søkefeltet kan du søke etter en hvilken som helst samling du har tilgang til.

## 1. **Filterpanel til venstre**

Ved å klikke på filterknappen vises et panel på venstre side. Ved å merke av boksene vil du innsnevre søket. Disse filtrene kan lagres øverst i filterlisten. Når du bruker noen av disse filtrene, legges filterteksten til i URL-en din. Hvis du deler denne URL-en, vil personen som åpner den se samme filter som du ser hvis de har tilgang til det. Hvis du for eksempel deler en URL med filteret "Jeg følger" aktivert, vil mottakeren se filtre de følger når de åpner URL-en. Når du holder musen over noen av filtrene i venstre panel, kan du klikke bare på høyre side av filteret for å fjerne alle andre tidligere brukte filtre.

## 2. **Lagrede filtre**

Klikk [her](https://support.catenda.com/en/articles/8551755-saving-filters) for å lese mer om hvordan du lagrer et sett med filtre

## 3. **Filter**

Klikk på filterknappen øverst til venstre for at et panel skal vises på venstre side. Når et filter brukes, endres URL-en som vises i nettleseren. I denne artikkelen vises filtre slik: _Filternavn i meny_ - `Filternavn i URL=Filteralternativ i URL`

_Standardfilter_ Standardfilteret er opprinnelig ikke synlig i URL-en. Når siden navigeres til for første gang, brukes følgende filter. _Samlinger fulgt av meg og teams jeg er medlem av_ - `followers=my-teams,me`

### 3.1 **Lagre og del gjeldende filter**

Gå til URL-en på en filtrert side for å laste siden med filteret brukt. De brukte filtrene kan lagres øverst i filtrermenyen. Klikk [her](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) for å lese mer om hvordan du lagrer og deler filtre

### 3.2 **Skjul tomme filtre**

Klikk [her](https://support.catenda.com/en/articles/8551755-saving-filters) for å lese mer om å begrense filterresultatene.

### 3.3 **Samlinger jeg følger**

_Jeg følger_ - `followers=me` Samlinger fulgt av brukeren.

_Teamene mine følger_ - `followers=my-teams` Samlinger fulgt av teams som brukeren er medlem av.

_Alle samlinger_ - `followers=all` Alle samlinger med eller uten følger. Dette filteret brukes automatisk når x-knappen i søkefeltet klikkes eller når både "Jeg følger" og "Teamene mine følger"-filtrene er deaktivert.

### 3.4 **Opprettet av meg**

Opprettet av - `createdBy=<Creator GUID>` Det er ingen brukergrensesnittkknapp for dette filteret. Når du filtrerer på privat eller delt med prosjekt, vil dette automatisk bli satt til din egen bruker, men du kan endre det til GUID-en til en annen bruker.

Privat - `visibility=private` Delt med prosjekt - `visibility=project-members`

### 3.5 **Fullført**

Fullført - `finalized=true` Ikke fullført - `finalized=false`

### 3.6 **Delt eksternt**

Delt eksternt - `sharedBy=email,link`

> **Merk:** Ved å skrive enten e-post eller lenke her kan du innsnevre søket ditt

Ikke delt eksternt - `sharedBy=not-shared`

### 3.7 **Datofilter**

Publisert - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Klikk på velg datoer for å velge datoer mellom hvilke du vil søke. Klikk [her](https://support.catenda.com/en/articles/6511685-date-filter) for å lese mer om datofilter

## 4. **Tekstsøk**

Du kan søke etter eksakte treff på tekst i filnavn som er minst 3 tegn lange

### 4.1 **Tekstsøk**

_Tekstsøk_ - `search=test`

_Innhold som kan søkes på_ samlingsnavn

_Versaler_ Tekstsøket er ikke følsomt for store eller små bokstaver.

_Tegnantall_ Hvilken som helst mengde tegn. Innhold som inkluderer den søkte frasen samsvares.

_Mellomrom_ Mellomromstegn i begynnelsen av en søkefrase fjernes.
