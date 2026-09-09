# Organisasjonsalternativer

Det er mulig å be om at følgende alternativer blir satt for organisasjonen din. Disse alternativene vil gjelde for alle prosjekter som eies av organisasjonen.

## 1. **Profil**

Kontakt støtten gjennom den sorte chatknappen ved siden av profilbildet ditt øverst til høyre, eller på [support@catenda.com](mailto:support@catenda.com) hvis du ønsker å endre navnet på organisasjonen din.

## 2. **Plan**

Kontakt [sales@catenda.com](mailto:sales@catenda.com) for spørsmål om planen din. Planen din avgjør hvor mange prosjekter du kan ha på ethvert tidspunkt i en organisasjon. Planen din avgjør også når nye prosjekter utløper.

## 3. **Standarder for nye prosjekter**

### 3.1 Alternativ for dokumentnedlastingstittel

Hvis du laster ned et enkelt dokument, vil filnavnet alltid være det opprinnelige filnavnet. Hvis du laster ned flere dokumenter, vil filnavnene være navnene på dokumentene.

Med dette alternativet kan du konfigurere hvilket filnavn du får når du laster ned flere dokumenter. Dette kan være nyttig i kombinasjon med navngivningskonvensjonen og for å overskrive dokumenter som har samme navn i stedet for med et annet revisjonsnummer hver gang.

_Eksempel:_ Navnet på prosjektet er _testproject._ To filer lastes opp med to revisjoner hver: _test01.pdf_ og _test02.pdf_ Navnene på dokumentene blir deretter endret til: _changed01.pdf_ og _changed02.pdf_

Standardnedlastingsatferd: Hvis du laster ned disse dokumentene ett for ett, vil de alltid være navngitt _test01.pdf_ og _test02.pdf_ Hvis du laster ned begge disse dokumentene samtidig, vil de som standard kalles _changed01.pdf_ og _changed02.pdf_ Dette er hva som kan endres med følgende alternativer:

_Alternativer:_

_Revisjonfilnavn_ Merk at dette er det samme som når du laster ned en enkelt fil, så navnene vil være konsistente hvis du velger dette alternativet. \<Opprinnelig filnavn>.\<Filtype> _test01.pdf_ og _test02.pdf_

_Dokumenttittel_ - standard \<Dokumentnavn>.\<Filtype> _changed01.pdf_ og _changed02.pdf_

_Dokumenttittel med revisjonsnummer_ \<Dokumentnavn>\<Revisjonsnummer>.\<Filtype> _changed01.pdf #2_ og _changed02.pdf #2_

_Prosjekttittel med dokumenttittel og revisjonsnummer_ \<Prosjektnavn>\<Dokumentnavn>\<Revisjonsnummer>.\<Filtype> _testproject changed01.pdf #2_ og _testproject changed02.pdf #2_

### 3.2 **Nedlasting av infiserte dokumenter**

Karantenebehandling for infiserte filer i eide prosjekter. Hvis et dokument blir funnet infisert, kan det som standard lastes ned. Brukeren vil få en advarsel om at dette dokumentet inneholder et virus. Et alternativ kan settes per organisasjon som gjør at ingen, ikke engang administratorer, vil være i stand til å laste ned infiserte dokumenter.

_Alternativer:_ _Advar ved nedlasting_ - standard

_Blokker nedlasting_

### 3.3 **Modeller som dokumenter**

