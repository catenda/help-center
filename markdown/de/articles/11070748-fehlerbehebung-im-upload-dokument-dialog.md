# Fehlerbehebung im Upload-Dokument-Dialog

## 1. **Dokument existiert im Ordner**

Wenn Sie Schreibzugriff auf einen Ordner haben, aber nur Lesezugriff auf ein Dokument, können Sie diesem Dokument keine Revisionen hinzufügen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qn4yk3x7/01-document-exists-in-folder.png)

Bitte erstellen Sie ein neues Dokument mit dieser Revision oder laden Sie die Revision in ein anderes Dokument hoch.

## 2. **Ausführbare und Script-Dateitypen**

Wenn eine Datei einen potenziell schädlichen Dateityp hat, wird sie nicht hochgeladen. So kann es aussehen, wenn Sie versuchen, einen schädlichen Dateityp hochzuladen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qn4yk3x7/02-executable-and-script-filetypes.png)

Die folgenden Dateitypen, die möglicherweise schädlich sind, sind nicht zulässig. Sehen Sie in [diesem](https://support.catenda.com/en/articles/4670320-previewing-file-types-on-catenda-hub) Artikel nach, welche Dateitypen nicht hochgeladen werden können.

## 3. **Dateiname abgeschnitten**

Dateien, die von einem externen Laufwerk wie einem USB-Festplattenlaufwerk/USB-Stick oder einem Netzlaufwerk hochgeladen werden, können eine Begrenzung von etwa 250 Zeichen in der Länge ihres Pfads haben. Wenn der Pfad zur Datei zu lang ist, wird das Ende des Dateinamens (vor der Dateierweiterung) abgeschnitten und durch ~1 ersetzt. So sieht es aus, wenn ein Dateiname abgeschnitten wird.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qn4yk3x7/03-filename-cut-off.png)

Dies ist nicht eine Begrenzung von Catenda, sondern eher eine Begrenzung zwischen dem Browser und dem Betriebssystem. Um dieses Problem zu vermeiden, kopieren Sie die Dateien von der externen Position auf Ihren lokalen Computer und laden Sie sie von dort zu Catenda hoch. Ein guter Ort für diese Dateien ist normalerweise das Dashboard, wo temporäre Dateien gefunden und später entfernt werden können, oder das C:// Stammverzeichnis, um sicherzustellen, dass so viele Zeichen wie möglich in der Pfadlänge verfügbar sind.
