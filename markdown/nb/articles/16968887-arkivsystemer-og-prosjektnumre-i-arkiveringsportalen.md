# Arkivsystemer og prosjektnumre i arkiveringsportalen

> Hvilket eksternt arkivsystem portalen sender til, og hvilket prosjektnumreringsskjema det registrerer.

De andre artiklene i Arkiveringsportalen beskriver arkivsystemet og prosjektnummeret i generelle termer, fordi det som ligger bak dem, avhenger av organisasjonen. Denne artikkelen navngir det som portalen støtter for øyeblikket.

## 1. **Arkivsystemet: WebSak+**

Portalen sender til **WebSak+**, arkivsystemet levert av **Acos**.

En innsending går ikke direkte inn i WebSak+. Portalen samler elementets metadata som XML og sender det til Acos sin innsendingtjeneste, som utfører arkiveringen. Referansen som denne tjenesten returnerer, er det som **Arkivert**-fanen viser under **ACOS Ref**, så sitér den når du må spørre om ett spesifikt arkivert element.

Dette er også hvorfor feilårsakene på **Arkivert**-fanen er formulert som grenser for det mottakende arkivet: maksimalt 50 filer og maksimalt 2300 MB per innsending.

## 2. **Prosjektnummerering: Agresso**

**Prosjektnummeret** i **Innstillinger** er et **Agresso-prosjektnummer** på 8 tegn.

> **Viktig:** Nummeret skrives inn i portalen fordi det er nummeret som er registrert mot prosjektet i WebSak+. Det er ingen forbindelse mellom Arkiveringsportalen og Agresso selv. Ingenting leses fra eller skrives til Agresso, og ingen validering utføres mot det, så skriv nummeret nøye. Portalen kan ikke fortelle deg at det er feil.

## 3. **Alt annet**

Portalen er bygd for openBIM-prosjektdata i Catenda Hub, så dokumentene og sakene den tilbyr kommer fra Catenda Hub og ingen andre steder.

For å få prosjektdata ut av Catenda Hub på andre måter, inkludert eksporter, langvarige formater og det fryste arkivalternativet, se [Eksporterer alle prosjektdata](https://support.catenda.com/nb/articles/7946690-exporting-all-project-data).
