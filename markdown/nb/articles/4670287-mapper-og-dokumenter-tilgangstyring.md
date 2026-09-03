# Mapper og Dokumenter tilgangstyring

> Tilgangskontrollnivåer for Dokumenter

Velg dokument(er) og/eller mappe(r) i dokumentområdet for å finne tilgangskontrollmenyen i [høyremeny](https://support.catenda.com/en/articles/8345396-right-menu-on-the-documents-page#h_cad792004b). Her kan du se hvilke prosjektmedlemmer som har tilgang til dokumentet. Følg disse trinnene for å redigere tilgangen for de valgte elementene.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/01-intro.png)

1. Velg dokument(ene) og/eller mappe(ne) som skal konfigureres.
1. Åpne høyremenyen
1. Klikk på **rediger tilgang**.

> **Viktig:** **Påkrevd tilgang:** Full tilgang

Tilgangskontrolldialogen kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/02-intro.png)

## 1. **1. Konfigurer tilgang for prosjektmedlemmer**

Klikk på "Definer tilgang for"-rullegardinmenyen for å velge medlemmer som tilgangen skal konfigureres for. Medlemmer kan velges som enkeltperson eller som medlem av et team. Tilgangsroller inkluderer administrator, individuell brukeradgang, grunnlinjadgang, teamadgang og eieradgang.

### 1.1 **1.1 Anbefalt arbeidsflyt**

Sett tilgang **per team i stedet for per bruker**. Roller endres ofte, og teambasert tilgang forblir fleksibel: når et medlem blir lagt til et team, får de riktig tilgang så snart de blir med i prosjektet. Et vanlig mønster er å sette "alle brukere" til ingen adgang – slik at nye, ikke-ennå-tildelte medlemmer ikke kan se sensitiv informasjon – og deretter gi tilgang til hvert team etter behov.

Klikk [her](https://support.catenda.com/en/articles/15644094-how-catenda-calculates-access-levels) for å lese mer om hvordan de ulike medlemmerrollene oppstiller seg mot hverandre.

## 2. **2. Hvilken tilgang blir brukt? (3 trinn)**

Tilgangen med høyest vekt vinner alltid, men det finnes unntak. Restriktive nivåer som "Ingen tilgang" heves selv når andre stier gir høyere rettigheter.

### 2.1 **2.1 Hvilken av konfigurasjonene gjelder?**

_Administratorer_ Administratorer har alltid tilgang til alt.

_Individer_ Den nøyaktig konfigurerte tilgangsnivået gjelder.

_Andre_ Kontroller den ulike tilgangen som er konfigurert for en bruker enten via en av følgende:

- Alle brukere
- Et team som brukeren er medlem av (kan være medlem av flere)
- Eieradgang.

Tilgangen med høyest vekt gjelder. Ingen tilgang > Full tilgang > Skriv > Les

Klikk [her](https://support.catenda.com/en/articles/15644094-how-catenda-calculates-access-levels) for å lese mer om hvordan tilgangsnivåer beregnes. Klikk [her](https://support.catenda.com/en/articles/15644249-access-control-deployment-use-cases) for å lese mer om typiske måter tilgang konfigureres på.

### 2.2 **2.2 Hva kan deltakere gjøre med den tilgangen?**

Klikk [her](https://support.catenda.com/en/articles/15647394-operations-on-document-library-items) for å lese mer om hvilke operasjoner som kan utføres på mapper og Dokumenter.

## 3. **3. Overskrivingsalternativer (omfang brukt ved lagring)**

Når tilgangsdialogen lagres, blir tilgangen på de valgte elementene **overskreve uavhengig av hva som var konfigurert tidligere**. De tre alternativene under "Hvor skal du bruke disse reglene" styrer hvor langt den endringen når.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Alternativ</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Hva blir overskreve</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Hvilken tilgang forblir som før</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Når skal du bruke</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Mappe og nytt innhold</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Valgte elementer + eventuelle nye elementer opprettet i dem</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Elementer ett nivå ned + elementer i mappestrukturer.</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Når du ikke må endre tilgangen til eksisterende innhold</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Mappe og filer<br/>(standard)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ovennevnte + eksisterende Dokumenter ett nivå ned</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Mapper ett nivå ned + elementer i mappestrukturer.</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Det vanlige valget; tilgang per undermappe bevares</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Mappe og alle undermapper og filer</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ovennevnte + mapper ett nivå ned + elementer i mappestrukturer.</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Bare når det er greit å overskrive eksisterende tilgang for undermappe også</p></td></tr></tbody></table></div>

> **Merk:** **Forsiktig:** de to første alternativene overskrever bare de valgte elementene, så eldre tilgang kan forbli på underelementene. Medlemmer kan kanskje ikke lenger navigere til dem, men kan fortsatt nå dem gjennom filtrering.

## 4. **4. Arbeidsflyt med status**

Hvis delte statuser ble aktivert etter 2. oktober 2025, vises to ekstra kolonner til høyre for tilgangskolonnen: **Se delte revisjoner** og **Kan publisere**. Hvilke bokser som kan merkes avhenger av tilgangsnivået. Slik kan det se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/03-4-status-workflow.png)

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Tilgang</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Se delte revisjoner</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Publiser</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ingen tilgang</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ikke tilgjengelig (element ikke vist i listen)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Nei</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Les</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Kan gis (valgfritt)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Nei</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Skriv</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Alltid i stand til å vise</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Kan gis (valgfritt)</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Full tilgang</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Alltid i stand til å vise</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ja</p></td></tr></tbody></table></div>
