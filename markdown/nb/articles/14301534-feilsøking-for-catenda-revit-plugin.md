# Feilsøking for Catenda Revit-plugin

Feil som kan oppstå med Catenda Revit-plugin og hvordan du løser dem, er forklart i denne artikkelen.

## 1. **Last opp IFC**

I feltene for filnavn og kommentar i dialogboksen for opplasting av modell støttes kun ASCII-tegn for opplasting. For å finne ut hvilke tegn som er i ASCII-settet, se [denne Wikipedia-artikkelen](https://en.wikipedia.org/wiki/ASCII).

Tegn som ikke er ASCII, kan legges til i fil- og kommentarfeltene slik:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0bx8b1nt/01-upload-ifc.png)

Når du klikker Last opp, vises følgende feilmelding:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/0bx8b1nt/02-upload-ifc.png)

```
Ubehandlet unntak har oppstått i en komponent i programmet. Hvis du klikker Fortsett, vil programmet ignorere denne feilen og forsøke å fortsette. Forespørselshoder må bare inneholde ASCII-tegn.
```

Vennligst start Revit på nytt etter å ha støtt på denne feilen for å fortsette opplastingen.

## 2. **Administrer Lenker-vindu**

Etter installasjon av Catenda Revit-plugin i Revit 2025 som ble oppdatert etter mars 2026, vil Revit krasje når du forsøker å åpne Administrer Lenker-vinduet. Dette skyldes en endring fra Autodesk. Klikk [her](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Program-crash-on-certain-machines-when-opening-the-Manage-Links-dialog-in-Revit.html) for en løsning. Vær oppmerksom på at bare Revit 2025 er berørt. Dette problemet finnes ikke i Revit 2026.

## 3. **Støttede Revit-utgaver**

Catenda-tillegget er kompatibelt med Revit-utgaver som støtter Revit API (Application Programming Interface). Integrasjon er mulig i følgende miljøer:

_Standard Revit_ Full støtte er gitt for multidisiplinær versjon av programvaren, som omfatter **Architecture**, **Structure** og **MEP** (Mechanical, Electrical, and Plumbing)-verktøysettene.

_Utdanningsversjon_ Lisenser utstedt til studenter og lærere støtter installasjonen av tredjepartstillegg, forutsatt at installasjonen er fullversjonen av programvaren og ikke LT-versjonen.

### 3.1 **Ikke-støttet utgave: Revit LT**

Det er viktig å merke seg at [Revit LT ikke støtter tredjepartstillegg eller plugins](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/Revit-LT-Is-it-possible-to-use-plugin-or-addins-in-Revit-LT.html), inkludert Catenda Revit-tillegget. Dette er en begrensning av LT-plattformens programarkitektur, da den mangler det nødvendige API-rammeverket. Følgelig er det ikke mulig å installere tillegget eller bruke Dynamo-basert automatisering i Revit LT-miljøet.

### 3.2 **Versjonkompatibilitet**

For å sikre samsvar med de nyeste programvareoppdateringene og ytelsesforbedringer, oppdateres integrasjonene regelmessig. For en omfattende liste over støttede årsversjoner for både Revit-tillegget og Dynamo-pakken, bør det refereres til [Plugins and Integrations](https://support.catenda.com/en/articles/8396532-catenda-plugins-integrations)-artikkelen.

## 4. Catenda Hub Dynamo-pakke

For arbeidsflyter som krever egendefinert automatisering, er en spesialisert pakke tilgjengelig for base Dynamo. Dette er ikke et separat program, men en samling noder for bruk i standard Dynamo-miljøet.

_Lisensiering_ Ingen ekstra Autodesk-lisens er påkrevd for å bruke Dynamo, da det er inkludert som en kjernefunksjon i standard Revit-lisensen.

_API-tilgang_ Bruk av denne pakken krever Catenda API-tilgang. Selv om dette ikke er inkludert for alle klienter som standard, kan tilgang forespørres gjennom Catenda-støtteportalen. Når det er gitt, tillater API-tilgang samhandling på tvers av alle prosjekter i en organisasjon.

_Installasjon_ Distribusjon av pakken krever manuell installasjon ved å angi filplasseringen i Dynamo-grensesnittet.

### 4.1 **Operasjonell advarsel for Dynamo-brukere**

Før bruken av denne pakken begynner, utstedes en advarsel om at disse verktøyene muliggjør handlinger innenfor et prosjekt som om aktøren var et program i stedet for en individuell bruker. Med store muligheter kommer stort ansvar. Handlinger utført på applikasjonsnivå, for eksempel slettinger, behandles annerledes enn standard brukerhandlinger. Elementer eller data slettet av et program kan ikke gjenopprettes. Ekstrem forsiktighet oppfordres når du bruker disse verktøyene innenfor et prosjektmiljø. For å be om API-tilgang eller Dynamo-pakken, kontakt [support@catenda.com](mailto:support@catenda.com) eller via boblesamtalen øverst til høyre på plattformen.
