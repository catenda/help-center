# Revisjonskontroll for navnekonvensjon

> Feilsøk opplastingsfeil for filer og feil ved stabling av revisjoner i mapper med navnekonvensjoner. Løs problemer forårsaket av en inkorrekt aktivert dokumentidentifikator og lær å identifisere tillatte egendefinerte feltVerdier fra forhåndsvisningen

Når en navnekonvensjon er aktivert på en mappe, stammer opplastingsfeil for filer eller feil ved stabling av revisjoner typisk fra to vanlige konfigurasjonsproble­mer.

## 1. **1. Feil aktivering av dokumentidentifikator**

Et vanlig problem oppstår når **dokumentidentifikatoren** er feil satt til **På** for en blokk som endres med hver revisjon. Når dette alternativet er aktivt, blir det skiftende variabelfeltet integrert i det permanente dokumentnavnet i stedet for å bli isolert til revisjonsmetadataene.

Følgelig vil den første reviseringen lastes opp uten problemer, men enhver påfølgende fil med en endret variabelverdi vil ikke samsvare med det etablerte dokumentnavnet. Denne uoverensstemmelsen får systemet til å avvise filen, og angir at den ikke følger konvensjonen. For å løse dette problemet må blokkonfigurasjonen oppdateres for å slå av dokumentidentifikatoren **Av**. _Tilgang som kreves:_ Administrator

## 2. **2. FeltVerdier som ikke samsvarer**

Opplastingsfeil kan også oppstå hvis teksten i den dynamiske blokken ikke samsvarer med valideringsreglene eller de spesifikke verdiene som er etablert for det underliggende egendefinerte feltet. For eksempel vil det å sette alfabettiske tegn inn i et heltallsegendefinert felt, eller å skrive inn en setning som ikke er eksplisitt definert i et rullegardinegendefinert felt, resultere i en uoverensstemmelse i konvensjonen.

### 2.1 **2.1 Slik identifiserer du tillatte verdier**

For å kontrollere de eksakte kravene til en navnekonvensjonsblokk, kan regelkonfigurasjonen vurderes direkte fra dokumentgrensesnittet:

1. Utvid informasjonsmenyenhen på høyre side for et eksisterende dokument i den berørte mappen.
1. Vurder delen **Forhåndsvisning av navnekonvensjon**, som gir en sanntids visuell nedbrytning av hva navneregelen forventer.
1. Hold musepekeren over den spesifikke versjon- eller statusblokken for å se konfigurasjonsreglene.
1. Identifiser det nøyaktige egendefinerte feltet som driver blokken, for å oppdage hvilke spesifikke verdier som er tillatt, slik at det lokale filnavnet kan justeres til å samsvare.
