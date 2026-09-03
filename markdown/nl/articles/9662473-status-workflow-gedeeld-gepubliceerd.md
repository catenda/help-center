# Status Workflow Gedeeld -> Gepubliceerd

## 1. **Beschikbaarheid op projecten**

De nieuwe status workflow is een functie op aanvraag die kan worden ingeschakeld voor lopende projecten. Nieuwe projecten die zijn gebaseerd op een sjabloonproject waar de nieuwe status workflow is ingeschakeld, hebben ook de nieuwe status workflow ingeschakeld.

**'Concepten' worden stopgezet en zijn niet langer beschikbaar.**

## 2. **Status workflow met 'gedeelde' revisies inschakelen**

De oude status workflow (verouderd) met 'concepten' wordt vervangen door de nieuwe Status Workflow (met gedeelde statussen) voor lopende projecten die de verouderde status workflow niet gebruiken. Gedeelde statussen kunnen worden geactiveerd in het menu Status workflow van de pagina Documentinstellingen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/h48tax1e/01-enabling-status-workflow-with-shared-revisions.png)

De upgrade van status workflow met 'concepten' naar status workflow met 'gedeelde' documenten heeft deze effecten;

## 3. **Catenda Hub**

**Gedeelde status** Uploads beginnen allemaal met een gedeelde status, zodra gedeelde statussen in het project beschikbaar zijn. Na het uploaden kunnen gedeelde documenten worden gepubliceerd.

**Conceptdocumenten** Concepten worden stopgezet, daarom kunnen nieuwe concepten niet meer worden geüpload. Bestaande concepten kunnen nog steeds in oude projecten worden gebruikt (met beperkingen)

🖥️  _Werkruimte en_ ✔️ _Gepubliceerde tabbladen_ Afzonderlijke tabbladen (werkruimte en gepubliceerd) zijn beschikbaar in het documentgebied, waarbij het gepubliceerde tabblad alleen gepubliceerde revisies bevat.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/h48tax1e/02-catenda-hub.png)

Een nieuwe revisienummering verschijnt (major.minor). #0.1, #0.2 enzovoort voor **gedeelde revisies** en #1, #2, #3 enzovoort voor **gepubliceerde revisies**.

### 3.1 _Toegangsbeheer_

Toegangsrechten kunnen worden ingesteld voor het publiceren van gedeelde revisies. Dit stelt gebruikers in staat om gedeelde revisies te publiceren en gepubliceerde statussen te wijzigen. Toegangsbeheer wordt weergegeven op map-/documentniveau om gebruikers het recht te geven documentsities met schrijftoegang te publiceren. Toegangsrechten voor het weergeven van gedeelde revisies zijn beschikbaar. Hier kunt u gebruikers met 'leestoegang' verbieden gedeelde revisies te zien.

**Goedkeuringen** Alleen gedeelde revisies kunnen aan een goedkeuringsaanvraag worden toegevoegd

**Verzamelingen** Verzamelingen kunnen alleen voor gepubliceerde revisies worden gebruikt

**Documentmodellen** Het modelgebied geeft de tabbladen (werkruimte en gepubliceerd) weer, net als in het documentgebied. Toegangsrechten worden van documenten overgenomen.

> **Opmerking:** Informeer uw projectleden over deze wijzigingen wanneer u deze functie inschakelt op bestaande projecten.

## 4. **API-clients**

**Nieuwste revisie** Nieuwste revisie van document (kan gedeeld of gepubliceerd zijn) wordt opgehaald, tenzij anders in de API-aanroep is opgegeven

**Standaardinstellingen voor uploads** Uploads via de API worden standaard ingesteld op een gedeelde revisie, zodra gedeelde statussen in het project beschikbaar zijn.

**Wijzigingen revisienummer** Revisienummers zijn inconsistent met de revisienummers (major.minor) op Catenda Hub. U moet uw app bijwerken.

> **Opmerking:** Informeer uw projectleden over deze wijzigingen wanneer u deze functie inschakelt op bestaande projecten.

Klik [hier](https://support.catenda.com/en/articles/12289689-status-workflow-api-updates) om meer te lezen over API-wijzigingen
