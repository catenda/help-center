# Filteren op de modellenpagina

De zoek- of filteroptie is zichtbaar in het bovenste deel van het venster. Door de naam van het model, de naam van een label dat aan een model is vastgemaakt of de gebruikersnaam van een lid in te voeren, kunnen de rijen in de modellentabel worden beperkt. Dit is wat het zoek- of filtermenu op de modellenpagina kan eruit zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qfd47nkw/01-intro.png)

In de zoekbalk kunt u zoeken naar elk model dat beschikbaar is in de modellentabel.

## 1. **Filterpaneel links**

Klik op de filterknop om een paneel aan de linkerkant weer te geven. Schakel de vakjes in om de zoekopdracht in te perken. Deze filters kunnen bovenaan de filterlijst worden opgeslagen. Wanneer een van deze filters wordt toegepast, wordt de filtertekst aan uw URL toegevoegd. Als de URL van de gefilterde pagina wordt gedeeld, ziet de persoon die deze opent hetzelfde filter in dezelfde map als momenteel wordt weergegeven, zolang deze toegang heeft. Wanneer u over een van de filters in het linkerpaneel beweegt, kunt u "alleen" aan de rechterkant van het filter klikken om andere, eerder toegepaste filters te verwijderen.

## 2. **Opgeslagen filters**

Klik [hier](https://support.catenda.com/en/articles/8551755-saving-filters) voor meer informatie over hoe u een reeks filters kunt opslaan

## 3. **Filters**

Klik op de filterknop in de linkerbovenhoek om een paneel aan de linkerkant weer te geven. Wanneer een filter wordt toegepast, verandert de URL in de browser daarmee. In dit artikel worden filters als volgt weergegeven: _Filternaam in menu_ - `Filternaam in URL=Filteroptie in URL`

**Standaardfilter** Het standaardfilter is aanvankelijk niet zichtbaar in de URL. Wanneer de pagina voor de eerste keer wordt geopend, wordt het volgende filter toegepast. Werkruimtetabblad - `v=all`

### 3.1 **Huidig filter opslaan en delen**

Ga naar de URL van een gefilterde pagina om die pagina met het toegepaste filter te laden. De toegepaste filters kunnen bovenaan het filtermenu worden opgeslagen. Klik [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) voor meer informatie over hoe u filters kunt opslaan en delen

### 3.2 **Lege filters verbergen**

Klik [hier](https://support.catenda.com/en/articles/8551755-saving-filters) voor meer informatie over het beperken van filterresultaten.

### 3.3 **Tabbladen**

Werkruimtetabblad - `v=all` Tabblad Gepubliceerd - `v=published`

### 3.4 **Koppelingen**

Gekoppeld - `associations=exists&subFolders=true` Niet gekoppeld - `associations=does-not-exist&subFolders=true` Gekoppeld aan geselecteerde objecten - `link=backlink&subFolders=true`

### 3.5 **Status (nieuwste revisie) - Status alleen workflow**

Gepubliceerd - `documentStatus=published&subFolders=true&documentType=file` Status ontbreekt - `documentStatus=published-without-status&subFolders=true` Projectpublicatiestatus - `documentStatus=<GUID>&subFolders=true` Gedeeld - `documentStatus=shared&subFolders=true&documentType=file` Gedeelde statussen zijn alleen beschikbaar op het werkruimtetabblad Gedeelde projectstatus - `documentStatus=<GUID>&subFolders=true` Geen revisie - `documentStatus=no-stage&subFolders=true`

### 3.6 **Concepten - Status alleen workflow**

Bevat nieuwe concepten - `newDrafts=exists&subFolders=true` Conceptstatusnaam - `newDrafts=<Draft status GUID>&subFolders=true` Als er meerdere conceptstatussen zijn, kan op elke conceptstatus worden gefilterd. Geen nieuwe concepten - `newDrafts=does-not-exist&subFolders=true`

### 3.7 **Document aangemaakt door**

Ledennaam - `owner=<Member GUID>&subFolders=true`

### 3.8 **Revisie gemaakt door**

Ledennaam - `revisionCreatedBy=<GUID>&subFolders=true`

### 3.9 **Gepubliceerd door**

Ledennaam - `publishedBy=<Member GUID>&subFolders=true`

### 3.10 **Datumfilters**

Gepubliceerd - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Klik op datums selecteren om datums te selecteren waartussen u wilt zoeken Klik [hier](https://support.catenda.com/en/articles/6511685-date-filter) voor meer informatie over het datumfilter

### 3.11 **Openstaande goedkeuringen - Status alleen workflow**

Goedkeuringsnaam - `approval=<Approval number>&subFolders=true`

### 3.12 **Labels**

Alle labels die geen onderdeel zijn van een labelgroep, worden weergegeven in een menu genaamd labels. Labelnaam - `labels=<Label GUID>6&subFolders=true`

### 3.13 **Labelgroepnaam**

Er is één menu per labelgroepnaam Labelnaam - `labels=<Label GUID>6&subFolders=true`

### 3.14 **Bundels**

Bundelnaam - `collections=<GUID>&subFolders=true`

## 4. **Tekst zoeken**

_Tekst zoeken_ - `search=test&subFolders=true`

### 4.1 **Inhoud waarnaar kan worden gezocht**

Modelnaam

### 4.2 **Kapitalisatie**

De tekstzoeking is niet gevoelig voor hoofd- of kleine letters.

### 4.3 **Aantal karakters**

Minder dan drie karakters - De tabel wordt niet gefilterd. Drie of meer karakters - Titels met één woord, gescheiden door een scheidingsteken zoals een spatie, dat overeenkomt met de zoekreeks, zijn opgenomen in de resultaten.

### 4.4 **Bestandstypen**

Als de modelnaam een extensie bevat, kan naar de extensie worden gezocht met de reguliere tekstzoeking. Zoek naar de bestandsextensie met de punt inbegrepen om naar een specifiek bestandstype te zoeken. Als u bijvoorbeeld naar .ifc zoekt, kunnen alle documenten met .ifc in de modelnaam worden gevonden.

## 5. **Sorteren**

Modellen kunnen worden gesorteerd door op de koptekst van elke kolom te klikken. De koptekst kan meerdere keren worden geklikt om de sortering ongedaan te maken of uit te schakelen.

_Naam, a-z_ - Standaard _Naam, z-a_ - `sort=modelName-desc` _Documentnaam, a-z_ - `sort=name-asc` _Documentnaam, z-a_ - `sort=name-desc` _Gepubliceerd, meest recent eerst_ - `sort=publishedAt-desc` _Gepubliceerd, oudste eerst_ - `sort=publishedAt-asc` _Document aangemaakt, meest recent eerst_ - `sort=createdAt-desc` _Document aangemaakt, oudste eerst_ - `sort=createdAt-asc` _Revisie aangemaakt, meest recent eerst_ - `sort=revisionCreatedAt-desc` _Revisie aangemaakt, oudste eerst_ - `sort=revisionCreatedAt-desc`
