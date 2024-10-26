# Projet réécriture du site *La Cour de l'Imaginaire*

Ce projet est un exercice visant à imaginer un redesign du site [*La Cour de l'Imaginaire*](http://www.lacourdelimaginaire.com/), collectif de passionnés de l'imaginaire visant à aider et publier des auteurs du genre.

Le but est d'entraîner mes compétences en création de sites internet à trois niveaux :
- Back (Django)
- Front (CSS vanilla, javascript)
- Expérience utilisateurs (UX, accessibilité par l'adoption de bonnes pratiques HTML).

J'ai choisi le site de *La Cour de l'Imaginaire* pour sa simplicité, et dans l'espoir sans doute arrogant que cette réimagination plairait aux auteurs d'origine.

## Installer le projet en local

Pour installer le projet, rien de plus simple !

D'abord, téléchargez-le. Ensuite, installez [Python](https://www.python.org/) si votre ordinateur ne l'a pas déjà.

Rendez-vous dans le dossier contenant le projet. Avec l'invite de commande, lancez-y la commande suivante :

> python -m venv venv

Sur Linux ou Mac, tapez ensuite :

> source venv/bin/activate

Sur Microsoft : 

> venv\Scripts\activate.bat

Votre environnement virtuel est maintenant activé. Installez les paquets nécessaires avec la commande :

> pip install -r requirements.txt

Le site est maintenant installé. Ne reste plus qu'à le lancer.

Naviguez dans le dossier contenant le fichier `manage.py` si ce n'est pas le même. Lancez la commande suivante :

> python manage.py makemigrations
> python manage.py migrate

Le site vous demandera de créer un superuser, ce qui vous permettra d'accéder à la partie administrative du site. Exécutez-vous.

Le site est maintenant installé !

## Lancer le projet

Pour lancer le projet, vérifiez que votre environnement est bien activé dans votre invite de commande (si oui, les mots `(venv)` précéderont la ligne de texte dans votre invite de commande). S'il ne l'est pas, utilisez l'invite de commande pour naviguer dans le dossier contenant le projet et le dossier `venv`.

Sur Linux ou Mac, tapez ensuite :

> source venv/bin/activate

Sur Microsoft : 

> venv\Scripts\activate.bat

Naviguez dans le dossier contenant le fichier `manage.py` si ce n'est pas le même. Lancez la commande suivante :

> python manage.py runserver

Vous avez vaincu !

## Crédit

L'icône du site (le château) appartient à [freepik](https://www.freepik.com/).