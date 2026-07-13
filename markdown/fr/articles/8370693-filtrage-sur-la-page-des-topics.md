# Filtrage sur la page des topics

Le menu de filtrage dans un tableau de topics peut être ouvert en cliquant sur le bouton de filtrage à gauche de la barre de recherche dans un [tableau de topics](https://support.catenda.com/en/articles/4670271-issues-page).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/01-intro.png)

Les topics suivants sont décrits dans cet article :

## 1. **Filtres**

Cliquez sur le bouton de filtrage en haut à gauche pour qu'un panneau apparaisse sur le côté gauche. Lorsqu'un filtre est appliqué, l'URL visible dans le navigateur change en conséquence. Dans cet article, les filtres sont affichés comme suit : _Nom du filtre dans le menu_ - `Nom du filtre dans l'URL=Option du filtre dans l'URL`

**Filtre par défaut** Le filtre par défaut n'est initialement pas visible dans l'URL. Lorsque la page est accédée pour la première fois, le filtre suivant est appliqué. _Aucun filtre_ - `status-type=all`

### 1.1 **Enregistrer et partager le filtre actuel**

Accédez à l'URL d'une page filtrée pour charger cette page avec le filtre appliqué. Les filtres appliqués peuvent être enregistrés vers le haut du menu de filtrage. Cliquez [ici](https://support.catenda.com/en/articles/11401493-saving-a-filter-link) pour en savoir plus sur la façon d'enregistrer et de partager les filtres

### 1.2 **Masquer les filtres vides**

Cliquez [ici](https://support.catenda.com/en/articles/8551755-saving-filters) pour en savoir plus sur la limitation des résultats de filtrage.

## 2. **Filtrage dans le menu de filtrage**

Vous trouverez ici les filtres suivants :

Les différents filtres du menu de filtrage n'apparaîtront que s'il existe des topics pour lesquels l'élément filtré a été configuré.

Les topics suivants sont décrits dans cette section :

### 2.1 **Mes topics**

Assigné à moi - `assigned-user=<User GUID>&assigned-team=<Team GUID>` _Utilisateur assigné_ - `assigned-user=<User GUID>` _Mes équipes_ - `assigned-team=<Team GUID>` _Demandé par moi_ - `requester-user=<Your GUID>` Topics _que je suis_ - `followed-by=me` _me mentionnant_ - `mentioned=me`

> **Remarque :** Si vous partagez un lien avec les filtres "Topic que je suis" ou "me mentionnant" actifs, l'utilisateur qui ouvre le lien aura son tableau de topics filtré pour les topics qu'il suit et les topics dans lesquels il a été mentionné, et non les topics que vous suivez et les topics dans lesquels vous êtes mentionné. Pour partager les topics dans lesquels vous avez été mentionné, veuillez utiliser [la recherche textuelle](#text-search)

_Créé par moi_ - `created-by=<User GUID>`

### 2.2 **Statut / Type**

_Tous les statuts ouverts_ - `status-type=open` _Statut ouvert spécifique_ - `status-type=<Status GUID>` _Tous les statuts fermés_ - `status-type=closed` _Statut fermé spécifique_ - `status-type=<Status GUID>` _Type_ - `type=<Type GUID>`

### 2.3 **Échéance**

_En retard_ - `due=overdue` _Tous avec une échéance_ - `due=present` _Pas d'échéance_ - `due=none`

### 2.4 **Mise à jour**

Avec le filtre de date, vous pouvez sélectionner une période pour le moment où les topics ont été mis à jour pour la dernière fois. _Mise à jour_ - `updated-from=<Epoch Unix Timestamp>&updated-to=<Epoch Unix Timestamp>` Lisez [cet](https://support.catenda.com/en/articles/6511685-date-filter) article pour apprendre comment sélectionner facilement les dates sur la page.

### 2.5 **Assigné à / Demandé par**

_Assigné à personne_ - `assigned=unassigned` _Aucune équipe assignée_ - `assigned-team=unassigned` _Assigné à l'équipe_ - `assigned-team=<Team GUID>` _Non assigné à l'utilisateur_ - `assigned-user=unassigned` _Assigné à l'utilisateur_ - `assigned-user=<User GUID>` Opérateur assigné - `assigned-op=and` Par défaut, vous ne pouvez rechercher que l'utilisateur assigné OU l'équipe assignée. Dans Catenda Hub, vous pouvez définir un assignataire comme utilisateur@équipe Pour trouver tous les topics de ce type, filtrez par l'équipe et l'utilisateur, et ajoutez &assigned-op=and à la fin de l'URL.

_Non demandé_ - `requester=unassigned` _Non demandé par équipe_ - `requester-team=unassigned` _Non demandé par utilisateur_ - `requester-user=unassigned` _Demandé par l'utilisateur_ - `requester-user=<User GUID>`

### 2.6 **Créé par**

_Créé par l'utilisateur_ - `created-by=<User GUID>`

### 2.7 **Jalons**

_Jalon_ - `milestone=<Milestone GUID>`

### 2.8 **Champ personnalisé**

_Le champ personnalisé a une valeur_ - `custom-field-has-value-<Custom field GUID>=true` Avec l'option "a une valeur" dans le menu de filtrage, tous les topics ayant une valeur configurée pour ce champ personnalisé peuvent être filtrés. Types de champs personnalisés qui peuvent être filtrés sur a une valeur : Date Décimal Déroulant Entier Texte

_Valeur spécifique du champ personnalisé_ - `custom-field-item-<Custom field GUID>=<Value GUID>` Types de champs personnalisés qui peuvent être filtrés sur une valeur spécifique depuis le menu de filtrage : Déroulant

Certaines valeurs dans les champs personnalisés où les valeurs peuvent être configurées peuvent être filtrées. Filtrez les valeurs en tapant une phrase de recherche dans la barre de recherche ou de filtrage et en sélectionnant le champ personnalisé correspondant. Types de champs personnalisés qui peuvent être filtrés en tapant dans la barre de recherche ou de filtrage : Décimal Déroulant Entier Texte

_Le champ personnalisé n'a pas de valeur_ - `custom-field-has-value-<Custom field GUID>=false` Filtrez tous les topics où un champ personnalisé n'a pas de valeur. Types de champs personnalisés qui peuvent être filtrés sur aucune valeur : Date Décimal Déroulant Entier Texte

> **Remarque :** Les champs personnalisés définis comme obligatoires auront toujours une valeur. Vous ne pourrez donc pas rechercher "a une valeur" ou "n'a pas de valeur" pour un champ personnalisé défini comme obligatoire.

### 2.9 **Étiquette**

_Étiquette_ - `label=<Label GUID>` Les étiquettes dans leur propre groupe d'étiquettes sont affichées dans une liste séparée.

### 2.10 **Liens**

Lié - `associations=exists` Filtrez les topics liés aux objets du modèle dans la visionneuse 3D.

Non lié - `associations=does-not-exist` Filtrez les topics qui ne sont pas liés aux objets du modèle dans la visionneuse 3D.

Lié aux objets sélectionnés - `link=backlink` Si le panneau 3D n'est pas déjà ouvert, il s'ouvrira. Sélectionnez des objets à partir d'un modèle dans la visionneuse 3D pour filtrer les topics liés aux objets sélectionnés.

## 3. **Filtrage dans la barre de recherche ou de filtrage**

En plus du menu de filtrage sur la gauche, il existe des fonctionnalités disponibles uniquement via la barre de recherche ou de filtrage. Voici à quoi peut ressembler la barre de recherche ou de filtrage lorsqu'elle est mise en surbrillance :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/02-filtering-in-the-search-or-filter-bar.png)

Sous la barre de recherche ou de filtrage, un menu avec des filtres suggérés s'ouvre. Le premier filtre du menu de filtrage est suggéré après la mise en surbrillance du menu de recherche ou de filtrage. Appuyez sur Entrée pour appliquer ce filtre ou utilisez les touches fléchées pour naviguer entre les différents filtres.

Les topics suivants sont décrits dans cette section :

### 3.1 **Filtres enregistrés**

Si vous avez des filtres enregistrés dans un tableau de topics, ceux-ci seront le premier filtre disponible dans le menu de filtrage et seront suggérés dès que vous mettez en surbrillance la boîte de recherche ou de filtrage :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/03-saved-filters.png)

Cliquez sur le filtre pour filtrer le tableau sur l'ensemble des filtres enregistrés qui ont reçu un nom. Cliquez [ici](https://support.catenda.com/en/articles/8551755-saving-filters) pour en savoir plus sur la façon d'enregistrer un ensemble de filtres.

### 3.2 **Recherche textuelle**

_Recherche textuelle -_ `search=<Search phrase>` Après avoir saisi des caractères dans la barre de recherche ou de filtrage, le premier filtre suggéré change en recherche textuelle.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/04-text-search.png)

**Contenu qui peut être recherché** Titre du topic Description du topic Commentaires du topic

**Capitalisation** La recherche textuelle n'est pas sensible aux caractères majuscules ou minuscules.

**Quantités de caractères** Un caractère Le contenu qui inclut le caractère recherché est mis en correspondance sauf s'il s'agit d'une lettre unicode avec une valeur de 58 ou plus au début du contenu.

Deux caractères Le contenu qui a un seul mot, séparé par un caractère de séparation comme un espace, qui correspond à la phrase de recherche est inclus dans les résultats.

Trois caractères ou plus Le contenu qui correspond à la phrase de recherche dans n'importe quelle partie du contenu est inclus dans les résultats.

**Espace blanc** Les caractères d'espace blanc au début d'une phrase de recherche sont supprimés.

**Recherche de membres ou d'équipes mentionnés** Les topics où un membre ou une équipe a été mentionné dans un commentaire ou une description peuvent être trouvés en utilisant la recherche textuelle :

Nom du membre ou de l'équipe Recherchez le nom du membre ou de l'équipe pour trouver toutes les occurrences de texte brut de ce nom de membre ou d'équipe.

Membre mentionné Recherchez l'email d'un membre pour trouver toutes les occurrences de texte brut de l'email de ce membre. Cela inclut les endroits où ils ont été mentionnés. Recherchez `#[<Email du membre>]` pour trouver uniquement les occurrences où ce membre est mentionné.

Équipe mentionnée Les équipes mentionnées peuvent être recherchées en recherchant le GUID de cette équipe. Pour trouver le GUID d'une équipe, accédez à la [page de contenu de cette équipe](https://support.catenda.com/en/articles/7891755-team-page) en cliquant sur son nom dans l'[onglet Équipes de la page Membres et équipes](https://support.catenda.com/en/articles/4670291-members-and-teams-page). L'URL devrait ressembler à ceci : [https://hub.catenda.com/project/\<Project](https://hub.catenda.com/project/<Project) GUID>/members/\<Member GUIID>

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/05-text-search.png)

Recherchez le GUID de l'équipe pour trouver toutes les occurrences de texte brut de ce GUID d'équipe. Cela inclut les endroits où ils ont été mentionnés. Recherchez `#[<team GUID>]` pour trouver uniquement les occurrences où cette équipe est mentionnée.

### 3.3 **Champs personnalisés - Texte**

Si une phrase de recherche commence par un caractère unicode avec une valeur unicode de 58 ou plus, les filtres suivants apparaîtront vers le bas de la liste des filtres suggérés.

_Champ personnalisé de texte -_ `custom-field-<Custom field GUID>=<Search phrase>` Si un champ personnalisé de texte est activé dans le tableau de topics, le contenu des champs personnalisés de texte dans tous les topics du tableau peut être filtré avec ce filtre.

### 3.4 **Phrase de recherche numérique**

Si une phrase de recherche commence par un caractère unicode avec une valeur unicode entre 33 et 57, les filtres suivants apparaîtront vers le bas de la liste des filtres suggérés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/06-number-search-phrase.png)

Cela inclut les caractères suivants : `!`,`"`,`#`,`$`,`%`,`&`,`'`,`(`,`)`,`*`,`+`,`,`,`-`,`.`,`/`,`0`,`1`,`2`,`3`,`4`,`5`,`6`,`7`,`8`,`9`

_Topic -_ `issues=<issue number>` Quand une phrase de recherche commence par un nombre, la recherche du numéro de topic apparaît comme une suggestion dans la barre de recherche ou de filtrage. Le filtre suggéré peut ressembler à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/xp3dca6w/07-number-search-phrase.png)

Bien qu'il soit possible de filtrer un tableau pour les numéros de topic avec plus que des chiffres, les topics ne peuvent être trouvés par leur numéro qu'avec ce filtre. Si plus que des chiffres sont fournis, le filtre disparaîtra du menu mais le tableau sera toujours filtré selon la phrase saisie.

Filtrage d'un ou plusieurs topics par numéro Il n'est possible de rechercher qu'un seul topic à la fois à partir de la barre de recherche ou de filtrage. Si le topic avec le numéro de topic Catenda 123 existe dans le tableau, l'URL aura `&issues=123` lorsqu'il est filtré sur le numéro de topic 123. Il est possible d'entrer plus de numéros de topic dans l'URL, par exemple : `&issues123,124,125` afficherait les trois topics s'ils existent dans le tableau. Le filtrage de plusieurs topics de cette manière n'est possible qu'en modifiant l'URL.

### 3.5 **Champs personnalisés - Nombre**

_Champ personnalisé entier -_ `custom-field-<Custom field GUID>=<Search phrase>` Si un champ personnalisé entier est activé dans le tableau de topics, le contenu des champs personnalisés entiers dans tous les topics du tableau peut être filtré avec ce filtre.

_Champ personnalisé décimal -_ `custom-field-<Custom field GUID>=<Search phrase>` Si un champ personnalisé décimal est activé dans le tableau de topics, le contenu des champs personnalisés décimaux dans tous les topics du tableau peut être filtré avec ce filtre.

### 3.6 **Champs personnalisés - Déroulant**

Si une phrase de recherche correspond au nom d'une valeur dans un filtre, le filtre qui correspond le mieux sera suggéré dans la boîte de suggestion.

_Champ personnalisé déroulant_ _-_ `custom-field-item-<Custom field GUID>=<Dropdown value GUID>` Si la phrase de recherche correspond à une valeur dans un champ personnalisé déroulant avec jusqu'à 10 valeurs, il sera suggéré de rechercher sur cette valeur déroulante.
