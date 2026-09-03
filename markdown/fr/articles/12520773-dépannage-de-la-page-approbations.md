# Dépannage de la page Approbations

## 1. **Soumettre une nouvelle demande d'approbation**

Lorsqu'une nouvelle demande d'approbation est soumise pour examen avec plus de 1000 documents ajoutés à l'aide du bouton d'ajout de documents, l'erreur suivante s'affiche :

![Erreur de nouvelle demande d'approbation Workflow workflow par défaut Auteur Titre](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/01-submitting-a-new-approval-request.png)

Il est uniquement possible de soumettre la boîte de dialogue de nouvelle demande d'approbation avec jusqu'à 1000 documents à la fois. Pour soumettre une demande d'approbation avec plus de 1000 documents, commencez par ajouter jusqu'à 1000 documents à la boîte de dialogue de nouvelle demande d'approbation et enregistrez en tant que brouillon. Accédez à la page de brouillon d'approbation du document et ajoutez autant de documents que souhaité avant de soumettre la demande d'approbation.

## 2. **Onglet Aperçu - Fermeture d'une demande d'approbation**

Lors de la fermeture d'une approbation, la publication peut échouer. Dans l'[onglet aperçu](https://support.catenda.com/en/articles/12495126-overview-tab-in-an-approval-request) de l'approbation, ce qui suit peut alors être visible :

![Échec de la publication 1 document publié. Impossible de mettre à jour 1 document afficher les détails](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/02-overview-tab-closing-an-approval-request.png)

### 2.1 **Une révision publiée existe déjà**

Il est uniquement possible de publier les révisions partagées dans les documents où la dernière révision est une révision partagée. Si la révision dans l'approbation, ou toute autre révision partagée après la révision publiée précédente a été publiée et qu'un nouveau numéro de révision majeure a été créé, cette révision ne peut pas devenir ce numéro de révision majeure suivant car il existe déjà et échouera. Une révision partagée peut avoir été publiée suite à la fermeture d'une demande d'approbation différente ou en utilisant l'action de publication dans le tableau des documents ou dans les informations de révision du menu de droite d'une révision.

## 3. **Onglet Documents**

### 3.1 **Document non trouvé**

Si un document qui fait partie d'une approbation est supprimé, il ne peut plus être trouvé et le contenu du document ne s'affichera plus sur la page d'examen du fichier. Voici ce que l'onglet du document peut ressembler lorsqu'un document qui fait partie d'une approbation a été supprimé :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/03-document-not-found.png)

Les documents qui ont été ajoutés à une demande d'approbation et qui ont été supprimés par la suite peuvent soit être récupérés par un administrateur, soit supprimés de la demande d'approbation.

### 3.2 **Révision retirée**

Si une révision de document qui fait partie d'une approbation est retirée, le numéro de révision est barré et le contenu du document ne s'affichera plus sur la page d'examen du fichier. Voici ce que l'onglet du document peut ressembler lorsqu'un document qui fait partie d'une approbation a été supprimé :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/04-withdrawn-revision.png)

Les révisions de document qui ont été ajoutées à une demande d'approbation et retirées par la suite peuvent être supprimées de la demande d'approbation.
