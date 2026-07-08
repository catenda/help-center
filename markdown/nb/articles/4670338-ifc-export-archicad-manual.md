# IFC Export Archicad Manual

Når du eksporterer en IFC, husk hva som er relevant for IFC-exporten din. IFC-filen kan være stor og vanskelig å arbeide med hvis den inneholder mye informasjon. Derfor er det viktig å ikke eksportere unødvendig informasjon. I denne rapporten får du ulike tips til å filtrere IFC-exporten din i Archicad.

## 1. Prosjektinfo

Før du eksporterer en IFC fra prosjektet ditt, må du kontrollere at prosjektinformasjonen er konfigurert. Prosjektinformasjonen finner du her:

`Fil -> Info -> Prosjektinfo`

Slik kan prosjektinformasjonen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/01-project-info.png)

Som standard vil de forskjellige feltene være tomme. Selv om de er tomme, opprettes en unik ID for hvert prosjekt, nettsted og bygning som er oppført. I noen situasjoner eksporteres flere IFC-filer fra samme Archicad-prosjekt. Eksempler på dette er:

IFC-filer med objekter fra ulike fagfelt. En MEP-modell med kanaler, en arkitekturmodell med vegger og en strukturmodell med alle platåene.

Flere bygninger Noen ganger modelleres flere bygninger sammen i samme Archicad-fil, og en egen IFC eksporteres for hver av dem.

Ulike designvalg. Når ulike variasjoner av en bygning er modellert i samme Archicad-fil, eksporteres hver variasjon ofte til sin egen IFC-fil.

### 1.1 Konfigurering av prosjektinfo

Enten det er planer om å eksportere flere IFC-filer eller ikke, er det ofte en god idé å fylle inn verdier i prosjektinformasjonen slik at den ikke må endres senere. Prosjektinformasjonen er viktig å fylle ut fordi den påvirker GUID-ene i filen. Hver type IFC som eksporteres, skal ha sine egne prosjektinnstillinger. Prosjektinnstillingene kan importeres og eksporteres til nederst til høyre. På denne måten kan flere profiler støttes for eksportene fra filen. For Catenda er det viktig at IFC-ene i ulike modeller har ulik informasjon konfigurert, mens IFC som vil være i samme modell har samme informasjon konfigurert.

## 2. IFC-eksportinnstillinger

For å eksportere hele prosjektet. Du må være i 3D-visningen. Sørg for at du bruker riktig oversetter.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/02-ifc-export-settings.png)

Klikk på alternativknappen for å se en oversikt over dine IFC-eksportinnstillinger. Under modellfilter kan du også velge å filtrere ut mer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/03-ifc-export-settings.png)

Boksen for IFC-oversettere lar deg se eller endre Oversetter-innstillinger, eller opprette nye Oversettere.

Hvis du vil endre IFC-exporten din, anbefales det at du dupliserer en av de ferpreperede oversetterne slik at du ikke masser opp en av standardoversetterne. Dupliser en oversetter her:

Klikk nye > Dupliser av > velg oversetter du vil duplisere.

Hvis du vil slå sammen IFC-en, kan du gjøre det under samme banner.

![image-2.png](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/04-ifc-export-settings.png)

---

### 2.1 Ulike innstillinger i eksporten

1\. [Modellfilter](#model-filter) lar deg filtrere ut det du vil eksportere etter ulike forhåndsinnstillinger. 2\. [Type mapping](#type-mapping) lar deg velge hva slags IFC-type hvert element eksporteres som. 3\. [Geometrikonvertering](#geometry-conversion) lar deg velge hva slags geometri du vil eksportere. 4\. [Egenskapskartlegging](#property-mapping) lar deg sette opp kriterier basert på typer. 5\. [Datakonvertering](#data-conversion) lar deg velge hva slags data du vil eksportere fra modellen. 6\. [Enhetkonvertering](#unit-conversion) lar deg velge hvilke måleenheter du vil eksportere i IFC-en din.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/05-different-settings-in-the-export.png)

---

## 3. Modellfilter

### 3.1 Eksportering av rutenett i IFC

Noen ganger ønsker du at rutenettet også eksporteres for å kunne se det i Catenda Hub.

Gå til modellfilter for IFC Export og sørg for at avmerkingsboksen "Rutenett system og elementer" er merket av.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/06-exporting-grids-in-the-ifc.png)

