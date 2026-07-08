# Multi-Factor Authenticatie

> Beschrijft hoe u MFA op uw account instelt

U kunt de **Multi-Factor Authenticatie** (MFA) instellingen vinden op de [verificatiepagina](https://support.catenda.com/en/articles/6880968-account-page#h_e04d63351f), die een subpagina is van de [accountpagina](https://support.catenda.com/en/articles/6880968-account-page).

**Multi-Factor Authenticatie** (MFA) vereist het invoeren van een code die u via uw mobiele apparaat ontvangt, evenals uw gebruikersnaam en wachtwoord, wanneer u zich aanmeldt bij Catenda Hub. Wanneer een organisatie MFA vereist, wordt deze toegepast op organisatieniveau. Alle projecten die tot die organisatie behoren, vereisen dan MFA om toegang tot hun projecten te krijgen. Dit dwingt alle gebruikers om MFA in te schakelen om toegang te krijgen tot projecten die tot die organisatie behoren.

## 1. **MFA inschakelen**

Meld u aan bij Catenda Hub en ga naar de **[Account](https://hub.catenda.com/account/profile)** pagina:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/01-enabling-mfa.png)

1. Klik op het **[Verificatie](https://hub.catenda.com/account/authentication)** tabblad:
2. Scrol omlaag naar het gedeelte voor MFA:
3. Klik op **MFA inschakelen**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/02-enabling-mfa.png)

### 1.1 **Verificatietoepassing**

Installeer een toepassing op een mobiel apparaat die het TOTP (Time-based one-time password) protocol ondersteunt. Installeer een vertrouwde verificatietoepassing op een mobiel apparaat om aan de slag te gaan. De hoeveelheid tijd dat een verificatietoepassing al bestaat en de rechtsmacht waar het bedrijf dat eigenaar is van, gevestigd is, zijn vaak goed om naar te kijken. Hier zijn enkele voorbeelden van aanbevolen verificatietoepassingen:

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 139px;"><h3 id="h_b56161ee38"><b>Beveiligingswetten voor verificatietoepassing</b></h3></td><td style="background-color: #e3e7fa80; width: 101px;"><h3 id="h_49bc31efe9">Bedrijf</h3></td><td style="background-color: #e3e7fa80; width: 119px;"><h3 id="h_46b679c81c">Rechtsmacht</h3></td><td style="background-color: #e3e7fa80;"><h3 id="h_7699fa4ab6">Van toepassing zijnde beveiligingswetten</h3></td></tr><tr><td style="width: 139px;"><h3 id="h_ae65255403">Aegis</h3></td><td style="width: 101px;"><p>Beem</p></td><td style="width: 119px;"><p>Nederland<br/>(Dordrecht)</p></td><td><p>AVG<br/>9 eyes agreement</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_42b556ff02">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Roland Moers</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Duitsland</p></td><td style="background-color: #e8e8e880;"><p>AVG<br/>Bundesdatenschutzgesetz - BDSG <br/>14 eyes agreement</p></td></tr><tr><td style="width: 139px;"><h3 id="h_5e0c03d260">Authenticator</h3></td><td style="width: 101px;"><p>Google</p></td><td style="width: 119px;"><p>Verenigde Staten<br/>(Californië)</p></td><td><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_918c12706e">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Microsoft</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Verenigde Staten<br/>(Washington)</p></td><td style="background-color: #e8e8e880;"><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="width: 139px;"><h3 id="h_b3a055f26d">Ente Auth</h3></td><td style="width: 101px;"><p>Ente</p></td><td style="width: 119px;"><p>Verenigde Staten (Delaware)</p></td><td><p>Clarifying Lawful Overseas Use of Data Act <i>(</i>CLOUD) Act</p></td></tr><tr><td style="background-color: #e8e8e880; width: 139px;"><h3 id="h_63d03979d2">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 101px;"><p>Internet Initiative Japan</p></td><td style="background-color: #e8e8e880; width: 119px;"><p>Japan</p></td><td style="background-color: #e8e8e880;"><p>Act on the Protection of Personal Information (APPI)</p></td></tr><tr><td style="width: 139px;"><h3 id="h_848afb2dfa">HENNGE Lock</h3></td><td style="width: 101px;"><p>HENNGE K.K.</p></td><td style="width: 119px;"><p>Japan</p></td><td><p>Act on the Protection of Personal Information (APPI)</p></td></tr></tbody></table></div>

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 138px;"><h3 id="h_5e28bb0eb3"><b>Functionaliteit verificatietoepassing</b></h3></td><td style="background-color: #e3e7fa80; width: 88px;"><h3 id="h_6ed7d3e230">Releasedatum</h3></td><td style="background-color: #e3e7fa80; width: 180px;"><h3 id="h_f652151c66">Besturingssysteem</h3></td><td style="background-color: #e3e7fa80;"><h3 id="h_824368384e">Codeextractie</h3></td></tr><tr><td style="width: 138px;"><h3 id="h_218c61c8b2">Aegis</h3></td><td style="width: 88px;"><p>2019</p></td><td style="width: 180px;"><p>Android</p></td><td><p>Exporteren naar Full Plaintext of Encrypted-bestand. JSON / TXT / QR</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_0274ada2cb">OTP Auth</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2020</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS</p></td><td style="background-color: #e8e8e880;"><p>Exporteren naar propriëtair bestand / Geheim weergeven</p></td></tr><tr><td style="width: 138px;"><h3 id="h_cc8ae8a27d">Authenticator</h3></td><td style="width: 88px;"><p>2010</p></td><td style="width: 180px;"><p>iOS<br/>Android</p></td><td><p>Overdragen naar andere Google Authenticator-app met Google-account</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_6d595cbd69">Microsoft Authenticator</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS<br/>Android</p></td><td style="background-color: #e8e8e880;"><p>Overdragen naar andere Microsoft Authenticator-app met Microsoft-account.</p></td></tr><tr><td style="width: 138px;"><h3 id="h_9cbe3f20d2">Ente Auth</h3></td><td style="width: 88px;"><p>2020</p></td><td style="width: 180px;"><p>iOS<br/>Android</p></td><td><p>JSON / TXT</p></td></tr><tr><td style="background-color: #e8e8e880; width: 138px;"><h3 id="h_425ee9cdba">IIJ SmartKey</h3></td><td style="background-color: #e8e8e880; width: 88px;"><p>2015</p></td><td style="background-color: #e8e8e880; width: 180px;"><p>iOS - 8.1+<br/>Android - 4.0+</p></td><td style="background-color: #e8e8e880;"><p>QR-codeexport per code.</p></td></tr><tr><td style="width: 138px;"><h3 id="h_10c8930b4e">HENNGE Lock</h3></td><td style="width: 88px;"><p>2020</p></td><td style="width: 180px;"><p>iOS - Laatste 2 grote versies <br/>Android - Laatste 4 codenamen versies</p></td><td><p>Geen</p></td></tr></tbody></table></div>

Theoretisch kan elke toepassing die MFA / Twee-factor authenticatie via het TOTP protocol ondersteunt, gebruikt worden. Er zijn zelfs desktoptoepassingen, maar deze worden niet aanbevolen omdat desktoptoepassingen vaak altijd verbonden zijn met hetzelfde netwerk dat meerdere apparaten bevat, wat het risico vergroot dat een slechte speler toegang krijgt tot de code.

**App-machtigingen** Om u in staat te stellen om de QR-code met de camera van het apparaat te scannen. De verificatietoepassing moet cameramachtigingen hebben om de code te kunnen scannen. De toepassing kan u vragen om toestemming te geven voor het gebruik van de camera van het apparaat. Machtigingsopties kunnen zijn: "Alleen wanneer de app in gebruik is" - De app heeft machtiging terwijl deze in gebruik is. "Elke keer vragen" - Machtiging moet bij elk gebruik van de app worden verleend. "Niet toestaan" - Machtiging wordt niet verleend of ingetrokken voor de app.

**Google Authenticator** Klik op het plusteken rechtsonder en scan een QR-code. Hier scant u de QR-code die de [verificatiepagina](https://hub.catenda.com/account/authentication) u geeft. U kunt ook uw camera gebruiken om de code te scannen en de instellingssleutel die u in de geopende URL ziet, in te voeren.

**Microsoft Authenticator** Zorg ervoor dat u zich in het Authenticator-menu onderaan bevindt.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/03-authentication-app.png)

> **Opmerking:** Zorg ervoor dat u zich niet in het menu Geverifieerde ID's bevindt, omdat u hier een QR-code kunt scannen, maar dit werkt niet.

Klik vervolgens op het plusteken in de blauwe balk rechtsboven. Selecteer Ander account (Google, Facebook, enz.) Als uw app geen machtiging voor uw camera heeft, kan u al dan niet worden gevraagd om machtiging voor uw camera te geven.

Als uw app toegang tot uw camera heeft, kunt u de QR-code scannen die de [verificatiepagina](https://hub.catenda.com/account/authentication) u geeft.

Als uw app geen toegang tot uw camera heeft, wordt u gevraagd om handmatig een account aan te maken.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/04-authentication-app.png)

Accountnaam: De naam die u aan uw account geeft Geheime sleutel: Dit is de sleutel die u zou hebben gekregen als u de QR-code zou hebben kunnen scannen. U kunt uw camera-app gebruiken om de code te scannen. De URL die opent wanneer u de code scant, kan er als volgt uitzien: `otpauth://totp/\<Catenda account e-mailadres>?secret=\<Geheime sleutel>&issuer=Catenda&algorithm=SHA1&digits=6&period=30` Als u de code invoert na "`secret=`" in de geheime sleutel die u in de geopende URL ziet, kan de accountnaam alles zijn.

> **Opmerking:** Als u een account met de verkeerde geheime sleutel aanmaakt, genereert de app toch eenmalige codes, dus Catenda accepteert de code mogelijk niet als de verkeerde geheime sleutel werd gebruikt.

### 1.2 **Succes of mislukking**

**Succes** Na het succesvol inschakelen van MFA ziet u dit bericht.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/05-success-or-fail.png)

Na het inschakelen moet u uw mobiele apparaat altijd bij de hand hebben wanneer u zich aanmeldt bij Catenda Hub. De MFA kan opnieuw worden uitgeschakeld door op MFA uitschakelen te klikken.

**Onjuiste code** Als u niet de juiste code hebt ingevoerd, krijgt u het bericht onjuiste code.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/06-success-or-fail.png)

