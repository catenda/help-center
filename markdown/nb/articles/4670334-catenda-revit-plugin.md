# Catenda Revit plugin

> **Merk:** Installeringsfilen for programtillegget kan finnes i [denne artikkelen](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Catenda Revit plugin er et programtillegg som kan installeres for Autodesk Revit. Med dette programtillegget kan du samarbeide om 3D-visningspunkter, topic og Dokumenter med andre medlemmer av byggeplassteamet

## 1. **Installasjon**

Når Catenda Revit plugin er installert på Windows, vil installeringsfiler vises i følgende mappe.

`C:\\ProgramData\\Autodesk\\ApplicationPlugins\\CatendaHub.bundle`

### 1.1 **Avinstallasjon**

For å avinstallere programtillegget, gå til følgende Windows-meny:

`Windows-innstillinger -> Apper -> Installerte apper`

Finn Catenda for Autodesk® Revit® i listen og klikk på handlingsmenyen på høyre side for å avinstallere.

## 2. **Åpne plugin-vinduet**

Etter installasjon finner du Catenda-panelet i ribbonen for tillegg. Avhengig av ribbon-innstillingene dine kan Catenda-panelet se slik ut:

_Full ribbon - Standard_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/01-opening-the-plugin-window.png)

_Paneelknapper_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/02-opening-the-plugin-window.png)

_Paneltitler_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/03-opening-the-plugin-window.png)

_Minimer til faner_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/04-opening-the-plugin-window.png)

### 2.1 **Topics**

Klikk på Topics for å åpne Catenda Plugin-vinduet på topics-siden. Hvis ingen bruker er logget inn, vises påloggingssiden i stedet.

### 2.2 **Last opp IFC**

Klikk på Last opp IFC for å åpne Catenda Plugin-vinduet på IFC-opplastingssiden. Hvis ingen bruker er logget inn, vises påloggingssiden i stedet.

### 2.3 **Catenda**

Klikk på Catenda for å bli omdirigert til [https://hub.catenda.com/](https://hub.catenda.com/) i standardnettleseren.

## 3. **Logg inn**

Slik kan plugin-vinduet se ut når det er festet til høyre:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/05-signing-in.png)

Logg inn med Catenda-e-postadressen og passordet ditt.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-703202eeb52b.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3e163e70c122.png" width="180"/><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/inline-3b6b4eaa010e.png" width="180"/>

