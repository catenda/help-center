# Bewerkingen op documenten in de bibliotheek

## 1. **1. Mapmapbewerkingen**

Dit zijn de verschillende bewerkingen die kunnen worden uitgevoerd op een map op basis van de toegangsniveaus.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Bewerking</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Vereiste toegang</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Mapinhoud weergeven / een mapkoppeling delen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lezen</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Een document maken, een submap toevoegen, de map een nieuwe naam geven</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Schrijven</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Verplaatsen, verwijderen, toegangsinstellingen (ACL) wijzigen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Volledige toegang</p></td></tr></tbody></table></div>

### 1.1 **1.1 Vereiste toegang: Lezen**

**Standaardgedrag** Alle leden hebben standaard minstens schrijftoegang. Een lid kan leestoegang hebben tot een map als deze is gemaakt in een map waar leestoegang is geconfigureerd of als leestoegang specifiek voor de map is geconfigureerd. De map kan later zijn verplaatst, dus de toegang hoeft niet noodzakelijk hetzelfde te zijn als de map waarin deze zich bevindt.

**Mapinhoud weergeven** Leden met leestoegang kunnen naar de inhoud van een map navigeren. Er kunnen verschillende toegangsmogelijkheden worden geconfigureerd voor de mapinhoud, zodat leden met leestoegang mogelijk niet alle elementen in de map kunnen openen.

**Map delen** Leden met leestoegang kunnen mapkoppelingen delen via sharelink of door de URL in te voeren. De sharelink-ontvanger kan verschillende toegang hebben en kan dezelfde mapinhoud niet zien. Er kan een openbare koppeling naar een collectie worden gemaakt met de mapinhoud, zodat iedereen de inhoud van de collectie kan downloaden, ongeacht de toegangsinstellingen.

### 1.2 **1.2 Vereiste toegang: Schrijven**

**Standaardgedrag** Alle leden hebben standaard minstens schrijftoegang.

**Document maken in map** Leden met schrijftoegang tot een map kunnen nieuwe documenten in die map maken.

**Map in map toevoegen** Leden met schrijftoegang tot een map kunnen nieuwe mappen in die map maken.

**Map een nieuwe naam geven** Leden met schrijftoegang tot een map kunnen de map een nieuwe naam geven.

### 1.3 **1.3 Vereiste toegang: Volledige toegang**

**Standaardgedrag** De maapeigenaar (maker van de map) en beheerders hebben standaard volledige toegang.

**Map verplaatsen** Leden met volledige toegang kunnen mappen naar andere mappen verplaatsen. Maapeigenaren (makers van de map) hebben vaak volledige toegang en kunnen daarom hun eigen mappen verplaatsen. Leden hebben vaak schrijftoegang tot documenten die door andere leden zijn gemaakt. Leden kunnen daarom meestal alleen mappen verplaatsen die ze zelf hebben gemaakt, tenzij ze zich in een map bevinden waarvoor hen meer toegang is gegeven.

**Map verwijderen** Leden met volledige toegang kunnen een map verwijderen, ongeacht de toegang die in de map is ingesteld.

**Map-ACL wijzigen** Leden met volledige toegang tot een map kunnen de toegangsinstellingen voor die map wijzigen.

## 2. **2. Documentbewerkingen**

Dit zijn de verschillende bewerkingen die kunnen worden uitgevoerd op een document op basis van de toegangsniveaus.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Bewerking</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Vereiste toegang</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Een documentkoppeling delen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lezen</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Objecten koppelen/ontkoppelen, labels bewerken, maken, hernoemen, een model (IFC) maken</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Schrijven</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Naar een ander mapje verplaatsen, verwijderen, de ACL wijzigen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Volledige toegang</p></td></tr></tbody></table></div>

> **Opmerking:** Het maken of verwijderen van een model uit een IFC-document vereist ook schrijftoegang tot "models maken en verwijderen" in projectinstellingen.

### 2.1 **2.1 Vereiste toegang: Lezen**

