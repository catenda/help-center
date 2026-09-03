# Storey Configurator-side

> Hvordan ha en PDF som overlegg i 2D-visningen

Ved å konfigurere etasjer i et prosjekt kan forberedte visninger i [2D-visningen](https://support.catenda.com/en/articles/4854537-2d-viewer) opprettes for medlemmer i prosjektet. Siden Storey Configurator finner du som en delside av [modellsiden](https://support.catenda.com/en/articles/4670286-models-page). Navnene Storey og Building som brukes her, stammer fra IFC-standarden. Selv om begrepene Storey og Building ofte brukes mer innen sosial infrastruktur, er dette verktøyet like nyttig, om ikke mer nyttig, for fysiske eller digitale infrastrukturprosjekter. _Tilgangskrav:_ Prosjektadministrator

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/01-intro.png)

I et prosjekt kan medlemmer sammensette etasjer ved å slå på og av 2D-visninger med generert geometri fra ulike modeller som er tilgjengelige i prosjektet. Konfigurer en etasje for å gjøre en konfigurert etasje med genererte 2D-visninger fra et sett av modeller tilgjengelig for medlemmer i prosjektet. Plasser et PDF-dokument som underlag i en etasje for å vise linjering som ellers kanskje ikke er synlig i den genererte geometrien fra modellen.

Slik kan siden for storey configurator se ut i et nytt prosjekt:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/02-intro.png)

Slik kan en konfigurert etasje med et underlagt tegning se ut

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/03-intro.png)

## 1. **Handlinger**

Handlingsmenyen på siden for storey configurator finner du ved å åpne de tre prikkene til høyre for den grønne plusskappen øverst til høyre.

![Legg til ny bygning](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/04-actions.png)

### 1.1 **Legg til ny bygning**

Klikk [her](https://support.catenda.com/en/articles/12291366-storey-configurator-actions) for å lese mer om hvordan du legger til en ny bygning.

### 1.2 **PDF**

For å fullføre trinnene i denne artikkelen trenger du en PDF-plan for hver etasje der du vil ha en PDF som underlag.

> **Merk:** Hver etasje må være i en separat PDF. En etasje kan ha flere PDF-er

## 2. **Oppsett**

Sett visningen din slik at du kan se 2D-modellen og alle modellene dine.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/05-setup.png)

## 3. **Etasjekonfigurasjon**

Her justerer du PDF-planen din med 2D-visningen din. Dette må gjøres en gang for hver etasje.

Som standard har du en bygning i oversikten din. Dette inneholder også nivaene for den importerte IFC-filen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/06-storey-configuration.png)

Det er viktig å angi et navn for bygningen, da det vises senere, så velg noe som er selvforklarende.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/07-storey-configuration.png)

Hvert IFC-nivå er representert i en etasje. Her kan du angi navn og høyde.

> **Merk:** Endring av høyden vil endre representasjonen av 2D-visningen din.

Innenfor etasjen kan du angi overlegget ved å klikke på "Vis ekstra alternativer"

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/08-storey-configuration.png)

Her ser du funksjonen "Tegninger knyttet til etasjen". Klikk på Legg til.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/09-storey-configuration.png)

En dialog åpnes og ber deg om den opplastede PDF-filen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/10-storey-configuration.png)

Når du har valgt ønsket PDF, klikker du på Legg til dette dokumentet. Dette tar deg til justeringsdialogen.

## 4. **Justeringsdialog**

Her definerer du overlegget og posisjonerer det.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/11-alignment-dialogue.png)

Bygningen din bør være valgt nå. Alt som gjenstår, er å velge etasjen du vil justere tegningen din mot.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/12-alignment-dialogue.png)

Nå bør du se den valgte PDF-en og den valgte etasjen på skjermen din.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/13-alignment-dialogue.png)

Med markør A og B definerer du posisjonen til overlegget. Punktene du velger må samsvare. Det er best å velge skjæringspunktet for to rutenett for eksempel.

Bruk markøren via dra og slipp for å plassere dem. Du kan også zoome ved å scrolle i tegningen.

Etter å ha plassert dem, klikker du på "Neste: Bekreft resultat"

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/14-alignment-dialogue.png)

### 4.1 **Viderefør dialog**

Etter at du har bekreftet posisjonen til markørene, åpnes videorefør-dialogen. Her kan du se på overlegget for å se om det fungerer for deg.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/15-approve-dialogue.png)

Her kan du alltid gjøre en endring ved å klikke på Forrige: Plasser modell- og tegnepunkter. Når du er fornøyd med justeringen, bekrefter du ved å klikke på Viderefør.

Dette bringer deg tilbake til Storey Configurator, og nå kan du sette opp neste etasje. Plassering av tegninger kan også endres i denne dialogen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/16-approve-dialogue.png)

**Viktig:** Her må du klikke på lagre konfigurasjonen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/17-approve-dialogue.png)

## 5. **Hvordan bruke det**

Nå som alt er konfigurert, kan du bruke det i det daglige arbeidet. Etter at byggekonfigurasjonen din er behandlet, kan du oppdatere siden. Hvis du befinner deg i modellvisningen din og åpner 2D-visningen, er det et alternativ for å velge bygningen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/18-how-to-use-it.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/19-how-to-use-it.png)

Velg den nettopp omdøpte bygningen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/20-how-to-use-it.png)

Og PDF-overlegget ditt vil være synlig.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hn8gfwtp/21-how-to-use-it.png)

Storey configurator vil alltid vise den nyeste revisjonen av den justerte tegningen(e)
