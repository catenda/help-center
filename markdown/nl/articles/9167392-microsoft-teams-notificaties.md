# Microsoft Teams-notificaties

> Blijf op de hoogte zonder van tabblad te wisselen. Verbind Catenda Hub met Microsoft Teams om real-time notificaties rechtstreeks in uw voorkeurkanalen te ontvangen.

Ontvang real-time notificaties van een Catenda-account rechtstreeks in een Microsoft Teams-kanaal door een Microsoft Teams-workflow te configureren in de Catenda-notificatie-instellingen. _Vereiste toegang:_ Een **Microsoft Teams**-account met machtigingen voor kanaalcreatie en Microsoft Teams-workflowbeheer.

Het tabblad Microsoft Teams-notificaties vindt u bovenaan de [pagina met accountnotificatie-instellingen](https://support.catenda.com/en/articles/8272435-account-notification-settings) die een subpagina is van de [pagina Accountnotificaties](https://support.catenda.com/en/articles/7439223-account-notifications-page):

![Catenda Hub Notification settings Microsoft Teams notificaitons Projects with own Teams settings](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/01-intro.png)

Zo kunnen Catenda-notificaties eruit zien in Microsoft Teams nadat een Microsoft Teams-workflow is geconfigureerd.

![Microsoft Teams channel Posts REady for review created a new topic a new revision was imported in model](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/02-intro.png)

---

### Stap 1: Een toegewezen kanaal voorbereiden

Gebruikers kunnen hun projectupdates organiseren door een specifieke ruimte voor Catenda-notificaties te maken. 1\. Selecteer in **Microsoft Teams** het tabblad **Teams** of **Chat**. 2\. Gebruik een bestaand team (sla deze stap over) of **maak een team**.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/03-step-1-prepare-a-dedicated-channel.png)

Voer een naam in en maak het team.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/04-step-1-prepare-a-dedicated-channel.png)

Wanneer een team wordt gemaakt, wordt automatisch een kanaal genaamd 'algemeen' toegevoegd. 3\. Gebruik een bestaand kanaal (sla deze stap over) of voeg een kanaal toe. Klik met de rechtermuisknop op een team en selecteer 'Kanaal toevoegen' in het actiemenu of klik op het team en klik op **Kanaal toevoegen** rechtsboven. _Vereiste toegang:_ Eigenaar of lid van team.

![Microsoft teams Catenda Integration Chat Channels Add channel Members Analytics Apps Tags Hidae all channels Add member Manage team Manage tags Copy link Leave team](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/05-step-1-prepare-a-dedicated-channel.png)

> **Opmerking:** Met gast- of externe toegang kunnen kanalen niet worden gemaakt. Vraag in dit geval een kanaalbeheerder om u een URL te geven waarnaar notificaties naar een kanaal kunnen worden verzonden.

Nadat u op 'Kanaal maken' hebt geklikt, verschijnt het dialoogvenster 'Kanaal maken':

![Create a channel Channel name Letters, numbers and spaces are allowed Description Choose a channel type Standard Private Threads Posts](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/06-step-1-prepare-a-dedicated-channel.png)

**4. Geef uw kanaal een naam**: Gebruik iets duidelijks zoals "Catenda-notificaties" of "Project-A-Notificaties".

**5. Kies privacy**: Catenda-notificaties kunnen naar zowel standaard- als privékanalen worden verzonden.

- Selecteer **Standaard** als u wilt dat het hele team de updates ziet.
- Selecteer **Privé** als de notificaties alleen voor u of een specifieke groep zijn.

6\. Klik op **Maken**.

---

### Stap 2: Uw Teams Webhook-URL genereren

In het verleden werden Catenda Teams-notificaties geconfigureerd via een Webhook Connector-toepassing die voor het kanaal was geconfigureerd. De Webhook Connector-toepassing is inmiddels beëindigd. De huidige manier om een webhook-URL te maken is door een Microsoft Teams-workflow te maken.

Volg deze stappen om een nieuwe Microsoft Teams **Workflow**-webhook te maken. 1\. Open **Microsoft Teams** 2\. Beweeg over het gewenste team en klik op de drie puntjes of klik op de drie puntjes rechtsboven nadat u het kanaal hebt geopend. 3\. Selecteer Microsoft Teams **Workflows** uit het actiemenu

