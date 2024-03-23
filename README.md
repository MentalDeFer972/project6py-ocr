# Projet6py-ocr: Un site Web d'information sur les films
Projet6py-ocr est une application Web permettant de donner des information sur les meilleurs films du moment.
Elle est contitué d'une entête qui décrit le film le mieux noté par le public,ainsi que 3 caroussels des meilleurs films par catégorie.

## Installation et exécution

1. Cloner ce dépôt de code à l'aide de la commande `$ git clone https://github.com/MentalDeFer972/project6py-ocr.git`
2. Cloner ce dépôt de code à l'aide de la commande `$ git clone https://github.com/OpenClassrooms-Student-Center/OCMovies-API-EN-FR.git` (vous pouvez également télécharger le code [en temps qu'archive zip](https://github.com/OpenClassrooms-Student-Center/OCMovies-API-EN-FR/archive/refs/heads/master.zip)) à la racine du projet project6py-ocr.
2. Rendez-vous depuis un terminal à la racine du répertoire OCMovies-API-EN-FR avec la commande `$ cd OCMovies-API-EN-FR`
3. Installez les dépendances du projet à l'aide de la commande `pipenv install` 
4. Créer et alimenter la base de données à l'aide de la commande `pipenv run python manage.py create_db`
5. Démarrer le serveur avec `pipenv run python manage.py runserver`
6. Et enfin,à la racine du projet projet6py-ocr,veuillez exécuter le fichier homepage.html
7. Et voilà!
