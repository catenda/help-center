# Endringslogg 4 Catenda - Januar 2024

> Ny informasjon og mindre endringer

Hallo alle sammen,

det har vært et par fine måneder siden siste endringslogg. Håpet dere alle hadde en fin vinterferien! 🎄🤶🧑‍🎄❄️ Og velkommen til 2024!🎇 Håpet vi kan gjøre mange endringer og forbedringer i år også! I denne artikkelen finner du oppdateringer om følgende: [Artikler](https://support.catenda.com/en/articles/7983534-changelog-3-catenda-update-october-2023#h_5be2a02999) - [saker løst](https://support.catenda.com/en/articles/7983534-changelog-3-catenda-update-october-2023#h_d238d9111d) - [Nye utgivelser](https://support.catenda.com/en/articles/7983534-changelog-3-catenda-update-october-2023#h_d238d9111d)

## 1. **Artikler**

Når nye funksjoner lanseres og feil utbedres, oppdateres artikler med endringene som gjøres. Se følgende artikler som er laget og endret siden siste endringslogg.

### 1.1 **Nye artikler:**

_Kom i gang og FAQ_ [Sorteringsrekkefølge av lister](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) [Strukturering av dokumenter](https://support.catenda.com/en/articles/8542598-structuring-documents)

_Hovedside_ [Organisasjonsside](https://support.catenda.com/en/articles/8281910-organizations-page)

_Saker_ [Sakhistorikk](https://support.catenda.com/en/articles/8613038-issue-history)

_Dokumenter_ [Dokumenter](https://support.catenda.com/en/articles/8461918-documents) [PDF-sammenligning](https://support.catenda.com/en/articles/8461650-pdf-compare) [Filtrering på gjennomgangssiden](https://support.catenda.com/en/articles/8551740-filtering-on-the-approvals-page)

_Modeller og 3D_ [Bokmerke](https://support.catenda.com/en/articles/8471481-bookmark)

_Prosjektinnstillinger_ [Opprett egendefinert felt](https://support.catenda.com/en/articles/8445575-creating-a-custom-field) [Side for egendefinert felt](https://support.catenda.com/en/articles/8445588-custom-field-page)

### 1.2 **Artikler som har endret seg:**

Kom i gang og FAQ [Lagre filtre](https://support.catenda.com/en/articles/8551755-saving-filters)

Saker [Saksliste ACL](https://support.catenda.com/en/articles/4670296-issue-boards-acl)

Dokumenter [Dokumentside](https://support.catenda.com/en/articles/8204673-documents-page) [Modeller som dokumenter](https://support.catenda.com/en/articles/8064548-models-as-documents) [Filtrering på dokumentsiden](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page)

Modeller [Bokmerker-side](https://support.catenda.com/en/articles/4670281-bookmarks-page) [Opprett nytt bokmerke](https://support.catenda.com/en/articles/4670269-creating-a-new-bookmark) [Modeller som dokumenter](https://support.catenda.com/en/articles/8064548-models-as-documents)

Bibliotek <a class="intercom-content-link" href="" target="_blank">Lenkekatalog</a>

Innstillinger [Medlemsside](https://support.catenda.com/en/articles/4670291-members-page)

## 2. **Feil løst**

Takk for dine verdifulle tilbakemeldinger har vi kunnet rette mange saker som du kanskje eller kanskje ikke har lagt merke til eksisterte. Nedenfor er en liste over mindre endringer som er gjort av utviklingsteamet som et resultat av samtaler med brukere.

### 2.1 **Saker**

- Rullegardinegendefinerte felt med opptil 10 obligatoriske verdier kan nå også filtreres.
- PDF-eksporter av saker viser nå ikke lenger bestemte bilder dobbelt.
- Egendefinerte feltfiltre vises nå selv om det egendefinerte feltet er satt som obligatorisk.
- Bilder som er vedlagt til sakkommentarer etter 16. november vil nå vises i samme rekkefølge som de er i sakkommentarene i forhåndsvisningsdialogen.
- Tidspunktet for eksport i PDF-eksporten sier nå UTC bak seg slik at brukeren kan vite hvilken tidssone tidsstempelet var i.
- Modeller som er slettet i tidsrommet mellom forberedelsen og aktivering av en modeller som dokumenter-migrering vil nå bli ordentlig slettet ved migrering.

### 2.2 **Dokumenter**

- Litauiske bokstaver i dokumenter importert fra ZIP-importer vil nå ikke lenger bli ødelelagt som et resultat av zip-forgiftning.
- Tekstbobler kan igjen plasseres for brukere med MFA-tvang.
- Fremheve merkinger fra pdf-filer vises nå korrekt i PDF-viseren etter at de er lastet opp.
- PDF-filer kan igjen lagres med merkinger og kommentarer.
- Dokumenter som ikke lastet for brukere med MFA-tvang lastes nå igjen.

### 2.3 **Modeller**

- Slettemodellknappen er synlig igjen.
- Det er nå ingen måte modeller kan bli skjult lenger hvis modeller som dokumenter ble aktivert uten å migrere prosjektet.
- Epostvarselet for modellimport er fullført sier nå importert fullført på \<model> i stedet for ny revisjon i modell for klarhet.
- Det er nå bare mulig å velge pdf-dokumenter i etasjekonfiguratoren der pdf.
- Det er ikke lenger mulig å legge til ikke-PDF-dokumenter i etasjekonfiguratoren. (som bare aksepterer PDF-filer uansett)

## 3. **Brukerønsker fullført**

### 3.1 **Saker**

- Du får nå et varsel når et team du er del av blir nevnt i en sak
- Hvis du klikker på vis markør på 2D på plasseringen av en sak, vil 2D-viseren din nå sentrere seg på denne markøren i stedet for bare å vise markøren som valgt på høyre etasje.
- Bredden på modellvalgdialogen i kommentaren til en sak skaleres nå med bredden på et modellnavn. Tidligere ble lange modellnavn kuttet av og måtte holdes musen over for å se.
- Det er nå mulig å se hvordan en beskrivelse så ut før den ble endret ved å klikke på beskrivelsen som er endret boks i sakhistorikken.
- Bilder er ikke lenger vist dobbelt i PDF-eksporter av eldre saker

### 3.2 **Dokumenter**

- Dokument-ACL gjenspeiles nå i modellseksjonen for prosjekter som har modeller som dokumenter aktivert
- Du kan nå se hvor mange dokumenter som er i en samling.
- Det er nå mulig å feste til midten og endepunkter av linjer i PDF-tegninger.
- Det er nå mulig å forhåndsvise .odt og .ods filformater.

### 3.3 **Modeller**

- Det er nå mulig å angi ACL per modell i stedet for for alle modeller.

Dette betyr at du kan skjule modeller fra personer i modellseksjonen.

- Med modeller som dokumenter kan du legge til merkelapper for modeller.
- Med modeller som dokumenter kan du strukturere modeller i mapper i dokumentseksjonen.
- Med modeller som dokumenter kan du se filstørrelsen på modellen
- Med modeller som dokumenter kan du bruke navnkonvensjonfunksjonen med modeller
- Det er igjen mulig å se tidligere revisjoner av modeller i revisionvelgeren

### 3.4 **Prosjektinnstillinger**

- Merklappegrupper kan nå slettes.
- Det er nå mulig å slette merkelapper som er koblet til saker/dokumenter.
- Merklappegrupper kan redigeres.
  Du finner redigeringsblyanten i høyre informasjonsmeny etter å ha valgt merklappegruppen i fanen Grupper.
- Det er nå mulig å opprette flere merkelapper på en gang.
  Legg merke til Import flere-knappen i menyen Ny merkelapp.
- Det er nå mulig å slette flere merkelapper på en gang.
- Merkelapper kan filtreres og filtre kan lagres.
- Det er nå mulig å legge til nye merklappegrupper
- Det er mulig å legge til merklappegrupper uten å legge dem til en merkelapp først.
- Det er nå mulig å søke på merkelappersiden.
- Administratorer vil nå være i stand til å flette merkelapper. Alternativet finnes ved å velge mer enn en merkelapp på merkelappersiden.

### 3.5 **Generelt**

- Opprettelse av nye prosjekter fra malprosjekter er forbedret. Det er nå mulig å bringe følgende deler av et prosjekt til et nytt prosjekt:
  - Mappestruktur
  - Konfigurering av dokumentstatus
  - Dokument- og saktaveltilgangskontroll
  - Egendefinerte felt og navnkonvensjoner

## 4. **Nye utgivelser** - Catenda Site, programtillegg og integrasjoner

_Catenda Hub:_

- Modeller som dokumenter er nå blitt fullstendig utgitt.
- Saker er blitt omdøpt til Saker.

_Catenda Site:_ [App store](https://apps.apple.com/us/app/catenda-site/id1449579790) [Play store](https://play.google.com/store/apps/details?id=no.catenda.bimsyncmobile)

_Ny versjon 3.3.1_

- Feilrettinger

_Ny versjon 3.3.0_

- _Dyplenking_ - URL-er fra Hub-nettstedet åpnes direkte i Site-appen.
- _Sakfiltrering_ - Nytt alternativ for filtrering etter milepæl.
- _Brukernevning_ - Finn og velg raskt en bruker for omtale i saker fra verktøylinjen.
- _Tekstmarkering_ - Bruk enkelt rik tekst på sakene dine fra verktøylinjen.
- _Sentrer 2D-markør_ - Åpning av en markør fra en sak vil sentrere visningen på markørplasseringen.
- Vietnamesisk språkstøtte. 🇻🇳

_Ny versjon 3.4.0_

- Saker er blitt omdøpt til saker
- Feilrettinger

_SharePoint-integrering:_

- Du kan nå koble til Catenda-kontoen din via et nettleservindu i stedet for å vente på en e-post.
