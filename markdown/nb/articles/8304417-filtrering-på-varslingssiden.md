# Filtrering på varslingssiden

Både i [innstillingene for varsel](https://support.catenda.com/en/articles/8272435-notification-settings) og i [prosjektspesifikke innstillingene for varsel](https://support.catenda.com/en/articles/4670262-project-specific-notification-settings) vil du kunne konfigurere hvilke varslinger du ønsker å motta.

I denne artikkelen vil vi forklare i hvilke situasjoner varslinger sendes for de forskjellige innstillingene. Etter at et varsel er sendt, kan det finnes igjen på [siden for kontovarsler](https://support.catenda.com/en/articles/7439223-account-notifications-page) og [siden for prosjektvarsler](https://support.catenda.com/en/articles/4670295-project-notifications-page) ved å åpne filtermenyen på venstre side.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/810mbm4a/01-intro.png)

## 1. **Varslingshistorikk**

Varsler begynner å bli sendt til et medlemskap så snart de har sluttet seg til et prosjekt. Historikken over varsler i et prosjekt går derfor tilbake til når prosjektet ble sluttet seg til. Medlemmer som har vært del av prosjektet lenger kan derfor være i stand til å fange opp tidligere hendelser som nye medlemmer ikke har.

## 2. **Filtre**

Klikk på filterknappen øverst til venstre for å få et panel til å vises på venstre side. Når et filter brukes, endres nettadressen som er synlig i nettleseren. I denne artikkelen vises filtrene slik:

### 2.1 **_Filternavn i meny_ - `Filternavn i URL=Filteralternativ i URL`**

_Standardfilter_ Standardfilteret er opprinnelig ikke synlig i nettadressen. Når siden navigeres til for første gang, brukes følgende filter.

### 2.2 _Fra en måned siden_ - `dateFrom=last-month`

### 2.3 **Lagre og del gjeldende filter**

Gå til nettadressen til en filtrert side for å laste inn siden med filteret brukt. De brukte filtrene kan lagres mot toppen av filtermenyen. Klikk [her](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) for å lese mer om hvordan du lagrer og deler filtre

### 2.4 **Skjul tomme filtre**

Klikk [her](https://support.catenda.com/en/articles/8551755-saving-filters) for å lese mer om å begrense filterresultater.

## 3. **Datofiltre**

Med datoilteret kan du velge en tidsperiode for når varsler ble sendt.

### 3.1 **Fra en uke siden** - `dateFrom=last-week`

Varsler fra den siste uken.

### 3.2 **Fra en måned siden** - `dateFrom=last-month`

Hvis du navigerer til siden for kontovarsler, vil den bli filtrert etter varsler fra siste måned som standard.

### 3.3 **Fra et år siden** - `dateFrom=last-year`

Varsler fra det siste året.

### 3.4 **Velg en dato** - `date-from=<Epoch Unix Timestamp>&date-to=<Epoch Unix Timestamp>`

Les [denne](https://support.catenda.com/en/articles/6511685-date-filter) artikkelen for å lære hvordan du enkelt velger datoer på siden.

### 3.5 **Alle varsler**

For å se alle varslinger du noen gang har mottatt, fjerner du dateFrom-filteret fra nettadressen.

## 4. **Type**

Typemenyen inneholder alle filtrerbare varslingstyper.

Varsler er delt inn i følgende typer:

## 5. **Alle** - `type=all`

Alle varsler sendes både i nettleseren og via e-post som standard. Hvis du går til en varslingsside, blir den filtrert etter varsler fra siste måned som standard. Hvis du fjerner dateFrom-filteret fra nettadressen og bruker type=all-filteret, vil du kunne se alle varslinger du noen gang har mottatt.

## 6. **Modeller** - `type=models`

_Ny modell -_ `type=new-model` Varselet viser navnet på modellen som ble opprettet.

_Varselklikk tar deg til:_ Modelloversiktssiden til prosjektet modellen er opprettet i.

_Varselinnstillingsalternativ:_ En ny modell opprettes

### 6.1 **Sendt selv om alle avmerkingsbokser er avhuket i innstillinger**

_Innsjekking mislyktes_ - `type=checkin-failed` Hvis formateringen av IFC-filen på en eller annen måte ikke gjenkjennes av systemet vårt

_Import mislyktes_ - `type=import-failed` Kan skje hvis tilkoblingen ble avbrutt under opplasting.

_Importering fullført_ - `type=import-completed` Når en modell er ferdig med behandlingen

_Varselinnstillingsalternativ:_ En ny revisjon importeres

_Eksport vellykket_ - `type=export-completed` Når modelleksporten har fullført zipping og er klar for nedlasting.

_Varselinnstillingsalternativ:_ En ny eksport opprettes

## 7. **Saker** - `type=issues`

### 7.1 **Ny sak** - `type=new-issue`

Dette er det eneste varselet du får om en sak hvis du ikke [følger](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) saken. Tildelte personer, forespørrere og medlemmer som er nevnt i saker, følger automatisk saken og vil få varslene nedenfor.

_Varselinnstillingsalternativ:_ En ny sak opprettes

### 7.2 **Ny kommentar** - `type=new-comment`

Hvis du verken er tildelt eller forespørrer av saken, men [følger](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) saken, vil du få dette varselet.

Dette kan skje hvis du tidligere var [tildelt](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9), [forespørrer](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [nevnt](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) eller [manuelt fulgt](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) saken. Hvis du ikke vil ha fremtidige varsler om denne saken, kan du slutte å følge saken i dens [høyre informasjonspanel](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue). _Varselinnstillingsalternativ: tildelt til meg_ En sak er tildelt deg

_Varselinnstillingsalternativ: forespurt av meg_ En sak er forespurt av deg

_Varselinnstillingsalternativ: fulgt av meg_ En sak er fulgt av deg

### 7.3 **Tildelt til meg** - `type=issue-assigned`

_Varselinnstillingsalternativ:_ En sak er tildelt meg

### 7.4 **Team tildelt** - `type=issue-team-assigned`

Når et team er tildelt en sak

_Varselinnstillingsalternativ:_ En sak er tildelt meg

### 7.5 Nevnt meg - `type=issue-mentioned`

_Varselinnstillingsalternativer:_ En sak nevner meg eller ett av mine team

### 7.6 **Team nevnt** - `type=issue-team-mentioned `

_Varselinnstillingsalternativer:_ En sak nevner meg eller ett av mine team

### 7.7 **Status oppdatert** - `type=status-updated`

Hvis du verken er tildelt eller forespørrer av saken, men [følger](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) saken, vil du få dette varselet.

Dette kan skje hvis du tidligere var [tildelt](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9), [forespørrer](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [nevnt](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) eller [manuelt fulgt](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) saken. Hvis du ikke vil ha fremtidige varsler om denne saken, kan du slutte å følge saken i dens [høyre informasjonspanel](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue). _Varselinnstillingsalternativ: tildelt til meg_ En status oppdateres i en sak tildelt deg

_Varselinnstillingsalternativ: forespurt av meg_ En status oppdateres i en sak forespurt av deg

_Varselinnstillingsalternativ: fulgt av meg_ En status oppdateres i en sak fulgt av deg

### 7.8 **Type oppdatert** - `type=type-updated`

Hvis du verken er tildelt eller forespørrer av saken, men [følger](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) saken, vil du få dette varselet.

Dette kan skje hvis du tidligere var [tildelt](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9), [forespørrer](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7), [nevnt](https://support.catenda.com/en/articles/8430847-formatting-of-posts#h_2481ad1c8c) eller [manuelt fulgt](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) saken. Hvis du ikke vil ha fremtidige varsler om denne saken, kan du slutte å følge saken i dens [høyre informasjonspanel](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue). _Varselinnstillingsalternativer:_

Tildelt til meg - En type oppdateres i en sak tildelt deg

Forespurt av meg - En type oppdateres i en sak forespurt av deg

Fulgt av meg - En type oppdateres i en sak fulgt av deg

### 7.9 **Sendt selv om alle avmerkingsbokser er avhuket i innstillinger**

### 7.10 **Flytt vellykket** - `type=issues-move-success`

Viser antallet saker som ble flyttet og til hvilken saksliste de ble flyttet.

### 7.11 **Flytt mislyktes** - `type=issues-move-failed`

Viser antallet saker som ikke kunne flyttes og til hvilken saksliste de ikke kunne flyttes til.

### 7.12 **Import mislyktes** - `type=issues-import-failed`

Viser hvilken type sakimport som mislyktes å importere og hvilken saksliste det mislyktes å importere til. _Mulige sakimporttyper:_ BCF

### 7.13 **Import fullført** - `type=issues-import-success`

Viser hvilken type sakimport som ble vellykket importert og hvilken saksliste den ble importert til. _Mulige sakimporttyper:_ BCF

### 7.14 **Eksport mislyktes** - `type=issues-export-failed`

Viser hvilken type sakeksport som mislyktes og hvilken saksliste den mislyktes å eksportere fra. _Mulige sakeksporttyper:_ BCF 2.0, BCF 2.1, PDF, Excel

### 7.15 **Eksport vellykket** - `type=issues-export-success`

Viser hvilken type sakeksport som ble vellykket eksportert og hvilken saksliste den ble eksportert fra. _Mulige sakeksporttyper:_ BCF 2.0, BCF 2.1, PDF, Excel

## 8. **Dokumenter** - `type=documents`

### 8.1 **Dokument lagt til** - `type=document-created`

_Varselinnstillingsalternativ:_ Et dokument eller en mappe opprettes

### 8.2 **Ny dokumentrevisjon** - `type=document-revision-uploaded`

_Varselinnstillingsalternativ:_ En ny dokumentrevisjon lastes opp

### 8.3 **Virus oppdaget** - `type=document-file-infected`

Hvis et dokument oppdages å være infisert med et virus, mottar du et varsel uavhengig av e-postsammendraginnsetting. Et varsel vil også bli sendt til administratorene i prosjektet til det infiserte dokumentet. Varselet vil angi hvem som lastet opp hvilket dokument hvor.

Hvis e-postvarslene dine er helt av, vil ikke dette varselet bli sendt som e-postvarsel. Du vil fortsatt få varselet i Catenda Hub selv om Catenda Hub-varsler er slått av.

> **Merknad:** Dette varselet vil bli sendt selv om alle varsler har blitt deaktivert

### 8.4 **Dokument fjernet** - `type=document-deleted`

_Varselinnstillingsalternativ:_ Et dokument eller en mappe slettes

### 8.5 **Dokumenter fjernet** - `type=documents-deleted`

_Varselinnstillingsalternativ:_ Et dokument eller en mappe slettes

### 8.6 **Dokumenter lastet opp** - `type=documents-uploaded`

_Varsel sendt hvis:_ Et dokument er lastet opp av en annen bruker

### 8.7 **Dokumentgjennomgang**

_Varselinnstillingsalternativer:_ Jeg er angitt som utgiver i en gjennomgangsforespørsel Et team jeg er medlem av er angitt som utgiver i en gjennomgangsforespørsel Jeg er angitt som anmelder for en gjennomgangsforespørsel Ny kommentar i gjennomgangsforespørsel

### 8.8 **Utpakking av zip fullført**

_Varsel sendt hvis:_ En zip-mappe er vellykket importert.

> **Merknad:** Dette varselet vil bli sendt selv om alle varsler har blitt deaktivert

### 8.9 **Din zip-nedlasting er klar**

Hvis du har lastet ned flere dokumenter på en gang, vil en zip bli forberedt. Denne zip-en kan lastes ned fra varselet når som helst, selv om du skulle lukke nettleseren og åpne den på nytt.

Klikk på "_Klikk for å laste ned (...MB)_" tekstdelen av varselet for å laste ned zip-filen.

Hvis du bare klikker på varselet, vil det bare oppdatere siden.

Navnet på den nedlastede zip-en vil være _\<Download GUID>.zip_ i motsetning til navnet på zip-en du automatisk får hvis du venter på at zip-en skal ferdig zipping etter å ha klikket på nedlasting, som er \<Projectname>-\<Documents>-\<Timestamp>.zip Varsel sendt til: _Brukeren som har lastet ned dokumentene._

> **Merknad:** Dette varselet vil bli sendt selv om alle varsler har blitt deaktivert

## 9. **Samlinger** - `type=document-collections`

### 9.1 **Samling fullført** - `type=library-item-collection-finalized`

_Varsel sendt hvis_ Du eller et team du er medlem av er angitt som følger av en samling og samlingen er fullført.

_Varselinnstillingsalternativ_ Samling fullført

### 9.2 **Fulgt en samling** - `type=library-item-collection-made-follower`

_Varsel sendt hvis_ Du eller et team du er medlem av ble lagt til som følger av en samling.

_Varselinnstillingsalternativ_ Fulgt en samling

### 9.3 **Sluttet å følge en samling** - `type=library-item-collection-removed-follower`

_Varsel sendt hvis_ Du eller et team du er medlem av ble fjernet fra en samling.

_Varselinnstillingsalternativ_ Sluttet å følge en samling

### 9.4 **Samling oppdatert** - `type=library-item-collection-updated`

_Varsel sendt hvis_ En samling deles med prosjektet og du eller et team du er medlem av har blitt angitt som følger.

_Varselinnstillingsalternativ_ Samling oppdatert

### 9.5 **Samling gjort privat** - `type=library-item-collection-made-private`

_Varsel sendt hvis_ Du, eller et team du er medlem av, er angitt som følger av en samling som deles med prosjektet og samlingen gjøres privat.

_Varselinnstillingsalternativ_ Samling gjort privat

### 9.6 **Samling slettet** - `type=library-item-collection-deleted`

_Varsel sendt hvis_ Du er administrator og en annen administrator sletter en samling i prosjektet.

_Varselinnstillingsalternativ_ Samling slettet

### 9.7 **Samling delt eksternt** - `type=library-item-collection-shared-externally`

_Varsel sendt hvis_ Du er administrator og en annen administrator deler en samling i prosjektet eksternt.

_Varselinnstillingsalternativ_ Samling delt eksternt

## 10. **Medlemmer** - `type=members`

### 10.1 **Ny invitasjon** - `type=invite`

_Varsel sendt hvis:_ En annen bruker sender deg en invitasjon til et prosjekt. Varselet beskriver hvem som inviterte deg og til hvilket prosjekt du ble invitert. Hvis du mottok dette varselet, bør du også ha mottatt en e-post med en invitasjonslenke som du kan klikke på for å godta invitasjonen. Kontroller [her](https://support.catenda.com/en/articles/8417802-why-am-i-not-receiving-emails) for feilsøking av e-post.

> **Merknad:** Varselet på Catenda Hub inneholder også invitasjonslenken slik at du også kan klikke på varselet for å godta invitasjonen. Hvis du ikke har en konto ennå, må du kanskje opprette en og bli invitert på nytt for å kunne klikke på varselet.

_Varselinnstillingsalternativ_ En person inviteres til prosjektet.

### 10.2 **Nytt medlem** - `type=member-accept-invitation`

_Varsel sendt hvis_ Hvis en bruker godtar en invitasjon sendt av et annet medlem, sendes et varsel om at et nytt medlem har blitt med i prosjektet.

_Varselinnstillingsalternativ_ En ny bruker har sluttet seg til prosjektet

### 10.3 **Lagt til team** - `type=member-added-to-team`

_Varsel sendt hvis_ Du har blitt lagt til et team.

### 10.4 **Nytt teammedlemsskap** - `type=project-member-added-to-team`

_Varselinnstillingsalternativ_ Et medlem legges til et team

## 11. **Prosjekt**

### 11.1 **Prosjektnavn** - `projects=<Project GUID>`

## 12. **Grense**

### 12.1 **Antall varsler per side** - `limit=<Notification amount>`

_Merknad:_ Det kan ta lengre tid å laste siden med flere varsler.

## 13. **Side**

### 13.1 **Gjeldende side med varsler** - `page=<Page number>`

## 14. **Obligatoriske varsler**

Det er noen varsler som sendes selv om du har avmerket alle avmerkingsboksene i varselinnstillingene.

### 14.1 **Sendt selv om alle avmerkingsbokser er avhuket**

Enhver type import eller eksport som behandles i bakgrunnen, vil produsere et varsel om resultatet av importen, uavhengig av om den er importert eller mislyktes. Hvis du slår av varsler helt med på/av-knappen øverst til høyre, vil disse varslene heller ikke sendes.

### 14.2 **Sendt selv om alle varsler er deaktivert**

Varsler om lenker delt med brukere via [sharelink](https://support.catenda.com/en/articles/4728886-sharelink-notify-people-about-catenda-hub-content)-funksjonen vil alltid opprette varsel for brukeren selv om en bruker har slått av varsler helt med på/av-knappen øverst til høyre på siden med varselinnstillinger.
