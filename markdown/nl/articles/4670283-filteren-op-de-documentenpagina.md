# Filteren op de documentenpagina

De zoek- of filteroptie is zichtbaar in het bovenste gedeelte van het venster. Door de naam van het document of de naam van een label dat aan een document is gekoppeld in te typen, kunnen de rijen in de documenttabel worden ingeperkt. Dit is hoe het zoek- of filtermenu op de documentenpagina eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/aa862mj2/01-intro.png)

## 1. **Filters**

Klik op de filterknop links bovenin om een paneel aan de linkerkant weer te geven. Wanneer een filter wordt toegepast, verandert de URL die in de browser zichtbaar is. In dit artikel worden filters als volgt weergegeven: _Filternaam in menu_ - `Filternaam in URL=Filteroptie in URL`

**Standaardfilter** Het standaardfilter is in eerste instantie niet zichtbaar in de URL. Wanneer de pagina voor het eerst wordt geopend, wordt het volgende filter toegepast. Werkruimtetabblad - `v=all`

### 1.1 **Actueel filter opslaan en delen**

Ga naar de URL van een gefilterde pagina om die pagina met het toegepaste filter te laden. De toegepaste filters kunnen bovenin het filtermenu worden opgeslagen. Klik [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) om meer te lezen over het opslaan en delen van filters. Opmerking: in tegenstelling tot andere filtermenu's is het niet mogelijk om persoonlijke filters bovenin het filtermenu op de goedkeuringspagina op te slaan.

### 1.2 **Lege filters verbergen**

