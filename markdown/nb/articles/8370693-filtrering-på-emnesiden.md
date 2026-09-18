# Filtrering på sakssiden

Filtermeny i en saksliste kan åpnes ved å klikke på filterknappen til venstre for søkelinjen i en [saksliste](https://support.catenda.com/en/articles/4670271-issues-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/01-intro.png)

## 1. **Filtre**

Klikk på filterknappen øverst til venstre for at et panel skal vises på venstre side. Når et filter brukes, endres URLen som vises i nettleseren tilsvarende. I denne artikkelen vises filtre slik: _Filternavn i meny_ - `Filternavn i URL=Filteralternativ i URL`

_Standardfilter_ Standardfilteret er opprinnelig ikke synlig i URLen. Når siden navigeres til for første gang, brukes følgende filter. _Ingen filter_ - `status-type=all`

### 1.1 **Lagre og del gjeldende filter**

Gå til URLen til en filtrert side for å laste inn siden med filteret brukt. De brukte filtrene kan lagres øverst i filtermeny. Klikk [her](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) for å lese mer om hvordan du lagrer og deler filtre

### 1.2 **Skjul tomme filtre**

Klikk [her](https://support.catenda.com/en/articles/8551755-saving-filters) for å lese mer om å begrense filterresultater.

## 2. **Filtrering i filtermeny**

Her finnes følgende filtre:

De ulike filtrene i filtermeny vises bare hvis det finnes saker der elementet som filtreres for er konfigurert.

### 2.1 **Mine saker**

Tildelt til meg - `assigned-user=<User GUID>&assigned-team=<Team GUID>` _Tildelt bruker_ - `assigned-user=<User GUID>` _Mine team_ - `assigned-team=<Team GUID>` _Etterspurt av meg_ - `requester-user=<Your GUID>` Saker _jeg følger_ - `followed-by=me` _som nevner meg_ - `mentioned=me`

> **Merknad:** Hvis du deler en lenke med filtrene "Sak jeg følger" eller "som nevner meg" aktiv, vil brukeren som åpner lenken ha sakslistene sine filtrert for saker de følger og saker de er nevnt i, og ikke saker du følger og saker du er nevnt i. For å dele saker du er nevnt i, bruk [tekstsøk](#h_7fc30a16f0)

_Opprettet av meg_ - `created-by=<User GUID>`

### 2.2 **Status / Type**

_Alle åpne status_ - `status-type=open` _Spesifikk åpen status_ - `status-type=<Status GUID>` _Alle lukkede status_ - `status-type=closed` _Spesifikk lukket status_ - `status-type=<Status GUID>` _Type_ - `type=<Type GUID>`

### 2.3 **Frist**

_Forfalt_ - `due=overdue` _Alt med frist_ - `due=present` _Ingen frist_ - `due=none`

### 2.4 **Oppdatert**

Med datofilteret kan du velge en tidsramme for når sakene sist ble oppdatert. _Oppdatert_ - `updated-from=<Epoch Unix Timestamp>&updated-to=<Epoch Unix Timestamp>` Les [denne](https://support.catenda.com/en/articles/6511685-date-filter) artikkelen for å lære hvordan du enkelt velger datoer på siden.

### 2.5 **Tildelt til / Etterspurt av**

_Tildelt ingen_ - `assigned=unassigned` _Ingen team tildelt_ - `assigned-team=unassigned` _Tildelt team_ - `assigned-team=<Team GUID>` _Ikke tildelt bruker_ - `assigned-user=unassigned` _Tildelt bruker_ - `assigned-user=<User GUID>` Tildelt operator - `assigned-op=and` Som standard kan du bare søke etter den tildelte brukeren ELLER det tildelte teamet. I Catenda Hub kan du angi en tildelt som bruker@team For å finne alle saker av denne typen**,** filtrer etter teamet og brukeren, og legg til &assigned-op=and på slutten av URLen.

_Ikke etterspurt_ - `requester=unassigned` _Ikke etterspurt av team_ - `requester-team=unassigned` _Ikke etterspurt av bruker_ - `requester-user=unassigned` _Etterspurt av bruker_ - `requester-user=<User GUID>`

### 2.6 **Opprettet av**

_Opprettet av bruker_ - `created-by=<User GUID>`

### 2.7 **Milepæl**

_Milepæl_ - `milestone=<Milestone GUID>`

### 2.8 **Egendefinert felt**

_Egendefinert felt har verdi_ - `custom-field-has-value-<Custom field GUID>=true` Med "har verdi"-alternativet i filtermeny kan alle saker som har en verdi konfigurert for det egendefinerte feltet filtreres. Egendefinerte felttyper som kan filtreres på har verdi: Dato Desimal Rullegardin Heltall Tekst

_Egendefinert felt spesifikk verdi_ - `custom-field-item-<Custom field GUID>=<Value GUID>` Egendefinerte felttyper som kan filtreres på spesifikk verdi fra filtermeny: Rullegardin

Noen verdier i egendefinerte felt der verdier kan konfigureres, kan filtreres. Filtrer verdier ved å skrive en søkefrase i søke- eller filterlinjen og velg det tilsvarende egendefinerte feltet. Egendefinerte felttyper som kan filtreres ved å skrive i søke- eller filterlinjen: Desimal Rullegardin Heltall Tekst

_Egendefinert felt har ingen verdi_ - `custom-field-has-value-<Custom field GUID>=false` Filtrer på alle saker der et egendefinert felt ikke har noen verdi. Egendefinerte felttyper som kan filtreres på ingen verdi: Dato Desimal Rullegardin Heltall Tekst

> **Merknad:** Egendefinerte felt som er angitt som påkrevd, vil alltid ha en verdi. Du vil derfor ikke kunne søke etter "har verdi" eller "har ingen verdi" kan derfor ikke søkes etter et egendefinert felt som er angitt som påkrevd.

### 2.9 **Merkelapp**

_Merkelapp_ - `label=<Label GUID>` Merkelapper i sin egen merkelappgruppe vises i en separat liste.

### 2.10 **Lenker**

Lenket - `associations=exists` Filtrer på saker lenket til modellobjekter i 3D-viseren.

Ikke lenket - `associations=does-not-exist` Filtrer på saker som ikke er lenket til modellobjekter i 3D-viseren.

Lenket til valgte objekter - `link=backlink` Hvis 3D-panelet ikke allerede er åpent, åpnes det. Velg objekter fra en modell i 3D-viseren for å filtrere på saker lenket til de valgte objektene.

## 3. **Filtrering i søke- eller filterlinjen**

I tillegg til filtermeny til venstre, finnes det noe funksjonalitet som bare er tilgjengelig gjennom søke- eller filterlinjen. Slik kan søke- eller filterlinjen se ut når den er uthevet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/02-filtering-in-the-search-or-filter-bar.png)

Under søke- eller filterlinjen åpnes en meny med foreslåtte filtre. Det første filteret i filtermeny foreslås etter at søke- eller filtermeny er uthevet. Trykk Enter for å bruke dette filteret eller bruk piltastene til å navigere mellom de ulike filtrene.

### 3.1 **Lagrede filtre**

Hvis du har noen lagrede filtre i en saksliste, vil disse være det første tilgjengelige filteret i filtermeny og vil bli foreslått så snart søke- eller filterfeltet er fremhevet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/03-saved-filters.png)

Klikk på filteret for å åpne filteret på brettet på det lagrede settet med filtre som har fått et navn. Klikk [her](https://support.catenda.com/en/articles/8551755-saving-filters) for å lese mer om hvordan du lagrer et sett med filtre.

### 3.2 **Tekstsøk**

_Tekstsøk -_ `search=<Search phrase>` Etter å ha skrevet inn tegn i søke- eller filterlinjen, endres det første foreslåtte filteret til tekstsøk.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/04-text-search.png)

_Innhold som kan søkes på_ Saktittel Saksbeskrivelse Sakskommentarer

_Stor-/små bokstaver_ Tekstsøket er ikke følsomt for store eller små bokstaver.

_Antall tegn_ Enkelt tegn Innhold som inkluderer det søkte tegnet samsvarer med mindre det er en Unicode-bokstav med en verdi som er 58 eller høyere ved starten av innholdet.

To tegn Innhold som har ett enkelt ord, atskilt av et skilletegn som mellomrom, som samsvarer med søkefraser som er inkludert i resultatene.

Tre eller flere tegn Innhold som samsvarer med søkefrasen i en hvilken som helst del av innholdet, er inkludert i resultatene.

_Mellomrom_ Mellomromstegn ved begynnelsen av en søkefrase fjernes.

_Søking etter nevnte medlemmer eller team_ Saker der et medlem eller team er nevnt i en kommentar eller beskrivelse, kan finnes ved å bruke tekstsøk:

Medlems- eller teamnavn Søk etter navn på medlemmet eller teamet for å finne alle vanlige tekstforekomster av medlemmet eller teamnavnet.

Nevnt medlem Søk etter e-posten til et medlem for å finne alle vanlige tekstforekomster av medlemmets e-post. Dette inkluderer hvor de er nevnt. Søk på `#[<E-post av medlem>]` for å finne bare forekomstene der medlemmet er nevnt.

Nevnt team Nevnte team kan søkes på ved å søke på GUID-en til det teamet. For å finne GUID-en til et team, går du til [innholdssiden for det teamet](https://support.catenda.com/en/articles/7891755-team-page) ved å klikke på navnet på [teamfanen på siden for medlemmer og team](https://support.catenda.com/en/articles/4670291-members-and-teams-page). URLen skal se omtrent slik ut: [https://hub.catenda.com/project/\<Project](https://hub.catenda.com/project/<Project) GUID>/members/\<Member GUIID>

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/05-text-search.png)

Søk på team-GUID-en for å finne alle vanlige tekstforekomster av team-GUID-en. Dette inkluderer hvor de er nevnt. Søk på `#[<team GUID>]` for å finne bare forekomstene der teamet er nevnt.

### 3.3 **Egendefinerte felt - Tekst**

Hvis en søkefrase starter med et Unicode-tegn med en Unicode-verdi som er 58 eller høyere, vises følgende filtre mot bunnen av listen over foreslåtte filtre.

_Tekstegendefinert felt -_ `custom-field-<Custom field GUID>=<Search phrase>` Hvis et tekstegendefinert felt er aktivert i sakslistene, kan innholdet av tekstegendefinerte felt i alle saker i brettet filtreres med dette filteret.

### 3.4 **Numerisk søkefrase**

Hvis en søkefrase starter med et Unicode-tegn med en Unicode-verdi mellom 33 og 57, vises følgende filtre mot bunnen av listen over foreslåtte filtre.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/06-number-search-phrase.png)

Dette inkluderer følgende tegn: `!`,`"`,`#`,`$`,`%`,`&`,`'`,`(`,`)`,`*`,`+`,`,`,`-`,`.`,`/`,`0`,`1`,`2`,`3`,`4`,`5`,`6`,`7`,`8`,`9`

_Sak -_ `issues=<issue number>` Når en søkefrase starter med et tall, vises saksnummersøket som et forslag i søke- eller filterlinjen. Det foreslåtte filteret kan se omtrent slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/07-number-search-phrase.png)

