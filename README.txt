INVENTAIRE DE MATÉRIEL - Application Flask
============================================

1. INSTALLER FLASK
-------------------
Ouvre le terminal dans VS Code (Terminal > Nouveau terminal) et tape :

    pip install flask

2. LANCER L'APPLICATION
-------------------------
Dans le même terminal, tape :

    python app.py

3. OUVRIR L'APPLICATION
--------------------------
Ouvre ton navigateur et va à l'adresse :

    http://127.0.0.1:5000

La base de données "inventaire.db" sera créée automatiquement au premier lancement.

4. ARRÊTER L'APPLICATION
---------------------------
Dans le terminal, appuie sur CTRL + C

STRUCTURE DU PROJET
----------------------
inventaire_app/
├── app.py                  -> Code principal (routes Flask)
├── inventaire.db            -> Base de données (créée automatiquement)
├── templates/
│   ├── index.html            -> Liste du matériel
│   ├── ajouter.html          -> Formulaire d'ajout
│   └── modifier.html         -> Formulaire de modification
└── static/
    └── style.css              -> Mise en forme
