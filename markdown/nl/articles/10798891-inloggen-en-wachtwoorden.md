# Inloggen en wachtwoorden

Er zijn verschillende locaties op Catenda waar u wordt gevraagd om een wachtwoord in te voeren. Dit artikel beschrijft de verschillende uitdagingen die gebruikers kunnen ondervinden bij het invoeren van hun accountgegevens.

## 1. **Inloggen**

Op de [inlogpagina](https://support.catenda.com/en/articles/7891486-sign-in-page) wordt u gevraagd uw wachtwoord in te voeren. Dezelfde inlogpagina wordt gebruikt zowel bij inloggen via de browser als bij inloggen om toegang tot uw account via de API te geven, wat u doet met veel van onze plugins. Tijdens dit proces kunnen de volgende uitdagingen ontstaan:

### 1.1 **Foutieve gebruikersnaam of wachtwoord**

Zorg ervoor dat u de juiste combinatie van gebruikersnaam en wachtwoord invoert. Uw gebruikersnaam is altijd het e-mailadres dat aan uw account is gekoppeld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/01-wrong-username-or-password.png)

Voor degenen die niet zeker weten of ze succesvol een account hebben aangemaakt, registreert u zich opnieuw op hub.catenda.com/signup en probeert u een account aan te maken door op de link in de e-mail voor het aanmaken van een account te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/02-wrong-username-or-password.png)

Als er een account onder uw e-mailadres bestaat, wordt een waarschuwing weergegeven die bevestigt dat uw account bestaat.

### 1.2 **Te veel inlogpogingen**

Als u te vaak de foutieve gebruikersnaam of wachtwoord invoert, moet u wachten tot u het opnieuw kunt proberen of naar [https://hub.catenda.com/forgot-password](https://hub.catenda.com/forgot-password) gaan om uw wachtwoord opnieuw in te stellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/03-too-many-login-requests.png)

## 2. **Wachtwoordbevestiging**

Wanneer er een wijziging in wachtwoordgegevens plaatsvindt, wordt u gevraagd uw wachtwoord eenmaal in te voeren en daarna nog eenmaal ter bevestiging. Tijdens dit proces kunnen de volgende uitdagingen ontstaan:

### 2.1 **Wachtwoordvereiste**

Zorg ervoor dat uw wachtwoord

- minstens 12 tekens lang is

en bevat minstens één van het volgende:

- één hoofdletter
- één kleine letter
- één numeriek teken

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/04-password-requirement.png)

### 2.2 **Wachtwoord vergeten**

Als u niet kunt inloggen, kunt u een nieuw wachtwoord aanvragen door naar [https://hub.catenda.com/forgot-password](https://hub.catenda.com/forgot-password) te gaan

### 2.3 **Wachtwoorden zijn niet gelijk**

Zorg er bij het tweede keer invoeren van uw nieuwe wachtwoord voor ter bevestiging dat u hetzelfde wachtwoord invoert als u zojuist hebt ingevoerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/05-passwords-are-not-equal.png)

### 2.4 **Oud wachtwoord niet geldig**

Als u kunt inloggen, kunt u naar de [accountauthenticatiepagina](https://support.catenda.com/en/articles/6880968-account-page) gaan om uw wachtwoord opnieuw in te stellen. Hier wordt u eerst gevraagd naar uw oude wachtwoord. Dit is het wachtwoord dat u hebt gebruikt om in te loggen op uw account. Als u het juiste wachtwoord niet invoert, ziet u het volgende bericht:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/06-old-password-not-valid.png)

### 2.5 **Nieuw wachtwoord is hetzelfde**

Als u uw wachtwoord wijzigt, zorg ervoor dat u een nieuw wachtwoord invoert dat niet hetzelfde is als uw vorige wachtwoord.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/07-new-password-is-the-same.png)

### 2.6 500-fout bij gebruik van SSO

Als u een 500-fout ontvangt nadat u zich hebt aangemeld met SSO, kan het e-mailadres dat door uw Identity Provider wordt verstrekt afwijken van het e-mailadres dat is geregistreerd op uw Catenda-gebruikersaccount. Omdat er geen overeenkomende gebruiker kan worden gevonden, mislukt het inloggen met een 500-fout. Neem contact op met de IT-beheerder van uw organisatie om te controleren welk e-mailadres via SSO wordt verzonden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/08-500-error-when-using-sso.png)
