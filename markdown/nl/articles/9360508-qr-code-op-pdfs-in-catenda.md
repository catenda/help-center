# QR-Code op PDF's in Catenda

QR-Codes kunnen per map worden geconfigureerd in de [mapconfiguratie](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) van [Documenten-instellingen](https://support.catenda.com/en/articles/7831371-document-settings).

Deze functie biedt gebruikers van Catenda een functie om te controleren of het Documenten dat zij gebruiken de meest recente versie is, door de QR-code op de PDF te scannen.

## 1. **QR-Code instellen op Catenda Hub**

De QR-code toewijzing vindt plaats via mappen, wat betekent dat elke projectbeheerder kan beslissen welke set mappen deze functie moet hebben.

Dit zijn de stappen om de QR-code functie toe te wijzen aan mappen in uw project;

1. Ga onder Documenten —> instellingen naar **'mapconfiguratie'**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/01-setup-qr-code-on-catenda-hub.png)

2\. Klik op het pluspictogram naast uw gewenste map om de mapconfiguratie te openen en zeg onder 'QR Code toewijzen' **'ja'**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/02-setup-qr-code-on-catenda-hub.png)

Het scannen van placeholders en plaatsing van QR-codes vindt alleen plaats op mappen met QR-code toewijzing;

> **Opmerking:** Zodra een bovenliggende map is toegewezen, hebben alle submappen deze toewijzing. QR-codes kunnen aan elke map worden toegewezen zodra een bovenliggende map nog niet is toegewezen.

## 2. De placeholder in uw Documenten plaatsen

Om deze functie te gebruiken, moet u de **[QR-code placeholder](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)**, verstrekt door Catenda, op uw Documenten plaatsen en vervolgens uploaden naar Catenda Hub. _Dimensievereiste:_ Dit moet een minimale grootte van 2 cm bij 2 cm hebben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/03-placing-the-placeholder-in-your-document.png)

De downloadkoppeling voor de QR-Code vindt u hier:

_[Downloadkoppeling](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)_

### 2.1 De QR-code als bestandsauteur plaatsen

Omdat Documenten niet kunnen worden gewijzigd nadat zij naar Catenda zijn geüpload, is het belangrijk dat de placeholder QR-Code op het Documenten wordt geplaatst voordat het naar Catenda wordt geüpload. De placeholder kan op elke laag worden geplaatst, behalve op de annotatilaag. Om Catenda de QR-Code te laten herkennen, moet deze als afbeelding worden toegevoegd. De afbeelding in het gepubliceerde Documenten moet exact dezelfde afbeelding zijn als de placeholder-afbeelding.

**PDF-optimalisatie** Veel programma's voeren optimalisatiestappen uit voor betere weergave en verkleining van bestandsgrootte. Deze stappen kunnen het aantal bytes in de afbeelding wijzigen, waardoor Catenda deze niet meer herkent. Hier vindt u enkele informatie over de placeholder die kan helpen bij optimalisatie. Pixeldichtheid: 144 dpi Afbeeldingscompressie: ZIP De afbeelding moet één gehele afbeelding zijn. Sommige optimizers kunnen de afbeelding als optimalisatie opsplitsen. Zorg ervoor dat de afbeelding na optimalisatie geheel is.

_Archicad_ Gebruik bij het plaatsen van de QR-code alstublieft: Importeren > interoperabiliteit > samenvoegen uit bestand > importeren en werkblad openen > slepen en neerzetten. Als u het werkblad opent en de PNG erop sleept en neer zet, verandert de resolutie en werkt het niet.

### 2.2 De QR-code op een bestaand Documenten plaatsen

Als u een Documenten hebt dat u niet hebt gemaakt en u wilt de QR-Placeholder toevoegen voordat u het naar Catenda Hub uploadt, zorg dan dat u het Documenten bewerkt en de QR-Placeholder als afbeelding toevoegt.

### 2.3 De QR-code op een Catenda Documenten plaatsen

Als uw Documenten al op Catenda staat, moet u de QR-placeholder toevoegen en een nieuwe revision uploaden. Als u geen toegang hebt tot een PDF-bewerkingsprogramma, kunt u het [gereedschap voor afbeeldingstempel annotatie](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6) gebruiken om de QR-placeholder aan uw Documenten toe te voegen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/04-placing-the-qr-code-a-catenda-document.png)

