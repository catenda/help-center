# 3D Viewer-optimalisatie

Hoewel Catenda Hub goed is geoptimaliseerd en de meeste modellen kan uitvoeren, willen sommige gebruikers zich zo goed mogelijk instellen voor succes.

Dit artikel bevat informatie over de volgende onderwerpen:

Hier zijn enkele strategieën die kunnen worden gebruikt om uw werkstroom in Catenda Hub te optimaliseren

## 1. **Veel objecten**

Natuurlijk betekent het laden van minder modellen minder objecten en dus betere prestaties. Het inschakelen van [incrementeel renderen](https://intercom.help/bimsync-arena/en/articles/5784718-3d-viewer-settings#:~:text=Incremental%20rendering%3A) versnelt het roteren rond modellen met veel geometrie, omdat niet alle objecten hoeven te worden geladen bij het roteren. Als laatste stap kunt u een [query](https://intercom.help/bimsync-arena/en/articles/4854514-queries) van de sectie waaraan u werkt maken. Meestal wanneer u een deel van het model afzondert, bevinden de objecten zich nog steeds in het geheugen en zijn deze alleen verborgen. Met een query worden deze objecten volledig verwijderd en is het dus gemakkelijker om met het model te werken. Houd er rekening mee dat u geen eigenschappenbibliotheken met queries kunt gebruiken omdat niet alle objecten zijn geladen.

## 2. **Puntenwolken**

Als u [vaste puntgrootte](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=Adaptive%20(default)%2C%20or-,Fixed%20size,-.%20The%20slider%20below) gebruikt, kunt u met lage fps komen wanneer veel punten zijn geladen. U kunt ook ervaren dat punten langer laden wanneer het geheugenbudget van uw systeem is bereikt. Punten die het dichtst bij de camera liggen, worden eerst geladen. Als u punten op een specifieke locatie wilt laden, is het beter om naar die positie te navigeren en vervolgens de puntenwolk in te schakelen, zodat deze eerst punten daar gaat laden. Om te voorkomen dat u de geheugengrens bereikt en lagere fps krijgt, kunt u het [puntbudget](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=with%20your%20PC.-,Point%20Budget%3A,-Using%20the%20viewer) verlagen zodat minder punten worden geladen.

## 3. **Browserzoomschaal**

Zorg ervoor dat de zoomschaal van uw browser correct is ingesteld, omdat een grote zoomschaal sommige menu's zo groot kan maken dat anderen verborgen zijn. Terwijl afbeeldingen die zijn gedefinieerd op basis van breedte en hoogte mogelijk schalen met de browserschaal, kunnen afbeeldingen die per pixel zijn gedefinieerd, gepixeleerd worden wanneer de zoomschaal wordt vergroot. Een kleine zoomschaal kan ertoe leiden dat afbeeldingen zo klein worden dat ze onzichtbaar zijn, en het nauwkeurig weergeven van verkleinde resources kan meer eisen stellen aan het apparaat.
