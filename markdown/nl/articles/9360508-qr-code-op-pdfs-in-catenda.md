# QR-Code op PDFs in Catenda

In Catenda Hub kunnen QR-codes op mapniveau worden geconfigureerd. Met deze functie kunnen gebruikers direct controleren of ze de meest recente revisie van een document in handen hebben. Door de QR-code op de fysieke of digitale PDF te scannen, ziet de gebruiker onmiddellijk of het document nog actueel is.

Dit artikel behandelt de volgende onderwerpen:

1. **Plaatsen:** De placeholder in uw document verwerken.
1. **Configureren:** Instellingen in Catenda Hub aanpassen.
1. **Publiceren:** Hoe en wanneer de code wordt gegenereerd (Update: Status-workflows).
1. **Controle:** Het scannen en verifiëren van revisies.

---

### De QR-Code Placeholder Plaatsen

Voordat u een document uploadt naar Catenda Hub, moet er een specifieke 'placeholder' (plaatsvervanger/marker) op het document staan. Catenda herkent deze afbeelding en vervangt deze tijdens het publicatieproces door een unieke, actieve QR-code.

Het maakt niet uit of je placeholder in Catenda of in een ander PDF programma plaatst. Als je deze maar opslaat in het document.

In catenda kan dat door 'save-as' en deze opnieuw te uploaden.

![](https://downloads.intercomcdn.com/i/o/areracg3/2352188601/e843eb06fb99ef49d782ed60aaa9/image.png?expires=1781092800&signature=71bb34f59d455b90fa9204f38458bd88705187398575b6e9da3f566b4aa147e9&req=diMiFMh2lYdfWPMW3nq%2BgegloklRe%2BXnbOFMc3n0lnvOnRUhhHKrkYa6Aw2K%0AM3MsbnLVN0RPR76Zu0I68IPw5Lg%3D%0A)

### Technische Vereisten

- **Afmetingen:** De placeholder moet minimaal **2cm bij 2cm** groot zijn.
- **Bestandstype:** De placeholder moet als een **afbeelding** worden toegevoegd, niet als een vector of annotatie.
- **Byte-vereiste:** De exacte byte-volgorde van de zwart-wit pixels in de originele Catenda-placeholder moet behouden blijven.
- **Positie:** Het maakt niet uit of hij in de annotatielaag zit of in de geprinte laag, let wel op dat bij het integreren in stempels soms het volledig stempel wordt vervangen.

### PDF-Optimalisatie & DPI

Sommige software comprimeert afbeeldingen bij het opslaan, wat de herkenning kan verstoren. Gebruik de volgende instellingen voor het beste resultaat:

- **Pixeldichtheid:** 144 DPI.
- **Compressie:** ZIP-compressie.
- **Geheel:** De afbeelding moet één geheel blijven. Sommige optimalisaties splitsen afbeeldingen op in segmenten; zorg dat dit niet gebeurt.

> **Note:** Gebruik altijd het originele marker bestand! **Download link:** [[Download hier de officiële QR-Code Placeholder](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)]

### Configureren in Catenda Hub

De toewijzing van QR-codes gebeurt per map. Dit geeft projectbeheerders de vrijheid om de functie alleen te activeren waar dit relevant is (bijv. voor definitieve bouwtekeningen).

**Toegang vereist:** Projectbeheerder

### Stappen voor configuratie:

1. Ga naar de **Documentinstellingen**.
1. Navigeer naar **Mappenconfiguratie**.
1. Klik op het **plus-icoon (+)** naast de gewenste map.
1. Zet de optie **Wijs QR-code toe** op "Ja".

**Let op: Zodra een hoofdmap is geactiveerd, erven alle submappen deze instelling automatisch over. U kunt QR-codes alleen handmatig toewijzen aan een map als de bovenliggende map nog niet is geactiveerd.**

![](https://downloads.intercomcdn.com/i/o/areracg3/2352188600/a638ede9483e26523af4d5b42fdd/image.png?expires=1781092800&signature=b8d83e82b286518729bda273c337c8d09d5d4893cc27e5c8a434fde307ae38b9&req=diMiFMh2lYdfWfMW3nq%2BgchEjV%2FU8I%2BpDClBd%2FtG6E3lHu2jP9oA2G9DXIc5%0ADjDjN6cNFChKr9gyjbsuFBxiuFs%3D%0A)

### Publiceren en Genereren (Update)

Het proces van het scannen van de placeholder en het genereren van de werkelijke QR-code vindt plaats tijdens het uploaden en publiceren.

### Status-workflow: Gedeelde vs. Gepubliceerde documenten

Dit is een cruciaal onderscheid bij het gebruik van revisiestatussen:

- **Concepten & Gedeelde revisies:** Wanneer u een revisie uploadt als 'gedeeld' (_shared_), wordt de QR-code nog **niet** gegenereerd. U ziet dan nog steeds de originele placeholder.
- **Publicatie:** De placeholder wordt pas definitief vervangen door de gegenereerde QR-code op het moment dat de revisie wordt **gepubliceerd**.
- **Zonder workflow:** Als uw project geen status-workflow gebruikt, worden documenten direct bij upload gepubliceerd en wordt de code direct gegenereerd.

### Controleren van de verwerking

In de **geschiedenis** van het document (rechtermenu) kunt u zien of het proces succesvol is afgerond. Als het genereren mislukt, controleer dan of de afbeelding kleiner is dan 2x2cm of dat deze per ongeluk op de annotatielaag staat.

![](https://downloads.intercomcdn.com/i/o/areracg3/2352188603/0ca068e54eb5ae1461ea6933c2e9/image.png?expires=1781092800&signature=30ff05372b42d41306411037a80ce40b1614455cddb1f67a30ba2fb7880787d1&req=diMiFMh2lYdfWvMW3nq%2Bgf2zEBxMvW1WqknLF5I1fUesPiNvdZPtUlNs0s%2Fa%0AeWG3NSl4dGdQN5mBT8Kok%2BUAfbk%3D%0A)

### Controle van de Laatste Revisie

Wanneer een gebruiker de gegenereerde QR-code op een bouwplaats of kantoor scant met een mobiel apparaat, verschijnt er een verificatiepagina met één van de volgende statussen:

- **Document geldig:** U heeft de laatste versie van het document in handen.
- **Document ongeldig:** Er is inmiddels een nieuwere revisie beschikbaar in Catenda Hub.
- **Nog niet gepubliceerd:** U scant een placeholder; dit document is nog niet officieel gepubliceerd in een geconfigureerde map.
