# Kontosida

Dine [kontoinnstillinger](https://bimsync.com/account/profile) finner du på to steder:

1. På venstre side av **startsiden** til Catenda Hub.
1. I rullegardinmenyen som vises etter at du klikker på **profilbildet** ditt hvor som helst i Catenda Hub.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/01-intro.png)

[Kontosiden](#h_38e4a79227) har tre undersider.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/02-intro.png)

## 1. **Konto**

På [kontosiden](https://bimsync.com/account/profile) er det mulig å endre brukernavnet ditt og profilbildet. Det er ikke mulig å endre e-postadressen din da den er knyttet til kontoen din.

slik kan kontosiden se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/03-account.png)

Som du kan se øverst til høyre, hvis ingen profilbilde er lastet opp, vises initialene fra brukernavnet ditt. Initialene som vises er de første tre tegnene etter hvert mellomrom i brukernavnet. Det er ikke mulig å angi egendefinerte initialer. En måte å omgå dette på ville være å lage et profilbilde med de ønskede initialene i.

### 1.1 **Endre bilde**

Klikk på endre bilde og velg et profilbilde fra systemet ditt. Dialogboksen "Angi nytt bilde" åpnes som kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/04-change-photo.png)

Klikk på angi nytt bilde for å lagre profilbildet. Dette er hvordan profilbildemenyen kan se ut etter at profilbildet er lagt til

![](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/05-change-photo.png)

> **Merk:** at profilbildet kun er synlig i Catenda-produkter og vil ikke være synlig i andre produkter som informasjon fra Catenda kan ha blitt utvekslet med.

### 1.2 **Slett bilde**

Klikk på slett bilde for å slette profilbildet ditt.

## 2. **Preferanser**

I [preferanser](https://bimsync.com/account/preferences) er det mulig å:

![Tilpass ulike aspekter i Catenda Hub](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/06-preferences.png)

### 2.1 **Språk**

[Endre språket](https://support.catenda.com/en/articles/4670248-changing-to-your-preferred-language) til Catenda Hub

### 2.2 **Dato og tid**

Velg i hvilket format du vil se dato- og tidsinnstillinger. Som standard vises dato- og tidsinnstillinger som relative til gjeldende tid. Dette betyr at et problem som blir opprettet eller en modell som blir lastet opp vil vises som opprettet for 1 uke eller 1 måned siden. Hvis du trenger mer spesifikk informasjon enn det, for eksempel for å se hvor mye tid som har gått mellom to elementer som ble lastet opp nær hverandre, er det mulig å slå av dette alternativet. Dato og tid rundt Catenda Hub vil nå vises med den spesifikke datoen og tiden for hendelsen.

## 3. **Autentisering**

I [autentisering](https://bimsync.com/account/authentication) er det mulig å:

1. Endre passordet ditt

Klikk [her](https://support.catenda.com/en/articles/10798891-sign-in-and-passwords) for feilsøking av passord

1. [Aktiver og deaktiver MFA.](https://support.catenda.com/en/articles/4969891-multi-factor-authentication)

![Kontroller hvordan du logger inn](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/07-authentication.png)

## 4. **Applikasjoner**

På [applikasjonssiden](https://bimsync.com/account/apps) kan applikasjoner som er konfigurert for kontoen vises. Dette er hvordan applikasjonssiden kan se ut:

![Håndter applikasjonene dine og applikasjoner som får tilgang til dataene dine](https://raw.githubusercontent.com/catenda/help-center/main/images/e4w10q5d/08-applications.png)

### 4.1 **Dine applikasjoner**

Hver API-applikasjon er forbundet med en Catenda-konto. Konfigurasjonen av applikasjonen kan vises i området "Dine applikasjoner". Med en konfigurert applikasjon er dette hvor følgende innstillinger finner du:

_Applikasjonsnavn_ Navnet på applikasjonen. Dette navnet konfigureres av Catenda. For å endre navnet på applikasjonen din, kontakt oss.

_Klient-ID_ Klient-ID-en til applikasjonen. Hver applikasjon har en unik ID som ikke kan endres.

_Klienthemlighet_ Passordet til applikasjonen. Hver applikasjon har et unikt passord som ikke kan endres.

_Omadresseringsadresse_ URL-en som applikasjonen vil omadressere tilgangskoder til når en forespørsel sendes med den riktige klienthemmeligheten og klient-ID-en. For å motta en tilgangskode på riktig måte, må URL-en i forespørselen samsvare med URL-en som er konfigurert her.

### 4.2 **Applikasjoner med tilgang til kontoen din**

Applikasjoner som har fått tilgang til kontoen vises. Klikk [her](https://support.catenda.com/en/articles/8396532-catenda-connections) for å se hvilke applikasjoner som kan kobles til.

_Tilbakekall tilgang_ Klikk på tilbakekall tilgang for å tilbakekalle tilgangen som ble gitt til den applikasjonen. Etter dette må tilgangen gis igjen for å fortsette å bruke den applikasjonen med denne kontoen. Avhengig av applikasjonen kan den spørre brukeren om å gi tilgang igjen eller den kan gi en feil og ikke spørre om ny tilgang. Det å logge ut og inn igjen tilbakestiller ofte koblingen i dette tilfellet.
