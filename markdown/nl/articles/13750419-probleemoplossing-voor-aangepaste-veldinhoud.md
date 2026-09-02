# Probleemoplossing voor aangepaste veldinhoud

## 1. **Kan gearchiveerde vervolgkeuzeoptie niet herstellen**

Er treedt een logische impasse op als u een gearchiveerde optie probeert te herstellen terwijl de bijbehorende **Naam** momenteel wordt gebruikt door een actieve optie. Omdat het alleen mogelijk is om een naam aan één optie toe te wijzen, wordt het herstel geblokkeerd. _Vereiste toegang:_ Beheerderstoegang

Volg deze stappen om de gearchiveerde waarde te herstellen:

**Pas de actieve waarde een nieuwe naam toe** De actieve optie die momenteel de naam gebruikt, wordt door een beheerder bewerkt naar een tijdelijke waarde om de naam in het systeem vrij te maken.

**Herstel de gearchiveerde waarde** De **Uitgeschakelde lijst** is toegankelijk en de actie **Herstellen** wordt geselecteerd voor het vereiste item.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/01-unable-to-restore-archived-dropdown-option.png)

**Corrigeer de gegevens** De namen en codes worden aangepast naar de juiste status.

**Zet namen terug** De tijdelijke naam wordt gewijzigd in de oorspronkelijke beoogde naam.

## 2. **Uniekheid van namen en codes**

Het is belangrijk om onderscheid te maken tussen de **Naam** van een optie en de bijbehorende **Code**. Elke vervolgkeuzeoptie bestaat uit beide elementen, en het is alleen mogelijk om een optie op te slaan als zowel de naam als de code uniek zijn binnen dat specifieke aangepaste veld.

## 3. **Fout met dubbele naam**

Het is alleen mogelijk om een naam aan één optie in een vervolgkeuzelijst toe te wijzen. Als een fout met dubbele naam wordt weergegeven, worden de volgende stappen ondernomen: _Vereiste toegang:_ Beheerderstoegang

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/02-duplicate-name-error.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/03-duplicate-name-error.png)

**Verificatie van actieve lijst** De lijst met actieve opties wordt gecontroleerd om te bevestigen of de naam al in gebruik is.

**Verificatie van uitgeschakelde lijst** De uitgeschakelde lijst wordt gecontroleerd, omdat namen die aan gearchiveerde items zijn toegewezen, in het systeem blijven staan.

**Oplossing** U kunt alleen doorgaan door ofwel een andere unieke naam te gebruiken, ofwel de naam van de bestaande optie die deze naam bevat, te wijzigen.

## 4. **Fout met dubbele code**

Het is alleen mogelijk om een code aan één optie binnen een aangepast vervolgkeuzeveld toe te wijzen. De code is een unieke waarde die wordt gebruikt om blokken voor naamgevingsconventies te identificeren. _Vereiste toegang:_ Beheerderstoegang

Als een fout met dubbele code wordt weergegeven:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/04-duplicate-code-error.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/05-duplicate-code-error.png)

**Verificatie van actieve lijst** De actieve lijst wordt gecontroleerd om te zien of de code al in gebruik is.

**Verificatie van uitgeschakelde lijst** De uitgeschakelde lijst wordt gecontroleerd, omdat codes die aan gearchiveerde items zijn toegewezen, nog steeds die unieke waarde innemen.

**Oplossing** U kunt alleen doorgaan door ofwel een andere unieke code te gebruiken, ofwel de bestaande optie die deze code bevat, uit te schakelen.

## 5. Bestaande codes wijzigen

Het is alleen mogelijk om een code tijdens het initiële maken van een optie te definiëren, of als een reeds bestaande optie nog geen code heeft gekregen. Nadat een code is toegevoegd en opgeslagen, wordt deze aan die waarde vergrendeld en wordt het veld niet-bewerkbaar.

**Bewerkingsbeperkingen** Het is alleen mogelijk om de **Naam** van een optie te wijzigen nadat een code is toegepast. Het **Codeveld** zal grijs weergegeven worden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/06-modifying-existing-codes.png)

Vóór toepassing:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/07-modifying-existing-codes.png)

Na toepassing:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/08-modifying-existing-codes.png)

**Code herstellen** Als een code al in gebruik is door een gearchiveerd item, is het alleen mogelijk om die specifieke code te gebruiken door eerst de gearchiveerde optie uit de uitgeschakelde lijst te herstellen. Het is niet mogelijk om een nieuwe optie in te dienen met een code die nog steeds technisch door een uitgeschakeld item wordt vastgehouden.

**Code wijzigen** Om een volledig andere code voor een bestaande naam te gebruiken, is dit alleen mogelijk door de huidige optie uit te schakelen en een nieuwe optie met de gewenste code te maken.

## 6. Invoerfouten voor geheetalvelden

Er gelden specifieke beperkingen voor geheetalvelden die leiden tot invoerfouten:

**Alleen gehele getallen** Het is alleen mogelijk om gehele getallen op te slaan in een aangepast geheetalveld.

**Niet-numerieke tekens** Hoewel u alleen nummers rechtstreeks in het veld kunt typen, is het mogelijk om niet-numerieke tekens in het veld te plakken.

**Gedrag van de knop Opslaan** Als er niet-numerieke tekens in het veld aanwezig zijn, is de knop Opslaan uitgeschakeld.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/09-input-errors-for-integer-fields.png)

## 7. **Zichtbaarheid en filtering van borden**

Als een aangepast veld niet zichtbaar is op een issue board, worden de volgende instellingen geverifieerd:

**Veldtoewijzing** Bij het maken van een aangepast veld is het mogelijk om dit toe te voegen aan een issue board. Het veld moet aan het specifieke board worden toegevoegd om in de header van het issue te verschijnen.

**Tabelweergave** Het is alleen mogelijk om aangepaste veldgegevens in een lijstindeling weer te geven als de bijbehorende kolom in de tabelweergave van het issue board is geselecteerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/10-board-visibility-and-filtering.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/b99swgb4/11-board-visibility-and-filtering.png)

**Filterlimieten** Het is alleen mogelijk om op aangepaste velden te filteren als er maximaal 10 velden zijn toegewezen.
