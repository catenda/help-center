# Statusarbeidsflyt Delt -> Publisert

## 1. **Tilgjengelighet på prosjekter**

Den nye statusarbeidsflyten er en on-demand-funksjon som kan aktiveres for pågående prosjekter. Nye prosjekter som opprettes basert på et malprosjekt der den nye statusarbeidsflyten er aktivert, vil også ha den nye statusarbeidsflyten aktivert.

_'Utkast' vil avvikles og vil ikke lenger være tilgjengelig._

## 2. **Aktivering av statusarbeidsflyt med 'delte' revisjoner**

Den gamle statusarbeidsflyten (arv) med 'utkast' vil bli erstattet av den nye statusarbeidsflyten (med delte statuser) for pågående prosjekter som ikke bruker den gamle statusarbeidsflyten. Delte statuser kan aktiveres i statusarbeidsflytmenyen på siden for dokumentinnstillinger.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/h48tax1e/01-enabling-status-workflow-with-shared-revisions.png)

Oppgraderingen fra statusarbeidsflyt med 'utkast' til statusarbeidsflyt med 'delte' dokumenter medfører disse effektene;

## 3. **Catenda Hub**

_Delt status_ Opplastinger vil alle begynne med en delt status når delte statuser er tilgjengelige i prosjektet. Etter opplasting kan delte dokumenter publiseres.

_Utkastdokumenter_ Utkast vil avvikles, derfor kan nye utkast ikke lastes opp lenger. Eksisterende utkast kan fortsatt brukes i gamle prosjekter (med begrensninger)

🖥️  _Arbeidsområde og_ ✔️ _Publisert-faner_ Separate faner (arbeidsområde og publisert) vil være tilgjengelige i dokumentområdet, der den publiserte fanen vil vise bare publiserte revisjoner.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/h48tax1e/02-catenda-hub.png)

En ny revisjonsnummerering vil vises (major.minor). #0.1, #0.2 og så videre for **delte revisjoner** og #1, #2, #3 og så videre for **publiserte revisjoner**.

### 3.1 _Tilgangskontroll_

Tilgangsrettigheter kan angis for publisering av delte revisjoner. Dette lar brukere publisere delte revisjoner og endre publiserte statuser. Tilgangskontroll vil vises på mappe-/dokumentnivå for å gi brukere rettigheten til å publisere dokumentrevisjoner med skrivetilgang. Tilgangsrettigheter for visning av delt revisjon vil være tilgjengelige. Her kan du hindre brukere med 'lesetilgang' fra å se delte revisjoner.

_Gjennomganger_ Bare delte revisjoner kan legges til en gjennomgangsforespørsel

_Samlinger_ Samlinger kan bare brukes til publiserte revisjoner

_Dokumentmodeller_ Modelområdet vil vise fanene (arbeidsområde og publisert) akkurat som i dokumentområdet. Tilgangsrettigheter vil arves fra dokumenter.

> **Merknad:** Vennligst informer prosjektmedlemmene dine om disse endringene når du aktiverer denne funksjonen på eksisterende prosjekter.

## 4. **API-klienter**

_Siste revisjon_ Siste revisjon av dokumentet (kan være delt eller publisert) hentes med mindre annet er angitt i API-anropet

_Opplastingsstandarder_ Opplastinger via API vil som standard være delte revisjoner når delte statuser er tilgjengelige i prosjektet.

_Endringer i revisjonsnummer_ Revisjonsnumre vil være inkonsistente med revisjonsnumrene (major.minor) på Catenda Hub. Du må oppdatere appen din.

> **Merknad:** Vennligst informer prosjektmedlemmene dine om disse endringene når du aktiverer denne funksjonen på eksisterende prosjekter.

Klikk [her](https://support.catenda.com/en/articles/12289689-status-workflow-api-updates) for å lese mer om API-endringer
