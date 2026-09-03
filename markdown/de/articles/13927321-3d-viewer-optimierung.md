# 3D-Viewer-Optimierung

Obwohl Catenda Hub gut optimiert ist und die meisten Modelle ausführen kann, möchten einige Benutzer optimale Bedingungen schaffen.

Dieser Artikel enthält Informationen zu den folgenden Themen:

Hier sind einige Strategien, die verwendet werden können, um Ihren Arbeitsablauf in Catenda Hub zu optimieren

## 1. **Viele Objekte**

Selbstverständlich bedeutet das Laden weniger Modelle weniger Objekte und daher eine bessere Leistung. Das Aktivieren des [inkrementellen Renderings](https://intercom.help/bimsync-arena/en/articles/5784718-3d-viewer-settings#:~:text=Incremental%20rendering%3A) beschleunigt die Rotation um Modelle mit vielen Geometrien, da nicht alle Objekte beim Drehen geladen werden müssen. Als letzten Schritt können Sie eine [Abfrage](https://intercom.help/bimsync-arena/en/articles/4854514-queries) des Bereichs erstellen, in dem Sie arbeiten. Normalerweise befinden sich die Objekte nach dem Ausschneiden eines Teils des Modells noch im Speicher und sind nur versteckt. Mit einer Abfrage werden diese Objekte vollständig entfernt, was die Arbeit mit dem Modell vereinfacht. Beachten Sie, dass Sie mit Abfragen keine Bibliotheken verwenden können, da nicht alle Objekte geladen sind.

## 2. **Punktwolken**

Wenn Sie [feste Punktgröße](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=Adaptive%20(default)%2C%20or-,Fixed%20size,-.%20The%20slider%20below) verwenden, können Sie auf niedrige fps stoßen, wenn viele Punkte geladen wurden. Es kann auch vorkommen, dass das Laden von Punkten länger dauert, wenn das Speicherbudget des Systems erreicht ist. Punkte, die der Kamera am nächsten sind, werden zuerst geladen. Wenn Sie Punkte an einem bestimmten Ort laden möchten, ist es besser, zu dieser Position zu navigieren und dann die Punktwolke einzuschalten, damit sie dort zuerst mit dem Laden von Punkten beginnt. Um zu verhindern, dass Sie das Speicherlimit erreichen und niedrigere fps erhalten, können Sie das [Punktbudget](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=with%20your%20PC.-,Point%20Budget%3A,-Using%20the%20viewer) senken, damit weniger Punkte geladen werden.

## 3. **Browser-Zoomfaktor**

Stellen Sie sicher, dass der Zoomfaktor Ihres Browsers korrekt eingestellt ist, da ein großer Zoomfaktor einige Menüs so groß machen kann, dass andere verborgen sind. Während Grafiken, die durch Breite und Höhe definiert sind, mit dem Browser-Zoomfaktor skaliert werden können, können Grafiken, die durch Pixel definiert sind, pixeliger werden, wenn der Zoomfaktor erhöht wird. Ein kleiner Zoomfaktor kann dazu führen, dass Grafiken so klein werden, dass sie unsichtbar sind, und das genaue Anzeigen herunterskalierter Ressourcen kann das Gerät stärker beanspruchen.
