# Ny statusarbeidsflyt - ISO 19650

Den nye statusarbeidsflyten er en etterspørselsfunksjon som kan aktiveres for pågående prosjekter. Nye prosjekter som opprettes basert på et malprosjekt der denne funksjonen er aktivert, har denne funksjonen aktivert. ISO 19650-serien er en internasjonal standard for god praksis som definerer informasjonsstyringsprocesser i en bredere sammenheng av digital transformasjon i byggeindustrien. Mange interessenter i byggeindustrien har tatt i bruk ISO-19650 som standarden for å styre dokumentleveranse- og godkjenningsprosesser i prosjekter.

Følgende emner er beskrevet i denne artikkelen:

## 1. **Livssyklus for et dokument**

I henhold til ISO-standarden kan et dokument ha fire forskjellige tilstander;

Følgende emner er beskrevet i denne delen:

### 1.1 **🏗️ Arbeid pågår (WiP)**

Filer som blir arbeidet med og konstant overskrevet i brukerens lokale miljø. Disse filene lastes vanligvis bare opp til Catenda slik at mennesker kan se brukerens fremgang.

### 1.2 **👥 Delt**

Filer som er klare til å deles med andre prosjektmedlemmer for koordinering og endelig gjennomgang av ulike fagområder og/eller spesialister. Disse filene lastes opp til Catenda og sendes til respektive parter for gjennomgang og godkjenning.

### 1.3 **📰 Publisert**

Filer som er koordinert, ferdigstilt og akseptert som en avtalefestet leveranse. Disse filene har gått gjennom en gjennomgangsprosess og anses som "klare for neste fase (konstruksjon, overleveranse, mengdeoppgjøring, tillatelseissuering osv.)"

### 1.4 **📦 Arkivert**

Informasjonen har blitt brukt og kan arkiveres for å forbli tilgjengelig om nødvendig senere (revisjon, opprettelse av utførelsesdokumentasjon, osv.)

### 1.5 **Dokumenttilstander - ISO 19650**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/01-document-states-iso-19650.png)

### 1.6 **Arbeidsflyt på Catenda Hub**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/02-workflow-on-catenda-hub.png)

## 2. **Konfigurering av statusarbeidsflyt**

Aktivering og konfigurering av den delte statusarbeidsflyten er reservert for prosjektadministratorer.

_Tilgang påkrevd_ Dokumentstatuskonfigurasjonstilgang i [tilgangskontrollområdet](https://support.catenda.com/en/articles/4670273-project-settings-page#h_3b98ced32a) på [prosjektinnstillingssiden](https://support.catenda.com/en/articles/4670273-project-settings-page). Medlemmer med denne tilgangen vil bare ha tilgang til statuskonfigurasjonsmenyen i dokumentinnstillinger. De vil ikke kunne se eller endre de andre menyene i dokumentinnstillinger.

Under [dokumentinnstillinger](https://support.catenda.com/en/articles/7831371-document-settings) navigerer du til [Statusarbeidsflyt](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) og aktiverer delte statuser

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/03-configuring-status-workflow.png)

Definer de delte og publiserte statusene som skal brukes i prosjektet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/04-configuring-status-workflow.png)

Angi standarddelt status for nye revisjoner. Nye revisjoner lastes opprinnelig opp som delte revisjoner som senere kan publiseres. Standardstatus må derfor være en delt revisjonsstatus. Denne statusen vil bli valgt i opplastingsdialogen for hver dokumentopplasting og kan endres til en annen delt status i opplastingsprosessen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/05-configuring-status-workflow.png)

## 3. **Kjent men annerledes**

Etter aktivering av statusarbeidsflyten vil du se to faner vises ovenfor dokumenter- og modelltabellene.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/06-familiar-but-different.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/07-familiar-but-different.png)

Følgende emner er beskrevet i denne delen:

### 3.1 **Arbeidsområde**

Alle opplastinger av nye revisjoner finner sted her. Den nyeste delte revisjonen vises for hver dokument og modell.

### 3.2 **Publisert**

En speilet versjon av arbeidsområdefanen. Den samme mappestrukturen som i arbeidsområdet vises. Bare dokumenter og modeller med publiserte revisjoner vises.

> **Merk:** Se delte revisjoner i revisjonsoversikten over dokumentforhåndsvisningen, selv om du åpnet dokumentet fra den publiserte fanen. _Tilgang påkrevd:_ Delte revisjoner

### 3.3 **Last opp nye delte revisjoner**

En revisjonsstatus vil være synlig for hver opplastet fil i opplastingsdialogen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/08-upload-new-shared-revisions.png)

En revisjonsstatus vil bli brukt for hver fil ekstrahert fra en zippet fil.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/09-upload-new-shared-revisions.png)

### 3.4 Publiser delte revisjoner

