# Filtrering på emnesiden

Filtermeny i et emnebrett kan åpnes ved å klikke på filterknappen til venstre for søkefeltet i et [emnerett](https://support.catenda.com/en/articles/4670271-issues-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/01-intro.png)

## 1. **Filtre**

Klikk filterknappen øverst til venstre for at et panel skal vises på venstre side. Når et filter er brukt, endres nettadressen som vises i nettleseren med det. I denne artikkelen vises filtre slik: _Filternavn i meny_ - `Filternavn i nettadresse=Filteralternativ i nettadresse`

_Standardfilter_ Standardfilteret er opprinnelig ikke synlig i nettadressen. Når siden navigeres til for første gang brukes følgende filter. _Ingen filter_ - `status-type=all`

### 1.1 **Lagre og del gjeldende filter**

Gå til nettadressen på en filtrert side for å laste siden med filteret brukt. De brukte filtrene kan lagres mot toppen av filtermeny. Klikk [her](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) for å lese mer om hvordan du lagrer og deler filtre

### 1.2 **Skjul tomme filtre**

Klikk [her](https://support.catenda.com/en/articles/8551755-saving-filters) for å lese mer om å begrense filterresultater.

## 2. **Filtrering i filtermeny**

Her finner du følgende filtre:

De ulike filtrene i filtermeny vises bare hvis det er emner der elementet som filtreres på har blitt konfigurert.

### 2.1 **Mine emner**

Tildelt til meg - `assigned-user=\<User GUID>&assigned-team=\<Team GUID>` _Tildelt bruker_ - `assigned-user=\<User GUID>` _Mine teams_ - `assigned-team=\<Team GUID>` _Etterspurt av meg_ - `requester-user=\<Your GUID>` Emner _jeg følger_ - `followed-by=me` _som nevner meg_ - `mentioned=me`

> **Merk:** Hvis du deler en lenke med filteret "Emne jeg følger" eller "som nevner meg" aktivt, vil brukeren som åpner lenken få emnerettets sitt filtrert for emner de følger og emner de har blitt nevnt i, og ikke emner du følger og emner du har blitt nevnt i. For å dele emner du har blitt nevnt i, bruk [tekstsøk](#text-search)

_Opprettet av meg_ - `created-by=\<User GUID>`

### 2.2 **Status / Type**

_All åpne status_ - `status-type=open` _Spesifikk åpen status_ - `status-type=\<Status GUID>` _All lukket status_ - `status-type=closed` _Spesifikk lukket status_ - `status-type=\<Status GUID>` _Type_ - `type=\<Type GUID>`

### 2.3 **Frist**

_Forfalt_ - `due=overdue` _Alle med en frist_ - `due=present` _Ingen frist_ - `due=none`

### 2.4 **Oppdatert**

Med datofilteret kan du velge en tidsramme for når emnene ble sist oppdatert. _Oppdatert_ - `updated-from=\<Epoch Unix Timestamp>&updated-to=\<Epoch Unix Timestamp>` Les [denne](https://support.catenda.com/en/articles/6511685-date-filter) artikkelen for å lære hvordan du enkelt velger datoer på siden.

### 2.5 **Tildelt til / Etterspurt av**

_Tildelt ingen_ - `assigned=unassigned` _Ingen team tildelt_ - `assigned-team=unassigned` _Tildelt team_ - `assigned-team=\<Team GUID>` _Ikke tildelt bruker_ - `assigned-user=unassigned` _Tildelt bruker_ - `assigned-user=\<User GUID>` Tildelt operator - `assigned-op=and` Som standard kan du bare søke etter den tildelte brukeren ELLER det tildelte teamet. I Catenda Hub kan du angi en tildelng som bruker@team For å finne alle emner av denne typen\*\*,\*\* filtrer etter teamet og brukeren, og legg til &assigned-op=and på slutten av nettadressen.

_Ikke etterspurt_ - `requester=unassigned` _Ikke etterspurt av team_ - `requester-team=unassigned` _Ikke etterspurt av bruker_ - `requester-user=unassigned` _Etterspurt av bruker_ - `requester-user=\<User GUID>`

### 2.6 **Opprettet av**

_Opprettet av bruker_ - `created-by=\<User GUID>`

### 2.7 **Milestone**

_Milestone_ - `milestone=\<Milestone GUID>`

### 2.8 **Egendefinert felt**

_Egendefinert felt har verdi_ - `custom-field-has-value-\<Custom field GUID>=true` Med alternativet "har verdi" i filtermeny kan alle emner som har en verdi konfigurert for det egendefinerte feltet filtreres. Egendefinert felttyper som kan filtreres på har verdi: Dato Desimal Rullegardin Heltall Tekst

_Egendefinert feltspesifikk verdi_ - `custom-field-item-\<Custom field GUID>=\<Value GUID>` Egendefinert felttyper som kan filtreres på spesifikk verdi fra filtermeny: Rullegardin

Noen verdier i egendefinerte felt der verdier kan konfigureres kan filtreres. Filtrer verdier ved å skrive en søkefrase i søke- eller filterfeltet og velge det tilsvarende egendefinerte feltet. Egendefinert felttyper som kan filtreres ved å skrive i søke- eller filterfeltet: Desimal Rullegardin Heltall Tekst

_Egendefinert felt har ingen verdi_ - `custom-field-has-value-\<Custom field GUID>=false` Filtrer på alle emner der et egendefinert felt ikke har noen verdi. Egendefinert felttyper som kan filtreres på ingen verdi: Dato Desimal Rullegardin Heltall Tekst

> **Merk:** Egendefinerte felt som er satt som påkrevd vil alltid ha en verdi. Du vil derfor ikke kunne søke etter "har verdi" eller "har ingen verdi" kan derfor ikke søkes etter for et egendefinert felt som er satt som påkrevd.

### 2.9 **Merkelapp**

_Merkelapp_ - `label=\<Label GUID>` Merkelapper i sin egen merkelappgruppe vises i en egen liste.

### 2.10 **Lenker**

Lenket - `associations=exists` Filtrer på emner lenket til modelobjekter i 3D-visningen.

Ikke lenket - `associations=does-not-exist` Filtrer på emner som ikke er lenket til modelobjekter i 3D-visningen.

Lenket til valgte objekter - `link=backlink` Hvis den ikke allerede er åpen, vil 3D-panelet åpnes. Velg objekter fra en modell i 3D-visningen for å filtrer på emner lenket til de valgte objektene.

## 3. **Filtrering i søke- eller filterfeltet**

I tillegg til filtermeny på venstre side er det noen funksjoner som bare er tilgjengelig gjennom søke- eller filterfeltet. Slik kan søke- eller filterfeltet se ut når det er uthevet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/02-filtering-in-the-search-or-filter-bar.png)

Under søke- eller filterfeltet åpnes en meny med foreslåtte filtre. Det første filteret i filtermeny foreslås etter uthevning av søke- eller filtermeny. Trykk Enter for å bruke dette filteret, eller bruk piltastene til å navigere mellom de ulike filtrene.

### 3.1 **Lagrede filtre**

Hvis du har lagrede filtre i et emnerett, vil disse være det første tilgjengelige filteret i filtermeny og vil foreslås så snart søke- eller filterfeltet er uthevet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/03-saved-filters.png)

Klikk på filteret for å åpne filtrer brettet på det lagrede settet med filtre som har fått et navn. Klikk [her](https://support.catenda.com/en/articles/8551755-saving-filters) for å lese mer om hvordan du lagrer et sett med filtre.

### 3.2 **Tekstsøk**

_Tekstsøk -_ `search=\<Search phrase>` Etter å ha skrevet tegn i søke- eller filterfeltet endres det første foreslåtte filteret til tekstsøk.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/04-text-search.png)

_Innhold som kan søkes på_ Emnetittel Emnebeskrivelse Emnekommentarer

_Kapitalisering_ Tekstsøket er ikke følsom for store eller små bokstaver.

_Tegntall_ Ett tegn Innhold som inkluderer det søkte tegnet samsvares med mindre det er en unicode-bokstav med en verdi som er 58 eller høyere ved starten av innholdet.

To tegn Innhold som har ett enkelt ord, atskilt av et skilletegn som et mellomrom, som samsvarer med søkefrasen er inkludert i resultatene.

Tre eller flere tegn Innhold som samsvarer med søkefrasen i hvilken som helst del av innholdet er inkludert i resultatene.

_Mellomrom_ Mellomromstegn ved starten av en søkefrase fjernes.

_Søking etter nevnte medlemmer eller teams_ Emner der et medlem eller team har blitt nevnt i en kommentar eller beskrivelse kan finnes ved hjelp av tekstsøk:

Medlems- eller teamnavn Søk etter medlems- eller teamnavn for å finne alle vanlige tekstforekomster av det medlems- eller teamnavnet.

Nevnt medlem Søk etter e-posten til et medlem for å finne alle vanlige tekstforekomster av det medlemmets e-post. Dette inkluderer der de har blitt nevnt. Søk etter `#[\<E-postadresse for medlem>]` for å finne bare forekomstene der det medlemmet er nevnt.

Nevnt team Nevnte teams kan søkes etter ved å søke på GUID-en til det teamet. For å finne GUID-en til et team, går du til [innholdssiden til det teamet](https://support.catenda.com/en/articles/7891755-team-page) ved å klikke på navnet hans på [teams-fanen på medlems- og teamssiden](https://support.catenda.com/en/articles/4670291-members-and-teams-page). Nettadressen bør se omtrent slik ut: [https://hub.catenda.com/project/\<Project](https://hub.catenda.com/project/<Project) GUID>/members/\<Member GUIID>

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/05-text-search.png)

Søk etter team-GUID-en for å finne alle vanlige tekstforekomster av det team-GUID-en. Dette inkluderer der de har blitt nevnt. Søk etter `#[\<team GUID>]` for å finne bare forekomstene der det teamet er nevnt.

### 3.3 **Egendefinert felt - Tekst**

Hvis en søkefrase begynner med et unicode-tegn med en unicode-verdi som er 58 eller høyere, vil følgende filtre vises mot bunnen av listen over foreslåtte filtre.

_Tekstegendefinert felt -_ `custom-field-\<Custom field GUID>=\<Search phrase>` Hvis et tekstegendefinert felt er aktivert i emnerettet, kan innholdet i tekstegendefinerte felt i alle emner i brettet filtreres med dette filteret.

### 3.4 **Tallsøkefrase**

Hvis en søkefrase begynner med et unicode-tegn med en unicode-verdi mellom 33 og 57, vil følgende filtre vises mot bunnen av listen over foreslåtte filtre.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/06-number-search-phrase.png)

Dette inkluderer følgende tegn: `!`,`"`,`#`,`$`,`%`,`&`,`'`,`(`,`)`,`\*`,`+`,`,`,`-`,`.`,`/`,`0`,`1`,`2`,`3`,`4`,`5`,`6`,`7`,`8`,`9`

_Emne -_ `issues=\<issue number>` Når en søkefrase begynner med et tall, vises emnenummersøket som en forslag i søke- eller filterfeltet. Det foreslåtte filteret kan se omtrent slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/07-number-search-phrase.png)

