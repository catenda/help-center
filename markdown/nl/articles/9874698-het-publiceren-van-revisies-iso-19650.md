# Nieuwe statusworkflow - ISO 19650

De nieuwe statusworkflow is een functie op aanvraag die voor lopende projecten kan worden ingeschakeld. Nieuwe projecten die zijn gebaseerd op een sjabloonproject waarbij deze functie is ingeschakeld, hebben deze functie ingeschakeld. De ISO 19650-reeks is een internationale norm voor goede praktijken die informatiemanagementprocessen binnen een bredere context van digitale transformatie in de bouw definieert. Veel belanghebbenden in de bouwsector hebben ISO-19650 aangenomen als de norm voor het beheren van documentbezorging en goedkeuringsprocedures in projecten.

## 1. **Levenscyclus van een document**

Volgens de ISO-norm kan een document vier verschillende toestanden hebben;

### 1.1 **🏗️ In uitvoering (WiP)**

Bestanden waaraan wordt gewerkt en die voortdurend worden overschreven in de lokale omgeving van de gebruiker. Deze bestanden worden meestal alleen naar catenda geüpload zodat mensen de voortgang van de gebruiker kunnen zien.

### 1.2 **👥 Gedeeld**

Bestanden die gereed zijn om te worden gedeeld met andere projectleden voor coördinatie en eindcontroles van verschillende vakgebieden en/of specialisten. Deze bestanden worden naar Catenda geüpload en naar respectieve partijen verzonden voor beoordeling en goedkeuring.

### 1.3 **📰 Gepubliceerd**

Bestanden die zijn gecoördineerd, voltooid en geaccepteerd als contractueel product. Deze bestanden hebben een beoordelingsproces doorlopen en worden geacht 'klaar voor het volgende stadium (bouw, overdracht, hoeveelheidsmeting, vergunningverlening, enz.)' te zijn

### 1.4 **📦 Gearchiveerd**

De informatie is gebruikt en kan worden gearchiveerd om indien nodig later beschikbaar te blijven (controle, aanmaking van het bestand van uitgevoerde werken, enz.)

### 1.5 **Documenttoestanden - ISO 19650**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/01-document-states-iso-19650.png)

### 1.6 **Workflow in Catenda Hub**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/02-workflow-on-catenda-hub.png)

## 2. **Statusworkflow configureren**

Activering en configuratie van de gedeelde statusworkflow zijn voorbehouden aan projectbeheerders.

_Vereiste toegang_ Documentstatusconfiguratie-toegang in het [toegangscontrolebereik](https://support.catenda.com/en/articles/4670273-project-settings-page#h_3b98ced32a) van de [projectinstellingenpagina](https://support.catenda.com/en/articles/4670273-project-settings-page). Leden met deze toegang hebben alleen toegang tot het statusconfiguratiemenu in documentinstellingen. Ze kunnen de andere menu's in documentinstellingen niet zien of wijzigen.

Navigeer onder [documentinstellingen](https://support.catenda.com/en/articles/7831371-document-settings) naar [Statusworkflow](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) en schakel gedeelde statussen in

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/03-configuring-status-workflow.png)

Definieer de gedeelde en gepubliceerde statussen die in het project worden gebruikt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/04-configuring-status-workflow.png)

Stel de standaard gedeelde status in voor nieuwe revisies. Nieuwe revisies worden aanvankelijk als gedeelde revisies geüpload en kunnen later worden gepubliceerd. De standaardstatus moet daarom een gedeelde revisiestatus zijn. Deze status wordt geselecteerd in het uploaddialoogvenster voor elke documentupload en kan tijdens het uploadproces worden gewijzigd in een andere gedeelde status.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/05-configuring-status-workflow.png)

## 3. **Vertrouwd maar anders**

Nadat u de statusworkflow activeert, ziet u twee tabbladen boven de tabellen met documenten en modellen verschijnen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/06-familiar-but-different.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/07-familiar-but-different.png)

### 3.1 **Werkruimte**

Alle uploads van nieuwe revisies vinden hier plaats. De nieuwste gedeelde revisie wordt voor elk document en model weergegeven.

### 3.2 **Gepubliceerd**

Een gespiegelde versie van het werkruimtetabblad. Dezelfde mapstructuur als in de werkruimte wordt weergegeven. Alleen documenten en modellen met gepubliceerde revisies worden weergegeven.

> **Opmerking:** Bekijk gedeelde revisies in het revisieoverzicht van de documentvoorvertoning, zelfs als u het document vanaf het gepubliceerde tabblad hebt geopend. _Vereiste toegang:_ Gedeelde revisies

### 3.3 **Nieuwe gedeelde revisies uploaden**

Een revisiestatus is zichtbaar voor elk geüpload bestand in het uploaddialoogvenster.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/08-upload-new-shared-revisions.png)

Een revisiestatus wordt toegepast op elk bestand dat uit een gezipt bestand wordt geëxtraheerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/09-upload-new-shared-revisions.png)

