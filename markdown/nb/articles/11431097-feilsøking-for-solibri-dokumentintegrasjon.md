# Feilsøking for Solibri-dokumentintegrasjon

Feil som kan oppstå med Solibri-dokumentintegrasjonen og hvordan du løser dem, er forklart i denne artikkelen.

## 1. **Kontotilkobling og tilgang**

### 1.1 **Logg av under last opp/ned ikke anbefalt**

Det er mulig å logge av fra kontoen din i dokumentvalgsmenyen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/01-signing-out-during-up-download-not-recommended.png)

Hvis du logger av her og logger på igjen, vil siden se slik ut i stedet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/02-signing-out-during-up-download-not-recommended.png)

Selv om du kan få tilgang til en annen Catenda-konto enn den du har gitt tilgang til på denne måten, anbefales det ikke. Tilgang vil ikke ha blitt gitt for den kontoen, og alle modeller eller dokumenter du navigerer til, vil ikke bli importert til Solibri.

### 1.2 **Last opp -** Ingen tilgang til dokument

Hvis du prøver å laste opp smc-filen din til en revisjon du ikke har tilgang til, vil du se følgende advarsel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/03-upload-no-access-to-document.png)

I denne situasjonen ber du om at en prosjektadministrator gir deg tilgang til dokumentet.

### 1.3 **Last opp -** Ingen tilgang til mappe

Hvis du prøver å opprette et nytt dokument i en mappe der du bare har leseatkomst, vil du se følgende melding.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/04-upload-no-access-to-folder.png)

I denne situasjonen ber du om at en prosjektadministrator gir deg minst skriveatkomst til mappen.

### 1.4 **Tilbakekall tilgang til Catenda-kontoen din**

Gå til programmers side i Catenda Hub [kontoinnstillinger](https://intercom.help/bimsync-arena/en/articles/6880968-account-settings#:~:text=your%20notification%20settings.-,Applications,-In%20applications%20you), finn Solibri-programmet og klikk på tilbakekall.

### 1.5 **Koble fra Catenda-serveren**

Hvis du ikke lenger ønsker å koble til Catenda-serveren, klikker du på koble fra.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/05-disconnect-from-the-catenda-server.png)

Etter frakobling vil Solibri fortsatt ha tilgang til kontoen din. Hvis du ønsker å koble til igjen senere, trenger du ikke å autentisere på nytt.

### 1.6 **Koble til med ny konto**

I følgende situasjoner kan det hjelpe å koble til med en ny konto:

- Tilgangen til kontoen din er blitt tilbakekalt.
- Gir tilgang til en annen konto.
- Tilbakestille tilkoblingen hvis den har sluttet å fungere

Den gamle kontoen kan kobles fra på følgende måter:

### 1.7 **Tilbakekall tilgang på Catenda**

For å tilbakekalle tilgangen som Solibri ble gitt til en konto, logger du inn med kontoen på Catenda. Etter at du har logget inn, går du til programmers side [https://hub.catenda.com/account/apps](https://hub.catenda.com/account/apps) Hvis Solibri ble gitt tilgang til denne kontoen, vil du se Solibri i listen over programmer med tilgang til kontoen. Klikk på tilbakekall tilgang. Hvis Solibri ble koblet til denne kontoen, vil det be brukeren om å gi tilgang til en ny konto.

### 1.8 **Slett .solibri-mappe**

En annen måte å fjerne tilkoblingen til en Catenda-konto på er ved å slette brukerdata i Solibri. For å gjøre det sletter du mappen som ligger her:

`C:\Users\<Username>\.solibri`

> **Merk:** Som standard er dette en skjult mappe på systemet ditt. Skriv banen direkte i filutforskeren din eller finn ut hvordan du viser skjulte mapper her: [https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5](https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5)

Solibri-påloggingsdataene lagres i denne mappen, så Solibri må logges inn på nytt neste gang det åpnes.

## 2. **Last opp**

### 2.1 **Forespurt dokument ikke funnet**

Hvis du har åpnet .smc-filen din fra Catenda, vil plasseringen i prosjektet du åpnet den fra bli husket. Når du senere laster opp .smc-filen på nytt til Catenda og enten dokumentet er blitt flyttet eller finnes ikke i prosjektet du har navigert til, vil du se følgende melding.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/06-requested-document-not-found.png)

### 2.2 **Ingen ny revisjon**

Hvis du har åpnet en .smc fra Catenda og laster den opp igjen til Catenda uten å gjøre noen endringer, selv om du har lagret smc-filen et sted, blir du ikke bedt om å lagre den først, og det vil se ut som om den blir lastet opp. Etter opplasting vil du få følgende melding som forventet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/07-no-new-revision.png)

Hvis filen din hadde samme navn som et dokument i mappen, vil du se at ingen ny revisjon blir lagt til det dokumentet i Catenda. Prøv å laste opp .smc-filen din på nytt hvis dette er tilfellet.

### 2.3 **Nytt dokument i stedet for ny revisjon**

Hvis filen din hadde et annet navn, men du valgte et dokument som revisjonen skulle lastes opp til, vil du se at et nytt dokument blir opprettet basert på filnavnet ditt, og filen din vil ikke være en ny revisjon av dokumentet. Kontroller at filen din har samme navn som dokumentet hvis du vil at det skal bli en ny revisjon av det dokumentet og ikke et nytt dokument.

### 2.4 **Knapp ikke tilgjengelig**

Hvis du prøver å laste opp dokumenter, kan du se meldingen om at ingen filer er valgt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/08-button-not-available.png)

Dette kan være tilfellet når du har gitt Solibri tilgang til Catenda med en konto, men prøver å laste opp en .smc-fil med en annen konto. For å gi tilgang til en annen konto, se [her](#h_0ef63a37db).

## 3. **Last ned**

### 3.1 **Feil**

Hvis du har valgt et dokument, kan du se en feil i høyre meny.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/09-error.png)

Dette kan være tilfellet når du har gitt Solibri tilgang til Catenda med en konto, men prøver å laste ned dokumentet med en annen konto. For å gi tilgang til en annen konto, se [her](#h_0ef63a37db).

### 3.2 **Filtype ikke støttet**

Med dokumentintegrasjonen vil du etter å ha navigert til og valgt et dokument som ikke støttes på dokumentsiden i et prosjekt se følgende melding i høyre informasjonsmeny.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/10-filetype-not-supported.png)

Forsøk på å laste ned et dokument med en annen utvidelse vil ikke ha noen effekt.

### 3.3 **Ingenting skjer**

Kontoen du er logget inn med, er annerledes enn kontoen du har gitt tilgang for.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ah50b5kr/11-nothing-happens.png)
