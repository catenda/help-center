# Meervoudige Factorverificatie

> Beschrijft hoe u MFA op uw account instelt

U vindt de **Multi Factor Authentication** (MFA)-instellingen op de [authenticatiepagina](https://support.catenda.com/en/articles/6880968-account-page#h_e04d63351f), een subpagina van de [accountpagina](https://support.catenda.com/en/articles/6880968-account-page).

**Multi Factor Authentication** (MFA) vereist dat u bij het aanmelden bij Catenda Hub een code invoert die u via uw mobiele apparaat ontvangt, samen met uw gebruikersnaam en wachtwoord. Wanneer een organisatie MFA vereist, wordt dit op organisatieniveau toegepast. Alle projecten die tot die organisatie behoren, vereisen dan MFA om toegang tot hun projecten te krijgen. Dit zal alle gebruikers dwingen MFA in te schakelen om toegang te krijgen tot projecten die tot die organisatie behoren.

## 1. **MFA inschakelen**

Log in op Catenda Hub en ga naar de **[Account](https://hub.catenda.com/account/profile)**pagina:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/01-enabling-mfa.png)

1. Klik op het **[Verificatie](https://hub.catenda.com/account/authentication)**tabblad:
1. Scrol omlaag naar het gedeelte voor MFA:
1. Klik op **MFA inschakelen**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/02-enabling-mfa.png)

### 1.1 **Verificatie-app**

Installeer een toepassing op een mobiel apparaat die het TOTP-protocol (Time-based one-time password) ondersteunt. Installeer een betrouwbare verificatie-app op een mobiel apparaat om aan de slag te gaan. De hoeveelheid tijd die een verificatietoepassing al bestaat en de jurisdictie waar het bedrijf dat eigenaar is gebaseerd is, zijn vaak nuttige aanwijzingen. Hier zijn enkele voorbeelden van aanbevolen verificatietoepassingen:

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 139px; padding: 8px;"><h3 id="h_b56161ee38"><b>Beveiligingswetten voor verificatie-apps</b></h3></td><td style="background-color: #e3e7fa80; width: 101px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_49bc31efe9">Bedrijf</h3></td><td style="background-color: #e3e7fa80; width: 119px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_46b679c81c">Jurisdictie</h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_7699fa4ab6">Toepasselijke beveiligingswetten</h3></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_ae65255403">Aegis</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Beem</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Nederland<br/>(Dordrecht)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>GDPR<br/>9-ogenakkoord</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_42b556ff02">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Roland Moers</p></td><td style="background-color: #e8e8e880; width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Duitsland</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>GDPR<br/>Bundesdatenschutzgesetz - BDSG <br/>14-ogenakkoord</p></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_5e0c03d260">Authenticator</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Google</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Verenigde Staten<br/>(Californië)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_918c12706e">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Microsoft</p></td><td style="background-color: #e8e8e880; width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Verenigde Staten<br/>(Washington)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_b3a055f26d">Ente Auth</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ente</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Verenigde Staten (Delaware)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_63d03979d2">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Internet Initiative Japan</p></td><td style="background-color: #e8e8e880; width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Japan</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Act on the Protection of Personal Information (APPI)</p></td></tr><tr><td style="width: 139px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_848afb2dfa">HENNGE Lock</h3></td><td style="width: 101px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>HENNGE K.K.</p></td><td style="width: 119px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Japan</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Act on the Protection of Personal Information (APPI)</p></td></tr></tbody></table></div>

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 138px; padding: 8px;"><h3 id="h_5e28bb0eb3"><b>Functionaliteit van verificatie-app</b></h3></td><td style="background-color: #e3e7fa80; width: 88px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_6ed7d3e230">Releasedatum</h3></td><td style="background-color: #e3e7fa80; width: 180px; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_f652151c66">Besturingssysteem</h3></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_824368384e">Code-extractie</h3></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_218c61c8b2">Aegis</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2019</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Android</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Exporteren naar volledig platte tekst- of versleuteld bestand. JSON / TXT / QR</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_0274ada2cb">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2020</p></td><td style="background-color: #e8e8e880; width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Exporteren naar eigen bestandsformaat / Geheim weergeven</p></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_cc8ae8a27d">Authenticator</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2010</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS<br/>Android</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Overbrengen naar andere Google Authenticator-app met Google-account</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_6d595cbd69">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS<br/>Android</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Overbrengen naar andere Microsoft Authenticator-app met Microsoft-account.</p></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_9cbe3f20d2">Ente Auth</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2020</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS<br/>Android</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>JSON / TXT</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_425ee9cdba">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS - 8.1+<br/>Android - 4.0+</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>QR-code-export per code.</p></td></tr><tr><td style="width: 138px; border-top: 1px solid #c6c9c0; padding: 8px;"><h3 id="h_10c8930b4e">HENNGE Lock</h3></td><td style="width: 88px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>2020</p></td><td style="width: 180px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>iOS - Nieuwste 2 hoofdversies <br/>Android - nieuwste 4 benoemde versies</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Geen</p></td></tr></tbody></table></div>

Theoretisch gezien kan elke toepassing die MFA / tweefactorauthenticatie via het TOTP-protocol ondersteunt, worden gebruikt. Er zijn zelfs bureautoepassen, maar deze worden niet aanbevolen omdat bureautoepassen vaak altijd met hetzelfde netwerk zijn verbonden, dat vaak meerdere apparaten heeft, wat het risico vergroot dat een kwaadwillende persoon toegang tot de code krijgt.

**App-machtigingen** Om de QR-code met de camera van het apparaat te kunnen scannen, moet de verificatie-app camerapermissies hebben. De toepassing kan u vragen om toestemming te geven voor het gebruik van de camera van het apparaat. Machtigingsopties kunnen onder andere zijn: "Alleen tijdens gebruik van de app" - De app heeft toestemming tijdens gebruik. "Elke keer vragen" - Toestemming moet bij elk gebruik van de app worden verleend. "Niet toestaan" - Toestemming is niet gegeven of ingetrokken van de app.

**Google Authenticator** Klik op het plusteken rechtsonder en scan een QR-code. Hier scant u de QR-code die de [verificatiepagina](https://hub.catenda.com/account/authentication) u geeft. U kunt ook uw camera gebruiken om de code te scannen en de installatiekey typen die u in de geopende URL ziet.

**Microsoft Authenticator** Zorg ervoor dat u zich in het Authenticator-menu onderaan bevindt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/03-authentication-app.png)

> **Opmerking:** zorg ervoor dat u niet in het menu Geverifieerde ID's bent, omdat u hier een qr-code kunt scannen, maar dit werkt niet.

Klik vervolgens op het plusteken in de blauwe balk rechtsboven. Selecteer Ander account (Google, Facebook, enz.). Als uw app geen toestemming voor uw camera heeft, wordt u mogelijk wel of niet gevraagd om toestemming voor uw camera te geven.

Als uw app toegang tot uw camera heeft, kunt u de QR-code die de [verificatiepagina](https://hub.catenda.com/account/authentication) u geeft, scannen.

Als uw app geen toegang tot uw camera heeft, wordt u gevraagd handmatig een account aan te maken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/04-authentication-app.png)

Accountnaam: De naam die u aan uw account geeft Geheime sleutel: Dit is de sleutel die u zou hebben gekregen als u de qr-code had kunnen scannen. U kunt uw camera-app gebruiken om de code te scannen. De URL die wordt geopend wanneer u de code scant, kan er als volgt uitzien: `otpauth://totp/<Catenda account email address>?secret=<Secret key>&issuer=Catenda&algorithm=SHA1&digits=6&period=30` Als u na "`secret=`" de code invoert in de geheime sleutel die u in de geopende URL ziet, kan de accountnaam van alles zijn.

> **Opmerking:** Als u een account aanmaakt met een onjuiste geheime sleutel, genereert de app toch eenmalige codes, dus Catenda accepteert de code mogelijk niet als de onjuiste geheime sleutel is gebruikt.

### 1.2 **Succes of falen**

**Succes** Nadat u MFA hebt ingeschakeld, ziet u dit bericht.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/05-success-or-fail.png)

Zodra deze is ingeschakeld, moet u uw mobiele apparaat bij de hand hebben elke keer dat u zich aanmeldt bij Catenda Hub. De MFA kan opnieuw worden uitgeschakeld door op MFA uitschakelen te klikken.

**Onjuiste code** Als u de juiste code niet hebt ingevoerd, krijgt u het bericht onjuiste code.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/06-success-or-fail.png)

