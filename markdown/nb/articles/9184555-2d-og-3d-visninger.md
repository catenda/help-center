# 2D og 3D-visninger

2D og 3D-visninger kan legges til som en [kommentar i en Sak](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_f76b44d3ca). Øyeblikksbilder er allsidige måter å kommunisere om 2D og 3D-informasjon på, da de ikke bare inneholder visuell informasjon, men kan brukes til å beskrive et sted og et tidspunkt i et dokument eller modell. Informasjonen som lagres i øyeblikksbilder gjør det mulig for deg å samarbeide med 2D og 3D-informasjon, da du vil være i stand til å spille av øyeblikksbilde ditt i en av dine BCF- og IFC-aktiverte tjenester.

Dette er hvordan et 3D-øyeblikksbilde kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/01-intro.png)

Øyeblikksbildet nedenfor hadde følgende oppsett da øyeblikksbildet ble tatt: Øyeblikksbildet ble gjenskapt med originale revisjoner. De 7 modelldokumentene som var koblet til øyeblikksbildet ble lastet inn i 3D-visningen. De 5 valgte objektene fra modelldokumentene ble valgt 2 dokumenter som ikke er koblet til modeller ble lastet inn, hvorav ett IFC og ett punktsky. 2D-øyeblikksbilder vil ha de samme knappene, men med et bilde av 2D-visningen vedlagt.

## 1. **Opprette et øyeblikksbilde**

Hvis du har en modell lastet inn i 3D, kan du klikke plussknappen til venstre for Sak-kommentarfeltet for å legge til et 3D-øyeblikksbilde i kommentaren. Hvis du har 2D-visningen åpen, kan du klikke plussknappen til venstre for Sak-kommentarfeltet for å legge til et 2D-øyeblikksbilde i kommentaren. Et øyeblikksbilde opprettes automatisk hvis du har lastet inn noe i 2D eller 3D og oppretter en ny Sak. Klikk [her](https://support.catenda.com/en/articles/10345863-snapshots) for å lese mer om øyeblikksbilder.

## 2. **Viserbilder**

Øyeblikksbilder er den beste måten å lage bilder av høy kvalitet eller renderinger fra Catenda Hub-visningen for følgende årsaker:

- Øyeblikksbildebilder kan lastes ned fra [vedleggsutsnittet](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_e36d14edc8).
- Øyeblikksbildebilder kan ha høyere oppløsninger enn bare å ta et skjermbilde fra visningen.
- Øyeblikksbildebilder har transparente bakgrunner. Med 3D-øyeblikksbilder inneholder bildet bare piksler der det er objekter i 3D. Med 2D-øyeblikksbilder inneholder bildet bare piksler der det er linjer i 2D.

### 2.1 **Bildestørrelse**

Størrelsen på bildet som er vedlagt, er avhengig av størrelsen på visningen og zoomprosenten i nettleseren. Antall piksler i et øyeblikksbildebilde avhenger av størrelsen på visningen, zoomprosenten i nettleseren og skjermskalaen for operativsystemet ditt. Det største bildet jeg har kunnet generere så langt har vært 6417 piksler ganger 11113 piksler. For å lage et øyeblikksbilde så stort, hadde jeg følgende innstillinger:

- 4K-skjermvisning.
- Innholdspanel og 3D-panel synlige.
- Innholdspanel så lite som mulig.
- Nettleser i fullskjerm.
- Nettleserens skala 10 %
- Skjermskala i Windows 100 %

Disse innstillingene er veldig tunge for systemet, og PC-en din har kanskje ikke kapasitet til å håndtere dette, så du må kanskje justere disse innstillingene for å passe dine spesifikasjoner.

## 3. **Avspillingsikonet**

Øyeblikksbilder inneholder informasjon om tidspunktet da du opprettet øyeblikksbildet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/02-play-icons.png)

Hvis et objekt var skjult på opprettingstidspunktet, vil objektet med den ID-en bli skjult når øyeblikksbildet blir gjenskapt. Hvis et objekt ble isolert, vil objektet med den ID-en bli vist mens objekter som ikke er isolert, blir skjult. Dette gjenspeiles også for alle objekter med nye ID-er som kan bli lagt til nyere versjoner av modellen.

### 3.1 **Gjenskap øyeblikksbilde**

Øyeblikksbilder er gode for å vise folk hva du ser, da de vil kunne gjenskape de samme visningene ikke bare innenfor Catenda Hub, men også i sitt eget miljø.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/03-recreate-snapshot.png)

Øyeblikksbilder kan gjenskapes ved å spille dem både i Catenda Hub og i tilleggene våre. I Catenda Hub vil øyeblikksbildet flytte kameraet til riktig sted i visningen vår. I tilleggene vil visuet for vertsprogramvaren bli vist.

