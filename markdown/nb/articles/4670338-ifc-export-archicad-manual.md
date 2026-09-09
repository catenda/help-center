# IFC Export Archicad Manual

Når du eksporterer en IFC, husk hva som er relevant for din IFC-eksport. IFC-filen kan bli stor og vanskelig å arbeide med hvis den inneholder mye informasjon. Derfor er det viktig å ikke eksportere unødvendig informasjon. I denne rapporten får du forskjellige tips til å filtrere din IFC-eksport i Archicad.

## 1. **1. Prosjektinfo**

Før du eksporterer en IFC fra prosjektet ditt, må du passe på at prosjektinformasjonen er konfigurert. Prosjektinformasjonen finnes her:

`Fil -> Info -> Prosjektinfo`

Slik kan prosjektinformasjonen se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/01-1-project-info.png)

som standard vil de ulike feltene være tomme. Selv om de er tomme, opprettes en unik ID for hvert prosjekt, område og bygning som er oppført.

### 1.1 **1.1 Flere IFC-er fra samme Archicad-prosjekt**

I noen situasjoner eksporteres flere IFC-filer fra samme Archicad-prosjekt. Eksempler på dette er:

_1.1.1 IFC-filer med objekter fra ulike fagfelt_ En MEP-modell med kanaler, en arkitekturmodell med vegger og en konstruksjonsmodell med alle platene.

_1.1.2 Flere bygninger_ Noen ganger blir flere bygninger modellert sammen i samme Archicad-fil, og en egen IFC eksporteres for hver av dem.

_1.1.3 Ulike designvalg_ Når ulike varianter av en bygning modelleres i samme Archicad-fil, eksporteres hver variant ofte til sin egen IFC-fil.

### 1.2 **1.2 Konfigurering av prosjektinformasjonen**

Enten det er planer om å eksportere flere IFC-filer eller ikke, er det ofte en god idé å fylle inn verdier i prosjektinformasjonen slik at den ikke må endres senere. Prosjektinformasjonen er viktig å fylle ut fordi den påvirker GUID-ene i filen. Hver type IFC som eksporteres, bør ha sine egne prosjektinnstillinger. Prosjektinnstillingene kan importeres og eksporteres nederst til høyre. På denne måten kan flere profiler støttes for eksportene fra filen. For Catenda er det viktig at IFC-er i ulike modeller har ulik informasjon konfigurert, mens IFC som skal være i samme modell, har samme informasjon konfigurert.

## 2. **2. IFC eksportinnstillinger**

For å eksportere hele prosjektet må du stå i 3D-visningen. Kontroller at du bruker riktig oversetter.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/02-2-ifc-export-settings.png)

Klikk på alternativer-knappen for å se et sammendrag av IFC-eksportinnstillingene dine. Under modelfilter kan du også velge å filtrere ut mer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/03-2-ifc-export-settings.png)

IFC-oversetter-boksen lar deg vise eller endre Oversetter-innstillinger, eller opprette nye Oversettere. Hvis du vil endre IFC-eksporten din, anbefales det at du dupliserer en av de forhåndslaget oversettere slik at du ikke messing opp en av standard-oversettere. Dupliser en oversetter her: Klikk ny > Dupliser av > velg oversetter du vil duplisere. Hvis du vil slå sammen IFC-en, kan du gjøre det under samme banner.

![image-2.png](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/04-2-ifc-export-settings.png)

## 3. **3. Ulike innstillinger i eksporten**

3.1 [Modelfilter](#h_138e653078) lar deg filtrere ut det du vil eksportere ved hjelp av ulike forhåndsinnstillinger. 3.2 [Typkartlegging](#h_a34c1332a3) lar deg velge hvilken type IFC hver element eksporteres som. 3.3 [Geometrikonvertering](#h_db084b5d6b) lar deg velge hvilken type geometri du vil eksportere. 3.4 [Egenskapskartlegging](#h_d48644eb35) lar deg sette opp kriterier basert på typer. 3.5 [Datakonvertering](#h_7f1df4ecb9) lar deg velge hvilken type data du vil eksportere fra modellen. 3.6 [Enhetkonvertering](#h_36caead1cd) lar deg velge hvilke måleenheter du vil eksportere i IFC-en din.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/05-3-different-settings-in-the-export.png)

## 4. **4. Modelfilter**

### 4.1 **Eksportering av rutenett i IFC**

Noen ganger vil du at rutenettet skal eksporteres også for å kunne se det i Catenda Hub. Gå til modellfilteret for IFC Export og sørg for at avmerkingsboksen "Gridsystem og elementer" er merket.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/06-exporting-grids-in-the-ifc.png)

## 5. **5. Typkartlegging**

