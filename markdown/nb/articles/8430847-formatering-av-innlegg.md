# Verktøy for formatering av innlegg

> Hvordan felt hvor innlegg kan skrives kan formateres

De samme formateringsreglene gjelder for ulike innlegg rundt Catenda Hub. Innlegg kan inkludere saksbeskrivelser, kommentarer, gjennomgangsbeskrivelser og gjennomgangskommentarer. Variasjoner kan forekomme med ulik tilgang til hvem som kan redigere innlegget. Catenda bruker markdown for å formatere tekst. Dette betyr at visse tegn før og etter setninger vil påvirke tekstens stil. Slik kan en saksoverskrift og beskrivelse se ut etter innsending:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/01-intro.png)

## 1. Tilgjengelighet for formatering

Det er ofte mulig å se at innsendte felt kan formateres ved verktøykassen som vises under feltet når feltet redigeres.

> **Merk:** Zoom ut nok med leserens zoomskala for å se alle verktøy.

Formatering er tilgjengelig i følgende felt:

### 1.1 **Saksbeskrivelse og kommentar**

Rediger beskrivelsen eller kommentaren til en eksisterende sak eller når du sender inn en ny sak for å se verktøykassen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/02-topic-description-and-comment.png)

### 1.2 **Gjennomgangsbeskrivelse**

Selv om verktøykassen ikke vises i beskrivelsen av den nye gjennomgangsforespørselen, blir formateringen brukt på denne beskrivelsen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/03-approval-request-description.png)

> **Merk:** Dette feltet kan ikke redigeres etter at gjennomgangsforespørselen er sendt inn.

### 1.3 Beskrivelse av saksliste

Selv om verktøykassen vises i den nye beskrivelsen av sakslisten, er det viktig å merke seg at beskrivelsen ikke formateres når listen sendes inn.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/04-topic-board-description.png)

## 2. **Vedlegg til sakskommentar**

I sakskommentarer er et vedleggverktøy synlig. Klikk på +-knappen i en sak for å legge til et vedlegg.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/05-topic-comment-attachment.png)

Klikk [her](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_0e3c0059ae) for å lese mer om kommentarvedlegg.

## 3. **Formater tekst**

Følgende metoder lar deg formatere teksten din:

### 3.1 **Fet, kursiv, gjennomstreket**

Fet, kursiv og gjennomstreket stil kan gjøres hvor som helst på en linje og fungerer godt sammen med annen stil som må være på starten av en linje.

<img alt="**Dette vil være fet** __Dette vil også være fet__ *Dette vil være kursiv* _Dette vil også være kursiv_ **Dette vil være fet _kombinert med kursiv_** ~~Denne teksten vil være gjennomstryket~~" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-b49c2f10b2de.png" width="290"/>   \<->   <img alt="Dette vil være fet​Dette vil også være fet​Dette vil være kursiv​Dette vil også være kursiv​Dette vil være fet kombinert med kursivDenne teksten vil være gjennomstryket" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-ea38fb93f8ee.png" width="290"/>

### 3.2 **Overskrifter**

Overskriftsverktøyet bruker hashtag/pundtegn på starten av linjen. Det støttes 5 nivåer av overskrifter: Formateringen som overskriften får, avhenger av hvor mange hashtag/pundtegn (`#`) som er på starten av linjen.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-c21079ec7efb.png" width="290"/>   \<->   <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-557784a5d702.png" width="290"/>

### 3.3 **Lenker**

Lenkestil kan gjøres hvor som helst på en linje og fungerer godt sammen med annen stil som må være på starten av en linje. Lenker i beskrivelser vil være grønne og understreket. Teksten deres kan være annerledes enn nettadressen som lenken peker til. Nettadresser vil automatisk bli gjort om til klikkbare lenker

```
https://hub.catenda.com
```