**Standaardgedrag** Alle leden hebben standaard minstens schrijftoegang. Een lid kan leestoegang hebben tot een document als dit is geüpload naar een map waar leestoegang is geconfigureerd of als leestoegang specifiek voor het document is geconfigureerd. Het document kan later zijn verplaatst, dus de toegang hoeft niet noodzakelijk hetzelfde te zijn als in de map waarin het zich bevindt.

**Document delen** Documenten kunnen via sharelink of door de URL in te voeren worden gedeeld. De sharelink-ontvanger kan verschillende toegang hebben en kan dezelfde documentrevisies niet zien. Er kan een openbare koppeling naar een collectie worden gemaakt met een specifieke documentrevisie, zodat iedereen de inhoud van de collectie kan downloaden, ongeacht de toegangsinstellingen.

### 2.2 **2.2 Vereiste toegang: Schrijven**

**Standaardgedrag** Alle leden hebben standaard minstens schrijftoegang.

**Objecten koppelen/ontkoppelen** Leden met minstens schrijftoegang kunnen objecten aan een document koppelen en ontkoppelen.

**Labels bewerken** Leden met minstens schrijftoegang kunnen labels aan een document toevoegen en verwijderen.

**Nieuw document maken** Leden met minstens schrijftoegang tot de bovenliggende map kunnen documenten in die map maken.

**Document hernoemen** Leden met minstens schrijftoegang kunnen documenten hernoemen.

**Model maken** Leden met minstens schrijftoegang tot een document kunnen een model uit een ifc-document maken, zodat dit op de modellenafbeelding wordt weergegeven. Vereiste extensie: `.ifc` of `.ifczip` _Aanvullende vereiste toegang:_ Schrijftoegang tot "models maken en verwijderen" in projectinstellingen

**Model verwijderen** Leden met minstens schrijftoegang kunnen de modelkoppeling uit een document verwijderen dat is gekoppeld aan een model, zodat dit verdwijnt van de modellenafbeelding. _Aanvullende vereiste toegang:_ Schrijftoegang tot "models maken en verwijderen" in projectinstellingen

### 2.3 **2.3 Vereiste toegang: Volledige toegang**

**Standaardgedrag** De documenteigenaar (maker van het document en vaak de uploader van de eerste revisie) en beheerders hebben standaard volledige toegang.

**Document naar een ander mapje verplaatsen** Leden met volledige toegang kunnen documenten naar andere mappen verplaatsen. Documenteigenaren (makers van het document en vaak de uploader van de eerste revisie) hebben vaak volledige toegang en kunnen daarom hun eigen documenten verplaatsen. Leden hebben vaak schrijftoegang tot documenten die door andere leden zijn gemaakt. Leden kunnen daarom meestal alleen documenten verplaatsen die ze zelf hebben gemaakt, tenzij ze zich in een map bevinden waarvoor hun meer toegang is gegeven.

**Document verwijderen** Leden met volledige toegang kunnen een document verwijderen, ongeacht de toegang die in het mapje is ingesteld.

**ACL wijzigen** Leden met volledige toegang tot een document kunnen de toegang tot dat document wijzigen.

## 3. **3. Bewerkingen gepubliceerde revisies**

In de onderstaande tabel worden de bewerkingen die op een gepubliceerde revisie kunnen worden uitgevoerd, gerelateerd aan de toegangsniveaus. Standaard worden alle nieuwe revisies in documenten gepubliceerd. Als gedeelde revisies zijn ingeschakeld, worden alle nieuwe revisies in documenten standaard gemaakt als gedeelde revisies.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Bewerking</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Vereiste toegang</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Voorbeeld in Catenda Hub, toegang in apps (mobiel / Catenda Site), 2D/3D-viewer, downloaden, vergelijken, toevoegen aan collectie, delen</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lezen</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Intrekken</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Volledige toegang</p></td></tr></tbody></table></div>

### 3.1 **3.1 Vereiste toegang: Lezen**

