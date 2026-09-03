# Vérification des révisions via code QR sur les PDF

Imprimez les révisions de documents avec des codes QR générés sur papier physique afin que les membres du projet puissent vérifier si le document qu'ils ont en main est toujours à jour.

Les dossiers configurés peuvent être identifiés par le badge d'engrenage sur l'[icône de dossier](https://support.catenda.com/en/articles/8466850-columns-on-the-documents-page#h_6af15c36b3). Voici à quoi peut ressembler une révision avec un code QR généré :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/01-intro.png)

## 1. **Configuration du dossier**

L'estampillage du code QR peut être [activé pour les dossiers configurés](https://support.catenda.com/en/articles/7831371-document-settings#h_166a269870) sur la page des documents. _Accès requis :_ Administrateur

Dans les dossiers configurés, les nouvelles révisions PDF dans les documents sont traitées lors du téléchargement. Catenda analyse le document pour trouver l'image placeholder du code QR ci-dessous. Si le placeholder est correctement identifié, un code QR est généré pour la révision. _Accès requis :_ Accès en écriture au document

### 1.1 **Attribuer un code QR**

Pour attribuer l'estampillage du code QR à un dossier, accédez aux [paramètres du document](https://support.catenda.com/en/articles/7831371-document-settings) qui se trouvent en tant que sous-page de la [page des documents](https://support.catenda.com/en/articles/8204673-documents-page). Dans les paramètres du document, développez le [menu de configuration du dossier](https://support.catenda.com/en/articles/7831371-document-settings#h_6672c14d90). Voici à quoi peut ressembler le menu de configuration du dossier :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/02-assign-qr-code.png)

Vers le bas, vous pouvez trouver le menu déroulant Attribuer un code QR. Cliquez sur le menu déroulant et sélectionnez Oui pour configurer ce dossier.

**Héritage de configuration** Si une configuration a été définie dans un dossier parent, tous ses sous-dossiers hériteront de sa configuration.

## 2. **Placement du code QR placeholder**

Comme mentionné dans l'introduction de cet article, pour qu'un code QR soit généré sur une révision téléchargée dans un dossier configuré, Catenda recherchera l'image placeholder du code QR. L'image placeholder du code QR peut ressembler à ceci :

<p class="intercom-align-center no-margin">[<img alt="Catenda QR-Code placeholder" src="https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/inline-8c4db2f4912c.png" width="150"/>](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk)</p>

Cliquez [ici](https://hub.catenda.com/share/collections/cZcmrt4ZYV9iatVmd5H0j9Xsp6WFvuf7UfIYYTkZ7SUk) pour télécharger le placeholder du code QR

> **Avertissement :** Ne copiez/collez pas cette image et ne l'enregistrez pas. L'image peut sembler identique sur le dessin mais ne sera pas reconnue.

Cliquez [ici](https://support.catenda.com/en/articles/9360508-qr-code-on-pdfs-in-catenda) pour en savoir plus sur comment placer le placeholder sur un PDF. Voici à quoi peut ressembler le placeholder lorsqu'il est placé dans le cartouche d'un dessin :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/03-qr-code-placeholder-placement.png)

## 3. **Téléchargement d'une révision avec un placeholder**

Téléchargez une nouvelle révision d'un PDF avec le placeholder dans un dossier avec attribution de code QR. Ceci s'applique uniquement aux révisions publiées !!! Les brouillons ou les PDF partagés n'obtiendront un code QR généré que lorsqu'ils auront été publiés.

### 3.1 **Génération de code QR pour la révision**

Une fois que le placeholder du code QR est placé, le PDF peut être téléchargé en tant que nouvelle révision dans le dossier configuré. Pendant le téléchargement, Catenda traite les images du document.

**Exigence relative aux octets** Les octets corrects correspondant aux pixels noirs et blancs du placeholder du code QR Catenda doivent être présents dans le bon ordre.

**Exigence dimensionnelle** L'image doit avoir une largeur et une hauteur minimales de 2 cm sur 2 cm.

**Exemple de code QR généré** Voici à quoi peut ressembler le cartouche dans l'exemple ci-dessus après que le PDF ait été traité et qu'un code QR ait été ajouté :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/jv55kyf8/04-revision-qr-code-generation.png)

## 4. **Flux de statut -** Publier pour générer un code QR

Sans le flux de statut, toutes les révisions qui sont téléchargées sont instantanément publiées. Les documents ne sont analysés pour les codes QR placeholder que lorsqu'ils sont publiés.

### 4.1 **Révisions partagées par rapport aux révisions publiées**

Avec le flux de statut activé, les nouvelles révisions sont téléchargées en tant que révisions partagées avant la publication. Lorsque vous regardez la révision partagée, vous pouvez voir le document original avant que Catenda ne l'ait modifié avec un code QR généré. Avec le flux de statut, le remplacement du placeholder du code QR par le code QR généré se fait lorsqu'une révision partagée dans un dossier configuré qui dispose du placeholder du code QR est publiée.
