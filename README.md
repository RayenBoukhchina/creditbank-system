# Loan Prediction - Data Exploration & Preprocessing

Ce projet s'inscrit dans le cadre de l'étude du dataset **Loan Prediction Problem** de Kaggle. L'objectif principal est de comprendre les données, identifier les facteurs influençant l'octroi de crédit, et préparer un jeu de données propre et structuré pour les étapes ultérieures de modélisation prédictive.

## 📊 Objectifs du projet

- Effectuer une **analyse exploratoire des données (EDA)** pour détecter les patterns et les corrélations.
- Gérer les **valeurs manquantes** et les **outliers**.
- Encoder les **variables catégorielles** pour les rendre exploitables par les algorithmes de machine learning.
- Préparer un jeu de données nettoyé, prêt à être utilisé pour l'entraînement de modèles de prédiction.

## 🛠️ Technologies utilisées

- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
## 🧪 Étapes clés

1. **Chargement des données**  
   Importation et première visualisation des données (dimensions, types, valeurs nulles, etc.)

2. **Analyse exploratoire (EDA)**  
   - Statistiques descriptives
   - Visualisation des distributions
   - Analyse de la corrélation entre les variables et la variable cible (`Loan_Status`)

3. **Nettoyage des données**  
   - Imputation des valeurs manquantes (moyenne, médiane, mode ou modèle supervisé)
   - Gestion des valeurs aberrantes
   - Encodage des variables catégorielles (Label Encoding / One-Hot Encoding)

4. **Export des données préparées**  
   Sauvegarde du jeu de données final au format `.csv` pour la modélisation future.

## 📌 Résultats

- Jeu de données propre, sans valeurs manquantes
- Meilleure compréhension des facteurs ayant un impact sur l'approbation de crédit
- Base solide pour les futurs modèles de machine learning (classification binaire)
