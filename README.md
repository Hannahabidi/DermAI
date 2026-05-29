
# 🔬 DermAI - Détection Intelligente du Cancer de Peau

Application Web complète en Python (Flask) intégrant un modèle d'Intelligence Artificielle Deep Learning (VGG16) pour la détection du cancer de peau.

## 🎯 Fonctionnalités

- 🔐 Authentification sécurisée (Login/Logout)
- 🧠 Analyse IA d'images de lésions cutanées (Bénin/Malin)
- 📊 Taux de confiance en pourcentage
- 👥 Historique complet des patients analysés
- 🗄️ Base de données MySQL

## 🛠️ Technologies Utilisées

- Python 3.11
- Flask (Framework Web)
- TensorFlow / Keras (VGG16)
- MySQL (Base de données)
- Bootstrap 5 (Interface)
- HTML/CSS/JavaScript

## 📁 Structure du Projet
## 🚀 Installation

1. Cloner le repository
2. Installer les dépendances :
3. 3. Configurer MySQL avec `database.sql`
4. Placer le modèle `vgg16_skin_cancer.h5` dans `/model/`
5. Lancer : `python app.py`

## 📸 Captures d'écran

### Page Login
![Login](screenshots/login.png)

### Dashboard
![Dashboard](screenshots/dashboard.png)

### Analyse Patient
![Analyse](screenshots/predict.png)

### Résultat
![Résultat](screenshots/result.png)

### Historique Patients
![Patients](screenshots/patients.png)

## 👩‍💻 Auteur

**Hana El Abidi** - ENSTAB 2025/2026  
Module : Introduction à l'IA  
Enseignante : Amira Echtioui
