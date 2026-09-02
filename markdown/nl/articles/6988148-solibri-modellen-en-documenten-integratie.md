# Solibri-modellen en documenten-integratie

De Documenten API-integratie biedt een gemakkelijke manier om toegang te krijgen tot uw cloud-opgeslagen inhoud. U kunt verbinding maken met een common data environment (CDE) en modellen downloaden en uploaden van/naar de server.

## 1. **Verbinding maken**

De Documenten API is te vinden in het integratiemenu van het tabblad Bestand in Solibri. Als u aan de slag wilt gaan met de Documenten API, moet u Solibri eerst toegang geven tot uw Catenda-account. Klik hiervoor op Verbinding maken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/01-connecting.png)

De lijst met servers waarmee u verbinding kunt maken, wordt nu geladen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/02-connecting.png)

De eerste keer dat u Solibri start, kan het laden van deze lijst enige tijd duren. Na het eerste laden wordt de lijst opgeslagen en wordt het sneller geopend. In het vervolgkeuzemenu kunt u kiezen tussen Catenda of Bimsync om verbinding te maken met de Catenda Documenten API.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/03-connecting.png)

## 2. **Documenten of modellen importeren**

Klik op Openen om Documenten of modellen die u in Catenda Hub kunt openen, te importeren.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/04-importing-documents-or-models.png)

Na het klikken op Openen wordt uw standaardbrowser geopend.

