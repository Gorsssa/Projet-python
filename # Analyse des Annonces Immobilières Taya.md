# Analyse des Annonces Immobilières Tayara


# Analyse des Annonces Immobilières Tayara

## Description
Projet complet d'analyse du marché immobilier tunisien comprenant deux composants principaux :
- Un scraper automatisé pour collecter les données de Tayara.tn
- Un tableau de bord interactif pour visualiser et analyser ces données

## Fonctionnalités

### Partie 1 : Scraping
- Extraction automatique des annonces immobilières
- Collecte des informations détaillées (titre, prix, catégorie, localisation)
- Gestion des erreurs et des timeouts
- Export au format CSV structuré
- Respect des règles de scraping éthique

### Partie 2 : Dashboard
- Visualisation de la distribution des biens par catégorie
- Analyse des prix moyens par type de bien
- Cartographie des annonces par région
- Filtres interactifs pour l'exploration des données
- Interface responsive et moderne

## Structure des Données
Le fichier `annonces_tayara.csv` contient :
- Nom : Titre de l'annonce
- Prix : Prix en Dinars Tunisiens (DT)
- Catégorie : Type de bien immobilier
- Localisation : Ville et timestamp


## Installation

### Prérequis
    
- Python 3.8+
- pip (gestionnaire de paquets Python)
- Navigateur web (Chrome/Firefox)


### Étapes d'installation
1. Cloner le repository
2. Installer les dépendances :
```bash
pip install -r requirements.txt

