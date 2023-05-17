# Etape de réalisation
### Ce code est un résumé d'un projet qui traite de la prédiction du prix des maisons en utilisant le framework TensorFlow pour les réseaux de neurones artificiels. Voici un résumé étape par étape du code :

    Importation des bibliothèques nécessaires pour la visualisation des données : numpy, pandas, matplotlib.pyplot et seaborn.
    Importation du jeu de données à partir d'un fichier CSV.
    Affichage de l'en-tête du jeu de données.
    Affichage de la taille du jeu de données et des variables.
    Affichage des informations sur les données, y compris les types de données et les valeurs manquantes.
    Description statistique du jeu de données, y compris les mesures de tendance centrale et de dispersion.
    Vérification des valeurs manquantes dans le jeu de données.
    Calcul de la corrélation entre les variables et le prix des maisons.
    Visualisation de la relation entre le prix et la superficie habitable.
    Visualisation du nombre de salles de bains.
    Visualisation de la relation entre la longitude, la latitude et le prix.
    Suppression de la variable "id" qui n'est pas utile pour prédire le prix.
    Conversion de la variable "date" au format de date.
    Exploration des données en fonction de l'année de vente.
    Suppression de la variable "zipcode" qui ne sera pas utilisée pour la prédiction.
    Nettoyage des données terminé, passage à l'étape d'entraînement et de test du modèle.
    Conversion des données en tableaux numpy.
    Séparation des données en ensembles d'entraînement et de test à l'aide de la fonction train_test_split.
    Mise à l'échelle des données à l'aide de MinMaxScaler.
    Importation des modules Sequential et Dense de TensorFlow.
    Création d'un modèle séquentiel avec des couches d'entrée, des couches cachées et une couche de sortie.
    Compilation du modèle avec l'optimiseur "adam" et la fonction de perte "mse" (mean squared error).
    Entraînement du modèle sur les données d'entraînement.
    Évaluation du modèle sur les données de test en calculant l'erreur absolue moyenne, l'erreur quadratique moyenne et le score de variance expliqué.
    Affichage des graphiques pour visualiser les performances du modèle et les prédictions par rapport aux valeurs réelles.
