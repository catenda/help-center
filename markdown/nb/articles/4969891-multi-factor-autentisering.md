# Flerfaktorgodkjenning

> Beskriver hvordan du setter opp MFA på kontoen din

Du finner innstillingene for **Flerfaktorgodkjenning** (MFA) på [godkjenningssiden](https://support.catenda.com/en/articles/6880968-account-page#h_e04d63351f), som er en underside til [kontosiden](https://support.catenda.com/en/articles/6880968-account-page).

**Flerfaktorgodkjenning** (MFA) krever at du skriver inn en kode du mottar på mobilenheten din, samt brukernavnet og passordet ditt når du logger på Catenda Hub. Når en organisasjon krever MFA, blir det brukt på organisasjonsnivå. Alle prosjekter som tilhører denne organisasjonen vil deretter kreve MFA for å få tilgang til deres prosjekter. Dette vil tvinge alle brukere til å aktivere MFA for å få tilgang til prosjekter som tilhører denne organisasjonen.

## 1. **Aktivering av MFA**

Logg på Catenda Hub og gå til siden for **[Konto](https://hub.catenda.com/account/profile)**:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/01-enabling-mfa.png)

1. Klikk på fanen **[Godkjenning](https://hub.catenda.com/account/authentication)**:
2. Rull ned til delen for MFA:
3. Klikk på **Aktivere MFA**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/02-enabling-mfa.png)

### 1.1 **Godkjenningsapp**

For å komme i gang, installer en applikasjon på en mobilenhet som støtter TOTP-protokollen (Time-based one-time password). Installer en pålitelig godkjenningsapp på en mobilenhet for å komme i gang. Hvor lenge en godkjenningsapplikasjon har vært i bruk og jurisdiksjonen der selskapet som eier den er basert, er ofte gode ting å vurdere. Her er noen eksempler på anbefalte godkjenningsapplikasjoner:

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 139px;"><h3 id="h_b56161ee38"><b>Godkjenningsappens sikkerhetslover</b></h3></td><td style="background-color: #e3e7fa80; width: 101px;"><h3 id="h_49bc31efe9">Selskap</h3></td><td style="background-color: #e3e7fa80; width: 119px;"><h3 id="h_46b679c81c">Jurisdiksjon</h3></td><td style="background-color: #e3e7fa80;"><h3 id="h_7699fa4ab6">Sikkerhetslover som gjelder</h3></td></tr><tr><td style="width: 139px;"><h3 id="h_ae65255403">Aegis</h3></td><td style="width: 101px;"><p>Beem</p></td><td style="width: 119px;"><p>Nederland<br/>(Dordrecht)</p></td><td><p>GDPR<br/>Avtale med 9 øyne</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_42b556ff02">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Roland Moers</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Tyskland</p></td><td style="background-color: #e8e8e880;"><p>GDPR<br/>Bundesdatenschutzgesetz - BDSG <br/>Avtale med 14 øyne</p></td></tr><tr><td style="width: 139px;"><h3 id="h_5e0c03d260">Godkjenner</h3></td><td style="width: 101px;"><p>Google</p></td><td style="width: 119px;"><p>USA<br/>(California)</p></td><td><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_918c12706e">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Microsoft</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>USA<br/>(Washington)</p></td><td style="background-color: #e8e8e880;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="width: 139px;"><h3 id="h_b3a055f26d">Ente Auth</h3></td><td style="width: 101px;"><p>Ente</p></td><td style="width: 119px;"><p>USA (Delaware)</p></td><td><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_63d03979d2">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Internet Initiative Japan</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Japan</p></td><td style="background-color: #e8e8e880;"><p>Lov om beskyttelse av personopplysninger (APPI)</p></td></tr><tr><td style="width: 139px;"><h3 id="h_848afb2dfa">HENNGE Lock</h3></td><td style="width: 101px;"><p>HENNGE K.K.</p></td><td style="width: 119px;"><p>Japan</p></td><td><p>Lov om beskyttelse av personopplysninger (APPI)</p></td></tr></tbody></table></div>

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 138px;"><h3 id="h_5e28bb0eb3"><b>Godkjenningsappens funksjonalitet</b></h3></td><td style="background-color: #e3e7fa80; width: 88px;"><h3 id="h_6ed7d3e230">Utgivelsesdato</h3></td><td style="background-color: #e3e7fa80; width: 180px;"><h3 id="h_f652151c66">Operativsystem</h3></td><td style="background-color: #e3e7fa80;"><h3 id="h_824368384e">Kodeekstraksjon</h3></td></tr><tr><td style="width: 138px;"><h3 id="h_218c61c8b2">Aegis</h3></td><td style="width: 88px;"><p>2019</p></td><td style="width: 180px;"><p>Android</p></td><td><p>Eksporter til Full Plaintext eller Encrypted file. JSON / TXT / QR</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_0274ada2cb">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2020</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS</p></td><td style="background-color: #e8e8e880;"><p>Eksporter til proprietær fil / Vis hemmelighet</p></td></tr><tr><td style="width: 138px;"><h3 id="h_cc8ae8a27d">Godkjenner</h3></td><td style="width: 88px;"><p>2010</p></td><td style="width: 180px;"><p>iOS<br/>Android</p></td><td><p>Overføring til annen Google Authenticator-app med Google-konto</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_6d595cbd69">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS<br/>Android</p></td><td style="background-color: #e8e8e880;"><p>Overføring til annen Microsoft Authenticator-app med Microsoft-konto.</p></td></tr><tr><td style="width: 138px;"><h3 id="h_9cbe3f20d2">Ente Auth</h3></td><td style="width: 88px;"><p>2020</p></td><td style="width: 180px;"><p>iOS<br/>Android</p></td><td><p>JSON / TXT</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_425ee9cdba">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS - 8.1+<br/>Android - 4.0+</p></td><td style="background-color: #e8e8e880;"><p>QR-kodeeksport per kode.</p></td></tr><tr><td style="width: 138px;"><h3 id="h_10c8930b4e">HENNGE Lock</h3></td><td style="width: 88px;"><p>2020</p></td><td style="width: 180px;"><p>iOS - Siste 2 hovedversjoner <br/>Android - siste 4 kodestykker</p></td><td><p>Ingen</p></td></tr></tbody></table></div>

Teoretisk sett kan enhver applikasjon som støtter MFA / Tofaktorgodkjenning via TOTP-protokollen brukes. Det finnes til og med stasjonærapplikasjoner, men disse anbefales ikke fordi stasjonærapplikasjoner ofte alltid er koblet til det samme nettverket, som ofte har flere enheter på seg, noe som øker risikoen for at en dårlig aktør får tilgang til koden.

_Apptillatelser_ For at du skal kunne skanne QR-koden med kameraet på enheten. Godkjenningsappen trenger kameratillatelser for å kunne skanne koden. Applikasjonen kan be om tillatelse til å bruke kameraet på enheten. Tillatselsesalternativer kan omfatte: "Bare mens du bruker appen" - Appen har tillatelse mens den er i bruk. "Spør hver gang" - Tillatelse må gis ved hver bruk av appen. "Tillat ikke" - Tillatelse er ikke gitt eller tilbakekalt fra appen.

_Google Authenticator_ Klikk på plusstegnet nederst til høyre og Scan en QR-kode. Her skal du skanne QR-koden som [godkjenningssiden](https://hub.catenda.com/account/authentication) gir deg. Alternativt kan du bruke kameraet ditt til å skanne koden og skrive inn oppsettnøkkelen som du ser i URL-en som åpnes.

_Microsoft Authenticator_ Kontroller at du er i Authenticator-menyen nederst.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/03-authentication-app.png)

> **Merk:** forsikre deg om at du ikke er i Verified IDs-menyen da du kan skanne en QR-kode her, men dette vil ikke fungere.

Klikk deretter på plusstegnet i den blå linjen øverst til høyre. Velg Annen konto (Google, Facebook, osv.) Hvis appen din ikke har tillatelse til kameraet ditt, kan du bli spurt om å gi tillatelse til kameraet ditt.

Hvis appen din har tilgang til kameraet ditt, kan du skanne QR-koden som [autentiseringssiden](https://hub.catenda.com/account/authentication) gir deg.

Hvis appen din ikke har tilgang til kameraet ditt, blir du bedt om å opprette en konto manuelt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/04-authentication-app.png)

Kontonavn: Navnet du gir til kontoen din Hemmelig nøkkel: Dette er nøkkelen du ville ha fått hvis du hadde kunnet skanne QR-koden. Du kan bruke kameraappen din til å skanne koden. URLen som åpnes når du skanner koden kan se omtrent slik ut: `otpauth://totp/<Catenda-kontoens e-postadresse>?secret=<Hemmelig nøkkel>&issuer=Catenda&algorithm=SHA1&digits=6&period=30` Hvis du skriver inn koden etter "`secret=`" i den hemmelige nøkkelen som du ser i URLen som åpnes, kan kontonavnet være hva som helst.

> **Merk:** Hvis du oppretter en konto med feil hemmelig nøkkel, vil appen fortsatt generere engangspasskoder, så Catenda godtar kanskje ikke koden hvis feil hemmelig nøkkel ble brukt.

### 1.2 **Suksess eller mislykking**

_Suksess_ Etter å ha aktivert MFA vil du se denne meldingen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/05-success-or-fail.png)

Når det er aktivert, må du ha mobilenheten din ved hånden hver gang du logger på Catenda Hub. MFA kan deaktiveres igjen ved å klikke på Deaktiver MFA.

_Feil kode_ Hvis du ikke skrev inn riktig kode, får du meldingen feil kode.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/06-success-or-fail.png)

