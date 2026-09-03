# Microsoft Teams Varsel Feilsøking

I denne artikkelen finner du informasjon om feilene som kan oppstå når du konfigurerer Microsoft Teams Varsel med Catenda via Microsoft Teams Workflows.

Denne artikkelen inneholder informasjon om følgende saker: [Ingen Varsel](#h_42fb432d1c)

## 1. **Ingen Varsel i Microsoft Teams-kanal**

Hvis en Microsoft Teams Workflow-URL har blitt konfigurert i Catenda og en Catenda-varsling for en av varslingsinnstillingene som er merket av i Microsoft Teams-fanen for varsling har blitt mottatt, men det er ingen melding i Microsoft Teams-kanalen som har blitt konfigurert der, er det sannsynligvis et problem med Microsoft Teams Workflow.

For å se om noe har gått galt med Microsoft Teams Workflow, velger du Workflows enten ved å holde musepekeren over kanalen og klikke på de tre prikkene eller ved å klikke på de tre prikkene øverst til høyre i en kanal.

<img alt="Microsoft Teams-kanalhandlingsmeny, Arbeidsflyter uthevet." src="https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/inline-f533eea19d48.png" width="290"/>  \<---> <img alt="Handlingsmeny i Microsoft Teams-kanal, Arbeidsflyter uthevet." src="https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/inline-1a6a43fe9eec.png" width="290"/>

Hvis noe er galt med arbeidsflyten, kan en feil vises i arbeidsflyten Send webhook-varsler til en kanal i menyen Dine arbeidsflyten.

![Microsoft Teams En tilkoblingsfeil har oppstått som krever din oppmerksomhet](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/01-no-notifications-in-microsoft-teams-channel.png)

En feil kan være: `En tilkoblingsfeil har oppstått som krever din oppmerksomhet`

Klikk på arbeidsflyten for å åpne arbeidsflyten i den foretrukne nettleseren, eller klikk på Detaljer for å se mer informasjon i Microsoft Teams. Dette er hvordan detaljene i Webhook-arbeidsflyten kan se ut i Microsoft Teams når det er en feil.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/02-no-notifications-in-microsoft-teams-channel.png)

Her kan du se tidspunktet og datoen da feilen oppstod. Klikk på tidspunktet og datoen for feilen for å åpne arbeidsflyten i Power Automate i den foretrukne nettleseren. Dette er hvordan feilen kan se ut i Power Automate:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/03-no-notifications-in-microsoft-teams-channel.png)

Varslingen i Power Automate gir oss flere indikasjoner på hva som kan være galt. I dette tilfellet har følgende feilmelding dukket opp:

`Varsel: Din <email>-tilkobling fungerer ikke: Det ser ut til at <email>-tilkoblingen for flyten din må logges inn på nytt. Den vanligste årsaken er et endret passord eller en policy fastsatt av leieadministratoren. Tilkoblinger kan også kreve gjenautentisering hvis multifaktorautentisering nylig har blitt aktivert for kontoen din.`

For å gjenautentisere, klikker du på arbeidsflyten i Teams og åpner arbeidsflyten i Power Automate. Det er også mulig å gå til tilkoblingssiden i Power Automate og etablere en tilkobling der.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/04-no-notifications-in-microsoft-teams-channel.png)

Klikk på Gjenautentiser i dialogboksen Handling påkrevd. Etter vellykket autentisering bør tilkoblingen vises på siden Tilkoblinger.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/05-no-notifications-in-microsoft-teams-channel.png)
