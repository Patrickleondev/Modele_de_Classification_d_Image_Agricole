# Système de Classification d'Images de Cultures Agricoles

Ce projet utilise l'apprentissage profond pour classifier différentes cultures agricoles, notamment :

- Fruits (Cherry, Lemon, banana, papaya, pineapple)
- Céréales (Pearl_millet, maize, jowar, rice, wheat)
- Épices (clove, cardamom, chilli)
- Cultures industrielles (Tobacco-plant, cotton, jute, sugarcane)
- Oléagineux (mustard-oil, sunflower, soyabean)
- Et plus encore...

## Installation

1. Créer un environnement virtuel :
```bash
python3 -m venv venv
source venv/bin/activate  # Sur Linux/Mac
```

2. Installer les dépendances :
```bash
pip install -r requirements.txt
```

## Utilisation

1. Activer l'environnement virtuel :
```bash
source venv/bin/activate  # Sur Linux/Mac
```

2. Lancer l'application :
```bash
python app.py
```

3. Ouvrir un navigateur et aller à `http://localhost:5000`

## Structure des données

Les images d'entraînement sont organisées dans le dossier `Agricultural-crops` avec un sous-dossier pour chaque type de culture.
