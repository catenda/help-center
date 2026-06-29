# Modeller som dokumenter

Tidligere har det vært mulig å laste opp ifc filer på to forskjellige sted på Catenda Hub. Med _modeller som dokumenter_ funksojonen legges disse to stedene sammen til en sømløs funksjon.

Hvis du lager en modell i modelldelen vil et dokument bli lenket og opprettet i dokumenter delen. Hvis du laster opp et IFC dokument i dokumentdelen kan du bruke lag modell aksjonsknappen for å lenke og opprette en modell i modelldelen.

Med denne funksjonen kan modeller i modelldelen håndteres som dokumenter mens modeller i dokumentdelen kan håndteres som modeller.

Denne artikkelen inneholder informasjon om følgende temaer:

## 1. **Før/Etter migrering - Hovedforskjell**

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e8e8e8; width: 168px;"><h1 id="h_8b37580f81"></h1></td><td style="background-color: #e8e8e8; width: 262px;"><h2 id="h_b7f579faf9"><b>Før</b></h2></td><td style="background-color: #e8e8e8; width: 248px;"><h2 id="h_bf2a4611cb"><b>Etter</b></h2></td></tr><tr><td style="background-color: #e8e8e8; width: 168px;"><p class="intercom-align-right"><b>Hovedoppførsel</b></p></td><td style="width: 262px;"><p>Modeler fantes kun i modeller delen. Brukeren måtte laste opp samme IFC fil til både dokumenter og modeller delene.</p></td><td style="width: 248px;"><p>Modeller er opprettet som IFC filer og lastet opp til dokumentdelen. Om brukere ber om det blir en modell som hører til IFC filen opprettet.</p></td></tr><tr><td style="background-color: #e8e8e8; width: 168px;"><p class="intercom-align-right"><b>Grensesnitt</b></p></td><td style="width: 262px;"><p><b>Forskjellig </b>fra dokumentdelen og vist med mindre informasjon, bare en liste med modeller.</p></td><td style="width: 248px;"><p><b>Likt</b> som i dokumentdelen. En redigerbar tabell med relatert metadata.</p></td></tr><tr><td style="background-color: #e8e8e8; width: 168px;"><p class="intercom-align-right"><b>Tilgangsrettigheter</b></p></td><td style="width: 262px;"><p><b>Kunne ikke settes </b>på modeller</p></td><td style="width: 248px;"><p><b>Kan settes</b> på modeller fra deres relaterte dokument i dokumentdelen.</p></td></tr></tbody></table></div>

## 2. **Kjent, men annerledes**

Nå som de to delene er lenket er det viktig å merke at det fortsatt er hovedforskjell mellom modeller og dokumenter delene.

I modellerdelen vil du kunne se alle modell-dokumenter samlet i en liste.

Her vil du kunne se dine modell-dokumenter på en måte som likner på hvordan de vil brukes i 3D viseren.

I dokumenter delen vil du kunne se dokumnet-modellene i din dokumentstruktur. Her vil du kunne se dokument-modellere på en måte som likner på hvordan de brukes i ditt felles datamiljø (CDE).

Alle modeller er lenket til hvert sitt dokument og funksjoner fra begge deler kan brukes, både i modeller delen og i dokumenter delen.

## 3. **Endringer på modellersiden**

Mode modeller som dokumenter vil modeller siden ha endret i utseende. Istedet for å se meny enheter for hver modell vil de nå dukke opp i en søkbar tabell.

På modeller siden vil du nå dukke finne følgende endringer:

### 3.1 **Modeller tabellen**

Den nye modeller tabellen kan se ut noe some dette:

