# Databricks-Accidents-Project

## Présentation du Projet

Ce projet a été réalisé dans le cadre de l'examen de Formation sur Cloud. Le but de ce projet est de construire et d'évaluer plusieurs modèles de classification pour prédire des accidents à partir des données fournies dans le tutoriel d'Ilyes Talbi de la revue IA c'est à dire lieux.csv, veh.csv , carac.csv ,vict.csv

## Sources des Données

Les données utilisées pour ce projet proviennent de moodle 
 lieux.csv
 veh.csv 
 carac.csv
 vict.csv.

## Contenu du Repository

- `Modelisation.dbc` : Notebook Databricks contenant toutes les étapes de modélisation, incluant la pré-traitement des données, la construction des échantillons de train et test, et la construction des modèles de KNeighborsClassifier, DecisionTreeClassifier, et RandomForestClassifier.
- `README.md` : Fichier de documentation du projet.

## Modèles Utilisés et Performances

### KNeighborsClassifier 

- Optimisation du paramètre `n_neighbors` via GridSearchCV
- **Meilleur n_neighbors** : 
- **Accuracy** :
- **F1-Score** : 

### DecisionTreeClassifier

- Optimisation des paramètres `max_depth` et `min_samples_leaf` via GridSearchCV
- **Meilleur max_depth** : 10
- **Meilleur min_samples_leaf** : 1
- **Accuracy** :0.63
- **F1-Score** : 0.64

### RandomForestClassifier

- Optimisation des paramètres `n_estimators`, `max_depth`, et `min_samples_leaf` via GridSearchCV
- **Meilleur n_estimators** :
- **Meilleur max_depth** : 
- **Meilleur min_samples_leaf** :
- **Accuracy** : 
- **F1-Score** : 

## Meilleur Modèle

Le meilleur modèle parmi les trois est .......



