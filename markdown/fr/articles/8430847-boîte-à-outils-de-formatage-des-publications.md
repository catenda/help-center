# Boîte à outils de formatage des publications

> Comment les champs où les publications peuvent être faites peuvent être formatés

Les mêmes règles de formatage s'appliquent aux différentes publications dans Catenda Hub. Les publications peuvent inclure les descriptions de sujets, les descriptions d'approbation et les commentaires d'approbation. Des variations peuvent s'appliquer selon les différents accès pour modifier la publication. Catenda utilise le markdown pour formater le texte. Cela signifie que certains caractères avant et après les phrases affecteront le style du texte. Voici à quoi peuvent ressembler un en-tête de sujet et une description après leur soumission :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/01-intro.png)

## 1. Disponibilité du formatage

Il est souvent possible de voir que les champs soumis peuvent être formatés par la boîte à outils qui apparaît sous le champ lors de la modification du champ.

> **Remarque :** Zoomez suffisamment pour voir tous les outils.

Le formatage est disponible dans les champs suivants :

### 1.1 **Description et commentaire du sujet**

Modifiez la description ou le commentaire d'un sujet existant ou lors de la soumission d'un nouveau sujet pour voir la boîte à outils :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/02-topic-description-and-comment.png)

### 1.2 **Description de la demande d'approbation**

Bien que la boîte à outils n'apparaisse pas dans la description de la nouvelle boîte de dialogue de demande d'approbation, le formatage est appliqué à cette description.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/03-approval-request-description.png)

> **Remarque :** Ce champ ne peut pas être modifié après la soumission de la demande d'approbation.

### 1.3 Description de la liste de sujets

Bien que la boîte à outils apparaisse dans la nouvelle description de la liste de sujets, il est important de noter que la description n'est pas formatée lors de la soumission de la liste.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/04-topic-board-description.png)

## 2. **Pièce jointe au commentaire du sujet**

Dans les commentaires du sujet, un outil de pièce jointe est visible. Cliquez sur le bouton + dans un sujet pour ajouter une pièce jointe.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/05-topic-comment-attachment.png)

Cliquez [ici](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_0e3c0059ae) pour en savoir plus sur les pièces jointes aux commentaires.

## 3. **Formatage du texte**

Les méthodes suivantes vous permettent de formater votre texte :

### 3.1 **Gras, italique, barré**

Le formatage gras, italique et barré peut être effectué n'importe où dans une ligne et fonctionne bien avec d'autres formatages qui doivent être au début d'une ligne.

<img alt="**Ceci sera en gras** __Ceci sera aussi en gras__ *Ceci sera en italique* _Ceci sera aussi en italique_ **Ceci sera en gras _combiné avec italique_** ~~Ce texte sera barré~~" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-b49c2f10b2de.png" width="290"/>   \<->   <img alt="Ceci sera en gras​Ceci sera aussi en gras​Ceci sera en italique​Ceci sera aussi en italique​Ceci sera en gras combiné avec italiquesCe texte sera barré" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-ea38fb93f8ee.png" width="290"/>

### 3.2 **En-têtes**

L'outil d'en-tête applique des dièses/signes dièse au début de la ligne. Il existe 5 niveaux d'en-têtes supportés : Le formatage que reçoit l'en-tête dépend du nombre de dièses/signes dièse (`#`) au début de la ligne.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-c21079ec7efb.png" width="290"/>   \<->   <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-557784a5d702.png" width="290"/>

### 3.3 **Liens**

Le formatage des liens peut être effectué n'importe où dans une ligne et fonctionne bien avec d'autres formatages qui doivent être au début d'une ligne. Les liens dans les descriptions seront verts et soulignés. Leur texte peut être différent de l'URL vers laquelle pointe le lien. Les URL seront automatiquement converties en liens cliquables.

```
https://hub.catenda.com
```

