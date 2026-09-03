# Werkbalk voor berichtopmaak

> Hoe velden waar berichten kunnen worden geplaatst, kunnen worden opgemaakt

Dezelfde opmaakregels gelden voor de verschillende berichten in Catenda Hub. Berichten kunnen topicbeschrijvingen, opmerkingen, goedkeuringsbeschrijvingen en goedkeuringsopmerkingen bevatten. Variaties kunnen voorkomen bij de verschillende toegangsrechten voor wie het bericht kan bewerken. Catenda gebruikt markdown om tekst op te maken. Dit betekent dat bepaalde tekens voor en na zinnen van invloed zijn op de opmaak van de tekst. Dit is hoe een topickop en beschrijving er na indiening uit kunnen zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/01-intro.png)

## 1. Beschikbaarheid van opmaak

Het is vaak mogelijk om te zien dat verzonden velden kunnen worden opgemaakt aan de hand van de werkbalk die onder het veld verschijnt wanneer het veld wordt bewerkt.

> **Opmerking:** Zoom ver genoeg uit met de browserzoombalk om alle gereedschappen te zien.

Opmaak is beschikbaar in de volgende velden:

### 1.1 **Topicbeschrijving en opmerking**

Bewerk de beschrijving of opmerking van een bestaand topic of bij het indienen van een nieuw topic om de werkbalk te zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/02-topic-description-and-comment.png)

### 1.2 **Beschrijving goedkeuringsverzoeking**

Hoewel de werkbalk niet verschijnt in de beschrijving van het dialoogvenster voor een nieuwe goedkeuringsverzoeking, wordt opmaak wel op deze beschrijving toegepast.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/03-approval-request-description.png)

> **Opmerking:** Dit veld kan niet worden bewerkt nadat de goedkeuringsverzoeking is ingediend.

### 1.3 Beschrijving topicbord

Hoewel de werkbalk in de nieuwe topicbordbeschrijving verschijnt, is het belangrijk op te merken dat de beschrijving niet wordt opgemaakt wanneer het bord wordt ingediend.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/04-topic-board-description.png)

## 2. **Bijlage topic-opmerking**

In topicopmerkingen is een bijlagegereedschap zichtbaar. Klik op de + knop in een topic om een bijlage toe te voegen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/05-topic-comment-attachment.png)

Klik [hier](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_0e3c0059ae) voor meer informatie over bijlagen in opmerkingen.

## 3. **Tekst opmaken**

De volgende methoden stellen u in staat uw tekst op te maken:

### 3.1 **Vet, cursief, doorgehaald**

Vet, cursief en doorgehaalde opmaak kunnen op elk punt van een regel worden toegepast en werken goed samen met andere opmaak die aan het begin van een regel moet staan.

<img alt="**Dit zal vet zijn** __Dit zal ook vet zijn__ *Dit zal cursief zijn* _Dit zal ook cursief zijn_ **Dit zal vet zijn _gecombineerd met cursief_** ~~Deze tekst zal doorgestreept zijn~~" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-b49c2f10b2de.png" width="290"/>   \<->   <img alt="Dit zal vet zijn​Dit zal ook vet zijn​Dit zal cursief zijn​Dit zal ook cursief zijn​Dit zal vet zijn gecombineerd met cursief​Deze tekst zal doorgestreept zijn" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-ea38fb93f8ee.png" width="290"/>

### 3.2 **Koppen**

De koppelingtool voegt hashtags/hekjes toe aan het begin van de regel. Er worden 5 kopniveaus ondersteund: De opmaak die de kop krijgt, is afhankelijk van het aantal hashtags/hekjes (`#`) aan het begin van de regel.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-c21079ec7efb.png" width="290"/>   \<->   <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-557784a5d702.png" width="290"/>

### 3.3 **Koppelingen**

Koppelingopmaak kan op elk punt van een regel worden toegepast en werkt goed samen met andere opmaak die aan het begin van een regel moet staan. Koppelingen in beschrijvingen zijn groen en onderstreept. Hun tekst kan anders zijn dan de URL waar de koppeling naar verwijst. URL's worden automatisch omgezet in aanklikbare koppelingen

