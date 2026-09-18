# Punktskyer i Catenda Hub

> Oppdag hvordan du kan dra nytte av laserskann og LIDAR-teknologier i Catenda Hub.

> **Merk:** Last ned en eksempelfil fra [her](https://drive.google.com/file/d/1G8U916oihDl5qHrTfQaVHxDeLsbq1ulG/view?usp=sharing).

Punktskydataset (PC) kan visualiseres inne i Catenda Hub Individuelle PC kan forhåndsvises inne i dokumentområdet. Flere PC kan lastes inn i [3D-viseren](https://support.catenda.com/en/articles/8227211-3d-viewer). I 3D-viseren kan PC vises sammen med andre 3D-dokumentformater som IFC-modeller og GML-filer.

Se nedenfor forskjellige innstillinger for å vise dataene dine:

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="padding: 8px;"><p>Adaptiv - Sparsom - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-05a450dc777f.png" style="height: auto;" width="3839"/></div></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>Adaptiv - Tett - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-196a1135014a.png" style="height: auto;" width="3839"/></div></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Fast - Tett - RGB</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-66e21551bbef.png" style="height: auto;" width="3834"/></div></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Fast - Sparsom - Intensitet</p><div class="intercom-container"><img height="2159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/inline-4a2046c8eaf1.png" style="height: auto;" width="3839"/></div></td></tr></tbody></table></div>

## 1. **Forhåndsvisning av dokumentseksjon**

PC-data av de følgende to filformatene kan forhåndsvises på Catenda.

- `*.e57`
- `*.las`

PC kan lastes opp som ethvert annet dokument i dokumentseksjonen. For disse to filformatene kan filer på opptil 25 GB lastes opp til dokumentseksjonen. Flere filer kan lastes inn i dokumentseksjonen og vises sammen i 3D-viseren.

### 1.1 **Opplasting av PC-data**

Det anbefales å bruke [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) eller komprimere PC-filen til en zippet mappe og bruke [zip-import](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) for å laste opp PC-en din. Disse metodene vil hjelpe deg å spare tid ettersom opplastingsfilstørrelsen vil være mindre og minimere risikoen for en nettverksfeil da filen lastes opp raskere

Etter at du laster opp en PC til dokumentseksjonen, starter dokumentforhåndsvisningen å behandle. Mens forhåndsvisningen behandles, vil du se en grå stolpe øverst i dokumentforhåndsvisningen din.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/01-uploading-pc-data.png)

Varigheten for forhåndsvisningsbehandling avhenger av størrelsen på PC-en. Behandlingen tar 1 time per GB, men det kan være mer/mindre avhengig av punktskyen.

Når forhåndsvisningen er ferdig behandlet, klikker du på dokumentet for å vise PC-en din i dokumentforhåndsvisningen:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/02-uploading-pc-data.png)

### 1.2 **Delte PC-revisjoner**

Hvis [revisjonspublisering](https://support.catenda.com/en/articles/9874698-revision-publishing-iso-19650) er aktivert for prosjektet, har punktskyen blitt lastet opp som en delt revisjon. Delte PC-revisjoner kan bare forhåndsvises i dokumentseksjonen. For å kunne laste PC-en inn i 3D-viseren, må revisjonen publiseres. Individuelle delte revisjoner kan publiseres med publiseringshandlingen i høyremenyen for dokumentforhåndsvisningen. Flere delte revisjoner kan publiseres med handlingen for valgte elementer i dokumentstrukturen. Når du publiserer en revisjon, starter forhåndsvisningen for den publiserte revisjonen å behandle.

### 1.3 **Publiserte PC-revisjoner**

Etter at forhåndsvisningen av en publisert PC-revisjon er behandlet, vises en 3D-knapp i viserkolonnen i dokumenttabellen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/03-br-published-pc-revisions.png)

3D-knappen laster den siste publiserte revisjonen av dokumentet inn i 3D-viseren.

Hvis du har valgt ett eller flere dokumenter med 3D-dokumenter som PC, IFC eller GML-dokumenter, vil du også se 3D-dokumenthandlingen i handlingsmenyen for valgte elementer i dokumenttabellen. På denne måten kan du laste inn de siste revisjonene av flere 3D-dokumenter i 3D-viseren på en gang.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/04-br-published-pc-revisions.png)

I et dokument med minst en publisert PC-revisjon som er ferdig behandlet, kan du se 3D-handlingen i handlingsmenyen øverst til høyre.

> **Merk:** 3D-handlingen laster den siste publiserte revisjonen av dokumentet inn i 3D-viseren. Selv om du ser på en tidligere revisjon.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/05-br-published-pc-revisions.png)

## 2. **Forhåndsvisning av 3D-viser**

Etter at du klikker på 3D-knappen, begynner PC-punktene å lastes inn i 3D-viseren. 3D-visningen av en PC kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/06-3d-viewer-preview.png)

