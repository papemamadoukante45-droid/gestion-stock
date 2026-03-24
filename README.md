# Application de Gestion de Stock

Application mobile de gestion de stock développée avec Flutter et Django.

## Fonctionnalités
- Authentification des utilisateurs
- Gestion des produits (ajout, modification, suppression)
- Upload d'images pour les produits
- Interface utilisateur intuitive

## Écrans
1. Écran de connexion
2. Tableau de bord
3. Liste des produits
4. Ajouter un produit
5. Détail d'un produit

## Technologies utilisées
- **Backend** : Django, Django REST Framework, JWT
- **Frontend** : Flutter
- **Base de données** : SQLite

## Installation

### Backend
```bash
cd gestion_stock
python -m venv venv
venv\Scripts\activate  # Sur Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver







cd gestion_stock_frontend
flutter pub get
flutter run
