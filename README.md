# Régression Logistique Non Linéaire from Scratch

Ce projet implémente un modèle de **régression logistique** pour des données **non linéairement séparables**, développé **from scratch** (sans `scikit-learn`), et appliqué sur des jeux de données synthétiques générés en forme de lunes.

## 🧪 Objectif

- Implémenter une régression logistique depuis zéro avec `NumPy`.
- Gérer des cas non linéaires à l’aide de la **transformation de caractéristiques** (features polynomiales).
- Visualiser les frontières de décision du modèle.
- Analyser les performances sur des données non linéaires.

## 🗃️ Dataset

Le dataset utilisé est généré via `make_moons` de `scikit-learn`, ou fourni dans un fichier CSV (`moonDataset.csv`) contenant deux colonnes de caractéristiques (`X1`, `X2`) et une colonne de label binaire (`Y`).

## 🧠 Méthodologie

1. Génération ou chargement des données
2. Transformation polynomiale des features
3. Implémentation des fonctions clés :
   - Fonction sigmoïde
   - Fonction coût (log-loss)
   - Descente de gradient
4. Entraînement du modèle
5. Prédiction et visualisation :
   - Accuracy
   - Frontière de décision
   - Convergence de la fonction coût

## 📈 Résultats

Le modèle parvient à apprendre une frontière non linéaire séparant efficacement les deux classes, avec une bonne précision et une visualisation claire de la décision.

## 📁 Fichiers

- Notebook avec génération de données et entraînement
- Notebook avec implémentation complète from scratch
- Dataset CSV avec des points en forme de lunes

## 🛠️ Technologies

- Python
- NumPy
- Matplotlib
- scikit-learn (pour la génération des données uniquement)
- Jupyter Notebook

## 👤 Auteur

**Labrini Ouiam**  
Date de dernière modification : mai 2025

---

> Projet pédagogique pour l'exploration de la régression logistique non linéaire.