> **Opmerking:** Als u de QR-code hebt gescand, kunt u de code proberen in te voeren binnen het gegeven tijdsbestek voor die code terwijl u dit menu open hebt. Als u dit menu sluit, moet u de code die in uw verificatie-app wordt gegenereerd verwijderen en de QR-code opnieuw scannen om een nieuwe codeverbinding in te stellen.

## 2. **MFA wijzigen**

Nadat u een MFA-code hebt verbonden, kunt u de accountnaam van de code veilig bewerken. U kunt dit op de volgende manieren doen:

**Google Authenticator**

1. Houd de code ingedrukt
1. Klik op het potlood rechtsboven om de naam te wijzigen.

**Microsoft Authenticator**

1. Klik op de code.
1. Klik op de tandwielknop rechtsboven
1. Klik op het potlood om de naam te wijzigen

## 3. **MFA overbrengen**

**Deactiveren en opnieuw activeren** Het is slechts mogelijk om één MFA-app-codeverbinding tegelijk te gebruiken. Als u wilt overschakelen naar een ander codepairing, misschien omdat uw huidige is gecompromitteerd, voert u deze stappen uit: U moet deze methode ook gebruiken als u de app die u voor MFA gebruikt, wilt wijzigen.

1. Schakel uw MFA uit op de [verificatiepagina](https://hub.catenda.com/account/authentication)
1. Bereid de app voor die u wilt gebruiken om uw MFA opnieuw te verbinden
1. Genereer een nieuw codepairing door de QR-code te scannen zoals in de [inschakelsectie](#h_9e13fd06f5)

> **Opmerking:** Wees voorzichtig met deze methode, want uw account is tijdelijk kwetsbaar terwijl het is uitgeschakeld en u kunt gedurende deze tijd geen toegang krijgen tot projecten waarvoor MFA vereist is.

**Overbrengen via back-up** Als u een nieuw apparaat wilt gaan gebruiken zonder dat uw code tijdelijk wordt uitgeschakeld, kunt u een andere installatie van dezelfde MFA-app gebruiken en de code van de oude installatie naar de nieuwe installatie overbrengen.

**Google authenticator** Oud apparaat:

1. Tik op het hamburgermenu rechtsboven
1. Tik op Accounts exporteren
1. Selecteer de accounts die u wilt exporteren

Nieuw apparaat:

1. Tik op het hamburgermenu rechtsboven
1. Tik op accounts importeren
1. Tik op QR-code scannen
1. Scan de QR-code die op het oude apparaat wordt weergegeven toen u het exportproces hebt doorlopen.

**Microsoft authenticator** Oud apparaat:

1. Tik op het hamburgermenu rechtsboven
1. Zet back-up aan

Nieuw apparaat:

1. Installeer en open de Microsoft Authenticator-app op uw nieuwe apparaat
1. Tik op "Herstel starten."

> **Opmerking 1:** Stel geen accounts in met Microsoft Authenticator totdat u het Recovery-hulpprogramma hebt gebruikt, omdat dit overeenkomende siteaccounts overschrijft.

> **Opmerking 2:** Deze methode vereist dat u uw MFA-codes een back-up maakt, wat betekent dat deze worden opgeslagen in de cloudservice van uw app-provider. Gebruik deze methode alleen als u de back-upservice van uw app-provider vertrouwt. Zo niet, dan kunt u beter deactiveren en opnieuw activeren.

## 4. **MFA uitschakelen**

U kunt MFA uitschakelen door op de bovenstaande uitschakelknop te klikken en vervolgens uw wachtwoord in te voeren ter bevestiging. Na het uitschakelen kunt u geen projecten waarvoor MFA vereist is meer openen.

Na het uitschakelen van de code op Catenda Hub, blijft de code in de toepassing waarmee u verbinding hebt gemaakt, staan. Deze code is nu nutteloos en kan veilig worden verwijderd.

### 4.1 **De oude code verwijderen:**

**Google Authenticator**

1. Houd de code ingedrukt
1. Klik op de vuilnisbak rechtsboven.

**Microsoft Authenticator**

1. Klik op de code.
1. Klik op de tandwielknop rechtsboven
1. Klik op account verwijderen

## 5. **MFA op niet-mobiele apparaten**

Verificatie-apps zijn veiliger dan SMS/E-mail-codeoplossingen omdat er na de oorspronkelijke configuratie geen communicatie kan worden onderschept tussen de twee systemen. Hoewel het beter is om een app op een mobiele toepassing te gebruiken, zie opmerking hieronder, het is mogelijk om MFA-codes op andere systemen dan alleen mobiele apparaten te krijgen. De aanbevolen bureautoepassing hiervoor is [Authy](https://authy.com/). Dit soort toepassingen gebruiken functioneel hetzelfde TOTP-protocol als de app op uw mobiele apparaat en moeten net zo veilig zijn.

> **Waarschuwing:** Bureautoepassen kunnen minder veilig zijn omdat ze gemakkelijker kunnen worden gehackt of waarop toegang kan worden verkregen. Dit is omdat bureaustelsels vaak, zo niet altijd, met het lokale netwerk zijn verbonden, wat mogelijk is besmet. Mobiele apparaten die niet altijd met het netwerk zijn verbonden, kunnen daarom moeilijker toegang te krijgen.

## 6. **Wie kan MFA op projecten handhaven?**

Enterprise-klanten kunnen verzoeken om een [organisatieoptie](https://support.catenda.com/en/articles/8224886-organization-options#h_d6710faf75) in te schakelen, waardoor alle gebruikers die deel uitmaken van hun projecten MFA moeten gebruiken om het project in te voeren. Neem contact op met de ondersteuning van Catenda om MFA op de projecten van uw organisatie in te schakelen. Wanneer MFA is vereist op de projecten van een organisatie, ziet u dit bericht wanneer u probeert het project te openen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/07-who-can-enforce-mfa-on-projects.png)
