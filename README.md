# Titanic – Prédiction de Survie

Projet de Machine Learning réalisé sur le challenge Kaggle **[Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)**.

## Objectif

Prédire si un passager a survécu au naufrage du Titanic à partir de ses caractéristiques (âge, sexe, classe, tarif, port d'embarquement...).

##  Résultat

- **+15% de précision** par rapport au modèle de base (baseline)
- Modèle final : **Random Forest (500 estimateurs)**

## Étapes du projet

1. **Exploration des données** – aperçu et analyse des datasets train/test (891 passagers)
2. **Nettoyage** – suppression des colonnes non pertinentes (`Name`, `Ticket`, `Cabin`)
3. **Gestion des valeurs manquantes** – remplissage par médiane (`Age`, `Fare`) et mode (`Embarked`)
4. **Encodage** – conversion des variables catégorielles (`Sex` → 0/1, `Embarked` → One-Hot Encoding)
5. **Normalisation** – standardisation des features avec `StandardScaler`
6. **Modélisation** – entraînement d'un `RandomForestClassifier` (n_estimators=500)
7. **Prédiction** – génération des résultats sur le jeu de test

## Technologies

| Outil | Usage |
|-------|-------|
| Python | Langage principal |
| Pandas | Manipulation des données |
| NumPy | Calcul numérique |
| Scikit-learn | Modèle ML, preprocessing |
| Kaggle Notebooks | Environnement d'exécution |

## Fichiers

```
├── TitanicKaggle.ipynb   # Notebook principal
└── README.md
```

## 👤 Auteur

**Alexandre Yang** – Étudiant ingénieur à l'ECE Paris  
[LinkedIn](https://linkedin.com/in/VOTRE_PROFIL) <!-- https://www.linkedin.com/in/alexandre-yang-a9a5a32b3/ -->
