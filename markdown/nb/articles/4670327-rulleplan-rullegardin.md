# Rulleplan-rullegardin

Hvis det er modeller i prosjektet som inneholder rutenett, vil rulleplan-rullegardin vises mot øvre venstre hjørne av [3D-viseren](https://support.catenda.com/en/articles/8227211-3d-viewer#h_2eec7c411b).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/01-intro.png)

Etter å ha klikket på rulleplan-rullegardin begynner rutenett og justeringer som er tilgjengelige i hver av modellene i prosjektet å lastes inn.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/02-intro.png)

Klikk på øyeikonet for et rutenett for å forhåndsvise kommentarlinjene for hver av aksene i 3D-viseren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/03-intro.png)

Denne artikkelen inneholder informasjon om følgende emner:

_Forhåndsvisning av kommentarer – Vis akser_

## 1. **1. Rulleplantyper**

Det finnes to typer rulleplan som kan vises

### 1.1 **1.1 Rutenett**

Rutenett er en type rulleplan som ofte brukes i bolig-, nærings- og industribygg som ofte går hånd i hånd med infrastruktur- og sivilkonstruksjonsprosjekter. Hvis en modell i prosjektet inneholder et IfcGrid i sin siste revisjon, vil det vises i rulleplan-menyen. De første planene som vises i rulleplan-rullegardin er rutenett. Rutenett er adskilt etter de forskjellige modellene de er fra. Modeller kan inneholde ett eller flere rutenett som inneholder forskjellige akser. Hvilke rutenett som eksporteres avhenger av eksporteren fra forfatterløsningen, men ofte eksporteres et eget rutenett for hver etasje av modellen. For hvert rutenett vises navnet på IfcStorey som rutenettet er på. Disse samme etasjene kan også finnes i etasjemenyen i 2D-viseren. Navnet på modellen rutenettet er fra og revisjonsnummeret det er i vises.

### 1.2 **1.2 Justeringer**

Justeringer er en type rulleplan som ofte brukes i infrastruktur- og sivilkonstruksjon, men har blitt sett brukt i bolig-, nærings- og industribygg også. Hvis en modell i prosjektet inneholder et IfcAlignment i sin siste revisjon, vil det vises i rulleplan-menyen. Dette er hvordan justeringer kan se ut i rulleplan-menyen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/04-1-2-alignments.png)

For hver justering vises navnet på justeringen sammen med navnet på modellen den er fra og revisjonsnummeret.

## 2. **2. Forhåndsvis kommentarlinjer**

Hvert rulleplan har en forhåndsvisningsknapp som ser ut som et øye.

![Rulleplan forhåndsvisningsknapp Catenda Hub for rutenett og justeringer](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/05-2-preview-annotation-lines.png)

Klikk på forhåndsvisningsikonet for et rulleplan for å forhåndsvise kommentarlinjene for rulleplanet i 3D-viseren. Så snart forhåndsvisningsikonet er uthevet i grønt, er kommentarlinjene for det valgte rulleplanet synlige i 3D-viseren.

_2.1 Rulleplan kommentarlinje_ En rulleplan kommentarlinje består av en kontinuerlig linje med en sirkel og en bokstav på hver ende.

Valg av kommentarlinjesirkel Klikk på kommentarlinjesirkelen på hver ende av en akse eller justering for å aktivere aksen eller justeringen. Kommentarlinjesirkelen for aktiverte akser eller justeringer er uthevet når den er valgt. Etter å ha valgt en kommentarlinje, vises forhåndsvisningsplanet som er forbundet med den aksen eller justeringen som en transparent overflate i 3D-viseren. Merk at når det er valgt, er planikikonet for den aksen eller justeringen også uthevet i grønt i rulleplan-rullegardin.

Klikk på kommentarlinjesirkelen igjen for å deselektere kommentarlinjen og skjule planet.