**Voorbeeld in Catenda Hub** Leden met minstens leestoegang tot een document kunnen gepubliceerde revisies in Catenda Hub bekijken.

**Toegang in toepassingen** Leden met minstens leestoegang tot een document kunnen gepubliceerde revisies van toepassingen die de API openen, zoals onze mobiele toepassing, Catenda Site, openen.

**Knoppen 2D/3D-viewer** Leden met minstens leestoegang tot een document met gepubliceerde 3D-documentrevisies kunnen de knoppen 2D en 3D in de viewerkolom gebruiken om het 3D-document in de desbetreffende viewer in te laden. Een van de volgende is vereist:

- Document gekoppeld aan model en de nieuwste revisie is een succesvol verwerkt `.ifc` of `.ifczip`
- Nieuwste revisie is een pointcloud
- Nieuwste revisie is een CityGML

**Gepubliceerde revisie delen** Leden met minstens leestoegang tot een document met gepubliceerde revisies kunnen koppelingen naar revisies via sharelink of door de URL in te voeren delen. De sharelink-ontvanger kan verschillende toegang hebben en kan het document mogelijk niet weergeven. Er kan een openbare koppeling naar een collectie worden gemaakt met een specifieke gepubliceerde revisie, zodat iedereen de inhoud van de collectie kan downloaden, ongeacht de toegangsinstellingen.

**Vergelijken** Leden met minstens leestoegang tot een document met minstens twee pdf-revisies kunnen de vergelijkingsfunctie gebruiken. Aanvullende vereiste toegang: Tweede gepubliceerde PDF-revisie aanwezig in document

**Downloaden** Leden met minstens leestoegang tot een document met gepubliceerde revisies kunnen de gepubliceerde revisies in het document downloaden.

**Toevoegen aan collectie** Leden met minstens leestoegang tot een document met gepubliceerde revisies kunnen een gepubliceerde revisie van een document aan een collectie toevoegen.

### 3.2 **3.2 Vereiste toegang: Volledige toegang**

**Intrekken** Leden met volledige toegang tot een document kunnen gepubliceerde revisies in het document intrekken.

## 4. **4. Bewerkingen conceptrevisies - Verouderd**

In de onderstaande tabel worden de bewerkingen die op een conceptrevisie kunnen worden uitgevoerd, gerelateerd aan de toegangsniveaus. Conceptrevisies zijn alleen beschikbaar in projecten die vóór 2 oktober 2025 zijn gemaakt.

### 4.1 **4.1 Vereiste toegang: Geen toegang**

**Toegang in toepassingen** Alleen gepubliceerde revisies kunnen worden geopend vanuit toepassingen die onze API benaderen, zoals onze mobiele toepassing, Catenda Site.

**Toevoegen aan collectie** Alleen gepubliceerde revisies kunnen aan collecties worden toegevoegd.

### 4.2 **4.2 Vereiste toegang: Lezen**

**Voorbeeld in Catenda Hub** Leden met minstens leestoegang tot een document en leestoegang tot concepten in projectinstellingen kunnen conceptrevisies in Catenda Hub bekijken. _Aanvullende vereiste toegang:_ Leestoegang tot documentconcepten in projectinstellingen.

**Conceptrevisie delen** Leden met minstens leestoegang tot een document met conceptrevisies en leestoegang tot concepten in projectinstellingen kunnen koppelingen naar conceptrevisies via sharelink of door de URL in te voeren delen. De sharelink-ontvanger kan verschillende toegang hebben en kan het document mogelijk niet weergeven.

**Downloaden** Leden met minstens leestoegang tot een document met conceptrevisies en leestoegang tot concepten in projectinstellingen kunnen conceptrevisies downloaden. Conceptrevisies kunnen een voor een worden gedownload door op de downloadknop in het revisiegebied van het rechtermenu van de revisie op de documentpreviewpagina te klikken. _Aanvullende vereiste toegang:_ Leestoegang tot documentconcepten in projectinstellingen

### 4.3 **4.3 Vereiste toegang: Schrijven**

