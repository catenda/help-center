# Filtrage sur la page des sujets

Le menu de filtre dans une liste de sujets peut être ouvert en cliquant sur le bouton de filtre à gauche de la barre de recherche dans une [liste de sujets](https://support.catenda.com/en/articles/4670271-issues-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/01-intro.png)

## 1. **Filtres**

Cliquez sur le bouton de filtre en haut à gauche pour que un panneau apparaisse sur le côté gauche. Quand un filtre est appliqué, l'URL visible dans le navigateur change en conséquence. Dans cet article, les filtres sont affichés ainsi : _Nom du filtre dans le menu_ - `Nom du filtre dans l'URL=Option de filtre dans l'URL`

**Filtre par défaut** Le filtre par défaut n'est initialement pas visible dans l'URL. Lors de la première navigation vers la page, le filtre suivant est appliqué. _Aucun filtre_ - `status-type=all`

### 1.1 **Enregistrer et partager le filtre actuel**

Allez à l'URL d'une page filtrée pour charger cette page avec le filtre appliqué. Les filtres appliqués peuvent être enregistrés vers le haut du menu de filtre. Cliquez [ici](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) pour en savoir plus sur comment enregistrer et partager les filtres

### 1.2 **Masquer les filtres vides**

Cliquez [ici](https://support.catenda.com/en/articles/8551755-saving-filters) pour en savoir plus sur la limitation des résultats de filtre.

## 2. **Filtrage dans le menu de filtre**

Voici les filtres qui peuvent être trouvés :

Les différents filtres du menu de filtre n'apparaîtront que s'il y a des sujets où l'élément filtré a été configuré.

### 2.1 **Mes sujets**

Assigné à moi - `assigned-user=<User GUID>&assigned-team=<Team GUID>` _Utilisateur assigné_ - `assigned-user=<User GUID>` _Mes équipes_ - `assigned-team=<Team GUID>` _Demandé par moi_ - `requester-user=<Your GUID>` Sujets _que je suis_ - `followed-by=me` _me mentionnant_ - `mentioned=me`

> **Remarque :** Si vous partagez un lien avec les filtres "Sujet que je suis" ou "me mentionnant" actifs, l'utilisateur qui ouvre le lien aura sa liste de sujets filtrée pour les sujets qu'il suit et les sujets dans lesquels il a été mentionné, et non les sujets que vous suivez et les sujets dans lesquels vous êtes mentionné. Pour partager des sujets dans lesquels vous avez été mentionné, veuillez utiliser [la recherche de texte](#h_7fc30a16f0)

_Créé par moi_ - `created-by=<User GUID>`

### 2.2 **Statut / Type**

_Tous les statuts ouverts_ - `status-type=open` _Statut ouvert spécifique_ - `status-type=<Status GUID>` _Tous les statuts fermés_ - `status-type=closed` _Statut fermé spécifique_ - `status-type=<Status GUID>` _Type_ - `type=<Type GUID>`

### 2.3 **Date d'échéance**

_En retard_ - `due=overdue` _Tous avec une date d'échéance_ - `due=present` _Pas de date d'échéance_ - `due=none`

### 2.4 **Mis à jour**

Avec le filtre de date, vous pouvez sélectionner une plage horaire pour le moment où les sujets ont été mis à jour en dernier. _Mis à jour_ - `updated-from=<Epoch Unix Timestamp>&updated-to=<Epoch Unix Timestamp>` Lisez [cet](https://support.catenda.com/en/articles/6511685-date-filter) article pour savoir comment sélectionner facilement les dates sur la page.

### 2.5 **Assigné à / Demandé par**

_Assigné à personne_ - `assigned=unassigned` _Aucune équipe assignée_ - `assigned-team=unassigned` _Assigné à l'équipe_ - `assigned-team=<Team GUID>` _Non assigné à l'utilisateur_ - `assigned-user=unassigned` _Assigné à l'utilisateur_ - `assigned-user=<User GUID>` Opérateur assigné - `assigned-op=and` Par défaut, vous ne pouvez rechercher que l'utilisateur assigné OU l'équipe assignée. Dans Catenda Hub, vous pouvez définir un assignataire comme utilisateur@équipe Pour trouver tous les sujets de ce type**,** filtrez par l'équipe et l'utilisateur, et ajoutez &assigned-op=and à la fin de l'URL.

_Non demandé_ - `requester=unassigned` _Non demandé par l'équipe_ - `requester-team=unassigned` _Non demandé par l'utilisateur_ - `requester-user=unassigned` _Demandé par l'utilisateur_ - `requester-user=<User GUID>`

### 2.6 **Créé par**

_Créé par l'utilisateur_ - `created-by=<User GUID>`

### 2.7 **Jalon**

_Jalon_ - `milestone=<Milestone GUID>`

### 2.8 **Champ personnalisé**

_Le champ personnalisé a une valeur_ - `custom-field-has-value-<Custom field GUID>=true` Avec l'option "a une valeur" dans le menu de filtre, tous les sujets qui ont une valeur configurée pour ce champ personnalisé peuvent être filtrés. Types de champs personnalisés qui peuvent être filtrés sur a une valeur : Date Décimal Liste déroulante Nombre entier Texte

_Valeur spécifique du champ personnalisé_ - `custom-field-item-<Custom field GUID>=<Value GUID>` Types de champs personnalisés qui peuvent être filtrés sur une valeur spécifique du menu de filtre : Liste déroulante

Certaines valeurs dans les champs personnalisés où les valeurs peuvent être configurées peuvent être filtrées. Filtrez les valeurs en écrivant une phrase de recherche dans la barre de recherche ou de filtre et en sélectionnant le champ personnalisé correspondant. Types de champs personnalisés qui peuvent être filtrés en tapant dans la barre de recherche ou de filtre : Décimal Liste déroulante Nombre entier Texte

_Le champ personnalisé n'a pas de valeur_ - `custom-field-has-value-<Custom field GUID>=false` Filtrez tous les sujets où un champ personnalisé n'a pas de valeur. Types de champs personnalisés qui peuvent être filtrés sur pas de valeur : Date Décimal Liste déroulante Nombre entier Texte

> **Remarque :** Les champs personnalisés définis comme obligatoires auront toujours une valeur. Vous ne pourrez donc pas rechercher "a une valeur" ou "n'a pas de valeur" et ne pourront donc pas être recherchés pour un champ personnalisé défini comme obligatoire.

### 2.9 **Étiquette**

_Étiquette_ - `label=<Label GUID>` Les étiquettes dans leur propre groupe d'étiquettes sont affichées dans une liste séparée.

### 2.10 **Liens**

Lié - `associations=exists` Filtrez sur les sujets liés aux objets du modèle dans la visionneuse 3D.

Non lié - `associations=does-not-exist` Filtrez sur les sujets qui ne sont pas liés aux objets du modèle dans la visionneuse 3D.

Lié aux objets sélectionnés - `link=backlink` Si le panneau 3D n'est pas déjà ouvert, il s'ouvrira. Sélectionnez les objets d'un modèle dans la visionneuse 3D pour filtrer sur les sujets liés aux objets sélectionnés.

## 3. **Filtrage dans la barre de recherche ou de filtre**

En plus du menu de filtre sur la gauche, il existe certaines fonctionnalités disponibles uniquement via la barre de recherche ou de filtre. Voici ce à quoi la barre de recherche ou de filtre peut ressembler quand elle est en surbrillance :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/02-filtering-in-the-search-or-filter-bar.png)

Sous la barre de recherche ou de filtre, un menu avec des filtres suggérés s'ouvre. Le premier filtre du menu de filtre est suggéré après la mise en surbrillance du menu de recherche ou de filtre. Appuyez sur Entrée pour appliquer ce filtre ou utilisez les touches fléchées pour naviguer entre les différents filtres.

### 3.1 **Filtres enregistrés**

Si vous avez des filtres enregistrés dans une liste de sujets, ceux-ci seront le premier filtre disponible dans le menu de filtre et seront suggérés dès que la boîte de recherche ou de filtre est mise en surbrillance :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/03-saved-filters.png)

Cliquez sur le filtre pour ouvrir la liste filtrée sur l'ensemble enregistré des filtres qui ont reçu un nom. Cliquez [ici](https://support.catenda.com/en/articles/8551755-saving-filters) pour en savoir plus sur comment enregistrer un ensemble de filtres.

### 3.2 **Recherche de texte**

_Recherche de texte -_ `search=<Search phrase>` Après avoir entré des caractères dans la barre de recherche ou de filtre, le premier filtre suggéré se transforme en recherche de texte.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/04-text-search.png)

**Contenu qui peut être recherché** Titre du sujet Description du sujet Commentaires du sujet

**Capitalisation** La recherche de texte n'est pas sensible à la casse.

**Quantités de caractères** Caractère unique Le contenu qui inclut le caractère recherché est mis en correspondance à moins qu'il ne s'agisse d'une lettre unicode avec une valeur supérieure ou égale à 58 au début du contenu.

Deux caractères Le contenu qui a un seul mot, séparé par un caractère séparateur tel qu'un espace, qui correspond à la phrase de recherche est inclus dans les résultats.

Trois caractères ou plus Le contenu qui correspond à la phrase de recherche dans n'importe quelle partie du contenu est inclus dans les résultats.

**Espaces** Les caractères d'espacement au début d'une phrase de recherche sont supprimés.

**Rechercher des membres ou des équipes mentionnés** Les sujets où un membre ou une équipe a été mentionné dans un commentaire ou une description peuvent être trouvés en utilisant la recherche de texte :

Nom du membre ou de l'équipe Recherchez le nom du membre ou de l'équipe pour trouver toutes les occurrences en texte brut de ce membre ou de cette équipe.

Membre mentionné Recherchez sur l'e-mail d'un membre pour trouver toutes les occurrences en texte brut de l'e-mail de ce membre. Cela inclut les endroits où ils ont été mentionnés. Recherchez sur `#[<E-mail du membre>]` pour trouver uniquement les occurrences où ce membre est mentionné.

Équipe mentionnée Les équipes mentionnées peuvent être recherchées en recherchant le GUID de cette équipe. Pour trouver le GUID d'une équipe, allez à la [page de contenu de cette équipe](https://support.catenda.com/en/articles/7891755-team-page) en cliquant sur son nom dans l'[onglet des équipes de la page des membres et des équipes](https://support.catenda.com/en/articles/4670291-members-and-teams-page). L'URL devrait ressembler à ceci : [https://hub.catenda.com/project/\<Project](https://hub.catenda.com/project/<Project) GUID>/members/\<Member GUIID>

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/05-text-search.png)

Recherchez sur le GUID de l'équipe pour trouver toutes les occurrences en texte brut de ce GUID d'équipe. Cela inclut les endroits où ils ont été mentionnés. Recherchez sur `#[<team GUID>]` pour trouver uniquement les occurrences où cette équipe est mentionnée.

### 3.3 **Champs personnalisés - Texte**

Si une phrase de recherche commence par un caractère unicode avec une valeur unicode supérieure ou égale à 58, les filtres suivants apparaîtront vers le bas de la liste des filtres suggérés.

_Champ de texte personnalisé -_ `custom-field-<Custom field GUID>=<Search phrase>` Si un champ de texte personnalisé est activé dans la liste de sujets, le contenu des champs de texte personnalisés dans tous les sujets de la liste peut être filtré avec ce filtre.

### 3.4 **Phrase de recherche numérique**

Si une phrase de recherche commence par un caractère unicode avec une valeur unicode comprise entre 33 et 57, les filtres suivants apparaîtront vers le bas de la liste des filtres suggérés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/06-number-search-phrase.png)

