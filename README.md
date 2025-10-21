# 🎬 IMDB Sentiment Classification

## 🔹 Objectif
Ce projet consiste à construire un modèle capable de **classifier automatiquement les critiques de films** du dataset IMDB en **positives** ou **négatives**.  
Il utilise un pipeline simple mais efficace combinant **TF-IDF** et **Régression Logistique**, et est conçu pour être clair et reproductible.

## 🗂️ Jeu de données
- Dataset : [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)  
- 50 000 critiques : 25 000 positives, 25 000 négatives  
- Format : CSV avec colonnes `review` et `sentiment`

## ⚙️ Méthodologie
1. Chargement et exploration du dataset  
2. Nettoyage et préparation du texte (HTML, ponctuation, stopwords, tokenisation)  
3. Création d’un pipeline **TF-IDF + Logistic Regression**  
4. Évaluation des performances (accuracy, F1-score, matrice de confusion)  
5. Publication du notebook sur GitHub

## 📊 Résultats
- Modèle simple mais performant pour la classification de sentiment  
- Visualisation de la répartition des classes et de la matrice de confusion  

## 🛠️ Librairies utilisées
- `pandas`, `scikit-learn`, `matplotlib`, `nltk`, `kagglehub`

## 📂 Structure du dépôt
   ```bash
   imdb-sentiment-classification/
   │
   ├── IMDB_Sentiment_Classification.ipynb # Notebook principal
   ├── requirements.txt # Librairies Python nécessaires
   └── README.md # Documentation du projet
   ```

## 📌 Instructions pour exécuter
1. Cloner le dépôt
   ```bash
   git clone https://github.com/NicolasStucky0/imdb-sentiment-classification.git

2. Installer les dépendances
pip install -r requirements.txt

3. Ouvrir et exécuter le notebook IMDB_Sentiment_Classification.ipynb dans Jupyter ou VS Code

## 🚀 Perspectives

Tester d’autres modèles (SVM, Random Forest, BERT, etc.)

Améliorer le prétraitement (lemmatisation, bigrammes/trigrammes, embeddings)

Publier le notebook interactif via Binder ou Google Colab
