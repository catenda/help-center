# Catenda Navisworks-plugin

> **Merk:** Installasjonfilen for programtillegget finnes i [denne artikkelen](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Catenda Navisworks plugin er et programtillegg som kan installeres for Nemetchek Archicad. Med dette programtillegget kan du samarbeide om 3D-synspunkter, saker og dokumenter med andre medlemmer av byggeprosjektet.

## 1. **Om programtillegget**

Catenda Hub-tillegget for Autodesk® Navisworks® er det perfekte verktøyet for prosjekter som samarbeider i Catenda Hub. Alle sakene dine synkroniseres i sanntid mellom Navisworks og Catenda Hub, noe som lar deg opprette, få tilgang til, dele og kommunisere om saker. Sakformatet er BCF slik at saker kan deles på tvers av hvilken som helst BCF-aktivert BIM-programvare eller -plattform. Dette tillegget lar deg visualisere, opprette og redigere saker sømløst fra Navisworks. Du kan også laste ned og samle IFC-modellen som lagres i Catenda Hub til den lokale klienten din.

### 1.1 **Funksjoner inkluderer:**

- Tilgang til alle Catenda-prosjektene dine
- Filtrer og administrer saker på tvers av sakslister
- Opprett nye saker direkte fra Navis Works
- Lokalisér saker i Navisworks-modellen din
- Opprett en ny 3D-visning for hver kommentar
- Opprett BCF-saker fra kollisjoner funnet ved hjelp av Clash Detective
- Tildel saker til andre prosjektmedlemmer
- Endre sakstatus og andre egenskaper

## 2. **Skybasert samarbeid**

Catenda Hub bringer byggedataene dine til liv på en skybasert samarbeidsplattform som spenner over hele bygningens livssyklus. Catenda administrerer prosjektinformasjonen din fra start til overlevering og utover, noe som sikrer dataene og kunnskapsoppbevaring på tvers av alle prosjektfaser.

## 3. **Åpne standarder**

Catenda Hub er et BIM-samarbeidsverktøy med støtte for alle buildingSMART-standarder (IFC, bSDD, BCF). Det kommer med en rekke API-er for enkel implementering i din egen programvare.

[YouTube-video](https://www.youtube.com/embed/osHul8oKysE?rel=0)

## 4. **Installasjon**

Når Catenda Navisworks plugin installeres på Windows, vil installasjonsfilene vises i følgende mappe.

`C:\ProgramData\Autodesk\ApplicationPlugins\Catenda.BCF.bundle`

Innstillingene som er konfigurert i programtillegget finnes her:

`C:\Users\<Username>\AppData\Local\Autodesk_Inc\Roamer.exe_Url_<GUID>\<Version>`

### 4.1 **Avinstallering**

For å avinstallere programtillegget går du til følgende Windows-meny:

`Windows-innstillinger -> Apper -> Installerte apper`

Finn Catenda Navisworks BCF plugin versjon \<version> i listen og klikk på handlingsmenyen på høyre side for å avinstallere.

## 5. **Catenda-fanen**

Etter at du har installert programtillegget vil Catenda-fanen vises. Navisworks må kanskje startes på nytt for at fanen skal vises. På startsiden for Navisworks vil fanen først være grået ut.

Start et nytt eller åpne et Navisworks-prosjekt for å komme i gang.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/01-catenda-tab.png)

Dette er hvordan Catenda-fanen kan se ut når den er valgt

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/02-catenda-tab.png)

### 5.1 **Catenda**

Catenda-knappen i Catenda Plugins-menyen på Catenda-fanen åpner standardnettleseren med [påloggingssiden](https://support.catenda.com/en/articles/7891486-sign-in-page) for Catenda Hub.

### 5.2 **BCF Plugin**

BCF Plugin-knappen i Catenda Plugins-menyen på Catenda-fanen åpner Catenda Navisworks-programtillegget med innstillingsmenyen aktivert. Innstillingsmenyen for Catenda Navisworks-programtillegget kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/03-bcf-plugin.png)

