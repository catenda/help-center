# Microsoft Teams-varsel

> Bli oppdatert uten å bytte faner. Koble Catenda Hub til Microsoft Teams for å motta sanntidsvarsel direkte i dine foretrukne kanaler.

Motta sanntidsvarsel fra en Catenda-konto direkte i en Microsoft Teams-kanal ved å konfigurere en Microsoft Teams-arbeidsflyt i Catenda-varselinnstillingene. _Nødvendig tilgang:_ En **Microsoft Teams**-konto med tillatelser for kanaloppretting og Microsoft Teams-arbeidsflytstyrring.

Fanen for Microsoft Teams-varsel finnes mot toppen av [siden for kontovarselinnstillinger](https://support.catenda.com/en/articles/8272435-account-notification-settings) som er en underside til [siden for kontovarslinger](https://support.catenda.com/en/articles/7439223-account-notifications-page):

![Catenda Hub Varsel-innstillinger Microsoft Teams-varsel Prosjekter med egne Teams-innstillinger](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/01-intro.png)

Slik kan Catenda-varsel se ut i Microsoft Teams etter at en Microsoft Teams-arbeitsflyt er konfigurert.

![Microsoft Teams-kanal Innlegg Klart til vurdering opprettet en ny sak en ny revision ble importert i model](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/02-intro.png)

---

### Trinn 1: Forbered en dedikert kanal

Brukere kan organisere prosjektoppdateringene sine ved å opprette et spesifikt område for Catenda-varsel. 1\. I **Microsoft Teams**, velg **Teams**- eller **Chat**-fanen. 2\. Bruk et eksisterende team (hopp over dette trinnet) eller **opprett et team**.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/03-step-1-prepare-a-dedicated-channel.png)

Skriv inn et navn og opprett teamet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/04-step-1-prepare-a-dedicated-channel.png)

Når et team opprettes, legges en kanal kalt «generell» automatisk til. 3\. Bruk en eksisterende kanal (hopp over dette trinnet) eller legg til en kanal. Høyreklikk på et team og velg Legg til kanal i handlingsmenyen, eller klikk på teamet og klikk på **Legg til kanal** øverst til høyre. _Nødvendig tilgang:_ Eier eller medlem av team.

![Microsoft Teams Catenda-integrasjon Chat-kanaler Legg til kanal Medlemmer Analyse Apper Koder Skjul alle kanaler Legg til medlem Administrer team Administrer koder Kopier lenke Forlat team](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/05-step-1-prepare-a-dedicated-channel.png)

> **Merk:** Med gjest- eller ekstern tilgang kan ikke kanaler opprettes. I dette tilfellet, vennligst be en kanaladministrator om å gi deg en URL for varsler som skal sendes til en kanal.

Etter at du klikker på Opprett kanal, vises dialogboksen Opprett en kanal:

![Opprett en kanal Kanalnavn Bokstaver, tall og mellomrom er tillatt Beskrivelse Velg kanaltype Standard Privat Tråder Innlegg](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/06-step-1-prepare-a-dedicated-channel.png)

**4. Gi kanalen et navn**: Bruk noe klart som "Catenda-varsel" eller "Prosjekt-A-Varsel".

**5. Velg personvern**: Catenda-varsel kan leveres til både standard- og private kanaler.

- Velg **Standard** hvis du vil at hele teamet skal se oppdateringene.
- Velg **Privat** hvis varslene kun er for deg eller en spesifikk gruppe.

6\. Klikk **Opprett**.

---

### Trinn 2: Generer Teams-webhook-URL-en din

Tidligere ble Catenda Teams-varsel konfigurert via en Webhook Connector-applikasjon som ble konfigurert for kanalen. Webhook Connector-applikasjonen har siden blitt avviklet. Den nåværende måten å opprette en webhook-URL på er ved å opprette en Microsoft Teams-arbeidsflyt.

Følg disse trinnene for å opprette en ny Microsoft Teams **Workflow** webhook. 1\. Åpne **Microsoft Teams** 2\. Hold markøren over ønsket team og klikk på de tre prikkene, eller klikk på de tre prikkene øverst til høyre etter at du har åpnet kanalen. 3\. Velg Microsoft Teams **Workflows** fra handlingsmenyen

<img alt="Microsoft Teams-kanal handlingsmeny, arbeidsflyter uthevet." src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-f533eea19d48.png" width="290"/>  \<---> <img alt="Handlingsmeny i Microsoft Teams-kanal, arbeidsflyter uthevet." src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-1a6a43fe9eec.png" width="290"/>

4\. Søk etter **"Send webhook-varslinger til en kanal"** og velg den.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/07-step-2-generate-your-teams-webhook-url.png)

