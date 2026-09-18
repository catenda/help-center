# Flerfaktor-autentisering

> Beskriver hvordan du konfigurerer MFA på kontoen din

Du finner **Flerfaktor-autentisering** (MFA)-innstillingene på [autentiseringssiden](https://support.catenda.com/en/articles/6880968-account-page#h_e04d63351f), som er en underside til [kontosiden](https://support.catenda.com/en/articles/6880968-account-page).

**Flerfaktor-autentisering** (MFA) krever at du angir en kode mottatt via mobilenheten din i tillegg til brukernavn og passord når du logger på Catenda Hub. Når en organisasjon krever MFA, brukes det på organisasjonsnivå. Alle prosjekter som tilhører den organisasjonen, vil da kreve MFA for å få tilgang til prosjektene. Dette tvinger alle brukere til å aktivere MFA for å få tilgang til prosjekter som tilhører den organisasjonen.

## 1. **Aktivering av MFA**

Logg inn på Catenda Hub og gå til **[Konto](https://hub.catenda.com/account/profile)**-siden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/01-enabling-mfa.png)

1. Klikk på **[Autentisering](https://hub.catenda.com/account/authentication)**-fanen:
1. Bla ned til delen for MFA:
1. Klikk på **Aktiver MFA**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/02-enabling-mfa.png)

### 1.1 **Autentiseringsapp**

For å komme i gang, installer en applikasjon på en mobilenhet som støtter TOTP-protokollen (Time-based one-time password). Installer en pålitelig autentiseringsapp på en mobilenhet for å komme i gang. Hvor lenge en autentiseringsapplikasjon har vært tilgjengelig, og jurisdiksjonen der selskapet som eier den er basert, er ofte gode ting å se på. Her er noen eksempler på anbefalte autentiseringsapplikasjoner:

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 139px; padding: 8px;"><h3 id="h_b56161ee38"><b>Sikkerhetslover for auth-apper</b></h3></td><td style="background-color: #e3e7fa80; width: 101px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_49bc31efe9">Selskap</h3></td><td style="background-color: #e3e7fa80; width: 119px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_46b679c81c">Jurisdiksjon</h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_7699fa4ab6">Sikkerhetslover som gjelder</h3></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_ae65255403">Aegis</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Beem</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Nederland<br/>(Dordrecht)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>GDPR<br/>9 eyes-avtale</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_42b556ff02">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Roland Moers</p></td><td style="background-color: #e8e8e880; width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Tyskland</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>GDPR<br/>Bundesdatenschutzgesetz - BDSG <br/>14 eyes-avtale</p></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_5e0c03d260">Autentisering</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Google</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>United States<br/>(California)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_918c12706e">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Microsoft</p></td><td style="background-color: #e8e8e880; width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>United States<br/>(Washington)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_b3a055f26d">Ente Auth</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ente</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>United States (Delaware)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_63d03979d2">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Internet Initiative Japan</p></td><td style="background-color: #e8e8e880; width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Japan</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Act on the Protection of Personal Information (APPI)</p></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_848afb2dfa">HENNGE Lock</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>HENNGE K.K.</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Japan</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Act on the Protection of Personal Information (APPI)</p></td></tr></tbody></table></div>

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 138px; padding: 8px;"><h3 id="h_5e28bb0eb3"><b>Autentiseringsapp-funksjonalitet</b></h3></td><td style="background-color: #e3e7fa80; width: 88px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_6ed7d3e230">Utgivelsesdato</h3></td><td style="background-color: #e3e7fa80; width: 180px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_f652151c66">Operativsystem</h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_824368384e">Kodeuttak</h3></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_218c61c8b2">Aegis</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2019</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Android</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Eksporter til fullt klartekst eller kryptert fil. JSON / TXT / QR</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_0274ada2cb">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2020</p></td><td style="background-color: #e8e8e880; width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Eksporter til proprietær fil / Vis hemmelighet</p></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_cc8ae8a27d">Autentisering</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2010</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS<br/>Android</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Overfør til annen Google Authenticator-app med Google-konto</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_6d595cbd69">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS<br/>Android</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Overfør til annen Microsoft Authenticator-app med Microsoft-konto.</p></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_9cbe3f20d2">Ente Auth</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2020</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS<br/>Android</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>JSON / TXT</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_425ee9cdba">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS - 8.1+<br/>Android - 4.0+</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>QR-kodeeksport per kode.</p></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_10c8930b4e">HENNGE Lock</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2020</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS - Siste 2 hovedversjoner <br/>Android - siste 4 navngitte versjoner</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ingen</p></td></tr></tbody></table></div>

Teoretisk sett kan enhver applikasjon som støtter MFA / To-faktors autentisering via TOTP-protokollen brukes. Det finnes til og med skrivebordsprogrammer, men disse anbefales ikke fordi skrivebordsprogrammer ofte er alltid tilkoblet samme nettverk, som ofte har flere enheter på det, noe som øker risikoen for at en dårlig aktør får tilgang til koden.

_Apptillatelser_ For at du skal kunne skanne QR-koden med kameraet på enheten, må autentiseringsappen ha kameratillatelser for å kunne skanne koden. Applikasjonen kan be om tillatelse til å bruke enhetsens kamera. Tillatelses alternativer kan omfatte: "Kun mens du bruker appen" - Appen har tillatelse mens den er i bruk. "Spør hver gang" - Tillatelse må gis ved hver bruk av appen. "Ikke tillatt" - Tillatelse er ikke gitt eller tilbakekalt fra appen.

_Google Authenticator_ Klikk på plusstegnet nederst til høyre og skann en QR-kode. Her skal du skanne QR-koden som [autentiseringssiden](https://hub.catenda.com/account/authentication) gir deg. Alternativt kan du bruke kameraet ditt til å skanne koden og skrive inn oppsettnøkkelen som du ser i nettadressen som åpnes.

_Microsoft Authenticator_ Kontroller at du er i Authenticator-menyen nederst.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/03-authentication-app.png)

> **Merk:** Sørg for at du ikke er i Verified IDs-menyen, da du kan skanne en QR-kode her, men det vil ikke fungere.

Klikk deretter på plusstegnet i det blå feltet øverst til høyre. Velg Annen konto (Google, Facebook osv.) Hvis appen din ikke har tillatelse til kameraet ditt, kan det hende eller ikke at du blir bedt om å gi tillatelse til kameraet ditt.

Hvis appen din har tilgang til kameraet ditt, kan du skanne QR-koden som [autentiseringssiden](https://hub.catenda.com/account/authentication) gir deg.

Hvis appen din ikke har tilgang til kameraet ditt, blir du bedt om å opprette en konto manuelt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/04-authentication-app.png)

Kontonavn: Navnet du gir kontoen din Hemmelig nøkkel: Dette er nøkkelen du ville ha fått hvis du hadde kunnet skanne QR-koden. Du kan bruke kameraappen din til å skanne koden. Nettadressen som åpnes når du skanner koden, kan se slik ut: `otpauth://totp/<Catenda account email address>?secret=<Secret key>&issuer=Catenda&algorithm=SHA1&digits=6&period=30` Hvis du skriver inn koden etter "`secret=`" i den hemmelige nøkkelen som du ser i nettadressen som åpnes, kan kontonavn være hva som helst.

> **Merk:** Hvis du oppretter en konto med feil hemmelig nøkkel, vil appen generere engangspassord likevel, så Catenda kan ikke akseptere koden hvis feil hemmelig nøkkel ble brukt.

### 1.2 **Suksess eller feil**

_Suksess_ Etter at du har aktivert MFA, vil du se denne meldingen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/05-success-or-fail.png)

Når det er aktivert, må du ha mobilenheten din til stede hver gang du logger på Catenda Hub. MFA kan deaktiveres igjen ved å klikke på Deaktiver MFA.

_Feil kode_ Hvis du ikke skrev inn riktig kode, får du meldingen feil kode.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/06-success-or-fail.png)