- Ved å klikke på denne knappen vil øyeblikksbildet bli gjenskapt med samme modell og siste revisjoner lastet inn i 3D-visningen.
- Det tilkoblede punktskyet eller IFC-dokumentene vil bli lastet inn
- Kameraet i 3D-visningen vil flytte seg til plasseringen angitt i øyeblikksbildet.
- Klippeplenene fra øyeblikksbildet vil bli gjenskapt
- Objektene som ble valgt i øyeblikksbildet, vil bli valgt
- Fargene som ble angitt i markeringer, vil motta sine spesifiserte farger

### 3.2 **Gjenskap øyeblikksbilde med opprinnelige revisjoner**

Klikk denne knappen for å gjenskape øyeblikksbildet med den originale modellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/04-recreate-snapshot-with-original-revisions.png)

Modellrevisjonene som var aktive i 3D-visningen på tidspunktet for opprettingen av øyeblikksbildet, blir lastet inn i 3D-visningen når denne knappen klikkes.

## 4. **Innholdsikonet**

Du finner ikoner som inneholder informasjon om innholdet i øyeblikksbildet nederst til høyre i øyeblikksbildet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/05-content-icons.png)

Hvis innholdspanelet er gjort lite, kan du finne noen av disse innholdsikoner i handlingsmenyen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/06-content-icons.png)

Handlingsmenyen kan finnes nederst til høyre i øyeblikksbildet der det ikke er nok plass til å vise alle innholdsikonet.

### 4.1 **Modellvelger**

Hvis 3D-visningen er åpen, vil modellastemenyen være tilgjengelig

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/07-model-picker.png)

- Modellene med en avmerking i denne menyen vil bli lastet inn når øyeblikksbildet blir spilt av.

    <div class="intercom-container"><img height="24" src="https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/inline-b248400a1359.png" style="height: auto;" width="30"/></div>

- Modellene med et plusstegn foran dem vil bli lagt til settet med modeller med avmerking etter at du har trykket lagre.

    <div class="intercom-container"><img height="25" src="https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/inline-ca568d75479a.png" style="height: auto;" width="30"/></div>

- Modellene med et minustegn foran dem vil bli fjernet fra settet med modeller med avmerking etter at du har trykket lagre.

    <div class="intercom-container"><img height="30" src="https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/inline-ff3494b6d9f8.png" style="height: auto;" width="30"/></div>

- Avhengig av innstillingene for objektsynlighet i øyeblikksbildet kan tilføyde modeller være helt skjult. Selv om de ikke er synlige, bør du se at de er lastet når Saken blir spilt av.
- Modellene som er aktivert når denne menyen åpnes, gjenspeiler modellene som er lastet inn i 3D-visningen. For å enkelt legge til/fjerne et sett med modeller, kan du lage et bokmerke, spille av bokmerket, gå til øyeblikksbildet, klikke på handlingsmenyen og trykke lagre i modellastemenyen.
- Hvis en modell i øyeblikksbildet ditt har samme IFCPROJECT-GUID som en modell i modellseksjonen, blir modellene automatisk koblet.

Her er en artikkel fra BuildingSMART som beskriver hvordan dette gjøres i Revit [https://user.buildingsmart.org/knowledge-base/ifcproject/](https://user.buildingsmart.org/knowledge-base/ifcproject/)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/08-model-picker.png)

### 4.2 **Vis valgte objekter**

Velg objektene som er valgt i øyeblikksbildene, i 3D-visningen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/09-show-selected-objects.png)

Viser hvor mange objekter som er valgt i øyeblikksbildet

### 4.3 **Koblede dokumenter**

Klikk her for å laste inn modellene fra øyeblikksbildet i tillegg til modellene som allerede finnes i visningen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/10-linked-documents.png)

Viser hvor mange modeller som er lastet inn i øyeblikksbildet.

### 4.4 **Angi kameraposisjon**

Flytt kameraet til posisjonen til øyeblikksbildet i 3D-visningen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/11-set-camera-position.png)

Hvis du har flyttet 3D-visningen etter å ha spilt av øyeblikksbildet, kan du klikke denne knappen for å gå tilbake til posisjonen til øyeblikksbildet.

## 5. **Bildeutsnitt**

Hvis du holder musepekeren over bildet av et 2D eller 3D-øyeblikksbilde, vil et forstørrelsesglass vises. Dette kan se slik ut som øyeblikksbildet nedenfor:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/avkn9zqg/12-image-pop-out.png)

Etter at øyeblikksbildet er sendt inn, kan bildet som er koblet til det, [poppes ut](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_e36d14edc8) for å se innholdet dets i et større format og laste det ned.

## 6. **Slette et øyeblikksbilde**

Det er ikke mulig å slette et øyeblikksbilde som er vedlagt en kommentar. Hvis du vil fjerne øyeblikksbildet fra Saken, må du slette hele kommentaren.
