# TaskLab TWIN2 — Projet fil rouge
Projet pédagogique Django couvrant les chapitres VIII à XII du Génie Logiciel.

## Installation
```bash
python -m venv .venv
# Windows PowerShell : .venv\\Scripts\\Activate.ps1
# Linux/macOS : source .venv/bin/activate
pip install -r requirements.txt
python manage.py makemigrations taches
python manage.py migrate
python manage.py runserver
```
Accès : http://127.0.0.1:8000/ ; admin : /admin/ (créer un superuser si besoin).

## Tests
`python manage.py test`

## Travail à réaliser
Consultez le document du TP associé pour le détail des tâches. Ce projet de départ est volontairement incomplet :
il ne comprend pas encore de filtre par statut, comporte peu de tests et ne définit pas de version de livraison.
Ne jamais publier une clé SECRET_KEY de production ; DEBUG=False en production.
