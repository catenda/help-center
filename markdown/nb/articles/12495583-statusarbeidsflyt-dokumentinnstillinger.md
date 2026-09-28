# Statusarbeidsflyt - Dokumentinnstillinger

Dette er hvordan statusarbeidsflytmenyen på [dokumentinnstillingssiden](https://support.catenda.com/nb/articles/7831371-dokumentinnstillinger) kan se ut for prosjekter som aktiverte delte revisjoner etter 2. oktober 2025. I nye prosjekter er statusarbeidsflyten deaktivert som standard. Dette er hvordan statusarbeidsflytmenyen kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/01-intro.png)

Prosjekter som er opprettet basert på et [malprosjekt](https://support.catenda.com/nb/articles/4670245-opprette-et-nytt-prosjekt#h_5db32e5398) og prosjekter som aktiverte delte revisjoner før 2. oktober 2025 vil se den gamle statusarbeidsflytmenyen.

## 1. **Delte statuser**

Aktiver delte statuser for å tilpasse seg ISO 19650 og konfigurer arbeidsflyter. Dette er hvordan statusarbeidsflytmenyen kan se ut etter at delte statuser er aktivert

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/02-shared-statuses.png)

### 1.1 Aktivere delte statuser

Som standard er det en delt status med navnet «delt» som er konfigurert. Typiske publiserte statuser som blir lagt til er:

- WIP - Blå
- Arbeid pågår - Blå
- Intern validering - Blå

_Prosjektendringer_

- Informasjon starter med et minor revisjonstall: 0.1, 0.2, 1.1, osv...
- Informasjon kan bli publisert for å få et major revisjonstall: 1.0, 2.0, 3.0, osv...
- Tilgangskontrollmenyen på dokumentsiden vil ha en ekstra kolonne der tilgang til delte revisjoner og publiseringsrettigheter kan konfigureres.
- Delte og publiserte statuser - Ny informasjon sendt inn i den delte fasen.
- Standard status er sett til «Delt».
- En gjennomgangsmeny i dokumentinnstillinger dukker opp.
- En gjennomgangsfane til dokumentsiden dukker opp.

### 1.2 **Deaktivere delte statuser**

_Prosjektendringer_

- Publiserte statuser - Ny informasjon sendt inn i den publiserte fasen.
- Standard status er sett til «Ingen status».
- Gjennomgangmenyen i dokumentinnstillingar er deaktivert.
- Godkjenningssiden for dokumenter er deaktivert.<br>

## 2. **Publiserte statuser**

Som standard er det én publisert status med navnet «publisert» som er konfigurert. Klikk på «Legg til status» for å legge til flere statuser. Typiske delte statuser som blir lagt til er:

- Publisert, med merknader - Lys grøn
- Ventar - Gul
- Til oppfølging - Rød<br>

## 3. **Legg til status**

Du kan legge til en status ved å klikke på «Legg til status». En ny status kan ha en farge og et navn. Statuser kan enten legges til i listen over delte statuser eller i listen over publiserte statuser.

## 4. **Endre statuser**

Status kan endres ved å klikke på blyantikonet til høyre for statusen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/03-changing-statuses.png)

Fargen og navnet på en status kan endres.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/04-changing-statuses.png)

### 4.1 **Sorteringsrekkjefølgje**

Etter redigering klikker du på pilene for å flytte statusen opp og ned i listen over statuser innenfor sin fase.

### 4.2 **Arkivering av statuser**

Statuser kan arkiveres ved å klikke på søppelbøtte-ikonet til høyre for statusen. Det er bare mulig å arkivere og gjenopprette statusen innenfor samme fase. Dersom statusen som nå er arkivert var brukt på informasjon, vil statusen være synlig, men gjennomstreket.

### 4.3 **Gjenopprette statuser**

Arkiverte statuser kan alltid bli hentet tilbake ved å klikke på "Vis arkiverte statuser". Her er alle arkiverte statuser vist og kan gjenopprettes.

## 5. Standard status

Statusen som blir vist som standard når publiseringshandlingen blir brukt for en delt revisjon. En annen status kan fremdeles bli valgt før publisering. Delte revisjoner kan også bli publisert via [gjennomgangsforespørsler](https://support.catenda.com/nb/articles/12494960-apen-eller-lukket-gjennomgangsforesporsel). Avhengig av hvilken arbeidsflyt innsenderen valgte på vegne av sitt innsender-team, når et medlem gjør en endelig validering på vegne av det endelige valideringsteamet, vil statusen på det publiserte dokumentet endres basert på hvordan arbeidsflytoppsettet er konfigurert.

## 6. Opplastingsmeny

### 6.1 **Delte statuser aktivert**

Dette er hvordan opplastingsmenyen kan se ut når den publiserte og delte arbeidsflyten har blitt bedt om å bli aktivert på et prosjekt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/05-shared-statuses-enabled.png)

Som standard er den standard delte statusen «Delt». En status fra listen over delte statuser kan bli valgt før opplasting.

### 6.2 **Delte statuser deaktivert**

Dette er hvordan opplastingsmenyen kan se ut når delte statuser er deaktivert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/06-shared-statuses-disabled.png)

Som standard er den standard publiserte statusen «ingen status». En status fra listen over publiserte statuser kan bli valgt før opplasting.
