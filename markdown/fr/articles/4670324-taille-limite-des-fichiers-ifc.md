# Quelle est la taille de fichier que je peux télécharger ?

Le tableau suivant contient les tailles maximales jusqu'auxquelles les fichiers peuvent être téléchargés : Les fichiers plus volumineux que ces limites nécessitent des méthodes alternatives pour être téléchargés efficacement.

Les tailles de fichiers du tableau ci-dessous s'appliquent aux fichiers individuels en eux-mêmes. Il n'y a pas de limite au nombre de fichiers qui peuvent se trouver dans un projet.

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e3e7fa80; width: 173px;"><h1 id="h_dee0bdcb7c"><b>Taille de téléchargement</b></h1></td><td style="background-color: #e3e7fa80; width: 108px;"><h3 id="h_644423a190"><b>Extension</b></h3></td><td style="background-color: #e3e7fa80;"><h3 class="intercom-align-center" id="h_0cc9638cff"><b>Taille du fichier</b></h3></td></tr><tr><td style="width: 173px;"><h3 id="h_02ef636d2a">Section Documents</h3></td><td style="width: 108px;"><p>Tous</p></td><td><p class="intercom-align-center">7 GB</p></td></tr><tr><td style="background-color: #e8e8e880; width: 173px;"><h3 id="h_79f0da432d">Traitement IFC</h3></td><td style="background-color: #e8e8e880; width: 108px;"><p><code>.ifc</code></p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">750 MB</p></td></tr><tr><td style="width: 173px;"><h3 id="h_7d57516cf7">Traitement IfcZIP</h3></td><td style="width: 108px;"><p><code>.ifczip</code></p></td><td><p class="intercom-align-center">750 MB</p></td></tr><tr><td style="background-color: #e8e8e880; width: 173px;"><h3 id="h_3c990303fb">Nuage de points</h3></td><td style="background-color: #e8e8e880; width: 108px;"><p><code>.e57</code> </p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">25 GB</p></td></tr><tr><td style="width: 173px;"><h3 id="h_0bbd014cc0">Nuage de points</h3></td><td style="width: 108px;"><p><code>.las</code></p></td><td><p class="intercom-align-center">25 GB</p></td></tr><tr><td style="background-color: #e8e8e880; width: 173px;"><h3 id="h_788001d9cb">Import BCF</h3></td><td style="background-color: #e8e8e880; width: 108px;"><p><code>.bcf</code></p></td><td style="background-color: #e8e8e880;"><p class="intercom-align-center">500 MB</p></td></tr><tr><td style="width: 173px;"><h3 id="h_418d98af37">Import BCFZIP</h3></td><td style="width: 108px;"><p><code>.bcfzip</code></p></td><td><p class="intercom-align-center">500 MB</p></td></tr></tbody></table></div>

## 1. **Division en fichiers plus petits**

Il est recommandé de diviser les fichiers volumineux .ifc et .ifczip en fichiers plus petits. La division peut aider à respecter la limite de téléchargement de 750 MB et permet une gestion de fichier plus facile au sein des projets.

En téléchargeant plusieurs fichiers plus petits, il devient plus facile pour les Membres du projet d'activer et de désactiver différentes parties et de télécharger séparément les différentes parties du fichier.

## 2. **Exportation vers IfcZip**

Certains outils d'édition prennent en charge IfcZIP en tant qu'option lors de l'exportation de fichiers IFC.

> **Remarque :** **Exemple :** `3D-model.ifczip`

## 3. **Création d'un IfcZip**

Si la taille d'un fichier `.ifc` dépasse la limite supérieure, un fichier `.ifczip` peut être créé pour rester admissible au téléchargement. Suivez ces étapes pour convertir un `.ifc` en `.ifczip` :

- Compressez le fichier `.ifc` en un fichier `.zip`.
- Modifiez l'extension de fichier de `.zip` en `.ifczip`

> **Remarque :** **Exemple :** `3D-model.ifc` v `3D-model.zip` v `3D-model.ifczip ​`

## 4. **Contacter le support**

Si la modification du fichier n'est pas possible et que le fichier est trop volumineux pour être téléchargé, veuillez nous en informer à [support@catenda.com](mailto:support@catenda.com). Les fichiers sont traités au cas par cas. Avant de nous contacter, envisagez d'utiliser des méthodes alternatives telles que la création d'un `.ifczip`, l'utilisation du Connecteur de bureau ou la division du fichier en parties plus petites.
