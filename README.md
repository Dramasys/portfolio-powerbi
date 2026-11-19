# Portfolio Power BI - Analyses de données

Ce dépôt présente mes projets d'analyse de données et de Business Intelligence réalisés avec Power BI Desktop, au format projet (.pbip) pour un versionnage propre du modèle et des mesures DAX.

Chaque projet suit la même démarche : cadrage du besoin, maquette Figma, préparation des données, modélisation en étoile, mesures DAX, rapport, sécurité (RLS) et documentation.

---

## Projets

### 1. Baromètre Communauté Data et IA
[![Vue d'ensemble du rapport](https://raw.githubusercontent.com/Dramasys/pbi-ia-kaggle-survey/main/screenshots/01-vue-ensemble.png)](https://github.com/Dramasys/pbi-ia-kaggle-survey)

* **Dépôt :** [pbi-ia-kaggle-survey](https://github.com/Dramasys/pbi-ia-kaggle-survey)
* **Documentation complète :** [PDF](https://github.com/Dramasys/pbi-ia-kaggle-survey/blob/main/docs/pbi-ia-kaggle-survey-documentation.pdf)
* **Sujet :** tendances des outils, salaires et profils de la communauté Kaggle, à partir de l'enquête 2020 à 2022 (70 006 répondants).
* **Réalisé :** préparation des données avec Power Query, modèle en étoile (2 tables de faits, 7 dimensions), mesures DAX, 6 pages de rapport avec fiche pays et info-bulle, sécurité par rôles régionaux (RLS), contrôle de la performance et de l'accessibilité.
* **Statut :** terminé.

### 2. Finance
* **Statut :** en préparation.

### 3. Consommation
* **Statut :** en préparation.

---

## Structure des dépôts
* `data/` : données de référence (les données brutes sont exclues via `.gitignore`).
* `docs/` : cadrage, dictionnaire de données, registre des mesures DAX, guide utilisateur.
* `powerbi/` : fichiers sources du projet Power BI (`.pbip`).
* `figma/` et `theme/` : maquettes, thème JSON du rapport.
* `screenshots/` : captures du rapport.