_Dokking av programtillegget_ Dra tittellinjen i vinduet til en av sidene av appen for å dokke den.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/04-bcf-plugin.png)

Dette er hvordan appen kan se ut når den er dokt på høyre side.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/05-bcf-plugin.png)

## 6. **Innstillinger**

Dette er hvordan innstillingsmenyen kan se ut etter at du har klikket på Logg inn øverst til venstre.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/06-settings.png)

På venstre side vises påloggingssiden for Catenda. Følg trinnene som er beskrevet i [påloggingsartikkelen](https://support.catenda.com/en/articles/7891486-sign-in-page) for å logge inn.

Dette er hvordan innstillingsmenyen kan se ut etter at du har logget inn.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/07-settings.png)

Hvis påloggingsøkten har utløpt, kan oppdateringsknappen brukes til å oppdatere påloggingsøkten.

### 6.1 **Autentiser**

_Token_ Her vil du se Catenda-autentiseringsjeton etter pålogging.

### 6.2 **IFCGuid**

_Kategori og egenskap_ Kategori standard: Element Egenskap standard: IfcGUID

_Egenskapskartlegging_ Catenda Navisworks-programtillegget knytter objekter til synspunkter i saker basert på GUID-en til IfcProject i IFC. I Navisworks finnes denne GUID-en i egenskapene til objektet. Her er et eksempel med et valgt objekt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/08-ifcguid.png)

Avhengig av innholdet i IFC-filen din, kan IfcProject GUID-en finnes i en eller flere andre egenskaper eller kategorier. Spesielt hvis Navisworks har blitt startet med en annen språkinnstilling enn engelsk, vil navnet på Element-kategorien være ordet for Element på det språket, mens standardordet fortsatt er engelsk i Catenda Navisworks-programtillegget. For å løse dette endrer du kategorien til ordet for Element på språket som Navisworks startes med.

2., 3., 4. Kategori og egenskap Hvis det finnes flere kategorier og egenskaper som kunne inkludere IFCProject GUID-en, kan de også legges til.

### 6.3 **Stier**

_DownloadPath_ Filplasseringen der modeller og dokumenter som lastes ned gjennom programtillegget ender opp.

### 6.4 **Øyeblikksbilder**

_Plassering_ Høyre - standard Øyeblikksbilder vises til høyre

Nedenfor Øyeblikksbilder vises nedenfor

## 7. **Sakslister**

I menyen Sakslister kan du se en oversikt over saker i saklistene for ulike prosjekter. Dette er hvordan menyen Sakslister kan se ut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/09-topic-boards.png)

Klikk på prosjektfanen for å laste inn listen over sakslister i det prosjektet i sakslister-fanen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/10-topic-boards.png)

### 7.1 **Ny sak**

Klikk på knappen Ny sak for å opprette en ny sak.

## 8. **Sak**

I sakmenyen kan valgte saker redigeres og nye saker kan sendes inn. Dette er hvordan sakmenyen kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/11-topic.png)

### 8.1 **Navigasjonspiler**

Bruk navigasjonspilene i menyen for å flytte mellom ulike saker i sakslisten.

### 8.2 **Ny sak**

Opprett en ny sak

### 8.3 **Legg til synspunkt**

Legg til et synspunkt fra gjeldende kameraposisjon til gjeldende sak.

### 8.4 **Oppdater**

Oppdater saken på Catenda med informasjonen som er lagt til i programtillegget.

### 8.5 **Saksnummer**

Nummeret på saken i prosjektet.

### 8.6 **Oppdater**

Last inn den siste informasjonen i saken fra Catenda.

### 8.7 **Fjern klippeplan**

Klikk på knappen Fjern klippeplan for å fjerne klippeplanen i visningen.

## 9. **Kollisjoner**

I kollisjonsmenyen kan saker sendes inn som resultat av Clash Detective-funn. Dette er hvordan kollisjonsmenyen kan se ut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/12-clashes.png)

### 9.1 **Kjør en kollisjonsprøve**

