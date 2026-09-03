# Ny statusarbeidsflyt - ISO 19650

Den nye statusarbeidsflyten er en etterspørselsfunksjon som kan aktiveres for pågående prosjekter. Nye prosjekter som opprettes basert på et malprosjekt der denne funksjonen er aktivert, får denne funksjonen aktivert. ISO 19650-serien er en internasjonal standard for god praksis som definerer informasjonsstyringsprocesser i en bredere kontekst av digital transformasjon i byggebransjen. Mange interessenter i byggebransjen har tatt i bruk ISO-19650 som standarden for å styre dokumentlevering og godkjenningsprosesser i prosjekter.

## 1. **Livssyklus for et dokument**

I følge ISO-standarden kan et dokument ha fire ulike tilstander;

### 1.1 **🏗️ Arbeid i prosess (WiP)**

Filer som blir arbeidet med og konstant overskrives i brukerens lokale miljø. Disse filene lastes vanligvis bare opp til Catenda slik at folk kan se brukerens progresjon.

### 1.2 **👥 Delt**

Filer som er klare til å deles med andre prosjektmedlemmer for koordinering og endelige vurderinger av ulike fagfelt og/eller spesialister. Disse filene lastes opp til Catenda og sendes til respektive parter for vurdering og godkjenning.

### 1.3 **📰 Publisert**

Filer som er koordinert, ferdigstilt og akseptert som en kontraktsmessig leveranse. Disse filene har gått gjennom en vurderingsprosess og anses som "klare for neste fase (konstruksjon, overlevering, mengdetakst, tillatsutstedelse osv.)"

### 1.4 **📦 Arkivert**

Informasjonen har blitt brukt og kan arkiveres for å holdes tilgjengelig ved behov senere (revisjon, opprettelse av dokumentasjon over utførte arbeider osv.)

### 1.5 **Dokumenttilstander - ISO 19650**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/01-document-states-iso-19650.png)

### 1.6 **Arbeidsflyt på Catenda Hub**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/02-workflow-on-catenda-hub.png)

## 2. **Konfigurering av statusarbeidsflyt**

Aktivering og konfigurering av den delte statusarbeidsflyten er reservert for prosjektadministratorer.

_Tilgang kreves_ Tilgang til dokumentstatuskonfigurasjon i [tilgangskontrollområdet](https://support.catenda.com/en/articles/4670273-project-settings-page#h_3b98ced32a) på [prosjektinnstillingssiden](https://support.catenda.com/en/articles/4670273-project-settings-page). Medlemmer med denne tilgangen vil bare ha tilgang til statuskonfigurasjonsmenyen i dokumentinnstillinger. De vil ikke kunne se eller endre de andre menyene i dokumentinnstillinger.

Under [dokumentinnstillinger](https://support.catenda.com/en/articles/7831371-document-settings) navigerer du til [Statusarbeidsflyt](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) og aktiverer delte statuser

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/03-configuring-status-workflow.png)

Definer de delte og publiserte statusene som skal brukes i prosjektet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/04-configuring-status-workflow.png)

Angi standard delt status for nye revisjoner. Nye revisjoner vil i utgangspunktet bli lastet opp som delte revisjoner som senere kan publiseres. Standardstatusen må derfor være en delt revisjonsstatus. Denne statusen vil bli valgt i opplastingsdialogen for hver dokumentopplasting og kan endres til en annen delt status i opplastingsprosessen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/05-configuring-status-workflow.png)

## 3. **Kjent men annerledes**

Etter aktivering av statusarbeidsflyten vil du se to faner vises over dokument- og modelltabellene.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/06-familiar-but-different.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/07-familiar-but-different.png)

### 3.1 **Arbeidsområde**

Alle opplastinger av nye revisjoner finner sted her. Den nyeste delte revisjonen vises for hvert dokument og modell.

### 3.2 **Publisert**

En speilvendt versjon av arbeidsområdefanen. Samme mappestruktur som i arbeidsområdet vises. Bare dokumenter og modeller med publiserte revisjoner vises.

> **Merknad:** Se delte revisjoner i revisjonsoversikten av dokumentforhåndsvisningen, selv om du åpnet dokumentet fra den publiserte fanen. _Tilgang kreves:_ Delte revisjoner

### 3.3 **Last opp nye delte revisjoner**

En revisjonsstatus vil være synlig for hver opplastet fil i opplastingsdialogen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/08-upload-new-shared-revisions.png)

En revisjonsstatus vil bli brukt for hver fil som er ekstrahert fra en zippet fil.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/09-upload-new-shared-revisions.png)

### 3.4 Publiser delte revisjoner

