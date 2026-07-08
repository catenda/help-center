# Toolbox voor postvormgeving

> Hoe velden waar berichten kunnen worden gemaakt, kunnen worden opgemaakt

Dezelfde opmaakregels gelden voor de verschillende berichten in Catenda Hub. Berichten kunnen topic-beschrijvingen, opmerkingen, goedkeuringsbeschrijvingen en goedkeuringscommentaren bevatten. Variaties kunnen voorkomen met verschillende toegangsrechten voor wie het bericht kan bewerken. Catenda gebruikt markdown voor tekstopmaak. Dit betekent dat bepaalde tekens voor en na zinnen de stijl van de tekst beïnvloeden. Dit is hoe een topic-header en beschrijving er uit kunnen zien nadat ze zijn ingediend:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/01-intro.png)

## 1. Beschikbaarheid van opmaak

Vaak kun je zien dat ingediende velden kunnen worden opgemaakt door de toolbox die onder het veld verschijnt wanneer het veld wordt bewerkt.

> **Opmerking:** Zoom ver genoeg uit met de browserzoomschaal om alle gereedschappen te zien.

Opmaak is beschikbaar in de volgende velden:

### 1.1 **Topic-beschrijving en opmerking**

Bewerk de beschrijving of opmerking van een bestaand topic of bij het indienen van een nieuw topic om de toolbox te zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/02-topic-description-and-comment.png)

### 1.2 **Goedkeuringsbeschrijving**

Hoewel de toolbox niet in de beschrijving van het dialoogvenster voor nieuwe goedkeuringsaanvragen verschijnt, wordt opmaak wel op deze beschrijving toegepast.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/03-approval-request-description.png)

> **Opmerking:** Dit veld kan niet meer worden bewerkt nadat de goedkeuringsaanvraag is ingediend.

### 1.3 Topic-bordbeschrijving

Hoewel de toolbox in de beschrijving van de nieuw topic-bord wordt weergegeven, is het belangrijk op te merken dat de beschrijving niet wordt opgemaakt wanneer de bord wordt ingediend.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/04-topic-board-description.png)

## 2. **Topic-commentaarbijlage**

In topic-opmerkingen is een bijlagetool zichtbaar. Klik op de +-knop in een topic om een bijlage toe te voegen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/05-topic-comment-attachment.png)

Klik [hier](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_0e3c0059ae) voor meer informatie over commentaarbijlagen.

## 3. **Tekst opmaken**

De volgende methoden stellen u in staat uw tekst op te maken:

### 3.1 **Vet, cursief, doorgestreept**

Vet, cursief en doorgestreept kunnen overal op een regel worden toegepast en werken goed samen met andere opmaak die aan het begin van een regel moet staan.

<img alt="**Dit zal vet zijn** __Dit zal ook vet zijn__ *Dit zal cursief zijn* _Dit zal ook cursief zijn_ **Dit zal vet zijn _gecombineerd met cursief_** ~~Deze tekst zal doorgestreept zijn~~" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-b49c2f10b2de.png" width="290"/>   \<->   <img alt="Dit zal vet zijn Dit zal ook vet zijn Dit zal cursief zijn Dit zal ook cursief zijn Dit zal vet zijn gecombineerd met cursief Deze tekst zal doorgestreept zijn" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-ea38fb93f8ee.png" width="290"/>

### 3.2 **Koppen**

Het koppenhulpmiddel voegt hashtags/pond-tekens toe aan het begin van de regel. Er worden 5 niveaus van koppen ondersteund: De opmaak die de kop ontvangt, hangt af van het aantal hashtags/pond-tekens (`#`) aan het begin van de regel.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-c21079ec7efb.png" width="290"/>   \<->   <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-557784a5d702.png" width="290"/>

### 3.3 **Koppelingen**

Koppelingopmaak kan overal op een regel worden toegepast en werkt goed samen met andere opmaak die aan het begin van een regel moet staan. Koppelingen in beschrijvingen zijn groen en onderstreept. Hun tekst kan anders zijn dan de URL waar de koppeling naar verwijst. URL's worden automatisch omgezet in klikbare koppelingen

