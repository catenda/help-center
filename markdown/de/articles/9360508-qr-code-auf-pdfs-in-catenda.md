# QR-Code auf PDFs in Catenda

Mit dieser Funktion können Catenda-Benutzer überprüfen, ob das von ihnen verwendete Dokument die neueste Version ist, indem sie den auf dem PDF-Dokument aufgedruckten QR-Code scannen.

Um diese Funktion nutzen zu können, müssen Sie den von Catenda bereitgestellten [QR-Code-Platzhalter](https://drive.google.com/file/d/1SbGcp8hC8l7854HOCZuI8o-WIBMWrsyF/view) auf Ihrem Dokument platzieren und dann in Catenda Hub hochladen. Dieser muss eine Mindestgröße von 2 cm x 2 cm haben.

![](https://downloads.intercomcdn.com/i/o/1129211123/a524f6603d55d5441a6d5d59/image.png?expires=1781092800&signature=95fb63500167c39120dfb7fd11b62718e338734fb7f061d55a7ace248cd5a186&req=dSElH8t%2FnIBdWvMW3nq%2BgUEuK3sH7rFkBhPc1p%2BzxEiSifalxuSnBalL%2FN2Y%0AZKa6KVb8ggmBPDKRG9TRSVU2geY%3D%0A)

### Setup QR-Code auf Catenda Hub

Die Zuweisung des QR-Codes erfolgt über Ordner, d. h. jeder Projektadministrator kann eine Reihe von Ordnern auswählen, für die diese Funktion gelten soll.

Dies sind die Schritte, um die QR-Code-Funktion den Ordnern in Ihrem Projekt zuzuweisen:

1. Gehen Sie unter Dokument -> Einstellungen auf 'Ordnerkonfiguration'.

![](https://downloads.intercomcdn.com/i/o/1058260520/dddd82c067f7b46accb5b32c/image.png?expires=1781092800&signature=e7941acca8aedcea4e848c67e0007a4e09578fab49b5e5c9a824b181ac99454a&req=dSAiHst4nYRdWfMW3nq%2BgRkR2h4rS0XQNc9lbtEQewqJ6NZ6VLakXmSCbXYB%0AVxWNDann97ZsWaqAzYsRKbOcTVk%3D%0A)

2. Klicken Sie auf das Plus neben dem gewünschten Ordner, um die Ordnerkonfiguration zu öffnen, und sagen Sie unter "QR-Code zuweisen" "Ja".

![](https://downloads.intercomcdn.com/i/o/1058261375/a52f5da19606885304d919f1/image.png?expires=1781092800&signature=4c64a3d24c6c5463ebe93bbe1059a2dbb1bb4338b4ad72cfa53803d88d531b46&req=dSAiHst4nIJYXPMW3nq%2BgSrY7yhARKJj3Bos80hgsCYYWj1IyWqj837ROIDg%0ADGVbmygamuvFA2FrHAL5c1SXMPw%3D%0A)

Das Scannen von Platzhaltern und Platzieren von QR-Codes erfolgt nur auf Ordnern mit QR-Code-Zuordnung:

> **Note:** Tipp: Sobald ein übergeordneter Ordner zugewiesen ist, haben alle Unterordner diese Zuweisung QR-Codes können jedem Ordner zugewiesen werden, sofern nicht bereits ein übergeordneter Ordner zugewiesen wurde.

### Veröffentlichen mit QR Codes

1. Hochladen einer neuen Revision eines PDFs mit dem Platzhalter in einen Ordner mit QR-Code-Zuweisung
1. Während der Veröffentlichung wird das PDF nach dem Platzhalter gescannt und durch einen QR-Code (der für diese Revision generiert wurde) ersetzt
1. Der neu generierte QR-Code wird Teil des PDFs, das auf Catenda Hub angezeigt/gescannt und/oder heruntergeladen werden kann.

![](https://downloads.intercomcdn.com/i/o/1058270845/bbf3025f7cf4ce2c44e5ff3a/image.png?expires=1781092800&signature=87316e36cd478d482c98ab3fde729320404c1178d31708e40ca8cb797844e67a&req=dSAiHst5nYlbXPMW3nq%2BgcetveFGeYCsO6kaiNDTAeDsrR86FZzvPBsliNcU%0AoJizxECcx70jjX9lsLKDjBubHOo%3D%0A)

Hier ist ein Beispiel für die Platzierung des QR-Code-Platzhalters und das Ergebnis nach dem Hochladen in Catenda Hub.

1. Platzhalter im Schriftfeld einer Zeichnung. Bereit zum Hochladen.

![](https://downloads.intercomcdn.com/i/o/1128898386/b042fd79d7595f8d12a0159c/image.png?expires=1781092800&signature=7b305493e3afeef99f797c6bde7577f9ee147be9259ffd5234d136ceb18b19a5&req=dSElHsF3lYJXX%2FMW3nq%2BgcCYNHtVa2O6MpBCTIpzHdyIjlAArQsK42e3eW8C%0ARJ8ENFmJfkyirg6BcnLQ%2FlGVRgM%3D%0A)

2. Der Platzhalter im Plankopf wird durch den dann generierten QR-Code ersetzt. Bereit für die Überprüfung.

![](https://downloads.intercomcdn.com/i/o/1129687828/6fba8f5b78f9f26b6c0e5b25/image.png?expires=1781092800&signature=55a085321bf04009ffc5682bedfb937e1a8a745978110ea5fa2e653c230c60eb&req=dSElH892moldUfMW3nq%2BgZOaMeorej4wNegl5eWFN3XW6bJCLqd8omIpfqDg%0AO6V0qLi3tjmDOiAbb2n%2BOrLzNCo%3D%0A)

### Überprüfung der letzten Revision

Wenn Sie den QR-Code mit Ihrem Smartphone scannen, gelangen Sie auf eine Überprüfungsseite, auf der je nach Version der PDF-Datei die folgenden Ergebnisse angezeigt werden;

1. Ihre Revision ist die neueste Version der PDF-Datei: **Dokument gültig**
1. Ihre Revision ist eine ältere Version der PDF-Datei: **Dokument ungültig**
1. Sie haben einen Platzhalter gescannt: **Sie haben einen Platzhalter gescannt, dieses Dokument ist nicht veröffentlicht**

![](https://downloads.intercomcdn.com/i/o/1128836302/b5ed664002c909cad1388c1c/image.png?expires=1781092800&signature=e32a0bc159c2fe53c0580cf78540908f18b726e36d6e988f6fd07bba7b2f7069&req=dSElHsF9m4JfW%2FMW3nq%2BgRAbWSa0uwekHXdmw0dniPvD%2F48H6GJmWGPMPCrC%0AngeKuBJW%2FPMavpOc%2Btwvf9PFqVY%3D%0A)
