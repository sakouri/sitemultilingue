# Site Multilingue

## Description

Ce projet est un site web multilingue développé avec Django. Il permet de gérer et d'afficher des articles de blog en plusieurs langues, avec une interface utilisateur traduisible.

## Prérequis

- Python 3.x
- Django 3.x ou plus récent
- pip (outil de gestion de paquets Python)

## Installation

1. **Cloner le dépôt :**

   git clone https://github.com/sakouri/sitemultilingue.git

Accéder au répertoire du projet :

cd sitemultilingue

Appliquer les migrations de la base de données :

python manage.py migrate

Créer un superutilisateur :

python manage.py createsuperuser

Démarrer le serveur de développement :

python manage.py runserver

Utilisation
Accès à l'interface d'administration :

Accédez à l'interface d'administration pour ajouter des articles de blog :

http://127.0.0.1:8000/admin

Ajouter des articles de blog :

Utilisez l'interface d'administration pour ajouter des articles avec les champs title, content et publication_date.

Accès à la liste des articles de blog :

Accédez à la page principale pour voir la liste des articles de blog :
http://127.0.0.1:8000/
