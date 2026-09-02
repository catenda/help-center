# Operasjoner på dokumentbibliotekselementer

Følgende emner er beskrevet i denne artikkelen:

## 1. **1. Mappeoperasjoner**

Dette er de forskjellige operasjonene som kan utføres på en mappe i henhold til tilgangsnivåene.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Operasjon</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Påkrevd tilgang</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vis mappeinnhold / del mappekoblingen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Les</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Opprett et dokument, legg til en undermappe, gi mappen nytt navn</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Skriv</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Flytt, slett, endre tilgangsinnstillinger (ACL)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Full tilgang</p></td></tr></tbody></table></div>

Følgende emner er beskrevet i denne delen:

### 1.1 **1.1 Påkrevd tilgang: Les**

_Standardatferd_ Alle medlemmer har minst skrivetilgang som standard. Et medlem kan ha lesetilgang til en mappe hvis den ble opprettet i en mappe der lesetilgang ble konfigurert, eller hvis lesetilgang ble konfigurert spesifikt for mappen. Mappen kan senere ha blitt flyttet, så dens tilgang trenger ikke nødvendigvis å være den samme som mappen den er i.

_Vis mappeinnhold_ Medlemmer med lesetilgang kan navigere til innholdet i en mappe. Ulik tilgang kan konfigureres til mappeinnholdet, så medlemmer med lesetilgang kan ikke ha tilgang til alle elementer i mappen.

_Del mappe_ Medlemmer med lesetilgang kan dele lenker til mapper med sharelink eller ved å lenke URL-en. Mottaker av sharelink kan ha annen tilgang og kan ikke se det samme innholdet i mappen. En offentlig kobling til en samling kan opprettes med mappeinnholdet, slik at hvem som helst kan laste ned samlingens innhold uavhengig av tilgangsinnstillinger.

### 1.2 **1.2 Påkrevd tilgang: Skriv**

_Standardatferd_ Alle medlemmer har minst skrivetilgang som standard.

_Opprett dokument i mappe_ Medlemmer med skrivetilgang til en mappe kan opprette nye dokumenter i den mappen.

_Legg til mappe i mappe_ Medlemmer med skrivetilgang til en mappe kan opprette nye mapper i den mappen.

_Gi mappen nytt navn_ Medlemmer med skrivetilgang til en mappe kan gi mappen nytt navn.

### 1.3 **1.3 Påkrevd tilgang: Full tilgang**

_Standardatferd_ Mappeeieren (oppretteren av mappen) og administratorer har full tilgang som standard.

_Flytt mappe_ Medlemmer med full tilgang kan flytte mapper til andre mapper. Mappeeiere (oppretteren av mappen) har ofte full tilgang og kan dermed flytte sine egne mapper. Medlemmer har ofte skrivetilgang til dokumenter opprettet av andre medlemmer. Medlemmer kan derfor ofte bare flytte mapper de opprettet, med mindre de er i en mappe der de har fått mer tilgang.

_Slett mappe_ Medlemmer med full tilgang kan slette en mappe uavhengig av hvilken tilgang som er angitt i mappen.

_Endre mappe-ACL_ Medlemmer med full tilgang til en mappe kan endre tilgangsinnstillingene for den mappen.

## 2. **2. Dokumentoperasjoner**

Dette er de forskjellige operasjonene som kan utføres på et dokument i henhold til tilgangsnivåene.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Operasjon</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Påkrevd tilgang</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Del en dokumentkobling</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Les</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Koble/avkoble objekter, rediger merkelapper, opprett, gi nytt navn, opprett en modell (IFC)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Skriv</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Flytt til en annen mappe, slett, endre ACL</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Full tilgang</p></td></tr></tbody></table></div>

> **Merknad:** Opprettelse eller fjerning av en modell fra et IFC-dokument krever også skrivetilgang til "opprettelse og fjerning av modeller" i prosjektinnstillinger.

Følgende emner er beskrevet i denne delen:

### 2.1 **2.1 Påkrevd tilgang: Les**

