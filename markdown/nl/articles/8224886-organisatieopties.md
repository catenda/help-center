# Organisatieopties

Het is mogelijk om de volgende opties voor uw organisatie in te stellen. Deze opties zijn van toepassing op alle projecten die eigendom zijn van de organisatie.

## 1. **Profiel**

Neem contact op met ondersteuning via de zwarte chatknop naast uw profielfoto in de rechterbovenhoek of via [support@catenda.com](mailto:support@catenda.com) als u de naam van uw organisatie wilt wijzigen.

## 2. **Plan**

Neem contact op met [sales@catenda.com](mailto:sales@catenda.com) voor vragen over uw plan. Uw plan bepaalt hoeveel projecten u op een bepaald moment in een organisatie kunt hebben. Uw plan bepaalt ook wanneer nieuwe projecten verlopen.

## 3. **Standaardinstellingen voor nieuwe projecten**

### 3.1 Optie voor documentdownload-titel

Als u een enkel document downloadt, is de bestandsnaam altijd de oorspronkelijke bestandsnaam. Als u meerdere documenten downloadt, zijn de bestandsnamen de namen van de documenten.

Met deze optie kunt u configureren welke bestandsnaam u krijgt wanneer u meerdere documenten downloadt. Dit kan nuttig zijn in combinatie met de naamgevingsconventie en voor het overschrijven van documenten met dezelfde naam in plaats van elke keer met een ander revisienummer.

**Voorbeeld:** De naam van het project is _testproject._ Twee bestanden worden geüpload met elk twee revisies: _test01.pdf_ en _test02.pdf_ De namen van de documenten worden vervolgens gewijzigd in: _changed01.pdf_ en _changed02.pdf_

Standaarddownloadgedrag: Als u deze documenten één voor één downloadt, worden ze altijd genoemd _test01.pdf_ en _test02.pdf_ Als u beide documenten tegelijk downloadt, worden ze standaard _changed01.pdf_ en _changed02.pdf_ genoemd. Dit is wat kan worden gewijzigd met de volgende opties:

**Opties:**

**Revisiebestandsnaam** Let op: dit is hetzelfde als bij het downloaden van een enkel bestand, dus de namen zullen consistent zijn als u deze optie kiest. \<Oorspronkelijke bestandsnaam>.\<Extensie> _test01.pdf_ en _test02.pdf_

_Documenttitel_ - standaard \<Documentnaam>.\<Extensie> _changed01.pdf_ en _changed02.pdf_

**Documenttitel met revisienummer** \<Documentnaam>\<Revisienummer>.\<Extensie> _changed01.pdf #2_ en _changed02.pdf #2_

**Projecttitel met Documenttitel en Revisienummer** \<Projectnaam>\<Documentnaam>\<Revisienummer>.\<Extensie> _testproject changed01.pdf #2_ en _testproject changed02.pdf #2_

### 3.2 **Downloaden van geïnfecteerde Documenten**

Quarantaineafhandeling voor geïnfecteerde bestanden in eigendomprojjecten. Als een document als geïnfecteerd wordt gedetecteerd, kan het standaard worden gedownload. De gebruiker ontvangt een waarschuwing dat dit document een virus bevat. Er kan een optie per organisatie worden ingesteld zodat niemand, zelfs niet beheerders, geïnfecteerde documenten kan downloaden.

**Opties:** _Waarschuwing bij download_ - standaard

**Download blokkeren**

### 3.3 **Modellen als Documenten**

