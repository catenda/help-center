# Pagina Topic template-instellingen

> Beheer uw Topic template-instellingen

De pagina Topic template-instellingen kunt u vinden door op Configureer topic templates te klikken op de [topic-instellingenpagina](https://support.catenda.com/en/articles/14183429-topic-settings-page) die u kunt openen vanuit het linkernavigatiemenu na het openen van de topics-pagina. _Vereiste toegang:_ Projectbeheerder

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/01-intro.png)

Op de pagina Topic template-instellingen kunnen topic templates voor elk van de topic boards in het project worden geconfigureerd. Na het maken worden topic templates automatisch beschikbaar gesteld om tekst en velden van topics in te vullen bij het maken. Topic templates kunnen worden geconfigureerd om beschikbaar te zijn in de volgende processen voor topic-aanmaak: [Topic templates gebruiken in algemene topics](https://support.catenda.com/en/articles/14075921-apply-a-general-topic-template-upon-topic-creation) [Topic templates in markup-topics gebruiken](https://support.catenda.com/en/articles/14078352-apply-a-document-topic-template-when-creating-a-markup-from-a-document) [Topic templates gebruiken met goedkeuringen](https://support.catenda.com/en/articles/14078683-apply-an-approval-topic-template-to-an-approval-workflow-template)

## 1. **Actiemenu**

Klik op de plus-knop rechtsboven om het actiemenu te openen. Dit is wat het actiemenu rechtsboven op de pagina Topic template-instellingen eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/02-action-menu.png)

Een vervolgkeuzemenu geeft u de mogelijkheid om 3 verschillende soorten topic templates te maken. Topic templates worden onderscheiden in drie verschillende template-types, omdat de variabelen die kunnen worden gebruikt om tekst en velden in topics automatisch in te vullen bij het maken verschillen, afhankelijk van het process dat voor topic-aanmaak wordt gebruikt.

## 2. **Zoek- of filteropties**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/03-search-or-filter-options.png)

### 2.1 **Zoeken**

_Tekstzoeken -_ `search=<Search phrase>` Na het invoeren van tekens in de zoek- of filterbalk, verandert het eerste aanbevolen filter in tekstzoeken.

**Inhoud die kan worden doorzocht** Naam van topic template

**Hoofdlettergebruik** Het tekstzoeken is niet gevoelig voor hoofd- of kleine letters.

**Aantal tekens** Elk aantal of type teken kan worden doorzocht.

**Witruimte** Tekens van witruimte aan het begin van een zoekzin kunnen worden doorzocht, maar worden verwijderd uit de template-namen, dus er zijn geen resultaten bij het zoeken. Tekens van witruimte aan het einde van een zoekzin worden verwijderd.

### 2.2 **Filteren in het filtermenu**

Topic templates worden gefilterd op basis van een van de mogelijke statussen Klik op het Status-menu in het filtermenu om de optiestatus die niet is gefilterd te verbergen. Het is mogelijk om op de X rechts in de zoekbalk te drukken om de filtertags uit de balk te verwijderen, maar dit heeft geen effect. U kunt templates alleen filteren met het filter Actief of Gearchiveerd.

_Actief_ - `status=active` - Standaard Topic templates die actief kunnen worden gebruikt en geconfigureerd om topics te genereren.

_Gearchiveerd_ - `status=archived` Topic templates die niet beschikbaar zijn voor gebruik of configuratie in het topic-generatieproces.

## 3. **Templates-tabel**

Nadat u naar uw pagina Topic template-instellingen bent genavigeerd, ziet u een overzicht van bestaande topic templates die eerder zijn gemaakt. Dit is wat de topic templates-tabel eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/04-templates-table.png)

