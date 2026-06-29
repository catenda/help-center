# Opmaak van berichten

Dezelfde opmaakregels gelden voor verschillende berichten m.b.t. Catenda Hub.

Berichten kunnen topic omschrijvingen, commentaren en beoordelingen zijn.

Wie het bericht kan bewerken is afhankelijk van de autorisatie.

Catenda gebruikt markdown om tekst op te maken.

Dit betekent dat bepaalde tekens voor en na de regels de stijl van de tekst beïnvloeden.

> **Note:** **Merk:** Vele methodes vergen een lege lijn ervoor om de stijl toe te passen.

De volgende thema's zullen beschreven worden in dit artikel:

## 1. **Het toepassen van stijl aan tekst**

Met de volgende opties heeft u diverse tekst stijlen:

### 1.1 **Vette, cursieve en doorgestreepte tekst**

```
**Dit zal vette tekst worden** __Dit zal ook vette tekst worden__ *Dit zal cursief worden* _Dit zal ook cursief worden_ **Dit zal vette tekst _gecombineerd met cursief_ worden**~~Deze tekst zal doorgestreept worden~~
```

**Dit zal vette tekst worden** **Dit zal ook vette tekst worden** _Dit zal cursief worden_ _Dit zal ook cursief worden_ **Dit zal vette tekst _gecombineerd met cursief_ worden** Deze tekst zal doorgestreept worden

### 1.2 **Kop tekst**

`##` aan het begin van tekst zal een kop tekst gemaakt worden

### 1.3 **Links**

Links in berichten zullen groen en onderstreept zijn.

De tekst kan verschillen van de url waar de link naar verwijst.

Urls zullen automatisch tot klikbare links veranderd worden.

```
https://hub.catenda.com
```

Zal het volgende worden:

[https://hub.catenda.com](https://hub.catenda.com)

En

```
[Catenda Hub](https://hub.catenda.com)
```

Zal het volgende worden:

[Catenda Hub](https://hub.catenda.com)

### 1.4 **Opmaak voorkomen**

Door woorden te plaatsen in niet-letter- of cijfertekens kun je ze er anders uit laten zien.

Dit is niet altijd gewenst.

Als je een י voor zo'n teken zet, verdwijnt de י.

De opmaak die voor deze tekens zou zijn toegepast, werkt dan niet meer.

Als je een ▶ op een lege regel zet die geen deel uitmaakt van een lijst, zal het resultaat ook een lege regel zijn.

## 2. **Tekst opsplitsen en structuur toevoegen**

Met de volgende methoden kun je je tekst verbeteren door hem op te splitsen en structuur toe te voegen:

### 2.1 **Foto's**

Foto's in berichten kunnen een gekoppelde link hebben.

Volg deze syntax om foto's in berichten in te sluiten.

```
![text](https://bimsync.com/img/favicon/dark-mode/favicon-32x32.png)
```

Om de volgende foto met het woord tekst er achter te krijgen.

![text](https://downloads.intercomcdn.com/i/o/areracg3/1211345724/faf70b08f3819dbb120fe1de4cb9/faviconV2.png?expires=1781092800&signature=548832312799b4ee2fb4f38df3219c970246643cb2f2c64dfdd6fdf425893a0f&req=dSImF8p6mIZdXfMW3nq%2BgY6nTsiIpE1wj0Itr3wpRi2Ru5%2BxSQb%2FMMbJONWB%0Af9S2DQSTCHJdsYiI8601Ah1rJe8%3D%0A)

Om een foto op de juiste manier tevoorschijn te laten komen moet Catenda toegang hebben tot de ingevoerde link.

> **Note:** \+ De foto kan tot de omschrijving toegevoegd worden \+ De foto kan worden gemengd met tekst, zodat je tekst zowel voor als na de foto kunt hebben in dezelfde opmerking of beschrijving. \+ Foto's als deze kunnen gecombineerd worden met tabellen en lijsten. Bijvoorbeeld kunt u een checkmark foto in het midden van een zin/tabel toevoegen in plaats van een opmaak selectievakje die alleen aan het begin van een zin werkt. \- Het kan niet gegarandeerd worden dat de link naar de foto in de toekomst toegankelijk blijft.

_Een Catenda foto documentenlink verkrijgen_ Als u met de rechtermuisknop op [de download actieknop na een document geselecteerd te hebben](https://support.catenda.com/en/articles/4670288-actions-in-the-document-structure#h_133e2bcc57) klikt of met de rechtermuisknop op [de download laatste revisie actieknop klikt na een document geopend te hebben](https://support.catenda.com/en/articles/9323521-actions-in-a-document) zal u de download link van het document kunnen kopiëren. Als u deze link in uw topic gebruikt als hier boven, zal Catenda documenten in topics kunnen gebruiken.

> **Note:** \+ Als u een link tot een Catenda foto document toevoegt zal u fotos zien die alleen op Catenda, en niet op andere platforms waar de topic mee uitgewisseld wordt, zichtbaar zijn \+ Door links tot een Catenda foto document toe te voegen zullen alleen leden met toegang tot het document de foto zien. \- Als u een link tot een Catenda foto document toevoegt zal deze niet zichtbaar zijn in andere platforms waar de topic mee gesynchroniseerd kan zijn en met andere leden die geen toegang tot het document hebben.

### 2.2 **Lijsten**

**Niet-gerangschikte lijsten**

Start een niet-gerangschikte lijst met een lege lijn erboven en daarna een koppelteken (`-`), plus (`+`), of een sterretje (`\*`) gevolgd door een spatie.

Voeg 4 spaties of een tab spatie in aan het begin van de lijn om een sublijst aan te maken.

```
- Eerste element- Tweede element     - Voeg 4 spaties aan het begin van de lijn toe en maak een sublijst.
```

Of

```
+ Eerste element+ Tweede element     + Voeg 4 spaties aan het begin van de lijn toe en maak een sublijst.
```

Of

```
* Eerste element* Tweede element     * Voeg 4 spaties aan het begin van de lijn toe en maak een sublijst.
```

Zal allemaal in dit veranderen:

- Eerste element
- Tweede element
    - Voeg 4 spaties aan het begin van de lijn toe en maak een sublijst.

**Gerangschikte lijst**

Start een gerangschikte lijst met een lege lijn er boven, een nummer, een punt en een spatie (`1. `)

Het maakt niet uit wat het nummer aan het begin van de lijn is. Alleen dat het een nummer is dat door een punt gevolgd wordt. Voeg 4 spaties of een tab spatie toe an het begin van de lijn om een sublijst te maken.

```
1. Punt één2. Punt twee3. Punt drie     4. Punt vier
```

Or

```
1. Punt één1. Punt twee1. item three     1. Punt vier
```

Or

```
1. Punt één10. Punt twee1. item three     1000. Punt vier
```

Zal allemaal hierin veranderen:

1. Punt één
1. Punt twee
1. Punt drie

    4. Punt vier

Het nummer waar u mee begint heeft geen invloed op waar de nummering begint.

```
23. Drie-en-twintig1. Vier-en-twintig1. Vijf-en-twintig    1. Zes-en-twintig
```

Zal hierin veranderen:

1. Drie-en-twintig
1. Vier-en-twintig
1. Vijf-en-twintig

    4. Zes-en-twintig

Als u wenst om het nummeren te resetten en weer vanaf één in een tweede lijst binnen hetzelfde bericht te beginnen kunt u een lege lijn of een [scheiding](#h_37339488ba) er tussen zetten.

Als u wilt [verzekeren dat de lijn niet opgemaakt wordt](#h_001385e47a) dan kan u uw eigen nummering maken: Zet een teken op de lijn boven de lijst. Een goede keuze is `\\` omdat deze zal verdwijnen

```
\23. Drie-en-twintig24. Vier-en-twintig25. Vijf-en-twintig    26. Zes-en-twintig
```

Zet een achterwaardse schuine streep (`\\`) voor de punt (`.`):

```
23\. Drie-en-twintig24\. Vier-en-twintig25\. Vijf-en-twintig    26\. Zes-en-twintig
```

Zal allemaal hierin veranderen:

23. Drie-en-twintig

24. Vier-en-twintig

25. Vijf-en-twintig

26. Zes-en-twintig

### 2.3 **Scheidingen**

Drie of meer koppeltekens `---` op hun eigen lijn zal een scheiding aanmaken:

---

### 2.4 **Checklijsten**

Deze kunnen gecheckt worden in de omschrijving van een topic.

_Toegang vereist:_ Schrijf toegang tot het topic board.

```
- [ ] Eerste punt- [x] Tweede punt     - [ ] Sublijst punt
```

Zal hierin veranderen:

![](https://downloads.intercomcdn.com/i/o/areracg3/1211345723/7a1585bccd8fa66e052333b606b3/image.png?expires=1781092800&signature=721222657a0c4c0d8536b51faf76c1aa77e36a95a9fbba3b1d110b47890c6f87&req=dSImF8p6mIZdWvMW3nq%2BgQykGtCVso3G%2FJ3a9oafC8JfDimpvcqSTY3Lv68B%0A8wzPIOzOY36CTQVS7JehWPDZsEU%3D%0A)

Klik [hier](https://support.catenda.com/en/articles/5036461-check-lists-within-issues) om een korte video te kijken over hoe checklijsten in een project gebruikt kunnen worden. Als u `- [ ]` of `- [x]` schrijft zal de box er nog steeds wel of niet gevinkt uitzien wanneer het commentaar ingediend wordt of opgeslagen wordt na bewerkt te zijn.

**Selectievakjes in commentaren**

In commentaren kunnen selectievakjes alleen gevinkt worden door opmaak.

Selctievakjes in commentaren kunnen niet geklikt worden om gevinkt te worden. _Toegang vereist -_ De aanmaker van het commentaar heeft toegang om het commentaar te bewerken.

### 2.5 **Tabellen**

Tekst in berichten kan in tabellen opgemaakt worden.

```
|            | Ramen              ||             | |            | Type 1   | Type 2   | Totaalbedrag| |----------- | -------- | -------- | ----------- | | **Prijs**  | 500,-    | 400,-    |             | | **Aantal** | 10       | 4        |             | | **Bedrag** | 5 000,-  | 1 600,-  | **6 600,-** |
```

Zal hierin veranderen:

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p class="no-margin"></p>
</td><td><p class="no-margin"></p>
</td><td><p class="no-margin">Ramen</p></td><td><p class="no-margin"></p>
</td></tr><tr><td><p class="no-margin"></p>
</td><td><p class="no-margin">Type 1</p></td><td><p class="no-margin">Type 2</p></td><td><p class="no-margin">Totaalbedrag</p></td></tr><tr><td><p class="no-margin"><b>Prijs</b></p></td><td><p class="no-margin">500,-</p></td><td><p class="no-margin">400,-</p></td><td><p class="no-margin"></p>
</td></tr><tr><td><p class="no-margin"><b>Aantal</b></p></td><td><p class="no-margin">10</p></td><td><p class="no-margin">4</p></td><td><p class="no-margin"></p>
</td></tr><tr><td><p class="no-margin"><b>Bedrag</b></p></td><td><p class="no-margin">5 000,-</p></td><td><p class="no-margin">1 600,-</p></td><td><p class="no-margin"><b>6 600,-</b></p></td></tr></tbody></table></div>

### 2.6 **Code stukken**

U kunt enkele lijnen met code op deze manier indienen:

Twee backtick-tekens `\`` rondtom tekst zal er zo uit zien:

![](https://downloads.intercomcdn.com/i/o/areracg3/1211345725/26a36da68a911a6aecdcdc21ca46/image.png?expires=1781092800&signature=74952851a37195d710ec4e507e77b15724167755801d24a9c2853e8faff3577b&req=dSImF8p6mIZdXPMW3nq%2BgYtB72jqcm9AqMmXlQw%2BqstgRp%2FPe4%2FdOjB8M20w%0AiwiJAzU4%2FbcRZiAiw%2BKcbhMVfoM%3D%0A)

Drie backtick-tekens `\`\`\`` boven en onder een stuk tekst zal er zo uit zien:

![](https://downloads.intercomcdn.com/i/o/areracg3/1211345727/e5d3c5f6c700ab4b1bcb6e7c113f/image.png?expires=1781092800&signature=b511a5eb28ef42a80b59872c21ed8fdc370d18b3dbebf67ca7e67550fc06127a&req=dSImF8p6mIZdXvMW3nq%2BgWfkW2HJaVA0dJ%2BCPAIuyxvgTuiQBcgoph5E3jVq%0A6nODZuPinphTMCcaH13%2Bpd9PyQc%3D%0A)

Het is niet mogelijk om tabellen in code stukken toe te voegen

### 2.7 **Markdown dialect**

Als u zou willen weten hoe de tekst in commentaren en omschrijvingen opgemaakt wordt gebruiken wij het markdown dialect "flexmark" om de tekst op te maken. Vind meer uit over flexmark op hun [github pagina](https://github.com/vsch/flexmark-java).

## 3. **@ Leden en teams vernoemen**

U kunt een gebruiker vernoemen door `@` te typen en de account naam van de gebruiker die u wilt vernoemen te typen.

Door op een vernoemde gebruiker of team te klikken zal u naar te [ledenpagina](https://support.catenda.com/en/articles/8228836-member-page) van die gebruiker of [team pagina](https://support.catenda.com/en/articles/7891755-team-page) van dat team genomen worden.

Gebruikers en teams die vernoemd zijn in berichten van een topic zullen het topic automatisch [volgen](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) en zullen daarmee notificaties over toekomstelijke veranderingen in het topic krijgen.

Dit is een goede manier om te verzekeren dat meer dan aleen de toegewezen en aangevraagde in het topic notificaties over toekomstelijke veranderingen uit een topic krijgen.

## 4. **# Getagde topics**

U kunt topics taggen door `#` te typen en het nummer van het topic te schrijven.

Na enter gedrukt te hebben zullen getagde topics er uit zien als `#[123]` in de bewerkte tekst. U kunt dit ook met de hand schrijven op deze manier.

Na een bericht verzonden te hebben zal de tekst van de link dynamisch de kleur, status, titel en topic nummer van de topic samen met een klikbare link van deze topic bevatten.

Wanneer u een topic tagt zal die topic tot de [gerelateerde topics](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) in het [rechter zij menu](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) toegevoegd worden.

Topics kunnen met de hand verwijderd worden uit [gerelateerde topics](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8).