For å komme i gang med kollisjonsmenyen finner du Clash Detective i båndet:

`Hjem-fanen -> Verktøy-meny -> Clash Detective`

_Testoversikt_ Legg til en ny test. Dette er hvordan testens oversikt kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/13-running-a-clash-detective-test.png)

_Regler_ Velg regler eller opprett nye.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/14-running-a-clash-detective-test.png)

_Velg_ Velg modeller som du vil sjekke mot hverandre for kollisjoner og kjør testen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/15-running-a-clash-detective-test.png)

_Resultater_ Gå gjennom resultatet og gi kollisjonene navn.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/16-running-a-clash-detective-test.png)

_Kontekstmeny_ Høyreklikk på en kollisjonrad for å åpne følgende kontekstmeny:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/17-running-a-clash-detective-test.png)

Gruppe Grupper sammen kollisjoner av lignende type.

Synspunkt Juster synspunktet med Fokuser på kollisjon og åpne deretter synspunktmenyen i kontekstmenyen på nytt for å lagre synspunktet i kollisjonen. Dette er synspunktet som ender opp i saken på Catenda.

Visningsinnstillinger Klikk på visningsinnstillinger til høyre for å åpne visningsinnstillingene.

Uthevelse Endre fargene på objektene fra begge modeller som kolliderer med hverandre.

Isolering Gjennomsiktigheetsinnstillinger

Synspunkter Angi synspunkter for automatisk oppdatering, automatisk lasting eller manuell lasting.

Simulering Vis simulering eller ikke

Vis i kontekst Alt, fil eller hjem.

Elementer Her ser du objektene som er relatert til den valgte kollisjonen.

_Rapport_ Dette er hvordan rapportmenyen kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/18-running-a-clash-detective-test.png)

Innhold Velg innholdet i rapporten din

Inkluder kollisjoner Velg hvilke kollisjoner som skal inkluderes

Utdatastillinger Velg enten gjeldende test for testen som er valgt i testoversikten, eller alle tester for alle tester i testoversikten kombinert eller separat.

Rapportformat Bruk alternativet som synspunkter og merk av boksen Bevar resultathevelse.

### 9.2 **Kollisjoner i Catenda plugin**

Etter at en kollisjontest har kjørt, vises synspunktene i kollisjons-fanen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/19-clashes-in-catenda-plugin.png)

### 9.3 **Legg til sak**

Opprett sak ved å velge en eller flere kollisjoner Gi saken en tittel Klikk på Legg til sak.

_Legg til sak-rullegardin_ Saker kan lages på følgende måter:

Opprett en samlet sak

- Opprett en sak fra de valgte kollisjonene
  - Opprett en sak med et synspunkt for hver kollisjon som er valgt i Navisworks Clash Detective.
- Opprett en sak fra de valgte kollisjonene (Konsolidert synspunkt)
  - Opprett en sak med et enkelt synspunkt som er zoomet ut for å inkludere alle kollisjoner som er valgt i Navisworks Clash Detective.

Opprett flere saker

- Opprett en sak for hver valgt kollisjon
  - Opprett en sak for hver kollisjon som er valgt i Catenda Navisworks-programtillegget.
- Opprett en sak for hver kollisjongruppe
  - Opprett en sak for hver kollisjongruppe som er valgt i Catenda Navisworks-programtillegget, med et synspunkt for hver kollisjon i kollisjongruppen.
- Opprett en sak for hver kollisjongruppe (Konsolidert synspunkt)
  - Opprett en sak for hver kollisjongruppe som er valgt i Catenda Navisworks-programtillegget, med et enkelt synspunkt som er zoomet ut for å inkludere alle valgte kollisjoner.
- Opprett en sak for hver ugruppert kollisjon
  - Opprett en sak for hver ugruppert kollisjon som er valgt i Catenda Navisworks-programtillegget

### 9.4 **Endre status**

Endre status for kollisjonene som er valgt i Catenda Navisworks-programtillegget til en av følgende statuser i Navisworks testresultater.