_Standardatferd_ Alle medlemmer har minst skrivetilgang som standard. Et medlem kan ha lesetilgang til et dokument hvis det ble lastet opp til en mappe der lesetilgang ble konfigurert, eller hvis lesetilgang ble konfigurert spesifikt for dokumentet. Dokumentet kan senere ha blitt flyttet, så dens tilgang trenger ikke nødvendigvis å være den samme som mappen det er i.

_Del dokument_ Dokumenter kan deles med sharelink eller ved å lenke URL-en. Mottaker av sharelink kan ha annen tilgang og kan ikke se de samme dokumentrevisjonene. En offentlig kobling til en samling kan opprettes med en spesifikk dokumentrevisjon, slik at hvem som helst kan laste ned samlingens innhold uavhengig av tilgangsinnstillinger.

### 2.2 **2.2 Påkrevd tilgang: Skriv**

_Standardatferd_ Alle medlemmer har minst skrivetilgang som standard.

_Koble/avkoble objekter_ Medlemmer med minst skrivetilgang kan koble og avkoble objekter til et dokument.

_Rediger merkelapper_ Medlemmer med minst skrivetilgang kan legge til og fjerne merkelapper fra et dokument.

_Opprett nytt dokument_ Medlemmer med minst skrivetilgang til overordnet mappe kan opprette dokumenter innenfor den mappen.

_Gi dokument nytt navn_ Medlemmer med minst skrivetilgang kan gi dokumenter nytt navn.

_Opprett modell_ Medlemmer med minst skrivetilgang til et dokument kan opprette en modell fra et ifc-dokument, slik at den vises på modellsiden. Utvidelse påkrevd: `.ifc` eller `.ifczip` _Ytterligere tilgang påkrevd:_ Skrivetilgang til opprettelse og fjerning av modeller i prosjektinnstillinger

_Fjern modell_ Medlemmer med minst skrivetilgang kan fjerne modellkoblingen fra et dokument som er knyttet til en modell, slik at den forsvinner fra modellsiden. _Ytterligere tilgang påkrevd:_ Skrivetilgang til opprettelse og fjerning av modeller i prosjektinnstillinger

### 2.3 **2.3 Påkrevd tilgang: Full tilgang**

_Standardatferd_ Dokumenteieren (oppretteren av dokumentet og ofte opplasteren av den første revisjonen) og administratorer har full tilgang som standard.

_Flytt dokument til en annen mappe_ Medlemmer med full tilgang kan flytte dokumenter til andre mapper. Dokumenteiere (oppretteren av dokumentet og ofte opplasteren av den første revisjonen) har ofte full tilgang og kan dermed flytte sine egne dokumenter. Medlemmer har ofte skrivetilgang til dokumenter opprettet av andre medlemmer. Medlemmer kan derfor ofte bare flytte dokumenter de opprettet, med mindre de er i en mappe der de har fått mer tilgang.

_Slett dokument_ Medlemmer med full tilgang kan slette et dokument uavhengig av hvilken tilgang som er angitt i mappen.

_Endre ACL_ Medlemmer med full tilgang til et dokument kan endre tilgangen til det dokumentet.

## 3. **3. Operasjoner for publisert revisjon**

Tabellen nedenfor relaterer operasjonene som kan utføres på en publisert revisjon til tilgangsnivåene. Som standard er alle nye revisjoner i dokumenter publisert. Hvis delte revisjoner er aktivert, opprettes alle nye revisjoner i dokumenter som delte revisjoner som standard.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Operasjon</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Påkrevd tilgang</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Forhåndsvisning i Catenda Hub, tilgang i apper (mobil / Catenda Site), 2D/3D-viser, last ned, sammenlign, legg til samling, del</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Les</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Trekk tilbake</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Full tilgang</p></td></tr></tbody></table></div>

Følgende emner er beskrevet i denne delen:

### 3.1 **3.1 Påkrevd tilgang: Les**

