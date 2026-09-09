# Revisionblokker i navngivningskonvensjoner

> Lær å konfigurere dynamiske blokker i navngivningskonvensjoner for mapper. Se hvordan filer stables som sekvensielle revisjoner, hvor du kan se resultatene, og hvordan du bruker egendefinerte felt med dokumentidentifikatoren slått av.

Når en navngivningskonvensjon er aktivert på en mappe, blir filer automatisk skannet under opplastingsprosessen for å sikre at de samsvarer med spesifikke strukturelle mønstre. Hvis lokale filnavn inneholder blokker som endres konstant med hver nye versjon, kan mappen konfigureres til å dynamisk gjenkjenne dem.

Når den er riktig konfigurert, vil opplasting av forskjellige lokale filer med varierte versjonsdata kartlegge dem til den nøyaktig samme dokumentbeholderen. I stedet for å opprette separate, rotete dokumentoppføringer for hver mindre filendring, gjenkjenner plattformen automatisk det delte grunnnavnet og stbler dem som sekvensielle revisjoner under et enkelt dokument.

## 1. Hvor du kan se dokumentdetaljene

Når filene er lastet opp, separerer plattformen rent statiske dokumentdetaljer fra endrede versjonsdata:

### 1.1 **1.1 Informasjonsmeny på høyre side**

Hvis du velger et dokument fra fillisten og utvider kategorien **Filinfo** på høyre side av siden, vises de segmenterte dataene.

_1.1.1 Dokumentinformasjon_ Dette viser data fra navngivningsblokkene som forblir konstante gjennom hele livssyklusen til dokumentet.

_1.1.2 Revisionsinformasjon_ Dette henter og viser automatisk verdiene fra endrede blokker direkte fra det opplastede filnavnet.

_1.1.3 Revisjonsnavn_ Dette viser eksplisitt det uforanderlige, originale lokale filnavnet nøyaktig slik det ble lagret på den lokale harddisken.

### 1.2 **1.2 Dokumenttabellen**

For å raskt se de originale filnavnene på tvers av hovedfillisten, kan kolonnen **"Revisjonsnavn"** (originaltnavn) slås på/av. Justeringer av kolonnesynlighet er knyttet strengt til individuelle kontoprofiler, noe som betyr at en arbeidsområde kan tilpasses uten å endre standardvisningen for resten av teamet.

## 2. Konfigurere endrede revisionblokker

For å bygge en navngivningskonvensjon som rent isolerer endrede versjonsmarkører fra statiske dokumentnavn, må individuelle blokkoppførsler justeres innenfor konvensjonsinnstillingene. Navigering til navngivningskonvensjoner-siden gjøres innenfor prosjektinnstillingene. _Tilgangsrettighetskrav:_ Administrator

### 2.1 Den kritiske innstillingen: Slå av dokumentidentifikatoren

For enhver blokk som endres per revisjon, må **dokumentidentifikatoren** slås **av**. Denne innstillingen sikrer at plattformen validerer tegnene under opplastingen for å opprettholde konsistensen, men fjerner dem når du ferdigstiller det faktiske dokumentnavnet.

Dette er den nøyaktige mekanismen som lar filer med varierende versjonsstrenger stable seg pent som revisjoner i stedet for å generere helt nye dokumenter.

### 2.2 Bruk av egendefinerte feltkilder

For å kontrollere nøyaktig hvilke tegn som er tillatt i disse dynamiske blokkene, tilordnes egendefinerte felt som blokkkilden **Source**. Avhengig av sporingsbehovene, kan ulike felttyper brukes til å fremtvinge valideringsbegrensninger:

_2.2.1 Egendefinerte tekstfelt_ Dette alternativet tillater et fleksibelt eller fast antall tegn for standard alfanumeriske inndata.

_2.2.2 Rullegardin egendefinerte felt_ Dette alternativet begrenser blokken til et forhåndsdefinert sett med spesifikke verdier, opp til en grense på 1000 alternativer. Dette er svært fordelaktig når korte filnavnkoder må kartlegges til fulle, beskrivende navn inne på plattformen.

_3.2.3 Egendefinerte heltallfelt_ Dette alternativet tvinger blokken til å strengt godta tall. Merk at mens det sikrer at bare numeriske poster blir brukt, vil systemet godta hvilket som helst gyldig heltall i stedet for å tvinge en streng, trinn-for-trinn sekvensiell opptelling.
