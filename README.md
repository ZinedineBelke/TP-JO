# Prédiction des médailles aux Jeux Olympiques 2024
Présentation du projet

Ce projet de data science vise à prédire le nombre de médailles susceptibles d’être remportées par chaque pays lors des Jeux Olympiques de Paris 2024, à partir de l’analyse des éditions précédentes des Jeux Olympiques.

Réalisé en binôme et implémenté sous forme de notebook Jupyter, ce projet s’appuie sur des données historiques remontant jusqu’à 1896, couvrant plus d’un siècle de compétitions olympiques. L’objectif est d’identifier des corrélations significatives entre les performances passées des nations et leurs résultats futurs, afin de construire un modèle prédictif pertinent.

Objectifs du projet

Analyser l’évolution des performances olympiques des pays au fil du temps

Mettre en évidence des tendances et corrélations entre éditions successives

Traiter les problématiques liées à l’historique des Jeux (changements de pays, disciplines disparues, évolutions géopolitiques)

Concevoir un algorithme de prédiction du nombre de médailles par pays pour l’édition 2024

Appliquer une démarche complète de data preparation → exploration → modélisation

Données utilisées

Les données exploitées couvrent l’ensemble des Jeux Olympiques modernes depuis 1896 et regroupent notamment :

les pays participants,

les disciplines et épreuves,

les résultats et médailles obtenues par édition.

L’utilisation de données aussi anciennes a nécessité un important travail de consolidation et d’harmonisation, notamment en raison de :

la disparition de certaines disciplines sportives,

la disparition ou la fusion de certains pays (ex : Yougoslavie),

le changement de nom ou de structure politique de certaines nations (ex : URSS).

Préparation et nettoyage des données

Avant toute phase de modélisation, plusieurs étapes clés ont été réalisées :

nettoyage des valeurs manquantes et incohérentes,

harmonisation des noms de pays à travers les différentes périodes,

regroupement et transformation des données historiques,

sélection des variables pertinentes pour l’analyse et la prédiction.

Ce travail de data cleaning et de feature engineering a été essentiel pour garantir la qualité des analyses et la fiabilité du modèle final.

Analyse exploratoire et visualisation

Une phase approfondie d’exploration des données (EDA) a permis :

d’identifier des tendances globales par pays et par édition,

de visualiser l’évolution des performances dans le temps,

de mettre en évidence des corrélations significatives entre les résultats passés et futurs.

Les visualisations ont joué un rôle central dans la compréhension des données et dans l’orientation des choix de modélisation.

Modélisation et prédiction

À l’issue des phases de préparation et d’analyse, un algorithme de prédiction a été développé afin d’estimer le nombre de médailles susceptibles d’être remportées par chaque pays lors des Jeux Olympiques de 2024.

Le modèle s’appuie sur :

les performances historiques,

les tendances observées sur plusieurs éditions,

des variables explicatives issues du traitement des données.

Les résultats obtenus sont présentés et analysés directement dans le notebook.

Technologies et outils

Python

Jupyter Notebook

Librairies data science :

pandas

numpy

matplotlib / seaborn

scikit-learn