Når en IFC eksporteres, tildeles alle elementene i modellen en IFC-type. Hvis du velger IFC-oversetter du vil bruke, kan du gå til typkartlegging og klikke på "Map IFC Types for import" for å administrere hvilken type kartlegging du vil ha på din eksporterte IFC.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/07-5-type-mapping.png)

Typkartlegging har hovedsakelig to ulike alternativer for å sortere IFC-typene dine etter.

### 5.1 **5.1 Elementtype**

Hvert element tildeles automatisk en grunnleggende IFC-type. Du kan se hver elements tildelte IFC-type i prosjektstyrings- og elementinnstillinger.

### 5.2 **5.2 Klassifikasjon**

Denne metoden tillater mer fleksibel og detaljert IFC-typekartlegging, i henhold til spesifikke klassifiseringsstandarder. Sone- og åpningselementer er satt til en fast IFC-type. IFCSpace og IFCOpeningElements.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/08-5-2-classification.png)

## 6. **6. Geometrikonvertering**

Geometrikonvertering for IFC Export lar deg konvertere geometrien din på ulike måter.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/09-6-geometry-conversion.png)

### 6.1 Konverteringer av Archicad-elementer

_6.1.1 Eksporter kun geometrier som "deltar i kollisjondeteksjon"_ Eksporter bare objekter som krysser hverandre

_6.1.2 Eksporter geometri for IFC-typeprodukter_ Typeprodukter inkludert

_6.1.3 Eksporter brutto geometri av elementer_ Bruttgeometri inkludert

_6.1.4 Eksporter all modellelementer geometri som:_ _Parametrisk med unntak_ - standard

_Parametrisk (ekstrudert/rotert)_ _BREP_ - Presis geometri - Hvis dette er valgt, vil de to neste alternativene også være BREP

_6.1.5 Elementer i fast elementoperasjoner:_ _Ekstrudert/rotert_ - standard _BREP_ - Presis geometri

_6.1.6 Elementer med forbindelser_ Noen elementer kan krysse hverandre, noe som kan trimme deler av ekstrusjonen.

Ekstrudert/rotert - Koble hjørner av elementer Dette legger til forbindelser til de ekstruderte elementene dine. Med dette alternativet vil du se at elementer som vegger eller tak, spesielt skråning, kobles fint.

Ekstrudert/rotert uten forbindelser - standard Dette gjør eksporten raskere. Hvis du har 90-graders elementer som vegger eller tak, vil du sannsynligvis ikke merke noen forskjell med dette alternativet. Hvis du har skråvegger, vil du merke at i hjørnet der veggene kobles, i stedet for å trimme overskuddet av den rette ekstrusjonen, går veggene rett forbi hverandre og kobles ikke fint.

BREP Presis geometri

_6.1.7 Parametriske elementer_ Archicad-elementer kan eksporteres som parametrisk geometri, ofte i form av veiledningslinjer som ekstruderes til en avstand. Parametrisk geometri gjør det enkelt å redigere objektet etter at det er opprettet. Selv om dette alternativet beholder redigerbarhet, kan geometrien ofte være noe unøyaktig da definisjonen er en tilnærming av geometrien. Dette alternativet anbefales hvis du har til hensikt å importere IFC-en tilbake til Archicad eller et annet redigeringsprogram for å foreta ytterligere redigeringer.

BREP Eksporter geometri som separate BREP-overflater. I stedet for å beskrive objektene ved deres parametere, for eksempel lengde/bredde/høyde med genererte overflater som resultat, beskrives hver overflate som en separat overflate med en plassering i 3D. Objekter kan fortsatt inneholde flere overflater, men disse vil være løse overflater. Etter eksportering må BREP-overflater redigeres individuelt da parametere ikke lenger brukes på overflaten. Med BREP-alternativet eksporteres nøyaktige overflater uten rom for forskjell i tolking av parametere mellom forfatterverktøy. Overflater fargelegges individuelt og vil ha samme farge i Catenda Hub som de har i Archicad. Overflatfarger kan konfigureres i følgende meny:

`Alternativer -> Elementattributter -> Overflater`

Det kan være bra å konfigurere alle innstillinger for en overflate da de vil bli skrevet inn i IFC.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/10-6-1-conversions-of-archicad-elements.png)

Overflater i Catenda 3D-visningen har flat skyggelegging uten lyskilde tilstede. Dette betyr at verdier som Ambient, Attenuation, Shinyness, Emission og Specular ikke tolkes når overflaten vises i Catenda 3D-visningen. Følgende verdier tolkes av Catenda ved visning av overflaten i 3D-visningen:

Overflatfarge Fargen på overflaten

Gjennomstrålning Hvor mye du kan se gjennom objektet (overstyrer den gjennomsiktige opasitetsinnstillingen)

Diffus Hvor mørk eller lys overflatfargen er