- Ny
- Aktiv
- Vurdert
- Videreført
- Løst

## 10. **Modeller**

Last ned, åpne og legg til modellversjoner fra Catenda-prosjektet som er valgt i menyen Sakslister, til Navisworks-prosjektet. Dette er hvordan modellmenyen kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/20-models.png)

### 10.1 **Søk**

Søk gjennom modellene i Catenda-prosjektet

### 10.2 **Oppdater**

Oppdater modelllisten fra Catenda-prosjektet

### 10.3 **Last ned valgt**

Last ned den/de valgte modellen(e) fra Catenda til systemet ditt

### 10.4 **Åpne valgt**

Åpne den/de valgte modellen(e) i et nytt Navisworks-prosjekt

### 10.5 **Legg til valgt**

Legg til den/de valgte modellen(e) i gjeldende Navisworks-prosjekt. For å kunne legge til en modell i gjeldende Navisworks-prosjekt, må den først lastes ned.

### 10.6 **Catenda dokumentbibliotek**

Åpne Catenda dokumentbibliotek-vinduet. Dette er hvordan dokumentbibliotek-vinduet kan se ut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/21-catenda-document-library.png)

_Navigasjonspil_ Flytt opp ett nivå i mappestrukturen.

_Oppdater_ Oppdater dokumentene i dokumentbiblioteket.

_Last ned_ Last ned den siste versjonen av det valgte Catenda-dokumentet til systemet ditt.

_Last opp_ Last opp den siste versjonen av det valgte Catenda-dokumentet til systemet ditt.

_Kolonner_ Navigasjon Dobbeltklikk på navigasjonspilen eller hvor som helst på raden i en mappe for å åpne den mappen.

Navn Navnet på mappen eller dokumentet

Dokumentnavn Navnet på dokumentet

Bilde Bildet av dokumentet

Versjon Versjonsnummeret for dokumentet

### 10.7 **Kolonner**

_Valgboks_ Valgboksen for modellen

_Modelikon_ Ikonet for modellen

_Navn_ Navnet på modellen

_Versjon Catenda_ Det siste versjonsnummeret i Catenda-prosjektet

_Versjon Navisworks_

_Last ned_ Klikk på nedlastingsikonet for å laste ned den siste modellversjonen. Når versjonsnummeret vises i kolonnen Versjon Navisworks, er modellen lastet ned.

_Åpne_ Klikk på åpne-ikonet for å åpne modellen i et nytt Navisworks-prosjekt.

_Legg til_ Klikk på legg til-ikonet for å legge til modellen i gjeldende Navisworks-prosjekt.

### 10.8 **Last ned modeller fra Catenda Hub**

Du kan enkelt laste ned IFC-modellene fra Catenda-prosjektet ditt ved hjelp av dette programtillegget og handlingene i Models-fanen. For å laste ned til den lokale enheten: Klikk nedlastingsknappen for hver modell du vil laste ned. Modellene lagres i en ny mappe med prosjektnavnet under nedlastingsstien som er angitt under innstillingsfanen. For eksempel:

`C:\...\Dokumenter\Catenda prosjektnavn`

### 10.9 **Opprett en sammenslått NWF-fil ved hjelp av IFC-filer fra Catenda Hub**

For å kunne bruke BCF-synspunktene fra Catenda-prosjektet ditt i Catenda-programtillegget, trenger du en sammenslått NavisWorks-fil som inneholder IFC-filene fra Catenda. Last ned IFC-modellene som du vil slå sammen ved å følge trinnene ovenfor. Åpne en av filene du har lastet ned i NavisWorks. Slå sammen flere modeller fra samme prosjekt inn i NavisWorks-modellen ved hjelp av "Legg til". Når du har alle filene du vil slå sammen lagt til, lagrer du filen som en NWF-fil. Lagre filen i samme mappe som de nedlastede IFC-filene. Bruk denne sammenslåtte filen når du ser BCF-synspunkter i Navisworks. Du kan også bruke denne sammenslåtte filen til å kjøre kollisjonsprøver i NavisWorks.
