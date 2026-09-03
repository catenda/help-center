# QR-Code auf PDFs in Catenda

QR-Codes können pro Ordner in der [Ordnerkonfiguration](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) der [Dokumenteinstellungen](https://support.catenda.com/en/articles/7831371-document-settings) konfiguriert werden.

Diese Funktion bietet Catenda-Benutzern die Möglichkeit zu überprüfen, ob es sich bei dem verwendeten Dokument um die neueste Version handelt, indem der auf dem PDF gedruckte QR-Code gescannt wird.

## 1. **QR-Code auf Catenda Hub einrichten**

Die QR-Code-Zuordnung erfolgt über Ordner, d. h. jeder Projektadministrator kann entscheiden, auf welchen ausgewählten Ordnern diese Funktion aktiviert sein soll.

Dies sind die Schritte zur Zuordnung der QR-Code-Funktion zu Ordnern in Ihrem Projekt;

1. Gehen Sie unter Dokument —> Einstellungen zu **"Ordnerkonfiguration"**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/01-setup-qr-code-on-catenda-hub.png)

2\. Klicken Sie auf das Pluszeichen neben Ihrem gewünschten Ordner, um die Ordnerkonfiguration zu öffnen, und sagen Sie unter "QR-Code zuordnen" **"Ja"**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/02-setup-qr-code-on-catenda-hub.png)

Das Scannen von Platzhaltern und die Platzierung von QR-Codes erfolgt nur in Ordnern mit QR-Code-Zuordnung;

> **Hinweis:** Sobald ein übergeordneter Ordner zugewiesen ist, wird diese Zuordnung auf alle Unterordner übertragen. QR-Codes können einem beliebigen Ordner zugewiesen werden, solange kein übergeordneter Ordner bereits zugewiesen wurde.

## 2. Platzierung des Platzhalters in Ihrem Dokument

Um diese Funktion zu nutzen, müssen Sie den von Catenda bereitgestellten **[QR-Code-Platzhalter](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)** auf Ihrem Dokument platzieren und dann auf Catenda Hub hochladen. _Größenanforderung:_ Dies muss eine Mindestgröße von 2 cm x 2 cm haben.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/03-placing-the-placeholder-in-your-document.png)

Der Download-Link für den QR-Code finden Sie hier:

_[Download-Link](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)_

### 2.1 Platzierung des QR-Codes als Dateiverfasser

Da Dokumente nach dem Hochladen auf Catenda nicht mehr geändert werden können, ist es wichtig, dass der QR-Code-Platzhalter vor dem Hochladen auf Catenda auf dem Dokument platziert wird. Der Platzhalter kann auf jeder Ebene außer der Anmerkungsebene platziert werden. Damit Catenda den QR-Code erkennt, muss er als Bild hinzugefügt werden. Das Bild im veröffentlichten Dokument muss identisch mit dem Platzholter-Bild sein.

**PDF-Optimierung** Viele Programme führen Optimierungsschritte durch, um die Anzeige zu verbessern und die Dateigröße zu reduzieren. Diese Schritte können die Anzahl der Bytes im Bild ändern, wodurch Catenda es nicht mehr erkennt. Hier finden Sie einige Informationen über den Platzhalter, die bei der Optimierung hilfreich sein können. Pixeldichte: 144 dpi Bildkomprimierung: ZIP Das Bild muss ein einzelnes Ganzes sein. Einige Optimierer könnten das Bild als Optimierungsmaßnahme aufteilen. Bitte stellen Sie sicher, dass das Bild nach der Optimierung intakt ist.

_Archicad_ Bitte verwenden Sie beim Platzieren des QR-Codes: Import > Interoperabilität > Aus Datei zusammenführen > Arbeitsblatt importieren und öffnen > Ziehen und ablegen. Wenn Sie das Arbeitsblatt öffnen und die PNG per Ziehen und Ablegen hinzufügen, ändert sich die Auflösung und es funktioniert nicht.

### 2.2 Platzierung des QR-Codes auf einem vorhandenen Dokument

Wenn Sie ein Dokument haben, das Sie nicht erstellt haben, und Sie den QR-Platzhalter vor dem Hochladen auf Catenda Hub hinzufügen möchten, stellen Sie sicher, dass Sie das Dokument bearbeiten und den QR-Platzhalter als Bild hinzufügen.

### 2.3 Platzierung des QR-Codes auf einem Catenda-Dokument

Wenn Ihr Dokument bereits auf Catenda vorhanden ist, müssen Sie den QR-Platzhalter hinzufügen und eine neue Fassung hochladen. Wenn Sie keinen Zugriff auf ein PDF-Bearbeitungsprogramm haben, können Sie das [Werkzeug für die Bildstempelanmerkung](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6) verwenden, um den QR-Platzhalter zu Ihrem Dokument hinzuzufügen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/04-placing-the-qr-code-a-catenda-document.png)