_6.1.8 Definer IFC modellposisjon etter:_ Dette alternativet bestemmer prosjektlokasjon. Det er viktig å bli enig om et felles koordinatpunkt for referanse i prosjektet allerede i begynnelsen. Hvis dette endres, kan det bety at flere rådgivere må flytte objektene sine, noe som ofte ikke er gjennomførbart mot slutten av et prosjekt.

Undersøkelsespunkt og prosjektopprinnelse - standard Med dette alternativet vil avstanden fra (0,0,0) til modellen din i Archicad være avstanden fra (0,0,0 + koordinater for undersøkelsespunktet ditt) til modellen din i Catenda Hub + hvis du har angitt en prosjektlokasjon, vil modellen din ende opp på disse koordinatene i Catenda Hub

Kun prosjektopprinnelse Med dette alternativet vil avstanden fra (0,0,0) til modellen din i Archicad være avstanden fra (0,0,0) til modellen din i Catenda Hub.

Kun undersøkelsespunkt Med dette alternativet vil avstanden fra undersøkelsespunktet i Archicad til modellene dine være avstanden fra (0,0,0) til modellen din i Catenda Hub

## 7. **7. Hierarkiske Archicad-elementer**

Eksporter objekter i et flatt hierarki eller som nestede underelementer.

### 7.1 **7.1 Gardinvegg**

Konverter til enkelt element Behold hierarki - standard

### 7.2 **7.2 Trapp**

Konverter til enkelt element Behold hierarki - standard

### 7.3 **7.3 Gelender**

Konverter til enkelt element - standard Behold hierarki

## 8. **8. IFC-skjema-relaterte alternativer**

### 8.1 **8.1 Materialbevaringmodus (kun IFC2x3)**

_8.1.1 Aldri spreng elementer, bevaring er ikke garantert_ Med dette alternativet eksporteres hele objektet som ett objekt

_8.1.2 Spreng bare når nødvendig for å bevare materialer - standard_ Med dette alternativet eksporterer du kun separate objekter for hvert komposittmateriale hvis nødvendig

_8.1.3 Spreng alle elementer i deler, bevar materialer_ Med dette alternativet eksporteres alle objekter som separate objekter for hvert materiale. Hvis du har et komposittveggmateriale, betyr det at et separat objekt eksporteres for hvert materiale. Du har ofte en dampsperre som er 1-5 mm som vil resultere i et veldig tynt objekt. Når objekter er så tynne, kan geometrien være unøyaktig. Problematiske veggmaterialer kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/11-8-1-material-preservation-mode-ifc2x3-only.png)

Dette kan gjøre det vanskelig for programvare å kutte hull gjennom overflaten da unøyaktigheten gjør det vanskelig å fastslå nøyaktig hvor hullet skal være. Hvis du derfor merker at åpningene dine ikke blir kuttet gjennom, kan det hjelpe å slå på dette alternativet. Hvis du slår på dette alternativet, eksporteres veggen som ett enkelt objekt i stedet for mange tynne kompositteobjekter.

## 9. **9. Sammensatte strukturer og komplekse profiler**

_9.1 Splitt komplekse bygningselementer i deler_ Her kan du velge for hvilke typer elementer du vil at det sammensatte elementet skal deles opp, og for hvilke du ikke vil det. Hvis du velger dette alternativet, vil du ikke kunne ta et valg for materialbevaringmodus.

## 10. **10. Egenskapskartlegging**

Innenfor egenskapskartlegging (Fil > IFC > Interoperabilitet > Egenskapskartlegging) kan du velge hvilken type versjon av IFC du vil eksportere. Du har standard IFC2x3 og standard IFC4. Du kan også legge til psets for eksport med IFC-en din. Hvis du gjør dette, bør du lage en duplikat av IFC-skjemaet du velger.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/12-10-property-mapping.png)

Etter at du har laget en duplikat av din standard IFC, kan du legge til egenskapene du vil ha til den nye forhåndsinnstillingen ved å velge IFC-skjemaet og klikke på _Map IFC Properties for Export_.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/13-10-property-mapping.png)

## 11. **11. Datakonvertering**

Under datakonvertering velger du hva slags data i tillegg til geometri du vil få ut av IFC-eksporten din. Huk av boksene for hva du vil eksportere. Elementparametere leser Archicad-elementparameteren og konverterer den til IFC-mengder eller IFC-egenskaper. Avhengig av deres type. Ved å velge dette alternativet øker du filstørrelsen betydelig.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tjawkzdp/14-11-data-conversion.png)

IFC Base Quantities leser parametrene for størrelse, område og volum. Hvis du ikke krysser av denne boksen, kan du få problemer med å importere IFC-en din til Catenda Hub.

## 12. **12. Enhetkonvertering**

Angi lengde-, vinkel-, område-, volum-, valuta- og tidsenheter for eksporten din.
