# Statusarbeidsflyt - Dokumentinnstillinger

Dette er hvordan statusarbeidsflytmenyen på [dokumentinnstillingssiden](https://support.catenda.com/en/articles/7831371-document-settings-page) kan se ut for prosjekter som aktiverte delte revisjoner etter 2. oktober 2025. I nye prosjekter er statusarbeidsflyten deaktivert som standard. Dette er hvordan statusarbeidsflytmenyen kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/01-intro.png)

Prosjekter som er opprettet basert på et [malprosjekt](https://support.catenda.com/en/articles/4670245-creating-a-new-project#h_5db32e5398) og prosjekter som aktiverte delte revisjoner før 2. oktober 2025 vil se den gamle statusarbeidsflytmenyen.

## 1. **Delte statusar**

Aktiver delte statusar for å tilpasse seg ISO 19650 og konfigurer arbeidsflyter. Dette er hvordan statusarbeidsflytmenyen kan se ut etter at delte statusar er aktivert

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/02-shared-statuses.png)

### 1.1 Aktivere delte statusar

Som standard er det ein delt status med namnet «delt» som er konfigurert. Typiske publiserte statusar som blir lagt til er:

- WIP - Blå
- Arbeid pågår - Blå
- Intern validering - Blå

_Prosjektendringer_

- Informasjon startar med eit minor revisjonstal: 0.1, 0.2, 1.1, osv...
- Informasjon kan bli publisert for å få eit major revisjonstal: 1.0, 2.0, 3.0, osv...
- Tilgangskontrollmenyen på dokumentsiden vil ha ein ekstra kolonne der tilgang til delte revisjoner og publiseringsrettar kan konfiguerast.
- Delte og publiserte statusar - Ny informasjon sendt inn i den delte fasen.
- Standard status er sett til «Delt».
- Ein gjennomgangsmeny i dokumentinnstillingar dukkar opp.
- Ein gjennomgangsfane til dokumentsiden dukkar opp.

### 1.2 **Deaktivere delte statusar**

_Prosjektendringer_

- Publiserte statusar - Ny informasjon sendt inn i den publiserte fasen.
- Standard status er sett til «Ingen status».
- Gjennomgangmenyen i dokumentinnstillingar er deaktivert.
- Gjennomgangsfanen til dokumentsiden er deaktivert.
  ​

## 2. **Publiserte statusar**

Som standard er det éin publisert status med namnet «publisert» som er konfigurert. Klikk på «Legg til status» for å leggje til fleire statusar. Typiske delte statusar som blir lagt til er:

- Publisert, med merknader - Lys grøn
- Ventar - Gul
- Til oppfølging - Raud
  ​

## 3. **Legg til status**

Du kan leggje til ein status ved å klikka på «Legg til status». Ein ny status kan ha ein farge og eit namn. Statusar kan anten leggjast til i lista over delte statusar eller i lista over publiserte statusar.

## 4. **Endre statusar**

Status kan endrast ved å klikka på blyantikonet til høgre for statusen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/03-changing-statuses.png)

Fargen og namnet på ein status kan endrast.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/04-changing-statuses.png)

### 4.1 **Sorteringsrekkjefølgje**

Etter redigering klikkar du på pilene for å flytte statusen opp og ned i lista over statusar innan sin fase.

### 4.2 **Arkivering av statusar**

Statusar kan arkiverast ved å klikka på søpelbøtta-ikonet til høgre for statusen. Det er berre mogleg å arkivere og gjenopprette statusen innan same fase. Dersom statusen som no er arkivert var brukt på informasjon, vil statusen være synleg men gjennomstreka.

### 4.3 **Gjenopprette statusar**

Arkiverte statusar kan alltid bli henta tilbake ved å klikka på "Vis arkiverte statusar". Her er alle arkiverte statusar viste og kan gjenopprettast.

## 5. Standard status

Statusen som blir vist som standard når publiseringshandlinga blir brukt for ein delt revisjon. Ein annan status kan framleis bli vald før publisering. Delte revisjoner kan òg bli publisert via [gjennomgangsførespurnader](https://support.catenda.com/en/articles/12494960-open-or-closed-approval-request-page). Avhengig av kva arbeidsflyt innsendar valde på vegne av sitt innsendar-team, når eit medlem gjer ein endelg validering på vegne av det endelege valideringsteamet vil statusen på det publiserte dokumentet endast basert på korleis arbeidsflytoppsettet er konfigurert.

## 6. Opplastingsmeny

### 6.1 **Delte statusar aktivert**

Dette er korleis opplastingsmenyen kan sjå ut når den publiserte og delte arbeidsflyten har blitt ber om å bli aktivert på eit prosjekt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/05-shared-statuses-enabled.png)

Som standard er den standard delte statusen «Delt». Ein status frå lista over delte statusar kan bli vald før opplasting.

### 6.2 **Delte statusar deaktivert**

Dette er korleis opplastingsmenyen kan sjå ut når delte statusar er deaktiverte.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/g7ntz7r8/06-shared-statuses-disabled.png)

Som standard er den standard publiserte statusen «ingen status». Ein status frå lista over publiserte statusar kan bli vald før opplasting.
