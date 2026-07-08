# Punktwolken in Catenda Hub

> Erfahren Sie, wie Sie von Laserscans und LIDAR-Technologien in Catenda Hub profitieren können.

> **Hinweis:** Laden Sie eine Beispieldatei von [hier](https://drive.google.com/file/d/1G8U916oihDl5qHrTfQaVHxDeLsbq1ulG/view?usp=sharing) herunter.

Punktwolken-Datensätze (PC) können in Catenda Hub visualisiert werden. Einzelne PC können im Dokumentenbereich in der Vorschau angezeigt werden. Mehrere PC können in den [3D Viewer](https://support.catenda.com/en/articles/8227211-3d-viewer) geladen werden. Im 3D Viewer können PC zusammen mit anderen 3D-Dokumentformaten wie IFC-Modellen und GML-Dateien angezeigt werden.

Nachfolgend finden Sie verschiedene Einstellungen zur Anzeige Ihrer Daten:

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p>Adaptiv - Dünn - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-05a450dc777f.png" style="height: auto;" width="3839"/></div></td><td><p>Adaptiv - Dicht - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-196a1135014a.png" style="height: auto;" width="3839"/></div></td></tr><tr><td><p>Fest - Dicht - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-66e21551bbef.png" style="height: auto;" width="3834"/></div></td><td><p>Fest - Dünn - Intensität</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-4a2046c8eaf1.png" style="height: auto;" width="3839"/></div></td></tr></tbody></table></div>

## 1. **Dokumentenbereich Vorschau**

PC-Daten der folgenden zwei Dateiformate können in Catenda in der Vorschau angezeigt werden.

- `\*.e57`
- `\*.las`

PC können wie jedes andere Dokument im Dokumentenbereich hochgeladen werden. Für diese zwei Dateiformate können Dateien bis zu 25 GB in den Dokumentenbereich hochgeladen werden. Mehrere Dateien können im Dokumentenbereich geladen und zusammen im 3D Viewer angezeigt werden.

### 1.1 **PC-Daten hochladen**

Es wird empfohlen, den [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) zu verwenden oder Ihre PC-Datei in einen gezippten Ordner zu komprimieren und den [Zip-Import](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) zum Hochladen Ihrer PC zu verwenden. Diese Methoden helfen Ihnen, Zeit zu sparen, da die Hochladedateigröße kleiner ist, und minimieren das Risiko eines Netzwerkfehlers, da die Datei schneller hochgeladen wird.

Nach dem Hochladen einer PC in den Dokumentenbereich beginnt die Dokumentvorschau mit der Verarbeitung. Während die Vorschau verarbeitet wird, sehen Sie einen grauen Balken oben in Ihrer Dokumentvorschau.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/01-uploading-pc-data.png)

Die Verarbeitungsdauer der Vorschau hängt von der Größe der PC ab. Die Verarbeitung dauert 1 Stunde pro GB, kann aber je nach Punktwolke mehr oder weniger sein.

Sobald die Vorschau die Verarbeitung abgeschlossen hat, klicken Sie auf das Dokument, um Ihre PC in der Dokumentvorschau anzuzeigen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/02-uploading-pc-data.png)

### 1.2 **PC-Revisionen freigegeben**

Wenn [Revisionspublikation](https://support.catenda.com/en/articles/9874698-revision-publishing-iso-19650) für das Projekt aktiviert wurde, wurde die Punktwolke als freigegebene Revision hochgeladen. Freigegebene PC-Revisionen können nur im Dokumentenbereich in der Vorschau angezeigt werden. Um Ihre PC im 3D Viewer laden zu können, muss die Revision veröffentlicht werden. Individuelle freigegebene Revisionen können mit der Veröffentlichungsaktion im rechten Menü der Dokumentvorschau veröffentlicht werden. Mehrere freigegebene Revisionen können mit der Aktion "Ausgewählte Elemente" in der Dokumentstruktur veröffentlicht werden. Wenn Sie eine Revision veröffentlichen, wird die Vorschau für die veröffentlichte Revision mit der Verarbeitung beginnen.

### 1.3 **Veröffentlichte PC-Revisionen**

Nach der Verarbeitung der Vorschau einer veröffentlichten PC-Revision wird eine 3D-Schaltfläche in der Viewer-Spalte der Dokumententabelle angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/03-br-published-pc-revisions.png)

Die 3D-Schaltfläche lädt die neueste veröffentlichte Revision des Dokuments im 3D Viewer.

Wenn Sie ein oder mehrere Dokumente mit 3D-Dokumenten wie PC-, IFC- oder GML-Dokumenten ausgewählt haben, wird die Aktion "3D-Dokumente" auch im Menü "Ausgewählte Element-Aktion" in der Dokumententabelle angezeigt. Auf diese Weise können Sie die neuesten Revisionen mehrerer 3D-Dokumente gleichzeitig im 3D Viewer laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/04-br-published-pc-revisions.png)

In einem Dokument mit mindestens einer veröffentlichten PC-Revision, die die Verarbeitung abgeschlossen hat, können Sie die 3D-Aktion im Aktionsmenü oben rechts sehen.

> **Hinweis:** Die 3D-Aktion lädt die neueste veröffentlichte Revision des Dokuments im 3D Viewer. Auch wenn Sie sich eine frühere Revision ansehen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/05-br-published-pc-revisions.png)

## 2. **3D Viewer Vorschau**

Nach dem Klicken auf die 3D-Schaltfläche beginnen die PC-Punkte, in den 3D Viewer zu laden. Die 3D-Ansicht eines PC kann so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/06-3d-viewer-preview.png)

