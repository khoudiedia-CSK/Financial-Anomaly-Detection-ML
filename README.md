Financial-Anomaly-Detection-ML


🔍 Contexte

La fraude financière est un problème majeur dans le secteur bancaire et les paiements en ligne. Ce projet vise à détecter automatiquement les transactions suspectes à partir d’un dataset de transactions par carte bancaire.

Dataset utilisé : Credit Card Fraud Detection (Kaggle)
 – 284 807 transactions, dont 492 fraudes (~0,172%).

🎯 Objectif

Identifier les transactions frauduleuses dans un jeu de données réel.

Comparer différentes méthodes de détection d’anomalies.

Visualiser les transactions suspectes pour faciliter l’analyse.

⚙️ Outils & Bibliothèques

Python 3.9+

Jupyter Notebook / VS Code

Bibliothèques Python : Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Imbalanced-learn

🧩 Étapes Techniques

Exploration des données

Analyse des valeurs manquantes et de la proportion de fraudes

Étude des distributions des montants et des variables principales

Préparation des données

Normalisation des montants

Séparation des variables explicatives et de la cible

Gestion du déséquilibre avec SMOTE (optionnel)

Détection d’anomalies

Isolation Forest : méthode basée sur l’isolation des points atypiques

Local Outlier Factor (LOF) : méthode basée sur la densité locale des transactions

Évaluation des modèles

Mesure de la précision, du rappel et du F1-score

Utilisation de la matrice de confusion et de l’AUC ROC

Visualisation des anomalies

Graphique des transactions normales et suspectes pour faciliter l’interprétation

💡 Résultats

Détection efficace des anomalies rares (~0,17%)

Isolation Forest et LOF permettent de repérer les fraudes sans supervision complète

Visualisation interactive pour analyser rapidement les transactions suspectes

<img width="1352" height="410" alt="image" src="https://github.com/user-attachments/assets/25ef2d2d-7fc2-437f-b965-e8e8297cc58f" />


🔧 Améliorations possibles

Tester d’autres modèles : One-Class SVM, Autoencoder

Ajouter des features supplémentaires (catégorisation des commerçants, localisation, fréquence)

Déploiement en temps réel avec un dashboard interactif (Plotly Dash)