![](https://downloads.intercomcdn.com/i/o/areracg3/1444226365/44372549a3253c3844972ac34220/image.png?expires=1781092800&signature=2b4a1bd1d5596223c3dc53db0355da88cb8061216152e137c34787350948af5d&req=dSQjEst8m4JZXPMW3nq%2BgcMYUUGSeENGBi4OuP8AaGhHMkzeNF%2BCgSKgX8B5%0AzB%2F4sfX95CZ9g97yhuDHUO6cgBA%3D%0A)

### 3.2 **Kolonner**

Listen over modellene har kolonner som viser mesteparten av informasjon du trenger å vite om dine modeller.

**Navn**

Navnet til modell-dokumentet vises her.

Modellnavnet er også navnet du vil se i revisjonselektoren i 3D viseren.

**Dokumentnavn**

Navnet til dokument-modellen i dokumenterdelen.

**Revisjonsnavn**

Navnet til den nyeste revisjonen.

### 3.3 **Tilgangskontroll**

Hvis en modell er begrenset for deg i dokumenter delen vil modellen verken vises i dokumentdelen, modeller tabellen eller i revisjonsvelger.

### 3.4 **Modellvalg**

Med modelltabellen kan du nå selektere et sett med modeller ved å holde shift og legge til eller fjerne modeller fra ditt utvalg med kontroll.

### 3.5 **Aksjonsknapper**

Før var den eneste handlingen du kunne utføre på valgte modeller at du kunne åpne de i 3D. Nå vil du kunne laste ned, fjerne og åpne 2D visningen til dine valgte modeller i tillegg.

Hvis du sletter en modell som er koblet til et dokument vil dokumentet miste koblingen til modellen men dokumentet vil beholdes i dokumentdelen.

### 3.6 **Tilgangskontroll for dokument-modeller**

**Opprette et dokumentmodell**

Hvis du lager en modell med ny modell kanppen i modelldelen vil du bli spurt om å selektere hvor du ønsker at den lenkede dokument-modellen ender opp i dokumentdelen.

I ny modell dialogen vil du også kunne gi modellen et navn.

Den resulterende lenkede dokument-modellen vil ha samme navn som modellen når den er opprettet. Catenda Hub vil huske mappen du valgte sist og automatisk selektere den neste gang du lager en ny modell.

Hvis modeller som dokumenter er koblet på for et prosjekt som ikke startet med denne funksjonen vil en mappe kalt 'Models' dukke opp i din mappestruktur. Denne mappen vil inneholde alle dokument-modellene som er lenket til dine modell-dokumenter i modelldelen.

Dokument-modeller kan flyttes ut av denne mappen til ethvert sted i dokumentdelen du har tilgang til. Dokument-modeller kan også fjernes (og gjenopprettes) fra Models mappen. Dokument-modellene må ikke ligge i models mappen og mappen kan fjernes uten at det påvirker prosjektet.

**Opprette en modell-revisjon**

For å kunne laste opp nye revisjoner til en modell vil du nå trenge minst skrivetilgang til dokument-modellen. Nye revisjoner til modellen kan legges til i dokumentet og omventdt.

> **Note:** **Merk:** Revisjonskommentarer er koblet av og kan valgfritt kobles på igjen med [egne felt på revisjoner](https://support.catenda.com/nb/articles/9531080-egne-felt-pa-dokumenter).

**Nedlastning av modell-revisjoner**

Du trenger minst lese-tilgang til dokument-modellen for å kunne laste ned modeller.

### 3.7 **Høyre informasjonspanel**

En høyre informasjonspanel vil være tilgjengelig hvis modeller er selektert.

**Dokumentfelt**

I dette panelet vil du se modellinformasjon i tilleg til et grått felt som lenker til dokument-modellen i dokumentdelen som er lenket til dette modell-dokumentet.

Klikk på dokumentfeltet for å bli tatt til det koblede dokumentet i dokumentdelen.

**Modellmerkelapper**

Det er nå mulig å legge merkelapper på modellen her.

**Modellstatus**

Om statuser er konfigurert i dokumentinnstillinger vil du kunne stille inn en status for din modell her.

**Model transformasjon**

Hvis du har åpnet denne modellen i 3D vil du kunne stille inn modelltransformasjon her.

## 4. **Endringer på dokumentersiden**

Selv om de visbare endringen ikke er like tilsynelatende som i modeller delen er det noen få ting som vil endres for dokumenter delne når modeller som dokumenter er koblet på.

![](https://downloads.intercomcdn.com/i/o/areracg3/1444501318/59cfe37d2e72723792c54e3f48e4/image.png?expires=1781092800&signature=0c904b4a8b3a3d001f365f1089d39fbb2a72500914dbb5d6dedd97dec54e1605&req=dSQjEsx%2BnIJeUfMW3nq%2BgQVHoqHR%2BtZmOjukh0758JkCBHPOngsupoEeel2c%0Ari%2B93zrgNY%2FLOKFZImfv5nOEnHE%3D%0A)

I dokumenter delen vil du kunne finne følgende endringer:

### 4.1 **Modellfilter**

Så snart som du har noen modeller i modelldelen vil du kunne se et modellfilter dukke opp i filtermenyen. Med dette filteret kan du vise/gjemme dokument-modeller som er opprettet.

### 4.2 **Kolommer**

**Ikon**

Du vil kunne se forskjell på dokument-modell fra vanlige dokument ved modellskiltet nederst til høyre av dokumentets ikon.

![](https://downloads.intercomcdn.com/i/o/811879911/aaf93b647d7a0d7fc7ed6a97/image.png?expires=1781092800&signature=d85d765520058c1439e55163e2fea82d540890b90710aefaed4d0147309ee130&req=fCEmHs53lIBeFb4V1XW4gccdxCQn6BnPwtMJ4ulKi%2Bha5TuhRRWaS4b3SwSd%0Ae5lEzyJ0AdLKyME26LS0NqHi4w%3D%3D%0A)

**Navn**

Navnet til dokumentet

**Modellnavn**

Navnet til modellen

Om ditt ifc dokument ikke er lenket til en modell vil du se en opprett-modell knapp her.

**Revisjonsnavn**

Navnet til den siste revisjonen i dokument-modellen.

**Viser**

En kolonne med knapper til å åpner hvert individuelle dokument-modell i 3D viser.

Dokument-modeller kan bare åpnes i 3D viser hvis dokumentet er lenket til en modell.

### 4.3 **Handlingsknapper**

Last ned, slett er last 2D/3D visningen valgte modeller i den respektive viseren ved å velge ett eller flere modeller.

<img alt="" src="https://downloads.intercomcdn.com/i/o/areracg3/1444472073/4a5d62987a173603bfc50826a54e/image.png?expires=1743174000&amp;signature=e473aad540c34bdea622ff938c7d3387dcf3fb5191fe74da2e812a0220503808&amp;req=dSQjEs15n4FYWvMW3Hu4gRIYyWwnFD80rJcTivpE97hTdX7r%2BIJrQePOhbxg%0AOA%3D%3D%0A" width="310"/>    <img alt="" src="https://downloads.intercomcdn.com/i/o/areracg3/1444476210/5d03429401f489c2f68540b604ab/image.png?expires=1743174000&amp;signature=5471295ce456e51b1061a3049633ed97d4e607ab4f9aa42703250f98a26a4836&amp;req=dSQjEs15m4NeWfMW3Hu4gRy0TuhGQJSoYokVUVJAmlIAOa3c8LwX05a1oNpM%0Alw%3D%3D%0A" width="310"/>

Dette betyr at du kan slette flere modeller av gangen fremfor en-for-en som før.

Om du sletter et dokument som er koblet til en modell vil du måtte godkjenne et varsel om at modellen som er koblet til dokumentet også slettes.

> **Note:** **Merk:** Dette betyr at du kan slette en modell uten å miste data. (Slettede dokumenter kan gjenopprettes)

### 4.4 **Tilgangskontroll for dokument-modeller**

**Opprette dokument-modeller**

For å kunne laste opp nye revisjoner til en modell vil du nå trenge minst skrive tilgang til dokument-modellen.

Du kan gjøre dette ved å opprette en modell med opprett modell aksjonsknappen over modelllisten etter å ha selektert din ifc fill.

Etter å ha gjort dette vil du se dokumentet som modell på modeller siden.

Modell-dokumentet i modeller delen vil ha samme navn som dokument-modellen selv om disse kan hver bli endret senere mens lenken ivaretas.

Nye revisjoner til modellen kan legges til som revisjoner til dokumentet og omvendt.

> **Note:** **Merk:** Dette betyr at du kan opprette modeller fra flere IFC filter samtidig istedet for å måtte laste de opp en og en.

**Laste opp revisjoner til dokument-modeller**

Du vil minst måtte ha skrivetilgang til dokument-modellen for å kunne laste opp nye revisjoner til modellen.

Dette betyr at du kan bruke multi-opplastingsfunksjonen for å laste opp ifc filer til flere dokument-modeller på en gang.

**Laste ned dokument-modller**

Du vil minst måtte ha lesetilgang til dokument-modellen for å kunne laste ned modeller.

Dette betyr at du kan konfigurere tilgang for å tillate nedlastning av separater modeller istedet for bare alle eller ingen modeller.

### 4.5 **Gjenfinnnbarhet**

Det er mulig å finne Dokument-modeller dokumentdelen på samme måte som vanlige dokumenter.

- Merkelapper kan legges på dine dokument-modeller for å finne alle dokument-modeller som tilhører en type.
- Dokument-modeller kan struktureres i mapper for å gjøre det lettere å navigere til de rette modellene.
- [Egne felt kan legges på mapper](https://support.catenda.com/nb/articles/9531080-egne-felt-pa-dokumenter) der dokumenter lastes opp for å søke på metadata-verdier som relateres til hvert dokument ved opplasting
- [Egne felt kan legges på mapper](https://support.catenda.com/nb/articles/9531080-egne-felt-pa-dokumenter) der dokumenter lastes opp for å kunne legge til informasjon på hver revisjon til hvert dokument-modell.

Se [her](https://support.catenda.com/en/articles/8542598-structuring-documents#h_7838a63c73) for anbefalinger for hvordan å strukturere dine dokument-modeller så de blir lettere å finne.

### 4.6 **Godkjenne utkast IFC filer**

IFC filer kan nå lastes opp som utkast så de kan tas gjennom en godkjenningsprosess før de publiseres.

### 4.7 **Navngingingsavtaler med dokumentmodeller**

Navn på dokument siden ofte inkluderer sammenføde avkortinger for å holde dokumentnavnet kort men allikevel vise noe informasjon om hva dokumentet handler om.

Navnet til dokument-modellen kan der fæver forskjellig fra navnet til modell-dokumentet for å holde det oversiktlig med de andre dokumentete i dokumentdelen men allekevel heholde et lettleslig navn til bruk i 3D viser og på modeller siden.

Dokumentnavnet til dokument-modellen vil være navnet som er gjenkjent når dokumenter lastes opp på dokumenter siden.

HVse navnet er linknende eller likt som dokumentet vil en ny revisjon automatisk bli opprettet akkurat som med andre dokumenter.

Fordi dokument-modeller oppfører seg det samme som valige modeller er det nå mulig å bruke navngivningsavtaler med dokument-modeller for å forsikre at deltagere til dine prosjekt gir riktige navn til dokumenter ved opplasting.
