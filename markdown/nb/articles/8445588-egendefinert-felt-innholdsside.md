# Egendefinert felt - innholdsside

Du vil kunne finne siden for et egendefinert felt ved å klikke på det respektive feltet på [egendefinerte felt-siden](https://support.catenda.com/en/articles/6550459-custom-fields-page) som du finner som en underside til [prosjektinnstillinger-siden](https://support.catenda.com/en/articles/4670273-project-settings-page).

Når du oppretter et egendefinert felt, kan du legge det til på et issue board. Saker på dette boardet vil da få et nytt felt i headeren. Du vil også kunne se en kolonne i tabellvisningen på issue boardet, og du vil kunne filtrere etter disse feltene.

## 1. **Ny valgmeny**

Administratorer vil kunne finne handlingsknapper øverst til høyre på innholdssiden for et egendefinert felt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/01-new-item-action-menu.png)

_Nytt egendefinert felt_ Klikk på den grønne plusskjappen øverst til høyre eller velg Nytt egendefinert felt i valgmenyen for å lage et [nytt egendefinert felt](https://support.catenda.com/en/articles/8445575-creating-a-custom-field)

_Arkiver_ Åpne valgmenyen med de tre prikkene øverst til høyre for å finne Arkiver-handlingen øverst til høyre. Det er kun mulig å arkivere et egendefinert felt. Det er ikke mulig å slette et egendefinert felt.

I stedet for å slette kan egendefinerte felt kun arkiveres. Et arkivert egendefinert felt vil forsvinne fra

## 2. **Egendefinert datofelt**

Et datofelt viser en dato i den gregorianske kalenderen. Datoen vises i formatet som er konfigurert på kontosiden for hvert medlem.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/02-date-custom-field.png)

Dette feltet kan brukes til å registrere datoen for originalt innhold hvis informasjonen ble opprettet en tid før den ble sendt til Catenda, og metadataene er kjente men ikke reflektert i dokumentmetadataene eller tittelen.

## 3. **Egendefinert felt med desimaltall**

Et desimalfelt viser opptil 6 desimaler etter kommaet. Hvis det er mer enn 6 desimaler etter kommaet, brukes vitenskapelig notasjon.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/03-decimal-number-custom-field.png)

Dette feltet brukes ofte til å registrere beløp som materialkostnad eller budsjettkonsekvenser.

_Grense_ Egendefinerte desimalfelt har en grense for verdier mellom `-0.000000001` til `2147483647` per egendefinert heltallsfelt som fylles ut. Egendefinerte desimalfelt har en grense på 17 tall kombinert før og etter desimalskilletegnet. For større tall kan vitenskapelig notasjon brukes. For eksempel `1.0991234567890123e+22` Antall tegn kan begrenses videre med en navnekonvensjon for bruk i dokumentopplastingsnavn.

## 4. **Egendefinert felt med nedtrekksliste**

For å gå til den egendefinerte feltesiden for et nedtrekksfelt, klikker du på et nedtrekksfelt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/04-dropdown-custom-field.png)

Når et egendefinert nedtrekksfelt først opprettes, blir du automatisk tatt til denne siden. En egendefinert nedtrekksfeltside kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/05-dropdown-custom-field.png)

### 4.1 **Tittel og beskrivelse**

Administratorer vil kunne endre tittelen og beskrivelsen av feltet ved å klikke på blyanten.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/06-title-and-description.png)

### 4.2 **Aktive og deaktiverte faner**

Under beskrivelsen er Aktiv-fanen aktivert som standard. Klikk på den deaktiverte fanen for å vise nedtrekksverdier som tidligere har blitt deaktivert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/07-active-and-disabled-tabs.png)

_Gjenopprett_ Bruk gjenopprettingshandlingen for å gjenopprette en tidligere deaktivert nedtrekksverdi

> **Merknad:** Hver verdi i listen over aktive verdier må ha et unikt navn, så kontroller at navnet ikke allerede er i bruk når du gjenoppretter en verdi.

### 4.3 **Nedtrekksalternativer** - Aktiv liste

I den aktive listen vil du kunne finne nedtrekksalternativene som er for tiden aktive.

_Anker_ Administratorer vil kunne konfigurere rekkefølgen på alternativene ved å dra på ankeret i kolonnen lengst til venstre.

_Navn_ Her vil brukere se navn og et nedtrekksalternativ. Hvis det egendefinerte nedtrekksfelt har blitt [lagt til på en saksliste](https://support.catenda.com/en/articles/6563368-custom-fields-in-a-topic-board), vil du se dette navnet som et alternativ i listen. Et navn kan kun tildeles ett alternativ.

_Kode_ Her vil brukere se koden for et nedtrekksalternativ. Koden brukes til å [identifisere en blokk med en navnekonvensjon](https://support.catenda.com/en/articles/7869240-how-to-use-custom-fields-in-naming-convention). En kode kan kun tildeles ett alternativ.

_Rediger og deaktiver_ Administratorer vil kunne redigere navnet på et alternativ etter at det har blitt opprettet. Hvis feltet ikke allerede har en kode, er det mulig å legge til en kode. Etter redigering klikker du lagre eller avbryt for å bekrefte.

Administratorer vil kunne deaktivere alternativer ved å klikke på deaktiver og deretter klikke på bekreft. Deaktivering er lignende som sletting ettersom alternativet vil forsvinne overalt på Catenda hub, men kan senere gjenopprettes fra listen over deaktiverte alternativer.

Etter at en kode er lagt til, er det ikke lenger mulig å redigere koden. Hvis du ønsker å bruke en annen kode, kan du deaktivere alternativet og opprette et nytt alternativ.

### 4.4 **Nedtrekksalternativer -** Deaktivert liste

Her vil du kunne finne alle alternativene som for tiden er deaktiverte. Administratorer vil kunne klikke på gjenopprett for å gjenopprette noen av de deaktiverte alternativene.

### 4.5 **Legge til et alternativ**

Etter opprettelse vil et egendefinert nedtrekksfelt ikke ha noen alternativer ennå. Administratorer vil kunne legge til alternativer ved å klikke på knappen "legg til alternativer" nederst til venstre

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/08-adding-an-option.png)

Etter å ha klikket på "legg til alternativer" vil du se følgende dialog:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/09-adding-an-option.png)

