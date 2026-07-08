# QR-Code auf PDFs in Catenda

QR-Codes können pro Ordner in der [Ordnerkonfiguration](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) der [Dokumenteinstellungen](https://support.catenda.com/en/articles/7831371-document-settings) konfiguriert werden.

Diese Funktion bietet Catenda-Benutzern die Möglichkeit zu überprüfen, ob das von ihnen verwendete Dokument die neueste Version ist, indem sie den auf dem PDF gedruckten QR-Code scannen.

## 1. **QR-Code auf Catenda Hub einrichten**

Die QR-Code-Zuweisung erfolgt über Ordner, was bedeutet, dass jeder Projektadministrator entscheiden kann, welche Ordner diese Funktion haben sollen.

Dies sind die Schritte, um die QR-Code-Funktion den Ordnern in Ihrem Projekt zuzuweisen:

1. Gehen Sie unter Dokumente —> Einstellungen zu **"Ordnerkonfiguration"**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/01-setup-qr-code-on-catenda-hub.png)

2\. Klicken Sie auf das Pluszeichen neben dem gewünschten Ordner, um die Ordnerkonfiguration zu öffnen, und wählen Sie unter "QR-Code zuweisen" die Option **"Ja"**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/02-setup-qr-code-on-catenda-hub.png)

Das Scannen von Platzhaltern und die Platzierung von QR-Codes erfolgt nur in Ordnern mit QR-Code-Zuweisung;

> **Hinweis:** Wenn einem übergeordneten Ordner eine Zuweisung erfolgt ist, haben alle Unterordner diese Zuweisung. QR-Codes können jedem Ordner zugewiesen werden, solange einem übergeordneten Ordner noch keine Zuweisung erfolgt ist.

## 2. Platzieren des Platzhalters in Ihrem Dokument

Um diese Funktion nutzen zu können, müssen Sie den von Catenda bereitgestellten **[QR-Code-Platzhalter](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)** auf Ihr Dokument platzieren und dann zu Catenda Hub hochladen. _Größenanforderung:_ Dieser muss eine Mindestgröße von 2 cm x 2 cm haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/03-placing-the-placeholder-in-your-document.png)

Der Download-Link für den QR-Code finden Sie hier:

_[Download-Link](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)_

### 2.1 QR-Code als Dateiautor platzieren

Da Dokumente nach dem Hochladen zu Catenda nicht mehr geändert werden können, ist es wichtig, dass der QR-Code-Platzhalter auf dem Dokument platziert wird, bevor es zu Catenda hochgeladen wird. Der Platzhalter kann auf jeder Ebene außer der Anmerkungsebene platziert werden. Damit Catenda den QR-Code erkennt, muss er als Bild hinzugefügt werden. Das Bild im veröffentlichten Dokument muss genau das gleiche Bild wie das Platzhalterbild sein.

**PDF-Optimierung** Viele Programme führen Optimierungsschritte für bessere Anzeige und Reduzierung der Dateigröße durch. Diese Schritte können die Anzahl der Bytes im Bild ändern, wodurch Catenda es nicht mehr erkennt. Hier sind einige Informationen zum Platzhalter, die bei der Optimierung hilfreich sein können. Pixeldichte: 144 dpi Bildkomprimierung: ZIP Das Bild muss ein einziges Bild sein. Einige Optimierer könnten das Bild als Optimierung aufteilen. Stellen Sie bitte sicher, dass das Bild nach der Optimierung intakt ist.

_Archicad_ Bitte verwenden Sie beim Platzieren des QR-Codes Folgendes: Import > Interoperabilität > Aus Datei zusammenführen > Arbeitsblatt importieren und öffnen > Drag and Drop. Wenn Sie das Arbeitsblatt öffnen und die PNG per Drag and Drop verschieben, wird die Auflösung geändert und es funktioniert nicht.

### 2.2 QR-Code in einem vorhandenen Dokument platzieren

Wenn Sie ein Dokument haben, das Sie nicht erstellt haben, und Sie den QR-Platzhalter vor dem Hochladen zu Catenda Hub hinzufügen möchten, stellen Sie bitte sicher, dass Sie das Dokument bearbeiten und den QR-Platzhalter als Bild hinzufügen.

### 2.3 QR-Code in einem Catenda-Dokument platzieren

Wenn sich Ihr Dokument bereits auf Catenda befindet, müssen Sie den QR-Platzhalter hinzufügen und eine neue Version hochladen. Wenn Sie keinen Zugriff auf ein PDF-Bearbeitungsprogramm haben, können Sie das [Bildstempel-Anmerkungstool](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6) verwenden, um den QR-Platzhalter zu Ihrem Dokument hinzuzufügen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/04-placing-the-qr-code-a-catenda-document.png)

