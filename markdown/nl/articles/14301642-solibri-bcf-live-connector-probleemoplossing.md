# Solibri BCF Live Connector probleemoplossing

Fouten die kunnen optreden bij de integratie van Solibri-Documenten en hoe deze op te lossen, worden in dit artikel uitgelegd.

## 1. **Ondersteuning en probleemoplossing**

De BCF Live Connector is ontwikkeld, onderhouden en eigendom van Solibri. Omdat deze integratie een onafhankelijk product is dat door Solibri is gemaakt om verbinding te maken met de Catenda API, richt onze ondersteuning zich op de gegevensuitwisseling in plaats van op de interne mechanica van de Solibri-software zelf.

### 1.1 **Voor werkstroom- en gegevensvragen**

Als u hulp nodig hebt om te begrijpen hoe functies binnen de integratie werken, of hoe informatie binnen Catenda wordt weergegeven nadat deze is gesynchroniseerd, helpt ons team u graag. We kunnen u helpen de beoogde werkstroom te navigeren en ervoor zorgen dat uw projectgegevens correct tussen de twee platforms communiceren.

### 1.2 **Voor technische problemen en functionele problemen**

Als u specifieke foutmeldingen in de Solibri-interface tegenkomt, als de connector niet naar behoren reageert, of als u een wijziging in de werking van de connector wilt, neem dan rechtstreeks contact op met **[Solibri Support](https://www.solibri.com/support)**. Als de ontwikkelaars en eigenaren van de connector, zijn zij de enigen die de onderliggende code kunnen wijzigen, interne validatieregels kunnen aanpassen of softwarespecifieke fouten kunnen oplossen.

## 2. **Dubbel model**

Wanneer deze fout optreedt, is dit meestal omdat de Solibri-connector twee modellen heeft gevonden die dezelfde IFCProject GUID delen.

### 2.1 **Namen versus ID's**

Catenda en de Solibri-connector identificeren modellen op basis van hun unieke GUID, niet op basis van hun bestandsnaam.

Als twee verschillende bestanden in uw Solibri Selection Basket uit hetzelfde oorspronkelijke bestand in uw bewerkingsprogramma (bijvoorbeeld Revit, ArchiCAD) zijn geëxporteerd, delen zij waarschijnlijk dezelfde IFCProject GUID.

Hoewel deze bestanden verschillende namen in Solibri hebben gekregen, herkent de connector ze als dezelfde entiteit en activeert een "Dubbel"-waarschuwing om gegevenssynchonisatieconflicten te voorkomen.

### 2.2 **De GUID in Solibri verifiëren**

Controleer de metagegevens rechtstreeks in Solibri om te bevestigen of uw modellen dezelfde identifier delen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ym9bebpy/01-how-to-verify-the-guid-in-solibri.png)

1. Selecteer het **Model** in de Solibri Model Tree.
1. Open de **Info Tool** of het **Identity** tabblad.
1. Zoek het veld **IFCProject GUID**.

Als twee modellen hier dezelfde reeks tekens tonen, behandelt de connector ze als hetzelfde model.