<img alt="Microsoft Teams channel action menu, Workflows highlighted." src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-f533eea19d48.png" width="290"/>  \<---> <img alt="Action menu in Microsoft Teams channel, Workflows highlighted." src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-1a6a43fe9eec.png" width="290"/>

4\. Zoek naar **"Webhook-meldingen naar een kanaal verzenden"** en selecteer het.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/07-step-2-generate-your-teams-webhook-url.png)

5\. Volg de instellingsstappen om uw Team en Kanaal te selecteren. **6. Kopieer de URL**: Nadat de Microsoft Teams-workflow is gemaakt, kopieert u de gegenereerde webhook-URL naar uw klembord door bovenaan op 'Webhook-koppeling kopiëren' te klikken.

> **Opmerking:** 💡**Tip**: Houd deze URL privé. Iedereen met deze koppeling kan berichten naar uw Teams-kanaal sturen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/08-step-2-generate-your-teams-webhook-url.png)

---

### Stap 3: Verbinden met Catenda Hub

Volg deze stappen om de webhook-koppeling in Catenda te configureren. Op deze manier weet Catenda waar de projectmeldingen naartoe moeten worden verzonden.

1. Log in op **Catenda Hub**.
1. Navigeer naar uw **Notificaties>Instellingen** (Account- of projectniveau).
1. Selecteer het tabblad "Microsoft Teams" en scroll helemaal naar beneden.
1. Plak uw gekopieerde URL in het veld **Webhook-URL**.
1. Klik op **Opslaan**.

    <div class="intercom-container intercom-align-center"><img height="320" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-a60f9c2dbac8.png" style="height: auto;" width="500"/></div>

1. **Notificaties inschakelen**: Controleer dat de schakelaar bovenaan de pagina op **Aan** staat.

    <div class="intercom-container intercom-align-center"><img height="159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-a3e9aa9365d2.png" style="height: auto;" width="500"/></div>

---

### Stap 4: Uw meldingen aanpassen

Pas de informatie die u ontvangt aan om meldingsoversaturation te voorkomen. 1\. Blader in hetzelfde menu **Notificatie-instellingen** door de lijst met notificatietypen. **2. Vink de vakjes aan** voor de specifieke updates die u in uw Teams-kanaal wilt ontvangen. Dit is hoe het Microsoft Teams-notificatiemenu eruit kan zien:

![Choose which notificaitons you would like to receive Catenda Hub Email Microsoft Teams notifications Tropics Documents Approvals Collections Models Users A new topic is created aA topic is assigned to me A topic is mentioning me or my Teams New comment in a topic assigned to me mentioned by me followed by me Status changed in a topic Type changed in a topics I am set as the publisher in an approval request A team I am member of is set as the publisher in an approval request An approval request is closed A member of the submitter team A new approval request has been submitted A document has been discarded An approval request is closed A new approval request has been submitted A new approval request has been assigned to my team A new approval request is ready for review by my team All reviews have been submitted by my team aA document has been discarded An approval request is closed As member of the review team for the final approval A new approval requesthas been submitted A new approval request has been assigned to my team A new approval reqeust is ready for review by my team All reviews have been submitted by my team All reviews have been submitted by my team A review step has been completed A document has been discarded An approval request is closed A new models is created A new revision is imported.](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/09-step-4-customize-your-alerts.png)

Grijze notificatievakken zijn uitgeschakeld voor Microsoft Teams en zijn alleen beschikbaar voor andere notificatiemethoden. Notificatievakken voor goedkeuringen worden beschikbaar als Gedeelde revisies zijn ingeschakeld in [documentinstellingen](https://support.catenda.com/en/articles/7831371-document-settings-page) van een project.

---

### Stap 5: Verificatie

Controleer of een melding naar uw account wordt verzonden die ook naar Microsoft Teams wordt verzonden.

1\. Voer een actie uit in Catenda Hub.

> **Waarschuwing:** ⚠️ **Opmerking:** Niet elke melding kan naar Microsoft Teams worden verzonden en Microsoft Teams-meldingen worden over het algemeen niet verzonden voor acties die gebruikers zelf uitvoeren. Upload een model of vraag een teamgenoot om een onderwerp te maken of u in een beschrijving of opmerking te noemen om de koppeling te verifiëren.

2\. Controleer uw **Microsoft Teams-kanaal**. 3\. Een bericht zou onmiddellijk via de Microsoft Teams **Workflow**-bot moeten verschijnen.
