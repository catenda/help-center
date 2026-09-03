# Feilsøking for dokumentforhåndsvisning

## 1. **1. Kan ikke koble til server**

Når et dokument åpnes, kan dokumentforhåndsvisningen være nedtonet med en sentrert melding som sier:

`Kan ikke koble til server`

Dette problemet kan også se ut som alvorlig platformlangsomhet eller lastelasting som aldri stopper, spesielt på siden **Samlinger** eller når du prøver å laste inn **Modelllisten** inne i 3D-viseren.

### 1.1 **1.1 Hvorfor dette skjer**

Det er en begrensning på det spesifikke internettnettverket eller VPN-forbindelsen som brukes. Sikkerhetsinnstillingene på nettverket tillater at hovednettstedet for Catenda lastes inn, men blokkerer eller avviser helt bakgrunnskoblingene som plattformen bruker til å sende og motta tungt prosjektdata og 3D-modeller. Fordi disse bakgrunnsdatastrømmene er kuttet av, kan systemet ikke laste inn informasjonen, noe som forårsaker at plattformen henger uendelig eller viser en tilkoblingsfeil.

### 1.2 **1.2 Feilsøkingstrinn**

Bekreft om nettverket forårsaker blokkeringen, prøv å laste plattformen eller dokumentforhåndsvisningen mens du er tilkoblet et annet nettverk, for eksempel et mobilt hotspot for mobil. Hvis siden og dataene lastes normalt der, blokkerer den primære nettverkskonfigurasjonen trafikken.

### 1.3 **1.3 Permanent løsning for nettverksadministratorer**

For å løse dette problemet permanent må nettverkskonfigurasjonen oppdateres til fullt ut å støtte Catendas bakgrunnstrafikk, inkludert alle underdomener og påkrevde porter. Klikk [her](https://support.catenda.com/en/articles/13927294-network-recommendation) for å lese mer om hvitelisekrav og portspesifikasjoner (inkludert obligatoriske Port 443 TCP/UDP-konfigurasjoner).

## 2. **2. Feil ved lasting av dokument (Les tidsavbrudd)**

Når et dokument åpnes, kan webviseren som viser dokumentforhåndsvisningen vise en melding som sier: **"Les tidsavbrudd"**.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/hq07qt4s/01-2-error-loading-document-read-timed-out.png)

`Les tidsavbrudd`

### 2.1 **2.1 Hvorfor dette skjer**

Sikkerhetsinnstillingene på nettverket som brukes tillater bare at hovedadressen for Catenda-nettstedet passerer. Nettverkets brannmur gjenkjenner ikke eller tillater ikke en jokertegning (som automatisk tillater alle adresser som slutter på `.catenda.com`), så den blokkerer den spesifikke, separate bakgrunnsadressen som håndterer dokumentforhåndsvisninger (`webviewer.catenda.com`). I stedet for å avvise tilkoblingen øyeblikkelig, ignorerer brannmuren forespørselen til nettleseren gir opp venting, noe som resulterer i en tidsavbruddfeil.

### 2.2 **2.2 Feilsøkingstrinn**

Bekreft om nettverkskonfigurasjonen forårsaker tidsavbruddet, prøv å laste dokumentforhåndsvisningen mens du er tilkoblet et annet nettverk, for eksempel et mobilt hotspot for mobil. Hvis forhåndsvisningen lastes normalt der, blokkerer den primære nettverksbrannmuren konfigurasjonen trafikken.

### 2.3 **2.3 Permanent løsning for nettverksadministratorer**

For å løse dette problemet permanent må nettverksbrannmuren konfigurasjonen oppdateres til eksplisitt å tillate den spesifikke adressen som brukes for dokumentforhåndsvisninger (`webviewer.catenda.com`). Klikk [her](https://netw) for å lese mer om hviteliseregler og portspesifikasjoner.
