# Multi Factor Authenticatie

U zal de **Multi Factor Authenticatie** (MFA) instellingen op de [authenticatie pagina](https://support.catenda.com/en/articles/6880968-account-page#h_e04d63351f) die een onderpagina van de [account pagina](https://support.catenda.com/en/articles/6880968-account-page) is kunnen vinden.

Als **Multi Factor Authenticatie** (MFA) geactiveerd is wordt er grevraagt om een code die u via uw mobile eenheid ontvangen heeft in te voeren, samen met uw gebruikersnaam en wachtwoord, bij het inloggen in Catenda Hub. Wanneer een organizatie MFA vereist zal dit op het organizatieniveau toegepast zijn. Alle projecten die tot die organizatie behoren eisen dan om MFA te activeren en deze code in te voeren om hun projecten binnen te komen. Dit maakt het zo dat alle gebruikers die toegang willen hebben tot the projecten van een organizatie MFA moeten activeren.

Deze pagina houd informatie over de volgende themas in:

## 1. **MFA activeren**

Log in bij Catenda Hub en ga naar det **[Account](https://hub.catenda.com/account/profile)** pagina:

![](https://downloads.intercomcdn.com/i/o/710942054/f2239e2186f2107afadd66a3/image.png?expires=1781092800&signature=f38bc42351fd302ec7396fa6cf12192e80e28a0d7f3432cf1ef011332c36b874&req=cyEnH818nYRbFb4V1XW4gc7BaZEBKtWdCLphfgCiOK%2Bew%2FThhA88vrm%2FPJq5%0APAs7mDo6nKHLBwYjCUY3Kyp9%2Bg%3D%3D%0A)

1. Klik op de **[Authenticatie](https://hub.catenda.com/account/authentication)** tab:
1. Scroll naar beneden naar het MFA gedeelte:
1. Klik op **Schakel MFA in**

![](https://downloads.intercomcdn.com/i/o/710944230/ebe37c5fb2379afe1d58d515/image.png?expires=1781092800&signature=bb1b215bf932a3da6fd9efd65031aa089830c4fa92090872b305802d5370aa61&req=cyEnH816n4JfFb4V1XW4gTVsh%2FWNq4RWV4OD%2BiH2LjOrUp6WWcpjxhq9folB%0A%2BuwHJKhvj1SGgt1qEKhqKE8VEQ%3D%3D%0A)

### 1.1 **Authentication app**

U zal een authenticatie app due u op uw mobiele eenheid vertrouwt nodig hebben.

Wij raden de [Google Authenticator](https://support.google.com/accounts/answer/1066447?co=GENIE.Platform%3DAndroid&hl=en) en de [Microsoft Authenticator](https://www.microsoft.com/en-us/account/authenticator) aan, maar u kunt theoretisch alle applicaties die het koppelen van MFA / Two factor authentication steunen gebruiken.

**App toegang**

Om u de QR code te kunnen laten scannen met uw camera zal u de authenticatie app toegang tot uw camera moeten geven. Wanneer u de applicatie installert kan u gevraaagd worden om de app toegang tot de camera te geven, alleen gedurende het gebruik van de app of dat er elke keer gevraagd moet worden of dat je geen toegang verleent.

Als u selecteert dat er elke keer gevraagt moet worden zal u elke keer om toegang gevraagt worden wanneer de app de camera wilt gebruiken. Hier zal u nogmaals de keuzen hebben om deze toegang te weigeren waarna deze vanaf dan geheel voor de app uit zal staan en er niet meer om gevraagt wordt. De app heeft dan geen toegang tot de camera.

**Google Authenticator**

Klik op de plus rechtsonder en scan een QR code.

Hier zal u de QR code scannen die de Catenda [authenticatie](https://hub.catenda.com/account/authentication) pagina u geeft.

Als alternatief kunt u uw camera gebruiken om de code te scannen waarna de setup key die in the URL staat ingevoerd kan worden.

**Microsoft Authenticator**

Pas op dat u in het authenticatie menu onderaan bent.

![](https://downloads.intercomcdn.com/i/o/825376957/d0ca2f4ff3122f26c2dd335e/image.png?expires=1781092800&signature=be1fcb59fb1bfa4b45e2cd97b6ea4639f51a97ac61ba103a8b19816235d2ee72&req=fCIiFc54lIRYFb4V1XW4gStU4QZFJuspH3Amx6IfbI1PH8Ta9AUUSD4f5PCO%0AAP4KnLWAE5JAwe0UK5S1t71eeA%3D%3D%0A)

> **Note:** **Merk:** Pas op dat u nit in het Verified IDs menu bent omdat u hier ook een qr code kunt scannen maar deze zal niet werken.

Klik verder op de plus in de blauwe balk rechtsboven.

Selecteer Other account (Google, Facebook, etc.)

Als uw app geen toegang heeft tot uw camera kan u wel of niet gevraagt worden om toegang te geven tot uw camera.

Als u w app toegang tot uw camera heeft kan u de QR code die zich op de [authenticatie](https://hub.catenda.com/account/authentication) pagina bevind.

Als uw app geen toegang tot uw camera heeft zal u gevraagd worden om met de hand een account aan te maken.

![](https://downloads.intercomcdn.com/i/o/1073587443/5a6dda006a38943a4c11fc28/image.png?expires=1781092800&signature=6859b1a2a4081eacf5fe3e3b2cbc8cbc20fe23ba599c13b94523c6aef1a0d697&req=dSAgFcx2moVbWvMW3nq%2BgQ2uGk1EdfhU4hASnzRRD%2FCNPzlrB1T21b5PfCNs%0AoaOKhDzf4%2BW06huquS6IL07Iqqg%3D%0A)

Account name: De naam die u aan de account geeft. Secret key: Dit is de sleutel die u gekregen zou moeten hebben als u de QR code met de app had gescant. U kunt de QR code ook met de camera app scannen. De URL die dan opent kan er zo uit zien: `otpauth://totp/\<Catenda account email address>?secret=\<Secret key>&issuer=Catenda&algorithm=SHA1&digits=6&period=30`

Als u de code na "`secret=`" die u in de URL die geopent is ziet kan deze in het secret key gedeelte ingevoert worden. Het maakt niet uit wat je in het account name veld invoert.

> **Note:** **Merk:** Als u en accout met de verkeerde secret key aanmaakt zal de app een one-time code toch aanmaken. Het kan dan zo zijn dat Catenda deze code niet accepteerd.

### 1.2 **Success or fail**

**Success**

Na het succesvol koppelen van MFA zal u dit bericht zien.

![](https://downloads.intercomcdn.com/i/o/areracg3/1278984783/550dc84e6c139543a0c228cb373c/image.png?expires=1781092800&signature=7fed7cda4d3a088aec375a3b8ffa14e4d47c301b38889c6a47720dcc8c89ec2a&req=dSIgHsB2mYZXWvMW3nq%2BgRzwWwxdVEP3raE2TkKALU9uKnULF7lc6rffERNQ%0AzJyivj5FME%2BS3astKTkqIY9u8Mc%3D%0A)

Na het kopelen zal u elke keer bij het inloggen in Catenda uw mobiele eenheid bij de hand moeten hebben.

De MFA kan gedeactiveerd worden door op deactiveer MFA te klikken.

**Incorrect code**

Foute code

If you did not insert the right code, you will get the message incorrrect code.

![](https://downloads.intercomcdn.com/i/o/areracg3/1278986910/fcf1dbb07ae982b15c655966b724/image.png?expires=1781092800&signature=b82460509b0074191d2a688692119b66fe0f3d7d25f887e359c7c701efc1a706&req=dSIgHsB2m4heWfMW3nq%2BgR6FUMmT2YJm5kXqqdp81bdgJjZuhxAXRoYDkUpp%0A%2By1CkiG5Pi56MWTUTQ7quR7FYqM%3D%0A)

> **Note:** **Merk:** Als u de QR-Code heeft gescant kut u deze opniew proberen in te voeren binnen de gegeven tijd voor de code terwijl dit menu open is. Alsu u dit menu afsluit zal u de code die in uw authenticator app gegenereerd wordt moeten verwijderen en de QR-Code op nieuw scannen om een nieuwe code kopppeling aan te maken.

## 2. **MFA veranderen**

Na het koppelen van een MFA code kan u met zekerheid de account naam van de code veranderen. Dit kan op de volgende manieren gedaan worden:

**Google authenticator**

1. Hou de code ingedrukt
1. Klik op het potlood rechtsboven om de naam te veranderen.

**Microsoft authenticator**

1. Klik op de code.
1. Klik op het tandwiel rechtsbovenaan
1. Klik op het podlood om de naam te veranderen

## 3. **MFA overhevelen**

**De-activeren en re-activeren**

Het is alleen mogelijk om een MFA app code tegelijkertijd te koppelen.

Als u wenst om naar een verschillende code koppeling te veranderen, misschien omdat de geldende code is gecompromitteerd, kunt u de volgende stappen volgen:

U zal ook deze methode gebruiken als u van app wenst te veranderen voor gebruik van MFA.

Deactiveer MFA op de [authentication page](https://hub.catenda.com/account/authentication).

1. Bereid de app die u wenst te gebruiken om de MFA te her-koppelen voor.
1. Genereer een nieuwe code-paring door de QR code te scannen zoals in het [activeren gedeelte](#h_bda390ecdc).

> **Note:** **Merk:** Pas op met deze methode omdat uw account tijdelijk kwetsbaar is terwijl deze gedeactiveerd is. Gedurende deze tijd zal u ook geen toegang hebben tot projecten waar MFA vereist is.

**Overhevelen door backup**

Als u wenst om een nieuwe eenheid te gebruiken zonder dat uw code tijdelijk gedeactiveerd is kunt u de code naar een andere installatie van dezelfde MFA app overhevelen van de oude installatie naar de nieuwe installatie.

**Google authenticator**

Oude eenheid:

1. Tap op het hamburger menu rechtsboven
1. Tap op Export accounts
1. Selecteer de accounts die u wenst te expoteren

Nieuwe eenheid:

1. Tap op het hamburger menu rechtsboven.
1. Tap op import accounts
1. Tap op scan QR code
1. Scan de QR code die getoond is op de oude eenheid waar u door het export process bent gegaan.

**Microsoft authenticator**

Oude eenheid:

1. Tap op het hamburgermenu rechtsboven
1. Activeer de backup

Nieuwe eenheid:

1. Installeer en open de Microsoft Authenticator app op uw nieuwe eenheid
1. Tap "Begin Recovery."

> **Note:** **Mer 1:** Stel geen andere accounts met de Microsoft Authenticator in tot na u de Recovery tool gebruikt hebt omdat accounts met dezelfde naam overschreven kunnen worden.

> **Note:** **Merk 2:** Deze methode eist dat u een backup van uw MFA codes maakt wat betekend dat deze in de leverancier van uw apps cloud service opgeslagen zijn. Gebruik daarom alleen deze methode als u deze cloud service vertrouwt. Als niet dan kunt u de code beter deactiveren en heractiveren.

## 4. **MFA deactiveren**

U kunt MFA deactiveren door op de deactiveer knop te kliken als hierboven aangeduid waarna u uw wachtwoord in moet typen om te bevestigen. Na het deactiveren zal geen toegang meer hebben tot projecten waar MFA vereist is.

Na het deactiveren van de code op Catenda Hub zal de code op uw applicatie waarmee u gekoppeld had blijven. Deze code zal nu geen nut meer hebben en kan met zekerheid verwijdered worden.

### 4.1 **Hoe de oude code verwijdert kan worden:**

**Google authenticator**

1. Houd de code ingedrukt
1. Klik op de afvalbak rechtsboven.

**Microsoft authenticator**

1. Klik op de code.
1. Klik op de tandwiel knop rechtsboven
1. Klik op verwijder account

## 5. **MFA op niet-mobile eenheden**

Authenticatie apps zijn zekerder dan SMS/Email code oplossingen omdat er geen communicatie die onderschept kan worden plaats vindt tussen de twee systemen na de originele configuratie.

Terwijl het beter is om een app op een mobiele eenheid te gebruiken, zie notaat hier onder, is het mogelijk om MFA codes op andere systemen dan alleen mobiele eenheden te installeren. De aanbevolden desktop applicatie hiervoor is [Authy](https://authy.com/).

Kwa functionaliteid gebruiken deze soort applicaties dezelfde TOTP protocol als de app op uw mobiele eeneid en zoude net zo zeker moeten zijn.

> **Note:** **Merk:** Desktop applicaties kunnen minder zeker zijn en makkelijker om toegang tot te krijgen. Dit kan zijn omdat desktop systemen vaak, als niet altijd, tot het locale netwekr verbonden zijn wat geinficeerd kan zijn. Mobiele eenheden die niet alteid verbonden zijn tot het netwerk kunnen daarom moeilijker zijn om binnen in te komen.

## 6. **Wie kan MFA in projecten afdwingen?**

Enterprise klanten kunnen aanvragen om een [organization optie](https://support.catenda.com/en/articles/8224886-organization-options#h_d6710faf75) te activeren die het zo maakt dat alle gebruikers die deel zijn van hun projecten MFA gekoppelt moeten hebben om het project binnen te komen.

Kontakt graag Catenda support om MFA te activeren voor uw organizaties porjecten. Wanneer MFA vereist is voor uw organizatie's projeten zal u dit bericht zien wanner er geprobeert wordt om een project te openen zonder dat MFA gekoppeld is.

![](https://downloads.intercomcdn.com/i/o/710237963/cc33c301cac2faaeaf8abb7e/image.png?expires=1781092800&signature=0a241c1b7d754dac6ac7f3fbfb908a97d6aad26a98db0773434988edd6c61515&req=cyEnFMp5lIdcFb4V1XW4geDBTPE7FEI38r7z7CIHG0OMPqmboH9ClY59uD%2F2%0APKhzmnNJ76NXpaOhL%2BVeRBzIhw%3D%3D%0A)
