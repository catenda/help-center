# Avansert navnekonvensjon

Denne artikkelen bygger på følgende artikler: [Enkleste navnekonvensjon](https://support.catenda.com/en/articles/7845360-simplest-naming-convention) og [Medium navnekonvensjon](https://support.catenda.com/en/articles/7936943-medium-naming-convention) Artikkelen kan følges uten å ha lest disse artiklene, men det kan være nyttig å se gjennom dem da det kan finnes informasjon om [konvensjoner](https://support.catenda.com/en/articles/7832559-naming-conventions-page) som ikke er nevnt i denne artikkelen. I denne artikkelen lærer du alle måtene [konvensjoner](https://support.catenda.com/en/articles/7832559-naming-conventions-page) kan brukes.

## 1. **YYMMDD\_Filnavn\_V.pdf**

Ved å konfigurere denne [konvensjonen](https://support.catenda.com/en/articles/7832559-naming-conventions-page) lærer du alt du trenger å vite om [navnekonvensjoner](https://support.catenda.com/en/articles/7832559-naming-conventions-page) slik at du kan velge [blokkene](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) du liker for din egen [konvensjon](https://support.catenda.com/en/articles/7832559-naming-conventions-page). Si at du organiserer alle 3D-modellene og konstruksjonstegningene dine lokalt.

- Du har en bindestrek _( - )_ i filnavnet, så for å skille de ulike [blokkene](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) må du bruke en understrek _( \_ )_ som [separator](https://support.catenda.com/en/articles/7832559-naming-conventions-page#:~:text=in%20document%20settings-,Separator,-%3A%20The%20character).
- Disse filene starter med datoen da filen ble laget.

Dette er nyttig for deg fordi selv om det vanligvis står dette på ulike steder, er det bare mer visuelt for deg å ha filene dine alfabetisk ordnet etter opprettelsesdato.

- Etter det vil du ha filnavnet som kan være av hvilken som helst lengde.
- På slutten av filnavnet har du en status som indikerer hvilken versjon av filen du har.

Denne delen er bare ekstra tekst du bruker til å skille filene dine lokalt. Du vil ikke se denne delen av filnavnet i Catenda Hub-dokumentnavnet da det bare er nyttig for deg lokalt og har ingenting å gjøre med andre personer i prosjektet.

- Til slutt har du bestemt deg for å sikre at du bare holder spesifikke filtyper i denne mappen.

Du begrenser filtypen til IFC, PDF, DWG, SMC, PL og RVT

### 1.1 **Innledende oppsett**

Dokumenter med følgende filnavn vil bli brukt i denne artikkelen. Du kan forberede disse på forhånd eller lage dem når du kommer til den delen av artikkelen:

_Lokale filer:_ 230219\_Elevation\_Draft.PDF 230219\_Elevation\_Final.PDF aaaaaa\_\_Elevation\_Draft.PDF 230219\_Elevation\_Draft.pdf

_En fjerde [blokk](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) for filstatusen_ Datoen på filen ser ut som koden fra eksemplet i [medium navnekonvensjon](https://support.catenda.com/en/articles/7936943-medium-naming-convention) artikkelen. [Blokken](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) som inneholder dokumentnavnet skal også være det samme som filnavnet [blokk](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) i den artikkelen. Den eneste [blokken](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) du trenger å legge til som er forskjellig fra eksemplet ovenfor er en [blokk](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) for statusdelen av filnavnet ditt.

_Konvensjonsoppsett_ For dette eksemplet bruker du [navnekonvensjonen](https://support.catenda.com/en/articles/7832559-naming-conventions-page) som vises på bildet nedenfor som utgangspunkt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b16sm7xd/01-initial-setup.png)

### 1.2 **Egendefinerte felt i konvensjoner**

Det finnes tre ulike typer egendefinerte felt som er nyttige i [konvensjoner](https://support.catenda.com/en/articles/7832559-naming-conventions-page): [Heltall](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=3.%20Click%20on%20%22New%20Custom%20Field%22), [Tekst](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=3.%20Click%20on%20%22New%20Custom%20Field%22) og [Rullegardin](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=If%20you%20add%20a%20%22dropdown%22%20field) [egendefinerte felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup) kan brukes som kilder for [konvensjonsblokker](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541).

_[Heltalls egendefinerte felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=3.%20Click%20on%20%22New%20Custom%20Field%22) i [konvensjoner](https://support.catenda.com/en/articles/7832559-naming-conventions-page)_ På bildet ovenfor er kilden til den første [blokken](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) satt til tekst. Hvis vi prøver å laste opp den første filen 230219\_Elevation\_Draft.PDF ser du at den lastes opp uten problemer. Du kunne imidlertid også laste opp seks bokstaver i stedet for tall som: aaaaaa\_\_Elevation\_Draft.PDF og det ville være ok også. For å begrense dette til kun tall, lag et nytt [heltalls egendefinert felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=3.%20Click%20on%20%22New%20Custom%20Field%22) kalt NC\_Date. Det heter det bare for å holde det organisert i [listen over egendefinerte felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=the%20list%20of%20custom%20fields). Sett deretter dette [egendefinerte feltet](https://support.catenda.com/en/articles/6550459-custom-fields-setup) som [kilden](https://support.catenda.com/en/articles/7832559-naming-conventions-page#:~:text=has%20an%20extension.-,Source,-%3A%20What%20will) til den første [blokken](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) ved å klikke på rullegardinlisten der det for tiden står tekst og velge [egendefinert felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup) du opprettet. Du vil nå se at aaaaaa\_\_Elevation\_Draft.PDF ikke lenger er akseptert mens 230219\_Elevation\_Draft.PDF er akseptert.

_[Tekst egendefinerte felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=3.%20Click%20on%20%22New%20Custom%20Field%22) i [konvensjoner](https://support.catenda.com/en/articles/7832559-naming-conventions-page)_ For den andre [blokken](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) kan du la kilden være tekst siden all tekst er akseptert her. Det anbefales fortsatt å bruke et tekst egendefinert felt som kunne være navngitt NC\_Filename for fremtidig kompatibilitet.

Statusen kan også være hvilket som helst ord av hvilken som helst lengde, så lag et [tekst egendefinert felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=3.%20Click%20on%20%22New%20Custom%20Field%22) kalt NC\_Status og sett det som [kilden](https://support.catenda.com/en/articles/7832559-naming-conventions-page#:~:text=has%20an%20extension.-,Source,-%3A%20What%20will) for den tredje [blokken](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541).

For disse to blokkene vil du ikke merke noen forskjell i opplastingsprosessen. Du vil kunne se at [forhåndsvisen](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_c2f7e24fbc) på ulike steder nå gjenspeiler navnet på det [egendefinerte feltet](https://support.catenda.com/en/articles/6550459-custom-fields-setup).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b16sm7xd/02-custom-fields-in-conventions.png)

_[Rullegardin egendefinerte felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=If%20you%20add%20a%20%22dropdown%22%20field) i [konvensjoner](https://support.catenda.com/en/articles/7832559-naming-conventions-page)_

_Navn samme som kode_ For den siste [blokken](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541) som inneholder [utvidelsen](https://support.catenda.com/en/articles/7832559-naming-conventions-page#:~:text=The%20name%20of%20the%20file/document%20extension), er det bare et spesifikt sett med fraser som skal aksepteres. For å gjøre dette lag et [rullegardin egendefinert felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=If%20you%20add%20a%20%22dropdown%22%20field) kalt NC\_Extension. I dette [egendefinerte feltet](https://support.catenda.com/en/articles/6550459-custom-fields-setup) setter du [rullegardinalternativene](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=add%20multiple%20options) IFC, PDF, DWG, SMC, PL og RVT. Gjør navn og kode like. Vær forsiktig fordi disse må legges til en etter en fordi en kode må angis. Prøv nå å laste opp 230219\_Elevation\_Draft.pdf og se at den ikke blir akseptert. Denne egendefinerte frasen er versalfølsom. Hvis du også vil at små bokstaver skal aksepteres, må du legge dem til [rullegardin egendefinert felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=If%20you%20add%20a%20%22dropdown%22%20field) også.

_Annet navn og kode_ Et annet godt eksempel på hva du kan gjøre med et [rullegardin egendefinert felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=If%20you%20add%20a%20%22dropdown%22%20field) er å ha et annet navn og kode. Si at du har tegninger fra mekaniske, strukturelle og elektriske ingeniører med deres respektive [blokker](https://support.catenda.com/en/articles/7832559-naming-conventions-page#h_efc0be7541). I Catenda Hub vil du at disse tegningene bare skal kalles Engineering. Hva du kan gjøre er å lag et [rullegardin egendefinert felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=If%20you%20add%20a%20%22dropdown%22%20field) [flere alternativer](https://support.catenda.com/en/articles/6550459-custom-fields-setup#:~:text=add%20multiple%20options) som har navn Engineering og kode for typen engineering du forventer å finne i filnavnet. Når du laster opp filen vil du se at selv om filnavnet hadde mekanisk, strukturell eller elektrisk i det, vil dokumentnavnet alltid si Engineering.

### 1.3 **Dokumentidentifikator**

[I begynnelsen av denne artikkelen](http://You%20do%20not%20want%20to%20see%20this%20part%20of%20the%20file%20name) var det nevnt at det var viktig at statusdelen av filnavnet ikke dukket opp som Catenda Hub-dokumentnavnet. Det er det [dokumentidentifikatoren](https://support.catenda.com/en/articles/7832559-naming-conventions-page#:~:text=block%20to%20do-,Document%20identifier,-%3A) gjør. Når dette alternativet er deaktivert, vil ikke denne delen av filnavnet bli brukt til å lage dokumentnavnet i Catenda Hub i det hele tatt. Prøv å laste opp 230219\_Elevation\_Draft.PDF og deretter 230219\_Elevation\_Final.PDF Legg merke til hvordan dokumentnavnet vil være det samme selv om filnavnet var annerledes. Dette er nyttig fordi hvis dokumentnavnet er det samme, vil [navnekonvensjonen](https://support.catenda.com/en/articles/7832559-naming-conventions-page) automatisk gjenkjenne at den andre filen er en revisjon av den første.

Til slutt er dette hvordan [navnekonvensjonen](https://support.catenda.com/en/articles/7832559-naming-conventions-page) din med [egendefinerte felt](https://support.catenda.com/en/articles/6550459-custom-fields-setup) og [dokumentidentifikatorer](https://support.catenda.com/en/articles/7832559-naming-conventions-page#:~:text=block%20to%20do-,Document%20identifier,-%3A) skal se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b16sm7xd/03-document-identifier.png)
