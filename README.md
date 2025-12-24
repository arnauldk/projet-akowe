# 📊 Projet Akowe

Le projet **Akowe** est un projet d’**analyse de données en Python** réalisé avec **Jupyter Notebook**.  
Il repose sur un important travail de **préparation, réduction et analyse de données**, appliqué aux **États d’Afrique subsaharienne**.

---

## 🧠 Contexte du projet

À l’origine, le projet s’appuie sur un **jeu de données très volumineux** contenant :

- 🌍 **Plus de 4 000 indicateurs**
- 🌐 **Tous les pays du monde**

Pour répondre aux objectifs de l’étude, un travail approfondi de **filtrage, sélection et transformation** a été réalisé afin d’obtenir un dataset exploitable et pertinent.

Le résultat de ce processus est le fichier **`df-1.csv`**, qui constitue la base **unique** de l’analyse finale.

👉 **Toute l’analyse du projet repose exclusivement sur `df-1.csv`.**

---

## 📦 Structure du projet

```text
projet-akowe/
│
├── notebook.ipynb          # Analyse finale
├── notebook_initial.ipynb  # Manipulations initiales
├── df.csv                # Dataset final nettoyé
├── requirements.txt        # Dépendances Python
└── README.md               # Documentation
##  Architecture du projet
notebook.ipynb
data/
└── df.csv
scripts/
README.md
requirements.txt

##  Notebook
Le notebook principal du projet est :
- `notebook.ipynb`

##  Données
Les données utilisées pour l’analyse sont disponibles dans le dossier :
- `data/df.csv`

##  Ressources supplémentaires
Les fichiers volumineux (PowerPoint) sont stockés sur Google Drive :  
[Lien Google Drive (accès éditeur)](https://drive.google.com/drive/folders/1cmhCzRcZyk9zANsP_odHemwxyE_wb5lL?usp=sharing)

##  Installation et utilisation

**Cloner le dépôt :**
```bash
git clone https://github.com/arnauldk/projet-akowe.git
cd projet-akowe
# Création de l'environnement virtuel
python -m venv venv
# Activation de l'environnement virtuel sur Windows
venv/Scripts/activate 
# Activation de l'environnement virtuel sur MacOs ou Linux
source venv/bin/activate
 
#Important: Activer l'environnement virtuel avant d'installer les dépendances

Installer les dépendances :
pip install -r requirements.txt

Lancer le notebook :
jupyter notebook notebook.ipynb
Le notebook s’ouvrira dans votre navigateur. Exécutez les cellules dans l’ordre pour reproduire les analyses.