Selv om det er mulig å filtrere et brett for saknumre med mer enn bare tall, kan saker bare finnes med nummeret sitt med dette filteret. Hvis mer enn bare tall gis, forsvinner filteret fra menyen, men brettet blir fortsatt filtrert på den angitte frasen.

Filtrering på en eller flere saker etter nummer Det er bare mulig å søke etter en sak om gangen fra søke- eller filterlinjen. Hvis saken med Catenda-saknummeret 123 finnes i brettet, vil URL-en ha `&issues=123` i den når den filtreres på saknummer 123. Det er mulig å angi flere saknumre i URL-en, for eksempel: `&issues123,124,125` ville resultert i at alle tre sakene vises hvis de finnes i brettet. Filtrering på flere saker på denne måten er bare mulig ved å redigere URL-en.

### 3.5 **Egendefinerte felt - Nummer**

_Heltallsegendefinert felt -_ `custom-field-<Custom field GUID>=<Search phrase>` Hvis et heltallsegendefinert felt er aktivert i sakslistene, kan innholdet av heltallsegendefinerte felt i alle saker i brettet filtreres med dette filteret.

_Desimalegendefinert felt -_ `custom-field-<Custom field GUID>=<Search phrase>` Hvis et desimalegendefinert felt er aktivert i sakslistene, kan innholdet av desimalegendefinerte felt i alle saker i brettet filtreres med dette filteret.

### 3.6 **Egendefinerte felt - Rullegardin**

Hvis en søkefrase samsvarer med navnet på en verdi i et filter, foreslås filteret som passer best i forslagsfeltet.

_Rullegardinegendefinert felt_ _-_ `custom-field-item-<Custom field GUID>=<Dropdown value GUID>` Hvis søkefrasen samsvarer med en verdi i et rullegardinegendefinert felt med opptil 10 verdier, vil det bli foreslått å søke etter den rullegardinverdien.
