# Projet Akowe

##  Description
Ce projet a été réalisé dans le cadre d’un apprentissage en analyse de données avec Python.  
Il présente une étude basée sur des données et un notebook Jupyter.

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