- [Annuleer uw browsersessie](#h_e921d649ed) als u dit proces wilt annuleren en met Solibri wilt blijven werken
- Indien u dit nog niet hebt gedaan, [verleen toegang tot uw account](#h_55ca1d4d10).
- Selecteer een project op de [projectenpagina](#h_343870704c) als u nog geen project hebt geselecteerd.
- Na het selecteren van een project, of als u eerder al een project hebt geselecteerd, kunt u de [documentenpagina](#h_b7ac757915) (_standaard_) of de [modellepagina](#h_617a3f8bf6) selecteren.

## 3. **Solibri-sessie exporteren naar Catenda**

U moet [uw Catenda-account hebben verbonden](#h_457cbf4e9d) en ten minste één bestand in uw Solibri-sessie hebben om de knop Model uploaden beschikbaar te maken. Klik op Model uploaden om uw Solibri-sessie te exporteren als onderdeel van uw Catenda-project waartoe u toegang hebt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/05-exporting-solibri-session-to-catenda.png)

Als u uw Solibri-sessie nog niet hebt opgeslagen, of wijzigingen hebt aangebracht sinds de laatste opslag, wordt u gevraagd een .smc-bestand op te slaan zodat het kan worden geüpload.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/06-exporting-solibri-session-to-catenda.png)

Het .smc-bestand dat is opgeslagen, kan nu als nieuwe revisie naar Catenda worden geëxporteerd en later opnieuw naar Solibri worden geïmporteerd als u uw sessie met de nieuwste revisie wilt voortzetten. Nadat u uw .smc-bestand hebt opgeslagen, klikt u opnieuw op Model uploaden.

Na het klikken op Model uploaden wordt uw standaardbrowser geopend.

- [Annuleer uw browsersessie](#h_e921d649ed) als u dit proces wilt annuleren en met Solibri wilt blijven werken
- Indien u dit nog niet hebt gedaan, [verleen toegang tot uw account](#h_55ca1d4d10).
- Selecteer een project op de [projectenpagina](#h_343870704c) als u nog geen project hebt geselecteerd.
- Na het selecteren van een project, of als u eerder al een project hebt geselecteerd, wordt u weergegeven met de [documentenpagina](#h_b7ac757915).

## 4. **Solibri-documentintegratie -** Projectenpagina

Na het klikken op Openen en aanmelden, als u zojuist toegang hebt gegeven of eerder toegang hebt verleend, wordt een pagina die vergelijkbaar is met de projectenpagina van Catenda Hub geopend als een nieuwe pagina in uw standaardbrowser. De pagina van Solibri-documentintegratie ziet er ongeveer als volgt uit:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/07-solibri-document-integration-projects-page.png)

> **Opmerking:** Deze pagina is gemaakt door Solibri en is niet hetzelfde als de normale projectenpagina in Catenda Hub. Alleen de secties modellen en Documenten van Catenda kunnen worden genavigeerd. Catenda Hub-functionaliteit zoals documentvoorvertoning en toegangsconfiguratie werkt hier niet.

## 5. **Solibri-documentintegratie -** documentenpagina

Zie de Documenten die u via uw Catenda-account op de documentenpagina van Solibri-documentintegratie kunt openen. Hier kunt u configureren welke Documenten met Solibri worden gesynchroniseerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/08-solibri-document-integration-documents-page.png)

### 5.1 **Navigatie**

Klik op de naam van het project als u naar een ander project wilt navigeren. Klik op modellen in het linkermenu om in plaats van per Document per model te importeren.

> **Opmerking:** De modellepagina is alleen beschikbaar bij het downloaden.

### 5.2 **Documentstructuur**

Voor elk Document ziet u:

- Pictogram bestandstype
- Documentnaam
- Revisienummer
- Documentstatus
- Labels (klik op de 3 punten om meer labels te zien)
- Bestandsgrootte
- Meest recente revisiemaker
- Meest recente revisie-publicatiedatum
- 3D-knop (Modelvoorbeeld bekijken voordat u importeert)
- Objectkoppelingen (Selecteer gekoppelde objecten in 3D-voorbeeld door op dit nummer te klikken)

Selecteer een reeks Documenten door de vakjes in te schakelen of schakel het vakje bovenaan in om alles te selecteren.

### 5.3 **Menu Rechts informatie**

Nadat u hebt geselecteerd, wordt het informatief menu rechtsboven weergegeven. Klik op het pictogram `i` om het uit te vouwen als het gesloten is.

### 5.4 ​**Menu Rechts informatie -** Download

Bij het importeren kunt u configureren welke Documenten naar Solibri worden geïmporteerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/09-right-information-menu-download.png)

Klik op Download onderaan om de meest recente gedeelde revisie van elk geselecteerd Document te importeren.

### 5.5 **Menu Rechts informatie -** Upload

Bij het exporteren kunt u het .smc-bestand configureren dat wordt geüpload.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/10-right-information-menu-upload.png)

**Documentnaam bijwerken** Met deze optie ingeschakeld, wordt de naam van het geselecteerde Document bijgewerkt naar de naam die u aan uw bestand hebt gegeven.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/11-right-information-menu-upload.png)

Op deze manier kunt u ervoor zorgen dat u revisies naar een Document blijft uploaden terwijl u ervoor zorgt dat deze altijd dezelfde naam heeft als die revisies.

**Soortgelijke Documenten automatisch selecteren** Met deze optie ingeschakeld, kunt u uw bestand uploaden naar een Document met een soortgelijke naam, zelfs als deze niet exact hetzelfde is. Houd er rekening mee dat de geüploade revisie nog steeds de bestandsnaam bevat die u hebt opgegeven.

**Bestandsnaam** Hier ziet u de naam van het bestand dat naar Catenda wordt geüpload.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/12-right-information-menu-upload.png)

Standaard wordt de naam van het smc-bestand dat u op uw systeem hebt opgeslagen weergegeven. De naam kan op dit moment nog steeds worden gewijzigd. Configureer de naam van het bestand door op het potlood aan de rechterkant te klikken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/13-right-information-menu-upload.png)

**Document** Hier ziet u de naam van het Document op Catenda dat het bestand ontvangt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/14-right-information-menu-upload.png)

Standaard heeft het dezelfde naam als de bestandsnaam. Als er nog geen Document met die naam in uw huidige map bestaat, is dit veld groen, wat aangeeft dat een nieuw Document wordt gemaakt. De naam van uw Document kan op dit moment nog steeds worden gewijzigd. Als er andere .smc-Documenten in deze map zijn, kunt u op de Documentnaam klikken om een van de andere Documenten te selecteren waarnaar u uw .smc-bestand als revisie wilt uploaden. Als u een Document hebt gekozen of als er in de huidige map een Document met dezelfde naam voorkomt, is dit veld grijs. U ziet dan een bericht met de waarschuwing dat een Document met deze naam al bestaat en dat uw smc-bestand als nieuwe revisie naar dat Document wordt geüpload.

