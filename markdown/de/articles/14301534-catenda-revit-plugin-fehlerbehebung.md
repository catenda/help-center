# Catenda Revit Plugin - Fehlerbehebung

Fehler, die bei der Verwendung des Catenda Revit Plugins auftreten können, und deren Lösungen werden in diesem Artikel erläutert.

## 1. **IFC hochladen**

In den Dateiname- und Kommentarfeldern des Upload-Modell-Dialogs werden nur ASCII-Zeichen zum Hochladen unterstützt. Um herauszufinden, welche Zeichen im ASCII-Satz enthalten sind, siehe [diesen Wikipedia-Artikel](https://en.wikipedia.org/wiki/ASCII).

Nicht-ASCII-Zeichen können wie folgt zu den Datei- und Kommentarfeldern hinzugefügt werden:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0bx8b1nt/01-upload-ifc.png)

Wenn Sie auf Hochladen klicken, wird die folgende Fehlermeldung angezeigt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0bx8b1nt/02-upload-ifc.png)

```
Ein nicht bearbeiteter Fehler ist in einer Komponente Ihrer Anwendung aufgetreten. Wenn Sie auf Weiter klicken, wird die Anwendung diesen Fehler ignorieren und versuchen, den Vorgang fortzusetzen. Anforderungsheader dürfen nur ASCII-Zeichen enthalten.
```

Bitte starten Sie Revit neu, nachdem dieser Fehler auftritt, um das Hochladen fortzusetzen.

## 2. **Manage Links-Fenster**

Nach der Installation des Catenda Revit Plugins in einem Revit 2025, das nach März 2026 aktualisiert wurde, stürzt Revit ab, wenn versucht wird, das Manage Links-Fenster zu öffnen. Dies ist auf eine Änderung von Autodesk zurückzuführen. Klicken Sie [hier](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Program-crash-on-certain-machines-when-opening-the-Manage-Links-dialog-in-Revit.html) für eine Problemumgehung. Bitte beachten Sie, dass nur Revit 2025 betroffen ist. Dieses Problem existiert nicht in Revit 2026.

## 3. **Unterstützte Revit-Editionen**

Das Catenda Add-in ist mit Revit-Editionen kompatibel, die die Revit API (Application Programming Interface) unterstützen. Die Integration ist in den folgenden Umgebungen möglich:

**Standard Revit** Vollständige Unterstützung wird für die multidisziplinäre Version der Software bereitgestellt, die die Toolsets **Architektur**, **Tragwerk** und **MEP** (Mechanik, Elektrik und Sanitär) umfasst.

**Educational Version** Lizenzen, die für Schüler und Pädagogen ausgestellt werden, unterstützen die Installation von Third-Party Add-ins, sofern es sich um die Vollversion der Software und nicht um die LT-Version handelt.

### 3.1 **Nicht unterstützte Edition: Revit LT**

Es ist wichtig zu beachten, dass [Revit LT Third-Party Add-ins oder Plugins nicht unterstützt](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Revit-LT-Is-it-possible-to-use-plugin-or-addins-in-Revit-LT.html), einschließlich des Catenda Revit Add-ins. Dies ist eine Einschränkung der Softwarearchitektur der LT-Plattform, da sie das erforderliche API-Framework nicht hat. Folglich ist es nicht möglich, das Add-in zu installieren oder eine Dynamo-basierte Automatisierung in der Revit LT-Umgebung zu nutzen.

### 3.2 **Versionskompatibilität**

Um die Ausrichtung auf die neuesten Software-Updates und Leistungsverbesserungen zu gewährleisten, werden die Integrationen regelmäßig aktualisiert. Um eine umfassende Liste der derzeit unterstützten Jahresversionen für sowohl das Revit Add-in als auch das Dynamo-Paket zu erhalten, lesen Sie bitte den Artikel [Plugins und Integrationen](https://support.catenda.com/en/articles/8396532-catenda-plugins-integrations).

## 4. Catenda Hub Dynamo Package

Für Workflows, die benutzerdefinierte Automatisierung erfordern, ist ein spezialisiertes Paket für Base Dynamo verfügbar. Dies ist nicht eine separate Anwendung, sondern eine Sammlung von Knoten zur Verwendung in der Standard-Dynamo-Umgebung.

**Lizenzierung** Für die Verwendung von Dynamo ist keine zusätzliche Autodesk-Lizenz erforderlich, da es als Kernfähigkeit in der Standard-Revit-Lizenz enthalten ist.

**API-Zugriff** Die Verwendung dieses Pakets erfordert Catenda API-Zugriff. Obwohl dieser nicht standardmäßig für jeden Kunden enthalten ist, kann der Zugriff über das Catenda-Support-Portal angefordert werden. Sobald der Zugriff gewährt wurde, ermöglicht der API-Zugriff Interaktionen über alle Projekte innerhalb einer Organisation.

**Installation** Die Bereitstellung des Pakets erfordert eine manuelle Installation durch Angabe des Dateispeicherorts in der Dynamo-Schnittstelle.

### 4.1 **Operational Warning für Dynamo-Benutzer**

Bevor die Verwendung dieses Pakets beginnt, wird eine Warnung ausgegeben, dass diese Tools Aktionen innerhalb eines Projekts ermöglichen, als wäre der Akteur eine Anwendung und nicht ein einzelner Benutzer. Mit großen Fähigkeiten kommt große Verantwortung. Auf Anwendungsebene ausgeführte Aktionen, wie z. B. Löschungen, werden anders verarbeitet als Standard-Benutzeraktionen. Elemente oder Daten, die von einer Anwendung gelöscht werden, können nicht wiederhergestellt werden. Extreme Vorsicht wird empfohlen, wenn diese Tools in einer Projektumgebung verwendet werden. Um API-Zugriff oder das Dynamo-Paket anzufordern, kontaktieren Sie bitte [support@catenda.com](mailto:support@catenda.com) oder nutzen Sie die schwarze Chat-Blase oben rechts auf der Plattform.
