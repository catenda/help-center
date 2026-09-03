# Revisionsverifizierung via QR-Code auf PDFs

Drucken Sie Dokumentrevisionen mit generierten QR-Codes auf Papier, damit Projektmitglieder überprüfen können, ob das Papier, das sie in den Händen halten, noch aktuell ist.

Konfigurierte Ordner können anhand des Zahnradsymbols auf dem [Ordnersymbol](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page#h_6af15c36b3) identifiziert werden. So kann eine Revision mit einem generierten QR-Code aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/01-intro.png)

## 1. **Ordnerkonfiguration**

QR-Code-Stempelung kann [für konfigurierte Ordner](https://support.catenda.com/en/articles/7831371-document-settings#h_166a269870) auf der Dokumentenseite aktiviert werden. _Erforderlicher Zugriff:_ Administrator

In konfigurierten Ordnern werden neue PDF-Revisionen in hochgeladenen Dokumenten verarbeitet. Catenda scannt das Dokument nach dem unten angegebenen QR-Code-Platzhalter. Wenn der Platzhalter erfolgreich erkannt wird, wird ein QR-Code für die Revision generiert. _Erforderlicher Zugriff:_ Schreibzugriff auf das Dokument

### 1.1 **QR-Code zuweisen**

Um QR-Code-Stempelung einem Ordner zuzuweisen, gehen Sie zu [Dokumenteinstellungen](https://support.catenda.com/en/articles/7831371-document-settings), die Sie auf der [Dokumentenseite](https://support.catenda.com/en/articles/8204673-documents-page) finden. Erweitern Sie in den Dokumenteinstellungen das [Ordnerkonfigurationsmenü](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90). So kann das Ordnerkonfigurationsmenü aussehen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/02-assign-qr-code.png)

Am unteren Ende befindet sich das Dropdown-Menü "QR-Code zuweisen". Klicken Sie auf das Dropdown-Menü und wählen Sie "Ja", um diesen Ordner zu konfigurieren.

**Konfigurationsvererbung** Wenn eine Konfiguration in einem übergeordneten Ordner festgelegt wurde, erben alle untergeordneten Ordner diese Konfiguration.

## 2. **QR-Code-Platzhalterplatzierung**

Wie in der Einleitung dieses Artikels erwähnt, sucht Catenda nach dem QR-Code-Platzhalterbild, um einen QR-Code auf einer in einen konfigurierten Ordner hochgeladenen Revision zu generieren. Das QR-Code-Platzhalterbild kann etwa so aussehen:

<p class="intercom-align-center no-margin">[<img alt="Catenda QR-Code placeholder" src="https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/inline-8c4db2f4912c.png" width="150"/>](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)</p>

Klicken Sie [hier](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk), um den QR-Code-Platzhalter herunterzuladen

> **Warnung:** Kopieren/Einfügen oder Speichern Sie dieses Bild nicht. Das Bild sieht auf der Zeichnung möglicherweise gleich aus, wird aber nicht erkannt.

Klicken Sie [hier](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda), um mehr darüber zu erfahren, wie Sie den Platzhalter auf einem PDF platzieren. So kann der Platzhalter aussehen, wenn er in einem Titelblock einer Zeichnung platziert wird:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/03-qr-code-placeholder-placement.png)

## 3. **Hochladen einer Revision mit einem Platzhalter**

Laden Sie eine neue Revision eines PDFs mit dem Platzhalter in einen Ordner mit QR-Code-Zuweisung hoch. Dies gilt nur für veröffentlichte Revisionen!!! Entwürfe oder gemeinsam genutzte PDFs erhalten einen QR-Code erst nach der Veröffentlichung.

### 3.1 **Revisions-QR-Code-Generierung**

Nachdem der QR-Code-Platzhalter platziert wurde, kann das PDF als neue Revision in den konfigurierten Ordner hochgeladen werden. Während des Hochladens verarbeitet Catenda die Bilder im Dokument.

**Byte-Anforderung** Die korrekten Bytes, die zu den schwarzen und weißen Pixeln im Catenda-QR-Code-Platzhalter gehören, müssen in der richtigen Reihenfolge vorhanden sein.

**Dimensionsanforderung** Das Bild muss eine Mindestbreite und -höhe von 2 cm x 2 cm haben.

**Beispiel für generierten QR-Code** So kann der Titelblock im obigen Beispiel aussehen, nachdem das PDF verarbeitet und ein QR-Code hinzugefügt wurde:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/04-revision-qr-code-generation.png)

## 4. **Status-Workflow -** Veröffentlichung zur QR-Code-Generierung

Ohne den Status-Workflow werden alle hochgeladenen Revisionen sofort veröffentlicht. Dokumente werden nur auf QR-Code-Platzhalter gescannt, wenn sie veröffentlicht werden.

### 4.1 **Gemeinsam genutzte Revisionen vs. veröffentlichte Revisionen**

Bei aktiviertem Status-Workflow werden neue Revisionen als gemeinsam genutzte Revisionen als Schritt vor der Veröffentlichung hochgeladen. Wenn Sie sich die gemeinsam genutzte Revision ansehen, können Sie das Originaldokument sehen, bevor Catenda es mit einem generierten QR-Code geändert hat. Beim Status-Workflow findet der Austausch des QR-Code-Platzhalters durch den generierten QR-Code statt, wenn eine gemeinsam genutzte Revision in einem konfigurierten Ordner, der den QR-Code-Platzhalter hat, veröffentlicht wird.
