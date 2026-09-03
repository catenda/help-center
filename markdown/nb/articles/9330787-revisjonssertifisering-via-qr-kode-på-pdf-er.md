# Revisjonssertifisering via QR-kode på PDF-er

Skriv ut dokumentrevisjoner med genererte QR-koder på papir slik at prosjektmedlemmer kan verifisere om papiret de har i hendene er fortsatt gjeldende.

Konfigurerte mapper kan identifiseres ved tanntakk-merket på [mappeikonet](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page#h_6af15c36b3). Dette er hvordan en revisjon med en generert QR-kode kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/01-intro.png)

## 1. **Mappekonfigurasjon**

QR-kode-stempling kan [aktiveres for konfigurerte mapper](https://support.catenda.com/en/articles/7831371-document-settings#h_166a269870) på dokumentsiden. _Nødvendig tilgang:_ Administrator

I konfigurerte mapper blir nye PDF-revisjoner i dokumenter som lastes opp, behandlet. Catenda søker i dokumentet etter QR-kode plassholder-bildet som finnes nedenfor. Hvis plassholdingen blir identifisert, genereres en QR-kode for revisjonen. _Nødvendig tilgang:_ Skrivetilgang til dokumentet

### 1.1 **Tildel QR-kode**

For å tildele QR-kode-stempling til en mappe, gå til [dokumentinnstillinger](https://support.catenda.com/en/articles/7831371-document-settings) som kan finnes som en underside av [dokumentsiden](https://support.catenda.com/en/articles/8204673-documents-page). I dokumentinnstillinger utvider du [mappeinnstillingmeny](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90). Dette er hvordan mappeinnstillingmenyen kan se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/02-assign-qr-code.png)

Mot bunnen kan rullegardinmenyen "Tildel QR-kode" finnes. Klikk på rullegardinmenyen og velg Ja for å konfigurere denne mappen.

_Konfigurasjonsarv_ Hvis en konfigurasjon er angitt i en overordnet mappe, vil alle dens undermapper arve konfigurasjonen.

## 2. **QR-kode plassholder-plassering**

Som nevnt i introduksjonen til denne artikkelen, for at en QR-kode skal genereres på en revisjon som lastes opp til en konfigurert mappe, vil Catenda søke etter QR-kode plassholder-bildet. QR-kode plassholder-bildet kan se ut omtrent slik:

<p class="intercom-align-center no-margin">[<img alt="Catenda QR-Code placeholder" src="https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/inline-8c4db2f4912c.png" width="150"/>](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)</p>

Klikk [her](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk) for å laste ned QR-kode plassholdingen

> **Advarsel:** Ikke kopier/lim inn dette bildet eller lagre som. Bildet kan se likt ut på tegningen, men blir ikke gjenkjent.

Klikk [her](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda) for å lese mer om hvordan du plasserer plassholdingen på en PDF. Dette er hvordan plassholdingen kan se ut når den er plassert i tittelblokken på en tegning:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/03-qr-code-placeholder-placement.png)

## 3. **Opplasting av revisjon med plassholder**

Last opp en ny revisjon av en PDF med plassholdingen til en mappe med QR-kode-tilordning. Dette gjelder bare publiserte revisjoner!!! Utkast eller delte PDF-er vil bare få en QR-kode generert etter at de er publisert.

### 3.1 **Revisjon QR-kode-generering**

Etter at QR-kode plassholdingen er plassert, kan PDF-en lastes opp som en ny revisjon til den konfigurerte mappen. Under opplastingen behandler Catenda bildene i dokumentet.

_Bytekrav_ De riktige bytene som tilhører de svarte og hvite pikslene i Catenda QR-kode plassholdingen må være til stede i riktig rekkefølge.

_Dimensjonskrav_ Bildet må ha en minimumsbredde og -høyde på 2 cm ganger 2 cm.

_Eksempel på generert QR-kode_ Dette er hvordan tittelblokken i eksemplet ovenfor kan se ut etter at PDF-en er behandlet og en QR-kode er lagt til:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/04-revision-qr-code-generation.png)

## 4. **Statusarbeidsflyt -** Publiser for å generere QR-kode

Uten statusarbeidsflyten blir alle revisjoner som lastes opp, umiddelbart publisert. Dokumenter blir bare skannet for QR-kode plassholdinger når de publiseres.

### 4.1 **Delte revisjoner kontra publiserte revisjoner**

Med statusarbeidsflytaktivering lastes nye revisjoner opp som delte revisjoner som et trinn før publisering. Når du ser på den delte revisjonen, kan du se originalsdokumentet før Catenda endret det med en generert QR-kode. Med statusarbeidsflyten skjer utskiftningen av plassholder QR-koden med den genererte QR-koden når en delt revisjon i en konfigurert mappe som har plassholder QR-koden publiseres.
