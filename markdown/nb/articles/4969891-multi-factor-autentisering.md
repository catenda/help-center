# Multi Factor Autentisering

Du vil kunne finne **Multi Factor autentisering** (MFA) innstillinger på [autentiserings siden](https://support.catenda.com/nb/articles/6880968-konto-siden#h_76f92e4ed6) som er en underside til konto [konto siden](https://support.catenda.com/nb/articles/6880968-konto-siden).

**Multi Factor autentisering** (MFA) kerver at en kode føres inn som du mottar via din mobile enhet i tillegg til ditt brukernavn og passord ved pålogging til Catenda Hub. Når en organisasjon påkrever MFA er det dette påført på et organisasjonsnivå. Alle prosjekter som tilhører organisasjonen vil da kreve MFA tilgang til deres prosjekt. Dette vil tvinge alle brukere til å koble på MFA for å få tilgang til prosjektene som tilhører organisasjonen.

Denne siden inneholder informasjon om følgende temaer:

## 1. **Koble på MFA**

Logg på Catenda Hub og gå til [konto siden](https://hub.catenda.com/account/profile):

![](https://downloads.intercomcdn.com/i/o/710942054/f2239e2186f2107afadd66a3/image.png?expires=1781092800&signature=f38bc42351fd302ec7396fa6cf12192e80e28a0d7f3432cf1ef011332c36b874&req=cyEnH818nYRbFb4V1XW4gc7BaZEBKtWdCLphfgCiOK%2Bew%2FThhA88vrm%2FPJq5%0APAs7mDo6nKHLBwYjCUY3Kyp9%2Bg%3D%3D%0A)

1. Klikk på [Autentiserings undersiden](https://support.catenda.com/nb/articles/6880968-konto-siden#h_76f92e4ed6):
1. Scroll ned til MFA dalen
1. Klikk på **Aktiver MFA**

![](https://downloads.intercomcdn.com/i/o/710944230/ebe37c5fb2379afe1d58d515/image.png?expires=1781092800&signature=bb1b215bf932a3da6fd9efd65031aa089830c4fa92090872b305802d5370aa61&req=cyEnH816n4JfFb4V1XW4gTVsh%2FWNq4RWV4OD%2BiH2LjOrUp6WWcpjxhq9folB%0A%2BuwHJKhvj1SGgt1qEKhqKE8VEQ%3D%3D%0A)

### 1.1 **Autentiseringsapp**

Du vil måtte installere en autentiseringspapp som du stoler på på din mobile enhet.

Vi anbefaler [Google Authenticator](https://support.google.com/accounts/answer/1066447?co=GENIE.Platform%3DAndroid&hl=en) og [Microsoft Authenticator](https://www.microsoft.com/en-us/account/authenticator) appene men du kan teoretisk bruke enhver applikasjon som støtter påkobling av MFA / Two factor authentication

**App tilganger**

For å kunne scanne QR koden med ditt kamera vil du måtte gi din autentiseringsapp tilgang til kameraet op din enhet.

Når du installerer applikasjonen vil du bli spurt om du ønsker å gi kameratilganger bare når du bruker appen, spør hver gang eller ikke tillat.

Hvis du valgte spør hver gang vil du bli spurt for tilgang hver gang hvor du kan si ikke tillat som skrur av tilgangen for appen.

**Google Authenticator**

Klikk på pluss knappen nederst til høyre og Scan en QR code.

Her vil du scanne QR konden som [autentiseringssiden](https://support.catenda.com/nb/articles/6880968-konto-siden#h_76f92e4ed6) gir deg.

Alternativt kan du bruke kameraet for å scanne koden og skrive inn setup key som du ser i URL som åpnes.

**Microsoft Authenticator**

Pass på at du er på Authenticator menyen nederst.

![](https://downloads.intercomcdn.com/i/o/825376957/d0ca2f4ff3122f26c2dd335e/image.png?expires=1781092800&signature=be1fcb59fb1bfa4b45e2cd97b6ea4639f51a97ac61ba103a8b19816235d2ee72&req=fCIiFc54lIRYFb4V1XW4gStU4QZFJuspH3Amx6IfbI1PH8Ta9AUUSD4f5PCO%0AAP4KnLWAE5JAwe0UK5S1t71eeA%3D%3D%0A)

> **Merk:** Pass på at du ikke er i Verified IDs menyen etter som du kan scanne en qr kode her men dette vil ikke fungere.

Videre, klikk på pluss knappen i den blåe bjelken øverst til høyre.

Selecter Other account (Google, Facebook, etc.)

Hvis din app ikke har tilganger til ditt kamera kan det hende at du blir spurt om å gi tilgang til ditt kamera.

Hvis din app har tilgang til ditt kamera kan du scanne QR koden som [autentiseringssiden](https://support.catenda.com/nb/articles/6880968-konto-siden#h_76f92e4ed6) gir deg.

Hvis appen ikke har tilgang til ditt kamera vil du bli spurt om å manuelt lage en konto.

![](https://downloads.intercomcdn.com/i/o/1073587443/5a6dda006a38943a4c11fc28/image.png?expires=1781092800&signature=6859b1a2a4081eacf5fe3e3b2cbc8cbc20fe23ba599c13b94523c6aef1a0d697&req=dSAgFcx2moVbWvMW3nq%2BgQ2uGk1EdfhU4hASnzRRD%2FCNPzlrB1T21b5PfCNs%0AoaOKhDzf4%2BW06huquS6IL07Iqqg%3D%0A)

Account name: Navnet du gir til kontoen

Secret key: Dette er nøkkelen di ville ha fårtt hvis du hadde scannet QR koden. Du kan bruke din kamera app for å scanne koden.

URL som åpner opp når du scanner koden kan se ut noe som dette: `otpauth://totp/\<Catenda konto epost addresse>?secret=\<hemmelig næøkkel>&issuer=Catenda&algorithm=SHA1&digits=6&period=30`

Skriver inn koden etter "`secret=`" i URL som åpnes i secret key feltet.

Kontonavn kan være hva du ønsker.

> **Merk:** Hvis du oppretter konto med feil hemmelig nøkkel vil appen lage engangspassord uansett så det kan hende Catenda ikke godtar koden hvis feil hemmelig nøkkel var brukt.

### 1.2 **Suksess eller feil**

**Suksess**

Etter at MFA koblingen er vellykket vil du se denne meldingen.

![](https://downloads.intercomcdn.com/i/o/areracg3/1278990979/c59adcb79ff50b83d8033567012f/image.png?expires=1781092800&signature=182c90e3d25c9d878c8438ca7666966d4526d30e07f659db14a7b04c70bbd115&req=dSIgHsB3nYhYUPMW3nq%2BgUqszxpod5dyIKfEaYTXklFljinW%2FXJpI%2BKOEkSH%0ARboyWe4asviqZJzxnej60YXmMNg%3D%0A)

Så snart den er koblet vil du måtte ha din mobile enhet tilgjengelig hver gang du ønsker å logge inn på Catenda Hub.

MFA kan skrus av igjen ved å klikke på Deaktiver MFA.

**Feil kode**

Om du ikke la inn riktig kode vil du få meldingen feil kode.

![](https://downloads.intercomcdn.com/i/o/areracg3/1278990977/a32126255de11e5dd081dbb2cd14/image.png?expires=1781092800&signature=399eb9649bed8ecc9bcc0dbb74ca49b0e0e17f80b348b27e156e93dd4e770a53&req=dSIgHsB3nYhYXvMW3nq%2BgXKvkZmZ9xp11h1Ky4RZuL2n58N9AFZ3OwKMnsJT%0ARn0aT7hlHvyeH%2F%2FKkbwScV4CNro%3D%0A)

> **Merk:** Om du har scannet QR-Koden kan du forsøke å skrive inn koden innen det gitte tidsrammet for koden igjen mens du har denne menyen åpent. Hvis du lukker menyen vil du måtte fjerne koden som genereres i din autentiseringsapp og scanne QR-Koden på nytt for å sette opp en ny kode kobling.

## 2. **Endre MFA**

Etter å ha koblet på en MFA kode kan du på en sikker måte rediger kontonavn til koen.

Du kan gjøre dette på følgende måter:

**Google authenticator**

1. Hold inn koden
1. Klikk på blyanten øverst til høyre for å endre navnet.

**Microsoft authenticator**

1. Klikk på koden.
1. Klikk på tannhjulknappen øverst til høyre.
1. Klikk på blyanten for å endre navnet.

## 3. **Overføre MFA**

**Deaktivere og reaktivere**

Det er bare mulig å bruke en MFA app kode kobling av gangen.

Hvis du ønsker å bytte til en forskjellige kode kobling, kanskjer fordi din gjeldende er kompromittert, kan du følge disse steg:

Du kan også bruke denne metoden hvis du ønsker å endre appen du bruker for MFA.

1. Deaktiver din MFA på [autentiseringssiden](https://support.catenda.com/nb/articles/6880968-konto-siden#h_76f92e4ed6)
1. Gjør klar appen du ønsker å bruke for å koble på din MFA
1. Generer en ny kode-kobling ved å scanne QR koden som i [påkoblingsavsnittet](#h_213609947a).

> **Merk:** Være forsiktig med denne metoden etter som din konto midlertidig vil være sårbar mens den er deaktivert og du vil ikke ha tilgang til prosjekter hvor MFA er påkrevd under denne tiden.

**Overføre gjennom backup**

Hvis du ønsker å starte å bruke en ny enhet uten at din kode midlertidig blir frakoblit kan du buke en annen installasjon til MFA appen og overføre koden fra den gamle installasjonen til den nye installasjonen.

**Google authenticator**

Gammel enhet:

1. Tapp på aksjonsmenyen øverst til høyre
1. Tapp på Export accounts
1. Selekter kontoene du ønsker å eksportere

Ny enhet:

1. Tapp på aksjonsmenyen øverst til høyre
1. Tapp på importer kontoer
1. Tapp på scan QR kode
1. Scan QR koden som er vist på den ganle enheten hvor du gikk gjennom eksporteringsprosessen.

**Microsoft authenticator**

Gammel enhet:

1. Tapp aksjonsmenyen øverst til høyre
1. Skru på backup

Ny enhet:

1. Installer og åpne Microsoft Autentiseringsappen på din nye enhet.
1. Tapp "Begin Recovery."

> **Merk 1:** Still ikke inn noen konto ved å bruke Microsoft Authenticator til etter at du har brukt Recovery tool siden det bare vil overskrive eksisterende kontoer.

> **Merk 2:** Denne metoden krever at du lager en backup av dine MFA koder som betyr at de er lagre ti din app leverandørs skytjeneste. Bare bruk denne metoden hvis du stoler på din app leverandørs skytjeneste. Hvis ikke er det bedre å deaktivere og reaktivere.

## 4. **Koble av MFA**

Du kan koble av MFA ved å klikke på Deaktiver kanppen vist over, for å så skrive inn ditt passord og godta. Etter å ha koblet av vil du ikke lenger ha tilgang til prosjekter som krever MFA.

Etter å ha koblet av koden på Catenda Hub vil koden bli igjen på applikasjonen du koblet med. Denne koden vil nå være ubrukelig og kan slettes med sikkerhet.

### 4.1 **Hvordan å slette den gamle koden:**

**Google authenticator**

1. Hold inn koden
1. Klikk på søppelikonet øverst til høyre.

**Microsoft authenticator**

1. Klikk på koden.
1. Klikk på tannhjulsknappen øverst til høyre.
1. Klikk på fjern konto

## 5. **MFA på ikke-mobile enheger**

Autentiseringskonto er mer sikre enn SMS/E-post kode løsninger siden det ikke er kommunikasjon som kan lekke ut i kommunikasjonen mellom to systemer etter den originale konfigurasjonen.

Siden det er bedre å bruke en app på en mobil applikasjon, se notatet under, er det mulig å få MFA koder på andre system enn bare mobile enheter.

Den anbefalte desktop applikasjonen for dette er [Authy](https://authy.com/).

Funksjonsmessig bruker disse typer applikasjoner samme TOTP protokoll som appen på din mobile enhet og bør være like sikre.

> **Merk:** Desktop applikasjoner kan være mindre sikkert ettter som de kan være letter å hacke eller få tilgang til. Dette er fordi dekstop systemer ofte, hvis ikke alltid, er koblet på det lokale nettverket som kan være infisert. Mobile enheter som ikke llatid er koblet på nettverket kan derfor være vanskeligere å komme inn på.

## 6. **Hvem kan påkreve MFA på prosjekt?**

Enterprise kunder kan be om at [organisasjonsvalget](https://support.catenda.com/nb/articles/8224886-organisasjonsvalg#h_aab0a5f0fa) for MFA skrus på. Dette valget gjør at alle brukere som er del av deres prosjekt må bruke MFA for å komme inn på prosjektet.

For å skru på MFA for din organisasjon sine prosjekter, kontakt Catenda support. Når MFA er påkrevd for prosjektene til en organisasjon vil du se denne meldingen ved et forsøk på å åpne prosjektet.

![](https://downloads.intercomcdn.com/i/o/710237963/cc33c301cac2faaeaf8abb7e/image.png?expires=1781092800&signature=0a241c1b7d754dac6ac7f3fbfb908a97d6aad26a98db0773434988edd6c61515&req=cyEnFMp5lIdcFb4V1XW4geDBTPE7FEI38r7z7CIHG0OMPqmboH9ClY59uD%2F2%0APKhzmnNJ76NXpaOhL%2BVeRBzIhw%3D%3D%0A)