Um das Dokument zu speichern, damit der QR-Platzhalter erkannt wird, drucken Sie das Dokument mit [der Druckschaltfläche](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70), die sich oben links in Ihrer Dokumentvorschau befindet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/05-placing-the-qr-code-a-catenda-document.png)

Dies öffnet den Druckdialog Ihres Browsers. So kann das für Google Chrome aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/06-placing-the-qr-code-a-catenda-document.png)

Drucken Sie das Dokument im Druckdialog als PDF.

> **Hinweis 1:** Der QR-Code wird nur auf der Inhaltsebene angezeigt, wenn Sie das Dokument drucken. Wenn Sie das Dokument herunterladen, befindet es sich auf der Anmerkungsebene. **Hinweis 2:** Durch das Drucken als PDF rastern Sie den Inhalt des Dokuments. Dies bedeutet, dass der Text bei der Hochladung als Version zu Catenda nicht durchsuchbar ist.

Das gedruckte PDF mit dem Platzhalter kann nun als neue Version zu Catenda hochgeladen werden. Um Ihren Versionsverlauf sauber zu halten, möchten Sie möglicherweise die vorherige Version ohne QR-Code zurückziehen.

## 3. **Veröffentlichung mit QR-Codes**

1. Laden Sie eine neue Version eines PDFs mit dem Platzhalter in einen Ordner mit QR-Code-Zuweisung hoch
2. Während der Veröffentlichung wird das PDF auf den Platzhalter gescannt und durch einen QR-Code ersetzt (generiert für diese Version)
3. Der neu generierte QR-Code wird Teil des PDFs und kann auf Catenda Hub angezeigt/gescannt und/oder heruntergeladen werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/07-publishing-with-qr-codes.png)

Hier ist ein Beispiel für die Platzierung des QR-Code-Platzhalters und die Ergebnisse nach dem Hochladen zu Catenda Hub. 1\. Platzhalter im Titelblock einer Zeichnung. **Zum Hochladen bereit.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/08-publishing-with-qr-codes.png)

2\. Der Platzhalter im Titelblock wird durch den generierten QR-Code ersetzt. **Zur Überprüfung bereit.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/09-publishing-with-qr-codes.png)

### 3.1 **Dokumentenhistorie**

Nach dem Hochladen eines Dokuments mit einem QR-Code-Platzhalter können Sie in der Dokumentenhistorie des [rechten Informationsmenüs](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision) sehen, dass es erfolgreich verarbeitet wurde.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/10-document-history.png)

Wenn die Generierung Ihres QR-Codes fehlgeschlagen ist, kann dies daran liegen, dass Ihr QR-Code kleiner als 2 cm x 2 cm war oder als Anmerkung statt als Bild platziert wurde.

**Abflachen von Anmerkungen** Einige Softwareprogramme ermöglichen es Ihnen, Anmerkungen abzuflachen, was die Verarbeitung des Platzhalters ermöglicht. Hier sind einige Beispiele:

**PDF X-Change**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/11-document-history.png)

**Adobe Acrobat**

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3d7d02c461d3.png" width="300"/> --> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3398dc9eef22.png" width="300"/>

_BlueBeam Revu_ Wenn Sie den Platzhalter in BlueBeam Revu platzieren und das Dokument speichern, wird er als Anmerkung hinzugefügt. Es ist möglich, den QR-Code abzuflachen, um ihn Teil der Inhaltsebene des Dokuments zu machen. Aber auch wenn Sie ihn normal speichern oder die Option für reduzierte Dateigröße verwenden, wird der QR-Code geändert und funktioniert nicht mit Catenda. Um den QR-Code mit Catenda zum Funktionieren zu bringen, drucken Sie stattdessen das Dokument mit dem BlueBeam-Treiber:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/12-document-history.png)

Wählen Sie im Speichern unter-Dialog die Option ZIP-Grafiken und aktivieren Sie die Nachbearbeitung. Dies liegt daran, dass der Komprimierungsalgorithmus für den Platzhalter ZIP ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/13-document-history.png)

Wählen Sie im Menü der Nachbearbeitung die Option Angrenzende Bilder kombinieren. Dies ist der Fall, weil das Bild normalerweise in zwei Teile aufgeteilt wird, damit es wieder zusammengefügt wird. Wenn Ihre Seitengröße nicht als Standardoption vorhanden ist, können Sie hier Ihre eigene benutzerdefinierte Größe hinzufügen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/14-document-history.png)
