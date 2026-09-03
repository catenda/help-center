# Richtlijnen voor revisieverwerking

> Los uploadfouten en fouten bij het stapelen van revisies op in mappen met naamgevingsconventies. Verhelp problemen door een onjuist ingeschakelde documentidentificatie en herken toegestane aangepaste veldwaarden in het voorbeeld

Wanneer een naamgevingsconventie is ingeschakeld op een map, worden fouten bij het uploaden van bestanden of fouten bij het stapelen van revisies meestal veroorzaakt door twee veelvoorkomende configuratieproblemen.

## 1. **1. Onjuiste documentidentificatie in-/uitschakelen**

Een veelvoorkomend probleem treedt op wanneer de **documentidentificatie** onjuist is ingesteld op **Aan** voor een blok dat bij elke revisie verandert. Wanneer deze optie actief is, wordt het veranderende variabele veld geïntegreerd in de permanente documentnaam in plaats van geïsoleerd te worden in de revisie-metagegevens.

Daarom zal, hoewel de eerste revisie met succes wordt geüpload, elk volgend bestand met een gewijzigde variabelewaarde niet overeenkomen met de vastgestelde documentnaam. Deze niet-overeenkomst zorgt ervoor dat het systeem het bestand afwijst en aangeeft dat het niet voldoet aan de conventie. Om dit probleem op te lossen, moet de blokconfiguratie worden bijgewerkt om de documentidentificatie **Uit** te zetten. _Vereiste toegang:_ Beheerder

## 2. **2. Niet-overeenkomende veldwaarden**

Uploadfouten kunnen ook optreden als de tekst in het dynamische blok niet overeenkomt met de validatieregels of de specifieke waarden die zijn ingesteld voor het onderliggende aangepaste veld. Als u bijvoorbeeld alfabetische tekens in een integer-aangepast veld invoegt of een zin invoert die niet expliciet is gedefinieerd in een vervolgkeuzelijst met aangepaste velden, resulteert dit in een niet-overeenkomst met de conventie.

### 2.1 **2.1 Toegestane waarden identificeren**

Om de exacte vereisten van een naamgevingsconventieblok te controleren, kan de regelconfiguratie rechtstreeks vanuit de documentinterface worden beoordeeld:

1. Vouw het rechtermenu met informatie uit voor een bestaand document in de betreffende map.
1. Controleer de sectie **Naamgevingsconventie-voorbeeld**, die een realtime visuele uitsplitsing biedt van wat de naamgevingsregel verwacht.
1. Beweeg de muis over het specifieke versie- of statusblok om de configuratieregels ervan weer te geven.
1. Identificeer het exacte aangepaste veld dat het blok aandrijft om te ontdekken welke specifieke waarden zijn toegestaan, zodat de lokale bestandsnaam kan worden aangepast.
