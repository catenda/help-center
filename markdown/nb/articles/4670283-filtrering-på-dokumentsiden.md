# Filtrering på dokumentsiden

Søke- eller filteralternativet kan ses i den øverste delen av vinduet. Ved å skrive navnet på dokumentet eller skrive navnet på en merkelapp som er festet til et dokument, kan radene i dokumenttabellen innsnevres. Slik kan søke- eller filtermenyen se ut på dokumentsiden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aa862mj2/01-intro.png)

Følgende saker er beskrevet i denne artikkelen:

## 1. **Filtre**

Klikk på filterknappen øverst til venstre for at et panel skal vises på venstre side. Når et filter brukes, endres URL-en som vises i nettleseren. I denne artikkelen vises filtre slik: _Filternavn i meny_ - `Filternavn i URL=Filteralternativ i URL`

_Standardfilter_ Standardfilteret er ikke synlig i URL-en i utgangspunktet. Når siden navigeres til for første gang, brukes følgende filter. Arbeidsområdefane - `v=all`

Følgende saker er beskrevet i denne delen:

### 1.1 **Lagre og del gjeldende filter**

Gå til URL-en på en filtrert side for å laste inn siden med filteret brukt. De brukte filtrene kan lagres øverst i filtermenyen. Klikk [her](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) for å lese mer om hvordan du lagrer og deler filtre. Merk at i motsetning til i andre filtermenyer er det ikke mulig å lagre personlige filtre øverst i filtermenyen på siden for gjennomganger.

### 1.2 **Skjul tomme filtre**

