# Filtrering på objektsiden

Filterpanelet på objektsiden kan åpnes ved å klikke på filterknappen til venstre for søkelinjen på objektsiden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/01-intro.png)
Slik kan søk- eller filtreringsmenyen se ut når den åpnes:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/02-intro.png)

## 1. **Filtre**

Klikk på filterknappen øverst til venstre for at et panel skal vises på venstre side. Når et filter brukes, endres URL-en som vises i nettleseren. I denne artikkelen vises filtre slik: _Filternavn i meny_ - `Filternavn i URL=Filteralternativ i URL`

_Standardfilter_ Standardfilteret er opprinnelig ikke synlig i URL-en. Når siden åpnes for første gang, brukes følgende filter.

_Ikke filter_

### 1.1 **Lagre og del gjeldende filter**

Gå til URL-en på en filtrert side for å laste siden med filteret brukt. De brukte filtrene kan lagres øverst i filtermenyen. Klikk [her](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) for å lese mer om hvordan du lagrer og deler filtre

### 1.2 **Skjul tomme filtre**

Klikk [her](https://support.catenda.com/en/articles/8551755-saving-filters) for å lese mer om å begrense filterresultater.

### 1.3 **Modeller**

Klikk på 3D til høyre for modellkategorien i filtermenyen for å filtrere på alle modeller som er lastet inn i 3D-visningen.

Modellnavn - `model=<Model GUID>` Filtrer på et sett med prosjektmodeller.

### 1.4 **Valgt**

Valgt - `selected=true` Filtrer for kun å vise rader for objekter som er valgt i 3D-visningen.

## 2. **Filtre som ikke er oppført i filterpanelet**

### 2.1 **Spørring**

Søking i spørring - `query=<Product>,<Operator>,<Value>` Klikk i søk- eller filterlinjen for å konfigurere et filter som sammenligner to verdier.

_Produkt_ Det første valget kan være enhver type IFC-produkt. Slik kan rullegardinmenyen for produkter se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/03-query.png)

_Operator_ Operatoren kan bare velges etter at et produkt er valgt. Operatordelen av spørringsfilteret bestemmer hvordan produktet sammenlignes med verdien. Avhengig av om produktet kan ha en hvilken som helst verdi eller bare kan ha et begrenset sett av verdier, kan det velges mellom forskjellige operatorer:

Alltid tilgjengelige operatorer: Lik - `equals` Når det valgte produktet har nøyaktig den angitte verdien

Ikke lik - `not-equals` Når det valgte produktet ikke har nøyaktig den angitte verdien

Eksisterer - `exists` Når eksisterer velges, kan bare et produkt velges og ikke en verdi siden alle verdier er en del av dette filteret

Eksisterer ikke - `not-exists` Når eksisterer ikke velges, kan bare et produkt velges og ikke en verdi siden alle verdier er en del av dette filteret

Operatorer for begrenset sett med verdier Slik kan rullegardinmenyen for operatorer se ut når den valgte egenskapen har et begrenset sett med verdier:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/04-query.png)

Inneholder - `contains`

Inneholder ikke - `not-contains` For å få resultater om produkter som ikke inneholder en bestemt verdi

Har verdi - `has-value` Når har verdi velges, kan bare et produkt velges og ikke en verdi siden alle verdier er en del av dette filteret

Operatorer for hvilken som helst verdi Slik kan rullegardinmenyen for operatorer se ut når den valgte egenskapen kan ha en hvilken som helst verdi:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/05-query.png)

I område - `range-inclusive` Når operatoren i området velges, finnes det to verdifelt. Slik kan det se ut når et filter i området redigeres.:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/06-query.png)

Området vil være hva som helst fra første verdi til andre verdi.

Større enn eller lik - `greater-than-equals`

Større enn - `greater-than`

Mindre enn eller lik - `less-than-equals`

Mindre enn - `less-than`

_Verdi_ Verdifeltet oppfører seg ulikt avhengig av de mulige verdiene som det valgte produktet kan ha.

Tallverdi Når det valgte produktet bare kan ha en tallverdi, vises piler når verdifeltet klikkes på, og bare tall kan angis.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/07-query.png)

Foreslåtte verdier Når et produkt kan ha en tekstverdi, kan den skrives direkte i verdifeltet. Slik kan verdienmenyen se ut når Entity-produktet er valgt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0470bggc/08-query.png)

Når du klikker i verdifeltet, vises en liste over foreslåtte elementer under feltet. Hvis det valgte produktet bare kan ha et begrenset sett med verdier, vises dette begrensede settet med verdier i listen over foreslåtte elementer. Hvis det valgte produktet kan ha en hvilken som helst verdi, viser listen over foreslåtte elementer en liste over verdier som andre produkter av denne typen har.
