# Projet-Python-SNCF
Ce projet, mené en collaboration par Kessang Flamand et moi même (Mathieu Garrouty), a pour but d'utiliser les données collectées par la SNCF, et partagées librement sur leur site. Nous avons deux principales pistes d'études : 
- Satisfaction client : à l'aide des enquêtes de satisfactions clients menées dans auprès des voyageurs, et des informations relatives aux gares (retards moyens, type de voyageurs par motif de voyage, fréquentation, connexion aux autres modes de transports, services proposés en gare, etc...), déterminer l'influence de ces facteurs sur la satisfaction des clients, et particulièrement leurs évolutions en fonction du temps
- Prédiction de retard : à l'aide de l'API mis à disposition par la SNCF, sur les écarts d'horaires théoriques et en temps réel de leurs différents services, mettre en place un modèle de prédiction de ces retards (d'expérience, certains TGV sont connus pour leur retard (Lyon-Massy à 18h le dimanche...) 

Afin de mener à bien ce projet, nous utiliserons le contenu des séances de travaux dirigés de Kim Antunez, basées sur le cours disponible en ligne de Lino Galiana, Python pour le Data Scientist.

Ce répertoire, et particulièrement ce texte, constitue le premier pas de ce projet.

Etude menée sur l'année 2017

Grandes parties du projet :

- Récupération des données et nettoyage et mise en forme (via API) 
- Croiser des bases de données directement via les API 
- Statistiques descriptives (affichage sur une carte) pour déterminer les facteurs principaux de satisfaction
- ACP pour les différents paramètres de satisfaction (indicatrices pour les catégories)

Variable observée : Satisfaction globale
Variables explicatives : 
- Répartition des modes d'accès (rabattement et diffusion) à la gare (Enquêtes en gare)
- Répartition des motifs de déplacements des voyageurs et non voyageurs (Enquêtes en gare)
- (Répartition des clients par distance parcourue (Enquête en gare) )
- Répartition des clients par fréquence en gare (Enquête en gare)
- Répartition des clients selon l'intermodalité (Enquête en gare)
- Répartition des clients par motif de déplacement (Enquête en gare)
- (Tarifs TGV par trajet)
- Répartition des distances d’accès à la gare (Enquêtes en gare)
- Gares équipées du wifi
- Travaux dans les grandes gares
- Répartition des partants par plage de temps de précaution (Enquêtes en gare)
- Répartition des clients par type (Enquêtes en gare
- Répartition des clients par catégorie socio-professionnelle (Enquêtes en gare)
- Répartition des clients par âge (Enquêtes en gare)
- Répartition des clients par genre (Enquêtes en gare)