---

## 4. Type Mapping

Når en IFC eksporteres, får alle elementene i modellen en IFC-type.

Hvis du velger IFC-oversetter du vil bruke, kan du deretter gå til type mapping og klikke på Map IFC Types for import for å administrere hva slags type mapping du vil ha på den eksporterte IFC-en din.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/07-2-type-mapping.png)

Type mapping har hovedsakelig to ulike alternativer for å sortere IFC-typene dine etter.

### 4.1 Elementtype

Hvert element får automatisk tildelt en grunnleggende IFC-type. Du kan se hvert elements tildelte IFC-type i prosjektbehandler og i elementinnstillinger.

### 4.2 Klassifikasjon

Denne metoden tillater mer fleksibel og detaljert IFC-type kartlegging, i henhold til bestemte klassifikasjonsstandarder. Sone- og åpningselementer er satt til en fast IFC-type. IFCSpace og IFCOpeningElements.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/08-classification.png)

---

## 5. Geometrikonvertering

Geometrikonvertering for IFC Export vil la deg konvertere geometrien din på ulike måter.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/09-3-geometry-conversion.png)

### 5.1 Konvertering av Archicad-elementer

_Eksporter all modellgeometri som:_ _Parametrisk med unntak_ - standard _BREP_ - Presis geometri - Hvis dette velges, vil de to neste alternativene også være BREP

_Elementer i solide elementoperasjoner:_ _Ekstrudert/revolvert_ - standard _BREP_ - Presis geometri

Elementer med kryss Noen elementer kan krysses med andre elementer som kan klippe av deler av ekstrusjonen. _Ekstrudert/revolvert_ - Koble hjørner av elementer Dette legger kryss til de ekstruderte elementene dine. Med dette alternativet vil du se at elementer som vegger eller tak, spesielt skrå, vil koble seg fint.

_Ekstrudert/revolvert uten kryss_ - standard - Dette gjør eksporten raskere Hvis du har 90 graders elementer som vegger eller tak, vil du sannsynligvis ikke se noen forskjell med dette alternativet. Hvis du har skrå vegger, vil du legge merke til at i hjørnet der veggene møtes, i stedet for å trimme overskuddet av den rette ekstrusjonen, går veggene rett forbi hverandre og kobler seg ikke fint.

_BREP_ - Presis geometri

Parametriske elementer Archicad-elementer kan eksporteres som parametrisk geometri ofte i form av veiledningslinjer som blir ekstrudert til en avstand. Parametrisk geometri gjør det enkelt å redigere objektet etter at det er opprettet. Selv om dette alternativet beholder redigerbarhet, kan geometrien ofte være noe unøyaktig siden definisjonen er en tilnærming av geometrien. Dette alternativet anbefales hvis du planlegger å importere IFC-en tilbake til Archicad eller et annet redigeringsprogram for å foreta ytterligere redigeringer.

BREP Eksporter geometri som separate BREP-flater. I stedet for å beskrive objektene ved deres parametrer som lengde/bredde/høyde med flater som genereres som resultat, beskrives hver flate som en separat flate med en plassering i 3D. Objekter kan fortsatt inneholde flere flater, men disse vil være løse flater. Etter eksportering må BREP-flater redigeres individuelt siden parametrer ikke lenger brukes på flaten. Med BREP-alternativet eksporteres eksakte flater uten rom for forskjell i tolking av parametrer mellom forfatterverktyg. Flater er farget individuelt og vil ha samme farge i Catenda Hub som de gjør i Archicad. Flatefargene kan konfigureres i følgende meny:

`Alternativer -> Elementegenskaper -> Flater`

Det kan være bra å konfigurere alle innstillinger for en flate da de vil bli skrevet inn i IFC.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/10-conversions-of-archicad-elements.png)

Flater i Catenda 3D-visningen har flat skyggelegging uten en lyskildenærvær. Dette betyr at verdier som Ambient, Attenuation, Shinyness, Emission og Specular ikke tolkes når flaten blir sett i Catenda 3D-visningen. Følgende verdier tolkes av Catenda når flaten vises i 3D-visningen:

Flatefargen Fargen på flaten

Transmittans Hvor mye du kan se gjennom objektet (Overstyrer innstillingen for gjennomsiktig dekkende evne)