Grenser for rutenettskommentarlinje For rutenett er kommentarlinjen en enkelt rett, plan linje som strekker seg litt forbi grensene for modellen i høyden som vises i rulleplan-rullegardin. For justeringer består kommentarlinjen av flere rette eller buede segmenter der start-, sluttkoordinater, høyde og retning kan sees i justeringsmenyen i informasjonspanelet.

### 2.1 **2.2 Finne kommentarlinjer**

Siden kommentarlinjer har en 3D-representasjon, må du passe på at de ikke blir dekket av objekter fra andre modeller, eller at jordelevasjonen i miljøet er under kommentarlinjene slik at de ikke blir skjult.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/06-2-2-finding-annotation-lines.png)

## 3. **3. Vis akser**

Til høyre for et rutenett i rulleplan-rullegardin kan en vis akser-meny utvides.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/07-3-show-axes.png)

Utvid vis akser-menyen for bedre kontroll over hver av aksene. Her kan hver akse sees etter navn og med sine to rulleplanknapper.

## 4. **4. Rulleplan overflateknapp**

Etter å være aktivert, strekker den transparente rulleplanoverflaten seg fra kommentarlinjen til øvre grenser for modellen på samme måte som en klippeplanoverfplate. I motsetning til en klippeplanoverfplate som ser tilsvarende transparent ut og kan flyttes, er dette et transparent objekt som ikke kan flyttes fra kommentarlinjen. I tillegg til klippeplanoverflatene er det mulig å måle til rulleplanoverflater. Klikk [her](https://support.catenda.com/en/articles/4670298-measuring-to-grids) for å lese mer om måling til ulike rulleplanoverflater.

### 4.1 **4.1 Rutenettsaksoverflate**

Den første knappen aktiverer rutenettsplanoverflatoen for den aksen. Slik kan rutenett se ut når aksoverflaten er aktivert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/08-4-1-grid-axis-surface.png)

Klikk på kommentarsirkelen ved enden av en rutenettsinie i 3D-viseren for å aktivere og deaktivere rutenettsaksoverflaten.

### 4.2 **4.2 Justeringsoverflate**

Klikk på planikikonet for å aktivere justeringsplanet. Velg justeringsplanet for å se informasjon om de ulike segmentene i inspeksjonmenyen.

## 5. **5. Klipp langs rulleplan-knapp**

### 5.1 **5.1 Klipp langs rutenettsakse**

Den andre knappen for en rutenettsakse i utvid akser-menyen for rulleplan-rullegardin oppretter et klippe plan langs rutenettsakselen. Dra en akseklippe plan for å dra klippeplanet vinkelrett langs aksen.

### 5.2 **5.2 Klipp langs justering**

Klikk på den andre knappen med klippeplan-ikonet for å opprette et klippeplan langs en justering. Justeringer klippeplaner fungerer på samme måte som rutenettsklippeplaner bortsett fra klikk- og dra-oppførselen. I stedet for å bli dratt vinkelrett på aksen, følger justeringens klippeplanoverfplate krumningen og retningene til segmentene i justeringen slik at planet alltid er i en skrå vinkel til krumningen på plasseringen langs justeringen.

<p class="intercom-align-center no-margin"><img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/inline-8520a612b6e1.png" width="150"/> -> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/y1c9bh9y/inline-2e858207316f.png" width="150"/></p>

### 5.3 **5.3 Klipping relativt til 3D-kameraet**

Med enten rulleplan-klippeplaner, men spesielt med justeringsklippeplaner, kan grensene for klippeplanoverflaten kanskje ikke være synlige fordi den kan være utenfor visningen av kameraet eller helt bak kameraet. Hvis objekter ser ut til å forsvinne etter å ha dratt på klippe planet, kan det være fordi klippeplanet blir dratt bak kameraet. I denne situasjonen kan det ofte hjelpe å enten vende klippe planet med vend-knappen i menyen mot bunnen av 3D-viseren eller å zoome ut slik at grensene for klippe planet er synlige.