Hvis du har aktivert MFA for kontoen din, blir du bedt om å fylle inn MFA-koden. Klikk [her](https://support.catenda.com/en/articles/7891486-sign-in-page) for å lese mer om påloggingssiden.

Klikk på «Tillat tilgang» for å tillate Revit-programtillegget for Bimsync Arena å få tilgang til Catenda Hub-kontoen din.

### 3.1 **Tilbakekall tilgang**

Tilgang til Catenda Hub-kontoen din kan tilbakekalles når som helst ved å gå til [kontosiden](https://support.catenda.com/en/articles/6880968-account-page#h_40e031c49a) din i Catenda Hub og klikke på «Tilbakekall tilgang» ved siden av «Revit-programtillegg for Bimsync Arena».

## 4. **Topic-liste**

Etter pålogging åpnes hovedvisningen av Catenda Hub-programtillegget. På denne siden finner du hovedmenyen for å navigere i Catenda Hub-prosjektet, topic boards og topics dine.

### 4.1 **Grensesnitt**

![Header.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/06-interface.png)

1. Velg Catenda Hub-prosjektet ditt
2. Velg et topic board i dette prosjektet
3. Opprett et nytt topic i det valgte topic boardet
4. Sorter topics som vises
5. Åpne Catenda Hub-programtilleggsmenyen
6. Søk og filtrer topics som vises
7. Listen over topics som filtreres for øyeblikket i topic boardet

### 4.2 **Prosjekt- og topic board-valg**

Valg av et Catenda Hub-prosjekt vil vise listen over topic board i dette prosjektet, slik at du kan velge en for å vise de tilsvarende topics. Det vil også lagre Catenda Hub-prosjektet og topic boardet i Revit-modellen din og åpne dem automatisk neste gang du åpner denne modellen.

![ProjectInfo.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/07-project-and-topic-board-selection.png)

### 4.3 **Handlinger**

Programtilleggshandlingene finnes i øvre høyre hjørne:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/08-actions.png)

Klikk [her](https://support.catenda.com/en/articles/13168755-actions-in-the-catenda-revit-plugin) for å lese mer om de ulike handlingene i Catenda Revit-programtillegget.

### 4.4 **Topic-valg**

I topic-listen finner du all hovednformasjonen om et topic:

![IssueInformation.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/09-topic-selection.png)

1. Tittelen på topic
2. Status (Åpen, Lukket, …), type (Info, Feil, …) og merkelapper
3. Medlemmet som etterspurte topic
4. Medlemmet som topic er tildelt til
5. Fristen for topic
6. Når topic ble oppdatert sist. Du kan holde musen over datoen for å vise hele datoen og klokkeslettet for oppdatering.
7. Antallet kommentarer i topic
8. Bildet av den første kommentaren i topic
9. Catenda Hub topic-nummer

Du kan klikke på et topic for å gå til [topic-detaljsiden](#topic-details).

### 4.5 **Sorter topics**

Du kan sortere topics som vises for å bringe de mest relevante først.

![sort.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/10-sort-topics.png)

1. Vis det nyeste topic først
2. Vis det eldste topic først
3. Vis det nyeste oppdaterte topic først. Oppdatering av et topic kan innebære endring av noen av disse egenskapene, tittel, kommentarer, …
4. Vis det minst nylig oppdaterte topic først
5. Vis den nyeste fristen først
6. Vis den eldste fristen først

### 4.6 **Filtrer topics**

Ved hjelp av filterlisten kan du kombinere hvilken som helst type filtre for å vise bare de mest relevante topics.

Aktuelle filtre vises som små sjetonger i filterlinjen. Her vises bare topics med «Åpen»-status. Klikk i filterlinjen for å vise alle tilgjengelige filtre (1).

![AvailableFilters.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/11-filter-topics.png)

Til venstre (2) er filternavnet, hver filtrer tilhører en type som vises til høyre (3).

Tilgjengelige filtertyper inkluderer:

- Etterspurt av: Få alle topics etterspurt av en gitt bruker
- Tildelt til: Få alle topics tildelt en gitt bruker
- Frist: Få alle forfalte topics eller topics som forfaller om mindre enn en måned, to uker, en uke eller en dag
- Status: Få alle topics med en gitt status (Åpen, Lukket, …)
- Type: Få alle topics av en gitt type (Feil, Advarsel, Info, …)
- Merkelapp: Få alle topics med en gitt merkelapp
- Mine topics: Få alle topics tildelt eller etterspurt av deg selv

Du kan søke etter disse filtrene ved å skrive tekst i filterlinjen (1). Du kan også bruke dette til å opprette et tekstfilter for å søke etter en spesifikk tekst i topic-tittelen eller beskrivelsen (2).

![TextFilter.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/12-filter-topics.png)

## 5. **Topic-detaljer**

I denne visningen kan du se og redigere et bestemt topic.

### 5.1 **Grensesnitt**

![IssueDetailView.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/13-interface.png)

1. Gå tilbake til [Topic-listen](#topic-list)
2. Oppdater innholdet i dette topic
3. Naviger mellom topics
4. Angi topic-status (Åpen, Lukket, …)
5. Angi topic-type (Feil, Advarsel, Info, …)
6. Angi fristen for topic
7. Angi medlemmet som er tildelt topic. Du kan tilordne et topic til en enkeltbruker eller et team.
8. Angi medlemmet som etterspør dette topic. Du kan angi en enkeltbruker eller et team.
9. Rediger topic-merkelappene
10. Listen over kommentarer i topic

### 5.2 **Topic-egenskaper**

Du kan redigere en hvilken som helst egenskap for topic: Status, type, tilordnet person, etterspørrer, frist, merkelapper. Hver meny vil vise en liste over tilgjengelige egenskaper. Du kan imidlertid ikke opprette en ny status, type eller merkelapp direkte i programtillegget, du må bruke webgrensesnittet for Catenda Hub til å gjøre det.

Du kan klikke på tittelen for å redigere den:

![editTitle.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/14-topic-properties.gif)

Du kan klikke på pennikonen for å redigere beskrivelsen:

![editDescription.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/15-topic-properties.gif)

Du kan også skrive tekst i merkelapplinjen for å filtrere ned listen over filtre:

![editLabels.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/16-topic-properties.gif)

### 5.3 **Kommentarer**

Alle kommentarer vises under topic. En kommentar kan inneholde tekst, et bilde, et øyeblikksbilde fra gjeldende Revit-visning eller et visningspunkt.

![CommentDetail.png](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/17-comments.png)

1. Forfatteren av kommentaren
2. Når kommentaren ble opprettet. Du kan holde musen over datoen for å vise hele datoen og klokkeslettet for oppdatering.
3. [Zoom-knappen](#zoom) (se kapittelet nedenfor)
4. Bildet som er knyttet til kommentaren
5. Teksten til kommentaren

### 5.4 **Zoom**

Hvis kommentaren inneholder et visningspunkt, kan du zoome inn på dette visningspunktet. Zoom vil opprett en ny 3D-visning i Revit-modellen din fokusert på samme visningspunkt.

![zoom.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/18-zoom.gif)

For at visningspunktet skal være relevant, må du ha åpnet samme modell som den kommentaren ble opprettet fra. Programtillegget forutsetter at delte koordinater ble brukt under eksport av modellen til IFC.

Hvis visningspunktet ble opprettet fra en perspektivvisning, vil den nye 3D-visningen ha projeksjonsmodusen satt til «Perspektiv». Ellers vil projeksjonsmodusen være «Ortogonal».

Programtillegget vil bare opprette en perspektivvisning og en ortogonal visning. Etter å ha opprettet dem, vil det gjenbruke dem for enhver etterfølgende bruk av zoom-funksjonen. Du kan endre det i innstillingsmenyen. Du kan også bruke innstillingsmenyen til å endre navnet på disse visningene.

### 5.5 **Relaterte elementer**

Hvis topic inneholder relaterte elementer, vil programtillegget velge dem i Revit når du zoomer inn på et visningspunkt.

![relatedElements.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/19-related-elements.gif)

For at denne funksjonen skal fungere, må Revit-modellen din ha blitt eksportert til IFC med «Lagre IFC GUID i en elementparameter etter eksport». Dette legger til IFCGuid-parameteren på hvert objekt, slik at programtillegget kan velge de relaterte elementene.

### 5.6 **Legg til kommentar**

Du kan legge til kommentarer til et topic ved å skrive i tekstboksen og klikke på Send.

Du kan også legge til et bilde fra datamaskinen din ved å klikke på «pluss»-knappen. Du kan kommentere bildet ved å klikke på forhåndsvisninsbildet etter å ha valgt det.

![createComment.gif](https://raw.githubusercontent.com/catenda/help-center/main/images/xjh922f7/20-add-comment.gif)

### 5.7 **Legg til 3D-øyeblikksbilde**

Du kan også legge til gjeldende Revit-visning som et visningspunkt og et øyeblikksbilde knyttet til kommentaren din. Akkurat som et hvilket som helst bilde, kan du kommentere øyeblikksbildet ved å klikke på forhåndsvisninsbildet.

Hvis IFCGUID-parameteren finnes, vil valgte elementer i Revit bli lagt til i topic som relaterte elementer.
