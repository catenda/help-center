# Modèles-Documents

> **Note:** **NB**: La fonctionnalité "Models as Documents" a été entièrement publiée le 16/11/2023 et sera activée pour tous les nouveaux projets, ainsi que pour les **projets existants à partir du 24 février 2025**.

## 1. **Avant/après la migration - Quelles différences?**

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td style="background-color: #e8e8e8; width: 144px;"><h1 id="h_5a1f3dfb13"></h1></td><td style="background-color: #e8e8e8; width: 234px;"><h2 class="intercom-align-center" id="h_7b42455e17"><b>Avant</b></h2></td><td style="background-color: #e8e8e8; width: 248px;"><h2 class="intercom-align-center" id="h_6bff83e895"><b>Après</b></h2></td></tr><tr><td style="background-color: #e8e8e8; width: 144px;"><p class="intercom-align-right"><b>Caractéristiques principales</b></p></td><td style="width: 234px;"><p>Les modèles n'existaient que dans la section des Modèles. L'utilisateur devait charger le même IFC à la fois dans la section des Modèles et dans la section des Documents.</p></td><td style="width: 248px;"><p>Les modèles sont créés depuis les fichiers IFC chargés dans la section des Documents, à la demande de l'utilisateur. Le fichier IFC et son modèle respectif sont liés.</p></td></tr><tr><td style="background-color: #e8e8e8; width: 144px;"><p class="intercom-align-right"><b>Interface Utilisateur</b></p></td><td style="width: 234px;"><p><b>L'interface Utilisateur des Modèles était differente</b> par rapport à la section des Documents et affichait moins d'information (principalement la liste des modèles existants).</p></td><td style="width: 248px;"><p><b>L'interface Utilisateur est la même que </b>la section des Documents : un tableau paramétrable avec toutes les métadonnéés liées aux modèles respectifs.</p></td></tr><tr><td style="background-color: #e8e8e8; width: 144px;"><p class="intercom-align-right"><b>Droits d'accès</b></p></td><td style="width: 234px;"><p><b>Ne pouvaient pas être appliqués</b> aux modèles.</p></td><td style="width: 248px;"><p><b>Peuvent être appliqués</b> aux modèles à partir de leur document respectif se trouvant au sein de la section documentaire.</p></td></tr></tbody></table></div>

**Avantages**

Les avantages de cette fonctionnalité sont les suivants :

- Ouvrir plusieurs modèles en 2D en les sélectionnant dans la section du document et en cliquant sur le bouton 2D en haut.
- Publier des modèles en une fois, par sélection multiple ou zip upload.
- Supprimer plusieurs modèles à la fois au lieu de les supprimer un par un.
- Structurer vos modèles IFC dans une structure de dossiers.
- Ajouter des étiquettes aux modèles
- Configurer l'ACL pour savoir qui peut voir les modèles dans la section des modèles
    - Vous devez au moins avoir un accès en lecture au modèle-document pour voir le document-modèle.
- Configurer l'ACL de qui peut télécharger des révisions à quel modèle au lieu de seulement tous les modèles ou aucun modèle.
    - Vous devez avoir au moins un accès en écriture au modèle-document pour pouvoir télécharger de nouvelles révisions dans le modèle.
- Configurer la liste de contrôle des personnes autorisées à télécharger un modèle au lieu de tous les modèles ou d'aucun modèle.
    - Vous devez au moins avoir un accès en lecture au modèle-document pour pouvoir télécharger le modèle.
- Télécharger des fichiers IFC en tant que brouillons afin qu'ils puissent être soumis à un processus d'approbation avant d'être publiés.
- La fonction de convention de nommage peut être utilisée pour les noms de modèles.
- Les modèles peuvent être ouverts dans la visionneuse 3D directement à partir de la section des documents.

**Liens**

Les modèles et les documents seront liés les uns aux autres.

Cela ressemble aux documents xRef dans Autocad ou aux documents hyperliens dans InDesign.

**Modèles liés à des documents**

Comme vous pouvez le constater si vous créez un modèle, un document sera également créé dans le dossier des modèles de la section des documents.

Vous pouvez spécifier l'emplacement des nouveaux documents générés par la création d'un modèle dans les paramètres du projet.

**Documents liés aux modèles**

De la même manière, vous pouvez télécharger une IFC dans un dossier et, dans le menu hamburger du panneau de droite, "Créér un modèle". Cela permettra de lier l'IFC à un modèle et de la traiter comme si elle avait été téléchargée dans la section "Modèles".

**Création d'un modèle**

Les modèles peuvent être créés de deux manières:

**Création d'un modèle dans la section des modèles**

Si vous créez un modèle à l'aide du bouton "Créer un modèle" dans la section "Modèles", un document vide sera ajouté dans un dossier appelé "Modèles" dans la section "Documents".

Les documents-modèles peuvent être déplacés de ce dossier vers n'importe quel endroit de la section des documents auquel vous avez accès et le dossier des modèles peut être supprimé si vous le souhaitez.

**Création d'un modèle dans la section des documents**

Vous pouvez créer un modèle depuis le menu hamburger après avoir sélectionné le fichier IFC.

![](https://downloads.intercomcdn.com/i/o/areracg3/1377189219/66a429739b6b9ca8a116b52a7129/image.png?expires=1781092800&signature=05230084a0aea0a466d0da17c782388aadd8a7a79cad7ef0ca38edb3cb2e9e82&req=dSMgEch2lINeUPMW3nq%2BgZrfgay7ee4I6WBKQx%2BUgu0foiEkhGKKT5a8gNN9%0AD4CGFd6Oy6ENuvAomDhZLKPznVI%3D%0A)

Une fois cette opération effectuée, le document apparaît comme un modèle dans la section des modèles dont l'interface est similaire à celle de la section des documents

![](https://downloads.intercomcdn.com/i/o/areracg3/1377200859/a375ad47cd8a9ba37abe1095ae06/image.png?expires=1781092800&signature=6b66d0d02d316663f1492f5d456aee5146025b50111bb5e9aa7e993e10222d0a&req=dSMgEct%2BnYlaUPMW3nq%2BgcZ%2BzzGkosI4ywprokkvTTwxsLuDbcaRko58CVYw%0AHoimzkOAAGgLf1vau31%2FA0m%2BW7E%3D%0A)

Les nouvelles révisions du modèle peuvent être ajoutées en tant que révisions du document.

**Remarque :** cela signifie que vous pouvez créer des modèles à partir de plusieurs fichiers IFC en même temps au lieu de devoir les télécharger un par un.

**Badge de l'icône du modèle de document**

Un modèle de document aura le badge du modèle sur son icône.

![](https://downloads.intercomcdn.com/i/o/811879911/aaf93b647d7a0d7fc7ed6a97/image.png?expires=1781092800&signature=d85d765520058c1439e55163e2fea82d540890b90710aefaed4d0147309ee130&req=fCEmHs53lIBeFb4V1XW4gccdxCQn6BnPwtMJ4ulKi%2Bha5TuhRRWaS4b3SwSd%0Ae5lEzyJ0AdLKyME26LS0NqHi4w%3D%3D%0A)

**Suppression**

Les modèles et les documents peuvent désormais être supprimés de deux manières différentes

**Suppression d'un modèle-document**

Si vous supprimez un modèle connecté à un document, le document perdra la connexion avec le modèle, mais le document restera dans la section des documents.

**Suppression d'un modèle-document.**

Si vous supprimez un document lié à un modèle, vous devrez approuver un avertissement indiquant que le modèle lié au document sera également supprimé.
