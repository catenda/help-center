# 3D-Position von Modellen

## 1. **Exportieren mit den gleichen Koordinaten**

In Autorenplattformen können Sie mit verschiedenen Koordinaten exportieren. Alle Koordinaten funktionieren gut mit Catenda Hub. Es wird empfohlen, dass alle Personen im Projekt das gleiche Koordinatensystem verwenden, um sicherzustellen, dass Objekte nicht weit voneinander entfernt landen und sich Benutzer nicht fragen, warum sie einige Objekte sehen, während andere ausgeblendet sind, obwohl sie wirklich nur sehr, sehr weit entfernt sind.

## 2. **Objekte weit weg vom Ursprung**

Im Vergleich zu anderen Autorenplattformen hat Catenda Hub keine Probleme mit der Genauigkeit, wenn Objekte weit weg von 0 sind. Der im IFC-Datei angegebene Modellstandort wird verwendet, um zu entscheiden, wo das Modell in 3D existiert. Die Szene (Größe des Bereichs, der im 3D-Viewer geladen wird) ist nur so groß wie die Objekte, die sich darin befinden, und muss nicht den Ursprungspunkt (0,0,0) einschließen. Dies ermöglicht es Ihnen, problemlos auf Objekte zu zoomen, ohne berechnen zu müssen, wie weit sie vom Ursprung entfernt sind.

## 3. **Objekte weit weg voneinander entfernt**

Wenn Sie Objekte haben, die mehr als 10000 KM voneinander entfernt sind, können Sie auf Probleme stoßen, da die Szene sehr groß wird. Wenn Sie eine horizontale Schnittebene erstellen, werden die gesamte Szene abgeschnitten und wird empfindlich beim Verschieben. Wenn ein Modell versehentlich mit falschen Koordinaten importiert wird und sehr weit entfernt landet, möchten Sie es möglicherweise transformieren. Die Modelle funktionieren noch einzeln einwandfrei, aber zusammen mit anderen Modellen, die sehr weit entfernt sind, können Sie auf Probleme stoßen.

## 4. **Umwandlung der Position eines Modells**

Es ist möglich, die 3D-Position eines Modells auf der Modellübersichtsseite umzuwandeln, wenn Sie es in 3D geladen haben. Dies ermöglicht es Ihnen, das Modell in 3D zu verschieben, nachdem es in Catenda Hub importiert wurde. Diese Bewegung ist nur optisch in Catenda Hub. Wenn die IFC heruntergeladen wird, wird sie an ihrem ursprünglichen Standort zurückkehren. Diese Methode wird nur empfohlen, um das Modell vorübergehend umzuwandeln, während Sie auf eine IFC-Datei mit dem richtigen Standort warten. Dies liegt daran, dass einige Funktionen mit umgewandelten Modellen nicht ordnungsgemäß funktionieren, wie z. B. 2D-Viewer-Schnitte, Abfragen und Schnappschüsse. Messungen sind nicht betroffen und sind genau, wenn das Modell an die richtige Stelle verschoben wird. Weitere Informationen dazu finden Sie [hier](https://support.catenda.com/en/articles/4670270-model-overview-page#h_c10dbce6c8)
