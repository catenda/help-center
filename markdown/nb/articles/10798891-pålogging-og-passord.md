# Pålogging og passord

Det finnes flere steder hvor du blir bedt om å skrive inn et passord på Catenda. Denne artikkelen beskriver de ulike utfordringene brukerne kan møte når de skriver inn kontoopplysningene sine.

## 1. **Logg inn**

På [påloggingssiden](https://support.catenda.com/en/articles/7891486-sign-in-page) blir du bedt om å skrive inn passordet ditt. Den samme påloggingssiden brukes både når du logger inn via nettleseren og når du logger inn for å gi tilgang til kontoen din via APIen, som du gjør med mange avPlugInnene våre. Under denne prosessen kan følgende utfordringer oppstå:

### 1.1 **Feil brukernavn eller passord**

Sørg for at du skriver inn riktig kombinasjon av brukernavn og passord. Brukernavnet ditt er alltid e-postadressen som er knyttet til kontoen din.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/01-wrong-username-or-password.png)

For de som er usikre på om de har opprettet en konto, registrer deg på nytt på hub.catenda.com/signup og prøv å opprette en konto ved å klikke på lenken i e-posten for kontoopretting.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/02-wrong-username-or-password.png)

Hvis en konto under e-postadressen din finnes, vises en advarsel som bekrefter at kontoen din finnes.

### 1.2 **For mange påloggingsforsøk**

Hvis du skriver inn feil brukernavn eller passord for mange ganger, må du enten vente en periode før du kan prøve igjen, eller gå til [https://hub.catenda.com/forgot-password](https://hub.catenda.com/forgot-password) for å tilbakestille passordet ditt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/03-too-many-login-requests.png)

## 2. **Passordbekreftelse**

Når det er en endring i passordinformasjonen, blir du bedt om å skrive inn passordet ditt en gang for å skrive det inn og en gang til som bekreftelse. Under denne prosessen kan følgende utfordringer oppstå:

### 2.1 **Passordkrav**

Sørg for at passordet ditt er

- minst 12 tegn langt

og inneholder minst ett av følgende:

- en stor bokstav
- en liten bokstav
- ett numerisk tegn

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/04-password-requirement.png)

### 2.2 **Glemt passord**

Hvis du ikke kan logge inn, kan du be om et nytt passord ved å gå til [https://hub.catenda.com/forgot-password](https://hub.catenda.com/forgot-password)

### 2.3 **Passordene er ulike**

Når du skriver inn det nye passordet ditt for andre gang for å bekrefte det, må du sørge for at du skriver inn samme passord som du nettopp skrev inn.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/05-passwords-are-not-equal.png)

### 2.4 **Eksisterende passord er feil**

Hvis du kan logge inn, kan du gå til [kontoautentiseringssiden](https://support.catenda.com/en/articles/6880968-account-page) for å tilbakestille passordet ditt. Her blir du først bedt om det gamle passordet ditt. Dette er passordet du brukte til å logge inn på kontoen din. Hvis du ikke skriver inn riktig passord, vil du se følgende melding:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/06-old-password-not-valid.png)

### 2.5 **Nytt passord er det samme**

Hvis du endrer passordet ditt, må du sørge for å skrive inn et nytt passord som ikke er det samme som det forrige passordet ditt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/07-new-password-is-the-same.png)

### 2.6 500-feil ved bruk av SSO

Hvis du mottar en 500-feil etter å ha logget inn med SSO, kan e-postadressen som tilbys av identitetsleverandøren din være forskjellig fra e-postadressen registrert på Catenda-brukerkontoen din. Siden ingen samsvarende bruker kan finnes, mislykkes påloggingen med en 500-feil. Kontakt IT-administratoren i organisasjonen din for å verifisere hvilken e-postadresse som sendes gjennom SSO.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/08-500-error-when-using-sso.png)
