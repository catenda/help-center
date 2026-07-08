# QR-kode på PDF-er i Catenda

QR-koder kan konfigureres per mappe i [mappen konfigurering](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) av [dokumentinnstillinger](https://support.catenda.com/en/articles/7831371-document-settings).

Denne funksjonen gir brukere av Catenda muligheten til å kontrollere om Dokumenter de bruker er den nyeste versjonen ved å skanne QR-koden som er skrevet ut på PDF-en.

## 1. **Konfigurer QR-kode på Catenda Hub**

Tilordningen av QR-kode gjøres via mapper, noe som betyr at hver prosjektadministrator kan bestemme et utvalgt sett med mapper som skal ha denne funksjonen.

Dette er trinnene for å tilordne QR-kodefunksjonen til mapper i prosjektet ditt;

1. Under Dokumenter —> innstillinger, gå til **'mappekonfigurering'**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/01-setup-qr-code-on-catenda-hub.png)

2\. Klikk på pluss-tegnet ved siden av den ønskede mappen for å åpne mappen sin konfigurering, og under 'tilordne QR-kode' sier du **'ja'**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/02-setup-qr-code-on-catenda-hub.png)

Skanning av plassholdere og plassering av QR-koder vil kun finne sted i mapper med QR-kodetilordning;

> **Merk:** Når en overordnet mappe er Tildelt til, vil alle undermapper ha denne tilordningen. QR-koder kan Tildelt til enhver mappe når en overordnet mappe ikke allerede er Tildelt til.

## 2. Plassering av plassholderen i Dokumenter ditt

For å bruke denne funksjonen må du plassere **[QR-kodeplassholderen](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)**, levert av Catenda, på Dokumenter ditt og deretter laste opp til Catenda Hub. _Dimensjonskrav:_ Dette må ha en minimumsstørrelse på 2 cm x 2 cm.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/03-placing-the-placeholder-in-your-document.png)

Nedlastingslenken for QR-koden finner du her:

_[Nedlastingslenke](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)_

### 2.1 Plassering av QR-koden som filforfattter

Siden Dokumenter ikke kan endres etter at de er lastet opp til Catenda, er det viktig at plassholder-QR-koden plasseres på Dokumenter før den lastes opp til Catenda. Plassholderen kan plasseres på hvilket som helst lag unntatt annoteringlegt. For at Catenda skal gjenkjenne QR-koden, må den legges til som et bilde. Bildet i det publiserte Dokumenter må være nøyaktig det samme bildet som plassholder-bildet.

_PDF-optimalisering_ Mange programmer utfører optimaliseringstrinn for bedre visning og mindre filstørrelse. Disse trinnene kan endre antall byte i bildet, noe som gjør at Catenda ikke gjenkjenner det lenger. Her er noe informasjon om plassholderen som kan hjelpe med optimalisering. Pikseltettheten: 144 dpi Bildekomprimering: ZIP Bildet må være ett helt bilde. Noen optimaliserere kan dele bildet som en optimalisering. Vennligst sørg for at bildet er helt etter optimalisering.

_Archicad_ Når du plasserer QR-koden, bruk: Importer > interoperabilitet > flett fra fil > importer og åpne regneark > dra og slipp Hvis du åpner regnerket og drar og slipper PNG-en, endres oppløsningen og fungerer ikke.

### 2.2 Plassering av QR-koden på et eksisterende Dokumenter

Hvis du har et Dokumenter som du ikke opprettet, og du vil legge til QR-plassholderen før du laster det opp til Catenda Hub, må du redigere Dokumenter og legge til QR-plassholderen som et bilde.

### 2.3 Plassering av QR-koden et Catenda-Dokumenter

Hvis Dokumenter ditt allerede er på Catenda, må du legge til QR-plassholderen og laste opp en ny revision. Hvis du ikke har tilgang til et PDF-redigeringsprogram, kan du bruke [merkingsverktøyet for bilder](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6) til å legge til QR-plassholderen i Dokumenter ditt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/04-placing-the-qr-code-a-catenda-document.png)

