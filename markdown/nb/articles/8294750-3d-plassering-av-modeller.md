# 3D-plassering av modeller

## 1. **Eksporter med samme koordinater**

I forfattingsplattformer kan du eksportere med forskjellige koordinater. Alle koordinater fungerer fint med Catenda Hub. Det anbefales at alle i prosjektet bruker det samme koordinatsystemet for å sikre at objekter ikke ender opp langt fra hverandre og at brukere ikke lurer på hvorfor de ser noen objekter mens andre er skjult mens de egentlig bare er veldig, veldig langt unna.

## 2. **Objekter langt fra origo**

Sammenlignet med andre forfattingsplattformer har Catenda Hub ikke problemer med presisjon når objekter er langt fra 0. Modellplasseringen angitt i IFC-filen brukes til å bestemme hvor i 3D modellen eksisterer. Scenen (størrelsen på området som lastes inn i 3D-viseren) er bare så stor som objektene den inneholder og trenger ikke å inkludere origo (0,0,0). Dette gjør at du enkelt kan zoome inn på objekter uten å måtte beregne hvor langt unna de er i forhold til origo.

## 3. **Objekter langt fra hverandre**

Hvis du har objekter som er mer enn 10000 KM fra hverandre, kan du støte på problemer fordi scenen blir veldig stor. Hvis du lager et horisontalt skjæreplan, vil det klippe hele scenen og vil bli følsom når du flytter det. Hvis en model derfor ved et uhell blir importert med feil koordinater og ender opp veldig langt unna, kan du ønske å transformere den. Modellene fungerer fortsatt bra hver for seg, men sammen med andre modeller som er veldig langt unna kan du støte på problemer.

## 4. **Transformering av modellplassering**

Det er mulig å transformere 3D-plasseringen av en model på modelloversiktssiden hvis du har den lastet inn i 3D. Dette lar deg flytte modellen i 3D etter at den er importert til Catenda Hub. Denne flyttingen er bare visuell i Catenda Hub. Hvis IFC-filen lastes ned, vil den være tilbake på sin opprinnelige plassering. Denne metoden anbefales bare for midlertidig transformering av modellen mens du venter på en IFC-fil med korrekt plassering. Dette er fordi noen funksjoner ikke fungerer ordentlig med transformerte modeller, som 2D-viserseksjoner, spørringer og øyeblikksbilder. Målinger er ikke påvirket og vil være nøyaktige hvis modellen flyttes til riktig sted. Du finner mer informasjon om hvordan du gjør dette [her](https://support.catenda.com/en/articles/4670270-model-overview-page#h_c10dbce6c8)
