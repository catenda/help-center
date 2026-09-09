# Filtrering på modelside

Søke- eller filtreringsalternativet kan ses i topparten av vinduet. Ved å skrive navn på modellen, navn på en merkelapp som er festet til en modell eller brukernavn på et medlem, kan radene i modelltabellen begrenses. Slik kan søke- eller filtermenyen se ut på modelside:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qfd47nkw/01-intro.png)

I søkefeltet kan du søke etter en hvilken som helst modell som er tilgjengelig i modelltabellen.

## 1. **Filtervenstrre panel**

Ved å klikke på filterknappen vises en panel på venstre side. Merk av i boksene for å begrense søket. Disse filtrene kan lagres øverst i filterlisten. Når noen av disse filtrene brukes, legges filterteksten til i URL-adressen din. Hvis URL-adressen for den filtrerte siden deles, vil personen som åpner den, se det samme filteret i samme mappe som vises for øyeblikket, så lenge vedkommende har tilgang til det. Når du holder markøren over noen av filtrene i venstrre panel, kan du klikke på "bare" til høyre for filteret for å fjerne andre tidligere brukte filtre.

## 2. **Lagrede filtre**

Klikk [her](https://support.catenda.com/en/articles/8551755-saving-filters) for å lese mer om hvordan du lagrer et sett med filtre

## 3. **Filtre**

Klikk på filterknappen øverst til venstre for at et panel skal vises på venstre side. Når et filter brukes, endres URL-adressen som vises i nettleseren. I denne artikkelen vises filtre slik: _Filternavn i meny_ - `Filternavn i URL = Filteralternativ i URL`

_Standardfilter_ Standardfilteret er i utgangspunktet ikke synlig i URL-adressen. Når siden åpnes for første gang, brukes følgende filter. Arbeidsarekkefane - `v=all`

### 3.1 **Lagre og dele gjeldende filter**

Gå til URL-adressen for en filtrert side for å laste inn siden med filteret brukt. De brukte filtrene kan lagres øverst i filtermenyen. Klikk [her](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) for å lese mer om hvordan du lagrer og deler filtre

### 3.2 **Skjul tomme filtre**

Klikk [her](https://support.catenda.com/en/articles/8551755-saving-filters) for å lese mer om begrensning av filterresultater.

### 3.3 **Kategorier**

Arbeidsarekkefane - `v=all` Publisert fane - `v=published`

### 3.4 **Lenker**

Linket - `associations=exists&subFolders=true` Ikke linket - `associations=does-not-exist&subFolders=true` Linket til valgte objekter - `link=backlink&subFolders=true`

### 3.5 **Status (nyeste revisjon) - Status bare arbeidsflyt**

Publisert - `documentStatus=published&subFolders=true&documentType=file` Manglende status - `documentStatus=published-without-status&subFolders=true` Prosjektpublisert status - `documentStatus=<GUID>&subFolders=true` Delt - `documentStatus=shared&subFolders=true&documentType=file` Delte statuser er bare tilgjengelige i arbeidsarekkefanen Prosjektdelt status - `documentStatus=<GUID>&subFolders=true` Ingen revisjon - `documentStatus=no-stage&subFolders=true`

### 3.6 **Utkast - Status bare arbeidsflyt**

Har nye utkast - `newDrafts=exists&subFolders=true` Utkasststatus navn - `newDrafts=<Draft status GUID>&subFolders=true` Hvis det finnes flere utkaststatusar, kan hver utkasststatus filtreres på. Har ingen nye utkast - `newDrafts=does-not-exist&subFolders=true`

### 3.7 **Dokument opprettet av**

Medlemsnavn - `owner=<Member GUID>&subFolders=true`

### 3.8 **Revisjon opprettet av**

Medlemsnavn - `revisionCreatedBy=<GUID>&subFolders=true`

### 3.9 **Publisert av**

Medlemsnavn - `publishedBy=<Member GUID>&subFolders=true`

### 3.10 **Datofiltre**

Publisert - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Klikk på velg datoer for å velge datoer mellom hvilke du vil søke Klikk [her](https://support.catenda.com/en/articles/6511685-date-filter) for å lese mer om datofilteret

### 3.11 **Åpne gjennomganger - Status bare arbeidsflyt**

Gjennomgangnavn - `approval=<Approval number>&subFolders=true`

### 3.12 **Merkelapper**

Alle merkelapper som ikke er en del av en merkelappgruppe, vises i en meny kalt merkelapper. Merkelappnavn - `labels=<Label GUID>6&subFolders=true`

### 3.13 **Merkelappgruppnavn**

Det vil være en meny per merkelappgruppnavn Merkelappnavn - `labels=<Label GUID>6&subFolders=true`

### 3.14 **Samlinger**

Samlingingnavn - `collections=<GUID>&subFolders=true`

## 4. **Tekstsøk**

_Tekstsøk_ - `search=test&subFolders=true`

### 4.1 **Innhold som kan søkes på**

Modellnavn

### 4.2 **Gro-og små bokstaver**

Tekstsøket er ikke følsom for små og store bokstaver.

### 4.3 **Antall tegn**

Mindre enn tre tegn - Tabellen er ikke filtrert. Tre eller flere tegn - Titler som har ett enkelt ord, atskilt med et skilletegn som et mellomrom, som samsvarer med søkefrasen, er inkludert i resultatene.

### 4.4 **Filtyper**

Hvis modellnavnet inneholder en fil extension, kan utvidelsen søkes på med vanlig tekstsøk. Søk på filtillegg med punktum inkludert for å søke etter en bestemt filtype. For eksempel når du søker på .ifc, kan alle dokumenter med .ifc i modellnavnet bli funnet.

## 5. **Sortering**

Modeller kan sorteres ved å klikke på hodeteksten på hver kolonne. Hodeteksten kan klikkes flere ganger for å tilbakestille eller deaktivere sorteringen.

_Navn, a-z_ - Standard _Navn, z-a_ - `sort=modelName-desc` _Dokumentnavn, a-z_ - `sort=name-asc` _Dokumentnavn, z-a_ -`sort=name-desc` _Publisert, nyeste først_ - `sort=publishedAt-desc` _Publisert, eldste først_ - `sort=publishedAt-asc` _Dokument opprettet, nyeste først_ - `sort=createdAt-desc` _Dokument opprettet, eldste først_ - `sort=createdAt-asc` Revisjon opprettet_, nyeste først_ - `sort=revisionCreatedAt-desc` Revisjon opprettet_, eldste først_ - `sort=revisionCreatedAt-desc`
