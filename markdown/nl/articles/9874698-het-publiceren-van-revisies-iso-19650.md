# Nieuwe statuswerkstroom - ISO 19650

De nieuwe statuswerkstroom is een functie op aanvraag die kan worden ingeschakeld voor lopende projecten. Nieuwe projecten die zijn gemaakt op basis van een templateproject waarbij deze functie is ingeschakeld, hebben deze functie ingeschakeld. De ISO 19650-serie is een internationale norm voor goed beheer die informatiemanagementprocessen definieert in een bredere context van digitale transformatie in de bouwsector. Veel belanghebbenden in de bouwsector hebben ISO 19650 als standaard aangenomen om documentlevering en goedkeuringsprocedures in projecten te beheren.

## 1. **Levenscyclus van een document**

Volgens de ISO-norm kan een document vier verschillende staten hebben;

### 1.1 **🏗️ Werk in uitvoering (WiP)**

Bestanden waaraan wordt gewerkt en die voortdurend worden overschreven in de lokale omgeving van de gebruiker. Deze bestanden worden doorgaans alleen naar Catenda geüpload zodat mensen de voortgang van de gebruiker kunnen zien.

### 1.2 **👥 Gedeeld**

Bestanden die gereed zijn om te worden gedeeld met andere projectleden voor coördinatie en eindcontroles van verschillende bouwdelen en/of specialisten. Deze bestanden worden naar Catenda geüpload en ter controle en goedkeuring naar de respectieve partijen verzonden.

### 1.3 **📰 Gepubliceerd**

Bestanden die zijn gecoördineerd, voltooid en aanvaard als contractueel resultaat. Deze bestanden hebben een controleproces ondergaan en worden geacht "gereed voor de volgende fase (bouw, overdracht, hoeveelheidsbepaling, vergunningverlening, enz.)"

### 1.4 **📦 Gearchiveerd**

De informatie is gebruikt en kan worden gearchiveerd om indien nodig later beschikbaar te blijven (audit, aanmaking van het dossier uitgevoerde werken, enz.)

### 1.5 **Documentstaten - ISO 19650**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/01-document-states-iso-19650.png)

### 1.6 **Werkstroom op Catenda Hub**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/02-workflow-on-catenda-hub.png)

## 2. **Statusinstellingen configureren**

Het inschakelen en configureren van de gedeelde statusinstellingen zijn voorbehouden aan projectbeheerders.

_Vereiste toegang_ Toegang tot documentstatusconfiguratie in het [toegangscontrolebied](https://support.catenda.com/en/articles/4670273-project-settings-page#h_3b98ced32a) van de [projectinstellingenpagina](https://support.catenda.com/en/articles/4670273-project-settings-page). Leden met deze toegang hebben alleen toegang tot het statusconfiguratiemenu in documentinstellingen. Ze kunnen de andere menu's in documentinstellingen niet zien of wijzigen.

Ga in [documentinstellingen](https://support.catenda.com/en/articles/7831371-document-settings) naar [Statusinstellingen](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) en schakel gedeelde statussen in

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/03-configuring-status-workflow.png)

Definieer de gedeelde en gepubliceerde statussen die in het project worden gebruikt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/04-configuring-status-workflow.png)

Stel de standaard gedeelde status voor nieuwe revisies in. Nieuwe revisies worden in eerste instantie als gedeelde revisies geüpload die later kunnen worden gepubliceerd. De standaardstatus moet daarom een gedeelde revisiestatus zijn. Deze status wordt in het uploaddialoogvenster voor elke documentupload geselecteerd en kan in het uploadproces worden gewijzigd in een andere gedeelde status.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/05-configuring-status-workflow.png)

## 3. **Vertrouwd maar anders**

Na het inschakelen van de statusinstellingen verschijnen er twee tabbladen boven de documenten- en modellentabellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/06-familiar-but-different.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/07-familiar-but-different.png)

### 3.1 **Werkruimte**

