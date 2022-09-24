# Bloc-n-3-Conversion-Rate-Challenge

# Lien de la vidéo de présentation du projet: 

https://share.vidyard.com/watch/wCARUCE6FMC1vZap4T6U3G?

## Description de l'entreprise 📇

www.datascienceweekly.org est une célèbre newsletter organisée par des data scientists indépendants. Tout le monde peut enregistrer son adresse e-mail sur ce site pour recevoir chaque semaine des actualités sur la science des données et ses applications!

## Projet 🚧

Les data scientists qui ont créé la newsletter souhaitent mieux comprendre le comportement des utilisateurs visitant leur site web. Ils aimeraient savoir s'il est possible de construire un modèle qui prédit si un utilisateur donné s'abonnera à la newsletter, en utilisant seulement quelques informations sur l'utilisateur. Ils aimeraient analyser les paramètres du modèle pour mettre en évidence des fonctionnalités importantes pour expliquer le comportement des utilisateurs, et peut-être découvrir un nouveau levier d'action pour améliorer le taux de conversion de la newsletter.

Ils ont conçu un concours visant à construire un modèle permettant de prédire les conversions (c'est-à-dire quand un utilisateur s'abonnera à la newsletter). Pour ce faire, ils ont ouvert un ensemble de données contenant des données sur le trafic sur leur site Web. Pour évaluer le classement des différentes équipes en compétition, ils ont décidé d'utiliser le f1-score .


## Description d'un défi de machine learning 🚴🚴

Dans les défis d'apprentissage automatique, le jeu de données est toujours séparé en deux fichiers :

data_train.csv contient des données étiquetées , ce qui signifie qu'il y a à la fois X (variables explicatives) et Y (la cible à prédire). Vous utiliserez ce fichier pour entraîner votre modèle comme d'habitude : faire le split train/test, pré-traitements, évaluer les performances, essayer différents modèles, affiner les hyperparamètres etc...

data_test.csv contient de "nouveaux" exemples qui n'ont pas été utilisés pour former le modèle, dans le même format que dans data_train.csv mais sans étiquette , ce qui signifie que la cible Y a été supprimée du fichier. Une fois que vous avez formé un modèle, vous utiliserez data_test.csv pour faire des prédictions que vous enverrez à l'équipe organisatrice. Ils pourront alors évaluer les performances de votre modèle de manière indépendante, en prévenant la triche 🤸

Et on retrouve par ailleurs un fichier contenant les prédictions finales:

conversion_data_test_predictions.csv est le fichier data_test.csv avec la prédiction représentée par la  **colonne :converted_by_logistic_regression** et réalisée par un modèle de machine learning.