Cela inclut les caractères suivants : `!`,`"`,`#`,`$`,`%`,`&`,`'`,`(`,`)`,`*`,`+`,`,`,`-`,`.`,`/`,`0`,`1`,`2`,`3`,`4`,`5`,`6`,`7`,`8`,`9`

_Sujet -_ `issues=<issue number>` Quand une phrase de recherche commence par un nombre, la recherche de numéro de sujet apparaît en tant que suggestion dans la barre de recherche ou de filtre. Le filtre suggéré peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/07-number-search-phrase.png)

Bien qu'il soit possible de filtrer une liste pour les numéros de sujets avec plus que de simples nombres, les sujets ne peuvent être trouvés avec leur nombre avec ce filtre. Si plus que de simples nombres sont fournis, le filtre disparaîtra du menu mais la liste sera toujours filtrée sur la phrase entrée.

Filtrage d'un ou plusieurs sujets par nombre Il est uniquement possible de rechercher un sujet à la fois à partir de la barre de recherche ou de filtre. Si le sujet avec le numéro de sujet Catenda 123 existe dans la liste, l'url aura `&issues=123` dedans quand il est filtré sur le numéro de sujet 123. Il est possible d'entrer plus de numéros de sujets dans l'url, par exemple : `&issues123,124,125` afficherait les trois sujets s'ils existent dans la liste. Le filtrage sur plusieurs sujets de cette manière n'est possible qu'en éditant l'URL.

### 3.5 **Champs personnalisés - Nombre**

_Champ de nombre entier personnalisé -_ `custom-field-<Custom field GUID>=<Search phrase>` Si un champ de nombre entier personnalisé est activé dans la liste de sujets, le contenu des champs de nombre entier personnalisés dans tous les sujets de la liste peut être filtré avec ce filtre.

_Champ décimal personnalisé -_ `custom-field-<Custom field GUID>=<Search phrase>` Si un champ décimal personnalisé est activé dans la liste de sujets, le contenu des champs décimaux personnalisés dans tous les sujets de la liste peut être filtré avec ce filtre.

### 3.6 **Champs personnalisés - Liste déroulante**

Si une phrase de recherche correspond au nom d'une valeur dans un filtre, le filtre qui correspond au mieux sera suggéré dans la boîte de suggestion.

_Champ de liste déroulante personnalisé_ _-_ `custom-field-item-<Custom field GUID>=<Dropdown value GUID>` Si la phrase de recherche correspond à une valeur dans un champ de liste déroulante personnalisé avec jusqu'à 10 valeurs, il sera suggéré de rechercher sur cette valeur de liste déroulante.