Oben im 3D Viewer ist ein grüner Ladebalken zu sehen. Dieser Ladebalken zeigt an, wie viele Punkte für die aktuelle Kameraposition und den Blickwinkel in den 3D Viewer geladen wurden. Der Ladebalken kann sich ändern, wenn Sie sich umdrehen, da Punkte aus der Ansicht verschwinden und entladen werden oder weitere Punkte in den Bereich gelangen und mit dem Laden beginnen.

Und nach einigen Anpassungen von Zoom und Positionierung kann die PC-Vorschau so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/07-3d-viewer-preview.png)

## 3. **3D Viewer Einstellungen**

In diesem Abschnitt betrachten wir die Einstellungen in Catenda Hub, die Sie die beste Erfahrung mit Ihrer PC machen lassen.

> **Hinweis:** Bevor Sie den 3D Viewer konfigurieren, stellen Sie sicher, dass die Anwendung, in der Catenda geöffnet ist, [wie empfohlen] konfiguriert ist (https://support.catenda.com/en/articles/6921941-hardware-recommendation).

Einstellungen, die zum Konfigurieren von Punktwolken verwendet werden können, befinden sich an zwei Stellen.

### 3.1 **1. Punktbudget:**

Das Punktbudget kann in den [3D Viewer Einstellungen](https://support.catenda.com/en/articles/5784718-3d-viewer-settings) konfiguriert werden, die sich im Zahnradsymbol oben rechts des 3D Viewers befinden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/08-1-point-budget.png)

Im 3D Viewer Einstellungsmenü kann das Punktbudget von 100.000 auf 10.000.000 eingestellt werden. Das Laden von mehr Punkten kann mehr Zeit in Anspruch nehmen und kann mehr Ressourcen aus Ihrem System beanspruchen. Durch Laden von mehr Punkten kann die Punktwolke mit höherer Treue angezeigt werden. Siehe die gleiche Ansicht mit: 100.000 Punkte

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/09-1-point-budget.png)

1.000.000 Punkte

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/10-1-point-budget.png)

10.000.000 Punkte

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/11-1-point-budget.png)

### 3.2 **2. Revisionsauswahl und individuelle PC-Einstellungen:**

Oben links im 3D Viewer finden Sie den [Revisionsauswahl](https://support.catenda.com/en/articles/4670246-accepting-an-invitation-to-join-a-project).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/12-2-revision-selector-and-individual-pc-settings.png)

Im [Modellmenü](https://support.catenda.com/en/articles/4670279-revision-selector#h_180a64490d) können Sie die einzelnen [3D-Dokumente](https://support.catenda.com/en/articles/4670279-revision-selector#h_fce60074ef) finden, die Sie in den 3D Viewer geladen haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/13-2-revision-selector-and-individual-pc-settings.png)

Punktwolken können in der Revisionsauswahl konfiguriert werden, indem Sie auf das Zahnradsymbol klicken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/14-2-revision-selector-and-individual-pc-settings.png)

Das Einstellungsmenü kann so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/15-2-revision-selector-and-individual-pc-settings.png)

_Attribut_ _RGBA_ - Standard PC-Punkte mit ihren Farben anzeigen

_Attribut Intensität_ Die Intensitätsoption kann verwendet werden, wenn die Punkte keine Farben enthalten. Zum Beispiel, wenn die Punktwolke in einem Tunnel oder einem dunklen Raum erfasst wurde.

**Deckkraft** Wenn Modelle zusammen mit Punktwolken angezeigt werden, kann es notwendig sein, die Punkte zu dämpfen, um eine bessere Ansicht des Blickwinkels zu erhalten.

_Punktgröße_ _Adaptiv_ - Standard Je näher ein Punkt zur Kamera ist, desto größer ist er. Punkte, die in Sicht sind, werden in den Speicher geladen. Punkte, die aus der Ansicht verschwinden, werden aus dem Speicher entladen.

> **Hinweis:** Stellen Sie sicher, dass die Hardware und die Software, auf der Catenda geöffnet ist, [wie empfohlen](https://support.catenda.com/en/articles/6921941-hardware-recommendation) konfiguriert sind, da dies die Art der Punktgrößenladung beeinflussen kann, die Ihr Gerät verarbeiten kann.

**Punktgröße Feste Größe** Punkte, die geladen wurden, bleiben mit dieser Option im Speicher. Bei vielen Punkten werden Sie bemerken, dass die Drehung verzögert werden kann und die Bewegung verlangsamt werden kann, wenn Sie sich der Menge an Punkten nähern, die Ihr System verarbeiten kann. Sie werden auch bemerken, dass das Laden von neuen Punkten immer länger dauert, wenn Sie sich dem Limit Ihres Geräts nähern. Punkte werden zuerst der Kamera am nächsten geladen. Bevor Sie die Punktwolke aus dem Dokumentenbereich laden, stellen Sie sicher, dass Sie die Kamera an der Stelle positionieren, an der die Punkte geladen werden sollen. Wenn dies eine Kameraposition ist, die Sie häufiger mit dieser Punktwolke verwenden möchten, erwägen Sie, ein Lesezeichen oder einen Schnappschuss in einem Thema zu erstellen, das Sie abspielen können, um zu dieser Position zurückzukehren.

**Punktdichteschieberegler** Der Dichteschieberegler hilft Ihnen, die endgültige Einstellung vorzunehmen. Es gibt keine Regel für den korrekten Wert. Sie hängt von den Daten ab, die Sie hochladen (Größe des Datensatzes, Punktdichte, Scan-Typ usw.). Unser Rat: Laden Sie die Punktwolke, und warten Sie einen Moment, bis genügend Punkte angezeigt werden, passen Sie dann die Einstellungen bei Bedarf an.

[YouTube-Video](https://www.youtube.com/embed/n9pztkRPxoc?rel=0)
