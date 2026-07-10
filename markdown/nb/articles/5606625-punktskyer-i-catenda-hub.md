# Punktskyer i Catenda Hub

> Oppdag hvordan du kan dra nytte av laserskanning og LIDAR-teknologier i Catenda Hub.

> **Merk:** Last ned en eksempelfil fra [her](https://drive.google.com/file/d/1G8U916oihDl5qHrTfQaVHxDeLsbq1ulG/view?usp=sharing).

Punktskydatasett (PC) kan visualiseres i Catenda Hub. Individuell PC kan forhåndsvises i dokumentomådet. Flere PC kan lastes inn i [3D-visningen](https://support.catenda.com/en/articles/8227211-3d-viewer). I 3D-visningen kan PC vises sammen med andre 3D-dokumentformat som IFC-modeller og GML-filer.

Se nedenfor ulike innstillinger for å vise dataene dine:

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p>Adaptiv - Sparsom - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-05a450dc777f.png" style="height: auto;" width="3839"/></div></td><td><p>Adaptiv - Tett - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-196a1135014a.png" style="height: auto;" width="3839"/></div></td></tr><tr><td><p>Fast - Tett - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-66e21551bbef.png" style="height: auto;" width="3834"/></div></td><td><p>Fast - Sparsom - Intensitet</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-4a2046c8eaf1.png" style="height: auto;" width="3839"/></div></td></tr></tbody></table></div>

## 1. **Dokumentomådesforhåndsvisning**

PC-data i følgende to filformat kan forhåndsvises på Catenda.

- `*.e57`
- `*.las`

PC kan lastes opp som ethvert annet dokument i dokumentomådet. For disse to filformatene kan filer opp til 25 GB lastes opp til dokumentomådet. Flere filer kan lastes inn i dokumentomådet og vises sammen i 3D-visningen.

### 1.1 **Opplasting av PC-data**

Det anbefales å bruke [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) eller å komprimere PC-filen din til en zippet mappe og bruke [zip-importen](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) for å laste opp PC-en din. Disse metodene vil hjelpe deg å spare tid da opplastingsfilstørrelsen blir mindre, og vil også minimalisere risikoen for nettverksfeil da filen blir lastet opp raskere

Etter at du laster opp en PC til dokumentomådet, vil dokumentforhåndsvisningen begynne å behandle. Mens forhåndsvisningen behandles, vil du se en grå stolpe mot toppen av dokumentforhåndsvisningen din.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/01-uploading-pc-data.png)

Varigheten av forhåndsvisningsbehandlingen avhenger av størrelsen på PC. Behandlingen tar 1 time per GB, men det kan være mer eller mindre avhengig av punktskyen.

Når forhåndsvisningen er ferdig behandlet, klikk på dokumentet for å vise PC-en din i dokumentforhåndsvisningen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/02-uploading-pc-data.png)

### 1.2 **Delte PC-revisjoner**

Hvis [revisjonspublisering](https://support.catenda.com/en/articles/9874698-revision-publishing-iso-19650) har blitt aktivert for prosjektet, vil punktskyen ha blitt lastet opp som en delt revisjon. Delte PC-revisjoner kan bare forhåndsvises i dokumentomådet. For å kunne laste PC-en inn i 3D-visningen, må revisjonen publiseres. Individuelle delte revisjoner kan publiseres med publiseringshandlingen i høyre meny på dokumentforhåndsvisningen. Flere delte revisjoner kan publiseres med handlingen valgte elementer i dokumentstrukturen. Når du publiserer en revisjon, vil forhåndsvisningen for den publiserte revisjonen begynne å behandle.

### 1.3 **Publiserte PC-revisjoner**

Etter at forhåndsvisningen av en publisert PC-revisjon har blitt behandlet, vil en 3D-knapp vises i viserkolonnen i dokumenttabellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/03-br-published-pc-revisions.png)

3D-knappen vil laste den siste publiserte revisjonen av dokumentet inn i 3D-visningen.

Hvis du har valgt ett eller flere dokumenter med 3D-dokumenter som PC, IFC eller GML-dokumenter, vil du også se 3D-dokumenthandlingen i handlingsmenyene for valgte elementer i dokumenttabellen. På denne måten kan du laste inn de siste revisjonene av flere 3D-dokumenter i 3D-visningen samtidig.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/04-br-published-pc-revisions.png)

I et dokument med minst én publisert PC-revisjon som er ferdig behandlet, vil du kunne se 3D-handlingen i handlingsmenyenen mot øvre høyre.

> **Merk:** 3D-handlingen vil laste den siste publiserte revisjonen av dokumentet inn i 3D-visningen. Selv om du ser på en tidligere revisjon.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/05-br-published-pc-revisions.png)

## 2. **3D-visningsforhåndsvisning**

Etter å ha klikket på 3D-knappen, vil PC-poengene begynne å laste inn i 3D-visningen. 3D-visningen av en PC kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/06-3d-viewer-preview.png)

