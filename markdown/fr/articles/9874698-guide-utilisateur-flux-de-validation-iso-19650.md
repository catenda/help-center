# Guide Utilisateur - Flux de Validation (ISO 19650)

La série ISO 19650 est une norme internationale de bonnes pratiques qui définit les processus de gestion de l'information dans le contexte plus large de la transformation digitale dans le secteur de la construction.

De nombreux acteurs du secteur de la construction ont adopté la norme ISO 19650 pour gérer les processus de livraison et d'approbation des documents dans les projets.

Cet article contient des informations sur les sujets suivants :

_[Cycle de vie d'un document](#h_5fd5f206e5) - [Configuration](#h_a29d778284) - [Onglets des documents](#h_6380765edc) - [Paramètres de validation](#h_76c8842f25) - [Étapes du flux de validation](#h_d62f911af7) -_ _[Désactivation du flux de validation](#h_9a2d33d0ed) -_ _[Avantages](#h_a74182326e)_

## **Cycle de vie d'un document**

Selon la norme ISO, un document peut avoir quatre états différents :

🏗️ **Travail en cours (WIP) :** Fichiers sur lesquels l'utilisateur travaille et qui sont constamment mis à jour dans son environnement local. Ces fichiers ne sont pas déposés sur Catenda.

👥 **Partagé :** Fichiers prêts à être partagés avec les autres membres du projet afin d'assurer la coordination et l'examen final des différents corps de métier et/ou spécialistes. Ces fichiers sont déposés sur Catenda et envoyés aux parties concernées pour examen et approbation.

📰 **Publié :** Fichiers coordonnés, finalisés et acceptés en tant que produits livrables contractuels. Ces fichiers ont fait l'objet d'un processus d'examen et sont jugés "prêts pour l'étape suivante (construction, livraison, devis quantitatif, permis de construire, etc.)"

📦 **Archivé :** L'information a été utilisée et peut être archivée afin de rester disponible si nécessaire par la suite (audit, création du dossier des travaux réalisés, etc.).

### 

**États d'un document (ISO 19650):**

![](https://downloads.intercomcdn.com/i/o/1201587102/dd062cd6f0668da781204f25/AD_4nXdxhgqhSMUAx3mvWCp_YY0Reke_AusmPHugivHaunwEyvVFnaC5Qs_xDThI3kiGPWYw6psdrUzS2Xa7U4k-HqQGc1ALlZpZyVTpzUivHHj4fvjLWAy_yq7cIvFkz20WsBfLvGcIqQUafYgdYxnVl6hQDpsV?expires=1781092800&signature=b1263852427165b95b01ed0ac6278321a1a6f5c6f05b850db8b7833c221ee726&req=dSInF8x2moBfW%2FMW3nq%2BgTdx%2Fx%2BBm8NOJ7dpGXwJ9oHGVHo%2FO1Wcfwjwn9Zi%0ABi0eej2vS%2BNB%2Ftw%2FIrNVk0HhsVQ%3D%0A)

### **Flux de Validation sur Catenda Hub:**

![](https://downloads.intercomcdn.com/i/o/1201587097/e18091509f2f186328797838/AD_4nXc-sz_yq5zZbwOV4LCV4zitdSXG7nBIg4EFbjXAXjAINfj0aDYDH27PINzlD-2NnwvpyM2H0mc28NMqEoaURHouvFXQGTdiWnr56HSyfTZGgs98NZVETiEfakzwcWQsQdMq7MIXGppFOe9rF4KaYscZB-U_?expires=1781092800&signature=2ea83e75b9d39096ef9fe7cbe5b644ee031898df6d091c2d842346b7ec6a6db0&req=dSInF8x2moFWXvMW3nq%2Bgb13oFC6bdUU7DqX5Nw8CVsBTF5thY%2FY2qj%2BiEDe%0AH1CjpWA2oemJq4bfHVSkqhPfEFo%3D%0A)

### 

## **Configuration du Flux de Validation**

L'activation et la configuration du flux de validation est réservée aux administrateurs de projet.

1. Dans les paramètres du document, naviguez jusqu'au Flux de Validation (Statut du workflow) et activez les "statuts partagés".

    <div class="intercom-container"><img src="https://downloads.intercomcdn.com/i/o/1178797115/8f4c7d83c220e1a8fe3528b2/image.png?expires=1781092800&amp;signature=14a7e338baf9119a8b2209541cf08076e04864d5c71047025a7ece8914ee5313&amp;req=dSEgHs53moBeXPMW3nq%2Bgf5xkZWPxPTjOEqSMsnokvN63PTnVEnAWMOWrcAy%0AiX9F0ODa5gjnq3GZY%2FNIt5svJ2s%3D%0A"/></div>

1. Définissez les statuts partagés et publiés à utiliser dans le projet.

    <div class="intercom-container"><img src="https://downloads.intercomcdn.com/i/o/1178802846/1302b0cd9163957bcfc9426d/image.png?expires=1781092800&amp;signature=8ba097f2269684ac5b7c25a00a52dd924bb587c4b72db3e01e4911e3b84f2b6b&amp;req=dSEgHsF%2Bn4lbX%2FMW3nq%2Bge%2FsFVcwAuYrCcfyzUUEfuoc4thu%2FCmpHxO99z%2B6%0AJ9cGBR9L99XqOxcqmQwo%2FKyA0%2F8%3D%0A"/></div>

1. Définissez le statut partagé par défaut pour les nouvelles révisions. Ce statut sera défini par défaut pour tous les nouveaux dépôts de documents sur la plateforme.

    <div class="intercom-container"><img src="https://downloads.intercomcdn.com/i/o/1178803801/1747b7b8c7d76f3dddbbfe88/image.png?expires=1781092800&amp;signature=e799c7e6ff3facf036b3bc0b95b77a2499257a73273d5e9a8636ea7de9981a68&amp;req=dSEgHsF%2BnolfWPMW3nq%2BgdaXG6x1PMxGkb8PvocbWQ8iVKGQavbXWek5XHyG%0AJozdIomWpNe7xP2s3B0Skh8GVtc%3D%0A"/></div>

## **Onglets des documents**

L'onglet "Espace de travail" est l'endroit où tous les chargements de nouvelles révisions ont lieu et l'onglet "Publié" est l'endroit où les révisions publiées sont exclusivement affichées.

![](https://downloads.intercomcdn.com/i/o/1201587093/a19faae184df563d2d0b763e/image.png?expires=1781092800&signature=731849f2669f8ab2d8a6709da2b41d5747efe20b12c0eebdd61f89f90520d0e5&req=dSInF8x2moFWWvMW3nq%2BgWzPmAi43CLUReUH3adIioOiJ67dOYRue80mVXLc%0AnNKKGIy4Vt%2FPMiVCCeFmr1W3wKs%3D%0A)

Voici quelques-unes des fonctionnalités disponibles :

- Charger de nouvelles révisions partagées. Celles-ci prennent par défaut le statut partagé dans la configuration des nouvelles révisions.

    <div class="intercom-container"><img src="https://downloads.intercomcdn.com/i/o/1178813626/b700d6f0f545826c6c94be54/image.png?expires=1781092800&amp;signature=eef60b7d24f9b9f88c69725d99c1f2d8b3476f1cffbb2ffea91324ad7b6dcc04&amp;req=dSEgHsF%2FnoddX%2FMW3nq%2BgaVPz8JiE%2BqSXKDYmlMzR0BgtKLOHM2dmmEArf%2F0%0A2BYRvokNO2dtY5sk%2BtFAvslFUQY%3D%0A"/></div>

- Publier des révisions partagées. Pour publier une révision partagée, il faut disposer des droits d'accès nécessaires.

    <div class="intercom-container"><img src="https://downloads.intercomcdn.com/i/o/1178818074/16b8b77b4ecca71f192b3e32/image.png?expires=1781092800&amp;signature=f7914eb3b7cc2832ac57614f09bf4d7ea75b04d499f04369142269737cccb068&amp;req=dSEgHsF%2FlYFYXfMW3nq%2BgZ2lpn0DoUjiXFWDMiR%2BeTACrpYvYdAvfO3il7UJ%0AyGKIZ7f3GbR%2FPlDdfa7D1UXHmX8%3D%0A"/></div>

- Les droits d'accès pour la publication et la visualisation des révisions partagées peuvent être accordés dans les paramètres de contrôle d'accès d'un dossier ou d'un document.

    <div class="intercom-container"><img src="https://downloads.intercomcdn.com/i/o/1178822859/a43b3f6b85d6ba192fa56c30/image.png?expires=1781092800&amp;signature=dae65ddfa5416bbb33f4dc2bc88c8d3cd8b96beb05eb3f4af42c6d54b5c09057&amp;req=dSEgHsF8n4laUPMW3nq%2BgbsVoecif30b3Gam80vpKN9YGx5JWY1zMrizhJqZ%0AURquQYJSBg%2FlwsK0Rd0AaZztfsk%3D%0A"/></div>

- Les cases des révisions partagées n'ont pas besoin d'être cochées si l'accès en lecture seule est configuré. Les utilisateurs avec cet accès pourront changer le statut des révisions partagée et les visualiser. Les utilisateurs sans ces accès ne pourront pas voir les révisions partagées mais pourront voir les révisions publiées si elles existent dans le document.

    _Par défaut_ - Coché

- Les cases des révisions publiées peuvent être cochées s'il y a au moins un accès d'écriture qui est configuré. Les utilisateurs avec ces accès seront en mesure de publier des révisions partagées et de changer leur statut. Les utilisateur sans ces accès pourront toujours voir les révisions publiées mais ne pourront pas changer leur statut.

    _Par défaut_ - Décoché

- Les dernières révisions sont listées dans l'onglet de l'espace de travail, qu'elles soient partagées ou publiées. Les révisions partagées ont un numéro de sous-révision (e.g. #0.1, #2.3, #4.1), tandis que les révisions publiées ont un numéro de révision majeure ( #1, #2, #3 etc.)

    <div class="intercom-container"><img src="https://downloads.intercomcdn.com/i/o/1178837744/20d8bdd3b298fedac27459f9/image.png?expires=1781092800&amp;signature=d4e288f428ac6bf1d93d2ca580b2d7a28edc41a78a4cfc0de24d60f428eb751a&amp;req=dSEgHsF9moZbXfMW3nq%2BgZHlR7dvV4o1hzqctwRKfXfdnYihi0IpQL4CDmzj%0Aq7G5DgtKNLtNaF1pU6QsA9syIpQ%3D%0A"/></div>

- Quand vous cliquez sur un document pour l'ouvrir dans l'onglet "Espace de travail", vous verrez la dernière révision du document qui peut être soit une révision partagée ou une révision publiée.
- L'onglet publié ne répertorie que la dernière révision publiée, ce qui signifie que les révisions partagées les plus récentes ne sont pas répertoriées ici.

    <div class="intercom-container"><img src="https://downloads.intercomcdn.com/i/o/1178825201/afe0228a33f10610c791af57/image.png?expires=1781092800&amp;signature=7e64dadbb5adcc5228d04c8eb8e61034ce3f449c75cbb98e1f3030895ff381a8&amp;req=dSEgHsF8mINfWPMW3nq%2BgVEMHZwrInPrEBw7XsaSZ10L8o%2FlrmgzxDd3Y%2BEd%0AfDLrO9ZLzp6XU95uZ%2BykGZmdwyA%3D%0A"/></div>

- Après ouverture d'un document, you pourrez voir l'information de la révision actuelle dans le [menu d'information à droite](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision).
- Vous pourrez ici publier la révision actuelle via l'action "Publier".

    _Accès requis_ - Cocher la case "Révisions partagées" dans le contrôle d'accès du document.

- Le statut d'une révision partagée peut être changé pour un autre statut de révision partagée.

    _Accès requis_ - Accès en lecture seule et la case cochée pour les révisions partagées dans le contrôle d'accès du document.

- Le statut d'une révision publiée peut être changé pour un autre statut de révision publiée.

    _Accès requis_ - Accès en écriture et la case cochée pour "Publier" dans le contrôle d'accès du document.

    <div class="intercom-container intercom-align-center"><img height="865" src="https://downloads.intercomcdn.com/i/o/areracg3/1208325230/a69cd3dc7b192806885d25ea59a8/image.png?expires=1781092800&amp;signature=d0bb215e4281e111e5762d9820e60b94c9743dd6c8b7c11d42279676e8140813&amp;req=dSInHsp8mINcWfMW3nq%2BgRfWyEfYxHzmMFbBU0EmK2FN%2F6wLMDw9bbGDpjxH%0APqOrpMc0nLlsZi%2FCuDFQn9wblPI%3D%0A" style="height: auto;" width="667"/></div>

- Si vous cliquez sur la le menu déroulant des révisions, vous trouverez tout [l'historique des révisions](https://support.catenda.com/en/articles/8302244-right-menu-of-a-revision#h_6838c6ad71).
Vous trouverez ici une vue d'ensemble de toutes les révisions du document. Vous pourrez également visualiser quelles sont les révisions partagées qui ont été publiées pour se transformer en révision publiée grâce au lien vert entre la révision partagée et la révision publiée.

    <div class="intercom-container"><img height="1146" src="https://downloads.intercomcdn.com/i/o/areracg3/1208322023/8b79e66b02a67d950bb54d33c1aa/image.png?expires=1781092800&amp;signature=d1ac5ca86ed243a0c6b58515ed9a4aec47dff2591e0d971816e3dd0857c6a04d&amp;req=dSInHsp8n4FdWvMW3nq%2BgZjvSDSuFOoja3Qs11%2BNqTI8cg50Atj40px8T1f8%0A86dioGDi7K3lFmXkKfsyGBUWj8I%3D%0A" style="height: auto;" width="2396"/></div>

## **Paramètres du flux de validation**

1. Les droits d'accès à la configuration des statuts des documents peuvent être configurés depuis [l'onglet des paramètres du projet](https://support.catenda.com/en/articles/4670273-project-settings-page) :

    <div class="intercom-container"><img height="678" src="https://downloads.intercomcdn.com/i/o/areracg3/1211347568/082eb05dc3b18bf896b0aa148431/image.png?expires=1781092800&amp;signature=d7f11d11f4522d76f1afc39c4fa3c1abcf07d65ea6866337afc4f9aec43ea4a9&amp;req=dSImF8p6moRZUfMW3nq%2BgWPlnxx3jrC6fMrF99grkWaNrp00TWDQdpt0O4gd%0AVlMGdQrCecjFzy0uRBOfB7Z9eqY%3D%0A" style="height: auto;" width="1918"/></div>

1. Les statuts des documents peuvent ensuite être [configurés](https://support.catenda.com/en/articles/7831371-document-settings#h_e6f3ffdbff) depuis les paramètres de la section des documents :

    <div class="intercom-container"><img height="852" src="https://downloads.intercomcdn.com/i/o/areracg3/1211364420/5d6103d8c487ef0b43f8275be5e3/image.png?expires=1781092800&amp;signature=284c9ac52ff4057d8c2333ea2f752321f7ac99e4db9fe32cf5b00a50a2ab7aa1&amp;req=dSImF8p4mYVdWfMW3nq%2BgSPBqKtQx3mDN2RUxAGHVK4Zm%2BCeuCGeKk2Kpqj6%0Ao7QTpegJSCq1qQ64o2dJOULG6GY%3D%0A" style="height: auto;" width="1918"/></div>

1. Enfin, ces statuts des documents peuvent être attribués à des "Statuts de la revue du document", accessibles depuis le bouton à droite du "+" vert en haut à droite dans la [section Validations](https://support.catenda.com/en/articles/8349340-approvals-page). Il est également possible de configurer ici un gabarit de Sujet.

    <div class="intercom-container"><img height="532" src="https://downloads.intercomcdn.com/i/o/areracg3/1211362235/ff7ea475a572749cba4247518058/image.png?expires=1781092800&amp;signature=ed641b32ce2b29ed26475385e36b8015832ce0fcc27dc7dd50942cd3942ef84f&amp;req=dSImF8p4n4NcXPMW3nq%2Bgcv5xnTzfFrfmLPu%2Fh%2FbaP0DptD%2Bm8oeC8vRpvPF%0AzFKQmL79JK7RcPLygqoKQ0CoqM4%3D%0A" style="height: auto;" width="1905"/></div><div class="intercom-container"><img height="620" src="https://downloads.intercomcdn.com/i/o/areracg3/1211362345/59c0a70c13879eacc2b08c0db623/image.png?expires=1781092800&amp;signature=9c4b2b7d82aee40c7c1baccfdf0c17735a34889d51b5680e5824f7502d8f4289&amp;req=dSImF8p4n4JbXPMW3nq%2BgQL5wc3pBXVaAiE%2FNNg7wwK7Y9rNWq0G7M1E0M6c%0AgGNJ2NG26plHpZW4oC7Y%2F2YpO2M%3D%0A" style="height: auto;" width="945"/></div>

## **Étapes du flux de validation**

1. Une demande d'approbation nomine un "Éditeur" (personne responsable de prendre la décision finale concernant the publication), et un ou plusieurs "Examinateur(s)", responsables de valider (ou non) une série de documents.
1. Chaque examinateur décide si un document partagé est "Approuvé", "Approuvé avec commentaires", ou "Rejeté".
1. À la fin du flux de validation, l'Éditeur choisira le résultat final de l'approbation, en choisissant les documents qui seront publiés.
1. Depuis les paramètres du flux de validation, les Sujets liés aux documents peuvent être créés automatiquement afin de garder une trace du processus par la suite.

Une démonstration détaillée de ces étapes est présentée dans ce tutoriel :

[Vidéo YouTube](https://www.youtube.com/embed/lDWKXWTtegU?rel=0)

## **Désactivation du flux de validation**

Si vous voulez désactiver le flux de validation, vous pouvez le faire en cliquant sur le bouton radio dans les [paramètres des documents](https://support.catenda.com/en/articles/7831371-document-settings).

![](https://downloads.intercomcdn.com/i/o/areracg3/1211320852/fabe4264bf2cdfecc0057b037951/image.png?expires=1781092800&signature=bc6763c7fd4e731e7a3e84ae43ce5a671efc5afa9916c7c308263eeb5e54a5ce&req=dSImF8p8nYlaW%2FMW3nq%2BgfCzgDD46saP91257vrr1SOiI6CWuxvglhq7sbpT%0AxLwXZRZU7Q9Mv1WjxQqXqZJqL9o%3D%0A)

Les onglets "Publié" et "Espace de travail" dans la section des documents disparaîtrons.

Les documents déposés pendant que le flux de validation n'est pas activé while the status seront déposés se trouveront dans l'onglet "Publié" une fois que le flux de validation est activé.

## **Avantages**

- L'onglet publié sert de zone désignée pour les documents contractuels. Les membres du projet peuvent facilement trouver des documents vérifiés.
- Les documents sont validés avant d'être publiés
- Vous pouvez configurer votre processus de livraison basé sur la norme ISO 19650 plus facilement.
- Les documents de coordination/collaboration sont séparés des documents contractuels.
- Les révisions partagées peuvent être sélectionnées et téléchargées, alors que les "brouillons" ne pouvaient être téléchargés qu'un par un.