_Flere dokumenter i dokumentstruktur_ En publiseringshandling vil være tilgjengelig i menyen for eksisterende elementhandling for ett eller flere valgte dokumenter med delte revisjoner.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/10-publish-shared-revisions.png)

_Enkelt revisjon i dokumentforhåndsvisning eller dokumentstruktur_ En publiseringshandling vil være tilgjengelig som et ikon og i handlingsmenyen av revisjonsinformasjonen for en delt revisjon i høyre informasjonsmeny.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/11-publish-shared-revisions.png)

_Flere modeller_ En publiseringshandling vil være tilgjengelig i revisjonsinformasjonen for et dokument med en delt revisjon i høyre informasjonsmeny i dokumentstrukturen og i dokumentforhåndsvisningen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/12-publish-shared-revisions.png)

_Tilgang påkrevd:_ Delte revisjoner

### 3.5 **Tilgangskontroll**

Etter at statusarbeidsflyten er aktivert, vil du se to nye kolonner dukke opp til høyre for tilgangskolonnen i tilgangskontrolldialogen for en mappe eller dokument.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/13-access-control.png)

Tabellen nedenfor forklarer hvordan avmerkingene påvirker brukerens opplevelse for hvert tilgangsnivå.

- Merk av "kan publisere" for et medlem eller team med skrivetilgang for å tillate dem å publisere delte revisjoner og redigere publiserte revisjonsstatus.
- Fjern merkingen "se delte revisjoner" for et medlem eller team med lesetilgang slik at de bare ser offisielle, publiserte revisjoner.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><h3 id="h_e9579ad9ca"><b>Delt publisert tilgang</b></h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_dea1580c70">Les</h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_3c6b6d7d28">Skrive</h3></td></tr><tr><td><h3 id="h_a33339c27e">Kan merke av "Se delte revisjoner"</h3></td><td><p class="intercom-align-center">Kan merke av. <br/>Uavmerket som standard.</p></td><td><p class="intercom-align-center">Alltid merket av</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_e909b5dc48">Kan merke av "Kan publisere"</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Aldri avmerket</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Kan fjerne merkingen. <br/>Merket av som standard</p></td></tr><tr><td><h3 id="h_95374b8adf">Vis dokumenter</h3></td><td><p class="intercom-align-center">Dokumenter med bare delte revisjoner er bare synlige hvis "se delte revisjoner" er avmerket</p></td><td><p class="intercom-align-center">Både dokumenter med delte og dokumenter med publiserte revisjoner er synlige</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_e401f7a37f">Se delte revisjoner i dokumentinfo</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Delte revisjoner er bare synlige hvis "se delte revisjoner" er avmerket</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Både delte og publiserte revisjoner er synlige</p></td></tr><tr><td><h3 id="h_13cbc969df">Rediger og se delte revisjonsstatus</h3></td><td><p class="intercom-align-center">Vist hvis "se delte revisjoner" er avmerket, men ikke redigert</p></td><td><p class="intercom-align-center">x</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_b228d7c432">Rediger og se publisert revisjonsstatus</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Kan bare se publisert revisjonsstatus</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Rediger hvis "Kan publisere" er merket av, ellers bare viselig</p></td></tr><tr><td><h3 id="h_13248acfd2">Publiser dokumenter</h3></td><td><p class="intercom-align-center">-</p></td><td><p class="intercom-align-center">Publiser hvis "Kan publisere" er merket av</p></td></tr></tbody></table></div>

### 3.6 **Hoved- og mindre revisjonsnumre**

Delte revisjoner har et mindre revisjonsnummer (f.eks. #0.1, #2.3, #4.1). Publiserte revisjoner har et hovedrevisjonsnummer (#1, #2, #3 og så videre)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/14-major-and-minor-revision-numbers.png)

### 3.7 Åpne dokumentforhåndsvisningen

I dokumentstrukturen vil du se den nyeste revisjonen som du har tilgang til. Klikk på navnet på et dokument for å åpne dokumentforhåndsvisningen av den viste revisjonen.

_Arbeidsområde-fanen_ Den nyeste revisjonen i arbeidsområde-fanen kan være: Delt revisjon - _Tilgang påkrevd:_ Delte revisjoner Publisert revisjon - ​_Tilgang påkrevd:_ Les

_Publisert fane_ Den nyeste revisjonen i den publiserte fanen kan være: Publisert revisjon - _Tilgang påkrevd:_ Les

> **Merk:** Delte revisjoner kan være synlige i revisjonsoversikten over dokumentforhåndsvisningen, selv om du åpnet dokumentet fra den publiserte fanen. _Tilgang påkrevd:_ Delte revisjoner

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/15-opening-the-document-preview.png)

### 3.8 **Revisjonsinformasjon**

Velg et enkelt dokument eller åpne dokumentforhåndsvisningen ved å klikke på dokumentet. Informasjon om gjeldende revisjon vil være synlig i [høyre informasjonsmeny](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/16-revision-information.png)