Mot toppen av 3D-visningen kan en grønn lastestolpe ses. Denne lastestolpen indikerer hvor mange poeng som har blitt lastet inn i 3D-visningen for den nåværende kameraposisjonen og vinkelen. Lastestolpen kan endres hvis du roterer rundt, da poeng kan forsvinne fra visningen og lastes ut, eller flere poeng kan komme innenfor rekkevidde og begynne å laste inn.

Og etter noen justeringer med zoom og posisjoner kan PC-forhåndsvisningen se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/07-3d-viewer-preview.png)

## 3. **3D-visningsinnstillinger**

I denne delen vil vi se på innstillingene i Catenda Hub som vil tillate deg å få den beste opplevelsen med PC-en din.

> **Merk:** Før du konfigurerer 3D-visningen, kontroller at applikasjonen Catenda er åpnet i er konfigurert [som anbefalt](https://support.catenda.com/en/articles/6921941-hardware-recommendation).

Innstillinger som kan brukes til å konfigurere punktskyer er plassert på to steder.

### 3.1 **1. Punktbudsjett:**

Punktbudsjettet kan konfigureres i [3D-visningsinnstillingene](https://support.catenda.com/en/articles/5784718-3d-viewer-settings) som finnes i tannhjulikonet mot øvre høyre av 3D-visningen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/08-1-point-budget.png)

I menyen for 3D-visningsinnstillinger kan punktbudsjettet justeres fra 100 000 opp til 10 000 000. Innlasting av flere poeng kan ta mer tid og kan kreve mer ressurser fra systemet ditt. Ved å laste inn flere poeng kan punktskyen vises i høyere troskyldigheit. Se den samme visningen med: 100 000 poeng

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/09-1-point-budget.png)

1 000 000 poeng

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/10-1-point-budget.png)

10 000 000 poeng

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/11-1-point-budget.png)

### 3.2 **2. Revisjonsveger, og individuelle PC-innstillinger:**

Øverst til venstre i 3D-visningen vil du finne [Revisionsvelegeren](https://support.catenda.com/en/articles/4670246-accepting-an-invitation-to-join-a-project).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/12-2-revision-selector-and-individual-pc-settings.png)

I [modellmenyen](https://support.catenda.com/en/articles/4670279-revision-selector#h_180a64490d) vil du være i stand til å finne de individuelle [3D-dokumentene](https://support.catenda.com/en/articles/4670279-revision-selector#h_fce60074ef) som du har lastet inn i 3D-visningen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/13-2-revision-selector-and-individual-pc-settings.png)

Punktskyer kan konfigureres i revisionsvelegeren ved å klikke på tannhjulikonet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/14-2-revision-selector-and-individual-pc-settings.png)

Slik kan innstillingsmenymen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/15-2-revision-selector-and-individual-pc-settings.png)

_Attributt_ _RGBA_ - Standard Vis PC-poeng med fargene deres

_Attributtintensitet_ Intensitetsalternativet kan brukes når poengene ikke inkluderer farger. For eksempel når punktskyen ble fanget opp i en tunnel eller et mørkt rom.

_Opasitet_ Når modeller vises sammen med punktskyer, kan det være nødvendig å dempe poengene for å få en bedre forståelse av visningspunktet.

_Punktstørrelse_ _Adaptiv_ - Standard Jo nærmere et punkt er kameraet, desto større er det. Poeng som er i visningen, lastes inn i minnet. Poeng som beveger seg ut av visningen, lastes ut av minnet.

> **Merk:** Kontroller at maskinvaren og programvaren Catenda er åpnet på er konfigurert [som anbefalt](https://support.catenda.com/en/articles/6921941-hardware-recommendation) da dette kan påvirke hvilken type punktstørrelse innlasting enheten din kan håndtere.

_Punktstørrelse Fast størrelse_ Poeng som har blitt lastet inn, vil holde seg i minnet med dette alternativet. Med mange poeng vil du merke at rotasjon kan bli forsinket og bevegelse kan bli bremset når du begynner å komme nærmere antall poeng som systemet ditt kan håndtere. Du kan også merke at det tar lengre og lengre tid å laste inn nye poeng når du kommer nærmere grensen for enheten din. Poeng laster nærmest kameraet først. Før du laster punktskyen fra dokumentomådet, sørg for å posisjonere kameraet til der du vil at poengene skal lastes inn. Hvis dette er en kameraposisjon som du planlegger å bruke oftere med denne punktskyen, vurder å opprette et bokmerke eller et øyeblikksbildei et emne som du kan spille for å vende tilbake til denne posisjonen.

_Punkttetthetskontroll_ Tetthetskontrollen hjelper deg med å gjøre den endelige innstillingen. Det finnes ingen regel for den korrekte verdien, det vil avhenge av dataene du laster opp (størrelse på datasettet, punkttetthet, type skanning osv.). Vår anbefaling: Last inn punktskyen, og vent en kort stund, når nok poeng er vist, juster innstillingene om nødvendig.

[YouTube-video](https://www.youtube.com/embed/n9pztkRPxoc?rel=0)
