# Feilsøking av innhold i egendefinert felt

## 1. **Kunne ikke gjenopprette arkivert rullegardinalternativ**

En logisk vranglås oppstår hvis et forsøk gjøres på å gjenopprette et arkivert alternativ mens det tilknyttede **Navnet** allerede er i bruk av et aktivt alternativ. Fordi det bare er mulig å tildele et navn til ett alternativ, blir gjenopprettingen blokkert. _Tilgang påkrevd:_ Administrator-tilgang

For å gjenopprette den arkiverte verdien, er det mulig å følge denne sekvensen:

_Gi nytt navn til den aktive verdien_ Det aktive alternativet som for øyeblikket bruker navnet, blir redigert av en administrator til en midlertidig verdi for å frigjøre navnet i systemet.

_Gjenopprette den arkiverte verdien_ **Deaktivert liste** åpnes, og **Gjenopprette**-handlingen velges for det nødvendige elementet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/01-unable-to-restore-archived-dropdown-option.png)

_Korrigere dataene_ Navnene og kodene justeres til riktig tilstand.

_Gjenopprette navn_ Det midlertidige navnet endres tilbake til det opprinnelige tiltenkte navnet.

## 2. **Unikhet av navn og koder**

Det er viktig å skille mellom **Navn** på et alternativ og **Koden** dets. Hvert rullegardinalternativ består av begge disse elementene, og det er bare mulig å lagre et alternativ hvis både navn og kode er unike innenfor det spesifikke egendefinerte feltet.

## 3. **Duplikatnavn-feil**

Det er bare mulig å tildele ett navn til ett alternativ i en rullegardinfølge. Hvis en duplikatnavn-feil vises, utføres følgende trinn: _Tilgang påkrevd:_ Administrator-tilgang

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/02-duplicate-name-error.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/03-duplicate-name-error.png)

_Verifisering av aktiv liste_ Listen over aktive alternativer sjekkes for å bekrefte om navnet allerede er i bruk.

_Verifisering av deaktivert liste_ Den deaktiverte listen sjekkes, da navn tilordnet arkiverte elementer forblir i systemet.

_Løsning_ Det er bare mulig å fortsette ved enten å bruke et annet unikt navn eller ved å gi nytt navn til det eksisterende alternativet som holder navnet.

## 4. **Duplikatkode-feil**

Det er bare mulig å tildele en kode til ett alternativ innenfor et egendefinert rullegardinfelt. Koden er en unik verdi som brukes til å identifisere blokker for navnekonvensjoner. _Tilgang påkrevd:_ Administrator-tilgang

Hvis en duplikatkode-feil vises:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/04-duplicate-code-error.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/05-duplicate-code-error.png)

_Verifisering av aktiv liste_ Den aktive listen sjekkes for å se om koden allerede er i bruk.

_Verifisering av deaktivert liste_ Den deaktiverte listen sjekkes, da koder tilordnet arkiverte elementer fortsatt opptar denne unike verdien.

_Løsning_ Det er bare mulig å fortsette ved enten å bruke en annen unik kode eller ved å deaktivere det eksisterende alternativet som holder koden.

## 5. Endring av eksisterende koder

Det er bare mulig å definere en kode under den opprinnelige opprettingen av et alternativ eller hvis et allerede eksisterende alternativ ikke har en kode tilordnet ennå. Etter at en kode er lagt til og lagret, er den låst til den verdien og feltet blir ikke redigerbart.

_Redigeringsbegrensninger_ Det er bare mulig å endre **Navn** på et alternativ etter at en kode er brukt. **Kode**-feltet vil vises grått.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/06-modifying-existing-codes.png)

Før bruk:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/07-modifying-existing-codes.png)

Etter bruk:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/08-modifying-existing-codes.png)

_Gjenoppretting av en kode_ Hvis en kode allerede er i bruk av et arkivert element, er det bare mulig å bruke denne spesifikke koden ved først å gjenopprette det arkiverte alternativet fra den deaktiverte listen. Det er ikke mulig å sende inn et nytt alternativ med en kode som teknisk sett fortsatt holdes av et deaktivert element.

_Endring av en kode_ For å bruke en helt annen kode for et eksisterende navn, er det bare mulig å gjøre dette ved å deaktivere det gjeldende alternativet og opprette et nytt med den ønskede koden.

## 6. Inndatafeil for heltallsfelt

Spesifikke begrensninger finnes for heltallsfelt som resulterer i inndatafeil:

_Bare hele tall_ Det er bare mulig å lagre hele tall i et egendefinert heltallsfelt.

_Ikke-numeriske tegn_ Selv om det bare er mulig å skrive tall direkte inn i feltet, er det mulig å lime inn ikke-numeriske tegn i det.

_Virkemåte for Lagre-knapp_ Hvis det er noen ikke-numeriske tegn i feltet, er Lagre-knappen deaktivert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/09-input-errors-for-integer-fields.png)

## 7. **Synlighet og Filtrering på brett**

Hvis et egendefinert felt ikke er synlig på et issue board, kontrolleres følgende innstillinger:

_Felttilordning_ Opprettelse av et egendefinert felt gjør det mulig å legge det til et issue board. Feltet må legges til det spesifikke brettet for å vises i issue header.

_Tabelvisning_ Det er bare mulig å vise data fra egendefinerte felt i et listeformat hvis den tilsvarende kolonnen er valgt i issue board tabelvisningen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/10-board-visibility-and-filtering.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/11-board-visibility-and-filtering.png)

_Filterbegrensninger_ Det er bare mulig å filtrere etter egendefinerte felt hvis det er opptil 10 felt tilordnet.
