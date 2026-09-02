# Feilsøking for dialogboksen Last opp dokument

## 1. **Dokument finnes i mappen**

Hvis du har skriverettigheter til en mappe, men bare leserettigheter til et dokument, vil du ikke kunne legge til revisjoner i det dokumentet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qn4yk3x7/01-document-exists-in-folder.png)

Opprett et nytt dokument med denne revisjonen eller last opp revisjonen til et annet dokument.

## 2. **Kjørbare og skriptfiltyper**

Når en fil har en potensielt skadelig filtype, vil den ikke bli lastet opp. Dette er hvordan det kan se ut når du forsøker å laste opp en skadelig filtype:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qn4yk3x7/02-executable-and-script-filetypes.png)

Følgende filtyper som kan være potensielt skadelige er ikke tillatt. Se hvilke filtyper som ikke kan lastes opp i [denne](https://support.catenda.com/en/articles/4670320-previewing-file-types-on-catenda-hub) artikkelen.

## 3. **Filnavn avkortet**

Filer som velges for opplasting fra en ekstern stasjon som en USB-harddisk/USB-pinne eller en nettverksstasjon kan ha en begrensning på omkring 250 tegn i lengden på banen. Hvis banen til filen er for lang, kuttes slutten av filnavnet (før filtypen) av og erstattes med ~1. Dette er hvordan det ser ut når et filnavn blir avkortet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/qn4yk3x7/03-filename-cut-off.png)

Dette er ikke en begrensning i Catenda, men snarere en begrensning mellom nettleseren og operativsystemet. For å unngå å støte på dette problemet, kopier filene fra den eksterne plasseringen til den lokale maskinen din og last dem opp til Catenda derfra. Et bra sted å legge dem er typisk dashbordet der midlertidige filer kan oppdages og senere fjernes, eller ved roten C:// for å sikre at det er så mange tegn som mulig tilgjengelig i banelengden.
