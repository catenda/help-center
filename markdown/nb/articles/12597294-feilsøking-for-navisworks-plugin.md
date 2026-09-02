# Feilsøking for Navisworks-plugin

Feil som kan oppstå med Navisworks-plugin og hvordan du løser dem er forklart i denne artikkelen.

## 1. **AddTopic**

Når sakmenyen åpnes uten å være pålogget vises følgende feil.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/01-addtopic.png)

For å løse dette, gå til innstillingsmenyen og klikk på pålogging øverst til høyre.

## 2. **PopulateIssueBoards**

Når det ikke er noen saker i et av prosjektene som et medlem er del av, vises følgende feil.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/02-populateissueboards.png)

Når en sak er opprettet i prosjektet, vises ikke feilen lenger.

## 3. **Tilbakestille plugin**

Etter oppdatering av Navisworks kan det oppstå problemer med installasjonen av Catenda navisworks-plugin. For å tilbakestille plugin, følg disse trinnene:

Endre først i Windows mappeinnstillinger for å vise skjulte filer og mapper

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/03-resetting-the-plugin.jpg)

Deretter finner vi Navisworks-programinnstillinger fra C:\\Brukere\\_brukernavn\_AppData\\Local-mappen. De kan være under mappene Autodesk\_Inc eller/og Autodesk\_Ltd

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/04-resetting-the-plugin.jpg)

Navisworks-innstillinger er plassert i mapper som begynner med "Roamer.exe\_Url…"

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/05-resetting-the-plugin.jpg)

Vi kan tilbakestille disse innstillingene ved å slette Roamer.exe\_Url…-mappen inkludert undermapper og filer

For å sjekke hvilke plugin-innstillinger som tilhører: Neste nivå indikerer versjonen av Navisworks f.eks. 19 er for Navisworks 2022-versjon, 18 for 2021-versjon og så videre

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/06-resetting-the-plugin.jpg)

Under den mappen finner vi den faktiske konfigurasjonfilen _user.config_ som kan åpnes med tekstredigering. Merk deg! Det er bedre å slette hele stien fra Roamer.exe\_Url-nivået enn å prøve å fjerne individuelle plugin ved bruk av tekstredigering.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/07-resetting-the-plugin.jpg)
