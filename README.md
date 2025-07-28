# Prévision Météorologique avec Régression Logistique

![Logo AIMS](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS2oqpzNfaL-_veUOsyKSrbcAg7m-_s6fYmb38nB_BBtfIxl5vpSKpq3c-9HUB6nyBF_A&usqp=CAU)

Ce dépôt contient un projet d'apprentissage automatique axé sur la prédiction des précipitations ("Rain Tomorrow") en utilisant un modèle de régression logistique. Il s'inscrit dans le cadre de l'exploration des données météorologiques historiques pour des applications prédictives.

## Introduction au Labo

Dans ce laboratoire, nous explorons l'utilisation de techniques d'apprentissage automatique pour analyser des données météorologiques historiques. L'objectif principal est de construire un modèle capable de prédire s'il pleuvra le jour suivant (`raintomorrow`) en se basant sur diverses caractéristiques météorologiques du jour actuel.

Nous abordons des étapes clés du pipeline d'apprentissage automatique, notamment :
* **Nettoyage et Prétraitement des Données :** Gestion des valeurs manquantes et conversion des types de données.
* **Ingénierie des Caractéristiques :** Création de la variable cible `raintomorrow`.
* **Analyse Exploratoire des Données (EDA) :** Visualisation des distributions des données et analyse des corrélations entre les variables.
* **Construction et Évaluation du Modèle :** Entraînement d'un modèle de régression logistique et évaluation de ses performances à l'aide de métriques telles que la précision et la matrice de confusion.

Ce projet met en lumière l'importance de la science des données pour transformer des données brutes en informations prédictives utiles, un domaine clé étudié à l'**African Institute for Mathematical Sciences (AIMS)**.

## Ensemble de Données

Le projet utilise l'ensemble de données `HistoricalDailyWeatherRecords.csv`, qui contient des enregistrements météorologiques quotidiens. Ce fichier inclut des informations comme la quantité totale de pluie quotidienne, les températures moyennes, maximales et minimales, ainsi que les vitesses de vent.

## Étapes Clés du Projet

Le carnet Jupyter (`LogisticRegression_2025_answers.ipynb` - remplacez par le nom de votre fichier .ipynb) parcourt les étapes suivantes :

1.  **Chargement et Inspection Initiale des Données :** Aperçu de la structure des données.
2.  **Analyse des Valeurs Manquantes :** Identification et quantification des valeurs 'na'.
3.  **Prétraitement des Données et Ingénierie des Caractéristiques :** Conversion des données numériques, création de la variable `raintomorrow` (pluie du lendemain).
4.  **Visualisation des Distributions :** Histograames pour comprendre la répartition des données.
5.  **Analyse des Corrélations :** Matrice de corrélation pour identifier les relations entre les variables.
6.  **Construction du Modèle :** Division des données, standardisation des caractéristiques et entraînement d'un modèle de Régression Logistique.
7.  **Évaluation du Modèle :** Calcul de la précision, de la corrélation des prédictions et affichage de la matrice de confusion.

## Comment Utiliser

Pour exécuter ce projet :

1.  Clonez ce dépôt GitHub.
2.  Assurez-vous d'avoir Python et les bibliothèques nécessaires installés (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`). Vous pouvez les installer via pip :
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```
3.  Placez le fichier `HistoricalDailyWeatherRecords.csv` dans le même répertoire que le carnet Jupyter.
4.  Ouvrez et exécutez le carnet Jupyter (`LogisticRegression_2025_answers.ipynb`) pour suivre les étapes et reproduire l'analyse.

---

**AIMS - Building Science in Africa**