Øverst i 3D-viseren kan du se en grønn lastestolpe. Denne lastelisten indikerer hvor mange punkt som har blitt lastet inn i 3D-viseren for gjeldende kameraposisjon og vinkel. Lastelisten kan endres hvis du roterer rundt, da punktene kan forsvinne fra visningen og lastes ut eller flere punkter kommer innen rekkevidde og begynner å laste inn.

Og etter noen justeringer med zoom og posisjonsering kan PC-forhåndsvisningen se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/07-3d-viewer-preview.png)

## 3. **3D-viserinnstillinger**

I denne seksjonen skal vi se på innstillingene inne i Catenda Hub som lar deg få den beste opplevelsen med PC-en din.

> **Merk:** Før du konfigurerer 3D-viseren, må du sørge for at programmet Catenda er åpent i er konfigurert [som anbefalt](https://support.catenda.com/en/articles/6921941-hardware-recommendation).

Innstillinger som kan brukes til å konfigurere punktskyer er plassert på to steder.

### 3.1 **1. Punktbudsjett:**

Punktbudsjettet kan konfigureres i [3D-viserinnstillingene](https://support.catenda.com/en/articles/5784718-3d-viewer-settings) som finnes i tannhjulikonet øverst til høyre i 3D-viseren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/08-1-point-budget.png)

I 3D-viserinnstillingsmenyen kan punktbudsjettet justeres fra 100 000 opp til 10 000 000. Lasting av flere punkter kan ta mer tid og kan kreve mer ressurser fra systemet ditt. Ved å laste inn flere punkter kan punktskyen vises med høyere troverdighet. Se samme visning med: 100 000 punkter

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/09-1-point-budget.png)

1 000 000 punkter

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/10-1-point-budget.png)

10 000 000 punkter

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/11-1-point-budget.png)

### 3.2 **2. Revisjonvelger og individuelle PC-innstillinger:**

Øverst til venstre i 3D-viseren finner du [Revisjonvelgeren](https://support.catenda.com/en/articles/4670246-accepting-an-invitation-to-join-a-project).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/12-2-revision-selector-and-individual-pc-settings.png)

I [modellmenyen](https://support.catenda.com/en/articles/4670279-revision-selector#h_180a64490d) kan du finne de individuelle [3D-dokumentene](https://support.catenda.com/en/articles/4670279-revision-selector#h_fce60074ef) som du har lastet inn i 3D-viseren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/13-2-revision-selector-and-individual-pc-settings.png)

Punktskyer kan konfigureres i revisjonvelgeren ved å klikke på tannhjulikonet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/14-2-revision-selector-and-individual-pc-settings.png)

Slik kan innstillingsmenyen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/yve4vvqf/15-2-revision-selector-and-individual-pc-settings.png)

_Attributt_ _RGBA_ - Standard Vis PC-punkter med deres farger

_Attributt Intensitet_ Intensitetsalternativet kan brukes når punktene ikke inkluderer farger. For eksempel når punktskyen ble fanget inn i en tunnel eller et mørkt rom.

_Dekkevne_ Når modeller vises sammen med punktskyer, kan det være nødvendig å dempe punktene for å få en bedre forståelse av synsvinkelen.

_Punktstørrelse_ _Adaptiv_ - Standard Jo nærmere et punkt er kameraet, jo større er det. Punkter som er i visningen lastes inn i minnet. Punkter som beveger seg ut av visningen, lastes ut av minnet.

> **Merk:** Sørg for at maskinvaren og programvaren Catenda er åpnet på er konfigurert [som anbefalt](https://support.catenda.com/en/articles/6921941-hardware-recommendation) da dette kan ha en effekt på typen punktstørrelseslasting enheten din kan håndtere.

_Punktstørrelse Fastsatt størrelse_ Punkter som er blitt lastet, vil forbli i minnet med dette alternativet. Med mange punkter vil du legge merke til at rotasjon kan bli forsinket og bevegelse kan bli bremset ned når du begynner å komme nær mengden punkter som systemet ditt kan håndtere. Du kan også legge merke til at det tar lengre og lengre tid å laste inn nye punkter når du kommer nærmere grensen for enheten din. Punkter lastes nærmest kameraet først. Før du laster inn punktskyen fra dokumentseksjonen, må du posisjonere kameraet til der du vil at punktene skal lastes. Hvis dette er en kameraposisjon du planlegger å bruke oftere med denne punktskyen, bør du vurdere å lage et bokmerke eller et øyeblikksbilde i en sak som du kan spille av for å gå tilbake til denne posisjonen.

_Punkttetthetskontroll_ Tetthetskontroller hjelper deg med å gjøre den endelige innstillingen. Det finnes ingen regel for riktig verdi, det vil avhenge av dataene du laster opp (størrelse på datasett, punkttetthet, type skanning osv...). Råd fra oss: Last inn punktskyen, og etter et kort øyeblikk, når nok punkter vises, justerer du innstillingene om nødvendig.

[YouTube-video](https://www.youtube.com/embed/n9pztkRPxoc?rel=0)