> **Merk:** Hvis du har skannet QR-koden, kan du prøve å skrive inn koden innenfor tidsvinduet for denne koden mens du har denne menyen åpen. Hvis du lukker denne menyen, må du fjerne koden som genereres i autentiseringsappen din og skanne QR-koden igjen for å sette opp en ny kodekombinasjon.

## 2. **Modifisering av MFA**

Etter å ha koblet til en MFA-kode kan du trygt redigere kontonavnet på koden. Du kan gjøre dette på følgende måter:

_Google Authenticator_

1. Trykk lenge på koden
2. Klikk på blyanten øverst til høyre for å endre navn.

_Microsoft Authenticator_

1. Klikk på koden.
2. Klikk på tannhjulet øverst til høyre
3. Klikk på blyanten for å endre navn

## 3. **Overføring av MFA**

_Deaktivering og reaktivering_ Det er bare mulig å bruke én MFA-app-kodekombinasjon om gangen. Hvis du ønsker å bytte til en annen kodekombinasjon, kanskje fordi den nåværende har blitt kompromittert, følger du disse trinnene: Du bør også bruke denne metoden hvis du ønsker å endre appen du bruker for MFA.

1. Deaktiver MFA på [autentiseringssiden](https://hub.catenda.com/account/authentication)
2. Forbered appen du vil bruke for å koble til MFA på nytt
3. Generer en ny kodekombinasjon ved å skanne QR-koden som i [aktiveringsavsnittet](#enabling-mfa)

> **Merk:** Vær forsiktig med denne metoden da kontoen din vil være midlertidig sårbar mens den er deaktivert, og du vil ikke kunne få tilgang til prosjekter der MFA er påkrevd i løpet av denne tiden.

_Overføring via sikkerhetskopi_ Hvis du ønsker å begynne å bruke en ny enhet uten at koden din midlertidig blir deaktivert, kan du bruke en annen installasjon av samme MFA-app og overføre koden fra den gamle installasjonen til den nye installasjonen.

_Google Authenticator_ Gammel enhet:

1. Trykk på hamburgermenyene øverst til høyre
2. Trykk på Eksporter kontoer
3. Velg kontiene du vil eksportere

Ny enhet:

1. Trykk på hamburgermenyene øverst til høyre
2. Trykk på Importer kontoer
3. Trykk på Skann QR-kode
4. Skann QR-koden som vises på den gamle enheten når du gikk gjennom eksportprosessen.

_Microsoft Authenticator_ Gammel enhet:

1. Trykk på hamburgermenyene øverst til høyre
2. Slå på sikkerhetskopi

Ny enhet:

1. Installer og åpne Microsoft Authenticator-appen på den nye enheten din
2. Trykk på "Begin Recovery."

> **Merk 1:** Ikke sett opp noen kontoer ved hjelp av Microsoft Authenticator før du har brukt Gjenoppretting-verktøyet fordi det vil overskrive samsvarende nettstedkontoer.

> **Merk 2:** Denne metoden krever at du sikkerhetskopierer MFA-kodene dine, noe som betyr at de lagres i skyservice fra appleverandøren din. Bruk denne metoden bare hvis du stoler på sikkerhetskopiservicen til appleverandøren din. Hvis ikke er det bedre å deaktivere og reaktivere.

## 4. **Deaktivering av MFA**

Du kan deaktivere MFA ved å klikke på deaktiveringsknappen vist ovenfor, deretter skriver du inn passordet ditt for å bekrefte. Etter deaktivering vil du ikke lenger være i stand til å få tilgang til prosjekter som krever MFA.

Etter å ha deaktivert koden på Catenda Hub, vil koden forbli på applikasjonen du koblet til. Denne koden vil nå være ubrukelig og kan trygt slettes.

### 4.1 **Slik sletter du den gamle koden:**

_Google Authenticator_

1. Trykk lenge på koden
2. Klikk på søppelkassen øverst til høyre.

_Microsoft Authenticator_

1. Klikk på koden.
2. Klikk på tannhjulet øverst til høyre
3. Klikk på Fjern konto

## 5. **MFA på ikke-mobile enheter**

Autentiseringsapper er tryggere enn SMS/e-postkodelløsninger fordi det ikke er noen kommunikasjon som kan avskjæres mellom de to systemene etter den opprinnelige konfigurasjonen. Selv om det er bedre å bruke en app på en mobilapplikasjon, se merknaden nedenfor, det er mulig å få MFA-koder på andre systemer enn bare mobilenheter. Det anbefalte skrivebordsprogrammet for dette er [Authy](https://authy.com/). Funksjonelt bruker disse typer applikasjoner samme TOTP-protokoll som appen på mobilenheten din og bør være like sikker.

> **Advarsel:** Skrivebordapper kan være mindre sikre siden de kan være lettere å hacke eller få tilgang til. Dette er fordi skrivebordssystemer ofte, hvis ikke alltid, er koblet til det lokale nettverket som kan være infisert. Mobilenheter som ikke alltid er koblet til nettverket kan derfor være vanskeligere å få tilgang til.

## 6. **Hvem kan påtvinge MFA på prosjekter?**

Bedriftskunder kan be om at et [organisasjonsalternativ](https://support.catenda.com/en/articles/8224886-organization-options#h_d6710faf75) slås på, slik at alle brukere som er del av prosjektene deres må bruke MFA for å få tilgang til prosjektet. For å aktivere MFA på organisasjonens prosjekter, kontakt Catenda Support. Når MFA er påkrevd på en organisasjons prosjekter, vil du se denne meldingen når du prøver å åpne prosjektet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/07-who-can-enforce-mfa-on-projects.png)