### 3.4 Gedeelde revisies publiceren

**Meerdere documenten in documentstructuur** Een publicatieactie is beschikbaar in het bestaande elementactiemenu van een of meer geselecteerde documenten met gedeelde revisies.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/10-publish-shared-revisions.png)

**Enkele revisie in documentvoorvertoning of documentstructuur** Een publicatieactie is beschikbaar als pictogram en in het actiemenu van de revisie-informatie van een gedeelde revisie in het rechtermenu met informatie.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/11-publish-shared-revisions.png)

**Meerdere modellen** Een publicatieactie is beschikbaar in de revisie-informatie van een document met een gedeelde revisie in het rechtermenu met informatie in de documentstructuur en in de documentvoorvertoning.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/12-publish-shared-revisions.png)

_Vereiste toegang:_ Gedeelde revisies

### 3.5 **Toegangscontrole**

Nadat de statusworkflow is ingeschakeld, ziet u twee nieuwe kolommen verschijnen rechts van de toegangskolom in het dialoogvenster voor toegangscontrole van een map of document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/13-access-control.png)

De tabel hieronder beschrijft hoe de selectievakjes het gebruikerservaring voor elk toegangsniveau beïnvloeden.

- Schakel "kan publiceren" in voor een lid of team met schrijftoegang zodat zij gedeelde revisies kunnen publiceren en statussen van gepubliceerde revisies kunnen bewerken.
- Schakel "gedeelde revisies bekijken" uit voor een lid of team met leestoegang zodat zij alleen officiële, gepubliceerde revisies zien.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><h3 id="h_e9579ad9ca"><b>Gedeelde gepubliceerde toegang</b></h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 class="intercom-align-center" id="h_dea1580c70">Lezen</h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 class="intercom-align-center" id="h_3c6b6d7d28">Schrijven</h3></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_a33339c27e">Kan "Gedeelde revisies bekijken" controleren</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Kan controleren. <br/>Standaard uitgeschakeld.</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Altijd ingeschakeld</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_e909b5dc48">Kan "Kan publiceren" controleren</h3></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Nooit ingeschakeld</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Kan uitschakelen. <br/>Standaard ingeschakeld</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_95374b8adf">Documenten weergeven</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Documenten met alleen gedeelde revisies zijn alleen zichtbaar als "gedeelde revisies bekijken" is ingeschakeld</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Beide documenten met gedeelde en documenten met gepubliceerde revisies zijn zichtbaar</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_e401f7a37f">Gedeelde revisies in documentinformatie weergeven</h3></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Gedeelde revisies zijn alleen zichtbaar als "gedeelde revisies bekijken" is ingeschakeld</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Zowel gedeelde als gepubliceerde revisies zijn zichtbaar</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_13cbc969df">Statussen van gedeelde revisies bewerken en weergeven</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Zichtbaar als "gedeelde revisies bekijken" is ingeschakeld, maar niet bewerkt</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_b228d7c432">Statussen van gepubliceerde revisies bewerken en weergeven</h3></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Kan alleen gepubliceerde revisiestatus weergeven</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Bewerken als "Kan publiceren" is ingeschakeld, anders alleen zichtbaar</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_13248acfd2">Documenten publiceren</h3></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">Publiceren als "Kan publiceren" is ingeschakeld</p></td></tr></tbody></table></div>

### 3.6 **Grote en kleine revisienummers**

Gedeelde revisies hebben een klein revisienummer (bijv. #0.1, #2.3, #4.1) Gepubliceerde revisies hebben een groot revisienummer (#1, #2, #3 enz.)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/14-major-and-minor-revision-numbers.png)

### 3.7 De documentvoorvertoning openen

In de documentstructuur ziet u de nieuwste revisie waartoe u toegang hebt. Klik op de naam van een document om de documentvoorvertoning van de weergegeven revisie te openen.

**Werkruimtetabblad** De nieuwste revisie op het werkruimtetabblad kan zijn: Gedeelde revisie - _Vereiste toegang:_ Gedeelde revisies Gepubliceerde revisie - _Vereiste toegang:_ Lezen

**Gepubliceerd tabblad** De nieuwste revisie op het gepubliceerde tabblad kan zijn: Gepubliceerde revisie - _Vereiste toegang:_ Lezen

> **Opmerking:** Gedeelde revisies kunnen zichtbaar zijn in het revisieoverzicht van de documentvoorvertoning, zelfs als u het document vanaf het gepubliceerde tabblad hebt geopend. _Vereiste toegang:_ Gedeelde revisies

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/15-opening-the-document-preview.png)

### 3.8 **Revisie-informatie**

Selecteer een enkel document of open de documentvoorvertoning door op het document te klikken. Informatie over de huidige revisie is zichtbaar in het [rechtermenu met informatie](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/16-revision-information.png)

- Publiceer de huidige revisie met de publicatieactie.
  _Vereiste toegang:_ Gedeelde revisies

- Wijzig een gedeelde revisiestatus in een andere gedeelde revisiestatus.
  _Vereiste toegang:_ Leestoegang en gedeelde revisies