**Status** Als de statusworkflow voor uw project is ingeschakeld, ziet u de statusvervolgkeuzelijst.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/15-right-information-menu-upload.png)

Als u een nieuw Document maakt, of als uw Document nog geen status heeft, ziet u geen status. Als u een revisie aan een bestaand Document toevoegt, ziet u de status van dat Document en kunt u de Documentstatus bij uploaden wijzigen. Als u de status van het Document wilt wijzigen wanneer uw revisie wordt geüpload, kunt u deze selecteren uit de lijst met beschikbare statussen in het project.

### 5.6 **Ontvangen Documenten**

Wanneer de download succesvol is gestart, ziet u het volgende bericht in de browser

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/16-documents-received.png)

Als u teruggaat naar Solibri, ziet u dat de Documenten beginnen te worden verwerkt. Gedownloade Documenten worden opgeslagen in een tijdelijke map terwijl uw Solibri-sessie actief is. Vergeet niet uw Solibri-sessie op te slaan of een nieuwe revisie op Catenda te uploaden als u wijzigingen in uw bestand wilt opslaan. Geüploade Documentrevisies worden opgeslagen op Catenda. De meest recente revisie kan later opnieuw in Solibri worden geopend.

## 6. **Solibri-documentintegratie -** Modellepagina

Bekijk de modellen die u via uw Catenda-account op de modellepagina van Solibri-documentintegratie kunt openen. Hier kunt u configureren welke modellen met Solibri worden gesynchroniseerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/17-solibri-document-integration-models-page.png)

Klik op de naam van het project als u naar een ander project wilt navigeren. Voor elk model ziet u:

- Modelnaam
- Revisienummer
- IFC-type
- Meest recente revisie creatiedatum
- Meest recente revisiemaker

Selecteer een reeks modellen door de vakjes in te schakelen of schakel het vakje bovenaan in om alles te selecteren. Na het selecteren wordt het informatief menu rechtsboven weergegeven. Klik op het pictogram `i` om het uit te vouwen als het gesloten is. Hier kunt u uw selectie van modellen bewerken die naar Solibri moeten worden geïmporteerd. Klik op Download onderaan om de meest recente gedeelde revisie van elk geselecteerd model te importeren.

## 7. **Browsersessie annuleren**

Terwijl uw browsersessie actief is, ziet u het volgende bericht in Solibri.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/18-cancel-browser-session.png)

Klik op Annuleren als u het importproces wilt beëindigen.

## 8. **Toegang verlenen tot uw Catenda-account**

Als u nog niet bent aangemeld bij Catenda, wordt u gevraagd [aan te melden](https://support.catenda.com/en/articles/7891486-sign-in-page). Nadat u de eerste keer opent, nadat u zich aanmeldt of als u al bent aangemeld, wordt u gevraagd om toestemming voor toegang tot uw Catenda-account:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/19-granting-access-to-your-catenda-account.png)

Als u al bent aangemeld, maar niet met het juiste account, kunt u op uw profielfoto klikken om u af te melden en u aan te melden met het juiste account. Zorg ervoor dat u bent aangemeld met het juiste account en klik op Toegang toestaan om door te gaan. Wacht niet te lang om dit te doen, anders werkt het niet. Zorg ervoor dat u uw wachtwoord klaar hebt! Nadat u toegang tot uw account hebt verleend, ziet u het volgende bericht:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/20-granting-access-to-your-catenda-account.png)

## 9. **Gekoppelde Documenten beheren**

Documenten die van Catenda in Solibri zijn gekoppeld, kunnen er anders uitzien dan gewone Documenten die vanuit het lokale systeem zijn geopend. Dit is hoe Documenten eruitzien wanneer ze met Documenten op Catenda zijn gekoppeld:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/21-managing-linked-documents.png)

### 9.1 **Naamkolom**