_Forhåndsvisning i Catenda Hub_ Medlemmer med minst lesetilgang til et dokument kan forhåndsvise publiserte revisjoner i Catenda Hub.

_Tilgang i applikasjoner_ Medlemmer med minst lesetilgang til et dokument kan få tilgang til publiserte revisjoner fra applikasjoner som får tilgang til API-en, for eksempel vår mobilapplikasjon, Catenda Site.

_2D/3D-viserknappar_ Medlemmer med minst lesetilgang til et dokument med publiserte 3D-dokumentrevisjoner kan bruke 2D- og 3D-knappane i viserkolonnen for å laste inn 3D-dokumentet i den respektive viseren. En av følgende er påkrevd:

- Dokument lenket til modell og siste revisjon er en vellykket behandlet `.ifc` eller `.ifczip`
- Siste revisjon er en punktsky
- Siste revisjon er en CityGML

_Del publisert revisjon_ Medlemmer med minst lesetilgang til et dokument med publiserte revisjoner kan dele lenker til revisjoner via sharelink eller ved å lenke URL-en. Mottaker av sharelink kan ha annen tilgang og kan ikke kunne se dokumentet. En offentlig kobling til en samling kan opprettes med en spesifikk publisert revisjon, slik at hvem som helst kan laste ned samlingens innhold uavhengig av tilgangsinnstillinger.

_Sammenlign_ Medlemmer med minst lesetilgang til et dokument med minst to PDF-revisjoner til stede kan bruke sammenligningsfunksjonen. Ytterligere tilgang påkrevd: Andre publiserte PDF-revisjon som finnes i dokumentet

_Last ned_ Medlemmer med minst lesetilgang til et dokument med publiserte revisjoner kan laste ned de publiserte revisjonene i dokumentet.

_Legg til samling_ Medlemmer med minst lesetilgang til et dokument med publiserte revisjoner kan legge til en publisert revisjon fra et dokument til en samling.

### 3.2 **3.2 Påkrevd tilgang: Full tilgang**

_Trekk tilbake_ Medlemmer med full tilgang til et dokument kan trekke tilbake publiserte revisjoner i dokumentet.

## 4. **4. Operasjoner for utkastrevisjoner - Arv**

Tabellen nedenfor relaterer operasjonene som kan utføres på en utkastrevisjoner til tilgangsnivåene. Utkastrevisjoner er bare tilgjengelige i prosjekter opprettet før 2. oktober 2025.

Følgende emner er beskrevet i denne delen:

### 4.1 **4.1 Påkrevd tilgang: Ingen tilgang**

_Tilgang i applikasjoner_ Bare publiserte revisjoner kan få tilgang fra applikasjoner som får tilgang til vår API, for eksempel vår mobilapplikasjon, Catenda Site.

_Legg til samling_ Bare publiserte revisjoner kan legges til i samlinger.

### 4.2 **4.2 Påkrevd tilgang: Les**

_Forhåndsvisning i Catenda Hub_ Medlemmer med minst lesetilgang til et dokument og lesetilgang til utkast i prosjektinnstillinger kan forhåndsvise utkastrevisjoner i Catenda Hub. _Ytterligere tilgang påkrevd:_ Lesetilgang til dokumentutkast i prosjektinnstillinger.

_Del utkastrevisjoner_ Medlemmer med minst lesetilgang til et dokument med utkastrevisjoner og lesetilgang til utkast i prosjektinnstillinger kan dele lenker til utkastrevisjoner via sharelink eller ved å lenke URL-en. Mottaker av sharelink kan ha annen tilgang og kan ikke kunne se dokumentet.

_Last ned_ Medlemmer med minst lesetilgang til et dokument med utkastrevisjoner og lesetilgang til utkast i prosjektinnstillinger kan laste ned utkastrevisjoner. Utkastrevisjoner kan lastes ned en og en ved å klikke på nedlastingsknappen i revisjonsområdet på høyre meny av revisjonen på dokumentforhåndsvisningssiden. _Ytterligere tilgang påkrevd:_ Lesetilgang til dokumentutkast i prosjektinnstillinger