_Flere dokumenter i dokumentstruktur_ En publiseringshandling vil være tilgjengelig i elementhandlingsmenyen for ett eller flere valgte dokumenter med delte revisjoner.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/10-publish-shared-revisions.png)

_Enkelt revidert i dokumentforhåndsvisning eller dokumentstruktur_ En publiseringshandling vil være tilgjengelig som et ikon og i handlingsmenyen for revisjonsinformasjonen til en delt revidert i høyre informasjonsmeny.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/11-publish-shared-revisions.png)

_Flere modeller_ En publiseringshandling vil være tilgjengelig i revisjonsinformasjonen om et dokument med en delt revidert i høyre informasjonsmeny i dokumentstrukturen og i dokumentforhåndsvisningen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/12-publish-shared-revisions.png)

_Tilgang kreves:_ Delte revisjoner

### 3.5 **Tilgangskontroll**

Etter at statusarbeidsflyten er aktivert, vil du se to nye kolonner vises til høyre for tilgangskolonnen i tilgangskontrolldialogen for en mappe eller et dokument.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/13-access-control.png)

Tabellen nedenfor forklarer hvordan avmerkingene påvirker brukeropplevelsen for hvert tilgangsnivå.

- Merk av "kan publisere" for et medlem eller team med skrivetilgang for å tillate dem å publisere delte revisjoner og redigere publiserte revisjonsstatus.
- Fjern merke fra "vis delte revisjoner" for et medlem eller team med lesetilgang slik at de bare ser offisielle, publiserte revisjoner.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><h3 id="h_e9579ad9ca"><b>Delt publisert tilgang</b></h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 class="intercom-align-center" id="h_dea1580c70">Lese</h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 class="intercom-align-center" id="h_3c6b6d7d28">Skrive</h3></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_a33339c27e">Kan merke av "Vis delte revisjoner"</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Kan merke av. <br/>Ikke merket som standard.</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Alltid merket</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_e909b5dc48">Kan merke av "Kan publisere"</h3></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Aldri merket</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Kan fjerne merke. <br/>Merket som standard</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_95374b8adf">Vis dokumenter</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Dokumenter med bare delte revisjoner er bare synlige hvis "vis delte revisjoner" er merket av</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Både dokumenter med delte og dokumenter med publiserte revisjoner er synlige</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_e401f7a37f">Vis delte revisjoner i dokumentinfo</h3></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Delte revisjoner er bare synlige hvis "vis delte revisjoner" er merket av</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Både delte og publiserte revisjoner er synlige</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_13cbc969df">Rediger og vis delte revisjonsstatus</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Synlig hvis "vis delte revisjoner" er merket av, men ikke redigert</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_b228d7c432">Rediger og vis publisert revisjonsstatus</h3></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Kan bare se publisert revisjonsstatus</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Rediger hvis "Kan publisere" er merket av, ellers bare visbart</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_13248acfd2">Publiser dokumenter</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Publiser hvis "Kan publisere" er merket av</p></td></tr></tbody></table></div>

### 3.6 **Hovednummer og revisjonsnummer**

Delte revisjoner har et mindre revisjonsnummer (f.eks. #0.1, #2.3, #4.1) Publiserte revisjoner har et hovednummer (#1, #2, #3 og så videre)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/14-major-and-minor-revision-numbers.png)

### 3.7 Åpne dokumentforhåndsvisningen

I dokumentstrukturen vil du se den nyeste revisjonen du har tilgang til. Klikk på navnet på et dokument for å åpne dokumentforhåndsvisningen av den viste revisjonen.

_Arbeidsområdefane_ Den nyeste revisjonen i arbeidsområdefanen kan være: Delt revidert - _Tilgang kreves:_ Delte revisjoner. Publisert revidert - ​_Tilgang kreves:_ Lese

_Publisert fane_ Den nyeste revisjonen i den publiserte fanen kan være: Publisert revidert - _Tilgang kreves:_ Lese

> **Merknad:** Delte revisjoner kan være synlige i revisjonsoversikten av dokumentforhåndsvisningen, selv om du åpnet dokumentet fra den publiserte fanen. _Tilgang kreves:_ Delte revisjoner

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/15-opening-the-document-preview.png)

### 3.8 **Revisjonsinformasjon**

Velg ett dokument eller åpne dokumentforhåndsvisningen ved å klikke på dokumentet. Informasjon om gjeldende revidert vil være synlig i [høyre informasjonsmeny](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/16-revision-information.png)

- Publiser gjeldende revidert med publiseringshandlingen.
  _Tilgang kreves:_ Delte revisjoner

