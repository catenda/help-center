# Dépannage du connecteur de bureau - Tous les dossiers n'ont pas été téléchargés

Dans cet article, vous trouverez des informations sur une erreur spécifique qui se produit lors de l'utilisation du [connecteur de bureau Catenda](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector). Voir [ici](https://app.intercom.com/a/apps/areracg3/knowledge-hub/all-content?activeContentId=11844906&activeContentType=article&editorMode=view&native_content=false) pour d'autres problèmes de dépannage du connecteur de bureau.

Dans la tâche elle-même, on peut voir ce qui suit :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/01-intro.png)

`Tous les dossiers n'ont pas été téléchargés, cliquez pour voir les erreurs.`

## 1. **Caractères non pris en charge**

Dans ce cas, le fichier journal affichera l'erreur suivante :

`La syntaxe du nom de fichier, du nom de répertoire ou de l'étiquette de volume est incorrecte.`

Les noms de documents peuvent être limités par une convention de nommage dans Catenda. Les dossiers ne peuvent pas être limités. Sans l'utilisation d'une convention de nommage, les documents portant n'importe quel nom peuvent être téléchargés. Dans ce cas, Catenda n'a peut-être pas pu enregistrer l'extension de fichier du document. Les dossiers portant n'importe quel nom peuvent être créés. Il se peut donc que le connecteur de bureau essaie de créer un fichier ou un dossier avec un caractère qui n'est pas autorisé dans un chemin d'accès dans Windows.

Les problèmes typiques surviennent avec les caractères suivants : `<` - inférieur à `>` - supérieur à `:` - deux-points `\"` - guillemet `|` - barre verticale ou tuyau `?` - point d'interrogation `*` - astérisque

Pour trouver une liste complète de ce qui est réservé dans Windows, consultez : [https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file](https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file)

## 2. **Dossier manquant ou chemin d'accès réseau**

Dans ce cas, le fichier journal affichera l'erreur suivante :

`Erreur : Le chemin d'accès réseau est introuvable. : '<path>'`

Dans cette situation, le transfert échoue immédiatement. Cela se produit parce que le programme tente d'accéder à un dossier qui n'est plus accessible. Comme le "chemin" est complètement cassé, le programme ne peut même pas commencer le téléchargement. Il y a trois raisons principales pour lesquelles votre dossier s'est transformé en "impasse" :

### 2.1 **1. Le dossier manquant (le plus courant)**

Le dossier local qui a été précédemment sélectionné a été déplacé, renommé ou supprimé. En accédant à l'emplacement du dossier dans l'Explorateur de fichiers, le dossier n'est pas présent. Le connecteur de bureau tente de sauvegarder votre fichier, ne trouve "rien" et s'arrête.

### 2.2 **2. Le lien symbolique cassé (La redirection cachée)**

Un lien symbolique ressemble à un dossier normal mais agit comme un "panneau indicateur" permanent qui redirige Windows vers un autre emplacement (comme un serveur de bureau). Lorsque vous tentez de l'ouvrir, l'erreur suivante s'affiche dans une fenêtre contextuelle :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/02-2-the-broken-symbolic-link-the-hidden-redirect.png)

`L'emplacement n'est pas disponible... Le chemin d'accès réseau est introuvable.`

**Comment les distinguer :** Comme les fichiers .lnk, les liens symboliques auront la petite flèche de raccourci bleue dans le coin inférieur gauche de l'icône du dossier ou cliquez avec le bouton droit sur le raccourci et sélectionnez Propriétés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/03-2-the-broken-symbolic-link-the-hidden-redirect.png)

Dans l'onglet Général, les champs nom et cible sont grisés :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/04-2-the-broken-symbolic-link-the-hidden-redirect.png)

**Pourquoi cela échoue** Le "panneau indicateur" se trouve sur votre ordinateur, mais la destination (comme un lecteur `Z:` ou un serveur) est déconnectée.

### 2.3 **3. Le raccourci Windows cassé (fichier .lnk)**

Un raccourci Windows standard est un petit fichier qui "pointe" vers un dossier ailleurs. Il peut s'agir de liens vers un dossier de votre propre disque dur ou vers un dossier d'un serveur de bureau distant.

**Comment les distinguer :** Comme les liens symboliques, les raccourcis de dossier et de lecteur auront la petite flèche de raccourci bleue dans le coin inférieur gauche de l'icône du dossier ou cliquez avec le bouton droit sur le raccourci et sélectionnez Propriétés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/05-3-the-broken-windows-shortcut-lnk-file.png)

