# digital-music-store

### Prérequis :

* Python version 3.8.2
* Git version 2.29.1.windows.1

### Contexte du projet :

Une base de données (de type SQLite) contenant les données d'un commerce de musique digital vous est fournie pour exploration et mise en pratique des langages SQL et Python. L'accent est mis ici sur des requêtes à multiples jointures et la mise en oeuvre des vues.

### Contenu du dépôt Git :

* Fichier README
* Fichier requirements.txt, listant les librairies python nécessaires qui seront installées sur l'environnement virtuel
* Notebook p1-exploration.ipynb
* Notebook p2-vues-sql.ipynb
* Dossier db/, contenant la base de données utilisée
* Dossier MACOSX/, contenant également la base de données dans un format adapté à macOS

### Étapes pour installer et lancer le projet : 

Copier le dépôt de travail digital-music-store
> git clone https://github.com/phil3in/digital-music-store

Créer son environnement virtuel avec Git Bash
> python3 -m venv nomDeEnv

Activer son environnement sous Windows avec GitBash
> source nomDeEnv/Scripts/activate

Installer jupyter-lab et toutes les librairies python nécessaires
> pip install -r requirements.txt

Aller dans le dépôt digital-music-store
> cd digital-music-store

Afin d'accéder aux scripts il nous faut lancer jupyter lab : 
> jupyter lab