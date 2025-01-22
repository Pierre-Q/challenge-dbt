# 🚀 Défi de Transformation de Données avec DBT

Bienvenue dans ce dépôt dédié à l'apprentissage de **DBT (Data Build Tool)**, un outil puissant pour gérer les transformations de données dans un processus ELT (Extract, Load, Transform).

---

## 🎯 Objectifs

- 📌 Comprendre l'importance de DBT pour les transformations de données.
- 📌 Installer et configurer DBT Core localement.
- 📌 Explorer les composants d'un projet DBT.

---

## 🗂️ Contenu du dépôt

Ce dépôt contient :

- **Structure DBT** : Les fichiers et dossiers générés par la commande `dbt init`.
- **Configuration** : `dbt_project.yml` : Fichier de configuration global du projet.
- **Base de données MySQL** : Un script Python pour importer les données brutes dans une base MySQL en utilisant SQLAlchemy.

---

## 🛠️ Mise en place du projet

### 1. Pré-requis

- **Python** : Assurez-vous qu'il est installé sur votre machine.
- **MySQL** : Installez et configurez une instance locale.
- **DBT Core** : Installez-le dans un environnement virtuel Python.

### 2. Installation

1. Créez un environnement virtuel Python :
   ```bash
   python -m venv my-dbt-env
   source my-dbt-env/bin/activate  # Mac/Linux
   .\my-dbt-env\Scripts\activate  # Windows

2. Installez DBT Core et le connecteur MySQL :
   ```bash
   pip install dbt-core
   pip install dbt-mysql
   
3. Initialisez un nouveau projet DBT :
   ```bash
   dbt init projet_dbt

4. Configurez le fichier `profiles.yml` pour se connecter à votre base de données MySQL.

---

## 🔗 Liens utiles

- [Documentation DBT](https://docs.getdbt.com/)
- [Téléchargement de MySQL](https://dev.mysql.com/downloads/)
- [Documentation SQLAlchemy](https://docs.sqlalchemy.org/)

---

Bonne exploration et apprentissage avec DBT ! 💡