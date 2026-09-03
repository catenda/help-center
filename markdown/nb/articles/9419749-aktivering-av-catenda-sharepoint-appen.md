# Aktivering av Catenda SharePoint-appen

> **Merk:** Installfilen for programtillegget finner du i [denne artikkelen](https://intercom.help/bimsync-arena/en/articles/8396532-catenda-plugins-and-integrations).

Catenda SharePoint-programmet kan aktiveres for et SharePoint-miljø av en systemadministrator og deretter legges til på et område av en områdenavtaler. Med denne appen vil SharePoint-brukere kunne vise, administrere og samarbeide om dokumenter i Catenda sammen med andre medlemmer av byggprosjektet.

Hvis du vil aktivere appen for miljøet ditt, finner du oppføringen her: [Microsoft AppSource](https://appsource.microsoft.com/en-us/marketplace/apps?search=Catenda&page=1), som kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/01-intro.png)

Etter at du klikker på "Få det nå" blir du bedt om å logge inn på SharePoint-kontoen din hvis du ikke allerede er logget inn. Du blir deretter omdirigert til SharePoint Store-oppføringen. SharePoint Store finner du også ved å klikke på profilen din øverst til høyre i SharePoint og deretter klikke på Legg til en app

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/02-intro.png)

I SharePoint Store vil du også kunne søke i Catenda SharePoint-programmet:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/03-intro.png)

**https://\<Tenant>.sharepoint.com/sites/appcatalog/\_layouts/15/appStore.aspx/sharePointStore?entry=ClassicAppCatalog&sorting=7&search=catenda**

SharePoint Store-oppføringen kan se slik ut:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/04-intro.png)

**https://\<Tenant>.sharepoint.com/\_layouts/15/appStore.aspx/appDetail/WA200005981**

## 1. **Vanlige SharePoint-brukere**

Vanlige SharePoint-brukere vil kunne be om at Catenda SharePoint-appen aktiveres ved å klikke på knappen Legg til apper på området. Du kan se om forespørselen din ble godkjent på siden Mine forespørsler i SharePoint Store. Hvis du er administrator, vil du kunne godkjenne forespørselen fra appkatalogen

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/05-regular-sharepoint-users.png)

_https://\<Tenant>.sharepoint.com/sites/appcatalog/SitePages/Home.aspx_

## 2. **SharePoint-administratorer**

Som administrator i et SharePoint-miljø vil du kunne aktivere appen ved å klikke på Legg til apper på området. Her blir du bedt om å bekrefte datatilgang.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/06-sharepoint-administrators.png)

### 2.1 **Bekreft datatilgang**

Appen du er i ferd med å aktivere vil ha tilgang til data ved å bruke identiteten til personen som bruker den. Aktiver denne appen bare hvis du stoler på utvikleren eller utgiver. Appen trenger denne tillatelsen for å vite hvilke av brukerens filer som skal publiseres når de velger å publisere dem. Sluttpunktet er: [https://sharepoint.plugins.catenda.com/1.0.0.0/](https://sharepoint.plugins.catenda.com/1.0.0.0/)

### 2.2 **API-tilgang**

Hvis API-tilgang ikke hadde blitt aktivert tidligere, må den aktiveres for at programmet skal fungere.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/07-api-access.png)

Hvis du vil godkjenne API-tilgang, går du til siden for API-tilgang i administrasjonssenteret ditt https://\<Tenant>.sharepoint.com/\_layouts/15/online/AdminHome.aspx#/webApiPermissionManagement

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/08-api-access.png)

API-tilgang er nødvendig slik at SharePoint-administratorer må koble til Catenda-kontoen sin for å aktivere publisering av dokumenter. Brukere blir også bedt om å logge inn med Catenda-kontoen sin når de prøver å publisere noe til Catenda, siden hver bruker kan ha ulike tillatelser i Catenda.

