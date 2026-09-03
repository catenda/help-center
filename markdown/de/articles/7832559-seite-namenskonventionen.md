# Seite Namenskonventionen

Administratoren finden die Seite Namenskonventionen als Unterseite unter [Projekteinstellungen](https://support.catenda.com/en/articles/4670273-project-settings-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/01-intro.png)

## 1. **Benennung lokaler Dateien**

Mit Namenskonventionen können Sie einschränken, welche Dateien je nach Name der Originaldatei in einen Ordner hochgeladen werden. Dies ist sehr nützlich, wenn Sie bereits Regeln für die Benennung Ihrer lokalen Dateien haben. Sie sollten Ihre Dateien nicht umbenennen müssen, um sie in Catenda Hub hochzuladen. Wenn Sie keine Regeln für die Benennung Ihrer lokalen Dateien haben, wird die Namenskonvention nicht empfohlen.

## 2. **Dokumente, Überarbeitungen und Originaldateien**

Bevor Sie beginnen, ist es wichtig, den Unterschied zwischen einem Catenda Hub **Dokument** und einer **Datei** zu verstehen. Sie können sich ein Dokument (und Dokumentüberarbeitungen) in Catenda Hub als einen _Container für Dateien_ vorstellen. Sie können eine Datei in diesen Container hochladen und als Administrator ihren Namen ändern. Dateinamen unterscheiden sich oft sehr voneinander, obwohl sie die gleiche Version der Zeichnung oder des Blattes sind, das Sie hochladen möchten. Mit der Namenskonvention können Sie ähnliche Dateien auf der Grundlage einer Reihe von Regeln im Namen der Datei in das gleiche Dokument hochladen.

## 3. **Neue Namenskonvention**

Oben rechts auf der Seite sehen Sie die Schaltfläche „Neue Namenskonvention".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/02-new-naming-convention.png)

So sieht eine neue Namenskonvention aus.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/03-new-naming-convention.png)

### 3.1 **Konventionsinformationen**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/04-convention-information.png)

**Name** Der Name der Konvention, wie er bei der Anwendung in den Dokumenteinstellungen angezeigt wird

**Beschreibung** Die Beschreibung der Konvention, wie sie in den Dokumenteinstellungen angezeigt wird

**Trennzeichen** Das Zeichen, das jeden Block außer dem Dateiendungs-Block trennt.

### 3.2 **Vorschau**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/05-previews.png)

In der Vorschau wird das Muster angezeigt, nach dem die Konventionen sowohl in Ihrem lokalen Dateisystem als auch in der Dokumentstruktur von Catenda Hub folgen. Diese können unterschiedlich sein und das eine kann dem anderen zugeordnet werden, wie Sie sehen werden

**Dokumentname** Die Art und Weise, wie das Dokument in Catenda Hub aussieht, wenn die Datei hochgeladen wird

**Erwarteter Dateiname** Die Art und Weise, wie Dateien aussehen sollen, die hochgeladen werden dürfen

### 3.3 **Vorschautypen**

Wenn Sie mit der Maus über die verschiedenen Vorschautypen fahren, wird eine detaillierte Erklärung angezeigt, was jede Vorschau bedeutet. _Text - variable Länge:_ {X} _Text - feste Länge:_ XXXX _Benutzerdefiniertes Feld:_ {Name des benutzerdefinierten Feldes} _Trennzeichen:_ Wenn Sie drei oder mehr Blöcke haben, wird das von Ihnen festgelegte Trennzeichen angezeigt

### 3.4 **Blöcke**

Die Namenskonvention besteht aus einer Reihe von Blöcken. Jeder Block stellt einen Teil des Namens der Datei/des Dokuments dar. Klicken Sie auf „Block hinzufügen", um einen neuen Block hinzuzufügen.

![Block hinzufügen](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/06-blocks.png)

Eine Konvention hat immer mindestens zwei Blöcke: 1\. Der Name der Datei/des Dokuments. 2\. Der Name der Datei-/Dokumentendung.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/07-blocks.png)

**Name** Der Name des Blocks im Namenskonventions-Setup, um sie voneinander zu unterscheiden

**Beschreibung** Hier können Sie eine Beschreibung eingeben, was dieser Block tun soll

**Dokumentkennung** Wenn Sie einen Teil des Dateinamens erwarten, den Sie in Catenda Hub nicht sehen möchten, können Sie die Dokumentkennung deaktivieren. Dieser Teil des Dateinamens wird weiterhin zum Akzeptieren von Dateien verwendet, wird aber im resultierenden Catenda Hub-Dokument nicht angezeigt.

**Ein** Wenn die Dokumentkennung aktiviert ist, identifiziert dieser Block den Namen des Dokuments

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/08-blocks.png)

**Aus** Wenn die Dokumentkennung deaktiviert ist, identifiziert dieser Block den Namen der lokalen Datei.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/09-blocks.png)

**Deaktiviert** Die Dokumentkennung des Erweiterungsblocks ist immer aus, da jede Datei eine Erweiterung hat.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/10-blocks.png)

**Quelle** Was wird die Identifizierung des Namens der Datei/des Dokuments qualifizieren? _Standard:_ Text - dieser Block kann ein beliebiges Zeichen enthalten _Benutzerdefiniertes Feld:_ - Beschränken Sie die Zeichentypen, die Ihr Block mit benutzerdefinierten Feldern akzeptiert

**Länge** Wie viele Zeichen in diesem Block vorhanden sein können. Wenn dieses Feld leer gelassen wird, hat der Block eine variable Länge.

### 3.5 **Übermittlung einer Konvention**

![Abbrechen Benennungskonvention einreichen](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/11-br-submitting-a-convention.png)

Nach dem Absenden einer Namenskonvention kann diese [pro Ordner aktiviert werden](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) in [Dokumenteinstellungen](https://support.catenda.com/en/articles/7831371-document-settings).
