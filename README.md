# Projet IA Explicable - Classification binaire

Le but de ce projet est d'ajouter l'interprétation de la prédiction de sexe à partie d'un prénom d'une personne en utilisant la librairie SHAP. 

## 1. Structure du dossier : 
+ XAI_sexe_pred.ipynb : Notebook Jupyter du projet.
+ dpt2022.csv : les données brutes de démographie sur le site INSEE.
+ data_dpt_model : fichier de données nettoyées, à utiliser pou construire le modèle d'apprentissage. 

## 2. Librairies utilisées
+ matplotlib/seaborn : visualisation des données
+ pandas : manipulation des données (dataframe)
+ numpy : faire les calculs en math, gestion de type de données (float ou int)
+ unidecode : pour normaliser les prénoms
+ TensorFlow : pour créer le réseau de neurones, l'entraîner et l'évaluer
+ scikit-learn : pour l'encodage des varaibles catégorielles, les métriques pour vérifier la classification binaire
+ difflib : pour trouver les prénoms similaires dans le cas où le prénom testé est mal tapé
+ SHAP : pour interpréter la prédiction du modèle (quelle(s) variable(s) qui sont importantes pour construire le modèle)

## 3. Comment exécuter le projet
+) Etape 1 : clonez le projet par les commandes dans l'ordre suivant : 
```sh
git clone https://github.com/Linhkobe/XAI-.git
```

```sh
cd XAI-
```

+) Etape 2 :
Il y a deux options :
- Si vous voulez exécuter la notebook "from scratch", vous pouvez l'exécuter depuis du premier block "! pip install category_encoders "
- Si vous voulez passer tous les étapes de prétraitement de données, vous pouvez exécuter la notebook à partir de la partie "Utiliser les données nettoyées". 