- Endre en delt revisjonsstatus til en annen delt revisjonsstatus.
  _Tilgang kreves:_ Lesetilgang og delte revisjoner

- Endre en publisert revisjonsstatus til en annen publisert revisjonsstatus.
  _Tilgang kreves:_ Skrivetilgang og publiserte revisjoner

_Revisjonsinformasjonsdialog_ Klikk på revisjonsboksen for å se en oversikt over alle revisjonene i dokumentet i [revisjonsinformasjonsdialogen](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision#h_6838c6ad71). En grønn lenke mellom en publisert og en delt revidert indikerer hvilken delt revidert som ble publisert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/17-revision-information.png)

### 3.9 Delte og publiserte revisjoner i Catenda Site

Bare publiserte revisjoner er synlige i Catenda Site.

## 4. Statuskonfigurasjonstilgang

1. Rediger tilgang til dokumentstatuskonfigurasjonen kan konfigureres fra [prosjektinnstillingssiden](https://support.catenda.com/en/articles/4670273-project-settings-page):

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-868820a898ba.png" width="500"/></div>

1. Dokumentstatus kan deretter [konfigureres](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) fra innstillingene i dokumentseksjonen:

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-931418a5fab1.png" width="500"/></div>

1. Til slutt kan disse dokumentstatusene tildeles filtilstandsstatus som er tilgjengelig fra knappen med tre punkter øverst til høyre i [Godkjenningsseksjonen](https://support.catenda.com/en/articles/8349340-approvals-page). Det er også mulig å konfigurere en saksmal her.

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-3cdbebefca38.png" width="500"/></div>

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-f8ab7f3194ff.png" width="300"/></div>

## 5. **Godkjenningsarbeidsflyt**

1. En godkjenningsarbeidsflyt opprettes av en administrator.
   1. Innsender-team
   1. Vurderingsteam (minst ett godkjenningstrinn er påkrevd)
   1. Sluttverifiseringsteam
1. Et medlem av et innsender-team sender en godkjenningsforespørsel med et sett med delte revisjoner på godkjenningssiden.
1. Medlemmer av innsender-teamene som er tildelt trinnet, vurderer dokumentene som er sendt inn i godkjenningen og gir enten en godkjent eller avvist validering.
1. Når alle trinn er fullført, vurderer et medlem av sluttverifiseringsteamet valideringene som er sendt inn på vegne av de ulike teamene i hvert trinn og gir sin endelige validering av godkjent, godkjent med kommentar eller avvist.
   1. Sluttvurderer kan ta en endelig, informert beslutning om hvorvidt dette dokumentet skal publiseres (godkjent) eller avvises (være som delt)

### 5.1 **Eldre godkjenningsarbeidsflyt**

1. En godkjenningsforespørsel nominerer en utgiver (person ansvarlig for å ta den endelige avgjørelsen om publisering), og en eller flere vurderere som er ansvarlig for å validere (eller ikke) settet med dokumenter
1. Hver vurderer vil bestemme om det delte dokumentet er godkjent, godkjent med kommentar eller avvist
1. På slutten av vurderingen vil utgiveren velge resultatet av godkjenningen ved å velge dokumenter som skal publiseres.
1. Fra godkjenningsinnstillingene kan saker knyttet til dokumentene opprettes for å holde styr på prosessen senere

En detaljert demonstrasjon av disse trinnene vises i følgende opplæring:

[YouTube-video](https://www.youtube.com/embed/lDWKXWTtegU?rel=0)

## 6. **Deaktivering av statusarbeidsflyt**

Hvis du vil slå av statusarbeidsflytstrømmen, kan du gjøre det ved å klikke på radioknappen i [dokumentinnstillinger](https://support.catenda.com/en/articles/7831371-document-settings). De publiserte og delte fanene i dokumentseksjonen vil da forsvinne. Dokumenter som lastes opp mens statusarbeidsflyten ikke er aktivert, lastes opp som publisert og vil vises i den publiserte fanen når statusarbeidsflyten aktiveres.

## 7. **Fordeler ved å bruke statusarbeidsflyten**

- Den publiserte fanen fungerer som et utpekt område for kontraktsdokumenter. Prosjektmedlemmer kan enkelt finne verifiserte dokumenter.
- Dokumenter valideres før de publiseres
- Du kan konfigurere leveringsprosessen basert på ISO 19650 mye lettere
- Koordinerings-/samarbeidsdokumenter er atskilt fra kontraktsdokumenter
- Flere delte revisjoner kan velges og lastes ned, mens i den tidligere versjonen kunne kladder bare lastes ned en etter en
- Begrenset hva folk kan se i mobilappen Catenda Site