Hvis denne funksjonen er aktivert, vil alle nye prosjekter som opprettes i organisasjonen ha [Modeller som dokumenter](https://support.catenda.com/en/articles/8064548-models-as-documents)-funksjonen aktivert.

> **Merknad:** 24. november: Denne funksjonen vil bli aktivert for alle nye organisasjoner. Vi vil støtte den gamle visningen i ca. ett år før alle prosjekter blir migrert.

### 3.4 **Alternativ for dokumentopplastingsutkast**

Hvis godkjenningsflyt har blitt aktivert og det er utkaststatuser i dokumentinnstillinger, er avmerking for opplasting som utkast merket som standard ved dokumentopplasting. På forespørsel kan denne avmerkingen settes til å være uavmerket som standard for alle prosjekter i en organisasjon.

## 4. **Medlemmer**

Brukere kan legges til som medlemmer eller eiere av en organisasjon.

### 4.1 **Eiere**

Eiere av organisasjoner kan se en oversikt over organisasjonen i [organisasjonsverktøyet](http://hub.catenda.com/orgs). I dette verktøyet vil de kunne: Flytte prosjekter til andre organisasjoner de eier (Arkiver er ofte separate organisasjoner) Opprette nye prosjekter innenfor organisasjonen hvis planen din tillater det. Slette prosjekter eid av organisasjonen. Legge til organisasjonsmedlemmer i prosjekter uten å invitere dem. Invitere brukere til organisasjonsprosjekter uten å måtte være del av prosjektet. Det anbefales at organisasjonseiere holdes få siden prosjekter ikke trenger å flyttes ofte.

### 4.2 **Medlemmer**

Medlemmer av organisasjoner kan enkelt legges til organisasjonenes prosjekter av organisasjoneiere.

## 5. **Prosjekteierregler**

### 5.1 **Krev at alle brukere bruker MFA**

Bedriftskunder kan be om håndhevelse av MFA for brukere som deltar i prosjektene deres. Med dette alternativet er alle brukere pålagt å ha MFA satt opp for å bli med i prosjekter som eies av organisasjonen din.

### 5.2 **Interne SSO-brukere trenger ikke MFA**

Bedriftskunder kan be om å sette opp [Single Sign-On](https://en.wikipedia.org/wiki/Single_sign-on). Det er et gebyr forbundet med det da det tar tid for utviklerne våre å sette opp konfigurasjonen.

_Hva gjør denne regelen?_ Som standard behandles brukere som logger inn med SSO og brukere som logger inn normalt på samme måte. Hvis MFA håndheves for en organisasjon, må både vanlige brukere og SSO-brukere derfor skrive inn MFA-koden for å logge inn og få tilgang til prosjektet. Hvis dette alternativet er merket av for en organisasjon, trenger SSO-brukere ikke å bruke MFA for å få tilgang til prosjektet. Vanlige brukere måtte fortsatt skrive inn MFA-koden mens SSO-brukere kunne logge inn uten å måtte bruke koden.

_Hva er SSO?_ [Single Sign-On](https://en.wikipedia.org/wiki/Single_sign-on) lar brukeren logge inn en gang og få tilgang til tjenester uten å skrive inn autentiseringsfaktorer på nytt. Med dette alternativet kan du gjøre det slik at brukere for organisasjonen din ikke trenger å sette opp MFA. Brukere fra andre organisasjoner som er del av organisasjonsprosjektene dine, må fortsatt ha MFA på hvis alternativet ovenfor er aktivert.

_Oppsett av SSO:_ Det er mulig å sette opp SSO med hvilken som helst SSO-leverandør da det er en standardisert prosess, vennligst finn noen av de vanligste SSO-leverandørene nedenfor:

_Microsoft Active Directory:_ For å konfigurere SSO med Microsoft Active Directory må et nytt Azure Enterprise-program konfigureres i Azure AD-miljøet. Vanligvis er det systemadministratoren for enheten som utfører denne konfigurasjonen. I Azure AD-miljøet må følgende felt fylles ut med SAML-autentisering av systemadministratoren: Entity ID: [https://hub.catenda.com/metadata.xml](https://hub.catenda.com/metadata.xml) Denne XML-filen er tilgjengelig for nedlasting, men vanligvis bør bare URL-en være limt inn i feltet. Assertion Consumer Service (ACS) URL: [https://hub.catenda.com/sso/saml/v2/attribute](https://hub.catenda.com/sso/saml/v2/attribute) Denne lenken skal også legges inn i feltet og er ikke tilgjengelig ved å åpne den i en nettleser. Når den er konfigurert, vil identitetsleverandøren utstede en POST-forespørsel til dette endepunktet. Hvis dette endepunktet kalles fra en normal nettleser (GET-forespørsel) eller via en POST-forespørsel uten korrekte data, lastes siden ikke. Innloggings-URL [https://hub.catenda.com/signin](https://hub.catenda.com/signin) Dette er påloggingssiden som vil omdirigere til den konfigurerte identitetsleverandøren før tilgang til Catenda gis.

Når det er gjort, må systemadministratoren din komme tilbake til oss med App Federation Metadata URL og Federation Metadata XML for det nye programmet.

_GSuite:_ Sett opp SSO som i [denne artikkelen](https://support.google.com/a/answer/12032922?hl=en)

_Testbrukere:_ Når SSO-oppsettet er konfigurert, vennligst oppgi en liste over testbrukere som SSO kan aktiveres for først slik at du kan se hvordan SSO vil fungere for dem. Når testbrukerne har blitt testet, kan de resterende brukerne aktiveres.

_Blacklist og Whitelist:_ Det er også mulig å konfigurere en blacklist/whitelist: For eksempel: Alle brukere unntatt: X, Y og osv. skal være tillatt å logge inn med SSO, eller, Bare X, Y og osv. skal være tillatt å logge inn med SSO Denne informasjonen må leveres i tillegg til XML-filen som spesifisert ovenfor.

### 5.3 **Deaktiver offentlig delingsfunksjon**

Dette alternativet lar deg deaktivere den offentlige delingsfunksjonen for alle prosjekter i organisasjonen din. Hvis dette alternativet er aktivert, vil det ikke lenger være mulig å:

- [Aktivere offentlige URL-er for bokmerker](https://support.catenda.com/en/articles/6423215-public-bookmarks-short-video).
- [Aktivere offentlige URL-er for dokumentsamlinger](https://support.catenda.com/en/articles/6344318-collections-page#h_c1e1a2a402).
- [Dele dokumentsamlinger via e-post](https://support.catenda.com/en/articles/6344318-collections-page#h_c1e1a2a402).

## 6. **Domener**

Du kan be om at et domene legges til organisasjonen din. Hvis et domene har blitt registrert med organisasjonen din, vil alternativet "legg til fra domene" vises på brukersiden i organisasjonen din i [organisasjonsverktøyet](http://hub.catenda.com/orgs). Dette lar deg legge til brukere fra organisasjonen din til prosjektene dine uten å måtte invitere dem gjennom [e-postinvitasjoner](https://support.catenda.com/en/articles/4670319-how-can-i-invite-new-members-to-a-project). Hvis du ikke finner en bruker fra organisasjonen din, er det mest sannsynlig fordi de ikke har opprettet en Catenda-konto ennå og vi har dem ikke i systemet vårt. Brukere fra domenet ditt som ikke har kontoer ennå, må [inviteres](https://support.catenda.com/en/articles/4670319-how-can-i-invite-new-members-to-a-project) på vanlig måte slik at de kan bli med i prosjektet og lage en konto. Brukere fra domener som ikke har blitt lagt til, må fortsatt inviteres med den vanlige [e-postinvitasjonen](https://support.catenda.com/en/articles/4670319-how-can-i-invite-new-members-to-a-project).
