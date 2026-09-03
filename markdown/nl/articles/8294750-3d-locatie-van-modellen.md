# 3D-locatie van modellen

## 1. **Exporteren met dezelfde coördinaten**

In creatieplatforms kunt u met verschillende coördinaten exporteren. Alle coördinaten werken prima met Catenda Hub. Het wordt aanbevolen dat iedereen in het project hetzelfde coördinatenstelsel gebruikt om ervoor te zorgen dat objecten niet ver van elkaar af komen te liggen en gebruikers zich niet afvragen waarom zij sommige objecten zien terwijl andere verborgen zijn, terwijl zij in werkelijkheid gewoon erg, erg ver weg zijn.

## 2. **Objecten ver weg van de oorsprong**

In vergelijking met andere creatieplatforms heeft Catenda Hub geen problemen met precisie wanneer objecten ver weg zijn van 0. De modellocatie die in het IFC-bestand is opgegeven, wordt gebruikt om te bepalen waar het model in 3D bestaat. De scène (grootte van het gebied dat in de 3D-viewer wordt geladen) is alleen zo groot als de objecten die erin zitten en hoeft het oorsprongspunt (0,0,0) niet op te nemen. Dit maakt het mogelijk dat u gemakkelijk kunt inzoomen op objecten zonder te hoeven berekenen hoe ver zij in relatie tot de oorsprong verwijderd zijn.

## 3. **Objecten ver weg van andere objecten**

Als u objecten hebt die meer dan 10000 km van elkaar af liggen, kunt u in problemen komen omdat de scène erg groot wordt. Als u een horizontaal clippingvlak maakt, wordt de gehele scène weggeknipt en wordt het gevoelig bij verplaatsing. Als een model daarom per ongeluk met de verkeerde coördinaten wordt geïmporteerd en heel ver weg eindigt, wilt u dit mogelijk transformeren. De modellen werken op zichzelf prima, maar samen met andere modellen die erg ver weg zijn, kunt u in problemen komen.

## 4. **De locatie van een model transformeren**

Het is mogelijk de 3D-locatie van een model op de modeloverzichtspagina te transformeren als u deze in 3D hebt geladen. Hiermee kunt u het model in 3D verplaatsen nadat het in Catenda Hub is geïmporteerd. Deze verplaatsing is alleen visueel in Catenda Hub. Als de IFC wordt gedownload, komt deze terug op de oorspronkelijke locatie. Deze methode wordt alleen aanbevolen om het model tijdelijk te transformeren terwijl u wacht op een IFC-bestand met de juiste locatie. Dit komt omdat bepaalde functies niet correct werken met getransformeerde modellen, zoals 2D-viewersecties, query's en issue-snapshots. Metingen worden niet beïnvloed en zijn nauwkeurig als het model op de juiste plaats wordt verplaatst. Meer informatie over hoe u dit doet, vindt u [hier](https://support.catenda.com/en/articles/4670270-model-overview-page#h_c10dbce6c8)