Klik [hier](https://support.catenda.com/en/articles/11748020-tables-on-catenda) om meer te lezen over hoe u met tabellen in Catenda werkt.

### 3.1 **Rijinhoud**

Klik op een topic-rij om de inhoudspagina van de topic template voor die template te openen.

### 3.2 **Kolommen**

Alle kolommen in de topic templates-tabel zijn standaard ingeschakeld. Op basis van de geconfigureerde kolomvolgorde worden de eerste kolommen weergegeven, terwijl u de tabel mogelijk horizontaal moet schuiven om andere ingeschakelde kolommen weer te geven. De standaardvolgorde en zichtbaarheidsinstelling van de kolommen op de documenten-pagina is als volgt:

Naam Templatetype Gemaakt door Gemaakt op Status Topic board

## 4. **Een nieuwe algemene topic template maken**

Kan worden gebruikt voor topics die zijn gemaakt vanuit de algemene Topic-sectie. Dit zijn de verschillende acties die u moet volgen en variabelen die u kunt invoeren bij het maken van een nieuwe algemene topic template:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/05-create-a-new-general-topic-template.png)

1. **Topic Board**: De topic board waarbinnen de algemene topic template kan worden gegenereerd.
1. **Template-naam**: De template-naam kan tijdens het maken worden geselecteerd in het vervolgkeuzemenu, of deze kan later in de instellingen worden bijgewerkt als dat nodig is.
1. **Onderwerptitel**: De resulterende topic-titel na het maken van het topic vanuit de algemene topic template.
   Beweeg de muis over het pictogram "?" in de rechterbovenhoek van het titelvak om te zien hoe u de titel van uw topic template kunt aanpassen met de beschikbare variabele: `topicCreator`.

    <div class="intercom-container intercom-align-center"><img height="184" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-272165f584d2.png" style="height: auto;" width="300"/></div>

1. **Onderwerp-status**: De resulterende topic-status na het maken van het topic vanuit de algemene topic template.
1. **Onderwerpstype**: Het resulterende topic-type na het maken van het topic vanuit de algemene topic template.
1. **Milestone**: De resulterende topic milestone na het maken van het topic vanuit de algemene topic template.
1. **Toegewezen aan**: De resulterende topic-ontvanger (projectlid of team) na het maken van het topic vanuit de algemene topic template. U kunt hier de variabele `Topic Creator` gebruiken om dit veld automatisch in te vullen met de topic-maker indien nodig.

    <div class="intercom-container intercom-align-center"><img height="94" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-c7f3d7220c54.png" style="height: auto;" width="150"/></div>

1. **Aangevraagd door**: De resulterende topic-aanvrager na het maken van het topic vanuit de algemene topic template. U kunt hier de variabele `Topic Creator` gebruiken om dit veld automatisch in te vullen met de topic-maker indien nodig.

    <div class="intercom-container intercom-align-center"><img height="93" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-43e4955bfdd8.png" style="height: auto;" width="150"/></div>

1. **Labels**: De resulterende topic-labels na het maken van het topic vanuit de algemene topic template.
1. **Beschrijving**: De resulterende topic-beschrijving na het maken van het topic vanuit de algemene topic template. Deze sectie ondersteunt de Markdown-indeling en u kunt het volledige potentieel ervan gebruiken om tekst op te maken, aangepaste headers en checklists te maken.
    Beweeg de muis over het pictogram "?" in de rechterbovenhoek van het beschrijvingsvak om te zien hoe u alle beschikbare functies (vermeld teamgenoten en koppel bestaande topics) en variabelen (zoals `topicCreator` in het geval van de algemene topic template) kunt gebruiken.

     <div class="intercom-container intercom-align-center"><img height="291" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-d2735ca1aec8.png" style="height: auto;" width="300"/></div>

Nadat u klaar bent met het instellen van uw nieuwe algemene topic template, kunt u op de knop "Opslaan" rechtsonder klikken.

## 5. **Nieuwe document topic template**

Kan worden gebruikt voor topics die zijn gemaakt vanuit Markups op Documenten. Dit zijn de verschillende acties die u moet volgen en variabelen die u kunt invoeren bij het maken van een nieuwe document topic template:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/06-new-document-topic-template.png)

