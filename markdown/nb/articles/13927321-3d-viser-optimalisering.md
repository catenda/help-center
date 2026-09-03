# 3D Viser-optimalisering

Selv om Catenda Hub er godt optimalisert og kan kjøre de fleste modeller, kan noen brukere ønske å sette seg selv opp for suksess så godt som mulig.

Denne artikkelen inneholder informasjon om følgende saker:

Her er noen strategier som kan brukes til å optimalisere arbeidsflyten din i Catenda Hub

## 1. **Mange objekter**

Selvfølgelig vil innlasting av færre modeller bety færre objekter og derfor bedre ytelse. Aktivering av [inkrementell gjengivelse](https://intercom.help/bimsync-arena/en/articles/5784718-3d-viewer-settings#:~:text=Incremental%20rendering%3A) fremskynder rotasjon rundt modeller med mye geometri siden ikke alle objekter må lastes inn under rotasjon. Som et siste trinn kan du lage en [spørring](https://intercom.help/bimsync-arena/en/articles/4854514-queries) om delen du arbeider med. Vanligvis når du avsnitter del av modellen, er objektene fortsatt i minnet og bare skjult. Med en spørring fjernes disse objektene helt, og det vil derfor være lettere å arbeide med modellen. Husk at du ikke vil kunne bruke egenskapsbiblioteker med spørringer fordi ikke alle objekter er lastet inn.

## 2. **Punktskyer**

Hvis du bruker [fast punktstørrelse](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=Adaptive%20(default)%2C%20or-,Fixed%20size,-.%20The%20slider%20below), kan du støte på lavt fps når mange punkter har blitt lastet inn. Du kan også oppleve at punkter tar lengre tid å laste når minnebudsjettet på systemet ditt er nådd. Punkter nærmest kameraet lastes først, så hvis du vil laste punkter på et bestemt sted, er det bedre å navigere til den posisjonen og deretter aktivere punktskyen slik at den begynner å laste punkter der først. For å unngå å nå minnegrensen og få lavere fps, kan du senke [punktbudsjettet](https://intercom.help/bimsync-arena/en/articles/5606625-point-clouds-in-bimsync#:~:text=with%20your%20PC.-,Point%20Budget%3A,-Using%20the%20viewer) slik at færre punkter lastes inn.

## 3. **Nettleserzoomskala**

Kontroller at zoomskalaen i nettleseren din er satt riktig, da en stor zoomskala kan gjøre noen menyer så store at andre blir skjult. Mens grafikk definert av bredde og høyde kan skaleres med nettleserzomen, kan grafikk som er definert av piksler bli mer pikslet når zoomskalaen økes. Liten zoomskala kan føre til at grafikk blir så liten at den blir usynlig, og nøyaktig visning av nedskalerte ressurser kan være mer krevende for enheten.
