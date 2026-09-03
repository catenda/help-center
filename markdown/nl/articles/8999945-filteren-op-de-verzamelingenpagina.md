# Filteren op de verzamelingenpagina

De zoek- en filteroptie die u ziet in het bovenste deel van het venster. U kunt zoeken door de naam van de verzameling in te voeren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/svz5chty/01-intro.png)

In de zoekbalk kunt u naar elke verzameling zoeken waartoe u toegang hebt.

## 1. **Filterlinkerpaneel**

Door op de filterknop te klikken verschijnt een paneel aan de linkerkant. Door de selectievakjes in te schakelen beperkt u de zoekopdracht. Deze filters kunnen bovenaan de filterlijst worden opgeslagen. Wanneer u een van deze filters toepast, wordt de filtertekst aan uw URL toegevoegd. Als u deze URL deelt, ziet de persoon die deze opent hetzelfde filter als u, mits deze toegang heeft. Als u bijvoorbeeld een URL deelt met het filter "Ik volg" ingeschakeld, ziet de ontvanger filters die zij volgen wanneer zij de URL openen. Wanneer u de muisaanwijzer over een van de filters in het linkerpaneel beweegt, kunt u op het filterpictogram rechts klikken om andere eerder toegepaste filters te verwijderen.

## 2. **Opgeslagen filters**

Klik [hier](https://support.catenda.com/en/articles/8551755-saving-filters) voor meer informatie over het opslaan van een set filters

## 3. **Filters**

Klik op de filterknop linksboven om een paneel aan de linkerkant te laten verschijnen. Wanneer een filter wordt toegepast, verandert de URL in de browser. In dit artikel worden filters als volgt weergegeven: _Filternaam in menu_ - `Filternaam in URL=Filteroptie in URL`

**Standaardfilter** Het standaardfilter is aanvankelijk niet zichtbaar in de URL. Wanneer de pagina voor het eerst wordt bezocht, wordt het volgende filter toegepast. _Verzamelingen die door mij en teams waarvan ik deel uitmake worden gevolgd_ - `followers=my-teams,me`

### 3.1 **Huidig filter opslaan en delen**

Ga naar de URL van een gefilterde pagina om die pagina met het toegepaste filter te laden. De toegepaste filters kunnen boven aan het filtermenu worden opgeslagen. Klik [hier](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) voor meer informatie over het opslaan en delen van filters

### 3.2 **Lege filters verbergen**

Klik [hier](https://support.catenda.com/en/articles/8551755-saving-filters) voor meer informatie over het beperken van filterresultaten.

### 3.3 **Verzamelingen die ik volg**

_Ik volg_ - `followers=me` Verzamelingen gevolgd door de gebruiker.

_Mijn teams volgen_ - `followers=my-teams` Verzamelingen gevolgd door teams waarvan de gebruiker deel uitmaakt.

_Alle verzamelingen_ - `followers=all` Alle verzamelingen met of zonder volger. Dit filter wordt automatisch toegepast wanneer op de knop x in de zoekbalk wordt geklikt of wanneer zowel het filter "Ik volg" als "Mijn teams volgen" is uitgeschakeld.

### 3.4 **Gemaakt door mij**

Gemaakt door - `createdBy=<Creator GUID>` Er is geen gebruikersinterfaceknop voor dit filter. Wanneer u filtert op privé of gedeeld met project, wordt dit automatisch ingesteld op uw eigen gebruiker, maar u kunt dit wijzigen in de GUID van een ander gebruiker.

Privé - `visibility=private` Gedeeld met project - `visibility=project-members`

### 3.5 **Voltooid**

Voltooid - `finalized=true` Niet voltooid - `finalized=false`

### 3.6 **Extern gedeeld**

Extern gedeeld - `sharedBy=email,link`

> **Opmerking:** Door hier e-mail of koppeling in te voeren, kunt u uw zoekopdracht verfijnen

Niet extern gedeeld - `sharedBy=not-shared`

### 3.7 **Datumfilters**

Gepubliceerd - `publishedAtFrom=<UTC timestamp>&publishedAtTo=<UTC timestamp>` Klik op datums selecteren om datums te selecteren waartussen u wilt zoeken Klik [hier](https://support.catenda.com/en/articles/6511685-date-filter) voor meer informatie over het datumfilter

## 4. **Tekst zoeken**

U kunt zoeken naar exacte overeenkomsten van tekst in bestandsnamen die minstens 3 tekens lang zijn

### 4.1 **Tekst zoeken**

_Tekst zoeken_ - `search=test`

**Inhoud die kan worden gezocht** verzamelingsnaam

**Kapitalisatie** De tekstzoekopdracht is niet gevoelig voor hoofd- of kleine letters.

**Aantal tekens** Een willekeurig aantal tekens. Inhoud die de gezochte woordgroep bevat, komt overeen.

**Witruimte** Witruimtetekens aan het begin van een zoekopdracht worden verwijderd.
