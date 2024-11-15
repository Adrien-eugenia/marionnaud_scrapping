# marionnaud_scrapping
Scrapping marionnaud website (Perfume for female)
# 🕵️‍♀️ Projet Python de Scraping - Marionnaud Parfums

### 📋 Description
Ce projet extrait des données sur les **parfums pour femmes** depuis le site de **Marionnaud** en utilisant Python et le scraping. Il est conçu pour collecter les informations essentielles (catégorie, marque, nom, quantité, et prix) des produits dans les catégories suivantes : 
- Eau de Parfum
- Eau de Toilette
- Eau de Cologne

Les données collectées sont exportées dans des fichiers JSON et CSV, et un fichier Google Sheet est généré pour analyse.

---

## 🚀 Fonctionnalités

- **Extraction automatique des liens des pages produits**
- **Filtrage par catégories d'intérêt** pour ne garder que les parfums pertinents
- **Scraping détaillé des informations produits** : catégorie, marque, nom, quantité, prix
- **Stockage des données** dans des fichiers JSON et CSV pour faciliter les analyses
- **Exportation vers Google Sheet** pour analyser et visualiser les données

---

## 📁 Structure des Fichiers de Sortie

- **`page_links.json`** : Contient les liens de chaque page de la catégorie.
- **`parfum_links.json`** : Stocke les liens des parfums filtrés par catégorie.
- **`parfum_data.json`** : Enregistre les informations complètes de chaque parfum.
- **`parfums_info_marketplace.csv`** : Fichier CSV final pour analyse sur un tableur ou importation en base de données.

---

## 🛠️ Utilisation

### Prérequis


## 🛠️ Instructions Détaillées

### Étape 1 : Installation des Prérequis
Avant de commencer, assurez-vous d’avoir Python installé sur votre machine ainsi que les bibliothèques nécessaires. Installez-les avec :
```bash
pip install requests beautifulsoup4
