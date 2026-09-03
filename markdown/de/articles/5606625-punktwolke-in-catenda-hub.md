# Punktwolken in Catenda Hub

> Entdecken Sie, wie Sie von Laserscans und LIDAR-Technologien in Catenda Hub profitieren.

> **Hinweis:** Laden Sie eine Beispieldatei von [hier](https://drive.google.com/file/d/1G8U916oihDl5qHrTfQaVHxDeLsbq1ulG/view?usp=sharing) herunter.

Punktwolkendatensätze (PC) können in Catenda Hub visualisiert werden. Einzelne PC können im Dokumentbereich in der Vorschau angezeigt werden. Mehrere PC können in den [3D-Viewer](https://support.catenda.com/en/articles/8227211-3d-viewer) geladen werden. Im 3D-Viewer können PC zusammen mit anderen 3D-Dokumentformaten wie IFC-Modellen und GML-Dateien angezeigt werden.

Nachfolgend finden Sie verschiedene Einstellungen zur Anzeige Ihrer Daten:

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="padding: 8px;"><p>Adaptiv - Dünn - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-05a450dc777f.png" style="height: auto;" width="3839"/></div></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>Adaptiv - Dicht - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-196a1135014a.png" style="height: auto;" width="3839"/></div></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Fest - Dicht - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-66e21551bbef.png" style="height: auto;" width="3834"/></div></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Fest - Dünn - Intensität</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-4a2046c8eaf1.png" style="height: auto;" width="3839"/></div></td></tr></tbody></table></div>

## 1. **Dokumentbereichsvorschau**

PC-Daten der folgenden zwei Dateiformate können auf Catenda in der Vorschau angezeigt werden.

- `*.e57`
- `*.las`

PC kann wie jedes andere Dokument im Dokumentbereich hochgeladen werden. Für diese beiden Dateiformate können Dateien bis zu 25 GB in den Dokumentbereich hochgeladen werden. Mehrere Dateien können im Dokumentbereich geladen und zusammen im 3D-Viewer angezeigt werden.

### 1.1 **Hochladen von PC-Daten**

Es wird empfohlen, den [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) zu verwenden oder Ihre PC-Datei in einen gezippten Ordner zu komprimieren und den [zip-Import](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) zum Hochladen Ihrer PC zu verwenden. Diese Methoden sparen Ihnen Zeit, da die Uploaddateigröße kleiner wird und das Risiko eines Netzwerkfehlers minimiert wird, da die Datei schneller hochgeladen wird

Nachdem Sie eine PC in den Dokumentbereich hochgeladen haben, wird die Dokumentvorschau verarbeitet. Während die Vorschau verarbeitet wird, sehen Sie einen grauen Balken am oberen Rand Ihrer Dokumentvorschau.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/01-uploading-pc-data.png)

Die Verarbeitungsdauer der Vorschau hängt von der Größe der PC ab. Die Verarbeitung dauert 1 Stunde pro GB, kann aber je nach Punktwolke mehr oder weniger dauern.

Nachdem die Vorschau verarbeitet wurde, klicken Sie auf das Dokument, um Ihre PC in der Dokumentvorschau anzuzeigen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/02-uploading-pc-data.png)

### 1.2 **Gemeinsame PC-Revisionen**

Wenn die [Revisionsveröffentlichung](https://support.catenda.com/en/articles/9874698-revision-publishing-iso-19650) für das Projekt aktiviert wurde, wurde die Punktwolke als gemeinsame revision hochgeladen. Gemeinsame PC-Revisionen können nur im Dokumentbereich in der Vorschau angezeigt werden. Um Ihre PC im 3D-Viewer laden zu können, muss die revision veröffentlicht werden. Einzelne gemeinsame Revisionen können mit der Veröffentlichungsaktion im rechten Menü der Dokumentvorschau veröffentlicht werden. Mehrere gemeinsame Revisionen können mit der Aktion "Ausgewählte Elemente" in der Dokumentstruktur veröffentlicht werden. Wenn Sie eine revision veröffentlichen, wird die Vorschau für die veröffentlichte revision verarbeitet.

### 1.3 **Veröffentlichte PC-Überarbeitungen**

Nach der Verarbeitung der Vorschau einer veröffentlichten PC-Überarbeitung wird eine 3D-Schaltfläche in der Viewer-Spalte der Dokumenttabelle angezeigt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/03-br-published-pc-revisions.png)

