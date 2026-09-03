# QR-kode på PDF-er i Catenda

QR-koder kan konfigureres per mappe i [mappe-konfigurasjonen](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) for [dokumentinnstillinger](https://support.catenda.com/en/articles/7831371-document-settings).

Denne funksjonen gir Catenda-brukere muligheten til å sjekke om dokumentet de bruker er den siste versjonen, ved å skanne QR-koden som er skrevet ut på PDF-en.

## 1. **Konfigurer QR-kode på Catenda Hub**

QR-kodetildelingen gjøres via mapper, noe som betyr at hver prosjektadministrator kan bestemme hvilke mapper som skal ha denne funksjonen.

Dette er trinnene for å tildele QR-kodefunksjonen til mapper i prosjektet ditt;

1. Under Dokumenter —> innstillinger, gå til **'mappe-konfigurasjon'**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/01-setup-qr-code-on-catenda-hub.png)

2\. Klikk på plusstegnet ved siden av ønsket mappe for å åpne mappe-konfigurasjonen, og under 'tilordne QR-kode' skriver du **'ja'**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/02-setup-qr-code-on-catenda-hub.png)

Skanningen av plasseholdere og plasseringen av QR-koder vil bare finne sted på mapper med QR-kodetilordning;

> **Merk:** Når en overordnet mappe er tilordnet, vil alle undermapper få denne tilordningen. QR-koder kan tilordnes til en mappe når en overordnet mappe ikke allerede har blitt tilordnet.

## 2. Plassering av plassehold i dokumentet ditt

For å bruke denne funksjonen må du plassere **[QR-kodens plassholder](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)**, levert av Catenda, på dokumentet ditt og deretter laste det opp til Catenda Hub. _Dimensjonskrav:_ Dette må ha en minimumsstørrelse på 2 cm x 2 cm.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/03-placing-the-placeholder-in-your-document.png)

Nedlastingskoblingen for QR-koden finner du her:

_[Nedlastingskobling](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)_

### 2.1 Plassering av QR-kode som forfatter

Siden dokumenter ikke kan endres etter at de lastes opp til Catenda, er det viktig at QR-kodens plassholder er plassert på dokumentet før det lastes opp til Catenda. Plasseholderen kan plasseres på hvilket som helst lag unntatt annoteringslaget. For at Catenda skal gjenkjenne QR-koden, må den legges til som et bilde. Bildet i det publiserte dokumentet må være nøyaktig samme bilde som plassholderbildet.

_PDF-optimalisering_ Mange programmer utfører optimaliseringstrinn for bedre visning og reduksjon av filstørrelse. Disse trinnene kan endre antall byte i bildet, noe som gjør at Catenda ikke gjenkjenner det lenger. Her er litt informasjon om plasseholderen som kan hjelpe med optimalisering. Pikseletthet: 144 dpi Bildekomprimering: ZIP Bildet må være ett helt bilde. Noen optimaliserere kan dele bildet som en optimalisering. Kontroller at bildet er helt etter optimalisering.

_Archicad_ Når du plasserer QR-koden, vennligst bruk: Importer > interpobility > slå sammen fra fil > importer og åpne regneark > dra og slipp Hvis du åpner regnearket og drar og slipper PNG-en, endres oppløsningen og den fungerer ikke.

### 2.2 Plassering av QR-kode på eksisterende dokument

Hvis du har et dokument som du ikke opprettet, og du vil legge til QR-plassholdingen før du laster det opp til Catenda Hub, må du kontrollere at du redigerer dokumentet og legger til QR-plassholdingen som et bilde.

### 2.3 Plassering av QR-kode på Catenda-dokument

Hvis dokumentet ditt allerede er på Catenda, må du legge til QR-plassholdingen og laste opp en ny revisjon. Hvis du ikke har tilgang til et PDF-redigeringsprogram, kan du bruke [bildemerkeannotasjonsverktøy](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_6e3ac983b6) for å legge til QR-plassholdingen i dokumentet ditt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/04-placing-the-qr-code-a-catenda-document.png)

