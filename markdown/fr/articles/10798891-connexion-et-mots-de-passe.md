# Connexion et mots de passe

Il y a plusieurs endroits sur Catenda où vous êtes invité à entrer un mot de passe. Cet article décrit les différents défis que les utilisateurs pourraient rencontrer lors de la saisie de leurs informations de compte.

## 1. **Se connecter**

Sur la [page de connexion](https://support.catenda.com/en/articles/7891486-sign-in-page) vous êtes invité à entrer votre mot de passe. La même page de connexion est utilisée à la fois lors de la connexion via le navigateur et lors de la connexion pour donner accès à votre compte via l'API comme vous le faites avec de nombreux nos plugins. Au cours de ce processus, les défis suivants pourraient survenir :

### 1.1 **Nom d'utilisateur ou mot de passe incorrect**

Assurez-vous d'entrer la bonne combinaison nom d'utilisateur et mot de passe. Votre nom d'utilisateur est toujours l'adresse e-mail associée à votre compte.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/01-wrong-username-or-password.png)

Pour ceux qui ne sont pas sûrs d'avoir créé avec succès un compte, veuillez vous inscrire à nouveau sur hub.catenda.com/signup et tenter de créer un compte en cliquant sur le lien dans l'e-mail de création de compte.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/02-wrong-username-or-password.png)

Si un compte sous votre adresse e-mail existe, un avertissement s'affiche pour confirmer que votre compte existe.

### 1.2 **Trop de tentatives de connexion**

Si vous entrez un mauvais nom d'utilisateur ou mot de passe trop de fois, vous devrez soit attendre un certain temps avant de pouvoir réessayer, soit aller sur [https://hub.catenda.com/forgot-password](https://hub.catenda.com/forgot-password) pour réinitialiser votre mot de passe.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/03-too-many-login-requests.png)

## 2. **Confirmation du mot de passe**

Chaque fois qu'il y a un changement d'informations de mot de passe, vous serez invité à entrer votre mot de passe une fois pour l'entrer et une fois de plus pour confirmation. Au cours de ce processus, les défis suivants pourraient survenir :

### 2.1 **Exigence de mot de passe**

Assurez-vous que votre mot de passe est

- au moins 12 caractères de long

et contient au moins un des éléments suivants :

- une lettre majuscule
- une lettre minuscule
- un caractère numérique

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/04-password-requirement.png)

### 2.2 **J'ai oublié mon mot de passe**

Si vous ne pouvez pas vous connecter, vous pouvez demander un nouveau mot de passe en allant à [https://hub.catenda.com/forgot-password](https://hub.catenda.com/forgot-password)

### 2.3 **Les mots de passe ne sont pas identiques**

Lorsque vous entrez votre nouveau mot de passe pour la deuxième fois pour le confirmer, assurez-vous d'entrer le même mot de passe que vous venez d'entrer.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/05-passwords-are-not-equal.png)

### 2.4 **L'ancien mot de passe n'est pas valide**

Si vous pouvez vous connecter, vous pouvez aller à la [page d'authentification du compte](https://support.catenda.com/en/articles/6880968-account-page) pour réinitialiser votre mot de passe. Vous devez d'abord entrer votre ancien mot de passe. C'est le mot de passe que vous avez utilisé pour vous connecter à votre compte. Si vous n'entrez pas le bon mot de passe, vous verrez le message suivant :

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/06-old-password-not-valid.png)

### 2.5 **Le nouveau mot de passe est le même**

Si vous changez votre mot de passe, assurez-vous d'entrer un nouveau mot de passe qui n'est pas identique à votre mot de passe précédent.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/07-new-password-is-the-same.png)

### 2.6 Erreur 500 lors de l'utilisation de SSO

Si vous recevez une erreur 500 après vous être connecté avec SSO, l'adresse e-mail fournie par votre fournisseur d'identité peut être différente de l'adresse e-mail enregistrée sur votre compte utilisateur Catenda. Comme aucun utilisateur correspondant ne peut être trouvé, la connexion échoue avec une erreur 500. Veuillez contacter l'administrateur informatique de votre organisation pour vérifier quelle adresse e-mail est envoyée via SSO.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/zw9p4shp/08-500-error-when-using-sso.png)
