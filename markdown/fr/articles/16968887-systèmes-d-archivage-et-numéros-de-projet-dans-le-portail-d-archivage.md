# Systèmes d'archivage et numéros de projet dans le portail d'archivage

> Quel système d'archivage externe le portail soumet, et quel schéma de numérotation de projet il enregistre.

Les autres articles du portail d'archivage décrivent le système d'archivage et le numéro de projet en termes généraux, car ce qui se cache derrière dépend de l'organisation. Cet article nomme ce que le portail supporte actuellement.

## 1. **Le système d'archivage : WebSak+**

Le portail soumet à **WebSak+**, le système d'archivage fourni par **Acos**.

Une soumission ne va pas directement dans WebSak+. Le portail assemble les métadonnées de l'élément en XML et les transmet au service de soumission d'Acos, qui effectue l'archivage. La référence que ce service retourne est ce que l'onglet **Archivé** affiche sous **Ref ACOS**, donc citez-la quand vous avez besoin de demander des informations sur un élément archivé spécifique.

C'est aussi pourquoi les raisons d'échec sur l'onglet **Archivé** sont formulées comme des limites de l'archive réceptrice : au maximum 50 fichiers et au maximum 2300 Mo par soumission.

## 2. **Numérotation de projet : Agresso**

Le **numéro de projet** dans **Paramètres** est un **numéro de projet Agresso**, composé de 8 caractères.

> **Important :** Le numéro est saisi dans le portail car c'est le numéro enregistré dans le projet dans WebSak+. Il n'y a aucune connexion entre le portail d'archivage et Agresso lui-même. Rien n'est lu ou écrit dans Agresso, et aucune validation n'est effectuée par rapport à celui-ci, alors saisissez le numéro avec soin. Le portail ne peut pas vous dire qu'il est incorrect.

## 3. **Tout le reste**

Le portail est construit pour les données de projet openBIM dans Catenda Hub, donc les documents et sujets qu'il propose proviennent de Catenda Hub et nulle part ailleurs.

Pour extraire les données du projet de Catenda Hub d'autres façons, y compris les exportations, les formats à long terme et l'option d'archive gelée, voir [Exportation de toutes les données du projet](https://support.catenda.com/en/articles/7946690-exporting-all-project-data).
