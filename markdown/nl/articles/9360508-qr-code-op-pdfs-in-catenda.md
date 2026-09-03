# QR-code op PDF's in Catenda

QR-codes kunnen per map worden geconfigureerd in de [mapconfiguratie](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) van [Documenten-instellingen](https://support.catenda.com/en/articles/7831371-document-settings).

Deze functie biedt Catenda-gebruikers een functie om te controleren of het document dat zij gebruiken de nieuwste versie is, door de QR-code op de PDF in te scannen.

## 1. **QR-code instellen op Catenda Hub**

De QR-code-toewijzing gebeurt via mappen, wat betekent dat elke projectbeheerder kan beslissen over een geselecteerde set mappen voor deze functie.

Dit zijn de stappen om de QR-code-functie aan mappen in uw project toe te wijzen;

1. Ga onder het document —> instellingen naar **'mapconfiguratie'**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/01-setup-qr-code-on-catenda-hub.png)

2\. Klik op het plusteken naast uw gewenste map om de mapconfiguratie te openen en zeg onder 'QR-code toewijzen' **'ja'**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/02-setup-qr-code-on-catenda-hub.png)

Het scannen van tijdelijke aanduidingen en het plaatsen van QR-codes vindt alleen plaats op mappen met QR-code-toewijzing;

> **Opmerking:** Zodra een bovenliggende map is toegewezen, hebben alle submappen deze toewijzing QR-codes kunnen aan elke map worden toegewezen als een bovenliggende map nog niet is toegewezen.

## 2. De tijdelijke aanduiding in uw document plaatsen

Om deze functie te gebruiken, moet u de **[QR-code-tijdelijke aanduiding](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)**, aangeboden door Catenda, op uw document plaatsen en deze vervolgens naar Catenda Hub uploaden. _Afmeting vereist:_ Dit moet minimaal 2 cm x 2 cm groot zijn.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/03-placing-the-placeholder-in-your-document.png)

De downloadkoppeling voor de QR-code is hier te vinden:

_[Koppelingen downloaden](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)_

### 2.1 De QR-code als bestandsauteur plaatsen

Aangezien Documenten na het uploaden naar Catenda niet kunnen worden gewijzigd, is het belangrijk dat de QR-code-tijdelijke aanduiding op het document wordt geplaatst voordat het naar Catenda wordt geüpload. De tijdelijke aanduiding kan op elke laag worden geplaatst behalve op de annotatielaag. Om de QR-code door Catenda te laten herkennen, moet deze als afbeelding worden toegevoegd. De afbeelding in het gepubliceerde document moet exact dezelfde afbeelding zijn als de tijdelijke aanduidingsafbeelding.

**PDF-optimalisatie** Veel programma's voeren optimalisatiestappen uit voor beter bekijken en kleinere bestandsgrootte. Deze stappen kunnen het aantal bytes in de afbeelding veranderen, waardoor Catenda deze niet meer herkent. Hier is informatie over de tijdelijke aanduiding die kan helpen bij optimalisatie. Pixeldichtheid: 144 dpi Afbeeldingscompressie: ZIP De afbeelding moet één geheel zijn. Sommige optimalisators kunnen de afbeelding als optimalisatie splitsen. Zorg ervoor dat de afbeelding na optimalisatie heel is.

_Archicad_ Bij het plaatsen van de qr-code kunt u het beste gebruikmaken van: Importeren > interoperabiliteit > samenvoegen uit bestand > importeren en worksheet openen > slepen en neerzetten Als u het werkblad opent en de PNG sleept en neerzet, wordt de resolutie gewijzigd en werkt het niet.

### 2.2 De QR-code op een bestaand document plaatsen

Als u een document hebt dat u niet hebt gemaakt en u wilt de QR-code-tijdelijke aanduiding voordat u het naar Catenda Hub uploadt, zorg er dan voor dat u het document bewerkt en de QR-code-tijdelijke aanduiding als afbeelding toevoegt.

### 2.3 De QR-code in een Catenda-document plaatsen

Als uw document al in Catenda staat, moet u de QR-code-tijdelijke aanduiding toevoegen en een nieuwe revisie uploaden. Als u geen toegang hebt tot een PDF-bewerkingsprogramma, kunt u de [gereedschap voor afbeeldingsstempel-annotaties](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6) gebruiken om de QR-code-tijdelijke aanduiding aan uw document toe te voegen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/04-placing-the-qr-code-a-catenda-document.png)

