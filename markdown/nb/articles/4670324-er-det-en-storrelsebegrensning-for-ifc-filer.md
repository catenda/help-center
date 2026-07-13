# Hvilken filstørrelse kan jeg laste opp?

Tabellen nedenfor inneholder størrelser opp til hvilke filer kan lastes opp: Filer større enn disse grensene krever alternative metoder for å lastes opp effektivt.

Filstørrelsene i tabellen nedenfor gjelder individuelle filer i seg selv. Det er ingen grense for hvor mange filer som kan være i et prosjekt.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 173px;"><h1 id="h_dee0bdcb7c"><b>Opplastingsstørrelse</b></h1></td><td style="background-color: #e3e7fa80; width: 108px;"><h3 id="h_644423a190"><b>Utvidelse</b></h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_0cc9638cff"><b>Filstørrelse</b></h3></td></tr><tr><td style="width: 173px;"><h3 id="h_02ef636d2a">Dokumentdel</h3></td><td style="width: 108px;"><p>Alle</p></td><td><p class="intercom-align-center">7 GB</p></td></tr><tr><td style="background-color: #e8e8e880; width: 173px;"><h3 id="h_79f0da432d">IFC-prosessering</h3></td><td style="background-color: #e8e8e880; width: 108px;"><p><code>.ifc</code></p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">750 MB</p></td></tr><tr><td style="width: 173px;"><h3 id="h_7d57516cf7">IfcZIP-prosessering</h3></td><td style="width: 108px;"><p><code>.ifczip</code></p></td><td><p class="intercom-align-center">750 MB</p></td></tr><tr><td style="background-color: #e8e8e880; width: 173px;"><h3 id="h_3c990303fb">Punktsky</h3></td><td style="background-color: #e8e8e880; width: 108px;"><p><code>.e57</code> </p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">25 GB</p></td></tr><tr><td style="width: 173px;"><h3 id="h_0bbd014cc0">Punktsky</h3></td><td style="width: 108px;"><p><code>.las</code></p></td><td><p class="intercom-align-center">25 GB</p></td></tr><tr><td style="background-color: #e8e8e880; width: 173px;"><h3 id="h_788001d9cb">BCF-import</h3></td><td style="background-color: #e8e8e880; width: 108px;"><p><code>.bcf</code></p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">500 MB</p></td></tr><tr><td style="width: 173px;"><h3 id="h_418d98af37">BCFZIP-import</h3></td><td style="width: 108px;"><p><code>.bcfzip</code></p></td><td><p class="intercom-align-center">500 MB</p></td></tr></tbody></table></div>

Følgende emner er beskrevet i denne artikkelen:

## 1. **Deling i mindre filer**

Store .ifc- og .ifczip-filer anbefales å deles inn i mindre filer. Deling kan bidra til å overholde begrensningen på 750 MB opplasting og muliggjør mer håndterlig filbehandling innen prosjekter.

Ved å laste opp flere mindre filer blir det både lettere for medlemmer av prosjektet å slå på og av ulike deler og å laste ned separate deler av filen individuelt.

## 2. **Eksport til IfcZip**

Noen forfattingsverktøy støtter IfcZIP som et alternativ når IFC-filer eksporteres.

> **Merknad:** **Eksempel:** `3D-model.ifczip`

## 3. **Oppretting av IfcZip**

Hvis størrelsen på en `.ifc` overstiger den øvre grensen, kan en `.ifczip`-fil opprettes for å forbli kvalifisert for opplasting. Følg disse trinnene for å gjøre en `.ifc` til en `.ifczip`:

- Komprimer `.ifc`-filen til en `.zip`-fil.
- Endre filendelsen fra `.zip` til `.ifczip`

> **Merknad:** **Eksempel:** `3D-model.ifc` v `3D-model.zip` v `3D-model.ifczip ​`

## 4. **Kontakt support**

Hvis endring av filen ikke er et alternativ, og filen er større enn det som kan lastes opp, vennligst gi oss beskjed på [support@catenda.com](mailto:support@catenda.com). Filer håndteres fra sak til sak. Før du tar kontakt, vurder å bruke alternative metoder som å opprette en `.ifczip`, bruke Desktop Connector, eller dele filen inn i mindre deler.
