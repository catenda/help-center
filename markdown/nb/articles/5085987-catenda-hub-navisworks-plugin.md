# Catenda Navisworks-plugin

> **Merk:** Installasjonsfilen for plugin-en finner du i [denne artikkelen](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Catenda Navisworks-plugin er en plugin som kan installeres for Nemetchek Archicad. Med denne plugin-en kan du samarbeide om 3D-visninger, emner og Dokumenter med andre medlemmer av byggekonseptet.

## 1. **Om plugin-en**

Catenda Hub-tillegg for Autodesk® Navisworks® er det perfekte verktøyet for prosjekter som samarbeider i Catenda Hub. Alle emnene dine synkroniseres i sanntid mellom Navisworks og Catenda Hub, slik at du kan opprette, få tilgang til, dele og kommunisere emner. Emneformatet er BCF slik at emnene kan deles på tvers av enhver BCF-aktivert BIM-programvare eller -plattform. Dette tillegg lar deg visualisere, opprette og redigere emner sømløst fra Navisworks. Du kan også laste ned og sammenslå IFC-modellen som er lagret i Catenda Hub til den lokale klienten din.

### 1.1 **Funksjoner inkluderer:**

- Tilgang til alle Catenda-prosjektene dine
- Filtrer og administrer emner på tvers av emne-tavler
- Opprett nye emner direkte fra Navis Works
- Lokaliser emner i Navisworks-modellen din
- Opprett en ny 3D-visning for hver kommentar
- Opprett BCF-emner fra konflikter som er funnet ved hjelp av Clash Detective
- Tildel emner til andre prosjektmedlemmer
- Endre emnestatus og andre egenskaper

## 2. **Skybasert samarbeid**

Catenda Hub bringer konstruksjonsdataene dine til live på en skybasert samarbeidsplattform som spenner over hele bygningens livssyklus. Catenda administrerer prosjektinformasjonen din fra starten til overlevering og utover, og sikrer datalagring og kunnskapsretensjon på tvers av alle prosjektfaser.

## 3. **Åpne standarder**

Catenda Hub er et BIM-samarbeidsverktøy med støtte for alle buildingSMART-standarder (IFC, bSDD, BCF). Det kommer med et utvalg av APIer for enkel implementering i din egen programvare.

[YouTube-video](https://www.youtube.com/embed/osHul8oKysE?rel=0)

## 4. **Installasjon**

Når Catenda Navisworks-plugin installeres på Windows, vises installasjonsfiler i følgende mappe.

`C:\ProgramData\Autodesk\ApplicationPlugins\Catenda.BCF.bundle`

Innstillingene som er konfigurert i plugin-en finner du her:

`C:\Users\<Username>\AppData\Local\Autodesk_Inc\Roamer.exe_Url_<GUID>\<Version>`

### 4.1 **Avinstallasjon**

For å avinstallere plugin-en går du til følgende Windows-meny:

`Windows-innstillinger -> Apper -> Installerte apper`

Finn Catenda Navisworks BCF-plugin versjon \<version> i listen og klikk på handlingsmenyen på høyre side for å avinstallere.

## 5. **Catenda-fanen**

Etter at plugin-en er installert, vises Catenda-fanen. Navisworks må kanskje startes på nytt for at fanen skal vises. På startsiden for Navisworks vil fanen opprinnelig være grået ut.

Start et nytt eller åpne et Navisworks-prosjekt for å komme i gang.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/01-catenda-tab.png)

Slik kan Catenda-fanen se ut når den er valgt

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/02-catenda-tab.png)

### 5.1 **Catenda**

Catenda-knappen i Catenda Plugins-menyen på Catenda-fanen åpner standardnettleseren med [påloggingssiden](https://support.catenda.com/en/articles/7891486-sign-in-page) til Catenda Hub.

### 5.2 **BCF Plugin**

BCF Plugin-knappen i Catenda Plugins-menyen på Catenda-fanen åpner Catenda Navisworks-plugin med innstillingsmenyen aktivert. Innstillingsmenyen for Catenda Navisworks-plugin kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/03-bcf-plugin.png)