- Wijzig een gepubliceerde revisiestatus in een andere gepubliceerde revisiestatus.
  _Vereiste toegang:_ Schrijftoegang en gepubliceerde revisies

**Dialoogvenster revisie-informatie** Klik op het revisievak om een overzicht van alle revisies in het document in het [dialoogvenster revisie-informatie](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision#h_6838c6ad71) te zien. Een groene verbinding tussen een gepubliceerde en een gedeelde revisie geeft aan welke gedeelde revisie is gepubliceerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/17-revision-information.png)

### 3.9 Gedeelde en gepubliceerde revisies in Catenda Site

Alleen gepubliceerde revisies zijn zichtbaar in Catenda Site.

## 4. Statusconfiguratietoegang

1. Bewerktoegang tot de documentstatusconfiguratie kan worden geconfigureerd op de [projectinstellingenpagina](https://support.catenda.com/en/articles/4670273-project-settings-page):

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-868820a898ba.png" width="500"/></div>

1. Documentstatus kan vervolgens [geconfigureerd](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) worden vanuit de instellingen in de documentsectie:

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-931418a5fab1.png" width="500"/></div>

1. Ten slotte kunnen deze documentstatussen worden toegewezen aan de status voor bestandsbeoordeling, toegankelijk vanuit de knop met drie punten rechtsboven in de [sectie Goedkeuringen](https://support.catenda.com/en/articles/8349340-approvals-page). Het is ook mogelijk om hier een onderwerpsjabloon te configureren.

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-3cdbebefca38.png" width="500"/></div>

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-f8ab7f3194ff.png" width="300"/></div>

## 5. **Goedkeuringswerkflow**

1. Een goedkeuringswerkflow wordt door een beheerder gemaakt.
   1. Team indieners
   1. Beoordelarenteam (minimaal één goedkeuringsstap is vereist)
   1. Team eindbeoordelaar
1. Een lid van een indienersteam dient een goedkeuringsaanvraag met een reeks gedeelde revisies in op de goedkeuringspagina.
1. Leden van de indienersteams die aan de stap zijn toegewezen, beoordelen de documenten die in de goedkeuring zijn ingediend en geven een goedgekeurd of afgewezen validatie.
1. Nadat alle stappen zijn voltooid, beoordeelt een lid van het eindbeoordelarenteam de validaties die namens de verschillende teams in elke stap zijn ingediend en geeft hun uiteindelijke validatie van goedgekeurd, goedgekeurd met opmerking of afgewezen.
   1. De eindgoedkeurder kan een definitieve, ingelijchte beslissing nemen of dit document moet worden gepubliceerd (goedgekeurd) of afgewezen (als gedeeld blijft)

### 5.1 **Verouderde goedkeuringswerkflow**

1. Een goedkeuringsaanvraag benoemt een Uitgever (persoon verantwoordelijk voor het nemen van de uiteindelijke beslissing over de publicatie) en een of meer Beoordelaars, verantwoordelijk voor het valideren (of niet) van de set documenten
1. Elke beoordelaar bepaalt of het gedeelde document wordt goedgekeurd, goedgekeurd met opmerking of afgewezen
1. Aan het einde van de beoordeling kiest de Uitgever het resultaat van de goedkeuring door de documenten te selecteren die moeten worden gepubliceerd.
1. Vanuit de goedkeuringsinstellingen kunnen onderwerpen met betrekking tot de documenten worden aangemaakt om het proces later bij te houden

Een gedetailleerde demonstratie van deze stappen wordt in de volgende zelfstudie getoond:

[YouTube-video](https://www.youtube.com/embed/lDWKXWTtegU?rel=0)

## 6. **Statusworkflow uitschakelen**

Als u de statusworkflowstroom wilt uitschakelen, kunt u dit doen door op de keuzerondje in [documentinstellingen](https://support.catenda.com/en/articles/7831371-document-settings) te klikken. De gepubliceerde en gedeelde tabbladen in de documentsectie verdwijnen vervolgens. Documenten die zijn geüpload terwijl de statusworkflow niet is ingeschakeld, worden als gepubliceerd geüpload en verschijnen op het gepubliceerde tabblad wanneer de statusworkflow wordt ingeschakeld.

## 7. **Voordelen van het gebruik van de statusworkflow**

- Het gepubliceerde tabblad dient als aangewezen gebied voor contractuele documenten. Projectleden kunnen geverifieerde documenten gemakkelijk vinden.
- Documenten worden gevalideerd voordat zij worden gepubliceerd
- U kunt uw leveringsproces op basis van ISO 19650 veel gemakkelijker configureren
- Coördinatie-/samenwerkingsdocumenten zijn gescheiden van contractuele documenten
- Meerdere gedeelde revisies kunnen worden geselecteerd en gedownload, terwijl in de vorige versie concepten slechts één voor één konden worden gedownload
- Beperken wat mensen kunnen zien in de mobiele app Catenda Site
