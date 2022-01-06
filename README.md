## I - Récupération des données
Nous travaillons sur les données publiques de la SNCF, accessibles depuis le site : https://ressources.data.sncf.com/pages/accueil/ :

<img src ="https://user-images.githubusercontent.com/91116132/148348116-2c126d62-de31-4012-a2bb-b204709f8ea0.png" width="80%"></img>

La SNCF y rend publique plus de 200 jeux de données relatifs au réseau ferroviaire, auquel nous accédons grâce à l'API également mise à disposition par la SNCF (dans notre notebook Récupération des données).

## II - Manipulation des données
Une fois les données récupérées, nous les avons nettoyées (gestion des NAs, des enquêtes doublons, des codes de gares différents, etc..), puis nous avons constitué notre base principale de travail, regroupant les données relatives à chaque gare. Voici un aperçu de notre base de donnée finale :

<img src ="https://user-images.githubusercontent.com/91116132/148350041-f66a0500-1995-4898-8903-1e7f7c63f7c1.png" width="100%"></img>
                                                                                                                             
## III - Visualiser les données
Afin d'avoir un aperçu globale des données, nous avons d'abord procédé à des visualisations de statistiques descriptives, à l'aide des outils utilisées en TD, notamment geopandas pour les données géographiques :
                                                                                                      
<p align="center"><img src ="https://user-images.githubusercontent.com/91116132/148350674-795d7c24-1a48-42e8-bede-4e6af699267a.png" width="50%" ></img></p>

## IV - Modéliser les données
Dans le but d'étudier les déterminants de la satisfaction en gare, nous avons utiliser différents modèles sur nos données : des régressions linéaires, des ACP et un cercle des corrélation appliquées aux différentes composantes de la satisfaction.
                                                                                                                              
## V - Constitution du répertoire
Le répertoire est constitué comme suit :

- Un fichier texte expliquant l'objectif de notre projet
- La partie base de données contient les bases de données extraites du site de la SNCF puis utilisées dans l'étude, au format Excel
- Un fichier regroupant nos notebook, à savoir :
    - Un notebook d'importation et de nettoyage des données (via les API du site de la SNCF)
    - Un notebook de statistiques descriptives (grands chiffres du trafic SNCF, analyse plus précises suivant les variables observées), 
      et d'analyse quantitative (régressions linéaires, ACP, cercle des corrélations) sur nos variables explicatives
- Un fichier checkpoint permettant de rapidement réaccéder aux anciennes versions importantes de nos notebooks.