Alle uploads van nieuwe revisies vinden hier plaats. De nieuwste gedeelde revisie wordt voor elk document en model weergegeven.

### 3.2 **Gepubliceerd**

Een gespiegelde versie van het werkruimtetabblad. Dezelfde mapstructuur als in de werkruimte wordt weergegeven. Alleen documenten en modellen met gepubliceerde revisies worden weergegeven.

> **Opmerking:** Zie gedeelde revisies in het revisieoverzicht van het documentvoorbeeld, zelfs als u het document van het gepubliceerde tabblad hebt geopend. _Vereiste toegang:_ Gedeelde revisies

### 3.3 **Nieuwe gedeelde revisies uploaden**

Voor elk geüpload bestand zal een revisiestatus zichtbaar zijn in het uploaddialoogvenster.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/08-upload-new-shared-revisions.png)

Voor elk bestand dat uit een gezipte map wordt gehaald, zal een revisiestatus worden toegepast.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/09-upload-new-shared-revisions.png)

### 3.4 Gedeelde revisies publiceren

**Meerdere documenten in documentstructuur** Een publicatieactie is beschikbaar in het bestaande elementactiemenu van een of meer geselecteerde documenten met gedeelde revisies.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/10-publish-shared-revisions.png)

**Enkele revisie in documentvoorbeeld of documentstructuur** Een publicatieactie is beschikbaar als pictogram en in het actiemenu van de revisieinfo van een gedeelde revisie in het menu met rechtsinformatie.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/11-publish-shared-revisions.png)

**Meerdere modellen** Een publicatieactie is beschikbaar in de revisieinfo van een document met een gedeelde revisie in het menu met rechtsinformatie in de documentstructuur en in het documentvoorbeeld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/12-publish-shared-revisions.png)

_Vereiste toegang:_ Gedeelde revisies

### 3.5 **Toegangsbeheer**

Nadat de statusinstellingen zijn ingeschakeld, ziet u twee nieuwe kolommen verschijnen rechts van de toegangskolom in het toegangsbeheerdialoogvenster van een map of document.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/13-access-control.png)

De tabel hieronder verklaart hoe de vinkjes de gebruikerservaring voor elk toegangsniveau beïnvloeden.

- Vink "kan publiceren" aan voor een lid of team met schrijftoegang om hen toe te staan gedeelde revisies te publiceren en gepubliceerde revisiestatussen te bewerken.
- Vink "gedeelde revisies weergeven" uit voor een lid of team met leestoegang, zodat ze alleen officiële, gepubliceerde revisies zien.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80;"><h3 id="h_e9579ad9ca"><b>Gedeeld gepubliceerde toegang</b></h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_dea1580c70">Lezen</h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_3c6b6d7d28">Schrijven</h3></td></tr><tr><td><h3 id="h_a33339c27e">Kan "Gedeelde revisies weergeven" aanvinken</h3></td><td><p class="intercom-align-center">Kan aanvinken. <br/>Standaard niet aangevinkt.</p></td><td><p class="intercom-align-center">Altijd aangevinkt</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_e909b5dc48">Kan "Kan publiceren" aanvinken</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Nooit aangevinkt</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Kan uitvinken. <br/>Standaard aangevinkt</p></td></tr><tr><td><h3 id="h_95374b8adf">Documenten weergeven</h3></td><td><p class="intercom-align-center">Documenten met alleen gedeelde revisies zijn alleen zichtbaar als "gedeelde revisies weergeven" is aangevinkt</p></td><td><p class="intercom-align-center">Zowel documenten met gedeelde als documenten met gepubliceerde revisies zijn zichtbaar</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_e401f7a37f">Gedeelde revisies in documentinfo weergeven</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Gedeelde revisies zijn alleen zichtbaar als "gedeelde revisies weergeven" is aangevinkt</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Zowel gedeelde als gepubliceerde revisies zijn zichtbaar</p></td></tr><tr><td><h3 id="h_13cbc969df">Gedeelde revisiestatussen bewerken en weergeven</h3></td><td><p class="intercom-align-center">Zichtbaar als "gedeelde revisies weergeven" is aangevinkt, maar niet bewerkt</p></td><td><p class="intercom-align-center">x</p></td></tr><tr><td style="background-color: #e8e8e880;"><h3 id="h_b228d7c432">Gepubliceerde revisiestatussen bewerken en weergeven</h3></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Kan alleen de status van gepubliceerde revisies weergeven</p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">Bewerken als "Kan publiceren" is aangevinkt, anders alleen zichtbaar</p></td></tr><tr><td><h3 id="h_13248acfd2">Documenten publiceren</h3></td><td><p class="intercom-align-center">-</p></td><td><p class="intercom-align-center">Publiceren als "Kan publiceren" is aangevinkt</p></td></tr></tbody></table></div>