Klik [hier](https://support.catenda.com/en/articles/8551755-saving-filters) om meer te lezen over het beperken van filterresultaten.

### 1.3 **Tabbladen**

Werkruimtetabblad - `v=all` Gepubliceerd tabblad - `v=published`

### 1.4 **Koppelingen**

Gekoppeld - `associations=exists&subFolders=true` Filter op documenten die zijn gekoppeld aan modelobjecten in de 3D-viewer.

Niet gekoppeld - `associations=does-not-exist&subFolders=true` Filter op documenten die niet zijn gekoppeld aan modelobjecten in de 3D-viewer.

Gekoppeld aan geselecteerde objecten - `link=backlink&subFolders=true` Indien nog niet geopend, wordt het 3D-paneel geopend. Selecteer objecten uit een model in de 3D-viewer om te filteren op onderwerpen die zijn gekoppeld aan de geselecteerde objecten.

### 1.5 **Status (nieuwste revisie) - Status alleen werkstroom**

Gepubliceerd - `documentStatus=published&subFolders=true&documentType=file` Status ontbreekt - `documentStatus=published-without-status&subFolders=true` Projectpublicatiestatus - `documentStatus=<GUID>&subFolders=true` Gedeeld - `documentStatus=shared&subFolders=true&documentType=file` Gedeelde statussen zijn alleen beschikbaar op het werkruimtetabblad Projectgedeelde status - `documentStatus=<GUID>&subFolders=true` Geen revisie - `documentStatus=no-stage&subFolders=true`

### 1.6 **Concepten - Status alleen werkstroom**

Heeft nieuwe concepten - `newDrafts=exists&subFolders=true` Conceptstatusnaam - `newDrafts=<Draft status GUID>&subFolders=true` Indien er meerdere conceptstatussen zijn, kan op elke conceptstatus worden gefilterd. Heeft geen nieuwe concepten - `newDrafts=does-not-exist&subFolders=true`

### 1.7 **Modellen**

Is model - `model=is-model&subFolders=true` Is geen model - `model=is-not-model&subFolders=true`

### 1.8 **Document gemaakt door**

Lidnaam - `owner=<Member GUID>&subFolders=true`

### 1.9 **Revisie gemaakt door**

Lidnaam - `revisionCreatedBy=<GUID>&subFolders=true`

### 1.10 **Gepubliceerd door**

Lidnaam - `publishedBy=<Member GUID>&subFolders=true`

### 1.11 **Datumfilters**

Gepubliceerd - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Klik op datums selecteren om datums te selecteren waartussen u wilt zoeken Klik [hier](https://support.catenda.com/en/articles/6511685-date-filter) om meer te lezen over het datumfilter

### 1.12 **Open goedkeuringen - Status alleen werkstroom**

Goedkeuringsnaam - `approval=<Approval number>&subFolders=true`

### 1.13 **Documenten - Labels**

Alle labels die geen deel uitmaken van een labelgroep, worden weergegeven in een menu met de naam Documenten. Labelnaam - `labels=<Label GUID>6&subFolders=true`

### 1.14 **Labelnaamgroep**

Per labelnaamgroep wordt één menu weergegeven. Labelnaam - `labels=<Label GUID>6&subFolders=true`

De inhoud van aangepaste velden waarbij waarden kunnen worden geconfigureerd, kan worden gefilterd door een zoekopdracht in de zoek- of filterbalk in te voeren en het bijbehorende filter in het voorgestelde filter te selecteren.

### 1.15 **Aangepast veld**

_Aangepast veld heeft waarde_ - `custom-field-has-value-<Custom field GUID>=true` Met de optie "heeft waarde" in het filtermenu kunnen alle onderwerpen waarvoor een waarde voor dat aangepaste veld is geconfigureerd, worden gefilterd. Aangepaste veldtypen die kunnen worden gefilterd op heeft waarde: Datum Decimaal Vervolgkeuzelijst Geheel getal Tekst

_Aangepast veld specifieke waarde_ - `custom-field-item-<Custom field GUID>=<Value GUID>` Specifieke waarden in velden voor velden met maximaal 10 waarden kunnen worden gefilterd. Aangepaste veldtypen die kunnen worden gefilterd op specifieke waarde uit het filtermenu: Vervolgkeuzelijst

Sommige waarden in aangepaste velden waarbij waarden kunnen worden geconfigureerd, kunnen worden gefilterd. Filter waarden door een zoekopdracht in de zoek- of filterbalk in te voeren en het bijbehorende aangepaste veld te selecteren. Aangepaste veldtypen die kunnen worden gefilterd door in de zoek- of filterbalk te typen: Decimaal Vervolgkeuzelijst Geheel getal Tekst

_Aangepast veld heeft geen waarde_ - `custom-field-has-value-<Custom field GUID>=false` Filter op alle onderwerpen waarbij een aangepast veld geen waarde heeft. Aangepaste veldtypen die kunnen worden gefilterd op geen waarde: Datum Decimaal Vervolgkeuzelijst Geheel getal Tekst

> **Opmerking:** Aangepaste velden die als vereist zijn ingesteld, hebben altijd een waarde. U kunt daarom niet zoeken naar "heeft waarde" of "heeft geen waarde" en kunt daarom niet zoeken naar een aangepast veld dat als vereist is ingesteld.

### 1.16 **Verzamelingen**

Verzamelingsnaam - `collections=<GUID>&subFolders=true`

### 1.17 **Verwijderd**

Verwijderd - `deleted=deleted&subFolders=true` Zie [hier](https://support.catenda.com/en/articles/4670249-undeleting-restoring-documents-or-folders) hoe u kunt zoeken naar verwijderde documenten

## 2. **Tekstzoekopdracht**

_Tekstzoekopdracht_ - `search=test&subFolders=true`

### 2.1 **Inhoud die kan worden doorzocht**

Documenttitel Maptitel

### 2.2 **Gebruik van hoofdletters**

De tekstzoekopdracht is niet gevoelig voor hoofd- of kleine letters.

### 2.3 **Aantal tekens**

Één teken - Titels die het gezochte teken bevatten, worden gevonden. Twee tekens - Geen resultaten. Drie of meer tekens - Titels die één woord bevatten, gescheiden door een scheidingsteken zoals een spatie, dat overeenkomt met de zoekopdracht, worden opgenomen in de resultaten.

### 2.4 **Bestandstypen**

Wanneer de titel een extensie bevat, kan naar de extensie worden gezocht met de normale tekstzoekopdracht. Zoek naar de bestandsextensie met de punt inbegrepen om naar een specifiek bestandstype te zoeken. Als u bijvoorbeeld naar .ifc zoekt, kunnen alle documenten met .ifc in de titel worden gevonden.

## 3. **Sorteren**

Documenten kunnen worden gesorteerd door op de header van elke kolom te klikken. De header kan meerdere keren worden aangeklikt om de sortering om te keren of uit te schakelen.

_Titel, a-z_ - Standaard _Naam, z-a_ - `sort=name-desc` _Gepubliceerd, nieuwste eerst_ - `sort=publishedAt-desc` _Gepubliceerd, oudste eerst_ - `sort=publishedAt-asc` _Gemaakt, nieuwste eerst_ - `sort=createdAt-desc` _Gemaakt, oudste eerst_ - `sort=createdAt-asc`
