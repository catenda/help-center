# Revisiecontrole via QR-code op PDF's

Druk documentrevisies af met gegenereerde QR-codes op papier, zodat projectleden kunnen verifiëren of het papier dat ze in handen hebben nog actueel is.

Geconfigureerde mappen kunnen worden geïdentificeerd aan de hand van het tandwielpictogram op het [mappictogram](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page#h_6af15c36b3). Dit is hoe een revisie met een gegenereerde QR-code er uit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/01-intro.png)

## 1. **Mapconfiguratie**

QR-code-stempeling kan [worden ingeschakeld voor geconfigureerde mappen](https://support.catenda.com/en/articles/7831371-document-settings#h_166a269870) op de documentenpagina. _Vereiste toegang:_ Beheerder

In geconfigureerde mappen worden nieuwe PDF-revisies die in documenten worden geüpload, verwerkt. Catenda scant het document naar de QR-code-aanduidingsafbeelding die hieronder is te vinden. Als de aanduiding met succes wordt geïdentificeerd, wordt een QR-code voor de revisie gegenereerd. _Vereiste toegang:_ Schrijftoegang tot het document

### 1.1 **QR-code toewijzen**

Om QR-code-stempeling aan een map toe te wijzen, gaat u naar [documentinstellingen](https://support.catenda.com/en/articles/7831371-document-settings), die kunnen worden gevonden als een subpagina van de [documentenpagina](https://support.catenda.com/en/articles/8204673-documents-page). Vouw in de documentinstellingen het [mapconfiguratiemenu](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) uit. Dit is hoe het mapconfiguratiemenu er uit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/02-assign-qr-code.png)

Onderaan vindt u de vervolgkeuzelijst QR-code toewijzen. Klik op de vervolgkeuzelijst en selecteer Ja om deze map in te stellen.

**Configuratie-overname** Wanneer een configuratie in een bovenliggende map is ingesteld, worden alle submappen deze configuratie overgenomen.

## 2. **QR-code-aanduidingsplaatsing**

Zoals genoemd in de inleiding van dit artikel, zal Catenda naar de QR-code-aanduidingsafbeelding zoeken om een QR-code op een revisie die naar een geconfigureerde map is geüpload, te genereren. De QR-code-aanduidingsafbeelding kan er ongeveer zo uitzien:

<p class="intercom-align-center no-margin">[<img alt="Catenda QR-Code placeholder" src="https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/inline-8c4db2f4912c.png" width="150"/>](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)</p>

Klik [hier](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk) om de QR-code-aanduiding te downloaden

> **Waarschuwing:** Kopieer/plak deze afbeelding niet en sla deze niet op als. De afbeelding kan er op de tekening hetzelfde uitzien, maar wordt niet herkend.

Klik [hier](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda) voor meer informatie over het plaatsen van de aanduiding op een PDF. Dit is hoe de aanduiding er uit kan zien wanneer deze in het titelblok van een tekening is geplaatst:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/03-qr-code-placeholder-placement.png)

## 3. **Een revisie met een aanduiding uploaden**

Upload een nieuwe revisie van een PDF met de aanduiding in een map met QR-code-toewijzing. Dit is alleen van toepassing op gepubliceerde revisies!!! Concepten of gedeelde PDF's krijgen pas een QR-code gegenereerd nadat ze zijn gepubliceerd.

### 3.1 **Revisie QR-code generatie**

Nadat de QR-code-aanduiding is geplaatst, kan de PDF als nieuwe revisie naar de geconfigureerde map worden geüpload. Tijdens het uploaden verwerkt Catenda de afbeeldingen in het document.

**Bytenopdracht** De juiste bytes die tot de zwarte en witte pixels in de Catenda QR-code-aanduiding behoren, moeten in de juiste volgorde aanwezig zijn.

**Dimensie-vereiste** De afbeelding moet een minimale breedte en hoogte van 2 cm x 2 cm hebben.

**Voorbeeld van gegenereerde QR-code** Dit is hoe het titelblok in het bovenstaande voorbeeld er uit kan zien nadat de PDF is verwerkt en een QR-code is toegevoegd:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/04-revision-qr-code-generation.png)

## 4. **Statuswerkstroom -** Publiceren om QR-code te genereren

Zonder de statuswerkstroom worden alle geüploade revisies onmiddellijk gepubliceerd. Documenten worden alleen gescand op QR-code-aanduidingen wanneer zij worden gepubliceerd.

### 4.1 **Gedeelde revisies versus gepubliceerde revisies**

Met de statuswerkstroom ingeschakeld, worden nieuwe revisies geüpload als gedeelde revisies als stap voorafgaand aan publicatie. Wanneer u naar de gedeelde revisie kijkt, kunt u het originele document zien voordat Catenda het met een gegenereerde QR-code heeft gewijzigd. Met de statuswerkstroom vindt het vervangen van de QR-code-aanduiding met de gegenereerde QR-code plaats wanneer een gedeelde revisie in een geconfigureerde map met de QR-code-aanduiding wordt gepubliceerd.