1. **Topic Board**: De topic board waarbinnen de document topic template kan worden gegenereerd.
1. **Template-naam**: De template-naam kan tijdens het maken van Markup worden geselecteerd in het vervolgkeuzemenu, of deze kan later in de instellingen worden bijgewerkt als dat nodig is.
1. **Onderwerptitel**: De resulterende topic-titel na het maken van het topic vanuit de document topic template.
   Beweeg de muis over het pictogram "?" aan de rechterkant van het titelvak om te zien hoe u de titel van uw document topic template kunt aanpassen met de beschikbare variabelen: `documentName`, `fileName`, `markupName` en `topicCreator`.

    <div class="intercom-container intercom-align-center"><img height="231" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-dbe5030f1082.png" style="height: auto;" width="300"/></div>

1. **Onderwerp-status**: De resulterende topic-status na het maken van het topic vanuit de document topic template.
1. **Onderwerpstype**: Het resulterende topic-type na het maken van het topic vanuit de document topic template.
1. **Milestone**: De resulterende topic milestone na het maken van het topic vanuit de document topic template.
1. **Toegewezen aan**: De resulterende topic-ontvanger (projectlid of team) na het maken van het topic vanuit de document topic template. Hier kunnen verschillende variabelen worden gebruikt, zoals `Document owner`, `File uploader`, `Markup creator`, `Publisher` en `Topic creator`.

    <div class="intercom-container intercom-align-center"><img height="228" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b3156a6c2724.png" style="height: auto;" width="150"/></div>

1. **Aangevraagd door**: De resulterende topic-aanvrager na het maken van het topic vanuit de document topic template. Hier kunnen verschillende variabelen worden gebruikt, zoals `Document owner`, `File uploader`, `Markup creator`, `Publisher` en `Topic creator`.

    <div class="intercom-container intercom-align-center"><img height="171" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-0c4680dfae06.png" style="height: auto;" width="150"/></div>

1. **Labels**: De resulterende topic-labels na het maken van het topic vanuit de document topic template. Houd er rekening mee dat u de labels van het document waaruit u de Markup hebt gemaakt, kunt ophalen met behulp van de variabele `Labels from documents` hieronder:

    <div class="intercom-container intercom-align-center"><img height="67" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-522016d4b8ae.png" style="height: auto;" width="500"/></div>

1. **Beschrijving**: De resulterende topic-beschrijving na het maken van het topic vanuit de document topic template. Deze sectie ondersteunt de Markdown-indeling en u kunt het volledige potentieel ervan gebruiken om tekst op te maken, aangepaste headers en checklists te maken.
    Beweeg de muis over het pictogram "?" in de rechterbovenhoek van het beschrijvingsvak om te zien hoe u alle beschikbare functies (vermeld teamgenoten en koppel bestaande topics) en variabelen (zoals `documentName`, `fileName`, `markupName` en `topicCreator` in het geval van de document topic template) kunt gebruiken.

     <div class="intercom-container intercom-align-center"><img height="349" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b8f3e2dabde9.png" style="height: auto;" width="300"/></div>

Nadat u klaar bent met het instellen van uw nieuwe document topic template, kunt u op de knop "Opslaan" rechtsonder klikken.

## 6. **Nieuwe goedkeurings topic template**

Kan worden gebruikt voor topics die zijn gegenereerd nadat een goedkeuringswerkstroom is gesloten. _Vereiste toegang:_ Gedeelde statussen ingeschakeld (Tabbladen Workspace en Published zichtbaar op pagina's Documenten en Modellen)

> **Opmerking:** Deze optie verschijnt alleen als huidige status- en validatiewerkstromen in gebruik zijn. Projecten die na 2 oktober 2025 zijn gemaakt, gebruiken automatisch huidige status- en validatiewerkstromen.

Dit zijn de verschillende acties die u moet volgen en variabelen die u kunt invoeren bij het maken van een nieuwe goedkeurings topic template:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/07-new-approval-topic-template.png)