Die 3D-Schaltfläche lädt die neueste veröffentlichte Überarbeitung des Dokuments in den 3D-Viewer.

Wenn Sie ein oder mehrere Dokumente mit 3D-Dokumenten wie PC-, IFC- oder GML-Dokumenten ausgewählt haben, wird auch die 3D-Dokumentaktion im Aktionsmenü für ausgewählte Elemente in der Dokumenttabelle angezeigt. Auf diese Weise können Sie die neuesten Überarbeitungen mehrerer 3D-Dokumente auf einmal in den 3D-Viewer laden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/04-br-published-pc-revisions.png)

In einem Dokument mit mindestens einer veröffentlichten PC-Überarbeitung, deren Verarbeitung beendet ist, können Sie die 3D-Aktion im Aktionsmenü oben rechts sehen.

> **Hinweis:** Die 3D-Aktion lädt die neueste veröffentlichte Überarbeitung des Dokuments in den 3D-Viewer. Auch wenn Sie eine frühere Überarbeitung anzeigen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/05-br-published-pc-revisions.png)

## 2. **3D-Viewer-Vorschau**

Nach dem Klicken auf die 3D-Schaltfläche werden die PC-Punkte in den 3D-Viewer geladen. Die 3D-Ansicht einer PC kann etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/06-3d-viewer-preview.png)

Oben im 3D-Viewer ist eine grüne Ladebalken zu sehen. Diese Ladebalken zeigt an, wie viele Punkte für die aktuelle Kameraposition und den aktuellen Winkel in den 3D-Viewer geladen wurden. Die Ladebalken kann sich ändern, wenn Sie sich umdrehen, da Punkte aus der Ansicht verschwinden und entladen oder mehr Punkte in den Bereich gelangen und geladen werden.

Nach einigen Anpassungen mit Zoom und Positionierung kann die PC-Vorschau etwa so aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/07-3d-viewer-preview.png)

## 3. **3D-Viewer-Einstellungen**

In diesem Abschnitt werden die Einstellungen in Catenda Hub beschrieben, mit denen Sie die beste Erfahrung mit Ihrer PC erhalten.

> **Hinweis:** Bevor Sie den 3D-Viewer konfigurieren, stellen Sie bitte sicher, dass die Anwendung Catenda auf der Anwendung [wie empfohlen](https://support.catenda.com/en/articles/6921941-hardware-recommendation) konfiguriert ist.

Einstellungen, die zum Konfigurieren von Punktwolken verwendet werden können, befinden sich an zwei Orten.

### 3.1 **1. Punktbudget:**

Das Punktbudget kann in den [3D-Viewer-Einstellungen](https://support.catenda.com/en/articles/5784718-3d-viewer-settings) konfiguriert werden, die sich in dem Zahnradsymbol oben rechts des 3D-Viewers befinden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/08-1-point-budget.png)

Im 3D-Viewer-Einstellungsmenü kann das Punktbudget von 100.000 bis 10.000.000 angepasst werden. Das Laden von mehr Punkten kann mehr Zeit in Anspruch nehmen und mehr Ressourcen von Ihrem System erfordern. Durch das Laden von mehr Punkten kann die Punktwolke mit höherer Genauigkeit angezeigt werden. Siehe dieselbe Ansicht mit: 100.000 Punkte

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/09-1-point-budget.png)

1.000.000 Punkte

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/10-1-point-budget.png)

