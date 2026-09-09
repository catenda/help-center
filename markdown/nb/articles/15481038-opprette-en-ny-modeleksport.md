# Opprette en ny modeleksport

Klikk på den grønne plusknappen øverst til høyre på [modeleksportsiden](https://support.catenda.com/en/articles/4670280-model-export) for å opprette en ny modeleksport. Det er fire trinn for å opprette en ny modeleksport. Slik kan det første trinnet i modeleksportprosessen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/01-intro.png)

## 1. **Trinn 1 - Velg modeller og revisjoner**

I det første trinnet kan revisjonen fra hver av modellene som skal inkluderes i eksporten angis. Start med å velge en modell som skal inkluderes ved å merke av for den. Når modellen er valgt, kan revisjonen som skal inkluderes i denne eksporten velges.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/02-step-1-select-models-and-revisons.png)

I det første trinnet av modeleksporten kan modellene som skal inkluderes i eksporten velges.

> **Merknad 1:** Hvis modellen ikke har revisjoner som kan eksporteres, vil avmerkingsboksen være utgråt. **Merknad 2:** En modellrevisjon må være blitt behandlet og ikke trukket tilbake for å kunne velges.

### 1.1 **Navigasjon**

Så snart en eller flere modeller er valgt og revisjoner er angitt, vil trinnet si Ferdig. Gå til neste trinn ved å klikke Neste: Flettingsalternativer nederst til høyre på siden.

## 2. **Trinn 2 - Flettingsalternativer**

I det andre trinnet kan elementer som er knyttet til modellinnhold i prosjektet flettes inn i IFC-filene de er knyttet til når de eksporteres. Slik kan siden med flettingsalternativer se ut i et nytt prosjekt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/03-step-2-merge-options.png)

Fjern merkingen i avmerkingsboksene for å velge bort prosjektbiblioteker som ikke skal flettes inn i modelfilene i eksporten.

I et nytt prosjekt er de tilgjengelige bibliotekene:

### 2.1 **Dokumenter**

Velg "Dokumenter" for å sette inn Catenda URL-lenker til eventuelle prosjektdokumenter som har blitt koblet til objekter i de eksporterte IFC-filene.

### 2.2 **Lenker**

Velg "Lenker" for å sette inn brukerdefinerte lenker fra lenkebibliotekets som har blitt koblet til objekter i de eksporterte IFC-filene.

### 2.3 **Brukerdefinerte biblioteker**

Alle biblioteker som har blitt opprettet i prosjektet vises etter biblioteknavn her. Dette er hvordan det kan se ut etter å ha lagt til et par biblioteker

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/04-user-defined-libraries.png)

Støttede bibliotektyper inkluderer:

_Dokumentbiblioteker som Dropbox eller SharePoint-biblioteker_ Logg inn med Dropbox eller SharePoint og koble elementer fra ditt eksterne bibliotek til modellobjekter for å få Catenda-lenker til disse bibliotekelementer inkludert i den eksporterte IFC.

_Lenkebibliotek_ Inkluder lagrede URL-lenker fra lenkebiblioteket i IFC-eksporten din ved å koble dem til objekter fra valgte eksportmodeller.

_Klassifikasjonsbibliotek_ Opprett et klassifikasjonsbibliotek ved å laste opp en CSV. Koble elementer fra CSV-en i klassifikasjonsbiblioteket til modellobjekter. Klassifikasjonsbiblioteker vises etter navn på biblioteket i listen over flettingsalternativer. Når avmerkingsboksen for et klassifikasjonsbibliotek er valgt, flettes alle klassifikasjonsbibliotekelementer fra CSV-en som har blitt koblet til objekter i valgte eksportmodeller inn i den eksporterte IFC. Objekter med slike lenker i IFC mottaker en lenke til klassifikasjonsbiblioteket på Catenda.

### 2.4 **Biblioteker som ikke støttes**

Biblioteker som ikke støttes, inkluderer biblioteker som er avhengig av dynamisk innhold som:

_Oppslagsbiblioteker_ Disse slår opp valgte objekter på internett

_Egenskapsverdibiblioteker_ Disse klassifiserer modellobjekter basert på en valgt egenskap

_Innebygde klassifikasjonsbiblioteker_ Disse klassifiserer objekter basert på et eksternt klassifikasjonsbibliotek som allerede er angitt i IFC.

### 2.5 **Navigasjon**

Etter å ha konfigurert de valgte bibliotekene klikker du "Neste: Legg til navn og kommentar" for å gå videre til neste trinn.

## 3. **Trinn 3 - Legg til navn og kommentar**

I det tredje trinnet kan eksporten gis et navn og en kommentar kan legges til. Slik kan trinnet for å legge til navn og kommentar se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/05-step-3-add-name-and-comment.png)

_Navn_ Navnet vil være forhåndsutfylt med Modeleksport og datoen og tidspunktet for eksporten. Dette navnet vil også være filnavnet på den nedlastede ZIP-filen.

_Kommentar_ Eksportkommentarer er valgfrie og vises bare på Catenda. Kommentaren kan gi prosjektdeltakerne informasjon om hva denne eksporten handler om.

## 4. **Trinn 4 - Delingsalternativer**

I det fjerde og siste trinnet kan delingsalternativet velges. Slik kan trinnet med delingsalternativer se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y8fzd5y5/06-step-4-sharing-options.png)

### 4.1 **Delt eksport**

Delte eksporter er synlige for alle prosjektdeltakere

### 4.2 **Privat eksport**

Private eksporter er bare synlige for eksportoppretteren.

### 4.3 **Navigasjon**

Klikk på eksport for å starte behandlingen av denne eksporten. Etter å ha fullført eksporten vises modeleksportsiden der du kan se framdriften for behandlingen av eksporten. Behandlingen av eksporten skjer helt i bakgrunnen, og det er sikkert å lukke nettleseren helt på dette punktet. Når en eksport er ferdig behandlet, sendes det et varsel til eksportoppretteren om at eksporten deres er klar til å lastes ned.
