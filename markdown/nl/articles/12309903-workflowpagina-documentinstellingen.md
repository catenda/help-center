# Workflowpagina - Documentinstellingen

De workflowpagina is te vinden door op de knop Workflows configureren in het goedkeuringenmenu van de [pagina met documentinstellingen](https://support.catenda.com/en/articles/7831371-document-settings-page) in projecten waar de nieuwe validatiewerkflow is aangevraagd om in te schakelen en gedeelde statussen zijn ingeschakeld in het statusworkflowmenu van [documentinstellingen](https://support.catenda.com/en/articles/7831371-document-settings-page). De nieuwe validatiewerkflow is een functiie op aanvraag die kan worden aangevraagd om in te schakelen bij het starten van een nieuw project. Het is alleen mogelijk om een project op basis van een templateproject te maken wanneer de nieuwe validatiewerkflow niet is ingeschakeld in dat templateproject. Op de workflowpagina kunnen workflows voor verschillende goedkeuringsconfiguraties worden geconfigureerd. _Vereiste toegang:_ Beheerder

De workflowpagina kan er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/01-intro.png)

De volgende onderwerpen worden in dit artikel beschreven:

_[Nieuwe itemacties](https://support.catenda.com/en/articles/8204673-documents-page#h_d0f4a44fb7) - [Zoeken of filteren](https://support.catenda.com/en/articles/8204673-documents-page#h_bbf4dcad58) - [Rechtermenu](https://support.catenda.com/en/articles/8204673-documents-page#h_fc89aaa1fe) - [Tabel](https://support.catenda.com/en/articles/8204673-documents-page#h_54e8dfcac2) - [Subpagina's](https://support.catenda.com/en/articles/8204673-documents-page#h_5751ccd2b7)_

Hoewel de workflowpagina een subpagina van de goedkeuringenpagina is, wat duidelijk wordt uit het feit dat de goedkeuringenpagina is gemarkeerd en de broodkruimels bovenaan staan, is de pagina alleen toegankelijk via het goedkeuringenmenu in de documentinstellingen.

## 1. **Nieuwe itemacties**

De nieuwe itemacties zijn te vinden in de rechterbovenhoek van de pagina.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/02-new-item-actions.png)

Klik hier om te zien wat de verschillende acties doen.

## 2. **Zoek- of filteropties**

Dit is hoe het zoek- of filtermenu er op de workflowpagina uit kan zien.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/03-search-or-filter-options.png)

In de zoekbalk kan elke workflow die beschikbaar is op de workflowpagina worden doorzocht.

### 2.1 **Filter linkerpaneel**

Door op de filterknop te klikken verschijnt een paneel aan de linkerkant. Schakel de selectievakjes in om uw zoekopdracht in te perken. Wanneer één van deze filters wordt toegepast, wordt de filtertekst aan uw URL toegevoegd. Als de URL van de gefilterde pagina wordt gedeeld, ziet de persoon die deze opent dezelfde resultaten als momenteel worden weergegeven, zolang zij er toegang toe hebben.

### 2.2 **Filters**

> **Opmerking:** De URL van de webpagina verandert afhankelijk van welke filters zijn toegepast. Dit maakt het mogelijk om de huidige gefilterde Documenten-tabel met andere leden van het project te delen.

Als meerdere van dezelfde filters zijn geselecteerd, worden deze gescheiden door een `,` of `%2C`. Als meerdere filters zijn geselecteerd, worden deze gescheiden door `&` of `%26`. Verschillende filters en hun URL-equivalenten:

**Status** Actief - Standaard - `status=active` Gearchiveerd - `status=archived`

> **Opmerking:** Het is alleen mogelijk om actieve of gearchiveerde workflows weer te geven, niet beide tegelijk

**Zoeken** Tekstzoeken - `search=test` Standaard komt de tekstzoeken alleen overeen met actieve workflows. Om gearchiveerde statussen te zoeken, filtert u eerst op gearchiveerd en gebruikt u vervolgens de tekstzoeken.

## 3. **Workflowstabel**

De workflowstabel kan er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/04-workflows-table.png)

Klik [hier](https://support.catenda.com/en/articles/11748020-tables-on-catenda) voor meer informatie over het werken met tabellen in Catenda. Zodra een workflow is gemaakt, verschijnt deze als een rij in de workflowstabel.

### 3.1 **Rijinhoud**

**Workflowrij** Het openen van de inhoud van een workflowrij opent de workflowpagina voor die workflow. Dit is hoe een workflowpagina er uit kan zien wanneer deze wordt geopend.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vnbxxjrb/05-row-content.png)

Op de workflowpagina van een workflow is het mogelijk om te zien hoe de workflow is geconfigureerd.

Titel Het enige gedeelte van de workflow dat kan worden bewerkt, is de naam van de workflow.

Tijdzone Als voor de workflow een tijdzone is geselecteerd, blijft deze het hele jaar hetzelfde. Als voor de workflow een geografische locatie is geselecteerd, verandert de GMT-offset afhankelijk van de tijdzone die momenteel actief is voor die geografische locatie.

Bijwerken Klik op bijwerken om de titel bij te werken.

### 3.2 **Kolommen**

Sommige kolommen in de workflowstabel zijn standaard ingeschakeld, terwijl anderen kunnen worden verborgen en moeten worden ingeschakeld. Op basis van de geconfigureerde kolomvolgorde worden de eerste kolommen weergegeven, terwijl de tabel mogelijk zijwaarts moet worden verschoven om andere ingeschakelde kolommen weer te geven. De standaardvolgorde en zichtbaarheidsinstelling van de kolommen op de workflowpagina is als volgt:

Titel - _Standaard_ De titel van de workflow

Gemaakt door - _Standaard_ Het lid dat de workflow heeft gemaakt.

Gemaakt op - _Standaard_ De datum en tijd waarop de workflow is gemaakt

Status - _Standaard_ De status van de workflow