### 3.6 **Hoofd- en bijversienummers**

Gedeelde revisies hebben een bijversienummer (bijv. #0.1, #2.3, #4.1) Gepubliceerde revisies hebben een hoofdversienummer (#1, #2, #3 en ga zo maar door)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/14-major-and-minor-revision-numbers.png)

### 3.7 Het documentvoorbeeld openen

In de documentstructuur ziet u de nieuwste revisie waartoe u toegang hebt. Klik op de naam van een document om het documentvoorbeeld van de weergegeven revisie te openen.

**Werkruimtetabblad** De nieuwste revisie in het werkruimtetabblad kan zijn: Gedeelde revisie - _Vereiste toegang:_ Gedeelde revisies Gepubliceerde revisie - ​_Vereiste toegang:_ Lezen

**Gepubliceerd tabblad** De nieuwste revisie in het gepubliceerde tabblad kan zijn: Gepubliceerde revisie - _Vereiste toegang:_ Lezen

> **Opmerking:** Gedeelde revisies kunnen zichtbaar zijn in het revisieoverzicht van het documentvoorbeeld, zelfs als u het document van het gepubliceerde tabblad hebt geopend. _Vereiste toegang:_ Gedeelde revisies

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/15-opening-the-document-preview.png)

### 3.8 **Revisiegegevens**

Selecteer één document of open het documentvoorbeeld door op het document te klikken. Informatie over de huidige revisie wordt zichtbaar in het [menu met rechtsinformatie](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/16-revision-information.png)

- Publiceer de huidige revisie met de publicatieactie.
  _Vereiste toegang:_ Gedeelde revisies

- Wijzig een gedeelde revisiestatus in een ander gedeelde revisiestatus.
  _Vereiste toegang:_ Leestoegang en gedeelde revisies

- Wijzig een gepubliceerde revisiestatus in een ander gepubliceerde revisiestatus.
  _Vereiste toegang:_ Schrijftoegang en gepubliceerde revisies

