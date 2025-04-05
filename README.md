# Prédiction des Accidents Vasculaires Cérébraux (AVC) avec le Machine Learning

## Description du Projet
Les accidents vasculaires cérébraux (AVC) sont une des principales causes de mortalité et d'invalidité dans le monde. Une détection précoce et une évaluation efficace des facteurs de risque sont essentielles pour réduire leur impact sur les individus et les systèmes de santé.

Ce projet vise à développer un modèle de machine learning capable de prédire la probabilité qu'un patient subisse un AVC. En utilisant des données cliniques et démographiques, nous avons appliqué des techniques avancées de traitement des données et d'optimisation de modèle pour offrir une solution précise et performante.

## Objectifs
- Préparer et explorer les données pour une meilleure compréhension des facteurs de risque.
- Sélectionner les caractéristiques les plus pertinentes pour la prédiction.
- Entraîner et optimiser un modèle de machine learning, notamment en utilisant **Random Forest**.
- Améliorer les performances du modèle à l'aide de **RandomizedSearchCV**.
- Évaluer la précision du modèle et discuter de ses applications potentielles en milieu médical.

## Prérequis
Avant d'exécuter ce projet, assure-toi d'avoir installé les bibliothèques suivantes :

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Structure du Projet

- `data/` : Contient les jeux de données utilisés pour l'entraînement et les tests.
- `notebooks/` : Contient les analyses exploratoires et les tests de modèles.
- `models/` : Contient les modèles entrainés et sauvegardés.
- `scripts/` : Contient les scripts Python pour le traitement des données et l'entraînement du modèle.
- `README.md` : Documentation du projet.

## Utilisation
1. **Exploration des Données** :
   Exécute le notebook d'analyse exploratoire dans `notebooks/` pour visualiser les données et comprendre les relations entre les variables.

2. **Entraînement du Modèle** :
   Lance le script d'entraînement du modèle :
   
   ```bash
   python scripts/train_model.py
   ```

3. **Évaluation du Modèle** :
   Utilise `scripts/evaluate_model.py` pour générer les métriques de performance.
   
   ```bash
   python scripts/evaluate_model.py
   ```

## Modèle Utilisé
- **Random Forest** : Algorithme robuste et performant pour la classification.
- **Optimisation avec RandomizedSearchCV** : Recherche des meilleurs hyperparamètres pour améliorer la précision du modèle.

## Résultats et Perspectives
- Le modèle atteint une précision satisfaisante dans la détection des risques d'AVC.
- Une amélioration est possible avec plus de données et l'utilisation de réseaux de neurones.
- Possibilité d'intégrer le modèle à une application de santé pour une détection précoce.

## Auteur
Ce projet a été réalisé par
**[Hajar Abdessadek]**.

