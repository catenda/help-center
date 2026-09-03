# Problemen met Microsoft Teams-meldingen oplossen

In dit artikel vindt u informatie over de fouten die kunnen optreden bij het configureren van Microsoft Teams-meldingen met Catenda via Microsoft Teams Workflows.

Dit artikel bevat informatie over de volgende onderwerpen: [Geen meldingen](#h_42fb432d1c)

## 1. **Geen meldingen in Microsoft Teams-kanaal**

Als een Microsoft Teams Workflow-URL in Catenda is geconfigureerd en een Catenda-melding voor een van de meldingsvakken die zijn ingeschakeld in het tabblad Microsoft Teams van de meldingsinstellingen is ontvangen, maar er is geen bericht in het Microsoft Teams-kanaal dat daar is geconfigureerd, is er waarschijnlijk een probleem met de Microsoft Teams Workflow.

Als u wilt zien of er iets mis is gegaan met de Microsoft Teams Workflow, selecteert u Workflows door over het kanaal te bewegen en op de drie puntjes te klikken of door op de drie puntjes in de rechterbovenhoek van een kanaal te klikken.

<img alt="Microsoft Teams-kanaalactiemenu, Workflows gemarkeerd." src="https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/inline-f533eea19d48.png" width="290"/>  \<---> <img alt="Actiemenu in Microsoft Teams-kanaal, Workflows gemarkeerd." src="https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/inline-1a6a43fe9eec.png" width="290"/>

Als er iets mis is met de workflow, kan een fout worden weergegeven in de workflow "Webhookwaarschuwingen naar een kanaal verzenden" in het menu "Uw workflows".

![Microsoft Teams Er is een verbindingsprobleem opgetreden dat uw aandacht nodig heeft](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/01-no-notifications-in-microsoft-teams-channel.png)

Een fout kan zijn: `Er is een verbindingsprobleem opgetreden dat uw aandacht nodig heeft`

Klik op de workflow om de workflow in de voorkeursbrowser te openen of klik op Details om meer informatie in Microsoft Teams weer te geven. Dit is hoe de details van de Webhook-workflow er in Microsoft Teams kunnen uitzien als er een fout optreedt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/02-no-notifications-in-microsoft-teams-channel.png)

Hier kunt u zien op welk moment en op welke datum de fout is opgetreden. Klik op het moment en de datum van de fout om de workflow in Power Automate in de voorkeursbrowser te openen. Dit is hoe de fout er in Power Automate kan uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/03-no-notifications-in-microsoft-teams-channel.png)

De waarschuwing in Power Automate geeft ons meer aanwijzingen over wat er mis kan zijn. In dit geval is het volgende foutbericht verschenen:

`Waarschuwing: Uw <email>-verbinding werkt niet: Het lijkt erop dat uw stroom's <email>-verbinding opnieuw moet worden aangemeld. De meest voorkomende oorzaak is een gewijzigd wachtwoord of een beleid dat door uw tenantbeheerder is ingesteld. Verbindingen moeten mogelijk opnieuw worden geverifieerd als verificatie met meerdere factoren onlangs voor uw account is ingeschakeld.`

Als u opnieuw wilt verifiëren, klikt u op de workflow in Teams en opent u de workflow in Power Automate. Het is ook mogelijk om naar de verbindingspagina in Power Automate te gaan en daar een verbinding tot stand te brengen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/04-no-notifications-in-microsoft-teams-channel.png)

Klik in het dialoogvenster Actie vereist op Opnieuw verifiëren. Nadat u zich hebt aangemeld, zou de verbinding op de pagina Verbindingen moeten verschijnen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/ycbjp9sn/05-no-notifications-in-microsoft-teams-channel.png)