_Docking av plugin-en_ Dra tittellinjen i vinduet til hvilken som helst side av programmet for å docke den.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/04-bcf-plugin.png)

Slik kan programmet se ut når det er docket på høyre side.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/05-bcf-plugin.png)

## 6. **Innstillinger**

Slik kan innstillingsmenyen se ut etter å ha klikket på Logg inn øverst til venstre.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/06-settings.png)

På venstre side vises påloggingssiden for Catenda. Følg trinnene som er beskrevet i [påloggingsartikkelen](https://support.catenda.com/en/articles/7891486-sign-in-page) for å logge på.

Slik kan innstillingsmenyen se ut etter å ha logget på.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/07-settings.png)

Hvis påloggingsøkten har tidsavbrudd, kan oppdateringsknappen brukes til å oppdatere påloggingsøkten.

### 6.1 **Godkjenn**

_Token_ Her vil du se autentiseringssignalet for Catenda etter innlogging.

### 6.2 **IFCGuid**

_Kategori og egenskap_ Kategoristandardinnstilling: Element Egenskapsstandardinnstilling: IfcGUID

_Egenskapsavbildning_ Catenda Navisworks-plugin knytter objekter til visninger i emner basert på GUID for IfcProject i IFC. I Navisworks kan denne GUID finnes i objektets egenskaper. Her er et eksempel med et valgt objekt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/08-ifcguid.png)

Avhengig av innholdet i IFC-filen din, kan IfcProject GUID finnes i en eller flere andre egenskaper eller kategorier. Spesielt hvis Navisworks har blitt startet med en språkinnstilling annet enn engelsk, vil navnet på kategorien Element være ordet for Element på det språket, mens standardordet fremdeles er engelsk i Catenda Navisworks-plugin. For å løse dette, endrer du kategorien til ordet for Element på det språket Navisworks startes i.

2., 3. og 4. kategori og egenskap Hvis det finnes flere kategorier og egenskaper som kan inneholde IFCProject GUID, kan de også legges til.

### 6.3 **Stier**

_LastingsBane_ Filplasseringen der modeller og Dokumenter som lastes ned gjennom plugin-en ender opp.

### 6.4 **Øyeblikksbilder**

_Plassering_ Høyre - standardinnstilling Øyeblikksbilder vises til høyre

Under Øyeblikksbilder vises nedenfor

## 7. **Emne-tavler**

I menyen Emne-tavler kan du se en oversikt over emner i emne-tavlene i ulike prosjekter. Slik kan menyen Emne-tavler se ut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/09-topic-boards.png)

Klikk på fanen Prosjekter for å laste inn listen med emne-tavler i det prosjektet i fanen emne-tavler.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/10-topic-boards.png)

### 7.1 **Nytt emne**

Klikk på knappen Nytt emne for å opprette et nytt emne.

## 8. **Emne**

I emne-menyen kan valgte emner redigeres og nye emner kan sendes inn. Slik kan emne-menyen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/11-topic.png)

### 8.1 **Navigasjonspiler**

Bruk navigasjonspilene i menyen for å bevege deg mellom ulike emner i emne-tavlen.

### 8.2 **Nytt emne**

Opprett et nytt emne

### 8.3 **Legg til visning**

Legg til en visning av den gjeldende kameraposisjonen til det gjeldende emnet.

### 8.4 **Oppdater**

Oppdater emnet på Catenda med informasjonen som er lagt til i plugin-en.

### 8.5 **Emnenummer**

Antallet emnet i prosjektet.

### 8.6 **Oppdater**

Last inn den nyeste informasjonen i emnet fra Catenda.

### 8.7 **Fjern utklippingsplan**

Klikk knappen Fjern utklippingsplan for å fjerne utklippingsplanene i viseren.

## 9. **Konflikter**

I konfliktmenyen kan emner sendes inn som et resultat av Clash Detective-funn. Slik kan konfliktmenyen se ut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/12-clashes.png)