De naam van het model kan enige tijd duren om bij te werken, maar verandert uiteindelijk in overeenstemming met het aantal revisies in het Document op Catenda. Als uw organisatie een voorkeur voor de downloadnaam van uw Document heeft ingesteld, vindt u hier mogelijk een andere naam. U kunt bijvoorbeeld de Documentnaam zonder de optie revisie aanvragen. Houd er rekening mee dat dit door de organisatie voor alle gedownloade bestanden in hun projecten moet worden aangevraagd. U kunt de verschillende downloadnaamopties voor organisaties [hier](https://support.catenda.com/en/articles/8224886-organization-options) zien.

### 9.2 **Versiekolom**

De versiekolom helpt u bij te houden welke revisie momenteel is geladen. Als revisiePublicatie is geactiveerd op uw Catenda-project, ziet u hier mogelijk major (1.0, 2.0, 3.0, enzovoort) en minor (1.1, 1.2, 2.1, enzovoort) revisienummers.

### 9.3 **Koppelingskolom**

Nadat een model uit Catenda Hub is geïmporteerd, wordt een kettinglinks pictogram in de derde kolom weergegeven om aan te geven dat het is gekoppeld.

### 9.4 **Model-hover**

Als u de muisaanwijzer over een Document plaatst dat van Catenda is gekoppeld, ziet u `[Documenten API] Catenda` gevolgd door de naam van het Document.

### 9.5 **Contextmenu -** Updates

Klik met de rechtermuisknop op een Document om het contextmenu te openen. Hier kunnen de updatevoorkeuren voor Documenten worden geconfigureerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/22-context-menu-updates.png)

**Modellen bijwerken** Dit is hoe de dialoog Modellen bijwerken eruitziet als u meerdere Documenten hebt geselecteerd.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/23-context-menu-updates.png)

Map - Klik op de map als u in plaats daarvan een lokaal bestand voor dit model wilt kiezen.

Versie - Hier ziet u het versienummer in Catenda samen met een vinkje dat aangeeft of u momenteel met de nieuwste revisie werkt of niet. Update - Schakel het updatevakje in voor elk model of voor alle modellen door het vakje bovenaan in te schakelen en klik op Modellen bijwerken om deze bij te werken.

Instellingen - Klik op Instellingen om de modelupdateinstellingen voor uw geselecteerde Documenten te openen.

Modellen opnieuw koppelen - Modellen opnieuw koppelen werkt alleen als u in deze dialoog lokale modellen hebt geselecteerd en niet met Catenda-modellen.

**Modelupdateinstellingen**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/24-context-menu-updates.png)

Automatisch - Wanneer een nieuwe revisie beschikbaar is in Catenda Hub, wordt het model automatisch bijgewerkt.

Prompt - Een melding wordt weergegeven wanneer een nieuwe revisie beschikbaar is op Catenda. Het bijwerken naar de nieuwe revisie begint op uw gemak.

Modellen opnieuw koppelen - Modellen opnieuw koppelen werkt alleen als u in deze dialoog lokale modellen hebt geselecteerd en niet met Catenda-modellen.

### 9.6 **Contextmenu -** Hyperlinks

Aan de onderkant van het contextmenu van het Document ziet u hyperlinks.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/25-context-menu-hyperlinks.png)

Voor elk geselecteerd Document dat een koppeling naar Catenda heeft, ziet u "Catenda" wanneer u elk hyperlink-menu opent. Dit is hoe het uitgevouwen hyperlink-menu eruit kan zien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/26-context-menu-hyperlinks.png)

Nieuwe hyperlink - Als u op Nieuwe hyperlink klikt, wordt het menu Hyperlink toevoegen geopend, dat er ongeveer als volgt kan uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/27-context-menu-hyperlinks.png)

Weergeven Klik op "Catenda" om dat gekoppelde Document op Catenda te openen.

Bewerken Klik op "Catenda" om de koppeling voor dat geselecteerde Document te bewerken. Het menu Hyperlink bewerken wordt nu geopend en kan er ongeveer als volgt uitzien:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/vjtcq1e9/28-context-menu-hyperlinks.png)

Het adres moet er ongeveer als volgt uitzien: [https://hub.catenda.com/project/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx/revisions/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx](https://hub.catenda.com/project/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx/revisions/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)

Het onderwerp is standaard Catenda, maar kan naar alles wat u wilt worden hernoemd.

Catenda-koppelingen zijn altijd absoluut, wat betekent dat ze niet relatief zijn ten opzichte van waar uw .smc-bestand op uw systeem staat.

Verwijderen Klik op "Catenda" om de koppeling voor dat geselecteerde Document te verwijderen.
