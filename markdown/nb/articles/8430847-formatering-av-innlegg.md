# Verktøy for formatering av innlegg

> Hvordan felt der innlegg kan gjøres kan formateres

De samme formateringsreglene gjelder for de ulike innleggene rundt Catenda Hub. Innlegg kan omfatte emnebeskrivelser, kommentarer godkjenningseskrivelser og godkjenningskommentarer. Variasjoner kan oppstå med de ulike tilgangene til hvem som kan redigere innlegget. Catenda bruker markdown til å formatere tekst. Dette betyr at visse tegn før og etter setninger vil påvirke stilen på teksten. Slik kan en emnekopptekst og beskrivelse se ut etter at de er sendt inn:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/01-intro.png)

Følgende emner er beskrevet i denne artikkelen:

## 1. Formateringstilgjengelighet

Det er ofte mulig å se at sendte felt kan formateres ved verktøykassen som vises under feltet når feltet redigeres.

> **Merk:** Zoom langt nok ut med nettleserens zoommål for å se alle verktøy.

Formatering er tilgjengelig i følgende felt:

Følgende emner er beskrevet i denne delen:

### 1.1 **Emneeskrivelse og kommentar**

Rediger beskrivelsen eller kommentaren til et eksisterende emne eller når du sender inn et nytt emne for å se verktøykassen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/02-topic-description-and-comment.png)

### 1.2 **Godkjennelsesforespørsel-beskrivelse**

Selv om verktøykassen ikke vises i beskrivelsen av den nye godkjenningforespørsel-dialogen, blir formatering brukt på denne beskrivelsen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/03-approval-request-description.png)

> **Merk:** Dette feltet kan ikke redigeres etter innsending av godkjenningsforespørselen.

### 1.3 Emnebrettbeskrivelse

Selv om verktøykassen vises i den nye emnebrettbeskrivelsen, er det viktig å merke seg at beskrivelsen ikke formateres når brettet sendes inn.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/04-topic-board-description.png)

## 2. **Emnekommentarvedlegg**

I emnekommentarer er et vedleggsverktøy synlig. Klikk på +-knappen i et emne for å legge til et vedlegg.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/05-topic-comment-attachment.png)

Klikk [her](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_0e3c0059ae) for å lese mer om kommentarvedlegg.

## 3. **Stilisering av tekst**

Følgende metoder lar deg stilisere teksten din:

Følgende emner er beskrevet i denne delen:

### 3.1 **Fet, kursiv, gjennomstreking**

Fet, kursiv og gjennomstreking-stil kan gjøres hvor som helst på en linje og fungerer godt sammen med annen stil som må være i begynnelsen av en linje.

<img alt="**This will be bold** __This will also be bold__ *This will be italics* _This will also be italics_ **This will be bold _combined with italics_** ~~This text will be struck through~~" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-b49c2f10b2de.png" width="290"/>   \<->   <img alt="This will be bold​This will also be bold​This will be italics​This will also be italics​This will be bold combined with italicsThis text will be struck through" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-ea38fb93f8ee.png" width="290"/>

### 3.2 **Overskrifter**

Overskriftsverktøyet bruker hashmerker/pundtegn i begynnelsen av linjen. Det er 5 nivåer av overskrifter som støttes: Formateringen som overskriften mottar er avhengig av antallet hashmerker/pundtegn (`#`) i begynnelsen av linjen.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-c21079ec7efb.png" width="290"/>   \<->   <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-557784a5d702.png" width="290"/>

### 3.3 **Lenker**

Lenkestil kan gjøres hvor som helst på en linje og fungerer godt sammen med annen stil som må være i begynnelsen av en linje. Lenker i beskrivelser vil være grønne og understreket. Teksten deres kan være forskjellig fra URL-en som lenken peker til. URL-er vil automatisk bli gjort om til klikkbare lenker

```
https://hub.catenda.com
```

