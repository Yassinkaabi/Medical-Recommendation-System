# Diagnostic des Maladies Basé sur les Symptômes avec Flask et GradientBoostingClassifier

Un projet de détection de maladies basé sur les symptômes fournis par l'utilisateur. L'application utilise Flask pour l'interface web et un modèle `GradientBoostingClassifier` pour prédire la maladie probable à partir des symptômes saisis.

---

## 📋 Table des Matières
- [À propos du Projet](#-à-propos-du-projet)
- [Caractéristiques](#-caractéristiques)
- [Technologies Utilisées](#-technologies-utilisées)
- [Installation](#-installation)
- [Utilisation](#-utilisation)
- [Données](#-données)

---

## 🧐 À propos du Projet
Ce projet vise à simplifier le diagnostic initial de maladies en permettant aux utilisateurs de saisir leurs symptômes via une interface web. Une fois les symptômes saisis, le modèle d'apprentissage automatique prédit la maladie probable et fournit des informations pertinentes comme :
- Description de la maladie
- Précautions à prendre
- Médicaments recommandés
- Régimes alimentaires suggérés
- Exercices adaptés

---

## ✨ Caractéristiques
- Prédiction des maladies à partir de symptômes saisis.
- Informations supplémentaires sur les maladies, telles que :
  - Description détaillée.
  - Précautions et médicaments suggérés.
  - Régimes alimentaires et exercices recommandés.
- Interface web conviviale construite avec Flask.
- Prise en charge d'un large éventail de symptômes et de maladies.

---

## 🛠️ Technologies Utilisées
- **Backend** : Flask (Python)
- **Modèle de Machine Learning** : GradientBoostingClassifier (Scikit-learn)
- **Frontend** : HTML, CSS, Bootstrap
- **Données** : CSV (symptômes, précautions, descriptions, régimes alimentaires, etc.)
- **Autres** : Pandas, NumPy, Pickle

---

## 🚀 Installation

### Prérequis
- Python 3.8+
- Pip (gestionnaire de paquets Python)

### Étapes
1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/Yassinkaabi/Medical-Recommendation-System
   cd votre-projet

Lancez l'application Flask :

python app.py
Accédez à l'application dans votre navigateur à l'adresse suivante :
http://127.0.0.1:5000/

## 🕹️ Utilisation
Accédez à la page principale.
Saisissez vos symptômes dans le champ prévu à cet effet, séparés par des virgules (ex. : itching,skin_rash,nodal_skin_eruptions,continuous_sneezing,shivering,chills,joint_pain.... ).
Cliquez sur le bouton de prédiction pour obtenir le diagnostic et les recommandations.

## 📂 Données
Les données utilisées dans ce projet sont stockées dans des fichiers CSV :

symptoms_df.csv : Liste des symptômes.
precautions_df.csv : Précautions suggérées pour chaque maladie.
description.csv : Descriptions des maladies.
workout_df.csv : Exercices recommandés.
medications.csv : Médicaments suggérés.
diets.csv : Régimes alimentaires recommandés.

