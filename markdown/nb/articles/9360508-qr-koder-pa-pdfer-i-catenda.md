# QR-Koder på PDFer i Catenda

Denne funksjonen gir brukere til Caenda en funksjon for å sjekke om dokumentet de bruker er den siste versjonen ved å scanne QR-koden printet på PDFen.

For å kunne ta i bruk denne funksjonen vil du måtte plassere en **[placeholder QR-kode](https://drive.google.com/file/d/1SbGcp8hC8l7854HOCZuI8o-WIBMWrsyF/view)** levert av Catenda på ditt dokument for å så laste opp dokumentet til Catenda Hub. Koden må ha minstestørrelse av 2cm ved 2cm.

![](https://downloads.intercomcdn.com/i/o/1129210747/3afe134405c9c151b8ed9936/image.png?expires=1781092800&signature=c2ea1933f269989980b29fa6c815f2115ec45196d7a904078bb197360e86fddf&req=dSElH8t%2FnYZbXvMW3nq%2BgZCIR8olrrgqRy31Ne2%2BudU3rI2Jb6gXfXlYW6X%2F%0AXNTNl9vBqIGhWJFcubOVyA7Cdis%3D%0A)

**[Placeholder QR-kode](https://drive.google.com/file/d/1SbGcp8hC8l7854HOCZuI8o-WIBMWrsyF/view)**

### Still inn QR-kode på Catenda Hub

QR-kode tildelingen er satt opp via mapper som betyr du kan bestemme at funksjonen skal være aktivert for en bestemt rekke med mapper.

_Tilgang påkrevd:_ Prosjektadministrator.

Under finner du steg for å aktivere QR-kode funksjonen til mapper i ditt prosjekt.

1. På dokumentinnstillinger siden, gå til **[mappekonfigurasjon](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90)**

![](https://downloads.intercomcdn.com/i/o/1058260520/dddd82c067f7b46accb5b32c/image.png?expires=1781092800&signature=e7941acca8aedcea4e848c67e0007a4e09578fab49b5e5c9a824b181ac99454a&req=dSAiHst4nYRdWfMW3nq%2BgRkR2h4rS0XQNc9lbtEQewqJ6NZ6VLakXmSCbXYB%0AVxWNDann97ZsWaqAzYsRKbOcTVk%3D%0A)

2. Klikk på pluss knappen ved siden av mappen du ønsker å aktivere funksjonen for for å åpne mappekonfigurasjonen. Under tildel QR kode si **ja**.

![](https://downloads.intercomcdn.com/i/o/1058261375/a52f5da19606885304d919f1/image.png?expires=1781092800&signature=4c64a3d24c6c5463ebe93bbe1059a2dbb1bb4338b4ad72cfa53803d88d531b46&req=dSAiHst4nIJYXPMW3nq%2BgSrY7yhARKJj3Bos80hgsCYYWj1IyWqj837ROIDg%0ADGVbmygamuvFA2FrHAL5c1SXMPw%3D%0A)

Scanningen av placeholdere og plasseringen av QR-koder vil bare foregå i mapper med QR-kode tildelingen.

> **Merk:** Så snart en foreldermappe er tildelt vil alle under-mapper ha denne tildelingen. QR-koder kan tildeles til enhver mappe så lenge forelder mappen ikke allere er tildelt.

### Publisering med QR-koder

1. Last opp en ny revisjon av en PDF med placeholder i en mappe med QR-kode tildeling
1. Under publiseringen vil PDFen scannes for placeholder og erstattes med en QR-kode (generert for denne revisjonen)
1. Den nylig genererte QR-koden vil være del av PDFen som kan vises/scannes på Catenda Hub og/eller lastes ned.

![](https://downloads.intercomcdn.com/i/o/1058270845/bbf3025f7cf4ce2c44e5ff3a/image.png?expires=1781092800&signature=87316e36cd478d482c98ab3fde729320404c1178d31708e40ca8cb797844e67a&req=dSAiHst5nYlbXPMW3nq%2BgcetveFGeYCsO6kaiNDTAeDsrR86FZzvPBsliNcU%0AoJizxECcx70jjX9lsLKDjBubHOo%3D%0A)

Her er et eksempel på plasseringen av placeholderen til QR-koden og resultatet etter å ha lastet den opp til Catenda Hub. 1. Placeholder i tittel delen av tegningen. **Klar for opplasting**.

![](https://downloads.intercomcdn.com/i/o/1128898386/b042fd79d7595f8d12a0159c/image.png?expires=1781092800&signature=7b305493e3afeef99f797c6bde7577f9ee147be9259ffd5234d136ceb18b19a5&req=dSElHsF3lYJXX%2FMW3nq%2BgcCYNHtVa2O6MpBCTIpzHdyIjlAArQsK42e3eW8C%0ARJ8ENFmJfkyirg6BcnLQ%2FlGVRgM%3D%0A)

2. Placeholder i tittel delen er erstattet med den genererte QR koden. **Klar for bekreftelse**.

![](https://downloads.intercomcdn.com/i/o/1129687828/6fba8f5b78f9f26b6c0e5b25/image.png?expires=1781092800&signature=55a085321bf04009ffc5682bedfb937e1a8a745978110ea5fa2e653c230c60eb&req=dSElH892moldUfMW3nq%2BgZOaMeorej4wNegl5eWFN3XW6bJCLqd8omIpfqDg%0AO6V0qLi3tjmDOiAbb2n%2BOrLzNCo%3D%0A)

### Bekreftelse av siste revisjon

Scanning av QR-koden med din mobile enhet vil ta deg til bekreftelse siden hvor følgende resultater sukker opp angående på versjonen til PDFen.

1. Din revisjon er siste versjon til PDFen: **Dokument gjeldende**
1. Din revisjon er en eldre versjon av PDFen: **Dokument ugyldig**
1. Du scannet en placeholder: **Du scannet en placeholder, dette dokumentet er ikke publisert.**

    <div class="intercom-container"><img height="684" src="https://downloads.intercomcdn.com/i/o/1128836302/b5ed664002c909cad1388c1c/image.png?expires=1781092800&amp;signature=e32a0bc159c2fe53c0580cf78540908f18b726e36d6e988f6fd07bba7b2f7069&amp;req=dSElHsF9m4JfW%2FMW3nq%2BgRAbWSa0uwekHXdmw0dniPvD%2F48H6GJmWGPMPCrC%0AngeKuBJW%2FPMavpOc%2Btwvf9PFqVY%3D%0A" style="height: auto;" width="1079"/></div>