### 9.1 **Kjører en Clash Detective-test**

For å komme i gang med konfliktmenyen, finner du Clash Detective i båndet:

`Hjem-fanen -> Verktøy-meny -> Clash Detective`

_Testoversikt_ Legg til en ny test. Slik kan testoversikten se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/13-running-a-clash-detective-test.png)

_Regler_ Velg regler eller opprett nye.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/14-running-a-clash-detective-test.png)

_Velg_ Velg modeller som du vil sjekke mot hverandre for konflikter, og kjør testen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/15-running-a-clash-detective-test.png)

_Resultater_ Gå gjennom resultatet og gi navn til konfliktene dine.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/16-running-a-clash-detective-test.png)

_Kontekstmeny_ Høyreklikk på en konflikt-rad for å åpne følgende kontekstmeny:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/17-running-a-clash-detective-test.png)

Gruppe Gruppér sammen konflikter av lignende type.

Visning Juster visuell visning med "Fokus på konflikt" og åpne deretter visningsmenyen i kontekstmenyen igjen for å lagre visuell visning til konflikten. Dette er visuell visning som vil ende opp i emnet på Catenda.

Visningsinnstillinger Klikk på visningsinnstillinger på høyre side for å åpne visningsinnstillingene.

Fremheving Endre fargene på objektene fra begge modeller som er i konflikt med hverandre.

Isolasjon Gjennomsiktighetsinnstillinger

Visninger Angi visninger til enten auto-oppdater, auto-last eller manuell lasting.

Simulasjon Vis simulasjon eller ikke

Vis i sammenheng Alle, fil eller hjem.

Elementer Her ser du objektene som er knyttet til den valgte konflikten.

_Rapport_ slik kan rapportmenyen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/18-running-a-clash-detective-test.png)

Innhold Velg innholdet i rapporten

Inkluder konflikter Velg hvilke konflikter som skal inkluderes

Utdatainnstillinger Velg enten gjeldende test for testen som er valgt i testoversikten eller alle tester for alle tester i testoversikten kombinert eller separat.

Rapportformat Bruk alternativet "som visninger" og merk av boksen "Bevar resultatfremheving".

### 9.2 **Konflikter i Catenda-plugin**

Etter at en konflikt-test har kjørt, vises visningene i konflikter-fanen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/19-clashes-in-catenda-plugin.png)

### 9.3 **Legg til emne**

Opprett emne ved å velge en eller flere konflikter Gi emnet en tittel Klikk Legg til emne.

_Legg til emne-rullegardin_ Emner kan lages på følgende måter:

Opprett ett kombinert emne

- Opprett ett emne fra de valgte konfliktene
  - Opprett et emne med en visning for hver konflikt som er valgt i Navisworks Clash Detective.
- Opprett ett emne fra de valgte konfliktene (Konsolidert visning)
  - Opprett et emne med en enkelt visning som er zoomet ut for å inkludere alle konflikter som er valgt i Navisworks Clash Detective.

Opprett flere emner

- Opprett ett emne for hver valgt konflikt
  - Opprett et emne for hver konflikt som er valgt i Catenda Navisworks-plugin.
- Opprett ett emne for hver konflikt-gruppe
  - Opprett et emne for hver konflikt-gruppe som er valgt i Catenda Navisworks-plugin, med en visning for hver konflikt i konflikt-gruppen.
- Opprett ett emne for hver konflikt-gruppe (Konsolidert visning)
  - Opprett et emne for hver konflikt-gruppe som er valgt i Catenda Navisworks-plugin, med en enkelt visning som er zoomet ut for å inkludere alle valgte konflikter.
- Opprett ett emne for hver ugruppert konflikt
  - Opprett et emne for hver ugruppert konflikt som er valgt i Catenda Navisworks-plugin

### 9.4 **Endre status**

Endre statusen for konfliktene som er valgt i Catenda Navisworks-plugin til en av følgende statuser i Navisworks-testrersultatene.

- Ny
- Aktiv
- Gjennomgått
- Godkjent
- Løst

## 10. **Modeller**

