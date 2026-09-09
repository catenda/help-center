# Catenda Power BI Connector

> **Merknad:** Installasjonfilen for denne applikasjonen kan finnes [her](https://support.catenda.com/en/articles/8396532-catenda-plugins-and-integrations)

I denne artikkelen vil vi forklare hvordan Catenda HUB-databasen kan kobles til PowerBI. Ved å opprette en kobling kan du få direkte tilgang til dataene på Catenda HUB i PowerBI. Disse dataene kan deretter brukes til å evaluere oppgaver, dokumenter eller for eksempel teammedlemmer.

## 1. **Installasjon**

Når Catenda Desktop Connector er installert på Windows, vil installasjonsfilene vises i følgende mappe.

`C:\Users\<Username>\Dokumenter\Power BI Desktop\Custom connectors`

### 1.1 **Avinstallering**

For å avinstallere plugin-en, gå til installasjonsmappe og kjør følgende fil:

`uninstall.exe`

Hvis mappen er blitt slettet og plugin-en fremdeles er aktiv, installer plugin-en på nytt og avinstaller den med avinstalleringsfilen som ble opprettet.

## 2. **Hent data og koble til**

For å opprette en forbindelse fra PowerBI til Catenda HUB-databasen, gjør følgende: Åpne PowerBI og klikk på "Hent data fra annen kilde" i midten av skjermen, eller bruk handlingen Hent data i hjemmemenyen på øverste bånd. Båndet må kanskje utvides for å se handlingen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/01-get-data-and-connect.png)

Velg målkilden under Annet --> Catenda. Bruk "_Koble til_" for å etablere forbindelsen til databasen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/02-get-data-and-connect.png)

## 3. **Last inn data**

En navigator åpnes der alle prosjekter du har tilgang til er oppført. Velg tilsvarende prosjekt og tabellen som skal kobles. I vårt eksempel vil vi gjerne evaluere [saker](https://support.catenda.com/en/articles/4670271-topics-page) i PowerBI. Klikk på "_Last inn_" for å laste inn datasettet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/03-load-data.png)

Her kan du velge fra følgende datasett: _Dokumenter_

_Dokumentetiketter_

_Etikett_

_Medlem_

_Modell_

_Modellrevisjon_

_Produkter_

_Team_

_Teammedlemmer_

_Token_

_Sak_

_Saksliste_

_Saketikett_

_Saksstatus_

_Sakstype_

Etter at du klikker på Last inn, starter PowerBI-koblingen med å hente saksdataene fra API-en.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/04-load-data.png)

Dataene vises deretter på høyre side. Velg det aktuelle datafeltet og lag analysen din.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/05-load-data.png)

> **Merknad:** Last inn ulike datasett og koble dem sammen. Med dette vil du kunne lage interaktive dashborder som gir deg en fullstendig oversikt.

Avhengig av hvilke data som finnes i prosjektet ditt og hvilke data du laster inn, vil ulike relasjoner opprettes automatisk.

## 4. **Tabellvisning**

Slik kan saksdata se ut i tabellvisning:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/06-table-view.png)

## 5. **Modellvisning**

Her er et kart over hvordan forbindelsene ser ut i modellvisning når all informasjon er tilstede i prosjektet ditt og du har lastet inn alle prosjektdata:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wajxs2mg/07-model-view.png)