For å lagre Dokumenter så QR-plassholderen vil bli gjenkjent, skriver du ut Dokumenter med [utskriftsknappen](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70) som finnes øverst til venstre i forhåndsvisningen av Dokumenter ditt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/05-placing-the-qr-code-a-catenda-document.png)

Dette åpner utskriftsdialogen til nettleseren din. Her er hva det kan se ut som for Google Chrome:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/06-placing-the-qr-code-a-catenda-document.png)

I utskriptsdialogen skriver du ut Dokumenter til PDF.

> **Merk 1:** QR-koden vil bare ende opp på innholdslaget hvis du skriver ut Dokumenter. Hvis du laster ned Dokumenter vil det være på annoteringlegt. **Merk 2:** Ved å skrive ut til PDF rasteriserer du innholdet i Dokumenter. Dette betyr at teksten ikke er søkbar når du laster den opp som en revision til Catenda.

Den utskrevne PDF-en med plassholderen kan nå lastes opp som en ny revision til Catenda. For å holde revisjonhistorikken din ren, kan det være lurt å trekke tilbake den forrige revisjonen uten QR-koden.

## 3. **Publisering med QR-koder**

1. Last opp en ny revision av en PDF med plassholderen til en mappe med QR-kodetilordning
2. Under publisering vil PDF-en bli skannet for plassholderen og erstattet med en QR-kode (generert for denne revisjonen)
3. Den nylig genererte QR-koden vil bli en del av PDF-en, som kan vises/skannes på Catenda Hub og/eller lastes ned.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/07-publishing-with-qr-codes.png)

Her er et eksempel på plasseringen av QR-kodeplassholderen og resultatene etter lasting opp til Catenda Hub. 1\. Plassholderen i tittelblokken til en tegning. **Klar for lasting opp.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/08-publishing-with-qr-codes.png)

2\. Plassholderen i tittelblokken erstattes med den genererte QR-koden. **Klar for verifisering.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/09-publishing-with-qr-codes.png)

### 3.1 **Dokumenter-Historikk**

Etter å ha lastet opp et Dokumenter med en plassholder-QR-kode, kan du se at den har blitt prosessert i Dokumenter-historikken til [høyremeny](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/10-document-history.png)

Hvis genereringen av QR-koden din har mislyktes, kan det være fordi QR-koden din var mindre enn 2 cm x 2 cm eller den ble plassert som en merknad i stedet for et bilde.

_Flatting av merknader_ Noen programvare tillater deg å flate merknader som tillater plassholderfunksjonen å bli prosessert. Her er noen eksempler:

_PDF X-change_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/11-document-history.png)

_Adobe Acrobat_

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3d7d02c461d3.png" width="300"/> --> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3398dc9eef22.png" width="300"/>

_BlueBeam Revu_ Når du plasserer plassholderen i BlueBeam Revu og lagrer Dokumenter, vil det bli lagt til som en merknad. Det er mulig å flate QR-koden for å gjøre den til en del av innholdslaget i Dokumenter, men selv når du lagrer det regelmessig eller bruker alternativer for redusert filstørrelse, vil QR-koden bli endret og vil ikke fungere med Catenda. For å gjøre QR-koden kompatibel med Catenda, gjør du i stedet: Skriv ut Dokumenter med BlueBeam-driveren:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/12-document-history.png)

I «Lagre som»-dialogen velger du ZIP-grafikk og aktiverer etterbehandling. Dette er fordi komprimeringsalgoritmen som brukes for plassholderen er ZIP.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/13-document-history.png)

I etterbehandlingsmenyen velger du alternativet Kombinere tilstøtende bilder. Dette er fordi bildet vanligvis vil bli delt i to, så det kombinerer det igjen. Hvis sidestørrelsen din ikke finnes som et standardalternativ, kan du legge til din egen tilpassede her:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/14-document-history.png)
