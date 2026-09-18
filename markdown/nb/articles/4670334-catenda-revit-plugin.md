# Catenda Revit-plugin

> **Merk:** Installasjonfilen for plugin-en finner du i [denne artikkelen](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Catenda Revit-plugin er en plugin som kan installeres for Autodesk Revit. Med denne plugin-en kan du samarbeide om 3D-visningspunkter, saker og dokumenter med andre medlemmer av byggprosjektet

## 1. **Installasjon**

Når Catenda Revit-plugin er installert på Windows, vises installasjonsfilene i følgende mappe.

`C:\ProgramData\Autodesk\ApplicationPlugins\CatendaHub.bundle`

### 1.1 **Avinstallering**

For å avinstallere plugin-en går du til følgende Windows-meny:

`Windows-innstillinger -> Apper -> Installerte apper`

Finn Catenda for Autodesk® Revit® i listen og klikk på handlingsmeny på høyre side for å avinstallere.

## 2. **Åpning av plugin-vindu**

Etter installasjon finner du Catenda-panelet i Add-ins-båndet. Avhengig av båndet dine innstillinger kan Catenda-panelet se slik ut:

_Fullt bånd - Standard_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/01-opening-the-plugin-window.png)

_Panelknapper_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/02-opening-the-plugin-window.png)

_Paneltitler_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/03-opening-the-plugin-window.png)

_Minimer til faner_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/04-opening-the-plugin-window.png)

### 2.1 **Saker**

Klikk på Saker for å åpne Catenda Plugin-vinduet på sakersiden. Hvis ingen bruker er logget inn, vises påloggingssiden i stedet.

### 2.2 **Last opp IFC**

Klikk på Last opp IFC for å åpne Catenda Plugin-vinduet til IFC-opplastingssiden. Hvis ingen bruker er logget inn, vises påloggingssiden i stedet.

### 2.3 **Catenda**

Klikk på Catenda for å bli omdirigert til [https://hub.catenda.com/](https://hub.catenda.com/) i standardnettleseren.

## 3. **Logge inn**

Slik kan plugin-vinduet se ut når det er forankret til høyre:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/05-signing-in.png)

Logg inn med din Catenda-e-postadresse og passord.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-703202eeb52b.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3e163e70c122.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3b6b4eaa010e.png" width="180"/>

Hvis du har MFA aktivert for kontoen din, blir du bedt om å fylle inn MFA-koden din. Klikk [her](https://support.catenda.com/en/articles/7891486-sign-in-page) for å lese mer om påloggingssiden.

Klikk på "Tillat tilgang" for å tillate Revit-plugin for Bimsync Arena å få tilgang til Catenda Hub-kontoen din.

### 3.1 **Opphev tilgang**

Tilgang til Catenda Hub-kontoen din kan oppheves når som helst ved å gå til Catenda Hub [programside](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) og klikke på "Opphev tilgang" ved siden av "Revit-plugin for Bimsync Arena".

## 4. **Saksliste**

Etter pålogging åpnes hovedvisningen av Catenda Hub-plugin. På denne siden finner du hovedmenyen for navigering i Catenda Hub-prosjektet ditt, saklister og saker.

### 4.1 **Grensesnitt**

![Header.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/06-interface.png)

1. Velg Catenda Hub-prosjektet ditt
1. Velg en sakliste i dette prosjektet
1. Opprett en ny sak i den valgte saklisten
1. Sorter viste saker
1. Åpne Catenda Hub-tillegg-menyen
1. Søk og filtrer de viste sakene
1. Listen over gjeldende filtrerte saker i saklisten

### 4.2 **Prosjekt- og sakliste-valg**

Når du velger et Catenda Hub-prosjekt, vises listen over saklister i dette prosjektet, som lar deg velge en for å vise de tilsvarende sakene. Det lagrer også Catenda Hub-prosjektet og saklisten i Revit-modellen din og åpner dem automatisk neste gang du åpner denne modellen.

![ProjectInfo.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/07-project-and-topic-board-selection.png)

### 4.3 **Handlinger**

Plugin-handlingene finner du øverst til høyre:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/08-actions.png)