Last ned, åpne og legg til modellrevisjoner fra Catenda-prosjektet som er valgt i menyen Emne-tavler til Navisworks-prosjektet. Slik kan modellmenyen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/20-models.png)

### 10.1 **Søk**

Søk gjennom modellene i Catenda-prosjektet

### 10.2 **Oppdater**

Oppdater modellisten fra Catenda-prosjektet

### 10.3 **Last ned valgt**

Last ned valgt(e) modell(er) fra Catenda til det lokale systemet ditt

### 10.4 **Åpne valgt**

Åpne valgt(e) modell(er) i et nytt Navisworks-prosjekt

### 10.5 **Legg til valgt**

Legg valgt(e) modell(er) til det gjeldende Navisworks-prosjektet. For å kunne legge til en modell i det gjeldende Navisworks-prosjektet må det være lastet ned først.

### 10.6 **Catenda-dokumentbibliotek**

Åpne Catenda-dokumentbibliotekvinduen. Slik kan dokumentbibliotekvinduen se ut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cthz4603/21-catenda-document-library.png)

_Navigasjonspil_ Flytt opp ett nivå i mappestrukturen.

_Oppdater_ Oppdater dokumentene i dokumentbiblioteket.

_Last ned_ Last ned den nyeste revisjonen av det valgte Catenda-dokumentet til det lokale systemet ditt.

_Last opp_ Last opp den nyeste revisjonen av det valgte Catenda-dokumentet til det lokale systemet ditt.

_Kolonner_ Navigasjon Dobbeltklikk på navigasjonspilen eller hvor som helst på raden i en mappe for å åpne denne mappen.

Navn Navnet på mappen eller dokumentet

Dokumentnavn Navnet på dokumentet

Bilde Bildet av dokumentet

Revisjon Revisjonsnummeret for dokumentet

### 10.7 **Kolonner**

_Valgboks_ Valgboksen for modellen

_Modellikon_ Ikonet for modellen

_Navn_ Navnet på modellen

_Revisjon Catenda_ Det nyeste revisjonsnummeret i Catenda-prosjektet

_Revisjon Navisworks_

_Last ned_ Klikk på nedlastingsikonet for å laste ned den nyeste modellrevisjonen. Når revisjonsnummeret vises i kolonnen Revisjon Navisworks, er modellen lastet ned.

_Åpne_ Klikk på åpne-ikonet for å åpne modellen i et nytt Navisworks-prosjekt.

_Legg til_ Klikk på legg til-ikonet for å legge til modellen i det gjeldende Navisworks-prosjektet.

### 10.8 **Laster ned modeller fra Catenda Hub**

Du kan enkelt laste ned IFC-modellene fra Catenda-prosjektet ditt ved hjelp av denne plugin-en og handlingene i modeller-fanen. For å laste ned til den lokale enheten din: Klikk på nedlastingsknappen for hver modell du vil laste ned. Modellene vil bli lagret i en ny mappe med prosjektnavnet under nedlastingsbanen som er angitt i innstillingsfanen. For eksempel:

`C:\...\Dokumenter\Catenda prosjektnavn`

### 10.9 **Opprett en sammenslått .nwf-fil ved hjelp av IFC-er fra Catenda Hub**

For å kunne bruke BCF-visningene fra Catenda-prosjektet ditt i Catenda-plugin-en, trenger du en sammenslått NavisWorks-fil som inneholder IFC-ene fra Catenda. Last ned IFC-modellene du vil slå sammen etter trinnene ovenfor. Åpne en av filene du har lastet ned i NavisWorks. Slå sammen flere modeller fra det samme prosjektet til NavisWorks-modellen ved hjelp av "Legg til". Når du har alle filene du vil slå sammen lagt til, lagrer du filen som en .nwf-fil. Lagre filen i samme mappe som dine nedlastede IFC-filer. Bruk denne sammenslåtte filen når du viser BCF-visninger i Navisworks. Du kan også bruke denne sammenslåtte filen for å kjøre kollisjonsprøver i NavisWorks.
