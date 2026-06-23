# Revit IFC Export Manual

Mit diesem IFC-Export-Handbuch soll der Benutzer eine Anleitung zum Export von IFC für die richtigen Zwecke erhalten. Eine IFC-Datei kann schnell groß und schwer werden, wenn Sie viele Informationen aus dem Modell exportieren müssen. Deshalb müssen Sie beim Export einer IFC unnötige Informationen deaktivieren. Beim Hochladen eines Modells zu Catenda ist es nicht immer erforderlich, viele Informationen und ein hohes Detaillierungsniveau im Modell zu haben. Später in diesem Handbuch werden wir auf die Einstellungen zurückgreifen, die wir empfehlen, um das Modell etwas kleiner und etwas einfacher zu handhaben. Hier gehen wir Schritt für Schritt durch den am meisten geeigneten Weg zum Export einer IFC von Revit zu Catenda.

## 1. **Projekteinstellungen**

Bevor Sie exportieren, ist es wichtig, sicherzustellen, dass die GUIDs Ihres Revit-Projekts korrekt sind.

`Verwalten -> Einstellungen -> Projektinformationen -> IFC-Parameter`

![Project information IFC Parameters IfcSite GUID IfcBuilding GUID IfcProject GUID](https://downloads.intercomcdn.com/i/o/975614819/ee92de6f2477949e208dac45/image.png?expires=1779991200&signature=488a733e6dce35b3f9f765548a38ebcbb902309625bfa1827447b3e10ff5d1ca&req=fSciEMh6lYBWFb4V1XW4gW4DZHJ8Y%2FMyB4KsohYxe9JI9upp%2BSOrcthV9MYf%0AU5M5bUP8q8Ck5XUUcK86OtHqKw%3D%3D%0A)

Wenn die GUID anders ist als bei einem vorherigen Export, werden die Objekte neuerer Exporte nicht ordnungsgemäß mit den GUIDs in BCF-Themen verlinkt.

Wenn Sie ein neues Projekt erstellen, erhält es eine eindeutige ID.

## 2. **IFC-Export ändern**

Wenn Revit offen ist und Sie bereit sind zum Exportieren, können Sie folgende Schritte ausführen.

![Oben links auf dem Bildschirm die Datei drücken](https://catenda-as.intercom-attachments-1.com/i/o/271057108/395387d7cf0cc2eb7d9928e9/image-0.png?expires=1779991200&signature=29709f4df2bf2e93a7f49e265c84ad240cb9e1ca9f0d647626ae988df2a5ce2c&req=dicmFsx5nIFXFb4V1XW4gWhxfMNYwk%2FrATxtIQ9WjWxRlpEJI1psfy%2F4XuaV%0ANtKM3bS8PgmX5bN8%2Buoj%2FLUGDQ%3D%3D%0A)

Oben links finden wir die Registerkarte "Datei".

----------------------------------------------------------------

> **Denken Sie daran:**_ Sie möchten möglicherweise einen dedizierten Ordner für Ihre IFCs haben, damit Sie immer die Kontrolle darüber haben, wo sich Ihre Datei befindet!_ Das IFC-Export-Menü finden Sie hier: `Datei -> Exportieren -> IFC` ![](https://downloads.intercomcdn.com/i/o/areracg3/1892251735/1f06f6821d79b19642af1b81ebe6/image.png?expires=1779991200&signature=f77ab31d228b76bdf13529fee00caae4d6d42ccf86705e6e6788b4103ef18ea5&req=dSguFMt7nIZcXPMW3nq%2BgYeYtz5lfambMm12jWodCPeBvHXniyUmgGYciDwf%0AYXW5CLORtPkNnSMKCCj0IG5c3qs%3D%0A) So sieht das Export-IFC-Menü aus: ![Export IFC](https://downloads.intercomcdn.com/i/o/areracg3/1798387143/866e2fe7cec7589a87073fcc0c82/image.png?expires=1779991200&signature=4bfa202fb3004eec5587f9ccff80d9ad260c643ce24349d84a233dd0f1b00abf&req=dScuHsp2moBbWvMW3nq%2BgZPn43QJg8WVVc0ZVd8M6r96eVKW%2BS8G1RavyNB3%0A6vNrKhgPoxi%2FkGAPFMy7%2BWg0BfM%3D%0A) Dateiname Geben Sie den Namen und den Speicherort ein, den die exportierte Datei im System haben wird Export-Setup Wählen Sie zwischen folgenden vordefinierten Setups: \<In-Session Setup> IFC 2x3 Coordination View 2.0 IFC 2x3 Coordination View IFC 2x3 GSA Concept Design BIM 2010 IFC 2x3 Basic FM Handover View IFC 2x3 Coordination View IFC 2x3 COBie 2.4 Design Deliverable View IFC4 Reference View [Architecture] IFC4 Reference View [Structural] IFC4 Reference View [BuildingService] IFC4 Reference View [Unofficial] IFC4x3 IFC-SG Regulatory Requirements View Wenn das Catenda Plugin für Revit verwendet wird, wird ein zusätzliches vordefiniertes Export-Setup zur Verwendung mit Catenda zur Liste der Optionen hinzugefügt.

## 3. **Setup ändern**

Klicken Sie auf "Setup ändern" im Export-Setup-Teil des Export-IFC-Dialogs.

Hier können die erforderlichen Einstellungen für IFC-Exporte geändert und benutzerdefinierte Setups erstellt werden.

So sieht das Menü "Setup ändern" aus:

![](https://downloads.intercomcdn.com/i/o/areracg3/1892255169/dc9485955be8e9d289ef7b133e42/image.png?expires=1779991200&signature=fdb3c6d8b891f2db5a5d46d63d24dabdeb1eb90d7e823e58f8076ad2e015e125&req=dSguFMt7mIBZUPMW3nq%2BgU4rCzwBivDLfsHeLviWOkIR%2BVu9c41EQE6LWfpQ%0AnFh5xdUdS7zkwB57Eqs2k6s5uMw%3D%0A)

Dieses Fenster enthält die folgenden Registerkarten:

[Allgemein](#h_fb41b895ea) - [Zusätzlicher Inhalt](#h_ed48fc4387) - [Property Sets](#h_04dd25ffef) - [LoD](#h_11ae63fb7f) - [Erweitert](#h_f7b35f27cd) - [Geografische Referenz](#h_de5067b34b)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 3.1 **Allgemein**

![General](https://downloads.intercomcdn.com/i/o/areracg3/1892229977/5b41cf313ce744a76d57707e7156/image.png?expires=1779991200&signature=de7a76fac9b01f590c83303ae40078c1584ff8b4876ef0b169519d39e6d9c20a&req=dSguFMt8lIhYXvMW3nq%2BgaV%2FCQixLdXaNeZ7QyQ0axWAyNp02PCsj0gdc2if%0Ad1tMevbVyEJSRIO7%2Bjxmt6fUIRM%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892261475/b091b92e7662bd96f93d12bf7f53/image.png?expires=1779991200&signature=9c06e8d7af983ce6a940f923b9ef8727f8c61d9e26ef8e352988fa36b62bd281&req=dSguFMt4nIVYXPMW3nq%2BgXBEgWjeQPHCGpBWTw2Nw1Jy05ppTRgbw1VTpLZH%0At1eqbpZDOUcMRs4z%2FBI%2Fnj41rJ0%3D%0A)

Wir führen Sie durch die verschiedenen Einstellungen.

_IFC-Version_

Auswahl der IFC-Version.

_Anforderung für den Austausch_

Diese Optionen können je nach ausgewählter IFC-Version unterschiedlich sein.

IFC 2x3 Coordination View 2.0

- Architektonischer Referenzaustausch
- MEP-Referenzaustausch
- Struktureller Referenzaustausch
  _Kategoriezuordnung_
  Vor Revit 2026 war diese Option unter Datei -> Exportieren -> Optionen -> IFC-Export-Optionen verfügbar.
  So sieht das Menü "IFC-Export-Zuordnungseinstellungen verwalten" aus:
  ![](https://downloads.intercomcdn.com/i/o/areracg3/1892362444/0291c2b037d32fe0a4808e9fe7f7/image.png?expires=1779991200&signature=528dc3b6bcb4d9399320d85087b57a2e29ed93341169cec06ce9cb8ed5c84fb7&req=dSguFMp4n4VbXfMW3nq%2BgZ7axO8%2FlFRz4FYwOCciizXyG4lDOXEisrBlsk4c%0AAoRXuiRV9UdddmK2UwD%2FBi7AM7g%3D%0A)
  _Dateityp_
  Auswahl des IFC-Typs.
  _Phase zum Exportieren_
  Wenn Sie das Phasen-Tool in Revit verwendet haben, können Sie hier wählen und nur neue oder vorhandene Strukturen exportieren.
  _Raumgrenzen_
  Dies dreht sich alles um die Nutzung von Rauminformationen.
  a. 1. Ebene - Beispiel für die Verwendung: Mengenentnahmen, Verwaltung, Betrieb und Wartung (FDVU).
  b. 2. Ebene - Beispiel für die Verwendung: Energieanalyse, Lichtanalyse.
  _Anlagetyp_
  Diese Option ist nur für IFC 4x3 verfügbar
  Wählen Sie eine der folgenden Optionen:
  Brücke (IfcBridge)
  Gebäude (IfcBuilding)
  Meeresanlage (IfcMarineFacility)
  Eisenbahn (IfcRailway)
  Straße (IfcRoad)
  _Wände, Säulen, Kanäle nach Ebene teilen_
  Hier können Sie z. B. Trennwände horizontal teilen, wenn sie über mehrere Geschosse modelliert sind.
  _Datei-Header-Informationen...
  Projektadresse..._
  Hier können Sie Informationen eingeben, wer die IFC geliefert hat, die Projektadresse usw.
  _Projektursprung_
  Projektursprung, den wir auf Aktuelle gemeinsame Koordinaten - Vorhandene gemeinsame Koordinaten setzen.

> **Hinweis:** Dies wurde ab Revit 2025 zu Geografische Referenz verschoben _Stahlelemente einbeziehen_ Beinhaltet Stahlkomponenten, falls modelliert. **Hinweis:** Dies wurde ab Revit 2025 zu Zusätzlicher Inhalt verschoben

---

### 3.2 **Zusätzlicher Inhalt**

![Additional Content](https://downloads.intercomcdn.com/i/o/areracg3/1892231518/1438a720e7d2d083f16e999b248d/image.png?expires=1779991200&signature=14ae8e037db758f837b33fce3426217ec13a1be4bdae21d9021a6c6e2adef1ed&req=dSguFMt9nIReUfMW3nq%2BgUrmoL4SQTHbWqp11fsyPaNkkVHU8HTI2%2F7M7%2BzB%0ABmowPSLQu3ATd2%2F2iUivb83tBuQ%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892263880/c2a3aa2c87b0e2798aa352e8e939/image.png?expires=1779991200&signature=d34f7286a508b4628d39a8280c078fb7fab54fd9c269d8f5f4b9bdb4b2f506cc&req=dSguFMt4nolXWfMW3nq%2BgZuMl2%2B0ocCSxdsSWUVwjc07TZne90pVVQ20GLrW%0AXKEA4G7s2qjM4xmQ4ob3bLJz%2Fzg%3D%0A)

Verlinkte Dateien als separate IFCs exportieren

Wenn Sie die verlinkten Dateien in die IFC einbeziehen möchten, können Sie diese Option aktivieren.

Es wird empfohlen, jede Datei separat zu exportieren und jede in ihr eigenes Modell zu importieren.

Nur sichtbare Objekte in der Ansicht IFC-Datei exportieren.

- Räume, Bereiche und Räume in 3D-Ansichten exportieren
  Diese Option kann nützlich sein, um Bereiche im 2D-Viewer zu wählen.
  Stahlelemente einschließen, _gefüllt_
  Exportiert 2D-Grundrisselemente, _gefüllt, Regionen_ (Kratzer).
  Deckenraster exportieren
  Deckenraster sind 2D-Elemente und werden daher nicht im Catenda 3D-Viewer angezeigt.

---

### 3.3 **Property Sets**

![Property Sets](https://downloads.intercomcdn.com/i/o/areracg3/1892232792/135fdbf14ece65c88f19bd1d226a/image.png?expires=1779991200&signature=08f85973ddc0828e1bce6019eed0e2ca144295420ac48e4d9b236988f3109720&req=dSguFMt9n4ZWW%2FMW3nq%2BgaY8ra%2BUm5L2ZjmJcmldhCuBAdrt45HA7HZqKLol%0AtoA76daMbGTClWLlzEA9uLIe9yA%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892275051/2ed64b1590f2714d62846de4f92f/image.png?expires=1779991200&signature=72c737d699d3e9d1d54ab3270ebf9a6416e597a6f32ba4fc860fd242e2c1abcd&req=dSguFMt5mIFaWPMW3nq%2BgZi725RhkXN5IeQuWPtKkGbxpRk%2Bl9O8njkEN8R8%0AV3y8MdRThA7Jgy%2FpcsTiX3Qr%2Bo0%3D%0A)

Exportiert alle Revit Property Sets (pset / Eigenschaften)

Hier ist ein Beispiel einer mit dieser Option exportierten Wand:

Revit (_Links_) --- Catenda (_Rechts_) <img alt="Properties" src="https://downloads.intercomcdn.com/i/o/1143733823/5843705d0d8e18fad06a2d26/image.png?expires=1766188800&amp;signature=e683738cab58632050b7cafa92c034f12a46f70dfe3155d1cf4d911252b4d5cc&amp;req=dSEjFc59noldWvMW3nq%2Bgf%2FEabfHtQiF4KaxSmsaQLmis0sQMPMY4FRacuZa%0Az3YPfah7rm21SlIs85aLL8uLrZY%3D%0A" width="208.60495436766624"/>  ---  <img alt="Properties" src="https://downloads.intercomcdn.com/i/o/1143736276/8e2cd444c3cb4bb85a54a8eb/image.png?expires=1766188800&amp;signature=10633b362c0901da616a360cdbf654306792d62af04cc4f3501c3bda51769102&amp;req=dSEjFc59m4NYX%2FMW3nq%2BgT9zLO7Skq%2BTFld2KtbnaRMzDGwWjYF5Mm1itI8z%0AVIQLHf%2B4YSGFII1x5k%2BObZqVuGo%3D%0A" width="190.21739130434784"/>

Typische Eigenschaften im Eigenschaftsmenü sind:

Einschränkungen, Querschnittsdefinition, Abmessungen, Struktur, Identitätsdaten, Sonstige

Typische Eigenschaften im Menü "Identifikation" sind:

IFC-Parameter

Exportiere Standard-IFC-Eigenschaften.

Exportiert berechnete Mengen von Objekten.

Exportlisten exportieren

Einmalige Property Set exportieren

_Klassifizierungseinstellungen_

Hier ist ein Beispiel, wie Klassifizierungseinstellungen mit Omniclass aussehen können.

![Classification Settings](https://downloads.intercomcdn.com/i/o/1143721778/529f91196d1161bc0f7fc191/image.png?expires=1779991200&signature=f13d4621978f597e4d0c968364da4bd522527c7f374efda94be6a0be7575c6ca&req=dSEjFc58nIZYUfMW3nq%2BgTdoFEUepwZW6XnZ2V0i6WQvADjlF%2BLhRY6OJkFP%0AiNN3Uof7HbJp4u6Gl9XBlQAU8Ss%3D%0A)

_Name_

Der Name der Klassifizierung

_Quelle (Herausgeber)_

Der Herausgeber der Klassifizierung

_Ausgabe_

Die Klassifizierungsausgabe

_Ausgabedatum_

Das Datum der Klassifizierung

_Dokumentationsort_

Dies muss ein gültiger Dokumentationsort sein

_Name des Klassifizierungsfelds_

Der Name des Klassifizierungsfelds ist der Name des Parameters in Ihren Objekten, der den Klassifizierungswert enthält. Dieser Parameter befindet sich häufig auf der Familienebene.

Bearbeiten Sie eine Familie, um ihre Eigenschaften zu sehen

![Edit Family](https://downloads.intercomcdn.com/i/o/1143724998/b22b5f6c87f49ea7c42381bf/image.png?expires=1779991200&signature=8590e78ce69a0d98961dc796b658ba4bf72cf03c45dba1890900a214bafbb117&req=dSEjFc58mYhWUfMW3nq%2BgSZUcWo6HOAqXXhYpyvCdnZ5nwKOSt5eRyx6qPHd%0AgRRUvOdjNZu11Av4vkAmqN6p0o4%3D%0A)

So sieht der Parameter in den Eigenschaften aus

![Properties OmniClass Number](https://downloads.intercomcdn.com/i/o/1143726246/d4edad8d1fd6912e74ac1dfd/image.png?expires=1779991200&signature=25a111f49176bbcd4a4eca8317c7d6020339ad9635734a6fdd66b808adc91213&req=dSEjFc58m4NbX%2FMW3nq%2Bge0lDZh%2F80lWgG1V9tT6cxgr0M7xLIsZrNn2i2Tj%0Ar3LmBV%2BDKYl2bfCvCkuordzTxII%3D%0A)

Wenn Sie Ihre IFC mit einer Klassifizierung exportiert und als Modell in Catenda importiert haben, wird die Klassifizierung als [empfohlene Bibliothek](https://support.catenda.com/en/articles/8065645-libraries-page#h_c03d50a9ca) angezeigt, wenn Sie eine neue Bibliothek auf der [Seite "Bibliotheken"](https://support.catenda.com/en/articles/8065645-libraries-page) erstellen.

Wenn ein Wert in der angegebenen Eigenschaft mit einem Wert in der bereitgestellten Dokumentation übereinstimmt, wird er gefunden und kann verwendet werden, um Objekte mit diesem Wert über die erstellte Klassifizierungsbibliothek auszuwählen.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 3.4 **Level der Details**

![Level of Detail](https://downloads.intercomcdn.com/i/o/areracg3/1892234477/a9bbe7f93df2e1f86dd77e0d8595/image.png?expires=1779991200&signature=51855781c86ef0d04cb75ec5abe362af236e216618b33ecddea36190c8ece55b&req=dSguFMt9mYVYXvMW3nq%2BgcGzWTbpx%2B5haiavdWYct%2BeRmFV0zbmfiG0oTuny%0ATNdlYRRUrCJXUVJUnpte5c9DwEg%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892279715/fc5d54cc402a319c1f102802fc97/image.png?expires=1779991200&signature=a04b7a621f85578fedddab7f9829e2da3a5a0d67f2226d40d826a5ff56e0f063&req=dSguFMt5lIZeXPMW3nq%2BgUWqnn%2FqIvGkfS0SdjfSGKflUy63XmjaojOfoQju%0ADW71Q%2BhgwZX1JLzynRJK3wz6z%2BQ%3D%0A)

Es geht darum, wie detailliert wir zum Beispiel haben. Tassen oder Handläufe oder vielleicht Fahrradräder. Es gibt 4 verschiedene Detailebenen.

Sehr niedrig

Niedrig

Mittel

Hoch

Wenn hoch, wird es am ausführlichsten wie in der Abbildung unten dargestellt.

![Level of detail extra low and high](https://catenda-as.intercom-attachments-1.com/i/o/271057169/c6cea2aa0003f1c409488aae/image-7.png?expires=1779991200&signature=61fe3f4006900fd1d34c251c062b3db03fc2fd91f19e16a776870e31c9aebfab&req=dicmFsx5nIdWFb4V1XW4gbUv%2FgfutyCFZjDb1AFfiWvoJKOpzILR0DxPJCm8%0AyB%2BxbX0DAGzFhIfWt2vGYTMOHg%3D%3D%0A)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Beim Export von IFCs aus Revit zur Verwendung in Catenda Hub empfehlen wir, die Detailebene nicht auf hoch einzustellen. Es gibt viele Details und zusätzliche Polygone in Modellen, wenn sie mit höherer Detailebene exportiert werden, und dies ist nicht immer erforderlich und verlangsamt die Modellnavigation. Dies ist ein Beispiel für den Unterschied zwischen dem Export mit der Einstellung "Sehr niedrig" und "Hoch".

![Dies ist ein Treppenhandlauf, der mit der Einstellung Hoch exportiert wurde. 900.000 Polygone](https://catenda-as.intercom-attachments-1.com/i/o/271057176/4d23600fddf517fa8afa68b3/image-8.png?expires=1779991200&signature=b40c5225839df08ff3cb63abba8707242a1b1485aea1a1349b7432050ae583ee&req=dicmFsx5nIZZFb4V1XW4gXDdgIisYwJtT%2FPcu87o1zP5fAUc4VXkBDnRaDr8%0A2T6aJEaBkIYupUl7unZmH%2FzFdA%3D%3D%0A)

![Dies ist dasselbe Modell, das mit der Einstellung "Sehr niedrig" exportiert wurde. 33.000 Polygone.](https://catenda-as.intercom-attachments-1.com/i/o/271057186/de52cec6e75ba1d44c01d9fb/image-9.png?expires=1779991200&signature=d8d2ced2202f3b52ae3b4585ea65977a74ee4709caed275abfc8d460d88a29db&req=dicmFsx5nIlZFb4V1XW4ga5Y09oq5DnlsKxhZ3TBUX7ENpGZnXWMCoB3Pz9w%0AYeiCXqLvdMUXo7BSPFFWU5lI1Q%3D%3D%0A)

Das Aussehen des Modells ist ähnlich, aber die Anzahl der Polygone nimmt drastisch ab und die Navigation in Catenda Hub ist viel schneller.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

### 3.5 **Erweitert**

![Advanced](https://downloads.intercomcdn.com/i/o/areracg3/1892235835/c5a537efaad511b257aa34fd9393/image.png?expires=1779991200&signature=9ef54911a2b76d39f4e3c23df0f85f171699dd8a363ab3cf3cb37349a603544d&req=dSguFMt9mIlcXPMW3nq%2Bgej6EvTV%2BJ5RKvpYf%2BwKvvA%2BZUGNGSO9ksC63ytf%0AVqsnDeqhyykw%2B4ATqbgGWKSALMs%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892285324/5ee98db642dda09e9ef2e32f89f3/image.png?expires=1779991200&signature=a1105615a979210c8668e250b9ba318c89bc4fbd6335483a32692b3f7a71552f&req=dSguFMt2mIJdXfMW3nq%2BgeyMDiMPhq7Q85wgYm3Xh1XpOK5XvxcASYTyhduW%0AsLQ%2B1rJyZBFN%2FAQvoW31uHOg%2F7A%3D%0A)

_Teile als Bauelemente exportieren_

Exportiere Teile wie Standard-IFC-Element.

_Verwendung gemischter "Solid Model"-Darstellung zulassen_

Wählen Sie diese Option, um das Mischen von BRep- und Extrusions-Geometrien für eine Einheit zu ermöglichen.

_Aktive Ansicht beim Erstellen der Geometrie verwenden_

Wählen Sie diese Option, um die aktive Ansicht zum Generieren der Geometrie zu verwenden. Beachten Sie, dass dies zu unerwarteten Ergebnissen führen kann, wenn es in einer Nicht-3D-Ansicht verwendet wird.

_Familiennamen und Typnamen für Referenz verwenden_

Wählen Sie diese Option, um die Familiennamen und Typnamen für Referenzen zu verwenden.

_2D-Raumgrenzen für Raumvolumen verwenden_

Wählen Sie diese Option, um einen vereinfachten Ansatz zur Berechnung des Raumvolumens zu verwenden (basierend auf Extrusion von 2D-Raumgrenzen), der auch Standard beim Export zu IFC 2x2 ist.

_IFCSite-Erhebung in den lokalen Platzierungsursprung der Website einbeziehen_

Wählen Sie diese Option, um die Höhe vom Z-Versatz für die lokale Position in IfcSite einzubeziehen. Entfernen Sie die Option, um sie auszuschließen.

_Speichern Sie die IFC-GUID nach dem Export in einem Elementparameter_

Wählen Sie diese Option, um die generierten IFC-GUIDs nach dem Export in der Projektdatei zu speichern. Dadurch werden "IFC GUID"-Parameter zu Elementen und deren Typen sowie zu Projektinformationen für Projekt-, Website- und Gebäudeführer hinzugefügt.

_Begrenzendes Feld exportieren_

Wählen Sie diese Option, um "Begrenzungsfeld"-Darstellungen zu exportieren. Diese Option wird für den GSA-Export automatisch ausgewählt.

_Tessellierte Geometrie als Triangulation beibehalten_

Wenn Sie komplexe gekrümmte Elemente oder Schalen haben und diese nach dem IFC-Export nicht korrekt angezeigt werden, können Sie diese Option wählen. Beachten Sie, dass Sie möglicherweise eine sehr große IFC-Datei erstellen.

_Nur Typnamen für IFCType-Namen verwenden_

Wählen Sie diese Option, wenn die BAT-ID oder die ID des Objekts als Name der Entität angezeigt werden soll.

_Sichtbaren Revit-Namen als IFCEntity-Namen verwenden_

Wählen Sie diese Option, wenn der Revit-Objektname der Name der Entität sein soll

_Alle facettierten Böden und Dächer immer als einzelne IFC-Entität exportieren_

Wählen Sie diese Option, um Flächen von Böden und Dächern mit mehreren Flächen zu einer einzelnen Entität zu kombinieren.

_Legen Sie den Benutzer "Zuletzt geändert" auf den Autor in den Projektinformationen fest_

Wählen Sie diese Option, wenn Sie der Autor der Änderungen bei diesem Export sind

_Zu exportierende Entitäten_

So sieht das IFC-Entity-Selection-Menü aus, das geöffnet wird:

![](https://downloads.intercomcdn.com/i/o/areracg3/1892286935/be99502f0dd70ec946f55438c390/image.png?expires=1779991200&signature=799dca9446d3b00d4ca06944add4e6d6f47d8fd33c8a778c5d2557ab8437c12e&req=dSguFMt2m4hcXPMW3nq%2BgcADQUPx2PSQHDp0RWxq5dUnOJgx%2ByBdwcstuqRL%0AJLIzsYDQIIYPtAIY1dFKFpLkOAE%3D%0A)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 3.6 **Geografische Referenz**

Es ist wichtig, dass Ihre Revit-Koordinaten mit den anderen Modellen in Ihrem Projekt synchronisiert sind, damit sie am selben Ort landen.

Daher messen Sie die Koordinaten in Catenda Hub mit einer Punktmessung und geben Sie eine Koordinatenbasis in Revit an einem Punkt an, der sich an der gleichen Stelle wie der gemessene Punkt in Catenda Hub befindet.

![Koordinate am Punkt angeben](https://downloads.intercomcdn.com/i/o/969764101/0c12135b4cfe78982de2d2c9/image.png?expires=1779991200&signature=060be8f8a603fc0b1a1df40a9afcb314add9da447d344221a97c1a482e645427&req=fSYuEc96nIFeFb4V1XW4gXGcH65AQ%2BvBsmsiUzSJvpOZcWtpsV6NEtp3COB%2B%0AaAl33RB7R1SlFNStV1N44yOhtw%3D%3D%0A)

Sie finden diese Option auf der Registerkarte "Verwalten" -> "Koordinaten" -> "Koordinatenbasis angeben".

_Koordinaten am Punkt angeben_

Versetzt ein Modell und dreht das Modell auf "Wahren Norden" durch Angabe von Koordinaten für Nord/Süd, Ost/West und Höhe.

In Revit ist es oft einfacher, mit 90-Grad-Winkeln zu modellieren und das gesamte Modell nicht zu drehen.

In diesem Fall können Sie stattdessen "Wahrer Norden" drehen.

Sie finden die Option in der Dropdown-Liste "Position" unter "Koordinaten" auf der Registerkarte "Verwalten".

![Geographic Reference](https://downloads.intercomcdn.com/i/o/areracg3/1892237064/dbd69633fadc1d5fe77cbbf10ad1/image.png?expires=1779991200&signature=a0fa45620598f4ea49637c071c3642c3e09a750a27b3c437d265926073e9efee&req=dSguFMt9moFZXfMW3nq%2BgWz5kavwajm2Q89QCw7rQngImO5dALYR%2F3X935bY%0ALRKgoqo1rT6VHyQCuYBc%2FWMRiDE%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892312196/3e117bb428e5bade5ced558f9bf3/image.png?expires=1779991200&signature=42aea4804b1dd4c21c0c6c4b6ed80d944086564e35b9902d1720c87903230719&req=dSguFMp%2Fn4BWX%2FMW3nq%2Bgak09I%2BhVIo7RxVv6rvgFchwhCbwffygGJDj6sXo%0AQDbWBuoUwVnnATNMwVm1SBR0YXM%3D%0A)

_Projektstandort_

Intern

_Koordinatenbasis_

Sie können diese Einstellung ändern, um sicherzustellen, dass Ihr Projekt nach Norden ausgerichtet ist

Gemeinsame Koordinaten - Standard

Vermessungspunkt

Projekt-Basispunkt

Interner Ursprung

Projekt-Basispunkt nach Wahrer Norden ausgerichtet

Interner Ursprung nach Wahrer Norden ausgerichtet

> **Hinweis:** Wenn Sie eine IFC in der Registerkarte "Einfügen" verlinken, wird die verlinkte Datei neben Ihren Objekten platziert und befindet sich nicht an der in der IFC beschriebenen Position. Um eine IFC am richtigen Ort zu importieren, klicken Sie auf "Datei" -> "Öffnen" -> "IFC". _Überschreiben_ Hier können Sie die Referenz des projizierten Koordinatensystems überschreiben

---

### 3.7 **Unternehmensinfo**

![](https://downloads.intercomcdn.com/i/o/areracg3/1892339968/a88c70cdc3d15ec1e87a1e966b46/image.png?expires=1779991200&signature=f68f221eb9ab0afd91c637e525a5d0057b3307e8e6530d5198dd90d3b144f8e5&req=dSguFMp9lIhZUfMW3nq%2BgRXRtZV646CzbhYCDTM1GZGXZIjmattZX5CDm0VJ%0ALOUcKRLlH3C9wmRrDi%2FTOy04v%2Bs%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892341695/f8aef094c7a84c8664cb6db386bc/image.png?expires=1779991200&signature=a174a5fdf3b7af5e95c5d1ed03b7d3edb1cacd026417765fdd6e0ec39c25cf03&req=dSguFMp6nIdWXPMW3nq%2BgSpJnU2%2FxbcY6345g60I7jviXU4X7ABgbjwoKuc7%0AcMRBSRyfbTm2vWp7Oys9oBkK7kw%3D%0A)

Dieses Menü ist nur verfügbar, wenn das Setup "IFC2x3 COBie 2.4 Design Deliverable View" im linken Menü ausgewählt ist.

-------------------------------------------------------------------------------------------------------------------------------------------------------

### 3.8 **Projektinformation**

![](https://downloads.intercomcdn.com/i/o/areracg3/1892356241/5a9153e5328e33ef5732be86af07/image.png?expires=1779991200&signature=24762c0ace7ebe4478d2b2713cd6017d4832352f6043104b1cc30ae373ab08f7&req=dSguFMp7m4NbWPMW3nq%2BgdDcqeJjXwra65LLEws6tCTU0wICq0oh9qpS9%2FJn%0Aqm4kmvwf4QEYAICFX8bkvDuQ7PE%3D%0A)

![](https://downloads.intercomcdn.com/i/o/areracg3/1892357722/97a31374ae328eff814a977ff3ec/image.png?expires=1779991200&signature=003f4e0f69fc7180132651ec2a4ffb712c3fd3dde1440a29ae2fc4dc2a0573bb&req=dSguFMp7moZdW%2FMW3nq%2BgaYH1F4G60q4NivzbwFWQfKx5c%2BITWNaFVEP55gD%0AWJoucJnbsl2gDq1dZBIrmkyfeVs%3D%0A)

Dieses Menü ist nur verfügbar, wenn das Setup "IFC2x3 COBie 2.4 Design Deliverable View" im linken Menü ausgewählt ist.

-------------------------------------------------------------------------------------------------------------------------------------------------------

## 4. **IFC-Optionen**

Die IFC-Optionen eines Revit-Projekts finden Sie unter:

`Datei -> Exportieren -> Optionen -> IFC-Optionen`

![Export -> Optionen -> IFC-Optionen](https://catenda-as.intercom-attachments-1.com/i/o/271057200/45a1257c55b1828c71e969a4/image-11.png?expires=1779991200&signature=19ba7f1f06c737fd1570f0a06070ad9db96d0694ad820be88fb17bb60ed41856&req=dicmFsx5n4FfFb4V1XW4gakKrGXQvzEGkCAUJOtaQtRh3HZCglVgstn6e2Ch%0AaxVYb3DMOLXIpE8hXgvg%2F%2FKfNg%3D%3D%0A)

> **Hinweis:** Ab Revit 2026 ist diese Option jetzt unter folgender Adresse verfügbar: `Export -> IFC -> Allgemein -> Kategoriezuordnung -> Aktionsmenü rechts neben Dropdown` Hier innerhalb der _IFC-Optionen_ nehmen wir die Einstellungen zum Exportieren eines Modells in eine IFC-Datei vor. Hier können Sie Einstellungseigenschaften zum Exportieren eines Modells in IFC anpassen. Was zu Beginn dieses Handbuchs erwähnt wurde, ist, dass es nicht erforderlich ist, zu viele Informationen aus dem Modell herauszubringen. Sie können gerne vor dem Export auf unnötige Informationen verzichten. ![IFC-Export-Klassen](https://catenda-as.intercom-attachments-1.com/i/o/271057211/d475dd84fb2efef9d7bf4c1d/image-12.png?expires=1779991200&signature=ceb04d005a9687945fd4c5efc680f142fa8f71ab5daddaf6ef11c8828c6103ea&req=dicmFsx5n4BeFb4V1XW4gdpd3cvRJhUNG2sGxDwDCuCNDMBg6YsRp7MEvaGe%0Ao0oBh68YB8CtIWlb%2Bwt%2Fl%2BbXug%3D%3D%0A) Es ist möglich, Raster in Catenda Hub anzuzeigen, und wenn Sie diese in Ihrem Revit-Modell haben, können Sie in IFC-Optionen Raster so einstellen, dass sie in der IFC exportiert werden. Standardmäßig werden diese nicht aus Revit exportiert.

## 5. **Farben und Materialien**

Die Farben, die in Catenda angezeigt werden, werden aus der importierten IFC-Datei gelesen.

Wenn die Materialeigenschaft einer Familie zu den IFC-Parametern hinzugefügt wird, wird die Farbe des Materials in der Materialeigenschaft zu der IFC hinzugefügt und somit in Catenda angezeigt.

In Revit finden Sie Materialien im Material-Browser:

`Verwalten Sie die Registerkarte -> Einstellungsbereich -> Materialien`

Im Material-Browser finden Sie die Farbeinstellung auf der Registerkarte "Grafiken" des Materials:

![Verwalten Sie -> Materialien -> Material-Browser -> Erstellen Sie ein neues Material](https://downloads.intercomcdn.com/i/o/areracg3/1798363404/1016d10e61dcd4bbf3969dd97a39/image.png?expires=1779991200&signature=6538f237377a045f7b7f567244f4fdefd99bc74142dc54780c79610f54b88159&req=dScuHsp4noVfXfMW3nq%2BgRHARe%2BQbSvVJU1tDswOuiSVbxNsRYJibJHNSy4a%0ADvZyAbDR4cFQbN%2FOUhLbnJ9ZKrw%3D%0A)

Es ist auch möglich, die Schattierung an die Render-Einstellungen zu sperren.

![Appearance](https://downloads.intercomcdn.com/i/o/areracg3/1798375002/9394922e0e04c7beffd701083d45/image.png?expires=1779991200&signature=d9d2670f75a1006a4b4d3d03f3e9c19bcfffcafb0d76728976f55be340ebe2c6&req=dScuHsp5mIFfW%2FMW3nq%2BgczmUc51w6Slra%2FB5MdIivv2AVzb0Puu5CECSt7u%0AvMA6oVuMcEZW9opaPvxvO6x6HrE%3D%0A)

Oberflächen im Catenda 3D-Viewer haben flache Schattierung ohne Lichtquelle.

Die folgenden Werte werden von Catenda bei der Anzeige der Oberfläche im 3D-Viewer interpretiert:

Allgemein

- Farbe
- Bild ausblenden
  Transparenz
- Menge
- Bildfade
- Transluzenz
  Tint
- Tint-Farbe
