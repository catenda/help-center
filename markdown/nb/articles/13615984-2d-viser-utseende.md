# 2D-viser utseende

Det finnes flere måter å konfigurere innholdet i 2D-viseren etter dine behov.

## 1. **Viserobjekter**

### 1.1 **Uthevelse av valgte objekter**

Linjene som genereres for hver etasje når modellen behandles, forblir knyttet til 3D-objektet som ble skåret gjennom når linjene ble generert.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/01-highlighting-selected-objects.png)

Når et objekt velges i 3D-viseren, hvis en etasje av denne modellen er aktivert i 2D-viseren som ble generert på høyden der objektet eksisterer, vil objektet også bli uthevet i 2D-viseren. Objektskiver genereres på en meter over høyden som er angitt for hver etasje i IFC-filen. Høydeavvik som høyden i IFCSite, tas ikke i betraktning.

I eksemplet nedenfor ligger etasjen "Kjellerstokk" på 0 meter. Vegger med bunnhøyde 0 og ulike tophøyder vises.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/02-highlighting-selected-objects.png)

Som man kan se, vises kun vegger som er 1 meter og høyere i 2D-viseren.

### 1.2 **Dørsving**

Dørsvinger er spesifisert i IFC-filen. Du kan se hvordan dette fungerer i følgende BuildingSMART-artikler: [IFC 2x3](https://standards.buildingsmart.org/IFC/RELEASE/IFC2x/FINAL/HTML/ifcsharedbldgelements/lexical/ifcdoorstyle.html) [IFC 4](https://standards.buildingsmart.org/IFC/RELEASE/IFC4_1/FINAL/HTML/schema/ifcsharedbldgelements/lexical/ifcdoortypeoperationenum.htm) Hvis ingen dørsvinger er angitt, svinger døren åpen til høyre.

## 2. **Tegning som underlag**

Det er mulig å legge til en PDF fra dokumentdelen med [etaskonfiguratoren](https://support.catenda.com/en/articles/6921756-storey-configurator-page). Dette er spesielt nyttig hvis det finnes objekter over eller under høyden der 3D-objektene skåres gjennom, som ikke vises i 2D-viseren. Eksempler på disse er: Kanaler og rør, Stikkontakter, Takplaner, Vei og jernbane

## 3. **Markører i 2D-viseren**

Med [markører aktivert](https://support.catenda.com/en/articles/4854537-2d-viewer#h_381a9d4098) vises saker med plassering som fargede sirkler på en x-y-koordinat. Slik kan en 2D-visning med ulike markører se ut i nettleseren:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3bzb6a32/03-markers-in-the-2d-viewer.png)

Klikk [her](https://support.catenda.com/en/articles/4854523-2d-location-of-issues) for å lese mer om 2D-plasseringen av saker.

### 3.1 **Saker med eksisterende markører**

**Markeringsinteraksjoner -** Hold musen over en markør for å se nummeret og tittelen på saken som markøren kommer fra. Klikk på markøren for å åpne saken i sakstabell i innholdspanelet. En markør som tilhører en åpen sak, er uthevet i grønt.

**Visning av markører -** Filtrer og søk i en sakstabel. Saker fra det filtrerte resultatet som har markører på den forberedte 2D-viseren vises.

### 3.2 **Saker med nye markører**

Før du arbeider med markører, må du kontrollere at 2D-viseren er konfigurert.

- **Etasjer fra modell 2D-visninger -** Velg en etasje fra en aktivert 2D-visning som bunnhøyde. Aktiver andre 2D-visninger for å vise sammen med denne etasjen.
- **Etasjer fra** **Bygninger -** Velg en etasje fra en forhåndskonfigurert bygning.
  Bunnhøyden og de aktiverte 2D-visningene fra konfigurerte modeller er aktivert.

**Markeringsplassering -** Høyreklikk på lerret og opprett en ny sak med markør. Klikk på legg til plassering i sakshodet på innholdspanelet, og klikk på stedet der markøren skal legges til.

## 4. **Roometiketter i 2D-viseren**

Roometikettene som vises i sentrum av rom i 2D-viseren, bestemmes ved hjelp av dataene som er tilgjengelige i IFC-romobjekter. Disse romobjektene inkluderer både korte og lange navn, som kan konfigureres for å definere etikettformatet via innstillingen **Romnavn-format** i Catenda. Sikre at både romnumre og områder er nøyaktig inkludert i IFC-dataene, da manglende attributter kan begrense visningen av ønskede roometiketter.

### 4.1 Feilsøking av roometiketter:

- Kontroller at IFC-datafilen inneholder nødvendige attributter som romnumre og områder.
- Kontroller og juster innstillingene for "Romnavn-format" for å samsvare med dine foretrukne etikettogninger. Du finner innstillingen i 2D-viserens "innstillingshjul" i høyre hjørne.