Klikk [her](https://support.catenda.com/en/articles/8551755-saving-filters) for å lese mer om begrensning av filterresultater.

### 1.3 **Faner**

Arbeidsområdefane - `v=all` Publisert fane - `v=published`

### 1.4 **Lenker**

Lenket - `associations=exists&subFolders=true` Filtrer på dokumenter som er lenket til modelobjekter i 3D-visningen.

Ikke lenket - `associations=does-not-exist&subFolders=true` Filtrer på dokumenter som ikke er lenket til modelobjekter i 3D-visningen.

Lenket til valgte objekter - `link=backlink&subFolders=true` Hvis 3D-panelet ikke allerede er åpent, vil det åpnes. Velg objekter fra en modell i 3D-visningen for å filtrere på saker som er lenket til de valgte objektene.

### 1.5 **Status (siste revisjon) - Kun arbeidsflyt**

Publisert - `documentStatus=published&subFolders=true&documentType=file` Manglende status - `documentStatus=published-without-status&subFolders=true` Prosjektpublisert status - `documentStatus=<GUID>&subFolders=true` Delt - `documentStatus=shared&subFolders=true&documentType=file` Delte statusverdier er bare tilgjengelige i arbeidsområdefanen Prosjektdelt status - `documentStatus=<GUID>&subFolders=true` Ingen revisjon - `documentStatus=no-stage&subFolders=true`

### 1.6 **Utkast - Kun arbeidsflyt**

Har nye utkast - `newDrafts=exists&subFolders=true` Navn på utkastsstatus - `newDrafts=<Draft status GUID>&subFolders=true` Hvis det er flere utkaststatustyper, kan hver utkastsstatus filtreres på. Ingen nye utkast - `newDrafts=does-not-exist&subFolders=true`

### 1.7 **Modeller**

Er modell - `model=is-model&subFolders=true` Er ikke modell - `model=is-not-model&subFolders=true`

### 1.8 **Dokument opprettet av**

Medlemsnavn - `owner=<Member GUID>&subFolders=true`

### 1.9 **Revisjon opprettet av**

Medlemsnavn - `revisionCreatedBy=<GUID>&subFolders=true`

### 1.10 **Publisert av**

Medlemsnavn - `publishedBy=<Member GUID>&subFolders=true`

### 1.11 **Datumfiltre**

Publisert - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Klikk på velg datoer for å velge datoer som du vil søke mellom Klikk [her](https://support.catenda.com/en/articles/6511685-date-filter) for å lese mer om datumsilteret

### 1.12 **Åpne gjennomganger - Kun arbeidsflyt**

Navn på gjennomgang - `approval=<Approval number>&subFolders=true`

### 1.13 **Dokumenter - Merkelapper**

Alle merkelapper som ikke er del av en merkelappegruppe, vil vises på en meny kalt dokumenter. Navn på merkelapp - `labels=<Label GUID>6&subFolders=true`

### 1.14 **Navn på merkelappegruppe**

Det vil være en meny per merkelappegruppe-navn Navn på merkelapp - `labels=<Label GUID>6&subFolders=true`

Innholdet av egendefinerte felt der verdier kan konfigureres, kan filtreres ved å skrive en søkefrase i søke- eller filterfeltet og velge det tilsvarende filteret i det foreslåtte filteret.

### 1.15 **Egendefinert felt**

_Egendefinert felt har verdi_ - `custom-field-has-value-<Custom field GUID>=true` Med alternativet "har verdi" i filtermenyen kan alle saker som har en verdi konfigurert for det egendefinerte feltet, filtreres. Egendefinerte felttyper som kan filtreres på har verdi: Dato Desimal Rullegardinliste Heltall Tekst

_Egendefinert feltspesifikk verdi_ - `custom-field-item-<Custom field GUID>=<Value GUID>` Spesifikke verdier i felt for felt med opptil 10 verdier kan filtreres. Egendefinerte felttyper som kan filtreres på spesifikk verdi fra filtermenyen: Rullegardinliste

Noen verdier i egendefinerte felt der verdier kan konfigureres, kan filtreres. Filtrer etter verdier ved å skrive en søkefrase i søke- eller filterfeltet og velg det tilsvarende egendefinerte feltet. Egendefinerte felttyper som kan filtreres ved å skrive i søke- eller filterfeltet: Desimal Rullegardinliste Heltall Tekst

_Egendefinert felt har ingen verdi_ - `custom-field-has-value-<Custom field GUID>=false` Filtrer på alle saker der et egendefinert felt ikke har noen verdi. Egendefinerte felttyper som kan filtreres på ingen verdi: Dato Desimal Rullegardinliste Heltall Tekst

> **Merk:** Egendefinerte felt som er satt som påkrevd, vil alltid ha en verdi. Du vil derfor ikke være i stand til å søke etter "har verdi" eller "har ingen verdi", og kan derfor ikke søkes etter et egendefinert felt som er satt som påkrevd.

### 1.16 **Samlinger**

Navn på samling - `collections=<GUID>&subFolders=true`

### 1.17 **Slettet**

Slettet - `deleted=deleted&subFolders=true` Se [her](https://support.catenda.com/en/articles/4670249-undeleting-restoring-documents-or-folders) hvordan du søker etter slettede dokumenter

## 2. **Tekstsøk**

_Tekstsøk_ - `search=test&subFolders=true`

### 2.1 **Innhold som kan søkes på**

Dokumenttittel Mappenavn

### 2.2 **Stor- og småbokstaver**

Tekstsøket er ikke følsomt for store eller små bokstaver.

### 2.3 **Tegntall**

Ett tegn - Titler som inneholder det søkte tegnet blir truffet. To tegn - Ingen resultater. Tre eller flere tegn - Titler som har ett enkelt ord, atskilt av et skilletegn som et mellomrom, som stemmer med søkefrasen, er inkludert i resultatene.

### 2.4 **Filtyper**

Hvis tittelen inneholder en utvidelse, kan utvidelsen søkes på med ordinært tekstsøk. Søk på filutvidelsen med punktum inkludert for å søke etter en bestemt filtype. For eksempel, når du søker på .ifc, kan alle dokumenter med .ifc i tittelen finnes.

## 3. **Sortering**

Dokumenter kan sorteres ved å klikke på overskriften til hver kolonne. Overskriften kan klikkes flere ganger for å reversere eller deaktivere sorteringen.

_Tittel, a-å_ - Standard _Navn, å-a_ - `sort=name-desc` _Publisert, nyeste først_ - `sort=publishedAt-desc` _Publisert, eldste først_ - `sort=publishedAt-asc` _Opprettet, nyeste først_ - `sort=createdAt-desc` _Opprettet, eldste først_ - `sort=createdAt-asc`
