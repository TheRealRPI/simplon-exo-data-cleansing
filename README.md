# 🧹 Data Cleansing - Exercices Pratiques

Un ensemble d'exercices et de travaux pratiques centrés sur le **nettoyage et la préparation des données** (Data Cleansing). Ce projet vise à explorer les techniques essentielles pour identifier, corriger et optimiser les jeux de données avant analyse.

---

## 📌 Prérequis

- **Python** : Version **3.13 ou inférieure** (requis pour la compatibilité avec `ydata-profiling`, qui n'est pas encore supporté sur Python 3.14).

---

## 🛠️ Installation

Pour exécuter les notebooks et scripts de ce projet, installez les dépendances requises avec la commande suivante :

```bash
pip install pyarrow seaborn pandas missingno scipy setuptools==79.0.0 ydata-profiling scikit-learn matplotlib numpy ipywidgets visions networkx
```

> ⚠️ **Note** : L'utilisation de `setuptools==79.0.0` est recommandée pour faire fonctionner ydata-profiling qui utilise encore des outils dépréciés depuis.

---

## 📂 Structure du Projet

```
DATA_CLEANING/
├── TP1_Data_Cleansing_TP1.ipynb    # Travail Pratique 1
├── TP2_Data_Cleansing_TP2.ipynb    # Travail Pratique 2
├── TP3_Data_Cleansing_TP3.ipynb    # Travail Pratique 3
├── TP4_Data_Cleansing_TP4.ipynb    # Travail Pratique 4
└── data/                            # Fichiers CSV sources
    ├── customers_duplicates.csv
    ├── ecommerce_simple.csv
    ├── healthcare_inconsistent.csv
    └── sales_outliers.csv
```
