# Welche Dateigröße kann ich hochladen?

Die folgende Tabelle enthält Größen, bis zu denen Dateien hochgeladen werden können: Dateien, die diese Limits überschreiten, erfordern alternative Methoden für einen effektiven Upload.

Die Dateigrößen in der folgenden Tabelle gelten für einzelne Dateien. Es gibt keine Begrenzung für die Anzahl der Dateien, die sich in einem Projekt befinden können.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 173px;"><h1 id="h_dee0bdcb7c"><b>Upload-Größe</b></h1></td><td style="background-color: #e3e7fa80; width: 108px;"><h3 id="h_644423a190"><b>Erweiterung</b></h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_0cc9638cff"><b>Dateigröße</b></h3></td></tr><tr><td style="width: 173px;"><h3 id="h_02ef636d2a">Dokumentbereich</h3></td><td style="width: 108px;"><p>Beliebig</p></td><td><p class="intercom-align-center">7 GB</p></td></tr><tr><td style="background-color: #e8e8e880; width: 173px;"><h3 id="h_79f0da432d">IFC-Verarbeitung</h3></td><td style="background-color: #e8e8e880; width: 108px;"><p><code>.ifc</code></p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">750 MB</p></td></tr><tr><td style="width: 173px;"><h3 id="h_7d57516cf7">IfcZIP-Verarbeitung</h3></td><td style="width: 108px;"><p><code>.ifczip</code></p></td><td><p class="intercom-align-center">750 MB</p></td></tr><tr><td style="background-color: #e8e8e880; width: 173px;"><h3 id="h_3c990303fb">Point Cloud</h3></td><td style="background-color: #e8e8e880; width: 108px;"><p><code>.e57</code> </p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">25 GB</p></td></tr><tr><td style="width: 173px;"><h3 id="h_0bbd014cc0">Point Cloud</h3></td><td style="width: 108px;"><p><code>.las</code></p></td><td><p class="intercom-align-center">25 GB</p></td></tr><tr><td style="background-color: #e8e8e880; width: 173px;"><h3 id="h_788001d9cb">BCF-Import</h3></td><td style="background-color: #e8e8e880; width: 108px;"><p><code>.bcf</code></p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">500 MB</p></td></tr><tr><td style="width: 173px;"><h3 id="h_418d98af37">BCFZIP-Import</h3></td><td style="width: 108px;"><p><code>.bcfzip</code></p></td><td><p class="intercom-align-center">500 MB</p></td></tr></tbody></table></div>

## 1. **In kleinere Dateien aufteilen**

Es wird empfohlen, große .ifc- und .ifczip-Dateien in kleinere Dateien aufzuteilen. Durch Aufteilen können Sie die Upload-Begrenzung von 750 MB einhalten und die Dateiverwaltung in Projekten erleichtern.

Durch das Hochladen mehrerer kleinerer Dateien wird es für Projektmitglieder einfacher, verschiedene Teile ein- und auszuschalten und separate Teile der Datei einzeln herunterzuladen.

## 2. **Nach IfcZip exportieren**

Einige Authoring-Tools unterstützen IfcZIP als Option beim Exportieren von IFC-Dateien.

> **Hinweis:** **Beispiel:** `3D-model.ifczip`

## 3. **IfcZip erstellen**

Wenn die Größe einer `.ifc`-Datei das Uploadlimit überschreitet, kann eine `.ifczip`-Datei erstellt werden, um weiterhin hochgeladen werden zu können. Befolgen Sie diese Schritte, um eine `.ifc`-Datei in eine `.ifczip`-Datei umzuwandeln:

- Komprimieren Sie die `.ifc`-Datei in eine `.zip`-Datei.
- Ändern Sie die Dateiendung von `.zip` in `.ifczip`

> **Hinweis:** **Beispiel:** `3D-model.ifc` v `3D-model.zip` v `3D-model.ifczip ​`

## 4. **Support kontaktieren**

Wenn Sie die Datei nicht ändern können und die Datei größer ist als das Upload-Limit, kontaktieren Sie uns unter [support@catenda.com](mailto:support@catenda.com). Dateien werden von Fall zu Fall bearbeitet. Bevor Sie uns kontaktieren, erwägen Sie alternative Methoden wie das Erstellen einer `.ifczip`-Datei, die Verwendung des Desktop Connectors oder das Aufteilen der Datei in kleinere Teile.
