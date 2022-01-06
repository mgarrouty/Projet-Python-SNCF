## Récupération des données


Le répertoire est constitué comme suit :

- Un fichier texte expliquant l'objectif de notre projet
- La partie base de données contient les bases de données extraites du site de la SNCF puis utilisées dans l'étude, au format Excel
- Un fichier regroupant nos notebook, à savoir :
    - Un notebook d'importation et de nettoyage des données (via les API du site de la SNCF)
    - Un notebook de statistiques descriptives (grands chiffres du trafic SNCF, analyse plus précises suivant les variables observées), 
      et d'analyse quantitative (régressions linéaires, ACP, cercle des corrélations) sur nos variables explicatives
- Un fichier checkpoint permettant de rapidement réaccéder aux anciennes versions importantes de nos notebooks.