```
https://hub.catenda.com
```

wordt [https://hub.catenda.com](https://hub.catenda.com) en

```
[Catenda Hub](https://hub.catenda.com)
```

wordt: [Catenda Hub](https://hub.catenda.com)

> **Opmerking:** Wees voorzichtig bij het klikken op koppelingen, want hoewel de tekst [uit de vierkante haken] één koppeling kan weergeven, kan de werkelijke koppeling (uit de haakjes) anders zijn. Het wordt aanbevolen om over een koppeling te zweven en te kijken waarheen de browser wordt omgeleid voordat u op een koppeling klikt.

### 3.4 **Opmaak voorkomen**

Door woorden met niet-letter- of nummertekens in te pakken, kunt u ze er anders laten uitzien. Dit is niet altijd gewenst. Als u een `\` voor zo'n teken plaatst, verdwijnt de `\`. Elke opmaak die voor deze tekens zou zijn toegepast, werkt dan niet meer. Als u een `\` op een lege regel plaatst die geen deel uitmaakt van een [lijst](#h_6da4949f8c), is het resultaat nog steeds een lege regel.

## 4. **Tekst opsplitsen en structuur toevoegen**

Met de volgende methoden kunt u uw tekst verbeteren door deze op te splitsen en structuur toe te voegen:

### 4.1 **Afbeeldingen**

Afbeeldingen in beschrijvingen kunnen een koppeling aan zich hebben. Om afbeeldingen in te voegen, kunt u deze syntaxis gebruiken

```
![text](https://bimsync.com/img/favicon/dark-mode/favicon-32x32.png)
```

om deze afbeelding met het woord tekst erachter te krijgen.

![text](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/06-images.png)

Om ervoor te zorgen dat de afbeelding correct wordt weergegeven, moet Catenda toegang hebben tot de verstrekte koppeling.

> **Opmerking:** \+ De afbeelding kan aan een beschrijving worden toegevoegd \+ De afbeelding kan met tekst worden gemengd zodat u tekst zowel voor als na de afbeelding in dezelfde opmerkingen of beschrijving kunt hebben. \+ Afbeeldingen kunnen met tabellen en lijsten worden gecombineerd. U kunt bijvoorbeeld een vinkje in het midden van een zin/tabel toevoegen in plaats van het opmaakkeuzevakje, dat alleen aan het begin van een zin werkt \- U kunt niet garanderen dat de koppeling naar de afbeelding in de toekomst beschikbaar blijft.

_Een Catenda-afbeeldingsdocumentkoppeling ophalen_ Als u met de rechtermuisknop op de [downloadactieknop klikt nadat u een document hebt geselecteerd](https://support.catenda.com/en/articles/4670288-actions-in-the-document-structure#h_133e2bcc57) of met de rechtermuisknop op de [downloadactie voor de nieuwste versie klikt nadat u een document hebt geopend](https://support.catenda.com/en/articles/9323521-actions-in-a-document), kunt u de downloadkoppeling van het document kopiëren. Als u deze koppeling in uw topic gebruikt zoals hierboven, kunt u Catenda-documenten in topics gebruiken.

> **Opmerking:** \+ Als u een koppeling naar een Catenda-afbeeldingsdocument toevoegt, kunt u afbeeldingen toevoegen die alleen in Catenda worden weergegeven en niet beschikbaar zijn op andere platforms waar het topic mee kan worden uitgewisseld. \+ Door koppelingen naar een Catenda-afbeeldingsdocument toe te voegen, zien alleen mensen met toegang tot het document de afbeelding. \- Als u een koppeling naar een Catenda-afbeeldingsdocument toevoegt, is het niet zichtbaar op andere platforms waarmee het topic is gesynchroniseerd en voor mensen die geen toegang tot het document hebben.

### 4.2 **Lijsten**

**Ongeordende lijsten** Start een ongeordende lijst met een lege regel erboven, gevolgd door een koppelteken (`-`), plus (`+`), of een asterisk (`*`) gevolgd door een spatie. Voeg 4 spaties of een tabteken aan het begin van de regel in om een sublijst te maken.

```
 - Eerste element - Tweede element     - Voeg 4 spaties aan het begin van de regel in om een sublijst te maken.
```

Of

```
 + Eerste element + Tweede element     + Voeg 4 spaties aan het begin van de regel in om een sublijst te maken.
```

Of

```
 * Eerste element * Tweede element     * Voeg 4 spaties aan het begin van de regel in om een sublijst te maken.
```

Dit zal allemaal zo worden:

- Eerste element
- Tweede element
  - Voeg 4 spaties aan het begin van de regel in om een sublijst te maken.

> **Opmerking:** Om ervoor te zorgen dat een ongeordende lijst correct wordt opgemaakt, moet er een lege nieuwe regel boven de lijst staan.

**Geordende lijsten** Start een geordende lijst met een lege regel erboven, een getal, een punt en een spatie (`1. `) Het getal ervoor maakt niet uit, alleen dat het een getal is gevolgd door een punt. Voeg 4 spaties of een tabteken aan het begin van de regel in om een sublijst te maken.

```
1. item één 2. item twee 3. item drie     4. item vier
```

Of

```
1. item één 1. item twee 1. item drie     1. item vier
```

Of

```
1. item één 10. item twee 1. item drie     1000. item vier
```

Dit zal allemaal zo worden:

1. item één
1. item twee
1. item drie

1. Item vier

> **Opmerking:** Om ervoor te zorgen dat een geordende lijst correct wordt opgemaakt, moet er een lege nieuwe regel boven de lijst staan.

Het getal waarmee u begint, heeft geen invloed op waar de nummering begint

```
23. drieëntwintig 1. vierentwintig 1. vijfentwintig     1. zesentwintig
```

Dit zal zo worden:

1. drieëntwintig
1. vierentwintig
1. vijfentwintig

1. zesentwintig

Als u de nummering opnieuw wilt instellen en opnieuw met één wilt beginnen op een tweede lijst in hetzelfde bericht, kunt u een blanco of een [scheidingslijn](#h_3a36cfbc61) ertussenin plaatsen.

Ga naar [zorg ervoor dat de lijst niet wordt opgemaakt](#h_2ec17c688b) zodat u uw eigen nummering kunt gebruiken: Plaats een teken op de regel boven de lijst. Een goed keuze is `\` omdat dit zal verdwijnen.

```
\23. drieëntwintig 24. vierentwintig 25. vijfentwintig     26. zesentwintig
```

Plaats een backslash (`\`) voor de punt (`.`):

```
23\. drieëntwintig 24\. vierentwintig 25\. vijfentwintig     26\. zesentwintig
```

Dit zal allemaal zo worden:

23\. drieëntwintig 24\. vierentwintig 25\. vijfentwintig 26\. zesentwintig

### 4.3 **Scheidingslijnen**

Drie streepjes `---` of meer op hun eigen regel creëren een scheidingslijn:

---

### 4.4 **Controlelijsten**

Deze kunnen worden ingevinkt in de beschrijving van een topic. _Toegang vereist:_ Schrijftoegang tot het topicbord.

```
- [ ] eerste item - [x] tweede item     - [ ] sublijst item
```

Dit zal zo worden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/07-checklists.png)

Klik [hier](https://support.catenda.com/en/articles/5036461-check-lists-within-issues) om een korte video te bekijken over hoe controlelijsten in het project kunnen worden gebruikt. Als u schrijft ` - [ ]` of `- [x]` zal het vakje nog steeds ongevinkt en gevinkt verschijnen wanneer de opmerking wordt ingediend of opgeslagen nadat deze is bewerkt.

**Keuzevakjes in opmerkingen** In opmerkingen kunnen keuzevakjes alleen via opmaak worden ingevinkt. Keuzevakjes in opmerkingen kunnen niet worden aangeklikt om deze in te vinken. _Toegang vereist -_ De opmerking creator heeft toegang tot het bewerken van de gemaakte opmerking

### 4.5 **Tabellen**

Tekst in beschrijvingen kan in tabellen worden geordend.

```
|            | Windows            ||             | |            | Type 1   | Type 2   | Sum total   | |----------- | -------- | -------- | ----------- | | **Price**  | 500,-    | 400,-    |             | | **Amount** | 10       | 4        |             | | **Sum**    | 5 000,-  | 1 600,-  | **6 600,-** |
```

zal dit resulteren in

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right">Win</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>dows</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Type 1</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Type 2</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Totaal som</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Prijs</b></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>500,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>400,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Aantal</b></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>10</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>4</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Som</b></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>5 000,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>1 600,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>6 600,-</b></p></td></tr></tbody></table></div>

### 4.6 **Codeblokken**

U kunt als volgt één regel code invoegen: Twee `` ` `` rond tekst ziet er als volgt uit:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/08-code-blocks.png)

Drie backticks ` ``` ` boven en onder wat tekst ziet er als volgt uit:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/09-code-blocks.png)

Het is niet mogelijk om tabellen in codeblokken toe te voegen

### 4.7 **Markdown-dialect**

Als u meer wilt weten over hoe tekst in opmerkingen en beschrijvingen wordt opgemaakt, gebruiken we het markdown-dialect "flexmark" om deze tekst op te maken. Meer informatie over flexmark vindt u op hun [github-pagina](https://github.com/vsch/flexmark-java).

## 5. **@ Vermelde leden en teams**

Klik op het `@`-gereedschap of schrijf `@` in een beschrijving of opmerking om een lid te vermelden. Na het typen van `@` wordt een vervolgkeuzelijst met leden en teams weergegeven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/10-mentioned-members-and-teams.png)

Zoek in de lijst door met het e-mailadres, lidnaam of teamnaam in te typen. Ga met de pijltoetsen omhoog en omlaag in de lijst en klik of druk op Enter om een lid of team te selecteren. Om een lid of team in deze lijst te laten verschijnen, moet het lid of team minstens leestoegang tot het topicbord hebben. Nadat u een lid of team in de lijst hebt geselecteerd, krijgt de `@` wat extra tekst die er zo uit kan zien:

`@[<e-mailadres van lid>]` of `@[<teamnaam>]`

### 5.1 **Opslaan of indienen van een vermelding in een topic**

Wanneer de beschrijving wordt opgeslagen of de opmerking wordt ingediend, ontvangen gerelateerde leden met toegang tot het topicbord een melding. Als het e-mailadres van het lid of de naam van het team bekend is, kan het ook handmatig worden geschreven, maar als zij niet onderdeel zijn van het topicbord, worden gerelateerde leden niet op de hoogte gesteld dat zij zijn vermeld.

**Melding bij vermelding van lid** Leden met toegang tot het topicbord die zijn vermeld, ontvangen een melding dat zij in een topic zijn vermeld.

**Melding bij vermelding van team** Leden met toegang tot het topicbord die deel uitmaken van een team dat is vermeld, ontvangen een melding dat een team waarvan zij deel uitmaken, in een topic is vermeld.

**Meldingen over toekomstige topic-gebeurtenissen** Leden van teams die in topicbeschrijvingen en opmerkingen zijn vermeld, ontvangen slechts één melding wanneer de beschrijving wordt opgeslagen of de opmerking wordt ingediend.

Naast de melding dat zij zijn vermeld, worden leden die in berichten zijn vermeld, automatisch ingesteld op [volgen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) van het topic en ontvangen meldingen over topic-gebeurtenissen zoals nieuwe opmerkingen en statuswijzigingen. Dit is een geweldige manier om ervoor te zorgen dat meer dan alleen de [toewijzingsgerechtigde](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9) en [aanvrager](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7) meldingen ontvangen over toekomstige wijzigingen in een topic. Als een lid niet langer het topic wil volgen, moet het dit handmatig opvolgen.

### 5.2 **Vermelding in bericht**

Vermeldingen in berichten kunnen worden geïdentificeerd aan de groene tekstkleur.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/11-mention-in-post.png)

Op de achtergrond wordt de unieke id van de vermelde projectdeelnemer opgeslagen. Het is de naam van de deelnemer die in deze groene tekst wordt weergegeven. Zelfs als het lid of team van naam verandert, blijven zij in het bericht vermeld, maar onder hun nieuwe naam.

Vermelde leden hebben een aanklikbare koppeling die naar de [ledenpagina](https://support.catenda.com/en/articles/8228836-member-page) van dat lid verwijst. Vermelde teams hebben een aanklikbare koppeling die naar de [teampagina](https://support.catenda.com/en/articles/7891755-team-page) van dat team verwijst.

**Niet-bestaand lid** Als er geen lid in het project is dat het e-mailadres heeft dat is vermeld, ziet het bericht er als volgt uit:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/12-mention-in-post.png)

Dit kan zijn omdat het e-mailadres onjuist is opgemaakt of omdat het lid niet langer onderdeel is van het project. Als een lid met dit e-mailadres in de toekomst onderdeel van het project wordt, verandert het bericht zodat de naam van dat lid wordt weergegeven.

**Niet-bestaand team** Als een team uit het project is verwijderd en een nieuw team wordt gemaakt, wordt dit nieuwe team niet vermeld. Om het nieuwe team te vermelden, moet het bericht opnieuw worden ingediend.

## 6. **# Getagde topics**

Klik op het `#`-gereedschap of schrijf `#` in een beschrijving of opmerking om een topic te taggen. Na het typen van `#` wordt een vervolgkeuzelijst met topics van alle topicborden weergegeven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/13-tagged-topics.png)

Zoek in de lijst door met de titel of topicnummer in te typen. Ga met de pijltoetsen omhoog en omlaag in de lijst en klik of druk op Enter om een topic te selecteren. Om een topic in deze lijst te laten verschijnen, moet het lid dat het topic tagged, toegang hebben tot het bord waarin het topic zich bevindt. Nadat u een topic in de lijst hebt geselecteerd, krijgt de `#` wat extra tekst die er zo uit kan zien:

`#[<topic nummer>]`

### 6.1 **Opslaan of indienen van een getagd topic**

Wanneer de beschrijving wordt opgeslagen of de opmerking wordt ingediend, wordt een topicrelatie gemaakt. Het gekoppelde topic wordt vervolgens toegevoegd aan de lijst met [gekoppelde topics](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) in [het rechtermenu](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) van het topic.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/14-saving-or-submitting-a-tagged-topic.png)

Naast het topic waarin een ander topic is getagd, ontvangt het getagde topic zelf een koppeling terug naar het topic waar het is toegevoegd aan de lijst met [gekoppelde topics](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) in [het rechtermenu](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/15-saving-or-submitting-a-tagged-topic.png)

De topickoppeling kan later worden verwijderd van het topic met het getagde topic in de beschrijving of van het topic dat is getagd door naar elk topic te gaan en de lijst met [gekoppelde topics](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) in [het rechtermenu](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) te bewerken.

### 6.2 **Getagd topic in bericht**

Getagde topics kunnen worden geïdentificeerd door eerst een cirkel met de kleur van de huidige status van het getagde topic samen met de naam van die status te hebben. Daarna wordt de topictitel weergegeven, gevolgd door het topicnummer.

Samen met de keuzevakjes tellen getagde topics die zijn gesloten mee naar de voortgang in de voortgangsbalk die boven wordt weergegeven, terwijl getagde topics die open zijn, meegerekend worden in het totaal aantal items waarnaar de voortgang wordt geteld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/16-tagged-topic-in-post.png)

Getagde topics hebben een aanklikbare koppeling die het getagde topic in het topicbord ervan opent.