Klikk [her](https://support.catenda.com/en/articles/13168755-actions-in-the-catenda-revit-plugin) for å lese mer om de ulike handlingene i Catenda Revit-plugin.

### 4.4 **Saksvalg**

I saklisten finner du all hovedinformasjonen om en sak:

![IssueInformation.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/09-topic-selection.png)

1. Tittel på saken
1. Dens status (Åpen, Lukket, …), dens type (Info, Feil, …) og etikettene
1. Medlemmet som ber om saken
1. Medlemmet som saken er tildelt til
1. Fristen på saken
1. Når saken sist ble oppdatert. Du kan holde musepekeren over datoen for å vise full dato og klokkeslett for oppdateringen.
1. Antallet kommentarer i saken
1. Bildet av den første kommentaren i saken
1. Catenda Hub-saknummer

Du kan klikke på en sak for å gå til [saksdetaljsiden](#h_445d3efa52).

### 4.5 **Sorter saker**

Du kan sortere de viste sakene for å bringe de mest relevante først.

![sort.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/10-sort-topics.png)

1. Bring den nyeste saken opprettet først
1. Bring den eldste saken først
1. Bring den nyeste oppdaterte saken først. Oppdatering av en sak kan innebære endring av noen av egenskapene, tittel, kommentarer, …
1. Bring den minst nylig oppdaterte saken først
1. Bring den seneste fristen først
1. Bring den eldste fristen først

### 4.6 **Filtrer saker**

Ved hjelp av filterlinjen kan du kombinere enhver type filter for å vise bare de mest relevante sakene.

Gjeldende filtre vises som små chips i filterlinjen. Her vises bare saker med status "Åpen". Klikk i filterlinjen for å vise alle tilgjengelige filtre (1).

![AvailableFilters.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/11-filter-topics.png)

Til venstre (2) er filternavnet, hver filter tilhører en type som vises til høyre (3).

Tilgjengelige filtertyper inkluderer:

- Etterspurt av: Få alle saker etterspurt av en gitt bruker
- Tildelt til: Få alle saker tildelt en gitt bruker
- Frist: Få alle forfalt saker eller sak som forfaller om mindre enn en måned, to uker, en uke eller en dag
- Status: Få alle saker av en gitt status (Åpen, Lukket, …)
- Type: Få alle saker av en gitt type (Feil, Advarsel, Info, …)
- Etikett: Få alle saker med en gitt etikett
- Mine saker: Få alle saker tildelt eller etterspurt av deg selv

Du kan søke etter disse filtrene ved å skrive tekst i filterlinjen (1). Du kan også bruke dette til å opprette et tekstfilter for å søke etter en spesifikk tekst i saktittel eller beskrivelse (2).

![TextFilter.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/12-filter-topics.png)

## 5. **Saksdetaljer**

I denne visningen kan du vurdere og redigere en spesifikk sak.

### 5.1 **Grensesnitt**

![IssueDetailView.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/13-interface.png)

1. Gå tilbake til [Saklisten](#h_642fa61854)
1. Oppdater innholdet i denne saken
1. Naviger mellom saker
1. Angi saksstatusen (Åpen, Lukket, …)
1. Angi sakstypen (Feil, Advarsel, Info, …)
1. Angi fristen på saken
1. Angi medlemmet tildelt saken. Du kan tilordne en sak til en enkeltbruker eller et team.
1. Angi medlemmet som ber om denne saken. Du kan angi en enkeltbruker eller et team.
1. Rediger saketikettene
1. Listen over kommentarer i saken

### 5.2 **Saksegenskaper**

Du kan redigere enhver egenskap for saken: Status, type, tilordnet, gjenstand, frist, etiketter. Hver meny viser en liste over tilgjengelige egenskaper. Du kan imidlertid ikke opprette en ny status, type eller etikett direkte i plugin-en, du må bruke webgrensesnittet til Catenda Hub.

Du kan klikke på tittelen for å redigere den:

![editTitle.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/14-topic-properties.gif)

Du kan klikke på penneikonet for å redigere beskrivelsen:

![editDescription.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/15-topic-properties.gif)

Du kan også skrive tekst i etikettlinjen for å filtrere ned listen over filtre:

![editLabels.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/16-topic-properties.gif)

### 5.3 **Kommentarer**

Alle kommentarer vises under saken. En kommentar kan inneholde tekst, et bilde, et øyeblikksbilde fra gjeldende Revit-visning eller et visningspunkt.

![CommentDetail.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/17-comments.png)

1. Forfatteren av kommentaren
1. Når kommentaren ble opprettet. Du kan holde musepekeren over datoen for å vise full dato og klokkeslett for oppdateringen.
1. [Zoom-knappen](#h_d873968c27) (se kapittel nedenfor)
1. Bildet som er knyttet til kommentaren
1. Teksten i kommentaren

### 5.4 **Zoom**

Hvis kommentaren inneholder et visningspunkt, kan du zoome til dette visningspunktet. Zoom inn vil opprette en ny 3D-visning i Revit-modellen din fokusert på samme visningspunkt.

![zoom.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/18-zoom.gif)

For at visningspunktet skal være relevant, må du ha åpnet samme modell som den hvor kommentaren ble opprettet. Plugin-en forutsetter at Delte koordinater ble brukt ved eksport av modellen til IFC.

Hvis visningspunktet ble opprettet fra en perspektivvisning, vil den nye 3D-visningen ha sin projeksjonsm odus satt til "Perspektiv". Ellers vil projeksjonsmodusen være "Ortografisk".

Tillegget vil bare opprette en perspektivvisning og en ortografisk visning. Etter å ha opprettet dem, vil det gjenbruke dem for enhver påfølgende bruk av zoomfunksjonen. Du kan endre det i [innstillingsmenyen](#h_b02502c589). Du kan også bruke innstillingsmenyen til å endre navnet på disse visningene.

### 5.5 **Relaterte elementer**

Hvis saken inneholder relaterte elementer, vil tillegget velge dem i Revit når du zoomer til et visningspunkt.

![relatedElements.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/19-related-elements.gif)

For at denne funksjonen skal fungere, må Revit-modellen din ha blitt eksportert til IFC med "Lagre IFC GUID i en elementparameter etter eksport". Dette legger til IFCGuid-parameteren på hvert objekt, som lar plugin-en velge de relaterte elementene.

### 5.6 **Legg til kommentar**

Du kan legge til kommentarer til en sak ved å skrive i tekstboksen og klikke på Send.

Du kan også legge til et bilde fra datamaskinen din ved å klikke på "Plus"-knappen. Du kan kommentere dette bildet ved å klikke på forhåndsvisningsbildet etter å ha valgt det.

![createComment.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/20-add-comment.gif)

### 5.7 **Legg til 3D øyeblikksbilde**

Du kan også legge til gjeldende Revit-visning som et visningspunkt og et øyeblikksbilde knyttet til kommentaren din. Akkurat som ethvert bilde kan du kommentere øyeblikksbildet ved å klikke på forhåndsvisningsbildet.

Hvis IFCGUID-parameteren er til stede, blir valgte elementer i Revit lagt til saken din som relaterte elementer.
