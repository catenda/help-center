# Utveksle saker

Du finner handlingen for utveksling av saker i [menyen for ny element](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_8c642e051a) øverst til høyre i en saksliste. Menyen for utveksling av saker kan se slik ut:

![Filbasert utveksling nytt element utveksle saker historikk importer bcf eksporter saker koble til bcf-klient synkroniser saker direkte med hvilken som helst BCF-kompatibel klient ved å bruke URL-en nedenfor](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/01-intro.png)

## 1. **Importer BCF**

Bruk BCF-importhandlingen til å importere BCF-filer. Slik kan BCF-importdialogen se ut:

![Importer BCF last opp bcf-fil velg fil bla gjennom velg saksliste generer nye typer og statuser fra BCF-filen](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/02-import-bcf.png)

Catenda er 100% forpliktet til åpne standarder. Basert på dette har vi implementert import og eksport av BCF (BIM-samarbeidsformat). Dette betyr at brukeren kan importere og eksportere saker fra/til annen programvare som støtter dette formatet (for eksempel Solibri, Navisworks og mange andre). Du kan for eksempel importere en fil med kollisjonskontrolldata for samme modell opprettet i et annet program. På denne måten kan du fortsette arbeidsflyten i Catenda.

_Flere saker per bcf_ En BCF-fil kan inneholde flere saker

_Maksimal filstørrelse_ Maksimal BCF-filstørrelse som kan importeres er 500 MB.

### 1.1 **Last opp BCF-fil**

Klikk på Bla gjennom for å velge en BCF-fil du vil laste opp

### 1.2 **Velg saksliste**

Velg saklisten der du vil at saken skal importeres.

### 1.3 **Generer nye typer og statuser fra BCF-filen**

Hvis BCF-filen din har statuser og typer som ikke finnes i saklisten, kan du opprette disse automatisk ved å merke av i denne boksen. _Nødvendig tilgang:_ Full tilgang til saklisten

Hvis BCF-filen din har statuser og typer som ikke finnes i saklisten, vil de ikke-eksisterende statusene/typene være frakoblet hvis denne boksen forblir uavmerket. Etter at importen er fullført, kan du tilordne de frakoblede statusene/typene til eksisterende statuser/typer.

_Koble flere statuser/typer samtidig_ Hvis det finnes frakoblede statuser/typer i en saksliste, vil du se en oransje advarsel som sier at det er frakoblede felt i saklisten. _Nødvendig tilgang:_ Prosjektadministrator

![Saker det er frakoblede felt i denne saklisten klikk her for å koble](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/03-generate-new-types-and-statuses-from-the-bcf-file.png)

Hvis du klikker på lenken, går du til [frakoblede felt](https://support.catenda.com/en/articles/4670277-topic-board-settings#h_3bd7e3e759)-området i [sakliste-innstillingene](https://support.catenda.com/en/articles/4670277-topic-board-settings) der du kan koble alle felt av én type til en eksisterende verdi på én gang.

## 2. **Eksporter saker**

Du kan eksportere saker ved å velge eksporter saker i [menyen for nytt element](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_8c642e051a) øverst til høyre i en saksliste, eller ved å velge en sak i sakslisten og velge eksportalternativet i [menyen for valgt element](https://support.catenda.com/en/articles/4670284-actions-in-a-topic-board#h_b5c00c149b) over saklisten. Eksporter saker-dialogen kan se slik ut:

![Eksporter topics alle topics fra gjeldende topic board gjeldende filter valgte topics bcf excel pdf v3.0](https://raw.githubusercontent.com/catenda/help-center/main/images/8qf7d3yv/04-export-topics.png)

> **Merknad:** Saker kan bare eksporteres fra én saksliste om gangen.

### 2.1 **Filteralternativer**

_Alle saker fra gjeldende saksliste_

_Gjeldende filter_

_Valgte saker_

### 2.2 **BCF-eksport**

Avhengig av hvilken versjon av BCF du velger, kan du få ulike filtyper. BCF v3.0 og v2.1 vil produsere en .bcf, mens v2.0 vil produsere en .bcfzip

### 2.3 **Excel-eksport**

Det er mulig å eksportere saker til Excel. Det vil være én rad per sak og én kolonne per kolonne i tabellvisningen av saklisten. Rekkefølgen på kolonnene vil være den samme som standard sakliste [tabellvisning](https://support.catenda.com/en/articles/6941099-table-view-in-an-topic-board#h_3102328063) kolonneorden.

> **Merknad:** Ingen bilder og bare siste kommentar i en sak vil bli eksportert.

### 2.4 **PDF-eksport**

Klikk [her](https://support.catenda.com/en/articles/9784934-exporting-topics-to-pdf) for å lese mer om eksportering av saker til PDF

## 3. **Rapportside**

Med rapportsiden er det mulig å lage egendefinerte rapporter ikke bare om saker, men også dokumenter. Rapportsiden er en etterspørselsfunksjon som kan forespørres aktivert for pågående prosjekter. Nye prosjekter som opprettes basert på et malprosjekt der denne funksjonen er aktivert, har ikke denne funksjonen aktivert. Disse rapportene kan deretter eksporteres ikke bare til Excel og PDF, men også mange flere filformater. Klikk [her](https://support.catenda.com/en/articles/12303098-reports-page) for å lese mer om rapportsiden

## 4. **Koble til en BCF-klient**

Hvis du bruker Catenda Hub som BCF-server, kan du koble direkte til annen programvare. Her kan du sende og motta saker fra og til Catenda uten å måtte eksportere og importere saker. Dette bruker den standardiserte (fra buildingSMART International) BCF API. Eksempler på programvare som støtter dette, er Navisworks, Revit, Archicad og Solibri. I denne programvaren kan du bruke den generelle URL-en til serveren vår som er [https://api.catenda.com/](https://api.catenda.com/), hvoretter du får alle saklister fra alle prosjektene dine. Dette kan raskt bli en lang liste å bla gjennom, så for å hjelpe deg gir vi lenken til gjeldende saksliste i denne menyen. Hvis du bruker denne lenken i stedet, finner du lett sakene du leter etter.
