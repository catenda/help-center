# Contrôle d'accès à la liste de sujets

> Niveaux de contrôle d'accès aux listes de sujets

Vous pourrez trouver le contrôle d'accès d'une liste de sujets en cliquant sur [modifier l'accès](https://support.catenda.com/en/articles/4670277-issue-board-settings#h_82063f7a79) dans le [menu de contrôle d'accès](https://support.catenda.com/en/articles/4670277-issue-board-settings#h_7a3aca4c7d) sur la page [paramètres de la liste de sujets](https://support.catenda.com/en/articles/4670277-issue-board-settings). _Accès requis:_ Accès complet à la liste de sujets

La boîte de dialogue de modification du contrôle d'accès peut ressembler à ceci:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/66bsqhfn/01-intro.png)

## 1. **Informations sur la liste de sujets**

Ici, le nom et le propriétaire de la liste de sujets sont affichés

## 2. **Extensions - Fermer les sujets**

Limitez qui peut fermer et rouvrir les sujets en limitant qui peut modifier le statut d'un sujet d'un statut avec un méta-statut ouvert à un statut avec un méta-statut fermé. Lorsque vous activez cette fonctionnalité, une [colonne Fermer les sujets](#h_3e36186c6f) apparaîtra à côté de la colonne d'accès.

## 3. **Définir l'accès pour**

Vous pourrez ici spécifier qui a quel accès à cette liste de sujets. En cliquant sur la liste déroulante "Membre ou équipe", vous pourrez définir l'accès pour le(s) membre(s) ou l'équipe. Une fois que vous avez sélectionné un membre ou une équipe, ils apparaîtront dans la liste ci-dessous.

## 4. **Colonne Rôle**

Dans la colonne Rôle, les différents rôles des projets sont décrits

### 4.1 **Administrateurs**

_Par défaut_ - Accès complet Les membres qui sont administrateurs ont toujours un accès complet. Le propriétaire du projet est un administrateur.

### 4.2 **Utilisateurs**

_Par défaut_ - Accès en écriture L'accès accordé aux membres individuels prévalue toujours sur l'accès accordé aux équipes, tous les utilisateurs et propriétaires.

### 4.3 **Tous les utilisateurs**

_Par défaut_ - accès en écriture Tous les utilisateurs est le terme utilisé pour les membres qui n'ont pas obtenu d'accès spécifique en tant qu'utilisateur, équipe ou propriétaire de la liste de sujets.

### 4.4 **Équipes**

_Par défaut_ - Accès en écriture L'accès accordé aux équipes est défini pour tous les membres de l'équipe sauf si le membre a un accès spécifique en tant qu'utilisateur ou propriétaire de la liste de sujets.

### 4.5 **Propriétaire de la liste de sujets**

_Par défaut_ - Accès complet Lorsque vous créez du contenu dans Catenda, vous en devenez le **propriétaire**. Les paramètres du propriétaire s'appliquent au propriétaire du contenu.

> **Remarque:** Les utilisateurs auront la permission la plus élevée parmi ce qui est défini dans **tous les utilisateurs**, **propriétaires** et **équipe**.

> **Conseil:** **Exemple:** Vous pouvez utiliser **équipe**, ou **propriétaires** pour accorder aux utilisateurs plus de permission que **tous les utilisateurs**, mais pas pour leur donner moins de permission.

La raison en est d'empêcher les utilisateurs de s'accorder plus d'accès en se retirant d'une équipe ou en tant que propriétaire.

## 5. **Niveaux d'accès**

Il y a quatre niveaux d'accès définis. L'accès qui s'applique est l'accès le plus élevé que les membres ont reçu soit par l'accès utilisateur, soit par l'accès configuré pour l'une de leurs équipes.

### 5.1 **Aucun accès**

Les membres sans accès ne pourront pas accéder à la liste de sujets.

### 5.2 **Lecture**

Les membres ayant un accès en lecture ont accès à la liste de sujets, mais ne peuvent pas créer de sujets ni faire de commentaires sur les sujets existants.

### 5.3 **Écriture**

Les membres ayant un accès en écriture pourront faire la même chose que les membres ayant un accès en lecture. Les membres ayant un accès en écriture pourront également créer de nouveaux sujets et commenter les sujets existants.

### 5.4 **Accès complet**

Les membres ayant un accès complet pourront faire la même chose que les membres ayant un accès en lecture et en écriture. Avec un accès complet, les membres pourront également modifier les paramètres d'accès de cette liste de sujets. Les membres ayant un accès complet pourront ajouter et modifier les champs personnalisés de cette liste de sujets. Les administrateurs ont toujours un accès complet. Les membres ayant un accès complet ne pourront pas modifier l'accès administrateur.

## 6. **Sujet**

Le tableau ci-dessous relie les opérations qui peuvent être effectuées sur un sujet aux niveaux d'accès de la liste de sujets dans laquelle il se trouve.

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="background-color: #e3e7fa80; width: 227px; padding: 8px;"><h2 id="h_b8c3cd8ee9">Opération</h2></td><td style="background-color: #e3e7fa80; width: 73px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_eaddbaa490">Lecture</h2></td><td style="background-color: #e3e7fa80; width: 195px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_8b71241e18">Écriture</h2></td><td style="background-color: #e3e7fa80; width: 50px; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_138755bddc">Complet</h2></td><td style="background-color: #e3e7fa80; border-left: 1px solid #c6c9c0; padding: 8px;"><h2 class="intercom-align-center" id="h_6eae5730c8">Admin</h2></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Afficher le contenu</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>​</p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Afficher l'historique du sujet</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Partager le sujet</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Créer une liste de sujets</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Créer un sujet dans la liste</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Renommer le sujet</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Modifier les champs d'en-tête du sujet</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Modifier le statut avec méta-statut ouvert à statut avec méta-statut fermé</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x et l'extension fermer les sujets cochée si activée</p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Modifier la description du sujet</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Cocher les cases dans la description</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Créer un commentaire de sujet</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Modifier le commentaire du sujet</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x auteur du commentaire uniquement</p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Cocher les cases dans le commentaire</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x auteur du commentaire uniquement</p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Supprimer le commentaire du sujet</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x auteur du commentaire uniquement</p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Supprimer le sujet</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Archiver la liste de sujets</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Modifier l'ACL de la liste de sujets</p></td><td style="width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="background-color: #e8e8e880; width: 227px; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Déplacer un sujet</p></td><td style="background-color: #e8e8e880; width: 73px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 195px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; width: 50px; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="background-color: #e8e8e880; border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-center">x</p></td></tr></tbody></table></div>

## 7. **Colonne Fermer les sujets**

Les cases à cocher de cette colonne détermineront si ces utilisateurs seront autorisés à fermer les sujets ou non. En bas de la liste, une option créateur de sujet apparaîtra également. L'élément créateur de sujet vous permet de donner des permissions supplémentaires au créateur d'un sujet. Cette règle ne s'applique que lorsque le créateur du sujet n'est pas listé sous "Utilisateurs" et a un accès en écriture.

Si l'option Fermer les sujets n'est pas cochée pour un utilisateur, il ne pourra plus:

- Créer des sujets fermés
- Fermer les sujets existants
- Modifier le statut d'un sujet qui est fermé

Permettez au propriétaire de fermer son propre sujet car seuls les propriétaires savent mieux si tout a été traité ou non. Permettez à une équipe appelée "responsables d'équipe" ou "relecteurs" de fermer les sujets car seuls eux ont l'autorité pour fermer les sujets.

## 8. **Bouton Enregistrer**

> **Remarque:** N'oubliez pas de cliquer sur le bouton Enregistrer et de recharger après avoir terminé pour voir les modifications.

## 9. **Exemple configuré**

Voici à quoi peut ressembler la boîte de dialogue de contrôle d'accès après sa configuration:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/66bsqhfn/02-configured-example.png)