vil bli [https://hub.catenda.com](https://hub.catenda.com) og

```
[Catenda Hub](https://hub.catenda.com)
```

vil bli: [Catenda Hub](https://hub.catenda.com)

> **Merk:** Vær forsiktig når du klikker på lenker fordi selv om teksten [fra parentesene] kan vise én lenke, kan den faktiske lenken (fra parentesene) være annerledes. Det anbefales å holde musepekeren over en lenke og se hvor nettleseren vil omdirigere til før du klikker på en lenke.

### 3.4 **Forhindring av formatering**

Ved å pakke ord i tegn som ikke er bokstaver eller tall, kan du få dem til å se annerledes ut. Dette er ikke alltid ønsket. Hvis du setter en `\` foran slik et tegn, vil `\` forsvinne. All formatering som ville blitt brukt på disse tegnene vil da slutte å fungere. Hvis du setter en `\` på en tom linje som ikke er del av en [liste](#lists) vil resultatet fortsatt være en tom linje.

## 4. **Dele opp tekst og legge til struktur**

Følgende metoder lar deg forbedre teksten din ved å dele den opp og legge til struktur:

Følgende emner er beskrevet i denne delen:

### 4.1 **Bilder**

Bilder i beskrivelser kan ha en lenke knyttet til seg. For å bygge inn bilder kan du bruke denne syntaksen

```
![text](https://bimsync.com/img/favicon/dark-mode/favicon-32x32.png)
```

for å få dette bildet med ordet tekst bak det.

![text](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/06-images.png)

For at bildet skal vises riktig, må Catenda ha tilgang til lenken som er gitt.

> **Merk:** \+ Bildet kan legges til en beskrivelse \+ Bildet kan blandes med tekst slik at du kan ha tekst både før og etter bildet i de samme kommentarene eller beskrivelsen. \+ Bilder som disse kan kombineres med tabeller og lister. For eksempel kan du legge til et hakkmerke-bilde i midten av en setning/tabell i stedet for avmerkingsboksen som bare fungerer i begynnelsen av en setning \- Du kan ikke garantere at lenken til bildet forblir tilgjengelig i fremtiden.

_Få en Catenda-bildedokumentlenke_ Hvis du høyreklikker på [nedlastingshandlingsknappen etter å ha valgt et dokument](https://support.catenda.com/en/articles/4670288-actions-in-the-document-structure#h_133e2bcc57) eller høyreklikker på [nedlastingen seneste revisjonshandlingsknappen etter å ha åpnet et dokument](https://support.catenda.com/en/articles/9323521-actions-in-a-document) kan du kopiere nedlastingslenken til dokumentet. Hvis du bruker denne lenken i emnet ditt som ovenfor, kan du bruke Catenda-dokumenter i emner.

> **Merk:** \+ Hvis du legger til en lenke til et Catenda-bildedokument, kan du legge til bilder som bare vises på Catenda og ikke er tilgjengelige på andre plattformer som emnet kan utveksles med. \+ Ved å legge til lenker til et Catenda-bildedokument kan bare personer med tilgang til dokumentet se bildet. \- Hvis du legger til en lenke til et Catenda-bildedokument, vil det ikke være synlig på andre plattformer som emnet kan ha blitt synkronisert med og for personer som ikke har tilgang til dokumentet.

### 4.2 **Lister**

_Uordnede lister_ Start en uordnet liste med en blank linje over den, deretter enten bindestrek (`-`), pluss (`+`) eller asterisk (`*`) fulgt av mellomrom. Sett inn 4 mellomrom eller et tabulatormelllomrom i begynnelsen av linjen for å opprette en underliste.

```
 - Første element - Andre element     - Sett inn 4 mellomrom i begynnelsen av linjen for å opprette en underliste.
```

Eller

```
 + Første element + Andre element     + Sett inn 4 mellomrom i begynnelsen av linjen for å opprette en underliste.
```

Eller

```
 * Første element * Andre element     * Sett inn 4 mellomrom i begynnelsen av linjen for å opprette en underliste.
```

Vil alle bli til dette:

- Første element
- Andre element
  - Sett inn 4 mellomrom i begynnelsen av linjen for å opprette en underliste.

> **Merk:** For at en uordnet liste skal formateres riktig, må det være  en blank ny linje på linjen over listen.

_Ordnede lister_ Start en ordnet liste med en blank linje over den, et nummer, en periode og mellomrom (`1. `) Hva nummeret foran er, spiller ingen rolle, bare at det er et nummer fulgt av en periode. Sett inn 4 mellomrom eller et tabulatormelllomrom i begynnelsen av linjen for å opprette en underliste.

```
1. punkt en 2. punkt to 3. punkt tre     4. punkt fire
```

Eller

```
1. punkt en 1. punkt to 1. punkt tre     1. punkt fire
```

Eller

```
1. punkt en 10. punkt to 1. punkt tre     1000. punkt fire
```

Vil alle bli til dette:

1. punkt en
2. punkt to
3. punkt tre

4. Punkt fire

> **Merk:** For at en ordnet liste skal formateres riktig, må det være  en blank ny linje på linjen over listen.

Nummeret du starter med påvirker ikke hvor nummereringen begynner

```
23. tjuetrettitre 1. tjuefiretid 1. tjuefem     1. tjueseks
```

Vil bli:

1. tjuetrettitre
2. tjuefiretid
3. tjuefem

4. tjueseks

Hvis du ønsker å tilbakestille nummereringen og starte fra en igjen på en andre liste innenfor det samme innlegget, kan du sette en tom eller en [skillelinje](#dividers) i mellom.

For å [sikre at listen ikke formateres](#preventing-formatting) slik at du kan bruke din egen nummerering: Sett et tegn på linjen over listen. Et godt valg er `\` fordi det vil forsvinne.

```
\23. tjuetrettitre 24. tjuefiretid 25. tjuefem     26. tjueseks
```

Sett en omvendt skråstrek (`\`) foran perioden (`.`):

```
23\. tjuetrettitre 24\. tjuefiretid 25\. tjuefem     26\. tjueseks
```

Vil alle bli til:

23\. tjuetrettitre 24\. tjuefiretid 25\. tjuefem 26\. tjueseks

### 4.3 **Skillelinjer**

Tre bindestrek `---` eller mer på sin egen linje vil opprette en skillelinje:

---

### 4.4 **Sjekklister**

Disse kan avmerkes i beskrivelsen av et emne. _Tilgang kreves:_ Skrivetilgang til emnebrettet.

```
- [ ] første punkt - [x] andre punkt     - [ ] underliste punkt
```

Vil bli til dette:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/07-checklists.png)

Klikk [her](https://support.catenda.com/en/articles/5036461-check-lists-within-issues) for å se en rask video om hvordan sjekklister kan brukes i prosjektet. Hvis du skriver ` - [ ]` eller `- [x]` vil boksen fortsatt vises uavmerket og avmerket når kommentaren sendes inn eller lagres etter redigering.

_Avmerkingsbokser i kommentarer_ I kommentarer kan avmerkingsbokser bare merkes av gjennom formatering. Avmerkingsbokser i kommentarer kan ikke klikkes for å bli merket. _Tilgang kreves -_ Kommentarskriveren har tilgang til redigering av den opprettede kommentaren

### 4.5 **Tabeller**

Tekst i beskrivelser kan organiseres i tabeller.

```
|            | Windows            ||             | |            | Type 1   | Type 2   | Sum total   | |----------- | -------- | -------- | ----------- | | **Price**  | 500,-    | 400,-    |             | | **Amount** | 10       | 4        |             | | **Sum**    | 5 000,-  | 1 600,-  | **6 600,-** |
```

vil resultere i dette

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p></p></td><td><p class="intercom-align-right">Win</p></td><td><p>dows</p></td><td><p></p></td></tr><tr><td><p></p></td><td><p>Type 1</p></td><td><p>Type 2</p></td><td><p>Sum total</p></td></tr><tr><td><p><b>Pris</b></p></td><td><p>500,-</p></td><td><p>400,-</p></td><td><p></p></td></tr><tr><td><p><b>Antall</b></p></td><td><p>10</p></td><td><p>4</p></td><td><p></p></td></tr><tr><td><p><b>Sum</b></p></td><td><p>5 000,-</p></td><td><p>1 600,-</p></td><td><p><b>6 600,-</b></p></td></tr></tbody></table></div>

### 4.6 **Kodeblokker**

Du kan sette inn enkeltlinjer med kode slik: To \`\`\` omgitt av tekst vil se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/08-code-blocks.png)

Tre tilbakeslash `\`\\`\`\` over og under en bit tekst vil se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/09-code-blocks.png)

Det er ikke mulig å legge til tabeller i kodeblokker

### 4.7 **Markdown-dialekt**

Hvis du gjerne vil vite mer om hvordan tekst formateres i kommentarer og beskrivelser, bruker vi markdown-dialekten "flexmark" til å formatere denne teksten. Finn ut mer om flexmark på deres [github-side](https://github.com/vsch/flexmark-java).

## 5. **@ Nevnte medlemmer og team**

Klikk på `@`-verktøyet eller skriv `@` i en beskrivelse eller kommentar for å nevne et medlem. Etter å ha skrevet `@` vises en rullegardinliste over medlemmer og team.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/10-mentioned-members-and-teams.png)

Søk gjennom listen ved å begynne å skrive e-posten, medlemmets navn eller teamets navn. Gå opp og ned i listen med piltastene og klikk eller trykk enter for å velge et medlem eller team. For at et medlem eller team skal vises i denne listen, må medlemmet eller teamet ha minst lese tilgang til emnebrettet. Etter å ha valgt et medlem eller team i listen, vil `@` få noe ekstra tekst som kan se ut slik:

`@[<e-postadresse for medlem>]` eller `@[<Teamnavn>]`

Følgende emner er beskrevet i denne delen:

### 5.1 **Lagring eller innsending av nevning i et emne**

Når beskrivelsen lagres eller kommentaren sendes inn, mottar relaterte medlemmer med tilgang til emnebrettet et varsel. Hvis medlemmets e-postadresse eller teamets navn er kjent, kan det også skrives manuelt, men hvis de ikke er del av emnebrettet, vil ikke de relaterte medlemmene bli varslet om at de er nevnt.

_Varsel ved nevning av medlem_ Medlemmer med tilgang til emnebrettet som er nevnt mottar et varsel om at de er nevnt i et emne.

_Varsel ved nevning av team_ Medlemmer med tilgang til emnebrettet som er del av et team som er nevnt, mottar et varsel om at et team de er del av er nevnt i et emne.

_Varsler om fremtidige emne-hendelser_ Medlemmer av team som er nevnt i emnebeskrivelser og kommentarer mottar bare det ene varselet ved den lagrede beskrivelsen eller den sendte kommentaren.

I tillegg til varselet om at de er nevnt, settes medlemmer som er nevnt i innlegg automatisk til å [følge](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) emnet og vil få varsler om emne-hendelser som nye kommentarer og statusendringer. Dette er en fin måte å sikre at ikke bare [assignee](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9) og [requestee](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7) får varsler om fremtidige endringer et emne. Hvis et medlem ikke lenger ønsker å følge emnet, må det manuelt slutte å følge det.

### 5.2 **Nevning i innlegg**

Nevninger i innlegg kan identifiseres ved å ha grønn tekstfarge.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/11-mention-in-post.png)

I bakgrunnen lagres den unike IDen til den nevnte prosjektdeltakeren. Det er navn på deltakeren som vises i denne grønne teksten. Selv om medlemmet eller teamet endrer navn, vil de fortsatt være nevnt i innlegget, men under sitt nye navn.

Nevnte medlemmer har en klikkbar lenke som direkter til [medlemsiden](https://support.catenda.com/en/articles/8228836-member-page) til det medlemmet. Nevnte team har en klikkbar lenke som direkter til [teamsiden](https://support.catenda.com/en/articles/7891755-team-page) til det teamet.

_Ikke-eksisterende medlem_ Hvis det ikke er noe medlem i prosjektet som har e-postadressen som er nevnt, ser innlegget slik ut i stedet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/12-mention-in-post.png)

Dette kan enten være fordi e-posten var formatert feil eller fordi medlemmet ikke lenger er del av prosjektet. Hvis et medlem med denne e-postadressen blir del av prosjektet i fremtiden, endres innlegget for å vise navnet på det medlemmet.

_Ikke-eksisterende team_ Hvis et team er fjernet fra prosjektet og et nytt team opprettes, vil ikke dette nye teamet bli nevnt. For å nevne det nye teamet må innlegget sendes inn på nytt.

## 6. **# Merkede emner**

Klikk på `#`-verktøyet eller skriv `#` i en beskrivelse eller kommentar for å merke et emne. Etter å ha skrevet `#` vises en rullegardinliste over emner fra alle emnebrett.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/13-tagged-topics.png)

Søk gjennom listen ved å begynne å skrive tittelen eller emnenummeret. Gå opp og ned i listen med piltastene og klikk eller trykk enter for å velge et emne. For at et emne skal vises i denne listen, må medlemmet som merker emnet ha tilgang til brettet som emnet befinner seg i. Etter å ha valgt et emne i listen, vil `#` få noe ekstra tekst som kan se ut slik:

`#[<emnenummer>]`

Følgende emner er beskrevet i denne delen:

### 6.1 **Lagring eller innsending av merket emne**

Når beskrivelsen lagres eller kommentaren sendes inn, opprettes en emnerelasjon. Det koblede emnet blir deretter lagt til listen over [koblede emner](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) i [høyre meny](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) av emnet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/14-saving-or-submitting-a-tagged-topic.png)

I tillegg til emnet der et annet emne ble merket, mottar det merkede emnet selv en lenke tilbake til emnet der det ble lagt til listen over [koblede emner](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) i [høyre meny](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/15-saving-or-submitting-a-tagged-topic.png)

Emnelenken kan senere fjernes fra enten emnet med det merkede emnet i beskrivelsen eller fra emnet som ble merket ved å gå til hvert emne og redigere listen over [koblede emner](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) i [høyre meny](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue).

### 6.2 **Merket emne i innlegg**

Merkede emner kan identifiseres ved først å ha en sirkel med fargen på den nåværende statusen til det merkede emnet sammen med navn på den statusen. Etter det vises emnetittelen etterfulgt av emnenummeret.

Sammen med avmerkingsboksene, merkede emner som er lukket, teller mot fremgangen i fremdriftslinjen som vises mot toppen, mens merkede emner som er åpne, teller mot totale elementer som fremdriften telles mot.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/16-tagged-topic-in-post.png)

Merkede emner har en klikkbar lenke som åpner det merkede emnet i sitt emnebrett.
