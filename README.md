## I - Récupération des données
Nous travaillons sur les données publiques de la SNCF, accessibles depuis le site : https://ressources.data.sncf.com/pages/accueil/ :

<img src ="https://user-images.githubusercontent.com/91116132/148348116-2c126d62-de31-4012-a2bb-b204709f8ea0.png" width="100%"></img>

La SNCF y rend publique plus de 200 jeux de données relatifs au réseau ferroviaire, auquel nous accédons grâce à l'API également mise à disposition par la SNCF (dans notre notebook Récupération des données).

## II - Manipulation des données
Une fois les données récupérées, nous les avons nettoyées (gestion des NAs, des enquêtes doublons, des codes de gares différents, etc..), puis nous avons constitué notre base principale de travail, regroupant les données relatives à chaque gare.

Le répertoire est constitué comme suit :

- Un fichier texte expliquant l'objectif de notre projet
- La partie base de données contient les bases de données extraites du site de la SNCF puis utilisées dans l'étude, au format Excel
- Un fichier regroupant nos notebook, à savoir :
    - Un notebook d'importation et de nettoyage des données (via les API du site de la SNCF)
    - Un notebook de statistiques descriptives (grands chiffres du trafic SNCF, analyse plus précises suivant les variables observées), 
      et d'analyse quantitative (régressions linéaires, ACP, cercle des corrélations) sur nos variables explicatives
- Un fichier checkpoint permettant de rapidement réaccéder aux anciennes versions importantes de nos notebooks.