```
https://hub.catenda.com
```

wordt [https://hub.catenda.com](https://hub.catenda.com) en

```
[Catenda Hub](https://hub.catenda.com)
```

wordt: [Catenda Hub](https://hub.catenda.com)

> **Opmerking:** Wees voorzichtig bij het klikken op koppelingen, omdat hoewel de tekst [uit de vierkante haken] één koppeling kan tonen, de werkelijke koppeling (uit de haakjes) anders kan zijn. Het wordt aanbevolen om over een koppeling te zweven en te kijken naar waar de browser naartoe zal leiden voordat u op een koppeling klikt.

### 3.4 **Opmaak voorkomen**

Door woorden in niet-letter- of nummertekens in te pakken, kunt u deze er anders uit laten zien. Dit is niet altijd gewenst. Als u `\\` voor zo'n teken plaatst, verdwijnt de `\\`. Alle opmaak die voor deze tekens zou zijn toegepast, werkt dan niet meer. Als u `\\` op een lege regel plaatst die geen onderdeel is van een [lijst](#lists), blijft het resultaat ook een lege regel.

## 4. **Tekst opsplitsen en structuur toevoegen**

De volgende methoden stellen u in staat uw tekst te verbeteren door deze op te splitsen en structuur toe te voegen:

### 4.1 **Afbeeldingen**

Afbeeldingen in beschrijvingen kunnen een koppeling eraan hebben. U kunt deze syntaxis gebruiken om afbeeldingen in te sluiten

```
![tekst](https://bimsync.com/img/favicon/dark-mode/favicon-32x32.png)
```

om deze afbeelding met het woord tekst erachter te krijgen.

![tekst](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/06-images.png)

Opdat de afbeelding correct wordt weergegeven, moet Catenda toegang hebben tot de gegeven koppeling.

> **Opmerking:** \+ De afbeelding kan aan een beschrijving worden toegevoegd \+ De afbeelding kan met tekst worden gemengd, zodat u zowel voor als na de afbeelding in dezelfde opmerkingen of beschrijving tekst kunt hebben. \+ Afbeeldingen zoals deze kunnen met tabellen en lijsten worden gecombineerd. U kunt bijvoorbeeld een vinkelteken-afbeelding in het midden van een zin/tabel plaatsen in plaats van het opmaak-selectievakje dat alleen aan het begin van een zin werkt \- U kunt niet garanderen dat de koppeling naar de afbeelding in de toekomst beschikbaar blijft.

_Een Catenda-afbeeldingsdocumentkoppeling ophalen_ Als u met de rechtermuisknop op de [downloadactieknop klikt nadat u een document hebt geselecteerd](https://support.catenda.com/en/articles/4670288-actions-in-the-document-structure#h_133e2bcc57) of met de rechtermuisknop op de [downloadactieknop voor de nieuwste revisie klikt nadat u een document hebt geopend](https://support.catenda.com/en/articles/9323521-actions-in-a-document), kunt u de downloadkoppeling van het document kopiëren. Als u deze koppeling in uw topic zoals hierboven gebruikt, kunt u Catenda-documenten in topics gebruiken.

> **Opmerking:** \+ Als u een koppeling naar een Catenda-afbeeldingsdocument toevoegt, kunt u afbeeldingen toevoegen die alleen op Catenda worden weergegeven en niet beschikbaar zijn op andere platforms waarmee het topic kan worden uitgewisseld. \+ Door koppelingen naar een Catenda-afbeeldingsdocument toe te voegen, kunnen alleen personen met toegang tot het document de afbeelding zien. \- Als u een koppeling naar een Catenda-afbeeldingsdocument toevoegt, is het niet zichtbaar op andere platforms waarmee het topic kan zijn gesynchroniseerd en voor personen die geen toegang tot het document hebben.

### 4.2 **Lijsten**

**Ongeordende lijsten** Begin een ongeordende lijst met een lege regel erboven, vervolgens een koppelteken (`-`), plus (`+`), of een asterisk (`\*`) gevolgd door een spatie. Voeg 4 spaties of een tabspatie in aan het begin van de regel om een sublijst te maken.

```
 - Eerste element - Tweede element     - Voeg 4 spaties toe aan het begin van de regel om een sublijst te maken.
```

Of

```
 + Eerste element + Tweede element     + Voeg 4 spaties toe aan het begin van de regel om een sublijst te maken.
```

Of

```
 * Eerste element * Tweede element     * Voeg 4 spaties toe aan het begin van de regel om een sublijst te maken.
```

Dit zal allemaal in dit veranderen:

- Eerste element
- Tweede element
  - Voeg 4 spaties toe aan het begin van de regel om een sublijst te maken.

> **Opmerking:** Opdat een ongeordende lijst correct wordt opgemaakt, moet er een lege nieuwe regel boven de lijst zijn.

**Geordende lijsten** Begin een geordende lijst met een lege regel erboven, een getal, een punt en een spatie (`1. `) Wat het getal ervoor is, doet er niet toe, zolang het maar een getal gevolgd door een punt is. Voeg 4 spaties of een tabspatie in aan het begin van de regel om een sublijst te maken.

```
1. artikel één 2. artikel twee 3. artikel drie     4. artikel vier
```

Of

```
1. artikel één 1. artikel twee 1. artikel drie     1. artikel vier
```

Of

```
1. artikel één 10. artikel twee 1. artikel drie     1000. artikel vier
```

Dit zal allemaal in dit veranderen:

1. artikel één
2. artikel twee
3. artikel drie

4. Artikel vier

> **Opmerking:** Opdat een geordende lijst correct wordt opgemaakt, moet er een lege nieuwe regel boven de lijst zijn.

Het getal waarmee u begint, beïnvloedt niet waar de nummering begint

```
23. drieëntwintig 1. vierentwintig 1. vijfentwintig     1. zesentwintig
```

Zal veranderen in:

1. drieëntwintig
2. vierentwintig
3. vijfentwintig

4. zesentwintig

Als u de nummering opnieuw wilt instellen en opnieuw met één wilt beginnen op een tweede lijst in dezelfde bericht, kunt u een lege regel of een [scheidingslijn](#dividers) ertussen plaatsen.

Om [ervoor te zorgen dat de lijst niet wordt opgemaakt](#preventing-formatting) zodat u uw eigen nummering kunt gebruiken: Plaats een teken op de regel boven de lijst. Een goed keuze is `\\` omdat het verdwijnt.

```
\23. drieëntwintig 24. vierentwintig 25. vijfentwintig     26. zesentwintig
```

Plaats een backslash (`\\`) voor de punt (`.`):

```
23\. drieëntwintig 24\. vierentwintig 25\. vijfentwintig     26\. zesentwintig
```

Dit zal allemaal veranderen in:

23\. drieëntwintig 24\. vierentwintig 25\. vijfentwintig 26\. zesentwintig

### 4.3 **Scheidingslijnen**

Drie streepjes `---` of meer op hun eigen regel creëert een scheidingslijn:

---

### 4.4 **Checklists**

Deze kunnen worden ingevinkt in de beschrijving van een topic. _Vereiste toegang:_ Schrijftoegang tot de topic-bord.

```
- [ ] eerste item - [x] tweede item     - [ ] sublijst item
```

Zal veranderen in:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/07-checklists.png)

Klik [hier](https://support.catenda.com/en/articles/5036461-check-lists-within-issues) om een snelle video te bekijken over hoe checklists in het project kunnen worden gebruikt. Als u `- [ ]` of `- [x]` schrijft, zal het selectievakje nog steeds als leeg of aangevinkt worden weergegeven wanneer de opmerking wordt ingediend of opgeslagen na bewerking.

**Selectievakjes in opmerkingen** In opmerkingen kunnen selectievakjes alleen via opmaak worden ingevinkt. Selectievakjes in opmerkingen kunnen niet worden aangeklikt om te worden ingevinkt. _Vereiste toegang -_ De opmerking maker heeft toegang tot het bewerken van de gemaakte opmerking

### 4.5 **Tabellen**

Tekst in beschrijvingen kan in tabellen worden georganiseerd.

```
|            | Windows            ||             | |            | Type 1   | Type 2   | Som totaal   | |----------- | -------- | -------- | ----------- | | **Prijs**  | 500,-    | 400,-    |             | | **Hoeveelheid** | 10       | 4        |             | | **Som**    | 5 000,-  | 1 600,-  | **6 600,-** |
```

zal dit resulteren

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p></p></td><td><p class="intercom-align-right">Win</p></td><td><p>dows</p></td><td><p></p></td></tr><tr><td><p></p></td><td><p>Type 1</p></td><td><p>Type 2</p></td><td><p>Som totaal</p></td></tr><tr><td><p><b>Prijs</b></p></td><td><p>500,-</p></td><td><p>400,-</p></td><td><p></p></td></tr><tr><td><p><b>Hoeveelheid</b></p></td><td><p>10</p></td><td><p>4</p></td><td><p></p></td></tr><tr><td><p><b>Som</b></p></td><td><p>5 000,-</p></td><td><p>1 600,-</p></td><td><p><b>6 600,-</b></p></td></tr></tbody></table></div>

### 4.6 **Codeblokken**

U kunt als volgt enkele regels code invoegen: Twee \`\\`\` rondom tekst ziet er als volgt uit:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/08-code-blocks.png)

Drie backticks `\`\\`\\`\` boven en onder wat tekst ziet er als volgt uit:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/09-code-blocks.png)

Het is niet mogelijk om tabellen in codeblokken toe te voegen

### 4.7 **Markdown-dialect**

Als u meer wilt weten over hoe tekst in opmerkingen en beschrijvingen wordt opgemaakt, gebruiken we het markdown-dialect "flexmark" om deze tekst op te maken. Meer informatie over flexmark vindt u op hun [github-pagina](https://github.com/vsch/flexmark-java).

## 5. **@ Vermelde leden en teams**

Klik het `@`-gereedschap of schrijf `@` in een beschrijving of opmerking om een lid te vermelden. Na het typen van `@` wordt een vervolgkeuzelijst met leden en teams weergegeven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/10-mentioned-members-and-teams.png)

Blader door de lijst door te beginnen met het typen van het e-mailadres, lidnaam of teamnaam. Ga omhoog en omlaag in de lijst met de pijltoetsen en klik of druk op Enter om een lid of team te selecteren. Opdat een lid of team in deze lijst wordt weergegeven, moet het lid of team minstens leeztoegang tot de topic-bord hebben. Na het selecteren van een lid of team in de lijst krijgt de `@` wat extra tekst die er als volgt uit kan zien:

`@[\<e-mailadres van lid>]` of `@[\<Teamnaam>]`

### 5.1 **Opslaan of indienen van een vermelding in een topic**

Wanneer de beschrijving wordt opgeslagen of de opmerking wordt ingediend, ontvangen gerelateerde leden met toegang tot de topic-bord een melding. Als het lidmaate-mailadres of de naam van het team bekend is, kan het ook handmatig worden geschreven, maar als zij geen onderdeel zijn van de topic-bord, worden de gerelateerde leden niet op de hoogte gesteld dat zij worden vermeld.

**Melding bij lidvermelding** Leden met toegang tot de topic-bord die worden vermeld, ontvangen een melding dat zij in een topic worden vermeld.

**Melding bij teamvermelding** Leden met toegang tot de topic-bord die deel uitmaken van een team dat wordt vermeld, ontvangen een melding dat zij in een topic worden vermeld via een team waar zij deel van uitmaken.

**Meldingen over toekomstige topic-evenementen** Leden van teams die in topic-beschrijvingen en opmerkingen worden vermeld, ontvangen slechts de ene melding op de opgeslagen beschrijving of ingediende opmerking.

Naast de melding dat zij worden vermeld, worden leden die in berichten worden vermeld, automatisch ingesteld op [volgen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) van het topic en ontvangen zij meldingen over topic-evenementen zoals nieuwe opmerkingen en statuswijzigingen. Dit is een geweldige manier om ervoor te zorgen dat niet alleen de [gemachtigde](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9) en [aanvrager](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7) meldingen krijgen over toekomstige wijzigingen in een topic. Als een lid niet langer het topic wil volgen, moet hij het handmatig niet volgen.

### 5.2 **Vermelding in bericht**

Vermeldingen in berichten kunnen worden geïdentificeerd door een groene tekstkleur te hebben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/11-mention-in-post.png)

Op de achtergrond wordt de unieke id van de vermelde projectdeelnemer opgeslagen. Het is de naam van de deelnemer die in deze groene tekst wordt weergegeven. Zelfs als het lid of team van naam verandert, blijft het in het bericht worden vermeld, maar onder de nieuwe naam.

Vermelde leden hebben een klikbare koppeling die naar de [ledenpagina](https://support.catenda.com/en/articles/8228836-member-page) van dat lid verwijst. Vermelde teams hebben een klikbare koppeling die naar de [teampagina](https://support.catenda.com/en/articles/7891755-team-page) van dat team verwijst.

**Niet-bestaand lid** Als er in het project geen lid is met het vermelde e-mailadres, ziet het bericht er als volgt uit:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/12-mention-in-post.png)

Dit kan zijn omdat het e-mailadres verkeerd werd opgemaakt of omdat het lid niet langer deel uitmaakt van het project. Zou een lid met dit e-mailadres in de toekomst deel van het project worden, dan verandert het bericht zodat de naam van dat lid wordt weergegeven.

**Niet-bestaand team** Als een team uit het project is verwijderd en een nieuw team is gemaakt, wordt dit nieuwe team niet vermeld. Om het nieuwe team te vermelden, moet het bericht opnieuw worden ingediend.

## 6. **# Getagde topics**

Klik het `#`-gereedschap of schrijf `#` in een beschrijving of opmerking om een topic te taggen. Na het typen van `#` wordt een vervolgkeuzelijst met topics van alle topic-borden weergegeven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/13-tagged-topics.png)

Blader door de lijst door te beginnen met het typen van de titel of topic-nummer. Ga omhoog en omlaag in de lijst met de pijltoetsen en klik of druk op Enter om een topic te selecteren. Opdat een topic in deze lijst verschijnt, moet het lid dat het topic tagt, toegang hebben tot de bord waarin het topic zich bevindt. Na het selecteren van een topic in de lijst krijgt de `#` wat extra tekst die er als volgt uit kan zien:

`#[\<topic-nummer>]`

### 6.1 **Opslaan of indienen van een getagd topic**

Wanneer de beschrijving wordt opgeslagen of de opmerking wordt ingediend, wordt een topic-relatie gemaakt. Het gekoppelde topic wordt vervolgens toegevoegd aan de lijst met [gekoppelde topics](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) in [het rechtermenu](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) van het topic.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/14-saving-or-submitting-a-tagged-topic.png)

Naast het topic waarin een ander topic werd getagd, ontvangt het getagde topic zelf een koppeling terug naar het topic waar het werd toegevoegd aan de lijst met [gekoppelde topics](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) in [het rechtermenu](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/15-saving-or-submitting-a-tagged-topic.png)

De topic-koppeling kan later worden verwijderd uit het topic met het getagde topic in de beschrijving of uit het topic dat werd getagd door naar elk topic te gaan en de lijst met [gekoppelde topics](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) in [het rechtermenu](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) te bewerken.

### 6.2 **Getagd topic in bericht**

Getagde topics kunnen worden geïdentificeerd door eerst een cirkel met de kleur van de huidige status van het getagde topic samen met de naam van die status. Daarna wordt de topictitel gevolgd door het topic-nummer weergegeven.

Samen met de selectievakjes tellen getagde topics die gesloten zijn mee naar de voortgang in de voortgangsbalk die naar de bovenkant wordt weergegeven, terwijl getagde topics die open zijn, meetellen naar het totale aantal items waar de voortgang naar wordt geteld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/16-tagged-topic-in-post.png)

Getagde topics hebben een klikbare koppeling die het getagde topic in zijn topic-bord opent.