> **Merk:** Hvis du har skannet QR-koden, kan du prøve å skrive inn koden innenfor den gitte tidsrammen for den koden mens du har denne menyen åpen. Hvis du lukker denne menyen, må du fjerne koden som genereres i autentiseringsappen din og skanne QR-koden igjen for å konfigurere en ny kodeparring.

## 2. **Endring av MFA**

Etter at du har koblet til en MFA-kode, kan du trygt redigere kontonavnet på koden. Du kan gjøre det på følgende måter:

_Google Authenticator_

1. Langtast på koden
1. Klikk på blyanten øverst til høyre for å endre navnet.

_Microsoft Authenticator_

1. Klikk på koden.
1. Klikk på tannhjulet øverst til høyre
1. Klikk på blyanten for å endre navnet

## 3. **Overføring av MFA**

_Deaktivering og reaktivering_ Det er bare mulig å bruke en MFA-apkkodeparring om gangen. Hvis du ønsker å bytte til en annen kodeparring, kanskje fordi din nåværende er kompromittert, følger du disse trinnene: Du bør også bruke denne metoden hvis du ønsker å endre appen du bruker for MFA.

1. Deaktiver MFA din på [autentiseringssiden](https://hub.catenda.com/account/authentication)
1. Forbered appen du vil bruke for å gjenopprette MFA-en din
1. Generer et nytt kodeparpar ved å skanne QR-koden som i [aktiveringsdelen](#h_9e13fd06f5)

> **Merk:** Vær forsiktig med denne metoden fordi kontoen din blir midlertidig sårbar mens den er deaktivert, og du vil ikke kunne få tilgang til prosjekter hvor MFA kreves i løpet av denne tiden.

_Overføring via sikkerhetskopi_ Hvis du ønsker å begynne å bruke en ny enhet uten at koden blir midlertidig deaktivert, kan du bruke en annen installasjon av samme MFA-app og overføre koden fra den gamle installasjonen til den nye installasjonen.

_Google authenticator_ Gammel enhet:

1. Trykk på hamburger-menyen øverst til høyre
1. Trykk på Eksporter kontoer
1. Velg kontiene du ønsker å eksportere

Ny enhet:

1. Trykk på hamburger-menyen øverst til høyre
1. Trykk på importer kontoer
1. Trykk på skann QR-kode
1. Skann QR-koden som vises på den gamle enheten når du gikk gjennom eksportprosessen.

_Microsoft authenticator_ Gammel enhet:

1. Trykk på hamburger-menyen øverst til høyre
1. Slå på sikkerhetskopi

Ny enhet:

1. Installer og åpne Microsoft Authenticator-appen på den nye enheten din
1. Trykk på "Begynn gjenoppretting."

> **Merk 1:** Ikke konfigurer noen kontoer med Microsoft Authenticator før du har brukt gjenopprettingsverktøyet, fordi det vil overskrive matchende nettstedkontoer.

> **Merk 2:** Denne metoden krever at du sikkerhetskopier MFA-kodene dine, noe som betyr at de lagres i sikkerhetskopieringstjenesten til appleverandøren din. Bruk bare denne metoden hvis du stoler på sikkerhetskopieringstjenesten til appleverandøren din. Hvis ikke er du bedre tjent med å deaktivere og reaktivere.

## 4. **Deaktivering av MFA**

Du kan deaktivere MFA ved å klikke på deaktiver-knappen som vises ovenfor, og deretter skrive inn passordet ditt for å bekrefte. Etter deaktivering kan du ikke lenger få tilgang til prosjekter som krever MFA.

Etter at du har deaktivert koden på Catenda Hub, vil koden forbli på applikasjonen som du koblet til. Denne koden vil nå være ubrukelig og kan slettes trygt.

### 4.1 **Hvordan slette den gamle koden:**

_Google Authenticator_

1. Langtast på koden
1. Klikk på søppelikonen øverst til høyre.

_Microsoft Authenticator_

1. Klikk på koden.
1. Klikk på tannhjulet øverst til høyre
1. Klikk på fjern konto

## 5. **MFA på enheter uten mobil**

Autentiseringsapper er sikrere enn SMS/E-post-koderesolninger fordi det ikke finnes kommunikasjon som kan avskjæres mellom de to systemene etter den opprinnelige konfigurasjonen. Selv om det er bedre å bruke en app på en mobilapplikasjon, se notat nedenfor, er det mulig å få MFA-koder på andre systemer enn bare mobilenheter. Den anbefalte skrivebordapplikasjonen for dette er [Authy](https://authy.com/). Funksjonelt bruker disse typene applikasjoner samme TOTP-protokoll som appen på mobilenheten din og skal være like sikre.

> **Advarsel:** Skrivebordapper kan være mindre sikre fordi de kan være lettere å hacke eller få tilgang til. Dette er fordi stasjonære systemer ofte, om ikke alltid, er koblet til det lokale nettverket som kan være infisert. Mobilenheter som ikke alltid er tilkoblet nettverket, kan derfor være vanskeligere å få tilgang til.

## 6. **Hvem kan håndheve MFA på prosjekter?**

Enterprise-kunder kan be om et [organisasjonsalternativ](https://support.catenda.com/en/articles/8224886-organization-options#h_d6710faf75) som skal slås på, som gjør at alle brukere som er del av prosjektene deres må bruke MFA for å gå inn i prosjektet. For å aktivere MFA på organisasjonens prosjekter, ta kontakt med Catenda-støtte. Når MFA kreves på organisasjonens prosjekter, vil du se denne meldingen når du forsøker å åpne prosjektet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/07-who-can-enforce-mfa-on-projects.png)