Um das Dokument zu speichern, damit der QR-Platzhalter erkannt wird, drucken Sie das Dokument mit [der Schaltfläche "Drucken"](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70), die sich oben links in der Dokumentvorschau befindet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/05-placing-the-qr-code-a-catenda-document.png)

Dadurch wird das Druckdialogfeld Ihres Browsers geöffnet. So kann es für Google Chrome aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/06-placing-the-qr-code-a-catenda-document.png)

Drucken Sie das Dokument im Druckdialogfeld als PDF.

> **Hinweis 1:** Der QR-Code wird nur auf der Inhaltsebene angezeigt, wenn Sie das Dokument drucken. Wenn Sie das Dokument herunterladen, befindet es sich auf der Anmerkungsebene. **Hinweis 2:** Durch das Drucken als PDF rastern Sie den Inhalt des Dokuments. Dies bedeutet, dass der Text nicht durchsuchbar ist, wenn Sie ihn als neue Fassung auf Catenda hochladen.

Das gedruckte PDF mit dem Platzhalter kann nun als neue Fassung auf Catenda hochgeladen werden. Um die Fassungshistorie übersichtlich zu halten, können Sie die vorherige Fassung ohne QR-Code zurückziehen.

## 3. **Veröffentlichung mit QR-Codes**

1. Laden Sie eine neue Fassung eines PDFs mit dem Platzhalter in einen Ordner mit QR-Code-Zuordnung hoch
1. Während der Veröffentlichung wird das PDF nach dem Platzhalter gescannt und durch einen QR-Code ersetzt (generiert für diese Fassung)
1. Der neu generierte QR-Code wird Teil des PDFs und kann auf Catenda Hub angezeigt/gescannt und/oder heruntergeladen werden.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/07-publishing-with-qr-codes.png)

Hier ist ein Beispiel für die Platzierung des QR-Code-Platzhalters und das Ergebnis nach dem Hochladen auf Catenda Hub. 1\. Platzhalter im Titelblock einer Zeichnung. **Bereit zum Hochladen.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/08-publishing-with-qr-codes.png)

2\. Platzhalter im Titelblock wird durch den generierten QR-Code ersetzt. **Bereit zur Überprüfung.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/09-publishing-with-qr-codes.png)

### 3.1 **Dokumenthistorie**

Nach dem Hochladen eines Dokuments mit QR-Code-Platzhalter können Sie in der Dokumenthistorie des [Informationsmenüs auf der rechten Seite](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision) sehen, dass es erfolgreich verarbeitet wurde.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/10-document-history.png)

Wenn die Generierung des QR-Codes fehlgeschlagen ist, kann dies daran liegen, dass Ihr QR-Code kleiner als 2 cm x 2 cm war oder als Anmerkung statt als Bild platziert wurde.

**Vereinflachen von Anmerkungen** Einige Software erlaubt es, Anmerkungen zu vereinfachen, was der Platzhalter verarbeitet zu werden. Hier sind einige Beispiele:

**PDF X-Change**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/11-document-history.png)

**Adobe Acrobat**

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3d7d02c461d3.png" width="300"/> --> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3398dc9eef22.png" width="300"/>

_BlueBeam Revu_ Wenn Sie den Platzhalter in BlueBeam Revu platzieren und das Dokument speichern, wird es als Anmerkung hinzugefügt. Es ist möglich, den QR-Code zu vereinfachen, um ihn zum Teil der Inhaltsebene des Dokuments zu machen, aber auch beim normalen Speichern oder mit der Option "Reduzierte Dateigröße" wird der QR-Code geändert und funktioniert nicht mit Catenda. Um den QR-Code mit Catenda funktionieren zu lassen, drucken Sie stattdessen das Dokument mit dem BlueBeam-Treiber:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/12-document-history.png)

Wählen Sie im Dialogfeld "Speichern unter" die ZIP-Grafiken aus und aktivieren Sie die Nachbearbeitung. Dies liegt daran, dass der Komprimierungsalgorithmus für den Platzhalter ZIP ist.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/13-document-history.png)

Wählen Sie im Menü "Nachbearbeitung" die Option "Benachbarte Bilder kombinieren". Dies liegt daran, dass das Bild normalerweise in zwei Teile aufgeteilt wird, sodass es wieder zusammengefügt wird. Wenn Ihre Seitengröße nicht als Standardoption vorhanden ist, können Sie hier eine benutzerdefinierte hinzufügen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/14-document-history.png)