- Publiser gjeldende revisjon med publiseringshandlingen.
  _Tilgang påkrevd:_ Delte revisjoner

- Endre en delt revisjonsstatus til en annen delt revisjonsstatus.
  _Tilgang påkrevd:_ Lesetilgang og delte revisjoner

- Endre en publisert revisjonsstatus til en annen publisert revisjonsstatus.
  _Tilgang påkrevd:_ Skrivetilgang og publiserte revisjoner

_Revisjonsinformasjonsdialog_ Klikk på revisjonsfeltet for å se en oversikt over alle revisjonene i dokumentet i [revisjonsinformasjonsdialogen](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision#h_6838c6ad71). En grønn lenke mellom en publisert og en delt revisjon indikerer hvilken delt revisjon som ble publisert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/17-revision-information.png)

### 3.9 Delte og publiserte revisjoner i Catenda Site

Bare publiserte revisjoner er synlige i Catenda Site.

## 4. Statuskonfigurasjonstilgang

1. Redigeringstitgang til dokumentstatuskonfigurasjonen kan konfigureres fra [prosjektinnstillingssiden](https://support.catenda.com/en/articles/4670273-project-settings-page):

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-868820a898ba.png" width="500"/></div>

2. Dokumentstatus kan deretter [konfigureres](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) fra innstillingene i dokumentdelen:

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-931418a5fab1.png" width="500"/></div>

3. Til slutt kan disse dokumentstatusene tilordnes filgjennomgangsstatus som er tilgjengelig fra de tre punktene-knappen øverst til høyre i [Godkjenningsdelen](https://support.catenda.com/en/articles/8349340-approvals-page). Det er også mulig å konfigurere en emnemal her.

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-3cdbebefca38.png" width="500"/></div>

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-f8ab7f3194ff.png" width="300"/></div>

## 5. **Godkjenningsarbeidsflyt**

1. En godkjenningsarbeidsflyt opprettes av en administrator.
   1. Innsendate team
   2. Gjennomgangsteam (minst ett godkjenningstrinn er påkrevd)
   3. Sluttgjennomgangsteam
2. Et medlem av et innsendate team sender inn en godkjenningsforespørsel med et sett med delte revisjoner på godkjenningssiden.
3. Medlemmer av innsendate team tildelt trinnet gjennomgår dokumentene som er sendt inn i godkjenningen og gir enten en godkjent eller avvist validering.
4. Når alle trinnene er fullført, gjennomgår et medlem av sluttgjennomgangsteamet valideringene som har blitt sendt inn på vegne av de ulike teamene i hvert trinn, og gir deres endelige validering av godkjent, godkjent med kommentar eller avvist.
   1. Den endelige godkjenneren er i stand til å ta en endelig, informert beslutning om hvorvidt dette dokumentet skal publiseres (godkjent) eller avvist (forbli som delt)

### 5.1 **Arv godkjenningsarbeidsflyt**

1. En godkjenningsforespørsel utnevner en Utgiver (person som er ansvarlig for å ta den endelige beslutningen om publiseringen), og en eller flere Gjennomgangspersoner, som er ansvarlige for å validere (eller ikke) settet med dokumenter
2. Hver gjennomgangsperson vil bestemme om det delte dokumentet er Godkjent, Godkjent med kommentar eller Avvist
3. På slutten av gjennomgangen vil Utgiver velge resultatet av godkjenningen ved å velge dokumentene som skal publiseres.
4. Fra godkjenningsinnstillingene kan emner relatert til dokumentene opprettes for å holde oversikt over prosessen senere

En detaljert demonstrasjon av disse trinnene vises i følgende veiledning:

[YouTube-video](https://www.youtube.com/embed/lDWKXWTtegU?rel=0)

## 6. **Deaktivering av statusarbeidsflyt**

Hvis du vil slå av statusarbeidsflyten kan du gjøre det ved å klikke på radioknappen i [dokumentinnstillinger](https://support.catenda.com/en/articles/7831371-document-settings). De publiserte og delte fanene i dokumentdelen vil da forsvinne. Dokumenter som lastes opp mens statusarbeidsflyten ikke er aktivert, lastes opp som publisert og vises i den publiserte fanen når statusarbeidsflyten blir aktivert.

## 7. **Fordeler ved bruk av statusarbeidsflyten**

- Den publiserte fanen fungerer som et utpekt område for avtalebaserte dokumenter. Prosjektmedlemmer kan lett finne verifiserte dokumenter.
- Dokumenter valideres før de publiseres
- Du kan konfigurere leveringsprosessen din basert på ISO 19650 mye lettere
- Koordinerings-/samarbeidsdokumenter er atskilt fra avtalebaserte dokumenter
- Flere delte revisjoner kan velges og lastes ned, der i tidligere versjon kunne utkast bare lastes ned ett om gangen
- Begrens hva mennesker kan se i mobilappen Catenda Site