**Voorbeeld in Catenda Hub** _Aanvullende vereiste toegang:_ Documenteigenaar

**Publiceren** In projecten waar de statuswerkstroom vóór 2 oktober 2025 was geactiveerd, is het selectievakje conceptrevisie standaard ingeschakeld in het uploadmenu, maar kan het worden uitgeschakeld om in plaats daarvan een gepubliceerde revisie te uploaden.

## 5. **5. Gedeelde revisie**

In de onderstaande tabel worden de bewerkingen die op een gedeelde revisie kunnen worden uitgevoerd, gerelateerd aan de toegangsniveaus. Als gedeelde revisies zijn ingeschakeld, worden alle nieuwe revisies in documenten standaard gemaakt als gedeelde revisies.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Bewerking</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Vereiste toegang (+ extra voorwaarde)</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Voorbeeld, delen, downloaden</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lezen (+ "Gedeelde revisies weergeven" aangevinkt)</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Publiceren</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Schrijven (+ "Kan publiceren" aangevinkt)</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Intrekken</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>"Gedeelde revisies weergeven" aangevinkt</p></td></tr></tbody></table></div>

> **Opmerking:** Opmerking: Alleen gepubliceerde revisies kunnen worden geopend vanuit apps of aan collecties worden toegevoegd.

### 5.1 **5.1 Vereiste toegang: Geen toegang**

**Toegang in toepassingen** Alleen gepubliceerde revisies kunnen worden geopend vanuit toepassingen die onze API benaderen, zoals onze mobiele toepassing, Catenda Site.

**Toevoegen aan collectie** Alleen gepubliceerde revisies kunnen aan collecties worden toegevoegd.

### 5.2 **5.2 Vereiste toegang: Lezen**

**Voorbeeld in Catenda Hub** Leden met minstens leestoegang tot een document met gedeelde revisies en toegang tot het weergeven van de gedeelde revisies van een document kunnen gedeelde revisies in Catenda Hub bekijken. _Aanvullende vereiste toegang:_ "Gedeelde revisies weergeven" aangevinkt in het documenttoegangsmenu

**Gedeelde revisie delen** Leden met minstens leestoegang tot een document met gedeelde revisies en toegang tot het weergeven van de gedeelde revisies van een document kunnen koppelingen naar gedeelde revisies via sharelink of door de URL in te voeren delen. De sharelink-ontvanger kan verschillende toegang hebben en kan het document mogelijk niet weergeven.

**Downloaden** Leden met minstens leestoegang tot een document met gedeelde revisies en toegang tot het weergeven van de gedeelde revisies van een document kunnen gedeelde revisies downloaden. De nieuwste gedeelde revisies van documenten die zijn geselecteerd op het werkruimtetabblad van de documenttabel kunnen met de downloadactie worden gedownload. Eerdere gedeelde revisies kunnen een voor een worden gedownload door op de downloadknop in het revisiegebied van het rechtermenu van de revisie op de documentpreviewpagina te klikken. _Aanvullende vereiste toegang:_ "Gedeelde revisies weergeven" is aangevinkt in het documenttoegangsmenu

### 5.3 **5.3 Vereiste toegang: Schrijven**

**Publiceren** Leden met minstens schrijftoegang tot een document met gedeelde revisies, toegang tot het weergeven van de gedeelde revisies van een document en toegang tot publicatie van revisies in het document kunnen één van de gedeelde revisies publiceren die sinds de nieuwste gepubliceerde revisie in het document zijn geüpload. _Aanvullende vereiste toegang:_ "Kan publiceren" is aangevinkt in het documenttoegangsmenu

### 5.4 **5.4 Vereiste toegang: Volledige toegang**

**Intrekken** Leden met minstens leestoegang tot een document met gedeelde revisies en toegang tot het weergeven van de gedeelde revisies van een document kunnen gedeelde revisies in het document intrekken. _Aanvullende vereiste toegang:_ "Gedeelde revisies weergeven" is aangevinkt in het documenttoegangsmenu
