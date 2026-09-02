# Ofte stilte spørsmål om egendefinerte felt

Begrensningene for hvordan egendefinerte felt kan brukes vil bli forklart her.

## 1. **Prosjekt \<=> Prosjekt**

Egendefinerte felt har en unik ID innenfor et prosjekt og kan derfor ikke utveksles fra ett prosjekt til et annet. Selv om egendefinerte felt har samme navn i begge prosjektene vil ID-en være unik og feltet vil ikke bli gjenkjent.

## 2. **Sakbrett \<=> Sakbrett**

Når et egendefinert felt er aktivert for to sakbrett innenfor samme prosjekt, kan saker flyttes mellom brettene og feltet vil bli opprettholdt.

## 3. **Eksportering av egendefinerte felt på saker**

Egendefinerte felt på saker kan eksporteres på følgende måter

### 3.1 **Sak PDF-eksport**

Egendefinerte feltverdier vises i PDF-eksporten av saker

### 3.2 **Sak BCF-eksport**

Egendefinerte felt er ikke ennå inkludert i den eksporterte BCF-en. Egendefinerte felt vil være en del av BCF 4-standarden når den blir utgitt. Etter utgivelsen vil vi og andre BCF-verktøy som følger standarden arbeide med å gjøre feltet tilgjengelig for utveksling.

### 3.3 **​Sak Excel-eksport**

En kolonne vil bli lagt til for hvert egendefinert felt i sakbrettet.

### 3.4 **API**

Egendefinerte felt i sakbrett [kan konfigureres](https://developers.catenda.com/topic-api/update-a-topic-board) via API-en. Egendefinerte felt på saker [kan konfigureres](https://developers.catenda.com/topic-api/update-topic) via API-en. Informasjon om egendefinerte felt på saker kan hentes via API-en.

### 3.5 **Rapporthandling**

Egendefinerte felt på saker er bare tilgjengelig for eksport med PDF-, BCF- eller Excel-eksporter og via API-en.

## 4. **Eksportering av egendefinerte felt på dokumenter**

Egendefinerte felt på dokumenter kan eksporteres på følgende måter

### 4.1 **Rapporthandling**

Når funksjonen for rapporter på etterspørsel har blitt forespurt aktivert for et prosjekt, blir rapporthandlingen gjort tilgjengelig. Hvis rapporten er konfigurert med navnet på det egendefinerte feltet, kan informasjon om egendefinerte felt for dokumenter valgt i dokumenttabellen eksporteres til en rapport og lagres i hvilket som helst av de tilgjengelige rapportformatene.

### 4.2 **API**

Egendefinerte felt på dokumenter er bare tilgjengelig for eksport med rapporthandlingen.

### 4.3 **Dokumentnedlasting**

Egendefinerte felt på dokumenter er bare tilgjengelig med rapporthandlingen. Når dokumenter lastes ned med nedlastingshandlingen i dokumenttabellen, lastes det opprinnelige dokumentet ned. Catenda endrer ikke dokumentet på noen måte, så egendefinerte felt legges heller ikke til som metadata.