Dans l'onglet Général, regardez le champ Cible : _Raccourci local_ La cible commence par une lettre de lecteur (par exemple, `C:\\Utilisateurs\\...` ou `D:\\Données`).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/06-3-the-broken-windows-shortcut-lnk-file.png)

_Raccourci réseau_ La cible commence par un chemin d'accès au serveur (par exemple, `\\\\NomServeur\\Dossier`) ou une lettre de lecteur réseau mappée (par exemple, `Z:\\DonnéesProjets`).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/07-3-the-broken-windows-shortcut-lnk-file.png)

Comportements différents lors du double-clic Windows gère un raccourci local "cassé" beaucoup plus rapidement qu'un raccourci réseau "cassé".

**Raccourci local (L'erreur "Supprimé") :** Si le dossier sur votre ordinateur a été supprimé, Windows le sait immédiatement. Lorsque le raccourci est double-cliqué, l'erreur suivante s'affiche instantanément :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/08-3-the-broken-windows-shortcut-lnk-file.png)

**`L'élément auquel ce raccourci fait référence a été modifié, déplacé ou supprimé.`**

**Raccourci réseau (L'erreur "Suspendu") :** Si le raccourci pointe vers un serveur de bureau et que vous êtes hors ligne (ou hors VPN), Windows ne sait pas immédiatement que la destination est manquante. Il tentera d'abord de "trouver" le serveur sur le réseau. Votre curseur de souris peut se transformer en cercle de chargement, et la fenêtre peut "se suspendre" ou geler pendant 30 à 60 secondes avant d'afficher enfin :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/09-3-the-broken-windows-shortcut-lnk-file.png)

**`Le lecteur ou la connexion réseau auquel le raccourci fait référence n'est pas disponible.`**

Si le connecteur de bureau est invité à utiliser l'un de ces raccourcis alors que la cible est manquante ou que le réseau est arrêté, le programme finira par "expirer" en attendant que Windows trouve le chemin. Parce que le connecteur de bureau ne peut pas trouver une destination valide pour commencer le travail, il s'arrête et signale l'erreur.

### 2.4 **Comment le corriger**

**Identifier la déconnexion** Essayez d'ouvrir le dossier de destination dans l'Explorateur Windows. Si le dossier de destination est manquant, soit un nouveau dossier doit être créé à cet emplacement, soit un dossier différent doit être sélectionné dans le connecteur de bureau.

**Reconnecter ou Resélectionner** Si une erreur "Chemin d'accès réseau introuvable" ou "Lecteur indisponible" s'affiche, confirmez la connexion au chemin d'accès réseau ou au lecteur. Allez à "Cet ordinateur" et assurez-vous que vos lecteurs réseau (comme `Z:`) sont actifs. Vérifiez si les lecteurs USB externes ou les disques durs externes sont correctement connectés. S'ils ont un X rouge, double-cliquez dessus pour les reconnecter. Si le lecteur réseau n'est pas actif et que vous savez quel réseau le lecteur est sur, reconnectez-vous au réseau soit en branchant un câble, soit en rejoignant via wifi ou lors de l'utilisation d'un VPN, vérifiez que le VPN est actif. Si le lecteur n'est plus disponible, sélectionnez un dossier de destination différent dans le connecteur de bureau qui est disponible soit sur l'ordinateur local, soit sur le réseau.

**Supprimer/renommer et recréer** Si un dossier local ou un raccourci reste "bloqué" (vous le voyez, mais ne pouvez pas l'ouvrir) même après un redémarrage : Renommez le dossier ou le fichier raccourci problématique (par exemple, renommez `DonnéesProjets` en `DonnéesProjets_OLD`) ou supprimez-le. Créez un tout nouveau dossier standard portant le même nom. Redémarrez le transfert. Le connecteur de bureau détectera le dossier frais et sain et reprendra le fonctionnement normal.

**Pourquoi aucun dossier temporaire n'a-t-il été créé à la place du dossier manquant ?** Dans d'autres situations, le connecteur de bureau crée un dossier avec `_restricted` ajouté au nom lorsque les choses tournent mal. Cependant, il existe une différence technique dans la façon dont Windows gère les emplacements "manquants" :

Le dossier `_restricted` n'est créé que si le dossier est "physiquement" là mais "verrouillé" (comme une porte qui est verrouillée). Dans ce cas, le programme peut voir la porte et décide de construire une nouvelle (`_restricted`) à côté.

Dans le cas du chemin manquant, c'est différent. Le dossier n'est plus là ou le "panneau indicateur" (lien symbolique) qui a été sélectionné pointe vers un emplacement vide. Pour le programme, ce n'est pas seulement verrouillé, la "pièce" entière manque du bâtiment. Parce qu'il n'y a pas de "porte" pour commencer, le programme ne peut pas créer une version `_restricted` et doit s'arrêter.

## 3. **Point de montage manquant**

Dans ce cas, le fichier journal affichera l'erreur suivante :

`Erreur : Impossible de trouver une partie du chemin '<path>'.`

Si le dossier ne peut pas être ouvert, Windows essaie de suivre le "panneau indicateur" vers un emplacement réseau et l'erreur suivante s'affiche :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/10-missing-mount-point.png)

`<Path> n'est pas accessible.`
`Le chemin d'accès réseau est introuvable`

Dans cette situation, le connecteur de bureau crée automatiquement un nouveau dossier avec "\_restricted" ajouté au nom (par exemple, `DonnéesProjets_restricted`).

Cela se produit lorsqu'un dossier sur l'ordinateur est en réalité un "point de montage" (une porte) vers un autre lecteur. Les exemples d'autres lecteurs peuvent inclure :

- Clé USB,
- Disque dur externe
- Volume réseau actuellement déconnecté.

Windows "se souvient" que le dossier existe, mais comme le lecteur physique est manquant, le dossier devient un "Fantôme". Le connecteur de bureau détecte que le dossier est là mais ne peut pas y écrire. Pour éviter la perte de vos données, un dossier fantôme est créé avec le suffixe `_restricted` pour que vos fichiers aient un endroit sûr où atterrir.

Voici quelques situations typiques dans lesquelles cela peut se produire :

- Le dossier a été mappé sur un lecteur (comme `D:`) qui a été débranché.
- Le dossier pointe vers un partage réseau (comme `Z:`) qui est hors ligne ou nécessite un VPN.
- Un service cloud (Dropbox, OneDrive ou autres services de synchronisation d'outils de collaboration) a créé un dossier "placeholder" qui n'est pas actuellement actif.
- Un outil de sécurité d'entreprise "protège" le dossier pour l'empêcher d'être modifié par des applications tierces.

Pour vérifier si votre dossier est un "Fantôme", cliquez avec le bouton droit sur le dossier et sélectionnez Propriétés.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/11-missing-mount-point.png)

Regardez le champ Type dans l'onglet Général : Un dossier normal dira "Dossier" alors qu'un dossier fantôme dira "Volume monté".

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/12-missing-mount-point.png)

Lorsque le dossier monté est double-cliqué, l'erreur suivante s'affiche instantanément :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/3s5dragb/13-missing-mount-point.png)

