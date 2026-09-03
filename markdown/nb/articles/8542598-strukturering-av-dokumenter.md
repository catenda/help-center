# Strukturering av dokumenter

Det finnes flere måter å strukturere og navngi mappene og dokumentene dine på. Avhengig av prosjekttypen din kan forskjellige strukturer og navnekonvensjoner fungere bedre for deg enn andre. Denne artikkelen inneholder noen hjelpelige tips når det gjelder å bestemme hvordan du skal sette opp datamiljøet ditt.

## 1. **Elementnavn**

Det er flere faktorer som kan påvirke hvordan elementer i en struktur navngis. Oppdagbarhet og stistilingde er ofte viktige faktorer.

### 1.1 **Eierskap**

Personen som setter navnet er ofte kjent med innholdet i elementet som navngis.

_Personlige dokumenter_ Ved navngiving av elementer til personlig bruk er en personlig måte å navngi elementet på ofte det beste, siden personen som navngir dokumentet vil kunne finne elementet enkelt ved å søke på det senere. Selv personen som navngir elementet kan slite med å finne sin egen informasjon igjen senere.

_Samarbeidsdokumenter_ Ved navngiving av elementer til samarbeid vil flere personer arbeide med de ulike elementene. Navn på mapper er derfor ofte forhåndsdefinert i prosjekter slik at de er lett gjenkjennelige på tvers av de ulike prosjektene av en viss type som tilhører den samme organisasjonen.

_Minimumskrav_ Minimumskrav for dokumentnavngiving blir ofte avtalt. Siden ulike ord kan ha ulik betydning for ulike personer er det ofte viktig å diskutere hvilke navn som gis til elementer med teamet slik at alle er klar over hva de skal navngi elementer som og hva de skal søke etter.

### 1.2 **Navneskjemaer**

Å følge god praksis for navngiving av dokumenter er alltid nyttig, men alle har sine egne preferanser. En navnestrategi som gir mening for deg gir ikke alltid mening for andre.

