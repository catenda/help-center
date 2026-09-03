# Contrôle d'accès aux dossiers et documents

> Niveaux de contrôle d'accès pour les documents

Sélectionnez le(s) document(s) et/ou dossier(s) dans la zone documents pour trouver le menu de contrôle d'accès dans le [menu d'informations de droite](https://support.catenda.com/en/articles/8345396-right-menu-on-the-documents-page#h_cad792004b). Ici, vous pouvez voir les membres du projet qui ont accès au document. Suivez ces étapes pour modifier l'accès des éléments sélectionnés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/01-intro.png)

1. Sélectionnez le(s) document(s) et/ou dossier(s) à configurer.
1. Ouvrez le menu d'informations de droite
1. Cliquez sur **modifier l'accès**.

> **Important :** **Accès requis :** Accès complet

Le dialogue de contrôle d'accès peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/02-intro.png)

## 1. **1. Configurer l'accès pour les participants du projet**

Cliquez sur la liste déroulante « Définir l'accès pour » pour sélectionner les participants pour lesquels l'accès doit être configuré. Les participants peuvent être sélectionnés en tant que membre ou en tant que membre d'une équipe. Les rôles d'accès incluent administrateur, accès utilisateur individuel, accès de base, accès d'équipe et accès propriétaire.

### 1.1 **1.1 Flux de travail recommandé**

Définissez l'accès **par équipe plutôt que par utilisateur**. Les rôles changent souvent, et l'accès basé sur les équipes reste flexible : un membre ajouté à une équipe obtient l'accès approprié dès qu'il rejoint le projet. Un modèle courant consiste à définir « tous les utilisateurs » sur pas d'accès — afin que les nouveaux membres non encore affectés ne puissent pas voir les informations sensibles — puis à accorder l'accès à chaque équipe selon les besoins.

Cliquez [ici](https://support.catenda.com/en/articles/15644094-how-catenda-calculates-access-levels) pour en savoir plus sur la façon dont les différents rôles de participants se comparent les uns aux autres.

## 2. **2. Quel accès est appliqué ? (3 étapes)**

L'accès avec le poids le plus élevé gagne toujours, mais il y a des exceptions. Les niveaux restrictifs comme « Pas d'accès » sont élevés même si d'autres chemins accordent des droits plus élevés.

### 2.1 **2.1 Laquelle des configurations s'applique ?**

**Administrateurs** Les administrateurs ont toujours accès à tout.

**Personnes physiques** Le niveau d'accès exactement configuré s'applique.

**Autres** Vérifiez les différents accès configurés pour un utilisateur via l'un des éléments suivants :

- Tous les utilisateurs
- Une équipe dont l'utilisateur fait partie (peut faire partie de plusieurs)
- Accès propriétaire.

L'accès avec le poids le plus élevé s'applique. Pas d'accès > Accès complet > Écriture > Lecture

Cliquez [ici](https://support.catenda.com/en/articles/15644094-how-catenda-calculates-access-levels) pour en savoir plus sur la façon dont les niveaux d'accès sont calculés. Cliquez [ici](https://support.catenda.com/en/articles/15644249-access-control-deployment-use-cases) pour en savoir plus sur les façons typiques de configurer l'accès.

### 2.2 **2.2 Que peuvent faire les participants avec cet accès ?**

Cliquez [ici](https://support.catenda.com/en/articles/15647394-operations-on-document-library-items) pour en savoir plus sur les opérations pouvant être effectuées sur les dossiers et les Documents.

## 3. **3. Options de remplacement (portée appliquée à l'enregistrement)**

Lorsque le dialogue d'accès est enregistré, l'accès sur les éléments sélectionnés est **remplacé indépendamment de la configuration précédente**. Les trois options sous « Où appliquer ces règles » contrôlent l'étendue de ce changement.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Option</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Ce qui est remplacé</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Quel accès reste inchangé</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Quand utiliser</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Dossier et nouveau contenu</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Éléments sélectionnés + tous les nouveaux éléments créés en eux</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Éléments un niveau en bas + éléments dans les structures de dossiers.</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lorsque vous ne devez pas modifier l'accès aux contenus existants</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Dossier et fichiers<br/>(défaut)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ce qui précède + documents existants un niveau en bas</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Dossiers un niveau en bas + éléments dans les structures de dossiers.</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Le choix habituel ; l'accès par sous-dossier est préservé</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Dossier et tous les sous-dossiers et fichiers</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Ce qui précède + dossiers un niveau en bas + éléments dans les structures de dossiers.</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Uniquement lorsqu'il est acceptable de remplacer aussi l'accès aux sous-dossiers existants</p></td></tr></tbody></table></div>

> **Remarque :** **Attention :** les deux premières options ne remplacent que les éléments sélectionnés, de sorte que l'accès ancien peut subsister sur les sous-éléments. Les membres pourraient ne plus être en mesure d'y accéder directement, mais peuvent toujours les atteindre par filtrage.

## 4. **4. Statut du workflow**

Si les statuts partagés ont été activés après le 2 octobre 2025, deux colonnes supplémentaires apparaissent à droite de la colonne d'accès : **Visualiser les révisions partagées** et **Peut publier**. Les cases à cocher disponibles dépendent du niveau d'accès. Voici à quoi cela peut ressembler :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/rzxv5j3a/03-4-status-workflow.png)

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; padding: 8px;"><p><b>Accès</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Visualiser les révisions partagées</b></p></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><p><b>Publier</b></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Accès refusé</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Non disponible (élément non affiché dans la liste)</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Non</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Lecture</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Peut être accordé (facultatif)</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Non</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p>Écriture</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Toujours capable de voir</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Peut être accordé (facultatif)</p></td></tr><tr><td style="background-color: #e8e8e880; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Accès complet</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Toujours capable de voir</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Oui</p></td></tr></tbody></table></div>
