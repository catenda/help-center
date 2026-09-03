# Jeg har en stor IFC-fil. Skal jeg bruke Solibri Optimizer før jeg laster opp filene til Catenda Hub?

Svaret er nei. Hvis filen din blir stor, er det bedre å bare [komprimere filene før opplasting](https://support.bimsync.com/hc/en-us/articles/360009995879) i stedet. Solibri Optimizer kan i noen tilfeller ødelegge filen slik at den ikke passerer gjennom de ulike importtrinnene i Catenda Hub. En optimalisert fil blir ikke raskere å bla gjennom i Catenda Hub fordi vi lagrer informasjon i optimaliserte formater uavhengig av tilstanden på filen ved import.

Hvis du har en fil som mislykkes ved opplasting, kontroller filhodet for spor av Solibri Optimizer (åpne i notepad eller lignende og se på de første 10 linjene i filhodet). Hvis den mislykkede filen er optimalisert, kan du prøve med originalfilen i stedet.

![mceclip0.png](https://raw.githubusercontent.com/catenda/help-center/main/images/p8sgh6tt/01-intro.png)

(denne filen har vært gjennom Solibri Optimizer)