Uten API-tilgang kan Catenda SharePoint-programmet aktiveres, hvoretter både listehandlingen og webdelen vil være synlig, men ikke brukbar, da ingen data kan utveksles uten å koble til Catenda-kontoen din. _Nødvendig tilgang:_ Global Administrator-rolle eller Application Administrator-rolle i Microsoft 365.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/09-api-access.png)

_Godkjenn tilgang_ Velg Catenda i listen over ventende forespørsler og klikk på godkjenn øverst. For at Catenda-programmet skal fungere, trenger det tillatelsen: tilgang

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/10-api-access.png)

_Fjern tilgang_ Velg Catenda på siden for API-tilgang og klikk på fjern øverst.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/11-api-access.png)

Klikk på Fjern i neste meny

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/12-api-access.png)

Selv om Catenda-programmet kan være aktivert, vil brukere ikke kunne koble til Catenda etter at denne tilgangen har blitt fjernet.

## 3. **Apptilgjengelighet**

### 3.1 **Aktiver bare denne appen**

Dette alternativet aktiverer appen for SharePoint-miljøet, som gjør at områdeeiere i miljøet ditt kan legge til appen på sin fra siden Mine apper. Appen gjør ingenting før den legges til på et område. Selv om dette alternativet er bra, kan det være forvirrende for brukere hvis du vil ha bedre kontroll over hvilke områder brukere kan publisere dokumenter til Catenda fra, siden noen områder har publiseringsalternativet mens andre ikke har det. For enda mer kontroll kan du aktivere [områdesamlingappkatalogen](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/site-collection-app-catalog), som lar deg velge hvilke apper områdeeier kan installere. Med dette alternativet vil appen heller ikke være aktivert som standard på nye områder, noe som betyr at det er mer arbeid å konfigurere et nytt område når det opprettes.

### 3.2 **Aktiver denne appen og legg den til på alle områder**

Med dette alternativet vil appen automatisk legges til på alle områder. Den eneste visuelle forskjellen brukeren vil se når appen legges til på området deres, er at de vil ha listekommandoen i listen og hamburgermeny når de velger et dokument. Webdeler og hele sider må legges til senere. Dette kan også gjøres fra siden Administrer apper senere.

### 3.3 **Legg til i team**

Med dette alternativet vil appen også legges til i Teams. Dette gjør det mulig for brukere å se Teams-fanen. Dette kan også gjøres fra siden Administrer apper senere.

## 4. **Administrer apper**

Etter at appen er aktivert, vil SharePoint-administratorer kunne se appen din i området Administrer apper. https://\<Tenant>.sharepoint.com/sites/appcatalog/AppCatalog/Forms/AllItems.aspx

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/13-manage-apps.png)

Etter at du har valgt appen, kan den legges til på ulike deler av SharePoint.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/14-manage-apps.png)

### 4.1 **Legg til på alle områder:**

Dette vil legge til appen på alle områder og alle nye områder som opprettes. Hvis appen er aktivert, vil områdeeiere også kunne legge til appen på et område enkeltvis. Hvis du ikke ønsker å fortsette med å legge til appen på nye områder, kan du stoppe med det ved å klikke på stopp å legge til på nye områder.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/15-add-to-all-sites.png)

Funksjonaliteten som appen gir, vil fortsette å være tilgjengelig på alle områder der den ble lagt til, og områdeeiere kan fortsatt legge til denne appen på områdene deres.

### 4.2 **Legg til i Teams:**

Dette aktiverer Teams-fanen for appen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kzzzd495/16-add-to-teams.png)

For at appen skal legges til i Teams, må den først legges til på alle områder.

## 5. **Videre lesning**

Se [her](https://support.catenda.com/en/articles/8396496-catenda-sharepoint-application) for informasjon om hvordan dette programmet fungerer etter at det er installert. Se [her](https://support.catenda.com/en/articles/9419678-catenda-sharepoint-faq) for mer informasjon om hvordan dette programmet kan være nyttig.