> **Opmerking:** Als u de QR-code hebt gescand, kunt u proberen om de code in het gegeven tijdsframe in te voeren terwijl dit menu open is. Als u dit menu sluit, moet u de code die in uw verificatietoepassing wordt gegenereerd verwijderen en de QR-code opnieuw scannen om een nieuwe codekoppeling in te stellen.

## 2. **MFA wijzigen**

Na het verbinden van een MFA-code kunt u veilig de accountnaam van de code bewerken. U kunt dit op de volgende manieren doen:

**Google Authenticator**

1. Houd de code ingedrukt
2. Klik op het potlood rechtsboven om de naam te wijzigen.

**Microsoft Authenticator**

1. Klik op de code.
2. Klik op de tandwielpictogram rechtsboven
3. Klik op het potlood om de naam te wijzigen

## 3. **MFA overdragen**

**Uitschakelen en opnieuw inschakelen** Het is slechts mogelijk om één MFA app-codekoppeling tegelijk te gebruiken. Als u wilt overschakelen naar een ander codepaar, misschien omdat uw huidige is gecompromitteerd, volgt u deze stappen: U moet deze methode ook gebruiken als u de app die u voor MFA gebruikt, wilt wijzigen.

1. Schakel uw MFA uit op de [verificatiepagina](https://hub.catenda.com/account/authentication)
2. Bereid de app voor die u wilt gebruiken om uw MFA opnieuw aan te sluiten
3. Genereer een nieuw codepaar door de QR-code te scannen zoals in de [inschakeling-sectie](#enabling-mfa)

> **Opmerking:** Wees voorzichtig met deze methode, want uw account is kwetsbaar terwijl het uitgeschakeld is en u kunt gedurende deze tijd geen toegang krijgen tot projecten waar MFA vereist is.

**Overdragen via back-up** Als u wilt beginnen met het gebruik van een nieuw apparaat zonder dat uw code tijdelijk wordt uitgeschakeld, kunt u een andere installatie van dezelfde MFA-app gebruiken en de code van de oude installatie naar de nieuwe installatie overdragen.

**Google Authenticator** Oud apparaat:

1. Tik op het hamburgermenu rechtsboven
2. Tik op Accounts exporteren
3. Selecteer de accounts die u wilt exporteren

Nieuw apparaat:

1. Tik op het hamburgermenu rechtsboven
2. Tik op accounts importeren
3. Tik op QR-code scannen
4. Scan de QR-code die op het oude apparaat wordt weergegeven toen u het exportproces doorliep.

**Microsoft Authenticator** Oud apparaat:

1. Tik op het hamburgermenu rechtsboven
2. Back-up inschakelen

Nieuw apparaat:

1. Installeer en open de Microsoft Authenticator-app op uw nieuwe apparaat
2. Tik op "Herstel starten."

> **Opmerking 1:** Stel geen accounts in met Microsoft Authenticator totdat u het Herstelhulpmiddel hebt gebruikt, anders worden overeenkomende site-accounts overschreven.

> **Opmerking 2:** Deze methode vereist dat u een back-up van uw MFA-codes maakt, wat betekent dat deze in de cloudservice van uw app-provider worden opgeslagen. Gebruik deze methode alleen als u de back-upservice van uw app-provider vertrouwt. Anders is het beter om uit te schakelen en opnieuw in te schakelen.

## 4. **MFA uitschakelen**

U kunt MFA uitschakelen door op de uitschakelknop hierboven te klikken en vervolgens uw wachtwoord in te voeren ter bevestiging. Na het uitschakelen kunt u geen toegang meer krijgen tot projecten waarvoor MFA vereist is.

Na het uitschakelen van de code op Catenda Hub, blijft de code op de toepassing waarmee u verbonden bent. Deze code is nu waardeloos en kan veilig worden verwijderd.

### 4.1 **De oude code verwijderen:**

**Google Authenticator**

1. Houd de code ingedrukt
2. Klik op het prullenmand-pictogram rechtsboven.

**Microsoft Authenticator**

1. Klik op de code.
2. Klik op de tandwielpictogram rechtsboven
3. Klik op account verwijderen

## 5. **MFA op niet-mobiele apparaten**

Verificatieapps zijn veiliger dan SMS/E-mailcodeoplossingen omdat er na de oorspronkelijke configuratie geen communicatie kan worden onderschept tussen de twee systemen. Hoewel het beter is om een app op een mobiele toepassing te gebruiken, zie opmerking hieronder, het is mogelijk om MFA-codes op andere systemen dan alleen mobiele apparaten op te halen. De aanbevolen desktoptoepassing hiervoor is [Authy](https://authy.com/). Functioneel gebruiken deze soorten toepassingen hetzelfde TOTP-protocol als de app op uw mobiele apparaat en zouden even veilig moeten zijn.

> **Waarschuwing:** Desktopapps kunnen minder veilig zijn omdat ze gemakkelijker kunnen worden gehackt of toegang tot kunnen krijgen. Dit is omdat desktopsystemen vaak, zoniet altijd, verbonden zijn met het lokale netwerk dat mogelijk is geïnfecteerd. Mobiele apparaten die niet altijd met het netwerk zijn verbonden, kunnen daarom moeilijker toegang krijgen.

## 6. **Wie kan MFA op projecten afdwingen?**

Ondernemingsklanten kunnen verzoeken om een [organisatieoptie](https://support.catenda.com/en/articles/8224886-organization-options#h_d6710faf75) in te schakelen waardoor alle gebruikers die deel uitmaken van hun projecten MFA moeten gebruiken om het project in te voeren. Neem contact op met Catenda-ondersteuning om MFA op de projecten van uw organisatie in te schakelen. Wanneer MFA vereist is op de projecten van een organisatie, ziet u dit bericht wanneer u het project probeert te openen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/q7gf11z1/07-who-can-enforce-mfa-on-projects.png)
