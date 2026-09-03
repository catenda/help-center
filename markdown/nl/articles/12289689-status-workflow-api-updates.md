# Status Workflow - API-updates

> Introductie van de API-wijzigingen van de nieuwe Status Workflow-functie, waarbij we gedeelde en gepubliceerde status onderscheiden volgens ISO 19650. Voor klanten en integratiepartners die de Catenda API gebruiken.

We implementeren **Status Workflow**, een belangrijke update voor hoe Catenda document- en model-revisies beheert. Deze wijziging introduceert een onderscheid tussen werk- en officiële revisies die aanpassingen aan uw integratie kunnen vereisen.

## 1. Samenvatting

Catenda maakt onderscheid tussen:

- **"Gedeelde"** revisies (werk-/conceptversies)
- **"Gepubliceerde"** revisies (officiële/goedgekeurde versies)

**Onmiddellijke actie vereist indien:**

- Uw toepassing is geïntegreerd met Catenda Hub
- U geeft revisie-informatie aan gebruikers weer
- U maakt nieuwe revisies via de API
- U gebruikt CAD-tool-plugins

## 2. Wat verandert

### 2.1 Revisietypen

Eerder werden alle revisies impliciet als "officieel" beschouwd. Nu:

- **"Gedeelde"**: Samenwerkingsrevisies met beperkte zichtbaarheid
- **"Gepubliceerde"**: Officiële revisies voor bredere distributie

### 2.2 API-responswijzigingen

**Document API** bevat nieuwe velden voor bibliotheekitems:

```
{  "document": {    "revision": {      "extendedVersion": {        "major": 1,        "minor": null  // of 1,2,3 voor Gedeelde      },      "version": 5  // Legacy-nummering behouden    }  }}
```

**Models API**-wijzigingen zijn minimaal:

- Voegt filtermogelijkheid toe via scope-parameter (scope=published of scope=all)
- Stelt revisie-status of uitgebreide nummering NIET bloot
- Handhaaft machtigingen overgeërfd van onderliggende documenten

### 2.3 Standaardgedrag

**Belangrijk**: API's geven standaard **zowel** "Gedeelde" als "Gepubliceerde" revisies terug waar gebruikers toegang hebben. Dit handhaaft achterwaartse compatibiliteit maar verandert fundamenteel de aard van geretourneerde gegevens.

## 3. Wie wordt beïnvloed en hoe

### 3.1 Niet beïnvloed

- ✅ Standalone API-toepassingen zonder Catenda Hub-afhankelijkheid
- ✅ Toepassingen die revisies niet weergeven of beheren

### 3.2 Aanzienlijk beïnvloed - CAD-tool-plugins

⚠️ **Kritieke problemen:**

- Kan niet bepalen of "Gedeelde" of "Gepubliceerde" revisies worden gemaakt
- Kan nauwkeurige revisie-status aan gebruikers niet weergeven
- Kan ander nummering dan Hub weergeven (opeenvolgend vs. X.Y-indeling)
- Gebruikers begrijpen revisiecontext zonder statusvisibiliteit niet

**Vereiste acties voor plug-in-ontwikkelaars:**

1. Evalueer of u revisie-informatie weergeeft
1. Overweeg richtlijnen voor gebruikers over revisietypen toe te voegen
1. Plan voor mogelijke gebruikersverwarring over nummerings discrepanties

### 3.3 Ook beïnvloed

⚠️ Toepassingen die:

- Revisie-lijsten aan gebruikers weergeven
- Nieuwe revisies via API maken
- Afhankelijk zijn van alle revisies die "officieel" zijn
- Catenda Site-integratie gebruiken

## 4. Technische implementatiegids

### 4.1 Revisies filteren

Gebruik de nieuwe scope-parameter om te bepalen welke revisies worden geretourneerd:

```
# Document API
GET /documents?scope=published     # Alleen gepubliceerd
GET /documents?scope=shared        # Alleen gedeeld (vereist toestemming)
GET /documents                     # Alles (standaard)
# Models API
GET /models/revisions?scope=published  # Alleen gepubliceerd
GET /models/revisions                  # Alles (standaard)
```

### 4.2 Machtigingswijzigingen

Nieuwe ACL-rechten beïnvloeden uw bewerkingen:

- **"Gedeelde" revisies weergeven**: Vereist specifieke toestemming
- **"Gepubliceerde" revisies maken**: Alleen mogelijk via Catenda Hub-interface
- **API-revisie maken**: Maakt standaard "Gedeelde" revisies

### 4.3 Wat u niet via API kunt doen

- ❌ "Gepubliceerde" revisies maken (alleen Hub)
- ❌ Revisie-status in Models API openen
- ❌ Uitgebreide nummering (X.Y) in Models API zien
- ❌ Model-naar-document-relaties bepalen

## 5. Migratieoverwegingen

**Bestaande projecten:**

- Alle huidige revisies worden bij migratie "Gepubliceerd"
- Versienummers worden grote revisienummers (bijv. v3 → 3)
- Geen actie vereist voor historische gegevens

**Nieuw gedrag:**

- Nieuwe revisies die via API zijn gemaakt = standaard "Gedeeld"
- Publiceren vereist handmatige actie in Hub

## 6. Kritieke beslissingen voor uw implementatie

**Vraag 1**: Hebt u alleen officiële revisies nodig?

- **Ja** → Implementeer `scope=published` filteren
- **Nee** → Bereid u voor op het omgaan met gemengde revisietypen

**Vraag 2**: Geeft u revisie-informatie weer?

- **Ja** → Plan voor nummerings discrepantie (vooral voor Models API-gebruikers)
- **Nee** → Minimale impact verwacht

**Vraag 3**: Maken gebruikers revisies via uw app?

- **Ja** → Informeer gebruikers dat ze "Gedeelde" revisies maken
- **Nee** → Geen actie vereist

## 7. Bekende beperkingen en workarounds

**Voor Models API-gebruikers:**

- **Beperking**: Kan revisie-status of uitgebreide nummering niet openen
- **Workaround**: Gebruik filteren om alleen gewenste revisietypen op te halen
- **Gebruikersimpact**: Mogelijke verwarring over revisie-nummerings verschillen

**Voor Collection API-gebruikers:**

- Momenteel kunnen alleen "Gepubliceerde" revisies aan collecties worden toegevoegd
- Dit kan veranderen op basis van klantenFeedback

## 8. Ondersteuningsbronnen

**Documentatie-updates beschikbaar:**

- [Bijgewerkte API-referentie] - Bevat nieuwe `scope`-parameter

## 9. Veelgestelde vragen

**V: Zal mijn integratie verbreken?** A: Geen brekende wijzigingen op API-niveau, maar de gebruikerservaring kan aanzienlijk veranderen, vooral voor CAD-plugins.

**V: Waarom kan ik revisie-status in Models API niet zien?** A: Om achterwaartse compatibiliteit te behouden, stelt de Models API Status Workflow-functies minimaal bloot. Gebruik filteren om geretourneerde revisies te bepalen.

**V: Hoe weten gebruikers wat voor type revisie ze maken?** A: Via API zijn alle nieuwe revisies "Gedeeld." Gebruikers moeten Catenda Hub gebruiken om "Gepubliceerde" revisies te maken.

**V: Wat als we meer tijd nodig hebben om ons aan te passen?** A: Neem onmiddellijk contact met ons op. Status Workflow wordt geleidelijk ingeschakeld en we kunnen timelineopties voor uw organisatie bespreken.
