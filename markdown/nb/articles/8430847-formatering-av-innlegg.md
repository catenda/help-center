# Formatering av innlegg

De samme formateringsreglene gjeler for forskjellige typer innlegg rundt Catenda Hub.

Inlegg kan inneholde beskrivelser i saker, kommenterer godkjenningsbeskrivelser og godkjenningskommentarer. Varisasjoner kan gjelde med forskjellig tilgang for hvem som kan redigere innlegget.

Catenda bruker markdown for å formatere tekst.

Dette betyr at visse karakter før og etter setninger vil påvirke utformingen av teksten.

> **Note:** **Merk:** Mange av metodene krever en blank ny linje før den

I denne artikkelen vil du kunne finne informasjon om følgende temaer:

## 1. **Utforming av tekst**

Følgende metoder tillater deg å utforme din tekst i innlegg:

### 1.1 **Fet skrift, kursiv, gjennomstreking**

```
**Dette vil ha fet skrift** __Dette vil også ha fet skrift__ *Dette vil være i kursiv* _Dette vil også være i kursiv_ **Dette vil være i fet skrift _Kombinert med kursiv_** ~~Denne teksten vil være gjennomstreket~~
```

**Dette vil ha fet skrift** **Dette vil også ha fet skrift** _Dette vil være i kursiv_ _Dette vil også være i kursiv_ **Dette vil være i fet skrift _Kombinert med kursiv_** Denne teksten vil være streket gjennom

### 1.2 **Overskrifter**

`##` Før tekst vil lage en overskrift

### 1.3 **Lenker**

Lenker i beskerivelser vil være grønn og understreket.

Deres tekst kan være forskjellig fra urlen som lenken peker på.

Urler vil automatisk endres til klikkbare lenker

```
https://hub.catenda.com
```

vil bli