**Dialoogvenster Revisiegegevens** Klik op het revisievak om een overzicht van alle revisies in het document in het [dialoogvenster revisiegegevens](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision#h_6838c6ad71) te zien. Een groene koppeling tussen een gepubliceerde en een gedeelde revisie geeft aan welke gedeelde revisie is gepubliceerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/17-revision-information.png)

### 3.9 Gedeelde en gepubliceerde revisies in Catenda Site

Alleen gepubliceerde revisies zijn zichtbaar in Catenda Site.

## 4. Toegang tot statusconfiguratie

1. Bewerkingstoegang tot de documentstatusconfiguratie kan worden geconfigureerd via de [projectinstellingenpagina](https://support.catenda.com/en/articles/4670273-project-settings-page):

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-868820a898ba.png" width="500"/></div>

2. De documentstatus kan vervolgens [geconfigureerd](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) worden vanuit de instellingen in de documentensectie:

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-931418a5fab1.png" width="500"/></div>

3. Ten slotte kunnen deze documentstatussen worden toegewezen aan bestandsreviesiestatus die toegankelijk is via de knop met drie puntjes rechtsboven in de [Goedkeuringssectie](https://support.catenda.com/en/articles/8349340-approvals-page). Het is ook mogelijk om hier een onderwerptemplate te configureren.

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-3cdbebefca38.png" width="500"/></div>

    <div class="intercom-container intercom-align-center"><img src="https://raw.githubusercontent.com/catenda/help-center/main/images/1csjjnv9/inline-f8ab7f3194ff.png" width="300"/></div>

## 5. **Goedkeuringswerkstroom**

1. Een goedkeuringswerkstroom wordt door een beheerder gemaakt.
   1. Verzendteam
   2. Beoordelingsteam (minstens één goedkeuringsstap is vereist)
   3. Uiteindelijk beoordelingsteam
2. Een lid van een verzendteam dient een goedkeuringsverzoek in met een reeks gedeelde revisies op de goedkeuringspagina.
3. Leden van de verzendteams die aan de stap zijn toegewezen beoordelen de in de goedkeuring ingediende documenten en geven een goedgekeurd of afgewezen validatie.
4. Nadat alle stappen zijn voltooid, beoordeelt een lid van het uiteindelijke beoordelingsteam de validaties die namens de verschillende teams in elke stap zijn ingediend en geeft hun eindvalidatie van goedgekeurd, goedgekeurd met opmerking of afgewezen.
   1. De eindgoedkeurder kan een eindgeldige, geïnformeerde beslissing nemen over of dit document moet worden gepubliceerd (goedgekeurd) of afgewezen (blijft gedeeld)

### 5.1 **Oudere goedkeuringswerkstroom**

1. Een goedkeuringsverzoek wijst een uitgever aan (persoon verantwoordelijk voor de eindebeslissing over publicatie) en een of meer beoordelaars, verantwoordelijk voor het valideren (of niet) van de reeks documenten
2. Elke beoordelaar bepaalt of het gedeelde document is Goedgekeurd, Goedgekeurd met opmerking of Afgewezen
3. Aan het einde van de beoordeling kiest de uitgever het resultaat van de goedkeuring door de documenten te selecteren die moeten worden gepubliceerd.
4. Vanuit de goedkeuringsinstellingen kunnen onderwerpen met betrekking tot de documenten worden aangemaakt om het proces later op te volgen

Een gedetailleerde demonstratie van deze stappen wordt getoond in de volgende tutorial:

[YouTube-video](https://www.youtube.com/embed/lDWKXWTtegU?rel=0)

## 6. **Statusinstellingen uitschakelen**

Als u de statusinstellingenwerkstroom wilt uitschakelen, kunt u dit doen door op de keuzerondje in [documentinstellingen](https://support.catenda.com/en/articles/7831371-document-settings) te klikken. De gepubliceerde en gedeelde tabbladen in de documentensectie verdwijnen vervolgens. Documenten die zijn geüpload terwijl de statusinstellingenwerkstroom niet is ingeschakeld, worden als gepubliceerd geüpload en verschijnen in het gepubliceerde tabblad wanneer de statusinstellingenwerkstroom wordt ingeschakeld.

## 7. **Voordelen van het gebruik van de statusinstellingenwerkstroom**

- Het gepubliceerde tabblad dient als een aangewezen gebied voor contractuele documenten. Projectleden kunnen geverifieerde documenten gemakkelijk vinden.
- Documenten worden gevalideerd voordat ze worden gepubliceerd
- U kunt uw leveringsproces veel gemakkelijker configureren op basis van ISO 19650
- Coördinatie-/samenwerkingsdocumenten zijn gescheiden van contractuele documenten
- Meerdere gedeelde revisies kunnen worden geselecteerd en gedownload, terwijl in de vorige versie concepten slechts één voor één konden worden gedownload
- Beperk wat mensen in de mobiele app Catenda Site kunnen zien