Om het Documenten op te slaan zodat de QR-placeholder wordt herkend, drukt u het Documenten af met [de printknop](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70) die u linksboven in uw Documenten-voorbeeld kunt vinden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/05-placing-the-qr-code-a-catenda-document.png)

Hiermee opent u het afdrukdialoogvenster van uw browser. Dit kan er zo uitzien voor Google Chrome:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/06-placing-the-qr-code-a-catenda-document.png)

Druk in het afdrukdialoogvenster het Documenten af naar PDF.

> **Opmerking 1:** De QR-code eindt alleen op de inhoudslaag als u het Documenten afdrukt. Als u het Documenten downloadt, wordt het op de annotatilaag weergegeven. **Opmerking 2:** Door naar PDF af te drukken, rasteri je u de inhoud van het Documenten. Dit betekent dat de tekst niet doorzoekbaar is wanneer u deze als revision naar Catenda uploadt.

De afgedrukte PDF met de placeholder kan nu als een nieuwe revision naar Catenda worden geüpload. Om uw revision-Geschiedenis schoon te houden, kunt u de vorige revision zonder de QR-code intrekken.

## 3. **Publicatie met QR-codes**

1. Upload een nieuwe revision van een PDF met de placeholder in een map met QR-code toewijzing
2. Tijdens publicatie wordt de PDF gescand op de placeholder en vervangen door een QR-code (gegenereerd voor deze revision)
3. De nieuw gegenereerde QR-code maakt deel uit van de PDF, die op Catenda Hub kan worden bekeken/gescand en/of gedownload.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/07-publishing-with-qr-codes.png)

Hier is een voorbeeld van de plaatsing van de QR-code placeholder en het resultaat na uploading naar Catenda Hub. 1\. Placeholder in het titelblok van een tekening. **Klaar voor uploaden.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/08-publishing-with-qr-codes.png)

2\. Placeholder in titelblok wordt vervangen door de gegenereerde QR-code. **Klaar voor verificatie.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/09-publishing-with-qr-codes.png)

### 3.1 **Documenten-Geschiedenis**

Na het uploaden van een Documenten met een QR-code placeholder kunt u zien dat het succesvol is verwerkt in de Documenten-Geschiedenis van het [rechtsinformatiemenu](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/10-document-history.png)

Als het genereren van uw QR-code is mislukt, kan dit zijn omdat uw QR-code kleiner was dan 2 cm x 2 cm of deze was geplaatst als een annotatie in plaats van een afbeelding.

**Annotaties platmaken** Sommige software biedt de mogelijkheid om annotaties plat te maken, waardoor de placeholder kan worden verwerkt. Hier volgen enkele voorbeelden:

**PDF X-change**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/11-document-history.png)

**Adobe Acrobat**

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3d7d02c461d3.png" width="300"/> --> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3398dc9eef22.png" width="300"/>

_BlueBeam Revu_ Wanneer u de placeholder in BlueBeam Revu plaatst en het Documenten opslaat, wordt het toegevoegd als een annotatie. Het is mogelijk om de QR-code plat te maken zodat deze deel uitmaakt van de inhoudslaag van het Documenten, maar zelfs als u deze regelmatig opslaat of de optie voor verkleinde bestandsgrootte gebruikt, wordt de QR-code gewijzigd en werkt deze niet met Catenda. Om de QR-code met Catenda te laten werken, drukt u in plaats daarvan het Documenten af met het BlueBeam-stuurprogramma:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/12-document-history.png)

Selecteer in het dialoogvenster Opslaan onder ZIP-afbeeldingen en schakel nabewerkingen in. Dit is omdat het compressiealgoritme dat voor de placeholder wordt gebruikt ZIP is.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/13-document-history.png)

Kies in het menu Nabewerkingen de optie Aangrenzende afbeeldingen combineren. Dit is omdat de afbeelding normaal in tweeën wordt gesplitst, dus het combineert deze terug samen. Als uw paginagrootte niet als standaardoptie bestaat, kunt u hier uw eigen aangepaste optie toevoegen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/14-document-history.png)