5\. Følg oppsettrinnene for å velge ditt team og kanal. **6. Kopier URL-en**: Når Microsoft Teams-arbeitsflyten er opprettet, kopier den genererte webhook-URL-en til utklippstavlen din ved å klikke på Kopier webhook-lenke øverst.

> **Merk:** 💡**Tips**: Behold denne URL-en privat. Hvem som helst med denne lenken kan sende meldinger til Teams-kanalen din.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/08-step-2-generate-your-teams-webhook-url.png)

---

### Trinn 3: Koble til Catenda Hub

Følg disse trinnene for å konfigurere webhook-lenken i Catenda. På denne måten vet Catenda hvor prosjektvarslene skal sendes.

1. Logg inn på **Catenda Hub**.
1. Naviger til **Varsel>Innstillinger** (på konto- eller prosjektnivå).
1. Velg "Microsoft Teams"-fanen og scroll helt ned.
1. Lim inn den kopierte URL-en i feltet **Webhook URL**.
1. Klikk **Lagre**.

    <div class="intercom-container intercom-align-center"><img height="320" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-a60f9c2dbac8.png" style="height: auto;" width="500"/></div>

1. **Aktiver varsel**: Kontroller at veksleknappen øverst på siden er satt til **På**.

    <div class="intercom-container intercom-align-center"><img height="159" src="https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/inline-a3e9aa9365d2.png" style="height: auto;" width="500"/></div>

---

### Trinn 4: Tilpass varslene dine

Skreddersy informasjonen du mottar for å unngå varslettmøtting. 1\. I samme **Varselinnstillinger**-meny, scroll gjennom listen over varseltyper. **2. Merk av i boksene** for de spesifikke oppdateringene du ønsker å motta i Teams-kanalen din. Slik kan Microsoft Teams-varselmenyen se ut:

![Velg hvilke varsel du ønsker å motta Catenda Hub E-post Microsoft Teams-varsel Saker Dokumenter Gjennomganger Samlinger Modeller Brukere En ny sak er opprettet En sak er tildelt til meg En sak nevner meg eller Teams mitt Ny kommentar i en sak tildelt meg nevnt av meg fulgt av meg Status endret i en sak Type endret i saker Jeg er angitt som utgiver i en gjennomgangsforespørsel Et team jeg er medlem av er angitt som utgiver i en gjennomgangsforespørsel En gjennomgangsforespørsel er lukket Et medlem av innsenderlaget En ny gjennomgangsforespørsel er blitt sendt inn Et dokument er kassert En gjennomgangsforespørsel er lukket En ny gjennomgangsforespørsel er blitt sendt inn En ny gjennomgangsforespørsel er tildelt teamet mitt En ny gjennomgangsforespørsel er klar til vurdering av teamet mitt Alle vurderinger er sendt inn av teamet mitt Et dokument er kassert En gjennomgangsforespørsel er lukket Som medlem av vurderingsteamet for den endelige gjennomgangen En ny gjennomgangsforespørsel er blitt sendt inn En ny gjennomgangsforespørsel er tildelt teamet mitt En ny gjennomgangsforespørsel er klar til vurdering av teamet mitt Alle vurderinger er sendt inn av teamet mitt Alle vurderinger er sendt inn av teamet mitt Et vurderingstrinn er fullført Et dokument er kassert En gjennomgangsforespørsel er lukket En ny model er opprettet En ny revision er importert.](https://raw.githubusercontent.com/catenda/help-center/main/images/cqcafpvn/09-step-4-customize-your-alerts.png)

Nedtonede varselsbokser er deaktivert for Microsoft Teams og er bare tilgjengelige for andre varselmethoder. Varselsbokser for gjennomganger blir tilgjengelige hvis Delte revisjoner er aktivert i [dokumentinnstillinger](https://support.catenda.com/en/articles/7831371-document-settings-page) for et prosjekt.

---

### Trinn 5: Verifisering

Kontroller at et varsel sendes til kontoen din som også sendes til Microsoft Teams.

1\. Utfør en handling i Catenda Hub.

> **Advarsel:** ⚠️ **Merk:** Ikke alle varslinger er tilgjengelige for sending til Microsoft Teams, og Microsoft Teams-varslinger sendes vanligvis ikke for handlinger brukere utfører selv. Last opp en modell eller be en lagkamerat om å opprette en sak eller nevne deg i en beskrivelse eller kommentar for å verifisere lenken.

2\. Sjekk **Microsoft Teams-kanalen** din. 3\. En melding skal vises umiddelbar via Microsoft Teams **Workflow**-boten.
