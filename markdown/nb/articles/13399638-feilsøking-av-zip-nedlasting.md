# Feilsøking av zip-nedlasting

Når en mappe eller flere enn ett element lastes ned i dokumentseksjonen, vises en dialog mot nederst til venstre på skjermen. I denne dialogen vises fremdriften for forberedelsen av zip-filen som skal lastes ned.

## 1. **Reserverte tegn i banen**

Hvis en mappe har tegnet `/` i mappenavnet, gjenkjennes dette som en bane i zip-filen, og mappen deles inn i flere mapper som alle er inni hverandre. Alle elementer i mappen havner i den siste av disse mappene. For eksempel mappen `This/is/a/folder` med dokumentet `This-is-a-document.pdf` lastes ned til en zip med følgende mappestruktur: This is a folder This-is-a-document.pdf

## 2. **Revisjoner som ikke kan lastes ned**

### 2.1 **Utkastrerevisjoner (Legacy)**

Utkastrerevisjoner kan bare lastes ned individuelt fra høyremenyen for en revisjon. Hvis bare utkastrerevisjoner velges, forberedes en zip, men den blir tom. Den nye typen revisjoner for å erstatte dette er delte revisjoner som, akkurat som vanlige publiserte revisjoner, kan lastes ned med handlingen for nedlasting av dokumenttabell uten problemer.

### 2.2 **Tilbaketrukne revisjoner**

Hvis den siste revisjonen av ett av dokumentene i utvalget er blitt trukket tilbake, kan en advarsel vises som informerer brukeren om at noen filer ikke vil bli lastet ned.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/169yxgzv/01-withdrawn-revisions.png)

Trykk fortsett for å fortsette forberedelsen, eller avbryt for å stoppe nedlastingen.

## 3. **Ikke ennå skannet for virus**

Hvis filer som nylig er lastet opp, forsøkes lastet ned, er det mulig at de ikke er skannet for virus ennå.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/169yxgzv/02-not-yet-scanned-for-virus.png)

Hvis det har gått en stund siden filene som skal lastes ned, ble lastet opp, kontakt oss om filer som ikke er skannet. Trykk fortsett for å fortsette forberedelsen, eller avbryt for å stoppe nedlastingen.

## 4. **Feil under nedlastingsforbereding**

Hvis noe går galt ved forberedelsen av denne zippede filen, kan følgende feil vises:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/169yxgzv/03-download-preparation-error.png)

Hvis du ser denne skjermen, kontakt oss.