_Navn_ Her kan du legge til et navn og en kode for hvert nedtrekksalternativ.

_Kode_ Koden brukes til å [identifisere en blokk med en navnekonvensjon](https://support.catenda.com/en/articles/7869240-how-to-use-custom-fields-in-naming-convention). Kode er en unik verdi som du kan angi på en gjenstand. Dette betyr at du ikke kan legge til den samme koden to ganger.

_Navn og kode feilsøking_ Klikk [her](https://support.catenda.com/en/articles/13750419-custom-field-content-troubleshooting) for å lese mer hvis du har problemer med navn og kode.

### 4.6 **Legge til flere alternativer**

I et nedtrekksfelt ønsker du ofte å legge til mer enn ett alternativ. Hvis du legger til et navn og klikker på send, må du klikke på "Legg til alternativer" hver gang du ønsker å legge til et alternativ, noe som kan være kjedelig og tidkrevende. Det finnes derfor flere måter du raskt kan legge til alternativer på.

_Hold åpen ved sending_ For å fortsette å legge til alternativ etter alternativ kan du merke av "Hold åpen ved sending"-knappen. Hvis denne knappen er merket, vil du kunne legge til navnet på det neste alternativet umiddelbart etter å ha sendt det forrige alternativet, slik at du ikke trenger å klikke på "Legg til alternativer" hele tiden.

_Legg til flere alternativer_ Hvis du allerede har dine alternativer forberedt utenfor Catenda, kan du lime dem inn på en god måte ved å klikke på "Legg til flere alternativer"-knappen. Når du klikker denne knappen, vil dialogen endres, og du vil kunne lime inn en streng. Hvis Catenda kan tolke stringen riktig, vil navnene og kodene for dine limte alternativer bli gjenkjent, og du vil kunne sende dem alle på en gang.

_Opprette en limstreng_

- Excel kopier lim

En enkel måte å opprette en limstreng på er å kopiere rader og kolonner fra et redigeringsprogram for tabeller som Excel. Hvis du legger til navnene dine i første rad og eventuelt kodene dine i andre rad, kan du kopiere dem og lime dem inn i dialogen for liming. Navnene og kodene dine vil da automatisk formateres riktig.

- Kommaseparert streng

For å opprette en streng som blir til et sett med alternativer, skiller du alternativene dine med et "komma" `,` eller en "ny linje" `\n`. For eksempel vil "Electrical,Architecture" bli til alternativene `Electrical` og `Architecture`

- Navn og koder i en streng

Eventuelt, hvis du ønsker å legge det til, kan du legge til en kode til alternativet ditt ved å separere det med en "tab", "kolon" `:`, "semikolon" `;` og "pipe" `|`. For eksempel vil "Electrical:el,Architecture:arc" bli til alternativet `Electrical` med koden `el` og alternativet `Architecture` med koden `arc`.

Etter å ha limt strengen inn i limefeltet, kan du klikke et sted på siden for å se om formateringen var vellykket.

> **Merknad:** Hvis nedtrekksfelt legges til på en saksliste, er det viktig hvor mange felt du legger til, og om feltet ditt er obligatorisk. Hvis det er opptil 10 felt, kan du filtrere etter hvert av feltene. Hvis feltet ikke er obligatorisk, kan du filtrere på om feltet er satt eller ikke.

_Grense_ Selv om det er mulig å legge til opptil 450 alternativer samtidig, anbefales det å legge til opptil 100 alternativer av gangen.

### 4.7 **Grense**

Egendefinerte nedtrekksfelt har en grense for valg av ett alternativ fra opptil 1000 alternativer per egendefinert nedtrekksfelt.

## 5. **Egendefinert felt med heltall**

Et egendefinert heltallsfelt viser hele tall.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/10-integer-custom-field.png)

Bare hele tall er tillatt med dette feltet, ingen desimaler. Dette brukes ofte til å registrere forekomster.

_Grense_ Egendefinerte heltallsfelt har en grense for verdier mellom `-2147483648` til `2147483647` per egendefinert heltallsfelt som fylles ut. Antall tegn kan begrenses videre med en navnekonvensjon for bruk i dokumentopplastingsnavn. For større tall kan et desimalfelt brukes med vitenskapelig notasjon.

## 6. **Egendefinert felt med tekst**

Et egendefinert tekstfelt viser en tekststreng.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/dyr0xwtr/11-text-custom-field.png)

Teksten vises på en enkelt linje. Et godt eksempel på et tekstfelt er et felt kalt kommentar som kan fylles ut og ses fra tabellvisningen. I navnekonvensjoner brukes det ofte til å begrense hvor mange tegn som er tillatt for et felt i en dokumenttittel.

_Grense_ Egendefinerte tekstfelt har en maksimal grense på 200 tegn per egendefinert tekstfelt som fylles ut. Antall tegn kan begrenses videre med en navnekonvensjon for bruk i dokumentopplastingsnavn.