Druk het document af met [de afdrukknop](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70) die u in de linkerbovenhoek van uw documentvoorvertoning kunt vinden om het document op te slaan zodat de QR-code-tijdelijke aanduiding wordt herkend.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/05-placing-the-qr-code-a-catenda-document.png)

Hiermee wordt het afdrukdialoogvenster van uw browser geopend. Dit is wat het voor Google Chrome kan lijken:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/06-placing-the-qr-code-a-catenda-document.png)

Druk in het afdrukdialoogvenster het document af naar PDF.

> **Opmerking 1:** De QR-code eindigt alleen op de inhoudslaag als u het document afdrukt. Als u het document downloadt, bevindt het zich op de annotatielaag. **Opmerking 2:** Door af te drukken naar PDF rasteriseert u de inhoud van het document. Dit betekent dat de tekst niet kan worden doorzocht wanneer u deze als revisie naar Catenda uploadt.

De afgedrukte PDF met de tijdelijke aanduiding kan nu als een nieuwe revisie naar Catenda worden geüpload. Om uw revisiegeschiedenis schoon te houden, kunt u de vorige revisie zonder QR-code intrekken.

## 3. **Publiceren met QR-codes**

1. Upload een nieuwe revisie van een PDF met de tijdelijke aanduiding in een map met QR-code-toewijzing
1. Tijdens het publiceren wordt de PDF gescand op de tijdelijke aanduiding en vervangen door een QR-code (gegenereerd voor deze revisie)
1. De nieuw gegenereerde QR-code maakt deel uit van de PDF, die kan worden bekeken/gescand op Catenda Hub en/of kan worden gedownload.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/07-publishing-with-qr-codes.png)

Hier is een voorbeeld van de plaatsing van de QR-code-tijdelijke aanduiding en de resultaten na het uploaden naar Catenda Hub. 1\. Tijdelijke aanduiding in het titelbalk van een tekening. **Klaar voor uploaden.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/08-publishing-with-qr-codes.png)

2\. Tijdelijke aanduiding in titelbalk wordt vervangen door de gegenereerde QR-code. **Klaar voor verificatie.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/09-publishing-with-qr-codes.png)

### 3.1 **Documentgeschiedenis**

Na het uploaden van een document met een QR-code-tijdelijke aanduiding kunt u zien dat dit succesvol is verwerkt in de Documentgeschiedenis van het [rechtsinformatiemenu](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/10-document-history.png)

Als het genereren van uw QR-code is mislukt, kan dit gebeurd zijn omdat uw QR-code kleiner was dan 2 cm x 2 cm of omdat deze als annotatie in plaats van als afbeelding is geplaatst.

**Annotaties afvlakken** Sommige software biedt u de mogelijkheid om annotaties af te vlakken, zodat de tijdelijke aanduiding kan worden verwerkt. Hier zijn enkele voorbeelden:

**PDF X-Change**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/11-document-history.png)

**Adobe Acrobat**

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3d7d02c461d3.png" width="300"/> --> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3398dc9eef22.png" width="300"/>

_BlueBeam Revu_ Wanneer u de tijdelijke aanduiding in BlueBeam Revu plaatst en het document opslaat, wordt dit als annotatie toegevoegd. Het is mogelijk om de QR-code af te vlakken zodat deze deel van de inhoudslaag van het document wordt, maar zelfs wanneer u deze normaal opslaat of door de optie voor gereduceerde bestandsgrootte te gebruiken, wordt de QR-code gewijzigd en werkt deze niet met Catenda. Om de QR-code met Catenda te laten werken, voert u in plaats daarvan het volgende uit: Print het document met het BlueBeam-stuurprogramma:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/12-document-history.png)

Selecteer in het dialoogvenster Opslaan als ZIP-afbeeldingen en schakel nabewerking in. Dit is omdat het compressiealgoritme dat voor de tijdelijke aanduiding wordt gebruikt ZIP is.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/13-document-history.png)

Kies in het verwerkingsmenu van na de bewerking de optie Aangrenzende afbeeldingen combineren. Dit is omdat de afbeelding normaal in twee wordt gesplitst, zodat deze weer wordt samengevoegd. Als uw paginagrootte niet als standaardoptie bestaat, kunt u hier uw eigen aangepaste optie toevoegen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/14-document-history.png)