### 4.3 **4.3 Påkrevd tilgang: Skriv**

_Forhåndsvisning i Catenda Hub_ _Ytterligere tilgang påkrevd:_ Dokumenteier

_Publiser_ I prosjekter der statusarbeidsflyt ble aktivert før 2. oktober 2025, er avkryssingsboksen for utkastrevisjoner aktivert som standard i opplastingsmenyen, men kan avmerkes for å laste opp en publisert revisjon i stedet.

## 5. **5. Delt revisjon**

Tabellen nedenfor relaterer operasjonene som kan utføres på en delt revisjon til tilgangsnivåene. Hvis delte revisjoner er aktivert, opprettes alle nye revisjoner i dokumenter som delte revisjoner som standard.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Operasjon</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Påkrevd tilgang (+ ekstra betingelse)</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Forhåndsvisning, del, last ned</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Les (+ "Vis delte revisjoner" merket av)</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Publiser</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Skriv (+ "Kan publisere" merket av)</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Trekk tilbake</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>"Vis delte revisjoner" merket av</p></td></tr></tbody></table></div>

> **Merknad:** Merknad: Bare publiserte revisjoner kan få tilgang fra apper eller legges til i samlinger.

Følgende emner er beskrevet i denne delen:

### 5.1 **5.1 Påkrevd tilgang: Ingen tilgang**

_Tilgang i applikasjoner_ Bare publiserte revisjoner kan få tilgang fra applikasjoner som får tilgang til vår API, for eksempel vår mobilapplikasjon, Catenda Site.

_Legg til samling_ Bare publiserte revisjoner kan legges til i samlinger.

### 5.2 **5.2 Påkrevd tilgang: Les**

_Forhåndsvisning i Catenda Hub_ Medlemmer med minst lesetilgang til et dokument med delte revisjoner og tilgang til visning av de delte revisjonene til et dokument kan forhåndsvise delte revisjoner i Catenda Hub. _Ytterligere tilgang påkrevd:_ "Vis delte revisjoner" merket av i dokumenttilgangsmeny

_Del delt revisjon_ Medlemmer med minst lesetilgang til et dokument med delte revisjoner og tilgang til visning av de delte revisjonene til et dokument kan dele lenker til delte revisjoner via sharelink eller ved å lenke URL-en. Mottaker av sharelink kan ha annen tilgang og kan ikke kunne se dokumentet.

_Last ned_ Medlemmer med minst lesetilgang til et dokument med delte revisjoner og tilgang til visning av de delte revisjonene til et dokument kan laste ned delte revisjoner. De siste delte revisjonene av dokumenter som er valgt i arbeidsområdefanen til dokumenttabellen, kan lastes ned med nedlastingshandlingen. Tidligere delte revisjoner kan lastes ned en og en ved å klikke på nedlastingsknappen i revisjonsområdet på høyre meny av revisjonen på dokumentforhåndsvisningssiden. _Ytterligere tilgang påkrevd:_ "Vis delte revisjoner" er merket av i dokumenttilgangsmeny

### 5.3 **5.3 Påkrevd tilgang: Skriv**

_Publiser_ Medlemmer med minst skrivetilgang til et dokument med delte revisjoner, tilgang til visning av de delte revisjonene til et dokument og tilgang til publisering av revisjoner i dokumentet kan publisere en av de delte revisjonene som har blitt lastet opp siden den siste publiserte revisjonen i dokumentet. _Ytterligere tilgang påkrevd:_ "Kan publisere" er merket av i dokumenttilgangsmeny

### 5.4 **5.4 Påkrevd tilgang: Full tilgang**

_Trekk tilbake_ Medlemmer med minst lesetilgang til et dokument med delte revisjoner og tilgang til visning av de delte revisjonene til et dokument kan trekke tilbake delte revisjoner i dokumentet. _Ytterligere tilgang påkrevd:_ "Vis delte revisjoner" er merket av i dokumenttilgangsmeny