deviendra [https://hub.catenda.com](https://hub.catenda.com) et

```
[Catenda Hub](https://hub.catenda.com)
```

deviendra : [Catenda Hub](https://hub.catenda.com)

> **Remarque :** Soyez prudent lorsque vous cliquez sur les liens, car bien que le texte [entre crochets] puisse afficher un lien, le lien réel (entre parenthèses) pourrait être différent. Il est recommandé de passer la souris sur un lien et de regarder où le navigateur vous redirigera avant de cliquer sur un lien.

### 3.4 **Prévention du formatage**

En enveloppant les mots dans des caractères autres que des lettres ou des chiffres, vous pouvez les faire ressembler différemment. Ce n'est pas toujours souhaité. Si vous mettez un `\` devant un tel caractère, le `\` disparaîtra. Tout formatage qui aurait été appliqué pour ces caractères cessera de fonctionner. Si vous mettez un `\` sur une ligne vide qui ne fait pas partie d'une [liste](#h_6da4949f8c), le résultat sera toujours une ligne vide aussi.

## 4. **Division du texte et ajout de structure**

Les méthodes suivantes vous permettent d'améliorer votre texte en le divisant et en ajoutant de la structure :

### 4.1 **Images**

Les images dans les descriptions peuvent avoir un lien qui y est attaché. Pour intégrer des images, vous pouvez utiliser cette syntaxe

```
![text](https://bimsync.com/img/favicon/dark-mode/favicon-32x32.png)
```

pour obtenir cette image avec le mot texte derrière elle.

![texte](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/06-images.png)

Pour que l'image s'affiche correctement, Catenda doit avoir accès au lien fourni.

> **Remarque :** \+ L'image peut être ajoutée à une description \+ L'image peut être mélangée avec du texte pour que vous ayez du texte avant et après l'image dans les mêmes commentaires ou description. \+ Les images comme celles-ci peuvent être combinées avec des tableaux et des listes. Par exemple, vous pourriez ajouter une image de coche au milieu d'une phrase/tableau au lieu de la case à cocher de formatage qui ne fonctionne qu'au début d'une phrase \- Vous ne pouvez pas garantir que le lien vers l'image restera disponible à l'avenir.

_Obtention d'un lien de document image Catenda_ Si vous cliquez avec le bouton droit sur le [bouton d'action de téléchargement après sélection d'un document](https://support.catenda.com/en/articles/4670288-actions-in-the-document-structure#h_133e2bcc57) ou cliquez avec le bouton droit sur le [bouton d'action de téléchargement de la dernière révision après ouverture d'un document](https://support.catenda.com/en/articles/9323521-actions-in-a-document), vous pouvez copier le lien de téléchargement du document. Si vous utilisez ce lien dans votre sujet comme ci-dessus, vous pourrez utiliser des documents Catenda dans les sujets.

> **Remarque :** \+ Si vous ajoutez un lien à un document image Catenda, vous pouvez ajouter des images qui n'apparaissent que sur Catenda et ne sont pas disponibles sur d'autres plateformes avec lesquelles le sujet peut être échangé. \+ En ajoutant des liens à un document image Catenda, seules les personnes ayant accès au document verront l'image. \- Si vous ajoutez un lien à un document image Catenda, il ne sera pas visible sur d'autres plateformes avec lesquelles le sujet a pu être synchronisé et aux personnes n'ayant pas accès au document.

### 4.2 **Listes**

**Listes non ordonnées** Commencez une liste non ordonnée avec une ligne vierge au-dessus, puis soit un tiret (`-`), un plus (`+`), soit un astérisque (`*`) suivi d'un espace. Insérez 4 espaces ou une tabulation au début de la ligne pour créer une sous-liste.

```
 - Premier élément - Deuxième élément     - Insérez 4 espaces au début de la ligne pour créer une sous-liste.
```

Ou

```
 + Premier élément + Deuxième élément     + Insérez 4 espaces au début de la ligne pour créer une sous-liste.
```

Ou

```
 * Premier élément * Deuxième élément     * Insérez 4 espaces au début de la ligne pour créer une sous-liste.
```

Se transformeront tous en ceci :

- Premier élément
- Deuxième élément
  - Insérez 4 espaces au début de la ligne pour créer une sous-liste.

> **Remarque :** Pour qu'une liste non ordonnée soit formatée correctement, il doit y avoir une ligne vierge au-dessus de la liste.

**Listes ordonnées** Commencez une liste ordonnée avec une ligne vierge au-dessus, un numéro, un point et un espace (`1. `) Le numéro en avant n'a pas d'importance, juste que c'est un numéro suivi d'un point. Insérez 4 espaces ou une tabulation au début de la ligne pour créer une sous-liste.

```
1. article un 2. article deux 3. article trois     4. article quatre
```

Ou

```
1. article un 1. article deux 1. article trois     1. article quatre
```

Ou

```
1. article un 10. article deux 1. article trois     1000. article quatre
```

Se transformeront tous en ceci :

1. article un
1. article deux
1. article trois

1. Article quatre

> **Remarque :** Pour qu'une liste ordonnée soit formatée correctement, il doit y avoir une ligne vierge au-dessus de la liste.

Le numéro avec lequel vous commencez n'affecte pas le début de la numérotation

```
23. vingt-trois 1. vingt-quatre 1. vingt-cinq     1. vingt-six
```

Se transformera en :

1. vingt-trois
1. vingt-quatre
1. vingt-cinq

1. vingt-six

Si vous souhaitez réinitialiser la numérotation et recommencer à partir d'un dans une deuxième liste au sein du même message, vous pouvez mettre une ligne vierge ou un [séparateur](#h_3a36cfbc61) entre les deux.

Pour [vous assurer que la liste n'est pas formatée](#h_2ec17c688b) pour que vous puissiez utiliser votre propre numérotation : Placez un caractère sur la ligne au-dessus de la liste. Un bon choix est `\` car il disparaîtra.

```
\23. vingt-trois 24. vingt-quatre 25. vingt-cinq     26. vingt-six
```

Mettez une barre oblique inverse (`\`) avant le point (`.`) :

```
23\. vingt-trois 24\. vingt-quatre 25\. vingt-cinq     26\. vingt-six
```

Se transformeront tous en :

23\. vingt-trois 24\. vingt-quatre 25\. vingt-cinq 26\. vingt-six

### 4.3 **Séparateurs**

Trois tirets `---` ou plus sur leur propre ligne créeront un séparateur :

---

### 4.4 **Listes de contrôle**

Ceux-ci peuvent être vérifiés dans la description d'un sujet. _Accès requis :_ Accès en écriture à la liste de sujets.

```
- [ ] premier article - [x] deuxième article     - [ ] article de sous-liste
```

Se transformera en ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/07-checklists.png)

Cliquez [ici](https://support.catenda.com/en/articles/5036461-check-lists-within-issues) pour regarder une courte vidéo sur la façon dont les listes de contrôle peuvent être utilisées dans le projet. Si vous écrivez` - [ ]` ou `- [x]` la case apparaîtra toujours non cochée et cochée lorsque le commentaire est soumis ou enregistré après modification.

**Cases à cocher dans les commentaires** Dans les commentaires, les cases à cocher ne peuvent être cochées que par le formatage. Les cases à cocher dans les commentaires ne peuvent pas être cochées. _Accès requis -_ Le créateur du commentaire a accès à la modification du commentaire créé

### 4.5 **Tableaux**

Le texte dans les descriptions peut être organisé en tableaux.

```
|            | Windows            ||             | |            | Type 1   | Type 2   | Sum total   | |----------- | -------- | -------- | ----------- | | **Prix**  | 500,-    | 400,-    |             | | **Quantité** | 10       | 4        |             | | **Total**    | 5 000,-  | 1 600,-  | **6 600,-** |
```

donnera ce résultat

<div class="intercom-interblocks-table-container"><table role="presentation" style="border: 1px solid #c6c9c0; border-radius: 6px; border-collapse: separate; border-spacing: 0;"><tbody><tr><td style="padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p class="intercom-align-right">Win</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p>dows</p></td><td style="border-left: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Type 1</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Type 2</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>Total général</p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Prix</b></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>500,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>400,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Quantité</b></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>10</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>4</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p></p></td></tr><tr><td style="border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>Total</b></p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>5 000,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p>1 600,-</p></td><td style="border-left: 1px solid #c6c9c0; border-top: 1px solid #c6c9c0; padding: 8px;"><p><b>6 600,-</b></p></td></tr></tbody></table></div>

### 4.6 **Blocs de code**

Vous pouvez insérer des lignes de code uniques comme ceci : Deux `` ` `` entourant du texte ressembleront à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/08-code-blocks.png)

Trois backticks ` ``` ` au-dessus et au-dessous d'un peu de texte ressembleront à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/09-code-blocks.png)

Il n'est pas possible d'ajouter des tableaux dans les blocs de code

### 4.7 **Dialecte Markdown**

Si vous souhaitez en savoir plus sur la façon dont le texte est formaté dans les commentaires et les descriptions, nous utilisons le dialecte markdown "flexmark" pour formater ce texte. Découvrez plus à propos de flexmark sur leur [page github](https://github.com/vsch/flexmark-java).

## 5. **@ Membres et équipes mentionnés**

Cliquez sur l'outil `@` ou écrivez `@` dans une description ou un commentaire pour mentionner un Membre. Après avoir tapé `@`, une liste déroulante des Membres et Équipes est affichée.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/10-mentioned-members-and-teams.png)

Parcourez la liste en commençant à taper l'email, le nom du Membre ou le nom de l'Équipe. Allez vers le haut et vers le bas de la liste avec les touches fléchées et cliquez ou appuyez sur Entrée pour sélectionner un Membre ou une Équipe. Pour qu'un Membre ou une Équipe apparaisse dans cette liste, le Membre ou l'Équipe doit avoir au minimum un accès en lecture à la liste de sujets. Après avoir sélectionné un Membre ou une Équipe dans la liste, le `@` recevra du texte supplémentaire qui peut ressembler à :

`@[<adresse e-mail de membre>]` ou `@[<nom d'équipe>]`

### 5.1 **Enregistrement ou soumission d'une mention dans un sujet**

Lorsque la description est enregistrée ou que le commentaire est soumis, les Membres concernés ayant accès à la liste de sujets reçoivent une notification. Si l'email du Membre ou le nom de l'Équipe est connu, il peut également être écrit manuellement, mais s'ils ne font pas partie de la liste de sujets, les Membres concernés ne seront pas notifiés de la mention.

**Notification lors de la mention d'un Membre** Les Membres ayant accès à la liste de sujets qui sont mentionnés reçoivent une notification indiquant qu'ils sont mentionnés dans un sujet.

**Notification lors de la mention d'une Équipe** Les Membres ayant accès à la liste de sujets qui font partie d'une Équipe mentionnée reçoivent une notification indiquant qu'une Équipe dont ils font partie est mentionnée dans un sujet.

**Notifications sur les futurs événements de sujet** Les Membres des Équipes mentionnées dans les descriptions de sujets et les commentaires reçoivent uniquement la notification lors de la description enregistrée ou du commentaire soumis.

En plus de la notification indiquant qu'ils sont mentionnés, les Membres mentionnés dans les publications sont automatiquement définis pour [suivre](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) le sujet et recevront des notifications sur les événements de sujet tels que les nouveaux commentaires et les changements de statut. C'est un excellent moyen de s'assurer que plus que le [responsable assigné](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9) et le [demandeur](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7) reçoivent les notifications concernant les futurs changements d'un sujet. Si un Membre ne souhaite plus suivre le sujet, il doit manuellement l'abandonner.

### 5.2 **Mention dans la publication**

Les mentions dans les publications peuvent être identifiées par une couleur de texte verte.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/11-mention-in-post.png)

En arrière-plan, l'ID unique du participant au projet mentionné est enregistré. C'est le nom du participant qui s'affiche dans ce texte vert. Même si le membre ou l'équipe change de nom, il restera mentionné dans la publication mais sous son nouveau nom.

Les Membres mentionnés ont un lien cliquable qui dirige vers la [page du Membre](https://support.catenda.com/en/articles/8228836-member-page) de ce Membre. Les Équipes mentionnées ont un lien cliquable qui dirige vers la [page de l'Équipe](https://support.catenda.com/en/articles/7891755-team-page) de cette Équipe.

**Membre inexistant** S'il n'y a pas de Membre dans le projet qui possède l'adresse e-mail mentionnée, la publication ressemble à ceci :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/12-mention-in-post.png)

Cela peut être dû au fait que l'email était mal formaté ou parce que le Membre ne fait plus partie du projet. Si à l'avenir un Membre avec cette adresse e-mail devient partie du projet, la publication change pour afficher le nom de ce Membre.

**Équipe inexistante** Si une Équipe a été supprimée du projet et qu'une nouvelle Équipe est créée, cette nouvelle Équipe ne sera pas mentionnée. Pour mentionner la nouvelle Équipe, la publication doit être soumise à nouveau.

## 6. **# Sujets étiquetés**

Cliquez sur l'outil `#` ou écrivez `#` dans une description ou un commentaire pour étiqueter un sujet. Après avoir tapé `#`, une liste déroulante des sujets de toutes les listes de sujets est affichée.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/13-tagged-topics.png)

Parcourez la liste en commençant à taper le titre ou le numéro du sujet. Allez vers le haut et vers le bas de la liste avec les touches fléchées et cliquez ou appuyez sur Entrée pour sélectionner un sujet. Pour qu'un sujet apparaisse dans cette liste, le Membre qui étiquette le sujet doit avoir accès à la liste contenant le sujet. Après avoir sélectionné un sujet dans la liste, le `#` recevra du texte supplémentaire qui peut ressembler à :

`#[<numéro du sujet>]`

### 6.1 **Enregistrement ou soumission d'un sujet étiquetée**

Lorsque la description est enregistrée ou que le commentaire est soumis, une relation de sujet est créée. Le sujet lié est ensuite ajouté à la liste des [sujets liés](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) dans [le menu de droite](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) du sujet.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/14-saving-or-submitting-a-tagged-topic.png)

En plus du sujet dans lequel un autre sujet a été étiquetée, le sujet étiquetée reçoit lui-même un lien de retour vers le sujet dans lequel il a été ajouté à la liste des [sujets liés](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) dans [le menu de droite](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/15-saving-or-submitting-a-tagged-topic.png)

Le lien de sujet peut ensuite être supprimé du sujet contenant le sujet étiquetée dans la description ou du sujet qui a été étiquetée en accédant à chaque sujet et en modifiant la liste des [sujets liés](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) dans [le menu de droite](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue).

### 6.2 **Sujet étiquetée dans la publication**

Les sujets étiquetées peuvent être identifiés en premier lieu par un cercle avec la couleur du statut actuel du sujet étiquetée ainsi que le nom de ce statut. Après cela, le titre du sujet est affiché suivi du numéro du sujet.

Avec les cases à cocher, les sujets étiquetées qui sont fermés comptent vers la progression dans la barre de progression affichée vers le haut, tandis que les sujets étiquetées qui sont ouverts comptent vers le nombre total d'articles pour lequel la progression est comptabilisée.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/16-tagged-topic-in-post.png)

Les sujets étiquetées ont un lien cliquable qui ouvre le sujet étiquetée dans sa liste de sujets.
