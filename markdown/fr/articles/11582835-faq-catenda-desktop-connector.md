# FAQ Catenda Desktop Connector

## 1. Fichiers en ligne uniquement

De nombreux systèmes de gestion de documents vous permettent d'afficher une version fantôme de vos fichiers sur votre système qui n'occupent aucun espace. Vous pouvez souvent identifier quand un Document est en ligne uniquement par un badge archivé ou ressemblant à un nuage. Voici quelques exemples de ce qu'un Document en ligne uniquement peut ressembler dans différents services :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/swkm9e7y/01-online-only-files.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/swkm9e7y/02-online-only-files.png)

![](https://raw.githubusercontent.com/catenda/help-center/main/images/swkm9e7y/03-online-only-files.png)

Dropbox Google Drive Microsoft 365/SharePoint

Quand le Desktop Connector tente de télécharger un Document comme celui-ci, il va tenter d'y accéder. Si vous avez le service respectif en cours d'exécution, cela sera reconnu et commencera à télécharger le Document sur votre système local. Par conséquent, assurez-vous d'avoir suffisamment d'espace sur votre machine, également lors du téléchargement ! Le Desktop Connector est capable de déterminer s'il y a eu des modifications au Document, même s'il est en ligne uniquement et ne téléchargera le fichier pour le télécharger vers Catenda que s'il a été modifié. Après que la tâche de téléchargement a été effectuée, tous les fichiers qui ont été téléchargés sur votre système occuperont de l'espace. De nombreux services de synchronisation libéreront régulièrement de l'espace si le Document n'a pas été utilisé après un certain temps. Si vous voulez que cela se produise immédiatement, le Document ou le dossier peut être cliqué avec le bouton droit et changé en ligne uniquement dans le menu du bouton droit.
