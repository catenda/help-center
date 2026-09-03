# Innstillinger for varsler

Siden for innstillinger for varsler finner du som en underside til [siden for varsler](https://hub.catenda.com/notifications). I [innstillinger for varsler](https://bimsync.com/notifications/settings) kan du konfigurere hvilke varsler du mottar.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/01-intro.png)

Hver fane svarer til en annen metode for å sende varsler.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/02-intro.png)

Fanen du er på for øyeblikket vil være understreket med en grønn linje.

## 1. **Várslerbryter**

For hver varslingsmetode kan du slå varsler helt på eller av. Som standard vil Catenda Hub og e-postvarsler være på, mens Slack- og Teams-varsler vil være av. For å aktivere eller deaktivere varsler helt for en fane, trykk på denne bryteren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/03-notification-switch.png)

Når en varslingsmetode er blitt deaktivert, blir sirkelen ved siden av fanen grå.

> **Merk:** Hvis du deaktiverer e-postvarsler, kan du fortsatt motta e-poster for prosjektinvitasjoner og dele lenke-e-poster.

Klikk på bryteren igjen for å slå varslene på igjen.

## 2. **Varsler-avmerkingsbokser**

For hver varslingsmetode kan du velge hvilke varslingstyper du vil motta for den metoden. Klikk [her](https://support.catenda.com/en/articles/8304417-untitled-article) for å se når hver type varsel sendes.

## 3. **Varsler i nettleseren**

Catenda Hub-fanen lar deg konfigurere hvilke varsler du mottar i nettleseren. Dette er varslene du ser på [siden for varsler](https://hub.catenda.com/notifications). Når du mottar et varsel, vil du se et rødt tall med ulesete varsler på varselikonet øverst til høyre. Når du klikker på denne knappen, forsvinner merket for ulesete varsler.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/04-in-browser-notifications.png)

## 4. **E-postvarsler**

E-postfanen lar deg konfigurere hvilke varsler du mottar via e-post. Som standard får du én e-post per varsel på Catenda Hub. Hvis du endrer e-postvarsler dine, vil du fortsatt få alle varslene på Catenda Hub som du konfigurerte [ovenfor](#h_e4a9ba5c0c)

### 4.1 **E-postsammendrag**

Med e-postvarsler kan du velge å få et daglig sammendrag i stedet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/05-br-email-summary.png)

Hver gang et sammendrag sendes, vil det inneholde alle varsler som har skjedd siden det forrige sammendraget.

## 5. **Slack-varsler**

Slack-fanen lar deg motta varslene som er sendt til kontoen din i en Slack-kanal. Denne varslingsmetoden er av som standard og må konfigureres og slås på hvis du vil bruke den. Du kan finne innstillingen for webhook-URL nederst på siden med faner.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/06-slack-notifications.png)

Ved å sette opp 'Slack webhook URL' vil du få varsler fra Catenda Hub sendt til Slack. For å sette opp går du til ([https://api.slack.com/incoming-webhooks](https://api.slack.com/incoming-webhooks)) og klikker deretter på lenken `incoming webhook integration`. Velg så hvilken kanal du ønsker at meldingene skal gå til og kopier feltet `webhook URL` inn i Catenda.

## 6. **Microsoft Teams-varsler**

Microsoft Teams-fanen lar deg motta varslene som er sendt til kontoen din i en Microsoft Teams-kanal. Denne varslingsmetoden er av som standard og må konfigureres og slås på hvis du vil bruke den. Du kan finne innstillingen for webhook-URL nederst på siden med faner.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/a9v4sbgg/07-microsoft-teams-notifications.png)

I Teams-kanalen velger du **"Koblinger"** fra hovedmenyen. Søk etter **"Innkommende Webhook"** og velg **"Konfigurer"**. Sett navn til Catenda, bruk **"[https://hub.catenda.com/img/logo-192x192.png](https://hub.catenda.com/img/logo-192x192.png)"** som bilde og trykk deretter **"Opprett"**.

Kopier URL-en til **"Webhook URL"** ovenfor. Kontroller at varslene er aktivert øverst, og merk deretter av for varseltyper du vil ha sendt til Teams-kanalen

## 7. **Varsler per prosjekt**

Hvis du har angitt varsler som er spesifikke for prosjekter, kan du se disse i navigasjonsmenyen til venstre i et prosjekt. Du kan klikke på navnet på prosjektet for å gå til [innstillinger for prosjektvarsler](https://support.catenda.com/en/articles/4670262-project-notification-settings) for det prosjektet. Disse innstillingene gjelder spesielt for deg og er ikke innstillinger for hele prosjektet.
