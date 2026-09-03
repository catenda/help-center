# Arbeidsflyt Catenda Hub - Solibri

Dette er et dokument som forklarer den optimale arbeidsflyten når du arbeider med BCF-serveren mellom Solibri og Catenda Hub.

1\. Start med å koble til Catenda Hub-prosjektet ditt. [( se her )](https://intercom.help/bimsync-arena/en/articles/4670340-solibri-model-checker-and-bimsync-bcf-connection) 2\. Når du er koblet til, starter du med å kjøre clash-deteksjonen i Solibri og oppretter en presentasjon. Det finnes flere måter å opprette en presentasjon i Solibri, men jeg vil forklare den beste typen for kommunikasjon med Catenda Hub. A. Kjør kontrollen med regelsettet ditt. B. Finn et Solibri-problem du vil legge til presentasjonen din. C. I stedet for å gå til kommunikasjon og legge til bildet i presentasjonen der, høyreklikker du på problemet i kontrollresultatene og trykker på knappen "Legg til bilde". Ved å gjøre det på denne måten, vil alle objekter i det problemet automatisk inkluderes i problemet i Catenda Hub og blir lettere å finne. Dette kombinert med skjul andre, gjør andre transparent i Catenda Hub er en god måte å aldri miste oversikten over hvilke objekter som er inkludert i problemene. Når du oppretter et bilde på denne måten, får du fortsatt samme type problemoppsettet som i kommunikasjon der du kan legge til en tittel, legge til en beskrivelse, legge til ekstra bilder og kommentarer. Det samme gjelder for tildeling av personer til problemet.

![Workflow_Solibri_-_Bimsync.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/01-intro.png)

D. Når du er ferdig med kontrollen, går du til kommunikasjon og oppretter en presentasjon fra "kontrollresultater". Deretter vil alle problemene du opprettet i kontrollresultatene vises i den nye presentasjonen din. Hvis du vil legge til disse bildene i en eksisterende presentasjon, kan du høyreklikke på presentasjonen og trykke på "oppdater presentasjon fra resultater", på denne måten vil alle bildene som er opprettet i resultater, inkluderes i presentasjonen.

![Workflow_Solibri_-Bimsync__1.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/02-intro.png)

3\. Nå når du har opprettet presentasjonen, kan du begynne å synkronisere med Catenda Hub. Når du trykker på "Synkroniser presentasjon" vises en popup-meny. I denne kan du merke av i bokser for å bestemme hvordan du vil synkronisere. Hvis du går til "Verdikonvertering" kan du angi forskjellige verdier for å samsvare med verdiene i Catenda Hub-prosjektet ditt.

![Workflow_Solibri_-Bimsync__2.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/03-intro.png)

4\. Verdikonvertering. Hvis du for eksempel har tildelt et problem til en person direkte i Solibri og det ikke tildeler problemet i Catenda Hub, er grunnen til at verdikonverteringen ikke er satt opp riktig.

![Snag_62f59e4.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/04-intro.png)

Disse ansvarene som er angitt i problemet, kan angis for å samsvare med brukerne i Catenda Hub-prosjektet. Dette gjøres i verdikonvertering her:

![Snag_62c9ad3.png](https://raw.githubusercontent.com/catenda/help-center/main/images/9qp86602/05-intro.png)

Knappen for verdikonvertering vises i popup-menyen når du høyreklikker på presentasjonen og trykker på "Synkroniser presentasjon". Når disse problemene er tildelt i Solibri og synkronisert med Catenda Hub-prosjektet, vil de tildelte brukerne motta varslinger hvis varslinger er aktivert. På denne måten trenger du ikke å tildele problemene manuelt i Catenda Hub etter synkronisering med Solibri.
