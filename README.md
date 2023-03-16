# Modèle de scoring pour l'octroi de crédits
## Contexte :
Home Credit, entreprise de crédit, souhaite développer un outil de scoring pour déterminer la probabilité de remboursement d'un client et ainsi décider si un prêt peut lui être accordé.

## Données :
Le projet utilise le jeu de données "olist".

## Objectifs :
- Développer un algorithme de classification à l'aide de modèles supervisés linéaires et non linéaires.
- Aider les chargés de relation client à prendre une décision sur l'octroi d'un crédit en fournissant une mesure de l'importance des variables utilisées pour calculer la probabilité de remboursement d'un client.

## Technologies :
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy
- Sklearn (RandomForestClassifier, AdaBoostClassifier, - GradientBoostingClassifier, LogisticRegression, - PolynomialFeatures, train_test_split, GridSearchCV, confusion_matrix)
- Imbalanced Learn

# Compétences évaluées :

- **Feature engineering :**
    - Analyse exploratoire des variables initiales.
Transformation des variables catégorielles en one-hot encoding.
Création d'au moins trois nouvelles variables à partir des variables initiales.
- **Entraînement d'un modèle supervisé :**
    - Identification de la variable cible.
    - Séparation du jeu de données en jeu d'entraînement et jeu de test sans fuite d'information.
   - Entraînement de plusieurs modèles supervisés (linéaires et non-linéaires).
- **Évaluation des performances du modèle :**
    - Utilisation d'une métrique adaptée au cas et qui pénalise le non-détection.
    - Évaluation de la performance d'un modèle de référence pour comparaison.
    - Utilisation de la validation croisée pour comparer les performances des modèles sur la métrique d'évaluation.
- **Ajustement des hyperparamètres pour améliorer les modèles :**
    - Identification des hyperparamètres pertinents pour le modèle.
    - Mise en œuvre d'une méthode d'optimisation appropriée, telle que la recherche en grille.
    - Utilisation de la validation croisée pour valider la performance du modèle ajusté.
  
---
## Mots-clés :
#machineLearning #supervisedLearning #logisticRegression #randomForests #adaboost #classification #true-false-positive-negative #hyperParameters #oneHotEncoding #labelEncoder #accuracy #precision #recall #f1Score #rocAuc #imbalancedClass #gridSearch #fBetaScore #exploratoryDataAnalysis #dataVisualization #dataScience #artificialIntelligence #bigData #finance