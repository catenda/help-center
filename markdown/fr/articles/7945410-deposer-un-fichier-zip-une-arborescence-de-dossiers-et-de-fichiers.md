# Déposer un fichier ZIP / une arborescence de dossiers et de fichiers

Par rapport au simple chargement d'un fichier ZIP, la fonction de chargement "Déposer un fichier ZIP" permet de "déballer" le contenu du fichier ZIP. Ceci vous permet d'importer une structure de dossiers et de fichiers dans la [partie documentaire](https://support.catenda.com/en/articles/8204673-documents-page#h_28610e1d21) sans avoir à créer des dossiers manuellement.

Si le dossier existe déjà, le fichier se retrouvera dans le dossier existant

Si le document existe déjà, le fichier deviendra une nouvelle révision de ce document.

Les thèmes suivants sont abordés dans cet article :

[Déposer un fichier ZIP](#h_5b148952e1) - [Caractères spéciaux](#h_80fc1e08a5) - [Contourner la limite de taille de fichier](#h_022b1d3b12) -

## 1. **Déposer un fichier ZIP**

Si vous souhaitez déposer un fichier ZIP, veuillez procéder comme suit :

1. Cliquez sur les 3 points en haut à droite de la partie documentaire, puis sur "Déposer un fichier ZIP" dans le menu déroulant :
​

    <div class="intercom-container"><img src="https://downloads.intercomcdn.com/i/o/areracg3/1305749502/d48726d4cb44420e106589edb662/image.png?expires=1781092800&amp;signature=1185e922cda9daaadd5b6a3c0367210bd6afe081134caf8c95e852e27e435926&amp;req=dSMnE856lIRfW%2FMW3nq%2Bgeh7aw4Dy7adlydgp83%2B27KOcXbZt0K59WP04cXs%0A9Im6Y5OiWUI%2F8JomErXdRgIGGlg%3D%0A"/></div>

1. Choisissez à présent le fichier ZIP en question sur votre ordinateur :
​

    <div class="intercom-container"><img src="https://downloads.intercomcdn.com/i/o/797822907/ba4b82b1faa83deecd64ec28/image.png?expires=1781092800&amp;signature=327c4dab9cc1cb61caae111afc2765697a9d1b0821469eaa339cc8754cf64203&amp;req=cykgHst8lIFYFb4V1XW4gR28Xyf3BETWzundTo%2BfNkgFspaWW8OUkqleovsI%0AQlM%2F9Aoj%2FOBRDfluxlZbsJpAhA%3D%3D%0A"/></div>

1. Paramétrez les réglages souhaités et déposer le fichier ZIP :
​

    <div class="intercom-container"><img height="260" src="https://downloads.intercomcdn.com/i/o/areracg3/1305763362/45eb8e49b32c574ce44a46c13d43/image.png?expires=1781092800&amp;signature=f7e79c6212f228a96cf87cadd9cc751db8aa0de58bfa75eab99ae780866d580d&amp;req=dSMnE854noJZW%2FMW3nq%2Bgb60NQ6qI27wS6P82D6JbTAB136aFRVU1oo%2BeLiK%0AyT%2BmsyutDLPOwVICN9DNW3HQdjU%3D%0A" style="height: auto;" width="703"/></div>

1. Après quelques secondes, le dossier est chargé et Catenda Hub vous demande d'actualiser la page depuis le coin inférieur gauche de l'écran.

![](https://downloads.intercomcdn.com/i/o/areracg3/1305738822/3034d5574914854ccc466f6a740c/image.png?expires=1781092800&signature=60e0cb1d80488050d90b992aed3ad579d9e77662d2c06a7fb60dc266dbc7c0cd&req=dSMnE859lYldW%2FMW3nq%2BgbqU9TvsagjsPAeDPE%2F%2FaYAJK9KaHc7PHPprfhkh%0AYjo281E2XmuAtcji%2FAsuVNmiPbw%3D%0A)

## 2. **Chargements ZIP avec caractères spéciaux**

Catenda détecte l'encodage du fichier ZIP lors de son extraction. Si le fichier ZIP contient des caractères spéciaux, ils seront interprétés correctement lors de l'extraction. Si les caractères spéciaux n'ont pas été encodés correctement, ils ne pourront pas être extraits par Catenda et auront l'air brouillés.

Selon le service que vous utilisez pour créer votre fichier ZIP, vos caractères peuvent ou non être encodés correctement.

Si vos caractères spéciaux sont brouillés, regardez dans le fichier ZIP pour voir s'ils sont corrects.

Si vous pensez que vos caractères ont été correctement encodés et qu'ils ne sont pas correctement extraits par Catenda, nous pouvons examiner votre fichier ZIP et de voir si nous pouvons faire quelque chose. Dans ce cas, veuillez contacter [support@catenda.com](mailto:support@catenda.com) en indiquant comment vous avez créé votre fichier ZIP.

### 2.1 **Encodage ZIP sur Windows**

Les différentes versions de Windows utilisent des encodages de ZIP différents.

Par exemple, la version anglaise utilise la norme d'encodage IBM-437 et la version pt-BR utilise IBM-850. Si votre installation Windows n'encode pas correctement vos fichiers ZIP, vous aurez peut-être plus de chance en utilisant un service tiers comme [7zip](https://7-zip.org/download.html) or [WinRAR](https://www.win-rar.com/download.html?&L=0) pour créer vos fichiers ZIP avec le bon encodage.

## 3. **Contourner la limite de taille de fichier**

Le chargement d'un ZIP vous permettra de charger des fichiers de plus de 7 Go car le ZIP compresse le fichier.

## 4. **Mes chargements ZIP**

L'option "Mes chargements ZIP" dans le menu déroulant vous permettra de voir un aperçu de vos précédents téléchargements ZIP.

![](https://downloads.intercomcdn.com/i/o/areracg3/1305761472/7a9ce5b081abff2fe091f4bb007c/image.png?expires=1781092800&signature=b75c5b1d93cbf854300c095ad67ddba0debc9ad9061ae4ec3678a9f6e6e400d8&req=dSMnE854nIVYW%2FMW3nq%2BgXJcSurIcnVrBjjgY1%2B194BbLvxGBY9K8iM8f4N%2F%0AC2bi76O44ffOXOKkwkzERxeSH%2Fo%3D%0A)

## 5. **Connecteur Desktop**

Avec le [Connecteur Desktop pour Catenda](https://support.catenda.com/en/articles/8358861-catenda-desktop-connector) vous pouvez automatiquement et périodiquement charger les dernières versions des documents depuis votre système local vers Catenda Hub.

Le Connecteur Desktop est plus rapide que le processus de chargement habituel et minimise le risque d'échec car il charge les documents fichier par fichier au lieu d'un gros lot de chargement d'un seul coup par glisser-déposer.