blir [https://hub.catenda.com](https://hub.catenda.com) og

```
[Catenda Hub](https://hub.catenda.com)
```

blir: [Catenda Hub](https://hub.catenda.com)

> **Merk:** Vær forsiktig når du klikker på lenker da selv om teksten [fra parentesene] kan vise en lenke, kan den faktiske lenken (fra parentesene) være annerledes. Det anbefales å holde markøren over en lenke og se hvor nettleseren vil omdirigere til før du klikker på en lenke.

### 3.4 **Forhindre formatering**

Ved å pakke ord i tegn som ikke er bokstaver eller tall, kan du få dem til å se annerledes ut. Dette er ikke alltid ønsket. Hvis du setter en `\` foran slike tegn, vil `\` forsvinne. Enhver formatering som ville ha blitt brukt for disse tegnene, vil da slutte å fungere. Hvis du setter en `\` på en tom linje som ikke er del av en [liste](#h_6da4949f8c), vil resultatet fortsatt være en tom linje.

## 4. **Strukturer tekst og legg til struktur**

Følgende metoder lar deg forbedre teksten ved å strukturere den og legge til struktur:

### 4.1 **Bilder**

Bilder i beskrivelser kan ha en lenke knyttet til seg. For å bygge inn bilder kan du bruke denne syntaksen

```
![text](https://bimsync.com/img/favicon/dark-mode/favicon-32x32.png)
```

for å få dette bildet med ordet tekst bak det.

![tekst](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/06-images.png)

For at bildet skal vises riktig, må Catenda ha tilgang til lenken som er gitt.

> **Merk:** \+ Bildet kan legges til en beskrivelse \+ Bildet kan blandes med tekst slik at du kan ha tekst både før og etter bildet i samme kommentarer eller beskrivelse. \+ Bilder som disse kan kombineres med tabeller og lister. Du kan for eksempel legge til et hakemerke-bilde midt i en setning/tabell i stedet for avkryssingsboksen som bare fungerer på starten av en setning \- Du kan ikke garantere at lenken til bildet forblir tilgjengelig i fremtiden.

_Få en Catenda-bildedokumentlenke_ Hvis du høyreklikker på [nedlastingsknappen etter å ha valgt et dokument](https://support.catenda.com/en/articles/4670288-actions-in-the-document-structure#h_133e2bcc57) eller høyreklikker på [nedlast siste revisjonsknapp etter å ha åpnet et dokument](https://support.catenda.com/en/articles/9323521-actions-in-a-document), kan du kopiere nedlastingslenken til dokumentet. Hvis du bruker denne lenken i saken din som ovenfor, vil du kunne bruke Catenda-dokumenter i saker.

> **Merk:** \+ Hvis du legger til en lenke til et Catenda-bildedokument, kan du legge til bilder som bare vises på Catenda og som ikke er tilgjengelige på andre plattformer som saken kan utveksles med. \+ Ved å legge til lenker til et Catenda-bildedokument kan bare personer med tilgang til dokumentet se bildet. \- Hvis du legger til en lenke til et Catenda-bildedokument, vil det ikke være synlig på andre plattformer som saken kan ha blitt synkronisert med, og for personer som ikke har tilgang til dokumentet.

### 4.2 **Lister**

_Uordnede lister_ Start en uordnet liste med en tom linje over den, deretter enten bindestrek (`-`), plusstegn (`+`) eller asterisk (`*`) fulgt av mellomrom. Sett inn 4 mellomrom eller et tabulatortegn på starten av linjen for å opprette en underliste.

```
 - Første element - Andre element     - Sett inn 4 mellomrom på starten av linjen for å opprette en underliste.
```

Eller

```
 + Første element + Andre element     + Sett inn 4 mellomrom på starten av linjen for å opprette en underliste.
```

Eller

```
 * Første element * Andre element     * Sett inn 4 mellomrom på starten av linjen for å opprette en underliste.
```

Vil alle bli til dette:

- Første element
- Andre element
  - Sett inn 4 mellomrom på starten av linjen for å opprette en underliste.

> **Merk:** For at en uordnet liste skal formateres riktig, må det være en tom linje over listen.

_Ordnede lister_ Start en ordnet liste med en tom linje over den, et tall, en periode og mellomrom (`1. `) Det tallet som er foran, spiller ingen rolle, bare at det er et tall etterfulgt av en periode. Sett inn 4 mellomrom eller et tabulatortegn på starten av linjen for å opprette en underliste.

```
1. element en 2. element to 3. element tre     4. element fire
```

Eller

```
1. element en 1. element to 1. element tre     1. element fire
```

Eller

```
1. element en 10. element to 1. element tre     1000. element fire
```

Vil alle bli til dette:

1. element en
1. element to
1. element tre

1. Element fire

> **Merk:** For at en ordnet liste skal formateres riktig, må det være en tom linje over listen.

Tallet du starter med, påvirker ikke hvor nummereringen begynner

```
23. tjuetreog 1. tjuefire 1. tjuefem     1. tjueseks
```

Blir til:

1. tjuetreog
1. tjuefire
1. tjuefem

1. tjueseks

Hvis du ønsker å tilbakestille nummereringen og starte fra en igjen på en annen liste innenfor samme innlegg, kan du legge en tom eller en [skillelinje](#h_3a36cfbc61) mellom dem.

For å [sikre at listen ikke blir formatert](#h_2ec17c688b) slik at du kan bruke din egen nummerering: Plasser et tegn på linjen over listen. Et godt valg er `\` fordi det vil forsvinne.

```
\23. tjuetreog 24. tjuefire 25. tjuefem     26. tjueseks
```

Plasser en omvendt skråstrek (`\`) før perioden (`.`):

```
23\. tjuetreog 24\. tjuefire 25\. tjuefem     26\. tjueseks
```

Vil alle bli til:

23\. tjuetreog 24\. tjuefire 25\. tjuefem 26\. tjueseks

### 4.3 **Skilleliner**

Tre bindestreker `---` eller flere på sin egen linje vil lage en skillelinje:

---

### 4.4 **Sjekklister**

Disse kan merkes av i beskrivelsen av en sak. _Tilgang påkrevd:_ Skrivetilgang til sakslisten.

```
- [ ] første element - [x] andre element     - [ ] undergruppelement
```

Blir til dette:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/07-checklists.png)

Klikk [her](https://support.catenda.com/en/articles/5036461-check-lists-within-issues) for å se en rask video om hvordan sjekklister kan brukes i prosjektet. Hvis du skriver` - [ ]` eller `- [x]` vil boksen fortsatt vises merket av eller ikke merket av når kommentaren sendes inn eller lagres etter redigering.

_Avkryssingsbokser i kommentarer_ I kommentarer kan avkryssingsbokser bare merkes av gjennom formatering. Avkryssingsbokser i kommentarer kan ikke klikkes for å bli merket av. _Tilgang påkrevd -_ Kommentarens skaper har tilgang til redigering av den opprettede kommentaren

### 4.5 **Tabeller**

Tekst i beskrivelser kan ordnes i tabeller.

```
|            | Windows            ||             | |            | Type 1   | Type 2   | Sum total   | |----------- | -------- | -------- | ----------- | | **Price**  | 500,-    | 400,-    |             | | **Amount** | 10       | 4        |             | | **Sum**    | 5 000,-  | 1 600,-  | **6 600,-** |
```

vil resultere i dette

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right">Vin</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>dues</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Type 1</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Type 2</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Sum totalt</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Pris</b></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>500,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>400,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Antall</b></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>10</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>4</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Sum</b></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>5 000,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>1 600,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>6 600,-</b></p></td></tr></tbody></table></div>

### 4.6 **Kodeblokkker**

Du kan sette inn kodelinjer slik: To `` ` `` rundt tekst vil se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/08-code-blocks.png)

Tre backticks ` ``` ` ovenfor og nedenfor litt tekst vil se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/09-code-blocks.png)

Det er ikke mulig å legge til tabeller i kodeblokkker

### 4.7 **Markdown-dialekt**

Hvis du vil vite mer om hvordan tekst formateres i kommentarer og beskrivelser bruker vi markdown-dialekten "flexmark" til å formatere denne teksten. Finn ut mer om flexmark på deres [github-side](https://github.com/vsch/flexmark-java).

## 5. **@ Nevnte medlemmer og teams**

Klikk på `@`-verktøyet eller skriv `@` i en beskrivelse eller kommentar for å nevne et medlem. Etter å ha skrevet `@` vises en nedtrekksliste over medlemmer og teams.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/10-mentioned-members-and-teams.png)

Søk gjennom listen ved å begynne å skrive e-postadressen, medlemsnavnet eller teamnavnet. Gå opp og ned i listen med piltastene og klikk eller trykk enter for å velge et medlem eller team. For at et medlem eller team skal vises i denne listen, må medlemmet eller teamet minst ha lesetilgang til sakslisten. Etter å ha valgt et medlem eller team i listen, vil `@` få ekstra tekst som kan se slik ut:

`@[<e-postadresse for medlem>]` eller `@[<teamnavn>]`

### 5.1 **Lagre eller sende inn en nevning i en sak**

Når beskrivelsen lagres eller kommentaren sendes inn, mottar relaterte medlemmer med tilgang til sakslisten et varsel. Hvis medlemmets e-postadresse eller teamnavnet er kjent, kan det også skrives manuelt, men hvis de ikke er del av sakslisten, vil de relaterte medlemmene ikke bli varslet om at de er nevnt.

_Varsel ved medlemsnevning_ Medlemmer med tilgang til sakslisten som er nevnt, mottar et varsel om at de er nevnt i en sak.

_Varsel ved teamnevning_ Medlemmer med tilgang til sakslisten som er del av et team som er nevnt, mottar et varsel om at et team de er del av, er nevnt i en sak.

_Varsler om fremtidige saksbegivenheter_ Medlemmer av teams som er nevnt i saksbeskrivelser og kommentarer mottar bare det ene varselet ved den lagrede beskrivelsen eller sendt kommentar.

I tillegg til varselet om at de er nevnt, blir medlemmer som er nevnt i innlegg automatisk satt til å [følge](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) saken og vil få varsler om saksbegivenheter som nye kommentarer og statusendringer. Dette er en fin måte å sikre at mer enn bare [tilordnet](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9) og [forespørrer](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7) få varsler om fremtidige endringer i saken. Hvis et medlem ikke lenger ønsker å følge saken, må de manuelt slutte å følge den.

### 5.2 **Nevning i innlegg**

Nevninger i innlegg kan identifiseres ved at de har grønn tekstfarge.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/11-mention-in-post.png)

I bakgrunnen lagres den unike ID-en til det nevnte prosjektdeltakeren. Det er deltakerens navn som vises i denne grønne teksten. Selv om medlemmet eller teamet endrer navn, vil de forbli nevnt i innlegget, men under sitt nye navn.

Nevnte medlemmer har en klikkbar lenke som leder til [medlemssiden](https://support.catenda.com/en/articles/8228836-member-page) til det medlemmet. Nevnte teams har en klikkbar lenke som leder til [teamsiden](https://support.catenda.com/en/articles/7891755-team-page) til det teamet.

_Ikke-eksisterende medlem_ Hvis det ikke er noe medlem i prosjektet som har e-postadressen som er nevnt, ser innlegget slik ut i stedet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/12-mention-in-post.png)

Dette kan enten være fordi e-posten var formatert feil eller fordi medlemmet ikke lenger er del av prosjektet. Hvis et medlem med denne e-postadressen blir del av prosjektet i fremtiden, endres innlegget til å vise medlemmets navn.

_Ikke-eksisterende team_ Hvis et team har blitt fjernet fra prosjektet og et nytt team opprettes, vil dette nye teamet ikke bli nevnt. For å nevne det nye teamet må innlegget sendes inn på nytt.

## 6. **# Merkede saker**

Klikk på `#`-verktøyet eller skriv `#` i en beskrivelse eller kommentar for å merke en sak. Etter å ha skrevet `#` vises en nedtrekksliste over saker fra alle sakslister.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/13-tagged-topics.png)

Søk gjennom listen ved å begynne å skrive tittelen eller saknummeret. Gå opp og ned i listen med piltastene og klikk eller trykk enter for å velge en sak. For at en sak skal vises i denne listen, må medlemmet som merker, ha tilgang til listen som saken befinner seg i. Etter å ha valgt en sak i listen, vil `#` få ekstra tekst som kan se slik ut:

`#[<saknummer>]`

### 6.1 **Lagre eller sende inn en merket sak**

Når beskrivelsen lagres eller kommentaren sendes inn, opprettes en sakrelasjon. Den merkede saken legges deretter til listen over [linkede saker](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) i [høyre meny](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) til saken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/14-saving-or-submitting-a-tagged-topic.png)

I tillegg til saken der en annen sak ble merket, mottar den merkede saken selv en lenke tilbake til saken der den ble lagt til listen over [linkede saker](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) i [høyre meny](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/15-saving-or-submitting-a-tagged-topic.png)

Saklenken kan senere fjernes fra enten saken med den merkede saken i beskrivelsen eller fra saken som ble merket ved å gå til hver sak og redigere listen over [linkede saker](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) i [høyre meny](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue).

### 6.2 **Merket sak i innlegg**

Merkede saker kan identifiseres ved først å ha en sirkel med fargen til gjeldende status for den merkede saken sammen med statusnavnet. Etter det vises saktittelen etterfulgt av saknummeret.

Sammen med avkryssingsboksene, merkede saker som er lukket, teller mot fremgangen i fremdriftslinjen som vises mot toppen, mens merkede saker som er åpne, teller mot de totale elementene som fremgangen beregnes mot.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/16-tagged-topic-in-post.png)

Merkede saker har en klikkbar lenke som åpner den merkede saken i dens saksliste.
