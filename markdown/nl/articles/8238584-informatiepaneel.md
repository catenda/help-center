# Informatiepaneel

U vindt het Informatiepaneel als een van de vier hoofdpanelen die u aan de bovenkant rechts van uw scherm kunt openen. U kunt het i-pictogram indrukken om dit paneel te openen of u kunt [shift+4](https://support.catenda.com/en/articles/4670267-summary-of-most-important-shortcuts-and-basic-controls#:~:text=Inspect%20panel-,Shift%20%2B%204,-Show/hide%20last) indrukken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/01-intro.png)

In het informatiepaneel kunt u de volgende secties vinden:

## 1. **Inspect**

Hiermee kunt u de informatie over uw geselecteerde objecten zien. Klik [hier](https://support.catenda.com/en/articles/4670285-inspect-panel) voor meer informatie over het inspectpaneel.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/02-inspect.png)

## 2. **Quantity Take-Off**

Hiermee kunt u een lijst met objecten maken en exporteren en de sommen van waarden berekenen die aan de verschillende geselecteerde objecten zijn gekoppeld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/03-quantity-take-off.png)

Klik [hier](https://support.catenda.com/en/articles/6673929-quantity-take-off-qto) voor meer informatie over Quantity Take-Off

## 3. **4D**

In deze sectie kunt u de voortgang van modellen volgen met de 4e dimensie. Tijd. Als uw IFC-bestand een IFCWORKPLAN bevat, kunt u een tijdschema voor de objecten in uw bestand zien.

> **Opmerking:** 4D in Catenda is alleen beschikbaar voor ifc-bestanden die zijn geëxporteerd uit [SYNCHRO](https://www.bentley.com/software/synchro/). Deze bestanden kunnen een IfcWorkPlan en IfcTasks bevatten

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/04-4d.png)

Aan het begin van het tijdkader zijn alle objecten verborgen en afhankelijk van hoe ver de tijd is gevorderd, verschijnen objecten met de juiste instelling. Hier volgt een voorbeeld van hoe de 4D-sectie eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/05-4d.png)

### 3.1 **4D-kolommen**

## 4. - Het taaknummer

_Taak-ID_ - De ID van de taak

_Naam_ - De naam van de taak

_Duur_ - De duur van de taak

**Start** De startdatum van de taak. Dit is wanneer het object in 3D verschijnt. De objecten verschijnen ook geselecteerd. Tussen de startdatum en de einddatum van een taak zal de taakbalk oranje zijn. Klik op het klokpictogram naast de datum om naar dit moment in de tijd te gaan.

Beëindigen De einddatum van de taak - Na de einddatum blijven de objecten in 3D zichtbaar maar worden ze gedeselecteerd. Na deze datum zal de taakbalk groen zijn. Klik op het klokpictogram naast de datum om naar dit moment in de tijd te gaan.

**Producten** De objecten die aan deze taak zijn gekoppeld. De objecten kunnen worden geïsoleerd en geselecteerd door op isoleren en selecteren te klikken.

### 4.1 **4D opgeslagen views**

Het is mogelijk om een opgeslagen view te maken waar het 4D-werkplan is ingeschakeld. Als u deze opgeslagen view opent, ziet u welke objecten tot nu toe zichtbaar zijn gemaakt volgens het plan. In Catenda Hub kunt u de tijdschaal aanpassen naar elk moment dat u wilt. Als u de opgeslagen view extern deelt, ziet de externe partij die de opgeslagen view opent alleen de objecten die tot nu toe zichtbaar zijn gemaakt.

### 4.2 **Hoe weet ik of mijn IFC 4D-informatie bevat?**

Als uw ifc IFCTASKs bevat, kunt u deze in het 4D-paneel zien. Als uw ifc IFCRELASSIGNSTOPROCESSes bevat, worden deze taken ook aan objecten gekoppeld. Een programma dat u kunt gebruiken om te zien of deze aanwezig zijn, is [OpenIFCViewer](https://openifcviewer.com/). Hier kunt u de statistieken van uw model controleren

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/06-how-do-i-know-if-my-ifc-has-4d-information-in-it.png)

Waar u de entiteit in het statistische paneel kunt vinden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/07-how-do-i-know-if-my-ifc-has-4d-information-in-it.png)

## 5. **Selecties**

Hiermee kunt u een set objecten maken die vervolgens kunnen worden gestileerd en gekleurd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/08-selections.png)

Boven in het menu Selectie ziet u hoeveel items u momenteel hebt geselecteerd in de 3D-viewer en boomstructuurpaneel. Selecties kunnen worden opgeslagen door een [Snapshot](https://support.catenda.com/en/articles/8053352-issue-body#h_1ba7f8873f) of een [opgeslagen view](https://support.catenda.com/en/articles/8471481-bookmark) te maken en deze later af te spelen. Omdat selecties in de Snapshot van een onderwerp worden opgeslagen, kunnen ze naar andere programma's worden geïmporteerd en geëxporteerd via BCF. Een voorbeeld hiervan is dat onderwerpen met selecties uit de selectiemand die via de BCF live connector in Solibri worden gesynchroniseerd, selectiegegevens bevatten wanneer de Snapshot wordt afgespeeld.

### 5.1 **Nieuwe selectie**

Nadat u een object hebt geselecteerd, kunt u op Nieuwe selectie klikken

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/09-new-selection.png)

### 5.2 **Potloodpictogram**

Klik op het potloodpictogram om de naam van uw selectie te wijzigen

### 5.3 **Aantal objecten**

Na het potloodpictogram ziet u het aantal objecten dat momenteel in deze selectie voorkomt.

### 5.4 **Bijwerken**

Klik op de knop Bijwerken om de objecten in de selectie in te stellen op de objecten die u momenteel hebt geselecteerd in de 3D-viewer en boomstructuurpaneel.

### 5.5 **Objectkiezer**

Klik op de selectieknop om de items in uw selectie te selecteren

### 5.6 **Kleur**

Met de kleurknop kunt u de kleur van de objecten in uw selectie wijzigen. De kleurkiezer kan er als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/10-color.png)

Selecteer kleur met behulp van de kleurschuif, het palet of geef uw gewenste kleur op met een hexadecimale code. De tweede schuif bepaalt de transparantie, waarbij 1 100% ondoorzichtig is en 0 100% transparant. Rechtsonder ziet u de resulterende kleur.

### 5.7 **Verwijderen**

Klik op de knop Verwijderen om deze selectie te verwijderen

### 5.8 **Uitvouwen/samenvouwen**

Vouw de selectie uit om te zien welke objecten onderdeel van de selectie zijn.

## 6. **Metingen**

Hiermee kunt u zien welke metingen in de 3D-viewer zijn gemaakt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/n3tcgav1/11-measurements.png)

Klik [hier](https://support.catenda.com/en/articles/4670294-measuring-features) voor meer informatie over metingen
