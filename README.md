# 🏦 Credit Scoring Analysis : Performance & Interprétabilité

Ce projet explore l'impact du prétraitement des données, de la réduction de dimension (PCA) et de l'optimisation des hyperparamètres sur un modèle de classification de crédit.

## 🎯 Objectif
Démontrer qu'une approche rigoureuse de Data Science (Nettoyage, Scaling) surpasse souvent la simple complexité algorithmique.

## 📊 Résultats Clés
- **Meilleur Modèle :** Random Forest (Données standardisées).
- **Précision :** **78.33%** (contre 64% avec PCA).
- **Impact PCA :** Une chute de performance de 14%, soulignant l'importance des variables brutes dans le secteur financier.

## 🛠️ Pipeline Technique
1. **Prétraitement :** Traitement des valeurs aberrantes (outliers) et imputation par la médiane.
2. **Feature Engineering :** Standardisation (StandardScaler) et Encodage.
3. **Réduction de Dimension :** Analyse comparative avec et sans PCA.
4. **Modélisation :** Benchmark entre KNN, Decision Tree et Random Forest.
5. **Validation :** Analyse des courbes de validation pour limiter le sur-apprentissage.

## 📁 Structure du Dépôt
- `Credit_Scoring.ipynb` : Notebook complet avec code et analyses.
- `Rapport_Final.pdf` : Rapport technique détaillé rédigé en LaTeX.
- `images/` : Visualisations clés (Importance des variables, Matrice de confusion).

## 🚀 Installation & Usage
1. Clonez le dépôt : `git clone https://github.com/votre-nom/credit-scoring-ia.git`
2. Installez les dépendances : `pip install -r requirements.txt`
3. Lancez le notebook sur Jupyter ou Google Colab.
