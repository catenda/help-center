# Tilgangstyring på saksliste

> Tilgangskontrollnivåer på sakslister

Du kan finne tilgangsstyringen for en saksliste ved å klikke på [rediger tilgang](https://support.catenda.com/en/articles/4670277-issue-board-settings#h_82063f7a79) i [tilgangskontrollmenyen](https://support.catenda.com/en/articles/4670277-issue-board-settings#h_7a3aca4c7d) på siden for [saksliste-innstillinger](https://support.catenda.com/en/articles/4670277-issue-board-settings). _Tilgang kreves:_ Full tilgang til sakslisten

Dialogboksen for redigering av tilgangskontroll kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/66bsqhfn/01-intro.png)

## 1. **Informasjon om saksliste**

Her vises navn og eier av sakslisten

## 2. **Utvidelser - Lukk saker**

Begrens hvem som kan lukke og gjenåpne saker ved å begrense hvem som kan endre statusen for en sak fra en status med åpen metastatus til en status med lukket metastatus. Når du aktiverer denne funksjonen vil du se en [lukk saker-kolonne](#h_3e36186c6f) vises ved siden av tilgangskolonnen.

## 3. **Definer tilgang for**

Her vil du kunne spesifisere hvem som har hvilken tilgang til denne sakslisten. Ved å klikke på "Medlem eller team"-rullegardinmenyen vil du kunne definere tilgang for medlem(mer) eller team(s). Når du har valgt et medlem eller team vil de vises i listen nedenfor.

## 4. **Rolle-kolonne**

I rolle-kolonnen beskrives de ulike rollene i prosjektene

### 4.1 **Administratorer**

_Standard_ - Full tilgang Medlemmer som er administratorer har alltid full tilgang. Prosjekteieren er en administrator.

### 4.2 **Brukere**

_Standard_ - Skrivetilgang Tilgang gitt til individuelle medlemmer overstyrer alltid tilgang gitt til team, alle brukere og eiere.

### 4.3 **Alle brukere**

_Standard_ - Skrivetilgang Alle brukere er betegnelsen som brukes for medlemmer som ikke har fått spesifikk tilgang som bruker, team eller eier av saksliste.

### 4.4 **Team**

_Standard_ - Skrivetilgang Tilgang gitt til team settes for alle medlemmene i teamet med mindre medlemmet har spesifikk tilgang som bruker eller eier av saksliste.

### 4.5 **Eier av saksliste**

_Standard_ - Full tilgang Når du oppretter innhold i Catenda blir du **eier** av innholdet. Eierinnstillinger gjelder for eieren av innholdet.

> **Merk:** Brukere vil få den høyeste tillatelsen som er angitt i **alle brukere**, **eiere** og **team**.

> **Tips:** **Eksempel:** Du kan bruke **team** eller **eiere** for å gi brukere mer tillatelse enn **alle brukere**, men ikke for å gi dem mindre tillatelse.

Årsaken til dette er å forhindre brukere fra å gi seg selv mer tilgang ved å fjerne seg selv fra et team eller som en eier.

## 5. **Tilgangsnivåer**

Det finnes fire definerte tilgangsnivåer. Tilgangen som gjelder er den høyeste tilgangen som medlemmer har fått enten gjennom bruker-tilgang eller gjennom tilgang som er konfigurert for noen av deres team.

### 5.1 **Ingen tilgang**

Medlemmer uten tilgang vil ikke kunne få tilgang til sakslisten.

### 5.2 **Lese**

Medlemmer med lesetilgang har tilgang til sakslisten, men kan ikke opprette saker eller kommentere eksisterende saker.

### 5.3 **Skriv**

Medlemmer med skrivetilgang kan gjøre det samme som medlemmer med lesetilgang. Medlemmer med skrivetilgang kan også opprette nye saker og kommentere eksisterende saker.

### 5.4 **Full tilgang**

Medlemmer med full tilgang kan gjøre det samme som medlemmer med lese- og skrivetilgang. Med full tilgang kan medlemmer også redigere tilgangsinnstillingene for denne sakslisten. Medlemmer med full tilgang kan legge til og endre egendefinerte felt på denne sakslisten. Administratorer har alltid full tilgang. Medlemmer med full tilgang kan ikke redigere administratortilgang.

## 6. **Sak**

Tabellen nedenfor viser operasjoner som kan utføres på en sak til tilgangsnivåene for sakslisten den er i.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 227px; padding: 8px;"><h2 id="h_b8c3cd8ee9">Operasjon</h2></td><td style="background-color: #e3e7fa80; width: 73px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_eaddbaa490">Lese</h2></td><td style="background-color: #e3e7fa80; width: 195px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_8b71241e18">Skriv</h2></td><td style="background-color: #e3e7fa80; width: 50px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_138755bddc">Fullt</h2></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_6eae5730c8">Admin</h2></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vis innhold</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>​</p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Vis sakshistorikk</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Del sak</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Opprett saksliste</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Opprett sak i liste</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Endre navn på sak</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Endre sakens topptekst-felt</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Endre status fra status med åpen metastatus til status med lukket metastatus</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x og lukk saker-utvidelse merket hvis aktivert</p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Rediger saksbeskrivelse</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Avmerk bokser i beskrivelse</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Opprett sakskommentar</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Rediger sakskommentar</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x kun kommentarskaper</p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Avmerk bokser i kommentar</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x kun kommentarskaper</p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Slett sakskommentar</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x kun kommentarskaper</p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Slett sak</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Arkiver saksliste</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Endre saksliste ACL</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Flytt sak</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td></tr></tbody></table></div>

## 7. **Lukk saker-kolonne**

Avmerkingsboksene i denne kolonnen bestemmer om disse brukerne får tillatelse til å lukke saker eller ikke. Nederst i listen vil det også vises et alternativ for saksoppretter. Saksoppretter-elementet lar deg gi ekstra tillatelser til oppretteren av en sak. Denne regelen gjelder bare når saksoppretteren ikke er oppført under "Brukere" og har skrivetilgang.

Hvis lukk saker-alternativet er avmerket for en bruker, vil de ikke lenger kunne:

- Opprett lukkede saker
- Lukk eksisterende saker
- Endre statusen for en sak som er lukket

La eieren lukke sin egen sak da bare de vet best om alt ble håndtert eller ikke. La et team kalt "teamledere" eller "anmeldere" lukke sakene da bare de har myndighet til å lukke sakene.

## 8. **Lagre-knapp**

> **Merk:** Husk å trykke Lagre-knappen og last inn på nytt etter at du er ferdig for å se endringene.

## 9. **Konfigurert eksempel**

Slik kan tilgangskontroll-dialogboksen se ut etter at den er konfigurert:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/66bsqhfn/02-configured-example.png)
