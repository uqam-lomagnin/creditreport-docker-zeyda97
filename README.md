# MGL7811 - German Credit Report

## Auteur
Sokhna Mariame Ndour

## Description
Ce projet permet d'exécuter le notebook `MGL7811_GermanCreditReport` dans un environnement Docker. Les données utilisées pour l'analyse proviennent d'une base de données NoSQL (MongoDB).

## Architecture
L'architecture choisie repose sur Docker Compose pour orchestrer deux services :
- Un service **Jupyter Notebook** pour exécuter les analyses et visualisations.
- Un service **MongoDB** pour stocker les données sous forme de documents JSON.

L'utilisation de MongoDB permet une manipulation facile des données dans un environnement Python.

## Instructions d'installation
1. Cloner le dépôt GitHub :

    ```bash
    git clone https://github.com/votre-utilisateur/projet-mgl7811.git
    ```

2. Se déplacer dans le répertoire du projet :

    ```bash
    cd MGL720
    ```

3. Démarrer les services Docker :

    ```bash
    docker-compose up --build
    ```

4. Accéder à Jupyter Notebook via l'URL suivante :

    ```bash
    http://127.0.0.1:8888/notebooks/mgl7811-germancreditreport.ipynb
    ```

## Notes importantes
- Le dataset est chargé dans MongoDB et accessible via l'adresse `mongo:27017`.
- Assurez-vous de bien respecter la structure des fichiers pour faciliter la reproduction de l'environnement.
