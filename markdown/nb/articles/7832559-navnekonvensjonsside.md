# Navnekonvensjonsside

Administratorer vil kunne finne siden Navnekonvensjoner som en underside til [prosjektinnstillinger](https://support.catenda.com/en/articles/4670273-project-settings-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/01-intro.png)

## 1. **Lokal filnavngivning**

Med navnekonvensjoner kan du begrense hvilke filer som lastes opp til en mappe avhengig av navnet på den opprinnelige filen. Dette er veldig nyttig hvis du allerede har et sett med regler for navngivning av dine lokale filer. Du burde ikke trenge å gi filene dine nytt navn slik at du kan laste dem opp til Catenda Hub. Hvis du ikke har regler for navngivning av dine lokale filer, anbefales ikke navnekonvensjonen.

## 2. **Dokumenter, revisjoner og originale filer**

Før du starter med dette, er det viktig å forstå forskjellen mellom et Catenda Hub-**dokument** og en **fil**. Du kan tenke på et dokument (og dokumentrevisjoner) i Catenda Hub som _beholdere for filer_. Du kan laste opp en fil til denne beholderen, og hvis du er administrator, kan du endre navnet. Filnavn er ofte veldig forskjellige fra hverandre selv om de er samme versjon av tegningen eller arket du ønsker å laste opp. Navnekonvensjonen lar deg laste opp lignende filer til det samme dokumentet basert på et sett med regler i filnavnet.

## 3. **Ny navnekonvensjon**

I øvre høyre hjørne av siden vil du se knappen Ny navnekonvensjon.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/02-new-naming-convention.png)

Slik ser en ny navnekonvensjon ut.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/03-new-naming-convention.png)

### 3.1 **Konvensjonsinformasjon**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/04-convention-information.png)

_Navn_ Konvensjonsnavnet slik det vil vises når du bruker det i dokumentinnstillinger

_Beskrivelse_ Beskrivelsen av konvensjonen slik den vil vises i dokumentinnstillinger

_Skilletegn_ Tegnet som skiller hver blokk unntatt filutvidelsesblokken.

### 3.2 **Forhåndsvisninger**

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/05-previews.png)

Forhåndsvisninger viser mønsteret som konvensjonene følger både i ditt lokale filsystem og i Catenda Hub-dokumentstrukturen. Disse kan være forskjellige, og en kan kartlegges til den andre som du vil se

_Dokumentnavn_ Måten dokumentet i Catenda Hub vil se ut når filen er lastet opp

_Forventet filnavn_ Hvordan filer som har tillatelse til å lastes opp, skal se ut

### 3.3 **Forhåndsvisningstyper**

Når du holder musepekeren over de ulike forhåndsvisningstypene, vil du se en detaljert forklaring av hva hver forhåndsvisning betyr. _Tekst - Variabel lengde:_ {X} _Tekst - Fast lengde:_ XXXX _Egendefinert felt:_ {Custom field name} _Skilletegn:_ Når du har tre eller flere blokker, vil du se skilletegnet du har angitt

### 3.4 **Blokker**

Navnekonvensjonen består av en serie blokker. Hver blokk representerer en del av filnavnet/dokumentnavnet. Klikk på Legg til blokk for å legge til en ny blokk.

![Legg til blokk](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/06-blocks.png)

En konvensjon har alltid minst to blokker: 1\. Navne på filen/dokumentet. 2\. Navne på filutvidelsen/dokumentutvidelsen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/07-blocks.png)

_Navn_ Navnet på blokken i navnekonvensjonsoppsettet slik at du kan skille dem fra hverandre

_Beskrivelse_ Her kan du skrive en beskrivelse av hva du forventer at denne blokken skal gjøre

_Dokumentidentifikator_ Hvis du forventer en del av filnavnet som du ikke vil se i Catenda Hub, kan du slå av dokumentidentifikatoren. Denne delen av filnavnet vil fortsatt brukes for å godta filer, men vil ikke være synlig i det resulterende Catenda Hub-dokumentet.

_Av_ Når dokumentidentifikatoren er slått på, identifiserer denne blokken dokumentnavnet

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/08-blocks.png)

_Av_ Når dokumentidentifikatoren er slått av, identifiserer denne blokken navnet på den lokale filen.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/09-blocks.png)

_Deaktivert_ Dokumentidentifikatoren for utvidelsesblokken er alltid av fordi hver fil har en utvidelse.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/10-blocks.png)

_Kilde_ Hva kvalifiserer identifikasjonen av filnavnet/dokumentnavnet? _Standard:_ Tekst - Denne blokken kan inneholde et hvilket som helst tegn _Egendefinert felt:_ - Begrens typene tegn som blokken din godtar med egendefinerte felt

_Lengde_ Hvor mange tegn det kan være i denne blokken. Hvis dette feltet er tomt, vil blokken ha variabel lengde.

### 3.5 **Innsending av en konvensjon**

![Avbryt Send navnkonvensjon](https://raw.githubusercontent.com/catenda/help-center/main/images/kj97gd0a/11-br-submitting-a-convention.png)

Etter innsending av en navnekonvensjon kan den [aktiveres per mappe](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90) i [dokumentinnstillinger](https://support.catenda.com/en/articles/7831371-document-settings).