[https://hub.catenda.com](https://hub.catenda.com)

og

```
[Catenda Hub](https://hub.catenda.com)
```

vil bli:

[Catenda Hub](https://hub.catenda.com)

### 1.4 **Forhindring av formatering**

Ved å flette ord i ikke bokstav eller nummer teg kan deres utforming endres.

Dette er er ikke alltid ønsket.

Hvis du legger in en `\\` før et utformingskarakter vil `\\` forsvinne.

All utforming som burda ha vært gjeldende for disse karakter vil da slutte å fungere.

Hvis du legger en `\\` på en tom linje som ikke er del av en [liste](#h_9bc5734bac) vil resultatet fortsatt være en tom linje.

## 2. **Dele opp tekst og legge til struktur**

Følgende metoder lar deg forbedre teksten din ved å dele den opp og legge til struktur:

### 2.1 **Bilder**

Bilder i beskrivelser kan ha lenker koblet til de. For å legge bilder sammen med tekst kan denne syntaksen brukes

```
![tekst](https://bimsync.com/img/favicon/dark-mode/favicon-32x32.png)
```

for å få dette bildet med ordet tekst koblet til det.

![text](https://downloads.intercomcdn.com/i/o/areracg3/1211345313/723bbdb579d6cb4d624d6ab1bcd8/faviconV2.png?expires=1781092800&signature=2300b51195b1b224b546a3e77d552303c1f99fe72cef64d391058523ff748c17&req=dSImF8p6mIJeWvMW3nq%2Bgehp%2BeBcEphmItpXGG60XCqLXLBk4rIvJ8Xy7Fsc%0ALUgLvCD1%2BVShqkNoXIuB9DvTnpY%3D%0A)

For at bildet skal vises på riktig måte må Catenda ha tilgang til lenken som er lagt ved.

> **Note:** \+ Bildet kan legges til i beskrivelse \+ Bildet kan legges sammen med tekst som gjør at du kan ha tekst både før og etter bildet i samme kommentar eller beskrivelse. \+ Bilder som disse kan kombines med tabeller og lister. For eksempel kan du legge til et avhukings bilde i midten av setningen/tabellen fremfor formatterings avhukingsboksen som bare fungerer på starten av en setning. \- Du kan ikke garantere at lenken til bildet fortsetter å være tilgjengelig i fremtiden.

_Få tak i lenken til et bilde dokument i Catenda_ Hvis du høyre klikker på [nedlastings aksjonsknappen etter å ha selektert et dokument](https://support.catenda.com/en/articles/4670288-actions-in-the-document-structure#h_133e2bcc57) eller høyre klikker på [last ned siste revisjon aksjonsknappen etter å ha åpnet opp et dokument](https://support.catenda.com/en/articles/9323521-actions-in-a-document) kan du kopiere nedlastingslenken til dokumenet. Hvis du bruker denne lenken i din sak som over vil du kubbe bruke Catenda dokumenter i saker.

> **Note:** \+ Hvis du legger til en lenke til et Catenda bilde dokument kan du legge til bilder som bare vises på Catenda og ikke er tilgjengelige i andre plattform som saken kan være utvekslet med. \+ Ved legge til lenken til et Catenda bilde dokument vil bare brukere med tilgang til dokumentet kunne se bildet. \- Hvis du legger til lenken til et Catenda bilde dokument vil du ikke kunne vise bildet på andre plattform som saken kan være synkronisert med eller til andre brukere i prosjektet som ikke har tilgang til bildet.

### 2.2 **Lister**

**Uordnede lister**

Start en uordnet liste med en tom linje over den, så endten med en (`-`), plus (`+`), eller et stjernetegn (`\*`) etterfulgt av et mellomrom.

Legg inn 4 mellomrom eller et tab mellomrom på starten av linjen for å lage en underliste.

```
- Første element- Andre element     - Legg inn 4 mellomrom på starten av linjen for å lage en underliste.
```

Eller

```
+ Første element + Andre element     + Legg inn 4 mellomrom på starten av linjen for å lage en underliste.
```

Eller

```
* Første element * Andre element     * Legg inn 4 mellomrom på starten av linjen for å lage en underliste.
```

Vil alle bli til dette:

- Første element
- Andre element
    - Legg inn 4 mellomrom på starten av linjen for å lage en underliste.

**Ordnede lister**

Start en ordnet liste me en tom linje over den, et nummer, et punktum og et mellomrom (`1. `) Hva enn nummeret foran er har ingenting å si, bare at det er et nummer fulgt av et punktum.

Legg inn 4 mellomrom eller et tab mellomrom på starten av linjen for å lage en underliste.

```
1. Element ett2. Element to3. Element tre     4. Element fire
```

Or

```
1. Element ett1. Element to1. Element tre     1. Element fire
```

Or

```
1. Element ett10. Element to1. Element tre     1000. Element fire
```

Will all turn into this:

1. Element ett
1. Element to
1. Element tre

    4. Element fire

Nummeret du starter med påvirker ikke hvor nummreringen begynner

```
23. Tjue-tre1. Tjue-fire1. Tjue-fem    1. Tjue-seks
```

Vil bli til:

1. Tjue-tre
1. Tjue-fire
1. Tjue-fem

    4. Tjue-seks

Hvis du ønsker å nullstille nummreringen og starte på nytt i en ny liste innenfor samme inlegg kan du legge inn en tom linje eller en [skillelinje](#h_a36ba89456) imellom.

For å [forsikre at listen ikke formateres](#h_e1cdd01a87) kan du bruke din egen numrering:

Legg til et karakter på linjen over listen. Et godt valg er `\\` for den vil forsvinne og se ut som en blank linje.

```
\23. Tjue-tre24. Tjue-fire25. Tjue-fem    26. Tjue-seks
```

Legg til en backslash (`\\`) før punktum (`.`):

```
23\. Tjue-tre24\. Tjue-fire25\. Tjue-fem    26\. Tjue-seks
```

Vil alle bli til:

23. Tjue-tre

24. Tjue-fire

25. Tjue-fem

26. Tjue-seks

### 2.3 **Skillelinje**

Tre bindestrek `---` eller mer på deres egen linje vil bli til en skillelinje:

---

### 2.4 **Sjekklister**

Disse kan sjekkes i beskrivelsen til en sak. _Tilgang påkrevd -_ Skrive tilgang til sakslisten.

```
- [ ] Første element- [x] Andre element    - [ ] Underliste element
```

Vil bli til dette:

![](https://downloads.intercomcdn.com/i/o/areracg3/1211345317/e318989361e33674f3c0605f404b/image.png?expires=1781092800&signature=e5d1ec8d77092682eaad7c3e6ea1db98b66e6c9a3758e880778e2cd13aaaa970&req=dSImF8p6mIJeXvMW3nq%2BgSPARjCfpSAgbeRM0dvZvwY8M%2F5KM0VqYxKUkHyc%0AiUBJlMcar7w%2ByPqzHdgOa3akORY%3D%0A)

Klikk [her](https://support.catenda.com/en/articles/5036461-check-lists-within-issues) for å se en kort video om hvordan sjekklister kan brukes i prosjektet. Hvis du skriver `- [ ]` eller `- [x]` vil boksen vises som sjekket eller usjekket når kommentaren sendes inn eller lagres etter redigering.

**Sjekkbokser i kommentarer**

I kommentarer kan sjekkbokser bare sjekkes gjennom formatering.

Sjekklister i kommentarer kan ikke klikkes på for å sjekkes. _Tilgang påkrevd -_ Kommentar oppretter har tilgang redigering av oprettet kommentar

### 2.5 **Tables**

Tekst i beskrivelser kan organiseres i tabeller.

```
|            | Vinduer            ||             | |            | Type 1   | Type 2   | Sum totalt  | |----------- | -------- | -------- | ----------- | | **Pris**   | 500,-    | 400,-    |             | | **Mengde** | 10       | 4        |             | | **Sum**    | 5 000,-  | 1 600,-  | **6 600,-** |
```

Vil resultere i

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p class="no-margin"></p>
</td><td><p class="no-margin"></p>
</td><td><p class="no-margin">Vinduer</p></td><td><p class="no-margin"></p>
</td></tr><tr><td><p class="no-margin"></p>
</td><td><p class="no-margin">Type 1</p></td><td><p class="no-margin">Type 2</p></td><td><p class="no-margin">Sum totalt</p></td></tr><tr><td><p class="no-margin"><b>Pris</b></p></td><td><p class="no-margin">500,-</p></td><td><p class="no-margin">400,-</p></td><td><p class="no-margin"></p>
</td></tr><tr><td><p class="no-margin"><b>Mengde</b></p></td><td><p class="no-margin">10</p></td><td><p class="no-margin">4</p></td><td><p class="no-margin"></p>
</td></tr><tr><td><p class="no-margin"><b>Sum</b></p></td><td><p class="no-margin">5 000,-</p></td><td><p class="no-margin">1 600,-</p></td><td><p class="no-margin"><b>6 600,-</b></p></td></tr></tbody></table></div>

### 2.6 **Kodesstykke**

Du kan legge inn enkeltlinjer av kode på denne måten:

To `\`` på hver side av tekst vil se ut som:

![](https://downloads.intercomcdn.com/i/o/areracg3/1211345315/d4a961e95ed6f5fdc839ff7a2f79/image.png?expires=1781092800&signature=f54d228d68521b66a3b08de32b0d50f3ea61222d245a707d86e57277db02b20e&req=dSImF8p6mIJeXPMW3nq%2BgTvzb6PjrcnVmjKEK5gPyDBn37T0C2M2p6aa5SCU%0Amd95aFH14ShRw6NelEoHOBCmjJU%3D%0A)

Tre backticker `\`\`\`` over og under et stykke tekst vil se ut som dette:

![](https://downloads.intercomcdn.com/i/o/areracg3/1211345318/4dced6408d0494aef941dc329074/image.png?expires=1781092800&signature=10d990dd2fd28526765567dd236db7c095c823ef487ddfc2bedf1053a57fe15c&req=dSImF8p6mIJeUfMW3nq%2BgUvqZsqTcCKyHqIIOzWMsbdnKV9nCYKFY71H86No%0AbOGd4bayb6vzxZ9GmqqrzX91xn0%3D%0A)

Det er ikke mulig å legge inn tabeller i kodestykker

### 2.7 **Markdown dialekt**

Hvis du ønsker å vite mer om hvordan tekst er formatert i kommentarer og beskrivelser bruker vi markdown dialekten "flexmark" for å formatere denne teksten. Finn ut mer om flexmark på deres [github side](https://github.com/vsch/flexmark-java).

## 3. **@ Nevnede medlemmer og teams**

Du kan nevne brukere ved å skrive `@` og skrive kontonavnet til brukeren.

Ønsker du å legge inn nevnet bruker manuelt kan du skrive `@[konto@domene.no]`

Ved å klikke på navnet bruker eller team vil du bli tatt til [medlemmer siden](https://support.catenda.com/en/articles/8228836-member-page) til den brukeren eller [team siden](https://support.catenda.com/en/articles/7891755-team-page) til det teamet.

Brukere og teams nevnet i beskrivelsen til en sak vil automatisk [følge](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) saken og dermed får varsel om fremtidige hendelser til saken.

Dette er en god måte å forsikre at mer enn bare den [tilordnede](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9) brukeren og [etterspurte](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7) brukeren får varsel om fremtidige hendelser som endringer av felt eller nye kommentarer.

## 4. **# Taggede saker**

Du kan tagge saker ved å skrive `#` og skrive nummeret til en sak. Etter å ha sendt inn eller lagret innlegget vil det se ut som `#[123]` i den redigerte teksten. Onsker du å legge til tagget sak manuelt kan du skrive `#[Saksnummer]`

Etter å ha sendt inn eller lagret innlegget vil lenken dynamisk vise farge, status, tittel og saksnummer til saken i tillegg til å være en klikkbar lenke til saken.

Når du tagger en sak vil den saken bli lagt til i [relaterte saker](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) i høyre [informasjonsmeny](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) til saken den er tagget i.

Saken som var tagget vil også ha saken hvor den var tagget i dens liste av relaterte saker.

Saken kan manuelt fjernes fra [relaterte saker](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8).