For å lagre dokumentet slik at QR-plassholdingen blir gjenkjent, skriver du ut dokumentet med [utskriftsknappen](https://support.catenda.com/en/articles/5001165-document-preview-and-annotations#h_709cb0ed70) som finnes i øvre venstre hjørne av dokumentforhåndsvisningen din.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/05-placing-the-qr-code-a-catenda-document.png)

Dette åpner utskriftsdialogen i nettleseren din. Her er et eksempel på hvordan det kan se ut for Google Chrome:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/06-placing-the-qr-code-a-catenda-document.png)

I utskriftsdialogen skriver du ut dokumentet til PDF.

> **Merk 1:** QR-koden vil bare havne på innholdslaget hvis du skriver ut dokumentet. Hvis du laster ned dokumentet, vil det være på annoterungslaget. **Merk 2:** Ved å skrive ut til PDF rasteriserer du innholdet i dokumentet. Dette betyr at teksten ikke vil være søkbar når du laster den opp som en revisjon til Catenda.

Den utskrevne PDF-en med plassholdingen kan nå lastes opp som en ny revisjon til Catenda. For å holde revisjonsloggen din ren kan du velge å trekke tilbake forrige revisjon uten QR-koden.

## 3. **Publisering med QR-koder**

1. Last opp en ny revisjon av en PDF med plassholdingen til en mappe med QR-kodetilordning
1. Under publisering vil PDF-en bli skannet etter plassholdingen og erstattet med en QR-kode (generert for denne revisjonen)
1. Den nylig genererte QR-koden blir en del av PDF-en, som kan vises/skannes på Catenda Hub og/eller lastes ned.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/07-publishing-with-qr-codes.png)

Her er et eksempel på plasseringen av QR-kodens plassholder og resultatene etter opplasting til Catenda Hub. 1\. Plassholder i tittelblokkene på en tegning. **Klar for opplasting.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/08-publishing-with-qr-codes.png)

2\. Plassholder i tittelblokk erstattes med den genererte QR-koden. **Klar for verifisering.**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/09-publishing-with-qr-codes.png)

### 3.1 **Dokumenthistorikk**

Etter at du har lastet opp et dokument med en QR-kode-plassholder, kan du se at det har blitt behandlet i dokumenthistorikken til [høyre informasjonsmeny](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/10-document-history.png)

Hvis genereringen av QR-koden har mislyktes, kan det skyldes at QR-koden var mindre enn 2 cm x 2 cm eller at den ble plassert som en annotering i stedet for et bilde.

_Flatterer annoteringar_ Noen programvare lar deg flattere annoteringar som tillater at plassholdingen blir behandlet. Her er noen eksempler:

_PDF X-change_

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/11-document-history.png)

_Adobe Acrobat_

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3d7d02c461d3.png" width="300"/> --> <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/inline-3398dc9eef22.png" width="300"/>

_BlueBeam Revu_ Når du plasserer plassholdingen i BlueBeam Revu og lagrer dokumentet, blir det lagt til som en annotering. Det er mulig å flattere QR-koden for å gjøre den til en del av dokumentets innholdslag, men selv når du lagrer den normalt eller ved å bruke alternativet for redusert filstørrelse, vil QR-koden endres og vil ikke fungere med Catenda. For å få QR-koden til å fungere med Catenda, gjør du i stedet: Skriv ut dokumentet med BlueBeam-driveren:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/12-document-history.png)

I dialogboksen Lagre som velger du ZIP-grafikk og aktiverer etterbehandling. Dette er fordi komprimeringalgoritmen som brukes for plassholdingen er ZIP.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/13-document-history.png)

I menyen for etterbehandling velger du alternativet Kombiner tilstøtende bilder. Dette er fordi bildet normalt vil bli delt i to, så det kombineres tilbake sammen. Hvis sidestørrelsen din ikke finnes som et standardalternativ, kan du legge til din egen tilpassede her:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/c86kfdqw/14-document-history.png)