_Teamomfattende navneskjemaer_ Innenfor et team blir bidragsytere til en filstruktur ofte enige om et navneskjema. Dette kan være et verbalt forslag, som å fortelle folk at de skal sette datoen i navnet, eller det kan håndheves ved å opprette en [navnekonvensjon](https://support.catenda.com/en/articles/7832559-naming-conventions-page) som krever at folk navngir filene sine for å kunne laste opp i det hele tatt.

_Prosjektomfattende navneskjemaer_ I et felles datamiljø kommer det ofte flere team sammen. Team kan ennå ikke ha en navneregel på plass eller være villig til å endre sin, men hvis de allerede har navngitt dokumentene sine på en måte i veldig lang tid kan det være vanskelig å overbevise dem om å gjøre noe annet. I dette tilfellet er en god løsning å tillate folk å laste opp filer med sitt foretrukne navn så lenge de endrer navnet på dokumentet som inneholder filen til konvensjonen som er avtalt av prosjektet. På denne måten vil teammedlemmet være i stand til å finne sitt dokument ved [originalnavnet på filen](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page) mens et prosjektmedlem vil være i stand til å finne det ved [dokumentnavnet](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page).

### 1.3 **Navnelengde**

Å være beskrivende og skrive ut hele ord kan hjelpe til med dette fordi du kan lese ordet og umiddelbart forstå innholdet i dokumentet. Dette betyr ikke at dokumentnavnet skal være en hel setning. Dokumentnavn som er for lange til å lese kan se ut som en vegg av tekst og blir raskt oversett. Det anbefales derfor å holde navn til 1 til 5 ord.

_Eksterne begrensninger_ Innenfor Catenda kan mappestrukturer av hvilken som helst stilengde både importeres og eksporteres. Annen programvare som denne informasjonen utveksles med kan ha begrensninger på det totale antallet tegn i de overordnede mappene og dokumentnavnet som danner stien til et dokument innenfor strukturen. Zip-filer brukes ofte til å utveksle mappestrukturer. I Windows er stibegrensningen for zip-filer for eksempel 260 tegn. I OneDrive og SharePoint økes denne grensen, men er fortsatt begrenset til 400 Unicode-enheter.

### 1.4 **Versjonskontroll**

En typisk situasjon folk ender opp med er at de kaller dokumentet sitt noe sånt som:

**Presentation\_Final** Så når de trenger å gjøre en endring blir det: _Presentation\_Final\_Final, Final\_Final\_For real, Final\_LastOneIPromise._ På det punktet gir du opp og kaller det neste: _Presentation\_Submitted_ Denne situasjonen kan forhindres ved å bestemme en versjoneringskonvensjon fra starten. Du kan starte filen din med _Presentation\_v1_, _Presentation\_v2_, osv... Dette vil sikre ulike versjoner av samme fil i en logisk rekkefølge. Selv om det finnes et godt revisjonssystem på Catenda kan det fortsatt være fornuftig å legge til et versjonsnummer. Noen ganger er tellingen av den lokale revisjonen din annerledes enn den som ble lastet opp. Si at du lastet opp v3 av presentasjonen, men så lastet du opp v5 neste gang. Revisjonen på Catenda vil øke med en mens din lokale revisjon har økt med 2. På denne måten kan du holde oversikt over hvilken versjon som er den riktige.

### 1.5 **Separering av informasjon**

Historisk sett har systemer slitt med mellomrom i dokumentnavn. Selv om mange systemer nå kan håndtere mellomrom i dokumentnavn, kan det fortsatt være grunner til å fjerne mellomrom fra dokumentnavn. Du kan kanskje søke etter to ord sammen som ikke er to separate ord. Du kan også håpe på å komprimere antallet tegn i et navn ved å fjerne mellomrommene. Når du tar et normalt filnavn som:

_this is a normal file name that is very long with many words.png_ og du fjerner mellomrommene blir det en uleselig rotete rot fordi du trenger visuelle indikatorer på hvor ordgrensene ligger:

_thisisanormalfilenamethatisverylongwithmanywords.png_ Hvis komprimering er målet ditt vil du ikke introdusere et annet tegn for å separere hvert ord fordi du ville være tilbake på samme lengde som før. I stedet kan du skrive stor bokstav på hvert ord.

_ThisIsANormalFileNameThatIsVeryLongWithManyWords.png_ Selv om dette allerede er litt bedre er det fortsatt ganske vanskelig å lese med lengre navn. Hvis målet er å minimere plass kan du prøve å gruppere ord som hører sammen:

**ThisIs\_ANormalFileName\_ThatIs\_VeryLong\_WithManyWords.png** Nå begynner vi å gå inn i territoriet for et godt, kort filnavn som er lesbart. Selv når filnavnlengde ikke gir mening, gir det mening å tenke på komprimering av ord på denne måten fordi det er lettere å forstå grupperte ord på et øyeblikk. Hvis du ikke bryr deg om hvor langt filnavnet ditt blir hva du kan gjøre for å gjøre det enda bedre er ved å introdusere en sekundær separator. Se her hvordan grupperte ord er separert på en måte mens ordene innenfor hver gruppe er separert på en annen måte.

**This-is\_A-normal-File-name\_That-is\_Very-long\_With-many-words.png** Legg merke til at ved å separere hvert ord var det mulig å skrive stor bokstav på hvert første ord, men deretter ha små bokstaver for de neste.

### 1.6 **Komprimering av informasjon**

I tilfeller hvor det finnes mange ulike dokumenter som alle er litt ulike gir det ikke mening å gjenta de samme 4 ordene igjen og igjen bare for å legge til en variasjon på det 5. ordet. I dette tilfellet kan du kanskje bruke en forkortelse for hvert ord. Eksempel: _Architecture_ kan bli til _ARC_, Første etasje kan bli til 1st. Faktum at du kan ha mer informasjon på mindre plass er både en styrke og en svakhet. Selv om det er lett å være 100% riktig med filnavninformasjonen på denne måten, er dette ikke alltid den beste måten å navngi filene dine på. Når du legger til forkortelser begynner du raskt å legge merke til at filnavnene dine blir til en rotete uleselig rot. Ta for eksempel: _20110101\_ARC\_BLDG1\_BLCK2\_FLR4\_Q4\_Wa3\_Win4\_S\_C\_v4_ Selv om det kan gi mening for forfatteren av filen at dette var en fil fra: 01. januar 2011 om den fjerde versjonen av en betongkarm i vindu 4 på vegg 3 på etasje 4 på blokk 2 i bygning 1 av arkitekten. Jeg er ganske sikker på at ingen andre i prosjektet vil ta seg tid til å lese det. Spesielt ikke når det søkeren egentlig lette etter var:

**20110101\_ARC\_BLDG1\_BLCK1\_FLR4\_Q4\_Wa2\_Win3\_S\_C\_V4** Som er en helt annen vinduskarm! Hvis det kommer til dette nivået er det bedre å dele filene dine opp i mapper.

### 1.7 **Sorteringsrekkefølge**

Dokumentdelen sorteres automatisk etter navn. Det kan derfor være en god idé å legge til noen tegn i begynnelsen av dokumentet slik at det mest relevante dokumentet kommer først.

_Kronologisk rekkefølge_ For å få en historisk oversikt på Catenda Hub kan du alltid sortere etter publisert eller opprettet. Som standard sorteres dokumentene etter navn. Når et medlem åpner en mappe for første gang, er det nyeste dokumentet kanskje ikke øverst. For å motvirke dette kan du legge til datoen på dokumentet foran i dokumentet: _20110101_ ville være den første januar 2011. Dette kan også være nyttig hvis du har dokumenter som ble opprettet for lenge siden og deretter importert til Catenda Hub. Selv om dette navnet kan endres kan det være en nyttig informasjon når du ser etter et dokument. På denne måten kan du også sortere navnkolonnen etter dato.

_Alfanumerisk rekkefølge_ For å finne ut hvilke tegn som kommer før andre tegn, se [sorteringsrekkefølgen for lister](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) på Catenda. For å få dokumentene dine i orden etter viktighet kan du alltid sortere etter merkelapper eller antall revisjoner. Som standard sorteres dokumentene etter navn. Når et medlem åpner en mappe for første gang, er det viktigste dokumentet kanskje ikke øverst. For å motvirke dette kan du legge til et tegn i begynnelsen av navnet som gjør at det kommer først. Du kan for eksempel kalle filene dine: _1.0 Viktigst. 1.1 Mindre viktig, 1.2 osv..._ Så kan det hende at noen bryter regelen din ved å laste opp et dokument med en 0 foran som ender opp først. Det du kan gjøre da er å legge til en \_ foran navnet for å sikre at det kommer før alle elementer. Denne kampen om hvem som er først kan virke endeløs. Det kan derfor hjelpe å se [sorteringsrekkefølgen for lister](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) for å se hvilke tegn som kommer før andre for å se hva som gir mening å bruke i din situasjon.

## 2. **Undermapper**

Det kan være vanskelig å finne informasjon hvis det er mye informasjon i en liste og du må scrolle langt ned for å finne informasjonen du ser etter.

### 2.1 **Når du skal flytte dokumenter inn i mapper**

Hvis det er for mange dokumenter eller mapper i en mappe, kan de bli vanskelige å finne siden du må scrolle langt ned i listen for å finne dokumentet du ser etter. På dette punktet gir det ofte mening å legge til en undermappe i denne listen og dele dokumentene etter deres viktigste egenskap.

Dette kan være en rekke egenskaper som:

_Dokumenttype (Tegning, bilde, regneark)_

_Relatert sak (Vegger og vinduer)_

_Fagfelt (ARC, MEP, STR)_

_Part som lastet det opp (Gruppe 1, Gruppe 2, Gruppe 3)_

_Opplastingsdato (20110101, 20231225)_

_Modenhet (Utkast, Innsendt, Godkjent, Avslått)_

Årsaker som kan påvirke beslutningen om hvordan du skal dele dokumentene dine kan være:

_Oppdagbarhet_

_Tilgangsstyring_

### 2.2 **Når du skal flytte dokumenter ut av mapper**

Etter å ha arbeidet med en dokumentstruktur en stund vil du legge merke til at du begynner å lage mange undermapper. Hvis det tar mange klikk å komme ned til undermappen løste du ikke problemet du prøvde å løse ved å lage undermapper i første omgang fordi informasjonen er fortsatt vanskelig å finne. Det anbefales å ikke gå dypere enn 3 nivåer når du lager undermapper. Dette er fordi de fleste mennesker kanskje husker de to siste mappene de var i, men jo dypere du går jo mer begynner du å glemme hvor du kom fra. For å forhindre dette kan du flytte undermappene dine opp et nivå.

_Her er et eksempel på en mappe som er 4 nivåer dyp:_ 01\_Models-and-drawings 0101\_Models 010101\_ARC 01010101\_Window 01010102\_Wall 010102\_MEP 01010201\_Ducts 01010202\_Vents 010103\_STR 0102\_Drawings

_Denne mappen kan forenkles til å bli:_ 0101\_Models\_ARC 010101\_Window 010102\_Wall 0102\_Models\_MEP 010201\_Ducts 010202\_Vents 0103\_Models\_\_STR 0201\_Drawings

_Eller kanskje enda enklere:_ 010101\_Models\_ARC\_Window 010102\_Models\_ARC\_Wall 010201\_Models\_MEP\_Ducts 010202\_Models\_MEP\_Vents 010301\_Models\_\_STR 020101\_Drawings

Som du kan se kan det å legge til flere mapper som er like på samme nivå bidra til å redusere antallet klikk det tar å komme ned til mappen som inneholder dokumentene du leter etter. En annen ting du kanskje legger merke til er at jo mer du forenkler mappestrukturen, jo lengre blir filnavnene. Når filnavnene blir for lange blir de vanskelige å lese. Det er derfor viktig å opprettholde en balanse mellom [filnavnlengde](#h_7549bd95d9) og [mappedybde](#h_e27bb794b2).

## 3. **Mappestruktur**

### 3.1 **Dokumenttype**

I denne dokumentstrukturen strukturerer du filene dine etter hva slags dokumenttype det er. Alle etasjeplaner går i etasjeplanmappen, alle møtereferater går i referatmappen osv. Denne filstrukturen er lettere å bruke for klienten siden filer som leveres av konsulenter samles på ett sted. Denne filstrukturen er vanskeligere å bruke for konsulentene siden de har mange forskjellige steder hvor de leverer filene sine.

_Eksempel på filstruktur_ Et eksempel på denne typen dokumentstruktur kan være:

0101\_Informasjon 010101\_Admin 010102\_Kontrakter 0201\_Bilder\_Presentasjoner YYMMDD\_Presentasjon-tittel.ppt 0202\_Bilder\_Nettstedsbesøk YYMMDD\_Nettstedsbesøk-tittel.jpg 0301\_2D 03010101\_Plan\_Etasje 030101010101\_DWG\_ARC YYMMDD\_Tegning-tittel.dwg 030101010102\_DWG\_STR 030101010103\_DWG\_MEP 030101010103\_DWG\_LAN 030101010201\_PDF\_ARK YYMMDD\_Tegning-tittel.pdf 030101010202\_PDF\_STR 030101010203\_PDF\_MEP 030101010203\_PDF\_LAN 03010102\_Plan\_Tak 03010103\_Plan\_Brannutgang 03010201\_Snitt 03010301\_Opphøyd 0302\_3D 03020101\_Modeller\_Archicad 030201010101\_PLN\_ARC 030201010102\_PLN\_STR YYMMDD\_Tegning-tittel.ifc 030201010103\_PLN\_MEP 030201010104\_PLN\_LAN 030201010201\_IFC\_ARC 030201010202\_IFC\_STR 030201010203\_IFC\_MEP 030201010204\_IFC\_LAN 03020102\_Modeller\_Navisworks 03020103\_Modeller\_Revit 030201030101\_RVT\_ARC 030201030201\_IFC\_ARC 03020104\_Modeller\_Rhinoceros 03020105\_Modeller\_Solibri 03020106\_Modeller\_Punktskyer 03020201\_Visualisering\_Rendringer 03020202\_Visualisering\_Bilder-høy-oppløsning

### 3.2 **Type fagfelt**

I denne dokumentstrukturen skiller du først ut de ulike fagfeltene som deltar i prosjektet ditt. Denne typen mappestruktur kan være bra hvis du vil gi brukerne dine full tilgang til sitt eget område hvor de fritt kan flytte filer rundt som de ønsker. Denne filstrukturen er lettere å bruke for konsulentene siden de har sitt eget område hvor de kan ha kontroll over alle filene som de laster opp. Denne filstrukturen er vanskeligere å bruke for klienten siden filer fra de ulike konsulentene er spredt ut over hver sin mappe.

_Eksempel på filstruktur_

0101\_Informasjon 010101\_Admin 010102\_Kontrakter 0201\_ARC 02010101\_2D 02010201\_3D\_Archicad 0201020101\_PLN 0201020102\_IFC YYMMDD\_Tegning-tittel.ifc 02010202\_3D\_Navisworks 02010203\_3D\_Revit 0201020301\_RVT 0201020301\_IFC 02010204\_3D\_Rhinoceros 02010205\_3D\_Solibri 02010206\_3D\_Punktskyer 02010307\_Kontrakter 0202\_MEP 020201\_2D 020202\_3D 020203\_Kontrakter 0203\_STR 0204\_LAN

## 4. **Modellmappe**

Med modeller som dokumenter aktivert er det mulig å koble modeller fra modelldelen med dokumenter i dokumentdelen. Hvis nye modeller lages i modelldelen vil de vises i en mappe som kalles modellmappen. Modeller kan flyttes ut av modellmappen og flyttes til hvor du vil at de skal være i dokumentstrukturen.

Tilsvarende eksemplene ovenfor kan du enten strukturere modellene dine etter type: 01\_Models -> 0101\_ARC -> YYMMDD\_Model-title.ifc

Eller du kan strukturere modellene dine etter fagfelt: 01\_ARC -> 0101\_Models -> YYMMDD\_Model-title.ifc

Det beste alternativet å velge her avhenger av om du tror brukerne dine vil bruke [modellmaskefilteret](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page#h_1723ca8291). Hvis du skiller modeller per fagfelt kan det være vanskelig for brukerne å finne 3D-modellene som er blandet sammen med de andre dokumentene for hvert fagfelt. Hvis du er sikker på at brukerne dine vil finne [modellfilteret](https://support.catenda.com/en/articles/4670283-filtering-on-the-documents-page#h_1723ca8291) kan du bruke dette alternativet. Hvis du ikke tror brukerne dine vil bruke dette filteret er det bedre å ha alle modellene dine i sin egen modellmappe slik at brukeren er klar over at denne mappen inneholder modeller som kan åpnes i 3D.