Selv om det er mulig å filtrer et brett for emnenumre med mer enn bare tall, kan emner bare finnes med nummeret sitt med dette filteret. Hvis det bare er tall som er oppgitt, vil filteret forsvinne fra menyen, men brettet vil fortsatt bli filtrert på den oppgitte frasen.

Filtrering på ett eller flere emner etter nummer Det er bare mulig å søke etter ett emne om gangen fra søke- eller filterfeltet. Hvis emnet med Catenda-emnenummeret 123 finnes i brettet, vil nettadressen ha `&issues=123` i den når den filtreres etter emnenummer 123. Det er mulig å legge inn flere emnenumre i nettadressen, for eksempel: `&issues123,124,125` ville resultert i at alle tre emnene vises hvis de finnes i brettet. Filtrering på flere emner på denne måten er bare mulig ved å redigere nettadressen.

### 3.5 **Egendefinert felt - Tall**

_Egendefinert heltallsfelt -_ `custom-field-\<Custom field GUID>=\<Search phrase>` Hvis et egendefinert heltallsfelt er aktivert i emnerettet, kan innholdet i egendefinerte heltallsfelt i alle emner i brettet filtreres med dette filteret.

_Egendefinert desimalfelt -_ `custom-field-\<Custom field GUID>=\<Search phrase>` Hvis et egendefinert desimalfelt er aktivert i emnerettet, kan innholdet i egendefinerte desimalfelt i alle emner i brettet filtreres med dette filteret.

### 3.6 **Egendefinert felt - Rullegardin**

Hvis en søkefrase samsvarer med navnet på en verdi i et filter, vil filteret som passer best foreslås i forslagsboksen.

_Rullegardinegendefinert felt_ _-_ `custom-field-item-\<Custom field GUID>=\<Dropdown value GUID>` Hvis søkefrasen samsvarer med en verdi i et rullegarddinegendefinert felt med opptil 10 verdier, vil det foreslås å søke på den rullegarddinverdien.
