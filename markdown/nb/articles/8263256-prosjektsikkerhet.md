# Prosjektsikkerhet

## 1. **Lagring av data**

### 1.1 **Aktiv vs. inaktiv kontostatus**

Under et aktivt forhold med et selskap opprettholdes prosjektinformasjonen vanligvis innenfor plattformorganisasjoner for å støtte pågående tilgang. Prosjekter som er på pause eller frosset men som fortsatt er en del av en aktiv kontokonfigurasjon, kan fortsette å være tilgjengelige for referanse- og vedlikeholdsaktiviteter. I disse tilfellene forblir data tilgjengelige så lenge plattformorganisasjonen opprettholder sin aktive status.

### 1.2 **Oppbevaring og gjenoppretting**

Når et prosjekt overføres til en utløpt status eller slettes manuelt, handlinger som betyr at det ikke lenger er knyttet til en aktiv plattformorganisasjon, er plattformen utformet med intensjon om å kunne opprettholde prosjektdata i opptil tre år. I løpet av dette tiltenkte vinduet kan prosjekter gjenopprettes og åpnes på nytt når som helst, forutsatt at et aktivt forhold med selskapet opprettholdes. Oppbevaringsperioden og muligheten til å gjenopprette data er strengt underlagt de juridiske og regulatoriske kravene i jurisdiksjonen der prosjektet ligger. I tilfeller der lokale lover om programvaredatahåndtering krever tidligere fjerning, tar disse jurisdiksjonelle kravene forrang over standard plattformoppførsel. For å sikre at informasjonen bevares i henhold til interne eller jurisdiksjonelle behov, anbefales det å [bruke tilgjengelige eksportverktøy](https://support.catenda.com/en/articles/7946690-exporting-all-project-data) for å utføre en endelig sikkerhetskopi før prosjektets utløp eller sletting.

### 1.3 **Data på hjemmebane**

Standardplattformdata er vert i sikre, etablerte regioner. Selv om gjeldende konfigurasjoner er sentraliserte, kan det finnes muligheter for å etablere databolig innenfor spesifikke geografiske lokasjoner for å samsvare med lokale juridiske krav. Organisasjoner med unike hosting- eller "hjemmebane"-behov oppfordres til å kontakte support på [support@catenda.com](mailto:support@catenda.com) for å diskutere mulige tekniske muligheter og konfigurasjoner.

## 2. **Deling av data med personer utenfor prosjektet**

Lenker kan opprettes for å dele både modeller og dokumenter med eksterne parter. Alle med tilgang til en slik lenke trenger ikke en konto for å vise modellen eller laste ned dokumentene. Dokumenter kan deles ved å lage en åpen URL for en dokumentsamling. _Tilgang påkrevd:_ Prosjektmedlem

Modeller kan deles ved å lage en åpen URL for et bokmerke. _Tilgang påkrevd:_ Administrator

Det er mulig å be om at denne typen URL-er slås av for alle prosjektene dine.

## 3. **Nedlasting av data**

Filer kan lastes opp som dokumentrevisjoner til dokumenter-delen.

### 3.1 **Begrensning av nedlasting med tilgangskontroll**

_Dokumenter / modeller_ Tilgang til dokumenter kan kontrolleres individuelt. Hvis tilgangen til IFC-dokumentet er begrenset, kan bare personer med tilgang til dokumentet se det. Medlemmer med tilgang til dokumentet kan laste det ned.

_Saker_ Tilgang til saker kan kontrolleres per sakstavle. Hvis tilgangen til en sakstavle er begrenset, kan bare personer med tilgang til sakstavlen se sakene i tavlen. Medlemmer med tilgang til sakstavlen kan eksportere saker til BCF, PDF og Excel.

### 3.2 **Begrensning av nedlasting ved tilbaketrekking av revisjon**

Hvis en revisjon finnes i et dokument som ikke skal være der, kan en administrator trekke tilbake revisjonen. Etter at en revisjon er trukket tilbake, kan den ikke lenger vises eller lastes ned noe sted av noen.

### 3.3 **Begrensning av nedlasting av enkeltsakene**

For å bevare relasjonene til elementer som dokumenter, saker og objekter kan en sak arkiveres. Saker kan flyttes til en annen sakstavle. Sakstavlen kan deretter arkiveres. _Tilgang påkrevd:_ Administrator

Mens saken er i den arkiverte sakstavlen, vil elementrelasjoner forbli intakte, men vil ikke være synlige på det relaterte elementet. Hvis en sakstavle gjenopprettes, vil de relaterte elementene igjen vise sin relasjon til saken.

### 3.4 Begrensning av nedlasting av modeller

Hvis dokumentet er et IFC-dokument, kan det kobles til en modell.

_Innenfor prosjektet_ Selv om dokumentet er koblet til en modell, vil bare personer med tilgang til dokumentet se det vises på dashbordet, modellerside og i revisjonsvalgeren.

_Ekstern deling_ Hvis en modell deles med en offentlig lenke i et bokmerke, kan modellforhåndsvisningen bare vises og ikke lastes ned.

Objektinformasjon er ikke synlig i eksternt delte bokmerker.

## 4. **Sletting av data**

_Dokumenter/modeller_ Medlemmer kan slette dokumenter, men administratorer i et prosjekt vil alltid kunne finne dokumenter ved å søke med "slettet" filter. Husk at dette filteret er språkspesifikt.

_Saker_ Før sletting kan saker eksporteres til BCF. Saken for den ID-en vil bli slettet, men hvis du endrer ID-en i BCF, kan saken importeres på nytt. Relasjoner til elementer som dokumenter, objekter og saker vil da gå tapt.

_Milepæler_ Medlemmer kan arkivere og gjenopprette milepæler. _Tilgang påkrevd:_ Milepælskaper eller administrator.