Diffus Hvor mørk eller lys flatens farge er

_Definer IFC-modellposisjon etter:_ Dette alternativet bestemmer prosjektsted. Det er viktig å bli enig om et felles koordinatpunkt å referere til i prosjektet allerede fra starten av, å endre det kan bety at flere konsulenter må flytte objektene sine noe som ofte ikke er mulig mot slutten av et prosjekt.

Målepunkt og prosjektopprinnelse - standard Med dette alternativet vil avstanden fra (0,0,0) til modellen din i Archicad være avstanden fra (0,0,0 + koordinater for målepunktet ditt) til modellen din i Catenda Hub + if Du har angitt en prosjektplassering, vil modellen din ende opp på disse koordinatene i Catenda Hub

Bare prosjektopprinnelse Med dette alternativet vil avstanden fra (0,0,0) til modellen din i Archicad være avstanden fra (0,0,0) til modellen din i Catenda Hub.

Bare målepunkt Med dette alternativet vil avstanden fra målepunktet i Archicad til modellene dine være avstanden fra (0,0,0) til modellen din i Catenda Hub

### 5.2 IFC-skema relaterte alternativer

_Materialbevarelsesprogram (kun IFC2x3)_ - Spreng aldri elementer, bevaring er ikke garantert Med dette alternativet eksporterer du hele objektet som ett objekt

- Eksploder bare når det er nødvendig for å bevare materialer - Standard
  Med dette alternativet eksporterer du bare separate objekter for hvert sammensatt materiale hvis det er nødvendig

- Eksploder alle elementer i deler, bevar materialer
  Med dette alternativet eksporteres alle objekter som separate objekter for hvert materiale

Hvis du har et sammensatt vegmateriale, betyr dette at et eget objekt vil bli eksportert for hvert materiale. Du har ofte en damperingsbarriere som er 1-5 mm som vil resultere i et veldig tynt objekt. Når objekter er så tynne, kan geometrien være unøyaktig. Problematiske vegmaterialer kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/11-ifc-schema-related-options.png)

Dette kan gjøre det vanskelig for programvare å kutte hull gjennom overflaten da unøyaktigheten gjør det vanskelig å finne ut nøyaktig hvor hullet skal være. Hvis du derfor legger merke til at åpningene dine ikke blir kuttet gjennom, kan det hjelpe å slå på dette alternativet. Hvis du slår på dette alternativet, eksporteres veggen som ett enkelt objekt i stedet for mange tynne sammensatte objekter.

### 5.3 Sammensatte strukturer og komplekse profiler

_Del komplekse bygnindelementer i deler_ Her kan du velge for hvilken type elementer du vil at det sammensatte elementet skal deles og for hvilke du ikke vil dele dem. Hvis du velger dette alternativet, vil du ikke være i stand til å gjøre et valg for materialbevarelsesprogram.

---

## 6. Egenskapskartlegging

Innenfor egenskapskartlegging (Fil > IFC > Interoperabilitet > Egenskapskartlegging) kan du velge hva slags versjon av IFC du vil eksportere. Du har standardene IFC2x3 og IFC4. Du kan også legge til psets for å eksportere med IFC-en din. Hvis du gjør dette, bør du lage en duplisering av IFC-skjemaet du velger.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/12-4-property-mapping.png)

Etter at du har laget en duplisering av standard IFC, kan du legge til egenskapene du vil ha til den nye forhåndsinnstillingen ved å velge IFC-skjemaet og klikke på _Kartlegg IFC-egenskaper for eksport_.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/13-4-property-mapping.png)

---

## 7. Datakonvertering

Under datakonvertering velger du hva slags data i tillegg til geometri du vil få ut av IFC-exporten din. Merk av boksene for det du vil eksportere.

Elementparametrer leser Archicad-elementparameteren og konverterer den til IFC-mengder eller IFC-egenskaper. Avhengig av deres type. Ved å velge dette alternativet øker du filstørrelsen betydelig.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/14-5-data-conversion.png)

IFC Base Quantities leser parametrene for størrelse, område og volum. Hvis du ikke avmerker denne boksen, kan du få problemer med å importere IFC-en din til Catenda Hub.

## 8. Enhetkonvertering

Sett lengde-, vinkel-, område-, volum-, valuta- og tidsenheter for eksporten din.
