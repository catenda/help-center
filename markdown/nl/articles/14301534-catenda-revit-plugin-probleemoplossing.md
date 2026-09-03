# Catenda Revit Plugin Probleemoplossing

Fouten die kunnen optreden bij de Catenda Revit-plugin en hoe deze op te lossen, worden in dit artikel uitgelegd.

## 1. **IFC uploaden**

In de bestandsnaam- en opmerking velden van het uploadmodeldialoogvenster worden alleen ASCII-tekens ondersteund voor upload. Zie [dit Wikipedia-artikel](https://en.wikipedia.org/wiki/ASCII) voor meer informatie over welke tekens in de ASCII-set voorkomen.

Niet-ASCII-tekens kunnen als volgt aan de bestands- en opmerking velden worden toegevoegd:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0bx8b1nt/01-upload-ifc.png)

Bij het klikken op Upload verschijnt het volgende foutbericht:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0bx8b1nt/02-upload-ifc.png)

```
Er is een onverwerkte uitzondering opgetreden in een onderdeel van uw toepassing. Klik op Doorgaan om de toepassing deze fout te laten negeren en door te gaan. Aanvraagheaders mogen alleen ASCII-tekens bevatten.
```

Start Revit opnieuw op nadat u deze fout hebt aangetroffen om door te gaan met uploaden.

## 2. **Koppelingen-venster beheren**

Na installatie van de Catenda Revit-plugin in Revit 2025 dat na maart 2026 is bijgewerkt, loopt Revit vast wanneer u probeert het venster Koppelingen beheren te openen. Dit komt door een wijziging van Autodesk. Klik [hier](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Program-crash-on-certain-machines-when-opening-the-Manage-Links-dialog-in-Revit.html) voor een oplossing. Houd er rekening mee dat alleen Revit 2025 wordt beïnvloed. Dit probleem bestaat niet in Revit 2026.

## 3. **Ondersteunde Revit-edities**

De Catenda add-in is compatibel met Revit-edities die ondersteuning bieden voor de Revit API (Application Programming Interface). Integratie is mogelijk in de volgende omgevingen:

**Standaard Revit** Volledige ondersteuning wordt geboden voor de multidisciplinaire versie van de software, met inbegrip van de toolsets **Architectuur**, **Constructie** en **MEP** (Mechanisch, Elektrisch en Sanitair).

**Educatieve versie** Licenties die zijn uitgegeven voor studenten en docenten ondersteunen de installatie van add-ins van derden, mits de installatie de volledige versie van de software is en niet de LT-versie.

### 3.1 **Niet-ondersteunde editie: Revit LT**

Het is belangrijk op te merken dat [Revit LT geen ondersteuning biedt voor add-ins of plugins van derden](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Revit-LT-Is-it-possible-to-use-plugin-or-addins-in-Revit-LT.html), inclusief de Catenda Revit add-in. Dit is een beperking van de softwarearchitectuur van het LT-platform, omdat het het vereiste API-framework niet heeft. Daarom is het niet mogelijk de add-in te installeren of Dynamo-gebaseerde automatisering in de Revit LT-omgeving te gebruiken.

### 3.2 **Versiecompatibiliteit**

Om aansluiting met de nieuwste software-updates en prestatieverbeteringen te waarborgen, worden de integraties regelmatig bijgewerkt. Voor een uitgebreide lijst met momenteel ondersteunde jaarversies voor zowel de Revit add-in als het Dynamo-pakket kunt u het best [artikel Plugins en integraties](https://support.catenda.com/en/articles/8396532-catenda-plugins-integrations) raadplegen.

## 4. Catenda Hub Dynamo Package

Voor workflows die aangepaste automatisering vereisen, is een gespecialiseerd pakket beschikbaar voor basis Dynamo. Dit is niet een aparte toepassing, maar een verzameling nodes voor gebruik in de standaard Dynamo-omgeving.

**Licenties** Er is geen aanvullende Autodesk-licentie vereist om Dynamo te gebruiken, omdat dit is opgenomen als mogelijkheid in de standaard Revit-licentie.

**API-toegang** Het gebruik van dit pakket vereist toegang tot de Catenda API. Hoewel dit niet standaard voor elke klant is inbegrepen, kunt u via de Catenda-ondersteuningsportal om toegang verzoeken. Wanneer toegang is verleend, kunt u met API-toegang met alle projecten binnen een organisatie communiceren.

**Installatie** Implementatie van het pakket vereist handmatige installatie door de bestandslocatie in de Dynamo-interface op te geven.

### 4.1 **Operationele waarschuwing voor Dynamo-gebruikers**

Voordat het gebruik van dit pakket begint, wordt een waarschuwing gegeven dat deze tools acties in een project mogelijk maken alsof de actor een toepassing is in plaats van een individuele gebruiker. Met grote mogelijkheden komt grote verantwoordelijkheid. Acties die op toepassingsniveau worden uitgevoerd, zoals verwijderingen, worden anders verwerkt dan standaard gebruikersacties. Elementen of gegevens die door een toepassing zijn verwijderd, kunnen niet worden hersteld. Uiterste voorzichtigheid wordt aanbevolen bij het gebruik van deze tools in een projectomgeving. Als u API-toegang of het Dynamo-pakket wilt aanvragen, kunt u contact opnemen met [support@catenda.com](mailto:support@catenda.com) of via de zwarte chatbel in de rechterbovenhoek van het platform.
