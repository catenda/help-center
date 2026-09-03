# Ich habe eine große IFC-Datei. Sollte ich Solibri Optimizer vor dem Hochladen der Dateien zu Catenda Hub verwenden?

Die Antwort ist nein. Wenn Ihre Datei zu groß wird, ist es besser, die Dateien einfach [vor dem Hochladen zu komprimieren](https://support.bimsync.com/hc/en-us/articles/360009995879). Solibri Optimizer kann die Datei in einigen Fällen beschädigen, sodass sie nicht durch die verschiedenen Importschritte in Catenda Hub gelangt. Eine optimierte Datei wird in Catenda Hub nicht schneller zu durchsuchen sein, da wir Informationen unabhängig vom Zustand der importierten Datei in optimierten Formaten speichern.

Wenn eine Datei beim Hochladen fehlschlägt, überprüfen Sie bitte den Dateiheader auf Spuren von Solibri Optimizer (öffnen Sie sie in Editor oder ähnlich und schauen Sie sich die ersten 10 Zeilen des Dateiheaders an). Wenn die fehlgeschlagene Datei optimiert wurde, versuchen Sie es stattdessen mit der ursprünglichen Datei.

![mceclip0.png](https://raw.githubusercontent.com/catenda/help-center/main/images/p8sgh6tt/01-intro.png)

(diese Datei wurde mit Solibri Optimizer bearbeitet)
