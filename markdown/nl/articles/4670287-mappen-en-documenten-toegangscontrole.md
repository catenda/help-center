# Mappen en Documenten toegangscontrole

> Toegangsniveaus voor documenten

Selecteer document(en) en/of map(pen) in het documentengebied om het menu voor toegangscontrole te vinden in het [rechterinformatiemenu](https://support.catenda.com/en/articles/8345396-right-menu-on-the-documents-page#h_cad792004b). Hier kunt u zien welke projectleden toegang tot het document hebben. Volg deze stappen om de toegang tot de geselecteerde items te bewerken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/01-intro.png)

1. Selecteer de document(en) en/of map(pen) die moeten worden geconfigureerd.
1. Open het rechterinformatiemenu
1. Klik op **toegang bewerken**.

> **Belangrijk:** **Vereiste toegang:** Volledige toegang

De dialoog voor toegangscontrole kan er ongeveer zo uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/02-intro.png)

## 1. **1. Toegang configureren voor projectdeelnemers**

Klik op de vervolgkeuzelijst "Toegang definiëren voor" om deelnemers te selecteren voor wie de toegang moet worden geconfigureerd. Deelnemers kunnen worden geselecteerd als lid of als lid van een team. De toegangsrollen omvatten beheerder, individuele gebruikerstoegang, basistoegang, teamtoegang en eigenaartoegang.

### 1.1 **1.1 Aanbevolen workflow**

Stel de toegang **per team in plaats van per gebruiker** in. Rollen veranderen vaak, en teamgebaseerde toegang blijft flexibel: wanneer een lid aan een team wordt toegevoegd, krijgen ze de juiste toegang zodra ze het project binnenkomen. Een gebruikelijk patroon is om "alle gebruikers" op geen toegang in te stellen — zodat nieuwe, nog niet toegewezen leden geen gevoelige informatie kunnen zien — en vervolgens indien nodig toegang aan elk team verlenen.

Klik [hier](https://support.catenda.com/en/articles/15644094-how-catenda-calculates-access-levels) om meer te lezen over hoe de verschillende deelnemersrollen zich tegenover elkaar verhouden.

## 2. **2. Welke toegang wordt toegepast? (3 stappen)**

De toegang met het hoogste gewicht wint altijd, maar er zijn uitzonderingen. Beperkende niveaus zoals "Geen toegang" worden verheven boven andere paden die hogere rechten toekennen.

### 2.1 **2.1 Welke configuratie is van toepassing?**

**Beheerders** Beheerders hebben altijd toegang tot alles.

**Individuen** Het exact geconfigureerde toegangsniveau is van toepassing.

**Anderen** Controleer de verschillende toegang die voor een gebruiker is geconfigureerd via een van de volgende:

- Alle gebruikers
- Een team waarvan de gebruiker deel uitmaakt (kan deel uitmaken van meerdere)
- Eigenaartoegang.

De toegang met het hoogste gewicht is van toepassing. Geen toegang > Volledige toegang > Schrijven > Lezen

Klik [hier](https://support.catenda.com/en/articles/15644094-how-catenda-calculates-access-levels) om meer te lezen over hoe toegangsniveaus worden berekend. Klik [hier](https://support.catenda.com/en/articles/15644249-access-control-deployment-use-cases) om meer te lezen over typische manieren waarop toegang is geconfigureerd.

### 2.2 **2.2 Wat kunnen deelnemers doen met die toegang?**

Klik [hier](https://support.catenda.com/en/articles/15647394-operations-on-document-library-items) om meer te lezen over welke bewerkingen op mappen en documenten kunnen worden uitgevoerd.

## 3. **3. Overschrijvingsopties (bereik toegepast bij opslaan)**

Wanneer de dialoog voor toegangscontrole wordt opgeslagen, wordt de toegang tot de geselecteerde elementen **overschreven ongeacht wat eerder was geconfigureerd**. De drie opties onder "Waar deze regels toepassen" bepalen hoe ver die wijziging reikt.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Optie</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Wat wordt overschreven</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Welke toegang blijft hetzelfde</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Wanneer te gebruiken</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Map en nieuwe inhoud</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Geselecteerde items + alle nieuwe items die daarin worden gemaakt</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Items één niveau lager + items in mapstructuren.</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Wanneer u de toegang tot bestaande inhoud niet mag wijzigen</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Map en bestanden<br/>(standaard)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Bovenstaande + bestaande documenten één niveau lager</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Mappen één niveau lager + items in mapstructuren.</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>De gebruikelijke keuze; toegang per submap blijft behouden</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Map en alle submappen en bestanden</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Bovenstaande + mappen één niveau lager + items in mapstructuren.</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Alleen wanneer het oké is om ook bestaande submaptoegang te overschrijven</p></td></tr></tbody></table></div>

> **Opmerking:** **Voorzichtig:** de eerste twee opties overschrijven alleen de geselecteerde elementen, dus oude toegang kan op sub-elementen blijven bestaan. Leden kunnen er mogelijk niet meer naar navigeren, maar kunnen er nog steeds via filtering bij komen.

## 4. **4. Statuswerkstroom**

Als gedeelde statussen na 2 oktober 2025 zijn ingeschakeld, verschijnen twee extra kolommen rechts van de toegangskolom: **Gedeelde revisies weergeven** en **Kan publiceren**. Welke vakjes kunnen worden ingeschakeld, hangt af van het toegangsniveau. Dit is wat dat eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/03-4-status-workflow.png)

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Toegang</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Gedeelde revisies weergeven</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Publiceren</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Geen toegang</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Niet beschikbaar (item niet in lijst weergegeven)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Nee</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lezen</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Kan worden verleend (optioneel)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Nee</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Schrijven</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Altijd in staat om te bekijken</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Kan worden verleend (optioneel)</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Volledige toegang</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Altijd in staat om te bekijken</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ja</p></td></tr></tbody></table></div>