1. **Topic Board**: De topic board waarbinnen de goedkeurings topic template na het sluiten van een goedkeuringswerkstroom wordt gegenereerd.
1. **Template-naam**: De template-naam van een goedkeurings topic template kan worden geselecteerd in het vervolgkeuzemenu in een goedkeuringswerkstroom template, of deze kan later in de instellingen worden bijgewerkt als dat nodig is.
1. **Onderwerptitel**: De resulterende topic-titel na het sluiten van de gekoppelde goedkeuringswerkstroom.
   Beweeg de muis over het pictogram "?" aan de rechterkant van het titelvak om te zien hoe u de titel van uw goedkeurings topic template kunt aanpassen met de beschikbare variabelen: `approvalRequestName`, `approvalRequestNumber`, `documentName`, `fileName`, `markupName` en `topicCreator`.

    <div class="intercom-container intercom-align-center"><img height="272" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-6038b1d41fed.png" style="height: auto;" width="300"/></div>

1. **Onderwerp-status**: De resulterende topic-status na het sluiten van de gekoppelde goedkeuringswerkstroom.
1. **Onderwerpstype**: Het resulterende topic-type na het sluiten van de gekoppelde goedkeuringswerkstroom.
1. **Milestone**: De resulterende topic milestone na het sluiten van de gekoppelde goedkeuringswerkstroom.
1. **Toegewezen aan**: De resulterende topic-ontvanger (projectlid of team) na het sluiten van de gekoppelde goedkeuringswerkstroom. Hier kunnen verschillende variabelen worden gebruikt, zoals `Approval request approver`, `Approval requested approver team`, `Approval request submitter`, `Approval request submitter team`, `Document owner`, `File uploader`, `Markup creator`, `Markup creator team`, `Publisher`.

    <div class="intercom-container intercom-align-center"><img height="182" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-b012d92ee132.png" style="height: auto;" width="150"/></div>

1. **Aangevraagd door**: De resulterende topic-aanvrager na het sluiten van de gekoppelde goedkeuringswerkstroom. Hier kunnen verschillende variabelen worden gebruikt, zoals `Approval request approver`, `Approval requested approver team`, `Approval request submitter`, `Approval request submitter team`, `Document owner`, `File uploader`, `Markup creator`, `Markup creator team`, `Publisher`.

    <div class="intercom-container intercom-align-center"><img height="181" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-d7986adac70c.png" style="height: auto;" width="150"/></div>

1. **Labels**: De resulterende topic-labels na het sluiten van de gekoppelde goedkeuringswerkstroom. Houd er rekening mee dat u de labels van het document waaruit u de Markup hebt gemaakt, kunt ophalen met behulp van de variabele `Labels from documents` hieronder:

    <div class="intercom-container intercom-align-center"><img height="67" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-522016d4b8ae.png" style="height: auto;" width="500"/></div>

1. **Beschrijving**: De resulterende topic-beschrijving na het sluiten van de gekoppelde goedkeuringswerkstroom. Deze sectie ondersteunt de Markdown-indeling en u kunt het volledige potentieel ervan gebruiken om tekst op te maken, aangepaste headers en checklists te maken.
    Beweeg de muis over het pictogram "?" in de rechterbovenhoek van het beschrijvingsvak om te zien hoe u alle beschikbare functies (vermeld teamgenoten en koppel bestaande Topics) en variabelen (zoals `approvalRequestDueDate`, `approvalRequestFileLink`, `approvalRequestLink`, `approvalRequestName`, `approvalRequestNumber`, `documentName`, `fileName`, `markupName`, `topicCreator`) in het geval van de goedkeurings template kunt gebruiken).

     <div class="intercom-container intercom-align-center"><img height="449" src="https://raw.githubusercontent.com/catenda/help-center/main/images/rf9vjf2t/inline-f3f078b5d2af.png" style="height: auto;" width="300"/></div>

Nadat u klaar bent met het instellen van uw nieuwe goedkeurings topic template, kunt u op de knop "Opslaan" rechtsonder klikken.
