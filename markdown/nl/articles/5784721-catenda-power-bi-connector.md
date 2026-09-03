# Catenda Power BI Connector

> **Opmerking:** Het installatiebestand voor deze applicatie is te vinden [hier](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)

In dit artikel leggen we uit hoe de Catenda HUB-database kan worden gekoppeld met PowerBI. Door te koppelen kan directe toegang tot de gegevens op Catenda HUB worden verkregen in PowerBI. Deze gegevens kunnen vervolgens worden gebruikt om taken, Documenten of bijvoorbeeld Leden te evalueren.

## 1. **Installatie**

Wanneer de Catenda Desktop Connector op Windows wordt geïnstalleerd, verschijnen de installatiebestanden in de volgende map.

`C:\Users\<Username>\Documenten\Power BI Desktop\Custom connectors`

### 1.1 **Verwijderen**

Ga naar de installatiemap om de plug-in te verwijderen en voer het volgende bestand uit:

`uninstall.exe`

Als de map is verwijderd en de plug-in nog steeds actief is, installeert u de plug-in opnieuw en verwijdert u deze met het verwijderingsbestand dat is gemaakt.

## 2. **Gegevens ophalen en verbinden**

Ga als volgt te werk om een verbinding van PowerBI naar de Catenda HUB-database tot stand te brengen: Open PowerBI en klik op "Gegevens ophalen uit een ander bron" in het midden van het scherm of gebruik de actie Gegevens ophalen in het startmenu van het bovenste lint. Het lint moet mogelijk worden uitgevouwen om de actie te zien.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/01-get-data-and-connect.png)

Selecteer de doelbron onder Overig --> Catenda. Gebruik "_Verbinden_" om de verbinding met de database tot stand te brengen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/02-get-data-and-connect.png)

## 3. **Gegevens laden**

Een navigator wordt geopend waarin alle projecten waartoe u toegang hebt, worden weergegeven. Selecteer het overeenkomstige project en de tabel die moet worden gekoppeld. In ons voorbeeld willen we [Topics](https://support.catenda.com/en/articles/4670271-topics-page) in PowerBI evalueren. Klik op "_Laden_" om de gegevensset te laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/03-load-data.png)

Hier kunt u kiezen uit de volgende gegevenssets: _Documenten_

**Document labels**

**Label**

**Gebruiker**

**Model**

**Revisie van het model**

**Producten**

**Team**

**Teamleden**

**Token**

**Topic**

**Topic Board**

**Topic Label**

**Topic Status**

**Topic Type**

Nadat u op Laden hebt geklikt, begint de PowerBI-connector met het ophalen van de topicgegevens uit de API.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/04-load-data.png)

De gegevens worden vervolgens aan de rechterkant weergegeven. Selecteer het gewenste gegevensveld en maak uw analyse.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/05-load-data.png)

> **Opmerking:** Laad verschillende gegevenssets en koppel deze aan elkaar. Hiermee kunt u interactieve dashboards maken die u een volledig overzicht geven.

Afhankelijk van welke gegevens in uw project aanwezig zijn en welke gegevens u laadt, worden automatisch verschillende relaties gemaakt.

## 4. **Tabel view**

Dit is hoe de topicgegevens er in tabel view kunnen uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/06-table-view.png)

## 5. **Modelweergave**

Hier is een overzicht van hoe de verbindingen er in model view uitzien wanneer alle informatie in uw project aanwezig is en u alle projectgegevens hebt geladen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/07-model-view.png)