10.000.000 Punkte

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/11-1-point-budget.png)

### 3.2 **2. Überarbeitungsauswahl und individuelle PC-Einstellungen:**

Oben links im 3D-Viewer finden Sie die [Überarbeitungsauswahl](https://support.catenda.com/en/articles/4670246-accepting-an-invitation-to-join-a-project).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/12-2-revision-selector-and-individual-pc-settings.png)

Im [Modellmenü](https://support.catenda.com/en/articles/4670279-revision-selector#h_180a64490d) können Sie die einzelnen [3D-Dokumente](https://support.catenda.com/en/articles/4670279-revision-selector#h_fce60074ef) finden, die Sie in den 3D-Viewer geladen haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/13-2-revision-selector-and-individual-pc-settings.png)

Punktwolken können in der Überarbeitungsauswahl durch Klicken auf das Zahnradsymbol konfiguriert werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/14-2-revision-selector-and-individual-pc-settings.png)

Dies ist ein Beispiel für das Einstellungsmenü:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/15-2-revision-selector-and-individual-pc-settings.png)

_Attribut_ _RGBA_ - Standard Zeigt PC-Punkte mit ihren Farben an

_Attribut Intensität_ Die Intensitätsoption kann verwendet werden, wenn die Punkte keine Farben enthalten. Beispielsweise wenn die Punktwolke in einem Tunnel oder in einem dunklen Raum erfasst wurde.

**Deckkraft** Wenn Modelle zusammen mit Punktwolken angezeigt werden, kann es notwendig sein, die Punkte zu verdunkeln, um die Ansicht besser zu verstehen.

_Punktgröße_ _Adaptiv_ - Standard Je näher ein Punkt an der Kamera ist, desto größer ist er. Punkte, die in der Ansicht sichtbar sind, werden in den Speicher geladen. Punkte, die aus der Ansicht verschwinden, werden aus dem Speicher entladen.

> **Hinweis:** Stellen Sie sicher, dass die Hardware und Software, auf denen Catenda geöffnet ist, [wie empfohlen](https://support.catenda.com/en/articles/6921941-hardware-recommendation) konfiguriert sind, da dies Auswirkungen auf die Art des Ladens der Punktgröße haben kann, die Ihr Gerät bewältigen kann.

**Punktgröße Feste Größe** Mit dieser Option werden Punkte, die geladen wurden, im Speicher behalten. Bei vielen Punkten werden Sie feststellen, dass die Drehung verzögert werden kann und die Bewegung verlangsamt wird, wenn Sie sich der Anzahl der Punkte nähern, die Ihr System verarbeiten kann. Sie können auch feststellen, dass es immer länger dauert, neue Punkte zu laden, wenn Sie sich dem Limit Ihres Geräts nähern. Punkte werden zuerst am nächsten zur Kamera geladen. Bevor Sie die Punktwolke aus dem Dokumentbereich laden, positionieren Sie die Kamera an der Stelle, an die Sie die Punkte laden möchten. Wenn dies eine Kameraposition ist, die Sie häufiger mit dieser Punktwolke verwenden möchten, erwägen Sie, ein Lesezeichen oder einen Schnappschuss in einem Thema zu erstellen, das Sie abspielen können, um zu dieser Position zurückzukehren.

**Punkt-Dichte-Schieberegler** Der Dichte-Schieberegler hilft Ihnen, die endgültige Einstellung vorzunehmen. Es gibt keine Regel für den korrekten Wert, er hängt von den Daten ab, die Sie hochladen (Größe des Datensatzes, Punktdichte, Art der Überprüfung usw.). Unser Rat: Laden Sie die Punktwolke und warten Sie einen Moment. Wenn genügend Punkte angezeigt werden, passen Sie die Einstellungen bei Bedarf an.

[YouTube-Video](https://www.youtube.com/embed/n9pztkRPxoc?rel=0)
