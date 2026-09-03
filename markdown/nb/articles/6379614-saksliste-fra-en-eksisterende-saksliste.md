# Saksliste fra en eksisterende saksliste

Du kan opprette en ny saksliste ved å klikke på handlingen for ny saksliste på [sakliste-siden](https://support.catenda.com/en/articles/9413644-boards-page). Handlingen finner du med den grønne plusskjermen øverst til høyre eller i dens tilstøtende handlingsmeny. Tilgang som kreves: Skrivetilgang for å opprette nye saklister i tilgangsmeny på [prosjektinnstillingssiden](https://support.catenda.com/en/articles/4670273-project-settings-page).

Slik kan den nye sakliste-siden se ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/01-intro.png)

## 1. **Navn**

Gi saklisten et navn som minimumsforutsetning for å legge til saklisten. Sakliste-listen sorteres etter sakliste-navn i henhold til den typiske [sorteringsrekkefølgen for lister](https://support.catenda.com/en/articles/8487788-sorting-order-of-lists) på Catenda. Det er derfor ofte en god idé å bruke en navnekonvensjon når du navngir saklister. Her er et eksempel på hva saklister kunne hete:

![Saksliste introduksjon Dokumenter vurdering Viderefør Viderefør med kommentarer Til oppfølging Dokumenter breeam socre koordinering kostnad prosjekter](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/02-name.png)

## 2. **Beskrivelse**

Beskrivelsen av saklisten er valgfri og kan senere bare sees i sakliste-innstillinger av de med full tilgang til saklisten. Beskrivelsen av saklisten følger de generelle reglene for [formatering av innlegg](https://support.catenda.com/en/articles/8430847-formatting-of-posts) på Catenda.

## 3. **Kopier innstillinger fra en eksisterende saksliste**

For å kopiere innstillinger fra en saksliste ved opprettelse av saksliste, klikker du på "kopier innstillinger fra en eksisterende saksliste"-menyen for å velge en eksisterende saksliste i prosjektet som innstillingene skal kopieres fra.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/03-copy-settings-from-an-existing-topic-board.png)

Etter å ha valgt saklisten er det mulig å velge hvilke innstillinger som skal kopieres.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/00aszxqg/04-copy-settings-from-an-existing-topic-board.png)

### 3.1 **Kopier statuser og typer**

Aktiver radioknappen for kopiering av statuser og typer for å få de samme statusene med deres statusnavn, farge og meta-statustype i saklisten som skal opprettes.

### 3.2 **Kopier tilgangsinnstillinger**

Aktiver radioknappen for kopiering av tilgangsinnstillinger for å få de samme statusene med deres farge i saklisten som skal opprettes.

## 4. **BCF 1.0-kompatibilitet**

Topic boards som brukes til eksport av topics til andre topic management-verktøy som kun støtter BCF opp til versjon 1.0, bør låses for kompatibilitet for å sikre at topics som genereres i Catenda ankommer uten feil på den andre siden. BCF 1.0-topics som genereres andre steder kan importeres til hvilket som helst topic board uavhengig av om topic board er låst for kompatibilitet eller ikke.

### 4.1 **Ingen redigering av statuser eller typer**

Ved å låse et topic board for kompatibilitet vil det ikke være mulig å redigere statusene og typene som er tilgjengelige i topic board. Så lenge topic board er låst for kompatibilitet, gjøres de forhåndsdefinerte statusene og typene som spesifisert i BCF 1.0 tilgjengelig og kan ikke redigeres. _Statuser:_ "Åpen" og "Lukket" _Typer:_ "Feil", "Advarsel", "Info" og "Ukjent"

### 4.2 **Låsing og opplåsing av BCF 1.0-kompatibilitet etter opprettelse**

Avmerkingsboksen for BCF 1.0-kompatibilitet kan fjernes merking fra topic board-innstillingene når som helst for å utvide antallet statuser som det er mulig å ha i topic board. Hvis statusene i et topic board ikke er kompatible med BCF 1.0, er det også mulig å fjerne eventuelle inkompatible statuser og låse topic board til BCF 1.0-kompatibilitet igjen når som helst etter opprettelse.

### 4.3 **Kopier innstillinger fra låst saksliste**

Hvis en saksliste velges i menyen for kopiering av innstillinger fra en annen saksliste, er avmerkingsboksen for BCF 1.0-kompatibilitet låst og vil være merket av eller ikke avhengig av om den valgte saklisten å kopiere innstillinger fra er låst til BCF 1.0-kompatibilitet eller ikke.

## 5. **Legg til**

Klikk på Legg til for å legge til den nye saklisten.

> **Merknad:** Saklisten må minst ha et navn for å kunne legges til

Det er ingen varsling ved opprettelse av saksliste.

## 6. **Opprettelse av saksliste ved prosjektopprettelse**

Når et nytt prosjekt opprettes, starter prosjektet med en standard saksliste kalt "Saker". Hvis avmerkingsboksen for saklister fra et malprosjekt er merket av ved prosjektopprettelse, starter prosjektet med saklister og sakliste-innstillinger fra det valgte malprosjektet.

> **Merknad:** Selv om innstillingene for disse nye saklisten er de samme som i saklisten i malene, er GUID-ene for saklisten, statusene og typene unike for prosjektet de er i.
