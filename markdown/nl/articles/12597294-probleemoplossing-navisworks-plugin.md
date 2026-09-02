# Probleemoplossing Navisworks-plugin

Fouten die kunnen optreden met de Navisworks-plugin en hoe deze op te lossen worden in dit artikel uitgelegd.

## 1. **AddTopic**

Wanneer het menu Onderwerpen wordt geopend zonder aangemeld te zijn, verschijnt de volgende fout.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/01-addtopic.png)

Ga naar het instellingenmenu en klik rechtsboven op aanmelden om dit op te lossen.

## 2. **PopulateIssueBoards**

Wanneer er geen onderwerpen zijn in een van de projecten waarvan een lid deel uitmaakt, verschijnt de volgende fout.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/02-populateissueboards.png)

Nadat een onderwerp in het project is aangemaakt, verschijnt de fout niet meer.

## 3. **De plugin opnieuw instellen**

Na het bijwerken van Navisworks kunnen er problemen optreden met de installatie van de Catenda Navisworks-plugin. Volg de volgende stappen om de plugin opnieuw in te stellen:

Wijzig eerst in de Windows-mapopties om verborgen bestanden en mappen weer te geven

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/03-resetting-the-plugin.jpg)

Vervolgens vinden we de Navisworks-toepassingsinstellingen uit de map C:\\Users\\_username\\_AppData\\Local. Ze kunnen zich in de mappen Autodesk\_Inc en/of Autodesk\_Ltd bevinden

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/04-resetting-the-plugin.jpg)

Navisworks-instellingen bevinden zich in mappen die beginnen met "Roamer.exe\_Url…"

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/05-resetting-the-plugin.jpg)

We kunnen deze instellingen opnieuw instellen door de map Roamer.exe\_Url… inclusief submappen en bestanden te verwijderen

Om te controleren welke plugins de instellingen aanbelangen: Het volgende niveau geeft de versie van Navisworks aan, bijvoorbeeld 19 is voor Navisworks 2022-versie, 18 voor 2021-versie enzovoort

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/06-resetting-the-plugin.jpg)

In die map kunnen we het daadwerkelijke configuratiebestand _user.config_ vinden dat met een teksteditor kan worden geopend. Opmerking: Het is beter om het hele pad van het niveau Roamer.exe\_Url te verwijderen dan te proberen afzonderlijke plugins te verwijderen met behulp van de teksteditor.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/wed29m2h/07-resetting-the-plugin.jpg)