**`L'emplacement n'est pas disponible`** ou

**`Le chemin d'accès réseau est introuvable`** `<Path> n'est pas disponible donc le lien est cassé`

### 3.1 **Comment le corriger**

Recréer manuellement le dossier Si le dossier reste "bloqué" même après un redémarrage :

1. Renommez le dossier problématique (par exemple, renommez `DonnéesProjets` en `DonnéesProjets_OLD`).
2. Créez un tout nouveau dossier portant le nom d'origine (`DonnéesProjets`).
3. Le connecteur de bureau détectera le dossier frais et sain et reprendra le fonctionnement normal sans le suffixe `_restricted`.

**Reconnecter le matériel ou le réseau** Allez à "Cet ordinateur" et assurez-vous que vos lecteurs réseau (comme `Z:`) sont actifs. Vérifiez si les lecteurs USB externes ou les disques durs externes sont correctement connectés. S'ils ont un X rouge, double-cliquez dessus pour les reconnecter. Si le lecteur réseau n'est pas actif et que vous savez quel réseau le lecteur est sur, reconnectez-vous au réseau soit en branchant un câble, soit en rejoignant via wifi ou lors de l'utilisation d'un VPN, vérifiez que le VPN est actif. Si le lecteur n'est plus disponible, sélectionnez un dossier de destination différent dans le connecteur de bureau qui est disponible soit sur l'ordinateur local, soit sur le réseau.

**Supprimer/renommer et recréer** Si un dossier local ou un raccourci reste "bloqué" (vous le voyez, mais ne pouvez pas l'ouvrir) même après un redémarrage : Renommez le dossier ou le fichier raccourci problématique (par exemple, renommez `DonnéesProjets` en `DonnéesProjets_OLD`) ou supprimez-le. Créez un tout nouveau dossier portant le nom d'origine (`DonnéesProjets`). Redémarrez le transfert. Le connecteur de bureau détectera le dossier frais et sain et reprendra le fonctionnement normal sans le suffixe `_restricted`.