Als deze functie is ingeschakeld, hebben alle nieuwe projecten die in de organisatie worden gemaakt, de functie [Modellen als Documenten](https://support.catenda.com/en/articles/8064548-models-as-documents) ingeschakeld.

> **Opmerking:** 24 november: Deze functie wordt ingeschakeld voor alle nieuwe organisaties. We zullen de oude weergave ongeveer een jaar ondersteunen voordat alle projecten worden gemigreerd.

### 3.4 **Optie voor documentupload als concept**

Als de goedkeuringsstroom is ingeschakeld en er conceptstatussen in documentinstellingen zijn, wordt het selectievakje "als concept uploaden" standaard ingeschakeld bij documentupload. Op aanvraag kan dit selectievakje standaard uitgeschakeld worden voor alle projecten in een organisatie.

## 4. **Leden**

Gebruikers kunnen als leden of eigenaren van een organisatie worden toegevoegd.

### 4.1 **Eigenaren**

Eigenaren van organisaties kunnen een overzicht van de organisatie zien in het [organisatiegebruikersvenster](http://hub.catenda.com/orgs). In dit gereedschap kunnen zij het volgende doen: Projecten verplaatsen naar andere organisaties die zij eigenaar zijn (Archieven zijn vaak afzonderlijke organisaties) Nieuwe projecten maken in de organisatie als uw plan dit toestaat. Projecten verwijderen die eigendom zijn van de organisatie. Organisatieleden aan projecten toevoegen zonder hen uit te nodigen. Gebruikers uitnodigen voor organisatieprojecten zonder deel uit te maken van het project. Het wordt aanbevolen dat organisatie-eigenaren gering in aantal blijven, aangezien projecten niet vaak hoeven te worden verplaatst.

### 4.2 **Leden**

Leden van organisaties kunnen eenvoudig door organisatie-eigenaren aan de projecten van de organisatie worden toegevoegd.

## 5. **Projecteigenaar regels**

### 5.1 **Afdwingen dat alle gebruikers MFA vereisen**

Ondernemingsklanten kunnen de afdwinging van MFA voor gebruikers die aan hun projecten deelnemen aanvragen. Met deze optie moeten alle gebruikers MFA hebben ingesteld om deel te nemen aan projecten die eigendom zijn van uw organisatie.

### 5.2 **Interne SSO-gebruikers vereisen geen MFA**

Ondernemingsklanten kunnen aanvragen [Single Sign-On](https://en.wikipedia.org/wiki/Single_sign-on) in te stellen. Er is een vergoeding gemoeid mee omdat onze ontwikkelaars tijd nodig hebben om de configuratie in te stellen.

_Wat doet deze regel?_ Standaard worden gebruikers die zich aanmelden met SSO en gebruikers die zich normaal aanmelden op dezelfde manier behandeld. Als MFA voor een organisatie wordt afgedwongen, moeten zowel normale gebruikers als SSO-gebruikers de MFA-code invoeren om zich aan te melden en toegang te krijgen tot het project. Als deze optie voor een organisatie is ingeschakeld, hoeven SSO-gebruikers geen MFA te gebruiken voor toegang tot het project. Normale gebruikers zouden nog steeds de MFA-code moeten invoeren, terwijl SSO-gebruikers zich zonder de code zouden kunnen aanmelden.

_Wat is SSO?_ [Single Sign-On](https://en.wikipedia.org/wiki/Single_sign-on) stelt de gebruiker in staat zich eenmaal aan te melden en services te openen zonder verificatiefactoren opnieuw in te voeren. Met deze optie kunt u ervoor zorgen dat gebruikers van uw organisatie geen MFA hoeven in te stellen. Gebruikers van verschillende organisaties die deel uitmaken van uw organisatieprojecten moeten nog steeds MFA hebben ingeschakeld als de bovenstaande optie is ingeschakeld.

_SSO instellen:_ Het is mogelijk om SSO in te stellen met elke SSO-provider, aangezien het een gestandaardiseerd proces is. Hieronder vindt u enkele van de meest voorkomende SSO-providers:

_Microsoft Active Directory:_ Om SSO met Microsoft Active Directory te configureren, moet een nieuwe Azure Enterprise Application in de Azure AD-omgeving worden geconfigureerd. Dit is meestal de systeembeheerder van de organisatie die deze configuratie uitvoert. In de Azure AD-omgeving moeten de volgende velden met SAML-authenticatie door de systeembeheerder worden ingevuld: Entity ID: [https://hub.catenda.com/metadata.xml](https://hub.catenda.com/metadata.xml) Dit XML-bestand kan worden gedownload, maar doorgaans mag alleen de URL in het veld worden geplakt. Assertion Consumer Service (ACS) URL: [https://hub.catenda.com/sso/saml/v2/attribute](https://hub.catenda.com/sso/saml/v2/attribute) Deze link mag ook in het veld worden geplaatst en is niet toegankelijk door deze in een browser te openen. Nadat de identiteitsprovider is geconfigureerd, verzendt deze een POST-aanvraag naar dit eindpunt. Als dit eindpunt vanuit een normale browser (GET-aanvraag) of via een POST-aanvraag zonder de juiste gegevens wordt aangeroepen, laadt de pagina niet. Sign-on URL [https://hub.catenda.com/signin](https://hub.catenda.com/signin) Dit is de aanmeldpagina die vóór het verlenen van toegang tot Catenda naar de geconfigureerde identiteitsprovider wordt omgeleid.

Als dat klaar is, moet uw systeembeheerder contact met ons opnemen met de App Federation Metadata URL en Federation Metadata XML voor de nieuwe toepassing.

**GSuite:** Stel SSO in zoals in [dit artikel](https://support.google.com/a/answer/12032922?hl=en)

**Testgebruikers:** Nadat de SSO-instelling is geconfigureerd, dient u een lijst met testgebruikers in te dienen waarvoor SSO eerst kan worden ingeschakeld, zodat u kunt zien hoe SSO voor hen werkt. Nadat de testgebruikers zijn getest, kunnen de overige gebruikers worden ingeschakeld.

**Zwart- en Whitelist:** Het is ook mogelijk een zwart/witlijst in te stellen: Bijvoorbeeld: Alle gebruikers behalve: X, Y enzovoort mogen zich aanmelden met SSO of, Alleen X, Y enzovoort mogen zich aanmelden met SSO Deze informatie zal naast het XML-bestand zoals hierboven aangegeven moeten worden verstrekt.

### 5.3 **Functie voor openbaar delen uitschakelen**

Met deze optie kunt u de functie voor openbaar delen voor alle projecten in uw organisatie uitschakelen. Als deze optie is ingeschakeld, is het niet langer mogelijk om:

- [Openbare URL's voor Opgeslagen views inschakelen](https://support.catenda.com/en/articles/6423215-public-bookmarks-short-video).
- [Openbare URL's voor Documentverzamelingen inschakelen](https://support.catenda.com/en/articles/6344318-collections-page#h_c1e1a2a402).
- [Documentverzamelingen per e-mail delen](https://support.catenda.com/en/articles/6344318-collections-page#h_c1e1a2a402).

## 6. **Domeinen**

U kunt aanvragen dat een domein aan uw organisatie wordt toegevoegd. Als een domein bij uw organisatie is geregistreerd, wordt de optie "toevoegen van domein" weergegeven op de gebruikerspagina van uw organisatie in het [organisatiegebruikersvenster](http://hub.catenda.com/orgs). Hiermee kunt u gebruikers van uw organisatie aan uw projecten toevoegen zonder hen via [e-mailuitnodigingen](https://support.catenda.com/en/articles/4670319-how-can-i-invite-new-members-to-a-project) uit te nodigen. Als u een gebruiker van uw organisatie niet kunt vinden, is dit waarschijnlijk omdat ze nog geen Catenda-account hebben gemaakt en we ze niet in ons systeem hebben. Gebruikers van uw domein die nog geen account hebben, zullen op de [normale manier](https://support.catenda.com/en/articles/4670319-how-can-i-invite-new-members-to-a-project) moeten worden uitgenodigd, zodat zij het project kunnen verlaten en een account kunnen maken. Gebruikers van domeinen die niet zijn toegevoegd, moeten nog steeds met de reguliere [e-mailuitnodiging](https://support.catenda.com/en/articles/4670319-how-can-i-invite-new-members-to-a-project) worden uitgenodigd.
