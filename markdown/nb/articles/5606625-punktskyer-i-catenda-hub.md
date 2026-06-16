# Punktskyer i Catenda Hub

> Finn ut hvordan du kan dra nytte av laserskanning og LIDAR-teknologi i Catenda Hub.

> **Merk:** Last ned en eksempelfil fra [her](https://drive.google.com/file/d/1G8U916oihDl5qHrTfQaVHxDeLsbq1ulG/view?usp=sharing). Punktskydatasett (PC) kan visualiseres i Catenda Hub Individuelle PC kan forhåndsvises i dokumentområdet. Flere PC kan lastes inn i [3D-visningen](https://support.catenda.com/en/articles/8227211-3d-viewer). I 3D-visningen kan PC vises sammen med andre 3D-dokumentformater som IFC model og GML-filer. Denne artikkelen inneholder informasjon om følgende emner: _[Dokumentforhåndsvisning](#h_bb5e5b9840) - [3D-visningsforhåndsvisning](#h_076189f481) - [3D-visningsinnstillinger](#h_9c02ade6a6)_ Se nedenfor ulike innstillinger for å vise dataene dine:

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p class="no-margin">Adaptiv - Sparsom - RGB</p><div class="intercom-container"><img height="2159" src="https://downloads.intercomcdn.com/i/o/areracg3/1609416415/d63b03e835b7de05a34bc464a67c/image.png?expires=1779991200&amp;signature=bb5f495209f2f06bdc3de410d4d7e1c422d3d8ea9034524db714f9077f73c45d&amp;req=dSYnH81%2Fm4VeXPMW3nq%2BgQpCsmyZG1KSFFVbUYNJ2UiYdd3J7TGDppb8CTJW%0Aa1wWWTAtvyWfrJEfDrlcNFHoTrU%3D%0A" style="height: auto;" width="3839"/></div></td><td><p class="no-margin">Adaptiv - Tett - RGB</p><div class="intercom-container"><img height="2159" src="https://downloads.intercomcdn.com/i/o/areracg3/1609416931/9c357c3e7bd94ba44368bf2e0476/image.png?expires=1779991200&amp;signature=85b6343cd7f91e12a9dc3356debe39dfdeac86db7f2b5c7794fca75e721585ae&amp;req=dSYnH81%2Fm4hcWPMW3nq%2BgdwfTofqQ7RvylQ%2FH6UFuY67uWWyGoYVG%2FSNG%2FvW%0AeXpHm2lN07PYjclbv0fHJIa1%2BZ8%3D%0A" style="height: auto;" width="3839"/></div></td></tr><tr><td><p class="no-margin">Fast - Tett - RGB</p><div class="intercom-container"><img height="2159" src="https://downloads.intercomcdn.com/i/o/areracg3/1609415523/d5626faba40b5c3551361c832b5b/image.png?expires=1779991200&amp;signature=adeb85b52cd8280463402acd243b7a6e1a811fae38a7f61f3e9aaa83cc90ee30&amp;req=dSYnH81%2FmIRdWvMW3nq%2BgYHi7%2FbQTl49HAjgtDsdSFh6QfdbdKda7GA55QfR%0AY65xOQbKB50egoMF75QUYo9dG0g%3D%0A" style="height: auto;" width="3834"/></div></td><td><p class="no-margin">Fast - Sparsom - Intensitet</p><div class="intercom-container"><img height="2159" src="https://downloads.intercomcdn.com/i/o/areracg3/1609415755/5d2aac51f6caea382c5d762b2dae/image.png?expires=1779991200&amp;signature=90c35496c076f66c2ff4cf8d42c759c0caaf01082168a2f7933e606aadc1d7ff&amp;req=dSYnH81%2FmIZaXPMW3nq%2BgUep5M5qKq9J8fpRvp8MeVoccLBBRVRiajRONyGy%0A8DqsOdPDMVir8z8%2Fzh6OjjIL57s%3D%0A" style="height: auto;" width="3839"/></div></td></tr></tbody></table></div>

## **Dokumentseksjonens forhåndsvisning**

PC-data med følgende to filformater kan forhåndsvises på Catenda.

- `\*.e57`
- `\*.las`

PC kan lastes opp som ethvert annet dokument i dokumentseksjonen.

For disse to filformatene kan filer opp til 25 GB lastes opp til dokumentseksjonen.

Flere filer kan lastes inn i dokumentseksjonen og vises sammen i 3D-visningen.

### **Lasting av PC-data**

Det anbefales å bruke [Catenda Desktop Connector](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) eller å komprimere PC-filen din til en zippet mappe og bruke [zip-importen](https://support.catenda.com/en/articles/7945410-upload-a-zip-file-structure) for å laste opp PC-en din.

Disse metodene vil hjelpe deg med å spare tid da opplastingsfilstørrelsen blir mindre, og vil også minimere risikoen for nettverksfeil da filen blir lastet opp raskere

Etter at du laster opp en PC til dokumentseksjonen, begynner forhåndsvisningen av dokumentet å behandles.

Mens forhåndsvisningen behandles, vil du se en grå stolpe mot toppen av dokumentforhåndsvisningen din.

![](https://downloads.intercomcdn.com/i/o/areracg3/1609421389/8e3f5ca035ebe50fb83c034ddaab/image.png?expires=1779991200&signature=bb8ee3de6805462c7033ed7a21c7afe915b1e9f9be7485aaed67465a8e6f5111&req=dSYnH818nIJXUPMW3nq%2BgdqJu4eRld6dpYdfOUiFyseZZ%2B%2FU4uaAS%2FgMiPjc%0A54hxfMtyyoZMY7F%2BBX5OrgUE5TM%3D%0A)

Varigheten av behandlingen av forhåndsvisningen avhenger av størrelsen på PC-en.

Behandlingen tar 1 time per GB, men det kan være mer eller mindre avhengig av punktskyen.

Når forhåndsvisningen er ferdig behandlet, klikker du på dokumentet for å vise PC-en din i dokumentforhåndsvisningen:

![](https://downloads.intercomcdn.com/i/o/areracg3/1609450891/70ce69784cedc730f37a34143f5c/image.png?expires=1779991200&signature=5b7dbb39946e2db64183d99b228cbffeea7b6236ac21ff91e565d6afb5a17bd9&req=dSYnH817nYlWWPMW3nq%2BgZjDFCu8k%2BqFmMj85V29ajp0dOPxv6on1BnnRR3a%0AhmdXl9cF4RVn02yDdXwAJFhR1FQ%3D%0A)

### **Delte PC-revisjoner**

Hvis [revisjonspublisering](https://support.catenda.com/en/articles/9874698-revision-publishing-iso-19650) har blitt aktivert for prosjektet, vil punktskyen ha blitt lastet opp som en delt revisjon.

Delte PC-revisjoner kan bare forhåndsvises i dokumentseksjonen.

For å kunne laste inn PC-en din i 3D-visningen må revisjonen publiseres.

Individuelle delte revisjoner kan publiseres med publiseringshandlingen i høyremenyen i dokumentforhåndsvisningen. Flere delte revisjoner kan publiseres med handlingen for valgte elementer i dokumentstrukturen.

Når du publiserer en revisjon, begynner forhåndsvisningen for den publiserte revisjonen å behandles.

### **Publiserte PC-revisjoner**

Etter at forhåndsvisningen av en publisert PC-revisjon er behandlet, vil en 3D-knapp vises i visningskolonnen i dokumenttabellen.

![](https://downloads.intercomcdn.com/i/o/areracg3/1609421833/99aa8dc6542b0fa5fff525ee0096/image.png?expires=1779991200&signature=a405649349f8f629e3da97c4d615b03ee35f54d67fdbfdba0842e0b16ba36abe&req=dSYnH818nIlcWvMW3nq%2BgW4P%2BGZNpG4%2Fjw6CfuQveZcBKehIzCa31VmOLufe%0A%2F9%2B%2BAhqB5usT08rMNgslBIDu7mQ%3D%0A)

3D-knappen vil laste den nyeste publiserte revisjonen av dokumentet inn i 3D-visningen.

Hvis du har valgt ett eller flere dokumenter med 3D-dokumenter som PC, IFC eller GML-dokumenter, vil du også se 3D-dokumenthandlingen i handlingsmenyens valgte elementer i dokumenttabellen.

På denne måten kan du laste de nyeste revisjonene av flere 3D-dokumenter inn i 3D-visningen på en gang.

![](https://downloads.intercomcdn.com/i/o/areracg3/1609422276/427b34fa8a17a3256f7885283fb9/image.png?expires=1779991200&signature=e957465f7c8737a6a5876f01838693655da92d5576071e5001f4759777378344&req=dSYnH818n4NYX%2FMW3nq%2BgS5oxHbz%2BVjDB0MLdYU%2FAfBHw6EYiHVet%2B7UhYgM%0ADvaURkwVqPxDlkm2wGpTZuqsxsg%3D%0A)

I et dokument med minst en publisert PC-revisjon som er ferdig behandlet, vil du kunne se 3D-handlingen i handlingsmenyens hjørne øverst til høyre.

> **Merk: **3D-handlingen vil laste den nyeste publiserte revisjonen av dokumentet inn i 3D-visningen. Selv om du ser på en tidligere revisjon.

![](https://downloads.intercomcdn.com/i/o/areracg3/1609467515/0f3244b065fb5bdbe46ad198ff98/image.png?expires=1779991200&signature=07151c3d91cad4cde6b077d6c93c35830876bd08dbcc55a3e120339c618e71ba&req=dSYnH814moReXPMW3nq%2BgZMc0Sbv6WPU8NqbTNkVjHj9fz%2FxQ0ZKfr3y0XoR%0Add4eA5xmPeB8ZpBjJyONyr7AiDo%3D%0A)

## **3D-visningsforhåndsvisning**

Etter at du klikker på 3D-knappen, begynner PC-punktene å lastes inn i 3D-visningen.

3D-visningen av en PC kan se slik ut:

![](https://downloads.intercomcdn.com/i/o/areracg3/1609423520/54537802e257cabf02a7e31773b3/image.png?expires=1779991200&signature=38819792169cb3030d41390f4a38f96c49ba752f16e6767c80658492d00e7b49&req=dSYnH818noRdWfMW3nq%2BgYkVc%2Bi0sao1bTLiV7WfFvJfkGUmK2opnDfoSCAb%0A%2B7NFC1hTE5OF4IfSJnas3coJQQA%3D%0A)

Mot toppen av 3D-visningen kan du se en grønn lastekurve.

Denne lastekurven viser hvor mange punkter som har blitt lastet inn i 3D-visningen for gjeldende kameraposisjon og -vinkel.

Lastekurven kan endres hvis du roterer rundt, ettersom punkter kan forsvinne fra visningen og lastes ut av hukommelsen, eller flere punkter kommer innenfor rekkevidde og begynner å lastes inn.

Og etter noen justeringer med zoom og posisjonering kan PC-forhåndsvisningen se slik ut:

![](https://downloads.intercomcdn.com/i/o/areracg3/1609531299/fdd952082ae44fec28ab2e1aa9ce/image.png?expires=1779991200&signature=932aa16b2db0b62bb18616cd349273d2651d5f0cfb65ddce51279364b27b14b1&req=dSYnH8x9nINWUPMW3nq%2Bgf0Z9P9tBxpV2awJEQpPIFx4Gnzi9h%2FQTFYUWF5z%0AVhX11npDyPLn%2BdtHgXazB97Po6U%3D%0A)

## **3D-visningsinnstillinger**

I denne delen skal vi se på innstillingene i Catenda Hub som gjør det mulig for deg å få den beste opplevelsen med PC-en din.

> **Merk:** Før du konfigurerer 3D-visningen, må du sørge for at applikasjonen Catenda er åpnet i, er konfigurert [som anbefalt](https://support.catenda.com/en/articles/6921941-hardware-recommendation).

Innstillinger som kan brukes til å konfigurere punktskyer, befinner seg på to steder.

### **1. Punktbudsjett:**

Punktbudsjett kan konfigureres i [3D-visningsinnstillingene](https://support.catenda.com/en/articles/5784718-3d-viewer-settings) som finnes i girkonet mot øverst til høyre i 3D-visningen.

![](https://downloads.intercomcdn.com/i/o/areracg3/1609545463/7cbc97711d4b61b542c7a402b5bf/image.png?expires=1779991200&signature=517977c7a3cf3411492469e999e980925db2ed07a4a049fb62c4ae4548ec3c66&req=dSYnH8x6mIVZWvMW3nq%2BgYowLhbAOrdEOFMDqAlQQwe7%2FZ8mtUSr3mrzJnbE%0ANcENhTLpWfdEZrctvIozPxiEmk8%3D%0A)

I 3D-visningsinnstillingsmenyene kan punktbudsjett justeres fra 100 000 opp til 10 000 000.

Lasting av flere punkter kan ta mer tid og kan kreve flere ressurser fra systemet ditt.

Ved å laste inn flere punkter kan punktskyen vises med høyere troskap.

Se samme visning med:

100 000 punkter

![](https://downloads.intercomcdn.com/i/o/areracg3/1609571739/d748e276eb87dc27a0aa7db8db07/image.png?expires=1779991200&signature=8d608db65ee68b9c7ed1d795b6b5345150f1339f1b7c2bd7818bdc1a5d9e3cd8&req=dSYnH8x5nIZcUPMW3nq%2BgdxOA5%2BTzjItrNh%2BK8v%2F4uVPmEk6bPwaZygwdlb0%0AAkIkaoRkk7rNnozUdf3g038zDSg%3D%0A)

1 000 000 punkter

![](https://downloads.intercomcdn.com/i/o/areracg3/1609571931/9586d0dbfe6e5504391c42478670/image.png?expires=1779991200&signature=594770a0e63419b134c01aecb98386b394e136703d9c304f236f322536172e3e&req=dSYnH8x5nIhcWPMW3nq%2BgdiGPj9UQOIMgKtrPLXgoEBAGFpn7w3fxifCwceD%0AYbUkDOtKvEbBRg23Pbz8eqYXtIQ%3D%0A)

10 000 000 punkter

![](https://downloads.intercomcdn.com/i/o/areracg3/1609572103/5812057c81b819d94f90f11bc5ce/image.png?expires=1779991200&signature=73bdb9c4763f969dc58057465bcc4401da595e2e7b12735d4d673142020dfd99&req=dSYnH8x5n4BfWvMW3nq%2BgaW7W936heNUiQ55yD2ziU8dx7c4d8PGzDxPoD2o%0ACl%2FKBMEP9%2BWHBBR9SM6E4DN%2BkB8%3D%0A)

### **2. Revisjonvelger, og individuelle PC-innstillinger:**

Øverst til venstre i 3D-visningen finner du [Revisjonsvelgeren](https://support.catenda.com/en/articles/4670246-accepting-an-invitation-to-join-a-project).

![](https://downloads.intercomcdn.com/i/o/areracg3/1541300106/af53e4c7d67a1b60647226c9682a/image.png?expires=1779991200&signature=3298942dda159f9a1377b241c8857541ca2969a60ce204063cc77099b4c5680d&req=dSUjF8p%2BnYBfX%2FMW3nq%2BgXL4o5%2BmNwOPnbEVzIeYwU0bxJgUWoge1RqP9gYi%0APvPadPyMmnCkXHG4wgW6LWYYnHU%3D%0A)

I [modellermenyen](https://support.catenda.com/en/articles/4670279-revision-selector#h_180a64490d) vil du kunne finne de individuelle [3D-dokumentene](https://support.catenda.com/en/articles/4670279-revision-selector#h_fce60074ef) som du har lastet inn i 3D-visningen.

![](https://downloads.intercomcdn.com/i/o/areracg3/1541305754/29b5954c54c437f5ea85b76877ca/image.png?expires=1779991200&signature=d610bcb8573541ed79ec47c2e4ad5ee8b281c5afc8fe469016d6b0e4b76a103c&req=dSUjF8p%2BmIZaXfMW3nq%2BgdbK8s%2BNqKV0vAI%2Fkvq3pfcZyKnfHgTINdFDcuQh%0A%2Fl7VYRuoPrvH14zoJpHpQWpa5Cs%3D%0A)

Punktskyer kan konfigureres i revisjonsvelgeren ved å klikke på girkonet.

![](https://downloads.intercomcdn.com/i/o/areracg3/1541308196/e45ef76ec9ef3c6653cb13e708a7/image.png?expires=1779991200&signature=d5fe1a56ce0abe12b3ad114e746b67ee4d89d3627a52790b614dc27fc31eb6ca&req=dSUjF8p%2BlYBWX%2FMW3nq%2BgT43D8MqTNy9N97BIaZoo3ng1XhL8h0%2F8dM79BQN%0AD9kSxrLC7GMqP1M0BYErXMIYCRA%3D%0A)

Dette er hvordan innstillingsmenyene kan se ut:

![](https://downloads.intercomcdn.com/i/o/areracg3/1541308195/8be3fe5976c1bc56aaedc1fd78fe/image.png?expires=1779991200&signature=6a1d3c12f83eff2a36d2cf1ce6455b989cc51fe365be655b870cd46fd021923e&req=dSUjF8p%2BlYBWXPMW3nq%2BgRw4zg3gSdIIbqpU1RpvsgP2UPwYfdGp3FBRm8Eo%0A%2BrTiPYgmzJsCswTEnhHKJ%2BgX6sQ%3D%0A)

_Attributt_ _RGBA _- Standard

Vis PC-punkter med deres farger

_Attributt Intensitet_

Intensitetsalternativet kan brukes når punktene ikke inneholder farger.

For eksempel når punktskyen ble fanget opp i en tunnel eller et mørkt rom.

_Dekkgrad_

Når model vises sammen med punktskyer, kan det være nødvendig å dempe punktene for å få en bedre forståelse av synsvinkelen.

_Punktstørrelse_ _Adaptiv_ - Standard

Jo nærmere et punkt er kameraet, desto større er det.

Punkter som er i visningen lastes inn i hukommelsen.

Punkter som beveger seg ut av visningen, lastes ut av hukommelsen.

> **Merk:** Pass på at maskinvaren og programvaren Catenda er åpnet på, er konfigurert [som anbefalt](https://support.catenda.com/en/articles/6921941-hardware-recommendation) ettersom dette kan påvirke typen punktstørrelsesinlasting som enheten din kan håndtere.

_Punktstørrelse Fast størrelse_

Punkter som har blitt lastet inn, vil holde seg i hukommelsen med dette alternativet.

Med mange punkter vil du legge merke til at rotasjon kan bli forsinket og bevegelse kan bli tregere når du begynner å komme nærmere antallet punkter som systemet ditt kan håndtere.

Du merker kanskje også at det tar lengre og lengre tid å laste inn nye punkter når du kommer nærmere grensen på enheten din.

Punkter lastes først nærmest kameraet.

Før du laster inn punktskyen fra dokumentseksjonen, må du sørge for å plassere kameraet der du vil at punktene skal lastes inn.

Hvis dette er en kameraposisjon du planlegger å bruke oftere med denne punktskyen, bør du vurdere å lage et bokmerke eller et øyeblikksbilder i et emne som du kan avspille for å returnere til denne posisjonen.

_Tettheitsglider for punkter_

Tetthetsgliden hjelper deg å foreta den endelige innstillingen.

Det er ingen regel for riktig verdi, det avhenger av dataene du laster opp (størrelse på datasettet, punkttetthet, type skanning osv...).

Vårt råd: Last inn punktskyen, og vent et kort øyeblikk, når nok punkter vises, justerer du innstillingene hvis nødvendig.

[YouTube-video](https://www.youtube.com/embed/n9pztkRPxoc?rel=0)
